Linux in Venezuela - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

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

Total: 333

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [d526621027](https://linux-hardware.org/?probe=d526621027) | Jan 05, 2025 |
| HP            | Pavilion Laptop 15t-eg30... | [a2b911a2d0](https://linux-hardware.org/?probe=a2b911a2d0) | Jan 02, 2025 |
| Lenovo        | G570 4334                   | [3348b2741c](https://linux-hardware.org/?probe=3348b2741c) | Dec 30, 2024 |
| Lenovo        | G570 4334                   | [e3535c8fe8](https://linux-hardware.org/?probe=e3535c8fe8) | Dec 30, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [ccee342e62](https://linux-hardware.org/?probe=ccee342e62) | Dec 18, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [428715e96d](https://linux-hardware.org/?probe=428715e96d) | Dec 17, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [46f8c1934d](https://linux-hardware.org/?probe=46f8c1934d) | Dec 17, 2024 |
| Toshiba       | Satellite L645              | [8ce1185c95](https://linux-hardware.org/?probe=8ce1185c95) | Nov 30, 2024 |
| HP            | ProBook 650 G1              | [f75dc49b84](https://linux-hardware.org/?probe=f75dc49b84) | Nov 23, 2024 |
| HP            | ProBook 6450b               | [1dbb3a5dd9](https://linux-hardware.org/?probe=1dbb3a5dd9) | Nov 21, 2024 |
| Unknown       | Unknown                     | [1e1c1f6c27](https://linux-hardware.org/?probe=1e1c1f6c27) | Nov 19, 2024 |
| ASUSTek       | ROG Strix G614JI_G614JI     | [b73f3d838f](https://linux-hardware.org/?probe=b73f3d838f) | Nov 13, 2024 |
| Dell          | XPS MXC062                  | [971fc4620d](https://linux-hardware.org/?probe=971fc4620d) | Nov 11, 2024 |
| Siragon       | MN-50                       | [31e300c3fb](https://linux-hardware.org/?probe=31e300c3fb) | Oct 28, 2024 |
| UNIQCELL      | Q15.6                       | [18be8c706d](https://linux-hardware.org/?probe=18be8c706d) | Oct 11, 2024 |
| Dell          | Latitude E5450              | [6843a865fe](https://linux-hardware.org/?probe=6843a865fe) | Oct 07, 2024 |
| Lenovo        | ThinkPad T490 20N2000LSP    | [34c10e27fb](https://linux-hardware.org/?probe=34c10e27fb) | Oct 03, 2024 |
| Toshiba       | Satellite C645              | [1a789a141f](https://linux-hardware.org/?probe=1a789a141f) | Sep 21, 2024 |
| Lenovo        | ThinkPad T410 2522G18       | [1165597d26](https://linux-hardware.org/?probe=1165597d26) | Sep 16, 2024 |
| VIT           | M2420                       | [6b9697ca39](https://linux-hardware.org/?probe=6b9697ca39) | Sep 11, 2024 |
| VIT           | M2420                       | [f36595500f](https://linux-hardware.org/?probe=f36595500f) | Sep 11, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | [b8407fb3c6](https://linux-hardware.org/?probe=b8407fb3c6) | Sep 08, 2024 |
| Google        | Relm                        | [a69f9fe43f](https://linux-hardware.org/?probe=a69f9fe43f) | Sep 05, 2024 |
| Acer          | Predator PT315-53           | [636347c33f](https://linux-hardware.org/?probe=636347c33f) | Sep 01, 2024 |
| MSI           | Cyborg 15 A12VF             | [f3409a16bc](https://linux-hardware.org/?probe=f3409a16bc) | Aug 21, 2024 |
| MSI           | Cyborg 15 A12VF             | [e8712ff63e](https://linux-hardware.org/?probe=e8712ff63e) | Aug 21, 2024 |
| Lenovo        | ThinkPad SL 2743A65         | [0ee47e6c13](https://linux-hardware.org/?probe=0ee47e6c13) | Aug 12, 2024 |
| VIT           | P2400                       | [b103ea6da4](https://linux-hardware.org/?probe=b103ea6da4) | Aug 12, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [636fdb4075](https://linux-hardware.org/?probe=636fdb4075) | Aug 05, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [14fae8137f](https://linux-hardware.org/?probe=14fae8137f) | Jul 25, 2024 |
| Dell          | Inspiron 5520               | [617fd7c71a](https://linux-hardware.org/?probe=617fd7c71a) | Jul 11, 2024 |
| Google        | Reks                        | [91715e189c](https://linux-hardware.org/?probe=91715e189c) | Jul 07, 2024 |
| Dell          | Latitude 5590               | [649a21d948](https://linux-hardware.org/?probe=649a21d948) | Jul 06, 2024 |
| Dell          | Precision 7720              | [26f2413f41](https://linux-hardware.org/?probe=26f2413f41) | Jul 04, 2024 |
| Dell          | Precision M4800             | [43ecd5fec8](https://linux-hardware.org/?probe=43ecd5fec8) | Jul 03, 2024 |
| Dell          | Latitude E6420              | [b39cf47b19](https://linux-hardware.org/?probe=b39cf47b19) | Jun 25, 2024 |
| Lenovo        | 3000 N200 0769AL3           | [47b20e869d](https://linux-hardware.org/?probe=47b20e869d) | Jun 22, 2024 |
| Dell          | Precision M4800             | [ef1ba678a3](https://linux-hardware.org/?probe=ef1ba678a3) | Jun 22, 2024 |
| VENEZOLANA... | VIT P2460-02                | [01054473b9](https://linux-hardware.org/?probe=01054473b9) | Jun 19, 2024 |
| Dell          | Latitude E6420              | [07364acb42](https://linux-hardware.org/?probe=07364acb42) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [b1f2bd7ee5](https://linux-hardware.org/?probe=b1f2bd7ee5) | Jun 11, 2024 |
| VENEZOLANA... | VIT P2460-02                | [6177f7ad15](https://linux-hardware.org/?probe=6177f7ad15) | Jun 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a639c86fe2](https://linux-hardware.org/?probe=a639c86fe2) | May 24, 2024 |
| Gigabyte      | AORUS 5 KB                  | [0083b70388](https://linux-hardware.org/?probe=0083b70388) | May 23, 2024 |
| HP            | 3115m                       | [45bdc53959](https://linux-hardware.org/?probe=45bdc53959) | May 14, 2024 |
| Notebook      | W54BL                       | [adb804fa7f](https://linux-hardware.org/?probe=adb804fa7f) | Apr 27, 2024 |
| Unknown       | Unknown                     | [5fda06b27d](https://linux-hardware.org/?probe=5fda06b27d) | Apr 26, 2024 |
| HP            | Pavilion m6                 | [7573d33d4f](https://linux-hardware.org/?probe=7573d33d4f) | Apr 04, 2024 |
| Toshiba       | Satellite A205              | [4fcbf3184c](https://linux-hardware.org/?probe=4fcbf3184c) | Apr 02, 2024 |
| VENEZOLANA... | VIT P2460-02                | [c6fc091713](https://linux-hardware.org/?probe=c6fc091713) | Mar 24, 2024 |
| Dell          | Precision M4800             | [9a66a454e2](https://linux-hardware.org/?probe=9a66a454e2) | Mar 17, 2024 |
| Dell          | Precision M4800             | [c38442b3dc](https://linux-hardware.org/?probe=c38442b3dc) | Mar 17, 2024 |
| Unknown       | Unknown                     | [d00c774230](https://linux-hardware.org/?probe=d00c774230) | Mar 16, 2024 |
| Google        | Kip                         | [3da64ae4ad](https://linux-hardware.org/?probe=3da64ae4ad) | Mar 11, 2024 |
| Google        | Kip                         | [a08197fa56](https://linux-hardware.org/?probe=a08197fa56) | Mar 11, 2024 |
| Acer          | Aspire A515-43              | [054ae2a4a5](https://linux-hardware.org/?probe=054ae2a4a5) | Mar 09, 2024 |
| Dell          | Inspiron N4010              | [0d25733cfa](https://linux-hardware.org/?probe=0d25733cfa) | Feb 27, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [46990d3920](https://linux-hardware.org/?probe=46990d3920) | Feb 17, 2024 |
| HP            | ProBook 650 G1              | [9b6886b2f0](https://linux-hardware.org/?probe=9b6886b2f0) | Feb 16, 2024 |
| HP            | ProBook 650 G1              | [d3d2fd6bda](https://linux-hardware.org/?probe=d3d2fd6bda) | Feb 16, 2024 |
| Lenovo        | 3000 N500 42336DS           | [7c23ebf66b](https://linux-hardware.org/?probe=7c23ebf66b) | Feb 13, 2024 |
| VIT           | P1400                       | [8cb8362e24](https://linux-hardware.org/?probe=8cb8362e24) | Feb 10, 2024 |
| VIT           | P3400                       | [036ee57838](https://linux-hardware.org/?probe=036ee57838) | Feb 02, 2024 |
| VIT           | P3400                       | [6b03e6574f](https://linux-hardware.org/?probe=6b03e6574f) | Feb 01, 2024 |
| Dell          | Inspiron MXC061             | [a134206781](https://linux-hardware.org/?probe=a134206781) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [1ebab4d906](https://linux-hardware.org/?probe=1ebab4d906) | Jan 30, 2024 |
| Dell          | Inspiron 3531               | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| Google        | Fleex                       | [100ab93f52](https://linux-hardware.org/?probe=100ab93f52) | Jan 09, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [45b99e2412](https://linux-hardware.org/?probe=45b99e2412) | Jan 08, 2024 |
| Dell          | G16 7630                    | [71f36f8ed0](https://linux-hardware.org/?probe=71f36f8ed0) | Dec 24, 2023 |
| HP            | Pavilion dv5                | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| Google        | Candy                       | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| VIT           | P3400                       | [0564cdc52e](https://linux-hardware.org/?probe=0564cdc52e) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [55a44e9a14](https://linux-hardware.org/?probe=55a44e9a14) | Dec 05, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [88fba30cec](https://linux-hardware.org/?probe=88fba30cec) | Nov 21, 2023 |
| Notebook      | NL40_50CU                   | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| Dell          | Inspiron 15 3511            | [79b891b4df](https://linux-hardware.org/?probe=79b891b4df) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9c9733a5c4](https://linux-hardware.org/?probe=9c9733a5c4) | Nov 07, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e4d524b5b8](https://linux-hardware.org/?probe=e4d524b5b8) | Nov 07, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Intel         | powered classmate PC        | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| VIT           | P1400                       | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| Gateway       | NV57H                       | [141355e1e3](https://linux-hardware.org/?probe=141355e1e3) | Oct 09, 2023 |
| HP            | Compaq Presario C768        | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| VIT           | P2400                       | [1896f1962a](https://linux-hardware.org/?probe=1896f1962a) | Oct 06, 2023 |
| HP            | Pavilion m6                 | [2fb7dbd455](https://linux-hardware.org/?probe=2fb7dbd455) | Sep 09, 2023 |
| Acer          | Aspire A315-42              | [a0abff6d5f](https://linux-hardware.org/?probe=a0abff6d5f) | Sep 08, 2023 |
| VIT           | P2400                       | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| VENEZOLANA... | VIT P2460-02                | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| ASUSTek       | X540SA                      | [71b31f4a43](https://linux-hardware.org/?probe=71b31f4a43) | Aug 31, 2023 |
| Panasonic     | CF-31RECAXDR                | [2c021f93de](https://linux-hardware.org/?probe=2c021f93de) | Aug 30, 2023 |
| ASUSTek       | X540SA                      | [dd6f1d7cac](https://linux-hardware.org/?probe=dd6f1d7cac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| HP            | Pavilion dv5                | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| VIT           | P2402                       | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| HP            | Laptop 15-fc0xxx            | [52c59bb799](https://linux-hardware.org/?probe=52c59bb799) | Aug 16, 2023 |
| Siragon       | MN-50                       | [8eafa43cb5](https://linux-hardware.org/?probe=8eafa43cb5) | Aug 09, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Shanghai Z... | ZXE CRB                     | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Acer          | Aspire 4750                 | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [c1da8fb79e](https://linux-hardware.org/?probe=c1da8fb79e) | Jul 08, 2023 |
| Dell          | Inspiron N4050              | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Dell          | Latitude 7490               | [3734a0a9bf](https://linux-hardware.org/?probe=3734a0a9bf) | Jul 07, 2023 |
| Acer          | Aspire 6930                 | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| VIT           | P2423                       | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| VIT           | P2402                       | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| VIT           | P2400                       | [dca6cca8a2](https://linux-hardware.org/?probe=dca6cca8a2) | May 26, 2023 |
| Acer          | Aspire A514-55              | [17996395f4](https://linux-hardware.org/?probe=17996395f4) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | [dddde1dc45](https://linux-hardware.org/?probe=dddde1dc45) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | [d8261039f8](https://linux-hardware.org/?probe=d8261039f8) | May 24, 2023 |
| HP            | Laptop 17-cp0xxx            | [7f1bc5a99c](https://linux-hardware.org/?probe=7f1bc5a99c) | May 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [701fb0df1b](https://linux-hardware.org/?probe=701fb0df1b) | Apr 26, 2023 |
| HP            | Laptop 17-cp0xxx            | [7ba77e1842](https://linux-hardware.org/?probe=7ba77e1842) | Apr 23, 2023 |
| Dell          | Latitude E6430              | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | [54af26ce93](https://linux-hardware.org/?probe=54af26ce93) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [98121ef614](https://linux-hardware.org/?probe=98121ef614) | Apr 14, 2023 |
| Lenovo        | 3000 V200 07642XU           | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| VIT           | P2402                       | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | EliteBook 840 G3            | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| Notebook      | W54BL                       | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
| Intel         | powered classmate PC        | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Pegatron      | H36Y                        | [1757156f40](https://linux-hardware.org/?probe=1757156f40) | Mar 11, 2023 |
| Acer          | Aspire A715-76              | [c0c0d5447d](https://linux-hardware.org/?probe=c0c0d5447d) | Mar 09, 2023 |
| Pegatron      | H36Y                        | [8d9c3ebbc8](https://linux-hardware.org/?probe=8d9c3ebbc8) | Mar 09, 2023 |
| MSI           | GL73 9SD                    | [0913746f16](https://linux-hardware.org/?probe=0913746f16) | Mar 07, 2023 |
| VIT           | P1400                       | [3d31270e0d](https://linux-hardware.org/?probe=3d31270e0d) | Mar 07, 2023 |
| VIT           | P1400                       | [bed6aed6fa](https://linux-hardware.org/?probe=bed6aed6fa) | Mar 07, 2023 |
| Acer          | Aspire A715-76              | [b9f52dc0f3](https://linux-hardware.org/?probe=b9f52dc0f3) | Feb 27, 2023 |
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| Dell          | Latitude E6430              | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Google        | Candy                       | [b2f2862759](https://linux-hardware.org/?probe=b2f2862759) | Feb 13, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Aspire 4739Z                | [cc795627da](https://linux-hardware.org/?probe=cc795627da) | Feb 10, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [c20b6ee7d2](https://linux-hardware.org/?probe=c20b6ee7d2) | Feb 04, 2023 |
| Dell          | Latitude E6430              | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| Dell          | Latitude E6430              | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| Lenovo        | ThinkPad SL 2743A65         | [89f744ff83](https://linux-hardware.org/?probe=89f744ff83) | Jan 22, 2023 |
| Dell          | Vostro 1220                 | [6cd42b6be3](https://linux-hardware.org/?probe=6cd42b6be3) | Jan 19, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Pegatron      | B74                         | [3e721dbe13](https://linux-hardware.org/?probe=3e721dbe13) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z580                | [6cb922bbdf](https://linux-hardware.org/?probe=6cb922bbdf) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8e885883c6](https://linux-hardware.org/?probe=8e885883c6) | Jan 03, 2023 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Acer          | Aspire A315-42              | [68f683d29e](https://linux-hardware.org/?probe=68f683d29e) | Dec 06, 2022 |
| HP            | Mini 110-1100               | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| Lenovo        | 3000 N500 42336DS           | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| Intel         | powered classmate PC        | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Dell          | Vostro 3550                 | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| Acer          | Aspire 4739Z                | [d3ef4a43db](https://linux-hardware.org/?probe=d3ef4a43db) | Nov 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Google        | Candy                       | [af2c0be6ca](https://linux-hardware.org/?probe=af2c0be6ca) | Oct 17, 2022 |
| Google        | Candy                       | [ec740507fd](https://linux-hardware.org/?probe=ec740507fd) | Oct 17, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Unknown       | NB-7000                     | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| HP            | EliteBook 8760w             | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Gateway       | NV57H                       | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| Clevo         | W54xEU                      | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Acer          | Aspire A515-44              | [ac687f4dcd](https://linux-hardware.org/?probe=ac687f4dcd) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Dell          | Latitude E6420              | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Dell          | Inspiron 3180               | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | ProBook 440 G1              | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| HP            | EliteBook 840 G3            | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| Dell          | Inspiron 5502               | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| Google        | Cyan                        | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| VIT           | M2420                       | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| VIT           | M2420                       | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Acer          | TravelMate 5742Z            | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| Dell          | Inspiron 5520               | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| Dell          | XPS 15 7590                 | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Unknown       | Unknown                     | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| Gateway       | NV57H                       | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| VIT           | P2402                       | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| Dell          | Inspiron 5502               | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | P3400                       | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| VIT           | P3400                       | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| Gateway       | NV57H                       | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| MSI           | MS-1454                     | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| VIT           | M2421                       | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| UNIQCELL      | Q15.6                       | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Lenovo        | B40-70 20392                | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| HP            | Pavilion dv6                | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| VIT           | P3400                       | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Clevo         | W54xEU                      | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Pegatron      | T14AF                       | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| VIT           | P2400                       | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| Acer          | Aspire VX5-591G             | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| HP            | Pavilion dv6700             | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| VIT           | P2400                       | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| VIT           | P1400                       | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| Sony          | VGN-FW510F                  | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| Lenovo        | G570 4334                   | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Acer          | Aspire 4935                 | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Toshiba       | Satellite E55t-A            | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Dell          | Inspiron 5437               | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 2000                        | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Dell          | Inspiron 5437               | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Dell          | Inspiron 3180               | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Lenovo        | G460 20041                  | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| Dell          | Inspiron 5570               | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| HP            | Presario V2000 (EW997LA#... | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| VIT           | M2421                       | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| Intel         | powered classmate PC        | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| HP            | Presario C700               | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| Unknown       | Unknown                     | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| VIT           | P3400                       | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| VIT           | P3400                       | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| VIT           | P2402                       | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| VIT           | P3400                       | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| VIT           | P2402                       | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| Lenovo        | Z50-75 80EC                 | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | IdeaPad S100c 20194         | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Dell          | Inspiron 3421               | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| Intel         | powered classmate PC        | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | IdeaPad S100c 20194         | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| Lenovo        | IdeaPad S100c 20194         | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Lenovo        | G480 20150                  | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| HP            | Pavilion dv4                | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | powered classmate PC        | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 22.04                 | 18        | 7.38%   |
| Debian 11                    | 16        | 6.56%   |
| Ubuntu 20.04                 | 13        | 5.33%   |
| Debian 12                    | 9         | 3.69%   |
| OpenMandriva 4.3             | 8         | 3.28%   |
| OpenMandriva 23.08           | 6         | 2.46%   |
| KDE neon 22.04               | 6         | 2.46%   |
| Debian 10                    | 6         | 2.46%   |
| Zorin 16                     | 5         | 2.05%   |
| Ubuntu 18.04                 | 5         | 2.05%   |
| Kubuntu 20.04                | 5         | 2.05%   |
| KDE neon 20.04               | 5         | 2.05%   |
| OpenMandriva 4.2             | 4         | 1.64%   |
| Linux Mint 21.1              | 4         | 1.64%   |
| Xubuntu 22.04                | 3         | 1.23%   |
| Xubuntu 18.04                | 3         | 1.23%   |
| Ubuntu 23.10                 | 3         | 1.23%   |
| ROSA R9                      | 3         | 1.23%   |
| OpenMandriva 23.03           | 3         | 1.23%   |
| Linux Mint 20.3              | 3         | 1.23%   |
| Fedora 39                    | 3         | 1.23%   |
| Arch Rolling                 | 3         | 1.23%   |
| Zorin 17                     | 2         | 0.82%   |
| Zorin 15                     | 2         | 0.82%   |
| Ubuntu Unity 16.04           | 2         | 0.82%   |
| Ubuntu 21.10                 | 2         | 0.82%   |
| Ubuntu 19.10                 | 2         | 0.82%   |
| Pop!_OS 22.04                | 2         | 0.82%   |
| Pop!_OS 21.04                | 2         | 0.82%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.82%   |
| OpenMandriva 24.07           | 2         | 0.82%   |
| OpenMandriva 24.01           | 2         | 0.82%   |
| OpenMandriva 23.06           | 2         | 0.82%   |
| OpenMandriva 23.01           | 2         | 0.82%   |
| Nobara 37                    | 2         | 0.82%   |
| MX 23                        | 2         | 0.82%   |
| Manjaro                      | 2         | 0.82%   |
| Linux Mint 21.3              | 2         | 0.82%   |
| Linux Mint 21.2              | 2         | 0.82%   |
| Linux Mint 20                | 2         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 43        | 18.7%   |
| OpenMandriva  | 30        | 13.04%  |
| Debian        | 30        | 13.04%  |
| Linux Mint    | 16        | 6.96%   |
| Fedora        | 13        | 5.65%   |
| KDE neon      | 12        | 5.22%   |
| Zorin         | 9         | 3.91%   |
| Xubuntu       | 9         | 3.91%   |
| ROSA          | 7         | 3.04%   |
| Kubuntu       | 7         | 3.04%   |
| Manjaro       | 6         | 2.61%   |
| Pop!_OS       | 4         | 1.74%   |
| MX            | 4         | 1.74%   |
| Arch          | 4         | 1.74%   |
| Ubuntu MATE   | 3         | 1.3%    |
| openSUSE      | 3         | 1.3%    |
| Nobara        | 3         | 1.3%    |
| Kali          | 3         | 1.3%    |
| Ubuntu Unity  | 2         | 0.87%   |
| Lubuntu       | 2         | 0.87%   |
| LMDE          | 2         | 0.87%   |
| EndeavourOS   | 2         | 0.87%   |
| Elementary    | 2         | 0.87%   |
| ArcoLinux     | 2         | 0.87%   |
| Xero          | 1         | 0.43%   |
| Ubuntu Budgie | 1         | 0.43%   |
| TUXEDO OS     | 1         | 0.43%   |
| Solus         | 1         | 0.43%   |
| Q4OS          | 1         | 0.43%   |
| Linux Lite    | 1         | 0.43%   |
| Garuda Linux  | 1         | 0.43%   |
| Feren OS      | 1         | 0.43%   |
| Deepin        | 1         | 0.43%   |
| BunsenLabs    | 1         | 0.43%   |
| Alpine        | 1         | 0.43%   |
| AlmaLinux     | 1         | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 8         | 2.94%   |
| 6.5.0-41-generic         | 4         | 1.47%   |
| 6.4.8-desktop-2omv2390   | 4         | 1.47%   |
| 5.4.0-42-generic         | 4         | 1.47%   |
| 5.15.0-46-generic        | 4         | 1.47%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.47%   |
| 5.10.0-23-amd64          | 4         | 1.47%   |
| 6.4.11-desktop-1omv2390  | 3         | 1.1%    |
| 6.2.6-desktop-1omv2390   | 3         | 1.1%    |
| 5.4.0-73-generic         | 3         | 1.1%    |
| 5.4.0-52-generic         | 3         | 1.1%    |
| 5.3.0-40-generic         | 3         | 1.1%    |
| 5.15.0-67-generic        | 3         | 1.1%    |
| 5.15.0-56-generic        | 3         | 1.1%    |
| 5.13.0-39-generic        | 3         | 1.1%    |
| 5.10.0-13-amd64          | 3         | 1.1%    |
| 4.19.0-17-amd64          | 3         | 1.1%    |
| 6.8.0-51-generic         | 2         | 0.74%   |
| 6.8.0-48-generic         | 2         | 0.74%   |
| 6.8.0-40-generic         | 2         | 0.74%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.74%   |
| 6.4.11-arch2-1           | 2         | 0.74%   |
| 6.3.5-desktop-3omv2390   | 2         | 0.74%   |
| 6.2.0-26-generic         | 2         | 0.74%   |
| 6.10.0-desktop-1omv2490  | 2         | 0.74%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.74%   |
| 6.1.0-22-amd64           | 2         | 0.74%   |
| 6.1.0-17-amd64           | 2         | 0.74%   |
| 5.4.0-89-generic         | 2         | 0.74%   |
| 5.4.0-77-generic         | 2         | 0.74%   |
| 5.4.0-48-generic         | 2         | 0.74%   |
| 5.4.0-107-generic        | 2         | 0.74%   |
| 5.19.0-41-generic        | 2         | 0.74%   |
| 5.19.0-40-generic        | 2         | 0.74%   |
| 5.19.0-2-amd64           | 2         | 0.74%   |
| 5.15.0-91-generic        | 2         | 0.74%   |
| 5.15.0-76-generic        | 2         | 0.74%   |
| 5.15.0-60-generic        | 2         | 0.74%   |
| 5.15.0-48-generic        | 2         | 0.74%   |
| 5.15.0-43-generic        | 2         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 32        | 12.65%  |
| 5.4.0   | 20        | 7.91%   |
| 5.10.0  | 17        | 6.72%   |
| 6.5.0   | 11        | 4.35%   |
| 6.2.0   | 10        | 3.95%   |
| 5.13.0  | 10        | 3.95%   |
| 6.1.0   | 9         | 3.56%   |
| 6.8.0   | 8         | 3.16%   |
| 5.16.7  | 8         | 3.16%   |
| 4.19.0  | 8         | 3.16%   |
| 5.19.0  | 7         | 2.77%   |
| 5.11.0  | 6         | 2.37%   |
| 6.4.11  | 5         | 1.98%   |
| 5.3.0   | 5         | 1.98%   |
| 6.4.8   | 4         | 1.58%   |
| 5.8.0   | 4         | 1.58%   |
| 5.10.14 | 4         | 1.58%   |
| 4.15.0  | 4         | 1.58%   |
| 6.6.2   | 3         | 1.19%   |
| 6.2.6   | 3         | 1.19%   |
| 6.4.2   | 2         | 0.79%   |
| 6.3.5   | 2         | 0.79%   |
| 6.10.0  | 2         | 0.79%   |
| 6.1.1   | 2         | 0.79%   |
| 5.18.0  | 2         | 0.79%   |
| 5.15.2  | 2         | 0.79%   |
| 5.14.10 | 2         | 0.79%   |
| 5.0.0   | 2         | 0.79%   |
| 4.9.20  | 2         | 0.79%   |
| 6.9.3   | 1         | 0.4%    |
| 6.9.1   | 1         | 0.4%    |
| 6.8.7   | 1         | 0.4%    |
| 6.7.7   | 1         | 0.4%    |
| 6.6.7   | 1         | 0.4%    |
| 6.6.21  | 1         | 0.4%    |
| 6.5.6   | 1         | 0.4%    |
| 6.5.3   | 1         | 0.4%    |
| 6.5.1   | 1         | 0.4%    |
| 6.4.12  | 1         | 0.4%    |
| 6.3.6   | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 40        | 15.94%  |
| 5.10    | 26        | 10.36%  |
| 5.4     | 22        | 8.76%   |
| 6.2     | 15        | 5.98%   |
| 6.1     | 15        | 5.98%   |
| 6.5     | 14        | 5.58%   |
| 6.4     | 12        | 4.78%   |
| 5.13    | 11        | 4.38%   |
| 6.8     | 9         | 3.59%   |
| 5.16    | 8         | 3.19%   |
| 4.19    | 8         | 3.19%   |
| 5.19    | 7         | 2.79%   |
| 5.11    | 6         | 2.39%   |
| 6.6     | 5         | 1.99%   |
| 5.8     | 5         | 1.99%   |
| 5.3     | 5         | 1.99%   |
| 6.3     | 4         | 1.59%   |
| 6.10    | 4         | 1.59%   |
| 5.17    | 4         | 1.59%   |
| 4.9     | 4         | 1.59%   |
| 4.15    | 4         | 1.59%   |
| 6.11    | 3         | 1.2%    |
| 5.14    | 3         | 1.2%    |
| 6.9     | 2         | 0.8%    |
| 6.0     | 2         | 0.8%    |
| 5.6     | 2         | 0.8%    |
| 5.18    | 2         | 0.8%    |
| 5.12    | 2         | 0.8%    |
| 5.0     | 2         | 0.8%    |
| 6.7     | 1         | 0.4%    |
| 6.12    | 1         | 0.4%    |
| 5.9     | 1         | 0.4%    |
| 5.5     | 1         | 0.4%    |
| 4.18    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 205       | 94.04%  |
| i686   | 13        | 5.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 77        | 32.63%  |
| KDE5          | 60        | 25.42%  |
| XFCE          | 34        | 14.41%  |
| X-Cinnamon    | 13        | 5.51%   |
| Unknown       | 13        | 5.51%   |
| KDE           | 6         | 2.54%   |
| MATE          | 5         | 2.12%   |
| LXQt          | 5         | 2.12%   |
| KDE6          | 5         | 2.12%   |
| KDE4          | 4         | 1.69%   |
| Cinnamon      | 3         | 1.27%   |
| Budgie        | 3         | 1.27%   |
| Unity         | 2         | 0.85%   |
| Pantheon      | 2         | 0.85%   |
| Openbox       | 1         | 0.42%   |
| GNOME Classic | 1         | 0.42%   |
| Deepin        | 1         | 0.42%   |
| awesome       | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 172       | 74.46%  |
| Wayland | 56        | 24.24%  |
| Tty     | 2         | 0.87%   |
| Unknown | 1         | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 31.03%  |
| SDDM    | 51        | 21.98%  |
| LightDM | 37        | 15.95%  |
| GDM3    | 36        | 15.52%  |
| GDM     | 29        | 12.5%   |
| KDM     | 4         | 1.72%   |
| TDM     | 3         | 1.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 124       | 53.68%  |
| en_US   | 65        | 28.14%  |
| es_ES   | 20        | 8.66%   |
| es_MX   | 8         | 3.46%   |
| Unknown | 8         | 3.46%   |
| es_US   | 2         | 0.87%   |
| C       | 2         | 0.87%   |
| en_GB   | 1         | 0.43%   |
| en_CA   | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 138       | 61.06%  |
| EFI  | 88        | 38.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 72.93%  |
| Overlay | 24        | 10.48%  |
| Btrfs   | 21        | 9.17%   |
| Tmpfs   | 10        | 4.37%   |
| Xfs     | 4         | 1.75%   |
| Unknown | 3         | 1.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 101       | 43.91%  |
| Unknown | 80        | 34.78%  |
| MBR     | 49        | 21.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 191       | 84.14%  |
| Yes       | 36        | 15.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 143       | 64.71%  |
| Yes       | 78        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 36        | 16.51%  |
| Dell                                     | 35        | 16.06%  |
| VIT                                      | 29        | 13.3%   |
| Hewlett-Packard                          | 29        | 13.3%   |
| ASUSTek Computer                         | 15        | 6.88%   |
| Acer                                     | 13        | 5.96%   |
| Intel                                    | 9         | 4.13%   |
| Unknown                                  | 9         | 4.13%   |
| Google                                   | 8         | 3.67%   |
| Toshiba                                  | 5         | 2.29%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 3         | 1.38%   |
| SIRAGON                                  | 3         | 1.38%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 1.38%   |
| Pegatron                                 | 3         | 1.38%   |
| Notebook                                 | 3         | 1.38%   |
| MSI                                      | 3         | 1.38%   |
| Samsung Electronics                      | 2         | 0.92%   |
| UNIQCELL                                 | 1         | 0.46%   |
| Sony                                     | 1         | 0.46%   |
| Panasonic                                | 1         | 0.46%   |
| GPU Company                              | 1         | 0.46%   |
| Gigabyte Technology                      | 1         | 0.46%   |
| Gateway                                  | 1         | 0.46%   |
| Exo                                      | 1         | 0.46%   |
| Clevo                                    | 1         | 0.46%   |
| AVITA                                    | 1         | 0.46%   |
| Alienware                                | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| VIT P2400                                             | 9         | 4.13%   |
| Intel powered classmate PC                            | 9         | 4.13%   |
| Unknown                                               | 9         | 4.13%   |
| VIT P3400                                             | 5         | 2.29%   |
| VIT P2402                                             | 5         | 2.29%   |
| VIT M2420                                             | 4         | 1.83%   |
| VIT P1400                                             | 3         | 1.38%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT P2460-02 | 3         | 1.38%   |
| Shanghai Zhaoxin ZXE CRB                              | 3         | 1.38%   |
| HP Pavilion dv5                                       | 3         | 1.38%   |
| Google Candy                                          | 3         | 1.38%   |
| ASUS VivoBook_ASUSLaptop K3605VC_K3605VC              | 3         | 1.38%   |
| VIT M2421                                             | 2         | 0.92%   |
| Siragon MN-50                                         | 2         | 0.92%   |
| Notebook W54BL                                        | 2         | 0.92%   |
| Lenovo ThinkPad SL 2743A65                            | 2         | 0.92%   |
| Lenovo IdeaPad S100c 20194                            | 2         | 0.92%   |
| Lenovo G570 4334                                      | 2         | 0.92%   |
| Lenovo 3000 N200 0769ARS                              | 2         | 0.92%   |
| HP Compaq Presario C700                               | 2         | 0.92%   |
| Dell Latitude E6420                                   | 2         | 0.92%   |
| Dell Latitude 5590                                    | 2         | 0.92%   |
| Dell Inspiron 1545                                    | 2         | 0.92%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM             | 2         | 0.92%   |
| Acer Aspire 4739Z                                     | 2         | 0.92%   |
| VIT P2423                                             | 1         | 0.46%   |
| UNIQCELL Q15.6                                        | 1         | 0.46%   |
| Toshiba Satellite L645                                | 1         | 0.46%   |
| Toshiba Satellite E55t-A                              | 1         | 0.46%   |
| Toshiba Satellite C645                                | 1         | 0.46%   |
| Toshiba Satellite A205                                | 1         | 0.46%   |
| Toshiba ENCORE 2 WT8-B                                | 1         | 0.46%   |
| Sony VGN-FW510F                                       | 1         | 0.46%   |
| SIRAGON LM-C100                                       | 1         | 0.46%   |
| Samsung 905S3G/906S3G/915S3G                          | 1         | 0.46%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.46%   |
| Pegatron T14AF                                        | 1         | 0.46%   |
| Pegatron H36Y                                         | 1         | 0.46%   |
| Pegatron B74                                          | 1         | 0.46%   |
| Panasonic CF-31RECAXDR                                | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Dell Inspiron                                | 16        | 7.34%   |
| Lenovo IdeaPad                               | 13        | 5.96%   |
| HP Pavilion                                  | 12        | 5.5%    |
| Acer Aspire                                  | 11        | 5.05%   |
| VIT P2400                                    | 9         | 4.13%   |
| Lenovo ThinkPad                              | 9         | 4.13%   |
| Intel powered                                | 9         | 4.13%   |
| Dell Latitude                                | 9         | 4.13%   |
| Unknown                                      | 9         | 4.13%   |
| VIT P3400                                    | 5         | 2.29%   |
| VIT P2402                                    | 5         | 2.29%   |
| Lenovo 3000                                  | 5         | 2.29%   |
| ASUS VivoBook                                | 5         | 2.29%   |
| ASUS ASUS                                    | 5         | 2.29%   |
| VIT M2420                                    | 4         | 1.83%   |
| Toshiba Satellite                            | 4         | 1.83%   |
| HP Laptop                                    | 4         | 1.83%   |
| Dell Vostro                                  | 4         | 1.83%   |
| VIT P1400                                    | 3         | 1.38%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT | 3         | 1.38%   |
| Shanghai Zhaoxin ZXE                         | 3         | 1.38%   |
| HP ProBook                                   | 3         | 1.38%   |
| HP Compaq                                    | 3         | 1.38%   |
| Google Candy                                 | 3         | 1.38%   |
| Dell Precision                               | 3         | 1.38%   |
| VIT M2421                                    | 2         | 0.92%   |
| Siragon MN-50                                | 2         | 0.92%   |
| Notebook W54BL                               | 2         | 0.92%   |
| Lenovo Legion                                | 2         | 0.92%   |
| Lenovo G570                                  | 2         | 0.92%   |
| HP Presario                                  | 2         | 0.92%   |
| HP EliteBook                                 | 2         | 0.92%   |
| Dell XPS                                     | 2         | 0.92%   |
| VIT P2423                                    | 1         | 0.46%   |
| UNIQCELL Q15.6                               | 1         | 0.46%   |
| Toshiba ENCORE                               | 1         | 0.46%   |
| Sony VGN-FW510F                              | 1         | 0.46%   |
| SIRAGON LM-C100                              | 1         | 0.46%   |
| Samsung 905S3G                               | 1         | 0.46%   |
| Samsung 355V4C                               | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 26        | 11.93%  |
| 2013    | 24        | 11.01%  |
| 2012    | 22        | 10.09%  |
| 2022    | 16        | 7.34%   |
| 2023    | 14        | 6.42%   |
| 2010    | 13        | 5.96%   |
| 2008    | 13        | 5.96%   |
| 2020    | 12        | 5.5%    |
| 2019    | 11        | 5.05%   |
| 2007    | 11        | 5.05%   |
| 2018    | 10        | 4.59%   |
| 2021    | 9         | 4.13%   |
| 2014    | 9         | 4.13%   |
| 2009    | 7         | 3.21%   |
| 2017    | 5         | 2.29%   |
| 2015    | 5         | 2.29%   |
| 2024    | 3         | 1.38%   |
| 2006    | 3         | 1.38%   |
| Unknown | 3         | 1.38%   |
| 2016    | 2         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 218       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 212       | 96.36%  |
| Enabled  | 8         | 3.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 210       | 96.33%  |
| Yes  | 8         | 3.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 58        | 26.24%  |
| 4.01-8.0    | 52        | 23.53%  |
| 1.01-2.0    | 34        | 15.38%  |
| 8.01-16.0   | 34        | 15.38%  |
| 16.01-24.0  | 19        | 8.6%    |
| 2.01-3.0    | 11        | 4.98%   |
| 32.01-64.0  | 9         | 4.07%   |
| 24.01-32.0  | 2         | 0.9%    |
| 64.01-256.0 | 1         | 0.45%   |
| 0.51-1.0    | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 85        | 33.33%  |
| 2.01-3.0   | 65        | 25.49%  |
| 4.01-8.0   | 32        | 12.55%  |
| 3.01-4.0   | 30        | 11.76%  |
| 0.51-1.0   | 29        | 11.37%  |
| 8.01-16.0  | 11        | 4.31%   |
| 0.01-0.5   | 2         | 0.78%   |
| 16.01-24.0 | 1         | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 149       | 66.52%  |
| 2      | 67        | 29.91%  |
| 3      | 7         | 3.13%   |
| 0      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 55%     |
| Yes       | 99        | 45%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 83.26%  |
| No        | 37        | 16.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 97.25%  |
| No        | 6         | 2.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 61.71%  |
| No        | 85        | 38.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 218       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 87        | 36.55%  |
| Maracaibo                  | 23        | 9.66%   |
| Maracay                    | 10        | 4.2%    |
| Valencia                   | 8         | 3.36%   |
| Barquisimeto               | 8         | 3.36%   |
| Mérida                    | 7         | 2.94%   |
| Barcelona                  | 6         | 2.52%   |
| Ciudad Guayana             | 5         | 2.1%    |
| Vigia                      | 4         | 1.68%   |
| Porlamar                   | 4         | 1.68%   |
| San Juan de los Morros     | 3         | 1.26%   |
| San Cristóbal             | 3         | 1.26%   |
| San Carlos del Zulia       | 3         | 1.26%   |
| Maturín                   | 3         | 1.26%   |
| Lecherias                  | 3         | 1.26%   |
| Coro                       | 3         | 1.26%   |
| Barinas                    | 3         | 1.26%   |
| San Antonio de Los Altos   | 2         | 0.84%   |
| Punto Fijo                 | 2         | 0.84%   |
| Puerto Ordaz and San Felix | 2         | 0.84%   |
| Miranda                    | 2         | 0.84%   |
| La Guaira                  | 2         | 0.84%   |
| Guatire                    | 2         | 0.84%   |
| Distrito Federal           | 2         | 0.84%   |
| Cambural                   | 2         | 0.84%   |
| Cagua                      | 2         | 0.84%   |
| Araure                     | 2         | 0.84%   |
| Anaco                      | 2         | 0.84%   |
| Acarigua                   | 2         | 0.84%   |
| Villa de Cura              | 1         | 0.42%   |
| Tucape                     | 1         | 0.42%   |
| San Juan Bautista          | 1         | 0.42%   |
| San Jose de Guanipa        | 1         | 0.42%   |
| San Fernando de Apure      | 1         | 0.42%   |
| San Felipe                 | 1         | 0.42%   |
| San Diego                  | 1         | 0.42%   |
| Puerto Cumarebo            | 1         | 0.42%   |
| Puerto Cruz                | 1         | 0.42%   |
| Petare                     | 1         | 0.42%   |
| Parroquia El Recreo        | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 40        | 43     | 15.21%  |
| WDC                         | 33        | 46     | 12.55%  |
| Toshiba                     | 25        | 27     | 9.51%   |
| Samsung Electronics         | 21        | 24     | 7.98%   |
| Unknown                     | 20        | 27     | 7.6%    |
| SanDisk                     | 12        | 18     | 4.56%   |
| Intel                       | 12        | 17     | 4.56%   |
| Hitachi                     | 11        | 12     | 4.18%   |
| Micron Technology           | 9         | 12     | 3.42%   |
| Kingston                    | 7         | 10     | 2.66%   |
| addlink                     | 7         | 8      | 2.66%   |
| LITEONIT                    | 6         | 10     | 2.28%   |
| Crucial                     | 6         | 9      | 2.28%   |
| SK hynix                    | 5         | 8      | 1.9%    |
| HGST                        | 5         | 5      | 1.9%    |
| PNY                         | 4         | 4      | 1.52%   |
| SPCC                        | 3         | 6      | 1.14%   |
| Patriot                     | 3         | 3      | 1.14%   |
| Team                        | 2         | 2      | 0.76%   |
| Silicon Motion              | 2         | 3      | 0.76%   |
| Micron/Crucial Technology   | 2         | 2      | 0.76%   |
| HUAWEI                      | 2         | 2      | 0.76%   |
| Fujitsu                     | 2         | 2      | 0.76%   |
| Dahua                       | 2         | 2      | 0.76%   |
| China                       | 2         | 2      | 0.76%   |
| BIWIN                       | 2         | 3      | 0.76%   |
| A-DATA Technology           | 2         | 2      | 0.76%   |
| WALRAM                      | 1         | 1      | 0.38%   |
| Vaseky                      | 1         | 2      | 0.38%   |
| UMIS                        | 1         | 4      | 0.38%   |
| Saichi                      | 1         | 2      | 0.38%   |
| PUSKILL                     | 1         | 1      | 0.38%   |
| Phison Electronics          | 1         | 1      | 0.38%   |
| Phison                      | 1         | 1      | 0.38%   |
| Netac                       | 1         | 1      | 0.38%   |
| Lexar                       | 1         | 1      | 0.38%   |
| Kingston Technology Company | 1         | 1      | 0.38%   |
| KingFast                    | 1         | 3      | 0.38%   |
| Intenso                     | 1         | 1      | 0.38%   |
| Emtec                       | 1         | 2      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB                 | 5         | 1.85%   |
| LITEONIT LMS-32L6M 32GB SSD                     | 5         | 1.85%   |
| WDC WD3200BPVT-22JJ5T0 320GB                    | 4         | 1.48%   |
| Seagate ST500LT012-9WS142 500GB                 | 4         | 1.48%   |
| WDC WD1600BEVT-22ZCT0 160GB                     | 3         | 1.11%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 3         | 1.11%   |
| Unknown NVMe SSD Drive 512GB                    | 3         | 1.11%   |
| Unknown MMC Card  16GB                          | 3         | 1.11%   |
| Unknown HAG2e  16GB                             | 3         | 1.11%   |
| Toshiba MQ04ABF100 1TB                          | 3         | 1.11%   |
| Seagate ST500LM021-1KJ152 500GB                 | 3         | 1.11%   |
| Seagate ST320LT012-9WS14C 320GB                 | 3         | 1.11%   |
| Seagate ST250LM004 HN-M250MBB 250GB             | 3         | 1.11%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                   | 3         | 1.11%   |
| addlink SATA SSD 120GB                          | 3         | 1.11%   |
| WDC WD5000LPVX-22V0TT0 500GB                    | 2         | 0.74%   |
| WDC WD5000LPVT-08G33T1 500GB                    | 2         | 0.74%   |
| WDC WD3200BEVT-00A0RT0 320GB                    | 2         | 0.74%   |
| WDC WD1200BEVS-60UST0 120GB                     | 2         | 0.74%   |
| Unknown MMC Card  64GB                          | 2         | 0.74%   |
| Toshiba MQ01ABF050 500GB                        | 2         | 0.74%   |
| Toshiba MQ01ABF032 320GB                        | 2         | 0.74%   |
| Toshiba MQ01ABD050 500GB                        | 2         | 0.74%   |
| Toshiba MK3276GSX 320GB                         | 2         | 0.74%   |
| Toshiba MK3275GSX 320GB                         | 2         | 0.74%   |
| SK hynix HFM001TD3JX013N 1024GB                 | 2         | 0.74%   |
| Seagate ST9500325AS 500GB                       | 2         | 0.74%   |
| Seagate ST9320325AS 320GB                       | 2         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB                 | 2         | 0.74%   |
| Seagate ST320LM001 HN-M320MBB 320GB             | 2         | 0.74%   |
| Seagate ST320LM000 HM321HI 320GB                | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 2         | 0.74%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB | 2         | 0.74%   |
| SanDisk NVMe SSD Drive 1TB                      | 2         | 0.74%   |
| Samsung MZALQ512HBLU-00BL2 512GB                | 2         | 0.74%   |
| Samsung HN-M320MBB 320GB                        | 2         | 0.74%   |
| Samsung HM250HI 250GB                           | 2         | 0.74%   |
| PNY CS900 480GB SSD                             | 2         | 0.74%   |
| PNY CS900 1TB SSD                               | 2         | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB           | 2         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 39     | 31.36%  |
| WDC                 | 31        | 41     | 26.27%  |
| Toshiba             | 23        | 25     | 19.49%  |
| Hitachi             | 11        | 12     | 9.32%   |
| Samsung Electronics | 8         | 8      | 6.78%   |
| HGST                | 5         | 5      | 4.24%   |
| Fujitsu             | 2         | 2      | 1.69%   |
| Unknown             | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 9      | 9.84%   |
| LITEONIT            | 6         | 10     | 9.84%   |
| Crucial             | 6         | 9      | 9.84%   |
| addlink             | 5         | 6      | 8.2%    |
| PNY                 | 4         | 4      | 6.56%   |
| Kingston            | 4         | 7      | 6.56%   |
| Patriot             | 3         | 3      | 4.92%   |
| Toshiba             | 2         | 2      | 3.28%   |
| SPCC                | 2         | 4      | 3.28%   |
| SanDisk             | 2         | 3      | 3.28%   |
| Intel               | 2         | 2      | 3.28%   |
| China               | 2         | 2      | 3.28%   |
| A-DATA Technology   | 2         | 2      | 3.28%   |
| WALRAM              | 1         | 1      | 1.64%   |
| Vaseky              | 1         | 2      | 1.64%   |
| Unknown             | 1         | 1      | 1.64%   |
| Team                | 1         | 1      | 1.64%   |
| Saichi              | 1         | 2      | 1.64%   |
| PUSKILL             | 1         | 1      | 1.64%   |
| Netac               | 1         | 1      | 1.64%   |
| Micron Technology   | 1         | 3      | 1.64%   |
| Lexar               | 1         | 1      | 1.64%   |
| KingFast            | 1         | 3      | 1.64%   |
| Intenso             | 1         | 1      | 1.64%   |
| Emtec               | 1         | 2      | 1.64%   |
| Dell                | 1         | 2      | 1.64%   |
| Dahua               | 1         | 1      | 1.64%   |
| BIWIN               | 1         | 2      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 117       | 133    | 46.61%  |
| SSD     | 59        | 87     | 23.51%  |
| NVMe    | 54        | 86     | 21.51%  |
| MMC     | 15        | 21     | 5.98%   |
| Unknown | 6         | 7      | 2.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 158       | 216    | 66.67%  |
| NVMe | 54        | 86     | 22.78%  |
| MMC  | 15        | 21     | 6.33%   |
| SAS  | 10        | 11     | 4.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 142       | 181    | 82.08%  |
| 0.51-1.0   | 30        | 38     | 17.34%  |
| 1.01-2.0   | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 69        | 29.74%  |
| 101-250        | 61        | 26.29%  |
| 501-1000       | 35        | 15.09%  |
| 1-20           | 25        | 10.78%  |
| 51-100         | 16        | 6.9%    |
| 21-50          | 11        | 4.74%   |
| 1001-2000      | 8         | 3.45%   |
| 2001-3000      | 3         | 1.29%   |
| More than 3000 | 2         | 0.86%   |
| Unknown        | 2         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 90        | 36.14%  |
| 21-50     | 51        | 20.48%  |
| 51-100    | 38        | 15.26%  |
| 101-250   | 36        | 14.46%  |
| 251-500   | 20        | 8.03%   |
| 501-1000  | 10        | 4.02%   |
| Unknown   | 2         | 0.8%    |
| 2001-3000 | 1         | 0.4%    |
| 0         | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-60UST0 120GB          | 2         | 2      | 5.41%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 5.41%   |
| Samsung Electronics HM250HI 250GB    | 2         | 2      | 5.41%   |
| Hitachi HTS725050A9A364 500GB        | 2         | 2      | 5.41%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 2.7%    |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 2.7%    |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 1      | 2.7%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 2.7%    |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 2.7%    |
| Toshiba MK3276GSX 320GB              | 1         | 1      | 2.7%    |
| Toshiba MK3275GSX 320GB              | 1         | 2      | 2.7%    |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 2.7%    |
| Toshiba MK2565GSX 250GB              | 1         | 1      | 2.7%    |
| Toshiba MK1032GSX 99GB               | 1         | 1      | 2.7%    |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 2.7%    |
| Seagate ST9320325AS 320GB            | 1         | 1      | 2.7%    |
| Seagate ST9160314AS 160GB            | 1         | 1      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 2.7%    |
| Seagate ST320LT012-1DG14C 320GB      | 1         | 1      | 2.7%    |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 2.7%    |
| Samsung Electronics HM321HI 320GB    | 1         | 1      | 2.7%    |
| Samsung Electronics HM121HI 120GB    | 1         | 1      | 2.7%    |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 2.7%    |
| Intel SSDPEKKF512G7L 512GB           | 1         | 1      | 2.7%    |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 2.7%    |
| Hitachi HTS543232A7A384 320GB        | 1         | 1      | 2.7%    |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 2.7%    |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 2.7%    |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 2.7%    |
| HGST HTS541010A7E630 1TB             | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 21.62%  |
| Toshiba             | 7         | 8      | 18.92%  |
| WDC                 | 6         | 7      | 16.22%  |
| Hitachi             | 6         | 6      | 16.22%  |
| Samsung Electronics | 5         | 5      | 13.51%  |
| Intel               | 2         | 2      | 5.41%   |
| HGST                | 2         | 2      | 5.41%   |
| SK hynix            | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 23.53%  |
| Toshiba             | 7         | 8      | 20.59%  |
| WDC                 | 6         | 7      | 17.65%  |
| Hitachi             | 6         | 6      | 17.65%  |
| Samsung Electronics | 5         | 5      | 14.71%  |
| HGST                | 2         | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 36     | 91.89%  |
| NVMe | 3         | 3      | 8.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM160HI 160GB | 1         | 1      | 100%    |

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
| Detected | 109       | 170    | 46.58%  |
| Works    | 87        | 124    | 37.18%  |
| Malfunc  | 37        | 39     | 15.81%  |
| Failed   | 1         | 1      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 171       | 69.51%  |
| AMD                         | 25        | 10.16%  |
| SanDisk                     | 11        | 4.47%   |
| Micron Technology           | 8         | 3.25%   |
| Samsung Electronics         | 7         | 2.85%   |
| SK hynix                    | 5         | 2.03%   |
| Phison Electronics          | 4         | 1.63%   |
| Kingston Technology Company | 4         | 1.63%   |
| Silicon Motion              | 3         | 1.22%   |
| Jiangsu Huacun Elec.        | 3         | 1.22%   |
| Micron/Crucial Technology   | 2         | 0.81%   |
| Union Memory (Shenzhen)     | 1         | 0.41%   |
| MAXIO Technology (Hangzhou) | 1         | 0.41%   |
| INNOGRIT                    | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 27        | 9.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 6.91%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 6.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 5.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 11        | 4%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 11        | 4%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 4%      |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.64%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 8         | 2.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 8         | 2.91%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 6         | 2.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.18%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 2.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 4         | 1.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.45%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.09%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 3         | 1.09%   |
| Jiangsu Huacun Elec. MMY MMSP350 PCIe 3 NVMe SSD (DRAM-less)                   | 3         | 1.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.09%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.73%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 0.73%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.73%   |
| Kingston Company NV2 NVMe SSD [SM2269XT] (DRAM-less)                           | 2         | 0.73%   |
| Intel SSD 600P Series                                                          | 2         | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.73%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.73%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 151       | 57.63%  |
| NVMe | 54        | 20.61%  |
| RAID | 30        | 11.45%  |
| IDE  | 27        | 10.31%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 185       | 84.86%  |
| AMD          | 30        | 13.76%  |
| CentaurHauls | 3         | 1.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz                | 8         | 3.67%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 7         | 3.21%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 6         | 2.75%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 5         | 2.29%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 4         | 1.83%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 4         | 1.83%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 4         | 1.83%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 1.38%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 3         | 1.38%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 3         | 1.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 3         | 1.38%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 1.38%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 3         | 1.38%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 3         | 1.38%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 1.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 3         | 1.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 3         | 1.38%   |
| Intel 13th Gen Core i9-13900H                  | 3         | 1.38%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 1.38%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 1.38%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 3         | 1.38%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 2         | 0.92%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 0.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 2         | 0.92%   |
| Intel Core i5 CPU M 560 @ 2.67GHz              | 2         | 0.92%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 2         | 0.92%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 2         | 0.92%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 2         | 0.92%   |
| Intel Core i3-2310M CPU @ 2.10GHz              | 2         | 0.92%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 2         | 0.92%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 2         | 0.92%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz           | 2         | 0.92%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 2         | 0.92%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 2         | 0.92%   |
| Intel Atom CPU N570 @ 1.66GHz                  | 2         | 0.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 0.92%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz        | 2         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 37        | 16.97%  |
| Intel Core i3                        | 33        | 15.14%  |
| Other                                | 25        | 11.47%  |
| Intel Celeron                        | 24        | 11.01%  |
| Intel Core i7                        | 20        | 9.17%   |
| Intel Core 2 Duo                     | 17        | 7.8%    |
| Intel Atom                           | 12        | 5.5%    |
| Intel Pentium                        | 8         | 3.67%   |
| AMD Ryzen 7                          | 7         | 3.21%   |
| AMD Ryzen 5                          | 7         | 3.21%   |
| Intel Pentium Dual                   | 5         | 2.29%   |
| Intel Pentium Dual-Core              | 2         | 0.92%   |
| Intel Genuine                        | 2         | 0.92%   |
| Intel Core 2                         | 2         | 0.92%   |
| AMD Ryzen 3                          | 2         | 0.92%   |
| AMD E                                | 2         | 0.92%   |
| AMD C-70                             | 2         | 0.92%   |
| AMD A10                              | 2         | 0.92%   |
| Intel Pentium Silver                 | 1         | 0.46%   |
| Intel Core i9                        | 1         | 0.46%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.46%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.46%   |
| AMD Quad-Core                        | 1         | 0.46%   |
| AMD Phenom II                        | 1         | 0.46%   |
| AMD Mobile Sempron                   | 1         | 0.46%   |
| AMD E1                               | 1         | 0.46%   |
| AMD A6                               | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 142       | 65.14%  |
| 4       | 35        | 16.06%  |
| 8       | 11        | 5.05%   |
| 1       | 10        | 4.59%   |
| 6       | 8         | 3.67%   |
| 14      | 4         | 1.83%   |
| 24      | 2         | 0.92%   |
| 12      | 2         | 0.92%   |
| 10      | 2         | 0.92%   |
| Unknown | 2         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 218       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 139       | 63.76%  |
| 1       | 77        | 35.32%  |
| Unknown | 2         | 0.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 212       | 97.25%  |
| 64-bit         | 3         | 1.38%   |
| 32-bit         | 3         | 1.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 40.09%  |
| 0x206a7    | 18        | 7.76%   |
| 0x306a9    | 17        | 7.33%   |
| 0x1067a    | 11        | 4.74%   |
| 0x6fd      | 8         | 3.45%   |
| 0x30678    | 7         | 3.02%   |
| 0x106ca    | 7         | 3.02%   |
| 0x806e9    | 5         | 2.16%   |
| 0x20655    | 5         | 2.16%   |
| 0x806c1    | 4         | 1.72%   |
| 0x806ec    | 3         | 1.29%   |
| 0x406e3    | 3         | 1.29%   |
| 0x40651    | 3         | 1.29%   |
| 0x306c3    | 3         | 1.29%   |
| 0x05000119 | 3         | 1.29%   |
| 0x806ea    | 2         | 0.86%   |
| 0x806d1    | 2         | 0.86%   |
| 0x306d4    | 2         | 0.86%   |
| 0x30673    | 2         | 0.86%   |
| 0x08608103 | 2         | 0.86%   |
| 0x08108102 | 2         | 0.86%   |
| 0x0500010d | 2         | 0.86%   |
| 0x02000057 | 2         | 0.86%   |
| 0x906ea    | 1         | 0.43%   |
| 0x906e9    | 1         | 0.43%   |
| 0x906a4    | 1         | 0.43%   |
| 0x806eb    | 1         | 0.43%   |
| 0x806c2    | 1         | 0.43%   |
| 0x706e5    | 1         | 0.43%   |
| 0x706a8    | 1         | 0.43%   |
| 0x6f6      | 1         | 0.43%   |
| 0x6ec      | 1         | 0.43%   |
| 0x506e3    | 1         | 0.43%   |
| 0x406c4    | 1         | 0.43%   |
| 0x30661    | 1         | 0.43%   |
| 0x20652    | 1         | 0.43%   |
| 0x106c2    | 1         | 0.43%   |
| 0x0a50000d | 1         | 0.43%   |
| 0x08608104 | 1         | 0.43%   |
| 0x08600104 | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 29        | 13.3%   |
| IvyBridge        | 25        | 11.47%  |
| KabyLake         | 17        | 7.8%    |
| Core             | 16        | 7.34%   |
| Westmere         | 15        | 6.88%   |
| Silvermont       | 13        | 5.96%   |
| Penryn           | 11        | 5.05%   |
| Bonnell          | 11        | 5.05%   |
| Unknown          | 11        | 5.05%   |
| Alderlake Hybrid | 9         | 4.13%   |
| TigerLake        | 7         | 3.21%   |
| Haswell          | 7         | 3.21%   |
| IceLake          | 6         | 2.75%   |
| Bobcat           | 5         | 2.29%   |
| Zen+             | 4         | 1.83%   |
| Skylake          | 4         | 1.83%   |
| Goldmont plus    | 4         | 1.83%   |
| CometLake        | 4         | 1.83%   |
| Zen 2            | 3         | 1.38%   |
| Excavator        | 3         | 1.38%   |
| Broadwell        | 3         | 1.38%   |
| Zen              | 2         | 0.92%   |
| K8 & K10 hybrid  | 2         | 0.92%   |
| Zen 3            | 1         | 0.46%   |
| Steamroller      | 1         | 0.46%   |
| P6               | 1         | 0.46%   |
| K8 Hammer        | 1         | 0.46%   |
| K10              | 1         | 0.46%   |
| Jaguar           | 1         | 0.46%   |
| Goldmont         | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 180       | 74.69%  |
| AMD     | 33        | 13.69%  |
| Nvidia  | 25        | 10.37%  |
| Zhaoxin | 3         | 1.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 10.94%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 9.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 5.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 4.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 4.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 4.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 3.52%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 9         | 3.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.73%   |
| Intel HD Graphics 620                                                                    | 5         | 1.95%   |
| AMD Lucienne                                                                             | 5         | 1.95%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.56%   |
| Zhaoxin KX-6000 C-960 GPU                                                                | 3         | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.17%   |
| Nvidia GA107M [GeForce RTX 3050 4GB Laptop GPU]                                          | 3         | 1.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.17%   |
| Intel HD Graphics 630                                                                    | 3         | 1.17%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.17%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.78%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 2         | 0.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.78%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.78%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 2         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.78%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 2         | 0.78%   |
| AMD Wrestler [Radeon HD 7290]                                                            | 2         | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.78%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 2         | 0.78%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 152       | 69.41%  |
| 1 x AMD        | 28        | 12.79%  |
| Intel + Nvidia | 17        | 7.76%   |
| 2 x Intel      | 7         | 3.2%    |
| 1 x Nvidia     | 6         | 2.74%   |
| 1 x Zhaoxin    | 3         | 1.37%   |
| Intel + AMD    | 3         | 1.37%   |
| AMD + Nvidia   | 2         | 0.91%   |
| Other          | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 193       | 87.73%  |
| Proprietary | 18        | 8.18%   |
| Unknown     | 9         | 4.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 183       | 82.81%  |
| 0.01-0.5   | 22        | 9.95%   |
| 1.01-2.0   | 6         | 2.71%   |
| 3.01-4.0   | 4         | 1.81%   |
| 0.51-1.0   | 4         | 1.81%   |
| 5.01-6.0   | 2         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 39        | 15.98%  |
| AU Optronics            | 39        | 15.98%  |
| BOE                     | 38        | 15.57%  |
| LG Display              | 29        | 11.89%  |
| Chimei Innolux          | 27        | 11.07%  |
| Lenovo                  | 10        | 4.1%    |
| InfoVision              | 10        | 4.1%    |
| Chi Mei Optoelectronics | 8         | 3.28%   |
| LG Philips              | 7         | 2.87%   |
| Hewlett-Packard         | 6         | 2.46%   |
| HannStar                | 4         | 1.64%   |
| Goldstar                | 4         | 1.64%   |
| PANDA                   | 3         | 1.23%   |
| InnoLux Display         | 3         | 1.23%   |
| Dell                    | 3         | 1.23%   |
| ViewSonic               | 2         | 0.82%   |
| Toshiba                 | 2         | 0.82%   |
| Vizio                   | 1         | 0.41%   |
| Vita                    | 1         | 0.41%   |
| Sharp                   | 1         | 0.41%   |
| Sceptre Tech            | 1         | 0.41%   |
| MStar                   | 1         | 0.41%   |
| KTC                     | 1         | 0.41%   |
| HKC                     | 1         | 0.41%   |
| CPT                     | 1         | 0.41%   |
| ASUSTek Computer        | 1         | 0.41%   |
| Acer                    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 7         | 2.85%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 6         | 2.44%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 310x170mm 13.9-inch        | 5         | 2.03%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 4         | 1.63%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch          | 4         | 1.63%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch | 3         | 1.22%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 1.22%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 1.22%   |
| Chimei Innolux N160JME-GL2 CMN1627 1920x1200 344x215mm 16.0-inch     | 3         | 1.22%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 1.22%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 3         | 1.22%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 3         | 1.22%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch | 2         | 0.81%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch    | 2         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.81%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch        | 2         | 0.81%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch        | 2         | 0.81%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 2         | 0.81%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 2         | 0.81%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.81%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.81%   |
| InnoLux Display LCD Monitor CMI001B 1366x768 309x174mm 14.0-inch     | 2         | 0.81%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.81%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 2         | 0.81%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                 | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch       | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch       | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO115C 1366x768 256x144mm 11.6-inch        | 2         | 0.81%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                 | 1         | 0.41%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 1         | 0.41%   |
| ViewSonic VA2252 Series VSC7731 1920x1080 476x268mm 21.5-inch        | 1         | 0.41%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch         | 1         | 0.41%   |
| Toshiba LCD-MONITOR LCDE981 1280x720 400x250mm 18.6-inch             | 1         | 0.41%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 114       | 50%     |
| 1920x1080 (FHD)    | 58        | 25.44%  |
| 1280x800 (WXGA)    | 20        | 8.77%   |
| 1920x1200 (WUXGA)  | 6         | 2.63%   |
| 1600x900 (HD+)     | 5         | 2.19%   |
| 1440x900 (WXGA+)   | 5         | 2.19%   |
| 3840x2160 (4K)     | 3         | 1.32%   |
| 2240x1400          | 3         | 1.32%   |
| 1280x1024 (SXGA)   | 3         | 1.32%   |
| 1024x600           | 3         | 1.32%   |
| 2560x1440 (QHD)    | 2         | 0.88%   |
| 1680x1050 (WSXGA+) | 2         | 0.88%   |
| 1360x768           | 2         | 0.88%   |
| 2560x1600          | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 85        | 34.98%  |
| 14      | 50        | 20.58%  |
| 13      | 36        | 14.81%  |
| 21      | 11        | 4.53%   |
| 11      | 10        | 4.12%   |
| 17      | 9         | 3.7%    |
| 18      | 7         | 2.88%   |
| 10      | 6         | 2.47%   |
| 16      | 5         | 2.06%   |
| 27      | 3         | 1.23%   |
| 24      | 3         | 1.23%   |
| 23      | 3         | 1.23%   |
| 19      | 3         | 1.23%   |
| 12      | 3         | 1.23%   |
| 32      | 2         | 0.82%   |
| Unknown | 2         | 0.82%   |
| 54      | 1         | 0.41%   |
| 52      | 1         | 0.41%   |
| 31      | 1         | 0.41%   |
| 22      | 1         | 0.41%   |
| 20      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 172       | 71.07%  |
| 401-500     | 22        | 9.09%   |
| 201-300     | 21        | 8.68%   |
| 351-400     | 12        | 4.96%   |
| 501-600     | 8         | 3.31%   |
| 701-800     | 2         | 0.83%   |
| 1001-1500   | 2         | 0.83%   |
| Unknown     | 2         | 0.83%   |
| 601-700     | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 175       | 80.65%  |
| 16/10 | 39        | 17.97%  |
| 5/4   | 2         | 0.92%   |
| 3/2   | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 85        | 34.98%  |
| 81-90          | 84        | 34.57%  |
| 201-250        | 11        | 4.53%   |
| 51-60          | 10        | 4.12%   |
| 151-200        | 10        | 4.12%   |
| 121-130        | 8         | 3.29%   |
| 41-50          | 6         | 2.47%   |
| 141-150        | 6         | 2.47%   |
| 111-120        | 5         | 2.06%   |
| 61-70          | 3         | 1.23%   |
| 351-500        | 3         | 1.23%   |
| 301-350        | 3         | 1.23%   |
| 251-300        | 3         | 1.23%   |
| More than 1000 | 2         | 0.82%   |
| 71-80          | 2         | 0.82%   |
| Unknown        | 2         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 106       | 44.35%  |
| 121-160       | 74        | 30.96%  |
| 51-100        | 46        | 19.25%  |
| 161-240       | 6         | 2.51%   |
| 1-50          | 4         | 1.67%   |
| Unknown       | 2         | 0.84%   |
| More than 240 | 1         | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 180       | 79.3%   |
| 2     | 37        | 16.3%   |
| 0     | 7         | 3.08%   |
| 3     | 3         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 136       | 37.67%  |
| Intel                           | 84        | 23.27%  |
| Qualcomm Atheros                | 74        | 20.5%   |
| Broadcom                        | 22        | 6.09%   |
| MediaTek                        | 9         | 2.49%   |
| Broadcom Limited                | 9         | 2.49%   |
| TP-Link                         | 5         | 1.39%   |
| Xiaomi                          | 3         | 0.83%   |
| Marvell Technology Group        | 3         | 0.83%   |
| JMicron Technology              | 3         | 0.83%   |
| Samsung Electronics             | 2         | 0.55%   |
| Qualcomm Atheros Communications | 2         | 0.55%   |
| ASIX Electronics                | 2         | 0.55%   |
| ZyXEL Communications            | 1         | 0.28%   |
| Trendchip Technologies          | 1         | 0.28%   |
| TP-Link Corporation Limited.    | 1         | 0.28%   |
| Ralink Technology               | 1         | 0.28%   |
| Ralink                          | 1         | 0.28%   |
| Huawei Technologies             | 1         | 0.28%   |
| AMD                             | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 71        | 17.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 28        | 6.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 5.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 2.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 2.64%   |
| Intel Wireless 7265                                                     | 10        | 2.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 9         | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 1.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 6         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 1.44%   |
| Intel Wireless 7260                                                     | 6         | 1.44%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 5         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.2%    |
| Intel Wireless 8265 / 8275                                              | 5         | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.2%    |
| Intel WiFi Link 5100                                                    | 4         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.72%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 0.72%   |
| Intel Wireless 3165                                                     | 3         | 0.72%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.72%   |
| Intel Ethernet Connection (13) I219-V                                   | 3         | 0.72%   |
| Intel Centrino Wireless-N 105                                           | 3         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.72%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express             | 3         | 0.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 34.67%  |
| Qualcomm Atheros                | 56        | 24.89%  |
| Realtek Semiconductor           | 51        | 22.67%  |
| Broadcom                        | 17        | 7.56%   |
| MediaTek                        | 9         | 4%      |
| TP-Link                         | 5         | 2.22%   |
| Broadcom Limited                | 4         | 1.78%   |
| Qualcomm Atheros Communications | 2         | 0.89%   |
| Xiaomi                          | 1         | 0.44%   |
| Ralink Technology               | 1         | 0.44%   |
| Ralink                          | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 10.67%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 5.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 4.89%   |
| Intel Wireless 7265                                                     | 10        | 4.44%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 9         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 3.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 3.11%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 6         | 2.67%   |
| Intel Wireless 7260                                                     | 6         | 2.67%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.22%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.22%   |
| Intel WiFi Link 5100                                                    | 4         | 1.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.33%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 1.33%   |
| Intel Wireless 3165                                                     | 3         | 1.33%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.33%   |
| Intel Centrino Wireless-N 105                                           | 3         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.89%   |
| Intel Wireless 8260                                                     | 2         | 0.89%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 2         | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.89%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.89%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.89%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Realtek Semiconductor        | 109       | 58.6%   |
| Intel                        | 27        | 14.52%  |
| Qualcomm Atheros             | 26        | 13.98%  |
| Broadcom                     | 6         | 3.23%   |
| Broadcom Limited             | 5         | 2.69%   |
| Marvell Technology Group     | 3         | 1.61%   |
| JMicron Technology           | 3         | 1.61%   |
| Xiaomi                       | 2         | 1.08%   |
| ASIX Electronics             | 2         | 1.08%   |
| ZyXEL Communications         | 1         | 0.54%   |
| Trendchip Technologies       | 1         | 0.54%   |
| TP-Link Corporation Limited. | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 71        | 37.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28        | 14.89%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 7         | 3.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 3.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.66%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.13%   |
| Intel Ethernet Connection (13) I219-V                                  | 3         | 1.6%    |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 3         | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.06%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 1.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 1.06%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.06%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.06%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.06%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                 | 2         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.06%   |
| ZyXEL ADSL Modem Prestige 600 series                                   | 1         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.53%   |
| Trendchip Ethernet controller                                          | 1         | 0.53%   |
| TP-Link Corporation Limited. M7010                                     | 1         | 0.53%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]     | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.53%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.53%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 212       | 53.27%  |
| Ethernet | 182       | 45.73%  |
| Modem    | 4         | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 169       | 74.12%  |
| Ethernet | 59        | 25.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 171       | 78.44%  |
| 1     | 45        | 20.64%  |
| 0     | 2         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 216       | 97.74%  |
| Yes  | 5         | 2.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 38.41%  |
| Realtek Semiconductor           | 19        | 13.77%  |
| Qualcomm Atheros Communications | 19        | 13.77%  |
| IMC Networks                    | 19        | 13.77%  |
| Broadcom                        | 9         | 6.52%   |
| Lite-On Technology              | 5         | 3.62%   |
| Cambridge Silicon Radio         | 4         | 2.9%    |
| Dell                            | 3         | 2.17%   |
| Hewlett-Packard                 | 2         | 1.45%   |
| SiW                             | 1         | 0.72%   |
| Ralink Technology               | 1         | 0.72%   |
| Foxconn / Hon Hai               | 1         | 0.72%   |
| ASUSTek Computer                | 1         | 0.72%   |
| Alps Electric                   | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 26        | 18.84%  |
| Realtek Bluetooth Radio                                     | 12        | 8.7%    |
| Intel AX201 Bluetooth                                       | 12        | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                          | 7         | 5.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 5.07%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 7         | 5.07%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 6         | 4.35%   |
| IMC Networks Wireless_Device                                | 6         | 4.35%   |
| IMC Networks Bluetooth                                      | 4         | 2.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 2.9%    |
| Realtek RTL8723B Bluetooth                                  | 3         | 2.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.17%   |
| Intel AX200 Bluetooth                                       | 3         | 2.17%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 2.17%   |
| Realtek RTL8723A Bluetooth                                  | 2         | 1.45%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 2         | 1.45%   |
| Lite-On Wireless_Device                                     | 2         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.45%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 2         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 2         | 1.45%   |
| SiW SiW                                                     | 1         | 0.72%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.72%   |
| Realtek 802.11ac WLAN Adapter                               | 1         | 0.72%   |
| Ralink CSR BS8510                                           | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.72%   |
| Lite-On Bluetooth Device                                    | 1         | 0.72%   |
| Lite-On BCM20702A0                                          | 1         | 0.72%   |
| Intel AX211 Bluetooth                                       | 1         | 0.72%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.72%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.72%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.72%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 0.72%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.72%   |
| Broadcom HP Portable Valentine                              | 1         | 0.72%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.72%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 185       | 75.51%  |
| AMD                   | 33        | 13.47%  |
| Nvidia                | 18        | 7.35%   |
| Zhaoxin               | 3         | 1.22%   |
| Texas Instruments     | 1         | 0.41%   |
| Realtek Semiconductor | 1         | 0.41%   |
| Microsoft             | 1         | 0.41%   |
| Logitech              | 1         | 0.41%   |
| Corsair               | 1         | 0.41%   |
| ASUSTek Computer      | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 12.28%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 6.67%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 16        | 5.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 5.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 4.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 4.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 4.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 3.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.11%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.75%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.4%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.4%    |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 1.05%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller         | 3         | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.05%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.05%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.05%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.7%    |
| Nvidia GA107 High Definition Audio Controller                                                     | 2         | 0.7%    |
| Nvidia AD107 High Definition Audio Controller                                                     | 2         | 0.7%    |
| Nvidia AD106M High Definition Audio Controller                                                    | 2         | 0.7%    |
| Intel Raptor Lake High Definition Audio Controller                                                | 2         | 0.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 19.9%   |
| SK hynix            | 34        | 17.8%   |
| Ramaxel Technology  | 23        | 12.04%  |
| Micron Technology   | 21        | 10.99%  |
| Unknown             | 20        | 10.47%  |
| Kingston            | 11        | 5.76%   |
| Crucial             | 11        | 5.76%   |
| Elpida              | 5         | 2.62%   |
| PNY                 | 3         | 1.57%   |
| Unknown (ABCD)      | 2         | 1.05%   |
| Timetec             | 2         | 1.05%   |
| Shenzhen WODPOSIT   | 2         | 1.05%   |
| Qimonda             | 2         | 1.05%   |
| Memox               | 2         | 1.05%   |
| A-DATA Technology   | 2         | 1.05%   |
| Unknown             | 2         | 1.05%   |
| Unknown (081A)      | 1         | 0.52%   |
| Unknown (07F7)      | 1         | 0.52%   |
| Transcend           | 1         | 0.52%   |
| Team                | 1         | 0.52%   |
| Hikvision           | 1         | 0.52%   |
| Gold Key            | 1         | 0.52%   |
| ff                  | 1         | 0.52%   |
| Corsair             | 1         | 0.52%   |
| <Invalid>           | 1         | 0.52%   |
| 4ea5                | 1         | 0.52%   |
| 48spaces            | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s   | 7         | 3.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 6         | 2.97%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s   | 5         | 2.48%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s   | 5         | 2.48%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s     | 4         | 1.98%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 1.98%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s   | 4         | 1.98%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s    | 3         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.49%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s | 3         | 1.49%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s      | 3         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 0.99%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                | 2         | 0.99%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s  | 2         | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.99%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 0.99%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 2         | 0.99%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.99%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s     | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s  | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.99%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s    | 2         | 0.99%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s       | 2         | 0.99%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s   | 2         | 0.99%   |
| Micron RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 800MT/s     | 2         | 0.99%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s      | 2         | 0.99%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s    | 2         | 0.99%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s   | 2         | 0.99%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s     | 2         | 0.99%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s     | 2         | 0.99%   |
| Crucial RAM CT25664BF160B.M8FK 2GB SODIMM DDR3 1333MT/s   | 2         | 0.99%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s   | 2         | 0.99%   |
| Unknown                                                   | 2         | 0.99%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.5%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM SDRAM                       | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 57        | 38.78%  |
| DDR4   | 54        | 36.73%  |
| DDR2   | 19        | 12.93%  |
| SDRAM  | 8         | 5.44%   |
| LPDDR4 | 4         | 2.72%   |
| DDR5   | 2         | 1.36%   |
| DDR    | 2         | 1.36%   |
| LPDDR3 | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 135       | 94.41%  |
| Row Of Chips | 5         | 3.5%    |
| Unknown      | 2         | 1.4%    |
| DIMM         | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 50        | 29.76%  |
| 2048  | 50        | 29.76%  |
| 4096  | 42        | 25%     |
| 16384 | 14        | 8.33%   |
| 1024  | 10        | 5.95%   |
| 32768 | 2         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 40        | 23.95%  |
| 3200    | 32        | 19.16%  |
| 2667    | 22        | 13.17%  |
| 667     | 12        | 7.19%   |
| 1333    | 11        | 6.59%   |
| 2400    | 10        | 5.99%   |
| 533     | 6         | 3.59%   |
| 1334    | 5         | 2.99%   |
| 4199    | 4         | 2.4%    |
| 2666    | 3         | 1.8%    |
| 2048    | 3         | 1.8%    |
| 1067    | 3         | 1.8%    |
| 800     | 3         | 1.8%    |
| Unknown | 3         | 1.8%    |
| 3266    | 2         | 1.2%    |
| 1867    | 2         | 1.2%    |
| 975     | 2         | 1.2%    |
| 5600    | 1         | 0.6%    |
| 4800    | 1         | 0.6%    |
| 2133    | 1         | 0.6%    |
| 1066    | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung ML-1865        | 1         | 33.33%  |
| HP LaserJet 1018       | 1         | 33.33%  |
| HP DeskJet 2300 series | 1         | 33.33%  |

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
| Chicony Electronics                    | 29        | 16.96%  |
| Microdia                               | 20        | 11.7%   |
| Bison Electronics                      | 18        | 10.53%  |
| Realtek Semiconductor                  | 14        | 8.19%   |
| IMC Networks                           | 14        | 8.19%   |
| Suyin                                  | 9         | 5.26%   |
| Sunplus Innovation Technology          | 9         | 5.26%   |
| Quanta                                 | 9         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.68%   |
| Luxvisions Innotech Limited            | 6         | 3.51%   |
| Syntek                                 | 5         | 2.92%   |
| Sonix Technology                       | 5         | 2.92%   |
| Acer                                   | 4         | 2.34%   |
| Ricoh                                  | 3         | 1.75%   |
| Lenovo                                 | 3         | 1.75%   |
| Importek                               | 3         | 1.75%   |
| ALi                                    | 3         | 1.75%   |
| Lite-On Technology                     | 2         | 1.17%   |
| Tobii Technology AB                    | 1         | 0.58%   |
| Silicon Motion                         | 1         | 0.58%   |
| OmniVision Technologies                | 1         | 0.58%   |
| Logitech                               | 1         | 0.58%   |
| icSpring                               | 1         | 0.58%   |
| Apple                                  | 1         | 0.58%   |
| Alcor Micro                            | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                          | 8         | 4.68%   |
| Bison USB Camera                                                | 7         | 4.09%   |
| Sunplus Integrated_Webcam_HD                                    | 6         | 3.51%   |
| Realtek Integrated_Webcam_HD                                    | 6         | 3.51%   |
| Microdia USB 2.0 Camera                                         | 6         | 3.51%   |
| Sonix USB2.0 HD UVC WebCam                                      | 5         | 2.92%   |
| Chicony Integrated Camera                                       | 5         | 2.92%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 2.34%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 4         | 2.34%   |
| Chicony Lenovo EasyCamera                                       | 4         | 2.34%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam   | 4         | 2.34%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 3         | 1.75%   |
| IMC Networks Integrated Camera                                  | 3         | 1.75%   |
| IMC Networks HD Camera                                          | 3         | 1.75%   |
| Bison HD Webcam                                                 | 3         | 1.75%   |
| Suyin Integrated_Webcam_HD                                      | 2         | 1.17%   |
| Suyin HP Webcam 101                                             | 2         | 1.17%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 2         | 1.17%   |
| Realtek Integrated Webcam HD                                    | 2         | 1.17%   |
| Quanta HD User Facing                                           | 2         | 1.17%   |
| Quanta ACER HD User Facing                                      | 2         | 1.17%   |
| Microdia Integrated_Webcam_1.3M                                 | 2         | 1.17%   |
| Lenovo CNF7237&CNF7238                                          | 2         | 1.17%   |
| IMC Networks Lenovo EasyCamera                                  | 2         | 1.17%   |
| Chicony HD WebCam                                               | 2         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD         | 2         | 1.17%   |
| Bison Lenovo EasyCamera                                         | 2         | 1.17%   |
| Bison Integrated Camera                                         | 2         | 1.17%   |
| Bison BisonCam, NB Pro                                          | 2         | 1.17%   |
| ALi WebCam                                                      | 2         | 1.17%   |
| Tobii AB EyeChip                                                | 1         | 0.58%   |
| Syntek USB Camera Device                                        | 1         | 0.58%   |
| Syntek USB 2.0 UVC PC Camera                                    | 1         | 0.58%   |
| Syntek Integrated Webcam                                        | 1         | 0.58%   |
| Syntek Integrated Camera                                        | 1         | 0.58%   |
| Syntek EasyCamera                                               | 1         | 0.58%   |
| Suyin USB2.0 UVC 1.3M WebCam                                    | 1         | 0.58%   |
| Suyin Integrated Webcam                                         | 1         | 0.58%   |
| Suyin HP TrueVision HD                                          | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 40.91%  |
| Upek                       | 3         | 13.64%  |
| AuthenTec                  | 3         | 13.64%  |
| Synaptics                  | 2         | 9.09%   |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| Elan Microelectronics      | 2         | 9.09%   |
| Futronic Technology        | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 13.64%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 13.64%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 9.09%   |
| Validity Sensors Fingerprint scanner                   | 2         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 9.09%   |
| Elan ELAN:ARM-M4                                       | 2         | 9.09%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4.55%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 4.55%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 4.55%   |
| AuthenTec AES1600                                      | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 81.82%  |
| Alcor Micro | 2         | 18.18%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 5         | 45.45%  |
| Broadcom BCM5880 Secure Applications Processor | 4         | 36.36%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 18.18%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 158       | 71.17%  |
| 1     | 48        | 21.62%  |
| 2     | 13        | 5.86%   |
| 4     | 2         | 0.9%    |
| 3     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 25        | 30.86%  |
| Fingerprint reader       | 22        | 27.16%  |
| Chipcard                 | 11        | 13.58%  |
| Net/wireless             | 9         | 11.11%  |
| Sound                    | 5         | 6.17%   |
| Camera                   | 4         | 4.94%   |
| Storage                  | 2         | 2.47%   |
| Multimedia controller    | 1         | 1.23%   |
| Communication controller | 1         | 1.23%   |
| Bluetooth                | 1         | 1.23%   |

