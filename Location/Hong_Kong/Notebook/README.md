Linux in Hong Kong - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

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

Total: 566

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga 3 11 80J8              | [ff5720da27](https://linux-hardware.org/?probe=ff5720da27) | Dec 26, 2025 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [8bafafff74](https://linux-hardware.org/?probe=8bafafff74) | Dec 23, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [9dd9dfc62f](https://linux-hardware.org/?probe=9dd9dfc62f) | Dec 23, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f1d96afe71](https://linux-hardware.org/?probe=f1d96afe71) | Dec 23, 2025 |
| Fujitsu       | LIFEBOOK V1020              | [f63611f79b](https://linux-hardware.org/?probe=f63611f79b) | Dec 22, 2025 |
| Fujitsu       | FMVU34013                   | [3afe0ca1c3](https://linux-hardware.org/?probe=3afe0ca1c3) | Dec 16, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [2c3b0e220b](https://linux-hardware.org/?probe=2c3b0e220b) | Dec 16, 2025 |
| Lenovo        | ThinkBook 16 G7+ IAH 21T... | [c8e741d2ce](https://linux-hardware.org/?probe=c8e741d2ce) | Dec 10, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [276308b156](https://linux-hardware.org/?probe=276308b156) | Dec 09, 2025 |
| Dell          | Inspiron 16 Plus 7620       | [d25d0a0512](https://linux-hardware.org/?probe=d25d0a0512) | Dec 03, 2025 |
| HONOR         | FRI-HXX                     | [765d7b7fc7](https://linux-hardware.org/?probe=765d7b7fc7) | Dec 03, 2025 |
| Fujitsu       | FMVU34013                   | [7149ec0834](https://linux-hardware.org/?probe=7149ec0834) | Dec 02, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [faf634944a](https://linux-hardware.org/?probe=faf634944a) | Nov 30, 2025 |
| Lenovo        | ThinkPad neo 14 21DN0SIT... | [291e6e2290](https://linux-hardware.org/?probe=291e6e2290) | Nov 25, 2025 |
| Dell          | Latitude 7410               | [07fe957e8d](https://linux-hardware.org/?probe=07fe957e8d) | Nov 20, 2025 |
| Hampoo        | B3W6_NA123C Reserved        | [a3fc95d78e](https://linux-hardware.org/?probe=a3fc95d78e) | Nov 17, 2025 |
| Hampoo        | B3W6_NA123C Reserved        | [dff2f448f8](https://linux-hardware.org/?probe=dff2f448f8) | Nov 17, 2025 |
| Dell          | Latitude 5250               | [84d072ff2e](https://linux-hardware.org/?probe=84d072ff2e) | Nov 03, 2025 |
| Lenovo        | XiaoXinPro-13IML 2020 82... | [8fd8df0714](https://linux-hardware.org/?probe=8fd8df0714) | Oct 29, 2025 |
| Sony          | SVE15118FGB                 | [18e3aff3f6](https://linux-hardware.org/?probe=18e3aff3f6) | Oct 28, 2025 |
| Lenovo        | ThinkPad X250 20CMA03VHH    | [da27460399](https://linux-hardware.org/?probe=da27460399) | Oct 27, 2025 |
| Lenovo        | ThinkPad X250 20CMA03VHH    | [b2b1b4f09c](https://linux-hardware.org/?probe=b2b1b4f09c) | Oct 26, 2025 |
| Fujitsu       | FMVU34013                   | [24c8ceb770](https://linux-hardware.org/?probe=24c8ceb770) | Oct 10, 2025 |
| Dell          | Latitude 7300               | [34b7964b04](https://linux-hardware.org/?probe=34b7964b04) | Oct 09, 2025 |
| AVITA         | NS14A8                      | [fad18b32a5](https://linux-hardware.org/?probe=fad18b32a5) | Sep 29, 2025 |
| Acer          | Nitro AN515-52              | [26b6290bd4](https://linux-hardware.org/?probe=26b6290bd4) | Sep 26, 2025 |
| Dell          | Latitude 3500               | [d8f0e25f8d](https://linux-hardware.org/?probe=d8f0e25f8d) | Sep 22, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b2518bb0e5](https://linux-hardware.org/?probe=b2518bb0e5) | Sep 20, 2025 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [01eece29a4](https://linux-hardware.org/?probe=01eece29a4) | Sep 19, 2025 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [da3ffef159](https://linux-hardware.org/?probe=da3ffef159) | Sep 09, 2025 |
| Lenovo        | XiaoXinPro-13IML 2020 82... | [0f0af27fad](https://linux-hardware.org/?probe=0f0af27fad) | Sep 07, 2025 |
| Lenovo        | ThinkBook 14 G7+ IAH 21T... | [33de55dfbb](https://linux-hardware.org/?probe=33de55dfbb) | Sep 04, 2025 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [eb5d1959dc](https://linux-hardware.org/?probe=eb5d1959dc) | Sep 01, 2025 |
| Acer          | Aspire E5-573               | [734c6a822d](https://linux-hardware.org/?probe=734c6a822d) | Aug 18, 2025 |
| MECHREVO      | WUJIE14XA                   | [4c870d1c7c](https://linux-hardware.org/?probe=4c870d1c7c) | Aug 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [3b67c79048](https://linux-hardware.org/?probe=3b67c79048) | Jul 29, 2025 |
| HP            | EliteBook 865 16 inch G9... | [9993d2a4d3](https://linux-hardware.org/?probe=9993d2a4d3) | Jul 21, 2025 |
| Google        | Dratini                     | [9f6cc86b5a](https://linux-hardware.org/?probe=9f6cc86b5a) | Jul 19, 2025 |
| Lenovo        | ThinkBook 16 G7+ IAH 21T... | [c21c222907](https://linux-hardware.org/?probe=c21c222907) | Jul 17, 2025 |
| Lenovo        | ZHAOYANG K4e-IML 81VQ       | [054052d85f](https://linux-hardware.org/?probe=054052d85f) | Jul 17, 2025 |
| Lenovo        | ThinkBook 16 G7+ ASP 21Q... | [8fb6ddde10](https://linux-hardware.org/?probe=8fb6ddde10) | Jul 16, 2025 |
| Lenovo        | ThinkBook 14 G7+ IAH 21T... | [9d738e3caf](https://linux-hardware.org/?probe=9d738e3caf) | Jul 14, 2025 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [2c8a39de71](https://linux-hardware.org/?probe=2c8a39de71) | Jul 13, 2025 |
| Acer          | Aspire A315-34              | [38e509298f](https://linux-hardware.org/?probe=38e509298f) | Jul 09, 2025 |
| Dell          | XPS 15 9560                 | [5db4a90ee2](https://linux-hardware.org/?probe=5db4a90ee2) | Jul 04, 2025 |
| Google        | Drallion                    | [1e2ace8a8e](https://linux-hardware.org/?probe=1e2ace8a8e) | Jun 28, 2025 |
| Lenovo        | ThinkPad neo 14 21DN0SIT... | [10c3aa1f58](https://linux-hardware.org/?probe=10c3aa1f58) | Jun 13, 2025 |
| HUAWEI        | KPR-WX9                     | [0202d12c51](https://linux-hardware.org/?probe=0202d12c51) | Jun 10, 2025 |
| IBM           | 26628HH                     | [3d09ecb624](https://linux-hardware.org/?probe=3d09ecb624) | May 30, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [6b718b33d1](https://linux-hardware.org/?probe=6b718b33d1) | May 28, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [bb974deaab](https://linux-hardware.org/?probe=bb974deaab) | May 27, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [380351ae43](https://linux-hardware.org/?probe=380351ae43) | May 24, 2025 |
| MECHREVO      | Jiaolong16S Series GM6XG... | [b271d99c5b](https://linux-hardware.org/?probe=b271d99c5b) | May 20, 2025 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [1a5f82c714](https://linux-hardware.org/?probe=1a5f82c714) | May 17, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [71afc2f691](https://linux-hardware.org/?probe=71afc2f691) | May 16, 2025 |
| Apple         | MacBookPro11,5              | [e6c0541589](https://linux-hardware.org/?probe=e6c0541589) | May 15, 2025 |
| Dell          | Latitude 5401               | [0b7f2f086b](https://linux-hardware.org/?probe=0b7f2f086b) | May 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [c097ed5c2c](https://linux-hardware.org/?probe=c097ed5c2c) | May 04, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [d4bff54d53](https://linux-hardware.org/?probe=d4bff54d53) | May 03, 2025 |
| MECHREVO      | Kuangshi16Pro Series GM6... | [69dd23df24](https://linux-hardware.org/?probe=69dd23df24) | May 02, 2025 |
| MECHREVO      | JiguangPro Series GM5AR0... | [9c1613c72f](https://linux-hardware.org/?probe=9c1613c72f) | Apr 26, 2025 |
| Dell          | XPS 14 9440                 | [d0529ebc87](https://linux-hardware.org/?probe=d0529ebc87) | Apr 25, 2025 |
| Fujitsu       | FMVU28021                   | [987e66d20b](https://linux-hardware.org/?probe=987e66d20b) | Apr 12, 2025 |
| Unknown       | Unknown                     | [1f36b90b11](https://linux-hardware.org/?probe=1f36b90b11) | Apr 12, 2025 |
| Fujitsu       | FMVU28021                   | [8d352a1e20](https://linux-hardware.org/?probe=8d352a1e20) | Apr 11, 2025 |
| Unknown       | Unknown                     | [8710d0e369](https://linux-hardware.org/?probe=8710d0e369) | Apr 02, 2025 |
| Unknown       | Unknown                     | [f8904eaba5](https://linux-hardware.org/?probe=f8904eaba5) | Mar 27, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [a9d752d46c](https://linux-hardware.org/?probe=a9d752d46c) | Mar 26, 2025 |
| Unknown       | Unknown                     | [0bc234f9cb](https://linux-hardware.org/?probe=0bc234f9cb) | Mar 24, 2025 |
| ASUSTek       | TUF Gaming FX505GU_FX95G... | [97f117a4b4](https://linux-hardware.org/?probe=97f117a4b4) | Mar 24, 2025 |
| Fujitsu       | LIFEBOOK AH555              | [1d14275956](https://linux-hardware.org/?probe=1d14275956) | Mar 22, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6c736abba5](https://linux-hardware.org/?probe=6c736abba5) | Mar 21, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d858e98743](https://linux-hardware.org/?probe=d858e98743) | Mar 21, 2025 |
| Apple         | MacBookPro16,2              | [e323a2014b](https://linux-hardware.org/?probe=e323a2014b) | Mar 20, 2025 |
| Fujitsu       | FMVU28021                   | [534b846d85](https://linux-hardware.org/?probe=534b846d85) | Mar 18, 2025 |
| Fujitsu       | FMVU28021                   | [f4a2de4d6f](https://linux-hardware.org/?probe=f4a2de4d6f) | Mar 17, 2025 |
| HASEE Comp... | CV15S                       | [205e9d1dec](https://linux-hardware.org/?probe=205e9d1dec) | Mar 17, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [e9373e84e9](https://linux-hardware.org/?probe=e9373e84e9) | Mar 16, 2025 |
| Lenovo        | ThinkBook 14 G6+ IMH 21L... | [8b223477d0](https://linux-hardware.org/?probe=8b223477d0) | Mar 12, 2025 |
| Unknown       | Unknown                     | [3e0ee91248](https://linux-hardware.org/?probe=3e0ee91248) | Mar 09, 2025 |
| GPD           | G1618-04                    | [6ea7a2622a](https://linux-hardware.org/?probe=6ea7a2622a) | Feb 26, 2025 |
| Dell          | XPS 14 9440                 | [e2be8398d0](https://linux-hardware.org/?probe=e2be8398d0) | Feb 25, 2025 |
| System76      | Pangolin                    | [00e0b7296f](https://linux-hardware.org/?probe=00e0b7296f) | Feb 24, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [96cef91eca](https://linux-hardware.org/?probe=96cef91eca) | Feb 23, 2025 |
| Google        | Dratini                     | [0c643ad16e](https://linux-hardware.org/?probe=0c643ad16e) | Feb 16, 2025 |
| MECHREVO      | WUJIE14XA                   | [44b087f2ca](https://linux-hardware.org/?probe=44b087f2ca) | Feb 01, 2025 |
| Fujitsu       | LIFEBOOK AH531              | [6986e60f2e](https://linux-hardware.org/?probe=6986e60f2e) | Jan 30, 2025 |
| Lenovo        | ThinkPad X250 20CMS00400    | [46d9ac422a](https://linux-hardware.org/?probe=46d9ac422a) | Jan 17, 2025 |
| Apple         | MacBookAir7,2               | [1c4187a80e](https://linux-hardware.org/?probe=1c4187a80e) | Jan 15, 2025 |
| Lenovo        | LOQ 15IRH8 82XV             | [0ea81c2eaf](https://linux-hardware.org/?probe=0ea81c2eaf) | Jan 09, 2025 |
| Apple         | MacBookPro11,3              | [92de19ed44](https://linux-hardware.org/?probe=92de19ed44) | Dec 23, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [07d669f90a](https://linux-hardware.org/?probe=07d669f90a) | Dec 18, 2024 |
| HASEE Comp... | CV15S                       | [b1c86ea2a0](https://linux-hardware.org/?probe=b1c86ea2a0) | Dec 14, 2024 |
| Apple         | MacBook10,1                 | [5789633a9d](https://linux-hardware.org/?probe=5789633a9d) | Dec 13, 2024 |
| Unknown       | Unknown                     | [33643facc4](https://linux-hardware.org/?probe=33643facc4) | Dec 08, 2024 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [5a4b082a2e](https://linux-hardware.org/?probe=5a4b082a2e) | Dec 08, 2024 |
| Unknown       | Unknown                     | [9eddfe9de4](https://linux-hardware.org/?probe=9eddfe9de4) | Dec 02, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | [773e88d3be](https://linux-hardware.org/?probe=773e88d3be) | Nov 27, 2024 |
| Dell          | XPS 14 9440                 | [e2339b154a](https://linux-hardware.org/?probe=e2339b154a) | Nov 24, 2024 |
| Lenovo        | XiaoXinPro 14 AHP9 83D3     | [ab6b345348](https://linux-hardware.org/?probe=ab6b345348) | Nov 23, 2024 |
| HP            | ENVY Laptop 13-aq0xxx       | [2c476e1d06](https://linux-hardware.org/?probe=2c476e1d06) | Nov 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA... | [6687dc4c23](https://linux-hardware.org/?probe=6687dc4c23) | Nov 18, 2024 |
| Dell          | XPS 15 9520                 | [c1dc8bd18f](https://linux-hardware.org/?probe=c1dc8bd18f) | Nov 08, 2024 |
| Lenovo        | ThinkPad X230 23201S5       | [718e98bfa9](https://linux-hardware.org/?probe=718e98bfa9) | Nov 04, 2024 |
| Unknown       | Unknown                     | [c7f9fb9e1a](https://linux-hardware.org/?probe=c7f9fb9e1a) | Nov 04, 2024 |
| Fujitsu       | LIFEBOOK AH555              | [1d5f0ccf29](https://linux-hardware.org/?probe=1d5f0ccf29) | Nov 01, 2024 |
| Unknown       | Unknown                     | [af08761713](https://linux-hardware.org/?probe=af08761713) | Oct 24, 2024 |
| Lenovo        | Legion R9000P2021H 82JQ     | [8ce04e68a7](https://linux-hardware.org/?probe=8ce04e68a7) | Oct 21, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [c8cf89df2f](https://linux-hardware.org/?probe=c8cf89df2f) | Oct 19, 2024 |
| MECHREVO      | Yilong15Pro Series GM5HG... | [ad455330b3](https://linux-hardware.org/?probe=ad455330b3) | Oct 16, 2024 |
| Apple         | MacBookAir6,2               | [f2d560b192](https://linux-hardware.org/?probe=f2d560b192) | Oct 12, 2024 |
| Acer          | Swift SF314-512             | [43c1da6093](https://linux-hardware.org/?probe=43c1da6093) | Oct 11, 2024 |
| Fujitsu       | LIFEBOOK AH555              | [0803e75c1a](https://linux-hardware.org/?probe=0803e75c1a) | Oct 10, 2024 |
| Unknown       | Unknown                     | [b2607af0bf](https://linux-hardware.org/?probe=b2607af0bf) | Sep 30, 2024 |
| Chuwi         | HeroBook Pro                | [5761f2cb8a](https://linux-hardware.org/?probe=5761f2cb8a) | Sep 29, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [08cb9cd8a5](https://linux-hardware.org/?probe=08cb9cd8a5) | Sep 26, 2024 |
| Unknown       | Unknown                     | [5c78d4f841](https://linux-hardware.org/?probe=5c78d4f841) | Sep 26, 2024 |
| ASUSTek       | K53SV                       | [d0243fad24](https://linux-hardware.org/?probe=d0243fad24) | Sep 23, 2024 |
| Lenovo        | Legion R7000 2020 82B6      | [6f7f645005](https://linux-hardware.org/?probe=6f7f645005) | Sep 16, 2024 |
| Fujitsu       | UH-X                        | [981737896a](https://linux-hardware.org/?probe=981737896a) | Sep 15, 2024 |
| Dell          | Precision 3541              | [2ab0c627bf](https://linux-hardware.org/?probe=2ab0c627bf) | Sep 14, 2024 |
| Apple         | MacBookAir6,2               | [41e5b4b4a3](https://linux-hardware.org/?probe=41e5b4b4a3) | Sep 11, 2024 |
| HONOR         | GLO-NX6                     | [c9df4596f4](https://linux-hardware.org/?probe=c9df4596f4) | Aug 22, 2024 |
| Acer          | Nitro AN515-57              | [805a90f139](https://linux-hardware.org/?probe=805a90f139) | Aug 19, 2024 |
| Unknown       | Unknown                     | [8afc1dbdf1](https://linux-hardware.org/?probe=8afc1dbdf1) | Aug 17, 2024 |
| Acer          | Swift SF514-55TA            | [b38d9c784d](https://linux-hardware.org/?probe=b38d9c784d) | Aug 16, 2024 |
| Unknown       | Unknown                     | [4ef8a514bb](https://linux-hardware.org/?probe=4ef8a514bb) | Aug 11, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [def46f775c](https://linux-hardware.org/?probe=def46f775c) | Aug 05, 2024 |
| Apple         | MacBookAir6,2               | [40d6662f45](https://linux-hardware.org/?probe=40d6662f45) | Aug 04, 2024 |
| Nexstgo       | NS14N1                      | [72d1f788cf](https://linux-hardware.org/?probe=72d1f788cf) | Aug 04, 2024 |
| Unknown       | Unknown                     | [24f692b500](https://linux-hardware.org/?probe=24f692b500) | Aug 04, 2024 |
| Chuwi         | Hi10 Go                     | [ad6318a578](https://linux-hardware.org/?probe=ad6318a578) | Jul 31, 2024 |
| Acer          | Nitro AN515-58              | [5fd8362319](https://linux-hardware.org/?probe=5fd8362319) | Jul 29, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [74f5e078c6](https://linux-hardware.org/?probe=74f5e078c6) | Jul 27, 2024 |
| MECHREVO      | WUJIE14XA                   | [d422024c89](https://linux-hardware.org/?probe=d422024c89) | Jul 22, 2024 |
| Lenovo        | ThinkBook 14 G5+ APO 21J... | [c544d39f9f](https://linux-hardware.org/?probe=c544d39f9f) | Jul 20, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [1a0b5dd4f4](https://linux-hardware.org/?probe=1a0b5dd4f4) | Jul 16, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [305c283665](https://linux-hardware.org/?probe=305c283665) | Jul 13, 2024 |
| Apple         | MacBookAir6,2               | [39095eabda](https://linux-hardware.org/?probe=39095eabda) | Jul 13, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [4769331d3b](https://linux-hardware.org/?probe=4769331d3b) | Jul 12, 2024 |
| System76      | Bonobo WS                   | [f29db971cf](https://linux-hardware.org/?probe=f29db971cf) | Jul 09, 2024 |
| Apple         | MacBookAir5,2               | [493d11b7ef](https://linux-hardware.org/?probe=493d11b7ef) | Jul 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [4d65aeea9b](https://linux-hardware.org/?probe=4d65aeea9b) | Jun 21, 2024 |
| Lenovo        | ThinkPad T460p 20FWA00PC... | [7e6b842321](https://linux-hardware.org/?probe=7e6b842321) | Jun 21, 2024 |
| Lenovo        | ThinkPad T460p 20FWA00PC... | [f214e8aea1](https://linux-hardware.org/?probe=f214e8aea1) | Jun 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [1c939e95a3](https://linux-hardware.org/?probe=1c939e95a3) | Jun 21, 2024 |
| Acer          | Aspire EC-470G              | [917d3d0335](https://linux-hardware.org/?probe=917d3d0335) | Jun 16, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [9fe889a23e](https://linux-hardware.org/?probe=9fe889a23e) | Jun 14, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [1ac37bcaea](https://linux-hardware.org/?probe=1ac37bcaea) | Jun 14, 2024 |
| Fujitsu       | LIFEBOOK AH555              | [6b46d91566](https://linux-hardware.org/?probe=6b46d91566) | Jun 07, 2024 |
| Fujitsu       | LIFEBOOK AH555              | [ae77cd2e47](https://linux-hardware.org/?probe=ae77cd2e47) | Jun 07, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [6712e54c02](https://linux-hardware.org/?probe=6712e54c02) | Jun 07, 2024 |
| Lenovo        | G710 20252                  | [2cb3e53b29](https://linux-hardware.org/?probe=2cb3e53b29) | May 31, 2024 |
| MECHREVO      | WUJIE14S                    | [19285731aa](https://linux-hardware.org/?probe=19285731aa) | May 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [67491fabd0](https://linux-hardware.org/?probe=67491fabd0) | May 29, 2024 |
| Unknown       | Unknown                     | [c6e7aa154b](https://linux-hardware.org/?probe=c6e7aa154b) | May 25, 2024 |
| MECHREVO      | WUJIE14S                    | [cf165908f2](https://linux-hardware.org/?probe=cf165908f2) | May 25, 2024 |
| Unknown       | Unknown                     | [c9b4ab2b7c](https://linux-hardware.org/?probe=c9b4ab2b7c) | May 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [2d3edc3820](https://linux-hardware.org/?probe=2d3edc3820) | May 20, 2024 |
| Sony          | VGN-TZ27GN_B                | [c5a2d5eb61](https://linux-hardware.org/?probe=c5a2d5eb61) | May 20, 2024 |
| Dell          | Precision M4800             | [5c452ec8a1](https://linux-hardware.org/?probe=5c452ec8a1) | May 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [dd5fb659cb](https://linux-hardware.org/?probe=dd5fb659cb) | May 08, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [c741f249e2](https://linux-hardware.org/?probe=c741f249e2) | May 06, 2024 |
| Unknown       | Unknown                     | [a857b08dd7](https://linux-hardware.org/?probe=a857b08dd7) | May 06, 2024 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [d98a742595](https://linux-hardware.org/?probe=d98a742595) | Apr 27, 2024 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [1680c3ad15](https://linux-hardware.org/?probe=1680c3ad15) | Apr 27, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [4324e618e8](https://linux-hardware.org/?probe=4324e618e8) | Apr 27, 2024 |
| Unknown       | Unknown                     | [a1db5a84e2](https://linux-hardware.org/?probe=a1db5a84e2) | Apr 26, 2024 |
| GPD           | G1619-04                    | [ad6e53094b](https://linux-hardware.org/?probe=ad6e53094b) | Apr 25, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [d93809116b](https://linux-hardware.org/?probe=d93809116b) | Apr 20, 2024 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [b431117c61](https://linux-hardware.org/?probe=b431117c61) | Apr 19, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | [fd2fc14275](https://linux-hardware.org/?probe=fd2fc14275) | Apr 12, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU605MI... | [042218f2b2](https://linux-hardware.org/?probe=042218f2b2) | Apr 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [0b20dc1c09](https://linux-hardware.org/?probe=0b20dc1c09) | Mar 30, 2024 |
| Unknown       | Unknown                     | [393d39e7a2](https://linux-hardware.org/?probe=393d39e7a2) | Mar 30, 2024 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [13225bc9d9](https://linux-hardware.org/?probe=13225bc9d9) | Mar 24, 2024 |
| Timi          | A35                         | [9f32e40385](https://linux-hardware.org/?probe=9f32e40385) | Mar 23, 2024 |
| ASUSTek       | GL552VW                     | [ebcb3dcdc3](https://linux-hardware.org/?probe=ebcb3dcdc3) | Mar 22, 2024 |
| MSI           | Alpha 17 C7VF               | [6103abec4d](https://linux-hardware.org/?probe=6103abec4d) | Mar 21, 2024 |
| MSI           | Alpha 17 C7VF               | [06e6614098](https://linux-hardware.org/?probe=06e6614098) | Mar 20, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [3bd908f059](https://linux-hardware.org/?probe=3bd908f059) | Mar 19, 2024 |
| Lenovo        | Legion Y9000P IRX8 82WK     | [4e51bba561](https://linux-hardware.org/?probe=4e51bba561) | Mar 18, 2024 |
| Fujitsu       | UH-X                        | [570594b1b8](https://linux-hardware.org/?probe=570594b1b8) | Mar 16, 2024 |
| Fujitsu       | UH-X                        | [fee081fe33](https://linux-hardware.org/?probe=fee081fe33) | Mar 10, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [1724afc932](https://linux-hardware.org/?probe=1724afc932) | Mar 06, 2024 |
| Unknown       | Unknown                     | [23114923e2](https://linux-hardware.org/?probe=23114923e2) | Mar 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8a9129741b](https://linux-hardware.org/?probe=8a9129741b) | Feb 27, 2024 |
| Unknown       | Unknown                     | [5f71daec56](https://linux-hardware.org/?probe=5f71daec56) | Feb 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [18e097cb5e](https://linux-hardware.org/?probe=18e097cb5e) | Feb 23, 2024 |
| Lenovo        | ThinkPad S2 20GJS00M00      | [85d2475b2b](https://linux-hardware.org/?probe=85d2475b2b) | Feb 21, 2024 |
| Lenovo        | ThinkBook 14 G6+ IMH 21L... | [15b4b910e3](https://linux-hardware.org/?probe=15b4b910e3) | Feb 20, 2024 |
| Lenovo        | ThinkBook 14 G6+ IMH 21L... | [3ba9848db3](https://linux-hardware.org/?probe=3ba9848db3) | Feb 20, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [a38ae05794](https://linux-hardware.org/?probe=a38ae05794) | Feb 20, 2024 |
| ASUSTek       | UX331UN                     | [f37b6ea077](https://linux-hardware.org/?probe=f37b6ea077) | Feb 17, 2024 |
| Lenovo        | ThinkPad L13 Gen 3a 4810... | [b26cbf0a95](https://linux-hardware.org/?probe=b26cbf0a95) | Feb 13, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6574b9929b](https://linux-hardware.org/?probe=6574b9929b) | Feb 08, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [7cbebba117](https://linux-hardware.org/?probe=7cbebba117) | Feb 02, 2024 |
| AMI           | Intel                       | [6d3ac84f15](https://linux-hardware.org/?probe=6d3ac84f15) | Feb 01, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [531a090457](https://linux-hardware.org/?probe=531a090457) | Feb 01, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [33490eaaf1](https://linux-hardware.org/?probe=33490eaaf1) | Jan 31, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [a3b9804ccf](https://linux-hardware.org/?probe=a3b9804ccf) | Jan 30, 2024 |
| Lenovo        | ZHAOYANG K4e-IIL 81Y2       | [a318e3a69e](https://linux-hardware.org/?probe=a318e3a69e) | Jan 17, 2024 |
| Notebook      | P15SM-A/SM1-A               | [bc817396a6](https://linux-hardware.org/?probe=bc817396a6) | Jan 16, 2024 |
| Acer          | Nitro AN515-58              | [23ad168a68](https://linux-hardware.org/?probe=23ad168a68) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [a16f0bdbca](https://linux-hardware.org/?probe=a16f0bdbca) | Jan 08, 2024 |
| Fujitsu       | UH-X                        | [fae98e772d](https://linux-hardware.org/?probe=fae98e772d) | Jan 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [8213f6a90c](https://linux-hardware.org/?probe=8213f6a90c) | Jan 04, 2024 |
| KUU           | Andes II                    | [bda39c51cd](https://linux-hardware.org/?probe=bda39c51cd) | Jan 03, 2024 |
| Unknown       | Unknown                     | [6133ac662c](https://linux-hardware.org/?probe=6133ac662c) | Jan 03, 2024 |
| Unknown       | Unknown                     | [6519663043](https://linux-hardware.org/?probe=6519663043) | Jan 02, 2024 |
| Notebook      | P15SM-A/SM1-A               | [ed3bd04f1a](https://linux-hardware.org/?probe=ed3bd04f1a) | Jan 02, 2024 |
| Notebook      | N13xWU                      | [b88a27e565](https://linux-hardware.org/?probe=b88a27e565) | Jan 02, 2024 |
| Google        | Caroline                    | [8b3ec77c48](https://linux-hardware.org/?probe=8b3ec77c48) | Jan 02, 2024 |
| Google        | Caroline                    | [95fb0e423e](https://linux-hardware.org/?probe=95fb0e423e) | Jan 01, 2024 |
| Notebook      | N13xWU                      | [d877ecb7be](https://linux-hardware.org/?probe=d877ecb7be) | Jan 01, 2024 |
| Google        | Caroline                    | [94a1dd78ec](https://linux-hardware.org/?probe=94a1dd78ec) | Dec 31, 2023 |
| Google        | Caroline                    | [0d1ce09fbd](https://linux-hardware.org/?probe=0d1ce09fbd) | Dec 31, 2023 |
| Unknown       | Unknown                     | [e67f78cf16](https://linux-hardware.org/?probe=e67f78cf16) | Dec 30, 2023 |
| Alienware     | x17 R2                      | [b439c4c2a9](https://linux-hardware.org/?probe=b439c4c2a9) | Dec 29, 2023 |
| Chuwi         | MiniBook X                  | [6249e8f644](https://linux-hardware.org/?probe=6249e8f644) | Dec 27, 2023 |
| Unknown       | Unknown                     | [a013d585d9](https://linux-hardware.org/?probe=a013d585d9) | Dec 24, 2023 |
| Dell          | Latitude E6430s             | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [adb83b1dca](https://linux-hardware.org/?probe=adb83b1dca) | Dec 20, 2023 |
| Acer          | Swift SF314-54              | [4d8fbbd6d0](https://linux-hardware.org/?probe=4d8fbbd6d0) | Dec 19, 2023 |
| Apple         | MacBookAir6,2               | [d1d3bc7a1c](https://linux-hardware.org/?probe=d1d3bc7a1c) | Dec 16, 2023 |
| Unknown       | Unknown                     | [071d7464d1](https://linux-hardware.org/?probe=071d7464d1) | Dec 15, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [ab468a9a14](https://linux-hardware.org/?probe=ab468a9a14) | Dec 13, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [df2900565f](https://linux-hardware.org/?probe=df2900565f) | Dec 12, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | [ef45ef93ac](https://linux-hardware.org/?probe=ef45ef93ac) | Dec 05, 2023 |
| Unknown       | Unknown                     | [a74febcadd](https://linux-hardware.org/?probe=a74febcadd) | Dec 04, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [a749e7b6c5](https://linux-hardware.org/?probe=a749e7b6c5) | Nov 23, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [47870e4c12](https://linux-hardware.org/?probe=47870e4c12) | Nov 13, 2023 |
| Unknown       | Unknown                     | [f90d872043](https://linux-hardware.org/?probe=f90d872043) | Nov 05, 2023 |
| Lenovo        | G770 20089                  | [8428ba05f5](https://linux-hardware.org/?probe=8428ba05f5) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [6a3e8e996e](https://linux-hardware.org/?probe=6a3e8e996e) | Oct 20, 2023 |
| MECHREVO      | WUJIE14 PRO                 | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | [422e2e497a](https://linux-hardware.org/?probe=422e2e497a) | Oct 15, 2023 |
| Lenovo        | G770 20089                  | [b8d4374337](https://linux-hardware.org/?probe=b8d4374337) | Oct 14, 2023 |
| Lenovo        | G770 20089                  | [eefc449148](https://linux-hardware.org/?probe=eefc449148) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| ASUSTek       | ROG Strix G732LWS_G732LW... | [cc1f103b33](https://linux-hardware.org/?probe=cc1f103b33) | Oct 12, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [ae56dcb316](https://linux-hardware.org/?probe=ae56dcb316) | Oct 12, 2023 |
| Unknown       | Unknown                     | [3f4a876b18](https://linux-hardware.org/?probe=3f4a876b18) | Oct 08, 2023 |
| Apple         | MacBookAir6,2               | [a716f2a182](https://linux-hardware.org/?probe=a716f2a182) | Oct 06, 2023 |
| Valve         | Jupiter                     | [54eaf1a92d](https://linux-hardware.org/?probe=54eaf1a92d) | Oct 04, 2023 |
| Unknown       | Unknown                     | [b3a1f027db](https://linux-hardware.org/?probe=b3a1f027db) | Oct 03, 2023 |
| Toshiba       | PORTEGE R830                | [beaf871c4c](https://linux-hardware.org/?probe=beaf871c4c) | Oct 01, 2023 |
| Unknown       | Unknown                     | [539887ee9a](https://linux-hardware.org/?probe=539887ee9a) | Sep 23, 2023 |
| Unknown       | Unknown                     | [5e399c56a0](https://linux-hardware.org/?probe=5e399c56a0) | Sep 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| HUAWEI        | MACHD-WXX9                  | [2e74e88e2f](https://linux-hardware.org/?probe=2e74e88e2f) | Aug 31, 2023 |
| Dell          | XPS 13 9300                 | [ca90d2134f](https://linux-hardware.org/?probe=ca90d2134f) | Aug 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| Lenovo        | V130-15IKB 81HN             | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| Unknown       | Unknown                     | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Fujitsu       | UH-X                        | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [a089f6ff62](https://linux-hardware.org/?probe=a089f6ff62) | Aug 05, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [dd11fc89fe](https://linux-hardware.org/?probe=dd11fc89fe) | Aug 02, 2023 |
| Chuwi         | HeroBook Pro                | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| Unknown       | Unknown                     | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| HP            | Laptop 15s-du3xxx           | [e14cb2c24e](https://linux-hardware.org/?probe=e14cb2c24e) | Jul 25, 2023 |
| HUAWEI        | MACHC-WAX9                  | [bddace9995](https://linux-hardware.org/?probe=bddace9995) | Jul 25, 2023 |
| ASUSTek       | S551LB                      | [edfa5090fc](https://linux-hardware.org/?probe=edfa5090fc) | Jul 21, 2023 |
| Unknown       | Unknown                     | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [c060069870](https://linux-hardware.org/?probe=c060069870) | Jul 07, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| Google        | Nami                        | [6ffc403580](https://linux-hardware.org/?probe=6ffc403580) | Jun 29, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| HUAWEI        | MACH-WX9                    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI        | MACH-WX9                    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| Unknown       | Unknown                     | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a67c1e25b2](https://linux-hardware.org/?probe=a67c1e25b2) | Jun 11, 2023 |
| ASUSTek       | S400CA                      | [25c1d47331](https://linux-hardware.org/?probe=25c1d47331) | Jun 08, 2023 |
| Unknown       | Unknown                     | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| GPD           | G1619-04                    | [49b9e4edd3](https://linux-hardware.org/?probe=49b9e4edd3) | May 28, 2023 |
| GPD           | G1619-04                    | [caa6b5459d](https://linux-hardware.org/?probe=caa6b5459d) | May 28, 2023 |
| Chuwi         | HeroBook Pro                | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2bfe226026](https://linux-hardware.org/?probe=2bfe226026) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c2ccca0208](https://linux-hardware.org/?probe=c2ccca0208) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| Fujitsu       | FMVNU6G1C                   | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [65cce76dc9](https://linux-hardware.org/?probe=65cce76dc9) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 33233QM       | [f84da542f6](https://linux-hardware.org/?probe=f84da542f6) | Apr 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| MACHENIKE     | T58-V                       | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Dell          | XPS 17 9710                 | [b4c155dc99](https://linux-hardware.org/?probe=b4c155dc99) | Apr 07, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| METAPHYUNI    | MetamechBook                | [7e4076cb61](https://linux-hardware.org/?probe=7e4076cb61) | Mar 24, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Dell          | XPS 13 9300                 | [fc803f9205](https://linux-hardware.org/?probe=fc803f9205) | Feb 27, 2023 |
| Valve         | Jupiter                     | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| Dell          | XPS 15 9570                 | [81cfc27f9e](https://linux-hardware.org/?probe=81cfc27f9e) | Feb 20, 2023 |
| Valve         | Jupiter                     | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [58bcb8bf04](https://linux-hardware.org/?probe=58bcb8bf04) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | Y430P 20435                 | [da3030daae](https://linux-hardware.org/?probe=da3030daae) | Feb 16, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | [6a223f0a71](https://linux-hardware.org/?probe=6a223f0a71) | Feb 15, 2023 |
| ASUSTek       | X705UA                      | [cc59e95283](https://linux-hardware.org/?probe=cc59e95283) | Feb 07, 2023 |
| ASUSTek       | X705UA                      | [25188e7cfa](https://linux-hardware.org/?probe=25188e7cfa) | Feb 07, 2023 |
| Timi          | TM1613                      | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Valve         | Jupiter                     | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Valve         | Jupiter                     | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | [6d6a8e4be4](https://linux-hardware.org/?probe=6d6a8e4be4) | Jan 24, 2023 |
| Acer          | Swift SF314-57G             | [ae9de10584](https://linux-hardware.org/?probe=ae9de10584) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7cb08d37fb](https://linux-hardware.org/?probe=7cb08d37fb) | Jan 14, 2023 |
| Dell          | XPS 15 9520                 | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| HP            | Stream Notebook PC 13       | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Apple         | MacBookAir5,2               | [641b77c3da](https://linux-hardware.org/?probe=641b77c3da) | Dec 20, 2022 |
| GPD           | P2 MAX                      | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| GPD           | P2 MAX                      | [63c199f475](https://linux-hardware.org/?probe=63c199f475) | Dec 08, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [706e40ed5a](https://linux-hardware.org/?probe=706e40ed5a) | Dec 04, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [aff020417f](https://linux-hardware.org/?probe=aff020417f) | Dec 01, 2022 |
| Dell          | Latitude 7390               | [7214cac96d](https://linux-hardware.org/?probe=7214cac96d) | Nov 30, 2022 |
| Dell          | Inspiron N4050              | [7b0cf2fa20](https://linux-hardware.org/?probe=7b0cf2fa20) | Nov 30, 2022 |
| GPD           | G1619-04                    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Dell          | XPS 15 9570                 | [468f8df590](https://linux-hardware.org/?probe=468f8df590) | Nov 06, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8ebbbf93e4](https://linux-hardware.org/?probe=8ebbbf93e4) | Oct 17, 2022 |
| AMI           | Cherry Trail CR             | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| HP            | ZHAN 66 Pro A 14 inch G5... | [c5587dbec5](https://linux-hardware.org/?probe=c5587dbec5) | Oct 04, 2022 |
| Fujitsu       | FMVNU6G1C                   | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7c8030e423](https://linux-hardware.org/?probe=7c8030e423) | Sep 26, 2022 |
| Dell          | Latitude E5250              | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| Chuwi         | HeroBook Pro                | [76be3ff1db](https://linux-hardware.org/?probe=76be3ff1db) | Sep 22, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| Chuwi         | HeroBook Pro                | [3759658825](https://linux-hardware.org/?probe=3759658825) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| Apple         | MacBookPro15,2              | [5160feeaf2](https://linux-hardware.org/?probe=5160feeaf2) | Sep 13, 2022 |
| Apple         | MacBookPro15,2              | [876e87c7b6](https://linux-hardware.org/?probe=876e87c7b6) | Sep 13, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4562797ebc](https://linux-hardware.org/?probe=4562797ebc) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | [d0ddfb5815](https://linux-hardware.org/?probe=d0ddfb5815) | Sep 07, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | [90aed4d5d1](https://linux-hardware.org/?probe=90aed4d5d1) | Aug 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c32d69a956](https://linux-hardware.org/?probe=c32d69a956) | Aug 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| Lenovo        | ThinkPad T490s 20NYS79X0... | [5fe4fba501](https://linux-hardware.org/?probe=5fe4fba501) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Acer          | Swift SF314-512             | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| HP            | ZBook 17 G3                 | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| KOHJINSHA     | SC series                   | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Fujitsu       | LIFEBOOK V1020              | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| IBM           | 260921H                     | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | [f3e0ebd16e](https://linux-hardware.org/?probe=f3e0ebd16e) | Jul 15, 2022 |
| IBM           | 260921H                     | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Acer          | Swift SF314-42              | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Compaq        | Tablet PC TC1000            | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [044be44d33](https://linux-hardware.org/?probe=044be44d33) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Dell          | XPS 15 9520                 | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Dell          | XPS 15 9520                 | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | [e3df184136](https://linux-hardware.org/?probe=e3df184136) | Jun 12, 2022 |
| Dell          | XPS 13 9305                 | [e373d39f20](https://linux-hardware.org/?probe=e373d39f20) | Jun 09, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| ASUSTek       | N501VW                      | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Dell          | XPS 15 9520                 | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [63fd75f1a8](https://linux-hardware.org/?probe=63fd75f1a8) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| Dell          | XPS 15 9520                 | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Intel Clie... | LAPKC71F                    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Dell          | Precision 7520              | [2dc98a1a8d](https://linux-hardware.org/?probe=2dc98a1a8d) | Apr 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [9191742453](https://linux-hardware.org/?probe=9191742453) | Apr 26, 2022 |
| Apple         | MacBookAir5,1               | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| GPD           | P2 MAX                      | [ca842dc5fb](https://linux-hardware.org/?probe=ca842dc5fb) | Apr 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [bdca066ba3](https://linux-hardware.org/?probe=bdca066ba3) | Apr 05, 2022 |
| Dell          | Inspiron 14 5410            | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | [a881a875bd](https://linux-hardware.org/?probe=a881a875bd) | Mar 27, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [2d48cb4419](https://linux-hardware.org/?probe=2d48cb4419) | Mar 26, 2022 |
| Dell          | Latitude 7285               | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [03b27c8ca4](https://linux-hardware.org/?probe=03b27c8ca4) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [c68cec2207](https://linux-hardware.org/?probe=c68cec2207) | Mar 11, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [96b36779e0](https://linux-hardware.org/?probe=96b36779e0) | Mar 11, 2022 |
| HP            | Notebook                    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| HP            | Notebook                    | [c7d735dc99](https://linux-hardware.org/?probe=c7d735dc99) | Mar 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [0f4fad19b2](https://linux-hardware.org/?probe=0f4fad19b2) | Feb 07, 2022 |
| Dell          | Inspiron 5580               | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| HP            | EliteBook 830 G5            | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK LH530              | [8db7409ab5](https://linux-hardware.org/?probe=8db7409ab5) | Dec 14, 2021 |
| Unknown       | Unknown                     | [739be994cb](https://linux-hardware.org/?probe=739be994cb) | Dec 09, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [024a42eb21](https://linux-hardware.org/?probe=024a42eb21) | Dec 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ee13ae89af](https://linux-hardware.org/?probe=ee13ae89af) | Nov 26, 2021 |
| Apple         | MacBook10,1                 | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Jumper        | EZbook                      | [5da2b95e2f](https://linux-hardware.org/?probe=5da2b95e2f) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Unknown       | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| HP            | Laptop 15s-du3xxx           | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [3d42bc888b](https://linux-hardware.org/?probe=3d42bc888b) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [54e54e71bd](https://linux-hardware.org/?probe=54e54e71bd) | Oct 24, 2021 |
| Dell          | XPS 13 9310                 | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Lenovo        | Legion Y9000P2021H 82JD     | [4c3be0fe24](https://linux-hardware.org/?probe=4c3be0fe24) | Oct 02, 2021 |
| GPD           | G1618-03                    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| Dell          | Precision 7550              | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Lenovo        | XiaoXin-14API QC 2019 81... | [814eb97442](https://linux-hardware.org/?probe=814eb97442) | Aug 14, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| HP            | EliteBook 2540p             | [eb060cd2c4](https://linux-hardware.org/?probe=eb060cd2c4) | Aug 04, 2021 |
| Toshiba       | dynabook R731/E             | [828a52387f](https://linux-hardware.org/?probe=828a52387f) | Aug 02, 2021 |
| Toshiba       | dynabook R731/E             | [12b2c3e130](https://linux-hardware.org/?probe=12b2c3e130) | Aug 01, 2021 |
| Toshiba       | dynabook R731/E             | [3af43c8ebe](https://linux-hardware.org/?probe=3af43c8ebe) | Jul 29, 2021 |
| Toshiba       | dynabook R731/E             | [fa0aa86cef](https://linux-hardware.org/?probe=fa0aa86cef) | Jul 28, 2021 |
| Unknown       | Unknown                     | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| Toshiba       | dynabook R731/E             | [c2bfccf320](https://linux-hardware.org/?probe=c2bfccf320) | Jun 16, 2021 |
| Toshiba       | dynabook R731/E             | [d3f69874dd](https://linux-hardware.org/?probe=d3f69874dd) | Jun 16, 2021 |
| Dell          | Precision M4800             | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| Acer          | Aspire E5-573               | [4193a2da9d](https://linux-hardware.org/?probe=4193a2da9d) | Jun 08, 2021 |
| Dell          | Precision M4800             | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| Toshiba       | dynabook R731/E             | [81ffc7ba9e](https://linux-hardware.org/?probe=81ffc7ba9e) | May 26, 2021 |
| Fujitsu       | UH-X                        | [be65091e59](https://linux-hardware.org/?probe=be65091e59) | May 19, 2021 |
| Panasonic     | CFSZ5-2L                    | [1409e11b30](https://linux-hardware.org/?probe=1409e11b30) | May 12, 2021 |
| Dell          | XPS 13 9310                 | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| Panasonic     | CFSZ5-2L                    | [f35a966b00](https://linux-hardware.org/?probe=f35a966b00) | Apr 14, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [a917367457](https://linux-hardware.org/?probe=a917367457) | Apr 09, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | [f7937503ac](https://linux-hardware.org/?probe=f7937503ac) | Apr 08, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | [99d71b6ea5](https://linux-hardware.org/?probe=99d71b6ea5) | Apr 06, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [8253b70553](https://linux-hardware.org/?probe=8253b70553) | Apr 06, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| ASUSTek       | UX302LA                     | [fe27a8e195](https://linux-hardware.org/?probe=fe27a8e195) | Mar 12, 2021 |
| Acer          | Aspire A315-34              | [d23d84b5f6](https://linux-hardware.org/?probe=d23d84b5f6) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK P771               | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | ThinkPad E14 20RAA002CD     | [77ccb1ee60](https://linux-hardware.org/?probe=77ccb1ee60) | Feb 22, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [7d9f2bee38](https://linux-hardware.org/?probe=7d9f2bee38) | Feb 21, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [d82924b12b](https://linux-hardware.org/?probe=d82924b12b) | Feb 16, 2021 |
| Lenovo        | G710 20252                  | [f4c2a6bac8](https://linux-hardware.org/?probe=f4c2a6bac8) | Feb 07, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [d4f69c78fa](https://linux-hardware.org/?probe=d4f69c78fa) | Jan 31, 2021 |
| Fujitsu       | S6420                       | [b23c0f10e7](https://linux-hardware.org/?probe=b23c0f10e7) | Jan 28, 2021 |
| Fujitsu       | S6420                       | [0cf6376b40](https://linux-hardware.org/?probe=0cf6376b40) | Jan 27, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| HUAWEI        | KPRC-WX0                    | [fe7d03f093](https://linux-hardware.org/?probe=fe7d03f093) | Jan 18, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [a8ac85cb5a](https://linux-hardware.org/?probe=a8ac85cb5a) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [8c7ba97457](https://linux-hardware.org/?probe=8c7ba97457) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [01333c5b9e](https://linux-hardware.org/?probe=01333c5b9e) | Dec 29, 2020 |
| Panasonic     | CFSZ5-2L                    | [728d7e48d4](https://linux-hardware.org/?probe=728d7e48d4) | Dec 27, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [1d4b16bb0d](https://linux-hardware.org/?probe=1d4b16bb0d) | Dec 22, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [88a7edec45](https://linux-hardware.org/?probe=88a7edec45) | Dec 18, 2020 |
| Sony          | VPCCB17FG                   | [ede3032fed](https://linux-hardware.org/?probe=ede3032fed) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | [f3012a2898](https://linux-hardware.org/?probe=f3012a2898) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | [3c4ff5bb58](https://linux-hardware.org/?probe=3c4ff5bb58) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Fujitsu       | UH-X                        | [f55a6a6679](https://linux-hardware.org/?probe=f55a6a6679) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | [7aea886f7a](https://linux-hardware.org/?probe=7aea886f7a) | Nov 20, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [6254edfb10](https://linux-hardware.org/?probe=6254edfb10) | Nov 14, 2020 |
| Lenovo        | G770 20089                  | [6da9203114](https://linux-hardware.org/?probe=6da9203114) | Nov 13, 2020 |
| HP            | 2000                        | [f548e6d1cc](https://linux-hardware.org/?probe=f548e6d1cc) | Nov 11, 2020 |
| ASUSTek       | K501UX                      | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| HP            | 2000                        | [df76d279ad](https://linux-hardware.org/?probe=df76d279ad) | Nov 05, 2020 |
| Timi          | TM1607                      | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| Acer          | Swift SF314-57              | [8395e5a946](https://linux-hardware.org/?probe=8395e5a946) | Oct 30, 2020 |
| Acer          | Swift SF314-57              | [123f60c868](https://linux-hardware.org/?probe=123f60c868) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [f9d1166197](https://linux-hardware.org/?probe=f9d1166197) | Oct 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| HP            | 2140                        | [bde3dc449f](https://linux-hardware.org/?probe=bde3dc449f) | Oct 07, 2020 |
| HUAWEI        | WRT-WX9                     | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| HP            | 2000                        | [fbd8bf0e69](https://linux-hardware.org/?probe=fbd8bf0e69) | Oct 01, 2020 |
| Fujitsu       | LIFEBOOK S904               | [5035864c45](https://linux-hardware.org/?probe=5035864c45) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | [37e6b406f7](https://linux-hardware.org/?probe=37e6b406f7) | Sep 27, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [bd8f561b0b](https://linux-hardware.org/?probe=bd8f561b0b) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | [64a249acd1](https://linux-hardware.org/?probe=64a249acd1) | Aug 28, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [6a91a7b38c](https://linux-hardware.org/?probe=6a91a7b38c) | Aug 25, 2020 |
| Samsung       | 930XBE                      | [92925e0656](https://linux-hardware.org/?probe=92925e0656) | Aug 24, 2020 |
| Dell          | Inspiron 5580               | [fbaf2b8f7f](https://linux-hardware.org/?probe=fbaf2b8f7f) | Aug 05, 2020 |
| Panasonic     | CFSZ5-2L                    | [e7488a8b16](https://linux-hardware.org/?probe=e7488a8b16) | Aug 04, 2020 |
| Toshiba       | PORTEGE R830                | [fa44f09e6e](https://linux-hardware.org/?probe=fa44f09e6e) | Aug 03, 2020 |
| Dell          | G7 7588                     | [e85e2949de](https://linux-hardware.org/?probe=e85e2949de) | Aug 01, 2020 |
| Lenovo        | ZHAOYANG K47                | [fa5be40392](https://linux-hardware.org/?probe=fa5be40392) | Jul 24, 2020 |
| Lenovo        | ZHAOYANG K47                | [879b0d586f](https://linux-hardware.org/?probe=879b0d586f) | Jul 22, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Fujitsu       | LIFEBOOK AH544              | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Lenovo        | E10-30 20424                | [c90b1cb242](https://linux-hardware.org/?probe=c90b1cb242) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | [74dadf599d](https://linux-hardware.org/?probe=74dadf599d) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | [db21903e1a](https://linux-hardware.org/?probe=db21903e1a) | Jun 14, 2020 |
| Lenovo        | ThinkPad T480s 20L7005FU... | [2bc99eeca5](https://linux-hardware.org/?probe=2bc99eeca5) | Jun 09, 2020 |
| Fujitsu       | LIFEBOOK AH556              | [c16b3d9827](https://linux-hardware.org/?probe=c16b3d9827) | May 30, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [55680319a1](https://linux-hardware.org/?probe=55680319a1) | May 29, 2020 |
| Apple         | MacBookPro7,1               | [956da1ac80](https://linux-hardware.org/?probe=956da1ac80) | May 11, 2020 |
| Toshiba       | PORTEGE R830                | [08f3e97afe](https://linux-hardware.org/?probe=08f3e97afe) | May 02, 2020 |
| Lenovo        | 3000 G410                   | [2a909aaad5](https://linux-hardware.org/?probe=2a909aaad5) | May 02, 2020 |
| Dell          | XPS 13 9370                 | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | G72                         | [6272536a26](https://linux-hardware.org/?probe=6272536a26) | Apr 11, 2020 |
| Google        | Eve                         | [17c248ca99](https://linux-hardware.org/?probe=17c248ca99) | Apr 04, 2020 |
| Dell          | Inspiron 3593               | [597092ba51](https://linux-hardware.org/?probe=597092ba51) | Feb 28, 2020 |
| Dell          | Inspiron 3593               | [71fc35ceea](https://linux-hardware.org/?probe=71fc35ceea) | Feb 28, 2020 |
| MSI           | GS73VR 7RG                  | [fbdf43d1d6](https://linux-hardware.org/?probe=fbdf43d1d6) | Feb 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cf4dbec684](https://linux-hardware.org/?probe=cf4dbec684) | Feb 01, 2020 |
| Unknown       | Unknown                     | [1007637420](https://linux-hardware.org/?probe=1007637420) | Dec 31, 2019 |
| Unknown       | Unknown                     | [bb58a92938](https://linux-hardware.org/?probe=bb58a92938) | Dec 31, 2019 |
| Dell          | XPS 13 9370                 | [0f39165d62](https://linux-hardware.org/?probe=0f39165d62) | Dec 06, 2019 |
| Dell          | XPS 13 9370                 | [816ad4feea](https://linux-hardware.org/?probe=816ad4feea) | Dec 06, 2019 |
| ASUSTek       | X556URK                     | [78f15ad5f0](https://linux-hardware.org/?probe=78f15ad5f0) | Nov 30, 2019 |
| HP            | EliteBook 2540p             | [49e2cab57b](https://linux-hardware.org/?probe=49e2cab57b) | Nov 28, 2019 |
| HUAWEI        | KPRC-WX0                    | [042c4b3c5a](https://linux-hardware.org/?probe=042c4b3c5a) | Nov 22, 2019 |
| HP            | EliteBook 2540p             | [f63dcc4fc8](https://linux-hardware.org/?probe=f63dcc4fc8) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3497939f58](https://linux-hardware.org/?probe=3497939f58) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a04ed98be8](https://linux-hardware.org/?probe=a04ed98be8) | Oct 18, 2019 |
| HP            | EliteBook 2540p             | [b2ebcf2c70](https://linux-hardware.org/?probe=b2ebcf2c70) | Oct 10, 2019 |
| HP            | EliteBook 2540p             | [43a5e168a1](https://linux-hardware.org/?probe=43a5e168a1) | Oct 10, 2019 |
| Unknown       | Unknown                     | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Acer          | Aspire S3-371               | [5086f9ddaa](https://linux-hardware.org/?probe=5086f9ddaa) | Sep 07, 2019 |
| Acer          | Aspire S3-371               | [aa8140a178](https://linux-hardware.org/?probe=aa8140a178) | Sep 03, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | [7e9553ea70](https://linux-hardware.org/?probe=7e9553ea70) | Jun 03, 2019 |
| Lenovo        | ThinkPad T430 2342AG4       | [cf7413e712](https://linux-hardware.org/?probe=cf7413e712) | May 31, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | [e8a5c28644](https://linux-hardware.org/?probe=e8a5c28644) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | [b67f52c0c2](https://linux-hardware.org/?probe=b67f52c0c2) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | [c408ceb62e](https://linux-hardware.org/?probe=c408ceb62e) | May 29, 2019 |
| Dell          | Latitude E4310              | [134afc5b6b](https://linux-hardware.org/?probe=134afc5b6b) | May 08, 2019 |
| Lenovo        | ThinkPad T520 4242BC5       | [977c44b97a](https://linux-hardware.org/?probe=977c44b97a) | Apr 29, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | [5801835e32](https://linux-hardware.org/?probe=5801835e32) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | [0f4999f205](https://linux-hardware.org/?probe=0f4999f205) | Apr 27, 2019 |
| Unknown       | A11-COMPUTER                | [fae06bb10f](https://linux-hardware.org/?probe=fae06bb10f) | Mar 28, 2019 |
| Unknown       | A11-COMPUTER                | [427daf4d4e](https://linux-hardware.org/?probe=427daf4d4e) | Mar 28, 2019 |
| Lenovo        | ThinkPad W530 24384KU       | [2064d92892](https://linux-hardware.org/?probe=2064d92892) | Dec 12, 2018 |
| Dell          | XPS 13 9350                 | [6fb539c340](https://linux-hardware.org/?probe=6fb539c340) | Oct 29, 2018 |
| HP            | ProBook 4540s               | [ace9a95fb7](https://linux-hardware.org/?probe=ace9a95fb7) | May 09, 2018 |
| HP            | ProBook 4540s               | [8f50260d94](https://linux-hardware.org/?probe=8f50260d94) | May 09, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hong_Kong/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Arch Rolling        | 39        | 10.05%  |
| Ubuntu 20.04        | 33        | 8.51%   |
| Ubuntu 22.04        | 32        | 8.25%   |
| Ubuntu 24.04        | 12        | 3.09%   |
| Ubuntu 18.04        | 9         | 2.32%   |
| Pop!_OS 22.04       | 9         | 2.32%   |
| ArcoLinux Rolling   | 9         | 2.32%   |
| antiX 21            | 9         | 2.32%   |
| Fedora 42           | 8         | 2.06%   |
| Fedora 37           | 8         | 2.06%   |
| Debian 12           | 8         | 2.06%   |
| Arch                | 8         | 2.06%   |
| Linux Mint 22.1     | 5         | 1.29%   |
| Kylin V10           | 5         | 1.29%   |
| Fedora 32           | 5         | 1.29%   |
| Ubuntu 19.10        | 4         | 1.03%   |
| OpenMandriva 23.03  | 4         | 1.03%   |
| Gentoo 2.7          | 4         | 1.03%   |
| Fedora 41           | 4         | 1.03%   |
| Fedora 40           | 4         | 1.03%   |
| Fedora 39           | 4         | 1.03%   |
| EndeavourOS Rolling | 4         | 1.03%   |
| Debian 11           | 4         | 1.03%   |
| CachyOS Rolling     | 4         | 1.03%   |
| Ubuntu 22.10        | 3         | 0.77%   |
| OpenMandriva 5.0    | 3         | 0.77%   |
| OpenMandriva 4.2    | 3         | 0.77%   |
| OpenMandriva 23.01  | 3         | 0.77%   |
| NixOS 25.05         | 3         | 0.77%   |
| Linux Mint 20       | 3         | 0.77%   |
| Fedora 36           | 3         | 0.77%   |
| Fedora 33           | 3         | 0.77%   |
| Chrome OS           | 3         | 0.77%   |
| UOS 20              | 2         | 0.52%   |
| Ubuntu MATE 22.04   | 2         | 0.52%   |
| Ubuntu 25.04        | 2         | 0.52%   |
| Ubuntu 23.10        | 2         | 0.52%   |
| Ubuntu 23.04        | 2         | 0.52%   |
| Ubuntu 21.04        | 2         | 0.52%   |
| Ubuntu 19.04        | 2         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 105       | 28.38%  |
| Arch          | 47        | 12.7%   |
| Fedora        | 41        | 11.08%  |
| OpenMandriva  | 21        | 5.68%   |
| Pop!_OS       | 16        | 4.32%   |
| Linux Mint    | 16        | 4.32%   |
| Debian        | 14        | 3.78%   |
| Gentoo        | 11        | 2.97%   |
| ArcoLinux     | 9         | 2.43%   |
| antiX         | 9         | 2.43%   |
| Kali          | 7         | 1.89%   |
| NixOS         | 6         | 1.62%   |
| Manjaro       | 6         | 1.62%   |
| Kylin         | 5         | 1.35%   |
| CachyOS       | 5         | 1.35%   |
| SteamOS       | 4         | 1.08%   |
| EndeavourOS   | 4         | 1.08%   |
| Clear Linux   | 4         | 1.08%   |
| Ubuntu Unity  | 3         | 0.81%   |
| ROSA          | 3         | 0.81%   |
| openSUSE      | 3         | 0.81%   |
| KDE neon      | 3         | 0.81%   |
| Chrome OS     | 3         | 0.81%   |
| Zorin         | 2         | 0.54%   |
| Ubuntu MATE   | 2         | 0.54%   |
| Nobara        | 2         | 0.54%   |
| Kubuntu       | 2         | 0.54%   |
| Elementary    | 2         | 0.54%   |
| Deepin        | 2         | 0.54%   |
| Bazzite       | 2         | 0.54%   |
| Xubuntu       | 1         | 0.27%   |
| Ultramarine   | 1         | 0.27%   |
| UbuntuDDE     | 1         | 0.27%   |
| Ubuntu Budgie | 1         | 0.27%   |
| RHEL          | 1         | 0.27%   |
| PCLinuxOS     | 1         | 0.27%   |
| Oracle Linux  | 1         | 0.27%   |
| Lubuntu       | 1         | 0.27%   |
| Guix          | 1         | 0.27%   |
| BlackPanther  | 1         | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp | 9         | 2.05%   |
| 5.4.0-42-generic          | 6         | 1.37%   |
| 6.6.2-desktop-1omv2390    | 5         | 1.14%   |
| 6.2.0-26-generic          | 5         | 1.14%   |
| 6.2.6-desktop-1omv2390    | 4         | 0.91%   |
| 6.3.6-arch1-1             | 3         | 0.68%   |
| 6.14.2-desktop-3omv2590   | 3         | 0.68%   |
| 6.1.1-desktop-1omv2290    | 3         | 0.68%   |
| 5.8.0-43-generic          | 3         | 0.68%   |
| 5.4.0-48-generic          | 3         | 0.68%   |
| 5.4.0-26-generic          | 3         | 0.68%   |
| 5.19.0-32-generic         | 3         | 0.68%   |
| 5.15.0-46-generic         | 3         | 0.68%   |
| 5.13.0-39-generic         | 3         | 0.68%   |
| 5.10.14-desktop-1omv4002  | 3         | 0.68%   |
| 4.19.49+                  | 3         | 0.68%   |
| 6.9.3-76060903-generic    | 2         | 0.46%   |
| 6.8.7-1-cachyos           | 2         | 0.46%   |
| 6.8.2-arch2-1             | 2         | 0.46%   |
| 6.8.0-51-generic          | 2         | 0.46%   |
| 6.8.0-47-generic          | 2         | 0.46%   |
| 6.8.0-40-generic          | 2         | 0.46%   |
| 6.8.0-35-generic          | 2         | 0.46%   |
| 6.7.5-arch1-1             | 2         | 0.46%   |
| 6.7.4-arch1-1             | 2         | 0.46%   |
| 6.6.7-arch1-1             | 2         | 0.46%   |
| 6.5.5-arch1-1             | 2         | 0.46%   |
| 6.5.0-26-generic          | 2         | 0.46%   |
| 6.5.0-14-generic          | 2         | 0.46%   |
| 6.4.11-desktop-1omv2390   | 2         | 0.46%   |
| 6.2.0-34-generic          | 2         | 0.46%   |
| 6.17.8-2-cachyos          | 2         | 0.46%   |
| 6.16.3-76061603-generic   | 2         | 0.46%   |
| 6.16.10-200.fc42.x86_64   | 2         | 0.46%   |
| 6.15.6-arch1-1            | 2         | 0.46%   |
| 6.14.0-36-generic         | 2         | 0.46%   |
| 6.14.0-29-generic         | 2         | 0.46%   |
| 6.14.0-27-generic         | 2         | 0.46%   |
| 6.14.0-24-generic         | 2         | 0.46%   |
| 6.11.2-amd64              | 2         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 5.18%   |
| 5.15.0  | 19        | 4.47%   |
| 6.8.0   | 15        | 3.53%   |
| 6.2.0   | 14        | 3.29%   |
| 5.19.0  | 13        | 3.06%   |
| 5.13.0  | 12        | 2.82%   |
| 6.5.0   | 10        | 2.35%   |
| 6.14.0  | 9         | 2.12%   |
| 5.8.0   | 9         | 2.12%   |
| 4.9.0   | 9         | 2.12%   |
| 6.1.0   | 8         | 1.88%   |
| 6.11.0  | 7         | 1.65%   |
| 4.15.0  | 7         | 1.65%   |
| 5.11.0  | 6         | 1.41%   |
| 6.6.2   | 5         | 1.18%   |
| 5.3.0   | 5         | 1.18%   |
| 5.0.0   | 5         | 1.18%   |
| 6.8.7   | 4         | 0.94%   |
| 6.2.6   | 4         | 0.94%   |
| 6.15.6  | 4         | 0.94%   |
| 5.10.0  | 4         | 0.94%   |
| 6.7.5   | 3         | 0.71%   |
| 6.6.6   | 3         | 0.71%   |
| 6.4.2   | 3         | 0.71%   |
| 6.4.11  | 3         | 0.71%   |
| 6.3.6   | 3         | 0.71%   |
| 6.17.9  | 3         | 0.71%   |
| 6.14.4  | 3         | 0.71%   |
| 6.14.2  | 3         | 0.71%   |
| 6.11.2  | 3         | 0.71%   |
| 6.1.1   | 3         | 0.71%   |
| 6.0.0   | 3         | 0.71%   |
| 5.10.14 | 3         | 0.71%   |
| 4.19.49 | 3         | 0.71%   |
| 6.9.9   | 2         | 0.47%   |
| 6.9.3   | 2         | 0.47%   |
| 6.9.1   | 2         | 0.47%   |
| 6.8.9   | 2         | 0.47%   |
| 6.8.2   | 2         | 0.47%   |
| 6.8.1   | 2         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.8     | 24        | 5.84%   |
| 6.1     | 24        | 5.84%   |
| 5.15    | 24        | 5.84%   |
| 5.4     | 22        | 5.35%   |
| 6.14    | 20        | 4.87%   |
| 5.19    | 20        | 4.87%   |
| 6.2     | 19        | 4.62%   |
| 6.6     | 17        | 4.14%   |
| 6.11    | 17        | 4.14%   |
| 6.5     | 16        | 3.89%   |
| 5.13    | 14        | 3.41%   |
| 5.10    | 14        | 3.41%   |
| 5.11    | 13        | 3.16%   |
| 5.8     | 12        | 2.92%   |
| 6.4     | 11        | 2.68%   |
| 6.12    | 11        | 2.68%   |
| 4.9     | 11        | 2.68%   |
| 6.16    | 9         | 2.19%   |
| 6.9     | 8         | 1.95%   |
| 6.10    | 8         | 1.95%   |
| 5.3     | 8         | 1.95%   |
| 5.17    | 8         | 1.95%   |
| 6.17    | 7         | 1.7%    |
| 6.15    | 7         | 1.7%    |
| 6.13    | 7         | 1.7%    |
| 6.0     | 7         | 1.7%    |
| 4.15    | 7         | 1.7%    |
| 6.7     | 6         | 1.46%   |
| 5.9     | 6         | 1.46%   |
| 6.3     | 5         | 1.22%   |
| 5.14    | 5         | 1.22%   |
| 5.0     | 5         | 1.22%   |
| 5.7     | 4         | 0.97%   |
| 5.16    | 4         | 0.97%   |
| 5.18    | 3         | 0.73%   |
| 4.19    | 3         | 0.73%   |
| 4.18    | 3         | 0.73%   |
| 5.6     | 1         | 0.24%   |
| 5.12    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 346       | 95.58%  |
| i686    | 13        | 3.59%   |
| aarch64 | 2         | 0.55%   |
| i586    | 1         | 0.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 168       | 44.09%  |
| KDE5       | 66        | 17.32%  |
| Unknown    | 38        | 9.97%   |
| KDE6       | 34        | 8.92%   |
| XFCE       | 17        | 4.46%   |
| X-Cinnamon | 13        | 3.41%   |
| i3         | 7         | 1.84%   |
| Hyprland   | 6         | 1.57%   |
| Deepin     | 6         | 1.57%   |
| KDE        | 5         | 1.31%   |
| LXQt       | 4         | 1.05%   |
| dwm        | 3         | 0.79%   |
| Unity      | 2         | 0.52%   |
| MATE       | 2         | 0.52%   |
| Sway       | 1         | 0.26%   |
| Pantheon   | 1         | 0.26%   |
| niri       | 1         | 0.26%   |
| KDE4       | 1         | 0.26%   |
| icewm      | 1         | 0.26%   |
| fvwm       | 1         | 0.26%   |
| dwl        | 1         | 0.26%   |
| COSMIC     | 1         | 0.26%   |
| Cinnamon   | 1         | 0.26%   |
| Budgie     | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 212       | 56.68%  |
| Wayland | 138       | 36.9%   |
| Unknown | 16        | 4.28%   |
| Tty     | 8         | 2.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 125       | 33.88%  |
| SDDM    | 89        | 24.12%  |
| GDM3    | 64        | 17.34%  |
| GDM     | 47        | 12.74%  |
| LightDM | 38        | 10.3%   |
| TDM     | 4         | 1.08%   |
| LXDM    | 1         | 0.27%   |
| GREETD  | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 152       | 40.11%  |
| zh_CN   | 79        | 20.84%  |
| en_HK   | 63        | 16.62%  |
| Unknown | 20        | 5.28%   |
| zh_TW   | 17        | 4.49%   |
| zh_HK   | 14        | 3.69%   |
| C       | 13        | 3.43%   |
| en_GB   | 8         | 2.11%   |
| en_AU   | 3         | 0.79%   |
| es_VE   | 2         | 0.53%   |
| zh_SG   | 1         | 0.26%   |
| ru_RU   | 1         | 0.26%   |
| pt_BR   | 1         | 0.26%   |
| ja_JP   | 1         | 0.26%   |
| it_IT   | 1         | 0.26%   |
| en_ZA   | 1         | 0.26%   |
| de_DE   | 1         | 0.26%   |
| C.UTF8  | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 264       | 72.13%  |
| BIOS | 102       | 27.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 230       | 61.99%  |
| Btrfs   | 81        | 21.83%  |
| Overlay | 22        | 5.93%   |
| Tmpfs   | 14        | 3.77%   |
| Xfs     | 9         | 2.43%   |
| Unknown | 7         | 1.89%   |
| Zfs     | 5         | 1.35%   |
| Ext2    | 2         | 0.54%   |
| Ext3    | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 233       | 63.49%  |
| Unknown | 111       | 30.25%  |
| MBR     | 23        | 6.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 322       | 87.98%  |
| Yes       | 44        | 12.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 59.78%  |
| Yes       | 148       | 40.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 125       | 34.53%  |
| ASUSTek Computer     | 39        | 10.77%  |
| Dell                 | 35        | 9.67%   |
| Hewlett-Packard      | 23        | 6.35%   |
| Fujitsu              | 18        | 4.97%   |
| Acer                 | 17        | 4.7%    |
| Apple                | 13        | 3.59%   |
| MECHREVO             | 11        | 3.04%   |
| Unknown              | 11        | 3.04%   |
| HUAWEI               | 8         | 2.21%   |
| GPD                  | 6         | 1.66%   |
| Chuwi                | 5         | 1.38%   |
| Samsung Electronics  | 4         | 1.1%    |
| Google               | 4         | 1.1%    |
| Timi                 | 3         | 0.83%   |
| Sony                 | 3         | 0.83%   |
| MSI                  | 3         | 0.83%   |
| IBM                  | 3         | 0.83%   |
| Valve                | 2         | 0.55%   |
| Toshiba              | 2         | 0.55%   |
| System76             | 2         | 0.55%   |
| Notebook             | 2         | 0.55%   |
| KOHJINSHA            | 2         | 0.55%   |
| HONOR                | 2         | 0.55%   |
| HASEE Computer       | 2         | 0.55%   |
| AMI                  | 2         | 0.55%   |
| XIAOMI               | 1         | 0.28%   |
| Schenker             | 1         | 0.28%   |
| Panasonic            | 1         | 0.28%   |
| ONE-NETBOOK          | 1         | 0.28%   |
| Nexstgo              | 1         | 0.28%   |
| METAPHYUNI           | 1         | 0.28%   |
| MACHENIKE            | 1         | 0.28%   |
| LG Electronics       | 1         | 0.28%   |
| KUU                  | 1         | 0.28%   |
| Jumper               | 1         | 0.28%   |
| Intel Client Systems | 1         | 0.28%   |
| Hampoo               | 1         | 0.28%   |
| Compaq               | 1         | 0.28%   |
| AVITA                | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 12        | 3.31%   |
| Lenovo LOQ 15IRH8 82XV               | 4         | 1.1%    |
| MECHREVO WUJIE14XA                   | 3         | 0.83%   |
| MECHREVO WUJIE14 PRO                 | 3         | 0.83%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0     | 3         | 0.83%   |
| Lenovo Legion R7000 2020 82B6        | 3         | 0.83%   |
| GPD G1619-04                         | 3         | 0.83%   |
| Chuwi HeroBook Pro                   | 3         | 0.83%   |
| Valve Jupiter                        | 2         | 0.55%   |
| Lenovo XiaoXinPro-13IML 2020 82DN    | 2         | 0.55%   |
| Lenovo XiaoXinPro 14ITL 2021 82GH    | 2         | 0.55%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN    | 2         | 0.55%   |
| Lenovo ThinkPad T14 Gen 5 21MCCTO1WW | 2         | 0.55%   |
| Lenovo ThinkBook 16 G7+ IAH 21TL     | 2         | 0.55%   |
| Lenovo ThinkBook 14p Gen 2 20YN      | 2         | 0.55%   |
| Lenovo ThinkBook 14 G6+ IMH 21LD     | 2         | 0.55%   |
| Lenovo Legion R9000P ARX8 82WM       | 2         | 0.55%   |
| Lenovo G770 20089                    | 2         | 0.55%   |
| IBM 260921H                          | 2         | 0.55%   |
| HUAWEI KPRC-WX0                      | 2         | 0.55%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC     | 2         | 0.55%   |
| HP Pavilion Gaming Laptop 15-ec2xxx  | 2         | 0.55%   |
| HP OMEN by Gaming Laptop 16-wf0xxx   | 2         | 0.55%   |
| HP EliteBook 2540p                   | 2         | 0.55%   |
| HASEE CV15S                          | 2         | 0.55%   |
| Fujitsu UH-X                         | 2         | 0.55%   |
| Fujitsu LIFEBOOK AH544               | 2         | 0.55%   |
| Fujitsu FMVU34013                    | 2         | 0.55%   |
| Fujitsu FMVNU6G1C                    | 2         | 0.55%   |
| Dell XPS 13 9310                     | 2         | 0.55%   |
| Dell Inspiron 5580                   | 2         | 0.55%   |
| ASUS TUF Gaming FA506IU_FA506IU      | 2         | 0.55%   |
| Apple MacBookAir6,2                  | 2         | 0.55%   |
| Apple MacBookAir5,2                  | 2         | 0.55%   |
| Apple MacBook10,1                    | 2         | 0.55%   |
| Acer Swift SF314-512                 | 2         | 0.55%   |
| Acer Aspire E5-573                   | 2         | 0.55%   |
| Acer Aspire A315-34                  | 2         | 0.55%   |
| XIAOMI Redmi Book Pro 14 2024        | 1         | 0.28%   |
| Toshiba PORTEGE R830                 | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 54        | 14.92%  |
| Lenovo ThinkBook        | 18        | 4.97%   |
| Lenovo Legion           | 16        | 4.42%   |
| Unknown                 | 12        | 3.31%   |
| Lenovo IdeaPad          | 11        | 3.04%   |
| Dell XPS                | 11        | 3.04%   |
| Fujitsu LIFEBOOK        | 10        | 2.76%   |
| Dell Latitude           | 10        | 2.76%   |
| Dell Inspiron           | 9         | 2.49%   |
| ASUS ROG                | 9         | 2.49%   |
| ASUS VivoBook           | 8         | 2.21%   |
| Acer Swift              | 7         | 1.93%   |
| Acer Aspire             | 6         | 1.66%   |
| ASUS ASUS               | 5         | 1.38%   |
| Lenovo LOQ              | 4         | 1.1%    |
| HP Pavilion             | 4         | 1.1%    |
| HP EliteBook            | 4         | 1.1%    |
| Dell Precision          | 4         | 1.1%    |
| ASUS TUF                | 4         | 1.1%    |
| Acer Nitro              | 4         | 1.1%    |
| MECHREVO WUJIE14XA      | 3         | 0.83%   |
| MECHREVO WUJIE14        | 3         | 0.83%   |
| Lenovo ZHAOYANG         | 3         | 0.83%   |
| Lenovo XiaoXinPro       | 3         | 0.83%   |
| HP ZHAN                 | 3         | 0.83%   |
| HP OMEN                 | 3         | 0.83%   |
| GPD G1619-04            | 3         | 0.83%   |
| Chuwi HeroBook          | 3         | 0.83%   |
| Apple MacBookAir5       | 3         | 0.83%   |
| Valve Jupiter           | 2         | 0.55%   |
| Lenovo Yoga             | 2         | 0.55%   |
| Lenovo XiaoXinPro-13IML | 2         | 0.55%   |
| Lenovo XiaoXinAir-14ARE | 2         | 0.55%   |
| Lenovo G770             | 2         | 0.55%   |
| IBM 260921H             | 2         | 0.55%   |
| HUAWEI KPRC-WX0         | 2         | 0.55%   |
| HASEE CV15S             | 2         | 0.55%   |
| Fujitsu UH-X            | 2         | 0.55%   |
| Fujitsu FMVU34013       | 2         | 0.55%   |
| Fujitsu FMVNU6G1C       | 2         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 46        | 12.71%  |
| 2023    | 41        | 11.33%  |
| 2018    | 38        | 10.5%   |
| 2021    | 36        | 9.94%   |
| 2022    | 32        | 8.84%   |
| 2019    | 30        | 8.29%   |
| 2017    | 18        | 4.97%   |
| 2024    | 17        | 4.7%    |
| 2011    | 15        | 4.14%   |
| 2015    | 13        | 3.59%   |
| 2012    | 13        | 3.59%   |
| 2014    | 10        | 2.76%   |
| 2013    | 10        | 2.76%   |
| 2016    | 7         | 1.93%   |
| 2010    | 7         | 1.93%   |
| 2008    | 7         | 1.93%   |
| 2025    | 6         | 1.66%   |
| 2007    | 6         | 1.66%   |
| 2009    | 2         | 0.55%   |
| 1999    | 2         | 0.55%   |
| Unknown | 2         | 0.55%   |
| 2006    | 1         | 0.28%   |
| 2005    | 1         | 0.28%   |
| 2003    | 1         | 0.28%   |
| 2001    | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 362       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 316       | 86.81%  |
| Enabled  | 48        | 13.19%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 357       | 98.62%  |
| Yes  | 5         | 1.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 78        | 21.43%  |
| 4.01-8.0    | 71        | 19.51%  |
| 8.01-16.0   | 70        | 19.23%  |
| 32.01-64.0  | 63        | 17.31%  |
| 3.01-4.0    | 30        | 8.24%   |
| 24.01-32.0  | 18        | 4.95%   |
| 64.01-256.0 | 15        | 4.12%   |
| 1.01-2.0    | 6         | 1.65%   |
| 0.51-1.0    | 6         | 1.65%   |
| 2.01-3.0    | 5         | 1.37%   |
| 0.01-0.5    | 2         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 99        | 25%     |
| 2.01-3.0   | 84        | 21.21%  |
| 1.01-2.0   | 73        | 18.43%  |
| 3.01-4.0   | 68        | 17.17%  |
| 8.01-16.0  | 34        | 8.59%   |
| 0.01-0.5   | 17        | 4.29%   |
| 16.01-24.0 | 9         | 2.27%   |
| 0.51-1.0   | 9         | 2.27%   |
| 24.01-32.0 | 2         | 0.51%   |
| 32.01-64.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 226       | 60.59%  |
| 2      | 119       | 31.9%   |
| 3      | 21        | 5.63%   |
| 0      | 6         | 1.61%   |
| 5      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 322       | 88.22%  |
| Yes       | 43        | 11.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 250       | 68.68%  |
| No        | 114       | 31.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 348       | 96.13%  |
| No        | 14        | 3.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 309       | 84.43%  |
| No        | 57        | 15.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Hong Kong | 362       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Central           | 201       | 52.76%  |
| Hong Kong         | 24        | 6.3%    |
| Kowloon           | 22        | 5.77%   |
| Wanchai           | 19        | 4.99%   |
| Shatin            | 11        | 2.89%   |
| Mong Kok          | 10        | 2.62%   |
| Tsuen Wan         | 9         | 2.36%   |
| Tseung Kwan O     | 6         | 1.57%   |
| Tai Po            | 6         | 1.57%   |
| Tung Chung        | 5         | 1.31%   |
| Tuen Mun          | 5         | 1.31%   |
| Hung Hom          | 5         | 1.31%   |
| Sai Kung          | 4         | 1.05%   |
| Wan Chai          | 3         | 0.79%   |
| Tsimshatsui       | 3         | 0.79%   |
| Man Kok           | 3         | 0.79%   |
| Yuen Long San Hui | 2         | 0.52%   |
| Shau Kei Wan      | 2         | 0.52%   |
| Sham Shui Po      | 2         | 0.52%   |
| Quarry Bay        | 2         | 0.52%   |
| Ngau Wu Tok       | 2         | 0.52%   |
| Kwai Chung        | 2         | 0.52%   |
| Ho Man Tin        | 2         | 0.52%   |
| Fanling           | 2         | 0.52%   |
| Eastern           | 2         | 0.52%   |
| Discovery Bay     | 2         | 0.52%   |
| Yuen Long         | 1         | 0.26%   |
| Yau Tsim Mong     | 1         | 0.26%   |
| Wong Tai Sin      | 1         | 0.26%   |
| Tuen Mun San Hui  | 1         | 0.26%   |
| Tsing Yi Town     | 1         | 0.26%   |
| Tsing Yi          | 1         | 0.26%   |
| To Kwa Wan        | 1         | 0.26%   |
| Tin Shui Wai      | 1         | 0.26%   |
| The Peak          | 1         | 0.26%   |
| Tai Wan To        | 1         | 0.26%   |
| Tai Wan           | 1         | 0.26%   |
| So Kon Po         | 1         | 0.26%   |
| Sheung Shui       | 1         | 0.26%   |
| Sha Tin Wai       | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 101       | 128    | 20.45%  |
| WDC                         | 39        | 51     | 7.89%   |
| Sandisk                     | 37        | 41     | 7.49%   |
| Unknown                     | 29        | 35     | 5.87%   |
| SK hynix                    | 22        | 27     | 4.45%   |
| Micron Technology           | 22        | 25     | 4.45%   |
| Seagate                     | 21        | 26     | 4.25%   |
| Intel                       | 19        | 24     | 3.85%   |
| Apple                       | 14        | 34     | 2.83%   |
| Toshiba                     | 12        | 12     | 2.43%   |
| Kingston                    | 12        | 13     | 2.43%   |
| KIOXIA                      | 11        | 12     | 2.23%   |
| Yangtze Memory Technologies | 10        | 12     | 2.02%   |
| Hitachi                     | 10        | 10     | 2.02%   |
| MAXIO Technology (Hangzhou) | 9         | 9      | 1.82%   |
| Crucial                     | 9         | 17     | 1.82%   |
| HGST                        | 7         | 8      | 1.42%   |
| YMTC                        | 5         | 5      | 1.01%   |
| Transcend                   | 4         | 4      | 0.81%   |
| JMicron Technology          | 4         | 5      | 0.81%   |
| Fujitsu                     | 4         | 6      | 0.81%   |
| China                       | 4         | 6      | 0.81%   |
| BIWIN                       | 4         | 4      | 0.81%   |
| Union Memory (Shenzhen)     | 3         | 4      | 0.61%   |
| Phison                      | 3         | 3      | 0.61%   |
| LITEON                      | 3         | 3      | 0.61%   |
| Kingston Technology Company | 3         | 3      | 0.61%   |
| Unknown                     | 3         | 4      | 0.61%   |
| ZHITAI                      | 2         | 2      | 0.4%    |
| Yangtze Memory              | 2         | 2      | 0.4%    |
| UMIS                        | 2         | 2      | 0.4%    |
| TO Exter                    | 2         | 2      | 0.4%    |
| Team                        | 2         | 2      | 0.4%    |
| Plextor                     | 2         | 3      | 0.4%    |
| Netac                       | 2         | 2      | 0.4%    |
| Micron/Crucial Technology   | 2         | 2      | 0.4%    |
| Lexar                       | 2         | 2      | 0.4%    |
| Lenovo                      | 2         | 2      | 0.4%    |
| KingSpec                    | 2         | 3      | 0.4%    |
| HS-SSD-C100                 | 2         | 3      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB       | 13        | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB        | 11        | 2.14%   |
| Unknown MMC Card  64GB                                   | 8         | 1.56%   |
| Samsung SSD 980 1TB                                      | 6         | 1.17%   |
| Unknown MMC Card  128GB                                  | 5         | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB                           | 5         | 0.97%   |
| SanDisk NVMe SSD Drive 2TB                               | 5         | 0.97%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB                   | 4         | 0.78%   |
| WDC WDS100T2B0C-00PXH0 1TB                               | 3         | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB                           | 3         | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB         | 3         | 0.58%   |
| SanDisk NVMe SSD Drive 512GB                             | 3         | 0.58%   |
| SanDisk NVMe SSD Drive 1TB                               | 3         | 0.58%   |
| SanDisk DF4064  64GB                                     | 3         | 0.58%   |
| Samsung SSD 990 PRO 1TB                                  | 3         | 0.58%   |
| Samsung NVMe SSD Drive 512GB                             | 3         | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB     | 3         | 0.58%   |
| Samsung MZVL2512HCJQ-00BL2 512GB                         | 3         | 0.58%   |
| Samsung MZAL41T0HBLB-00BL2 1TB                           | 3         | 0.58%   |
| Micron 3400_MTFDKBA512TFH 512GB                          | 3         | 0.58%   |
| Crucial CT1000MX500SSD1 1TB                              | 3         | 0.58%   |
| BIWIN SSD 512GB                                          | 3         | 0.58%   |
| Unknown                                                  | 3         | 0.58%   |
| YMTC YMSS2ED08D25MC 1TB                                  | 2         | 0.39%   |
| Yangtze Memory ZHITAI PC005 Active 1TB                   | 2         | 0.39%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                     | 2         | 0.39%   |
| Yangtze Memory YMTC PC300-1TB-B                          | 2         | 0.39%   |
| Yangtze Memory PC300 M.2 2280 NVMe SSD (DRAM-less) 512GB | 2         | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                         | 2         | 0.39%   |
| WDC WD10SPZX-24Z10T0 1TB                                 | 2         | 0.39%   |
| WDC WD10SPZX-22Z10T1 1TB                                 | 2         | 0.39%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                     | 2         | 0.39%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB                     | 2         | 0.39%   |
| Unknown NVMe SSD Drive 1TB                               | 2         | 0.39%   |
| Unknown NVMe SSD Drive 1024GB                            | 2         | 0.39%   |
| Toshiba MQ04ABF100 1TB                                   | 2         | 0.39%   |
| Toshiba MQ01ABF050 500GB                                 | 2         | 0.39%   |
| TO Exter nal USB 3.0 250GB                               | 2         | 0.39%   |
| SK hynix BC501 NVMe 128GB                                | 2         | 0.39%   |
| Seagate ST500LT012-9WS142 500GB                          | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 29.17%  |
| WDC                 | 18        | 26     | 25%     |
| Hitachi             | 10        | 10     | 13.89%  |
| HGST                | 7         | 8      | 9.72%   |
| Toshiba             | 5         | 5      | 6.94%   |
| JMicron Technology  | 3         | 4      | 4.17%   |
| TO Exter            | 2         | 2      | 2.78%   |
| External            | 2         | 2      | 2.78%   |
| USB3.0              | 1         | 1      | 1.39%   |
| Samsung Electronics | 1         | 1      | 1.39%   |
| IBM/Hitachi         | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 27     | 18.81%  |
| Crucial             | 8         | 16     | 7.92%   |
| Apple               | 8         | 13     | 7.92%   |
| Kingston            | 7         | 7      | 6.93%   |
| Intel               | 7         | 10     | 6.93%   |
| WDC                 | 6         | 6      | 5.94%   |
| Transcend           | 4         | 4      | 3.96%   |
| SanDisk             | 4         | 4      | 3.96%   |
| China               | 4         | 6      | 3.96%   |
| Micron Technology   | 3         | 4      | 2.97%   |
| LITEON              | 3         | 3      | 2.97%   |
| Team                | 2         | 2      | 1.98%   |
| SK hynix            | 2         | 2      | 1.98%   |
| Plextor             | 2         | 3      | 1.98%   |
| Fujitsu             | 2         | 4      | 1.98%   |
| BIWIN               | 2         | 2      | 1.98%   |
| Verbatim            | 1         | 2      | 0.99%   |
| Vaseky              | 1         | 1      | 0.99%   |
| Unknown (CF)        | 1         | 1      | 0.99%   |
| UNITEK              | 1         | 1      | 0.99%   |
| ShiJi               | 1         | 19     | 0.99%   |
| RECADATA            | 1         | 1      | 0.99%   |
| Ramsta              | 1         | 1      | 0.99%   |
| PNY                 | 1         | 1      | 0.99%   |
| Netac               | 1         | 1      | 0.99%   |
| Lexar               | 1         | 1      | 0.99%   |
| Lenovo              | 1         | 1      | 0.99%   |
| KLEVV               | 1         | 1      | 0.99%   |
| HS-SSD-C100         | 1         | 1      | 0.99%   |
| Hikvision           | 1         | 1      | 0.99%   |
| Galaxy              | 1         | 1      | 0.99%   |
| DGM                 | 1         | 1      | 0.99%   |
| Apacer              | 1         | 4      | 0.99%   |
| A-DATA Technology   | 1         | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 232       | 332    | 52.73%  |
| SSD     | 92        | 153    | 20.91%  |
| HDD     | 70        | 87     | 15.91%  |
| MMC     | 28        | 36     | 6.36%   |
| Unknown | 18        | 21     | 4.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 232       | 328    | 53.95%  |
| SATA | 141       | 231    | 32.79%  |
| SAS  | 29        | 34     | 6.74%   |
| MMC  | 28        | 36     | 6.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 98        | 138    | 61.25%  |
| 0.51-1.0   | 51        | 88     | 31.88%  |
| 1.01-2.0   | 8         | 11     | 5%      |
| 3.01-4.0   | 2         | 2      | 1.25%   |
| 20.01-50.0 | 1         | 1      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 87        | 22.42%  |
| 251-500        | 71        | 18.3%   |
| 501-1000       | 68        | 17.53%  |
| 1001-2000      | 48        | 12.37%  |
| 1-20           | 34        | 8.76%   |
| 51-100         | 25        | 6.44%   |
| More than 3000 | 22        | 5.67%   |
| 21-50          | 16        | 4.12%   |
| 2001-3000      | 10        | 2.58%   |
| Unknown        | 7         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 138       | 34.94%  |
| 21-50          | 59        | 14.94%  |
| 101-250        | 55        | 13.92%  |
| 51-100         | 44        | 11.14%  |
| 251-500        | 43        | 10.89%  |
| 501-1000       | 27        | 6.84%   |
| 1001-2000      | 16        | 4.05%   |
| Unknown        | 7         | 1.77%   |
| More than 3000 | 3         | 0.76%   |
| 2001-3000      | 3         | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| LITEON CV8-8E128-HP 128GB SSD                       | 2         | 2      | 11.11%  |
| WDC WD20SPZX-75UA7T0 2TB                            | 1         | 2      | 5.56%   |
| Seagate ST9500325AS 500GB                           | 1         | 2      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 5.56%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1      | 5.56%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 5.56%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                 | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 860 EVO 1TB                 | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS725050A7E630 500GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS723216L9A360 160GB                       | 1         | 1      | 5.56%   |
| Hitachi HTC426040G8CE00 40GB                        | 1         | 1      | 5.56%   |
| HGST TOURO Mobile 1TB                               | 1         | 1      | 5.56%   |
| DGM SSD 120GB S3-120A                               | 1         | 1      | 5.56%   |
| Crucial CT240M500SSD1 240GB                         | 1         | 1      | 5.56%   |
| BIWIN SSD 32GB                                      | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 16.67%  |
| Hitachi             | 3         | 3      | 16.67%  |
| SanDisk             | 2         | 2      | 11.11%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| LITEON              | 2         | 2      | 11.11%  |
| WDC                 | 1         | 2      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| DGM                 | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| BIWIN               | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 37.5%   |
| Hitachi | 3         | 3      | 37.5%   |
| WDC     | 1         | 2      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 10        | 10     | 55.56%  |
| HDD  | 8         | 10     | 44.44%  |

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
| Works    | 211       | 342    | 53.96%  |
| Detected | 162       | 267    | 41.43%  |
| Malfunc  | 18        | 20     | 4.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 189       | 40.13%  |
| Samsung Electronics                     | 88        | 18.68%  |
| SanDisk                                 | 45        | 9.55%   |
| SK hynix                                | 20        | 4.25%   |
| Micron Technology                       | 20        | 4.25%   |
| Yangtze Memory Technologies             | 18        | 3.82%   |
| AMD                                     | 18        | 3.82%   |
| MAXIO Technology (Hangzhou)             | 12        | 2.55%   |
| Toshiba America Info Systems            | 9         | 1.91%   |
| KIOXIA                                  | 9         | 1.91%   |
| Kingston Technology Company             | 8         | 1.7%    |
| Shenzhen Unionmemory Information System | 5         | 1.06%   |
| Silicon Motion                          | 4         | 0.85%   |
| Phison Electronics                      | 4         | 0.85%   |
| INNOGRIT                                | 4         | 0.85%   |
| Apple                                   | 4         | 0.85%   |
| Biwin Storage Technology                | 3         | 0.64%   |
| Realtek Semiconductor                   | 2         | 0.42%   |
| Micron/Crucial Technology               | 2         | 0.42%   |
| VIA Technologies                        | 1         | 0.21%   |
| Union Memory (Shenzhen)                 | 1         | 0.21%   |
| Solidigm                                | 1         | 0.21%   |
| Solid State Storage Technology          | 1         | 0.21%   |
| Nvidia                                  | 1         | 0.21%   |
| Marvell Technology Group                | 1         | 0.21%   |
| Lenovo                                  | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 28        | 5.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 24        | 4.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 3.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 3.62%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 3.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 2.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13        | 2.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 2.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 1.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 9         | 1.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 1.81%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 8         | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 1.61%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 7         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 7         | 1.41%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 6         | 1.21%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 6         | 1.21%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 6         | 1.21%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 6         | 1.21%   |
| Intel SSD 660P Series                                                          | 6         | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 1.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.21%   |
| Yangtze Memory PC300 M.2 2280 NVMe SSD (DRAM-less)                             | 5         | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.01%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 5         | 1.01%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 5         | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 1.01%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 4         | 0.8%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.8%    |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 4         | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 0.8%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 4         | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.8%    |
| Yangtze Memory ZHITAI TiPro5000 NVMe SSD                                       | 3         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 232       | 52.13%  |
| SATA | 157       | 35.28%  |
| RAID | 35        | 7.87%   |
| IDE  | 21        | 4.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 277       | 76.52%  |
| AMD          | 82        | 22.65%  |
| Unknown      | 2         | 0.55%   |
| GenuineTMx86 | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 2.21%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 8         | 2.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 1.93%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 1.66%   |
| Intel 12th Gen Core i7-12700H                 | 6         | 1.66%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 1.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.38%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 5         | 1.38%   |
| Intel Core Ultra 7 155H                       | 4         | 1.1%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.1%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.1%    |
| Intel Core i5-10310U CPU @ 1.70GHz            | 4         | 1.1%    |
| Intel 13th Gen Core i9-13900HX                | 4         | 1.1%    |
| Intel 13th Gen Core i5-13420H                 | 4         | 1.1%    |
| AMD Ryzen 9 7945HX with Radeon Graphics       | 4         | 1.1%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 1.1%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 4         | 1.1%    |
| AMD Ryzen 7 6800U with Radeon Graphics        | 4         | 1.1%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.1%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.1%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.83%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.83%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.83%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.83%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.83%   |
| Intel 13th Gen Core i9-13900H                 | 3         | 0.83%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 0.83%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.83%   |
| Intel Genuine processor 800MHz                | 2         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 74        | 20.44%  |
| Intel Core i7           | 68        | 18.78%  |
| Other                   | 64        | 17.68%  |
| AMD Ryzen 7             | 41        | 11.33%  |
| Intel Celeron           | 22        | 6.08%   |
| Intel Core i3           | 16        | 4.42%   |
| AMD Ryzen 5             | 14        | 3.87%   |
| Intel Core              | 13        | 3.59%   |
| AMD Ryzen 9             | 12        | 3.31%   |
| AMD Ryzen 7 PRO         | 9         | 2.49%   |
| Intel Atom              | 5         | 1.38%   |
| Intel Core m3           | 4         | 1.1%    |
| Intel Core 2 Duo        | 4         | 1.1%    |
| Intel Xeon              | 2         | 0.55%   |
| Intel Pentium Dual-Core | 2         | 0.55%   |
| Intel Genuine           | 2         | 0.55%   |
| Intel Core 2            | 2         | 0.55%   |
| Intel Pentium Silver    | 1         | 0.28%   |
| Intel Pentium M         | 1         | 0.28%   |
| Intel Pentium III       | 1         | 0.28%   |
| Intel Pentium Gold      | 1         | 0.28%   |
| Intel Pentium Dual      | 1         | 0.28%   |
| Intel Core M            | 1         | 0.28%   |
| Intel Core i9           | 1         | 0.28%   |
| AMD Quad-Core           | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 110       | 30.39%  |
| 2      | 98        | 27.07%  |
| 8      | 66        | 18.23%  |
| 6      | 28        | 7.73%   |
| 14     | 16        | 4.42%   |
| 16     | 11        | 3.04%   |
| 12     | 11        | 3.04%   |
| 1      | 11        | 3.04%   |
| 10     | 6         | 1.66%   |
| 24     | 5         | 1.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 362       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 305       | 84.02%  |
| 1      | 58        | 15.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 344       | 95.03%  |
| 32-bit         | 11        | 3.04%   |
| Unknown        | 5         | 1.38%   |
| 64-bit         | 2         | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 191       | 51.34%  |
| 0x806e9    | 11        | 2.96%   |
| 0x806ea    | 10        | 2.69%   |
| 0x206a7    | 10        | 2.69%   |
| 0x906ea    | 9         | 2.42%   |
| 0x806c1    | 8         | 2.15%   |
| 0x806ec    | 7         | 1.88%   |
| 0x306a9    | 7         | 1.88%   |
| 0x08600106 | 7         | 1.88%   |
| 0x706e5    | 6         | 1.61%   |
| 0x506c9    | 6         | 1.61%   |
| 0x406e3    | 6         | 1.61%   |
| 0x0a50000c | 6         | 1.61%   |
| 0x0a404102 | 6         | 1.61%   |
| 0xa0652    | 5         | 1.34%   |
| 0x806eb    | 5         | 1.34%   |
| 0x40651    | 5         | 1.34%   |
| 0x106c2    | 4         | 1.08%   |
| 0xb0671    | 3         | 0.81%   |
| 0x906a3    | 3         | 0.81%   |
| 0x806d1    | 3         | 0.81%   |
| 0x706a8    | 3         | 0.81%   |
| 0x306c3    | 3         | 0.81%   |
| 0x20655    | 3         | 0.81%   |
| 0x1067a    | 3         | 0.81%   |
| 0x08600104 | 3         | 0.81%   |
| 0x08108102 | 3         | 0.81%   |
| 0x906e9    | 2         | 0.54%   |
| 0x6fd      | 2         | 0.54%   |
| 0x6d8      | 2         | 0.54%   |
| 0x66a      | 2         | 0.54%   |
| 0x506e3    | 2         | 0.54%   |
| 0x306d4    | 2         | 0.54%   |
| 0x0a601203 | 2         | 0.54%   |
| 0x0a50000b | 2         | 0.54%   |
| 0x08600103 | 2         | 0.54%   |
| 0x906c0    | 1         | 0.27%   |
| 0x706a1    | 1         | 0.27%   |
| 0x6fb      | 1         | 0.27%   |
| 0x6f6      | 1         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KabyLake           | 75        | 20.66%  |
| Unknown            | 61        | 16.8%   |
| Alderlake Hybrid   | 23        | 6.34%   |
| TigerLake          | 19        | 5.23%   |
| Zen 2              | 17        | 4.68%   |
| Zen 3              | 16        | 4.41%   |
| SandyBridge        | 16        | 4.41%   |
| Skylake            | 15        | 4.13%   |
| IvyBridge          | 15        | 4.13%   |
| Haswell            | 15        | 4.13%   |
| IceLake            | 13        | 3.58%   |
| Broadwell          | 11        | 3.03%   |
| Goldmont plus      | 9         | 2.48%   |
| CometLake          | 8         | 2.2%    |
| Meteorlake Hybrid  | 7         | 1.93%   |
| Goldmont           | 7         | 1.93%   |
| Zen+               | 6         | 1.65%   |
| Westmere           | 5         | 1.38%   |
| Core               | 5         | 1.38%   |
| Penryn             | 4         | 1.1%    |
| P6                 | 4         | 1.1%    |
| Bonnell            | 4         | 1.1%    |
| Silvermont         | 2         | 0.55%   |
| ArrowLake-H Hybrid | 2         | 0.55%   |
| Tremont            | 1         | 0.28%   |
| Lunarlake Hybrid   | 1         | 0.28%   |
| Jaguar             | 1         | 0.28%   |
| Gracemont          | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 262       | 55.04%  |
| Nvidia      | 119       | 25%     |
| AMD         | 92        | 19.33%  |
| Neomagic    | 2         | 0.42%   |
| S3 Graphics | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 17        | 3.5%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                      | 17        | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 16        | 3.29%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 15        | 3.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 14        | 2.88%   |
| AMD Rembrandt [Radeon 680M]                                                   | 14        | 2.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 13        | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 13        | 2.67%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 13        | 2.67%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 13        | 2.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 13        | 2.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 12        | 2.47%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 12        | 2.47%   |
| AMD HawkPoint1                                                                | 11        | 2.26%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                         | 9         | 1.85%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                      | 9         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 8         | 1.65%   |
| Nvidia GP108M [GeForce MX150]                                                 | 7         | 1.44%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                      | 7         | 1.44%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                       | 7         | 1.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 1.44%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                       | 7         | 1.44%   |
| AMD Phoenix1                                                                  | 7         | 1.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 6         | 1.23%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                               | 6         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 6         | 1.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 1.03%   |
| Intel Raptor Lake-P [UHD Graphics]                                            | 5         | 1.03%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 5         | 1.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 5         | 1.03%   |
| Intel Kaby Lake-Y GT2 [HD Graphics 615]                                       | 5         | 1.03%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 5         | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 0.82%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                               | 4         | 0.82%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                         | 4         | 0.82%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 0.82%   |
| AMD Raphael                                                                   | 4         | 0.82%   |
| Nvidia TU117M [GeForce MX450]                                                 | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 168       | 46.15%  |
| Intel + Nvidia  | 83        | 22.8%   |
| 1 x AMD         | 57        | 15.66%  |
| AMD + Nvidia    | 23        | 6.32%   |
| 1 x Nvidia      | 15        | 4.12%   |
| Intel + AMD     | 10        | 2.75%   |
| Other           | 2         | 0.55%   |
| 2 x AMD         | 2         | 0.55%   |
| 1 x Neomagic    | 2         | 0.55%   |
| 2 x Intel       | 1         | 0.27%   |
| 1 x S3 Graphics | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 284       | 77.38%  |
| Proprietary | 60        | 16.35%  |
| Unknown     | 23        | 6.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 247       | 67.67%  |
| 0.01-0.5   | 37        | 10.14%  |
| 1.01-2.0   | 28        | 7.67%   |
| 3.01-4.0   | 16        | 4.38%   |
| 7.01-8.0   | 12        | 3.29%   |
| 0.51-1.0   | 12        | 3.29%   |
| 5.01-6.0   | 10        | 2.74%   |
| 2.01-3.0   | 2         | 0.55%   |
| 8.01-16.0  | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 77        | 19.25%  |
| AU Optronics            | 57        | 14.25%  |
| LG Display              | 44        | 11%     |
| Chimei Innolux          | 39        | 9.75%   |
| Samsung Electronics     | 28        | 7%      |
| Sharp                   | 18        | 4.5%    |
| Dell                    | 16        | 4%      |
| Apple                   | 13        | 3.25%   |
| Lenovo                  | 12        | 3%      |
| AOC                     | 10        | 2.5%    |
| TMA                     | 7         | 1.75%   |
| CSO                     | 7         | 1.75%   |
| Mi                      | 6         | 1.5%    |
| JDI                     | 5         | 1.25%   |
| CSOT                    | 5         | 1.25%   |
| Philips                 | 4         | 1%      |
| Goldstar                | 4         | 1%      |
| ViewSonic               | 3         | 0.75%   |
| TMX                     | 3         | 0.75%   |
| PANDA                   | 3         | 0.75%   |
| InfoVision              | 3         | 0.75%   |
| CSW                     | 3         | 0.75%   |
| Valve                   | 2         | 0.5%    |
| LG Philips              | 2         | 0.5%    |
| IPS                     | 2         | 0.5%    |
| HKC                     | 2         | 0.5%    |
| CPT                     | 2         | 0.5%    |
| Chi Mei Optoelectronics | 2         | 0.5%    |
| Unknown (DAE)           | 1         | 0.25%   |
| TUO                     | 1         | 0.25%   |
| SOY                     | 1         | 0.25%   |
| Sony                    | 1         | 0.25%   |
| SAC                     | 1         | 0.25%   |
| RKS                     | 1         | 0.25%   |
| RGT                     | 1         | 0.25%   |
| MStar                   | 1         | 0.25%   |
| Lenovo Group Limited    | 1         | 0.25%   |
| JXC                     | 1         | 0.25%   |
| ITE                     | 1         | 0.25%   |
| Intehill                | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| TMA TL140ADXP24-0 TMA2004 2880x1800 300x190mm 14.0-inch               | 7         | 1.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 1.23%   |
| BOE LCD Monitor BOE0AE3 1920x1080 344x194mm 15.5-inch                 | 4         | 0.99%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 4         | 0.99%   |
| Samsung Electronics LCD Monitor SDC419F 2880x1800 302x189mm 14.0-inch | 3         | 0.74%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 3         | 0.74%   |
| Lenovo LCD Monitor LEN8AB1 3072x1920 312x195mm 14.5-inch              | 3         | 0.74%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 3         | 0.74%   |
| Dell P2422H DELA1C5 1920x1080 527x296mm 23.8-inch                     | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.74%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 3         | 0.74%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 0.74%   |
| AU Optronics LCD Monitor AUOC391 2880x1800 301x188mm 14.0-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUOA195 2240x1400 300x188mm 13.9-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 0.74%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 0.74%   |
| ViewSonic VA2456 Series VSC3236 1920x1080 527x296mm 23.8-inch         | 2         | 0.49%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.49%   |
| Sharp LQ133M1JW48B SHP1531 1920x1080 294x165mm 13.3-inch              | 2         | 0.49%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 2         | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.49%   |
| Mi Monitor XMI27A1 3840x2160 597x336mm 27.0-inch                      | 2         | 0.49%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.49%   |
| LG Display LCD Monitor LGD058B 2560x1440 309x174mm 14.0-inch          | 2         | 0.49%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.49%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.49%   |
| IPS R240 IPS2380 1920x1080 526x296mm 23.8-inch                        | 2         | 0.49%   |
| CSOT LCD Monitor CSO076D 2560x1600 286x179mm 13.3-inch                | 2         | 0.49%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 381x214mm 17.2-inch                 | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN140E 1920x1080 309x173mm 13.9-inch      | 2         | 0.49%   |
| BOE LCD Monitor BOE0B7D 2560x1440 355x200mm 16.0-inch                 | 2         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 160       | 41.88%  |
| 1366x768 (WXGA)   | 42        | 10.99%  |
| 3840x2160 (4K)    | 26        | 6.81%   |
| 2560x1600         | 24        | 6.28%   |
| 2880x1800         | 23        | 6.02%   |
| 2560x1440 (QHD)   | 23        | 6.02%   |
| 1920x1200 (WUXGA) | 8         | 2.09%   |
| 1600x900 (HD+)    | 8         | 2.09%   |
| 1440x900 (WXGA+)  | 7         | 1.83%   |
| 3200x2000         | 6         | 1.57%   |
| 2240x1400         | 6         | 1.57%   |
| 1280x800 (WXGA)   | 6         | 1.57%   |
| 3072x1920         | 5         | 1.31%   |
| 3840x2400         | 4         | 1.05%   |
| 3000x2000         | 3         | 0.79%   |
| Unknown           | 3         | 0.79%   |
| 800x1280          | 2         | 0.52%   |
| 3456x2160         | 2         | 0.52%   |
| 3440x1440         | 2         | 0.52%   |
| 3200x1800 (QHD+)  | 2         | 0.52%   |
| 2880x1920         | 2         | 0.52%   |
| 2880x1620         | 2         | 0.52%   |
| 2400x1600         | 2         | 0.52%   |
| 2304x1440         | 2         | 0.52%   |
| 2160x1440         | 2         | 0.52%   |
| 3840x1600         | 1         | 0.26%   |
| 3840x1100         | 1         | 0.26%   |
| 3840x1080         | 1         | 0.26%   |
| 3520x1080         | 1         | 0.26%   |
| 2736x1824         | 1         | 0.26%   |
| 2560x1080         | 1         | 0.26%   |
| 2256x1504         | 1         | 0.26%   |
| 1600x2560         | 1         | 0.26%   |
| 1024x600          | 1         | 0.26%   |
| 1024x576          | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 101       | 25.19%  |
| 14      | 76        | 18.95%  |
| 13      | 75        | 18.7%   |
| 16      | 25        | 6.23%   |
| 12      | 22        | 5.49%   |
| 27      | 20        | 4.99%   |
| 24      | 15        | 3.74%   |
| 17      | 13        | 3.24%   |
| 21      | 10        | 2.49%   |
| 23      | 6         | 1.5%    |
| Unknown | 6         | 1.5%    |
| 40      | 4         | 1%      |
| 31      | 4         | 1%      |
| 34      | 3         | 0.75%   |
| 11      | 3         | 0.75%   |
| 10      | 3         | 0.75%   |
| 20      | 2         | 0.5%    |
| 8       | 2         | 0.5%    |
| 7       | 2         | 0.5%    |
| 72      | 1         | 0.25%   |
| 52      | 1         | 0.25%   |
| 48      | 1         | 0.25%   |
| 43      | 1         | 0.25%   |
| 37      | 1         | 0.25%   |
| 32      | 1         | 0.25%   |
| 26      | 1         | 0.25%   |
| 19      | 1         | 0.25%   |
| 18      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 215       | 53.88%  |
| 201-300     | 84        | 21.05%  |
| 501-600     | 41        | 10.28%  |
| 351-400     | 18        | 4.51%   |
| 401-500     | 13        | 3.26%   |
| Unknown     | 6         | 1.5%    |
| 801-900     | 5         | 1.25%   |
| 601-700     | 5         | 1.25%   |
| 701-800     | 4         | 1%      |
| 101-200     | 2         | 0.5%    |
| 1001-1500   | 2         | 0.5%    |
| 1-100       | 2         | 0.5%    |
| 1501-2000   | 1         | 0.25%   |
| 901-1000    | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 252       | 69.04%  |
| 16/10   | 88        | 24.11%  |
| 3/2     | 12        | 3.29%   |
| 21/9    | 4         | 1.1%    |
| Unknown | 3         | 0.82%   |
| 0.67    | 2         | 0.55%   |
| 0.62    | 2         | 0.55%   |
| 32/9    | 1         | 0.27%   |
| 3.40    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 114       | 28.36%  |
| 101-110        | 102       | 25.37%  |
| 71-80          | 33        | 8.21%   |
| 201-250        | 27        | 6.72%   |
| 111-120        | 23        | 5.72%   |
| 61-70          | 21        | 5.22%   |
| 301-350        | 21        | 5.22%   |
| 121-130        | 13        | 3.23%   |
| 351-500        | 9         | 2.24%   |
| 151-200        | 6         | 1.49%   |
| 501-1000       | 6         | 1.49%   |
| 91-100         | 6         | 1.49%   |
| Unknown        | 6         | 1.49%   |
| 51-60          | 4         | 1%      |
| 1-40           | 4         | 1%      |
| 41-50          | 3         | 0.75%   |
| More than 1000 | 2         | 0.5%    |
| 251-300        | 2         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 149       | 38.21%  |
| 161-240       | 94        | 24.1%   |
| 101-120       | 51        | 13.08%  |
| More than 240 | 49        | 12.56%  |
| 51-100        | 37        | 9.49%   |
| Unknown       | 6         | 1.54%   |
| 1-50          | 4         | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 287       | 77.15%  |
| 2     | 68        | 18.28%  |
| 0     | 14        | 3.76%   |
| 3     | 3         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 226       | 41.39%  |
| Realtek Semiconductor                  | 160       | 29.3%   |
| Qualcomm Atheros                       | 42        | 7.69%   |
| MediaTek                               | 34        | 6.23%   |
| Broadcom                               | 21        | 3.85%   |
| ASIX Electronics                       | 10        | 1.83%   |
| Qualcomm                               | 9         | 1.65%   |
| Broadcom Limited                       | 7         | 1.28%   |
| Ralink Technology                      | 4         | 0.73%   |
| Marvell Technology Group               | 4         | 0.73%   |
| DisplayLink                            | 4         | 0.73%   |
| Suzhou Motorcomm Electronic Technology | 3         | 0.55%   |
| TP-Link                                | 2         | 0.37%   |
| SEGGER                                 | 2         | 0.37%   |
| Quectel Wireless Solutions             | 2         | 0.37%   |
| Lenovo                                 | 2         | 0.37%   |
| Apple                                  | 2         | 0.37%   |
| Xiaomi                                 | 1         | 0.18%   |
| Texas Instruments                      | 1         | 0.18%   |
| Shenzhen Goodix Technology             | 1         | 0.18%   |
| Ralink                                 | 1         | 0.18%   |
| Qualcomm Technologies                  | 1         | 0.18%   |
| OPPO Electronics                       | 1         | 0.18%   |
| NetGear                                | 1         | 0.18%   |
| Microsoft                              | 1         | 0.18%   |
| LSI                                    | 1         | 0.18%   |
| Linksys                                | 1         | 0.18%   |
| Huawei Technologies                    | 1         | 0.18%   |
| Fitbit                                 | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 98        | 15.17%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 22        | 3.41%   |
| Intel Wi-Fi 6 AX200                                                     | 22        | 3.41%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 16        | 2.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 2.32%   |
| Intel Wireless 7265                                                     | 14        | 2.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 14        | 2.17%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 2.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 2.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.7%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 10        | 1.55%   |
| Intel Wireless 8260                                                     | 10        | 1.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.39%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 8         | 1.24%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 8         | 1.24%   |
| Intel Ethernet Connection (4) I219-V                                    | 8         | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 7         | 1.08%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 7         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                           | 7         | 1.08%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 6         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                       | 5         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 0.77%   |
| Intel Wireless 7260                                                     | 5         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.77%   |
| Intel 700 Series Chipset CNVi WiFi                                      | 5         | 0.77%   |
| Realtek USB 10/100/1G/2.5 LAN                                           | 4         | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.62%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 212       | 58.73%  |
| Realtek Semiconductor      | 38        | 10.53%  |
| Qualcomm Atheros           | 38        | 10.53%  |
| MediaTek                   | 28        | 7.76%   |
| Broadcom                   | 18        | 4.99%   |
| Qualcomm                   | 9         | 2.49%   |
| Broadcom Limited           | 5         | 1.39%   |
| Ralink Technology          | 4         | 1.11%   |
| TP-Link                    | 2         | 0.55%   |
| Quectel Wireless Solutions | 2         | 0.55%   |
| Texas Instruments          | 1         | 0.28%   |
| Ralink                     | 1         | 0.28%   |
| NetGear                    | 1         | 0.28%   |
| Microsoft                  | 1         | 0.28%   |
| Linksys                    | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                             | 22        | 6.08%   |
| Intel Wireless 8265 / 8275                                                      | 17        | 4.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 15        | 4.14%   |
| Intel Wireless 7265                                                             | 14        | 3.87%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 14        | 3.87%   |
| Intel Wi-Fi 6 AX201                                                             | 13        | 3.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                        | 12        | 3.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 12        | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 11        | 3.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                | 11        | 3.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 10        | 2.76%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 10        | 2.76%   |
| Intel Wireless 8260                                                             | 10        | 2.76%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 8         | 2.21%   |
| Intel Meteor Lake PCH CNVi WiFi                                                 | 8         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 7         | 1.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                      | 7         | 1.93%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                      | 7         | 1.93%   |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 6         | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 6         | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 5         | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                | 5         | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                  | 5         | 1.38%   |
| Intel Wireless 7260                                                             | 5         | 1.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                 | 5         | 1.38%   |
| Intel 700 Series Chipset CNVi WiFi                                              | 5         | 1.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 4         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 4         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)         | 4         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 4         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 4         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                                   | 4         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                                 | 3         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 3         | 0.83%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 3         | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 3         | 0.83%   |
| Intel Gemini Lake PCH CNVi WiFi                                                 | 3         | 0.83%   |
| Intel Centrino Advanced-N 6200                                                  | 3         | 0.83%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter            | 3         | 0.83%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                              | 3         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 143       | 53.16%  |
| Intel                                  | 75        | 27.88%  |
| ASIX Electronics                       | 10        | 3.72%   |
| Qualcomm Atheros                       | 9         | 3.35%   |
| MediaTek                               | 6         | 2.23%   |
| Broadcom                               | 5         | 1.86%   |
| Marvell Technology Group               | 4         | 1.49%   |
| DisplayLink                            | 4         | 1.49%   |
| Suzhou Motorcomm Electronic Technology | 3         | 1.12%   |
| Lenovo                                 | 2         | 0.74%   |
| Broadcom Limited                       | 2         | 0.74%   |
| Apple                                  | 2         | 0.74%   |
| Xiaomi                                 | 1         | 0.37%   |
| Qualcomm Technologies                  | 1         | 0.37%   |
| OPPO Electronics                       | 1         | 0.37%   |
| Huawei Technologies                    | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98        | 35.38%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 7.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 3.25%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 2.89%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 2.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 1.81%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 1.81%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 4         | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.44%   |
| DisplayLink StarTech USB3DOCKHDPC                                      | 4         | 1.44%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 3         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 1.08%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 1.08%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.08%   |
| Intel Ethernet Connection (24) I219-V                                  | 3         | 1.08%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.72%   |
| Lenovo Thinkpad LAN                                                    | 2         | 0.72%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.72%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.72%   |
| Intel Ethernet Connection (18) I219-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection (13) I219-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection (10) I219-LM                                 | 2         | 0.72%   |
| Intel Arrow Lake CNVi WiFi                                             | 2         | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.72%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 2         | 0.72%   |
| ASIX AX88772B                                                          | 2         | 0.72%   |
| Apple iBridge                                                          | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.36%   |
| Realtek USB 10/100 LAN                                                 | 1         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 348       | 57.62%  |
| Ethernet | 249       | 41.23%  |
| Modem    | 5         | 0.83%   |
| Unknown  | 2         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 304       | 77.95%  |
| Ethernet | 86        | 22.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 211       | 58.29%  |
| 1     | 142       | 39.23%  |
| 0     | 9         | 2.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 346       | 95.32%  |
| Yes  | 17        | 4.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 190       | 61.29%  |
| Foxconn / Hon Hai               | 29        | 9.35%   |
| Realtek Semiconductor           | 16        | 5.16%   |
| IMC Networks                    | 16        | 5.16%   |
| Qualcomm Atheros Communications | 11        | 3.55%   |
| Apple                           | 9         | 2.9%    |
| Broadcom                        | 8         | 2.58%   |
| Lite-On Technology              | 7         | 2.26%   |
| MediaTek                        | 5         | 1.61%   |
| Realtek                         | 3         | 0.97%   |
| Hewlett-Packard                 | 3         | 0.97%   |
| Foxconn International           | 3         | 0.97%   |
| USI                             | 2         | 0.65%   |
| Taiyo Yuden                     | 2         | 0.65%   |
| Dell                            | 2         | 0.65%   |
| Fujitsu                         | 1         | 0.32%   |
| Cambridge Silicon Radio         | 1         | 0.32%   |
| Askey Computer                  | 1         | 0.32%   |
| Alps Electric                   | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 44        | 14.19%  |
| Intel AX201 Bluetooth                             | 41        | 13.23%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 32        | 10.32%  |
| Intel Bluetooth Device                            | 31        | 10%     |
| Intel AX200 Bluetooth                             | 22        | 7.1%    |
| Realtek Bluetooth Radio                           | 16        | 5.16%   |
| Intel AX210 Bluetooth                             | 14        | 4.52%   |
| Foxconn / Hon Hai Wireless_Device                 | 11        | 3.55%   |
| IMC Networks Wireless_Device                      | 10        | 3.23%   |
| Foxconn / Hon Hai Bluetooth Device                | 7         | 2.26%   |
| Qualcomm Atheros  Bluetooth Device                | 6         | 1.94%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 6         | 1.94%   |
| MediaTek Wireless_Device                          | 5         | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 4         | 1.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 1.29%   |
| Realtek Bluetooth Radio                           | 3         | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 3         | 0.97%   |
| IMC Networks Bluetooth Radio                      | 3         | 0.97%   |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 0.97%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 3         | 0.97%   |
| Apple Bluetooth USB Host Controller               | 3         | 0.97%   |
| Apple Bluetooth Host Controller                   | 3         | 0.97%   |
| USI Bluetooth Device                              | 2         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 2         | 0.65%   |
| IMC Networks Bluetooth Device                     | 2         | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 0.65%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device   | 2         | 0.65%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)           | 1         | 0.32%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)           | 1         | 0.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.32%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.32%   |
| Lite-On Bluetooth Radio                           | 1         | 0.32%   |
| Lite-On Bluetooth Device                          | 1         | 0.32%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 0.32%   |
| Intel Bluetooth                                   | 1         | 0.32%   |
| IMC Networks Bluetooth USB Host Controller        | 1         | 0.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 0.32%   |
| Fujitsu Bluetooth Device                          | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 271       | 59.82%  |
| AMD                         | 85        | 18.76%  |
| Nvidia                      | 73        | 16.11%  |
| DSEA A/S                    | 3         | 0.66%   |
| HECATE G4 TE GAMING HEADSET | 2         | 0.44%   |
| Generalplus Technology      | 2         | 0.44%   |
| ESS Technology              | 2         | 0.44%   |
| Apple                       | 2         | 0.44%   |
| Walmart                     | 1         | 0.22%   |
| VIA Technologies            | 1         | 0.22%   |
| Sony                        | 1         | 0.22%   |
| Logitech                    | 1         | 0.22%   |
| Lenovo                      | 1         | 0.22%   |
| JMTek                       | 1         | 0.22%   |
| iCreate Technologies        | 1         | 0.22%   |
| Huawei Technologies         | 1         | 0.22%   |
| FiiO Electronics Technology | 1         | 0.22%   |
| C-Media Electronics         | 1         | 0.22%   |
| BEHRINGER International     | 1         | 0.22%   |
| AudioQuest                  | 1         | 0.22%   |
| ASUSTek Computer            | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 78        | 14.34%  |
| Intel Sunrise Point-LP HD Audio                                            | 42        | 7.72%   |
| AMD Radeon High Definition Audio Controller                                | 38        | 6.99%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 21        | 3.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 3.49%   |
| Nvidia AD107 High Definition Audio Controller                              | 16        | 2.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 2.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 2.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 13        | 2.39%   |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 2.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 2.02%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 2.02%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 1.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 1.65%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 8         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 1.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 1.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 7         | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.29%   |
| Nvidia GA107 High Definition Audio Controller                              | 6         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.92%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5         | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.74%   |
| Nvidia AD106M High Definition Audio Controller                             | 4         | 0.74%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.55%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.55%   |
| Intel Arrow Lake cAVS                                                      | 3         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 88        | 31.54%  |
| SK hynix                   | 70        | 25.09%  |
| Micron Technology          | 41        | 14.7%   |
| Unknown                    | 19        | 6.81%   |
| Crucial                    | 15        | 5.38%   |
| Kingston                   | 12        | 4.3%    |
| Unknown                    | 10        | 3.58%   |
| A-DATA Technology          | 5         | 1.79%   |
| Unknown (ABCD)             | 4         | 1.43%   |
| Elpida                     | 3         | 1.08%   |
| Ramaxel Technology         | 2         | 0.72%   |
| Unknown (08C8)             | 1         | 0.36%   |
| Team                       | 1         | 0.36%   |
| Silicon Power              | 1         | 0.36%   |
| Shenzhen Jinge Information | 1         | 0.36%   |
| Patriot                    | 1         | 0.36%   |
| Nanya Technology           | 1         | 0.36%   |
| Lenovo                     | 1         | 0.36%   |
| Kingmax                    | 1         | 0.36%   |
| Corsair                    | 1         | 0.36%   |
| ChangXin Memory            | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 10        | 3.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 5         | 1.72%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s           | 5         | 1.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 4         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 4         | 1.37%   |
| SK hynix RAM H58G66BK7BX067 8GB Row Of Chips LPDDR5 7500MT/s      | 4         | 1.37%   |
| Samsung RAM M471A1K43BB0-CPB 8GiB SODIMM DDR4 2133MT/s            | 4         | 1.37%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GiB SODIMM DDR5 5600MT/s         | 4         | 1.37%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                      | 3         | 1.03%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s            | 3         | 1.03%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 3         | 1.03%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s             | 3         | 1.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 3         | 1.03%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s             | 3         | 1.03%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s      | 3         | 1.03%   |
| Samsung RAM K3KL9L90CM-MGCT 4GB Row Of Chips LPDDR5 7500MT/s      | 3         | 1.03%   |
| Micron RAM MT62F2G32D4DS-026 4GB Row Of Chips LPDDR5 7500MT/s     | 3         | 1.03%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                       | 2         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR                                 | 2         | 0.69%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 2         | 0.69%   |
| Unknown RAM Module 256MB SODIMM DRAM                              | 2         | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 2         | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s    | 2         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s            | 2         | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.69%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s            | 2         | 0.69%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GiB Row Of Chips LPDDR4 4800MT/s | 2         | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.69%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s             | 2         | 0.69%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s            | 2         | 0.69%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s            | 2         | 0.69%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 2         | 0.69%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s      | 2         | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 2         | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.69%   |
| Samsung RAM M425R2GA3EB0-CWMOL 16GB SODIMM DDR5 5600MT/s          | 2         | 0.69%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s           | 2         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 96        | 39.34%  |
| DDR5    | 32        | 13.11%  |
| DDR3    | 31        | 12.7%   |
| LPDDR5  | 28        | 11.48%  |
| LPDDR4  | 23        | 9.43%   |
| LPDDR3  | 16        | 6.56%   |
| DDR2    | 8         | 3.28%   |
| SDRAM   | 3         | 1.23%   |
| DRAM    | 3         | 1.23%   |
| DDR     | 2         | 0.82%   |
| Unknown | 2         | 0.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 170       | 68.83%  |
| Row Of Chips | 67        | 27.13%  |
| DIMM         | 6         | 2.43%   |
| Unknown      | 3         | 1.21%   |
| Chip         | 1         | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 101       | 37.97%  |
| 4096  | 52        | 19.55%  |
| 16384 | 51        | 19.17%  |
| 32768 | 25        | 9.4%    |
| 2048  | 20        | 7.52%   |
| 1024  | 6         | 2.26%   |
| 3072  | 2         | 0.75%   |
| 512   | 2         | 0.75%   |
| 256   | 2         | 0.75%   |
| 64    | 2         | 0.75%   |
| 49152 | 1         | 0.38%   |
| 232   | 1         | 0.38%   |
| 128   | 1         | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 43        | 16.73%  |
| 2667    | 43        | 16.73%  |
| 1600    | 25        | 9.73%   |
| 5600    | 20        | 7.78%   |
| 2133    | 17        | 6.61%   |
| 2400    | 16        | 6.23%   |
| 4800    | 14        | 5.45%   |
| 7500    | 13        | 5.06%   |
| 6400    | 11        | 4.28%   |
| 4267    | 10        | 3.89%   |
| 1867    | 8         | 3.11%   |
| Unknown | 8         | 3.11%   |
| 3266    | 5         | 1.95%   |
| 8533    | 4         | 1.56%   |
| 1334    | 3         | 1.17%   |
| 667     | 3         | 1.17%   |
| 8400    | 2         | 0.78%   |
| 3733    | 2         | 0.78%   |
| 533     | 2         | 0.78%   |
| 200     | 2         | 0.78%   |
| 4266    | 1         | 0.39%   |
| 2933    | 1         | 0.39%   |
| 1067    | 1         | 0.39%   |
| 1066    | 1         | 0.39%   |
| 975     | 1         | 0.39%   |
| 333     | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Xiaomi | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Xiaomi MiMouse 2 | 1         | 100%    |

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
| Chicony Electronics                    | 74        | 23.49%  |
| IMC Networks                           | 34        | 10.79%  |
| Bison Electronics                      | 28        | 8.89%   |
| Luxvisions Innotech Limited            | 23        | 7.3%    |
| Realtek Semiconductor                  | 17        | 5.4%    |
| Microdia                               | 17        | 5.4%    |
| Sunplus Innovation Technology          | 11        | 3.49%   |
| Quanta                                 | 11        | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.49%   |
| Syntek                                 | 9         | 2.86%   |
| Apple                                  | 9         | 2.86%   |
| SunplusIT                              | 7         | 2.22%   |
| Sonix Technology                       | 7         | 2.22%   |
| Alcor Micro                            | 6         | 1.9%    |
| Silicon Motion                         | 5         | 1.59%   |
| Microsoft                              | 5         | 1.59%   |
| Suyin                                  | 4         | 1.27%   |
| Shinetech                              | 4         | 1.27%   |
| Lite-On Technology                     | 4         | 1.27%   |
| Tripath Technology                     | 3         | 0.95%   |
| Acer                                   | 3         | 0.95%   |
| Ricoh                                  | 2         | 0.63%   |
| kingcome                               | 2         | 0.63%   |
| Importek                               | 2         | 0.63%   |
| Xiaomi                                 | 1         | 0.32%   |
| WaveRider Communications               | 1         | 0.32%   |
| SN0002                                 | 1         | 0.32%   |
| ShineOptics                            | 1         | 0.32%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| Nebraska Furniture Mart                | 1         | 0.32%   |
| Logitech                               | 1         | 0.32%   |
| lihappe8                               | 1         | 0.32%   |
| Lenovo                                 | 1         | 0.32%   |
| Intel                                  | 1         | 0.32%   |
| icSpring                               | 1         | 0.32%   |
| HYGD-220831-A                          | 1         | 0.32%   |
| Genesys Logic                          | 1         | 0.32%   |
| eMPIA Technology                       | 1         | 0.32%   |
| BillionPixels                          | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 35        | 10.94%  |
| IMC Networks Integrated Camera                                  | 13        | 4.06%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 12        | 3.75%   |
| Microdia Integrated_Webcam_HD                                   | 11        | 3.44%   |
| Bison Integrated Camera                                         | 10        | 3.13%   |
| Luxvisions Innotech Limited Integrated Camera                   | 9         | 2.81%   |
| Chicony FJ Camera                                               | 9         | 2.81%   |
| Realtek Integrated_Webcam_HD                                    | 8         | 2.5%    |
| Syntek Integrated Camera                                        | 7         | 2.19%   |
| Chicony HD WebCam                                               | 7         | 2.19%   |
| SunplusIT HD Webcam                                             | 6         | 1.88%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 6         | 1.88%   |
| Bison Integrated RGB Camera                                     | 5         | 1.56%   |
| Apple FaceTime HD Camera (Built-in)                             | 5         | 1.56%   |
| Sonix USB2.0 FHD UVC WebCam                                     | 4         | 1.25%   |
| Shinetech USB2.0 FHD UVC WebCam                                 | 4         | 1.25%   |
| Microsoft LifeCam Cinema                                        | 4         | 1.25%   |
| Lite-On Integrated Camera                                       | 4         | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 4         | 1.25%   |
| Alcor Micro USB 2.0 Camera                                      | 4         | 1.25%   |
| Tripath PC Camera                                               | 3         | 0.94%   |
| Sunplus Integrated_Webcam_HD                                    | 3         | 0.94%   |
| Sonix USB2.0 HD UVC WebCam                                      | 3         | 0.94%   |
| Quanta HD User Facing                                           | 3         | 0.94%   |
| Luxvisions Innotech Limited HP HD Camera                        | 3         | 0.94%   |
| Chicony Integrated IR Camera                                    | 3         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 3         | 0.94%   |
| Bison Lenovo EasyCamera                                         | 3         | 0.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 3         | 0.94%   |
| Acer Integrated Camera                                          | 3         | 0.94%   |
| Sunplus Integrated Camera                                       | 2         | 0.63%   |
| Silicon Motion 720p HD Camera                                   | 2         | 0.63%   |
| Realtek USB Camera                                              | 2         | 0.63%   |
| Realtek Front Camera                                            | 2         | 0.63%   |
| Quanta hm1091_techfront                                         | 2         | 0.63%   |
| Quanta ACER HD User Facing                                      | 2         | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 0.63%   |
| Importek FJ Camera                                              | 2         | 0.63%   |
| Chicony VGA WebCam                                              | 2         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 26        | 37.68%  |
| Validity Sensors                   | 15        | 21.74%  |
| Shenzhen Goodix Technology         | 12        | 17.39%  |
| Upek                               | 4         | 5.8%    |
| LighTuning Technology              | 4         | 5.8%    |
| AuthenTec                          | 4         | 5.8%    |
| Samsung Electronics                | 2         | 2.9%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.45%   |
| Focal-systems.Corp                 | 1         | 1.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 9         | 13.04%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 7         | 10.14%  |
| Shenzhen Goodix  FingerPrint Device                             | 6         | 8.7%    |
| Validity Sensors Synaptics WBDI                                 | 5         | 7.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 5.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 5.8%    |
| Synaptics UWP WBDI Device                                       | 4         | 5.8%    |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 4.35%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 3         | 4.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 2.9%    |
| Synaptics Prometheus Fingerprint Reader                         | 2         | 2.9%    |
| AuthenTec Fingerprint Sensor                                    | 2         | 2.9%    |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 2.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.45%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 1.45%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.45%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.45%   |
| Synaptics WBDI                                                  | 1         | 1.45%   |
| Synaptics UWP WBDI                                              | 1         | 1.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.45%   |
| Samsung Fingerprint Sensor Device - 730B                        | 1         | 1.45%   |
| Samsung Fingerprint Device                                      | 1         | 1.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.45%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.45%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.45%   |
| Unknown                                                         | 1         | 1.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 45%     |
| Upek                  | 4         | 20%     |
| Alcor Micro           | 3         | 15%     |
| Lenovo                | 2         | 10%     |
| O2 Micro              | 1         | 5%      |
| Advanced Card Systems | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 20%     |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 15%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 15%     |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10%     |
| Broadcom 5880                                                                | 2         | 10%     |
| Broadcom 58200                                                               | 2         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5%      |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 220       | 59.95%  |
| 1     | 114       | 31.06%  |
| 2     | 25        | 6.81%   |
| 3     | 5         | 1.36%   |
| 7     | 1         | 0.27%   |
| 5     | 1         | 0.27%   |
| 4     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 64        | 33.68%  |
| Graphics card            | 44        | 23.16%  |
| Multimedia controller    | 20        | 10.53%  |
| Chipcard                 | 19        | 10%     |
| Net/wireless             | 11        | 5.79%   |
| Communication controller | 8         | 4.21%   |
| Camera                   | 8         | 4.21%   |
| Bluetooth                | 4         | 2.11%   |
| Modem                    | 3         | 1.58%   |
| Card reader              | 3         | 1.58%   |
| Sound                    | 2         | 1.05%   |
| Net/ethernet             | 2         | 1.05%   |
| Storage                  | 1         | 0.53%   |
| Network                  | 1         | 0.53%   |

