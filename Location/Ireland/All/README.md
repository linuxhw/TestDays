Linux in Ireland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ireland/Desktop/README.md) and [notebooks](/Location/Ireland/Notebook/README.md).

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

Total: 1551

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5480               | Notebook    | [bf6091037f](https://linux-hardware.org/?probe=bf6091037f) | Jan 02, 2026 |
| HP            | 8054                        | Desktop     | [3a92aa6278](https://linux-hardware.org/?probe=3a92aa6278) | Jan 02, 2026 |
| Lenovo        | ThinkPad L14 Gen 5 21L6S... | Notebook    | [26d690db11](https://linux-hardware.org/?probe=26d690db11) | Jan 01, 2026 |
| HP            | Spectre x360 Convertible... | Convertible | [40ce3307ba](https://linux-hardware.org/?probe=40ce3307ba) | Dec 29, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [6177dbde06](https://linux-hardware.org/?probe=6177dbde06) | Dec 29, 2025 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [b22aaf7082](https://linux-hardware.org/?probe=b22aaf7082) | Dec 27, 2025 |
| Lenovo        | 3706 SDK0J40697 WIN 3305... | Desktop     | [4d20ffd18e](https://linux-hardware.org/?probe=4d20ffd18e) | Dec 26, 2025 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [7430ee5a08](https://linux-hardware.org/?probe=7430ee5a08) | Dec 26, 2025 |
| Schenker      | XMG EVO (M24)               | Notebook    | [3c9ed7a8e1](https://linux-hardware.org/?probe=3c9ed7a8e1) | Dec 26, 2025 |
| Apple         | MacBookPro5,4               | Notebook    | [238e2b95cc](https://linux-hardware.org/?probe=238e2b95cc) | Dec 22, 2025 |
| Intel         | SKYBAY                      | Desktop     | [b03f828223](https://linux-hardware.org/?probe=b03f828223) | Dec 19, 2025 |
| ASUSTek       | H97M-E                      | Desktop     | [ffe359b043](https://linux-hardware.org/?probe=ffe359b043) | Dec 09, 2025 |
| ASUSTek       | M2N-TE                      | Desktop     | [e5386b7876](https://linux-hardware.org/?probe=e5386b7876) | Dec 09, 2025 |
| Dell          | Latitude 5480               | Notebook    | [f9cb3f4f06](https://linux-hardware.org/?probe=f9cb3f4f06) | Dec 08, 2025 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [ad7d44ca83](https://linux-hardware.org/?probe=ad7d44ca83) | Dec 07, 2025 |
| HP            | Pavilion m6                 | Notebook    | [83ae8543ad](https://linux-hardware.org/?probe=83ae8543ad) | Dec 06, 2025 |
| ASRock        | A520M-HVS                   | Desktop     | [481fdc2cd8](https://linux-hardware.org/?probe=481fdc2cd8) | Dec 06, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [643dd3254e](https://linux-hardware.org/?probe=643dd3254e) | Dec 06, 2025 |
| Dell          | Latitude E5420              | Notebook    | [87fa4c5494](https://linux-hardware.org/?probe=87fa4c5494) | Dec 04, 2025 |
| Dell          | 0YNVJG A02                  | Desktop     | [cb1f80a2c8](https://linux-hardware.org/?probe=cb1f80a2c8) | Dec 02, 2025 |
| Apple         | MacBookPro5,5               | Notebook    | [c9d9e42f58](https://linux-hardware.org/?probe=c9d9e42f58) | Dec 02, 2025 |
| TianBei       | G5                          | Desktop     | [f56b6a032c](https://linux-hardware.org/?probe=f56b6a032c) | Dec 01, 2025 |
| Lenovo        | ThinkPad P16s Gen 4 21QV... | Notebook    | [2d69745285](https://linux-hardware.org/?probe=2d69745285) | Nov 30, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [a1f3296e93](https://linux-hardware.org/?probe=a1f3296e93) | Nov 28, 2025 |
| Dell          | Latitude 5480               | Notebook    | [c4f9267dd0](https://linux-hardware.org/?probe=c4f9267dd0) | Nov 27, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | Notebook    | [ac7a4ba5fa](https://linux-hardware.org/?probe=ac7a4ba5fa) | Nov 27, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | Desktop     | [f0414ac6bb](https://linux-hardware.org/?probe=f0414ac6bb) | Nov 24, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | Desktop     | [0d72d78760](https://linux-hardware.org/?probe=0d72d78760) | Nov 24, 2025 |
| Gigabyte      | H610M K DDR4                | Desktop     | [206e1863a0](https://linux-hardware.org/?probe=206e1863a0) | Nov 24, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c6c798ec6a](https://linux-hardware.org/?probe=c6c798ec6a) | Nov 22, 2025 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [bc44863efb](https://linux-hardware.org/?probe=bc44863efb) | Nov 21, 2025 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3ab12fe1b7](https://linux-hardware.org/?probe=3ab12fe1b7) | Nov 20, 2025 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d06e70ccfa](https://linux-hardware.org/?probe=d06e70ccfa) | Nov 18, 2025 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [016f8989b1](https://linux-hardware.org/?probe=016f8989b1) | Nov 14, 2025 |
| Lenovo        | 105E SBB1C50523 WIN 3556... | Desktop     | [a2362b03bf](https://linux-hardware.org/?probe=a2362b03bf) | Nov 14, 2025 |
| Lenovo        | 105E SBB1C50523 WIN 3556... | Desktop     | [66d2b08872](https://linux-hardware.org/?probe=66d2b08872) | Nov 14, 2025 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [88a072f547](https://linux-hardware.org/?probe=88a072f547) | Nov 14, 2025 |
| Lenovo        | ThinkPad T480 20L6S0CG04    | Notebook    | [41102d245e](https://linux-hardware.org/?probe=41102d245e) | Nov 14, 2025 |
| AZW           | GTR V21                     | Desktop     | [f3bf254495](https://linux-hardware.org/?probe=f3bf254495) | Nov 14, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ed6b6d3adb](https://linux-hardware.org/?probe=ed6b6d3adb) | Nov 13, 2025 |
| Lenovo        | ThinkPad Z16 Gen 1 21D5S... | Notebook    | [a98b6568d5](https://linux-hardware.org/?probe=a98b6568d5) | Nov 13, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [9a14004136](https://linux-hardware.org/?probe=9a14004136) | Nov 04, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [13caf7fdd7](https://linux-hardware.org/?probe=13caf7fdd7) | Nov 02, 2025 |
| Simply NUC    | CBM3r9MS                    | Desktop     | [4a489980eb](https://linux-hardware.org/?probe=4a489980eb) | Nov 02, 2025 |
| PELADN        | WI-6                        | Desktop     | [3ca3fc9dc0](https://linux-hardware.org/?probe=3ca3fc9dc0) | Nov 02, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [27b2e515dd](https://linux-hardware.org/?probe=27b2e515dd) | Nov 02, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e9cb213ef9](https://linux-hardware.org/?probe=e9cb213ef9) | Oct 30, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c7afeb73cb](https://linux-hardware.org/?probe=c7afeb73cb) | Oct 28, 2025 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ea235e152b](https://linux-hardware.org/?probe=ea235e152b) | Oct 25, 2025 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [1965c9b813](https://linux-hardware.org/?probe=1965c9b813) | Oct 24, 2025 |
| HP            | EliteBook 850 G5            | Notebook    | [187ad354a0](https://linux-hardware.org/?probe=187ad354a0) | Oct 22, 2025 |
| Dell          | Latitude 7290               | Notebook    | [17d6b12d74](https://linux-hardware.org/?probe=17d6b12d74) | Oct 21, 2025 |
| HP            | Pro x2 612 G2               | Tablet      | [23f775fc4b](https://linux-hardware.org/?probe=23f775fc4b) | Oct 21, 2025 |
| HP            | ProBook 460 16 inch G11 ... | Notebook    | [474c444bb7](https://linux-hardware.org/?probe=474c444bb7) | Oct 16, 2025 |
| HP            | 81C6 MVB 0C                 | Server      | [1fdba98edb](https://linux-hardware.org/?probe=1fdba98edb) | Oct 16, 2025 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | Desktop     | [577b37f16a](https://linux-hardware.org/?probe=577b37f16a) | Oct 15, 2025 |
| HP            | ProBook 460 16 inch G11 ... | Notebook    | [0e855ea22e](https://linux-hardware.org/?probe=0e855ea22e) | Oct 13, 2025 |
| TianBei       | G5                          | Desktop     | [c7de156fce](https://linux-hardware.org/?probe=c7de156fce) | Oct 12, 2025 |
| Acer          | Aspire 4820T                | Notebook    | [0b96b1a45c](https://linux-hardware.org/?probe=0b96b1a45c) | Oct 11, 2025 |
| HP            | ZBook 15 G3                 | Notebook    | [fda4022552](https://linux-hardware.org/?probe=fda4022552) | Oct 10, 2025 |
| Dell          | 0M5DCD A00                  | Desktop     | [76a7edd20f](https://linux-hardware.org/?probe=76a7edd20f) | Oct 09, 2025 |
| Acer          | Aspire AV16-51P             | Notebook    | [8ee21f7207](https://linux-hardware.org/?probe=8ee21f7207) | Oct 09, 2025 |
| Dell          | XPS 9320                    | Notebook    | [cfdf87fa43](https://linux-hardware.org/?probe=cfdf87fa43) | Oct 07, 2025 |
| Soyo          | B550M ARGB V1.0             | Desktop     | [0e64b458e9](https://linux-hardware.org/?probe=0e64b458e9) | Oct 07, 2025 |
| Pegatron      | 2AB5                        | Desktop     | [da6c2b35e5](https://linux-hardware.org/?probe=da6c2b35e5) | Oct 06, 2025 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [d93fd9cd68](https://linux-hardware.org/?probe=d93fd9cd68) | Oct 05, 2025 |
| HP            | 8643 SMVB                   | Desktop     | [880db6d712](https://linux-hardware.org/?probe=880db6d712) | Oct 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | Notebook    | [b373da7b66](https://linux-hardware.org/?probe=b373da7b66) | Oct 02, 2025 |
| Dell          | Precision 3570              | Notebook    | [0792cd8ac5](https://linux-hardware.org/?probe=0792cd8ac5) | Oct 01, 2025 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [0ab773f2cb](https://linux-hardware.org/?probe=0ab773f2cb) | Sep 30, 2025 |
| System76      | Darter Pro                  | Notebook    | [93e47e0ea8](https://linux-hardware.org/?probe=93e47e0ea8) | Sep 28, 2025 |
| Dell          | Latitude 5550               | Notebook    | [3a45309ea3](https://linux-hardware.org/?probe=3a45309ea3) | Sep 26, 2025 |
| Microsoft     | Surface Pro 4               | Tablet      | [45fb1c7aa0](https://linux-hardware.org/?probe=45fb1c7aa0) | Sep 24, 2025 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [5f13a167cf](https://linux-hardware.org/?probe=5f13a167cf) | Sep 22, 2025 |
| Dell          | Latitude E7250              | Notebook    | [23d0cae5a2](https://linux-hardware.org/?probe=23d0cae5a2) | Sep 21, 2025 |
| HP            | ProBook 650 G3              | Notebook    | [14e64e6479](https://linux-hardware.org/?probe=14e64e6479) | Sep 20, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | Notebook    | [f820f5c67e](https://linux-hardware.org/?probe=f820f5c67e) | Sep 20, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [133d9ca143](https://linux-hardware.org/?probe=133d9ca143) | Sep 19, 2025 |
| System76      | Darter Pro                  | Notebook    | [ea73200ad1](https://linux-hardware.org/?probe=ea73200ad1) | Sep 13, 2025 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [feedd5c728](https://linux-hardware.org/?probe=feedd5c728) | Sep 12, 2025 |
| Lenovo        | ThinkPad T580 20L9001YUK    | Notebook    | [ae256cd6a3](https://linux-hardware.org/?probe=ae256cd6a3) | Sep 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [13efdd5d50](https://linux-hardware.org/?probe=13efdd5d50) | Sep 11, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [0c67a7a769](https://linux-hardware.org/?probe=0c67a7a769) | Sep 10, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [06bde6fe38](https://linux-hardware.org/?probe=06bde6fe38) | Sep 10, 2025 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [35d85793e9](https://linux-hardware.org/?probe=35d85793e9) | Sep 07, 2025 |
| Dell          | 0654JC A01                  | Desktop     | [796e7c67bd](https://linux-hardware.org/?probe=796e7c67bd) | Sep 06, 2025 |
| ASRock        | H170M Pro4S                 | Desktop     | [8dfb9ecd3f](https://linux-hardware.org/?probe=8dfb9ecd3f) | Sep 06, 2025 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [1b2cb57846](https://linux-hardware.org/?probe=1b2cb57846) | Sep 06, 2025 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [a256c85c0e](https://linux-hardware.org/?probe=a256c85c0e) | Sep 04, 2025 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [f9edae111e](https://linux-hardware.org/?probe=f9edae111e) | Sep 04, 2025 |
| System76      | Darter Pro                  | Notebook    | [ca35503054](https://linux-hardware.org/?probe=ca35503054) | Sep 03, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [1bc81eac5d](https://linux-hardware.org/?probe=1bc81eac5d) | Sep 03, 2025 |
| HP            | Pavilion 15                 | Notebook    | [ab1864300c](https://linux-hardware.org/?probe=ab1864300c) | Sep 02, 2025 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4deac2ee9a](https://linux-hardware.org/?probe=4deac2ee9a) | Aug 31, 2025 |
| Apple         | MacBookPro11,5              | Notebook    | [424d535907](https://linux-hardware.org/?probe=424d535907) | Aug 29, 2025 |
| Microsoft     | Surface Laptop for Busin... | Tablet      | [4a4d4fc2e8](https://linux-hardware.org/?probe=4a4d4fc2e8) | Aug 28, 2025 |
| AZW           | GT-R                        | Notebook    | [6341fd2b0a](https://linux-hardware.org/?probe=6341fd2b0a) | Aug 27, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [dcb47bcd7a](https://linux-hardware.org/?probe=dcb47bcd7a) | Aug 27, 2025 |
| MSI           | PRO B650M-P                 | Desktop     | [bb7b40a4d1](https://linux-hardware.org/?probe=bb7b40a4d1) | Aug 25, 2025 |
| Dell          | 0VRWRC A00                  | Desktop     | [3faf049b13](https://linux-hardware.org/?probe=3faf049b13) | Aug 24, 2025 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [984ab24fce](https://linux-hardware.org/?probe=984ab24fce) | Aug 24, 2025 |
| Gigabyte      | B85M-D3H                    | Desktop     | [699f8be0a6](https://linux-hardware.org/?probe=699f8be0a6) | Aug 23, 2025 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [bfbcf4905c](https://linux-hardware.org/?probe=bfbcf4905c) | Aug 23, 2025 |
| Acer          | Aspire XC-605               | Desktop     | [95db947c8a](https://linux-hardware.org/?probe=95db947c8a) | Aug 22, 2025 |
| Dell          | Precision 5540              | Notebook    | [83d6c9afdb](https://linux-hardware.org/?probe=83d6c9afdb) | Aug 17, 2025 |
| AZW           | MINI S 10                   | Desktop     | [261666e686](https://linux-hardware.org/?probe=261666e686) | Aug 16, 2025 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [77e06cedb3](https://linux-hardware.org/?probe=77e06cedb3) | Aug 14, 2025 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [12512c558c](https://linux-hardware.org/?probe=12512c558c) | Aug 13, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | Notebook    | [5fadb3c020](https://linux-hardware.org/?probe=5fadb3c020) | Aug 12, 2025 |
| Minix         | NEO Z100-0dB                | All in one  | [d2b5a6eaf4](https://linux-hardware.org/?probe=d2b5a6eaf4) | Aug 09, 2025 |
| Minix         | NEO Z100-0dB                | All in one  | [eab6827235](https://linux-hardware.org/?probe=eab6827235) | Aug 09, 2025 |
| Acer          | Aspire XC-605               | Desktop     | [29cba8aede](https://linux-hardware.org/?probe=29cba8aede) | Aug 08, 2025 |
| Gigabyte      | B850 AORUS ELITE WIFI7 I... | Desktop     | [342dbe65f0](https://linux-hardware.org/?probe=342dbe65f0) | Aug 07, 2025 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [5dc1c83dab](https://linux-hardware.org/?probe=5dc1c83dab) | Aug 04, 2025 |
| HP            | 1495                        | Desktop     | [218563e7f6](https://linux-hardware.org/?probe=218563e7f6) | Aug 04, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [7bd56fcc64](https://linux-hardware.org/?probe=7bd56fcc64) | Aug 04, 2025 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [f27ff982b9](https://linux-hardware.org/?probe=f27ff982b9) | Aug 02, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KWS0... | Notebook    | [50840ef175](https://linux-hardware.org/?probe=50840ef175) | Jul 31, 2025 |
| Notebook      | NV4xPZ                      | Notebook    | [37a332f596](https://linux-hardware.org/?probe=37a332f596) | Jul 29, 2025 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ee90f7187d](https://linux-hardware.org/?probe=ee90f7187d) | Jul 29, 2025 |
| System76      | Darter Pro                  | Notebook    | [25f8f54f0e](https://linux-hardware.org/?probe=25f8f54f0e) | Jul 24, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [fbde4bb58c](https://linux-hardware.org/?probe=fbde4bb58c) | Jul 18, 2025 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d8f0a226b3](https://linux-hardware.org/?probe=d8f0a226b3) | Jul 18, 2025 |
| Dell          | Precision 7510              | Notebook    | [2b98d07080](https://linux-hardware.org/?probe=2b98d07080) | Jul 14, 2025 |
| Lenovo        | ThinkCentre M91p 7034A1G    | Desktop     | [4013346091](https://linux-hardware.org/?probe=4013346091) | Jul 12, 2025 |
| Dell          | Latitude 7424 Rugged Ext... | Notebook    | [c58532453b](https://linux-hardware.org/?probe=c58532453b) | Jul 10, 2025 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [1c615c695d](https://linux-hardware.org/?probe=1c615c695d) | Jul 10, 2025 |
| System76      | Darter Pro                  | Notebook    | [17726b23c3](https://linux-hardware.org/?probe=17726b23c3) | Jul 09, 2025 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [01d5138add](https://linux-hardware.org/?probe=01d5138add) | Jul 09, 2025 |
| Dell          | 02YYK5 A01                  | Desktop     | [0614e49217](https://linux-hardware.org/?probe=0614e49217) | Jul 04, 2025 |
| Apple         | MacBook6,1                  | Notebook    | [018d803185](https://linux-hardware.org/?probe=018d803185) | Jul 03, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [297f3e778a](https://linux-hardware.org/?probe=297f3e778a) | Jul 03, 2025 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [4588382960](https://linux-hardware.org/?probe=4588382960) | Jun 29, 2025 |
| Shuttle       | DH410                       | Desktop     | [25c234963e](https://linux-hardware.org/?probe=25c234963e) | Jun 23, 2025 |
| ASUSTek       | ROG STRIX X870-I GAMING ... | Desktop     | [b42f0b2b6a](https://linux-hardware.org/?probe=b42f0b2b6a) | Jun 23, 2025 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [1f4aaf8ee0](https://linux-hardware.org/?probe=1f4aaf8ee0) | Jun 23, 2025 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [2664beae66](https://linux-hardware.org/?probe=2664beae66) | Jun 21, 2025 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f86bf33629](https://linux-hardware.org/?probe=f86bf33629) | Jun 19, 2025 |
| Shuttle       | DH410                       | Desktop     | [a5b93b10ce](https://linux-hardware.org/?probe=a5b93b10ce) | Jun 17, 2025 |
| System76      | Darter Pro                  | Notebook    | [5ca8b470c6](https://linux-hardware.org/?probe=5ca8b470c6) | Jun 17, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8294c2fa1b](https://linux-hardware.org/?probe=8294c2fa1b) | Jun 12, 2025 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [2e81385a5f](https://linux-hardware.org/?probe=2e81385a5f) | Jun 11, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [b064170607](https://linux-hardware.org/?probe=b064170607) | Jun 06, 2025 |
| Lenovo        | ThinkPad T480s 20L8S09L0... | Notebook    | [bc583ce6ee](https://linux-hardware.org/?probe=bc583ce6ee) | Jun 01, 2025 |
| Apple         | MacBook4,1                  | Notebook    | [d9ae84f37e](https://linux-hardware.org/?probe=d9ae84f37e) | Jun 01, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ffd469703c](https://linux-hardware.org/?probe=ffd469703c) | May 31, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [dd811105df](https://linux-hardware.org/?probe=dd811105df) | May 29, 2025 |
| Microsoft     | Surface Pro 3               | Tablet      | [0b22d0d79e](https://linux-hardware.org/?probe=0b22d0d79e) | May 29, 2025 |
| Dell          | Latitude 3420               | Notebook    | [b9411d97ee](https://linux-hardware.org/?probe=b9411d97ee) | May 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [cf20a10194](https://linux-hardware.org/?probe=cf20a10194) | May 21, 2025 |
| Chuwi         | LapBook Pro                 | Notebook    | [0be3d742be](https://linux-hardware.org/?probe=0be3d742be) | May 18, 2025 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7a999f67c3](https://linux-hardware.org/?probe=7a999f67c3) | May 13, 2025 |
| HP            | 1998                        | Desktop     | [c1dbae3094](https://linux-hardware.org/?probe=c1dbae3094) | May 12, 2025 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [c5e9db0075](https://linux-hardware.org/?probe=c5e9db0075) | May 10, 2025 |
| Rockchip      | RK3318 BOX                  | Soc         | [7d6a685b06](https://linux-hardware.org/?probe=7d6a685b06) | May 06, 2025 |
| Acer          | Aspire A315-43              | Notebook    | [80f219b944](https://linux-hardware.org/?probe=80f219b944) | May 04, 2025 |
| Google        | Pujjo                       | Notebook    | [19302700df](https://linux-hardware.org/?probe=19302700df) | May 03, 2025 |
| HP            | EliteBook 8460p             | Notebook    | [6149b5debc](https://linux-hardware.org/?probe=6149b5debc) | May 02, 2025 |
| TongFang      | GX4MRXL                     | Notebook    | [2eb600b776](https://linux-hardware.org/?probe=2eb600b776) | May 02, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [9be6c62ee5](https://linux-hardware.org/?probe=9be6c62ee5) | Apr 30, 2025 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [31c032aaab](https://linux-hardware.org/?probe=31c032aaab) | Apr 29, 2025 |
| Dell          | Inspiron 15 7510            | Notebook    | [58f2cd330f](https://linux-hardware.org/?probe=58f2cd330f) | Apr 27, 2025 |
| ASRock        | Z77 Extreme3                | Desktop     | [918024e344](https://linux-hardware.org/?probe=918024e344) | Apr 25, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [dead9d6449](https://linux-hardware.org/?probe=dead9d6449) | Apr 23, 2025 |
| Lenovo        | Yoga Slim 7 14ILL10 83JX    | Notebook    | [c79b637a89](https://linux-hardware.org/?probe=c79b637a89) | Apr 23, 2025 |
| Lenovo        | ThinkCentre M91p 7033C76    | Desktop     | [8ad7c4d196](https://linux-hardware.org/?probe=8ad7c4d196) | Apr 20, 2025 |
| Lenovo        | ThinkPad P51 20HJS0BR0E     | Notebook    | [cb7152ef4a](https://linux-hardware.org/?probe=cb7152ef4a) | Apr 19, 2025 |
| Microsoft     | Surface Laptop 3            | Tablet      | [7ba12a64a8](https://linux-hardware.org/?probe=7ba12a64a8) | Apr 19, 2025 |
| ASUSTek       | GL503VM                     | Notebook    | [6c9e57e895](https://linux-hardware.org/?probe=6c9e57e895) | Apr 18, 2025 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [4947bd8c70](https://linux-hardware.org/?probe=4947bd8c70) | Apr 17, 2025 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | Notebook    | [8d9c12b21a](https://linux-hardware.org/?probe=8d9c12b21a) | Apr 16, 2025 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [7e327c55ff](https://linux-hardware.org/?probe=7e327c55ff) | Apr 13, 2025 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [09f81a9fe8](https://linux-hardware.org/?probe=09f81a9fe8) | Apr 12, 2025 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [77c4f14ad1](https://linux-hardware.org/?probe=77c4f14ad1) | Apr 12, 2025 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [164fad2d68](https://linux-hardware.org/?probe=164fad2d68) | Apr 12, 2025 |
| Lenovo        | Yoga Slim 7 14ILL10 83JX    | Notebook    | [88b6822a08](https://linux-hardware.org/?probe=88b6822a08) | Apr 10, 2025 |
| Supermicro    | X8SIU                       | Desktop     | [879f1f0180](https://linux-hardware.org/?probe=879f1f0180) | Apr 09, 2025 |
| HUAWEI        | MRC-WX0                     | Notebook    | [4007d809cb](https://linux-hardware.org/?probe=4007d809cb) | Apr 07, 2025 |
| ASUSTek       | G15DK                       | Desktop     | [c4cc373af8](https://linux-hardware.org/?probe=c4cc373af8) | Apr 06, 2025 |
| ASUSTek       | G15DK                       | Desktop     | [714b7bb551](https://linux-hardware.org/?probe=714b7bb551) | Apr 04, 2025 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [2162ed7b48](https://linux-hardware.org/?probe=2162ed7b48) | Apr 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [15ec5ab51c](https://linux-hardware.org/?probe=15ec5ab51c) | Apr 03, 2025 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [934f706661](https://linux-hardware.org/?probe=934f706661) | Apr 03, 2025 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6743cc0ccc](https://linux-hardware.org/?probe=6743cc0ccc) | Apr 03, 2025 |
| Dell          | 09KPNV A01                  | Desktop     | [00236a7acd](https://linux-hardware.org/?probe=00236a7acd) | Mar 26, 2025 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [0a78f8643e](https://linux-hardware.org/?probe=0a78f8643e) | Mar 25, 2025 |
| Intel         | NUC7i5BNB J31144-312        | Mini pc     | [07130a86ec](https://linux-hardware.org/?probe=07130a86ec) | Mar 25, 2025 |
| HP            | 355 G2                      | Notebook    | [da41c8fa00](https://linux-hardware.org/?probe=da41c8fa00) | Mar 23, 2025 |
| HP            | 355 G2                      | Notebook    | [8ccd514031](https://linux-hardware.org/?probe=8ccd514031) | Mar 23, 2025 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [057f701781](https://linux-hardware.org/?probe=057f701781) | Mar 21, 2025 |
| Dell          | XPS 15 9550                 | Notebook    | [7761b16ab8](https://linux-hardware.org/?probe=7761b16ab8) | Mar 21, 2025 |
| Alienware     | m17 R2                      | Notebook    | [55c4ba2a35](https://linux-hardware.org/?probe=55c4ba2a35) | Mar 21, 2025 |
| Alienware     | m17 R2                      | Notebook    | [08b2ce6a1a](https://linux-hardware.org/?probe=08b2ce6a1a) | Mar 21, 2025 |
| Apple         | MacBook6,1                  | Notebook    | [48a420e964](https://linux-hardware.org/?probe=48a420e964) | Mar 16, 2025 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [77b2e7b85f](https://linux-hardware.org/?probe=77b2e7b85f) | Mar 14, 2025 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ea6ae957b4](https://linux-hardware.org/?probe=ea6ae957b4) | Mar 14, 2025 |
| MSI           | Z97 PC Mate                 | Desktop     | [090e852926](https://linux-hardware.org/?probe=090e852926) | Mar 14, 2025 |
| Micro Comp... | V3                          | Tablet      | [4caad3c929](https://linux-hardware.org/?probe=4caad3c929) | Mar 14, 2025 |
| Alienware     | m17 R2                      | Notebook    | [b4ba048ec9](https://linux-hardware.org/?probe=b4ba048ec9) | Mar 10, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6b87535141](https://linux-hardware.org/?probe=6b87535141) | Mar 10, 2025 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | Desktop     | [d4653475b4](https://linux-hardware.org/?probe=d4653475b4) | Mar 09, 2025 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [515f6f56bb](https://linux-hardware.org/?probe=515f6f56bb) | Mar 06, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [d8d86946e7](https://linux-hardware.org/?probe=d8d86946e7) | Mar 05, 2025 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [247af323ec](https://linux-hardware.org/?probe=247af323ec) | Mar 04, 2025 |
| HP            | 8768 A                      | Desktop     | [b687e426c9](https://linux-hardware.org/?probe=b687e426c9) | Mar 01, 2025 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [ed8e4cc5ee](https://linux-hardware.org/?probe=ed8e4cc5ee) | Mar 01, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [36b6d03f3b](https://linux-hardware.org/?probe=36b6d03f3b) | Feb 25, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ee43186dc2](https://linux-hardware.org/?probe=ee43186dc2) | Feb 25, 2025 |
| AZW           | MINI S 10                   | Desktop     | [8ef03df6e4](https://linux-hardware.org/?probe=8ef03df6e4) | Feb 23, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [26747b091b](https://linux-hardware.org/?probe=26747b091b) | Feb 21, 2025 |
| Lenovo        | ThinkPad P14s Gen 4 21HG... | Notebook    | [207c8c56a3](https://linux-hardware.org/?probe=207c8c56a3) | Feb 19, 2025 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [fa01335caf](https://linux-hardware.org/?probe=fa01335caf) | Feb 18, 2025 |
| Dell          | 0J3C2F A00                  | Desktop     | [c3abc4d409](https://linux-hardware.org/?probe=c3abc4d409) | Feb 17, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [b6d8ed00a0](https://linux-hardware.org/?probe=b6d8ed00a0) | Feb 16, 2025 |
| Shenzhen D... | MP100                       | Desktop     | [cfa8b4b798](https://linux-hardware.org/?probe=cfa8b4b798) | Feb 15, 2025 |
| Shenzhen D... | MP100                       | Desktop     | [d725129d0f](https://linux-hardware.org/?probe=d725129d0f) | Feb 15, 2025 |
| Samsung       | 960QFG                      | Convertible | [1b27c63988](https://linux-hardware.org/?probe=1b27c63988) | Feb 15, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [f069dadfd7](https://linux-hardware.org/?probe=f069dadfd7) | Feb 15, 2025 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [51f4c4c8a9](https://linux-hardware.org/?probe=51f4c4c8a9) | Feb 14, 2025 |
| Dell          | Latitude 3400               | Notebook    | [6316de7eb8](https://linux-hardware.org/?probe=6316de7eb8) | Feb 13, 2025 |
| Intel         | NUC11TNBi3 M11908-500       | Mini pc     | [1704fd4b60](https://linux-hardware.org/?probe=1704fd4b60) | Feb 13, 2025 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [b64aa64987](https://linux-hardware.org/?probe=b64aa64987) | Feb 12, 2025 |
| Dell          | 0PU052                      | Desktop     | [aa5a42b383](https://linux-hardware.org/?probe=aa5a42b383) | Feb 11, 2025 |
| Dell          | 0PU052                      | Desktop     | [ae72425f6e](https://linux-hardware.org/?probe=ae72425f6e) | Feb 10, 2025 |
| AZW           | MINI S 10                   | Desktop     | [ce558777e8](https://linux-hardware.org/?probe=ce558777e8) | Feb 10, 2025 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [a686b7459e](https://linux-hardware.org/?probe=a686b7459e) | Feb 09, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [7ec3267a63](https://linux-hardware.org/?probe=7ec3267a63) | Feb 06, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [4f16bfb62c](https://linux-hardware.org/?probe=4f16bfb62c) | Feb 06, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [2fa42ecff5](https://linux-hardware.org/?probe=2fa42ecff5) | Feb 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0a2a207aa2](https://linux-hardware.org/?probe=0a2a207aa2) | Feb 04, 2025 |
| ASRock        | A75 Extreme6                | Desktop     | [259c8d624c](https://linux-hardware.org/?probe=259c8d624c) | Feb 03, 2025 |
| Dell          | Precision M4700             | Notebook    | [3f43f6d9b6](https://linux-hardware.org/?probe=3f43f6d9b6) | Feb 03, 2025 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [811d2dc60f](https://linux-hardware.org/?probe=811d2dc60f) | Jan 30, 2025 |
| Dell          | XPS 15 9570                 | Notebook    | [e301d8ed01](https://linux-hardware.org/?probe=e301d8ed01) | Jan 28, 2025 |
| HP            | 255 G6 Notebook PC          | Notebook    | [b945b8159f](https://linux-hardware.org/?probe=b945b8159f) | Jan 28, 2025 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [ce67196c06](https://linux-hardware.org/?probe=ce67196c06) | Jan 26, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e48900314b](https://linux-hardware.org/?probe=e48900314b) | Jan 26, 2025 |
| Lenovo        | ThinkPad E590 20NCA005GI    | Notebook    | [bc2595d887](https://linux-hardware.org/?probe=bc2595d887) | Jan 26, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8d0c94654d](https://linux-hardware.org/?probe=8d0c94654d) | Jan 26, 2025 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [140af0a66d](https://linux-hardware.org/?probe=140af0a66d) | Jan 25, 2025 |
| Dell          | Precision 7530              | Notebook    | [d6e9391b08](https://linux-hardware.org/?probe=d6e9391b08) | Jan 24, 2025 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [33fa5f78bf](https://linux-hardware.org/?probe=33fa5f78bf) | Jan 24, 2025 |
| HP            | 8711                        | Mini pc     | [0692097f23](https://linux-hardware.org/?probe=0692097f23) | Jan 21, 2025 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [bfd86e6390](https://linux-hardware.org/?probe=bfd86e6390) | Jan 21, 2025 |
| Lenovo        | Y50-70 20378                | Notebook    | [6b820e0a67](https://linux-hardware.org/?probe=6b820e0a67) | Jan 19, 2025 |
| HP            | Laptop 15-bs0xx             | Notebook    | [64535b9eb9](https://linux-hardware.org/?probe=64535b9eb9) | Jan 17, 2025 |
| Dell          | Inspiron 7591 2n1           | Convertible | [e1ac85198c](https://linux-hardware.org/?probe=e1ac85198c) | Jan 17, 2025 |
| Dell          | 0Y7V6M A00                  | Desktop     | [5760285e2d](https://linux-hardware.org/?probe=5760285e2d) | Jan 17, 2025 |
| Unknown       | Unknown                     | Notebook    | [fb321de9f1](https://linux-hardware.org/?probe=fb321de9f1) | Jan 17, 2025 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [aad81d4f8e](https://linux-hardware.org/?probe=aad81d4f8e) | Jan 15, 2025 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1f2ac5231b](https://linux-hardware.org/?probe=1f2ac5231b) | Jan 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [6c220b1cf8](https://linux-hardware.org/?probe=6c220b1cf8) | Jan 14, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [abb3061225](https://linux-hardware.org/?probe=abb3061225) | Jan 13, 2025 |
| Gigabyte      | B760 GAMING X AX            | Desktop     | [c97b9a3410](https://linux-hardware.org/?probe=c97b9a3410) | Jan 13, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c48fe7366b](https://linux-hardware.org/?probe=c48fe7366b) | Jan 12, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [14c10b89b2](https://linux-hardware.org/?probe=14c10b89b2) | Jan 12, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [16efaa656c](https://linux-hardware.org/?probe=16efaa656c) | Jan 10, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2b008dec6e](https://linux-hardware.org/?probe=2b008dec6e) | Jan 10, 2025 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [0891556ea8](https://linux-hardware.org/?probe=0891556ea8) | Jan 10, 2025 |
| Dell          | Latitude 7280               | Notebook    | [1673706549](https://linux-hardware.org/?probe=1673706549) | Jan 08, 2025 |
| Dell          | 0JP3NX A00                  | Desktop     | [2a6ef08460](https://linux-hardware.org/?probe=2a6ef08460) | Jan 07, 2025 |
| Dell          | Latitude 5320               | Notebook    | [c7f4eada6c](https://linux-hardware.org/?probe=c7f4eada6c) | Jan 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [28e55a6043](https://linux-hardware.org/?probe=28e55a6043) | Jan 03, 2025 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [9cb18b3ddd](https://linux-hardware.org/?probe=9cb18b3ddd) | Jan 01, 2025 |
| Minix         | NEO Z100-0dB                | All in one  | [7a69de9ac1](https://linux-hardware.org/?probe=7a69de9ac1) | Jan 01, 2025 |
| ASRock        | Z170M Pro4S                 | Desktop     | [14a8e0fe62](https://linux-hardware.org/?probe=14a8e0fe62) | Dec 31, 2024 |
| ASRock        | A75 Extreme6                | Desktop     | [86fd341a89](https://linux-hardware.org/?probe=86fd341a89) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [0de62191fb](https://linux-hardware.org/?probe=0de62191fb) | Dec 30, 2024 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [abef694a7c](https://linux-hardware.org/?probe=abef694a7c) | Dec 21, 2024 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [1015720abc](https://linux-hardware.org/?probe=1015720abc) | Dec 21, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [83995fdfa3](https://linux-hardware.org/?probe=83995fdfa3) | Dec 21, 2024 |
| ASUSTek       | H81-PLUS                    | Desktop     | [b1c71133ae](https://linux-hardware.org/?probe=b1c71133ae) | Dec 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [80d60e6ac6](https://linux-hardware.org/?probe=80d60e6ac6) | Dec 19, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [e35c79dde2](https://linux-hardware.org/?probe=e35c79dde2) | Dec 19, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [7dfcccc6eb](https://linux-hardware.org/?probe=7dfcccc6eb) | Dec 19, 2024 |
| Dell          | 0JP3NX A00                  | Desktop     | [f80311b20d](https://linux-hardware.org/?probe=f80311b20d) | Dec 18, 2024 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [92fad15c25](https://linux-hardware.org/?probe=92fad15c25) | Dec 15, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [3db7006e49](https://linux-hardware.org/?probe=3db7006e49) | Dec 12, 2024 |
| Dell          | 0200DY A02                  | Desktop     | [4cf84c1ce5](https://linux-hardware.org/?probe=4cf84c1ce5) | Dec 06, 2024 |
| Dell          | 0H19HD A07                  | Server      | [a35a094f7e](https://linux-hardware.org/?probe=a35a094f7e) | Dec 06, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [d025744ff8](https://linux-hardware.org/?probe=d025744ff8) | Dec 06, 2024 |
| ASUSTek       | V-P8H67E                    | Desktop     | [d1c21b9076](https://linux-hardware.org/?probe=d1c21b9076) | Dec 03, 2024 |
| Shenzhen M... | F7BSI                       | Mini pc     | [57e49450cb](https://linux-hardware.org/?probe=57e49450cb) | Dec 01, 2024 |
| Dell          | Latitude 5520               | Notebook    | [f1222f143e](https://linux-hardware.org/?probe=f1222f143e) | Nov 28, 2024 |
| ASUSTek       | V-P8H67E                    | Desktop     | [89f2b30be4](https://linux-hardware.org/?probe=89f2b30be4) | Nov 28, 2024 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [da194d6897](https://linux-hardware.org/?probe=da194d6897) | Nov 23, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | Notebook    | [e6e49dc8df](https://linux-hardware.org/?probe=e6e49dc8df) | Nov 23, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b3d142c510](https://linux-hardware.org/?probe=b3d142c510) | Nov 21, 2024 |
| PC Special... | NH5xAx                      | Notebook    | [61b94b9412](https://linux-hardware.org/?probe=61b94b9412) | Nov 18, 2024 |
| Lenovo        | ThinkPad L450 20DT0003MH    | Notebook    | [64603771ce](https://linux-hardware.org/?probe=64603771ce) | Nov 14, 2024 |
| Toshiba       | Satellite C50-B             | Notebook    | [1d473c3a6c](https://linux-hardware.org/?probe=1d473c3a6c) | Nov 12, 2024 |
| Dell          | Latitude 5440               | Notebook    | [b13672d2ba](https://linux-hardware.org/?probe=b13672d2ba) | Nov 03, 2024 |
| Gigabyte      | X870 AORUS ELITE WIFI7      | Desktop     | [5193ed5476](https://linux-hardware.org/?probe=5193ed5476) | Nov 01, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d0f6ac1a5b](https://linux-hardware.org/?probe=d0f6ac1a5b) | Oct 29, 2024 |
| Packard Be... | DOTS2                       | Notebook    | [8c96da9d65](https://linux-hardware.org/?probe=8c96da9d65) | Oct 28, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [03830ecacb](https://linux-hardware.org/?probe=03830ecacb) | Oct 27, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [71dd2a69e3](https://linux-hardware.org/?probe=71dd2a69e3) | Oct 25, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4f16dff63](https://linux-hardware.org/?probe=a4f16dff63) | Oct 25, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Notebook    | [7468eead65](https://linux-hardware.org/?probe=7468eead65) | Oct 24, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [dccda71823](https://linux-hardware.org/?probe=dccda71823) | Oct 22, 2024 |
| Dell          | Latitude 5350               | Notebook    | [58f8fa615d](https://linux-hardware.org/?probe=58f8fa615d) | Oct 21, 2024 |
| Dell          | Latitude 5350               | Notebook    | [b2d8fecadb](https://linux-hardware.org/?probe=b2d8fecadb) | Oct 21, 2024 |
| Dell          | Latitude 5510               | Notebook    | [58a2b04e3e](https://linux-hardware.org/?probe=58a2b04e3e) | Oct 21, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1fb4ba033c](https://linux-hardware.org/?probe=1fb4ba033c) | Oct 19, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Notebook    | [6ecd5007e0](https://linux-hardware.org/?probe=6ecd5007e0) | Oct 19, 2024 |
| Dell          | 0J3C2F A00                  | Desktop     | [13429e7bda](https://linux-hardware.org/?probe=13429e7bda) | Oct 17, 2024 |
| Valve         | Galileo                     | Notebook    | [6fcae86bfc](https://linux-hardware.org/?probe=6fcae86bfc) | Oct 16, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [04dbd52935](https://linux-hardware.org/?probe=04dbd52935) | Oct 10, 2024 |
| System76      | Oryx Pro                    | Notebook    | [4a122791a4](https://linux-hardware.org/?probe=4a122791a4) | Oct 09, 2024 |
| ASRock        | Z77 Extreme3                | Desktop     | [d8afc712e5](https://linux-hardware.org/?probe=d8afc712e5) | Oct 02, 2024 |
| ASRock        | Z77 Extreme3                | Desktop     | [506ca6ed34](https://linux-hardware.org/?probe=506ca6ed34) | Oct 02, 2024 |
| AVITA         | NS14A6                      | Notebook    | [360beece3d](https://linux-hardware.org/?probe=360beece3d) | Oct 01, 2024 |
| Dell          | Inspiron N5040              | Notebook    | [d09e43e3e6](https://linux-hardware.org/?probe=d09e43e3e6) | Oct 01, 2024 |
| Dell          | Latitude E6320              | Notebook    | [e83def8251](https://linux-hardware.org/?probe=e83def8251) | Sep 30, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | Notebook    | [b072f8b0cc](https://linux-hardware.org/?probe=b072f8b0cc) | Sep 29, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [ed4eaaf121](https://linux-hardware.org/?probe=ed4eaaf121) | Sep 29, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [44ffa4ec45](https://linux-hardware.org/?probe=44ffa4ec45) | Sep 29, 2024 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [0da6f1fd46](https://linux-hardware.org/?probe=0da6f1fd46) | Sep 28, 2024 |
| Dell          | 0NW73C A01                  | Desktop     | [a219f52b9b](https://linux-hardware.org/?probe=a219f52b9b) | Sep 25, 2024 |
| Dell          | 0NW73C A01                  | Desktop     | [6f6c30cd6f](https://linux-hardware.org/?probe=6f6c30cd6f) | Sep 25, 2024 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [1984c24a25](https://linux-hardware.org/?probe=1984c24a25) | Sep 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [9a260645fb](https://linux-hardware.org/?probe=9a260645fb) | Sep 23, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [a8471713fe](https://linux-hardware.org/?probe=a8471713fe) | Sep 23, 2024 |
| MSI           | 2AE0                        | Desktop     | [7ccc588275](https://linux-hardware.org/?probe=7ccc588275) | Sep 23, 2024 |
| Google        | Careena                     | Notebook    | [bff7611d3d](https://linux-hardware.org/?probe=bff7611d3d) | Sep 22, 2024 |
| Google        | Careena                     | Notebook    | [34debfe95a](https://linux-hardware.org/?probe=34debfe95a) | Sep 22, 2024 |
| Tactus        | GeoBook 140                 | Notebook    | [a1ce5b2e82](https://linux-hardware.org/?probe=a1ce5b2e82) | Sep 22, 2024 |
| Tactus        | GeoBook 140                 | Notebook    | [b3f597938a](https://linux-hardware.org/?probe=b3f597938a) | Sep 22, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [798c2aed63](https://linux-hardware.org/?probe=798c2aed63) | Sep 22, 2024 |
| Pegatron      | 2A6C                        | Desktop     | [46d503af68](https://linux-hardware.org/?probe=46d503af68) | Sep 21, 2024 |
| System76      | Oryx Pro                    | Notebook    | [6610d42db1](https://linux-hardware.org/?probe=6610d42db1) | Sep 20, 2024 |
| Samsung       | 960QFG                      | Convertible | [f6803427f2](https://linux-hardware.org/?probe=f6803427f2) | Sep 19, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0de24f49c8](https://linux-hardware.org/?probe=0de24f49c8) | Sep 17, 2024 |
| Novatech      | P7xxTM1                     | Notebook    | [d775331611](https://linux-hardware.org/?probe=d775331611) | Sep 15, 2024 |
| Acer          | Aspire 7740                 | Notebook    | [ca477b674b](https://linux-hardware.org/?probe=ca477b674b) | Sep 12, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [f1283f35a2](https://linux-hardware.org/?probe=f1283f35a2) | Sep 12, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [42d52446ef](https://linux-hardware.org/?probe=42d52446ef) | Sep 11, 2024 |
| Acer          | Aspire 8930                 | Notebook    | [73a2294956](https://linux-hardware.org/?probe=73a2294956) | Sep 09, 2024 |
| Foxconn       | 2AA9h                       | Desktop     | [20e06a61c2](https://linux-hardware.org/?probe=20e06a61c2) | Sep 09, 2024 |
| Lenovo        | ThinkPad T410 253722G       | Notebook    | [851485830a](https://linux-hardware.org/?probe=851485830a) | Sep 08, 2024 |
| MSI           | PRO B650-VC WIFI            | Desktop     | [047d37a789](https://linux-hardware.org/?probe=047d37a789) | Sep 08, 2024 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [c5902bc488](https://linux-hardware.org/?probe=c5902bc488) | Sep 06, 2024 |
| ASRock        | AB350M                      | Desktop     | [1cd8bb8d06](https://linux-hardware.org/?probe=1cd8bb8d06) | Sep 03, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [74b60a3b85](https://linux-hardware.org/?probe=74b60a3b85) | Sep 03, 2024 |
| Acer          | Mammoth                     | Notebook    | [ccafd3b2e7](https://linux-hardware.org/?probe=ccafd3b2e7) | Sep 03, 2024 |
| Dell          | 0K240Y A02                  | Desktop     | [8e63f0cc67](https://linux-hardware.org/?probe=8e63f0cc67) | Aug 30, 2024 |
| Dell          | Latitude E7240              | Notebook    | [81904cae54](https://linux-hardware.org/?probe=81904cae54) | Aug 30, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f0b578eaff](https://linux-hardware.org/?probe=f0b578eaff) | Aug 29, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [13091c280d](https://linux-hardware.org/?probe=13091c280d) | Aug 29, 2024 |
| Toshiba       | Satellite Pro C50-A-1E4     | Notebook    | [948af4a150](https://linux-hardware.org/?probe=948af4a150) | Aug 25, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [62f0ae71dd](https://linux-hardware.org/?probe=62f0ae71dd) | Aug 20, 2024 |
| HP            | ZBook 17 G6                 | Notebook    | [e6928ca128](https://linux-hardware.org/?probe=e6928ca128) | Aug 17, 2024 |
| Dell          | 0PRR48 A01                  | Desktop     | [d92db0ea54](https://linux-hardware.org/?probe=d92db0ea54) | Aug 12, 2024 |
| Acer          | Aspire A517-53G             | Notebook    | [cc67b415a8](https://linux-hardware.org/?probe=cc67b415a8) | Aug 10, 2024 |
| Acer          | Aspire A517-53G             | Notebook    | [b746d7a719](https://linux-hardware.org/?probe=b746d7a719) | Aug 09, 2024 |
| Dell          | G3 3500                     | Notebook    | [e36e48651a](https://linux-hardware.org/?probe=e36e48651a) | Aug 07, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [0d84feef29](https://linux-hardware.org/?probe=0d84feef29) | Aug 06, 2024 |
| HP            | ProLiant MicroServer        | Desktop     | [cd4e49eeeb](https://linux-hardware.org/?probe=cd4e49eeeb) | Aug 05, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | Notebook    | [9bc06639cf](https://linux-hardware.org/?probe=9bc06639cf) | Aug 05, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | Notebook    | [a52122bb38](https://linux-hardware.org/?probe=a52122bb38) | Aug 05, 2024 |
| Lenovo        | B50-80 80EW                 | Notebook    | [39cd7e2e3c](https://linux-hardware.org/?probe=39cd7e2e3c) | Aug 03, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [f494d1f180](https://linux-hardware.org/?probe=f494d1f180) | Aug 03, 2024 |
| Tactus        | GeoPad 220                  | Tablet      | [774f6deb38](https://linux-hardware.org/?probe=774f6deb38) | Aug 02, 2024 |
| Tactus        | GeoPad 220                  | Tablet      | [864152a8d0](https://linux-hardware.org/?probe=864152a8d0) | Aug 02, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [d637423290](https://linux-hardware.org/?probe=d637423290) | Aug 01, 2024 |
| Apple         | MacBookPro13,1              | Notebook    | [63e8900b1d](https://linux-hardware.org/?probe=63e8900b1d) | Aug 01, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6b88264648](https://linux-hardware.org/?probe=6b88264648) | Jul 31, 2024 |
| Lenovo        | B50-80 80EW                 | Notebook    | [1896ed136c](https://linux-hardware.org/?probe=1896ed136c) | Jul 23, 2024 |
| Micro Comp... | V3                          | Tablet      | [ecb0dde2ac](https://linux-hardware.org/?probe=ecb0dde2ac) | Jul 20, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [95075ae0bd](https://linux-hardware.org/?probe=95075ae0bd) | Jul 16, 2024 |
| PC Special... | Initia Ii 15                | Notebook    | [e027b0a5a9](https://linux-hardware.org/?probe=e027b0a5a9) | Jul 13, 2024 |
| Gigabyte      | B85-HD3                     | Desktop     | [ce9e0e79fb](https://linux-hardware.org/?probe=ce9e0e79fb) | Jul 10, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [80dbd2fcb8](https://linux-hardware.org/?probe=80dbd2fcb8) | Jul 08, 2024 |
| Google        | Pujjoteen15W                | Notebook    | [0ec95a0e93](https://linux-hardware.org/?probe=0ec95a0e93) | Jul 03, 2024 |
| Dell          | Latitude E5420              | Notebook    | [a140673eb6](https://linux-hardware.org/?probe=a140673eb6) | Jul 01, 2024 |
| Lenovo        | ThinkPad X270 20HN0016MD    | Notebook    | [e01ca65526](https://linux-hardware.org/?probe=e01ca65526) | Jul 01, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [a5cd077129](https://linux-hardware.org/?probe=a5cd077129) | Jun 30, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [1fd69cd28b](https://linux-hardware.org/?probe=1fd69cd28b) | Jun 29, 2024 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | Notebook    | [87e480dac2](https://linux-hardware.org/?probe=87e480dac2) | Jun 20, 2024 |
| HP            | ZBook 17 G6                 | Notebook    | [2095486226](https://linux-hardware.org/?probe=2095486226) | Jun 19, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [c58ac40c49](https://linux-hardware.org/?probe=c58ac40c49) | Jun 17, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [e8badf27ab](https://linux-hardware.org/?probe=e8badf27ab) | Jun 15, 2024 |
| Google        | Minnie                      | Notebook    | [3538fec98e](https://linux-hardware.org/?probe=3538fec98e) | Jun 12, 2024 |
| Acer          | Aspire V3-571               | Notebook    | [5a63cb3389](https://linux-hardware.org/?probe=5a63cb3389) | Jun 10, 2024 |
| Acer          | Aspire V3-571               | Notebook    | [bafbbe0825](https://linux-hardware.org/?probe=bafbbe0825) | Jun 10, 2024 |
| HUAWEI        | WRT-WX9                     | Notebook    | [96b329d349](https://linux-hardware.org/?probe=96b329d349) | Jun 09, 2024 |
| Samsung       | 750XFG                      | Notebook    | [c581b9c2af](https://linux-hardware.org/?probe=c581b9c2af) | Jun 08, 2024 |
| Dell          | Latitude 3420               | Notebook    | [356a53eef2](https://linux-hardware.org/?probe=356a53eef2) | Jun 08, 2024 |
| Dell          | Latitude 3420               | Notebook    | [0b6a5b6ad8](https://linux-hardware.org/?probe=0b6a5b6ad8) | Jun 08, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [75a6e84995](https://linux-hardware.org/?probe=75a6e84995) | Jun 08, 2024 |
| Dell          | 0JP3NX A00                  | Desktop     | [0c47cbeefd](https://linux-hardware.org/?probe=0c47cbeefd) | Jun 03, 2024 |
| HP            | 87D6 SMVB                   | Desktop     | [45c984912b](https://linux-hardware.org/?probe=45c984912b) | Jun 02, 2024 |
| ASUSTek       | X541UAK                     | Notebook    | [1acb106c74](https://linux-hardware.org/?probe=1acb106c74) | Jun 02, 2024 |
| Acer          | Aspire Z5700                | All in one  | [ddd2686715](https://linux-hardware.org/?probe=ddd2686715) | May 31, 2024 |
| Alienware     | 17 R4                       | Notebook    | [b4872ce68c](https://linux-hardware.org/?probe=b4872ce68c) | May 28, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [564a4d2df9](https://linux-hardware.org/?probe=564a4d2df9) | May 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3f1cca26a0](https://linux-hardware.org/?probe=3f1cca26a0) | May 24, 2024 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [b5afb9f441](https://linux-hardware.org/?probe=b5afb9f441) | May 23, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [a36dfede38](https://linux-hardware.org/?probe=a36dfede38) | May 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ede73c3b15](https://linux-hardware.org/?probe=ede73c3b15) | May 22, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [28b6a47300](https://linux-hardware.org/?probe=28b6a47300) | May 22, 2024 |
| Dell          | 0HJ054                      | Desktop     | [8d6c3f640c](https://linux-hardware.org/?probe=8d6c3f640c) | May 22, 2024 |
| Lenovo        | B50-30 80ES                 | Notebook    | [a1857bbe42](https://linux-hardware.org/?probe=a1857bbe42) | May 19, 2024 |
| Lenovo        | B50-30 80ES                 | Notebook    | [5cfe795600](https://linux-hardware.org/?probe=5cfe795600) | May 19, 2024 |
| HP            | Pavilion x2 Detachable      | Tablet      | [1c2db671df](https://linux-hardware.org/?probe=1c2db671df) | May 19, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [b044004def](https://linux-hardware.org/?probe=b044004def) | May 18, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [c96622de49](https://linux-hardware.org/?probe=c96622de49) | May 18, 2024 |
| Alienware     | M11xR3                      | Notebook    | [ebbebdcdf9](https://linux-hardware.org/?probe=ebbebdcdf9) | May 15, 2024 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [a566624747](https://linux-hardware.org/?probe=a566624747) | May 15, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [d05298bbb0](https://linux-hardware.org/?probe=d05298bbb0) | May 14, 2024 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [49d494a8ad](https://linux-hardware.org/?probe=49d494a8ad) | May 11, 2024 |
| Dell          | Inspiron 15 3530            | Notebook    | [a71239f845](https://linux-hardware.org/?probe=a71239f845) | May 05, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [8bc6786d26](https://linux-hardware.org/?probe=8bc6786d26) | May 04, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [5a7379a961](https://linux-hardware.org/?probe=5a7379a961) | May 04, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [239aa09252](https://linux-hardware.org/?probe=239aa09252) | May 04, 2024 |
| HP            | Notebook                    | Notebook    | [3719fa55d8](https://linux-hardware.org/?probe=3719fa55d8) | May 02, 2024 |
| Dell          | Precision 3551              | Notebook    | [1dc964b6fb](https://linux-hardware.org/?probe=1dc964b6fb) | Apr 30, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [43fd55c47a](https://linux-hardware.org/?probe=43fd55c47a) | Apr 30, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [d480d08c5e](https://linux-hardware.org/?probe=d480d08c5e) | Apr 30, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [2349cf6da5](https://linux-hardware.org/?probe=2349cf6da5) | Apr 26, 2024 |
| Toshiba       | Satellite Pro A200          | Notebook    | [305f0f136a](https://linux-hardware.org/?probe=305f0f136a) | Apr 23, 2024 |
| Google        | Morphius                    | Notebook    | [a8361bc931](https://linux-hardware.org/?probe=a8361bc931) | Apr 19, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [d297fd582e](https://linux-hardware.org/?probe=d297fd582e) | Apr 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [46fe84935f](https://linux-hardware.org/?probe=46fe84935f) | Apr 18, 2024 |
| MSI           | PRO B650M-P                 | Desktop     | [90165c7480](https://linux-hardware.org/?probe=90165c7480) | Apr 18, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [24acebde2b](https://linux-hardware.org/?probe=24acebde2b) | Apr 18, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [c0e482caa4](https://linux-hardware.org/?probe=c0e482caa4) | Apr 16, 2024 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [7beaf3fb93](https://linux-hardware.org/?probe=7beaf3fb93) | Apr 14, 2024 |
| Dell          | Latitude E6410              | Notebook    | [af5738b699](https://linux-hardware.org/?probe=af5738b699) | Apr 07, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [36cae1df97](https://linux-hardware.org/?probe=36cae1df97) | Apr 06, 2024 |
| Alienware     | 0TYR0X A01                  | Desktop     | [ef1d3c4e97](https://linux-hardware.org/?probe=ef1d3c4e97) | Apr 04, 2024 |
| HP            | 21D0                        | Desktop     | [8097b780d4](https://linux-hardware.org/?probe=8097b780d4) | Apr 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3bc12b2fdc](https://linux-hardware.org/?probe=3bc12b2fdc) | Mar 31, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e04b94ae7b](https://linux-hardware.org/?probe=e04b94ae7b) | Mar 30, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [69432492b9](https://linux-hardware.org/?probe=69432492b9) | Mar 28, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [45c0437f91](https://linux-hardware.org/?probe=45c0437f91) | Mar 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f1279e5f4](https://linux-hardware.org/?probe=2f1279e5f4) | Mar 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [96e93279ce](https://linux-hardware.org/?probe=96e93279ce) | Mar 21, 2024 |
| Dell          | Latitude E7240              | Notebook    | [bac4c4e0b9](https://linux-hardware.org/?probe=bac4c4e0b9) | Mar 21, 2024 |
| Dell          | Latitude E7240              | Notebook    | [4b2cf432cb](https://linux-hardware.org/?probe=4b2cf432cb) | Mar 19, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9275a0aa01](https://linux-hardware.org/?probe=9275a0aa01) | Mar 18, 2024 |
| Dell          | Precision 7780              | Notebook    | [0cea91e90e](https://linux-hardware.org/?probe=0cea91e90e) | Mar 13, 2024 |
| Dell          | Precision 3551              | Notebook    | [ac0c79297b](https://linux-hardware.org/?probe=ac0c79297b) | Mar 12, 2024 |
| Dell          | Latitude 7490               | Notebook    | [af0f098b77](https://linux-hardware.org/?probe=af0f098b77) | Mar 10, 2024 |
| Lenovo        | ThinkPad X230 2325AEG       | Notebook    | [8e4dbd3b9a](https://linux-hardware.org/?probe=8e4dbd3b9a) | Mar 10, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [10302c2e00](https://linux-hardware.org/?probe=10302c2e00) | Mar 04, 2024 |
| Linx          | LINX1010B                   | Notebook    | [185483454f](https://linux-hardware.org/?probe=185483454f) | Mar 03, 2024 |
| Notebook      | N15_17RD                    | Notebook    | [efc829810d](https://linux-hardware.org/?probe=efc829810d) | Feb 28, 2024 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [bc6b844872](https://linux-hardware.org/?probe=bc6b844872) | Feb 22, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [5f363c641f](https://linux-hardware.org/?probe=5f363c641f) | Feb 22, 2024 |
| ASUSTek       | PRIME B760M-A               | Desktop     | [df41ae1364](https://linux-hardware.org/?probe=df41ae1364) | Feb 20, 2024 |
| HP            | 21D0                        | Desktop     | [a19cdbd10a](https://linux-hardware.org/?probe=a19cdbd10a) | Feb 20, 2024 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [656953e587](https://linux-hardware.org/?probe=656953e587) | Feb 20, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [13aee4c968](https://linux-hardware.org/?probe=13aee4c968) | Feb 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [51257484fe](https://linux-hardware.org/?probe=51257484fe) | Feb 17, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [4a65dda0f2](https://linux-hardware.org/?probe=4a65dda0f2) | Feb 10, 2024 |
| Dell          | Studio XPS 1645             | Notebook    | [cb868b4ea2](https://linux-hardware.org/?probe=cb868b4ea2) | Feb 09, 2024 |
| Google        | Reks                        | Notebook    | [5e667c40ed](https://linux-hardware.org/?probe=5e667c40ed) | Feb 09, 2024 |
| Lenovo        | ThinkPad L13 Gen 2a 21AC... | Notebook    | [a07cdee250](https://linux-hardware.org/?probe=a07cdee250) | Feb 08, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [24d22f38e9](https://linux-hardware.org/?probe=24d22f38e9) | Feb 08, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [abce3a8f48](https://linux-hardware.org/?probe=abce3a8f48) | Feb 06, 2024 |
| Lenovo        | ThinkPad P50 20EQS57700     | Notebook    | [39735c6cd2](https://linux-hardware.org/?probe=39735c6cd2) | Feb 03, 2024 |
| HP            | 21D0                        | Desktop     | [b9cb80ae88](https://linux-hardware.org/?probe=b9cb80ae88) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c8e849a73](https://linux-hardware.org/?probe=0c8e849a73) | Jan 15, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [3717e058ac](https://linux-hardware.org/?probe=3717e058ac) | Jan 13, 2024 |
| Gigabyte      | GA-MA790X-UD4P              | Desktop     | [4e5951814a](https://linux-hardware.org/?probe=4e5951814a) | Jan 09, 2024 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [8101d22b4a](https://linux-hardware.org/?probe=8101d22b4a) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [999111d4e5](https://linux-hardware.org/?probe=999111d4e5) | Jan 09, 2024 |
| Acer          | Aspire ES1-533              | Notebook    | [68d1525855](https://linux-hardware.org/?probe=68d1525855) | Jan 08, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e2b86aade4](https://linux-hardware.org/?probe=e2b86aade4) | Jan 07, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e9337be795](https://linux-hardware.org/?probe=e9337be795) | Jan 07, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [1198f24836](https://linux-hardware.org/?probe=1198f24836) | Jan 04, 2024 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [0781004009](https://linux-hardware.org/?probe=0781004009) | Jan 02, 2024 |
| Medion        | Akoya E6239                 | Notebook    | [757858a876](https://linux-hardware.org/?probe=757858a876) | Dec 31, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [a06265dd1e](https://linux-hardware.org/?probe=a06265dd1e) | Dec 30, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| Dell          | Inspiron 3482               | Notebook    | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| AVITA         | NS14A6                      | Notebook    | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| Toshiba       | Satellite A660              | Notebook    | [d0415e05d3](https://linux-hardware.org/?probe=d0415e05d3) | Dec 23, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1dd35fdb02](https://linux-hardware.org/?probe=1dd35fdb02) | Dec 19, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [18f1d4c5d0](https://linux-hardware.org/?probe=18f1d4c5d0) | Dec 18, 2023 |
| Dell          | Latitude 5400               | Notebook    | [9ae128faf4](https://linux-hardware.org/?probe=9ae128faf4) | Dec 16, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | Notebook    | [91fd392ea3](https://linux-hardware.org/?probe=91fd392ea3) | Dec 14, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | Notebook    | [2dc1349392](https://linux-hardware.org/?probe=2dc1349392) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [647f96ad2c](https://linux-hardware.org/?probe=647f96ad2c) | Dec 08, 2023 |
| Samsung       | 750XED                      | Notebook    | [5263f7ebc0](https://linux-hardware.org/?probe=5263f7ebc0) | Dec 07, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [a84f25d406](https://linux-hardware.org/?probe=a84f25d406) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [6a95e96b1b](https://linux-hardware.org/?probe=6a95e96b1b) | Dec 02, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [8425b9dc62](https://linux-hardware.org/?probe=8425b9dc62) | Nov 30, 2023 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [438812dbd7](https://linux-hardware.org/?probe=438812dbd7) | Nov 27, 2023 |
| Samsung       | 965QFG                      | Convertible | [8769cfd663](https://linux-hardware.org/?probe=8769cfd663) | Nov 27, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| AZW           | Green G3                    | Desktop     | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [2c7d8106d0](https://linux-hardware.org/?probe=2c7d8106d0) | Nov 24, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [9fe4290fb6](https://linux-hardware.org/?probe=9fe4290fb6) | Nov 21, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [93d573033d](https://linux-hardware.org/?probe=93d573033d) | Nov 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0af175a9d7](https://linux-hardware.org/?probe=0af175a9d7) | Nov 19, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [d0f4cc3a98](https://linux-hardware.org/?probe=d0f4cc3a98) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [a76432f7df](https://linux-hardware.org/?probe=a76432f7df) | Nov 16, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [1d3516385d](https://linux-hardware.org/?probe=1d3516385d) | Nov 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e45684a89b](https://linux-hardware.org/?probe=e45684a89b) | Nov 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Alienware     | m18 R1                      | Notebook    | [f4c5c9d2ec](https://linux-hardware.org/?probe=f4c5c9d2ec) | Nov 13, 2023 |
| HP            | Pavilion m6                 | Notebook    | [60a4921f94](https://linux-hardware.org/?probe=60a4921f94) | Nov 13, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [5ad5316ab5](https://linux-hardware.org/?probe=5ad5316ab5) | Nov 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [94186792b2](https://linux-hardware.org/?probe=94186792b2) | Nov 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [d743b33cc7](https://linux-hardware.org/?probe=d743b33cc7) | Nov 05, 2023 |
| System76      | Lemur Pro                   | Notebook    | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [3ba4126936](https://linux-hardware.org/?probe=3ba4126936) | Nov 04, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [440d52f445](https://linux-hardware.org/?probe=440d52f445) | Nov 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Dell          | Latitude 5421               | Notebook    | [670d635ddc](https://linux-hardware.org/?probe=670d635ddc) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1a7844f56d](https://linux-hardware.org/?probe=1a7844f56d) | Oct 30, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [1a28398320](https://linux-hardware.org/?probe=1a28398320) | Oct 26, 2023 |
| HP            | 3399                        | Desktop     | [3dca1c2950](https://linux-hardware.org/?probe=3dca1c2950) | Oct 22, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [c9ab502087](https://linux-hardware.org/?probe=c9ab502087) | Oct 17, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [88057db3aa](https://linux-hardware.org/?probe=88057db3aa) | Oct 11, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45d51130b0](https://linux-hardware.org/?probe=45d51130b0) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [446c6847c3](https://linux-hardware.org/?probe=446c6847c3) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cf79594d59](https://linux-hardware.org/?probe=cf79594d59) | Oct 02, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cb7ac852c](https://linux-hardware.org/?probe=9cb7ac852c) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| Dell          | Latitude 5410               | Notebook    | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [86d39b72d6](https://linux-hardware.org/?probe=86d39b72d6) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Dell          | Latitude 5410               | Notebook    | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Dell          | Latitude 7320               | Notebook    | [2549020a4e](https://linux-hardware.org/?probe=2549020a4e) | Sep 26, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| MSI           | Katana GF76 12UG            | Notebook    | [ee50afcf85](https://linux-hardware.org/?probe=ee50afcf85) | Sep 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [8bf4c79f98](https://linux-hardware.org/?probe=8bf4c79f98) | Sep 17, 2023 |
| HP            | 0B54h D                     | Desktop     | [f5259ad0b1](https://linux-hardware.org/?probe=f5259ad0b1) | Sep 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| Dell          | Latitude E6400              | Notebook    | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| ASUSTek       | TALAS                       | Desktop     | [094153c6f4](https://linux-hardware.org/?probe=094153c6f4) | Sep 04, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [0f98d77b72](https://linux-hardware.org/?probe=0f98d77b72) | Sep 01, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | Notebook    | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [db091802b1](https://linux-hardware.org/?probe=db091802b1) | Aug 26, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [8f51778271](https://linux-hardware.org/?probe=8f51778271) | Aug 25, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7e397373d8](https://linux-hardware.org/?probe=7e397373d8) | Aug 25, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82be53cac0](https://linux-hardware.org/?probe=82be53cac0) | Aug 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2970428ad3](https://linux-hardware.org/?probe=2970428ad3) | Aug 23, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [0182dad759](https://linux-hardware.org/?probe=0182dad759) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8b0d028b37](https://linux-hardware.org/?probe=8b0d028b37) | Aug 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [179beade50](https://linux-hardware.org/?probe=179beade50) | Aug 08, 2023 |
| Dell          | Precision M2800             | Notebook    | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea4d9240fb](https://linux-hardware.org/?probe=ea4d9240fb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [6c13f7a1f0](https://linux-hardware.org/?probe=6c13f7a1f0) | Aug 04, 2023 |
| HP            | 21D0                        | Desktop     | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [928fd8c7cb](https://linux-hardware.org/?probe=928fd8c7cb) | Jul 29, 2023 |
| HP            | 829A                        | Mini pc     | [5bd4fdc8d1](https://linux-hardware.org/?probe=5bd4fdc8d1) | Jul 28, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [8e05eceeef](https://linux-hardware.org/?probe=8e05eceeef) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [5457b19b2b](https://linux-hardware.org/?probe=5457b19b2b) | Jul 26, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [08fd0fea6a](https://linux-hardware.org/?probe=08fd0fea6a) | Jul 26, 2023 |
| HP            | 21D0                        | Desktop     | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [8b128357b4](https://linux-hardware.org/?probe=8b128357b4) | Jul 19, 2023 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [7733080cef](https://linux-hardware.org/?probe=7733080cef) | Jul 19, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| HP            | Pavilion m6                 | Notebook    | [8566e9607f](https://linux-hardware.org/?probe=8566e9607f) | Jul 14, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [0e9916f3e3](https://linux-hardware.org/?probe=0e9916f3e3) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [a72d009fab](https://linux-hardware.org/?probe=a72d009fab) | Jul 13, 2023 |
| HP            | 21D0                        | Desktop     | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Samsung       | 750XED                      | Notebook    | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [aa8cfd7d60](https://linux-hardware.org/?probe=aa8cfd7d60) | Jul 07, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | Desktop     | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | Desktop     | [b24c1d471d](https://linux-hardware.org/?probe=b24c1d471d) | Jul 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Shenzhen W... | AERO 5 Lite Mini PC         | Mini pc     | [7375ced625](https://linux-hardware.org/?probe=7375ced625) | Jun 30, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3e2928fe9d](https://linux-hardware.org/?probe=3e2928fe9d) | Jun 23, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [ae5f4be943](https://linux-hardware.org/?probe=ae5f4be943) | Jun 20, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [913d8d26b9](https://linux-hardware.org/?probe=913d8d26b9) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | Notebook    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [8678eeac9b](https://linux-hardware.org/?probe=8678eeac9b) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Notebook    | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| HP            | 0AECh D                     | Desktop     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| HP            | ZBook 15                    | Notebook    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [a3798147d9](https://linux-hardware.org/?probe=a3798147d9) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [f2655b5798](https://linux-hardware.org/?probe=f2655b5798) | May 24, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [2bed616680](https://linux-hardware.org/?probe=2bed616680) | May 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [785f4bad86](https://linux-hardware.org/?probe=785f4bad86) | May 23, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63c991635f](https://linux-hardware.org/?probe=63c991635f) | May 17, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [46b31c9243](https://linux-hardware.org/?probe=46b31c9243) | May 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e21cdf9e37](https://linux-hardware.org/?probe=e21cdf9e37) | May 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed810bd154](https://linux-hardware.org/?probe=ed810bd154) | May 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [d6598957ff](https://linux-hardware.org/?probe=d6598957ff) | May 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [51eba04846](https://linux-hardware.org/?probe=51eba04846) | May 08, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [c223c83063](https://linux-hardware.org/?probe=c223c83063) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [983ec204ab](https://linux-hardware.org/?probe=983ec204ab) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3ba3358e4d](https://linux-hardware.org/?probe=3ba3358e4d) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Dell          | Latitude E5520              | Notebook    | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f543ce6c65](https://linux-hardware.org/?probe=f543ce6c65) | Apr 29, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [261c116001](https://linux-hardware.org/?probe=261c116001) | Apr 28, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [f2b702b631](https://linux-hardware.org/?probe=f2b702b631) | Apr 28, 2023 |
| Dell          | Latitude 7420               | Notebook    | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [84ae892fb4](https://linux-hardware.org/?probe=84ae892fb4) | Apr 19, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88b9080a8c](https://linux-hardware.org/?probe=88b9080a8c) | Apr 17, 2023 |
| Dell          | Latitude 7420               | Notebook    | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [690ed7960a](https://linux-hardware.org/?probe=690ed7960a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63574c5adf](https://linux-hardware.org/?probe=63574c5adf) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [beeb850c3b](https://linux-hardware.org/?probe=beeb850c3b) | Apr 09, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | G752VM                      | Notebook    | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ab9916feea](https://linux-hardware.org/?probe=ab9916feea) | Apr 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7e97eb6308](https://linux-hardware.org/?probe=7e97eb6308) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Dell          | 0TP412                      | Desktop     | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [4f8515b9ed](https://linux-hardware.org/?probe=4f8515b9ed) | Mar 27, 2023 |
| HP            | 0B54h D                     | Desktop     | [3edc678017](https://linux-hardware.org/?probe=3edc678017) | Mar 26, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| Timi          | A35S                        | Notebook    | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5cbf68e6d](https://linux-hardware.org/?probe=f5cbf68e6d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 8715                        | Mini pc     | [9ce704a4b9](https://linux-hardware.org/?probe=9ce704a4b9) | Mar 23, 2023 |
| MSI           | GP72 7RE                    | Notebook    | [729f2297cb](https://linux-hardware.org/?probe=729f2297cb) | Mar 23, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [dab7a6edbc](https://linux-hardware.org/?probe=dab7a6edbc) | Mar 22, 2023 |
| Dell          | Latitude 7420               | Notebook    | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| HP            | 83E9                        | Desktop     | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c462ccc41a](https://linux-hardware.org/?probe=c462ccc41a) | Mar 19, 2023 |
| Samsung       | 940XFG                      | Notebook    | [566a4046f6](https://linux-hardware.org/?probe=566a4046f6) | Mar 18, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [9d0ac027df](https://linux-hardware.org/?probe=9d0ac027df) | Mar 14, 2023 |
| Google        | Reks                        | Notebook    | [56296236c5](https://linux-hardware.org/?probe=56296236c5) | Mar 12, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [f6da200721](https://linux-hardware.org/?probe=f6da200721) | Mar 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [56e5783575](https://linux-hardware.org/?probe=56e5783575) | Mar 11, 2023 |
| HP            | ProBook 4330s               | Notebook    | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Google        | Reks                        | Notebook    | [f877db79d3](https://linux-hardware.org/?probe=f877db79d3) | Mar 09, 2023 |
| Intel         | ArcherCity                  | Server      | [3ddb00da94](https://linux-hardware.org/?probe=3ddb00da94) | Mar 08, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [a541fe5881](https://linux-hardware.org/?probe=a541fe5881) | Mar 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| Dell          | Latitude 7420               | Notebook    | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| Dell          | 0JC474                      | Desktop     | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [8078d7ca28](https://linux-hardware.org/?probe=8078d7ca28) | Mar 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d70aeca173](https://linux-hardware.org/?probe=d70aeca173) | Mar 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a23a00a71e](https://linux-hardware.org/?probe=a23a00a71e) | Mar 02, 2023 |
| Dell          | Latitude 7420               | Notebook    | [49bdd8711f](https://linux-hardware.org/?probe=49bdd8711f) | Mar 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [2b007293f7](https://linux-hardware.org/?probe=2b007293f7) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd415a086a](https://linux-hardware.org/?probe=bd415a086a) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [dcaa80ec62](https://linux-hardware.org/?probe=dcaa80ec62) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [91405b88cc](https://linux-hardware.org/?probe=91405b88cc) | Feb 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [d3af27a0ac](https://linux-hardware.org/?probe=d3af27a0ac) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d032f0a547](https://linux-hardware.org/?probe=d032f0a547) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b6f7c77e33](https://linux-hardware.org/?probe=b6f7c77e33) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1d62ae4e43](https://linux-hardware.org/?probe=1d62ae4e43) | Feb 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [813066eda5](https://linux-hardware.org/?probe=813066eda5) | Feb 19, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [0496d0bbcf](https://linux-hardware.org/?probe=0496d0bbcf) | Feb 18, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [ba5a46ec10](https://linux-hardware.org/?probe=ba5a46ec10) | Feb 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [fdab522500](https://linux-hardware.org/?probe=fdab522500) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [dd863b4bdf](https://linux-hardware.org/?probe=dd863b4bdf) | Feb 17, 2023 |
| Foxconn       | H67M-S/H67M-V/H67M          | Desktop     | [78dc1c5856](https://linux-hardware.org/?probe=78dc1c5856) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [8de835c5da](https://linux-hardware.org/?probe=8de835c5da) | Feb 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fb6daef60c](https://linux-hardware.org/?probe=fb6daef60c) | Feb 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3206e7be82](https://linux-hardware.org/?probe=3206e7be82) | Feb 16, 2023 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [4891d8306b](https://linux-hardware.org/?probe=4891d8306b) | Feb 15, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [73f7fb3f85](https://linux-hardware.org/?probe=73f7fb3f85) | Feb 15, 2023 |
| Dell          | G15 5520                    | Notebook    | [a5966eaac0](https://linux-hardware.org/?probe=a5966eaac0) | Feb 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [cc77f75f3d](https://linux-hardware.org/?probe=cc77f75f3d) | Feb 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [011e8929fa](https://linux-hardware.org/?probe=011e8929fa) | Feb 15, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [e689bce0ca](https://linux-hardware.org/?probe=e689bce0ca) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [bc1c7ec97f](https://linux-hardware.org/?probe=bc1c7ec97f) | Feb 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7e81f35584](https://linux-hardware.org/?probe=7e81f35584) | Feb 13, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [b1b8672218](https://linux-hardware.org/?probe=b1b8672218) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c17ac89917](https://linux-hardware.org/?probe=c17ac89917) | Feb 11, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [181833b556](https://linux-hardware.org/?probe=181833b556) | Feb 09, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [6a589cafec](https://linux-hardware.org/?probe=6a589cafec) | Feb 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [43b52ad56f](https://linux-hardware.org/?probe=43b52ad56f) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [275ce1a7fc](https://linux-hardware.org/?probe=275ce1a7fc) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef988ae85](https://linux-hardware.org/?probe=aef988ae85) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0f24e9c32c](https://linux-hardware.org/?probe=0f24e9c32c) | Feb 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a838bfb720](https://linux-hardware.org/?probe=a838bfb720) | Feb 04, 2023 |
| Shenzhen W... | AERO 5 Lite Mini PC         | Mini pc     | [cd8f74acd2](https://linux-hardware.org/?probe=cd8f74acd2) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [50727dbbde](https://linux-hardware.org/?probe=50727dbbde) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0b0eaa5c48](https://linux-hardware.org/?probe=0b0eaa5c48) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe2d2d279](https://linux-hardware.org/?probe=2fe2d2d279) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [995da6b474](https://linux-hardware.org/?probe=995da6b474) | Jan 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0323a2bd47](https://linux-hardware.org/?probe=0323a2bd47) | Jan 27, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe7cc7865](https://linux-hardware.org/?probe=2fe7cc7865) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [8ae5c7adec](https://linux-hardware.org/?probe=8ae5c7adec) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b87a9b3447](https://linux-hardware.org/?probe=b87a9b3447) | Jan 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c7c957ccb3](https://linux-hardware.org/?probe=c7c957ccb3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [09735072af](https://linux-hardware.org/?probe=09735072af) | Jan 23, 2023 |
| Dell          | Latitude 7420               | Notebook    | [dc99eb6c92](https://linux-hardware.org/?probe=dc99eb6c92) | Jan 23, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4f65820da4](https://linux-hardware.org/?probe=4f65820da4) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [01e83b7640](https://linux-hardware.org/?probe=01e83b7640) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [70b4ca8de7](https://linux-hardware.org/?probe=70b4ca8de7) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [7fb655b498](https://linux-hardware.org/?probe=7fb655b498) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [397b4da9ab](https://linux-hardware.org/?probe=397b4da9ab) | Jan 21, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [93932bdc92](https://linux-hardware.org/?probe=93932bdc92) | Jan 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2ad3ad8258](https://linux-hardware.org/?probe=2ad3ad8258) | Jan 20, 2023 |
| Dell          | G5 5590                     | Notebook    | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude 5510               | Notebook    | [c9738f8691](https://linux-hardware.org/?probe=c9738f8691) | Jan 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [b5b4cde08e](https://linux-hardware.org/?probe=b5b4cde08e) | Jan 18, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [fa1a881ee9](https://linux-hardware.org/?probe=fa1a881ee9) | Jan 17, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6941e3520e](https://linux-hardware.org/?probe=6941e3520e) | Jan 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [24d62d6974](https://linux-hardware.org/?probe=24d62d6974) | Jan 17, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [5905971b70](https://linux-hardware.org/?probe=5905971b70) | Jan 16, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [389b01b49a](https://linux-hardware.org/?probe=389b01b49a) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4c3d300ccc](https://linux-hardware.org/?probe=4c3d300ccc) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1ad37ae4cc](https://linux-hardware.org/?probe=1ad37ae4cc) | Jan 13, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [d390e11930](https://linux-hardware.org/?probe=d390e11930) | Jan 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [a181d83115](https://linux-hardware.org/?probe=a181d83115) | Jan 11, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4ce659b05d](https://linux-hardware.org/?probe=4ce659b05d) | Jan 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| Star Labs     | Lite                        | Notebook    | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef797585c](https://linux-hardware.org/?probe=aef797585c) | Jan 09, 2023 |
| Dell          | Latitude 7420               | Notebook    | [cd159088a3](https://linux-hardware.org/?probe=cd159088a3) | Jan 09, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [ec306ce0f9](https://linux-hardware.org/?probe=ec306ce0f9) | Jan 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [81269f2363](https://linux-hardware.org/?probe=81269f2363) | Jan 04, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [21b5ec2d81](https://linux-hardware.org/?probe=21b5ec2d81) | Jan 03, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [1b8d741ea3](https://linux-hardware.org/?probe=1b8d741ea3) | Jan 03, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a51048ad0a](https://linux-hardware.org/?probe=a51048ad0a) | Jan 01, 2023 |
| Samsung       | 940XFG                      | Notebook    | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e7ac43e8c3](https://linux-hardware.org/?probe=e7ac43e8c3) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4d613961a4](https://linux-hardware.org/?probe=4d613961a4) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1780cf9c13](https://linux-hardware.org/?probe=1780cf9c13) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c93684da4d](https://linux-hardware.org/?probe=c93684da4d) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c9cadd190](https://linux-hardware.org/?probe=5c9cadd190) | Dec 28, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5ea84f62cb](https://linux-hardware.org/?probe=5ea84f62cb) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3fc3ad1b46](https://linux-hardware.org/?probe=3fc3ad1b46) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [afb738446f](https://linux-hardware.org/?probe=afb738446f) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [91a9d07c9f](https://linux-hardware.org/?probe=91a9d07c9f) | Dec 22, 2022 |
| Intel         | DQ77CP AAG67261-300         | Desktop     | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0b63acf3b2](https://linux-hardware.org/?probe=0b63acf3b2) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [660c9e5023](https://linux-hardware.org/?probe=660c9e5023) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [54fbda3732](https://linux-hardware.org/?probe=54fbda3732) | Dec 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [da494e2be3](https://linux-hardware.org/?probe=da494e2be3) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1bd00059e2](https://linux-hardware.org/?probe=1bd00059e2) | Dec 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7236ad8a5d](https://linux-hardware.org/?probe=7236ad8a5d) | Dec 17, 2022 |
| Dell          | Latitude 7420               | Notebook    | [60f07d5a45](https://linux-hardware.org/?probe=60f07d5a45) | Dec 16, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2991f8736b](https://linux-hardware.org/?probe=2991f8736b) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [69776fdb13](https://linux-hardware.org/?probe=69776fdb13) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [09c89a9bef](https://linux-hardware.org/?probe=09c89a9bef) | Dec 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed707b6698](https://linux-hardware.org/?probe=ed707b6698) | Dec 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c91212b8ed](https://linux-hardware.org/?probe=c91212b8ed) | Dec 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88196a712d](https://linux-hardware.org/?probe=88196a712d) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [57e8e4ab79](https://linux-hardware.org/?probe=57e8e4ab79) | Dec 06, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| Dell          | Latitude 7290               | Notebook    | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | Notebook    | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [7bdc87a5cc](https://linux-hardware.org/?probe=7bdc87a5cc) | Dec 02, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [d17ff52554](https://linux-hardware.org/?probe=d17ff52554) | Dec 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [080e04d17d](https://linux-hardware.org/?probe=080e04d17d) | Dec 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c4ae439087](https://linux-hardware.org/?probe=c4ae439087) | Nov 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c395ef8a4](https://linux-hardware.org/?probe=5c395ef8a4) | Nov 26, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [0c97f1e481](https://linux-hardware.org/?probe=0c97f1e481) | Nov 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [587e23a674](https://linux-hardware.org/?probe=587e23a674) | Nov 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | Notebook    | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4ac6dbf9b](https://linux-hardware.org/?probe=a4ac6dbf9b) | Nov 17, 2022 |
| Chuwi         | X312B                       | Notebook    | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [11dbbdfcc1](https://linux-hardware.org/?probe=11dbbdfcc1) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [02aab6ab70](https://linux-hardware.org/?probe=02aab6ab70) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | Notebook    | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [74a1e6875a](https://linux-hardware.org/?probe=74a1e6875a) | Nov 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c03daa3621](https://linux-hardware.org/?probe=c03daa3621) | Nov 08, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a5700bebdf](https://linux-hardware.org/?probe=a5700bebdf) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d89464b05](https://linux-hardware.org/?probe=5d89464b05) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [8b457c11e8](https://linux-hardware.org/?probe=8b457c11e8) | Oct 23, 2022 |
| Dell          | Latitude E6440              | Notebook    | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| Dell          | Latitude 7400               | Notebook    | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | Notebook    | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | Notebook    | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | 21D0                        | Desktop     | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [26df10ca7d](https://linux-hardware.org/?probe=26df10ca7d) | Oct 02, 2022 |
| Timi          | TM1709                      | Notebook    | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [da0b586e04](https://linux-hardware.org/?probe=da0b586e04) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b389a760a8](https://linux-hardware.org/?probe=b389a760a8) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Pavilion m6                 | Notebook    | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | Notebook    | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [296fc14c83](https://linux-hardware.org/?probe=296fc14c83) | Aug 26, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | Notebook    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | Notebook    | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [531e4340a6](https://linux-hardware.org/?probe=531e4340a6) | Aug 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd2dbeaa0e](https://linux-hardware.org/?probe=bd2dbeaa0e) | Aug 02, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d83f785b08](https://linux-hardware.org/?probe=d83f785b08) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Samsung       | 935XDB                      | Notebook    | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [033c284273](https://linux-hardware.org/?probe=033c284273) | Jul 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8d0399bc8d](https://linux-hardware.org/?probe=8d0399bc8d) | Jul 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ef61582503](https://linux-hardware.org/?probe=ef61582503) | Jul 16, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Jumper        | EZbook                      | Notebook    | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | Notebook    | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1bde29740](https://linux-hardware.org/?probe=c1bde29740) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | Notebook    | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | Desktop     | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Rockchip      | Unknown                     | Soc         | [fcef507e8e](https://linux-hardware.org/?probe=fcef507e8e) | Mar 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5723ec8b7](https://linux-hardware.org/?probe=f5723ec8b7) | Mar 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [27548876c6](https://linux-hardware.org/?probe=27548876c6) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0eaf02ff7d](https://linux-hardware.org/?probe=0eaf02ff7d) | Mar 07, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ireland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 88        | 7.86%   |
| Ubuntu 22.04       | 48        | 4.29%   |
| Ubuntu 18.04       | 45        | 4.02%   |
| Pop!_OS 22.04      | 31        | 2.77%   |
| Arch Rolling       | 30        | 2.68%   |
| Debian 11          | 29        | 2.59%   |
| Ubuntu 24.04       | 28        | 2.5%    |
| Zorin 17           | 25        | 2.23%   |
| Debian 12          | 22        | 1.97%   |
| Fedora 40          | 18        | 1.61%   |
| Zorin 16           | 16        | 1.43%   |
| ArcoLinux Rolling  | 15        | 1.34%   |
| Linux Mint 21.3    | 14        | 1.25%   |
| Fedora 42          | 14        | 1.25%   |
| Manjaro            | 13        | 1.16%   |
| OpenMandriva 4.2   | 12        | 1.07%   |
| Linux Mint 21.1    | 12        | 1.07%   |
| Linux Mint 20.2    | 12        | 1.07%   |
| Fedora 38          | 12        | 1.07%   |
| OpenMandriva 24.12 | 11        | 0.98%   |
| Linux Mint 21.2    | 11        | 0.98%   |
| Linux Mint 20      | 11        | 0.98%   |
| Fedora 37          | 11        | 0.98%   |
| Arch               | 11        | 0.98%   |
| Ubuntu 22.10       | 10        | 0.89%   |
| Linux Mint 20.3    | 10        | 0.89%   |
| Fedora 36          | 10        | 0.89%   |
| Debian 10          | 10        | 0.89%   |
| Ubuntu 19.04       | 9         | 0.8%    |
| Pop!_OS 21.10      | 9         | 0.8%    |
| OpenMandriva 23.01 | 9         | 0.8%    |
| Ubuntu 23.04       | 8         | 0.71%   |
| Pop!_OS 20.10      | 8         | 0.71%   |
| Linux Mint 22.1    | 8         | 0.71%   |
| Fedora 39          | 8         | 0.71%   |
| Debian             | 8         | 0.71%   |
| Pop!_OS 20.04      | 7         | 0.63%   |
| OpenMandriva 4.3   | 7         | 0.63%   |
| OpenMandriva 25.06 | 7         | 0.63%   |
| Linux Mint 22      | 7         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 251       | 23.9%   |
| Linux Mint    | 111       | 10.57%  |
| Fedora        | 98        | 9.33%   |
| OpenMandriva  | 85        | 8.1%    |
| Debian        | 82        | 7.81%   |
| Pop!_OS       | 54        | 5.14%   |
| Zorin         | 50        | 4.76%   |
| Arch          | 41        | 3.9%    |
| Manjaro       | 29        | 2.76%   |
| Kubuntu       | 24        | 2.29%   |
| KDE neon      | 17        | 1.62%   |
| ArcoLinux     | 15        | 1.43%   |
| ROSA          | 14        | 1.33%   |
| Elementary    | 14        | 1.33%   |
| Bazzite       | 14        | 1.33%   |
| SteamOS       | 13        | 1.24%   |
| BlackPanther  | 13        | 1.24%   |
| Xubuntu       | 9         | 0.86%   |
| Lubuntu       | 9         | 0.86%   |
| Gentoo        | 9         | 0.86%   |
| openSUSE      | 8         | 0.76%   |
| MX            | 8         | 0.76%   |
| Ubuntu Budgie | 6         | 0.57%   |
| Endless       | 6         | 0.57%   |
| Ubuntu Unity  | 5         | 0.48%   |
| Ubuntu MATE   | 5         | 0.48%   |
| LMDE          | 5         | 0.48%   |
| CentOS        | 5         | 0.48%   |
| RHEL          | 4         | 0.38%   |
| Kali          | 4         | 0.38%   |
| EndeavourOS   | 4         | 0.38%   |
| CachyOS       | 4         | 0.38%   |
| Parrot        | 3         | 0.29%   |
| Nobara        | 3         | 0.29%   |
| Clear Linux   | 3         | 0.29%   |
| Rocky Linux   | 2         | 0.19%   |
| Peppermint    | 2         | 0.19%   |
| Linux Lite    | 2         | 0.19%   |
| Garuda Linux  | 2         | 0.19%   |
| BigLinux      | 2         | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 1.22%   |
| 6.14.2-desktop-3omv2590  | 13        | 1.06%   |
| 5.10.14-desktop-1omv4002 | 12        | 0.98%   |
| 5.3.0-46-generic         | 10        | 0.81%   |
| 6.8.0-51-generic         | 9         | 0.73%   |
| 5.15.0-91-generic        | 9         | 0.73%   |
| 6.12.9-desktop-1omv2490  | 8         | 0.65%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.65%   |
| 5.15.0-56-generic        | 8         | 0.65%   |
| 5.15.0-46-generic        | 8         | 0.65%   |
| 6.8.0-52-generic         | 7         | 0.57%   |
| 5.19.0-35-generic        | 7         | 0.57%   |
| 5.16.7-desktop-1omv4003  | 7         | 0.57%   |
| 5.10.0-23-amd64          | 7         | 0.57%   |
| 6.5.0-26-generic         | 6         | 0.49%   |
| 6.4.11-desktop-1omv2390  | 6         | 0.49%   |
| 6.2.0-26-generic         | 6         | 0.49%   |
| 6.12.1-desktop-1omv2490  | 6         | 0.49%   |
| 5.4.0-52-generic         | 6         | 0.49%   |
| 5.15.0-67-generic        | 6         | 0.49%   |
| 5.15.0-52-generic        | 6         | 0.49%   |
| 4.18.16-desktop-1bP      | 6         | 0.49%   |
| 6.9.3-76060903-generic   | 5         | 0.41%   |
| 6.8.0-49-generic         | 5         | 0.41%   |
| 6.8.0-45-generic         | 5         | 0.41%   |
| 6.2.6-desktop-1omv2390   | 5         | 0.41%   |
| 6.2.0-39-generic         | 5         | 0.41%   |
| 6.2.0-20-generic         | 5         | 0.41%   |
| 6.14.0-36-generic        | 5         | 0.41%   |
| 6.12.48+deb13-amd64      | 5         | 0.41%   |
| 5.4.0-91-generic         | 5         | 0.41%   |
| 5.4.0-72-generic         | 5         | 0.41%   |
| 5.4.0-48-generic         | 5         | 0.41%   |
| 5.19.0-29-generic        | 5         | 0.41%   |
| 5.11.0-27-generic        | 5         | 0.41%   |
| 6.8.0-88-generic         | 4         | 0.33%   |
| 6.8.0-65-generic         | 4         | 0.33%   |
| 6.8.0-60-generic         | 4         | 0.33%   |
| 6.8.0-57-generic         | 4         | 0.33%   |
| 6.8.0-40-generic         | 4         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 122       | 10.54%  |
| 5.15.0  | 84        | 7.25%   |
| 6.8.0   | 70        | 6.04%   |
| 5.19.0  | 37        | 3.2%    |
| 4.15.0  | 37        | 3.2%    |
| 6.5.0   | 31        | 2.68%   |
| 6.2.0   | 28        | 2.42%   |
| 6.14.0  | 28        | 2.42%   |
| 5.8.0   | 28        | 2.42%   |
| 5.11.0  | 28        | 2.42%   |
| 5.10.0  | 28        | 2.42%   |
| 5.3.0   | 26        | 2.25%   |
| 6.1.0   | 24        | 2.07%   |
| 5.13.0  | 22        | 1.9%    |
| 5.0.0   | 15        | 1.3%    |
| 6.14.2  | 13        | 1.12%   |
| 6.12.9  | 13        | 1.12%   |
| 5.10.14 | 12        | 1.04%   |
| 4.19.0  | 11        | 0.95%   |
| 4.18.0  | 11        | 0.95%   |
| 6.2.6   | 9         | 0.78%   |
| 6.11.0  | 9         | 0.78%   |
| 6.1.1   | 8         | 0.69%   |
| 5.17.5  | 8         | 0.69%   |
| 5.14.0  | 8         | 0.69%   |
| 6.17.7  | 7         | 0.6%    |
| 5.16.7  | 7         | 0.6%    |
| 6.9.3   | 6         | 0.52%   |
| 6.4.11  | 6         | 0.52%   |
| 6.3.8   | 6         | 0.52%   |
| 6.12.1  | 6         | 0.52%   |
| 4.18.16 | 6         | 0.52%   |
| 6.6.2   | 5         | 0.43%   |
| 6.12.48 | 5         | 0.43%   |
| 6.10.9  | 5         | 0.43%   |
| 6.9.12  | 4         | 0.35%   |
| 6.6.32  | 4         | 0.35%   |
| 6.5.6   | 4         | 0.35%   |
| 6.16.4  | 4         | 0.35%   |
| 6.12.6  | 4         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 128       | 11.23%  |
| 5.15    | 103       | 9.04%   |
| 6.8     | 80        | 7.02%   |
| 5.10    | 54        | 4.74%   |
| 6.1     | 49        | 4.3%    |
| 6.14    | 48        | 4.21%   |
| 6.2     | 45        | 3.95%   |
| 6.12    | 45        | 3.95%   |
| 5.19    | 44        | 3.86%   |
| 6.5     | 39        | 3.42%   |
| 4.15    | 37        | 3.25%   |
| 5.8     | 35        | 3.07%   |
| 5.11    | 34        | 2.98%   |
| 5.13    | 28        | 2.46%   |
| 5.3     | 27        | 2.37%   |
| 6.6     | 23        | 2.02%   |
| 6.0     | 23        | 2.02%   |
| 6.11    | 19        | 1.67%   |
| 6.9     | 17        | 1.49%   |
| 5.16    | 17        | 1.49%   |
| 4.18    | 17        | 1.49%   |
| 6.17    | 16        | 1.4%    |
| 6.10    | 16        | 1.4%    |
| 5.17    | 15        | 1.32%   |
| 5.0     | 15        | 1.32%   |
| 6.16    | 14        | 1.23%   |
| 5.14    | 14        | 1.23%   |
| 6.4     | 13        | 1.14%   |
| 4.19    | 13        | 1.14%   |
| 6.3     | 12        | 1.05%   |
| 6.13    | 11        | 0.96%   |
| 5.18    | 11        | 0.96%   |
| 4.9     | 11        | 0.96%   |
| 5.6     | 10        | 0.88%   |
| 6.15    | 9         | 0.79%   |
| 5.12    | 9         | 0.79%   |
| 5.7     | 7         | 0.61%   |
| 6.7     | 5         | 0.44%   |
| 5.9     | 5         | 0.44%   |
| 6.18    | 4         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 979       | 97.41%  |
| i686    | 16        | 1.59%   |
| aarch64 | 9         | 0.9%    |
| armv7l  | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 451       | 42.67%  |
| KDE5            | 147       | 13.91%  |
| Unknown         | 101       | 9.56%   |
| X-Cinnamon      | 91        | 8.61%   |
| KDE6            | 78        | 7.38%   |
| XFCE            | 75        | 7.1%    |
| KDE             | 20        | 1.89%   |
| MATE            | 18        | 1.7%    |
| Pantheon        | 13        | 1.23%   |
| LXQt            | 10        | 0.95%   |
| Cinnamon        | 9         | 0.85%   |
| KDE4            | 8         | 0.76%   |
| Budgie          | 7         | 0.66%   |
| i3              | 6         | 0.57%   |
| Unity           | 5         | 0.47%   |
| Hyprland        | 4         | 0.38%   |
| GNOME Flashback | 3         | 0.28%   |
| LXDE            | 2         | 0.19%   |
| GNOME Classic   | 2         | 0.19%   |
| X-Generic       | 1         | 0.09%   |
| LeftWM          | 1         | 0.09%   |
| Enlightenment   | 1         | 0.09%   |
| Endless:GNOME   | 1         | 0.09%   |
| DWM             | 1         | 0.09%   |
| COSMIC          | 1         | 0.09%   |
| BunsenLabs      | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 674       | 65.18%  |
| Wayland | 289       | 27.95%  |
| Unknown | 48        | 4.64%   |
| Tty     | 23        | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 488       | 46.39%  |
| SDDM           | 181       | 17.21%  |
| GDM3           | 126       | 11.98%  |
| LightDM        | 121       | 11.5%   |
| GDM            | 104       | 9.89%   |
| TDM            | 19        | 1.81%   |
| KDM            | 7         | 0.67%   |
| LXDM           | 2         | 0.19%   |
| SLiM           | 1         | 0.1%    |
| MDM            | 1         | 0.1%    |
| Ly             | 1         | 0.1%    |
| COSMIC-GREETER | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_IE      | 480       | 45.76%  |
| en_GB      | 220       | 20.97%  |
| en_US      | 200       | 19.07%  |
| Unknown    | 75        | 7.15%   |
| pl_PL      | 18        | 1.72%   |
| C          | 15        | 1.43%   |
| hu_HU      | 4         | 0.38%   |
| de_DE      | 4         | 0.38%   |
| ru_RU      | 3         | 0.29%   |
| es_ES      | 3         | 0.29%   |
| en_IN      | 3         | 0.29%   |
| uk_UA      | 2         | 0.19%   |
| pt_BR      | 2         | 0.19%   |
| lt_LT      | 2         | 0.19%   |
| fr_FR      | 2         | 0.19%   |
| en_CA      | 2         | 0.19%   |
| bg_BG      | 2         | 0.19%   |
| zh_CN      | 1         | 0.1%    |
| pt_PT      | 1         | 0.1%    |
| it_IT      | 1         | 0.1%    |
| ga_IE.UTF8 | 1         | 0.1%    |
| ga_IE      | 1         | 0.1%    |
| fr_BE      | 1         | 0.1%    |
| es_SV      | 1         | 0.1%    |
| en_ZA      | 1         | 0.1%    |
| en_DE      | 1         | 0.1%    |
| en_BW      | 1         | 0.1%    |
| en_AU      | 1         | 0.1%    |
| C.UTF8     | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 523       | 50.83%  |
| EFI  | 506       | 49.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 704       | 67.95%  |
| Btrfs               | 168       | 16.22%  |
| Overlay             | 61        | 5.89%   |
| Tmpfs               | 41        | 3.96%   |
| Xfs                 | 23        | 2.22%   |
| Unknown             | 23        | 2.22%   |
| Zfs                 | 8         | 0.77%   |
| Ext3                | 2         | 0.19%   |
| Ext2                | 2         | 0.19%   |
| Rootfs              | 1         | 0.1%    |
| Fuse.fuse-overlayfs | 1         | 0.1%    |
| Fake                | 1         | 0.1%    |
| F2fs                | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 477       | 45.87%  |
| GPT     | 469       | 45.1%   |
| MBR     | 94        | 9.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 876       | 85.71%  |
| Yes       | 146       | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 793       | 77.37%  |
| Yes       | 232       | 22.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell                                 | 199       | 19.84%  |
| Lenovo                               | 179       | 17.85%  |
| ASUSTek Computer                     | 124       | 12.36%  |
| Hewlett-Packard                      | 115       | 11.47%  |
| Gigabyte Technology                  | 54        | 5.38%   |
| MSI                                  | 40        | 3.99%   |
| Acer                                 | 39        | 3.89%   |
| Apple                                | 30        | 2.99%   |
| ASRock                               | 21        | 2.09%   |
| Toshiba                              | 16        | 1.6%    |
| Samsung Electronics                  | 14        | 1.4%    |
| Intel                                | 14        | 1.4%    |
| Valve                                | 8         | 0.8%    |
| AZW                                  | 8         | 0.8%    |
| Google                               | 7         | 0.7%    |
| Medion                               | 6         | 0.6%    |
| Foxconn                              | 6         | 0.6%    |
| Chuwi                                | 6         | 0.6%    |
| System76                             | 5         | 0.5%    |
| PC Specialist                        | 5         | 0.5%    |
| Packard Bell                         | 5         | 0.5%    |
| Notebook                             | 5         | 0.5%    |
| HUAWEI                               | 5         | 0.5%    |
| Alienware                            | 5         | 0.5%    |
| TUXEDO                               | 4         | 0.4%    |
| Timi                                 | 4         | 0.4%    |
| Shenzhen Meigao Electronic Equipment | 4         | 0.4%    |
| Microsoft                            | 4         | 0.4%    |
| Fujitsu                              | 4         | 0.4%    |
| Framework                            | 4         | 0.4%    |
| Unknown                              | 4         | 0.4%    |
| Shuttle                              | 3         | 0.3%    |
| Raspberry Pi Foundation              | 3         | 0.3%    |
| Pegatron                             | 3         | 0.3%    |
| AVITA                                | 3         | 0.3%    |
| Tactus                               | 2         | 0.2%    |
| Seeed Studio                         | 2         | 0.2%    |
| Seco                                 | 2         | 0.2%    |
| Schenker                             | 2         | 0.2%    |
| Rockchip                             | 2         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 10        | 1%      |
| Dell OptiPlex 7010                         | 8         | 0.8%    |
| Dell Latitude 7420                         | 8         | 0.8%    |
| Valve Jupiter                              | 7         | 0.7%    |
| Lenovo IdeaPad 330-15IKB 81DE              | 6         | 0.6%    |
| Lenovo Yoga 6 13ALC7 82UD                  | 5         | 0.5%    |
| Gigabyte B450M DS3H                        | 5         | 0.5%    |
| Unknown                                    | 5         | 0.5%    |
| MSI MS-7C37                                | 4         | 0.4%    |
| HP Compaq 8200 Elite SFF PC                | 4         | 0.4%    |
| Dell OptiPlex 790                          | 4         | 0.4%    |
| Dell OptiPlex 780                          | 4         | 0.4%    |
| Dell OptiPlex 7020                         | 4         | 0.4%    |
| Dell Latitude E7240                        | 4         | 0.4%    |
| Dell Latitude 5480                         | 4         | 0.4%    |
| ASUS TUF Gaming X570-PLUS                  | 4         | 0.4%    |
| Lenovo V145-15AST 81MT                     | 3         | 0.3%    |
| Lenovo ThinkCentre E73 10DS000TUK          | 3         | 0.3%    |
| HP Pavilion Laptop 15-eh0xxx               | 3         | 0.3%    |
| HP Notebook                                | 3         | 0.3%    |
| HP EliteDesk 800 G1 SFF                    | 3         | 0.3%    |
| Gigabyte Z77-DS3H                          | 3         | 0.3%    |
| Dell XPS 9320                              | 3         | 0.3%    |
| Dell Latitude E5420                        | 3         | 0.3%    |
| Dell Inspiron 13-5378                      | 3         | 0.3%    |
| AZW MINI S                                 | 3         | 0.3%    |
| ASUS ROG STRIX B450-F GAMING               | 3         | 0.3%    |
| TUXEDO Pulse 15 Gen1                       | 2         | 0.2%    |
| Toshiba Satellite C50-B                    | 2         | 0.2%    |
| Shenzhen Meigao Electronic Equipment UM690 | 2         | 0.2%    |
| Seeed Studio ODYSSEY-X86J4105              | 2         | 0.2%    |
| Seco C40                                   | 2         | 0.2%    |
| Samsung 750XED                             | 2         | 0.2%    |
| RPi Raspberry Pi                           | 2         | 0.2%    |
| Nvidia Tegra                               | 2         | 0.2%    |
| MSI Stealth GS66 12UGS                     | 2         | 0.2%    |
| MSI Pro 3515 Series                        | 2         | 0.2%    |
| MSI MS-7E27                                | 2         | 0.2%    |
| MSI MS-7E26                                | 2         | 0.2%    |
| MSI MS-7B86                                | 2         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 83        | 8.28%   |
| Dell Latitude         | 69        | 6.88%   |
| Lenovo IdeaPad        | 36        | 3.59%   |
| Dell OptiPlex         | 36        | 3.59%   |
| Dell Inspiron         | 30        | 2.99%   |
| Acer Aspire           | 29        | 2.89%   |
| HP Pavilion           | 24        | 2.39%   |
| Dell XPS              | 23        | 2.29%   |
| Dell Precision        | 22        | 2.19%   |
| HP EliteBook          | 19        | 1.89%   |
| ASUS ROG              | 17        | 1.69%   |
| Lenovo ThinkCentre    | 14        | 1.4%    |
| ASUS PRIME            | 14        | 1.4%    |
| Toshiba Satellite     | 13        | 1.3%    |
| ASUS TUF              | 13        | 1.3%    |
| ASUS VivoBook         | 12        | 1.2%    |
| Lenovo Yoga           | 11        | 1.1%    |
| HP Compaq             | 11        | 1.1%    |
| ASUS All              | 10        | 1%      |
| HP EliteDesk          | 8         | 0.8%    |
| ASUS Zenbook          | 8         | 0.8%    |
| Valve Jupiter         | 7         | 0.7%    |
| HP ProBook            | 6         | 0.6%    |
| HP Laptop             | 6         | 0.6%    |
| Lenovo ThinkStation   | 5         | 0.5%    |
| Gigabyte B450M        | 5         | 0.5%    |
| Gigabyte B450         | 5         | 0.5%    |
| Dell Vostro           | 5         | 0.5%    |
| Apple MacBookPro5     | 5         | 0.5%    |
| Unknown               | 5         | 0.5%    |
| MSI MS-7C37           | 4         | 0.4%    |
| Microsoft Surface     | 4         | 0.4%    |
| HP ZBook              | 4         | 0.4%    |
| HP OMEN               | 4         | 0.4%    |
| Gigabyte X570         | 4         | 0.4%    |
| Framework Laptop      | 4         | 0.4%    |
| Foxconn Pro           | 4         | 0.4%    |
| RPi Raspberry         | 3         | 0.3%    |
| Packard Bell EasyNote | 3         | 0.3%    |
| Lenovo V145-15AST     | 3         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 90        | 8.97%   |
| 2020    | 85        | 8.47%   |
| 2019    | 85        | 8.47%   |
| 2012    | 69        | 6.88%   |
| 2022    | 65        | 6.48%   |
| 2017    | 65        | 6.48%   |
| 2013    | 63        | 6.28%   |
| 2021    | 62        | 6.18%   |
| 2011    | 57        | 5.68%   |
| 2023    | 46        | 4.59%   |
| 2016    | 46        | 4.59%   |
| 2015    | 46        | 4.59%   |
| 2010    | 44        | 4.39%   |
| 2014    | 37        | 3.69%   |
| 2024    | 34        | 3.39%   |
| 2008    | 34        | 3.39%   |
| 2009    | 28        | 2.79%   |
| 2007    | 14        | 1.4%    |
| 2006    | 10        | 1%      |
| Unknown | 10        | 1%      |
| 2025    | 9         | 0.9%    |
| 2005    | 3         | 0.3%    |
| 2003    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 584       | 58.23%  |
| Desktop        | 331       | 33%     |
| Convertible    | 26        | 2.59%   |
| Mini pc        | 21        | 2.09%   |
| All in one     | 15        | 1.5%    |
| Tablet         | 14        | 1.4%    |
| System on chip | 8         | 0.8%    |
| Server         | 3         | 0.3%    |
| Phone          | 1         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 921       | 91.37%  |
| Enabled  | 87        | 8.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 992       | 98.9%   |
| Yes  | 11        | 1.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 222       | 21.68%  |
| 16.01-24.0      | 215       | 21%     |
| 8.01-16.0       | 179       | 17.48%  |
| 3.01-4.0        | 147       | 14.36%  |
| 32.01-64.0      | 140       | 13.67%  |
| 64.01-256.0     | 49        | 4.79%   |
| 24.01-32.0      | 31        | 3.03%   |
| 1.01-2.0        | 25        | 2.44%   |
| 2.01-3.0        | 8         | 0.78%   |
| 0.51-1.0        | 5         | 0.49%   |
| More than 256.0 | 2         | 0.2%    |
| 0.01-0.5        | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 285       | 25.45%  |
| 2.01-3.0   | 282       | 25.18%  |
| 4.01-8.0   | 230       | 20.54%  |
| 3.01-4.0   | 181       | 16.16%  |
| 8.01-16.0  | 70        | 6.25%   |
| 0.51-1.0   | 52        | 4.64%   |
| 16.01-24.0 | 8         | 0.71%   |
| 0.01-0.5   | 8         | 0.71%   |
| 32.01-64.0 | 3         | 0.27%   |
| Unknown    | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 622       | 59.41%  |
| 2      | 254       | 24.26%  |
| 3      | 77        | 7.35%   |
| 4      | 45        | 4.3%    |
| 5      | 20        | 1.91%   |
| 0      | 9         | 0.86%   |
| 6      | 8         | 0.76%   |
| 7      | 6         | 0.57%   |
| 10     | 3         | 0.29%   |
| 11     | 1         | 0.1%    |
| 9      | 1         | 0.1%    |
| 8      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 707       | 69.66%  |
| Yes       | 308       | 30.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 833       | 82.56%  |
| No        | 176       | 17.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 841       | 82.86%  |
| No        | 174       | 17.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 706       | 69.22%  |
| No        | 314       | 30.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 1003      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Dublin         | 626       | 59.34%  |
| Cork           | 53        | 5.02%   |
| Galway         | 38        | 3.6%    |
| Limerick       | 30        | 2.84%   |
| Naas           | 16        | 1.52%   |
| Drogheda       | 12        | 1.14%   |
| Waterford      | 11        | 1.04%   |
| Ennis          | 11        | 1.04%   |
| Enniscorthy    | 8         | 0.76%   |
| Portlaoise     | 7         | 0.66%   |
| Nenagh         | 7         | 0.66%   |
| Navan          | 7         | 0.66%   |
| Gorey          | 7         | 0.66%   |
| Athlone        | 7         | 0.66%   |
| Wexford        | 6         | 0.57%   |
| Sligo          | 6         | 0.57%   |
| Kilkenny       | 6         | 0.57%   |
| Kenmare        | 6         | 0.57%   |
| Westport       | 5         | 0.47%   |
| Lucan          | 5         | 0.47%   |
| Tullamore      | 4         | 0.38%   |
| Tuam           | 4         | 0.38%   |
| Maynooth       | 4         | 0.38%   |
| Loughrea       | 4         | 0.38%   |
| Letterkenny    | 4         | 0.38%   |
| Dundalk        | 4         | 0.38%   |
| Dún Laoghaire | 4         | 0.38%   |
| Cavan          | 4         | 0.38%   |
| Tralee         | 3         | 0.28%   |
| Tobercurry     | 3         | 0.28%   |
| Midleton       | 3         | 0.28%   |
| Kildare        | 3         | 0.28%   |
| Greystones     | 3         | 0.28%   |
| Cobh           | 3         | 0.28%   |
| Clonakilty     | 3         | 0.28%   |
| Celbridge      | 3         | 0.28%   |
| Bray           | 3         | 0.28%   |
| Blackrock      | 3         | 0.28%   |
| Ballina        | 3         | 0.28%   |
| Balbriggan     | 3         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 249       | 373    | 16.78%  |
| WDC                         | 176       | 300    | 11.86%  |
| Seagate                     | 175       | 288    | 11.79%  |
| SanDisk                     | 97        | 129    | 6.54%   |
| Unknown                     | 75        | 99     | 5.05%   |
| Toshiba                     | 74        | 104    | 4.99%   |
| Crucial                     | 71        | 91     | 4.78%   |
| Kingston                    | 51        | 78     | 3.44%   |
| Hitachi                     | 47        | 66     | 3.17%   |
| Micron Technology           | 42        | 48     | 2.83%   |
| SK hynix                    | 41        | 45     | 2.76%   |
| Intel                       | 35        | 49     | 2.36%   |
| KIOXIA                      | 29        | 35     | 1.95%   |
| Micron/Crucial Technology   | 21        | 31     | 1.42%   |
| HGST                        | 19        | 24     | 1.28%   |
| A-DATA Technology           | 14        | 24     | 0.94%   |
| Phison Electronics          | 13        | 17     | 0.88%   |
| Kingston Technology Company | 13        | 14     | 0.88%   |
| China                       | 13        | 23     | 0.88%   |
| Apple                       | 11        | 15     | 0.74%   |
| LITEON                      | 9         | 10     | 0.61%   |
| Fujitsu                     | 8         | 11     | 0.54%   |
| ADATA Technology            | 8         | 10     | 0.54%   |
| Transcend                   | 7         | 7      | 0.47%   |
| Silicon Motion              | 7         | 17     | 0.47%   |
| Phison                      | 7         | 12     | 0.47%   |
| OCZ                         | 7         | 9      | 0.47%   |
| Netac                       | 7         | 7      | 0.47%   |
| MAXIO Technology (Hangzhou) | 7         | 7      | 0.47%   |
| FORESEE                     | 7         | 9      | 0.47%   |
| PNY                         | 6         | 6      | 0.4%    |
| Verbatim                    | 5         | 5      | 0.34%   |
| SABRENT                     | 5         | 6      | 0.34%   |
| JMicron Technology          | 5         | 5      | 0.34%   |
| Fanxiang                    | 5         | 7      | 0.34%   |
| Unknown                     | 5         | 5      | 0.34%   |
| Union Memory                | 4         | 4      | 0.27%   |
| Patriot                     | 4         | 5      | 0.27%   |
| Lexar                       | 4         | 5      | 0.27%   |
| KingSpec                    | 4         | 4      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 23        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 21        | 1.28%   |
| Unknown MMC Card  64GB                                | 14        | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB                        | 13        | 0.79%   |
| Unknown MMC Card  32GB                                | 12        | 0.73%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                        | 11        | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 10        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                           | 10        | 0.61%   |
| Seagate ST500DM002-1BD142 500GB                       | 9         | 0.55%   |
| Samsung SSD 850 EVO 500GB                             | 9         | 0.55%   |
| Samsung SSD 850 EVO 250GB                             | 9         | 0.55%   |
| Kingston SA400S37480G 480GB SSD                       | 9         | 0.55%   |
| Kingston SA400S37240G 240GB SSD                       | 9         | 0.55%   |
| Crucial CT500MX500SSD1 500GB                          | 9         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                        | 8         | 0.49%   |
| Samsung SSD 860 EVO 500GB                             | 8         | 0.49%   |
| Toshiba MQ01ABD100 1TB                                | 7         | 0.43%   |
| Seagate ST2000DL003-9VT166 2TB                        | 7         | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                          | 7         | 0.43%   |
| WDC WD10EURX-83UY4Y0 1TB                              | 6         | 0.37%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB                | 6         | 0.37%   |
| Seagate ST8000DM004-2CX188 8TB                        | 6         | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6         | 0.37%   |
| SanDisk SDSSDH3500G 500GB                             | 6         | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB                        | 6         | 0.37%   |
| Samsung SSD 840 EVO 250GB                             | 6         | 0.37%   |
| Samsung NVMe SSD Drive 500GB                          | 6         | 0.37%   |
| Samsung NVMe SSD Drive 256GB                          | 6         | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 6         | 0.37%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB      | 6         | 0.37%   |
| HGST HTS721010A9E630 1TB                              | 6         | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5         | 0.3%    |
| WDC WD10EALX-009BA0 1TB                               | 5         | 0.3%    |
| Verbatim Vi550 S3 SSD 512GB                           | 5         | 0.3%    |
| Unknown MMC Card  512GB                               | 5         | 0.3%    |
| Unknown MMC Card  128GB                               | 5         | 0.3%    |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 5         | 0.3%    |
| Toshiba MQ04ABF100 1TB                                | 5         | 0.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 5         | 0.3%    |
| Seagate ST4000DM004-2CV104 4TB                        | 5         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 171       | 281    | 36.15%  |
| WDC                 | 136       | 246    | 28.75%  |
| Toshiba             | 50        | 70     | 10.57%  |
| Hitachi             | 47        | 66     | 9.94%   |
| HGST                | 19        | 24     | 4.02%   |
| Samsung Electronics | 14        | 19     | 2.96%   |
| Fujitsu             | 8         | 11     | 1.69%   |
| Apple               | 5         | 5      | 1.06%   |
| Unknown             | 4         | 4      | 0.85%   |
| QNAP                | 2         | 18     | 0.42%   |
| Maxtor              | 2         | 2      | 0.42%   |
| JMicron Technology  | 2         | 2      | 0.42%   |
| Intenso             | 2         | 2      | 0.42%   |
| USB3.0              | 1         | 1      | 0.21%   |
| USB                 | 1         | 2      | 0.21%   |
| SABRENT             | 1         | 2      | 0.21%   |
| MARVELL             | 1         | 1      | 0.21%   |
| LaCie               | 1         | 1      | 0.21%   |
| KESU                | 1         | 1      | 0.21%   |
| Inateck             | 1         | 1      | 0.21%   |
| FNK TECH            | 1         | 1      | 0.21%   |
| ExcelStor           | 1         | 2      | 0.21%   |
| DAS                 | 1         | 4      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 108       | 159    | 24.32%  |
| Crucial             | 61        | 77     | 13.74%  |
| SanDisk             | 49        | 55     | 11.04%  |
| Kingston            | 37        | 60     | 8.33%   |
| WDC                 | 19        | 27     | 4.28%   |
| Intel               | 13        | 16     | 2.93%   |
| China               | 13        | 23     | 2.93%   |
| A-DATA Technology   | 11        | 20     | 2.48%   |
| Micron Technology   | 8         | 9      | 1.8%    |
| LITEON              | 8         | 9      | 1.8%    |
| OCZ                 | 7         | 9      | 1.58%   |
| Netac               | 7         | 7      | 1.58%   |
| SK hynix            | 6         | 6      | 1.35%   |
| PNY                 | 6         | 6      | 1.35%   |
| Verbatim            | 5         | 5      | 1.13%   |
| Transcend           | 5         | 5      | 1.13%   |
| Fanxiang            | 5         | 7      | 1.13%   |
| Apple               | 5         | 5      | 1.13%   |
| Toshiba             | 4         | 6      | 0.9%    |
| SABRENT             | 4         | 4      | 0.9%    |
| Patriot             | 4         | 5      | 0.9%    |
| KingSpec            | 4         | 4      | 0.9%    |
| FORESEE             | 4         | 5      | 0.9%    |
| LITEONIT            | 3         | 3      | 0.68%   |
| KingDian            | 3         | 14     | 0.68%   |
| Emtec               | 3         | 4      | 0.68%   |
| Unknown             | 3         | 3      | 0.68%   |
| Team                | 2         | 2      | 0.45%   |
| SPCC                | 2         | 2      | 0.45%   |
| Lexar               | 2         | 2      | 0.45%   |
| Intenso             | 2         | 2      | 0.45%   |
| Integral            | 2         | 2      | 0.45%   |
| Hewlett-Packard     | 2         | 4      | 0.45%   |
| ASMT                | 2         | 4      | 0.45%   |
| 2-Power             | 2         | 3      | 0.45%   |
| ZTC                 | 1         | 1      | 0.23%   |
| Zheino              | 1         | 1      | 0.23%   |
| Wibtek              | 1         | 2      | 0.23%   |
| W800S               | 1         | 2      | 0.23%   |
| Union Memory        | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 446       | 660    | 33.86%  |
| SSD     | 395       | 601    | 29.99%  |
| HDD     | 385       | 767    | 29.23%  |
| MMC     | 69        | 96     | 5.24%   |
| Unknown | 22        | 24     | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 630       | 1312   | 52.07%  |
| NVMe | 444       | 655    | 36.69%  |
| MMC  | 69        | 96     | 5.7%    |
| SAS  | 67        | 85     | 5.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 461       | 771    | 56.01%  |
| 0.51-1.0   | 225       | 335    | 27.34%  |
| 1.01-2.0   | 76        | 111    | 9.23%   |
| 3.01-4.0   | 28        | 64     | 3.4%    |
| 4.01-10.0  | 15        | 40     | 1.82%   |
| 2.01-3.0   | 14        | 37     | 1.7%    |
| 10.01-20.0 | 4         | 10     | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 254       | 23.67%  |
| 251-500        | 243       | 22.65%  |
| 501-1000       | 157       | 14.63%  |
| 1001-2000      | 89        | 8.29%   |
| 1-20           | 78        | 7.27%   |
| More than 3000 | 73        | 6.8%    |
| 51-100         | 71        | 6.62%   |
| Unknown        | 42        | 3.91%   |
| 2001-3000      | 37        | 3.45%   |
| 21-50          | 29        | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 388       | 34.58%  |
| 21-50          | 177       | 15.78%  |
| 101-250        | 146       | 13.01%  |
| 51-100         | 142       | 12.66%  |
| 251-500        | 78        | 6.95%   |
| 501-1000       | 67        | 5.97%   |
| Unknown        | 42        | 3.74%   |
| 1001-2000      | 35        | 3.12%   |
| More than 3000 | 32        | 2.85%   |
| 2001-3000      | 15        | 1.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10EALX-009BA0 1TB             | 5         | 11     | 5.21%   |
| Seagate ST2000DL003-9VT166 2TB      | 5         | 8      | 5.21%   |
| WDC WD3200AVJS-63B6A0 320GB         | 2         | 2      | 2.08%   |
| WDC WD2500AAKX-753CA1 250GB         | 2         | 6      | 2.08%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 2      | 2.08%   |
| Hitachi HDS721010CLA332 1TB         | 2         | 2      | 2.08%   |
| Hitachi HDS721010CLA330 1TB         | 2         | 2      | 2.08%   |
| Western Digital SN730 500GB         | 1         | 2      | 1.04%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 1      | 1.04%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 1      | 1.04%   |
| WDC WD5000HHTZ-04N21V0 500GB        | 1         | 3      | 1.04%   |
| WDC WD5000BEVT-35A0RT0 500GB        | 1         | 1      | 1.04%   |
| WDC WD5000AAKX-083CA1 500GB         | 1         | 1      | 1.04%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 2      | 1.04%   |
| WDC WD400JB-00FMA0 40GB             | 1         | 2      | 1.04%   |
| WDC WD32 00BEKT-75PVMT0 320GB       | 1         | 1      | 1.04%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 1      | 1.04%   |
| WDC WD2500BEKT-75A25T0 250GB        | 1         | 1      | 1.04%   |
| WDC WD2500AAKX-603CA0 250GB         | 1         | 1      | 1.04%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1         | 2      | 1.04%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1         | 1      | 1.04%   |
| WDC WD1003FBYX-12 1TB               | 1         | 1      | 1.04%   |
| WDC WD1001FALS-00E8B0 1TB           | 1         | 2      | 1.04%   |
| Toshiba MQ01ABF050H 500GB           | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.04%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.04%   |
| Toshiba MK3255GSXF 250GB            | 1         | 1      | 1.04%   |
| Toshiba MK1652GSX 160GB             | 1         | 1      | 1.04%   |
| Toshiba MK1059GSM 1TB               | 1         | 1      | 1.04%   |
| Toshiba DT01ACA050 500GB            | 1         | 3      | 1.04%   |
| SK hynix SC308 SATA 256GB SSD       | 1         | 1      | 1.04%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 1.04%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.04%   |
| Seagate ST910021AS 100GB            | 1         | 1      | 1.04%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 1.04%   |
| Seagate ST500LM030-2E717D 500GB     | 1         | 1      | 1.04%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.04%   |
| Seagate ST500LM000-1EJ162 500GB     | 1         | 1      | 1.04%   |
| Seagate ST4000DX001-1CE168 4TB      | 1         | 1      | 1.04%   |
| Seagate ST3500418AS 500GB           | 1         | 3      | 1.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 28     | 23.66%  |
| WDC                 | 21        | 40     | 22.58%  |
| Hitachi             | 14        | 18     | 15.05%  |
| Toshiba             | 7         | 9      | 7.53%   |
| Samsung Electronics | 5         | 5      | 5.38%   |
| Micron Technology   | 3         | 3      | 3.23%   |
| HGST                | 3         | 3      | 3.23%   |
| SanDisk             | 2         | 2      | 2.15%   |
| Crucial             | 2         | 2      | 2.15%   |
| Western Digital     | 1         | 2      | 1.08%   |
| SK hynix            | 1         | 1      | 1.08%   |
| Netac               | 1         | 1      | 1.08%   |
| Maxtor              | 1         | 1      | 1.08%   |
| Lexar               | 1         | 1      | 1.08%   |
| JMicron Technology  | 1         | 1      | 1.08%   |
| Intel               | 1         | 1      | 1.08%   |
| Inateck             | 1         | 1      | 1.08%   |
| Fujitsu             | 1         | 1      | 1.08%   |
| DRVEO               | 1         | 1      | 1.08%   |
| China               | 1         | 1      | 1.08%   |
| Apple               | 1         | 1      | 1.08%   |
| ADATA Technology    | 1         | 1      | 1.08%   |
| A-DATA Technology   | 1         | 1      | 1.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 28     | 29.73%  |
| WDC                 | 21        | 40     | 28.38%  |
| Hitachi             | 14        | 18     | 18.92%  |
| Toshiba             | 7         | 9      | 9.46%   |
| HGST                | 3         | 3      | 4.05%   |
| Samsung Electronics | 2         | 2      | 2.7%    |
| Maxtor              | 1         | 1      | 1.35%   |
| JMicron Technology  | 1         | 1      | 1.35%   |
| Inateck             | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 59        | 105    | 75.64%  |
| SSD  | 13        | 13     | 16.67%  |
| NVMe | 6         | 7      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB     | 1         | 1      | 33.33%  |
| Sandisk PC SN520 NVMe SSD 128GB | 1         | 1      | 33.33%  |
| KingDian S400 120GB             | 1         | 4      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 33.33%  |
| Sandisk  | 1         | 1      | 33.33%  |
| KingDian | 1         | 4      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 576       | 1191   | 52.17%  |
| Works    | 448       | 826    | 40.58%  |
| Malfunc  | 77        | 125    | 6.97%   |
| Failed   | 3         | 6      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 591       | 44.81%  |
| AMD                                     | 189       | 14.33%  |
| Samsung Electronics                     | 141       | 10.69%  |
| SanDisk                                 | 70        | 5.31%   |
| Micron Technology                       | 36        | 2.73%   |
| SK hynix                                | 35        | 2.65%   |
| Micron/Crucial Technology               | 29        | 2.2%    |
| KIOXIA                                  | 28        | 2.12%   |
| Kingston Technology Company             | 26        | 1.97%   |
| Toshiba America Info Systems            | 22        | 1.67%   |
| Phison Electronics                      | 21        | 1.59%   |
| Nvidia                                  | 20        | 1.52%   |
| ASMedia Technology                      | 18        | 1.36%   |
| Marvell Technology Group                | 15        | 1.14%   |
| MAXIO Technology (Hangzhou)             | 10        | 0.76%   |
| JMicron Technology                      | 10        | 0.76%   |
| ADATA Technology                        | 9         | 0.68%   |
| Silicon Motion                          | 8         | 0.61%   |
| Union Memory (Shenzhen)                 | 7         | 0.53%   |
| LSI Logic / Symbios Logic               | 4         | 0.3%    |
| Transcend                               | 3         | 0.23%   |
| Solid State Storage Technology          | 3         | 0.23%   |
| Shenzhen Longsys Electronics            | 3         | 0.23%   |
| O2 Micro                                | 3         | 0.23%   |
| INNOGRIT                                | 3         | 0.23%   |
| Realtek Semiconductor                   | 2         | 0.15%   |
| Lenovo                                  | 2         | 0.15%   |
| Apple                                   | 2         | 0.15%   |
| ULi Electronics                         | 1         | 0.08%   |
| Solidigm                                | 1         | 0.08%   |
| Silicon Image                           | 1         | 0.08%   |
| Shenzhen Unionmemory Information System | 1         | 0.08%   |
| Seagate Technology                      | 1         | 0.08%   |
| Lite-On Technology                      | 1         | 0.08%   |
| Hosin Global Electronics                | 1         | 0.08%   |
| Broadcom / LSI                          | 1         | 0.08%   |
| Adaptec                                 | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 122       | 8.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 65        | 4.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 58        | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 35        | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 35        | 2.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 33        | 2.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 31        | 2.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 28        | 1.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 26        | 1.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 24        | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 23        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23        | 1.55%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 22        | 1.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 22        | 1.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21        | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 19        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19        | 1.28%   |
| AMD 600 Series Chipset SATA Controller                                                  | 18        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 17        | 1.14%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 16        | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 16        | 1.08%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 16        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15        | 1.01%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 14        | 0.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 13        | 0.87%   |
| Intel SATA Controller [RAID mode]                                                       | 13        | 0.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13        | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 12        | 0.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 12        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12        | 0.81%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 10        | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 10        | 0.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 10        | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 0.67%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                            | 9         | 0.61%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 9         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 665       | 51%     |
| NVMe | 445       | 34.13%  |
| IDE  | 98        | 7.52%   |
| RAID | 92        | 7.06%   |
| SCSI | 4         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 727       | 72.41%  |
| AMD    | 266       | 26.49%  |
| ARM    | 10        | 1%      |
| iSH    | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.49%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 14        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.99%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 9         | 0.89%   |
| ARM Processor                                 | 9         | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.79%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 8         | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 0.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 7         | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 7         | 0.69%   |
| AMD Custom APU 0405                           | 7         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.59%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 0.59%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 6         | 0.59%   |
| Intel N100                                    | 5         | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.5%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 0.5%    |
| Intel Core i7-3770K CPU @ 3.50GHz             | 5         | 0.5%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.5%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.5%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 5         | 0.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.5%    |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.5%    |
| Intel 12th Gen Core i5-1235U                  | 5         | 0.5%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 5         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 198       | 19.62%  |
| Intel Core i7           | 183       | 18.14%  |
| Other                   | 126       | 12.49%  |
| AMD Ryzen 5             | 73        | 7.23%   |
| Intel Core i3           | 62        | 6.14%   |
| AMD Ryzen 7             | 59        | 5.85%   |
| Intel Celeron           | 45        | 4.46%   |
| Intel Core 2 Duo        | 35        | 3.47%   |
| AMD Ryzen 9             | 30        | 2.97%   |
| Intel Xeon              | 18        | 1.78%   |
| Intel Pentium           | 14        | 1.39%   |
| Intel Atom              | 14        | 1.39%   |
| Intel Core              | 11        | 1.09%   |
| AMD Ryzen 3             | 10        | 0.99%   |
| Intel Core 2 Quad       | 9         | 0.89%   |
| AMD Athlon 64 X2        | 7         | 0.69%   |
| Intel Core i9           | 6         | 0.59%   |
| AMD Ryzen Threadripper  | 6         | 0.59%   |
| AMD FX                  | 6         | 0.59%   |
| AMD A8                  | 6         | 0.59%   |
| AMD A6                  | 6         | 0.59%   |
| Intel Pentium Dual-Core | 5         | 0.5%    |
| AMD Ryzen 5 PRO         | 5         | 0.5%    |
| Intel Pentium Silver    | 4         | 0.4%    |
| Intel Pentium 4         | 4         | 0.4%    |
| AMD Ryzen 7 PRO         | 4         | 0.4%    |
| AMD E1                  | 4         | 0.4%    |
| AMD A4                  | 4         | 0.4%    |
| Intel Core 2            | 3         | 0.3%    |
| Intel Celeron Dual-Core | 3         | 0.3%    |
| AMD Phenom II X4        | 3         | 0.3%    |
| AMD Athlon II X4        | 3         | 0.3%    |
| AMD Athlon II X2        | 3         | 0.3%    |
| AMD A10                 | 3         | 0.3%    |
| Intel Pentium Gold      | 2         | 0.2%    |
| Intel Pentium Dual      | 2         | 0.2%    |
| Intel Pentium D         | 2         | 0.2%    |
| Intel Core m3           | 2         | 0.2%    |
| AMD Sempron             | 2         | 0.2%    |
| AMD Ryzen Embedded      | 2         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 393       | 39.03%  |
| 2       | 311       | 30.88%  |
| 6       | 98        | 9.73%   |
| 8       | 89        | 8.84%   |
| 12      | 37        | 3.67%   |
| 1       | 22        | 2.18%   |
| 14      | 16        | 1.59%   |
| 10      | 14        | 1.39%   |
| 16      | 13        | 1.29%   |
| 32      | 3         | 0.3%    |
| 24      | 3         | 0.3%    |
| 3       | 3         | 0.3%    |
| Unknown | 2         | 0.2%    |
| 96      | 1         | 0.1%    |
| 44      | 1         | 0.1%    |
| 20      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 994       | 99.1%   |
| 2       | 8         | 0.8%    |
| Unknown | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 705       | 69.87%  |
| 1       | 302       | 29.93%  |
| Unknown | 2         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 984       | 97.81%  |
| Unknown        | 19        | 1.89%   |
| 32-bit         | 3         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 544       | 51.96%  |
| 0x306a9    | 41        | 3.92%   |
| 0x206a7    | 34        | 3.25%   |
| 0x306c3    | 24        | 2.29%   |
| 0x1067a    | 24        | 2.29%   |
| 0x806ec    | 22        | 2.1%    |
| 0x806c1    | 19        | 1.81%   |
| 0x806e9    | 18        | 1.72%   |
| 0x406e3    | 16        | 1.53%   |
| 0x806ea    | 14        | 1.34%   |
| 0x40651    | 12        | 1.15%   |
| 0x906ea    | 11        | 1.05%   |
| 0x906e9    | 10        | 0.96%   |
| 0x406c4    | 10        | 0.96%   |
| 0x08108109 | 10        | 0.96%   |
| 0x0a50000c | 9         | 0.86%   |
| 0x506e3    | 8         | 0.76%   |
| 0x30678    | 8         | 0.76%   |
| 0x10676    | 8         | 0.76%   |
| 0xa0652    | 7         | 0.67%   |
| 0x08701021 | 7         | 0.67%   |
| 0x306d4    | 6         | 0.57%   |
| 0x20655    | 6         | 0.57%   |
| 0x0810100b | 6         | 0.57%   |
| 0x0800820d | 6         | 0.57%   |
| 0x08108102 | 5         | 0.48%   |
| 0x06006705 | 5         | 0.48%   |
| 0xa0653    | 4         | 0.38%   |
| 0x906a3    | 4         | 0.38%   |
| 0x706a8    | 4         | 0.38%   |
| 0x6fd      | 4         | 0.38%   |
| 0x6fb      | 4         | 0.38%   |
| 0x206c2    | 4         | 0.38%   |
| 0x20652    | 4         | 0.38%   |
| 0x106e5    | 4         | 0.38%   |
| 0x106ca    | 4         | 0.38%   |
| 0x08600106 | 4         | 0.38%   |
| 0x0600611a | 4         | 0.38%   |
| 0x010000c8 | 4         | 0.38%   |
| 0xf43      | 3         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 154       | 15.28%  |
| Unknown           | 106       | 10.52%  |
| IvyBridge         | 69        | 6.85%   |
| Haswell           | 66        | 6.55%   |
| SandyBridge       | 59        | 5.85%   |
| Skylake           | 53        | 5.26%   |
| Zen 3             | 44        | 4.37%   |
| Zen 2             | 42        | 4.17%   |
| TigerLake         | 42        | 4.17%   |
| Penryn            | 42        | 4.17%   |
| Zen+              | 40        | 3.97%   |
| Westmere          | 28        | 2.78%   |
| Silvermont        | 27        | 2.68%   |
| Alderlake Hybrid  | 26        | 2.58%   |
| Goldmont plus     | 20        | 1.98%   |
| CometLake         | 20        | 1.98%   |
| Core              | 18        | 1.79%   |
| Zen               | 16        | 1.59%   |
| K10               | 14        | 1.39%   |
| IceLake           | 14        | 1.39%   |
| Excavator         | 13        | 1.29%   |
| Broadwell         | 13        | 1.29%   |
| Piledriver        | 10        | 0.99%   |
| K8 Hammer         | 10        | 0.99%   |
| Nehalem           | 9         | 0.89%   |
| Gracemont         | 8         | 0.79%   |
| NetBurst          | 6         | 0.6%    |
| Bonnell           | 6         | 0.6%    |
| Puma              | 5         | 0.5%    |
| P6                | 4         | 0.4%    |
| Jaguar            | 4         | 0.4%    |
| Goldmont          | 4         | 0.4%    |
| Bobcat            | 4         | 0.4%    |
| Meteorlake Hybrid | 3         | 0.3%    |
| Tremont           | 2         | 0.2%    |
| Steamroller       | 2         | 0.2%    |
| Lunarlake Hybrid  | 1         | 0.1%    |
| K8 & K10 hybrid   | 1         | 0.1%    |
| K10 Llano         | 1         | 0.1%    |
| Bulldozer         | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 577       | 49.61%  |
| Nvidia                     | 293       | 25.19%  |
| AMD                        | 290       | 24.94%  |
| Matrox Electronics Systems | 2         | 0.17%   |
| ASPEED Technology          | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 41        | 3.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 2.83%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 33        | 2.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 2.66%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 25        | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 2%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 2%      |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 20        | 1.66%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 18        | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 1.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 1.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 13        | 1.08%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 13        | 1.08%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 11        | 0.91%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 11        | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.91%   |
| AMD Rembrandt [Radeon 680M]                                                              | 10        | 0.83%   |
| AMD Lucienne                                                                             | 10        | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.67%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 0.67%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 8         | 0.67%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 8         | 0.67%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 8         | 0.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.67%   |
| AMD Raphael                                                                              | 8         | 0.67%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 8         | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 436       | 42.83%  |
| 1 x AMD         | 232       | 22.79%  |
| 1 x Nvidia      | 158       | 15.52%  |
| Intel + Nvidia  | 113       | 11.1%   |
| 2 x AMD         | 24        | 2.36%   |
| AMD + Nvidia    | 20        | 1.96%   |
| Intel + AMD     | 15        | 1.47%   |
| Other           | 11        | 1.08%   |
| 2 x Intel       | 4         | 0.39%   |
| 2 x Nvidia      | 2         | 0.2%    |
| Nvidia + Matrox | 1         | 0.1%    |
| 1 x Matrox      | 1         | 0.1%    |
| 1 x ASPEED      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 809       | 79.39%  |
| Proprietary | 135       | 13.25%  |
| Unknown     | 75        | 7.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 669       | 64.27%  |
| 0.01-0.5   | 88        | 8.45%   |
| 1.01-2.0   | 78        | 7.49%   |
| 0.51-1.0   | 61        | 5.86%   |
| 3.01-4.0   | 60        | 5.76%   |
| 7.01-8.0   | 38        | 3.65%   |
| 5.01-6.0   | 21        | 2.02%   |
| 8.01-16.0  | 16        | 1.54%   |
| 2.01-3.0   | 5         | 0.48%   |
| 16.01-24.0 | 5         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 120       | 10.66%  |
| Dell                    | 119       | 10.57%  |
| AU Optronics            | 116       | 10.3%   |
| Samsung Electronics     | 103       | 9.15%   |
| LG Display              | 97        | 8.61%   |
| Chimei Innolux          | 86        | 7.64%   |
| Acer                    | 42        | 3.73%   |
| AOC                     | 39        | 3.46%   |
| Goldstar                | 34        | 3.02%   |
| Sharp                   | 33        | 2.93%   |
| Hewlett-Packard         | 30        | 2.66%   |
| Philips                 | 29        | 2.58%   |
| Apple                   | 28        | 2.49%   |
| Lenovo                  | 27        | 2.4%    |
| BenQ                    | 27        | 2.4%    |
| Iiyama                  | 20        | 1.78%   |
| ViewSonic               | 17        | 1.51%   |
| ASUSTek Computer        | 13        | 1.15%   |
| Chi Mei Optoelectronics | 11        | 0.98%   |
| PANDA                   | 9         | 0.8%    |
| Sony                    | 8         | 0.71%   |
| InfoVision              | 8         | 0.71%   |
| Ancor Communications    | 8         | 0.71%   |
| Vestel Elektronik       | 7         | 0.62%   |
| Valve                   | 7         | 0.62%   |
| MSI                     | 7         | 0.62%   |
| LG Philips              | 7         | 0.62%   |
| HannStar                | 5         | 0.44%   |
| Unknown                 | 4         | 0.36%   |
| CSO                     | 4         | 0.36%   |
| ___                     | 3         | 0.27%   |
| Toshiba                 | 3         | 0.27%   |
| Panasonic               | 3         | 0.27%   |
| KDB                     | 3         | 0.27%   |
| HKC                     | 3         | 0.27%   |
| OEM                     | 2         | 0.18%   |
| NEC Computers           | 2         | 0.18%   |
| MiTAC                   | 2         | 0.18%   |
| Medion                  | 2         | 0.18%   |
| HUAWEI                  | 2         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                     | 9         | 0.77%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                 | 9         | 0.77%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch             | 8         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 8         | 0.68%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch  | 7         | 0.6%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 0.51%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 6         | 0.51%   |
| Acer KA220Q B ACR0A30 1920x1080 476x267mm 21.5-inch                   | 6         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 5         | 0.43%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 580x320mm 26.1-inch  | 5         | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.43%   |
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                  | 5         | 0.43%   |
| BOE LCD Monitor BOE0964 1920x1200 286x179mm 13.3-inch                 | 5         | 0.43%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch               | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.43%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 5         | 0.43%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5         | 0.43%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 5         | 0.43%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 5         | 0.43%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 4         | 0.34%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 4         | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 4         | 0.34%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 4         | 0.34%   |
| ___ LCD TV ___9000 1360x768                                           | 3         | 0.26%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 3         | 0.26%   |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                    | 3         | 0.26%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.26%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 3         | 0.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 3         | 0.26%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 3         | 0.26%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 3         | 0.26%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 3         | 0.26%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 3         | 0.26%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 3         | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.26%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 3         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 485       | 45.63%  |
| 1366x768 (WXGA)    | 147       | 13.83%  |
| 3840x2160 (4K)     | 84        | 7.9%    |
| 2560x1440 (QHD)    | 71        | 6.68%   |
| 1920x1200 (WUXGA)  | 41        | 3.86%   |
| 1600x900 (HD+)     | 29        | 2.73%   |
| 1280x1024 (SXGA)   | 28        | 2.63%   |
| 1440x900 (WXGA+)   | 20        | 1.88%   |
| 1280x800 (WXGA)    | 20        | 1.88%   |
| 3440x1440          | 17        | 1.6%    |
| 2880x1800          | 14        | 1.32%   |
| 2560x1600          | 14        | 1.32%   |
| 1680x1050 (WSXGA+) | 12        | 1.13%   |
| 1360x768           | 9         | 0.85%   |
| Unknown            | 9         | 0.85%   |
| 800x1280           | 8         | 0.75%   |
| 3840x1080          | 6         | 0.56%   |
| 3840x2400          | 5         | 0.47%   |
| 2560x1080          | 5         | 0.47%   |
| 2256x1504          | 4         | 0.38%   |
| 2160x1440          | 4         | 0.38%   |
| 1024x600           | 4         | 0.38%   |
| 3456x2160          | 3         | 0.28%   |
| 3200x1800 (QHD+)   | 3         | 0.28%   |
| 1920x540           | 3         | 0.28%   |
| 1600x1200          | 3         | 0.28%   |
| 1024x768 (XGA)     | 3         | 0.28%   |
| 3840x1100          | 2         | 0.19%   |
| 6400x2160          | 1         | 0.09%   |
| 5280x2560          | 1         | 0.09%   |
| 4480x1440          | 1         | 0.09%   |
| 3840x1600          | 1         | 0.09%   |
| 3840x1200          | 1         | 0.09%   |
| 3600x1080          | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |
| 2496x1664          | 1         | 0.09%   |
| 2160x1200          | 1         | 0.09%   |
| 1920x1280          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 265       | 23.56%  |
| 27      | 117       | 10.4%   |
| 14      | 112       | 9.96%   |
| 13      | 109       | 9.69%   |
| 24      | 91        | 8.09%   |
| 21      | 69        | 6.13%   |
| 23      | 53        | 4.71%   |
| 17      | 42        | 3.73%   |
| Unknown | 33        | 2.93%   |
| 12      | 28        | 2.49%   |
| 31      | 25        | 2.22%   |
| 19      | 25        | 2.22%   |
| 34      | 20        | 1.78%   |
| 16      | 19        | 1.69%   |
| 84      | 13        | 1.16%   |
| 22      | 11        | 0.98%   |
| 11      | 10        | 0.89%   |
| 20      | 9         | 0.8%    |
| 18      | 9         | 0.8%    |
| 32      | 7         | 0.62%   |
| 7       | 7         | 0.62%   |
| 33      | 6         | 0.53%   |
| 72      | 5         | 0.44%   |
| 65      | 5         | 0.44%   |
| 25      | 5         | 0.44%   |
| 40      | 4         | 0.36%   |
| 10      | 4         | 0.36%   |
| 48      | 3         | 0.27%   |
| 75      | 2         | 0.18%   |
| 54      | 2         | 0.18%   |
| 39      | 2         | 0.18%   |
| 29      | 2         | 0.18%   |
| 28      | 2         | 0.18%   |
| 26      | 2         | 0.18%   |
| 55      | 1         | 0.09%   |
| 49      | 1         | 0.09%   |
| 46      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 35      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 437       | 39.69%  |
| 501-600     | 238       | 21.62%  |
| 201-300     | 108       | 9.81%   |
| 401-500     | 106       | 9.63%   |
| 351-400     | 53        | 4.81%   |
| 601-700     | 44        | 4%      |
| Unknown     | 33        | 3%      |
| 701-800     | 32        | 2.91%   |
| 1501-2000   | 20        | 1.82%   |
| 1001-1500   | 14        | 1.27%   |
| 1-100       | 8         | 0.73%   |
| 801-900     | 6         | 0.54%   |
| 901-1000    | 2         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 741       | 75.08%  |
| 16/10   | 133       | 13.48%  |
| 5/4     | 27        | 2.74%   |
| Unknown | 26        | 2.63%   |
| 21/9    | 25        | 2.53%   |
| 3/2     | 12        | 1.22%   |
| 4/3     | 8         | 0.81%   |
| 0.67    | 6         | 0.61%   |
| 32/9    | 4         | 0.41%   |
| 3.40    | 2         | 0.2%    |
| 6/5     | 1         | 0.1%    |
| 3.20    | 1         | 0.1%    |
| 0.62    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 262       | 23.39%  |
| 81-90          | 171       | 15.27%  |
| 201-250        | 170       | 15.18%  |
| 301-350        | 119       | 10.63%  |
| 351-500        | 60        | 5.36%   |
| 151-200        | 53        | 4.73%   |
| 71-80          | 50        | 4.46%   |
| 251-300        | 40        | 3.57%   |
| Unknown        | 33        | 2.95%   |
| More than 1000 | 26        | 2.32%   |
| 61-70          | 26        | 2.32%   |
| 121-130        | 23        | 2.05%   |
| 141-150        | 21        | 1.88%   |
| 111-120        | 21        | 1.88%   |
| 501-1000       | 14        | 1.25%   |
| 51-60          | 12        | 1.07%   |
| 1-40           | 8         | 0.71%   |
| 131-140        | 5         | 0.45%   |
| 41-50          | 4         | 0.36%   |
| 91-100         | 2         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 327       | 30.22%  |
| 51-100        | 317       | 29.3%   |
| 101-120       | 250       | 23.11%  |
| 161-240       | 98        | 9.06%   |
| More than 240 | 39        | 3.6%    |
| Unknown       | 33        | 3.05%   |
| 1-50          | 18        | 1.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 794       | 76.79%  |
| 2     | 167       | 16.15%  |
| 0     | 41        | 3.97%   |
| 3     | 31        | 3%      |
| 4     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 555       | 35.24%  |
| Realtek Semiconductor                  | 492       | 31.24%  |
| Qualcomm Atheros                       | 127       | 8.06%   |
| Broadcom                               | 93        | 5.9%    |
| MediaTek                               | 47        | 2.98%   |
| TP-Link                                | 33        | 2.1%    |
| Ralink Technology                      | 25        | 1.59%   |
| Nvidia                                 | 18        | 1.14%   |
| Marvell Technology Group               | 17        | 1.08%   |
| Broadcom Limited                       | 17        | 1.08%   |
| Ralink                                 | 13        | 0.83%   |
| Samsung Electronics                    | 11        | 0.7%    |
| Shenzhen Goodix Technology             | 10        | 0.63%   |
| Microsoft                              | 9         | 0.57%   |
| DisplayLink                            | 9         | 0.57%   |
| ASIX Electronics                       | 9         | 0.57%   |
| Qualcomm                               | 7         | 0.44%   |
| Lenovo                                 | 6         | 0.38%   |
| Ericsson Business Mobile Networks      | 6         | 0.38%   |
| Xiaomi                                 | 5         | 0.32%   |
| OPPO Electronics                       | 5         | 0.32%   |
| Aquantia                               | 5         | 0.32%   |
| Microchip Technology                   | 4         | 0.25%   |
| Qualcomm Atheros Communications        | 3         | 0.19%   |
| NetGear                                | 3         | 0.19%   |
| Dell                                   | 3         | 0.19%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.13%   |
| Sierra Wireless                        | 2         | 0.13%   |
| ICS Advent                             | 2         | 0.13%   |
| Huawei Technologies                    | 2         | 0.13%   |
| Hewlett-Packard                        | 2         | 0.13%   |
| Google                                 | 2         | 0.13%   |
| Belkin Components                      | 2         | 0.13%   |
| ASUSTek Computer                       | 2         | 0.13%   |
| ZyDAS                                  | 1         | 0.06%   |
| Xilinx                                 | 1         | 0.06%   |
| Van Ooijen Technische Informatica      | 1         | 0.06%   |
| ULi Electronics                        | 1         | 0.06%   |
| U-Blox                                 | 1         | 0.06%   |
| Toshiba                                | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 285       | 15.34%  |
| Intel Wi-Fi 6 AX200                                                    | 58        | 3.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 52        | 2.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 51        | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 45        | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                      | 36        | 1.94%   |
| Intel Wireless 8265 / 8275                                             | 36        | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 32        | 1.72%   |
| Intel Wi-Fi 6 AX201                                                    | 30        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 28        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 23        | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 21        | 1.13%   |
| Intel Wireless 8260                                                    | 20        | 1.08%   |
| Intel Wireless 7265                                                    | 19        | 1.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 19        | 1.02%   |
| Intel Wireless 7260                                                    | 18        | 0.97%   |
| Intel I211 Gigabit Network Connection                                  | 18        | 0.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 17        | 0.91%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 17        | 0.91%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 17        | 0.91%   |
| Intel Ethernet Connection I217-LM                                      | 17        | 0.91%   |
| Realtek 802.11ac NIC                                                   | 16        | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 16        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 0.86%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 15        | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 14        | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 14        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 14        | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 13        | 0.7%    |
| Intel Wireless 3165                                                    | 13        | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 13        | 0.7%    |
| Ralink MT7601U Wireless Adapter                                        | 12        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 11        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                   | 11        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 11        | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 11        | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 11        | 0.59%   |
| Shenzhen Goodix Fingerprint Reader                                     | 10        | 0.54%   |
| Nvidia MCP79 Ethernet                                                  | 10        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 426       | 47.7%   |
| Realtek Semiconductor           | 133       | 14.89%  |
| Qualcomm Atheros                | 112       | 12.54%  |
| Broadcom                        | 65        | 7.28%   |
| MediaTek                        | 40        | 4.48%   |
| TP-Link                         | 32        | 3.58%   |
| Ralink Technology               | 25        | 2.8%    |
| Ralink                          | 13        | 1.46%   |
| Microsoft                       | 8         | 0.9%    |
| Broadcom Limited                | 7         | 0.78%   |
| Qualcomm                        | 6         | 0.67%   |
| Qualcomm Atheros Communications | 3         | 0.34%   |
| NetGear                         | 3         | 0.34%   |
| Marvell Technology Group        | 3         | 0.34%   |
| Dell                            | 3         | 0.34%   |
| Sierra Wireless                 | 2         | 0.22%   |
| Belkin Components               | 2         | 0.22%   |
| ASUSTek Computer                | 2         | 0.22%   |
| ZyDAS                           | 1         | 0.11%   |
| Qualcomm Technologies           | 1         | 0.11%   |
| LG Electronics                  | 1         | 0.11%   |
| IMC Networks                    | 1         | 0.11%   |
| Fibocom                         | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| BUFFALO                         | 1         | 0.11%   |
| Apple                           | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 58        | 6.44%   |
| Intel Wireless 8265 / 8275                                           | 36        | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 32        | 3.56%   |
| Intel Wi-Fi 6 AX201                                                  | 30        | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 28        | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 23        | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 21        | 2.33%   |
| Intel Wireless 8260                                                  | 20        | 2.22%   |
| Intel Wireless 7265                                                  | 19        | 2.11%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 19        | 2.11%   |
| Intel Wireless 7260                                                  | 18        | 2%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 17        | 1.89%   |
| Realtek 802.11ac NIC                                                 | 16        | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 16        | 1.78%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 16        | 1.78%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 15        | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 14        | 1.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 14        | 1.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 13        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 13        | 1.44%   |
| Intel Wireless 3165                                                  | 13        | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 13        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 13        | 1.44%   |
| Ralink MT7601U Wireless Adapter                                      | 12        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 11        | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 11        | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 11        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 11        | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 10        | 1.11%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 10        | 1.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 9         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 9         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 9         | 1%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 9         | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 8         | 0.89%   |
| Ralink RT5370 Wireless Adapter                                       | 8         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                        | 8         | 0.89%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 7         | 0.78%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 6         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 6         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 422       | 46.84%  |
| Intel                                  | 289       | 32.08%  |
| Broadcom                               | 40        | 4.44%   |
| Qualcomm Atheros                       | 26        | 2.89%   |
| Nvidia                                 | 18        | 2%      |
| Marvell Technology Group               | 14        | 1.55%   |
| Samsung Electronics                    | 11        | 1.22%   |
| Broadcom Limited                       | 11        | 1.22%   |
| DisplayLink                            | 9         | 1%      |
| ASIX Electronics                       | 9         | 1%      |
| MediaTek                               | 6         | 0.67%   |
| Lenovo                                 | 6         | 0.67%   |
| Xiaomi                                 | 5         | 0.55%   |
| OPPO Electronics                       | 5         | 0.55%   |
| Aquantia                               | 5         | 0.55%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.22%   |
| Microchip Technology                   | 2         | 0.22%   |
| ICS Advent                             | 2         | 0.22%   |
| Google                                 | 2         | 0.22%   |
| Xilinx                                 | 1         | 0.11%   |
| ULi Electronics                        | 1         | 0.11%   |
| TP-Link                                | 1         | 0.11%   |
| T & A Mobile Phones                    | 1         | 0.11%   |
| Qualcomm                               | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.11%   |
| NetXen Incorporated                    | 1         | 0.11%   |
| Naxiang                                | 1         | 0.11%   |
| Motorola PCS                           | 1         | 0.11%   |
| Microsoft                              | 1         | 0.11%   |
| Mellanox Technologies                  | 1         | 0.11%   |
| JMicron Technology                     | 1         | 0.11%   |
| Huawei Technologies                    | 1         | 0.11%   |
| HMD Global                             | 1         | 0.11%   |
| Hewlett-Packard                        | 1         | 0.11%   |
| ADMtek                                 | 1         | 0.11%   |
| 3Com                                   | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 285       | 30.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 52        | 5.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 51        | 5.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 45        | 4.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 36        | 3.88%   |
| Intel I211 Gigabit Network Connection                                  | 18        | 1.94%   |
| Intel Ethernet Connection I217-LM                                      | 17        | 1.83%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 1.72%   |
| Intel Ethernet Connection (4) I219-V                                   | 11        | 1.18%   |
| Nvidia MCP79 Ethernet                                                  | 10        | 1.08%   |
| Intel Ethernet Controller I225-V                                       | 10        | 1.08%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7         | 0.75%   |
| Intel Ethernet Controller I226-V                                       | 6         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.65%   |
| Intel Ethernet Connection (2) I218-V                                   | 6         | 0.65%   |
| Intel Ethernet Connection (11) I219-LM                                 | 6         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 0.65%   |
| OPPO Ace 3V                                                            | 5         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 0.54%   |
| Intel Ethernet Controller I225-LM                                      | 5         | 0.54%   |
| Intel Ethernet Connection I219-V                                       | 5         | 0.54%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.54%   |
| Intel Ethernet Connection (10) I219-V                                  | 5         | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 4         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.43%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 4         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.43%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 0.43%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 837       | 49.35%  |
| Ethernet | 830       | 48.94%  |
| Modem    | 29        | 1.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 632       | 60.54%  |
| Ethernet | 412       | 39.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 551       | 54.61%  |
| 1     | 401       | 39.74%  |
| 3     | 28        | 2.78%   |
| 0     | 24        | 2.38%   |
| 4     | 3         | 0.3%    |
| 6     | 2         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 838       | 82.32%  |
| Yes  | 180       | 17.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 362       | 50.21%  |
| Realtek Semiconductor           | 71        | 9.85%   |
| IMC Networks                    | 41        | 5.69%   |
| Qualcomm Atheros Communications | 39        | 5.41%   |
| Cambridge Silicon Radio         | 39        | 5.41%   |
| Broadcom                        | 31        | 4.3%    |
| Apple                           | 25        | 3.47%   |
| Foxconn / Hon Hai               | 21        | 2.91%   |
| Lite-On Technology              | 20        | 2.77%   |
| MediaTek                        | 13        | 1.8%    |
| Dell                            | 12        | 1.66%   |
| ASUSTek Computer                | 8         | 1.11%   |
| Toshiba                         | 7         | 0.97%   |
| Hewlett-Packard                 | 7         | 0.97%   |
| TP-Link                         | 4         | 0.55%   |
| Realtek                         | 4         | 0.55%   |
| USI                             | 3         | 0.42%   |
| Edimax Technology               | 3         | 0.42%   |
| Marvell Semiconductor           | 2         | 0.28%   |
| Foxconn International           | 2         | 0.28%   |
| Belkin Components               | 2         | 0.28%   |
| SiW                             | 1         | 0.14%   |
| Ralink                          | 1         | 0.14%   |
| Qcom                            | 1         | 0.14%   |
| Conwise Technology              | 1         | 0.14%   |
| Unknown                         | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 113       | 15.63%  |
| Intel AX201 Bluetooth                               | 72        | 9.96%   |
| Intel AX200 Bluetooth                               | 53        | 7.33%   |
| Realtek Bluetooth Radio                             | 52        | 7.19%   |
| Intel Bluetooth Device                              | 40        | 5.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 5.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 4.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 2.9%    |
| IMC Networks Bluetooth Radio                        | 18        | 2.49%   |
| Intel AX210 Bluetooth                               | 17        | 2.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 2.07%   |
| IMC Networks Wireless_Device                        | 14        | 1.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.8%    |
| MediaTek Wireless_Device                            | 13        | 1.8%    |
| Apple Bluetooth Host Controller                     | 13        | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.24%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 0.97%   |
| IMC Networks Bluetooth Device                       | 7         | 0.97%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.97%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.97%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 5         | 0.69%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.69%   |
| TP-Link TP-T@- UB500 Adapter                        | 4         | 0.55%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.55%   |
| Realtek Bluetooth Radio                             | 4         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.55%   |
| Lite-On Wireless_Device                             | 4         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.55%   |
| Apple Bluetooth HCI                                 | 4         | 0.55%   |
| USI Bluetooth Device                                | 3         | 0.41%   |
| Toshiba Bluetooth Device                            | 3         | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 697       | 48.74%  |
| AMD                                  | 319       | 22.31%  |
| Nvidia                               | 228       | 15.94%  |
| C-Media Electronics                  | 16        | 1.12%   |
| Realtek Semiconductor                | 13        | 0.91%   |
| Plantronics                          | 12        | 0.84%   |
| Logitech                             | 11        | 0.77%   |
| GN Netcom                            | 10        | 0.7%    |
| Kingston Technology                  | 9         | 0.63%   |
| Focusrite-Novation                   | 8         | 0.56%   |
| Creative Labs                        | 8         | 0.56%   |
| Creative Technology                  | 7         | 0.49%   |
| Lenovo                               | 6         | 0.42%   |
| Texas Instruments                    | 5         | 0.35%   |
| SteelSeries ApS                      | 4         | 0.28%   |
| Sony                                 | 4         | 0.28%   |
| Blue Microphones                     | 4         | 0.28%   |
| BEHRINGER International              | 4         | 0.28%   |
| RODE Microphones                     | 3         | 0.21%   |
| JMTek                                | 3         | 0.21%   |
| Generalplus Technology               | 3         | 0.21%   |
| FiiO Electronics Technology          | 3         | 0.21%   |
| Dell                                 | 3         | 0.21%   |
| VIA Technologies                     | 2         | 0.14%   |
| Turtle Beach                         | 2         | 0.14%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.14%   |
| Setek Elektronik                     | 2         | 0.14%   |
| Razer USA                            | 2         | 0.14%   |
| Micronas                             | 2         | 0.14%   |
| Micro Star International             | 2         | 0.14%   |
| KTMicro                              | 2         | 0.14%   |
| Giga-Byte Technology                 | 2         | 0.14%   |
| Ensoniq                              | 2         | 0.14%   |
| Audient                              | 2         | 0.14%   |
| XMOS                                 | 1         | 0.07%   |
| Walmart                              | 1         | 0.07%   |
| USB MICROPHONE                       | 1         | 0.07%   |
| ULi Electronics                      | 1         | 0.07%   |
| Trust                                | 1         | 0.07%   |
| SAVITECH                             | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 125       | 7.34%   |
| Intel Sunrise Point-LP HD Audio                                            | 91        | 5.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 68        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 59        | 3.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 48        | 2.82%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 43        | 2.53%   |
| AMD Radeon High Definition Audio Controller                                | 42        | 2.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 40        | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 33        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 27        | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 27        | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 25        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24        | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 24        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 23        | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 22        | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 21        | 1.23%   |
| AMD FCH Azalia Controller                                                  | 21        | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 19        | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 18        | 1.06%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 18        | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 18        | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1%      |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 0.94%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 16        | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 15        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 15        | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 14        | 0.82%   |
| Realtek Semiconductor USB Audio                                            | 13        | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 0.76%   |
| Intel 200 Series PCH HD Audio                                              | 13        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 12        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 145       | 22.21%  |
| SK hynix                           | 122       | 18.68%  |
| Micron Technology                  | 74        | 11.33%  |
| Corsair                            | 62        | 9.49%   |
| Crucial                            | 60        | 9.19%   |
| Kingston                           | 53        | 8.12%   |
| Unknown                            | 44        | 6.74%   |
| Ramaxel Technology                 | 16        | 2.45%   |
| G.Skill                            | 14        | 2.14%   |
| Unknown                            | 11        | 1.68%   |
| Elpida                             | 8         | 1.23%   |
| Unknown (ABCD)                     | 7         | 1.07%   |
| Nanya Technology                   | 5         | 0.77%   |
| Patriot                            | 4         | 0.61%   |
| A-DATA Technology                  | 4         | 0.61%   |
| Team                               | 3         | 0.46%   |
| Apacer                             | 3         | 0.46%   |
| A Force                            | 2         | 0.31%   |
| Unknown (AD8A)                     | 1         | 0.15%   |
| Unknown (0x0B45)                   | 1         | 0.15%   |
| Transcend                          | 1         | 0.15%   |
| Toshiba                            | 1         | 0.15%   |
| Timetec                            | 1         | 0.15%   |
| Silicon Power                      | 1         | 0.15%   |
| SHARETRONIC                        | 1         | 0.15%   |
| OSV                                | 1         | 0.15%   |
| KLEVV                              | 1         | 0.15%   |
| Kimtigo Semiconductor (HK) Limited | 1         | 0.15%   |
| INNOVATION PC                      | 1         | 0.15%   |
| Infineon                           | 1         | 0.15%   |
| CXMT                               | 1         | 0.15%   |
| CSX                                | 1         | 0.15%   |
| BiNFUL                             | 1         | 0.15%   |
| 4ea5                               | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 11        | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 8         | 1.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.99%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.85%   |
| Crucial RAM CT8G4SFS824A.C8FN 8GB SODIMM DDR4 2400MT/s           | 6         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 5         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.71%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.71%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.71%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.71%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 4         | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 4         | 0.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 4         | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 4         | 0.57%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 4         | 0.57%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 4         | 0.57%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s           | 4         | 0.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 4         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.42%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.42%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.42%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.42%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.42%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.42%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.42%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 3         | 0.42%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3400MT/s            | 3         | 0.42%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 0.42%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 2         | 0.28%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.28%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 269       | 47.7%   |
| DDR3    | 141       | 25%     |
| DDR5    | 36        | 6.38%   |
| LPDDR4  | 28        | 4.96%   |
| LPDDR5  | 20        | 3.55%   |
| DDR2    | 17        | 3.01%   |
| Unknown | 17        | 3.01%   |
| SDRAM   | 15        | 2.66%   |
| LPDDR3  | 15        | 2.66%   |
| DRAM    | 3         | 0.53%   |
| DDR     | 3         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 322       | 57.3%   |
| DIMM         | 174       | 30.96%  |
| Row Of Chips | 53        | 9.43%   |
| Chip         | 7         | 1.25%   |
| Unknown      | 5         | 0.89%   |
| RIMM         | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 232       | 37.36%  |
| 4096  | 152       | 24.48%  |
| 16384 | 122       | 19.65%  |
| 2048  | 57        | 9.18%   |
| 32768 | 35        | 5.64%   |
| 1024  | 15        | 2.42%   |
| 512   | 2         | 0.32%   |
| 128   | 2         | 0.32%   |
| 49152 | 1         | 0.16%   |
| 24576 | 1         | 0.16%   |
| 12288 | 1         | 0.16%   |
| 256   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 99        | 15.76%  |
| 1600    | 94        | 14.97%  |
| 2667    | 87        | 13.85%  |
| 2400    | 46        | 7.32%   |
| 2133    | 32        | 5.1%    |
| 1333    | 29        | 4.62%   |
| 3600    | 21        | 3.34%   |
| 800     | 16        | 2.55%   |
| 4267    | 15        | 2.39%   |
| 5600    | 14        | 2.23%   |
| 667     | 14        | 2.23%   |
| 1867    | 13        | 2.07%   |
| 4800    | 12        | 1.91%   |
| 1334    | 12        | 1.91%   |
| 3266    | 11        | 1.75%   |
| 6400    | 10        | 1.59%   |
| 8400    | 7         | 1.11%   |
| 6000    | 7         | 1.11%   |
| 3800    | 7         | 1.11%   |
| 1067    | 7         | 1.11%   |
| 1866    | 6         | 0.96%   |
| 1800    | 6         | 0.96%   |
| 3400    | 5         | 0.8%    |
| Unknown | 5         | 0.8%    |
| 7500    | 4         | 0.64%   |
| 5200    | 4         | 0.64%   |
| 4266    | 4         | 0.64%   |
| 3000    | 4         | 0.64%   |
| 4199    | 3         | 0.48%   |
| 2666    | 3         | 0.48%   |
| 1066    | 3         | 0.48%   |
| 533     | 3         | 0.48%   |
| 7467    | 2         | 0.32%   |
| 3466    | 2         | 0.32%   |
| 2933    | 2         | 0.32%   |
| 2267    | 2         | 0.32%   |
| 2048    | 2         | 0.32%   |
| 1648    | 2         | 0.32%   |
| 1639    | 2         | 0.32%   |
| 975     | 2         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 28.57%  |
| Canon               | 3         | 21.43%  |
| STMicroelectronics  | 2         | 14.29%  |
| Seiko Epson         | 2         | 14.29%  |
| Samsung Electronics | 1         | 7.14%   |
| QinHeng Electronics | 1         | 7.14%   |
| Hewlett-Packard     | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 14.29%  |
| Seiko Epson ET-2710 Series                                | 1         | 7.14%   |
| Seiko Epson EPSON WF-3520 Series                          | 1         | 7.14%   |
| Samsung M2070 Series                                      | 1         | 7.14%   |
| QinHeng CH340S                                            | 1         | 7.14%   |
| HP Officejet 4500 G510g-m                                 | 1         | 7.14%   |
| Canon TS5300 series                                       | 1         | 7.14%   |
| Canon PIXMA MG3600 Series                                 | 1         | 7.14%   |
| Canon PIXMA MG2500 Series                                 | 1         | 7.14%   |
| Brother MFC-L2700DW                                       | 1         | 7.14%   |
| Brother HL-L2340D series                                  | 1         | 7.14%   |
| Brother HL-2030 Laser Printer                             | 1         | 7.14%   |
| Brother DCP-J140W                                         | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 138       | 21.2%   |
| Realtek Semiconductor                  | 63        | 9.68%   |
| Microdia                               | 63        | 9.68%   |
| IMC Networks                           | 62        | 9.52%   |
| Sunplus Innovation Technology          | 45        | 6.91%   |
| Bison Electronics                      | 45        | 6.91%   |
| Logitech                               | 44        | 6.76%   |
| Quanta                                 | 28        | 4.3%    |
| Apple                                  | 24        | 3.69%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 2.46%   |
| Microsoft                              | 11        | 1.69%   |
| Luxvisions Innotech Limited            | 10        | 1.54%   |
| Syntek                                 | 8         | 1.23%   |
| Samsung Electronics                    | 8         | 1.23%   |
| Lite-On Technology                     | 8         | 1.23%   |
| Suyin                                  | 7         | 1.08%   |
| Sonix Technology                       | 6         | 0.92%   |
| ALi                                    | 6         | 0.92%   |
| Silicon Motion                         | 5         | 0.77%   |
| Ricoh                                  | 5         | 0.77%   |
| SunplusIT                              | 4         | 0.61%   |
| Razer USA                              | 4         | 0.61%   |
| kingcome                               | 4         | 0.61%   |
| Lenovo                                 | 3         | 0.46%   |
| Generalplus Technology                 | 3         | 0.46%   |
| Alcor Micro                            | 3         | 0.46%   |
| Z-Star Microelectronics                | 2         | 0.31%   |
| webcam                                 | 2         | 0.31%   |
| Trust                                  | 2         | 0.31%   |
| Creative Technology                    | 2         | 0.31%   |
| Acer                                   | 2         | 0.31%   |
| Y Media                                | 1         | 0.15%   |
| WaveRider Communications               | 1         | 0.15%   |
| USB3.0 HD Audio Capture                | 1         | 0.15%   |
| Shinetech                              | 1         | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.15%   |
| Nokia Mobile Phones                    | 1         | 0.15%   |
| Nikon                                  | 1         | 0.15%   |
| MacroSilicon                           | 1         | 0.15%   |
| LianYi                                 | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 38        | 5.78%   |
| Microdia Integrated_Webcam_HD                                   | 31        | 4.71%   |
| Realtek Integrated_Webcam_HD                                    | 23        | 3.5%    |
| IMC Networks Integrated Camera                                  | 20        | 3.04%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 16        | 2.43%   |
| Bison Integrated Camera                                         | 16        | 2.43%   |
| Logitech HD Pro Webcam C920                                     | 15        | 2.28%   |
| Apple Built-in iSight                                           | 13        | 1.98%   |
| Sunplus Integrated_Webcam_HD                                    | 11        | 1.67%   |
| Sunplus Integrated_Webcam_FHD                                   | 10        | 1.52%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 8         | 1.22%   |
| IMC Networks EasyCamera                                         | 8         | 1.22%   |
| Chicony HD WebCam                                               | 8         | 1.22%   |
| Microsoft LifeCam HD-3000                                       | 7         | 1.06%   |
| Chicony USB2.0 Camera                                           | 7         | 1.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 7         | 1.06%   |
| Microdia Integrated Webcam                                      | 6         | 0.91%   |
| Logitech Webcam C270                                            | 6         | 0.91%   |
| Lite-On HP HD Camera                                            | 6         | 0.91%   |
| Chicony Integrated Camera (1280x720@30)                         | 6         | 0.91%   |
| Chicony HP Wide Vision HD Camera                                | 6         | 0.91%   |
| Syntek Integrated Camera                                        | 5         | 0.76%   |
| Realtek Integrated Webcam HD                                    | 5         | 0.76%   |
| Microdia Webcam Vitade AF                                       | 5         | 0.76%   |
| Chicony USB2.0 HD UVC WebCam                                    | 5         | 0.76%   |
| Chicony HP HD Camera                                            | 5         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 0.76%   |
| Bison EasyCamera                                                | 5         | 0.76%   |
| Bison BisonCam,NB Pro                                           | 5         | 0.76%   |
| Bison BisonCam, NB Pro                                          | 5         | 0.76%   |
| Apple FaceTime HD Camera (Built-in)                             | 5         | 0.76%   |
| Sonix USB2.0 FHD UVC WebCam                                     | 4         | 0.61%   |
| Realtek Integrated_Webcam_FHD                                   | 4         | 0.61%   |
| Quanta HP Wide Vision HD Camera                                 | 4         | 0.61%   |
| Luxvisions Innotech Limited Integrated Camera                   | 4         | 0.61%   |
| Logitech Logitech Webcam C925e                                  | 4         | 0.61%   |
| Chicony TOSHIBA Web Camera - HD                                 | 4         | 0.61%   |
| Chicony Integrated IR Camera                                    | 4         | 0.61%   |
| Chicony HP Truevision HD camera                                 | 4         | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                            | 3         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 52        | 40.94%  |
| Validity Sensors           | 31        | 24.41%  |
| Shenzhen Goodix Technology | 20        | 15.75%  |
| Elan Microelectronics      | 7         | 5.51%   |
| Upek                       | 6         | 4.72%   |
| LighTuning Technology      | 4         | 3.15%   |
| AuthenTec                  | 4         | 3.15%   |
| STMicroelectronics         | 1         | 0.79%   |
| HOLTEK                     | 1         | 0.79%   |
| Focal-systems.Corp         | 1         | 0.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 7.87%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 7.87%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 7.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 6.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.72%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 4.72%   |
| Synaptics UWP WBDI Device                                                  | 5         | 3.94%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 3.94%   |
| Elan ELAN:ARM-M4                                                           | 5         | 3.94%   |
| Unknown                                                                    | 5         | 3.94%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.15%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.36%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.36%   |
| Synaptics UWP WBDI                                                         | 3         | 2.36%   |
| Synaptics  WBDI                                                            | 3         | 2.36%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 2.36%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 2.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.57%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.57%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.79%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.79%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.79%   |
| Synaptics WBDI Device                                                      | 1         | 0.79%   |
| Synaptics WBDI                                                             | 1         | 0.79%   |
| Synaptics TouchPad                                                         | 1         | 0.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.79%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 0.79%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.79%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.79%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 50        | 64.1%   |
| Alcor Micro                       | 12        | 15.38%  |
| Upek                              | 7         | 8.97%   |
| O2 Micro                          | 5         | 6.41%   |
| Lenovo                            | 2         | 2.56%   |
| Gemalto (was Gemplus)             | 1         | 1.28%   |
| Free Software Initiative of Japan | 1         | 1.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 18        | 23.08%  |
| Broadcom 5880                                                                | 14        | 17.95%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 12.82%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 8.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 6.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.13%   |
| Broadcom 58200                                                               | 3         | 3.85%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.28%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.28%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 1.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 660       | 64.14%  |
| 1     | 298       | 28.96%  |
| 2     | 59        | 5.73%   |
| 3     | 10        | 0.97%   |
| 7     | 1         | 0.1%    |
| 5     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 125       | 29.07%  |
| Net/wireless             | 80        | 18.6%   |
| Graphics card            | 80        | 18.6%   |
| Chipcard                 | 67        | 15.58%  |
| Multimedia controller    | 22        | 5.12%   |
| Communication controller | 11        | 2.56%   |
| Camera                   | 9         | 2.09%   |
| Storage                  | 7         | 1.63%   |
| Net/ethernet             | 7         | 1.63%   |
| Bluetooth                | 5         | 1.16%   |
| Unassigned class         | 4         | 0.93%   |
| Card reader              | 4         | 0.93%   |
| Storage/raid             | 2         | 0.47%   |
| Modem                    | 2         | 0.47%   |
| Storage/ata              | 1         | 0.23%   |
| Sound                    | 1         | 0.23%   |
| Network                  | 1         | 0.23%   |
| Firewire controller      | 1         | 0.23%   |
| Dvb card                 | 1         | 0.23%   |

