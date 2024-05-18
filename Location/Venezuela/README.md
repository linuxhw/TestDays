Linux in Venezuela - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Venezuela/Desktop/README.md) and [notebooks](/Location/Venezuela/Notebook/README.md).

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

Total: 642

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ECS           | H61H2-CM                    | Desktop     | [65f99c7e8d](https://linux-hardware.org/?probe=65f99c7e8d) | May 08, 2024 |
| Intel         | powered classmate PC        | Tablet      | [42a4f299a3](https://linux-hardware.org/?probe=42a4f299a3) | May 05, 2024 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [1ee81eb650](https://linux-hardware.org/?probe=1ee81eb650) | May 05, 2024 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [4fa09a0b8e](https://linux-hardware.org/?probe=4fa09a0b8e) | May 04, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [277b1dc273](https://linux-hardware.org/?probe=277b1dc273) | May 04, 2024 |
| Dell          | 0WR7PY A04                  | Desktop     | [b48e977e84](https://linux-hardware.org/?probe=b48e977e84) | May 03, 2024 |
| Notebook      | W54BL                       | Notebook    | [adb804fa7f](https://linux-hardware.org/?probe=adb804fa7f) | Apr 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [5fda06b27d](https://linux-hardware.org/?probe=5fda06b27d) | Apr 26, 2024 |
| Dell          | 040DDP A01                  | Desktop     | [7eea0dc663](https://linux-hardware.org/?probe=7eea0dc663) | Apr 25, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1cc02514fd](https://linux-hardware.org/?probe=1cc02514fd) | Apr 23, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [caf43c2754](https://linux-hardware.org/?probe=caf43c2754) | Apr 14, 2024 |
| Pegatron      | 2A73h                       | Desktop     | [941a2d0e0d](https://linux-hardware.org/?probe=941a2d0e0d) | Apr 10, 2024 |
| MSI           | NF725M-P43                  | Desktop     | [ff3656c7c8](https://linux-hardware.org/?probe=ff3656c7c8) | Apr 10, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [82fa2b1397](https://linux-hardware.org/?probe=82fa2b1397) | Apr 04, 2024 |
| HP            | Pavilion m6                 | Notebook    | [7573d33d4f](https://linux-hardware.org/?probe=7573d33d4f) | Apr 04, 2024 |
| Toshiba       | Satellite A205              | Notebook    | [4fcbf3184c](https://linux-hardware.org/?probe=4fcbf3184c) | Apr 02, 2024 |
| Pegatron      | 2A73h                       | Desktop     | [193e8e5cb1](https://linux-hardware.org/?probe=193e8e5cb1) | Mar 26, 2024 |
| ASRock        | H510M/ac                    | Desktop     | [37ecfed47c](https://linux-hardware.org/?probe=37ecfed47c) | Mar 25, 2024 |
| VENEZOLANA... | VIT P2460-02                | Notebook    | [c6fc091713](https://linux-hardware.org/?probe=c6fc091713) | Mar 24, 2024 |
| Dell          | Precision M4800             | Notebook    | [9a66a454e2](https://linux-hardware.org/?probe=9a66a454e2) | Mar 17, 2024 |
| Dell          | Precision M4800             | Notebook    | [c38442b3dc](https://linux-hardware.org/?probe=c38442b3dc) | Mar 17, 2024 |
| Unknown       | Unknown                     | Notebook    | [d00c774230](https://linux-hardware.org/?probe=d00c774230) | Mar 16, 2024 |
| Google        | Kip                         | Notebook    | [3da64ae4ad](https://linux-hardware.org/?probe=3da64ae4ad) | Mar 11, 2024 |
| Google        | Kip                         | Notebook    | [a08197fa56](https://linux-hardware.org/?probe=a08197fa56) | Mar 11, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [054ae2a4a5](https://linux-hardware.org/?probe=054ae2a4a5) | Mar 09, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [4ed069d496](https://linux-hardware.org/?probe=4ed069d496) | Mar 09, 2024 |
| HP            | 18E7                        | Desktop     | [a0f611e1dc](https://linux-hardware.org/?probe=a0f611e1dc) | Mar 04, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e053d06a2d](https://linux-hardware.org/?probe=e053d06a2d) | Mar 04, 2024 |
| HP            | 805D                        | Desktop     | [a4e341ef12](https://linux-hardware.org/?probe=a4e341ef12) | Feb 27, 2024 |
| Dell          | Inspiron N4010              | Notebook    | [0d25733cfa](https://linux-hardware.org/?probe=0d25733cfa) | Feb 27, 2024 |
| langchao      | IPM41-D3                    | Desktop     | [7f1319de8d](https://linux-hardware.org/?probe=7f1319de8d) | Feb 25, 2024 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [8ba60b265f](https://linux-hardware.org/?probe=8ba60b265f) | Feb 24, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [1dab02eb79](https://linux-hardware.org/?probe=1dab02eb79) | Feb 24, 2024 |
| HP            | 805D                        | Desktop     | [bfe43c8f6f](https://linux-hardware.org/?probe=bfe43c8f6f) | Feb 22, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [46990d3920](https://linux-hardware.org/?probe=46990d3920) | Feb 17, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [9b6886b2f0](https://linux-hardware.org/?probe=9b6886b2f0) | Feb 16, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [d3d2fd6bda](https://linux-hardware.org/?probe=d3d2fd6bda) | Feb 16, 2024 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [24a8cd9e6e](https://linux-hardware.org/?probe=24a8cd9e6e) | Feb 13, 2024 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [7c23ebf66b](https://linux-hardware.org/?probe=7c23ebf66b) | Feb 13, 2024 |
| ASRock        | N73V-S                      | Desktop     | [91167398d3](https://linux-hardware.org/?probe=91167398d3) | Feb 11, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [de284cc9b2](https://linux-hardware.org/?probe=de284cc9b2) | Feb 10, 2024 |
| VIT           | P1400                       | Notebook    | [8cb8362e24](https://linux-hardware.org/?probe=8cb8362e24) | Feb 10, 2024 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [f5699d9598](https://linux-hardware.org/?probe=f5699d9598) | Feb 04, 2024 |
| HP            | 3397                        | Desktop     | [f5180bd918](https://linux-hardware.org/?probe=f5180bd918) | Feb 02, 2024 |
| VIT           | P3400                       | Notebook    | [036ee57838](https://linux-hardware.org/?probe=036ee57838) | Feb 02, 2024 |
| VIT           | P3400                       | Notebook    | [6b03e6574f](https://linux-hardware.org/?probe=6b03e6574f) | Feb 01, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [c3510619ed](https://linux-hardware.org/?probe=c3510619ed) | Feb 01, 2024 |
| Dell          | Inspiron MXC061             | Notebook    | [a134206781](https://linux-hardware.org/?probe=a134206781) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [1ebab4d906](https://linux-hardware.org/?probe=1ebab4d906) | Jan 30, 2024 |
| ECS           | H61H2-CM                    | Desktop     | [c439ae84ce](https://linux-hardware.org/?probe=c439ae84ce) | Jan 26, 2024 |
| Dell          | Inspiron 3531               | Notebook    | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [cf56455a29](https://linux-hardware.org/?probe=cf56455a29) | Jan 15, 2024 |
| HP            | 8767 A                      | Desktop     | [88f6719b01](https://linux-hardware.org/?probe=88f6719b01) | Jan 10, 2024 |
| HP            | 8767 A                      | Desktop     | [b8a28f8c5f](https://linux-hardware.org/?probe=b8a28f8c5f) | Jan 10, 2024 |
| Google        | Fleex                       | Notebook    | [100ab93f52](https://linux-hardware.org/?probe=100ab93f52) | Jan 09, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [45b99e2412](https://linux-hardware.org/?probe=45b99e2412) | Jan 08, 2024 |
| Dell          | G16 7630                    | Notebook    | [71f36f8ed0](https://linux-hardware.org/?probe=71f36f8ed0) | Dec 24, 2023 |
| HP            | 1998                        | Desktop     | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| HP            | Pavilion dv5                | Notebook    | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| Google        | Candy                       | Notebook    | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| VIT           | P3400                       | Notebook    | [0564cdc52e](https://linux-hardware.org/?probe=0564cdc52e) | Dec 17, 2023 |
| VIT           | M2400-01                    | Mini pc     | [8c80d8ce0c](https://linux-hardware.org/?probe=8c80d8ce0c) | Dec 15, 2023 |
| Intel         | powered classmate PC        | Tablet      | [834af9a8e7](https://linux-hardware.org/?probe=834af9a8e7) | Dec 13, 2023 |
| VIT           | M2400-01                    | Mini pc     | [a7c0e03aa5](https://linux-hardware.org/?probe=a7c0e03aa5) | Dec 10, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [23a0828c28](https://linux-hardware.org/?probe=23a0828c28) | Dec 07, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [acf5ffd938](https://linux-hardware.org/?probe=acf5ffd938) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [55a44e9a14](https://linux-hardware.org/?probe=55a44e9a14) | Dec 05, 2023 |
| VIT           | M2400-01                    | Mini pc     | [c7a55f96c4](https://linux-hardware.org/?probe=c7a55f96c4) | Nov 27, 2023 |
| VIT           | M2400-01                    | Mini pc     | [9b992b1f8d](https://linux-hardware.org/?probe=9b992b1f8d) | Nov 27, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [8b7f6c2f5f](https://linux-hardware.org/?probe=8b7f6c2f5f) | Nov 27, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a5b04f6fdb](https://linux-hardware.org/?probe=a5b04f6fdb) | Nov 24, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [2248b23cde](https://linux-hardware.org/?probe=2248b23cde) | Nov 22, 2023 |
| Inspur        | H110H4-EM                   | Desktop     | [cd9931b178](https://linux-hardware.org/?probe=cd9931b178) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [88fba30cec](https://linux-hardware.org/?probe=88fba30cec) | Nov 21, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| HP            | 3647h                       | Desktop     | [9b0451eab9](https://linux-hardware.org/?probe=9b0451eab9) | Nov 15, 2023 |
| HP            | 3647h                       | Desktop     | [d6de3838ec](https://linux-hardware.org/?probe=d6de3838ec) | Nov 15, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [4d61ab4747](https://linux-hardware.org/?probe=4d61ab4747) | Nov 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [79b891b4df](https://linux-hardware.org/?probe=79b891b4df) | Nov 13, 2023 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [6ea7323880](https://linux-hardware.org/?probe=6ea7323880) | Nov 11, 2023 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [71a3f3197c](https://linux-hardware.org/?probe=71a3f3197c) | Nov 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9c9733a5c4](https://linux-hardware.org/?probe=9c9733a5c4) | Nov 07, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e4d524b5b8](https://linux-hardware.org/?probe=e4d524b5b8) | Nov 07, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [0b51da062f](https://linux-hardware.org/?probe=0b51da062f) | Nov 06, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | Notebook    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [3e5d819c23](https://linux-hardware.org/?probe=3e5d819c23) | Nov 03, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [9fb5c6d4d3](https://linux-hardware.org/?probe=9fb5c6d4d3) | Nov 03, 2023 |
| Intel         | powered classmate PC        | Notebook    | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| VIT           | P1400                       | Notebook    | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| ASRock        | D1800M                      | Desktop     | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| HP            | 18E5                        | Desktop     | [95cc2c3a9c](https://linux-hardware.org/?probe=95cc2c3a9c) | Oct 22, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [eb8522ff13](https://linux-hardware.org/?probe=eb8522ff13) | Oct 21, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [deb1dc3eaa](https://linux-hardware.org/?probe=deb1dc3eaa) | Oct 21, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [2a39f005cb](https://linux-hardware.org/?probe=2a39f005cb) | Oct 17, 2023 |
| Intel         | D945GTP AAC97837-309        | Other       | [49d064bc5d](https://linux-hardware.org/?probe=49d064bc5d) | Oct 15, 2023 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [447110886e](https://linux-hardware.org/?probe=447110886e) | Oct 14, 2023 |
| Gateway       | NV57H                       | Notebook    | [141355e1e3](https://linux-hardware.org/?probe=141355e1e3) | Oct 09, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [3b45c6b974](https://linux-hardware.org/?probe=3b45c6b974) | Oct 08, 2023 |
| Lenovo        | ThinkCentre A57 9702AB7     | Desktop     | [3237019933](https://linux-hardware.org/?probe=3237019933) | Oct 07, 2023 |
| HP            | Compaq Presario C768        | Notebook    | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| VIT           | P2400                       | Notebook    | [1896f1962a](https://linux-hardware.org/?probe=1896f1962a) | Oct 06, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [51ec04551f](https://linux-hardware.org/?probe=51ec04551f) | Oct 04, 2023 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [def181c0e4](https://linux-hardware.org/?probe=def181c0e4) | Sep 26, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [92e5dde8b3](https://linux-hardware.org/?probe=92e5dde8b3) | Sep 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [adff9fb2a8](https://linux-hardware.org/?probe=adff9fb2a8) | Sep 14, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0a25a3d2af](https://linux-hardware.org/?probe=0a25a3d2af) | Sep 12, 2023 |
| HP            | Pavilion m6                 | Notebook    | [2fb7dbd455](https://linux-hardware.org/?probe=2fb7dbd455) | Sep 09, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [a0abff6d5f](https://linux-hardware.org/?probe=a0abff6d5f) | Sep 08, 2023 |
| VIT           | M2400-01                    | Mini pc     | [8d658beb19](https://linux-hardware.org/?probe=8d658beb19) | Sep 07, 2023 |
| VIT           | P2400                       | Notebook    | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| VENEZOLANA... | VIT P2460-02                | Notebook    | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| Biostar       | G41D3                       | Desktop     | [0d4f48c335](https://linux-hardware.org/?probe=0d4f48c335) | Aug 31, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [71b31f4a43](https://linux-hardware.org/?probe=71b31f4a43) | Aug 31, 2023 |
| Panasonic     | CF-31RECAXDR                | Notebook    | [2c021f93de](https://linux-hardware.org/?probe=2c021f93de) | Aug 30, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [390b033780](https://linux-hardware.org/?probe=390b033780) | Aug 29, 2023 |
| Intel         | DG41TY AAE47335-301         | Desktop     | [1f8897e1a2](https://linux-hardware.org/?probe=1f8897e1a2) | Aug 29, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [dd6f1d7cac](https://linux-hardware.org/?probe=dd6f1d7cac) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [b67fbfb529](https://linux-hardware.org/?probe=b67fbfb529) | Aug 26, 2023 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dfa16eab4](https://linux-hardware.org/?probe=7dfa16eab4) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| Biostar       | G41D3C                      | Desktop     | [5e2c852104](https://linux-hardware.org/?probe=5e2c852104) | Aug 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Lenovo        | ThinkCentre M72e 3597A56    | Desktop     | [6b6d2e95f9](https://linux-hardware.org/?probe=6b6d2e95f9) | Aug 24, 2023 |
| VIT           | P2402                       | Notebook    | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | Notebook    | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| Inspur        | H110H4-EM                   | Desktop     | [75ce94f0f9](https://linux-hardware.org/?probe=75ce94f0f9) | Aug 21, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [bee6142eee](https://linux-hardware.org/?probe=bee6142eee) | Aug 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [52c59bb799](https://linux-hardware.org/?probe=52c59bb799) | Aug 16, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Siragon       | MN-50                       | Notebook    | [8eafa43cb5](https://linux-hardware.org/?probe=8eafa43cb5) | Aug 09, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [ae0cada933](https://linux-hardware.org/?probe=ae0cada933) | Aug 07, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [566421a903](https://linux-hardware.org/?probe=566421a903) | Jul 21, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [be9d638406](https://linux-hardware.org/?probe=be9d638406) | Jul 21, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [67db76ffed](https://linux-hardware.org/?probe=67db76ffed) | Jul 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | Desktop     | [90a2c4e2d0](https://linux-hardware.org/?probe=90a2c4e2d0) | Jul 18, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | Notebook    | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [c1da8fb79e](https://linux-hardware.org/?probe=c1da8fb79e) | Jul 08, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3734a0a9bf](https://linux-hardware.org/?probe=3734a0a9bf) | Jul 07, 2023 |
| HP            | 0A80h                       | Desktop     | [54635d0b1b](https://linux-hardware.org/?probe=54635d0b1b) | Jul 05, 2023 |
| Acer          | Aspire 6930                 | Notebook    | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| HP            | 0A80h                       | Desktop     | [83691b49d2](https://linux-hardware.org/?probe=83691b49d2) | Jul 03, 2023 |
| Intel         | D845GRG AAA84341-206        | Desktop     | [1863434dc7](https://linux-hardware.org/?probe=1863434dc7) | Jul 01, 2023 |
| Intel         | D845GRG AAA84341-206        | Desktop     | [7734dda00e](https://linux-hardware.org/?probe=7734dda00e) | Jun 30, 2023 |
| VIT           | P2423                       | Notebook    | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Pegatron      | IPMIP-H55-INSPUR            | Desktop     | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [722b363829](https://linux-hardware.org/?probe=722b363829) | Jun 17, 2023 |
| Intel         | powered classmate PC        | Notebook    | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| VIT           | P2402                       | Notebook    | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [2e0c1fbe0d](https://linux-hardware.org/?probe=2e0c1fbe0d) | Jun 06, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [5832b8b801](https://linux-hardware.org/?probe=5832b8b801) | Jun 06, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ef4a96955c](https://linux-hardware.org/?probe=ef4a96955c) | Jun 01, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a106c6a98a](https://linux-hardware.org/?probe=a106c6a98a) | Jun 01, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [c207b5f41c](https://linux-hardware.org/?probe=c207b5f41c) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| VIT           | P2400                       | Notebook    | [dca6cca8a2](https://linux-hardware.org/?probe=dca6cca8a2) | May 26, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [17996395f4](https://linux-hardware.org/?probe=17996395f4) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [dddde1dc45](https://linux-hardware.org/?probe=dddde1dc45) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [d8261039f8](https://linux-hardware.org/?probe=d8261039f8) | May 24, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| VIT           | M2400-01                    | Mini pc     | [64e5a3aa50](https://linux-hardware.org/?probe=64e5a3aa50) | May 16, 2023 |
| Lenovo        | ThinkCentre A57 9702AB7     | Desktop     | [f045709958](https://linux-hardware.org/?probe=f045709958) | May 12, 2023 |
| Intel         | H55AD17                     | Desktop     | [7d393c3814](https://linux-hardware.org/?probe=7d393c3814) | May 11, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [974c00cb61](https://linux-hardware.org/?probe=974c00cb61) | May 09, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7f1bc5a99c](https://linux-hardware.org/?probe=7f1bc5a99c) | May 06, 2023 |
| ASRock        | 945GCM-S                    | Desktop     | [940d88bfce](https://linux-hardware.org/?probe=940d88bfce) | May 06, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [701fb0df1b](https://linux-hardware.org/?probe=701fb0df1b) | Apr 26, 2023 |
| HP            | 18E7                        | Desktop     | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [fa6f088b8d](https://linux-hardware.org/?probe=fa6f088b8d) | Apr 24, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7ba77e1842](https://linux-hardware.org/?probe=7ba77e1842) | Apr 23, 2023 |
| Dell          | Latitude E6430              | Notebook    | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [54af26ce93](https://linux-hardware.org/?probe=54af26ce93) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [98121ef614](https://linux-hardware.org/?probe=98121ef614) | Apr 14, 2023 |
| HP            | 1998                        | Desktop     | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| Lenovo        | 3000 V200 07642XU           | Notebook    | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| Biostar       | H61MHV                      | Desktop     | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [fdb331baab](https://linux-hardware.org/?probe=fdb331baab) | Apr 10, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| VIT           | P2402                       | Notebook    | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| Biostar       | G41D3                       | Desktop     | [969695eafd](https://linux-hardware.org/?probe=969695eafd) | Apr 06, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [df6a8a3453](https://linux-hardware.org/?probe=df6a8a3453) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| ASRock        | A55M-HVS                    | Desktop     | [426d150c30](https://linux-hardware.org/?probe=426d150c30) | Apr 03, 2023 |
| Notebook      | W54BL                       | Notebook    | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| Soncview      | G41D3C                      | Desktop     | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [615409e462](https://linux-hardware.org/?probe=615409e462) | Mar 12, 2023 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [cc778f466a](https://linux-hardware.org/?probe=cc778f466a) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [d94d167f13](https://linux-hardware.org/?probe=d94d167f13) | Mar 11, 2023 |
| Pegatron      | H36Y                        | Notebook    | [1757156f40](https://linux-hardware.org/?probe=1757156f40) | Mar 11, 2023 |
| Acer          | Aspire A715-76              | Notebook    | [c0c0d5447d](https://linux-hardware.org/?probe=c0c0d5447d) | Mar 09, 2023 |
| Pegatron      | H36Y                        | Notebook    | [8d9c3ebbc8](https://linux-hardware.org/?probe=8d9c3ebbc8) | Mar 09, 2023 |
| MSI           | GL73 9SD                    | Notebook    | [0913746f16](https://linux-hardware.org/?probe=0913746f16) | Mar 07, 2023 |
| VIT           | P1400                       | Notebook    | [3d31270e0d](https://linux-hardware.org/?probe=3d31270e0d) | Mar 07, 2023 |
| VIT           | P1400                       | Notebook    | [bed6aed6fa](https://linux-hardware.org/?probe=bed6aed6fa) | Mar 07, 2023 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [9a9f442174](https://linux-hardware.org/?probe=9a9f442174) | Mar 03, 2023 |
| Acer          | Aspire A715-76              | Notebook    | [b9f52dc0f3](https://linux-hardware.org/?probe=b9f52dc0f3) | Feb 27, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [b9fbaca53d](https://linux-hardware.org/?probe=b9fbaca53d) | Feb 23, 2023 |
| Dell          | Latitude E6430              | Notebook    | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Google        | Candy                       | Notebook    | [b2f2862759](https://linux-hardware.org/?probe=b2f2862759) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Aspire 4739Z                | Notebook    | [cc795627da](https://linux-hardware.org/?probe=cc795627da) | Feb 10, 2023 |
| HP            | 1495                        | Desktop     | [627c584065](https://linux-hardware.org/?probe=627c584065) | Feb 09, 2023 |
| Dell          | 0YF8P5 A00                  | Desktop     | [4bb4dd8a98](https://linux-hardware.org/?probe=4bb4dd8a98) | Feb 06, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d6cea67f50](https://linux-hardware.org/?probe=d6cea67f50) | Feb 05, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [c20b6ee7d2](https://linux-hardware.org/?probe=c20b6ee7d2) | Feb 04, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| ECS           | G31T-M7                     | Desktop     | [76be6a1404](https://linux-hardware.org/?probe=76be6a1404) | Feb 01, 2023 |
| ECS           | G31T-M7                     | Desktop     | [9b0f53b46c](https://linux-hardware.org/?probe=9b0f53b46c) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [daa9bd48c8](https://linux-hardware.org/?probe=daa9bd48c8) | Jan 31, 2023 |
| Gigabyte      | EP35-DS3L                   | Desktop     | [5be0362f3e](https://linux-hardware.org/?probe=5be0362f3e) | Jan 23, 2023 |
| Lenovo        | ThinkPad SL 2743A65         | Notebook    | [89f744ff83](https://linux-hardware.org/?probe=89f744ff83) | Jan 22, 2023 |
| Dell          | Vostro 1220                 | Notebook    | [6cd42b6be3](https://linux-hardware.org/?probe=6cd42b6be3) | Jan 19, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [c48a8fe525](https://linux-hardware.org/?probe=c48a8fe525) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| HP            | 1495                        | Desktop     | [28c3cf967d](https://linux-hardware.org/?probe=28c3cf967d) | Jan 16, 2023 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| Pegatron      | B74                         | Notebook    | [3e721dbe13](https://linux-hardware.org/?probe=3e721dbe13) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6cb922bbdf](https://linux-hardware.org/?probe=6cb922bbdf) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4ed227f8af](https://linux-hardware.org/?probe=4ed227f8af) | Jan 09, 2023 |
| Intel         | powered classmate PC        | Tablet      | [c35a8d75ce](https://linux-hardware.org/?probe=c35a8d75ce) | Jan 05, 2023 |
| Intel         | powered classmate PC        | Tablet      | [dbca24d9e5](https://linux-hardware.org/?probe=dbca24d9e5) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8e885883c6](https://linux-hardware.org/?probe=8e885883c6) | Jan 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [61b7eaac72](https://linux-hardware.org/?probe=61b7eaac72) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [de0a127527](https://linux-hardware.org/?probe=de0a127527) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [515785c9c4](https://linux-hardware.org/?probe=515785c9c4) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [68f683d29e](https://linux-hardware.org/?probe=68f683d29e) | Dec 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a656b96d5f](https://linux-hardware.org/?probe=a656b96d5f) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6275a6ee8f](https://linux-hardware.org/?probe=6275a6ee8f) | Dec 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e1a4335a71](https://linux-hardware.org/?probe=e1a4335a71) | Dec 01, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| Intel         | powered classmate PC        | Tablet      | [44cc912fe3](https://linux-hardware.org/?probe=44cc912fe3) | Nov 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [906ad9a3c1](https://linux-hardware.org/?probe=906ad9a3c1) | Nov 25, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [b252a902f4](https://linux-hardware.org/?probe=b252a902f4) | Nov 24, 2022 |
| VIT           | M2400-01                    | Mini pc     | [4b590aa76a](https://linux-hardware.org/?probe=4b590aa76a) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3469b1e624](https://linux-hardware.org/?probe=3469b1e624) | Nov 07, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [d3ef4a43db](https://linux-hardware.org/?probe=d3ef4a43db) | Nov 06, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Intel         | H61                         | Desktop     | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| Intel         | powered classmate PC        | Tablet      | [d047cd6e73](https://linux-hardware.org/?probe=d047cd6e73) | Oct 22, 2022 |
| Google        | Candy                       | Notebook    | [af2c0be6ca](https://linux-hardware.org/?probe=af2c0be6ca) | Oct 17, 2022 |
| Google        | Candy                       | Notebook    | [ec740507fd](https://linux-hardware.org/?probe=ec740507fd) | Oct 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| ECS           | A890GXM-A2                  | Desktop     | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| VIT           | P2402                       | Notebook    | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | Notebook    | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [21cfcdcbdd](https://linux-hardware.org/?probe=21cfcdcbdd) | Sep 23, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Gateway       | NV57H                       | Notebook    | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| Clevo         | W54xEU                      | Notebook    | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [ac687f4dcd](https://linux-hardware.org/?probe=ac687f4dcd) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b3b173a476](https://linux-hardware.org/?probe=b3b173a476) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Intel         | S1200BTL E98681-352         | Server      | [1db51bcff9](https://linux-hardware.org/?probe=1db51bcff9) | Aug 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | 339A                        | Desktop     | [c19f3d1361](https://linux-hardware.org/?probe=c19f3d1361) | Jul 29, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| Intel         | powered classmate PC        | Tablet      | [1abacce964](https://linux-hardware.org/?probe=1abacce964) | Jul 06, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [737e14fea7](https://linux-hardware.org/?probe=737e14fea7) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| Pegatron      | IPPSB-DB                    | Desktop     | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| Google        | Cyan                        | Notebook    | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| langchao      | IPM41-D3                    | Desktop     | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [5d8aa17afc](https://linux-hardware.org/?probe=5d8aa17afc) | Jun 10, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [a502ed154f](https://linux-hardware.org/?probe=a502ed154f) | Jun 10, 2022 |
| VIT           | M2420                       | Notebook    | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| VIT           | M2420                       | Notebook    | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | Notebook    | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Lenovo        | 11051CS ThinkServer TS13... | Desktop     | [48e6a5501d](https://linux-hardware.org/?probe=48e6a5501d) | May 26, 2022 |
| Acer          | TravelMate 5742Z            | Notebook    | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| IP3 Tech      | TB20                        | Desktop     | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Intel         | H61                         | Desktop     | [28277b5d5a](https://linux-hardware.org/?probe=28277b5d5a) | May 10, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | Notebook    | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| ASRock        | G31M-S                      | Desktop     | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| Gateway       | NV57H                       | Notebook    | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [552956f271](https://linux-hardware.org/?probe=552956f271) | Mar 24, 2022 |
| VIT           | P2402                       | Notebook    | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Inspur        | Computer All in one PC V... | Desktop     | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| MSI           | 3664h                       | Desktop     | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | NP3020M3                    | Server      | [9fbb87a829](https://linux-hardware.org/?probe=9fbb87a829) | Mar 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [0e8fbc26f1](https://linux-hardware.org/?probe=0e8fbc26f1) | Mar 01, 2022 |
| Pegatron      | 2ACC                        | Desktop     | [c1127626c5](https://linux-hardware.org/?probe=c1127626c5) | Mar 01, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Intel         | powered classmate PC        | Tablet      | [a2b7a04dfa](https://linux-hardware.org/?probe=a2b7a04dfa) | Feb 18, 2022 |
| VIT           | P3400                       | Notebook    | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | Notebook    | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| ECS           | KAM1-I                      | Desktop     | [be38f855ff](https://linux-hardware.org/?probe=be38f855ff) | Feb 10, 2022 |
| Gateway       | NV57H                       | Notebook    | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| ASRock        | A55M-HVS                    | Desktop     | [c4c68e7dd1](https://linux-hardware.org/?probe=c4c68e7dd1) | Feb 08, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| ASUSTek       | P6X58-E PRO                 | Desktop     | [9ee8e1ecdf](https://linux-hardware.org/?probe=9ee8e1ecdf) | Jan 30, 2022 |
| Intel         | DG41TY AAE47335-203         | Desktop     | [01ec1ff569](https://linux-hardware.org/?probe=01ec1ff569) | Jan 26, 2022 |
| MSI           | MS-1454                     | Notebook    | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8700fd1193](https://linux-hardware.org/?probe=8700fd1193) | Jan 11, 2022 |
| VIT           | M2421                       | Notebook    | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| UNIQCELL      | Q15.6                       | Notebook    | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [8d19cd079a](https://linux-hardware.org/?probe=8d19cd079a) | Dec 09, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ecd0add9b3](https://linux-hardware.org/?probe=ecd0add9b3) | Dec 09, 2021 |
| HP            | 3398                        | Desktop     | [5ae73e1468](https://linux-hardware.org/?probe=5ae73e1468) | Dec 07, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Lenovo        | B40-70 20392                | Notebook    | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| Intel         | powered classmate PC        | Tablet      | [aea7e0243a](https://linux-hardware.org/?probe=aea7e0243a) | Nov 21, 2021 |
| Intel         | powered classmate PC        | Tablet      | [444812feb3](https://linux-hardware.org/?probe=444812feb3) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | Notebook    | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| HP            | 1495                        | Desktop     | [64cbb112e2](https://linux-hardware.org/?probe=64cbb112e2) | Oct 01, 2021 |
| Clevo         | W54xEU                      | Notebook    | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | Notebook    | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | Notebook    | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Foxconn       | M61PMV FAB                  | Desktop     | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| Pegatron      | T14AF                       | Notebook    | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | Notebook    | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ec9367ff70](https://linux-hardware.org/?probe=ec9367ff70) | Aug 16, 2021 |
| VIT           | P2400                       | Notebook    | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Foxconn       | ELA01                       | Desktop     | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Lenovo        | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [60c62c33f8](https://linux-hardware.org/?probe=60c62c33f8) | Jul 14, 2021 |
| Biostar       | G41D3                       | Desktop     | [673d4faa98](https://linux-hardware.org/?probe=673d4faa98) | Jul 12, 2021 |
| HP            | 3397                        | Desktop     | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP            | 3397                        | Desktop     | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [a57f28921c](https://linux-hardware.org/?probe=a57f28921c) | Jul 05, 2021 |
| ECS           | Livermore                   | Desktop     | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| VIT           | P2400                       | Notebook    | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [512537c402](https://linux-hardware.org/?probe=512537c402) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [9773736b0f](https://linux-hardware.org/?probe=9773736b0f) | Jun 17, 2021 |
| ECS           | G31T-M7                     | Desktop     | [01ed8410e9](https://linux-hardware.org/?probe=01ed8410e9) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M55E 9645BN2    | Desktop     | [ef91279611](https://linux-hardware.org/?probe=ef91279611) | Jun 15, 2021 |
| VIT           | P1400                       | Notebook    | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| Biostar       | G41D3C                      | Desktop     | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | Notebook    | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | Notebook    | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [42960896cb](https://linux-hardware.org/?probe=42960896cb) | May 20, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4856303cbe](https://linux-hardware.org/?probe=4856303cbe) | May 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | Notebook    | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [8d84f6dc9e](https://linux-hardware.org/?probe=8d84f6dc9e) | Apr 25, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [db04624ac3](https://linux-hardware.org/?probe=db04624ac3) | Apr 20, 2021 |
| Acer          | Aspire 4935                 | Notebook    | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| Toshiba       | Satellite E55t-A            | Notebook    | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | Notebook    | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [7f2618efb7](https://linux-hardware.org/?probe=7f2618efb7) | Mar 12, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 1495                        | Desktop     | [248af9611e](https://linux-hardware.org/?probe=248af9611e) | Mar 11, 2021 |
| Dell          | 0GX297                      | Desktop     | [6ac3da669a](https://linux-hardware.org/?probe=6ac3da669a) | Mar 09, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [543e8d3501](https://linux-hardware.org/?probe=543e8d3501) | Mar 07, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [892f3e6658](https://linux-hardware.org/?probe=892f3e6658) | Mar 07, 2021 |
| HP            | 2000                        | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Intel         | S5500BC E25124-407          | Server      | [fe3d758c20](https://linux-hardware.org/?probe=fe3d758c20) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9e6a12d9e1](https://linux-hardware.org/?probe=9e6a12d9e1) | Feb 15, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e4d1cc65bc](https://linux-hardware.org/?probe=e4d1cc65bc) | Jan 27, 2021 |
| HP            | 1493                        | Desktop     | [febb5aee31](https://linux-hardware.org/?probe=febb5aee31) | Jan 15, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| Pegatron      | IPM41-D3                    | Desktop     | [4e0489bdb0](https://linux-hardware.org/?probe=4e0489bdb0) | Dec 05, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [e195f622e4](https://linux-hardware.org/?probe=e195f622e4) | Nov 22, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [a0456b9ad3](https://linux-hardware.org/?probe=a0456b9ad3) | Nov 22, 2020 |
| HP            | 1495                        | Desktop     | [72bdee2784](https://linux-hardware.org/?probe=72bdee2784) | Nov 19, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | Notebook    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Foxconn       | M61PMV FAB A1               | Desktop     | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db328c3c01](https://linux-hardware.org/?probe=db328c3c01) | Sep 29, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [8ae7ffac0b](https://linux-hardware.org/?probe=8ae7ffac0b) | Sep 28, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | Notebook    | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Intel         | powered classmate PC        | Tablet      | [4f4efbc5c6](https://linux-hardware.org/?probe=4f4efbc5c6) | Sep 06, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [5f5f0bd2cf](https://linux-hardware.org/?probe=5f5f0bd2cf) | Aug 29, 2020 |
| Biostar       | N68S3B                      | Desktop     | [1e4d89cafe](https://linux-hardware.org/?probe=1e4d89cafe) | Aug 27, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [7f40a96159](https://linux-hardware.org/?probe=7f40a96159) | Aug 20, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8445b18759](https://linux-hardware.org/?probe=8445b18759) | Aug 20, 2020 |
| HP            | Presario V2000 (EW997LA#... | Notebook    | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | Notebook    | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [43d0144f0a](https://linux-hardware.org/?probe=43d0144f0a) | Aug 06, 2020 |
| MSI           | K9N2 Diamond                | Desktop     | [07a001660f](https://linux-hardware.org/?probe=07a001660f) | Aug 04, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [f2fdb4f618](https://linux-hardware.org/?probe=f2fdb4f618) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [a2e742ec36](https://linux-hardware.org/?probe=a2e742ec36) | Jul 27, 2020 |
| VIT           | M2421                       | Notebook    | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [6786c103d7](https://linux-hardware.org/?probe=6786c103d7) | Jul 27, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| Intel         | powered classmate PC        | Notebook    | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | Notebook    | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [39510acc74](https://linux-hardware.org/?probe=39510acc74) | Jul 06, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [eff9ad2c7d](https://linux-hardware.org/?probe=eff9ad2c7d) | Jul 05, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [a1e610807e](https://linux-hardware.org/?probe=a1e610807e) | Jun 30, 2020 |
| HP            | Presario C700               | Notebook    | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [e8c521f7e8](https://linux-hardware.org/?probe=e8c521f7e8) | Jun 25, 2020 |
| Standard      | AHV                         | All in one  | [989175dbdc](https://linux-hardware.org/?probe=989175dbdc) | Jun 08, 2020 |
| Standard      | AHV                         | All in one  | [f0bd9ac2e1](https://linux-hardware.org/?probe=f0bd9ac2e1) | Jun 07, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [cd52689b0a](https://linux-hardware.org/?probe=cd52689b0a) | May 25, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [d48d360c14](https://linux-hardware.org/?probe=d48d360c14) | May 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [18c81b7e8b](https://linux-hardware.org/?probe=18c81b7e8b) | May 19, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [cce631f67b](https://linux-hardware.org/?probe=cce631f67b) | May 19, 2020 |
| VIT           | P3400                       | Notebook    | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [084641dbc1](https://linux-hardware.org/?probe=084641dbc1) | May 17, 2020 |
| VIT           | P3400                       | Notebook    | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | Notebook    | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b55d1daea5](https://linux-hardware.org/?probe=b55d1daea5) | May 11, 2020 |
| VIT           | P2402                       | Notebook    | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97e5a8c8da](https://linux-hardware.org/?probe=97e5a8c8da) | Apr 26, 2020 |
| VIT           | P3400                       | Notebook    | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | Notebook    | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | Notebook    | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [b3436f0ec6](https://linux-hardware.org/?probe=b3436f0ec6) | Apr 11, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [841ded939f](https://linux-hardware.org/?probe=841ded939f) | Mar 31, 2020 |
| Lenovo        | ThinkCentre A58 7515A33     | Desktop     | [75be0ab7ac](https://linux-hardware.org/?probe=75be0ab7ac) | Mar 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | Notebook    | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [1d140aa76c](https://linux-hardware.org/?probe=1d140aa76c) | Mar 07, 2020 |
| Acer          | Aspire Z3730                | All in one  | [24d42a520e](https://linux-hardware.org/?probe=24d42a520e) | Mar 03, 2020 |
| VIT           | P2402                       | Notebook    | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [2859756e56](https://linux-hardware.org/?probe=2859756e56) | Feb 29, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | ThinkCentre XXXX 8705A84    | Desktop     | [b824441963](https://linux-hardware.org/?probe=b824441963) | Feb 23, 2020 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [e79318e87d](https://linux-hardware.org/?probe=e79318e87d) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [3e6bc93a39](https://linux-hardware.org/?probe=3e6bc93a39) | Jan 31, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b6ba4394f7](https://linux-hardware.org/?probe=b6ba4394f7) | Jan 29, 2020 |
| ASUSTek       | Leonite2                    | Desktop     | [d0d56d5609](https://linux-hardware.org/?probe=d0d56d5609) | Jan 23, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| VIT           | Aptio CRB                   | Mini pc     | [d999c674f1](https://linux-hardware.org/?probe=d999c674f1) | Dec 23, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [41131b1d8e](https://linux-hardware.org/?probe=41131b1d8e) | Dec 23, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | Desktop     | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [2d4b473d59](https://linux-hardware.org/?probe=2d4b473d59) | Dec 01, 2019 |
| Pegatron      | 2A73h                       | Desktop     | [2371d130d0](https://linux-hardware.org/?probe=2371d130d0) | Nov 30, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [aba5fa885d](https://linux-hardware.org/?probe=aba5fa885d) | Nov 25, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3d775f418d](https://linux-hardware.org/?probe=3d775f418d) | Oct 08, 2019 |
| Foxconn       | 8657MF-series               | Desktop     | [8ce7f69a15](https://linux-hardware.org/?probe=8ce7f69a15) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3fc14db446](https://linux-hardware.org/?probe=3fc14db446) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [af840eb366](https://linux-hardware.org/?probe=af840eb366) | Oct 04, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Intel         | powered classmate PC        | Tablet      | [05f47d610a](https://linux-hardware.org/?probe=05f47d610a) | Aug 22, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [f80cb4a7f2](https://linux-hardware.org/?probe=f80cb4a7f2) | Aug 17, 2019 |
| Dell          | 0RK936                      | Desktop     | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [e107cafe33](https://linux-hardware.org/?probe=e107cafe33) | Jun 07, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [65dd091a6f](https://linux-hardware.org/?probe=65dd091a6f) | May 13, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| Pegatron      | 2AF0                        | Desktop     | [bebc187dbd](https://linux-hardware.org/?probe=bebc187dbd) | May 05, 2019 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [c73b25ed21](https://linux-hardware.org/?probe=c73b25ed21) | Apr 24, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [d1941d4619](https://linux-hardware.org/?probe=d1941d4619) | Apr 24, 2019 |
| Lenovo        | H220 10028                  | Desktop     | [9b6593e8c6](https://linux-hardware.org/?probe=9b6593e8c6) | Apr 21, 2019 |
| ASRock        | N68C-S UCC                  | Desktop     | [ac39e69311](https://linux-hardware.org/?probe=ac39e69311) | Apr 21, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [282ee52768](https://linux-hardware.org/?probe=282ee52768) | Apr 19, 2019 |
| HP            | Pavilion dv4                | Notebook    | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [e054fab57c](https://linux-hardware.org/?probe=e054fab57c) | Nov 24, 2018 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d3d5ff2e54](https://linux-hardware.org/?probe=d3d5ff2e54) | Nov 24, 2018 |
| Intel         | powered classmate PC        | Notebook    | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | Notebook    | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [8d884b92fa](https://linux-hardware.org/?probe=8d884b92fa) | Sep 16, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [17af4fce47](https://linux-hardware.org/?probe=17af4fce47) | Sep 03, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [c501aaa553](https://linux-hardware.org/?probe=c501aaa553) | Sep 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |
| ASRock        | 945GCM-S                    | Desktop     | [009791bef2](https://linux-hardware.org/?probe=009791bef2) | Jun 25, 2017 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [270499b92c](https://linux-hardware.org/?probe=270499b92c) | Dec 29, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Venezuela/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Debian 11          | 37        | 7.84%   |
| Ubuntu 22.04       | 31        | 6.57%   |
| Ubuntu 20.04       | 28        | 5.93%   |
| OpenMandriva 4.3   | 18        | 3.81%   |
| Ubuntu 18.04       | 16        | 3.39%   |
| OpenMandriva 23.08 | 15        | 3.18%   |
| Zorin 16           | 12        | 2.54%   |
| OpenMandriva 23.03 | 12        | 2.54%   |
| OpenMandriva 4.2   | 11        | 2.33%   |
| Linux Mint 21.1    | 10        | 2.12%   |
| Debian 12          | 10        | 2.12%   |
| Debian 10          | 10        | 2.12%   |
| Linux Mint 20.3    | 9         | 1.91%   |
| KDE neon 20.04     | 9         | 1.91%   |
| OpenMandriva 23.01 | 8         | 1.69%   |
| KDE neon 22.04     | 8         | 1.69%   |
| Arch Rolling       | 8         | 1.69%   |
| Xubuntu 18.04      | 7         | 1.48%   |
| Linux Mint 21.2    | 6         | 1.27%   |
| Kubuntu 20.04      | 6         | 1.27%   |
| ROSA R9            | 5         | 1.06%   |
| ROSA R11           | 5         | 1.06%   |
| Manjaro            | 5         | 1.06%   |
| Linux Mint 20      | 5         | 1.06%   |
| Linux Mint 19.3    | 5         | 1.06%   |
| ArcoLinux Rolling  | 5         | 1.06%   |
| Zorin 15           | 4         | 0.85%   |
| Ubuntu MATE 19.10  | 4         | 0.85%   |
| Ubuntu 19.10       | 4         | 0.85%   |
| OpenMandriva 4.50  | 4         | 0.85%   |
| MX 21              | 4         | 0.85%   |
| Linux Mint 21.3    | 4         | 0.85%   |
| Linux Mint 20.1    | 4         | 0.85%   |
| Kubuntu 22.04      | 4         | 0.85%   |
| Fedora 39          | 4         | 0.85%   |
| Fedora 38          | 4         | 0.85%   |
| Fedora 35          | 4         | 0.85%   |
| Xubuntu 22.04      | 3         | 0.64%   |
| Ubuntu 23.10       | 3         | 0.64%   |
| Ubuntu 21.10       | 3         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 88        | 19.51%  |
| OpenMandriva | 70        | 15.52%  |
| Debian       | 59        | 13.08%  |
| Linux Mint   | 46        | 10.2%   |
| KDE neon     | 19        | 4.21%   |
| Fedora       | 19        | 4.21%   |
| Zorin        | 17        | 3.77%   |
| ROSA         | 17        | 3.77%   |
| Xubuntu      | 15        | 3.33%   |
| Kubuntu      | 11        | 2.44%   |
| Manjaro      | 10        | 2.22%   |
| Arch         | 10        | 2.22%   |
| Ubuntu MATE  | 7         | 1.55%   |
| MX           | 6         | 1.33%   |
| Elementary   | 6         | 1.33%   |
| Pop!_OS      | 5         | 1.11%   |
| Nobara       | 5         | 1.11%   |
| ArcoLinux    | 5         | 1.11%   |
| Lubuntu      | 4         | 0.89%   |
| Kali         | 4         | 0.89%   |
| Ubuntu Unity | 3         | 0.67%   |
| LMDE         | 3         | 0.67%   |
| Xero         | 2         | 0.44%   |
| Solus        | 2         | 0.44%   |
| Q4OS         | 2         | 0.44%   |
| openSUSE     | 2         | 0.44%   |
| Garuda Linux | 2         | 0.44%   |
| Feren OS     | 2         | 0.44%   |
| Sparky       | 1         | 0.22%   |
| PCLinuxOS    | 1         | 0.22%   |
| Linux Lite   | 1         | 0.22%   |
| Frnsf        | 1         | 0.22%   |
| Endless      | 1         | 0.22%   |
| EndeavourOS  | 1         | 0.22%   |
| Deepin       | 1         | 0.22%   |
| BunsenLabs   | 1         | 0.22%   |
| Alpine       | 1         | 0.22%   |
| AlmaLinux    | 1         | 0.22%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 18        | 3.5%    |
| 6.2.6-desktop-1omv2390          | 12        | 2.33%   |
| 5.10.14-desktop-1omv4002        | 11        | 2.14%   |
| 6.4.8-desktop-2omv2390          | 8         | 1.55%   |
| 6.4.11-desktop-1omv2390         | 8         | 1.55%   |
| 6.1.1-desktop-1omv2290          | 8         | 1.55%   |
| 5.4.0-42-generic                | 8         | 1.55%   |
| 5.3.0-40-generic                | 6         | 1.17%   |
| 5.15.0-46-generic               | 6         | 1.17%   |
| 6.2.0-26-generic                | 5         | 0.97%   |
| 5.19.0-41-generic               | 5         | 0.97%   |
| 5.15.0-67-generic               | 5         | 0.97%   |
| 5.15.0-56-generic               | 5         | 0.97%   |
| 5.10.0-23-amd64                 | 5         | 0.97%   |
| 5.4.0-77-generic                | 4         | 0.78%   |
| 5.15.0-76-generic               | 4         | 0.78%   |
| 5.13.0-39-generic               | 4         | 0.78%   |
| 5.10.0-16-amd64                 | 4         | 0.78%   |
| 5.10.0-13-amd64                 | 4         | 0.78%   |
| 5.10.0-11-amd64                 | 4         | 0.78%   |
| 5.0.0-37-generic                | 4         | 0.78%   |
| 4.19.0-17-amd64                 | 4         | 0.78%   |
| 6.6.2-desktop-1omv2390          | 3         | 0.58%   |
| 6.2.0-32-generic                | 3         | 0.58%   |
| 5.4.0-74-generic                | 3         | 0.58%   |
| 5.4.0-73-generic                | 3         | 0.58%   |
| 5.4.0-52-generic                | 3         | 0.58%   |
| 5.3.0-29-generic                | 3         | 0.58%   |
| 5.15.0-91-generic               | 3         | 0.58%   |
| 5.15.0-58-generic               | 3         | 0.58%   |
| 5.15.0-52-generic               | 3         | 0.58%   |
| 5.11.0-37-generic               | 3         | 0.58%   |
| 5.10.0-21-amd64                 | 3         | 0.58%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 0.58%   |
| 4.15.0-48-generic               | 3         | 0.58%   |
| 6.5.0-28-generic                | 2         | 0.39%   |
| 6.5.0-26-generic                | 2         | 0.39%   |
| 6.5.0-21-generic                | 2         | 0.39%   |
| 6.4.11-arch2-1                  | 2         | 0.39%   |
| 6.3.5-desktop-3omv2390          | 2         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 59        | 12.27%  |
| 5.4.0   | 51        | 10.6%   |
| 5.10.0  | 40        | 8.32%   |
| 4.15.0  | 24        | 4.99%   |
| 6.2.0   | 20        | 4.16%   |
| 5.13.0  | 19        | 3.95%   |
| 5.16.7  | 18        | 3.74%   |
| 6.5.0   | 14        | 2.91%   |
| 5.19.0  | 14        | 2.91%   |
| 6.2.6   | 12        | 2.49%   |
| 6.1.0   | 12        | 2.49%   |
| 5.3.0   | 12        | 2.49%   |
| 4.19.0  | 12        | 2.49%   |
| 5.10.14 | 11        | 2.29%   |
| 6.4.11  | 10        | 2.08%   |
| 5.8.0   | 10        | 2.08%   |
| 5.11.0  | 9         | 1.87%   |
| 6.4.8   | 8         | 1.66%   |
| 6.1.1   | 8         | 1.66%   |
| 5.0.0   | 7         | 1.46%   |
| 6.6.2   | 4         | 0.83%   |
| 4.9.20  | 4         | 0.83%   |
| 6.2.12  | 3         | 0.62%   |
| 5.14.10 | 3         | 0.62%   |
| 6.4.6   | 2         | 0.42%   |
| 6.4.3   | 2         | 0.42%   |
| 6.4.2   | 2         | 0.42%   |
| 6.3.5   | 2         | 0.42%   |
| 5.18.0  | 2         | 0.42%   |
| 5.15.6  | 2         | 0.42%   |
| 5.15.2  | 2         | 0.42%   |
| 5.12.4  | 2         | 0.42%   |
| 4.9.0   | 2         | 0.42%   |
| 4.18.0  | 2         | 0.42%   |
| 6.8.7   | 1         | 0.21%   |
| 6.7.7   | 1         | 0.21%   |
| 6.7.4   | 1         | 0.21%   |
| 6.6.7   | 1         | 0.21%   |
| 6.6.4   | 1         | 0.21%   |
| 6.6.30  | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 69        | 14.5%   |
| 5.10    | 58        | 12.18%  |
| 5.4     | 53        | 11.13%  |
| 6.2     | 35        | 7.35%   |
| 6.4     | 26        | 5.46%   |
| 6.1     | 24        | 5.04%   |
| 4.15    | 24        | 5.04%   |
| 5.13    | 22        | 4.62%   |
| 5.16    | 20        | 4.2%    |
| 6.5     | 18        | 3.78%   |
| 5.19    | 17        | 3.57%   |
| 5.8     | 13        | 2.73%   |
| 5.3     | 12        | 2.52%   |
| 4.19    | 12        | 2.52%   |
| 6.6     | 11        | 2.31%   |
| 5.11    | 9         | 1.89%   |
| 4.9     | 8         | 1.68%   |
| 5.0     | 7         | 1.47%   |
| 6.3     | 5         | 1.05%   |
| 6.0     | 4         | 0.84%   |
| 5.17    | 4         | 0.84%   |
| 5.14    | 4         | 0.84%   |
| 5.6     | 3         | 0.63%   |
| 5.18    | 3         | 0.63%   |
| 5.12    | 3         | 0.63%   |
| 6.7     | 2         | 0.42%   |
| 5.9     | 2         | 0.42%   |
| 4.18    | 2         | 0.42%   |
| 6.8     | 1         | 0.21%   |
| 5.7     | 1         | 0.21%   |
| 5.5     | 1         | 0.21%   |
| 4.4     | 1         | 0.21%   |
| 4.13    | 1         | 0.21%   |
| 4.1     | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 405       | 93.1%   |
| i686   | 30        | 6.9%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 139       | 30.42%  |
| KDE5            | 120       | 26.26%  |
| XFCE            | 53        | 11.6%   |
| X-Cinnamon      | 33        | 7.22%   |
| Unknown         | 27        | 5.91%   |
| MATE            | 16        | 3.5%    |
| KDE             | 14        | 3.06%   |
| LXQt            | 12        | 2.63%   |
| KDE4            | 8         | 1.75%   |
| Cinnamon        | 6         | 1.31%   |
| Pantheon        | 5         | 1.09%   |
| LXDE            | 5         | 1.09%   |
| Unity           | 3         | 0.66%   |
| Budgie          | 3         | 0.66%   |
| KDE6            | 2         | 0.44%   |
| GNOME Classic   | 2         | 0.44%   |
| awesome         | 2         | 0.44%   |
| xmonad          | 1         | 0.22%   |
| Trinity         | 1         | 0.22%   |
| Openbox         | 1         | 0.22%   |
| i3              | 1         | 0.22%   |
| GNOME Flashback | 1         | 0.22%   |
| Deepin          | 1         | 0.22%   |
| bspwm           | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 345       | 77.18%  |
| Wayland | 93        | 20.81%  |
| Unknown | 6         | 1.34%   |
| Tty     | 3         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 160       | 35.63%  |
| SDDM    | 110       | 24.5%   |
| LightDM | 61        | 13.59%  |
| GDM3    | 51        | 11.36%  |
| GDM     | 46        | 10.24%  |
| TDM     | 11        | 2.45%   |
| KDM     | 8         | 1.78%   |
| SLiM    | 2         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 266       | 59.11%  |
| en_US   | 105       | 23.33%  |
| es_ES   | 28        | 6.22%   |
| Unknown | 26        | 5.78%   |
| es_MX   | 14        | 3.11%   |
| es_US   | 4         | 0.89%   |
| C       | 3         | 0.67%   |
| es_CO   | 2         | 0.44%   |
| en_CA   | 1         | 0.22%   |
| de_DE   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 308       | 70%     |
| EFI  | 132       | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 326       | 72.61%  |
| Overlay | 53        | 11.8%   |
| Btrfs   | 34        | 7.57%   |
| Tmpfs   | 17        | 3.79%   |
| Unknown | 8         | 1.78%   |
| Xfs     | 7         | 1.56%   |
| Ext2    | 2         | 0.45%   |
| XXX4    | 1         | 0.22%   |
| Ext3    | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 176       | 39.11%  |
| GPT     | 148       | 32.89%  |
| MBR     | 126       | 28%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 363       | 82.13%  |
| Yes       | 79        | 17.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 282       | 64.09%  |
| Yes       | 158       | 35.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Hewlett-Packard                          | 48        | 11.09%  |
| Lenovo                                   | 45        | 10.39%  |
| Dell                                     | 45        | 10.39%  |
| ASRock                                   | 41        | 9.47%   |
| VIT                                      | 36        | 8.31%   |
| Intel                                    | 34        | 7.85%   |
| ASUSTek Computer                         | 26        | 6%      |
| ECS                                      | 20        | 4.62%   |
| Pegatron                                 | 18        | 4.16%   |
| Gigabyte Technology                      | 18        | 4.16%   |
| Biostar                                  | 13        | 3%      |
| Acer                                     | 13        | 3%      |
| MSI                                      | 10        | 2.31%   |
| Foxconn                                  | 8         | 1.85%   |
| Unknown                                  | 8         | 1.85%   |
| langchao                                 | 7         | 1.62%   |
| Google                                   | 6         | 1.39%   |
| Inspur                                   | 4         | 0.92%   |
| Apple                                    | 4         | 0.92%   |
| Toshiba                                  | 3         | 0.69%   |
| SIRAGON                                  | 3         | 0.69%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 0.69%   |
| Notebook                                 | 3         | 0.69%   |
| Samsung Electronics                      | 2         | 0.46%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.23%   |
| UNIQCELL                                 | 1         | 0.23%   |
| Standard                                 | 1         | 0.23%   |
| Sony                                     | 1         | 0.23%   |
| Soncview                                 | 1         | 0.23%   |
| Panasonic                                | 1         | 0.23%   |
| Microsoft                                | 1         | 0.23%   |
| IP3 Tech                                 | 1         | 0.23%   |
| IBM                                      | 1         | 0.23%   |
| GPU Company                              | 1         | 0.23%   |
| Gateway                                  | 1         | 0.23%   |
| Exo                                      | 1         | 0.23%   |
| Clevo                                    | 1         | 0.23%   |
| AVITA                                    | 1         | 0.23%   |
| Alienware                                | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel powered classmate PC        | 15        | 3.46%   |
| ECS H61H2-CM                      | 12        | 2.77%   |
| VIT P2400                         | 8         | 1.85%   |
| Unknown                           | 8         | 1.85%   |
| langchao 12345                    | 7         | 1.62%   |
| ASRock G41M-VS3                   | 7         | 1.62%   |
| VIT M2400-01                      | 6         | 1.39%   |
| VIT P3400                         | 5         | 1.15%   |
| VIT P2402                         | 5         | 1.15%   |
| Pegatron Compaq dx2400 Microtower | 4         | 0.92%   |
| ASRock N68C-S UCC                 | 4         | 0.92%   |
| ASRock N68-VS3 UCC                | 4         | 0.92%   |
| ASRock H61M-VG3                   | 4         | 0.92%   |
| VIT P1400                         | 3         | 0.69%   |
| VIT M2420                         | 3         | 0.69%   |
| Shanghai Zhaoxin ZXE CRB          | 3         | 0.69%   |
| HP Pavilion dv5                   | 3         | 0.69%   |
| HP Compaq 8200 Elite SFF PC       | 3         | 0.69%   |
| Google Candy                      | 3         | 0.69%   |
| Gigabyte 970A-DS3P                | 3         | 0.69%   |
| Biostar G41D3                     | 3         | 0.69%   |
| VIT M2421                         | 2         | 0.46%   |
| VIT Aptio CRB                     | 2         | 0.46%   |
| Pegatron IPM41-D3                 | 2         | 0.46%   |
| Notebook W54BL                    | 2         | 0.46%   |
| Lenovo ThinkCentre A57 9702AB7    | 2         | 0.46%   |
| Lenovo IdeaPad S100c 20194        | 2         | 0.46%   |
| Lenovo 3000 N200 0769ARS          | 2         | 0.46%   |
| Intel H61                         | 2         | 0.46%   |
| Inspur VIT E2250                  | 2         | 0.46%   |
| HP ProDesk 600 G1 SFF             | 2         | 0.46%   |
| HP EliteDesk 800 G1 USDT          | 2         | 0.46%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.46%   |
| HP Compaq Presario C700           | 2         | 0.46%   |
| HP Compaq Elite 8300 SFF          | 2         | 0.46%   |
| ECS H61H2-MV                      | 2         | 0.46%   |
| ECS G31T-M7                       | 2         | 0.46%   |
| Dell OptiPlex 9020                | 2         | 0.46%   |
| Dell OptiPlex 790                 | 2         | 0.46%   |
| Dell Inspiron 3891                | 2         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 18        | 4.16%   |
| Intel powered        | 15        | 3.46%   |
| HP Compaq            | 14        | 3.23%   |
| Lenovo IdeaPad       | 13        | 3%      |
| HP Pavilion          | 12        | 2.77%   |
| ECS H61H2-CM         | 12        | 2.77%   |
| Acer Aspire          | 12        | 2.77%   |
| Lenovo ThinkCentre   | 11        | 2.54%   |
| Dell OptiPlex        | 9         | 2.08%   |
| VIT P2400            | 8         | 1.85%   |
| Unknown              | 8         | 1.85%   |
| Lenovo ThinkPad      | 7         | 1.62%   |
| langchao 12345       | 7         | 1.62%   |
| Dell Latitude        | 7         | 1.62%   |
| ASRock G41M-VS3      | 7         | 1.62%   |
| VIT M2400-01         | 6         | 1.39%   |
| Dell Vostro          | 6         | 1.39%   |
| VIT P3400            | 5         | 1.15%   |
| VIT P2402            | 5         | 1.15%   |
| Pegatron Compaq      | 5         | 1.15%   |
| ASUS ASUS            | 5         | 1.15%   |
| ASRock N68-VS3       | 5         | 1.15%   |
| Lenovo 3000          | 4         | 0.92%   |
| HP Laptop            | 4         | 0.92%   |
| HP EliteDesk         | 4         | 0.92%   |
| ASUS VivoBook        | 4         | 0.92%   |
| ASRock N68C-S        | 4         | 0.92%   |
| ASRock H61M-VG3      | 4         | 0.92%   |
| VIT P1400            | 3         | 0.69%   |
| VIT M2420            | 3         | 0.69%   |
| Shanghai Zhaoxin ZXE | 3         | 0.69%   |
| HP ProDesk           | 3         | 0.69%   |
| Google Candy         | 3         | 0.69%   |
| Gigabyte 970A-DS3P   | 3         | 0.69%   |
| Dell Precision       | 3         | 0.69%   |
| Biostar G41D3        | 3         | 0.69%   |
| VIT M2421            | 2         | 0.46%   |
| VIT Aptio            | 2         | 0.46%   |
| Toshiba Satellite    | 2         | 0.46%   |
| Pegatron IPM41-D3    | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 69        | 15.94%  |
| 2010    | 52        | 12.01%  |
| 2012    | 46        | 10.62%  |
| 2013    | 38        | 8.78%   |
| 2008    | 32        | 7.39%   |
| 2014    | 27        | 6.24%   |
| 2007    | 27        | 6.24%   |
| 2022    | 20        | 4.62%   |
| 2020    | 18        | 4.16%   |
| 2009    | 16        | 3.7%    |
| 2021    | 15        | 3.46%   |
| 2019    | 14        | 3.23%   |
| 2006    | 11        | 2.54%   |
| 2023    | 9         | 2.08%   |
| 2018    | 9         | 2.08%   |
| 2015    | 9         | 2.08%   |
| 2017    | 8         | 1.85%   |
| 2016    | 7         | 1.62%   |
| Unknown | 3         | 0.69%   |
| 2024    | 1         | 0.23%   |
| 2005    | 1         | 0.23%   |
| 2002    | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 215       | 49.65%  |
| Notebook    | 190       | 43.88%  |
| Mini pc     | 8         | 1.85%   |
| Tablet      | 7         | 1.62%   |
| All in one  | 7         | 1.62%   |
| Server      | 3         | 0.69%   |
| Convertible | 2         | 0.46%   |
| Other       | 1         | 0.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 423       | 97.69%  |
| Enabled  | 10        | 2.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 427       | 98.61%  |
| Yes  | 6         | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 119       | 26.74%  |
| 4.01-8.0    | 94        | 21.12%  |
| 1.01-2.0    | 70        | 15.73%  |
| 8.01-16.0   | 69        | 15.51%  |
| 16.01-24.0  | 53        | 11.91%  |
| 2.01-3.0    | 18        | 4.04%   |
| 32.01-64.0  | 11        | 2.47%   |
| 24.01-32.0  | 6         | 1.35%   |
| 0.51-1.0    | 3         | 0.67%   |
| 64.01-256.0 | 2         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 189       | 38.89%  |
| 2.01-3.0   | 122       | 25.1%   |
| 4.01-8.0   | 59        | 12.14%  |
| 0.51-1.0   | 58        | 11.93%  |
| 3.01-4.0   | 44        | 9.05%   |
| 8.01-16.0  | 7         | 1.44%   |
| 0.01-0.5   | 6         | 1.23%   |
| 16.01-24.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 272       | 60.99%  |
| 2      | 133       | 29.82%  |
| 3      | 32        | 7.17%   |
| 4      | 6         | 1.35%   |
| 0      | 2         | 0.45%   |
| 6      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 57.73%  |
| Yes       | 186       | 42.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 394       | 90.57%  |
| No        | 41        | 9.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 319       | 73%     |
| No        | 118       | 27%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 273       | 62.33%  |
| Yes       | 165       | 37.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 433       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 185       | 39.53%  |
| Maracaibo                  | 38        | 8.12%   |
| Barquisimeto               | 20        | 4.27%   |
| Valencia                   | 19        | 4.06%   |
| Maracay                    | 19        | 4.06%   |
| San Cristóbal             | 17        | 3.63%   |
| Mérida                    | 12        | 2.56%   |
| San Carlos del Zulia       | 11        | 2.35%   |
| Barcelona                  | 11        | 2.35%   |
| Maturín                   | 8         | 1.71%   |
| Ciudad Guayana             | 8         | 1.71%   |
| Barinas                    | 7         | 1.5%    |
| Vigia                      | 5         | 1.07%   |
| Lecherias                  | 5         | 1.07%   |
| Porlamar                   | 4         | 0.85%   |
| Ciudad Bolívar            | 4         | 0.85%   |
| Araure                     | 4         | 0.85%   |
| Acarigua                   | 4         | 0.85%   |
| San Antonio de Los Altos   | 3         | 0.64%   |
| Puerto Ordaz and San Felix | 3         | 0.64%   |
| Parroquia El Recreo        | 3         | 0.64%   |
| Los Teques                 | 3         | 0.64%   |
| La Guaira                  | 3         | 0.64%   |
| Guatire                    | 3         | 0.64%   |
| Carrizal                   | 3         | 0.64%   |
| Anaco                      | 3         | 0.64%   |
| San Juan de los Morros     | 2         | 0.43%   |
| San Juan Bautista          | 2         | 0.43%   |
| Punto Fijo                 | 2         | 0.43%   |
| Petare                     | 2         | 0.43%   |
| Miranda                    | 2         | 0.43%   |
| Los Palos Grandes          | 2         | 0.43%   |
| Las Vegas                  | 2         | 0.43%   |
| Las Tienditas              | 2         | 0.43%   |
| Guarenas                   | 2         | 0.43%   |
| Guanare                    | 2         | 0.43%   |
| Cua                        | 2         | 0.43%   |
| Coro                       | 2         | 0.43%   |
| Cambural                   | 2         | 0.43%   |
| Cagua                      | 2         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 129       | 183    | 22.4%   |
| Seagate                   | 116       | 167    | 20.14%  |
| Samsung Electronics       | 49        | 53     | 8.51%   |
| Hitachi                   | 48        | 65     | 8.33%   |
| Toshiba                   | 40        | 44     | 6.94%   |
| Kingston                  | 25        | 30     | 4.34%   |
| Unknown                   | 18        | 24     | 3.13%   |
| Intel                     | 15        | 20     | 2.6%    |
| SanDisk                   | 13        | 19     | 2.26%   |
| SK hynix                  | 11        | 13     | 1.91%   |
| Crucial                   | 10        | 14     | 1.74%   |
| PNY                       | 8         | 10     | 1.39%   |
| Patriot                   | 7         | 8      | 1.22%   |
| Micron Technology         | 7         | 10     | 1.22%   |
| Maxtor                    | 7         | 7      | 1.22%   |
| HGST                      | 7         | 7      | 1.22%   |
| LITEONIT                  | 6         | 10     | 1.04%   |
| addlink                   | 6         | 6      | 1.04%   |
| SPCC                      | 5         | 9      | 0.87%   |
| Team                      | 4         | 5      | 0.69%   |
| Fujitsu                   | 4         | 4      | 0.69%   |
| ExcelStor                 | 3         | 3      | 0.52%   |
| A-DATA Technology         | 3         | 3      | 0.52%   |
| Silicon Motion            | 2         | 3      | 0.35%   |
| HUAWEI                    | 2         | 2      | 0.35%   |
| Emtec                     | 2         | 3      | 0.35%   |
| Dahua                     | 2         | 2      | 0.35%   |
| China                     | 2         | 2      | 0.35%   |
| BIWIN                     | 2         | 3      | 0.35%   |
| WALRAM                    | 1         | 1      | 0.17%   |
| Vaseky                    | 1         | 1      | 0.17%   |
| UMIS                      | 1         | 1      | 0.17%   |
| Saichi                    | 1         | 1      | 0.17%   |
| PUSKILL                   | 1         | 1      | 0.17%   |
| Phison Electronics        | 1         | 1      | 0.17%   |
| Phison                    | 1         | 1      | 0.17%   |
| Netac                     | 1         | 1      | 0.17%   |
| Mushkin                   | 1         | 1      | 0.17%   |
| Micron/Crucial Technology | 1         | 1      | 0.17%   |
| Lexar                     | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 16        | 2.57%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 12        | 1.93%   |
| Toshiba DT01ACA050 500GB            | 11        | 1.77%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 1.28%   |
| Seagate ST500DM002-1BD142 500GB     | 7         | 1.12%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 6         | 0.96%   |
| Seagate ST320LM000 HM321HI 320GB    | 6         | 0.96%   |
| Samsung HD502HJ 500GB               | 6         | 0.96%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 0.8%    |
| LITEONIT LMS-32L6M 32GB SSD         | 5         | 0.8%    |
| WDC WD5000AAKS-00UU3A0 500GB        | 4         | 0.64%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 0.64%   |
| WDC WD3200AAJS-08L7A0 320GB         | 4         | 0.64%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4         | 0.64%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB            | 4         | 0.64%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 0.64%   |
| Seagate ST3320418AS 320GB           | 4         | 0.64%   |
| Seagate ST320LT012-9WS14C 320GB     | 4         | 0.64%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 4         | 0.64%   |
| Samsung HN-M320MBB 320GB            | 4         | 0.64%   |
| Samsung HM321HI 320GB               | 4         | 0.64%   |
| Samsung HD322HJ 320GB               | 4         | 0.64%   |
| Samsung HD161HJ 160GB               | 4         | 0.64%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 0.64%   |
| Hitachi HTS543225L9A300 250GB       | 4         | 0.64%   |
| WDC WD5000AAKX-221CA1 500GB         | 3         | 0.48%   |
| WDC WD5000AAKX-001CA0 500GB         | 3         | 0.48%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 0.48%   |
| WDC WD1600AABS-00PRA0 160GB         | 3         | 0.48%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 3         | 0.48%   |
| WDC WD10EZEX-08M2NA0 1TB            | 3         | 0.48%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 0.48%   |
| Toshiba MQ04ABF100 1TB              | 3         | 0.48%   |
| Toshiba MQ01ABF032 320GB            | 3         | 0.48%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.48%   |
| Toshiba MK3275GSX 320GB             | 3         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 0.48%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 0.48%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 125       | 176    | 32.55%  |
| Seagate             | 113       | 163    | 29.43%  |
| Hitachi             | 48        | 65     | 12.5%   |
| Toshiba             | 39        | 43     | 10.16%  |
| Samsung Electronics | 33        | 36     | 8.59%   |
| Maxtor              | 7         | 7      | 1.82%   |
| HGST                | 7         | 7      | 1.82%   |
| Fujitsu             | 4         | 4      | 1.04%   |
| ExcelStor           | 3         | 3      | 0.78%   |
| Unknown             | 2         | 2      | 0.52%   |
| JMicron Technology  | 1         | 1      | 0.26%   |
| IBM/Hitachi         | 1         | 2      | 0.26%   |
| HPE                 | 1         | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 22        | 26     | 20.75%  |
| Crucial             | 10        | 14     | 9.43%   |
| Samsung Electronics | 9         | 10     | 8.49%   |
| PNY                 | 8         | 10     | 7.55%   |
| Patriot             | 7         | 8      | 6.6%    |
| LITEONIT            | 6         | 10     | 5.66%   |
| SPCC                | 4         | 7      | 3.77%   |
| SK hynix            | 4         | 4      | 3.77%   |
| addlink             | 4         | 4      | 3.77%   |
| Team                | 3         | 4      | 2.83%   |
| SanDisk             | 3         | 4      | 2.83%   |
| A-DATA Technology   | 3         | 3      | 2.83%   |
| Emtec               | 2         | 3      | 1.89%   |
| Dahua               | 2         | 2      | 1.89%   |
| China               | 2         | 2      | 1.89%   |
| WDC                 | 1         | 1      | 0.94%   |
| WALRAM              | 1         | 1      | 0.94%   |
| Vaseky              | 1         | 1      | 0.94%   |
| Toshiba             | 1         | 1      | 0.94%   |
| Saichi              | 1         | 1      | 0.94%   |
| PUSKILL             | 1         | 1      | 0.94%   |
| Netac               | 1         | 1      | 0.94%   |
| Micron Technology   | 1         | 3      | 0.94%   |
| Lexar               | 1         | 1      | 0.94%   |
| KingFast            | 1         | 3      | 0.94%   |
| Intenso             | 1         | 1      | 0.94%   |
| Intel               | 1         | 1      | 0.94%   |
| Hewlett-Packard     | 1         | 1      | 0.94%   |
| Gigabyte Technology | 1         | 1      | 0.94%   |
| Dogfish             | 1         | 1      | 0.94%   |
| Dell                | 1         | 2      | 0.94%   |
| BIWIN               | 1         | 2      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 315       | 510    | 63.38%  |
| SSD     | 99        | 134    | 19.92%  |
| NVMe    | 63        | 87     | 12.68%  |
| MMC     | 13        | 18     | 2.62%   |
| Unknown | 7         | 8      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 371       | 640    | 81%     |
| NVMe | 63        | 87     | 13.76%  |
| MMC  | 13        | 18     | 2.84%   |
| SAS  | 11        | 12     | 2.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 333       | 514    | 79.29%  |
| 0.51-1.0   | 67        | 97     | 15.95%  |
| 1.01-2.0   | 12        | 20     | 2.86%   |
| 3.01-4.0   | 4         | 8      | 0.95%   |
| 2.01-3.0   | 2         | 3      | 0.48%   |
| 10.01-20.0 | 1         | 1      | 0.24%   |
| 4.01-10.0  | 1         | 1      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 144       | 31.1%   |
| 101-250        | 108       | 23.33%  |
| 501-1000       | 64        | 13.82%  |
| 1-20           | 49        | 10.58%  |
| 51-100         | 35        | 7.56%   |
| 1001-2000      | 24        | 5.18%   |
| 21-50          | 20        | 4.32%   |
| 2001-3000      | 7         | 1.51%   |
| More than 3000 | 6         | 1.3%    |
| Unknown        | 6         | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 187       | 39.2%   |
| 21-50          | 86        | 18.03%  |
| 101-250        | 68        | 14.26%  |
| 51-100         | 54        | 11.32%  |
| 251-500        | 44        | 9.22%   |
| 501-1000       | 20        | 4.19%   |
| 1001-2000      | 6         | 1.26%   |
| Unknown        | 6         | 1.26%   |
| 2001-3000      | 4         | 0.84%   |
| More than 3000 | 2         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB      | 6         | 8      | 4.65%   |
| Seagate ST320LT012-1DG14C 320GB   | 6         | 7      | 4.65%   |
| Toshiba DT01ACA050 500GB          | 4         | 5      | 3.1%    |
| Hitachi HTS543225L9A300 250GB     | 4         | 4      | 3.1%    |
| Samsung Electronics HM321HI 320GB | 3         | 3      | 2.33%   |
| Hitachi HDS721616PLA380 160GB     | 3         | 3      | 2.33%   |
| WDC WD5000AAKX-221CA1 500GB       | 2         | 2      | 1.55%   |
| WDC WD5000AAKS-00A7B0 500GB       | 2         | 2      | 1.55%   |
| WDC WD3200AAJS-08L7A0 320GB       | 2         | 3      | 1.55%   |
| WDC WD1200BEVS-60UST0 120GB       | 2         | 2      | 1.55%   |
| Toshiba MK3275GSX 320GB           | 2         | 3      | 1.55%   |
| Seagate ST9500325AS 500GB         | 2         | 2      | 1.55%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 1.55%   |
| Seagate ST3500312CS 500GB         | 2         | 2      | 1.55%   |
| Samsung Electronics HM250HI 250GB | 2         | 2      | 1.55%   |
| Samsung Electronics HD161GJ 160GB | 2         | 2      | 1.55%   |
| Maxtor STM3160215AS 160GB         | 2         | 2      | 1.55%   |
| Hitachi HTS725050A9A364 500GB     | 2         | 2      | 1.55%   |
| Hitachi HDS728080PLA380 80GB      | 2         | 2      | 1.55%   |
| HGST HTS545050A7E380 500GB        | 2         | 2      | 1.55%   |
| WDC WD800BD-08MRA1 80GB           | 1         | 1      | 0.78%   |
| WDC WD800BB-22JHC0 80GB           | 1         | 1      | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 0.78%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1         | 1      | 0.78%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 1      | 0.78%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 2      | 0.78%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1         | 1      | 0.78%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1         | 1      | 0.78%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1         | 1      | 0.78%   |
| WDC WD50 00BPVT-24HXZT1 500GB     | 1         | 1      | 0.78%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 0.78%   |
| WDC WD3200BEVT-00A0RT0 320GB      | 1         | 1      | 0.78%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1         | 1      | 0.78%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 1      | 0.78%   |
| WDC WD2500BEVT-60ZCT1 250GB       | 1         | 1      | 0.78%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1         | 1      | 0.78%   |
| WDC WD10JPVX-22JC3T0 1TB          | 1         | 2      | 0.78%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1         | 1      | 0.78%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1         | 1      | 0.78%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1         | 1      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 35     | 26.45%  |
| WDC                 | 28        | 39     | 23.14%  |
| Hitachi             | 24        | 24     | 19.83%  |
| Samsung Electronics | 12        | 13     | 9.92%   |
| Toshiba             | 11        | 14     | 9.09%   |
| Maxtor              | 3         | 3      | 2.48%   |
| HGST                | 3         | 3      | 2.48%   |
| Intel               | 2         | 2      | 1.65%   |
| ExcelStor           | 2         | 2      | 1.65%   |
| SK hynix            | 1         | 1      | 0.83%   |
| Kingston            | 1         | 1      | 0.83%   |
| JMicron Technology  | 1         | 1      | 0.83%   |
| IBM/Hitachi         | 1         | 2      | 0.83%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 35     | 27.35%  |
| WDC                 | 28        | 39     | 23.93%  |
| Hitachi             | 24        | 24     | 20.51%  |
| Samsung Electronics | 12        | 13     | 10.26%  |
| Toshiba             | 11        | 14     | 9.4%    |
| Maxtor              | 3         | 3      | 2.56%   |
| HGST                | 3         | 3      | 2.56%   |
| ExcelStor           | 2         | 2      | 1.71%   |
| JMicron Technology  | 1         | 1      | 0.85%   |
| IBM/Hitachi         | 1         | 2      | 0.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 101       | 136    | 96.19%  |
| NVMe | 3         | 3      | 2.86%   |
| SSD  | 1         | 1      | 0.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB  | 2         | 2      | 50%     |
| WDC WD800JD-00MSA1 80GB   | 1         | 1      | 25%     |
| Seagate ST9320423AS 320GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 223       | 407    | 46.75%  |
| Works    | 145       | 206    | 30.4%   |
| Malfunc  | 105       | 140    | 22.01%  |
| Failed   | 4         | 4      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 343       | 71.31%  |
| AMD                         | 46        | 9.56%   |
| Nvidia                      | 21        | 4.37%   |
| SanDisk                     | 13        | 2.7%    |
| SK hynix                    | 7         | 1.46%   |
| Samsung Electronics         | 7         | 1.46%   |
| Micron Technology           | 6         | 1.25%   |
| Marvell Technology Group    | 6         | 1.25%   |
| JMicron Technology          | 6         | 1.25%   |
| VIA Technologies            | 4         | 0.83%   |
| Silicon Motion              | 4         | 0.83%   |
| Phison Electronics          | 4         | 0.83%   |
| Jiangsu Huacun Elec.        | 4         | 0.83%   |
| Kingston Technology Company | 3         | 0.62%   |
| ASMedia Technology          | 3         | 0.62%   |
| Union Memory (Shenzhen)     | 1         | 0.21%   |
| Micron/Crucial Technology   | 1         | 0.21%   |
| MAXIO Technology (Hangzhou) | 1         | 0.21%   |
| Adaptec                     | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 54        | 8.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 42        | 6.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 33        | 5.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 27        | 4.23%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 26        | 4.08%   |
| Nvidia MCP61 SATA Controller                                                            | 19        | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18        | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18        | 2.82%   |
| Nvidia MCP61 IDE                                                                        | 17        | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 16        | 2.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 13        | 2.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 11        | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 11        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.25%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 1.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 8         | 1.25%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 8         | 1.25%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 0.94%   |
| Intel SSD 660P Series                                                                   | 6         | 0.94%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 0.94%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 0.94%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 0.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5         | 0.78%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 5         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 0.78%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 4         | 0.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 4         | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                   | 4         | 0.63%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 4         | 0.63%   |
| Jiangsu Huacun Elec. MMY MMSP350 PCIe 3 NVMe SSD (DRAM-less)                            | 4         | 0.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 254       | 49.9%   |
| IDE  | 157       | 30.84%  |
| NVMe | 63        | 12.38%  |
| RAID | 33        | 6.48%   |
| SAS  | 1         | 0.2%    |
| SCSI | 1         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 358       | 82.68%  |
| AMD          | 72        | 16.63%  |
| CentaurHauls | 3         | 0.69%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 9         | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 8         | 1.85%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 8         | 1.85%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 8         | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 8         | 1.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 7         | 1.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 7         | 1.62%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 6         | 1.39%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 6         | 1.39%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 5         | 1.15%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz    | 4         | 0.92%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 4         | 0.92%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 4         | 0.92%   |
| Intel Pentium 4 CPU 3.00GHz                    | 4         | 0.92%   |
| Intel Core i5-3330 CPU @ 3.00GHz               | 4         | 0.92%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 4         | 0.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 4         | 0.92%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 0.92%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz    | 3         | 0.69%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 3         | 0.69%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 0.69%   |
| Intel Pentium CPU N3710 @ 1.60GHz              | 3         | 0.69%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 3         | 0.69%   |
| Intel Pentium CPU G2010 @ 2.80GHz              | 3         | 0.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 3         | 0.69%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 3         | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 3         | 0.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 0.69%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 3         | 0.69%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 3         | 0.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3         | 0.69%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3         | 0.69%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 0.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 3         | 0.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz           | 3         | 0.69%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 3         | 0.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 3         | 0.69%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 0.69%   |
| AMD Sempron 145 Processor                      | 3         | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 3         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 75        | 17.32%  |
| Intel Core i3                        | 42        | 9.7%    |
| Intel Pentium Dual-Core              | 36        | 8.31%   |
| Intel Core i7                        | 33        | 7.62%   |
| Intel Celeron                        | 31        | 7.16%   |
| Other                                | 30        | 6.93%   |
| Intel Core 2 Duo                     | 29        | 6.7%    |
| Intel Pentium                        | 27        | 6.24%   |
| Intel Pentium Dual                   | 14        | 3.23%   |
| Intel Atom                           | 12        | 2.77%   |
| AMD Ryzen 5                          | 12        | 2.77%   |
| Intel Pentium 4                      | 8         | 1.85%   |
| Intel Xeon                           | 7         | 1.62%   |
| AMD Sempron                          | 7         | 1.62%   |
| AMD Ryzen 7                          | 7         | 1.62%   |
| Intel Core 2 Quad                    | 6         | 1.39%   |
| Intel Core 2                         | 6         | 1.39%   |
| AMD FX                               | 6         | 1.39%   |
| AMD Athlon II X2                     | 4         | 0.92%   |
| AMD Ryzen 3                          | 3         | 0.69%   |
| AMD Phenom II X4                     | 3         | 0.69%   |
| AMD Athlon II X4                     | 3         | 0.69%   |
| AMD Athlon 64 X2                     | 3         | 0.69%   |
| Intel Pentium D                      | 2         | 0.46%   |
| Intel Genuine                        | 2         | 0.46%   |
| AMD Phenom                           | 2         | 0.46%   |
| AMD E1                               | 2         | 0.46%   |
| AMD C-70                             | 2         | 0.46%   |
| AMD Athlon                           | 2         | 0.46%   |
| AMD A6                               | 2         | 0.46%   |
| AMD A10                              | 2         | 0.46%   |
| Intel Pentium Silver                 | 1         | 0.23%   |
| Intel Core i9                        | 1         | 0.23%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.23%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.23%   |
| AMD Quad-Core                        | 1         | 0.23%   |
| AMD Phenom II X6                     | 1         | 0.23%   |
| AMD Phenom II X2                     | 1         | 0.23%   |
| AMD Phenom II                        | 1         | 0.23%   |
| AMD Mobile Sempron                   | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 242       | 55.89%  |
| 4       | 119       | 27.48%  |
| 1       | 26        | 6%      |
| 6       | 18        | 4.16%   |
| 8       | 11        | 2.54%   |
| 3       | 7         | 1.62%   |
| Unknown | 4         | 0.92%   |
| 14      | 3         | 0.69%   |
| 24      | 1         | 0.23%   |
| 12      | 1         | 0.23%   |
| 10      | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 433       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 245       | 56.58%  |
| 2       | 184       | 42.49%  |
| Unknown | 4         | 0.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 422       | 97.46%  |
| 64-bit         | 5         | 1.15%   |
| 32-bit         | 5         | 1.15%   |
| Unknown        | 1         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 145       | 32.08%  |
| 0x1067a    | 43        | 9.51%   |
| 0x206a7    | 40        | 8.85%   |
| 0x306a9    | 33        | 7.3%    |
| 0x6fd      | 15        | 3.32%   |
| 0x306c3    | 11        | 2.43%   |
| 0x806c1    | 7         | 1.55%   |
| 0x30678    | 7         | 1.55%   |
| 0x30673    | 7         | 1.55%   |
| 0x106ca    | 7         | 1.55%   |
| 0x010000c8 | 6         | 1.33%   |
| 0x806e9    | 5         | 1.11%   |
| 0x6fb      | 5         | 1.11%   |
| 0x20655    | 5         | 1.11%   |
| 0xf65      | 4         | 0.88%   |
| 0x010000b6 | 4         | 0.88%   |
| 0xa0671    | 3         | 0.66%   |
| 0x806ec    | 3         | 0.66%   |
| 0x6f2      | 3         | 0.66%   |
| 0x506e3    | 3         | 0.66%   |
| 0x406e3    | 3         | 0.66%   |
| 0x40651    | 3         | 0.66%   |
| 0x106a5    | 3         | 0.66%   |
| 0x10676    | 3         | 0.66%   |
| 0x06000852 | 3         | 0.66%   |
| 0x0600063e | 3         | 0.66%   |
| 0x05000119 | 3         | 0.66%   |
| 0x010000c7 | 3         | 0.66%   |
| 0x906e9    | 2         | 0.44%   |
| 0x806ea    | 2         | 0.44%   |
| 0x806d1    | 2         | 0.44%   |
| 0x6f6      | 2         | 0.44%   |
| 0x406c4    | 2         | 0.44%   |
| 0x306d4    | 2         | 0.44%   |
| 0x206d7    | 2         | 0.44%   |
| 0x20652    | 2         | 0.44%   |
| 0x0a50000d | 2         | 0.44%   |
| 0x08608103 | 2         | 0.44%   |
| 0x08600104 | 2         | 0.44%   |
| 0x08108102 | 2         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 59        | 13.63%  |
| SandyBridge      | 57        | 13.16%  |
| IvyBridge        | 55        | 12.7%   |
| Core             | 37        | 8.55%   |
| Haswell          | 23        | 5.31%   |
| K10              | 21        | 4.85%   |
| Silvermont       | 20        | 4.62%   |
| KabyLake         | 18        | 4.16%   |
| Westmere         | 14        | 3.23%   |
| TigerLake        | 12        | 2.77%   |
| Bonnell          | 11        | 2.54%   |
| NetBurst         | 10        | 2.31%   |
| Unknown          | 10        | 2.31%   |
| Alderlake Hybrid | 8         | 1.85%   |
| Zen+             | 7         | 1.62%   |
| Skylake          | 7         | 1.62%   |
| Icelake          | 7         | 1.62%   |
| K8 Hammer        | 6         | 1.39%   |
| Zen 2            | 5         | 1.15%   |
| CometLake        | 5         | 1.15%   |
| Bobcat           | 5         | 1.15%   |
| Piledriver       | 4         | 0.92%   |
| Nehalem          | 4         | 0.92%   |
| Goldmont plus    | 4         | 0.92%   |
| Zen 3            | 3         | 0.69%   |
| Zen              | 3         | 0.69%   |
| Excavator        | 3         | 0.69%   |
| Bulldozer        | 3         | 0.69%   |
| Broadwell        | 3         | 0.69%   |
| K8 & K10 hybrid  | 2         | 0.46%   |
| K10 Llano        | 2         | 0.46%   |
| Jaguar           | 2         | 0.46%   |
| Steamroller      | 1         | 0.23%   |
| P6               | 1         | 0.23%   |
| Goldmont         | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 300       | 64.79%  |
| AMD                        | 79        | 17.06%  |
| Nvidia                     | 75        | 16.2%   |
| VIA Technologies           | 4         | 0.86%   |
| Zhaoxin                    | 3         | 0.65%   |
| Matrox Electronics Systems | 1         | 0.22%   |
| ASPEED Technology          | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 50        | 10.37%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 26        | 5.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 4.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 3.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12        | 2.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 2.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 2.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.28%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 9         | 1.87%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7         | 1.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 6         | 1.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.24%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5         | 1.04%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 5         | 1.04%   |
| AMD Lucienne                                                                             | 5         | 1.04%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 4         | 0.83%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 0.83%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 4         | 0.83%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 4         | 0.83%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 4         | 0.83%   |
| Intel HD Graphics 620                                                                    | 4         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.83%   |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 4         | 0.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.83%   |
| Zhaoxin KX-6000 C-960 GPU                                                                | 3         | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.62%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3         | 0.62%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 3         | 0.62%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 0.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.62%   |
| Intel HD Graphics 630                                                                    | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 270       | 61.93%  |
| 1 x AMD         | 69        | 15.83%  |
| 1 x Nvidia      | 59        | 13.53%  |
| Intel + Nvidia  | 13        | 2.98%   |
| 2 x Intel       | 6         | 1.38%   |
| 1 x VIA         | 4         | 0.92%   |
| 2 x AMD         | 3         | 0.69%   |
| 1 x Zhaoxin     | 3         | 0.69%   |
| Intel + AMD     | 3         | 0.69%   |
| AMD + Nvidia    | 3         | 0.69%   |
| Other           | 1         | 0.23%   |
| Nvidia + ASPEED | 1         | 0.23%   |
| 1 x Matrox      | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 379       | 86.93%  |
| Proprietary | 35        | 8.03%   |
| Unknown     | 22        | 5.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 307       | 68.99%  |
| 0.01-0.5   | 51        | 11.46%  |
| 0.51-1.0   | 45        | 10.11%  |
| 1.01-2.0   | 30        | 6.74%   |
| 3.01-4.0   | 9         | 2.02%   |
| 5.01-6.0   | 2         | 0.45%   |
| 7.01-8.0   | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 81        | 18.84%  |
| BOE                                   | 34        | 7.91%   |
| AU Optronics                          | 34        | 7.91%   |
| LG Display                            | 28        | 6.51%   |
| Goldstar                              | 27        | 6.28%   |
| Chimei Innolux                        | 25        | 5.81%   |
| Hewlett-Packard                       | 24        | 5.58%   |
| Toshiba                               | 18        | 4.19%   |
| Lenovo                                | 17        | 3.95%   |
| Dell                                  | 15        | 3.49%   |
| Acer                                  | 14        | 3.26%   |
| InfoVision                            | 13        | 3.02%   |
| AOC                                   | 13        | 3.02%   |
| Vita                                  | 11        | 2.56%   |
| LG Philips                            | 7         | 1.63%   |
| Chi Mei Optoelectronics               | 7         | 1.63%   |
| BenQ                                  | 5         | 1.16%   |
| HannStar                              | 4         | 0.93%   |
| Apple                                 | 4         | 0.93%   |
| Unknown (XXX)                         | 3         | 0.7%    |
| LG Electronics                        | 3         | 0.7%    |
| ViewSonic                             | 2         | 0.47%   |
| Sony                                  | 2         | 0.47%   |
| PANDA                                 | 2         | 0.47%   |
| NEC Computers                         | 2         | 0.47%   |
| MStar                                 | 2         | 0.47%   |
| KTC                                   | 2         | 0.47%   |
| ITL                                   | 2         | 0.47%   |
| IPS                                   | 2         | 0.47%   |
| HKC                                   | 2         | 0.47%   |
| Envision                              | 2         | 0.47%   |
| Vizio                                 | 1         | 0.23%   |
| Unknown (CEA)                         | 1         | 0.23%   |
| Toshiba Matsushita Display Technology | 1         | 0.23%   |
| TCL                                   | 1         | 0.23%   |
| Sharp                                 | 1         | 0.23%   |
| Sceptre Tech                          | 1         | 0.23%   |
| PXO                                   | 1         | 0.23%   |
| Plain Tree Systems                    | 1         | 0.23%   |
| PEGA                                  | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 14        | 3.2%    |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 11        | 2.51%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 8         | 1.83%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 6         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 6         | 1.37%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                | 5         | 1.14%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 5         | 1.14%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 4         | 0.91%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch | 4         | 0.91%   |
| Toshiba TV TSB0206 1920x1080                                         | 3         | 0.68%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 0.68%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch          | 3         | 0.68%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 3         | 0.68%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 0.68%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 3         | 0.68%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 3         | 0.68%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 0.68%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 3         | 0.68%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 3         | 0.68%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch               | 2         | 0.46%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 2         | 0.46%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2         | 0.46%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.46%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.46%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.46%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                       | 2         | 0.46%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch        | 2         | 0.46%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 2         | 0.46%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 2         | 0.46%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.46%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.46%   |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                 | 2         | 0.46%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 2         | 0.46%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                     | 2         | 0.46%   |
| IPS ZP2200 IPS2200 1920x1080 477x268mm 21.5-inch                     | 2         | 0.46%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.46%   |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch           | 2         | 0.46%   |
| Goldstar L194W GSM4B6A 1440x900 408x255mm 18.9-inch                  | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 147       | 35.17%  |
| 1920x1080 (FHD)    | 98        | 23.44%  |
| 1280x1024 (SXGA)   | 37        | 8.85%   |
| 1440x900 (WXGA+)   | 33        | 7.89%   |
| 1600x900 (HD+)     | 26        | 6.22%   |
| 1280x800 (WXGA)    | 17        | 4.07%   |
| 1360x768           | 12        | 2.87%   |
| 1680x1050 (WSXGA+) | 11        | 2.63%   |
| 1024x768 (XGA)     | 8         | 1.91%   |
| 1920x1200 (WUXGA)  | 6         | 1.44%   |
| 3840x2160 (4K)     | 5         | 1.2%    |
| 2560x1440 (QHD)    | 5         | 1.2%    |
| 1280x720 (HD)      | 4         | 0.96%   |
| 1024x600           | 3         | 0.72%   |
| Unknown            | 2         | 0.48%   |
| 3840x1080          | 1         | 0.24%   |
| 3240x2160          | 1         | 0.24%   |
| 2560x1600          | 1         | 0.24%   |
| 2240x1400          | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 89        | 20.75%  |
| 18      | 57        | 13.29%  |
| 14      | 43        | 10.02%  |
| 13      | 36        | 8.39%   |
| 17      | 35        | 8.16%   |
| 21      | 34        | 7.93%   |
| 19      | 33        | 7.69%   |
| Unknown | 16        | 3.73%   |
| 23      | 15        | 3.5%    |
| 20      | 11        | 2.56%   |
| 10      | 11        | 2.56%   |
| 22      | 7         | 1.63%   |
| 11      | 7         | 1.63%   |
| 27      | 6         | 1.4%    |
| 16      | 6         | 1.4%    |
| 32      | 4         | 0.93%   |
| 24      | 4         | 0.93%   |
| 74      | 3         | 0.7%    |
| 31      | 3         | 0.7%    |
| 72      | 2         | 0.47%   |
| 52      | 2         | 0.47%   |
| 12      | 2         | 0.47%   |
| 54      | 1         | 0.23%   |
| 42      | 1         | 0.23%   |
| 39      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 189       | 44.89%  |
| 401-500     | 129       | 30.64%  |
| 501-600     | 24        | 5.7%    |
| 201-300     | 24        | 5.7%    |
| 351-400     | 22        | 5.23%   |
| Unknown     | 16        | 3.8%    |
| 1501-2000   | 5         | 1.19%   |
| 701-800     | 4         | 0.95%   |
| 601-700     | 3         | 0.71%   |
| 1001-1500   | 3         | 0.71%   |
| 801-900     | 1         | 0.24%   |
| 901-1000    | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 269       | 67.76%  |
| 16/10   | 72        | 18.14%  |
| 5/4     | 33        | 8.31%   |
| Unknown | 11        | 2.77%   |
| 4/3     | 9         | 2.27%   |
| 3/2     | 3         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 88        | 20.66%  |
| 81-90          | 76        | 17.84%  |
| 151-200        | 72        | 16.9%   |
| 141-150        | 65        | 15.26%  |
| 201-250        | 43        | 10.09%  |
| Unknown        | 16        | 3.76%   |
| 41-50          | 11        | 2.58%   |
| 121-130        | 10        | 2.35%   |
| More than 1000 | 8         | 1.88%   |
| 51-60          | 7         | 1.64%   |
| 351-500        | 7         | 1.64%   |
| 301-350        | 6         | 1.41%   |
| 111-120        | 4         | 0.94%   |
| 251-300        | 3         | 0.7%    |
| 131-140        | 3         | 0.7%    |
| 71-80          | 2         | 0.47%   |
| 61-70          | 2         | 0.47%   |
| 501-1000       | 2         | 0.47%   |
| 91-100         | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 187       | 44.52%  |
| 101-120       | 132       | 31.43%  |
| 121-160       | 67        | 15.95%  |
| Unknown       | 16        | 3.81%   |
| 1-50          | 12        | 2.86%   |
| 161-240       | 4         | 0.95%   |
| More than 240 | 2         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 362       | 82.27%  |
| 2     | 46        | 10.45%  |
| 0     | 27        | 6.14%   |
| 3     | 5         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 269       | 39.21%  |
| Intel                             | 133       | 19.39%  |
| Qualcomm Atheros                  | 115       | 16.76%  |
| Broadcom                          | 33        | 4.81%   |
| Ralink                            | 21        | 3.06%   |
| Nvidia                            | 20        | 2.92%   |
| Ralink Technology                 | 13        | 1.9%    |
| TP-Link                           | 10        | 1.46%   |
| MediaTek                          | 9         | 1.31%   |
| Xiaomi                            | 8         | 1.17%   |
| Marvell Technology Group          | 8         | 1.17%   |
| Broadcom Limited                  | 8         | 1.17%   |
| Qualcomm Atheros Communications   | 6         | 0.87%   |
| VIA Technologies                  | 4         | 0.58%   |
| JMicron Technology                | 4         | 0.58%   |
| Samsung Electronics               | 3         | 0.44%   |
| D-Link System                     | 3         | 0.44%   |
| Trendchip Technologies            | 2         | 0.29%   |
| Sundance Technology Inc / IC Plus | 2         | 0.29%   |
| Mercucys                          | 2         | 0.29%   |
| ASIX Electronics                  | 2         | 0.29%   |
| ZyXEL Communications              | 1         | 0.15%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.15%   |
| National Semiconductor            | 1         | 0.15%   |
| Motorola PCS                      | 1         | 0.15%   |
| Motorola BCS                      | 1         | 0.15%   |
| ICS Advent                        | 1         | 0.15%   |
| Huawei Technologies               | 1         | 0.15%   |
| Digium                            | 1         | 0.15%   |
| Davicom Semiconductor             | 1         | 0.15%   |
| AMD                               | 1         | 0.15%   |
| ADMtek                            | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 166       | 21.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 48        | 6.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 29        | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 20        | 2.61%   |
| Nvidia MCP61 Ethernet                                                         | 18        | 2.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 11        | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 11        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 11        | 1.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 11        | 1.44%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 10        | 1.31%   |
| Intel Wi-Fi 6 AX201                                                           | 10        | 1.31%   |
| Intel Ethernet Connection I217-LM                                             | 10        | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 9         | 1.18%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 9         | 1.18%   |
| Intel Wireless 7265                                                           | 9         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 8         | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 8         | 1.05%   |
| Ralink MT7601U Wireless Adapter                                               | 7         | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 7         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 7         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 0.92%   |
| Intel Wireless 7260                                                           | 7         | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 6         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 6         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 6         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 5         | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 5         | 0.65%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 5         | 0.65%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 5         | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 0.65%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 5         | 0.65%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 4         | 0.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 4         | 0.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 4         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 4         | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 4         | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 4         | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 86        | 25.67%  |
| Realtek Semiconductor           | 81        | 24.18%  |
| Intel                           | 81        | 24.18%  |
| Ralink                          | 21        | 6.27%   |
| Broadcom                        | 18        | 5.37%   |
| Ralink Technology               | 13        | 3.88%   |
| TP-Link                         | 9         | 2.69%   |
| MediaTek                        | 8         | 2.39%   |
| Qualcomm Atheros Communications | 6         | 1.79%   |
| Broadcom Limited                | 4         | 1.19%   |
| D-Link System                   | 3         | 0.9%    |
| Xiaomi                          | 2         | 0.6%    |
| Mercucys                        | 2         | 0.6%    |
| Marvell Technology Group        | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 29        | 8.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 11        | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 11        | 3.28%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 10        | 2.99%   |
| Intel Wi-Fi 6 AX201                                                            | 10        | 2.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 9         | 2.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 9         | 2.69%   |
| Intel Wireless 7265                                                            | 9         | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 8         | 2.39%   |
| Ralink MT7601U Wireless Adapter                                                | 7         | 2.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7         | 2.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 7         | 2.09%   |
| Intel Wireless 7260                                                            | 7         | 2.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 6         | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 6         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 6         | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 5         | 1.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5         | 1.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 5         | 1.49%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 5         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 1.49%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 5         | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 5         | 1.49%   |
| Intel Wi-Fi 6 AX200                                                            | 5         | 1.49%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4         | 1.19%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 1.19%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4         | 1.19%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 4         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 1.19%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4         | 1.19%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 1.19%   |
| Intel WiFi Link 5100                                                           | 4         | 1.19%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 1.19%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 0.9%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 3         | 0.9%    |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 0.9%    |
| Intel Wireless 3165                                                            | 3         | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 3         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                                 | 3         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 230       | 54.89%  |
| Intel                             | 71        | 16.95%  |
| Qualcomm Atheros                  | 39        | 9.31%   |
| Nvidia                            | 20        | 4.77%   |
| Broadcom                          | 16        | 3.82%   |
| Marvell Technology Group          | 7         | 1.67%   |
| Xiaomi                            | 6         | 1.43%   |
| VIA Technologies                  | 4         | 0.95%   |
| JMicron Technology                | 4         | 0.95%   |
| Broadcom Limited                  | 4         | 0.95%   |
| Samsung Electronics               | 3         | 0.72%   |
| Trendchip Technologies            | 2         | 0.48%   |
| Sundance Technology Inc / IC Plus | 2         | 0.48%   |
| ASIX Electronics                  | 2         | 0.48%   |
| ZyXEL Communications              | 1         | 0.24%   |
| TP-Link                           | 1         | 0.24%   |
| National Semiconductor            | 1         | 0.24%   |
| Motorola PCS                      | 1         | 0.24%   |
| Motorola BCS                      | 1         | 0.24%   |
| MediaTek                          | 1         | 0.24%   |
| ICS Advent                        | 1         | 0.24%   |
| Davicom Semiconductor             | 1         | 0.24%   |
| ADMtek                            | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 166       | 38.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 11.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 4.69%   |
| Nvidia MCP61 Ethernet                                                  | 18        | 4.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 11        | 2.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 11        | 2.58%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 2.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 1.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 4         | 0.94%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                  | 4         | 0.94%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 0.7%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 0.7%    |
| Intel PRO/100 VE Network Connection                                    | 3         | 0.7%    |
| Intel Ethernet Connection I217-V                                       | 3         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.7%    |
| Intel 82567V-2 Gigabit Network Connection                              | 3         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.47%   |
| Trendchip Ethernet controller                                          | 2         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.47%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.47%   |
| Intel 82574L Gigabit Network Connection                                | 2         | 0.47%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.47%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.47%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 2         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.47%   |
| ZyXEL ADSL Modem Prestige 600 series                                   | 1         | 0.23%   |
| TP-Link M7010                                                          | 1         | 0.23%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                  | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 393       | 54.89%  |
| WiFi     | 319       | 44.55%  |
| Modem    | 3         | 0.42%   |
| Unknown  | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 232       | 51.1%   |
| Ethernet | 222       | 48.9%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 242       | 55.25%  |
| 1     | 186       | 42.47%  |
| 3     | 4         | 0.91%   |
| 0     | 4         | 0.91%   |
| 33    | 1         | 0.23%   |
| 4     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 432       | 99.08%  |
| Yes  | 4         | 0.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 33.73%  |
| Realtek Semiconductor           | 24        | 14.46%  |
| IMC Networks                    | 19        | 11.45%  |
| Cambridge Silicon Radio         | 19        | 11.45%  |
| Qualcomm Atheros Communications | 17        | 10.24%  |
| Broadcom                        | 11        | 6.63%   |
| Lite-On Technology              | 5         | 3.01%   |
| Apple                           | 4         | 2.41%   |
| ASUSTek Computer                | 3         | 1.81%   |
| Hewlett-Packard                 | 2         | 1.2%    |
| Dell                            | 2         | 1.2%    |
| SiW                             | 1         | 0.6%    |
| Marvell Semiconductor           | 1         | 0.6%    |
| Foxconn / Hon Hai               | 1         | 0.6%    |
| Alps Electric                   | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 11.45%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 19        | 11.45%  |
| Intel AX201 Bluetooth                                       | 17        | 10.24%  |
| Realtek Bluetooth Radio                                     | 11        | 6.63%   |
| Realtek RTL8723B Bluetooth                                  | 9         | 5.42%   |
| Qualcomm Atheros  Bluetooth Device                          | 6         | 3.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 3.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 6         | 3.61%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 3.01%   |
| Intel Bluetooth Device                                      | 5         | 3.01%   |
| Intel AX200 Bluetooth                                       | 5         | 3.01%   |
| IMC Networks Wireless_Device                                | 5         | 3.01%   |
| IMC Networks Bluetooth                                      | 4         | 2.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 1.81%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 1.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 1.81%   |
| Realtek RTL8723A Bluetooth                                  | 2         | 1.2%    |
| Qualcomm Atheros Bluetooth (AR3011)                         | 2         | 1.2%    |
| Lite-On Wireless_Device                                     | 2         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.2%    |
| IMC Networks Bluetooth Radio                                | 2         | 1.2%    |
| IMC Networks Bluetooth Module                               | 2         | 1.2%    |
| SiW SiW                                                     | 1         | 0.6%    |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.6%    |
| Realtek 802.11ac WLAN Adapter                               | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.6%    |
| Marvell Bluetooth and Wireless LAN Composite                | 1         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.6%    |
| Lite-On Bluetooth Device                                    | 1         | 0.6%    |
| Lite-On BCM20702A0                                          | 1         | 0.6%    |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.6%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.6%    |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.6%    |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.6%    |
| Broadcom HP Portable Valentine                              | 1         | 0.6%    |
| Broadcom Bluetooth 2.0+eDR dongle                           | 1         | 0.6%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle         | 1         | 0.6%    |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 346       | 63.72%  |
| AMD                    | 83        | 15.29%  |
| Nvidia                 | 63        | 11.6%   |
| C-Media Electronics    | 10        | 1.84%   |
| VIA Technologies       | 6         | 1.1%    |
| Creative Labs          | 6         | 1.1%    |
| Generalplus Technology | 4         | 0.74%   |
| Zhaoxin                | 3         | 0.55%   |
| Logitech               | 3         | 0.55%   |
| JMTek                  | 3         | 0.55%   |
| Microsoft              | 2         | 0.37%   |
| DSEA A/S               | 2         | 0.37%   |
| Corsair                | 2         | 0.37%   |
| Cirrus Logic           | 2         | 0.37%   |
| Unknown                | 1         | 0.18%   |
| Texas Instruments      | 1         | 0.18%   |
| Realtek Semiconductor  | 1         | 0.18%   |
| Megawin Technology     | 1         | 0.18%   |
| M-Audio                | 1         | 0.18%   |
| Giga-Byte Technology   | 1         | 0.18%   |
| Aureal Semiconductor   | 1         | 0.18%   |
| ASUSTek Computer       | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 66        | 10.75%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 64        | 10.42%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 43        | 7%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 3.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 19        | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 2.93%   |
| Nvidia MCP61 High Definition Audio                                                                | 17        | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 2.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 2.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 1.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.79%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 9         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 9         | 1.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 7         | 1.14%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.81%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 4         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.65%   |
| Generalplus Technology USB Audio Device                                                           | 4         | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 0.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 0.65%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 0.49%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller         | 3         | 0.49%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.49%   |
| Nvidia Audio device                                                                               | 3         | 0.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.49%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 74        | 20.16%  |
| Samsung Electronics        | 55        | 14.99%  |
| SK hynix                   | 49        | 13.35%  |
| Ramaxel Technology         | 39        | 10.63%  |
| Kingston                   | 35        | 9.54%   |
| Micron Technology          | 26        | 7.08%   |
| Crucial                    | 19        | 5.18%   |
| Corsair                    | 12        | 3.27%   |
| Elpida                     | 7         | 1.91%   |
| Team                       | 4         | 1.09%   |
| A-DATA Technology          | 4         | 1.09%   |
| Unknown                    | 4         | 1.09%   |
| Qimonda                    | 3         | 0.82%   |
| PNY                        | 3         | 0.82%   |
| Nanya Technology           | 3         | 0.82%   |
| Avant                      | 3         | 0.82%   |
| Unknown (ABCD)             | 2         | 0.54%   |
| Unknown (0x07D5)           | 2         | 0.54%   |
| Shenzhen WODPOSIT          | 2         | 0.54%   |
| Memox                      | 2         | 0.54%   |
| Kreton                     | 2         | 0.54%   |
| Unknown (FFFF000000000000) | 1         | 0.27%   |
| Unknown (7F7F7F7F7F7F7F83) | 1         | 0.27%   |
| Unknown (0x0CBA)           | 1         | 0.27%   |
| Unknown (081A)             | 1         | 0.27%   |
| Unknown (07F7)             | 1         | 0.27%   |
| Transcend                  | 1         | 0.27%   |
| Timetec                    | 1         | 0.27%   |
| Super Talent               | 1         | 0.27%   |
| OCZ                        | 1         | 0.27%   |
| Mushkin                    | 1         | 0.27%   |
| Hikvision                  | 1         | 0.27%   |
| Gold Key                   | 1         | 0.27%   |
| ff                         | 1         | 0.27%   |
| Apacer                     | 1         | 0.27%   |
| <Invalid>                  | 1         | 0.27%   |
| 4ea5                       | 1         | 0.27%   |
| 48spaces                   | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                       | 7         | 1.74%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 6         | 1.49%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s | 6         | 1.49%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s | 6         | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR2                        | 5         | 1.24%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s | 5         | 1.24%   |
| Unknown RAM Module 4GB DIMM SDRAM                       | 4         | 0.99%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 4         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 4         | 0.99%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s  | 4         | 0.99%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s   | 4         | 0.99%   |
| Unknown                                                 | 4         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s             | 3         | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2                     | 3         | 0.74%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 3         | 0.74%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s  | 3         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 3         | 0.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s   | 3         | 0.74%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s     | 3         | 0.74%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s | 3         | 0.74%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s   | 3         | 0.74%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s   | 3         | 0.74%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s | 3         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 2         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s               | 2         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2         | 0.5%    |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 2         | 0.5%    |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 2         | 0.5%    |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 2         | 0.5%    |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s             | 2         | 0.5%    |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s    | 2         | 0.5%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 2         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 2         | 0.5%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 116       | 41.13%  |
| DDR4    | 66        | 23.4%   |
| DDR2    | 45        | 15.96%  |
| SDRAM   | 26        | 9.22%   |
| Unknown | 16        | 5.67%   |
| DDR     | 7         | 2.48%   |
| LPDDR4  | 4         | 1.42%   |
| LPDDR3  | 1         | 0.35%   |
| DDR5    | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 135       | 49.09%  |
| DIMM         | 133       | 48.36%  |
| Row Of Chips | 6         | 2.18%   |
| Unknown      | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 106       | 32.62%  |
| 4096  | 98        | 30.15%  |
| 8192  | 69        | 21.23%  |
| 1024  | 28        | 8.62%   |
| 16384 | 19        | 5.85%   |
| 32768 | 3         | 0.92%   |
| 512   | 2         | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 71        | 22.12%  |
| 1333    | 43        | 13.4%   |
| 3200    | 37        | 11.53%  |
| Unknown | 28        | 8.72%   |
| 2667    | 21        | 6.54%   |
| 667     | 19        | 5.92%   |
| 800     | 13        | 4.05%   |
| 2400    | 11        | 3.43%   |
| 533     | 10        | 3.12%   |
| 1066    | 8         | 2.49%   |
| 1334    | 6         | 1.87%   |
| 400     | 6         | 1.87%   |
| 2048    | 5         | 1.56%   |
| 2133    | 4         | 1.25%   |
| 1867    | 4         | 1.25%   |
| 1067    | 4         | 1.25%   |
| 3733    | 3         | 0.93%   |
| 3266    | 3         | 0.93%   |
| 2666    | 3         | 0.93%   |
| 1800    | 3         | 0.93%   |
| 1639    | 3         | 0.93%   |
| 133     | 3         | 0.93%   |
| 4199    | 2         | 0.62%   |
| 3600    | 2         | 0.62%   |
| 975     | 2         | 0.62%   |
| 4800    | 1         | 0.31%   |
| 3800    | 1         | 0.31%   |
| 2933    | 1         | 0.31%   |
| 2000    | 1         | 0.31%   |
| 1648    | 1         | 0.31%   |
| 1024    | 1         | 0.31%   |
| 266     | 1         | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 61.54%  |
| Seiko Epson         | 3         | 23.08%  |
| Samsung Electronics | 2         | 15.38%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 7.69%   |
| Seiko Epson L6160 Series                     | 1         | 7.69%   |
| Seiko Epson L210 Series                      | 1         | 7.69%   |
| Samsung ML-216x Series Laser Printer         | 1         | 7.69%   |
| Samsung ML-1865                              | 1         | 7.69%   |
| HP LaserJet Professional P1102w              | 1         | 7.69%   |
| HP LaserJet P1006                            | 1         | 7.69%   |
| HP LaserJet P1005                            | 1         | 7.69%   |
| HP LaserJet 1018                             | 1         | 7.69%   |
| HP DeskJet F4100 Printer series              | 1         | 7.69%   |
| HP DeskJet 2300 series                       | 1         | 7.69%   |
| HP Deskjet 2050 J510                         | 1         | 7.69%   |
| HP Color LaserJet CP1215                     | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| KYE Systems (Mouse Systems) | 1         | 33.33%  |
| Hewlett-Packard             | 1         | 33.33%  |
| Canon                       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE | 1         | 33.33%  |
| HP Scanjet 200                                      | 1         | 33.33%  |
| Canon CanoScan LiDE 110                             | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 17.89%  |
| Microdia                               | 20        | 10.53%  |
| Bison Electronics                      | 16        | 8.42%   |
| IMC Networks                           | 15        | 7.89%   |
| Realtek Semiconductor                  | 14        | 7.37%   |
| Suyin                                  | 10        | 5.26%   |
| Sunplus Innovation Technology          | 7         | 3.68%   |
| Quanta                                 | 7         | 3.68%   |
| Logitech                               | 7         | 3.68%   |
| Syntek                                 | 5         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.63%   |
| Apple                                  | 5         | 2.63%   |
| Sonix Technology                       | 4         | 2.11%   |
| Microsoft                              | 4         | 2.11%   |
| Acer                                   | 4         | 2.11%   |
| Samsung Electronics                    | 3         | 1.58%   |
| Ricoh                                  | 3         | 1.58%   |
| Luxvisions Innotech Limited            | 3         | 1.58%   |
| Lite-On Technology                     | 3         | 1.58%   |
| ALi                                    | 3         | 1.58%   |
| Importek                               | 2         | 1.05%   |
| Cubeternet                             | 2         | 1.05%   |
| Alcor Micro                            | 2         | 1.05%   |
| Z-Star Microelectronics                | 1         | 0.53%   |
| Tobii Technology AB                    | 1         | 0.53%   |
| Silicon Motion                         | 1         | 0.53%   |
| SiGma Micro                            | 1         | 0.53%   |
| OmniVision Technologies                | 1         | 0.53%   |
| LG Electronics                         | 1         | 0.53%   |
| Lenovo                                 | 1         | 0.53%   |
| KYE Systems (Mouse Systems)            | 1         | 0.53%   |
| KYE Systems                            | 1         | 0.53%   |
| icSpring                               | 1         | 0.53%   |
| Aveo Technology                        | 1         | 0.53%   |
| 04004000_P040200_SN0002                | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 12        | 6.32%   |
| Realtek Integrated_Webcam_HD                                  | 6         | 3.16%   |
| Microdia USB 2.0 Camera                                       | 6         | 3.16%   |
| Bison USB HD Webcam                                           | 5         | 2.63%   |
| Sunplus Integrated_Webcam_HD                                  | 4         | 2.11%   |
| Sonix USB2.0 HD UVC WebCam                                    | 4         | 2.11%   |
| Microdia Integrated_Webcam_HD                                 | 4         | 2.11%   |
| Chicony Lenovo EasyCamera                                     | 4         | 2.11%   |
| Chicony Integrated Camera                                     | 4         | 2.11%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 3         | 1.58%   |
| Logitech Webcam C270                                          | 3         | 1.58%   |
| IMC Networks XHC Camera                                       | 3         | 1.58%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 3         | 1.58%   |
| IMC Networks Integrated Camera                                | 3         | 1.58%   |
| Chicony HD Webcam                                             | 3         | 1.58%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 1.58%   |
| Bison USB Camera                                              | 3         | 1.58%   |
| Bison HD Webcam                                               | 3         | 1.58%   |
| Apple Built-in iSight                                         | 3         | 1.58%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.05%   |
| Suyin HP Webcam 101                                           | 2         | 1.05%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.05%   |
| Realtek USB Camera                                            | 2         | 1.05%   |
| Realtek Integrated Webcam HD                                  | 2         | 1.05%   |
| Quanta ACER HD User Facing                                    | 2         | 1.05%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.05%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.05%   |
| Cubeternet USB2.0 Camera                                      | 2         | 1.05%   |
| Chicony HP Wide Vision HD Camera                              | 2         | 1.05%   |
| Bison BisonCam, NB Pro                                        | 2         | 1.05%   |
| ALi WebCam                                                    | 2         | 1.05%   |
| Z-Star Venus USB2.0 Camera                                    | 1         | 0.53%   |
| Tobii AB EyeChip                                              | 1         | 0.53%   |
| Syntek USB Camera Device                                      | 1         | 0.53%   |
| Syntek USB 2.0 UVC PC Camera                                  | 1         | 0.53%   |
| Syntek Integrated Webcam                                      | 1         | 0.53%   |
| Syntek Integrated Camera                                      | 1         | 0.53%   |
| Syntek EasyCamera                                             | 1         | 0.53%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 0.53%   |
| Suyin Integrated Webcam                                       | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 42.11%  |
| Synaptics                  | 3         | 15.79%  |
| AuthenTec                  | 3         | 15.79%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| Upek                       | 1         | 5.26%   |
| Futronic Technology        | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 15.79%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 10.53%  |
| Validity Sensors Fingerprint scanner                   | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 10.53%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 10.53%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.26%   |
| Synaptics UWP WBDI                                     | 1         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.26%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.26%   |
| AuthenTec AES1600                                      | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 75%     |
| Alcor Micro | 2         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 37.5%   |
| Broadcom 5880                                  | 3         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 338       | 77.17%  |
| 1     | 85        | 19.41%  |
| 2     | 11        | 2.51%   |
| 6     | 1         | 0.23%   |
| 5     | 1         | 0.23%   |
| 4     | 1         | 0.23%   |
| 3     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 42        | 35%     |
| Fingerprint reader       | 19        | 15.83%  |
| Net/wireless             | 11        | 9.17%   |
| Communication controller | 11        | 9.17%   |
| Sound                    | 9         | 7.5%    |
| Chipcard                 | 8         | 6.67%   |
| Multimedia controller    | 6         | 5%      |
| Camera                   | 5         | 4.17%   |
| Network                  | 2         | 1.67%   |
| Video                    | 1         | 0.83%   |
| Storage/ide              | 1         | 0.83%   |
| Storage                  | 1         | 0.83%   |
| Net/ethernet             | 1         | 0.83%   |
| Firewire controller      | 1         | 0.83%   |
| Card reader              | 1         | 0.83%   |
| Bluetooth                | 1         | 0.83%   |

