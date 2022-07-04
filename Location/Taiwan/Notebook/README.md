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

Total: 251

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 36        | 20.69%  |
| Ubuntu 18.04        | 19        | 10.92%  |
| Arch Rolling        | 7         | 4.02%   |
| Ubuntu 22.04        | 6         | 3.45%   |
| Pop!_OS 20.04       | 5         | 2.87%   |
| OpenMandriva 4.2    | 5         | 2.87%   |
| Ubuntu 19.04        | 4         | 2.3%    |
| KDE neon 20.04      | 4         | 2.3%    |
| Ubuntu 21.04        | 3         | 1.72%   |
| Ubuntu 19.10        | 3         | 1.72%   |
| Pop!_OS 21.04       | 3         | 1.72%   |
| Fedora 36           | 3         | 1.72%   |
| Fedora 34           | 3         | 1.72%   |
| Debian Testing      | 3         | 1.72%   |
| Arch                | 3         | 1.72%   |
| Ubuntu 20.10        | 2         | 1.15%   |
| Ubuntu 18.10        | 2         | 1.15%   |
| Ubuntu 16.04        | 2         | 1.15%   |
| Pop!_OS 21.10       | 2         | 1.15%   |
| OpenMandriva 4.50   | 2         | 1.15%   |
| Manjaro 21.2.2      | 2         | 1.15%   |
| Manjaro 21.1.3      | 2         | 1.15%   |
| Manjaro 21.1.0      | 2         | 1.15%   |
| Manjaro 20.1        | 2         | 1.15%   |
| Manjaro 20.0        | 2         | 1.15%   |
| Manjaro 18.0.0      | 2         | 1.15%   |
| Manjaro             | 2         | 1.15%   |
| Linux Mint 20.3     | 2         | 1.15%   |
| Linux Mint 20.1     | 2         | 1.15%   |
| Gentoo 2.7          | 2         | 1.15%   |
| Fedora 35           | 2         | 1.15%   |
| Debian 11           | 2         | 1.15%   |
| Zorin 16            | 1         | 0.57%   |
| Zorin 15            | 1         | 0.57%   |
| Xubuntu 17.10       | 1         | 0.57%   |
| Ubuntu Studio 20.04 | 1         | 0.57%   |
| Ubuntu MATE 20.04   | 1         | 0.57%   |
| Ubuntu MATE 18.04   | 1         | 0.57%   |
| Ubuntu 17.10        | 1         | 0.57%   |
| OpenMandriva 4.3    | 1         | 0.57%   |
| Manjaro 21.2.5      | 1         | 0.57%   |
| Manjaro 21.2.4      | 1         | 0.57%   |
| Manjaro 21.1.6      | 1         | 0.57%   |
| Manjaro 21.1.2      | 1         | 0.57%   |
| Manjaro 21.0.6      | 1         | 0.57%   |
| Manjaro 20.2        | 1         | 0.57%   |
| Manjaro 20.1.2      | 1         | 0.57%   |
| Lubuntu 21.10       | 1         | 0.57%   |
| Lubuntu 18.04       | 1         | 0.57%   |
| Linux Mint 20       | 1         | 0.57%   |
| Linux Mint 19.3     | 1         | 0.57%   |
| Linux Mint 19.2     | 1         | 0.57%   |
| Kubuntu 22.04       | 1         | 0.57%   |
| Kubuntu 20.04       | 1         | 0.57%   |
| Kali 2020.2         | 1         | 0.57%   |
| Fedora 33           | 1         | 0.57%   |
| Fedora 31           | 1         | 0.57%   |
| Fedora 30           | 1         | 0.57%   |
| Endless 3.9.4       | 1         | 0.57%   |
| Endless 3.8.4       | 1         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 75        | 45.18%  |
| Manjaro       | 19        | 11.45%  |
| Pop!_OS       | 10        | 6.02%   |
| Fedora        | 10        | 6.02%   |
| Arch          | 10        | 6.02%   |
| OpenMandriva  | 8         | 4.82%   |
| Linux Mint    | 6         | 3.61%   |
| Debian        | 6         | 3.61%   |
| KDE neon      | 4         | 2.41%   |
| Zorin         | 2         | 1.2%    |
| Ubuntu MATE   | 2         | 1.2%    |
| Lubuntu       | 2         | 1.2%    |
| Kubuntu       | 2         | 1.2%    |
| Gentoo        | 2         | 1.2%    |
| Endless       | 2         | 1.2%    |
| Xubuntu       | 1         | 0.6%    |
| Ubuntu Studio | 1         | 0.6%    |
| Kali          | 1         | 0.6%    |
| EndeavourOS   | 1         | 0.6%    |
| Elementary    | 1         | 0.6%    |
| CentOS        | 1         | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 5         | 2.76%   |
| 5.8.0-7630-generic       | 3         | 1.66%   |
| 5.4.0-42-generic         | 3         | 1.66%   |
| 5.3.0-46-generic         | 3         | 1.66%   |
| 5.3.0-40-generic         | 3         | 1.66%   |
| 5.11.0-25-generic        | 3         | 1.66%   |
| 5.8.10-arch1-1           | 2         | 1.1%    |
| 5.8.0-53-generic         | 2         | 1.1%    |
| 5.8.0-43-generic         | 2         | 1.1%    |
| 5.4.64-1-MANJARO         | 2         | 1.1%    |
| 5.4.0-52-generic         | 2         | 1.1%    |
| 5.4.0-26-generic         | 2         | 1.1%    |
| 5.16.11-2-MANJARO        | 2         | 1.1%    |
| 5.13.15-1-MANJARO        | 2         | 1.1%    |
| 5.13.0-30-generic        | 2         | 1.1%    |
| 5.11.0-7620-generic      | 2         | 1.1%    |
| 5.11.0-43-generic        | 2         | 1.1%    |
| 5.11.0-27-generic        | 2         | 1.1%    |
| 5.10.0-8-amd64           | 2         | 1.1%    |
| 4.18.0-17-generic        | 2         | 1.1%    |
| 4.18.0-15-generic        | 2         | 1.1%    |
| 4.15.0-47-generic        | 2         | 1.1%    |
| 4.15.0-43-generic        | 2         | 1.1%    |
| 5.9.16-200.fc33.x86_64   | 1         | 0.55%   |
| 5.9.0-4-amd64            | 1         | 0.55%   |
| 5.8.3-2-MANJARO          | 1         | 0.55%   |
| 5.8.18-1-MANJARO         | 1         | 0.55%   |
| 5.8.16-2-MANJARO         | 1         | 0.55%   |
| 5.8.0-59-generic         | 1         | 0.55%   |
| 5.8.0-49-generic         | 1         | 0.55%   |
| 5.8.0-44-generic         | 1         | 0.55%   |
| 5.8.0-36-generic         | 1         | 0.55%   |
| 5.8.0-29-generic         | 1         | 0.55%   |
| 5.8.0-14-generic         | 1         | 0.55%   |
| 5.7.8-arch1-1            | 1         | 0.55%   |
| 5.7.4-arch1-1            | 1         | 0.55%   |
| 5.7.11-arch1-1           | 1         | 0.55%   |
| 5.7.1-custom             | 1         | 0.55%   |
| 5.7.1-050701-generic     | 1         | 0.55%   |
| 5.7.0-3-MANJARO          | 1         | 0.55%   |
| 5.7.0-2-amd64            | 1         | 0.55%   |
| 5.6.7-1-MANJARO          | 1         | 0.55%   |
| 5.6.3-arch1-1            | 1         | 0.55%   |
| 5.6.15-zen2-1-zen        | 1         | 0.55%   |
| 5.6.0-1008-oem           | 1         | 0.55%   |
| 5.4.35-1-MANJARO         | 1         | 0.55%   |
| 5.4.0-88-generic         | 1         | 0.55%   |
| 5.4.0-84-generic         | 1         | 0.55%   |
| 5.4.0-7642-generic       | 1         | 0.55%   |
| 5.4.0-7634-generic       | 1         | 0.55%   |
| 5.4.0-74-generic         | 1         | 0.55%   |
| 5.4.0-70-generic         | 1         | 0.55%   |
| 5.4.0-66-generic         | 1         | 0.55%   |
| 5.4.0-58-generic         | 1         | 0.55%   |
| 5.4.0-48-generic         | 1         | 0.55%   |
| 5.4.0-40-generic         | 1         | 0.55%   |
| 5.4.0-39-generic         | 1         | 0.55%   |
| 5.4.0-37-generic         | 1         | 0.55%   |
| 5.4.0-29-generic         | 1         | 0.55%   |
| 5.4.0-19-generic         | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 11.86%  |
| 5.8.0   | 13        | 7.34%   |
| 5.11.0  | 13        | 7.34%   |
| 5.13.0  | 11        | 6.21%   |
| 4.18.0  | 9         | 5.08%   |
| 4.15.0  | 9         | 5.08%   |
| 5.3.0   | 7         | 3.95%   |
| 5.0.0   | 7         | 3.95%   |
| 5.10.14 | 5         | 2.82%   |
| 5.10.0  | 5         | 2.82%   |
| 5.15.0  | 4         | 2.26%   |
| 5.16.11 | 3         | 1.69%   |
| 5.14.0  | 3         | 1.69%   |
| 5.8.10  | 2         | 1.13%   |
| 5.7.1   | 2         | 1.13%   |
| 5.7.0   | 2         | 1.13%   |
| 5.4.64  | 2         | 1.13%   |
| 5.18.7  | 2         | 1.13%   |
| 5.17.5  | 2         | 1.13%   |
| 5.15.21 | 2         | 1.13%   |
| 5.15.16 | 2         | 1.13%   |
| 5.13.15 | 2         | 1.13%   |
| 5.9.16  | 1         | 0.56%   |
| 5.9.0   | 1         | 0.56%   |
| 5.8.3   | 1         | 0.56%   |
| 5.8.18  | 1         | 0.56%   |
| 5.8.16  | 1         | 0.56%   |
| 5.7.8   | 1         | 0.56%   |
| 5.7.4   | 1         | 0.56%   |
| 5.7.11  | 1         | 0.56%   |
| 5.6.7   | 1         | 0.56%   |
| 5.6.3   | 1         | 0.56%   |
| 5.6.15  | 1         | 0.56%   |
| 5.6.0   | 1         | 0.56%   |
| 5.4.35  | 1         | 0.56%   |
| 5.2.6   | 1         | 0.56%   |
| 5.18.6  | 1         | 0.56%   |
| 5.17.13 | 1         | 0.56%   |
| 5.16.7  | 1         | 0.56%   |
| 5.16.19 | 1         | 0.56%   |
| 5.16.18 | 1         | 0.56%   |
| 5.16.0  | 1         | 0.56%   |
| 5.15.6  | 1         | 0.56%   |
| 5.15.34 | 1         | 0.56%   |
| 5.15.32 | 1         | 0.56%   |
| 5.15.28 | 1         | 0.56%   |
| 5.15.17 | 1         | 0.56%   |
| 5.15.15 | 1         | 0.56%   |
| 5.15.12 | 1         | 0.56%   |
| 5.15.11 | 1         | 0.56%   |
| 5.14.14 | 1         | 0.56%   |
| 5.14.10 | 1         | 0.56%   |
| 5.13.9  | 1         | 0.56%   |
| 5.13.13 | 1         | 0.56%   |
| 5.13.12 | 1         | 0.56%   |
| 5.12.9  | 1         | 0.56%   |
| 5.12.7  | 1         | 0.56%   |
| 5.12.4  | 1         | 0.56%   |
| 5.11.7  | 1         | 0.56%   |
| 5.11.5  | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 24        | 13.64%  |
| 5.8     | 18        | 10.23%  |
| 5.13    | 16        | 9.09%   |
| 5.15    | 15        | 8.52%   |
| 5.11    | 15        | 8.52%   |
| 5.10    | 15        | 8.52%   |
| 4.18    | 9         | 5.11%   |
| 4.15    | 9         | 5.11%   |
| 5.0     | 8         | 4.55%   |
| 5.7     | 7         | 3.98%   |
| 5.3     | 7         | 3.98%   |
| 5.16    | 7         | 3.98%   |
| 5.14    | 5         | 2.84%   |
| 5.6     | 4         | 2.27%   |
| 5.18    | 3         | 1.7%    |
| 5.17    | 3         | 1.7%    |
| 5.12    | 3         | 1.7%    |
| 5.9     | 2         | 1.14%   |
| 5.2     | 1         | 0.57%   |
| 4.19    | 1         | 0.57%   |
| 4.14    | 1         | 0.57%   |
| 4.13    | 1         | 0.57%   |
| 4.10    | 1         | 0.57%   |
| 3.10    | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 159       | 98.15%  |
| i686   | 3         | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 81        | 47.37%  |
| Unknown         | 32        | 18.71%  |
| KDE5            | 25        | 14.62%  |
| XFCE            | 6         | 3.51%   |
| X-Cinnamon      | 5         | 2.92%   |
| MATE            | 5         | 2.92%   |
| KDE             | 5         | 2.92%   |
| LXQt            | 2         | 1.17%   |
| i3              | 2         | 1.17%   |
| GNOME Flashback | 2         | 1.17%   |
| Deepin          | 2         | 1.17%   |
| Unity           | 1         | 0.58%   |
| sway            | 1         | 0.58%   |
| Pantheon        | 1         | 0.58%   |
| LXDE            | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 129       | 77.71%  |
| Wayland | 17        | 10.24%  |
| Unknown | 17        | 10.24%  |
| Tty     | 3         | 1.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 48.21%  |
| GDM     | 32        | 19.05%  |
| SDDM    | 27        | 16.07%  |
| GDM3    | 12        | 7.14%   |
| LightDM | 10        | 5.95%   |
| TDM     | 4         | 2.38%   |
| SLiM    | 2         | 1.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 75        | 44.64%  |
| zh_TW   | 50        | 29.76%  |
| Unknown | 27        | 16.07%  |
| zh_CN   | 3         | 1.79%   |
| ru_RU   | 3         | 1.79%   |
| en_GB   | 2         | 1.19%   |
| zh_SG   | 1         | 0.6%    |
| lzh_TW  | 1         | 0.6%    |
| ja_JP   | 1         | 0.6%    |
| en_SG   | 1         | 0.6%    |
| en_IE   | 1         | 0.6%    |
| de_DE   | 1         | 0.6%    |
| C.UTF8  | 1         | 0.6%    |
| C       | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 99        | 60.37%  |
| BIOS | 65        | 39.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 140       | 85.37%  |
| Overlay | 7         | 4.27%   |
| Xfs     | 5         | 3.05%   |
| Btrfs   | 5         | 3.05%   |
| Unknown | 4         | 2.44%   |
| Ext2    | 2         | 1.22%   |
| F2fs    | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 51.53%  |
| GPT     | 65        | 39.88%  |
| MBR     | 14        | 8.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 145       | 88.41%  |
| Yes       | 19        | 11.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 59.51%  |
| Yes       | 66        | 40.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer                 | 33        | 20.37%  |
| ASUSTek Computer     | 30        | 18.52%  |
| Hewlett-Packard      | 22        | 13.58%  |
| Lenovo               | 21        | 12.96%  |
| Dell                 | 17        | 10.49%  |
| MSI                  | 14        | 8.64%   |
| Sony                 | 3         | 1.85%   |
| Unknown              | 3         | 1.85%   |
| Toshiba              | 2         | 1.23%   |
| Lex                  | 2         | 1.23%   |
| Apple                | 2         | 1.23%   |
| win element          | 1         | 0.62%   |
| Vizio                | 1         | 0.62%   |
| Samsung Electronics  | 1         | 0.62%   |
| NEXCOM               | 1         | 0.62%   |
| LG Electronics       | 1         | 0.62%   |
| Intel Client Systems | 1         | 0.62%   |
| Intel                | 1         | 0.62%   |
| HUAWEI               | 1         | 0.62%   |
| Gigabyte Technology  | 1         | 0.62%   |
| CJSCOPE              | 1         | 0.62%   |
| AVITA                | 1         | 0.62%   |
| AMI                  | 1         | 0.62%   |
| AMD                  | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 3.09%   |
| MSI GS63 7RE                             | 2         | 1.23%   |
| Lex 3I610DW                              | 2         | 1.23%   |
| HP Pavilion dv7                          | 2         | 1.23%   |
| Dell XPS 13 9380                         | 2         | 1.23%   |
| Acer Swift SF514-52T                     | 2         | 1.23%   |
| Acer Aspire 4755                         | 2         | 1.23%   |
| win element MBOX                         | 1         | 0.62%   |
| Vizio CT14                               | 1         | 0.62%   |
| Toshiba Satellite L850                   | 1         | 0.62%   |
| Toshiba PORTEGE R830                     | 1         | 0.62%   |
| Sony VPCCB15FW                           | 1         | 0.62%   |
| Sony SVS15115FWB                         | 1         | 0.62%   |
| Sony SVP13229PWB                         | 1         | 0.62%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B      | 1         | 0.62%   |
| NEXCOM B537-I                            | 1         | 0.62%   |
| MSI PE72 8RD                             | 1         | 0.62%   |
| MSI PE62 8RD                             | 1         | 0.62%   |
| MSI PE60 6QE                             | 1         | 0.62%   |
| MSI P65 Creator 9SD                      | 1         | 0.62%   |
| MSI Modern 14 B11M                       | 1         | 0.62%   |
| MSI GV72 8RC                             | 1         | 0.62%   |
| MSI GT63 Titan 9SG                       | 1         | 0.62%   |
| MSI GS76 Stealth 11UH                    | 1         | 0.62%   |
| MSI GL65 9SD                             | 1         | 0.62%   |
| MSI GE70 2PE                             | 1         | 0.62%   |
| MSI GE70 0NC/GE70 0ND                    | 1         | 0.62%   |
| MSI CX62 6QD                             | 1         | 0.62%   |
| LG 16Z90P-G.AA78C                        | 1         | 0.62%   |
| Lenovo Z50-70 20354                      | 1         | 0.62%   |
| Lenovo XiaoXinAir 15ARE 2021 82GL        | 1         | 0.62%   |
| Lenovo V330-15IGM                        | 1         | 0.62%   |
| Lenovo ThinkPad X230 2324CD1             | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS0L800 | 1         | 0.62%   |
| Lenovo ThinkPad T510 4384CJ7             | 1         | 0.62%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 0.62%   |
| Lenovo ThinkPad T440s 20ARS3RM00         | 1         | 0.62%   |
| Lenovo ThinkPad T420s 4171A18            | 1         | 0.62%   |
| Lenovo ThinkPad T410 2537F34             | 1         | 0.62%   |
| Lenovo ThinkPad T410 2518A37             | 1         | 0.62%   |
| Lenovo ThinkPad L14 Gen 1 20U5S02700     | 1         | 0.62%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01Y00     | 1         | 0.62%   |
| Lenovo ThinkPad Edge E531 688534V        | 1         | 0.62%   |
| Lenovo ThinkPad E585 20KVCTO1WW          | 1         | 0.62%   |
| Lenovo ThinkPad 13 2nd Gen 20J1CTO1WW    | 1         | 0.62%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 1         | 0.62%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 0.62%   |
| Lenovo IdeaPad S410 20301                | 1         | 0.62%   |
| Lenovo IdeaPad 5 14ALC05 82LM            | 1         | 0.62%   |
| Lenovo IdeaPad 100-14IBD 80RK            | 1         | 0.62%   |
| Intel Client Systems LAPBC710            | 1         | 0.62%   |
| Intel Aspire One 753                     | 1         | 0.62%   |
| HUAWEI KPRC-WX0                          | 1         | 0.62%   |
| HP ZBook 15 G6                           | 1         | 0.62%   |
| HP ProBook 455 G7                        | 1         | 0.62%   |
| HP ProBook 4310s                         | 1         | 0.62%   |
| HP ProBook 430 G7                        | 1         | 0.62%   |
| HP ProBook 430 G6                        | 1         | 0.62%   |
| HP ProBook 430 G3                        | 1         | 0.62%   |
| HP Pavilion Notebook                     | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Acer Aspire                   | 21        | 12.96%  |
| Lenovo ThinkPad               | 13        | 8.02%   |
| HP Pavilion                   | 7         | 4.32%   |
| Dell Inspiron                 | 6         | 3.7%    |
| Acer Swift                    | 6         | 3.7%    |
| HP ProBook                    | 5         | 3.09%   |
| ASUS VivoBook                 | 5         | 3.09%   |
| ASUS ROG                      | 5         | 3.09%   |
| Unknown                       | 5         | 3.09%   |
| Lenovo IdeaPad                | 4         | 2.47%   |
| ASUS ZenBook                  | 4         | 2.47%   |
| Dell XPS                      | 3         | 1.85%   |
| Dell Vostro                   | 3         | 1.85%   |
| Dell Latitude                 | 3         | 1.85%   |
| Acer TravelMate               | 3         | 1.85%   |
| MSI GS63                      | 2         | 1.23%   |
| MSI GE70                      | 2         | 1.23%   |
| Lex 3I610DW                   | 2         | 1.23%   |
| HP EliteBook                  | 2         | 1.23%   |
| win element MBOX              | 1         | 0.62%   |
| Vizio CT14                    | 1         | 0.62%   |
| Toshiba Satellite             | 1         | 0.62%   |
| Toshiba PORTEGE               | 1         | 0.62%   |
| Sony VPCCB15FW                | 1         | 0.62%   |
| Sony SVS15115FWB              | 1         | 0.62%   |
| Sony SVP13229PWB              | 1         | 0.62%   |
| Samsung 700Z3A                | 1         | 0.62%   |
| NEXCOM B537-I                 | 1         | 0.62%   |
| MSI PE72                      | 1         | 0.62%   |
| MSI PE62                      | 1         | 0.62%   |
| MSI PE60                      | 1         | 0.62%   |
| MSI P65                       | 1         | 0.62%   |
| MSI Modern                    | 1         | 0.62%   |
| MSI GV72                      | 1         | 0.62%   |
| MSI GT63                      | 1         | 0.62%   |
| MSI GS76                      | 1         | 0.62%   |
| MSI GL65                      | 1         | 0.62%   |
| MSI CX62                      | 1         | 0.62%   |
| LG 16Z90P-G.AA78C             | 1         | 0.62%   |
| Lenovo Z50-70                 | 1         | 0.62%   |
| Lenovo XiaoXinAir             | 1         | 0.62%   |
| Lenovo V330-15IGM             | 1         | 0.62%   |
| Lenovo Legion                 | 1         | 0.62%   |
| Intel Client Systems LAPBC710 | 1         | 0.62%   |
| Intel Aspire                  | 1         | 0.62%   |
| HUAWEI KPRC-WX0               | 1         | 0.62%   |
| HP ZBook                      | 1         | 0.62%   |
| HP G62                        | 1         | 0.62%   |
| HP ENVY                       | 1         | 0.62%   |
| HP DevX                       | 1         | 0.62%   |
| HP Compaq                     | 1         | 0.62%   |
| HP 250                        | 1         | 0.62%   |
| HP 15                         | 1         | 0.62%   |
| Gigabyte P65                  | 1         | 0.62%   |
| Dell System                   | 1         | 0.62%   |
| Dell Precision                | 1         | 0.62%   |
| CJSCOPE Z                     | 1         | 0.62%   |
| AVITA NE14A2                  | 1         | 0.62%   |
| ASUS X580VD                   | 1         | 0.62%   |
| ASUS X555LB                   | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 11.11%  |
| 2019 | 17        | 10.49%  |
| 2020 | 16        | 9.88%   |
| 2017 | 16        | 9.88%   |
| 2018 | 15        | 9.26%   |
| 2014 | 12        | 7.41%   |
| 2012 | 11        | 6.79%   |
| 2011 | 11        | 6.79%   |
| 2016 | 9         | 5.56%   |
| 2015 | 9         | 5.56%   |
| 2009 | 7         | 4.32%   |
| 2013 | 6         | 3.7%    |
| 2010 | 5         | 3.09%   |
| 2022 | 4         | 2.47%   |
| 2008 | 4         | 2.47%   |
| 2007 | 1         | 0.62%   |
| 2004 | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 162       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 147       | 90.18%  |
| Enabled  | 16        | 9.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 162       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 31.52%  |
| 16.01-24.0  | 40        | 24.24%  |
| 8.01-16.0   | 29        | 17.58%  |
| 3.01-4.0    | 22        | 13.33%  |
| 32.01-64.0  | 10        | 6.06%   |
| 64.01-256.0 | 5         | 3.03%   |
| 24.01-32.0  | 3         | 1.82%   |
| 2.01-3.0    | 2         | 1.21%   |
| 1.01-2.0    | 1         | 0.61%   |
| 0.51-1.0    | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 54        | 30.86%  |
| 2.01-3.0   | 49        | 28%     |
| 4.01-8.0   | 27        | 15.43%  |
| 3.01-4.0   | 27        | 15.43%  |
| 8.01-16.0  | 8         | 4.57%   |
| 0.51-1.0   | 6         | 3.43%   |
| 24.01-32.0 | 2         | 1.14%   |
| 32.01-64.0 | 1         | 0.57%   |
| 0.01-0.5   | 1         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 103       | 61.68%  |
| 2      | 50        | 29.94%  |
| 3      | 9         | 5.39%   |
| 0      | 3         | 1.8%    |
| 5      | 1         | 0.6%    |
| 4      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 71.6%   |
| Yes       | 46        | 28.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 77.91%  |
| No        | 36        | 22.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 95.06%  |
| No        | 8         | 4.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 87.12%  |
| No        | 21        | 12.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Taiwan  | 162       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Taipei           | 50        | 28.74%  |
| New Taipei       | 28        | 16.09%  |
| Taoyuan District | 21        | 12.07%  |
| Hsinchu          | 17        | 9.77%   |
| Taichung         | 13        | 7.47%   |
| Kaohsiung City   | 10        | 5.75%   |
| Tainan City      | 6         | 3.45%   |
| Hsinchu County   | 4         | 2.3%    |
| Zhudong          | 3         | 1.72%   |
| Yunlin           | 3         | 1.72%   |
| Pingtung City    | 3         | 1.72%   |
| Chang-hua        | 3         | 1.72%   |
| Shulin District  | 2         | 1.15%   |
| Keelung          | 2         | 1.15%   |
| Zhubei           | 1         | 0.57%   |
| Taichung City    | 1         | 0.57%   |
| Penghu County    | 1         | 0.57%   |
| Neihu            | 1         | 0.57%   |
| Nantou City      | 1         | 0.57%   |
| Miaoli           | 1         | 0.57%   |
| Fenjihu          | 1         | 0.57%   |
| Chenggong        | 1         | 0.57%   |
| Bao'an           | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 26        | 34     | 11.71%  |
| Samsung Electronics          | 23        | 34     | 10.36%  |
| Crucial                      | 19        | 23     | 8.56%   |
| Seagate                      | 17        | 19     | 7.66%   |
| Kingston                     | 17        | 23     | 7.66%   |
| SanDisk                      | 15        | 18     | 6.76%   |
| HGST                         | 14        | 15     | 6.31%   |
| Toshiba                      | 12        | 12     | 5.41%   |
| SK hynix                     | 12        | 13     | 5.41%   |
| Unknown                      | 9         | 10     | 4.05%   |
| Intel                        | 7         | 7      | 3.15%   |
| Micron Technology            | 6         | 6      | 2.7%    |
| Hitachi                      | 6         | 6      | 2.7%    |
| Transcend                    | 3         | 3      | 1.35%   |
| JMicron Technology           | 3         | 6      | 1.35%   |
| ASMT                         | 3         | 3      | 1.35%   |
| A-DATA Technology            | 3         | 3      | 1.35%   |
| SPCC                         | 2         | 3      | 0.9%    |
| AGI                          | 2         | 2      | 0.9%    |
| Unknown                      | 2         | 2      | 0.9%    |
| ZHITAI                       | 1         | 1      | 0.45%   |
| Yangtze Memory Technologies  | 1         | 1      | 0.45%   |
| USB3.2                       | 1         | 1      | 0.45%   |
| Union Memory                 | 1         | 1      | 0.45%   |
| Toshiba America Info Systems | 1         | 2      | 0.45%   |
| StoreJet                     | 1         | 2      | 0.45%   |
| Silicon Motion               | 1         | 1      | 0.45%   |
| Plextor                      | 1         | 1      | 0.45%   |
| Pioneer                      | 1         | 1      | 0.45%   |
| OCZ                          | 1         | 1      | 0.45%   |
| NeoTech                      | 1         | 1      | 0.45%   |
| MX                           | 1         | 1      | 0.45%   |
| Micron/Crucial Technology    | 1         | 1      | 0.45%   |
| LITEONIT                     | 1         | 1      | 0.45%   |
| LITEON                       | 1         | 1      | 0.45%   |
| Lite-On                      | 1         | 1      | 0.45%   |
| KIOXIA                       | 1         | 1      | 0.45%   |
| HGST HTE                     | 1         | 1      | 0.45%   |
| Aura                         | 1         | 1      | 0.45%   |
| Apple                        | 1         | 1      | 0.45%   |
| Apacer                       | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB                    | 7         | 2.99%   |
| HGST HTS721010A9E630 1TB                        | 6         | 2.56%   |
| Seagate ST1000LM049-2GH172 1TB                  | 4         | 1.71%   |
| Seagate ST1000LM035-1RK172 1TB                  | 4         | 1.71%   |
| Unknown MMC Card  64GB                          | 3         | 1.28%   |
| Toshiba MQ01ABD100 1TB                          | 3         | 1.28%   |
| SanDisk NVMe SSD Drive 512GB                    | 3         | 1.28%   |
| SanDisk NVMe SSD Drive 256GB                    | 3         | 1.28%   |
| SanDisk NVMe SSD Drive 1TB                      | 3         | 1.28%   |
| Crucial CT500MX500SSD4 500GB                    | 3         | 1.28%   |
| Crucial CT240BX500SSD1 240GB                    | 3         | 1.28%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                | 2         | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 2         | 0.85%   |
| Unknown MMC Card  32GB                          | 2         | 0.85%   |
| Toshiba MQ04ABF100 1TB                          | 2         | 0.85%   |
| SPCC Solid State Disk 240GB                     | 2         | 0.85%   |
| SK hynix NVMe SSD Drive 512GB                   | 2         | 0.85%   |
| SK hynix HFM512GD3JX013N 512GB                  | 2         | 0.85%   |
| Samsung NVMe SSD Drive 256GB                    | 2         | 0.85%   |
| Samsung NVMe SSD Drive 1024GB                   | 2         | 0.85%   |
| Samsung MZVLW256HEHP-00000 256GB                | 2         | 0.85%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD             | 2         | 0.85%   |
| Kingston SA400S37240G 240GB SSD                 | 2         | 0.85%   |
| Kingston SA400S37120G 120GB SSD                 | 2         | 0.85%   |
| Kingston SA2000M8500G 500GB                     | 2         | 0.85%   |
| Kingston RBUSNS8154P3512GJ1 512GB               | 2         | 0.85%   |
| Kingston NVMe SSD Drive 512GB                   | 2         | 0.85%   |
| HGST HTS541010B7E610 1TB                        | 2         | 0.85%   |
| HGST HTS541010A9E680 1TB                        | 2         | 0.85%   |
| ASMT 2115 128GB                                 | 2         | 0.85%   |
| Unknown                                         | 2         | 0.85%   |
| ZHITAI TiPro7000 1TB                            | 1         | 0.43%   |
| Yangtze Memory NVMe SSD Drive 1TB               | 1         | 0.43%   |
| WDC WDS500G3X0C-00SJG0 500GB                    | 1         | 0.43%   |
| WDC WDS500G2B0B 500GB SSD                       | 1         | 0.43%   |
| WDC WDS500G2B0A 500GB SSD                       | 1         | 0.43%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                  | 1         | 0.43%   |
| WDC WDS200T1X0E-00AFY0 2TB                      | 1         | 0.43%   |
| WDC WDS100T2B0C-00PXH0 1TB                      | 1         | 0.43%   |
| WDC WD7500BPKX-00HPJT0 752GB                    | 1         | 0.43%   |
| WDC WD5000LPCX-00VHAT0 500GB                    | 1         | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB                     | 1         | 0.43%   |
| WDC WD2500BEVT-60ZCT1 250GB                     | 1         | 0.43%   |
| WDC WD1600BEVT-22ZCT0 160GB                     | 1         | 0.43%   |
| WDC WD1600BEVS-60RST0 160GB                     | 1         | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB                        | 1         | 0.43%   |
| WDC WD10SPZX-08Z10 1TB                          | 1         | 0.43%   |
| WDC WD10SPSX-00A6WT0 1TB                        | 1         | 0.43%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB            | 1         | 0.43%   |
| WDC PC SN720 SDAPNTW-512G-1127 512GB            | 1         | 0.43%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB            | 1         | 0.43%   |
| WDC PC SN530 SDBPNPZ-1T00-1114 1TB              | 1         | 0.43%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB            | 1         | 0.43%   |
| WDC PC SN520 SDAPNUW-512G-1102 512GB            | 1         | 0.43%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB            | 1         | 0.43%   |
| USB3.2 FLASH DRIVE 128GB                        | 1         | 0.43%   |
| Unknown UBA2MAC128HIM1-FTG-UGN TW65230003 128GB | 1         | 0.43%   |
| Unknown SU16G  16GB                             | 1         | 0.43%   |
| Unknown SD16G  16GB                             | 1         | 0.43%   |
| Unknown SC32G  32GB                             | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 17        | 18     | 26.56%  |
| HGST               | 14        | 15     | 21.88%  |
| WDC                | 11        | 13     | 17.19%  |
| Toshiba            | 9         | 9      | 14.06%  |
| Hitachi            | 6         | 6      | 9.38%   |
| ASMT               | 3         | 3      | 4.69%   |
| JMicron Technology | 2         | 4      | 3.13%   |
| StoreJet           | 1         | 2      | 1.56%   |
| NeoTech            | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 17        | 20     | 22.97%  |
| Kingston            | 9         | 10     | 12.16%  |
| Samsung Electronics | 7         | 9      | 9.46%   |
| SanDisk             | 6         | 7      | 8.11%   |
| WDC                 | 5         | 7      | 6.76%   |
| Micron Technology   | 4         | 4      | 5.41%   |
| Intel               | 4         | 4      | 5.41%   |
| Transcend           | 3         | 3      | 4.05%   |
| A-DATA Technology   | 3         | 3      | 4.05%   |
| Toshiba             | 2         | 2      | 2.7%    |
| SPCC                | 2         | 3      | 2.7%    |
| SK hynix            | 2         | 2      | 2.7%    |
| Unknown             | 2         | 2      | 2.7%    |
| Plextor             | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 1      | 1.35%   |
| MX                  | 1         | 1      | 1.35%   |
| LITEONIT            | 1         | 1      | 1.35%   |
| LITEON              | 1         | 1      | 1.35%   |
| Aura                | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |
| Apacer              | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 71        | 84     | 33.33%  |
| NVMe    | 66        | 92     | 30.99%  |
| HDD     | 60        | 71     | 28.17%  |
| MMC     | 8         | 9      | 3.76%   |
| Unknown | 8         | 9      | 3.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 147    | 57%     |
| NVMe | 66        | 92     | 33%     |
| SAS  | 12        | 17     | 6%      |
| MMC  | 8         | 9      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 96     | 60.15%  |
| 0.51-1.0   | 46        | 51     | 34.59%  |
| 1.01-2.0   | 4         | 5      | 3.01%   |
| 2.01-3.0   | 1         | 1      | 0.75%   |
| 10.01-20.0 | 1         | 1      | 0.75%   |
| 4.01-10.0  | 1         | 1      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 53        | 31.74%  |
| 101-250        | 51        | 30.54%  |
| 501-1000       | 22        | 13.17%  |
| 1001-2000      | 11        | 6.59%   |
| 1-20           | 9         | 5.39%   |
| 51-100         | 9         | 5.39%   |
| 21-50          | 8         | 4.79%   |
| Unknown        | 2         | 1.2%    |
| More than 3000 | 1         | 0.6%    |
| 2001-3000      | 1         | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 43.2%   |
| 21-50          | 27        | 15.98%  |
| 101-250        | 20        | 11.83%  |
| 51-100         | 20        | 11.83%  |
| 251-500        | 18        | 10.65%  |
| 501-1000       | 8         | 4.73%   |
| Unknown        | 2         | 1.18%   |
| More than 3000 | 1         | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 20%     |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 20%     |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 20%     |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 20%     |
| ASMT 2115 128GB                                | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SK hynix          | 1         | 1      | 20%     |
| Micron Technology | 1         | 1      | 20%     |
| Hitachi           | 1         | 1      | 20%     |
| HGST              | 1         | 1      | 20%     |
| ASMT              | 1         | 1      | 20%     |

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
| HDD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 94        | 149    | 54.97%  |
| Works    | 72        | 111    | 42.11%  |
| Malfunc  | 5         | 5      | 2.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 121       | 59.31%  |
| Samsung Electronics          | 20        | 9.8%    |
| SanDisk                      | 18        | 8.82%   |
| AMD                          | 13        | 6.37%   |
| SK hynix                     | 10        | 4.9%    |
| Kingston Technology Company  | 8         | 3.92%   |
| Toshiba America Info Systems | 3         | 1.47%   |
| Micron/Crucial Technology    | 3         | 1.47%   |
| Micron Technology            | 3         | 1.47%   |
| Yangtze Memory Technologies  | 1         | 0.49%   |
| Union Memory (Shenzhen)      | 1         | 0.49%   |
| Silicon Motion               | 1         | 0.49%   |
| Marvell Technology Group     | 1         | 0.49%   |
| Lite-On Technology           | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 8.1%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 6.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 5.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 5.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 3.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 3.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 3.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 3.81%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 3.33%   |
| SK hynix Gold P31 SSD                                                            | 6         | 2.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 5         | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.38%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 1.9%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.9%    |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.9%    |
| Micron Non-Volatile memory controller                                            | 3         | 1.43%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 1.43%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.43%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.95%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.95%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 2         | 0.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.95%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 0.95%   |
| Yangtze Memory ZHITAI TiPro7000                                                  | 1         | 0.48%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.48%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.48%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.48%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.48%   |
| SK hynix BC511                                                                   | 1         | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.48%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.48%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.48%   |
| Samsung XP941 PCIe SSD                                                           | 1         | 0.48%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.48%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.48%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 0.48%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.48%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.48%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.48%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.48%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 120       | 58.82%  |
| NVMe | 67        | 32.84%  |
| RAID | 15        | 7.35%   |
| IDE  | 2         | 0.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 139       | 85.8%   |
| AMD    | 23        | 14.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz       | 6         | 3.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 5         | 3.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 2.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 2.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 4         | 2.47%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 4         | 2.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 2.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 1.23%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 1.23%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 1.23%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 1.23%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 2         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 1.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 1.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 1.23%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 1.23%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz      | 2         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 1.23%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 2         | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.23%   |
| Intel Celeron CPU 3955U @ 2.00GHz       | 2         | 1.23%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 1.23%   |
| AMD Ryzen 7 4800HS with Radeon Graphics | 2         | 1.23%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 2         | 1.23%   |
| AMD Ryzen 5 5625U with Radeon Graphics  | 2         | 1.23%   |
| Intel Xeon E-2286M CPU @ 2.40GHz        | 1         | 0.62%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz  | 1         | 0.62%   |
| Intel Pentium CPU U5400 @ 1.20GHz       | 1         | 0.62%   |
| Intel Pentium CPU P6300 @ 2.27GHz       | 1         | 0.62%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 0.62%   |
| Intel Pentium CPU N3540 @ 2.16GHz       | 1         | 0.62%   |
| Intel Pentium CPU 4405U @ 2.10GHz       | 1         | 0.62%   |
| Intel Pentium 3558U @ 1.70GHz           | 1         | 0.62%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.62%   |
| Intel Genuine CPU 0000 @ 1.80GHz        | 1         | 0.62%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 0.62%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 0.62%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz        | 1         | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 0.62%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz      | 1         | 0.62%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz      | 1         | 0.62%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 0.62%   |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 1         | 0.62%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 0.62%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 0.62%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 0.62%   |
| Intel Core i7-2675QM CPU @ 2.20GHz      | 1         | 0.62%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 0.62%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz       | 1         | 0.62%   |
| Intel Core i5-7500T CPU @ 2.70GHz       | 1         | 0.62%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 48        | 29.63%  |
| Intel Core i7      | 46        | 28.4%   |
| Other              | 15        | 9.26%   |
| AMD Ryzen 7        | 9         | 5.56%   |
| Intel Core i3      | 7         | 4.32%   |
| Intel Celeron      | 7         | 4.32%   |
| Intel Pentium      | 6         | 3.7%    |
| AMD Ryzen 5        | 5         | 3.09%   |
| Intel Core 2 Duo   | 3         | 1.85%   |
| Intel Atom         | 3         | 1.85%   |
| AMD Ryzen 9        | 3         | 1.85%   |
| Intel Genuine      | 2         | 1.23%   |
| AMD Ryzen 7 PRO    | 2         | 1.23%   |
| Intel Xeon         | 1         | 0.62%   |
| Intel Pentium Dual | 1         | 0.62%   |
| Intel Core 2 Solo  | 1         | 0.62%   |
| AMD Ryzen 3        | 1         | 0.62%   |
| AMD FX             | 1         | 0.62%   |
| AMD Embedded       | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 65        | 40.12%  |
| 2      | 64        | 39.51%  |
| 8      | 17        | 10.49%  |
| 6      | 11        | 6.79%   |
| 1      | 4         | 2.47%   |
| 12     | 1         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 162       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 132       | 81.48%  |
| 1      | 30        | 18.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 160       | 98.77%  |
| 32-bit         | 1         | 0.62%   |
| Unknown        | 1         | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 18.18%  |
| 0x306a9    | 11        | 6.67%   |
| 0x40651    | 10        | 6.06%   |
| 0x206a7    | 10        | 6.06%   |
| 0x806c1    | 9         | 5.45%   |
| 0x806ea    | 7         | 4.24%   |
| 0x906e9    | 6         | 3.64%   |
| 0x806eb    | 6         | 3.64%   |
| 0x20655    | 6         | 3.64%   |
| 0x906ea    | 5         | 3.03%   |
| 0x806e9    | 5         | 3.03%   |
| 0x406e3    | 5         | 3.03%   |
| 0x706e5    | 4         | 2.42%   |
| 0x306d4    | 4         | 2.42%   |
| 0x0a50000c | 4         | 2.42%   |
| 0x506e3    | 3         | 1.82%   |
| 0x08600106 | 3         | 1.82%   |
| 0x906ed    | 2         | 1.21%   |
| 0x806ec    | 2         | 1.21%   |
| 0x706a8    | 2         | 1.21%   |
| 0x6fd      | 2         | 1.21%   |
| 0x406c4    | 2         | 1.21%   |
| 0x306c3    | 2         | 1.21%   |
| 0x1067a    | 2         | 1.21%   |
| 0x08608103 | 2         | 1.21%   |
| 0x906a3    | 1         | 0.61%   |
| 0x806d1    | 1         | 0.61%   |
| 0x706a1    | 1         | 0.61%   |
| 0x506c9    | 1         | 0.61%   |
| 0x406c3    | 1         | 0.61%   |
| 0x40661    | 1         | 0.61%   |
| 0x306a8    | 1         | 0.61%   |
| 0x30678    | 1         | 0.61%   |
| 0x20652    | 1         | 0.61%   |
| 0x106e5    | 1         | 0.61%   |
| 0x106c2    | 1         | 0.61%   |
| 0x10676    | 1         | 0.61%   |
| 0x0a404101 | 1         | 0.61%   |
| 0x08600104 | 1         | 0.61%   |
| 0x08600103 | 1         | 0.61%   |
| 0x08600102 | 1         | 0.61%   |
| 0x08108109 | 1         | 0.61%   |
| 0x08108102 | 1         | 0.61%   |
| 0x06006705 | 1         | 0.61%   |
| 0x06006118 | 1         | 0.61%   |
| 0x06006115 | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 25.31%  |
| Haswell          | 14        | 8.64%   |
| IvyBridge        | 13        | 8.02%   |
| SandyBridge      | 12        | 7.41%   |
| Skylake          | 11        | 6.79%   |
| Westmere         | 10        | 6.17%   |
| TigerLake        | 10        | 6.17%   |
| Zen 3            | 7         | 4.32%   |
| Zen 2            | 7         | 4.32%   |
| IceLake          | 5         | 3.09%   |
| Unknown          | 5         | 3.09%   |
| Silvermont       | 4         | 2.47%   |
| Penryn           | 4         | 2.47%   |
| Broadwell        | 4         | 2.47%   |
| Goldmont plus    | 3         | 1.85%   |
| Excavator        | 3         | 1.85%   |
| Zen+             | 2         | 1.23%   |
| Core             | 2         | 1.23%   |
| Zen              | 1         | 0.62%   |
| Nehalem          | 1         | 0.62%   |
| Goldmont         | 1         | 0.62%   |
| Bonnell          | 1         | 0.62%   |
| Alderlake Hybrid | 1         | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 130       | 56.03%  |
| Nvidia | 64        | 27.59%  |
| AMD    | 38        | 16.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 5.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 5.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 4.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 3.4%    |
| Intel UHD Graphics 620                                                                   | 8         | 3.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.4%    |
| Intel HD Graphics 630                                                                    | 7         | 2.98%   |
| AMD Renoir                                                                               | 7         | 2.98%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 2.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 2.13%   |
| Intel HD Graphics 620                                                                    | 5         | 2.13%   |
| Intel HD Graphics 530                                                                    | 5         | 2.13%   |
| AMD Cezanne                                                                              | 5         | 2.13%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.7%    |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 1.7%    |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.28%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.28%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 1.28%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.28%   |
| Intel HD Graphics 510                                                                    | 3         | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.28%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.28%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.85%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.85%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.85%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.85%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.85%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.85%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.85%   |
| AMD Lucienne                                                                             | 2         | 0.85%   |
| AMD Barcelo                                                                              | 2         | 0.85%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.43%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.43%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.43%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 1         | 0.43%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.43%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.43%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.43%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.43%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.43%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.43%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.43%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.43%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 38.89%  |
| Intel + Nvidia | 56        | 34.57%  |
| 1 x AMD        | 23        | 14.2%   |
| Intel + AMD    | 11        | 6.79%   |
| 1 x Nvidia     | 5         | 3.09%   |
| AMD + Nvidia   | 3         | 1.85%   |
| 2 x AMD        | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 125       | 76.69%  |
| Proprietary | 34        | 20.86%  |
| Unknown     | 4         | 2.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 54.82%  |
| 1.01-2.0   | 29        | 17.47%  |
| 0.01-0.5   | 20        | 12.05%  |
| 3.01-4.0   | 11        | 6.63%   |
| 0.51-1.0   | 8         | 4.82%   |
| 5.01-6.0   | 6         | 3.61%   |
| 7.01-8.0   | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 24.73%  |
| LG Display              | 27        | 14.52%  |
| Chimei Innolux          | 26        | 13.98%  |
| BOE                     | 22        | 11.83%  |
| Samsung Electronics     | 11        | 5.91%   |
| BenQ                    | 6         | 3.23%   |
| Ancor Communications    | 6         | 3.23%   |
| Sharp                   | 5         | 2.69%   |
| Dell                    | 5         | 2.69%   |
| Lenovo                  | 3         | 1.61%   |
| ASUSTek Computer        | 3         | 1.61%   |
| Acer                    | 3         | 1.61%   |
| ViewSonic               | 2         | 1.08%   |
| Philips                 | 2         | 1.08%   |
| PANDA                   | 2         | 1.08%   |
| Eizo                    | 2         | 1.08%   |
| TMX                     | 1         | 0.54%   |
| Sony                    | 1         | 0.54%   |
| Panasonic               | 1         | 0.54%   |
| Olevia                  | 1         | 0.54%   |
| NEX                     | 1         | 0.54%   |
| MStar                   | 1         | 0.54%   |
| LG Philips              | 1         | 0.54%   |
| Goldstar                | 1         | 0.54%   |
| CHR                     | 1         | 0.54%   |
| Chi Mei Optoelectronics | 1         | 0.54%   |
| BOE Technology Group    | 1         | 0.54%   |
| AVX                     | 1         | 0.54%   |
| Apple                   | 1         | 0.54%   |
| AOC                     | 1         | 0.54%   |
| AGT                     | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 2.13%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 1.6%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 1.6%    |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 3         | 1.6%    |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch              | 2         | 1.06%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.06%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 1.06%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO253D 1920x1080 309x174mm 14.0-inch        | 2         | 1.06%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 2         | 1.06%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 520x290mm 23.4-inch | 2         | 1.06%   |
| ViewSonic VX2376 Series VSC3B32 1920x1080 509x286mm 23.0-inch         | 1         | 0.53%   |
| ViewSonic VA2732-FHD VSC0D3A 1920x1080 598x336mm 27.0-inch            | 1         | 0.53%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.53%   |
| Sony TV SNY8200 1920x1080 560x420mm 27.6-inch                         | 1         | 0.53%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 1         | 0.53%   |
| Sharp LQ133M1JW07 SHP1435 1920x1080 294x165mm 13.3-inch               | 1         | 0.53%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.53%   |
| Sharp LCD Monitor SHP14AD 3840x2160 290x170mm 13.2-inch               | 1         | 0.53%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 1         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.53%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.53%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 0.53%   |
| Olevia PnP montor SYN2300 1280x1024 530x290mm 23.8-inch               | 1         | 0.53%   |
| NEX CHIMEI LCD NEX1073 1920x1080 521x293mm 23.5-inch                  | 1         | 0.53%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.53%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.53%   |
| LG Display LP140WH2-TLA2 LGD0211 1366x768 310x174mm 14.0-inch         | 1         | 0.53%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0506 1366x768 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD04CD 1366x768 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0366 1600x900 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD031C 1366x768 345x194mm 15.6-inch           | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 89        | 53.94%  |
| 1366x768 (WXGA)    | 39        | 23.64%  |
| 3840x2160 (4K)     | 8         | 4.85%   |
| 1600x900 (HD+)     | 4         | 2.42%   |
| 2560x1440 (QHD)    | 3         | 1.82%   |
| 2880x1800          | 2         | 1.21%   |
| 2560x1600          | 2         | 1.21%   |
| 1920x1200 (WUXGA)  | 2         | 1.21%   |
| 1680x1050 (WSXGA+) | 2         | 1.21%   |
| 1280x800 (WXGA)    | 2         | 1.21%   |
| 3840x1080          | 1         | 0.61%   |
| 3200x1800 (QHD+)   | 1         | 0.61%   |
| 2560x1080          | 1         | 0.61%   |
| 2288x1287          | 1         | 0.61%   |
| 2256x1504          | 1         | 0.61%   |
| 2048x1152          | 1         | 0.61%   |
| 1680x945           | 1         | 0.61%   |
| 1440x900 (WXGA+)   | 1         | 0.61%   |
| 1280x720 (HD)      | 1         | 0.61%   |
| 1280x1024 (SXGA)   | 1         | 0.61%   |
| 1024x600           | 1         | 0.61%   |
| Unknown            | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 58        | 31.35%  |
| 14      | 33        | 17.84%  |
| 13      | 30        | 16.22%  |
| 24      | 11        | 5.95%   |
| 23      | 10        | 5.41%   |
| 17      | 8         | 4.32%   |
| 27      | 7         | 3.78%   |
| 11      | 5         | 2.7%    |
| 21      | 4         | 2.16%   |
| 12      | 4         | 2.16%   |
| 22      | 3         | 1.62%   |
| 16      | 3         | 1.62%   |
| 18      | 2         | 1.08%   |
| Unknown | 2         | 1.08%   |
| 55      | 1         | 0.54%   |
| 52      | 1         | 0.54%   |
| 34      | 1         | 0.54%   |
| 31      | 1         | 0.54%   |
| 10      | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 108       | 58.7%   |
| 501-600     | 25        | 13.59%  |
| 201-300     | 24        | 13.04%  |
| 351-400     | 10        | 5.43%   |
| 401-500     | 9         | 4.89%   |
| 601-700     | 3         | 1.63%   |
| 1001-1500   | 2         | 1.09%   |
| Unknown     | 2         | 1.09%   |
| 701-800     | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 88.61%  |
| 16/10   | 15        | 9.49%   |
| 3/2     | 1         | 0.63%   |
| 21/9    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 31.52%  |
| 81-90          | 50        | 27.17%  |
| 201-250        | 25        | 13.59%  |
| 71-80          | 14        | 7.61%   |
| 121-130        | 8         | 4.35%   |
| 301-350        | 7         | 3.8%    |
| 51-60          | 5         | 2.72%   |
| 61-70          | 3         | 1.63%   |
| 111-120        | 3         | 1.63%   |
| More than 1000 | 2         | 1.09%   |
| 351-500        | 2         | 1.09%   |
| 251-300        | 2         | 1.09%   |
| 141-150        | 2         | 1.09%   |
| Unknown        | 2         | 1.09%   |
| 41-50          | 1         | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 85        | 46.45%  |
| 101-120       | 42        | 22.95%  |
| 51-100        | 30        | 16.39%  |
| 161-240       | 15        | 8.2%    |
| More than 240 | 7         | 3.83%   |
| 1-50          | 2         | 1.09%   |
| Unknown       | 2         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 129       | 78.66%  |
| 2     | 29        | 17.68%  |
| 0     | 4         | 2.44%   |
| 3     | 2         | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 95        | 35.71%  |
| Realtek Semiconductor    | 79        | 29.7%   |
| Qualcomm Atheros         | 48        | 18.05%  |
| Broadcom                 | 18        | 6.77%   |
| MediaTek                 | 7         | 2.63%   |
| Broadcom Limited         | 5         | 1.88%   |
| Ralink                   | 3         | 1.13%   |
| TP-Link                  | 2         | 0.75%   |
| Edimax Technology        | 2         | 0.75%   |
| ASIX Electronics         | 2         | 0.75%   |
| U-Blox                   | 1         | 0.38%   |
| Marvell Technology Group | 1         | 0.38%   |
| Lenovo                   | 1         | 0.38%   |
| D-Link                   | 1         | 0.38%   |
| ASUSTek Computer         | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 17.94%  |
| Intel Wi-Fi 6 AX200                                               | 12        | 3.99%   |
| Intel Wireless 8265 / 8275                                        | 11        | 3.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 3.32%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.66%   |
| Intel Wireless 7265                                               | 5         | 1.66%   |
| Intel Wireless 7260                                               | 5         | 1.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 1.33%   |
| Intel Wireless 3165                                               | 4         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.33%   |
| Broadcom BCM43225 802.11b/g/n                                     | 4         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1%      |
| Intel Wireless 8260                                               | 3         | 1%      |
| Intel I211 Gigabit Network Connection                             | 3         | 1%      |
| Intel Ethernet Connection I218-LM                                 | 3         | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1%      |
| Intel Centrino Advanced-N 6235                                    | 3         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.66%   |
| Intel Wireless-AC 9260                                            | 2         | 0.66%   |
| Intel Wireless 3160                                               | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.66%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.66%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.66%   |
| U-Blox [u-blox 8]                                                 | 1         | 0.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.33%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.33%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.33%   |
| Ralink RT3091 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 89        | 55.97%  |
| Qualcomm Atheros      | 33        | 20.75%  |
| Broadcom              | 12        | 7.55%   |
| Realtek Semiconductor | 7         | 4.4%    |
| MediaTek              | 7         | 4.4%    |
| Ralink                | 3         | 1.89%   |
| Broadcom Limited      | 3         | 1.89%   |
| Edimax Technology     | 2         | 1.26%   |
| TP-Link               | 1         | 0.63%   |
| D-Link                | 1         | 0.63%   |
| ASUSTek Computer      | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 12        | 7.55%   |
| Intel Wireless 8265 / 8275                                              | 11        | 6.92%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 6.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 4.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 3.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 3.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.14%   |
| Intel Wireless 7265                                                     | 5         | 3.14%   |
| Intel Wireless 7260                                                     | 5         | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 2.52%   |
| Intel Wireless 3165                                                     | 4         | 2.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 2.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.52%   |
| Broadcom BCM43225 802.11b/g/n                                           | 4         | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.89%   |
| Intel Wireless 8260                                                     | 3         | 1.89%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.26%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.26%   |
| Intel Wireless 3160                                                     | 2         | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.26%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.26%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.63%   |
| Ralink RT3091 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.63%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 1         | 0.63%   |
| Intel WiFi Link 5100                                                    | 1         | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.63%   |
| Intel Centrino Wireless-N 135                                           | 1         | 0.63%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.63%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.63%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 0.63%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                | 1         | 0.63%   |
| Edimax 802.11ac WLAN Adapter                                            | 1         | 0.63%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]    | 1         | 0.63%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                  | 1         | 0.63%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 0.63%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 0.63%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 0.63%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                      | 1         | 0.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.63%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.63%   |
| ASUS 802.11ac NIC                                                       | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 75        | 55.15%  |
| Qualcomm Atheros         | 24        | 17.65%  |
| Intel                    | 23        | 16.91%  |
| Broadcom                 | 7         | 5.15%   |
| Broadcom Limited         | 2         | 1.47%   |
| ASIX Electronics         | 2         | 1.47%   |
| TP-Link                  | 1         | 0.74%   |
| Marvell Technology Group | 1         | 0.74%   |
| Lenovo                   | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 38.3%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 7.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 7.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 4.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 2.84%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 2.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 2.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.13%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.42%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 1.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.71%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.71%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.71%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Lenovo USB-C Hub                                                  | 1         | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.71%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.71%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.71%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 54.61%  |
| Ethernet | 127       | 45.04%  |
| Modem    | 1         | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 72.51%  |
| Ethernet | 47        | 27.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 117       | 72.22%  |
| 1     | 44        | 27.16%  |
| 5     | 1         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 151       | 93.21%  |
| Yes  | 11        | 6.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 56.34%  |
| Qualcomm Atheros Communications | 11        | 7.75%   |
| Foxconn / Hon Hai               | 11        | 7.75%   |
| Broadcom                        | 11        | 7.75%   |
| IMC Networks                    | 8         | 5.63%   |
| Lite-On Technology              | 7         | 4.93%   |
| Realtek Semiconductor           | 4         | 2.82%   |
| Ralink                          | 2         | 1.41%   |
| Hewlett-Packard                 | 2         | 1.41%   |
| ASUSTek Computer                | 2         | 1.41%   |
| Apple                           | 2         | 1.41%   |
| Toshiba                         | 1         | 0.7%    |
| Realtek                         | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 32        | 22.54%  |
| Intel Bluetooth Device                                                              | 16        | 11.27%  |
| Intel AX200 Bluetooth                                                               | 12        | 8.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 7.75%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 2.82%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 4         | 2.82%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.11%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.11%   |
| IMC Networks Bluetooth Device                                                       | 3         | 2.11%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 2.11%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 2.11%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.41%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.41%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.41%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.41%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 1.41%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 1.41%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.41%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.7%    |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.7%    |
| Realtek Bluetooth Radio                                                             | 1         | 0.7%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.7%    |
| Intel AX210 Bluetooth                                                               | 1         | 0.7%    |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.7%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.7%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.7%    |
| Broadcom HP Portable Valentine                                                      | 1         | 0.7%    |
| Broadcom Bluetooth Device                                                           | 1         | 0.7%    |
| Broadcom Bluetooth                                                                  | 1         | 0.7%    |
| Broadcom BCM20702A0                                                                 | 1         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.7%    |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 0.7%    |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 137       | 69.54%  |
| AMD                     | 29        | 14.72%  |
| Nvidia                  | 25        | 12.69%  |
| Realtek Semiconductor   | 1         | 0.51%   |
| GN Netcom               | 1         | 0.51%   |
| ESS Technology          | 1         | 0.51%   |
| Dell                    | 1         | 0.51%   |
| Cambridge Silicon Radio | 1         | 0.51%   |
| C-Media Electronics     | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 8.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 4.58%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 4.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 4.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 4.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 3.33%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.25%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.83%   |
| Nvidia Audio device                                                                               | 2         | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.83%   |
| Intel USB PnP Sound Device                                                                        | 2         | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.83%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.42%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.42%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.42%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.42%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.42%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.42%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.42%   |
| ESS Technology Asus USB DAC                                                                       | 1         | 0.42%   |
| Dell AC511 USB SoundBar                                                                           | 1         | 0.42%   |
| Cambridge Silicon Radio Audioengine HD3                                                           | 1         | 0.42%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.42%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.42%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.42%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.42%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 32        | 26.67%  |
| Samsung Electronics | 25        | 20.83%  |
| Kingston            | 16        | 13.33%  |
| Micron Technology   | 15        | 12.5%   |
| Crucial             | 6         | 5%      |
| Unknown             | 5         | 4.17%   |
| Transcend           | 4         | 3.33%   |
| Apacer              | 3         | 2.5%    |
| Ramaxel Technology  | 2         | 1.67%   |
| G-Alantic           | 2         | 1.67%   |
| A-DATA Technology   | 2         | 1.67%   |
| Unknown (ABCD)      | 1         | 0.83%   |
| Unknown (08AE)      | 1         | 0.83%   |
| Patriot             | 1         | 0.83%   |
| Goldkey             | 1         | 0.83%   |
| G.Skill             | 1         | 0.83%   |
| Elpida              | 1         | 0.83%   |
| Avant               | 1         | 0.83%   |
| ASint Technology    | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.29%   |
| Kingston RAM 9905624-033.A00G 8192MB SODIMM DDR4 2400MT/s           | 3         | 2.29%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 1.53%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 1.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.53%   |
| Samsung RAM M471A1K43CB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 1.53%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.53%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s               | 2         | 1.53%   |
| G-Alantic RAM D4SS12161SH26A-C 4GB SODIMM DDR4 2133MT/s             | 2         | 1.53%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s           | 2         | 1.53%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.76%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                    | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 1         | 0.76%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                       | 1         | 0.76%   |
| Unknown RAM Module 1024MB SODIMM DDR2 800MT/s                       | 1         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.76%   |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.76%   |
| Transcend RAM TS512MSK64V6N 4096MB SODIMM DDR3 1600MT/s             | 1         | 0.76%   |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s            | 1         | 0.76%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s               | 1         | 0.76%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s              | 1         | 0.76%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 0.76%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 1600MT/s                      | 1         | 0.76%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.76%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                          | 1         | 0.76%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                    | 1         | 0.76%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                    | 1         | 0.76%   |
| SK hynix RAM Module 1024MB SODIMM DDR2 533MT/s                      | 1         | 0.76%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.76%   |
| SK hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT451S6AFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.76%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 1         | 0.76%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.76%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s           | 1         | 0.76%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 0.76%   |
| SK hynix RAM HMA81GS7CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s          | 1         | 0.76%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s    | 1         | 0.76%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s    | 1         | 0.76%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.76%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 1         | 0.76%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 0.76%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 0.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.76%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s               | 1         | 0.76%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 0.76%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 53        | 54.64%  |
| DDR3    | 23        | 23.71%  |
| LPDDR4  | 11        | 11.34%  |
| LPDDR3  | 7         | 7.22%   |
| DDR2    | 2         | 2.06%   |
| Unknown | 1         | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 80        | 82.47%  |
| Row Of Chips | 15        | 15.46%  |
| DIMM         | 1         | 1.03%   |
| Chip         | 1         | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 42        | 39.62%  |
| 4096  | 36        | 33.96%  |
| 16384 | 16        | 15.09%  |
| 32768 | 6         | 5.66%   |
| 2048  | 4         | 3.77%   |
| 1024  | 2         | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 24        | 24.24%  |
| 2667  | 19        | 19.19%  |
| 1600  | 19        | 19.19%  |
| 2400  | 9         | 9.09%   |
| 2133  | 7         | 7.07%   |
| 4267  | 4         | 4.04%   |
| 1867  | 3         | 3.03%   |
| 1334  | 3         | 3.03%   |
| 4800  | 2         | 2.02%   |
| 4266  | 2         | 2.02%   |
| 800   | 2         | 2.02%   |
| 3733  | 1         | 1.01%   |
| 3266  | 1         | 1.01%   |
| 2000  | 1         | 1.01%   |
| 1066  | 1         | 1.01%   |
| 533   | 1         | 1.01%   |

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
| Chicony Electronics                    | 36        | 26.67%  |
| IMC Networks                           | 19        | 14.07%  |
| Realtek Semiconductor                  | 17        | 12.59%  |
| Quanta                                 | 9         | 6.67%   |
| Acer                                   | 9         | 6.67%   |
| Sunplus Innovation Technology          | 8         | 5.93%   |
| Microdia                               | 7         | 5.19%   |
| Suyin                                  | 5         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.7%    |
| ALi                                    | 3         | 2.22%   |
| Syntek                                 | 2         | 1.48%   |
| Sunplus Technology                     | 2         | 1.48%   |
| Ricoh                                  | 2         | 1.48%   |
| Lite-On Technology                     | 2         | 1.48%   |
| Lenovo                                 | 2         | 1.48%   |
| Apple                                  | 2         | 1.48%   |
| Silicon Motion                         | 1         | 0.74%   |
| Logitech                               | 1         | 0.74%   |
| Google                                 | 1         | 0.74%   |
| Generalplus Technology                 | 1         | 0.74%   |
| Foxconn / Hon Hai                      | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 5.19%   |
| Chicony HD WebCam                                                          | 7         | 5.19%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 3.7%    |
| Chicony Integrated Camera                                                  | 5         | 3.7%    |
| Chicony HP HD Camera                                                       | 5         | 3.7%    |
| Sunplus HD WebCam                                                          | 4         | 2.96%   |
| Quanta HD User Facing                                                      | 4         | 2.96%   |
| IMC Networks Integrated Camera                                             | 4         | 2.96%   |
| Realtek HD WebCam                                                          | 3         | 2.22%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 2.22%   |
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 2.22%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 2.22%   |
| ALi Gateway Webcam                                                         | 3         | 2.22%   |
| Acer HD Webcam                                                             | 3         | 2.22%   |
| Sunplus 1.3M HD WebCam                                                     | 2         | 1.48%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.48%   |
| Realtek USB Camera                                                         | 2         | 1.48%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 1.48%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 1.48%   |
| IMC Networks UVC VGA Webcam                                                | 2         | 1.48%   |
| Chicony USB 2.0 Webcam Device                                              | 2         | 1.48%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.48%   |
| Acer BisonCam, NB Pro                                                      | 2         | 1.48%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.74%   |
| Syntek HP TrueVision HD                                                    | 1         | 0.74%   |
| Suyin UVC 1.3MPixel WebCam                                                 | 1         | 0.74%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 0.74%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 0.74%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.74%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.74%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.74%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.74%   |
| Sunplus HD User Facing                                                     | 1         | 0.74%   |
| Silicon Motion WebCam SC-13HDL11431N                                       | 1         | 0.74%   |
| Ricoh USB2.0 Camera                                                        | 1         | 0.74%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 0.74%   |
| Realtek USB2.0 camera                                                      | 1         | 0.74%   |
| Realtek LG Camera                                                          | 1         | 0.74%   |
| Realtek HP Wide Vision FHD Camera                                          | 1         | 0.74%   |
| Realtek HD Webcam - Realtek                                                | 1         | 0.74%   |
| Realtek Front Camera                                                       | 1         | 0.74%   |
| Quanta VGA WebCam                                                          | 1         | 0.74%   |
| Quanta HP HD Camera                                                        | 1         | 0.74%   |
| Quanta hm1091_techfront                                                    | 1         | 0.74%   |
| Quanta HD Webcam                                                           | 1         | 0.74%   |
| Quanta FHD User Facing                                                     | 1         | 0.74%   |
| Microdia Integrated Webcam                                                 | 1         | 0.74%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 0.74%   |
| Logitech HP Webcam                                                         | 1         | 0.74%   |
| Lite-On Integrated Camera                                                  | 1         | 0.74%   |
| Lite-On HP HD Camera                                                       | 1         | 0.74%   |
| IMC Networks VGA UVC WebCam                                                | 1         | 0.74%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 0.74%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 1         | 0.74%   |
| Google Nexus/Pixel Device (MTP + debug)                                    | 1         | 0.74%   |
| Generalplus GENERAL WEBCAM                                                 | 1         | 0.74%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 22.22%  |
| Synaptics                  | 8         | 22.22%  |
| LighTuning Technology      | 7         | 19.44%  |
| Upek                       | 4         | 11.11%  |
| Elan Microelectronics      | 4         | 11.11%  |
| Shenzhen Goodix Technology | 3         | 8.33%   |
| AuthenTec                  | 2         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 11.11%  |
| Elan ELAN:Fingerprint                                      | 4         | 11.11%  |
| Unknown                                                    | 4         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 8.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 3         | 8.33%   |
| Validity Sensors VFS Fingerprint sensor                    | 2         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 2.78%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.78%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.78%   |
| Synaptics  WBDI Fingerprint Reader - USB 052               | 1         | 2.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 2.78%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2.78%   |
| AuthenTec AES2810                                          | 1         | 2.78%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.78%   |

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
| 0     | 97        | 57.74%  |
| 1     | 56        | 33.33%  |
| 2     | 13        | 7.74%   |
| 4     | 1         | 0.6%    |
| 3     | 1         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 44.44%  |
| Graphics card            | 17        | 20.99%  |
| Chipcard                 | 7         | 8.64%   |
| Camera                   | 5         | 6.17%   |
| Multimedia controller    | 3         | 3.7%    |
| Card reader              | 3         | 3.7%    |
| Bluetooth                | 3         | 3.7%    |
| Net/wireless             | 2         | 2.47%   |
| Net/ethernet             | 2         | 2.47%   |
| Storage/nvme             | 1         | 1.23%   |
| Sound                    | 1         | 1.23%   |
| Communication controller | 1         | 1.23%   |

