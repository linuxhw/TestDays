Fedora 40 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 40.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 2743

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZHAN 66 Pro A 14 G4 Note... | [0c0d5510fc](https://linux-hardware.org/?probe=0c0d5510fc) | Jan 05, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 21G2... | [f1a3b79f94](https://linux-hardware.org/?probe=f1a3b79f94) | Dec 26, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [a16e1a46ec](https://linux-hardware.org/?probe=a16e1a46ec) | Dec 25, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [0659ed4270](https://linux-hardware.org/?probe=0659ed4270) | Dec 25, 2024 |
| Lenovo        | Yoga 900-13ISK 80MK         | [7852114da0](https://linux-hardware.org/?probe=7852114da0) | Dec 24, 2024 |
| Apple         | MacBookPro14,2              | [fded50dece](https://linux-hardware.org/?probe=fded50dece) | Dec 24, 2024 |
| TUXEDO        | N650DU                      | [00621c75d7](https://linux-hardware.org/?probe=00621c75d7) | Dec 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7bfad25e97](https://linux-hardware.org/?probe=7bfad25e97) | Dec 22, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [26283d6910](https://linux-hardware.org/?probe=26283d6910) | Dec 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | [fff8bed544](https://linux-hardware.org/?probe=fff8bed544) | Dec 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | [02f1237767](https://linux-hardware.org/?probe=02f1237767) | Dec 19, 2024 |
| HP            | 15 Notebook PC              | [d4d74d7666](https://linux-hardware.org/?probe=d4d74d7666) | Dec 19, 2024 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [9c999b2e96](https://linux-hardware.org/?probe=9c999b2e96) | Dec 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c80c3adbe0](https://linux-hardware.org/?probe=c80c3adbe0) | Dec 17, 2024 |
| ASUSTek       | X555LF                      | [7c3dbd59b5](https://linux-hardware.org/?probe=7c3dbd59b5) | Dec 17, 2024 |
| Dell          | Latitude E5570              | [5eb8637f79](https://linux-hardware.org/?probe=5eb8637f79) | Dec 15, 2024 |
| Dell          | Latitude E5570              | [c1af283f5f](https://linux-hardware.org/?probe=c1af283f5f) | Dec 14, 2024 |
| Intel Clie... | LAPBC510                    | [ad76cb1437](https://linux-hardware.org/?probe=ad76cb1437) | Dec 13, 2024 |
| HP            | Laptop 15-dw3xxx            | [6b8ce5850b](https://linux-hardware.org/?probe=6b8ce5850b) | Dec 12, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [b8fc7010b0](https://linux-hardware.org/?probe=b8fc7010b0) | Dec 12, 2024 |
| Lenovo        | ThinkPad E525 12003NG       | [ae0a08738a](https://linux-hardware.org/?probe=ae0a08738a) | Dec 09, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [39eb234a0f](https://linux-hardware.org/?probe=39eb234a0f) | Dec 09, 2024 |
| HP            | ProBook 430 G5              | [d6fbd54c05](https://linux-hardware.org/?probe=d6fbd54c05) | Dec 07, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [3dafc8c3c6](https://linux-hardware.org/?probe=3dafc8c3c6) | Dec 06, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [34f8b6bc0b](https://linux-hardware.org/?probe=34f8b6bc0b) | Dec 06, 2024 |
| HP            | ProBook 430 G2              | [7d778aaa23](https://linux-hardware.org/?probe=7d778aaa23) | Dec 04, 2024 |
| Dell          | XPS 15 9570                 | [047e3e03f0](https://linux-hardware.org/?probe=047e3e03f0) | Dec 03, 2024 |
| Acer          | Aspire E5-771G              | [46262b8198](https://linux-hardware.org/?probe=46262b8198) | Dec 02, 2024 |
| HONOR         | FRI-FXX                     | [d5c89a650a](https://linux-hardware.org/?probe=d5c89a650a) | Dec 02, 2024 |
| Toshiba       | Satellite L850              | [d7efdeae96](https://linux-hardware.org/?probe=d7efdeae96) | Dec 01, 2024 |
| Toshiba       | Satellite L850              | [510d7773fa](https://linux-hardware.org/?probe=510d7773fa) | Dec 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [7af06c00e5](https://linux-hardware.org/?probe=7af06c00e5) | Dec 01, 2024 |
| Acer          | Aspire ES1-572              | [612f5558b5](https://linux-hardware.org/?probe=612f5558b5) | Nov 26, 2024 |
| Apple         | MacBookPro9,2               | [5b7f540652](https://linux-hardware.org/?probe=5b7f540652) | Nov 24, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | [9743c11187](https://linux-hardware.org/?probe=9743c11187) | Nov 24, 2024 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [da194d6897](https://linux-hardware.org/?probe=da194d6897) | Nov 23, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | [2b9ffeae7c](https://linux-hardware.org/?probe=2b9ffeae7c) | Nov 23, 2024 |
| HUAWEI        | MDF-XX                      | [5345ae504f](https://linux-hardware.org/?probe=5345ae504f) | Nov 23, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [40b777045b](https://linux-hardware.org/?probe=40b777045b) | Nov 21, 2024 |
| Lenovo        | ThinkPad P50 20EQS0SM01     | [bd76e1e326](https://linux-hardware.org/?probe=bd76e1e326) | Nov 18, 2024 |
| Samsung       | 550XDA                      | [01ef3193ec](https://linux-hardware.org/?probe=01ef3193ec) | Nov 17, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [4ecadd4fa2](https://linux-hardware.org/?probe=4ecadd4fa2) | Nov 17, 2024 |
| ASUSTek       | X550JK                      | [82b0e4d59c](https://linux-hardware.org/?probe=82b0e4d59c) | Nov 17, 2024 |
| ASUSTek       | X550JK                      | [b343c33a78](https://linux-hardware.org/?probe=b343c33a78) | Nov 17, 2024 |
| HP            | 15                          | [79f04083ac](https://linux-hardware.org/?probe=79f04083ac) | Nov 16, 2024 |
| HP            | ProBook 650 G4              | [aa662f23e7](https://linux-hardware.org/?probe=aa662f23e7) | Nov 15, 2024 |
| Lenovo        | ThinkPad P1 20TJS2F42V      | [6d7dd4ff42](https://linux-hardware.org/?probe=6d7dd4ff42) | Nov 14, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [8ab1c5f89a](https://linux-hardware.org/?probe=8ab1c5f89a) | Nov 12, 2024 |
| HP            | ProBook 650 G4              | [5211ddeeac](https://linux-hardware.org/?probe=5211ddeeac) | Nov 12, 2024 |
| Dell          | Latitude 5540               | [6b66bd70e6](https://linux-hardware.org/?probe=6b66bd70e6) | Nov 12, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [e88d7b46ce](https://linux-hardware.org/?probe=e88d7b46ce) | Nov 12, 2024 |
| HP            | Laptop 14-dq4xxx            | [0b2580a6fd](https://linux-hardware.org/?probe=0b2580a6fd) | Nov 11, 2024 |
| Apple         | MacBookPro11,4              | [4cf83bb804](https://linux-hardware.org/?probe=4cf83bb804) | Nov 10, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [e16d78d766](https://linux-hardware.org/?probe=e16d78d766) | Nov 10, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [480d5f0266](https://linux-hardware.org/?probe=480d5f0266) | Nov 10, 2024 |
| Lenovo        | ThinkPad T480 20L5S05U00    | [cd6f4884f3](https://linux-hardware.org/?probe=cd6f4884f3) | Nov 09, 2024 |
| Juno Compu... | junotab3                    | [f6d2381f9f](https://linux-hardware.org/?probe=f6d2381f9f) | Nov 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f84abc56e9](https://linux-hardware.org/?probe=f84abc56e9) | Nov 08, 2024 |
| MSI           | Modern 14 B11MO             | [392e7d82ed](https://linux-hardware.org/?probe=392e7d82ed) | Nov 08, 2024 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [f711f4d637](https://linux-hardware.org/?probe=f711f4d637) | Nov 06, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [4a06e31cc5](https://linux-hardware.org/?probe=4a06e31cc5) | Nov 06, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [e218882150](https://linux-hardware.org/?probe=e218882150) | Nov 05, 2024 |
| Lenovo        | ThinkBook 14s G2 ITL 20V... | [239a991b05](https://linux-hardware.org/?probe=239a991b05) | Nov 04, 2024 |
| Apple         | MacBook8,1                  | [2b932f61ea](https://linux-hardware.org/?probe=2b932f61ea) | Nov 04, 2024 |
| Dell          | Latitude E5420              | [9e08b522db](https://linux-hardware.org/?probe=9e08b522db) | Nov 02, 2024 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [ced7393b11](https://linux-hardware.org/?probe=ced7393b11) | Nov 02, 2024 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | [e82e4d82e0](https://linux-hardware.org/?probe=e82e4d82e0) | Nov 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS3CV0V    | [9a1a8e0d40](https://linux-hardware.org/?probe=9a1a8e0d40) | Nov 01, 2024 |
| Intel         | Milstead Platform           | [fe0d78d041](https://linux-hardware.org/?probe=fe0d78d041) | Nov 01, 2024 |
| Intel         | Milstead Platform           | [94d678f3f5](https://linux-hardware.org/?probe=94d678f3f5) | Nov 01, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | [02bcf148cc](https://linux-hardware.org/?probe=02bcf148cc) | Oct 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [926da4587b](https://linux-hardware.org/?probe=926da4587b) | Oct 31, 2024 |
| HP            | Laptop 15s-eq2xxx           | [a06eab93a5](https://linux-hardware.org/?probe=a06eab93a5) | Oct 30, 2024 |
| Timi          | TM1707                      | [6f1f7e4e34](https://linux-hardware.org/?probe=6f1f7e4e34) | Oct 30, 2024 |
| Acer          | Aspire A515-45              | [14cc9b1bd2](https://linux-hardware.org/?probe=14cc9b1bd2) | Oct 30, 2024 |
| Dell          | XPS 15 9510                 | [30d0451aa4](https://linux-hardware.org/?probe=30d0451aa4) | Oct 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb3134b841](https://linux-hardware.org/?probe=eb3134b841) | Oct 30, 2024 |
| Acer          | Aspire A514-52K             | [102e60dfa8](https://linux-hardware.org/?probe=102e60dfa8) | Oct 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [e6e3c615dc](https://linux-hardware.org/?probe=e6e3c615dc) | Oct 29, 2024 |
| Apple         | MacBookPro13,1              | [a4cea0834a](https://linux-hardware.org/?probe=a4cea0834a) | Oct 29, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [c8b803b5be](https://linux-hardware.org/?probe=c8b803b5be) | Oct 29, 2024 |
| ASUSTek       | UX530UX                     | [b11e1b2e90](https://linux-hardware.org/?probe=b11e1b2e90) | Oct 29, 2024 |
| HUAWEI        | BDZ-WXX9                    | [a775cc4234](https://linux-hardware.org/?probe=a775cc4234) | Oct 29, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [e738c30646](https://linux-hardware.org/?probe=e738c30646) | Oct 29, 2024 |
| Lenovo        | ThinkPad T495 20NKS02N00    | [ab02b5d5f4](https://linux-hardware.org/?probe=ab02b5d5f4) | Oct 29, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [4408314643](https://linux-hardware.org/?probe=4408314643) | Oct 29, 2024 |
| Lenovo        | ThinkPad T480s 20L8S4AE0... | [059a8899aa](https://linux-hardware.org/?probe=059a8899aa) | Oct 29, 2024 |
| HP            | EliteBook Folio 9470m       | [75652d2b07](https://linux-hardware.org/?probe=75652d2b07) | Oct 29, 2024 |
| Dell          | Precision 7510              | [eaa22e1a44](https://linux-hardware.org/?probe=eaa22e1a44) | Oct 29, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [f5d019253b](https://linux-hardware.org/?probe=f5d019253b) | Oct 28, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [888b01a398](https://linux-hardware.org/?probe=888b01a398) | Oct 28, 2024 |
| Positivo      | N6440                       | [11f3656786](https://linux-hardware.org/?probe=11f3656786) | Oct 28, 2024 |
| GPD           | G1619-04                    | [8d4edea2b8](https://linux-hardware.org/?probe=8d4edea2b8) | Oct 28, 2024 |
| TUXEDO        | Sirius 16 Gen2              | [701fca6089](https://linux-hardware.org/?probe=701fca6089) | Oct 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [b48d086216](https://linux-hardware.org/?probe=b48d086216) | Oct 28, 2024 |
| HP            | ENVY Notebook               | [3570398b68](https://linux-hardware.org/?probe=3570398b68) | Oct 28, 2024 |
| Lenovo        | ThinkPad P1 20MES14G0M      | [518afdbf37](https://linux-hardware.org/?probe=518afdbf37) | Oct 28, 2024 |
| GPU Compan... | GWTC116-2                   | [3f3a6e5d57](https://linux-hardware.org/?probe=3f3a6e5d57) | Oct 28, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b36ba56662](https://linux-hardware.org/?probe=b36ba56662) | Oct 27, 2024 |
| Acer          | Aspire F5-573               | [127885eb15](https://linux-hardware.org/?probe=127885eb15) | Oct 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2468c65082](https://linux-hardware.org/?probe=2468c65082) | Oct 27, 2024 |
| Avell High... | Avell G1750 MUV / C65 MU... | [5efedd5ac9](https://linux-hardware.org/?probe=5efedd5ac9) | Oct 27, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [87db71f6fe](https://linux-hardware.org/?probe=87db71f6fe) | Oct 27, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [9521917abe](https://linux-hardware.org/?probe=9521917abe) | Oct 27, 2024 |
| Infinix       | ZERO BOOK 13                | [a2e892c47b](https://linux-hardware.org/?probe=a2e892c47b) | Oct 27, 2024 |
| HUAWEI        | KPL-W0X                     | [c157b5e147](https://linux-hardware.org/?probe=c157b5e147) | Oct 27, 2024 |
| THUNDEROBO... | 911AirD                     | [d14d084c2a](https://linux-hardware.org/?probe=d14d084c2a) | Oct 27, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [cb5e0b58a1](https://linux-hardware.org/?probe=cb5e0b58a1) | Oct 27, 2024 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [72a70468eb](https://linux-hardware.org/?probe=72a70468eb) | Oct 27, 2024 |
| Dell          | XPS 13 9360                 | [03830ecacb](https://linux-hardware.org/?probe=03830ecacb) | Oct 27, 2024 |
| HONOR         | FRI-FXX                     | [762796bb28](https://linux-hardware.org/?probe=762796bb28) | Oct 27, 2024 |
| Acer          | Aspire A315-59              | [4dd89f3bf0](https://linux-hardware.org/?probe=4dd89f3bf0) | Oct 26, 2024 |
| Apple         | MacBookPro11,1              | [95fc0bceda](https://linux-hardware.org/?probe=95fc0bceda) | Oct 26, 2024 |
| Apple         | MacBookPro11,1              | [dbd73dea03](https://linux-hardware.org/?probe=dbd73dea03) | Oct 26, 2024 |
| HP            | Laptop 14-ep0xxx            | [e0c4e36b31](https://linux-hardware.org/?probe=e0c4e36b31) | Oct 26, 2024 |
| Apple         | MacBookPro3,1               | [6dadd636e6](https://linux-hardware.org/?probe=6dadd636e6) | Oct 26, 2024 |
| Samsung       | 550P5C/550P7C               | [68724c7216](https://linux-hardware.org/?probe=68724c7216) | Oct 26, 2024 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [c10b72972e](https://linux-hardware.org/?probe=c10b72972e) | Oct 26, 2024 |
| HONOR         | FRI-HXX                     | [6aa30c6282](https://linux-hardware.org/?probe=6aa30c6282) | Oct 25, 2024 |
| Google        | Lillipup                    | [bde8c2e9fc](https://linux-hardware.org/?probe=bde8c2e9fc) | Oct 25, 2024 |
| TUXEDO        | Pulse 15 Gen2               | [c3eb35c1d9](https://linux-hardware.org/?probe=c3eb35c1d9) | Oct 25, 2024 |
| Dell          | Latitude E7440              | [59f882ef98](https://linux-hardware.org/?probe=59f882ef98) | Oct 25, 2024 |
| MSI           | GE70 2PE                    | [010126bf70](https://linux-hardware.org/?probe=010126bf70) | Oct 25, 2024 |
| Acer          | Aspire M5-581T              | [be8bfccf68](https://linux-hardware.org/?probe=be8bfccf68) | Oct 25, 2024 |
| Dell          | Latitude E7440              | [48182c2497](https://linux-hardware.org/?probe=48182c2497) | Oct 25, 2024 |
| Acer          | Aspire E5-771G              | [bc9ea310da](https://linux-hardware.org/?probe=bc9ea310da) | Oct 25, 2024 |
| Acer          | Aspire E5-771G              | [54b3dc0aff](https://linux-hardware.org/?probe=54b3dc0aff) | Oct 25, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [11d0ba0b30](https://linux-hardware.org/?probe=11d0ba0b30) | Oct 25, 2024 |
| MSI           | Alpha 15 A3DDK              | [43126100f1](https://linux-hardware.org/?probe=43126100f1) | Oct 25, 2024 |
| Dell          | XPS 15 9530                 | [22b47c8319](https://linux-hardware.org/?probe=22b47c8319) | Oct 25, 2024 |
| HP            | EliteBook 8570p             | [58feb4525c](https://linux-hardware.org/?probe=58feb4525c) | Oct 25, 2024 |
| ASUSTek       | N501VW                      | [9a9324955b](https://linux-hardware.org/?probe=9a9324955b) | Oct 25, 2024 |
| Dell          | XPS 15 9570                 | [19ab71d343](https://linux-hardware.org/?probe=19ab71d343) | Oct 25, 2024 |
| Dell          | Latitude 5320               | [7302e97437](https://linux-hardware.org/?probe=7302e97437) | Oct 25, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [3facf7a704](https://linux-hardware.org/?probe=3facf7a704) | Oct 25, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [e63c2ce069](https://linux-hardware.org/?probe=e63c2ce069) | Oct 24, 2024 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [57bc043676](https://linux-hardware.org/?probe=57bc043676) | Oct 24, 2024 |
| ASUSTek       | ROG Zephyrus G16 GA605WI... | [2bfca1dd72](https://linux-hardware.org/?probe=2bfca1dd72) | Oct 24, 2024 |
| HP            | Laptop 14-dq4xxx            | [65f9d4fa03](https://linux-hardware.org/?probe=65f9d4fa03) | Oct 24, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [0fc1305fc4](https://linux-hardware.org/?probe=0fc1305fc4) | Oct 24, 2024 |
| Apple         | MacBookPro3,1               | [3866b77fbe](https://linux-hardware.org/?probe=3866b77fbe) | Oct 24, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [82a1bda877](https://linux-hardware.org/?probe=82a1bda877) | Oct 24, 2024 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [eb57d61b77](https://linux-hardware.org/?probe=eb57d61b77) | Oct 24, 2024 |
| Dell          | Inspiron M5010              | [f8441a09c6](https://linux-hardware.org/?probe=f8441a09c6) | Oct 24, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f20e803485](https://linux-hardware.org/?probe=f20e803485) | Oct 24, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [6ca982f426](https://linux-hardware.org/?probe=6ca982f426) | Oct 24, 2024 |
| Dell          | Inspiron 15-3567            | [4379516edc](https://linux-hardware.org/?probe=4379516edc) | Oct 24, 2024 |
| HP            | Laptop 15-fd0xxx            | [2f43fcbe70](https://linux-hardware.org/?probe=2f43fcbe70) | Oct 24, 2024 |
| MSI           | GF63 Thin 10SC              | [264705b101](https://linux-hardware.org/?probe=264705b101) | Oct 24, 2024 |
| Dell          | Precision M4500             | [b3d982c517](https://linux-hardware.org/?probe=b3d982c517) | Oct 24, 2024 |
| Acer          | Aspire AL14-31P             | [5dc0afb6b3](https://linux-hardware.org/?probe=5dc0afb6b3) | Oct 24, 2024 |
| Apple         | MacBookPro12,1              | [0d3280fcc2](https://linux-hardware.org/?probe=0d3280fcc2) | Oct 24, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [f697805e66](https://linux-hardware.org/?probe=f697805e66) | Oct 24, 2024 |
| Acer          | Aspire A15-41M              | [b5a44016cd](https://linux-hardware.org/?probe=b5a44016cd) | Oct 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d52c99f09c](https://linux-hardware.org/?probe=d52c99f09c) | Oct 23, 2024 |
| Positivo B... | VJFE55F11X-B0211H           | [e018b67f9b](https://linux-hardware.org/?probe=e018b67f9b) | Oct 23, 2024 |
| Acer          | TravelMate 5744Z            | [ef9fc07cd1](https://linux-hardware.org/?probe=ef9fc07cd1) | Oct 23, 2024 |
| PC Special... | GM6PC0X                     | [1c0fa981a9](https://linux-hardware.org/?probe=1c0fa981a9) | Oct 23, 2024 |
| Lenovo        | ThinkPad X270 20HMS2C002    | [3bd05e0ee9](https://linux-hardware.org/?probe=3bd05e0ee9) | Oct 23, 2024 |
| Jumper        | EZbook                      | [5532770efb](https://linux-hardware.org/?probe=5532770efb) | Oct 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [071f9330d7](https://linux-hardware.org/?probe=071f9330d7) | Oct 23, 2024 |
| LG Electro... | 15ZD90S-GX56K               | [e9630cc537](https://linux-hardware.org/?probe=e9630cc537) | Oct 23, 2024 |
| HP            | Notebook                    | [c77d9407e6](https://linux-hardware.org/?probe=c77d9407e6) | Oct 23, 2024 |
| HP            | Laptop 15-db0xxx            | [d009d7f8d5](https://linux-hardware.org/?probe=d009d7f8d5) | Oct 23, 2024 |
| Dell          | Precision M4500             | [655b69cf4e](https://linux-hardware.org/?probe=655b69cf4e) | Oct 23, 2024 |
| Dell          | Inspiron 15 3535            | [54b7377997](https://linux-hardware.org/?probe=54b7377997) | Oct 23, 2024 |
| Dell          | Inspiron 15 3535            | [c38ffd4514](https://linux-hardware.org/?probe=c38ffd4514) | Oct 23, 2024 |
| HUAWEI        | KLVL-WXX9                   | [1aba2900e3](https://linux-hardware.org/?probe=1aba2900e3) | Oct 23, 2024 |
| Alienware     | m16 R1                      | [955ee0df4a](https://linux-hardware.org/?probe=955ee0df4a) | Oct 23, 2024 |
| Alienware     | m16 R1                      | [d871f524b4](https://linux-hardware.org/?probe=d871f524b4) | Oct 23, 2024 |
| Alienware     | m16 R1                      | [3a959e0d23](https://linux-hardware.org/?probe=3a959e0d23) | Oct 23, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [1b10590afd](https://linux-hardware.org/?probe=1b10590afd) | Oct 22, 2024 |
| Fujitsu       | LIFEBOOK E559               | [96ff5d9648](https://linux-hardware.org/?probe=96ff5d9648) | Oct 22, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [9d3eacadee](https://linux-hardware.org/?probe=9d3eacadee) | Oct 22, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [79407ce2bb](https://linux-hardware.org/?probe=79407ce2bb) | Oct 22, 2024 |
| Lenovo        | ThinkPad T580 20L9001YGE    | [9710a2a195](https://linux-hardware.org/?probe=9710a2a195) | Oct 22, 2024 |
| Insyde        | KX210                       | [12b2392210](https://linux-hardware.org/?probe=12b2392210) | Oct 22, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [27c3ff8bf4](https://linux-hardware.org/?probe=27c3ff8bf4) | Oct 22, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [a4417e3060](https://linux-hardware.org/?probe=a4417e3060) | Oct 22, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [2c7b38c7b2](https://linux-hardware.org/?probe=2c7b38c7b2) | Oct 22, 2024 |
| Dell          | Vostro 3550                 | [855f0534c1](https://linux-hardware.org/?probe=855f0534c1) | Oct 22, 2024 |
| GPU Compan... | GWTC116-2                   | [149b7cb745](https://linux-hardware.org/?probe=149b7cb745) | Oct 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f5b00c79d2](https://linux-hardware.org/?probe=f5b00c79d2) | Oct 22, 2024 |
| Acer          | Aspire A315-58              | [9dc1b13a4c](https://linux-hardware.org/?probe=9dc1b13a4c) | Oct 22, 2024 |
| Dell          | Precision M4600             | [93cbb268c2](https://linux-hardware.org/?probe=93cbb268c2) | Oct 22, 2024 |
| Alienware     | m18 R2                      | [e39538339d](https://linux-hardware.org/?probe=e39538339d) | Oct 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [5fde0c28f7](https://linux-hardware.org/?probe=5fde0c28f7) | Oct 22, 2024 |
| Lenovo        | ThinkPad T460 20FMS03600    | [b73c211fdf](https://linux-hardware.org/?probe=b73c211fdf) | Oct 21, 2024 |
| SLIMBOOK      | PROX-AMD5                   | [cfed3dc7f9](https://linux-hardware.org/?probe=cfed3dc7f9) | Oct 21, 2024 |
| Dell          | Inspiron 5579               | [abd9463583](https://linux-hardware.org/?probe=abd9463583) | Oct 21, 2024 |
| Dell          | Latitude 5430               | [3519e7a530](https://linux-hardware.org/?probe=3519e7a530) | Oct 21, 2024 |
| Lenovo        | B50-70 20384                | [09f5eef685](https://linux-hardware.org/?probe=09f5eef685) | Oct 21, 2024 |
| Dell          | Latitude 5510               | [98036add3f](https://linux-hardware.org/?probe=98036add3f) | Oct 21, 2024 |
| HP            | 250 15.6 inch G10 Notebo... | [9e94170315](https://linux-hardware.org/?probe=9e94170315) | Oct 21, 2024 |
| Dell          | XPS 15 9560                 | [9d3cba48c5](https://linux-hardware.org/?probe=9d3cba48c5) | Oct 21, 2024 |
| Apple         | MacBookAir5,2               | [7b9ad509e7](https://linux-hardware.org/?probe=7b9ad509e7) | Oct 21, 2024 |
| System76      | Pangolin                    | [dfaff4a65b](https://linux-hardware.org/?probe=dfaff4a65b) | Oct 21, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [1c61630c00](https://linux-hardware.org/?probe=1c61630c00) | Oct 20, 2024 |
| Acer          | Aspire A315-44P             | [757f809c22](https://linux-hardware.org/?probe=757f809c22) | Oct 20, 2024 |
| ASUSTek       | K73BY                       | [183ebc94a6](https://linux-hardware.org/?probe=183ebc94a6) | Oct 20, 2024 |
| Fujitsu       | LIFEBOOK E559               | [2ec391ffdc](https://linux-hardware.org/?probe=2ec391ffdc) | Oct 20, 2024 |
| MSI           | Alpha 17 C7VG               | [dbcee0fcec](https://linux-hardware.org/?probe=dbcee0fcec) | Oct 20, 2024 |
| Lenovo        | ThinkPad X270 20HN0016GE    | [6d342bda35](https://linux-hardware.org/?probe=6d342bda35) | Oct 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3795fe9a2b](https://linux-hardware.org/?probe=3795fe9a2b) | Oct 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [90de471428](https://linux-hardware.org/?probe=90de471428) | Oct 20, 2024 |
| Sony          | SVD11223CXB                 | [6b3e7fa3c6](https://linux-hardware.org/?probe=6b3e7fa3c6) | Oct 20, 2024 |
| Lenovo        | ThinkPad T480s 20L8S05A0... | [50c322a885](https://linux-hardware.org/?probe=50c322a885) | Oct 20, 2024 |
| MSI           | GT72S 6QE                   | [0cfe32ce18](https://linux-hardware.org/?probe=0cfe32ce18) | Oct 20, 2024 |
| Dell          | Precision 3570              | [1e848b6e97](https://linux-hardware.org/?probe=1e848b6e97) | Oct 20, 2024 |
| Dell          | Latitude E6400              | [45684f9885](https://linux-hardware.org/?probe=45684f9885) | Oct 20, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | [8b03dd3ef4](https://linux-hardware.org/?probe=8b03dd3ef4) | Oct 19, 2024 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [674a976e7b](https://linux-hardware.org/?probe=674a976e7b) | Oct 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [71f101364f](https://linux-hardware.org/?probe=71f101364f) | Oct 19, 2024 |
| TECNO         | WinPad 2                    | [1cb685a8f9](https://linux-hardware.org/?probe=1cb685a8f9) | Oct 19, 2024 |
| Gigabyte      | AORUS 16X ASG               | [2d585acb5b](https://linux-hardware.org/?probe=2d585acb5b) | Oct 19, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b25ed1f0fb](https://linux-hardware.org/?probe=b25ed1f0fb) | Oct 19, 2024 |
| HP            | ZBook 15 G5                 | [60584277b0](https://linux-hardware.org/?probe=60584277b0) | Oct 19, 2024 |
| GPU Compan... | GWTC51427                   | [9a2db06e84](https://linux-hardware.org/?probe=9a2db06e84) | Oct 19, 2024 |
| Dell          | Latitude 5540               | [ba75f2134f](https://linux-hardware.org/?probe=ba75f2134f) | Oct 19, 2024 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [ba795881fe](https://linux-hardware.org/?probe=ba795881fe) | Oct 19, 2024 |
| Timi          | Xiaomi Book Pro 14 2022     | [6e59218d2a](https://linux-hardware.org/?probe=6e59218d2a) | Oct 19, 2024 |
| Razer         | Blade Stealth               | [30a96f6443](https://linux-hardware.org/?probe=30a96f6443) | Oct 18, 2024 |
| HP            | Laptop 15s-eq2xxx           | [339f546673](https://linux-hardware.org/?probe=339f546673) | Oct 18, 2024 |
| HP            | Laptop 15t-dy200            | [a790abfc93](https://linux-hardware.org/?probe=a790abfc93) | Oct 18, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | [d137ac3a49](https://linux-hardware.org/?probe=d137ac3a49) | Oct 18, 2024 |
| ASUSTek       | GL503VS                     | [c2b42dfce0](https://linux-hardware.org/?probe=c2b42dfce0) | Oct 18, 2024 |
| ASUSTek       | K53SV                       | [4cc4056c72](https://linux-hardware.org/?probe=4cc4056c72) | Oct 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MDS... | [2d00c7ffe3](https://linux-hardware.org/?probe=2d00c7ffe3) | Oct 18, 2024 |
| HUAWEI        | BOD-WXX9                    | [c8ea9da7d2](https://linux-hardware.org/?probe=c8ea9da7d2) | Oct 18, 2024 |
| ASUSTek       | K53SV                       | [2b0f461f62](https://linux-hardware.org/?probe=2b0f461f62) | Oct 18, 2024 |
| Dell          | Latitude E6540              | [6211512b05](https://linux-hardware.org/?probe=6211512b05) | Oct 18, 2024 |
| Lenovo        | ThinkPad E14 20RA0016PB     | [99c42f786e](https://linux-hardware.org/?probe=99c42f786e) | Oct 18, 2024 |
| LG Electro... | S425-G.BE35P1               | [31259d6063](https://linux-hardware.org/?probe=31259d6063) | Oct 18, 2024 |
| Lenovo        | ThinkPad W540 20BHS09Y07    | [7d9781e63e](https://linux-hardware.org/?probe=7d9781e63e) | Oct 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [54f11d9d18](https://linux-hardware.org/?probe=54f11d9d18) | Oct 18, 2024 |
| Dell          | Inspiron N5010              | [7e1677822a](https://linux-hardware.org/?probe=7e1677822a) | Oct 18, 2024 |
| ASUSTek       | GL503VS                     | [59987a96a2](https://linux-hardware.org/?probe=59987a96a2) | Oct 17, 2024 |
| HP            | Stream Laptop 14-cb101np    | [e8bc94e534](https://linux-hardware.org/?probe=e8bc94e534) | Oct 17, 2024 |
| Lenovo        | ThinkPad X230 2324FU0       | [1560655db4](https://linux-hardware.org/?probe=1560655db4) | Oct 17, 2024 |
| Acer          | Predator PHN16-71           | [878ae06df8](https://linux-hardware.org/?probe=878ae06df8) | Oct 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [537a4d29f8](https://linux-hardware.org/?probe=537a4d29f8) | Oct 17, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [581e0cc59d](https://linux-hardware.org/?probe=581e0cc59d) | Oct 17, 2024 |
| Insyde        | BayTrail                    | [83fca1d770](https://linux-hardware.org/?probe=83fca1d770) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [fe6cbc762f](https://linux-hardware.org/?probe=fe6cbc762f) | Oct 17, 2024 |
| BAKED         | P65xRP                      | [9d26712e83](https://linux-hardware.org/?probe=9d26712e83) | Oct 17, 2024 |
| BAKED         | P65xRP                      | [b843af1c15](https://linux-hardware.org/?probe=b843af1c15) | Oct 17, 2024 |
| Apple         | MacBookPro10,1              | [df2b41f937](https://linux-hardware.org/?probe=df2b41f937) | Oct 17, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [815aad1371](https://linux-hardware.org/?probe=815aad1371) | Oct 17, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | [a15c3e921c](https://linux-hardware.org/?probe=a15c3e921c) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [63a9495ac8](https://linux-hardware.org/?probe=63a9495ac8) | Oct 17, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [b6c163527d](https://linux-hardware.org/?probe=b6c163527d) | Oct 17, 2024 |
| Alienware     | 17                          | [6923888471](https://linux-hardware.org/?probe=6923888471) | Oct 17, 2024 |
| Alienware     | 17                          | [9c5979e59a](https://linux-hardware.org/?probe=9c5979e59a) | Oct 17, 2024 |
| Samsung       | 940XGK                      | [e6b94cea06](https://linux-hardware.org/?probe=e6b94cea06) | Oct 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [117d3104ce](https://linux-hardware.org/?probe=117d3104ce) | Oct 17, 2024 |
| Lenovo        | ThinkPad P1 Gen 7 21KV00... | [3af3fb7243](https://linux-hardware.org/?probe=3af3fb7243) | Oct 16, 2024 |
| Lenovo        | IdeaPad Pro 5 16AHP9 83D... | [818bcae40b](https://linux-hardware.org/?probe=818bcae40b) | Oct 16, 2024 |
| Acer          | Aspire AL14-31P             | [6ae8586613](https://linux-hardware.org/?probe=6ae8586613) | Oct 16, 2024 |
| Apple         | MacBookPro14,1              | [13b45a29d3](https://linux-hardware.org/?probe=13b45a29d3) | Oct 16, 2024 |
| Dell          | Latitude 7390 2-in-1        | [ae0ebdeca8](https://linux-hardware.org/?probe=ae0ebdeca8) | Oct 16, 2024 |
| Acer          | Aspire E5-573G              | [47c8fdec6e](https://linux-hardware.org/?probe=47c8fdec6e) | Oct 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | [553cb8fd6e](https://linux-hardware.org/?probe=553cb8fd6e) | Oct 16, 2024 |
| Toshiba       | TECRA R950                  | [4c64d6dc1c](https://linux-hardware.org/?probe=4c64d6dc1c) | Oct 16, 2024 |
| Google        | Kano                        | [81f269cd85](https://linux-hardware.org/?probe=81f269cd85) | Oct 16, 2024 |
| Dell          | G16 7630                    | [e2f9e14b38](https://linux-hardware.org/?probe=e2f9e14b38) | Oct 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [91835aeee5](https://linux-hardware.org/?probe=91835aeee5) | Oct 16, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [721f67c310](https://linux-hardware.org/?probe=721f67c310) | Oct 15, 2024 |
| Dell          | Latitude 3400               | [52efd2e71e](https://linux-hardware.org/?probe=52efd2e71e) | Oct 15, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [d2c23ff5c0](https://linux-hardware.org/?probe=d2c23ff5c0) | Oct 15, 2024 |
| Dell          | XPS 15 9560                 | [cac6b26403](https://linux-hardware.org/?probe=cac6b26403) | Oct 15, 2024 |
| Dell          | Precision M6500             | [102728b70f](https://linux-hardware.org/?probe=102728b70f) | Oct 15, 2024 |
| HUAWEI        | KLVL-WXX9                   | [09034dd10d](https://linux-hardware.org/?probe=09034dd10d) | Oct 15, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a156cbf522](https://linux-hardware.org/?probe=a156cbf522) | Oct 15, 2024 |
| Lenovo        | ThinkBook 16 G6+ IMH 21L... | [209cffc8c6](https://linux-hardware.org/?probe=209cffc8c6) | Oct 15, 2024 |
| ASUSTek       | Strix 15 GL503GE            | [293f156926](https://linux-hardware.org/?probe=293f156926) | Oct 15, 2024 |
| ASUSTek       | ROG Zephyrus G16 GA605WI... | [8159b5a478](https://linux-hardware.org/?probe=8159b5a478) | Oct 15, 2024 |
| Dell          | Precision M6500             | [5f6091daf1](https://linux-hardware.org/?probe=5f6091daf1) | Oct 15, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9ae59f6ed9](https://linux-hardware.org/?probe=9ae59f6ed9) | Oct 14, 2024 |
| Dell          | Latitude E6410              | [d3476d39f8](https://linux-hardware.org/?probe=d3476d39f8) | Oct 14, 2024 |
| Acer          | Aspire V5-471               | [47d623d405](https://linux-hardware.org/?probe=47d623d405) | Oct 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7e6947f44f](https://linux-hardware.org/?probe=7e6947f44f) | Oct 14, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [544aea53d8](https://linux-hardware.org/?probe=544aea53d8) | Oct 14, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a9c9a656c3](https://linux-hardware.org/?probe=a9c9a656c3) | Oct 14, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [4379a607c2](https://linux-hardware.org/?probe=4379a607c2) | Oct 14, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [ea6a9feccf](https://linux-hardware.org/?probe=ea6a9feccf) | Oct 14, 2024 |
| Acer          | Aspire ES1-521              | [152353aceb](https://linux-hardware.org/?probe=152353aceb) | Oct 14, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [f43ac657a5](https://linux-hardware.org/?probe=f43ac657a5) | Oct 14, 2024 |
| Apple         | MacBookPro9,2               | [2408ee5d67](https://linux-hardware.org/?probe=2408ee5d67) | Oct 14, 2024 |
| Lenovo        | IdeaPadFlex 15 20309        | [64e5571acf](https://linux-hardware.org/?probe=64e5571acf) | Oct 13, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [2131d0a645](https://linux-hardware.org/?probe=2131d0a645) | Oct 13, 2024 |
| Acer          | Aspire E5-575G              | [12c27f8091](https://linux-hardware.org/?probe=12c27f8091) | Oct 13, 2024 |
| Lenovo        | ThinkPad T440p 20AWS1HM0... | [3018939080](https://linux-hardware.org/?probe=3018939080) | Oct 13, 2024 |
| Apple         | MacBookAir5,2               | [f20095e3af](https://linux-hardware.org/?probe=f20095e3af) | Oct 13, 2024 |
| MSI           | GT72S 6QE                   | [dd761bfc6f](https://linux-hardware.org/?probe=dd761bfc6f) | Oct 13, 2024 |
| HP            | EliteBook 830 G7 Noteboo... | [2f02059daf](https://linux-hardware.org/?probe=2f02059daf) | Oct 13, 2024 |
| Samsung       | 305V4A/305V5A               | [75ad76a7fb](https://linux-hardware.org/?probe=75ad76a7fb) | Oct 13, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [b4a4852367](https://linux-hardware.org/?probe=b4a4852367) | Oct 13, 2024 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [e87b219656](https://linux-hardware.org/?probe=e87b219656) | Oct 13, 2024 |
| MSI           | GF65 Thin 10UE              | [a6c169c33b](https://linux-hardware.org/?probe=a6c169c33b) | Oct 13, 2024 |
| HP            | ProBook 4540s               | [38d30c1f16](https://linux-hardware.org/?probe=38d30c1f16) | Oct 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [dddb1827ce](https://linux-hardware.org/?probe=dddb1827ce) | Oct 13, 2024 |
| ASUSTek       | TUF Gaming FX705GM_PX705... | [a66833f881](https://linux-hardware.org/?probe=a66833f881) | Oct 12, 2024 |
| HP            | mt41                        | [56a4716804](https://linux-hardware.org/?probe=56a4716804) | Oct 12, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [c331d0b34d](https://linux-hardware.org/?probe=c331d0b34d) | Oct 12, 2024 |
| HP            | 250 G7 Notebook PC          | [e1c4a5a26f](https://linux-hardware.org/?probe=e1c4a5a26f) | Oct 12, 2024 |
| Samsung       | 270E5G/270E5U               | [5c391c318b](https://linux-hardware.org/?probe=5c391c318b) | Oct 12, 2024 |
| Google        | Lindar                      | [248279b8b2](https://linux-hardware.org/?probe=248279b8b2) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 20HMS2C002    | [1718617fcc](https://linux-hardware.org/?probe=1718617fcc) | Oct 12, 2024 |
| Acer          | Nitro AN515-52              | [7700aaaef5](https://linux-hardware.org/?probe=7700aaaef5) | Oct 12, 2024 |
| ASUSTek       | K93SV                       | [4b16fe7309](https://linux-hardware.org/?probe=4b16fe7309) | Oct 12, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [73af5119fe](https://linux-hardware.org/?probe=73af5119fe) | Oct 12, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [0df50eaff2](https://linux-hardware.org/?probe=0df50eaff2) | Oct 12, 2024 |
| Positivo      | N3240                       | [9c315c6ddb](https://linux-hardware.org/?probe=9c315c6ddb) | Oct 12, 2024 |
| Apple         | MacBookAir7,2               | [25f5532900](https://linux-hardware.org/?probe=25f5532900) | Oct 11, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5ff6f3f1a8](https://linux-hardware.org/?probe=5ff6f3f1a8) | Oct 11, 2024 |
| Dell          | Precision 7530              | [ca12dbc1be](https://linux-hardware.org/?probe=ca12dbc1be) | Oct 11, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [cef125c743](https://linux-hardware.org/?probe=cef125c743) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c9a54bde4c](https://linux-hardware.org/?probe=c9a54bde4c) | Oct 11, 2024 |
| Lenovo        | ThinkBook 15p G2 ITH 21B... | [0da47f72b3](https://linux-hardware.org/?probe=0da47f72b3) | Oct 11, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [f6d8e2dbf5](https://linux-hardware.org/?probe=f6d8e2dbf5) | Oct 11, 2024 |
| Dell          | XPS 15 9530                 | [61b9e50d90](https://linux-hardware.org/?probe=61b9e50d90) | Oct 11, 2024 |
| Lenovo        | ThinkPad T560 20FJS3HL00    | [3c122324a9](https://linux-hardware.org/?probe=3c122324a9) | Oct 11, 2024 |
| HP            | Pavilion Laptop 14-dv2xx... | [2a034b4114](https://linux-hardware.org/?probe=2a034b4114) | Oct 11, 2024 |
| HP            | Pavilion Laptop 14-dv2xx... | [b7355dce23](https://linux-hardware.org/?probe=b7355dce23) | Oct 11, 2024 |
| ASUSTek       | ROG Strix G16 G614JVR_G6... | [78f651233a](https://linux-hardware.org/?probe=78f651233a) | Oct 11, 2024 |
| Acer          | Aspire E5-771G              | [808d8ffd44](https://linux-hardware.org/?probe=808d8ffd44) | Oct 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | [fe4bfb3208](https://linux-hardware.org/?probe=fe4bfb3208) | Oct 10, 2024 |
| Dell          | Inspiron 3583               | [f2fd99c3f0](https://linux-hardware.org/?probe=f2fd99c3f0) | Oct 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [59c4c502f1](https://linux-hardware.org/?probe=59c4c502f1) | Oct 10, 2024 |
| Acer          | Predator PHN16-71           | [36e4ba09ca](https://linux-hardware.org/?probe=36e4ba09ca) | Oct 10, 2024 |
| Irbis         | NB656                       | [2bdb435376](https://linux-hardware.org/?probe=2bdb435376) | Oct 10, 2024 |
| Acer          | Nitro ANV15-51              | [7a65e38a37](https://linux-hardware.org/?probe=7a65e38a37) | Oct 10, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [b94d479256](https://linux-hardware.org/?probe=b94d479256) | Oct 10, 2024 |
| Positivo      | N3240                       | [ce2105487f](https://linux-hardware.org/?probe=ce2105487f) | Oct 10, 2024 |
| Apple         | MacBookPro11,3              | [46acb8c4d7](https://linux-hardware.org/?probe=46acb8c4d7) | Oct 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [95d12e5cce](https://linux-hardware.org/?probe=95d12e5cce) | Oct 10, 2024 |
| MSI           | GF63 Thin 10SC              | [8880f8b55c](https://linux-hardware.org/?probe=8880f8b55c) | Oct 10, 2024 |
| Dell          | Precision 7530              | [c386366ce5](https://linux-hardware.org/?probe=c386366ce5) | Oct 10, 2024 |
| Acer          | Aspire A515-57              | [1e73b44291](https://linux-hardware.org/?probe=1e73b44291) | Oct 10, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3A01... | [f69f8fa533](https://linux-hardware.org/?probe=f69f8fa533) | Oct 09, 2024 |
| HP            | EliteBook 840 G6            | [90925b97bb](https://linux-hardware.org/?probe=90925b97bb) | Oct 09, 2024 |
| Samsung       | 305V4A/305V5A               | [2b41086555](https://linux-hardware.org/?probe=2b41086555) | Oct 09, 2024 |
| HP            | Laptop 15-dw3xxx            | [5188f7bee3](https://linux-hardware.org/?probe=5188f7bee3) | Oct 09, 2024 |
| Avell High... | B.ON                        | [6695fdbdac](https://linux-hardware.org/?probe=6695fdbdac) | Oct 09, 2024 |
| Acer          | Nitro AN515-56              | [7d9e391f34](https://linux-hardware.org/?probe=7d9e391f34) | Oct 09, 2024 |
| Lenovo        | ThinkPad T450s 20BWS12V0... | [62e5d7e94f](https://linux-hardware.org/?probe=62e5d7e94f) | Oct 09, 2024 |
| MSI           | Modern 14 A10M              | [e17fa96504](https://linux-hardware.org/?probe=e17fa96504) | Oct 08, 2024 |
| Dell          | Latitude E6410              | [67c1dd89e4](https://linux-hardware.org/?probe=67c1dd89e4) | Oct 08, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [7df1e66c9c](https://linux-hardware.org/?probe=7df1e66c9c) | Oct 08, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [8adc49985c](https://linux-hardware.org/?probe=8adc49985c) | Oct 08, 2024 |
| HP            | Unknown                     | [3f098896a0](https://linux-hardware.org/?probe=3f098896a0) | Oct 08, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [6e0d9c2a31](https://linux-hardware.org/?probe=6e0d9c2a31) | Oct 08, 2024 |
| HP            | Unknown                     | [8d8a005650](https://linux-hardware.org/?probe=8d8a005650) | Oct 08, 2024 |
| Samsung       | 940XFG                      | [a30f0716a0](https://linux-hardware.org/?probe=a30f0716a0) | Oct 08, 2024 |
| HP            | Victus by Gaming Laptop ... | [4618b6e25f](https://linux-hardware.org/?probe=4618b6e25f) | Oct 08, 2024 |
| Dell          | XPS 15 9500                 | [855ca0cb21](https://linux-hardware.org/?probe=855ca0cb21) | Oct 08, 2024 |
| Apple         | MacBookPro9,2               | [5ffe9c3801](https://linux-hardware.org/?probe=5ffe9c3801) | Oct 08, 2024 |
| Apple         | MacBookPro9,2               | [5124f0d14b](https://linux-hardware.org/?probe=5124f0d14b) | Oct 08, 2024 |
| HP            | Laptop 15t-dy200            | [5629b2f0c2](https://linux-hardware.org/?probe=5629b2f0c2) | Oct 08, 2024 |
| Apple         | MacBookPro14,2              | [eb3a502532](https://linux-hardware.org/?probe=eb3a502532) | Oct 07, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [94477eb0ba](https://linux-hardware.org/?probe=94477eb0ba) | Oct 07, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [a810910a2d](https://linux-hardware.org/?probe=a810910a2d) | Oct 07, 2024 |
| Jumper        | EZbook                      | [7b2e82cd1f](https://linux-hardware.org/?probe=7b2e82cd1f) | Oct 07, 2024 |
| HP            | Pavilion 15                 | [6f84e0d056](https://linux-hardware.org/?probe=6f84e0d056) | Oct 07, 2024 |
| Acer          | Aspire F5-573               | [dde8514a09](https://linux-hardware.org/?probe=dde8514a09) | Oct 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [83788f745f](https://linux-hardware.org/?probe=83788f745f) | Oct 07, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [267a889e66](https://linux-hardware.org/?probe=267a889e66) | Oct 07, 2024 |
| Jumper        | EZbook                      | [58f1d46c13](https://linux-hardware.org/?probe=58f1d46c13) | Oct 07, 2024 |
| Notebook      | NL5xNU                      | [e7e86c089c](https://linux-hardware.org/?probe=e7e86c089c) | Oct 07, 2024 |
| Infinix       | INBOOK X3 Plus              | [2ea5f65277](https://linux-hardware.org/?probe=2ea5f65277) | Oct 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IRH8 83... | [94d2e36c7b](https://linux-hardware.org/?probe=94d2e36c7b) | Oct 06, 2024 |
| Dell          | Precision M4400             | [0d412792d5](https://linux-hardware.org/?probe=0d412792d5) | Oct 06, 2024 |
| Apple         | MacBookPro8,3               | [6d79b159b0](https://linux-hardware.org/?probe=6d79b159b0) | Oct 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [71902dd97c](https://linux-hardware.org/?probe=71902dd97c) | Oct 06, 2024 |
| PC Special... | N750HU                      | [e0aecc58af](https://linux-hardware.org/?probe=e0aecc58af) | Oct 06, 2024 |
| Lenovo        | LOQ 15IRH8 83EU             | [a7b0ff3425](https://linux-hardware.org/?probe=a7b0ff3425) | Oct 05, 2024 |
| Lenovo        | LOQ 15IRH8 83EU             | [f16315d3be](https://linux-hardware.org/?probe=f16315d3be) | Oct 05, 2024 |
| HP            | EliteBook Folio 9480m       | [ef64b85ad4](https://linux-hardware.org/?probe=ef64b85ad4) | Oct 05, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [1d982586c7](https://linux-hardware.org/?probe=1d982586c7) | Oct 05, 2024 |
| Dell          | Inspiron 3537               | [9a5d9a5065](https://linux-hardware.org/?probe=9a5d9a5065) | Oct 05, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U60... | [1734e91761](https://linux-hardware.org/?probe=1734e91761) | Oct 05, 2024 |
| ASUSTek       | X550CL                      | [c561d0fe5b](https://linux-hardware.org/?probe=c561d0fe5b) | Oct 05, 2024 |
| Dell          | Precision 7540              | [b7190e112c](https://linux-hardware.org/?probe=b7190e112c) | Oct 05, 2024 |
| Acer          | Aspire AL14-31P             | [b1fff870c3](https://linux-hardware.org/?probe=b1fff870c3) | Oct 05, 2024 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | [33416938d4](https://linux-hardware.org/?probe=33416938d4) | Oct 05, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [54c023b2f6](https://linux-hardware.org/?probe=54c023b2f6) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | [ba0935bde6](https://linux-hardware.org/?probe=ba0935bde6) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | [f3c50b490a](https://linux-hardware.org/?probe=f3c50b490a) | Oct 05, 2024 |
| Sony          | VGNFW490Y                   | [7341b2c2c6](https://linux-hardware.org/?probe=7341b2c2c6) | Oct 05, 2024 |
| Dell          | Latitude 5430               | [41fd38816a](https://linux-hardware.org/?probe=41fd38816a) | Oct 05, 2024 |
| MSI           | GF65 Thin 10UE              | [220a1355fa](https://linux-hardware.org/?probe=220a1355fa) | Oct 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [f314e87727](https://linux-hardware.org/?probe=f314e87727) | Oct 04, 2024 |
| Samsung       | 550XED                      | [da76a0e07b](https://linux-hardware.org/?probe=da76a0e07b) | Oct 04, 2024 |
| Apple         | MacBookPro14,1              | [3a685cfdfd](https://linux-hardware.org/?probe=3a685cfdfd) | Oct 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [884d99dd9f](https://linux-hardware.org/?probe=884d99dd9f) | Oct 04, 2024 |
| Samsung       | 550XED                      | [d8bebe5591](https://linux-hardware.org/?probe=d8bebe5591) | Oct 04, 2024 |
| HP            | Pavilion 15                 | [fdfb5cf338](https://linux-hardware.org/?probe=fdfb5cf338) | Oct 04, 2024 |
| HP            | Dev One Notebook PC         | [b43c3029a6](https://linux-hardware.org/?probe=b43c3029a6) | Oct 04, 2024 |
| HP            | EliteBook Folio 9470m       | [34092d7b69](https://linux-hardware.org/?probe=34092d7b69) | Oct 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [23f6034531](https://linux-hardware.org/?probe=23f6034531) | Oct 04, 2024 |
| HP            | EliteBook Folio 9470m       | [ce05e67256](https://linux-hardware.org/?probe=ce05e67256) | Oct 04, 2024 |
| HP            | Victus by Gaming Laptop ... | [f2b5bbd4de](https://linux-hardware.org/?probe=f2b5bbd4de) | Oct 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [95c32b4c50](https://linux-hardware.org/?probe=95c32b4c50) | Oct 04, 2024 |
| eMachines     | E725 V1.03                  | [4a9590683e](https://linux-hardware.org/?probe=4a9590683e) | Oct 03, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [045cd6bfce](https://linux-hardware.org/?probe=045cd6bfce) | Oct 03, 2024 |
| Dell          | G15 5511                    | [fdfcb44572](https://linux-hardware.org/?probe=fdfcb44572) | Oct 03, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [dd84c0fff7](https://linux-hardware.org/?probe=dd84c0fff7) | Oct 03, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [05f7a6ed10](https://linux-hardware.org/?probe=05f7a6ed10) | Oct 03, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [0f527314f8](https://linux-hardware.org/?probe=0f527314f8) | Oct 03, 2024 |
| Acer          | Nitro AN515-55              | [ec74664078](https://linux-hardware.org/?probe=ec74664078) | Oct 03, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | [306ac3f0e3](https://linux-hardware.org/?probe=306ac3f0e3) | Oct 03, 2024 |
| HP            | Laptop 15-db0xxx            | [66c92534ee](https://linux-hardware.org/?probe=66c92534ee) | Oct 03, 2024 |
| HP            | EliteBook 840 G6            | [384750eca9](https://linux-hardware.org/?probe=384750eca9) | Oct 03, 2024 |
| HP            | EliteBook Folio 9480m       | [074be404b5](https://linux-hardware.org/?probe=074be404b5) | Oct 03, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [395b3fa9c6](https://linux-hardware.org/?probe=395b3fa9c6) | Oct 03, 2024 |
| ASUSTek       | N552VX                      | [2ef6bdc43a](https://linux-hardware.org/?probe=2ef6bdc43a) | Oct 03, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [5baaadc069](https://linux-hardware.org/?probe=5baaadc069) | Oct 02, 2024 |
| Dell          | G15 5511                    | [c3f5ed0a06](https://linux-hardware.org/?probe=c3f5ed0a06) | Oct 02, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [a1110f667e](https://linux-hardware.org/?probe=a1110f667e) | Oct 02, 2024 |
| ASUSTek       | X550CC                      | [8aa7d83ae5](https://linux-hardware.org/?probe=8aa7d83ae5) | Oct 02, 2024 |
| ASUSTek       | X550CC                      | [5e4a8d8e8b](https://linux-hardware.org/?probe=5e4a8d8e8b) | Oct 02, 2024 |
| Fujitsu       | FMVA12001                   | [fda024f87c](https://linux-hardware.org/?probe=fda024f87c) | Oct 02, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | [5fca760834](https://linux-hardware.org/?probe=5fca760834) | Oct 02, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | [c263b0d128](https://linux-hardware.org/?probe=c263b0d128) | Oct 02, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | [6e28788eb8](https://linux-hardware.org/?probe=6e28788eb8) | Oct 02, 2024 |
| Lenovo        | Slim 7 14IMH9 83D8          | [3f13c711a8](https://linux-hardware.org/?probe=3f13c711a8) | Oct 02, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [9a4f4dafdd](https://linux-hardware.org/?probe=9a4f4dafdd) | Oct 02, 2024 |
| Lenovo        | V130-15IKB 81HN             | [ada6d21b48](https://linux-hardware.org/?probe=ada6d21b48) | Oct 02, 2024 |
| Acer          | Nitro AN515-58              | [a4ffdce5bf](https://linux-hardware.org/?probe=a4ffdce5bf) | Oct 01, 2024 |
| Dell          | Latitude E6320              | [14bcade039](https://linux-hardware.org/?probe=14bcade039) | Oct 01, 2024 |
| Lenovo        | V130-15IKB 81HN             | [bfae8f46d4](https://linux-hardware.org/?probe=bfae8f46d4) | Oct 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [066c22c11b](https://linux-hardware.org/?probe=066c22c11b) | Oct 01, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [48137752ca](https://linux-hardware.org/?probe=48137752ca) | Oct 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [f3c9aa0b81](https://linux-hardware.org/?probe=f3c9aa0b81) | Oct 01, 2024 |
| Apple         | MacBookPro4,1               | [e4dea90fb8](https://linux-hardware.org/?probe=e4dea90fb8) | Oct 01, 2024 |
| Samsung       | 550XCJ/550XCR               | [c68df5226e](https://linux-hardware.org/?probe=c68df5226e) | Oct 01, 2024 |
| AVITA         | NS14A6                      | [360beece3d](https://linux-hardware.org/?probe=360beece3d) | Oct 01, 2024 |
| Lenovo        | Legion Y545 81Q6            | [451563b4fb](https://linux-hardware.org/?probe=451563b4fb) | Oct 01, 2024 |
| Dell          | Latitude E5470              | [649f2683b3](https://linux-hardware.org/?probe=649f2683b3) | Oct 01, 2024 |
| HP            | Victus by Gaming Laptop ... | [605995ef0d](https://linux-hardware.org/?probe=605995ef0d) | Oct 01, 2024 |
| Dell          | Inspiron 16 5635            | [fa35ff049c](https://linux-hardware.org/?probe=fa35ff049c) | Oct 01, 2024 |
| Dell          | Inspiron 3521               | [32cd855c59](https://linux-hardware.org/?probe=32cd855c59) | Oct 01, 2024 |
| Dell          | Inspiron 3521               | [0e57e17e13](https://linux-hardware.org/?probe=0e57e17e13) | Oct 01, 2024 |
| Dell          | Latitude 5420               | [1c0a43d055](https://linux-hardware.org/?probe=1c0a43d055) | Sep 30, 2024 |
| HP            | Victus by Gaming Laptop ... | [ee4039dadc](https://linux-hardware.org/?probe=ee4039dadc) | Sep 30, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [fb89302a2c](https://linux-hardware.org/?probe=fb89302a2c) | Sep 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [bd54b4b008](https://linux-hardware.org/?probe=bd54b4b008) | Sep 30, 2024 |
| Dell          | Precision 7780              | [27449211bc](https://linux-hardware.org/?probe=27449211bc) | Sep 30, 2024 |
| Dell          | Precision 7780              | [406157083d](https://linux-hardware.org/?probe=406157083d) | Sep 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [b78b3c6ea8](https://linux-hardware.org/?probe=b78b3c6ea8) | Sep 30, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [b0712ef444](https://linux-hardware.org/?probe=b0712ef444) | Sep 30, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [f01b96e5ac](https://linux-hardware.org/?probe=f01b96e5ac) | Sep 30, 2024 |
| MSI           | Summit E13FlipEvo A13MT     | [105c69a831](https://linux-hardware.org/?probe=105c69a831) | Sep 30, 2024 |
| HP            | Laptop 15-dy2xxx            | [c940397cc8](https://linux-hardware.org/?probe=c940397cc8) | Sep 30, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5cdf246355](https://linux-hardware.org/?probe=5cdf246355) | Sep 30, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [2c916dede8](https://linux-hardware.org/?probe=2c916dede8) | Sep 30, 2024 |
| Schenker      | XMG NEO (TGL/M21)           | [1237ae4821](https://linux-hardware.org/?probe=1237ae4821) | Sep 30, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [4f4ec89b3a](https://linux-hardware.org/?probe=4f4ec89b3a) | Sep 29, 2024 |
| ASUSTek       | G750JHA                     | [c78859f5ae](https://linux-hardware.org/?probe=c78859f5ae) | Sep 29, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [ba8072bee4](https://linux-hardware.org/?probe=ba8072bee4) | Sep 29, 2024 |
| HP            | EliteBook 840 G3            | [4d52b9b4ac](https://linux-hardware.org/?probe=4d52b9b4ac) | Sep 29, 2024 |
| Lenovo        | G510 20238                  | [df4e3d53be](https://linux-hardware.org/?probe=df4e3d53be) | Sep 29, 2024 |
| Toshiba       | Satellite C870-1GD          | [515b2dadd3](https://linux-hardware.org/?probe=515b2dadd3) | Sep 29, 2024 |
| HP            | Laptop 15-dw2xxx            | [43f4d4163d](https://linux-hardware.org/?probe=43f4d4163d) | Sep 29, 2024 |
| Toshiba       | QOSMIO X775                 | [d082c62bb9](https://linux-hardware.org/?probe=d082c62bb9) | Sep 29, 2024 |
| Fujitsu       | LIFEBOOK E548               | [6e0f5e1ba9](https://linux-hardware.org/?probe=6e0f5e1ba9) | Sep 29, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [d1718d14ab](https://linux-hardware.org/?probe=d1718d14ab) | Sep 29, 2024 |
| Lenovo        | ThinkPad W520 42844DG       | [34267b7e13](https://linux-hardware.org/?probe=34267b7e13) | Sep 29, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [b2b12658a9](https://linux-hardware.org/?probe=b2b12658a9) | Sep 29, 2024 |
| Timi          | TM1701                      | [cfe083e967](https://linux-hardware.org/?probe=cfe083e967) | Sep 29, 2024 |
| Unknown       | Unknown                     | [cdc226d94d](https://linux-hardware.org/?probe=cdc226d94d) | Sep 29, 2024 |
| Unknown       | Unknown                     | [8a4172464a](https://linux-hardware.org/?probe=8a4172464a) | Sep 29, 2024 |
| MSI           | GS76 Stealth 11UG           | [dd4516ba37](https://linux-hardware.org/?probe=dd4516ba37) | Sep 29, 2024 |
| Dell          | XPS 15 9500                 | [6e01b29e3b](https://linux-hardware.org/?probe=6e01b29e3b) | Sep 29, 2024 |
| Dell          | XPS 15 9500                 | [ee50af1163](https://linux-hardware.org/?probe=ee50af1163) | Sep 29, 2024 |
| HP            | Grunt                       | [2264efe866](https://linux-hardware.org/?probe=2264efe866) | Sep 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [767a70e7fe](https://linux-hardware.org/?probe=767a70e7fe) | Sep 29, 2024 |
| Apple         | MacBookPro11,5              | [4e7e3890bb](https://linux-hardware.org/?probe=4e7e3890bb) | Sep 29, 2024 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f4697c886f](https://linux-hardware.org/?probe=f4697c886f) | Sep 28, 2024 |
| Samsung       | 305V4A/305V5A               | [1da0c18a13](https://linux-hardware.org/?probe=1da0c18a13) | Sep 28, 2024 |
| HP            | Victus by Gaming Laptop ... | [b27c7324e8](https://linux-hardware.org/?probe=b27c7324e8) | Sep 28, 2024 |
| Schenker      | VISION 14                   | [2d8dc470e9](https://linux-hardware.org/?probe=2d8dc470e9) | Sep 28, 2024 |
| Acer          | Okinawa                     | [dd1134eda8](https://linux-hardware.org/?probe=dd1134eda8) | Sep 28, 2024 |
| HP            | EliteBook Folio 9480m       | [55eb1cb193](https://linux-hardware.org/?probe=55eb1cb193) | Sep 28, 2024 |
| Dell          | Latitude 7480               | [36028e7ce7](https://linux-hardware.org/?probe=36028e7ce7) | Sep 28, 2024 |
| HP            | Pavilion dv6700             | [707360a70f](https://linux-hardware.org/?probe=707360a70f) | Sep 28, 2024 |
| Dell          | Latitude 7490               | [bb2ef7aeaa](https://linux-hardware.org/?probe=bb2ef7aeaa) | Sep 28, 2024 |
| Lenovo        | Z50-70 20354                | [f17e1584e0](https://linux-hardware.org/?probe=f17e1584e0) | Sep 27, 2024 |
| HP            | Laptop 15-fc0xxx            | [b06ebcfa91](https://linux-hardware.org/?probe=b06ebcfa91) | Sep 27, 2024 |
| HP            | Pavilion Laptop 14-ec1xx... | [0a0cbfcc0c](https://linux-hardware.org/?probe=0a0cbfcc0c) | Sep 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3bd8900d6d](https://linux-hardware.org/?probe=3bd8900d6d) | Sep 27, 2024 |
| Lenovo        | G580 20150                  | [a5db1c0652](https://linux-hardware.org/?probe=a5db1c0652) | Sep 27, 2024 |
| Lenovo        | G580 20150                  | [9f8c1e9038](https://linux-hardware.org/?probe=9f8c1e9038) | Sep 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [2d0c60bf4e](https://linux-hardware.org/?probe=2d0c60bf4e) | Sep 27, 2024 |
| HP            | EliteBook Folio 9480m       | [915bab9e91](https://linux-hardware.org/?probe=915bab9e91) | Sep 27, 2024 |
| HP            | Notebook                    | [cfe81118c3](https://linux-hardware.org/?probe=cfe81118c3) | Sep 27, 2024 |
| Dell          | Vostro 5391                 | [bf2cd1b3a1](https://linux-hardware.org/?probe=bf2cd1b3a1) | Sep 27, 2024 |
| HP            | Notebook                    | [0695d61a4c](https://linux-hardware.org/?probe=0695d61a4c) | Sep 27, 2024 |
| HP            | ENVY 15                     | [cec3ec4958](https://linux-hardware.org/?probe=cec3ec4958) | Sep 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [617d6c24ec](https://linux-hardware.org/?probe=617d6c24ec) | Sep 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [914d0011a1](https://linux-hardware.org/?probe=914d0011a1) | Sep 26, 2024 |
| Xiaomi        | Pad 5                       | [10df1d4339](https://linux-hardware.org/?probe=10df1d4339) | Sep 26, 2024 |
| Dell          | G7 7790                     | [b118f9066c](https://linux-hardware.org/?probe=b118f9066c) | Sep 26, 2024 |
| Dell          | G7 7790                     | [b9b8f409cf](https://linux-hardware.org/?probe=b9b8f409cf) | Sep 26, 2024 |
| Dell          | Latitude 7400               | [a8fc62b85e](https://linux-hardware.org/?probe=a8fc62b85e) | Sep 26, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [d328b51ed5](https://linux-hardware.org/?probe=d328b51ed5) | Sep 26, 2024 |
| ASUSTek       | ASUS ExpertBook P2451FA     | [76efe6a713](https://linux-hardware.org/?probe=76efe6a713) | Sep 26, 2024 |
| HP            | Laptop 15-bs0xx             | [739b6f2f9e](https://linux-hardware.org/?probe=739b6f2f9e) | Sep 26, 2024 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [fd7f6af786](https://linux-hardware.org/?probe=fd7f6af786) | Sep 26, 2024 |
| Packard Be... | EasyNote TJ65               | [a49aa6c0b8](https://linux-hardware.org/?probe=a49aa6c0b8) | Sep 25, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7f07e86f5c](https://linux-hardware.org/?probe=7f07e86f5c) | Sep 25, 2024 |
| MSI           | Bravo 17 A4DDR              | [994fcd21ee](https://linux-hardware.org/?probe=994fcd21ee) | Sep 25, 2024 |
| Apple         | MacBookAir6,2               | [4a145a2850](https://linux-hardware.org/?probe=4a145a2850) | Sep 25, 2024 |
| Acer          | Nitro AN515-57              | [4cd5e49a76](https://linux-hardware.org/?probe=4cd5e49a76) | Sep 25, 2024 |
| MSI           | GF63 Thin 9SC               | [1803b90b56](https://linux-hardware.org/?probe=1803b90b56) | Sep 25, 2024 |
| Toshiba       | PORTEGE Z30t-C              | [06807aa903](https://linux-hardware.org/?probe=06807aa903) | Sep 25, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [413217c3d1](https://linux-hardware.org/?probe=413217c3d1) | Sep 25, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [86c41c5c5b](https://linux-hardware.org/?probe=86c41c5c5b) | Sep 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [13e5463ee0](https://linux-hardware.org/?probe=13e5463ee0) | Sep 25, 2024 |
| Alienware     | 15 R3                       | [6c47406fd9](https://linux-hardware.org/?probe=6c47406fd9) | Sep 25, 2024 |
| Dell          | Inspiron 5565               | [665b2cc68c](https://linux-hardware.org/?probe=665b2cc68c) | Sep 25, 2024 |
| Dell          | Inspiron 5565               | [3763aeacb5](https://linux-hardware.org/?probe=3763aeacb5) | Sep 25, 2024 |
| Lenovo        | Yoga S730-13IML 81U4        | [b411da6d9e](https://linux-hardware.org/?probe=b411da6d9e) | Sep 25, 2024 |
| HP            | Victus by Gaming Laptop ... | [adf809b073](https://linux-hardware.org/?probe=adf809b073) | Sep 25, 2024 |
| Apple         | MacBookPro9,2               | [e41bee6ced](https://linux-hardware.org/?probe=e41bee6ced) | Sep 25, 2024 |
| Dell          | Inspiron 5770               | [9ea257bf1a](https://linux-hardware.org/?probe=9ea257bf1a) | Sep 24, 2024 |
| Dell          | Latitude E5470              | [b33fe80d61](https://linux-hardware.org/?probe=b33fe80d61) | Sep 24, 2024 |
| HONOR         | FRI-FXX                     | [1ed83fb238](https://linux-hardware.org/?probe=1ed83fb238) | Sep 24, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [845ef2198e](https://linux-hardware.org/?probe=845ef2198e) | Sep 24, 2024 |
| Acer          | Aspire A315-55G             | [3f77776e4c](https://linux-hardware.org/?probe=3f77776e4c) | Sep 24, 2024 |
| Lenovo        | ThinkPad E550 20DF002MAU    | [311e26a0a8](https://linux-hardware.org/?probe=311e26a0a8) | Sep 24, 2024 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [6eb428f2a4](https://linux-hardware.org/?probe=6eb428f2a4) | Sep 24, 2024 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [43ca7f9dab](https://linux-hardware.org/?probe=43ca7f9dab) | Sep 24, 2024 |
| Dell          | Inspiron M5010              | [f3866be309](https://linux-hardware.org/?probe=f3866be309) | Sep 24, 2024 |
| Lenovo        | ThinkPad L440 20AT002KUS    | [a25beb7d30](https://linux-hardware.org/?probe=a25beb7d30) | Sep 24, 2024 |
| Dell          | Inspiron 3480               | [427d801a8c](https://linux-hardware.org/?probe=427d801a8c) | Sep 24, 2024 |
| HP            | 255 G7 Notebook PC          | [afadf0990e](https://linux-hardware.org/?probe=afadf0990e) | Sep 24, 2024 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [8be8636936](https://linux-hardware.org/?probe=8be8636936) | Sep 24, 2024 |
| Acer          | Aspire A315-21              | [6d1d288b78](https://linux-hardware.org/?probe=6d1d288b78) | Sep 23, 2024 |
| Apple         | MacBookPro11,2              | [f82874c7bf](https://linux-hardware.org/?probe=f82874c7bf) | Sep 23, 2024 |
| Apple         | MacBook9,1                  | [99bbe2dde8](https://linux-hardware.org/?probe=99bbe2dde8) | Sep 23, 2024 |
| HP            | EliteBook 840 G5            | [a6c2ea003a](https://linux-hardware.org/?probe=a6c2ea003a) | Sep 23, 2024 |
| Acer          | Nitro ANV15-51              | [cb05db35d0](https://linux-hardware.org/?probe=cb05db35d0) | Sep 23, 2024 |
| Dell          | Precision 5750              | [9fe4ca4c16](https://linux-hardware.org/?probe=9fe4ca4c16) | Sep 23, 2024 |
| Acer          | Aspire 5741G                | [0ec5e1b286](https://linux-hardware.org/?probe=0ec5e1b286) | Sep 23, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2761cb9d0a](https://linux-hardware.org/?probe=2761cb9d0a) | Sep 23, 2024 |
| Dell          | Precision 5750              | [34ccb39f7e](https://linux-hardware.org/?probe=34ccb39f7e) | Sep 23, 2024 |
| Dell          | Precision 7720              | [a4383ff70c](https://linux-hardware.org/?probe=a4383ff70c) | Sep 23, 2024 |
| Dell          | Precision 7720              | [20fa60176f](https://linux-hardware.org/?probe=20fa60176f) | Sep 23, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [5872050527](https://linux-hardware.org/?probe=5872050527) | Sep 23, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [9ef6e2eb2e](https://linux-hardware.org/?probe=9ef6e2eb2e) | Sep 23, 2024 |
| MSI           | H110M PRO-VH PLUS           | [9ad9765626](https://linux-hardware.org/?probe=9ad9765626) | Sep 23, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b2ee829194](https://linux-hardware.org/?probe=b2ee829194) | Sep 22, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [753000c68b](https://linux-hardware.org/?probe=753000c68b) | Sep 22, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [12453cb09e](https://linux-hardware.org/?probe=12453cb09e) | Sep 22, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [dc3efeacb0](https://linux-hardware.org/?probe=dc3efeacb0) | Sep 22, 2024 |
| Dell          | G5 5590                     | [b6a29e38bc](https://linux-hardware.org/?probe=b6a29e38bc) | Sep 22, 2024 |
| Dell          | G5 5590                     | [3fecd0e8ed](https://linux-hardware.org/?probe=3fecd0e8ed) | Sep 22, 2024 |
| ASUSTek       | X550CL                      | [81e41b1e3a](https://linux-hardware.org/?probe=81e41b1e3a) | Sep 22, 2024 |
| Dell          | Latitude 5290 2-in-1        | [c6a31952c8](https://linux-hardware.org/?probe=c6a31952c8) | Sep 22, 2024 |
| HP            | mt41                        | [43ec5adfbb](https://linux-hardware.org/?probe=43ec5adfbb) | Sep 22, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1daf0e051a](https://linux-hardware.org/?probe=1daf0e051a) | Sep 22, 2024 |
| Lenovo        | ThinkPad X100e 2876CTO      | [7282bf9e1e](https://linux-hardware.org/?probe=7282bf9e1e) | Sep 22, 2024 |
| Avell High... | B.ON                        | [e0a58907d4](https://linux-hardware.org/?probe=e0a58907d4) | Sep 22, 2024 |
| HP            | ProBook 650 G3              | [bcf5899b61](https://linux-hardware.org/?probe=bcf5899b61) | Sep 22, 2024 |
| HP            | mt41                        | [e73acf9786](https://linux-hardware.org/?probe=e73acf9786) | Sep 22, 2024 |
| Acer          | Predator PH16-71            | [4a96095a65](https://linux-hardware.org/?probe=4a96095a65) | Sep 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18f4f034a3](https://linux-hardware.org/?probe=18f4f034a3) | Sep 21, 2024 |
| HP            | ProBook 450 G3              | [ceef2c6eb0](https://linux-hardware.org/?probe=ceef2c6eb0) | Sep 21, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [f79e932a7a](https://linux-hardware.org/?probe=f79e932a7a) | Sep 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [9185553180](https://linux-hardware.org/?probe=9185553180) | Sep 21, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [16e05d44a4](https://linux-hardware.org/?probe=16e05d44a4) | Sep 21, 2024 |
| Dell          | Inspiron 5567               | [2ffb704d95](https://linux-hardware.org/?probe=2ffb704d95) | Sep 21, 2024 |
| HP            | Notebook                    | [9c2e3e0589](https://linux-hardware.org/?probe=9c2e3e0589) | Sep 21, 2024 |
| Acer          | Aspire A315-42              | [2a4a97599e](https://linux-hardware.org/?probe=2a4a97599e) | Sep 21, 2024 |
| Acer          | Nitro AN515-54              | [7fb7c1c4aa](https://linux-hardware.org/?probe=7fb7c1c4aa) | Sep 21, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d573658a58](https://linux-hardware.org/?probe=d573658a58) | Sep 20, 2024 |
| Acer          | Nitro AN515-54              | [a365378bd0](https://linux-hardware.org/?probe=a365378bd0) | Sep 20, 2024 |
| HP            | Notebook                    | [880bf3d95a](https://linux-hardware.org/?probe=880bf3d95a) | Sep 20, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [1659219206](https://linux-hardware.org/?probe=1659219206) | Sep 20, 2024 |
| ASUSTek       | X411UN                      | [d4bc8d6e18](https://linux-hardware.org/?probe=d4bc8d6e18) | Sep 20, 2024 |
| MSI           | Prestige 14 A10RB           | [f8b0fb37bc](https://linux-hardware.org/?probe=f8b0fb37bc) | Sep 20, 2024 |
| HP            | EliteBook 830 G5            | [d35be3d520](https://linux-hardware.org/?probe=d35be3d520) | Sep 20, 2024 |
| ASUSTek       | X411UN                      | [58db6ddb64](https://linux-hardware.org/?probe=58db6ddb64) | Sep 20, 2024 |
| HP            | Laptop 15-bs0xx             | [c22b23aa7e](https://linux-hardware.org/?probe=c22b23aa7e) | Sep 20, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU605MZ... | [b8990e6727](https://linux-hardware.org/?probe=b8990e6727) | Sep 20, 2024 |
| HP            | Victus by Gaming Laptop ... | [e647d35e74](https://linux-hardware.org/?probe=e647d35e74) | Sep 20, 2024 |
| Samsung       | 520U4C/520U4X               | [7d59f26919](https://linux-hardware.org/?probe=7d59f26919) | Sep 20, 2024 |
| HP            | Victus by Gaming Laptop ... | [59adb2dd76](https://linux-hardware.org/?probe=59adb2dd76) | Sep 20, 2024 |
| Dell          | Precision 3591              | [563dbb0f5a](https://linux-hardware.org/?probe=563dbb0f5a) | Sep 20, 2024 |
| MSI           | GP66 Leopard 11UH           | [1400dccdf2](https://linux-hardware.org/?probe=1400dccdf2) | Sep 20, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [96d0c8fdb6](https://linux-hardware.org/?probe=96d0c8fdb6) | Sep 20, 2024 |
| HP            | ZBook 15                    | [0c69053683](https://linux-hardware.org/?probe=0c69053683) | Sep 19, 2024 |
| realme        | RMNBXXXX                    | [40ebd6d2d1](https://linux-hardware.org/?probe=40ebd6d2d1) | Sep 19, 2024 |
| VIT           | M2420                       | [0ab836dd8d](https://linux-hardware.org/?probe=0ab836dd8d) | Sep 19, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [9d05a2b904](https://linux-hardware.org/?probe=9d05a2b904) | Sep 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [dfca2e65f8](https://linux-hardware.org/?probe=dfca2e65f8) | Sep 19, 2024 |
| Dell          | Latitude 5500               | [501082c1fa](https://linux-hardware.org/?probe=501082c1fa) | Sep 19, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f55c8205c](https://linux-hardware.org/?probe=1f55c8205c) | Sep 19, 2024 |
| Packard Be... | EasyNote TN65               | [08791fd1e4](https://linux-hardware.org/?probe=08791fd1e4) | Sep 19, 2024 |
| Lenovo        | ThinkPad T490 20N3S8T22A    | [32ec38ff8c](https://linux-hardware.org/?probe=32ec38ff8c) | Sep 19, 2024 |
| Dell          | Inspiron 5593               | [f0cb4e0c5d](https://linux-hardware.org/?probe=f0cb4e0c5d) | Sep 19, 2024 |
| ASUSTek       | GL503VM                     | [e902c6f46a](https://linux-hardware.org/?probe=e902c6f46a) | Sep 19, 2024 |
| HUAWEI        | FLMH-XX                     | [c451e8d47c](https://linux-hardware.org/?probe=c451e8d47c) | Sep 18, 2024 |
| Dell          | Latitude 5580               | [84da47bab6](https://linux-hardware.org/?probe=84da47bab6) | Sep 18, 2024 |
| ASUSTek       | ZenBook Pro Duo UX581GV     | [f66f374e96](https://linux-hardware.org/?probe=f66f374e96) | Sep 18, 2024 |
| ASUSTek       | ZenBook Pro Duo UX581GV     | [f99ef4e656](https://linux-hardware.org/?probe=f99ef4e656) | Sep 18, 2024 |
| ASUSTek       | ASUSLaptop_Q530VJ           | [41dc349281](https://linux-hardware.org/?probe=41dc349281) | Sep 18, 2024 |
| ASUSTek       | ASUSLaptop_Q530VJ           | [c8569b8aa7](https://linux-hardware.org/?probe=c8569b8aa7) | Sep 18, 2024 |
| HP            | Victus by Laptop 16-e1xx... | [2b87bb3b60](https://linux-hardware.org/?probe=2b87bb3b60) | Sep 18, 2024 |
| Apple         | MacBookPro14,1              | [004786a4d3](https://linux-hardware.org/?probe=004786a4d3) | Sep 18, 2024 |
| LG Electro... | 16Z90R-G.AD7CG              | [6f3ae7e9dd](https://linux-hardware.org/?probe=6f3ae7e9dd) | Sep 18, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [6d272a054d](https://linux-hardware.org/?probe=6d272a054d) | Sep 18, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [c52e98c803](https://linux-hardware.org/?probe=c52e98c803) | Sep 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8640... | [f6d7aba39d](https://linux-hardware.org/?probe=f6d7aba39d) | Sep 18, 2024 |
| Lenovo        | Legion 9 16IRX9 83G0        | [12e9df64e7](https://linux-hardware.org/?probe=12e9df64e7) | Sep 18, 2024 |
| Dell          | Latitude E7470              | [03e3962b06](https://linux-hardware.org/?probe=03e3962b06) | Sep 18, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [d80c5e46a5](https://linux-hardware.org/?probe=d80c5e46a5) | Sep 18, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [afd60ed1d2](https://linux-hardware.org/?probe=afd60ed1d2) | Sep 18, 2024 |
| Dell          | Inspiron 5402               | [3f4d1f2f6f](https://linux-hardware.org/?probe=3f4d1f2f6f) | Sep 18, 2024 |
| ASUSTek       | G751JL                      | [52a8615d4c](https://linux-hardware.org/?probe=52a8615d4c) | Sep 18, 2024 |
| HP            | EliteBook 850 G6            | [b17e3e3f74](https://linux-hardware.org/?probe=b17e3e3f74) | Sep 17, 2024 |
| HP            | ZBook 15 G6                 | [edda518320](https://linux-hardware.org/?probe=edda518320) | Sep 17, 2024 |
| Dell          | Inspiron 3505               | [cfc5cce54a](https://linux-hardware.org/?probe=cfc5cce54a) | Sep 17, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [048b958f3f](https://linux-hardware.org/?probe=048b958f3f) | Sep 17, 2024 |
| Insyde        | I86                         | [e9c8a3bdcc](https://linux-hardware.org/?probe=e9c8a3bdcc) | Sep 17, 2024 |
| MSI           | Modern 14 B11MOU            | [71b193b765](https://linux-hardware.org/?probe=71b193b765) | Sep 17, 2024 |
| Lenovo        | ThinkPad P51 20HH000TUS     | [3b55f65cd8](https://linux-hardware.org/?probe=3b55f65cd8) | Sep 17, 2024 |
| Lenovo        | ThinkPad E550 20DF004HKD    | [3f884bbbaa](https://linux-hardware.org/?probe=3f884bbbaa) | Sep 17, 2024 |
| ASUSTek       | N552VW                      | [d6e3386113](https://linux-hardware.org/?probe=d6e3386113) | Sep 17, 2024 |
| Acer          | Aspire E5-571P              | [237600bfd8](https://linux-hardware.org/?probe=237600bfd8) | Sep 17, 2024 |
| Apple         | MacBookAir6,1               | [f280566505](https://linux-hardware.org/?probe=f280566505) | Sep 17, 2024 |
| Apple         | MacBookAir6,1               | [3bc4e39ea8](https://linux-hardware.org/?probe=3bc4e39ea8) | Sep 17, 2024 |
| ASUSTek       | X550JX                      | [6d52e722d2](https://linux-hardware.org/?probe=6d52e722d2) | Sep 17, 2024 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [696670c392](https://linux-hardware.org/?probe=696670c392) | Sep 16, 2024 |
| Apple         | MacBookAir8,2               | [fe96fbd2cd](https://linux-hardware.org/?probe=fe96fbd2cd) | Sep 16, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [42d5c7a71e](https://linux-hardware.org/?probe=42d5c7a71e) | Sep 16, 2024 |
| Insyde        | I86                         | [ad18628c42](https://linux-hardware.org/?probe=ad18628c42) | Sep 16, 2024 |
| Google        | Bluebird                    | [37715d6b1e](https://linux-hardware.org/?probe=37715d6b1e) | Sep 16, 2024 |
| Acer          | Aspire F5-573G              | [c140c4229e](https://linux-hardware.org/?probe=c140c4229e) | Sep 16, 2024 |
| ASUSTek       | X555LAB                     | [89b2177889](https://linux-hardware.org/?probe=89b2177889) | Sep 16, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | [b7d362f58d](https://linux-hardware.org/?probe=b7d362f58d) | Sep 16, 2024 |
| Dell          | Inspiron 7537               | [52f4b56ba1](https://linux-hardware.org/?probe=52f4b56ba1) | Sep 16, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M7C... | [e5b6891ce8](https://linux-hardware.org/?probe=e5b6891ce8) | Sep 16, 2024 |
| ASUSTek       | GL503VM                     | [2453276424](https://linux-hardware.org/?probe=2453276424) | Sep 16, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [8bc9d0de32](https://linux-hardware.org/?probe=8bc9d0de32) | Sep 16, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7a23f7cc90](https://linux-hardware.org/?probe=7a23f7cc90) | Sep 16, 2024 |
| Acer          | Extensa 215-23              | [4eb675a392](https://linux-hardware.org/?probe=4eb675a392) | Sep 16, 2024 |
| Dell          | Inspiron 7560               | [6e9451de3a](https://linux-hardware.org/?probe=6e9451de3a) | Sep 15, 2024 |
| Dell          | Inspiron 7560               | [fed6c12a5e](https://linux-hardware.org/?probe=fed6c12a5e) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d41454dadb](https://linux-hardware.org/?probe=d41454dadb) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7f8844716d](https://linux-hardware.org/?probe=7f8844716d) | Sep 15, 2024 |
| Apple         | MacBookPro5,2               | [8ff2aff753](https://linux-hardware.org/?probe=8ff2aff753) | Sep 15, 2024 |
| HP            | ZBook 17 G2                 | [15c61e5e5d](https://linux-hardware.org/?probe=15c61e5e5d) | Sep 15, 2024 |
| Lenovo        | ThinkPad W520 42844DG       | [6ae32aef27](https://linux-hardware.org/?probe=6ae32aef27) | Sep 15, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [61cbf2c77f](https://linux-hardware.org/?probe=61cbf2c77f) | Sep 15, 2024 |
| Apple         | MacBookPro10,1              | [1fec1d3db3](https://linux-hardware.org/?probe=1fec1d3db3) | Sep 15, 2024 |
| Timi          | Mi NoteBook Pro             | [5cc0f3b8dc](https://linux-hardware.org/?probe=5cc0f3b8dc) | Sep 15, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [070de054b5](https://linux-hardware.org/?probe=070de054b5) | Sep 15, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5783d8f5b8](https://linux-hardware.org/?probe=5783d8f5b8) | Sep 15, 2024 |
| MSI           | Modern 14 B4MW              | [1e32af6401](https://linux-hardware.org/?probe=1e32af6401) | Sep 15, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [06a9408594](https://linux-hardware.org/?probe=06a9408594) | Sep 15, 2024 |
| HP            | Laptop 15-fc0xxx            | [be1922c0f5](https://linux-hardware.org/?probe=be1922c0f5) | Sep 15, 2024 |
| Apple         | MacBookPro5,2               | [78021d7a6b](https://linux-hardware.org/?probe=78021d7a6b) | Sep 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2d1f00b430](https://linux-hardware.org/?probe=2d1f00b430) | Sep 14, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JNS... | [9154b6e130](https://linux-hardware.org/?probe=9154b6e130) | Sep 14, 2024 |
| HP            | Pavilion Aero Laptop        | [378a1e1ce9](https://linux-hardware.org/?probe=378a1e1ce9) | Sep 14, 2024 |
| Lenovo        | ThinkPad T14s Gen 5 21LS... | [0d443adfb0](https://linux-hardware.org/?probe=0d443adfb0) | Sep 14, 2024 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | [45e681b236](https://linux-hardware.org/?probe=45e681b236) | Sep 14, 2024 |
| Dell          | Precision M4800             | [16e3018467](https://linux-hardware.org/?probe=16e3018467) | Sep 14, 2024 |
| Sony          | VPCEH2E0E                   | [0db705664d](https://linux-hardware.org/?probe=0db705664d) | Sep 14, 2024 |
| HONOR         | HYM-WXX                     | [86b75136f1](https://linux-hardware.org/?probe=86b75136f1) | Sep 14, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [a350f83b22](https://linux-hardware.org/?probe=a350f83b22) | Sep 14, 2024 |
| Dell          | Inspiron 1440               | [7371036197](https://linux-hardware.org/?probe=7371036197) | Sep 14, 2024 |
| LG Electro... | 16Z90R-K.AA78A1             | [20fac5cdd4](https://linux-hardware.org/?probe=20fac5cdd4) | Sep 14, 2024 |
| LG Electro... | 16Z90R-K.AA78A1             | [be5dd35fc2](https://linux-hardware.org/?probe=be5dd35fc2) | Sep 14, 2024 |
| Timi          | Mi NoteBook Pro             | [dd2c9cdb6a](https://linux-hardware.org/?probe=dd2c9cdb6a) | Sep 14, 2024 |
| Fujitsu       | FARQ06006                   | [c52b3facb2](https://linux-hardware.org/?probe=c52b3facb2) | Sep 14, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [df016642ea](https://linux-hardware.org/?probe=df016642ea) | Sep 14, 2024 |
| Apple         | MacBookPro12,1              | [e264945c26](https://linux-hardware.org/?probe=e264945c26) | Sep 14, 2024 |
| Apple         | MacBookPro12,1              | [e73d847f61](https://linux-hardware.org/?probe=e73d847f61) | Sep 14, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0b51bb9bd2](https://linux-hardware.org/?probe=0b51bb9bd2) | Sep 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [b0637fc9c7](https://linux-hardware.org/?probe=b0637fc9c7) | Sep 14, 2024 |
| Unknown       | Unknown                     | [c508820725](https://linux-hardware.org/?probe=c508820725) | Sep 14, 2024 |
| Acer          | Swift SF514-56T             | [9810b40a09](https://linux-hardware.org/?probe=9810b40a09) | Sep 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a20b0a103d](https://linux-hardware.org/?probe=a20b0a103d) | Sep 13, 2024 |
| Dell          | Latitude 5420               | [a921e02f6a](https://linux-hardware.org/?probe=a921e02f6a) | Sep 13, 2024 |
| Dell          | XPS 17 9730                 | [dbec469ebd](https://linux-hardware.org/?probe=dbec469ebd) | Sep 13, 2024 |
| Unknown       | Unknown                     | [f5cc9ae2cb](https://linux-hardware.org/?probe=f5cc9ae2cb) | Sep 13, 2024 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [8cc1cfd629](https://linux-hardware.org/?probe=8cc1cfd629) | Sep 13, 2024 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [ce710ab20c](https://linux-hardware.org/?probe=ce710ab20c) | Sep 13, 2024 |
| HP            | Dragonfly Pro ONE           | [ea5a903bc7](https://linux-hardware.org/?probe=ea5a903bc7) | Sep 13, 2024 |
| Acer          | Predator PHN16-71           | [0129ae7436](https://linux-hardware.org/?probe=0129ae7436) | Sep 13, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [94b9b06e69](https://linux-hardware.org/?probe=94b9b06e69) | Sep 13, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [9bcdf43c85](https://linux-hardware.org/?probe=9bcdf43c85) | Sep 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [a85edece16](https://linux-hardware.org/?probe=a85edece16) | Sep 12, 2024 |
| Apple         | MacBookPro14,1              | [34e2b18eed](https://linux-hardware.org/?probe=34e2b18eed) | Sep 12, 2024 |
| Apple         | MacBookPro9,2               | [1e0c78765a](https://linux-hardware.org/?probe=1e0c78765a) | Sep 12, 2024 |
| Acer          | Aspire A517-53              | [e65dd5192b](https://linux-hardware.org/?probe=e65dd5192b) | Sep 12, 2024 |
| ASUSTek       | ROG Strix G732LWS           | [235b3c37c1](https://linux-hardware.org/?probe=235b3c37c1) | Sep 12, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [e6fc0b663c](https://linux-hardware.org/?probe=e6fc0b663c) | Sep 12, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [e54db6ea20](https://linux-hardware.org/?probe=e54db6ea20) | Sep 12, 2024 |
| Framework     | Laptop 13 (Intel Core Ul... | [b5b2f25d38](https://linux-hardware.org/?probe=b5b2f25d38) | Sep 12, 2024 |
| Acer          | Aspire M3-581PT             | [a8d7660e94](https://linux-hardware.org/?probe=a8d7660e94) | Sep 12, 2024 |
| HP            | ZBook 17 G2                 | [b484f7d804](https://linux-hardware.org/?probe=b484f7d804) | Sep 12, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8640... | [b31a0e8b1d](https://linux-hardware.org/?probe=b31a0e8b1d) | Sep 12, 2024 |
| HUAWEI        | NBM-WXX9                    | [c1712b4ef5](https://linux-hardware.org/?probe=c1712b4ef5) | Sep 12, 2024 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [71465e244f](https://linux-hardware.org/?probe=71465e244f) | Sep 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a65cafef3a](https://linux-hardware.org/?probe=a65cafef3a) | Sep 12, 2024 |
| Dell          | Latitude 5540               | [fb34d8c85e](https://linux-hardware.org/?probe=fb34d8c85e) | Sep 11, 2024 |
| Lenovo        | ThinkPad T480 20L6SFB100    | [03d2f82def](https://linux-hardware.org/?probe=03d2f82def) | Sep 11, 2024 |
| HP            | Laptop 15s-eq2xxx           | [1d019808fa](https://linux-hardware.org/?probe=1d019808fa) | Sep 11, 2024 |
| HP            | Laptop 15-fc0xxx            | [7b0abd1147](https://linux-hardware.org/?probe=7b0abd1147) | Sep 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0a84c9af97](https://linux-hardware.org/?probe=0a84c9af97) | Sep 11, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [a7abab3361](https://linux-hardware.org/?probe=a7abab3361) | Sep 11, 2024 |
| Google        | Bluebird                    | [2721bc7aaa](https://linux-hardware.org/?probe=2721bc7aaa) | Sep 11, 2024 |
| Dell          | Latitude 5520               | [48e02de343](https://linux-hardware.org/?probe=48e02de343) | Sep 11, 2024 |
| Dell          | XPS 15 9500                 | [58404164b9](https://linux-hardware.org/?probe=58404164b9) | Sep 11, 2024 |
| HP            | Laptop 15-bs0xx             | [0a7952610f](https://linux-hardware.org/?probe=0a7952610f) | Sep 11, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | [cbd5c6f4d1](https://linux-hardware.org/?probe=cbd5c6f4d1) | Sep 11, 2024 |
| ASUSTek       | X550JX                      | [a19d7dbbc7](https://linux-hardware.org/?probe=a19d7dbbc7) | Sep 11, 2024 |
| HP            | Pavilion Plus Laptop 14z... | [b2d6a23382](https://linux-hardware.org/?probe=b2d6a23382) | Sep 11, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | [a690f1cdb6](https://linux-hardware.org/?probe=a690f1cdb6) | Sep 11, 2024 |
| HONOR         | FRI-FXX                     | [10da812ef6](https://linux-hardware.org/?probe=10da812ef6) | Sep 10, 2024 |
| HUAWEI        | KLVL-WXX9                   | [ce88062d16](https://linux-hardware.org/?probe=ce88062d16) | Sep 10, 2024 |
| Apple         | MacBookPro14,1              | [03dfadf1e7](https://linux-hardware.org/?probe=03dfadf1e7) | Sep 10, 2024 |
| HP            | Dragonfly Pro ONE           | [816005b8fa](https://linux-hardware.org/?probe=816005b8fa) | Sep 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [a89fe7cf2e](https://linux-hardware.org/?probe=a89fe7cf2e) | Sep 10, 2024 |
| MSI           | Bravo 17 A4DDR              | [1dfeb24a87](https://linux-hardware.org/?probe=1dfeb24a87) | Sep 10, 2024 |
| Apple         | MacBookPro8,1               | [fdb4c24263](https://linux-hardware.org/?probe=fdb4c24263) | Sep 10, 2024 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [afe420697f](https://linux-hardware.org/?probe=afe420697f) | Sep 10, 2024 |
| HP            | EliteBook 850 G2            | [564d24fc5f](https://linux-hardware.org/?probe=564d24fc5f) | Sep 10, 2024 |
| HP            | EliteBook 840 G6            | [9fe4170603](https://linux-hardware.org/?probe=9fe4170603) | Sep 10, 2024 |
| Dell          | Inspiron 15 3520            | [91ef18ff7f](https://linux-hardware.org/?probe=91ef18ff7f) | Sep 10, 2024 |
| HP            | EliteBook 835 G8 Noteboo... | [7b97957b7a](https://linux-hardware.org/?probe=7b97957b7a) | Sep 10, 2024 |
| ASUSTek       | ASUS Vivobook S 15 M5506... | [405394d8a0](https://linux-hardware.org/?probe=405394d8a0) | Sep 10, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [8f7ee39306](https://linux-hardware.org/?probe=8f7ee39306) | Sep 09, 2024 |
| Lenovo        | ThinkPad T580 20LAS6TM00    | [6b50046e25](https://linux-hardware.org/?probe=6b50046e25) | Sep 09, 2024 |
| HUAWEI        | HVY-WXX9                    | [44f0f1aac2](https://linux-hardware.org/?probe=44f0f1aac2) | Sep 09, 2024 |
| Dell          | G15 5530                    | [44c02e89a4](https://linux-hardware.org/?probe=44c02e89a4) | Sep 09, 2024 |
| Lenovo        | ThinkPad T480s 20L70025U... | [6906134330](https://linux-hardware.org/?probe=6906134330) | Sep 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [8cb22dd22a](https://linux-hardware.org/?probe=8cb22dd22a) | Sep 09, 2024 |
| HUAWEI        | HVY-WXX9                    | [c53d292f57](https://linux-hardware.org/?probe=c53d292f57) | Sep 09, 2024 |
| Apple         | MacBookPro11,2              | [c329793ba2](https://linux-hardware.org/?probe=c329793ba2) | Sep 09, 2024 |
| Dell          | Latitude E5270              | [75e63f90f7](https://linux-hardware.org/?probe=75e63f90f7) | Sep 09, 2024 |
| Dell          | XPS 15 9510                 | [1798e2816b](https://linux-hardware.org/?probe=1798e2816b) | Sep 09, 2024 |
| Dell          | XPS 13 9340                 | [1277dadaa4](https://linux-hardware.org/?probe=1277dadaa4) | Sep 09, 2024 |
| Dell          | XPS 13 9310                 | [38f0a1d2cc](https://linux-hardware.org/?probe=38f0a1d2cc) | Sep 09, 2024 |
| Gigabyte      | AERO 17 KC                  | [ef6af38948](https://linux-hardware.org/?probe=ef6af38948) | Sep 09, 2024 |
| MSI           | Summit E16Flip A12UDT       | [d839fcca1e](https://linux-hardware.org/?probe=d839fcca1e) | Sep 09, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [b2bda3297a](https://linux-hardware.org/?probe=b2bda3297a) | Sep 09, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [97578fa017](https://linux-hardware.org/?probe=97578fa017) | Sep 09, 2024 |
| HP            | Laptop 14s-fq1xxx           | [afd4f003e2](https://linux-hardware.org/?probe=afd4f003e2) | Sep 09, 2024 |
| Lenovo        | Flex 3-1580 80R4            | [3e658a0090](https://linux-hardware.org/?probe=3e658a0090) | Sep 09, 2024 |
| ASUSTek       | ASUS Vivobook S 15 M5506... | [fa5f58a7f1](https://linux-hardware.org/?probe=fa5f58a7f1) | Sep 09, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [5b6c362951](https://linux-hardware.org/?probe=5b6c362951) | Sep 09, 2024 |
| HP            | EliteBook 820 G2            | [0ea31e9a91](https://linux-hardware.org/?probe=0ea31e9a91) | Sep 09, 2024 |
| Samsung       | 940XFG                      | [4afba7e537](https://linux-hardware.org/?probe=4afba7e537) | Sep 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [21a97d52c8](https://linux-hardware.org/?probe=21a97d52c8) | Sep 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [88cc82dc97](https://linux-hardware.org/?probe=88cc82dc97) | Sep 08, 2024 |
| Timi          | Mi NoteBook Ultra           | [65b3524b81](https://linux-hardware.org/?probe=65b3524b81) | Sep 08, 2024 |
| HP            | EliteBook 8460p             | [d28a7d92f7](https://linux-hardware.org/?probe=d28a7d92f7) | Sep 08, 2024 |
| HP            | EliteBook 8460p             | [375da72314](https://linux-hardware.org/?probe=375da72314) | Sep 08, 2024 |
| MSI           | GS72 6QE                    | [f727148d69](https://linux-hardware.org/?probe=f727148d69) | Sep 08, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [83fffbe211](https://linux-hardware.org/?probe=83fffbe211) | Sep 08, 2024 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [7ab4f22e0a](https://linux-hardware.org/?probe=7ab4f22e0a) | Sep 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | [099a44d5c4](https://linux-hardware.org/?probe=099a44d5c4) | Sep 08, 2024 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b200161c65](https://linux-hardware.org/?probe=b200161c65) | Sep 08, 2024 |
| Dell          | Latitude E5570              | [2e9045765c](https://linux-hardware.org/?probe=2e9045765c) | Sep 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [d46b86a77f](https://linux-hardware.org/?probe=d46b86a77f) | Sep 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [2a1feab9bf](https://linux-hardware.org/?probe=2a1feab9bf) | Sep 08, 2024 |
| Apple         | MacBookPro8,1               | [6488d13a49](https://linux-hardware.org/?probe=6488d13a49) | Sep 08, 2024 |
| ASUSTek       | X510URR                     | [27ad81edd7](https://linux-hardware.org/?probe=27ad81edd7) | Sep 07, 2024 |
| Lenovo        | ThinkPad X280 20KF001GGE    | [41b3f178e6](https://linux-hardware.org/?probe=41b3f178e6) | Sep 07, 2024 |
| Dell          | Latitude 7480               | [50c9089652](https://linux-hardware.org/?probe=50c9089652) | Sep 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3dc2a0c586](https://linux-hardware.org/?probe=3dc2a0c586) | Sep 07, 2024 |
| HP            | Laptop 15-dy5xxx            | [5c809a6628](https://linux-hardware.org/?probe=5c809a6628) | Sep 07, 2024 |
| HP            | Laptop 15-dy5xxx            | [62f690418d](https://linux-hardware.org/?probe=62f690418d) | Sep 07, 2024 |
| Apple         | MacBookPro11,2              | [277183655d](https://linux-hardware.org/?probe=277183655d) | Sep 07, 2024 |
| Notebook      | W65KJ1_KK1                  | [54dc17b5cd](https://linux-hardware.org/?probe=54dc17b5cd) | Sep 07, 2024 |
| HP            | Pavilion dv6                | [3912214dfe](https://linux-hardware.org/?probe=3912214dfe) | Sep 07, 2024 |
| HP            | Pavilion dv6                | [c76473b98c](https://linux-hardware.org/?probe=c76473b98c) | Sep 07, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [736cea649b](https://linux-hardware.org/?probe=736cea649b) | Sep 07, 2024 |
| Dell          | Latitude 5420               | [b325ffdd85](https://linux-hardware.org/?probe=b325ffdd85) | Sep 07, 2024 |
| Casper        | EXCALIBUR G770              | [d108785bd9](https://linux-hardware.org/?probe=d108785bd9) | Sep 07, 2024 |
| Casper        | EXCALIBUR G770              | [5751df0967](https://linux-hardware.org/?probe=5751df0967) | Sep 07, 2024 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9c44e7602a](https://linux-hardware.org/?probe=9c44e7602a) | Sep 07, 2024 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [5bcc850dbd](https://linux-hardware.org/?probe=5bcc850dbd) | Sep 07, 2024 |
| Dell          | Latitude 5480               | [5a335696d8](https://linux-hardware.org/?probe=5a335696d8) | Sep 07, 2024 |
| Apple         | MacBookPro5,5               | [93368dde72](https://linux-hardware.org/?probe=93368dde72) | Sep 07, 2024 |
| Lenovo        | ThinkPad T540p 20BECTO1W... | [ebcfa80154](https://linux-hardware.org/?probe=ebcfa80154) | Sep 07, 2024 |
| Dell          | Latitude E5570              | [1734eacb6f](https://linux-hardware.org/?probe=1734eacb6f) | Sep 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [558e2441f3](https://linux-hardware.org/?probe=558e2441f3) | Sep 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [90887c7486](https://linux-hardware.org/?probe=90887c7486) | Sep 06, 2024 |
| Maibenben     | Perfectum Series            | [8e92876c60](https://linux-hardware.org/?probe=8e92876c60) | Sep 06, 2024 |
| MSI           | B450M BAZOOKA V2            | [72dc3e5ddb](https://linux-hardware.org/?probe=72dc3e5ddb) | Sep 06, 2024 |
| HP            | Notebook                    | [f0c02f3bc1](https://linux-hardware.org/?probe=f0c02f3bc1) | Sep 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1b5357f8b3](https://linux-hardware.org/?probe=1b5357f8b3) | Sep 06, 2024 |
| HP            | EliteBook 840 G5            | [9a594bf56d](https://linux-hardware.org/?probe=9a594bf56d) | Sep 06, 2024 |
| Timi          | Redmi Book Pro 14 2022      | [9eae2aa3e9](https://linux-hardware.org/?probe=9eae2aa3e9) | Sep 06, 2024 |
| ASUSTek       | Q553UB                      | [deb0858253](https://linux-hardware.org/?probe=deb0858253) | Sep 06, 2024 |
| Avell         | A52 HYB NEW                 | [5781bd393f](https://linux-hardware.org/?probe=5781bd393f) | Sep 06, 2024 |
| Avell         | A52 HYB NEW                 | [15c7a91a65](https://linux-hardware.org/?probe=15c7a91a65) | Sep 06, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [ecffd53863](https://linux-hardware.org/?probe=ecffd53863) | Sep 06, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [48f64a6eaf](https://linux-hardware.org/?probe=48f64a6eaf) | Sep 06, 2024 |
| HP            | ProBook 650 G4              | [e8edfbf65e](https://linux-hardware.org/?probe=e8edfbf65e) | Sep 05, 2024 |
| Samsung       | 960XGL                      | [92c178c78e](https://linux-hardware.org/?probe=92c178c78e) | Sep 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9bba1d7287](https://linux-hardware.org/?probe=9bba1d7287) | Sep 05, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [9da4458d4a](https://linux-hardware.org/?probe=9da4458d4a) | Sep 05, 2024 |
| HP            | Laptop 17-cn3xxx            | [fe37e84853](https://linux-hardware.org/?probe=fe37e84853) | Sep 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [32b933b3d1](https://linux-hardware.org/?probe=32b933b3d1) | Sep 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [815ddf6853](https://linux-hardware.org/?probe=815ddf6853) | Sep 05, 2024 |
| Lenovo        | ThinkPad T430 2344A15       | [ef361a731b](https://linux-hardware.org/?probe=ef361a731b) | Sep 05, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1a4cbd00f5](https://linux-hardware.org/?probe=1a4cbd00f5) | Sep 05, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [05d8ff52c0](https://linux-hardware.org/?probe=05d8ff52c0) | Sep 05, 2024 |
| K.A.Techno... | TM1                         | [f5a54e3e47](https://linux-hardware.org/?probe=f5a54e3e47) | Sep 05, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [734a4c8056](https://linux-hardware.org/?probe=734a4c8056) | Sep 04, 2024 |
| Dell          | Precision M6500             | [d38f4f3a0d](https://linux-hardware.org/?probe=d38f4f3a0d) | Sep 04, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [e814a945c1](https://linux-hardware.org/?probe=e814a945c1) | Sep 04, 2024 |
| Lenovo        | ThinkPad T560 20FJS1WT00    | [6d577588f9](https://linux-hardware.org/?probe=6d577588f9) | Sep 04, 2024 |
| Dell          | Inspiron 7572               | [48752ba8a1](https://linux-hardware.org/?probe=48752ba8a1) | Sep 04, 2024 |
| Dell          | Precision 5690              | [fe97e83a0c](https://linux-hardware.org/?probe=fe97e83a0c) | Sep 04, 2024 |
| Lenovo        | ThinkPad P52 20M9S0MQ00     | [b1ed83bba1](https://linux-hardware.org/?probe=b1ed83bba1) | Sep 04, 2024 |
| Dell          | Latitude 7440               | [c5f8a12f8b](https://linux-hardware.org/?probe=c5f8a12f8b) | Sep 04, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [8c9b872c4a](https://linux-hardware.org/?probe=8c9b872c4a) | Sep 03, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | [520785e72f](https://linux-hardware.org/?probe=520785e72f) | Sep 03, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | [9fbc883284](https://linux-hardware.org/?probe=9fbc883284) | Sep 03, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [74b60a3b85](https://linux-hardware.org/?probe=74b60a3b85) | Sep 03, 2024 |
| Chuwi         | MiniBook X                  | [d8c4b6d97f](https://linux-hardware.org/?probe=d8c4b6d97f) | Sep 03, 2024 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [c9474f150c](https://linux-hardware.org/?probe=c9474f150c) | Sep 03, 2024 |
| Acer          | Aspire AL14-31P             | [229145b0e7](https://linux-hardware.org/?probe=229145b0e7) | Sep 03, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [118c5274e0](https://linux-hardware.org/?probe=118c5274e0) | Sep 03, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | [0cf32a7c28](https://linux-hardware.org/?probe=0cf32a7c28) | Sep 03, 2024 |
| Acer          | Aspire 5750Z                | [ea1ca628e6](https://linux-hardware.org/?probe=ea1ca628e6) | Sep 03, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [1ac4846a16](https://linux-hardware.org/?probe=1ac4846a16) | Sep 03, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [0501fbf7ac](https://linux-hardware.org/?probe=0501fbf7ac) | Sep 02, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [56bdbb019e](https://linux-hardware.org/?probe=56bdbb019e) | Sep 02, 2024 |
| HONOR         | FRI-FXX                     | [c1cf4ffbab](https://linux-hardware.org/?probe=c1cf4ffbab) | Sep 02, 2024 |
| Samsung       | 940XFG                      | [aa1058489d](https://linux-hardware.org/?probe=aa1058489d) | Sep 02, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [46b2c8c407](https://linux-hardware.org/?probe=46b2c8c407) | Sep 02, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [75baa3ca2a](https://linux-hardware.org/?probe=75baa3ca2a) | Sep 02, 2024 |
| MSI           | GP62 6QF                    | [5bdc4dc696](https://linux-hardware.org/?probe=5bdc4dc696) | Sep 02, 2024 |
| Acer          | Aspire A315-24P             | [3f3c62d2ba](https://linux-hardware.org/?probe=3f3c62d2ba) | Sep 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [682b1cad5b](https://linux-hardware.org/?probe=682b1cad5b) | Sep 02, 2024 |
| Apple         | MacBookPro11,5              | [9670123d59](https://linux-hardware.org/?probe=9670123d59) | Sep 02, 2024 |
| Dell          | Latitude 5511               | [b63a8e1a5a](https://linux-hardware.org/?probe=b63a8e1a5a) | Sep 02, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [133c875de2](https://linux-hardware.org/?probe=133c875de2) | Sep 02, 2024 |
| Dell          | Inspiron 3501               | [384782e9c9](https://linux-hardware.org/?probe=384782e9c9) | Sep 02, 2024 |
| ASUSTek       | K53SV                       | [8a1d41c5fb](https://linux-hardware.org/?probe=8a1d41c5fb) | Sep 02, 2024 |
| Apple         | MacBookPro8,1               | [3de9cb3d60](https://linux-hardware.org/?probe=3de9cb3d60) | Sep 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [245966c79e](https://linux-hardware.org/?probe=245966c79e) | Sep 01, 2024 |
| Apple         | MacBookPro7,1               | [a3720d80f0](https://linux-hardware.org/?probe=a3720d80f0) | Sep 01, 2024 |
| HP            | Notebook                    | [347326e919](https://linux-hardware.org/?probe=347326e919) | Sep 01, 2024 |
| Apple         | MacBookPro7,1               | [2000ed4989](https://linux-hardware.org/?probe=2000ed4989) | Sep 01, 2024 |
| ASUSTek       | G750JS                      | [fe330265da](https://linux-hardware.org/?probe=fe330265da) | Sep 01, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [0a640526c1](https://linux-hardware.org/?probe=0a640526c1) | Sep 01, 2024 |
| Dell          | XPS 15 9530                 | [3a7f336a2c](https://linux-hardware.org/?probe=3a7f336a2c) | Sep 01, 2024 |
| HP            | G72                         | [3e3c18c84c](https://linux-hardware.org/?probe=3e3c18c84c) | Sep 01, 2024 |
| Dell          | XPS 14 9440                 | [7d09dc6039](https://linux-hardware.org/?probe=7d09dc6039) | Sep 01, 2024 |
| Dell          | Latitude 5401               | [be4f309714](https://linux-hardware.org/?probe=be4f309714) | Sep 01, 2024 |
| HP            | G72                         | [26352c9d5a](https://linux-hardware.org/?probe=26352c9d5a) | Sep 01, 2024 |
| Dell          | Precision 7740              | [49c0dd0ae9](https://linux-hardware.org/?probe=49c0dd0ae9) | Sep 01, 2024 |
| HP            | ProBook 455 15.6 inch G9... | [f1e0a7d241](https://linux-hardware.org/?probe=f1e0a7d241) | Sep 01, 2024 |
| Acer          | Aspire A515-56              | [0b1027a0fd](https://linux-hardware.org/?probe=0b1027a0fd) | Aug 31, 2024 |
| Dell          | Precision 7740              | [5f67818a4c](https://linux-hardware.org/?probe=5f67818a4c) | Aug 31, 2024 |
| Acer          | Predator PT316-51s          | [165b9b21e4](https://linux-hardware.org/?probe=165b9b21e4) | Aug 31, 2024 |
| ASUSTek       | K52F                        | [2f931b5122](https://linux-hardware.org/?probe=2f931b5122) | Aug 31, 2024 |
| Razer         | Blade 15 Advanced Model ... | [d976bc7ac5](https://linux-hardware.org/?probe=d976bc7ac5) | Aug 31, 2024 |
| Dell          | Vostro 16 5635              | [fc6900819a](https://linux-hardware.org/?probe=fc6900819a) | Aug 31, 2024 |
| HP            | ZBook Studio 16 inch G10... | [12c5234bb4](https://linux-hardware.org/?probe=12c5234bb4) | Aug 31, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [5f1a20d80b](https://linux-hardware.org/?probe=5f1a20d80b) | Aug 31, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [bded4e0703](https://linux-hardware.org/?probe=bded4e0703) | Aug 31, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [98dd6b1386](https://linux-hardware.org/?probe=98dd6b1386) | Aug 31, 2024 |
| Dell          | Latitude 5420               | [7aae0d42c2](https://linux-hardware.org/?probe=7aae0d42c2) | Aug 31, 2024 |
| Dell          | Vostro 16 5635              | [1eaac7d5c1](https://linux-hardware.org/?probe=1eaac7d5c1) | Aug 31, 2024 |
| Toshiba       | WT8-A                       | [427fe42ea1](https://linux-hardware.org/?probe=427fe42ea1) | Aug 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [acc91bcc92](https://linux-hardware.org/?probe=acc91bcc92) | Aug 30, 2024 |
| ASUSTek       | TP500LAB                    | [94b0ddb71b](https://linux-hardware.org/?probe=94b0ddb71b) | Aug 30, 2024 |
| HP            | EliteBook 865 16 inch G9... | [8f52a83d6b](https://linux-hardware.org/?probe=8f52a83d6b) | Aug 30, 2024 |
| Timi          | Mi Notebook Pro             | [b51c55748c](https://linux-hardware.org/?probe=b51c55748c) | Aug 30, 2024 |
| Apple         | MacBookPro7,1               | [82e779af12](https://linux-hardware.org/?probe=82e779af12) | Aug 30, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [381d377e54](https://linux-hardware.org/?probe=381d377e54) | Aug 30, 2024 |
| HP            | Laptop 17-by3xxx            | [53ebedbcd3](https://linux-hardware.org/?probe=53ebedbcd3) | Aug 29, 2024 |
| HP            | Dragonfly Pro ONE           | [24e3709aa5](https://linux-hardware.org/?probe=24e3709aa5) | Aug 29, 2024 |
| HUAWEI        | KLVL-WXXW                   | [3412e900ef](https://linux-hardware.org/?probe=3412e900ef) | Aug 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 5 21L2S... | [2c0e8d6521](https://linux-hardware.org/?probe=2c0e8d6521) | Aug 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 5 21L2S... | [c3d33859e4](https://linux-hardware.org/?probe=c3d33859e4) | Aug 29, 2024 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [8886ae523e](https://linux-hardware.org/?probe=8886ae523e) | Aug 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [5502afcee2](https://linux-hardware.org/?probe=5502afcee2) | Aug 29, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [74cc53bc31](https://linux-hardware.org/?probe=74cc53bc31) | Aug 29, 2024 |
| Lenovo        | ThinkPad Z16 Gen 2 21JX0... | [516ac7a1f3](https://linux-hardware.org/?probe=516ac7a1f3) | Aug 29, 2024 |
| Dell          | Inspiron 5579               | [4e6014b422](https://linux-hardware.org/?probe=4e6014b422) | Aug 29, 2024 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [3eb74f889c](https://linux-hardware.org/?probe=3eb74f889c) | Aug 29, 2024 |
| Framework     | Laptop 13 (Intel Core Ul... | [633b884968](https://linux-hardware.org/?probe=633b884968) | Aug 29, 2024 |
| HP            | Pavilion Laptop 14-ce3xx... | [064e1eae52](https://linux-hardware.org/?probe=064e1eae52) | Aug 29, 2024 |
| HP            | Pavilion Laptop 14-ce3xx... | [3cfbee40d3](https://linux-hardware.org/?probe=3cfbee40d3) | Aug 29, 2024 |
| Acer          | Aspire A715-51G             | [f631cf58e3](https://linux-hardware.org/?probe=f631cf58e3) | Aug 29, 2024 |
| Toshiba       | Satellite C55D-B            | [25708fcb1c](https://linux-hardware.org/?probe=25708fcb1c) | Aug 29, 2024 |
| HP            | ENVY 15                     | [bb6e6b46f0](https://linux-hardware.org/?probe=bb6e6b46f0) | Aug 29, 2024 |
| Dell          | Inspiron 5579               | [1acc72d360](https://linux-hardware.org/?probe=1acc72d360) | Aug 29, 2024 |
| Apple         | MacBookPro13,2              | [1b0112eb88](https://linux-hardware.org/?probe=1b0112eb88) | Aug 29, 2024 |
| Acer          | Aspire 5738                 | [f11fc75696](https://linux-hardware.org/?probe=f11fc75696) | Aug 29, 2024 |
| Acer          | Aspire 5738                 | [1eeedafcbd](https://linux-hardware.org/?probe=1eeedafcbd) | Aug 29, 2024 |
| Dell          | XPS 16 9640                 | [4978f9a29c](https://linux-hardware.org/?probe=4978f9a29c) | Aug 28, 2024 |
| Notebook      | PCx0Dx                      | [d36d294d4c](https://linux-hardware.org/?probe=d36d294d4c) | Aug 28, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [bf4ca5d368](https://linux-hardware.org/?probe=bf4ca5d368) | Aug 28, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | [1c13d8f468](https://linux-hardware.org/?probe=1c13d8f468) | Aug 28, 2024 |
| Dell          | Inspiron 3501               | [ffc73d2862](https://linux-hardware.org/?probe=ffc73d2862) | Aug 28, 2024 |
| Lenovo        | ThinkPad T490 20N2006NUS    | [604a2fb976](https://linux-hardware.org/?probe=604a2fb976) | Aug 28, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [244d64bcf6](https://linux-hardware.org/?probe=244d64bcf6) | Aug 28, 2024 |
| Dell          | Latitude 5520               | [f63ab5f58f](https://linux-hardware.org/?probe=f63ab5f58f) | Aug 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0670a48314](https://linux-hardware.org/?probe=0670a48314) | Aug 28, 2024 |
| ASUSTek       | ROG Flow X13 GV301QC_GV3... | [e0a86fbe96](https://linux-hardware.org/?probe=e0a86fbe96) | Aug 28, 2024 |
| HP            | ZBook Fury 15.6 inch G8 ... | [7033add9ee](https://linux-hardware.org/?probe=7033add9ee) | Aug 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f4acc2572c](https://linux-hardware.org/?probe=f4acc2572c) | Aug 27, 2024 |
| MSI           | Prestige 15 A11SC           | [13e5ee748a](https://linux-hardware.org/?probe=13e5ee748a) | Aug 27, 2024 |
| Dell          | Inspiron 1545               | [120b7ffea6](https://linux-hardware.org/?probe=120b7ffea6) | Aug 27, 2024 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9c5cfa098e](https://linux-hardware.org/?probe=9c5cfa098e) | Aug 27, 2024 |
| HP            | EliteBook 840 G5            | [a2c78743d3](https://linux-hardware.org/?probe=a2c78743d3) | Aug 27, 2024 |
| XIAOMI        | Redmi Book Pro 16 2024      | [fa9ec8c4bf](https://linux-hardware.org/?probe=fa9ec8c4bf) | Aug 27, 2024 |
| Acer          | Predator PHN16-71           | [337b7305bc](https://linux-hardware.org/?probe=337b7305bc) | Aug 27, 2024 |
| HUAWEI        | BOHB-WAX9                   | [b9f2e9fd0f](https://linux-hardware.org/?probe=b9f2e9fd0f) | Aug 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [10e7b03e65](https://linux-hardware.org/?probe=10e7b03e65) | Aug 27, 2024 |
| Acer          | Nitro ANV15-51              | [658312a83f](https://linux-hardware.org/?probe=658312a83f) | Aug 27, 2024 |
| Acer          | Aspire 4743                 | [2407fc17fc](https://linux-hardware.org/?probe=2407fc17fc) | Aug 27, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [f4feff91fa](https://linux-hardware.org/?probe=f4feff91fa) | Aug 27, 2024 |
| Dell          | XPS 13 9343                 | [75aa5b52af](https://linux-hardware.org/?probe=75aa5b52af) | Aug 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [3c99fdbd9c](https://linux-hardware.org/?probe=3c99fdbd9c) | Aug 26, 2024 |
| Unknown       | Unknown                     | [6ef6b36874](https://linux-hardware.org/?probe=6ef6b36874) | Aug 26, 2024 |
| Lenovo        | G50-70 20351                | [a7194178fb](https://linux-hardware.org/?probe=a7194178fb) | Aug 26, 2024 |
| Dell          | Precision M4800             | [96502a628e](https://linux-hardware.org/?probe=96502a628e) | Aug 26, 2024 |
| Acer          | Swift SFX14-41G             | [4977e3c5f8](https://linux-hardware.org/?probe=4977e3c5f8) | Aug 26, 2024 |
| Apple         | MacBookPro11,2              | [f6892d7513](https://linux-hardware.org/?probe=f6892d7513) | Aug 26, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [04b6aafa21](https://linux-hardware.org/?probe=04b6aafa21) | Aug 26, 2024 |
| Dell          | Studio 1749                 | [caff4fc4c0](https://linux-hardware.org/?probe=caff4fc4c0) | Aug 26, 2024 |
| ShenZhen Z... | NA08H                       | [9b814ce223](https://linux-hardware.org/?probe=9b814ce223) | Aug 26, 2024 |
| GPU Compan... | GWTN141-10                  | [56d15172b4](https://linux-hardware.org/?probe=56d15172b4) | Aug 26, 2024 |
| Alurin        | ALU-BAR-R757-000-156        | [c33dddd779](https://linux-hardware.org/?probe=c33dddd779) | Aug 26, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [6cb29fe22e](https://linux-hardware.org/?probe=6cb29fe22e) | Aug 25, 2024 |
| Positivo      | I38512BI-15                 | [6f39a3ff4e](https://linux-hardware.org/?probe=6f39a3ff4e) | Aug 25, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0d00087eaf](https://linux-hardware.org/?probe=0d00087eaf) | Aug 25, 2024 |
| Timi          | A35S                        | [0eceb7a4f7](https://linux-hardware.org/?probe=0eceb7a4f7) | Aug 25, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [83cd076649](https://linux-hardware.org/?probe=83cd076649) | Aug 25, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [3f0f6d878b](https://linux-hardware.org/?probe=3f0f6d878b) | Aug 25, 2024 |
| Lenovo        | ThinkPad X220 4289A92       | [60139dbbf1](https://linux-hardware.org/?probe=60139dbbf1) | Aug 25, 2024 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [b46990a5ac](https://linux-hardware.org/?probe=b46990a5ac) | Aug 25, 2024 |
| Lenovo        | ThinkPad E595 20NF001HGE    | [25857e2b9b](https://linux-hardware.org/?probe=25857e2b9b) | Aug 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [61c061245a](https://linux-hardware.org/?probe=61c061245a) | Aug 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [c6be7f3bf3](https://linux-hardware.org/?probe=c6be7f3bf3) | Aug 25, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H7C... | [efe6c30787](https://linux-hardware.org/?probe=efe6c30787) | Aug 25, 2024 |
| HP            | Pavilion dv6700             | [8a6c458a6b](https://linux-hardware.org/?probe=8a6c458a6b) | Aug 25, 2024 |
| Lenovo        | ThinkPad X230 2325S4N       | [cb8bc76587](https://linux-hardware.org/?probe=cb8bc76587) | Aug 25, 2024 |
| HP            | Pavilion dv6700             | [f3eedcecc1](https://linux-hardware.org/?probe=f3eedcecc1) | Aug 25, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [94baba1ddd](https://linux-hardware.org/?probe=94baba1ddd) | Aug 25, 2024 |
| Acer          | One S1002                   | [e7fbe039c8](https://linux-hardware.org/?probe=e7fbe039c8) | Aug 24, 2024 |
| Toshiba       | TECRA R940                  | [94a8813314](https://linux-hardware.org/?probe=94a8813314) | Aug 24, 2024 |
| Acer          | One S1002                   | [9f00745090](https://linux-hardware.org/?probe=9f00745090) | Aug 24, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c35c3ff2ea](https://linux-hardware.org/?probe=c35c3ff2ea) | Aug 24, 2024 |
| HP            | ZBook 17 G2                 | [dd2712a99b](https://linux-hardware.org/?probe=dd2712a99b) | Aug 24, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [c8c7a1fc43](https://linux-hardware.org/?probe=c8c7a1fc43) | Aug 24, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [d9ae779618](https://linux-hardware.org/?probe=d9ae779618) | Aug 24, 2024 |
| HP            | Notebook                    | [6ed4167b2b](https://linux-hardware.org/?probe=6ed4167b2b) | Aug 24, 2024 |
| Sony          | SVF1521H1EB                 | [f7a0c27cba](https://linux-hardware.org/?probe=f7a0c27cba) | Aug 24, 2024 |
| HP            | 250 G7 Notebook PC          | [039112a07f](https://linux-hardware.org/?probe=039112a07f) | Aug 24, 2024 |
| HP            | ENVY Notebook               | [0374693fee](https://linux-hardware.org/?probe=0374693fee) | Aug 24, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [b4bbb3c10a](https://linux-hardware.org/?probe=b4bbb3c10a) | Aug 24, 2024 |
| Google        | Bobba                       | [2e4550465e](https://linux-hardware.org/?probe=2e4550465e) | Aug 24, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2LN0... | [6898e279ae](https://linux-hardware.org/?probe=6898e279ae) | Aug 24, 2024 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [4a4cf112cc](https://linux-hardware.org/?probe=4a4cf112cc) | Aug 24, 2024 |
| Lenovo        | ThinkPad X260 20F5S3Y901    | [95bbbfc253](https://linux-hardware.org/?probe=95bbbfc253) | Aug 24, 2024 |
| Lenovo        | ThinkPad P52 20MAS3Q601     | [9f7516a089](https://linux-hardware.org/?probe=9f7516a089) | Aug 23, 2024 |
| Acer          | Aspire A715-71G             | [96deaa4c04](https://linux-hardware.org/?probe=96deaa4c04) | Aug 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a2229f95b](https://linux-hardware.org/?probe=2a2229f95b) | Aug 23, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [a8dbc3881b](https://linux-hardware.org/?probe=a8dbc3881b) | Aug 23, 2024 |
| Apple         | MacBookPro14,1              | [13aa3fa7f6](https://linux-hardware.org/?probe=13aa3fa7f6) | Aug 23, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 21G3... | [6ee9f17101](https://linux-hardware.org/?probe=6ee9f17101) | Aug 23, 2024 |
| Dell          | Latitude E6400              | [e8c0884ba1](https://linux-hardware.org/?probe=e8c0884ba1) | Aug 23, 2024 |
| HP            | EliteBook 840 G6            | [27ca85151e](https://linux-hardware.org/?probe=27ca85151e) | Aug 23, 2024 |
| ASUSTek       | ROG Flow X13 GV301QC_GV3... | [7305ee2b45](https://linux-hardware.org/?probe=7305ee2b45) | Aug 23, 2024 |
| Apple         | MacBookPro14,1              | [cf84650588](https://linux-hardware.org/?probe=cf84650588) | Aug 23, 2024 |
| Framework     | Laptop                      | [e3d4676078](https://linux-hardware.org/?probe=e3d4676078) | Aug 23, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [8b89513463](https://linux-hardware.org/?probe=8b89513463) | Aug 23, 2024 |
| Dell          | G3 3579                     | [e205cfc5e8](https://linux-hardware.org/?probe=e205cfc5e8) | Aug 23, 2024 |
| HP            | Pavilion Laptop 14-ec1xx... | [d9039ce75d](https://linux-hardware.org/?probe=d9039ce75d) | Aug 23, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [9ec2c392ec](https://linux-hardware.org/?probe=9ec2c392ec) | Aug 23, 2024 |
| MSI           | Katana GF66 11UC            | [2d222a09c5](https://linux-hardware.org/?probe=2d222a09c5) | Aug 22, 2024 |
| TECNO Mobi... | MEGABOOK T15DA              | [400884244e](https://linux-hardware.org/?probe=400884244e) | Aug 22, 2024 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [249cbe9aad](https://linux-hardware.org/?probe=249cbe9aad) | Aug 22, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [9a2d871eee](https://linux-hardware.org/?probe=9a2d871eee) | Aug 22, 2024 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [2a1227b5a1](https://linux-hardware.org/?probe=2a1227b5a1) | Aug 22, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [9883bc28dc](https://linux-hardware.org/?probe=9883bc28dc) | Aug 22, 2024 |
| Apple         | MacBookPro9,2               | [d3307bfd34](https://linux-hardware.org/?probe=d3307bfd34) | Aug 22, 2024 |
| HP            | EliteBook 8570w             | [dedcc35c4e](https://linux-hardware.org/?probe=dedcc35c4e) | Aug 22, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [9ea4cb510f](https://linux-hardware.org/?probe=9ea4cb510f) | Aug 22, 2024 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [83f3da5e32](https://linux-hardware.org/?probe=83f3da5e32) | Aug 22, 2024 |
| K.A.Techno... | TM1                         | [160af6cab3](https://linux-hardware.org/?probe=160af6cab3) | Aug 22, 2024 |
| Dell          | Latitude 5310               | [df5c866666](https://linux-hardware.org/?probe=df5c866666) | Aug 22, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [8cc040cae3](https://linux-hardware.org/?probe=8cc040cae3) | Aug 22, 2024 |
| HP            | EliteBook Folio 9480m       | [342d11ed39](https://linux-hardware.org/?probe=342d11ed39) | Aug 22, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [7e5e83f998](https://linux-hardware.org/?probe=7e5e83f998) | Aug 22, 2024 |
| HP            | Laptop 15-bs0xx             | [244824354d](https://linux-hardware.org/?probe=244824354d) | Aug 22, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_40/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 6.8.5-301.fc40.x86_64        | 251       | 11.04%  |
| 6.8.11-300.fc40.x86_64       | 177       | 7.79%   |
| 6.8.7-300.fc40.x86_64        | 141       | 6.2%    |
| 6.8.9-300.fc40.x86_64        | 125       | 5.5%    |
| 6.10.6-200.fc40.x86_64       | 124       | 5.46%   |
| 6.8.10-300.fc40.x86_64       | 93        | 4.09%   |
| 6.9.12-200.fc40.x86_64       | 81        | 3.56%   |
| 6.11.3-200.fc40.x86_64       | 81        | 3.56%   |
| 6.8.8-300.fc40.x86_64        | 80        | 3.52%   |
| 6.10.11-200.fc40.x86_64      | 79        | 3.48%   |
| 6.10.12-200.fc40.x86_64      | 78        | 3.43%   |
| 6.9.7-200.fc40.x86_64        | 69        | 3.04%   |
| 6.10.10-200.fc40.x86_64      | 67        | 2.95%   |
| 6.10.3-200.fc40.x86_64       | 64        | 2.82%   |
| 6.9.9-200.fc40.x86_64        | 56        | 2.46%   |
| 6.9.4-200.fc40.x86_64        | 53        | 2.33%   |
| 6.10.9-200.fc40.x86_64       | 53        | 2.33%   |
| 6.9.6-200.fc40.x86_64        | 49        | 2.16%   |
| 6.11.4-201.fc40.x86_64       | 49        | 2.16%   |
| 6.9.8-200.fc40.x86_64        | 48        | 2.11%   |
| 6.9.5-200.fc40.x86_64        | 47        | 2.07%   |
| 6.10.7-200.fc40.x86_64       | 47        | 2.07%   |
| 6.10.4-200.fc40.x86_64       | 42        | 1.85%   |
| 6.10.8-200.fc40.x86_64       | 41        | 1.8%    |
| 6.9.11-200.fc40.x86_64       | 38        | 1.67%   |
| 6.10.5-200.fc40.x86_64       | 30        | 1.32%   |
| 6.9.10-200.fc40.x86_64       | 27        | 1.19%   |
| 6.8.4-300.fc40.x86_64        | 13        | 0.57%   |
| 6.8.2-300.fc40.x86_64        | 12        | 0.53%   |
| 6.8.9-301.fsync.fc40.x86_64  | 11        | 0.48%   |
| 6.8.0-0.rc6.49.fc40.x86_64   | 11        | 0.48%   |
| 6.9.4-201.fsync.fc40.x86_64  | 10        | 0.44%   |
| 6.11.6-200.fc40.x86_64       | 10        | 0.44%   |
| 6.11.5-200.fc40.x86_64       | 9         | 0.4%    |
| 6.11.10-200.fc40.x86_64      | 8         | 0.35%   |
| 6.8.11-301.fsync.fc40.x86_64 | 5         | 0.22%   |
| 6.8.1-300.fc40.x86_64        | 5         | 0.22%   |
| 6.8.10-301.fsync.fc40.x86_64 | 4         | 0.18%   |
| 6.12.4-100.fc40.x86_64       | 4         | 0.18%   |
| 6.8.7-303.fsync.fc40.x86_64  | 3         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.8.5   | 251       | 11.04%  |
| 6.8.11  | 183       | 8.05%   |
| 6.8.7   | 148       | 6.51%   |
| 6.8.9   | 137       | 6.03%   |
| 6.10.6  | 124       | 5.46%   |
| 6.8.10  | 98        | 4.31%   |
| 6.9.12  | 83        | 3.65%   |
| 6.11.3  | 81        | 3.56%   |
| 6.8.8   | 80        | 3.52%   |
| 6.10.11 | 79        | 3.48%   |
| 6.10.12 | 78        | 3.43%   |
| 6.9.7   | 70        | 3.08%   |
| 6.10.10 | 70        | 3.08%   |
| 6.10.3  | 66        | 2.9%    |
| 6.9.4   | 64        | 2.82%   |
| 6.9.9   | 57        | 2.51%   |
| 6.9.6   | 53        | 2.33%   |
| 6.10.9  | 53        | 2.33%   |
| 6.11.4  | 50        | 2.2%    |
| 6.9.8   | 49        | 2.16%   |
| 6.9.5   | 48        | 2.11%   |
| 6.10.7  | 47        | 2.07%   |
| 6.10.8  | 43        | 1.89%   |
| 6.10.4  | 42        | 1.85%   |
| 6.9.11  | 39        | 1.72%   |
| 6.10.5  | 33        | 1.45%   |
| 6.9.10  | 27        | 1.19%   |
| 6.8.4   | 15        | 0.66%   |
| 6.8.0   | 14        | 0.62%   |
| 6.8.2   | 13        | 0.57%   |
| 6.11.6  | 10        | 0.44%   |
| 6.11.5  | 9         | 0.4%    |
| 6.11.10 | 8         | 0.35%   |
| 6.8.1   | 5         | 0.22%   |
| 6.8.12  | 4         | 0.18%   |
| 6.5.0   | 4         | 0.18%   |
| 6.12.4  | 4         | 0.18%   |
| 6.11.8  | 4         | 0.18%   |
| 6.11.0  | 4         | 0.18%   |
| 6.11.7  | 3         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.8     | 918       | 41.5%   |
| 6.10    | 621       | 28.07%  |
| 6.9     | 482       | 21.79%  |
| 6.11    | 170       | 7.69%   |
| 6.12    | 7         | 0.32%   |
| 6.5     | 6         | 0.27%   |
| 6.7     | 4         | 0.18%   |
| 6.6     | 2         | 0.09%   |
| 6.1     | 1         | 0.05%   |
| 5.15    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2092      | 99.76%  |
| aarch64 | 5         | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 1532      | 72.4%   |
| KDE6          | 358       | 16.92%  |
| KDE4          | 54        | 2.55%   |
| X-Cinnamon    | 29        | 1.37%   |
| Unknown       | 29        | 1.37%   |
| XFCE          | 28        | 1.32%   |
| GNOME Classic | 20        | 0.95%   |
| MATE          | 16        | 0.76%   |
| Budgie        | 10        | 0.47%   |
| Hyprland      | 8         | 0.38%   |
| sway          | 7         | 0.33%   |
| Cinnamon      | 7         | 0.33%   |
| i3            | 4         | 0.19%   |
| LXQt          | 3         | 0.14%   |
| KDE5          | 3         | 0.14%   |
| Deepin        | 3         | 0.14%   |
| bspwm         | 2         | 0.09%   |
| LXDE          | 1         | 0.05%   |
| KDE           | 1         | 0.05%   |
| awesome       | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 1851      | 87.64%  |
| X11     | 224       | 10.61%  |
| Unknown | 22        | 1.04%   |
| Tty     | 15        | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1355      | 64.07%  |
| GDM     | 450       | 21.28%  |
| SDDM    | 229       | 10.83%  |
| LightDM | 79        | 3.74%   |
| LXDM    | 2         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1142      | 54.2%   |
| en_GB   | 148       | 7.02%   |
| de_DE   | 99        | 4.7%    |
| pt_BR   | 86        | 4.08%   |
| ru_RU   | 83        | 3.94%   |
| it_IT   | 65        | 3.08%   |
| fr_FR   | 63        | 2.99%   |
| en_AU   | 36        | 1.71%   |
| es_MX   | 35        | 1.66%   |
| es_ES   | 33        | 1.57%   |
| en_CA   | 33        | 1.57%   |
| en_IN   | 32        | 1.52%   |
| pl_PL   | 26        | 1.23%   |
| es_CL   | 18        | 0.85%   |
| tr_TR   | 17        | 0.81%   |
| en_DK   | 11        | 0.52%   |
| nl_NL   | 10        | 0.47%   |
| es_CO   | 10        | 0.47%   |
| es_AR   | 10        | 0.47%   |
| en_IE   | 10        | 0.47%   |
| zh_CN   | 9         | 0.43%   |
| de_AT   | 8         | 0.38%   |
| da_DK   | 8         | 0.38%   |
| Unknown | 8         | 0.38%   |
| uk_UA   | 6         | 0.28%   |
| es_PE   | 6         | 0.28%   |
| cs_CZ   | 6         | 0.28%   |
| sv_SE   | 5         | 0.24%   |
| pt_PT   | 5         | 0.24%   |
| fr_CA   | 5         | 0.24%   |
| de_CH   | 5         | 0.24%   |
| zh_TW   | 4         | 0.19%   |
| ro_RO   | 4         | 0.19%   |
| nl_BE   | 4         | 0.19%   |
| nb_NO   | 4         | 0.19%   |
| fi_FI   | 4         | 0.19%   |
| ru_UA   | 3         | 0.14%   |
| ko_KR   | 3         | 0.14%   |
| es_UY   | 3         | 0.14%   |
| es_US   | 3         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1400      | 66.38%  |
| EFI  | 709       | 33.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 1830      | 86.89%  |
| Ext4    | 223       | 10.59%  |
| Tmpfs   | 29        | 1.38%   |
| Xfs     | 16        | 0.76%   |
| Overlay | 4         | 0.19%   |
| F2fs    | 2         | 0.09%   |
| Unknown | 2         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1331      | 63.08%  |
| GPT     | 762       | 36.11%  |
| MBR     | 17        | 0.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1959      | 93.15%  |
| Yes       | 144       | 6.85%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1826      | 86.75%  |
| Yes       | 279       | 13.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 529       | 25.23%  |
| Hewlett-Packard      | 312       | 14.88%  |
| ASUSTek Computer     | 291       | 13.88%  |
| Dell                 | 267       | 12.73%  |
| Acer                 | 145       | 6.91%   |
| Apple                | 128       | 6.1%    |
| MSI                  | 57        | 2.72%   |
| HUAWEI               | 44        | 2.1%    |
| Framework            | 28        | 1.34%   |
| Google               | 26        | 1.24%   |
| Toshiba              | 24        | 1.14%   |
| Samsung Electronics  | 23        | 1.1%    |
| Timi                 | 16        | 0.76%   |
| Alienware            | 13        | 0.62%   |
| Unknown              | 12        | 0.57%   |
| HONOR                | 10        | 0.48%   |
| Gigabyte Technology  | 10        | 0.48%   |
| LG Electronics       | 9         | 0.43%   |
| TUXEDO               | 8         | 0.38%   |
| Sony                 | 8         | 0.38%   |
| Fujitsu              | 8         | 0.38%   |
| XIAOMI               | 7         | 0.33%   |
| Chuwi                | 7         | 0.33%   |
| SLIMBOOK             | 6         | 0.29%   |
| Positivo             | 5         | 0.24%   |
| System76             | 4         | 0.19%   |
| Schenker             | 4         | 0.19%   |
| Razer                | 4         | 0.19%   |
| GPD                  | 4         | 0.19%   |
| Valve                | 3         | 0.14%   |
| PC Specialist        | 3         | 0.14%   |
| Packard Bell         | 3         | 0.14%   |
| Notebook             | 3         | 0.14%   |
| Monster              | 3         | 0.14%   |
| Medion               | 3         | 0.14%   |
| Intel Client Systems | 3         | 0.14%   |
| Insyde               | 3         | 0.14%   |
| Infinix              | 3         | 0.14%   |
| GPU Company          | 3         | 0.14%   |
| Avell                | 3         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 18        | 0.86%   |
| Apple MacBookPro9,2                         | 14        | 0.67%   |
| Apple MacBookPro14,1                        | 12        | 0.57%   |
| HP Notebook                                 | 11        | 0.52%   |
| HP EliteBook 840 G5                         | 10        | 0.48%   |
| Framework Laptop 16 (AMD Ryzen 7040 Series) | 10        | 0.48%   |
| HUAWEI BOM-WXX9                             | 9         | 0.43%   |
| Framework Laptop 13 (AMD Ryzen 7040Series)  | 9         | 0.43%   |
| Apple MacBookPro12,1                        | 9         | 0.43%   |
| Apple MacBookPro11,2                        | 9         | 0.43%   |
| Lenovo Yoga Pro 9 16IMH9 83DN               | 8         | 0.38%   |
| HP EliteBook 840 G6                         | 8         | 0.38%   |
| Apple MacBookPro8,1                         | 8         | 0.38%   |
| Apple MacBookPro11,1                        | 8         | 0.38%   |
| Acer Nitro ANV15-51                         | 7         | 0.33%   |
| Lenovo Legion 5 15ACH6H 82JU                | 6         | 0.29%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 6         | 0.29%   |
| HP Pavilion Notebook                        | 6         | 0.29%   |
| Dell XPS 15 9500                            | 6         | 0.29%   |
| Dell Latitude 7400                          | 6         | 0.29%   |
| Dell Latitude 5420                          | 6         | 0.29%   |
| Apple MacBookPro11,3                        | 6         | 0.29%   |
| Acer Nitro AN515-58                         | 6         | 0.29%   |
| HP Victus by Gaming Laptop 15-fa1xxx        | 5         | 0.24%   |
| HP Laptop 15-fc0xxx                         | 5         | 0.24%   |
| HP Laptop 15-bs0xx                          | 5         | 0.24%   |
| Dell XPS 15 9560                            | 5         | 0.24%   |
| Dell XPS 15 9530                            | 5         | 0.24%   |
| ASUS ROG Strix G513QY_G513QY                | 5         | 0.24%   |
| ASUS ASUS Zenbook 14 UX3405MA_UX3405MA      | 5         | 0.24%   |
| Apple MacBookPro10,1                        | 5         | 0.24%   |
| Apple MacBookAir7,2                         | 5         | 0.24%   |
| MSI Modern 15 A5M                           | 4         | 0.19%   |
| Lenovo Y520-15IKBN 80WK                     | 4         | 0.19%   |
| Lenovo ThinkPad P16s Gen 2 21K9CTO1WW       | 4         | 0.19%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 4         | 0.19%   |
| HP ProBook 450 15.6 inch G9 Notebook PC     | 4         | 0.19%   |
| HP Pavilion Gaming Laptop 15-cx0xxx         | 4         | 0.19%   |
| HP Pavilion 15                              | 4         | 0.19%   |
| Dell Latitude 5540                          | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 283       | 13.5%   |
| Lenovo IdeaPad     | 103       | 4.91%   |
| Dell Latitude      | 93        | 4.43%   |
| Acer Aspire        | 81        | 3.86%   |
| ASUS VivoBook      | 79        | 3.77%   |
| ASUS ROG           | 65        | 3.1%    |
| Dell Inspiron      | 60        | 2.86%   |
| ASUS ASUS          | 59        | 2.81%   |
| HP EliteBook       | 57        | 2.72%   |
| HP Pavilion        | 50        | 2.38%   |
| HP Laptop          | 50        | 2.38%   |
| Lenovo Legion      | 46        | 2.19%   |
| Dell XPS           | 43        | 2.05%   |
| HP ProBook         | 41        | 1.96%   |
| Dell Precision     | 39        | 1.86%   |
| Acer Nitro         | 33        | 1.57%   |
| Framework Laptop   | 28        | 1.34%   |
| Apple MacBookPro11 | 28        | 1.34%   |
| Lenovo Yoga        | 27        | 1.29%   |
| Lenovo ThinkBook   | 24        | 1.14%   |
| HP ZBook           | 20        | 0.95%   |
| HP Victus          | 19        | 0.91%   |
| Unknown            | 18        | 0.86%   |
| HP OMEN            | 17        | 0.81%   |
| ASUS Zenbook       | 17        | 0.81%   |
| Toshiba Satellite  | 16        | 0.76%   |
| Apple MacBookPro9  | 15        | 0.72%   |
| Dell Vostro        | 14        | 0.67%   |
| Apple MacBookPro14 | 14        | 0.67%   |
| Apple MacBookPro8  | 12        | 0.57%   |
| Acer Predator      | 12        | 0.57%   |
| HP Notebook        | 11        | 0.52%   |
| HP ENVY            | 11        | 0.52%   |
| MSI Modern         | 10        | 0.48%   |
| HUAWEI BOM-WXX9    | 9         | 0.43%   |
| Apple MacBookPro12 | 9         | 0.43%   |
| Acer Swift         | 9         | 0.43%   |
| ASUS TUF           | 8         | 0.38%   |
| Apple MacBookAir7  | 8         | 0.38%   |
| Lenovo LOQ         | 7         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2023    | 297       | 14.16%  |
| 2021    | 257       | 12.26%  |
| 2022    | 207       | 9.87%   |
| 2020    | 196       | 9.35%   |
| 2019    | 168       | 8.01%   |
| 2018    | 148       | 7.06%   |
| 2024    | 140       | 6.68%   |
| 2017    | 125       | 5.96%   |
| 2012    | 108       | 5.15%   |
| 2013    | 79        | 3.77%   |
| 2016    | 77        | 3.67%   |
| 2014    | 76        | 3.62%   |
| 2015    | 75        | 3.58%   |
| 2011    | 55        | 2.62%   |
| 2010    | 28        | 1.34%   |
| 2008    | 26        | 1.24%   |
| 2009    | 23        | 1.1%    |
| 2007    | 9         | 0.43%   |
| Unknown | 3         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2097      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1879      | 89.31%  |
| Enabled  | 225       | 10.69%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2067      | 98.57%  |
| Yes  | 30        | 1.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 520       | 24.71%  |
| 16.01-24.0  | 481       | 22.86%  |
| 8.01-16.0   | 458       | 21.77%  |
| 32.01-64.0  | 321       | 15.26%  |
| 3.01-4.0    | 134       | 6.37%   |
| 24.01-32.0  | 88        | 4.18%   |
| 64.01-256.0 | 71        | 3.37%   |
| 1.01-2.0    | 23        | 1.09%   |
| 2.01-3.0    | 8         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 793       | 36.03%  |
| 3.01-4.0   | 530       | 24.08%  |
| 2.01-3.0   | 479       | 21.76%  |
| 1.01-2.0   | 180       | 8.18%   |
| 8.01-16.0  | 171       | 7.77%   |
| 16.01-24.0 | 24        | 1.09%   |
| 0.51-1.0   | 16        | 0.73%   |
| 24.01-32.0 | 7         | 0.32%   |
| 32.01-64.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1558      | 73.8%   |
| 2      | 482       | 22.83%  |
| 3      | 49        | 2.32%   |
| 4      | 13        | 0.62%   |
| 0      | 6         | 0.28%   |
| 7      | 2         | 0.09%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1789      | 85.27%  |
| Yes       | 309       | 14.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1489      | 70.74%  |
| No        | 616       | 29.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2011      | 95.9%   |
| No        | 86        | 4.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1853      | 88.2%   |
| No        | 248       | 11.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 389       | 18.42%  |
| Germany     | 159       | 7.53%   |
| Brazil      | 126       | 5.97%   |
| Russia      | 115       | 5.45%   |
| Italy       | 109       | 5.16%   |
| India       | 108       | 5.11%   |
| UK          | 84        | 3.98%   |
| France      | 80        | 3.79%   |
| Mexico      | 56        | 2.65%   |
| Poland      | 54        | 2.56%   |
| Canada      | 53        | 2.51%   |
| Spain       | 46        | 2.18%   |
| Netherlands | 43        | 2.04%   |
| Turkey      | 39        | 1.85%   |
| Australia   | 35        | 1.66%   |
| Chile       | 31        | 1.47%   |
| Sweden      | 29        | 1.37%   |
| Switzerland | 22        | 1.04%   |
| Norway      | 21        | 0.99%   |
| Indonesia   | 21        | 0.99%   |
| Austria     | 21        | 0.99%   |
| Denmark     | 19        | 0.9%    |
| Argentina   | 19        | 0.9%    |
| Romania     | 18        | 0.85%   |
| Egypt       | 18        | 0.85%   |
| Portugal    | 16        | 0.76%   |
| Czechia     | 16        | 0.76%   |
| Colombia    | 16        | 0.76%   |
| Philippines | 14        | 0.66%   |
| Belgium     | 14        | 0.66%   |
| Israel      | 13        | 0.62%   |
| Serbia      | 12        | 0.57%   |
| China       | 11        | 0.52%   |
| Bulgaria    | 11        | 0.52%   |
| Vietnam     | 10        | 0.47%   |
| Ireland     | 10        | 0.47%   |
| Finland     | 10        | 0.47%   |
| Peru        | 9         | 0.43%   |
| Hungary     | 9         | 0.43%   |
| Taiwan      | 8         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Berlin         | 30        | 1.4%    |
| Moscow         | 23        | 1.07%   |
| Milan          | 21        | 0.98%   |
| St Petersburg  | 18        | 0.84%   |
| Santiago       | 18        | 0.84%   |
| Mexico City    | 17        | 0.79%   |
| Istanbul       | 17        | 0.79%   |
| Delhi          | 17        | 0.79%   |
| Sao Paulo      | 14        | 0.65%   |
| Paris          | 14        | 0.65%   |
| Munich         | 13        | 0.6%    |
| Sydney         | 12        | 0.56%   |
| Bengaluru      | 11        | 0.51%   |
| Amsterdam      | 11        | 0.51%   |
| Rome           | 10        | 0.47%   |
| Hyderabad      | 10        | 0.47%   |
| Vienna         | 9         | 0.42%   |
| Dublin         | 9         | 0.42%   |
| Bogotá        | 9         | 0.42%   |
| Warsaw         | 8         | 0.37%   |
| Stockholm      | 8         | 0.37%   |
| Rio de Janeiro | 8         | 0.37%   |
| Mumbai         | 8         | 0.37%   |
| Montreal       | 8         | 0.37%   |
| Madrid         | 8         | 0.37%   |
| Jacksonville   | 8         | 0.37%   |
| Cairo          | 8         | 0.37%   |
| Alexandria     | 8         | 0.37%   |
| Oslo           | 7         | 0.33%   |
| Novosibirsk    | 7         | 0.33%   |
| Montevideo     | 7         | 0.33%   |
| Melbourne      | 7         | 0.33%   |
| Lima           | 7         | 0.33%   |
| Helsinki       | 7         | 0.33%   |
| Ankara         | 7         | 0.33%   |
| Zurich         | 6         | 0.28%   |
| Zagreb         | 6         | 0.28%   |
| New York       | 6         | 0.28%   |
| Los Angeles    | 6         | 0.28%   |
| Lisbon         | 6         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 480       | 564    | 18.37%  |
| Sandisk                        | 337       | 380    | 12.9%   |
| SK hynix                       | 203       | 225    | 7.77%   |
| Micron Technology              | 154       | 167    | 5.89%   |
| Seagate                        | 130       | 142    | 4.98%   |
| Unknown                        | 119       | 133    | 4.55%   |
| Kingston                       | 115       | 124    | 4.4%    |
| WDC                            | 98        | 109    | 3.75%   |
| Toshiba                        | 97        | 108    | 3.71%   |
| Intel                          | 92        | 107    | 3.52%   |
| Apple                          | 74        | 103    | 2.83%   |
| KIOXIA                         | 70        | 85     | 2.68%   |
| Micron/Crucial Technology      | 54        | 59     | 2.07%   |
| Phison Electronics             | 47        | 51     | 1.8%    |
| Crucial                        | 45        | 47     | 1.72%   |
| HGST                           | 38        | 39     | 1.45%   |
| Kingston Technology Company    | 34        | 34     | 1.3%    |
| China                          | 30        | 33     | 1.15%   |
| ADATA Technology               | 25        | 27     | 0.96%   |
| Hitachi                        | 24        | 25     | 0.92%   |
| MAXIO Technology (Hangzhou)    | 22        | 23     | 0.84%   |
| A-DATA Technology              | 22        | 28     | 0.84%   |
| Shenzhen Longsys Electronics   | 19        | 21     | 0.73%   |
| Silicon Motion                 | 14        | 15     | 0.54%   |
| Unknown                        | 13        | 13     | 0.5%    |
| Union Memory (Shenzhen)        | 12        | 14     | 0.46%   |
| Realtek Semiconductor          | 11        | 13     | 0.42%   |
| Solid State Storage Technology | 10        | 13     | 0.38%   |
| PNY                            | 10        | 10     | 0.38%   |
| Transcend                      | 9         | 10     | 0.34%   |
| SPCC                           | 8         | 8      | 0.31%   |
| LITEON                         | 8         | 8      | 0.31%   |
| Intenso                        | 8         | 8      | 0.31%   |
| Yangtze Memory Technologies    | 7         | 11     | 0.27%   |
| Solid State Storage            | 7         | 7      | 0.27%   |
| Phison                         | 7         | 9      | 0.27%   |
| Union Memory                   | 6         | 6      | 0.23%   |
| Netac                          | 6         | 7      | 0.23%   |
| Lexar                          | 6         | 8      | 0.23%   |
| JMicron Technology             | 6         | 8      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 115       | 4.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 95        | 3.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 40        | 1.49%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 40        | 1.49%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 35        | 1.31%   |
| Seagate ST1000LM035-1RK172 1TB                       | 33        | 1.23%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 29        | 1.08%   |
| Intel SSD 660P Series 1024GB                         | 27        | 1.01%   |
| Unknown MMC Card  64GB                               | 24        | 0.9%    |
| Unknown MMC Card  32GB                               | 24        | 0.9%    |
| Kingston SA400S37240G 240GB SSD                      | 24        | 0.9%    |
| Intel SSDPEKNU512GZ 512GB                            | 23        | 0.86%   |
| Unknown MMC Card  128GB                              | 22        | 0.82%   |
| Phison PS5013 E13 NVMe Controller 512GB              | 22        | 0.82%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 20        | 0.75%   |
| HGST HTS721010A9E630 1TB                             | 18        | 0.67%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 17        | 0.64%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 17        | 0.64%   |
| Kingston SA400S37480G 480GB SSD                      | 16        | 0.6%    |
| Toshiba MQ01ABD100 1TB                               | 15        | 0.56%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1TB                 | 15        | 0.56%   |
| Sandisk WD PC SN560 SDDPNQE-1T00-1102 1024GB         | 15        | 0.56%   |
| Sandisk WD Black SN850 2TB                           | 15        | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 14        | 0.52%   |
| SK hynix BC511 512GB                                 | 13        | 0.49%   |
| Micron 2450_MTFDKBA512TFK 512GB                      | 13        | 0.49%   |
| Apple S3X NVMe Controller 500GB                      | 13        | 0.49%   |
| Unknown                                              | 13        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 12        | 0.45%   |
| Phison E12 NVMe Controller 480GB                     | 12        | 0.45%   |
| Samsung MZAL4512HBLU-00BL2 512GB                     | 11        | 0.41%   |
| Micron CT1000P3PSSD8 1TB                             | 11        | 0.41%   |
| Micron 2400_MTFDKBA512QFM 512GB                      | 11        | 0.41%   |
| Unknown NVMe SSD Drive 512GB                         | 10        | 0.37%   |
| Micron MTFDKBA1T0QFM-1BD1AABGB 1024GB                | 10        | 0.37%   |
| KIOXIA KBG50ZNV512G 512GB                            | 10        | 0.37%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 10        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                         | 10        | 0.37%   |
| Toshiba MQ04ABF100 1TB                               | 9         | 0.34%   |
| Sandisk WD_BLACK SN850X 2000GB                       | 9         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 132    | 39.31%  |
| WDC                 | 63        | 70     | 19.81%  |
| Toshiba             | 51        | 57     | 16.04%  |
| HGST                | 38        | 39     | 11.95%  |
| Hitachi             | 24        | 25     | 7.55%   |
| JMicron Technology  | 4         | 6      | 1.26%   |
| Unknown             | 3         | 3      | 0.94%   |
| Samsung Electronics | 2         | 3      | 0.63%   |
| USB3.0              | 1         | 2      | 0.31%   |
| TO Exter            | 1         | 1      | 0.31%   |
| SAGE                | 1         | 1      | 0.31%   |
| SABRENT             | 1         | 1      | 0.31%   |
| LaCie               | 1         | 1      | 0.31%   |
| External            | 1         | 1      | 0.31%   |
| ASMT                | 1         | 1      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 122       | 144    | 19.33%  |
| Kingston            | 78        | 86     | 12.36%  |
| SanDisk             | 58        | 65     | 9.19%   |
| Apple               | 50        | 53     | 7.92%   |
| Crucial             | 45        | 47     | 7.13%   |
| WDC                 | 34        | 38     | 5.39%   |
| China               | 30        | 33     | 4.75%   |
| SK hynix            | 21        | 25     | 3.33%   |
| A-DATA Technology   | 19        | 22     | 3.01%   |
| Intel               | 16        | 18     | 2.54%   |
| Micron Technology   | 13        | 14     | 2.06%   |
| PNY                 | 10        | 10     | 1.58%   |
| Transcend           | 9         | 10     | 1.43%   |
| SPCC                | 8         | 8      | 1.27%   |
| LITEON              | 8         | 8      | 1.27%   |
| Intenso             | 8         | 8      | 1.27%   |
| Toshiba             | 6         | 6      | 0.95%   |
| Verbatim            | 5         | 6      | 0.79%   |
| Netac               | 5         | 6      | 0.79%   |
| Lexar               | 5         | 7      | 0.79%   |
| KingSpec            | 5         | 5      | 0.79%   |
| Hewlett-Packard     | 5         | 6      | 0.79%   |
| Fanxiang            | 5         | 5      | 0.79%   |
| Corsair             | 5         | 6      | 0.79%   |
| Patriot             | 4         | 5      | 0.63%   |
| Apacer              | 4         | 4      | 0.63%   |
| Plextor             | 3         | 5      | 0.48%   |
| GOODRAM             | 3         | 3      | 0.48%   |
| FORESEE             | 3         | 3      | 0.48%   |
| XrayDisk            | 2         | 2      | 0.32%   |
| Wibtek              | 2         | 3      | 0.32%   |
| Team                | 2         | 2      | 0.32%   |
| HUSKY               | 2         | 2      | 0.32%   |
| Gigabyte Technology | 2         | 2      | 0.32%   |
| BIWIN               | 2         | 2      | 0.32%   |
| Unknown             | 2         | 2      | 0.32%   |
| X12                 | 1         | 1      | 0.16%   |
| USB3.0              | 1         | 1      | 0.16%   |
| Teclast             | 1         | 2      | 0.16%   |
| T-FORCE             | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1392      | 1752   | 57.43%  |
| SSD     | 586       | 703    | 24.17%  |
| HDD     | 310       | 344    | 12.79%  |
| MMC     | 94        | 106    | 3.88%   |
| Unknown | 42        | 49     | 1.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1391      | 1739   | 58.97%  |
| SATA | 791       | 1006   | 33.53%  |
| MMC  | 94        | 106    | 3.98%   |
| SAS  | 83        | 103    | 3.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 531       | 656    | 59.8%   |
| 0.51-1.0   | 292       | 319    | 32.88%  |
| 1.01-2.0   | 49        | 54     | 5.52%   |
| 3.01-4.0   | 6         | 7      | 0.68%   |
| 4.01-10.0  | 6         | 7      | 0.68%   |
| 10.01-20.0 | 4         | 4      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 526       | 24.59%  |
| 251-500        | 409       | 19.12%  |
| 1001-2000      | 341       | 15.94%  |
| 101-250        | 281       | 13.14%  |
| 1-20           | 189       | 8.84%   |
| Unknown        | 166       | 7.76%   |
| More than 3000 | 83        | 3.88%   |
| 51-100         | 70        | 3.27%   |
| 2001-3000      | 52        | 2.43%   |
| 21-50          | 22        | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 802       | 36.79%  |
| 21-50          | 366       | 16.79%  |
| 101-250        | 259       | 11.88%  |
| 51-100         | 244       | 11.19%  |
| Unknown        | 166       | 7.61%   |
| 251-500        | 156       | 7.16%   |
| 501-1000       | 118       | 5.41%   |
| 1001-2000      | 48        | 2.2%    |
| 2001-3000      | 11        | 0.5%    |
| More than 3000 | 9         | 0.41%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                            | Notebooks | Drives | Percent |
|------------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB  | 3         | 3      | 6.38%   |
| Seagate ST1000LM049-2GH172 1TB                                   | 2         | 2      | 4.26%   |
| Seagate ST1000LM035-1RK172 1TB                                   | 2         | 2      | 4.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                               | 2         | 2      | 4.26%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2         | 2      | 4.26%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                 | 1         | 1      | 2.13%   |
| WDC WD3200BEKT-60KA9T0 320GB                                     | 1         | 1      | 2.13%   |
| WDC WD10SPZX-60Z10T1 1TB                                         | 1         | 1      | 2.13%   |
| WDC WD10SPZX-24Z10T0 1TB                                         | 1         | 1      | 2.13%   |
| WDC WD10JPCX-24UE4T0 1TB                                         | 1         | 1      | 2.13%   |
| Transcend TS480GMTS420S 480GB SSD                                | 1         | 1      | 2.13%   |
| Transcend TS240GMTS420S 240GB SSD                                | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD100M 1TB                                          | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD100 1TB                                           | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD075 752GB                                         | 1         | 1      | 2.13%   |
| SK hynix PC300 NVMe Solid State Drive 1TB                        | 1         | 1      | 2.13%   |
| Seagate ST9500325ASG 500GB                                       | 1         | 1      | 2.13%   |
| Seagate ST9320325AS 320GB                                        | 1         | 1      | 2.13%   |
| Seagate ST500VT000-1DK142 500GB                                  | 1         | 1      | 2.13%   |
| Seagate ST2000LX001-1RG174 2TB                                   | 1         | 1      | 2.13%   |
| Seagate ST2000LM015-2E8174 2TB                                   | 1         | 1      | 2.13%   |
| SanDisk SSD PLUS 480GB                                           | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 870 QVO 1TB                              | 1         | 1      | 2.13%   |
| Micron Technology 1100 SATA 256GB SSD                            | 1         | 1      | 2.13%   |
| Intenso SSD Sata III 240GB                                       | 1         | 1      | 2.13%   |
| Hitachi HTS725025A9A364 250GB                                    | 1         | 1      | 2.13%   |
| Hitachi HTS723216L9SA60 160GB                                    | 1         | 1      | 2.13%   |
| Hitachi HTS722080K9A300 80GB                                     | 1         | 1      | 2.13%   |
| Hitachi HTS547575A9E384 752GB                                    | 1         | 1      | 2.13%   |
| Hitachi HTS542520K9SA00 200GB                                    | 1         | 1      | 2.13%   |
| Hitachi HTS541616J9SA00 160GB                                    | 1         | 1      | 2.13%   |
| HGST HTS725050A7E630 500GB                                       | 1         | 1      | 2.13%   |
| HGST HTS721010A9E630 1TB                                         | 1         | 1      | 2.13%   |
| HGST HTS541075A9E680 752GB                                       | 1         | 1      | 2.13%   |
| HGST HTS541010A9E680 1TB                                         | 1         | 1      | 2.13%   |
| Hewlett-Packard SSD S700 1TB                                     | 1         | 1      | 2.13%   |
| Crucial CT525MX300SSD1 528GB                                     | 1         | 1      | 2.13%   |
| Crucial CT275MX300SSD1 275GB                                     | 1         | 1      | 2.13%   |
| China SSD 1TB                                                    | 1         | 1      | 2.13%   |
| China SATA SSD 20GB                                              | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 23.4%   |
| Samsung Electronics | 6         | 6      | 12.77%  |
| Hitachi             | 6         | 6      | 12.77%  |
| WDC                 | 5         | 5      | 10.64%  |
| HGST                | 4         | 4      | 8.51%   |
| Toshiba             | 3         | 3      | 6.38%   |
| China               | 3         | 3      | 6.38%   |
| Transcend           | 2         | 2      | 4.26%   |
| Crucial             | 2         | 2      | 4.26%   |
| SK hynix            | 1         | 1      | 2.13%   |
| SanDisk             | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 11     | 39.29%  |
| Hitachi | 6         | 6      | 21.43%  |
| WDC     | 4         | 4      | 14.29%  |
| HGST    | 4         | 4      | 14.29%  |
| Toshiba | 3         | 3      | 10.71%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 28     | 62.22%  |
| SSD  | 11        | 13     | 24.44%  |
| NVMe | 6         | 6      | 13.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB | 1         | 1      | 50%     |
| Apple SSD SM0256F 256GB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 50%     |
| Apple  | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1422      | 1998   | 65.89%  |
| Works    | 690       | 907    | 31.97%  |
| Malfunc  | 44        | 47     | 2.04%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1054      | 38.74%  |
| Samsung Electronics                     | 406       | 14.92%  |
| SanDisk                                 | 285       | 10.47%  |
| SK hynix                                | 182       | 6.69%   |
| AMD                                     | 154       | 5.66%   |
| Micron Technology                       | 140       | 5.15%   |
| Kingston Technology Company             | 71        | 2.61%   |
| KIOXIA                                  | 69        | 2.54%   |
| Phison Electronics                      | 54        | 1.98%   |
| Micron/Crucial Technology               | 54        | 1.98%   |
| Toshiba America Info Systems            | 41        | 1.51%   |
| ADATA Technology                        | 28        | 1.03%   |
| MAXIO Technology (Hangzhou)             | 22        | 0.81%   |
| Apple                                   | 21        | 0.77%   |
| Shenzhen Longsys Electronics            | 20        | 0.74%   |
| Solid State Storage Technology          | 17        | 0.62%   |
| Silicon Motion                          | 14        | 0.51%   |
| Solidigm                                | 12        | 0.44%   |
| Realtek Semiconductor                   | 11        | 0.4%    |
| Union Memory (Shenzhen)                 | 10        | 0.37%   |
| Nvidia                                  | 10        | 0.37%   |
| Shenzhen Unionmemory Information System | 8         | 0.29%   |
| Yangtze Memory Technologies             | 7         | 0.26%   |
| Biwin Storage Technology                | 6         | 0.22%   |
| Shenzhen Shichuangyi Electronics        | 3         | 0.11%   |
| Seagate Technology                      | 3         | 0.11%   |
| Lenovo                                  | 3         | 0.11%   |
| INNOGRIT                                | 3         | 0.11%   |
| Transcend                               | 2         | 0.07%   |
| Marvell Technology Group                | 2         | 0.07%   |
| Lite-On Technology                      | 2         | 0.07%   |
| ASMedia Technology                      | 2         | 0.07%   |
| Unknown                                 | 2         | 0.07%   |
| Ramaxel Technology(Shenzhen) Limited    | 1         | 0.04%   |
| Netac Technology                        | 1         | 0.04%   |
| Hosin Global Electronics                | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 144       | 5.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 127       | 4.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 125       | 4.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 118       | 4.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 104       | 3.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 96        | 3.38%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 80        | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 78        | 2.75%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 65        | 2.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 61        | 2.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 58        | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 53        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 53        | 1.87%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 48        | 1.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 42        | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 40        | 1.41%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 40        | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 39        | 1.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 39        | 1.37%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 37        | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.3%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 36        | 1.27%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 35        | 1.23%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 34        | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 33        | 1.16%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 32        | 1.13%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 30        | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                          | 30        | 1.06%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 29        | 1.02%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 27        | 0.95%   |
| Intel SSD 660P Series                                                          | 27        | 0.95%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 25        | 0.88%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 24        | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 23        | 0.81%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 22        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.77%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 21        | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 20        | 0.7%    |
| Sandisk WD Black SN850X NVMe SSD                                               | 19        | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 19        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 1388      | 52.06%  |
| SATA | 980       | 36.76%  |
| RAID | 276       | 10.35%  |
| IDE  | 22        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 1602      | 76.39%  |
| AMD      | 490       | 23.37%  |
| ARM      | 2         | 0.1%    |
| Unknown  | 2         | 0.1%    |
| Qualcomm | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 44        | 2.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 32        | 1.52%   |
| Intel Core Ultra 7 155H                    | 28        | 1.33%   |
| Intel 12th Gen Core i7-12700H              | 28        | 1.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 26        | 1.24%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 26        | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 25        | 1.19%   |
| AMD Ryzen 5 5500U with Radeon Graphics     | 25        | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 24        | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 24        | 1.14%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 23        | 1.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz          | 22        | 1.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 22        | 1.05%   |
| Intel 12th Gen Core i5-1235U               | 22        | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 22        | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 21        | 1%      |
| Intel Core i5-6300U CPU @ 2.40GHz          | 21        | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 20        | 0.95%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 20        | 0.95%   |
| Intel 13th Gen Core i7-13700H              | 20        | 0.95%   |
| Intel 12th Gen Core i5-12450H              | 20        | 0.95%   |
| AMD Ryzen 5 5600H with Radeon Graphics     | 20        | 0.95%   |
| Intel Core Ultra 9 185H                    | 19        | 0.9%    |
| Intel Core i5-8365U CPU @ 1.60GHz          | 18        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 18        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 16        | 0.76%   |
| Intel 13th Gen Core i7-13620H              | 16        | 0.76%   |
| Intel 12th Gen Core i7-1255U               | 16        | 0.76%   |
| Intel Core i7-8665U CPU @ 1.90GHz          | 15        | 0.71%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 15        | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 15        | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz         | 15        | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 14        | 0.67%   |
| Intel 12th Gen Core i5-12500H              | 14        | 0.67%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 14        | 0.67%   |
| AMD Ryzen 5 7520U with Radeon Graphics     | 14        | 0.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz          | 13        | 0.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 13        | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 13        | 0.62%   |
| Intel 13th Gen Core i5-1335U               | 13        | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 487       | 23.21%  |
| Intel Core i5           | 418       | 19.92%  |
| Intel Core i7           | 415       | 19.78%  |
| AMD Ryzen 7             | 191       | 9.1%    |
| AMD Ryzen 5             | 127       | 6.05%   |
| Intel Core i3           | 80        | 3.81%   |
| Intel Core              | 61        | 2.91%   |
| AMD Ryzen 9             | 43        | 2.05%   |
| Intel Core 2 Duo        | 41        | 1.95%   |
| Intel Celeron           | 37        | 1.76%   |
| AMD Ryzen 7 PRO         | 30        | 1.43%   |
| Intel Pentium           | 25        | 1.19%   |
| AMD Ryzen 3             | 25        | 1.19%   |
| AMD Ryzen 5 PRO         | 22        | 1.05%   |
| Intel Atom              | 18        | 0.86%   |
| Intel Core i9           | 14        | 0.67%   |
| AMD A4                  | 9         | 0.43%   |
| Intel Xeon              | 8         | 0.38%   |
| AMD A8                  | 7         | 0.33%   |
| AMD A6                  | 7         | 0.33%   |
| Intel Pentium Dual-Core | 5         | 0.24%   |
| Intel Pentium Silver    | 4         | 0.19%   |
| AMD A10                 | 4         | 0.19%   |
| Intel Core m3           | 3         | 0.14%   |
| Intel Pentium Gold      | 2         | 0.1%    |
| Intel Core m5           | 2         | 0.1%    |
| Intel Core M            | 2         | 0.1%    |
| AMD E2                  | 2         | 0.1%    |
| AMD Athlon              | 2         | 0.1%    |
| AMD Ryzen 3 PRO         | 1         | 0.05%   |
| AMD GX                  | 1         | 0.05%   |
| AMD E1                  | 1         | 0.05%   |
| AMD E                   | 1         | 0.05%   |
| AMD Athlon Neo X2       | 1         | 0.05%   |
| AMD Athlon II           | 1         | 0.05%   |
| AMD A12                 | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 668       | 31.86%  |
| 2      | 554       | 26.42%  |
| 8      | 326       | 15.55%  |
| 6      | 224       | 10.68%  |
| 10     | 92        | 4.39%   |
| 14     | 86        | 4.1%    |
| 16     | 67        | 3.2%    |
| 12     | 60        | 2.86%   |
| 24     | 16        | 0.76%   |
| 1      | 2         | 0.1%    |
| 20     | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2094      | 99.81%  |
| 2      | 4         | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1873      | 89.28%  |
| 1      | 225       | 10.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2092      | 99.76%  |
| 64-bit         | 5         | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2095      | 99.86%  |
| 0x0a50000c | 2         | 0.1%    |
| 0x206a7    | 1         | 0.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 484       | 23.07%  |
| KabyLake          | 400       | 19.07%  |
| TigerLake         | 132       | 6.29%   |
| Alderlake Hybrid  | 126       | 6.01%   |
| Zen 3             | 110       | 5.24%   |
| Haswell           | 110       | 5.24%   |
| IvyBridge         | 108       | 5.15%   |
| Skylake           | 98        | 4.67%   |
| SandyBridge       | 61        | 2.91%   |
| CometLake         | 56        | 2.67%   |
| Broadwell         | 56        | 2.67%   |
| Zen 2             | 52        | 2.48%   |
| Icelake           | 42        | 2%      |
| Penryn            | 39        | 1.86%   |
| Zen+              | 38        | 1.81%   |
| Silvermont        | 33        | 1.57%   |
| Meteorlake Hybrid | 33        | 1.57%   |
| Westmere          | 22        | 1.05%   |
| Zen               | 17        | 0.81%   |
| Goldmont plus     | 16        | 0.76%   |
| Excavator         | 15        | 0.71%   |
| Puma              | 8         | 0.38%   |
| Core              | 8         | 0.38%   |
| Gracemont         | 7         | 0.33%   |
| Jaguar            | 5         | 0.24%   |
| Goldmont          | 5         | 0.24%   |
| Tremont           | 4         | 0.19%   |
| Nehalem           | 4         | 0.19%   |
| Piledriver        | 3         | 0.14%   |
| K10 Llano         | 2         | 0.1%    |
| K8 Hammer         | 1         | 0.05%   |
| K10               | 1         | 0.05%   |
| Bonnell           | 1         | 0.05%   |
| Bobcat            | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1504      | 53.89%  |
| Nvidia | 738       | 26.44%  |
| AMD    | 549       | 19.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 117       | 4.11%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 100       | 3.51%   |
| Intel UHD Graphics 620                                                    | 86        | 3.02%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 79        | 2.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 78        | 2.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 68        | 2.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 61        | 2.14%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 61        | 2.14%   |
| AMD Rembrandt [Radeon 680M]                                               | 61        | 2.14%   |
| AMD Phoenix1                                                              | 59        | 2.07%   |
| AMD Lucienne                                                              | 57        | 2%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 55        | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 54        | 1.9%    |
| Intel HD Graphics 620                                                     | 54        | 1.9%    |
| Intel Meteor Lake-P [Intel Arc Graphics]                                  | 53        | 1.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 52        | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 51        | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 50        | 1.76%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 49        | 1.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 47        | 1.65%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 44        | 1.55%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 42        | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 42        | 1.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 40        | 1.4%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 40        | 1.4%    |
| Intel HD Graphics 5500                                                    | 35        | 1.23%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 35        | 1.23%   |
| Intel HD Graphics 630                                                     | 33        | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 33        | 1.16%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 29        | 1.02%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                           | 29        | 1.02%   |
| Intel HD Graphics 530                                                     | 28        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 27        | 0.95%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 27        | 0.95%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 26        | 0.91%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 23        | 0.81%   |
| AMD Barcelo                                                               | 23        | 0.81%   |
| Intel Raptor Lake-S UHD Graphics                                          | 22        | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 22        | 0.77%   |
| AMD Phoenix3                                                              | 22        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 913       | 43.54%  |
| Intel + Nvidia           | 524       | 24.99%  |
| 1 x AMD                  | 342       | 16.31%  |
| AMD + Nvidia             | 112       | 5.34%   |
| 1 x Nvidia               | 96        | 4.58%   |
| Intel + AMD              | 50        | 2.38%   |
| 2 x AMD                  | 44        | 2.1%    |
| Other                    | 8         | 0.38%   |
| 2 x Intel                | 5         | 0.24%   |
| 2 x Nvidia               | 2         | 0.1%    |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1614      | 76.57%  |
| Proprietary | 278       | 13.19%  |
| Unknown     | 216       | 10.25%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1789      | 84.91%  |
| 0.01-0.5   | 105       | 4.98%   |
| 3.01-4.0   | 63        | 2.99%   |
| 1.01-2.0   | 58        | 2.75%   |
| 0.51-1.0   | 31        | 1.47%   |
| 7.01-8.0   | 30        | 1.42%   |
| 5.01-6.0   | 24        | 1.14%   |
| 8.01-16.0  | 6         | 0.28%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 430       | 17.64%  |
| AU Optronics            | 411       | 16.86%  |
| Chimei Innolux          | 341       | 13.99%  |
| LG Display              | 233       | 9.56%   |
| Samsung Electronics     | 225       | 9.23%   |
| Apple                   | 122       | 5.01%   |
| Sharp                   | 65        | 2.67%   |
| Dell                    | 65        | 2.67%   |
| Goldstar                | 58        | 2.38%   |
| CSO                     | 58        | 2.38%   |
| PANDA                   | 41        | 1.68%   |
| Lenovo                  | 38        | 1.56%   |
| InfoVision              | 37        | 1.52%   |
| Philips                 | 36        | 1.48%   |
| Hewlett-Packard         | 30        | 1.23%   |
| Chi Mei Optoelectronics | 21        | 0.86%   |
| Acer                    | 20        | 0.82%   |
| TMX                     | 17        | 0.7%    |
| AOC                     | 17        | 0.7%    |
| CSW                     | 15        | 0.62%   |
| ASUSTek Computer        | 15        | 0.62%   |
| Iiyama                  | 12        | 0.49%   |
| Ancor Communications    | 11        | 0.45%   |
| BenQ                    | 9         | 0.37%   |
| KDB                     | 6         | 0.25%   |
| HKC                     | 6         | 0.25%   |
| ViewSonic               | 5         | 0.21%   |
| Pixio                   | 4         | 0.16%   |
| MSI                     | 4         | 0.16%   |
| Mi                      | 4         | 0.16%   |
| JDI                     | 4         | 0.16%   |
| InnoLux Display         | 4         | 0.16%   |
| HUAWEI                  | 4         | 0.16%   |
| Valve                   | 3         | 0.12%   |
| Sony                    | 3         | 0.12%   |
| Panasonic               | 3         | 0.12%   |
| Gigabyte Technology     | 3         | 0.12%   |
| Eizo                    | 3         | 0.12%   |
| VXN                     | 2         | 0.08%   |
| VIE                     | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 26        | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 21        | 0.85%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 17        | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.69%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 16        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.6%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 15        | 0.6%    |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 14        | 0.56%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 12        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.44%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 11        | 0.44%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 10        | 0.4%    |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                    | 10        | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 9         | 0.36%   |
| BOE LCD Monitor BOE0BC9 2560x1600 345x215mm 16.0-inch                    | 9         | 0.36%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.36%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 9         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch    | 8         | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch         | 8         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.32%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 8         | 0.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 8         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch    | 7         | 0.28%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 7         | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.28%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 7         | 0.28%   |
| CSW LCD Monitor CSW1640 3200x2000 344x215mm 16.0-inch                    | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 7         | 0.28%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 7         | 0.28%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 7         | 0.28%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 7         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1076      | 46.2%   |
| 1366x768 (WXGA)    | 312       | 13.4%   |
| 1920x1200 (WUXGA)  | 142       | 6.1%    |
| 2560x1600          | 125       | 5.37%   |
| 3840x2160 (4K)     | 117       | 5.02%   |
| 2880x1800          | 112       | 4.81%   |
| 2560x1440 (QHD)    | 96        | 4.12%   |
| 1600x900 (HD+)     | 52        | 2.23%   |
| 1280x800 (WXGA)    | 44        | 1.89%   |
| 3440x1440          | 32        | 1.37%   |
| 3200x2000          | 27        | 1.16%   |
| 3840x2400          | 24        | 1.03%   |
| 1440x900 (WXGA+)   | 21        | 0.9%    |
| 2560x1080          | 20        | 0.86%   |
| 2256x1504          | 17        | 0.73%   |
| 1680x1050 (WSXGA+) | 12        | 0.52%   |
| 2160x1440          | 11        | 0.47%   |
| 2240x1400          | 8         | 0.34%   |
| Unknown            | 8         | 0.34%   |
| 3456x2160          | 7         | 0.3%    |
| 3200x1800 (QHD+)   | 7         | 0.3%    |
| 3072x1920          | 6         | 0.26%   |
| 2880x1620          | 6         | 0.26%   |
| 3840x1080          | 5         | 0.21%   |
| 3840x1100          | 4         | 0.17%   |
| 1920x1280          | 4         | 0.17%   |
| 800x1280           | 3         | 0.13%   |
| 3000x2000          | 3         | 0.13%   |
| 2880x1920          | 3         | 0.13%   |
| 2304x1440          | 3         | 0.13%   |
| 1360x768           | 3         | 0.13%   |
| 1280x1024 (SXGA)   | 3         | 0.13%   |
| 3840x2560          | 2         | 0.09%   |
| 3840x1600          | 2         | 0.09%   |
| 2048x1280          | 2         | 0.09%   |
| 3120x2080          | 1         | 0.04%   |
| 2944x1840          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2400x1600          | 1         | 0.04%   |
| 2160x1350          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 918       | 37.64%  |
| 14      | 367       | 15.05%  |
| 13      | 328       | 13.45%  |
| 16      | 188       | 7.71%   |
| 17      | 118       | 4.84%   |
| 27      | 96        | 3.94%   |
| 24      | 78        | 3.2%    |
| 31      | 49        | 2.01%   |
| 34      | 44        | 1.8%    |
| 12      | 43        | 1.76%   |
| 23      | 35        | 1.44%   |
| 21      | 35        | 1.44%   |
| 11      | 24        | 0.98%   |
| Unknown | 17        | 0.7%    |
| 22      | 12        | 0.49%   |
| 18      | 11        | 0.45%   |
| 40      | 8         | 0.33%   |
| 28      | 8         | 0.33%   |
| 39      | 5         | 0.21%   |
| 20      | 5         | 0.21%   |
| 19      | 5         | 0.21%   |
| 48      | 4         | 0.16%   |
| 32      | 4         | 0.16%   |
| 65      | 3         | 0.12%   |
| 52      | 3         | 0.12%   |
| 42      | 3         | 0.12%   |
| 26      | 3         | 0.12%   |
| 7       | 3         | 0.12%   |
| 84      | 2         | 0.08%   |
| 38      | 2         | 0.08%   |
| 37      | 2         | 0.08%   |
| 29      | 2         | 0.08%   |
| 25      | 2         | 0.08%   |
| 10      | 2         | 0.08%   |
| 74      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 55      | 1         | 0.04%   |
| 54      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 44      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1557      | 64.26%  |
| 201-300     | 275       | 11.35%  |
| 501-600     | 196       | 8.09%   |
| 351-400     | 150       | 6.19%   |
| 601-700     | 72        | 2.97%   |
| 401-500     | 64        | 2.64%   |
| 701-800     | 49        | 2.02%   |
| Unknown     | 17        | 0.7%    |
| 801-900     | 15        | 0.62%   |
| 1001-1500   | 15        | 0.62%   |
| 901-1000    | 6         | 0.25%   |
| 1-100       | 4         | 0.17%   |
| 1501-2000   | 3         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1551      | 70.37%  |
| 16/10   | 525       | 23.82%  |
| 21/9    | 53        | 2.4%    |
| 3/2     | 45        | 2.04%   |
| Unknown | 11        | 0.5%    |
| 32/9    | 5         | 0.23%   |
| 3.40    | 4         | 0.18%   |
| 5/4     | 3         | 0.14%   |
| 0.67    | 2         | 0.09%   |
| 4/3     | 1         | 0.05%   |
| 2.12    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 931       | 38.31%  |
| 81-90          | 570       | 23.46%  |
| 111-120        | 174       | 7.16%   |
| 201-250        | 119       | 4.9%    |
| 121-130        | 107       | 4.4%    |
| 351-500        | 104       | 4.28%   |
| 71-80          | 101       | 4.16%   |
| 301-350        | 100       | 4.12%   |
| 61-70          | 43        | 1.77%   |
| 51-60          | 29        | 1.19%   |
| 501-1000       | 26        | 1.07%   |
| 251-300        | 25        | 1.03%   |
| 151-200        | 23        | 0.95%   |
| 91-100         | 20        | 0.82%   |
| Unknown        | 17        | 0.7%    |
| More than 1000 | 13        | 0.53%   |
| 141-150        | 13        | 0.53%   |
| 131-140        | 10        | 0.41%   |
| 1-40           | 4         | 0.16%   |
| 41-50          | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1103      | 46.25%  |
| 101-120       | 407       | 17.06%  |
| 161-240       | 394       | 16.52%  |
| 51-100        | 276       | 11.57%  |
| More than 240 | 173       | 7.25%   |
| Unknown       | 17        | 0.71%   |
| 1-50          | 15        | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1667      | 78.52%  |
| 2     | 334       | 15.73%  |
| 0     | 60        | 2.83%   |
| 3     | 55        | 2.59%   |
| 4     | 7         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1179      | 37.22%  |
| Realtek Semiconductor             | 1037      | 32.73%  |
| Qualcomm Atheros                  | 202       | 6.38%   |
| MediaTek                          | 202       | 6.38%   |
| Broadcom                          | 193       | 6.09%   |
| Broadcom Limited                  | 50        | 1.58%   |
| Qualcomm                          | 39        | 1.23%   |
| ASIX Electronics                  | 32        | 1.01%   |
| Samsung Electronics               | 26        | 0.82%   |
| TP-Link                           | 24        | 0.76%   |
| DisplayLink                       | 16        | 0.51%   |
| Xiaomi                            | 14        | 0.44%   |
| Lenovo                            | 13        | 0.41%   |
| Ralink                            | 12        | 0.38%   |
| Sierra Wireless                   | 11        | 0.35%   |
| Marvell Technology Group          | 10        | 0.32%   |
| Google                            | 9         | 0.28%   |
| OPPO Electronics                  | 8         | 0.25%   |
| Qualcomm Technologies             | 7         | 0.22%   |
| Nvidia                            | 7         | 0.22%   |
| Apple                             | 7         | 0.22%   |
| Dell                              | 6         | 0.19%   |
| Ralink Technology                 | 5         | 0.16%   |
| Hewlett-Packard                   | 4         | 0.13%   |
| Ericsson Business Mobile Networks | 4         | 0.13%   |
| Edimax Technology                 | 4         | 0.13%   |
| Qualcomm Atheros Communications   | 3         | 0.09%   |
| NetGear                           | 3         | 0.09%   |
| Motorola PCS                      | 3         | 0.09%   |
| Microsoft                         | 3         | 0.09%   |
| JMicron Technology                | 3         | 0.09%   |
| ICS Advent                        | 3         | 0.09%   |
| Huawei Technologies               | 3         | 0.09%   |
| Fibocom                           | 3         | 0.09%   |
| D-Link System                     | 3         | 0.09%   |
| D-Link                            | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
| Unknown                           | 2         | 0.06%   |
| Wacom                             | 1         | 0.03%   |
| Uniden                            | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 606       | 16.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 124       | 3.3%    |
| Intel Wi-Fi 6 AX201                                                    | 105       | 2.79%   |
| Intel Wi-Fi 6 AX200                                                    | 103       | 2.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 99        | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 98        | 2.61%   |
| Intel Wireless 8265 / 8275                                             | 98        | 2.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 96        | 2.55%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 81        | 2.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 72        | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 69        | 1.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 56        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 55        | 1.46%   |
| Intel Meteor Lake PCH CNVi WiFi                                        | 54        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 53        | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 48        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 48        | 1.28%   |
| Intel Wireless 8260                                                    | 46        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 45        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 45        | 1.2%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 43        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 43        | 1.14%   |
| Intel Wireless 7265                                                    | 41        | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 38        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 37        | 0.98%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 35        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                          | 32        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 31        | 0.82%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 30        | 0.8%    |
| Intel Wireless 7260                                                    | 29        | 0.77%   |
| Realtek Killer E2600 GbE Controller                                    | 28        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 28        | 0.74%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 28        | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 0.72%   |
| Intel Ethernet Connection I219-LM                                      | 27        | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 27        | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                                  | 26        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 25        | 0.66%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 24        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                          | 23        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1133      | 53.95%  |
| Realtek Semiconductor           | 281       | 13.38%  |
| MediaTek                        | 178       | 8.48%   |
| Qualcomm Atheros                | 174       | 8.29%   |
| Broadcom                        | 169       | 8.05%   |
| Broadcom Limited                | 44        | 2.1%    |
| Qualcomm                        | 37        | 1.76%   |
| TP-Link                         | 17        | 0.81%   |
| Ralink                          | 12        | 0.57%   |
| Sierra Wireless                 | 11        | 0.52%   |
| Qualcomm Technologies           | 7         | 0.33%   |
| Ralink Technology               | 5         | 0.24%   |
| Dell                            | 5         | 0.24%   |
| Edimax Technology               | 4         | 0.19%   |
| Qualcomm Atheros Communications | 3         | 0.14%   |
| NetGear                         | 3         | 0.14%   |
| Fibocom                         | 3         | 0.14%   |
| D-Link System                   | 3         | 0.14%   |
| Microsoft                       | 2         | 0.1%    |
| D-Link                          | 2         | 0.1%    |
| ASUSTek Computer                | 2         | 0.1%    |
| Wacom                           | 1         | 0.05%   |
| Linksys                         | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| Guillemot                       | 1         | 0.05%   |
| AirTies Wireless Networks       | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 105       | 4.99%   |
| Intel Wi-Fi 6 AX200                                                  | 103       | 4.89%   |
| Intel Wireless 8265 / 8275                                           | 98        | 4.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 98        | 4.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 96        | 4.56%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 81        | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 69        | 3.28%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 56        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 55        | 2.61%   |
| Intel Meteor Lake PCH CNVi WiFi                                      | 54        | 2.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 53        | 2.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 49        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 48        | 2.28%   |
| Intel Wireless 8260                                                  | 46        | 2.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 45        | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 45        | 2.14%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 43        | 2.04%   |
| Intel Wireless 7265                                                  | 41        | 1.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 38        | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 37        | 1.76%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 35        | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 31        | 1.47%   |
| Intel Wireless 7260                                                  | 29        | 1.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 28        | 1.33%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 28        | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 28        | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 25        | 1.19%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 24        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 23        | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 22        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 21        | 1%      |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 19        | 0.9%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 19        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 17        | 0.81%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                   | 17        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 16        | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 16        | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 15        | 0.71%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 15        | 0.71%   |
| Intel Wireless 3160                                                  | 14        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 900       | 56.6%   |
| Intel                                  | 391       | 24.59%  |
| Broadcom                               | 63        | 3.96%   |
| Qualcomm Atheros                       | 43        | 2.7%    |
| ASIX Electronics                       | 32        | 2.01%   |
| MediaTek                               | 24        | 1.51%   |
| Samsung Electronics                    | 18        | 1.13%   |
| DisplayLink                            | 16        | 1.01%   |
| Xiaomi                                 | 14        | 0.88%   |
| Lenovo                                 | 13        | 0.82%   |
| Marvell Technology Group               | 10        | 0.63%   |
| OPPO Electronics                       | 8         | 0.5%    |
| Google                                 | 8         | 0.5%    |
| TP-Link                                | 7         | 0.44%   |
| Nvidia                                 | 7         | 0.44%   |
| Broadcom Limited                       | 7         | 0.44%   |
| Apple                                  | 7         | 0.44%   |
| Motorola PCS                           | 3         | 0.19%   |
| JMicron Technology                     | 3         | 0.19%   |
| ICS Advent                             | 3         | 0.19%   |
| Huawei Technologies                    | 3         | 0.19%   |
| Qualcomm                               | 2         | 0.13%   |
| Unknown                                | 2         | 0.13%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Hewlett-Packard                        | 1         | 0.06%   |
| Aquantia                               | 1         | 0.06%   |
| AboCom Systems                         | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 606       | 37.13%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 124       | 7.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 98        | 6%      |
| Intel Ethernet Connection (4) I219-LM                                  | 48        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 38        | 2.33%   |
| ASIX AX88179 Gigabit Ethernet                                          | 32        | 1.96%   |
| Realtek Killer E2600 GbE Controller                                    | 28        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 1.65%   |
| Intel Ethernet Connection I219-LM                                      | 27        | 1.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 27        | 1.65%   |
| Intel Ethernet Connection (6) I219-LM                                  | 26        | 1.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 23        | 1.41%   |
| Intel Ethernet Connection (7) I219-LM                                  | 20        | 1.23%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 18        | 1.1%    |
| Intel Ethernet Connection I217-LM                                      | 17        | 1.04%   |
| Intel Ethernet Connection (4) I219-V                                   | 17        | 1.04%   |
| Intel Ethernet Connection (13) I219-V                                  | 15        | 0.92%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 13        | 0.8%    |
| Intel Ethernet Connection (16) I219-LM                                 | 13        | 0.8%    |
| Intel Ethernet Connection (16) I219-V                                  | 12        | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 0.61%   |
| Intel Ethernet Connection I218-LM                                      | 10        | 0.61%   |
| Intel Ethernet Connection (13) I219-LM                                 | 10        | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                  | 10        | 0.61%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 9         | 0.55%   |
| Intel Ethernet Connection (23) I219-V                                  | 9         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 0.55%   |
| Intel Ethernet Connection (10) I219-LM                                 | 9         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                               | 9         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 8         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                  | 8         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 8         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 7         | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 7         | 0.43%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 7         | 0.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]     | 7         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 0.43%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 0.43%   |
| Intel Ethernet Controller I219-V                                       | 7         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2011      | 57.15%  |
| Ethernet | 1484      | 42.17%  |
| Modem    | 19        | 0.54%   |
| Unknown  | 5         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1731      | 79.48%  |
| Ethernet | 446       | 20.48%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1250      | 59.58%  |
| 1     | 798       | 38.04%  |
| 0     | 27        | 1.29%   |
| 3     | 22        | 1.05%   |
| 5     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1413      | 66.78%  |
| Yes  | 703       | 33.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1017      | 54.33%  |
| Realtek Semiconductor           | 192       | 10.26%  |
| IMC Networks                    | 138       | 7.37%   |
| Foxconn / Hon Hai               | 103       | 5.5%    |
| Apple                           | 99        | 5.29%   |
| Qualcomm Atheros Communications | 92        | 4.91%   |
| Lite-On Technology              | 55        | 2.94%   |
| Broadcom                        | 46        | 2.46%   |
| MediaTek                        | 28        | 1.5%    |
| USI                             | 23        | 1.23%   |
| Realtek                         | 16        | 0.85%   |
| Cambridge Silicon Radio         | 13        | 0.69%   |
| Dell                            | 11        | 0.59%   |
| Toshiba                         | 8         | 0.43%   |
| Ralink                          | 7         | 0.37%   |
| Foxconn International           | 6         | 0.32%   |
| TP-Link                         | 4         | 0.21%   |
| Hewlett-Packard                 | 4         | 0.21%   |
| Opticis                         | 3         | 0.16%   |
| Ralink Technology               | 2         | 0.11%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Alps Electric                   | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 265       | 14.16%  |
| Intel Bluetooth wireless interface                  | 225       | 12.02%  |
| Intel AX211 Bluetooth                               | 182       | 9.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 138       | 7.37%   |
| Realtek Bluetooth Radio                             | 124       | 6.62%   |
| Intel AX200 Bluetooth                               | 100       | 5.34%   |
| IMC Networks Wireless_Device                        | 93        | 4.97%   |
| Apple Bluetooth Host Controller                     | 63        | 3.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 54        | 2.88%   |
| Intel AX210 Bluetooth                               | 54        | 2.88%   |
| Foxconn / Hon Hai Wireless_Device                   | 47        | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 37        | 1.98%   |
| MediaTek Wireless_Device                            | 27        | 1.44%   |
| Apple Bluetooth USB Host Controller                 | 27        | 1.44%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.34%   |
| USI Bluetooth Device                                | 23        | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 1.23%   |
| Realtek 802.11ac WLAN Adapter                       | 22        | 1.18%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 19        | 1.01%   |
| Lite-On Wireless_Device                             | 18        | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 0.96%   |
| Realtek Bluetooth Radio                             | 16        | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 0.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.64%   |
| Lite-On Bluetooth Device                            | 12        | 0.64%   |
| Intel Bluetooth Device                              | 11        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 0.48%   |
| IMC Networks Bluetooth Device                       | 8         | 0.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.43%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.37%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.37%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 0.32%   |
| Lite-On Bluetooth Radio                             | 5         | 0.27%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.27%   |
| Broadcom HP Portable Bumble Bee                     | 5         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1573      | 56.75%  |
| AMD                                  | 519       | 18.72%  |
| Nvidia                               | 476       | 17.17%  |
| Logitech                             | 19        | 0.69%   |
| C-Media Electronics                  | 17        | 0.61%   |
| Lenovo                               | 16        | 0.58%   |
| GN Netcom                            | 15        | 0.54%   |
| Sony                                 | 12        | 0.43%   |
| Realtek Semiconductor                | 12        | 0.43%   |
| Plantronics                          | 9         | 0.32%   |
| Hewlett-Packard                      | 8         | 0.29%   |
| Generalplus Technology               | 7         | 0.25%   |
| ASUSTek Computer                     | 7         | 0.25%   |
| Texas Instruments                    | 6         | 0.22%   |
| Apple                                | 6         | 0.22%   |
| Razer USA                            | 4         | 0.14%   |
| Kingston Technology                  | 4         | 0.14%   |
| JMTek                                | 4         | 0.14%   |
| Focusrite-Novation                   | 4         | 0.14%   |
| Unknown                              | 4         | 0.14%   |
| Creative Technology                  | 3         | 0.11%   |
| ZOOM                                 | 2         | 0.07%   |
| TTGK Technology                      | 2         | 0.07%   |
| Trust                                | 2         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| SteelSeries ApS                      | 2         | 0.07%   |
| No brand                             | 2         | 0.07%   |
| Jieli Technology                     | 2         | 0.07%   |
| Framework                            | 2         | 0.07%   |
| DSEA A/S                             | 2         | 0.07%   |
| Dell                                 | 2         | 0.07%   |
| BEHRINGER International              | 2         | 0.07%   |
| Audeze                               | 2         | 0.07%   |
| Yealink Network Technology           | 1         | 0.04%   |
| Winbond Electronics                  | 1         | 0.04%   |
| Walmart                              | 1         | 0.04%   |
| Tenx Technology                      | 1         | 0.04%   |
| Silicon Motion                       | 1         | 0.04%   |
| Sennheiser electronic                | 1         | 0.04%   |
| Samsung Electronics                  | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 422       | 12.53%  |
| Intel Sunrise Point-LP HD Audio                                            | 226       | 6.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 186       | 5.52%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 166       | 4.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 149       | 4.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 132       | 3.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 113       | 3.36%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 106       | 3.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 82        | 2.43%   |
| Nvidia GA107 High Definition Audio Controller                              | 64        | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 64        | 1.9%    |
| Nvidia AD107 High Definition Audio Controller                              | 61        | 1.81%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 61        | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 59        | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 56        | 1.66%   |
| Intel Broadwell-U Audio Controller                                         | 56        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 56        | 1.66%   |
| Intel Comet Lake PCH cAVS                                                  | 54        | 1.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 53        | 1.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 51        | 1.51%   |
| Intel Haswell-ULT HD Audio Controller                                      | 51        | 1.51%   |
| Intel 8 Series HD Audio Controller                                         | 50        | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 49        | 1.45%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 43        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 42        | 1.25%   |
| Nvidia GA106 High Definition Audio Controller                              | 39        | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 39        | 1.16%   |
| Intel Raptor Lake High Definition Audio Controller                         | 33        | 0.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 33        | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 32        | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                              | 31        | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 31        | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 26        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 25        | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 25        | 0.74%   |
| Nvidia AD106M High Definition Audio Controller                             | 23        | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 20        | 0.59%   |
| AMD Kabini HDMI/DP Audio                                                   | 18        | 0.53%   |
| AMD FCH Azalia Controller                                                  | 18        | 0.53%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 17        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 287       | 30.79%  |
| SK hynix               | 201       | 21.57%  |
| Micron Technology      | 177       | 18.99%  |
| Crucial                | 53        | 5.69%   |
| Kingston               | 51        | 5.47%   |
| A-DATA Technology      | 25        | 2.68%   |
| Unknown                | 19        | 2.04%   |
| Unknown                | 18        | 1.93%   |
| Ramaxel Technology     | 11        | 1.18%   |
| Elpida                 | 11        | 1.18%   |
| G.Skill                | 8         | 0.86%   |
| Corsair                | 6         | 0.64%   |
| Apacer                 | 5         | 0.54%   |
| Nanya Technology       | 4         | 0.43%   |
| Timetec                | 3         | 0.32%   |
| Smart                  | 3         | 0.32%   |
| Patriot                | 3         | 0.32%   |
| Kllisre                | 3         | 0.32%   |
| ChangXin Memory        | 3         | 0.32%   |
| Transcend              | 2         | 0.21%   |
| Teikon                 | 2         | 0.21%   |
| Team                   | 2         | 0.21%   |
| Smart Modular          | 2         | 0.21%   |
| Shenzhen SCY           | 2         | 0.21%   |
| Lexar                  | 2         | 0.21%   |
| GOODRAM                | 2         | 0.21%   |
| Avant                  | 2         | 0.21%   |
| AMD                    | 2         | 0.21%   |
| Wilk                   | 1         | 0.11%   |
| Unknown (F785)         | 1         | 0.11%   |
| Unknown (ABCD)         | 1         | 0.11%   |
| Unknown (89F7)         | 1         | 0.11%   |
| Unknown (0x8000)       | 1         | 0.11%   |
| Unknown (0x1636)       | 1         | 0.11%   |
| Unknown (0x0B5E)       | 1         | 0.11%   |
| Unknown (0000000080CE) | 1         | 0.11%   |
| Smart Brazil           | 1         | 0.11%   |
| PNY                    | 1         | 0.11%   |
| Neo Forza              | 1         | 0.11%   |
| Multilaser             | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 2.06%   |
| Unknown                                                          | 19        | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 1.75%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 16        | 1.65%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.93%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.72%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 7         | 0.72%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 7         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.62%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 6         | 0.62%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.51%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 5         | 0.51%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.51%   |
| SK hynix RAM H58G66BK7BX067 4GB Row Of Chips LPDDR5 8533MT/s     | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.51%   |
| Micron RAM MT62F4G32D8DV-026 WT 16GB SODIMM LPDDR5 7500MT/s      | 5         | 0.51%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s       | 5         | 0.51%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.51%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 5         | 0.51%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s        | 5         | 0.51%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 4         | 0.41%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 4         | 0.41%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 4         | 0.41%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 4         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.41%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.41%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 386       | 48.61%  |
| DDR3    | 137       | 17.25%  |
| LPDDR5  | 107       | 13.48%  |
| DDR5    | 89        | 11.21%  |
| LPDDR4  | 38        | 4.79%   |
| LPDDR3  | 27        | 3.4%    |
| DDR2    | 5         | 0.63%   |
| SDRAM   | 4         | 0.5%    |
| Unknown | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 630       | 78.95%  |
| Row Of Chips    | 153       | 19.17%  |
| Unknown         | 8         | 1%      |
| Chip            | 4         | 0.5%    |
| DIMM            | 2         | 0.25%   |
| Proprietary Car | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Notebooks | Percent |
|--------|-----------|---------|
| 8192   | 376       | 44.08%  |
| 16384  | 188       | 22.04%  |
| 4096   | 169       | 19.81%  |
| 32768  | 59        | 6.92%   |
| 2048   | 47        | 5.51%   |
| 1024   | 8         | 0.94%   |
| 3072   | 4         | 0.47%   |
| 131072 | 1         | 0.12%   |
| 12288  | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 236       | 28.2%   |
| 2667    | 125       | 14.93%  |
| 1600    | 108       | 12.9%   |
| 6400    | 53        | 6.33%   |
| 5600    | 52        | 6.21%   |
| 4800    | 38        | 4.54%   |
| 2400    | 38        | 4.54%   |
| 2133    | 35        | 4.18%   |
| 7500    | 27        | 3.23%   |
| 7467    | 16        | 1.91%   |
| 4267    | 16        | 1.91%   |
| 1867    | 14        | 1.67%   |
| 1333    | 12        | 1.43%   |
| 3266    | 8         | 0.96%   |
| 1334    | 8         | 0.96%   |
| 8533    | 7         | 0.84%   |
| 4266    | 7         | 0.84%   |
| 3733    | 7         | 0.84%   |
| 1067    | 4         | 0.48%   |
| 667     | 4         | 0.48%   |
| 5500    | 3         | 0.36%   |
| 1066    | 3         | 0.36%   |
| 8600    | 2         | 0.24%   |
| 8400    | 2         | 0.24%   |
| 4199    | 2         | 0.24%   |
| 2933    | 2         | 0.24%   |
| 2048    | 2         | 0.24%   |
| Unknown | 2         | 0.24%   |
| 5200    | 1         | 0.12%   |
| 2800    | 1         | 0.12%   |
| 1330    | 1         | 0.12%   |
| 975     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 62.5%   |
| Seiko Epson        | 1         | 12.5%   |
| iDPRT              | 1         | 12.5%   |
| Brother Industries | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Seiko Epson M1120 Series        | 1         | 12.5%   |
| iDPRT SP410                     | 1         | 12.5%   |
| HP LaserJet 3050                | 1         | 12.5%   |
| HP Ink Tank Wireless 410 series | 1         | 12.5%   |
| HP Deskjet F2280 series         | 1         | 12.5%   |
| HP Deskjet 2050 J510            | 1         | 12.5%   |
| HP Deskjet 1000 J110 series     | 1         | 12.5%   |
| Brother DCP-7030                | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| HP ScanJet 4070 PhotoSmart | 1         | 50%     |
| Canon CanoScan 4200F       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 396       | 20.96%  |
| IMC Networks                           | 214       | 11.33%  |
| Quanta                                 | 144       | 7.62%   |
| Realtek Semiconductor                  | 143       | 7.57%   |
| Bison Electronics                      | 133       | 7.04%   |
| Microdia                               | 132       | 6.99%   |
| Luxvisions Innotech Limited            | 103       | 5.45%   |
| Sunplus Innovation Technology          | 80        | 4.24%   |
| Cheng Uei Precision Industry (Foxlink) | 71        | 3.76%   |
| Apple                                  | 64        | 3.39%   |
| Syntek                                 | 62        | 3.28%   |
| Sonix Technology                       | 58        | 3.07%   |
| Lite-On Technology                     | 46        | 2.44%   |
| ShineTech                              | 39        | 2.06%   |
| Logitech                               | 34        | 1.8%    |
| Acer                                   | 21        | 1.11%   |
| Suyin                                  | 19        | 1.01%   |
| SunplusIT                              | 17        | 0.9%    |
| Alcor Micro                            | 15        | 0.79%   |
| Samsung Electronics                    | 12        | 0.64%   |
| Silicon Motion                         | 11        | 0.58%   |
| icSpring                               | 5         | 0.26%   |
| ShineOptics                            | 4         | 0.21%   |
| Lenovo                                 | 4         | 0.21%   |
| Tripath Technology                     | 3         | 0.16%   |
| Importek                               | 3         | 0.16%   |
| HYGD-220831-A                          | 3         | 0.16%   |
| Framework                              | 3         | 0.16%   |
| Unknown                                | 3         | 0.16%   |
| Sunwingroup                            | 2         | 0.11%   |
| Ricoh                                  | 2         | 0.11%   |
| Microsoft                              | 2         | 0.11%   |
| KYE Systems (Mouse Systems)            | 2         | 0.11%   |
| kingcome                               | 2         | 0.11%   |
| ALi                                    | 2         | 0.11%   |
| Yealink Network Technology             | 1         | 0.05%   |
| Xiaomi                                 | 1         | 0.05%   |
| Trust                                  | 1         | 0.05%   |
| Sunplus Technology                     | 1         | 0.05%   |
| Sunplus IT                             | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 129       | 6.75%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 87        | 4.55%   |
| Microdia Integrated_Webcam_HD                        | 68        | 3.56%   |
| Realtek Integrated_Webcam_HD                         | 67        | 3.51%   |
| IMC Networks Integrated Camera                       | 63        | 3.3%    |
| Syntek Integrated Camera                             | 55        | 2.88%   |
| Bison Integrated Camera                              | 44        | 2.3%    |
| Sonix USB2.0 HD UVC WebCam                           | 39        | 2.04%   |
| Luxvisions Innotech Limited Integrated Camera        | 31        | 1.62%   |
| Sunplus Integrated_Webcam_HD                         | 29        | 1.52%   |
| Chicony HP HD Camera                                 | 27        | 1.41%   |
| Apple FaceTime HD Camera                             | 27        | 1.41%   |
| Shinetech USB2.0 FHD UVC WebCam                      | 24        | 1.26%   |
| Quanta ACER HD User Facing                           | 23        | 1.2%    |
| Quanta HP HD Camera                                  | 22        | 1.15%   |
| Chicony HD Webcam                                    | 22        | 1.15%   |
| Lite-On Integrated Camera                            | 20        | 1.05%   |
| Chicony Integrated Camera (1280x720@30)              | 20        | 1.05%   |
| Chicony Integrated IR Camera                         | 17        | 0.89%   |
| Quanta HP Wide Vision HD Camera                      | 16        | 0.84%   |
| Bison HD Webcam                                      | 16        | 0.84%   |
| Sonix USB2.0 FHD UVC WebCam                          | 15        | 0.79%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 15        | 0.79%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 15        | 0.79%   |
| Chicony ACER HD User Facing                          | 15        | 0.79%   |
| Quanta HD User Facing                                | 14        | 0.73%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 14        | 0.73%   |
| Chicony HD User Facing                               | 14        | 0.73%   |
| ShineTech USB2.0 HD UVC WebCam                       | 13        | 0.68%   |
| Luxvisions Innotech Limited HP HD Camera             | 13        | 0.68%   |
| Apple Built-in iSight                                | 13        | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)              | 12        | 0.63%   |
| Bison SunplusIT Integrated Camera                    | 12        | 0.63%   |
| Bison Integrated RGB Camera                          | 12        | 0.63%   |
| Apple FaceTime HD Camera (Built-in)                  | 12        | 0.63%   |
| Quanta HP TrueVision HD Camera                       | 11        | 0.58%   |
| Microdia Integrated_Webcam_FHD                       | 11        | 0.58%   |
| IMC Networks HD Camera                               | 11        | 0.58%   |
| Sunplus HD WebCam                                    | 10        | 0.52%   |
| Realtek Integrated_Webcam_FHD                        | 10        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 149       | 40.49%  |
| Validity Sensors                   | 90        | 24.46%  |
| Shenzhen Goodix Technology         | 61        | 16.58%  |
| Elan Microelectronics              | 26        | 7.07%   |
| Upek                               | 13        | 3.53%   |
| Realtek USB2.0 Finger Print Bridge | 13        | 3.53%   |
| AuthenTec                          | 5         | 1.36%   |
| LighTuning Technology              | 4         | 1.09%   |
| FocalTech                          | 2         | 0.54%   |
| Focal-systems.Corp                 | 2         | 0.54%   |
| Next Biometrics                    | 1         | 0.27%   |
| GDMicroelectronics                 | 1         | 0.27%   |
| DigitalPersona                     | 1         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 48        | 13.04%  |
| Shenzhen Goodix  Fingerprint Device                                        | 44        | 11.96%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 31        | 8.42%   |
| Synaptics UWP WBDI Device                                                  | 21        | 5.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 4.89%   |
| Elan ELAN:ARM-M4                                                           | 15        | 4.08%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 3.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 3.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 3.53%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 13        | 3.53%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 3.26%   |
| Validity Sensors VFS491                                                    | 11        | 2.99%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 2.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.45%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.45%   |
| Synaptics Prometheus Fingerprint Reader                                    | 8         | 2.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 1.9%    |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.9%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.36%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.36%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.36%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 1.09%   |
| Synaptics  WBDI                                                            | 3         | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.54%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.54%   |
| Synaptics TouchPad                                                         | 2         | 0.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.54%   |
| FocalTech FocalTech Fingerprint Device                                     | 2         | 0.54%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 0.54%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.54%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.27%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.27%   |
| Synaptics WBDI                                                             | 1         | 0.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.27%   |
| Next Biometrics NB-2020-U Fingerprint Reader                               | 1         | 0.27%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 84        | 56%     |
| Alcor Micro           | 44        | 29.33%  |
| Upek                  | 10        | 6.67%   |
| O2 Micro              | 3         | 2%      |
| Lenovo                | 3         | 2%      |
| Yubico.com            | 1         | 0.67%   |
| OmniKey               | 1         | 0.67%   |
| Gemalto (was Gemplus) | 1         | 0.67%   |
| Feitian Technologies  | 1         | 0.67%   |
| Clay Logic            | 1         | 0.67%   |
| Advanced Card Systems | 1         | 0.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 29.33%  |
| Broadcom 58200                                                               | 40        | 26.67%  |
| Broadcom 5880                                                                | 21        | 14%     |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 9.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 6%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2%      |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.67%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.67%   |
| Feitian Technologies ePass2003                                               | 1         | 0.67%   |
| Clay Logic CanoKey Pigeon                                                    | 1         | 0.67%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1193      | 56.19%  |
| 1     | 770       | 36.27%  |
| 2     | 148       | 6.97%   |
| 3     | 12        | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 375       | 34.79%  |
| Fingerprint reader       | 364       | 33.77%  |
| Multimedia controller    | 177       | 16.42%  |
| Net/wireless             | 72        | 6.68%   |
| Chipcard                 | 36        | 3.34%   |
| Camera                   | 15        | 1.39%   |
| Bluetooth                | 9         | 0.83%   |
| Storage                  | 8         | 0.74%   |
| Net/ethernet             | 8         | 0.74%   |
| Card reader              | 6         | 0.56%   |
| Sound                    | 3         | 0.28%   |
| Modem                    | 2         | 0.19%   |
| Communication controller | 2         | 0.19%   |
| Network                  | 1         | 0.09%   |

