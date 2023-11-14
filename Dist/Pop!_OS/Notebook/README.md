Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 7919

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Y720-15IKB 80VR             | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Google        | Taeko                       | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| System76      | Lemur Pro                   | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| System76      | Lemur Pro                   | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| HP            | 655                         | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| HP            | ProBook 6450b               | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [dba91e5612](https://linux-hardware.org/?probe=dba91e5612) | Nov 01, 2023 |
| HP            | ENVY 15                     | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [c1e44a55c8](https://linux-hardware.org/?probe=c1e44a55c8) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [84ca0a285d](https://linux-hardware.org/?probe=84ca0a285d) | Nov 01, 2023 |
| Dell          | XPS 15 9520                 | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| System76      | Lemur Pro                   | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [f08e4e21a0](https://linux-hardware.org/?probe=f08e4e21a0) | Nov 01, 2023 |
| HUAWEI        | CREF-XX                     | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [cb013304f5](https://linux-hardware.org/?probe=cb013304f5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [d6ac483e43](https://linux-hardware.org/?probe=d6ac483e43) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [ee528fce07](https://linux-hardware.org/?probe=ee528fce07) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [4e0042e20c](https://linux-hardware.org/?probe=4e0042e20c) | Oct 31, 2023 |
| Acer          | Aspire E5-553G              | [7c76f143a4](https://linux-hardware.org/?probe=7c76f143a4) | Oct 31, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| HP            | Dev One Notebook PC         | [d5ace42b13](https://linux-hardware.org/?probe=d5ace42b13) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [d51c491524](https://linux-hardware.org/?probe=d51c491524) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| System76      | Adder WS                    | [57478f4561](https://linux-hardware.org/?probe=57478f4561) | Oct 30, 2023 |
| System76      | Adder WS                    | [a10fcac3f4](https://linux-hardware.org/?probe=a10fcac3f4) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Apple         | MacBookPro5,5               | [2815a5477f](https://linux-hardware.org/?probe=2815a5477f) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d621a72336](https://linux-hardware.org/?probe=d621a72336) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [57e3abc23d](https://linux-hardware.org/?probe=57e3abc23d) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| Lenovo        | Z50-70 20354                | [2e5ee0032d](https://linux-hardware.org/?probe=2e5ee0032d) | Oct 27, 2023 |
| System76      | Lemur Pro                   | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| System76      | Darter Pro                  | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | OMEN LAPTOP - 15-EK0013D... | [0c582fd597](https://linux-hardware.org/?probe=0c582fd597) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f0641b8822](https://linux-hardware.org/?probe=f0641b8822) | Oct 26, 2023 |
| Haier         | U1520SD                     | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Dell          | Latitude E6530              | [ec57b86fe6](https://linux-hardware.org/?probe=ec57b86fe6) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| Panasonic     | CF-31SBM08DM                | [820f042ba6](https://linux-hardware.org/?probe=820f042ba6) | Oct 26, 2023 |
| Haier         | U1520SD                     | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Dell          | Latitude E7240              | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47fdb21256](https://linux-hardware.org/?probe=47fdb21256) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | [7e9d761b35](https://linux-hardware.org/?probe=7e9d761b35) | Oct 23, 2023 |
| MSI           | Sword 15 A11UD              | [d07a7c777c](https://linux-hardware.org/?probe=d07a7c777c) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [73c1b49eab](https://linux-hardware.org/?probe=73c1b49eab) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [b6169d3a96](https://linux-hardware.org/?probe=b6169d3a96) | Oct 23, 2023 |
| ASUSTek       | G750JW                      | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | Latitude 5520               | [f5664b02d2](https://linux-hardware.org/?probe=f5664b02d2) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | [010dd78352](https://linux-hardware.org/?probe=010dd78352) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | [e51b067a88](https://linux-hardware.org/?probe=e51b067a88) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| ASUSTek       | X551MA                      | [6ee41b351a](https://linux-hardware.org/?probe=6ee41b351a) | Oct 20, 2023 |
| Acer          | Aspire 5253                 | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | Latitude 5520               | [281fdb7e86](https://linux-hardware.org/?probe=281fdb7e86) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | [7148bf6db9](https://linux-hardware.org/?probe=7148bf6db9) | Oct 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | [9cbbb0364b](https://linux-hardware.org/?probe=9cbbb0364b) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [b2cba37968](https://linux-hardware.org/?probe=b2cba37968) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| System76      | Gazelle                     | [061012cdb0](https://linux-hardware.org/?probe=061012cdb0) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| HP            | 250 G4                      | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| HP            | Laptop 15-dw4xxx            | [44ba7f4015](https://linux-hardware.org/?probe=44ba7f4015) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| HP            | ProBook 4730s               | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| System76      | Lemur Pro                   | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| Acer          | Aspire A314-23P             | [142bc36a3f](https://linux-hardware.org/?probe=142bc36a3f) | Oct 14, 2023 |
| Notebook      | P9XXEN_EF_ED                | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| Acer          | Aspire E1-571               | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| Dell          | Inspiron 16 7610            | [ee849775df](https://linux-hardware.org/?probe=ee849775df) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| Gateway       | NE570                       | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| Dell          | Inspiron 15 3525            | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Lenovo        | ThinkPad P1 20MES05502      | [869264ad64](https://linux-hardware.org/?probe=869264ad64) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6591296a12](https://linux-hardware.org/?probe=6591296a12) | Oct 10, 2023 |
| Gigabyte      | AORUS 17H BXF               | [4fcbae7a75](https://linux-hardware.org/?probe=4fcbae7a75) | Oct 10, 2023 |
| System76      | Darter Pro                  | [71e1a67b2a](https://linux-hardware.org/?probe=71e1a67b2a) | Oct 10, 2023 |
| Razer         | Blade                       | [22de5dfe50](https://linux-hardware.org/?probe=22de5dfe50) | Oct 09, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| Dell          | Inspiron 7375               | [3b54f5530b](https://linux-hardware.org/?probe=3b54f5530b) | Oct 08, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | [36d48fe6f7](https://linux-hardware.org/?probe=36d48fe6f7) | Oct 07, 2023 |
| System76      | Serval WS                   | [509cc872ee](https://linux-hardware.org/?probe=509cc872ee) | Oct 07, 2023 |
| Alienware     | m15 R7                      | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| HP            | EliteBook 850 G3            | [f773c3004e](https://linux-hardware.org/?probe=f773c3004e) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| MSI           | GE62 2QF                    | [cd73adb01d](https://linux-hardware.org/?probe=cd73adb01d) | Oct 07, 2023 |
| HP            | Laptop 15-db1xxx            | [687a37a00f](https://linux-hardware.org/?probe=687a37a00f) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| System76      | Serval WS                   | [f8e3cd9fd0](https://linux-hardware.org/?probe=f8e3cd9fd0) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [b6caf35101](https://linux-hardware.org/?probe=b6caf35101) | Oct 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3e6f44ce5c](https://linux-hardware.org/?probe=3e6f44ce5c) | Oct 05, 2023 |
| Google        | Morphius                    | [735ed70d9c](https://linux-hardware.org/?probe=735ed70d9c) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [34ff66e3a9](https://linux-hardware.org/?probe=34ff66e3a9) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [314a6f2edf](https://linux-hardware.org/?probe=314a6f2edf) | Oct 05, 2023 |
| Dell          | Inspiron 5490               | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [234f939987](https://linux-hardware.org/?probe=234f939987) | Oct 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [1dcdef2d17](https://linux-hardware.org/?probe=1dcdef2d17) | Oct 04, 2023 |
| Dell          | Latitude 7400               | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Dell          | Inspiron 3543               | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G74Sx                       | [2e57173dd9](https://linux-hardware.org/?probe=2e57173dd9) | Oct 02, 2023 |
| System76      | Lemur Pro                   | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [3bb0e0c792](https://linux-hardware.org/?probe=3bb0e0c792) | Oct 01, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| HP            | 250 G4                      | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| MSI           | Cyborg 15 A12VF             | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Dell          | Latitude E7440              | [8e74ff2f99](https://linux-hardware.org/?probe=8e74ff2f99) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| Positivo      | C14CR01                     | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| System76      | Oryx Pro                    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| HUAWEI        | NbDE-WXX9                   | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| HP            | EliteBook 725 G4            | [1ef194c5fd](https://linux-hardware.org/?probe=1ef194c5fd) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| System76      | Darter Pro                  | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| HP            | Dev One Notebook PC         | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| HP            | Laptop 14-dk0xxx            | [57b82728d8](https://linux-hardware.org/?probe=57b82728d8) | Sep 08, 2023 |
| HP            | EliteBook 745 G5            | [05d61b5c23](https://linux-hardware.org/?probe=05d61b5c23) | Sep 08, 2023 |
| MSI           | P65 Creator 8RD             | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| HP            | Laptop 15-dy2xxx            | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| Alienware     | m15 R7                      | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Apple         | MacBookPro11,3              | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Google        | Kefka                       | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Dell          | Latitude 5330               | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| HP            | ProBook 4730s               | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Dell          | Latitude 7430               | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| HP            | Pavilion Notebook           | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| Samsung       | 750TDA                      | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| System76      | Darter Pro                  | [a244cb8283](https://linux-hardware.org/?probe=a244cb8283) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| HP            | ProBook 4730s               | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| System76      | Oryx Pro                    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| System76      | Kudu Pro                    | [0fc481c5fc](https://linux-hardware.org/?probe=0fc481c5fc) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| System76      | Lemur Pro                   | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| System76      | Galago Pro                  | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| HP            | ProBook 4540s               | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Acer          | Nitro AN517-55              | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| System76      | Darter Pro                  | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Alienware     | 14                          | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ec7a911951](https://linux-hardware.org/?probe=ec7a911951) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| System76      | Oryx Pro                    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| Notebook      | 1745                        | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Dell          | Latitude 5430               | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| System76      | Bonobo WS                   | [64ba21a272](https://linux-hardware.org/?probe=64ba21a272) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| Dell          | Latitude 5490               | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASUSTek       | K95VM                       | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Dell          | Latitude E7440              | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| System76      | Darter Pro                  | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| Dell          | Precision 3550              | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | Latitude 3500               | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| Dell          | Latitude 5410               | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Dell          | Latitude 5520               | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| LG Electro... | S425-G.BC31P1               | [2f54821f3f](https://linux-hardware.org/?probe=2f54821f3f) | Jul 21, 2023 |
| Dell          | Precision 7530              | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Notebook      | NH5x_7xDPx                  | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [86f515ebce](https://linux-hardware.org/?probe=86f515ebce) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4abe81669a](https://linux-hardware.org/?probe=4abe81669a) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| Acer          | Predator PT515-51           | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Dell          | XPS 17 9720                 | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Toshiba       | IS 1413G                    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Positivo      | Mobile                      | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| HP            | Notebook                    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| Acer          | Swift SF314-512             | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| System76      | Lemur Pro                   | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| Avell High... | A70 HYB                     | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| Dell          | Latitude E7470              | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Acer          | Aspire 7750                 | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| ASUSTek       | UX32LN                      | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| Dell          | Latitude E7240              | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| Machcreato... | 14                          | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| Dell          | Latitude E6420              | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Machcreato... | 14                          | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| Dell          | Inspiron 5437               | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| Apple         | MacBookPro9,2               | [6964a1da79](https://linux-hardware.org/?probe=6964a1da79) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| Toshiba       | IS 1413G                    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| Toshiba       | Satellite P755              | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| Avell High... | A70 MOB                     | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| Apple         | MacBookAir5,1               | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| System76      | Adder WS                    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | X502CA                      | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| HP            | Spectre Pro x360 G1         | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| Lenovo        | Unknown                     | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Reliance C... | R141TL5                     | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| Dell          | Inspiron 5559               | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| Dell          | Inspiron 14 5408            | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [dd1e6376c2](https://linux-hardware.org/?probe=dd1e6376c2) | May 17, 2023 |
| Google        | Blorb                       | [7537bc5890](https://linux-hardware.org/?probe=7537bc5890) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| Apple         | MacBookAir7,2               | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| HP            | Pavilion dv6                | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| ASUSTek       | X541UJ                      | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| Dell          | Inspiron 3583               | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | [c74505560b](https://linux-hardware.org/?probe=c74505560b) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Toshiba       | TECRA R850                  | [e48ff4432d](https://linux-hardware.org/?probe=e48ff4432d) | May 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [effc7c876e](https://linux-hardware.org/?probe=effc7c876e) | May 14, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| System76      | Oryx Pro                    | [4b3677634e](https://linux-hardware.org/?probe=4b3677634e) | May 13, 2023 |
| HP            | Pavilion dv6                | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Dell          | G7 7700                     | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| Gigabyte      | P34V7                       | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| System76      | Galago Pro                  | [a30efb5622](https://linux-hardware.org/?probe=a30efb5622) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Dell          | Precision 3571              | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| System76      | Gazelle                     | [bd4e912b20](https://linux-hardware.org/?probe=bd4e912b20) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7dd8e30770](https://linux-hardware.org/?probe=7dd8e30770) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| ASUSTek       | ZenBook UX431FN             | [ee40bf2168](https://linux-hardware.org/?probe=ee40bf2168) | May 12, 2023 |
| System76      | Gazelle                     | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [f54531cd16](https://linux-hardware.org/?probe=f54531cd16) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| Dell          | Inspiron 5566               | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [4d9a7df494](https://linux-hardware.org/?probe=4d9a7df494) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2522AA6       | [82755e3688](https://linux-hardware.org/?probe=82755e3688) | May 08, 2023 |
| Acer          | Aspire A715-72G             | [da1c6920b6](https://linux-hardware.org/?probe=da1c6920b6) | May 08, 2023 |
| Alienware     | Area-51m R2 A00             | [3cc417c9d9](https://linux-hardware.org/?probe=3cc417c9d9) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion dv6                | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Notebook      | N141CU                      | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [078d3ae45f](https://linux-hardware.org/?probe=078d3ae45f) | May 06, 2023 |
| Notebook      | P15SM                       | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001HUS    | [4bad3ee37e](https://linux-hardware.org/?probe=4bad3ee37e) | May 06, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Dell          | XPS 15 9510                 | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Positivo      | N4350                       | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| ASUSTek       | ZenBook UX431FN             | [3194ab7fa2](https://linux-hardware.org/?probe=3194ab7fa2) | May 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [eaf28f6af4](https://linux-hardware.org/?probe=eaf28f6af4) | May 05, 2023 |
| Toshiba       | TECRA R850                  | [bb41171733](https://linux-hardware.org/?probe=bb41171733) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [5022c3993a](https://linux-hardware.org/?probe=5022c3993a) | May 04, 2023 |
| Dell          | Latitude 7370               | [6beab237df](https://linux-hardware.org/?probe=6beab237df) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| HP            | Unknown                     | [311e275897](https://linux-hardware.org/?probe=311e275897) | May 04, 2023 |
| MSI           | GV62 7RE                    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| System76      | Oryx Pro                    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| HP            | Unknown                     | [122c1783c0](https://linux-hardware.org/?probe=122c1783c0) | May 03, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [9322206a7d](https://linux-hardware.org/?probe=9322206a7d) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| System76      | Oryx Pro                    | [8bd4f39eaa](https://linux-hardware.org/?probe=8bd4f39eaa) | May 02, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| System76      | Gazelle                     | [8a8de3e027](https://linux-hardware.org/?probe=8a8de3e027) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [3c82fea068](https://linux-hardware.org/?probe=3c82fea068) | May 01, 2023 |
| Dell          | Precision 5530              | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| Apple         | MacBookPro11,3              | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| HP            | ENVY 15                     | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| System76      | Gazelle                     | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| Alienware     | 13 R3                       | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| HP            | ZBook 15                    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Dell          | Precision 5550              | [1546772c9f](https://linux-hardware.org/?probe=1546772c9f) | Apr 14, 2023 |
| Dell          | Latitude E5440              | [a827218c2e](https://linux-hardware.org/?probe=a827218c2e) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| HP            | Laptop 15z-fc000            | [df47336192](https://linux-hardware.org/?probe=df47336192) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Toshiba       | IS 1413G                    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| System76      | Pangolin                    | [1750f20c8d](https://linux-hardware.org/?probe=1750f20c8d) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [1f12146974](https://linux-hardware.org/?probe=1f12146974) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9aadb88a2d](https://linux-hardware.org/?probe=9aadb88a2d) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| Dell          | G3 3579                     | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Timi          | TM1707                      | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Samsung       | 760XDA                      | [bdc1648c05](https://linux-hardware.org/?probe=bdc1648c05) | Apr 11, 2023 |
| Dell          | Latitude 5590               | [f8f0f0125f](https://linux-hardware.org/?probe=f8f0f0125f) | Apr 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [c48286f8a2](https://linux-hardware.org/?probe=c48286f8a2) | Apr 10, 2023 |
| Apple         | MacBookPro11,4              | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | ProBook 640 G1              | [769d886cc9](https://linux-hardware.org/?probe=769d886cc9) | Apr 05, 2023 |
| HP            | ProBook 640 G1              | [de7d3ba0c0](https://linux-hardware.org/?probe=de7d3ba0c0) | Apr 05, 2023 |
| Razer         | Blade                       | [351fe907cb](https://linux-hardware.org/?probe=351fe907cb) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Laptop 14-dq0xxx            | [ba87782532](https://linux-hardware.org/?probe=ba87782532) | Apr 05, 2023 |
| Lenovo        | Edge 15 80K9                | [911d261c1b](https://linux-hardware.org/?probe=911d261c1b) | Apr 05, 2023 |
| ASUSTek       | N76VZ                       | [d87006e429](https://linux-hardware.org/?probe=d87006e429) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Dell          | Inspiron 7375               | [0d8465f75c](https://linux-hardware.org/?probe=0d8465f75c) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| ASUSTek       | E201NA                      | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| Acer          | Swift SF314-43              | [a964b0aa55](https://linux-hardware.org/?probe=a964b0aa55) | Apr 04, 2023 |
| Razer         | Blade Stealth               | [2cf4a53eb5](https://linux-hardware.org/?probe=2cf4a53eb5) | Apr 04, 2023 |
| Dell          | Latitude E7240              | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Unknown       | Unknown                     | [190b5364e1](https://linux-hardware.org/?probe=190b5364e1) | Apr 03, 2023 |
| Unknown       | Unknown                     | [a6a766a40a](https://linux-hardware.org/?probe=a6a766a40a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9880810adc](https://linux-hardware.org/?probe=9880810adc) | Apr 03, 2023 |
| MSI           | GV62 7RE                    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 2068      | 36.38%  |
| Pop!_OS 20.04 | 1153      | 20.29%  |
| Pop!_OS 21.04 | 960       | 16.89%  |
| Pop!_OS 20.10 | 856       | 15.06%  |
| Pop!_OS 21.10 | 600       | 10.56%  |
| Pop!_OS 19.10 | 30        | 0.53%   |
| Pop!_OS 18.04 | 7         | 0.12%   |
| Pop!_OS 19.04 | 6         | 0.11%   |
| Pop!_OS 18.10 | 4         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 5421      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 468       | 7.65%   |
| 5.11.0-7620-generic      | 443       | 7.24%   |
| 5.8.0-7630-generic       | 381       | 6.23%   |
| 5.4.0-7634-generic       | 346       | 5.66%   |
| 5.19.0-76051900-generic  | 274       | 4.48%   |
| 6.0.12-76060006-generic  | 265       | 4.33%   |
| 5.13.0-7614-generic      | 262       | 4.28%   |
| 5.4.0-7642-generic       | 256       | 4.19%   |
| 5.17.5-76051705-generic  | 252       | 4.12%   |
| 5.8.0-7642-generic       | 242       | 3.96%   |
| 5.11.0-7614-generic      | 227       | 3.71%   |
| 5.13.0-7620-generic      | 218       | 3.56%   |
| 6.4.6-76060406-generic   | 183       | 2.99%   |
| 6.0.6-76060006-generic   | 162       | 2.65%   |
| 5.15.15-76051515-generic | 154       | 2.52%   |
| 5.16.11-76051611-generic | 139       | 2.27%   |
| 5.11.0-7612-generic      | 128       | 2.09%   |
| 5.15.5-76051505-generic  | 123       | 2.01%   |
| 5.18.10-76051810-generic | 122       | 1.99%   |
| 5.17.15-76051715-generic | 106       | 1.73%   |
| 5.8.0-7625-generic       | 105       | 1.72%   |
| 5.11.0-7633-generic      | 99        | 1.62%   |
| 5.16.19-76051619-generic | 98        | 1.6%    |
| 5.15.8-76051508-generic  | 98        | 1.6%    |
| 5.16.15-76051615-generic | 92        | 1.5%    |
| 5.4.0-7626-generic       | 84        | 1.37%   |
| 6.2.0-76060200-generic   | 77        | 1.26%   |
| 5.15.11-76051511-generic | 63        | 1.03%   |
| 6.0.2-76060002-generic   | 59        | 0.96%   |
| 5.15.23-76051523-generic | 56        | 0.92%   |
| 6.5.6-76060506-generic   | 55        | 0.9%    |
| 6.1.11-76060111-generic  | 54        | 0.88%   |
| 6.5.4-76060504-generic   | 51        | 0.83%   |
| 5.4.0-7625-generic       | 44        | 0.72%   |
| 5.4.0-7629-generic       | 35        | 0.57%   |
| 6.0.3-76060003-generic   | 24        | 0.39%   |
| 5.19.16-76051916-generic | 21        | 0.34%   |
| 5.3.0-7625-generic       | 10        | 0.16%   |
| 6.0.12-76060012-generic  | 6         | 0.1%    |
| 5.3.0-7648-generic       | 6         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 875       | 14.55%  |
| 5.4.0   | 744       | 12.37%  |
| 5.8.0   | 698       | 11.61%  |
| 6.2.6   | 469       | 7.8%    |
| 5.13.0  | 467       | 7.77%   |
| 5.19.0  | 277       | 4.61%   |
| 6.0.12  | 271       | 4.51%   |
| 5.17.5  | 255       | 4.24%   |
| 6.4.6   | 183       | 3.04%   |
| 6.0.6   | 162       | 2.69%   |
| 5.15.15 | 154       | 2.56%   |
| 5.16.11 | 139       | 2.31%   |
| 5.15.5  | 123       | 2.05%   |
| 5.18.10 | 122       | 2.03%   |
| 5.17.15 | 106       | 1.76%   |
| 5.16.19 | 98        | 1.63%   |
| 5.15.8  | 98        | 1.63%   |
| 5.16.15 | 92        | 1.53%   |
| 6.2.0   | 77        | 1.28%   |
| 5.15.11 | 63        | 1.05%   |
| 6.0.2   | 60        | 1%      |
| 5.15.23 | 56        | 0.93%   |
| 6.5.6   | 55        | 0.91%   |
| 6.1.11  | 54        | 0.9%    |
| 6.5.4   | 51        | 0.85%   |
| 5.3.0   | 32        | 0.53%   |
| 6.0.3   | 24        | 0.4%    |
| 5.19.16 | 21        | 0.35%   |
| 5.0.0   | 6         | 0.1%    |
| 4.18.0  | 6         | 0.1%    |
| 5.7.0   | 4         | 0.07%   |
| 5.15.0  | 4         | 0.07%   |
| 5.8.6   | 3         | 0.05%   |
| 5.8.11  | 3         | 0.05%   |
| 5.7.1   | 3         | 0.05%   |
| 5.14.0  | 3         | 0.05%   |
| 5.12.14 | 3         | 0.05%   |
| 5.10.0  | 3         | 0.05%   |
| 6.5.7   | 2         | 0.03%   |
| 6.4.0   | 2         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 881       | 14.79%  |
| 5.4     | 745       | 12.51%  |
| 5.8     | 712       | 11.95%  |
| 6.2     | 547       | 9.18%   |
| 6.0     | 503       | 8.44%   |
| 5.15    | 494       | 8.29%   |
| 5.13    | 478       | 8.02%   |
| 5.17    | 361       | 6.06%   |
| 5.16    | 327       | 5.49%   |
| 5.19    | 300       | 5.04%   |
| 6.4     | 187       | 3.14%   |
| 5.18    | 126       | 2.12%   |
| 6.5     | 111       | 1.86%   |
| 6.1     | 61        | 1.02%   |
| 5.3     | 32        | 0.54%   |
| 5.10    | 18        | 0.3%    |
| 5.12    | 13        | 0.22%   |
| 5.7     | 11        | 0.18%   |
| 5.14    | 11        | 0.18%   |
| 5.9     | 9         | 0.15%   |
| 6.3     | 7         | 0.12%   |
| 5.6     | 7         | 0.12%   |
| 4.18    | 7         | 0.12%   |
| 5.0     | 6         | 0.1%    |
| 4.15    | 2         | 0.03%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 5421      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 5251      | 96.4%   |
| Unknown         | 46        | 0.84%   |
| KDE5            | 45        | 0.83%   |
| KDE             | 25        | 0.46%   |
| X-Cinnamon      | 19        | 0.35%   |
| GNOME Flashback | 12        | 0.22%   |
| XFCE            | 9         | 0.17%   |
| MATE            | 9         | 0.17%   |
| LXQt            | 9         | 0.17%   |
| Unity           | 7         | 0.13%   |
| Cinnamon        | 7         | 0.13%   |
| Budgie          | 4         | 0.07%   |
| awesome         | 2         | 0.04%   |
| i3              | 1         | 0.02%   |
| Deepin          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 5231      | 95.93%  |
| Wayland | 194       | 3.56%   |
| Unknown | 20        | 0.37%   |
| Tty     | 8         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4085      | 74.46%  |
| GDM     | 776       | 14.15%  |
| GDM3    | 609       | 11.1%   |
| SDDM    | 9         | 0.16%   |
| TDM     | 5         | 0.09%   |
| LightDM | 2         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3156      | 57.82%  |
| pt_BR   | 393       | 7.2%    |
| en_GB   | 378       | 6.93%   |
| de_DE   | 231       | 4.23%   |
| C       | 144       | 2.64%   |
| fr_FR   | 110       | 2.02%   |
| en_AU   | 110       | 2.02%   |
| it_IT   | 109       | 2%      |
| es_ES   | 108       | 1.98%   |
| en_CA   | 94        | 1.72%   |
| ru_RU   | 75        | 1.37%   |
| Unknown | 58        | 1.06%   |
| pl_PL   | 50        | 0.92%   |
| pt_PT   | 47        | 0.86%   |
| sv_SE   | 34        | 0.62%   |
| en_IN   | 34        | 0.62%   |
| nb_NO   | 25        | 0.46%   |
| nl_NL   | 23        | 0.42%   |
| es_MX   | 20        | 0.37%   |
| en_ZA   | 20        | 0.37%   |
| tr_TR   | 18        | 0.33%   |
| fi_FI   | 18        | 0.33%   |
| en_NZ   | 17        | 0.31%   |
| fr_CA   | 12        | 0.22%   |
| es_AR   | 11        | 0.2%    |
| en_IE   | 11        | 0.2%    |
| en_DK   | 11        | 0.2%    |
| cs_CZ   | 11        | 0.2%    |
| da_DK   | 9         | 0.16%   |
| hu_HU   | 8         | 0.15%   |
| hr_HR   | 8         | 0.15%   |
| es_CL   | 8         | 0.15%   |
| de_CH   | 8         | 0.15%   |
| sk_SK   | 6         | 0.11%   |
| ro_RO   | 6         | 0.11%   |
| zh_CN   | 5         | 0.09%   |
| es_CO   | 5         | 0.09%   |
| en_IL   | 5         | 0.09%   |
| de_AT   | 5         | 0.09%   |
| nl_BE   | 4         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3821      | 69.41%  |
| EFI  | 1684      | 30.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5196      | 95.5%   |
| Btrfs   | 134       | 2.46%   |
| Overlay | 84        | 1.54%   |
| Xfs     | 19        | 0.35%   |
| Unknown | 7         | 0.13%   |
| Zfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4047      | 73.92%  |
| GPT     | 1310      | 23.93%  |
| MBR     | 118       | 2.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5301      | 97.5%   |
| Yes       | 136       | 2.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4934      | 90.6%   |
| Yes       | 512       | 9.4%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1069      | 19.72%  |
| Dell                   | 935       | 17.25%  |
| Hewlett-Packard        | 750       | 13.84%  |
| ASUSTek Computer       | 631       | 11.64%  |
| Acer                   | 421       | 7.77%   |
| Apple                  | 323       | 5.96%   |
| System76               | 200       | 3.69%   |
| MSI                    | 181       | 3.34%   |
| Toshiba                | 107       | 1.97%   |
| Samsung Electronics    | 95        | 1.75%   |
| HUAWEI                 | 66        | 1.22%   |
| Sony                   | 50        | 0.92%   |
| Notebook               | 50        | 0.92%   |
| Google                 | 44        | 0.81%   |
| Alienware              | 42        | 0.77%   |
| Positivo               | 30        | 0.55%   |
| Fujitsu                | 30        | 0.55%   |
| Razer                  | 26        | 0.48%   |
| Gigabyte Technology    | 20        | 0.37%   |
| Timi                   | 19        | 0.35%   |
| PC Specialist          | 17        | 0.31%   |
| Unknown                | 15        | 0.28%   |
| TUXEDO                 | 14        | 0.26%   |
| Framework              | 14        | 0.26%   |
| LG Electronics         | 13        | 0.24%   |
| GPU Company            | 13        | 0.24%   |
| Medion                 | 12        | 0.22%   |
| Packard Bell           | 11        | 0.2%    |
| Avell High Performance | 11        | 0.2%    |
| Teclast                | 7         | 0.13%   |
| Schenker               | 7         | 0.13%   |
| Panasonic              | 7         | 0.13%   |
| HONOR                  | 7         | 0.13%   |
| Gateway                | 7         | 0.13%   |
| Eluktronics            | 7         | 0.13%   |
| Clevo                  | 7         | 0.13%   |
| Intel                  | 6         | 0.11%   |
| SLIMBOOK               | 5         | 0.09%   |
| Chuwi                  | 5         | 0.09%   |
| Quanta                 | 4         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 48        | 0.89%   |
| System76 Lemur Pro                        | 40        | 0.74%   |
| Dell XPS 15 7590                          | 33        | 0.61%   |
| Unknown                                   | 30        | 0.55%   |
| System76 Gazelle                          | 29        | 0.53%   |
| Apple MacBookPro9,2                       | 27        | 0.5%    |
| System76 Galago Pro                       | 23        | 0.42%   |
| Apple MacBookPro8,1                       | 23        | 0.42%   |
| Apple MacBookPro12,1                      | 23        | 0.42%   |
| Dell XPS 15 9500                          | 22        | 0.41%   |
| System76 Darter Pro                       | 21        | 0.39%   |
| Apple MacBookAir7,2                       | 21        | 0.39%   |
| HP Pavilion Notebook                      | 20        | 0.37%   |
| HP Notebook                               | 20        | 0.37%   |
| Apple MacBookAir6,2                       | 19        | 0.35%   |
| HP Pavilion 15                            | 18        | 0.33%   |
| HP Pavilion dv6                           | 16        | 0.3%    |
| Dell XPS 15 9570                          | 15        | 0.28%   |
| Dell XPS 15 9560                          | 15        | 0.28%   |
| Apple MacBookPro7,1                       | 15        | 0.28%   |
| Lenovo IdeaPad S145-15API 81V7            | 14        | 0.26%   |
| Dell Latitude E6420                       | 14        | 0.26%   |
| Apple MacBookPro5,5                       | 14        | 0.26%   |
| Apple MacBookPro11,3                      | 13        | 0.24%   |
| Dell XPS 17 9700                          | 12        | 0.22%   |
| Dell Latitude E7240                       | 12        | 0.22%   |
| Acer Aspire E5-575G                       | 12        | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81FE             | 11        | 0.2%    |
| Lenovo IdeaPad 330-15IKB 81DE             | 11        | 0.2%    |
| HP Pavilion Laptop 15-cw1xxx              | 11        | 0.2%    |
| HP Pavilion g6                            | 11        | 0.2%    |
| HP Dev One Notebook PC                    | 11        | 0.2%    |
| Framework Laptop                          | 11        | 0.2%    |
| Dell XPS 13 9380                          | 11        | 0.2%    |
| Dell XPS 13 9370                          | 11        | 0.2%    |
| ASUS TUF Gaming FX505DT_FX505DT           | 11        | 0.2%    |
| Apple MacBookPro10,1                      | 11        | 0.2%    |
| Apple MacBook5,1                          | 11        | 0.2%    |
| Samsung 340XAA/350XAA/550XAA              | 10        | 0.18%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 10        | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 518       | 9.56%   |
| Dell Inspiron      | 299       | 5.52%   |
| Lenovo IdeaPad     | 295       | 5.44%   |
| Acer Aspire        | 286       | 5.28%   |
| Dell Latitude      | 228       | 4.21%   |
| Dell XPS           | 199       | 3.67%   |
| HP Pavilion        | 178       | 3.28%   |
| HP EliteBook       | 117       | 2.16%   |
| ASUS VivoBook      | 110       | 2.03%   |
| HP Laptop          | 109       | 2.01%   |
| ASUS ROG           | 95        | 1.75%   |
| Toshiba Satellite  | 92        | 1.7%    |
| HP ProBook         | 83        | 1.53%   |
| Lenovo Legion      | 81        | 1.49%   |
| Dell Precision     | 67        | 1.24%   |
| ASUS ASUS          | 53        | 0.98%   |
| Dell Vostro        | 52        | 0.96%   |
| Acer Nitro         | 51        | 0.94%   |
| System76 Oryx      | 48        | 0.89%   |
| System76 Lemur     | 43        | 0.79%   |
| Apple MacBookPro11 | 41        | 0.76%   |
| Acer Swift         | 40        | 0.74%   |
| HP ENVY            | 36        | 0.66%   |
| ASUS ZenBook       | 36        | 0.66%   |
| Apple MacBookPro9  | 34        | 0.63%   |
| HP OMEN            | 33        | 0.61%   |
| ASUS TUF           | 33        | 0.61%   |
| Apple MacBookPro8  | 32        | 0.59%   |
| System76 Gazelle   | 31        | 0.57%   |
| HP ZBook           | 31        | 0.57%   |
| Unknown            | 30        | 0.55%   |
| Lenovo ThinkBook   | 29        | 0.53%   |
| Apple MacBookPro5  | 28        | 0.52%   |
| System76 Galago    | 26        | 0.48%   |
| Razer Blade        | 26        | 0.48%   |
| Lenovo Yoga        | 25        | 0.46%   |
| Fujitsu LIFEBOOK   | 23        | 0.42%   |
| Apple MacBookPro12 | 23        | 0.42%   |
| Apple MacBookAir7  | 22        | 0.41%   |
| Apple MacBookAir6  | 22        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 663       | 12.23%  |
| 2020    | 630       | 11.62%  |
| 2021    | 561       | 10.35%  |
| 2018    | 511       | 9.43%   |
| 2012    | 384       | 7.08%   |
| 2013    | 364       | 6.71%   |
| 2017    | 325       | 6%      |
| 2011    | 323       | 5.96%   |
| 2015    | 316       | 5.83%   |
| 2016    | 278       | 5.13%   |
| 2014    | 261       | 4.81%   |
| 2022    | 248       | 4.57%   |
| 2010    | 200       | 3.69%   |
| 2009    | 130       | 2.4%    |
| 2008    | 115       | 2.12%   |
| 2023    | 61        | 1.13%   |
| 2007    | 36        | 0.66%   |
| 2006    | 10        | 0.18%   |
| Unknown | 3         | 0.06%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5421      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5418      | 99.94%  |
| Enabled  | 3         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5248      | 96.81%  |
| Yes  | 173       | 3.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1598      | 29.22%  |
| 16.01-24.0  | 1231      | 22.51%  |
| 8.01-16.0   | 1015      | 18.56%  |
| 3.01-4.0    | 794       | 14.52%  |
| 32.01-64.0  | 524       | 9.58%   |
| 64.01-256.0 | 117       | 2.14%   |
| 24.01-32.0  | 81        | 1.48%   |
| 1.01-2.0    | 72        | 1.32%   |
| 2.01-3.0    | 36        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1802      | 30.45%  |
| 1.01-2.0   | 1339      | 22.63%  |
| 4.01-8.0   | 1289      | 21.78%  |
| 3.01-4.0   | 1105      | 18.67%  |
| 8.01-16.0  | 314       | 5.31%   |
| 16.01-24.0 | 44        | 0.74%   |
| 24.01-32.0 | 12        | 0.2%    |
| 0.51-1.0   | 12        | 0.2%    |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3855      | 69.85%  |
| 2      | 1420      | 25.73%  |
| 3      | 183       | 3.32%   |
| 0      | 28        | 0.51%   |
| 4      | 24        | 0.43%   |
| 5      | 7         | 0.13%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3953      | 72.73%  |
| Yes       | 1482      | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4295      | 78.75%  |
| No        | 1159      | 21.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5355      | 98.73%  |
| No        | 69        | 1.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4594      | 84.05%  |
| No        | 872       | 15.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1456      | 26.73%  |
| Brazil       | 549       | 10.08%  |
| Germany      | 330       | 6.06%   |
| UK           | 239       | 4.39%   |
| India        | 230       | 4.22%   |
| Canada       | 192       | 3.52%   |
| Italy        | 174       | 3.19%   |
| France       | 158       | 2.9%    |
| Australia    | 128       | 2.35%   |
| Netherlands  | 112       | 2.06%   |
| Russia       | 103       | 1.89%   |
| Spain        | 93        | 1.71%   |
| Sweden       | 90        | 1.65%   |
| Poland       | 87        | 1.6%    |
| Portugal     | 79        | 1.45%   |
| Mexico       | 79        | 1.45%   |
| Romania      | 58        | 1.06%   |
| Norway       | 58        | 1.06%   |
| Turkey       | 54        | 0.99%   |
| Switzerland  | 51        | 0.94%   |
| South Africa | 49        | 0.9%    |
| Indonesia    | 44        | 0.81%   |
| Philippines  | 43        | 0.79%   |
| Finland      | 43        | 0.79%   |
| Greece       | 40        | 0.73%   |
| Denmark      | 40        | 0.73%   |
| New Zealand  | 38        | 0.7%    |
| Belgium      | 38        | 0.7%    |
| Argentina    | 38        | 0.7%    |
| Czechia      | 36        | 0.66%   |
| Austria      | 35        | 0.64%   |
| Chile        | 29        | 0.53%   |
| Croatia      | 26        | 0.48%   |
| Serbia       | 24        | 0.44%   |
| Malaysia     | 23        | 0.42%   |
| Ireland      | 23        | 0.42%   |
| Hungary      | 23        | 0.42%   |
| Bulgaria     | 23        | 0.42%   |
| Vietnam      | 21        | 0.39%   |
| Colombia     | 21        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 63        | 1.11%   |
| Bengaluru      | 36        | 0.63%   |
| Milan          | 33        | 0.58%   |
| Sydney         | 32        | 0.56%   |
| Brisbane       | 32        | 0.56%   |
| Rio de Janeiro | 28        | 0.49%   |
| Warsaw         | 27        | 0.47%   |
| Melbourne      | 27        | 0.47%   |
| Paris          | 26        | 0.46%   |
| New York       | 26        | 0.46%   |
| Moscow         | 26        | 0.46%   |
| Dallas         | 26        | 0.46%   |
| Vienna         | 25        | 0.44%   |
| Helsinki       | 25        | 0.44%   |
| London         | 24        | 0.42%   |
| Madrid         | 23        | 0.4%    |
| Bucharest      | 23        | 0.4%    |
| Berlin         | 23        | 0.4%    |
| Athens         | 23        | 0.4%    |
| Oslo           | 22        | 0.39%   |
| Istanbul       | 22        | 0.39%   |
| Amsterdam      | 22        | 0.39%   |
| Los Angeles    | 20        | 0.35%   |
| Auckland       | 20        | 0.35%   |
| Rome           | 19        | 0.33%   |
| Chicago        | 19        | 0.33%   |
| Johannesburg   | 18        | 0.32%   |
| Zagreb         | 17        | 0.3%    |
| Stockholm      | 17        | 0.3%    |
| St Petersburg  | 17        | 0.3%    |
| Sofia          | 17        | 0.3%    |
| Mexico City    | 17        | 0.3%    |
| Lisbon         | 17        | 0.3%    |
| Fortaleza      | 17        | 0.3%    |
| Denver         | 17        | 0.3%    |
| Toronto        | 16        | 0.28%   |
| Hyderabad      | 16        | 0.28%   |
| Calgary        | 16        | 0.28%   |
| Brasília      | 16        | 0.28%   |
| Zurich         | 15        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1266      | 1729   | 18.17%  |
| WDC                            | 714       | 825    | 10.25%  |
| Seagate                        | 650       | 767    | 9.33%   |
| SanDisk                        | 516       | 672    | 7.4%    |
| Toshiba                        | 432       | 513    | 6.2%    |
| Kingston                       | 374       | 444    | 5.37%   |
| SK hynix                       | 342       | 434    | 4.91%   |
| Unknown                        | 314       | 383    | 4.51%   |
| Crucial                        | 240       | 282    | 3.44%   |
| Intel                          | 233       | 288    | 3.34%   |
| Micron Technology              | 210       | 237    | 3.01%   |
| HGST                           | 191       | 223    | 2.74%   |
| Apple                          | 163       | 177    | 2.34%   |
| Hitachi                        | 107       | 118    | 1.54%   |
| A-DATA Technology              | 97        | 118    | 1.39%   |
| Phison                         | 78        | 95     | 1.12%   |
| KIOXIA                         | 65        | 75     | 0.93%   |
| China                          | 61        | 71     | 0.88%   |
| PNY                            | 52        | 63     | 0.75%   |
| Micron/Crucial Technology      | 51        | 67     | 0.73%   |
| Silicon Motion                 | 44        | 54     | 0.63%   |
| LITEON                         | 44        | 50     | 0.63%   |
| Transcend                      | 37        | 42     | 0.53%   |
| LITEONIT                       | 32        | 46     | 0.46%   |
| ADATA Technology               | 26        | 35     | 0.37%   |
| Phison Electronics             | 25        | 28     | 0.36%   |
| Team                           | 21        | 25     | 0.3%    |
| SPCC                           | 21        | 22     | 0.3%    |
| Kingston Technology Company    | 20        | 21     | 0.29%   |
| KingSpec                       | 19        | 21     | 0.27%   |
| JMicron Technology             | 19        | 26     | 0.27%   |
| Fujitsu                        | 19        | 20     | 0.27%   |
| Solid State Storage Technology | 17        | 20     | 0.24%   |
| Unknown                        | 17        | 21     | 0.24%   |
| Union Memory (Shenzhen)        | 16        | 19     | 0.23%   |
| Netac                          | 16        | 18     | 0.23%   |
| Patriot                        | 15        | 17     | 0.22%   |
| Intenso                        | 15        | 19     | 0.22%   |
| Hewlett-Packard                | 14        | 16     | 0.2%    |
| Solid State Storage            | 13        | 14     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 111       | 1.52%   |
| Kingston SA400S37240G 240GB SSD                    | 95        | 1.3%    |
| Samsung NVMe SSD Drive 512GB                       | 80        | 1.1%    |
| HGST HTS721010A9E630 1TB                           | 78        | 1.07%   |
| Unknown MMC Card  64GB                             | 73        | 1%      |
| Samsung NVMe SSD Drive 1TB                         | 64        | 0.88%   |
| Toshiba MQ01ABD100 1TB                             | 63        | 0.86%   |
| SK hynix NVMe SSD Drive 512GB                      | 59        | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 59        | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 58        | 0.79%   |
| Unknown MMC Card  32GB                             | 57        | 0.78%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 57        | 0.78%   |
| SanDisk NVMe SSD Drive 512GB                       | 55        | 0.75%   |
| Toshiba MQ04ABF100 1TB                             | 53        | 0.73%   |
| Samsung NVMe SSD Drive 500GB                       | 52        | 0.71%   |
| Intel NVMe SSD Drive 512GB                         | 47        | 0.64%   |
| SanDisk NVMe SSD Drive 1TB                         | 43        | 0.59%   |
| WDC WD10SPZX-24Z10 1TB                             | 42        | 0.58%   |
| Samsung NVMe SSD Drive 1024GB                      | 40        | 0.55%   |
| Seagate ST9500325AS 500GB                          | 39        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 38        | 0.52%   |
| Samsung SSD 860 EVO 500GB                          | 37        | 0.51%   |
| SanDisk NVMe SSD Drive 256GB                       | 36        | 0.49%   |
| Kingston SA400S37480G 480GB SSD                    | 36        | 0.49%   |
| Seagate ST500LT012-1DG142 500GB                    | 35        | 0.48%   |
| Seagate ST1000LM049-2GH172 1TB                     | 35        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                       | 34        | 0.47%   |
| Crucial CT240BX500SSD1 240GB                       | 34        | 0.47%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 33        | 0.45%   |
| Unknown MMC Card  128GB                            | 33        | 0.45%   |
| Samsung SSD 850 EVO 250GB                          | 32        | 0.44%   |
| SK hynix NVMe SSD Drive 1024GB                     | 31        | 0.42%   |
| Kingston SA400S37120G 120GB SSD                    | 31        | 0.42%   |
| Apple SSD SM0128G 121GB                            | 31        | 0.42%   |
| HGST HTS541010A9E680 1TB                           | 30        | 0.41%   |
| SK hynix NVMe SSD Drive 256GB                      | 29        | 0.4%    |
| SanDisk NVMe SSD Drive 500GB                       | 29        | 0.4%    |
| Toshiba NVMe SSD Drive 512GB                       | 28        | 0.38%   |
| Samsung SSD 860 EVO 1TB                            | 28        | 0.38%   |
| Seagate Expansion 1TB                              | 27        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 623       | 723    | 36.01%  |
| WDC                 | 429       | 477    | 24.8%   |
| Toshiba             | 268       | 303    | 15.49%  |
| HGST                | 191       | 223    | 11.04%  |
| Hitachi             | 107       | 118    | 6.18%   |
| Samsung Electronics | 32        | 33     | 1.85%   |
| Unknown             | 26        | 28     | 1.5%    |
| Fujitsu             | 19        | 20     | 1.1%    |
| Apple               | 16        | 18     | 0.92%   |
| External            | 5         | 5      | 0.29%   |
| Intenso             | 3         | 6      | 0.17%   |
| JMicron Technology  | 2         | 6      | 0.12%   |
| ASMT                | 2         | 4      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| StoreJet            | 1         | 1      | 0.06%   |
| SABRENT             | 1         | 2      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 496       | 654    | 21.19%  |
| Kingston            | 285       | 325    | 12.17%  |
| SanDisk             | 235       | 290    | 10.04%  |
| Crucial             | 221       | 263    | 9.44%   |
| WDC                 | 145       | 179    | 6.19%   |
| Apple               | 125       | 134    | 5.34%   |
| Micron Technology   | 64        | 70     | 2.73%   |
| A-DATA Technology   | 63        | 74     | 2.69%   |
| SK hynix            | 61        | 70     | 2.61%   |
| China               | 61        | 71     | 2.61%   |
| Toshiba             | 54        | 65     | 2.31%   |
| PNY                 | 50        | 61     | 2.14%   |
| Intel               | 44        | 48     | 1.88%   |
| LITEON              | 40        | 46     | 1.71%   |
| Transcend           | 34        | 39     | 1.45%   |
| LITEONIT            | 32        | 46     | 1.37%   |
| SPCC                | 19        | 20     | 0.81%   |
| KingSpec            | 19        | 21     | 0.81%   |
| Team                | 14        | 18     | 0.6%    |
| Seagate             | 14        | 15     | 0.6%    |
| Patriot             | 14        | 16     | 0.6%    |
| OCZ                 | 13        | 13     | 0.56%   |
| Netac               | 13        | 15     | 0.56%   |
| Hewlett-Packard     | 11        | 13     | 0.47%   |
| Lexar               | 9         | 9      | 0.38%   |
| Intenso             | 9         | 9      | 0.38%   |
| Corsair             | 9         | 10     | 0.38%   |
| Dogfish             | 8         | 11     | 0.34%   |
| Apacer              | 8         | 13     | 0.34%   |
| KingDian            | 7         | 8      | 0.3%    |
| SABRENT             | 6         | 7      | 0.26%   |
| GOODRAM             | 6         | 7      | 0.26%   |
| BHT                 | 6         | 6      | 0.26%   |
| ASMT                | 6         | 6      | 0.26%   |
| TO Exter            | 5         | 5      | 0.21%   |
| Plextor             | 5         | 7      | 0.21%   |
| Mushkin             | 5         | 6      | 0.21%   |
| KIOXIA-EXCERIA      | 5         | 5      | 0.21%   |
| Gigabyte Technology | 5         | 7      | 0.21%   |
| Teclast             | 4         | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2351      | 3311   | 35.93%  |
| SSD     | 2164      | 2804   | 33.07%  |
| HDD     | 1674      | 1975   | 25.58%  |
| MMC     | 264       | 321    | 4.03%   |
| Unknown | 90        | 117    | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3367      | 4593   | 54.13%  |
| NVMe | 2345      | 3291   | 37.7%   |
| MMC  | 264       | 321    | 4.24%   |
| SAS  | 244       | 323    | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2421      | 3120   | 63.74%  |
| 0.51-1.0   | 1226      | 1461   | 32.28%  |
| 1.01-2.0   | 126       | 157    | 3.32%   |
| 3.01-4.0   | 9         | 14     | 0.24%   |
| 2.01-3.0   | 9         | 16     | 0.24%   |
| 4.01-10.0  | 6         | 9      | 0.16%   |
| 10.01-20.0 | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1873      | 33.41%  |
| 251-500        | 1589      | 28.34%  |
| 501-1000       | 1049      | 18.71%  |
| 1001-2000      | 374       | 6.67%   |
| 51-100         | 268       | 4.78%   |
| 1-20           | 131       | 2.34%   |
| 21-50          | 124       | 2.21%   |
| 2001-3000      | 89        | 1.59%   |
| More than 3000 | 71        | 1.27%   |
| Unknown        | 38        | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2242      | 38.11%  |
| 21-50          | 1317      | 22.39%  |
| 101-250        | 772       | 13.12%  |
| 51-100         | 771       | 13.11%  |
| 251-500        | 412       | 7%      |
| 501-1000       | 217       | 3.69%   |
| 1001-2000      | 75        | 1.27%   |
| Unknown        | 38        | 0.65%   |
| More than 3000 | 21        | 0.36%   |
| 2001-3000      | 18        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 5         | 5      | 3.88%   |
| HGST HTS725050A7E630 500GB               | 5         | 8      | 3.88%   |
| Seagate ST1000LX015-1U7172 1TB           | 4         | 4      | 3.1%    |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.1%    |
| SK hynix PC711 HFS001TDE9X073N 1024GB    | 3         | 3      | 2.33%   |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 2.33%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.33%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.33%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.33%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.55%   |
| Toshiba MK7559GSXP 752GB                 | 2         | 2      | 1.55%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 2         | 2      | 1.55%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.55%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.55%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.55%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.55%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD         | 1         | 1      | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.78%   |
| WDC WDS100T2B0B-00YS70 1TB SSD           | 1         | 1      | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.78%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.78%   |
| WDC WD3200BEKX-75B7WT0 320GB             | 1         | 1      | 0.78%   |
| WDC WD3200BEKT-60PVMT0 320GB             | 1         | 1      | 0.78%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.78%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.78%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.78%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.78%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 1         | 1      | 0.78%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.78%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.78%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 29     | 21.71%  |
| WDC                 | 22        | 22     | 17.05%  |
| HGST                | 14        | 17     | 10.85%  |
| Toshiba             | 13        | 14     | 10.08%  |
| SK hynix            | 10        | 12     | 7.75%   |
| Samsung Electronics | 6         | 6      | 4.65%   |
| Hitachi             | 6         | 8      | 4.65%   |
| Kingston            | 5         | 5      | 3.88%   |
| Crucial             | 5         | 5      | 3.88%   |
| A-DATA Technology   | 5         | 5      | 3.88%   |
| Micron Technology   | 4         | 4      | 3.1%    |
| Intel               | 4         | 4      | 3.1%    |
| SanDisk             | 2         | 2      | 1.55%   |
| Team                | 1         | 1      | 0.78%   |
| LITEON              | 1         | 1      | 0.78%   |
| Lexar               | 1         | 1      | 0.78%   |
| Leven               | 1         | 1      | 0.78%   |
| China               | 1         | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 29     | 36.84%  |
| WDC     | 18        | 18     | 23.68%  |
| HGST    | 14        | 17     | 18.42%  |
| Toshiba | 10        | 10     | 13.16%  |
| Hitachi | 6         | 8      | 7.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 76        | 82     | 58.91%  |
| SSD  | 33        | 36     | 25.58%  |
| NVMe | 20        | 20     | 15.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| Intenso JAJP600M1TB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Intenso             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4150      | 6508   | 73.14%  |
| Works    | 1393      | 1880   | 24.55%  |
| Malfunc  | 129       | 138    | 2.27%   |
| Failed   | 2         | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3563      | 52.29%  |
| Samsung Electronics                     | 858       | 12.59%  |
| AMD                                     | 673       | 9.88%   |
| SanDisk                                 | 409       | 6%      |
| SK hynix                                | 280       | 4.11%   |
| Micron Technology                       | 146       | 2.14%   |
| Toshiba America Info Systems            | 123       | 1.81%   |
| Phison Electronics                      | 108       | 1.58%   |
| Kingston Technology Company             | 108       | 1.58%   |
| Nvidia                                  | 85        | 1.25%   |
| Micron/Crucial Technology               | 65        | 0.95%   |
| KIOXIA                                  | 65        | 0.95%   |
| ADATA Technology                        | 62        | 0.91%   |
| Silicon Motion                          | 56        | 0.82%   |
| Solid State Storage Technology          | 45        | 0.66%   |
| Union Memory (Shenzhen)                 | 32        | 0.47%   |
| Marvell Technology Group                | 22        | 0.32%   |
| Apple                                   | 22        | 0.32%   |
| Realtek Semiconductor                   | 19        | 0.28%   |
| Seagate Technology                      | 12        | 0.18%   |
| Shenzhen Longsys Electronics            | 10        | 0.15%   |
| Silicon Integrated Systems [SiS]        | 8         | 0.12%   |
| Lite-On Technology                      | 8         | 0.12%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.09%   |
| Lenovo                                  | 6         | 0.09%   |
| JMicron Technology                      | 4         | 0.06%   |
| ASMedia Technology                      | 4         | 0.06%   |
| Yangtze Memory Technologies             | 3         | 0.04%   |
| Transcend                               | 2         | 0.03%   |
| INNOGRIT                                | 2         | 0.03%   |
| Solidigm                                | 1         | 0.01%   |
| Silicon Image                           | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| O2 Micro                                | 1         | 0.01%   |
| Netac Technology                        | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Biwin Storage Technology                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 639       | 8.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 438       | 6.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 422       | 5.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 357       | 5.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 331       | 4.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 302       | 4.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 261       | 3.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 209       | 2.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 175       | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 165       | 2.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 154       | 2.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 138       | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 136       | 1.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 110       | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 110       | 1.54%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 103       | 1.44%   |
| Intel SSD 660P Series                                                          | 102       | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 101       | 1.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 100       | 1.4%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 96        | 1.35%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 95        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 93        | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 83        | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 72        | 1.01%   |
| Phison E12 NVMe Controller                                                     | 56        | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 54        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 54        | 0.76%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 53        | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 53        | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 52        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 52        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 51        | 0.72%   |
| Nvidia MCP79 AHCI Controller                                                   | 49        | 0.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 48        | 0.67%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 48        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 47        | 0.66%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 42        | 0.59%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 41        | 0.57%   |
| SK hynix BC511 NVMe SSD                                                        | 36        | 0.5%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 36        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3762      | 55.29%  |
| NVMe | 2341      | 34.41%  |
| RAID | 537       | 7.89%   |
| IDE  | 164       | 2.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4370      | 80.61%  |
| AMD    | 1051      | 19.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 135       | 2.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 107       | 1.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 99        | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 95        | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 93        | 1.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 82        | 1.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 81        | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 77        | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 75        | 1.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 74        | 1.36%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 68        | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 67        | 1.24%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 65        | 1.2%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 64        | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 59        | 1.09%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 57        | 1.05%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 55        | 1.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 50        | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 49        | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 46        | 0.85%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 45        | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.79%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 43        | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 42        | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 41        | 0.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 39        | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 39        | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 39        | 0.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 39        | 0.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 38        | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 38        | 0.7%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 38        | 0.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 36        | 0.66%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 36        | 0.66%   |
| Intel 12th Gen Core i7-12700H                 | 35        | 0.65%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 34        | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 33        | 0.61%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 32        | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 32        | 0.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 32        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1568      | 28.92%  |
| Intel Core i5           | 1356      | 25.01%  |
| Other                   | 513       | 9.46%   |
| Intel Core i3           | 331       | 6.11%   |
| AMD Ryzen 7             | 298       | 5.5%    |
| AMD Ryzen 5             | 298       | 5.5%    |
| Intel Core 2 Duo        | 185       | 3.41%   |
| Intel Celeron           | 176       | 3.25%   |
| AMD Ryzen 9             | 70        | 1.29%   |
| AMD Ryzen 3             | 62        | 1.14%   |
| Intel Pentium           | 61        | 1.13%   |
| Intel Core i9           | 53        | 0.98%   |
| AMD A6                  | 51        | 0.94%   |
| AMD Ryzen 7 PRO         | 44        | 0.81%   |
| AMD A8                  | 39        | 0.72%   |
| AMD A10                 | 34        | 0.63%   |
| Intel Pentium Dual-Core | 33        | 0.61%   |
| AMD A4                  | 25        | 0.46%   |
| Intel Atom              | 20        | 0.37%   |
| Intel Core 2            | 17        | 0.31%   |
| AMD E1                  | 14        | 0.26%   |
| Intel Xeon              | 13        | 0.24%   |
| Intel Pentium Dual      | 13        | 0.24%   |
| Intel Genuine           | 13        | 0.24%   |
| AMD Athlon              | 13        | 0.24%   |
| Intel Core m3           | 12        | 0.22%   |
| AMD E                   | 11        | 0.2%    |
| AMD Ryzen 5 PRO         | 10        | 0.18%   |
| AMD E2                  | 10        | 0.18%   |
| Intel Pentium Silver    | 8         | 0.15%   |
| AMD FX                  | 8         | 0.15%   |
| AMD A12                 | 7         | 0.13%   |
| Intel Core M            | 6         | 0.11%   |
| AMD Turion 64 X2 Mobile | 6         | 0.11%   |
| Intel Core m5           | 5         | 0.09%   |
| AMD Athlon X2           | 5         | 0.09%   |
| Intel Celeron Dual-Core | 4         | 0.07%   |
| AMD C-60                | 4         | 0.07%   |
| AMD Phenom II           | 3         | 0.06%   |
| AMD V120                | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2276      | 41.98%  |
| 4      | 1868      | 34.46%  |
| 6      | 565       | 10.42%  |
| 8      | 527       | 9.72%   |
| 14     | 70        | 1.29%   |
| 12     | 37        | 0.68%   |
| 10     | 33        | 0.61%   |
| 1      | 25        | 0.46%   |
| 16     | 11        | 0.2%    |
| 24     | 6         | 0.11%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5421      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4573      | 84.29%  |
| 1      | 852       | 15.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5414      | 99.87%  |
| Unknown        | 7         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3691      | 66.44%  |
| 0x906ea    | 152       | 2.74%   |
| 0x806ea    | 108       | 1.94%   |
| 0x306a9    | 101       | 1.82%   |
| 0x806ec    | 98        | 1.76%   |
| 0x806c1    | 94        | 1.69%   |
| 0x206a7    | 92        | 1.66%   |
| 0x406e3    | 86        | 1.55%   |
| 0x40651    | 80        | 1.44%   |
| 0xa0652    | 75        | 1.35%   |
| 0x806e9    | 61        | 1.1%    |
| 0x306c3    | 57        | 1.03%   |
| 0x0a50000c | 56        | 1.01%   |
| 0x906e9    | 53        | 0.95%   |
| 0x08108102 | 46        | 0.83%   |
| 0x306d4    | 40        | 0.72%   |
| 0x08600106 | 39        | 0.7%    |
| 0x806d1    | 37        | 0.67%   |
| 0x1067a    | 35        | 0.63%   |
| 0x806eb    | 34        | 0.61%   |
| 0x506e3    | 34        | 0.61%   |
| 0x08108109 | 31        | 0.56%   |
| 0x906ed    | 28        | 0.5%    |
| 0x08608103 | 26        | 0.47%   |
| 0x906a3    | 25        | 0.45%   |
| 0x08600104 | 25        | 0.45%   |
| 0x20655    | 22        | 0.4%    |
| 0x706e5    | 20        | 0.36%   |
| 0x08600103 | 20        | 0.36%   |
| 0x06006705 | 17        | 0.31%   |
| 0x0a404102 | 15        | 0.27%   |
| 0x0810100b | 15        | 0.27%   |
| 0x706a1    | 13        | 0.23%   |
| 0x0a404101 | 13        | 0.23%   |
| 0x0a50000d | 12        | 0.22%   |
| 0x40661    | 11        | 0.2%    |
| 0x10676    | 11        | 0.2%    |
| 0x07030105 | 10        | 0.18%   |
| 0xa0660    | 9         | 0.16%   |
| 0x06001119 | 9         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1250      | 23.03%  |
| Haswell          | 481       | 8.86%   |
| SandyBridge      | 384       | 7.08%   |
| IvyBridge        | 360       | 6.63%   |
| Skylake          | 303       | 5.58%   |
| Unknown          | 288       | 5.31%   |
| TigerLake        | 248       | 4.57%   |
| Zen+             | 215       | 3.96%   |
| CometLake        | 210       | 3.87%   |
| Broadwell        | 200       | 3.69%   |
| Penryn           | 199       | 3.67%   |
| Zen 2            | 195       | 3.59%   |
| Zen 3            | 184       | 3.39%   |
| Westmere         | 151       | 2.78%   |
| IceLake          | 103       | 1.9%    |
| Silvermont       | 85        | 1.57%   |
| Core             | 74        | 1.36%   |
| Alderlake Hybrid | 74        | 1.36%   |
| Excavator        | 72        | 1.33%   |
| Goldmont plus    | 65        | 1.2%    |
| Zen              | 56        | 1.03%   |
| Puma             | 45        | 0.83%   |
| Piledriver       | 38        | 0.7%    |
| Bobcat           | 27        | 0.5%    |
| Goldmont         | 24        | 0.44%   |
| Nehalem          | 17        | 0.31%   |
| Steamroller      | 15        | 0.28%   |
| Jaguar           | 15        | 0.28%   |
| K10 Llano        | 13        | 0.24%   |
| K8 Hammer        | 12        | 0.22%   |
| K10              | 9         | 0.17%   |
| K8 & K10 hybrid  | 8         | 0.15%   |
| Bonnell          | 4         | 0.07%   |
| Tremont          | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3973      | 54.78%  |
| Nvidia                           | 1964      | 27.08%  |
| AMD                              | 1308      | 18.04%  |
| Silicon Integrated Systems [SiS] | 6         | 0.08%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 349       | 4.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 347       | 4.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 331       | 4.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 258       | 3.48%   |
| Intel UHD Graphics 620                                                                   | 235       | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 233       | 3.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 215       | 2.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 188       | 2.53%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 185       | 2.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 183       | 2.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 172       | 2.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 163       | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 160       | 2.16%   |
| Intel HD Graphics 620                                                                    | 158       | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 156       | 2.1%    |
| Intel HD Graphics 5500                                                                   | 140       | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 136       | 1.83%   |
| Intel HD Graphics 630                                                                    | 123       | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 116       | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 91        | 1.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 89        | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 83        | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 83        | 1.12%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 80        | 1.08%   |
| AMD Lucienne                                                                             | 80        | 1.08%   |
| Intel HD Graphics 530                                                                    | 74        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 70        | 0.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 66        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 62        | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 61        | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 59        | 0.8%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 58        | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 56        | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 55        | 0.74%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 54        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 51        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 50        | 0.67%   |
| AMD Rembrandt [Radeon 680M]                                                              | 50        | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 48        | 0.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2435      | 44.61%  |
| Intel + Nvidia     | 1341      | 24.56%  |
| 1 x AMD            | 751       | 13.76%  |
| 1 x Nvidia         | 350       | 6.41%   |
| AMD + Nvidia       | 249       | 4.56%   |
| Intel + AMD        | 203       | 3.72%   |
| 2 x AMD            | 107       | 1.96%   |
| 2 x Nvidia         | 10        | 0.18%   |
| 1 x SiS            | 6         | 0.11%   |
| Other              | 3         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 2 x Intel          | 1         | 0.02%   |
| 1 x S3 Graphics    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3784      | 69.1%   |
| Proprietary | 1555      | 28.4%   |
| Unknown     | 137       | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4187      | 75.92%  |
| 1.01-2.0   | 348       | 6.31%   |
| 3.01-4.0   | 318       | 5.77%   |
| 0.01-0.5   | 225       | 4.08%   |
| 5.01-6.0   | 189       | 3.43%   |
| 7.01-8.0   | 108       | 1.96%   |
| 0.51-1.0   | 97        | 1.76%   |
| 2.01-3.0   | 29        | 0.53%   |
| 8.01-16.0  | 14        | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1120      | 17.79%  |
| Chimei Innolux          | 922       | 14.64%  |
| LG Display              | 855       | 13.58%  |
| BOE                     | 847       | 13.45%  |
| Samsung Electronics     | 562       | 8.92%   |
| Apple                   | 271       | 4.3%    |
| Sharp                   | 229       | 3.64%   |
| Dell                    | 189       | 3%      |
| Goldstar                | 186       | 2.95%   |
| PANDA                   | 152       | 2.41%   |
| Chi Mei Optoelectronics | 97        | 1.54%   |
| Lenovo                  | 83        | 1.32%   |
| Acer                    | 65        | 1.03%   |
| Hewlett-Packard         | 64        | 1.02%   |
| AOC                     | 64        | 1.02%   |
| InfoVision              | 56        | 0.89%   |
| Philips                 | 50        | 0.79%   |
| BenQ                    | 47        | 0.75%   |
| CSO                     | 37        | 0.59%   |
| ASUSTek Computer        | 35        | 0.56%   |
| Ancor Communications    | 35        | 0.56%   |
| ViewSonic               | 22        | 0.35%   |
| TMX                     | 16        | 0.25%   |
| Sony                    | 14        | 0.22%   |
| Panasonic               | 14        | 0.22%   |
| LG Philips              | 14        | 0.22%   |
| Iiyama                  | 14        | 0.22%   |
| Vizio                   | 11        | 0.17%   |
| InnoLux Display         | 10        | 0.16%   |
| Sceptre Tech            | 9         | 0.14%   |
| Toshiba                 | 8         | 0.13%   |
| MSI                     | 8         | 0.13%   |
| JDI                     | 8         | 0.13%   |
| Vestel Elektronik       | 7         | 0.11%   |
| RTK                     | 5         | 0.08%   |
| NEC Computers           | 5         | 0.08%   |
| LGD                     | 5         | 0.08%   |
| HUAWEI                  | 5         | 0.08%   |
| HKC                     | 5         | 0.08%   |
| Hitachi                 | 5         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 60        | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 57        | 0.9%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 51        | 0.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 50        | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 50        | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 45        | 0.71%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 40        | 0.63%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 38        | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 34        | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 30        | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 29        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 29        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 29        | 0.46%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 26        | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 26        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 26        | 0.41%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch               | 24        | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 23        | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 23        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 22        | 0.35%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 22        | 0.35%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 21        | 0.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 21        | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 21        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 19        | 0.3%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 19        | 0.3%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 18        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 18        | 0.28%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 18        | 0.28%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 17        | 0.27%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 17        | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 17        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 17        | 0.27%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 17        | 0.27%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                   | 16        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch          | 16        | 0.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 16        | 0.25%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 16        | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 15        | 0.24%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 15        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2790      | 47.3%   |
| 1366x768 (WXGA)    | 1461      | 24.77%  |
| 3840x2160 (4K)     | 299       | 5.07%   |
| 1600x900 (HD+)     | 233       | 3.95%   |
| 2560x1440 (QHD)    | 211       | 3.58%   |
| 1280x800 (WXGA)    | 140       | 2.37%   |
| 1920x1200 (WUXGA)  | 120       | 2.03%   |
| 1440x900 (WXGA+)   | 108       | 1.83%   |
| 2560x1600          | 94        | 1.59%   |
| 2880x1800          | 76        | 1.29%   |
| 2560x1080          | 52        | 0.88%   |
| 3840x2400          | 38        | 0.64%   |
| 3440x1440          | 38        | 0.64%   |
| 1680x1050 (WSXGA+) | 35        | 0.59%   |
| 2160x1440          | 20        | 0.34%   |
| 3200x1800 (QHD+)   | 19        | 0.32%   |
| 1360x768           | 18        | 0.31%   |
| 1280x1024 (SXGA)   | 16        | 0.27%   |
| 2256x1504          | 15        | 0.25%   |
| 3072x1920          | 13        | 0.22%   |
| 1920x540           | 13        | 0.22%   |
| 3840x1080          | 10        | 0.17%   |
| 3000x2000          | 10        | 0.17%   |
| 3200x2000          | 7         | 0.12%   |
| 3456x2160          | 6         | 0.1%    |
| Unknown            | 6         | 0.1%    |
| 3840x1100          | 4         | 0.07%   |
| 2240x1400          | 4         | 0.07%   |
| 2560x1700          | 3         | 0.05%   |
| 2304x1440          | 3         | 0.05%   |
| 1920x1280          | 3         | 0.05%   |
| 1280x720 (HD)      | 3         | 0.05%   |
| 800x1280           | 2         | 0.03%   |
| 3840x1600          | 2         | 0.03%   |
| 3840x1200          | 2         | 0.03%   |
| 2880x1620          | 2         | 0.03%   |
| 2520x1680          | 2         | 0.03%   |
| 2288x1287          | 2         | 0.03%   |
| 1920x515           | 2         | 0.03%   |
| 1680x945           | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2629      | 41.82%  |
| 13      | 965       | 15.35%  |
| 14      | 714       | 11.36%  |
| 17      | 452       | 7.19%   |
| 27      | 217       | 3.45%   |
| 24      | 183       | 2.91%   |
| 23      | 155       | 2.47%   |
| 12      | 130       | 2.07%   |
| 16      | 119       | 1.89%   |
| 21      | 118       | 1.88%   |
| 31      | 91        | 1.45%   |
| 11      | 78        | 1.24%   |
| 34      | 77        | 1.22%   |
| 18      | 52        | 0.83%   |
| Unknown | 43        | 0.68%   |
| 19      | 34        | 0.54%   |
| 40      | 23        | 0.37%   |
| 32      | 23        | 0.37%   |
| 84      | 22        | 0.35%   |
| 20      | 19        | 0.3%    |
| 22      | 18        | 0.29%   |
| 72      | 15        | 0.24%   |
| 54      | 12        | 0.19%   |
| 48      | 11        | 0.17%   |
| 25      | 9         | 0.14%   |
| 26      | 8         | 0.13%   |
| 28      | 7         | 0.11%   |
| 52      | 6         | 0.1%    |
| 35      | 6         | 0.1%    |
| 46      | 5         | 0.08%   |
| 39      | 5         | 0.08%   |
| 33      | 5         | 0.08%   |
| 29      | 5         | 0.08%   |
| 10      | 5         | 0.08%   |
| 65      | 4         | 0.06%   |
| 49      | 3         | 0.05%   |
| 37      | 3         | 0.05%   |
| 47      | 2         | 0.03%   |
| 8       | 2         | 0.03%   |
| 99      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3860      | 61.85%  |
| 201-300        | 686       | 10.99%  |
| 351-400        | 548       | 8.78%   |
| 501-600        | 508       | 8.14%   |
| 401-500        | 229       | 3.67%   |
| 601-700        | 132       | 2.12%   |
| 701-800        | 106       | 1.7%    |
| 1001-1500      | 47        | 0.75%   |
| Unknown        | 43        | 0.69%   |
| 1501-2000      | 39        | 0.62%   |
| 801-900        | 34        | 0.54%   |
| 901-1000       | 4         | 0.06%   |
| 101-200        | 2         | 0.03%   |
| 1-100          | 2         | 0.03%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4615      | 84.09%  |
| 16/10   | 645       | 11.75%  |
| 21/9    | 93        | 1.69%   |
| 3/2     | 61        | 1.11%   |
| Unknown | 23        | 0.42%   |
| 5/4     | 19        | 0.35%   |
| 32/9    | 11        | 0.2%    |
| 4/3     | 8         | 0.15%   |
| 3.40    | 4         | 0.07%   |
| 6/5     | 2         | 0.04%   |
| 3.73    | 2         | 0.04%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2622      | 41.78%  |
| 81-90          | 1354      | 21.57%  |
| 121-130        | 421       | 6.71%   |
| 201-250        | 400       | 6.37%   |
| 71-80          | 316       | 5.04%   |
| 301-350        | 224       | 3.57%   |
| 351-500        | 202       | 3.22%   |
| 61-70          | 123       | 1.96%   |
| 111-120        | 110       | 1.75%   |
| 51-60          | 82        | 1.31%   |
| 151-200        | 80        | 1.27%   |
| More than 1000 | 71        | 1.13%   |
| 251-300        | 59        | 0.94%   |
| 141-150        | 56        | 0.89%   |
| 501-1000       | 52        | 0.83%   |
| Unknown        | 43        | 0.69%   |
| 131-140        | 38        | 0.61%   |
| 91-100         | 14        | 0.22%   |
| 41-50          | 5         | 0.08%   |
| 1-40           | 4         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2734      | 44.43%  |
| 101-120       | 1684      | 27.36%  |
| 51-100        | 846       | 13.75%  |
| 161-240       | 497       | 8.08%   |
| More than 240 | 274       | 4.45%   |
| 1-50          | 76        | 1.23%   |
| Unknown       | 43        | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4305      | 77.5%   |
| 2     | 950       | 17.1%   |
| 0     | 177       | 3.19%   |
| 3     | 116       | 2.09%   |
| 4     | 7         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2968      | 33.94%  |
| Intel                             | 2895      | 33.1%   |
| Qualcomm Atheros                  | 1165      | 13.32%  |
| Broadcom                          | 588       | 6.72%   |
| Broadcom Limited                  | 169       | 1.93%   |
| MediaTek                          | 165       | 1.89%   |
| Marvell Technology Group          | 68        | 0.78%   |
| ASIX Electronics                  | 63        | 0.72%   |
| Ralink                            | 62        | 0.71%   |
| Nvidia                            | 59        | 0.67%   |
| TP-Link                           | 53        | 0.61%   |
| Samsung Electronics               | 43        | 0.49%   |
| Ralink Technology                 | 43        | 0.49%   |
| DisplayLink                       | 33        | 0.38%   |
| Dell                              | 31        | 0.35%   |
| Xiaomi                            | 26        | 0.3%    |
| Lenovo                            | 26        | 0.3%    |
| Qualcomm                          | 25        | 0.29%   |
| Sierra Wireless                   | 24        | 0.27%   |
| Ericsson Business Mobile Networks | 22        | 0.25%   |
| JMicron Technology                | 20        | 0.23%   |
| Hewlett-Packard                   | 17        | 0.19%   |
| Google                            | 17        | 0.19%   |
| ASUSTek Computer                  | 17        | 0.19%   |
| OnePlus Technology (Shenzhen)     | 12        | 0.14%   |
| NetGear                           | 12        | 0.14%   |
| Huawei Technologies               | 11        | 0.13%   |
| OPPO Electronics                  | 10        | 0.11%   |
| Motorola PCS                      | 10        | 0.11%   |
| D-Link                            | 9         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 8         | 0.09%   |
| Linksys                           | 6         | 0.07%   |
| Edimax Technology                 | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| Qualcomm Atheros Communications   | 5         | 0.06%   |
| Fibocom                           | 5         | 0.06%   |
| Microsoft                         | 4         | 0.05%   |
| ICS Advent                        | 3         | 0.03%   |
| Arduino SA                        | 3         | 0.03%   |
| U-Blox                            | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 1891      | 18.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 449       | 4.36%   |
| Intel Wi-Fi 6 AX200                                                  | 356       | 3.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 255       | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 239       | 2.32%   |
| Intel Wireless 8265 / 8275                                           | 225       | 2.18%   |
| Intel Wi-Fi 6 AX201                                                  | 188       | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 186       | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 177       | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 175       | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 175       | 1.7%    |
| Intel Wireless 7260                                                  | 173       | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 172       | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 157       | 1.52%   |
| Intel Wireless 7265                                                  | 154       | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 139       | 1.35%   |
| Intel Wireless 8260                                                  | 138       | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 126       | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 126       | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 112       | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 107       | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 107       | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 101       | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 96        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                        | 87        | 0.84%   |
| Intel Wireless 3165                                                  | 76        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                | 75        | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 72        | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 68        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 66        | 0.64%   |
| Intel Ethernet Connection I219-LM                                    | 65        | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 64        | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 62        | 0.6%    |
| Intel Wireless 3160                                                  | 61        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 61        | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 59        | 0.57%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 59        | 0.57%   |
| Intel Ethernet Connection I218-LM                                    | 58        | 0.56%   |
| Intel Wireless-AC 9260                                               | 56        | 0.54%   |
| Intel Ethernet Connection I217-LM                                    | 54        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2793      | 49.44%  |
| Qualcomm Atheros                      | 976       | 17.28%  |
| Realtek Semiconductor                 | 778       | 13.77%  |
| Broadcom                              | 501       | 8.87%   |
| MediaTek                              | 161       | 2.85%   |
| Broadcom Limited                      | 137       | 2.43%   |
| Ralink                                | 62        | 1.1%    |
| TP-Link                               | 46        | 0.81%   |
| Ralink Technology                     | 43        | 0.76%   |
| Dell                                  | 26        | 0.46%   |
| Sierra Wireless                       | 24        | 0.42%   |
| Qualcomm                              | 21        | 0.37%   |
| ASUSTek Computer                      | 14        | 0.25%   |
| NetGear                               | 11        | 0.19%   |
| D-Link                                | 9         | 0.16%   |
| Hewlett-Packard                       | 7         | 0.12%   |
| Edimax Technology                     | 6         | 0.11%   |
| Qualcomm Atheros Communications       | 5         | 0.09%   |
| Fibocom                               | 5         | 0.09%   |
| Microsoft                             | 3         | 0.05%   |
| Linksys                               | 3         | 0.05%   |
| Ericsson Business Mobile Networks     | 3         | 0.05%   |
| D-Link System                         | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| AVM                                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 356       | 6.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 255       | 4.49%   |
| Intel Wireless 8265 / 8275                                           | 225       | 3.96%   |
| Intel Wi-Fi 6 AX201                                                  | 188       | 3.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 177       | 3.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 175       | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 175       | 3.08%   |
| Intel Wireless 7260                                                  | 173       | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 172       | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 157       | 2.76%   |
| Intel Wireless 7265                                                  | 154       | 2.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 139       | 2.45%   |
| Intel Wireless 8260                                                  | 138       | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 126       | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 126       | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 112       | 1.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 107       | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 107       | 1.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 99        | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 96        | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                        | 87        | 1.53%   |
| Intel Wireless 3165                                                  | 76        | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 72        | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 68        | 1.2%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 64        | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 62        | 1.09%   |
| Intel Wireless 3160                                                  | 61        | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 61        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 59        | 1.04%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 59        | 1.04%   |
| Intel Wireless-AC 9260                                               | 56        | 0.99%   |
| Intel Centrino Ultimate-N 6300                                       | 54        | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 52        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 50        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 49        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 45        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 44        | 0.77%   |
| Intel Centrino Advanced-N 6235                                       | 44        | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 42        | 0.74%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 35        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2669      | 59.25%  |
| Intel                            | 850       | 18.87%  |
| Qualcomm Atheros                 | 305       | 6.77%   |
| Broadcom                         | 199       | 4.42%   |
| Marvell Technology Group         | 68        | 1.51%   |
| ASIX Electronics                 | 63        | 1.4%    |
| Nvidia                           | 59        | 1.31%   |
| Samsung Electronics              | 42        | 0.93%   |
| Broadcom Limited                 | 36        | 0.8%    |
| DisplayLink                      | 33        | 0.73%   |
| Xiaomi                           | 26        | 0.58%   |
| Lenovo                           | 26        | 0.58%   |
| JMicron Technology               | 20        | 0.44%   |
| Google                           | 17        | 0.38%   |
| OnePlus Technology (Shenzhen)    | 11        | 0.24%   |
| OPPO Electronics                 | 10        | 0.22%   |
| Silicon Integrated Systems [SiS] | 8         | 0.18%   |
| Huawei Technologies              | 8         | 0.18%   |
| TP-Link                          | 7         | 0.16%   |
| Motorola PCS                     | 7         | 0.16%   |
| Apple                            | 5         | 0.11%   |
| Qualcomm                         | 4         | 0.09%   |
| Hewlett-Packard                  | 4         | 0.09%   |
| MediaTek                         | 3         | 0.07%   |
| Linksys                          | 3         | 0.07%   |
| ICS Advent                       | 3         | 0.07%   |
| ASUSTek Computer                 | 3         | 0.07%   |
| T & A Mobile Phones              | 2         | 0.04%   |
| LSI                              | 2         | 0.04%   |
| LG Electronics                   | 2         | 0.04%   |
| Aquantia                         | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| Research In Motion               | 1         | 0.02%   |
| NTmore                           | 1         | 0.02%   |
| NetGear                          | 1         | 0.02%   |
| Microsoft                        | 1         | 0.02%   |
| Foxconn / Hon Hai                | 1         | 0.02%   |
| Cypress Semiconductor            | 1         | 0.02%   |
| Attansic Technology              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1891      | 41.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 449       | 9.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 239       | 5.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 186       | 4.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 75        | 1.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 66        | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 65        | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 58        | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 54        | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 51        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 46        | 1.01%   |
| Nvidia MCP79 Ethernet                                             | 45        | 0.99%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 44        | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 38        | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 35        | 0.77%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 32        | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 30        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 29        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 29        | 0.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 25        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 22        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.48%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.46%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 21        | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 20        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 20        | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 19        | 0.42%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 19        | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                            | 18        | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5358      | 55.27%  |
| Ethernet | 4282      | 44.17%  |
| Modem    | 41        | 0.42%   |
| Unknown  | 14        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4565      | 79.02%  |
| Ethernet | 1212      | 20.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3895      | 71.8%   |
| 1     | 1454      | 26.8%   |
| 0     | 43        | 0.79%   |
| 3     | 33        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4280      | 77.89%  |
| Yes  | 1215      | 22.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2364      | 51.05%  |
| Qualcomm Atheros Communications | 438       | 9.46%   |
| Realtek Semiconductor           | 414       | 8.94%   |
| Apple                           | 289       | 6.24%   |
| IMC Networks                    | 249       | 5.38%   |
| Lite-On Technology              | 208       | 4.49%   |
| Broadcom                        | 199       | 4.3%    |
| Foxconn / Hon Hai               | 150       | 3.24%   |
| Dell                            | 68        | 1.47%   |
| Cambridge Silicon Radio         | 43        | 0.93%   |
| Realtek                         | 33        | 0.71%   |
| Toshiba                         | 32        | 0.69%   |
| Ralink                          | 32        | 0.69%   |
| Hewlett-Packard                 | 30        | 0.65%   |
| ASUSTek Computer                | 17        | 0.37%   |
| Foxconn International           | 11        | 0.24%   |
| Ralink Technology               | 8         | 0.17%   |
| MediaTek                        | 8         | 0.17%   |
| Alps Electric                   | 7         | 0.15%   |
| USI                             | 4         | 0.09%   |
| Smart Modular Technologies      | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| Qcom                            | 3         | 0.06%   |
| Opticis                         | 3         | 0.06%   |
| TP-Link                         | 2         | 0.04%   |
| Fujitsu                         | 2         | 0.04%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 806       | 17.4%   |
| Intel AX201 Bluetooth                               | 478       | 10.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 375       | 8.09%   |
| Intel AX200 Bluetooth                               | 350       | 7.55%   |
| Realtek Bluetooth Radio                             | 257       | 5.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 242       | 5.22%   |
| Apple Bluetooth Host Controller                     | 165       | 3.56%   |
| Intel Bluetooth Device                              | 135       | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 108       | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 89        | 1.92%   |
| IMC Networks Bluetooth Radio                        | 78        | 1.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 76        | 1.64%   |
| IMC Networks Wireless_Device                        | 71        | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 68        | 1.47%   |
| Intel AX210 Bluetooth                               | 60        | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                  | 56        | 1.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 53        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 50        | 1.08%   |
| IMC Networks Bluetooth Device                       | 49        | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 46        | 0.99%   |
| Lite-On Bluetooth Device                            | 46        | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 43        | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                   | 43        | 0.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 43        | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                         | 34        | 0.73%   |
| Realtek Bluetooth Radio                             | 33        | 0.71%   |
| Ralink RT3290 Bluetooth                             | 32        | 0.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 0.52%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.52%   |
| Lite-On Wireless_Device                             | 22        | 0.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 20        | 0.43%   |
| Apple Bluetooth HCI                                 | 20        | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 18        | 0.39%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 17        | 0.37%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 4264      | 59.88%  |
| Nvidia                                          | 1247      | 17.51%  |
| AMD                                             | 1137      | 15.97%  |
| C-Media Electronics                             | 57        | 0.8%    |
| Logitech                                        | 47        | 0.66%   |
| Realtek Semiconductor                           | 42        | 0.59%   |
| Lenovo                                          | 27        | 0.38%   |
| JMTek                                           | 25        | 0.35%   |
| GN Netcom                                       | 25        | 0.35%   |
| Kingston Technology                             | 19        | 0.27%   |
| Apple                                           | 17        | 0.24%   |
| Texas Instruments                               | 16        | 0.22%   |
| Generalplus Technology                          | 16        | 0.22%   |
| Corsair                                         | 12        | 0.17%   |
| Sony                                            | 11        | 0.15%   |
| Razer USA                                       | 11        | 0.15%   |
| Plantronics                                     | 11        | 0.15%   |
| Hewlett-Packard                                 | 11        | 0.15%   |
| SteelSeries ApS                                 | 9         | 0.13%   |
| Silicon Integrated Systems [SiS]                | 8         | 0.11%   |
| Focusrite-Novation                              | 7         | 0.1%    |
| Sennheiser Communications                       | 5         | 0.07%   |
| Creative Technology                             | 5         | 0.07%   |
| ASUSTek Computer                                | 5         | 0.07%   |
| Samson Technologies                             | 4         | 0.06%   |
| FiiO Electronics Technology                     | 4         | 0.06%   |
| Yamaha                                          | 3         | 0.04%   |
| Tenx Technology                                 | 3         | 0.04%   |
| No brand                                        | 3         | 0.04%   |
| GYROCOM C&C                                     | 3         | 0.04%   |
| DSEA A/S                                        | 3         | 0.04%   |
| Blue Microphones                                | 3         | 0.04%   |
| XMOS                                            | 2         | 0.03%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.03%   |
| TerraTec Electronic                             | 2         | 0.03%   |
| Pioneer DJ                                      | 2         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.03%   |
| CMX Systems                                     | 2         | 0.03%   |
| Bose                                            | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 770       | 8.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 624       | 7.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 409       | 4.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 379       | 4.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 351       | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 333       | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 260       | 3.01%   |
| Intel Haswell-ULT HD Audio Controller                                      | 258       | 2.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 248       | 2.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 237       | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 224       | 2.59%   |
| Intel Broadwell-U Audio Controller                                         | 200       | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 192       | 2.22%   |
| Intel Comet Lake PCH cAVS                                                  | 192       | 2.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 172       | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 168       | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 164       | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 156       | 1.8%    |
| Intel Comet Lake PCH-LP cAVS                                               | 155       | 1.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 142       | 1.64%   |
| AMD FCH Azalia Controller                                                  | 139       | 1.61%   |
| Intel CM238 HD Audio Controller                                            | 137       | 1.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 122       | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 117       | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 98        | 1.13%   |
| Nvidia Audio device                                                        | 97        | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 95        | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 94        | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                              | 92        | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                              | 87        | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                   | 85        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 73        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 71        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 65        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 64        | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 58        | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 56        | 0.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 54        | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                         | 52        | 0.6%    |
| Nvidia MCP79 High Definition Audio                                         | 49        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 533       | 29.13%  |
| SK hynix                                | 422       | 23.06%  |
| Micron Technology                       | 256       | 13.99%  |
| Kingston                                | 146       | 7.98%   |
| Crucial                                 | 99        | 5.41%   |
| Unknown                                 | 56        | 3.06%   |
| A-DATA Technology                       | 39        | 2.13%   |
| Smart                                   | 34        | 1.86%   |
| Ramaxel Technology                      | 30        | 1.64%   |
| Corsair                                 | 27        | 1.48%   |
| Goldkey                                 | 22        | 1.2%    |
| Elpida                                  | 22        | 1.2%    |
| Neo Forza                               | 20        | 1.09%   |
| G.Skill                                 | 16        | 0.87%   |
| Unknown                                 | 16        | 0.87%   |
| Unknown (ABCD)                          | 12        | 0.66%   |
| Smart Brazil                            | 10        | 0.55%   |
| Team                                    | 9         | 0.49%   |
| Teikon                                  | 7         | 0.38%   |
| Nanya Technology                        | 6         | 0.33%   |
| Apacer                                  | 5         | 0.27%   |
| PNY                                     | 4         | 0.22%   |
| Patriot                                 | 3         | 0.16%   |
| High Bridge                             | 3         | 0.16%   |
| GSkill                                  | 3         | 0.16%   |
| ChangXin Memory                         | 3         | 0.16%   |
| Avant                                   | 3         | 0.16%   |
| Transcend                               | 2         | 0.11%   |
| Timetec                                 | 2         | 0.11%   |
| GOODRAM                                 | 2         | 0.11%   |
| Gold Key                                | 2         | 0.11%   |
| CSX                                     | 2         | 0.11%   |
| Unknown (8A02)                          | 1         | 0.05%   |
| Unknown (898F)                          | 1         | 0.05%   |
| Unknown (09B6)                          | 1         | 0.05%   |
| Unknown (09A4)                          | 1         | 0.05%   |
| Silicon Power Computer & Communications | 1         | 0.05%   |
| Silicon Power                           | 1         | 0.05%   |
| RZX                                     | 1         | 0.05%   |
| PUSKILL                                 | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 48        | 2.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 32        | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 27        | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.25%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 1.15%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 19        | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.99%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.99%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.99%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 18        | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.89%   |
| Unknown                                                          | 16        | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.78%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.78%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.68%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.63%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.63%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.63%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.57%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.57%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 10        | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 10        | 0.52%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 10        | 0.52%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 10        | 0.52%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 9         | 0.47%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 997       | 64.99%  |
| DDR3    | 291       | 18.97%  |
| LPDDR4  | 78        | 5.08%   |
| LPDDR3  | 65        | 4.24%   |
| DDR5    | 51        | 3.32%   |
| LPDDR5  | 33        | 2.15%   |
| DDR2    | 10        | 0.65%   |
| SDRAM   | 5         | 0.33%   |
| Unknown | 4         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1339      | 85.72%  |
| Row Of Chips | 202       | 12.93%  |
| Chip         | 13        | 0.83%   |
| DIMM         | 4         | 0.26%   |
| Unknown      | 4         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 763       | 45.55%  |
| 4096  | 387       | 23.1%   |
| 16384 | 341       | 20.36%  |
| 32768 | 91        | 5.43%   |
| 2048  | 82        | 4.9%    |
| 1024  | 11        | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 469       | 28.13%  |
| 3200    | 417       | 25.01%  |
| 1600    | 233       | 13.98%  |
| 2400    | 138       | 8.28%   |
| 2133    | 94        | 5.64%   |
| 4800    | 46        | 2.76%   |
| 4267    | 38        | 2.28%   |
| 6400    | 32        | 1.92%   |
| 1334    | 32        | 1.92%   |
| 3266    | 27        | 1.62%   |
| 1867    | 24        | 1.44%   |
| 1333    | 21        | 1.26%   |
| 8400    | 18        | 1.08%   |
| 4266    | 13        | 0.78%   |
| 1067    | 12        | 0.72%   |
| 800     | 9         | 0.54%   |
| 3733    | 8         | 0.48%   |
| 1866    | 5         | 0.3%    |
| 5600    | 4         | 0.24%   |
| 2933    | 4         | 0.24%   |
| 667     | 4         | 0.24%   |
| 4199    | 3         | 0.18%   |
| Unknown | 3         | 0.18%   |
| 3000    | 2         | 0.12%   |
| 2048    | 2         | 0.12%   |
| 1066    | 2         | 0.12%   |
| 5500    | 1         | 0.06%   |
| 5200    | 1         | 0.06%   |
| 3466    | 1         | 0.06%   |
| 3400    | 1         | 0.06%   |
| 3333    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 29.63%  |
| Seiko Epson         | 5         | 18.52%  |
| Canon               | 5         | 18.52%  |
| Brother Industries  | 4         | 14.81%  |
| Samsung Electronics | 2         | 7.41%   |
| Xerox               | 1         | 3.7%    |
| MIIIW               | 1         | 3.7%    |
| ICS Advent          | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M2020 Series            | 2         | 7.41%   |
| Canon PIXMA MX920 Series        | 2         | 7.41%   |
| Xerox B215                      | 1         | 3.7%    |
| Seiko Epson WF-3520 Series      | 1         | 3.7%    |
| Seiko Epson L6160 Series        | 1         | 3.7%    |
| Seiko Epson L3110 Series        | 1         | 3.7%    |
| Seiko Epson L132 Series         | 1         | 3.7%    |
| Seiko Epson ET-2700 Series      | 1         | 3.7%    |
| MIIIW MW Keyboard Air Mini      | 1         | 3.7%    |
| ICS Advent Parallel Adapter     | 1         | 3.7%    |
| HP OfficeJet 3830 series        | 1         | 3.7%    |
| HP Ink Tank Wireless 410 series | 1         | 3.7%    |
| HP ENVY Photo 7800 series       | 1         | 3.7%    |
| HP ENVY 4520 series             | 1         | 3.7%    |
| HP Deskjet 3050 J610 series     | 1         | 3.7%    |
| HP Deskjet 2540 series          | 1         | 3.7%    |
| HP Deskjet 2050 J510            | 1         | 3.7%    |
| HP Color LaserJet CP2025dn      | 1         | 3.7%    |
| Canon GX7000 series             | 1         | 3.7%    |
| Canon G4010 series              | 1         | 3.7%    |
| Canon E400 series               | 1         | 3.7%    |
| Brother HL-L2370DW series       | 1         | 3.7%    |
| Brother HL-L2320D series        | 1         | 3.7%    |
| Brother HL-3170CDW series       | 1         | 3.7%    |
| Brother HL-2270DW Laser Printer | 1         | 3.7%    |

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
| Chicony Electronics                    | 1149      | 23.68%  |
| IMC Networks                           | 534       | 11%     |
| Microdia                               | 476       | 9.81%   |
| Realtek Semiconductor                  | 397       | 8.18%   |
| Bison Electronics                      | 383       | 7.89%   |
| Sunplus Innovation Technology          | 266       | 5.48%   |
| Quanta                                 | 252       | 5.19%   |
| Apple                                  | 215       | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 167       | 3.44%   |
| Suyin                                  | 127       | 2.62%   |
| Syntek                                 | 122       | 2.51%   |
| Acer                                   | 118       | 2.43%   |
| Lite-On Technology                     | 96        | 1.98%   |
| Luxvisions Innotech Limited            | 81        | 1.67%   |
| Silicon Motion                         | 68        | 1.4%    |
| Logitech                               | 63        | 1.3%    |
| Ricoh                                  | 39        | 0.8%    |
| Alcor Micro                            | 35        | 0.72%   |
| Sonix Technology                       | 31        | 0.64%   |
| Samsung Electronics                    | 28        | 0.58%   |
| SunplusIT                              | 16        | 0.33%   |
| ALi                                    | 15        | 0.31%   |
| Primax Electronics                     | 13        | 0.27%   |
| Microsoft                              | 11        | 0.23%   |
| Lenovo                                 | 11        | 0.23%   |
| Importek                               | 11        | 0.23%   |
| Z-Star Microelectronics                | 10        | 0.21%   |
| DigiTech                               | 10        | 0.21%   |
| Intel                                  | 8         | 0.16%   |
| OmniVision Technologies                | 6         | 0.12%   |
| Generalplus Technology                 | 6         | 0.12%   |
| Razer USA                              | 5         | 0.1%    |
| icSpring                               | 5         | 0.1%    |
| Tobii Technology AB                    | 4         | 0.08%   |
| MacroSilicon                           | 4         | 0.08%   |
| Foxconn / Hon Hai                      | 4         | 0.08%   |
| DLTDC0A9II090N                         | 4         | 0.08%   |
| AVerMedia Technologies                 | 4         | 0.08%   |
| 8SSC20F27114V1SR0BK1X4S                | 4         | 0.08%   |
| Unknown                                | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 260       | 5.33%   |
| Chicony integrated camera                           | 226       | 4.64%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 175       | 3.59%   |
| Realtek Integrated_Webcam_HD                        | 158       | 3.24%   |
| Chicony HD WebCam                                   | 148       | 3.04%   |
| IMC Networks Integrated Camera                      | 145       | 2.97%   |
| Chicony USB2.0 Camera                               | 109       | 2.24%   |
| Bison BisonCam,NB Pro                               | 103       | 2.11%   |
| Sunplus Integrated_Webcam_HD                        | 79        | 1.62%   |
| Syntek Integrated Camera                            | 78        | 1.6%    |
| Apple Built-in iSight                               | 71        | 1.46%   |
| Apple FaceTime HD Camera                            | 67        | 1.37%   |
| Bison HD Webcam                                     | 61        | 1.25%   |
| Quanta HD User Facing                               | 58        | 1.19%   |
| Bison Integrated Camera                             | 57        | 1.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 55        | 1.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 46        | 0.94%   |
| Acer Integrated Camera                              | 38        | 0.78%   |
| Microdia Integrated Webcam                          | 37        | 0.76%   |
| Lite-On Integrated Camera                           | 37        | 0.76%   |
| Chicony HP HD Camera                                | 37        | 0.76%   |
| Chicony HD User Facing                              | 37        | 0.76%   |
| Chicony TOSHIBA Web Camera - HD                     | 34        | 0.7%    |
| Chicony Integrated Camera (1280x720@30)             | 34        | 0.7%    |
| Bison SunplusIT Integrated Camera                   | 34        | 0.7%    |
| Sunplus HD WebCam                                   | 33        | 0.68%   |
| Sunplus ASUS Webcam                                 | 33        | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                        | 32        | 0.66%   |
| Quanta HP TrueVision HD Camera                      | 31        | 0.64%   |
| Quanta HD Webcam                                    | 30        | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD                | 30        | 0.62%   |
| Realtek Integrated Webcam                           | 29        | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam                       | 29        | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 28        | 0.57%   |
| Chicony HP Wide Vision HD Camera                    | 28        | 0.57%   |
| Chicony HP TrueVision HD Camera                     | 28        | 0.57%   |
| Realtek USB Camera                                  | 27        | 0.55%   |
| Quanta VGA WebCam                                   | 27        | 0.55%   |
| Acer BisonCam, NB Pro                               | 27        | 0.55%   |
| Samsung Galaxy series, misc. (MTP mode)             | 25        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 290       | 31.02%  |
| Validity Sensors                   | 283       | 30.27%  |
| Shenzhen Goodix Technology         | 167       | 17.86%  |
| Elan Microelectronics              | 54        | 5.78%   |
| Upek                               | 52        | 5.56%   |
| LighTuning Technology              | 38        | 4.06%   |
| AuthenTec                          | 29        | 3.1%    |
| STMicroelectronics                 | 7         | 0.75%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 0.53%   |
| Focal-systems.Corp                 | 5         | 0.53%   |
| HOLTEK                             | 3         | 0.32%   |
| Samsung Electronics                | 1         | 0.11%   |
| DigitalPersona                     | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 86        | 9.2%    |
| Shenzhen Goodix  FingerPrint Device                                        | 81        | 8.66%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 66        | 7.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 58        | 6.2%    |
| Shenzhen Goodix FingerPrint                                                | 50        | 5.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 47        | 5.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 42        | 4.49%   |
| Elan ELAN:Fingerprint                                                      | 39        | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 36        | 3.85%   |
| Synaptics TouchPad                                                         | 27        | 2.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 21        | 2.25%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 2.25%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 2.25%   |
| Synaptics WBDI Device                                                      | 21        | 2.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 2.14%   |
| Validity Sensors VFS491                                                    | 19        | 2.03%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 19        | 2.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 1.82%   |
| Unknown                                                                    | 17        | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 16        | 1.71%   |
| Elan ELAN:ARM-M4                                                           | 15        | 1.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 13        | 1.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.28%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 1.28%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 1.28%   |
| Synaptics  WBDI                                                            | 11        | 1.18%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.07%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 0.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 0.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.86%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.75%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.75%   |
| AuthenTec AES2810                                                          | 7         | 0.75%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.75%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.64%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.53%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 0.53%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 170       | 48.85%  |
| Alcor Micro               | 97        | 27.87%  |
| Upek                      | 29        | 8.33%   |
| O2 Micro                  | 25        | 7.18%   |
| Lenovo                    | 18        | 5.17%   |
| Gemalto (was Gemplus)     | 2         | 0.57%   |
| Aladdin Knowledge Systems | 2         | 0.57%   |
| SCM Microsystems          | 1         | 0.29%   |
| OmniKey                   | 1         | 0.29%   |
| Giesecke & Devrient       | 1         | 0.29%   |
| Clay Logic                | 1         | 0.29%   |
| Advanced Card Systems     | 1         | 0.29%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 97        | 27.87%  |
| Broadcom BCM5880 Secure Applications Processor                               | 49        | 14.08%  |
| Broadcom 5880                                                                | 45        | 12.93%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 41        | 11.78%  |
| Broadcom 58200                                                               | 32        | 9.2%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 6.03%   |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.86%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.57%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.29%   |
| OmniKey CardMan 4321                                                         | 1         | 0.29%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.29%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.29%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.29%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.29%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3414      | 61.78%  |
| 1     | 1665      | 30.13%  |
| 2     | 387       | 7%      |
| 3     | 52        | 0.94%   |
| 4     | 5         | 0.09%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 912       | 35.91%  |
| Multimedia controller    | 355       | 13.98%  |
| Chipcard                 | 338       | 13.31%  |
| Graphics card            | 299       | 11.77%  |
| Net/wireless             | 298       | 11.73%  |
| Bluetooth                | 92        | 3.62%   |
| Camera                   | 65        | 2.56%   |
| Storage                  | 40        | 1.57%   |
| Sound                    | 32        | 1.26%   |
| Net/ethernet             | 32        | 1.26%   |
| Card reader              | 19        | 0.75%   |
| Communication controller | 18        | 0.71%   |
| Network                  | 14        | 0.55%   |
| Modem                    | 12        | 0.47%   |
| Storage/ide              | 5         | 0.2%    |
| Storage/nvme             | 3         | 0.12%   |
| Flash memory             | 2         | 0.08%   |
| Firewire controller      | 2         | 0.08%   |
| Unclassified device      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

