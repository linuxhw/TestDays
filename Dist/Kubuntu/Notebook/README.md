Kubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Kubuntu.

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

Total: 3173

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| ASUSTek       | G551JM                      | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| Dell          | Latitude 7490               | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Dell          | Latitude E6500              | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| HP            | Notebook                    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [cdf37a1590](https://linux-hardware.org/?probe=cdf37a1590) | Sep 03, 2023 |
| Dell          | Latitude E6500              | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| Dell          | XPS 9315                    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| Avell High... | C62 MOB                     | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| mPTech        | ARC 11.6 128GB HD           | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z580                | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| Dell          | Precision 7780              | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| MSI           | GL65 9SE                    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Irbis         | NB123                       | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Dell          | Latitude E6520              | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| HP            | Laptop 17-ca1xxx            | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Schenker      | XMG PRO (E23)               | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Acer          | Nitro AN517-41              | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| Acer          | Aspire A515-51              | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Medion        | P651x series                | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Google        | Dragonair                   | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| GPD           | G1621-02                    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Precision 7670              | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| Dell          | Latitude E6420              | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| Dell          | Latitude 5530               | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| System76      | Galago Pro                  | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Alienware     | 14                          | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Dell          | Inspiron 16 7610            | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| HP            | G60                         | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Acer          | Aspire A515-45              | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| HP            | G62                         | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| HP            | Presario CQ62               | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| HP            | ENVY Notebook               | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| HP            | ZBook 17 G2                 | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| HP            | Pavilion 15                 | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| Dell          | G3 3779                     | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Unknown       | Unknown                     | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [9400bf75de](https://linux-hardware.org/?probe=9400bf75de) | Jul 09, 2023 |
| Acer          | Predator G3-572             | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Dell          | G3 3779                     | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| HP            | ProBook 650 G1              | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Dell          | Latitude 7530               | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Notebook      | PC5x_7xHP_HR_HS             | [e76be78ba9](https://linux-hardware.org/?probe=e76be78ba9) | Jul 02, 2023 |
| Dell          | G3 3779                     | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Dell          | G3 3779                     | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Dell          | Latitude E5450              | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| HP            | Laptop 14s-dq2xxx           | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Dell          | G3 3590                     | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| HP            | Notebook                    | [db641e216c](https://linux-hardware.org/?probe=db641e216c) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Dell          | Latitude 3310               | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Proline       | V1165C4                     | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Dell          | Latitude E6420              | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Irbis         | NB123                       | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Samsung       | 550XCJ/550XCR               | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Dell          | G3 3779                     | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Dell          | XPS 13 9333                 | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | Notebook                    | [1b099710b7](https://linux-hardware.org/?probe=1b099710b7) | Jun 08, 2023 |
| HP            | Notebook                    | [9bf82397c3](https://linux-hardware.org/?probe=9bf82397c3) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Acer          | Nitro AN515-56              | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| ASUSTek       | K50IJ                       | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| Dell          | Latitude E6500              | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Dell          | G15 5525                    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer          | Aspire A317-53              | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire E5-575               | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Acer          | Aspire A515-45              | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Google        | Bluebird                    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Acer          | Aspire V3-772               | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| Acer          | Aspire V3-772               | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Apple         | MacBookPro9,1               | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Acer          | Aspire A317-53              | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Fujitsu       | LIFEBOOK U748               | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| HP            | 350 G1                      | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME       | B95                         | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Notebook      | NLx0MU                      | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Dell          | Latitude E5530 non-vPro     | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Acer          | Swift SFX14-41G             | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | ENVY TS 15                  | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Dell          | XPS 15 7590                 | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| HP            | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Dell          | Latitude E6500              | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| PC Special... | P65_67RSRP                  | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| Dell          | G3 3590                     | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | Latitude E5470              | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Dell          | Latitude 5420               | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| HP            | EliteBook 8470p             | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| Dell          | Latitude 3570               | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Dell          | XPS 13 9300                 | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Google        | Lars                        | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Razer         | Blade Pro 17 (2019)         | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| HP            | ProBook 440 G5              | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Dell          | Latitude 5480               | [1ab8b910e4](https://linux-hardware.org/?probe=1ab8b910e4) | May 04, 2023 |
| ASUSTek       | X750JB                      | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| Dell          | Inspiron 3593               | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| Acer          | Aspire M5-481T              | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| Samsung       | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Dell          | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Carbon Sys... | Iridium 14                  | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | X510UAR                     | [d96138627b](https://linux-hardware.org/?probe=d96138627b) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| HP            | 630                         | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| Apple         | MacBookPro14,2              | [26a430e092](https://linux-hardware.org/?probe=26a430e092) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| ASUSTek       | X51RL                       | [ca3fb7f6d5](https://linux-hardware.org/?probe=ca3fb7f6d5) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Unknown       | Unknown                     | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| HP            | EliteBook 6930p             | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| Acer          | Aspire A515-45              | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Acer          | Aspire A515-57              | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Dell          | Vostro 15-3568              | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| MSI           | Modern 15 A5M               | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | Vostro 5620                 | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Avell High... | C62 MOB                     | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Clevo         | W340EU                      | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Clevo         | W340EU                      | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| Dell          | Latitude E6420              | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| HP            | Pavilion 11 x360 PC         | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| System76      | Gazelle                     | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Acer          | Aspire A515-46              | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Nitro AN515-45              | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Chuwi         | Hi10 Go                     | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Acer          | Nitro AN517-41              | [ecb7c49d2e](https://linux-hardware.org/?probe=ecb7c49d2e) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| Dell          | Inspiron 5593               | [36db3e5d78](https://linux-hardware.org/?probe=36db3e5d78) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [b265f91d10](https://linux-hardware.org/?probe=b265f91d10) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| ASUSTek       | GL503VD                     | [f4095c61ff](https://linux-hardware.org/?probe=f4095c61ff) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Medion        | E15410                      | [5ba9ffd6a8](https://linux-hardware.org/?probe=5ba9ffd6a8) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| Dell          | Latitude 5491               | [37746d7f71](https://linux-hardware.org/?probe=37746d7f71) | Jan 24, 2023 |
| Medion        | E15410                      | [f7e27f2ba9](https://linux-hardware.org/?probe=f7e27f2ba9) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [df35617170](https://linux-hardware.org/?probe=df35617170) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Dell          | Vostro 1014                 | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| Dell          | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Notebook                    | [1c935be3b1](https://linux-hardware.org/?probe=1c935be3b1) | Jan 18, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| Notebook      | W35xSS_370SS                | [2337667e0f](https://linux-hardware.org/?probe=2337667e0f) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3a97589bc9](https://linux-hardware.org/?probe=3a97589bc9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ed648f1f72](https://linux-hardware.org/?probe=ed648f1f72) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [b9df733a47](https://linux-hardware.org/?probe=b9df733a47) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [75209e7521](https://linux-hardware.org/?probe=75209e7521) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Dell          | Inspiron 5570               | [4ebc1e97c5](https://linux-hardware.org/?probe=4ebc1e97c5) | Jan 07, 2023 |
| Dell          | Inspiron 5570               | [86b0308f38](https://linux-hardware.org/?probe=86b0308f38) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| Acer          | Swift SF314-71              | [21ebb26df9](https://linux-hardware.org/?probe=21ebb26df9) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Acer          | Aspire M5-583P              | [1182d7305d](https://linux-hardware.org/?probe=1182d7305d) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Unknown       | Unknown                     | [7a85f424f5](https://linux-hardware.org/?probe=7a85f424f5) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [059e72c9a0](https://linux-hardware.org/?probe=059e72c9a0) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| MSI           | Alpha 17 B5EEK              | [a5881c627c](https://linux-hardware.org/?probe=a5881c627c) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion dv7                | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [60a56500f1](https://linux-hardware.org/?probe=60a56500f1) | Dec 18, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [89166d1da4](https://linux-hardware.org/?probe=89166d1da4) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c18a20ec35](https://linux-hardware.org/?probe=c18a20ec35) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| HP            | Pavilion g7                 | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| HP            | 550                         | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Monster       | TULPAR T7 V21.6             | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Google        | Kled                        | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Dell          | G3 3779                     | [3e85396dae](https://linux-hardware.org/?probe=3e85396dae) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| GPD           | G1621-02                    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| Dell          | Latitude E6440              | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| HP            | Unknown                     | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| Dell          | Inspiron 1545               | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| Dell          | Inspiron 1545               | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e7152e6cb3](https://linux-hardware.org/?probe=e7152e6cb3) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a30ec58d99](https://linux-hardware.org/?probe=a30ec58d99) | Nov 16, 2022 |
| Dell          | Latitude E7250              | [907a7245b4](https://linux-hardware.org/?probe=907a7245b4) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Acer          | Aspire V3-571G              | [ea0093a1f6](https://linux-hardware.org/?probe=ea0093a1f6) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Dell          | Precision 7510              | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Google        | Celes                       | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ffa33ab238](https://linux-hardware.org/?probe=ffa33ab238) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| HP            | Laptop 17-ca2xxx            | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a72c604f03](https://linux-hardware.org/?probe=a72c604f03) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8ba7f1aa17](https://linux-hardware.org/?probe=8ba7f1aa17) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Acer          | Aspire 5750                 | [83a24172bd](https://linux-hardware.org/?probe=83a24172bd) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HP            | Pavilion 17                 | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Dell          | Latitude E6320              | [b66269072e](https://linux-hardware.org/?probe=b66269072e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| Acer          | Aspire 5732Z                | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| HP            | 470 G8 Notebook PC          | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| HP            | Laptop 15-da2xxx            | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Haier         | A1420EM                     | [62ce3535b2](https://linux-hardware.org/?probe=62ce3535b2) | Oct 19, 2022 |
| Haier         | A1420EM                     | [a50bc27e31](https://linux-hardware.org/?probe=a50bc27e31) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Latitude E6420              | [f39e0305c5](https://linux-hardware.org/?probe=f39e0305c5) | Oct 13, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [7a11da121e](https://linux-hardware.org/?probe=7a11da121e) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| HP            | Compaq 15                   | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| HP            | Compaq 15                   | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| Intel         | W7645                       | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [76709f5d09](https://linux-hardware.org/?probe=76709f5d09) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 754       | 32.53%  |
| Kubuntu 22.04   | 562       | 24.25%  |
| Kubuntu 22.10   | 157       | 6.77%   |
| Kubuntu 21.10   | 151       | 6.51%   |
| Kubuntu 20.10   | 141       | 6.08%   |
| Kubuntu 21.04   | 126       | 5.44%   |
| Kubuntu 23.04   | 124       | 5.35%   |
| Kubuntu 19.10   | 105       | 4.53%   |
| Kubuntu 18.04   | 102       | 4.4%    |
| Kubuntu 11      | 48        | 2.07%   |
| Kubuntu 11.1    | 18        | 0.78%   |
| Kubuntu 19.04   | 9         | 0.39%   |
| Kubuntu 2.0     | 4         | 0.17%   |
| Kubuntu 16.04   | 4         | 0.17%   |
| Kubuntu 18.10   | 3         | 0.13%   |
| Kubuntu         | 3         | 0.13%   |
| Kubuntu 23.10   | 2         | 0.09%   |
| Kubuntu 14.04   | 2         | 0.09%   |
| Kubuntu 20.08.3 | 1         | 0.04%   |
| Kubuntu 17.10   | 1         | 0.04%   |
| Kubuntu 17.04   | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Kubuntu | 2225      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 55        | 2.17%   |
| 6.2.0-20-generic  | 53        | 2.09%   |
| 5.15.0-52-generic | 51        | 2.02%   |
| 5.15.0-56-generic | 44        | 1.74%   |
| 5.19.0-35-generic | 38        | 1.5%    |
| 5.4.0-52-generic  | 35        | 1.38%   |
| 5.13.0-39-generic | 35        | 1.38%   |
| 5.4.0-48-generic  | 34        | 1.34%   |
| 6.2.0-26-generic  | 32        | 1.26%   |
| 5.15.0-48-generic | 30        | 1.19%   |
| 5.19.0-26-generic | 28        | 1.11%   |
| 5.15.0-58-generic | 28        | 1.11%   |
| 5.4.0-58-generic  | 27        | 1.07%   |
| 5.13.0-28-generic | 27        | 1.07%   |
| 5.15.0-46-generic | 26        | 1.03%   |
| 5.13.0-30-generic | 26        | 1.03%   |
| 5.19.0-23-generic | 25        | 0.99%   |
| 5.11.0-25-generic | 25        | 0.99%   |
| 5.4.0-40-generic  | 24        | 0.95%   |
| 5.19.0-38-generic | 24        | 0.95%   |
| 5.15.0-53-generic | 24        | 0.95%   |
| 5.3.0-40-generic  | 22        | 0.87%   |
| 5.19.0-31-generic | 22        | 0.87%   |
| 5.15.0-47-generic | 22        | 0.87%   |
| 5.15.0-60-generic | 21        | 0.83%   |
| 5.15.0-43-generic | 21        | 0.83%   |
| 5.11.0-37-generic | 21        | 0.83%   |
| 5.15.0-41-generic | 20        | 0.79%   |
| 5.4.0-47-generic  | 19        | 0.75%   |
| 5.4.0-29-generic  | 19        | 0.75%   |
| 5.13.0-22-generic | 19        | 0.75%   |
| 5.4.0-37-generic  | 18        | 0.71%   |
| 5.13.0-27-generic | 18        | 0.71%   |
| 5.4.0-65-generic  | 17        | 0.67%   |
| 5.3.0-42-generic  | 17        | 0.67%   |
| 5.13.0-40-generic | 17        | 0.67%   |
| 5.11.0-38-generic | 17        | 0.67%   |
| 5.8.0-63-generic  | 16        | 0.63%   |
| 5.8.0-48-generic  | 16        | 0.63%   |
| 5.8.0-44-generic  | 16        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 481       | 20.33%  |
| 5.15.0  | 467       | 19.74%  |
| 5.13.0  | 258       | 10.9%   |
| 5.19.0  | 245       | 10.36%  |
| 5.8.0   | 220       | 9.3%    |
| 5.11.0  | 185       | 7.82%   |
| 6.2.0   | 132       | 5.58%   |
| 5.3.0   | 129       | 5.45%   |
| 4.15.0  | 38        | 1.61%   |
| 5.0.0   | 17        | 0.72%   |
| 5.10.0  | 13        | 0.55%   |
| 5.17.0  | 11        | 0.46%   |
| 5.6.0   | 7         | 0.3%    |
| 5.14.0  | 7         | 0.3%    |
| 6.1.0   | 6         | 0.25%   |
| 6.0.0   | 6         | 0.25%   |
| 6.0.9   | 5         | 0.21%   |
| 5.7.0   | 4         | 0.17%   |
| 4.4.0   | 4         | 0.17%   |
| 4.18.0  | 4         | 0.17%   |
| 6.4.8   | 3         | 0.13%   |
| 6.3.8   | 3         | 0.13%   |
| 5.12.0  | 3         | 0.13%   |
| 6.4.0   | 2         | 0.08%   |
| 6.3.7   | 2         | 0.08%   |
| 6.3.4   | 2         | 0.08%   |
| 6.3.0   | 2         | 0.08%   |
| 6.2.2   | 2         | 0.08%   |
| 6.1.8   | 2         | 0.08%   |
| 6.1.12  | 2         | 0.08%   |
| 6.0.7   | 2         | 0.08%   |
| 5.9.10  | 2         | 0.08%   |
| 5.9.0   | 2         | 0.08%   |
| 5.19.5  | 2         | 0.08%   |
| 5.18.10 | 2         | 0.08%   |
| 5.15.5  | 2         | 0.08%   |
| 5.15.34 | 2         | 0.08%   |
| 5.13.1  | 2         | 0.08%   |
| 5.12.8  | 2         | 0.08%   |
| 4.10.0  | 2         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 484       | 20.5%   |
| 5.15    | 477       | 20.2%   |
| 5.13    | 264       | 11.18%  |
| 5.19    | 249       | 10.55%  |
| 5.8     | 228       | 9.66%   |
| 5.11    | 189       | 8.01%   |
| 6.2     | 137       | 5.8%    |
| 5.3     | 130       | 5.51%   |
| 4.15    | 38        | 1.61%   |
| 5.10    | 17        | 0.72%   |
| 5.0     | 17        | 0.72%   |
| 6.1     | 15        | 0.64%   |
| 5.17    | 14        | 0.59%   |
| 6.3     | 13        | 0.55%   |
| 6.0     | 13        | 0.55%   |
| 5.14    | 13        | 0.55%   |
| 5.12    | 9         | 0.38%   |
| 5.6     | 8         | 0.34%   |
| 5.9     | 7         | 0.3%    |
| 6.4     | 6         | 0.25%   |
| 5.7     | 6         | 0.25%   |
| 5.18    | 5         | 0.21%   |
| 5.16    | 5         | 0.21%   |
| 4.18    | 5         | 0.21%   |
| 4.4     | 4         | 0.17%   |
| 5.5     | 3         | 0.13%   |
| 4.10    | 2         | 0.08%   |
| 5.1     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2222      | 99.87%  |
| i686   | 3         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 1738      | 76.94%  |
| KDE        | 491       | 21.74%  |
| GNOME      | 11        | 0.49%   |
| Cinnamon   | 5         | 0.22%   |
| MATE       | 3         | 0.13%   |
| Budgie     | 3         | 0.13%   |
| KDE4       | 2         | 0.09%   |
| XFCE       | 1         | 0.04%   |
| X-Cinnamon | 1         | 0.04%   |
| LXQt       | 1         | 0.04%   |
| i3         | 1         | 0.04%   |
| GNUstep    | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2124      | 94.74%  |
| Wayland | 100       | 4.46%   |
| Tty     | 18        | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1374      | 60.77%  |
| Unknown | 742       | 32.82%  |
| GDM     | 62        | 2.74%   |
| GDM3    | 39        | 1.72%   |
| LightDM | 31        | 1.37%   |
| TDM     | 11        | 0.49%   |
| SLiM    | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 968       | 43.16%  |
| de_DE   | 175       | 7.8%    |
| ru_RU   | 116       | 5.17%   |
| en_GB   | 98        | 4.37%   |
| pt_BR   | 97        | 4.32%   |
| it_IT   | 95        | 4.24%   |
| fr_FR   | 89        | 3.97%   |
| en_IN   | 58        | 2.59%   |
| es_ES   | 48        | 2.14%   |
| en_CA   | 48        | 2.14%   |
| Unknown | 43        | 1.92%   |
| pl_PL   | 41        | 1.83%   |
| en_AU   | 32        | 1.43%   |
| C       | 23        | 1.03%   |
| cs_CZ   | 17        | 0.76%   |
| hu_HU   | 16        | 0.71%   |
| es_MX   | 16        | 0.71%   |
| en_ZA   | 15        | 0.67%   |
| tr_TR   | 13        | 0.58%   |
| ru_UA   | 13        | 0.58%   |
| nl_NL   | 11        | 0.49%   |
| en_NZ   | 11        | 0.49%   |
| zh_CN   | 10        | 0.45%   |
| en_IE   | 9         | 0.4%    |
| es_CO   | 8         | 0.36%   |
| es_AR   | 8         | 0.36%   |
| sv_SE   | 7         | 0.31%   |
| pt_PT   | 7         | 0.31%   |
| es_CL   | 7         | 0.31%   |
| de_CH   | 7         | 0.31%   |
| fr_BE   | 6         | 0.27%   |
| es_VE   | 6         | 0.27%   |
| de_AT   | 6         | 0.27%   |
| ca_ES   | 6         | 0.27%   |
| sk_SK   | 5         | 0.22%   |
| nl_BE   | 5         | 0.22%   |
| fr_CH   | 5         | 0.22%   |
| fi_FI   | 5         | 0.22%   |
| en_SG   | 5         | 0.22%   |
| ro_RO   | 4         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1375      | 60.79%  |
| BIOS | 887       | 39.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2012      | 89.74%  |
| Btrfs   | 81        | 3.61%   |
| Overlay | 62        | 2.77%   |
| Tmpfs   | 51        | 2.27%   |
| Xfs     | 14        | 0.62%   |
| Zfs     | 11        | 0.49%   |
| Unknown | 6         | 0.27%   |
| Ext2    | 3         | 0.13%   |
| Ext3    | 2         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1222      | 54.19%  |
| Unknown | 860       | 38.14%  |
| MBR     | 173       | 7.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2024      | 90.56%  |
| Yes       | 211       | 9.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1407      | 62.81%  |
| Yes       | 833       | 37.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 518       | 23.28%  |
| Dell                   | 411       | 18.47%  |
| Hewlett-Packard        | 384       | 17.26%  |
| ASUSTek Computer       | 223       | 10.02%  |
| Acer                   | 165       | 7.42%   |
| MSI                    | 61        | 2.74%   |
| HUAWEI                 | 46        | 2.07%   |
| Samsung Electronics    | 41        | 1.84%   |
| Apple                  | 32        | 1.44%   |
| Toshiba                | 27        | 1.21%   |
| Notebook               | 25        | 1.12%   |
| Sony                   | 21        | 0.94%   |
| TUXEDO                 | 19        | 0.85%   |
| Google                 | 18        | 0.81%   |
| Unknown                | 15        | 0.67%   |
| Timi                   | 13        | 0.58%   |
| Gigabyte Technology    | 13        | 0.58%   |
| Alienware              | 12        | 0.54%   |
| Positivo               | 10        | 0.45%   |
| Fujitsu                | 9         | 0.4%    |
| System76               | 8         | 0.36%   |
| PC Specialist          | 8         | 0.36%   |
| Medion                 | 8         | 0.36%   |
| GPU Company            | 7         | 0.31%   |
| Chuwi                  | 7         | 0.31%   |
| Razer                  | 6         | 0.27%   |
| Packard Bell           | 6         | 0.27%   |
| LG Electronics         | 6         | 0.27%   |
| Intel                  | 6         | 0.27%   |
| Schenker               | 5         | 0.22%   |
| Panasonic              | 5         | 0.22%   |
| Framework              | 5         | 0.22%   |
| HONOR                  | 4         | 0.18%   |
| Fujitsu Siemens        | 4         | 0.18%   |
| Avell High Performance | 4         | 0.18%   |
| Irbis                  | 3         | 0.13%   |
| Haier                  | 3         | 0.13%   |
| GPD                    | 3         | 0.13%   |
| Digma                  | 3         | 0.13%   |
| Clevo                  | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 26        | 1.17%   |
| HP Notebook                      | 10        | 0.45%   |
| HP Pavilion g6                   | 9         | 0.4%    |
| HP Pavilion dv6                  | 9         | 0.4%    |
| Dell XPS 15 9560                 | 9         | 0.4%    |
| HUAWEI NBLK-WAX9X                | 8         | 0.36%   |
| HP Pavilion dv7                  | 7         | 0.31%   |
| HP Pavilion 15                   | 7         | 0.31%   |
| HP EliteBook 840 G5              | 7         | 0.31%   |
| Dell XPS 15 9570                 | 7         | 0.31%   |
| HUAWEI HVY-WXX9                  | 6         | 0.27%   |
| HP EliteBook 840 G6              | 6         | 0.27%   |
| HP EliteBook 840 G3              | 6         | 0.27%   |
| Dell XPS 15 7590                 | 6         | 0.27%   |
| Dell Latitude 5480               | 6         | 0.27%   |
| HP Pavilion Notebook             | 5         | 0.22%   |
| HP 255 G8 Notebook PC            | 5         | 0.22%   |
| GPU Company GWTC116-2            | 5         | 0.22%   |
| Dell XPS 13 9310                 | 5         | 0.22%   |
| Dell Latitude E6540              | 5         | 0.22%   |
| Dell Latitude E6420              | 5         | 0.22%   |
| Dell Latitude 5420               | 5         | 0.22%   |
| Dell Inspiron 5570               | 5         | 0.22%   |
| Dell Inspiron 15-3567            | 5         | 0.22%   |
| Acer Aspire A515-45              | 5         | 0.22%   |
| Lenovo Z50-75 80EC               | 4         | 0.18%   |
| Lenovo ThinkBook 15 G2 ITL 20VE  | 4         | 0.18%   |
| Lenovo Legion Y530-15ICH 81FV    | 4         | 0.18%   |
| Lenovo Legion 5 15ARH05H 82B1    | 4         | 0.18%   |
| Lenovo IdeaPad S145-15API 81V7   | 4         | 0.18%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7 | 4         | 0.18%   |
| Lenovo IdeaPad 5 15ARE05 81YQ    | 4         | 0.18%   |
| Lenovo IdeaPad 330-15IKB 81DE    | 4         | 0.18%   |
| Lenovo G50-70 20351              | 4         | 0.18%   |
| HUAWEI KLVL-WXX9                 | 4         | 0.18%   |
| HUAWEI CREM-WXX9                 | 4         | 0.18%   |
| HP ProBook 6470b                 | 4         | 0.18%   |
| HP Laptop 15s-eq0xxx             | 4         | 0.18%   |
| HP Laptop 15-da0xxx              | 4         | 0.18%   |
| HP EliteBook 845 G7 Notebook PC  | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 272       | 12.22%  |
| Dell Latitude     | 145       | 6.52%   |
| Lenovo IdeaPad    | 111       | 4.99%   |
| Acer Aspire       | 103       | 4.63%   |
| Dell Inspiron     | 98        | 4.4%    |
| HP Pavilion       | 87        | 3.91%   |
| Dell XPS          | 71        | 3.19%   |
| HP ProBook        | 63        | 2.83%   |
| HP EliteBook      | 61        | 2.74%   |
| HP Laptop         | 55        | 2.47%   |
| ASUS VivoBook     | 52        | 2.34%   |
| Dell Precision    | 38        | 1.71%   |
| Lenovo Legion     | 29        | 1.3%    |
| Dell Vostro       | 27        | 1.21%   |
| Acer Nitro        | 26        | 1.17%   |
| Unknown           | 26        | 1.17%   |
| Toshiba Satellite | 23        | 1.03%   |
| ASUS ASUS         | 23        | 1.03%   |
| Lenovo ThinkBook  | 22        | 0.99%   |
| ASUS ROG          | 18        | 0.81%   |
| Acer Swift        | 18        | 0.81%   |
| HP ZBook          | 16        | 0.72%   |
| HP ENVY           | 16        | 0.72%   |
| ASUS Zenbook      | 14        | 0.63%   |
| Dell G3           | 12        | 0.54%   |
| ASUS TUF          | 11        | 0.49%   |
| HP Notebook       | 10        | 0.45%   |
| HP 255            | 10        | 0.45%   |
| Lenovo Yoga       | 9         | 0.4%    |
| HUAWEI NBLK-WAX9X | 8         | 0.36%   |
| HP 250            | 8         | 0.36%   |
| Fujitsu LIFEBOOK  | 8         | 0.36%   |
| MSI Prestige      | 7         | 0.31%   |
| MSI Modern        | 7         | 0.31%   |
| HP OMEN           | 7         | 0.31%   |
| Acer Predator     | 7         | 0.31%   |
| Razer Blade       | 6         | 0.27%   |
| HUAWEI HVY-WXX9   | 6         | 0.27%   |
| HP Compaq         | 6         | 0.27%   |
| HP 15             | 6         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 297       | 13.35%  |
| 2019 | 290       | 13.03%  |
| 2021 | 262       | 11.78%  |
| 2018 | 198       | 8.9%    |
| 2017 | 148       | 6.65%   |
| 2012 | 147       | 6.61%   |
| 2014 | 136       | 6.11%   |
| 2011 | 136       | 6.11%   |
| 2013 | 132       | 5.93%   |
| 2022 | 113       | 5.08%   |
| 2016 | 107       | 4.81%   |
| 2015 | 79        | 3.55%   |
| 2010 | 59        | 2.65%   |
| 2008 | 56        | 2.52%   |
| 2009 | 29        | 1.3%    |
| 2023 | 18        | 0.81%   |
| 2007 | 18        | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2225      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1972      | 87.8%   |
| Enabled  | 274       | 12.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2200      | 98.88%  |
| Yes  | 25        | 1.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 628       | 28.04%  |
| 16.01-24.0  | 521       | 23.26%  |
| 8.01-16.0   | 421       | 18.79%  |
| 3.01-4.0    | 303       | 13.53%  |
| 32.01-64.0  | 232       | 10.36%  |
| 1.01-2.0    | 43        | 1.92%   |
| 64.01-256.0 | 39        | 1.74%   |
| 24.01-32.0  | 37        | 1.65%   |
| 2.01-3.0    | 16        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 640       | 26.73%  |
| 1.01-2.0   | 556       | 23.22%  |
| 4.01-8.0   | 544       | 22.72%  |
| 3.01-4.0   | 410       | 17.13%  |
| 8.01-16.0  | 173       | 7.23%   |
| 0.51-1.0   | 44        | 1.84%   |
| 16.01-24.0 | 18        | 0.75%   |
| 24.01-32.0 | 6         | 0.25%   |
| 32.01-64.0 | 3         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1569      | 69.55%  |
| 2      | 589       | 26.11%  |
| 3      | 71        | 3.15%   |
| 4      | 16        | 0.71%   |
| 0      | 9         | 0.4%    |
| 6      | 1         | 0.04%   |
| 5      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1657      | 74.17%  |
| Yes       | 577       | 25.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1736      | 77.85%  |
| No        | 494       | 22.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2204      | 99.06%  |
| No        | 21        | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1879      | 83.81%  |
| No        | 363       | 16.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 363       | 16.28%  |
| Germany      | 244       | 10.94%  |
| Russia       | 159       | 7.13%   |
| France       | 128       | 5.74%   |
| Brazil       | 128       | 5.74%   |
| Italy        | 123       | 5.52%   |
| UK           | 92        | 4.13%   |
| Spain        | 72        | 3.23%   |
| India        | 60        | 2.69%   |
| Poland       | 58        | 2.6%    |
| Canada       | 54        | 2.42%   |
| Netherlands  | 47        | 2.11%   |
| Ukraine      | 35        | 1.57%   |
| Mexico       | 35        | 1.57%   |
| Australia    | 31        | 1.39%   |
| Hungary      | 29        | 1.3%    |
| Czechia      | 29        | 1.3%    |
| Belgium      | 27        | 1.21%   |
| Turkey       | 25        | 1.12%   |
| Switzerland  | 23        | 1.03%   |
| Indonesia    | 23        | 1.03%   |
| South Africa | 17        | 0.76%   |
| Bulgaria     | 17        | 0.76%   |
| Sweden       | 16        | 0.72%   |
| Slovenia     | 15        | 0.67%   |
| Romania      | 15        | 0.67%   |
| Portugal     | 14        | 0.63%   |
| China        | 14        | 0.63%   |
| Slovakia     | 13        | 0.58%   |
| Greece       | 13        | 0.58%   |
| Finland      | 13        | 0.58%   |
| Denmark      | 13        | 0.58%   |
| Colombia     | 13        | 0.58%   |
| Austria      | 13        | 0.58%   |
| Argentina    | 13        | 0.58%   |
| Ireland      | 12        | 0.54%   |
| Croatia      | 12        | 0.54%   |
| Belarus      | 12        | 0.54%   |
| New Zealand  | 10        | 0.45%   |
| Serbia       | 9         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 49        | 2.1%    |
| Berlin            | 29        | 1.24%   |
| St Petersburg     | 22        | 0.94%   |
| Milan             | 21        | 0.9%    |
| Paris             | 20        | 0.86%   |
| Madrid            | 18        | 0.77%   |
| Warsaw            | 17        | 0.73%   |
| Hamburg           | 15        | 0.64%   |
| Cologne           | 14        | 0.6%    |
| Sao Paulo         | 13        | 0.56%   |
| Rome              | 13        | 0.56%   |
| Budapest          | 13        | 0.56%   |
| Zurich            | 11        | 0.47%   |
| Sofia             | 11        | 0.47%   |
| Prague            | 11        | 0.47%   |
| Minsk             | 11        | 0.47%   |
| Amsterdam         | 11        | 0.47%   |
| Munich            | 10        | 0.43%   |
| Jakarta           | 10        | 0.43%   |
| Vienna            | 9         | 0.39%   |
| Kyiv              | 9         | 0.39%   |
| Frankfurt am Main | 9         | 0.39%   |
| Bengaluru         | 9         | 0.39%   |
| Sydney            | 8         | 0.34%   |
| Rio de Janeiro    | 8         | 0.34%   |
| Phoenix           | 8         | 0.34%   |
| Istanbul          | 8         | 0.34%   |
| Dublin            | 8         | 0.34%   |
| Zagreb            | 7         | 0.3%    |
| Melbourne         | 7         | 0.3%    |
| Los Angeles       | 7         | 0.3%    |
| Helsinki          | 7         | 0.3%    |
| Chennai           | 7         | 0.3%    |
| Birmingham        | 7         | 0.3%    |
| Belgrade          | 7         | 0.3%    |
| Athens            | 7         | 0.3%    |
| Wroclaw           | 6         | 0.26%   |
| Washington        | 6         | 0.26%   |
| Singapore         | 6         | 0.26%   |
| Seville           | 6         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 554       | 727    | 19.3%   |
| WDC                         | 312       | 378    | 10.87%  |
| Seagate                     | 246       | 305    | 8.57%   |
| Toshiba                     | 192       | 243    | 6.69%   |
| SanDisk                     | 182       | 220    | 6.34%   |
| Kingston                    | 175       | 197    | 6.1%    |
| Unknown                     | 137       | 168    | 4.77%   |
| SK hynix                    | 132       | 159    | 4.6%    |
| Intel                       | 123       | 155    | 4.29%   |
| Crucial                     | 106       | 129    | 3.69%   |
| Micron Technology           | 85        | 95     | 2.96%   |
| HGST                        | 70        | 81     | 2.44%   |
| Hitachi                     | 47        | 50     | 1.64%   |
| KIOXIA                      | 44        | 50     | 1.53%   |
| A-DATA Technology           | 42        | 44     | 1.46%   |
| Apple                       | 22        | 28     | 0.77%   |
| LITEON                      | 21        | 22     | 0.73%   |
| China                       | 21        | 29     | 0.73%   |
| SPCC                        | 18        | 19     | 0.63%   |
| Silicon Motion              | 18        | 21     | 0.63%   |
| Phison Electronics          | 14        | 14     | 0.49%   |
| Unknown                     | 14        | 15     | 0.49%   |
| Phison                      | 13        | 13     | 0.45%   |
| PNY                         | 12        | 12     | 0.42%   |
| Transcend                   | 10        | 10     | 0.35%   |
| LITEONIT                    | 10        | 12     | 0.35%   |
| Intenso                     | 10        | 12     | 0.35%   |
| JMicron Technology          | 9         | 10     | 0.31%   |
| SSSTC                       | 8         | 8      | 0.28%   |
| Patriot                     | 8         | 8      | 0.28%   |
| Micron/Crucial Technology   | 8         | 12     | 0.28%   |
| UMIS                        | 7         | 8      | 0.24%   |
| Netac                       | 7         | 7      | 0.24%   |
| Kingston Technology Company | 7         | 7      | 0.24%   |
| GOODRAM                     | 7         | 7      | 0.24%   |
| Apacer                      | 7         | 7      | 0.24%   |
| Lenovo                      | 6         | 6      | 0.21%   |
| Corsair                     | 6         | 6      | 0.21%   |
| Union Memory                | 5         | 5      | 0.17%   |
| Team                        | 5         | 6      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 38        | 1.27%   |
| Toshiba MQ04ABF100 1TB                                | 27        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 27        | 0.9%    |
| Samsung SSD 860 EVO 500GB                             | 27        | 0.9%    |
| Unknown MMC Card  32GB                                | 26        | 0.87%   |
| HGST HTS721010A9E630 1TB                              | 25        | 0.83%   |
| Toshiba MQ01ABD100 1TB                                | 23        | 0.77%   |
| Unknown MMC Card  64GB                                | 22        | 0.73%   |
| Samsung NVMe SSD Drive 512GB                          | 21        | 0.7%    |
| Kingston SA400S37240G 240GB SSD                       | 21        | 0.7%    |
| Seagate ST500LT012-1DG142 500GB                       | 18        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                       | 18        | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB                        | 16        | 0.53%   |
| Samsung SSD 850 EVO 500GB                             | 16        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                          | 15        | 0.5%    |
| Samsung SSD 850 EVO 250GB                             | 15        | 0.5%    |
| Unknown MMC Card  128GB                               | 14        | 0.47%   |
| Samsung NVMe SSD Drive 1TB                            | 14        | 0.47%   |
| Unknown                                               | 14        | 0.47%   |
| Seagate ST2000LM007-1R8174 2TB                        | 13        | 0.43%   |
| SanDisk SSD PLUS 240GB                                | 13        | 0.43%   |
| SanDisk NVMe SSD Drive 256GB                          | 13        | 0.43%   |
| Samsung SSD 860 EVO M.2 500GB                         | 13        | 0.43%   |
| Intel SSDPEKNW512G8 512GB                             | 13        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                           | 13        | 0.43%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 12        | 0.4%    |
| SK hynix NVMe SSD Drive 512GB                         | 12        | 0.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 12        | 0.4%    |
| KIOXIA KBG40ZNS512G NVMe 512GB                        | 12        | 0.4%    |
| Toshiba MQ01ABF050 500GB                              | 11        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                          | 11        | 0.37%   |
| Samsung SSD 860 EVO 1TB                               | 11        | 0.37%   |
| HGST HTS541010A9E680 1TB                              | 11        | 0.37%   |
| Crucial CT500MX500SSD1 500GB                          | 11        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 10        | 0.33%   |
| WDC WD10SPZX-24Z10 1TB                                | 10        | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 10        | 0.33%   |
| Seagate ST1000LM048-2E7172 1TB                        | 10        | 0.33%   |
| SanDisk NVMe SSD Drive 1TB                            | 10        | 0.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 10        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 242       | 300    | 36.12%  |
| WDC                 | 164       | 192    | 24.48%  |
| Toshiba             | 108       | 138    | 16.12%  |
| HGST                | 69        | 80     | 10.3%   |
| Hitachi             | 47        | 50     | 7.01%   |
| Samsung Electronics | 12        | 15     | 1.79%   |
| Unknown             | 5         | 7      | 0.75%   |
| SABRENT             | 5         | 8      | 0.75%   |
| Fujitsu             | 5         | 7      | 0.75%   |
| Apple               | 4         | 4      | 0.6%    |
| External            | 3         | 4      | 0.45%   |
| USB3.0              | 1         | 1      | 0.15%   |
| KESU                | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| ipTIME              | 1         | 1      | 0.15%   |
| HGST HTS            | 1         | 1      | 0.15%   |
| ASMT                | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 246       | 326    | 26.48%  |
| Kingston            | 113       | 127    | 12.16%  |
| SanDisk             | 103       | 123    | 11.09%  |
| Crucial             | 90        | 112    | 9.69%   |
| WDC                 | 47        | 68     | 5.06%   |
| A-DATA Technology   | 24        | 24     | 2.58%   |
| Toshiba             | 22        | 32     | 2.37%   |
| Intel               | 22        | 27     | 2.37%   |
| Micron Technology   | 21        | 23     | 2.26%   |
| China               | 20        | 28     | 2.15%   |
| SK hynix            | 19        | 19     | 2.05%   |
| LITEON              | 16        | 16     | 1.72%   |
| SPCC                | 15        | 16     | 1.61%   |
| PNY                 | 10        | 10     | 1.08%   |
| LITEONIT            | 10        | 12     | 1.08%   |
| Apple               | 10        | 10     | 1.08%   |
| Transcend           | 9         | 9      | 0.97%   |
| Patriot             | 8         | 8      | 0.86%   |
| Intenso             | 8         | 10     | 0.86%   |
| GOODRAM             | 7         | 7      | 0.75%   |
| Apacer              | 7         | 7      | 0.75%   |
| JMicron Technology  | 6         | 6      | 0.65%   |
| KingSpec            | 5         | 5      | 0.54%   |
| Dogfish             | 5         | 5      | 0.54%   |
| Team                | 4         | 4      | 0.43%   |
| Netac               | 4         | 4      | 0.43%   |
| Emtec               | 4         | 4      | 0.43%   |
| Corsair             | 4         | 4      | 0.43%   |
| Zheino              | 3         | 5      | 0.32%   |
| TO Exter            | 3         | 3      | 0.32%   |
| Lexar               | 3         | 3      | 0.32%   |
| ASMT                | 3         | 4      | 0.32%   |
| Unknown             | 3         | 3      | 0.32%   |
| Verbatim            | 2         | 3      | 0.22%   |
| Smart               | 2         | 2      | 0.22%   |
| RZX                 | 2         | 3      | 0.22%   |
| Plextor             | 2         | 2      | 0.22%   |
| Mushkin             | 2         | 2      | 0.22%   |
| Kimtigo             | 2         | 2      | 0.22%   |
| FORESEE             | 2         | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1049      | 1336   | 38.54%  |
| SSD     | 846       | 1132   | 31.08%  |
| HDD     | 653       | 811    | 23.99%  |
| MMC     | 141       | 170    | 5.18%   |
| Unknown | 33        | 39     | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1295      | 1863   | 50.27%  |
| NVMe | 1049      | 1336   | 40.72%  |
| MMC  | 141       | 170    | 5.47%   |
| SAS  | 91        | 119    | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 905       | 1185   | 60.78%  |
| 0.51-1.0   | 492       | 639    | 33.04%  |
| 1.01-2.0   | 83        | 106    | 5.57%   |
| 3.01-4.0   | 5         | 9      | 0.34%   |
| 4.01-10.0  | 4         | 4      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 657       | 28.65%  |
| 101-250        | 656       | 28.61%  |
| 501-1000       | 431       | 18.8%   |
| 1001-2000      | 187       | 8.16%   |
| 51-100         | 132       | 5.76%   |
| 1-20           | 66        | 2.88%   |
| 21-50          | 60        | 2.62%   |
| More than 3000 | 47        | 2.05%   |
| 2001-3000      | 47        | 2.05%   |
| Unknown        | 10        | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 604       | 25.41%  |
| 101-250        | 471       | 19.81%  |
| 21-50          | 414       | 17.42%  |
| 51-100         | 337       | 14.18%  |
| 251-500        | 288       | 12.12%  |
| 501-1000       | 158       | 6.65%   |
| 1001-2000      | 64        | 2.69%   |
| More than 3000 | 18        | 0.76%   |
| 2001-3000      | 13        | 0.55%   |
| Unknown        | 10        | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 5         | 11     | 3.25%   |
| HGST HTS721010A9E630 1TB                 | 5         | 6      | 3.25%   |
| Toshiba MQ04ABF100 1TB                   | 4         | 4      | 2.6%    |
| Toshiba MQ01ABD100 1TB                   | 3         | 5      | 1.95%   |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 1.95%   |
| Seagate ST1000LM048-2E7172 1TB           | 3         | 3      | 1.95%   |
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 1.95%   |
| SanDisk SSD PLUS 240GB                   | 3         | 3      | 1.95%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 1.95%   |
| Hitachi HTS547564A9E384 640GB            | 3         | 3      | 1.95%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 1.95%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 2         | 2      | 1.3%    |
| Toshiba MQ01ABD075 752GB                 | 2         | 4      | 1.3%    |
| SK hynix SC401 SATA 512GB SSD            | 2         | 2      | 1.3%    |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.3%    |
| SK hynix BC711 HFM256GD3JX013N 256GB     | 2         | 2      | 1.3%    |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.3%    |
| Seagate ST2000LM007-1R8174 2TB           | 2         | 2      | 1.3%    |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.3%    |
| Hitachi HTS545050B9A300 500GB            | 2         | 2      | 1.3%    |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 1.3%    |
| Crucial CT500P1SSD8 500GB                | 2         | 2      | 1.3%    |
| Zheino CHN mSATA02M 256 256GB SSD        | 1         | 2      | 0.65%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD         | 1         | 1      | 0.65%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.65%   |
| WDC WD6400BEVT-00A0RT0 640GB             | 1         | 1      | 0.65%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.65%   |
| WDC WD5000LPVX-55V0TT0 500GB             | 1         | 1      | 0.65%   |
| WDC WD5000LPVT-24G33T1 500GB             | 1         | 1      | 0.65%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 0.65%   |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.65%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.65%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.65%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB     | 1         | 1      | 0.65%   |
| VISIPRO SSD 256GB                        | 1         | 2      | 0.65%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.65%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.65%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1      | 0.65%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 2      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 20.78%  |
| Toshiba             | 23        | 28     | 14.94%  |
| Hitachi             | 13        | 13     | 8.44%   |
| HGST                | 12        | 13     | 7.79%   |
| WDC                 | 11        | 11     | 7.14%   |
| Samsung Electronics | 11        | 12     | 7.14%   |
| SK hynix            | 10        | 10     | 6.49%   |
| Crucial             | 9         | 10     | 5.84%   |
| SanDisk             | 8         | 8      | 5.19%   |
| Kingston            | 6         | 6      | 3.9%    |
| A-DATA Technology   | 5         | 5      | 3.25%   |
| Micron Technology   | 3         | 3      | 1.95%   |
| Zheino              | 1         | 2      | 0.65%   |
| VISIPRO             | 1         | 2      | 0.65%   |
| Team                | 1         | 1      | 0.65%   |
| R580                | 1         | 1      | 0.65%   |
| Mushkin             | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| LITEON              | 1         | 1      | 0.65%   |
| Intel               | 1         | 1      | 0.65%   |
| Drevo               | 1         | 1      | 0.65%   |
| BAITITON            | 1         | 3      | 0.65%   |
| ASENNO              | 1         | 1      | 0.65%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 36.78%  |
| Toshiba             | 19        | 24     | 21.84%  |
| Hitachi             | 13        | 13     | 14.94%  |
| HGST                | 12        | 13     | 13.79%  |
| WDC                 | 9         | 9      | 10.34%  |
| Samsung Electronics | 2         | 2      | 2.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 86        | 101    | 56.58%  |
| SSD  | 49        | 56     | 32.24%  |
| NVMe | 17        | 17     | 11.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 33.33%  |
| Intel SSDSC2KB960G8 960GB | 1         | 1      | 33.33%  |
| Acer SSD FA100 256GB      | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Acer    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1192      | 1629   | 49.24%  |
| Detected | 1075      | 1682   | 44.4%   |
| Malfunc  | 151       | 174    | 6.24%   |
| Failed   | 3         | 3      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1496      | 53.31%  |
| Samsung Electronics              | 317       | 11.3%   |
| AMD                              | 271       | 9.66%   |
| SanDisk                          | 185       | 6.59%   |
| SK hynix                         | 113       | 4.03%   |
| Toshiba America Info Systems     | 69        | 2.46%   |
| Kingston Technology Company      | 69        | 2.46%   |
| Micron Technology                | 64        | 2.28%   |
| KIOXIA                           | 41        | 1.46%   |
| Phison Electronics               | 31        | 1.1%    |
| Micron/Crucial Technology        | 24        | 0.86%   |
| Silicon Motion                   | 23        | 0.82%   |
| ADATA Technology                 | 22        | 0.78%   |
| Union Memory (Shenzhen)          | 15        | 0.53%   |
| Solid State Storage Technology   | 15        | 0.53%   |
| Realtek Semiconductor            | 11        | 0.39%   |
| Lite-On Technology               | 8         | 0.29%   |
| Apple                            | 6         | 0.21%   |
| Nvidia                           | 5         | 0.18%   |
| Lenovo                           | 5         | 0.18%   |
| Marvell Technology Group         | 3         | 0.11%   |
| Netac Technology                 | 2         | 0.07%   |
| Biwin Storage Technology         | 2         | 0.07%   |
| Zhaoxin                          | 1         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| Seagate Technology               | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| ASMedia Technology               | 1         | 0.04%   |
| Unknown                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 251       | 8.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 178       | 5.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 164       | 5.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 153       | 5.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 148       | 4.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 102       | 3.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 99        | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 98        | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 83        | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 76        | 2.55%   |
| Samsung NVMe SSD Controller 980                                                | 75        | 2.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 1.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 53        | 1.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 52        | 1.75%   |
| Intel SSD 660P Series                                                          | 51        | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 49        | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 48        | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 42        | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                          | 41        | 1.38%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 39        | 1.31%   |
| Intel Tiger Lake-LP SATA Controller                                            | 38        | 1.28%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 34        | 1.14%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 34        | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 34        | 1.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 32        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 30        | 1.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 28        | 0.94%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 27        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 26        | 0.87%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 22        | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 22        | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 21        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 21        | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 19        | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 19        | 0.64%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 17        | 0.57%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 17        | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 17        | 0.57%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 16        | 0.54%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 16        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1492      | 52.17%  |
| NVMe | 1045      | 36.54%  |
| RAID | 258       | 9.02%   |
| IDE  | 65        | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1777      | 79.87%  |
| AMD          | 447       | 20.09%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 51        | 2.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 44        | 1.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 43        | 1.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 41        | 1.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 40        | 1.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 38        | 1.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 36        | 1.62%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 34        | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 33        | 1.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 1.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 1.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 31        | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 31        | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 1.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 1.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 28        | 1.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 27        | 1.21%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 25        | 1.12%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 24        | 1.08%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 22        | 0.99%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 20        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 18        | 0.81%   |
| Intel 12th Gen Core i7-12700H                 | 18        | 0.81%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 18        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.76%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 17        | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 16        | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 15        | 0.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 15        | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.63%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 14        | 0.63%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 13        | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.58%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 13        | 0.58%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 13        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 12        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 607       | 27.28%  |
| Intel Core i5           | 541       | 24.31%  |
| Other                   | 249       | 11.19%  |
| AMD Ryzen 7             | 134       | 6.02%   |
| AMD Ryzen 5             | 123       | 5.53%   |
| Intel Core i3           | 118       | 5.3%    |
| Intel Celeron           | 98        | 4.4%    |
| Intel Core 2 Duo        | 52        | 2.34%   |
| Intel Pentium           | 32        | 1.44%   |
| AMD A6                  | 25        | 1.12%   |
| AMD Ryzen 7 PRO         | 23        | 1.03%   |
| AMD Ryzen 3             | 23        | 1.03%   |
| AMD Ryzen 9             | 18        | 0.81%   |
| Intel Pentium Dual-Core | 16        | 0.72%   |
| Intel Core i9           | 15        | 0.67%   |
| AMD A10                 | 15        | 0.67%   |
| Intel Atom              | 14        | 0.63%   |
| Intel Pentium Silver    | 12        | 0.54%   |
| AMD Ryzen 5 PRO         | 11        | 0.49%   |
| AMD A8                  | 10        | 0.45%   |
| Intel Genuine           | 7         | 0.31%   |
| AMD E1                  | 7         | 0.31%   |
| AMD E                   | 7         | 0.31%   |
| AMD A4                  | 7         | 0.31%   |
| AMD FX                  | 6         | 0.27%   |
| AMD E2                  | 6         | 0.27%   |
| AMD Athlon              | 6         | 0.27%   |
| Intel Pentium Dual      | 5         | 0.22%   |
| Intel Core m3           | 5         | 0.22%   |
| Intel Celeron Dual-Core | 5         | 0.22%   |
| AMD Athlon II           | 4         | 0.18%   |
| Intel Xeon              | 3         | 0.13%   |
| Intel Core 2            | 3         | 0.13%   |
| AMD A12                 | 3         | 0.13%   |
| AMD C-50                | 2         | 0.09%   |
| AMD Athlon II Dual-Core | 2         | 0.09%   |
| Intel Pentium Gold      | 1         | 0.04%   |
| Intel Core M            | 1         | 0.04%   |
| Intel Core 2 Quad       | 1         | 0.04%   |
| AMD Z                   | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 882       | 39.62%  |
| 4      | 832       | 37.38%  |
| 6      | 239       | 10.74%  |
| 8      | 185       | 8.31%   |
| 14     | 29        | 1.3%    |
| 10     | 19        | 0.85%   |
| 12     | 18        | 0.81%   |
| 1      | 14        | 0.63%   |
| 24     | 4         | 0.18%   |
| 16     | 3         | 0.13%   |
| 5      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2225      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1844      | 82.65%  |
| 1      | 387       | 17.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2225      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 639       | 27.96%  |
| 0x306a9    | 112       | 4.9%    |
| 0x206a7    | 96        | 4.2%    |
| 0x906ea    | 92        | 4.03%   |
| 0x806ec    | 92        | 4.03%   |
| 0x806c1    | 88        | 3.85%   |
| 0x806ea    | 83        | 3.63%   |
| 0x40651    | 73        | 3.19%   |
| 0x306c3    | 61        | 2.67%   |
| 0x806e9    | 58        | 2.54%   |
| 0x406e3    | 56        | 2.45%   |
| 0x306d4    | 44        | 1.93%   |
| 0x0a50000c | 44        | 1.93%   |
| 0x08108109 | 41        | 1.79%   |
| 0x08600106 | 38        | 1.66%   |
| 0x1067a    | 37        | 1.62%   |
| 0xa0652    | 36        | 1.58%   |
| 0x906e9    | 35        | 1.53%   |
| 0x08108102 | 35        | 1.53%   |
| 0x906a3    | 34        | 1.49%   |
| 0x706e5    | 33        | 1.44%   |
| 0x806eb    | 26        | 1.14%   |
| 0x506e3    | 26        | 1.14%   |
| 0x08608103 | 23        | 1.01%   |
| 0x20655    | 21        | 0.92%   |
| 0x806d1    | 20        | 0.88%   |
| 0x706a8    | 20        | 0.88%   |
| 0x706a1    | 20        | 0.88%   |
| 0x406c4    | 18        | 0.79%   |
| 0x30678    | 16        | 0.7%    |
| 0x906ed    | 15        | 0.66%   |
| 0x08600104 | 15        | 0.66%   |
| 0x08600103 | 13        | 0.57%   |
| 0x07030105 | 13        | 0.57%   |
| 0x03000027 | 13        | 0.57%   |
| 0x6fd      | 12        | 0.53%   |
| 0x06006705 | 12        | 0.53%   |
| 0x20652    | 11        | 0.48%   |
| 0x906a4    | 9         | 0.39%   |
| 0x506c9    | 9         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 523       | 23.48%  |
| Haswell          | 181       | 8.13%   |
| IvyBridge        | 162       | 7.27%   |
| TigerLake        | 137       | 6.15%   |
| SandyBridge      | 128       | 5.75%   |
| Skylake          | 109       | 4.89%   |
| Unknown          | 101       | 4.54%   |
| Zen+             | 91        | 4.09%   |
| Zen 2            | 90        | 4.04%   |
| Zen 3            | 74        | 3.32%   |
| Icelake          | 65        | 2.92%   |
| Penryn           | 63        | 2.83%   |
| CometLake        | 63        | 2.83%   |
| Broadwell        | 58        | 2.6%    |
| Alderlake Hybrid | 56        | 2.51%   |
| Goldmont plus    | 55        | 2.47%   |
| Silvermont       | 47        | 2.11%   |
| Westmere         | 46        | 2.07%   |
| Excavator        | 33        | 1.48%   |
| Core             | 30        | 1.35%   |
| Zen              | 18        | 0.81%   |
| Puma             | 18        | 0.81%   |
| K10 Llano        | 14        | 0.63%   |
| Goldmont         | 14        | 0.63%   |
| Bobcat           | 12        | 0.54%   |
| Piledriver       | 8         | 0.36%   |
| Jaguar           | 8         | 0.36%   |
| K10              | 7         | 0.31%   |
| Steamroller      | 5         | 0.22%   |
| Nehalem          | 5         | 0.22%   |
| Bonnell          | 3         | 0.13%   |
| K8 & K10 hybrid  | 2         | 0.09%   |
| Tremont          | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1672      | 56.43%  |
| Nvidia                           | 720       | 24.3%   |
| AMD                              | 568       | 19.17%  |
| Zhaoxin                          | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 149       | 4.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 129       | 4.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 124       | 4.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 119       | 3.93%   |
| Intel UHD Graphics 620                                                                   | 94        | 3.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 94        | 3.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 89        | 2.94%   |
| AMD Renoir                                                                               | 89        | 2.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 82        | 2.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 81        | 2.68%   |
| Intel HD Graphics 620                                                                    | 75        | 2.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 67        | 2.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 67        | 2.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 61        | 2.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 1.85%   |
| Intel HD Graphics 5500                                                                   | 53        | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 45        | 1.49%   |
| Intel HD Graphics 630                                                                    | 43        | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 42        | 1.39%   |
| AMD Lucienne                                                                             | 42        | 1.39%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 40        | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 37        | 1.22%   |
| Intel HD Graphics 530                                                                    | 33        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 31        | 1.02%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 25        | 0.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 25        | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 24        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 23        | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 23        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.76%   |
| AMD Rembrandt [Radeon 680M]                                                              | 23        | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 21        | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.66%   |
| Intel Iris Plus Graphics G7                                                              | 20        | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 18        | 0.59%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 18        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1006      | 45.13%  |
| Intel + Nvidia | 569       | 25.53%  |
| 1 x AMD        | 358       | 16.06%  |
| Intel + AMD    | 93        | 4.17%   |
| 1 x Nvidia     | 76        | 3.41%   |
| AMD + Nvidia   | 73        | 3.28%   |
| 2 x AMD        | 45        | 2.02%   |
| Other          | 3         | 0.13%   |
| 2 x Nvidia     | 2         | 0.09%   |
| 2 x Intel      | 2         | 0.09%   |
| 1 x Zhaoxin    | 1         | 0.04%   |
| 1 x SiS        | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1738      | 77.18%  |
| Proprietary | 480       | 21.31%  |
| Unknown     | 34        | 1.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1473      | 64.69%  |
| 1.01-2.0   | 247       | 10.85%  |
| 0.01-0.5   | 229       | 10.06%  |
| 3.01-4.0   | 135       | 5.93%   |
| 0.51-1.0   | 110       | 4.83%   |
| 5.01-6.0   | 41        | 1.8%    |
| 7.01-8.0   | 28        | 1.23%   |
| 2.01-3.0   | 12        | 0.53%   |
| 8.01-16.0  | 2         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 474       | 17.7%   |
| BOE                     | 396       | 14.79%  |
| LG Display              | 374       | 13.97%  |
| Chimei Innolux          | 359       | 13.41%  |
| Samsung Electronics     | 255       | 9.52%   |
| Sharp                   | 106       | 3.96%   |
| Dell                    | 93        | 3.47%   |
| Goldstar                | 75        | 2.8%    |
| PANDA                   | 46        | 1.72%   |
| Lenovo                  | 46        | 1.72%   |
| Chi Mei Optoelectronics | 41        | 1.53%   |
| Hewlett-Packard         | 40        | 1.49%   |
| Apple                   | 35        | 1.31%   |
| Acer                    | 34        | 1.27%   |
| Philips                 | 31        | 1.16%   |
| InfoVision              | 24        | 0.9%    |
| BenQ                    | 22        | 0.82%   |
| AOC                     | 21        | 0.78%   |
| Ancor Communications    | 20        | 0.75%   |
| CSO                     | 15        | 0.56%   |
| ASUSTek Computer        | 13        | 0.49%   |
| ViewSonic               | 12        | 0.45%   |
| Iiyama                  | 11        | 0.41%   |
| Panasonic               | 7         | 0.26%   |
| LG Philips              | 7         | 0.26%   |
| Toshiba                 | 6         | 0.22%   |
| Sony                    | 6         | 0.22%   |
| Sceptre Tech            | 6         | 0.22%   |
| MSI                     | 5         | 0.19%   |
| CPT                     | 5         | 0.19%   |
| Seiko/Epson             | 4         | 0.15%   |
| NEC Computers           | 4         | 0.15%   |
| HannStar                | 4         | 0.15%   |
| Vizio                   | 3         | 0.11%   |
| Vestel Elektronik       | 3         | 0.11%   |
| Unknown                 | 3         | 0.11%   |
| SLD                     | 3         | 0.11%   |
| Medion                  | 3         | 0.11%   |
| LGD                     | 3         | 0.11%   |
| KDC                     | 3         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 21        | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 19        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 16        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.44%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 12        | 0.44%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 12        | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 11        | 0.41%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 10        | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 10        | 0.37%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 9         | 0.33%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 8         | 0.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 8         | 0.29%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 8         | 0.29%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 8         | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.29%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 8         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 7         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.26%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 7         | 0.26%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 7         | 0.26%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 7         | 0.26%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 6         | 0.22%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 6         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 6         | 0.22%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 6         | 0.22%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 6         | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 6         | 0.22%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 6         | 0.22%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 6         | 0.22%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 6         | 0.22%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 6         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1208      | 48.93%  |
| 1366x768 (WXGA)    | 579       | 23.45%  |
| 3840x2160 (4K)     | 123       | 4.98%   |
| 1600x900 (HD+)     | 119       | 4.82%   |
| 2560x1440 (QHD)    | 95        | 3.85%   |
| 1920x1200 (WUXGA)  | 56        | 2.27%   |
| 1280x800 (WXGA)    | 38        | 1.54%   |
| 2560x1600          | 28        | 1.13%   |
| 2880x1800          | 25        | 1.01%   |
| 1440x900 (WXGA+)   | 25        | 1.01%   |
| 3840x2400          | 19        | 0.77%   |
| 1680x1050 (WSXGA+) | 17        | 0.69%   |
| 3440x1440          | 16        | 0.65%   |
| 2560x1080          | 16        | 0.65%   |
| 2160x1440          | 16        | 0.65%   |
| 1280x1024 (SXGA)   | 13        | 0.53%   |
| 1360x768           | 8         | 0.32%   |
| 3200x1800 (QHD+)   | 7         | 0.28%   |
| 2240x1400          | 7         | 0.28%   |
| 2256x1504          | 6         | 0.24%   |
| 3840x1080          | 5         | 0.2%    |
| 3456x2160          | 4         | 0.16%   |
| 3072x1920          | 4         | 0.16%   |
| 2520x1680          | 4         | 0.16%   |
| 1920x540           | 4         | 0.16%   |
| 1600x1200          | 4         | 0.16%   |
| Unknown            | 4         | 0.16%   |
| 1920x1280          | 3         | 0.12%   |
| 1024x768 (XGA)     | 3         | 0.12%   |
| 1280x720 (HD)      | 2         | 0.08%   |
| 1024x600           | 2         | 0.08%   |
| 5760x2160          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 3000x1920          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |
| 2160x1350          | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |
| 1080x1920          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1075      | 40.07%  |
| 14      | 335       | 12.49%  |
| 13      | 327       | 12.19%  |
| 17      | 228       | 8.5%    |
| 27      | 118       | 4.4%    |
| 24      | 102       | 3.8%    |
| 23      | 82        | 3.06%   |
| 21      | 65        | 2.42%   |
| 16      | 51        | 1.9%    |
| 11      | 47        | 1.75%   |
| 12      | 41        | 1.53%   |
| 34      | 30        | 1.12%   |
| Unknown | 25        | 0.93%   |
| 31      | 24        | 0.89%   |
| 18      | 17        | 0.63%   |
| 20      | 14        | 0.52%   |
| 19      | 13        | 0.48%   |
| 22      | 10        | 0.37%   |
| 54      | 9         | 0.34%   |
| 84      | 8         | 0.3%    |
| 72      | 7         | 0.26%   |
| 32      | 7         | 0.26%   |
| 40      | 6         | 0.22%   |
| 26      | 6         | 0.22%   |
| 25      | 6         | 0.22%   |
| 10      | 4         | 0.15%   |
| 42      | 3         | 0.11%   |
| 65      | 2         | 0.07%   |
| 49      | 2         | 0.07%   |
| 48      | 2         | 0.07%   |
| 46      | 2         | 0.07%   |
| 78      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 63      | 1         | 0.04%   |
| 61      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1595      | 60.21%  |
| 501-600     | 282       | 10.65%  |
| 351-400     | 270       | 10.19%  |
| 201-300     | 238       | 8.98%   |
| 401-500     | 113       | 4.27%   |
| 701-800     | 36        | 1.36%   |
| 601-700     | 36        | 1.36%   |
| Unknown     | 25        | 0.94%   |
| 1001-1500   | 22        | 0.83%   |
| 1501-2000   | 17        | 0.64%   |
| 801-900     | 10        | 0.38%   |
| 901-1000    | 3         | 0.11%   |
| 101-200     | 1         | 0.04%   |
| 1-100       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1947      | 85.32%  |
| 16/10   | 226       | 9.9%    |
| 3/2     | 34        | 1.49%   |
| 21/9    | 32        | 1.4%    |
| Unknown | 16        | 0.7%    |
| 5/4     | 13        | 0.57%   |
| 4/3     | 8         | 0.35%   |
| 32/9    | 3         | 0.13%   |
| 3.40    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1075      | 40.28%  |
| 81-90          | 541       | 20.27%  |
| 201-250        | 204       | 7.64%   |
| 121-130        | 197       | 7.38%   |
| 301-350        | 125       | 4.68%   |
| 71-80          | 121       | 4.53%   |
| 351-500        | 59        | 2.21%   |
| 51-60          | 48        | 1.8%    |
| 151-200        | 45        | 1.69%   |
| 111-120        | 44        | 1.65%   |
| 61-70          | 37        | 1.39%   |
| More than 1000 | 34        | 1.27%   |
| 251-300        | 34        | 1.27%   |
| Unknown        | 25        | 0.94%   |
| 131-140        | 24        | 0.9%    |
| 141-150        | 20        | 0.75%   |
| 501-1000       | 18        | 0.67%   |
| 91-100         | 12        | 0.45%   |
| 41-50          | 4         | 0.15%   |
| 1-40           | 2         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1182      | 45.13%  |
| 101-120       | 659       | 25.16%  |
| 51-100        | 400       | 15.27%  |
| 161-240       | 207       | 7.9%    |
| More than 240 | 112       | 4.28%   |
| 1-50          | 34        | 1.3%    |
| Unknown       | 25        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1720      | 75.67%  |
| 2     | 447       | 19.67%  |
| 3     | 63        | 2.77%   |
| 0     | 36        | 1.58%   |
| 4     | 7         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1266      | 35.85%  |
| Realtek Semiconductor             | 1252      | 35.46%  |
| Qualcomm Atheros                  | 436       | 12.35%  |
| Broadcom                          | 168       | 4.76%   |
| MediaTek                          | 89        | 2.52%   |
| Broadcom Limited                  | 31        | 0.88%   |
| Ralink                            | 28        | 0.79%   |
| Marvell Technology Group          | 22        | 0.62%   |
| ASIX Electronics                  | 20        | 0.57%   |
| TP-Link                           | 18        | 0.51%   |
| Lenovo                            | 17        | 0.48%   |
| Sierra Wireless                   | 15        | 0.42%   |
| Qualcomm                          | 15        | 0.42%   |
| Samsung Electronics               | 13        | 0.37%   |
| Ralink Technology                 | 12        | 0.34%   |
| DisplayLink                       | 12        | 0.34%   |
| Dell                              | 11        | 0.31%   |
| Xiaomi                            | 10        | 0.28%   |
| Ericsson Business Mobile Networks | 10        | 0.28%   |
| Huawei Technologies               | 9         | 0.25%   |
| Hewlett-Packard                   | 9         | 0.25%   |
| JMicron Technology                | 8         | 0.23%   |
| D-Link                            | 5         | 0.14%   |
| Apple                             | 5         | 0.14%   |
| Nvidia                            | 4         | 0.11%   |
| Google                            | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.08%   |
| T & A Mobile Phones               | 3         | 0.08%   |
| Qualcomm Atheros Communications   | 3         | 0.08%   |
| NetGear                           | 3         | 0.08%   |
| Motorola PCS                      | 3         | 0.08%   |
| Fibocom                           | 3         | 0.08%   |
| ZyDAS                             | 2         | 0.06%   |
| Edimax Technology                 | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |
| Texas Instruments                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 777       | 18.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 166       | 3.94%   |
| Intel Wi-Fi 6 AX200                                               | 143       | 3.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 111       | 2.64%   |
| Intel Wireless 8265 / 8275                                        | 106       | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 91        | 2.16%   |
| Intel Wi-Fi 6 AX201                                               | 91        | 2.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88        | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 87        | 2.07%   |
| Intel Wireless 7260                                               | 82        | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 81        | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 77        | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 71        | 1.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 65        | 1.54%   |
| Intel Wireless 7265                                               | 63        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 62        | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 61        | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 58        | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 54        | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 51        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 49        | 1.16%   |
| Intel Wireless 8260                                               | 48        | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 41        | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 41        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 39        | 0.93%   |
| Intel Wireless 3165                                               | 37        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 34        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 31        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 27        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 23        | 0.55%   |
| Intel Wireless-AC 9260                                            | 23        | 0.55%   |
| Intel Wireless 3160                                               | 23        | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 23        | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 23        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                     | 23        | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 22        | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1211      | 52.47%  |
| Qualcomm Atheros                      | 369       | 15.99%  |
| Realtek Semiconductor                 | 368       | 15.94%  |
| Broadcom                              | 127       | 5.5%    |
| MediaTek                              | 87        | 3.77%   |
| Ralink                                | 28        | 1.21%   |
| Broadcom Limited                      | 24        | 1.04%   |
| Sierra Wireless                       | 15        | 0.65%   |
| TP-Link                               | 13        | 0.56%   |
| Ralink Technology                     | 12        | 0.52%   |
| Qualcomm                              | 12        | 0.52%   |
| Dell                                  | 6         | 0.26%   |
| D-Link                                | 5         | 0.22%   |
| Ericsson Business Mobile Networks     | 4         | 0.17%   |
| Qualcomm Atheros Communications       | 3         | 0.13%   |
| NetGear                               | 3         | 0.13%   |
| Hewlett-Packard                       | 3         | 0.13%   |
| Fibocom                               | 3         | 0.13%   |
| ZyDAS                                 | 2         | 0.09%   |
| Edimax Technology                     | 2         | 0.09%   |
| ASUSTek Computer                      | 2         | 0.09%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| Wacom                                 | 1         | 0.04%   |
| Texas Instruments                     | 1         | 0.04%   |
| Microsoft                             | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| D-Link System                         | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 143       | 6.15%   |
| Intel Wireless 8265 / 8275                                     | 106       | 4.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 91        | 3.91%   |
| Intel Wi-Fi 6 AX201                                            | 91        | 3.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 87        | 3.74%   |
| Intel Wireless 7260                                            | 82        | 3.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 81        | 3.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 77        | 3.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 71        | 3.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 65        | 2.79%   |
| Intel Wireless 7265                                            | 63        | 2.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 62        | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 61        | 2.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 58        | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 54        | 2.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 51        | 2.19%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 49        | 2.11%   |
| Intel Wireless 8260                                            | 48        | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 41        | 1.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 41        | 1.76%   |
| Intel Wireless 3165                                            | 37        | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 34        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 31        | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 27        | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 23        | 0.99%   |
| Intel Wireless-AC 9260                                         | 23        | 0.99%   |
| Intel Wireless 3160                                            | 23        | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 23        | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 23        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                  | 23        | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 22        | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 19        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 0.77%   |
| Intel Centrino Advanced-N 6235                                 | 18        | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 16        | 0.69%   |
| Realtek 802.11n WLAN Adapter                                   | 15        | 0.64%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 0.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 15        | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 14        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1091      | 59.85%  |
| Intel                            | 428       | 23.48%  |
| Qualcomm Atheros                 | 100       | 5.49%   |
| Broadcom                         | 54        | 2.96%   |
| Marvell Technology Group         | 22        | 1.21%   |
| ASIX Electronics                 | 20        | 1.1%    |
| Lenovo                           | 17        | 0.93%   |
| Samsung Electronics              | 13        | 0.71%   |
| DisplayLink                      | 12        | 0.66%   |
| Xiaomi                           | 10        | 0.55%   |
| JMicron Technology               | 8         | 0.44%   |
| Broadcom Limited                 | 8         | 0.44%   |
| Huawei Technologies              | 6         | 0.33%   |
| TP-Link                          | 5         | 0.27%   |
| Apple                            | 5         | 0.27%   |
| Nvidia                           | 4         | 0.22%   |
| Google                           | 4         | 0.22%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.16%   |
| T & A Mobile Phones              | 3         | 0.16%   |
| Qualcomm                         | 3         | 0.16%   |
| Motorola PCS                     | 2         | 0.11%   |
| MediaTek                         | 2         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 777       | 41.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 166       | 8.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 111       | 5.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88        | 4.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 39        | 2.1%    |
| Intel Ethernet Connection I218-LM                                 | 24        | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 1.29%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 1.13%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 1.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 19        | 1.02%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 18        | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.97%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.81%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.65%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.43%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.32%   |
| Realtek Killer E3000 2.5GbE Controller                            | 6         | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2203      | 55.59%  |
| Ethernet | 1733      | 43.73%  |
| Modem    | 23        | 0.58%   |
| Unknown  | 4         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1856      | 78.38%  |
| Ethernet | 511       | 21.58%  |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1590      | 71.46%  |
| 1     | 574       | 25.8%   |
| 0     | 42        | 1.89%   |
| 3     | 18        | 0.81%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1809      | 80.36%  |
| Yes  | 442       | 19.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1010      | 53.3%   |
| Realtek Semiconductor           | 204       | 10.77%  |
| Qualcomm Atheros Communications | 176       | 9.29%   |
| IMC Networks                    | 93        | 4.91%   |
| Broadcom                        | 87        | 4.59%   |
| Lite-On Technology              | 82        | 4.33%   |
| Foxconn / Hon Hai               | 72        | 3.8%    |
| Dell                            | 34        | 1.79%   |
| Realtek                         | 27        | 1.42%   |
| Apple                           | 25        | 1.32%   |
| Cambridge Silicon Radio         | 15        | 0.79%   |
| Ralink                          | 13        | 0.69%   |
| Hewlett-Packard                 | 13        | 0.69%   |
| Toshiba                         | 11        | 0.58%   |
| Foxconn International           | 8         | 0.42%   |
| Ralink Technology               | 5         | 0.26%   |
| ASUSTek Computer                | 4         | 0.21%   |
| Alps Electric                   | 4         | 0.21%   |
| USI                             | 2         | 0.11%   |
| TP-Link                         | 2         | 0.11%   |
| Taiyo Yuden                     | 2         | 0.11%   |
| Smart Modular Technologies      | 2         | 0.11%   |
| SINO WEALTH                     | 1         | 0.05%   |
| MediaTek                        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 348       | 18.34%  |
| Intel AX201 Bluetooth                               | 220       | 11.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 158       | 8.33%   |
| Intel AX200 Bluetooth                               | 139       | 7.33%   |
| Realtek Bluetooth Radio                             | 134       | 7.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 96        | 5.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 3.11%   |
| Intel Bluetooth Device                              | 58        | 3.06%   |
| IMC Networks Wireless_Device                        | 30        | 1.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 1.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 28        | 1.48%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.48%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 1.42%   |
| Lite-On Bluetooth Device                            | 26        | 1.37%   |
| Realtek 802.11ac WLAN Adapter                       | 24        | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 1.11%   |
| Intel AX210 Bluetooth                               | 21        | 1.11%   |
| Lite-On Wireless_Device                             | 20        | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.95%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 18        | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.84%   |
| IMC Networks Bluetooth Device                       | 15        | 0.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 0.79%   |
| Apple Bluetooth Host Controller                     | 14        | 0.74%   |
| Ralink RT3290 Bluetooth                             | 13        | 0.69%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.63%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.63%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.42%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.42%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.37%   |
| IMC Networks Bluetooth USB Host Controller          | 7         | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1759      | 62.18%  |
| AMD                              | 486       | 17.18%  |
| Nvidia                           | 368       | 13.01%  |
| Realtek Semiconductor            | 26        | 0.92%   |
| GN Netcom                        | 22        | 0.78%   |
| C-Media Electronics              | 21        | 0.74%   |
| Logitech                         | 15        | 0.53%   |
| Lenovo                           | 15        | 0.53%   |
| Hewlett-Packard                  | 14        | 0.49%   |
| Plantronics                      | 9         | 0.32%   |
| JMTek                            | 7         | 0.25%   |
| Texas Instruments                | 6         | 0.21%   |
| Razer USA                        | 6         | 0.21%   |
| Generalplus Technology           | 6         | 0.21%   |
| Creative Technology              | 5         | 0.18%   |
| Sony                             | 4         | 0.14%   |
| Dell                             | 4         | 0.14%   |
| Focusrite-Novation               | 3         | 0.11%   |
| Conexant Systems                 | 3         | 0.11%   |
| CMX Systems                      | 3         | 0.11%   |
| ZOOM                             | 2         | 0.07%   |
| Sennheiser Communications        | 2         | 0.07%   |
| Nordic Semiconductor ASA         | 2         | 0.07%   |
| Microsoft                        | 2         | 0.07%   |
| Kingston Technology              | 2         | 0.07%   |
| GYROCOM C&C                      | 2         | 0.07%   |
| Google                           | 2         | 0.07%   |
| Corsair                          | 2         | 0.07%   |
| Blue Microphones                 | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| Alesis                           | 2         | 0.07%   |
| Zhaoxin                          | 1         | 0.04%   |
| YZ Technology                    | 1         | 0.04%   |
| Winbond Electronics              | 1         | 0.04%   |
| Trust                            | 1         | 0.04%   |
| TerraTec Electronic              | 1         | 0.04%   |
| SteelSeries ApS                  | 1         | 0.04%   |
| Silicon Motion                   | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 327       | 9.45%   |
| Intel Sunrise Point-LP HD Audio                                            | 255       | 7.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 180       | 5.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 174       | 5.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 141       | 4.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 137       | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 110       | 3.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 103       | 2.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 98        | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 87        | 2.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 84        | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 82        | 2.37%   |
| Intel 8 Series HD Audio Controller                                         | 82        | 2.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 72        | 2.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 60        | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 60        | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 59        | 1.7%    |
| Intel Comet Lake PCH cAVS                                                  | 59        | 1.7%    |
| Intel Broadwell-U Audio Controller                                         | 58        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 57        | 1.65%   |
| AMD FCH Azalia Controller                                                  | 56        | 1.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 54        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 51        | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 44        | 1.27%   |
| Intel CM238 HD Audio Controller                                            | 43        | 1.24%   |
| AMD Kabini HDMI/DP Audio                                                   | 42        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 40        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 39        | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 38        | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 32        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 31        | 0.9%    |
| Realtek Semiconductor USB Audio                                            | 25        | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 25        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 25        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 25        | 0.72%   |
| Nvidia Audio device                                                        | 24        | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 24        | 0.69%   |
| Nvidia GA106 High Definition Audio Controller                              | 23        | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 21        | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 21        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 516       | 28.91%  |
| SK hynix            | 365       | 20.45%  |
| Micron Technology   | 243       | 13.61%  |
| Kingston            | 173       | 9.69%   |
| Crucial             | 113       | 6.33%   |
| Unknown             | 67        | 3.75%   |
| Ramaxel Technology  | 43        | 2.41%   |
| A-DATA Technology   | 42        | 2.35%   |
| Unknown (ABCD)      | 33        | 1.85%   |
| Elpida              | 29        | 1.62%   |
| Nanya Technology    | 22        | 1.23%   |
| Corsair             | 21        | 1.18%   |
| Smart               | 12        | 0.67%   |
| Unknown             | 12        | 0.67%   |
| Transcend           | 11        | 0.62%   |
| G.Skill             | 9         | 0.5%    |
| Wilk                | 5         | 0.28%   |
| Team                | 5         | 0.28%   |
| Smart Brazil        | 5         | 0.28%   |
| GOODRAM             | 5         | 0.28%   |
| Apacer              | 5         | 0.28%   |
| Teikon              | 4         | 0.22%   |
| Silicon Power       | 4         | 0.22%   |
| SHARETRONIC         | 3         | 0.17%   |
| Goldkey             | 3         | 0.17%   |
| ASint Technology    | 3         | 0.17%   |
| CSX                 | 2         | 0.11%   |
| AMD                 | 2         | 0.11%   |
| 4ea5                | 2         | 0.11%   |
| V-GeN               | 1         | 0.06%   |
| V-Color             | 1         | 0.06%   |
| Unknown (8AD6)      | 1         | 0.06%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (08AE)      | 1         | 0.06%   |
| Timetec             | 1         | 0.06%   |
| Super Talent        | 1         | 0.06%   |
| Shenzhen Zhongteng  | 1         | 0.06%   |
| Shenzhen WODPOSIT   | 1         | 0.06%   |
| Reboto              | 1         | 0.06%   |
| Qimonda             | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 30        | 1.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 1.07%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 1.01%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.8%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 15        | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 0.75%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 13        | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.64%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 12        | 0.64%   |
| Unknown                                                          | 12        | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 11        | 0.59%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.59%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.53%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.53%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.53%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.48%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.48%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 876       | 59.39%  |
| DDR3    | 379       | 25.69%  |
| LPDDR4  | 82        | 5.56%   |
| LPDDR3  | 43        | 2.92%   |
| DDR5    | 32        | 2.17%   |
| LPDDR5  | 21        | 1.42%   |
| DDR2    | 19        | 1.29%   |
| SDRAM   | 15        | 1.02%   |
| Unknown | 6         | 0.41%   |
| DDR     | 2         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1309      | 87.56%  |
| Row Of Chips | 157       | 10.5%   |
| Chip         | 14        | 0.94%   |
| Unknown      | 9         | 0.6%    |
| DIMM         | 6         | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 754       | 46.49%  |
| 4096  | 412       | 25.4%   |
| 16384 | 301       | 18.56%  |
| 2048  | 93        | 5.73%   |
| 32768 | 47        | 2.9%    |
| 1024  | 14        | 0.86%   |
| 12288 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 407       | 25.6%   |
| 3200    | 357       | 22.45%  |
| 1600    | 280       | 17.61%  |
| 2400    | 154       | 9.69%   |
| 2133    | 68        | 4.28%   |
| 1334    | 57        | 3.58%   |
| 1333    | 47        | 2.96%   |
| 4800    | 29        | 1.82%   |
| 4267    | 29        | 1.82%   |
| 1867    | 21        | 1.32%   |
| 6400    | 20        | 1.26%   |
| 3266    | 19        | 1.19%   |
| 8400    | 13        | 0.82%   |
| Unknown | 12        | 0.75%   |
| 1067    | 11        | 0.69%   |
| 667     | 11        | 0.69%   |
| 4199    | 10        | 0.63%   |
| 800     | 10        | 0.63%   |
| 4266    | 7         | 0.44%   |
| 2048    | 5         | 0.31%   |
| 5600    | 3         | 0.19%   |
| 1066    | 3         | 0.19%   |
| 975     | 3         | 0.19%   |
| 3000    | 2         | 0.13%   |
| 2933    | 2         | 0.13%   |
| 1866    | 2         | 0.13%   |
| 7500    | 1         | 0.06%   |
| 3733    | 1         | 0.06%   |
| 2666    | 1         | 0.06%   |
| 2000    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |
| 533     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 5         | 25%     |
| Brother Industries  | 5         | 25%     |
| Hewlett-Packard     | 4         | 20%     |
| Samsung Electronics | 3         | 15%     |
| Seiko Epson         | 2         | 10%     |
| Xerox               | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Xerox Phaser 6500DN                             | 1         | 5%      |
| Seiko Epson L3110 Series                        | 1         | 5%      |
| Seiko Epson ET-2700 Series                      | 1         | 5%      |
| Samsung Xerox Phaser 3117 Laser Printer         | 1         | 5%      |
| Samsung SCX-3200 Series                         | 1         | 5%      |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 5%      |
| HP LaserJet Professional P 1102w                | 1         | 5%      |
| HP LaserJet 1020                                | 1         | 5%      |
| HP DeskJet F300 series                          | 1         | 5%      |
| HP DeskJet 2300 series                          | 1         | 5%      |
| Canon PIXMA MX490 Series                        | 1         | 5%      |
| Canon PIXMA MP250                               | 1         | 5%      |
| Canon MF4800 Series                             | 1         | 5%      |
| Canon LBP6020                                   | 1         | 5%      |
| Canon iP2600 series                             | 1         | 5%      |
| Brother MFC-J4340DW                             | 1         | 5%      |
| Brother HL-L2390DW                              | 1         | 5%      |
| Brother HL-5450DN series                        | 1         | 5%      |
| Brother HL-2230 series                          | 1         | 5%      |
| Brother DCP-J1050DW                             | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 450       | 21.31%  |
| IMC Networks                           | 251       | 11.88%  |
| Microdia                               | 206       | 9.75%   |
| Realtek Semiconductor                  | 175       | 8.29%   |
| Bison Electronics                      | 165       | 7.81%   |
| Quanta                                 | 134       | 6.34%   |
| Sunplus Innovation Technology          | 120       | 5.68%   |
| Cheng Uei Precision Industry (Foxlink) | 96        | 4.55%   |
| Syntek                                 | 55        | 2.6%    |
| Suyin                                  | 46        | 2.18%   |
| Acer                                   | 45        | 2.13%   |
| Lite-On Technology                     | 41        | 1.94%   |
| Silicon Motion                         | 40        | 1.89%   |
| Luxvisions Innotech Limited            | 37        | 1.75%   |
| Logitech                               | 37        | 1.75%   |
| Apple                                  | 30        | 1.42%   |
| Alcor Micro                            | 21        | 0.99%   |
| Ricoh                                  | 15        | 0.71%   |
| Samsung Electronics                    | 14        | 0.66%   |
| Sonix Technology                       | 13        | 0.62%   |
| Lenovo                                 | 12        | 0.57%   |
| SunplusIT                              | 8         | 0.38%   |
| Y Media                                | 6         | 0.28%   |
| icSpring                               | 6         | 0.28%   |
| Sunplus Technology                     | 5         | 0.24%   |
| Importek                               | 5         | 0.24%   |
| Generalplus Technology                 | 5         | 0.24%   |
| Z-Star Microelectronics                | 4         | 0.19%   |
| USB Camera CS                          | 4         | 0.19%   |
| Primax Electronics                     | 4         | 0.19%   |
| Microsoft                              | 4         | 0.19%   |
| ShineTech                              | 3         | 0.14%   |
| LG Electronics                         | 3         | 0.14%   |
| Intel                                  | 3         | 0.14%   |
| Genesys Logic                          | 3         | 0.14%   |
| GEMBIRD                                | 3         | 0.14%   |
| OYT Tech                               | 2         | 0.09%   |
| Novatek Microelectronics               | 2         | 0.09%   |
| MacroSilicon                           | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 105       | 4.95%   |
| Microdia Integrated_Webcam_HD                                              | 101       | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 77        | 3.63%   |
| IMC Networks Integrated Camera                                             | 76        | 3.58%   |
| Realtek Integrated_Webcam_HD                                               | 71        | 3.34%   |
| Bison Integrated Camera                                                    | 59        | 2.78%   |
| Sunplus Integrated_Webcam_HD                                               | 56        | 2.64%   |
| Chicony HD WebCam                                                          | 43        | 2.03%   |
| Syntek Integrated Camera                                                   | 37        | 1.74%   |
| Chicony USB2.0 Camera                                                      | 31        | 1.46%   |
| Quanta HD User Facing                                                      | 29        | 1.37%   |
| Chicony HP HD Camera                                                       | 29        | 1.37%   |
| Chicony HD User Facing                                                     | 26        | 1.22%   |
| Bison HD Webcam                                                            | 25        | 1.18%   |
| Microdia Integrated Webcam                                                 | 22        | 1.04%   |
| Quanta HP TrueVision HD Camera                                             | 19        | 0.89%   |
| Quanta HP HD Camera                                                        | 18        | 0.85%   |
| Chicony Integrated Camera (1280x720@30)                                    | 18        | 0.85%   |
| Lite-On Integrated Camera                                                  | 17        | 0.8%    |
| IMC Networks HD Camera                                                     | 17        | 0.8%    |
| Quanta HD Webcam                                                           | 15        | 0.71%   |
| Chicony HP Wide Vision HD Camera                                           | 15        | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 14        | 0.66%   |
| Realtek Integrated Webcam                                                  | 14        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 14        | 0.66%   |
| Sunplus HD WebCam                                                          | 13        | 0.61%   |
| Chicony HP TrueVision HD Camera                                            | 13        | 0.61%   |
| Chicony HP TrueVision HD                                                   | 13        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 13        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 13        | 0.61%   |
| Bison Lenovo EasyCamera                                                    | 13        | 0.61%   |
| Bison BisonCam,NB Pro                                                      | 13        | 0.61%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 13        | 0.61%   |
| Realtek Integrated Webcam HD                                               | 12        | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 12        | 0.57%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 12        | 0.57%   |
| Microdia Webcam Vitade AF                                                  | 11        | 0.52%   |
| Microdia Integrated_Webcam_FHD                                             | 11        | 0.52%   |
| Logitech HD Pro Webcam C920                                                | 11        | 0.52%   |
| Chicony USB 2.0 Camera                                                     | 11        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 135       | 29.03%  |
| Validity Sensors                   | 128       | 27.53%  |
| Shenzhen Goodix Technology         | 97        | 20.86%  |
| Elan Microelectronics              | 35        | 7.53%   |
| Upek                               | 21        | 4.52%   |
| AuthenTec                          | 20        | 4.3%    |
| LighTuning Technology              | 19        | 4.09%   |
| STMicroelectronics                 | 5         | 1.08%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.65%   |
| Focal-systems.Corp                 | 2         | 0.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 61        | 13.12%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 53        | 11.4%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 5.16%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 4.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 4.09%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 3.66%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 3.01%   |
| Elan ELAN:Fingerprint                                                      | 14        | 3.01%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 2.8%    |
| Elan ELAN:ARM-M4                                                           | 13        | 2.8%    |
| Validity Sensors Synaptics WBDI                                            | 12        | 2.58%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 2.15%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.94%   |
| Synaptics UWP WBDI                                                         | 8         | 1.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 1.72%   |
| AuthenTec AES2810                                                          | 8         | 1.72%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.51%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.51%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 1.51%   |
| Validity Sensors VFS491                                                    | 6         | 1.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.29%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.29%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.08%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.08%   |
| Unknown                                                                    | 5         | 1.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 0.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.86%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.86%   |
| Synaptics  WBDI                                                            | 3         | 0.65%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.65%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.65%   |
| Synaptics WBDI Device                                                      | 2         | 0.43%   |
| Synaptics WBDI                                                             | 2         | 0.43%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 95        | 45.89%  |
| Alcor Micro               | 64        | 30.92%  |
| Upek                      | 14        | 6.76%   |
| O2 Micro                  | 9         | 4.35%   |
| Lenovo                    | 8         | 3.86%   |
| Yubico.com                | 2         | 0.97%   |
| Realtek Semiconductor     | 2         | 0.97%   |
| Clay Logic                | 2         | 0.97%   |
| Advanced Card Systems     | 2         | 0.97%   |
| Watchdata                 | 1         | 0.48%   |
| SCM Microsystems          | 1         | 0.48%   |
| In Focus Systems          | 1         | 0.48%   |
| Giesecke & Devrient       | 1         | 0.48%   |
| Fujitsu Siemens Computers | 1         | 0.48%   |
| Chicony Electronics       | 1         | 0.48%   |
| BIT4ID                    | 1         | 0.48%   |
| Aladdin R.D.              | 1         | 0.48%   |
| Aladdin Knowledge Systems | 1         | 0.48%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 64        | 30.92%  |
| Broadcom BCM5880 Secure Applications Processor                               | 26        | 12.56%  |
| Broadcom 5880                                                                | 26        | 12.56%  |
| Broadcom 58200                                                               | 26        | 12.56%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 7.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 6.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 4.35%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.86%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.97%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.97%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.97%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.97%   |
| Watchdata USB Key                                                            | 1         | 0.48%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.48%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.48%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.48%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.48%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.48%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.48%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.48%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.48%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1335      | 58.68%  |
| 1     | 747       | 32.84%  |
| 2     | 168       | 7.38%   |
| 3     | 14        | 0.62%   |
| 4     | 5         | 0.22%   |
| 7     | 3         | 0.13%   |
| 6     | 2         | 0.09%   |
| 9     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 457       | 40.02%  |
| Chipcard                 | 187       | 16.37%  |
| Graphics card            | 182       | 15.94%  |
| Net/wireless             | 99        | 8.67%   |
| Camera                   | 56        | 4.9%    |
| Multimedia controller    | 41        | 3.59%   |
| Bluetooth                | 32        | 2.8%    |
| Storage                  | 19        | 1.66%   |
| Sound                    | 19        | 1.66%   |
| Card reader              | 19        | 1.66%   |
| Communication controller | 14        | 1.23%   |
| Net/ethernet             | 7         | 0.61%   |
| Network                  | 5         | 0.44%   |
| Modem                    | 4         | 0.35%   |
| Firewire controller      | 1         | 0.09%   |

