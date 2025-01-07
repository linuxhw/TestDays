Linux in Finland - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

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

Total: 1432

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 640 G1              | [d6e43bba74](https://linux-hardware.org/?probe=d6e43bba74) | Jan 06, 2025 |
| HP            | ProBook 640 G1              | [7b033a8375](https://linux-hardware.org/?probe=7b033a8375) | Jan 06, 2025 |
| HP            | ProBook 450 G3              | [a1f8c7d33c](https://linux-hardware.org/?probe=a1f8c7d33c) | Jan 05, 2025 |
| Dell          | Inspiron 7520               | [d24db96b79](https://linux-hardware.org/?probe=d24db96b79) | Jan 01, 2025 |
| Lenovo        | IdeaPad U510 4941           | [78a774dc27](https://linux-hardware.org/?probe=78a774dc27) | Jan 01, 2025 |
| Dell          | Inspiron 1011               | [d0c3eef6f6](https://linux-hardware.org/?probe=d0c3eef6f6) | Dec 31, 2024 |
| Dell          | Inspiron 7520               | [f60d84588c](https://linux-hardware.org/?probe=f60d84588c) | Dec 31, 2024 |
| Valve         | Galileo                     | [d942a63123](https://linux-hardware.org/?probe=d942a63123) | Dec 30, 2024 |
| Unchartevi... | 6540                        | [1d27092258](https://linux-hardware.org/?probe=1d27092258) | Dec 29, 2024 |
| ASUSTek       | X751NA                      | [f5f28d0769](https://linux-hardware.org/?probe=f5f28d0769) | Dec 25, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [d076330974](https://linux-hardware.org/?probe=d076330974) | Dec 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0ade3a3f94](https://linux-hardware.org/?probe=0ade3a3f94) | Dec 22, 2024 |
| HP            | ProBook 640 G1              | [7c92813622](https://linux-hardware.org/?probe=7c92813622) | Dec 19, 2024 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [9c999b2e96](https://linux-hardware.org/?probe=9c999b2e96) | Dec 18, 2024 |
| HP            | Pavilion dv6                | [c6677142e4](https://linux-hardware.org/?probe=c6677142e4) | Dec 16, 2024 |
| Apple         | MacBookPro10,1              | [e27d08b364](https://linux-hardware.org/?probe=e27d08b364) | Dec 15, 2024 |
| Apple         | MacBookPro10,1              | [96ffa04014](https://linux-hardware.org/?probe=96ffa04014) | Dec 15, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f7062395dc](https://linux-hardware.org/?probe=f7062395dc) | Dec 15, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ee8dddc4e4](https://linux-hardware.org/?probe=ee8dddc4e4) | Dec 12, 2024 |
| HP            | EliteBook 745 G6            | [b46ff16ea8](https://linux-hardware.org/?probe=b46ff16ea8) | Dec 11, 2024 |
| HP            | Laptop 15-dw0xxx            | [a331c3b846](https://linux-hardware.org/?probe=a331c3b846) | Dec 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [c21e962ea0](https://linux-hardware.org/?probe=c21e962ea0) | Dec 10, 2024 |
| MSI           | Katana GF76 11UE            | [96e708290f](https://linux-hardware.org/?probe=96e708290f) | Dec 08, 2024 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [d1dafff4c9](https://linux-hardware.org/?probe=d1dafff4c9) | Dec 08, 2024 |
| Packard Be... | EasyNote TS11HR             | [9be4f893aa](https://linux-hardware.org/?probe=9be4f893aa) | Dec 07, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [3e24a418c3](https://linux-hardware.org/?probe=3e24a418c3) | Dec 06, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [fdd1f52e06](https://linux-hardware.org/?probe=fdd1f52e06) | Dec 06, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [ee7e95092d](https://linux-hardware.org/?probe=ee7e95092d) | Dec 05, 2024 |
| HP            | EliteBook 830 G5            | [4987877bbe](https://linux-hardware.org/?probe=4987877bbe) | Dec 03, 2024 |
| Lenovo        | ThinkPad P16 Gen 2 21FA0... | [a2afd1ee93](https://linux-hardware.org/?probe=a2afd1ee93) | Nov 27, 2024 |
| ASUSTek       | UX32VD                      | [84ed5ccaa6](https://linux-hardware.org/?probe=84ed5ccaa6) | Nov 25, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [79dfcb127b](https://linux-hardware.org/?probe=79dfcb127b) | Nov 22, 2024 |
| Fujitsu       | LIFEBOOK A514               | [0c1b1704f6](https://linux-hardware.org/?probe=0c1b1704f6) | Nov 20, 2024 |
| Lenovo        | Yoga 500-15IBD 80N6         | [e157b1804e](https://linux-hardware.org/?probe=e157b1804e) | Nov 16, 2024 |
| Fujitsu       | LIFEBOOK A530               | [3f35643c04](https://linux-hardware.org/?probe=3f35643c04) | Nov 12, 2024 |
| Fujitsu       | Unknown                     | [e1f88f1f19](https://linux-hardware.org/?probe=e1f88f1f19) | Nov 12, 2024 |
| HP            | Notebook                    | [60dba81312](https://linux-hardware.org/?probe=60dba81312) | Nov 12, 2024 |
| ASUSTek       | ZenBook S UX391UA           | [8913deb8fe](https://linux-hardware.org/?probe=8913deb8fe) | Nov 12, 2024 |
| HP            | Notebook                    | [3d619505fc](https://linux-hardware.org/?probe=3d619505fc) | Nov 12, 2024 |
| Acer          | Swift SF14-11               | [97526f926d](https://linux-hardware.org/?probe=97526f926d) | Nov 11, 2024 |
| Dell          | XPS 15 9530                 | [5667c491cd](https://linux-hardware.org/?probe=5667c491cd) | Nov 10, 2024 |
| Lenovo        | ThinkPad T560 20FHS06V00    | [c45dfe1fdd](https://linux-hardware.org/?probe=c45dfe1fdd) | Nov 08, 2024 |
| Acer          | Swift SF14-11               | [731d294cbe](https://linux-hardware.org/?probe=731d294cbe) | Nov 08, 2024 |
| Samsung       | Galaxy S2 (GT-I9100)        | [c732892f18](https://linux-hardware.org/?probe=c732892f18) | Nov 05, 2024 |
| Lenovo        | ThinkPad X200 7459D12       | [a34523d690](https://linux-hardware.org/?probe=a34523d690) | Nov 05, 2024 |
| HP            | 15                          | [b69517827e](https://linux-hardware.org/?probe=b69517827e) | Nov 03, 2024 |
| Apple         | MacBookPro10,1              | [1c42e6c25f](https://linux-hardware.org/?probe=1c42e6c25f) | Nov 02, 2024 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [fe49c1b15d](https://linux-hardware.org/?probe=fe49c1b15d) | Nov 01, 2024 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [7ea533c0eb](https://linux-hardware.org/?probe=7ea533c0eb) | Nov 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [0672cada99](https://linux-hardware.org/?probe=0672cada99) | Oct 30, 2024 |
| ASUSTek       | S551LB                      | [8b564e5511](https://linux-hardware.org/?probe=8b564e5511) | Oct 28, 2024 |
| Lenovo        | ThinkPad X390 20Q1S6W600    | [8e5f1a7f66](https://linux-hardware.org/?probe=8e5f1a7f66) | Oct 27, 2024 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [0941cfd8b8](https://linux-hardware.org/?probe=0941cfd8b8) | Oct 26, 2024 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [1c4bfc91f8](https://linux-hardware.org/?probe=1c4bfc91f8) | Oct 26, 2024 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [4d4b2c7929](https://linux-hardware.org/?probe=4d4b2c7929) | Oct 26, 2024 |
| ASUSTek       | GL553VE                     | [ac2e87e2ce](https://linux-hardware.org/?probe=ac2e87e2ce) | Oct 23, 2024 |
| Fujitsu       | LIFEBOOK AH531              | [7205fb0b92](https://linux-hardware.org/?probe=7205fb0b92) | Oct 23, 2024 |
| Lenovo        | G50-80 80E5                 | [38f6fb752d](https://linux-hardware.org/?probe=38f6fb752d) | Oct 23, 2024 |
| Fujitsu       | LIFEBOOK E559               | [96ff5d9648](https://linux-hardware.org/?probe=96ff5d9648) | Oct 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fcf2df9453](https://linux-hardware.org/?probe=fcf2df9453) | Oct 22, 2024 |
| MSI           | GS60 6QE                    | [7e1d315d47](https://linux-hardware.org/?probe=7e1d315d47) | Oct 22, 2024 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | [c73cd8024e](https://linux-hardware.org/?probe=c73cd8024e) | Oct 21, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [369e3e4bdd](https://linux-hardware.org/?probe=369e3e4bdd) | Oct 21, 2024 |
| Dell          | Latitude 5430               | [3519e7a530](https://linux-hardware.org/?probe=3519e7a530) | Oct 21, 2024 |
| Dell          | Latitude 5430               | [aea23cbc32](https://linux-hardware.org/?probe=aea23cbc32) | Oct 21, 2024 |
| Fujitsu       | LIFEBOOK E559               | [2ec391ffdc](https://linux-hardware.org/?probe=2ec391ffdc) | Oct 20, 2024 |
| Gigabyte      | P2542                       | [10122364e5](https://linux-hardware.org/?probe=10122364e5) | Oct 17, 2024 |
| HP            | Pavilion 15                 | [a6276808ad](https://linux-hardware.org/?probe=a6276808ad) | Oct 17, 2024 |
| HP            | Pavilion 11 x360 PC         | [161e32efcd](https://linux-hardware.org/?probe=161e32efcd) | Oct 16, 2024 |
| ASUSTek       | E403NA                      | [9ae450e44c](https://linux-hardware.org/?probe=9ae450e44c) | Oct 13, 2024 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [3d7009833d](https://linux-hardware.org/?probe=3d7009833d) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [aa8a91dad1](https://linux-hardware.org/?probe=aa8a91dad1) | Oct 08, 2024 |
| Apple         | MacBookAir6,1               | [c9cda4f625](https://linux-hardware.org/?probe=c9cda4f625) | Oct 06, 2024 |
| Apple         | MacBookPro5,5               | [6c0b20bdce](https://linux-hardware.org/?probe=6c0b20bdce) | Oct 03, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6f1403e89a](https://linux-hardware.org/?probe=6f1403e89a) | Oct 02, 2024 |
| HP            | EliteBook 2530p             | [d75b4282e9](https://linux-hardware.org/?probe=d75b4282e9) | Oct 01, 2024 |
| HP            | EliteBook 2530p             | [52857f0cec](https://linux-hardware.org/?probe=52857f0cec) | Sep 30, 2024 |
| Lenovo        | ThinkPad A485 20MU000DMX    | [c79a269779](https://linux-hardware.org/?probe=c79a269779) | Sep 29, 2024 |
| Lenovo        | ThinkPad X230 2325TWT       | [617daeda56](https://linux-hardware.org/?probe=617daeda56) | Sep 28, 2024 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [4d2337d8a2](https://linux-hardware.org/?probe=4d2337d8a2) | Sep 28, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [eb128112b1](https://linux-hardware.org/?probe=eb128112b1) | Sep 27, 2024 |
| Apple         | MacBookPro8,1               | [93e19e497d](https://linux-hardware.org/?probe=93e19e497d) | Sep 27, 2024 |
| Dell          | Latitude 7400               | [a8fc62b85e](https://linux-hardware.org/?probe=a8fc62b85e) | Sep 26, 2024 |
| Dell          | Precision 3551              | [c201795f7c](https://linux-hardware.org/?probe=c201795f7c) | Sep 18, 2024 |
| Acer          | Aspire A515-51G             | [1c1ac8a360](https://linux-hardware.org/?probe=1c1ac8a360) | Sep 18, 2024 |
| HP            | Victus by Gaming Laptop ... | [1b4a966af7](https://linux-hardware.org/?probe=1b4a966af7) | Sep 16, 2024 |
| Lenovo        | ThinkPad P16 Gen 2 21FA0... | [96c93da8c8](https://linux-hardware.org/?probe=96c93da8c8) | Sep 16, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [28e8212852](https://linux-hardware.org/?probe=28e8212852) | Sep 16, 2024 |
| HP            | EliteBook 840 G5            | [94be8e0e90](https://linux-hardware.org/?probe=94be8e0e90) | Sep 12, 2024 |
| Lenovo        | B50-10 80QR                 | [1bada55b47](https://linux-hardware.org/?probe=1bada55b47) | Sep 12, 2024 |
| Packard Be... | EasyNote TS11HR             | [c1d8cfb914](https://linux-hardware.org/?probe=c1d8cfb914) | Sep 11, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [bb1ea1554d](https://linux-hardware.org/?probe=bb1ea1554d) | Sep 10, 2024 |
| Acer          | Aspire V3-572G              | [6de946d5a9](https://linux-hardware.org/?probe=6de946d5a9) | Sep 07, 2024 |
| Cepter        | Maximus WARDON              | [545c021bf3](https://linux-hardware.org/?probe=545c021bf3) | Sep 06, 2024 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [c9474f150c](https://linux-hardware.org/?probe=c9474f150c) | Sep 03, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [7b534afcea](https://linux-hardware.org/?probe=7b534afcea) | Sep 02, 2024 |
| Toshiba       | TECRA S11                   | [4617ceeeec](https://linux-hardware.org/?probe=4617ceeeec) | Aug 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0984d35721](https://linux-hardware.org/?probe=0984d35721) | Aug 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cb37d72216](https://linux-hardware.org/?probe=cb37d72216) | Aug 28, 2024 |
| HP            | Laptop 14-dg0xxx            | [ef85d2699e](https://linux-hardware.org/?probe=ef85d2699e) | Aug 19, 2024 |
| Samsung       | R540/R580/R780/SA41/E452... | [d033b522c3](https://linux-hardware.org/?probe=d033b522c3) | Aug 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [684eeb17ab](https://linux-hardware.org/?probe=684eeb17ab) | Aug 14, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [248f8ee89d](https://linux-hardware.org/?probe=248f8ee89d) | Aug 13, 2024 |
| ASUSTek       | T100TA                      | [087ac815ec](https://linux-hardware.org/?probe=087ac815ec) | Aug 06, 2024 |
| Lenovo        | ThinkPad W510 431967G       | [58cb012163](https://linux-hardware.org/?probe=58cb012163) | Aug 06, 2024 |
| Acer          | Swift SFX16-61G             | [2359a79645](https://linux-hardware.org/?probe=2359a79645) | Aug 03, 2024 |
| Lenovo        | ThinkPad P52 20M9001NMX     | [a06c67958c](https://linux-hardware.org/?probe=a06c67958c) | Aug 01, 2024 |
| Lenovo        | ThinkPad T61p 8889AU5       | [e06a1aad9c](https://linux-hardware.org/?probe=e06a1aad9c) | Aug 01, 2024 |
| Dell          | Latitude 7330 Rugged Ext... | [1c0578984c](https://linux-hardware.org/?probe=1c0578984c) | Jul 31, 2024 |
| Packard Be... | EasyNote TS11HR             | [a96ddb3094](https://linux-hardware.org/?probe=a96ddb3094) | Jul 27, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [0219498bb7](https://linux-hardware.org/?probe=0219498bb7) | Jul 26, 2024 |
| ASUSTek       | UX490UA                     | [958c573822](https://linux-hardware.org/?probe=958c573822) | Jul 22, 2024 |
| Acer          | Aspire A315-41              | [288f9de47d](https://linux-hardware.org/?probe=288f9de47d) | Jul 21, 2024 |
| Apple         | MacBookAir6,2               | [fdda23379d](https://linux-hardware.org/?probe=fdda23379d) | Jul 20, 2024 |
| Fujitsu       | LIFEBOOK U772               | [8ba4824fc8](https://linux-hardware.org/?probe=8ba4824fc8) | Jul 19, 2024 |
| Fujitsu       | LIFEBOOK E733               | [6d6b42a6fe](https://linux-hardware.org/?probe=6d6b42a6fe) | Jul 19, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | [62354fe581](https://linux-hardware.org/?probe=62354fe581) | Jul 19, 2024 |
| Apple         | MacBookPro14,1              | [bc496941a2](https://linux-hardware.org/?probe=bc496941a2) | Jul 17, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [1b9fd5da77](https://linux-hardware.org/?probe=1b9fd5da77) | Jul 16, 2024 |
| Acer          | Aspire A315-41              | [0c819b933c](https://linux-hardware.org/?probe=0c819b933c) | Jul 11, 2024 |
| HUAWEI        | NBD-WXX9                    | [fbe8c9cc90](https://linux-hardware.org/?probe=fbe8c9cc90) | Jul 09, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [fdb5740619](https://linux-hardware.org/?probe=fdb5740619) | Jul 08, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [344a3a1381](https://linux-hardware.org/?probe=344a3a1381) | Jul 08, 2024 |
| Toshiba       | Satellite L500              | [d41f6ae73f](https://linux-hardware.org/?probe=d41f6ae73f) | Jul 07, 2024 |
| ASUSTek       | E502SA                      | [2f4823de9d](https://linux-hardware.org/?probe=2f4823de9d) | Jul 03, 2024 |
| ASUSTek       | E502SA                      | [3ee55aa7b7](https://linux-hardware.org/?probe=3ee55aa7b7) | Jul 01, 2024 |
| HP            | EliteBook 840 G3            | [aa123bef20](https://linux-hardware.org/?probe=aa123bef20) | Jun 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bed62e6b3c](https://linux-hardware.org/?probe=bed62e6b3c) | Jun 26, 2024 |
| Acer          | Aspire A315-41              | [ea31d636fb](https://linux-hardware.org/?probe=ea31d636fb) | Jun 21, 2024 |
| Acer          | Predator PT316-51s          | [c6dff2e738](https://linux-hardware.org/?probe=c6dff2e738) | Jun 20, 2024 |
| Fujitsu Si... | AMILO Li 1818               | [3b06204330](https://linux-hardware.org/?probe=3b06204330) | Jun 19, 2024 |
| Fujitsu Si... | AMILO Li 1818               | [7a2e0e42b4](https://linux-hardware.org/?probe=7a2e0e42b4) | Jun 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [49d80d594c](https://linux-hardware.org/?probe=49d80d594c) | Jun 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [14aecfba4d](https://linux-hardware.org/?probe=14aecfba4d) | Jun 16, 2024 |
| Apple         | MacBookPro12,1              | [62324bdfab](https://linux-hardware.org/?probe=62324bdfab) | Jun 12, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [0e4d5ebe28](https://linux-hardware.org/?probe=0e4d5ebe28) | Jun 11, 2024 |
| Lenovo        | ThinkPad X201 3680F7G       | [cd02d8af64](https://linux-hardware.org/?probe=cd02d8af64) | Jun 11, 2024 |
| HP            | EliteBook 840 G5            | [8d3c1d6921](https://linux-hardware.org/?probe=8d3c1d6921) | Jun 11, 2024 |
| HP            | Compaq 6735s                | [eddd6a81e1](https://linux-hardware.org/?probe=eddd6a81e1) | Jun 09, 2024 |
| Lenovo        | ThinkPad T480 20L6S68T2W    | [9c7b8ae370](https://linux-hardware.org/?probe=9c7b8ae370) | Jun 06, 2024 |
| Acer          | Aspire A315-24P             | [975ee64b42](https://linux-hardware.org/?probe=975ee64b42) | Jun 05, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [5e62fb480d](https://linux-hardware.org/?probe=5e62fb480d) | Jun 04, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | [91837aebea](https://linux-hardware.org/?probe=91837aebea) | Jun 03, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [93ed456d67](https://linux-hardware.org/?probe=93ed456d67) | Jun 02, 2024 |
| Apple         | MacBookPro5,5               | [66d630c0a5](https://linux-hardware.org/?probe=66d630c0a5) | May 29, 2024 |
| System76      | Oryx Pro                    | [f55f9f2e45](https://linux-hardware.org/?probe=f55f9f2e45) | May 29, 2024 |
| HP            | 250 G6 Notebook PC          | [26c0ea4975](https://linux-hardware.org/?probe=26c0ea4975) | May 28, 2024 |
| HP            | 250 G6 Notebook PC          | [531a0ed407](https://linux-hardware.org/?probe=531a0ed407) | May 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [95c55a6647](https://linux-hardware.org/?probe=95c55a6647) | May 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [76eede6737](https://linux-hardware.org/?probe=76eede6737) | May 26, 2024 |
| HP            | Laptop 15-gw0xxx            | [faf7f3c294](https://linux-hardware.org/?probe=faf7f3c294) | May 20, 2024 |
| Dell          | XPS 13 9360                 | [81cce5b7bc](https://linux-hardware.org/?probe=81cce5b7bc) | May 14, 2024 |
| MSI           | Alpha 17 C7VF               | [dbff416a1d](https://linux-hardware.org/?probe=dbff416a1d) | May 13, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [d4d583a573](https://linux-hardware.org/?probe=d4d583a573) | May 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C70... | [701d936a1c](https://linux-hardware.org/?probe=701d936a1c) | May 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C70... | [6d05bc6b3d](https://linux-hardware.org/?probe=6d05bc6b3d) | May 07, 2024 |
| Dell          | XPS 13 9310                 | [868dd4d0bd](https://linux-hardware.org/?probe=868dd4d0bd) | May 03, 2024 |
| Gigabyte      | P2542                       | [1520cc00e6](https://linux-hardware.org/?probe=1520cc00e6) | May 01, 2024 |
| Acer          | Aspire E5-573               | [1060cb82e8](https://linux-hardware.org/?probe=1060cb82e8) | May 01, 2024 |
| Dell          | Latitude 5490               | [0b0c0eb973](https://linux-hardware.org/?probe=0b0c0eb973) | Apr 29, 2024 |
| Dell          | Inspiron 1011               | [3952627b7f](https://linux-hardware.org/?probe=3952627b7f) | Apr 29, 2024 |
| Valve         | Jupiter                     | [2b383bd91e](https://linux-hardware.org/?probe=2b383bd91e) | Apr 27, 2024 |
| ASUSTek       | K53BY                       | [6f6c4b9d68](https://linux-hardware.org/?probe=6f6c4b9d68) | Apr 26, 2024 |
| HP            | ProBook 450 G0              | [5945f4d2d5](https://linux-hardware.org/?probe=5945f4d2d5) | Apr 26, 2024 |
| HP            | ProBook 450 G0              | [e161f58e8e](https://linux-hardware.org/?probe=e161f58e8e) | Apr 19, 2024 |
| Packard Be... | EasyNote TE69KB             | [ae940fd7b0](https://linux-hardware.org/?probe=ae940fd7b0) | Apr 18, 2024 |
| Packard Be... | EasyNote TE69KB             | [4d615a62ea](https://linux-hardware.org/?probe=4d615a62ea) | Apr 18, 2024 |
| HP            | EliteBook 840 G1            | [a810237e8f](https://linux-hardware.org/?probe=a810237e8f) | Apr 16, 2024 |
| ASUSTek       | UX305CA                     | [e25d8c8e00](https://linux-hardware.org/?probe=e25d8c8e00) | Apr 16, 2024 |
| HP            | EliteBook 640 14 inch G9... | [20fe73c7f9](https://linux-hardware.org/?probe=20fe73c7f9) | Apr 11, 2024 |
| ASUSTek       | N751JK                      | [1d678d0a58](https://linux-hardware.org/?probe=1d678d0a58) | Apr 09, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [d2ba76970a](https://linux-hardware.org/?probe=d2ba76970a) | Apr 04, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [16c1d7aa41](https://linux-hardware.org/?probe=16c1d7aa41) | Apr 04, 2024 |
| Acer          | Aspire 3000                 | [1d2fad06c8](https://linux-hardware.org/?probe=1d2fad06c8) | Apr 02, 2024 |
| Fujitsu       | LIFEBOOK E746               | [0eda4797d3](https://linux-hardware.org/?probe=0eda4797d3) | Apr 01, 2024 |
| HP            | EliteBook 850 G6            | [eb4d7e2521](https://linux-hardware.org/?probe=eb4d7e2521) | Apr 01, 2024 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [3cd31b8ad2](https://linux-hardware.org/?probe=3cd31b8ad2) | Mar 31, 2024 |
| HP            | EliteBook 840 G4            | [b4724cc6b0](https://linux-hardware.org/?probe=b4724cc6b0) | Mar 31, 2024 |
| HP            | Compaq 8510p                | [c57e175a01](https://linux-hardware.org/?probe=c57e175a01) | Mar 29, 2024 |
| Dell          | Latitude E7440              | [8046c24f21](https://linux-hardware.org/?probe=8046c24f21) | Mar 27, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e5e4d98f62](https://linux-hardware.org/?probe=e5e4d98f62) | Mar 25, 2024 |
| Lenovo        | ThinkPad T530 24297XG       | [4935048c5f](https://linux-hardware.org/?probe=4935048c5f) | Mar 25, 2024 |
| Lenovo        | ThinkPad T410 253725G       | [33a07105de](https://linux-hardware.org/?probe=33a07105de) | Mar 24, 2024 |
| Fujitsu       | LIFEBOOK E734               | [1da01e0e94](https://linux-hardware.org/?probe=1da01e0e94) | Mar 24, 2024 |
| HP            | Laptop 14s-fq0xxx           | [5f50d8654a](https://linux-hardware.org/?probe=5f50d8654a) | Mar 23, 2024 |
| Lenovo        | ThinkPad X395 20NMS13801    | [bf71f2099b](https://linux-hardware.org/?probe=bf71f2099b) | Mar 21, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | [b912e786a3](https://linux-hardware.org/?probe=b912e786a3) | Mar 20, 2024 |
| HP            | Pavilion 15                 | [6901a5764b](https://linux-hardware.org/?probe=6901a5764b) | Mar 20, 2024 |
| Apple         | MacBookPro14,1              | [621ae3ca60](https://linux-hardware.org/?probe=621ae3ca60) | Mar 16, 2024 |
| Lenovo        | Yoga 700-11ISK 80QE         | [a0a622a966](https://linux-hardware.org/?probe=a0a622a966) | Mar 14, 2024 |
| eMachines     | E727                        | [af56e195f8](https://linux-hardware.org/?probe=af56e195f8) | Mar 13, 2024 |
| ASUSTek       | UX31E                       | [94fc346288](https://linux-hardware.org/?probe=94fc346288) | Mar 10, 2024 |
| HONOR         | BOHK-WAX9X                  | [d7892c8c29](https://linux-hardware.org/?probe=d7892c8c29) | Mar 10, 2024 |
| Lenovo        | ThinkPad T495 20NKS1RQ01    | [5c00b6631a](https://linux-hardware.org/?probe=5c00b6631a) | Mar 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1dda71290f](https://linux-hardware.org/?probe=1dda71290f) | Mar 08, 2024 |
| ASUSTek       | X555LJ                      | [9e67d96b3f](https://linux-hardware.org/?probe=9e67d96b3f) | Mar 04, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [792fce7b20](https://linux-hardware.org/?probe=792fce7b20) | Feb 29, 2024 |
| Unknown       | WY133A                      | [ac6776d5fc](https://linux-hardware.org/?probe=ac6776d5fc) | Feb 29, 2024 |
| ASUSTek       | T100HAN                     | [1dcbcd018e](https://linux-hardware.org/?probe=1dcbcd018e) | Feb 26, 2024 |
| Acer          | Extensa 215-55              | [14c23eee9c](https://linux-hardware.org/?probe=14c23eee9c) | Feb 26, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [6731541710](https://linux-hardware.org/?probe=6731541710) | Feb 24, 2024 |
| Valve         | Galileo                     | [222802e961](https://linux-hardware.org/?probe=222802e961) | Feb 24, 2024 |
| Apple         | MacBookAir7,2               | [2afbc3922a](https://linux-hardware.org/?probe=2afbc3922a) | Feb 23, 2024 |
| Apple         | MacBookPro11,3              | [88448eac7a](https://linux-hardware.org/?probe=88448eac7a) | Feb 23, 2024 |
| Apple         | MacBookPro13,1              | [cc881016ff](https://linux-hardware.org/?probe=cc881016ff) | Feb 22, 2024 |
| Apple         | MacBookPro8,1               | [f8d09630be](https://linux-hardware.org/?probe=f8d09630be) | Feb 20, 2024 |
| Apple         | MacBookPro8,1               | [5eb44e20c3](https://linux-hardware.org/?probe=5eb44e20c3) | Feb 20, 2024 |
| Apple         | MacBookPro13,1              | [6436d22d55](https://linux-hardware.org/?probe=6436d22d55) | Feb 19, 2024 |
| Acer          | Extensa 215-55              | [36eaeb4ef3](https://linux-hardware.org/?probe=36eaeb4ef3) | Feb 16, 2024 |
| HP            | EliteBook 840 G6            | [b3ffbe3673](https://linux-hardware.org/?probe=b3ffbe3673) | Feb 14, 2024 |
| Acer          | Extensa 215-55              | [84309010d3](https://linux-hardware.org/?probe=84309010d3) | Feb 14, 2024 |
| HP            | EliteBook 850 G3            | [35174dcd36](https://linux-hardware.org/?probe=35174dcd36) | Feb 12, 2024 |
| Lenovo        | ThinkPad E495 20NE000JMX    | [efcec1dc1e](https://linux-hardware.org/?probe=efcec1dc1e) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a22b67cf36](https://linux-hardware.org/?probe=a22b67cf36) | Feb 11, 2024 |
| HP            | Pavilion g7                 | [fb9d5315c4](https://linux-hardware.org/?probe=fb9d5315c4) | Feb 11, 2024 |
| HP            | Pavilion g7                 | [d93edf4e50](https://linux-hardware.org/?probe=d93edf4e50) | Feb 11, 2024 |
| HP            | Pavilion Notebook           | [7da16fe9d7](https://linux-hardware.org/?probe=7da16fe9d7) | Feb 09, 2024 |
| Toshiba       | Satellite L40               | [b798661cd0](https://linux-hardware.org/?probe=b798661cd0) | Feb 09, 2024 |
| Dell          | Latitude 5440               | [f1a8f212e3](https://linux-hardware.org/?probe=f1a8f212e3) | Feb 08, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [55b8176dfd](https://linux-hardware.org/?probe=55b8176dfd) | Feb 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2bdeaafbb9](https://linux-hardware.org/?probe=2bdeaafbb9) | Feb 06, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a654b497ec](https://linux-hardware.org/?probe=a654b497ec) | Feb 05, 2024 |
| Lenovo        | ThinkPad X13 Gen 2a 20XJ... | [d9db0185ec](https://linux-hardware.org/?probe=d9db0185ec) | Feb 05, 2024 |
| HP            | Pavilion 15                 | [066b0cf774](https://linux-hardware.org/?probe=066b0cf774) | Feb 05, 2024 |
| Panasonic     | CF-54-2                     | [7758f322a6](https://linux-hardware.org/?probe=7758f322a6) | Feb 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [02d7b129fc](https://linux-hardware.org/?probe=02d7b129fc) | Jan 31, 2024 |
| Fujitsu       | LIFEBOOK E734               | [7b3a60ae2d](https://linux-hardware.org/?probe=7b3a60ae2d) | Jan 30, 2024 |
| Lenovo        | ThinkPad P52 20M9001MMX     | [0270f75e12](https://linux-hardware.org/?probe=0270f75e12) | Jan 29, 2024 |
| Insyde        | CherryTrail                 | [a0eeda1d5a](https://linux-hardware.org/?probe=a0eeda1d5a) | Jan 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [54f3192aa0](https://linux-hardware.org/?probe=54f3192aa0) | Jan 25, 2024 |
| ASUSTek       | X541UV                      | [7df0d2b4af](https://linux-hardware.org/?probe=7df0d2b4af) | Jan 24, 2024 |
| Lenovo        | ThinkPad T530 24297XG       | [9b6f11b3a9](https://linux-hardware.org/?probe=9b6f11b3a9) | Jan 24, 2024 |
| ASUSTek       | T100HAN                     | [66829eb63f](https://linux-hardware.org/?probe=66829eb63f) | Jan 23, 2024 |
| Lenovo        | ThinkPad T480s 20L8S0SA0... | [5f60d47122](https://linux-hardware.org/?probe=5f60d47122) | Jan 21, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b5e7e0d38](https://linux-hardware.org/?probe=1b5e7e0d38) | Jan 20, 2024 |
| HP            | ProBook 430 G3              | [ed36d7cd8f](https://linux-hardware.org/?probe=ed36d7cd8f) | Jan 20, 2024 |
| Lenovo        | G50-30 80G0                 | [469e8ffc49](https://linux-hardware.org/?probe=469e8ffc49) | Jan 16, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [6c360c2400](https://linux-hardware.org/?probe=6c360c2400) | Jan 15, 2024 |
| Acer          | Aspire V5-552G              | [88a4824eac](https://linux-hardware.org/?probe=88a4824eac) | Jan 15, 2024 |
| Acer          | Aspire V5-552G              | [9b2eb6e626](https://linux-hardware.org/?probe=9b2eb6e626) | Jan 15, 2024 |
| HP            | ProBook 445 14 inch G10 ... | [cc219f9e8e](https://linux-hardware.org/?probe=cc219f9e8e) | Jan 13, 2024 |
| HP            | ProBook 445 14 inch G10 ... | [5d10765449](https://linux-hardware.org/?probe=5d10765449) | Jan 13, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [e085204d13](https://linux-hardware.org/?probe=e085204d13) | Jan 12, 2024 |
| Lenovo        | ThinkPad T530 24297XG       | [3ca4357d99](https://linux-hardware.org/?probe=3ca4357d99) | Jan 12, 2024 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [61e9830d84](https://linux-hardware.org/?probe=61e9830d84) | Jan 12, 2024 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [c74c1758a4](https://linux-hardware.org/?probe=c74c1758a4) | Jan 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [a127ed2c69](https://linux-hardware.org/?probe=a127ed2c69) | Jan 11, 2024 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [9663b055e8](https://linux-hardware.org/?probe=9663b055e8) | Jan 10, 2024 |
| HP            | EliteBook 745 G6            | [e7c4951a31](https://linux-hardware.org/?probe=e7c4951a31) | Jan 10, 2024 |
| HP            | EliteBook 645 14 inch G9... | [f56d1e88ba](https://linux-hardware.org/?probe=f56d1e88ba) | Jan 07, 2024 |
| HP            | Pavilion 13 x360 PC         | [52fea1e890](https://linux-hardware.org/?probe=52fea1e890) | Jan 06, 2024 |
| Apple         | MacBookPro8,1               | [a620a3be8d](https://linux-hardware.org/?probe=a620a3be8d) | Jan 06, 2024 |
| Dell          | Latitude E6440              | [4c184aed54](https://linux-hardware.org/?probe=4c184aed54) | Jan 05, 2024 |
| Apple         | MacBookPro8,1               | [1593858ec2](https://linux-hardware.org/?probe=1593858ec2) | Jan 04, 2024 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [23c30ee5a3](https://linux-hardware.org/?probe=23c30ee5a3) | Jan 03, 2024 |
| ASUSTek       | VivoBook E14 E402YA_R417... | [47112e4c46](https://linux-hardware.org/?probe=47112e4c46) | Dec 31, 2023 |
| Dell          | Latitude E6440              | [f4ba63ff52](https://linux-hardware.org/?probe=f4ba63ff52) | Dec 30, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [f3af16ad5d](https://linux-hardware.org/?probe=f3af16ad5d) | Dec 29, 2023 |
| Lenovo        | ThinkPad E480 20KN0065MX    | [14018f1aec](https://linux-hardware.org/?probe=14018f1aec) | Dec 27, 2023 |
| HP            | Laptop 15-db1xxx            | [692cf22259](https://linux-hardware.org/?probe=692cf22259) | Dec 25, 2023 |
| Lenovo        | ThinkPad X270 20HN005NMX    | [aeb2dccb91](https://linux-hardware.org/?probe=aeb2dccb91) | Dec 25, 2023 |
| Lenovo        | ThinkPad X280 20KES63G00    | [a5688cc794](https://linux-hardware.org/?probe=a5688cc794) | Dec 24, 2023 |
| Apple         | MacBookPro8,1               | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| Acer          | Aspire E5-573               | [91c6527140](https://linux-hardware.org/?probe=91c6527140) | Dec 19, 2023 |
| Fujitsu       | LIFEBOOK U728               | [381f2ea08d](https://linux-hardware.org/?probe=381f2ea08d) | Dec 16, 2023 |
| Lenovo        | B50-10 80QR                 | [f44fe4ce19](https://linux-hardware.org/?probe=f44fe4ce19) | Dec 11, 2023 |
| Samsung       | RF511/RF411/RF711           | [59846b1d85](https://linux-hardware.org/?probe=59846b1d85) | Dec 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [96a56fd534](https://linux-hardware.org/?probe=96a56fd534) | Dec 09, 2023 |
| Acer          | Aspire E5-573               | [c23042b293](https://linux-hardware.org/?probe=c23042b293) | Dec 08, 2023 |
| Lenovo        | ThinkPad X270 20HN005NMX    | [23d9249c5e](https://linux-hardware.org/?probe=23d9249c5e) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2d483d736b](https://linux-hardware.org/?probe=2d483d736b) | Dec 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [70394fdace](https://linux-hardware.org/?probe=70394fdace) | Dec 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [9e1d0f5fdc](https://linux-hardware.org/?probe=9e1d0f5fdc) | Dec 03, 2023 |
| Acer          | Aspire E5-573               | [c265401f64](https://linux-hardware.org/?probe=c265401f64) | Dec 03, 2023 |
| HP            | Pavilion dv7                | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | [7922226a1c](https://linux-hardware.org/?probe=7922226a1c) | Dec 02, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | [cb2b5c10a7](https://linux-hardware.org/?probe=cb2b5c10a7) | Dec 02, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [d923b4bdf8](https://linux-hardware.org/?probe=d923b4bdf8) | Dec 02, 2023 |
| HP            | Laptop 14-dk0xxx            | [eae202e5f1](https://linux-hardware.org/?probe=eae202e5f1) | Nov 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | [0769357573](https://linux-hardware.org/?probe=0769357573) | Nov 27, 2023 |
| Acer          | Swift SFE16-43              | [849f368635](https://linux-hardware.org/?probe=849f368635) | Nov 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [956dbda516](https://linux-hardware.org/?probe=956dbda516) | Nov 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [5289268737](https://linux-hardware.org/?probe=5289268737) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [bd428a8490](https://linux-hardware.org/?probe=bd428a8490) | Nov 22, 2023 |
| Fujitsu       | LIFEBOOK S710               | [a0453d2f05](https://linux-hardware.org/?probe=a0453d2f05) | Nov 20, 2023 |
| Unknown       | M17                         | [1708365bec](https://linux-hardware.org/?probe=1708365bec) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d0549c695d](https://linux-hardware.org/?probe=d0549c695d) | Nov 13, 2023 |
| HP            | Unknown                     | [c22e23b2f8](https://linux-hardware.org/?probe=c22e23b2f8) | Nov 12, 2023 |
| Dell          | Latitude E5430 non-vPro     | [518492850b](https://linux-hardware.org/?probe=518492850b) | Nov 10, 2023 |
| Lenovo        | ThinkPad T490 20N3S7AA00    | [b4fd9fd045](https://linux-hardware.org/?probe=b4fd9fd045) | Nov 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [39e2c7584e](https://linux-hardware.org/?probe=39e2c7584e) | Nov 08, 2023 |
| Fujitsu Si... | AMILO Li 1818               | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| HP            | EliteBook 840 G3            | [1bb894cf19](https://linux-hardware.org/?probe=1bb894cf19) | Nov 04, 2023 |
| MSI           | GF75 Thin 9SC               | [2aceaf7016](https://linux-hardware.org/?probe=2aceaf7016) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [2bdd27dc18](https://linux-hardware.org/?probe=2bdd27dc18) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [cb35a8d8f6](https://linux-hardware.org/?probe=cb35a8d8f6) | Oct 31, 2023 |
| ASUSTek       | X507UA                      | [c52aa98c38](https://linux-hardware.org/?probe=c52aa98c38) | Oct 31, 2023 |
| Lenovo        | ThinkPad T60 1952WUV        | [4ecf9f7f50](https://linux-hardware.org/?probe=4ecf9f7f50) | Oct 30, 2023 |
| HP            | EliteBook 8460p             | [7d6972297f](https://linux-hardware.org/?probe=7d6972297f) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ecab2bb9fe](https://linux-hardware.org/?probe=ecab2bb9fe) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [a3355c6898](https://linux-hardware.org/?probe=a3355c6898) | Oct 27, 2023 |
| Lenovo        | G580 2189                   | [18dc8e53d9](https://linux-hardware.org/?probe=18dc8e53d9) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | [0fb2b25961](https://linux-hardware.org/?probe=0fb2b25961) | Oct 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8754714bce](https://linux-hardware.org/?probe=8754714bce) | Oct 23, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| HP            | Pavilion g7                 | [11f3136e05](https://linux-hardware.org/?probe=11f3136e05) | Oct 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0504910ad7](https://linux-hardware.org/?probe=0504910ad7) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [2956823009](https://linux-hardware.org/?probe=2956823009) | Oct 14, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [d268453669](https://linux-hardware.org/?probe=d268453669) | Oct 13, 2023 |
| ASUSTek       | GR8                         | [5b509d021c](https://linux-hardware.org/?probe=5b509d021c) | Oct 13, 2023 |
| ASUSTek       | GR8                         | [e381fff6d8](https://linux-hardware.org/?probe=e381fff6d8) | Oct 13, 2023 |
| Lenovo        | ThinkPad T400 27658JG       | [3b3b7832c9](https://linux-hardware.org/?probe=3b3b7832c9) | Oct 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [afff949494](https://linux-hardware.org/?probe=afff949494) | Oct 08, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9dc2fd3247](https://linux-hardware.org/?probe=9dc2fd3247) | Oct 06, 2023 |
| Apple         | MacBookPro16,3              | [9ca487f2cf](https://linux-hardware.org/?probe=9ca487f2cf) | Oct 02, 2023 |
| HP            | Pavilion 11 x360 PC         | [b3eb082c5e](https://linux-hardware.org/?probe=b3eb082c5e) | Oct 01, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2cf86f7f12](https://linux-hardware.org/?probe=2cf86f7f12) | Sep 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9a24a19f6e](https://linux-hardware.org/?probe=9a24a19f6e) | Sep 25, 2023 |
| Acer          | Aspire 7730G                | [e21c91c34c](https://linux-hardware.org/?probe=e21c91c34c) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb276947f2](https://linux-hardware.org/?probe=eb276947f2) | Sep 23, 2023 |
| HP            | EliteBook 8570p             | [ca346761d3](https://linux-hardware.org/?probe=ca346761d3) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e75a2a8b71](https://linux-hardware.org/?probe=e75a2a8b71) | Sep 22, 2023 |
| HP            | EliteBook 840 G3            | [b6379ef77c](https://linux-hardware.org/?probe=b6379ef77c) | Sep 22, 2023 |
| Acer          | Aspire 5741G                | [b79d8aec76](https://linux-hardware.org/?probe=b79d8aec76) | Sep 21, 2023 |
| Lenovo        | ThinkPad W520 4284W1D       | [c634509519](https://linux-hardware.org/?probe=c634509519) | Sep 18, 2023 |
| ASUSTek       | N73SM                       | [d4ce8f336d](https://linux-hardware.org/?probe=d4ce8f336d) | Sep 17, 2023 |
| Toshiba       | QOSMIO X770                 | [84fc7ea45e](https://linux-hardware.org/?probe=84fc7ea45e) | Sep 17, 2023 |
| Fujitsu       | LIFEBOOK E733               | [0613157456](https://linux-hardware.org/?probe=0613157456) | Sep 15, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [3b71101d09](https://linux-hardware.org/?probe=3b71101d09) | Sep 14, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| HP            | Pavilion Laptop 14-bf1xx    | [fe3ed738a1](https://linux-hardware.org/?probe=fe3ed738a1) | Sep 11, 2023 |
| Apple         | MacBookPro8,2               | [f23bb97453](https://linux-hardware.org/?probe=f23bb97453) | Sep 11, 2023 |
| Acer          | Aspire V5-472               | [198d33eff6](https://linux-hardware.org/?probe=198d33eff6) | Sep 09, 2023 |
| Lenovo        | ThinkPad P43s 20RH001UMX    | [0fdff74089](https://linux-hardware.org/?probe=0fdff74089) | Sep 07, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | [cb8de94658](https://linux-hardware.org/?probe=cb8de94658) | Sep 05, 2023 |
| Apple         | MacBookPro11,1              | [d8efe50ca5](https://linux-hardware.org/?probe=d8efe50ca5) | Sep 04, 2023 |
| Fujitsu       | LIFEBOOK E734               | [1b89968327](https://linux-hardware.org/?probe=1b89968327) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [0a55847393](https://linux-hardware.org/?probe=0a55847393) | Aug 30, 2023 |
| ASUSTek       | X541UAK                     | [c75a044974](https://linux-hardware.org/?probe=c75a044974) | Aug 30, 2023 |
| Lenovo        | Y50-70 20378                | [5a20b8cd20](https://linux-hardware.org/?probe=5a20b8cd20) | Aug 29, 2023 |
| HP            | 630                         | [4a94779668](https://linux-hardware.org/?probe=4a94779668) | Aug 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H5C... | [96b559d5d6](https://linux-hardware.org/?probe=96b559d5d6) | Aug 27, 2023 |
| ASUSTek       | TP300LA                     | [7588e955e3](https://linux-hardware.org/?probe=7588e955e3) | Aug 27, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [9b94ab3887](https://linux-hardware.org/?probe=9b94ab3887) | Aug 27, 2023 |
| HP            | EliteBook 840 G3            | [d3c6faac81](https://linux-hardware.org/?probe=d3c6faac81) | Aug 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [1a86753f1c](https://linux-hardware.org/?probe=1a86753f1c) | Aug 20, 2023 |
| ASUSTek       | X541UAK                     | [048ca1ce02](https://linux-hardware.org/?probe=048ca1ce02) | Aug 20, 2023 |
| Valve         | Jupiter                     | [0a6ed7bae4](https://linux-hardware.org/?probe=0a6ed7bae4) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | [76dda9cde6](https://linux-hardware.org/?probe=76dda9cde6) | Aug 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [da5582d4bf](https://linux-hardware.org/?probe=da5582d4bf) | Aug 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [63f2bc3a80](https://linux-hardware.org/?probe=63f2bc3a80) | Aug 16, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MN    | [c853746c1f](https://linux-hardware.org/?probe=c853746c1f) | Aug 16, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MN    | [a460ba57d2](https://linux-hardware.org/?probe=a460ba57d2) | Aug 16, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [6cbef2a38d](https://linux-hardware.org/?probe=6cbef2a38d) | Aug 13, 2023 |
| Dell          | Latitude E6330              | [b3081e041e](https://linux-hardware.org/?probe=b3081e041e) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2980681052](https://linux-hardware.org/?probe=2980681052) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8b84e48f4c](https://linux-hardware.org/?probe=8b84e48f4c) | Aug 04, 2023 |
| Lenovo        | Yoga 2 13 20344             | [767b492aa4](https://linux-hardware.org/?probe=767b492aa4) | Aug 03, 2023 |
| Lenovo        | Yoga 2 13 20344             | [47ca08e0d1](https://linux-hardware.org/?probe=47ca08e0d1) | Aug 03, 2023 |
| HP            | Unknown                     | [f7ffb3c085](https://linux-hardware.org/?probe=f7ffb3c085) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| Lenovo        | V145-15AST 81MT             | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| Lenovo        | ThinkPad T520 4243JA1       | [410cebaba3](https://linux-hardware.org/?probe=410cebaba3) | Jul 28, 2023 |
| Lenovo        | ThinkPad W500 4063WPV       | [d750cddcb0](https://linux-hardware.org/?probe=d750cddcb0) | Jul 26, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [6750fae080](https://linux-hardware.org/?probe=6750fae080) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [a61cd014ac](https://linux-hardware.org/?probe=a61cd014ac) | Jul 23, 2023 |
| HP            | EliteBook 6930p (NG813UP... | [4c6736fd14](https://linux-hardware.org/?probe=4c6736fd14) | Jul 17, 2023 |
| HP            | EliteBook 6930p (NG813UP... | [33b2f9227b](https://linux-hardware.org/?probe=33b2f9227b) | Jul 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e037f08e1](https://linux-hardware.org/?probe=9e037f08e1) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [b592c5b551](https://linux-hardware.org/?probe=b592c5b551) | Jul 15, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [151cc29e31](https://linux-hardware.org/?probe=151cc29e31) | Jul 12, 2023 |
| ASUSTek       | TP300LA                     | [7821a5e0e6](https://linux-hardware.org/?probe=7821a5e0e6) | Jul 05, 2023 |
| HP            | ProBook 650 G1              | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [728d4edecd](https://linux-hardware.org/?probe=728d4edecd) | Jul 01, 2023 |
| HP            | ProBook 650 G1              | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| HP            | 250 G3                      | [90647a4b33](https://linux-hardware.org/?probe=90647a4b33) | Jun 28, 2023 |
| Apple         | MacBookPro8,2               | [3e5baaaa01](https://linux-hardware.org/?probe=3e5baaaa01) | Jun 27, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [0defa5c92d](https://linux-hardware.org/?probe=0defa5c92d) | Jun 27, 2023 |
| Acer          | Nitro AN515-55              | [2153f80362](https://linux-hardware.org/?probe=2153f80362) | Jun 25, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4429a0f659](https://linux-hardware.org/?probe=4429a0f659) | Jun 23, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [017f0476b0](https://linux-hardware.org/?probe=017f0476b0) | Jun 21, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [4af402b7c9](https://linux-hardware.org/?probe=4af402b7c9) | Jun 21, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| Toshiba       | Satellite C850-1DV          | [eb574aab3b](https://linux-hardware.org/?probe=eb574aab3b) | Jun 19, 2023 |
| ASUSTek       | UX530UQ                     | [c952ec8390](https://linux-hardware.org/?probe=c952ec8390) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK A514               | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| Lenovo        | Yoga 2 13 20344             | [eab5787d6a](https://linux-hardware.org/?probe=eab5787d6a) | Jun 11, 2023 |
| ASUSTek       | UX530UQ                     | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| Gigabyte      | P2542                       | [12a2415432](https://linux-hardware.org/?probe=12a2415432) | Jun 08, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [281be42f34](https://linux-hardware.org/?probe=281be42f34) | Jun 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f9b3588ff3](https://linux-hardware.org/?probe=f9b3588ff3) | Jun 07, 2023 |
| Lenovo        | ThinkPad T495 20NKS10K00    | [f205c52b8f](https://linux-hardware.org/?probe=f205c52b8f) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [16aa33fdfe](https://linux-hardware.org/?probe=16aa33fdfe) | Jun 06, 2023 |
| HP            | Laptop 17-ak0xx             | [a0430d6f0c](https://linux-hardware.org/?probe=a0430d6f0c) | Jun 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [9a1c9022af](https://linux-hardware.org/?probe=9a1c9022af) | Jun 05, 2023 |
| HP            | EliteBook 840 G1            | [4840dda2e3](https://linux-hardware.org/?probe=4840dda2e3) | Jun 04, 2023 |
| HP            | EliteBook 8440p             | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| Gigabyte      | P2542                       | [b1064cae7a](https://linux-hardware.org/?probe=b1064cae7a) | May 30, 2023 |
| Gigabyte      | P2542                       | [7cded000f2](https://linux-hardware.org/?probe=7cded000f2) | May 30, 2023 |
| Toshiba       | Satellite L500              | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cb238efd5e](https://linux-hardware.org/?probe=cb238efd5e) | May 27, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [a81e627367](https://linux-hardware.org/?probe=a81e627367) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [0197aaf79a](https://linux-hardware.org/?probe=0197aaf79a) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [bb39617225](https://linux-hardware.org/?probe=bb39617225) | May 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [f811501691](https://linux-hardware.org/?probe=f811501691) | May 18, 2023 |
| HP            | EliteBook 745 G4            | [7c6154717b](https://linux-hardware.org/?probe=7c6154717b) | May 18, 2023 |
| HP            | Stream Notebook PC 14       | [835c46e8e2](https://linux-hardware.org/?probe=835c46e8e2) | May 18, 2023 |
| ASUSTek       | K73SV                       | [d1d5700b2c](https://linux-hardware.org/?probe=d1d5700b2c) | May 18, 2023 |
| Lenovo        | ThinkPad T400 276522G       | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| ASUSTek       | G750JM                      | [2a93ec6ed8](https://linux-hardware.org/?probe=2a93ec6ed8) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f5ef3c16c5](https://linux-hardware.org/?probe=f5ef3c16c5) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| HP            | EliteBook 2560p             | [2a50b288f8](https://linux-hardware.org/?probe=2a50b288f8) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23259J6       | [dede8cf401](https://linux-hardware.org/?probe=dede8cf401) | May 14, 2023 |
| Lenovo        | ThinkPad X230 23259J6       | [9fd366eba6](https://linux-hardware.org/?probe=9fd366eba6) | May 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| HP            | 655                         | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Lenovo        | ThinkPad Edge E320 12988... | [5d3d3fb42e](https://linux-hardware.org/?probe=5d3d3fb42e) | May 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Latitude 7370               | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [1e7a947d41](https://linux-hardware.org/?probe=1e7a947d41) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [9a7a15dae3](https://linux-hardware.org/?probe=9a7a15dae3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [754fc44526](https://linux-hardware.org/?probe=754fc44526) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [379a1710e5](https://linux-hardware.org/?probe=379a1710e5) | Apr 25, 2023 |
| Dell          | Latitude 5420               | [8c1a7992c0](https://linux-hardware.org/?probe=8c1a7992c0) | Apr 25, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| Dell          | Latitude E5470              | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| HP            | EliteBook 830 G5            | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3ea28c33c9](https://linux-hardware.org/?probe=3ea28c33c9) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [6c711c5197](https://linux-hardware.org/?probe=6c711c5197) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9ce743560b](https://linux-hardware.org/?probe=9ce743560b) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [91da873411](https://linux-hardware.org/?probe=91da873411) | Apr 14, 2023 |
| Dell          | Latitude E7440              | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Lenovo        | ThinkPad L580 20LW000VMX    | [7b2e3794c9](https://linux-hardware.org/?probe=7b2e3794c9) | Apr 11, 2023 |
| Google        | Lindar rev3                 | [e6dd3f6805](https://linux-hardware.org/?probe=e6dd3f6805) | Apr 09, 2023 |
| Acer          | Enduro EUN314-51WG          | [7f73117dba](https://linux-hardware.org/?probe=7f73117dba) | Apr 09, 2023 |
| Lenovo        | ThinkPad T470s 20HF0001M... | [8c6105e5be](https://linux-hardware.org/?probe=8c6105e5be) | Apr 06, 2023 |
| Lenovo        | ThinkPad T410 2537WB7       | [d68ffd9d0f](https://linux-hardware.org/?probe=d68ffd9d0f) | Apr 04, 2023 |
| MSI           | GL63 8RC                    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [cd18ce0a96](https://linux-hardware.org/?probe=cd18ce0a96) | Apr 03, 2023 |
| MSI           | GS66 Stealth 11UH           | [43a7d8f578](https://linux-hardware.org/?probe=43a7d8f578) | Apr 03, 2023 |
| Acer          | Aspire A515-51              | [c9245a7032](https://linux-hardware.org/?probe=c9245a7032) | Apr 03, 2023 |
| HP            | EliteBook 840 G3            | [20e885eb0b](https://linux-hardware.org/?probe=20e885eb0b) | Apr 02, 2023 |
| Motion Com... | J3600                       | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d74490158e](https://linux-hardware.org/?probe=d74490158e) | Mar 29, 2023 |
| Lenovo        | IdeaPad S145-14IWL          | [91f36f67a4](https://linux-hardware.org/?probe=91f36f67a4) | Mar 28, 2023 |
| Dell          | Latitude E5250              | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| MSI           | GL63 8RC                    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E744               | [f32cce4c6f](https://linux-hardware.org/?probe=f32cce4c6f) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [d77c81e9e3](https://linux-hardware.org/?probe=d77c81e9e3) | Mar 24, 2023 |
| Valve         | Jupiter                     | [f2fed76f66](https://linux-hardware.org/?probe=f2fed76f66) | Mar 23, 2023 |
| Dell          | Latitude E6430              | [7eafa653dc](https://linux-hardware.org/?probe=7eafa653dc) | Mar 20, 2023 |
| HP            | EliteBook 840 G3            | [8a2a9a9e75](https://linux-hardware.org/?probe=8a2a9a9e75) | Mar 18, 2023 |
| Dell          | Latitude E5470              | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| HP            | EliteBook 6930p             | [c9ba614358](https://linux-hardware.org/?probe=c9ba614358) | Mar 18, 2023 |
| Alienware     | 15 R3                       | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [ae9acbc4ef](https://linux-hardware.org/?probe=ae9acbc4ef) | Mar 15, 2023 |
| HP            | EliteBook 840 G3            | [e111e27012](https://linux-hardware.org/?probe=e111e27012) | Mar 13, 2023 |
| Dell          | Precision M4500             | [b61053a0de](https://linux-hardware.org/?probe=b61053a0de) | Mar 13, 2023 |
| ASUSTek       | UX430UAR                    | [a2b1839fd1](https://linux-hardware.org/?probe=a2b1839fd1) | Mar 11, 2023 |
| HP            | ZBook 17                    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Lenovo        | G580 2189                   | [5e2c4e9a1c](https://linux-hardware.org/?probe=5e2c4e9a1c) | Mar 09, 2023 |
| HP            | ZBook 17                    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [5a9c11da8a](https://linux-hardware.org/?probe=5a9c11da8a) | Mar 07, 2023 |
| HP            | Laptop 14-cm0xxx            | [e24f683971](https://linux-hardware.org/?probe=e24f683971) | Mar 06, 2023 |
| Acer          | Aspire A315-54              | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [d49f7315d3](https://linux-hardware.org/?probe=d49f7315d3) | Mar 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EH00    | [11d225cddb](https://linux-hardware.org/?probe=11d225cddb) | Mar 03, 2023 |
| HP            | Compaq Presario CQ60        | [5ad0c4c383](https://linux-hardware.org/?probe=5ad0c4c383) | Mar 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | [db0d3b74bd](https://linux-hardware.org/?probe=db0d3b74bd) | Feb 27, 2023 |
| HP            | ProBook 470 G1              | [8044704386](https://linux-hardware.org/?probe=8044704386) | Feb 26, 2023 |
| Lenovo        | ThinkPad L412 0585A38       | [da6493ef82](https://linux-hardware.org/?probe=da6493ef82) | Feb 25, 2023 |
| Alienware     | 15 R3                       | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| HP            | ProBook 4530s               | [305f79455e](https://linux-hardware.org/?probe=305f79455e) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK A530               | [9035e056b4](https://linux-hardware.org/?probe=9035e056b4) | Feb 24, 2023 |
| HP            | Compaq CQ58                 | [cfff7e8c96](https://linux-hardware.org/?probe=cfff7e8c96) | Feb 24, 2023 |
| Dell          | Latitude D620               | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| ASUSTek       | X550LB                      | [736bb83bb8](https://linux-hardware.org/?probe=736bb83bb8) | Feb 23, 2023 |
| Dell          | Latitude E5470              | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| Apple         | MacBookPro8,2               | [fd4b8d6419](https://linux-hardware.org/?probe=fd4b8d6419) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Acer          | Aspire 6530G                | [c1d73e8ceb](https://linux-hardware.org/?probe=c1d73e8ceb) | Feb 20, 2023 |
| HP            | EliteBook 830 G5            | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [47e6250a37](https://linux-hardware.org/?probe=47e6250a37) | Feb 19, 2023 |
| Chuwi         | GemiBook Pro                | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| ASUSTek       | K54C                        | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| Valve         | Jupiter                     | [9f63fbafbe](https://linux-hardware.org/?probe=9f63fbafbe) | Feb 16, 2023 |
| Acer          | Predator G9-793             | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| Fujitsu       | LIFEBOOK U748               | [2a189f2497](https://linux-hardware.org/?probe=2a189f2497) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| Dell          | Latitude E7440              | [ac0e96d86c](https://linux-hardware.org/?probe=ac0e96d86c) | Feb 08, 2023 |
| HP            | ZBook 15 G4                 | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9401dac6d](https://linux-hardware.org/?probe=d9401dac6d) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK E736               | [a8fea59f32](https://linux-hardware.org/?probe=a8fea59f32) | Feb 04, 2023 |
| Fujitsu       | LIFEBOOK E736               | [67c2139481](https://linux-hardware.org/?probe=67c2139481) | Feb 04, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| HP            | EliteBook 840 G1            | [b6f1c93413](https://linux-hardware.org/?probe=b6f1c93413) | Feb 02, 2023 |
| HP            | ZBook 15 G4                 | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [3fc59532b8](https://linux-hardware.org/?probe=3fc59532b8) | Feb 01, 2023 |
| Dell          | Precision 5560              | [c994bfa3a7](https://linux-hardware.org/?probe=c994bfa3a7) | Jan 30, 2023 |
| HP            | ZBook 15 G4                 | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Lenovo        | ThinkPad R500 2718WA3       | [2bb86279a8](https://linux-hardware.org/?probe=2bb86279a8) | Jan 27, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [0065b33518](https://linux-hardware.org/?probe=0065b33518) | Jan 26, 2023 |
| Dell          | Inspiron 7577               | [4dded574d3](https://linux-hardware.org/?probe=4dded574d3) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430s 2356GRG      | [cd81d567a2](https://linux-hardware.org/?probe=cd81d567a2) | Jan 24, 2023 |
| HP            | EliteBook 840 G1            | [08d8bb84c4](https://linux-hardware.org/?probe=08d8bb84c4) | Jan 24, 2023 |
| Packard Be... | EasyNote TE69KB             | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| HP            | Pavilion 17                 | [0ba46e91d2](https://linux-hardware.org/?probe=0ba46e91d2) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Acer          | Predator G9-591             | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| Valve         | Jupiter                     | [bd55cae677](https://linux-hardware.org/?probe=bd55cae677) | Jan 17, 2023 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [e24691c830](https://linux-hardware.org/?probe=e24691c830) | Jan 15, 2023 |
| Dell          | Precision M4700             | [64bd9a7627](https://linux-hardware.org/?probe=64bd9a7627) | Jan 14, 2023 |
| ASUSTek       | N53SM                       | [fdf56c0639](https://linux-hardware.org/?probe=fdf56c0639) | Jan 13, 2023 |
| Acer          | Aspire 7730G                | [ba1e942da3](https://linux-hardware.org/?probe=ba1e942da3) | Jan 12, 2023 |
| TUXEDO        | Unknown                     | [ae60044fa6](https://linux-hardware.org/?probe=ae60044fa6) | Jan 12, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [7a2cdcb0ab](https://linux-hardware.org/?probe=7a2cdcb0ab) | Jan 12, 2023 |
| ASUSTek       | X550LN                      | [791cd47247](https://linux-hardware.org/?probe=791cd47247) | Jan 12, 2023 |
| HP            | Unknown                     | [604bea5ac6](https://linux-hardware.org/?probe=604bea5ac6) | Jan 11, 2023 |
| Acer          | Predator G9-591             | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| Apple         | MacBookAir5,1               | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| HP            | 255 G4                      | [1893637142](https://linux-hardware.org/?probe=1893637142) | Jan 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| Dell          | XPS 13 7390                 | [7a89ea18a0](https://linux-hardware.org/?probe=7a89ea18a0) | Jan 06, 2023 |
| ASUSTek       | X501A1                      | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [729d97d43a](https://linux-hardware.org/?probe=729d97d43a) | Jan 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [4b951f8c2a](https://linux-hardware.org/?probe=4b951f8c2a) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [347dc56d43](https://linux-hardware.org/?probe=347dc56d43) | Dec 30, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [3cfcfad4ba](https://linux-hardware.org/?probe=3cfcfad4ba) | Dec 22, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [66b2e8e737](https://linux-hardware.org/?probe=66b2e8e737) | Dec 14, 2022 |
| Acer          | Predator G9-591             | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| Acer          | Aspire A315-43              | [6d77f1e173](https://linux-hardware.org/?probe=6d77f1e173) | Dec 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| Acer          | Predator G9-591             | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Dell          | Latitude E6440              | [425331326b](https://linux-hardware.org/?probe=425331326b) | Dec 06, 2022 |
| Valve         | Jupiter                     | [19f5d58b52](https://linux-hardware.org/?probe=19f5d58b52) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| HP            | 250 G6 Notebook PC          | [95b1694080](https://linux-hardware.org/?probe=95b1694080) | Nov 28, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | [ccc431ef2e](https://linux-hardware.org/?probe=ccc431ef2e) | Nov 28, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [028c06fcdc](https://linux-hardware.org/?probe=028c06fcdc) | Nov 27, 2022 |
| ASUSTek       | E402SA                      | [05983f8566](https://linux-hardware.org/?probe=05983f8566) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| Dell          | Latitude 5410               | [1eeb98c3b0](https://linux-hardware.org/?probe=1eeb98c3b0) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| Dell          | Latitude 5410               | [a9b8b4208d](https://linux-hardware.org/?probe=a9b8b4208d) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| Samsung       | RF511/RF411/RF711           | [db9c9330b7](https://linux-hardware.org/?probe=db9c9330b7) | Nov 23, 2022 |
| ASUSTek       | PRIME Z690-P                | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| HP            | EliteBook 850 G2            | [dd13c1df3f](https://linux-hardware.org/?probe=dd13c1df3f) | Nov 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [6a4c697203](https://linux-hardware.org/?probe=6a4c697203) | Nov 15, 2022 |
| HP            | Compaq 6830s                | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| Lenovo        | G50-30 80G0                 | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HP            | 250 G6 Notebook PC          | [0d8609e1ed](https://linux-hardware.org/?probe=0d8609e1ed) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| MSI           | GP66 Leopard 11UG           | [0dab96ade2](https://linux-hardware.org/?probe=0dab96ade2) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9af713ef6e](https://linux-hardware.org/?probe=9af713ef6e) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dae32fcba7](https://linux-hardware.org/?probe=dae32fcba7) | Nov 04, 2022 |
| Acer          | Predator G9-591             | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| Dell          | Latitude E6330              | [51ded2feb1](https://linux-hardware.org/?probe=51ded2feb1) | Oct 31, 2022 |
| Packard Be... | EasyNote TE69KB             | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [cbdfd56f05](https://linux-hardware.org/?probe=cbdfd56f05) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [031a5998a5](https://linux-hardware.org/?probe=031a5998a5) | Oct 30, 2022 |
| HP            | ZBook 15                    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| Lenovo        | ThinkPad T470 20HES21434    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Acer          | Aspire A315-33              | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [682dcf0b87](https://linux-hardware.org/?probe=682dcf0b87) | Oct 12, 2022 |
| Alienware     | 15 R3                       | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | [703ab6caa2](https://linux-hardware.org/?probe=703ab6caa2) | Oct 10, 2022 |
| Acer          | Aspire A315-33              | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | [29f7444a6e](https://linux-hardware.org/?probe=29f7444a6e) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| Acer          | Aspire 5742G                | [0272592d8e](https://linux-hardware.org/?probe=0272592d8e) | Oct 08, 2022 |
| Acer          | Aspire 5520                 | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Google        | Banon                       | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| Alienware     | 15 R3                       | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Dell          | Latitude 5480               | [ec9593f051](https://linux-hardware.org/?probe=ec9593f051) | Oct 01, 2022 |
| ASUSTek       | GL753VE                     | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [a64f339e70](https://linux-hardware.org/?probe=a64f339e70) | Sep 28, 2022 |
| HP            | EliteBook Revolve 810 G3    | [03ac8c5daa](https://linux-hardware.org/?probe=03ac8c5daa) | Sep 26, 2022 |
| HP            | EliteBook 840 G3            | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Dell          | Latitude E6420              | [e46ce42e90](https://linux-hardware.org/?probe=e46ce42e90) | Sep 20, 2022 |
| Acer          | Aspire E1-570G              | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Valve         | Jupiter                     | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| HP            | EliteBook 8470p             | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| Dell          | Inspiron 3543               | [bb1af3736f](https://linux-hardware.org/?probe=bb1af3736f) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | [40ad505314](https://linux-hardware.org/?probe=40ad505314) | Sep 10, 2022 |
| Dell          | Latitude E6220              | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Dell          | XPS 15 9500                 | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| HP            | Compaq 6735s                | [4e52bb6ecb](https://linux-hardware.org/?probe=4e52bb6ecb) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Acer          | Enduro EUN314-51WG          | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Alienware     | 15 R3                       | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [8834646a81](https://linux-hardware.org/?probe=8834646a81) | Aug 19, 2022 |
| Packard Be... | EasyNote TS11HR             | [9d82dca288](https://linux-hardware.org/?probe=9d82dca288) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Packard Be... | EasyNote TE69KB             | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X501A1                      | [d021969767](https://linux-hardware.org/?probe=d021969767) | Aug 15, 2022 |
| Acer          | Aspire VN7-571G             | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion 15                 | [a5ef05aaff](https://linux-hardware.org/?probe=a5ef05aaff) | Aug 13, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| HP            | EliteBook 8460p             | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| HP            | EliteBook 840 G1            | [2539e9f908](https://linux-hardware.org/?probe=2539e9f908) | Aug 08, 2022 |
| Packard Be... | EasyNote LS11HR             | [0f1a9e4af2](https://linux-hardware.org/?probe=0f1a9e4af2) | Aug 06, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fa0a089121](https://linux-hardware.org/?probe=fa0a089121) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a284074100](https://linux-hardware.org/?probe=a284074100) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| HP            | Laptop 14-dg0xxx            | [365fe3e266](https://linux-hardware.org/?probe=365fe3e266) | Aug 03, 2022 |
| HP            | ProBook 650 G1              | [da1731c1d2](https://linux-hardware.org/?probe=da1731c1d2) | Aug 03, 2022 |
| Packard Be... | EasyNote TE69KB             | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| HP            | EliteBook 840 G1            | [09cd376e43](https://linux-hardware.org/?probe=09cd376e43) | Aug 02, 2022 |
| HP            | Compaq 2510p                | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| HP            | Laptop 14-dg0xxx            | [fa46d23eda](https://linux-hardware.org/?probe=fa46d23eda) | Jul 27, 2022 |
| HP            | ProBook 450 G3              | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| HP            | G62                         | [bc85466c3f](https://linux-hardware.org/?probe=bc85466c3f) | Jul 19, 2022 |
| HP            | ProBook 450 G3              | [96c65556bb](https://linux-hardware.org/?probe=96c65556bb) | Jul 18, 2022 |
| HP            | ProBook 650 G1              | [e540c6e30d](https://linux-hardware.org/?probe=e540c6e30d) | Jul 18, 2022 |
| Acer          | Aspire 5520                 | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 10SC              | [f4f2c80cdd](https://linux-hardware.org/?probe=f4f2c80cdd) | Jul 09, 2022 |
| HP            | EliteBook 840 G1            | [57517e2dc2](https://linux-hardware.org/?probe=57517e2dc2) | Jul 09, 2022 |
| Dell          | Precision 7560              | [3a5fc098c4](https://linux-hardware.org/?probe=3a5fc098c4) | Jul 08, 2022 |
| ASUSTek       | GL753VE                     | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| HUAWEI        | VLT-WX0                     | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Acer          | Aspire R3-131T              | [f525b5f3b0](https://linux-hardware.org/?probe=f525b5f3b0) | Jul 04, 2022 |
| HP            | EliteBook 840 G1            | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | XPS 13 9300                 | [8ecea7fce7](https://linux-hardware.org/?probe=8ecea7fce7) | Jun 28, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Dell          | Latitude E7440              | [41acc5e2ba](https://linux-hardware.org/?probe=41acc5e2ba) | Jun 17, 2022 |
| ASUSTek       | G752VSK                     | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [d4bfcc2d6d](https://linux-hardware.org/?probe=d4bfcc2d6d) | Jun 12, 2022 |
| Dell          | Latitude E7440              | [d2861687ff](https://linux-hardware.org/?probe=d2861687ff) | Jun 12, 2022 |
| HP            | EliteBook 840 G6            | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| HP            | G62                         | [de2464c378](https://linux-hardware.org/?probe=de2464c378) | Jun 08, 2022 |
| ASUSTek       | GL753VE                     | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [6e41ef26bf](https://linux-hardware.org/?probe=6e41ef26bf) | May 29, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | [3a472b96d3](https://linux-hardware.org/?probe=3a472b96d3) | May 27, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | [7f3e3aada0](https://linux-hardware.org/?probe=7f3e3aada0) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Dell          | Latitude 3520               | [6c5618416d](https://linux-hardware.org/?probe=6c5618416d) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | [018e2a8bff](https://linux-hardware.org/?probe=018e2a8bff) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | [6d4ab67cb8](https://linux-hardware.org/?probe=6d4ab67cb8) | May 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| MSI           | GF75 Thin 9SC               | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | V14-IIL 82C4                | [1ca9184b98](https://linux-hardware.org/?probe=1ca9184b98) | May 22, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| HP            | EliteBook 820 G1            | [f06eee580b](https://linux-hardware.org/?probe=f06eee580b) | May 16, 2022 |
| Dell          | Latitude E6330              | [0065ab0681](https://linux-hardware.org/?probe=0065ab0681) | May 12, 2022 |
| Dell          | Latitude 7490               | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| Acer          | Aspire E1-571               | [65d7984ad4](https://linux-hardware.org/?probe=65d7984ad4) | May 09, 2022 |
| HP            | EliteBook 840 G2            | [df57c0ad60](https://linux-hardware.org/?probe=df57c0ad60) | May 09, 2022 |
| Lenovo        | G50-80 80E5                 | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| Lenovo        | Yoga 2 13 20344             | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| Dell          | Latitude E6330              | [c78066bc19](https://linux-hardware.org/?probe=c78066bc19) | Apr 29, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | [31bc958302](https://linux-hardware.org/?probe=31bc958302) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | [8446691cb3](https://linux-hardware.org/?probe=8446691cb3) | Apr 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| Lenovo        | ThinkPad X230 2324GA7       | [a5138b511d](https://linux-hardware.org/?probe=a5138b511d) | Apr 25, 2022 |
| HP            | Laptop 15-bw0xx             | [e83ffcb04f](https://linux-hardware.org/?probe=e83ffcb04f) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | [25e6181500](https://linux-hardware.org/?probe=25e6181500) | Apr 24, 2022 |
| MSI           | Stealth GS77 12UGS          | [cd1bc2095f](https://linux-hardware.org/?probe=cd1bc2095f) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | [33afc70a54](https://linux-hardware.org/?probe=33afc70a54) | Apr 22, 2022 |
| Acer          | Aspire 7530G                | [710b429d94](https://linux-hardware.org/?probe=710b429d94) | Apr 21, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [5a93c8e68c](https://linux-hardware.org/?probe=5a93c8e68c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| HP            | Notebook                    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [07efb6a561](https://linux-hardware.org/?probe=07efb6a561) | Apr 01, 2022 |
| Dell          | Latitude 5480               | [2d431aae25](https://linux-hardware.org/?probe=2d431aae25) | Mar 29, 2022 |
| Lenovo        | ThinkPad X230 2325BN8       | [3ad2d0f3ee](https://linux-hardware.org/?probe=3ad2d0f3ee) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [78ae0419a3](https://linux-hardware.org/?probe=78ae0419a3) | Mar 14, 2022 |
| Lenovo        | V145-15AST 81MT             | [ba2686174e](https://linux-hardware.org/?probe=ba2686174e) | Mar 13, 2022 |
| Acer          | AO725                       | [70febdd28f](https://linux-hardware.org/?probe=70febdd28f) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| HP            | G62                         | [67bc301ee6](https://linux-hardware.org/?probe=67bc301ee6) | Mar 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f351d9839b](https://linux-hardware.org/?probe=f351d9839b) | Mar 09, 2022 |
| ASUSTek       | G751JT                      | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Lenovo        | ThinkPad 13 20GJ0048MS      | [6590a539cf](https://linux-hardware.org/?probe=6590a539cf) | Mar 02, 2022 |
| Fujitsu       | AMILO Pi 3560               | [ea68b8ed21](https://linux-hardware.org/?probe=ea68b8ed21) | Mar 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0278765ef8](https://linux-hardware.org/?probe=0278765ef8) | Feb 28, 2022 |
| Apple         | MacBook4,1                  | [c08be74242](https://linux-hardware.org/?probe=c08be74242) | Feb 27, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fa5d4846df](https://linux-hardware.org/?probe=fa5d4846df) | Feb 23, 2022 |
| HP            | G62                         | [337afde8c1](https://linux-hardware.org/?probe=337afde8c1) | Feb 21, 2022 |
| HP            | G62                         | [a175af3dd6](https://linux-hardware.org/?probe=a175af3dd6) | Feb 21, 2022 |
| powerinter... | Cepter N510-03              | [cd6804144d](https://linux-hardware.org/?probe=cd6804144d) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Lenovo        | ThinkPad E14 20RA001LMX     | [19edff5659](https://linux-hardware.org/?probe=19edff5659) | Feb 17, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Acer          | Aspire ES1-512              | [deb108070d](https://linux-hardware.org/?probe=deb108070d) | Feb 15, 2022 |
| ASUSTek       | T200TAC                     | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| Lenovo        | ThinkPad X230 23252SG       | [a5179b9681](https://linux-hardware.org/?probe=a5179b9681) | Feb 15, 2022 |
| HP            | 250 G5 Notebook PC          | [7cdffcccb7](https://linux-hardware.org/?probe=7cdffcccb7) | Feb 13, 2022 |
| Fujitsu       | LIFEBOOK E780               | [0ba38c6605](https://linux-hardware.org/?probe=0ba38c6605) | Feb 13, 2022 |
| Dell          | Latitude E5420              | [f016e9f3ad](https://linux-hardware.org/?probe=f016e9f3ad) | Feb 12, 2022 |
| Dell          | Latitude E5420              | [8843a735a0](https://linux-hardware.org/?probe=8843a735a0) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | [61e1bce7ae](https://linux-hardware.org/?probe=61e1bce7ae) | Feb 12, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [766e937263](https://linux-hardware.org/?probe=766e937263) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| Lenovo        | G50-80 80E5                 | [72b880911a](https://linux-hardware.org/?probe=72b880911a) | Feb 08, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e0765c9f5a](https://linux-hardware.org/?probe=e0765c9f5a) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | UX303UB                     | [cba6a6b5a6](https://linux-hardware.org/?probe=cba6a6b5a6) | Feb 02, 2022 |
| Lenovo        | ThinkPad X390 20Q00057MX    | [326cb714f0](https://linux-hardware.org/?probe=326cb714f0) | Jan 27, 2022 |
| HP            | Compaq Presario CQ70        | [a31ae712c0](https://linux-hardware.org/?probe=a31ae712c0) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | [82a45a6067](https://linux-hardware.org/?probe=82a45a6067) | Jan 26, 2022 |
| HP            | Compaq 6830s                | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASUSTek       | S551LN                      | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| HP            | EliteBook 820 G1            | [39b90ab9c3](https://linux-hardware.org/?probe=39b90ab9c3) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| Dell          | XPS 17 9710                 | [3417abe371](https://linux-hardware.org/?probe=3417abe371) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Dell          | XPS 17 9710                 | [3d2a67265f](https://linux-hardware.org/?probe=3d2a67265f) | Jan 15, 2022 |
| ASUSTek       | UL30A                       | [c2406eee73](https://linux-hardware.org/?probe=c2406eee73) | Jan 13, 2022 |
| HP            | Laptop 14-dk0xxx            | [4bbc688f9d](https://linux-hardware.org/?probe=4bbc688f9d) | Jan 13, 2022 |
| Toshiba       | Satellite P870              | [e046040d73](https://linux-hardware.org/?probe=e046040d73) | Jan 11, 2022 |
| HP            | Notebook                    | [0667124a5f](https://linux-hardware.org/?probe=0667124a5f) | Jan 10, 2022 |
| Sony          | VGN-FZ21Z                   | [6291085e58](https://linux-hardware.org/?probe=6291085e58) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| Sony          | VGN-FZ21Z                   | [c4ac286105](https://linux-hardware.org/?probe=c4ac286105) | Jan 08, 2022 |
| HP            | ProBook 450 G3              | [1644301279](https://linux-hardware.org/?probe=1644301279) | Jan 07, 2022 |
| ASUSTek       | UL30A                       | [b2682cb5fe](https://linux-hardware.org/?probe=b2682cb5fe) | Jan 06, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 20RA001BMX     | [b34ccf2c06](https://linux-hardware.org/?probe=b34ccf2c06) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [5dd20e2872](https://linux-hardware.org/?probe=5dd20e2872) | Jan 03, 2022 |
| Lenovo        | ThinkPad X61 7674CT0        | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| Acer          | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| MSI           | GE72 6QC                    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| HP            | EliteBook 2570p             | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| MSI           | GE72 6QC                    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Dell          | Latitude 5490               | [a9261b4529](https://linux-hardware.org/?probe=a9261b4529) | Dec 16, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [81873c2912](https://linux-hardware.org/?probe=81873c2912) | Dec 14, 2021 |
| Dell          | Precision 7510              | [59a0d1a314](https://linux-hardware.org/?probe=59a0d1a314) | Dec 13, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| HP            | Pavilion 15                 | [9b61f8e080](https://linux-hardware.org/?probe=9b61f8e080) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Samsung       | 750XDA                      | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| HP            | 340 G5                      | [8ed2eec9b4](https://linux-hardware.org/?probe=8ed2eec9b4) | Dec 07, 2021 |
| Dell          | Latitude E6400              | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| Lenovo        | ThinkPad W540 20BH002NMS    | [52d66e95f4](https://linux-hardware.org/?probe=52d66e95f4) | Dec 01, 2021 |
| ASUSTek       | T100TA                      | [493153bf7c](https://linux-hardware.org/?probe=493153bf7c) | Nov 30, 2021 |
| ASUSTek       | T100TA                      | [b98f644a91](https://linux-hardware.org/?probe=b98f644a91) | Nov 30, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Apple         | MacBookAir6,2               | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| Lenovo        | B50-70 80EU                 | [9476bb5e05](https://linux-hardware.org/?probe=9476bb5e05) | Nov 24, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Google        | Relm                        | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Dell          | Latitude E6420              | [2e2b68b190](https://linux-hardware.org/?probe=2e2b68b190) | Nov 20, 2021 |
| HP            | Pavilion 17                 | [a633bbd978](https://linux-hardware.org/?probe=a633bbd978) | Nov 20, 2021 |
| Acer          | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Lenovo        | ThinkPad T530 24341G0       | [0dcfa8bdc7](https://linux-hardware.org/?probe=0dcfa8bdc7) | Nov 17, 2021 |
| Dell          | Latitude 7420               | [52bd94ce90](https://linux-hardware.org/?probe=52bd94ce90) | Nov 17, 2021 |
| HP            | EliteBook 8560w             | [5bed28d52e](https://linux-hardware.org/?probe=5bed28d52e) | Nov 15, 2021 |
| HP            | ProBook 430 G1              | [da8846a5fd](https://linux-hardware.org/?probe=da8846a5fd) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| ASUSTek       | N53SN                       | [438a1236fb](https://linux-hardware.org/?probe=438a1236fb) | Nov 11, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | [7a1824b26a](https://linux-hardware.org/?probe=7a1824b26a) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | G751JT                      | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [536b4200f8](https://linux-hardware.org/?probe=536b4200f8) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [33a5ffbf9a](https://linux-hardware.org/?probe=33a5ffbf9a) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | [ae1af68eae](https://linux-hardware.org/?probe=ae1af68eae) | Nov 03, 2021 |
| Samsung       | R530/R730                   | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| ASUSTek       | G751JT                      | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Packard Be... | EasyNote TS11HR             | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| ASUSTek       | 1001PX                      | [e74dc83f0a](https://linux-hardware.org/?probe=e74dc83f0a) | Oct 24, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| HP            | Compaq 6735s                | [25c73d7c4d](https://linux-hardware.org/?probe=25c73d7c4d) | Oct 20, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [d89008ef64](https://linux-hardware.org/?probe=d89008ef64) | Oct 16, 2021 |
| Acer          | Aspire 7530G                | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| HP            | ProBook 655 G1              | [5a67ea75fe](https://linux-hardware.org/?probe=5a67ea75fe) | Oct 14, 2021 |
| ASUSTek       | G751JT                      | [072dab3e8c](https://linux-hardware.org/?probe=072dab3e8c) | Oct 14, 2021 |
| Timi          | RedmiBook 13 R              | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | [cf747bee4e](https://linux-hardware.org/?probe=cf747bee4e) | Oct 13, 2021 |
| Lenovo        | Yoga 2 13 20344             | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Dixonsxp      | Unknown                     | [a9d87f6d4e](https://linux-hardware.org/?probe=a9d87f6d4e) | Oct 08, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Dixonsxp      | Unknown                     | [2fe4152b53](https://linux-hardware.org/?probe=2fe4152b53) | Oct 07, 2021 |
| Acer          | Swift SF314-54              | [26501031e8](https://linux-hardware.org/?probe=26501031e8) | Oct 07, 2021 |
| Lenovo        | G50-80 80E5                 | [31df81c76d](https://linux-hardware.org/?probe=31df81c76d) | Sep 30, 2021 |
| ASUSTek       | G751JT                      | [ba4f1bda7d](https://linux-hardware.org/?probe=ba4f1bda7d) | Sep 30, 2021 |
| Acer          | Aspire 5738                 | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| Toshiba       | Satellite C50-B             | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Acer          | Aspire 5750G                | [89783ad217](https://linux-hardware.org/?probe=89783ad217) | Sep 24, 2021 |
| Acer          | Aspire 5750G                | [867138c338](https://linux-hardware.org/?probe=867138c338) | Sep 22, 2021 |
| Lenovo        | ThinkPad X230 204016Z1ZS    | [eb1d7abffc](https://linux-hardware.org/?probe=eb1d7abffc) | Sep 21, 2021 |
| HP            | EliteBook 2570p             | [a4488fd2fe](https://linux-hardware.org/?probe=a4488fd2fe) | Sep 19, 2021 |
| HP            | EliteBook 8540p             | [f9509414bc](https://linux-hardware.org/?probe=f9509414bc) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | B50-10 80QR                 | [506a3682b9](https://linux-hardware.org/?probe=506a3682b9) | Sep 15, 2021 |
| Lenovo        | G50-80 80E5                 | [badf707f13](https://linux-hardware.org/?probe=badf707f13) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c8e465fcb0](https://linux-hardware.org/?probe=c8e465fcb0) | Sep 14, 2021 |
| HP            | Pavilion 11 x360 PC         | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| HP            | Pavilion 11 x360 PC         | [94e64b5b30](https://linux-hardware.org/?probe=94e64b5b30) | Sep 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Dell          | Latitude 7420               | [225b6a0d52](https://linux-hardware.org/?probe=225b6a0d52) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Dell          | Latitude E6430              | [e02c871576](https://linux-hardware.org/?probe=e02c871576) | Sep 06, 2021 |
| Dell          | Latitude E6430              | [5d2627b08e](https://linux-hardware.org/?probe=5d2627b08e) | Sep 06, 2021 |
| Fujitsu       | LIFEBOOK U9310              | [48113d6636](https://linux-hardware.org/?probe=48113d6636) | Sep 02, 2021 |
| Lenovo        | B50-10 80QR                 | [08ad3775b8](https://linux-hardware.org/?probe=08ad3775b8) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | [8e46956f05](https://linux-hardware.org/?probe=8e46956f05) | Aug 31, 2021 |
| Acer          | Nitro AN517-52              | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | [8512904445](https://linux-hardware.org/?probe=8512904445) | Aug 29, 2021 |
| HP            | EliteBook 2560p             | [93e2baa57a](https://linux-hardware.org/?probe=93e2baa57a) | Aug 29, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [f15a7392b9](https://linux-hardware.org/?probe=f15a7392b9) | Aug 27, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| Fujitsu Si... | AMILO Li3910                | [4198aeb0a0](https://linux-hardware.org/?probe=4198aeb0a0) | Aug 26, 2021 |
| Dell          | Latitude 5480               | [3374e57369](https://linux-hardware.org/?probe=3374e57369) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| HP            | Compaq 8710w (GC124EA#AK... | [d7475c57ca](https://linux-hardware.org/?probe=d7475c57ca) | Aug 24, 2021 |
| HP            | ProBook 6360b               | [f8a9a512b2](https://linux-hardware.org/?probe=f8a9a512b2) | Aug 24, 2021 |
| HP            | ProBook 6360b               | [beb76e16b5](https://linux-hardware.org/?probe=beb76e16b5) | Aug 24, 2021 |
| Dell          | Vostro 5568                 | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Dell          | Latitude 7490               | [b4759deb9a](https://linux-hardware.org/?probe=b4759deb9a) | Aug 21, 2021 |
| HP            | EliteBook 8560p             | [97a8f28916](https://linux-hardware.org/?probe=97a8f28916) | Aug 21, 2021 |
| HP            | 255 G1                      | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | [78377f3635](https://linux-hardware.org/?probe=78377f3635) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | [e91d03b0c4](https://linux-hardware.org/?probe=e91d03b0c4) | Aug 17, 2021 |
| Dell          | Latitude E6430              | [afe966ff62](https://linux-hardware.org/?probe=afe966ff62) | Aug 17, 2021 |
| Dell          | Latitude E6500              | [a707e64d52](https://linux-hardware.org/?probe=a707e64d52) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| Dell          | XPS 15 7590                 | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [8d464633db](https://linux-hardware.org/?probe=8d464633db) | Aug 08, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [bd3d1ed844](https://linux-hardware.org/?probe=bd3d1ed844) | Aug 08, 2021 |
| Lenovo        | ThinkPad X270 20HMS70400    | [6b647baf7c](https://linux-hardware.org/?probe=6b647baf7c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| ASUSTek       | 1001PX                      | [a5d694843c](https://linux-hardware.org/?probe=a5d694843c) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | [0297e70b90](https://linux-hardware.org/?probe=0297e70b90) | Aug 04, 2021 |
| Lenovo        | ThinkPad T440p 20AN007FM... | [ba75506849](https://linux-hardware.org/?probe=ba75506849) | Aug 02, 2021 |
| Apple         | MacBookPro9,2               | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| Fujitsu       | LIFEBOOK A530               | [643094a68a](https://linux-hardware.org/?probe=643094a68a) | Jul 26, 2021 |
| Acer          | AO725                       | [4e27f519f7](https://linux-hardware.org/?probe=4e27f519f7) | Jul 25, 2021 |
| Sony          | VPCEH3D0E                   | [2d04f2e0e8](https://linux-hardware.org/?probe=2d04f2e0e8) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| ASUSTek       | G751JT                      | [2c81844355](https://linux-hardware.org/?probe=2c81844355) | Jul 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | [550f9db7cd](https://linux-hardware.org/?probe=550f9db7cd) | Jul 22, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| MSI           | GS60 2PC Ghost              | [cf537038dd](https://linux-hardware.org/?probe=cf537038dd) | Jul 17, 2021 |
| Dell          | Latitude E7470              | [8c32d73d55](https://linux-hardware.org/?probe=8c32d73d55) | Jul 16, 2021 |
| Dell          | Latitude E7470              | [22583cadb6](https://linux-hardware.org/?probe=22583cadb6) | Jul 14, 2021 |
| ASUSTek       | G751JT                      | [532e266dcb](https://linux-hardware.org/?probe=532e266dcb) | Jul 13, 2021 |
| Acer          | Swift SF515-51T             | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Samsung       | R530/R730                   | [103edb36d2](https://linux-hardware.org/?probe=103edb36d2) | Jul 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d52de582e8](https://linux-hardware.org/?probe=d52de582e8) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| Dell          | G7 7700                     | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [def9f42f6c](https://linux-hardware.org/?probe=def9f42f6c) | Jul 02, 2021 |
| Apple         | MacBook4,1                  | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| Dell          | Precision 5540              | [a685a9c5bb](https://linux-hardware.org/?probe=a685a9c5bb) | Jun 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e2743844ad](https://linux-hardware.org/?probe=e2743844ad) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [39f8c7f885](https://linux-hardware.org/?probe=39f8c7f885) | Jun 26, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | [110b313bc0](https://linux-hardware.org/?probe=110b313bc0) | Jun 25, 2021 |
| Lenovo        | ThinkPad X220 42912XG       | [52199864f7](https://linux-hardware.org/?probe=52199864f7) | Jun 24, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e966d318da](https://linux-hardware.org/?probe=e966d318da) | Jun 23, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [7767a1cde7](https://linux-hardware.org/?probe=7767a1cde7) | Jun 23, 2021 |
| Dell          | Precision 5550              | [646d84cc95](https://linux-hardware.org/?probe=646d84cc95) | Jun 23, 2021 |
| IBM           | ThinkPad T43 2668F7G        | [93c8e53b04](https://linux-hardware.org/?probe=93c8e53b04) | Jun 15, 2021 |
| Timi          | RedmiBook 13 R              | [ce648ba480](https://linux-hardware.org/?probe=ce648ba480) | Jun 12, 2021 |
| HP            | Compaq 8510p                | [c371bbdff4](https://linux-hardware.org/?probe=c371bbdff4) | Jun 09, 2021 |
| Dell          | XPS 13 7390                 | [54b62ad499](https://linux-hardware.org/?probe=54b62ad499) | Jun 08, 2021 |
| ASUSTek       | K53U                        | [3acb45024a](https://linux-hardware.org/?probe=3acb45024a) | Jun 08, 2021 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [3764e87d16](https://linux-hardware.org/?probe=3764e87d16) | Jun 07, 2021 |
| Dell          | Latitude E7470              | [6be76778ae](https://linux-hardware.org/?probe=6be76778ae) | Jun 03, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | V145-15AST 81MT             | [30e8995988](https://linux-hardware.org/?probe=30e8995988) | May 27, 2021 |
| HP            | Compaq 8510p                | [7e17cf2706](https://linux-hardware.org/?probe=7e17cf2706) | May 26, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [541b3e9cba](https://linux-hardware.org/?probe=541b3e9cba) | May 25, 2021 |
| Acer          | Aspire 8950G                | [d65fb86955](https://linux-hardware.org/?probe=d65fb86955) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [1b1a173884](https://linux-hardware.org/?probe=1b1a173884) | May 22, 2021 |
| HP            | 350 G1                      | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| Toshiba       | Satellite C660              | [60eb674c8f](https://linux-hardware.org/?probe=60eb674c8f) | May 19, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | [09351c4654](https://linux-hardware.org/?probe=09351c4654) | May 18, 2021 |
| Lenovo        | Yoga 2 13 20344             | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Apple         | MacBookAir3,2               | [8b2100d9ad](https://linux-hardware.org/?probe=8b2100d9ad) | May 14, 2021 |
| HP            | EliteBook 2170p             | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| HP            | Pavilion g6                 | [ab2366fd14](https://linux-hardware.org/?probe=ab2366fd14) | May 11, 2021 |
| Dell          | Latitude 7400               | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| Dell          | Latitude 7400               | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Dell          | Latitude E7270              | [6708f53385](https://linux-hardware.org/?probe=6708f53385) | May 04, 2021 |
| ASUSTek       | G751JT                      | [93eb4a6a39](https://linux-hardware.org/?probe=93eb4a6a39) | Apr 24, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c586a3a771](https://linux-hardware.org/?probe=c586a3a771) | Apr 20, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [7e5ffea0b6](https://linux-hardware.org/?probe=7e5ffea0b6) | Apr 20, 2021 |
| Lenovo        | B70-80 80MR                 | [edef8dfd8b](https://linux-hardware.org/?probe=edef8dfd8b) | Apr 19, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [d01dac7a8f](https://linux-hardware.org/?probe=d01dac7a8f) | Apr 16, 2021 |
| Lenovo        | B50-45 80F0                 | [0558c9e99e](https://linux-hardware.org/?probe=0558c9e99e) | Apr 16, 2021 |
| ASUSTek       | G751JT                      | [7ca0cd3696](https://linux-hardware.org/?probe=7ca0cd3696) | Apr 15, 2021 |
| HP            | Compaq CQ58                 | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9776a806ac](https://linux-hardware.org/?probe=9776a806ac) | Apr 14, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [12fb9fd662](https://linux-hardware.org/?probe=12fb9fd662) | Apr 12, 2021 |
| MSI           | GL62M 7REX                  | [8ee2678b38](https://linux-hardware.org/?probe=8ee2678b38) | Apr 10, 2021 |
| ASUSTek       | X75VD                       | [258fbf86ed](https://linux-hardware.org/?probe=258fbf86ed) | Apr 09, 2021 |
| ASUSTek       | G751JT                      | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [c480530d42](https://linux-hardware.org/?probe=c480530d42) | Apr 07, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ecae2e7ad8](https://linux-hardware.org/?probe=ecae2e7ad8) | Apr 06, 2021 |
| Samsung       | R530/R730                   | [0085bebd03](https://linux-hardware.org/?probe=0085bebd03) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| HP            | EliteBook 755 G2            | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [d8f1bccb78](https://linux-hardware.org/?probe=d8f1bccb78) | Mar 29, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [54845ca16f](https://linux-hardware.org/?probe=54845ca16f) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [1f11381bfb](https://linux-hardware.org/?probe=1f11381bfb) | Mar 27, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 103       | 9.67%   |
| Ubuntu 22.04                 | 61        | 5.73%   |
| Ubuntu 18.04                 | 60        | 5.63%   |
| Pop!_OS 22.04                | 29        | 2.72%   |
| OpenMandriva 23.01           | 29        | 2.72%   |
| Debian 11                    | 25        | 2.35%   |
| Ubuntu 24.04                 | 20        | 1.88%   |
| Linux Mint 21.1              | 20        | 1.88%   |
| Arch Rolling                 | 19        | 1.78%   |
| Ubuntu 21.04                 | 16        | 1.5%    |
| OpenMandriva 4.3             | 16        | 1.5%    |
| Debian 12                    | 16        | 1.5%    |
| OpenMandriva 4.2             | 14        | 1.31%   |
| Fedora 39                    | 14        | 1.31%   |
| EndeavourOS Rolling          | 14        | 1.31%   |
| OpenMandriva 23.03           | 13        | 1.22%   |
| Manjaro                      | 13        | 1.22%   |
| Linux Mint 20                | 13        | 1.22%   |
| Fedora 38                    | 12        | 1.13%   |
| ArcoLinux Rolling            | 12        | 1.13%   |
| Arch                         | 12        | 1.13%   |
| Linux Mint 20.2              | 11        | 1.03%   |
| Linux Mint 19.3              | 11        | 1.03%   |
| Fedora 33                    | 11        | 1.03%   |
| Zorin 16                     | 10        | 0.94%   |
| Xubuntu 20.04                | 10        | 0.94%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.94%   |
| OpenMandriva 23.08           | 10        | 0.94%   |
| Fedora 40                    | 10        | 0.94%   |
| Fedora 34                    | 10        | 0.94%   |
| Zorin 17                     | 9         | 0.85%   |
| Ubuntu 21.10                 | 9         | 0.85%   |
| Pop!_OS 21.04                | 9         | 0.85%   |
| Fedora 37                    | 9         | 0.85%   |
| Ubuntu 20.10                 | 8         | 0.75%   |
| Linux Mint 20.1              | 8         | 0.75%   |
| Fedora 32                    | 8         | 0.75%   |
| Ubuntu 19.10                 | 7         | 0.66%   |
| Pop!_OS 21.10                | 7         | 0.66%   |
| Pop!_OS 20.04                | 7         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 296       | 29.69%  |
| OpenMandriva     | 91        | 9.13%   |
| Fedora           | 91        | 9.13%   |
| Linux Mint       | 86        | 8.63%   |
| Pop!_OS          | 54        | 5.42%   |
| Debian           | 54        | 5.42%   |
| Manjaro          | 30        | 3.01%   |
| Arch             | 30        | 3.01%   |
| Xubuntu          | 23        | 2.31%   |
| Kubuntu          | 22        | 2.21%   |
| Zorin            | 21        | 2.11%   |
| EndeavourOS      | 16        | 1.6%    |
| ROSA             | 15        | 1.5%    |
| openSUSE         | 14        | 1.4%    |
| Kali             | 13        | 1.3%    |
| Ubuntu MATE      | 12        | 1.2%    |
| ArcoLinux        | 12        | 1.2%    |
| Lubuntu          | 10        | 1%      |
| KDE neon         | 10        | 1%      |
| Gentoo           | 10        | 1%      |
| Elementary       | 7         | 0.7%    |
| SteamOS          | 6         | 0.6%    |
| MX               | 5         | 0.5%    |
| Ubuntu Budgie    | 4         | 0.4%    |
| Parrot           | 4         | 0.4%    |
| NixOS            | 4         | 0.4%    |
| Endless          | 4         | 0.4%    |
| Devuan           | 4         | 0.4%    |
| CentOS           | 4         | 0.4%    |
| LMDE             | 3         | 0.3%    |
| Garuda Linux     | 3         | 0.3%    |
| BlackPanther     | 3         | 0.3%    |
| Ubuntu Unity     | 2         | 0.2%    |
| Solus            | 2         | 0.2%    |
| RHEL             | 2         | 0.2%    |
| Peppermint       | 2         | 0.2%    |
| org.kde.Platform | 2         | 0.2%    |
| Nobara           | 2         | 0.2%    |
| Lilidog          | 2         | 0.2%    |
| Clear Linux      | 2         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290   | 28        | 2.4%    |
| 5.4.0-42-generic         | 20        | 1.72%   |
| 5.4.0-58-generic         | 13        | 1.11%   |
| 5.16.7-desktop-1omv4003  | 13        | 1.11%   |
| 5.10.14-desktop-1omv4002 | 13        | 1.11%   |
| 6.2.6-desktop-1omv2390   | 12        | 1.03%   |
| 5.4.0-48-generic         | 10        | 0.86%   |
| 6.4.11-desktop-1omv2390  | 9         | 0.77%   |
| 5.3.0-40-generic         | 8         | 0.69%   |
| 6.9.3-76060903-generic   | 7         | 0.6%    |
| 5.4.0-47-generic         | 7         | 0.6%    |
| 5.15.0-58-generic        | 7         | 0.6%    |
| 5.11.0-7620-generic      | 7         | 0.6%    |
| 6.8.0-47-generic         | 6         | 0.51%   |
| 6.8.0-40-generic         | 6         | 0.51%   |
| 6.5.0-14-generic         | 6         | 0.51%   |
| 6.2.0-39-generic         | 6         | 0.51%   |
| 6.2.0-26-generic         | 6         | 0.51%   |
| 6.2.0-20-generic         | 6         | 0.51%   |
| 5.4.0-52-generic         | 6         | 0.51%   |
| 5.3.0-42-generic         | 6         | 0.51%   |
| 5.15.0-91-generic        | 6         | 0.51%   |
| 5.15.0-71-generic        | 6         | 0.51%   |
| 5.15.0-52-generic        | 6         | 0.51%   |
| 5.11.0-41-generic        | 6         | 0.51%   |
| 6.8.0-49-generic         | 5         | 0.43%   |
| 6.8.0-45-generic         | 5         | 0.43%   |
| 6.5.0-26-generic         | 5         | 0.43%   |
| 6.5.0-15-generic         | 5         | 0.43%   |
| 6.2.0-32-generic         | 5         | 0.43%   |
| 5.15.0-67-generic        | 5         | 0.43%   |
| 5.15.0-48-generic        | 5         | 0.43%   |
| 5.13.0-22-generic        | 5         | 0.43%   |
| 5.10.0-21-amd64          | 5         | 0.43%   |
| 6.8.0-31-generic         | 4         | 0.34%   |
| 6.6.2-desktop-1omv2390   | 4         | 0.34%   |
| 6.2.0-37-generic         | 4         | 0.34%   |
| 6.12.1-desktop-1omv2490  | 4         | 0.34%   |
| 6.1.0-13-amd64           | 4         | 0.34%   |
| 5.8.0-50-generic         | 4         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 133       | 12.06%  |
| 5.15.0  | 84        | 7.62%   |
| 5.11.0  | 44        | 3.99%   |
| 4.15.0  | 43        | 3.9%    |
| 6.8.0   | 39        | 3.54%   |
| 5.8.0   | 39        | 3.54%   |
| 6.5.0   | 38        | 3.45%   |
| 5.3.0   | 35        | 3.17%   |
| 6.2.0   | 34        | 3.08%   |
| 5.10.0  | 30        | 2.72%   |
| 6.1.1   | 29        | 2.63%   |
| 5.13.0  | 24        | 2.18%   |
| 5.19.0  | 21        | 1.9%    |
| 6.1.0   | 19        | 1.72%   |
| 6.2.6   | 15        | 1.36%   |
| 5.0.0   | 15        | 1.36%   |
| 5.16.7  | 13        | 1.18%   |
| 5.10.14 | 13        | 1.18%   |
| 6.4.11  | 10        | 0.91%   |
| 4.18.0  | 10        | 0.91%   |
| 6.9.3   | 9         | 0.82%   |
| 4.19.0  | 8         | 0.73%   |
| 6.11.0  | 7         | 0.63%   |
| 6.12.1  | 6         | 0.54%   |
| 5.14.0  | 6         | 0.54%   |
| 6.0.0   | 5         | 0.45%   |
| 5.16.13 | 5         | 0.45%   |
| 6.8.5   | 4         | 0.36%   |
| 6.6.2   | 4         | 0.36%   |
| 6.5.6   | 4         | 0.36%   |
| 6.10.0  | 4         | 0.36%   |
| 6.0.8   | 4         | 0.36%   |
| 5.17.5  | 4         | 0.36%   |
| 5.15.15 | 4         | 0.36%   |
| 4.18.16 | 4         | 0.36%   |
| 6.9.7   | 3         | 0.27%   |
| 6.8.11  | 3         | 0.27%   |
| 6.7.3   | 3         | 0.27%   |
| 6.6.10  | 3         | 0.27%   |
| 6.5.4   | 3         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 143       | 13.17%  |
| 5.15    | 112       | 10.31%  |
| 6.1     | 67        | 6.17%   |
| 5.10    | 64        | 5.89%   |
| 6.2     | 58        | 5.34%   |
| 6.5     | 57        | 5.25%   |
| 5.11    | 54        | 4.97%   |
| 5.8     | 51        | 4.7%    |
| 6.8     | 50        | 4.6%    |
| 4.15    | 43        | 3.96%   |
| 5.3     | 40        | 3.68%   |
| 5.13    | 33        | 3.04%   |
| 5.19    | 30        | 2.76%   |
| 5.16    | 29        | 2.67%   |
| 6.6     | 20        | 1.84%   |
| 6.0     | 20        | 1.84%   |
| 6.4     | 19        | 1.75%   |
| 6.11    | 16        | 1.47%   |
| 5.0     | 15        | 1.38%   |
| 6.9     | 14        | 1.29%   |
| 5.14    | 14        | 1.29%   |
| 4.18    | 14        | 1.29%   |
| 6.10    | 13        | 1.2%    |
| 5.17    | 11        | 1.01%   |
| 6.7     | 10        | 0.92%   |
| 4.19    | 10        | 0.92%   |
| 6.3     | 9         | 0.83%   |
| 5.12    | 9         | 0.83%   |
| 6.12    | 8         | 0.74%   |
| 5.9     | 8         | 0.74%   |
| 5.7     | 7         | 0.64%   |
| 5.5     | 7         | 0.64%   |
| 4.9     | 7         | 0.64%   |
| 5.18    | 6         | 0.55%   |
| 5.6     | 5         | 0.46%   |
| 5.2     | 2         | 0.18%   |
| 4.4     | 2         | 0.18%   |
| 4.1     | 2         | 0.18%   |
| 3.10    | 2         | 0.18%   |
| 5.1     | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 940       | 97.21%  |
| i686    | 25        | 2.59%   |
| armv7l  | 1         | 0.1%    |
| aarch64 | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 444       | 44.22%  |
| KDE5             | 193       | 19.22%  |
| Unknown          | 89        | 8.86%   |
| XFCE             | 76        | 7.57%   |
| X-Cinnamon       | 62        | 6.18%   |
| MATE             | 23        | 2.29%   |
| LXQt             | 14        | 1.39%   |
| KDE6             | 14        | 1.39%   |
| i3               | 11        | 1.1%    |
| KDE4             | 10        | 1%      |
| Cinnamon         | 10        | 1%      |
| GNOME Flashback  | 9         | 0.9%    |
| Pantheon         | 7         | 0.7%    |
| Budgie           | 7         | 0.7%    |
| LXDE             | 6         | 0.6%    |
| KDE              | 6         | 0.6%    |
| lightdm-xsession | 4         | 0.4%    |
| Hyprland         | 3         | 0.3%    |
| Unity            | 2         | 0.2%    |
| sway             | 2         | 0.2%    |
| openbox          | 2         | 0.2%    |
| LeftWM           | 2         | 0.2%    |
| xubuntu          | 1         | 0.1%    |
| xmonad           | 1         | 0.1%    |
| icewm            | 1         | 0.1%    |
| Enlightenment    | 1         | 0.1%    |
| DWM              | 1         | 0.1%    |
| Deepin           | 1         | 0.1%    |
| BunsenLabs       | 1         | 0.1%    |
| bspwm            | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 678       | 67.73%  |
| Wayland | 263       | 26.27%  |
| Unknown | 45        | 4.5%    |
| Tty     | 15        | 1.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 419       | 41.69%  |
| SDDM          | 180       | 17.91%  |
| GDM           | 125       | 12.44%  |
| GDM3          | 119       | 11.84%  |
| LightDM       | 112       | 11.14%  |
| TDM           | 33        | 3.28%   |
| KDM           | 9         | 0.9%    |
| XDM           | 2         | 0.2%    |
| GREETD        | 2         | 0.2%    |
| SLIMSKI       | 1         | 0.1%    |
| Ly            | 1         | 0.1%    |
| LXDM          | 1         | 0.1%    |
| DARKDM_ON_TTY | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 449       | 45.54%  |
| fi_FI       | 304       | 30.83%  |
| Unknown     | 77        | 7.81%   |
| en_GB       | 76        | 7.71%   |
| C           | 22        | 2.23%   |
| ru_RU       | 19        | 1.93%   |
| et_EE       | 4         | 0.41%   |
| en_DK       | 4         | 0.41%   |
| de_DE       | 4         | 0.41%   |
| fr_FR       | 3         | 0.3%    |
| en_AG       | 3         | 0.3%    |
| zh_CN       | 2         | 0.2%    |
| UTF-8       | 2         | 0.2%    |
| sv_FI       | 2         | 0.2%    |
| POSIX       | 2         | 0.2%    |
| pl_PL       | 2         | 0.2%    |
| en_IE       | 2         | 0.2%    |
| en_FI       | 2         | 0.2%    |
| ja_JP       | 1         | 0.1%    |
| it_IT       | 1         | 0.1%    |
| is_IS       | 1         | 0.1%    |
| hu_HU       | 1         | 0.1%    |
| en_US.utf-8 | 1         | 0.1%    |
| en_NG       | 1         | 0.1%    |
| C.UTF8      | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 499       | 50.76%  |
| BIOS | 484       | 49.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 686       | 68.88%  |
| Btrfs   | 129       | 12.95%  |
| Overlay | 81        | 8.13%   |
| Tmpfs   | 58        | 5.82%   |
| Unknown | 19        | 1.91%   |
| Xfs     | 12        | 1.2%    |
| Zfs     | 7         | 0.7%    |
| Ext2    | 3         | 0.3%    |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 446       | 45.23%  |
| Unknown | 420       | 42.6%   |
| MBR     | 120       | 12.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 878       | 89.41%  |
| Yes       | 104       | 10.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 771       | 79.24%  |
| Yes       | 202       | 20.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 307       | 31.75%  |
| Hewlett-Packard     | 198       | 20.48%  |
| ASUSTek Computer    | 124       | 12.82%  |
| Dell                | 93        | 9.62%   |
| Acer                | 67        | 6.93%   |
| Fujitsu             | 32        | 3.31%   |
| Apple               | 32        | 3.31%   |
| Samsung Electronics | 22        | 2.28%   |
| MSI                 | 16        | 1.65%   |
| Fujitsu Siemens     | 13        | 1.34%   |
| Toshiba             | 10        | 1.03%   |
| Valve               | 6         | 0.62%   |
| HUAWEI              | 6         | 0.62%   |
| Sony                | 4         | 0.41%   |
| Packard Bell        | 4         | 0.41%   |
| Google              | 3         | 0.31%   |
| Unknown             | 3         | 0.31%   |
| TUXEDO              | 2         | 0.21%   |
| Timi                | 2         | 0.21%   |
| Notebook            | 2         | 0.21%   |
| Framework           | 2         | 0.21%   |
| Unchartevice        | 1         | 0.1%    |
| TrekStor            | 1         | 0.1%    |
| System76            | 1         | 0.1%    |
| Seco                | 1         | 0.1%    |
| Schenker            | 1         | 0.1%    |
| powerinternational  | 1         | 0.1%    |
| Panasonic           | 1         | 0.1%    |
| Motion Computing    | 1         | 0.1%    |
| Intel               | 1         | 0.1%    |
| Insyde              | 1         | 0.1%    |
| IBM                 | 1         | 0.1%    |
| HONOR               | 1         | 0.1%    |
| Gigabyte Technology | 1         | 0.1%    |
| eMachines           | 1         | 0.1%    |
| Dixonsxp            | 1         | 0.1%    |
| Chuwi               | 1         | 0.1%    |
| Cepter              | 1         | 0.1%    |
| Bluechip Computer   | 1         | 0.1%    |
| Alienware           | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 8         | 0.83%   |
| HP EliteBook 840 G3                    | 7         | 0.72%   |
| Fujitsu LIFEBOOK A530                  | 5         | 0.52%   |
| Valve Jupiter                          | 4         | 0.41%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 4         | 0.41%   |
| Lenovo V145-15AST 81MT                 | 4         | 0.41%   |
| Lenovo ThinkPad T420 4180PBG           | 4         | 0.41%   |
| HP Pavilion dv6                        | 4         | 0.41%   |
| HP Pavilion 15                         | 4         | 0.41%   |
| HP EliteBook 8460p                     | 4         | 0.41%   |
| HP EliteBook 840 G6                    | 4         | 0.41%   |
| HP EliteBook 840 G1                    | 4         | 0.41%   |
| HP EliteBook 2560p                     | 4         | 0.41%   |
| ASUS TUF Gaming FX505DT_FX505DT        | 4         | 0.41%   |
| Samsung R530/R730                      | 3         | 0.31%   |
| Samsung 300E4A/300E5A/300E7A           | 3         | 0.31%   |
| Lenovo ThinkPad T480 20L5000BMX        | 3         | 0.31%   |
| Lenovo ThinkPad P14s Gen 2a 21A00004MX | 3         | 0.31%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ       | 3         | 0.31%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 3         | 0.31%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 3         | 0.31%   |
| Lenovo G50-30 80G0                     | 3         | 0.31%   |
| HP ZBook 15 G4                         | 3         | 0.31%   |
| HP ProBook 650 G1                      | 3         | 0.31%   |
| HP Pavilion 17                         | 3         | 0.31%   |
| HP Notebook                            | 3         | 0.31%   |
| HP EliteBook 840 G7 Notebook PC        | 3         | 0.31%   |
| HP EliteBook 840 G5                    | 3         | 0.31%   |
| HP EliteBook 820 G1                    | 3         | 0.31%   |
| Fujitsu Siemens ESPRIMO Mobile D9500   | 3         | 0.31%   |
| Dell XPS 13 9380                       | 3         | 0.31%   |
| Dell XPS 13 9360                       | 3         | 0.31%   |
| Dell Precision M4700                   | 3         | 0.31%   |
| Dell Latitude E7440                    | 3         | 0.31%   |
| Dell Latitude E6430                    | 3         | 0.31%   |
| Dell Latitude E5470                    | 3         | 0.31%   |
| Dell Latitude 7490                     | 3         | 0.31%   |
| ASUS T100TA                            | 3         | 0.31%   |
| ASUS E402NA                            | 3         | 0.31%   |
| Apple MacBookPro8,2                    | 3         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 214       | 22.13%  |
| HP EliteBook            | 70        | 7.24%   |
| Dell Latitude           | 50        | 5.17%   |
| Acer Aspire             | 44        | 4.55%   |
| HP Pavilion             | 37        | 3.83%   |
| Lenovo IdeaPad          | 33        | 3.41%   |
| Fujitsu LIFEBOOK        | 30        | 3.1%    |
| HP ProBook              | 18        | 1.86%   |
| Dell XPS                | 18        | 1.86%   |
| HP Compaq               | 17        | 1.76%   |
| ASUS VivoBook           | 16        | 1.65%   |
| HP Laptop               | 15        | 1.55%   |
| Lenovo Yoga             | 14        | 1.45%   |
| Dell Precision          | 13        | 1.34%   |
| Lenovo Legion           | 12        | 1.24%   |
| ASUS ASUS               | 11        | 1.14%   |
| HP ZBook                | 9         | 0.93%   |
| Toshiba Satellite       | 8         | 0.83%   |
| Dell Inspiron           | 8         | 0.83%   |
| ASUS ZenBook            | 8         | 0.83%   |
| ASUS TUF                | 8         | 0.83%   |
| Acer Swift              | 8         | 0.83%   |
| Unknown                 | 8         | 0.83%   |
| ASUS ROG                | 7         | 0.72%   |
| Fujitsu Siemens ESPRIMO | 6         | 0.62%   |
| Fujitsu Siemens AMILO   | 6         | 0.62%   |
| HP 250                  | 5         | 0.52%   |
| Valve Jupiter           | 4         | 0.41%   |
| Samsung 300E4A          | 4         | 0.41%   |
| Packard Bell EasyNote   | 4         | 0.41%   |
| Lenovo V145-15AST       | 4         | 0.41%   |
| HP 255                  | 4         | 0.41%   |
| Apple MacBookPro8       | 4         | 0.41%   |
| Apple MacBookPro5       | 4         | 0.41%   |
| Samsung R530            | 3         | 0.31%   |
| Lenovo G50-30           | 3         | 0.31%   |
| HP Notebook             | 3         | 0.31%   |
| Dell Vostro             | 3         | 0.31%   |
| ASUS T100TA             | 3         | 0.31%   |
| ASUS E402NA             | 3         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 87        | 9%      |
| 2011    | 77        | 7.96%   |
| 2018    | 75        | 7.76%   |
| 2013    | 74        | 7.65%   |
| 2012    | 70        | 7.24%   |
| 2017    | 66        | 6.83%   |
| 2020    | 64        | 6.62%   |
| 2014    | 63        | 6.51%   |
| 2021    | 60        | 6.2%    |
| 2008    | 58        | 6%      |
| 2015    | 55        | 5.69%   |
| 2016    | 51        | 5.27%   |
| 2010    | 39        | 4.03%   |
| 2023    | 30        | 3.1%    |
| 2022    | 27        | 2.79%   |
| 2007    | 26        | 2.69%   |
| 2009    | 25        | 2.59%   |
| 2024    | 8         | 0.83%   |
| 2006    | 8         | 0.83%   |
| 2005    | 3         | 0.31%   |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 967       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 883       | 90.47%  |
| Enabled  | 93        | 9.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 961       | 99.38%  |
| Yes  | 6         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 306       | 31.19%  |
| 3.01-4.0    | 200       | 20.39%  |
| 16.01-24.0  | 158       | 16.11%  |
| 8.01-16.0   | 153       | 15.6%   |
| 32.01-64.0  | 72        | 7.34%   |
| 1.01-2.0    | 33        | 3.36%   |
| 24.01-32.0  | 21        | 2.14%   |
| 2.01-3.0    | 15        | 1.53%   |
| 64.01-256.0 | 14        | 1.43%   |
| 0.51-1.0    | 9         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 387       | 36.58%  |
| 2.01-3.0   | 251       | 23.72%  |
| 4.01-8.0   | 158       | 14.93%  |
| 3.01-4.0   | 128       | 12.1%   |
| 0.51-1.0   | 72        | 6.81%   |
| 8.01-16.0  | 39        | 3.69%   |
| 0.01-0.5   | 12        | 1.13%   |
| 16.01-24.0 | 9         | 0.85%   |
| 32.01-64.0 | 1         | 0.09%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 793       | 81%     |
| 2      | 155       | 15.83%  |
| 3      | 17        | 1.74%   |
| 0      | 9         | 0.92%   |
| 4      | 3         | 0.31%   |
| 7      | 1         | 0.1%    |
| 6      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 648       | 66.6%   |
| Yes       | 325       | 33.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 802       | 82.51%  |
| No        | 170       | 17.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 939       | 96.8%   |
| No        | 31        | 3.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 782       | 79.96%  |
| No        | 196       | 20.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Finland | 967       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Helsinki     | 490       | 47.76%  |
| Tampere      | 80        | 7.8%    |
| Turku        | 69        | 6.73%   |
| Espoo        | 47        | 4.58%   |
| Oulu         | 41        | 4%      |
| Vantaa       | 32        | 3.12%   |
| Jyväskylä  | 28        | 2.73%   |
| Kuopio       | 23        | 2.24%   |
| Lahti        | 21        | 2.05%   |
| Vaasa        | 10        | 0.97%   |
| Raisio       | 8         | 0.78%   |
| Hyvinkaeae   | 7         | 0.68%   |
| Seinäjoki   | 6         | 0.58%   |
| Joensuu      | 6         | 0.58%   |
| Tuusula      | 5         | 0.49%   |
| Salo         | 5         | 0.49%   |
| Rovaniemi    | 5         | 0.49%   |
| Pori         | 5         | 0.49%   |
| Kouvola      | 5         | 0.49%   |
| Kotka        | 5         | 0.49%   |
| Kokkola      | 5         | 0.49%   |
| Järvenpää | 5         | 0.49%   |
| Riihimäki   | 4         | 0.39%   |
| Porvoo       | 4         | 0.39%   |
| Lohja        | 4         | 0.39%   |
| Lappeenranta | 4         | 0.39%   |
| Hämeenlinna | 4         | 0.39%   |
| Forssa       | 4         | 0.39%   |
| Rusko        | 3         | 0.29%   |
| Raahe        | 3         | 0.29%   |
| Pirkkala     | 3         | 0.29%   |
| Mikkeli      | 3         | 0.29%   |
| Mäntsälä  | 3         | 0.29%   |
| Halikko      | 3         | 0.29%   |
| Ylöjärvi   | 2         | 0.19%   |
| Valkeakoski  | 2         | 0.19%   |
| Urjala       | 2         | 0.19%   |
| Tenala       | 2         | 0.19%   |
| Solv         | 2         | 0.19%   |
| Simo         | 2         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 235       | 316    | 20.83%  |
| Kingston                    | 96        | 113    | 8.51%   |
| Seagate                     | 89        | 105    | 7.89%   |
| WDC                         | 79        | 106    | 7%      |
| SK hynix                    | 69        | 88     | 6.12%   |
| Sandisk                     | 69        | 85     | 6.12%   |
| Toshiba                     | 65        | 76     | 5.76%   |
| Unknown                     | 58        | 78     | 5.14%   |
| Intel                       | 51        | 60     | 4.52%   |
| Micron Technology           | 47        | 55     | 4.17%   |
| Hitachi                     | 43        | 60     | 3.81%   |
| HGST                        | 27        | 43     | 2.39%   |
| Apple                       | 21        | 31     | 1.86%   |
| Crucial                     | 18        | 20     | 1.6%    |
| KIOXIA                      | 16        | 16     | 1.42%   |
| A-DATA Technology           | 12        | 13     | 1.06%   |
| Transcend                   | 11        | 11     | 0.98%   |
| Kingston Technology Company | 11        | 13     | 0.98%   |
| Fujitsu                     | 11        | 14     | 0.98%   |
| OCZ                         | 8         | 12     | 0.71%   |
| Corsair                     | 6         | 6      | 0.53%   |
| PNY                         | 5         | 5      | 0.44%   |
| LITEONIT                    | 5         | 11     | 0.44%   |
| LITEON                      | 5         | 9      | 0.44%   |
| BHT                         | 5         | 7      | 0.44%   |
| Lenovo                      | 4         | 4      | 0.35%   |
| Intenso                     | 4         | 4      | 0.35%   |
| China                       | 4         | 6      | 0.35%   |
| UMIS                        | 3         | 6      | 0.27%   |
| Silicon Motion              | 3         | 3      | 0.27%   |
| ASMT                        | 3         | 3      | 0.27%   |
| Verbatim                    | 2         | 2      | 0.18%   |
| Union Memory (Shenzhen)     | 2         | 4      | 0.18%   |
| Union Memory                | 2         | 2      | 0.18%   |
| Phison Electronics          | 2         | 3      | 0.18%   |
| Phison                      | 2         | 2      | 0.18%   |
| Patriot                     | 2         | 2      | 0.18%   |
| O2 Micro                    | 2         | 2      | 0.18%   |
| Micron/Crucial Technology   | 2         | 2      | 0.18%   |
| JMicron Technology          | 2         | 5      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                      | 20        | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 18        | 1.55%   |
| Unknown MMC Card  64GB                               | 14        | 1.2%    |
| Seagate ST9500325AS 500GB                            | 13        | 1.12%   |
| Samsung SSD 850 EVO 500GB                            | 12        | 1.03%   |
| Kingston SA400S37120G 120GB SSD                      | 11        | 0.94%   |
| Unknown MMC Card  32GB                               | 9         | 0.77%   |
| Seagate ST500LT012-1DG142 500GB                      | 9         | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 9         | 0.77%   |
| HGST HTS721010A9E630 1TB                             | 9         | 0.77%   |
| Samsung NVMe SSD Drive 512GB                         | 8         | 0.69%   |
| Kingston SA400S37480G 480GB SSD                      | 8         | 0.69%   |
| Unknown MMC Card  128GB                              | 7         | 0.6%    |
| Samsung NVMe SSD Drive 256GB                         | 7         | 0.6%    |
| Samsung MZYLF128HCHP-000L2 128GB SSD                 | 7         | 0.6%    |
| SK hynix NVMe SSD Drive 512GB                        | 6         | 0.52%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                  | 6         | 0.52%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD                 | 6         | 0.52%   |
| Micron 2210_MTFDHBA512QFD 512GB                      | 6         | 0.52%   |
| Kingston SV300S37A240G 240GB SSD                     | 6         | 0.52%   |
| Intel SSDSC2BW180A3L 180GB                           | 6         | 0.52%   |
| Toshiba MQ01ABD100 1TB                               | 5         | 0.43%   |
| Seagate ST500LT012-9WS142 500GB                      | 5         | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB                       | 5         | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 5         | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                         | 5         | 0.43%   |
| Samsung SSD 850 EVO 250GB                            | 5         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 5         | 0.43%   |
| Hitachi HTS547550A9E384 500GB                        | 5         | 0.43%   |
| HGST HTS725050A7E630 500GB                           | 5         | 0.43%   |
| Toshiba THNSNF128GCSS 128GB SSD                      | 4         | 0.34%   |
| Toshiba NVMe SSD Drive 256GB                         | 4         | 0.34%   |
| Toshiba MQ01ABF050 500GB                             | 4         | 0.34%   |
| Toshiba MQ01ABD075 752GB                             | 4         | 0.34%   |
| Toshiba MQ01ABD050 500GB                             | 4         | 0.34%   |
| SK hynix NVMe SSD Drive 256GB                        | 4         | 0.34%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                | 4         | 0.34%   |
| SK hynix BC511 512GB                                 | 4         | 0.34%   |
| Seagate ST750LM022 HN-M750MBB 752GB                  | 4         | 0.34%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 4         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 103    | 32.1%   |
| WDC                 | 50        | 67     | 18.45%  |
| Hitachi             | 43        | 60     | 15.87%  |
| Toshiba             | 34        | 41     | 12.55%  |
| HGST                | 27        | 43     | 9.96%   |
| Fujitsu             | 11        | 14     | 4.06%   |
| Samsung Electronics | 7         | 7      | 2.58%   |
| Unknown             | 2         | 2      | 0.74%   |
| JMicron Technology  | 2         | 5      | 0.74%   |
| Intenso             | 2         | 2      | 0.74%   |
| ASMT                | 2         | 2      | 0.74%   |
| ASMedia             | 2         | 2      | 0.74%   |
| RSH-339             | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 122       | 181    | 28.5%   |
| Kingston            | 81        | 96     | 18.93%  |
| SanDisk             | 41        | 51     | 9.58%   |
| Intel               | 24        | 29     | 5.61%   |
| Micron Technology   | 17        | 19     | 3.97%   |
| Crucial             | 17        | 19     | 3.97%   |
| WDC                 | 16        | 20     | 3.74%   |
| Apple               | 15        | 19     | 3.5%    |
| SK hynix            | 13        | 21     | 3.04%   |
| Transcend           | 11        | 11     | 2.57%   |
| Toshiba             | 10        | 11     | 2.34%   |
| A-DATA Technology   | 9         | 10     | 2.1%    |
| OCZ                 | 8         | 12     | 1.87%   |
| PNY                 | 5         | 5      | 1.17%   |
| LITEONIT            | 5         | 11     | 1.17%   |
| LITEON              | 5         | 9      | 1.17%   |
| China               | 4         | 6      | 0.93%   |
| BHT                 | 4         | 6      | 0.93%   |
| Verbatim            | 2         | 2      | 0.47%   |
| Patriot             | 2         | 2      | 0.47%   |
| Intenso             | 2         | 2      | 0.47%   |
| Corsair             | 2         | 2      | 0.47%   |
| WALRAM              | 1         | 1      | 0.23%   |
| Vaseky              | 1         | 1      | 0.23%   |
| Ramsta              | 1         | 1      | 0.23%   |
| OCZ-VERTEX          | 1         | 1      | 0.23%   |
| Netac               | 1         | 1      | 0.23%   |
| Kolink              | 1         | 1      | 0.23%   |
| Hewlett-Packard     | 1         | 1      | 0.23%   |
| GOODRAM             | 1         | 1      | 0.23%   |
| CT500MX5            | 1         | 1      | 0.23%   |
| CF400               | 1         | 1      | 0.23%   |
| ATP                 | 1         | 1      | 0.23%   |
| ASMT                | 1         | 1      | 0.23%   |
| Unknown             | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 405       | 557    | 37.71%  |
| NVMe    | 343       | 436    | 31.94%  |
| HDD     | 261       | 350    | 24.3%   |
| MMC     | 59        | 82     | 5.49%   |
| Unknown | 6         | 7      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 614       | 879    | 58.98%  |
| NVMe | 343       | 436    | 32.95%  |
| MMC  | 59        | 82     | 5.67%   |
| SAS  | 25        | 35     | 2.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 527       | 732    | 80.34%  |
| 0.51-1.0   | 119       | 162    | 18.14%  |
| 1.01-2.0   | 7         | 8      | 1.07%   |
| 4.01-10.0  | 2         | 3      | 0.3%    |
| 3.01-4.0   | 1         | 2      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 343       | 34.03%  |
| 251-500        | 235       | 23.31%  |
| 501-1000       | 123       | 12.2%   |
| 51-100         | 82        | 8.13%   |
| 1-20           | 73        | 7.24%   |
| 21-50          | 45        | 4.46%   |
| Unknown        | 44        | 4.37%   |
| 1001-2000      | 40        | 3.97%   |
| More than 3000 | 16        | 1.59%   |
| 2001-3000      | 7         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 449       | 42.48%  |
| 21-50          | 222       | 21%     |
| 101-250        | 113       | 10.69%  |
| 51-100         | 113       | 10.69%  |
| 251-500        | 65        | 6.15%   |
| Unknown        | 44        | 4.16%   |
| 501-1000       | 34        | 3.22%   |
| 1001-2000      | 7         | 0.66%   |
| More than 3000 | 5         | 0.47%   |
| 2001-3000      | 5         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 4         | 5      | 7.55%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 3      | 3.77%   |
| Intel SSDSC2BF240A5L 240GB                       | 2         | 3      | 3.77%   |
| WDC WD1600BJKT-75F4T0 160GB                      | 1         | 1      | 1.89%   |
| WDC WD10JUCT-63CYNY0 1TB                         | 1         | 1      | 1.89%   |
| Vaseky V800/60G 64GB                             | 1         | 1      | 1.89%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.89%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 1.89%   |
| Toshiba MK8052GSX 80GB                           | 1         | 1      | 1.89%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 1.89%   |
| Toshiba MK1652GSX 160GB                          | 1         | 1      | 1.89%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD          | 1         | 1      | 1.89%   |
| SK hynix PC401 NVMe 512GB                        | 1         | 1      | 1.89%   |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 1         | 1      | 1.89%   |
| SK hynix BC711 HFM256GD3JX013N 256GB             | 1         | 1      | 1.89%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.89%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.89%   |
| Seagate ST9250827AS 250GB                        | 1         | 1      | 1.89%   |
| Seagate ST9250320AS 250GB                        | 1         | 1      | 1.89%   |
| Seagate ST9160412AS 160GB                        | 1         | 1      | 1.89%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB             | 1         | 1      | 1.89%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1         | 1      | 1.89%   |
| SanDisk SSD i100 32GB                            | 1         | 1      | 1.89%   |
| SanDisk SD9TN8W-256G-1006 256GB SSD              | 1         | 1      | 1.89%   |
| Samsung Electronics MZNLN256HAJQ-000H1 256GB SSD | 1         | 1      | 1.89%   |
| Samsung Electronics MZMTD512HAGL-000L1 512GB SSD | 1         | 1      | 1.89%   |
| Samsung Electronics HM060HI 64GB                 | 1         | 1      | 1.89%   |
| OCZ TRION100 120GB SSD                           | 1         | 1      | 1.89%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 1.89%   |
| Kingston RBUSC180DS37128GH 128GB SSD             | 1         | 1      | 1.89%   |
| Kingston RBU-SNS8100S3128GD 128GB SSD            | 1         | 1      | 1.89%   |
| Intel SSDSC2BW240H6 240GB                        | 1         | 1      | 1.89%   |
| Intel SSDSC2BW180A3L 180GB                       | 1         | 1      | 1.89%   |
| Intel SSDSA2M080G2GC 80GB                        | 1         | 1      | 1.89%   |
| Hitachi HTS721010G9SA00 100GB                    | 1         | 4      | 1.89%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 1.89%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 4      | 1.89%   |
| Hitachi HTS543232L9A300 320GB                    | 1         | 2      | 1.89%   |
| Hitachi HTS543216L9SA02 160GB                    | 1         | 1      | 1.89%   |
| Hitachi HTS541680J9SA00 80GB                     | 1         | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 24.53%  |
| Toshiba             | 6         | 6      | 11.32%  |
| Hitachi             | 6         | 13     | 11.32%  |
| Intel               | 5         | 6      | 9.43%   |
| HGST                | 4         | 4      | 7.55%   |
| SK hynix            | 3         | 3      | 5.66%   |
| Samsung Electronics | 3         | 3      | 5.66%   |
| Kingston            | 3         | 3      | 5.66%   |
| WDC                 | 2         | 2      | 3.77%   |
| SanDisk             | 2         | 2      | 3.77%   |
| Fujitsu             | 2         | 3      | 3.77%   |
| Vaseky              | 1         | 1      | 1.89%   |
| OCZ                 | 1         | 1      | 1.89%   |
| ATP                 | 1         | 1      | 1.89%   |
| Apple               | 1         | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 39.39%  |
| Hitachi             | 6         | 13     | 18.18%  |
| Toshiba             | 5         | 5      | 15.15%  |
| HGST                | 4         | 4      | 12.12%  |
| WDC                 | 2         | 2      | 6.06%   |
| Fujitsu             | 2         | 3      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 43     | 62.26%  |
| SSD  | 18        | 19     | 33.96%  |
| NVMe | 2         | 2      | 3.77%   |

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
| Detected | 519       | 799    | 51.18%  |
| Works    | 442       | 569    | 43.59%  |
| Malfunc  | 53        | 64     | 5.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 617       | 57.13%  |
| Samsung Electronics              | 112       | 10.37%  |
| AMD                              | 101       | 9.35%   |
| SK hynix                         | 54        | 5%      |
| SanDisk                          | 36        | 3.33%   |
| Micron Technology                | 30        | 2.78%   |
| Kingston Technology Company      | 24        | 2.22%   |
| Toshiba America Info Systems     | 23        | 2.13%   |
| KIOXIA                           | 16        | 1.48%   |
| Nvidia                           | 14        | 1.3%    |
| Phison Electronics               | 10        | 0.93%   |
| Union Memory (Shenzhen)          | 6         | 0.56%   |
| Apple                            | 5         | 0.46%   |
| ADATA Technology                 | 5         | 0.46%   |
| Silicon Integrated Systems [SiS] | 4         | 0.37%   |
| Lenovo                           | 4         | 0.37%   |
| Silicon Motion                   | 3         | 0.28%   |
| Micron/Crucial Technology        | 3         | 0.28%   |
| Solid State Storage Technology   | 2         | 0.19%   |
| Seagate Technology               | 2         | 0.19%   |
| O2 Micro                         | 2         | 0.19%   |
| Marvell Technology Group         | 2         | 0.19%   |
| Yangtze Memory Technologies      | 1         | 0.09%   |
| VIA Technologies                 | 1         | 0.09%   |
| OCZ Technology Group             | 1         | 0.09%   |
| Lite-On Technology               | 1         | 0.09%   |
| JMicron Technology               | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 88        | 7.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 81        | 6.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 68        | 5.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 62        | 5.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 53        | 4.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 43        | 3.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 38        | 3.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 35        | 2.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 29        | 2.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 23        | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 23        | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 21        | 1.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 20        | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                              | 19        | 1.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 18        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 17        | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 15        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 14        | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 14        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 1.11%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 12        | 1.02%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 12        | 1.02%   |
| Intel SSD 660P Series                                                            | 12        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 12        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 12        | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 10        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 10        | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 10        | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 0.77%   |
| SK hynix BC511 NVMe SSD                                                          | 8         | 0.68%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 8         | 0.68%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 8         | 0.68%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 7         | 0.6%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 7         | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 640       | 56.84%  |
| NVMe | 343       | 30.46%  |
| IDE  | 82        | 7.28%   |
| RAID | 61        | 5.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 768       | 79.42%  |
| AMD          | 196       | 20.27%  |
| Qualcomm     | 1         | 0.1%    |
| CentaurHauls | 1         | 0.1%    |
| ARM          | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 24        | 2.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 20        | 2.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 19        | 1.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 16        | 1.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 16        | 1.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 15        | 1.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 14        | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 14        | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 14        | 1.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 10        | 1.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 10        | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 9         | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 9         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 8         | 0.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 8         | 0.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 8         | 0.83%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 8         | 0.83%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 7         | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 7         | 0.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 7         | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 7         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 7         | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 7         | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 7         | 0.72%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 6         | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 6         | 0.62%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 6         | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 6         | 0.62%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 6         | 0.62%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 6         | 0.62%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 6         | 0.62%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 6         | 0.62%   |
| AMD Ryzen 5 5600H with Radeon Graphics      | 6         | 0.62%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 5         | 0.52%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 5         | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 5         | 0.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 5         | 0.52%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 5         | 0.52%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 0.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 282       | 29.16%  |
| Intel Core i7                  | 190       | 19.65%  |
| Other                          | 73        | 7.55%   |
| Intel Core 2 Duo               | 52        | 5.38%   |
| Intel Celeron                  | 51        | 5.27%   |
| Intel Core i3                  | 50        | 5.17%   |
| AMD Ryzen 5                    | 36        | 3.72%   |
| AMD Ryzen 7                    | 27        | 2.79%   |
| Intel Pentium                  | 23        | 2.38%   |
| Intel Atom                     | 14        | 1.45%   |
| AMD Ryzen 7 PRO                | 14        | 1.45%   |
| Intel Pentium Dual-Core        | 12        | 1.24%   |
| AMD Ryzen 9                    | 11        | 1.14%   |
| AMD Ryzen 3                    | 10        | 1.03%   |
| AMD Ryzen 5 PRO                | 9         | 0.93%   |
| AMD E1                         | 9         | 0.93%   |
| AMD A8                         | 9         | 0.93%   |
| AMD A10                        | 8         | 0.83%   |
| Intel Genuine                  | 7         | 0.72%   |
| AMD E2                         | 7         | 0.72%   |
| AMD A4                         | 7         | 0.72%   |
| Intel Core 2                   | 5         | 0.52%   |
| AMD A6                         | 5         | 0.52%   |
| Intel Pentium Dual             | 4         | 0.41%   |
| AMD Athlon                     | 4         | 0.41%   |
| Intel Core i9                  | 3         | 0.31%   |
| Intel Celeron Dual-Core        | 3         | 0.31%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.31%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.31%   |
| AMD Ryzen 3 PRO                | 3         | 0.31%   |
| AMD Athlon II Dual-Core        | 3         | 0.31%   |
| Intel Core m7                  | 2         | 0.21%   |
| Intel Core m5                  | 2         | 0.21%   |
| Intel Core Duo                 | 2         | 0.21%   |
| Intel Celeron M                | 2         | 0.21%   |
| AMD Turion                     | 2         | 0.21%   |
| AMD Mobile Sempron             | 2         | 0.21%   |
| AMD E                          | 2         | 0.21%   |
| AMD A12                        | 2         | 0.21%   |
| Intel Xeon                     | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 519       | 53.62%  |
| 4      | 300       | 30.99%  |
| 8      | 58        | 5.99%   |
| 6      | 48        | 4.96%   |
| 1      | 16        | 1.65%   |
| 10     | 9         | 0.93%   |
| 14     | 7         | 0.72%   |
| 16     | 4         | 0.41%   |
| 24     | 3         | 0.31%   |
| 12     | 3         | 0.31%   |
| 5      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 967       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 710       | 73.35%  |
| 1      | 258       | 26.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 948       | 97.93%  |
| 32-bit         | 12        | 1.24%   |
| Unknown        | 7         | 0.72%   |
| 64-bit         | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 383       | 38.15%  |
| 0x206a7    | 51        | 5.08%   |
| 0x306a9    | 42        | 4.18%   |
| 0x806ec    | 34        | 3.39%   |
| 0x40651    | 31        | 3.09%   |
| 0x406e3    | 30        | 2.99%   |
| 0x1067a    | 26        | 2.59%   |
| 0x806ea    | 25        | 2.49%   |
| 0x806e9    | 17        | 1.69%   |
| 0x306d4    | 17        | 1.69%   |
| 0x306c3    | 17        | 1.69%   |
| 0x30678    | 17        | 1.69%   |
| 0x10676    | 16        | 1.59%   |
| 0x906e9    | 14        | 1.39%   |
| 0x20655    | 14        | 1.39%   |
| 0x806c1    | 13        | 1.29%   |
| 0xa0652    | 11        | 1.1%    |
| 0x506e3    | 11        | 1.1%    |
| 0x6fd      | 10        | 1%      |
| 0x20652    | 10        | 1%      |
| 0x08600106 | 10        | 1%      |
| 0x906ea    | 9         | 0.9%    |
| 0x406c4    | 9         | 0.9%    |
| 0x806eb    | 8         | 0.8%    |
| 0x706e5    | 8         | 0.8%    |
| 0x6fb      | 8         | 0.8%    |
| 0x08108102 | 8         | 0.8%    |
| 0x506c9    | 7         | 0.7%    |
| 0x06001119 | 7         | 0.7%    |
| 0x0a50000d | 6         | 0.6%    |
| 0x0a50000c | 6         | 0.6%    |
| 0x08108109 | 6         | 0.6%    |
| 0x0810100b | 6         | 0.6%    |
| 0x06006705 | 6         | 0.6%    |
| 0x05000119 | 6         | 0.6%    |
| 0x806d1    | 5         | 0.5%    |
| 0x406c3    | 5         | 0.5%    |
| 0x0a50000b | 5         | 0.5%    |
| 0x08608103 | 5         | 0.5%    |
| 0x02000032 | 5         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 179       | 18.51%  |
| Haswell           | 80        | 8.27%   |
| SandyBridge       | 77        | 7.96%   |
| IvyBridge         | 67        | 6.93%   |
| Skylake           | 64        | 6.62%   |
| Penryn            | 53        | 5.48%   |
| Unknown           | 48        | 4.96%   |
| Silvermont        | 37        | 3.83%   |
| Westmere          | 32        | 3.31%   |
| Core              | 31        | 3.21%   |
| TigerLake         | 28        | 2.9%    |
| Broadwell         | 28        | 2.9%    |
| Zen+              | 27        | 2.79%   |
| Zen 3             | 26        | 2.69%   |
| Zen 2             | 25        | 2.59%   |
| Icelake           | 16        | 1.65%   |
| Alderlake Hybrid  | 16        | 1.65%   |
| CometLake         | 15        | 1.55%   |
| Puma              | 14        | 1.45%   |
| Excavator         | 12        | 1.24%   |
| Piledriver        | 11        | 1.14%   |
| Goldmont          | 10        | 1.03%   |
| Goldmont plus     | 9         | 0.93%   |
| Bobcat            | 9         | 0.93%   |
| Zen               | 8         | 0.83%   |
| K8 Hammer         | 8         | 0.83%   |
| K8 & K10 hybrid   | 8         | 0.83%   |
| P6                | 7         | 0.72%   |
| Bonnell           | 5         | 0.52%   |
| K10               | 4         | 0.41%   |
| Jaguar            | 4         | 0.41%   |
| Steamroller       | 3         | 0.31%   |
| Nehalem           | 3         | 0.31%   |
| K10 Llano         | 2         | 0.21%   |
| Meteorlake Hybrid | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 699       | 59.39%  |
| Nvidia                           | 244       | 20.73%  |
| AMD                              | 229       | 19.46%  |
| Silicon Integrated Systems [SiS] | 4         | 0.34%   |
| VIA Technologies                 | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 69        | 5.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 5.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 49        | 4%      |
| Intel UHD Graphics 620                                                                   | 44        | 3.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 3.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 3.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 2.45%   |
| Intel HD Graphics 620                                                                    | 30        | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 29        | 2.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 2.28%   |
| Intel HD Graphics 5500                                                                   | 25        | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 1.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 1.88%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 23        | 1.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 22        | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 1.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.31%   |
| Intel HD Graphics 630                                                                    | 13        | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.06%   |
| Intel HD Graphics 530                                                                    | 12        | 0.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.9%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 0.82%   |
| AMD Phoenix1                                                                             | 10        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.65%   |
| AMD Lucienne                                                                             | 8         | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.57%   |
| Intel HD Graphics 500                                                                    | 7         | 0.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.57%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 7         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 513       | 52.89%  |
| Intel + Nvidia | 159       | 16.39%  |
| 1 x AMD        | 154       | 15.88%  |
| 1 x Nvidia     | 55        | 5.67%   |
| AMD + Nvidia   | 30        | 3.09%   |
| Intel + AMD    | 25        | 2.58%   |
| 2 x AMD        | 19        | 1.96%   |
| 2 x Intel      | 6         | 0.62%   |
| 1 x SiS        | 4         | 0.41%   |
| Other          | 2         | 0.21%   |
| 2 x Nvidia     | 2         | 0.21%   |
| 1 x VIA        | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 817       | 83.62%  |
| Proprietary | 127       | 13%     |
| Unknown     | 33        | 3.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 671       | 68.54%  |
| 0.01-0.5   | 110       | 11.24%  |
| 1.01-2.0   | 80        | 8.17%   |
| 0.51-1.0   | 57        | 5.82%   |
| 3.01-4.0   | 40        | 4.09%   |
| 7.01-8.0   | 9         | 0.92%   |
| 5.01-6.0   | 6         | 0.61%   |
| 2.01-3.0   | 3         | 0.31%   |
| 16.01-24.0 | 2         | 0.2%    |
| 8.01-16.0  | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 211       | 19.41%  |
| LG Display              | 175       | 16.1%   |
| Samsung Electronics     | 142       | 13.06%  |
| Chimei Innolux          | 124       | 11.41%  |
| BOE                     | 97        | 8.92%   |
| Lenovo                  | 55        | 5.06%   |
| Apple                   | 33        | 3.04%   |
| Sharp                   | 23        | 2.12%   |
| Dell                    | 23        | 2.12%   |
| Hewlett-Packard         | 21        | 1.93%   |
| InfoVision              | 20        | 1.84%   |
| CSO                     | 17        | 1.56%   |
| BenQ                    | 14        | 1.29%   |
| Acer                    | 14        | 1.29%   |
| Chi Mei Optoelectronics | 13        | 1.2%    |
| PANDA                   | 11        | 1.01%   |
| LG Philips              | 10        | 0.92%   |
| Vestel Elektronik       | 8         | 0.74%   |
| Ancor Communications    | 8         | 0.74%   |
| Valve                   | 6         | 0.55%   |
| Goldstar                | 6         | 0.55%   |
| Sony                    | 4         | 0.37%   |
| IBM                     | 4         | 0.37%   |
| CPT                     | 4         | 0.37%   |
| ASUSTek Computer        | 4         | 0.37%   |
| ViewSonic               | 3         | 0.28%   |
| Toshiba                 | 3         | 0.28%   |
| LGD                     | 3         | 0.28%   |
| TMX                     | 2         | 0.18%   |
| Quanta Display          | 2         | 0.18%   |
| Pixio                   | 2         | 0.18%   |
| Panasonic               | 2         | 0.18%   |
| Mi                      | 2         | 0.18%   |
| Fujitsu Siemens         | 2         | 0.18%   |
| YTH                     | 1         | 0.09%   |
| STA                     | 1         | 0.09%   |
| Philips                 | 1         | 0.09%   |
| OEM                     | 1         | 0.09%   |
| MSI                     | 1         | 0.09%   |
| Marantz                 | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.91%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 8         | 0.73%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 8         | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.64%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.55%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch               | 6         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 0.55%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 6         | 0.55%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 5         | 0.46%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 5         | 0.46%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 5         | 0.46%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.36%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 4         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 4         | 0.36%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.36%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 4         | 0.36%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.36%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 4         | 0.36%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 4         | 0.36%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 4         | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.36%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch           | 4         | 0.36%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 4         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 454       | 43.65%  |
| 1366x768 (WXGA)    | 221       | 21.25%  |
| 1600x900 (HD+)     | 69        | 6.63%   |
| 3840x2160 (4K)     | 43        | 4.13%   |
| 2560x1440 (QHD)    | 40        | 3.85%   |
| 1280x800 (WXGA)    | 37        | 3.56%   |
| 1440x900 (WXGA+)   | 33        | 3.17%   |
| 1920x1200 (WUXGA)  | 31        | 2.98%   |
| 2560x1600          | 20        | 1.92%   |
| 1680x1050 (WSXGA+) | 17        | 1.63%   |
| 2880x1800          | 16        | 1.54%   |
| 3840x2400          | 9         | 0.87%   |
| 3440x1440          | 9         | 0.87%   |
| 800x1280           | 6         | 0.58%   |
| 1280x1024 (SXGA)   | 6         | 0.58%   |
| 1024x600           | 5         | 0.48%   |
| 3200x2000          | 4         | 0.38%   |
| 3200x1800 (QHD+)   | 3         | 0.29%   |
| 2256x1504          | 2         | 0.19%   |
| 1600x1200          | 2         | 0.19%   |
| 1400x1050          | 2         | 0.19%   |
| 1360x768           | 2         | 0.19%   |
| 3840x1200          | 1         | 0.1%    |
| 3456x2160          | 1         | 0.1%    |
| 3000x2000          | 1         | 0.1%    |
| 2304x1440          | 1         | 0.1%    |
| 2160x1440          | 1         | 0.1%    |
| 1920x540           | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1680x945           | 1         | 0.1%    |
| 1280x720 (HD)      | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 359       | 32.82%  |
| 14      | 178       | 16.27%  |
| 13      | 173       | 15.81%  |
| 17      | 76        | 6.95%   |
| 12      | 46        | 4.2%    |
| 27      | 45        | 4.11%   |
| 24      | 33        | 3.02%   |
| 23      | 29        | 2.65%   |
| 16      | 22        | 2.01%   |
| 11      | 17        | 1.55%   |
| 31      | 16        | 1.46%   |
| 21      | 14        | 1.28%   |
| Unknown | 11        | 1.01%   |
| 84      | 10        | 0.91%   |
| 34      | 9         | 0.82%   |
| 18      | 9         | 0.82%   |
| 7       | 6         | 0.55%   |
| 10      | 5         | 0.46%   |
| 32      | 4         | 0.37%   |
| 54      | 3         | 0.27%   |
| 40      | 3         | 0.27%   |
| 28      | 3         | 0.27%   |
| 22      | 3         | 0.27%   |
| 19      | 3         | 0.27%   |
| 72      | 2         | 0.18%   |
| 58      | 2         | 0.18%   |
| 55      | 2         | 0.18%   |
| 43      | 2         | 0.18%   |
| 20      | 2         | 0.18%   |
| 86      | 1         | 0.09%   |
| 57      | 1         | 0.09%   |
| 49      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 25      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 632       | 58.25%  |
| 201-300     | 157       | 14.47%  |
| 501-600     | 98        | 9.03%   |
| 351-400     | 91        | 8.39%   |
| 601-700     | 26        | 2.4%    |
| 401-500     | 23        | 2.12%   |
| 701-800     | 13        | 1.2%    |
| 1501-2000   | 12        | 1.11%   |
| 1001-1500   | 12        | 1.11%   |
| Unknown     | 11        | 1.01%   |
| 1-100       | 6         | 0.55%   |
| 801-900     | 3         | 0.28%   |
| 901-1000    | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 758       | 78.22%  |
| 16/10   | 163       | 16.82%  |
| 3/2     | 10        | 1.03%   |
| 21/9    | 9         | 0.93%   |
| 5/4     | 8         | 0.83%   |
| Unknown | 7         | 0.72%   |
| 4/3     | 4         | 0.41%   |
| 0.67    | 4         | 0.41%   |
| 32/9    | 2         | 0.21%   |
| 0.62    | 2         | 0.21%   |
| 3.20    | 1         | 0.1%    |
| 0.56    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 356       | 32.72%  |
| 81-90          | 283       | 26.01%  |
| 71-80          | 66        | 6.07%   |
| 121-130        | 63        | 5.79%   |
| 201-250        | 58        | 5.33%   |
| 61-70          | 46        | 4.23%   |
| 301-350        | 46        | 4.23%   |
| 351-500        | 33        | 3.03%   |
| 111-120        | 24        | 2.21%   |
| More than 1000 | 21        | 1.93%   |
| 51-60          | 17        | 1.56%   |
| 251-300        | 15        | 1.38%   |
| 131-140        | 11        | 1.01%   |
| Unknown        | 11        | 1.01%   |
| 151-200        | 9         | 0.83%   |
| 141-150        | 9         | 0.83%   |
| 501-1000       | 7         | 0.64%   |
| 1-40           | 6         | 0.55%   |
| 41-50          | 5         | 0.46%   |
| 91-100         | 2         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 464       | 43.12%  |
| 101-120       | 277       | 25.74%  |
| 51-100        | 166       | 15.43%  |
| 161-240       | 107       | 9.94%   |
| More than 240 | 36        | 3.35%   |
| 1-50          | 15        | 1.39%   |
| Unknown       | 11        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 779       | 78.61%  |
| 2     | 166       | 16.75%  |
| 0     | 31        | 3.13%   |
| 3     | 15        | 1.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 551       | 36.27%  |
| Realtek Semiconductor                  | 402       | 26.46%  |
| Qualcomm Atheros                       | 168       | 11.06%  |
| Broadcom                               | 88        | 5.79%   |
| MediaTek                               | 39        | 2.57%   |
| Ericsson Business Mobile Networks      | 26        | 1.71%   |
| Sierra Wireless                        | 24        | 1.58%   |
| Hewlett-Packard                        | 23        | 1.51%   |
| Broadcom Limited                       | 20        | 1.32%   |
| Marvell Technology Group               | 18        | 1.18%   |
| Ralink                                 | 15        | 0.99%   |
| Huawei Technologies                    | 13        | 0.86%   |
| TP-Link                                | 12        | 0.79%   |
| Dell                                   | 11        | 0.72%   |
| Nvidia                                 | 10        | 0.66%   |
| Lenovo                                 | 10        | 0.66%   |
| Fibocom                                | 10        | 0.66%   |
| Qualcomm                               | 8         | 0.53%   |
| Samsung Electronics                    | 7         | 0.46%   |
| DisplayLink                            | 7         | 0.46%   |
| ASUSTek Computer                       | 6         | 0.39%   |
| ASIX Electronics                       | 6         | 0.39%   |
| OPPO Electronics                       | 5         | 0.33%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.33%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.26%   |
| Ralink Technology                      | 4         | 0.26%   |
| Qualcomm Technologies                  | 3         | 0.2%    |
| ZyXEL Communications                   | 2         | 0.13%   |
| Motorola PCS                           | 2         | 0.13%   |
| Xiaomi                                 | 1         | 0.07%   |
| Van Ooijen Technische Informatica      | 1         | 0.07%   |
| U-Blox                                 | 1         | 0.07%   |
| Texas Instruments                      | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| SEGGER                                 | 1         | 0.07%   |
| Research In Motion                     | 1         | 0.07%   |
| Qualcomm Atheros Communications        | 1         | 0.07%   |
| Primax Electronics                     | 1         | 0.07%   |
| Microsoft                              | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 270       | 13.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 67        | 3.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 58        | 2.98%   |
| Intel Wireless 8265 / 8275                                             | 54        | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 48        | 2.47%   |
| Intel Wireless 8260                                                    | 41        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 37        | 1.9%    |
| Intel Wireless 7260                                                    | 37        | 1.9%    |
| Intel Wireless 7265                                                    | 34        | 1.75%   |
| Intel Wi-Fi 6 AX200                                                    | 32        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 29        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 27        | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 24        | 1.23%   |
| Intel Wi-Fi 6 AX201                                                    | 23        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 23        | 1.18%   |
| Intel Ethernet Connection (4) I219-V                                   | 21        | 1.08%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                  | 18        | 0.93%   |
| Intel 82577LM Gigabit Network Connection                               | 18        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 17        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 17        | 0.87%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.87%   |
| Intel Ethernet Connection (6) I219-V                                   | 17        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 16        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 16        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 15        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                         | 15        | 0.77%   |
| Intel Ethernet Connection I219-V                                       | 14        | 0.72%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 14        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 13        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 0.67%   |
| Intel Centrino Advanced-N 6235                                         | 13        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 13        | 0.67%   |
| Intel 82567LM Gigabit Network Connection                               | 13        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 12        | 0.62%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 12        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 12        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 527       | 52.02%  |
| Qualcomm Atheros                | 151       | 14.91%  |
| Realtek Semiconductor           | 122       | 12.04%  |
| Broadcom                        | 69        | 6.81%   |
| MediaTek                        | 31        | 3.06%   |
| Sierra Wireless                 | 24        | 2.37%   |
| Ralink                          | 15        | 1.48%   |
| Broadcom Limited                | 14        | 1.38%   |
| TP-Link                         | 11        | 1.09%   |
| Fibocom                         | 10        | 0.99%   |
| Hewlett-Packard                 | 8         | 0.79%   |
| Qualcomm                        | 7         | 0.69%   |
| Dell                            | 6         | 0.59%   |
| ASUSTek Computer                | 5         | 0.49%   |
| Ralink Technology               | 4         | 0.39%   |
| ZyXEL Communications            | 2         | 0.2%    |
| Qualcomm Technologies           | 2         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.1%    |
| Microsoft                       | 1         | 0.1%    |
| Linksys                         | 1         | 0.1%    |
| Fujitsu Siemens Computers       | 1         | 0.1%    |
| Arduino SA                      | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 54        | 5.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 48        | 4.73%   |
| Intel Wireless 8260                                                     | 41        | 4.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 37        | 3.65%   |
| Intel Wireless 7260                                                     | 37        | 3.65%   |
| Intel Wireless 7265                                                     | 34        | 3.35%   |
| Intel Wi-Fi 6 AX200                                                     | 32        | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 2.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 2.37%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 16        | 1.58%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 1.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 15        | 1.48%   |
| Intel Centrino Ultimate-N 6300                                          | 15        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.28%   |
| Intel Centrino Advanced-N 6235                                          | 13        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 12        | 1.18%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 12        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.18%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 11        | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 1.08%   |
| Intel Wireless 3165                                                     | 11        | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.08%   |
| Intel Wireless 3160                                                     | 10        | 0.99%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 10        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 0.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 8         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 375       | 43.55%  |
| Intel                                  | 306       | 35.54%  |
| Broadcom                               | 35        | 4.07%   |
| Qualcomm Atheros                       | 34        | 3.95%   |
| Marvell Technology Group               | 18        | 2.09%   |
| Nvidia                                 | 10        | 1.16%   |
| Lenovo                                 | 10        | 1.16%   |
| Huawei Technologies                    | 10        | 1.16%   |
| MediaTek                               | 8         | 0.93%   |
| DisplayLink                            | 7         | 0.81%   |
| Broadcom Limited                       | 6         | 0.7%    |
| ASIX Electronics                       | 6         | 0.7%    |
| Samsung Electronics                    | 5         | 0.58%   |
| OPPO Electronics                       | 5         | 0.58%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.46%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.46%   |
| Hewlett-Packard                        | 4         | 0.46%   |
| TP-Link                                | 2         | 0.23%   |
| Motorola PCS                           | 2         | 0.23%   |
| Xiaomi                                 | 1         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.12%   |
| Research In Motion                     | 1         | 0.12%   |
| Qualcomm Technologies                  | 1         | 0.12%   |
| Qualcomm                               | 1         | 0.12%   |
| ICS Advent                             | 1         | 0.12%   |
| HMD Global                             | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| Attansic Technology                    | 1         | 0.12%   |
| ASUSTek Computer                       | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 270       | 31.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 67        | 7.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 58        | 6.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 3.45%   |
| Intel Ethernet Connection (4) I219-V                                   | 21        | 2.41%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 2.18%   |
| Intel Ethernet Connection (4) I219-LM                                  | 18        | 2.07%   |
| Intel 82577LM Gigabit Network Connection                               | 18        | 2.07%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 1.95%   |
| Intel Ethernet Connection (6) I219-V                                   | 17        | 1.95%   |
| Intel Ethernet Connection I219-V                                       | 14        | 1.61%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 1.49%   |
| Intel 82567LM Gigabit Network Connection                               | 13        | 1.49%   |
| Intel 82566MM Gigabit Network Connection                               | 11        | 1.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 8         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.69%   |
| Huawei FOA-LX9                                                         | 6         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 5         | 0.57%   |
| Intel 82573L Gigabit Ethernet Controller                               | 5         | 0.57%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 5         | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 5         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.46%   |
| OPPO OnePlus Nord 4                                                    | 4         | 0.46%   |
| OnePlus (Shenzhen) OnePlus                                             | 4         | 0.46%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 0.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.46%   |
| MediaTek Infinix SMART 5                                               | 4         | 0.46%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 938       | 52.26%  |
| Ethernet | 798       | 44.46%  |
| Modem    | 57        | 3.18%   |
| Unknown  | 2         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 767       | 76.02%  |
| Ethernet | 242       | 23.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 728       | 74.97%  |
| 1     | 219       | 22.55%  |
| 3     | 13        | 1.34%   |
| 0     | 11        | 1.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 757       | 76.31%  |
| Yes  | 235       | 23.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 375       | 47.35%  |
| Realtek Semiconductor           | 76        | 9.6%    |
| Broadcom                        | 73        | 9.22%   |
| Qualcomm Atheros Communications | 50        | 6.31%   |
| IMC Networks                    | 45        | 5.68%   |
| Foxconn / Hon Hai               | 40        | 5.05%   |
| Apple                           | 25        | 3.16%   |
| Lite-On Technology              | 20        | 2.53%   |
| Hewlett-Packard                 | 18        | 2.27%   |
| Cambridge Silicon Radio         | 14        | 1.77%   |
| Dell                            | 12        | 1.52%   |
| Ralink                          | 11        | 1.39%   |
| Askey Computer                  | 10        | 1.26%   |
| USI                             | 4         | 0.51%   |
| Foxconn International           | 4         | 0.51%   |
| Toshiba                         | 3         | 0.38%   |
| ASUSTek Computer                | 3         | 0.38%   |
| Realtek                         | 2         | 0.25%   |
| Fujitsu                         | 2         | 0.25%   |
| Chicony Electronics             | 2         | 0.25%   |
| Taiyo Yuden                     | 1         | 0.13%   |
| MediaTek                        | 1         | 0.13%   |
| Alps Electric                   | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 179       | 22.6%   |
| Intel AX201 Bluetooth                               | 59        | 7.45%   |
| Realtek Bluetooth Radio                             | 40        | 5.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 36        | 4.55%   |
| Intel AX200 Bluetooth                               | 33        | 4.17%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 2.4%    |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 2.27%   |
| Intel AX211 Bluetooth                               | 18        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 2.15%   |
| IMC Networks Bluetooth Radio                        | 17        | 2.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14        | 1.77%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 1.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 1.52%   |
| Apple Bluetooth Host Controller                     | 12        | 1.52%   |
| Ralink RT3290 Bluetooth                             | 11        | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 1.39%   |
| IMC Networks Wireless_Device                        | 11        | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 1.26%   |
| Askey Bluetooth Device                              | 10        | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.14%   |
| IMC Networks Bluetooth Device                       | 9         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 1.14%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 1.14%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 1.14%   |
| Realtek RTL8723B Bluetooth                          | 8         | 1.01%   |
| Apple Bluetooth USB Host Controller                 | 8         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.88%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 0.88%   |
| Broadcom HP Portable Bumble Bee                     | 7         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 7         | 0.88%   |
| Lite-On Bluetooth Device                            | 6         | 0.76%   |
| Intel AX210 Bluetooth                               | 6         | 0.76%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.63%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.63%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.63%   |
| USI Bluetooth Device                                | 4         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 748       | 63.88%  |
| AMD                              | 202       | 17.25%  |
| Nvidia                           | 146       | 12.47%  |
| Lenovo                           | 8         | 0.68%   |
| Realtek Semiconductor            | 6         | 0.51%   |
| GN Netcom                        | 6         | 0.51%   |
| C-Media Electronics              | 5         | 0.43%   |
| Silicon Integrated Systems [SiS] | 4         | 0.34%   |
| Logitech                         | 4         | 0.34%   |
| Kingston Technology              | 3         | 0.26%   |
| Hewlett-Packard                  | 3         | 0.26%   |
| Turtle Beach                     | 2         | 0.17%   |
| RODE Microphones                 | 2         | 0.17%   |
| Plantronics                      | 2         | 0.17%   |
| Microsoft                        | 2         | 0.17%   |
| Focusrite-Novation               | 2         | 0.17%   |
| Creative Technology              | 2         | 0.17%   |
| Apple                            | 2         | 0.17%   |
| ZOOM                             | 1         | 0.09%   |
| Yamaha                           | 1         | 0.09%   |
| VIA Technologies                 | 1         | 0.09%   |
| Texas Instruments                | 1         | 0.09%   |
| Sony                             | 1         | 0.09%   |
| ROCCAT                           | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.09%   |
| Numark                           | 1         | 0.09%   |
| No brand                         | 1         | 0.09%   |
| Native Instruments               | 1         | 0.09%   |
| Micro Star International         | 1         | 0.09%   |
| Huawei Technologies              | 1         | 0.09%   |
| GYROCOM C&C                      | 1         | 0.09%   |
| Generalplus Technology           | 1         | 0.09%   |
| DSEA A/S                         | 1         | 0.09%   |
| DigiTech                         | 1         | 0.09%   |
| Dell                             | 1         | 0.09%   |
| Corsair                          | 1         | 0.09%   |
| Cambridge Audio                  | 1         | 0.09%   |
| BEHRINGER International          | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |
| Antlion Audio                    | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 132       | 9.21%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 114       | 7.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 73        | 5.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 71        | 4.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 48        | 3.35%   |
| Intel 8 Series HD Audio Controller                                                                | 48        | 3.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 47        | 3.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 3%      |
| AMD FCH Azalia Controller                                                                         | 41        | 2.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 40        | 2.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 35        | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 31        | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 1.95%   |
| Intel Broadwell-U Audio Controller                                                                | 28        | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 27        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 26        | 1.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 26        | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 24        | 1.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 24        | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 22        | 1.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 1.19%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 0.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 0.84%   |
| AMD Trinity HDMI Audio Controller                                                                 | 11        | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 10        | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 10        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.7%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 9         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.63%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 9         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 228       | 34.55%  |
| SK hynix            | 164       | 24.85%  |
| Micron Technology   | 83        | 12.58%  |
| Kingston            | 56        | 8.48%   |
| Unknown             | 48        | 7.27%   |
| Elpida              | 18        | 2.73%   |
| Ramaxel Technology  | 13        | 1.97%   |
| A-DATA Technology   | 11        | 1.67%   |
| Crucial             | 10        | 1.52%   |
| Corsair             | 8         | 1.21%   |
| Nanya Technology    | 6         | 0.91%   |
| G.Skill             | 3         | 0.45%   |
| Qimonda             | 2         | 0.3%    |
| ChangXin Memory     | 2         | 0.3%    |
| Unknown             | 2         | 0.3%    |
| Unknown (ABCD)      | 1         | 0.15%   |
| Unknown (0E97)      | 1         | 0.15%   |
| Toshiba             | 1         | 0.15%   |
| PUSKILL             | 1         | 0.15%   |
| pqi                 | 1         | 0.15%   |
| 48spaces            | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 13        | 1.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 12        | 1.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 12        | 1.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 10        | 1.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 10        | 1.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 10        | 1.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 10        | 1.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 9         | 1.26%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 7         | 0.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                | 7         | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s      | 7         | 0.98%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 6         | 0.84%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 6         | 0.84%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 6         | 0.84%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 5         | 0.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 5         | 0.7%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s     | 5         | 0.7%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s     | 5         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s      | 5         | 0.7%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s      | 5         | 0.7%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 5         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                         | 4         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 4         | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 4         | 0.56%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 4         | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 4         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 4         | 0.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s      | 4         | 0.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s     | 4         | 0.56%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s      | 4         | 0.56%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s | 4         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                | 3         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                      | 3         | 0.42%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s               | 3         | 0.42%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s       | 3         | 0.42%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s              | 3         | 0.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 3         | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s     | 3         | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 3         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 234       | 40.63%  |
| DDR3    | 194       | 33.68%  |
| DDR2    | 45        | 7.81%   |
| LPDDR3  | 26        | 4.51%   |
| LPDDR4  | 25        | 4.34%   |
| DDR5    | 16        | 2.78%   |
| SDRAM   | 15        | 2.6%    |
| LPDDR5  | 11        | 1.91%   |
| Unknown | 5         | 0.87%   |
| DDR     | 3         | 0.52%   |
| DRAM    | 2         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 517       | 90.7%   |
| Row Of Chips | 46        | 8.07%   |
| Chip         | 5         | 0.88%   |
| Unknown      | 2         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 225       | 36.12%  |
| 4096  | 172       | 27.61%  |
| 16384 | 102       | 16.37%  |
| 2048  | 79        | 12.68%  |
| 1024  | 24        | 3.85%   |
| 32768 | 19        | 3.05%   |
| 512   | 1         | 0.16%   |
| 256   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 130       | 21.04%  |
| 2667    | 104       | 16.83%  |
| 3200    | 89        | 14.4%   |
| 2400    | 41        | 6.63%   |
| 1334    | 37        | 5.99%   |
| 2133    | 36        | 5.83%   |
| 667     | 29        | 4.69%   |
| 1333    | 17        | 2.75%   |
| Unknown | 16        | 2.59%   |
| 4267    | 12        | 1.94%   |
| 1867    | 12        | 1.94%   |
| 1067    | 12        | 1.94%   |
| 4800    | 10        | 1.62%   |
| 800     | 10        | 1.62%   |
| 5600    | 9         | 1.46%   |
| 7500    | 7         | 1.13%   |
| 4199    | 7         | 1.13%   |
| 2048    | 7         | 1.13%   |
| 3266    | 6         | 0.97%   |
| 8400    | 4         | 0.65%   |
| 4266    | 4         | 0.65%   |
| 1066    | 4         | 0.65%   |
| 6400    | 3         | 0.49%   |
| 3733    | 3         | 0.49%   |
| 975     | 3         | 0.49%   |
| 533     | 2         | 0.32%   |
| 7467    | 1         | 0.16%   |
| 2933    | 1         | 0.16%   |
| 1639    | 1         | 0.16%   |
| 333     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 30.77%  |
| Samsung Electronics   | 2         | 15.38%  |
| Canon                 | 2         | 15.38%  |
| Seiko Epson           | 1         | 7.69%   |
| Pantum                | 1         | 7.69%   |
| Lexmark International | 1         | 7.69%   |
| Dell                  | 1         | 7.69%   |
| Brother Industries    | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-510 Series         | 1         | 7.69%   |
| Samsung M2020 Series              | 1         | 7.69%   |
| Samsung C43x Series               | 1         | 7.69%   |
| Pantum P2500W series              | 1         | 7.69%   |
| Lexmark International 2400 series | 1         | 7.69%   |
| HP OfficeJet Pro 6970             | 1         | 7.69%   |
| HP LaserJet P2055 series          | 1         | 7.69%   |
| HP LaserJet 1018                  | 1         | 7.69%   |
| HP DeskJet 2130 series            | 1         | 7.69%   |
| Dell Laser Printer 1720           | 1         | 7.69%   |
| Canon PIXMA MG3100 Series         | 1         | 7.69%   |
| Canon LBP6000                     | 1         | 7.69%   |
| Brother DCP-7055 scanner/printer  | 1         | 7.69%   |

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
| Chicony Electronics                    | 282       | 33.49%  |
| IMC Networks                           | 83        | 9.86%   |
| Bison Electronics                      | 56        | 6.65%   |
| Realtek Semiconductor                  | 53        | 6.29%   |
| Microdia                               | 51        | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 4.87%   |
| Quanta                                 | 37        | 4.39%   |
| Sunplus Innovation Technology          | 31        | 3.68%   |
| Suyin                                  | 29        | 3.44%   |
| Lite-On Technology                     | 22        | 2.61%   |
| Syntek                                 | 20        | 2.38%   |
| Apple                                  | 19        | 2.26%   |
| Logitech                               | 18        | 2.14%   |
| Acer                                   | 14        | 1.66%   |
| Lenovo                                 | 13        | 1.54%   |
| Luxvisions Innotech Limited            | 12        | 1.43%   |
| Silicon Motion                         | 11        | 1.31%   |
| Sonix Technology                       | 8         | 0.95%   |
| Alcor Micro                            | 6         | 0.71%   |
| Samsung Electronics                    | 5         | 0.59%   |
| Primax Electronics                     | 5         | 0.59%   |
| Z-Star Microelectronics                | 4         | 0.48%   |
| Shinetech                              | 4         | 0.48%   |
| ALi                                    | 4         | 0.48%   |
| Ricoh                                  | 3         | 0.36%   |
| Microsoft                              | 2         | 0.24%   |
| Importek                               | 2         | 0.24%   |
| DigiTech                               | 2         | 0.24%   |
| STEREOLABS                             | 1         | 0.12%   |
| OPPO Electronics                       | 1         | 0.12%   |
| Omnivision                             | 1         | 0.12%   |
| LG Electronics                         | 1         | 0.12%   |
| Anker PowerConf C200                   | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 77        | 9.08%   |
| IMC Networks Integrated Camera                   | 28        | 3.3%    |
| Microdia Integrated_Webcam_HD                    | 22        | 2.59%   |
| IMC Networks USB2.0 HD UVC WebCam                | 19        | 2.24%   |
| Chicony HP HD Camera                             | 18        | 2.12%   |
| Chicony FJ Camera                                | 18        | 2.12%   |
| Bison Integrated Camera                          | 18        | 2.12%   |
| Realtek Integrated_Webcam_HD                     | 13        | 1.53%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 13        | 1.53%   |
| Chicony HP HD Webcam                             | 13        | 1.53%   |
| Chicony HD WebCam                                | 13        | 1.53%   |
| Syntek Integrated Camera                         | 10        | 1.18%   |
| Chicony Integrated Camera (1280x720@30)          | 10        | 1.18%   |
| Bison SunplusIT Integrated Camera                | 10        | 1.18%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 9         | 1.06%   |
| Lite-On HP HD Camera                             | 8         | 0.94%   |
| Chicony USB2.0 VGA UVC WebCam                    | 8         | 0.94%   |
| Sunplus Integrated_Webcam_HD                     | 7         | 0.83%   |
| Sonix USB2.0 HD UVC WebCam                       | 7         | 0.83%   |
| Realtek USB Camera                               | 7         | 0.83%   |
| Lite-On Integrated Camera                        | 7         | 0.83%   |
| Chicony USB2.0 HD UVC WebCam                     | 7         | 0.83%   |
| Chicony ThinkPad T490 Webcam                     | 7         | 0.83%   |
| Chicony Integrated Camera [ThinkPad]             | 7         | 0.83%   |
| Chicony EasyCamera                               | 7         | 0.83%   |
| Bison Lenovo EasyCamera                          | 7         | 0.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 6         | 0.71%   |
| Sunplus HD WebCam                                | 6         | 0.71%   |
| Realtek USB2.0 HD UVC WebCam                     | 6         | 0.71%   |
| Microdia Integrated Webcam                       | 6         | 0.71%   |
| Lenovo Integrated Webcam [R5U877]                | 6         | 0.71%   |
| Chicony Lenovo EasyCamera                        | 6         | 0.71%   |
| Chicony Integrated HP HD Webcam                  | 6         | 0.71%   |
| Chicony HP TrueVision HD Camera                  | 6         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 6         | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)          | 5         | 0.59%   |
| Realtek Lenovo EasyCamera                        | 5         | 0.59%   |
| Quanta USB Webcam                                | 5         | 0.59%   |
| Quanta HP Webcam                                 | 5         | 0.59%   |
| Quanta HP TrueVision HD Camera                   | 5         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 88        | 39.46%  |
| Synaptics                  | 57        | 25.56%  |
| AuthenTec                  | 25        | 11.21%  |
| Shenzhen Goodix Technology | 17        | 7.62%   |
| Upek                       | 16        | 7.17%   |
| STMicroelectronics         | 9         | 4.04%   |
| LighTuning Technology      | 6         | 2.69%   |
| Elan Microelectronics      | 5         | 2.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 13.45%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 11.66%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 7.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 6.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 14        | 6.28%   |
| AuthenTec AES2810                                                          | 14        | 6.28%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 4.04%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 4.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 3.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 3.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.69%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 2.69%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.24%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 2.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.24%   |
| Validity Sensors VFS491                                                    | 4         | 1.79%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.79%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.35%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.35%   |
| Synaptics Prometheus Fingerprint Reader                                    | 3         | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.35%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.9%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.45%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.45%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.45%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.45%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.45%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.45%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.45%   |
| AuthenTec AES1600                                                          | 1         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 79        | 51.63%  |
| Broadcom         | 41        | 26.8%   |
| O2 Micro         | 11        | 7.19%   |
| Lenovo           | 11        | 7.19%   |
| Upek             | 9         | 5.88%   |
| SCM Microsystems | 2         | 1.31%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 79        | 51.63%  |
| Broadcom 5880                                                                | 13        | 8.5%    |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.19%   |
| Broadcom 58200                                                               | 11        | 7.19%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 6.54%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 3.27%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.65%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.65%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 527       | 53.18%  |
| 1     | 331       | 33.4%   |
| 2     | 111       | 11.2%   |
| 3     | 15        | 1.51%   |
| 5     | 4         | 0.4%    |
| 4     | 2         | 0.2%    |
| 6     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 221       | 35.93%  |
| Chipcard                 | 135       | 21.95%  |
| Graphics card            | 102       | 16.59%  |
| Net/wireless             | 45        | 7.32%   |
| Multimedia controller    | 29        | 4.72%   |
| Bluetooth                | 19        | 3.09%   |
| Camera                   | 17        | 2.76%   |
| Storage                  | 10        | 1.63%   |
| Card reader              | 9         | 1.46%   |
| Net/ethernet             | 8         | 1.3%    |
| Communication controller | 6         | 0.98%   |
| Sound                    | 4         | 0.65%   |
| Modem                    | 4         | 0.65%   |
| Firewire controller      | 2         | 0.33%   |
| Storage/raid             | 1         | 0.16%   |
| Network                  | 1         | 0.16%   |
| Flash memory             | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

