Linux in UAE - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Linux in UAE.

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

Total: 289

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [47b95e50dc](https://linux-hardware.org/?probe=47b95e50dc) | Jan 02, 2025 |
| HP            | Pavilion Laptop 15-eh3xx... | [2b58ebfebe](https://linux-hardware.org/?probe=2b58ebfebe) | Dec 16, 2024 |
| Valve         | Jupiter                     | [b81aceb033](https://linux-hardware.org/?probe=b81aceb033) | Dec 09, 2024 |
| Dell          | XPS 13 9305                 | [1496432b74](https://linux-hardware.org/?probe=1496432b74) | Dec 04, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | [ed79db6569](https://linux-hardware.org/?probe=ed79db6569) | Nov 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [fa8c5128c6](https://linux-hardware.org/?probe=fa8c5128c6) | Nov 25, 2024 |
| Alienware     | 17 R3                       | [d6363a7652](https://linux-hardware.org/?probe=d6363a7652) | Nov 24, 2024 |
| Valve         | Jupiter                     | [01d5857ef9](https://linux-hardware.org/?probe=01d5857ef9) | Nov 22, 2024 |
| Valve         | Jupiter                     | [228a34d78e](https://linux-hardware.org/?probe=228a34d78e) | Nov 21, 2024 |
| Valve         | Jupiter                     | [fc95853dd8](https://linux-hardware.org/?probe=fc95853dd8) | Nov 19, 2024 |
| HP            | Laptop 15s-eq0xxx           | [364e24bd93](https://linux-hardware.org/?probe=364e24bd93) | Nov 12, 2024 |
| HP            | ProBook 450 G6              | [3d3f18fab8](https://linux-hardware.org/?probe=3d3f18fab8) | Nov 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c36723680e](https://linux-hardware.org/?probe=c36723680e) | Nov 04, 2024 |
| HP            | ProBook 450 G6              | [b6327b1771](https://linux-hardware.org/?probe=b6327b1771) | Oct 27, 2024 |
| Alienware     | x17 R2                      | [ead78bb072](https://linux-hardware.org/?probe=ead78bb072) | Oct 24, 2024 |
| Alienware     | x17 R2                      | [9e6b5acd94](https://linux-hardware.org/?probe=9e6b5acd94) | Oct 22, 2024 |
| Valve         | Jupiter                     | [b40269dd83](https://linux-hardware.org/?probe=b40269dd83) | Oct 22, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [c31e6ce172](https://linux-hardware.org/?probe=c31e6ce172) | Oct 20, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [4d89b5ebcb](https://linux-hardware.org/?probe=4d89b5ebcb) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | [0e2f27c078](https://linux-hardware.org/?probe=0e2f27c078) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | [8253f323a0](https://linux-hardware.org/?probe=8253f323a0) | Oct 07, 2024 |
| HP            | Laptop 15-dy5xxx            | [6273853b03](https://linux-hardware.org/?probe=6273853b03) | Oct 07, 2024 |
| Valve         | Jupiter                     | [98801dba2b](https://linux-hardware.org/?probe=98801dba2b) | Oct 04, 2024 |
| Valve         | Jupiter                     | [f72decd0b9](https://linux-hardware.org/?probe=f72decd0b9) | Oct 02, 2024 |
| Dell          | Latitude E5470              | [77e0c3eadc](https://linux-hardware.org/?probe=77e0c3eadc) | Sep 29, 2024 |
| Apple         | MacBookAir7,2               | [f267e0be7a](https://linux-hardware.org/?probe=f267e0be7a) | Sep 29, 2024 |
| Razer         | Blade 15 Advanced Model ... | [61b7158fe5](https://linux-hardware.org/?probe=61b7158fe5) | Sep 23, 2024 |
| ASUSTek       | X541UJ                      | [cc2936a90c](https://linux-hardware.org/?probe=cc2936a90c) | Sep 22, 2024 |
| Dell          | Latitude E5470              | [b03d8fc762](https://linux-hardware.org/?probe=b03d8fc762) | Sep 15, 2024 |
| Dell          | Latitude E6540              | [1181675540](https://linux-hardware.org/?probe=1181675540) | Sep 14, 2024 |
| MSI           | Creator Z16 A11UE           | [146049daab](https://linux-hardware.org/?probe=146049daab) | Sep 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [381d377e54](https://linux-hardware.org/?probe=381d377e54) | Aug 30, 2024 |
| HP            | ENVY 15                     | [bb6e6b46f0](https://linux-hardware.org/?probe=bb6e6b46f0) | Aug 29, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [c62daa5e9a](https://linux-hardware.org/?probe=c62daa5e9a) | Aug 28, 2024 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | [37adaec870](https://linux-hardware.org/?probe=37adaec870) | Aug 19, 2024 |
| Apple         | MacBookPro14,3              | [9553d16dbc](https://linux-hardware.org/?probe=9553d16dbc) | Aug 18, 2024 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [adbf48a938](https://linux-hardware.org/?probe=adbf48a938) | Aug 14, 2024 |
| Lenovo        | ThinkPad T540p 20BE00AXA... | [c87a2a98f7](https://linux-hardware.org/?probe=c87a2a98f7) | Aug 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [ac95e09d3d](https://linux-hardware.org/?probe=ac95e09d3d) | Aug 13, 2024 |
| Valve         | Jupiter                     | [8908b97b57](https://linux-hardware.org/?probe=8908b97b57) | Aug 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S4KR00    | [124704efaa](https://linux-hardware.org/?probe=124704efaa) | Aug 03, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | [1c41f0d25c](https://linux-hardware.org/?probe=1c41f0d25c) | Jul 28, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | [8c28e82d86](https://linux-hardware.org/?probe=8c28e82d86) | Jul 28, 2024 |
| Apple         | MacBookPro9,2               | [100dfc761e](https://linux-hardware.org/?probe=100dfc761e) | Jul 28, 2024 |
| Lenovo        | ThinkPad T490 20N3SCND00    | [d366cdfef1](https://linux-hardware.org/?probe=d366cdfef1) | Jul 26, 2024 |
| Lenovo        | ThinkPad T490 20N3SCND00    | [5d9ee468e3](https://linux-hardware.org/?probe=5d9ee468e3) | Jul 26, 2024 |
| Apple         | MacBookPro9,2               | [b43115fc35](https://linux-hardware.org/?probe=b43115fc35) | Jul 25, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | [e7b913d07d](https://linux-hardware.org/?probe=e7b913d07d) | Jul 08, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [43eb169014](https://linux-hardware.org/?probe=43eb169014) | Jul 02, 2024 |
| ASUSTek       | ROG Strix G512LW_2nd2LW     | [c29d8bf39f](https://linux-hardware.org/?probe=c29d8bf39f) | Jun 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3595b48d6f](https://linux-hardware.org/?probe=3595b48d6f) | Jun 17, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [9b30ebc629](https://linux-hardware.org/?probe=9b30ebc629) | Jun 15, 2024 |
| Dell          | Latitude E5570              | [aa3048d0b3](https://linux-hardware.org/?probe=aa3048d0b3) | Jun 13, 2024 |
| Dell          | XPS L501X                   | [396ec3b48f](https://linux-hardware.org/?probe=396ec3b48f) | Jun 13, 2024 |
| Dell          | Vostro 3400                 | [2ae5830f06](https://linux-hardware.org/?probe=2ae5830f06) | Jun 05, 2024 |
| Lenovo        | ThinkPad T460 20FMS77B0D    | [48b925a3b1](https://linux-hardware.org/?probe=48b925a3b1) | Jun 02, 2024 |
| Dell          | Latitude E6540              | [64a38f3167](https://linux-hardware.org/?probe=64a38f3167) | Jun 01, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [ceb3eb9275](https://linux-hardware.org/?probe=ceb3eb9275) | May 31, 2024 |
| Dell          | XPS 15 9520                 | [dec3f4b80d](https://linux-hardware.org/?probe=dec3f4b80d) | May 30, 2024 |
| Lenovo        | ThinkPad X240 20AMS39F0E    | [8c697fb84c](https://linux-hardware.org/?probe=8c697fb84c) | May 28, 2024 |
| Dell          | Latitude E6540              | [b74e867eb2](https://linux-hardware.org/?probe=b74e867eb2) | May 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9d438abd6e](https://linux-hardware.org/?probe=9d438abd6e) | May 24, 2024 |
| HP            | ProBook 430 G4              | [986474f731](https://linux-hardware.org/?probe=986474f731) | May 21, 2024 |
| Acer          | Aspire ES1-531              | [3387f387e2](https://linux-hardware.org/?probe=3387f387e2) | May 19, 2024 |
| Acer          | Aspire ES1-531              | [b7158b3151](https://linux-hardware.org/?probe=b7158b3151) | May 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [5ecbd0cbbc](https://linux-hardware.org/?probe=5ecbd0cbbc) | May 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [fac2c941b9](https://linux-hardware.org/?probe=fac2c941b9) | May 17, 2024 |
| MSI           | Alpha 15 A4DEK              | [df01e00ae4](https://linux-hardware.org/?probe=df01e00ae4) | May 17, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [815681c523](https://linux-hardware.org/?probe=815681c523) | May 14, 2024 |
| Dell          | XPS 15 9520                 | [ef8de4b0d9](https://linux-hardware.org/?probe=ef8de4b0d9) | May 09, 2024 |
| HP            | HPPavilionLaptop15-eh0xx... | [2d309668c0](https://linux-hardware.org/?probe=2d309668c0) | May 04, 2024 |
| Dell          | Vostro 3400                 | [ddb98658ed](https://linux-hardware.org/?probe=ddb98658ed) | Apr 15, 2024 |
| Valve         | Jupiter                     | [3f58323ccb](https://linux-hardware.org/?probe=3f58323ccb) | Apr 02, 2024 |
| Lenovo        | ThinkPad T480s 20L8S07A0... | [b136c2a573](https://linux-hardware.org/?probe=b136c2a573) | Mar 26, 2024 |
| Dell          | Inspiron 16 Plus 7620       | [16c311a8b2](https://linux-hardware.org/?probe=16c311a8b2) | Mar 13, 2024 |
| Lenovo        | ThinkPad X240 20AMS39F0E    | [28e62d76d4](https://linux-hardware.org/?probe=28e62d76d4) | Feb 25, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | [19f5064a8e](https://linux-hardware.org/?probe=19f5064a8e) | Feb 24, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | [d6e9ae9de6](https://linux-hardware.org/?probe=d6e9ae9de6) | Feb 24, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [82828b68cb](https://linux-hardware.org/?probe=82828b68cb) | Feb 20, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [813c2cba09](https://linux-hardware.org/?probe=813c2cba09) | Feb 17, 2024 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [84059a6773](https://linux-hardware.org/?probe=84059a6773) | Feb 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [95e1c6903c](https://linux-hardware.org/?probe=95e1c6903c) | Feb 16, 2024 |
| Valve         | Jupiter                     | [4bfb818f2f](https://linux-hardware.org/?probe=4bfb818f2f) | Feb 12, 2024 |
| Lenovo        | ThinkPad E570 20H50067AD    | [a51f602de8](https://linux-hardware.org/?probe=a51f602de8) | Feb 11, 2024 |
| Lenovo        | ThinkPad E570 20H50067AD    | [2752e93d4b](https://linux-hardware.org/?probe=2752e93d4b) | Feb 08, 2024 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [4c292546e2](https://linux-hardware.org/?probe=4c292546e2) | Jan 27, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [3de8476f0b](https://linux-hardware.org/?probe=3de8476f0b) | Jan 21, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [3373e374fb](https://linux-hardware.org/?probe=3373e374fb) | Jan 14, 2024 |
| Dell          | XPS 13 9305                 | [382558433d](https://linux-hardware.org/?probe=382558433d) | Jan 11, 2024 |
| Apple         | MacBookAir5,1               | [26c37b7e05](https://linux-hardware.org/?probe=26c37b7e05) | Jan 02, 2024 |
| Apple         | MacBookAir5,1               | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | [c977bbe2c4](https://linux-hardware.org/?probe=c977bbe2c4) | Dec 03, 2023 |
| Acer          | Nitro AN517-55              | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Apple         | MacBookAir6,1               | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| Apple         | MacBookAir6,1               | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| HP            | Laptop 15-dy1xxx            | [9218c25c70](https://linux-hardware.org/?probe=9218c25c70) | Nov 21, 2023 |
| Acer          | Aspire A315-58              | [9c08dba7b5](https://linux-hardware.org/?probe=9c08dba7b5) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [e7f5173a86](https://linux-hardware.org/?probe=e7f5173a86) | Nov 12, 2023 |
| HP            | Laptop 14-dq2xxx            | [0d5d11180c](https://linux-hardware.org/?probe=0d5d11180c) | Nov 07, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [600445b726](https://linux-hardware.org/?probe=600445b726) | Nov 05, 2023 |
| HP            | HPPavilionLaptop15-eh0xx... | [436064bfba](https://linux-hardware.org/?probe=436064bfba) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | [f4cbcd5ba1](https://linux-hardware.org/?probe=f4cbcd5ba1) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | [34a347877f](https://linux-hardware.org/?probe=34a347877f) | Nov 05, 2023 |
| Gigabyte      | A5 X1                       | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| Lenovo        | ThinkPad E490 20N80006UE    | [4bb8e497d3](https://linux-hardware.org/?probe=4bb8e497d3) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| I-Life Dig... | ZED AIR PRO                 | [7cb30879f6](https://linux-hardware.org/?probe=7cb30879f6) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| Google        | Lick                        | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| HP            | ProBook 450 G2              | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| Dell          | Latitude 3420               | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| Lenovo        | Z50-70 20354                | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| HP            | ProBook 450 G2              | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | [3466d6ab26](https://linux-hardware.org/?probe=3466d6ab26) | Jul 23, 2023 |
| HP            | ProBook 450 G2              | [94df828438](https://linux-hardware.org/?probe=94df828438) | Jul 22, 2023 |
| Dell          | G15 Special Edition 5521    | [42890cd134](https://linux-hardware.org/?probe=42890cd134) | Jul 04, 2023 |
| Dell          | G15 Special Edition 5521    | [8a3a0f9375](https://linux-hardware.org/?probe=8a3a0f9375) | Jul 04, 2023 |
| ASUSTek       | GL553VD                     | [884a5ecd03](https://linux-hardware.org/?probe=884a5ecd03) | Jun 28, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Razer         | Blade 15 Advanced Model ... | [7dd15a9fa4](https://linux-hardware.org/?probe=7dd15a9fa4) | Jun 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Valve         | Jupiter                     | [0c81d929ca](https://linux-hardware.org/?probe=0c81d929ca) | Jun 04, 2023 |
| HP            | Laptop 14-dq2xxx            | [589112cb44](https://linux-hardware.org/?probe=589112cb44) | May 25, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [2ae74516a9](https://linux-hardware.org/?probe=2ae74516a9) | May 24, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [cbd7b1dcc7](https://linux-hardware.org/?probe=cbd7b1dcc7) | May 24, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Toshiba       | Satellite L850-B434         | [54e6cd2fc6](https://linux-hardware.org/?probe=54e6cd2fc6) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| HP            | Laptop 14-dq2xxx            | [0a639ba55d](https://linux-hardware.org/?probe=0a639ba55d) | May 08, 2023 |
| Acer          | Aspire F5-573G              | [aabb19e388](https://linux-hardware.org/?probe=aabb19e388) | May 06, 2023 |
| HP            | Laptop 14-dq2xxx            | [856494ea85](https://linux-hardware.org/?probe=856494ea85) | May 04, 2023 |
| Valve         | Jupiter                     | [c6e5e310b9](https://linux-hardware.org/?probe=c6e5e310b9) | May 02, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [1704454cdb](https://linux-hardware.org/?probe=1704454cdb) | May 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [d2f8737b9d](https://linux-hardware.org/?probe=d2f8737b9d) | May 02, 2023 |
| Valve         | Jupiter                     | [78a3abdc19](https://linux-hardware.org/?probe=78a3abdc19) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6e2da1e766](https://linux-hardware.org/?probe=6e2da1e766) | Apr 21, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | [a0cf4fd00d](https://linux-hardware.org/?probe=a0cf4fd00d) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | [7ce26d7fd9](https://linux-hardware.org/?probe=7ce26d7fd9) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| HP            | 15-dc1018ur                 | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [a7b2caaba8](https://linux-hardware.org/?probe=a7b2caaba8) | Apr 16, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1U20... | [99ea485cee](https://linux-hardware.org/?probe=99ea485cee) | Mar 27, 2023 |
| ASUSTek       | Q551LN                      | [3385f39150](https://linux-hardware.org/?probe=3385f39150) | Mar 26, 2023 |
| HP            | Laptop 14-dq2xxx            | [1a46276700](https://linux-hardware.org/?probe=1a46276700) | Mar 05, 2023 |
| Dell          | XPS 13 7390                 | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Dell          | XPS 13 9370                 | [452bd46c01](https://linux-hardware.org/?probe=452bd46c01) | Feb 22, 2023 |
| Dell          | XPS 13 9370                 | [fe78ef8424](https://linux-hardware.org/?probe=fe78ef8424) | Feb 22, 2023 |
| HP            | Laptop 14-dq2xxx            | [83bef528a7](https://linux-hardware.org/?probe=83bef528a7) | Feb 19, 2023 |
| Lenovo        | G50-80 80E5                 | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| HP            | Laptop 14-dq2xxx            | [54f7f241bf](https://linux-hardware.org/?probe=54f7f241bf) | Feb 15, 2023 |
| HP            | Laptop 14-dq2xxx            | [8fc284c3b5](https://linux-hardware.org/?probe=8fc284c3b5) | Feb 15, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| HP            | Laptop 14-dq2xxx            | [f308688189](https://linux-hardware.org/?probe=f308688189) | Jan 25, 2023 |
| Valve         | Jupiter                     | [83d050bdbe](https://linux-hardware.org/?probe=83d050bdbe) | Jan 25, 2023 |
| HP            | Laptop 14-dq2xxx            | [9a930173a0](https://linux-hardware.org/?probe=9a930173a0) | Jan 24, 2023 |
| Dell          | G5 5587                     | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Acer          | Aspire E5-471P              | [c50e807e64](https://linux-hardware.org/?probe=c50e807e64) | Jan 12, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [6d3966411f](https://linux-hardware.org/?probe=6d3966411f) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [1405e2a7c8](https://linux-hardware.org/?probe=1405e2a7c8) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [6206409322](https://linux-hardware.org/?probe=6206409322) | Jan 08, 2023 |
| HP            | EliteBook 2560p             | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Lenovo        | Legion Y7000P 81LD          | [d27a1b703b](https://linux-hardware.org/?probe=d27a1b703b) | Dec 26, 2022 |
| Valve         | Jupiter                     | [fae62b5114](https://linux-hardware.org/?probe=fae62b5114) | Dec 11, 2022 |
| MSI           | Modern 14 B5M               | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| HP            | EliteBook 840 G1            | [7d3eac2c7d](https://linux-hardware.org/?probe=7d3eac2c7d) | Nov 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | [910b452558](https://linux-hardware.org/?probe=910b452558) | Oct 30, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [7406489511](https://linux-hardware.org/?probe=7406489511) | Oct 21, 2022 |
| HP            | 250 G5 Notebook PC          | [e8e0acd06e](https://linux-hardware.org/?probe=e8e0acd06e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b1590cf8fa](https://linux-hardware.org/?probe=b1590cf8fa) | Oct 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lenovo        | ThinkPad T61 76653JG        | [0fae1da16b](https://linux-hardware.org/?probe=0fae1da16b) | Aug 02, 2022 |
| Lenovo        | 81FV                        | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | [de71ab8780](https://linux-hardware.org/?probe=de71ab8780) | Jul 21, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | [28c774c6de](https://linux-hardware.org/?probe=28c774c6de) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Google        | Terra                       | [54163369b2](https://linux-hardware.org/?probe=54163369b2) | Feb 23, 2022 |
| Dell          | Latitude E6230              | [a8aeb155b0](https://linux-hardware.org/?probe=a8aeb155b0) | Feb 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Dell          | Latitude E5440              | [ebbb8ee138](https://linux-hardware.org/?probe=ebbb8ee138) | Jan 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FV0... | [78080db667](https://linux-hardware.org/?probe=78080db667) | Jan 13, 2022 |
| HP            | EliteBook 840 G6            | [c36553e3a3](https://linux-hardware.org/?probe=c36553e3a3) | Dec 27, 2021 |
| Google        | Akemi                       | [aaf0a3e10e](https://linux-hardware.org/?probe=aaf0a3e10e) | Dec 20, 2021 |
| Dell          | Inspiron 5570               | [927497310e](https://linux-hardware.org/?probe=927497310e) | Nov 16, 2021 |
| win elemen... | MoreFine S500+              | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| MSI           | PS63 Modern 8RD             | [519048dea2](https://linux-hardware.org/?probe=519048dea2) | Nov 01, 2021 |
| MSI           | PS63 Modern 8RD             | [6d3cd2f117](https://linux-hardware.org/?probe=6d3cd2f117) | Nov 01, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| HP            | ProBook 6475b               | [9d60bf5397](https://linux-hardware.org/?probe=9d60bf5397) | Oct 02, 2021 |
| Apple         | MacBook9,1                  | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| Sony          | VGN-NS10J_S                 | [31d1e0e91d](https://linux-hardware.org/?probe=31d1e0e91d) | Aug 12, 2021 |
| LG Electro... | C500-G.AEF5BE1              | [b78f4cd34d](https://linux-hardware.org/?probe=b78f4cd34d) | Jun 14, 2021 |
| Toshiba       | Satellite C850-A966         | [391d22d993](https://linux-hardware.org/?probe=391d22d993) | Jun 02, 2021 |
| Sony          | SVE14A25CAB                 | [78ddb916b5](https://linux-hardware.org/?probe=78ddb916b5) | May 30, 2021 |
| Sony          | SVE14A25CAB                 | [0a2c5cf1cd](https://linux-hardware.org/?probe=0a2c5cf1cd) | May 30, 2021 |
| HP            | Laptop 15s-eq2xxx           | [5707e7ae37](https://linux-hardware.org/?probe=5707e7ae37) | May 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [66cc8bd4a5](https://linux-hardware.org/?probe=66cc8bd4a5) | May 19, 2021 |
| Dell          | G5 5587                     | [2d2cf67a2d](https://linux-hardware.org/?probe=2d2cf67a2d) | May 08, 2021 |
| Dell          | Latitude E6510              | [06d38294ab](https://linux-hardware.org/?probe=06d38294ab) | May 03, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| Acer          | Aspire 5755G                | [6b82d5c050](https://linux-hardware.org/?probe=6b82d5c050) | Mar 07, 2021 |
| Acer          | Aspire 5755G                | [227244211b](https://linux-hardware.org/?probe=227244211b) | Mar 07, 2021 |
| HP            | Pavilion Notebook           | [3c9d39abce](https://linux-hardware.org/?probe=3c9d39abce) | Mar 06, 2021 |
| Lenovo        | ThinkPad X230 2325DV8       | [11d5145d10](https://linux-hardware.org/?probe=11d5145d10) | Feb 12, 2021 |
| HP            | Pavilion dv6                | [317b81878c](https://linux-hardware.org/?probe=317b81878c) | Jan 27, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [3d8ea2b061](https://linux-hardware.org/?probe=3d8ea2b061) | Jan 27, 2021 |
| HP            | Laptop 15-da1xxx            | [a3c15a6f74](https://linux-hardware.org/?probe=a3c15a6f74) | Jan 18, 2021 |
| HP            | Laptop 15-da1xxx            | [58bf01b1e7](https://linux-hardware.org/?probe=58bf01b1e7) | Jan 18, 2021 |
| Dell          | Inspiron 3521               | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [6a02570e23](https://linux-hardware.org/?probe=6a02570e23) | Jan 03, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [092666f171](https://linux-hardware.org/?probe=092666f171) | Dec 31, 2020 |
| HP            | EliteBook 8460p             | [d24a3c768e](https://linux-hardware.org/?probe=d24a3c768e) | Dec 24, 2020 |
| Dell          | Latitude E6410              | [a2a46d21e9](https://linux-hardware.org/?probe=a2a46d21e9) | Dec 15, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [e2816ed19c](https://linux-hardware.org/?probe=e2816ed19c) | Nov 27, 2020 |
| HP            | Laptop 15-dw1xxx            | [91e0e6c6bc](https://linux-hardware.org/?probe=91e0e6c6bc) | Nov 04, 2020 |
| HP            | Pavilion Power Laptop 15... | [b1cd303933](https://linux-hardware.org/?probe=b1cd303933) | Oct 08, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [f9f212a509](https://linux-hardware.org/?probe=f9f212a509) | Oct 01, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| Acer          | ChiefRiver Platform         | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |
| Dell          | Inspiron 5537               | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| Dell          | Latitude E6540              | [9abf14d168](https://linux-hardware.org/?probe=9abf14d168) | Aug 31, 2020 |
| Dell          | Precision 5540              | [76f1cfa736](https://linux-hardware.org/?probe=76f1cfa736) | Aug 23, 2020 |
| I-Life Dig... | ZED AIR                     | [b40d7e9c7c](https://linux-hardware.org/?probe=b40d7e9c7c) | Aug 10, 2020 |
| I-Life Dig... | ZED AIR                     | [5662aa186c](https://linux-hardware.org/?probe=5662aa186c) | Aug 10, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | [81d46e4c4a](https://linux-hardware.org/?probe=81d46e4c4a) | Aug 02, 2020 |
| Toshiba       | Satellite C660              | [670cc8a66c](https://linux-hardware.org/?probe=670cc8a66c) | Jul 26, 2020 |
| Lenovo        | IdeaPadFlex 14 20308        | [aea3470496](https://linux-hardware.org/?probe=aea3470496) | Jul 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [b3dbd3f2af](https://linux-hardware.org/?probe=b3dbd3f2af) | Jul 14, 2020 |
| Toshiba       | TECRA A50-C                 | [adf7a73571](https://linux-hardware.org/?probe=adf7a73571) | Jul 03, 2020 |
| ASUSTek       | FX503VD                     | [d6c0a21749](https://linux-hardware.org/?probe=d6c0a21749) | Jul 02, 2020 |
| HP            | Pavilion 15                 | [499f0c72ee](https://linux-hardware.org/?probe=499f0c72ee) | Jun 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [dd5c9e8d9f](https://linux-hardware.org/?probe=dd5c9e8d9f) | Jun 23, 2020 |
| Dell          | Latitude E6410              | [06055ff260](https://linux-hardware.org/?probe=06055ff260) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [b53cc32ed0](https://linux-hardware.org/?probe=b53cc32ed0) | Jun 19, 2020 |
| Lenovo        | G500 20236                  | [fdc9496e84](https://linux-hardware.org/?probe=fdc9496e84) | Jun 19, 2020 |
| Dell          | Latitude E6410              | [1b73d74e65](https://linux-hardware.org/?probe=1b73d74e65) | Jun 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | [e9b38b78d7](https://linux-hardware.org/?probe=e9b38b78d7) | May 30, 2020 |
| HP            | Presario C300 (RH208UA#A... | [50e95ff237](https://linux-hardware.org/?probe=50e95ff237) | May 14, 2020 |
| HP            | Presario C300 (RH208UA#A... | [6b4a8eab4c](https://linux-hardware.org/?probe=6b4a8eab4c) | May 14, 2020 |
| Toshiba       | TECRA X40-D                 | [3255796d07](https://linux-hardware.org/?probe=3255796d07) | May 10, 2020 |
| YJKC          | vBOOK Plus RVP7             | [49363e9553](https://linux-hardware.org/?probe=49363e9553) | May 07, 2020 |
| HP            | ProBook 450 G2              | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS6GB00    | [3fa804be21](https://linux-hardware.org/?probe=3fa804be21) | May 01, 2020 |
| YJKC          | vBOOK Plus RVP7             | [d2328783da](https://linux-hardware.org/?probe=d2328783da) | Apr 24, 2020 |
| Dell          | Vostro 14-5480              | [1bba68101c](https://linux-hardware.org/?probe=1bba68101c) | Apr 20, 2020 |
| HP            | ProBook 450 G2              | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | Notebook                    | [4f154f82b0](https://linux-hardware.org/?probe=4f154f82b0) | Apr 01, 2020 |
| HP            | Pavilion Notebook           | [5cd86dffe9](https://linux-hardware.org/?probe=5cd86dffe9) | Mar 16, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [7f0b4db18a](https://linux-hardware.org/?probe=7f0b4db18a) | Mar 12, 2020 |
| HP            | Pavilion Notebook           | [87df29714d](https://linux-hardware.org/?probe=87df29714d) | Mar 11, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [04da794ff5](https://linux-hardware.org/?probe=04da794ff5) | Feb 25, 2020 |
| HP            | EliteBook 2760p             | [40333472c7](https://linux-hardware.org/?probe=40333472c7) | Feb 21, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [b12186f161](https://linux-hardware.org/?probe=b12186f161) | Feb 13, 2020 |
| HP            | Notebook                    | [a25a67e533](https://linux-hardware.org/?probe=a25a67e533) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | [c2a7159d3a](https://linux-hardware.org/?probe=c2a7159d3a) | Jan 04, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | [028d728043](https://linux-hardware.org/?probe=028d728043) | Jan 04, 2020 |
| Lenovo        | Yoga S730-13IWL 81J0        | [d1ca80edff](https://linux-hardware.org/?probe=d1ca80edff) | Dec 24, 2019 |
| Toshiba       | Satellite A300              | [420c738977](https://linux-hardware.org/?probe=420c738977) | Oct 15, 2019 |
| Toshiba       | Satellite A300              | [036dc7e829](https://linux-hardware.org/?probe=036dc7e829) | Oct 15, 2019 |
| Lenovo        | Yoga 2 Pro 20266            | [ab1c14d729](https://linux-hardware.org/?probe=ab1c14d729) | Oct 12, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [558c01fdce](https://linux-hardware.org/?probe=558c01fdce) | Oct 07, 2019 |
| Notebook      | P95_96_97Ex,Rx              | [d4ad7906b5](https://linux-hardware.org/?probe=d4ad7906b5) | Sep 11, 2019 |
| I-Life Dig... | ZED AIR                     | [514c494f7f](https://linux-hardware.org/?probe=514c494f7f) | Jul 23, 2019 |
| I-Life Dig... | ZED AIR                     | [a9fe92aa3c](https://linux-hardware.org/?probe=a9fe92aa3c) | Jul 23, 2019 |
| HP            | EliteBook 8440p             | [1f8a20b199](https://linux-hardware.org/?probe=1f8a20b199) | May 25, 2019 |
| HP            | EliteBook 8440p             | [60d0e8dd5d](https://linux-hardware.org/?probe=60d0e8dd5d) | May 25, 2019 |
| HP            | ProBook 4540s               | [271be85705](https://linux-hardware.org/?probe=271be85705) | May 15, 2019 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [ab25f83cd0](https://linux-hardware.org/?probe=ab25f83cd0) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 25        | 11.57%  |
| Ubuntu 22.04                 | 16        | 7.41%   |
| Ubuntu 18.04                 | 10        | 4.63%   |
| Pop!_OS 22.04                | 10        | 4.63%   |
| Arch Rolling                 | 9         | 4.17%   |
| Debian 12                    | 8         | 3.7%    |
| Ubuntu 24.04                 | 7         | 3.24%   |
| Fedora 40                    | 6         | 2.78%   |
| ArcoLinux Rolling            | 6         | 2.78%   |
| Arch                         | 5         | 2.31%   |
| Fedora 38                    | 4         | 1.85%   |
| Zorin 15                     | 3         | 1.39%   |
| Ubuntu 20.10                 | 3         | 1.39%   |
| Ubuntu 19.10                 | 3         | 1.39%   |
| SteamOS 3.6.20               | 3         | 1.39%   |
| Linux Mint 21.3              | 3         | 1.39%   |
| Kubuntu 22.04                | 3         | 1.39%   |
| KDE neon 22.04               | 3         | 1.39%   |
| Fedora 37                    | 3         | 1.39%   |
| Fedora 36                    | 3         | 1.39%   |
| Debian 11                    | 3         | 1.39%   |
| Ubuntu 23.04                 | 2         | 0.93%   |
| Ubuntu 22.10                 | 2         | 0.93%   |
| Ubuntu 21.10                 | 2         | 0.93%   |
| Ubuntu 16.04                 | 2         | 0.93%   |
| SteamOS 3.5.19               | 2         | 0.93%   |
| SteamOS 3.4.6                | 2         | 0.93%   |
| Parrot 6.0                   | 2         | 0.93%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.93%   |
| OpenMandriva 23.08           | 2         | 0.93%   |
| Lubuntu 22.04                | 2         | 0.93%   |
| Linux Mint 22                | 2         | 0.93%   |
| Linux Mint 20.3              | 2         | 0.93%   |
| Kubuntu 24.04                | 2         | 0.93%   |
| KDE neon 20.04               | 2         | 0.93%   |
| Kali 2023.4                  | 2         | 0.93%   |
| Kali 2023.1                  | 2         | 0.93%   |
| Fedora 41                    | 2         | 0.93%   |
| Fedora 39                    | 2         | 0.93%   |
| BlackPanther 18.1            | 2         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 72        | 34.29%  |
| Fedora       | 20        | 9.52%   |
| Arch         | 14        | 6.67%   |
| Pop!_OS      | 13        | 6.19%   |
| Debian       | 12        | 5.71%   |
| Linux Mint   | 11        | 5.24%   |
| SteamOS      | 10        | 4.76%   |
| OpenMandriva | 7         | 3.33%   |
| Kubuntu      | 6         | 2.86%   |
| ArcoLinux    | 6         | 2.86%   |
| KDE neon     | 5         | 2.38%   |
| Kali         | 5         | 2.38%   |
| Zorin        | 3         | 1.43%   |
| Parrot       | 3         | 1.43%   |
| Manjaro      | 3         | 1.43%   |
| openSUSE     | 2         | 0.95%   |
| Lubuntu      | 2         | 0.95%   |
| BlackPanther | 2         | 0.95%   |
| Xubuntu      | 1         | 0.48%   |
| Ubuntu Unity | 1         | 0.48%   |
| Sparky       | 1         | 0.48%   |
| ROSA         | 1         | 0.48%   |
| Rocky Linux  | 1         | 0.48%   |
| Nobara       | 1         | 0.48%   |
| NixOS        | 1         | 0.48%   |
| GNOME OS     | 1         | 0.48%   |
| Gentoo       | 1         | 0.48%   |
| Feren OS     | 1         | 0.48%   |
| Endless      | 1         | 0.48%   |
| Elementary   | 1         | 0.48%   |
| CachyOS      | 1         | 0.48%   |
| Alpine       | 1         | 0.48%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| 5.4.0-42-generic                         | 5         | 2.21%   |
| 5.4.0-58-generic                         | 4         | 1.77%   |
| 5.13.0-valve36-1-neptune                 | 4         | 1.77%   |
| 6.9.3-76060903-generic                   | 3         | 1.33%   |
| 6.8.5-301.fc40.x86_64                    | 3         | 1.33%   |
| 6.8.0-40-generic                         | 3         | 1.33%   |
| 6.5.0-valve22-1-neptune-65-g9a338ed8a75e | 3         | 1.33%   |
| 6.1.52-valve16-1-neptune-61              | 3         | 1.33%   |
| 5.4.0-26-generic                         | 3         | 1.33%   |
| 6.8.0-35-generic                         | 2         | 0.88%   |
| 6.8.0-31-generic                         | 2         | 0.88%   |
| 6.5.0-kali3-amd64                        | 2         | 0.88%   |
| 6.5.0-35-generic                         | 2         | 0.88%   |
| 6.4.8-desktop-2omv2390                   | 2         | 0.88%   |
| 6.4.7-200.fc38.x86_64                    | 2         | 0.88%   |
| 6.2.0-33-generic                         | 2         | 0.88%   |
| 6.2.0-26-generic                         | 2         | 0.88%   |
| 6.11.8-300.fc41.x86_64                   | 2         | 0.88%   |
| 6.1.0-kali5-amd64                        | 2         | 0.88%   |
| 6.1.0-21-amd64                           | 2         | 0.88%   |
| 6.1.0-18-amd64                           | 2         | 0.88%   |
| 6.1.0-13-amd64                           | 2         | 0.88%   |
| 5.4.0-33-generic                         | 2         | 0.88%   |
| 5.4.0-29-generic                         | 2         | 0.88%   |
| 5.3.0-40-generic                         | 2         | 0.88%   |
| 5.3.0-29-generic                         | 2         | 0.88%   |
| 5.19.0-42-generic                        | 2         | 0.88%   |
| 5.19.0-40-generic                        | 2         | 0.88%   |
| 4.15.0-50-generic                        | 2         | 0.88%   |
| 6.9.9-200.fc40.x86_64                    | 1         | 0.44%   |
| 6.9.3-arch1-1                            | 1         | 0.44%   |
| 6.9.1-1-default                          | 1         | 0.44%   |
| 6.8.9-300.fc40.x86_64                    | 1         | 0.44%   |
| 6.8.7-200.fsync.fc39.x86_64              | 1         | 0.44%   |
| 6.8.5-zen1-1-zen                         | 1         | 0.44%   |
| 6.8.11-amd64                             | 1         | 0.44%   |
| 6.8.1-arch1-1                            | 1         | 0.44%   |
| 6.8.0-76060800daily20240311-generic      | 1         | 0.44%   |
| 6.8.0-51-generic                         | 1         | 0.44%   |
| 6.8.0-50-generic                         | 1         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 27        | 12.27%  |
| 6.8.0   | 12        | 5.45%   |
| 6.5.0   | 12        | 5.45%   |
| 6.1.0   | 11        | 5%      |
| 5.19.0  | 11        | 5%      |
| 5.15.0  | 11        | 5%      |
| 4.15.0  | 9         | 4.09%   |
| 6.2.0   | 7         | 3.18%   |
| 5.8.0   | 7         | 3.18%   |
| 5.13.0  | 7         | 3.18%   |
| 5.3.0   | 5         | 2.27%   |
| 5.11.0  | 5         | 2.27%   |
| 5.10.0  | 5         | 2.27%   |
| 6.9.3   | 4         | 1.82%   |
| 6.8.5   | 4         | 1.82%   |
| 6.1.52  | 4         | 1.82%   |
| 6.4.8   | 3         | 1.36%   |
| 6.7.4   | 2         | 0.91%   |
| 6.5.6   | 2         | 0.91%   |
| 6.4.7   | 2         | 0.91%   |
| 6.11.8  | 2         | 0.91%   |
| 6.11.0  | 2         | 0.91%   |
| 6.10.6  | 2         | 0.91%   |
| 5.14.0  | 2         | 0.91%   |
| 5.0.0   | 2         | 0.91%   |
| 6.9.9   | 1         | 0.45%   |
| 6.9.1   | 1         | 0.45%   |
| 6.8.9   | 1         | 0.45%   |
| 6.8.7   | 1         | 0.45%   |
| 6.8.11  | 1         | 0.45%   |
| 6.8.1   | 1         | 0.45%   |
| 6.7.9   | 1         | 0.45%   |
| 6.7.5   | 1         | 0.45%   |
| 6.6.8   | 1         | 0.45%   |
| 6.6.54  | 1         | 0.45%   |
| 6.6.2   | 1         | 0.45%   |
| 6.6.10  | 1         | 0.45%   |
| 6.6.1   | 1         | 0.45%   |
| 6.5.9   | 1         | 0.45%   |
| 6.5.5   | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 29        | 13.24%  |
| 6.8     | 20        | 9.13%   |
| 6.1     | 20        | 9.13%   |
| 6.5     | 16        | 7.31%   |
| 5.15    | 14        | 6.39%   |
| 5.19    | 13        | 5.94%   |
| 6.2     | 10        | 4.57%   |
| 4.15    | 9         | 4.11%   |
| 5.8     | 8         | 3.65%   |
| 6.11    | 7         | 3.2%    |
| 5.13    | 7         | 3.2%    |
| 5.10    | 7         | 3.2%    |
| 6.9     | 6         | 2.74%   |
| 6.4     | 6         | 2.74%   |
| 6.6     | 5         | 2.28%   |
| 5.3     | 5         | 2.28%   |
| 5.11    | 5         | 2.28%   |
| 6.7     | 4         | 1.83%   |
| 6.10    | 4         | 1.83%   |
| 5.16    | 4         | 1.83%   |
| 6.3     | 2         | 0.91%   |
| 6.0     | 2         | 0.91%   |
| 5.7     | 2         | 0.91%   |
| 5.6     | 2         | 0.91%   |
| 5.18    | 2         | 0.91%   |
| 5.14    | 2         | 0.91%   |
| 5.0     | 2         | 0.91%   |
| 4.18    | 2         | 0.91%   |
| 5.9     | 1         | 0.46%   |
| 5.17    | 1         | 0.46%   |
| 4.4     | 1         | 0.46%   |
| 4.19    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 200       | 99.5%   |
| i686   | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 112       | 52.83%  |
| KDE5       | 37        | 17.45%  |
| Unknown    | 14        | 6.6%    |
| XFCE       | 11        | 5.19%   |
| X-Cinnamon | 10        | 4.72%   |
| KDE6       | 10        | 4.72%   |
| MATE       | 5         | 2.36%   |
| KDE        | 4         | 1.89%   |
| LXQt       | 2         | 0.94%   |
| Unity      | 1         | 0.47%   |
| Pantheon   | 1         | 0.47%   |
| Hyprland   | 1         | 0.47%   |
| gamescope  | 1         | 0.47%   |
| DWM        | 1         | 0.47%   |
| Cinnamon   | 1         | 0.47%   |
| awesome    | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 132       | 63.46%  |
| Wayland | 68        | 32.69%  |
| Unknown | 8         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 104       | 49.52%  |
| GDM3    | 32        | 15.24%  |
| SDDM    | 28        | 13.33%  |
| GDM     | 25        | 11.9%   |
| LightDM | 19        | 9.05%   |
| TDM     | 2         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 162       | 79.02%  |
| Unknown | 14        | 6.83%   |
| en_GB   | 12        | 5.85%   |
| C       | 6         | 2.93%   |
| ru_RU   | 3         | 1.46%   |
| en_IN   | 2         | 0.98%   |
| en_AU   | 2         | 0.98%   |
| pl_PL   | 1         | 0.49%   |
| hu_HU   | 1         | 0.49%   |
| el_GR   | 1         | 0.49%   |
| de_DE   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 112       | 53.85%  |
| BIOS | 96        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 143       | 69.42%  |
| Btrfs   | 38        | 18.45%  |
| Tmpfs   | 10        | 4.85%   |
| Overlay | 10        | 4.85%   |
| Xfs     | 4         | 1.94%   |
| F2fs    | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 103       | 49.76%  |
| GPT     | 97        | 46.86%  |
| MBR     | 7         | 3.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 92.61%  |
| Yes       | 15        | 7.39%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 133       | 65.2%   |
| Yes       | 71        | 34.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 59        | 29.35%  |
| Hewlett-Packard             | 42        | 20.9%   |
| Dell                        | 25        | 12.44%  |
| ASUSTek Computer            | 19        | 9.45%   |
| Valve                       | 10        | 4.98%   |
| Toshiba                     | 8         | 3.98%   |
| Acer                        | 7         | 3.48%   |
| Apple                       | 6         | 2.99%   |
| MSI                         | 4         | 1.99%   |
| Notebook                    | 3         | 1.49%   |
| Google                      | 3         | 1.49%   |
| Sony                        | 2         | 1%      |
| Razer                       | 2         | 1%      |
| I-Life Digital Technologies | 2         | 1%      |
| HUAWEI                      | 2         | 1%      |
| Alienware                   | 2         | 1%      |
| YJKC                        | 1         | 0.5%    |
| win element                 | 1         | 0.5%    |
| LG Electronics              | 1         | 0.5%    |
| Gigabyte Technology         | 1         | 0.5%    |
| A-DATA Technology           | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 10        | 4.98%   |
| ASUS VivoBook_ASUSLaptop X1404VA_X1404VA              | 3         | 1.49%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 2         | 1%      |
| HP ProBook 450 G2                                     | 2         | 1%      |
| HP Pavilion Notebook                                  | 2         | 1%      |
| HP Pavilion 15                                        | 2         | 1%      |
| HP ENVY Laptop 13-aq0xxx                              | 2         | 1%      |
| Dell Latitude E6540                                   | 2         | 1%      |
| Dell G5 5587                                          | 2         | 1%      |
| YJKC vBOOK Plus                                       | 1         | 0.5%    |
| win element MoreFine S500+                            | 1         | 0.5%    |
| Toshiba TECRA X40-D                                   | 1         | 0.5%    |
| Toshiba TECRA A50-C                                   | 1         | 0.5%    |
| Toshiba Satellite L850-B434                           | 1         | 0.5%    |
| Toshiba Satellite L750                                | 1         | 0.5%    |
| Toshiba Satellite C850-A966                           | 1         | 0.5%    |
| Toshiba Satellite C660                                | 1         | 0.5%    |
| Toshiba Satellite A300                                | 1         | 0.5%    |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.5%    |
| Sony VGN-NS10J_S                                      | 1         | 0.5%    |
| Sony SVE14A25CAB                                      | 1         | 0.5%    |
| Notebook PD5x_7xPNP_PNN_PNT                           | 1         | 0.5%    |
| Notebook P95_96_97Ex,Rx                               | 1         | 0.5%    |
| Notebook NV4XMB,ME,MZ                                 | 1         | 0.5%    |
| MSI PS63 Modern 8RD                                   | 1         | 0.5%    |
| MSI Modern 14 B5M                                     | 1         | 0.5%    |
| MSI Creator Z16 A11UE                                 | 1         | 0.5%    |
| MSI Alpha 15 A4DEK                                    | 1         | 0.5%    |
| LG C500-G.AEF5BE1                                     | 1         | 0.5%    |
| Lenovo Z50-70 20354                                   | 1         | 0.5%    |
| Lenovo Yoga S730-13IWL 81J0                           | 1         | 0.5%    |
| Lenovo Yoga Creator 7 15IMH05 82DS                    | 1         | 0.5%    |
| Lenovo Yoga 2 Pro 20266                               | 1         | 0.5%    |
| Lenovo ThinkPad X240 20AMS6GB00                       | 1         | 0.5%    |
| Lenovo ThinkPad X240 20AMS39F0E                       | 1         | 0.5%    |
| Lenovo ThinkPad X230 2325DV8                          | 1         | 0.5%    |
| Lenovo ThinkPad X13 Gen 1 20T2003TUK                  | 1         | 0.5%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS           | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A9US            | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW           | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 35        | 17.41%  |
| Lenovo IdeaPad       | 11        | 5.47%   |
| HP Pavilion          | 11        | 5.47%   |
| Valve Jupiter        | 10        | 4.98%   |
| HP Laptop            | 9         | 4.48%   |
| Dell Latitude        | 9         | 4.48%   |
| HP EliteBook         | 7         | 3.48%   |
| HP ProBook           | 6         | 2.99%   |
| Dell XPS             | 6         | 2.99%   |
| ASUS VivoBook        | 6         | 2.99%   |
| Toshiba Satellite    | 5         | 2.49%   |
| Acer Aspire          | 5         | 2.49%   |
| Lenovo Legion        | 4         | 1.99%   |
| Dell Inspiron        | 4         | 1.99%   |
| Lenovo Yoga          | 3         | 1.49%   |
| HP ENVY              | 3         | 1.49%   |
| ASUS ROG             | 3         | 1.49%   |
| ASUS ASUS            | 3         | 1.49%   |
| Toshiba TECRA        | 2         | 1%      |
| Razer Blade          | 2         | 1%      |
| I-Life Digital ZED   | 2         | 1%      |
| Dell Vostro          | 2         | 1%      |
| Dell G5              | 2         | 1%      |
| ASUS Zenbook         | 2         | 1%      |
| YJKC vBOOK           | 1         | 0.5%    |
| win element MoreFine | 1         | 0.5%    |
| Toshiba PORTEGE      | 1         | 0.5%    |
| Sony VGN-NS10J       | 1         | 0.5%    |
| Sony SVE14A25CAB     | 1         | 0.5%    |
| Notebook PD5x        | 1         | 0.5%    |
| Notebook P95         | 1         | 0.5%    |
| Notebook NV4XMB      | 1         | 0.5%    |
| MSI PS63             | 1         | 0.5%    |
| MSI Modern           | 1         | 0.5%    |
| MSI Creator          | 1         | 0.5%    |
| MSI Alpha            | 1         | 0.5%    |
| LG C500-G.AEF5BE1    | 1         | 0.5%    |
| Lenovo Z50-70        | 1         | 0.5%    |
| Lenovo ThinkBook     | 1         | 0.5%    |
| Lenovo IdeaPadFlex   | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 28        | 13.93%  |
| 2020 | 19        | 9.45%   |
| 2018 | 19        | 9.45%   |
| 2013 | 18        | 8.96%   |
| 2022 | 17        | 8.46%   |
| 2019 | 17        | 8.46%   |
| 2016 | 15        | 7.46%   |
| 2023 | 13        | 6.47%   |
| 2017 | 10        | 4.98%   |
| 2012 | 9         | 4.48%   |
| 2014 | 8         | 3.98%   |
| 2010 | 8         | 3.98%   |
| 2015 | 5         | 2.49%   |
| 2011 | 5         | 2.49%   |
| 2008 | 4         | 1.99%   |
| 2024 | 3         | 1.49%   |
| 2007 | 3         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 201       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 183       | 89.71%  |
| Enabled  | 21        | 10.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 198       | 98.51%  |
| Yes  | 3         | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 56        | 27.72%  |
| 4.01-8.0    | 45        | 22.28%  |
| 16.01-24.0  | 40        | 19.8%   |
| 3.01-4.0    | 23        | 11.39%  |
| 32.01-64.0  | 22        | 10.89%  |
| 64.01-256.0 | 7         | 3.47%   |
| 24.01-32.0  | 3         | 1.49%   |
| 1.01-2.0    | 3         | 1.49%   |
| 2.01-3.0    | 2         | 0.99%   |
| 0.51-1.0    | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 56        | 25.57%  |
| 2.01-3.0   | 55        | 25.11%  |
| 1.01-2.0   | 48        | 21.92%  |
| 3.01-4.0   | 45        | 20.55%  |
| 8.01-16.0  | 8         | 3.65%   |
| 0.51-1.0   | 5         | 2.28%   |
| 16.01-24.0 | 1         | 0.46%   |
| 0.01-0.5   | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 150       | 73.89%  |
| 2      | 43        | 21.18%  |
| 3      | 6         | 2.96%   |
| 4      | 2         | 0.99%   |
| 0      | 2         | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 77.61%  |
| Yes       | 45        | 22.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 68.63%  |
| No        | 64        | 31.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 98.51%  |
| No        | 3         | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 86.63%  |
| No        | 27        | 13.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UAE     | 201       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Dubai            | 109       | 52.91%  |
| Abu Dhabi        | 50        | 24.27%  |
| Sharjah          | 24        | 11.65%  |
| Ajman            | 10        | 4.85%   |
| Al Ain City      | 9         | 4.37%   |
| Al Fujairah City | 2         | 0.97%   |
| Ras al-Khaimah   | 1         | 0.49%   |
| Al Halah         | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 42        | 45     | 16.6%   |
| WDC                            | 28        | 30     | 11.07%  |
| Seagate                        | 19        | 23     | 7.51%   |
| Unknown                        | 17        | 26     | 6.72%   |
| Toshiba                        | 17        | 17     | 6.72%   |
| SanDisk                        | 14        | 16     | 5.53%   |
| Intel                          | 12        | 15     | 4.74%   |
| Crucial                        | 12        | 12     | 4.74%   |
| SK hynix                       | 11        | 15     | 4.35%   |
| Micron Technology              | 11        | 12     | 4.35%   |
| HGST                           | 11        | 14     | 4.35%   |
| Phison Electronics             | 5         | 5      | 1.98%   |
| Kingston                       | 5         | 5      | 1.98%   |
| Micron/Crucial Technology      | 4         | 5      | 1.58%   |
| Kingston Technology Company    | 4         | 4      | 1.58%   |
| Apple                          | 4         | 5      | 1.58%   |
| Team                           | 3         | 3      | 1.19%   |
| Silicon Motion                 | 3         | 3      | 1.19%   |
| Hitachi                        | 3         | 3      | 1.19%   |
| Realtek Semiconductor          | 2         | 2      | 0.79%   |
| KIOXIA                         | 2         | 6      | 0.79%   |
| JMicron Technology             | 2         | 2      | 0.79%   |
| External                       | 2         | 2      | 0.79%   |
| ASMT                           | 2         | 3      | 0.79%   |
| ADATA Technology               | 2         | 2      | 0.79%   |
| Unknown                        | 2         | 2      | 0.79%   |
| Transcend                      | 1         | 1      | 0.4%    |
| Solid State Storage Technology | 1         | 1      | 0.4%    |
| Phison                         | 1         | 1      | 0.4%    |
| Patriot                        | 1         | 1      | 0.4%    |
| O2 Micro                       | 1         | 2      | 0.4%    |
| Lite-On                        | 1         | 1      | 0.4%    |
| Lexar                          | 1         | 1      | 0.4%    |
| LaCie                          | 1         | 1      | 0.4%    |
| KingSpec                       | 1         | 2      | 0.4%    |
| HXY                            | 1         | 1      | 0.4%    |
| Fujitsu                        | 1         | 1      | 0.4%    |
| Corsair                        | 1         | 1      | 0.4%    |
| China                          | 1         | 1      | 0.4%    |
| A-DATA Technology              | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                              | 6         | 2.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 5         | 1.91%   |
| WDC WD10SPZX-08Z10 1TB                                | 4         | 1.53%   |
| Seagate ST1000LM035-1RK172 1TB                        | 4         | 1.53%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 3         | 1.15%   |
| Unknown MMC Card  64GB                                | 3         | 1.15%   |
| Unknown MMC Card  512GB                               | 3         | 1.15%   |
| Unknown MMC Card  32GB                                | 3         | 1.15%   |
| Toshiba MQ01ABD075 752GB                              | 3         | 1.15%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 3         | 1.15%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 3         | 1.15%   |
| Intel NVMe SSD Drive 512GB                            | 3         | 1.15%   |
| HGST HTS725050A7E630 500GB                            | 3         | 1.15%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                    | 2         | 0.76%   |
| Unknown MMC Card  256GB                               | 2         | 0.76%   |
| Unknown MMC Card  16GB                                | 2         | 0.76%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 2         | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.76%   |
| Seagate ST500LT012-9WS142 500GB                       | 2         | 0.76%   |
| Seagate ST500LT012-1DG142 500GB                       | 2         | 0.76%   |
| Seagate ST500LM000-1EJ162 500GB                       | 2         | 0.76%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                    | 2         | 0.76%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 2         | 0.76%   |
| Samsung NVMe SSD Drive 256GB                          | 2         | 0.76%   |
| Samsung MZVLQ512HALU-000H1 512GB                      | 2         | 0.76%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 2         | 0.76%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 2         | 0.76%   |
| Micron MTFDHBA512QFD 512GB                            | 2         | 0.76%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 2         | 0.76%   |
| Intel SSD 660P Series 1024GB                          | 2         | 0.76%   |
| External USB3.0 1TB                                   | 2         | 0.76%   |
| Crucial CT2000P5PSSD8 2TB                             | 2         | 0.76%   |
| Crucial CT1000BX500SSD1 1TB                           | 2         | 0.76%   |
| Unknown                                               | 2         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1         | 0.38%   |
| WDC WDS250G2B0A 250GB SSD                             | 1         | 0.38%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                      | 1         | 0.38%   |
| WDC WDS100T3X0C-00SJG0 1TB                            | 1         | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 0.38%   |
| WDC WD5000LPVX-60V0TT0 500GB                          | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 18        | 20     | 26.47%  |
| Seagate            | 18        | 22     | 26.47%  |
| Toshiba            | 12        | 12     | 17.65%  |
| HGST               | 11        | 14     | 16.18%  |
| Hitachi            | 3         | 3      | 4.41%   |
| External           | 2         | 2      | 2.94%   |
| JMicron Technology | 1         | 1      | 1.47%   |
| Fujitsu            | 1         | 1      | 1.47%   |
| ASMT               | 1         | 2      | 1.47%   |
| Apple              | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 8         | 8      | 19.05%  |
| Samsung Electronics | 7         | 7      | 16.67%  |
| SanDisk             | 6         | 7      | 14.29%  |
| WDC                 | 5         | 5      | 11.9%   |
| Team                | 2         | 2      | 4.76%   |
| Intel               | 2         | 3      | 4.76%   |
| Apple               | 2         | 2      | 4.76%   |
| Transcend           | 1         | 1      | 2.38%   |
| Toshiba             | 1         | 1      | 2.38%   |
| SK hynix            | 1         | 1      | 2.38%   |
| Patriot             | 1         | 1      | 2.38%   |
| LaCie               | 1         | 1      | 2.38%   |
| Kingston            | 1         | 1      | 2.38%   |
| KingSpec            | 1         | 2      | 2.38%   |
| HXY                 | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| ASMT                | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 115       | 144    | 48.12%  |
| HDD     | 67        | 78     | 28.03%  |
| SSD     | 39        | 45     | 16.32%  |
| MMC     | 16        | 24     | 6.69%   |
| Unknown | 2         | 2      | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 115       | 144    | 49.57%  |
| SATA | 95        | 117    | 40.95%  |
| MMC  | 16        | 24     | 6.9%    |
| SAS  | 6         | 8      | 2.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 55        | 66     | 53.4%   |
| 0.51-1.0   | 44        | 51     | 42.72%  |
| 1.01-2.0   | 3         | 4      | 2.91%   |
| 3.01-4.0   | 1         | 2      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 63        | 29.72%  |
| 101-250        | 46        | 21.7%   |
| 501-1000       | 29        | 13.68%  |
| 1001-2000      | 18        | 8.49%   |
| 51-100         | 18        | 8.49%   |
| 21-50          | 16        | 7.55%   |
| 1-20           | 11        | 5.19%   |
| Unknown        | 5         | 2.36%   |
| More than 3000 | 4         | 1.89%   |
| 2001-3000      | 2         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 39.45%  |
| 21-50          | 52        | 23.85%  |
| 101-250        | 27        | 12.39%  |
| 51-100         | 22        | 10.09%  |
| 251-500        | 11        | 5.05%   |
| 501-1000       | 11        | 5.05%   |
| Unknown        | 5         | 2.29%   |
| 1001-2000      | 3         | 1.38%   |
| More than 3000 | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Notebooks | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T1 1TB                                  | 1         | 1      | 11.11%  |
| WDC WD Blue SA510 2.5 500GB                               | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD050V 500GB                                 | 1         | 1      | 11.11%  |
| Seagate ST500LM000-1EJ162 500GB                           | 1         | 2      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB                            | 1         | 1      | 11.11%  |
| SanDisk SD9SN8W-128G-1006 128GB SSD                       | 1         | 2      | 11.11%  |
| Samsung Electronics MZVLQ256HBJD-00BH1 256GB              | 1         | 1      | 11.11%  |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB | 1         | 1      | 11.11%  |
| Intel SSDSCKKF256H6 SATA 256GB                            | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 2         | 2      | 22.22%  |
| Seagate               | 2         | 3      | 22.22%  |
| Toshiba               | 1         | 1      | 11.11%  |
| SanDisk               | 1         | 2      | 11.11%  |
| Samsung Electronics   | 1         | 1      | 11.11%  |
| Realtek Semiconductor | 1         | 1      | 11.11%  |
| Intel                 | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 4      | 37.5%   |
| HDD  | 3         | 5      | 37.5%   |
| NVMe | 2         | 2      | 25%     |

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
| Detected | 127       | 189    | 59.91%  |
| Works    | 77        | 93     | 36.32%  |
| Malfunc  | 8         | 11     | 3.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 126       | 51.64%  |
| Samsung Electronics            | 36        | 14.75%  |
| SanDisk                        | 13        | 5.33%   |
| Micron Technology              | 11        | 4.51%   |
| SK hynix                       | 10        | 4.1%    |
| Kingston Technology Company    | 8         | 3.28%   |
| Phison Electronics             | 7         | 2.87%   |
| Micron/Crucial Technology      | 7         | 2.87%   |
| Toshiba America Info Systems   | 4         | 1.64%   |
| Silicon Motion                 | 4         | 1.64%   |
| AMD                            | 4         | 1.64%   |
| Realtek Semiconductor          | 2         | 0.82%   |
| KIOXIA                         | 2         | 0.82%   |
| ADATA Technology               | 2         | 0.82%   |
| Solidigm                       | 1         | 0.41%   |
| Solid State Storage Technology | 1         | 0.41%   |
| Shenzhen Longsys Electronics   | 1         | 0.41%   |
| Seagate Technology             | 1         | 0.41%   |
| O2 Micro                       | 1         | 0.41%   |
| Marvell Technology Group       | 1         | 0.41%   |
| Lite-On Technology             | 1         | 0.41%   |
| Apple                          | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 6.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 6.64%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14        | 5.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 4.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 4.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 4.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 4.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 3.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 2.34%   |
| Intel SSD 660P Series                                                          | 6         | 2.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.95%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.95%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 4         | 1.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.56%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.17%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 1.17%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 3         | 1.17%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.17%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 1.17%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3         | 1.17%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.17%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.78%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.78%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.78%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.78%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 2         | 0.78%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 0.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 115       | 46.56%  |
| SATA | 98        | 39.68%  |
| RAID | 31        | 12.55%  |
| IDE  | 3         | 1.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 170       | 84.58%  |
| AMD    | 31        | 15.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 10        | 4.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 3.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 2.99%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 2.49%   |
| Intel 12th Gen Core i7-12700H           | 5         | 2.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 1.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 1.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 1.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 1.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 4         | 1.99%   |
| Intel 13th Gen Core i7-1355U            | 4         | 1.99%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 4         | 1.99%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 3         | 1.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 1.49%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 1.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 3         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 1.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.49%   |
| Intel Core i9-10885H CPU @ 2.40GHz      | 2         | 1%      |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 1%      |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 2         | 1%      |
| Intel Core i7-10875H CPU @ 2.30GHz      | 2         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1%      |
| Intel Core i5-8300H CPU @ 2.30GHz       | 2         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 1%      |
| Intel Core i5-4300U CPU @ 1.90GHz       | 2         | 1%      |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1%      |
| Intel Core i5-3317U CPU @ 1.70GHz       | 2         | 1%      |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 1%      |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 1%      |
| Intel Core i3-4005U CPU @ 1.70GHz       | 2         | 1%      |
| Intel 12th Gen Core i9-12900H           | 2         | 1%      |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 2         | 1%      |
| AMD Ryzen 7 7730U with Radeon Graphics  | 2         | 1%      |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 1%      |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 1%      |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 59        | 29.35%  |
| Intel Core i5    | 51        | 25.37%  |
| Other            | 45        | 22.39%  |
| Intel Core i3    | 8         | 3.98%   |
| AMD Ryzen 7      | 8         | 3.98%   |
| Intel Celeron    | 5         | 2.49%   |
| AMD Ryzen 9      | 5         | 2.49%   |
| Intel Core i9    | 4         | 1.99%   |
| AMD Ryzen 5      | 4         | 1.99%   |
| Intel Core 2 Duo | 3         | 1.49%   |
| Intel Atom       | 2         | 1%      |
| Intel Pentium    | 1         | 0.5%    |
| Intel Core m5    | 1         | 0.5%    |
| Intel Core       | 1         | 0.5%    |
| Intel Celeron M  | 1         | 0.5%    |
| AMD Ryzen 7 PRO  | 1         | 0.5%    |
| AMD Ryzen 3      | 1         | 0.5%    |
| AMD A6           | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 74        | 36.82%  |
| 4      | 71        | 35.32%  |
| 8      | 21        | 10.45%  |
| 6      | 15        | 7.46%   |
| 14     | 9         | 4.48%   |
| 10     | 6         | 2.99%   |
| 12     | 2         | 1%      |
| 1      | 2         | 1%      |
| 16     | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 201       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 184       | 91.54%  |
| 1      | 17        | 8.46%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 200       | 99.5%   |
| 32-bit         | 1         | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 49.51%  |
| 0x806c1    | 8         | 3.92%   |
| 0x406e3    | 8         | 3.92%   |
| 0x306a9    | 8         | 3.92%   |
| 0x40651    | 7         | 3.43%   |
| 0x206a7    | 7         | 3.43%   |
| 0x906ea    | 6         | 2.94%   |
| 0x806ec    | 6         | 2.94%   |
| 0x806ea    | 5         | 2.45%   |
| 0x906a3    | 4         | 1.96%   |
| 0x806e9    | 4         | 1.96%   |
| 0xb06a3    | 3         | 1.47%   |
| 0xa0652    | 3         | 1.47%   |
| 0x906e9    | 3         | 1.47%   |
| 0x20655    | 3         | 1.47%   |
| 0x0a50000c | 3         | 1.47%   |
| 0x906ed    | 2         | 0.98%   |
| 0x806eb    | 2         | 0.98%   |
| 0x6fd      | 2         | 0.98%   |
| 0x306d4    | 2         | 0.98%   |
| 0x306c3    | 2         | 0.98%   |
| 0x806d1    | 1         | 0.49%   |
| 0x706a1    | 1         | 0.49%   |
| 0x6fb      | 1         | 0.49%   |
| 0x6e8      | 1         | 0.49%   |
| 0x506e3    | 1         | 0.49%   |
| 0x406c4    | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x20652    | 1         | 0.49%   |
| 0x106e5    | 1         | 0.49%   |
| 0x08608103 | 1         | 0.49%   |
| 0x08608102 | 1         | 0.49%   |
| 0x08600106 | 1         | 0.49%   |
| 0x08600104 | 1         | 0.49%   |
| 0x08108109 | 1         | 0.49%   |
| 0x06001119 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 48        | 23.88%  |
| Unknown           | 23        | 11.44%  |
| Haswell           | 20        | 9.95%   |
| TigerLake         | 15        | 7.46%   |
| Skylake           | 15        | 7.46%   |
| Zen 3             | 11        | 5.47%   |
| IvyBridge         | 11        | 5.47%   |
| SandyBridge       | 10        | 4.98%   |
| Alderlake Hybrid  | 9         | 4.48%   |
| CometLake         | 8         | 3.98%   |
| Broadwell         | 6         | 2.99%   |
| Westmere          | 4         | 1.99%   |
| Silvermont        | 4         | 1.99%   |
| Zen 2             | 3         | 1.49%   |
| Icelake           | 3         | 1.49%   |
| Core              | 3         | 1.49%   |
| Zen+              | 2         | 1%      |
| Goldmont plus     | 2         | 1%      |
| Piledriver        | 1         | 0.5%    |
| P6                | 1         | 0.5%    |
| Nehalem           | 1         | 0.5%    |
| Meteorlake Hybrid | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 159       | 56.58%  |
| Nvidia | 75        | 26.69%  |
| AMD    | 47        | 16.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 4.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 4.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 3.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.52%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 10        | 3.52%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 9         | 3.17%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.82%   |
| Intel HD Graphics 620                                                                    | 8         | 2.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 2.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 2.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.46%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 6         | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.11%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.76%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 1.41%   |
| Intel HD Graphics 630                                                                    | 4         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.06%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.06%   |
| Intel HD Graphics 530                                                                    | 3         | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.06%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.06%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.7%    |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 2         | 0.7%    |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.7%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.7%    |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.7%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 85        | 42.08%  |
| Intel + Nvidia | 60        | 29.7%   |
| 1 x AMD        | 25        | 12.38%  |
| Intel + AMD    | 15        | 7.43%   |
| 1 x Nvidia     | 10        | 4.95%   |
| AMD + Nvidia   | 5         | 2.48%   |
| 2 x AMD        | 2         | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 163       | 80.69%  |
| Proprietary | 33        | 16.34%  |
| Unknown     | 6         | 2.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 68.81%  |
| 1.01-2.0   | 27        | 13.37%  |
| 3.01-4.0   | 14        | 6.93%   |
| 0.01-0.5   | 12        | 5.94%   |
| 0.51-1.0   | 5         | 2.48%   |
| 5.01-6.0   | 4         | 1.98%   |
| 8.01-16.0  | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 19.2%   |
| BOE                     | 36        | 16.07%  |
| Chimei Innolux          | 31        | 13.84%  |
| LG Display              | 26        | 11.61%  |
| Samsung Electronics     | 21        | 9.38%   |
| Valve                   | 9         | 4.02%   |
| InfoVision              | 6         | 2.68%   |
| Goldstar                | 6         | 2.68%   |
| Apple                   | 6         | 2.68%   |
| Dell                    | 5         | 2.23%   |
| CSO                     | 4         | 1.79%   |
| Sharp                   | 3         | 1.34%   |
| Hewlett-Packard         | 3         | 1.34%   |
| BenQ                    | 3         | 1.34%   |
| ASUSTek Computer        | 3         | 1.34%   |
| LGD                     | 2         | 0.89%   |
| LG Philips              | 2         | 0.89%   |
| HKC                     | 2         | 0.89%   |
| Chi Mei Optoelectronics | 2         | 0.89%   |
| WBT                     | 1         | 0.45%   |
| ViewSonic               | 1         | 0.45%   |
| TMX                     | 1         | 0.45%   |
| Seiko/Epson             | 1         | 0.45%   |
| Philips                 | 1         | 0.45%   |
| PANDA                   | 1         | 0.45%   |
| Lenovo                  | 1         | 0.45%   |
| CMN                     | 1         | 0.45%   |
| Ancor Communications    | 1         | 0.45%   |
| Analogix                | 1         | 0.45%   |
| Acer                    | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 9         | 3.98%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 2.21%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 3         | 1.33%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 3         | 1.33%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 3         | 1.33%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 2         | 0.88%   |
| LGD LCD Monitor 1366x768                                              | 2         | 0.88%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch          | 2         | 0.88%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 0.88%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.88%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 0.88%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 0.88%   |
| Hewlett-Packard E233 HPN3460 1920x1080 509x286mm 23.0-inch            | 2         | 0.88%   |
| CSO LCD Monitor CSO1603 2560x1600 344x215mm 16.0-inch                 | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.88%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch        | 2         | 0.88%   |
| ASUSTek Computer PG32UQ AUS32E1 3840x2160 708x399mm 32.0-inch         | 2         | 0.88%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.88%   |
| WBT GOP28UHD144I WBT2800 3840x2160 630x330mm 28.0-inch                | 1         | 0.44%   |
| ViewSonic VX2718 Series VSCE439 1920x1080 598x336mm 27.0-inch         | 1         | 0.44%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.44%   |
| Seiko/Epson LCD Monitor 1280x800                                      | 1         | 0.44%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1         | 0.44%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 99        | 45.62%  |
| 1366x768 (WXGA)   | 54        | 24.88%  |
| 3840x2160 (4K)    | 15        | 6.91%   |
| 800x1280          | 10        | 4.61%   |
| 1920x1200 (WUXGA) | 6         | 2.76%   |
| 2880x1800         | 5         | 2.3%    |
| 1280x800 (WXGA)   | 5         | 2.3%    |
| 2560x1600         | 4         | 1.84%   |
| 2560x1440 (QHD)   | 4         | 1.84%   |
| 3440x1440         | 2         | 0.92%   |
| 1600x900 (HD+)    | 2         | 0.92%   |
| 1440x900 (WXGA+)  | 2         | 0.92%   |
| 3456x2160         | 1         | 0.46%   |
| 3200x2000         | 1         | 0.46%   |
| 3200x1800 (QHD+)  | 1         | 0.46%   |
| 3072x1920         | 1         | 0.46%   |
| 2880x1920         | 1         | 0.46%   |
| 2560x1080         | 1         | 0.46%   |
| 2304x1440         | 1         | 0.46%   |
| 2160x1440         | 1         | 0.46%   |
| 1920x515          | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 80        | 35.56%  |
| 14      | 37        | 16.44%  |
| 13      | 34        | 15.11%  |
| 16      | 10        | 4.44%   |
| 27      | 9         | 4%      |
| 7       | 9         | 4%      |
| 12      | 7         | 3.11%   |
| 11      | 6         | 2.67%   |
| Unknown | 5         | 2.22%   |
| 23      | 4         | 1.78%   |
| 21      | 4         | 1.78%   |
| 17      | 4         | 1.78%   |
| 31      | 3         | 1.33%   |
| 34      | 2         | 0.89%   |
| 32      | 2         | 0.89%   |
| 24      | 2         | 0.89%   |
| 84      | 1         | 0.44%   |
| 65      | 1         | 0.44%   |
| 40      | 1         | 0.44%   |
| 35      | 1         | 0.44%   |
| 28      | 1         | 0.44%   |
| 18      | 1         | 0.44%   |
| 3       | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 143       | 63.56%  |
| 201-300     | 29        | 12.89%  |
| 501-600     | 14        | 6.22%   |
| 1-100       | 10        | 4.44%   |
| 351-400     | 6         | 2.67%   |
| 601-700     | 5         | 2.22%   |
| 401-500     | 5         | 2.22%   |
| Unknown     | 5         | 2.22%   |
| 701-800     | 4         | 1.78%   |
| 801-900     | 2         | 0.89%   |
| 1501-2000   | 1         | 0.44%   |
| 1001-1500   | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 160       | 78.82%  |
| 16/10   | 24        | 11.82%  |
| 0.67    | 9         | 4.43%   |
| Unknown | 4         | 1.97%   |
| 21/9    | 3         | 1.48%   |
| 6/5     | 1         | 0.49%   |
| 3/2     | 1         | 0.49%   |
| 3.73    | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 35.56%  |
| 81-90          | 57        | 25.33%  |
| 71-80          | 13        | 5.78%   |
| 1-40           | 10        | 4.44%   |
| 301-350        | 10        | 4.44%   |
| 111-120        | 10        | 4.44%   |
| 201-250        | 9         | 4%      |
| 351-500        | 8         | 3.56%   |
| 61-70          | 7         | 3.11%   |
| 51-60          | 6         | 2.67%   |
| Unknown        | 5         | 2.22%   |
| 121-130        | 4         | 1.78%   |
| More than 1000 | 2         | 0.89%   |
| 251-300        | 1         | 0.44%   |
| 141-150        | 1         | 0.44%   |
| 501-1000       | 1         | 0.44%   |
| 91-100         | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 98        | 44.55%  |
| 101-120       | 51        | 23.18%  |
| 161-240       | 32        | 14.55%  |
| 51-100        | 21        | 9.55%   |
| More than 240 | 12        | 5.45%   |
| Unknown       | 5         | 2.27%   |
| 1-50          | 1         | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 163       | 81.09%  |
| 2     | 31        | 15.42%  |
| 0     | 6         | 2.99%   |
| 3     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 121       | 41.16%  |
| Realtek Semiconductor    | 99        | 33.67%  |
| Qualcomm Atheros         | 24        | 8.16%   |
| Broadcom                 | 11        | 3.74%   |
| MediaTek                 | 10        | 3.4%    |
| Ralink                   | 6         | 2.04%   |
| ASIX Electronics         | 5         | 1.7%    |
| Broadcom Limited         | 4         | 1.36%   |
| Xiaomi                   | 3         | 1.02%   |
| TP-Link                  | 3         | 1.02%   |
| Sierra Wireless          | 1         | 0.34%   |
| Samsung Electronics      | 1         | 0.34%   |
| Ralink Technology        | 1         | 0.34%   |
| Qualcomm                 | 1         | 0.34%   |
| QinHeng Electronics      | 1         | 0.34%   |
| NetGear                  | 1         | 0.34%   |
| Marvell Technology Group | 1         | 0.34%   |
| Lenovo                   | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 52        | 14.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16        | 4.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 13        | 3.66%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 3.38%   |
| Intel Wireless 8265 / 8275                                             | 10        | 2.82%   |
| Intel Wireless 8260                                                    | 9         | 2.54%   |
| Intel Wireless 7260                                                    | 9         | 2.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 2.54%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 2.25%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.97%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.41%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 1.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.13%   |
| Intel Wireless 7265                                                    | 4         | 1.13%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 1.13%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.85%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 3         | 0.85%   |
| Intel Wireless 3165                                                    | 3         | 0.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.85%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 117       | 55.98%  |
| Realtek Semiconductor | 36        | 17.22%  |
| Qualcomm Atheros      | 20        | 9.57%   |
| MediaTek              | 10        | 4.78%   |
| Broadcom              | 10        | 4.78%   |
| Ralink                | 6         | 2.87%   |
| Broadcom Limited      | 4         | 1.91%   |
| TP-Link               | 3         | 1.44%   |
| Sierra Wireless       | 1         | 0.48%   |
| Ralink Technology     | 1         | 0.48%   |
| NetGear               | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 13        | 6.19%   |
| Intel Wi-Fi 6 AX201                                                  | 12        | 5.71%   |
| Intel Wireless 8265 / 8275                                           | 10        | 4.76%   |
| Intel Wireless 8260                                                  | 9         | 4.29%   |
| Intel Wireless 7260                                                  | 9         | 4.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 9         | 4.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 8         | 3.81%   |
| Intel Wi-Fi 6 AX200                                                  | 7         | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 6         | 2.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 5         | 2.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 5         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 5         | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 2.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 1.9%    |
| Intel Wireless 7265                                                  | 4         | 1.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 1.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 1.43%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 3         | 1.43%   |
| Intel Wireless 3165                                                  | 3         | 1.43%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 3         | 1.43%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.43%   |
| Intel Centrino Advanced-N 6235                                       | 3         | 1.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2         | 0.95%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 2         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 0.95%   |
| Intel Wireless 3160                                                  | 2         | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 0.95%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 0.95%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                              | 2         | 0.95%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 0.95%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 79        | 55.63%  |
| Intel                    | 42        | 29.58%  |
| Qualcomm Atheros         | 6         | 4.23%   |
| ASIX Electronics         | 5         | 3.52%   |
| Xiaomi                   | 3         | 2.11%   |
| Broadcom                 | 2         | 1.41%   |
| Samsung Electronics      | 1         | 0.7%    |
| Qualcomm                 | 1         | 0.7%    |
| QinHeng Electronics      | 1         | 0.7%    |
| Marvell Technology Group | 1         | 0.7%    |
| Lenovo                   | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 52        | 35.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16        | 11.03%  |
| Intel Ethernet Connection I219-LM                                      | 8         | 5.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 4.14%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 3.45%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 3.45%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 2.76%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 2.07%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 2.07%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.07%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 2.07%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.38%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.38%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.38%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.69%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.69%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.69%   |
| Qualcomm Airtel 4G                                                     | 1         | 0.69%   |
| QinHeng USB 10/100 LAN                                                 | 1         | 0.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.69%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 0.69%   |
| Intel Ethernet Controller I219-V                                       | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.69%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 0.69%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.69%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.69%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 198       | 59.1%   |
| Ethernet | 137       | 40.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 86.14%  |
| Ethernet | 28        | 13.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 125       | 61.88%  |
| 1     | 75        | 37.13%  |
| 0     | 2         | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 141       | 68.78%  |
| Yes  | 64        | 31.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 55.11%  |
| Realtek Semiconductor           | 18        | 10.23%  |
| IMC Networks                    | 18        | 10.23%  |
| Qualcomm Atheros Communications | 11        | 6.25%   |
| Ralink                          | 5         | 2.84%   |
| Broadcom                        | 5         | 2.84%   |
| Toshiba                         | 4         | 2.27%   |
| Foxconn / Hon Hai               | 4         | 2.27%   |
| Apple                           | 4         | 2.27%   |
| Lite-On Technology              | 3         | 1.7%    |
| Hewlett-Packard                 | 2         | 1.14%   |
| Dell                            | 2         | 1.14%   |
| TP-Link                         | 1         | 0.57%   |
| MediaTek                        | 1         | 0.57%   |
| Cambridge Silicon Radio         | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 30        | 16.95%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 12.43%  |
| Intel AX201 Bluetooth                               | 20        | 11.3%   |
| Realtek Bluetooth Radio                             | 13        | 7.34%   |
| Intel AX211 Bluetooth                               | 10        | 5.65%   |
| IMC Networks Bluetooth Radio                        | 10        | 5.65%   |
| IMC Networks Wireless_Device                        | 8         | 4.52%   |
| Intel AX200 Bluetooth                               | 7         | 3.95%   |
| Ralink RT3290 Bluetooth                             | 5         | 2.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.82%   |
| Intel AX210 Bluetooth                               | 4         | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.69%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.69%   |
| Toshiba Bluetooth USB Host Controller               | 2         | 1.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.13%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.13%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 0.56%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.56%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.56%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.56%   |
| MediaTek Wireless_Device                            | 1         | 0.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.56%   |
| Lite-On Bluetooth Device                            | 1         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.56%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.56%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.56%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 169       | 66.02%  |
| Nvidia                | 43        | 16.8%   |
| AMD                   | 33        | 12.89%  |
| Lenovo                | 3         | 1.17%   |
| JMTek                 | 2         | 0.78%   |
| SteelSeries ApS       | 1         | 0.39%   |
| Samsung Electronics   | 1         | 0.39%   |
| Realtek Semiconductor | 1         | 0.39%   |
| Logitech              | 1         | 0.39%   |
| Hewlett-Packard       | 1         | 0.39%   |
| ASUSTek Computer      | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 9.33%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 20        | 6.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 5%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 4.67%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 4%      |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 12        | 4%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 3.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 11        | 3.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 3.33%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 8         | 2.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 2.33%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2%      |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 6         | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.33%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 4         | 1.33%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.33%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 1%      |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1%      |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Lenovo ThinkPad USB-C Dock Audio                                                                  | 2         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 36.97%  |
| SK hynix            | 23        | 19.33%  |
| Micron Technology   | 21        | 17.65%  |
| Crucial             | 10        | 8.4%    |
| Kingston            | 6         | 5.04%   |
| Unknown             | 4         | 3.36%   |
| Ramaxel Technology  | 4         | 3.36%   |
| Timetec             | 2         | 1.68%   |
| Wilk                | 1         | 0.84%   |
| Nanya Technology    | 1         | 0.84%   |
| Lexar               | 1         | 0.84%   |
| Gold Key            | 1         | 0.84%   |
| 4ea5                | 1         | 0.84%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 3.15%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 2.36%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s      | 3         | 2.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 1.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.57%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 2         | 1.57%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s  | 2         | 1.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.57%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 2         | 1.57%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s    | 2         | 1.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.57%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s   | 2         | 1.57%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 1.57%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s   | 2         | 1.57%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.57%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s | 2         | 1.57%   |
| Wilk RAM W-HK32S32O 32GB SODIMM DDR4 3200MT/s             | 1         | 0.79%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                 | 1         | 0.79%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s            | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.79%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.79%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                | 1         | 0.79%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.79%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.79%   |
| Timetec RAM S8G-1600 8GB Chip DDR3 1600MT/s               | 1         | 0.79%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s    | 1         | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.79%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s    | 1         | 0.79%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s    | 1         | 0.79%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s    | 1         | 0.79%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s   | 1         | 0.79%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.79%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.79%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 1         | 0.79%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 63        | 64.95%  |
| DDR3   | 18        | 18.56%  |
| DDR5   | 6         | 6.19%   |
| LPDDR4 | 5         | 5.15%   |
| LPDDR5 | 2         | 2.06%   |
| LPDDR3 | 2         | 2.06%   |
| DDR2   | 1         | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 86.14%  |
| Row Of Chips | 11        | 10.89%  |
| Chip         | 2         | 1.98%   |
| Unknown      | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 50        | 45.45%  |
| 16384 | 28        | 25.45%  |
| 4096  | 18        | 16.36%  |
| 2048  | 8         | 7.27%   |
| 32768 | 4         | 3.64%   |
| 49152 | 1         | 0.91%   |
| 1024  | 1         | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 33        | 30.84%  |
| 2667  | 28        | 26.17%  |
| 1600  | 11        | 10.28%  |
| 2400  | 8         | 7.48%   |
| 2133  | 7         | 6.54%   |
| 4800  | 4         | 3.74%   |
| 4267  | 3         | 2.8%    |
| 1334  | 3         | 2.8%    |
| 7500  | 2         | 1.87%   |
| 5600  | 2         | 1.87%   |
| 4266  | 1         | 0.93%   |
| 3733  | 1         | 0.93%   |
| 1867  | 1         | 0.93%   |
| 1333  | 1         | 0.93%   |
| 1067  | 1         | 0.93%   |
| 667   | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP DeskJet 2300 series | 1         | 50%     |
| Canon TR150 series     | 1         | 50%     |

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
| Chicony Electronics                    | 51        | 28.18%  |
| IMC Networks                           | 20        | 11.05%  |
| Microdia                               | 14        | 7.73%   |
| Bison Electronics                      | 14        | 7.73%   |
| Realtek Semiconductor                  | 10        | 5.52%   |
| Sunplus Innovation Technology          | 9         | 4.97%   |
| Luxvisions Innotech Limited            | 9         | 4.97%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 4.97%   |
| Quanta                                 | 8         | 4.42%   |
| Syntek                                 | 7         | 3.87%   |
| Apple                                  | 5         | 2.76%   |
| Acer                                   | 4         | 2.21%   |
| Sonix Technology                       | 3         | 1.66%   |
| Ricoh                                  | 3         | 1.66%   |
| Lite-On Technology                     | 3         | 1.66%   |
| Alcor Micro                            | 3         | 1.66%   |
| Suyin                                  | 2         | 1.1%    |
| Shinetech                              | 1         | 0.55%   |
| Samsung Electronics                    | 1         | 0.55%   |
| Ruision                                | 1         | 0.55%   |
| Microsoft                              | 1         | 0.55%   |
| Logitech                               | 1         | 0.55%   |
| Lenovo                                 | 1         | 0.55%   |
| Google                                 | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 22        | 12.09%  |
| IMC Networks USB2.0 HD UVC WebCam                               | 10        | 5.49%   |
| Microdia Integrated_Webcam_HD                                   | 8         | 4.4%    |
| Syntek Integrated Camera                                        | 6         | 3.3%    |
| Sunplus Integrated_Webcam_HD                                    | 5         | 2.75%   |
| IMC Networks Integrated Camera                                  | 5         | 2.75%   |
| Chicony Integrated Camera (1280x720@30)                         | 5         | 2.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 2.2%    |
| Bison Integrated Camera                                         | 4         | 2.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 4         | 2.2%    |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.65%   |
| Realtek HP Truevision HD                                        | 3         | 1.65%   |
| Quanta HP TrueVision HD Camera                                  | 3         | 1.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 1.65%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 1.65%   |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 1.1%    |
| Sonix USB2.0 HD UVC WebCam                                      | 2         | 1.1%    |
| Ricoh HD Webcam                                                 | 2         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 1.1%    |
| Microdia Integrated Webcam                                      | 2         | 1.1%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 1.1%    |
| Lite-On HP HD Camera                                            | 2         | 1.1%    |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 1.1%    |
| Chicony TOSHIBA Web Camera - FHD                                | 2         | 1.1%    |
| Chicony Lenovo EasyCamera                                       | 2         | 1.1%    |
| Chicony HP Truevision HD                                        | 2         | 1.1%    |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 1.1%    |
| Chicony HP HD Webcam                                            | 2         | 1.1%    |
| Chicony HD WebCam                                               | 2         | 1.1%    |
| Chicony EasyCamera                                              | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 1.1%    |
| Bison SunplusIT Integrated Camera                               | 2         | 1.1%    |
| Acer BisonCam,NB Pro                                            | 2         | 1.1%    |
| Syntek EasyCamera                                               | 1         | 0.55%   |
| Suyin HP TrueVision HD                                          | 1         | 0.55%   |
| Suyin 1.3M HD WebCam                                            | 1         | 0.55%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 0.55%   |
| Sunplus Integrated Webcam                                       | 1         | 0.55%   |
| Sonix USB2.0 FHD UVC WebCam                                     | 1         | 0.55%   |
| Shinetech ASUS FHD webcam                                       | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 24        | 43.64%  |
| Validity Sensors                   | 18        | 32.73%  |
| Elan Microelectronics              | 7         | 12.73%  |
| Shenzhen Goodix Technology         | 4         | 7.27%   |
| STMicroelectronics                 | 1         | 1.82%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                | 7         | 12.73%  |
| Validity Sensors Synaptics WBDI                                 | 5         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 5         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 5.45%   |
| Synaptics UWP WBDI Device                                       | 3         | 5.45%   |
| Synaptics Prometheus Fingerprint Reader                         | 3         | 5.45%   |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 5.45%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 3.64%   |
| Validity Sensors VFS491                                         | 2         | 3.64%   |
| Synaptics UWP WBDI                                              | 2         | 3.64%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 3.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 1.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.82%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.82%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.82%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.82%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 1.82%   |
| Synaptics TouchPad                                              | 1         | 1.82%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.82%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 1.82%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 45.45%  |
| Broadcom    | 4         | 36.36%  |
| Upek        | 1         | 9.09%   |
| Aktiv       | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 45.45%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 5880                                                                | 1         | 9.09%   |
| Aktiv Rutoken lite                                                           | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 104       | 50.98%  |
| 1     | 74        | 36.27%  |
| 2     | 20        | 9.8%    |
| 3     | 6         | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 41.73%  |
| Graphics card            | 27        | 21.26%  |
| Net/wireless             | 11        | 8.66%   |
| Chipcard                 | 9         | 7.09%   |
| Multimedia controller    | 7         | 5.51%   |
| Camera                   | 7         | 5.51%   |
| Bluetooth                | 5         | 3.94%   |
| Wireless                 | 2         | 1.57%   |
| Sound                    | 2         | 1.57%   |
| Communication controller | 2         | 1.57%   |
| Net/ethernet             | 1         | 0.79%   |
| Card reader              | 1         | 0.79%   |

