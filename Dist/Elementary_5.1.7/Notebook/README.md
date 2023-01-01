Elementary 5.1.7 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Elementary 5.1.7.

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

Total: 205

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [7b03f438db](https://linux-hardware.org/?probe=7b03f438db) | Dec 28, 2022 |
| Positivo      | S14SL01                     | [476e8a784c](https://linux-hardware.org/?probe=476e8a784c) | Dec 21, 2022 |
| Positivo      | S14SL01                     | [08e3a4d7f2](https://linux-hardware.org/?probe=08e3a4d7f2) | Dec 21, 2022 |
| Apple         | MacBook3,1                  | [404821c7d6](https://linux-hardware.org/?probe=404821c7d6) | Nov 25, 2022 |
| HP            | Pavilion dv5                | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| ASUSTek       | UX31A                       | [4b7e610e25](https://linux-hardware.org/?probe=4b7e610e25) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| Lenovo        | V15-IIL 82C5                | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
| Lenovo        | V15-IIL 82C5                | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HP            | ZBook 15                    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| HP            | EliteBook 8470p             | [d7223d4b03](https://linux-hardware.org/?probe=d7223d4b03) | May 05, 2022 |
| Dell          | Latitude 3550               | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| Panasonic     | CF-31SBLJGDM                | [60a1068658](https://linux-hardware.org/?probe=60a1068658) | Apr 13, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| Acer          | Swift SF314-52              | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| Dell          | Latitude 3550               | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
| ASUSTek       | K75VJ                       | [e0c07cf9d2](https://linux-hardware.org/?probe=e0c07cf9d2) | Feb 20, 2022 |
| Panasonic     | CF-31SBLJGDM                | [488b80a942](https://linux-hardware.org/?probe=488b80a942) | Feb 03, 2022 |
| HP            | Pavilion dv5                | [62a18fa26b](https://linux-hardware.org/?probe=62a18fa26b) | Jan 26, 2022 |
| Dell          | Latitude 5420               | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
| MSI           | GE60 2PE                    | [d74dcddae6](https://linux-hardware.org/?probe=d74dcddae6) | Jan 13, 2022 |
| ASUSTek       | UX31A                       | [afe25bb395](https://linux-hardware.org/?probe=afe25bb395) | Jan 10, 2022 |
| Dell          | Latitude 5420               | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fa46d4f41a](https://linux-hardware.org/?probe=fa46d4f41a) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [22fb358e03](https://linux-hardware.org/?probe=22fb358e03) | Dec 28, 2021 |
| Apple         | MacBook2,1                  | [82483b42e2](https://linux-hardware.org/?probe=82483b42e2) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | [197a4e0280](https://linux-hardware.org/?probe=197a4e0280) | Dec 21, 2021 |
| Acer          | Aspire R3-131T              | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| HP            | Pavilion dv7                | [073367afb1](https://linux-hardware.org/?probe=073367afb1) | Nov 25, 2021 |
| HP            | Laptop 17-by3xxx            | [beba4da01c](https://linux-hardware.org/?probe=beba4da01c) | Nov 09, 2021 |
| ASUSTek       | K75VJ                       | [9c0bccf601](https://linux-hardware.org/?probe=9c0bccf601) | Nov 01, 2021 |
| Toshiba       | Satellite C870-1H2          | [73615204f8](https://linux-hardware.org/?probe=73615204f8) | Sep 23, 2021 |
| Acer          | Aspire R3-131T              | [e872ba288e](https://linux-hardware.org/?probe=e872ba288e) | Sep 12, 2021 |
| Dell          | Vostro 15-3568              | [9460412d4d](https://linux-hardware.org/?probe=9460412d4d) | Sep 04, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [cf69bd4423](https://linux-hardware.org/?probe=cf69bd4423) | Aug 31, 2021 |
| Acer          | Aspire E5-573G              | [8c61841633](https://linux-hardware.org/?probe=8c61841633) | Aug 30, 2021 |
| HP            | Laptop 17-by3xxx            | [84aa134848](https://linux-hardware.org/?probe=84aa134848) | Aug 25, 2021 |
| HP            | Laptop 17-by3xxx            | [674068cb21](https://linux-hardware.org/?probe=674068cb21) | Aug 19, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Acer          | Aspire 3810TZ               | [6b7176e5ed](https://linux-hardware.org/?probe=6b7176e5ed) | Aug 10, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| Acer          | Aspire E5-573G              | [caa41076f3](https://linux-hardware.org/?probe=caa41076f3) | Aug 07, 2021 |
| HP            | EliteBook 2570p             | [53c721a204](https://linux-hardware.org/?probe=53c721a204) | Aug 01, 2021 |
| Lenovo        | ThinkPad P50 20ENA00PLM     | [3b6f4346e5](https://linux-hardware.org/?probe=3b6f4346e5) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [75ff3dac2c](https://linux-hardware.org/?probe=75ff3dac2c) | Jul 28, 2021 |
| Dell          | Latitude E5470              | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| Dell          | Vostro 3446                 | [566fe43065](https://linux-hardware.org/?probe=566fe43065) | Jul 25, 2021 |
| Dell          | Vostro 3446                 | [9a984d5856](https://linux-hardware.org/?probe=9a984d5856) | Jul 25, 2021 |
| Dell          | Vostro 15-3568              | [9951dfaa86](https://linux-hardware.org/?probe=9951dfaa86) | Jul 24, 2021 |
| Acer          | Aspire E5-573G              | [a01b8bbea0](https://linux-hardware.org/?probe=a01b8bbea0) | Jul 07, 2021 |
| Google        | Banjo                       | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| HP            | Pavilion 14                 | [01491528b1](https://linux-hardware.org/?probe=01491528b1) | Jun 28, 2021 |
| Acer          | Aspire E1-570G              | [e72de97e18](https://linux-hardware.org/?probe=e72de97e18) | Jun 25, 2021 |
| ASUSTek       | ZenBook UX481FA_UX481FA     | [675397a7db](https://linux-hardware.org/?probe=675397a7db) | Jun 19, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [82e660e88d](https://linux-hardware.org/?probe=82e660e88d) | Jun 12, 2021 |
| Toshiba       | Satellite L500              | [e8589abc23](https://linux-hardware.org/?probe=e8589abc23) | Jun 10, 2021 |
| Toshiba       | Satellite L500              | [b65c50aaf8](https://linux-hardware.org/?probe=b65c50aaf8) | Jun 09, 2021 |
| Toshiba       | Satellite L500              | [6b941d232d](https://linux-hardware.org/?probe=6b941d232d) | Jun 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3f8470a641](https://linux-hardware.org/?probe=3f8470a641) | Jun 02, 2021 |
| Lenovo        | ThinkPad X240 20AMA0XK00    | [8b7ecca1b8](https://linux-hardware.org/?probe=8b7ecca1b8) | Jun 02, 2021 |
| HP            | Presario CQ56               | [70a720b401](https://linux-hardware.org/?probe=70a720b401) | May 31, 2021 |
| HP            | Pavilion g7                 | [6607d7bfd4](https://linux-hardware.org/?probe=6607d7bfd4) | May 28, 2021 |
| HP            | Laptop 17-by3xxx            | [94e12db274](https://linux-hardware.org/?probe=94e12db274) | May 28, 2021 |
| Toshiba       | Satellite L500              | [7bcdcd125f](https://linux-hardware.org/?probe=7bcdcd125f) | May 24, 2021 |
| Toshiba       | Satellite L500              | [c812470c98](https://linux-hardware.org/?probe=c812470c98) | May 22, 2021 |
| HUAWEI        | HLY-WX9XX                   | [96c74bb052](https://linux-hardware.org/?probe=96c74bb052) | May 14, 2021 |
| Dell          | Latitude E6400              | [28c0f73a83](https://linux-hardware.org/?probe=28c0f73a83) | May 12, 2021 |
| LG Electro... | A410-K.BE43P1               | [dd6a1734a8](https://linux-hardware.org/?probe=dd6a1734a8) | May 09, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [dc9c7088dd](https://linux-hardware.org/?probe=dc9c7088dd) | May 08, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [9cf4893825](https://linux-hardware.org/?probe=9cf4893825) | May 08, 2021 |
| ASUSTek       | K45VD                       | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| Acer          | Aspire F5-573G              | [fdabc1d291](https://linux-hardware.org/?probe=fdabc1d291) | Apr 28, 2021 |
| Acer          | Aspire F5-573G              | [2e2cc93814](https://linux-hardware.org/?probe=2e2cc93814) | Apr 28, 2021 |
| ASUSTek       | X205TAW                     | [91e8c10d9e](https://linux-hardware.org/?probe=91e8c10d9e) | Apr 25, 2021 |
| Acer          | Aspire R3-131T              | [1d52101f3a](https://linux-hardware.org/?probe=1d52101f3a) | Apr 23, 2021 |
| Positivo      | S14SL01                     | [f1cc01bb29](https://linux-hardware.org/?probe=f1cc01bb29) | Apr 22, 2021 |
| Lenovo        | ThinkPad T460 20FMS6C200    | [7f900f8923](https://linux-hardware.org/?probe=7f900f8923) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Lenovo        | ThinkPad R61e/R61i 76508... | [e3b2bd3e3a](https://linux-hardware.org/?probe=e3b2bd3e3a) | Apr 14, 2021 |
| HP            | Elite x2 1012 G1            | [09240a2a3f](https://linux-hardware.org/?probe=09240a2a3f) | Apr 13, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [9749184629](https://linux-hardware.org/?probe=9749184629) | Apr 12, 2021 |
| ASUSTek       | K53SC                       | [7cd834c7b9](https://linux-hardware.org/?probe=7cd834c7b9) | Apr 11, 2021 |
| Positivo      | C14CR21                     | [b4ed03e23e](https://linux-hardware.org/?probe=b4ed03e23e) | Apr 11, 2021 |
| Dell          | Inspiron 5458               | [90eb8e7cc2](https://linux-hardware.org/?probe=90eb8e7cc2) | Apr 08, 2021 |
| Lenovo        | ThinkPad W540 20BHS1MX00    | [47cc5eb719](https://linux-hardware.org/?probe=47cc5eb719) | Apr 07, 2021 |
| HP            | Pavilion 15                 | [e2bbdc0f8a](https://linux-hardware.org/?probe=e2bbdc0f8a) | Mar 26, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Toshiba       | QOSMIO G55                  | [be88551910](https://linux-hardware.org/?probe=be88551910) | Mar 22, 2021 |
| HP            | ProBook 430 G6              | [29ef42ccfc](https://linux-hardware.org/?probe=29ef42ccfc) | Mar 20, 2021 |
| Toshiba       | QOSMIO G55                  | [35fcfae27e](https://linux-hardware.org/?probe=35fcfae27e) | Mar 19, 2021 |
| HP            | 250 G6 Notebook PC          | [0fadf2dbc1](https://linux-hardware.org/?probe=0fadf2dbc1) | Mar 08, 2021 |
| Apple         | MacBookPro5,5               | [9e67aa8a54](https://linux-hardware.org/?probe=9e67aa8a54) | Mar 02, 2021 |
| HP            | Notebook                    | [201023370e](https://linux-hardware.org/?probe=201023370e) | Feb 28, 2021 |
| Lenovo        | G50-45 80E3                 | [686e15d925](https://linux-hardware.org/?probe=686e15d925) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Lenovo        | ThinkPad E14 20RBS6MD00     | [32fced07f8](https://linux-hardware.org/?probe=32fced07f8) | Feb 25, 2021 |
| Dell          | Vostro 14 5401              | [e6e3289d55](https://linux-hardware.org/?probe=e6e3289d55) | Feb 25, 2021 |
| HP            | ProBook 5330m               | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Compaq        | Presario CQ-23              | [2266878950](https://linux-hardware.org/?probe=2266878950) | Feb 21, 2021 |
| Acer          | V5-131                      | [fb508c9cd9](https://linux-hardware.org/?probe=fb508c9cd9) | Feb 14, 2021 |
| Toshiba       | Satellite P750              | [65db006d0a](https://linux-hardware.org/?probe=65db006d0a) | Feb 12, 2021 |
| Compaq        | Presario CQ-23              | [0303913f3a](https://linux-hardware.org/?probe=0303913f3a) | Feb 10, 2021 |
| Acer          | Aspire A515-54              | [878b85cbc6](https://linux-hardware.org/?probe=878b85cbc6) | Feb 06, 2021 |
| Lenovo        | 3000 G530 4151/200          | [9bccdfbc03](https://linux-hardware.org/?probe=9bccdfbc03) | Feb 05, 2021 |
| Apple         | MacBook7,1                  | [8b201eef4f](https://linux-hardware.org/?probe=8b201eef4f) | Feb 05, 2021 |
| Dell          | XPS 13 7390                 | [69d8376e50](https://linux-hardware.org/?probe=69d8376e50) | Feb 03, 2021 |
| Sony          | VPCF23JFX                   | [6fffecad4a](https://linux-hardware.org/?probe=6fffecad4a) | Feb 02, 2021 |
| HP            | EliteBook 840 G3            | [2ee3bd8ca9](https://linux-hardware.org/?probe=2ee3bd8ca9) | Jan 30, 2021 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [4ce7ac1cce](https://linux-hardware.org/?probe=4ce7ac1cce) | Jan 30, 2021 |
| Acer          | AOD255E                     | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [c259d42e53](https://linux-hardware.org/?probe=c259d42e53) | Jan 16, 2021 |
| Dell          | G3 3579                     | [888385f26b](https://linux-hardware.org/?probe=888385f26b) | Jan 13, 2021 |
| Dell          | Latitude E6500              | [81ffedd992](https://linux-hardware.org/?probe=81ffedd992) | Jan 13, 2021 |
| Acer          | Swift SF314-54              | [b4bd0c4eec](https://linux-hardware.org/?probe=b4bd0c4eec) | Jan 12, 2021 |
| Dell          | XPS 13 9300                 | [4a241f61c6](https://linux-hardware.org/?probe=4a241f61c6) | Jan 05, 2021 |
| HP            | Laptop 17-by3xxx            | [84272dcaa9](https://linux-hardware.org/?probe=84272dcaa9) | Jan 05, 2021 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [21c0963f18](https://linux-hardware.org/?probe=21c0963f18) | Jan 03, 2021 |
| Star Labs     | Lite                        | [02fa9d26a2](https://linux-hardware.org/?probe=02fa9d26a2) | Jan 03, 2021 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [7f209f6d03](https://linux-hardware.org/?probe=7f209f6d03) | Dec 31, 2020 |
| Acer          | Aspire R3-131T              | [934454c9c1](https://linux-hardware.org/?probe=934454c9c1) | Dec 29, 2020 |
| Lenovo        | ThinkPad T420 4236M37       | [da2b217109](https://linux-hardware.org/?probe=da2b217109) | Dec 27, 2020 |
| HP            | EliteBook Folio 9470m       | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Apple         | MacBook7,1                  | [8f63e2a0d9](https://linux-hardware.org/?probe=8f63e2a0d9) | Dec 25, 2020 |
| HP            | G42                         | [c2046377dc](https://linux-hardware.org/?probe=c2046377dc) | Dec 25, 2020 |
| Dell          | Latitude E6520              | [01048967fe](https://linux-hardware.org/?probe=01048967fe) | Dec 24, 2020 |
| Apple         | MacBook7,1                  | [5e92b317ef](https://linux-hardware.org/?probe=5e92b317ef) | Dec 24, 2020 |
| Apple         | MacBook2,1                  | [1bae958a19](https://linux-hardware.org/?probe=1bae958a19) | Dec 17, 2020 |
| LG Electro... | R490-G.ARL5RE2              | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | [ec54395d4b](https://linux-hardware.org/?probe=ec54395d4b) | Dec 15, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | [344504a10b](https://linux-hardware.org/?probe=344504a10b) | Dec 15, 2020 |
| Chuwi         | LapBook Pro                 | [602060bbe9](https://linux-hardware.org/?probe=602060bbe9) | Dec 13, 2020 |
| HP            | Pavilion dv7                | [fee310f330](https://linux-hardware.org/?probe=fee310f330) | Dec 13, 2020 |
| Toshiba       | Satellite R630              | [816b966aa8](https://linux-hardware.org/?probe=816b966aa8) | Dec 11, 2020 |
| HP            | 250 G7 Notebook PC          | [0e95ec9f75](https://linux-hardware.org/?probe=0e95ec9f75) | Dec 08, 2020 |
| Unknown       | 1.0                         | [05b0ad54c9](https://linux-hardware.org/?probe=05b0ad54c9) | Dec 07, 2020 |
| HP            | Pavilion dv7                | [332576610a](https://linux-hardware.org/?probe=332576610a) | Dec 06, 2020 |
| Acer          | Aspire E5-411               | [2513d28117](https://linux-hardware.org/?probe=2513d28117) | Dec 02, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [0ef0b89d48](https://linux-hardware.org/?probe=0ef0b89d48) | Dec 01, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Apple         | MacBookAir7,2               | [04def4b8c8](https://linux-hardware.org/?probe=04def4b8c8) | Nov 25, 2020 |
| Dell          | Inspiron 3542               | [d7a6b8524d](https://linux-hardware.org/?probe=d7a6b8524d) | Nov 23, 2020 |
| ASUSTek       | X200CA                      | [73a317dd32](https://linux-hardware.org/?probe=73a317dd32) | Nov 21, 2020 |
| ASUSTek       | X200CA                      | [2a86994bf7](https://linux-hardware.org/?probe=2a86994bf7) | Nov 21, 2020 |
| HP            | EliteBook 840 G3            | [b0504dfd39](https://linux-hardware.org/?probe=b0504dfd39) | Nov 21, 2020 |
| ASUSTek       | U31SD                       | [0454faa58e](https://linux-hardware.org/?probe=0454faa58e) | Nov 20, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| HP            | Laptop 17-by3xxx            | [4b3fbfd552](https://linux-hardware.org/?probe=4b3fbfd552) | Nov 12, 2020 |
| Lenovo        | ThinkPad T480 20L50007RT    | [284c6ccc22](https://linux-hardware.org/?probe=284c6ccc22) | Nov 10, 2020 |
| Acer          | Aspire E5-475G              | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| Apple         | MacBookPro11,2              | [aaa025e278](https://linux-hardware.org/?probe=aaa025e278) | Nov 09, 2020 |
| Acer          | Aspire F5-573G              | [dec186ab5a](https://linux-hardware.org/?probe=dec186ab5a) | Nov 08, 2020 |
| Apple         | MacBookPro11,2              | [c9674438eb](https://linux-hardware.org/?probe=c9674438eb) | Nov 04, 2020 |
| Acer          | AOD255E                     | [b64297fa62](https://linux-hardware.org/?probe=b64297fa62) | Nov 04, 2020 |
| Acer          | AOD255E                     | [3ef6628882](https://linux-hardware.org/?probe=3ef6628882) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| Toshiba       | Satellite L855              | [4b4e294b37](https://linux-hardware.org/?probe=4b4e294b37) | Oct 28, 2020 |
| Lenovo        | ThinkPad L480 20LSS0GL00    | [7401cec82c](https://linux-hardware.org/?probe=7401cec82c) | Oct 28, 2020 |
| Lenovo        | ThinkPad L480 20LSS0GL00    | [70d33d80bb](https://linux-hardware.org/?probe=70d33d80bb) | Oct 27, 2020 |
| Dell          | MXG061                      | [d3495d4c8b](https://linux-hardware.org/?probe=d3495d4c8b) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Dell          | XPS 13 9370                 | [565653d844](https://linux-hardware.org/?probe=565653d844) | Oct 21, 2020 |
| HP            | Laptop 17-by3xxx            | [2c0288dadd](https://linux-hardware.org/?probe=2c0288dadd) | Oct 20, 2020 |
| HP            | Laptop 17-by3xxx            | [72d9d5cf88](https://linux-hardware.org/?probe=72d9d5cf88) | Oct 20, 2020 |
| Apple         | MacBook5,2                  | [743c634d73](https://linux-hardware.org/?probe=743c634d73) | Oct 10, 2020 |
| Apple         | MacBookPro8,1               | [bdcba0b93e](https://linux-hardware.org/?probe=bdcba0b93e) | Oct 08, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ba00de031e](https://linux-hardware.org/?probe=ba00de031e) | Oct 05, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| Samsung       | 850XBD                      | [0f37b12bcf](https://linux-hardware.org/?probe=0f37b12bcf) | Sep 25, 2020 |
| Samsung       | 850XBD                      | [6d3aecebe1](https://linux-hardware.org/?probe=6d3aecebe1) | Sep 25, 2020 |
| Dell          | Latitude E5440              | [ce030d4ddf](https://linux-hardware.org/?probe=ce030d4ddf) | Sep 21, 2020 |
| Toshiba       | Satellite C55t-A            | [74cf1c0699](https://linux-hardware.org/?probe=74cf1c0699) | Sep 16, 2020 |
| ASUSTek       | X550JX                      | [73576f6c41](https://linux-hardware.org/?probe=73576f6c41) | Sep 09, 2020 |
| HP            | ProBook 6460b               | [dd1da16f74](https://linux-hardware.org/?probe=dd1da16f74) | Sep 06, 2020 |
| Dell          | Inspiron 5565               | [61e0f4dfb2](https://linux-hardware.org/?probe=61e0f4dfb2) | Sep 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [e5e4260a64](https://linux-hardware.org/?probe=e5e4260a64) | Sep 04, 2020 |
| Lenovo        | ThinkPad T480 20L50018US    | [3e3f5cb909](https://linux-hardware.org/?probe=3e3f5cb909) | Sep 04, 2020 |
| Dell          | Latitude E5540              | [7f237410a4](https://linux-hardware.org/?probe=7f237410a4) | Sep 03, 2020 |
| ASUSTek       | X441BA                      | [e244d30598](https://linux-hardware.org/?probe=e244d30598) | Sep 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [51aa00a8f0](https://linux-hardware.org/?probe=51aa00a8f0) | Sep 03, 2020 |
| Acer          | Swift SF313-52              | [c03f9b4cc4](https://linux-hardware.org/?probe=c03f9b4cc4) | Aug 30, 2020 |
| Dell          | Inspiron 3585               | [4c1c8da34d](https://linux-hardware.org/?probe=4c1c8da34d) | Aug 28, 2020 |
| Dell          | Latitude E6400              | [097649e115](https://linux-hardware.org/?probe=097649e115) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | [adcbc1af5f](https://linux-hardware.org/?probe=adcbc1af5f) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | [b2a99bdee8](https://linux-hardware.org/?probe=b2a99bdee8) | Aug 25, 2020 |
| ASUSTek       | X501U                       | [11b77977b4](https://linux-hardware.org/?probe=11b77977b4) | Aug 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4dc08dfc6f](https://linux-hardware.org/?probe=4dc08dfc6f) | Aug 22, 2020 |
| HP            | ProBook 450 G7              | [caa355d2ed](https://linux-hardware.org/?probe=caa355d2ed) | Aug 21, 2020 |
| HP            | 250 G4                      | [24615bedce](https://linux-hardware.org/?probe=24615bedce) | Aug 19, 2020 |
| HP            | 250 G4                      | [bdadaddd2d](https://linux-hardware.org/?probe=bdadaddd2d) | Aug 18, 2020 |
| Apple         | MacBook2,1                  | [86447b8ed9](https://linux-hardware.org/?probe=86447b8ed9) | Aug 17, 2020 |
| Apple         | MacBook2,1                  | [e623d56bad](https://linux-hardware.org/?probe=e623d56bad) | Aug 17, 2020 |
| Gigabyte      | AERO 15-WA                  | [1843d38083](https://linux-hardware.org/?probe=1843d38083) | Aug 10, 2020 |
| Apple         | MacBook6,1                  | [8ae138eceb](https://linux-hardware.org/?probe=8ae138eceb) | Aug 10, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.4.0-42-generic          | 13        | 8.02%   |
| 5.4.0-65-generic          | 10        | 6.17%   |
| 5.4.0-58-generic          | 9         | 5.56%   |
| 5.4.0-52-generic          | 9         | 5.56%   |
| 5.4.0-73-generic          | 7         | 4.32%   |
| 5.4.0-56-generic          | 7         | 4.32%   |
| 5.4.0-80-generic          | 6         | 3.7%    |
| 5.4.0-72-generic          | 6         | 3.7%    |
| 5.4.0-66-generic          | 5         | 3.09%   |
| 5.4.0-48-generic          | 5         | 3.09%   |
| 5.4.0-81-generic          | 4         | 2.47%   |
| 5.4.0-70-generic          | 4         | 2.47%   |
| 5.4.0-54-generic          | 4         | 2.47%   |
| 5.4.0-74-generic          | 3         | 1.85%   |
| 5.4.0-67-generic          | 3         | 1.85%   |
| 5.4.0-64-generic          | 3         | 1.85%   |
| 5.4.0-60-generic          | 3         | 1.85%   |
| 5.4.0-47-generic          | 3         | 1.85%   |
| 5.4.0-92-generic          | 2         | 1.23%   |
| 5.4.0-90-generic          | 2         | 1.23%   |
| 5.4.0-77-generic          | 2         | 1.23%   |
| 5.4.0-59-generic          | 2         | 1.23%   |
| 5.4.0-53-generic          | 2         | 1.23%   |
| 5.4.0-51-generic          | 2         | 1.23%   |
| 5.4.0-45-generic          | 2         | 1.23%   |
| 5.4.0-135-generic         | 2         | 1.23%   |
| 5.4.0-131-generic         | 2         | 1.23%   |
| 5.4.0-120-generic         | 2         | 1.23%   |
| 5.3.0-62-generic          | 2         | 1.23%   |
| 5.10.0-051000-generic     | 2         | 1.23%   |
| 4.15.0-128-generic        | 2         | 1.23%   |
| 4.15.0-112-generic        | 2         | 1.23%   |
| 5.9.1-050901-generic      | 1         | 0.62%   |
| 5.8.5-050805-generic      | 1         | 0.62%   |
| 5.8.13-050813-generic     | 1         | 0.62%   |
| 5.8.0-17.2-liquorix-amd64 | 1         | 0.62%   |
| 5.6.19-050619-generic     | 1         | 0.62%   |
| 5.4.0-97-generic          | 1         | 0.62%   |
| 5.4.0-96-generic          | 1         | 0.62%   |
| 5.4.0-91-generic          | 1         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 124       | 82.12%  |
| 4.15.0  | 12        | 7.95%   |
| 5.3.0   | 4         | 2.65%   |
| 5.10.0  | 3         | 1.99%   |
| 5.9.1   | 1         | 0.66%   |
| 5.8.5   | 1         | 0.66%   |
| 5.8.13  | 1         | 0.66%   |
| 5.8.0   | 1         | 0.66%   |
| 5.6.19  | 1         | 0.66%   |
| 5.15.5  | 1         | 0.66%   |
| 5.14.9  | 1         | 0.66%   |
| 5.10.4  | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 124       | 82.12%  |
| 4.15    | 12        | 7.95%   |
| 5.3     | 4         | 2.65%   |
| 5.10    | 4         | 2.65%   |
| 5.8     | 3         | 1.99%   |
| 5.9     | 1         | 0.66%   |
| 5.6     | 1         | 0.66%   |
| 5.15    | 1         | 0.66%   |
| 5.14    | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 148       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Pantheon   | 125       | 83.33%  |
| Unknown    | 20        | 13.33%  |
| X-Cinnamon | 2         | 1.33%   |
| Unity      | 1         | 0.67%   |
| GNOME      | 1         | 0.67%   |
| Budgie     | 1         | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 147       | 99.32%  |
| Unknown | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 111       | 73.51%  |
| TDM     | 24        | 15.89%  |
| LightDM | 16        | 10.6%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 62        | 41.89%  |
| en_GB | 10        | 6.76%   |
| ru_RU | 8         | 5.41%   |
| pt_BR | 8         | 5.41%   |
| pl_PL | 6         | 4.05%   |
| es_ES | 6         | 4.05%   |
| en_IN | 6         | 4.05%   |
| en_AU | 6         | 4.05%   |
| de_DE | 6         | 4.05%   |
| it_IT | 4         | 2.7%    |
| fr_FR | 4         | 2.7%    |
| hu_HU | 2         | 1.35%   |
| es_MX | 2         | 1.35%   |
| es_EC | 2         | 1.35%   |
| en_ZA | 2         | 1.35%   |
| en_CA | 2         | 1.35%   |
| tr_TR | 1         | 0.68%   |
| ru_UA | 1         | 0.68%   |
| hr_HR | 1         | 0.68%   |
| fr_CA | 1         | 0.68%   |
| es_UY | 1         | 0.68%   |
| es_PE | 1         | 0.68%   |
| es_AR | 1         | 0.68%   |
| en_PH | 1         | 0.68%   |
| el_GR | 1         | 0.68%   |
| de_IT | 1         | 0.68%   |
| de_AT | 1         | 0.68%   |
| ca_ES | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 75        | 50.68%  |
| EFI  | 73        | 49.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 140       | 94.59%  |
| Btrfs   | 4         | 2.7%    |
| Overlay | 3         | 2.03%   |
| Ext3    | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 118       | 79.19%  |
| GPT     | 23        | 15.44%  |
| MBR     | 8         | 5.37%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 94.59%  |
| Yes       | 8         | 5.41%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 118       | 79.19%  |
| Yes       | 31        | 20.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 18.24%  |
| Hewlett-Packard     | 27        | 18.24%  |
| Dell                | 22        | 14.86%  |
| Acer                | 16        | 10.81%  |
| ASUSTek Computer    | 14        | 9.46%   |
| Apple               | 14        | 9.46%   |
| Toshiba             | 8         | 5.41%   |
| Samsung Electronics | 4         | 2.7%    |
| Star Labs           | 1         | 0.68%   |
| Sony                | 1         | 0.68%   |
| Positivo            | 1         | 0.68%   |
| Panasonic           | 1         | 0.68%   |
| MSI                 | 1         | 0.68%   |
| LG Electronics      | 1         | 0.68%   |
| HUAWEI              | 1         | 0.68%   |
| Hampoo              | 1         | 0.68%   |
| Google              | 1         | 0.68%   |
| Gigabyte Technology | 1         | 0.68%   |
| Fujitsu Siemens     | 1         | 0.68%   |
| Fujitsu             | 1         | 0.68%   |
| Compaq              | 1         | 0.68%   |
| Clevo               | 1         | 0.68%   |
| Chuwi               | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                           | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                            | 3         | 2.03%   |
| Apple MacBook2,1                               | 3         | 2.03%   |
| HP Pavilion dv7                                | 2         | 1.35%   |
| HP Laptop 17-by3xxx                            | 2         | 1.35%   |
| Dell Latitude E6400                            | 2         | 1.35%   |
| Apple MacBook7,1                               | 2         | 1.35%   |
| Acer Aspire R3-131T                            | 2         | 1.35%   |
| Acer Aspire F5-573G                            | 2         | 1.35%   |
| Acer AOD255E                                   | 2         | 1.35%   |
| Toshiba Satellite R630                         | 1         | 0.68%   |
| Toshiba Satellite P750                         | 1         | 0.68%   |
| Toshiba Satellite L855                         | 1         | 0.68%   |
| Toshiba Satellite L500                         | 1         | 0.68%   |
| Toshiba Satellite C870-1H2                     | 1         | 0.68%   |
| Toshiba Satellite C850D-119                    | 1         | 0.68%   |
| Toshiba Satellite C55t-A                       | 1         | 0.68%   |
| Toshiba QOSMIO G55                             | 1         | 0.68%   |
| Star Labs Lite                                 | 1         | 0.68%   |
| Sony VPCF23JFX                                 | 1         | 0.68%   |
| Samsung 850XBD                                 | 1         | 0.68%   |
| Samsung 530U3C/530U4C/532U3C                   | 1         | 0.68%   |
| Samsung 350V5C/351V5C/3540VC/3440VC            | 1         | 0.68%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 1         | 0.68%   |
| Positivo S14SL01                               | 1         | 0.68%   |
| Panasonic CF-31SBLJGDM                         | 1         | 0.68%   |
| MSI GE60 2PE                                   | 1         | 0.68%   |
| LG R490-G.ARL5RE2                              | 1         | 0.68%   |
| Lenovo V15-IIL 82C5                            | 1         | 0.68%   |
| Lenovo V15-ADA 82C7                            | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AMS0XP0S                | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AMA0XK00                | 1         | 0.68%   |
| Lenovo ThinkPad X13 Gen 1 20UF0013US           | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDS1WX00       | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS03P00       | 1         | 0.68%   |
| Lenovo ThinkPad T530 2429JB5                   | 1         | 0.68%   |
| Lenovo ThinkPad T480 20L50018US                | 1         | 0.68%   |
| Lenovo ThinkPad T480 20L50007RT                | 1         | 0.68%   |
| Lenovo ThinkPad T460 20FMS6C200                | 1         | 0.68%   |
| Lenovo ThinkPad T440p 20AWS1HK0P               | 1         | 0.68%   |
| Lenovo ThinkPad T440 20B7S0JF0L                | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 11.49%  |
| Acer Aspire            | 10        | 6.76%   |
| Dell Latitude          | 9         | 6.08%   |
| HP Pavilion            | 8         | 5.41%   |
| Toshiba Satellite      | 7         | 4.73%   |
| Lenovo IdeaPad         | 5         | 3.38%   |
| HP ProBook             | 5         | 3.38%   |
| Dell Inspiron          | 5         | 3.38%   |
| HP EliteBook           | 4         | 2.7%    |
| HP 250                 | 3         | 2.03%   |
| Dell XPS               | 3         | 2.03%   |
| Dell Vostro            | 3         | 2.03%   |
| Apple MacBookPro8      | 3         | 2.03%   |
| Apple MacBook2         | 3         | 2.03%   |
| Acer Swift             | 3         | 2.03%   |
| HP Laptop              | 2         | 1.35%   |
| ASUS ZenBook           | 2         | 1.35%   |
| ASUS VivoBook          | 2         | 1.35%   |
| Apple MacBook7         | 2         | 1.35%   |
| Acer AOD255E           | 2         | 1.35%   |
| Toshiba QOSMIO         | 1         | 0.68%   |
| Star Labs Lite         | 1         | 0.68%   |
| Sony VPCF23JFX         | 1         | 0.68%   |
| Samsung 850XBD         | 1         | 0.68%   |
| Samsung 530U3C         | 1         | 0.68%   |
| Samsung 350V5C         | 1         | 0.68%   |
| Samsung 300E5EV        | 1         | 0.68%   |
| Positivo S14SL01       | 1         | 0.68%   |
| Panasonic CF-31SBLJGDM | 1         | 0.68%   |
| MSI GE60               | 1         | 0.68%   |
| LG R490-G.ARL5RE2      | 1         | 0.68%   |
| Lenovo V15-IIL         | 1         | 0.68%   |
| Lenovo V15-ADA         | 1         | 0.68%   |
| Lenovo IdeaPadFlex     | 1         | 0.68%   |
| Lenovo G50-45          | 1         | 0.68%   |
| Lenovo 3000            | 1         | 0.68%   |
| HUAWEI HLY-WX9XX       | 1         | 0.68%   |
| HP ZBook               | 1         | 0.68%   |
| HP Presario            | 1         | 0.68%   |
| HP Notebook            | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 10.14%  |
| 2013 | 15        | 10.14%  |
| 2020 | 14        | 9.46%   |
| 2018 | 14        | 9.46%   |
| 2011 | 14        | 9.46%   |
| 2012 | 13        | 8.78%   |
| 2016 | 12        | 8.11%   |
| 2015 | 9         | 6.08%   |
| 2014 | 9         | 6.08%   |
| 2010 | 8         | 5.41%   |
| 2008 | 8         | 5.41%   |
| 2009 | 6         | 4.05%   |
| 2007 | 5         | 3.38%   |
| 2017 | 4         | 2.7%    |
| 2021 | 1         | 0.68%   |
| 2006 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 148       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 144       | 97.3%   |
| Enabled  | 4         | 2.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 147       | 99.32%  |
| Yes  | 1         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 43        | 29.05%  |
| 3.01-4.0   | 34        | 22.97%  |
| 8.01-16.0  | 27        | 18.24%  |
| 16.01-24.0 | 25        | 16.89%  |
| 1.01-2.0   | 10        | 6.76%   |
| 32.01-64.0 | 4         | 2.7%    |
| 2.01-3.0   | 3         | 2.03%   |
| 0.51-1.0   | 2         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 58        | 37.66%  |
| 2.01-3.0  | 44        | 28.57%  |
| 3.01-4.0  | 26        | 16.88%  |
| 4.01-8.0  | 16        | 10.39%  |
| 0.51-1.0  | 6         | 3.9%    |
| 8.01-16.0 | 4         | 2.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 105       | 70.95%  |
| 2      | 39        | 26.35%  |
| 0      | 2         | 1.35%   |
| 5      | 1         | 0.68%   |
| 3      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 60.14%  |
| Yes       | 59        | 39.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 82.43%  |
| No        | 26        | 17.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 97.97%  |
| No        | 3         | 2.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 79.19%  |
| No        | 31        | 20.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 18        | 12.16%  |
| Germany      | 10        | 6.76%   |
| UK           | 9         | 6.08%   |
| Brazil       | 9         | 6.08%   |
| India        | 8         | 5.41%   |
| Spain        | 7         | 4.73%   |
| Russia       | 6         | 4.05%   |
| Poland       | 6         | 4.05%   |
| Mexico       | 6         | 4.05%   |
| Italy        | 6         | 4.05%   |
| Indonesia    | 5         | 3.38%   |
| Australia    | 5         | 3.38%   |
| Ukraine      | 4         | 2.7%    |
| Turkey       | 4         | 2.7%    |
| France       | 4         | 2.7%    |
| Peru         | 3         | 2.03%   |
| Netherlands  | 3         | 2.03%   |
| Canada       | 3         | 2.03%   |
| South Africa | 2         | 1.35%   |
| Malaysia     | 2         | 1.35%   |
| Hungary      | 2         | 1.35%   |
| Greece       | 2         | 1.35%   |
| Ecuador      | 2         | 1.35%   |
| Uruguay      | 1         | 0.68%   |
| UAE          | 1         | 0.68%   |
| Tajikistan   | 1         | 0.68%   |
| Sweden       | 1         | 0.68%   |
| Slovakia     | 1         | 0.68%   |
| Saudi Arabia | 1         | 0.68%   |
| Romania      | 1         | 0.68%   |
| Portugal     | 1         | 0.68%   |
| Philippines  | 1         | 0.68%   |
| Nicaragua    | 1         | 0.68%   |
| New Zealand  | 1         | 0.68%   |
| Latvia       | 1         | 0.68%   |
| Kenya        | 1         | 0.68%   |
| Israel       | 1         | 0.68%   |
| Ireland      | 1         | 0.68%   |
| Hong Kong    | 1         | 0.68%   |
| Georgia      | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Warsaw         | 2         | 1.32%   |
| Perth          | 2         | 1.32%   |
| Montreal       | 2         | 1.32%   |
| Milan          | 2         | 1.32%   |
| Melbourne      | 2         | 1.32%   |
| Lima           | 2         | 1.32%   |
| Jaipur         | 2         | 1.32%   |
| Hamburg        | 2         | 1.32%   |
| Eskişehir     | 2         | 1.32%   |
| Cape Town      | 2         | 1.32%   |
| Ames           | 2         | 1.32%   |
| Zaragoza       | 1         | 0.66%   |
| Zagreb         | 1         | 0.66%   |
| York           | 1         | 0.66%   |
| Yogyakarta     | 1         | 0.66%   |
| Wellington     | 1         | 0.66%   |
| Villahermosa   | 1         | 0.66%   |
| Vienna         | 1         | 0.66%   |
| Vernon         | 1         | 0.66%   |
| Valencia       | 1         | 0.66%   |
| Torun          | 1         | 0.66%   |
| Tirupur        | 1         | 0.66%   |
| Tijuana        | 1         | 0.66%   |
| SГЈo Pedro   | 1         | 0.66%   |
| Surabaya       | 1         | 0.66%   |
| Sungai Petani  | 1         | 0.66%   |
| Stuttgart      | 1         | 0.66%   |
| Solna          | 1         | 0.66%   |
| Simferopol     | 1         | 0.66%   |
| Shelekhov      | 1         | 0.66%   |
| Serres         | 1         | 0.66%   |
| Sao Luís      | 1         | 0.66%   |
| Santos         | 1         | 0.66%   |
| Santo André   | 1         | 0.66%   |
| Santa Rosa     | 1         | 0.66%   |
| Rotterdam      | 1         | 0.66%   |
| Rome           | 1         | 0.66%   |
| Riyadh         | 1         | 0.66%   |
| Rio de Janeiro | 1         | 0.66%   |
| Riga           | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 25        | 29     | 13.89%  |
| SanDisk             | 21        | 23     | 11.67%  |
| Kingston            | 16        | 16     | 8.89%   |
| Samsung Electronics | 15        | 18     | 8.33%   |
| WDC                 | 13        | 15     | 7.22%   |
| Seagate             | 13        | 16     | 7.22%   |
| Unknown             | 12        | 14     | 6.67%   |
| Hitachi             | 10        | 11     | 5.56%   |
| Crucial             | 10        | 12     | 5.56%   |
| Intel               | 8         | 9      | 4.44%   |
| HGST                | 7         | 8      | 3.89%   |
| SK hynix            | 3         | 3      | 1.67%   |
| KIOXIA              | 3         | 8      | 1.67%   |
| Fujitsu             | 3         | 3      | 1.67%   |
| Apple               | 3         | 3      | 1.67%   |
| Micron Technology   | 2         | 3      | 1.11%   |
| A-DATA Technology   | 2         | 2      | 1.11%   |
| V-GeN               | 1         | 1      | 0.56%   |
| TO Exter            | 1         | 1      | 0.56%   |
| Star                | 1         | 1      | 0.56%   |
| SPCC                | 1         | 1      | 0.56%   |
| PNY                 | 1         | 1      | 0.56%   |
| Phison              | 1         | 1      | 0.56%   |
| Patriot             | 1         | 1      | 0.56%   |
| NGFF                | 1         | 1      | 0.56%   |
| LITEON              | 1         | 1      | 0.56%   |
| JMicron Technology  | 1         | 1      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| Gigabyte Technology | 1         | 1      | 0.56%   |
| ADATA Technology    | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                  | 6         | 3.26%   |
| SanDisk NVMe SSD Drive 256GB            | 4         | 2.17%   |
| Samsung NVMe SSD Drive 512GB            | 4         | 2.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 1.63%   |
| Unknown MMC Card  64GB                  | 3         | 1.63%   |
| Unknown MMC Card  32GB                  | 3         | 1.63%   |
| SanDisk NVMe SSD Drive 512GB            | 3         | 1.63%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 1.63%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 1.09%   |
| Unknown MMC Card  16GB                  | 2         | 1.09%   |
| Toshiba THNSNJ128GCSU 128GB SSD         | 2         | 1.09%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 1.09%   |
| Toshiba MQ01ABF050 500GB                | 2         | 1.09%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 1.09%   |
| Seagate ST500LM000-1EJ162 500GB         | 2         | 1.09%   |
| Seagate ST320LT007-9ZV142 320GB         | 2         | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 1.09%   |
| Samsung SSD 860 EVO 500GB               | 2         | 1.09%   |
| Samsung SSD 850 EVO 250GB               | 2         | 1.09%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 1.09%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 1.09%   |
| Hitachi HTS545025B9A300 250GB           | 2         | 1.09%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.09%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.09%   |
| HGST HTS541010A9E680 1TB                | 2         | 1.09%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 1.09%   |
| Crucial CT2000MX500SSD1 2TB             | 2         | 1.09%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.09%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.54%   |
| WDC WD5000LUCT-63RC2Y0 500GB            | 1         | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.54%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.54%   |
| WDC WD5000BPVT-75HXZT3 500GB            | 1         | 0.54%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.54%   |
| V-GeN V-GEN07SM20AR128SDK 128GB SSD     | 1         | 0.54%   |
| Unknown SD64G  64GB                     | 1         | 0.54%   |
| Unknown SC32G  32GB                     | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 20        | 24     | 31.75%  |
| Seagate             | 13        | 15     | 20.63%  |
| Hitachi             | 10        | 11     | 15.87%  |
| WDC                 | 8         | 10     | 12.7%   |
| HGST                | 7         | 8      | 11.11%  |
| Fujitsu             | 3         | 3      | 4.76%   |
| Samsung Electronics | 1         | 3      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 13        | 15     | 17.33%  |
| Kingston            | 13        | 13     | 17.33%  |
| Crucial             | 10        | 12     | 13.33%  |
| Samsung Electronics | 9         | 10     | 12%     |
| WDC                 | 5         | 5      | 6.67%   |
| Intel               | 5         | 5      | 6.67%   |
| Toshiba             | 2         | 2      | 2.67%   |
| Apple               | 2         | 2      | 2.67%   |
| A-DATA Technology   | 2         | 2      | 2.67%   |
| V-GeN               | 1         | 1      | 1.33%   |
| TO Exter            | 1         | 1      | 1.33%   |
| Star                | 1         | 1      | 1.33%   |
| SPCC                | 1         | 1      | 1.33%   |
| SK hynix            | 1         | 1      | 1.33%   |
| PNY                 | 1         | 1      | 1.33%   |
| Patriot             | 1         | 1      | 1.33%   |
| NGFF                | 1         | 1      | 1.33%   |
| Micron Technology   | 1         | 2      | 1.33%   |
| LITEON              | 1         | 1      | 1.33%   |
| JMicron Technology  | 1         | 1      | 1.33%   |
| Intenso             | 1         | 1      | 1.33%   |
| Hewlett-Packard     | 1         | 1      | 1.33%   |
| Gigabyte Technology | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 69        | 81     | 40.12%  |
| HDD     | 61        | 75     | 35.47%  |
| NVMe    | 29        | 36     | 16.86%  |
| MMC     | 12        | 14     | 6.98%   |
| Unknown | 1         | 1      | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 117       | 150    | 72.22%  |
| NVMe | 29        | 36     | 17.9%   |
| MMC  | 12        | 14     | 7.41%   |
| SAS  | 4         | 7      | 2.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 93        | 113    | 71.54%  |
| 0.51-1.0   | 33        | 38     | 25.38%  |
| 1.01-2.0   | 3         | 3      | 2.31%   |
| 3.01-4.0   | 1         | 2      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 34.23%  |
| 251-500        | 45        | 30.2%   |
| 501-1000       | 14        | 9.4%    |
| 51-100         | 14        | 9.4%    |
| 21-50          | 11        | 7.38%   |
| 1001-2000      | 5         | 3.36%   |
| 1-20           | 4         | 2.68%   |
| More than 3000 | 3         | 2.01%   |
| 2001-3000      | 2         | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 52        | 33.55%  |
| 21-50     | 47        | 30.32%  |
| 101-250   | 21        | 13.55%  |
| 51-100    | 18        | 11.61%  |
| 251-500   | 9         | 5.81%   |
| 501-1000  | 4         | 2.58%   |
| 2001-3000 | 2         | 1.29%   |
| 1001-2000 | 2         | 1.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 33.33%  |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 33.33%  |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 66.67%  |
| SanDisk | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Detected | 121       | 168    | 80.67%  |
| Works    | 26        | 36     | 17.33%  |
| Malfunc  | 3         | 3      | 2%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 113       | 70.63%  |
| AMD                          | 12        | 7.5%    |
| SanDisk                      | 8         | 5%      |
| Samsung Electronics          | 7         | 4.38%   |
| Nvidia                       | 5         | 3.13%   |
| Toshiba America Info Systems | 4         | 2.5%    |
| KIOXIA                       | 3         | 1.88%   |
| Kingston Technology Company  | 3         | 1.88%   |
| SK hynix                     | 2         | 1.25%   |
| Phison Electronics           | 1         | 0.63%   |
| Micron Technology            | 1         | 0.63%   |
| ADATA Technology             | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 10.59%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 8.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 7.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 7.06%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 6.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 5.88%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 3.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.94%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 1.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.76%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 1.76%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.76%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.18%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.18%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 1.18%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.18%   |
| Nvidia MCP89 SATA Controller                                                     | 2         | 1.18%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.18%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.59%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.59%   |
| Samsung Electronics SATA controller                                              | 1         | 0.59%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.59%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.59%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.59%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 110       | 65.87%  |
| NVMe | 30        | 17.96%  |
| IDE  | 14        | 8.38%   |
| RAID | 13        | 7.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 89.86%  |
| AMD    | 15        | 10.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 3.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 2.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 2.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.03%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 2.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 2.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 2.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.03%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 2.03%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.35%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.35%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.35%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.35%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 1.35%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.35%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.35%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 2         | 1.35%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.35%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 1.35%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.35%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 1.35%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.35%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.68%   |
| Intel Genuine CPU U2700 @ 1.30GHz             | 1         | 0.68%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.68%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.68%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz            | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 44        | 29.73%  |
| Intel Core i7                        | 33        | 22.3%   |
| Intel Core i3                        | 17        | 11.49%  |
| Intel Core 2 Duo                     | 13        | 8.78%   |
| Intel Celeron                        | 8         | 5.41%   |
| Intel Atom                           | 5         | 3.38%   |
| Intel Core 2                         | 4         | 2.7%    |
| Other                                | 3         | 2.03%   |
| AMD Ryzen 5                          | 3         | 2.03%   |
| Intel Pentium Dual-Core              | 2         | 1.35%   |
| Intel Pentium                        | 2         | 1.35%   |
| AMD Ryzen 7                          | 2         | 1.35%   |
| Intel Pentium Silver                 | 1         | 0.68%   |
| Intel Genuine                        | 1         | 0.68%   |
| Intel Core m3                        | 1         | 0.68%   |
| Intel Celeron Dual-Core              | 1         | 0.68%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.68%   |
| AMD Ryzen 5 PRO                      | 1         | 0.68%   |
| AMD Ryzen 3                          | 1         | 0.68%   |
| AMD E1                               | 1         | 0.68%   |
| AMD C-60                             | 1         | 0.68%   |
| AMD A8                               | 1         | 0.68%   |
| AMD A6                               | 1         | 0.68%   |
| AMD A12                              | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 95        | 64.19%  |
| 4      | 45        | 30.41%  |
| 6      | 5         | 3.38%   |
| 1      | 3         | 2.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 148       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 71.62%  |
| 1      | 42        | 28.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 148       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 15.33%  |
| 0x306a9    | 16        | 10.67%  |
| 0x206a7    | 12        | 8%      |
| 0x1067a    | 12        | 8%      |
| 0x40651    | 9         | 6%      |
| 0x806ec    | 7         | 4.67%   |
| 0x706e5    | 6         | 4%      |
| 0x806ea    | 5         | 3.33%   |
| 0x806e9    | 5         | 3.33%   |
| 0x406e3    | 5         | 3.33%   |
| 0x306c3    | 5         | 3.33%   |
| 0x30678    | 5         | 3.33%   |
| 0x906ea    | 4         | 2.67%   |
| 0x6f6      | 4         | 2.67%   |
| 0x406c3    | 3         | 2%      |
| 0x306d4    | 3         | 2%      |
| 0x706a1    | 2         | 1.33%   |
| 0x20655    | 2         | 1.33%   |
| 0x106ca    | 2         | 1.33%   |
| 0x08108109 | 2         | 1.33%   |
| 0x08108102 | 2         | 1.33%   |
| 0x06006705 | 2         | 1.33%   |
| 0x05000119 | 2         | 1.33%   |
| 0x806eb    | 1         | 0.67%   |
| 0x806c1    | 1         | 0.67%   |
| 0x6fd      | 1         | 0.67%   |
| 0x6fb      | 1         | 0.67%   |
| 0x506e3    | 1         | 0.67%   |
| 0x40661    | 1         | 0.67%   |
| 0x20652    | 1         | 0.67%   |
| 0x08600106 | 1         | 0.67%   |
| 0x0810100b | 1         | 0.67%   |
| 0x07030105 | 1         | 0.67%   |
| 0x06006118 | 1         | 0.67%   |
| 0x02000057 | 1         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 28        | 18.92%  |
| IvyBridge       | 18        | 12.16%  |
| Haswell         | 17        | 11.49%  |
| SandyBridge     | 14        | 9.46%   |
| Penryn          | 14        | 9.46%   |
| Silvermont      | 10        | 6.76%   |
| Skylake         | 7         | 4.73%   |
| IceLake         | 7         | 4.73%   |
| Core            | 7         | 4.73%   |
| Zen+            | 4         | 2.7%    |
| Excavator       | 4         | 2.7%    |
| Westmere        | 3         | 2.03%   |
| Broadwell       | 3         | 2.03%   |
| Zen             | 2         | 1.35%   |
| Goldmont plus   | 2         | 1.35%   |
| Bonnell         | 2         | 1.35%   |
| Bobcat          | 2         | 1.35%   |
| Zen 2           | 1         | 0.68%   |
| TigerLake       | 1         | 0.68%   |
| Puma            | 1         | 0.68%   |
| K8 & K10 hybrid | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 120       | 70.18%  |
| Nvidia | 31        | 18.13%  |
| AMD    | 20        | 11.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 8.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 7.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 6.18%   |
| Intel UHD Graphics 620                                                                   | 8         | 4.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 4.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.93%   |
| Intel HD Graphics 620                                                                    | 6         | 3.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.69%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 1.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.69%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 1.12%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.12%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 1.12%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1.12%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.12%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.12%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.56%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.56%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.56%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 65.54%  |
| Intel + Nvidia | 21        | 14.19%  |
| 1 x AMD        | 17        | 11.49%  |
| 1 x Nvidia     | 10        | 6.76%   |
| Intel + AMD    | 2         | 1.35%   |
| 2 x AMD        | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 126       | 85.14%  |
| Proprietary | 18        | 12.16%  |
| Unknown     | 4         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 68.46%  |
| 1.01-2.0   | 17        | 11.41%  |
| 0.01-0.5   | 14        | 9.4%    |
| 0.51-1.0   | 10        | 6.71%   |
| 3.01-4.0   | 5         | 3.36%   |
| 2.01-3.0   | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 15.82%  |
| BOE                     | 24        | 15.19%  |
| LG Display              | 22        | 13.92%  |
| Chimei Innolux          | 21        | 13.29%  |
| Samsung Electronics     | 19        | 12.03%  |
| Apple                   | 14        | 8.86%   |
| Chi Mei Optoelectronics | 6         | 3.8%    |
| Sharp                   | 5         | 3.16%   |
| Unknown                 | 3         | 1.9%    |
| PANDA                   | 3         | 1.9%    |
| Dell                    | 3         | 1.9%    |
| Lenovo                  | 2         | 1.27%   |
| Hewlett-Packard         | 2         | 1.27%   |
| ___                     | 1         | 0.63%   |
| Toshiba                 | 1         | 0.63%   |
| Panasonic               | 1         | 0.63%   |
| LG Philips              | 1         | 0.63%   |
| Fujitsu Siemens         | 1         | 0.63%   |
| BenQ                    | 1         | 0.63%   |
| AOC                     | 1         | 0.63%   |
| Acer                    | 1         | 0.63%   |
| Unknown                 | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 1.89%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 3         | 1.89%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 1.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 1.26%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 2         | 1.26%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 1.26%   |
| ___ LCDTV16 ___0101 1920x1080                                            | 1         | 0.63%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                       | 1         | 0.63%   |
| Unknown LCD Monitor Toshiba Internal LCD 1680x945                        | 1         | 0.63%   |
| Unknown LCD Monitor NCP 1920x1080                                        | 1         | 0.63%   |
| Toshiba TV TSB010B 1920x1080 706x398mm 31.9-inch                         | 1         | 0.63%   |
| Sharp LCD Monitor SHP14CB 1920x1200 288x180mm 13.4-inch                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP13C1 1920x1200 366x229mm 17.0-inch                  | 1         | 0.63%   |
| Sharp HDMI SHP10A1 1360x768 700x390mm 31.5-inch                          | 1         | 0.63%   |
| Samsung Electronics U28E510 SAM0D63 1680x1050 610x350mm 27.7-inch        | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 459x296mm 21.5-inch     | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0560 1440x900 408x255mm 18.9-inch      | 1         | 0.63%   |
| Samsung Electronics LS32R75 SAM0F92 3840x2160 697x392mm 31.5-inch        | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3155 1366x768 293x165mm 13.2-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 0.63%   |
| PANDA LM116LF3L01 NCP000A 1920x1080 256x144mm 11.6-inch                  | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 54        | 35.29%  |
| 1920x1080 (FHD)    | 47        | 30.72%  |
| 1280x800 (WXGA)    | 16        | 10.46%  |
| 1600x900 (HD+)     | 9         | 5.88%   |
| 3840x2160 (4K)     | 7         | 4.58%   |
| 1440x900 (WXGA+)   | 4         | 2.61%   |
| 1920x1200 (WUXGA)  | 3         | 1.96%   |
| 1024x600           | 2         | 1.31%   |
| 3840x1080          | 1         | 0.65%   |
| 2880x1800          | 1         | 0.65%   |
| 2256x1504          | 1         | 0.65%   |
| 1920x515           | 1         | 0.65%   |
| 1920x1280          | 1         | 0.65%   |
| 1680x945           | 1         | 0.65%   |
| 1680x1050 (WSXGA+) | 1         | 0.65%   |
| 1600x1200          | 1         | 0.65%   |
| 1360x768           | 1         | 0.65%   |
| 1280x1024 (SXGA)   | 1         | 0.65%   |
| Unknown            | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 46        | 29.11%  |
| 13      | 44        | 27.85%  |
| 14      | 18        | 11.39%  |
| 17      | 10        | 6.33%   |
| Unknown | 7         | 4.43%   |
| 11      | 6         | 3.8%    |
| 24      | 4         | 2.53%   |
| 27      | 3         | 1.9%    |
| 23      | 3         | 1.9%    |
| 19      | 3         | 1.9%    |
| 72      | 2         | 1.27%   |
| 31      | 2         | 1.27%   |
| 18      | 2         | 1.27%   |
| 12      | 2         | 1.27%   |
| 10      | 2         | 1.27%   |
| 84      | 1         | 0.63%   |
| 22      | 1         | 0.63%   |
| 21      | 1         | 0.63%   |
| 16      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 85        | 54.49%  |
| 201-300     | 32        | 20.51%  |
| 351-400     | 12        | 7.69%   |
| 501-600     | 9         | 5.77%   |
| Unknown     | 7         | 4.49%   |
| 401-500     | 5         | 3.21%   |
| 601-700     | 3         | 1.92%   |
| 1501-2000   | 3         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 109       | 75.69%  |
| 16/10   | 24        | 16.67%  |
| Unknown | 6         | 4.17%   |
| 3/2     | 2         | 1.39%   |
| 5/4     | 1         | 0.69%   |
| 4/3     | 1         | 0.69%   |
| 3.73    | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 32.28%  |
| 101-110        | 47        | 29.75%  |
| 71-80          | 11        | 6.96%   |
| 201-250        | 9         | 5.7%    |
| Unknown        | 7         | 4.43%   |
| 51-60          | 6         | 3.8%    |
| 121-130        | 6         | 3.8%    |
| More than 1000 | 3         | 1.9%    |
| 301-350        | 3         | 1.9%    |
| 151-200        | 3         | 1.9%    |
| 141-150        | 3         | 1.9%    |
| 131-140        | 3         | 1.9%    |
| 61-70          | 2         | 1.27%   |
| 351-500        | 2         | 1.27%   |
| 41-50          | 2         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 71        | 45.81%  |
| 121-160       | 45        | 29.03%  |
| 51-100        | 18        | 11.61%  |
| 161-240       | 9         | 5.81%   |
| Unknown       | 7         | 4.52%   |
| 1-50          | 3         | 1.94%   |
| More than 240 | 2         | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 129       | 85.43%  |
| 2     | 19        | 12.58%  |
| 0     | 3         | 1.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 72        | 30.9%   |
| Intel                             | 70        | 30.04%  |
| Qualcomm Atheros                  | 39        | 16.74%  |
| Broadcom                          | 24        | 10.3%   |
| Nvidia                            | 5         | 2.15%   |
| Marvell Technology Group          | 5         | 2.15%   |
| Ralink                            | 3         | 1.29%   |
| Broadcom Limited                  | 2         | 0.86%   |
| Xiaomi                            | 1         | 0.43%   |
| TP-Link                           | 1         | 0.43%   |
| Sierra Wireless                   | 1         | 0.43%   |
| Samsung Electronics               | 1         | 0.43%   |
| Ralink Technology                 | 1         | 0.43%   |
| Qualcomm                          | 1         | 0.43%   |
| LG Electronics                    | 1         | 0.43%   |
| Huawei Technologies               | 1         | 0.43%   |
| Hewlett-Packard                   | 1         | 0.43%   |
| Fibocom                           | 1         | 0.43%   |
| Ericsson Business Mobile Networks | 1         | 0.43%   |
| ASIX Electronics                  | 1         | 0.43%   |
| Arduino SA                        | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 45        | 16.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 19        | 6.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 9         | 3.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 7         | 2.49%   |
| Intel Wireless 7260                                                                   | 7         | 2.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 1.78%   |
| Intel Wireless 8260                                                                   | 5         | 1.78%   |
| Intel Ethernet Connection I218-LM                                                     | 5         | 1.78%   |
| Intel Centrino Advanced-N 6235                                                        | 5         | 1.78%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.42%   |
| Intel Wireless 7265                                                                   | 4         | 1.42%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 1.42%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 4         | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.07%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 1.07%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 3         | 1.07%   |
| Nvidia MCP79 Ethernet                                                                 | 3         | 1.07%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 3         | 1.07%   |
| Intel Wireless 3165                                                                   | 3         | 1.07%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 1.07%   |
| Intel Ethernet Connection I219-LM                                                     | 3         | 1.07%   |
| Intel Ethernet Connection (4) I219-V                                                  | 3         | 1.07%   |
| Intel 82567LM Gigabit Network Connection                                              | 3         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 3         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 3         | 1.07%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 1.07%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 2         | 0.71%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 2         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 2         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.71%   |
| Nvidia MCP89 Ethernet                                                                 | 2         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 42.11%  |
| Qualcomm Atheros      | 35        | 23.03%  |
| Realtek Semiconductor | 22        | 14.47%  |
| Broadcom              | 22        | 14.47%  |
| Ralink                | 3         | 1.97%   |
| Broadcom Limited      | 2         | 1.32%   |
| TP-Link               | 1         | 0.66%   |
| Sierra Wireless       | 1         | 0.66%   |
| Ralink Technology     | 1         | 0.66%   |
| Fibocom               | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 5.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 7         | 4.61%   |
| Intel Wireless 7260                                                                   | 7         | 4.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 3.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 3.29%   |
| Intel Wireless 8260                                                                   | 5         | 3.29%   |
| Intel Centrino Advanced-N 6235                                                        | 5         | 3.29%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 2.63%   |
| Intel Wireless 7265                                                                   | 4         | 2.63%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 2.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 4         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.97%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 1.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 1.97%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 3         | 1.97%   |
| Intel Wireless 3165                                                                   | 3         | 1.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 1.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 3         | 1.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3         | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 1.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 1.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 1.32%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 2         | 1.32%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 1.32%   |
| Intel Wireless 3160                                                                   | 2         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 2         | 1.32%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 2         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 2         | 1.32%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 1.32%   |
| TP-Link 802.11ac WLAN Adapter                                                         | 1         | 0.66%   |
| Sierra Wireless MC7700                                                                | 1         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.66%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 51.59%  |
| Intel                    | 29        | 23.02%  |
| Qualcomm Atheros         | 8         | 6.35%   |
| Broadcom                 | 7         | 5.56%   |
| Nvidia                   | 5         | 3.97%   |
| Marvell Technology Group | 5         | 3.97%   |
| Xiaomi                   | 1         | 0.79%   |
| Samsung Electronics      | 1         | 0.79%   |
| Qualcomm                 | 1         | 0.79%   |
| LG Electronics           | 1         | 0.79%   |
| Huawei Technologies      | 1         | 0.79%   |
| Hewlett-Packard          | 1         | 0.79%   |
| ASIX Electronics         | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 35.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 14.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 7.09%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 3.94%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.36%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 2.36%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.36%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 2.36%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 2.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.57%   |
| Nvidia MCP89 Ethernet                                             | 2         | 1.57%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.79%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.79%   |
| Qualcomm MegaFon M150-4                                           | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.79%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.79%   |
| Huawei E353/E3131                                                 | 1         | 0.79%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.79%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.79%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.79%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 145       | 53.51%  |
| Ethernet | 124       | 45.76%  |
| Modem    | 2         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 134       | 89.93%  |
| Ethernet | 15        | 10.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 118       | 79.73%  |
| 1     | 27        | 18.24%  |
| 0     | 3         | 2.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 87.25%  |
| Yes  | 19        | 12.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 38.84%  |
| Apple                           | 14        | 11.57%  |
| Qualcomm Atheros Communications | 12        | 9.92%   |
| Realtek Semiconductor           | 9         | 7.44%   |
| Lite-On Technology              | 8         | 6.61%   |
| Broadcom                        | 7         | 5.79%   |
| Cambridge Silicon Radio         | 6         | 4.96%   |
| Toshiba                         | 3         | 2.48%   |
| Hewlett-Packard                 | 3         | 2.48%   |
| Foxconn / Hon Hai               | 3         | 2.48%   |
| IMC Networks                    | 2         | 1.65%   |
| Taiyo Yuden                     | 1         | 0.83%   |
| Realtek                         | 1         | 0.83%   |
| Ralink                          | 1         | 0.83%   |
| Qcom                            | 1         | 0.83%   |
| Logitech                        | 1         | 0.83%   |
| Fujitsu                         | 1         | 0.83%   |
| Dell                            | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 17.36%  |
| Apple Bluetooth Host Controller                                                     | 8         | 6.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 5.79%   |
| Intel AX201 Bluetooth                                                               | 7         | 5.79%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 4.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 4.96%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 4.13%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 3.31%   |
| Realtek Bluetooth Radio                                                             | 4         | 3.31%   |
| Intel AX200 Bluetooth                                                               | 4         | 3.31%   |
| Apple Bluetooth HCI                                                                 | 4         | 3.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.48%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 2.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.65%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.83%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.83%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.83%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.83%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.83%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.83%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.83%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.83%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.83%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.83%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.83%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.83%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.83%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.83%   |
| Fujitsu Bluetooth Device                                                            | 1         | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.83%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.83%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 125       | 75.76%  |
| Nvidia                     | 18        | 10.91%  |
| AMD                        | 18        | 10.91%  |
| YUAN High-Tech Development | 1         | 0.61%   |
| Native Instruments         | 1         | 0.61%   |
| Generalplus Technology     | 1         | 0.61%   |
| C-Media Electronics        | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 10.05%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 9.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 7.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 5.53%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 5.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 4.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 4.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 3.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 3.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.01%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.51%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.51%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.51%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.51%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.51%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.01%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.01%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.01%   |
| YUAN High-Tech Development YUAN FM100                                                             | 1         | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.5%    |
| Native Instruments Traktor Kontrol Z2                                                             | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 26.67%  |
| SK hynix            | 16        | 17.78%  |
| Micron Technology   | 12        | 13.33%  |
| Unknown             | 10        | 11.11%  |
| Kingston            | 7         | 7.78%   |
| Elpida              | 5         | 5.56%   |
| Unknown (ABCD)      | 2         | 2.22%   |
| Crucial             | 2         | 2.22%   |
| Transcend           | 1         | 1.11%   |
| Timetec             | 1         | 1.11%   |
| Smart               | 1         | 1.11%   |
| Ramaxel Technology  | 1         | 1.11%   |
| PNY                 | 1         | 1.11%   |
| Multilaser          | 1         | 1.11%   |
| Melco               | 1         | 1.11%   |
| Magnum Tech         | 1         | 1.11%   |
| Corsair             | 1         | 1.11%   |
| Avant               | 1         | 1.11%   |
| Aeneon              | 1         | 1.11%   |
| A-DATA Technology   | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 4.17%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 2         | 2.08%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 2         | 2.08%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 2.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.08%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 2.08%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 2.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1067MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.04%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s                   | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 3733MT/s             | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR3 667MT/s                    | 1         | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.04%   |
| Transcend RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.04%   |
| Timetec RAM SD4-2666 16GB SODIMM DDR4 2667MT/s                   | 1         | 1.04%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 1         | 1.04%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.04%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 1         | 1.04%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.04%   |
| SK hynix RAM Module 1024MB SODIMM DDR2 800MT/s                   | 1         | 1.04%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.04%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.04%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s                    | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 40        | 53.33%  |
| DDR4   | 19        | 25.33%  |
| DDR2   | 8         | 10.67%  |
| LPDDR4 | 4         | 5.33%   |
| LPDDR3 | 3         | 4%      |
| SDRAM  | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 90.54%  |
| Row Of Chips | 4         | 5.41%   |
| DIMM         | 3         | 4.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 32.94%  |
| 4096  | 27        | 31.76%  |
| 2048  | 17        | 20%     |
| 16384 | 7         | 8.24%   |
| 1024  | 5         | 5.88%   |
| 32768 | 1         | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 25        | 30.49%  |
| 2667  | 11        | 13.41%  |
| 1334  | 8         | 9.76%   |
| 2133  | 7         | 8.54%   |
| 667   | 7         | 8.54%   |
| 1333  | 5         | 6.1%    |
| 1067  | 5         | 6.1%    |
| 2400  | 4         | 4.88%   |
| 800   | 3         | 3.66%   |
| 3200  | 2         | 2.44%   |
| 4267  | 1         | 1.22%   |
| 4199  | 1         | 1.22%   |
| 3733  | 1         | 1.22%   |
| 1867  | 1         | 1.22%   |
| 1066  | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson XP-200 Series | 1         | 100%    |

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
| Chicony Electronics                    | 30        | 22.73%  |
| Realtek Semiconductor                  | 17        | 12.88%  |
| IMC Networks                           | 14        | 10.61%  |
| Sunplus Innovation Technology          | 10        | 7.58%   |
| Apple                                  | 10        | 7.58%   |
| Acer                                   | 8         | 6.06%   |
| Microdia                               | 7         | 5.3%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.55%   |
| Silicon Motion                         | 5         | 3.79%   |
| Quanta                                 | 5         | 3.79%   |
| Syntek                                 | 4         | 3.03%   |
| Suyin                                  | 3         | 2.27%   |
| Lite-On Technology                     | 3         | 2.27%   |
| Importek                               | 3         | 2.27%   |
| Alcor Micro                            | 2         | 1.52%   |
| Samsung Electronics                    | 1         | 0.76%   |
| Ricoh                                  | 1         | 0.76%   |
| LG Electronics                         | 1         | 0.76%   |
| Jieli Technology                       | 1         | 0.76%   |
| ALi                                    | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                         | 7         | 5.3%    |
| Chicony Integrated Camera                            | 6         | 4.55%   |
| Chicony HD WebCam                                    | 6         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 3.03%   |
| IMC Networks Integrated Camera                       | 4         | 3.03%   |
| Apple Built-in iSight                                | 4         | 3.03%   |
| Sunplus HD WebCam                                    | 3         | 2.27%   |
| Realtek HD WebCam                                    | 3         | 2.27%   |
| Apple iPhone5/5C/5S/6                                | 3         | 2.27%   |
| Apple FaceTime HD Camera                             | 3         | 2.27%   |
| Syntek Integrated Camera                             | 2         | 1.52%   |
| Syntek EasyCamera                                    | 2         | 1.52%   |
| Sunplus Laptop_Integrated_Webcam_HD                  | 2         | 1.52%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.52%   |
| Realtek USB Camera                                   | 2         | 1.52%   |
| Quanta HP Webcam                                     | 2         | 1.52%   |
| Microdia Integrated_Webcam_HD                        | 2         | 1.52%   |
| Importek TOSHIBA Web Camera - HD                     | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 2         | 1.52%   |
| Acer SunplusIT INC. Integrated Camera                | 2         | 1.52%   |
| Acer Integrated Camera                               | 2         | 1.52%   |
| Acer BisonCam, NB Pro                                | 2         | 1.52%   |
| Suyin UVC HD Webcam                                  | 1         | 0.76%   |
| Suyin HP Truevision HD                               | 1         | 0.76%   |
| Suyin HD Video WebCam                                | 1         | 0.76%   |
| Sunplus HP Universal Camera                          | 1         | 0.76%   |
| Sunplus Dell HD Webcam                               | 1         | 0.76%   |
| Sunplus Dell E5570 integrated webcam                 | 1         | 0.76%   |
| Silicon Motion WebCam SC-13HDL12131N                 | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD12636N                 | 1         | 0.76%   |
| Silicon Motion Web Camera                            | 1         | 0.76%   |
| Silicon Motion Lenovo EasyCamera                     | 1         | 0.76%   |
| Silicon Motion HP Webcam-101 Integrated Camera       | 1         | 0.76%   |
| Samsung Galaxy A5 (MTP)                              | 1         | 0.76%   |
| Ricoh USB2.0 Camera                                  | 1         | 0.76%   |
| Realtek USB2.0 HD UVC WebCam                         | 1         | 0.76%   |
| Realtek Integrated Webcam HD                         | 1         | 0.76%   |
| Realtek Integrated Webcam                            | 1         | 0.76%   |
| Realtek HP Webcam                                    | 1         | 0.76%   |
| Realtek HD Webcam - Realtek                          | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 44%     |
| Synaptics                  | 7         | 28%     |
| LighTuning Technology      | 3         | 12%     |
| Shenzhen Goodix Technology | 2         | 8%      |
| Elan Microelectronics      | 2         | 8%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 12%     |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 12%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 8%      |
| Validity Sensors VFS491                                                    | 2         | 8%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 8%      |
| Elan ELAN:Fingerprint                                                      | 2         | 8%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4%      |
| Validity Sensors Fingerprint scanner                                       | 1         | 4%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 4%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4%      |
| Shenzhen Goodix FingerPrint                                                | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 46.15%  |
| Alcor Micro | 3         | 23.08%  |
| O2 Micro    | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |
| Lenovo      | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 23.08%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 100       | 66.67%  |
| 1     | 40        | 26.67%  |
| 2     | 7         | 4.67%   |
| 3     | 3         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 24        | 38.71%  |
| Chipcard           | 13        | 20.97%  |
| Graphics card      | 10        | 16.13%  |
| Net/wireless       | 8         | 12.9%   |
| Camera             | 3         | 4.84%   |
| Storage            | 2         | 3.23%   |
| Net/ethernet       | 1         | 1.61%   |
| Bluetooth          | 1         | 1.61%   |

