Linux in Germany - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

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

Total: 15077

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu       | LIFEBOOK E780               | [12c5cd0309](https://linux-hardware.org/?probe=12c5cd0309) | Jul 01, 2023 |
| Valve         | Jupiter                     | [86984d2e19](https://linux-hardware.org/?probe=86984d2e19) | Jun 30, 2023 |
| Fujitsu       | LIFEBOOK P771               | [9d6575a3aa](https://linux-hardware.org/?probe=9d6575a3aa) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| ASUSTek       | N76VM                       | [df79346cd4](https://linux-hardware.org/?probe=df79346cd4) | Jun 30, 2023 |
| HP            | Laptop 17-cp2xxx            | [2012cd2c37](https://linux-hardware.org/?probe=2012cd2c37) | Jun 30, 2023 |
| Acer          | Aspire A315-56              | [3a814856ae](https://linux-hardware.org/?probe=3a814856ae) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 8760w             | [470630eb65](https://linux-hardware.org/?probe=470630eb65) | Jun 30, 2023 |
| ASUSTek       | N76VM                       | [d770e894db](https://linux-hardware.org/?probe=d770e894db) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Valve         | Jupiter                     | [d8a4613446](https://linux-hardware.org/?probe=d8a4613446) | Jun 29, 2023 |
| Intel         | Whiskey Platform            | [1caca06d89](https://linux-hardware.org/?probe=1caca06d89) | Jun 29, 2023 |
| Medion        | Akoya P7818                 | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| Sony          | VGN-FE41M                   | [3bc894dc99](https://linux-hardware.org/?probe=3bc894dc99) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [a24ee9a903](https://linux-hardware.org/?probe=a24ee9a903) | Jun 29, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| HP            | EliteBook 840 G3            | [979c4b20fc](https://linux-hardware.org/?probe=979c4b20fc) | Jun 29, 2023 |
| HP            | Notebook                    | [a178cbf707](https://linux-hardware.org/?probe=a178cbf707) | Jun 29, 2023 |
| Acer          | Aspire A517-52              | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| Acer          | Aspire 5830TG               | [8c001b69bb](https://linux-hardware.org/?probe=8c001b69bb) | Jun 29, 2023 |
| HP            | Laptop 17-cp2xxx            | [f1a1aa76e2](https://linux-hardware.org/?probe=f1a1aa76e2) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| Acer          | Aspire V5-572P              | [1a28142960](https://linux-hardware.org/?probe=1a28142960) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [5819c72f02](https://linux-hardware.org/?probe=5819c72f02) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | [892229f999](https://linux-hardware.org/?probe=892229f999) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | [6d470794e9](https://linux-hardware.org/?probe=6d470794e9) | Jun 28, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| ASUSTek       | F5SR                        | [3722cfa5fb](https://linux-hardware.org/?probe=3722cfa5fb) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| TUXEDO        | P64_HJ,HK1                  | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| Acer          | Aspire 5738                 | [09d8109c56](https://linux-hardware.org/?probe=09d8109c56) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| Acer          | Aspire E5-573G              | [fc532e9492](https://linux-hardware.org/?probe=fc532e9492) | Jun 27, 2023 |
| Dell          | Latitude E6230              | [b52e22e663](https://linux-hardware.org/?probe=b52e22e663) | Jun 27, 2023 |
| Valve         | Jupiter                     | [563dc53040](https://linux-hardware.org/?probe=563dc53040) | Jun 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [d3e14b3015](https://linux-hardware.org/?probe=d3e14b3015) | Jun 26, 2023 |
| Dell          | Precision 5570              | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T1J    | [91955c07a6](https://linux-hardware.org/?probe=91955c07a6) | Jun 26, 2023 |
| ASUSTek       | F5SR                        | [059a0b2611](https://linux-hardware.org/?probe=059a0b2611) | Jun 26, 2023 |
| HP            | EliteBook 8560w             | [dc55ec08b3](https://linux-hardware.org/?probe=dc55ec08b3) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [44f08646c1](https://linux-hardware.org/?probe=44f08646c1) | Jun 26, 2023 |
| Unknown       | Unknown                     | [736f2d7bb5](https://linux-hardware.org/?probe=736f2d7bb5) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [de0797cd44](https://linux-hardware.org/?probe=de0797cd44) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| Acer          | Swift SFX16-52G             | [28c4b7b2f3](https://linux-hardware.org/?probe=28c4b7b2f3) | Jun 25, 2023 |
| Acer          | Swift SFX16-52G             | [ac98f81b2a](https://linux-hardware.org/?probe=ac98f81b2a) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| ASUSTek       | X75VC                       | [9fd44ac61e](https://linux-hardware.org/?probe=9fd44ac61e) | Jun 25, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e172f7e955](https://linux-hardware.org/?probe=e172f7e955) | Jun 25, 2023 |
| ASUSTek       | K54C                        | [38e6ce020c](https://linux-hardware.org/?probe=38e6ce020c) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| Unknown       | Unknown                     | [72c377827d](https://linux-hardware.org/?probe=72c377827d) | Jun 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [df9521a37d](https://linux-hardware.org/?probe=df9521a37d) | Jun 24, 2023 |
| ASUSTek       | X750LN                      | [739ab83805](https://linux-hardware.org/?probe=739ab83805) | Jun 24, 2023 |
| HP            | Pavilion Notebook           | [e80fd49ba9](https://linux-hardware.org/?probe=e80fd49ba9) | Jun 24, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [71f17d4d74](https://linux-hardware.org/?probe=71f17d4d74) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [8a22a7fba4](https://linux-hardware.org/?probe=8a22a7fba4) | Jun 24, 2023 |
| Dell          | Inspiron 5767               | [9e3bf66b84](https://linux-hardware.org/?probe=9e3bf66b84) | Jun 24, 2023 |
| Dell          | Latitude E6500              | [2b1720ad90](https://linux-hardware.org/?probe=2b1720ad90) | Jun 24, 2023 |
| MSI           | GS63 7RD                    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| ASUSTek       | K53TK                       | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| Lenovo        | V145-15AST 81MT             | [1fe939429c](https://linux-hardware.org/?probe=1fe939429c) | Jun 24, 2023 |
| Valve         | Jupiter                     | [ba0343b607](https://linux-hardware.org/?probe=ba0343b607) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [f51aeb6252](https://linux-hardware.org/?probe=f51aeb6252) | Jun 23, 2023 |
| Gigabyte      | AORUS 15P YD                | [1e2fb31885](https://linux-hardware.org/?probe=1e2fb31885) | Jun 23, 2023 |
| ASUSTek       | X555LAB                     | [7b227bbaed](https://linux-hardware.org/?probe=7b227bbaed) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [46e9b730a1](https://linux-hardware.org/?probe=46e9b730a1) | Jun 23, 2023 |
| Medion        | P6624                       | [49bd227ded](https://linux-hardware.org/?probe=49bd227ded) | Jun 23, 2023 |
| MSI           | S12T 3M/S12 3M              | [f135825cec](https://linux-hardware.org/?probe=f135825cec) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| HP            | Pavilion Notebook           | [cc0361248f](https://linux-hardware.org/?probe=cc0361248f) | Jun 23, 2023 |
| Acer          | Swift SFX14-51G             | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| TUXEDO        | Unknown                     | [71a75069f7](https://linux-hardware.org/?probe=71a75069f7) | Jun 23, 2023 |
| Dell          | Latitude E6510              | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [efad2eddea](https://linux-hardware.org/?probe=efad2eddea) | Jun 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [70b047f976](https://linux-hardware.org/?probe=70b047f976) | Jun 22, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [9d234065ed](https://linux-hardware.org/?probe=9d234065ed) | Jun 22, 2023 |
| Dell          | XPS 17 9710                 | [892620ac83](https://linux-hardware.org/?probe=892620ac83) | Jun 22, 2023 |
| Sony          | SVE1712C1EW                 | [12f0ee026f](https://linux-hardware.org/?probe=12f0ee026f) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4ae6c879aa](https://linux-hardware.org/?probe=4ae6c879aa) | Jun 22, 2023 |
| Acer          | Swift SFE16-42              | [9afa4fb174](https://linux-hardware.org/?probe=9afa4fb174) | Jun 22, 2023 |
| Framework     | Laptop                      | [eb51a9a662](https://linux-hardware.org/?probe=eb51a9a662) | Jun 22, 2023 |
| HP            | EliteBook 820 G3            | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| Acer          | Aspire V5-552G              | [adeea10c6c](https://linux-hardware.org/?probe=adeea10c6c) | Jun 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [8158959dbd](https://linux-hardware.org/?probe=8158959dbd) | Jun 22, 2023 |
| HP            | EliteBook 8540p             | [c72d0ef702](https://linux-hardware.org/?probe=c72d0ef702) | Jun 22, 2023 |
| Lenovo        | ThinkPad L380 20M5000UGE    | [06db720b62](https://linux-hardware.org/?probe=06db720b62) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [888133764a](https://linux-hardware.org/?probe=888133764a) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [522dfb5977](https://linux-hardware.org/?probe=522dfb5977) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [601921c51d](https://linux-hardware.org/?probe=601921c51d) | Jun 21, 2023 |
| ASUSTek       | G752VM                      | [b518236bd7](https://linux-hardware.org/?probe=b518236bd7) | Jun 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo        | ThinkPad T510 4349WHC       | [9134464b7a](https://linux-hardware.org/?probe=9134464b7a) | Jun 21, 2023 |
| Acer          | Extensa 2519                | [36f37b33d5](https://linux-hardware.org/?probe=36f37b33d5) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [510604914c](https://linux-hardware.org/?probe=510604914c) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [ab169bfbfd](https://linux-hardware.org/?probe=ab169bfbfd) | Jun 21, 2023 |
| HONOR         | HLYL-WXX9                   | [498f41554b](https://linux-hardware.org/?probe=498f41554b) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Apple         | MacBookPro6,2               | [3beb323b62](https://linux-hardware.org/?probe=3beb323b62) | Jun 21, 2023 |
| Packard Be... | EasyNote TE11HC             | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [293b8783a3](https://linux-hardware.org/?probe=293b8783a3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f452cfce0](https://linux-hardware.org/?probe=2f452cfce0) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| HUAWEI        | CREM-WXX9                   | [55182e9371](https://linux-hardware.org/?probe=55182e9371) | Jun 20, 2023 |
| TUXEDO        | P95xER                      | [f2f6ddaf27](https://linux-hardware.org/?probe=f2f6ddaf27) | Jun 20, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [3be3d70197](https://linux-hardware.org/?probe=3be3d70197) | Jun 20, 2023 |
| HP            | 255 G7 Notebook PC          | [3db68832fd](https://linux-hardware.org/?probe=3db68832fd) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| MSI           | GT70 2OC/2OD                | [d8d81f0614](https://linux-hardware.org/?probe=d8d81f0614) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| TUXEDO        | P65xRP                      | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Valve         | Jupiter                     | [f4e47bb83e](https://linux-hardware.org/?probe=f4e47bb83e) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | [82c9c200bc](https://linux-hardware.org/?probe=82c9c200bc) | Jun 20, 2023 |
| HP            | Pavilion dv6                | [09d49049bf](https://linux-hardware.org/?probe=09d49049bf) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [91f85b5bb5](https://linux-hardware.org/?probe=91f85b5bb5) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [93f576698e](https://linux-hardware.org/?probe=93f576698e) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| HP            | Pavilion Laptop 13-an0xx... | [0f68ace67c](https://linux-hardware.org/?probe=0f68ace67c) | Jun 19, 2023 |
| Lenovo        | ThinkPad T450s 20BWS11H0... | [596055aa43](https://linux-hardware.org/?probe=596055aa43) | Jun 19, 2023 |
| HP            | Laptop 15-db0xxx            | [c67d08fe43](https://linux-hardware.org/?probe=c67d08fe43) | Jun 19, 2023 |
| HP            | Laptop 14s-fq0xxx           | [6ff28ccac1](https://linux-hardware.org/?probe=6ff28ccac1) | Jun 19, 2023 |
| Acer          | Aspire 7739                 | [eda7fb180a](https://linux-hardware.org/?probe=eda7fb180a) | Jun 19, 2023 |
| MSI           | GL72M 7REX                  | [6d50ff945d](https://linux-hardware.org/?probe=6d50ff945d) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| Acer          | Aspire 7739                 | [34854e20dd](https://linux-hardware.org/?probe=34854e20dd) | Jun 18, 2023 |
| MSI           | MS-16Y1                     | [167889509f](https://linux-hardware.org/?probe=167889509f) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | [ce3c5bc056](https://linux-hardware.org/?probe=ce3c5bc056) | Jun 18, 2023 |
| ASUSTek       | X555LJ                      | [a4bea0f3e3](https://linux-hardware.org/?probe=a4bea0f3e3) | Jun 18, 2023 |
| ASUSTek       | X555LA                      | [a57885e16c](https://linux-hardware.org/?probe=a57885e16c) | Jun 18, 2023 |
| HP            | Notebook                    | [e53b70bcac](https://linux-hardware.org/?probe=e53b70bcac) | Jun 18, 2023 |
| ASUSTek       | X556UQK                     | [fb675907ec](https://linux-hardware.org/?probe=fb675907ec) | Jun 18, 2023 |
| Dell          | Precision M4800             | [9f86d737f2](https://linux-hardware.org/?probe=9f86d737f2) | Jun 18, 2023 |
| HP            | Compaq Presario CQ71        | [d5025e2864](https://linux-hardware.org/?probe=d5025e2864) | Jun 18, 2023 |
| HP            | EliteBook 840 G5            | [7c7742bf5a](https://linux-hardware.org/?probe=7c7742bf5a) | Jun 18, 2023 |
| VALE          | Notebook Classic C140       | [afa3a9de5e](https://linux-hardware.org/?probe=afa3a9de5e) | Jun 18, 2023 |
| Sony          | SVF1421L1EW                 | [5d377cbe13](https://linux-hardware.org/?probe=5d377cbe13) | Jun 17, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [2bfd69673e](https://linux-hardware.org/?probe=2bfd69673e) | Jun 17, 2023 |
| Sony          | SVF1421L1EW                 | [e4dc7d363e](https://linux-hardware.org/?probe=e4dc7d363e) | Jun 17, 2023 |
| HP            | Notebook                    | [f01887f9d6](https://linux-hardware.org/?probe=f01887f9d6) | Jun 17, 2023 |
| HP            | 250 G4                      | [f25c49812b](https://linux-hardware.org/?probe=f25c49812b) | Jun 17, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [9206f6c141](https://linux-hardware.org/?probe=9206f6c141) | Jun 17, 2023 |
| HP            | EliteBook 8440p             | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Medion        | S15449                      | [9ee17b411b](https://linux-hardware.org/?probe=9ee17b411b) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop      | [2d5c5b2c80](https://linux-hardware.org/?probe=2d5c5b2c80) | Jun 17, 2023 |
| Lenovo        | ThinkPad Edge E535 3260F... | [3fd273f672](https://linux-hardware.org/?probe=3fd273f672) | Jun 17, 2023 |
| Medion        | E6214                       | [5547ea042f](https://linux-hardware.org/?probe=5547ea042f) | Jun 17, 2023 |
| Medion        | E6214                       | [98ddb6700a](https://linux-hardware.org/?probe=98ddb6700a) | Jun 17, 2023 |
| Dell          | Inspiron 3593               | [46ad2c78f7](https://linux-hardware.org/?probe=46ad2c78f7) | Jun 17, 2023 |
| Toshiba       | Satellite L775D-107         | [7959d73eb9](https://linux-hardware.org/?probe=7959d73eb9) | Jun 17, 2023 |
| ASUSTek       | K73BR                       | [9f4d2564bf](https://linux-hardware.org/?probe=9f4d2564bf) | Jun 16, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [45d3e053e3](https://linux-hardware.org/?probe=45d3e053e3) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| Samsung       | 750XDA                      | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| Dell          | Latitude D620               | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| HONOR         | BMH-WCX9                    | [da0a4b3bf0](https://linux-hardware.org/?probe=da0a4b3bf0) | Jun 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ea2e8604af](https://linux-hardware.org/?probe=ea2e8604af) | Jun 16, 2023 |
| Dell          | Precision 3570              | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| MSI           | GL72M 7REX                  | [1f1699301f](https://linux-hardware.org/?probe=1f1699301f) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | [32eb9f5dea](https://linux-hardware.org/?probe=32eb9f5dea) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | [9f9ffda2e3](https://linux-hardware.org/?probe=9f9ffda2e3) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| ASUSTek       | K70AC                       | [b9dc7d0b00](https://linux-hardware.org/?probe=b9dc7d0b00) | Jun 15, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Dell          | Latitude E7450              | [05ebaf45ae](https://linux-hardware.org/?probe=05ebaf45ae) | Jun 15, 2023 |
| Medion        | E6214                       | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | [ff98efdef7](https://linux-hardware.org/?probe=ff98efdef7) | Jun 15, 2023 |
| HP            | EliteBook 1040 G4           | [01724286d9](https://linux-hardware.org/?probe=01724286d9) | Jun 15, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5b85dc34c6](https://linux-hardware.org/?probe=5b85dc34c6) | Jun 15, 2023 |
| Dell          | Precision M4500             | [5daca408ec](https://linux-hardware.org/?probe=5daca408ec) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HP            | ENVY 17                     | [269ca0c6e9](https://linux-hardware.org/?probe=269ca0c6e9) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | [8f84dca464](https://linux-hardware.org/?probe=8f84dca464) | Jun 14, 2023 |
| Dell          | Latitude 7430               | [6cf1c68c1d](https://linux-hardware.org/?probe=6cf1c68c1d) | Jun 14, 2023 |
| HP            | Pavilion 17                 | [bf5d126cc8](https://linux-hardware.org/?probe=bf5d126cc8) | Jun 14, 2023 |
| ASUSTek       | X555LA                      | [782fa74afe](https://linux-hardware.org/?probe=782fa74afe) | Jun 14, 2023 |
| Dell          | XPS 9320                    | [a6567a0c58](https://linux-hardware.org/?probe=a6567a0c58) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK E780               | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | [1626648a8b](https://linux-hardware.org/?probe=1626648a8b) | Jun 13, 2023 |
| LincPlus      | LINNCPLUS P1                | [878dc2b05f](https://linux-hardware.org/?probe=878dc2b05f) | Jun 13, 2023 |
| Medion        | E7424 MD60150               | [c8d6acdb6f](https://linux-hardware.org/?probe=c8d6acdb6f) | Jun 13, 2023 |
| Medion        | Akoya P6656 MD99615         | [f6956c6b6c](https://linux-hardware.org/?probe=f6956c6b6c) | Jun 13, 2023 |
| Medion        | E7424 MD60150               | [9f4ec54afd](https://linux-hardware.org/?probe=9f4ec54afd) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Schenker      | VIA 15 Pro                  | [311a7e116c](https://linux-hardware.org/?probe=311a7e116c) | Jun 13, 2023 |
| HP            | Pavilion 17                 | [54eb1dbd1c](https://linux-hardware.org/?probe=54eb1dbd1c) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3f3cbfd7fe](https://linux-hardware.org/?probe=3f3cbfd7fe) | Jun 12, 2023 |
| Acer          | Aspire F5-573G              | [c85f08223b](https://linux-hardware.org/?probe=c85f08223b) | Jun 12, 2023 |
| TUXEDO        | Unknown                     | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [4df7edf5e2](https://linux-hardware.org/?probe=4df7edf5e2) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | [a4c87fb2bc](https://linux-hardware.org/?probe=a4c87fb2bc) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a6d7a1885](https://linux-hardware.org/?probe=7a6d7a1885) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | [2069778d1f](https://linux-hardware.org/?probe=2069778d1f) | Jun 12, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [f3dae81611](https://linux-hardware.org/?probe=f3dae81611) | Jun 12, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [f19d062310](https://linux-hardware.org/?probe=f19d062310) | Jun 12, 2023 |
| Dell          | Latitude 7430               | [6a01453dfa](https://linux-hardware.org/?probe=6a01453dfa) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| Dell          | Latitude E6510              | [f3e9e3bbf1](https://linux-hardware.org/?probe=f3e9e3bbf1) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9a4af7d5c3](https://linux-hardware.org/?probe=9a4af7d5c3) | Jun 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [d2c4574d58](https://linux-hardware.org/?probe=d2c4574d58) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | [352eaf6ce7](https://linux-hardware.org/?probe=352eaf6ce7) | Jun 11, 2023 |
| Acer          | Aspire A317-33              | [f62e645bd3](https://linux-hardware.org/?probe=f62e645bd3) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | [673ab1f0a9](https://linux-hardware.org/?probe=673ab1f0a9) | Jun 11, 2023 |
| Valve         | Jupiter                     | [fc47f86c91](https://linux-hardware.org/?probe=fc47f86c91) | Jun 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| HP            | EliteBook 1040 G4           | [98aa06475b](https://linux-hardware.org/?probe=98aa06475b) | Jun 10, 2023 |
| Apple         | MacBookPro11,3              | [b7dfbae839](https://linux-hardware.org/?probe=b7dfbae839) | Jun 10, 2023 |
| Dell          | Latitude E6510              | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| HP            | Laptop 17-by3xxx            | [421ff52b0b](https://linux-hardware.org/?probe=421ff52b0b) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [65a47406b0](https://linux-hardware.org/?probe=65a47406b0) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [b2f7d876c7](https://linux-hardware.org/?probe=b2f7d876c7) | Jun 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| HP            | ZBook 15 G2                 | [68c941fe5d](https://linux-hardware.org/?probe=68c941fe5d) | Jun 10, 2023 |
| HP            | EliteBook 840 G2            | [770045a9fc](https://linux-hardware.org/?probe=770045a9fc) | Jun 10, 2023 |
| HP            | ZBook 15 G2                 | [2851b41659](https://linux-hardware.org/?probe=2851b41659) | Jun 09, 2023 |
| HP            | Laptop 17-bs0xx             | [c93d52343c](https://linux-hardware.org/?probe=c93d52343c) | Jun 09, 2023 |
| Google        | Akali 360                   | [1f7d5f8bc5](https://linux-hardware.org/?probe=1f7d5f8bc5) | Jun 09, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| Dell          | Latitude E7470              | [c5457da74f](https://linux-hardware.org/?probe=c5457da74f) | Jun 09, 2023 |
| Dell          | Precision M4600             | [a79a783515](https://linux-hardware.org/?probe=a79a783515) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E754               | [4d09f42447](https://linux-hardware.org/?probe=4d09f42447) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [531e3f124d](https://linux-hardware.org/?probe=531e3f124d) | Jun 09, 2023 |
| HP            | EliteBook Folio 9470m       | [5739bbf07f](https://linux-hardware.org/?probe=5739bbf07f) | Jun 08, 2023 |
| HP            | EliteBook Folio 9470m       | [74dd8ef72a](https://linux-hardware.org/?probe=74dd8ef72a) | Jun 08, 2023 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [4c8d8758b7](https://linux-hardware.org/?probe=4c8d8758b7) | Jun 08, 2023 |
| Lenovo        | ThinkPad X280 20KES5SE22    | [c25a510191](https://linux-hardware.org/?probe=c25a510191) | Jun 08, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [e6cb646bd4](https://linux-hardware.org/?probe=e6cb646bd4) | Jun 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [0aea375d78](https://linux-hardware.org/?probe=0aea375d78) | Jun 08, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3f04b950e8](https://linux-hardware.org/?probe=3f04b950e8) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7543a0bbc1](https://linux-hardware.org/?probe=7543a0bbc1) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444C... | [4e5e1d4052](https://linux-hardware.org/?probe=4e5e1d4052) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [06608c68d7](https://linux-hardware.org/?probe=06608c68d7) | Jun 07, 2023 |
| Apple         | MacBookPro11,1              | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| ASUSTek       | X200MA                      | [7c0552ad30](https://linux-hardware.org/?probe=7c0552ad30) | Jun 06, 2023 |
| Dell          | Precision 5510              | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| Acer          | Aspire V5-572P              | [cdb5005799](https://linux-hardware.org/?probe=cdb5005799) | Jun 06, 2023 |
| Acer          | Aspire V5-572P              | [49745927a0](https://linux-hardware.org/?probe=49745927a0) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| Acer          | Aspire A517-53              | [a039ca0054](https://linux-hardware.org/?probe=a039ca0054) | Jun 05, 2023 |
| TUXEDO        | N8xEJEK                     | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X250 20CLS02K00    | [fc306205a7](https://linux-hardware.org/?probe=fc306205a7) | Jun 05, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [55abece90c](https://linux-hardware.org/?probe=55abece90c) | Jun 05, 2023 |
| Acer          | Aspire ES1-571              | [ed19db3614](https://linux-hardware.org/?probe=ed19db3614) | Jun 05, 2023 |
| HP            | Notebook                    | [1605419ae0](https://linux-hardware.org/?probe=1605419ae0) | Jun 05, 2023 |
| HP            | Laptop 17-cp0xxx            | [b142b6de06](https://linux-hardware.org/?probe=b142b6de06) | Jun 05, 2023 |
| Dell          | Latitude E6510              | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5540              | [d2bde0e098](https://linux-hardware.org/?probe=d2bde0e098) | Jun 04, 2023 |
| Dell          | Latitude E5540              | [f9483c219e](https://linux-hardware.org/?probe=f9483c219e) | Jun 04, 2023 |
| Dell          | Latitude E6510              | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| Acer          | Aspire 3820                 | [edbf91844a](https://linux-hardware.org/?probe=edbf91844a) | Jun 04, 2023 |
| Sony          | VPCEH2H4E                   | [793e883d0c](https://linux-hardware.org/?probe=793e883d0c) | Jun 04, 2023 |
| HP            | EliteBook 840 G3            | [7c35e9a268](https://linux-hardware.org/?probe=7c35e9a268) | Jun 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | [4d9e4fb129](https://linux-hardware.org/?probe=4d9e4fb129) | Jun 04, 2023 |
| Dell          | Latitude E5440              | [02b3462a2c](https://linux-hardware.org/?probe=02b3462a2c) | Jun 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| Acer          | Swift SF316-51              | [4ba1405836](https://linux-hardware.org/?probe=4ba1405836) | Jun 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [2eeb67613f](https://linux-hardware.org/?probe=2eeb67613f) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| MSI           | U200                        | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7179829c20](https://linux-hardware.org/?probe=7179829c20) | Jun 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [038871f5be](https://linux-hardware.org/?probe=038871f5be) | Jun 04, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Toshiba       | TECRA Z40-C                 | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| ASUSTek       | K52Je                       | [0190eef08c](https://linux-hardware.org/?probe=0190eef08c) | Jun 03, 2023 |
| Gigabyte      | G5 GE                       | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| ASUSTek       | X540SA                      | [e9e8995d2e](https://linux-hardware.org/?probe=e9e8995d2e) | Jun 03, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| Chuwi         | GemiBook Pro                | [772d1f8765](https://linux-hardware.org/?probe=772d1f8765) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| ASUSTek       | K52Je                       | [c6f78ba2aa](https://linux-hardware.org/?probe=c6f78ba2aa) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [41e5c1790c](https://linux-hardware.org/?probe=41e5c1790c) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [d583c74274](https://linux-hardware.org/?probe=d583c74274) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [7ed9ba7165](https://linux-hardware.org/?probe=7ed9ba7165) | Jun 03, 2023 |
| Toshiba       | Satellite L50-C             | [7b1b547b11](https://linux-hardware.org/?probe=7b1b547b11) | Jun 03, 2023 |
| Acer          | Aspire 7745G                | [135ce50995](https://linux-hardware.org/?probe=135ce50995) | Jun 03, 2023 |
| Dell          | G15 5520                    | [b77b760dfe](https://linux-hardware.org/?probe=b77b760dfe) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Notebook                    | [9b12c54cf2](https://linux-hardware.org/?probe=9b12c54cf2) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | [160d4525c6](https://linux-hardware.org/?probe=160d4525c6) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| MSI           | U200                        | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [f576f54ff2](https://linux-hardware.org/?probe=f576f54ff2) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | [e94cab5008](https://linux-hardware.org/?probe=e94cab5008) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1aea71b6c0](https://linux-hardware.org/?probe=1aea71b6c0) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1bdb74a8ba](https://linux-hardware.org/?probe=1bdb74a8ba) | Jun 02, 2023 |
| HP            | G62                         | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Dell          | Latitude 5540               | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| Acer          | Predator PH517-51           | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [97b54068b7](https://linux-hardware.org/?probe=97b54068b7) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| Dell          | Vostro 7590                 | [d9bfa42b63](https://linux-hardware.org/?probe=d9bfa42b63) | Jun 01, 2023 |
| Packard Be... | EasyNote TK11BZ             | [b1cbe3b6a6](https://linux-hardware.org/?probe=b1cbe3b6a6) | Jun 01, 2023 |
| HP            | ProBook 6450b               | [d3d4e45f9d](https://linux-hardware.org/?probe=d3d4e45f9d) | Jun 01, 2023 |
| ASUSTek       | K53SK                       | [9b376cdd45](https://linux-hardware.org/?probe=9b376cdd45) | Jun 01, 2023 |
| Apple         | MacBook4,1                  | [996b318420](https://linux-hardware.org/?probe=996b318420) | Jun 01, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efe855c429](https://linux-hardware.org/?probe=efe855c429) | May 31, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [c56e8318db](https://linux-hardware.org/?probe=c56e8318db) | May 31, 2023 |
| ASUSTek       | K53SK                       | [39c63c5bd1](https://linux-hardware.org/?probe=39c63c5bd1) | May 31, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | [1be071e25d](https://linux-hardware.org/?probe=1be071e25d) | May 31, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [2bb50cdcc7](https://linux-hardware.org/?probe=2bb50cdcc7) | May 31, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| Dell          | Precision 3550              | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [0ead50ad49](https://linux-hardware.org/?probe=0ead50ad49) | May 31, 2023 |
| ASUSTek       | K53SK                       | [bfd926c8da](https://linux-hardware.org/?probe=bfd926c8da) | May 30, 2023 |
| VALE          | Notebook Classic C140       | [cdc6168586](https://linux-hardware.org/?probe=cdc6168586) | May 30, 2023 |
| Acer          | Aspire 5749                 | [3bca2af88d](https://linux-hardware.org/?probe=3bca2af88d) | May 30, 2023 |
| Acer          | Predator PH517-51           | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [048a3a0f30](https://linux-hardware.org/?probe=048a3a0f30) | May 29, 2023 |
| Fujitsu       | LIFEBOOK E780               | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9fce8d1e40](https://linux-hardware.org/?probe=9fce8d1e40) | May 29, 2023 |
| Acer          | Aspire A315-51              | [d6f1c2bdbd](https://linux-hardware.org/?probe=d6f1c2bdbd) | May 29, 2023 |
| Acer          | Aspire ES1-571              | [6f75ba50c1](https://linux-hardware.org/?probe=6f75ba50c1) | May 29, 2023 |
| Apple         | MacBookPro14,1              | [a5785cf3c3](https://linux-hardware.org/?probe=a5785cf3c3) | May 29, 2023 |
| Samsung       | 600B4B/600B5B               | [feba5017b3](https://linux-hardware.org/?probe=feba5017b3) | May 29, 2023 |
| Dell          | XPS 13 9310                 | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| HP            | EliteBook 735 G6            | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Fujitsu       | CELSIUS H720                | [d7d19435c2](https://linux-hardware.org/?probe=d7d19435c2) | May 29, 2023 |
| Acer          | Nitro AN515-52              | [b90162f812](https://linux-hardware.org/?probe=b90162f812) | May 29, 2023 |
| HP            | Laptop 17-cp0xxx            | [5ac36928a5](https://linux-hardware.org/?probe=5ac36928a5) | May 28, 2023 |
| ALLDOCUBE     | i1405C                      | [7e4475ef13](https://linux-hardware.org/?probe=7e4475ef13) | May 28, 2023 |
| Acer          | Swift SF114-34              | [ec48f7a207](https://linux-hardware.org/?probe=ec48f7a207) | May 28, 2023 |
| Dell          | Inspiron 7559               | [af1bb009ca](https://linux-hardware.org/?probe=af1bb009ca) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| Lenovo        | V130-15IKB 81HN             | [e50700f8be](https://linux-hardware.org/?probe=e50700f8be) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Acer          | Aspire ES1-571              | [a3da42e0e9](https://linux-hardware.org/?probe=a3da42e0e9) | May 28, 2023 |
| TUXEDO        | Unknown                     | [21be23e012](https://linux-hardware.org/?probe=21be23e012) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [618a907425](https://linux-hardware.org/?probe=618a907425) | May 27, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [ef1ea73723](https://linux-hardware.org/?probe=ef1ea73723) | May 27, 2023 |
| Acer          | TravelMate 5735Z            | [9eea76e3ee](https://linux-hardware.org/?probe=9eea76e3ee) | May 27, 2023 |
| Lenovo        | G50-70 20351                | [ee0a9f666c](https://linux-hardware.org/?probe=ee0a9f666c) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | EliteBook 840 G2            | [519e04a228](https://linux-hardware.org/?probe=519e04a228) | May 27, 2023 |
| Acer          | Aspire ES1-571              | [029ea88e3b](https://linux-hardware.org/?probe=029ea88e3b) | May 27, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [9984b363d1](https://linux-hardware.org/?probe=9984b363d1) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [737d3fe7fb](https://linux-hardware.org/?probe=737d3fe7fb) | May 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [d5d9543a5a](https://linux-hardware.org/?probe=d5d9543a5a) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [16ee98f9cc](https://linux-hardware.org/?probe=16ee98f9cc) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [39cf075935](https://linux-hardware.org/?probe=39cf075935) | May 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90058G... | [71a2e90192](https://linux-hardware.org/?probe=71a2e90192) | May 26, 2023 |
| ASUSTek       | K53SV                       | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| ASUSTek       | K52Je                       | [3b40aeae90](https://linux-hardware.org/?probe=3b40aeae90) | May 26, 2023 |
| Dell          | Latitude E6330              | [e7477af1a5](https://linux-hardware.org/?probe=e7477af1a5) | May 26, 2023 |
| Dell          | Precision 5530              | [702b4d7914](https://linux-hardware.org/?probe=702b4d7914) | May 26, 2023 |
| Dell          | Latitude E6510              | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| HP            | 250 G7 Notebook PC          | [2f0f83bda2](https://linux-hardware.org/?probe=2f0f83bda2) | May 25, 2023 |
| ASUSTek       | X705UVR                     | [bedbf77e16](https://linux-hardware.org/?probe=bedbf77e16) | May 25, 2023 |
| Sony          | SVF1521B4E                  | [d6eaf68ef4](https://linux-hardware.org/?probe=d6eaf68ef4) | May 25, 2023 |
| Sony          | SVF1521B4E                  | [03c5deb4cc](https://linux-hardware.org/?probe=03c5deb4cc) | May 25, 2023 |
| Acer          | Aspire V3-371               | [f9200e891b](https://linux-hardware.org/?probe=f9200e891b) | May 25, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | [48ad025649](https://linux-hardware.org/?probe=48ad025649) | May 25, 2023 |
| Google        | Akali 360                   | [2a4bbc5d81](https://linux-hardware.org/?probe=2a4bbc5d81) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| Dell          | Latitude E6430              | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Lenovo        | ThinkPad T440p 20AW0045M... | [355e03f684](https://linux-hardware.org/?probe=355e03f684) | May 25, 2023 |
| Fujitsu       | LIFEBOOK E752               | [0c7493d8d3](https://linux-hardware.org/?probe=0c7493d8d3) | May 24, 2023 |
| Lenovo        | IdeaPad Y560                | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | 255 G7 Notebook PC          | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Lenovo        | G50-70 20351                | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| Apple         | MacBookPro6,2               | [6858db4f73](https://linux-hardware.org/?probe=6858db4f73) | May 24, 2023 |
| Dell          | Precision 5570              | [f014c35d45](https://linux-hardware.org/?probe=f014c35d45) | May 24, 2023 |
| Lenovo        | ThinkPad T410 2537AT1       | [babbb757c6](https://linux-hardware.org/?probe=babbb757c6) | May 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [520e3d90a6](https://linux-hardware.org/?probe=520e3d90a6) | May 24, 2023 |
| ASUSTek       | K73BR                       | [2b59c4c84c](https://linux-hardware.org/?probe=2b59c4c84c) | May 24, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [306ecade71](https://linux-hardware.org/?probe=306ecade71) | May 24, 2023 |
| Valve         | Jupiter                     | [fd4190f3d7](https://linux-hardware.org/?probe=fd4190f3d7) | May 24, 2023 |
| PC Special... | NH5x_7xDPx                  | [4d4ce3a2bc](https://linux-hardware.org/?probe=4d4ce3a2bc) | May 23, 2023 |
| Dell          | Inspiron 3593               | [715800f05d](https://linux-hardware.org/?probe=715800f05d) | May 23, 2023 |
| Toshiba       | Satellite C660D             | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| Dell          | Latitude E6510              | [731befae67](https://linux-hardware.org/?probe=731befae67) | May 23, 2023 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | [cd2c3fbd45](https://linux-hardware.org/?probe=cd2c3fbd45) | May 23, 2023 |
| ASUSTek       | X751MA                      | [674b64f381](https://linux-hardware.org/?probe=674b64f381) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e1c91c725](https://linux-hardware.org/?probe=6e1c91c725) | May 23, 2023 |
| Matsushita... | CF-W7BWAYZL3                | [a00f38be95](https://linux-hardware.org/?probe=a00f38be95) | May 23, 2023 |
| Lenovo        | ThinkPad W500 40626NG       | [9466f83af8](https://linux-hardware.org/?probe=9466f83af8) | May 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| Dell          | Latitude 7490               | [f689b559e8](https://linux-hardware.org/?probe=f689b559e8) | May 22, 2023 |
| Acer          | Aspire V3-371               | [c6276aaa0c](https://linux-hardware.org/?probe=c6276aaa0c) | May 22, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [03e6dd8808](https://linux-hardware.org/?probe=03e6dd8808) | May 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f25279745a](https://linux-hardware.org/?probe=f25279745a) | May 22, 2023 |
| Apple         | MacBookPro8,1               | [5b78800649](https://linux-hardware.org/?probe=5b78800649) | May 22, 2023 |
| Acer          | Aspire A315-43              | [926421c6be](https://linux-hardware.org/?probe=926421c6be) | May 22, 2023 |
| Apple         | MacBookPro8,1               | [a78ee7457a](https://linux-hardware.org/?probe=a78ee7457a) | May 22, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [7cba5b3595](https://linux-hardware.org/?probe=7cba5b3595) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| Framework     | Laptop                      | [7715f5f056](https://linux-hardware.org/?probe=7715f5f056) | May 22, 2023 |
| Lenovo        | ThinkPad X230 2325AC2       | [bc1633cf27](https://linux-hardware.org/?probe=bc1633cf27) | May 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [0148c19bc7](https://linux-hardware.org/?probe=0148c19bc7) | May 22, 2023 |
| Acer          | TM8573T                     | [64df92ebbe](https://linux-hardware.org/?probe=64df92ebbe) | May 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cccb529fd3](https://linux-hardware.org/?probe=cccb529fd3) | May 21, 2023 |
| Acer          | TM8573T                     | [2ea1f44eb8](https://linux-hardware.org/?probe=2ea1f44eb8) | May 21, 2023 |
| Apple         | MacBookPro14,2              | [d29f7a36f9](https://linux-hardware.org/?probe=d29f7a36f9) | May 21, 2023 |
| Acer          | Aspire A515-52G             | [a80648e2a4](https://linux-hardware.org/?probe=a80648e2a4) | May 21, 2023 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | [03afaf2468](https://linux-hardware.org/?probe=03afaf2468) | May 21, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [0b3265b088](https://linux-hardware.org/?probe=0b3265b088) | May 21, 2023 |
| Fujitsu       | LIFEBOOK S752               | [906ba8b65c](https://linux-hardware.org/?probe=906ba8b65c) | May 21, 2023 |
| Acer          | Aspire V5-572P              | [99f4730d26](https://linux-hardware.org/?probe=99f4730d26) | May 21, 2023 |
| Sony          | SVF1521B4E                  | [89c04d3b34](https://linux-hardware.org/?probe=89c04d3b34) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| Dell          | G3 3500                     | [cbe9c2f010](https://linux-hardware.org/?probe=cbe9c2f010) | May 21, 2023 |
| Lenovo        | Y50-70 20378                | [2aff70d7c9](https://linux-hardware.org/?probe=2aff70d7c9) | May 21, 2023 |
| Acer          | E1-510                      | [709c32e016](https://linux-hardware.org/?probe=709c32e016) | May 21, 2023 |
| Acer          | E1-510                      | [c18f4ac56b](https://linux-hardware.org/?probe=c18f4ac56b) | May 21, 2023 |
| Acer          | Aspire V5-572P              | [456d6c8887](https://linux-hardware.org/?probe=456d6c8887) | May 21, 2023 |
| MICROBYTE     | ezbook                      | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [157b535164](https://linux-hardware.org/?probe=157b535164) | May 20, 2023 |
| Acer          | Aspire S3                   | [b6841c9aeb](https://linux-hardware.org/?probe=b6841c9aeb) | May 20, 2023 |
| Acer          | Aspire 5739G                | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Acer          | Aspire S3                   | [3fafb0df5d](https://linux-hardware.org/?probe=3fafb0df5d) | May 20, 2023 |
| Dell          | Latitude 5285               | [0db3cfd34e](https://linux-hardware.org/?probe=0db3cfd34e) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| Dell          | Latitude E6510              | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| HP            | Pavilion dv6                | [17ac43247a](https://linux-hardware.org/?probe=17ac43247a) | May 20, 2023 |
| Acer          | Aspire 5739G                | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| Dell          | Latitude E6510              | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| Packard Be... | EasyNote MH36               | [a77cfa4947](https://linux-hardware.org/?probe=a77cfa4947) | May 20, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | [87e70e9606](https://linux-hardware.org/?probe=87e70e9606) | May 19, 2023 |
| HP            | Notebook                    | [3664846c35](https://linux-hardware.org/?probe=3664846c35) | May 19, 2023 |
| Lenovo        | ThinkPad T61 6463B45        | [a2445821f3](https://linux-hardware.org/?probe=a2445821f3) | May 19, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [c0e3ea54c0](https://linux-hardware.org/?probe=c0e3ea54c0) | May 19, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6d6cdfc735](https://linux-hardware.org/?probe=6d6cdfc735) | May 19, 2023 |
| Apple         | MacBookPro11,3              | [3de00073ba](https://linux-hardware.org/?probe=3de00073ba) | May 19, 2023 |
| Dell          | Latitude 5411               | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [749d31d44a](https://linux-hardware.org/?probe=749d31d44a) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [85da505294](https://linux-hardware.org/?probe=85da505294) | May 19, 2023 |
| HP            | 15                          | [a22d3981e2](https://linux-hardware.org/?probe=a22d3981e2) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| HP            | Pavilion dv6                | [4fb1281981](https://linux-hardware.org/?probe=4fb1281981) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Dell          | Latitude E6500              | [27213adbe8](https://linux-hardware.org/?probe=27213adbe8) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [6141537b7b](https://linux-hardware.org/?probe=6141537b7b) | May 18, 2023 |
| HP            | Laptop 14s-dq0xxx           | [6173aa2164](https://linux-hardware.org/?probe=6173aa2164) | May 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [25e9a17dd0](https://linux-hardware.org/?probe=25e9a17dd0) | May 18, 2023 |
| Dell          | XPS 13 9305                 | [3eb1bee421](https://linux-hardware.org/?probe=3eb1bee421) | May 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [eb15dc415d](https://linux-hardware.org/?probe=eb15dc415d) | May 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [b30078ae71](https://linux-hardware.org/?probe=b30078ae71) | May 18, 2023 |
| HP            | 630                         | [bd7bdf5942](https://linux-hardware.org/?probe=bd7bdf5942) | May 18, 2023 |
| Sony          | VPCEB4Z1E                   | [d1cca131ad](https://linux-hardware.org/?probe=d1cca131ad) | May 18, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d3bfab996e](https://linux-hardware.org/?probe=d3bfab996e) | May 18, 2023 |
| Dell          | Latitude E7240              | [208261238e](https://linux-hardware.org/?probe=208261238e) | May 18, 2023 |
| Dell          | Latitude E7240              | [faf148036f](https://linux-hardware.org/?probe=faf148036f) | May 18, 2023 |
| Medion        | E6232                       | [a447a0aba0](https://linux-hardware.org/?probe=a447a0aba0) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [a23a2d1c6c](https://linux-hardware.org/?probe=a23a2d1c6c) | May 18, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [aa625a94a0](https://linux-hardware.org/?probe=aa625a94a0) | May 18, 2023 |
| Valve         | Jupiter                     | [c16624e321](https://linux-hardware.org/?probe=c16624e321) | May 17, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| HP            | Laptop 14s-dq0xxx           | [0a08d453f7](https://linux-hardware.org/?probe=0a08d453f7) | May 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | [ad17e04f3b](https://linux-hardware.org/?probe=ad17e04f3b) | May 17, 2023 |
| Dell          | Latitude E7270              | [c3b39e55f4](https://linux-hardware.org/?probe=c3b39e55f4) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Dell          | Latitude 7430               | [eb576d7c2a](https://linux-hardware.org/?probe=eb576d7c2a) | May 17, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [f31be9149e](https://linux-hardware.org/?probe=f31be9149e) | May 17, 2023 |
| Dell          | XPS 13 7390                 | [51ff9a820a](https://linux-hardware.org/?probe=51ff9a820a) | May 16, 2023 |
| Dell          | XPS 13 7390                 | [e98b404c17](https://linux-hardware.org/?probe=e98b404c17) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | [1d5a340968](https://linux-hardware.org/?probe=1d5a340968) | May 16, 2023 |
| Dell          | Latitude 7430               | [d137c2d73b](https://linux-hardware.org/?probe=d137c2d73b) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c62b63f5bf](https://linux-hardware.org/?probe=c62b63f5bf) | May 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [24cb48f7d7](https://linux-hardware.org/?probe=24cb48f7d7) | May 16, 2023 |
| Acer          | Swift SFA16-41              | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [58b895e713](https://linux-hardware.org/?probe=58b895e713) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | [040fb99c20](https://linux-hardware.org/?probe=040fb99c20) | May 15, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [19feb08b89](https://linux-hardware.org/?probe=19feb08b89) | May 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0770462dab](https://linux-hardware.org/?probe=0770462dab) | May 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [61499d189f](https://linux-hardware.org/?probe=61499d189f) | May 15, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [dc5dd8c32a](https://linux-hardware.org/?probe=dc5dd8c32a) | May 15, 2023 |
| Sony          | SVF1521B4E                  | [ec03e769b8](https://linux-hardware.org/?probe=ec03e769b8) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [1573285475](https://linux-hardware.org/?probe=1573285475) | May 15, 2023 |
| Toshiba       | Satellite Pro R50-B         | [dda235ab03](https://linux-hardware.org/?probe=dda235ab03) | May 15, 2023 |
| Toshiba       | Satellite Pro R50-B         | [f9535b38b0](https://linux-hardware.org/?probe=f9535b38b0) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | [61665ffc1a](https://linux-hardware.org/?probe=61665ffc1a) | May 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [84526e9b64](https://linux-hardware.org/?probe=84526e9b64) | May 15, 2023 |
| Toshiba       | TECRA Z40-A                 | [55210b06ca](https://linux-hardware.org/?probe=55210b06ca) | May 15, 2023 |
| Acer          | Aspire 7745G                | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Apple         | MacBookPro10,1              | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| VALE          | Notebook Classic C140       | [656e811dfb](https://linux-hardware.org/?probe=656e811dfb) | May 14, 2023 |
| Acer          | Swift SF114-34              | [360db31139](https://linux-hardware.org/?probe=360db31139) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Acer          | Swift SF114-34              | [c3bbc544d3](https://linux-hardware.org/?probe=c3bbc544d3) | May 14, 2023 |
| Lenovo        | ThinkBook Plus G2 ITG 20... | [2881ffcb77](https://linux-hardware.org/?probe=2881ffcb77) | May 14, 2023 |
| Lenovo        | ThinkPad T570 20H90002GE    | [e6ff63678e](https://linux-hardware.org/?probe=e6ff63678e) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [0ea14cadea](https://linux-hardware.org/?probe=0ea14cadea) | May 14, 2023 |
| Dell          | XPS 15 7590                 | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8747e49a83](https://linux-hardware.org/?probe=8747e49a83) | May 14, 2023 |
| HP            | ENVY 15                     | [0d1450cd2d](https://linux-hardware.org/?probe=0d1450cd2d) | May 14, 2023 |
| Lenovo        | G50-45 80E3                 | [9298a8529a](https://linux-hardware.org/?probe=9298a8529a) | May 14, 2023 |
| Valve         | Jupiter                     | [6d8b04de33](https://linux-hardware.org/?probe=6d8b04de33) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1e5caac049](https://linux-hardware.org/?probe=1e5caac049) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| Fujitsu Si... | LIFEBOOK T5010              | [374128840e](https://linux-hardware.org/?probe=374128840e) | May 13, 2023 |
| Valve         | Jupiter                     | [abf57f2578](https://linux-hardware.org/?probe=abf57f2578) | May 13, 2023 |
| Valve         | Jupiter                     | [49d110c5d2](https://linux-hardware.org/?probe=49d110c5d2) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [a25f9e8d93](https://linux-hardware.org/?probe=a25f9e8d93) | May 13, 2023 |
| ASUSTek       | K53SV                       | [60d7b5acf8](https://linux-hardware.org/?probe=60d7b5acf8) | May 13, 2023 |
| HP            | Notebook                    | [ee7a6bde04](https://linux-hardware.org/?probe=ee7a6bde04) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [d2ba323017](https://linux-hardware.org/?probe=d2ba323017) | May 13, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [4b296f5c40](https://linux-hardware.org/?probe=4b296f5c40) | May 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [d90b0e6626](https://linux-hardware.org/?probe=d90b0e6626) | May 12, 2023 |
| HP            | ENVY 17                     | [9f71f0b3e1](https://linux-hardware.org/?probe=9f71f0b3e1) | May 12, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [ba177fa007](https://linux-hardware.org/?probe=ba177fa007) | May 12, 2023 |
| ASUSTek       | X555LJ                      | [f39ba53533](https://linux-hardware.org/?probe=f39ba53533) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [b054e28875](https://linux-hardware.org/?probe=b054e28875) | May 12, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [703faeb982](https://linux-hardware.org/?probe=703faeb982) | May 12, 2023 |
| HP            | OMEN by Laptop              | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| Dell          | Latitude D830               | [79c9ffb643](https://linux-hardware.org/?probe=79c9ffb643) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [870c85a9ac](https://linux-hardware.org/?probe=870c85a9ac) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [b01a016489](https://linux-hardware.org/?probe=b01a016489) | May 12, 2023 |
| HP            | Pavilion g6                 | [83693568b6](https://linux-hardware.org/?probe=83693568b6) | May 12, 2023 |
| Dell          | Vostro 15 3510              | [fc82fe9907](https://linux-hardware.org/?probe=fc82fe9907) | May 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [5d67743d33](https://linux-hardware.org/?probe=5d67743d33) | May 11, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [bfb11f92b1](https://linux-hardware.org/?probe=bfb11f92b1) | May 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [637d09143c](https://linux-hardware.org/?probe=637d09143c) | May 11, 2023 |
| HP            | OMEN by Laptop              | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| MSI           | GT70 2PC                    | [c98c889dbf](https://linux-hardware.org/?probe=c98c889dbf) | May 11, 2023 |
| Dell          | Vostro 3501                 | [c6cb7f265a](https://linux-hardware.org/?probe=c6cb7f265a) | May 11, 2023 |
| Dell          | Precision 7520              | [184802dbab](https://linux-hardware.org/?probe=184802dbab) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| TUXEDO        | Book_XA1510                 | [9aed9e823a](https://linux-hardware.org/?probe=9aed9e823a) | May 11, 2023 |
| HP            | Laptop 17-by0xxx            | [10b9d3a925](https://linux-hardware.org/?probe=10b9d3a925) | May 11, 2023 |
| HP            | Pavilion g6                 | [2eaacf14f6](https://linux-hardware.org/?probe=2eaacf14f6) | May 10, 2023 |
| ASUSTek       | X75VC                       | [cb14c4b8e0](https://linux-hardware.org/?probe=cb14c4b8e0) | May 10, 2023 |
| Lenovo        | ThinkPad W541 20EF001UGE    | [29c8170a0e](https://linux-hardware.org/?probe=29c8170a0e) | May 10, 2023 |
| Dell          | Latitude E5530 non-vPro     | [07bcb8d332](https://linux-hardware.org/?probe=07bcb8d332) | May 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b192a6461f](https://linux-hardware.org/?probe=b192a6461f) | May 10, 2023 |
| Toshiba       | Satellite Pro R50-C         | [66fe960f10](https://linux-hardware.org/?probe=66fe960f10) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57a74239f8](https://linux-hardware.org/?probe=57a74239f8) | May 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3ea1fd6554](https://linux-hardware.org/?probe=3ea1fd6554) | May 10, 2023 |
| ASUSTek       | X555LAB                     | [2710a15a04](https://linux-hardware.org/?probe=2710a15a04) | May 10, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | [d5d7d8308f](https://linux-hardware.org/?probe=d5d7d8308f) | May 10, 2023 |
| Medion        | E6232                       | [46e240ed2c](https://linux-hardware.org/?probe=46e240ed2c) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [962ca6e507](https://linux-hardware.org/?probe=962ca6e507) | May 10, 2023 |
| HP            | Laptop 17-cp0xxx            | [b32a7122fc](https://linux-hardware.org/?probe=b32a7122fc) | May 10, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [39dd8fc09a](https://linux-hardware.org/?probe=39dd8fc09a) | May 10, 2023 |
| Apple         | MacBook8,1                  | [89d87ca773](https://linux-hardware.org/?probe=89d87ca773) | May 09, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | [c0ad43f440](https://linux-hardware.org/?probe=c0ad43f440) | May 09, 2023 |
| Dell          | XPS 15 9560                 | [b904defc14](https://linux-hardware.org/?probe=b904defc14) | May 09, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | [f3572c500c](https://linux-hardware.org/?probe=f3572c500c) | May 09, 2023 |
| Acer          | Swift SF114-34              | [deab607d5b](https://linux-hardware.org/?probe=deab607d5b) | May 09, 2023 |
| Toshiba       | Satellite P500              | [16472912d5](https://linux-hardware.org/?probe=16472912d5) | May 09, 2023 |
| Dell          | Latitude 7400               | [dd232bb43b](https://linux-hardware.org/?probe=dd232bb43b) | May 09, 2023 |
| Lenovo        | IdeaPad 110-17ISK 80VL      | [61056ebf79](https://linux-hardware.org/?probe=61056ebf79) | May 09, 2023 |
| Gigabyte      | A7 K1                       | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Bluechip C... | TRAVELline B15W33           | [53091b3af6](https://linux-hardware.org/?probe=53091b3af6) | May 09, 2023 |
| Packard Be... | EasyNote TK36               | [18f7e68fb1](https://linux-hardware.org/?probe=18f7e68fb1) | May 09, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fba089b3d4](https://linux-hardware.org/?probe=fba089b3d4) | May 09, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f3abd29ef8](https://linux-hardware.org/?probe=f3abd29ef8) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Valve         | Jupiter                     | [08aba8925e](https://linux-hardware.org/?probe=08aba8925e) | May 08, 2023 |
| Medion        | E6234                       | [6c3bd7d77f](https://linux-hardware.org/?probe=6c3bd7d77f) | May 08, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [3211c828a2](https://linux-hardware.org/?probe=3211c828a2) | May 08, 2023 |
| HP            | 625                         | [956346de67](https://linux-hardware.org/?probe=956346de67) | May 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [db609197b4](https://linux-hardware.org/?probe=db609197b4) | May 08, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [0ebb311510](https://linux-hardware.org/?probe=0ebb311510) | May 08, 2023 |
| Fujitsu       | LIFEBOOK E751               | [8a3bd16269](https://linux-hardware.org/?probe=8a3bd16269) | May 08, 2023 |
| Acer          | Aspire A315-22              | [8849d7a1c9](https://linux-hardware.org/?probe=8849d7a1c9) | May 08, 2023 |
| Lenovo        | G560 0679                   | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [36334e327a](https://linux-hardware.org/?probe=36334e327a) | May 08, 2023 |
| TUXEDO        | N24_25BU                    | [9cd4e499ae](https://linux-hardware.org/?probe=9cd4e499ae) | May 07, 2023 |
| Dell          | XPS 13 9305                 | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| Medion        | E6234                       | [5afe99ed93](https://linux-hardware.org/?probe=5afe99ed93) | May 07, 2023 |
| Toshiba       | Satellite L655              | [9eef570443](https://linux-hardware.org/?probe=9eef570443) | May 07, 2023 |
| Acer          | Aspire 8930                 | [1ec5df3fc1](https://linux-hardware.org/?probe=1ec5df3fc1) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [febe8d60fc](https://linux-hardware.org/?probe=febe8d60fc) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [2e25cad4b3](https://linux-hardware.org/?probe=2e25cad4b3) | May 07, 2023 |
| Lenovo        | ThinkPad L530 24812TG       | [d95ccbf97d](https://linux-hardware.org/?probe=d95ccbf97d) | May 07, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [020041a666](https://linux-hardware.org/?probe=020041a666) | May 07, 2023 |
| MSI           | GL75 9SD                    | [522594401b](https://linux-hardware.org/?probe=522594401b) | May 07, 2023 |
| Medion        | E6417 MD99252               | [6c46322374](https://linux-hardware.org/?probe=6c46322374) | May 07, 2023 |
| Valve         | Jupiter                     | [17b055eca4](https://linux-hardware.org/?probe=17b055eca4) | May 07, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| Dell          | Precision 7720              | [9e0a1bd8ef](https://linux-hardware.org/?probe=9e0a1bd8ef) | May 06, 2023 |
| Valve         | Jupiter                     | [55acf244c5](https://linux-hardware.org/?probe=55acf244c5) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3bf20b454](https://linux-hardware.org/?probe=b3bf20b454) | May 06, 2023 |
| HP            | Laptop 17-ca0xxx            | [96099a3217](https://linux-hardware.org/?probe=96099a3217) | May 06, 2023 |
| Dell          | Latitude E6410              | [535fd92f64](https://linux-hardware.org/?probe=535fd92f64) | May 06, 2023 |
| Gigabyte      | G5 MD                       | [7ad914a8a9](https://linux-hardware.org/?probe=7ad914a8a9) | May 06, 2023 |
| Acer          | Aspire ES1-711              | [9c88de8a31](https://linux-hardware.org/?probe=9c88de8a31) | May 06, 2023 |
| Acer          | Aspire ES1-711              | [a106dc51b2](https://linux-hardware.org/?probe=a106dc51b2) | May 06, 2023 |
| Notebook      | P15SM                       | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [59cdec7fce](https://linux-hardware.org/?probe=59cdec7fce) | May 06, 2023 |
| Sony          | SVF1521M6E                  | [82f869d683](https://linux-hardware.org/?probe=82f869d683) | May 06, 2023 |
| Medion        | E6214                       | [869c63244c](https://linux-hardware.org/?probe=869c63244c) | May 06, 2023 |
| Medion        | E6214                       | [64eeb6e165](https://linux-hardware.org/?probe=64eeb6e165) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [79c33e919f](https://linux-hardware.org/?probe=79c33e919f) | May 06, 2023 |
| Acer          | TravelMate P215-53          | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | [449779fbe4](https://linux-hardware.org/?probe=449779fbe4) | May 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [ec3e2f4be9](https://linux-hardware.org/?probe=ec3e2f4be9) | May 05, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | [ffce6dd6d5](https://linux-hardware.org/?probe=ffce6dd6d5) | May 05, 2023 |
| Acer          | Aspire SW3-016              | [19f043f522](https://linux-hardware.org/?probe=19f043f522) | May 05, 2023 |
| Acer          | Aspire SW3-016              | [7996b7f419](https://linux-hardware.org/?probe=7996b7f419) | May 05, 2023 |
| Medion        | P8614                       | [831518705e](https://linux-hardware.org/?probe=831518705e) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [d016282342](https://linux-hardware.org/?probe=d016282342) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Dell          | Latitude E5430 non-vPro     | [e9cfd8b8c4](https://linux-hardware.org/?probe=e9cfd8b8c4) | May 05, 2023 |
| Acer          | Aspire A315-42              | [d8f78a98f2](https://linux-hardware.org/?probe=d8f78a98f2) | May 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [907a94ae07](https://linux-hardware.org/?probe=907a94ae07) | May 05, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [d02d56f013](https://linux-hardware.org/?probe=d02d56f013) | May 05, 2023 |
| HP            | EliteBook 8440p             | [1ba4a283b1](https://linux-hardware.org/?probe=1ba4a283b1) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [f9a56b49f3](https://linux-hardware.org/?probe=f9a56b49f3) | May 05, 2023 |
| Medion        | E11201                      | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [2d8b053492](https://linux-hardware.org/?probe=2d8b053492) | May 04, 2023 |
| HUAWEI        | MRGF-XX                     | [ca2c7ad92c](https://linux-hardware.org/?probe=ca2c7ad92c) | May 04, 2023 |
| Apple         | MacBookPro14,2              | [4124bb2dde](https://linux-hardware.org/?probe=4124bb2dde) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [cc11b2dcde](https://linux-hardware.org/?probe=cc11b2dcde) | May 04, 2023 |
| Acer          | Aspire 7530G                | [5c19c9f6e4](https://linux-hardware.org/?probe=5c19c9f6e4) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| HP            | Laptop 17-ak0xx             | [579c16cd5c](https://linux-hardware.org/?probe=579c16cd5c) | May 04, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [c83ed0c49b](https://linux-hardware.org/?probe=c83ed0c49b) | May 04, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [b8a363f717](https://linux-hardware.org/?probe=b8a363f717) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Dell          | Latitude E5570              | [6b532c004d](https://linux-hardware.org/?probe=6b532c004d) | May 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fbc24a91e6](https://linux-hardware.org/?probe=fbc24a91e6) | May 04, 2023 |
| HP            | ProBook 450 G6              | [c5927045a3](https://linux-hardware.org/?probe=c5927045a3) | May 04, 2023 |
| HP            | EliteBook 8440p             | [16028c4863](https://linux-hardware.org/?probe=16028c4863) | May 04, 2023 |
| HP            | ProBook 650 G1              | [0cbc314c84](https://linux-hardware.org/?probe=0cbc314c84) | May 04, 2023 |
| Lenovo        | IdeaPad N581 7505           | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Acer          | Swift SF314-56G             | [460a286d9a](https://linux-hardware.org/?probe=460a286d9a) | May 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [7ffc12366e](https://linux-hardware.org/?probe=7ffc12366e) | May 03, 2023 |
| HP            | Pavilion dv6                | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| ASUSTek       | X200MA                      | [31e08853ae](https://linux-hardware.org/?probe=31e08853ae) | May 03, 2023 |
| Dell          | Latitude 5414               | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| Apple         | MacBookPro12,1              | [ff5236b993](https://linux-hardware.org/?probe=ff5236b993) | May 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [1e70580006](https://linux-hardware.org/?probe=1e70580006) | May 02, 2023 |
| Acer          | Aspire V5-531               | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| Acer          | Aspire V5-572P              | [a2e6cae633](https://linux-hardware.org/?probe=a2e6cae633) | May 02, 2023 |
| Acer          | Aspire V5-572P              | [00d2e57fb9](https://linux-hardware.org/?probe=00d2e57fb9) | May 02, 2023 |
| Acer          | Aspire E1-571               | [46ecc78df6](https://linux-hardware.org/?probe=46ecc78df6) | May 02, 2023 |
| HP            | EliteBook 2540p             | [a0b1299baa](https://linux-hardware.org/?probe=a0b1299baa) | May 02, 2023 |
| Dell          | Studio 1747                 | [6f140484a6](https://linux-hardware.org/?probe=6f140484a6) | May 02, 2023 |
| Unknown       | Unknown                     | [5434cb77bf](https://linux-hardware.org/?probe=5434cb77bf) | May 02, 2023 |
| Lenovo        | V15-IGL 82C3                | [583642a695](https://linux-hardware.org/?probe=583642a695) | May 02, 2023 |
| Dell          | Latitude 5520               | [394f247286](https://linux-hardware.org/?probe=394f247286) | May 02, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Dell          | Latitude E6540              | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Acer          | Aspire E1-571               | [7b4e78233a](https://linux-hardware.org/?probe=7b4e78233a) | May 01, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [c604e4ce30](https://linux-hardware.org/?probe=c604e4ce30) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [c5c9bbda3d](https://linux-hardware.org/?probe=c5c9bbda3d) | May 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e9bd630708](https://linux-hardware.org/?probe=e9bd630708) | May 01, 2023 |
| Dell          | Studio 1555                 | [4f9f0dc9bf](https://linux-hardware.org/?probe=4f9f0dc9bf) | May 01, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [15c04364fa](https://linux-hardware.org/?probe=15c04364fa) | May 01, 2023 |
| ASUSTek       | K53U                        | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Dell          | Inspiron 1090               | [690e8bfe3a](https://linux-hardware.org/?probe=690e8bfe3a) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [3c82fea068](https://linux-hardware.org/?probe=3c82fea068) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [44bea19730](https://linux-hardware.org/?probe=44bea19730) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [3de4215710](https://linux-hardware.org/?probe=3de4215710) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [6b61472a4a](https://linux-hardware.org/?probe=6b61472a4a) | May 01, 2023 |
| Sony          | SVF1521C6EW                 | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| Acer          | Aspire A315-33              | [fdba59c054](https://linux-hardware.org/?probe=fdba59c054) | Apr 30, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [1714bffa0e](https://linux-hardware.org/?probe=1714bffa0e) | Apr 30, 2023 |
| ASUSTek       | X751SA                      | [5192130c0e](https://linux-hardware.org/?probe=5192130c0e) | Apr 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [32b3bf20de](https://linux-hardware.org/?probe=32b3bf20de) | Apr 30, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | [874f19f26e](https://linux-hardware.org/?probe=874f19f26e) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9876205c45](https://linux-hardware.org/?probe=9876205c45) | Apr 30, 2023 |
| Medion        | E6214                       | [7bb9f39d76](https://linux-hardware.org/?probe=7bb9f39d76) | Apr 30, 2023 |
| Medion        | E6214                       | [39747632e6](https://linux-hardware.org/?probe=39747632e6) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E734               | [f99ecceaeb](https://linux-hardware.org/?probe=f99ecceaeb) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E734               | [31fa8aa587](https://linux-hardware.org/?probe=31fa8aa587) | Apr 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [df9cc0160a](https://linux-hardware.org/?probe=df9cc0160a) | Apr 30, 2023 |
| HP            | 255 G6 Notebook PC          | [d99135522b](https://linux-hardware.org/?probe=d99135522b) | Apr 30, 2023 |
| Dell          | XPS 13 7390                 | [c5000ec967](https://linux-hardware.org/?probe=c5000ec967) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [2bc3c5303f](https://linux-hardware.org/?probe=2bc3c5303f) | Apr 30, 2023 |
| ASUSTek       | X751MA                      | [c952010dbb](https://linux-hardware.org/?probe=c952010dbb) | Apr 29, 2023 |
| Medion        | X681X                       | [f65ca1e461](https://linux-hardware.org/?probe=f65ca1e461) | Apr 29, 2023 |
| Acer          | Aspire 8950G                | [348a7d728c](https://linux-hardware.org/?probe=348a7d728c) | Apr 29, 2023 |
| Dell          | Inspiron 7773               | [19741ac2ea](https://linux-hardware.org/?probe=19741ac2ea) | Apr 29, 2023 |
| Lenovo        | G50-70 20351                | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| Medion        | X6816                       | [2c1807dad7](https://linux-hardware.org/?probe=2c1807dad7) | Apr 29, 2023 |
| Dell          | Latitude E5450              | [85fb3ec2fd](https://linux-hardware.org/?probe=85fb3ec2fd) | Apr 28, 2023 |
| Acer          | Aspire ES1-731              | [140e5eb8fc](https://linux-hardware.org/?probe=140e5eb8fc) | Apr 28, 2023 |
| Notebook      | W35xSTQ_370ST               | [a68f02482d](https://linux-hardware.org/?probe=a68f02482d) | Apr 28, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [a8deb2307c](https://linux-hardware.org/?probe=a8deb2307c) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Acer          | Swift SF314-59              | [a84de33c38](https://linux-hardware.org/?probe=a84de33c38) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | [a1584c31ec](https://linux-hardware.org/?probe=a1584c31ec) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | [5f191f449f](https://linux-hardware.org/?probe=5f191f449f) | Apr 28, 2023 |
| Acer          | Aspire V5-572P              | [4fa79fb180](https://linux-hardware.org/?probe=4fa79fb180) | Apr 28, 2023 |
| Acer          | Aspire V5-572P              | [fdc85a159b](https://linux-hardware.org/?probe=fdc85a159b) | Apr 28, 2023 |
| ASUSTek       | K54C                        | [7223b97463](https://linux-hardware.org/?probe=7223b97463) | Apr 27, 2023 |
| Dell          | XPS 13 9350                 | [aea99797db](https://linux-hardware.org/?probe=aea99797db) | Apr 27, 2023 |
| ASUSTek       | X751MA                      | [eb9967626a](https://linux-hardware.org/?probe=eb9967626a) | Apr 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [dd5391c20d](https://linux-hardware.org/?probe=dd5391c20d) | Apr 27, 2023 |
| Dell          | Inspiron 16 5630            | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Lenovo        | ThinkPad R61 8943DJG        | [afc3fc578e](https://linux-hardware.org/?probe=afc3fc578e) | Apr 27, 2023 |
| MSI           | PE60 6QE                    | [1a5ae975ee](https://linux-hardware.org/?probe=1a5ae975ee) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| HP            | Compaq 6910p                | [049253c0c8](https://linux-hardware.org/?probe=049253c0c8) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e1b7846c92](https://linux-hardware.org/?probe=e1b7846c92) | Apr 27, 2023 |
| Apple         | MacBookAir6,1               | [c0f967c0bc](https://linux-hardware.org/?probe=c0f967c0bc) | Apr 27, 2023 |
| Acer          | Aspire E1-571               | [c95605ef8e](https://linux-hardware.org/?probe=c95605ef8e) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [21577119ad](https://linux-hardware.org/?probe=21577119ad) | Apr 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [8ab4a35e8c](https://linux-hardware.org/?probe=8ab4a35e8c) | Apr 26, 2023 |
| Sony          | SVD1322X2EW                 | [2574ef07fb](https://linux-hardware.org/?probe=2574ef07fb) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [4a6eed684e](https://linux-hardware.org/?probe=4a6eed684e) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Apple         | MacBookPro14,2              | [4e1caf5a7a](https://linux-hardware.org/?probe=4e1caf5a7a) | Apr 26, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [7274cefe89](https://linux-hardware.org/?probe=7274cefe89) | Apr 26, 2023 |
| Dell          | Latitude E6440              | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [7ca1ebbe7f](https://linux-hardware.org/?probe=7ca1ebbe7f) | Apr 26, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | [2d40a711f9](https://linux-hardware.org/?probe=2d40a711f9) | Apr 26, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [67a77ff775](https://linux-hardware.org/?probe=67a77ff775) | Apr 26, 2023 |
| ASUSTek       | X550LB                      | [053e93702b](https://linux-hardware.org/?probe=053e93702b) | Apr 26, 2023 |
| Google        | Bobba                       | [5eb10d8965](https://linux-hardware.org/?probe=5eb10d8965) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| Acer          | Aspire R7-571G              | [d4220bc210](https://linux-hardware.org/?probe=d4220bc210) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| Sony          | VPCS13V9E                   | [3c1551d7be](https://linux-hardware.org/?probe=3c1551d7be) | Apr 25, 2023 |
| ASUSTek       | K52JK                       | [dd0ced2f54](https://linux-hardware.org/?probe=dd0ced2f54) | Apr 25, 2023 |
| HP            | 255 G5 Notebook PC          | [c542c2df7e](https://linux-hardware.org/?probe=c542c2df7e) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [c0d8e6e6b5](https://linux-hardware.org/?probe=c0d8e6e6b5) | Apr 25, 2023 |
| Lenovo        | ThinkPad Edge E545 20B20... | [fd66f3852a](https://linux-hardware.org/?probe=fd66f3852a) | Apr 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [554f32b909](https://linux-hardware.org/?probe=554f32b909) | Apr 25, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [2732f4b096](https://linux-hardware.org/?probe=2732f4b096) | Apr 25, 2023 |
| Fujitsu       | LIFEBOOK S935               | [418c2c626e](https://linux-hardware.org/?probe=418c2c626e) | Apr 25, 2023 |
| ASUSTek       | X510UQR                     | [4a2e357ace](https://linux-hardware.org/?probe=4a2e357ace) | Apr 24, 2023 |
| HUAWEI        | HN-WX9X                     | [d07874c829](https://linux-hardware.org/?probe=d07874c829) | Apr 24, 2023 |
| Fujitsu       | LIFEBOOK S751               | [e01b26f35f](https://linux-hardware.org/?probe=e01b26f35f) | Apr 24, 2023 |
| Dell          | Latitude E6540              | [ba8579b1a5](https://linux-hardware.org/?probe=ba8579b1a5) | Apr 24, 2023 |
| Fujitsu       | LIFEBOOK S751               | [07e4819355](https://linux-hardware.org/?probe=07e4819355) | Apr 24, 2023 |
| Acer          | Aspire A515-47              | [35a591e26a](https://linux-hardware.org/?probe=35a591e26a) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| Hampoo        | Cherry Trail CR V200        | [f3d90b0d4a](https://linux-hardware.org/?probe=f3d90b0d4a) | Apr 23, 2023 |
| HP            | 350 G2                      | [ffa4ab3dc0](https://linux-hardware.org/?probe=ffa4ab3dc0) | Apr 23, 2023 |
| Valve         | Jupiter                     | [7501c5e0e4](https://linux-hardware.org/?probe=7501c5e0e4) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | [f6fe80f275](https://linux-hardware.org/?probe=f6fe80f275) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| Sony          | SVD1322X2EW                 | [1652ce4c8f](https://linux-hardware.org/?probe=1652ce4c8f) | Apr 23, 2023 |
| Apple         | MacBookPro11,3              | [db4dd7bc7a](https://linux-hardware.org/?probe=db4dd7bc7a) | Apr 23, 2023 |
| eMachines     | E725                        | [7f35646c99](https://linux-hardware.org/?probe=7f35646c99) | Apr 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [af2d38aec0](https://linux-hardware.org/?probe=af2d38aec0) | Apr 23, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Dell          | Latitude 5290               | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| Dell          | Latitude E7240              | [1b5828d441](https://linux-hardware.org/?probe=1b5828d441) | Apr 23, 2023 |
| Lenovo        | ThinkPad T410 2537AT1       | [8e7059747e](https://linux-hardware.org/?probe=8e7059747e) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [241411df47](https://linux-hardware.org/?probe=241411df47) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Sony          | VPCF13M1E                   | [023cbeeac3](https://linux-hardware.org/?probe=023cbeeac3) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | [5a626f5754](https://linux-hardware.org/?probe=5a626f5754) | Apr 23, 2023 |
| Valve         | Jupiter                     | [1ec068394a](https://linux-hardware.org/?probe=1ec068394a) | Apr 23, 2023 |
| ASUSTek       | K52JU                       | [74fdb1fa53](https://linux-hardware.org/?probe=74fdb1fa53) | Apr 23, 2023 |
| Valve         | Jupiter                     | [b34ccafbdf](https://linux-hardware.org/?probe=b34ccafbdf) | Apr 23, 2023 |
| Dell          | Latitude E6420              | [ef822feab1](https://linux-hardware.org/?probe=ef822feab1) | Apr 22, 2023 |
| Dell          | Latitude E6420              | [475a16531a](https://linux-hardware.org/?probe=475a16531a) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| Dell          | Latitude E6500              | [5de8825606](https://linux-hardware.org/?probe=5de8825606) | Apr 22, 2023 |
| Medion        | Akoya E7416T                | [da5ea2c44b](https://linux-hardware.org/?probe=da5ea2c44b) | Apr 22, 2023 |
| Acer          | Aspire E5-772               | [edfa9fcbef](https://linux-hardware.org/?probe=edfa9fcbef) | Apr 22, 2023 |
| Lenovo        | Z50-70 20354                | [76f54ae42f](https://linux-hardware.org/?probe=76f54ae42f) | Apr 22, 2023 |
| Dell          | XPS 15 9550                 | [2defeff264](https://linux-hardware.org/?probe=2defeff264) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [afdab44276](https://linux-hardware.org/?probe=afdab44276) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [1f6e58080a](https://linux-hardware.org/?probe=1f6e58080a) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| Dell          | Latitude E6330              | [da6f0379c1](https://linux-hardware.org/?probe=da6f0379c1) | Apr 22, 2023 |
| Lenovo        | ThinkPad X230T 343824G      | [2df9760e40](https://linux-hardware.org/?probe=2df9760e40) | Apr 22, 2023 |
| Acer          | Extensa 5635Z               | [015e857f63](https://linux-hardware.org/?probe=015e857f63) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [63cafebe06](https://linux-hardware.org/?probe=63cafebe06) | Apr 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2a507e00bf](https://linux-hardware.org/?probe=2a507e00bf) | Apr 21, 2023 |
| Gigabyte      | AERO 16 KE5                 | [9e4fe316b8](https://linux-hardware.org/?probe=9e4fe316b8) | Apr 21, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [52cfdbde2d](https://linux-hardware.org/?probe=52cfdbde2d) | Apr 21, 2023 |
| ASUSTek       | N53SN                       | [7c0a7d4494](https://linux-hardware.org/?probe=7c0a7d4494) | Apr 21, 2023 |
| Medion        | S15449                      | [c63e98624a](https://linux-hardware.org/?probe=c63e98624a) | Apr 21, 2023 |
| Medion        | S15449                      | [914511ca07](https://linux-hardware.org/?probe=914511ca07) | Apr 21, 2023 |
| Dell          | Latitude E6500              | [363b443628](https://linux-hardware.org/?probe=363b443628) | Apr 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6dcb6d41ef](https://linux-hardware.org/?probe=6dcb6d41ef) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [036616c992](https://linux-hardware.org/?probe=036616c992) | Apr 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c46312dc86](https://linux-hardware.org/?probe=c46312dc86) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [cb40e046d8](https://linux-hardware.org/?probe=cb40e046d8) | Apr 21, 2023 |
| Dell          | Precision 3550              | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| Packard Be... | EasyNote TSX62HR            | [7e7dbc9acd](https://linux-hardware.org/?probe=7e7dbc9acd) | Apr 21, 2023 |
| Dell          | Latitude E6420              | [5e3466ce98](https://linux-hardware.org/?probe=5e3466ce98) | Apr 21, 2023 |
| HP            | Pavilion dv7                | [def294f74c](https://linux-hardware.org/?probe=def294f74c) | Apr 20, 2023 |
| ASUSTek       | N53SN                       | [ad32ff5e4a](https://linux-hardware.org/?probe=ad32ff5e4a) | Apr 20, 2023 |
| Google        | Akali 360                   | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| MSI           | GF63 Thin 9SC               | [fbed7350fc](https://linux-hardware.org/?probe=fbed7350fc) | Apr 20, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [8e02f43636](https://linux-hardware.org/?probe=8e02f43636) | Apr 20, 2023 |
| HP            | Laptop 17-ca0xxx            | [50f90c0b1f](https://linux-hardware.org/?probe=50f90c0b1f) | Apr 20, 2023 |
| Fujitsu       | LIFEBOOK A557               | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Acer          | Aspire E1-571G              | [e062ca363c](https://linux-hardware.org/?probe=e062ca363c) | Apr 20, 2023 |
| HP            | 250 G8 Notebook PC          | [e57b4bd7fa](https://linux-hardware.org/?probe=e57b4bd7fa) | Apr 20, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [65a009e9dd](https://linux-hardware.org/?probe=65a009e9dd) | Apr 20, 2023 |
| Acer          | Extensa 2540                | [c47272dcf1](https://linux-hardware.org/?probe=c47272dcf1) | Apr 19, 2023 |
| ASUSTek       | N501VW                      | [a31036cae1](https://linux-hardware.org/?probe=a31036cae1) | Apr 19, 2023 |
| TUXEDO        | Book XUX7 Gen11             | [c92f90cd3b](https://linux-hardware.org/?probe=c92f90cd3b) | Apr 19, 2023 |
| Lenovo        | G50-30 80G0                 | [42cb984b27](https://linux-hardware.org/?probe=42cb984b27) | Apr 19, 2023 |
| Dell          | Latitude 7490               | [90177fdac8](https://linux-hardware.org/?probe=90177fdac8) | Apr 19, 2023 |
| Dell          | Latitude 7490               | [182c7ea2b4](https://linux-hardware.org/?probe=182c7ea2b4) | Apr 19, 2023 |
| Valve         | Jupiter                     | [b7ba4129b2](https://linux-hardware.org/?probe=b7ba4129b2) | Apr 19, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [69b2b1c95f](https://linux-hardware.org/?probe=69b2b1c95f) | Apr 19, 2023 |
| Acer          | Aspire A315-24P             | [f48f292cd5](https://linux-hardware.org/?probe=f48f292cd5) | Apr 19, 2023 |
| Dell          | Precision 3550              | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [be217cbc1e](https://linux-hardware.org/?probe=be217cbc1e) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d5e90c4b14](https://linux-hardware.org/?probe=d5e90c4b14) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c100e01f6](https://linux-hardware.org/?probe=5c100e01f6) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [67030bc167](https://linux-hardware.org/?probe=67030bc167) | Apr 19, 2023 |
| HP            | Pavilion g6                 | [7a96ad05f1](https://linux-hardware.org/?probe=7a96ad05f1) | Apr 19, 2023 |
| Dell          | XPS 13 7390                 | [357c45c81c](https://linux-hardware.org/?probe=357c45c81c) | Apr 19, 2023 |
| Apple         | MacBookAir6,1               | [5a600ce01b](https://linux-hardware.org/?probe=5a600ce01b) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4185aada87](https://linux-hardware.org/?probe=4185aada87) | Apr 19, 2023 |
| Dell          | Latitude 5520               | [afe27daf93](https://linux-hardware.org/?probe=afe27daf93) | Apr 19, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | [315be40dae](https://linux-hardware.org/?probe=315be40dae) | Apr 18, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [3b3f4afdd8](https://linux-hardware.org/?probe=3b3f4afdd8) | Apr 18, 2023 |
| Acer          | TravelMate 7750             | [16afdc422d](https://linux-hardware.org/?probe=16afdc422d) | Apr 18, 2023 |
| Tactus        | GeoBook 140                 | [704da241f5](https://linux-hardware.org/?probe=704da241f5) | Apr 18, 2023 |
| Valve         | Jupiter                     | [80792055d4](https://linux-hardware.org/?probe=80792055d4) | Apr 18, 2023 |
| HP            | Laptop 17-cn0xxx            | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [67a6474ece](https://linux-hardware.org/?probe=67a6474ece) | Apr 18, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [3166a23ce1](https://linux-hardware.org/?probe=3166a23ce1) | Apr 18, 2023 |
| Fujitsu       | LIFEBOOK U7510              | [21605e555f](https://linux-hardware.org/?probe=21605e555f) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Apple         | MacBookPro14,2              | [26a430e092](https://linux-hardware.org/?probe=26a430e092) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| Samsung       | 750XDA                      | [89f13174bc](https://linux-hardware.org/?probe=89f13174bc) | Apr 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [0dde7d44fb](https://linux-hardware.org/?probe=0dde7d44fb) | Apr 18, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [146c678131](https://linux-hardware.org/?probe=146c678131) | Apr 18, 2023 |
| HP            | Pavilion g6                 | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| Medion        | P6634                       | [bb900074b5](https://linux-hardware.org/?probe=bb900074b5) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Acer          | Aspire 3820                 | [2be4b1b525](https://linux-hardware.org/?probe=2be4b1b525) | Apr 16, 2023 |
| HP            | ENVY Laptop 17-cg1xxx       | [e4fda598c3](https://linux-hardware.org/?probe=e4fda598c3) | Apr 16, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [66104cc9cf](https://linux-hardware.org/?probe=66104cc9cf) | Apr 16, 2023 |
| Acer          | Aspire 7736                 | [0f53f9450f](https://linux-hardware.org/?probe=0f53f9450f) | Apr 16, 2023 |
| ASUSTek       | K52F                        | [a6b8e3a78c](https://linux-hardware.org/?probe=a6b8e3a78c) | Apr 16, 2023 |
| Acer          | Aspire V3-772               | [a44b73c5e5](https://linux-hardware.org/?probe=a44b73c5e5) | Apr 16, 2023 |
| Acer          | Aspire V3-772               | [5dec93d2ba](https://linux-hardware.org/?probe=5dec93d2ba) | Apr 16, 2023 |
| Medion        | E6214                       | [ff06e74c6d](https://linux-hardware.org/?probe=ff06e74c6d) | Apr 16, 2023 |
| Dell          | XPS 13 9305                 | [838519057f](https://linux-hardware.org/?probe=838519057f) | Apr 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [325fbee473](https://linux-hardware.org/?probe=325fbee473) | Apr 16, 2023 |
| Medion        | E6214                       | [ab33cd63b8](https://linux-hardware.org/?probe=ab33cd63b8) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5f4a346d92](https://linux-hardware.org/?probe=5f4a346d92) | Apr 16, 2023 |
| Medion        | S14409                      | [d031a8b813](https://linux-hardware.org/?probe=d031a8b813) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [411186569d](https://linux-hardware.org/?probe=411186569d) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d86218a8d1](https://linux-hardware.org/?probe=d86218a8d1) | Apr 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b1b447dbbf](https://linux-hardware.org/?probe=b1b447dbbf) | Apr 16, 2023 |
| Dell          | Latitude E6520              | [4cce894e16](https://linux-hardware.org/?probe=4cce894e16) | Apr 16, 2023 |
| LG Electro... | X120-G.C7VPG                | [2ba90d32b2](https://linux-hardware.org/?probe=2ba90d32b2) | Apr 16, 2023 |
| Sony          | VPCCA1S1E                   | [05ab5df066](https://linux-hardware.org/?probe=05ab5df066) | Apr 16, 2023 |
| Dell          | Precision M4500             | [52f0958abf](https://linux-hardware.org/?probe=52f0958abf) | Apr 15, 2023 |
| Dell          | Precision M4500             | [0d948fdd8a](https://linux-hardware.org/?probe=0d948fdd8a) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Fujitsu Si... | ESPRIMO Mobile X9515        | [82ffd0e4bd](https://linux-hardware.org/?probe=82ffd0e4bd) | Apr 15, 2023 |
| Sony          | VPCCA1S1E                   | [30625007d9](https://linux-hardware.org/?probe=30625007d9) | Apr 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [861920db51](https://linux-hardware.org/?probe=861920db51) | Apr 15, 2023 |
| Sony          | VPCSB1V9E                   | [2764fa4b5d](https://linux-hardware.org/?probe=2764fa4b5d) | Apr 15, 2023 |
| Apple         | MacBookAir6,1               | [c649f1b898](https://linux-hardware.org/?probe=c649f1b898) | Apr 15, 2023 |
| Acer          | Aspire ES1-731              | [774333b753](https://linux-hardware.org/?probe=774333b753) | Apr 15, 2023 |
| GPD           | G1619-01                    | [2edac2c38e](https://linux-hardware.org/?probe=2edac2c38e) | Apr 15, 2023 |
| Toshiba       | TECRA R950                  | [8639e17658](https://linux-hardware.org/?probe=8639e17658) | Apr 14, 2023 |
| Acer          | Swift SF314-511             | [f960c27052](https://linux-hardware.org/?probe=f960c27052) | Apr 14, 2023 |
| Acer          | Aspire V3-772               | [da455f59df](https://linux-hardware.org/?probe=da455f59df) | Apr 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| Lenovo        | ThinkPad X250 20CLS0YR00    | [59dd927928](https://linux-hardware.org/?probe=59dd927928) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6b11fc87a5](https://linux-hardware.org/?probe=6b11fc87a5) | Apr 14, 2023 |
| HP            | Elite x2 1012 G1            | [3d58a731c0](https://linux-hardware.org/?probe=3d58a731c0) | Apr 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [67ef588216](https://linux-hardware.org/?probe=67ef588216) | Apr 14, 2023 |
| Samsung       | 750XDA                      | [e447451a7a](https://linux-hardware.org/?probe=e447451a7a) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| HP            | 255 G8 Notebook PC          | [58ec498e8f](https://linux-hardware.org/?probe=58ec498e8f) | Apr 14, 2023 |
| HP            | Laptop 17-cp2xxx            | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [5ef7e46837](https://linux-hardware.org/?probe=5ef7e46837) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | [5221d5c433](https://linux-hardware.org/?probe=5221d5c433) | Apr 14, 2023 |
| Dell          | Latitude E6330              | [71eafecde4](https://linux-hardware.org/?probe=71eafecde4) | Apr 14, 2023 |
| Sony          | VGN-NR11Z_T                 | [d7d5674aa5](https://linux-hardware.org/?probe=d7d5674aa5) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| Lenovo        | ThinkPad T460 20FMS0E22C    | [ee911053e5](https://linux-hardware.org/?probe=ee911053e5) | Apr 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U747               | [489760398d](https://linux-hardware.org/?probe=489760398d) | Apr 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| Acer          | Aspire A315-56              | [8c2cc310b2](https://linux-hardware.org/?probe=8c2cc310b2) | Apr 13, 2023 |
| Dell          | Latitude 5520               | [d3422967cd](https://linux-hardware.org/?probe=d3422967cd) | Apr 13, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f983dadfeb](https://linux-hardware.org/?probe=f983dadfeb) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [d809f15d99](https://linux-hardware.org/?probe=d809f15d99) | Apr 12, 2023 |
| Acer          | Aspire 5733Z                | [b42b19277c](https://linux-hardware.org/?probe=b42b19277c) | Apr 12, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b98cc92cd1](https://linux-hardware.org/?probe=b98cc92cd1) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [468d9ef4bf](https://linux-hardware.org/?probe=468d9ef4bf) | Apr 12, 2023 |
| Acer          | Aspire ES1-731              | [3ea34efd72](https://linux-hardware.org/?probe=3ea34efd72) | Apr 12, 2023 |
| Acer          | TravelMate P253             | [e07f3af414](https://linux-hardware.org/?probe=e07f3af414) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| HP            | Compaq CQ58                 | [77ae8df47c](https://linux-hardware.org/?probe=77ae8df47c) | Apr 11, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [ea2aa5245d](https://linux-hardware.org/?probe=ea2aa5245d) | Apr 11, 2023 |
| HP            | Compaq CQ58                 | [31975ede32](https://linux-hardware.org/?probe=31975ede32) | Apr 11, 2023 |
| Valve         | Jupiter                     | [c9f69e03d8](https://linux-hardware.org/?probe=c9f69e03d8) | Apr 11, 2023 |
| Dell          | XPS 13 7390                 | [da86532b55](https://linux-hardware.org/?probe=da86532b55) | Apr 11, 2023 |
| Acer          | Aspire 5738                 | [c039220e20](https://linux-hardware.org/?probe=c039220e20) | Apr 11, 2023 |
| Packard Be... | EasyNote LS11HR             | [56f4b51911](https://linux-hardware.org/?probe=56f4b51911) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [b7c2bb88b3](https://linux-hardware.org/?probe=b7c2bb88b3) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [436e7b8903](https://linux-hardware.org/?probe=436e7b8903) | Apr 10, 2023 |
| HP            | EliteBook 2170p             | [34f1e1686e](https://linux-hardware.org/?probe=34f1e1686e) | Apr 10, 2023 |
| TUXEDO        | Book XP1511                 | [5f5ee54a58](https://linux-hardware.org/?probe=5f5ee54a58) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [fec574fe0d](https://linux-hardware.org/?probe=fec574fe0d) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [f97c4e6d47](https://linux-hardware.org/?probe=f97c4e6d47) | Apr 10, 2023 |
| HP            | Pavilion 15                 | [cd77493427](https://linux-hardware.org/?probe=cd77493427) | Apr 09, 2023 |
| Apple         | MacBookPro5,3               | [7cc7bacd89](https://linux-hardware.org/?probe=7cc7bacd89) | Apr 09, 2023 |
| Apple         | MacBookPro11,4              | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [85dce7d0b2](https://linux-hardware.org/?probe=85dce7d0b2) | Apr 09, 2023 |
| Dell          | XPS 13 9343                 | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d261eb3697](https://linux-hardware.org/?probe=d261eb3697) | Apr 09, 2023 |
| HP            | ENVY 15                     | [5ecc7b36c8](https://linux-hardware.org/?probe=5ecc7b36c8) | Apr 09, 2023 |
| ASUSTek       | G751JT                      | [91ad3a3599](https://linux-hardware.org/?probe=91ad3a3599) | Apr 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1ab81a719b](https://linux-hardware.org/?probe=1ab81a719b) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | [37849126d4](https://linux-hardware.org/?probe=37849126d4) | Apr 08, 2023 |
| Acer          | Aspire E5-573               | [368e4f8489](https://linux-hardware.org/?probe=368e4f8489) | Apr 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [99305e0876](https://linux-hardware.org/?probe=99305e0876) | Apr 07, 2023 |
| Apple         | MacBook5,1                  | [cc4ff224bb](https://linux-hardware.org/?probe=cc4ff224bb) | Apr 07, 2023 |
| Notebook      | NJ50_70CU                   | [0ad152ba3c](https://linux-hardware.org/?probe=0ad152ba3c) | Apr 07, 2023 |
| Lenovo        | ThinkPad T450 20BUA05900    | [e771177cca](https://linux-hardware.org/?probe=e771177cca) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [6d50e55675](https://linux-hardware.org/?probe=6d50e55675) | Apr 07, 2023 |
| Acer          | Swift SF314-55G             | [e15eaec4c0](https://linux-hardware.org/?probe=e15eaec4c0) | Apr 07, 2023 |
| Notebook      | NL5xNU                      | [3d65b6c046](https://linux-hardware.org/?probe=3d65b6c046) | Apr 07, 2023 |
| HP            | ProBook 650 G4              | [0e9b21ff7e](https://linux-hardware.org/?probe=0e9b21ff7e) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK S935               | [e7ba943509](https://linux-hardware.org/?probe=e7ba943509) | Apr 07, 2023 |
| HP            | EliteBook 820 G4            | [9a07514bba](https://linux-hardware.org/?probe=9a07514bba) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [a74c66fc15](https://linux-hardware.org/?probe=a74c66fc15) | Apr 07, 2023 |
| Dell          | Latitude E5570              | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [46990342e8](https://linux-hardware.org/?probe=46990342e8) | Apr 06, 2023 |
| Acer          | TravelMate 5735Z            | [6d0065dea2](https://linux-hardware.org/?probe=6d0065dea2) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK E746               | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Dell          | Latitude 5531               | [8d3458bff6](https://linux-hardware.org/?probe=8d3458bff6) | Apr 06, 2023 |
| Unknown       | Unknown                     | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 1407      | 13.14%  |
| Ubuntu 18.04                 | 645       | 6.02%   |
| Ubuntu 22.04                 | 544       | 5.08%   |
| Linux Mint 20.3              | 303       | 2.83%   |
| Linux Mint 20.2              | 303       | 2.83%   |
| Debian 11                    | 281       | 2.62%   |
| OpenMandriva 4.2             | 254       | 2.37%   |
| OpenMandriva 4.3             | 243       | 2.27%   |
| Linux Mint 21.1              | 229       | 2.14%   |
| Linux Mint 20.1              | 201       | 1.88%   |
| Linux Mint 20                | 175       | 1.63%   |
| Manjaro                      | 173       | 1.62%   |
| Zorin 16                     | 171       | 1.6%    |
| Ubuntu 21.10                 | 162       | 1.51%   |
| Ubuntu 20.10                 | 160       | 1.49%   |
| Linux Mint 19.3              | 158       | 1.48%   |
| Arch Rolling                 | 158       | 1.48%   |
| Arch                         | 146       | 1.36%   |
| Xubuntu 20.04                | 138       | 1.29%   |
| KDE neon 20.04               | 118       | 1.1%    |
| Linux Mint 21                | 113       | 1.05%   |
| Ubuntu 22.10                 | 112       | 1.05%   |
| Ubuntu 19.10                 | 112       | 1.05%   |
| Pop!_OS 22.04                | 103       | 0.96%   |
| Ubuntu 19.04                 | 102       | 0.95%   |
| Ubuntu 21.04                 | 99        | 0.92%   |
| openSUSE Tumbleweed-XXXXXXXX | 93        | 0.87%   |
| Fedora 37                    | 90        | 0.84%   |
| OpenMandriva 23.01           | 86        | 0.8%    |
| Fedora 36                    | 86        | 0.8%    |
| BlackPanther 18.1            | 84        | 0.78%   |
| OpenMandriva 23.03           | 82        | 0.77%   |
| Debian 10                    | 78        | 0.73%   |
| ArcoLinux Rolling            | 76        | 0.71%   |
| Fedora 33                    | 72        | 0.67%   |
| Pop!_OS 20.10                | 67        | 0.63%   |
| Kubuntu 20.04                | 66        | 0.62%   |
| Zorin 15                     | 65        | 0.61%   |
| Xubuntu 18.04                | 65        | 0.61%   |
| Fedora 32                    | 63        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3263      | 32.41%  |
| Linux Mint    | 1496      | 14.86%  |
| OpenMandriva  | 707       | 7.02%   |
| Debian        | 490       | 4.87%   |
| Fedora        | 460       | 4.57%   |
| Manjaro       | 402       | 3.99%   |
| Pop!_OS       | 306       | 3.04%   |
| Arch          | 299       | 2.97%   |
| Xubuntu       | 290       | 2.88%   |
| Zorin         | 248       | 2.46%   |
| Kubuntu       | 221       | 2.2%    |
| ROSA          | 186       | 1.85%   |
| openSUSE      | 168       | 1.67%   |
| KDE neon      | 160       | 1.59%   |
| Endless       | 105       | 1.04%   |
| Elementary    | 102       | 1.01%   |
| BlackPanther  | 93        | 0.92%   |
| SteamOS       | 87        | 0.86%   |
| Gentoo        | 85        | 0.84%   |
| Ubuntu MATE   | 84        | 0.83%   |
| ArcoLinux     | 84        | 0.83%   |
| Kali          | 69        | 0.69%   |
| LMDE          | 63        | 0.63%   |
| Ubuntu Budgie | 61        | 0.61%   |
| Lubuntu       | 57        | 0.57%   |
| Ubuntu Unity  | 52        | 0.52%   |
| MX            | 40        | 0.4%    |
| EndeavourOS   | 40        | 0.4%    |
| TUXEDO OS     | 26        | 0.26%   |
| Garuda Linux  | 26        | 0.26%   |
| Clear Linux   | 24        | 0.24%   |
| Peppermint    | 18        | 0.18%   |
| Parrot        | 18        | 0.18%   |
| CentOS        | 17        | 0.17%   |
| Nobara        | 12        | 0.12%   |
| LinuxFX       | 12        | 0.12%   |
| Void Linux    | 11        | 0.11%   |
| Deepin        | 11        | 0.11%   |
| Devuan        | 10        | 0.1%    |
| Xero          | 9         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 244       | 2.05%   |
| 5.16.7-desktop-1omv4003  | 226       | 1.9%    |
| 5.4.0-42-generic         | 157       | 1.32%   |
| 5.15.0-56-generic        | 151       | 1.27%   |
| 5.4.0-58-generic         | 120       | 1.01%   |
| 5.15.0-58-generic        | 110       | 0.92%   |
| 5.4.0-91-generic         | 105       | 0.88%   |
| 5.4.0-48-generic         | 93        | 0.78%   |
| 5.4.0-52-generic         | 90        | 0.75%   |
| 6.1.1-desktop-1omv2290   | 80        | 0.67%   |
| 6.2.6-desktop-1omv2390   | 79        | 0.66%   |
| 5.15.0-46-generic        | 79        | 0.66%   |
| 5.15.0-52-generic        | 78        | 0.65%   |
| 5.15.0-60-generic        | 73        | 0.61%   |
| 5.8.0-43-generic         | 67        | 0.56%   |
| 5.4.0-26-generic         | 64        | 0.54%   |
| 5.19.0-35-generic        | 64        | 0.54%   |
| 5.15.0-48-generic        | 64        | 0.54%   |
| 5.13.0-39-generic        | 61        | 0.51%   |
| 5.13.0-28-generic        | 60        | 0.5%    |
| 5.11.0-38-generic        | 60        | 0.5%    |
| 5.4.0-56-generic         | 59        | 0.49%   |
| 5.4.0-74-generic         | 58        | 0.49%   |
| 5.4.0-72-generic         | 58        | 0.49%   |
| 5.4.0-65-generic         | 58        | 0.49%   |
| 5.11.0-27-generic        | 58        | 0.49%   |
| 5.15.0-53-generic        | 57        | 0.48%   |
| 5.11.0-37-generic        | 57        | 0.48%   |
| 4.18.16-desktop-1bP      | 57        | 0.48%   |
| 5.4.0-54-generic         | 56        | 0.47%   |
| 5.11.0-40-generic        | 56        | 0.47%   |
| 5.4.0-33-generic         | 55        | 0.46%   |
| 5.4.0-29-generic         | 55        | 0.46%   |
| 5.15.0-67-generic        | 54        | 0.45%   |
| 5.15.0-47-generic        | 54        | 0.45%   |
| 5.4.0-40-generic         | 53        | 0.44%   |
| 5.3.0-40-generic         | 52        | 0.44%   |
| 5.4.0-47-generic         | 51        | 0.43%   |
| 5.3.0-28-generic         | 51        | 0.43%   |
| 5.4.0-90-generic         | 50        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 2094      | 19.01%  |
| 5.15.0  | 1078      | 9.79%   |
| 4.15.0  | 603       | 5.47%   |
| 5.8.0   | 598       | 5.43%   |
| 5.13.0  | 596       | 5.41%   |
| 5.11.0  | 584       | 5.3%    |
| 5.3.0   | 388       | 3.52%   |
| 5.19.0  | 382       | 3.47%   |
| 5.10.0  | 365       | 3.31%   |
| 5.0.0   | 250       | 2.27%   |
| 5.10.14 | 246       | 2.23%   |
| 5.16.7  | 229       | 2.08%   |
| 4.18.0  | 209       | 1.9%    |
| 6.2.6   | 107       | 0.97%   |
| 4.19.0  | 94        | 0.85%   |
| 6.1.1   | 91        | 0.83%   |
| 6.1.0   | 81        | 0.74%   |
| 6.2.0   | 73        | 0.66%   |
| 4.18.16 | 61        | 0.55%   |
| 6.0.0   | 51        | 0.46%   |
| 5.14.0  | 46        | 0.42%   |
| 4.9.20  | 36        | 0.33%   |
| 5.3.18  | 33        | 0.3%    |
| 5.18.0  | 33        | 0.3%    |
| 4.9.60  | 31        | 0.28%   |
| 5.17.5  | 30        | 0.27%   |
| 5.6.0   | 28        | 0.25%   |
| 4.4.0   | 28        | 0.25%   |
| 5.9.16  | 27        | 0.25%   |
| 5.6.14  | 27        | 0.25%   |
| 5.16.0  | 27        | 0.25%   |
| 5.8.16  | 24        | 0.22%   |
| 6.0.12  | 23        | 0.21%   |
| 5.17.0  | 23        | 0.21%   |
| 6.3.1   | 21        | 0.19%   |
| 6.2.11  | 21        | 0.19%   |
| 6.1.12  | 21        | 0.19%   |
| 5.17.1  | 20        | 0.18%   |
| 5.18.10 | 19        | 0.17%   |
| 5.14.21 | 19        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 2206      | 20.28%  |
| 5.15    | 1296      | 11.91%  |
| 5.10    | 771       | 7.09%   |
| 5.8     | 714       | 6.56%   |
| 5.13    | 672       | 6.18%   |
| 5.11    | 668       | 6.14%   |
| 4.15    | 607       | 5.58%   |
| 5.19    | 474       | 4.36%   |
| 5.3     | 458       | 4.21%   |
| 5.16    | 354       | 3.25%   |
| 6.1     | 343       | 3.15%   |
| 6.2     | 281       | 2.58%   |
| 4.18    | 279       | 2.56%   |
| 5.0     | 258       | 2.37%   |
| 6.0     | 192       | 1.76%   |
| 5.9     | 133       | 1.22%   |
| 4.9     | 128       | 1.18%   |
| 5.6     | 123       | 1.13%   |
| 5.14    | 120       | 1.1%    |
| 4.19    | 118       | 1.08%   |
| 5.17    | 117       | 1.08%   |
| 5.18    | 110       | 1.01%   |
| 6.3     | 83        | 0.76%   |
| 5.12    | 80        | 0.74%   |
| 5.7     | 71        | 0.65%   |
| 5.5     | 52        | 0.48%   |
| 4.4     | 31        | 0.28%   |
| 5.1     | 25        | 0.23%   |
| 4.1     | 22        | 0.2%    |
| 4.13    | 19        | 0.17%   |
| 5.2     | 18        | 0.17%   |
| 4.12    | 16        | 0.15%   |
| 4.14    | 10        | 0.09%   |
| 4.20    | 7         | 0.06%   |
| 4.8     | 4         | 0.04%   |
| 4.17    | 4         | 0.04%   |
| 3.10    | 4         | 0.04%   |
| 4.11    | 3         | 0.03%   |
| 4.10    | 2         | 0.02%   |
| 5.4.104 | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 9442      | 96.54%  |
| i686    | 329       | 3.36%   |
| aarch64 | 4         | 0.04%   |
| ppc     | 3         | 0.03%   |
| armv7l  | 2         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 4084      | 40.14%  |
| KDE5                         | 1699      | 16.7%   |
| X-Cinnamon                   | 1151      | 11.31%  |
| Unknown                      | 995       | 9.78%   |
| XFCE                         | 842       | 8.28%   |
| MATE                         | 318       | 3.13%   |
| KDE                          | 226       | 2.22%   |
| Cinnamon                     | 171       | 1.68%   |
| KDE4                         | 106       | 1.04%   |
| Pantheon                     | 97        | 0.95%   |
| LXQt                         | 85        | 0.84%   |
| Budgie                       | 75        | 0.74%   |
| i3                           | 63        | 0.62%   |
| Unity                        | 56        | 0.55%   |
| LXDE                         | 47        | 0.46%   |
| GNOME Flashback              | 24        | 0.24%   |
| Deepin                       | 22        | 0.22%   |
| sway                         | 15        | 0.15%   |
| lightdm-xsession             | 15        | 0.15%   |
| awesome                      | 13        | 0.13%   |
| GNOME Classic                | 10        | 0.1%    |
| openbox                      | 6         | 0.06%   |
| bspwm                        | 6         | 0.06%   |
| xmonad                       | 5         | 0.05%   |
| herbstluftwm                 | 5         | 0.05%   |
| Trinity                      | 4         | 0.04%   |
| Enlightenment                | 4         | 0.04%   |
| qtile                        | 3         | 0.03%   |
| Hyprland                     | 3         | 0.03%   |
| DWM                          | 3         | 0.03%   |
| chadwm                       | 3         | 0.03%   |
| x-session-manager            | 2         | 0.02%   |
| leftwm                       | 2         | 0.02%   |
| icewm                        | 2         | 0.02%   |
| fluxbox                      | 2         | 0.02%   |
| default                      | 2         | 0.02%   |
| xubuntu                      | 1         | 0.01%   |
| nxde                         | 1         | 0.01%   |
| KDE:old                      | 1         | 0.01%   |
| GNOME-Subgraph-Classic:GNOME | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 7887      | 78.57%  |
| Wayland     | 1507      | 15.01%  |
| Unknown     | 543       | 5.41%   |
| Tty         | 100       | 1%      |
| Unspecified | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4775      | 47%     |
| SDDM    | 1465      | 14.42%  |
| LightDM | 1250      | 12.3%   |
| GDM3    | 1189      | 11.7%   |
| GDM     | 951       | 9.36%   |
| TDM     | 366       | 3.6%    |
| KDM     | 108       | 1.06%   |
| XDM     | 16        | 0.16%   |
| SLiM    | 16        | 0.16%   |
| LXDM    | 9         | 0.09%   |
| NODM    | 5         | 0.05%   |
| GREETD  | 5         | 0.05%   |
| MDM     | 2         | 0.02%   |
| Ly      | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| de_DE      | 6345      | 63.59%  |
| en_US      | 1894      | 18.98%  |
| Unknown    | 1094      | 10.96%  |
| en_GB      | 166       | 1.66%   |
| C          | 118       | 1.18%   |
| ru_RU      | 59        | 0.59%   |
| pl_PL      | 33        | 0.33%   |
| en_DE      | 32        | 0.32%   |
| it_IT      | 21        | 0.21%   |
| POSIX      | 18        | 0.18%   |
| fr_FR      | 17        | 0.17%   |
| es_ES      | 14        | 0.14%   |
| de_AT      | 11        | 0.11%   |
| hu_HU      | 10        | 0.1%    |
| C.UTF8     | 9         | 0.09%   |
| ro_RO      | 8         | 0.08%   |
| nl_NL      | 8         | 0.08%   |
| en_CA      | 8         | 0.08%   |
| ru_UA      | 7         | 0.07%   |
| en_IN      | 7         | 0.07%   |
| en_IE      | 7         | 0.07%   |
| de_CH      | 7         | 0.07%   |
| tr_TR      | 6         | 0.06%   |
| pt_BR      | 6         | 0.06%   |
| en_AG      | 6         | 0.06%   |
| en_DK      | 5         | 0.05%   |
| en_AU      | 5         | 0.05%   |
| sk_SK      | 4         | 0.04%   |
| bg_BG      | 4         | 0.04%   |
| uk_UA      | 3         | 0.03%   |
| nds_DE     | 3         | 0.03%   |
| de_BE      | 3         | 0.03%   |
| sl_SI      | 2         | 0.02%   |
| pt_PT      | 2         | 0.02%   |
| ja_JP      | 2         | 0.02%   |
| en_US-UTF8 | 2         | 0.02%   |
| en_SG      | 2         | 0.02%   |
| el_GR      | 2         | 0.02%   |
| de_LI      | 2         | 0.02%   |
| de_IT      | 2         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 5060      | 50.71%  |
| EFI  | 4919      | 49.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 7776      | 77.99%  |
| Btrfs    | 803       | 8.05%   |
| Overlay  | 745       | 7.47%   |
| Unknown  | 344       | 3.45%   |
| Tmpfs    | 96        | 0.96%   |
| Xfs      | 92        | 0.92%   |
| Zfs      | 54        | 0.54%   |
| Ext2     | 23        | 0.23%   |
| F2fs     | 16        | 0.16%   |
| Ext3     | 12        | 0.12%   |
| Rootfs   | 2         | 0.02%   |
| Reiserfs | 2         | 0.02%   |
| Aufs     | 2         | 0.02%   |
| XXXXXXX  | 1         | 0.01%   |
| XXXfs    | 1         | 0.01%   |
| OveXlay  | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5261      | 52.58%  |
| GPT     | 3622      | 36.2%   |
| MBR     | 1123      | 11.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8663      | 87.38%  |
| Yes       | 1251      | 12.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7417      | 74.79%  |
| Yes       | 2500      | 25.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2550      | 26.09%  |
| Hewlett-Packard     | 1423      | 14.56%  |
| Dell                | 1141      | 11.68%  |
| Acer                | 1059      | 10.84%  |
| ASUSTek Computer    | 820       | 8.39%   |
| Medion              | 303       | 3.1%    |
| Toshiba             | 257       | 2.63%   |
| Fujitsu             | 236       | 2.41%   |
| Apple               | 218       | 2.23%   |
| Samsung Electronics | 208       | 2.13%   |
| TUXEDO              | 195       | 2%      |
| Sony                | 169       | 1.73%   |
| MSI                 | 153       | 1.57%   |
| HUAWEI              | 113       | 1.16%   |
| Notebook            | 94        | 0.96%   |
| Fujitsu Siemens     | 89        | 0.91%   |
| Valve               | 88        | 0.9%    |
| Packard Bell        | 80        | 0.82%   |
| Schenker            | 72        | 0.74%   |
| Unknown             | 44        | 0.45%   |
| Wortmann AG         | 42        | 0.43%   |
| Google              | 25        | 0.26%   |
| TrekStor            | 22        | 0.23%   |
| Gigabyte Technology | 22        | 0.23%   |
| IBM                 | 17        | 0.17%   |
| Clevo               | 16        | 0.16%   |
| AXDIA International | 16        | 0.16%   |
| Alienware           | 16        | 0.16%   |
| Timi                | 15        | 0.15%   |
| eMachines           | 15        | 0.15%   |
| Razer               | 14        | 0.14%   |
| Panasonic           | 13        | 0.13%   |
| LG Electronics      | 13        | 0.13%   |
| Framework           | 12        | 0.12%   |
| Chuwi               | 12        | 0.12%   |
| Tactus              | 9         | 0.09%   |
| LincPlus            | 9         | 0.09%   |
| AMI                 | 9         | 0.09%   |
| VALE                | 6         | 0.06%   |
| CSL-Computer        | 6         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 113       | 1.16%   |
| Valve Jupiter                 | 88        | 0.9%    |
| HP Notebook                   | 51        | 0.52%   |
| Lenovo IdeaPad 5 15ARE05 81YQ | 30        | 0.31%   |
| ASUS P50IJ                    | 29        | 0.3%    |
| HP 255 G7 Notebook PC         | 26        | 0.27%   |
| Dell Latitude E6420           | 24        | 0.25%   |
| HP Laptop 15s-eq2xxx          | 23        | 0.24%   |
| Dell Latitude E6430           | 22        | 0.23%   |
| Dell Latitude E6410           | 22        | 0.23%   |
| Dell XPS 15 9570              | 21        | 0.21%   |
| Acer Swift SF114-34           | 21        | 0.21%   |
| Dell XPS 13 9370              | 19        | 0.19%   |
| HP Pavilion Notebook          | 18        | 0.18%   |
| HP Laptop 17-ca1xxx           | 18        | 0.18%   |
| HP Laptop 17-ca0xxx           | 18        | 0.18%   |
| HP 250 G7 Notebook PC         | 18        | 0.18%   |
| Dell XPS 15 7590              | 18        | 0.18%   |
| Dell XPS 13 7390              | 18        | 0.18%   |
| Dell Latitude E7470           | 18        | 0.18%   |
| Apple MacBookPro9,2           | 18        | 0.18%   |
| HP Pavilion g6                | 17        | 0.17%   |
| HP Pavilion dv7               | 17        | 0.17%   |
| HP Pavilion 17                | 17        | 0.17%   |
| HP EliteBook 8470p            | 17        | 0.17%   |
| HP EliteBook 8460p            | 17        | 0.17%   |
| Dell Latitude E6540           | 17        | 0.17%   |
| Acer Aspire 7750G             | 17        | 0.17%   |
| HUAWEI NBLK-WAX9X             | 16        | 0.16%   |
| HP ProBook 650 G1             | 16        | 0.16%   |
| HP Pavilion g7                | 16        | 0.16%   |
| HP Pavilion dv6               | 16        | 0.16%   |
| Dell XPS 15 9500              | 16        | 0.16%   |
| Dell Latitude E6520           | 16        | 0.16%   |
| TUXEDO Pulse 15 Gen1          | 15        | 0.15%   |
| Lenovo G50-70 20351           | 15        | 0.15%   |
| HP EliteBook 8440p            | 15        | 0.15%   |
| HP EliteBook 840 G5           | 15        | 0.15%   |
| Apple MacBookPro8,1           | 15        | 0.15%   |
| HP Laptop 17-bs0xx            | 14        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 1696      | 17.35%  |
| Acer Aspire              | 723       | 7.4%    |
| Dell Latitude            | 519       | 5.31%   |
| Lenovo IdeaPad           | 393       | 4.02%   |
| HP EliteBook             | 303       | 3.1%    |
| HP Laptop                | 236       | 2.41%   |
| Fujitsu LIFEBOOK         | 224       | 2.29%   |
| HP Pavilion              | 212       | 2.17%   |
| Toshiba Satellite        | 209       | 2.14%   |
| Dell XPS                 | 191       | 1.95%   |
| HP ProBook               | 181       | 1.85%   |
| Dell Inspiron            | 161       | 1.65%   |
| Dell Precision           | 137       | 1.4%    |
| Unknown                  | 113       | 1.16%   |
| Acer Swift               | 107       | 1.09%   |
| ASUS VivoBook            | 101       | 1.03%   |
| HP Compaq                | 90        | 0.92%   |
| Valve Jupiter            | 88        | 0.9%    |
| Acer TravelMate          | 84        | 0.86%   |
| Packard Bell EasyNote    | 71        | 0.73%   |
| Medion Akoya             | 61        | 0.62%   |
| HP 255                   | 59        | 0.6%    |
| HP ZBook                 | 58        | 0.59%   |
| Dell Vostro              | 58        | 0.59%   |
| ASUS ZenBook             | 58        | 0.59%   |
| HP 250                   | 56        | 0.57%   |
| Lenovo Yoga              | 52        | 0.53%   |
| HP Notebook              | 51        | 0.52%   |
| TUXEDO InfinityBook      | 40        | 0.41%   |
| Lenovo Legion            | 40        | 0.41%   |
| Acer Extensa             | 39        | 0.4%    |
| Fujitsu Siemens AMILO    | 37        | 0.38%   |
| Schenker XMG             | 36        | 0.37%   |
| Lenovo ThinkBook         | 35        | 0.36%   |
| HP ENVY                  | 35        | 0.36%   |
| Acer Nitro               | 34        | 0.35%   |
| ASUS ROG                 | 29        | 0.3%    |
| ASUS P50IJ               | 29        | 0.3%    |
| Fujitsu Siemens LIFEBOOK | 28        | 0.29%   |
| Apple MacBookPro11       | 28        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 854       | 8.74%   |
| 2012    | 823       | 8.42%   |
| 2019    | 814       | 8.33%   |
| 2011    | 783       | 8.01%   |
| 2018    | 770       | 7.88%   |
| 2021    | 683       | 6.99%   |
| 2013    | 646       | 6.61%   |
| 2010    | 598       | 6.12%   |
| 2014    | 566       | 5.79%   |
| 2017    | 546       | 5.59%   |
| 2016    | 519       | 5.31%   |
| 2015    | 515       | 5.27%   |
| 2008    | 462       | 4.73%   |
| 2009    | 417       | 4.27%   |
| 2022    | 335       | 3.43%   |
| 2007    | 237       | 2.43%   |
| 2006    | 109       | 1.12%   |
| 2005    | 42        | 0.43%   |
| Unknown | 21        | 0.21%   |
| 2023    | 16        | 0.16%   |
| 2004    | 10        | 0.1%    |
| 2003    | 3         | 0.03%   |
| 2002    | 2         | 0.02%   |
| 2000    | 1         | 0.01%   |
| 1999    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 9773      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 8894      | 90.25%  |
| Enabled  | 961       | 9.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 9727      | 99.53%  |
| Yes  | 46        | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2779      | 28.1%   |
| 3.01-4.0    | 2266      | 22.92%  |
| 8.01-16.0   | 1789      | 18.09%  |
| 16.01-24.0  | 1502      | 15.19%  |
| 32.01-64.0  | 620       | 6.27%   |
| 1.01-2.0    | 423       | 4.28%   |
| 2.01-3.0    | 183       | 1.85%   |
| 64.01-256.0 | 121       | 1.22%   |
| 24.01-32.0  | 113       | 1.14%   |
| 0.51-1.0    | 83        | 0.84%   |
| 0.01-0.5    | 7         | 0.07%   |
| Unknown     | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 4444      | 41.12%  |
| 2.01-3.0   | 2660      | 24.61%  |
| 4.01-8.0   | 1202      | 11.12%  |
| 3.01-4.0   | 1196      | 11.07%  |
| 0.51-1.0   | 788       | 7.29%   |
| 8.01-16.0  | 339       | 3.14%   |
| 0.01-0.5   | 117       | 1.08%   |
| 16.01-24.0 | 40        | 0.37%   |
| 24.01-32.0 | 15        | 0.14%   |
| 32.01-64.0 | 3         | 0.03%   |
| Unknown    | 3         | 0.03%   |
| 0          | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7351      | 73.47%  |
| 2      | 2243      | 22.42%  |
| 3      | 272       | 2.72%   |
| 0      | 85        | 0.85%   |
| 4      | 43        | 0.43%   |
| 6      | 5         | 0.05%   |
| 5      | 4         | 0.04%   |
| 7      | 2         | 0.02%   |
| 9      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5545      | 56.4%   |
| Yes       | 4287      | 43.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8273      | 84.34%  |
| No        | 1536      | 15.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9606      | 98.21%  |
| No        | 175       | 1.79%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7258      | 73.03%  |
| No        | 2681      | 26.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 9773      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Berlin               | 932       | 8.79%   |
| Munich               | 508       | 4.79%   |
| Hamburg              | 387       | 3.65%   |
| Frankfurt am Main    | 323       | 3.05%   |
| Cologne              | 248       | 2.34%   |
| Stuttgart            | 216       | 2.04%   |
| Leipzig              | 166       | 1.57%   |
| Dresden              | 131       | 1.24%   |
| Nuremberg            | 122       | 1.15%   |
| Düsseldorf          | 117       | 1.1%    |
| Essen                | 110       | 1.04%   |
| Mannheim             | 106       | 1%      |
| Karlsruhe            | 94        | 0.89%   |
| Dortmund             | 91        | 0.86%   |
| Duisburg             | 80        | 0.75%   |
| Bremen               | 73        | 0.69%   |
| Bonn                 | 68        | 0.64%   |
| Hanover              | 66        | 0.62%   |
| Wuppertal            | 64        | 0.6%    |
| Bielefeld            | 63        | 0.59%   |
| Darmstadt            | 61        | 0.58%   |
| Münster             | 58        | 0.55%   |
| Augsburg             | 58        | 0.55%   |
| Braunschweig         | 56        | 0.53%   |
| Wiesbaden            | 51        | 0.48%   |
| Bochum               | 49        | 0.46%   |
| Mainz                | 48        | 0.45%   |
| Regensburg           | 47        | 0.44%   |
| Chemnitz             | 47        | 0.44%   |
| Aachen               | 45        | 0.42%   |
| Kiel                 | 42        | 0.4%    |
| Halle                | 42        | 0.4%    |
| Freiburg im Breisgau | 41        | 0.39%   |
| Bamberg              | 38        | 0.36%   |
| Erfurt               | 35        | 0.33%   |
| Garbsen              | 34        | 0.32%   |
| Offenbach            | 31        | 0.29%   |
| Kassel               | 31        | 0.29%   |
| Heilbronn            | 31        | 0.29%   |
| Rüsselsheim am Main | 30        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2607      | 3490   | 21.81%  |
| WDC                         | 1204      | 1533   | 10.07%  |
| Seagate                     | 1091      | 1408   | 9.13%   |
| Sandisk                     | 997       | 1347   | 8.34%   |
| Toshiba                     | 905       | 1155   | 7.57%   |
| Unknown                     | 673       | 918    | 5.63%   |
| SK hynix                    | 490       | 613    | 4.1%    |
| Crucial                     | 456       | 595    | 3.82%   |
| Hitachi                     | 380       | 462    | 3.18%   |
| Kingston                    | 365       | 450    | 3.05%   |
| Intel                       | 341       | 444    | 2.85%   |
| Micron Technology           | 316       | 396    | 2.64%   |
| Intenso                     | 294       | 375    | 2.46%   |
| HGST                        | 234       | 298    | 1.96%   |
| Fujitsu                     | 108       | 138    | 0.9%    |
| KIOXIA                      | 94        | 117    | 0.79%   |
| Apple                       | 92        | 117    | 0.77%   |
| Transcend                   | 77        | 95     | 0.64%   |
| Phison                      | 77        | 99     | 0.64%   |
| LITEON                      | 71        | 73     | 0.59%   |
| A-DATA Technology           | 61        | 69     | 0.51%   |
| Unknown                     | 55        | 60     | 0.46%   |
| LITEONIT                    | 47        | 58     | 0.39%   |
| China                       | 41        | 47     | 0.34%   |
| Phison Electronics          | 38        | 42     | 0.32%   |
| Micron/Crucial Technology   | 38        | 42     | 0.32%   |
| OCZ                         | 35        | 47     | 0.29%   |
| SPCC                        | 34        | 38     | 0.28%   |
| Kingston Technology Company | 34        | 41     | 0.28%   |
| JMicron Technology          | 30        | 30     | 0.25%   |
| Silicon Motion              | 28        | 33     | 0.23%   |
| Patriot                     | 25        | 29     | 0.21%   |
| UMIS                        | 24        | 39     | 0.2%    |
| Netac                       | 23        | 31     | 0.19%   |
| ASMT                        | 23        | 27     | 0.19%   |
| INNOVATION IT               | 22        | 28     | 0.18%   |
| Leven                       | 21        | 31     | 0.18%   |
| Lenovo                      | 21        | 25     | 0.18%   |
| Union Memory (Shenzhen)     | 16        | 26     | 0.13%   |
| PNY                         | 16        | 21     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 130       | 1.04%   |
| Unknown MMC Card  32GB                              | 122       | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 115       | 0.92%   |
| Samsung SSD 850 EVO 500GB                           | 112       | 0.9%    |
| Samsung SSD 860 EVO 500GB                           | 109       | 0.87%   |
| Samsung SSD 850 EVO 250GB                           | 100       | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 100       | 0.8%    |
| Samsung NVMe SSD Drive 512GB                        | 99        | 0.79%   |
| Unknown MMC Card  64GB                              | 98        | 0.79%   |
| SanDisk NVMe SSD Drive 512GB                        | 98        | 0.79%   |
| Seagate ST9500325AS 500GB                           | 91        | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB                      | 88        | 0.7%    |
| Crucial CT500MX500SSD1 500GB                        | 74        | 0.59%   |
| Toshiba MQ01ABF050 500GB                            | 71        | 0.57%   |
| SanDisk SSD PLUS 240GB                              | 70        | 0.56%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 68        | 0.54%   |
| Unknown MMC Card  128GB                             | 64        | 0.51%   |
| Samsung SSD 860 EVO 1TB                             | 64        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                       | 63        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 58        | 0.46%   |
| Samsung SSD 860 EVO 250GB                           | 58        | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 56        | 0.45%   |
| Samsung NVMe SSD Drive 1024GB                       | 56        | 0.45%   |
| SanDisk SSD PLUS 1000GB                             | 55        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 55        | 0.44%   |
| Unknown                                             | 55        | 0.44%   |
| Samsung NVMe SSD Drive 256GB                        | 54        | 0.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 51        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                        | 50        | 0.4%    |
| HGST HTS721010A9E630 1TB                            | 50        | 0.4%    |
| Intel NVMe SSD Drive 512GB                          | 49        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                        | 49        | 0.39%   |
| Samsung SSD 840 EVO 250GB                           | 45        | 0.36%   |
| HGST HTS725050A7E630 500GB                          | 45        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 44        | 0.35%   |
| Samsung NVMe SSD Drive 500GB                        | 44        | 0.35%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                        | 42        | 0.34%   |
| HGST HTS541010A9E680 1TB                            | 42        | 0.34%   |
| Samsung SSD 840 EVO 500GB                           | 41        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1059      | 1366   | 31.41%  |
| WDC                 | 804       | 1033   | 23.84%  |
| Toshiba             | 557       | 705    | 16.52%  |
| Hitachi             | 380       | 462    | 11.27%  |
| HGST                | 234       | 298    | 6.94%   |
| Samsung Electronics | 114       | 146    | 3.38%   |
| Fujitsu             | 108       | 138    | 3.2%    |
| Unknown             | 32        | 71     | 0.95%   |
| Intenso             | 24        | 31     | 0.71%   |
| Apple               | 9         | 9      | 0.27%   |
| USB3.0              | 8         | 9      | 0.24%   |
| IBM/Hitachi         | 8         | 8      | 0.24%   |
| ASMT                | 8         | 9      | 0.24%   |
| ASMedia             | 8         | 9      | 0.24%   |
| USB                 | 3         | 3      | 0.09%   |
| SILICONMOTION       | 2         | 3      | 0.06%   |
| LIO-ORG             | 2         | 8      | 0.06%   |
| HGST HTS            | 2         | 2      | 0.06%   |
| WD MediaMax         | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SSK                 | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| IB-AC703            | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 2      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1432      | 1877   | 32.05%  |
| SanDisk             | 690       | 969    | 15.44%  |
| Crucial             | 425       | 562    | 9.51%   |
| Kingston            | 239       | 307    | 5.35%   |
| Intenso             | 224       | 280    | 5.01%   |
| WDC                 | 159       | 197    | 3.56%   |
| Micron Technology   | 139       | 166    | 3.11%   |
| Toshiba             | 130       | 157    | 2.91%   |
| SK hynix            | 114       | 136    | 2.55%   |
| Intel               | 109       | 138    | 2.44%   |
| Transcend           | 75        | 93     | 1.68%   |
| LITEON              | 66        | 68     | 1.48%   |
| Apple               | 63        | 74     | 1.41%   |
| A-DATA Technology   | 50        | 56     | 1.12%   |
| LITEONIT            | 47        | 58     | 1.05%   |
| China               | 41        | 47     | 0.92%   |
| OCZ                 | 35        | 47     | 0.78%   |
| SPCC                | 30        | 33     | 0.67%   |
| Patriot             | 25        | 29     | 0.56%   |
| Netac               | 23        | 31     | 0.51%   |
| INNOVATION IT       | 22        | 28     | 0.49%   |
| Leven               | 20        | 30     | 0.45%   |
| Phison              | 18        | 20     | 0.4%    |
| Unknown             | 16        | 17     | 0.36%   |
| Hewlett-Packard     | 13        | 14     | 0.29%   |
| ASMT                | 13        | 16     | 0.29%   |
| Apacer              | 13        | 17     | 0.29%   |
| PNY                 | 12        | 16     | 0.27%   |
| Unknown             | 11        | 11     | 0.25%   |
| Verbatim            | 10        | 15     | 0.22%   |
| Seagate             | 10        | 12     | 0.22%   |
| KingSpec            | 10        | 13     | 0.22%   |
| Emtec               | 10        | 11     | 0.22%   |
| Dogfish             | 10        | 18     | 0.22%   |
| Corsair             | 8         | 9      | 0.18%   |
| Lexar               | 7         | 9      | 0.16%   |
| KingDian            | 7         | 8      | 0.16%   |
| TrekStor            | 6         | 8      | 0.13%   |
| BIWIN               | 6         | 6      | 0.13%   |
| TO Exter            | 5         | 6      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 4165      | 5763   | 36.45%  |
| HDD     | 3263      | 4321   | 28.55%  |
| NVMe    | 3160      | 4269   | 27.65%  |
| MMC     | 680       | 893    | 5.95%   |
| Unknown | 160       | 203    | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6728      | 9750   | 61.43%  |
| NVMe | 3140      | 4228   | 28.67%  |
| MMC  | 680       | 893    | 6.21%   |
| SAS  | 405       | 578    | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5195      | 7145   | 70.41%  |
| 0.51-1.0   | 1921      | 2573   | 26.04%  |
| 1.01-2.0   | 200       | 266    | 2.71%   |
| 4.01-10.0  | 43        | 63     | 0.58%   |
| 3.01-4.0   | 18        | 35     | 0.24%   |
| 2.01-3.0   | 1         | 2      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 3076      | 29.75%  |
| 251-500        | 2690      | 26.02%  |
| 501-1000       | 1514      | 14.64%  |
| 1-20           | 752       | 7.27%   |
| 51-100         | 691       | 6.68%   |
| 1001-2000      | 549       | 5.31%   |
| 21-50          | 411       | 3.97%   |
| Unknown        | 315       | 3.05%   |
| More than 3000 | 207       | 2%      |
| 2001-3000      | 135       | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 4255      | 39.3%   |
| 21-50          | 2059      | 19.02%  |
| 101-250        | 1395      | 12.88%  |
| 51-100         | 1331      | 12.29%  |
| 251-500        | 792       | 7.31%   |
| 501-1000       | 405       | 3.74%   |
| Unknown        | 315       | 2.91%   |
| 1001-2000      | 190       | 1.75%   |
| More than 3000 | 50        | 0.46%   |
| 2001-3000      | 33        | 0.3%    |
| 0              | 3         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                                          | 10        | 13     | 2.03%   |
| Seagate ST9500325AS 500GB                                       | 10        | 14     | 2.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 10        | 13     | 2.03%   |
| Seagate ST9320325AS 320GB                                       | 9         | 10     | 1.83%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 9         | 9      | 1.83%   |
| Seagate ST500LT012-1DG142 500GB                                 | 8         | 8      | 1.62%   |
| Seagate ST500LT012-9WS142 500GB                                 | 7         | 8      | 1.42%   |
| Seagate ST500LM000-SSHD-8GB                                     | 7         | 7      | 1.42%   |
| HGST HTS545050A7E680 500GB                                      | 7         | 11     | 1.42%   |
| Seagate ST500LM000-1EJ162 500GB                                 | 6         | 9      | 1.22%   |
| HGST HTS725050A7E630 500GB                                      | 6         | 6      | 1.22%   |
| HGST HTS541010A9E680 1TB                                        | 6         | 6      | 1.22%   |
| Hitachi HTS547575A9E384 752GB                                   | 5         | 5      | 1.01%   |
| Crucial M4-CT256M4SSD3 256GB                                    | 5         | 5      | 1.01%   |
| Seagate ST9500420AS 500GB                                       | 4         | 4      | 0.81%   |
| Seagate ST9250315AS 250GB                                       | 4         | 5      | 0.81%   |
| SanDisk SSD PLUS 1000GB                                         | 4         | 5      | 0.81%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD             | 4         | 4      | 0.81%   |
| Hitachi HTS547564A9E384 640GB                                   | 4         | 4      | 0.81%   |
| Hitachi HTS545050A7E380 500GB                                   | 4         | 4      | 0.81%   |
| Hitachi HTS541616J9SA00 160GB                                   | 4         | 5      | 0.81%   |
| HGST HTS545050A7E380 500GB                                      | 4         | 7      | 0.81%   |
| Fujitsu MHZ2320BH G2 320GB                                      | 4         | 5      | 0.81%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                | 3         | 3      | 0.61%   |
| Toshiba MQ01ACF050 500GB                                        | 3         | 3      | 0.61%   |
| Toshiba MQ01ABD075 752GB                                        | 3         | 4      | 0.61%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 3         | 3      | 0.61%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 3         | 3      | 0.61%   |
| Seagate ST9750423AS 752GB                                       | 3         | 4      | 0.61%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 3         | 3      | 0.61%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 3      | 0.61%   |
| Hitachi HTS723232A7A364 320GB                                   | 3         | 3      | 0.61%   |
| Hitachi HTS545032B9A300 320GB                                   | 3         | 3      | 0.61%   |
| Hitachi HTS545025B9A300 250GB                                   | 3         | 3      | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 2         | 2      | 0.41%   |
| WDC WD7500BPVX-22JC3T0 752GB                                    | 2         | 2      | 0.41%   |
| WDC WD7500BPVT-22HXZT3 752GB                                    | 2         | 2      | 0.41%   |
| WDC WD5000LPCX-24C6HT0 500GB                                    | 2         | 2      | 0.41%   |
| WDC WD5000BPVT-22HXZT1 500GB                                    | 2         | 2      | 0.41%   |
| WDC WD5000BEVT-00A0RT0 500GB                                    | 2         | 2      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 143    | 24.9%   |
| WDC                 | 59        | 66     | 12.04%  |
| Hitachi             | 59        | 65     | 12.04%  |
| Toshiba             | 46        | 53     | 9.39%   |
| Samsung Electronics | 39        | 46     | 7.96%   |
| HGST                | 27        | 34     | 5.51%   |
| SanDisk             | 25        | 30     | 5.1%    |
| SK hynix            | 20        | 23     | 4.08%   |
| Micron Technology   | 17        | 20     | 3.47%   |
| Fujitsu             | 16        | 18     | 3.27%   |
| Crucial             | 16        | 16     | 3.27%   |
| Intel               | 11        | 11     | 2.24%   |
| Kingston            | 7         | 7      | 1.43%   |
| Transcend           | 4         | 4      | 0.82%   |
| Intenso             | 3         | 3      | 0.61%   |
| China               | 3         | 3      | 0.61%   |
| A-DATA Technology   | 3         | 4      | 0.61%   |
| PNY                 | 2         | 3      | 0.41%   |
| LITEONIT            | 2         | 5      | 0.41%   |
| LITEON              | 2         | 2      | 0.41%   |
| Apple               | 2         | 2      | 0.41%   |
| Phison              | 1         | 1      | 0.2%    |
| OCZ                 | 1         | 1      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| ASMedia             | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 121       | 142    | 36.89%  |
| Hitachi             | 59        | 65     | 17.99%  |
| WDC                 | 48        | 55     | 14.63%  |
| Toshiba             | 40        | 45     | 12.2%   |
| HGST                | 27        | 34     | 8.23%   |
| Fujitsu             | 16        | 18     | 4.88%   |
| Samsung Electronics | 15        | 19     | 4.57%   |
| IBM/Hitachi         | 1         | 1      | 0.3%    |
| ASMedia             | 1         | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 326       | 380    | 66.94%  |
| SSD  | 134       | 149    | 27.52%  |
| NVMe | 27        | 34     | 5.54%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-00A0RT0 500GB                   | 1         | 1      | 8.33%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB           | 1         | 1      | 8.33%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 8.33%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 980 1TB                | 1         | 1      | 8.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 8.33%   |
| Intel SSDSCKGF256A5 SATA 256GB                 | 1         | 1      | 8.33%   |
| Intel SSDSA2BW160G3 160GB                      | 1         | 1      | 8.33%   |
| Hitachi HTS541010G9SA00 100GB                  | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 16.67%  |
| Toshiba             | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Intel               | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 6030      | 9804   | 58.53%  |
| Works    | 3777      | 5070   | 36.66%  |
| Malfunc  | 484       | 563    | 4.7%    |
| Failed   | 12        | 12     | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 6793      | 60.77%  |
| Samsung Electronics                     | 1185      | 10.6%   |
| AMD                                     | 1072      | 9.59%   |
| SanDisk                                 | 532       | 4.76%   |
| SK hynix                                | 360       | 3.22%   |
| Toshiba America Info Systems            | 222       | 1.99%   |
| Micron Technology                       | 178       | 1.59%   |
| Kingston Technology Company             | 157       | 1.4%    |
| Phison Electronics                      | 104       | 0.93%   |
| Nvidia                                  | 101       | 0.9%    |
| KIOXIA                                  | 100       | 0.89%   |
| Micron/Crucial Technology               | 68        | 0.61%   |
| Union Memory (Shenzhen)                 | 44        | 0.39%   |
| Silicon Motion                          | 33        | 0.3%    |
| Silicon Integrated Systems [SiS]        | 28        | 0.25%   |
| Solid State Storage Technology          | 23        | 0.21%   |
| Lenovo                                  | 21        | 0.19%   |
| ADATA Technology                        | 21        | 0.19%   |
| Apple                                   | 17        | 0.15%   |
| VIA Technologies                        | 16        | 0.14%   |
| Lite-On Technology                      | 14        | 0.13%   |
| Silicon Image                           | 12        | 0.11%   |
| O2 Micro                                | 11        | 0.1%    |
| Marvell Technology Group                | 11        | 0.1%    |
| Seagate Technology                      | 10        | 0.09%   |
| JMicron Technology                      | 9         | 0.08%   |
| Shenzhen Longsys Electronics            | 7         | 0.06%   |
| Realtek Semiconductor                   | 7         | 0.06%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.05%   |
| ASMedia Technology                      | 4         | 0.04%   |
| Yangtze Memory Technologies             | 3         | 0.03%   |
| ULi Electronics                         | 3         | 0.03%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |
| Biwin Storage Technology                | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 846       | 7.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 829       | 6.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 729       | 6.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 632       | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 620       | 5.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 484       | 4.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 428       | 3.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 366       | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 321       | 2.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 320       | 2.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 272       | 2.26%   |
| Samsung NVMe SSD Controller 980                                                  | 251       | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 215       | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 211       | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                              | 188       | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 182       | 1.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 177       | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 177       | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 148       | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 143       | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 141       | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 141       | 1.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 137       | 1.14%   |
| Micron NVMe Storage Controller                                                   | 114       | 0.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 112       | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 112       | 0.93%   |
| Intel SSD 660P Series                                                            | 111       | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 100       | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 93        | 0.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 92        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 91        | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 90        | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 87        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 86        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                              | 85        | 0.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 85        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 82        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 77        | 0.64%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 69        | 0.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 68        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 6942      | 59.9%   |
| NVMe | 3164      | 27.3%   |
| IDE  | 842       | 7.27%   |
| RAID | 641       | 5.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 7946      | 81.31%  |
| AMD          | 1816      | 18.58%  |
| ARM          | 4         | 0.04%   |
| Unknown      | 2         | 0.02%   |
| QUALCOMM     | 1         | 0.01%   |
| PowerBook5,6 | 1         | 0.01%   |
| PowerBook5,4 | 1         | 0.01%   |
| PowerBook3,4 | 1         | 0.01%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 157       | 1.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 155       | 1.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 149       | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 132       | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 131       | 1.34%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 130       | 1.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 117       | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 113       | 1.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 113       | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 110       | 1.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 109       | 1.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 108       | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 107       | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 98        | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 95        | 0.97%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 93        | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 88        | 0.9%    |
| AMD Custom APU 0405                           | 88        | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 78        | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 76        | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 74        | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 69        | 0.71%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 69        | 0.71%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 68        | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 68        | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 66        | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 65        | 0.66%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 65        | 0.66%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 64        | 0.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 63        | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 61        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 61        | 0.62%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 59        | 0.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 59        | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 58        | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 57        | 0.58%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 56        | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 54        | 0.55%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 53        | 0.54%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 52        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2529      | 25.86%  |
| Intel Core i7                  | 2052      | 20.99%  |
| Other                          | 655       | 6.7%    |
| Intel Core i3                  | 650       | 6.65%   |
| Intel Core 2 Duo               | 643       | 6.58%   |
| AMD Ryzen 5                    | 429       | 4.39%   |
| Intel Celeron                  | 412       | 4.21%   |
| AMD Ryzen 7                    | 385       | 3.94%   |
| Intel Pentium                  | 345       | 3.53%   |
| Intel Atom                     | 233       | 2.38%   |
| AMD Ryzen 7 PRO                | 119       | 1.22%   |
| Intel Pentium Dual-Core        | 111       | 1.14%   |
| AMD A6                         | 90        | 0.92%   |
| AMD Ryzen 3                    | 76        | 0.78%   |
| AMD E                          | 75        | 0.77%   |
| Intel Pentium Silver           | 73        | 0.75%   |
| AMD A4                         | 69        | 0.71%   |
| Intel Core 2                   | 64        | 0.65%   |
| AMD A8                         | 62        | 0.63%   |
| Intel Genuine                  | 61        | 0.62%   |
| Intel Pentium Dual             | 59        | 0.6%    |
| AMD Ryzen 9                    | 47        | 0.48%   |
| Intel Pentium M                | 43        | 0.44%   |
| AMD Turion 64 X2 Mobile        | 43        | 0.44%   |
| AMD E2                         | 42        | 0.43%   |
| AMD Ryzen 5 PRO                | 30        | 0.31%   |
| Intel Core i9                  | 28        | 0.29%   |
| AMD A10                        | 28        | 0.29%   |
| AMD E1                         | 26        | 0.27%   |
| Intel Celeron M                | 24        | 0.25%   |
| AMD Athlon                     | 24        | 0.25%   |
| AMD Athlon II                  | 20        | 0.2%    |
| AMD Athlon X2                  | 19        | 0.19%   |
| Intel Core M                   | 18        | 0.18%   |
| Intel Xeon                     | 15        | 0.15%   |
| AMD Athlon 64 X2               | 13        | 0.13%   |
| Intel Core m5                  | 12        | 0.12%   |
| AMD Turion 64 Mobile           | 12        | 0.12%   |
| Intel Core m3                  | 11        | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 10        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5141      | 52.56%  |
| 4       | 3051      | 31.19%  |
| 6       | 581       | 5.94%   |
| 8       | 560       | 5.72%   |
| 1       | 290       | 2.96%   |
| 14      | 54        | 0.55%   |
| 12      | 46        | 0.47%   |
| 10      | 34        | 0.35%   |
| Unknown | 15        | 0.15%   |
| 5       | 4         | 0.04%   |
| 16      | 3         | 0.03%   |
| 24      | 2         | 0.02%   |
| 3       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 9768      | 99.95%  |
| 2       | 2         | 0.02%   |
| Unknown | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6999      | 71.54%  |
| 1       | 2765      | 28.26%  |
| Unknown | 15        | 0.15%   |
| 4       | 3         | 0.03%   |
| 8       | 2         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9469      | 96.7%   |
| 32-bit         | 171       | 1.75%   |
| Unknown        | 149       | 1.52%   |
| 64-bit         | 3         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2301      | 22.75%  |
| 0x206a7    | 652       | 6.45%   |
| 0x306a9    | 640       | 6.33%   |
| 0x1067a    | 382       | 3.78%   |
| 0x40651    | 321       | 3.17%   |
| 0x406e3    | 313       | 3.09%   |
| 0x806ea    | 305       | 3.02%   |
| 0x806ec    | 290       | 2.87%   |
| 0x306c3    | 287       | 2.84%   |
| 0x20655    | 281       | 2.78%   |
| 0x806c1    | 256       | 2.53%   |
| 0x306d4    | 241       | 2.38%   |
| 0x806e9    | 231       | 2.28%   |
| 0x906ea    | 199       | 1.97%   |
| 0x6fd      | 160       | 1.58%   |
| 0x10676    | 160       | 1.58%   |
| 0x0a50000c | 138       | 1.36%   |
| 0x08108102 | 136       | 1.34%   |
| 0x30678    | 134       | 1.32%   |
| 0x08600106 | 126       | 1.25%   |
| 0x20652    | 124       | 1.23%   |
| 0x08608103 | 122       | 1.21%   |
| 0x08108109 | 111       | 1.1%    |
| 0x806eb    | 107       | 1.06%   |
| 0x506e3    | 99        | 0.98%   |
| 0xa0652    | 98        | 0.97%   |
| 0x406c4    | 96        | 0.95%   |
| 0x906e9    | 93        | 0.92%   |
| 0x706e5    | 86        | 0.85%   |
| 0x08600103 | 78        | 0.77%   |
| 0x06006705 | 71        | 0.7%    |
| 0x506c9    | 70        | 0.69%   |
| 0x906a3    | 67        | 0.66%   |
| 0x706a1    | 66        | 0.65%   |
| 0x05000119 | 66        | 0.65%   |
| 0x106ca    | 56        | 0.55%   |
| 0x406c3    | 53        | 0.52%   |
| 0x07030105 | 51        | 0.5%    |
| 0x106c2    | 50        | 0.49%   |
| 0x706a8    | 47        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1601      | 16.37%  |
| SandyBridge      | 807       | 8.25%   |
| IvyBridge        | 795       | 8.13%   |
| Haswell          | 764       | 7.81%   |
| Penryn           | 629       | 6.43%   |
| Skylake          | 540       | 5.52%   |
| Westmere         | 503       | 5.14%   |
| Unknown          | 397       | 4.06%   |
| Silvermont       | 352       | 3.6%    |
| Core             | 331       | 3.38%   |
| Zen 2            | 330       | 3.37%   |
| TigerLake        | 318       | 3.25%   |
| Broadwell        | 310       | 3.17%   |
| Zen+             | 285       | 2.91%   |
| Zen 3            | 201       | 2.06%   |
| Icelake          | 152       | 1.55%   |
| Goldmont plus    | 146       | 1.49%   |
| CometLake        | 135       | 1.38%   |
| Bonnell          | 121       | 1.24%   |
| Excavator        | 113       | 1.16%   |
| Bobcat           | 109       | 1.11%   |
| P6               | 106       | 1.08%   |
| Alderlake Hybrid | 101       | 1.03%   |
| Puma             | 92        | 0.94%   |
| Goldmont         | 89        | 0.91%   |
| K8 Hammer        | 84        | 0.86%   |
| Zen              | 79        | 0.81%   |
| Jaguar           | 46        | 0.47%   |
| K10              | 45        | 0.46%   |
| Piledriver       | 41        | 0.42%   |
| Nehalem          | 37        | 0.38%   |
| K8 & K10 hybrid  | 37        | 0.38%   |
| K10 Llano        | 36        | 0.37%   |
| Tremont          | 28        | 0.29%   |
| Steamroller      | 13        | 0.13%   |
| NetBurst         | 6         | 0.06%   |
| K6               | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6966      | 58.06%  |
| Nvidia                           | 2520      | 21%     |
| AMD                              | 2483      | 20.7%   |
| Silicon Integrated Systems [SiS] | 14        | 0.12%   |
| VIA Technologies                 | 10        | 0.08%   |
| S3 Graphics                      | 4         | 0.03%   |
| Neomagic                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 757       | 6.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 695       | 5.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 391       | 3.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 361       | 2.91%   |
| Intel UHD Graphics 620                                                                   | 358       | 2.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 353       | 2.85%   |
| AMD Renoir                                                                               | 326       | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 320       | 2.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 318       | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 289       | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 287       | 2.31%   |
| Intel HD Graphics 620                                                                    | 268       | 2.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 266       | 2.15%   |
| Intel HD Graphics 5500                                                                   | 250       | 2.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 250       | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 205       | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 181       | 1.46%   |
| AMD Lucienne                                                                             | 173       | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 171       | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 155       | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 131       | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 131       | 1.06%   |
| Intel HD Graphics 530                                                                    | 121       | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 115       | 0.93%   |
| Intel HD Graphics 630                                                                    | 112       | 0.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 109       | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 106       | 0.85%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 97        | 0.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 94        | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 91        | 0.73%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 88        | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 78        | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 75        | 0.6%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 73        | 0.59%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 72        | 0.58%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 71        | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 68        | 0.55%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 68        | 0.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 67        | 0.54%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 64        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 4854      | 49.55%  |
| 1 x AMD            | 1855      | 18.94%  |
| Intel + Nvidia     | 1739      | 17.75%  |
| 1 x Nvidia         | 636       | 6.49%   |
| Intel + AMD        | 353       | 3.6%    |
| 2 x AMD            | 142       | 1.45%   |
| AMD + Nvidia       | 137       | 1.4%    |
| 2 x Intel          | 21        | 0.21%   |
| 2 x Nvidia         | 15        | 0.15%   |
| Other              | 14        | 0.14%   |
| 1 x SiS            | 14        | 0.14%   |
| 1 x VIA            | 10        | 0.1%    |
| 1 x S3 Graphics    | 4         | 0.04%   |
| 1 x Neomagic       | 1         | 0.01%   |
| Intel + 2 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 8503      | 85.81%  |
| Proprietary | 1092      | 11.02%  |
| Unknown     | 314       | 3.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 6215      | 61.85%  |
| 0.01-0.5       | 1344      | 13.37%  |
| 1.01-2.0       | 1186      | 11.8%   |
| 0.51-1.0       | 665       | 6.62%   |
| 3.01-4.0       | 431       | 4.29%   |
| 5.01-6.0       | 114       | 1.13%   |
| 7.01-8.0       | 68        | 0.68%   |
| 2.01-3.0       | 15        | 0.15%   |
| 8.01-16.0      | 10        | 0.1%    |
| More than 64.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2169      | 20.1%   |
| LG Display              | 1705      | 15.8%   |
| Chimei Innolux          | 1324      | 12.27%  |
| BOE                     | 1116      | 10.34%  |
| Samsung Electronics     | 1069      | 9.91%   |
| Lenovo                  | 376       | 3.48%   |
| Chi Mei Optoelectronics | 282       | 2.61%   |
| Sharp                   | 271       | 2.51%   |
| Dell                    | 269       | 2.49%   |
| Apple                   | 223       | 2.07%   |
| Goldstar                | 165       | 1.53%   |
| BenQ                    | 133       | 1.23%   |
| PANDA                   | 128       | 1.19%   |
| LG Philips              | 126       | 1.17%   |
| Hewlett-Packard         | 106       | 0.98%   |
| Acer                    | 101       | 0.94%   |
| Ancor Communications    | 84        | 0.78%   |
| InfoVision              | 80        | 0.74%   |
| CSO                     | 67        | 0.62%   |
| AOC                     | 64        | 0.59%   |
| Philips                 | 60        | 0.56%   |
| Iiyama                  | 59        | 0.55%   |
| CPT                     | 57        | 0.53%   |
| Eizo                    | 54        | 0.5%    |
| Sony                    | 52        | 0.48%   |
| Valve                   | 50        | 0.46%   |
| HannStar                | 45        | 0.42%   |
| Fujitsu Siemens         | 44        | 0.41%   |
| Panasonic               | 35        | 0.32%   |
| Seiko/Epson             | 31        | 0.29%   |
| LGD                     | 30        | 0.28%   |
| Analogix                | 23        | 0.21%   |
| Toshiba                 | 22        | 0.2%    |
| Medion                  | 22        | 0.2%    |
| ASUSTek Computer        | 21        | 0.19%   |
| Vestel Elektronik       | 20        | 0.19%   |
| Quanta Display          | 18        | 0.17%   |
| ViewSonic               | 17        | 0.16%   |
| Unknown                 | 17        | 0.16%   |
| IBM                     | 17        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 82        | 0.75%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 71        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 70        | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 66        | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 59        | 0.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 58        | 0.53%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch              | 54        | 0.49%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 54        | 0.49%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 51        | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 50        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 50        | 0.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 49        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 47        | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 46        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 45        | 0.41%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 45        | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 44        | 0.4%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 41        | 0.37%   |
| BOE LCD Monitor BOE0660 1600x900 382x215mm 17.3-inch                      | 41        | 0.37%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 40        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 40        | 0.36%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 40        | 0.36%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 39        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 38        | 0.35%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 37        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 36        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 35        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 35        | 0.32%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 35        | 0.32%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 35        | 0.32%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 34        | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 34        | 0.31%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 34        | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 34        | 0.31%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 33        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 32        | 0.29%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch            | 32        | 0.29%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 30        | 0.27%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 30        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 30        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4341      | 42.4%   |
| 1366x768 (WXGA)    | 2260      | 22.07%  |
| 1600x900 (HD+)     | 1011      | 9.87%   |
| 1280x800 (WXGA)    | 488       | 4.77%   |
| 3840x2160 (4K)     | 370       | 3.61%   |
| 2560x1440 (QHD)    | 325       | 3.17%   |
| 1440x900 (WXGA+)   | 244       | 2.38%   |
| 1920x1200 (WUXGA)  | 221       | 2.16%   |
| 1680x1050 (WSXGA+) | 147       | 1.44%   |
| 1024x600           | 81        | 0.79%   |
| 2560x1600          | 79        | 0.77%   |
| 800x1280           | 69        | 0.67%   |
| 2880x1800          | 69        | 0.67%   |
| 1280x1024 (SXGA)   | 63        | 0.62%   |
| 3440x1440          | 59        | 0.58%   |
| 3840x2400          | 46        | 0.45%   |
| 2160x1440          | 32        | 0.31%   |
| 3200x1800 (QHD+)   | 31        | 0.3%    |
| Unknown            | 28        | 0.27%   |
| 1024x768 (XGA)     | 25        | 0.24%   |
| 2560x1080          | 23        | 0.22%   |
| 2256x1504          | 22        | 0.21%   |
| 1680x945           | 21        | 0.21%   |
| 3840x1080          | 19        | 0.19%   |
| 1920x540           | 16        | 0.16%   |
| 1360x768           | 15        | 0.15%   |
| 1920x1280          | 12        | 0.12%   |
| 3000x2000          | 11        | 0.11%   |
| 1600x1200          | 10        | 0.1%    |
| 1400x1050          | 10        | 0.1%    |
| 3840x1600          | 7         | 0.07%   |
| 2520x1680          | 7         | 0.07%   |
| 1280x720 (HD)      | 7         | 0.07%   |
| 3072x1920          | 6         | 0.06%   |
| 2304x1440          | 5         | 0.05%   |
| 2288x1287          | 5         | 0.05%   |
| 1280x768           | 5         | 0.05%   |
| 3840x1200          | 3         | 0.03%   |
| 2240x1400          | 3         | 0.03%   |
| 2160x1350          | 3         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 4047      | 37.5%   |
| 17      | 1400      | 12.97%  |
| 13      | 1277      | 11.83%  |
| 14      | 1245      | 11.54%  |
| 24      | 429       | 3.98%   |
| 27      | 383       | 3.55%   |
| 12      | 377       | 3.49%   |
| 23      | 230       | 2.13%   |
| Unknown | 185       | 1.71%   |
| 11      | 164       | 1.52%   |
| 21      | 136       | 1.26%   |
| 16      | 107       | 0.99%   |
| 10      | 102       | 0.95%   |
| 18      | 91        | 0.84%   |
| 34      | 69        | 0.64%   |
| 31      | 67        | 0.62%   |
| 22      | 62        | 0.57%   |
| 19      | 62        | 0.57%   |
| 7       | 51        | 0.47%   |
| 84      | 38        | 0.35%   |
| 25      | 25        | 0.23%   |
| 40      | 24        | 0.22%   |
| 72      | 23        | 0.21%   |
| 3       | 23        | 0.21%   |
| 20      | 21        | 0.19%   |
| 54      | 20        | 0.19%   |
| 32      | 18        | 0.17%   |
| 26      | 13        | 0.12%   |
| 28      | 12        | 0.11%   |
| 48      | 11        | 0.1%    |
| 8       | 9         | 0.08%   |
| 37      | 8         | 0.07%   |
| 52      | 7         | 0.06%   |
| 33      | 7         | 0.06%   |
| 35      | 6         | 0.06%   |
| 142     | 5         | 0.05%   |
| 65      | 5         | 0.05%   |
| 49      | 5         | 0.05%   |
| 36      | 5         | 0.05%   |
| 55      | 3         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5835      | 54.49%  |
| 351-400        | 1592      | 14.87%  |
| 201-300        | 1323      | 12.35%  |
| 501-600        | 981       | 9.16%   |
| 401-500        | 325       | 3.03%   |
| Unknown        | 185       | 1.73%   |
| 601-700        | 120       | 1.12%   |
| 701-800        | 100       | 0.93%   |
| 1-100          | 69        | 0.64%   |
| 1501-2000      | 59        | 0.55%   |
| 1001-1500      | 57        | 0.53%   |
| 801-900        | 40        | 0.37%   |
| 101-200        | 10        | 0.09%   |
| 901-1000       | 8         | 0.07%   |
| More than 2000 | 5         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 7825      | 80.9%   |
| 16/10   | 1285      | 13.28%  |
| Unknown | 139       | 1.44%   |
| 3/2     | 119       | 1.23%   |
| 21/9    | 86        | 0.89%   |
| 5/4     | 58        | 0.6%    |
| 0.67    | 50        | 0.52%   |
| 4/3     | 49        | 0.51%   |
| 6/5     | 28        | 0.29%   |
| 32/9    | 19        | 0.2%    |
| 1.00    | 5         | 0.05%   |
| 0.62    | 3         | 0.03%   |
| 3.73    | 2         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.65    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 4041      | 37.5%   |
| 81-90          | 1981      | 18.38%  |
| 121-130        | 1185      | 11%     |
| 201-250        | 647       | 6%      |
| 71-80          | 527       | 4.89%   |
| 301-350        | 393       | 3.65%   |
| 61-70          | 372       | 3.45%   |
| 131-140        | 202       | 1.87%   |
| 251-300        | 185       | 1.72%   |
| Unknown        | 185       | 1.72%   |
| 351-500        | 177       | 1.64%   |
| 51-60          | 167       | 1.55%   |
| 151-200        | 132       | 1.22%   |
| More than 1000 | 104       | 0.97%   |
| 141-150        | 101       | 0.94%   |
| 41-50          | 100       | 0.93%   |
| 111-120        | 92        | 0.85%   |
| 1-40           | 79        | 0.73%   |
| 501-1000       | 64        | 0.59%   |
| 91-100         | 42        | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 4350      | 41.07%  |
| 101-120       | 3121      | 29.47%  |
| 51-100        | 1752      | 16.54%  |
| 161-240       | 784       | 7.4%    |
| More than 240 | 328       | 3.1%    |
| Unknown       | 185       | 1.75%   |
| 1-50          | 72        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 8075      | 80.52%  |
| 2     | 1426      | 14.22%  |
| 0     | 313       | 3.12%   |
| 3     | 202       | 2.01%   |
| 4     | 12        | 0.12%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 5573      | 35.21%  |
| Realtek Semiconductor             | 4676      | 29.54%  |
| Qualcomm Atheros                  | 2157      | 13.63%  |
| Broadcom                          | 1061      | 6.7%    |
| Broadcom Limited                  | 243       | 1.54%   |
| Marvell Technology Group          | 228       | 1.44%   |
| Sierra Wireless                   | 194       | 1.23%   |
| Ericsson Business Mobile Networks | 181       | 1.14%   |
| MediaTek                          | 164       | 1.04%   |
| Dell                              | 161       | 1.02%   |
| Ralink                            | 114       | 0.72%   |
| ASIX Electronics                  | 113       | 0.71%   |
| Lenovo                            | 106       | 0.67%   |
| Hewlett-Packard                   | 72        | 0.45%   |
| Nvidia                            | 71        | 0.45%   |
| TP-Link                           | 63        | 0.4%    |
| DisplayLink                       | 61        | 0.39%   |
| Huawei Technologies               | 60        | 0.38%   |
| Ralink Technology                 | 53        | 0.33%   |
| Fibocom                           | 44        | 0.28%   |
| Samsung Electronics               | 40        | 0.25%   |
| JMicron Technology                | 30        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 25        | 0.16%   |
| Qualcomm                          | 25        | 0.16%   |
| Edimax Technology                 | 23        | 0.15%   |
| ASUSTek Computer                  | 22        | 0.14%   |
| AVM                               | 18        | 0.11%   |
| Xiaomi                            | 17        | 0.11%   |
| NetGear                           | 15        | 0.09%   |
| VIA Technologies                  | 13        | 0.08%   |
| Qualcomm Atheros Communications   | 13        | 0.08%   |
| D-Link                            | 12        | 0.08%   |
| D-Link System                     | 11        | 0.07%   |
| Attansic Technology               | 11        | 0.07%   |
| Apple                             | 11        | 0.07%   |
| U-Blox                            | 9         | 0.06%   |
| Google                            | 9         | 0.06%   |
| Microsoft                         | 7         | 0.04%   |
| Arduino SA                        | 7         | 0.04%   |
| AMD                               | 7         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 3018      | 15.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 603       | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 564       | 2.89%   |
| Intel Wi-Fi 6 AX200                                                     | 524       | 2.68%   |
| Intel Wireless 8265 / 8275                                              | 453       | 2.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 426       | 2.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 405       | 2.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 398       | 2.04%   |
| Intel Wireless 7260                                                     | 392       | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 336       | 1.72%   |
| Intel Wireless 8260                                                     | 313       | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 295       | 1.51%   |
| Intel Wireless 7265                                                     | 271       | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 254       | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 237       | 1.21%   |
| Intel Wi-Fi 6 AX201                                                     | 219       | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 202       | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 201       | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 182       | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 168       | 0.86%   |
| Intel 82577LM Gigabit Network Connection                                | 164       | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 157       | 0.8%    |
| Intel Wireless 3160                                                     | 151       | 0.77%   |
| Intel Ethernet Connection I219-LM                                       | 151       | 0.77%   |
| Intel Wireless 3165                                                     | 149       | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 149       | 0.76%   |
| Intel WiFi Link 5100                                                    | 148       | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 147       | 0.75%   |
| Intel Wireless-AC 9260                                                  | 147       | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 146       | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 145       | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 144       | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 136       | 0.7%    |
| Intel Ethernet Connection I217-LM                                       | 132       | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                | 132       | 0.68%   |
| Intel Ethernet Connection I218-LM                                       | 130       | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 125       | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 124       | 0.64%   |
| Intel Ethernet Connection (4) I219-V                                    | 121       | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                   | 116       | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5303      | 51.58%  |
| Qualcomm Atheros                | 1791      | 17.42%  |
| Realtek Semiconductor           | 1432      | 13.93%  |
| Broadcom                        | 739       | 7.19%   |
| Sierra Wireless                 | 194       | 1.89%   |
| MediaTek                        | 160       | 1.56%   |
| Broadcom Limited                | 123       | 1.2%    |
| Ralink                          | 114       | 1.11%   |
| Dell                            | 82        | 0.8%    |
| TP-Link                         | 55        | 0.53%   |
| Ralink Technology               | 53        | 0.52%   |
| Fibocom                         | 44        | 0.43%   |
| Edimax Technology               | 23        | 0.22%   |
| ASUSTek Computer                | 22        | 0.21%   |
| Qualcomm                        | 20        | 0.19%   |
| AVM                             | 18        | 0.18%   |
| Hewlett-Packard                 | 17        | 0.17%   |
| NetGear                         | 14        | 0.14%   |
| Qualcomm Atheros Communications | 13        | 0.13%   |
| D-Link System                   | 11        | 0.11%   |
| D-Link                          | 11        | 0.11%   |
| Microsoft                       | 6         | 0.06%   |
| ZyDAS                           | 5         | 0.05%   |
| Belkin Components               | 4         | 0.04%   |
| Winbond Electronics             | 3         | 0.03%   |
| Wacom                           | 3         | 0.03%   |
| Fujitsu Siemens Computers       | 3         | 0.03%   |
| ZyXEL Communications            | 2         | 0.02%   |
| Texas Instruments               | 2         | 0.02%   |
| Sitecom Europe                  | 2         | 0.02%   |
| Samsung Electronics             | 2         | 0.02%   |
| Quectel Wireless Solutions      | 2         | 0.02%   |
| Micro Star International        | 2         | 0.02%   |
| Linksys                         | 2         | 0.02%   |
| Qcom                            | 1         | 0.01%   |
| Marvell Technology Group        | 1         | 0.01%   |
| BUFFALO                         | 1         | 0.01%   |
| Acer NeWeb                      | 1         | 0.01%   |
| AboCom Systems                  | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 524       | 5.07%   |
| Intel Wireless 8265 / 8275                                              | 453       | 4.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 405       | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 398       | 3.85%   |
| Intel Wireless 7260                                                     | 392       | 3.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 336       | 3.25%   |
| Intel Wireless 8260                                                     | 313       | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 295       | 2.85%   |
| Intel Wireless 7265                                                     | 271       | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 254       | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 237       | 2.29%   |
| Intel Wi-Fi 6 AX201                                                     | 219       | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 202       | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 201       | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 182       | 1.76%   |
| Intel Centrino Ultimate-N 6300                                          | 168       | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 157       | 1.52%   |
| Intel Wireless 3160                                                     | 151       | 1.46%   |
| Intel Wireless 3165                                                     | 149       | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 149       | 1.44%   |
| Intel WiFi Link 5100                                                    | 148       | 1.43%   |
| Intel Wireless-AC 9260                                                  | 147       | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 146       | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 145       | 1.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 144       | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 136       | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 125       | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 124       | 1.2%    |
| Intel Centrino Wireless-N 2230                                          | 115       | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 115       | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 109       | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 108       | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 103       | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 92        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 90        | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 88        | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 86        | 0.83%   |
| Intel Centrino Advanced-N 6235                                          | 84        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 83        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 78        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 4126      | 47.82%  |
| Intel                                  | 2427      | 28.13%  |
| Qualcomm Atheros                       | 665       | 7.71%   |
| Broadcom                               | 467       | 5.41%   |
| Marvell Technology Group               | 227       | 2.63%   |
| Broadcom Limited                       | 127       | 1.47%   |
| ASIX Electronics                       | 113       | 1.31%   |
| Lenovo                                 | 106       | 1.23%   |
| Nvidia                                 | 71        | 0.82%   |
| DisplayLink                            | 61        | 0.71%   |
| JMicron Technology                     | 30        | 0.35%   |
| Samsung Electronics                    | 25        | 0.29%   |
| Silicon Integrated Systems [SiS]       | 23        | 0.27%   |
| Huawei Technologies                    | 22        | 0.25%   |
| Xiaomi                                 | 17        | 0.2%    |
| Hewlett-Packard                        | 17        | 0.2%    |
| VIA Technologies                       | 13        | 0.15%   |
| Attansic Technology                    | 11        | 0.13%   |
| Apple                                  | 11        | 0.13%   |
| Google                                 | 9         | 0.1%    |
| TP-Link                                | 8         | 0.09%   |
| Qualcomm                               | 5         | 0.06%   |
| Microchip Technology                   | 5         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.05%   |
| HMD Global                             | 4         | 0.05%   |
| ULi Electronics                        | 3         | 0.03%   |
| T & A Mobile Phones                    | 3         | 0.03%   |
| OPPO Electronics                       | 3         | 0.03%   |
| MosChip Semiconductor                  | 3         | 0.03%   |
| MediaTek                               | 3         | 0.03%   |
| ICS Advent                             | 2         | 0.02%   |
| Davicom Semiconductor                  | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.01%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.01%   |
| Research In Motion                     | 1         | 0.01%   |
| Promise Technology                     | 1         | 0.01%   |
| NetGear                                | 1         | 0.01%   |
| National Semiconductor                 | 1         | 0.01%   |
| Motorola PCS                           | 1         | 0.01%   |
| Microsoft                              | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3018      | 34.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 603       | 6.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 564       | 6.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 426       | 4.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 164       | 1.88%   |
| Intel Ethernet Connection I219-LM                                              | 151       | 1.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 147       | 1.69%   |
| Intel Ethernet Connection I217-LM                                              | 132       | 1.51%   |
| Intel 82567LM Gigabit Network Connection                                       | 132       | 1.51%   |
| Intel Ethernet Connection I218-LM                                              | 130       | 1.49%   |
| Intel Ethernet Connection (4) I219-V                                           | 121       | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                                          | 116       | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                                          | 112       | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 103       | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 95        | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 73        | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 73        | 0.84%   |
| Intel Ethernet Connection I219-V                                               | 68        | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 66        | 0.76%   |
| Intel 82579V Gigabit Network Connection                                        | 63        | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                           | 60        | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 54        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 53        | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 53        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 52        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                          | 48        | 0.55%   |
| Intel 82566MM Gigabit Network Connection                                       | 46        | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 46        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 45        | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                              | 44        | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 44        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                                          | 43        | 0.49%   |
| Nvidia MCP79 Ethernet                                                          | 42        | 0.48%   |
| Intel Ethernet Connection (10) I219-V                                          | 42        | 0.48%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 42        | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 41        | 0.47%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 40        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 37        | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 37        | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                          | 35        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9605      | 52.41%  |
| Ethernet | 8264      | 45.1%   |
| Modem    | 442       | 2.41%   |
| Unknown  | 14        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7696      | 73.25%  |
| Ethernet | 2809      | 26.74%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 7590      | 77.58%  |
| 1     | 1986      | 20.3%   |
| 0     | 117       | 1.2%    |
| 3     | 88        | 0.9%    |
| 4     | 2         | 0.02%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6624      | 65.71%  |
| Yes  | 3456      | 34.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3555      | 48.49%  |
| Realtek Semiconductor           | 821       | 11.2%   |
| Broadcom                        | 530       | 7.23%   |
| Qualcomm Atheros Communications | 406       | 5.54%   |
| Lite-On Technology              | 358       | 4.88%   |
| Foxconn / Hon Hai               | 349       | 4.76%   |
| IMC Networks                    | 310       | 4.23%   |
| Apple                           | 197       | 2.69%   |
| Dell                            | 183       | 2.5%    |
| Cambridge Silicon Radio         | 150       | 2.05%   |
| Hewlett-Packard                 | 95        | 1.3%    |
| Toshiba                         | 72        | 0.98%   |
| Realtek                         | 57        | 0.78%   |
| Foxconn International           | 44        | 0.6%    |
| ASUSTek Computer                | 35        | 0.48%   |
| Alps Electric                   | 32        | 0.44%   |
| Askey Computer                  | 29        | 0.4%    |
| Ralink                          | 23        | 0.31%   |
| Taiyo Yuden                     | 17        | 0.23%   |
| Chicony Electronics             | 11        | 0.15%   |
| USI                             | 9         | 0.12%   |
| Ralink Technology               | 9         | 0.12%   |
| Qcom                            | 7         | 0.1%    |
| MediaTek                        | 6         | 0.08%   |
| Fujitsu                         | 6         | 0.08%   |
| Belkin Components               | 6         | 0.08%   |
| Edimax Technology               | 4         | 0.05%   |
| TP-Link                         | 2         | 0.03%   |
| Syntek                          | 1         | 0.01%   |
| Sitecom Europe                  | 1         | 0.01%   |
| SINO WEALTH                     | 1         | 0.01%   |
| Roper                           | 1         | 0.01%   |
| Micro Star International        | 1         | 0.01%   |
| Logitech                        | 1         | 0.01%   |
| Integrated System Solution      | 1         | 0.01%   |
| Fujitsu Siemens Computers       | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1587      | 21.64%  |
| Intel AX201 Bluetooth                               | 523       | 7.13%   |
| Realtek Bluetooth Radio                             | 502       | 6.84%   |
| Intel AX200 Bluetooth                               | 498       | 6.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 367       | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 217       | 2.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 179       | 2.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 160       | 2.18%   |
| IMC Networks Bluetooth Radio                        | 160       | 2.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 150       | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 134       | 1.83%   |
| Broadcom BCM2045B (BDC-2.1)                         | 132       | 1.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 115       | 1.57%   |
| Apple Bluetooth Host Controller                     | 113       | 1.54%   |
| Lite-On Bluetooth Device                            | 106       | 1.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 103       | 1.4%    |
| Foxconn / Hon Hai Bluetooth Device                  | 102       | 1.39%   |
| Intel Bluetooth Device                              | 80        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 77        | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 77        | 1.05%   |
| Dell DW375 Bluetooth Module                         | 73        | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 71        | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 70        | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                    | 66        | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 62        | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 59        | 0.8%    |
| Realtek Bluetooth Radio                             | 57        | 0.78%   |
| Intel AX210 Bluetooth                               | 57        | 0.78%   |
| IMC Networks Bluetooth Device                       | 57        | 0.78%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 57        | 0.78%   |
| Foxconn / Hon Hai BCM20702A0                        | 52        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 49        | 0.67%   |
| Dell BCM20702A0 Bluetooth Module                    | 46        | 0.63%   |
| Realtek RTL8723B Bluetooth                          | 45        | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 44        | 0.6%    |
| Broadcom BCM2045 Bluetooth                          | 43        | 0.59%   |
| Apple Bluetooth USB Host Controller                 | 43        | 0.59%   |
| IMC Networks Wireless_Device                        | 36        | 0.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 36        | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 34        | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7715      | 64.65%  |
| AMD                              | 2112      | 17.7%   |
| Nvidia                           | 1240      | 10.39%  |
| Lenovo                           | 118       | 0.99%   |
| C-Media Electronics              | 97        | 0.81%   |
| GN Netcom                        | 91        | 0.76%   |
| Realtek Semiconductor            | 76        | 0.64%   |
| Logitech                         | 58        | 0.49%   |
| Plantronics                      | 37        | 0.31%   |
| Silicon Integrated Systems [SiS] | 28        | 0.23%   |
| Texas Instruments                | 25        | 0.21%   |
| Hewlett-Packard                  | 20        | 0.17%   |
| Focusrite-Novation               | 18        | 0.15%   |
| Generalplus Technology           | 17        | 0.14%   |
| JMTek                            | 16        | 0.13%   |
| Sennheiser Communications        | 15        | 0.13%   |
| Conexant Systems                 | 15        | 0.13%   |
| VIA Technologies                 | 13        | 0.11%   |
| Creative Technology              | 13        | 0.11%   |
| Razer USA                        | 12        | 0.1%    |
| Kingston Technology              | 12        | 0.1%    |
| RODE Microphones                 | 11        | 0.09%   |
| Apple                            | 9         | 0.08%   |
| DSEA A/S                         | 8         | 0.07%   |
| Dell                             | 8         | 0.07%   |
| SteelSeries ApS                  | 7         | 0.06%   |
| TerraTec Electronic              | 6         | 0.05%   |
| Yamaha                           | 5         | 0.04%   |
| M-Audio                          | 5         | 0.04%   |
| Fujitsu                          | 5         | 0.04%   |
| Corsair                          | 5         | 0.04%   |
| Blue Microphones                 | 5         | 0.04%   |
| BEHRINGER International          | 5         | 0.04%   |
| SAVITECH                         | 4         | 0.03%   |
| No brand                         | 4         | 0.03%   |
| Native Instruments               | 4         | 0.03%   |
| GYROCOM C&C                      | 4         | 0.03%   |
| Cambridge Silicon Radio          | 4         | 0.03%   |
| ULi Electronics                  | 3         | 0.03%   |
| Sony                             | 3         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1079      | 7.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1077      | 7.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 907       | 6.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 694       | 4.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 627       | 4.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 562       | 3.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 540       | 3.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 396       | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 394       | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 367       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 349       | 2.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 318       | 2.2%    |
| Intel Broadwell-U Audio Controller                                                                | 310       | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 309       | 2.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 306       | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 286       | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 280       | 1.94%   |
| AMD FCH Azalia Controller                                                                         | 259       | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 230       | 1.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 218       | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 215       | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 195       | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 168       | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 159       | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 149       | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 146       | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 138       | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 135       | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 134       | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 127       | 0.88%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 121       | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 112       | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 106       | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 99        | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 91        | 0.63%   |
| AMD High Definition Audio Controller                                                              | 91        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 90        | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 88        | 0.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 79        | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 78        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1897      | 32.16%  |
| SK hynix            | 1349      | 22.87%  |
| Micron Technology   | 696       | 11.8%   |
| Unknown             | 464       | 7.87%   |
| Kingston            | 436       | 7.39%   |
| Crucial             | 259       | 4.39%   |
| Ramaxel Technology  | 163       | 2.76%   |
| Elpida              | 132       | 2.24%   |
| A-DATA Technology   | 84        | 1.42%   |
| Corsair             | 78        | 1.32%   |
| Nanya Technology    | 70        | 1.19%   |
| Unknown (ABCD)      | 60        | 1.02%   |
| G.Skill             | 32        | 0.54%   |
| Unknown             | 23        | 0.39%   |
| Transcend           | 22        | 0.37%   |
| ASint Technology    | 17        | 0.29%   |
| 48spaces            | 11        | 0.19%   |
| GOODRAM             | 8         | 0.14%   |
| Avant               | 8         | 0.14%   |
| Team                | 7         | 0.12%   |
| Toshiba             | 6         | 0.1%    |
| SHARETRONIC         | 6         | 0.1%    |
| CSX                 | 6         | 0.1%    |
| Qimonda             | 5         | 0.08%   |
| Patriot             | 5         | 0.08%   |
| PNY                 | 3         | 0.05%   |
| Neo Forza           | 3         | 0.05%   |
| Lexar               | 3         | 0.05%   |
| Apacer              | 3         | 0.05%   |
| Unknown (8ECE)      | 2         | 0.03%   |
| GSkill              | 2         | 0.03%   |
| Goldkey             | 2         | 0.03%   |
| GeIL                | 2         | 0.03%   |
| ff                  | 2         | 0.03%   |
| fef5                | 2         | 0.03%   |
| Aeneon              | 2         | 0.03%   |
| 4ea5                | 2         | 0.03%   |
| ZIFEI               | 1         | 0.02%   |
| Wilk                | 1         | 0.02%   |
| Unknown (AB)        | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 92        | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 83        | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 79        | 1.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 73        | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 70        | 1.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 67        | 1.07%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 65        | 1.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 63        | 1%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 63        | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 58        | 0.92%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 58        | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 55        | 0.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 54        | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 52        | 0.83%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 51        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 48        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 47        | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 47        | 0.75%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 44        | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 44        | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 43        | 0.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 41        | 0.65%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 41        | 0.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 39        | 0.62%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 38        | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 36        | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 35        | 0.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.54%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 33        | 0.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 32        | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 32        | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 32        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 31        | 0.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.49%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 30        | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 29        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 29        | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 28        | 0.45%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 28        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2286      | 45.2%   |
| DDR3    | 1835      | 36.28%  |
| DDR2    | 263       | 5.2%    |
| LPDDR4  | 245       | 4.84%   |
| LPDDR3  | 151       | 2.99%   |
| SDRAM   | 104       | 2.06%   |
| LPDDR5  | 53        | 1.05%   |
| Unknown | 37        | 0.73%   |
| DDR5    | 34        | 0.67%   |
| DDR     | 32        | 0.63%   |
| DRAM    | 18        | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 4544      | 89.29%  |
| Row Of Chips | 439       | 8.63%   |
| Chip         | 64        | 1.26%   |
| DIMM         | 28        | 0.55%   |
| Unknown      | 14        | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1999      | 36.64%  |
| 4096  | 1682      | 30.83%  |
| 16384 | 762       | 13.97%  |
| 2048  | 659       | 12.08%  |
| 1024  | 170       | 3.12%   |
| 32768 | 153       | 2.8%    |
| 512   | 22        | 0.4%    |
| 256   | 4         | 0.07%   |
| 128   | 4         | 0.07%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1194      | 21.97%  |
| 2667    | 1058      | 19.47%  |
| 3200    | 932       | 17.15%  |
| 2400    | 364       | 6.7%    |
| 1334    | 319       | 5.87%   |
| 2133    | 232       | 4.27%   |
| 1333    | 216       | 3.97%   |
| Unknown | 149       | 2.74%   |
| 667     | 137       | 2.52%   |
| 1067    | 132       | 2.43%   |
| 4267    | 97        | 1.78%   |
| 1867    | 82        | 1.51%   |
| 800     | 68        | 1.25%   |
| 3266    | 63        | 1.16%   |
| 4199    | 58        | 1.07%   |
| 6400    | 49        | 0.9%    |
| 1066    | 41        | 0.75%   |
| 4800    | 36        | 0.66%   |
| 4266    | 35        | 0.64%   |
| 8400    | 33        | 0.61%   |
| 975     | 28        | 0.52%   |
| 2048    | 27        | 0.5%    |
| 533     | 22        | 0.4%    |
| 1866    | 13        | 0.24%   |
| 3733    | 11        | 0.2%    |
| 333     | 10        | 0.18%   |
| 2933    | 5         | 0.09%   |
| 3000    | 4         | 0.07%   |
| 2267    | 3         | 0.06%   |
| 400     | 3         | 0.06%   |
| 5500    | 2         | 0.04%   |
| 1639    | 2         | 0.04%   |
| 666     | 2         | 0.04%   |
| 266     | 2         | 0.04%   |
| 166     | 2         | 0.04%   |
| 2800    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 200     | 1         | 0.02%   |
| 100     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 56        | 33.14%  |
| Canon                 | 32        | 18.93%  |
| Brother Industries    | 27        | 15.98%  |
| Samsung Electronics   | 19        | 11.24%  |
| Seiko Epson           | 15        | 8.88%   |
| Kyocera               | 7         | 4.14%   |
| Prolific Technology   | 5         | 2.96%   |
| QinHeng Electronics   | 2         | 1.18%   |
| Lexmark International | 2         | 1.18%   |
| STMicroelectronics    | 1         | 0.59%   |
| Oki Data              | 1         | 0.59%   |
| MIIIW                 | 1         | 0.59%   |
| Dymo-CoStar           | 1         | 0.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                      | 5         | 2.96%   |
| Prolific PL2305 Parallel Port                             | 5         | 2.96%   |
| Canon PIXMA MX920 Series                                  | 5         | 2.96%   |
| HP Deskjet 2540 series                                    | 4         | 2.37%   |
| Brother DCP-7055W                                         | 4         | 2.37%   |
| Kyocera Mita FS-820                                       | 3         | 1.78%   |
| HP ENVY 4520 series                                       | 3         | 1.78%   |
| HP Deskjet 2050 J510                                      | 3         | 1.78%   |
| HP Deskjet 1050 J410                                      | 3         | 1.78%   |
| Seiko Epson XP-4100 Series                                | 2         | 1.18%   |
| Seiko Epson WF-2510 Series                                | 2         | 1.18%   |
| Samsung CLX-3300 Series                                   | 2         | 1.18%   |
| QinHeng CH340S                                            | 2         | 1.18%   |
| Lexmark International E360d                               | 2         | 1.18%   |
| Kyocera FS-1030D printer                                  | 2         | 1.18%   |
| HP Officejet 4620 series                                  | 2         | 1.18%   |
| HP LaserJet 200 colorMFP M275nw                           | 2         | 1.18%   |
| HP EWS UPD                                                | 2         | 1.18%   |
| HP ENVY 4500 series                                       | 2         | 1.18%   |
| HP DeskJet 3630 series                                    | 2         | 1.18%   |
| HP DeskJet 2700 series                                    | 2         | 1.18%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 1.18%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.18%   |
| Canon TS700 series                                        | 2         | 1.18%   |
| Canon TR8500 series                                       | 2         | 1.18%   |
| Canon PIXMA MG3600 Series                                 | 2         | 1.18%   |
| Brother MFC-L3750CDW                                      | 2         | 1.18%   |
| Brother MFC-L2710DW series                                | 2         | 1.18%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.59%   |
| Seiko Epson XP-3100 Series                                | 1         | 0.59%   |
| Seiko Epson XP-2100 Series                                | 1         | 0.59%   |
| Seiko Epson WF-2530 Series                                | 1         | 0.59%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.59%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.59%   |
| Seiko Epson Printer                                       | 1         | 0.59%   |
| Seiko Epson L4260 Series                                  | 1         | 0.59%   |
| Seiko Epson ET-2720 Series                                | 1         | 0.59%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.59%   |
| Seiko Epson Epson Stylus Photo 1500                       | 1         | 0.59%   |
| Seiko Epson AcuLaser C1700                                | 1         | 0.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 29        | 74.36%  |
| Seiko Epson                                    | 5         | 12.82%  |
| Siemens Information and Communication Products | 1         | 2.56%   |
| Plustek                                        | 1         | 2.56%   |
| Mustek Systems                                 | 1         | 2.56%   |
| Hewlett-Packard                                | 1         | 2.56%   |
| AGFA-Gevaert NV                                | 1         | 2.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                         | 5         | 12.82%  |
| Canon CanoScan N670U/N676U/LiDE 20                                              | 4         | 10.26%  |
| Canon CanoScan LiDE 110                                                         | 4         | 10.26%  |
| Canon CanoScan LIDE 25                                                          | 3         | 7.69%   |
| Canon CanoScan LiDE 500F                                                        | 2         | 5.13%   |
| Canon CanoScan LiDE 210                                                         | 2         | 5.13%   |
| Canon CanoScan LiDE 100                                                         | 2         | 5.13%   |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 2.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                         | 1         | 2.56%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                         | 1         | 2.56%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                        | 1         | 2.56%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                              | 1         | 2.56%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                               | 1         | 2.56%   |
| Plustek OpticPro UT12/16/24 Scanner                                             | 1         | 2.56%   |
| Mustek Systems SNAPSCAN e22                                                     | 1         | 2.56%   |
| HP HP4470C                                                                      | 1         | 2.56%   |
| Canon CanoScan LiDE 90                                                          | 1         | 2.56%   |
| Canon CanoScan LiDE 600F                                                        | 1         | 2.56%   |
| Canon CanoScan LiDE 60                                                          | 1         | 2.56%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                          | 1         | 2.56%   |
| Canon CanoScan LiDE 200                                                         | 1         | 2.56%   |
| Canon CanoScan LiDE 120                                                         | 1         | 2.56%   |
| Canon CanoScan 3200F                                                            | 1         | 2.56%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                              | 1         | 2.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2526      | 30.11%  |
| IMC Networks                           | 778       | 9.27%   |
| Realtek Semiconductor                  | 575       | 6.85%   |
| Microdia                               | 566       | 6.75%   |
| Bison Electronics                      | 506       | 6.03%   |
| Quanta                                 | 406       | 4.84%   |
| Sunplus Innovation Technology          | 372       | 4.43%   |
| Suyin                                  | 331       | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 328       | 3.91%   |
| Acer                                   | 266       | 3.17%   |
| Lite-On Technology                     | 219       | 2.61%   |
| Syntek                                 | 193       | 2.3%    |
| Apple                                  | 163       | 1.94%   |
| Logitech                               | 149       | 1.78%   |
| Silicon Motion                         | 114       | 1.36%   |
| Ricoh                                  | 110       | 1.31%   |
| Alcor Micro                            | 107       | 1.28%   |
| Luxvisions Innotech Limited            | 94        | 1.12%   |
| Lenovo                                 | 93        | 1.11%   |
| Z-Star Microelectronics                | 56        | 0.67%   |
| ALi                                    | 54        | 0.64%   |
| Samsung Electronics                    | 36        | 0.43%   |
| Primax Electronics                     | 34        | 0.41%   |
| DigiTech                               | 29        | 0.35%   |
| Importek                               | 26        | 0.31%   |
| SunplusIT                              | 20        | 0.24%   |
| Sonix Technology                       | 20        | 0.24%   |
| Microsoft                              | 18        | 0.21%   |
| Sunplus Technology                     | 15        | 0.18%   |
| Generalplus Technology                 | 14        | 0.17%   |
| Genesys Logic                          | 11        | 0.13%   |
| USB Camera                             | 10        | 0.12%   |
| OmniVision Technologies                | 9         | 0.11%   |
| eMPIA Technology                       | 9         | 0.11%   |
| Intel                                  | 8         | 0.1%    |
| Y Media                                | 7         | 0.08%   |
| Creative Technology                    | 7         | 0.08%   |
| ARC International                      | 6         | 0.07%   |
| Alpha Imaging Technology               | 6         | 0.07%   |
| KYE Systems (Mouse Systems)            | 5         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 537       | 6.38%   |
| IMC Networks Integrated Camera                   | 285       | 3.39%   |
| Chicony HD Webcam                                | 269       | 3.2%    |
| Microdia Integrated_Webcam_HD                    | 199       | 2.36%   |
| Realtek Integrated_Webcam_HD                     | 147       | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam                | 145       | 1.72%   |
| Chicony USB2.0 Camera                            | 133       | 1.58%   |
| Bison Integrated Camera                          | 131       | 1.56%   |
| Chicony FJ Camera                                | 122       | 1.45%   |
| Syntek Integrated Camera                         | 107       | 1.27%   |
| Lite-On Integrated Camera                        | 99        | 1.18%   |
| Chicony USB 2.0 Camera                           | 88        | 1.05%   |
| Microdia Integrated Webcam                       | 84        | 1%      |
| Sunplus HD WebCam                                | 79        | 0.94%   |
| Quanta HD User Facing                            | 76        | 0.9%    |
| Chicony USB2.0 HD UVC WebCam                     | 75        | 0.89%   |
| Chicony HD User Facing                           | 74        | 0.88%   |
| Sunplus Integrated_Webcam_HD                     | 73        | 0.87%   |
| Chicony HP HD Camera                             | 72        | 0.86%   |
| Acer Integrated Camera                           | 72        | 0.86%   |
| Bison SunplusIT Integrated Camera                | 71        | 0.84%   |
| Chicony Integrated Camera (1280x720@30)          | 67        | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 63        | 0.75%   |
| Quanta HP Webcam                                 | 60        | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 59        | 0.7%    |
| Chicony HP Webcam                                | 59        | 0.7%    |
| Chicony TOSHIBA Web Camera - HD                  | 57        | 0.68%   |
| Quanta HP HD Camera                              | 56        | 0.67%   |
| Chicony Integrated IR Camera                     | 55        | 0.65%   |
| Apple Built-in iSight                            | 55        | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 53        | 0.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 53        | 0.63%   |
| Realtek USB Camera                               | 52        | 0.62%   |
| Chicony VGA Webcam                               | 48        | 0.57%   |
| Realtek Lenovo EasyCamera                        | 46        | 0.55%   |
| Chicony HP TrueVision HD Camera                  | 46        | 0.55%   |
| Chicony EasyCamera                               | 46        | 0.55%   |
| Acer Lenovo EasyCamera                           | 46        | 0.55%   |
| Apple FaceTime HD Camera                         | 45        | 0.53%   |
| ALi Gateway Webcam                               | 45        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 666       | 32.05%  |
| Synaptics                          | 534       | 25.7%   |
| Shenzhen Goodix Technology         | 259       | 12.46%  |
| AuthenTec                          | 192       | 9.24%   |
| Upek                               | 157       | 7.56%   |
| LighTuning Technology              | 132       | 6.35%   |
| Elan Microelectronics              | 82        | 3.95%   |
| STMicroelectronics                 | 37        | 1.78%   |
| HOLTEK                             | 10        | 0.48%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 0.29%   |
| Samsung Electronics                | 1         | 0.05%   |
| Next Biometrics                    | 1         | 0.05%   |
| Focal-systems.Corp                 | 1         | 0.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 230       | 11.07%  |
| Shenzhen Goodix  FingerPrint Device                                        | 160       | 7.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 148       | 7.12%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 126       | 6.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 114       | 5.49%   |
| Validity Sensors Synaptics WBDI                                            | 80        | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 79        | 3.8%    |
| AuthenTec AES2810                                                          | 69        | 3.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 67        | 3.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 59        | 2.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 58        | 2.79%   |
| Elan ELAN:Fingerprint                                                      | 51        | 2.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 46        | 2.21%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 45        | 2.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 45        | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 42        | 2.02%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 41        | 1.97%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 40        | 1.92%   |
| Shenzhen Goodix FingerPrint                                                | 40        | 1.92%   |
| STMicroelectronics Fingerprint Reader                                      | 37        | 1.78%   |
| Validity Sensors VFS491                                                    | 31        | 1.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 31        | 1.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 30        | 1.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 30        | 1.44%   |
| AuthenTec AES1600                                                          | 30        | 1.44%   |
| Elan ELAN:ARM-M4                                                           | 29        | 1.4%    |
| AuthenTec Fingerprint Sensor                                               | 29        | 1.4%    |
| LighTuning Fingerprint Reader                                              | 28        | 1.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 26        | 1.25%   |
| Synaptics UWP WBDI                                                         | 24        | 1.15%   |
| Unknown                                                                    | 21        | 1.01%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 19        | 0.91%   |
| Validity Sensors Fingerprint scanner                                       | 19        | 0.91%   |
| Synaptics UWP WBDI Device                                                  | 15        | 0.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 0.72%   |
| Synaptics WBDI Device                                                      | 13        | 0.63%   |
| Synaptics WBDI                                                             | 13        | 0.63%   |
| Synaptics  WBDI                                                            | 13        | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 11        | 0.53%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 11        | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 505       | 40.73%  |
| Broadcom                  | 377       | 30.4%   |
| O2 Micro                  | 116       | 9.35%   |
| Lenovo                    | 106       | 8.55%   |
| Upek                      | 78        | 6.29%   |
| Gemalto (was Gemplus)     | 15        | 1.21%   |
| Yubico.com                | 12        | 0.97%   |
| OmniKey                   | 7         | 0.56%   |
| Clay Logic                | 6         | 0.48%   |
| SCM Microsystems          | 4         | 0.32%   |
| Reiner SCT Kartensysteme  | 4         | 0.32%   |
| NXP Semiconductors        | 2         | 0.16%   |
| Cherry                    | 2         | 0.16%   |
| Realtek Semiconductor     | 1         | 0.08%   |
| Purism, SPC               | 1         | 0.08%   |
| Microchip Technology      | 1         | 0.08%   |
| Kobil Systems             | 1         | 0.08%   |
| In Focus Systems          | 1         | 0.08%   |
| Fujitsu Siemens Computers | 1         | 0.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 505       | 40.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 153       | 12.34%  |
| Lenovo Integrated Smart Card Reader                                          | 106       | 8.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 104       | 8.39%   |
| Broadcom 5880                                                                | 84        | 6.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 78        | 6.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 77        | 6.21%   |
| Broadcom 58200                                                               | 57        | 4.6%    |
| O2 Micro Oz776 SmartCard Reader                                              | 12        | 0.97%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 9         | 0.73%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 8         | 0.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 0.56%   |
| Clay Logic Nitrokey Pro                                                      | 6         | 0.48%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 6         | 0.48%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.24%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 3         | 0.24%   |
| OmniKey CardMan 4321                                                         | 3         | 0.24%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.16%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.16%   |
| NXP Semiconductors PR533                                                     | 2         | 0.16%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.16%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.08%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.08%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.08%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.08%   |
| Purism, SPC Librem Key                                                       | 1         | 0.08%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.08%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.08%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.08%   |
| Kobil Systems Smart Token                                                    | 1         | 0.08%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.08%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5740      | 57.16%  |
| 1     | 3180      | 31.67%  |
| 2     | 894       | 8.9%    |
| 3     | 169       | 1.68%   |
| 4     | 34        | 0.34%   |
| 5     | 17        | 0.17%   |
| 6     | 4         | 0.04%   |
| 7     | 3         | 0.03%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 2051      | 37.01%  |
| Chipcard                 | 1108      | 20%     |
| Graphics card            | 871       | 15.72%  |
| Net/wireless             | 526       | 9.49%   |
| Multimedia controller    | 252       | 4.55%   |
| Camera                   | 140       | 2.53%   |
| Storage                  | 139       | 2.51%   |
| Communication controller | 113       | 2.04%   |
| Card reader              | 89        | 1.61%   |
| Bluetooth                | 85        | 1.53%   |
| Sound                    | 45        | 0.81%   |
| Modem                    | 44        | 0.79%   |
| Net/ethernet             | 29        | 0.52%   |
| Network                  | 16        | 0.29%   |
| Flash memory             | 11        | 0.2%    |
| Unassigned class         | 5         | 0.09%   |
| Storage/ide              | 5         | 0.09%   |
| Firewire controller      | 4         | 0.07%   |
| Dvb card                 | 3         | 0.05%   |
| Storage/raid             | 2         | 0.04%   |
| Tv card                  | 1         | 0.02%   |
| Storage/nvme             | 1         | 0.02%   |
| Storage/ata              | 1         | 0.02%   |

