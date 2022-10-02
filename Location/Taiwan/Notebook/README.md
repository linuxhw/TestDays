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

Total: 274

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 37        | 19.17%  |
| Ubuntu 18.04        | 19        | 9.84%   |
| Ubuntu 22.04        | 14        | 7.25%   |
| Arch Rolling        | 8         | 4.15%   |
| Pop!_OS 20.04       | 5         | 2.59%   |
| OpenMandriva 4.2    | 5         | 2.59%   |
| Ubuntu 19.04        | 4         | 2.07%   |
| KDE neon 20.04      | 4         | 2.07%   |
| Fedora 36           | 4         | 2.07%   |
| Debian 11           | 4         | 2.07%   |
| Ubuntu 21.04        | 3         | 1.55%   |
| Ubuntu 19.10        | 3         | 1.55%   |
| Pop!_OS 21.04       | 3         | 1.55%   |
| Fedora 34           | 3         | 1.55%   |
| Debian Testing      | 3         | 1.55%   |
| Arch                | 3         | 1.55%   |
| Ubuntu 20.10        | 2         | 1.04%   |
| Ubuntu 18.10        | 2         | 1.04%   |
| Ubuntu 16.04        | 2         | 1.04%   |
| Pop!_OS 21.10       | 2         | 1.04%   |
| OpenMandriva 4.50   | 2         | 1.04%   |
| OpenMandriva 4.3    | 2         | 1.04%   |
| Manjaro 21.2.2      | 2         | 1.04%   |
| Manjaro 21.1.3      | 2         | 1.04%   |
| Manjaro 21.1.0      | 2         | 1.04%   |
| Manjaro 20.1        | 2         | 1.04%   |
| Manjaro 20.0        | 2         | 1.04%   |
| Manjaro 18.0.0      | 2         | 1.04%   |
| Manjaro             | 2         | 1.04%   |
| Linux Mint 20.3     | 2         | 1.04%   |
| Linux Mint 20.1     | 2         | 1.04%   |
| Gentoo 2.7          | 2         | 1.04%   |
| Fedora 35           | 2         | 1.04%   |
| Zorin 16            | 1         | 0.52%   |
| Zorin 15            | 1         | 0.52%   |
| Xubuntu 17.10       | 1         | 0.52%   |
| Xubuntu 16.04       | 1         | 0.52%   |
| Ubuntu Unity 16.04  | 1         | 0.52%   |
| Ubuntu Studio 20.04 | 1         | 0.52%   |
| Ubuntu MATE 20.04   | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 83        | 45.36%  |
| Manjaro          | 19        | 10.38%  |
| Fedora           | 11        | 6.01%   |
| Arch             | 11        | 6.01%   |
| Pop!_OS          | 10        | 5.46%   |
| OpenMandriva     | 9         | 4.92%   |
| Debian           | 8         | 4.37%   |
| Linux Mint       | 6         | 3.28%   |
| KDE neon         | 4         | 2.19%   |
| Zorin            | 2         | 1.09%   |
| Xubuntu          | 2         | 1.09%   |
| Ubuntu MATE      | 2         | 1.09%   |
| Lubuntu          | 2         | 1.09%   |
| Kubuntu          | 2         | 1.09%   |
| Gentoo           | 2         | 1.09%   |
| Endless          | 2         | 1.09%   |
| Ubuntu Unity     | 1         | 0.55%   |
| Ubuntu Studio    | 1         | 0.55%   |
| Ubuntu Budgie    | 1         | 0.55%   |
| org.kde.Platform | 1         | 0.55%   |
| Kali             | 1         | 0.55%   |
| EndeavourOS      | 1         | 0.55%   |
| Elementary       | 1         | 0.55%   |
| CentOS           | 1         | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 5         | 2.5%    |
| 5.8.0-7630-generic       | 3         | 1.5%    |
| 5.4.0-42-generic         | 3         | 1.5%    |
| 5.3.0-46-generic         | 3         | 1.5%    |
| 5.3.0-40-generic         | 3         | 1.5%    |
| 5.15.0-40-generic        | 3         | 1.5%    |
| 5.11.0-25-generic        | 3         | 1.5%    |
| 5.8.10-arch1-1           | 2         | 1%      |
| 5.8.0-53-generic         | 2         | 1%      |
| 5.8.0-43-generic         | 2         | 1%      |
| 5.4.64-1-MANJARO         | 2         | 1%      |
| 5.4.0-52-generic         | 2         | 1%      |
| 5.4.0-26-generic         | 2         | 1%      |
| 5.16.7-desktop-1omv4003  | 2         | 1%      |
| 5.16.11-2-MANJARO        | 2         | 1%      |
| 5.13.15-1-MANJARO        | 2         | 1%      |
| 5.13.0-30-generic        | 2         | 1%      |
| 5.11.0-7620-generic      | 2         | 1%      |
| 5.11.0-43-generic        | 2         | 1%      |
| 5.11.0-41-generic        | 2         | 1%      |
| 5.11.0-27-generic        | 2         | 1%      |
| 5.10.0-8-amd64           | 2         | 1%      |
| 5.10.0-16-amd64          | 2         | 1%      |
| 4.18.0-17-generic        | 2         | 1%      |
| 4.18.0-15-generic        | 2         | 1%      |
| 4.15.0-47-generic        | 2         | 1%      |
| 4.15.0-43-generic        | 2         | 1%      |
| 5.9.16-200.fc33.x86_64   | 1         | 0.5%    |
| 5.9.0-4-amd64            | 1         | 0.5%    |
| 5.8.3-2-MANJARO          | 1         | 0.5%    |
| 5.8.18-1-MANJARO         | 1         | 0.5%    |
| 5.8.16-2-MANJARO         | 1         | 0.5%    |
| 5.8.0-59-generic         | 1         | 0.5%    |
| 5.8.0-49-generic         | 1         | 0.5%    |
| 5.8.0-44-generic         | 1         | 0.5%    |
| 5.8.0-36-generic         | 1         | 0.5%    |
| 5.8.0-29-generic         | 1         | 0.5%    |
| 5.8.0-14-generic         | 1         | 0.5%    |
| 5.7.8-arch1-1            | 1         | 0.5%    |
| 5.7.4-arch1-1            | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 10.77%  |
| 5.8.0   | 13        | 6.67%   |
| 5.11.0  | 13        | 6.67%   |
| 5.15.0  | 11        | 5.64%   |
| 5.13.0  | 11        | 5.64%   |
| 4.18.0  | 9         | 4.62%   |
| 4.15.0  | 9         | 4.62%   |
| 5.3.0   | 7         | 3.59%   |
| 5.10.0  | 7         | 3.59%   |
| 5.0.0   | 7         | 3.59%   |
| 5.10.14 | 5         | 2.56%   |
| 5.14.0  | 4         | 2.05%   |
| 5.16.11 | 3         | 1.54%   |
| 5.8.10  | 2         | 1.03%   |
| 5.7.1   | 2         | 1.03%   |
| 5.7.0   | 2         | 1.03%   |
| 5.4.64  | 2         | 1.03%   |
| 5.18.7  | 2         | 1.03%   |
| 5.17.5  | 2         | 1.03%   |
| 5.16.7  | 2         | 1.03%   |
| 5.16.18 | 2         | 1.03%   |
| 5.15.21 | 2         | 1.03%   |
| 5.15.16 | 2         | 1.03%   |
| 5.13.15 | 2         | 1.03%   |
| 5.9.16  | 1         | 0.51%   |
| 5.9.0   | 1         | 0.51%   |
| 5.8.3   | 1         | 0.51%   |
| 5.8.18  | 1         | 0.51%   |
| 5.8.16  | 1         | 0.51%   |
| 5.7.8   | 1         | 0.51%   |
| 5.7.4   | 1         | 0.51%   |
| 5.7.11  | 1         | 0.51%   |
| 5.6.7   | 1         | 0.51%   |
| 5.6.3   | 1         | 0.51%   |
| 5.6.15  | 1         | 0.51%   |
| 5.6.0   | 1         | 0.51%   |
| 5.4.35  | 1         | 0.51%   |
| 5.2.6   | 1         | 0.51%   |
| 5.19.3  | 1         | 0.51%   |
| 5.19.1  | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 24        | 12.44%  |
| 5.15    | 23        | 11.92%  |
| 5.8     | 18        | 9.33%   |
| 5.10    | 17        | 8.81%   |
| 5.13    | 16        | 8.29%   |
| 5.11    | 15        | 7.77%   |
| 4.18    | 9         | 4.66%   |
| 4.15    | 9         | 4.66%   |
| 5.16    | 8         | 4.15%   |
| 5.0     | 8         | 4.15%   |
| 5.7     | 7         | 3.63%   |
| 5.3     | 7         | 3.63%   |
| 5.14    | 6         | 3.11%   |
| 5.6     | 4         | 2.07%   |
| 5.17    | 4         | 2.07%   |
| 5.19    | 3         | 1.55%   |
| 5.18    | 3         | 1.55%   |
| 5.12    | 3         | 1.55%   |
| 5.9     | 2         | 1.04%   |
| 5.2     | 1         | 0.52%   |
| 4.4     | 1         | 0.52%   |
| 4.19    | 1         | 0.52%   |
| 4.14    | 1         | 0.52%   |
| 4.13    | 1         | 0.52%   |
| 4.10    | 1         | 0.52%   |
| 3.10    | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 172       | 97.73%  |
| i686   | 4         | 2.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 88        | 47.06%  |
| Unknown         | 35        | 18.72%  |
| KDE5            | 26        | 13.9%   |
| XFCE            | 7         | 3.74%   |
| X-Cinnamon      | 5         | 2.67%   |
| MATE            | 5         | 2.67%   |
| KDE             | 5         | 2.67%   |
| Openbox         | 2         | 1.07%   |
| LXQt            | 2         | 1.07%   |
| LXDE            | 2         | 1.07%   |
| i3              | 2         | 1.07%   |
| GNOME Flashback | 2         | 1.07%   |
| Deepin          | 2         | 1.07%   |
| Unity           | 1         | 0.53%   |
| sway            | 1         | 0.53%   |
| Pantheon        | 1         | 0.53%   |
| Budgie          | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 138       | 76.67%  |
| Wayland | 21        | 11.67%  |
| Unknown | 18        | 10%     |
| Tty     | 3         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 44.86%  |
| GDM     | 34        | 18.38%  |
| SDDM    | 29        | 15.68%  |
| GDM3    | 19        | 10.27%  |
| LightDM | 13        | 7.03%   |
| TDM     | 4         | 2.16%   |
| SLiM    | 2         | 1.08%   |
| LXDM    | 1         | 0.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 85        | 46.7%   |
| zh_TW   | 52        | 28.57%  |
| Unknown | 27        | 14.84%  |
| zh_CN   | 3         | 1.65%   |
| ru_RU   | 3         | 1.65%   |
| en_GB   | 3         | 1.65%   |
| C       | 2         | 1.1%    |
| zh_SG   | 1         | 0.55%   |
| lzh_TW  | 1         | 0.55%   |
| ja_JP   | 1         | 0.55%   |
| en_SG   | 1         | 0.55%   |
| en_IE   | 1         | 0.55%   |
| de_DE   | 1         | 0.55%   |
| C.UTF8  | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 109       | 60.89%  |
| BIOS | 70        | 39.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 152       | 85.39%  |
| Overlay | 8         | 4.49%   |
| Xfs     | 5         | 2.81%   |
| Btrfs   | 5         | 2.81%   |
| Unknown | 4         | 2.25%   |
| Ext2    | 2         | 1.12%   |
| Tmpfs   | 1         | 0.56%   |
| F2fs    | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 50%     |
| GPT     | 74        | 41.57%  |
| MBR     | 15        | 8.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 157       | 88.2%   |
| Yes       | 21        | 11.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 58.76%  |
| Yes       | 73        | 41.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer                 | 37        | 21.02%  |
| ASUSTek Computer     | 33        | 18.75%  |
| Lenovo               | 23        | 13.07%  |
| Hewlett-Packard      | 22        | 12.5%   |
| Dell                 | 20        | 11.36%  |
| MSI                  | 14        | 7.95%   |
| Sony                 | 3         | 1.7%    |
| Unknown              | 3         | 1.7%    |
| Toshiba              | 2         | 1.14%   |
| LG Electronics       | 2         | 1.14%   |
| Lex                  | 2         | 1.14%   |
| Gigabyte Technology  | 2         | 1.14%   |
| Apple                | 2         | 1.14%   |
| win element          | 1         | 0.57%   |
| Vizio                | 1         | 0.57%   |
| Samsung Electronics  | 1         | 0.57%   |
| NEXCOM               | 1         | 0.57%   |
| Intel Client Systems | 1         | 0.57%   |
| Intel                | 1         | 0.57%   |
| HUAWEI               | 1         | 0.57%   |
| CJSCOPE              | 1         | 0.57%   |
| AVITA                | 1         | 0.57%   |
| AMI                  | 1         | 0.57%   |
| AMD                  | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 2.84%   |
| MSI GS63 7RE                             | 2         | 1.14%   |
| Lex 3I610DW                              | 2         | 1.14%   |
| Lenovo IdeaPad 5 14ALC05 82LM            | 2         | 1.14%   |
| HP Pavilion dv7                          | 2         | 1.14%   |
| Dell XPS 13 9380                         | 2         | 1.14%   |
| Acer Swift SF514-52T                     | 2         | 1.14%   |
| Acer Aspire 4755                         | 2         | 1.14%   |
| win element MBOX                         | 1         | 0.57%   |
| Vizio CT14                               | 1         | 0.57%   |
| Toshiba Satellite L850                   | 1         | 0.57%   |
| Toshiba PORTEGE R830                     | 1         | 0.57%   |
| Sony VPCCB15FW                           | 1         | 0.57%   |
| Sony SVS15115FWB                         | 1         | 0.57%   |
| Sony SVP13229PWB                         | 1         | 0.57%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B      | 1         | 0.57%   |
| NEXCOM B537-I                            | 1         | 0.57%   |
| MSI PE72 8RD                             | 1         | 0.57%   |
| MSI PE62 8RD                             | 1         | 0.57%   |
| MSI PE60 6QE                             | 1         | 0.57%   |
| MSI P65 Creator 9SD                      | 1         | 0.57%   |
| MSI Modern 14 B11M                       | 1         | 0.57%   |
| MSI GV72 8RC                             | 1         | 0.57%   |
| MSI GT63 Titan 9SG                       | 1         | 0.57%   |
| MSI GS76 Stealth 11UH                    | 1         | 0.57%   |
| MSI GL65 9SD                             | 1         | 0.57%   |
| MSI GE70 2PE                             | 1         | 0.57%   |
| MSI GE70 0NC/GE70 0ND                    | 1         | 0.57%   |
| MSI CX62 6QD                             | 1         | 0.57%   |
| LG LE50-5BC6H1                           | 1         | 0.57%   |
| LG 16Z90P-G.AA78C                        | 1         | 0.57%   |
| Lenovo Z50-70 20354                      | 1         | 0.57%   |
| Lenovo XiaoXinAir 15ARE 2021 82GL        | 1         | 0.57%   |
| Lenovo V330-15IGM                        | 1         | 0.57%   |
| Lenovo ThinkPad X230 2324CD1             | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS0L800 | 1         | 0.57%   |
| Lenovo ThinkPad T510 4384CJ7             | 1         | 0.57%   |
| Lenovo ThinkPad T480s 20L7001YUS         | 1         | 0.57%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 0.57%   |
| Lenovo ThinkPad T440s 20ARS3RM00         | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 24        | 13.64%  |
| Lenovo ThinkPad   | 14        | 7.95%   |
| Dell Inspiron     | 8         | 4.55%   |
| HP Pavilion       | 7         | 3.98%   |
| ASUS ROG          | 6         | 3.41%   |
| Acer Swift        | 6         | 3.41%   |
| Lenovo IdeaPad    | 5         | 2.84%   |
| HP ProBook        | 5         | 2.84%   |
| ASUS VivoBook     | 5         | 2.84%   |
| Unknown           | 5         | 2.84%   |
| Dell Vostro       | 4         | 2.27%   |
| ASUS ZenBook      | 4         | 2.27%   |
| Acer TravelMate   | 4         | 2.27%   |
| Dell XPS          | 3         | 1.7%    |
| Dell Latitude     | 3         | 1.7%    |
| MSI GS63          | 2         | 1.14%   |
| MSI GE70          | 2         | 1.14%   |
| Lex 3I610DW       | 2         | 1.14%   |
| HP EliteBook      | 2         | 1.14%   |
| ASUS ASUS         | 2         | 1.14%   |
| win element MBOX  | 1         | 0.57%   |
| Vizio CT14        | 1         | 0.57%   |
| Toshiba Satellite | 1         | 0.57%   |
| Toshiba PORTEGE   | 1         | 0.57%   |
| Sony VPCCB15FW    | 1         | 0.57%   |
| Sony SVS15115FWB  | 1         | 0.57%   |
| Sony SVP13229PWB  | 1         | 0.57%   |
| Samsung 700Z3A    | 1         | 0.57%   |
| NEXCOM B537-I     | 1         | 0.57%   |
| MSI PE72          | 1         | 0.57%   |
| MSI PE62          | 1         | 0.57%   |
| MSI PE60          | 1         | 0.57%   |
| MSI P65           | 1         | 0.57%   |
| MSI Modern        | 1         | 0.57%   |
| MSI GV72          | 1         | 0.57%   |
| MSI GT63          | 1         | 0.57%   |
| MSI GS76          | 1         | 0.57%   |
| MSI GL65          | 1         | 0.57%   |
| MSI CX62          | 1         | 0.57%   |
| LG LE50-5BC6H1    | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 22        | 12.5%   |
| 2017 | 18        | 10.23%  |
| 2020 | 17        | 9.66%   |
| 2019 | 17        | 9.66%   |
| 2018 | 16        | 9.09%   |
| 2014 | 11        | 6.25%   |
| 2012 | 11        | 6.25%   |
| 2011 | 11        | 6.25%   |
| 2016 | 10        | 5.68%   |
| 2015 | 9         | 5.11%   |
| 2022 | 7         | 3.98%   |
| 2013 | 7         | 3.98%   |
| 2009 | 7         | 3.98%   |
| 2010 | 6         | 3.41%   |
| 2008 | 4         | 2.27%   |
| 2007 | 1         | 0.57%   |
| 2006 | 1         | 0.57%   |
| 2004 | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 176       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 158       | 88.76%  |
| Enabled  | 20        | 11.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 176       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 53        | 29.44%  |
| 16.01-24.0  | 47        | 26.11%  |
| 8.01-16.0   | 30        | 16.67%  |
| 3.01-4.0    | 25        | 13.89%  |
| 32.01-64.0  | 11        | 6.11%   |
| 64.01-256.0 | 6         | 3.33%   |
| 24.01-32.0  | 3         | 1.67%   |
| 2.01-3.0    | 2         | 1.11%   |
| 1.01-2.0    | 2         | 1.11%   |
| 0.51-1.0    | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 59        | 30.73%  |
| 2.01-3.0   | 53        | 27.6%   |
| 4.01-8.0   | 31        | 16.15%  |
| 3.01-4.0   | 28        | 14.58%  |
| 8.01-16.0  | 9         | 4.69%   |
| 0.51-1.0   | 7         | 3.65%   |
| 24.01-32.0 | 2         | 1.04%   |
| 0.01-0.5   | 2         | 1.04%   |
| 32.01-64.0 | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 62.09%  |
| 2      | 54        | 29.67%  |
| 3      | 9         | 4.95%   |
| 0      | 4         | 2.2%    |
| 5      | 1         | 0.55%   |
| 4      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 129       | 73.3%   |
| Yes       | 47        | 26.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 79.1%   |
| No        | 37        | 20.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 95.45%  |
| No        | 8         | 4.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 87.57%  |
| No        | 22        | 12.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Taiwan  | 176       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Taipei           | 60        | 31.75%  |
| New Taipei       | 29        | 15.34%  |
| Taoyuan District | 21        | 11.11%  |
| Hsinchu          | 18        | 9.52%   |
| Taichung         | 14        | 7.41%   |
| Kaohsiung City   | 10        | 5.29%   |
| Tainan City      | 7         | 3.7%    |
| Hsinchu County   | 4         | 2.12%   |
| Zhudong          | 3         | 1.59%   |
| Yunlin           | 3         | 1.59%   |
| Pingtung City    | 3         | 1.59%   |
| Chang-hua        | 3         | 1.59%   |
| Shulin District  | 2         | 1.06%   |
| Keelung          | 2         | 1.06%   |
| Zhubei           | 1         | 0.53%   |
| Yilan            | 1         | 0.53%   |
| Taichung City    | 1         | 0.53%   |
| Penghu County    | 1         | 0.53%   |
| Neihu            | 1         | 0.53%   |
| Nantou City      | 1         | 0.53%   |
| Miaoli           | 1         | 0.53%   |
| Fenjihu          | 1         | 0.53%   |
| Chenggong        | 1         | 0.53%   |
| Bao'an           | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 27        | 35     | 11.16%  |
| Samsung Electronics            | 25        | 36     | 10.33%  |
| Crucial                        | 21        | 25     | 8.68%   |
| Seagate                        | 19        | 21     | 7.85%   |
| Kingston                       | 17        | 23     | 7.02%   |
| SanDisk                        | 16        | 19     | 6.61%   |
| SK hynix                       | 15        | 16     | 6.2%    |
| HGST                           | 14        | 15     | 5.79%   |
| Toshiba                        | 12        | 13     | 4.96%   |
| Unknown                        | 9         | 10     | 3.72%   |
| Micron Technology              | 8         | 8      | 3.31%   |
| Intel                          | 8         | 9      | 3.31%   |
| Hitachi                        | 7         | 8      | 2.89%   |
| Transcend                      | 3         | 3      | 1.24%   |
| JMicron Technology             | 3         | 6      | 1.24%   |
| ASMT                           | 3         | 3      | 1.24%   |
| A-DATA Technology              | 3         | 3      | 1.24%   |
| SPCC                           | 2         | 3      | 0.83%   |
| AGI                            | 2         | 2      | 0.83%   |
| Unknown                        | 2         | 2      | 0.83%   |
| ZHITAI                         | 1         | 1      | 0.41%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.41%   |
| XPG                            | 1         | 1      | 0.41%   |
| USB3.2                         | 1         | 1      | 0.41%   |
| Union Memory                   | 1         | 1      | 0.41%   |
| Toshiba America Info Systems   | 1         | 2      | 0.41%   |
| StoreJet                       | 1         | 2      | 0.41%   |
| Solid State Storage Technology | 1         | 1      | 0.41%   |
| Silicon Motion                 | 1         | 1      | 0.41%   |
| Plextor                        | 1         | 1      | 0.41%   |
| Pioneer                        | 1         | 1      | 0.41%   |
| Phison                         | 1         | 1      | 0.41%   |
| OCZ                            | 1         | 1      | 0.41%   |
| NeoTech                        | 1         | 1      | 0.41%   |
| MyDigitalSSD                   | 1         | 1      | 0.41%   |
| MX                             | 1         | 1      | 0.41%   |
| Micron/Crucial Technology      | 1         | 1      | 0.41%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.41%   |
| LITEONIT                       | 1         | 1      | 0.41%   |
| LITEON                         | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB        | 7         | 2.76%   |
| HGST HTS721010A9E630 1TB            | 6         | 2.36%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 1.97%   |
| Seagate ST1000LM049-2GH172 1TB      | 4         | 1.57%   |
| Unknown MMC Card  64GB              | 3         | 1.18%   |
| Toshiba MQ01ABD100 1TB              | 3         | 1.18%   |
| SanDisk NVMe SSD Drive 512GB        | 3         | 1.18%   |
| SanDisk NVMe SSD Drive 256GB        | 3         | 1.18%   |
| SanDisk NVMe SSD Drive 1TB          | 3         | 1.18%   |
| Crucial CT500MX500SSD4 500GB        | 3         | 1.18%   |
| Crucial CT240BX500SSD1 240GB        | 3         | 1.18%   |
| Crucial CT1000MX500SSD1 1TB         | 3         | 1.18%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 2         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 0.79%   |
| Unknown MMC Card  32GB              | 2         | 0.79%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.79%   |
| SPCC Solid State Disk 240GB         | 2         | 0.79%   |
| SK hynix NVMe SSD Drive 512GB       | 2         | 0.79%   |
| SK hynix HFM512GD3JX013N 512GB      | 2         | 0.79%   |
| SK hynix BC711 NVMe 512GB           | 2         | 0.79%   |
| Samsung NVMe SSD Drive 256GB        | 2         | 0.79%   |
| Samsung NVMe SSD Drive 1024GB       | 2         | 0.79%   |
| Samsung MZVLW256HEHP-00000 256GB    | 2         | 0.79%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD | 2         | 0.79%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.79%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.79%   |
| Kingston SA2000M8500G 500GB         | 2         | 0.79%   |
| Kingston RBUSNS8154P3512GJ1 512GB   | 2         | 0.79%   |
| Kingston NVMe SSD Drive 512GB       | 2         | 0.79%   |
| HGST HTS541010B7E610 1TB            | 2         | 0.79%   |
| HGST HTS541010A9E680 1TB            | 2         | 0.79%   |
| ASMT 2115 1TB                       | 2         | 0.79%   |
| Unknown                             | 2         | 0.79%   |
| ZHITAI TiPro7000 1TB                | 1         | 0.39%   |
| Yangtze Memory NVMe SSD Drive 1TB   | 1         | 0.39%   |
| XPG NVMe SSD Drive 1024GB           | 1         | 0.39%   |
| WDC WDS500G3X0C-00SJG0 500GB        | 1         | 0.39%   |
| WDC WDS500G2B0B 500GB SSD           | 1         | 0.39%   |
| WDC WDS500G2B0A 500GB SSD           | 1         | 0.39%   |
| WDC WDS200T2B0A-00SM50 2TB SSD      | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 19        | 20     | 29.69%  |
| HGST               | 14        | 15     | 21.88%  |
| WDC                | 11        | 13     | 17.19%  |
| Toshiba            | 9         | 10     | 14.06%  |
| Hitachi            | 7         | 8      | 10.94%  |
| StoreJet           | 1         | 2      | 1.56%   |
| NeoTech            | 1         | 1      | 1.56%   |
| JMicron Technology | 1         | 3      | 1.56%   |
| ASMT               | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 19        | 22     | 23.75%  |
| Kingston            | 9         | 10     | 11.25%  |
| Samsung Electronics | 7         | 9      | 8.75%   |
| SanDisk             | 6         | 7      | 7.5%    |
| WDC                 | 5         | 7      | 6.25%   |
| Micron Technology   | 4         | 4      | 5%      |
| Intel               | 4         | 5      | 5%      |
| Transcend           | 3         | 3      | 3.75%   |
| SK hynix            | 3         | 3      | 3.75%   |
| A-DATA Technology   | 3         | 3      | 3.75%   |
| Toshiba             | 2         | 2      | 2.5%    |
| SPCC                | 2         | 3      | 2.5%    |
| ASMT                | 2         | 2      | 2.5%    |
| Unknown             | 2         | 2      | 2.5%    |
| Plextor             | 1         | 1      | 1.25%   |
| OCZ                 | 1         | 1      | 1.25%   |
| MyDigitalSSD        | 1         | 1      | 1.25%   |
| MX                  | 1         | 1      | 1.25%   |
| LITEONIT            | 1         | 1      | 1.25%   |
| LITEON              | 1         | 1      | 1.25%   |
| Aura                | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |
| Apacer              | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 76        | 106    | 33.04%  |
| SSD     | 76        | 91     | 33.04%  |
| HDD     | 62        | 73     | 26.96%  |
| MMC     | 8         | 9      | 3.48%   |
| Unknown | 8         | 9      | 3.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 120       | 157    | 55.81%  |
| NVMe | 75        | 105    | 34.88%  |
| SAS  | 12        | 17     | 5.58%   |
| MMC  | 8         | 9      | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 98     | 59.29%  |
| 0.51-1.0   | 50        | 58     | 35.71%  |
| 1.01-2.0   | 4         | 5      | 2.86%   |
| 2.01-3.0   | 1         | 1      | 0.71%   |
| 10.01-20.0 | 1         | 1      | 0.71%   |
| 4.01-10.0  | 1         | 1      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 57        | 30.98%  |
| 101-250        | 56        | 30.43%  |
| 501-1000       | 22        | 11.96%  |
| 1-20           | 12        | 6.52%   |
| 21-50          | 11        | 5.98%   |
| 1001-2000      | 11        | 5.98%   |
| 51-100         | 10        | 5.43%   |
| 2001-3000      | 2         | 1.09%   |
| Unknown        | 2         | 1.09%   |
| More than 3000 | 1         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 44.32%  |
| 21-50          | 27        | 14.59%  |
| 51-100         | 24        | 12.97%  |
| 101-250        | 21        | 11.35%  |
| 251-500        | 19        | 10.27%  |
| 501-1000       | 9         | 4.86%   |
| Unknown        | 2         | 1.08%   |
| More than 3000 | 1         | 0.54%   |

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
| ASMT 2115 1TB                                  | 1         | 1      | 16.67%  |

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
| Hitachi | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 50%     |
| HDD  | 2         | 2      | 33.33%  |
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
| Detected | 98        | 157    | 52.97%  |
| Works    | 81        | 125    | 43.78%  |
| Malfunc  | 6         | 6      | 3.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 129       | 56.58%  |
| Samsung Electronics            | 22        | 9.65%   |
| SanDisk                        | 19        | 8.33%   |
| AMD                            | 18        | 7.89%   |
| SK hynix                       | 12        | 5.26%   |
| Kingston Technology Company    | 8         | 3.51%   |
| Micron Technology              | 5         | 2.19%   |
| Toshiba America Info Systems   | 3         | 1.32%   |
| Micron/Crucial Technology      | 3         | 1.32%   |
| Yangtze Memory Technologies    | 1         | 0.44%   |
| Union Memory (Shenzhen)        | 1         | 0.44%   |
| Solid State Storage Technology | 1         | 0.44%   |
| Silicon Motion                 | 1         | 0.44%   |
| Phison Electronics             | 1         | 0.44%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.44%   |
| Marvell Technology Group       | 1         | 0.44%   |
| Lite-On Technology             | 1         | 0.44%   |
| ADATA Technology               | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 7.63%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 7.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 12        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 5.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 4.66%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 3.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.81%   |
| SK hynix Gold P31 SSD                                                          | 8         | 3.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 2.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 2.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.12%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.12%   |
| Micron Non-Volatile memory controller                                          | 5         | 2.12%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 1.69%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 1.69%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.27%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.27%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.85%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.85%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.85%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.85%   |
| Yangtze Memory ZHITAI TiPro7000                                                | 1         | 0.42%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.42%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.42%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.42%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.42%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 130       | 57.27%  |
| NVMe | 76        | 33.48%  |
| RAID | 18        | 7.93%   |
| IDE  | 3         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 149       | 84.66%  |
| AMD    | 27        | 15.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 3.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 6         | 3.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 2.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 4         | 2.27%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 4         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 2.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 2.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 1.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.7%    |
| AMD Ryzen 7 4800HS with Radeon Graphics | 3         | 1.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.14%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 1.14%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 1.14%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 1.14%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 1.14%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 2         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 1.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.14%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.14%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 1.14%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 1.14%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz      | 2         | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.14%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 1.14%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 2         | 1.14%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.14%   |
| Intel Celeron CPU 3955U @ 2.00GHz       | 2         | 1.14%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 1.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 1.14%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 2         | 1.14%   |
| AMD Ryzen 5 5625U with Radeon Graphics  | 2         | 1.14%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 1.14%   |
| Intel Xeon E-2286M CPU @ 2.40GHz        | 1         | 0.57%   |
| Intel Pentium M processor 1.73GHz       | 1         | 0.57%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz  | 1         | 0.57%   |
| Intel Pentium CPU U5400 @ 1.20GHz       | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 50        | 28.41%  |
| Intel Core i7      | 48        | 27.27%  |
| Other              | 19        | 10.8%   |
| AMD Ryzen 7        | 11        | 6.25%   |
| Intel Core i3      | 7         | 3.98%   |
| Intel Celeron      | 7         | 3.98%   |
| Intel Pentium      | 6         | 3.41%   |
| AMD Ryzen 5        | 6         | 3.41%   |
| Intel Genuine      | 3         | 1.7%    |
| Intel Core 2 Duo   | 3         | 1.7%    |
| Intel Atom         | 3         | 1.7%    |
| AMD Ryzen 9        | 3         | 1.7%    |
| AMD Ryzen 7 PRO    | 2         | 1.14%   |
| AMD Ryzen 3        | 2         | 1.14%   |
| Intel Xeon         | 1         | 0.57%   |
| Intel Pentium M    | 1         | 0.57%   |
| Intel Pentium Dual | 1         | 0.57%   |
| Intel Core 2 Solo  | 1         | 0.57%   |
| AMD FX             | 1         | 0.57%   |
| AMD Embedded       | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 68        | 38.64%  |
| 2      | 67        | 38.07%  |
| 8      | 19        | 10.8%   |
| 6      | 12        | 6.82%   |
| 1      | 5         | 2.84%   |
| 12     | 2         | 1.14%   |
| 10     | 2         | 1.14%   |
| 14     | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 176       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 144       | 81.82%  |
| 1      | 32        | 18.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 173       | 98.3%   |
| 32-bit         | 2         | 1.14%   |
| Unknown        | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 19.34%  |
| 0x306a9    | 11        | 6.08%   |
| 0x40651    | 10        | 5.52%   |
| 0x206a7    | 10        | 5.52%   |
| 0x806c1    | 9         | 4.97%   |
| 0x806ea    | 8         | 4.42%   |
| 0x906e9    | 7         | 3.87%   |
| 0x806eb    | 6         | 3.31%   |
| 0x806e9    | 6         | 3.31%   |
| 0x20655    | 6         | 3.31%   |
| 0x906ea    | 5         | 2.76%   |
| 0x406e3    | 5         | 2.76%   |
| 0x306d4    | 5         | 2.76%   |
| 0x0a50000c | 5         | 2.76%   |
| 0x706e5    | 4         | 2.21%   |
| 0x506e3    | 3         | 1.66%   |
| 0x1067a    | 3         | 1.66%   |
| 0x08608103 | 3         | 1.66%   |
| 0x08600106 | 3         | 1.66%   |
| 0x906ed    | 2         | 1.1%    |
| 0x906a4    | 2         | 1.1%    |
| 0x906a3    | 2         | 1.1%    |
| 0x806ec    | 2         | 1.1%    |
| 0x706a8    | 2         | 1.1%    |
| 0x6fd      | 2         | 1.1%    |
| 0x406c4    | 2         | 1.1%    |
| 0x306c3    | 2         | 1.1%    |
| 0x806d1    | 1         | 0.55%   |
| 0x706a1    | 1         | 0.55%   |
| 0x506c9    | 1         | 0.55%   |
| 0x406c3    | 1         | 0.55%   |
| 0x40661    | 1         | 0.55%   |
| 0x306a8    | 1         | 0.55%   |
| 0x30678    | 1         | 0.55%   |
| 0x20652    | 1         | 0.55%   |
| 0x106e5    | 1         | 0.55%   |
| 0x106c2    | 1         | 0.55%   |
| 0x10676    | 1         | 0.55%   |
| 0x0a404101 | 1         | 0.55%   |
| 0x08608102 | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 44        | 25%     |
| Haswell          | 14        | 7.95%   |
| IvyBridge        | 13        | 7.39%   |
| SandyBridge      | 12        | 6.82%   |
| Skylake          | 11        | 6.25%   |
| Westmere         | 10        | 5.68%   |
| TigerLake        | 10        | 5.68%   |
| Zen 3            | 8         | 4.55%   |
| Zen 2            | 8         | 4.55%   |
| Unknown          | 8         | 4.55%   |
| Penryn           | 5         | 2.84%   |
| IceLake          | 5         | 2.84%   |
| Broadwell        | 5         | 2.84%   |
| Silvermont       | 4         | 2.27%   |
| Alderlake Hybrid | 4         | 2.27%   |
| Goldmont plus    | 3         | 1.7%    |
| Excavator        | 3         | 1.7%    |
| Zen+             | 2         | 1.14%   |
| Core             | 2         | 1.14%   |
| Zen              | 1         | 0.57%   |
| P6               | 1         | 0.57%   |
| Nehalem          | 1         | 0.57%   |
| Goldmont         | 1         | 0.57%   |
| Bonnell          | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 139       | 54.94%  |
| Nvidia | 70        | 27.67%  |
| AMD    | 44        | 17.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 4.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.91%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 3.13%   |
| Intel HD Graphics 630                                                                    | 8         | 3.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.13%   |
| AMD Renoir                                                                               | 8         | 3.13%   |
| Intel HD Graphics 620                                                                    | 6         | 2.34%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.95%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.95%   |
| Intel HD Graphics 530                                                                    | 5         | 1.95%   |
| AMD Cezanne                                                                              | 5         | 1.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.56%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 1.56%   |
| AMD Lucienne                                                                             | 4         | 1.56%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 1.17%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.17%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 1.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.17%   |
| Intel HD Graphics 510                                                                    | 3         | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.17%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.17%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.17%   |
| AMD Barcelo                                                                              | 3         | 1.17%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.78%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.78%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.78%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.78%   |
| Intel VGA compatible controller                                                          | 2         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 37.5%   |
| Intel + Nvidia | 61        | 34.66%  |
| 1 x AMD        | 27        | 15.34%  |
| Intel + AMD    | 12        | 6.82%   |
| 1 x Nvidia     | 5         | 2.84%   |
| AMD + Nvidia   | 4         | 2.27%   |
| 2 x AMD        | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 141       | 78.33%  |
| Proprietary | 35        | 19.44%  |
| Unknown     | 4         | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 55.25%  |
| 1.01-2.0   | 30        | 16.57%  |
| 0.01-0.5   | 24        | 13.26%  |
| 3.01-4.0   | 12        | 6.63%   |
| 0.51-1.0   | 8         | 4.42%   |
| 5.01-6.0   | 6         | 3.31%   |
| 7.01-8.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 50        | 25%     |
| Chimei Innolux          | 29        | 14.5%   |
| LG Display              | 27        | 13.5%   |
| BOE                     | 27        | 13.5%   |
| Samsung Electronics     | 11        | 5.5%    |
| Ancor Communications    | 7         | 3.5%    |
| BenQ                    | 6         | 3%      |
| Sharp                   | 5         | 2.5%    |
| Dell                    | 5         | 2.5%    |
| PANDA                   | 3         | 1.5%    |
| Lenovo                  | 3         | 1.5%    |
| ASUSTek Computer        | 3         | 1.5%    |
| Acer                    | 3         | 1.5%    |
| ViewSonic               | 2         | 1%      |
| Philips                 | 2         | 1%      |
| Eizo                    | 2         | 1%      |
| TMX                     | 1         | 0.5%    |
| Sony                    | 1         | 0.5%    |
| Panasonic               | 1         | 0.5%    |
| Olevia                  | 1         | 0.5%    |
| NEX                     | 1         | 0.5%    |
| MStar                   | 1         | 0.5%    |
| LG Philips              | 1         | 0.5%    |
| Goldstar                | 1         | 0.5%    |
| CHR                     | 1         | 0.5%    |
| Chi Mei Optoelectronics | 1         | 0.5%    |
| BOE Technology Group    | 1         | 0.5%    |
| AVX                     | 1         | 0.5%    |
| Apple                   | 1         | 0.5%    |
| AOC                     | 1         | 0.5%    |
| AGT                     | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 1.98%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 1.49%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 1.49%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch              | 2         | 0.99%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.99%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.99%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.99%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 2         | 0.99%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO332C 1366x768 293x164mm 13.2-inch         | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO253D 1920x1080 309x174mm 14.0-inch        | 2         | 0.99%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 2         | 0.99%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 520x290mm 23.4-inch | 2         | 0.99%   |
| ViewSonic VX2376 Series VSC3B32 1920x1080 509x286mm 23.0-inch         | 1         | 0.5%    |
| ViewSonic VA2732-FHD VSC0D3A 1920x1080 598x336mm 27.0-inch            | 1         | 0.5%    |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.5%    |
| Sony TV SNY8200 1920x1080 560x420mm 27.6-inch                         | 1         | 0.5%    |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 1         | 0.5%    |
| Sharp LQ133M1JW07 SHP1435 1920x1080 294x165mm 13.3-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 98        | 55.06%  |
| 1366x768 (WXGA)    | 41        | 23.03%  |
| 3840x2160 (4K)     | 8         | 4.49%   |
| 2560x1440 (QHD)    | 4         | 2.25%   |
| 1600x900 (HD+)     | 4         | 2.25%   |
| 2560x1600          | 3         | 1.69%   |
| 2880x1800          | 2         | 1.12%   |
| 1920x1200 (WUXGA)  | 2         | 1.12%   |
| 1680x1050 (WSXGA+) | 2         | 1.12%   |
| 1280x800 (WXGA)    | 2         | 1.12%   |
| 3840x1080          | 1         | 0.56%   |
| 3200x1800 (QHD+)   | 1         | 0.56%   |
| 2560x1080          | 1         | 0.56%   |
| 2288x1287          | 1         | 0.56%   |
| 2256x1504          | 1         | 0.56%   |
| 2048x1152          | 1         | 0.56%   |
| 1680x945           | 1         | 0.56%   |
| 1440x900 (WXGA+)   | 1         | 0.56%   |
| 1280x720 (HD)      | 1         | 0.56%   |
| 1280x1024 (SXGA)   | 1         | 0.56%   |
| 1024x600           | 1         | 0.56%   |
| Unknown            | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 66        | 33.17%  |
| 14      | 36        | 18.09%  |
| 13      | 32        | 16.08%  |
| 24      | 12        | 6.03%   |
| 23      | 10        | 5.03%   |
| 17      | 8         | 4.02%   |
| 27      | 7         | 3.52%   |
| 11      | 5         | 2.51%   |
| 21      | 4         | 2.01%   |
| 12      | 4         | 2.01%   |
| 22      | 3         | 1.51%   |
| 16      | 3         | 1.51%   |
| 18      | 2         | 1.01%   |
| Unknown | 2         | 1.01%   |
| 55      | 1         | 0.5%    |
| 52      | 1         | 0.5%    |
| 34      | 1         | 0.5%    |
| 31      | 1         | 0.5%    |
| 10      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 60.1%   |
| 501-600     | 26        | 13.13%  |
| 201-300     | 26        | 13.13%  |
| 351-400     | 10        | 5.05%   |
| 401-500     | 9         | 4.55%   |
| 601-700     | 3         | 1.52%   |
| 1001-1500   | 2         | 1.01%   |
| Unknown     | 2         | 1.01%   |
| 701-800     | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 152       | 88.89%  |
| 16/10   | 16        | 9.36%   |
| 3/2     | 1         | 0.58%   |
| 21/9    | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 66        | 33.33%  |
| 81-90          | 53        | 26.77%  |
| 201-250        | 26        | 13.13%  |
| 71-80          | 16        | 8.08%   |
| 121-130        | 8         | 4.04%   |
| 301-350        | 7         | 3.54%   |
| 51-60          | 5         | 2.53%   |
| 61-70          | 3         | 1.52%   |
| 111-120        | 3         | 1.52%   |
| More than 1000 | 2         | 1.01%   |
| 351-500        | 2         | 1.01%   |
| 251-300        | 2         | 1.01%   |
| 141-150        | 2         | 1.01%   |
| Unknown        | 2         | 1.01%   |
| 41-50          | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 94        | 47.72%  |
| 101-120       | 44        | 22.34%  |
| 51-100        | 31        | 15.74%  |
| 161-240       | 17        | 8.63%   |
| More than 240 | 7         | 3.55%   |
| 1-50          | 2         | 1.02%   |
| Unknown       | 2         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 142       | 79.78%  |
| 2     | 30        | 16.85%  |
| 0     | 4         | 2.25%   |
| 3     | 2         | 1.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 106       | 36.3%   |
| Realtek Semiconductor    | 89        | 30.48%  |
| Qualcomm Atheros         | 49        | 16.78%  |
| Broadcom                 | 18        | 6.16%   |
| MediaTek                 | 8         | 2.74%   |
| Broadcom Limited         | 5         | 1.71%   |
| Ralink                   | 3         | 1.03%   |
| ASIX Electronics         | 3         | 1.03%   |
| TP-Link                  | 2         | 0.68%   |
| Marvell Technology Group | 2         | 0.68%   |
| Edimax Technology        | 2         | 0.68%   |
| U-Blox                   | 1         | 0.34%   |
| OPPO Electronics         | 1         | 0.34%   |
| Lenovo                   | 1         | 0.34%   |
| D-Link                   | 1         | 0.34%   |
| ASUSTek Computer         | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 18.84%  |
| Intel Wi-Fi 6 AX200                                               | 14        | 4.26%   |
| Intel Wireless 8265 / 8275                                        | 12        | 3.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 3.04%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 3.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 2.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.82%   |
| Intel Wireless 7260                                               | 6         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.52%   |
| Intel Wireless 7265                                               | 5         | 1.52%   |
| Intel Wireless 3165                                               | 5         | 1.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 1.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.22%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.22%   |
| Broadcom BCM43225 802.11b/g/n                                     | 4         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.91%   |
| Intel Wireless 8260                                               | 3         | 0.91%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.91%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 57.8%   |
| Qualcomm Atheros      | 34        | 19.65%  |
| Broadcom              | 12        | 6.94%   |
| Realtek Semiconductor | 8         | 4.62%   |
| MediaTek              | 8         | 4.62%   |
| Ralink                | 3         | 1.73%   |
| Broadcom Limited      | 3         | 1.73%   |
| Edimax Technology     | 2         | 1.16%   |
| TP-Link               | 1         | 0.58%   |
| D-Link                | 1         | 0.58%   |
| ASUSTek Computer      | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 14        | 8.09%   |
| Intel Wireless 8265 / 8275                                              | 12        | 6.94%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 5.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 4.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 4.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 3.47%   |
| Intel Wireless 7260                                                     | 6         | 3.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.89%   |
| Intel Wireless 7265                                                     | 5         | 2.89%   |
| Intel Wireless 3165                                                     | 5         | 2.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 2.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 2.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 2.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.31%   |
| Broadcom BCM43225 802.11b/g/n                                           | 4         | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.73%   |
| Intel Wireless 8260                                                     | 3         | 1.73%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.16%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.16%   |
| Intel Wireless 3160                                                     | 2         | 1.16%   |
| Intel WiFi Link 5100                                                    | 2         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.16%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.16%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.58%   |
| Ralink RT3091 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.58%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.58%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 1         | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 84        | 56%     |
| Intel                    | 25        | 16.67%  |
| Qualcomm Atheros         | 24        | 16%     |
| Broadcom                 | 7         | 4.67%   |
| ASIX Electronics         | 3         | 2%      |
| Marvell Technology Group | 2         | 1.33%   |
| Broadcom Limited         | 2         | 1.33%   |
| TP-Link                  | 1         | 0.67%   |
| OPPO Electronics         | 1         | 0.67%   |
| Lenovo                   | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 40%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 6.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 3.87%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 2.58%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 2.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 2.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.94%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.94%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.94%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.94%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.29%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.29%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 1.29%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.29%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.65%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.65%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.65%   |
| OPPO RMX2117                                                      | 1         | 0.65%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.65%   |
| Lenovo USB-C Hub                                                  | 1         | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.65%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.65%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 54.37%  |
| Ethernet | 140       | 45.31%  |
| Modem    | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 72.97%  |
| Ethernet | 50        | 27.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 129       | 73.3%   |
| 1     | 46        | 26.14%  |
| 5     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 161       | 91.48%  |
| Yes  | 15        | 8.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 57.42%  |
| Foxconn / Hon Hai               | 12        | 7.74%   |
| Broadcom                        | 12        | 7.74%   |
| Qualcomm Atheros Communications | 11        | 7.1%    |
| Lite-On Technology              | 8         | 5.16%   |
| IMC Networks                    | 8         | 5.16%   |
| Realtek Semiconductor           | 5         | 3.23%   |
| Ralink                          | 2         | 1.29%   |
| Hewlett-Packard                 | 2         | 1.29%   |
| ASUSTek Computer                | 2         | 1.29%   |
| Apple                           | 2         | 1.29%   |
| Toshiba                         | 1         | 0.65%   |
| Realtek                         | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 35        | 22.58%  |
| Intel AX201 Bluetooth                                                               | 16        | 10.32%  |
| Intel AX200 Bluetooth                                                               | 14        | 9.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 7.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 3.23%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 3.23%   |
| Realtek Bluetooth Radio                                                             | 4         | 2.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.58%   |
| Intel Bluetooth Device                                                              | 4         | 2.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.94%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.94%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.94%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.94%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.29%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.29%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.29%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.29%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.29%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 1.29%   |
| Broadcom Bluetooth                                                                  | 2         | 1.29%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 1.29%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.29%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.65%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.65%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.65%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.65%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.65%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.65%   |
| Broadcom Bluetooth Device                                                           | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 146       | 67.91%  |
| AMD                     | 34        | 15.81%  |
| Nvidia                  | 28        | 13.02%  |
| Realtek Semiconductor   | 1         | 0.47%   |
| GN Netcom               | 1         | 0.47%   |
| ESS Technology          | 1         | 0.47%   |
| Dell                    | 1         | 0.47%   |
| Cambridge Silicon Radio | 1         | 0.47%   |
| C-Media Electronics     | 1         | 0.47%   |
| ASUSTek Computer        | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 9.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 22        | 8.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 20        | 7.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 4.18%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 4.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 4.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 3.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 3.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 3.04%   |
| Intel CM238 HD Audio Controller                                            | 7         | 2.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.28%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.9%    |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.52%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.14%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.76%   |
| Intel USB PnP Sound Device                                                 | 2         | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.76%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.38%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.38%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 36        | 26.09%  |
| Samsung Electronics | 30        | 21.74%  |
| Micron Technology   | 18        | 13.04%  |
| Kingston            | 16        | 11.59%  |
| Crucial             | 11        | 7.97%   |
| Unknown             | 5         | 3.62%   |
| Transcend           | 4         | 2.9%    |
| Apacer              | 3         | 2.17%   |
| Ramaxel Technology  | 2         | 1.45%   |
| G-Alantic           | 2         | 1.45%   |
| A-DATA Technology   | 2         | 1.45%   |
| Unknown (ABCD)      | 1         | 0.72%   |
| Unknown (08AE)      | 1         | 0.72%   |
| Patriot             | 1         | 0.72%   |
| Goldkey             | 1         | 0.72%   |
| G.Skill             | 1         | 0.72%   |
| Elpida              | 1         | 0.72%   |
| Avant               | 1         | 0.72%   |
| ASint Technology    | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2%      |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s           | 3         | 2%      |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.33%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.33%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.33%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.33%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.33%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.33%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 2         | 1.33%   |
| G-Alantic RAM D4SS12161SH26A-C 4GB SODIMM DDR4 2133MT/s          | 2         | 1.33%   |
| Crucial RAM CT8G4SFS632A.C4FE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.33%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 1.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.67%   |
| Unknown RAM Module 1024MB SODIMM DDR2 800MT/s                    | 1         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.67%   |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.67%   |
| Transcend RAM TS512MSK64V6N 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.67%   |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.67%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.67%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.67%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.67%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 1600MT/s                   | 1         | 0.67%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.67%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.67%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 1         | 0.67%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 0.67%   |
| SK hynix RAM Module 1024MB SODIMM DDR2 533MT/s                   | 1         | 0.67%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.67%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT451S6AFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 62        | 56.88%  |
| DDR3    | 25        | 22.94%  |
| LPDDR4  | 11        | 10.09%  |
| LPDDR3  | 7         | 6.42%   |
| DDR2    | 2         | 1.83%   |
| DDR5    | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 90        | 82.57%  |
| Row Of Chips | 17        | 15.6%   |
| DIMM         | 1         | 0.92%   |
| Chip         | 1         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 49        | 40.83%  |
| 4096  | 36        | 30%     |
| 16384 | 20        | 16.67%  |
| 32768 | 7         | 5.83%   |
| 2048  | 6         | 5%      |
| 1024  | 2         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 32        | 27.83%  |
| 2667  | 21        | 18.26%  |
| 1600  | 20        | 17.39%  |
| 2400  | 11        | 9.57%   |
| 2133  | 7         | 6.09%   |
| 4267  | 4         | 3.48%   |
| 1867  | 3         | 2.61%   |
| 1334  | 3         | 2.61%   |
| 4800  | 2         | 1.74%   |
| 4266  | 2         | 1.74%   |
| 800   | 2         | 1.74%   |
| 8400  | 1         | 0.87%   |
| 6400  | 1         | 0.87%   |
| 3733  | 1         | 0.87%   |
| 3266  | 1         | 0.87%   |
| 2000  | 1         | 0.87%   |
| 1067  | 1         | 0.87%   |
| 1066  | 1         | 0.87%   |
| 533   | 1         | 0.87%   |

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
| Chicony Electronics                    | 42        | 28.38%  |
| IMC Networks                           | 20        | 13.51%  |
| Realtek Semiconductor                  | 17        | 11.49%  |
| Quanta                                 | 10        | 6.76%   |
| Sunplus Innovation Technology          | 9         | 6.08%   |
| Microdia                               | 9         | 6.08%   |
| Acer                                   | 9         | 6.08%   |
| Suyin                                  | 5         | 3.38%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.38%   |
| ALi                                    | 3         | 2.03%   |
| Syntek                                 | 2         | 1.35%   |
| Sunplus Technology                     | 2         | 1.35%   |
| Ricoh                                  | 2         | 1.35%   |
| Lite-On Technology                     | 2         | 1.35%   |
| Lenovo                                 | 2         | 1.35%   |
| Apple                                  | 2         | 1.35%   |
| Sonix Technology                       | 1         | 0.68%   |
| Silicon Motion                         | 1         | 0.68%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Logitech                               | 1         | 0.68%   |
| Google                                 | 1         | 0.68%   |
| Generalplus Technology                 | 1         | 0.68%   |
| Foxconn / Hon Hai                      | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 8         | 5.37%   |
| Chicony HD WebCam                                                          | 8         | 5.37%   |
| Chicony Integrated Camera                                                  | 7         | 4.7%    |
| Realtek Integrated_Webcam_HD                                               | 5         | 3.36%   |
| Chicony HP HD Camera                                                       | 5         | 3.36%   |
| Sunplus HD WebCam                                                          | 4         | 2.68%   |
| Quanta HD User Facing                                                      | 4         | 2.68%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 2.68%   |
| IMC Networks Integrated Camera                                             | 4         | 2.68%   |
| Realtek HD WebCam                                                          | 3         | 2.01%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 2.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 2.01%   |
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 2.01%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 2.01%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 2.01%   |
| ALi Gateway Webcam                                                         | 3         | 2.01%   |
| Acer HD Webcam                                                             | 3         | 2.01%   |
| Sunplus 1.3M HD WebCam                                                     | 2         | 1.34%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.34%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.34%   |
| Realtek USB Camera                                                         | 2         | 1.34%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 1.34%   |
| IMC Networks UVC VGA Webcam                                                | 2         | 1.34%   |
| Chicony Webcam                                                             | 2         | 1.34%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 1.34%   |
| Chicony USB 2.0 Webcam Device                                              | 2         | 1.34%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.34%   |
| Acer BisonCam, NB Pro                                                      | 2         | 1.34%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.67%   |
| Syntek HP TrueVision HD                                                    | 1         | 0.67%   |
| Suyin UVC 1.3MPixel WebCam                                                 | 1         | 0.67%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 0.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 0.67%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 0.67%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.67%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.67%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.67%   |
| Sunplus HD User Facing                                                     | 1         | 0.67%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.67%   |
| Silicon Motion WebCam SC-13HDL11431N                                       | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 23.08%  |
| Validity Sensors           | 8         | 20.51%  |
| LighTuning Technology      | 8         | 20.51%  |
| Upek                       | 4         | 10.26%  |
| Shenzhen Goodix Technology | 4         | 10.26%  |
| Elan Microelectronics      | 4         | 10.26%  |
| AuthenTec                  | 2         | 5.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 10.26%  |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 10.26%  |
| Unknown                                                    | 4         | 10.26%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 7.69%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 7.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 3         | 7.69%   |
| Elan ELAN:Fingerprint                                      | 3         | 7.69%   |
| Validity Sensors VFS Fingerprint sensor                    | 2         | 5.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 2.56%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.56%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.56%   |
| Synaptics  WBDI Fingerprint Reader - USB 052               | 1         | 2.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2.56%   |
| LighTuning Fingerprint Reader                              | 1         | 2.56%   |
| Elan fingerprint sensor [FeinTech FPS00200]                | 1         | 2.56%   |
| AuthenTec AES2810                                          | 1         | 2.56%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.56%   |

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
| 0     | 105       | 57.69%  |
| 1     | 60        | 32.97%  |
| 2     | 15        | 8.24%   |
| 4     | 1         | 0.55%   |
| 3     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 44.32%  |
| Graphics card            | 20        | 22.73%  |
| Chipcard                 | 7         | 7.95%   |
| Camera                   | 5         | 5.68%   |
| Net/wireless             | 3         | 3.41%   |
| Multimedia controller    | 3         | 3.41%   |
| Card reader              | 3         | 3.41%   |
| Bluetooth                | 3         | 3.41%   |
| Net/ethernet             | 2         | 2.27%   |
| Storage/nvme             | 1         | 1.14%   |
| Sound                    | 1         | 1.14%   |
| Communication controller | 1         | 1.14%   |

