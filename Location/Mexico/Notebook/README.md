Linux in Mexico - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

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

Total: 2058

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 320-15AST 80XV      | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Laptop 15-dw1xxx            | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| Acer          | Aspire A315-56              | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| DERE          | X16                         | [8c51699ade](https://linux-hardware.org/?probe=8c51699ade) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| Dell          | G15 5510                    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| ASUSTek       | T100TAF                     | [9e59d428d2](https://linux-hardware.org/?probe=9e59d428d2) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2cb8ecb34d](https://linux-hardware.org/?probe=2cb8ecb34d) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| HP            | Unknown                     | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| Apple         | MacBook4,1                  | [39057bb60a](https://linux-hardware.org/?probe=39057bb60a) | Apr 18, 2023 |
| Apple         | MacBook4,1                  | [ebfd8fec1b](https://linux-hardware.org/?probe=ebfd8fec1b) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| HP            | ProBook 645 G1              | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [52e4ec34e1](https://linux-hardware.org/?probe=52e4ec34e1) | Apr 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| HP            | ProBook 655 G1              | [aaef8a36db](https://linux-hardware.org/?probe=aaef8a36db) | Apr 10, 2023 |
| Gateway       | M-6812M                     | [6101b79a06](https://linux-hardware.org/?probe=6101b79a06) | Apr 08, 2023 |
| Samsung       | RV415/RV515                 | [fe77afbdfa](https://linux-hardware.org/?probe=fe77afbdfa) | Apr 07, 2023 |
| HP            | ProBook 6360b               | [bfa6c44b14](https://linux-hardware.org/?probe=bfa6c44b14) | Apr 07, 2023 |
| Acer          | Aspire 3680                 | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Notebook      | L140PU                      | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [9da88b2a33](https://linux-hardware.org/?probe=9da88b2a33) | Apr 04, 2023 |
| Sony          | VPCF236FM                   | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Valve         | Jupiter                     | [7a6dcc077f](https://linux-hardware.org/?probe=7a6dcc077f) | Apr 03, 2023 |
| HP            | Unknown                     | [bd783cf180](https://linux-hardware.org/?probe=bd783cf180) | Apr 03, 2023 |
| HP            | 2000                        | [3fffec7875](https://linux-hardware.org/?probe=3fffec7875) | Apr 03, 2023 |
| HUAWEI        | HVY-WXX9                    | [63d38ddebf](https://linux-hardware.org/?probe=63d38ddebf) | Apr 02, 2023 |
| Dell          | System XPS L502X            | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [111eeac3b3](https://linux-hardware.org/?probe=111eeac3b3) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [2fcab6a925](https://linux-hardware.org/?probe=2fcab6a925) | Apr 01, 2023 |
| EVOO          | EVC156-1                    | [8e665ae8b2](https://linux-hardware.org/?probe=8e665ae8b2) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [f5db7a6030](https://linux-hardware.org/?probe=f5db7a6030) | Mar 30, 2023 |
| HP            | Notebook                    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [31d94ffb5f](https://linux-hardware.org/?probe=31d94ffb5f) | Mar 29, 2023 |
| Apple         | MacBookPro8,3               | [90fadbf903](https://linux-hardware.org/?probe=90fadbf903) | Mar 28, 2023 |
| Apple         | MacBookPro9,2               | [bce7f8b531](https://linux-hardware.org/?probe=bce7f8b531) | Mar 27, 2023 |
| Alienware     | 17 R4                       | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Lenovo        | IdeaPad Y910-17ISK 80V1     | [5e4e7975c1](https://linux-hardware.org/?probe=5e4e7975c1) | Mar 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Toshiba       | Satellite C845D             | [32341bde2a](https://linux-hardware.org/?probe=32341bde2a) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| American M... | XA133PR110                  | [7e49d89ca8](https://linux-hardware.org/?probe=7e49d89ca8) | Mar 25, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| HP            | Unknown                     | [c27dcda931](https://linux-hardware.org/?probe=c27dcda931) | Mar 24, 2023 |
| Dell          | Inspiron 7559               | [51aab276a2](https://linux-hardware.org/?probe=51aab276a2) | Mar 23, 2023 |
| ASUSTek       | X202EP                      | [5cc1f3216b](https://linux-hardware.org/?probe=5cc1f3216b) | Mar 23, 2023 |
| HP            | Unknown                     | [913aa678bf](https://linux-hardware.org/?probe=913aa678bf) | Mar 23, 2023 |
| Lenovo        | Yoga 500-14IBD 80N4         | [f364402e8a](https://linux-hardware.org/?probe=f364402e8a) | Mar 23, 2023 |
| HONOR         | BBR-WAX9                    | [b16e6324ed](https://linux-hardware.org/?probe=b16e6324ed) | Mar 22, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | G15 5510                    | [3ddfc82bcd](https://linux-hardware.org/?probe=3ddfc82bcd) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [8a70a156a4](https://linux-hardware.org/?probe=8a70a156a4) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6dc3256710](https://linux-hardware.org/?probe=6dc3256710) | Mar 21, 2023 |
| HP            | Unknown                     | [66723d18e0](https://linux-hardware.org/?probe=66723d18e0) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [56b1138062](https://linux-hardware.org/?probe=56b1138062) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [1fe782c379](https://linux-hardware.org/?probe=1fe782c379) | Mar 21, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Lenovo        | G40-80 80E4                 | [70b2fab92b](https://linux-hardware.org/?probe=70b2fab92b) | Mar 17, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [70812fb9c8](https://linux-hardware.org/?probe=70812fb9c8) | Mar 17, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Toshiba       | Satellite P55t-B            | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [f3dd1409f6](https://linux-hardware.org/?probe=f3dd1409f6) | Mar 14, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f91bf005b0](https://linux-hardware.org/?probe=f91bf005b0) | Mar 11, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Acer          | Aspire R3-131T              | [94435f58ed](https://linux-hardware.org/?probe=94435f58ed) | Mar 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e770c2f24c](https://linux-hardware.org/?probe=e770c2f24c) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| Dell          | G3 3500                     | [5cfed5bee9](https://linux-hardware.org/?probe=5cfed5bee9) | Mar 10, 2023 |
| HP            | Pavilion dv4                | [79a8c505ef](https://linux-hardware.org/?probe=79a8c505ef) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Dell          | Inspiron 5567               | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6f7e8084e5](https://linux-hardware.org/?probe=6f7e8084e5) | Mar 04, 2023 |
| HP            | ProBook 6360b               | [8b6826988f](https://linux-hardware.org/?probe=8b6826988f) | Mar 03, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [c3113c9da6](https://linux-hardware.org/?probe=c3113c9da6) | Mar 02, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [73efff8199](https://linux-hardware.org/?probe=73efff8199) | Mar 02, 2023 |
| HP            | Pavilion 14                 | [ae0e65f5d1](https://linux-hardware.org/?probe=ae0e65f5d1) | Feb 28, 2023 |
| Dell          | Latitude E7270              | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| HP            | Pavilion 14                 | [c9b9f213b5](https://linux-hardware.org/?probe=c9b9f213b5) | Feb 26, 2023 |
| Lenovo        | B40-45 20394                | [8472ed364a](https://linux-hardware.org/?probe=8472ed364a) | Feb 26, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Alienware     | 17 R4                       | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| Valve         | Jupiter                     | [0ec37b6ef2](https://linux-hardware.org/?probe=0ec37b6ef2) | Feb 25, 2023 |
| Chuwi         | HeroBook Air                | [8daed679c2](https://linux-hardware.org/?probe=8daed679c2) | Feb 24, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [bfd3019210](https://linux-hardware.org/?probe=bfd3019210) | Feb 22, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Toshiba       | Satellite C50D-A            | [3e9201a0fe](https://linux-hardware.org/?probe=3e9201a0fe) | Feb 20, 2023 |
| HP            | Pavilion g6                 | [2b4de6efbe](https://linux-hardware.org/?probe=2b4de6efbe) | Feb 18, 2023 |
| Dell          | Studio 1558                 | [4a2f0524b9](https://linux-hardware.org/?probe=4a2f0524b9) | Feb 17, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Dell          | Latitude E7440              | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [269420c3fe](https://linux-hardware.org/?probe=269420c3fe) | Feb 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [de592b6218](https://linux-hardware.org/?probe=de592b6218) | Feb 14, 2023 |
| Dell          | Latitude E7270              | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| HP            | Laptop 15-da2xxx            | [41bf5d50f8](https://linux-hardware.org/?probe=41bf5d50f8) | Feb 14, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [cfeb6479d1](https://linux-hardware.org/?probe=cfeb6479d1) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Dell          | Latitude E7270              | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| HP            | 240 G3                      | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [f7c5e9e498](https://linux-hardware.org/?probe=f7c5e9e498) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [44aed7e81a](https://linux-hardware.org/?probe=44aed7e81a) | Feb 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [5acc007668](https://linux-hardware.org/?probe=5acc007668) | Feb 04, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 240 G3                      | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| HUAWEI        | KLVD-WXX9                   | [6546c6e279](https://linux-hardware.org/?probe=6546c6e279) | Feb 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [73230e9490](https://linux-hardware.org/?probe=73230e9490) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| ASUSTek       | N56VB                       | [d5b5c983c9](https://linux-hardware.org/?probe=d5b5c983c9) | Feb 02, 2023 |
| Apple         | MacBookPro15,2              | [7c17db143e](https://linux-hardware.org/?probe=7c17db143e) | Feb 01, 2023 |
| Apple         | MacBookPro8,1               | [13467e9e83](https://linux-hardware.org/?probe=13467e9e83) | Feb 01, 2023 |
| Dell          | Latitude 5430               | [2afa57d0fa](https://linux-hardware.org/?probe=2afa57d0fa) | Feb 01, 2023 |
| Apple         | MacBookPro15,2              | [7612aba4cb](https://linux-hardware.org/?probe=7612aba4cb) | Jan 31, 2023 |
| Lenovo        | ThinkPad T430 2349A44       | [9f8528c5da](https://linux-hardware.org/?probe=9f8528c5da) | Jan 31, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| HP            | Laptop 15-dw1xxx            | [c7d825c34c](https://linux-hardware.org/?probe=c7d825c34c) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [bd58d910f7](https://linux-hardware.org/?probe=bd58d910f7) | Jan 25, 2023 |
| Dell          | Latitude E5440              | [f8e7f1785b](https://linux-hardware.org/?probe=f8e7f1785b) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [65b6391803](https://linux-hardware.org/?probe=65b6391803) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Dell          | Inspiron 5558               | [bf87467519](https://linux-hardware.org/?probe=bf87467519) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [57ed6980d4](https://linux-hardware.org/?probe=57ed6980d4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [0667ad7cee](https://linux-hardware.org/?probe=0667ad7cee) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c9279b845](https://linux-hardware.org/?probe=9c9279b845) | Jan 19, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | [7e61f98275](https://linux-hardware.org/?probe=7e61f98275) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [3709c83303](https://linux-hardware.org/?probe=3709c83303) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [6eeac14bb9](https://linux-hardware.org/?probe=6eeac14bb9) | Jan 15, 2023 |
| Dell          | Latitude E6440              | [d04d05f246](https://linux-hardware.org/?probe=d04d05f246) | Jan 14, 2023 |
| Lenovo        | B490 20205                  | [14243e79d2](https://linux-hardware.org/?probe=14243e79d2) | Jan 13, 2023 |
| HP            | ProBook 4230s               | [63a87864b9](https://linux-hardware.org/?probe=63a87864b9) | Jan 12, 2023 |
| HP            | ProBook 4230s               | [9a6505c0aa](https://linux-hardware.org/?probe=9a6505c0aa) | Jan 12, 2023 |
| Lenovo        | Y50-70 20378                | [64ec4b6816](https://linux-hardware.org/?probe=64ec4b6816) | Jan 12, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Lenovo        | Y50-70 20378                | [9cd68b4513](https://linux-hardware.org/?probe=9cd68b4513) | Jan 11, 2023 |
| Sony          | VPCEH1AFX                   | [3f64681bc7](https://linux-hardware.org/?probe=3f64681bc7) | Jan 11, 2023 |
| HP            | Pavilion Notebook           | [2132701432](https://linux-hardware.org/?probe=2132701432) | Jan 11, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Valve         | Jupiter                     | [57b570af42](https://linux-hardware.org/?probe=57b570af42) | Jan 09, 2023 |
| HP            | Pavilion 15                 | [2937882035](https://linux-hardware.org/?probe=2937882035) | Jan 08, 2023 |
| Notebook      | W9x0LU                      | [a81dd09b0c](https://linux-hardware.org/?probe=a81dd09b0c) | Jan 07, 2023 |
| HP            | Stream Laptop 11-y0XX       | [b40a3e32e9](https://linux-hardware.org/?probe=b40a3e32e9) | Jan 06, 2023 |
| HP            | Stream Laptop 11-y0XX       | [73db1ffcf6](https://linux-hardware.org/?probe=73db1ffcf6) | Jan 06, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| Lenovo        | G580 20157                  | [c0199fa7bf](https://linux-hardware.org/?probe=c0199fa7bf) | Jan 05, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | EliteBook 8460p             | [3365055862](https://linux-hardware.org/?probe=3365055862) | Jan 02, 2023 |
| HP            | EliteBook 8460p             | [45184e1f70](https://linux-hardware.org/?probe=45184e1f70) | Jan 02, 2023 |
| HP            | Laptop 15-dy2xxx            | [8c76b9ad8e](https://linux-hardware.org/?probe=8c76b9ad8e) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| Acer          | Aspire R7-371T              | [057e717cb7](https://linux-hardware.org/?probe=057e717cb7) | Dec 30, 2022 |
| HP            | 240 G7 Notebook PC          | [414db30bff](https://linux-hardware.org/?probe=414db30bff) | Dec 30, 2022 |
| ASUSTek       | N56VB                       | [6201ddc028](https://linux-hardware.org/?probe=6201ddc028) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Dell          | Inspiron MM061              | [34804f8a34](https://linux-hardware.org/?probe=34804f8a34) | Dec 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | Laptop 14-fq0xxx            | [e020678b51](https://linux-hardware.org/?probe=e020678b51) | Dec 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [8e2393e7b4](https://linux-hardware.org/?probe=8e2393e7b4) | Dec 26, 2022 |
| Acer          | Aspire E1-522               | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Google        | Bobba360                    | [bdad461cec](https://linux-hardware.org/?probe=bdad461cec) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Dell          | Inspiron 7559               | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Acer          | Aspire A515-51              | [29af4c3712](https://linux-hardware.org/?probe=29af4c3712) | Dec 20, 2022 |
| Google        | Coral                       | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [96dcb47ba1](https://linux-hardware.org/?probe=96dcb47ba1) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Valve         | Jupiter                     | [f89644c711](https://linux-hardware.org/?probe=f89644c711) | Dec 15, 2022 |
| HP            | Laptop 15-da2xxx            | [cd64f27416](https://linux-hardware.org/?probe=cd64f27416) | Dec 14, 2022 |
| MSI           | GL75 Leopard 10SDK          | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [36bd6688bb](https://linux-hardware.org/?probe=36bd6688bb) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [ed5d274c1a](https://linux-hardware.org/?probe=ed5d274c1a) | Dec 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| Alienware     | 15 R4                       | [f365266667](https://linux-hardware.org/?probe=f365266667) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Toshiba       | Satellite L855              | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| Sony          | VPCEE27FL                   | [dd2bc8b6ff](https://linux-hardware.org/?probe=dd2bc8b6ff) | Dec 10, 2022 |
| Dell          | Latitude E6420              | [acd81c73d0](https://linux-hardware.org/?probe=acd81c73d0) | Dec 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [38d274571d](https://linux-hardware.org/?probe=38d274571d) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Acer          | TravelMate B117-M           | [00ff19b078](https://linux-hardware.org/?probe=00ff19b078) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| HP            | 15                          | [132fad5c38](https://linux-hardware.org/?probe=132fad5c38) | Dec 04, 2022 |
| Acer          | TravelMate B117-M           | [0b86a9c3b9](https://linux-hardware.org/?probe=0b86a9c3b9) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| HP            | Pavilion 14                 | [dedd30adc4](https://linux-hardware.org/?probe=dedd30adc4) | Nov 30, 2022 |
| Sony          | VGN-NS150FJ                 | [e675a19a27](https://linux-hardware.org/?probe=e675a19a27) | Nov 29, 2022 |
| Apple         | MacBookPro8,1               | [7ba1690c68](https://linux-hardware.org/?probe=7ba1690c68) | Nov 28, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [a7b7f4f100](https://linux-hardware.org/?probe=a7b7f4f100) | Nov 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AX05    | [c4a2ce46ca](https://linux-hardware.org/?probe=c4a2ce46ca) | Nov 24, 2022 |
| HUAWEI        | CREM-WXX9                   | [240694e932](https://linux-hardware.org/?probe=240694e932) | Nov 23, 2022 |
| HP            | Notebook                    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Dell          | G3 3579                     | [7f4d27ea26](https://linux-hardware.org/?probe=7f4d27ea26) | Nov 23, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Toshiba       | Satellite L45Dt-B           | [9cdcee20dc](https://linux-hardware.org/?probe=9cdcee20dc) | Nov 22, 2022 |
| Valve         | Jupiter                     | [e9f2caddf6](https://linux-hardware.org/?probe=e9f2caddf6) | Nov 21, 2022 |
| MSI           | Stealth GS66 12UGS          | [ca3d88f38d](https://linux-hardware.org/?probe=ca3d88f38d) | Nov 21, 2022 |
| Dell          | Latitude E5440              | [f423bbe9b0](https://linux-hardware.org/?probe=f423bbe9b0) | Nov 19, 2022 |
| Dell          | Latitude E5440              | [0f98fe6066](https://linux-hardware.org/?probe=0f98fe6066) | Nov 18, 2022 |
| HP            | Laptop 15-da2xxx            | [e55a0e2ae1](https://linux-hardware.org/?probe=e55a0e2ae1) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [c08218542c](https://linux-hardware.org/?probe=c08218542c) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [4830cb0a27](https://linux-hardware.org/?probe=4830cb0a27) | Nov 17, 2022 |
| ASUSTek       | X556UQK                     | [fb33c2bdea](https://linux-hardware.org/?probe=fb33c2bdea) | Nov 16, 2022 |
| ASUSTek       | X556UQK                     | [b4f8d67230](https://linux-hardware.org/?probe=b4f8d67230) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| HP            | Laptop 15-da2xxx            | [b1ed3e6190](https://linux-hardware.org/?probe=b1ed3e6190) | Nov 16, 2022 |
| HP            | EliteBook 820 G3            | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b9d92c6041](https://linux-hardware.org/?probe=b9d92c6041) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [61b131a3ae](https://linux-hardware.org/?probe=61b131a3ae) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [3f3280fa71](https://linux-hardware.org/?probe=3f3280fa71) | Nov 13, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [416c73c293](https://linux-hardware.org/?probe=416c73c293) | Nov 09, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [eac572ee3d](https://linux-hardware.org/?probe=eac572ee3d) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| Chuwi         | GemiBook Pro                | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Google        | Grunt                       | [dc9067b4b6](https://linux-hardware.org/?probe=dc9067b4b6) | Nov 07, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [20826ec148](https://linux-hardware.org/?probe=20826ec148) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [41e941e3ca](https://linux-hardware.org/?probe=41e941e3ca) | Nov 03, 2022 |
| HP            | Laptop 17-ca0xxx            | [af3aa996df](https://linux-hardware.org/?probe=af3aa996df) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [caaca6d1f1](https://linux-hardware.org/?probe=caaca6d1f1) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Toshiba       | Satellite L55-B             | [ca03715db3](https://linux-hardware.org/?probe=ca03715db3) | Nov 03, 2022 |
| Acer          | Aspire E5-522               | [32f73c64a6](https://linux-hardware.org/?probe=32f73c64a6) | Nov 02, 2022 |
| Acer          | Aspire E5-522               | [412b8c701e](https://linux-hardware.org/?probe=412b8c701e) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [95d825cd94](https://linux-hardware.org/?probe=95d825cd94) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| GPU Compan... | GWNR71517                   | [168f199ffd](https://linux-hardware.org/?probe=168f199ffd) | Oct 29, 2022 |
| Dell          | Latitude 3590               | [d1b6c7cd85](https://linux-hardware.org/?probe=d1b6c7cd85) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| GPU Compan... | GWNR71517                   | [e03f1db8e1](https://linux-hardware.org/?probe=e03f1db8e1) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Dell          | Latitude 9420               | [ab37e0d841](https://linux-hardware.org/?probe=ab37e0d841) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Dell          | Inspiron 3505               | [891f846aac](https://linux-hardware.org/?probe=891f846aac) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| HP            | Laptop 15-da2xxx            | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [914bab2302](https://linux-hardware.org/?probe=914bab2302) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| GPU Compan... | GWNR71517                   | [f467f29abf](https://linux-hardware.org/?probe=f467f29abf) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Lenovo        | G450 2949                   | [13c0232085](https://linux-hardware.org/?probe=13c0232085) | Oct 19, 2022 |
| Lenovo        | G450 2949                   | [1e5a91a31d](https://linux-hardware.org/?probe=1e5a91a31d) | Oct 18, 2022 |
| Dell          | Latitude 7430               | [d4d6f89390](https://linux-hardware.org/?probe=d4d6f89390) | Oct 18, 2022 |
| HP            | Unknown                     | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| Dell          | Vostro 14-3468              | [c0958ba47f](https://linux-hardware.org/?probe=c0958ba47f) | Oct 17, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| HP            | 245 G7 Notebook PC          | [c164c2ab59](https://linux-hardware.org/?probe=c164c2ab59) | Oct 16, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [87cf4b398b](https://linux-hardware.org/?probe=87cf4b398b) | Oct 16, 2022 |
| HUAWEI        | CREM-WXX9                   | [3edd19f985](https://linux-hardware.org/?probe=3edd19f985) | Oct 15, 2022 |
| Dell          | Latitude E5440              | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| HP            | Laptop 14-bw0xx             | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| Toshiba       | Satellite P55t-A            | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | GV62 8RD                    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| Dell          | System XPS L502X            | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| Dell          | Inspiron 3520               | [5cf6d495ff](https://linux-hardware.org/?probe=5cf6d495ff) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [167321509c](https://linux-hardware.org/?probe=167321509c) | Oct 07, 2022 |
| Apple         | MacBookPro8,1               | [0d9e169836](https://linux-hardware.org/?probe=0d9e169836) | Oct 06, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| HP            | ProBook 6470b               | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| HP            | Unknown                     | [72a00fa1a2](https://linux-hardware.org/?probe=72a00fa1a2) | Oct 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion                    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| GHIA          | LFI3H                       | [4233e4e6c5](https://linux-hardware.org/?probe=4233e4e6c5) | Sep 29, 2022 |
| GHIA          | LFI3H                       | [482e78460a](https://linux-hardware.org/?probe=482e78460a) | Sep 29, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [4f2655de78](https://linux-hardware.org/?probe=4f2655de78) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| Apple         | MacBookPro8,1               | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Dell          | Latitude E7440              | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Dell          | Latitude E5450              | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| HP            | Unknown                     | [63af86aa38](https://linux-hardware.org/?probe=63af86aa38) | Sep 25, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| Chuwi         | CoreBook XPro               | [5ace2b3ea5](https://linux-hardware.org/?probe=5ace2b3ea5) | Sep 23, 2022 |
| MSI           | Prestige 14Evo A11M         | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| ASUSTek       | G750JM                      | [2e53c11312](https://linux-hardware.org/?probe=2e53c11312) | Sep 22, 2022 |
| MSI           | GT70 2OC/2OD                | [c6a0b0d987](https://linux-hardware.org/?probe=c6a0b0d987) | Sep 22, 2022 |
| Lenovo        | G40-80 80E4                 | [575b85b038](https://linux-hardware.org/?probe=575b85b038) | Sep 21, 2022 |
| Lenovo        | G40-80 80E4                 | [18a0a2158c](https://linux-hardware.org/?probe=18a0a2158c) | Sep 21, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| American M... | XA133PR110                  | [b79d35c0bd](https://linux-hardware.org/?probe=b79d35c0bd) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| HP            | EliteBook 2740p             | [6643773237](https://linux-hardware.org/?probe=6643773237) | Sep 18, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| ASUSTek       | X555DG                      | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Toshiba       | Satellite L855              | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [0c6b0c35e6](https://linux-hardware.org/?probe=0c6b0c35e6) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [b4c9fcf4c3](https://linux-hardware.org/?probe=b4c9fcf4c3) | Sep 14, 2022 |
| Lanix         | AL V9                       | [03e7c7ece5](https://linux-hardware.org/?probe=03e7c7ece5) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| Chuwi         | GemiBook Pro                | [5b62dddb37](https://linux-hardware.org/?probe=5b62dddb37) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| Lanix         | AL V9                       | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| ASUSTek       | X553MA                      | [32c5b56788](https://linux-hardware.org/?probe=32c5b56788) | Sep 11, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| Gateway       | NE56R                       | [c928861fb0](https://linux-hardware.org/?probe=c928861fb0) | Sep 09, 2022 |
| Gateway       | NE56R                       | [3167a59b9b](https://linux-hardware.org/?probe=3167a59b9b) | Sep 09, 2022 |
| ASUSTek       | X553MA                      | [32edc5cfad](https://linux-hardware.org/?probe=32edc5cfad) | Sep 08, 2022 |
| Apple         | MacBook4,1                  | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Dell          | Latitude D410               | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| HP            | Laptop 15-bw0xx             | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| Dell          | Latitude E7450              | [de66677d3d](https://linux-hardware.org/?probe=de66677d3d) | Sep 03, 2022 |
| HP            | Pavilion 14                 | [7a2b6c5f4b](https://linux-hardware.org/?probe=7a2b6c5f4b) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [7da5af06fb](https://linux-hardware.org/?probe=7da5af06fb) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [c7b43caa52](https://linux-hardware.org/?probe=c7b43caa52) | Sep 01, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [bceac5a658](https://linux-hardware.org/?probe=bceac5a658) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6f169db96b](https://linux-hardware.org/?probe=6f169db96b) | Aug 29, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| HP            | 240 G7 Notebook PC          | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| HP            | ENVY m6 Notebook            | [c51af546e7](https://linux-hardware.org/?probe=c51af546e7) | Aug 22, 2022 |
| HP            | Pavilion dv7                | [81b7ddb4e9](https://linux-hardware.org/?probe=81b7ddb4e9) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [aa44fba5de](https://linux-hardware.org/?probe=aa44fba5de) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [21d9982f20](https://linux-hardware.org/?probe=21d9982f20) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HUAWEI        | EMD-WXX                     | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| HP            | 240 G7 Notebook PC          | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| HP            | Pavilion TS 14              | [145fc8369f](https://linux-hardware.org/?probe=145fc8369f) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| Toshiba       | Satellite P200              | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Sony          | VPCYB20AL                   | [f886e2ff98](https://linux-hardware.org/?probe=f886e2ff98) | Aug 10, 2022 |
| Lenovo        | L340-15API 81LW             | [50eca7fa1e](https://linux-hardware.org/?probe=50eca7fa1e) | Aug 10, 2022 |
| HUAWEI        | WRT-WX9                     | [f9c85afff2](https://linux-hardware.org/?probe=f9c85afff2) | Aug 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Google        | Blorb                       | [b893b34702](https://linux-hardware.org/?probe=b893b34702) | Aug 06, 2022 |
| Acer          | AO756                       | [4bc715a31c](https://linux-hardware.org/?probe=4bc715a31c) | Aug 05, 2022 |
| Dell          | Inspiron 5559               | [3e02305524](https://linux-hardware.org/?probe=3e02305524) | Aug 04, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| HP            | ProBook 4520s               | [8e03860e5f](https://linux-hardware.org/?probe=8e03860e5f) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [057703210a](https://linux-hardware.org/?probe=057703210a) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| HP            | ProBook 4520s               | [80024f9b67](https://linux-hardware.org/?probe=80024f9b67) | Jul 26, 2022 |
| HP            | 245 G7 Notebook PC          | [07c70033f5](https://linux-hardware.org/?probe=07c70033f5) | Jul 25, 2022 |
| Alienware     | M11xR3                      | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| Dell          | Inspiron 3505               | [5bec1168d0](https://linux-hardware.org/?probe=5bec1168d0) | Jul 22, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Unknown       | W1415A                      | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| Dell          | Latitude E7250              | [5fdb8cad05](https://linux-hardware.org/?probe=5fdb8cad05) | Jul 21, 2022 |
| GHIA          | Notebook                    | [2193ab1cd3](https://linux-hardware.org/?probe=2193ab1cd3) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Dell          | Inspiron 3421               | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [1cf6844d33](https://linux-hardware.org/?probe=1cf6844d33) | Jul 14, 2022 |
| Toshiba       | Satellite L55-B             | [0e0ba8274b](https://linux-hardware.org/?probe=0e0ba8274b) | Jul 13, 2022 |
| Toshiba       | Satellite L55-B             | [a7bebd622f](https://linux-hardware.org/?probe=a7bebd622f) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Dell          | Latitude E5530 non-vPro     | [0ab6a30f98](https://linux-hardware.org/?probe=0ab6a30f98) | Jul 12, 2022 |
| Sony          | VPCYB20AL                   | [c9645d6952](https://linux-hardware.org/?probe=c9645d6952) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| MSI           | GF63 Thin 11UC              | [ecfb5f39c5](https://linux-hardware.org/?probe=ecfb5f39c5) | Jul 09, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-51              | [0b57ab5b5b](https://linux-hardware.org/?probe=0b57ab5b5b) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7e53f712c5](https://linux-hardware.org/?probe=7e53f712c5) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| HP            | Pavilion dv4                | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [a5ad48eeb5](https://linux-hardware.org/?probe=a5ad48eeb5) | Jul 03, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [c364b347a5](https://linux-hardware.org/?probe=c364b347a5) | Jul 02, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| HUAWEI        | NBM-WXX9                    | [6ed674f77e](https://linux-hardware.org/?probe=6ed674f77e) | Jul 01, 2022 |
| Acer          | Aspire E5-573               | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| HP            | Compaq CQ45                 | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Dell          | Latitude 7420               | [3730ffb739](https://linux-hardware.org/?probe=3730ffb739) | Jun 27, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Sony          | VPCF236FM                   | [b2af243689](https://linux-hardware.org/?probe=b2af243689) | Jun 25, 2022 |
| Google        | Kip                         | [d21adde488](https://linux-hardware.org/?probe=d21adde488) | Jun 24, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68ca5e600d](https://linux-hardware.org/?probe=68ca5e600d) | Jun 18, 2022 |
| Apple         | MacBookAir6,1               | [665cfa446b](https://linux-hardware.org/?probe=665cfa446b) | Jun 18, 2022 |
| HP            | Laptop 15-bs0xx             | [aa89682b09](https://linux-hardware.org/?probe=aa89682b09) | Jun 18, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkPad T540p 20BE003NU... | [e05c2e42c2](https://linux-hardware.org/?probe=e05c2e42c2) | Jun 17, 2022 |
| Gateway       | NE513                       | [c33ad72253](https://linux-hardware.org/?probe=c33ad72253) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | IdeaPad Z480                | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| Dell          | Latitude E6410              | [6194911b41](https://linux-hardware.org/?probe=6194911b41) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| Lenovo        | Y50-70 20378                | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| Apple         | MacBookPro14,1              | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [005799b9bf](https://linux-hardware.org/?probe=005799b9bf) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Dell          | Studio XPS 1340             | [36f61b29b5](https://linux-hardware.org/?probe=36f61b29b5) | Jun 11, 2022 |
| HP            | Pavilion dv6                | [c8e7eea8fc](https://linux-hardware.org/?probe=c8e7eea8fc) | Jun 11, 2022 |
| Corporativ... | Neuron LT                   | [84ed262694](https://linux-hardware.org/?probe=84ed262694) | Jun 10, 2022 |
| Corporativ... | Neuron LT                   | [ad265d5197](https://linux-hardware.org/?probe=ad265d5197) | Jun 10, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [479a01b8d8](https://linux-hardware.org/?probe=479a01b8d8) | Jun 10, 2022 |
| ASUSTek       | K43E                        | [cd9e7dab5e](https://linux-hardware.org/?probe=cd9e7dab5e) | Jun 09, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Toshiba       | Satellite L55-B             | [38c0d1cebc](https://linux-hardware.org/?probe=38c0d1cebc) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| HP            | Laptop 15-dy2xxx            | [ecc580e75f](https://linux-hardware.org/?probe=ecc580e75f) | Jun 06, 2022 |
| HP            | Laptop 15-dy2xxx            | [e737d522f2](https://linux-hardware.org/?probe=e737d522f2) | Jun 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| EVOO          | EV-C-116-7                  | [1955955afc](https://linux-hardware.org/?probe=1955955afc) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a3e63f04e7](https://linux-hardware.org/?probe=a3e63f04e7) | May 31, 2022 |
| Dell          | G7 7588                     | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Inspiron 5547               | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| Lenovo        | IdeaPad S300 20197          | [fcb07ac9aa](https://linux-hardware.org/?probe=fcb07ac9aa) | May 31, 2022 |
| Lenovo        | IdeaPad Z480                | [b1cf8ca505](https://linux-hardware.org/?probe=b1cf8ca505) | May 30, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [55dfdf01c6](https://linux-hardware.org/?probe=55dfdf01c6) | May 29, 2022 |
| HP            | Presario CQ62               | [fe3cac8868](https://linux-hardware.org/?probe=fe3cac8868) | May 27, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| Acer          | Swift SF113-31              | [2bdba73cfa](https://linux-hardware.org/?probe=2bdba73cfa) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| HP            | Pavilion g4                 | [0c943e458a](https://linux-hardware.org/?probe=0c943e458a) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| ASUSTek       | X402CA                      | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| HUAWEI        | HVY-WXX9                    | [93bb32d1b2](https://linux-hardware.org/?probe=93bb32d1b2) | May 21, 2022 |
| Acer          | Aspire 5332                 | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| System76      | Oryx Pro                    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | S10-3                       | [b2eb29a65e](https://linux-hardware.org/?probe=b2eb29a65e) | May 14, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4316b121b1](https://linux-hardware.org/?probe=4316b121b1) | May 14, 2022 |
| Dell          | Studio 1558                 | [ccffb59f97](https://linux-hardware.org/?probe=ccffb59f97) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [2bd7babedc](https://linux-hardware.org/?probe=2bd7babedc) | May 13, 2022 |
| Toshiba       | TECRA Z50-A                 | [985d5869bf](https://linux-hardware.org/?probe=985d5869bf) | May 12, 2022 |
| Dell          | XPS 15 9550                 | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| Google        | Blooglet                    | [64b4f18c1c](https://linux-hardware.org/?probe=64b4f18c1c) | May 09, 2022 |
| Google        | Blooglet                    | [f3dc91bf66](https://linux-hardware.org/?probe=f3dc91bf66) | May 09, 2022 |
| HP            | Laptop 17z-ca300            | [c43f2b0e29](https://linux-hardware.org/?probe=c43f2b0e29) | May 08, 2022 |
| Acer          | Aspire ES1-531              | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| Acer          | Aspire F5-573               | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| HP            | Notebook                    | [04f5e602de](https://linux-hardware.org/?probe=04f5e602de) | May 07, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [46d0c349d6](https://linux-hardware.org/?probe=46d0c349d6) | May 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [38f5d37dcc](https://linux-hardware.org/?probe=38f5d37dcc) | May 07, 2022 |
| HP            | Pavilion 14                 | [2bd48eeb41](https://linux-hardware.org/?probe=2bd48eeb41) | May 06, 2022 |
| Apple         | MacBookAir6,2               | [d04d5e927d](https://linux-hardware.org/?probe=d04d5e927d) | May 05, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [4208da52ad](https://linux-hardware.org/?probe=4208da52ad) | May 04, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| Dell          | Latitude 7420               | [a0bd1ee0f4](https://linux-hardware.org/?probe=a0bd1ee0f4) | May 03, 2022 |
| Sony          | VPCF236FM                   | [ec0af02205](https://linux-hardware.org/?probe=ec0af02205) | May 02, 2022 |
| Acer          | Aspire V5-561               | [e9dfda82d4](https://linux-hardware.org/?probe=e9dfda82d4) | May 02, 2022 |
| Dell          | Latitude E5550              | [42a576bd39](https://linux-hardware.org/?probe=42a576bd39) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [fbb6d3b97e](https://linux-hardware.org/?probe=fbb6d3b97e) | May 01, 2022 |
| HP            | Pavilion 13 x2 PC           | [d594f3335c](https://linux-hardware.org/?probe=d594f3335c) | May 01, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f5d70fb9d3](https://linux-hardware.org/?probe=f5d70fb9d3) | Apr 30, 2022 |
| Lenovo        | S10-3                       | [712c2dced9](https://linux-hardware.org/?probe=712c2dced9) | Apr 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Toshiba       | Satellite L735D             | [4bd23809e6](https://linux-hardware.org/?probe=4bd23809e6) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| Dell          | Inspiron 5577               | [0925d92173](https://linux-hardware.org/?probe=0925d92173) | Apr 25, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| ASUSTek       | K46CA                       | [e762eba391](https://linux-hardware.org/?probe=e762eba391) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| Chuwi         | Unknown                     | [96105ecbb2](https://linux-hardware.org/?probe=96105ecbb2) | Apr 23, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [55186a3c2e](https://linux-hardware.org/?probe=55186a3c2e) | Apr 18, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Acer          | Aspire R3-131T              | [776575ecdb](https://linux-hardware.org/?probe=776575ecdb) | Apr 16, 2022 |
| Lenovo        | G40-45 80E1                 | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Sony          | VPCEE23FX                   | [4c7634a096](https://linux-hardware.org/?probe=4c7634a096) | Apr 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [25c2200e11](https://linux-hardware.org/?probe=25c2200e11) | Apr 14, 2022 |
| HP            | Laptop 14-cm0xxx            | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Acer          | Nitro AN515-41              | [b938e715f4](https://linux-hardware.org/?probe=b938e715f4) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [5d153a1030](https://linux-hardware.org/?probe=5d153a1030) | Apr 12, 2022 |
| HP            | ZBook 15                    | [c8c2248854](https://linux-hardware.org/?probe=c8c2248854) | Apr 11, 2022 |
| Toshiba       | Satellite L735D             | [47f0119635](https://linux-hardware.org/?probe=47f0119635) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| HP            | Laptop 15-da1xxx            | [8d9c212045](https://linux-hardware.org/?probe=8d9c212045) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| HP            | ZBook 15                    | [ee70932ef2](https://linux-hardware.org/?probe=ee70932ef2) | Apr 09, 2022 |
| HP            | Pavilion dv6                | [9d37acefa0](https://linux-hardware.org/?probe=9d37acefa0) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| Toshiba       | Satellite P775              | [3acd0b8861](https://linux-hardware.org/?probe=3acd0b8861) | Apr 08, 2022 |
| Dell          | Inspiron 5570               | [801e4fdab1](https://linux-hardware.org/?probe=801e4fdab1) | Apr 07, 2022 |
| Dell          | Latitude E5440              | [18a9d37c02](https://linux-hardware.org/?probe=18a9d37c02) | Apr 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [e168714dee](https://linux-hardware.org/?probe=e168714dee) | Apr 06, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [9d26a79ca6](https://linux-hardware.org/?probe=9d26a79ca6) | Apr 05, 2022 |
| HP            | 245 G7 Notebook PC          | [54db9ac27f](https://linux-hardware.org/?probe=54db9ac27f) | Apr 05, 2022 |
| HP            | Pavilion 14                 | [136105017c](https://linux-hardware.org/?probe=136105017c) | Apr 04, 2022 |
| HP            | Presario CQ56               | [7233c29381](https://linux-hardware.org/?probe=7233c29381) | Apr 03, 2022 |
| Toshiba       | Satellite S855D             | [45b97d03ed](https://linux-hardware.org/?probe=45b97d03ed) | Apr 03, 2022 |
| Apple         | MacBookPro9,2               | [f646cb03d2](https://linux-hardware.org/?probe=f646cb03d2) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| HUAWEI        | HVY-WXX9                    | [5af7df2c2a](https://linux-hardware.org/?probe=5af7df2c2a) | Mar 30, 2022 |
| Acer          | Aspire one                  | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d346f2a1b1](https://linux-hardware.org/?probe=d346f2a1b1) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [67475db5e9](https://linux-hardware.org/?probe=67475db5e9) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [2c7227662f](https://linux-hardware.org/?probe=2c7227662f) | Mar 29, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Dell          | Latitude E6510              | [4feee8c983](https://linux-hardware.org/?probe=4feee8c983) | Mar 26, 2022 |
| HP            | Pavilion 11 x360 PC         | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b955479cc](https://linux-hardware.org/?probe=4b955479cc) | Mar 24, 2022 |
| System76      | Gazelle                     | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| Acer          | Nitro AN515-54              | [4bb7650e38](https://linux-hardware.org/?probe=4bb7650e38) | Mar 23, 2022 |
| Lenovo        | Unknown                     | [661ddbd0df](https://linux-hardware.org/?probe=661ddbd0df) | Mar 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [e1f3c645b5](https://linux-hardware.org/?probe=e1f3c645b5) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [ed01dc4465](https://linux-hardware.org/?probe=ed01dc4465) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | [6c0caa0de4](https://linux-hardware.org/?probe=6c0caa0de4) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1PD0M    | [dbed1562e8](https://linux-hardware.org/?probe=dbed1562e8) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| HP            | Pavilion 15                 | [29ac5f13cd](https://linux-hardware.org/?probe=29ac5f13cd) | Mar 16, 2022 |
| Apple         | MacBookPro15,2              | [a77a1ff925](https://linux-hardware.org/?probe=a77a1ff925) | Mar 16, 2022 |
| Dell          | Latitude E6220              | [0dbd85da47](https://linux-hardware.org/?probe=0dbd85da47) | Mar 13, 2022 |
| Dell          | G5 5505                     | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | ProBook 650 G1              | [046572a251](https://linux-hardware.org/?probe=046572a251) | Mar 09, 2022 |
| Dell          | XPS 15 9570                 | [dd0ebc18ce](https://linux-hardware.org/?probe=dd0ebc18ce) | Mar 07, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Chuwi         | GemiBook                    | [60146fd918](https://linux-hardware.org/?probe=60146fd918) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| Unknown       | KN12A                       | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| Panasonic     | CF-30KTPA9NP                | [fffe3abd97](https://linux-hardware.org/?probe=fffe3abd97) | Mar 05, 2022 |
| Lenovo        | G40-70 20369                | [fd797ac0c1](https://linux-hardware.org/?probe=fd797ac0c1) | Mar 03, 2022 |
| Chuwi         | GemiBook                    | [af28b0f0d8](https://linux-hardware.org/?probe=af28b0f0d8) | Mar 02, 2022 |
| Timi          | TM1612                      | [dc1c26b3a9](https://linux-hardware.org/?probe=dc1c26b3a9) | Mar 01, 2022 |
| Sony          | VGN-Z690N                   | [d3465abe44](https://linux-hardware.org/?probe=d3465abe44) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [0a0e3feff6](https://linux-hardware.org/?probe=0a0e3feff6) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [2b791434ce](https://linux-hardware.org/?probe=2b791434ce) | Feb 28, 2022 |
| Toshiba       | Satellite C655D             | [10f38d005e](https://linux-hardware.org/?probe=10f38d005e) | Feb 28, 2022 |
| ASUSTek       | X401A                       | [e97f529634](https://linux-hardware.org/?probe=e97f529634) | Feb 28, 2022 |
| Lenovo        | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Apple         | MacBookAir5,2               | [fb0403c8b8](https://linux-hardware.org/?probe=fb0403c8b8) | Feb 26, 2022 |
| Timi          | RedmiBook 13 R              | [a74bea030c](https://linux-hardware.org/?probe=a74bea030c) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | [318a4d1d35](https://linux-hardware.org/?probe=318a4d1d35) | Feb 25, 2022 |
| MSI           | GL75 Leopard 10SDK          | [6a14728490](https://linux-hardware.org/?probe=6a14728490) | Feb 24, 2022 |
| Apple         | MacBookPro15,2              | [aebbda3f2d](https://linux-hardware.org/?probe=aebbda3f2d) | Feb 23, 2022 |
| Apple         | MacBookPro15,2              | [302836f9d3](https://linux-hardware.org/?probe=302836f9d3) | Feb 23, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [fe042017e6](https://linux-hardware.org/?probe=fe042017e6) | Feb 23, 2022 |
| ASUSTek       | X45U                        | [41f11e9487](https://linux-hardware.org/?probe=41f11e9487) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| Acer          | Aspire A315-56              | [26d9aa49e7](https://linux-hardware.org/?probe=26d9aa49e7) | Feb 19, 2022 |
| HP            | ProBook 4530s               | [26a60b46d2](https://linux-hardware.org/?probe=26a60b46d2) | Feb 18, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [91540e8aa6](https://linux-hardware.org/?probe=91540e8aa6) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e5d5d5afe](https://linux-hardware.org/?probe=3e5d5d5afe) | Feb 18, 2022 |
| Hyundai Te... | Thinnote 13                 | [16d5bcb194](https://linux-hardware.org/?probe=16d5bcb194) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [eb1d4cf9d8](https://linux-hardware.org/?probe=eb1d4cf9d8) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | [38fe80e2a8](https://linux-hardware.org/?probe=38fe80e2a8) | Feb 17, 2022 |
| Acer          | Aspire A315-56              | [cf4c296719](https://linux-hardware.org/?probe=cf4c296719) | Feb 17, 2022 |
| Apple         | MacBookPro14,1              | [f7c7bd4baf](https://linux-hardware.org/?probe=f7c7bd4baf) | Feb 17, 2022 |
| Acer          | TravelMate P214-53          | [4d1c34fef7](https://linux-hardware.org/?probe=4d1c34fef7) | Feb 17, 2022 |
| Lenovo        | G40-45 80E1                 | [f181193143](https://linux-hardware.org/?probe=f181193143) | Feb 16, 2022 |
| Lenovo        | G40-45 80E1                 | [88c9f0db96](https://linux-hardware.org/?probe=88c9f0db96) | Feb 16, 2022 |
| Dell          | Latitude E7440              | [1efc982c71](https://linux-hardware.org/?probe=1efc982c71) | Feb 16, 2022 |
| HP            | Laptop 15-da0xxx            | [84171dc3cd](https://linux-hardware.org/?probe=84171dc3cd) | Feb 16, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [34fff5bf39](https://linux-hardware.org/?probe=34fff5bf39) | Feb 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [85d4a8278e](https://linux-hardware.org/?probe=85d4a8278e) | Feb 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a533f0d469](https://linux-hardware.org/?probe=a533f0d469) | Feb 14, 2022 |
| HP            | 655                         | [b0189b16b1](https://linux-hardware.org/?probe=b0189b16b1) | Feb 14, 2022 |
| HP            | Laptop 15-da2xxx            | [51dfcad0d4](https://linux-hardware.org/?probe=51dfcad0d4) | Feb 14, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [429d06ed33](https://linux-hardware.org/?probe=429d06ed33) | Feb 13, 2022 |
| HP            | 245 G1                      | [30c3eb937a](https://linux-hardware.org/?probe=30c3eb937a) | Feb 13, 2022 |
| Dell          | Inspiron 5537               | [3ef228db80](https://linux-hardware.org/?probe=3ef228db80) | Feb 11, 2022 |
| Dell          | Latitude 7420               | [2547d7836e](https://linux-hardware.org/?probe=2547d7836e) | Feb 11, 2022 |
| HP            | Laptop 15-dw0xxx            | [16157beba6](https://linux-hardware.org/?probe=16157beba6) | Feb 11, 2022 |
| Sony          | VGN-Z575FN                  | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [cc5c3cd3d0](https://linux-hardware.org/?probe=cc5c3cd3d0) | Feb 11, 2022 |
| Lenovo        | ThinkPad T430 2349L38       | [85d1c3705e](https://linux-hardware.org/?probe=85d1c3705e) | Feb 09, 2022 |
| Dell          | Inspiron 5567               | [eec17e2cdc](https://linux-hardware.org/?probe=eec17e2cdc) | Feb 09, 2022 |
| HP            | ProBook 645 G1              | [98bdb87a7c](https://linux-hardware.org/?probe=98bdb87a7c) | Feb 08, 2022 |
| Lanix         | A V16                       | [2cbb463004](https://linux-hardware.org/?probe=2cbb463004) | Feb 08, 2022 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [78011da841](https://linux-hardware.org/?probe=78011da841) | Feb 07, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [7196de2b08](https://linux-hardware.org/?probe=7196de2b08) | Feb 06, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Sony          | VPCF236FM                   | [784b1b0c3b](https://linux-hardware.org/?probe=784b1b0c3b) | Feb 06, 2022 |
| Lanix         | NEURON_FLEX                 | [566f9282eb](https://linux-hardware.org/?probe=566f9282eb) | Feb 05, 2022 |
| HP            | Laptop 17-cn0xxx            | [cfdee7d88e](https://linux-hardware.org/?probe=cfdee7d88e) | Feb 05, 2022 |
| Lanix         | NEURON_FLEX                 | [90d39053df](https://linux-hardware.org/?probe=90d39053df) | Feb 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a11c55e55](https://linux-hardware.org/?probe=5a11c55e55) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| Dell          | Latitude 3420               | [98d388a60d](https://linux-hardware.org/?probe=98d388a60d) | Feb 03, 2022 |
| Lenovo        | V14-ARE 82DQ                | [b3cfaa23eb](https://linux-hardware.org/?probe=b3cfaa23eb) | Feb 01, 2022 |
| Lenovo        | Rev B 20YM                  | [83c63da100](https://linux-hardware.org/?probe=83c63da100) | Feb 01, 2022 |
| Dell          | Latitude 3330               | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| Dell          | Latitude 3330               | [61a24473d4](https://linux-hardware.org/?probe=61a24473d4) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [2248ba47d2](https://linux-hardware.org/?probe=2248ba47d2) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [74eb47cb2f](https://linux-hardware.org/?probe=74eb47cb2f) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| HP            | Laptop 14-cm0xxx            | [36fa473b25](https://linux-hardware.org/?probe=36fa473b25) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | [f25c578f5a](https://linux-hardware.org/?probe=f25c578f5a) | Jan 28, 2022 |
| Timi          | TM1701                      | [c4387537b3](https://linux-hardware.org/?probe=c4387537b3) | Jan 28, 2022 |
| Dell          | Latitude E6410              | [8f9cad1934](https://linux-hardware.org/?probe=8f9cad1934) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWA15L0... | [6e1153bb21](https://linux-hardware.org/?probe=6e1153bb21) | Jan 28, 2022 |
| Timi          | TM1701                      | [90877c2a8a](https://linux-hardware.org/?probe=90877c2a8a) | Jan 28, 2022 |
| HP            | EliteBook 8460p             | [49ab3da4e2](https://linux-hardware.org/?probe=49ab3da4e2) | Jan 28, 2022 |
| System76      | Gazelle                     | [4066e8f06a](https://linux-hardware.org/?probe=4066e8f06a) | Jan 24, 2022 |
| ASUSTek       | B551LG                      | [4df03afb9f](https://linux-hardware.org/?probe=4df03afb9f) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f9deb1d329](https://linux-hardware.org/?probe=f9deb1d329) | Jan 20, 2022 |
| Alienware     | x15 R1                      | [5f9dce49b3](https://linux-hardware.org/?probe=5f9dce49b3) | Jan 20, 2022 |
| Acer          | Predator G9-591             | [187b246949](https://linux-hardware.org/?probe=187b246949) | Jan 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [efdc064669](https://linux-hardware.org/?probe=efdc064669) | Jan 19, 2022 |
| Dell          | Latitude E6400              | [05d5d5de96](https://linux-hardware.org/?probe=05d5d5de96) | Jan 17, 2022 |
| Google        | Ultima                      | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Dell          | XPS 15 9570                 | [eb68d3d4dd](https://linux-hardware.org/?probe=eb68d3d4dd) | Jan 15, 2022 |
| Dell          | Inspiron 1525               | [286a7e58fd](https://linux-hardware.org/?probe=286a7e58fd) | Jan 14, 2022 |
| Dell          | Inspiron 1525               | [981a9aff50](https://linux-hardware.org/?probe=981a9aff50) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2d83a27067](https://linux-hardware.org/?probe=2d83a27067) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Dell          | Inspiron 3505               | [85c2838614](https://linux-hardware.org/?probe=85c2838614) | Jan 11, 2022 |
| Acer          | Aspire F5-573               | [2bf3f44e95](https://linux-hardware.org/?probe=2bf3f44e95) | Jan 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [99a245965c](https://linux-hardware.org/?probe=99a245965c) | Jan 09, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Apple         | MacBook3,1                  | [b384dcb200](https://linux-hardware.org/?probe=b384dcb200) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [1660421dd9](https://linux-hardware.org/?probe=1660421dd9) | Jan 05, 2022 |
| MSI           | Bravo 15 A4DDR              | [d9aa580e5f](https://linux-hardware.org/?probe=d9aa580e5f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [643f4e101f](https://linux-hardware.org/?probe=643f4e101f) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [ca3df238bc](https://linux-hardware.org/?probe=ca3df238bc) | Jan 05, 2022 |
| HP            | Pavilion 14                 | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| Acer          | Aspire E3-112M              | [466004173b](https://linux-hardware.org/?probe=466004173b) | Jan 04, 2022 |
| Lenovo        | ThinkPad W530 24382HU       | [5a4cc794e4](https://linux-hardware.org/?probe=5a4cc794e4) | Jan 02, 2022 |
| Lanix         | NeuronALV5                  | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| ASUSTek       | G75VW                       | [ffda51867b](https://linux-hardware.org/?probe=ffda51867b) | Jan 01, 2022 |
| eMachines     | E525                        | [192bbb8b30](https://linux-hardware.org/?probe=192bbb8b30) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Alienware     | 17 R3                       | [d5f4157f56](https://linux-hardware.org/?probe=d5f4157f56) | Dec 30, 2021 |
| Alienware     | 17 R3                       | [6c4813d3fd](https://linux-hardware.org/?probe=6c4813d3fd) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | [de9115a89c](https://linux-hardware.org/?probe=de9115a89c) | Dec 30, 2021 |
| Sony          | SVF14215CLW                 | [bf4fd6e13c](https://linux-hardware.org/?probe=bf4fd6e13c) | Dec 30, 2021 |
| HP            | ZBook 15u G3                | [e220b55c78](https://linux-hardware.org/?probe=e220b55c78) | Dec 30, 2021 |
| ASUSTek       | K43E                        | [38e1c3f86f](https://linux-hardware.org/?probe=38e1c3f86f) | Dec 30, 2021 |
| HUAWEI        | WRTD-WXX9                   | [0184868fb6](https://linux-hardware.org/?probe=0184868fb6) | Dec 29, 2021 |
| HP            | EliteBook 8460p             | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Sony          | VPCEA35FL                   | [6c2b68633d](https://linux-hardware.org/?probe=6c2b68633d) | Dec 27, 2021 |
| HP            | ZBook 15u G3                | [f770dacb13](https://linux-hardware.org/?probe=f770dacb13) | Dec 25, 2021 |
| Acer          | Aspire 4752                 | [bb08100c63](https://linux-hardware.org/?probe=bb08100c63) | Dec 24, 2021 |
| MSI           | GF65 Thin 9SEXR             | [2be4e41c8e](https://linux-hardware.org/?probe=2be4e41c8e) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| HP            | Pavilion dv4                | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Apple         | MacBookPro14,1              | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [d14536043e](https://linux-hardware.org/?probe=d14536043e) | Dec 20, 2021 |
| HUAWEI        | MACH-WX9                    | [033e872459](https://linux-hardware.org/?probe=033e872459) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HP            | 14                          | [921783a9be](https://linux-hardware.org/?probe=921783a9be) | Dec 17, 2021 |
| ASUSTek       | X541NA                      | [70801591a7](https://linux-hardware.org/?probe=70801591a7) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [66c985876e](https://linux-hardware.org/?probe=66c985876e) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [ca0c96e24b](https://linux-hardware.org/?probe=ca0c96e24b) | Dec 15, 2021 |
| ASUSTek       | N53SV                       | [c17076e55c](https://linux-hardware.org/?probe=c17076e55c) | Dec 15, 2021 |
| Toshiba       | TECRA Z50-A                 | [0119ac4373](https://linux-hardware.org/?probe=0119ac4373) | Dec 15, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [191acd1645](https://linux-hardware.org/?probe=191acd1645) | Dec 14, 2021 |
| Acer          | Aspire 4352                 | [f87ff266d6](https://linux-hardware.org/?probe=f87ff266d6) | Dec 13, 2021 |
| Acer          | Aspire 4352                 | [38f2bc6cc7](https://linux-hardware.org/?probe=38f2bc6cc7) | Dec 13, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [2e8509fb8b](https://linux-hardware.org/?probe=2e8509fb8b) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| Timi          | TM1612                      | [1179aed154](https://linux-hardware.org/?probe=1179aed154) | Dec 12, 2021 |
| Dell          | Latitude E5400              | [3ce40a821b](https://linux-hardware.org/?probe=3ce40a821b) | Dec 09, 2021 |
| Gateway       | NE511                       | [ca37375600](https://linux-hardware.org/?probe=ca37375600) | Dec 09, 2021 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [1533118145](https://linux-hardware.org/?probe=1533118145) | Dec 09, 2021 |
| HONOR         | NBR-WAX9                    | [e4edda2131](https://linux-hardware.org/?probe=e4edda2131) | Dec 08, 2021 |
| Lenovo        | ThinkPad W520 4284D47       | [a48239fba8](https://linux-hardware.org/?probe=a48239fba8) | Dec 08, 2021 |
| HUAWEI        | HVY-WXX9                    | [89330570db](https://linux-hardware.org/?probe=89330570db) | Dec 07, 2021 |
| HUAWEI        | HVY-WXX9                    | [7ff7601d59](https://linux-hardware.org/?probe=7ff7601d59) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Dell          | Vostro 3405                 | [b2dc2ac6b8](https://linux-hardware.org/?probe=b2dc2ac6b8) | Dec 05, 2021 |
| Lenovo        | G50-45 80E3                 | [cf43f05660](https://linux-hardware.org/?probe=cf43f05660) | Dec 03, 2021 |
| HP            | Laptop 15-db0xxx            | [4993feea8f](https://linux-hardware.org/?probe=4993feea8f) | Dec 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4855fe75cb](https://linux-hardware.org/?probe=4855fe75cb) | Dec 01, 2021 |
| HP            | Pavilion dv5                | [71ea9a6485](https://linux-hardware.org/?probe=71ea9a6485) | Nov 30, 2021 |
| HUAWEI        | HVY-WXX9                    | [c6289480ca](https://linux-hardware.org/?probe=c6289480ca) | Nov 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [7569ef6338](https://linux-hardware.org/?probe=7569ef6338) | Nov 26, 2021 |
| Dell          | Latitude 3520               | [dfb19a422e](https://linux-hardware.org/?probe=dfb19a422e) | Nov 25, 2021 |
| Dell          | Latitude 3520               | [a0271563a5](https://linux-hardware.org/?probe=a0271563a5) | Nov 25, 2021 |
| Dell          | Inspiron 3505               | [9d28cad38c](https://linux-hardware.org/?probe=9d28cad38c) | Nov 24, 2021 |
| Alienware     | m15 R6                      | [7a71325757](https://linux-hardware.org/?probe=7a71325757) | Nov 24, 2021 |
| HP            | Laptop 15-da2xxx            | [eade5e3428](https://linux-hardware.org/?probe=eade5e3428) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | [8278dcbd86](https://linux-hardware.org/?probe=8278dcbd86) | Nov 23, 2021 |
| MSI           | Prestige 14Evo A11M         | [ecc3ddf24a](https://linux-hardware.org/?probe=ecc3ddf24a) | Nov 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [af11f87974](https://linux-hardware.org/?probe=af11f87974) | Nov 22, 2021 |
| HP            | Laptop 14-cm0xxx            | [55e4412774](https://linux-hardware.org/?probe=55e4412774) | Nov 20, 2021 |
| Lenovo        | G475 20080                  | [98bc985284](https://linux-hardware.org/?probe=98bc985284) | Nov 18, 2021 |
| Dell          | System XPS L502X            | [8d247d71f2](https://linux-hardware.org/?probe=8d247d71f2) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| Sony          | VPCF236FM                   | [70cffc5595](https://linux-hardware.org/?probe=70cffc5595) | Nov 16, 2021 |
| Dell          | Latitude E6400              | [e86a11de03](https://linux-hardware.org/?probe=e86a11de03) | Nov 15, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [5df470b888](https://linux-hardware.org/?probe=5df470b888) | Nov 15, 2021 |
| HP            | Pavilion g4                 | [e82daa0aba](https://linux-hardware.org/?probe=e82daa0aba) | Nov 13, 2021 |
| HP            | Pavilion g4                 | [ec71ab6f0c](https://linux-hardware.org/?probe=ec71ab6f0c) | Nov 12, 2021 |
| Dell          | Inspiron 1501               | [94ca9e7f47](https://linux-hardware.org/?probe=94ca9e7f47) | Nov 12, 2021 |
| Sony          | SVF14211CLB                 | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| HP            | ProBook 645 G2              | [beada5c26b](https://linux-hardware.org/?probe=beada5c26b) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | [64b38adff8](https://linux-hardware.org/?probe=64b38adff8) | Nov 09, 2021 |
| HP            | Laptop 15-dy1xxx            | [e019dfb216](https://linux-hardware.org/?probe=e019dfb216) | Nov 09, 2021 |
| Dell          | XPS 15 9570                 | [a990ce7acd](https://linux-hardware.org/?probe=a990ce7acd) | Nov 08, 2021 |
| Sony          | VPCF236FM                   | [dda9f712f8](https://linux-hardware.org/?probe=dda9f712f8) | Nov 07, 2021 |
| Unknown       | Unknown                     | [38d3058206](https://linux-hardware.org/?probe=38d3058206) | Nov 05, 2021 |
| Unknown       | Unknown                     | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| ASUSTek       | T100TA                      | [7ac20ab25f](https://linux-hardware.org/?probe=7ac20ab25f) | Nov 03, 2021 |
| ASUSTek       | T100TA                      | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [d7c67d8ce7](https://linux-hardware.org/?probe=d7c67d8ce7) | Nov 02, 2021 |
| System76      | Gazelle                     | [09a256c5ae](https://linux-hardware.org/?probe=09a256c5ae) | Nov 02, 2021 |
| System76      | Gazelle                     | [09da0264ca](https://linux-hardware.org/?probe=09da0264ca) | Nov 01, 2021 |
| Gateway       | NV42                        | [8f46bc202f](https://linux-hardware.org/?probe=8f46bc202f) | Nov 01, 2021 |
| Toshiba       | Satellite P105              | [1b17b5c927](https://linux-hardware.org/?probe=1b17b5c927) | Oct 31, 2021 |
| Toshiba       | Satellite P105              | [8f6268031e](https://linux-hardware.org/?probe=8f6268031e) | Oct 31, 2021 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [2fca11cf26](https://linux-hardware.org/?probe=2fca11cf26) | Oct 31, 2021 |
| Dell          | Inspiron 3537               | [0812a6b105](https://linux-hardware.org/?probe=0812a6b105) | Oct 29, 2021 |
| Dell          | Inspiron 3537               | [0e2d73ad29](https://linux-hardware.org/?probe=0e2d73ad29) | Oct 29, 2021 |
| HP            | Laptop 17z-ca300            | [0071faabac](https://linux-hardware.org/?probe=0071faabac) | Oct 29, 2021 |
| HP            | Notebook                    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| Dell          | Studio 1535                 | [69dc8fefa7](https://linux-hardware.org/?probe=69dc8fefa7) | Oct 27, 2021 |
| Dell          | Studio 1535                 | [3779b20704](https://linux-hardware.org/?probe=3779b20704) | Oct 27, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| HP            | Laptop 15-db0xxx            | [57be86b920](https://linux-hardware.org/?probe=57be86b920) | Oct 24, 2021 |
| Dell          | Inspiron 1545               | [e8e9a85406](https://linux-hardware.org/?probe=e8e9a85406) | Oct 23, 2021 |
| HP            | 240 G4 Notebook PC          | [b4cd0bde35](https://linux-hardware.org/?probe=b4cd0bde35) | Oct 23, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [20123f6b2f](https://linux-hardware.org/?probe=20123f6b2f) | Oct 23, 2021 |
| Dell          | Inspiron 1545               | [172b30ebe0](https://linux-hardware.org/?probe=172b30ebe0) | Oct 23, 2021 |
| Dell          | Latitude 5400               | [6a14ed2d5e](https://linux-hardware.org/?probe=6a14ed2d5e) | Oct 21, 2021 |
| HP            | Pavilion dv5                | [74cee5b7a8](https://linux-hardware.org/?probe=74cee5b7a8) | Oct 20, 2021 |
| Acer          | Aspire V5-122P              | [14086a6760](https://linux-hardware.org/?probe=14086a6760) | Oct 19, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [90aa462368](https://linux-hardware.org/?probe=90aa462368) | Oct 18, 2021 |
| Acer          | Aspire E5-523               | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| HP            | Compaq Presario CQ50        | [bb34275819](https://linux-hardware.org/?probe=bb34275819) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [b4c6139d09](https://linux-hardware.org/?probe=b4c6139d09) | Oct 17, 2021 |
| Sony          | SVE14A15FLB                 | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Acer          | Aspire A514-53              | [ef16468238](https://linux-hardware.org/?probe=ef16468238) | Oct 13, 2021 |
| Sony          | SVE14A15FLB                 | [51170d9250](https://linux-hardware.org/?probe=51170d9250) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [bdc66de1e6](https://linux-hardware.org/?probe=bdc66de1e6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [90dd918da6](https://linux-hardware.org/?probe=90dd918da6) | Oct 11, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0562199997](https://linux-hardware.org/?probe=0562199997) | Oct 11, 2021 |
| HP            | EliteBook 820 G2            | [96da43b986](https://linux-hardware.org/?probe=96da43b986) | Oct 11, 2021 |
| Toshiba       | Satellite A215              | [06c3b56836](https://linux-hardware.org/?probe=06c3b56836) | Oct 11, 2021 |
| ASUSTek       | N61Jq                       | [2307cb57c4](https://linux-hardware.org/?probe=2307cb57c4) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [564dd05308](https://linux-hardware.org/?probe=564dd05308) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [01f8341213](https://linux-hardware.org/?probe=01f8341213) | Oct 04, 2021 |
| Lenovo        | ThinkPad X220 4291T5Q       | [d31646221c](https://linux-hardware.org/?probe=d31646221c) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| ASUSTek       | T102HA                      | [0a301456dc](https://linux-hardware.org/?probe=0a301456dc) | Oct 03, 2021 |
| ASUSTek       | T102HA                      | [16e83f5564](https://linux-hardware.org/?probe=16e83f5564) | Oct 03, 2021 |
| MSI           | GE72 6QD                    | [a8713aca99](https://linux-hardware.org/?probe=a8713aca99) | Oct 01, 2021 |
| Eluktronic... | RP-15                       | [c147de5b16](https://linux-hardware.org/?probe=c147de5b16) | Sep 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [2692ea7a93](https://linux-hardware.org/?probe=2692ea7a93) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| Dell          | Latitude 5491               | [197b1a5c35](https://linux-hardware.org/?probe=197b1a5c35) | Sep 29, 2021 |
| Sony          | VGN-NR330FE                 | [9222a5b0bf](https://linux-hardware.org/?probe=9222a5b0bf) | Sep 26, 2021 |
| Sony          | VGN-NR330FE                 | [4e7013363c](https://linux-hardware.org/?probe=4e7013363c) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | [72bee59f14](https://linux-hardware.org/?probe=72bee59f14) | Sep 26, 2021 |
| Dell          | Latitude E6440              | [940e015781](https://linux-hardware.org/?probe=940e015781) | Sep 24, 2021 |
| Dell          | Latitude E6440              | [3b8c430d4d](https://linux-hardware.org/?probe=3b8c430d4d) | Sep 24, 2021 |
| Google        | Ekko                        | [8760e0b36c](https://linux-hardware.org/?probe=8760e0b36c) | Sep 24, 2021 |
| Google        | Ekko                        | [0d6d5cc44a](https://linux-hardware.org/?probe=0d6d5cc44a) | Sep 23, 2021 |
| EVOO          | EG-LP10                     | [e6ab927226](https://linux-hardware.org/?probe=e6ab927226) | Sep 22, 2021 |
| Dell          | Latitude E6440              | [45f88af089](https://linux-hardware.org/?probe=45f88af089) | Sep 22, 2021 |
| Dell          | Latitude E6440              | [28a8dacd93](https://linux-hardware.org/?probe=28a8dacd93) | Sep 22, 2021 |
| Sony          | VGN-CR360FE                 | [db32680a97](https://linux-hardware.org/?probe=db32680a97) | Sep 22, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [2d0d73c751](https://linux-hardware.org/?probe=2d0d73c751) | Sep 19, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [a2bbae72c0](https://linux-hardware.org/?probe=a2bbae72c0) | Sep 18, 2021 |
| Toshiba       | Satellite L15W-B            | [3871a3c4fc](https://linux-hardware.org/?probe=3871a3c4fc) | Sep 18, 2021 |
| Acer          | AO751h                      | [d217a1c6b7](https://linux-hardware.org/?probe=d217a1c6b7) | Sep 18, 2021 |
| Dell          | Inspiron 5577               | [3c89bcae88](https://linux-hardware.org/?probe=3c89bcae88) | Sep 18, 2021 |
| Acer          | Aspire E5-551               | [223b8d9942](https://linux-hardware.org/?probe=223b8d9942) | Sep 18, 2021 |
| Dell          | Precision 5540              | [5f6d259dce](https://linux-hardware.org/?probe=5f6d259dce) | Sep 18, 2021 |
| Dell          | XPS 15 9570                 | [cc48078a68](https://linux-hardware.org/?probe=cc48078a68) | Sep 16, 2021 |
| Sony          | VGN-CS140F                  | [a7e19c8a44](https://linux-hardware.org/?probe=a7e19c8a44) | Sep 16, 2021 |
| Lenovo        | B40-45 20394                | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Notebook                    | [c3bcf38e50](https://linux-hardware.org/?probe=c3bcf38e50) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Mini 110-3500               | [a4dd2b26bf](https://linux-hardware.org/?probe=a4dd2b26bf) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [69338ada32](https://linux-hardware.org/?probe=69338ada32) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [57f772fc9f](https://linux-hardware.org/?probe=57f772fc9f) | Sep 12, 2021 |
| Sony          | VPCCW25FL                   | [5dcd7a6c93](https://linux-hardware.org/?probe=5dcd7a6c93) | Sep 12, 2021 |
| ASUSTek       | U56E                        | [99bd7dbfdf](https://linux-hardware.org/?probe=99bd7dbfdf) | Sep 09, 2021 |
| HP            | G60                         | [065e03350f](https://linux-hardware.org/?probe=065e03350f) | Sep 09, 2021 |
| HP            | G60                         | [4d35031cdf](https://linux-hardware.org/?probe=4d35031cdf) | Sep 09, 2021 |
| Acer          | Aspire 4752                 | [f11003a698](https://linux-hardware.org/?probe=f11003a698) | Sep 08, 2021 |
| Acer          | Aspire 4752                 | [cb8ee015c6](https://linux-hardware.org/?probe=cb8ee015c6) | Sep 08, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Gateway       | NV55C                       | [1515d7dfbf](https://linux-hardware.org/?probe=1515d7dfbf) | Sep 06, 2021 |
| Apple         | MacBookPro9,1               | [78f1531e54](https://linux-hardware.org/?probe=78f1531e54) | Sep 05, 2021 |
| Apple         | MacBookPro9,1               | [d306a73462](https://linux-hardware.org/?probe=d306a73462) | Sep 05, 2021 |
| Apple         | MacBookPro12,1              | [b3c5e46b4d](https://linux-hardware.org/?probe=b3c5e46b4d) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [4115bc0195](https://linux-hardware.org/?probe=4115bc0195) | Sep 03, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Sony          | SVE14A15FLB                 | [b49abbf4c8](https://linux-hardware.org/?probe=b49abbf4c8) | Sep 01, 2021 |
| HP            | Laptop 15-bs0xx             | [fc0f8f406b](https://linux-hardware.org/?probe=fc0f8f406b) | Aug 31, 2021 |
| Toshiba       | Satellite A215              | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Toshiba       | Satellite A215              | [3140742cd5](https://linux-hardware.org/?probe=3140742cd5) | Aug 31, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e134361dc2](https://linux-hardware.org/?probe=e134361dc2) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [cf69bd4423](https://linux-hardware.org/?probe=cf69bd4423) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [b409334e94](https://linux-hardware.org/?probe=b409334e94) | Aug 30, 2021 |
| HP            | ProBook 440 G3              | [c4b5fdc75f](https://linux-hardware.org/?probe=c4b5fdc75f) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| HP            | 2000                        | [c1d490dc62](https://linux-hardware.org/?probe=c1d490dc62) | Aug 29, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [d8daca96d1](https://linux-hardware.org/?probe=d8daca96d1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire E5-521               | [5716a5328f](https://linux-hardware.org/?probe=5716a5328f) | Aug 28, 2021 |
| HUAWEI        | WRT-WX9                     | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| Toshiba       | Satellite A215              | [5899e10002](https://linux-hardware.org/?probe=5899e10002) | Aug 25, 2021 |
| Dell          | Inspiron 5577               | [27ba1b6422](https://linux-hardware.org/?probe=27ba1b6422) | Aug 25, 2021 |
| Dell          | Inspiron 5577               | [cfc2b9442c](https://linux-hardware.org/?probe=cfc2b9442c) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | [3d74a16440](https://linux-hardware.org/?probe=3d74a16440) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | [551749a1af](https://linux-hardware.org/?probe=551749a1af) | Aug 25, 2021 |
| HP            | Laptop 14-cm0xxx            | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| HP            | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [01fadd29fd](https://linux-hardware.org/?probe=01fadd29fd) | Aug 23, 2021 |
| ASUSTek       | X455LA                      | [d40617b08b](https://linux-hardware.org/?probe=d40617b08b) | Aug 22, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [0d33aed04c](https://linux-hardware.org/?probe=0d33aed04c) | Aug 19, 2021 |
| Dell          | Inspiron 5559               | [004298137f](https://linux-hardware.org/?probe=004298137f) | Aug 17, 2021 |
| HP            | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [41e2825c3d](https://linux-hardware.org/?probe=41e2825c3d) | Aug 15, 2021 |
| Dell          | XPS 15 9570                 | [3a677218c5](https://linux-hardware.org/?probe=3a677218c5) | Aug 14, 2021 |
| HP            | ProBook 440 G3              | [e93a65b9cf](https://linux-hardware.org/?probe=e93a65b9cf) | Aug 14, 2021 |
| HP            | Notebook                    | [53235618da](https://linux-hardware.org/?probe=53235618da) | Aug 13, 2021 |
| Lenovo        | ThinkPad R61/R61i 7733AY... | [b074276477](https://linux-hardware.org/?probe=b074276477) | Aug 13, 2021 |
| HP            | ProBook 645 G1              | [38105c93e2](https://linux-hardware.org/?probe=38105c93e2) | Aug 13, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [c6acb13b5c](https://linux-hardware.org/?probe=c6acb13b5c) | Aug 12, 2021 |
| Apple         | MacBookPro9,2               | [10a9ce514b](https://linux-hardware.org/?probe=10a9ce514b) | Aug 11, 2021 |
| Apple         | MacBookPro9,2               | [4a08b4bc9c](https://linux-hardware.org/?probe=4a08b4bc9c) | Aug 11, 2021 |
| Samsung       | R530/R730                   | [3c4eb18a66](https://linux-hardware.org/?probe=3c4eb18a66) | Aug 11, 2021 |
| Acer          | Aspire 5742Z                | [dd55e4423e](https://linux-hardware.org/?probe=dd55e4423e) | Aug 11, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 164       | 11.4%   |
| Ubuntu 18.04       | 114       | 7.93%   |
| Ubuntu 22.04       | 65        | 4.52%   |
| OpenMandriva 4.3   | 46        | 3.2%    |
| OpenMandriva 4.2   | 43        | 2.99%   |
| Debian 11          | 43        | 2.99%   |
| Manjaro            | 37        | 2.57%   |
| Zorin 16           | 36        | 2.5%    |
| KDE neon 20.04     | 36        | 2.5%    |
| Fedora 36          | 30        | 2.09%   |
| Linux Mint 20.3    | 26        | 1.81%   |
| Pop!_OS 20.04      | 23        | 1.6%    |
| Arch               | 21        | 1.46%   |
| Pop!_OS 22.04      | 20        | 1.39%   |
| Zorin 15           | 19        | 1.32%   |
| Linux Mint 20      | 19        | 1.32%   |
| Fedora 37          | 19        | 1.32%   |
| Ubuntu 19.10       | 18        | 1.25%   |
| Ubuntu 19.04       | 18        | 1.25%   |
| Debian 10          | 18        | 1.25%   |
| Linux Mint 19.3    | 17        | 1.18%   |
| Ubuntu 21.10       | 16        | 1.11%   |
| Pop!_OS 21.04      | 15        | 1.04%   |
| Kubuntu 20.04      | 15        | 1.04%   |
| Fedora 34          | 15        | 1.04%   |
| Xubuntu 18.04      | 14        | 0.97%   |
| Ubuntu 22.10       | 14        | 0.97%   |
| Ubuntu 20.10       | 14        | 0.97%   |
| Linux Mint 21      | 14        | 0.97%   |
| Fedora 35          | 14        | 0.97%   |
| Linux Mint 20.1    | 13        | 0.9%    |
| Elementary 6.1     | 13        | 0.9%    |
| OpenMandriva 23.01 | 12        | 0.83%   |
| Fedora 32          | 12        | 0.83%   |
| Xubuntu 20.04      | 10        | 0.7%    |
| KDE neon 22.04     | 10        | 0.7%    |
| Arch Rolling       | 10        | 0.7%    |
| Ubuntu 21.04       | 9         | 0.63%   |
| Linux Mint 21.1    | 9         | 0.63%   |
| Pop!_OS 20.10      | 8         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 432       | 31.26%  |
| OpenMandriva  | 111       | 8.03%   |
| Linux Mint    | 108       | 7.81%   |
| Fedora        | 106       | 7.67%   |
| Pop!_OS       | 70        | 5.07%   |
| Debian        | 68        | 4.92%   |
| Manjaro       | 63        | 4.56%   |
| Zorin         | 58        | 4.2%    |
| KDE neon      | 49        | 3.55%   |
| Kubuntu       | 33        | 2.39%   |
| Xubuntu       | 31        | 2.24%   |
| Arch          | 30        | 2.17%   |
| Elementary    | 24        | 1.74%   |
| Kali          | 19        | 1.37%   |
| ROSA          | 16        | 1.16%   |
| openSUSE      | 14        | 1.01%   |
| Endless       | 11        | 0.8%    |
| Clear Linux   | 11        | 0.8%    |
| Lubuntu       | 10        | 0.72%   |
| LMDE          | 9         | 0.65%   |
| Ubuntu Budgie | 8         | 0.58%   |
| Ubuntu Unity  | 7         | 0.51%   |
| Gentoo        | 7         | 0.51%   |
| EndeavourOS   | 7         | 0.51%   |
| ArcoLinux     | 7         | 0.51%   |
| Ubuntu MATE   | 6         | 0.43%   |
| SteamOS       | 6         | 0.43%   |
| Nobara        | 5         | 0.36%   |
| Garuda Linux  | 5         | 0.36%   |
| CentOS        | 5         | 0.36%   |
| Parrot        | 4         | 0.29%   |
| MX            | 4         | 0.29%   |
| Archcraft     | 4         | 0.29%   |
| RHEL          | 3         | 0.22%   |
| Peppermint    | 3         | 0.22%   |
| Reborn OS     | 2         | 0.14%   |
| Loc OS        | 2         | 0.14%   |
| LinuxFX       | 2         | 0.14%   |
| BlackPanther  | 2         | 0.14%   |
| Xero          | 1         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 46        | 2.93%   |
| 5.10.14-desktop-1omv4002 | 43        | 2.74%   |
| 5.4.0-42-generic         | 27        | 1.72%   |
| 5.4.0-58-generic         | 17        | 1.08%   |
| 5.15.0-56-generic        | 16        | 1.02%   |
| 5.4.0-52-generic         | 14        | 0.89%   |
| 5.3.0-46-generic         | 14        | 0.89%   |
| 5.4.0-48-generic         | 12        | 0.76%   |
| 5.19.0-38-generic        | 12        | 0.76%   |
| 5.15.0-48-generic        | 12        | 0.76%   |
| 5.11.0-27-generic        | 12        | 0.76%   |
| 5.0.0-37-generic         | 12        | 0.76%   |
| 6.1.1-desktop-1omv2290   | 11        | 0.7%    |
| 5.4.0-91-generic         | 11        | 0.7%    |
| 5.3.0-40-generic         | 11        | 0.7%    |
| 5.15.0-58-generic        | 11        | 0.7%    |
| 5.15.0-43-generic        | 11        | 0.7%    |
| 5.3.0-42-generic         | 10        | 0.64%   |
| 5.19.0-35-generic        | 10        | 0.64%   |
| 5.13.0-39-generic        | 10        | 0.64%   |
| 5.13.0-28-generic        | 10        | 0.64%   |
| 5.11.0-43-generic        | 10        | 0.64%   |
| 5.4.0-7642-generic       | 9         | 0.57%   |
| 5.4.0-74-generic         | 9         | 0.57%   |
| 5.4.0-65-generic         | 9         | 0.57%   |
| 5.4.0-45-generic         | 9         | 0.57%   |
| 5.3.0-28-generic         | 9         | 0.57%   |
| 5.15.0-52-generic        | 9         | 0.57%   |
| 5.13.0-40-generic        | 9         | 0.57%   |
| 5.11.0-7620-generic      | 9         | 0.57%   |
| 5.11.0-37-generic        | 9         | 0.57%   |
| 5.8.0-43-generic         | 8         | 0.51%   |
| 5.4.0-37-generic         | 8         | 0.51%   |
| 5.15.0-47-generic        | 8         | 0.51%   |
| 4.18.0-25-generic        | 8         | 0.51%   |
| 4.18.0-15-generic        | 8         | 0.51%   |
| 5.4.0-7634-generic       | 7         | 0.45%   |
| 5.4.0-40-generic         | 7         | 0.45%   |
| 5.4.0-33-generic         | 7         | 0.45%   |
| 5.15.0-60-generic        | 7         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 231       | 15.61%  |
| 5.15.0  | 123       | 8.31%   |
| 5.11.0  | 85        | 5.74%   |
| 5.13.0  | 78        | 5.27%   |
| 5.8.0   | 72        | 4.86%   |
| 5.3.0   | 72        | 4.86%   |
| 4.15.0  | 65        | 4.39%   |
| 5.0.0   | 54        | 3.65%   |
| 5.10.0  | 49        | 3.31%   |
| 5.16.7  | 47        | 3.18%   |
| 4.18.0  | 47        | 3.18%   |
| 5.19.0  | 44        | 2.97%   |
| 5.10.14 | 43        | 2.91%   |
| 4.19.0  | 28        | 1.89%   |
| 6.1.1   | 17        | 1.15%   |
| 5.17.5  | 8         | 0.54%   |
| 6.2.6   | 7         | 0.47%   |
| 6.0.12  | 7         | 0.47%   |
| 5.14.0  | 6         | 0.41%   |
| 6.1.0   | 5         | 0.34%   |
| 6.0.11  | 5         | 0.34%   |
| 5.9.1   | 5         | 0.34%   |
| 5.15.8  | 5         | 0.34%   |
| 6.2.0   | 4         | 0.27%   |
| 6.1.9   | 4         | 0.27%   |
| 6.0.0   | 4         | 0.27%   |
| 5.3.18  | 4         | 0.27%   |
| 5.19.8  | 4         | 0.27%   |
| 5.17.0  | 4         | 0.27%   |
| 5.16.0  | 4         | 0.27%   |
| 5.15.13 | 4         | 0.27%   |
| 4.9.20  | 4         | 0.27%   |
| 4.4.0   | 4         | 0.27%   |
| 6.2.2   | 3         | 0.2%    |
| 5.9.14  | 3         | 0.2%    |
| 5.7.15  | 3         | 0.2%    |
| 5.19.12 | 3         | 0.2%    |
| 5.19.11 | 3         | 0.2%    |
| 5.18.9  | 3         | 0.2%    |
| 5.18.6  | 3         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 248       | 17%     |
| 5.15    | 172       | 11.79%  |
| 5.10    | 120       | 8.22%   |
| 5.11    | 94        | 6.44%   |
| 5.13    | 90        | 6.17%   |
| 5.3     | 83        | 5.69%   |
| 5.8     | 79        | 5.41%   |
| 5.19    | 69        | 4.73%   |
| 5.16    | 69        | 4.73%   |
| 4.15    | 65        | 4.46%   |
| 5.0     | 54        | 3.7%    |
| 4.18    | 48        | 3.29%   |
| 6.1     | 37        | 2.54%   |
| 4.19    | 30        | 2.06%   |
| 6.0     | 29        | 1.99%   |
| 5.17    | 26        | 1.78%   |
| 6.2     | 22        | 1.51%   |
| 5.18    | 22        | 1.51%   |
| 5.14    | 19        | 1.3%    |
| 5.9     | 16        | 1.1%    |
| 5.6     | 12        | 0.82%   |
| 4.9     | 12        | 0.82%   |
| 5.12    | 11        | 0.75%   |
| 5.7     | 10        | 0.69%   |
| 5.5     | 7         | 0.48%   |
| 4.4     | 4         | 0.27%   |
| 4.13    | 3         | 0.21%   |
| 5.2     | 2         | 0.14%   |
| 4.12    | 2         | 0.14%   |
| 5.1     | 1         | 0.07%   |
| 4.10    | 1         | 0.07%   |
| 3.2     | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1283      | 96.39%  |
| i686   | 48        | 3.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 630       | 45.42%  |
| KDE5              | 240       | 17.3%   |
| Unknown           | 142       | 10.24%  |
| XFCE              | 100       | 7.21%   |
| X-Cinnamon        | 81        | 5.84%   |
| KDE               | 52        | 3.75%   |
| MATE              | 38        | 2.74%   |
| Pantheon          | 24        | 1.73%   |
| Cinnamon          | 15        | 1.08%   |
| LXQt              | 13        | 0.94%   |
| Budgie            | 10        | 0.72%   |
| Unity             | 7         | 0.5%    |
| LXDE              | 7         | 0.5%    |
| KDE4              | 5         | 0.36%   |
| openbox           | 4         | 0.29%   |
| Deepin            | 4         | 0.29%   |
| i3                | 3         | 0.22%   |
| trinity           | 2         | 0.14%   |
| GNOME Classic     | 2         | 0.14%   |
| Enlightenment     | 2         | 0.14%   |
| Yaru:ubuntu:GNOME | 1         | 0.07%   |
| xmonad            | 1         | 0.07%   |
| qtile             | 1         | 0.07%   |
| lightdm-xsession  | 1         | 0.07%   |
| GNOME Flashback   | 1         | 0.07%   |
| bspwm             | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1056      | 77.14%  |
| Wayland | 222       | 16.22%  |
| Unknown | 84        | 6.14%   |
| Tty     | 7         | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 711       | 51.48%  |
| SDDM    | 204       | 14.77%  |
| GDM     | 173       | 12.53%  |
| GDM3    | 126       | 9.12%   |
| LightDM | 118       | 8.54%   |
| TDM     | 34        | 2.46%   |
| KDM     | 5         | 0.36%   |
| XDM     | 4         | 0.29%   |
| SLiM    | 3         | 0.22%   |
| MDM     | 1         | 0.07%   |
| Ly      | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_MX      | 659       | 48.56%  |
| en_US      | 418       | 30.8%   |
| Unknown    | 132       | 9.73%   |
| es_ES      | 87        | 6.41%   |
| C          | 26        | 1.92%   |
| en_GB      | 10        | 0.74%   |
| es_US      | 5         | 0.37%   |
| en_CA      | 3         | 0.22%   |
| fr_FR      | 2         | 0.15%   |
| es_MX.UTF8 | 2         | 0.15%   |
| es_AR      | 2         | 0.15%   |
| en_MX      | 2         | 0.15%   |
| C.UTF8     | 2         | 0.15%   |
| uk_UA      | 1         | 0.07%   |
| pt_BR      | 1         | 0.07%   |
| POSIX      | 1         | 0.07%   |
| it_IT      | 1         | 0.07%   |
| es_CR      | 1         | 0.07%   |
| es_419     | 1         | 0.07%   |
| en_IE      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 691       | 50.7%   |
| BIOS | 672       | 49.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1046      | 77.14%  |
| Overlay | 125       | 9.22%   |
| Btrfs   | 107       | 7.89%   |
| Unknown | 36        | 2.65%   |
| Xfs     | 21        | 1.55%   |
| Zfs     | 9         | 0.66%   |
| Ext2    | 4         | 0.29%   |
| Tmpfs   | 3         | 0.22%   |
| XXXXXXX | 2         | 0.15%   |
| Ext3    | 2         | 0.15%   |
| Aufs    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 779       | 57.2%   |
| GPT     | 437       | 32.09%  |
| MBR     | 146       | 10.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1204      | 89.25%  |
| Yes       | 145       | 10.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 927       | 68.46%  |
| Yes       | 427       | 31.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 325       | 24.44%  |
| Lenovo              | 253       | 19.02%  |
| Dell                | 199       | 14.96%  |
| Acer                | 106       | 7.97%   |
| ASUSTek Computer    | 94        | 7.07%   |
| Toshiba             | 66        | 4.96%   |
| HUAWEI              | 51        | 3.83%   |
| Apple               | 48        | 3.61%   |
| Sony                | 40        | 3.01%   |
| Samsung Electronics | 19        | 1.43%   |
| MSI                 | 18        | 1.35%   |
| Gateway             | 17        | 1.28%   |
| Google              | 13        | 0.98%   |
| Alienware           | 10        | 0.75%   |
| Unknown             | 7         | 0.53%   |
| Lanix               | 6         | 0.45%   |
| Chuwi               | 6         | 0.45%   |
| Valve               | 5         | 0.38%   |
| EVOO                | 4         | 0.3%    |
| A-DATA Technology   | 4         | 0.3%    |
| Timi                | 3         | 0.23%   |
| System76            | 3         | 0.23%   |
| Notebook            | 3         | 0.23%   |
| HONOR               | 3         | 0.23%   |
| GPU Company         | 3         | 0.23%   |
| Panasonic           | 2         | 0.15%   |
| Insyde              | 2         | 0.15%   |
| GHIA                | 2         | 0.15%   |
| eMachines           | 2         | 0.15%   |
| Corporativo Lanix   | 2         | 0.15%   |
| American Megatrends | 2         | 0.15%   |
| TECH PAD            | 1         | 0.08%   |
| SK hynix            | 1         | 0.08%   |
| Schenker            | 1         | 0.08%   |
| Razer               | 1         | 0.08%   |
| LG Electronics      | 1         | 0.08%   |
| Hyundai Technology  | 1         | 0.08%   |
| Hannspree           | 1         | 0.08%   |
| Eluktronics         | 1         | 0.08%   |
| DERE                | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 27        | 2.03%   |
| Unknown                       | 21        | 1.58%   |
| HP Pavilion Laptop 15-cw0xxx  | 16        | 1.2%    |
| HUAWEI HVY-WXX9               | 13        | 0.98%   |
| HP Pavilion g4                | 13        | 0.98%   |
| HP Pavilion Notebook          | 12        | 0.9%    |
| HP Pavilion Laptop 15-cw1xxx  | 9         | 0.68%   |
| HP Laptop 15-da0xxx           | 9         | 0.68%   |
| Apple MacBookPro9,2           | 9         | 0.68%   |
| Lenovo IdeaPad 330-14AST 81D5 | 8         | 0.6%    |
| HP Laptop 15-bw0xx            | 8         | 0.6%    |
| HP EliteBook 8460p            | 8         | 0.6%    |
| Dell Latitude E6430           | 8         | 0.6%    |
| HP Pavilion dv4               | 7         | 0.53%   |
| Apple MacBookPro8,1           | 7         | 0.53%   |
| HP Pavilion dv5               | 6         | 0.45%   |
| Dell Inspiron 5559            | 6         | 0.45%   |
| Dell Inspiron 3421            | 6         | 0.45%   |
| Valve Jupiter                 | 5         | 0.38%   |
| Lenovo Y50-70 20378           | 5         | 0.38%   |
| HUAWEI NBLB-WAX9N             | 5         | 0.38%   |
| HP Pavilion 14                | 5         | 0.38%   |
| HP Laptop 15-da2xxx           | 5         | 0.38%   |
| HP Laptop 14-cm0xxx           | 5         | 0.38%   |
| Acer Aspire E5-573            | 5         | 0.38%   |
| Acer Aspire E3-112M           | 5         | 0.38%   |
| Toshiba Satellite L855        | 4         | 0.3%    |
| Toshiba Satellite L55-B       | 4         | 0.3%    |
| Lenovo Y720-15IKB 80VR        | 4         | 0.3%    |
| Lenovo IdeaPad 330-15AST 81D6 | 4         | 0.3%    |
| Lenovo IdeaPad 3 15ALC6 82KU  | 4         | 0.3%    |
| Lenovo G50-30 80G0            | 4         | 0.3%    |
| Lenovo G40-45 80E1            | 4         | 0.3%    |
| HUAWEI BOHK-WAX9X             | 4         | 0.3%    |
| HP Pavilion 15                | 4         | 0.3%    |
| HP Laptop 15-bs0xx            | 4         | 0.3%    |
| HP G42                        | 4         | 0.3%    |
| HP 245 G7 Notebook PC         | 4         | 0.3%    |
| HP 14                         | 4         | 0.3%    |
| Dell Studio 1558              | 4         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| HP Pavilion       | 103       | 7.74%   |
| Lenovo ThinkPad   | 97        | 7.29%   |
| Lenovo IdeaPad    | 93        | 6.99%   |
| Acer Aspire       | 75        | 5.64%   |
| Dell Latitude     | 74        | 5.56%   |
| Dell Inspiron     | 74        | 5.56%   |
| Toshiba Satellite | 61        | 4.59%   |
| HP Laptop         | 57        | 4.29%   |
| HP Notebook       | 27        | 2.03%   |
| HP EliteBook      | 25        | 1.88%   |
| HP ProBook        | 24        | 1.8%    |
| Unknown           | 21        | 1.58%   |
| ASUS VivoBook     | 20        | 1.5%    |
| HUAWEI HVY-WXX9   | 13        | 0.98%   |
| HP Compaq         | 12        | 0.9%    |
| HP 240            | 11        | 0.83%   |
| Dell Vostro       | 10        | 0.75%   |
| Apple MacBookPro9 | 10        | 0.75%   |
| HP ENVY           | 9         | 0.68%   |
| Dell XPS          | 9         | 0.68%   |
| Dell Studio       | 9         | 0.68%   |
| Apple MacBookPro8 | 8         | 0.6%    |
| Lenovo Legion     | 7         | 0.53%   |
| HP OMEN           | 7         | 0.53%   |
| HP ZBook          | 6         | 0.45%   |
| Dell Precision    | 6         | 0.45%   |
| ASUS ASUS         | 6         | 0.45%   |
| Acer Nitro        | 6         | 0.45%   |
| Valve Jupiter     | 5         | 0.38%   |
| MSI GF63          | 5         | 0.38%   |
| Lenovo Y50-70     | 5         | 0.38%   |
| HUAWEI NBLB-WAX9N | 5         | 0.38%   |
| HP 245            | 5         | 0.38%   |
| Dell G3           | 5         | 0.38%   |
| Dell G15          | 5         | 0.38%   |
| Lenovo Yoga       | 4         | 0.3%    |
| Lenovo Y720-15IKB | 4         | 0.3%    |
| Lenovo G50-30     | 4         | 0.3%    |
| Lenovo G40-45     | 4         | 0.3%    |
| HUAWEI BOHK-WAX9X | 4         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 121       | 9.1%    |
| 2011    | 116       | 8.72%   |
| 2019    | 115       | 8.65%   |
| 2020    | 105       | 7.89%   |
| 2012    | 103       | 7.74%   |
| 2015    | 97        | 7.29%   |
| 2017    | 94        | 7.07%   |
| 2013    | 93        | 6.99%   |
| 2014    | 91        | 6.84%   |
| 2021    | 80        | 6.02%   |
| 2010    | 78        | 5.86%   |
| 2008    | 72        | 5.41%   |
| 2016    | 70        | 5.26%   |
| 2009    | 33        | 2.48%   |
| 2007    | 23        | 1.73%   |
| 2022    | 22        | 1.65%   |
| 2006    | 8         | 0.6%    |
| 2005    | 4         | 0.3%    |
| Unknown | 3         | 0.23%   |
| 2004    | 2         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1330      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1180      | 87.67%  |
| Enabled  | 166       | 12.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1316      | 98.95%  |
| Yes  | 14        | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 398       | 29.59%  |
| 3.01-4.0    | 325       | 24.16%  |
| 8.01-16.0   | 254       | 18.88%  |
| 16.01-24.0  | 165       | 12.27%  |
| 1.01-2.0    | 93        | 6.91%   |
| 32.01-64.0  | 42        | 3.12%   |
| 2.01-3.0    | 29        | 2.16%   |
| 0.51-1.0    | 17        | 1.26%   |
| 24.01-32.0  | 15        | 1.12%   |
| 64.01-256.0 | 7         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 542       | 37.1%   |
| 2.01-3.0   | 413       | 28.27%  |
| 3.01-4.0   | 185       | 12.66%  |
| 4.01-8.0   | 157       | 10.75%  |
| 0.51-1.0   | 101       | 6.91%   |
| 8.01-16.0  | 43        | 2.94%   |
| 0.01-0.5   | 13        | 0.89%   |
| 16.01-24.0 | 5         | 0.34%   |
| 32.01-64.0 | 1         | 0.07%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1021      | 75.24%  |
| 2      | 287       | 21.15%  |
| 3      | 24        | 1.77%   |
| 0      | 18        | 1.33%   |
| 4      | 5         | 0.37%   |
| 6      | 1         | 0.07%   |
| 5      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 845       | 63.2%   |
| Yes       | 492       | 36.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1098      | 82.56%  |
| No        | 232       | 17.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1308      | 98.27%  |
| No        | 23        | 1.73%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 991       | 73.41%  |
| No        | 359       | 26.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Mexico  | 1330      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 299       | 21.22%  |
| Guadalajara           | 68        | 4.83%   |
| Monterrey             | 44        | 3.12%   |
| Tijuana               | 37        | 2.63%   |
| Puebla City           | 37        | 2.63%   |
| Zapopan               | 36        | 2.56%   |
| Queretaro             | 33        | 2.34%   |
| Mérida               | 24        | 1.7%    |
| Cancún               | 24        | 1.7%    |
| Toluca                | 22        | 1.56%   |
| Xalapa                | 17        | 1.21%   |
| Hermosillo            | 17        | 1.21%   |
| Ciudad Lopez Mateos   | 17        | 1.21%   |
| León                 | 15        | 1.06%   |
| Ciudad Juárez        | 15        | 1.06%   |
| Naucalpan             | 14        | 0.99%   |
| Mexicali              | 14        | 0.99%   |
| Ecatepec              | 14        | 0.99%   |
| Veracruz              | 13        | 0.92%   |
| Morelia               | 13        | 0.92%   |
| Cuernavaca            | 13        | 0.92%   |
| Celaya                | 13        | 0.92%   |
| Apodaca               | 13        | 0.92%   |
| Tlalnepantla          | 12        | 0.85%   |
| México               | 12        | 0.85%   |
| Culiacán             | 12        | 0.85%   |
| Ciudad Nezahualcoyotl | 12        | 0.85%   |
| Villahermosa          | 11        | 0.78%   |
| San Luis Potosí City | 11        | 0.78%   |
| Guadalupe             | 11        | 0.78%   |
| Durango               | 11        | 0.78%   |
| Chihuahua City        | 11        | 0.78%   |
| Zacatecas City        | 10        | 0.71%   |
| Ensenada              | 10        | 0.71%   |
| Azcapotzalco          | 10        | 0.71%   |
| Pachuca               | 9         | 0.64%   |
| Oaxaca City           | 9         | 0.64%   |
| Iztapalapa            | 9         | 0.64%   |
| Cuautitlán Izcalli   | 9         | 0.64%   |
| Saltillo              | 8         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 241       | 302    | 14.79%  |
| WDC                         | 216       | 271    | 13.26%  |
| Toshiba                     | 173       | 210    | 10.62%  |
| Kingston                    | 155       | 191    | 9.52%   |
| Samsung Electronics         | 122       | 154    | 7.49%   |
| A-DATA Technology           | 107       | 126    | 6.57%   |
| Unknown                     | 92        | 105    | 5.65%   |
| Hitachi                     | 73        | 81     | 4.48%   |
| HGST                        | 69        | 73     | 4.24%   |
| Sandisk                     | 62        | 81     | 3.81%   |
| SK hynix                    | 36        | 45     | 2.21%   |
| Intel                       | 29        | 42     | 1.78%   |
| Apple                       | 24        | 32     | 1.47%   |
| Crucial                     | 19        | 21     | 1.17%   |
| Micron Technology           | 17        | 18     | 1.04%   |
| XPG                         | 14        | 22     | 0.86%   |
| Fujitsu                     | 13        | 14     | 0.8%    |
| LITEON                      | 10        | 15     | 0.61%   |
| KIOXIA                      | 10        | 12     | 0.61%   |
| Phison                      | 9         | 9      | 0.55%   |
| YMTC                        | 8         | 9      | 0.49%   |
| Realtek Semiconductor       | 8         | 9      | 0.49%   |
| China                       | 7         | 7      | 0.43%   |
| Unknown                     | 7         | 7      | 0.43%   |
| Silicon Motion              | 6         | 6      | 0.37%   |
| Phison Electronics          | 6         | 6      | 0.37%   |
| Netac                       | 6         | 6      | 0.37%   |
| ADATA Technology            | 6         | 6      | 0.37%   |
| PNY                         | 5         | 7      | 0.31%   |
| JMicron Technology          | 5         | 5      | 0.31%   |
| Patriot                     | 4         | 7      | 0.25%   |
| LITEONIT                    | 4         | 4      | 0.25%   |
| Kingston Technology Company | 4         | 4      | 0.25%   |
| Union Memory (Shenzhen)     | 3         | 3      | 0.18%   |
| SABRENT                     | 3         | 3      | 0.18%   |
| Pioneer                     | 3         | 4      | 0.18%   |
| Hewlett-Packard             | 3         | 3      | 0.18%   |
| AS201                       | 3         | 3      | 0.18%   |
| SSSTC                       | 2         | 2      | 0.12%   |
| ShiJi                       | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                  | 57        | 3.39%   |
| Kingston SA400S37240G 240GB SSD                   | 37        | 2.2%    |
| Toshiba MQ04ABF100 1TB                            | 36        | 2.14%   |
| Toshiba MQ01ABD100 1TB                            | 34        | 2.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 34        | 2.03%   |
| Kingston SA400S37480G 480GB SSD                   | 33        | 1.97%   |
| Toshiba MQ01ABF050 500GB                          | 22        | 1.31%   |
| Unknown MMC Card  32GB                            | 21        | 1.25%   |
| Seagate ST500LT012-1DG142 500GB                   | 21        | 1.25%   |
| A-DATA SU650 120GB SSD                            | 19        | 1.13%   |
| A-DATA SU630 240GB SSD                            | 15        | 0.89%   |
| HGST HTS725050A7E630 500GB                        | 13        | 0.77%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 12        | 0.71%   |
| HGST HTS541010A9E680 1TB                          | 12        | 0.71%   |
| Unknown MMC Card  64GB                            | 11        | 0.66%   |
| Samsung NVMe SSD Drive 512GB                      | 11        | 0.66%   |
| Kingston SA400S37960G 960GB SSD                   | 11        | 0.66%   |
| Seagate ST9500325AS 500GB                         | 10        | 0.6%    |
| HGST HTS721010A9E630 1TB                          | 10        | 0.6%    |
| A-DATA SU650 240GB SSD                            | 10        | 0.6%    |
| WDC WD5000LPCX-24VHAT0 500GB                      | 9         | 0.54%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 9         | 0.54%   |
| Unknown MMC Card  16GB                            | 9         | 0.54%   |
| Seagate ST500LM021-1KJ152 500GB                   | 9         | 0.54%   |
| Seagate ST2000LM007-1R8174 2TB                    | 9         | 0.54%   |
| Seagate Expansion 4TB                             | 9         | 0.54%   |
| Kingston SA400S37120G 120GB SSD                   | 9         | 0.54%   |
| HGST HTS545050A7E680 500GB                        | 9         | 0.54%   |
| HGST HTS541075A9E680 752GB                        | 9         | 0.54%   |
| WDC WD10SPZX-08Z10 1TB                            | 8         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 8         | 0.48%   |
| A-DATA SU630 480GB SSD                            | 8         | 0.48%   |
| YMTC PC005 512GB                                  | 7         | 0.42%   |
| Seagate ST1000LM048-2E7172 1TB                    | 7         | 0.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 7         | 0.42%   |
| Kingston SUV400S37480G 480GB SSD                  | 7         | 0.42%   |
| Hitachi HTS547550A9E384 500GB                     | 7         | 0.42%   |
| Unknown                                           | 7         | 0.42%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 6         | 0.36%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 6         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 240       | 299    | 31.58%  |
| WDC                 | 179       | 220    | 23.55%  |
| Toshiba             | 154       | 187    | 20.26%  |
| Hitachi             | 73        | 81     | 9.61%   |
| HGST                | 69        | 73     | 9.08%   |
| Samsung Electronics | 13        | 14     | 1.71%   |
| Fujitsu             | 13        | 14     | 1.71%   |
| Unknown             | 5         | 5      | 0.66%   |
| Apple               | 4         | 5      | 0.53%   |
| Pioneer             | 2         | 3      | 0.26%   |
| JMicron Technology  | 2         | 2      | 0.26%   |
| Hewlett-Packard     | 2         | 2      | 0.26%   |
| SAGE                | 1         | 1      | 0.13%   |
| LaCie               | 1         | 2      | 0.13%   |
| IBM/Hitachi         | 1         | 1      | 0.13%   |
| ASMedia             | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 139       | 172    | 31.24%  |
| A-DATA Technology   | 101       | 120    | 22.7%   |
| Samsung Electronics | 39        | 43     | 8.76%   |
| SanDisk             | 27        | 32     | 6.07%   |
| WDC                 | 16        | 23     | 3.6%    |
| Crucial             | 16        | 16     | 3.6%    |
| Apple               | 15        | 17     | 3.37%   |
| SK hynix            | 9         | 10     | 2.02%   |
| LITEON              | 9         | 14     | 2.02%   |
| Micron Technology   | 7         | 8      | 1.57%   |
| China               | 7         | 7      | 1.57%   |
| Netac               | 6         | 6      | 1.35%   |
| Intel               | 6         | 7      | 1.35%   |
| PNY                 | 5         | 7      | 1.12%   |
| LITEONIT            | 4         | 4      | 0.9%    |
| Toshiba             | 3         | 3      | 0.67%   |
| Patriot             | 3         | 6      | 0.67%   |
| AS201               | 3         | 3      | 0.67%   |
| Unknown             | 3         | 3      | 0.67%   |
| Unknown             | 2         | 2      | 0.45%   |
| OCZ                 | 2         | 4      | 0.45%   |
| Gigabyte Technology | 2         | 2      | 0.45%   |
| Blackpcs            | 2         | 2      | 0.45%   |
| BHT                 | 2         | 2      | 0.45%   |
| ZTC                 | 1         | 1      | 0.22%   |
| Zheino              | 1         | 1      | 0.22%   |
| Yeyian              | 1         | 3      | 0.22%   |
| Wibtek              | 1         | 1      | 0.22%   |
| Transcend           | 1         | 1      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| StoreJet            | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 1      | 0.22%   |
| SPCC                | 1         | 1      | 0.22%   |
| ShanDianZhe         | 1         | 2      | 0.22%   |
| Pioneer             | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 4      | 0.22%   |
| Hikvision           | 1         | 1      | 0.22%   |
| Hewlett-Packard     | 1         | 1      | 0.22%   |
| Dogfish             | 1         | 4      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 743       | 910    | 47.32%  |
| SSD     | 417       | 539    | 26.56%  |
| NVMe    | 301       | 412    | 19.17%  |
| MMC     | 89        | 103    | 5.67%   |
| Unknown | 20        | 24     | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1057      | 1409   | 70.42%  |
| NVMe | 299       | 410    | 19.92%  |
| MMC  | 89        | 103    | 5.93%   |
| SAS  | 56        | 66     | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 728       | 915    | 63.08%  |
| 0.51-1.0   | 384       | 475    | 33.28%  |
| 1.01-2.0   | 30        | 46     | 2.6%    |
| 3.01-4.0   | 10        | 11     | 0.87%   |
| 10.01-20.0 | 1         | 1      | 0.09%   |
| 4.01-10.0  | 1         | 1      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 377       | 27.12%  |
| 251-500        | 343       | 24.68%  |
| 501-1000       | 230       | 16.55%  |
| 1-20           | 125       | 8.99%   |
| 51-100         | 113       | 8.13%   |
| 1001-2000      | 76        | 5.47%   |
| 21-50          | 74        | 5.32%   |
| More than 3000 | 19        | 1.37%   |
| 2001-3000      | 17        | 1.22%   |
| Unknown        | 16        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 636       | 44.01%  |
| 21-50          | 281       | 19.45%  |
| 101-250        | 179       | 12.39%  |
| 51-100         | 155       | 10.73%  |
| 251-500        | 92        | 6.37%   |
| 501-1000       | 57        | 3.94%   |
| 1001-2000      | 21        | 1.45%   |
| Unknown        | 16        | 1.11%   |
| More than 3000 | 5         | 0.35%   |
| 2001-3000      | 3         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 6         | 7      | 4.8%    |
| Seagate ST500LT012-1DG142 500GB     | 5         | 5      | 4%      |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 3.2%    |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 3.2%    |
| HGST HTS541075A9E680 752GB          | 4         | 4      | 3.2%    |
| Toshiba MQ04ABF100 1TB              | 3         | 3      | 2.4%    |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 2.4%    |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 2      | 1.6%    |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 2      | 1.6%    |
| Seagate ST9500420AS 500GB           | 2         | 2      | 1.6%    |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 2      | 1.6%    |
| Seagate ST1000LM035-1RK172 970GB    | 2         | 2      | 1.6%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 1.6%    |
| LITEON CV8-8E128-HP 128GB SSD       | 2         | 2      | 1.6%    |
| Hitachi HTS545016B9A300 160GB       | 2         | 2      | 1.6%    |
| Hitachi HTS543232A7A384 320GB       | 2         | 2      | 1.6%    |
| HGST HTS541010A7E630 1TB            | 2         | 2      | 1.6%    |
| China SSD 256GB                     | 2         | 2      | 1.6%    |
| A-DATA Technology SU650 240GB SSD   | 2         | 2      | 1.6%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.8%    |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 2      | 0.8%    |
| WDC WD50 00BEVT-11ZAT0 500GB        | 1         | 1      | 0.8%    |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 0.8%    |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 1      | 0.8%    |
| WDC WD2500LPVX-22V0TT0 250GB        | 1         | 1      | 0.8%    |
| WDC WD2500BEVT-80A23T0 250GB        | 1         | 2      | 0.8%    |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1      | 0.8%    |
| WDC WD10SPCX-60KHST0 1TB            | 1         | 1      | 0.8%    |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1      | 0.8%    |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 0.8%    |
| WDC WD10JPVX-55JC3T3 1TB            | 1         | 1      | 0.8%    |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 0.8%    |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 0.8%    |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 0.8%    |
| Toshiba MK7559GSXP 752GB            | 1         | 7      | 0.8%    |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 0.8%    |
| Toshiba MK3276GSX H 320GB           | 1         | 1      | 0.8%    |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 0.8%    |
| Toshiba MK2561GSY 250GB             | 1         | 1      | 0.8%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 20%     |
| Toshiba             | 24        | 31     | 19.2%   |
| Hitachi             | 20        | 21     | 16%     |
| WDC                 | 17        | 19     | 13.6%   |
| HGST                | 14        | 14     | 11.2%   |
| Kingston            | 8         | 8      | 6.4%    |
| SanDisk             | 4         | 4      | 3.2%    |
| Fujitsu             | 3         | 3      | 2.4%    |
| Samsung Electronics | 2         | 2      | 1.6%    |
| LITEON              | 2         | 2      | 1.6%    |
| China               | 2         | 2      | 1.6%    |
| A-DATA Technology   | 2         | 2      | 1.6%    |
| Micron Technology   | 1         | 1      | 0.8%    |
| Crucial             | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 24.04%  |
| Toshiba             | 24        | 31     | 23.08%  |
| Hitachi             | 20        | 21     | 19.23%  |
| WDC                 | 17        | 19     | 16.35%  |
| HGST                | 14        | 14     | 13.46%  |
| Fujitsu             | 3         | 3      | 2.88%   |
| Samsung Electronics | 1         | 1      | 0.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 104       | 117    | 83.2%   |
| SSD  | 18        | 18     | 14.4%   |
| NVMe | 3         | 3      | 2.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-75A23T0 160GB  | 1         | 1      | 50%     |
| Hitachi HTS545016B9A300 160GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 855       | 1273   | 61.25%  |
| Works    | 416       | 575    | 29.8%   |
| Malfunc  | 123       | 138    | 8.81%   |
| Failed   | 2         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 892       | 60.31%  |
| AMD                              | 265       | 17.92%  |
| Samsung Electronics              | 76        | 5.14%   |
| SanDisk                          | 54        | 3.65%   |
| SK hynix                         | 27        | 1.83%   |
| Kingston Technology Company      | 20        | 1.35%   |
| Nvidia                           | 18        | 1.22%   |
| ADATA Technology                 | 18        | 1.22%   |
| Toshiba America Info Systems     | 17        | 1.15%   |
| Phison Electronics               | 15        | 1.01%   |
| Realtek Semiconductor            | 13        | 0.88%   |
| KIOXIA                           | 11        | 0.74%   |
| Micron Technology                | 10        | 0.68%   |
| Yangtze Memory Technologies      | 8         | 0.54%   |
| Union Memory (Shenzhen)          | 6         | 0.41%   |
| Silicon Motion                   | 6         | 0.41%   |
| Micron/Crucial Technology        | 5         | 0.34%   |
| Marvell Technology Group         | 5         | 0.34%   |
| Apple                            | 5         | 0.34%   |
| Lite-On Technology               | 2         | 0.14%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| Biwin Storage Technology         | 1         | 0.07%   |
| Unknown                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 214       | 13.48%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 104       | 6.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 102       | 6.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 75        | 4.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 74        | 4.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 46        | 2.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 44        | 2.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 37        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 37        | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 36        | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 35        | 2.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 31        | 1.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 29        | 1.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 28        | 1.76%   |
| Samsung NVMe SSD Controller 980                                                  | 27        | 1.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 27        | 1.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 26        | 1.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 23        | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 21        | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 20        | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 19        | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 19        | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                            | 17        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 15        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 14        | 0.88%   |
| Phison PS5013 E13 NVMe Controller                                                | 13        | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 13        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 13        | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 12        | 0.76%   |
| SanDisk Non-Volatile memory controller                                           | 12        | 0.76%   |
| Realtek NVMe Controller                                                          | 12        | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 0.69%   |
| Micron NVMe Storage Controller                                                   | 10        | 0.63%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 10        | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 10        | 0.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 9         | 0.57%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 9         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1008      | 65.33%  |
| NVMe | 301       | 19.51%  |
| RAID | 127       | 8.23%   |
| IDE  | 107       | 6.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1001      | 75.26%  |
| AMD    | 329       | 24.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 22        | 1.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 19        | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 1.35%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 18        | 1.35%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 18        | 1.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 15        | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.05%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 14        | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 13        | 0.98%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 13        | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.98%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 13        | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.83%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 0.83%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 11        | 0.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 0.83%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 11        | 0.83%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 10        | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.75%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 10        | 0.75%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 10        | 0.75%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 10        | 0.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 10        | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.68%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 9         | 0.68%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 9         | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 0.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.68%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 9         | 0.68%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 8         | 0.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 270       | 20.3%   |
| Intel Core i7                  | 245       | 18.42%  |
| Intel Celeron                  | 147       | 11.05%  |
| Intel Core i3                  | 120       | 9.02%   |
| Other                          | 68        | 5.11%   |
| AMD Ryzen 5                    | 66        | 4.96%   |
| Intel Core 2 Duo               | 57        | 4.29%   |
| Intel Atom                     | 42        | 3.16%   |
| AMD Ryzen 7                    | 30        | 2.26%   |
| AMD A6                         | 28        | 2.11%   |
| AMD A8                         | 26        | 1.95%   |
| Intel Pentium                  | 23        | 1.73%   |
| AMD E                          | 20        | 1.5%    |
| AMD A4                         | 20        | 1.5%    |
| AMD Ryzen 3                    | 19        | 1.43%   |
| AMD A10                        | 19        | 1.43%   |
| Intel Pentium Dual             | 13        | 0.98%   |
| AMD Turion 64 X2 Mobile        | 10        | 0.75%   |
| Intel Pentium Dual-Core        | 9         | 0.68%   |
| AMD Athlon II                  | 9         | 0.68%   |
| Intel Genuine                  | 8         | 0.6%    |
| Intel Core 2                   | 6         | 0.45%   |
| AMD Ryzen 5 PRO                | 6         | 0.45%   |
| AMD E1                         | 6         | 0.45%   |
| AMD Ryzen 9                    | 5         | 0.38%   |
| AMD FX                         | 5         | 0.38%   |
| AMD A12                        | 5         | 0.38%   |
| AMD E2                         | 4         | 0.3%    |
| AMD Athlon 64 X2               | 4         | 0.3%    |
| AMD Athlon                     | 4         | 0.3%    |
| Intel Celeron M                | 3         | 0.23%   |
| AMD Sempron                    | 3         | 0.23%   |
| Intel Pentium Silver           | 2         | 0.15%   |
| Intel Pentium M                | 2         | 0.15%   |
| Intel Core Duo                 | 2         | 0.15%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.15%   |
| AMD C-60                       | 2         | 0.15%   |
| AMD Athlon X2                  | 2         | 0.15%   |
| AMD Athlon II Neo              | 2         | 0.15%   |
| Intel Xeon                     | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 793       | 59.62%  |
| 4      | 364       | 27.37%  |
| 6      | 82        | 6.17%   |
| 1      | 58        | 4.36%   |
| 8      | 27        | 2.03%   |
| 10     | 3         | 0.23%   |
| 14     | 2         | 0.15%   |
| 3      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1330      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 864       | 64.96%  |
| 1      | 466       | 35.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1293      | 97.22%  |
| 32-bit         | 18        | 1.35%   |
| Unknown        | 14        | 1.05%   |
| 64-bit         | 5         | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 292       | 21.17%  |
| 0x206a7    | 86        | 6.24%   |
| 0x306a9    | 72        | 5.22%   |
| 0x40651    | 51        | 3.7%    |
| 0x806ec    | 43        | 3.12%   |
| 0x306d4    | 37        | 2.68%   |
| 0x30678    | 36        | 2.61%   |
| 0x806e9    | 34        | 2.47%   |
| 0x1067a    | 33        | 2.39%   |
| 0x906ea    | 30        | 2.18%   |
| 0x806ea    | 29        | 2.1%    |
| 0x806c1    | 29        | 2.1%    |
| 0x406e3    | 27        | 1.96%   |
| 0x06006705 | 27        | 1.96%   |
| 0x20655    | 25        | 1.81%   |
| 0x08108109 | 23        | 1.67%   |
| 0x406c3    | 22        | 1.6%    |
| 0x6fd      | 21        | 1.52%   |
| 0x406c4    | 21        | 1.52%   |
| 0x306c3    | 20        | 1.45%   |
| 0x106ca    | 20        | 1.45%   |
| 0x08600106 | 20        | 1.45%   |
| 0x506e3    | 19        | 1.38%   |
| 0x0810100b | 19        | 1.38%   |
| 0x08108102 | 18        | 1.31%   |
| 0x20652    | 17        | 1.23%   |
| 0x10676    | 16        | 1.16%   |
| 0x07030105 | 16        | 1.16%   |
| 0x706e5    | 15        | 1.09%   |
| 0x506c9    | 15        | 1.09%   |
| 0x05000119 | 15        | 1.09%   |
| 0xa0652    | 14        | 1.02%   |
| 0x906e9    | 14        | 1.02%   |
| 0x06001119 | 14        | 1.02%   |
| 0x706a1    | 13        | 0.94%   |
| 0x010000c8 | 12        | 0.87%   |
| 0x106c2    | 9         | 0.65%   |
| 0x06006704 | 9         | 0.65%   |
| 0x706a8    | 8         | 0.58%   |
| 0x08608103 | 8         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 197       | 14.81%  |
| SandyBridge      | 109       | 8.2%    |
| Silvermont       | 88        | 6.62%   |
| IvyBridge        | 88        | 6.62%   |
| Haswell          | 86        | 6.47%   |
| Excavator        | 61        | 4.59%   |
| Skylake          | 60        | 4.51%   |
| Penryn           | 58        | 4.36%   |
| Zen+             | 51        | 3.83%   |
| Broadwell        | 48        | 3.61%   |
| Westmere         | 45        | 3.38%   |
| Core             | 42        | 3.16%   |
| TigerLake        | 35        | 2.63%   |
| Zen 2            | 33        | 2.48%   |
| Bonnell          | 31        | 2.33%   |
| Bobcat           | 29        | 2.18%   |
| Goldmont plus    | 28        | 2.11%   |
| Unknown          | 26        | 1.95%   |
| Zen              | 23        | 1.73%   |
| Piledriver       | 23        | 1.73%   |
| CometLake        | 23        | 1.73%   |
| Puma             | 22        | 1.65%   |
| IceLake          | 20        | 1.5%    |
| Goldmont         | 20        | 1.5%    |
| K8 Hammer        | 17        | 1.28%   |
| K10              | 15        | 1.13%   |
| P6               | 10        | 0.75%   |
| K8 & K10 hybrid  | 9         | 0.68%   |
| Jaguar           | 9         | 0.68%   |
| Zen 3            | 8         | 0.6%    |
| K10 Llano        | 6         | 0.45%   |
| Alderlake Hybrid | 4         | 0.3%    |
| Steamroller      | 3         | 0.23%   |
| Nehalem          | 2         | 0.15%   |
| Tremont          | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 946       | 61.03%  |
| AMD                              | 366       | 23.61%  |
| Nvidia                           | 237       | 15.29%  |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 102       | 6.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 82        | 5.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 60        | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 52        | 3.21%   |
| Intel HD Graphics 5500                                                                   | 44        | 2.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 44        | 2.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 44        | 2.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 41        | 2.53%   |
| Intel HD Graphics 620                                                                    | 40        | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 2.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 39        | 2.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 1.97%   |
| AMD Renoir                                                                               | 32        | 1.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 1.91%   |
| Intel UHD Graphics 620                                                                   | 30        | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 28        | 1.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 28        | 1.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 26        | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 1.48%   |
| Intel HD Graphics 530                                                                    | 22        | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 1.36%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 22        | 1.36%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 1.36%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 20        | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 1.05%   |
| Intel HD Graphics 630                                                                    | 17        | 1.05%   |
| Intel HD Graphics 500                                                                    | 17        | 1.05%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 17        | 1.05%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 0.99%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 15        | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.8%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 13        | 0.8%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 13        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 0.8%    |
| AMD Lucienne                                                                             | 13        | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 10        | 0.62%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 740       | 55.56%  |
| 1 x AMD        | 291       | 21.85%  |
| Intel + Nvidia | 166       | 12.46%  |
| 1 x Nvidia     | 52        | 3.9%    |
| Intel + AMD    | 31        | 2.33%   |
| 2 x AMD        | 26        | 1.95%   |
| AMD + Nvidia   | 18        | 1.35%   |
| Other          | 4         | 0.3%    |
| 2 x Intel      | 3         | 0.23%   |
| 1 x SiS        | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1197      | 89.33%  |
| Proprietary | 117       | 8.73%   |
| Unknown     | 26        | 1.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 886       | 65.34%  |
| 0.01-0.5   | 195       | 14.38%  |
| 1.01-2.0   | 109       | 8.04%   |
| 0.51-1.0   | 88        | 6.49%   |
| 3.01-4.0   | 48        | 3.54%   |
| 5.01-6.0   | 15        | 1.11%   |
| 7.01-8.0   | 11        | 0.81%   |
| 2.01-3.0   | 4         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 264       | 17.66%  |
| BOE                     | 241       | 16.12%  |
| Chimei Innolux          | 214       | 14.31%  |
| LG Display              | 203       | 13.58%  |
| Samsung Electronics     | 164       | 10.97%  |
| Apple                   | 51        | 3.41%   |
| Chi Mei Optoelectronics | 37        | 2.47%   |
| Goldstar                | 30        | 2.01%   |
| Lenovo                  | 28        | 1.87%   |
| Hewlett-Packard         | 27        | 1.81%   |
| Dell                    | 25        | 1.67%   |
| LG Philips              | 21        | 1.4%    |
| BenQ                    | 20        | 1.34%   |
| Sharp                   | 17        | 1.14%   |
| PANDA                   | 17        | 1.14%   |
| Acer                    | 14        | 0.94%   |
| Unknown                 | 10        | 0.67%   |
| HannStar                | 10        | 0.67%   |
| InfoVision              | 8         | 0.54%   |
| Sony                    | 6         | 0.4%    |
| AOC                     | 6         | 0.4%    |
| InnoLux Display         | 5         | 0.33%   |
| Valve                   | 4         | 0.27%   |
| JDI                     | 4         | 0.27%   |
| Gateway                 | 4         | 0.27%   |
| CPT                     | 4         | 0.27%   |
| ___                     | 3         | 0.2%    |
| Toshiba                 | 3         | 0.2%    |
| FOX                     | 3         | 0.2%    |
| CSO                     | 3         | 0.2%    |
| ASUSTek Computer        | 3         | 0.2%    |
| Vizio                   | 2         | 0.13%   |
| ViewSonic               | 2         | 0.13%   |
| Unknown (AAA)           | 2         | 0.13%   |
| TMX                     | 2         | 0.13%   |
| SLD                     | 2         | 0.13%   |
| LGD                     | 2         | 0.13%   |
| KDC                     | 2         | 0.13%   |
| HUAWEI                  | 2         | 0.13%   |
| HKC                     | 2         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 17        | 1.13%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                     | 16        | 1.06%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 13        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.8%    |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 12        | 0.8%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 12        | 0.8%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 12        | 0.8%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 11        | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.66%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 10        | 0.66%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 10        | 0.66%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 10        | 0.66%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 9         | 0.6%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.53%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch          | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch          | 7         | 0.46%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.46%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 7         | 0.46%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 6         | 0.4%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 6         | 0.4%    |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 6         | 0.4%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 6         | 0.4%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 6         | 0.4%    |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 6         | 0.4%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 6         | 0.4%    |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                     | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 704       | 49.51%  |
| 1920x1080 (FHD)    | 390       | 27.43%  |
| 1280x800 (WXGA)    | 88        | 6.19%   |
| 1600x900 (HD+)     | 41        | 2.88%   |
| 1440x900 (WXGA+)   | 25        | 1.76%   |
| 1024x600           | 25        | 1.76%   |
| 3840x2160 (4K)     | 23        | 1.62%   |
| 2160x1440          | 15        | 1.05%   |
| 2560x1440 (QHD)    | 11        | 0.77%   |
| 1360x768           | 9         | 0.63%   |
| 2560x1600          | 8         | 0.56%   |
| 2560x1080          | 8         | 0.56%   |
| 1280x1024 (SXGA)   | 8         | 0.56%   |
| 3440x1440          | 7         | 0.49%   |
| 1920x1200 (WUXGA)  | 7         | 0.49%   |
| 1680x1050 (WSXGA+) | 7         | 0.49%   |
| 1024x768 (XGA)     | 6         | 0.42%   |
| 800x1280           | 5         | 0.35%   |
| 3000x2000          | 5         | 0.35%   |
| 2880x1800          | 5         | 0.35%   |
| 3200x1800 (QHD+)   | 4         | 0.28%   |
| 2520x1680          | 3         | 0.21%   |
| Unknown            | 3         | 0.21%   |
| 3840x2400          | 2         | 0.14%   |
| 2288x1287          | 2         | 0.14%   |
| 1600x1200          | 2         | 0.14%   |
| 1280x768           | 2         | 0.14%   |
| 3840x1080          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |
| 3280x1080          | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |
| 1366x912           | 1         | 0.07%   |
| 1152x864           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 561       | 37.58%  |
| 13      | 285       | 19.09%  |
| 14      | 235       | 15.74%  |
| 11      | 55        | 3.68%   |
| 17      | 43        | 2.88%   |
| 21      | 38        | 2.55%   |
| 12      | 31        | 2.08%   |
| 24      | 28        | 1.88%   |
| 23      | 24        | 1.61%   |
| 10      | 23        | 1.54%   |
| 27      | 20        | 1.34%   |
| 18      | 18        | 1.21%   |
| 16      | 17        | 1.14%   |
| Unknown | 16        | 1.07%   |
| 34      | 14        | 0.94%   |
| 20      | 13        | 0.87%   |
| 19      | 11        | 0.74%   |
| 31      | 10        | 0.67%   |
| 84      | 8         | 0.54%   |
| 22      | 5         | 0.33%   |
| 72      | 4         | 0.27%   |
| 54      | 4         | 0.27%   |
| 40      | 4         | 0.27%   |
| 32      | 4         | 0.27%   |
| 7       | 4         | 0.27%   |
| 142     | 2         | 0.13%   |
| 42      | 2         | 0.13%   |
| 39      | 2         | 0.13%   |
| 8       | 2         | 0.13%   |
| 74      | 1         | 0.07%   |
| 55      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 46      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 35      | 1         | 0.07%   |
| 29      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 966       | 65.18%  |
| 201-300        | 209       | 14.1%   |
| 401-500        | 83        | 5.6%    |
| 501-600        | 71        | 4.79%   |
| 351-400        | 68        | 4.59%   |
| 701-800        | 18        | 1.21%   |
| Unknown        | 16        | 1.08%   |
| 1501-2000      | 13        | 0.88%   |
| 601-700        | 12        | 0.81%   |
| 801-900        | 8         | 0.54%   |
| 1001-1500      | 8         | 0.54%   |
| 1-100          | 4         | 0.27%   |
| More than 2000 | 2         | 0.13%   |
| 101-200        | 2         | 0.13%   |
| 901-1000       | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1117      | 83.55%  |
| 16/10   | 144       | 10.77%  |
| 3/2     | 27        | 2.02%   |
| 21/9    | 15        | 1.12%   |
| 4/3     | 11        | 0.82%   |
| Unknown | 10        | 0.75%   |
| 5/4     | 6         | 0.45%   |
| 0.67    | 4         | 0.3%    |
| 1.00    | 2         | 0.15%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 572       | 38.39%  |
| 81-90          | 463       | 31.07%  |
| 201-250        | 78        | 5.23%   |
| 71-80          | 58        | 3.89%   |
| 51-60          | 55        | 3.69%   |
| 151-200        | 31        | 2.08%   |
| 121-130        | 30        | 2.01%   |
| 61-70          | 29        | 1.95%   |
| 351-500        | 29        | 1.95%   |
| 41-50          | 23        | 1.54%   |
| 141-150        | 22        | 1.48%   |
| More than 1000 | 21        | 1.41%   |
| 301-350        | 21        | 1.41%   |
| Unknown        | 16        | 1.07%   |
| 501-1000       | 10        | 0.67%   |
| 131-140        | 9         | 0.6%    |
| 251-300        | 8         | 0.54%   |
| 1-40           | 6         | 0.4%    |
| 111-120        | 5         | 0.34%   |
| 91-100         | 4         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 723       | 49.39%  |
| 121-160       | 406       | 27.73%  |
| 51-100        | 215       | 14.69%  |
| 161-240       | 56        | 3.83%   |
| 1-50          | 26        | 1.78%   |
| More than 240 | 22        | 1.5%    |
| Unknown       | 16        | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1103      | 80.92%  |
| 2     | 209       | 15.33%  |
| 0     | 29        | 2.13%   |
| 3     | 22        | 1.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 761       | 36.96%  |
| Intel                                  | 521       | 25.3%   |
| Qualcomm Atheros                       | 332       | 16.12%  |
| Broadcom                               | 188       | 9.13%   |
| Broadcom Limited                       | 42        | 2.04%   |
| Ralink                                 | 38        | 1.85%   |
| Marvell Technology Group               | 35        | 1.7%    |
| TP-Link                                | 18        | 0.87%   |
| Ralink Technology                      | 17        | 0.83%   |
| Nvidia                                 | 15        | 0.73%   |
| MediaTek                               | 14        | 0.68%   |
| ASIX Electronics                       | 12        | 0.58%   |
| Huawei Technologies                    | 9         | 0.44%   |
| DisplayLink                            | 6         | 0.29%   |
| Qualcomm Atheros Communications        | 5         | 0.24%   |
| Xiaomi                                 | 4         | 0.19%   |
| Motorola PCS                           | 4         | 0.19%   |
| ICS Advent                             | 4         | 0.19%   |
| Spreadtrum Communications              | 3         | 0.15%   |
| Samsung Electronics                    | 3         | 0.15%   |
| Lenovo                                 | 3         | 0.15%   |
| Qualcomm                               | 2         | 0.1%    |
| JMicron Technology                     | 2         | 0.1%    |
| Dell                                   | 2         | 0.1%    |
| D-Link                                 | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 1         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |
| Shenzhen Goodix Technology             | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |
| NIIMBOT                                | 1         | 0.05%   |
| NetGear                                | 1         | 0.05%   |
| Mercucys                               | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| LG Electronics                         | 1         | 0.05%   |
| Lab126                                 | 1         | 0.05%   |
| Hewlett-Packard                        | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |
| Foxconn / Hon Hai                      | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 379       | 14.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 249       | 9.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 75        | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 61        | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 52        | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 49        | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 47        | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 43        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 1.69%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 42        | 1.65%   |
| Intel Wi-Fi 6 AX200                                               | 41        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                     | 36        | 1.41%   |
| Intel Wireless 7265                                               | 34        | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 30        | 1.18%   |
| Intel Wireless 8265 / 8275                                        | 29        | 1.14%   |
| Intel Wireless 7260                                               | 28        | 1.1%    |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 0.98%   |
| Intel Wireless 8260                                               | 21        | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 21        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 19        | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 19        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.71%   |
| Intel Wireless 3160                                               | 18        | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 18        | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 16        | 0.63%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 16        | 0.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 16        | 0.63%   |
| Intel Wireless 3165                                               | 15        | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 14        | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 14        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 487       | 35.52%  |
| Realtek Semiconductor                 | 316       | 23.05%  |
| Qualcomm Atheros                      | 282       | 20.57%  |
| Broadcom                              | 159       | 11.6%   |
| Ralink                                | 38        | 2.77%   |
| Broadcom Limited                      | 31        | 2.26%   |
| Ralink Technology                     | 17        | 1.24%   |
| TP-Link                               | 16        | 1.17%   |
| MediaTek                              | 11        | 0.8%    |
| Qualcomm Atheros Communications       | 5         | 0.36%   |
| Qualcomm                              | 2         | 0.15%   |
| D-Link                                | 2         | 0.15%   |
| NetGear                               | 1         | 0.07%   |
| Mercucys                              | 1         | 0.07%   |
| Dell                                  | 1         | 0.07%   |
| D-Link System                         | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 75        | 5.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 61        | 4.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 3.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 49        | 3.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 47        | 3.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 43        | 3.08%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 42        | 3.01%   |
| Intel Wi-Fi 6 AX200                                                     | 41        | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 2.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 36        | 2.58%   |
| Intel Wireless 7265                                                     | 34        | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 30        | 2.15%   |
| Intel Wireless 8265 / 8275                                              | 29        | 2.08%   |
| Intel Wireless 7260                                                     | 28        | 2.01%   |
| Intel Wi-Fi 6 AX201                                                     | 28        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 27        | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 27        | 1.94%   |
| Intel Wireless 8260                                                     | 21        | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 21        | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 19        | 1.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 19        | 1.36%   |
| Intel Wireless 3160                                                     | 18        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 16        | 1.15%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 16        | 1.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 16        | 1.15%   |
| Intel Wireless 3165                                                     | 15        | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.86%   |
| Intel WiFi Link 5100                                                    | 12        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.86%   |
| Intel Centrino Ultimate-N 6300                                          | 12        | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 11        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 661       | 58.34%  |
| Intel                                  | 189       | 16.68%  |
| Qualcomm Atheros                       | 103       | 9.09%   |
| Broadcom                               | 60        | 5.3%    |
| Marvell Technology Group               | 35        | 3.09%   |
| Nvidia                                 | 15        | 1.32%   |
| ASIX Electronics                       | 12        | 1.06%   |
| Broadcom Limited                       | 11        | 0.97%   |
| Huawei Technologies                    | 8         | 0.71%   |
| DisplayLink                            | 6         | 0.53%   |
| Xiaomi                                 | 4         | 0.35%   |
| ICS Advent                             | 4         | 0.35%   |
| Spreadtrum Communications              | 3         | 0.26%   |
| MediaTek                               | 3         | 0.26%   |
| Lenovo                                 | 3         | 0.26%   |
| TP-Link                                | 2         | 0.18%   |
| JMicron Technology                     | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.09%   |
| T & A Mobile Phones                    | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.09%   |
| Samsung Electronics                    | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| Motorola PCS                           | 1         | 0.09%   |
| Linksys                                | 1         | 0.09%   |
| LG Electronics                         | 1         | 0.09%   |
| Lab126                                 | 1         | 0.09%   |
| Google                                 | 1         | 0.09%   |
| Foxconn / Hon Hai                      | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 379       | 33.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 249       | 21.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 43        | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 25        | 2.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 18        | 1.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 18        | 1.58%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                                          | 13        | 1.14%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 12        | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 12        | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 12        | 1.05%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 1.05%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 11        | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                       | 11        | 0.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 10        | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 10        | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.79%   |
| Intel Ethernet Connection I217-LM                                              | 9         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 9         | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 8         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 0.7%    |
| Nvidia MCP67 Ethernet                                                          | 7         | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                                           | 7         | 0.61%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.61%   |
| Huawei ATU-L21                                                                 | 7         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 6         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 5         | 0.44%   |
| Intel Ethernet Connection I219-V                                               | 5         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                                          | 5         | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.35%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.35%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 4         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1308      | 54.07%  |
| Ethernet | 1096      | 45.31%  |
| Modem    | 10        | 0.41%   |
| Unknown  | 5         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1069      | 75.33%  |
| Ethernet | 349       | 24.59%  |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1018      | 76.54%  |
| 1     | 285       | 21.43%  |
| 0     | 22        | 1.65%   |
| 3     | 5         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 970       | 71.22%  |
| Yes  | 392       | 28.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 348       | 35.01%  |
| Realtek Semiconductor           | 191       | 19.22%  |
| Qualcomm Atheros Communications | 105       | 10.56%  |
| Broadcom                        | 73        | 7.34%   |
| Lite-On Technology              | 45        | 4.53%   |
| Apple                           | 42        | 4.23%   |
| Foxconn / Hon Hai               | 36        | 3.62%   |
| IMC Networks                    | 35        | 3.52%   |
| Dell                            | 24        | 2.41%   |
| Hewlett-Packard                 | 20        | 2.01%   |
| Toshiba                         | 18        | 1.81%   |
| Realtek                         | 17        | 1.71%   |
| Ralink                          | 16        | 1.61%   |
| Cambridge Silicon Radio         | 8         | 0.8%    |
| Ralink Technology               | 6         | 0.6%    |
| Alps Electric                   | 4         | 0.4%    |
| Foxconn International           | 3         | 0.3%    |
| Integrated System Solution      | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |
| ASUSTek Computer                | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 141       | 14.16%  |
| Realtek Bluetooth Radio                                                             | 82        | 8.23%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 79        | 7.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 77        | 7.73%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 66        | 6.63%   |
| Intel AX201 Bluetooth                                                               | 51        | 5.12%   |
| Intel AX200 Bluetooth                                                               | 40        | 4.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 20        | 2.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 18        | 1.81%   |
| Apple Bluetooth Host Controller                                                     | 18        | 1.81%   |
| Realtek 802.11ac WLAN Adapter                                                       | 17        | 1.71%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 16        | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 1.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 15        | 1.51%   |
| IMC Networks Bluetooth Radio                                                        | 15        | 1.51%   |
| Apple Bluetooth USB Host Controller                                                 | 15        | 1.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 14        | 1.41%   |
| Realtek RTL8723B Bluetooth                                                          | 13        | 1.31%   |
| Lite-On Bluetooth Device                                                            | 13        | 1.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 13        | 1.31%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 10        | 1%      |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 1%      |
| Realtek RTL8821A Bluetooth                                                          | 9         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 9         | 0.9%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.8%    |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 0.7%    |
| IMC Networks Wireless_Device                                                        | 6         | 0.6%    |
| IMC Networks Bluetooth Device                                                       | 6         | 0.6%    |
| Dell Wireless 355 Bluetooth                                                         | 6         | 0.6%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 0.5%    |
| Broadcom HP Portable Bumble Bee                                                     | 5         | 0.5%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.5%    |
| Apple Bluetooth HCI                                                                 | 5         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 983       | 63.91%  |
| AMD                                             | 331       | 21.52%  |
| Nvidia                                          | 146       | 9.49%   |
| Logitech                                        | 8         | 0.52%   |
| Texas Instruments                               | 7         | 0.46%   |
| C-Media Electronics                             | 7         | 0.46%   |
| Realtek Semiconductor                           | 5         | 0.33%   |
| Plantronics                                     | 5         | 0.33%   |
| Generalplus Technology                          | 5         | 0.33%   |
| Tenx Technology                                 | 4         | 0.26%   |
| Lenovo                                          | 4         | 0.26%   |
| Kingston Technology                             | 4         | 0.26%   |
| GN Netcom                                       | 4         | 0.26%   |
| Creative Technology                             | 3         | 0.2%    |
| Syntek                                          | 2         | 0.13%   |
| Samson Technologies                             | 2         | 0.13%   |
| JMTek                                           | 2         | 0.13%   |
| Apple                                           | 2         | 0.13%   |
| Yamaha                                          | 1         | 0.07%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.07%   |
| Synaptics                                       | 1         | 0.07%   |
| Sony                                            | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.07%   |
| Sennheiser Communications                       | 1         | 0.07%   |
| Samsung Electronics                             | 1         | 0.07%   |
| Razer USA                                       | 1         | 0.07%   |
| M-Audio                                         | 1         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.07%   |
| DisplayLink                                     | 1         | 0.07%   |
| DCMT Technology                                 | 1         | 0.07%   |
| Cambridge Audio                                 | 1         | 0.07%   |
| ASUSTek Computer                                | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 115       | 5.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 112       | 5.78%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 110       | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 82        | 4.23%   |
| AMD FCH Azalia Controller                                                                         | 74        | 3.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 71        | 3.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 60        | 3.1%    |
| Intel 8 Series HD Audio Controller                                                                | 60        | 3.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 60        | 3.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 53        | 2.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 51        | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 48        | 2.48%   |
| Intel Broadwell-U Audio Controller                                                                | 48        | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 47        | 2.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 47        | 2.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 46        | 2.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 44        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 42        | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 40        | 2.07%   |
| AMD High Definition Audio Controller                                                              | 39        | 2.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 37        | 1.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 35        | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 35        | 1.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 34        | 1.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 29        | 1.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 28        | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 24        | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 23        | 1.19%   |
| AMD Trinity HDMI Audio Controller                                                                 | 23        | 1.19%   |
| Intel Comet Lake PCH cAVS                                                                         | 22        | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 18        | 0.93%   |
| AMD Wrestler HDMI Audio                                                                           | 17        | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 0.77%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 13        | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 10        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 221       | 27.8%   |
| SK hynix                                         | 178       | 22.39%  |
| Kingston                                         | 106       | 13.33%  |
| Micron Technology                                | 101       | 12.7%   |
| Unknown                                          | 56        | 7.04%   |
| A-DATA Technology                                | 33        | 4.15%   |
| Ramaxel Technology                               | 27        | 3.4%    |
| Elpida                                           | 12        | 1.51%   |
| Unknown (ABCD)                                   | 11        | 1.38%   |
| Nanya Technology                                 | 10        | 1.26%   |
| Crucial                                          | 10        | 1.26%   |
| Corsair                                          | 6         | 0.75%   |
| Team                                             | 3         | 0.38%   |
| PNY                                              | 3         | 0.38%   |
| Transcend                                        | 2         | 0.25%   |
| Qimonda                                          | 2         | 0.25%   |
| Patriot                                          | 2         | 0.25%   |
| ChangXin Memory                                  | 2         | 0.25%   |
| Unknown                                          | 2         | 0.25%   |
| Unknown (0x8AF1)                                 | 1         | 0.13%   |
| Unknown (0x4D342037305435363633515A332D43453620) | 1         | 0.13%   |
| Timetec                                          | 1         | 0.13%   |
| SHARETRONIC                                      | 1         | 0.13%   |
| Goldkey                                          | 1         | 0.13%   |
| Avant                                            | 1         | 0.13%   |
| 3235CB0010E4                                     | 1         | 0.13%   |
| 0161000080AD                                     | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 2.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 1.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 11        | 1.28%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 11        | 1.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.16%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 1.05%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 1.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 0.81%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.81%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 0.81%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 7         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 6         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.58%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.58%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 5         | 0.58%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 5         | 0.58%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 5         | 0.58%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 5         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 4         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 4         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 0.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 4         | 0.47%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 270       | 41.54%  |
| DDR4    | 262       | 40.31%  |
| DDR2    | 42        | 6.46%   |
| LPDDR4  | 27        | 4.15%   |
| LPDDR3  | 21        | 3.23%   |
| SDRAM   | 11        | 1.69%   |
| DDR     | 7         | 1.08%   |
| Unknown | 5         | 0.77%   |
| LPDDR5  | 2         | 0.31%   |
| DDR5    | 2         | 0.31%   |
| RAM     | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 579       | 89.08%  |
| Row Of Chips | 66        | 10.15%  |
| Chip         | 4         | 0.62%   |
| Unknown      | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 282       | 37.4%   |
| 8192  | 275       | 36.47%  |
| 2048  | 111       | 14.72%  |
| 16384 | 47        | 6.23%   |
| 1024  | 28        | 3.71%   |
| 32768 | 7         | 0.93%   |
| 512   | 3         | 0.4%    |
| 256   | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 208       | 28.77%  |
| 2667    | 139       | 19.23%  |
| 3200    | 72        | 9.96%   |
| 2400    | 51        | 7.05%   |
| 2133    | 40        | 5.53%   |
| 1334    | 37        | 5.12%   |
| 1333    | 34        | 4.7%    |
| 667     | 26        | 3.6%    |
| 3266    | 25        | 3.46%   |
| Unknown | 20        | 2.77%   |
| 4267    | 12        | 1.66%   |
| 800     | 11        | 1.52%   |
| 2048    | 7         | 0.97%   |
| 1867    | 6         | 0.83%   |
| 975     | 6         | 0.83%   |
| 1067    | 5         | 0.69%   |
| 1066    | 5         | 0.69%   |
| 4199    | 4         | 0.55%   |
| 533     | 4         | 0.55%   |
| 8400    | 3         | 0.41%   |
| 6400    | 2         | 0.28%   |
| 4800    | 2         | 0.28%   |
| 3733    | 2         | 0.28%   |
| 2933    | 1         | 0.14%   |
| 400     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 3         | 23.08%  |
| Samsung Electronics    | 2         | 15.38%  |
| Hewlett-Packard        | 2         | 15.38%  |
| Brother Industries     | 2         | 15.38%  |
| TSC Auto ID Technology | 1         | 7.69%   |
| Kyocera                | 1         | 7.69%   |
| Canon                  | 1         | 7.69%   |
| BIXOLON                | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP DeskJet 2300 series  | 2         | 15.38%  |
| TSC Auto ID Printer     | 1         | 7.69%   |
| Seiko Epson L555 Series | 1         | 7.69%   |
| Seiko Epson L210 Series | 1         | 7.69%   |
| Seiko Epson L120 Series | 1         | 7.69%   |
| Samsung ML-1660 Series  | 1         | 7.69%   |
| Samsung M2020 Series    | 1         | 7.69%   |
| Kyocera FS-1116MFP      | 1         | 7.69%   |
| Canon iP2600 series     | 1         | 7.69%   |
| Brother MFC-J470DW      | 1         | 7.69%   |
| Brother DCP-1510        | 1         | 7.69%   |
| BIXOLON SRP-350plusIII  | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| HP ScanJet 5590 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 291       | 23.95%  |
| IMC Networks                           | 119       | 9.79%   |
| Microdia                               | 116       | 9.55%   |
| Realtek Semiconductor                  | 86        | 7.08%   |
| Cheng Uei Precision Industry (Foxlink) | 72        | 5.93%   |
| Suyin                                  | 63        | 5.19%   |
| Sunplus Innovation Technology          | 63        | 5.19%   |
| Quanta                                 | 52        | 4.28%   |
| Syntek                                 | 42        | 3.46%   |
| Acer                                   | 41        | 3.37%   |
| Bison Electronics                      | 36        | 2.96%   |
| Apple                                  | 34        | 2.8%    |
| Lite-On Technology                     | 33        | 2.72%   |
| Ricoh                                  | 21        | 1.73%   |
| Silicon Motion                         | 19        | 1.56%   |
| Importek                               | 15        | 1.23%   |
| Alcor Micro                            | 14        | 1.15%   |
| Logitech                               | 13        | 1.07%   |
| Luxvisions Innotech Limited            | 8         | 0.66%   |
| ALi                                    | 8         | 0.66%   |
| Primax Electronics                     | 6         | 0.49%   |
| OmniVision Technologies                | 6         | 0.49%   |
| Y Media                                | 5         | 0.41%   |
| Sonix Technology                       | 4         | 0.33%   |
| Genesys Logic                          | 4         | 0.33%   |
| Microsoft                              | 3         | 0.25%   |
| MacroSilicon                           | 3         | 0.25%   |
| Lenovo                                 | 3         | 0.25%   |
| icSpring                               | 3         | 0.25%   |
| Generalplus Technology                 | 3         | 0.25%   |
| BKX                                    | 3         | 0.25%   |
| Z-Star Microelectronics                | 2         | 0.16%   |
| Tobii Technology AB                    | 2         | 0.16%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Samsung Electronics                    | 2         | 0.16%   |
| Jieli Technology                       | 2         | 0.16%   |
| DigiTech                               | 2         | 0.16%   |
| YGTek                                  | 1         | 0.08%   |
| Novatek Microelectronics               | 1         | 0.08%   |
| Nebraska Furniture Mart                | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 42        | 3.44%   |
| Microdia Integrated_Webcam_HD                                              | 41        | 3.36%   |
| Chicony HD WebCam                                                          | 31        | 2.54%   |
| IMC Networks Integrated Camera                                             | 24        | 1.97%   |
| IMC Networks HD Camera                                                     | 22        | 1.8%    |
| Realtek Integrated_Webcam_HD                                               | 21        | 1.72%   |
| Chicony HP Webcam                                                          | 21        | 1.72%   |
| Sunplus Integrated_Webcam_HD                                               | 19        | 1.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 17        | 1.39%   |
| Apple FaceTime HD Camera                                                   | 17        | 1.39%   |
| Acer Integrated Camera                                                     | 17        | 1.39%   |
| Syntek Lenovo EasyCamera                                                   | 15        | 1.23%   |
| Chicony HP Truevision HD                                                   | 15        | 1.23%   |
| Microdia Integrated Webcam                                                 | 14        | 1.15%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 14        | 1.15%   |
| Chicony HP Truevision HD camera                                            | 14        | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 14        | 1.15%   |
| Quanta HP Webcam                                                           | 13        | 1.07%   |
| Sunplus HD Webcam                                                          | 12        | 0.98%   |
| IMC Networks EasyCamera                                                    | 12        | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 12        | 0.98%   |
| Syntek Integrated Camera                                                   | 11        | 0.9%    |
| Chicony HP Wide Vision HD Camera                                           | 11        | 0.9%    |
| Suyin HP Truevision HD                                                     | 10        | 0.82%   |
| Lite-On HP Wide Vision HD Camera                                           | 10        | 0.82%   |
| Chicony USB 2.0 Camera                                                     | 10        | 0.82%   |
| Chicony TOSHIBA Web Camera - HD                                            | 10        | 0.82%   |
| Chicony HP HD Camera                                                       | 10        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 10        | 0.82%   |
| Bison Integrated Camera                                                    | 10        | 0.82%   |
| Microdia Lenovo EasyCamera                                                 | 9         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 9         | 0.74%   |
| Realtek HP Truevision HD                                                   | 8         | 0.66%   |
| Realtek HD WebCam                                                          | 8         | 0.66%   |
| Microdia Sonix USB 2.0 Camera                                              | 8         | 0.66%   |
| Chicony Lenovo EasyCamera                                                  | 8         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 8         | 0.66%   |
| Bison EasyCamera                                                           | 8         | 0.66%   |
| Acer Lenovo EasyCamera                                                     | 8         | 0.66%   |
| Syntek EasyCamera                                                          | 7         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 80        | 37.04%  |
| Shenzhen Goodix Technology         | 46        | 21.3%   |
| Synaptics                          | 32        | 14.81%  |
| AuthenTec                          | 19        | 8.8%    |
| Upek                               | 15        | 6.94%   |
| Elan Microelectronics              | 7         | 3.24%   |
| STMicroelectronics                 | 5         | 2.31%   |
| Focal-systems.Corp                 | 5         | 2.31%   |
| LighTuning Technology              | 3         | 1.39%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.93%   |
| Suprema                            | 1         | 0.46%   |
| Samsung Electronics                | 1         | 0.46%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 18.98%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 8.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 6.02%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 6.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 5.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 4.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 4.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 4.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.31%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 2.31%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 2.31%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 2.31%   |
| AuthenTec AES2810                                                          | 5         | 2.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.85%   |
| Validity Sensors VFS491                                                    | 4         | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.85%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.85%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.39%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.39%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.39%   |
| AuthenTec AES1600                                                          | 3         | 1.39%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.93%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 0.93%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.93%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.93%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.93%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.93%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.46%   |
| Synaptics WBDI                                                             | 1         | 0.46%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.46%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.46%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.46%   |
| Samsung Fingerprint Device                                                 | 1         | 0.46%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 37        | 60.66%  |
| Alcor Micro           | 11        | 18.03%  |
| Upek                  | 7         | 11.48%  |
| Lenovo                | 5         | 8.2%    |
| Gemalto (was Gemplus) | 1         | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 22.95%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 19.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 18.03%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 11.48%  |
| Broadcom 58200                                                               | 6         | 9.84%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 8.2%    |
| Broadcom 5880                                                                | 4         | 6.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 857       | 63.06%  |
| 1     | 413       | 30.39%  |
| 2     | 78        | 5.74%   |
| 3     | 7         | 0.52%   |
| 5     | 2         | 0.15%   |
| 7     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 213       | 35.68%  |
| Graphics card            | 109       | 18.26%  |
| Net/wireless             | 86        | 14.41%  |
| Chipcard                 | 58        | 9.72%   |
| Multimedia controller    | 34        | 5.7%    |
| Bluetooth                | 21        | 3.52%   |
| Camera                   | 20        | 3.35%   |
| Communication controller | 12        | 2.01%   |
| Storage                  | 10        | 1.68%   |
| Net/ethernet             | 10        | 1.68%   |
| Sound                    | 7         | 1.17%   |
| Card reader              | 6         | 1.01%   |
| Modem                    | 5         | 0.84%   |
| Network                  | 3         | 0.5%    |
| Storage/ide              | 1         | 0.17%   |
| Firewire controller      | 1         | 0.17%   |
| Dvb card                 | 1         | 0.17%   |

