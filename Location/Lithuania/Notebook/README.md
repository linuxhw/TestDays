Linux in Lithuania - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

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

Total: 522

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 15IRX10 83LY       | [4f082892b3](https://linux-hardware.org/?probe=4f082892b3) | Dec 30, 2025 |
| HP            | EliteBook 845 G7 Noteboo... | [9b95796474](https://linux-hardware.org/?probe=9b95796474) | Dec 29, 2025 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [304b46260d](https://linux-hardware.org/?probe=304b46260d) | Dec 27, 2025 |
| Acer          | Aspire VN7-593G             | [059d7078c4](https://linux-hardware.org/?probe=059d7078c4) | Dec 23, 2025 |
| Apple         | MacBookAir6,2               | [8c7ac32499](https://linux-hardware.org/?probe=8c7ac32499) | Dec 20, 2025 |
| HP            | ProBook 455 G7              | [3cfae5d2e3](https://linux-hardware.org/?probe=3cfae5d2e3) | Dec 17, 2025 |
| Lenovo        | Y520-15IKBM 80YY            | [e6c7a15772](https://linux-hardware.org/?probe=e6c7a15772) | Dec 10, 2025 |
| Dell          | G5 5590                     | [a7784fbd62](https://linux-hardware.org/?probe=a7784fbd62) | Dec 04, 2025 |
| HP            | EliteBook 845 14 inch G1... | [b3e1d6bcc2](https://linux-hardware.org/?probe=b3e1d6bcc2) | Nov 29, 2025 |
| MSI           | Thin A15 B7UC               | [7a418cb4a1](https://linux-hardware.org/?probe=7a418cb4a1) | Nov 20, 2025 |
| Founder       | Veriton Balao               | [e8d347d21f](https://linux-hardware.org/?probe=e8d347d21f) | Nov 09, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [8d98956ad1](https://linux-hardware.org/?probe=8d98956ad1) | Oct 07, 2025 |
| Dell          | G5 5590                     | [3770723293](https://linux-hardware.org/?probe=3770723293) | Sep 28, 2025 |
| Lenovo        | Legion y540 15IRH 81SX      | [25fff34c25](https://linux-hardware.org/?probe=25fff34c25) | Sep 21, 2025 |
| Lenovo        | ThinkPad X260 20F5S2NN01    | [25ac357819](https://linux-hardware.org/?probe=25ac357819) | Sep 19, 2025 |
| LIVEFAN       | Unknown                     | [e0ac313de5](https://linux-hardware.org/?probe=e0ac313de5) | Sep 17, 2025 |
| Acer          | Swift SF314-510G            | [a47d7c6003](https://linux-hardware.org/?probe=a47d7c6003) | Sep 14, 2025 |
| Dell          | Inspiron 7520               | [ec8d171969](https://linux-hardware.org/?probe=ec8d171969) | Sep 07, 2025 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [af0afe24bd](https://linux-hardware.org/?probe=af0afe24bd) | Sep 01, 2025 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [feb7618768](https://linux-hardware.org/?probe=feb7618768) | Sep 01, 2025 |
| Fujitsu       | LIFEBOOK A544               | [cf9feb946f](https://linux-hardware.org/?probe=cf9feb946f) | Aug 30, 2025 |
| Fujitsu       | LIFEBOOK A544               | [0d2cbac126](https://linux-hardware.org/?probe=0d2cbac126) | Aug 30, 2025 |
| Dell          | G5 5587                     | [5e881988d8](https://linux-hardware.org/?probe=5e881988d8) | Aug 21, 2025 |
| Lenovo        | B575e 36852DG               | [4459e655aa](https://linux-hardware.org/?probe=4459e655aa) | Aug 18, 2025 |
| Toshiba       | Satellite C55-A-1H1         | [46d169b35f](https://linux-hardware.org/?probe=46d169b35f) | Aug 15, 2025 |
| Dell          | Latitude E6520              | [c1c387694c](https://linux-hardware.org/?probe=c1c387694c) | Jul 15, 2025 |
| Valve         | Galileo                     | [f621354788](https://linux-hardware.org/?probe=f621354788) | Jul 13, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | [c2a2ec1d63](https://linux-hardware.org/?probe=c2a2ec1d63) | Jul 07, 2025 |
| ASUSTek       | ASUS Vivobook 18 M1807HA... | [732ea02185](https://linux-hardware.org/?probe=732ea02185) | Jun 27, 2025 |
| HP            | 255 15.6 inch G9 Noteboo... | [7d6309811a](https://linux-hardware.org/?probe=7d6309811a) | Jun 19, 2025 |
| HP            | EliteBook 8440p             | [35290b1a76](https://linux-hardware.org/?probe=35290b1a76) | Jun 18, 2025 |
| Acer          | Swift SF314-510G            | [e724265a9b](https://linux-hardware.org/?probe=e724265a9b) | Jun 15, 2025 |
| HP            | OMEN by Laptop 16-b1xxx     | [33b8476dda](https://linux-hardware.org/?probe=33b8476dda) | Jun 12, 2025 |
| HP            | 255 15.6 inch G9 Noteboo... | [9a5d701e5a](https://linux-hardware.org/?probe=9a5d701e5a) | Jun 05, 2025 |
| HP            | EliteBook 8560w             | [955a8ec175](https://linux-hardware.org/?probe=955a8ec175) | Jun 03, 2025 |
| Acer          | Aspire A315-44P             | [495e09c0c4](https://linux-hardware.org/?probe=495e09c0c4) | May 28, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [b271f4bee4](https://linux-hardware.org/?probe=b271f4bee4) | May 18, 2025 |
| Acer          | Aspire A315-22              | [4b4180a83d](https://linux-hardware.org/?probe=4b4180a83d) | May 12, 2025 |
| Acer          | Aspire A315-22              | [32a38ce05d](https://linux-hardware.org/?probe=32a38ce05d) | May 12, 2025 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f1c5374fdb](https://linux-hardware.org/?probe=f1c5374fdb) | May 08, 2025 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1843734a30](https://linux-hardware.org/?probe=1843734a30) | May 08, 2025 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [662d929045](https://linux-hardware.org/?probe=662d929045) | May 05, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [96f23d70bb](https://linux-hardware.org/?probe=96f23d70bb) | May 03, 2025 |
| ASUSTek       | ASUS Vivobook S 15 S5507... | [4a7aecfbf4](https://linux-hardware.org/?probe=4a7aecfbf4) | May 02, 2025 |
| Dell          | G5 5587                     | [7b8d38901d](https://linux-hardware.org/?probe=7b8d38901d) | May 02, 2025 |
| Acer          | Predator PT315-52           | [6675ee758a](https://linux-hardware.org/?probe=6675ee758a) | May 01, 2025 |
| Dell          | Vostro 3520                 | [dca733d29a](https://linux-hardware.org/?probe=dca733d29a) | Apr 27, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [7be920486a](https://linux-hardware.org/?probe=7be920486a) | Mar 14, 2025 |
| Lenovo        | ThinkPad X230 2324HZ9       | [a964f5b4dc](https://linux-hardware.org/?probe=a964f5b4dc) | Mar 11, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | [2864de1320](https://linux-hardware.org/?probe=2864de1320) | Mar 10, 2025 |
| Lenovo        | ThinkPad X230 2324HZ9       | [0ad576c3a0](https://linux-hardware.org/?probe=0ad576c3a0) | Mar 10, 2025 |
| Dell          | Latitude 6430U              | [4ec2ca9dba](https://linux-hardware.org/?probe=4ec2ca9dba) | Mar 07, 2025 |
| Dell          | G5 5590                     | [8f611efe9b](https://linux-hardware.org/?probe=8f611efe9b) | Feb 27, 2025 |
| Dell          | G5 5590                     | [4ba539e8f1](https://linux-hardware.org/?probe=4ba539e8f1) | Feb 26, 2025 |
| HP            | ProBook 4530s               | [1dc13d5976](https://linux-hardware.org/?probe=1dc13d5976) | Feb 25, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [e5eebb0ef9](https://linux-hardware.org/?probe=e5eebb0ef9) | Feb 12, 2025 |
| HP            | Laptop 17-cn2xxx            | [95c78d15c8](https://linux-hardware.org/?probe=95c78d15c8) | Feb 10, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | [0819155de0](https://linux-hardware.org/?probe=0819155de0) | Jan 26, 2025 |
| HP            | 255 G8 Notebook PC          | [5b43d9cbbc](https://linux-hardware.org/?probe=5b43d9cbbc) | Jan 19, 2025 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [94f872b551](https://linux-hardware.org/?probe=94f872b551) | Jan 13, 2025 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [3cd4965210](https://linux-hardware.org/?probe=3cd4965210) | Jan 04, 2025 |
| HONOR         | HYM-WXX                     | [6b719e5c5d](https://linux-hardware.org/?probe=6b719e5c5d) | Dec 28, 2024 |
| Lenovo        | LOQ 15AHP9 83DX             | [c4d33f738c](https://linux-hardware.org/?probe=c4d33f738c) | Dec 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y2... | [b7ad8c7467](https://linux-hardware.org/?probe=b7ad8c7467) | Dec 21, 2024 |
| HP            | ZBook 15 G2                 | [ccdf904498](https://linux-hardware.org/?probe=ccdf904498) | Dec 20, 2024 |
| MSI           | Stealth 16 AI Studio A1V... | [ab7f87b6f5](https://linux-hardware.org/?probe=ab7f87b6f5) | Dec 16, 2024 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [1f398807de](https://linux-hardware.org/?probe=1f398807de) | Dec 12, 2024 |
| ASUSTek       | G751JT                      | [2bbcb36d29](https://linux-hardware.org/?probe=2bbcb36d29) | Dec 03, 2024 |
| Acer          | Aspire 5750G                | [1fb7124f16](https://linux-hardware.org/?probe=1fb7124f16) | Dec 03, 2024 |
| ASUSTek       | X555LN                      | [8fe10d8894](https://linux-hardware.org/?probe=8fe10d8894) | Nov 30, 2024 |
| Apple         | MacBookPro9,2               | [58f0a1ff3a](https://linux-hardware.org/?probe=58f0a1ff3a) | Nov 30, 2024 |
| Dell          | Vostro 3578                 | [2490918f08](https://linux-hardware.org/?probe=2490918f08) | Nov 24, 2024 |
| Acer          | Aspire A515-48M             | [7e76e833e3](https://linux-hardware.org/?probe=7e76e833e3) | Nov 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [c3b63fd37e](https://linux-hardware.org/?probe=c3b63fd37e) | Nov 18, 2024 |
| Valve         | Jupiter                     | [1caa8b41f8](https://linux-hardware.org/?probe=1caa8b41f8) | Nov 14, 2024 |
| Valve         | Jupiter                     | [158bfeec61](https://linux-hardware.org/?probe=158bfeec61) | Nov 13, 2024 |
| Apple         | MacBookPro9,2               | [03d50f54b5](https://linux-hardware.org/?probe=03d50f54b5) | Nov 12, 2024 |
| Toshiba       | WT8-A                       | [e99f4125d4](https://linux-hardware.org/?probe=e99f4125d4) | Nov 10, 2024 |
| Acer          | Predator PH315-53           | [f1266330e4](https://linux-hardware.org/?probe=f1266330e4) | Nov 08, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ceeeb0ce3f](https://linux-hardware.org/?probe=ceeeb0ce3f) | Nov 01, 2024 |
| Lenovo        | ThinkPad T450 20BUS0H200    | [f2c4a96ba0](https://linux-hardware.org/?probe=f2c4a96ba0) | Nov 01, 2024 |
| Lenovo        | ThinkPad T450 20BUS0H200    | [c169540ec2](https://linux-hardware.org/?probe=c169540ec2) | Nov 01, 2024 |
| Dell          | Latitude 5580               | [5eb086f8c2](https://linux-hardware.org/?probe=5eb086f8c2) | Oct 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [08b6a5d7d3](https://linux-hardware.org/?probe=08b6a5d7d3) | Oct 26, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | [7f94eafaf2](https://linux-hardware.org/?probe=7f94eafaf2) | Oct 25, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | [20e158e9fb](https://linux-hardware.org/?probe=20e158e9fb) | Oct 25, 2024 |
| Dell          | Latitude E6420              | [62acf0960f](https://linux-hardware.org/?probe=62acf0960f) | Oct 13, 2024 |
| Dell          | Vostro 3520                 | [1da2193371](https://linux-hardware.org/?probe=1da2193371) | Oct 12, 2024 |
| XIAOMI        | Redmi Book Pro 16 2024      | [0566eccc4c](https://linux-hardware.org/?probe=0566eccc4c) | Sep 29, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [27da4fdb75](https://linux-hardware.org/?probe=27da4fdb75) | Sep 26, 2024 |
| ASUSTek       | X555LN                      | [fc48a399c1](https://linux-hardware.org/?probe=fc48a399c1) | Sep 23, 2024 |
| ASUSTek       | M50Vn                       | [2e22fd3bd2](https://linux-hardware.org/?probe=2e22fd3bd2) | Sep 22, 2024 |
| ASUSTek       | X555LN                      | [acbf9d7e70](https://linux-hardware.org/?probe=acbf9d7e70) | Sep 12, 2024 |
| HP            | ZBook 15 G2                 | [144f86e54b](https://linux-hardware.org/?probe=144f86e54b) | Sep 07, 2024 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4S... | [f6500b9c01](https://linux-hardware.org/?probe=f6500b9c01) | Sep 06, 2024 |
| Toshiba       | WT8-A                       | [427fe42ea1](https://linux-hardware.org/?probe=427fe42ea1) | Aug 30, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [bd4a519cc3](https://linux-hardware.org/?probe=bd4a519cc3) | Aug 26, 2024 |
| Apple         | MacBook5,1                  | [69ab889544](https://linux-hardware.org/?probe=69ab889544) | Aug 26, 2024 |
| Lenovo        | Z710 20250                  | [b199061083](https://linux-hardware.org/?probe=b199061083) | Aug 25, 2024 |
| Lenovo        | Z710 20250                  | [4f5bbb6201](https://linux-hardware.org/?probe=4f5bbb6201) | Aug 25, 2024 |
| Acer          | Aspire 5750G                | [550fd81be0](https://linux-hardware.org/?probe=550fd81be0) | Aug 23, 2024 |
| Acer          | Aspire 5750G                | [5171e2cc88](https://linux-hardware.org/?probe=5171e2cc88) | Aug 22, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b543fa8dec](https://linux-hardware.org/?probe=b543fa8dec) | Aug 17, 2024 |
| ASUSTek       | X555LN                      | [f1bf5f5504](https://linux-hardware.org/?probe=f1bf5f5504) | Aug 06, 2024 |
| Lenovo        | IdeaPad Z580                | [cb672c1d21](https://linux-hardware.org/?probe=cb672c1d21) | Aug 05, 2024 |
| Dell          | Vostro 5490                 | [8582fd1c71](https://linux-hardware.org/?probe=8582fd1c71) | Aug 01, 2024 |
| Fujitsu       | LIFEBOOK E554               | [df893fa78f](https://linux-hardware.org/?probe=df893fa78f) | Jul 30, 2024 |
| Fujitsu       | LIFEBOOK E554               | [010cf4260e](https://linux-hardware.org/?probe=010cf4260e) | Jul 30, 2024 |
| ASUSTek       | GL552VX                     | [a54d8753e5](https://linux-hardware.org/?probe=a54d8753e5) | Jul 28, 2024 |
| HP            | Pavilion g6                 | [8d4cd1cce3](https://linux-hardware.org/?probe=8d4cd1cce3) | Jul 25, 2024 |
| ASUSTek       | X555LN                      | [c97fa10f61](https://linux-hardware.org/?probe=c97fa10f61) | Jul 14, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a89abcf2b8](https://linux-hardware.org/?probe=a89abcf2b8) | Jul 13, 2024 |
| HP            | Laptop 17-ca1xxx            | [7b6bf257b9](https://linux-hardware.org/?probe=7b6bf257b9) | Jul 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [111614cf4c](https://linux-hardware.org/?probe=111614cf4c) | Jul 08, 2024 |
| Acer          | Aspire A315-58              | [647ca9ecb0](https://linux-hardware.org/?probe=647ca9ecb0) | Jul 04, 2024 |
| HP            | ProBook 650 G2              | [b2c03fc0a5](https://linux-hardware.org/?probe=b2c03fc0a5) | Jun 18, 2024 |
| Dell          | Inspiron N5110              | [110790c81a](https://linux-hardware.org/?probe=110790c81a) | Jun 14, 2024 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [ed148c6672](https://linux-hardware.org/?probe=ed148c6672) | Jun 09, 2024 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [46b02b8b55](https://linux-hardware.org/?probe=46b02b8b55) | Jun 08, 2024 |
| Lenovo        | G560 20042                  | [3cf1e98f3b](https://linux-hardware.org/?probe=3cf1e98f3b) | Jun 06, 2024 |
| Prestigio     | PSB141C03                   | [c7612dfd34](https://linux-hardware.org/?probe=c7612dfd34) | Jun 03, 2024 |
| HP            | EliteBook 8440p             | [0707d81b82](https://linux-hardware.org/?probe=0707d81b82) | Jun 03, 2024 |
| Dell          | Latitude 5540               | [dba27825e6](https://linux-hardware.org/?probe=dba27825e6) | May 29, 2024 |
| Dell          | Latitude 5540               | [aa8fd65cf6](https://linux-hardware.org/?probe=aa8fd65cf6) | May 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [50e4cb18c3](https://linux-hardware.org/?probe=50e4cb18c3) | May 23, 2024 |
| ASUSTek       | X556UQ                      | [54473bca57](https://linux-hardware.org/?probe=54473bca57) | May 20, 2024 |
| MSI           | Cyborg 15 A12VF             | [4301eba9f0](https://linux-hardware.org/?probe=4301eba9f0) | May 17, 2024 |
| ASUSTek       | K53E                        | [2c14a21fe8](https://linux-hardware.org/?probe=2c14a21fe8) | May 02, 2024 |
| Acer          | Aspire E5-771G              | [752982118a](https://linux-hardware.org/?probe=752982118a) | Apr 09, 2024 |
| ASUSTek       | X553MA                      | [3e60ae1de4](https://linux-hardware.org/?probe=3e60ae1de4) | Apr 08, 2024 |
| Maibenben     | MaiBook X series            | [44a21e3fc3](https://linux-hardware.org/?probe=44a21e3fc3) | Apr 05, 2024 |
| ASUSTek       | K53E                        | [0564fa09ec](https://linux-hardware.org/?probe=0564fa09ec) | Apr 05, 2024 |
| Lenovo        | ThinkPad T470 20HD0001MH    | [5999aa3b46](https://linux-hardware.org/?probe=5999aa3b46) | Mar 26, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [33164bcce1](https://linux-hardware.org/?probe=33164bcce1) | Mar 14, 2024 |
| Fujitsu       | LIFEBOOK E554               | [cdc8c121ad](https://linux-hardware.org/?probe=cdc8c121ad) | Mar 09, 2024 |
| Dell          | Inspiron 5567               | [0304104a60](https://linux-hardware.org/?probe=0304104a60) | Mar 03, 2024 |
| Apple         | MacBookPro9,2               | [336cabac77](https://linux-hardware.org/?probe=336cabac77) | Mar 02, 2024 |
| Dell          | Inspiron 5559               | [f4f2d5a42e](https://linux-hardware.org/?probe=f4f2d5a42e) | Feb 28, 2024 |
| Dell          | Inspiron 5559               | [a8565459dd](https://linux-hardware.org/?probe=a8565459dd) | Feb 28, 2024 |
| Dell          | Inspiron 5567               | [9a57de6e15](https://linux-hardware.org/?probe=9a57de6e15) | Feb 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [46c0e99842](https://linux-hardware.org/?probe=46c0e99842) | Feb 27, 2024 |
| Apple         | MacBookPro9,2               | [7167de20ce](https://linux-hardware.org/?probe=7167de20ce) | Feb 27, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [40fbd1acd6](https://linux-hardware.org/?probe=40fbd1acd6) | Feb 06, 2024 |
| Fujitsu       | LIFEBOOK E554               | [ce905760f2](https://linux-hardware.org/?probe=ce905760f2) | Jan 31, 2024 |
| Apple         | MacBook5,1                  | [0833d2c5c5](https://linux-hardware.org/?probe=0833d2c5c5) | Jan 22, 2024 |
| HP            | ZBook 15 G2                 | [cb33073a09](https://linux-hardware.org/?probe=cb33073a09) | Jan 15, 2024 |
| MSI           | PRO H610M-B DDR4            | [fa4ed3c75c](https://linux-hardware.org/?probe=fa4ed3c75c) | Jan 10, 2024 |
| HP            | Pavilion dv6                | [39515c70db](https://linux-hardware.org/?probe=39515c70db) | Dec 27, 2023 |
| HP            | Pavilion dv6                | [c29956a752](https://linux-hardware.org/?probe=c29956a752) | Dec 27, 2023 |
| HP            | Pavilion g6                 | [62a002d063](https://linux-hardware.org/?probe=62a002d063) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5a16e00d6c](https://linux-hardware.org/?probe=5a16e00d6c) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [262bfe0585](https://linux-hardware.org/?probe=262bfe0585) | Dec 14, 2023 |
| HP            | ZBook 15 G2                 | [f60bc8a984](https://linux-hardware.org/?probe=f60bc8a984) | Dec 03, 2023 |
| Dell          | Inspiron 7720               | [ec97e6b200](https://linux-hardware.org/?probe=ec97e6b200) | Dec 02, 2023 |
| Lenovo        | G580 20157                  | [f03f814b9c](https://linux-hardware.org/?probe=f03f814b9c) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [aaccb61f12](https://linux-hardware.org/?probe=aaccb61f12) | Nov 24, 2023 |
| ASUSTek       | M50Vn                       | [9c35898e36](https://linux-hardware.org/?probe=9c35898e36) | Nov 16, 2023 |
| HP            | Mini 110-4100               | [a7aaa77ba5](https://linux-hardware.org/?probe=a7aaa77ba5) | Nov 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3281df4dcd](https://linux-hardware.org/?probe=3281df4dcd) | Nov 15, 2023 |
| Acer          | Extensa 5620                | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| Fujitsu       | LIFEBOOK E554               | [f212dcca29](https://linux-hardware.org/?probe=f212dcca29) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c7d2d860fb](https://linux-hardware.org/?probe=c7d2d860fb) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [6e619afdba](https://linux-hardware.org/?probe=6e619afdba) | Oct 30, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [a368ef3766](https://linux-hardware.org/?probe=a368ef3766) | Oct 22, 2023 |
| Samsung       | R530/R730/P530              | [ba506f75d1](https://linux-hardware.org/?probe=ba506f75d1) | Oct 21, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [6bd80595bd](https://linux-hardware.org/?probe=6bd80595bd) | Oct 19, 2023 |
| HP            | EliteBook 2760p             | [3d62b547f3](https://linux-hardware.org/?probe=3d62b547f3) | Oct 16, 2023 |
| Lenovo        | ThinkPad T450 20BUS0H200    | [c38151f281](https://linux-hardware.org/?probe=c38151f281) | Sep 20, 2023 |
| Dell          | Vostro 3400                 | [faddcc51a7](https://linux-hardware.org/?probe=faddcc51a7) | Sep 17, 2023 |
| LIVEFAN       | Unknown                     | [102a13c2c5](https://linux-hardware.org/?probe=102a13c2c5) | Sep 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [820eeccddf](https://linux-hardware.org/?probe=820eeccddf) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8b6b039242](https://linux-hardware.org/?probe=8b6b039242) | Sep 10, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [0309bcca29](https://linux-hardware.org/?probe=0309bcca29) | Sep 05, 2023 |
| MSI           | Delta 15 A5EFK              | [8d2e359aec](https://linux-hardware.org/?probe=8d2e359aec) | Sep 03, 2023 |
| Acer          | Aspire 5750G                | [009242b925](https://linux-hardware.org/?probe=009242b925) | Aug 13, 2023 |
| HP            | Presario CQ57               | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| Acer          | Aspire xxxx                 | [8bc8edb11c](https://linux-hardware.org/?probe=8bc8edb11c) | Aug 03, 2023 |
| Dell          | G5 5590                     | [2745b35776](https://linux-hardware.org/?probe=2745b35776) | Jul 29, 2023 |
| MSI           | Alpha 15 B5EEK              | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| Dell          | Latitude E7250              | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [2f730cccf1](https://linux-hardware.org/?probe=2f730cccf1) | Jul 18, 2023 |
| Alienware     | 17                          | [90e6911a60](https://linux-hardware.org/?probe=90e6911a60) | Jul 09, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [0b81f2e9b0](https://linux-hardware.org/?probe=0b81f2e9b0) | Jul 07, 2023 |
| Acer          | Aspire 5750G                | [d487f9f635](https://linux-hardware.org/?probe=d487f9f635) | Jul 05, 2023 |
| Valve         | Jupiter                     | [d62c8c81d4](https://linux-hardware.org/?probe=d62c8c81d4) | Jul 04, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [97b1fc630a](https://linux-hardware.org/?probe=97b1fc630a) | Jun 25, 2023 |
| ASUSTek       | G50V                        | [32048be4b5](https://linux-hardware.org/?probe=32048be4b5) | Jun 16, 2023 |
| Unknown       | Unknown                     | [c5accf4cf8](https://linux-hardware.org/?probe=c5accf4cf8) | Jun 09, 2023 |
| Unknown       | Unknown                     | [45e51a6b5d](https://linux-hardware.org/?probe=45e51a6b5d) | Jun 09, 2023 |
| Acer          | Aspire ES1-711              | [79bb8d8e39](https://linux-hardware.org/?probe=79bb8d8e39) | Jun 08, 2023 |
| HP            | Laptop 15-bs0xx             | [ea2d944708](https://linux-hardware.org/?probe=ea2d944708) | Jun 01, 2023 |
| Acer          | Aspire A315-58              | [f9995cb422](https://linux-hardware.org/?probe=f9995cb422) | May 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [230a02bfda](https://linux-hardware.org/?probe=230a02bfda) | May 29, 2023 |
| MSI           | Bravo 15 A4DDR              | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [767c697ac8](https://linux-hardware.org/?probe=767c697ac8) | May 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3f7beed595](https://linux-hardware.org/?probe=3f7beed595) | May 25, 2023 |
| Dell          | Inspiron 15-3552            | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fff0e981f2](https://linux-hardware.org/?probe=fff0e981f2) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8933c29ce](https://linux-hardware.org/?probe=b8933c29ce) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HUAWEI        | MRGF-XX                     | [25233eb8d1](https://linux-hardware.org/?probe=25233eb8d1) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [517662dd54](https://linux-hardware.org/?probe=517662dd54) | Apr 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [083aef9e64](https://linux-hardware.org/?probe=083aef9e64) | Apr 20, 2023 |
| Dell          | Inspiron 7720               | [27df270817](https://linux-hardware.org/?probe=27df270817) | Apr 09, 2023 |
| Lenovo        | ThinkPad W530 243852U       | [ea2ee391a5](https://linux-hardware.org/?probe=ea2ee391a5) | Apr 07, 2023 |
| Lenovo        | ThinkPad E470 20H1006VRT    | [a9b909f3df](https://linux-hardware.org/?probe=a9b909f3df) | Apr 05, 2023 |
| Notebook      | L140CU                      | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Notebook      | L140CU                      | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| ASUSTek       | T100HAN                     | [c1f3b9658c](https://linux-hardware.org/?probe=c1f3b9658c) | Mar 26, 2023 |
| ASUSTek       | T100HAN                     | [3f74c992e7](https://linux-hardware.org/?probe=3f74c992e7) | Mar 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [ba879b76da](https://linux-hardware.org/?probe=ba879b76da) | Mar 19, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [547559d982](https://linux-hardware.org/?probe=547559d982) | Mar 19, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| ASUSTek       | N550JK                      | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| MSI           | GT72 2PE                    | [0483315836](https://linux-hardware.org/?probe=0483315836) | Mar 16, 2023 |
| ASUSTek       | N61Jq                       | [706eca5e8a](https://linux-hardware.org/?probe=706eca5e8a) | Mar 15, 2023 |
| ASUSTek       | T100HAN                     | [b4046bce15](https://linux-hardware.org/?probe=b4046bce15) | Mar 10, 2023 |
| HP            | Compaq Presario CQ60        | [cbdc8bcd6a](https://linux-hardware.org/?probe=cbdc8bcd6a) | Mar 06, 2023 |
| MSI           | GS66 Stealth 10UE           | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI           | GS66 Stealth 10UE           | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP            | EliteBook 2540p             | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Apple         | MacBookPro11,5              | [7933746ce1](https://linux-hardware.org/?probe=7933746ce1) | Feb 17, 2023 |
| MSI           | GS66 Stealth 10UE           | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [8ba717ec45](https://linux-hardware.org/?probe=8ba717ec45) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| HP            | EliteBook 2540p             | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [a3a0a3a505](https://linux-hardware.org/?probe=a3a0a3a505) | Jan 25, 2023 |
| ASUSTek       | GL552VX                     | [d196ac82e2](https://linux-hardware.org/?probe=d196ac82e2) | Jan 23, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| MSI           | GP70 2PE                    | [697974aa68](https://linux-hardware.org/?probe=697974aa68) | Jan 08, 2023 |
| HP            | ProBook 450 G0              | [e7af660f1a](https://linux-hardware.org/?probe=e7af660f1a) | Jan 05, 2023 |
| HP            | 250 G7 Notebook PC          | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7a6ba7238f](https://linux-hardware.org/?probe=7a6ba7238f) | Dec 08, 2022 |
| Dell          | Vostro 5502                 | [862097a47c](https://linux-hardware.org/?probe=862097a47c) | Dec 05, 2022 |
| ASUSTek       | X550CL                      | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| HP            | EliteBook 8470p             | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| HP            | EliteBook 8470p             | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| Acer          | Aspire 5750G                | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| Dell          | G3 3579                     | [2191706dd0](https://linux-hardware.org/?probe=2191706dd0) | Oct 11, 2022 |
| Dell          | G3 3579                     | [7f20851840](https://linux-hardware.org/?probe=7f20851840) | Oct 10, 2022 |
| HP            | EliteBook 850 G3            | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| ASUSTek       | X540LA                      | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| HP            | ProBook 440 G3              | [e51d4ae241](https://linux-hardware.org/?probe=e51d4ae241) | Aug 20, 2022 |
| Lenovo        | ThinkPad T590 20N4004EMH    | [42d130e184](https://linux-hardware.org/?probe=42d130e184) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| MSI           | MS-16F1                     | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [f3a7c88015](https://linux-hardware.org/?probe=f3a7c88015) | Aug 11, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| HP            | Compaq Presario CQ60        | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| eMachines     | eME443                      | [9197e8ef17](https://linux-hardware.org/?probe=9197e8ef17) | Jul 11, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f23b75e3ca](https://linux-hardware.org/?probe=f23b75e3ca) | Jun 19, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [8f2740e70e](https://linux-hardware.org/?probe=8f2740e70e) | Jun 18, 2022 |
| Panasonic     | CF-52VDA131M                | [aa40370193](https://linux-hardware.org/?probe=aa40370193) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| Dell          | Latitude E5570              | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| Alienware     | 17                          | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [3e171a4858](https://linux-hardware.org/?probe=3e171a4858) | May 09, 2022 |
| Lenovo        | G500 20236                  | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| Dell          | XPS 15 9510                 | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Dell          | Latitude 5401               | [d115db916d](https://linux-hardware.org/?probe=d115db916d) | Apr 23, 2022 |
| Dell          | Latitude 5401               | [c9f380ea26](https://linux-hardware.org/?probe=c9f380ea26) | Apr 23, 2022 |
| ASUSTek       | X55A                        | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| Dell          | Vostro 3580                 | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| ASUSTek       | X55A                        | [9b02d587bf](https://linux-hardware.org/?probe=9b02d587bf) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5d0113f42d](https://linux-hardware.org/?probe=5d0113f42d) | Mar 16, 2022 |
| HP            | ProBook 455 G1              | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [12a1b54a3a](https://linux-hardware.org/?probe=12a1b54a3a) | Feb 16, 2022 |
| ASUSTek       | X55A                        | [dbbb7b1213](https://linux-hardware.org/?probe=dbbb7b1213) | Feb 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a7d1f29451](https://linux-hardware.org/?probe=a7d1f29451) | Jan 31, 2022 |
| Jumper        | EZbook                      | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| HP            | ProBook 450 G1              | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Lenovo        | Flex 2-15 20405             | [8f6a587ed3](https://linux-hardware.org/?probe=8f6a587ed3) | Jan 20, 2022 |
| ASUSTek       | N53SV                       | [a5b43fd8b4](https://linux-hardware.org/?probe=a5b43fd8b4) | Jan 05, 2022 |
| HP            | Laptop 14s-fq1xxx           | [8e0b4fec6c](https://linux-hardware.org/?probe=8e0b4fec6c) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | [113924cdba](https://linux-hardware.org/?probe=113924cdba) | Dec 12, 2021 |
| ASUSTek       | N53SV                       | [557bb216fc](https://linux-hardware.org/?probe=557bb216fc) | Nov 20, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [3119a05196](https://linux-hardware.org/?probe=3119a05196) | Nov 15, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [b455b4457c](https://linux-hardware.org/?probe=b455b4457c) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| ASUSTek       | X55A                        | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| ASUSTek       | K52F                        | [f90cbb4d26](https://linux-hardware.org/?probe=f90cbb4d26) | Nov 04, 2021 |
| ASUSTek       | N73SV                       | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| HUAWEI        | MACHD-WXX9                  | [1876547e8e](https://linux-hardware.org/?probe=1876547e8e) | Oct 25, 2021 |
| HUAWEI        | MACHD-WXX9                  | [078863a9b7](https://linux-hardware.org/?probe=078863a9b7) | Oct 25, 2021 |
| Toshiba       | Satellite C50D-A-13G        | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| Dell          | Inspiron 15-3567            | [5db12e2534](https://linux-hardware.org/?probe=5db12e2534) | Oct 02, 2021 |
| Alienware     | 17                          | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | XPS 15 9500                 | [239dced9a1](https://linux-hardware.org/?probe=239dced9a1) | Sep 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | [4db5d51b06](https://linux-hardware.org/?probe=4db5d51b06) | Sep 17, 2021 |
| HP            | 250 G4                      | [6c66581e62](https://linux-hardware.org/?probe=6c66581e62) | Sep 06, 2021 |
| HP            | 250 G4                      | [619fff9116](https://linux-hardware.org/?probe=619fff9116) | Sep 04, 2021 |
| ASUSTek       | X551CAP                     | [626023b280](https://linux-hardware.org/?probe=626023b280) | Aug 24, 2021 |
| ASUSTek       | X551CAP                     | [9e64453373](https://linux-hardware.org/?probe=9e64453373) | Aug 23, 2021 |
| Acer          | Aspire 5750G                | [c358dfd2e6](https://linux-hardware.org/?probe=c358dfd2e6) | Aug 18, 2021 |
| HP            | Pavilion dv7                | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5d33b12497](https://linux-hardware.org/?probe=5d33b12497) | Aug 13, 2021 |
| HP            | EliteBook 8440p             | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | 250 G4                      | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4752d9cb90](https://linux-hardware.org/?probe=4752d9cb90) | Aug 01, 2021 |
| Alienware     | 17                          | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [45b678cc45](https://linux-hardware.org/?probe=45b678cc45) | Jun 07, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [dab115ff9f](https://linux-hardware.org/?probe=dab115ff9f) | Jun 07, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [63b5d9a81a](https://linux-hardware.org/?probe=63b5d9a81a) | Jun 05, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [56308999d2](https://linux-hardware.org/?probe=56308999d2) | Jun 05, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [20b885e70c](https://linux-hardware.org/?probe=20b885e70c) | Jun 01, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [74979cf76a](https://linux-hardware.org/?probe=74979cf76a) | Jun 01, 2021 |
| ASUSTek       | K52F                        | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| Dell          | Precision M4700             | [1d14e22fbd](https://linux-hardware.org/?probe=1d14e22fbd) | May 22, 2021 |
| Dell          | Inspiron 5579               | [83c30b9084](https://linux-hardware.org/?probe=83c30b9084) | May 15, 2021 |
| ASUSTek       | UX430UAR                    | [84b8a6331d](https://linux-hardware.org/?probe=84b8a6331d) | May 08, 2021 |
| Unknown       | Unknown                     | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Unknown       | Unknown                     | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [49aad4b320](https://linux-hardware.org/?probe=49aad4b320) | May 04, 2021 |
| Lenovo        | ThinkPad P53 20QN0034MH     | [bcb2272cf0](https://linux-hardware.org/?probe=bcb2272cf0) | Apr 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [26133ce35a](https://linux-hardware.org/?probe=26133ce35a) | Apr 24, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [1e30c2850c](https://linux-hardware.org/?probe=1e30c2850c) | Apr 09, 2021 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [faca4e4038](https://linux-hardware.org/?probe=faca4e4038) | Apr 08, 2021 |
| Acer          | Aspire A515-56              | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| ASUSTek       | K50C                        | [4ccd0463c4](https://linux-hardware.org/?probe=4ccd0463c4) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480 20L50002MH    | [554173e0d7](https://linux-hardware.org/?probe=554173e0d7) | Mar 17, 2021 |
| ASUSTek       | K50C                        | [65941d7354](https://linux-hardware.org/?probe=65941d7354) | Mar 17, 2021 |
| Dell          | Latitude E5530 non-vPro     | [530ac66726](https://linux-hardware.org/?probe=530ac66726) | Mar 17, 2021 |
| Dell          | Latitude 7380               | [43510cebc1](https://linux-hardware.org/?probe=43510cebc1) | Mar 13, 2021 |
| Lenovo        | ThinkPad W530 243852U       | [15c953bc70](https://linux-hardware.org/?probe=15c953bc70) | Mar 09, 2021 |
| Dell          | Inspiron 5758               | [f371afba83](https://linux-hardware.org/?probe=f371afba83) | Feb 27, 2021 |
| Dell          | Inspiron 5570               | [d36796da44](https://linux-hardware.org/?probe=d36796da44) | Feb 27, 2021 |
| Lenovo        | ThinkPad T430 2347EV8       | [3bf5967320](https://linux-hardware.org/?probe=3bf5967320) | Feb 19, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a398ccbc3d](https://linux-hardware.org/?probe=a398ccbc3d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XN0... | [f25ec6b2f3](https://linux-hardware.org/?probe=f25ec6b2f3) | Jan 31, 2021 |
| Acer          | Extensa 5220                | [20ea0cd55c](https://linux-hardware.org/?probe=20ea0cd55c) | Jan 23, 2021 |
| Acer          | Extensa 5220                | [9fe95abf63](https://linux-hardware.org/?probe=9fe95abf63) | Jan 23, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [b7b3175352](https://linux-hardware.org/?probe=b7b3175352) | Jan 14, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ed7d9bff15](https://linux-hardware.org/?probe=ed7d9bff15) | Jan 13, 2021 |
| Acer          | Aspire 5750G                | [91885a7829](https://linux-hardware.org/?probe=91885a7829) | Jan 05, 2021 |
| Acer          | Aspire 5750G                | [34198a369d](https://linux-hardware.org/?probe=34198a369d) | Dec 26, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | [f4ab3e4295](https://linux-hardware.org/?probe=f4ab3e4295) | Dec 26, 2020 |
| Acer          | Aspire 1410                 | [3ff80e7b33](https://linux-hardware.org/?probe=3ff80e7b33) | Dec 26, 2020 |
| ASUSTek       | X510UNR                     | [44990d7fc0](https://linux-hardware.org/?probe=44990d7fc0) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [e6e91c5ea2](https://linux-hardware.org/?probe=e6e91c5ea2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [5b56323f14](https://linux-hardware.org/?probe=5b56323f14) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [2c7c774492](https://linux-hardware.org/?probe=2c7c774492) | Dec 15, 2020 |
| Toshiba       | Satellite L855              | [48d0f1a04c](https://linux-hardware.org/?probe=48d0f1a04c) | Dec 08, 2020 |
| Dell          | Latitude E7470              | [3c76403f27](https://linux-hardware.org/?probe=3c76403f27) | Dec 01, 2020 |
| Packard Be... | EasyNote TE11HC             | [a58e43a971](https://linux-hardware.org/?probe=a58e43a971) | Nov 20, 2020 |
| Packard Be... | EasyNote TE11HC             | [374504e0bd](https://linux-hardware.org/?probe=374504e0bd) | Nov 20, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [1310e54c33](https://linux-hardware.org/?probe=1310e54c33) | Nov 20, 2020 |
| ASUSTek       | X510UNR                     | [fb41abdfb1](https://linux-hardware.org/?probe=fb41abdfb1) | Nov 13, 2020 |
| Alienware     | 17                          | [59fdbdd4d7](https://linux-hardware.org/?probe=59fdbdd4d7) | Nov 11, 2020 |
| ASUSTek       | GL553VD                     | [86837daf1c](https://linux-hardware.org/?probe=86837daf1c) | Nov 10, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cf2cbcbe72](https://linux-hardware.org/?probe=cf2cbcbe72) | Nov 05, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [39dcf2485b](https://linux-hardware.org/?probe=39dcf2485b) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1b2dd49d08](https://linux-hardware.org/?probe=1b2dd49d08) | Oct 20, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [b3e5017b13](https://linux-hardware.org/?probe=b3e5017b13) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | [09fbf70f49](https://linux-hardware.org/?probe=09fbf70f49) | Oct 16, 2020 |
| HP            | ProBook 450 G1              | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| Dell          | G5 5587                     | [ba6fbeb10c](https://linux-hardware.org/?probe=ba6fbeb10c) | Oct 09, 2020 |
| Dell          | G5 5587                     | [8b28232f32](https://linux-hardware.org/?probe=8b28232f32) | Oct 09, 2020 |
| HP            | ProBook 4720s               | [a882fdd653](https://linux-hardware.org/?probe=a882fdd653) | Oct 02, 2020 |
| ASUSTek       | N56VZ                       | [d4d74a6e34](https://linux-hardware.org/?probe=d4d74a6e34) | Sep 29, 2020 |
| ASUSTek       | K52JT                       | [2acb54cb0d](https://linux-hardware.org/?probe=2acb54cb0d) | Sep 28, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [87092c4768](https://linux-hardware.org/?probe=87092c4768) | Sep 21, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [48825acdce](https://linux-hardware.org/?probe=48825acdce) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| HP            | ProBook 450 G6              | [6fffc9928f](https://linux-hardware.org/?probe=6fffc9928f) | Sep 10, 2020 |
| HP            | ProBook 450 G6              | [7465caa486](https://linux-hardware.org/?probe=7465caa486) | Sep 10, 2020 |
| Lenovo        | ThinkPad T460s 20F90058M... | [352f3932b4](https://linux-hardware.org/?probe=352f3932b4) | Sep 09, 2020 |
| Dell          | Latitude 5491               | [06d4120fc1](https://linux-hardware.org/?probe=06d4120fc1) | Sep 08, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| Timi          | TM1701                      | [4c01fca357](https://linux-hardware.org/?probe=4c01fca357) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| Dell          | XPS M1330                   | [4a907eebb9](https://linux-hardware.org/?probe=4a907eebb9) | Aug 02, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [a52cd7499e](https://linux-hardware.org/?probe=a52cd7499e) | Jul 28, 2020 |
| Acer          | Swift SF314-54G             | [a4948f0d33](https://linux-hardware.org/?probe=a4948f0d33) | Jul 24, 2020 |
| Acer          | Swift SF314-54G             | [cd250d0e7b](https://linux-hardware.org/?probe=cd250d0e7b) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| HP            | Pavilion dv6                | [4c09684767](https://linux-hardware.org/?probe=4c09684767) | Jul 23, 2020 |
| ASUSTek       | N71Ja                       | [db78759a1a](https://linux-hardware.org/?probe=db78759a1a) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [0fb6ac937d](https://linux-hardware.org/?probe=0fb6ac937d) | Jul 06, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [fc16d36603](https://linux-hardware.org/?probe=fc16d36603) | Jul 03, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [9c1c6b6919](https://linux-hardware.org/?probe=9c1c6b6919) | Jun 30, 2020 |
| Dell          | XPS 15 7590                 | [78351d2937](https://linux-hardware.org/?probe=78351d2937) | Jun 22, 2020 |
| Lenovo        | ThinkPad L460 20FU0007MH    | [27a87ca264](https://linux-hardware.org/?probe=27a87ca264) | Jun 18, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [9c0419884f](https://linux-hardware.org/?probe=9c0419884f) | Jun 17, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | [ed27c7aa81](https://linux-hardware.org/?probe=ed27c7aa81) | Jun 10, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | [574368a188](https://linux-hardware.org/?probe=574368a188) | Jun 09, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [ebac9eaefe](https://linux-hardware.org/?probe=ebac9eaefe) | Jun 02, 2020 |
| HP            | EliteBook 8440p             | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | Y50-70 20378                | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| Dell          | Inspiron 1520               | [368e9f53e5](https://linux-hardware.org/?probe=368e9f53e5) | May 22, 2020 |
| Samsung       | RC530/RC730                 | [7e180f5fd2](https://linux-hardware.org/?probe=7e180f5fd2) | May 21, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [04ed3686b1](https://linux-hardware.org/?probe=04ed3686b1) | May 19, 2020 |
| ASUSTek       | X51RL                       | [afee28a69b](https://linux-hardware.org/?probe=afee28a69b) | May 16, 2020 |
| HP            | EliteBook 8440p             | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Lenovo        | ThinkPad Edge E320 12985... | [e4a1ece1ec](https://linux-hardware.org/?probe=e4a1ece1ec) | Apr 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [70daf3ad77](https://linux-hardware.org/?probe=70daf3ad77) | Apr 20, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [c4b061e0f5](https://linux-hardware.org/?probe=c4b061e0f5) | Apr 19, 2020 |
| Lenovo        | V130-15IGM 81HL             | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| ASUSTek       | M50SA                       | [a7381b478e](https://linux-hardware.org/?probe=a7381b478e) | Apr 10, 2020 |
| Dell          | Inspiron 3542               | [38086a42be](https://linux-hardware.org/?probe=38086a42be) | Apr 01, 2020 |
| Dell          | Inspiron 3542               | [2246b94acb](https://linux-hardware.org/?probe=2246b94acb) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | [0552ab024f](https://linux-hardware.org/?probe=0552ab024f) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | [0fd03337ad](https://linux-hardware.org/?probe=0fd03337ad) | Mar 29, 2020 |
| Acer          | Aspire 5733                 | [055f9887c3](https://linux-hardware.org/?probe=055f9887c3) | Mar 29, 2020 |
| Lenovo        | G550 20023                  | [0e9b1fb324](https://linux-hardware.org/?probe=0e9b1fb324) | Mar 29, 2020 |
| HP            | 630                         | [fc76abe01b](https://linux-hardware.org/?probe=fc76abe01b) | Mar 29, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [23a0bdb230](https://linux-hardware.org/?probe=23a0bdb230) | Mar 19, 2020 |
| ASUSTek       | K43E                        | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| ASUSTek       | K53E                        | [8729f56cdc](https://linux-hardware.org/?probe=8729f56cdc) | Mar 07, 2020 |
| ASUSTek       | K53SV                       | [3b537b4a10](https://linux-hardware.org/?probe=3b537b4a10) | Mar 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f08088a64d](https://linux-hardware.org/?probe=f08088a64d) | Feb 20, 2020 |
| HP            | ProBook 4740s               | [4d4d26ef02](https://linux-hardware.org/?probe=4d4d26ef02) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB0065MH    | [e895371f73](https://linux-hardware.org/?probe=e895371f73) | Feb 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [226b976601](https://linux-hardware.org/?probe=226b976601) | Jan 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6973864306](https://linux-hardware.org/?probe=6973864306) | Jan 25, 2020 |
| Acer          | Aspire V3-772               | [17005306cd](https://linux-hardware.org/?probe=17005306cd) | Jan 24, 2020 |
| ASUSTek       | K52JT                       | [4335a97dd6](https://linux-hardware.org/?probe=4335a97dd6) | Jan 24, 2020 |
| Dell          | G3 3579                     | [56f84db06b](https://linux-hardware.org/?probe=56f84db06b) | Jan 22, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [f22d44d39f](https://linux-hardware.org/?probe=f22d44d39f) | Jan 22, 2020 |
| Panasonic     | CF-52WEBBYDE                | [0d21ee7063](https://linux-hardware.org/?probe=0d21ee7063) | Jan 17, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [cf8ada0ad0](https://linux-hardware.org/?probe=cf8ada0ad0) | Jan 16, 2020 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [f57bc0120b](https://linux-hardware.org/?probe=f57bc0120b) | Jan 15, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | [4ea8d503ae](https://linux-hardware.org/?probe=4ea8d503ae) | Dec 13, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | [a298251c28](https://linux-hardware.org/?probe=a298251c28) | Dec 13, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 856               | [80cf2af707](https://linux-hardware.org/?probe=80cf2af707) | Nov 22, 2019 |
| HP            | Pavilion dv6                | [6f6270eb8e](https://linux-hardware.org/?probe=6f6270eb8e) | Nov 16, 2019 |
| HP            | Pavilion dv6                | [c08e4bac64](https://linux-hardware.org/?probe=c08e4bac64) | Nov 16, 2019 |
| HP            | EliteBook 8460p             | [56a12d5f20](https://linux-hardware.org/?probe=56a12d5f20) | Nov 09, 2019 |
| Acer          | AOD260                      | [a911172500](https://linux-hardware.org/?probe=a911172500) | Nov 09, 2019 |
| Sony          | VGN-C260E                   | [c623de88ee](https://linux-hardware.org/?probe=c623de88ee) | Oct 24, 2019 |
| Lenovo        | G505s 20255                 | [36deb3b32d](https://linux-hardware.org/?probe=36deb3b32d) | Oct 13, 2019 |
| HP            | Pavilion dv6                | [c2264e7abd](https://linux-hardware.org/?probe=c2264e7abd) | Oct 11, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [77b1afae40](https://linux-hardware.org/?probe=77b1afae40) | Oct 09, 2019 |
| ASUSTek       | K53SV                       | [61f7ec13d8](https://linux-hardware.org/?probe=61f7ec13d8) | Sep 19, 2019 |
| ASUSTek       | K53E                        | [71fd2610fe](https://linux-hardware.org/?probe=71fd2610fe) | Sep 15, 2019 |
| ASUSTek       | K53E                        | [e435064ad7](https://linux-hardware.org/?probe=e435064ad7) | Sep 15, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [3baafefb84](https://linux-hardware.org/?probe=3baafefb84) | Aug 27, 2019 |
| Prestigio     | PSB141C02                   | [3e96d56c17](https://linux-hardware.org/?probe=3e96d56c17) | Aug 25, 2019 |
| ASUSTek       | K53E                        | [c1811b7ec3](https://linux-hardware.org/?probe=c1811b7ec3) | Aug 23, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [15419d9561](https://linux-hardware.org/?probe=15419d9561) | Aug 20, 2019 |
| HP            | Laptop 15-bw0xx             | [7653d7fa4d](https://linux-hardware.org/?probe=7653d7fa4d) | Jul 29, 2019 |
| Lenovo        | G550 20023                  | [601d53f9eb](https://linux-hardware.org/?probe=601d53f9eb) | Jul 23, 2019 |
| Lenovo        | ThinkPad R500 27327KG       | [c8b31c9d99](https://linux-hardware.org/?probe=c8b31c9d99) | Jun 04, 2019 |
| Dell          | Inspiron N5010              | [23d8e1dd30](https://linux-hardware.org/?probe=23d8e1dd30) | May 31, 2019 |
| Acer          | TravelMate 5740G            | [0d4611c952](https://linux-hardware.org/?probe=0d4611c952) | May 25, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [be887070fe](https://linux-hardware.org/?probe=be887070fe) | May 17, 2019 |
| Toshiba       | Satellite C50D-A-13G        | [c39268dff8](https://linux-hardware.org/?probe=c39268dff8) | May 13, 2019 |
| Toshiba       | Satellite C50D-A-13G        | [e0d133befc](https://linux-hardware.org/?probe=e0d133befc) | May 13, 2019 |
| HP            | ProBook 6555b               | [598fc6c1ca](https://linux-hardware.org/?probe=598fc6c1ca) | May 13, 2019 |
| HP            | ProBook 4540s               | [2e61bfe1be](https://linux-hardware.org/?probe=2e61bfe1be) | Apr 28, 2019 |
| HP            | ProBook 4540s               | [8d460232a9](https://linux-hardware.org/?probe=8d460232a9) | Apr 28, 2019 |
| Dell          | Inspiron 5737               | [2c7d308e3a](https://linux-hardware.org/?probe=2c7d308e3a) | Apr 26, 2019 |
| Dell          | Inspiron 5737               | [dcf03f780e](https://linux-hardware.org/?probe=dcf03f780e) | Apr 26, 2019 |
| Acer          | TravelMate 5740G            | [6b69828c13](https://linux-hardware.org/?probe=6b69828c13) | Apr 07, 2019 |
| Sony          | VPCZ1390S                   | [eb4e58c4d9](https://linux-hardware.org/?probe=eb4e58c4d9) | Mar 05, 2019 |
| Sony          | VPCZ1390S                   | [8995c67e48](https://linux-hardware.org/?probe=8995c67e48) | Mar 05, 2019 |
| Lenovo        | ThinkPad X230 2325AEG       | [2b8bcfe576](https://linux-hardware.org/?probe=2b8bcfe576) | Feb 19, 2019 |
| ASUSTek       | X550LB                      | [992697103b](https://linux-hardware.org/?probe=992697103b) | Jan 18, 2019 |
| ASUSTek       | X550LB                      | [5228ac3dbc](https://linux-hardware.org/?probe=5228ac3dbc) | Jan 18, 2019 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [dffa2ed3ef](https://linux-hardware.org/?probe=dffa2ed3ef) | Dec 20, 2018 |
| Lenovo        | ThinkPad L440 20ASA10P00    | [e192353344](https://linux-hardware.org/?probe=e192353344) | Dec 20, 2018 |
| Lenovo        | G550 20023                  | [54fd0e13d2](https://linux-hardware.org/?probe=54fd0e13d2) | Oct 29, 2018 |
| Lenovo        | G550 20023                  | [3011864d4b](https://linux-hardware.org/?probe=3011864d4b) | Oct 25, 2018 |
| ASUSTek       | K53E                        | [0e63193763](https://linux-hardware.org/?probe=0e63193763) | Oct 21, 2018 |
| ASUSTek       | K53E                        | [8a053e30bf](https://linux-hardware.org/?probe=8a053e30bf) | Sep 30, 2018 |
| ASUSTek       | K53E                        | [8e1eab57d7](https://linux-hardware.org/?probe=8e1eab57d7) | Sep 03, 2018 |
| ASUSTek       | 1225B                       | [fb333d2cde](https://linux-hardware.org/?probe=fb333d2cde) | Aug 23, 2018 |
| ASUSTek       | K53E                        | [8ebafe3965](https://linux-hardware.org/?probe=8ebafe3965) | Aug 04, 2018 |
| ASUSTek       | K53E                        | [58b632622d](https://linux-hardware.org/?probe=58b632622d) | Apr 15, 2018 |
| ASUSTek       | X555LN                      | [9760e114b0](https://linux-hardware.org/?probe=9760e114b0) | Apr 07, 2018 |
| ASUSTek       | X555LN                      | [c3f232766b](https://linux-hardware.org/?probe=c3f232766b) | Apr 07, 2018 |
| ASUSTek       | K53SV                       | [e3e865dedf](https://linux-hardware.org/?probe=e3e865dedf) | Apr 06, 2018 |
| ASUSTek       | K53SV                       | [041cd61823](https://linux-hardware.org/?probe=041cd61823) | Dec 14, 2017 |
| Acer          | Aspire 5610Z                | [c79786fae0](https://linux-hardware.org/?probe=c79786fae0) | Dec 12, 2017 |
| Dell          | Inspiron 3537               | [0cb8d57f73](https://linux-hardware.org/?probe=0cb8d57f73) | Sep 25, 2017 |
| ASUSTek       | M50Vc                       | [9224093b58](https://linux-hardware.org/?probe=9224093b58) | Aug 22, 2017 |
| ASUSTek       | K53SV                       | [366e5e884c](https://linux-hardware.org/?probe=366e5e884c) | Jun 23, 2017 |
| Lenovo        | B50-10 80QR                 | [0ba3b01a3b](https://linux-hardware.org/?probe=0ba3b01a3b) | May 17, 2017 |
| Lenovo        | B50-10 80QR                 | [0a9d97b358](https://linux-hardware.org/?probe=0a9d97b358) | Apr 11, 2017 |
| Dell          | Precision M4600             | [2a09c39637](https://linux-hardware.org/?probe=2a09c39637) | Mar 15, 2017 |
| Dell          | Precision M4600             | [c9a115e18c](https://linux-hardware.org/?probe=c9a115e18c) | Mar 15, 2017 |
| Acer          | Aspire ES1-711              | [0f7625ddc4](https://linux-hardware.org/?probe=0f7625ddc4) | Mar 10, 2017 |
| Acer          | Aspire ES1-711              | [64cea7b4eb](https://linux-hardware.org/?probe=64cea7b4eb) | Mar 10, 2017 |
| Dell          | Precision M4600             | [e851921cd7](https://linux-hardware.org/?probe=e851921cd7) | Oct 24, 2016 |
| Dell          | Latitude E6440              | [ea1b5da2e7](https://linux-hardware.org/?probe=ea1b5da2e7) | Dec 07, 2015 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Lithuania/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 26        | 6.67%   |
| Arch Rolling                 | 20        | 5.13%   |
| Ubuntu 18.04                 | 19        | 4.87%   |
| Ubuntu 22.04                 | 14        | 3.59%   |
| Debian 12                    | 9         | 2.31%   |
| OpenMandriva 4.3             | 7         | 1.79%   |
| OpenMandriva 24.07           | 6         | 1.54%   |
| Linux Mint 21.1              | 6         | 1.54%   |
| Ubuntu 24.04                 | 5         | 1.28%   |
| Ubuntu 19.04                 | 5         | 1.28%   |
| ROSA R11                     | 5         | 1.28%   |
| Pop!_OS 21.04                | 5         | 1.28%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.28%   |
| OpenMandriva 23.03           | 5         | 1.28%   |
| Kubuntu 22.04                | 5         | 1.28%   |
| ArcoLinux Rolling            | 5         | 1.28%   |
| Arch                         | 5         | 1.28%   |
| Zorin 17                     | 4         | 1.03%   |
| Zorin 16                     | 4         | 1.03%   |
| Xubuntu 20.04                | 4         | 1.03%   |
| ROSA R9                      | 4         | 1.03%   |
| ROSA R8.1                    | 4         | 1.03%   |
| ROSA R11.1                   | 4         | 1.03%   |
| ROSA R10                     | 4         | 1.03%   |
| Pop!_OS 22.04                | 4         | 1.03%   |
| Pop!_OS 20.04                | 4         | 1.03%   |
| OpenMandriva 4.2             | 4         | 1.03%   |
| OpenMandriva 23.08           | 4         | 1.03%   |
| Linux Mint 20.1              | 4         | 1.03%   |
| Linux Mint 20                | 4         | 1.03%   |
| KDE neon 22.04               | 4         | 1.03%   |
| KDE neon 20.04               | 4         | 1.03%   |
| Fedora 40                    | 4         | 1.03%   |
| Fedora 39                    | 4         | 1.03%   |
| Fedora 38                    | 4         | 1.03%   |
| Xubuntu 19.10                | 3         | 0.77%   |
| OpenMandriva 24.12           | 3         | 0.77%   |
| Linux Mint 21.3              | 3         | 0.77%   |
| Linux Mint 20.3              | 3         | 0.77%   |
| Fedora 41                    | 3         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 81        | 22.63%  |
| OpenMandriva  | 35        | 9.78%   |
| Linux Mint    | 28        | 7.82%   |
| Fedora        | 27        | 7.54%   |
| Arch          | 24        | 6.7%    |
| ROSA          | 19        | 5.31%   |
| Pop!_OS       | 17        | 4.75%   |
| Debian        | 16        | 4.47%   |
| Manjaro       | 13        | 3.63%   |
| Zorin         | 10        | 2.79%   |
| KDE neon      | 9         | 2.51%   |
| Xubuntu       | 8         | 2.23%   |
| Kubuntu       | 7         | 1.96%   |
| openSUSE      | 6         | 1.68%   |
| Lubuntu       | 5         | 1.4%    |
| Gentoo        | 5         | 1.4%    |
| ArcoLinux     | 5         | 1.4%    |
| SteamOS       | 4         | 1.12%   |
| Endless       | 4         | 1.12%   |
| Elementary    | 4         | 1.12%   |
| Ubuntu Unity  | 3         | 0.84%   |
| LMDE          | 3         | 0.84%   |
| EndeavourOS   | 3         | 0.84%   |
| Ubuntu MATE   | 2         | 0.56%   |
| RED           | 2         | 0.56%   |
| Nobara        | 2         | 0.56%   |
| Kali          | 2         | 0.56%   |
| Artix         | 2         | 0.56%   |
| Ubuntu Budgie | 1         | 0.28%   |
| Slackware     | 1         | 0.28%   |
| RHEL          | 1         | 0.28%   |
| Peppermint    | 1         | 0.28%   |
| Parrot        | 1         | 0.28%   |
| NixOS         | 1         | 0.28%   |
| MX            | 1         | 0.28%   |
| Drauger OS    | 1         | 0.28%   |
| Devuan        | 1         | 0.28%   |
| CentOS        | 1         | 0.28%   |
| Bazzite       | 1         | 0.28%   |
| Alpine        | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| 6.14.2-desktop-3omv2590                  | 5         | 1.2%    |
| 6.10.0-desktop-1omv2490                  | 5         | 1.2%    |
| 5.4.0-42-generic                         | 5         | 1.2%    |
| 5.13.0-40-generic                        | 5         | 1.2%    |
| 6.2.6-desktop-1omv2390                   | 4         | 0.96%   |
| 5.16.7-desktop-1omv4003                  | 4         | 0.96%   |
| 5.15.0-56-generic                        | 4         | 0.96%   |
| 5.10.14-desktop-1omv4002                 | 4         | 0.96%   |
| 6.6.2-desktop-1omv2390                   | 3         | 0.72%   |
| 6.4.8-desktop-2omv2390                   | 3         | 0.72%   |
| 6.12.1-desktop-1omv2490                  | 3         | 0.72%   |
| 6.1.0-10-amd64                           | 3         | 0.72%   |
| 5.4.0-48-generic                         | 3         | 0.72%   |
| 5.4.0-47-generic                         | 3         | 0.72%   |
| 5.3.0-26-generic                         | 3         | 0.72%   |
| 4.9.41-nrj-desktop-1rosa-x86_64          | 3         | 0.72%   |
| 4.15.0-91-generic                        | 3         | 0.72%   |
| 6.9.3-76060903-generic                   | 2         | 0.48%   |
| 6.8.4-200.fc39.x86_64                    | 2         | 0.48%   |
| 6.5.0-valve22-1-neptune-65-g9a338ed8a75e | 2         | 0.48%   |
| 6.3.5-desktop-3omv2390                   | 2         | 0.48%   |
| 6.2.11-300.fc38.x86_64                   | 2         | 0.48%   |
| 6.2.0-39-generic                         | 2         | 0.48%   |
| 6.2.0-35-generic                         | 2         | 0.48%   |
| 6.2.0-33-generic                         | 2         | 0.48%   |
| 6.2.0-32-generic                         | 2         | 0.48%   |
| 6.2.0-26-generic                         | 2         | 0.48%   |
| 6.14.0-37-generic                        | 2         | 0.48%   |
| 6.14.0-29-generic                        | 2         | 0.48%   |
| 6.11.0-29-generic                        | 2         | 0.48%   |
| 6.1.0-27-amd64                           | 2         | 0.48%   |
| 5.8.0-44-generic                         | 2         | 0.48%   |
| 5.8.0-14-generic                         | 2         | 0.48%   |
| 5.4.0-7634-generic                       | 2         | 0.48%   |
| 5.4.0-73-generic                         | 2         | 0.48%   |
| 5.4.0-66-generic                         | 2         | 0.48%   |
| 5.4.0-58-generic                         | 2         | 0.48%   |
| 5.4.0-52-generic                         | 2         | 0.48%   |
| 5.4.0-31-generic                         | 2         | 0.48%   |
| 5.3.0-28-generic                         | 2         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 9.82%   |
| 5.15.0  | 24        | 6.05%   |
| 4.15.0  | 20        | 5.04%   |
| 6.1.0   | 13        | 3.27%   |
| 5.3.0   | 13        | 3.27%   |
| 6.2.0   | 12        | 3.02%   |
| 6.8.0   | 11        | 2.77%   |
| 5.13.0  | 11        | 2.77%   |
| 5.8.0   | 10        | 2.52%   |
| 5.0.0   | 10        | 2.52%   |
| 6.14.0  | 6         | 1.51%   |
| 5.19.0  | 6         | 1.51%   |
| 5.11.0  | 6         | 1.51%   |
| 6.5.0   | 5         | 1.26%   |
| 6.2.6   | 5         | 1.26%   |
| 6.14.2  | 5         | 1.26%   |
| 6.11.0  | 5         | 1.26%   |
| 6.10.0  | 5         | 1.26%   |
| 5.16.7  | 5         | 1.26%   |
| 6.6.2   | 4         | 1.01%   |
| 6.12.1  | 4         | 1.01%   |
| 5.10.14 | 4         | 1.01%   |
| 5.10.0  | 4         | 1.01%   |
| 4.18.0  | 4         | 1.01%   |
| 6.4.8   | 3         | 0.76%   |
| 4.9.41  | 3         | 0.76%   |
| 6.9.3   | 2         | 0.5%    |
| 6.8.4   | 2         | 0.5%    |
| 6.8.11  | 2         | 0.5%    |
| 6.3.5   | 2         | 0.5%    |
| 6.2.7   | 2         | 0.5%    |
| 6.2.11  | 2         | 0.5%    |
| 6.17.9  | 2         | 0.5%    |
| 6.17.7  | 2         | 0.5%    |
| 6.14.4  | 2         | 0.5%    |
| 6.13.4  | 2         | 0.5%    |
| 6.12.4  | 2         | 0.5%    |
| 6.11.5  | 2         | 0.5%    |
| 6.11.4  | 2         | 0.5%    |
| 5.8.18  | 2         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 12.08%  |
| 5.15    | 33        | 8.48%   |
| 6.2     | 24        | 6.17%   |
| 6.1     | 23        | 5.91%   |
| 4.15    | 20        | 5.14%   |
| 6.8     | 18        | 4.63%   |
| 6.14    | 15        | 3.86%   |
| 5.8     | 15        | 3.86%   |
| 5.10    | 15        | 3.86%   |
| 6.12    | 13        | 3.34%   |
| 5.3     | 13        | 3.34%   |
| 5.13    | 12        | 3.08%   |
| 6.11    | 11        | 2.83%   |
| 6.10    | 11        | 2.83%   |
| 5.0     | 11        | 2.83%   |
| 4.9     | 11        | 2.83%   |
| 5.16    | 10        | 2.57%   |
| 6.6     | 8         | 2.06%   |
| 5.19    | 8         | 2.06%   |
| 5.11    | 8         | 2.06%   |
| 6.5     | 6         | 1.54%   |
| 6.4     | 6         | 1.54%   |
| 6.17    | 6         | 1.54%   |
| 6.3     | 4         | 1.03%   |
| 5.17    | 4         | 1.03%   |
| 5.12    | 4         | 1.03%   |
| 4.18    | 4         | 1.03%   |
| 6.9     | 3         | 0.77%   |
| 6.16    | 3         | 0.77%   |
| 6.13    | 3         | 0.77%   |
| 5.9     | 3         | 0.77%   |
| 4.4     | 3         | 0.77%   |
| 6.15    | 2         | 0.51%   |
| 6.0     | 2         | 0.51%   |
| 5.6     | 2         | 0.51%   |
| 4.19    | 2         | 0.51%   |
| 5.7     | 1         | 0.26%   |
| 5.18    | 1         | 0.26%   |
| 5.14    | 1         | 0.26%   |
| 4.14    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 322       | 96.12%  |
| i686    | 12        | 3.58%   |
| aarch64 | 1         | 0.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 126       | 34.81%  |
| KDE5            | 61        | 16.85%  |
| Unknown         | 32        | 8.84%   |
| XFCE            | 29        | 8.01%   |
| KDE6            | 24        | 6.63%   |
| X-Cinnamon      | 23        | 6.35%   |
| LXQt            | 14        | 3.87%   |
| KDE4            | 14        | 3.87%   |
| MATE            | 5         | 1.38%   |
| KDE             | 5         | 1.38%   |
| Unity           | 4         | 1.1%    |
| Pantheon        | 4         | 1.1%    |
| LXDE            | 3         | 0.83%   |
| Hyprland        | 3         | 0.83%   |
| GNOME Flashback | 2         | 0.55%   |
| GNOME Classic   | 2         | 0.55%   |
| dwm             | 2         | 0.55%   |
| Cinnamon        | 2         | 0.55%   |
| Budgie          | 2         | 0.55%   |
| awesome         | 2         | 0.55%   |
| Enlightenment   | 1         | 0.28%   |
| Deepin          | 1         | 0.28%   |
| COSMIC          | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 234       | 66.29%  |
| Wayland | 96        | 27.2%   |
| Unknown | 13        | 3.68%   |
| Tty     | 10        | 2.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 150       | 42.61%  |
| SDDM    | 73        | 20.74%  |
| GDM     | 40        | 11.36%  |
| LightDM | 36        | 10.23%  |
| GDM3    | 30        | 8.52%   |
| KDM     | 13        | 3.69%   |
| TDM     | 8         | 2.27%   |
| XDM     | 1         | 0.28%   |
| Ly      | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 215       | 61.6%   |
| lt_LT   | 48        | 13.75%  |
| Unknown | 39        | 11.17%  |
| ru_RU   | 18        | 5.16%   |
| en_GB   | 13        | 3.72%   |
| C       | 8         | 2.29%   |
| de_DE   | 3         | 0.86%   |
| en_AU   | 2         | 0.57%   |
| nl_NL   | 1         | 0.29%   |
| en_DK   | 1         | 0.29%   |
| be_BY   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 175       | 51.47%  |
| BIOS | 165       | 48.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 236       | 67.24%  |
| Btrfs   | 46        | 13.11%  |
| Overlay | 28        | 7.98%   |
| Tmpfs   | 17        | 4.84%   |
| Unknown | 16        | 4.56%   |
| Xfs     | 4         | 1.14%   |
| Zfs     | 2         | 0.57%   |
| ExX4    | 1         | 0.28%   |
| Ext2    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 157       | 45.38%  |
| Unknown | 155       | 44.8%   |
| MBR     | 34        | 9.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 299       | 87.17%  |
| Yes       | 44        | 12.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 264       | 77.19%  |
| Yes       | 78        | 22.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 101       | 30.33%  |
| ASUSTek Computer    | 58        | 17.42%  |
| Hewlett-Packard     | 48        | 14.41%  |
| Dell                | 47        | 14.11%  |
| Acer                | 24        | 7.21%   |
| MSI                 | 11        | 3.3%    |
| Apple               | 6         | 1.8%    |
| Samsung Electronics | 5         | 1.5%    |
| Valve               | 4         | 1.2%    |
| Toshiba             | 4         | 1.2%    |
| Fujitsu             | 3         | 0.9%    |
| Sony                | 2         | 0.6%    |
| Prestigio           | 2         | 0.6%    |
| Panasonic           | 2         | 0.6%    |
| HUAWEI              | 2         | 0.6%    |
| Unknown             | 2         | 0.6%    |
| Timi                | 1         | 0.3%    |
| Packard Bell        | 1         | 0.3%    |
| Notebook            | 1         | 0.3%    |
| LIVEFAN             | 1         | 0.3%    |
| Jumper              | 1         | 0.3%    |
| HONOR               | 1         | 0.3%    |
| Gigabyte Technology | 1         | 0.3%    |
| Fujitsu Siemens     | 1         | 0.3%    |
| Framework           | 1         | 0.3%    |
| Founder             | 1         | 0.3%    |
| eMachines           | 1         | 0.3%    |
| Alienware           | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 3         | 0.9%    |
| Lenovo Legion Y530-15ICH 81FV                         | 3         | 0.9%    |
| Unknown                                               | 3         | 0.9%    |
| Lenovo ThinkPad T490 20N3000KMH                       | 2         | 0.6%    |
| Lenovo Legion 5 15ACH6H 82JU                          | 2         | 0.6%    |
| Lenovo IdeaPad Y700-15ISK 80NV                        | 2         | 0.6%    |
| Lenovo G550 20023                                     | 2         | 0.6%    |
| HP Pavilion g6                                        | 2         | 0.6%    |
| HP Pavilion dv6                                       | 2         | 0.6%    |
| HP EliteBook 8460p                                    | 2         | 0.6%    |
| HP EliteBook 8440p                                    | 2         | 0.6%    |
| Fujitsu LIFEBOOK E554                                 | 2         | 0.6%    |
| Dell Inspiron 7720                                    | 2         | 0.6%    |
| Dell G5 5590                                          | 2         | 0.6%    |
| Dell G5 5587                                          | 2         | 0.6%    |
| ASUS X555LN                                           | 2         | 0.6%    |
| ASUS K53E                                             | 2         | 0.6%    |
| ASUS GL552VX                                          | 2         | 0.6%    |
| Apple MacBookPro9,2                                   | 2         | 0.6%    |
| Apple MacBook5,1                                      | 2         | 0.6%    |
| Acer Aspire ES1-711                                   | 2         | 0.6%    |
| Acer Aspire 5750G                                     | 2         | 0.6%    |
| Valve Galileo                                         | 1         | 0.3%    |
| Toshiba WT8-A                                         | 1         | 0.3%    |
| Toshiba Satellite L855                                | 1         | 0.3%    |
| Toshiba Satellite C55-A-1H1                           | 1         | 0.3%    |
| Toshiba Satellite C50D-A-13G                          | 1         | 0.3%    |
| Timi TM1701                                           | 1         | 0.3%    |
| Sony VPCZ1390S                                        | 1         | 0.3%    |
| Sony VGN-C260E                                        | 1         | 0.3%    |
| Samsung RC530/RC730                                   | 1         | 0.3%    |
| Samsung R530/R730/P530                                | 1         | 0.3%    |
| Samsung 950XCJ/951XCJ/950XCR                          | 1         | 0.3%    |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.3%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.3%    |
| Prestigio PSB141C03                                   | 1         | 0.3%    |
| Prestigio PSB141C02                                   | 1         | 0.3%    |
| Panasonic CF-52WEBBYDE                                | 1         | 0.3%    |
| Panasonic CF-52VDA131M                                | 1         | 0.3%    |
| Packard Bell EasyNote TE11HC                          | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 56        | 16.82%  |
| Dell Inspiron     | 17        | 5.11%   |
| Lenovo IdeaPad    | 16        | 4.8%    |
| Acer Aspire       | 16        | 4.8%    |
| HP ProBook        | 14        | 4.2%    |
| HP EliteBook      | 14        | 4.2%    |
| Dell Latitude     | 13        | 3.9%    |
| Lenovo Legion     | 11        | 3.3%    |
| ASUS VivoBook     | 7         | 2.1%    |
| ASUS ASUS         | 7         | 2.1%    |
| Dell Vostro       | 6         | 1.8%    |
| HP Laptop         | 5         | 1.5%    |
| HP Pavilion       | 4         | 1.2%    |
| Dell XPS          | 4         | 1.2%    |
| Dell G5           | 4         | 1.2%    |
| Valve Jupiter     | 3         | 0.9%    |
| Toshiba Satellite | 3         | 0.9%    |
| Fujitsu LIFEBOOK  | 3         | 0.9%    |
| ASUS ZenBook      | 3         | 0.9%    |
| ASUS TUF          | 3         | 0.9%    |
| ASUS ROG          | 3         | 0.9%    |
| Unknown           | 3         | 0.9%    |
| Lenovo Yoga       | 2         | 0.6%    |
| Lenovo LOQ        | 2         | 0.6%    |
| Lenovo G550       | 2         | 0.6%    |
| HP Compaq         | 2         | 0.6%    |
| HP 255            | 2         | 0.6%    |
| HP 250            | 2         | 0.6%    |
| Dell Precision    | 2         | 0.6%    |
| ASUS X555LN       | 2         | 0.6%    |
| ASUS K53E         | 2         | 0.6%    |
| ASUS GL552VX      | 2         | 0.6%    |
| Apple MacBookPro9 | 2         | 0.6%    |
| Apple MacBook5    | 2         | 0.6%    |
| Acer Swift        | 2         | 0.6%    |
| Acer Predator     | 2         | 0.6%    |
| Acer Extensa      | 2         | 0.6%    |
| Valve Galileo     | 1         | 0.3%    |
| Toshiba WT8-A     | 1         | 0.3%    |
| Timi TM1701       | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 32        | 9.61%   |
| 2021 | 29        | 8.71%   |
| 2011 | 29        | 8.71%   |
| 2014 | 27        | 8.11%   |
| 2019 | 23        | 6.91%   |
| 2022 | 22        | 6.61%   |
| 2012 | 21        | 6.31%   |
| 2018 | 20        | 6.01%   |
| 2013 | 19        | 5.71%   |
| 2017 | 17        | 5.11%   |
| 2010 | 15        | 4.5%    |
| 2016 | 14        | 4.2%    |
| 2015 | 14        | 4.2%    |
| 2009 | 11        | 3.3%    |
| 2008 | 10        | 3%      |
| 2024 | 9         | 2.7%    |
| 2023 | 9         | 2.7%    |
| 2007 | 5         | 1.5%    |
| 2006 | 4         | 1.2%    |
| 2025 | 2         | 0.6%    |
| 2004 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 333       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 313       | 93.15%  |
| Enabled  | 23        | 6.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 333       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 84        | 24.71%  |
| 16.01-24.0  | 76        | 22.35%  |
| 8.01-16.0   | 68        | 20%     |
| 3.01-4.0    | 62        | 18.24%  |
| 32.01-64.0  | 24        | 7.06%   |
| 1.01-2.0    | 10        | 2.94%   |
| 24.01-32.0  | 6         | 1.76%   |
| 2.01-3.0    | 5         | 1.47%   |
| 64.01-256.0 | 3         | 0.88%   |
| 0.51-1.0    | 2         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 106       | 27.39%  |
| 2.01-3.0   | 100       | 25.84%  |
| 4.01-8.0   | 76        | 19.64%  |
| 3.01-4.0   | 50        | 12.92%  |
| 0.51-1.0   | 26        | 6.72%   |
| 8.01-16.0  | 21        | 5.43%   |
| 0.01-0.5   | 4         | 1.03%   |
| 16.01-24.0 | 2         | 0.52%   |
| 32.01-64.0 | 1         | 0.26%   |
| 24.01-32.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 244       | 71.14%  |
| 2      | 84        | 24.49%  |
| 3      | 12        | 3.5%    |
| 0      | 2         | 0.58%   |
| 4      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 227       | 67.56%  |
| Yes       | 109       | 32.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 278       | 83.23%  |
| No        | 56        | 16.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 322       | 96.7%   |
| No        | 11        | 3.3%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 78.89%  |
| No        | 72        | 21.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Lithuania | 333       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Vilnius       | 176       | 50.14%  |
| Kaunas        | 58        | 16.52%  |
| Klaipėda     | 22        | 6.27%   |
| Šiauliai     | 20        | 5.7%    |
| Mažeikiai    | 12        | 3.42%   |
| Alytus        | 7         | 1.99%   |
| Jonava        | 5         | 1.42%   |
| Utena         | 4         | 1.14%   |
| Panevezys     | 4         | 1.14%   |
| Telšiai      | 3         | 0.85%   |
| Rokiškis     | 3         | 0.85%   |
| Kėdainiai    | 3         | 0.85%   |
| Trakai        | 2         | 0.57%   |
| Tauragė      | 2         | 0.57%   |
| Plungė       | 2         | 0.57%   |
| Palanga       | 2         | 0.57%   |
| Anykščiai   | 2         | 0.57%   |
| Želva        | 1         | 0.28%   |
| Visaginas     | 1         | 0.28%   |
| Vėžaičiai  | 1         | 0.28%   |
| Ukmerge       | 1         | 0.28%   |
| Švenčionys  | 1         | 0.28%   |
| Skuodas       | 1         | 0.28%   |
| Širvintos    | 1         | 0.28%   |
| Šilalė      | 1         | 0.28%   |
| Serdokai      | 1         | 0.28%   |
| Šeduva       | 1         | 0.28%   |
| Šalčininkai | 1         | 0.28%   |
| Rietavas      | 1         | 0.28%   |
| Pasvalys      | 1         | 0.28%   |
| Pakruojis     | 1         | 0.28%   |
| Molėtai      | 1         | 0.28%   |
| Mauruciai     | 1         | 0.28%   |
| Marijampolė  | 1         | 0.28%   |
| Maneikiai     | 1         | 0.28%   |
| Lentvaris     | 1         | 0.28%   |
| Karkliniai    | 1         | 0.28%   |
| Joniškis     | 1         | 0.28%   |
| Gineitiskes   | 1         | 0.28%   |
| Domeikava     | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 75        | 112    | 17.48%  |
| Seagate                      | 36        | 45     | 8.39%   |
| Toshiba                      | 35        | 47     | 8.16%   |
| Sandisk                      | 34        | 35     | 7.93%   |
| WDC                          | 33        | 43     | 7.69%   |
| Kingston                     | 32        | 42     | 7.46%   |
| Unknown                      | 17        | 38     | 3.96%   |
| SK hynix                     | 15        | 17     | 3.5%    |
| Micron Technology            | 14        | 15     | 3.26%   |
| Intel                        | 14        | 18     | 3.26%   |
| Hitachi                      | 13        | 20     | 3.03%   |
| A-DATA Technology            | 13        | 14     | 3.03%   |
| Patriot                      | 11        | 12     | 2.56%   |
| KIOXIA                       | 9         | 12     | 2.1%    |
| Crucial                      | 8         | 9      | 1.86%   |
| HGST                         | 7         | 8      | 1.63%   |
| SPCC                         | 6         | 12     | 1.4%    |
| MAXIO Technology (Hangzhou)  | 5         | 8      | 1.17%   |
| Phison Electronics           | 3         | 4      | 0.7%    |
| Lexar                        | 3         | 4      | 0.7%    |
| Kingston Technology Company  | 3         | 3      | 0.7%    |
| China                        | 3         | 5      | 0.7%    |
| XrayDisk                     | 2         | 3      | 0.47%   |
| Union Memory (Shenzhen)      | 2         | 2      | 0.47%   |
| Plextor                      | 2         | 2      | 0.47%   |
| KingSpec                     | 2         | 2      | 0.47%   |
| KingDian                     | 2         | 3      | 0.47%   |
| ASMT                         | 2         | 2      | 0.47%   |
| Apple                        | 2         | 2      | 0.47%   |
| Apacer                       | 2         | 2      | 0.47%   |
| Unknown                      | 2         | 2      | 0.47%   |
| Yangtze Memory Technologies  | 1         | 1      | 0.23%   |
| Union Memory                 | 1         | 1      | 0.23%   |
| UMIS                         | 1         | 1      | 0.23%   |
| Team                         | 1         | 1      | 0.23%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.23%   |
| PNY                          | 1         | 1      | 0.23%   |
| OWC                          | 1         | 2      | 0.23%   |
| OCZ                          | 1         | 1      | 0.23%   |
| O2 Micro                     | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 7         | 1.57%   |
| Kingston SA400S37240G 240GB SSD                    | 7         | 1.57%   |
| Samsung SSD 850 EVO 250GB                          | 6         | 1.35%   |
| Unknown MMC Card  32GB                             | 5         | 1.12%   |
| Toshiba MQ01ABD100 1TB                             | 5         | 1.12%   |
| Toshiba BG3 NVMe SSD Controller 256GB              | 5         | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 5         | 1.12%   |
| SanDisk NVMe SSD Drive 256GB                       | 5         | 1.12%   |
| Kingston SV300S37A120G 120GB SSD                   | 5         | 1.12%   |
| Kingston SA400S37480G 480GB SSD                    | 5         | 1.12%   |
| Intel NVMe SSD Drive 512GB                         | 5         | 1.12%   |
| Toshiba MQ01ABF050 500GB                           | 4         | 0.9%    |
| Seagate ST500LT012-1DG142 500GB                    | 4         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 0.9%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB   | 4         | 0.9%    |
| Seagate ST9500325AS 500GB                          | 3         | 0.67%   |
| Seagate ST750LM022 HN-M750MBB 752GB                | 3         | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB                     | 3         | 0.67%   |
| Samsung SSD 980 1TB                                | 3         | 0.67%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                      | 3         | 0.67%   |
| Kingston SA400S37120G 120GB SSD                    | 3         | 0.67%   |
| HGST HTS541010A9E680 1TB                           | 3         | 0.67%   |
| WDC WD5000BEVT-24A0RT0 500GB                       | 2         | 0.45%   |
| Unknown MMC Card  64GB                             | 2         | 0.45%   |
| Toshiba NVMe SSD Drive 512GB                       | 2         | 0.45%   |
| Toshiba NVMe SSD Drive 256GB                       | 2         | 0.45%   |
| Toshiba MQ01ABD050 500GB                           | 2         | 0.45%   |
| Toshiba KXG6AZNV512G 512GB                         | 2         | 0.45%   |
| Toshiba HDWL110 1TB                                | 2         | 0.45%   |
| SPCC Solid State Disk 256GB                        | 2         | 0.45%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 2         | 0.45%   |
| SK hynix HFS256G32TND-N210A 256GB SSD              | 2         | 0.45%   |
| Seagate ST9750420AS 752GB                          | 2         | 0.45%   |
| Seagate ST9160821AS 160GB                          | 2         | 0.45%   |
| Seagate ST2000LM007-1R8174 2TB                     | 2         | 0.45%   |
| SanDisk X400 M.2 2280 256GB SSD                    | 2         | 0.45%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 2         | 0.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 2         | 0.45%   |
| SanDisk SD8SBAT128G1002 128GB SSD                  | 2         | 0.45%   |
| Samsung MZVLQ512HALU-000H1 512GB                   | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 45     | 36%     |
| WDC                 | 22        | 29     | 22%     |
| Toshiba             | 17        | 21     | 17%     |
| Hitachi             | 13        | 20     | 13%     |
| HGST                | 7         | 8      | 7%      |
| Samsung Electronics | 2         | 4      | 2%      |
| Unknown             | 1         | 1      | 1%      |
| Fujitsu             | 1         | 1      | 1%      |
| ASMT                | 1         | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 28        | 38     | 18.42%  |
| Samsung Electronics | 27        | 49     | 17.76%  |
| SanDisk             | 12        | 13     | 7.89%   |
| A-DATA Technology   | 12        | 13     | 7.89%   |
| Patriot             | 11        | 12     | 7.24%   |
| Crucial             | 7         | 7      | 4.61%   |
| SPCC                | 6         | 12     | 3.95%   |
| SK hynix            | 6         | 7      | 3.95%   |
| Toshiba             | 5         | 7      | 3.29%   |
| WDC                 | 4         | 7      | 2.63%   |
| Intel               | 3         | 3      | 1.97%   |
| China               | 3         | 5      | 1.97%   |
| Plextor             | 2         | 2      | 1.32%   |
| Micron Technology   | 2         | 2      | 1.32%   |
| KingSpec            | 2         | 2      | 1.32%   |
| Apple               | 2         | 2      | 1.32%   |
| Apacer              | 2         | 2      | 1.32%   |
| XrayDisk            | 1         | 2      | 0.66%   |
| Team                | 1         | 1      | 0.66%   |
| PNY                 | 1         | 1      | 0.66%   |
| OWC                 | 1         | 2      | 0.66%   |
| OCZ                 | 1         | 1      | 0.66%   |
| LITEONIT            | 1         | 1      | 0.66%   |
| LITEON              | 1         | 2      | 0.66%   |
| Lexar               | 1         | 1      | 0.66%   |
| KingDian            | 1         | 2      | 0.66%   |
| GOODRAM             | 1         | 1      | 0.66%   |
| FORESEE             | 1         | 1      | 0.66%   |
| Dahua               | 1         | 2      | 0.66%   |
| CUSU                | 1         | 1      | 0.66%   |
| CT120BX5            | 1         | 1      | 0.66%   |
| Corsair             | 1         | 1      | 0.66%   |
| BR                  | 1         | 1      | 0.66%   |
| ASMT                | 1         | 1      | 0.66%   |
| ADATA LE            | 1         | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 147       | 191    | 36.48%  |
| SSD     | 139       | 206    | 34.49%  |
| HDD     | 98        | 130    | 24.32%  |
| MMC     | 16        | 38     | 3.97%   |
| Unknown | 3         | 3      | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 198       | 323    | 52.8%   |
| NVMe | 146       | 190    | 38.93%  |
| MMC  | 16        | 38     | 4.27%   |
| SAS  | 15        | 17     | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 167       | 252    | 73.89%  |
| 0.51-1.0   | 53        | 76     | 23.45%  |
| 1.01-2.0   | 5         | 7      | 2.21%   |
| 3.01-4.0   | 1         | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 107       | 29.56%  |
| 251-500        | 99        | 27.35%  |
| 501-1000       | 49        | 13.54%  |
| 1-20           | 29        | 8.01%   |
| 51-100         | 21        | 5.8%    |
| 21-50          | 18        | 4.97%   |
| 1001-2000      | 18        | 4.97%   |
| Unknown        | 11        | 3.04%   |
| More than 3000 | 6         | 1.66%   |
| 2001-3000      | 4         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 149       | 39.11%  |
| 21-50          | 68        | 17.85%  |
| 101-250        | 59        | 15.49%  |
| 51-100         | 42        | 11.02%  |
| 251-500        | 36        | 9.45%   |
| Unknown        | 11        | 2.89%   |
| 501-1000       | 10        | 2.62%   |
| 1001-2000      | 5         | 1.31%   |
| More than 3000 | 1         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 3.85%   |
| WDC WD6400BPVT-22HXZT1 640GB                        | 1         | 2      | 3.85%   |
| WDC WD5000BEVT-24A0RT0 500GB                        | 1         | 1      | 3.85%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 2      | 3.85%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 3.85%   |
| Toshiba MK1652GSX 160GB                             | 1         | 2      | 3.85%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 3.85%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD               | 1         | 1      | 3.85%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 3.85%   |
| Seagate ST9640320AS 640GB                           | 1         | 2      | 3.85%   |
| Samsung Electronics SSD 850 EVO 250GB               | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 840 Series 500GB            | 1         | 3      | 3.85%   |
| Samsung Electronics HM641JI 640GB                   | 1         | 2      | 3.85%   |
| Plextor PX-128M6M 128GB SSD                         | 1         | 1      | 3.85%   |
| Micron Technology MTFDDAK512TBN-1AR15ABHA 512GB SSD | 1         | 1      | 3.85%   |
| Hitachi HTS545050KTA300 500GB                       | 1         | 1      | 3.85%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 3.85%   |
| Hitachi HTS545025B9A300 250GB                       | 1         | 1      | 3.85%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 3.85%   |
| HGST HTS541010A9E680 1TB                            | 1         | 2      | 3.85%   |
| A-DATA Technology SX900 128GB SSD                   | 1         | 1      | 3.85%   |
| A-DATA Technology SU800 256GB SSD                   | 1         | 2      | 3.85%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 15.38%  |
| Toshiba             | 4         | 6      | 15.38%  |
| Hitachi             | 4         | 4      | 15.38%  |
| SK hynix            | 3         | 3      | 11.54%  |
| Samsung Electronics | 3         | 6      | 11.54%  |
| A-DATA Technology   | 3         | 4      | 11.54%  |
| HGST                | 2         | 3      | 7.69%   |
| Seagate             | 1         | 2      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 25%     |
| Toshiba             | 4         | 6      | 25%     |
| Hitachi             | 4         | 4      | 25%     |
| HGST                | 2         | 3      | 12.5%   |
| Seagate             | 1         | 2      | 6.25%   |
| Samsung Electronics | 1         | 2      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 22     | 61.54%  |
| SSD  | 9         | 12     | 34.62%  |
| NVMe | 1         | 1      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Hitachi HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 190       | 312    | 52.92%  |
| Works    | 144       | 220    | 40.11%  |
| Malfunc  | 24        | 35     | 6.69%   |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 219       | 54.89%  |
| Samsung Electronics                     | 48        | 12.03%  |
| AMD                                     | 28        | 7.02%   |
| SanDisk                                 | 26        | 6.52%   |
| Toshiba America Info Systems            | 14        | 3.51%   |
| Micron Technology                       | 12        | 3.01%   |
| SK hynix                                | 9         | 2.26%   |
| KIOXIA                                  | 9         | 2.26%   |
| Kingston Technology Company             | 7         | 1.75%   |
| MAXIO Technology (Hangzhou)             | 5         | 1.25%   |
| Union Memory (Shenzhen)                 | 3         | 0.75%   |
| Phison Electronics                      | 3         | 0.75%   |
| Nvidia                                  | 3         | 0.75%   |
| Solidigm                                | 2         | 0.5%    |
| Shenzhen Longsys Electronics            | 2         | 0.5%    |
| Yangtze Memory Technologies             | 1         | 0.25%   |
| VIA Technologies                        | 1         | 0.25%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.25%   |
| Shenzhen Unionmemory Information System | 1         | 0.25%   |
| O2 Micro                                | 1         | 0.25%   |
| Micron/Crucial Technology               | 1         | 0.25%   |
| Lite-On Technology                      | 1         | 0.25%   |
| JMicron Technology                      | 1         | 0.25%   |
| ADATA Technology                        | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 28        | 6.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 23        | 5.39%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 4.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 4.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 3.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 3.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 3.28%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13        | 3.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 12        | 2.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 2.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 2.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 8         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 1.87%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 7         | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 1.64%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 1.41%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 6         | 1.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.41%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 1.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.17%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 5         | 1.17%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.17%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.94%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 4         | 0.94%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 4         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.94%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 4         | 0.94%   |
| Intel SSD 660P Series                                                          | 4         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.94%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.7%    |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 0.7%    |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.7%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 3         | 0.7%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 210       | 52.24%  |
| NVMe | 146       | 36.32%  |
| RAID | 26        | 6.47%   |
| IDE  | 20        | 4.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 260       | 78.08%  |
| AMD          | 71        | 21.32%  |
| Qualcomm     | 1         | 0.3%    |
| CentaurHauls | 1         | 0.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz          | 6         | 1.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 1.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 1.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.5%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 5         | 1.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz           | 5         | 1.5%    |
| AMD Ryzen 5 5600H with Radeon Graphics      | 5         | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 1.2%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 4         | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.2%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.2%    |
| Intel Core i5-2430M CPU @ 2.40GHz           | 4         | 1.2%    |
| Intel Core i3-4000M CPU @ 2.40GHz           | 4         | 1.2%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 4         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.2%    |
| AMD Ryzen 7 5800H with Radeon Graphics      | 4         | 1.2%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 1.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics      | 4         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.9%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 3         | 0.9%    |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 3         | 0.9%    |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 0.9%    |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.9%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 3         | 0.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 0.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.9%    |
| Intel Core i5-2540M CPU @ 2.60GHz           | 3         | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 0.9%    |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 0.9%    |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 0.9%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 3         | 0.9%    |
| AMD Custom APU 0405                         | 3         | 0.9%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.6%    |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.6%    |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 0.6%    |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.6%    |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 77        | 23.12%  |
| Intel Core i7           | 68        | 20.42%  |
| Other                   | 35        | 10.51%  |
| Intel Core i3           | 34        | 10.21%  |
| AMD Ryzen 5             | 25        | 7.51%   |
| AMD Ryzen 7             | 19        | 5.71%   |
| Intel Core 2 Duo        | 13        | 3.9%    |
| Intel Celeron           | 13        | 3.9%    |
| Intel Pentium           | 6         | 1.8%    |
| AMD Ryzen 7 PRO         | 6         | 1.8%    |
| Intel Atom              | 5         | 1.5%    |
| Intel Pentium Dual-Core | 3         | 0.9%    |
| Intel Core i9           | 3         | 0.9%    |
| Intel Core 2            | 3         | 0.9%    |
| AMD Phenom II           | 3         | 0.9%    |
| Intel Genuine           | 2         | 0.6%    |
| AMD Ryzen 5 PRO         | 2         | 0.6%    |
| AMD Ryzen 3             | 2         | 0.6%    |
| AMD E                   | 2         | 0.6%    |
| AMD A8                  | 2         | 0.6%    |
| Intel Pentium Silver    | 1         | 0.3%    |
| Intel Pentium Gold      | 1         | 0.3%    |
| Intel Core m7           | 1         | 0.3%    |
| Intel Core              | 1         | 0.3%    |
| CentaurHauls VIA Nano   | 1         | 0.3%    |
| AMD Sempron             | 1         | 0.3%    |
| AMD E2                  | 1         | 0.3%    |
| AMD C-60                | 1         | 0.3%    |
| AMD A6                  | 1         | 0.3%    |
| AMD A10                 | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 142       | 42.39%  |
| 4       | 104       | 31.04%  |
| 6       | 39        | 11.64%  |
| 8       | 33        | 9.85%   |
| 14      | 3         | 0.9%    |
| 12      | 3         | 0.9%    |
| 10      | 3         | 0.9%    |
| 1       | 3         | 0.9%    |
| Unknown | 2         | 0.6%    |
| 20      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 3       | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 333       | 99.7%   |
| Unknown | 1         | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 259       | 77.54%  |
| 1       | 73        | 21.86%  |
| Unknown | 2         | 0.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 329       | 98.8%   |
| 32-bit         | 2         | 0.6%    |
| 64-bit         | 1         | 0.3%    |
| Unknown        | 1         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 44.96%  |
| 0x306a9    | 19        | 5.48%   |
| 0x206a7    | 17        | 4.9%    |
| 0x806ea    | 11        | 3.17%   |
| 0x306c3    | 10        | 2.88%   |
| 0x406e3    | 9         | 2.59%   |
| 0x20655    | 9         | 2.59%   |
| 0x806c1    | 8         | 2.31%   |
| 0x806ec    | 6         | 1.73%   |
| 0x40651    | 6         | 1.73%   |
| 0x306d4    | 6         | 1.73%   |
| 0x1067a    | 6         | 1.73%   |
| 0xa0652    | 4         | 1.15%   |
| 0x906ea    | 4         | 1.15%   |
| 0x506e3    | 4         | 1.15%   |
| 0x0a50000d | 4         | 1.15%   |
| 0x0a50000c | 4         | 1.15%   |
| 0x806eb    | 3         | 0.86%   |
| 0x6fd      | 3         | 0.86%   |
| 0x30678    | 3         | 0.86%   |
| 0x20652    | 3         | 0.86%   |
| 0x08608103 | 3         | 0.86%   |
| 0x906ed    | 2         | 0.58%   |
| 0x906e9    | 2         | 0.58%   |
| 0x706a1    | 2         | 0.58%   |
| 0x6f2      | 2         | 0.58%   |
| 0x10676    | 2         | 0.58%   |
| 0x0a404102 | 2         | 0.58%   |
| 0x0a404101 | 2         | 0.58%   |
| 0x08600106 | 2         | 0.58%   |
| 0x08108102 | 2         | 0.58%   |
| 0x05000119 | 2         | 0.58%   |
| 0x010000c8 | 2         | 0.58%   |
| 0x906a3    | 1         | 0.29%   |
| 0x806e9    | 1         | 0.29%   |
| 0x706e5    | 1         | 0.29%   |
| 0x6fa      | 1         | 0.29%   |
| 0x6f6      | 1         | 0.29%   |
| 0x6ec      | 1         | 0.29%   |
| 0x506c9    | 1         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 52        | 15.62%  |
| Unknown          | 36        | 10.81%  |
| Haswell          | 29        | 8.71%   |
| IvyBridge        | 28        | 8.41%   |
| SandyBridge      | 27        | 8.11%   |
| Skylake          | 19        | 5.71%   |
| Zen 3            | 18        | 5.41%   |
| TigerLake        | 15        | 4.5%    |
| Westmere         | 14        | 4.2%    |
| Penryn           | 12        | 3.6%    |
| Zen 2            | 11        | 3.3%    |
| Core             | 9         | 2.7%    |
| CometLake        | 9         | 2.7%    |
| Silvermont       | 8         | 2.4%    |
| Broadwell        | 7         | 2.1%    |
| Alderlake Hybrid | 7         | 2.1%    |
| Zen+             | 5         | 1.5%    |
| Goldmont plus    | 5         | 1.5%    |
| Bobcat           | 4         | 1.2%    |
| K10              | 3         | 0.9%    |
| Goldmont         | 3         | 0.9%    |
| Piledriver       | 2         | 0.6%    |
| Nehalem          | 2         | 0.6%    |
| IceLake          | 2         | 0.6%    |
| Excavator        | 2         | 0.6%    |
| Bonnell          | 2         | 0.6%    |
| K8 & K10 hybrid  | 1         | 0.3%    |
| Jaguar           | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 230       | 52.75%  |
| Nvidia                           | 109       | 25%     |
| AMD                              | 95        | 21.79%  |
| VIA Technologies                 | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 25        | 5.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 24        | 5.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 16        | 3.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 15        | 3.32%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                         | 12        | 2.65%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                      | 12        | 2.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 11        | 2.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 10        | 2.21%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 10        | 2.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 9         | 1.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 1.77%   |
| Intel Core Processor Integrated Graphics Controller                           | 8         | 1.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 8         | 1.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 8         | 1.77%   |
| AMD Rembrandt [Radeon 680M]                                                   | 8         | 1.77%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                      | 7         | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 6         | 1.33%   |
| AMD Lucienne                                                                  | 6         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 5         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.11%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 5         | 1.11%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                         | 5         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 5         | 1.11%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                       | 5         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 5         | 1.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.11%   |
| AMD Barcelo                                                                   | 5         | 1.11%   |
| Nvidia GP108M [GeForce MX150]                                                 | 4         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                                  | 4         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 4         | 0.88%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 4         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 4         | 0.88%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                       | 4         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 0.88%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 4         | 0.88%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 4         | 0.88%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 4         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 3         | 0.66%   |
| Nvidia GP108M [GeForce MX330]                                                 | 3         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 134       | 40%     |
| Intel + Nvidia | 79        | 23.58%  |
| 1 x AMD        | 64        | 19.1%   |
| 1 x Nvidia     | 23        | 6.87%   |
| Intel + AMD    | 14        | 4.18%   |
| 2 x AMD        | 9         | 2.69%   |
| AMD + Nvidia   | 7         | 2.09%   |
| 2 x Intel      | 2         | 0.6%    |
| Other          | 1         | 0.3%    |
| 1 x VIA        | 1         | 0.3%    |
| 1 x SiS        | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 285       | 82.61%  |
| Proprietary | 49        | 14.2%   |
| Unknown     | 11        | 3.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 203       | 59.01%  |
| 1.01-2.0   | 49        | 14.24%  |
| 0.01-0.5   | 49        | 14.24%  |
| 0.51-1.0   | 17        | 4.94%   |
| 3.01-4.0   | 13        | 3.78%   |
| 5.01-6.0   | 6         | 1.74%   |
| 7.01-8.0   | 4         | 1.16%   |
| 2.01-3.0   | 2         | 0.58%   |
| 8.01-16.0  | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 63        | 16.41%  |
| LG Display              | 61        | 15.89%  |
| BOE                     | 56        | 14.58%  |
| Chimei Innolux          | 44        | 11.46%  |
| Samsung Electronics     | 41        | 10.68%  |
| Dell                    | 19        | 4.95%   |
| Lenovo                  | 17        | 4.43%   |
| Chi Mei Optoelectronics | 14        | 3.65%   |
| PANDA                   | 7         | 1.82%   |
| Goldstar                | 7         | 1.82%   |
| Apple                   | 6         | 1.56%   |
| Sony                    | 5         | 1.3%    |
| Philips                 | 5         | 1.3%    |
| CSO                     | 5         | 1.3%    |
| Valve                   | 4         | 1.04%   |
| Sharp                   | 4         | 1.04%   |
| LG Philips              | 2         | 0.52%   |
| HKC                     | 2         | 0.52%   |
| Hewlett-Packard         | 2         | 0.52%   |
| AOC                     | 2         | 0.52%   |
| Unknown (AAA)           | 1         | 0.26%   |
| Toshiba                 | 1         | 0.26%   |
| TMX                     | 1         | 0.26%   |
| Panasonic               | 1         | 0.26%   |
| MStar                   | 1         | 0.26%   |
| LGD                     | 1         | 0.26%   |
| KDC                     | 1         | 0.26%   |
| JDI                     | 1         | 0.26%   |
| InfoVision              | 1         | 0.26%   |
| Iiyama                  | 1         | 0.26%   |
| IBM                     | 1         | 0.26%   |
| HannStar                | 1         | 0.26%   |
| Gigabyte Technology     | 1         | 0.26%   |
| EDO                     | 1         | 0.26%   |
| CSW                     | 1         | 0.26%   |
| BenQ                    | 1         | 0.26%   |
| ASUSTek Computer        | 1         | 0.26%   |
| Acer                    | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 5         | 1.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 1.03%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 3         | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.78%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 3         | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.78%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                     | 3         | 0.78%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.78%   |
| Sony LCD Monitor MS_9005 1920x1080                                       | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.52%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 294x165mm 13.3-inch                  | 2         | 0.52%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.52%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 2         | 0.52%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.52%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.52%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.52%   |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch             | 2         | 0.52%   |
| HKC LCD Monitor HKC3D00 1920x1080 344x194mm 15.5-inch                    | 2         | 0.52%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 2         | 0.52%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 2         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 166       | 46.24%  |
| 1366x768 (WXGA)    | 77        | 21.45%  |
| 1600x900 (HD+)     | 24        | 6.69%   |
| 3840x2160 (4K)     | 14        | 3.9%    |
| 2560x1440 (QHD)    | 14        | 3.9%    |
| 1280x800 (WXGA)    | 14        | 3.9%    |
| 1920x1200 (WUXGA)  | 12        | 3.34%   |
| 2560x1600          | 8         | 2.23%   |
| 800x1280           | 4         | 1.11%   |
| 1680x1050 (WSXGA+) | 4         | 1.11%   |
| 2880x1800          | 3         | 0.84%   |
| 1440x900 (WXGA+)   | 3         | 0.84%   |
| 3840x2400          | 2         | 0.56%   |
| 3440x1440          | 2         | 0.56%   |
| 2880x1620          | 2         | 0.56%   |
| 1280x1024 (SXGA)   | 2         | 0.56%   |
| 3120x2080          | 1         | 0.28%   |
| 3000x2000          | 1         | 0.28%   |
| 2880x1920          | 1         | 0.28%   |
| 2560x1080          | 1         | 0.28%   |
| 2160x1440          | 1         | 0.28%   |
| 1024x768 (XGA)     | 1         | 0.28%   |
| 1024x600           | 1         | 0.28%   |
| Unknown            | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 175       | 45.81%  |
| 14      | 41        | 10.73%  |
| 13      | 37        | 9.69%   |
| 17      | 25        | 6.54%   |
| 24      | 19        | 4.97%   |
| 27      | 15        | 3.93%   |
| 16      | 14        | 3.66%   |
| 12      | 11        | 2.88%   |
| 23      | 9         | 2.36%   |
| 21      | 7         | 1.83%   |
| 31      | 6         | 1.57%   |
| 7       | 4         | 1.05%   |
| 72      | 2         | 0.52%   |
| 34      | 2         | 0.52%   |
| 18      | 2         | 0.52%   |
| Unknown | 2         | 0.52%   |
| 84      | 1         | 0.26%   |
| 75      | 1         | 0.26%   |
| 52      | 1         | 0.26%   |
| 40      | 1         | 0.26%   |
| 29      | 1         | 0.26%   |
| 25      | 1         | 0.26%   |
| 22      | 1         | 0.26%   |
| 20      | 1         | 0.26%   |
| 19      | 1         | 0.26%   |
| 11      | 1         | 0.26%   |
| 10      | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 246       | 64.57%  |
| 501-600     | 41        | 10.76%  |
| 351-400     | 32        | 8.4%    |
| 201-300     | 29        | 7.61%   |
| 401-500     | 10        | 2.62%   |
| 601-700     | 9         | 2.36%   |
| 1501-2000   | 4         | 1.05%   |
| 1-100       | 4         | 1.05%   |
| 701-800     | 2         | 0.52%   |
| Unknown     | 2         | 0.52%   |
| 801-900     | 1         | 0.26%   |
| 1001-1500   | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 274       | 81.79%  |
| 16/10   | 46        | 13.73%  |
| 3/2     | 4         | 1.19%   |
| 0.67    | 3         | 0.9%    |
| 5/4     | 2         | 0.6%    |
| 21/9    | 2         | 0.6%    |
| Unknown | 2         | 0.6%    |
| 4/3     | 1         | 0.3%    |
| 0.62    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 172       | 45.26%  |
| 81-90          | 68        | 17.89%  |
| 201-250        | 29        | 7.63%   |
| 121-130        | 23        | 6.05%   |
| 301-350        | 15        | 3.95%   |
| 111-120        | 13        | 3.42%   |
| 61-70          | 11        | 2.89%   |
| 351-500        | 9         | 2.37%   |
| 71-80          | 8         | 2.11%   |
| More than 1000 | 5         | 1.32%   |
| 251-300        | 5         | 1.32%   |
| 1-40           | 4         | 1.05%   |
| 91-100         | 4         | 1.05%   |
| 151-200        | 3         | 0.79%   |
| 141-150        | 3         | 0.79%   |
| 131-140        | 3         | 0.79%   |
| Unknown        | 2         | 0.53%   |
| 51-60          | 1         | 0.26%   |
| 41-50          | 1         | 0.26%   |
| 501-1000       | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 171       | 45.6%   |
| 101-120       | 88        | 23.47%  |
| 51-100        | 69        | 18.4%   |
| 161-240       | 32        | 8.53%   |
| More than 240 | 10        | 2.67%   |
| 1-50          | 3         | 0.8%    |
| Unknown       | 2         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 271       | 80.42%  |
| 2     | 52        | 15.43%  |
| 0     | 8         | 2.37%   |
| 3     | 6         | 1.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 176       | 32.29%  |
| Intel                             | 172       | 31.56%  |
| Qualcomm Atheros                  | 74        | 13.58%  |
| Broadcom                          | 34        | 6.24%   |
| MediaTek                          | 23        | 4.22%   |
| Broadcom Limited                  | 7         | 1.28%   |
| Ralink                            | 5         | 0.92%   |
| Qualcomm                          | 5         | 0.92%   |
| Marvell Technology Group          | 5         | 0.92%   |
| Lenovo                            | 5         | 0.92%   |
| Shenzhen Goodix Technology        | 4         | 0.73%   |
| TP-Link                           | 3         | 0.55%   |
| Nvidia                            | 3         | 0.55%   |
| Huawei Technologies               | 3         | 0.55%   |
| Ericsson Business Mobile Networks | 3         | 0.55%   |
| Dell                              | 3         | 0.55%   |
| ASIX Electronics                  | 3         | 0.55%   |
| Sierra Wireless                   | 2         | 0.37%   |
| Qualcomm Technologies             | 2         | 0.37%   |
| JMicron Technology                | 2         | 0.37%   |
| Hewlett-Packard                   | 2         | 0.37%   |
| Fibocom                           | 2         | 0.37%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.18%   |
| Ralink Technology                 | 1         | 0.18%   |
| Qualcomm Atheros Communications   | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.18%   |
| MOBILE                            | 1         | 0.18%   |
| Edimax Technology                 | 1         | 0.18%   |
| D-Link                            | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 113       | 17.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 27        | 4.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 19        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18        | 2.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 17        | 2.58%   |
| Intel Wi-Fi 6 AX201                                                    | 14        | 2.12%   |
| Intel Wi-Fi 6 AX200                                                    | 14        | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 1.82%   |
| Intel Wireless 8260                                                    | 12        | 1.82%   |
| Intel Wireless 8265 / 8275                                             | 11        | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.52%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 10        | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 10        | 1.52%   |
| Intel Wireless 7260                                                    | 9         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 8         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 8         | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 1.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7         | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 6         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 0.91%   |
| Intel Wireless 7265                                                    | 6         | 0.91%   |
| Intel Wireless 3165                                                    | 6         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                         | 6         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.76%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 0.76%   |
| Shenzhen Goodix Fingerprint Reader                                     | 4         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.61%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 4         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 165       | 48.39%  |
| Qualcomm Atheros                | 65        | 19.06%  |
| Realtek Semiconductor           | 34        | 9.97%   |
| Broadcom                        | 27        | 7.92%   |
| MediaTek                        | 22        | 6.45%   |
| Ralink                          | 5         | 1.47%   |
| Qualcomm                        | 4         | 1.17%   |
| Broadcom Limited                | 4         | 1.17%   |
| TP-Link                         | 3         | 0.88%   |
| Sierra Wireless                 | 2         | 0.59%   |
| Qualcomm Technologies           | 2         | 0.59%   |
| Fibocom                         | 2         | 0.59%   |
| Dell                            | 2         | 0.59%   |
| Ralink Technology               | 1         | 0.29%   |
| Qualcomm Atheros Communications | 1         | 0.29%   |
| Edimax Technology               | 1         | 0.29%   |
| D-Link                          | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 5.57%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 4.11%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 4.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 3.52%   |
| Intel Wireless 8260                                                     | 12        | 3.52%   |
| Intel Wireless 8265 / 8275                                              | 11        | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.93%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 10        | 2.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 2.93%   |
| Intel Wireless 7260                                                     | 9         | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 2.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 7         | 2.05%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 6         | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.76%   |
| Intel Wireless 7265                                                     | 6         | 1.76%   |
| Intel Wireless 3165                                                     | 6         | 1.76%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 1.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.17%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 4         | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.17%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.88%   |
| Intel Wireless 3160                                                     | 3         | 0.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.88%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 3         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 163       | 55.07%  |
| Intel                         | 66        | 22.3%   |
| Qualcomm Atheros              | 24        | 8.11%   |
| Broadcom                      | 15        | 5.07%   |
| Marvell Technology Group      | 5         | 1.69%   |
| Lenovo                        | 5         | 1.69%   |
| Nvidia                        | 3         | 1.01%   |
| Huawei Technologies           | 3         | 1.01%   |
| Broadcom Limited              | 3         | 1.01%   |
| ASIX Electronics              | 3         | 1.01%   |
| JMicron Technology            | 2         | 0.68%   |
| Qualcomm                      | 1         | 0.34%   |
| OnePlus Technology (Shenzhen) | 1         | 0.34%   |
| MOBILE                        | 1         | 0.34%   |
| MediaTek                      | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 113       | 36.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 27        | 8.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18        | 5.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 17        | 5.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.63%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 1.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 1.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 4         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.98%   |
| Lenovo USB-C Dock Ethernet                                                     | 3         | 0.98%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.98%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 3         | 0.98%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 3         | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.98%   |
| Realtek Killer E2600 GbE Controller                                            | 2         | 0.65%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.65%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.65%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.65%   |
| Intel Ethernet Connection (16) I219-LM                                         | 2         | 0.65%   |
| Huawei E353/E3131                                                              | 2         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.65%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.65%   |
| Realtek USB 10/100 LAN                                                         | 1         | 0.33%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 324       | 52.68%  |
| Ethernet | 280       | 45.53%  |
| Modem    | 11        | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 271       | 75.7%   |
| Ethernet | 86        | 24.02%  |
| Modem    | 1         | 0.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 258       | 77.48%  |
| 1     | 67        | 20.12%  |
| 0     | 5         | 1.5%    |
| 3     | 3         | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 328       | 97.91%  |
| Yes  | 7         | 2.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 44.73%  |
| Qualcomm Atheros Communications | 31        | 11.27%  |
| IMC Networks                    | 21        | 7.64%   |
| Realtek Semiconductor           | 20        | 7.27%   |
| Foxconn / Hon Hai               | 19        | 6.91%   |
| Broadcom                        | 19        | 6.91%   |
| Lite-On Technology              | 6         | 2.18%   |
| Apple                           | 6         | 2.18%   |
| Hewlett-Packard                 | 5         | 1.82%   |
| Cambridge Silicon Radio         | 5         | 1.82%   |
| Ralink                          | 4         | 1.45%   |
| ASUSTek Computer                | 4         | 1.45%   |
| Toshiba                         | 3         | 1.09%   |
| MediaTek                        | 3         | 1.09%   |
| Dell                            | 3         | 1.09%   |
| USI                             | 1         | 0.36%   |
| TP-Link                         | 1         | 0.36%   |
| Taiyo Yuden                     | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 44        | 16%     |
| Intel AX201 Bluetooth                               | 29        | 10.55%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 6.55%   |
| Realtek Bluetooth Radio                             | 15        | 5.45%   |
| Intel AX200 Bluetooth                               | 13        | 4.73%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 3.64%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.55%   |
| Intel AX210 Bluetooth                               | 6         | 2.18%   |
| IMC Networks Wireless_Device                        | 6         | 2.18%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 2.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.82%   |
| Intel Bluetooth Device                              | 5         | 1.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 1.82%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 1.82%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.09%   |
| MediaTek Wireless_Device                            | 3         | 1.09%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 1.09%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 1.09%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 1.09%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.09%   |
| Apple Bluetooth Host Controller                     | 3         | 1.09%   |
| Toshiba Bluetooth Device                            | 2         | 0.73%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.73%   |
| IMC Networks Bluetooth Device                       | 2         | 0.73%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.73%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.73%   |
| Broadcom HP Portable Valentine                      | 2         | 0.73%   |
| Broadcom BCM2046 Bluetooth Device                   | 2         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.73%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.73%   |
| USI Bluetooth Device                                | 1         | 0.36%   |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.36%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 255       | 58.62%  |
| AMD                              | 83        | 19.08%  |
| Nvidia                           | 66        | 15.17%  |
| Lenovo                           | 5         | 1.15%   |
| Realtek Semiconductor            | 2         | 0.46%   |
| JMTek                            | 2         | 0.46%   |
| Hewlett-Packard                  | 2         | 0.46%   |
| Creative Technology              | 2         | 0.46%   |
| C-Media Electronics              | 2         | 0.46%   |
| ASUSTek Computer                 | 2         | 0.46%   |
| XMOS                             | 1         | 0.23%   |
| VIA Technologies                 | 1         | 0.23%   |
| Texas Instruments                | 1         | 0.23%   |
| SteelSeries ApS                  | 1         | 0.23%   |
| Sony                             | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Razer USA                        | 1         | 0.23%   |
| Microsoft                        | 1         | 0.23%   |
| Logitech                         | 1         | 0.23%   |
| Kingston Technology              | 1         | 0.23%   |
| GN Netcom                        | 1         | 0.23%   |
| Generalplus Technology           | 1         | 0.23%   |
| DSEA A/S                         | 1         | 0.23%   |
| Comtrue                          | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 53        | 10.02%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32        | 6.05%   |
| Intel Sunrise Point-LP HD Audio                                            | 31        | 5.86%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 29        | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 4.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19        | 3.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 3.02%   |
| AMD Radeon High Definition Audio Controller                                | 16        | 3.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 2.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 2.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.89%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.89%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 1.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 1.51%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.32%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.76%   |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 0.76%   |
| Nvidia AD107 High Definition Audio Controller                              | 4         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.76%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 0.76%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 4         | 0.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 0.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.76%   |
| AMD FCH Azalia Controller                                                  | 4         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 78        | 32.5%   |
| SK hynix            | 42        | 17.5%   |
| Micron Technology   | 37        | 15.42%  |
| Kingston            | 25        | 10.42%  |
| Ramaxel Technology  | 10        | 4.17%   |
| Unknown             | 8         | 3.33%   |
| Crucial             | 8         | 3.33%   |
| Elpida              | 5         | 2.08%   |
| A-DATA Technology   | 5         | 2.08%   |
| Nanya Technology    | 4         | 1.67%   |
| Unknown (ABCD)      | 3         | 1.25%   |
| G.Skill             | 3         | 1.25%   |
| Patriot             | 2         | 0.83%   |
| Lexar               | 2         | 0.83%   |
| GOODRAM             | 2         | 0.83%   |
| Corsair             | 2         | 0.83%   |
| Team                | 1         | 0.42%   |
| Lexar Co Limited    | 1         | 0.42%   |
| Innodisk            | 1         | 0.42%   |
| Unknown             | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 1.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.6%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 3         | 1.2%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 1.2%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.2%    |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 3         | 1.2%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.2%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 1.2%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 3         | 1.2%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.8%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.8%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.8%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 2         | 0.8%    |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Samsung RAM M425R2GA3EB0-CWMOL 16GB SODIMM DDR5 5600MT/s         | 2         | 0.8%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.8%    |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.8%    |
| Micron RAM MTC8C1084S1SC56BD1 16GB SODIMM DDR5 5600MT/s          | 2         | 0.8%    |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s       | 2         | 0.8%    |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.8%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.8%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.8%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 77        | 38.89%  |
| DDR3   | 76        | 38.38%  |
| DDR5   | 15        | 7.58%   |
| LPDDR4 | 10        | 5.05%   |
| DDR2   | 9         | 4.55%   |
| LPDDR3 | 6         | 3.03%   |
| LPDDR5 | 3         | 1.52%   |
| SDRAM  | 1         | 0.51%   |
| DRAM   | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 183       | 93.37%  |
| Row Of Chips | 11        | 5.61%   |
| DIMM         | 1         | 0.51%   |
| Unknown      | 1         | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 89        | 41.2%   |
| 4096  | 63        | 29.17%  |
| 16384 | 36        | 16.67%  |
| 2048  | 17        | 7.87%   |
| 32768 | 6         | 2.78%   |
| 1024  | 4         | 1.85%   |
| 512   | 1         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 52        | 24.3%   |
| 3200    | 45        | 21.03%  |
| 2667    | 40        | 18.69%  |
| 1334    | 13        | 6.07%   |
| 5600    | 10        | 4.67%   |
| 2400    | 7         | 3.27%   |
| 2133    | 7         | 3.27%   |
| 1333    | 7         | 3.27%   |
| 4800    | 5         | 2.34%   |
| 667     | 5         | 2.34%   |
| 1867    | 4         | 1.87%   |
| 1067    | 4         | 1.87%   |
| 6400    | 3         | 1.4%    |
| 800     | 3         | 1.4%    |
| 4267    | 2         | 0.93%   |
| 8400    | 1         | 0.47%   |
| 4266    | 1         | 0.47%   |
| 3266    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 1066    | 1         | 0.47%   |
| 333     | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1000 | 1         | 100%    |

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
| Chicony Electronics                    | 73        | 25%     |
| IMC Networks                           | 46        | 15.75%  |
| Microdia                               | 23        | 7.88%   |
| Bison Electronics                      | 20        | 6.85%   |
| Sunplus Innovation Technology          | 18        | 6.16%   |
| Realtek Semiconductor                  | 17        | 5.82%   |
| Suyin                                  | 12        | 4.11%   |
| Luxvisions Innotech Limited            | 12        | 4.11%   |
| Quanta                                 | 10        | 3.42%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.74%   |
| Alcor Micro                            | 7         | 2.4%    |
| Syntek                                 | 6         | 2.05%   |
| Lite-On Technology                     | 6         | 2.05%   |
| Apple                                  | 6         | 2.05%   |
| Sonix Technology                       | 4         | 1.37%   |
| Silicon Motion                         | 3         | 1.03%   |
| Ricoh                                  | 2         | 0.68%   |
| OmniVision Technologies                | 2         | 0.68%   |
| Logitech                               | 2         | 0.68%   |
| Lenovo                                 | 2         | 0.68%   |
| DigiTech                               | 2         | 0.68%   |
| Unknown (3730304231393831325530)       | 1         | 0.34%   |
| SunplusIT                              | 1         | 0.34%   |
| ShineTech                              | 1         | 0.34%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.34%   |
| Primax Electronics                     | 1         | 0.34%   |
| Intel                                  | 1         | 0.34%   |
| Importek                               | 1         | 0.34%   |
| Genesys Logic                          | 1         | 0.34%   |
| Framework                              | 1         | 0.34%   |
| ALi                                    | 1         | 0.34%   |
| Acer                                   | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 26        | 8.9%    |
| IMC Networks USB2.0 HD UVC WebCam                 | 15        | 5.14%   |
| IMC Networks Integrated Camera                    | 14        | 4.79%   |
| Microdia Integrated_Webcam_HD                     | 10        | 3.42%   |
| Sunplus Integrated_Webcam_HD                      | 6         | 2.05%   |
| Realtek Integrated_Webcam_HD                      | 6         | 2.05%   |
| Bison Integrated Camera                           | 5         | 1.71%   |
| Syntek Lenovo EasyCamera                          | 4         | 1.37%   |
| Sunplus HP HD Webcam [Fixed]                      | 4         | 1.37%   |
| Quanta HD User Facing                             | 4         | 1.37%   |
| Luxvisions Innotech Limited Integrated Camera     | 4         | 1.37%   |
| Luxvisions Innotech Limited HP HD Camera          | 4         | 1.37%   |
| Lite-On Integrated Camera                         | 4         | 1.37%   |
| Sonix USB2.0 HD UVC WebCam                        | 3         | 1.03%   |
| Realtek USB Camera                                | 3         | 1.03%   |
| Microdia Integrated Webcam                        | 3         | 1.03%   |
| IMC Networks UVC VGA Webcam                       | 3         | 1.03%   |
| IMC Networks 2M Integrated Webcam                 | 3         | 1.03%   |
| Chicony VGA WebCam                                | 3         | 1.03%   |
| Chicony USB2.0 HD UVC WebCam                      | 3         | 1.03%   |
| Chicony ThinkPad T490 Webcam                      | 3         | 1.03%   |
| Chicony HD WebCam                                 | 3         | 1.03%   |
| Bison Lenovo Integrated Webcam                    | 3         | 1.03%   |
| Alcor Micro USB 2.0 Camera                        | 3         | 1.03%   |
| Suyin Laptop_Integrated_Webcam_HD                 | 2         | 0.68%   |
| Suyin HP Webcam                                   | 2         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 2         | 0.68%   |
| Sunplus HD WebCam                                 | 2         | 0.68%   |
| Sunplus Asus Webcam                               | 2         | 0.68%   |
| Silicon Motion Lenovo EasyCamera                  | 2         | 0.68%   |
| Quanta HP Webcam                                  | 2         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD              | 2         | 0.68%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 0.68%   |
| IMC Networks VGA UVC WebCam                       | 2         | 0.68%   |
| IMC Networks USB2.0 UVC HD Webcam                 | 2         | 0.68%   |
| Chicony Webcam                                    | 2         | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam                     | 2         | 0.68%   |
| Chicony USB2.0 0.3M UVC WebCam                    | 2         | 0.68%   |
| Chicony HP Webcam [2 MP Macro]                    | 2         | 0.68%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed]  | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 26        | 37.68%  |
| Validity Sensors           | 21        | 30.43%  |
| Shenzhen Goodix Technology | 8         | 11.59%  |
| Elan Microelectronics      | 5         | 7.25%   |
| AuthenTec                  | 4         | 5.8%    |
| STMicroelectronics         | 2         | 2.9%    |
| Upek                       | 1         | 1.45%   |
| Samsung Electronics        | 1         | 1.45%   |
| LighTuning Technology      | 1         | 1.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 13        | 18.84%  |
| Validity Sensors VFS471 Fingerprint Reader                  | 5         | 7.25%   |
| Synaptics UWP WBDI Device                                   | 4         | 5.8%    |
| Shenzhen Goodix Fingerprint Reader                          | 4         | 5.8%    |
| Elan ELAN:Fingerprint                                       | 4         | 5.8%    |
| Validity Sensors VFS495 Fingerprint Reader                  | 3         | 4.35%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 3         | 4.35%   |
| Shenzhen Goodix  Fingerprint Device                         | 3         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 2         | 2.9%    |
| Validity Sensors Fingerprint scanner                        | 2         | 2.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 2         | 2.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 2         | 2.9%    |
| STMicroelectronics Fingerprint Reader                       | 2         | 2.9%    |
| AuthenTec AES2810                                           | 2         | 2.9%    |
| AuthenTec AES1600                                           | 2         | 2.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 1.45%   |
| Validity Sensors VFS491                                     | 1         | 1.45%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 1         | 1.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 1.45%   |
| Validity Sensors Synaptics WBDI                             | 1         | 1.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 1.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 1         | 1.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint    | 1         | 1.45%   |
| Synaptics Fingerprint reader [HP G6]                        | 1         | 1.45%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 1.45%   |
| Samsung Fingerprint Sensor Device - 730B                    | 1         | 1.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 1.45%   |
| Elan ELAN:ARM-M4                                            | 1         | 1.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 15        | 55.56%  |
| Broadcom              | 9         | 33.33%  |
| Gemalto (was Gemplus) | 2         | 7.41%   |
| Upek                  | 1         | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 55.56%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 7.41%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 7.41%   |
| Broadcom 5880                                                                | 2         | 7.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.7%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.7%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 208       | 60.47%  |
| 1     | 102       | 29.65%  |
| 2     | 24        | 6.98%   |
| 3     | 8         | 2.33%   |
| 7     | 1         | 0.29%   |
| 4     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 67        | 37.22%  |
| Graphics card            | 38        | 21.11%  |
| Chipcard                 | 25        | 13.89%  |
| Net/wireless             | 13        | 7.22%   |
| Multimedia controller    | 9         | 5%      |
| Bluetooth                | 8         | 4.44%   |
| Communication controller | 4         | 2.22%   |
| Card reader              | 4         | 2.22%   |
| Camera                   | 4         | 2.22%   |
| Storage                  | 2         | 1.11%   |
| Sound                    | 2         | 1.11%   |
| Net/ethernet             | 2         | 1.11%   |
| Storage/raid             | 1         | 0.56%   |
| Flash memory             | 1         | 0.56%   |

