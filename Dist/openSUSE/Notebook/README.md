openSUSE - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for openSUSE.

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

Total: 1579

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Maibenben     | MaiBook X series            | [5e11bea093](https://linux-hardware.org/?probe=5e11bea093) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | [70ce1e280f](https://linux-hardware.org/?probe=70ce1e280f) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | [b5e0044759](https://linux-hardware.org/?probe=b5e0044759) | Jun 30, 2023 |
| Apple         | MacBookPro12,1              | [6cc649e9ba](https://linux-hardware.org/?probe=6cc649e9ba) | Jun 29, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| Acer          | Aspire V3-571G              | [9d4c4f5506](https://linux-hardware.org/?probe=9d4c4f5506) | Jun 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6a29eda577](https://linux-hardware.org/?probe=6a29eda577) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bf4abd6e9e](https://linux-hardware.org/?probe=bf4abd6e9e) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [3ea9e41d03](https://linux-hardware.org/?probe=3ea9e41d03) | Jun 28, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [465cc8968f](https://linux-hardware.org/?probe=465cc8968f) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [fce3ec0379](https://linux-hardware.org/?probe=fce3ec0379) | Jun 27, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [97b1fc630a](https://linux-hardware.org/?probe=97b1fc630a) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [71f17d4d74](https://linux-hardware.org/?probe=71f17d4d74) | Jun 24, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | [ebfe7d469a](https://linux-hardware.org/?probe=ebfe7d469a) | Jun 24, 2023 |
| ASUSTek       | K53TK                       | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [1d6a241c9e](https://linux-hardware.org/?probe=1d6a241c9e) | Jun 23, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fed92425f3](https://linux-hardware.org/?probe=fed92425f3) | Jun 23, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [e3ded6b5e4](https://linux-hardware.org/?probe=e3ded6b5e4) | Jun 19, 2023 |
| Lenovo        | G50-45 80E3                 | [1f1209bd20](https://linux-hardware.org/?probe=1f1209bd20) | Jun 19, 2023 |
| Notebook      | NLx0MU                      | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [34610e62fe](https://linux-hardware.org/?probe=34610e62fe) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [bd4abe1a68](https://linux-hardware.org/?probe=bd4abe1a68) | Jun 18, 2023 |
| HP            | EliteBook 840 G5            | [7c7742bf5a](https://linux-hardware.org/?probe=7c7742bf5a) | Jun 18, 2023 |
| HP            | Laptop 17-bs0xx             | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| HONOR         | BMH-WCX9                    | [da0a4b3bf0](https://linux-hardware.org/?probe=da0a4b3bf0) | Jun 16, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [940ab1af2a](https://linux-hardware.org/?probe=940ab1af2a) | Jun 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [4d81fc8320](https://linux-hardware.org/?probe=4d81fc8320) | Jun 15, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [cb6681d609](https://linux-hardware.org/?probe=cb6681d609) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [9b67ef406b](https://linux-hardware.org/?probe=9b67ef406b) | Jun 14, 2023 |
| HP            | ProBook 430 G1              | [b972bb9890](https://linux-hardware.org/?probe=b972bb9890) | Jun 14, 2023 |
| Gigabyte      | AORUS 17X AXF               | [3715cf9513](https://linux-hardware.org/?probe=3715cf9513) | Jun 14, 2023 |
| HP            | Laptop 17-bs0xx             | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3f3cbfd7fe](https://linux-hardware.org/?probe=3f3cbfd7fe) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [effdc6a5a3](https://linux-hardware.org/?probe=effdc6a5a3) | Jun 12, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| Notebook      | NS50_70MU                   | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [758afab931](https://linux-hardware.org/?probe=758afab931) | Jun 10, 2023 |
| Acer          | Aspire F5-573G              | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Apple         | MacBookPro11,4              | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| Gigabyte      | AORUS 17X AXF               | [685ba556b4](https://linux-hardware.org/?probe=685ba556b4) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Dell          | Precision 5540              | [0e925c8b3c](https://linux-hardware.org/?probe=0e925c8b3c) | Jun 08, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [f6fddfcd65](https://linux-hardware.org/?probe=f6fddfcd65) | Jun 07, 2023 |
| MSI           | CreatorPro X17 A12UKS       | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| Gigabyte      | AORUS 17X AXF               | [87bd8323b6](https://linux-hardware.org/?probe=87bd8323b6) | Jun 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [2508cbfdd2](https://linux-hardware.org/?probe=2508cbfdd2) | Jun 06, 2023 |
| MSI           | Stealth 15M B12UE           | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| Sony          | VPCEH25EN                   | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| Acer          | Aspire 3820                 | [edbf91844a](https://linux-hardware.org/?probe=edbf91844a) | Jun 04, 2023 |
| Dell          | Inspiron N4030              | [4d82d8bf8b](https://linux-hardware.org/?probe=4d82d8bf8b) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cdbebd8a7e](https://linux-hardware.org/?probe=cdbebd8a7e) | Jun 04, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| MSI           | Modern 14 B5M               | [25ffe9ad37](https://linux-hardware.org/?probe=25ffe9ad37) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| Dell          | G15 5520                    | [5880c98c54](https://linux-hardware.org/?probe=5880c98c54) | Jun 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [2bcfc48199](https://linux-hardware.org/?probe=2bcfc48199) | Jun 02, 2023 |
| Dell          | Inspiron 3501               | [2cf19f7b32](https://linux-hardware.org/?probe=2cf19f7b32) | Jun 02, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [71c2818f01](https://linux-hardware.org/?probe=71c2818f01) | Jun 01, 2023 |
| Apple         | MacBook5,1                  | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| HP            | Laptop 15-bs1xx             | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| Acer          | Aspire V3-571G              | [d3afe375cf](https://linux-hardware.org/?probe=d3afe375cf) | May 28, 2023 |
| Acer          | Nitro AN517-54              | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| Dell          | Latitude 3440               | [1d32fe235f](https://linux-hardware.org/?probe=1d32fe235f) | May 26, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f4de9c8a5f](https://linux-hardware.org/?probe=f4de9c8a5f) | May 26, 2023 |
| HP            | Laptop 17-cn0xxx            | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| Acer          | Aspire A314-22              | [776f5c2411](https://linux-hardware.org/?probe=776f5c2411) | May 25, 2023 |
| Acer          | Aspire A314-22              | [e2110ab5da](https://linux-hardware.org/?probe=e2110ab5da) | May 25, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Apple         | MacBookPro8,1               | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| HP            | ENVY m6 Notebook            | [f133543500](https://linux-hardware.org/?probe=f133543500) | May 23, 2023 |
| Acer          | Aspire A315-43              | [926421c6be](https://linux-hardware.org/?probe=926421c6be) | May 22, 2023 |
| HP            | ENVY m6 Notebook            | [c903e06758](https://linux-hardware.org/?probe=c903e06758) | May 22, 2023 |
| HP            | EliteBook 830 G5            | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | [a6e8e03e74](https://linux-hardware.org/?probe=a6e8e03e74) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| Dell          | XPS 15 9550                 | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8EG0... | [0735cab104](https://linux-hardware.org/?probe=0735cab104) | May 18, 2023 |
| HP            | Laptop 15s-fq2xxx           | [ad17e04f3b](https://linux-hardware.org/?probe=ad17e04f3b) | May 17, 2023 |
| Dell          | Inspiron 3501               | [74c412b40a](https://linux-hardware.org/?probe=74c412b40a) | May 16, 2023 |
| MSI           | Stealth 15M B12UE           | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| Dell          | Latitude 5320               | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [61499d189f](https://linux-hardware.org/?probe=61499d189f) | May 15, 2023 |
| HP            | EliteBook 830 G5            | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| HP            | Victus by Gaming Laptop ... | [2dc2bdd057](https://linux-hardware.org/?probe=2dc2bdd057) | May 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [6335ace28b](https://linux-hardware.org/?probe=6335ace28b) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Lenovo        | ThinkPad L540 20AUS01H00    | [d39599a293](https://linux-hardware.org/?probe=d39599a293) | May 12, 2023 |
| Apple         | MacBookPro11,3              | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Apple         | MacBookPro9,2               | [165d6e12b4](https://linux-hardware.org/?probe=165d6e12b4) | May 11, 2023 |
| Lenovo        | ThinkPad T530 23926CU       | [4e7cab81f3](https://linux-hardware.org/?probe=4e7cab81f3) | May 11, 2023 |
| Lenovo        | ThinkPad W541 20EF001UGE    | [29c8170a0e](https://linux-hardware.org/?probe=29c8170a0e) | May 10, 2023 |
| Apple         | MacBookPro9,2               | [49e9002825](https://linux-hardware.org/?probe=49e9002825) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | [c0ad43f440](https://linux-hardware.org/?probe=c0ad43f440) | May 09, 2023 |
| Acer          | Aspire E5-553G              | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | [f3572c500c](https://linux-hardware.org/?probe=f3572c500c) | May 09, 2023 |
| Acer          | Aspire A315-53              | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Lenovo        | ThinkPad T410 2522K3U       | [55756e1659](https://linux-hardware.org/?probe=55756e1659) | May 07, 2023 |
| Acer          | Aspire 5742G                | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| Maibenben     | MaiBook M                   | [aaad2fda16](https://linux-hardware.org/?probe=aaad2fda16) | May 06, 2023 |
| Maibenben     | MaiBook M                   | [c6b9cf8729](https://linux-hardware.org/?probe=c6b9cf8729) | May 05, 2023 |
| ASUSTek       | K42Jc                       | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [f9a56b49f3](https://linux-hardware.org/?probe=f9a56b49f3) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab21408c4c](https://linux-hardware.org/?probe=ab21408c4c) | May 03, 2023 |
| Apple         | MacBook5,1                  | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e9bd630708](https://linux-hardware.org/?probe=e9bd630708) | May 01, 2023 |
| Apple         | MacBookPro6,2               | [0cb8947c84](https://linux-hardware.org/?probe=0cb8947c84) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9876205c45](https://linux-hardware.org/?probe=9876205c45) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| Acer          | Aspire V3-772               | [a1584c31ec](https://linux-hardware.org/?probe=a1584c31ec) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | [5f191f449f](https://linux-hardware.org/?probe=5f191f449f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Acer          | Aspire E1-572G              | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5c5fece872](https://linux-hardware.org/?probe=5c5fece872) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| Dell          | Inspiron 3501               | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| ASUSTek       | N750JV                      | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| Acer          | Nitro AN515-51              | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Apple         | MacBookAir7,2               | [2ccfcd2b27](https://linux-hardware.org/?probe=2ccfcd2b27) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Google        | Kefka                       | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| ASUSTek       | GL703VM                     | [f3c76b5075](https://linux-hardware.org/?probe=f3c76b5075) | Apr 23, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | [2aa36b9cfd](https://linux-hardware.org/?probe=2aa36b9cfd) | Apr 22, 2023 |
| Allview       | Allbook J                   | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| Gateway       | NV55C                       | [e77192c3b1](https://linux-hardware.org/?probe=e77192c3b1) | Apr 20, 2023 |
| HP            | Laptop 17-ca0xxx            | [50f90c0b1f](https://linux-hardware.org/?probe=50f90c0b1f) | Apr 20, 2023 |
| MSI           | Vector GP76 12UHSO          | [e299a6ed8e](https://linux-hardware.org/?probe=e299a6ed8e) | Apr 20, 2023 |
| Dell          | Latitude 7410               | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| Lenovo        | G50-45 80E3                 | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [69b2b1c95f](https://linux-hardware.org/?probe=69b2b1c95f) | Apr 19, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Allview       | Allbook J                   | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [482a8c29cc](https://linux-hardware.org/?probe=482a8c29cc) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Toshiba       | Satellite C45-A             | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| HP            | Mini 210-1000               | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| ASUSTek       | GL502VM                     | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Apple         | MacBookPro8,1               | [6e34f5a7b8](https://linux-hardware.org/?probe=6e34f5a7b8) | Apr 13, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| ASUSTek       | TP500LAG                    | [ae048d3165](https://linux-hardware.org/?probe=ae048d3165) | Apr 12, 2023 |
| MSI           | Stealth 14Studio A13VF      | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| MSI           | Vector GP76 12UHSO          | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| ASUSTek       | TP500LAG                    | [b67954cc59](https://linux-hardware.org/?probe=b67954cc59) | Apr 10, 2023 |
| Gigabyte      | G5 KF                       | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1ab81a719b](https://linux-hardware.org/?probe=1ab81a719b) | Apr 08, 2023 |
| Dell          | Latitude 5431               | [d85ac2917b](https://linux-hardware.org/?probe=d85ac2917b) | Apr 07, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| Dell          | Precision 5530              | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | Unknown                     | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| HP            | EliteBook 865 16 inch G9... | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| Apple         | MacBookPro11,3              | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK U938               | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | Compaq 6730s                | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| MSI           | Bravo 15 B5DD               | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| Lenovo        | G580 20157                  | [98df8e769b](https://linux-hardware.org/?probe=98df8e769b) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Packard Be... | EasyNote TE11HC             | [6c942c5a39](https://linux-hardware.org/?probe=6c942c5a39) | Mar 26, 2023 |
| HP            | ProBook 645 G4              | [6a03f43f29](https://linux-hardware.org/?probe=6a03f43f29) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | [640a9ac505](https://linux-hardware.org/?probe=640a9ac505) | Mar 24, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [b618258a5c](https://linux-hardware.org/?probe=b618258a5c) | Mar 22, 2023 |
| Dell          | Latitude D530               | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7b772c82ca](https://linux-hardware.org/?probe=7b772c82ca) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bd045deb23](https://linux-hardware.org/?probe=bd045deb23) | Mar 21, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [c87a678cf5](https://linux-hardware.org/?probe=c87a678cf5) | Mar 21, 2023 |
| Lenovo        | LEGION5PRO-16ACH6H 82JQ     | [4f3cbedf85](https://linux-hardware.org/?probe=4f3cbedf85) | Mar 20, 2023 |
| Dell          | XPS 15 9570                 | [729a1432a0](https://linux-hardware.org/?probe=729a1432a0) | Mar 19, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [9cdd00c854](https://linux-hardware.org/?probe=9cdd00c854) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [f35715c399](https://linux-hardware.org/?probe=f35715c399) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [92d818d184](https://linux-hardware.org/?probe=92d818d184) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [60114cc9c8](https://linux-hardware.org/?probe=60114cc9c8) | Mar 16, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [4a47120f89](https://linux-hardware.org/?probe=4a47120f89) | Mar 15, 2023 |
| HP            | EliteBook 820 G4            | [bc12f3e2e4](https://linux-hardware.org/?probe=bc12f3e2e4) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [2b69e73996](https://linux-hardware.org/?probe=2b69e73996) | Mar 14, 2023 |
| Lenovo        | ThinkPad Edge E530 3259H... | [74348d01f3](https://linux-hardware.org/?probe=74348d01f3) | Mar 13, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [8dc295e39b](https://linux-hardware.org/?probe=8dc295e39b) | Mar 13, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | [fac1ee2528](https://linux-hardware.org/?probe=fac1ee2528) | Mar 12, 2023 |
| Acer          | Swift SF314-43              | [8f3c49d011](https://linux-hardware.org/?probe=8f3c49d011) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| Jumper        | EZbook                      | [ed607c4113](https://linux-hardware.org/?probe=ed607c4113) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [54e498fb2e](https://linux-hardware.org/?probe=54e498fb2e) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | [d524e6c586](https://linux-hardware.org/?probe=d524e6c586) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | [2d75f5ea8b](https://linux-hardware.org/?probe=2d75f5ea8b) | Mar 10, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1490c281bd](https://linux-hardware.org/?probe=1490c281bd) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [9b1357d5c0](https://linux-hardware.org/?probe=9b1357d5c0) | Mar 06, 2023 |
| Acer          | Aspire A314-35              | [3e4fdfbb73](https://linux-hardware.org/?probe=3e4fdfbb73) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| Acer          | Aspire A314-35              | [587096ec48](https://linux-hardware.org/?probe=587096ec48) | Mar 03, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d008353c16](https://linux-hardware.org/?probe=d008353c16) | Mar 01, 2023 |
| Apple         | MacBook5,1                  | [0242801bbc](https://linux-hardware.org/?probe=0242801bbc) | Mar 01, 2023 |
| Notebook      | PCx0Dx                      | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| HP            | ProBook 4540s               | [a52b9c7637](https://linux-hardware.org/?probe=a52b9c7637) | Feb 27, 2023 |
| HP            | ProBook 4540s               | [45e989b539](https://linux-hardware.org/?probe=45e989b539) | Feb 27, 2023 |
| HP            | Notebook                    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| ASUSTek       | X541NA                      | [8c0dc3ba82](https://linux-hardware.org/?probe=8c0dc3ba82) | Feb 27, 2023 |
| HP            | Notebook                    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| AXDIA Inte... | WINDESK9 3G v2              | [49282044d3](https://linux-hardware.org/?probe=49282044d3) | Feb 26, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [c3156c3f23](https://linux-hardware.org/?probe=c3156c3f23) | Feb 26, 2023 |
| Dell          | Inspiron 5502               | [2c490934fb](https://linux-hardware.org/?probe=2c490934fb) | Feb 24, 2023 |
| HP            | Compaq 6720s                | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| Dell          | XPS 9320                    | [896a21551e](https://linux-hardware.org/?probe=896a21551e) | Feb 22, 2023 |
| Lenovo        | IdeaPad Y900-17ISK 80Q1     | [d852e3306a](https://linux-hardware.org/?probe=d852e3306a) | Feb 20, 2023 |
| SK hynix      | HyBook                      | [494c1a322d](https://linux-hardware.org/?probe=494c1a322d) | Feb 20, 2023 |
| HP            | ProBook 4540s               | [079a5f512d](https://linux-hardware.org/?probe=079a5f512d) | Feb 20, 2023 |
| ASUSTek       | G771JW                      | [e5b5f4792c](https://linux-hardware.org/?probe=e5b5f4792c) | Feb 19, 2023 |
| ASUSTek       | G771JW                      | [c73a9b9ee2](https://linux-hardware.org/?probe=c73a9b9ee2) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [19bdc55bfd](https://linux-hardware.org/?probe=19bdc55bfd) | Feb 19, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [f4065623e5](https://linux-hardware.org/?probe=f4065623e5) | Feb 18, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [5fb2330e71](https://linux-hardware.org/?probe=5fb2330e71) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [76c8c6f7ba](https://linux-hardware.org/?probe=76c8c6f7ba) | Feb 17, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [9497d288f6](https://linux-hardware.org/?probe=9497d288f6) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| Google        | Lillipup                    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| HP            | ProBook 6460b               | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | [0a6d50bc2a](https://linux-hardware.org/?probe=0a6d50bc2a) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | [75980f2f55](https://linux-hardware.org/?probe=75980f2f55) | Feb 13, 2023 |
| Samsung       | 550XDA                      | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| Toshiba       | PORTEGE Z830                | [a384bb740c](https://linux-hardware.org/?probe=a384bb740c) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [df97c92c82](https://linux-hardware.org/?probe=df97c92c82) | Feb 11, 2023 |
| Dell          | Precision 5570              | [8398c80e6b](https://linux-hardware.org/?probe=8398c80e6b) | Feb 11, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f721ad33a](https://linux-hardware.org/?probe=2f721ad33a) | Feb 10, 2023 |
| Dell          | Latitude 5421               | [e7c6fbfeb8](https://linux-hardware.org/?probe=e7c6fbfeb8) | Feb 09, 2023 |
| Unknown       | M-140BI5                    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Schenker      | VIA 15                      | [8096682644](https://linux-hardware.org/?probe=8096682644) | Feb 09, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2V90... | [a2e7b3b9b7](https://linux-hardware.org/?probe=a2e7b3b9b7) | Feb 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [acbbbca6e7](https://linux-hardware.org/?probe=acbbbca6e7) | Feb 08, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [9b92561723](https://linux-hardware.org/?probe=9b92561723) | Feb 06, 2023 |
| Medion        | P6624                       | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| Dell          | Latitude E7470              | [88a8b69cc3](https://linux-hardware.org/?probe=88a8b69cc3) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| HP            | Pavilion dv7                | [b61ed06b1e](https://linux-hardware.org/?probe=b61ed06b1e) | Jan 30, 2023 |
| Toshiba       | Satellite L500              | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f20e47b9d7](https://linux-hardware.org/?probe=f20e47b9d7) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [de71656929](https://linux-hardware.org/?probe=de71656929) | Jan 27, 2023 |
| Lenovo        | ThinkPad R500 2718WA3       | [2bb86279a8](https://linux-hardware.org/?probe=2bb86279a8) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Fujitsu       | LIFEBOOK U7511              | [7b9b00eccb](https://linux-hardware.org/?probe=7b9b00eccb) | Jan 24, 2023 |
| Acer          | Swift SFX16-52G             | [62e1cc77f9](https://linux-hardware.org/?probe=62e1cc77f9) | Jan 23, 2023 |
| HP            | Pavilion dv4                | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | [282161cc92](https://linux-hardware.org/?probe=282161cc92) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | [8d235b1b8d](https://linux-hardware.org/?probe=8d235b1b8d) | Jan 22, 2023 |
| Acer          | Predator PH315-52           | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Dell          | Latitude 9420               | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Fujitsu       | LIFEBOOK P1630              | [5ee218deb4](https://linux-hardware.org/?probe=5ee218deb4) | Jan 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| Medion        | P6624                       | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| ASUSTek       | X555LF                      | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [1f56f8cb21](https://linux-hardware.org/?probe=1f56f8cb21) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [004b2669ef](https://linux-hardware.org/?probe=004b2669ef) | Jan 18, 2023 |
| Fujitsu       | LIFEBOOK P1630              | [5a9662e39b](https://linux-hardware.org/?probe=5a9662e39b) | Jan 17, 2023 |
| HP            | ProBook 4540s               | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| HP            | ProBook 4540s               | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [9b874af8a4](https://linux-hardware.org/?probe=9b874af8a4) | Jan 16, 2023 |
| HP            | Pavilion dv7                | [ae33b4bb24](https://linux-hardware.org/?probe=ae33b4bb24) | Jan 16, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [9bfcd0f555](https://linux-hardware.org/?probe=9bfcd0f555) | Jan 14, 2023 |
| Dell          | Latitude 5414               | [bc4fdb0971](https://linux-hardware.org/?probe=bc4fdb0971) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| HP            | Laptop 15-ef2xxx            | [e8bf140d81](https://linux-hardware.org/?probe=e8bf140d81) | Jan 12, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a5ea710efd](https://linux-hardware.org/?probe=a5ea710efd) | Jan 11, 2023 |
| HP            | ENVY 15                     | [bff59f1d42](https://linux-hardware.org/?probe=bff59f1d42) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Dell          | G7 7790                     | [ffaafd92cf](https://linux-hardware.org/?probe=ffaafd92cf) | Jan 05, 2023 |
| Dell          | Latitude 5430               | [4e8033e0f6](https://linux-hardware.org/?probe=4e8033e0f6) | Jan 05, 2023 |
| Maibenben     | MaiBook M                   | [6b475a50fc](https://linux-hardware.org/?probe=6b475a50fc) | Jan 05, 2023 |
| Dell          | Inspiron 15 3525            | [e11b38ed14](https://linux-hardware.org/?probe=e11b38ed14) | Jan 05, 2023 |
| Apple         | MacBook5,1                  | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Dell          | G3 3579                     | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| MSI           | Stealth 15M B12UE           | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| HP            | Dev One Notebook PC         | [092aa8fe44](https://linux-hardware.org/?probe=092aa8fe44) | Jan 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [a8ce1c44a8](https://linux-hardware.org/?probe=a8ce1c44a8) | Jan 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c7a7749a95](https://linux-hardware.org/?probe=c7a7749a95) | Dec 30, 2022 |
| Dell          | XPS 9320                    | [458727c26e](https://linux-hardware.org/?probe=458727c26e) | Dec 30, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [250104c525](https://linux-hardware.org/?probe=250104c525) | Dec 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [23fe358945](https://linux-hardware.org/?probe=23fe358945) | Dec 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [442fcdba27](https://linux-hardware.org/?probe=442fcdba27) | Dec 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [4ad973e635](https://linux-hardware.org/?probe=4ad973e635) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [1c5b59d2e4](https://linux-hardware.org/?probe=1c5b59d2e4) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [730469b496](https://linux-hardware.org/?probe=730469b496) | Dec 26, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [cc51ba5d49](https://linux-hardware.org/?probe=cc51ba5d49) | Dec 24, 2022 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [660e3a6511](https://linux-hardware.org/?probe=660e3a6511) | Dec 24, 2022 |
| Dell          | Inspiron 3593               | [a640541ee0](https://linux-hardware.org/?probe=a640541ee0) | Dec 24, 2022 |
| Dell          | Inspiron 15 7510            | [d5702b0c66](https://linux-hardware.org/?probe=d5702b0c66) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| HP            | Pavilion 17                 | [0adc0d708b](https://linux-hardware.org/?probe=0adc0d708b) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [b26dc749a5](https://linux-hardware.org/?probe=b26dc749a5) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Acer          | Nitro AN515-51              | [9dca0f7674](https://linux-hardware.org/?probe=9dca0f7674) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3a505870ba](https://linux-hardware.org/?probe=3a505870ba) | Dec 22, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [13e778509f](https://linux-hardware.org/?probe=13e778509f) | Dec 22, 2022 |
| Dell          | Latitude 5510               | [b4f32be15b](https://linux-hardware.org/?probe=b4f32be15b) | Dec 22, 2022 |
| Multilaser    | MLSH1H LINUX                | [70695e9f3b](https://linux-hardware.org/?probe=70695e9f3b) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [5ea57fb331](https://linux-hardware.org/?probe=5ea57fb331) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [6ec5c4fc19](https://linux-hardware.org/?probe=6ec5c4fc19) | Dec 21, 2022 |
| Dell          | XPS 9320                    | [ce5835b58d](https://linux-hardware.org/?probe=ce5835b58d) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a4549398af](https://linux-hardware.org/?probe=a4549398af) | Dec 20, 2022 |
| HUAWEI        | BOD-WXX9                    | [da35f3ec23](https://linux-hardware.org/?probe=da35f3ec23) | Dec 19, 2022 |
| Dell          | Latitude 5590               | [83e177278e](https://linux-hardware.org/?probe=83e177278e) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Acer          | Aspire E1-572G              | [adc5196d64](https://linux-hardware.org/?probe=adc5196d64) | Dec 17, 2022 |
| Lenovo        | 1S20UDCT01WWPF1ARBNP 29U... | [b5e9681592](https://linux-hardware.org/?probe=b5e9681592) | Dec 17, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [665bd04471](https://linux-hardware.org/?probe=665bd04471) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f5a317963c](https://linux-hardware.org/?probe=f5a317963c) | Dec 15, 2022 |
| Dell          | Precision 7760              | [cbe51e9db3](https://linux-hardware.org/?probe=cbe51e9db3) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [1d57f3ab30](https://linux-hardware.org/?probe=1d57f3ab30) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a1d6879fab](https://linux-hardware.org/?probe=a1d6879fab) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f18b9184ca](https://linux-hardware.org/?probe=f18b9184ca) | Dec 15, 2022 |
| Irbis         | NB264                       | [d137aad605](https://linux-hardware.org/?probe=d137aad605) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ004EU... | [8d04dfe3a5](https://linux-hardware.org/?probe=8d04dfe3a5) | Dec 12, 2022 |
| Acer          | Predator PH315-52           | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| Dell          | Inspiron 3593               | [62212b2baa](https://linux-hardware.org/?probe=62212b2baa) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| HP            | ZBook 15 G6                 | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [799ba39d5e](https://linux-hardware.org/?probe=799ba39d5e) | Dec 06, 2022 |
| Dell          | Inspiron 3593               | [6fc850bb3e](https://linux-hardware.org/?probe=6fc850bb3e) | Dec 06, 2022 |
| Dell          | Latitude E5400              | [ab5b64fe8a](https://linux-hardware.org/?probe=ab5b64fe8a) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | [5827ea2fa5](https://linux-hardware.org/?probe=5827ea2fa5) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | [7f8dcdb666](https://linux-hardware.org/?probe=7f8dcdb666) | Dec 05, 2022 |
| HP            | Pavilion 13 x360 PC         | [50bcdd33eb](https://linux-hardware.org/?probe=50bcdd33eb) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [a41d7dbfb1](https://linux-hardware.org/?probe=a41d7dbfb1) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Lenovo        | ThinkPad X260 20F6005HUS    | [6418eda1a9](https://linux-hardware.org/?probe=6418eda1a9) | Nov 27, 2022 |
| ASUSTek       | Z450LA                      | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| MSI           | GE72VR 7RF                  | [a034af6b70](https://linux-hardware.org/?probe=a034af6b70) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| Dell          | Latitude E5570              | [ed2e9cfb4f](https://linux-hardware.org/?probe=ed2e9cfb4f) | Nov 24, 2022 |
| HP            | Pavilion 15                 | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| Dell          | Latitude 5401               | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| Timi          | TM1612                      | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [d9a74ee60a](https://linux-hardware.org/?probe=d9a74ee60a) | Nov 20, 2022 |
| Acer          | Aspire A317-51              | [43c8f9b08b](https://linux-hardware.org/?probe=43c8f9b08b) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | [a4a3dabbb4](https://linux-hardware.org/?probe=a4a3dabbb4) | Nov 19, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [05c9ad6f4a](https://linux-hardware.org/?probe=05c9ad6f4a) | Nov 19, 2022 |
| Dell          | Latitude 5414               | [a408bec327](https://linux-hardware.org/?probe=a408bec327) | Nov 18, 2022 |
| Apple         | MacBook5,1                  | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| HP            | Laptop 15-ef2xxx            | [371368cfe7](https://linux-hardware.org/?probe=371368cfe7) | Nov 16, 2022 |
| HP            | Compaq 6830s                | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Lenovo        | ThinkPad T530 2394D56       | [3d44b768e5](https://linux-hardware.org/?probe=3d44b768e5) | Nov 12, 2022 |
| Toshiba       | IS 1422+                    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [969fa6c183](https://linux-hardware.org/?probe=969fa6c183) | Nov 11, 2022 |
| Intel         | (R) Education Tablet        | [13286af46e](https://linux-hardware.org/?probe=13286af46e) | Nov 10, 2022 |
| HP            | ZBook 17                    | [e866fa1319](https://linux-hardware.org/?probe=e866fa1319) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| Dell          | Inspiron 3593               | [be071c7456](https://linux-hardware.org/?probe=be071c7456) | Nov 08, 2022 |
| HP            | ZBook 17                    | [af26e94623](https://linux-hardware.org/?probe=af26e94623) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e13f29fc81](https://linux-hardware.org/?probe=e13f29fc81) | Nov 07, 2022 |
| Dell          | Inspiron 7577               | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [912bfcc57e](https://linux-hardware.org/?probe=912bfcc57e) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | [0f119b6000](https://linux-hardware.org/?probe=0f119b6000) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | [e872fcb5f7](https://linux-hardware.org/?probe=e872fcb5f7) | Nov 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [99e32a37ff](https://linux-hardware.org/?probe=99e32a37ff) | Nov 04, 2022 |
| Lenovo        | G50-45 80E3                 | [011d776675](https://linux-hardware.org/?probe=011d776675) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| HP            | Notebook                    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6314ec0dd1](https://linux-hardware.org/?probe=6314ec0dd1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [033cc83715](https://linux-hardware.org/?probe=033cc83715) | Oct 28, 2022 |
| Dell          | Latitude E6430              | [cb4eb1f556](https://linux-hardware.org/?probe=cb4eb1f556) | Oct 28, 2022 |
| Lenovo        | Unknown                     | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Dell          | Latitude 9420               | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Fujitsu       | LIFEBOOK E746               | [4c699ac628](https://linux-hardware.org/?probe=4c699ac628) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| HP            | ZBook 17                    | [6dc9848327](https://linux-hardware.org/?probe=6dc9848327) | Oct 20, 2022 |
| Sony          | VPCEL3S1R                   | [5c37559c2d](https://linux-hardware.org/?probe=5c37559c2d) | Oct 20, 2022 |
| Dell          | Inspiron 7577               | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| HP            | ZBook 15 G3                 | [a078a2f2ae](https://linux-hardware.org/?probe=a078a2f2ae) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [a66d2944a8](https://linux-hardware.org/?probe=a66d2944a8) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [b11fa8e1dd](https://linux-hardware.org/?probe=b11fa8e1dd) | Oct 16, 2022 |
| MSI           | Prestige 14 A11SCS          | [e552920463](https://linux-hardware.org/?probe=e552920463) | Oct 13, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [61eb97192e](https://linux-hardware.org/?probe=61eb97192e) | Oct 12, 2022 |
| Toshiba       | Satellite P55t-A            | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| Lenovo        | ThinkPad T430 2347DS3       | [970542656e](https://linux-hardware.org/?probe=970542656e) | Oct 11, 2022 |
| Intel         | (R) Education Tablet        | [9d1756d283](https://linux-hardware.org/?probe=9d1756d283) | Oct 09, 2022 |
| Gateway       | NV54 Series                 | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| ASUSTek       | F3Sv                        | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| Toshiba       | Satellite L350              | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [33a0cb05e8](https://linux-hardware.org/?probe=33a0cb05e8) | Oct 04, 2022 |
| Acer          | S50-54                      | [7680195105](https://linux-hardware.org/?probe=7680195105) | Oct 04, 2022 |
| Dell          | Latitude 3340               | [100b89b0a9](https://linux-hardware.org/?probe=100b89b0a9) | Oct 04, 2022 |
| Dell          | Vostro 3560                 | [79f922d367](https://linux-hardware.org/?probe=79f922d367) | Oct 02, 2022 |
| Acer          | S50-54                      | [a7ff4f9792](https://linux-hardware.org/?probe=a7ff4f9792) | Oct 02, 2022 |
| Dell          | Vostro 3560                 | [59c14fb5c0](https://linux-hardware.org/?probe=59c14fb5c0) | Oct 02, 2022 |
| Dell          | Latitude E5250              | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| HP            | ZBook 17 G2                 | [d6d9af3173](https://linux-hardware.org/?probe=d6d9af3173) | Sep 26, 2022 |
| HP            | ZBook 17 G2                 | [ff70118578](https://linux-hardware.org/?probe=ff70118578) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [911a73323d](https://linux-hardware.org/?probe=911a73323d) | Sep 24, 2022 |
| Timi          | A35S                        | [a57a688f31](https://linux-hardware.org/?probe=a57a688f31) | Sep 21, 2022 |
| Dell          | Latitude 7400               | [466bd310ef](https://linux-hardware.org/?probe=466bd310ef) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Dell          | Inspiron 5515               | [a7f0e24464](https://linux-hardware.org/?probe=a7f0e24464) | Sep 20, 2022 |
| Dell          | Inspiron 3542               | [7f7ef47d4b](https://linux-hardware.org/?probe=7f7ef47d4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [167d69530f](https://linux-hardware.org/?probe=167d69530f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d3b972d870](https://linux-hardware.org/?probe=d3b972d870) | Sep 19, 2022 |
| Acer          | Predator PH315-52           | [959330d9c1](https://linux-hardware.org/?probe=959330d9c1) | Sep 19, 2022 |
| HP            | EliteBook 8470p             | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| ASUSTek       | X55CR                       | [43b77d436c](https://linux-hardware.org/?probe=43b77d436c) | Sep 14, 2022 |
| Apple         | MacBookPro8,2               | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| MSI           | Modern 14 B5M               | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [ea53dc8c02](https://linux-hardware.org/?probe=ea53dc8c02) | Sep 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| HP            | 250 G8 Notebook PC          | [312e65fd07](https://linux-hardware.org/?probe=312e65fd07) | Sep 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [ede97805ec](https://linux-hardware.org/?probe=ede97805ec) | Sep 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [e5ae0e72ca](https://linux-hardware.org/?probe=e5ae0e72ca) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| Notebook      | N24_25JU                    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| HP            | ZBook 17                    | [98e643f5af](https://linux-hardware.org/?probe=98e643f5af) | Aug 30, 2022 |
| Positivo      | W942SW_SW1                  | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| Google        | Eldrid                      | [6a0c6eb1de](https://linux-hardware.org/?probe=6a0c6eb1de) | Aug 27, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Eluktronic... | MAX-17                      | [0a454665e0](https://linux-hardware.org/?probe=0a454665e0) | Aug 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| HP            | Laptop 17-ca0xxx            | [c956ba84ed](https://linux-hardware.org/?probe=c956ba84ed) | Aug 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| HP            | ProBook 640 G1              | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Dell          | XPS 15 9530                 | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Lenovo        | Z51-70 80K6                 | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| Notebook      | NLx0MU                      | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| HP            | Pavilion Notebook           | [a05b95b836](https://linux-hardware.org/?probe=a05b95b836) | Aug 15, 2022 |
| HP            | Pavilion Notebook           | [aea2bfde6a](https://linux-hardware.org/?probe=aea2bfde6a) | Aug 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [fd64b105a4](https://linux-hardware.org/?probe=fd64b105a4) | Aug 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [73f2db9159](https://linux-hardware.org/?probe=73f2db9159) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| Dell          | Latitude E6430              | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| HP            | Laptop 17-by1xxx            | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0aada24b1e](https://linux-hardware.org/?probe=0aada24b1e) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Valve         | Jupiter                     | [37f87e94fc](https://linux-hardware.org/?probe=37f87e94fc) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Unknown       | Unknown                     | [904bd1db44](https://linux-hardware.org/?probe=904bd1db44) | Aug 06, 2022 |
| Acer          | Aspire A515-45              | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| Dell          | Inspiron 13-7359            | [24fa962b0b](https://linux-hardware.org/?probe=24fa962b0b) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| Unknown       | Unknown                     | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
| Unknown       | Unknown                     | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [5a6d4e8ba4](https://linux-hardware.org/?probe=5a6d4e8ba4) | Jul 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b128b9e7a](https://linux-hardware.org/?probe=7b128b9e7a) | Jul 19, 2022 |
| Lenovo        | ThinkPad Edge 0328A11       | [4305889043](https://linux-hardware.org/?probe=4305889043) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [0f1dd0317a](https://linux-hardware.org/?probe=0f1dd0317a) | Jul 17, 2022 |
| Dell          | Inspiron 5584               | [b6d23c8307](https://linux-hardware.org/?probe=b6d23c8307) | Jul 16, 2022 |
| HP            | Pavilion g6                 | [556c813157](https://linux-hardware.org/?probe=556c813157) | Jul 16, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [95b0d6d487](https://linux-hardware.org/?probe=95b0d6d487) | Jul 14, 2022 |
| Jumper        | EZbook                      | [2515427610](https://linux-hardware.org/?probe=2515427610) | Jul 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Dell          | XPS 15 9510                 | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [42cc0cf38e](https://linux-hardware.org/?probe=42cc0cf38e) | Jul 07, 2022 |
| Purism        | Librem 15 v3                | [1e39d0bba8](https://linux-hardware.org/?probe=1e39d0bba8) | Jul 06, 2022 |
| Dell          | XPS 15 9570                 | [2311c99a80](https://linux-hardware.org/?probe=2311c99a80) | Jul 06, 2022 |
| Multilaser    | PC150                       | [b6fcf6d507](https://linux-hardware.org/?probe=b6fcf6d507) | Jul 04, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [80fbf3aee4](https://linux-hardware.org/?probe=80fbf3aee4) | Jul 02, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [9de0586493](https://linux-hardware.org/?probe=9de0586493) | Jul 01, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [8c7b7c1b45](https://linux-hardware.org/?probe=8c7b7c1b45) | Jul 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [bec2a7697f](https://linux-hardware.org/?probe=bec2a7697f) | Jun 30, 2022 |
| HP            | ENVY TS 17                  | [7b5d021513](https://linux-hardware.org/?probe=7b5d021513) | Jun 29, 2022 |
| Framework     | Laptop                      | [d4cd42f3af](https://linux-hardware.org/?probe=d4cd42f3af) | Jun 28, 2022 |
| Apple         | MacBook7,1                  | [2818c11c12](https://linux-hardware.org/?probe=2818c11c12) | Jun 28, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [f1b7197958](https://linux-hardware.org/?probe=f1b7197958) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Acer          | Swift SFX14-41G             | [c3c9ce7e40](https://linux-hardware.org/?probe=c3c9ce7e40) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [9a2d492e07](https://linux-hardware.org/?probe=9a2d492e07) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d98df1e3c5](https://linux-hardware.org/?probe=d98df1e3c5) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [8adbb8b56a](https://linux-hardware.org/?probe=8adbb8b56a) | Jun 22, 2022 |
| Apple         | MacBook5,1                  | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [ff63b72fd2](https://linux-hardware.org/?probe=ff63b72fd2) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [3ec9bac70f](https://linux-hardware.org/?probe=3ec9bac70f) | Jun 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cc0719c813](https://linux-hardware.org/?probe=cc0719c813) | Jun 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [52276b3971](https://linux-hardware.org/?probe=52276b3971) | Jun 16, 2022 |
| Clevo         | P7xxTM(1)                   | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | [74770880f9](https://linux-hardware.org/?probe=74770880f9) | Jun 15, 2022 |
| Apple         | MacBook7,1                  | [f14133e69e](https://linux-hardware.org/?probe=f14133e69e) | Jun 14, 2022 |
| MSI           | Raider GE76 12UH            | [c29e79e22d](https://linux-hardware.org/?probe=c29e79e22d) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | [02e4c63249](https://linux-hardware.org/?probe=02e4c63249) | Jun 12, 2022 |
| HP            | Laptop 17-ca0xxx            | [a1069bbb9d](https://linux-hardware.org/?probe=a1069bbb9d) | Jun 12, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Mini 210-1000               | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| HP            | Mini 210-1000               | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| Samsung       | 935XDB                      | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | [0970e891ee](https://linux-hardware.org/?probe=0970e891ee) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | [3b33a1b625](https://linux-hardware.org/?probe=3b33a1b625) | Jun 07, 2022 |
| Toshiba       | Satellite L500              | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| ASUSTek       | G771JW                      | [b6c03572a0](https://linux-hardware.org/?probe=b6c03572a0) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| Dell          | Latitude 7320               | [63c6f252ab](https://linux-hardware.org/?probe=63c6f252ab) | May 30, 2022 |
| Acer          | Swift SF314-43              | [640f9226a1](https://linux-hardware.org/?probe=640f9226a1) | May 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| HP            | EliteBook 840 G4            | [2864dc6f0a](https://linux-hardware.org/?probe=2864dc6f0a) | May 19, 2022 |
| Dell          | Latitude 5430 Rugged        | [c32e65738e](https://linux-hardware.org/?probe=c32e65738e) | May 18, 2022 |
| Dell          | XPS 15 9560                 | [d1575ec23a](https://linux-hardware.org/?probe=d1575ec23a) | May 17, 2022 |
| HP            | 250 G3                      | [73dbcb9953](https://linux-hardware.org/?probe=73dbcb9953) | May 17, 2022 |
| HP            | 250 G3                      | [a12d6710cf](https://linux-hardware.org/?probe=a12d6710cf) | May 16, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| Notebook      | NB50TJ1_TK1                 | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [2591f59c80](https://linux-hardware.org/?probe=2591f59c80) | May 11, 2022 |
| Sony          | VPCF23S1E                   | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [b1d92dcb4e](https://linux-hardware.org/?probe=b1d92dcb4e) | May 10, 2022 |
| HP            | Notebook                    | [afe98a811e](https://linux-hardware.org/?probe=afe98a811e) | May 10, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [d2b0694da5](https://linux-hardware.org/?probe=d2b0694da5) | May 10, 2022 |
| Dell          | Latitude 7490               | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| Monster       | HUMA H4 V3.1                | [38372af132](https://linux-hardware.org/?probe=38372af132) | May 10, 2022 |
| Lenovo        | ThinkPad E555 20DH000WGE    | [75920152df](https://linux-hardware.org/?probe=75920152df) | May 10, 2022 |
| Clevo         | P7xxTM(1)                   | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| HP            | EliteBook 820 G3            | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| Clevo         | W55xEU                      | [7bdef594e1](https://linux-hardware.org/?probe=7bdef594e1) | May 09, 2022 |
| HP            | Pavilion dv6                | [165c15d078](https://linux-hardware.org/?probe=165c15d078) | May 09, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [cc53668d3f](https://linux-hardware.org/?probe=cc53668d3f) | May 09, 2022 |
| Dell          | XPS 15 9550                 | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| HP            | Pavilion 13 x360 PC         | [78b977ea42](https://linux-hardware.org/?probe=78b977ea42) | May 07, 2022 |
| Samsung       | 550XDA                      | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| Apple         | MacBookPro9,2               | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| ASUSTek       | X540LJ                      | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| HP            | EliteBook 2560p             | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| HP            | Laptop 17-ca0xxx            | [899a0e8999](https://linux-hardware.org/?probe=899a0e8999) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| HP            | Laptop 17-ca0xxx            | [10eb959775](https://linux-hardware.org/?probe=10eb959775) | Apr 30, 2022 |
| Fujitsu       | LIFEBOOK S762               | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| HUAWEI        | BOM-WXX9                    | [c07e06f794](https://linux-hardware.org/?probe=c07e06f794) | Apr 27, 2022 |
| Acer          | Aspire 3810TZ               | [cba19ea352](https://linux-hardware.org/?probe=cba19ea352) | Apr 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [593ee8ccf3](https://linux-hardware.org/?probe=593ee8ccf3) | Apr 27, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Acer          | Extensa 2519                | [ae1a90a282](https://linux-hardware.org/?probe=ae1a90a282) | Apr 21, 2022 |
| HP            | Notebook                    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [80572def69](https://linux-hardware.org/?probe=80572def69) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| Dell          | System Inspiron N7110       | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| Dell          | Precision 5530              | [3c4cc67cc4](https://linux-hardware.org/?probe=3c4cc67cc4) | Apr 13, 2022 |
| HP            | OMEN by Laptop              | [3775d7e528](https://linux-hardware.org/?probe=3775d7e528) | Apr 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| MSI           | Modern 15 A4M               | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | [8645c57fcc](https://linux-hardware.org/?probe=8645c57fcc) | Apr 09, 2022 |
| HP            | Laptop 17-ca0xxx            | [00d95f7a3a](https://linux-hardware.org/?probe=00d95f7a3a) | Apr 09, 2022 |
| Toshiba       | Satellite C55Dt-B           | [7e54067e6a](https://linux-hardware.org/?probe=7e54067e6a) | Apr 08, 2022 |
| Toshiba       | Satellite C55Dt-B           | [c40867ec67](https://linux-hardware.org/?probe=c40867ec67) | Apr 08, 2022 |
| HP            | Laptop 17-ca0xxx            | [9a2939bd71](https://linux-hardware.org/?probe=9a2939bd71) | Apr 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | [ff290845fe](https://linux-hardware.org/?probe=ff290845fe) | Apr 08, 2022 |
| ASUSTek       | N551JW                      | [3ddfbf37e2](https://linux-hardware.org/?probe=3ddfbf37e2) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| LG Electro... | C400-G.BC22P1               | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | [065554d2ad](https://linux-hardware.org/?probe=065554d2ad) | Apr 04, 2022 |
| Acer          | TravelMate P215-41-G2       | [4e35add210](https://linux-hardware.org/?probe=4e35add210) | Apr 04, 2022 |
| HUAWEI        | KPL-W0X                     | [c1419a6f3c](https://linux-hardware.org/?probe=c1419a6f3c) | Apr 03, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [ff7f2845b0](https://linux-hardware.org/?probe=ff7f2845b0) | Apr 01, 2022 |
| HUAWEI        | HVY-WXX9                    | [6eb9c66f7d](https://linux-hardware.org/?probe=6eb9c66f7d) | Mar 31, 2022 |
| Dell          | Precision 5540              | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [8392d5c3fe](https://linux-hardware.org/?probe=8392d5c3fe) | Mar 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| Acer          | Swift SF314-43              | [b632c4a0c5](https://linux-hardware.org/?probe=b632c4a0c5) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| Dell          | XPS 15 9560                 | [73734bbce5](https://linux-hardware.org/?probe=73734bbce5) | Mar 19, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Acer          | Aspire A315-41              | [704438d05e](https://linux-hardware.org/?probe=704438d05e) | Mar 13, 2022 |
| Acer          | Aspire A315-41              | [571547ee1d](https://linux-hardware.org/?probe=571547ee1d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | [7ce09d403d](https://linux-hardware.org/?probe=7ce09d403d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | [31b0bbe97f](https://linux-hardware.org/?probe=31b0bbe97f) | Mar 13, 2022 |
| Dell          | Latitude 7480               | [cbff798f89](https://linux-hardware.org/?probe=cbff798f89) | Mar 11, 2022 |
| Dell          | Latitude 7480               | [02e748e3ac](https://linux-hardware.org/?probe=02e748e3ac) | Mar 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c9b7431269](https://linux-hardware.org/?probe=c9b7431269) | Mar 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f118a17b6e](https://linux-hardware.org/?probe=f118a17b6e) | Mar 08, 2022 |
| Unknown       | Unknown                     | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Acer          | Swift SF314-59              | [d549055064](https://linux-hardware.org/?probe=d549055064) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| Dell          | XPS 15 9550                 | [f4a068f57c](https://linux-hardware.org/?probe=f4a068f57c) | Feb 27, 2022 |
| LG Electro... | C400-G.BC22P1               | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [f904e185fb](https://linux-hardware.org/?probe=f904e185fb) | Feb 25, 2022 |
| ASUSTek       | 1101HA                      | [f8f8968f19](https://linux-hardware.org/?probe=f8f8968f19) | Feb 22, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [100666467c](https://linux-hardware.org/?probe=100666467c) | Feb 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [450f779085](https://linux-hardware.org/?probe=450f779085) | Feb 20, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [24ec19a092](https://linux-hardware.org/?probe=24ec19a092) | Feb 17, 2022 |
| MSI           | CX600                       | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| LG Electro... | C400-G.BC22P1               | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Dell          | Latitude E6410              | [787eacd33c](https://linux-hardware.org/?probe=787eacd33c) | Feb 13, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [33abf3e568](https://linux-hardware.org/?probe=33abf3e568) | Feb 11, 2022 |
| Dell          | XPS 15 9510                 | [8c571a917d](https://linux-hardware.org/?probe=8c571a917d) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [34a6010fb2](https://linux-hardware.org/?probe=34a6010fb2) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Dell          | XPS 17 9710                 | [1b0a32e129](https://linux-hardware.org/?probe=1b0a32e129) | Feb 06, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [af586bb69e](https://linux-hardware.org/?probe=af586bb69e) | Feb 05, 2022 |
| Acer          | Nitro AN515-52              | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HUAWEI        | KPL-W0X                     | [af71ad30ed](https://linux-hardware.org/?probe=af71ad30ed) | Jan 30, 2022 |
| HP            | Laptop 17-ca0xxx            | [373b062fd0](https://linux-hardware.org/?probe=373b062fd0) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| HP            | Compaq 6830s                | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| MSI           | Pulse GL66 11UDK            | [06d5ba6ef3](https://linux-hardware.org/?probe=06d5ba6ef3) | Jan 26, 2022 |
| Getac         | V200-G2                     | [6d9b456d5f](https://linux-hardware.org/?probe=6d9b456d5f) | Jan 24, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c07dc3a8ee](https://linux-hardware.org/?probe=c07dc3a8ee) | Jan 24, 2022 |
| Acer          | Aspire F5-572G              | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| HUAWEI        | HKD-WXX                     | [170a3c500e](https://linux-hardware.org/?probe=170a3c500e) | Jan 21, 2022 |
| HUAWEI        | HKD-WXX                     | [a8eefb04f1](https://linux-hardware.org/?probe=a8eefb04f1) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d195d57aa4](https://linux-hardware.org/?probe=d195d57aa4) | Jan 21, 2022 |
| Sony          | VPCYB15AB                   | [1d7c8aa76a](https://linux-hardware.org/?probe=1d7c8aa76a) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| Acer          | Nitro AN515-45              | [a30f5fabcd](https://linux-hardware.org/?probe=a30f5fabcd) | Jan 18, 2022 |
| Toshiba       | Satellite C660D             | [99d2f2253d](https://linux-hardware.org/?probe=99d2f2253d) | Jan 11, 2022 |
| HP            | ENVY 15                     | [30b86e16bf](https://linux-hardware.org/?probe=30b86e16bf) | Jan 10, 2022 |
| Razer         | Blade 15 Base Model (Mid... | [af7d37f35c](https://linux-hardware.org/?probe=af7d37f35c) | Jan 10, 2022 |
| Dell          | Latitude XT2                | [65adc4cb22](https://linux-hardware.org/?probe=65adc4cb22) | Jan 09, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [4a33da1bc1](https://linux-hardware.org/?probe=4a33da1bc1) | Jan 06, 2022 |
| Notebook      | NL5xRU                      | [39b60e131a](https://linux-hardware.org/?probe=39b60e131a) | Jan 05, 2022 |
| Dell          | XPS 13 9343                 | [c7bf784225](https://linux-hardware.org/?probe=c7bf784225) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [896b348390](https://linux-hardware.org/?probe=896b348390) | Jan 03, 2022 |
| Toshiba       | AS 1301                     | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| TUXEDO        | Unknown                     | [6a29278e3f](https://linux-hardware.org/?probe=6a29278e3f) | Dec 31, 2021 |
| Fujitsu       | LIFEBOOK E746               | [86da0c348f](https://linux-hardware.org/?probe=86da0c348f) | Dec 30, 2021 |
| HP            | EliteBook 8460p             | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Dell          | XPS 15 9510                 | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Dell          | Studio 1737                 | [6b5362714f](https://linux-hardware.org/?probe=6b5362714f) | Dec 27, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [e62e9c50d0](https://linux-hardware.org/?probe=e62e9c50d0) | Dec 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [a1b975a4e1](https://linux-hardware.org/?probe=a1b975a4e1) | Dec 26, 2021 |
| Notebook      | NL5xRU                      | [f74478e98e](https://linux-hardware.org/?probe=f74478e98e) | Dec 25, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Avell High... | A62 LIV                     | [b2108dd133](https://linux-hardware.org/?probe=b2108dd133) | Dec 21, 2021 |
| Dell          | Inspiron N4030              | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| HP            | Pavilion dv6                | [bb01b911cd](https://linux-hardware.org/?probe=bb01b911cd) | Dec 17, 2021 |
| Google        | Pantheon                    | [8b1d8783ad](https://linux-hardware.org/?probe=8b1d8783ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | [0fca0b679f](https://linux-hardware.org/?probe=0fca0b679f) | Dec 16, 2021 |
| Acer          | Aspire E1-571               | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [452044c67e](https://linux-hardware.org/?probe=452044c67e) | Dec 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [4dc9e683af](https://linux-hardware.org/?probe=4dc9e683af) | Dec 15, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [696d4a24cd](https://linux-hardware.org/?probe=696d4a24cd) | Dec 13, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3d396a7f28](https://linux-hardware.org/?probe=3d396a7f28) | Dec 13, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | [68bef1611d](https://linux-hardware.org/?probe=68bef1611d) | Dec 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Dell          | Inspiron 15 3510            | [7d97420d98](https://linux-hardware.org/?probe=7d97420d98) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [176194b06f](https://linux-hardware.org/?probe=176194b06f) | Dec 10, 2021 |
| Google        | Kip                         | [0e5291c891](https://linux-hardware.org/?probe=0e5291c891) | Dec 09, 2021 |
| Google        | Kip                         | [9bbfc62162](https://linux-hardware.org/?probe=9bbfc62162) | Dec 09, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [543d2dfef7](https://linux-hardware.org/?probe=543d2dfef7) | Dec 07, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | [4d4c80773b](https://linux-hardware.org/?probe=4d4c80773b) | Dec 07, 2021 |
| Lenovo        | G500 20236                  | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| Acer          | Aspire A315-21              | [b6e4b7efdc](https://linux-hardware.org/?probe=b6e4b7efdc) | Dec 04, 2021 |
| Lenovo        | ThinkPad E495 20NE001GGE    | [31e9125d85](https://linux-hardware.org/?probe=31e9125d85) | Dec 03, 2021 |
| Lenovo        | ThinkPad E495 20NE001GGE    | [3b230e73b3](https://linux-hardware.org/?probe=3b230e73b3) | Dec 03, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7b1d555cc3](https://linux-hardware.org/?probe=7b1d555cc3) | Dec 03, 2021 |
| Lenovo        | B41-80 80LG                 | [96e84134f0](https://linux-hardware.org/?probe=96e84134f0) | Dec 03, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Dell          | Vostro 5471                 | [3da13c5e1b](https://linux-hardware.org/?probe=3da13c5e1b) | Nov 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [8e84498214](https://linux-hardware.org/?probe=8e84498214) | Nov 30, 2021 |
| HP            | OMEN by Laptop              | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Toshiba       | Satellite C660              | [e4f4713ac2](https://linux-hardware.org/?probe=e4f4713ac2) | Nov 29, 2021 |
| Apple         | MacBookPro9,2               | [65ba69012d](https://linux-hardware.org/?probe=65ba69012d) | Nov 28, 2021 |
| HUAWEI        | KLVL-WXX9                   | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | [403ada1042](https://linux-hardware.org/?probe=403ada1042) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | [b58c73a493](https://linux-hardware.org/?probe=b58c73a493) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [27a4935e65](https://linux-hardware.org/?probe=27a4935e65) | Nov 26, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Acer          | Aspire E1-772G              | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| Dell          | Precision M4800             | [c81b76f119](https://linux-hardware.org/?probe=c81b76f119) | Nov 25, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | [4eb53d4335](https://linux-hardware.org/?probe=4eb53d4335) | Nov 25, 2021 |
| Toshiba       | Satellite C660              | [995eaf8345](https://linux-hardware.org/?probe=995eaf8345) | Nov 25, 2021 |
| HP            | EliteBook 8460p             | [8278dcbd86](https://linux-hardware.org/?probe=8278dcbd86) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [933eda02dc](https://linux-hardware.org/?probe=933eda02dc) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [4f96b5ad58](https://linux-hardware.org/?probe=4f96b5ad58) | Nov 19, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [6d345c2500](https://linux-hardware.org/?probe=6d345c2500) | Nov 18, 2021 |
| Lenovo        | ThinkPad E495 20NES01600    | [aacc57f134](https://linux-hardware.org/?probe=aacc57f134) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E782               | [f2e77fa439](https://linux-hardware.org/?probe=f2e77fa439) | Nov 17, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [ce05c5de33](https://linux-hardware.org/?probe=ce05c5de33) | Nov 15, 2021 |
| HP            | Pavilion dv6                | [30c1df8961](https://linux-hardware.org/?probe=30c1df8961) | Nov 13, 2021 |
| Samsung       | 550XDA                      | [69fe372895](https://linux-hardware.org/?probe=69fe372895) | Nov 12, 2021 |
| Samsung       | 550XDA                      | [61a4dbe6b6](https://linux-hardware.org/?probe=61a4dbe6b6) | Nov 12, 2021 |
| Dell          | Latitude E5440              | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Acer          | Aspire E1-772G              | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [be3123eae1](https://linux-hardware.org/?probe=be3123eae1) | Nov 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cf717529eb](https://linux-hardware.org/?probe=cf717529eb) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell          | G3 3590                     | [aa237dfc61](https://linux-hardware.org/?probe=aa237dfc61) | Nov 06, 2021 |
| Acer          | Aspire 5820TG               | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Dell          | Precision 7530              | [6a1961e13d](https://linux-hardware.org/?probe=6a1961e13d) | Nov 03, 2021 |
| Lenovo        | ThinkPad Edge E430 3254T... | [f9fbde199a](https://linux-hardware.org/?probe=f9fbde199a) | Nov 02, 2021 |
| HP            | ZBook 14 G2                 | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| ASUSTek       | X751LK                      | [b2cda34b7e](https://linux-hardware.org/?probe=b2cda34b7e) | Oct 30, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [65eac6abc6](https://linux-hardware.org/?probe=65eac6abc6) | Oct 27, 2021 |
| Lenovo        | Yoga 710-11IKB 80V6         | [2b89909a49](https://linux-hardware.org/?probe=2b89909a49) | Oct 25, 2021 |
| Acer          | Aspire E1-772G              | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer          | Nitro AN515-54              | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| Dell          | Latitude 7420               | [a4ff2480e6](https://linux-hardware.org/?probe=a4ff2480e6) | Oct 22, 2021 |
| TUXEDO        | Aura 15 Gen1                | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| HP            | ProBook 650 G1              | [20be8bd8e7](https://linux-hardware.org/?probe=20be8bd8e7) | Oct 21, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Acer          | Swift SF314-43              | [ef2da9ecca](https://linux-hardware.org/?probe=ef2da9ecca) | Oct 21, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [d111902eac](https://linux-hardware.org/?probe=d111902eac) | Oct 18, 2021 |
| Medion        | E6436 MD61150               | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion        | E6436 MD61150               | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | [d1cdbd537e](https://linux-hardware.org/?probe=d1cdbd537e) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [d3fdfb0745](https://linux-hardware.org/?probe=d3fdfb0745) | Oct 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| ASUSTek       | X550CL                      | [15e808f714](https://linux-hardware.org/?probe=15e808f714) | Oct 10, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [4bb69f9fcc](https://linux-hardware.org/?probe=4bb69f9fcc) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | [778b409af2](https://linux-hardware.org/?probe=778b409af2) | Oct 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [eb4d7c93c0](https://linux-hardware.org/?probe=eb4d7c93c0) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [4206d52561](https://linux-hardware.org/?probe=4206d52561) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8e94483caf](https://linux-hardware.org/?probe=8e94483caf) | Oct 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Acer          | Nitro AN515-45              | [c439170645](https://linux-hardware.org/?probe=c439170645) | Oct 05, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [a9f8d1f512](https://linux-hardware.org/?probe=a9f8d1f512) | Oct 05, 2021 |
| HP            | G61                         | [98ef6e48b5](https://linux-hardware.org/?probe=98ef6e48b5) | Oct 03, 2021 |
| Google        | Pantheon                    | [72ded95fab](https://linux-hardware.org/?probe=72ded95fab) | Oct 02, 2021 |
| HUAWEI        | HVY-WXX9                    | [f0b874d4f2](https://linux-hardware.org/?probe=f0b874d4f2) | Oct 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [eabcfa676f](https://linux-hardware.org/?probe=eabcfa676f) | Oct 02, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| HP            | EliteBook Folio 9470m       | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| MSI           | GP63 Leopard 8RD            | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| HUAWEI        | KPL-W0X                     | [7024087dbd](https://linux-hardware.org/?probe=7024087dbd) | Sep 26, 2021 |
| HUAWEI        | KPL-W0X                     | [b1c787f5e6](https://linux-hardware.org/?probe=b1c787f5e6) | Sep 26, 2021 |
| Dell          | XPS 13 9310                 | [39d644c56a](https://linux-hardware.org/?probe=39d644c56a) | Sep 26, 2021 |
| Lenovo        | ThinkPad L420 7827AW9       | [6c7308609b](https://linux-hardware.org/?probe=6c7308609b) | Sep 26, 2021 |
| Dell          | Inspiron N4010              | [82ad91793d](https://linux-hardware.org/?probe=82ad91793d) | Sep 25, 2021 |
| Timi          | A35S                        | [c10b3fac0b](https://linux-hardware.org/?probe=c10b3fac0b) | Sep 22, 2021 |
| Lenovo        | Yoga 710-11IKB 80V6         | [59490b03a0](https://linux-hardware.org/?probe=59490b03a0) | Sep 21, 2021 |
| Dell          | Precision M6700             | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [9e88464633](https://linux-hardware.org/?probe=9e88464633) | Sep 20, 2021 |
| Google        | Pantheon                    | [eaa5a17c4b](https://linux-hardware.org/?probe=eaa5a17c4b) | Sep 19, 2021 |
| Medion        | S15449                      | [8f1110e14a](https://linux-hardware.org/?probe=8f1110e14a) | Sep 18, 2021 |
| HP            | ZBook 17                    | [df2e227740](https://linux-hardware.org/?probe=df2e227740) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [385fd35a7e](https://linux-hardware.org/?probe=385fd35a7e) | Sep 16, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | [47d1d04589](https://linux-hardware.org/?probe=47d1d04589) | Sep 16, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | [5f33450a0d](https://linux-hardware.org/?probe=5f33450a0d) | Sep 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [66385493ae](https://linux-hardware.org/?probe=66385493ae) | Sep 15, 2021 |
| MSI           | Modern 15 A4M               | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| Dell          | Inspiron 3521               | [1e2e03c85c](https://linux-hardware.org/?probe=1e2e03c85c) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| Medion        | S15449                      | [03b29809eb](https://linux-hardware.org/?probe=03b29809eb) | Sep 11, 2021 |
| MSI           | GE72 7RD                    | [d02699b3f9](https://linux-hardware.org/?probe=d02699b3f9) | Sep 11, 2021 |
| Dell          | Precision M3800             | [5dba4d3bce](https://linux-hardware.org/?probe=5dba4d3bce) | Sep 07, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [9a46145cf4](https://linux-hardware.org/?probe=9a46145cf4) | Sep 06, 2021 |
| Lenovo        | ThinkPad X270 20HN0016GE    | [cecb5eb453](https://linux-hardware.org/?probe=cecb5eb453) | Sep 05, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [3eb77262b0](https://linux-hardware.org/?probe=3eb77262b0) | Sep 04, 2021 |
| Acer          | Aspire A517-52G             | [2d3edcffdd](https://linux-hardware.org/?probe=2d3edcffdd) | Sep 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [82785cc5a8](https://linux-hardware.org/?probe=82785cc5a8) | Sep 03, 2021 |
| Dell          | Inspiron 3593               | [5f9f37c33b](https://linux-hardware.org/?probe=5f9f37c33b) | Aug 30, 2021 |
| Medion        | S15449                      | [a0c8d15a30](https://linux-hardware.org/?probe=a0c8d15a30) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung       | 600B4B/600B5B               | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| Dell          | Precision M6700             | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo        | V330-15IKB 81AX             | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62c96ffa5b](https://linux-hardware.org/?probe=62c96ffa5b) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [516b9ff2ed](https://linux-hardware.org/?probe=516b9ff2ed) | Aug 25, 2021 |
| Lenovo        | G500 20236                  | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell          | Latitude 5480               | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [e59555689c](https://linux-hardware.org/?probe=e59555689c) | Aug 23, 2021 |
| Medion        | S15449                      | [adf11d6583](https://linux-hardware.org/?probe=adf11d6583) | Aug 22, 2021 |
| Lenovo        | ThinkPad L420 7827AW9       | [d18b84f4e1](https://linux-hardware.org/?probe=d18b84f4e1) | Aug 22, 2021 |
| Lenovo        | ThinkPad L420 7827AW9       | [7e1de8f6ba](https://linux-hardware.org/?probe=7e1de8f6ba) | Aug 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | [90446b95e6](https://linux-hardware.org/?probe=90446b95e6) | Aug 21, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d79e5a84](https://linux-hardware.org/?probe=18d79e5a84) | Aug 21, 2021 |
| Dell          | Latitude 5480               | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 8895W9U        | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [4e946ccb36](https://linux-hardware.org/?probe=4e946ccb36) | Aug 15, 2021 |
| HP            | ProBook 450 G6              | [c206f3c985](https://linux-hardware.org/?probe=c206f3c985) | Aug 13, 2021 |
| Dell          | Inspiron 3521               | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell          | Inspiron 3521               | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell          | Inspiron 7460               | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung       | 600B4B/600B5B               | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [77e5c1027c](https://linux-hardware.org/?probe=77e5c1027c) | Aug 06, 2021 |
| Dell          | Inspiron 5770               | [0061c42395](https://linux-hardware.org/?probe=0061c42395) | Aug 02, 2021 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [25a6865386](https://linux-hardware.org/?probe=25a6865386) | Aug 01, 2021 |
| Lenovo        | ThinkPad SL510 2847CSG      | [505d87d58a](https://linux-hardware.org/?probe=505d87d58a) | Jul 30, 2021 |
| Lenovo        | ThinkPad SL510 2847CSG      | [09c0faf429](https://linux-hardware.org/?probe=09c0faf429) | Jul 30, 2021 |
| HP            | ZBook 15 G6                 | [617fd327a3](https://linux-hardware.org/?probe=617fd327a3) | Jul 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3c2fc847b2](https://linux-hardware.org/?probe=3c2fc847b2) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [818166936a](https://linux-hardware.org/?probe=818166936a) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2640930f28](https://linux-hardware.org/?probe=2640930f28) | Jul 23, 2021 |
| HP            | Stream Notebook PC 11       | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| Dell          | Inspiron 5570               | [2803a67fa3](https://linux-hardware.org/?probe=2803a67fa3) | Jul 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [61ac3fb728](https://linux-hardware.org/?probe=61ac3fb728) | Jul 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [52642a99c5](https://linux-hardware.org/?probe=52642a99c5) | Jul 19, 2021 |
| Dell          | Inspiron 3442               | [8814bd2240](https://linux-hardware.org/?probe=8814bd2240) | Jul 18, 2021 |
| Avell High... | A62 LIV                     | [a1398c199a](https://linux-hardware.org/?probe=a1398c199a) | Jul 17, 2021 |
| Avell High... | A62 LIV                     | [2e01a9aa5b](https://linux-hardware.org/?probe=2e01a9aa5b) | Jul 17, 2021 |
| Dell          | G3 3590                     | [5526842a03](https://linux-hardware.org/?probe=5526842a03) | Jul 16, 2021 |
| Toshiba       | Satellite L850              | [1697c7eaf6](https://linux-hardware.org/?probe=1697c7eaf6) | Jul 15, 2021 |
| Intel Clie... | A60 MUV                     | [f2c8c49a38](https://linux-hardware.org/?probe=f2c8c49a38) | Jul 11, 2021 |
| Gateway       | NE56R                       | [94fe19c4ee](https://linux-hardware.org/?probe=94fe19c4ee) | Jul 10, 2021 |
| Lenovo        | Yoga 710-11IKB 80V6         | [8b4e2829d2](https://linux-hardware.org/?probe=8b4e2829d2) | Jul 10, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu       | LIFEBOOK E754               | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| MSI           | Prestige 14 A11SCS          | [8c1215643e](https://linux-hardware.org/?probe=8c1215643e) | Jul 07, 2021 |
| MSI           | Prestige 14 A11SCS          | [8f329afe05](https://linux-hardware.org/?probe=8f329afe05) | Jul 07, 2021 |
| Clevo         | P7xxTM(1)                   | [98eeef735f](https://linux-hardware.org/?probe=98eeef735f) | Jul 07, 2021 |
| Sony          | VPCP11S1R                   | [185fd7ceef](https://linux-hardware.org/?probe=185fd7ceef) | Jul 05, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c19ad895a0](https://linux-hardware.org/?probe=c19ad895a0) | Jul 02, 2021 |
| Gateway       | NE56R                       | [06b945a761](https://linux-hardware.org/?probe=06b945a761) | Jul 02, 2021 |
| Lenovo        | ThinkPad T580 20L9S0D100    | [e7f9397916](https://linux-hardware.org/?probe=e7f9397916) | Jul 02, 2021 |
| ASUSTek       | G771JW                      | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| HP            | EliteBook 840 G3            | [8db2c9c6d8](https://linux-hardware.org/?probe=8db2c9c6d8) | Jun 18, 2021 |
| HP            | ZBook Studio G4             | [231843ea67](https://linux-hardware.org/?probe=231843ea67) | Jun 17, 2021 |
| HP            | ZBook Studio G4             | [4e20cbff63](https://linux-hardware.org/?probe=4e20cbff63) | Jun 17, 2021 |
| HP            | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [bbedefdee0](https://linux-hardware.org/?probe=bbedefdee0) | Jun 16, 2021 |
| Dell          | XPS 17 9700                 | [2773858bd8](https://linux-hardware.org/?probe=2773858bd8) | Jun 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [9674952e07](https://linux-hardware.org/?probe=9674952e07) | Jun 11, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [b39699b009](https://linux-hardware.org/?probe=b39699b009) | Jun 11, 2021 |
| HP            | ZBook Studio G4             | [3eb6cb2692](https://linux-hardware.org/?probe=3eb6cb2692) | Jun 10, 2021 |
| HP            | ProBook 450 G6              | [18f1d91786](https://linux-hardware.org/?probe=18f1d91786) | Jun 09, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [396457505a](https://linux-hardware.org/?probe=396457505a) | Jun 09, 2021 |
| Fujitsu Si... | AMILO Li 1718               | [28837b4881](https://linux-hardware.org/?probe=28837b4881) | Jun 08, 2021 |
| Unknown       | Unknown                     | [3c6ccf834d](https://linux-hardware.org/?probe=3c6ccf834d) | Jun 08, 2021 |
| Dell          | XPS 13 9310                 | [5456739d8f](https://linux-hardware.org/?probe=5456739d8f) | Jun 08, 2021 |
| Dell          | Studio 1747                 | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Sony          | VPCSB15GB                   | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| MSI           | CR500                       | [76d2d77034](https://linux-hardware.org/?probe=76d2d77034) | Jun 03, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [6b168c2c19](https://linux-hardware.org/?probe=6b168c2c19) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [c1492eba42](https://linux-hardware.org/?probe=c1492eba42) | Jun 02, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7cfb53e5f2](https://linux-hardware.org/?probe=7cfb53e5f2) | Jun 01, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [13d155653f](https://linux-hardware.org/?probe=13d155653f) | May 31, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [bba3bc97b7](https://linux-hardware.org/?probe=bba3bc97b7) | May 31, 2021 |
| MSI           | CR500                       | [b1d00d1444](https://linux-hardware.org/?probe=b1d00d1444) | May 30, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 713       | 66.82%  |
| openSUSE Leap-15.2           | 101       | 9.47%   |
| openSUSE Leap-15.4           | 64        | 6%      |
| openSUSE Leap-15.3           | 59        | 5.53%   |
| openSUSE Leap-15.1           | 59        | 5.53%   |
| openSUSE Microos-XXXXXXXX    | 23        | 2.16%   |
| openSUSE Leap-15.0           | 21        | 1.97%   |
| openSUSE Leap-15.5           | 17        | 1.59%   |
| openSUSE Leap-42.3           | 2         | 0.19%   |
| openSUSE Leap-42.2           | 2         | 0.19%   |
| openSUSE 13.2                | 2         | 0.19%   |
| openSUSE                     | 2         | 0.19%   |
| openSUSE 42.3                | 1         | 0.09%   |
| openSUSE 13.1                | 1         | 0.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| openSUSE | 1044      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.17.4-1-default             | 26        | 2.12%   |
| 4.12.14-lp151.28.44-default  | 24        | 1.96%   |
| 6.2.12-1-default             | 19        | 1.55%   |
| 6.0.8-1-default              | 18        | 1.47%   |
| 6.3.2-1-default              | 16        | 1.31%   |
| 5.19.2-1-default             | 15        | 1.23%   |
| 4.18.15-1-default            | 15        | 1.23%   |
| 6.2.9-1-default              | 14        | 1.14%   |
| 6.1.8-1-default              | 14        | 1.14%   |
| 6.1.12-1-default             | 14        | 1.14%   |
| 5.6.0-1-default              | 13        | 1.06%   |
| 5.3.18-lp152.57-default      | 13        | 1.06%   |
| 6.0.12-1-default             | 12        | 0.98%   |
| 5.17.1-1-default             | 12        | 0.98%   |
| 5.14.21-150400.22-default    | 12        | 0.98%   |
| 6.3.7-1-default              | 11        | 0.9%    |
| 6.3.4-1-default              | 11        | 0.9%    |
| 6.2.10-1-default             | 11        | 0.9%    |
| 6.0.10-1-default             | 11        | 0.9%    |
| 5.8.4-1-default              | 11        | 0.9%    |
| 5.14.21-150500.53-default    | 11        | 0.9%    |
| 6.3.1-1-default              | 10        | 0.82%   |
| 6.2.6-1-default              | 10        | 0.82%   |
| 6.1.10-1-default             | 10        | 0.82%   |
| 6.1.1-1-default              | 10        | 0.82%   |
| 6.0.3-1-default              | 10        | 0.82%   |
| 5.18.6-1-default             | 10        | 0.82%   |
| 5.3.18-lp152.63-default      | 9         | 0.74%   |
| 5.3.18-lp152.50-default      | 9         | 0.74%   |
| 5.14.21-150400.24.21-default | 9         | 0.74%   |
| 5.11.6-1-default             | 9         | 0.74%   |
| 6.0.6-1-default              | 8         | 0.65%   |
| 5.6.12-1-default             | 8         | 0.65%   |
| 5.3.18-lp152.47-default      | 8         | 0.65%   |
| 5.3.18-59.27-default         | 8         | 0.65%   |
| 5.17.9-1-default             | 8         | 0.65%   |
| 5.14.21-150400.24.38-default | 8         | 0.65%   |
| 5.10.7-1-default             | 8         | 0.65%   |
| 6.2.1-1-default              | 7         | 0.57%   |
| 5.8.7-1-default              | 7         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3.18  | 142       | 11.93%  |
| 5.14.21 | 79        | 6.64%   |
| 4.12.14 | 75        | 6.3%    |
| 5.17.4  | 26        | 2.18%   |
| 6.2.12  | 19        | 1.6%    |
| 6.0.8   | 18        | 1.51%   |
| 6.3.2   | 16        | 1.34%   |
| 6.3.1   | 16        | 1.34%   |
| 5.19.2  | 15        | 1.26%   |
| 4.18.15 | 15        | 1.26%   |
| 6.2.9   | 14        | 1.18%   |
| 6.1.8   | 14        | 1.18%   |
| 6.1.12  | 14        | 1.18%   |
| 5.6.0   | 14        | 1.18%   |
| 5.17.1  | 13        | 1.09%   |
| 6.1.10  | 12        | 1.01%   |
| 6.0.12  | 12        | 1.01%   |
| 5.8.4   | 12        | 1.01%   |
| 6.3.7   | 11        | 0.92%   |
| 6.3.4   | 11        | 0.92%   |
| 6.2.10  | 11        | 0.92%   |
| 6.0.10  | 11        | 0.92%   |
| 5.14.14 | 11        | 0.92%   |
| 6.2.6   | 10        | 0.84%   |
| 6.1.1   | 10        | 0.84%   |
| 6.0.3   | 10        | 0.84%   |
| 5.18.6  | 10        | 0.84%   |
| 5.14.6  | 10        | 0.84%   |
| 5.11.6  | 10        | 0.84%   |
| 5.12.4  | 9         | 0.76%   |
| 5.10.7  | 9         | 0.76%   |
| 6.0.6   | 8         | 0.67%   |
| 5.6.12  | 8         | 0.67%   |
| 5.17.9  | 8         | 0.67%   |
| 6.2.1   | 7         | 0.59%   |
| 5.8.7   | 7         | 0.59%   |
| 5.16.11 | 7         | 0.59%   |
| 5.15.5  | 7         | 0.59%   |
| 5.15.12 | 7         | 0.59%   |
| 5.14.2  | 7         | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3     | 149       | 12.9%   |
| 5.14    | 122       | 10.56%  |
| 6.0     | 78        | 6.75%   |
| 4.12    | 75        | 6.49%   |
| 6.1     | 74        | 6.41%   |
| 6.2     | 71        | 6.15%   |
| 6.3     | 67        | 5.8%    |
| 5.17    | 57        | 4.94%   |
| 5.16    | 41        | 3.55%   |
| 5.8     | 38        | 3.29%   |
| 5.6     | 37        | 3.2%    |
| 5.19    | 35        | 3.03%   |
| 5.18    | 35        | 3.03%   |
| 5.15    | 35        | 3.03%   |
| 5.10    | 35        | 3.03%   |
| 5.11    | 30        | 2.6%    |
| 5.12    | 29        | 2.51%   |
| 5.13    | 23        | 1.99%   |
| 5.5     | 21        | 1.82%   |
| 5.9     | 19        | 1.65%   |
| 4.18    | 19        | 1.65%   |
| 5.7     | 17        | 1.47%   |
| 5.4     | 11        | 0.95%   |
| 5.0     | 8         | 0.69%   |
| 4.4     | 7         | 0.61%   |
| 4.17    | 6         | 0.52%   |
| 5.2     | 5         | 0.43%   |
| 5.1     | 4         | 0.35%   |
| 4.3     | 2         | 0.17%   |
| 3.16    | 2         | 0.17%   |
| 4.20    | 1         | 0.09%   |
| 4.16    | 1         | 0.09%   |
| 3.12    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1033      | 98.85%  |
| i686    | 11        | 1.05%   |
| aarch64 | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KDE5          | 604       | 56.29%  |
| GNOME         | 198       | 18.45%  |
| KDE           | 97        | 9.04%   |
| Unknown       | 60        | 5.59%   |
| XFCE          | 57        | 5.31%   |
| MATE          | 11        | 1.03%   |
| X-Cinnamon    | 8         | 0.75%   |
| Cinnamon      | 8         | 0.75%   |
| KDE4          | 6         | 0.56%   |
| LXQt          | 5         | 0.47%   |
| LXDE          | 4         | 0.37%   |
| ICEWM         | 2         | 0.19%   |
| i3            | 2         | 0.19%   |
| GNOME Classic | 2         | 0.19%   |
| Deepin        | 2         | 0.19%   |
| sway          | 1         | 0.09%   |
| plasma5       | 1         | 0.09%   |
| Hyprland      | 1         | 0.09%   |
| Herbstluftwm  | 1         | 0.09%   |
| default       | 1         | 0.09%   |
| custom        | 1         | 0.09%   |
| Budgie        | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 845       | 78.75%  |
| Wayland     | 206       | 19.2%   |
| Unknown     | 11        | 1.03%   |
| Tty         | 10        | 0.93%   |
| Unspecified | 1         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 413       | 38.42%  |
| LightDM | 308       | 28.65%  |
| SDDM    | 278       | 25.86%  |
| XDM     | 65        | 6.05%   |
| GDM     | 10        | 0.93%   |
| GREETD  | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 392       | 36.67%  |
| de_DE   | 121       | 11.32%  |
| POSIX   | 91        | 8.51%   |
| Unknown | 90        | 8.42%   |
| en_GB   | 68        | 6.36%   |
| pt_BR   | 47        | 4.4%    |
| ru_RU   | 45        | 4.21%   |
| es_ES   | 39        | 3.65%   |
| it_IT   | 31        | 2.9%    |
| fr_FR   | 27        | 2.53%   |
| pl_PL   | 16        | 1.5%    |
| zh_CN   | 10        | 0.94%   |
| nl_NL   | 10        | 0.94%   |
| cs_CZ   | 9         | 0.84%   |
| pt_PT   | 8         | 0.75%   |
| hu_HU   | 7         | 0.65%   |
| en_IN   | 5         | 0.47%   |
| fi_FI   | 4         | 0.37%   |
| C       | 4         | 0.37%   |
| bg_BG   | 4         | 0.37%   |
| es_MX   | 3         | 0.28%   |
| en_IE   | 3         | 0.28%   |
| sv_SE   | 2         | 0.19%   |
| nn_NO   | 2         | 0.19%   |
| ja_JP   | 2         | 0.19%   |
| es_AR   | 2         | 0.19%   |
| en_PH   | 2         | 0.19%   |
| en_DE   | 2         | 0.19%   |
| en_AU   | 2         | 0.19%   |
| de_AT   | 2         | 0.19%   |
| vi_VN   | 1         | 0.09%   |
| tr_TR   | 1         | 0.09%   |
| szl_PL  | 1         | 0.09%   |
| sk_SK   | 1         | 0.09%   |
| ru_UA   | 1         | 0.09%   |
| ro_RO   | 1         | 0.09%   |
| nb_NO   | 1         | 0.09%   |
| ko_KR   | 1         | 0.09%   |
| hr_HR   | 1         | 0.09%   |
| es_VE   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 755       | 71.63%  |
| BIOS | 299       | 28.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Btrfs    | 764       | 72.49%  |
| Ext4     | 204       | 19.35%  |
| Xfs      | 43        | 4.08%   |
| Unknown  | 27        | 2.56%   |
| Overlay  | 12        | 1.14%   |
| Reiserfs | 1         | 0.09%   |
| F2fs     | 1         | 0.09%   |
| Ext3     | 1         | 0.09%   |
| Ext2     | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 591       | 55.7%   |
| Unknown | 380       | 35.82%  |
| MBR     | 90        | 8.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 940       | 88.68%  |
| Yes       | 120       | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 785       | 74.27%  |
| Yes       | 272       | 25.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 261       | 25%     |
| Hewlett-Packard        | 199       | 19.06%  |
| Dell                   | 160       | 15.33%  |
| ASUSTek Computer       | 101       | 9.67%   |
| Acer                   | 76        | 7.28%   |
| MSI                    | 31        | 2.97%   |
| Apple                  | 31        | 2.97%   |
| Toshiba                | 21        | 2.01%   |
| TUXEDO                 | 18        | 1.72%   |
| HUAWEI                 | 16        | 1.53%   |
| Fujitsu                | 14        | 1.34%   |
| Sony                   | 13        | 1.25%   |
| Samsung Electronics    | 11        | 1.05%   |
| Notebook               | 8         | 0.77%   |
| Fujitsu Siemens        | 5         | 0.48%   |
| Unknown                | 5         | 0.48%   |
| Google                 | 4         | 0.38%   |
| Alienware              | 4         | 0.38%   |
| Timi                   | 3         | 0.29%   |
| SLIMBOOK               | 3         | 0.29%   |
| Schenker               | 3         | 0.29%   |
| Razer                  | 3         | 0.29%   |
| Medion                 | 3         | 0.29%   |
| LG Electronics         | 3         | 0.29%   |
| Gigabyte Technology    | 3         | 0.29%   |
| Gateway                | 3         | 0.29%   |
| Clevo                  | 3         | 0.29%   |
| Avell High Performance | 3         | 0.29%   |
| Semp Toshiba           | 2         | 0.19%   |
| Purism                 | 2         | 0.19%   |
| Positivo               | 2         | 0.19%   |
| Multilaser             | 2         | 0.19%   |
| Maibenben              | 2         | 0.19%   |
| Jumper                 | 2         | 0.19%   |
| Intel Client Systems   | 2         | 0.19%   |
| Intel                  | 2         | 0.19%   |
| Getac                  | 2         | 0.19%   |
| Wortmann AG            | 1         | 0.1%    |
| VIT                    | 1         | 0.1%    |
| Valve                  | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 11        | 1.05%   |
| HP Notebook                           | 8         | 0.77%   |
| Dell Precision 5530                   | 6         | 0.57%   |
| Apple MacBookPro9,2                   | 6         | 0.57%   |
| HP Pavilion dv7                       | 5         | 0.48%   |
| HP Pavilion dv6                       | 5         | 0.48%   |
| HP Laptop 17-ca0xxx                   | 5         | 0.48%   |
| Dell Latitude 7490                    | 5         | 0.48%   |
| TUXEDO Pulse 15 Gen1                  | 4         | 0.38%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 4         | 0.38%   |
| Lenovo G50-45 80E3                    | 4         | 0.38%   |
| HP Pavilion g6                        | 4         | 0.38%   |
| HP OMEN Laptop 15-en0xxx              | 4         | 0.38%   |
| Dell XPS 15 9560                      | 4         | 0.38%   |
| Dell Latitude E7470                   | 4         | 0.38%   |
| Acer Swift SF314-43                   | 4         | 0.38%   |
| Samsung 550XDA                        | 3         | 0.29%   |
| Lenovo ThinkBook 14 G3 ACL 21A2       | 3         | 0.29%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 3         | 0.29%   |
| HUAWEI BOHK-WAX9X                     | 3         | 0.29%   |
| HP Laptop 15-bs0xx                    | 3         | 0.29%   |
| HP EliteBook 840 G5                   | 3         | 0.29%   |
| HP Compaq Presario CQ40               | 3         | 0.29%   |
| Dell XPS 15 9550                      | 3         | 0.29%   |
| Dell XPS 15 9510                      | 3         | 0.29%   |
| Dell Latitude E6430                   | 3         | 0.29%   |
| Dell Inspiron 5584                    | 3         | 0.29%   |
| Dell Inspiron 3593                    | 3         | 0.29%   |
| Dell G3 3579                          | 3         | 0.29%   |
| Apple MacBookPro8,1                   | 3         | 0.29%   |
| Acer Predator PH315-52                | 3         | 0.29%   |
| Acer Aspire V3-571G                   | 3         | 0.29%   |
| SLIMBOOK PROX-AMD5                    | 2         | 0.19%   |
| MSI Modern 14 B5M                     | 2         | 0.19%   |
| Lenovo ThinkPad X270 20HN0016GE       | 2         | 0.19%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 2         | 0.19%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG      | 2         | 0.19%   |
| Lenovo IdeaPad S145-15API 81V7        | 2         | 0.19%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 2         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 2         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 153       | 14.66%  |
| Dell Latitude       | 54        | 5.17%   |
| Lenovo IdeaPad      | 51        | 4.89%   |
| Acer Aspire         | 51        | 4.89%   |
| Dell Inspiron       | 43        | 4.12%   |
| HP EliteBook        | 41        | 3.93%   |
| HP Pavilion         | 39        | 3.74%   |
| HP Laptop           | 27        | 2.59%   |
| ASUS VivoBook       | 26        | 2.49%   |
| Dell XPS            | 24        | 2.3%    |
| Toshiba Satellite   | 19        | 1.82%   |
| HP ProBook          | 19        | 1.82%   |
| HP ZBook            | 18        | 1.72%   |
| Dell Precision      | 17        | 1.63%   |
| Fujitsu LIFEBOOK    | 13        | 1.25%   |
| ASUS ROG            | 12        | 1.15%   |
| Unknown             | 11        | 1.05%   |
| HP OMEN             | 10        | 0.96%   |
| Lenovo Yoga         | 9         | 0.86%   |
| HP ENVY             | 9         | 0.86%   |
| HP Compaq           | 9         | 0.86%   |
| ASUS ZenBook        | 9         | 0.86%   |
| Acer Swift          | 9         | 0.86%   |
| Lenovo ThinkBook    | 8         | 0.77%   |
| HP Notebook         | 8         | 0.77%   |
| Dell Vostro         | 8         | 0.77%   |
| ASUS ASUS           | 8         | 0.77%   |
| Lenovo Legion       | 7         | 0.67%   |
| ASUS TUF            | 7         | 0.67%   |
| Acer Nitro          | 7         | 0.67%   |
| Dell G3             | 6         | 0.57%   |
| Apple MacBookPro9   | 6         | 0.57%   |
| TUXEDO InfinityBook | 5         | 0.48%   |
| TUXEDO Pulse        | 4         | 0.38%   |
| MSI Modern          | 4         | 0.38%   |
| Lenovo G50-45       | 4         | 0.38%   |
| Apple MacBookPro8   | 4         | 0.38%   |
| Samsung 550XDA      | 3         | 0.29%   |
| Razer Blade         | 3         | 0.29%   |
| HUAWEI BOHK-WAX9X   | 3         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 125       | 11.97%  |
| 2020 | 124       | 11.88%  |
| 2019 | 104       | 9.96%   |
| 2018 | 95        | 9.1%    |
| 2017 | 81        | 7.76%   |
| 2012 | 68        | 6.51%   |
| 2015 | 67        | 6.42%   |
| 2013 | 60        | 5.75%   |
| 2022 | 53        | 5.08%   |
| 2014 | 53        | 5.08%   |
| 2016 | 52        | 4.98%   |
| 2011 | 50        | 4.79%   |
| 2010 | 39        | 3.74%   |
| 2008 | 31        | 2.97%   |
| 2009 | 24        | 2.3%    |
| 2007 | 9         | 0.86%   |
| 2023 | 5         | 0.48%   |
| 2005 | 2         | 0.19%   |
| 2006 | 1         | 0.1%    |
| 2000 | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1044      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 834       | 78.38%  |
| Enabled  | 230       | 21.62%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1037      | 99.33%  |
| Yes  | 7         | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 315       | 29.89%  |
| 16.01-24.0  | 224       | 21.25%  |
| 8.01-16.0   | 221       | 20.97%  |
| 32.01-64.0  | 114       | 10.82%  |
| 3.01-4.0    | 107       | 10.15%  |
| 1.01-2.0    | 22        | 2.09%   |
| 24.01-32.0  | 20        | 1.9%    |
| 64.01-256.0 | 17        | 1.61%   |
| 2.01-3.0    | 9         | 0.85%   |
| 0.51-1.0    | 4         | 0.38%   |
| 0.01-0.5    | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 300       | 26.34%  |
| 4.01-8.0   | 265       | 23.27%  |
| 1.01-2.0   | 254       | 22.3%   |
| 3.01-4.0   | 194       | 17.03%  |
| 8.01-16.0  | 71        | 6.23%   |
| 0.51-1.0   | 41        | 3.6%    |
| 0.01-0.5   | 8         | 0.7%    |
| 16.01-24.0 | 5         | 0.44%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 743       | 70.16%  |
| 2      | 282       | 26.63%  |
| 3      | 29        | 2.74%   |
| 4      | 3         | 0.28%   |
| 5      | 1         | 0.09%   |
| 0      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 766       | 72.95%  |
| Yes       | 284       | 27.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 843       | 80.52%  |
| No        | 204       | 19.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1031      | 98.66%  |
| No        | 14        | 1.34%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 864       | 82.13%  |
| No        | 188       | 17.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 168       | 16.03%  |
| USA          | 147       | 14.03%  |
| Brazil       | 69        | 6.58%   |
| Italy        | 50        | 4.77%   |
| Russia       | 49        | 4.68%   |
| France       | 49        | 4.68%   |
| Netherlands  | 46        | 4.39%   |
| UK           | 29        | 2.77%   |
| Spain        | 27        | 2.58%   |
| Poland       | 27        | 2.58%   |
| India        | 27        | 2.58%   |
| China        | 20        | 1.91%   |
| Canada       | 20        | 1.91%   |
| Czechia      | 18        | 1.72%   |
| Austria      | 18        | 1.72%   |
| Switzerland  | 16        | 1.53%   |
| Sweden       | 15        | 1.43%   |
| Belgium      | 15        | 1.43%   |
| Mexico       | 14        | 1.34%   |
| Romania      | 13        | 1.24%   |
| Hungary      | 13        | 1.24%   |
| Australia    | 12        | 1.15%   |
| Portugal     | 11        | 1.05%   |
| Bulgaria     | 11        | 1.05%   |
| Turkey       | 10        | 0.95%   |
| Norway       | 10        | 0.95%   |
| Finland      | 9         | 0.86%   |
| Chile        | 9         | 0.86%   |
| Ukraine      | 8         | 0.76%   |
| Belarus      | 7         | 0.67%   |
| Serbia       | 6         | 0.57%   |
| Indonesia    | 6         | 0.57%   |
| Argentina    | 6         | 0.57%   |
| Peru         | 5         | 0.48%   |
| Greece       | 5         | 0.48%   |
| Vietnam      | 4         | 0.38%   |
| South Africa | 4         | 0.38%   |
| Philippines  | 4         | 0.38%   |
| Luxembourg   | 4         | 0.38%   |
| Denmark      | 4         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 18        | 1.63%   |
| Moscow            | 15        | 1.36%   |
| Vienna            | 12        | 1.09%   |
| Paris             | 11        | 1%      |
| Sao Paulo         | 10        | 0.9%    |
| Amsterdam         | 9         | 0.81%   |
| St Petersburg     | 8         | 0.72%   |
| Prague            | 8         | 0.72%   |
| Bengaluru         | 8         | 0.72%   |
| Warsaw            | 7         | 0.63%   |
| Rio de Janeiro    | 7         | 0.63%   |
| Munich            | 7         | 0.63%   |
| Milan             | 7         | 0.63%   |
| Budapest          | 7         | 0.63%   |
| Sofia             | 6         | 0.54%   |
| Santiago          | 6         | 0.54%   |
| Hamburg           | 6         | 0.54%   |
| Zurich            | 5         | 0.45%   |
| The Hague         | 5         | 0.45%   |
| Rome              | 5         | 0.45%   |
| Riverton          | 5         | 0.45%   |
| Montreal          | 5         | 0.45%   |
| Bucharest         | 5         | 0.45%   |
| Belgrade          | 5         | 0.45%   |
| Barcelona         | 5         | 0.45%   |
| Stockholm         | 4         | 0.36%   |
| Schrobenhausen    | 4         | 0.36%   |
| Recife            | 4         | 0.36%   |
| Poznan            | 4         | 0.36%   |
| Porto             | 4         | 0.36%   |
| Neuchatel         | 4         | 0.36%   |
| Minsk             | 4         | 0.36%   |
| Mexico City       | 4         | 0.36%   |
| Mesa              | 4         | 0.36%   |
| Melbourne         | 4         | 0.36%   |
| Madrid            | 4         | 0.36%   |
| Los Angeles       | 4         | 0.36%   |
| Jakarta           | 4         | 0.36%   |
| Halle             | 4         | 0.36%   |
| Frankfurt am Main | 4         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 294       | 377    | 21.97%  |
| WDC                            | 128       | 156    | 9.57%   |
| Seagate                        | 120       | 152    | 8.97%   |
| Toshiba                        | 97        | 112    | 7.25%   |
| Sandisk                        | 86        | 104    | 6.43%   |
| Kingston                       | 82        | 97     | 6.13%   |
| SK hynix                       | 73        | 87     | 5.46%   |
| Crucial                        | 49        | 63     | 3.66%   |
| Unknown                        | 45        | 53     | 3.36%   |
| Intel                          | 41        | 46     | 3.06%   |
| HGST                           | 38        | 50     | 2.84%   |
| Micron Technology              | 32        | 38     | 2.39%   |
| Hitachi                        | 24        | 27     | 1.79%   |
| KIOXIA                         | 17        | 20     | 1.27%   |
| China                          | 13        | 15     | 0.97%   |
| A-DATA Technology              | 12        | 17     | 0.9%    |
| Kingston Technology Company    | 11        | 11     | 0.82%   |
| Silicon Motion                 | 10        | 11     | 0.75%   |
| LITEON                         | 10        | 11     | 0.75%   |
| Intenso                        | 10        | 13     | 0.75%   |
| Apple                          | 10        | 12     | 0.75%   |
| PNY                            | 8         | 10     | 0.6%    |
| Phison Electronics             | 6         | 10     | 0.45%   |
| Micron/Crucial Technology      | 6         | 6      | 0.45%   |
| Fujitsu                        | 6         | 7      | 0.45%   |
| Transcend                      | 5         | 6      | 0.37%   |
| Hewlett-Packard                | 5         | 7      | 0.37%   |
| GOODRAM                        | 5         | 5      | 0.37%   |
| Solid State Storage Technology | 4         | 4      | 0.3%    |
| Phison                         | 4         | 5      | 0.3%    |
| LITEONIT                       | 4         | 4      | 0.3%    |
| Lenovo                         | 4         | 6      | 0.3%    |
| Unknown                        | 4         | 4      | 0.3%    |
| XPG                            | 3         | 5      | 0.22%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.22%   |
| UMIS                           | 3         | 4      | 0.22%   |
| Team                           | 3         | 3      | 0.22%   |
| SPCC                           | 3         | 4      | 0.22%   |
| Plextor                        | 3         | 4      | 0.22%   |
| Pioneer                        | 3         | 11     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 24        | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 23        | 1.65%   |
| Seagate ST1000LM035-1RK172 1TB                      | 21        | 1.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 21        | 1.51%   |
| HGST HTS721010A9E630 1TB                            | 17        | 1.22%   |
| Toshiba MQ04ABF100 1TB                              | 13        | 0.93%   |
| Samsung SSD 860 EVO 500GB                           | 13        | 0.93%   |
| Toshiba MQ01ABD100 1TB                              | 12        | 0.86%   |
| Kingston SA400S37480G 480GB SSD                     | 12        | 0.86%   |
| Kingston SA400S37120G 120GB SSD                     | 11        | 0.79%   |
| Samsung NVMe SSD Drive 512GB                        | 10        | 0.72%   |
| Unknown MMC Card  128GB                             | 9         | 0.65%   |
| Seagate ST2000LM015-2E8174 2TB                      | 9         | 0.65%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 9         | 0.65%   |
| Samsung SSD 860 EVO 1TB                             | 8         | 0.57%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.57%   |
| Unknown MMC Card  32GB                              | 7         | 0.5%    |
| Seagate ST1000LM048-2E7172 1TB                      | 7         | 0.5%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 7         | 0.5%    |
| Kingston SA400S37240G 240GB SSD                     | 7         | 0.5%    |
| Intel SSD 660P Series 512GB                         | 7         | 0.5%    |
| HGST HTS725050A7E630 500GB                          | 7         | 0.5%    |
| Crucial CT500MX500SSD1 500GB                        | 7         | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                         | 7         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 6         | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 6         | 0.43%   |
| WDC WD10SPZX-24Z10 1TB                              | 6         | 0.43%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 6         | 0.43%   |
| Sandisk WD Black SN850 1TB                          | 6         | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.43%   |
| Samsung SSD 850 EVO 1TB                             | 6         | 0.43%   |
| Samsung NVMe SSD Drive 500GB                        | 6         | 0.43%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.36%   |
| SK hynix NVMe SSD Drive 512GB                       | 5         | 0.36%   |
| Seagate ST9500325AS 500GB                           | 5         | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB                     | 5         | 0.36%   |
| Samsung SSD 970 EVO 500GB                           | 5         | 0.36%   |
| Samsung SSD 850 PRO 256GB                           | 5         | 0.36%   |
| Samsung SSD 840 EVO 250GB                           | 5         | 0.36%   |
| Samsung NVMe SSD Drive 1TB                          | 5         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 117       | 148    | 34.11%  |
| WDC                 | 81        | 103    | 23.62%  |
| Toshiba             | 57        | 63     | 16.62%  |
| HGST                | 38        | 50     | 11.08%  |
| Hitachi             | 24        | 27     | 7%      |
| Samsung Electronics | 11        | 15     | 3.21%   |
| Fujitsu             | 6         | 7      | 1.75%   |
| Unknown             | 3         | 3      | 0.87%   |
| Pioneer             | 2         | 7      | 0.58%   |
| SSK                 | 1         | 1      | 0.29%   |
| Magnetic Data       | 1         | 2      | 0.29%   |
| Intenso             | 1         | 1      | 0.29%   |
| Apple               | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 119       | 138    | 26.62%  |
| Kingston            | 55        | 64     | 12.3%   |
| SanDisk             | 52        | 60     | 11.63%  |
| Crucial             | 44        | 58     | 9.84%   |
| WDC                 | 24        | 25     | 5.37%   |
| SK hynix            | 16        | 22     | 3.58%   |
| Toshiba             | 13        | 16     | 2.91%   |
| China               | 13        | 15     | 2.91%   |
| Micron Technology   | 10        | 14     | 2.24%   |
| LITEON              | 10        | 11     | 2.24%   |
| Intenso             | 9         | 12     | 2.01%   |
| Intel               | 8         | 9      | 1.79%   |
| Apple               | 8         | 10     | 1.79%   |
| A-DATA Technology   | 7         | 9      | 1.57%   |
| PNY                 | 6         | 7      | 1.34%   |
| GOODRAM             | 5         | 5      | 1.12%   |
| Transcend           | 4         | 5      | 0.89%   |
| LITEONIT            | 4         | 4      | 0.89%   |
| Hewlett-Packard     | 4         | 6      | 0.89%   |
| Plextor             | 3         | 4      | 0.67%   |
| Unknown             | 3         | 3      | 0.67%   |
| Team                | 2         | 2      | 0.45%   |
| SPCC                | 2         | 3      | 0.45%   |
| Seagate             | 2         | 2      | 0.45%   |
| Patriot             | 2         | 2      | 0.45%   |
| ASMT                | 2         | 2      | 0.45%   |
| Wibtek              | 1         | 1      | 0.22%   |
| WDC WDS             | 1         | 2      | 0.22%   |
| VISIPRO             | 1         | 1      | 0.22%   |
| TO Exter            | 1         | 1      | 0.22%   |
| Smartbuy            | 1         | 1      | 0.22%   |
| ShanDianZhe         | 1         | 1      | 0.22%   |
| S3+                 | 1         | 1      | 0.22%   |
| Pioneer             | 1         | 4      | 0.22%   |
| OCZ                 | 1         | 1      | 0.22%   |
| MyDigitalSSD        | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| Maxtor              | 1         | 1      | 0.22%   |
| LEQIXIANG           | 1         | 1      | 0.22%   |
| Lenovo              | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 475       | 627    | 37.17%  |
| SSD     | 418       | 532    | 32.71%  |
| HDD     | 334       | 428    | 26.13%  |
| MMC     | 43        | 50     | 3.36%   |
| Unknown | 8         | 8      | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 649       | 932    | 54.08%  |
| NVMe | 473       | 622    | 39.42%  |
| MMC  | 43        | 50     | 3.58%   |
| SAS  | 35        | 41     | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 448       | 587    | 60.54%  |
| 0.51-1.0   | 255       | 330    | 34.46%  |
| 1.01-2.0   | 33        | 39     | 4.46%   |
| 3.01-4.0   | 2         | 2      | 0.27%   |
| 4.01-10.0  | 2         | 2      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 271       | 24.93%  |
| 1001-2000      | 252       | 23.18%  |
| 501-1000       | 181       | 16.65%  |
| 2001-3000      | 137       | 12.6%   |
| 251-500        | 120       | 11.04%  |
| 101-250        | 75        | 6.9%    |
| 51-100         | 21        | 1.93%   |
| Unknown        | 12        | 1.1%    |
| 21-50          | 9         | 0.83%   |
| 1-20           | 9         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 271       | 23.83%  |
| 251-500        | 209       | 18.38%  |
| 51-100         | 188       | 16.53%  |
| 501-1000       | 143       | 12.58%  |
| 1001-2000      | 110       | 9.67%   |
| 1-20           | 73        | 6.42%   |
| 21-50          | 55        | 4.84%   |
| 2001-3000      | 38        | 3.34%   |
| More than 3000 | 37        | 3.25%   |
| Unknown        | 12        | 1.06%   |
| 0              | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 4      | 4.44%   |
| HGST HTS725050A7E630 500GB                          | 3         | 3      | 3.33%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 2.22%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 2      | 2.22%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 2      | 2.22%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                 | 2         | 2      | 2.22%   |
| Kingston SMS200S3240G 240GB SSD                     | 2         | 2      | 2.22%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 2      | 2.22%   |
| HGST HTS721010A9E630 1TB                            | 2         | 2      | 2.22%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 1      | 1.11%   |
| WDC WD5000LPVX-00V0TT0 500GB                        | 1         | 1      | 1.11%   |
| WDC WD3200BEVT-75A23T0 320GB                        | 1         | 1      | 1.11%   |
| WDC WD3200BEVT-22A23T0 320GB                        | 1         | 1      | 1.11%   |
| WDC WD2500BEKT-75A25T0 250GB                        | 1         | 1      | 1.11%   |
| WDC WD10SPZX-75Z10T2 1TB                            | 1         | 1      | 1.11%   |
| Transcend TS128GSSD340 128GB                        | 1         | 1      | 1.11%   |
| Toshiba THNSNJ256G8NY 256GB SSD                     | 1         | 1      | 1.11%   |
| Toshiba MQ02ABD100H 1TB                             | 1         | 2      | 1.11%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 1.11%   |
| Toshiba MQ01ABD032 320GB                            | 1         | 1      | 1.11%   |
| Toshiba MK6465GSX 640GB                             | 1         | 1      | 1.11%   |
| Toshiba MK6008GAH 64GB                              | 1         | 1      | 1.11%   |
| Toshiba MK5075GSX 500GB                             | 1         | 1      | 1.11%   |
| Toshiba MK5065GSXF 500GB                            | 1         | 1      | 1.11%   |
| Toshiba MK5056GSY 500GB                             | 1         | 1      | 1.11%   |
| Toshiba MK5055GSX 500GB                             | 1         | 3      | 1.11%   |
| Toshiba MK3259GSXP 320GB                            | 1         | 1      | 1.11%   |
| Toshiba MK2552GSX 250GB                             | 1         | 1      | 1.11%   |
| Toshiba MK1059GSMP 1TB                              | 1         | 2      | 1.11%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 1.11%   |
| SK hynix HFS032G34MNC-2200A 32GB SSD                | 1         | 1      | 1.11%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 480GB | 1         | 1      | 1.11%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 1.11%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 1.11%   |
| Seagate ST9100824AS 100GB                           | 1         | 1      | 1.11%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 1         | 1      | 1.11%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 1.11%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 1.11%   |
| Seagate ST500LM000-1EJ162 500GB                     | 1         | 1      | 1.11%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1      | 1.11%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 17        | 18     | 19.1%   |
| Toshiba                  | 15        | 19     | 16.85%  |
| Samsung Electronics      | 9         | 11     | 10.11%  |
| WDC                      | 6         | 6      | 6.74%   |
| Hitachi                  | 6         | 7      | 6.74%   |
| HGST                     | 6         | 6      | 6.74%   |
| SanDisk                  | 4         | 4      | 4.49%   |
| Kingston                 | 4         | 5      | 4.49%   |
| Intel                    | 4         | 4      | 4.49%   |
| Crucial                  | 3         | 3      | 3.37%   |
| SK hynix                 | 2         | 2      | 2.25%   |
| LITEONIT                 | 2         | 2      | 2.25%   |
| Fujitsu                  | 2         | 3      | 2.25%   |
| Transcend                | 1         | 1      | 1.12%   |
| Silicon Motion           | 1         | 1      | 1.12%   |
| Phison                   | 1         | 1      | 1.12%   |
| Patriot                  | 1         | 1      | 1.12%   |
| LEQIXIANG                | 1         | 1      | 1.12%   |
| Corsair                  | 1         | 1      | 1.12%   |
| Biwin Storage Technology | 1         | 1      | 1.12%   |
| Apple                    | 1         | 1      | 1.12%   |
| A-DATA Technology        | 1         | 2      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 30.91%  |
| Toshiba             | 14        | 18     | 25.45%  |
| Hitachi             | 6         | 7      | 10.91%  |
| HGST                | 6         | 6      | 10.91%  |
| WDC                 | 5         | 5      | 9.09%   |
| Samsung Electronics | 4         | 6      | 7.27%   |
| Fujitsu             | 2         | 3      | 3.64%   |
| Apple               | 1         | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 64     | 61.8%   |
| SSD  | 28        | 30     | 31.46%  |
| NVMe | 6         | 6      | 6.74%   |

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
| Works    | 613       | 882    | 54.25%  |
| Detected | 431       | 663    | 38.14%  |
| Malfunc  | 86        | 100    | 7.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 680       | 51.75%  |
| Samsung Electronics                     | 180       | 13.7%   |
| AMD                                     | 143       | 10.88%  |
| SanDisk                                 | 58        | 4.41%   |
| SK hynix                                | 56        | 4.26%   |
| Kingston Technology Company             | 39        | 2.97%   |
| Toshiba America Info Systems            | 30        | 2.28%   |
| Micron Technology                       | 23        | 1.75%   |
| KIOXIA                                  | 16        | 1.22%   |
| Phison Electronics                      | 14        | 1.07%   |
| Silicon Motion                          | 12        | 0.91%   |
| Micron/Crucial Technology               | 10        | 0.76%   |
| Nvidia                                  | 9         | 0.68%   |
| ADATA Technology                        | 8         | 0.61%   |
| Solid State Storage Technology          | 7         | 0.53%   |
| Union Memory (Shenzhen)                 | 5         | 0.38%   |
| Realtek Semiconductor                   | 5         | 0.38%   |
| Yangtze Memory Technologies             | 4         | 0.3%    |
| Lenovo                                  | 3         | 0.23%   |
| Shenzhen Longsys Electronics            | 2         | 0.15%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.15%   |
| VIA Technologies                        | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.08%   |
| Shenzhen Unionmemory Information System | 1         | 0.08%   |
| Seagate Technology                      | 1         | 0.08%   |
| Marvell Technology Group                | 1         | 0.08%   |
| Lite-On Technology                      | 1         | 0.08%   |
| Biwin Storage Technology                | 1         | 0.08%   |
| Apple                                   | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 131       | 9.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 93        | 6.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 84        | 6.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 71        | 5.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 48        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 45        | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 44        | 3.19%   |
| Intel Volume Management Device NVMe RAID Controller                            | 42        | 3.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 39        | 2.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 38        | 2.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 35        | 2.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 33        | 2.39%   |
| Samsung NVMe SSD Controller 980                                                | 31        | 2.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 30        | 2.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 26        | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 1.38%   |
| Intel Tiger Lake-LP SATA Controller                                            | 19        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 19        | 1.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 17        | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 16        | 1.16%   |
| Intel SSD 660P Series                                                          | 15        | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 14        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 12        | 0.87%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 12        | 0.87%   |
| Micron NVMe Storage Controller                                                 | 12        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 12        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 12        | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 11        | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 0.73%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 9         | 0.65%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 9         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 9         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 0.65%   |
| Phison E12 NVMe Controller                                                     | 8         | 0.58%   |
| Intel Non-Volatile memory controller                                           | 8         | 0.58%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 7         | 0.51%   |
| Nvidia MCP79 AHCI Controller                                                   | 7         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 716       | 54.04%  |
| NVMe | 471       | 35.55%  |
| RAID | 94        | 7.09%   |
| IDE  | 44        | 3.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 801       | 76.72%  |
| AMD    | 242       | 23.18%  |
| ARM    | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 20        | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 20        | 1.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 1.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 1.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 1.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 1.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 1.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 1.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 1.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 1.34%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 13        | 1.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 1.25%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 12        | 1.15%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 12        | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 1.05%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 1.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 1.05%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.96%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 10        | 0.96%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 0.86%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 8         | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.77%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 7         | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 7         | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 7         | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.67%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.67%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 7         | 0.67%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 7         | 0.67%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 7         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 283       | 27.11%  |
| Intel Core i5                  | 249       | 23.85%  |
| Other                          | 114       | 10.92%  |
| AMD Ryzen 5                    | 68        | 6.51%   |
| AMD Ryzen 7                    | 62        | 5.94%   |
| Intel Core i3                  | 56        | 5.36%   |
| Intel Core 2 Duo               | 37        | 3.54%   |
| Intel Celeron                  | 24        | 2.3%    |
| AMD Ryzen 7 PRO                | 18        | 1.72%   |
| AMD Ryzen 9                    | 14        | 1.34%   |
| Intel Pentium                  | 12        | 1.15%   |
| AMD Ryzen 3                    | 11        | 1.05%   |
| AMD A6                         | 11        | 1.05%   |
| AMD A8                         | 9         | 0.86%   |
| Intel Atom                     | 8         | 0.77%   |
| Intel Xeon                     | 6         | 0.57%   |
| AMD A10                        | 6         | 0.57%   |
| Intel Pentium Dual-Core        | 5         | 0.48%   |
| AMD Ryzen 5 PRO                | 5         | 0.48%   |
| AMD A4                         | 4         | 0.38%   |
| Intel Pentium Silver           | 3         | 0.29%   |
| Intel Core 2                   | 3         | 0.29%   |
| AMD E2                         | 3         | 0.29%   |
| AMD E                          | 3         | 0.29%   |
| AMD Athlon                     | 3         | 0.29%   |
| Intel Genuine                  | 2         | 0.19%   |
| Intel Core m3                  | 2         | 0.19%   |
| Intel Core i9                  | 2         | 0.19%   |
| AMD Ryzen 3 PRO                | 2         | 0.19%   |
| AMD E1                         | 2         | 0.19%   |
| AMD Athlon X2                  | 2         | 0.19%   |
| AMD Athlon II                  | 2         | 0.19%   |
| AMD A12                        | 2         | 0.19%   |
| Intel Pentium M                | 1         | 0.1%    |
| Intel Pentium III              | 1         | 0.1%    |
| Intel Pentium Dual             | 1         | 0.1%    |
| Intel Core M                   | 1         | 0.1%    |
| Intel Celeron M                | 1         | 0.1%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.1%    |
| AMD Turion II Dual-Core        | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 449       | 42.97%  |
| 4      | 347       | 33.21%  |
| 8      | 106       | 10.14%  |
| 6      | 94        | 9%      |
| 1      | 16        | 1.53%   |
| 12     | 12        | 1.15%   |
| 10     | 10        | 0.96%   |
| 14     | 9         | 0.86%   |
| 24     | 1         | 0.1%    |
| 16     | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1043      | 99.9%   |
| 2      | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 874       | 83.64%  |
| 1      | 170       | 16.27%  |
| 8      | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1019      | 97.23%  |
| Unknown        | 23        | 2.19%   |
| 32-bit         | 6         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 183       | 17.2%   |
| 0x206a7    | 56        | 5.26%   |
| 0x306a9    | 55        | 5.17%   |
| 0x806c1    | 50        | 4.7%    |
| 0x406e3    | 43        | 4.04%   |
| 0x906ea    | 39        | 3.67%   |
| 0x806ec    | 38        | 3.57%   |
| 0x806ea    | 36        | 3.38%   |
| 0x306c3    | 36        | 3.38%   |
| 0x0a50000c | 35        | 3.29%   |
| 0x806e9    | 34        | 3.2%    |
| 0x40651    | 31        | 2.91%   |
| 0x306d4    | 30        | 2.82%   |
| 0x08600106 | 23        | 2.16%   |
| 0x506e3    | 22        | 2.07%   |
| 0x08600104 | 19        | 1.79%   |
| 0x08108102 | 19        | 1.79%   |
| 0x906e9    | 18        | 1.69%   |
| 0x20655    | 18        | 1.69%   |
| 0x1067a    | 17        | 1.6%    |
| 0x08608103 | 17        | 1.6%    |
| 0x08108109 | 17        | 1.6%    |
| 0x906a3    | 14        | 1.32%   |
| 0x806eb    | 13        | 1.22%   |
| 0x806d1    | 12        | 1.13%   |
| 0x706e5    | 12        | 1.13%   |
| 0x06006705 | 11        | 1.03%   |
| 0x6fd      | 9         | 0.85%   |
| 0x08608102 | 8         | 0.75%   |
| 0xa0652    | 7         | 0.66%   |
| 0x706a8    | 7         | 0.66%   |
| 0x10676    | 7         | 0.66%   |
| 0x0a404102 | 7         | 0.66%   |
| 0x08600103 | 7         | 0.66%   |
| 0x0810100b | 7         | 0.66%   |
| 0x07030105 | 6         | 0.56%   |
| 0x06001119 | 6         | 0.56%   |
| 0x906ed    | 5         | 0.47%   |
| 0x906a4    | 5         | 0.47%   |
| 0x30678    | 5         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 227       | 21.74%  |
| Haswell          | 87        | 8.33%   |
| Skylake          | 75        | 7.18%   |
| IvyBridge        | 70        | 6.7%    |
| TigerLake        | 59        | 5.65%   |
| SandyBridge      | 59        | 5.65%   |
| Zen 2            | 54        | 5.17%   |
| Zen 3            | 41        | 3.93%   |
| Unknown          | 41        | 3.93%   |
| Zen+             | 38        | 3.64%   |
| Broadwell        | 36        | 3.45%   |
| Alderlake Hybrid | 33        | 3.16%   |
| Westmere         | 32        | 3.07%   |
| Penryn           | 30        | 2.87%   |
| Icelake          | 24        | 2.3%    |
| Excavator        | 19        | 1.82%   |
| Core             | 18        | 1.72%   |
| Zen              | 13        | 1.25%   |
| CometLake        | 13        | 1.25%   |
| Goldmont plus    | 12        | 1.15%   |
| Puma             | 9         | 0.86%   |
| Silvermont       | 8         | 0.77%   |
| Piledriver       | 7         | 0.67%   |
| Bonnell          | 6         | 0.57%   |
| K10 Llano        | 5         | 0.48%   |
| Bobcat           | 5         | 0.48%   |
| Steamroller      | 3         | 0.29%   |
| P6               | 3         | 0.29%   |
| Nehalem          | 3         | 0.29%   |
| K8 & K10 hybrid  | 3         | 0.29%   |
| K10              | 3         | 0.29%   |
| Goldmont         | 3         | 0.29%   |
| Tremont          | 2         | 0.19%   |
| Jaguar           | 2         | 0.19%   |
| K8 Hammer        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 733       | 53.98%  |
| Nvidia           | 329       | 24.23%  |
| AMD              | 295       | 21.72%  |
| VIA Technologies | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 63        | 4.5%    |
| AMD Renoir                                                                            | 54        | 3.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 52        | 3.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 49        | 3.5%    |
| Intel UHD Graphics 620                                                                | 47        | 3.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 47        | 3.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 46        | 3.29%   |
| Intel HD Graphics 620                                                                 | 41        | 2.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 41        | 2.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 39        | 2.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 39        | 2.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 39        | 2.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 36        | 2.57%   |
| Intel HD Graphics 5500                                                                | 27        | 1.93%   |
| AMD Lucienne                                                                          | 26        | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                   | 25        | 1.79%   |
| Intel HD Graphics 530                                                                 | 22        | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 22        | 1.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 21        | 1.5%    |
| Intel HD Graphics 630                                                                 | 20        | 1.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 16        | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 15        | 1.07%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 12        | 0.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 12        | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 12        | 0.86%   |
| AMD Rembrandt [Radeon 680M]                                                           | 12        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 11        | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 11        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 11        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 11        | 0.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 11        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 11        | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 10        | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 10        | 0.71%   |
| Nvidia GP108M [GeForce MX150]                                                         | 9         | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 9         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 9         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 9         | 0.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 9         | 0.64%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 9         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 458       | 43.87%  |
| Intel + Nvidia | 232       | 22.22%  |
| 1 x AMD        | 192       | 18.39%  |
| 1 x Nvidia     | 52        | 4.98%   |
| AMD + Nvidia   | 43        | 4.12%   |
| Intel + AMD    | 37        | 3.54%   |
| 2 x AMD        | 23        | 2.2%    |
| 2 x Intel      | 3         | 0.29%   |
| Other          | 2         | 0.19%   |
| 2 x Nvidia     | 1         | 0.1%    |
| 1 x VIA        | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 888       | 84.17%  |
| Proprietary | 150       | 14.22%  |
| Unknown     | 17        | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 618       | 58.25%  |
| 0.01-0.5   | 151       | 14.23%  |
| 1.01-2.0   | 119       | 11.22%  |
| 3.01-4.0   | 66        | 6.22%   |
| 0.51-1.0   | 65        | 6.13%   |
| 5.01-6.0   | 20        | 1.89%   |
| 7.01-8.0   | 13        | 1.23%   |
| 8.01-16.0  | 7         | 0.66%   |
| 2.01-3.0   | 2         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 225       | 17.96%  |
| Chimei Innolux          | 176       | 14.05%  |
| BOE                     | 173       | 13.81%  |
| LG Display              | 168       | 13.41%  |
| Samsung Electronics     | 116       | 9.26%   |
| Dell                    | 45        | 3.59%   |
| Sharp                   | 39        | 3.11%   |
| Apple                   | 33        | 2.63%   |
| Lenovo                  | 31        | 2.47%   |
| Goldstar                | 31        | 2.47%   |
| PANDA                   | 21        | 1.68%   |
| InfoVision              | 19        | 1.52%   |
| Hewlett-Packard         | 17        | 1.36%   |
| Chi Mei Optoelectronics | 17        | 1.36%   |
| BenQ                    | 12        | 0.96%   |
| Acer                    | 11        | 0.88%   |
| AOC                     | 10        | 0.8%    |
| Philips                 | 8         | 0.64%   |
| LG Philips              | 8         | 0.64%   |
| Ancor Communications    | 8         | 0.64%   |
| CSO                     | 7         | 0.56%   |
| Iiyama                  | 6         | 0.48%   |
| TMX                     | 5         | 0.4%    |
| Unknown                 | 4         | 0.32%   |
| Pixio                   | 4         | 0.32%   |
| Fujitsu Siemens         | 4         | 0.32%   |
| CPT                     | 4         | 0.32%   |
| Toshiba                 | 3         | 0.24%   |
| Sony                    | 3         | 0.24%   |
| HUAWEI                  | 3         | 0.24%   |
| Eizo                    | 3         | 0.24%   |
| ASUSTek Computer        | 3         | 0.24%   |
| Vizio                   | 2         | 0.16%   |
| ViewSonic               | 2         | 0.16%   |
| STA                     | 2         | 0.16%   |
| Insignia                | 2         | 0.16%   |
| InnoLux Display         | 2         | 0.16%   |
| GDH                     | 2         | 0.16%   |
| DENON                   | 2         | 0.16%   |
| ___                     | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 13        | 1.02%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 9         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 9         | 0.71%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 8         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 7         | 0.55%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 6         | 0.47%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 6         | 0.47%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 6         | 0.47%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 5         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 5         | 0.39%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 5         | 0.39%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 5         | 0.39%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 5         | 0.39%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 0.39%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 5         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.31%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 4         | 0.31%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.31%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 4         | 0.31%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 4         | 0.31%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 4         | 0.31%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 4         | 0.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4         | 0.31%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 4         | 0.31%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 4         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 579       | 48.86%  |
| 1366x768 (WXGA)    | 241       | 20.34%  |
| 1600x900 (HD+)     | 65        | 5.49%   |
| 3840x2160 (4K)     | 54        | 4.56%   |
| 2560x1440 (QHD)    | 42        | 3.54%   |
| 1280x800 (WXGA)    | 39        | 3.29%   |
| 1920x1200 (WUXGA)  | 32        | 2.7%    |
| 1440x900 (WXGA+)   | 16        | 1.35%   |
| 2560x1600          | 14        | 1.18%   |
| 2560x1080          | 13        | 1.1%    |
| 2880x1800          | 12        | 1.01%   |
| 1680x1050 (WSXGA+) | 10        | 0.84%   |
| 1280x1024 (SXGA)   | 10        | 0.84%   |
| 3200x1800 (QHD+)   | 6         | 0.51%   |
| 2160x1440          | 5         | 0.42%   |
| 1024x768 (XGA)     | 5         | 0.42%   |
| 3840x2400          | 4         | 0.34%   |
| 1024x600           | 4         | 0.34%   |
| 3440x1440          | 3         | 0.25%   |
| Unknown            | 3         | 0.25%   |
| 3840x1080          | 2         | 0.17%   |
| 3456x2160          | 2         | 0.17%   |
| 3200x2000          | 2         | 0.17%   |
| 2520x1680          | 2         | 0.17%   |
| 2240x1400          | 2         | 0.17%   |
| 1920x540           | 2         | 0.17%   |
| 1360x768           | 2         | 0.17%   |
| 8960x2160          | 1         | 0.08%   |
| 800x1280           | 1         | 0.08%   |
| 4480x1440          | 1         | 0.08%   |
| 3840x2560          | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3840x1100          | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |
| 2256x1504          | 1         | 0.08%   |
| 2200x1650          | 1         | 0.08%   |
| 2048x1536          | 1         | 0.08%   |
| 1600x1200          | 1         | 0.08%   |
| 1280x960           | 1         | 0.08%   |
| 1280x720 (HD)      | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 506       | 40.35%  |
| 14      | 171       | 13.64%  |
| 13      | 149       | 11.88%  |
| 17      | 105       | 8.37%   |
| 27      | 47        | 3.75%   |
| 12      | 38        | 3.03%   |
| 24      | 35        | 2.79%   |
| 21      | 35        | 2.79%   |
| 23      | 32        | 2.55%   |
| 16      | 18        | 1.44%   |
| 34      | 11        | 0.88%   |
| 11      | 11        | 0.88%   |
| 84      | 8         | 0.64%   |
| 31      | 8         | 0.64%   |
| 19      | 8         | 0.64%   |
| 18      | 8         | 0.64%   |
| Unknown | 8         | 0.64%   |
| 26      | 7         | 0.56%   |
| 22      | 6         | 0.48%   |
| 29      | 5         | 0.4%    |
| 20      | 5         | 0.4%    |
| 49      | 3         | 0.24%   |
| 37      | 3         | 0.24%   |
| 25      | 3         | 0.24%   |
| 10      | 3         | 0.24%   |
| 72      | 2         | 0.16%   |
| 54      | 2         | 0.16%   |
| 52      | 2         | 0.16%   |
| 38      | 2         | 0.16%   |
| 32      | 2         | 0.16%   |
| 142     | 1         | 0.08%   |
| 60      | 1         | 0.08%   |
| 58      | 1         | 0.08%   |
| 48      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 40      | 1         | 0.08%   |
| 35      | 1         | 0.08%   |
| 28      | 1         | 0.08%   |
| 9       | 1         | 0.08%   |
| 8       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 751       | 60.47%  |
| 201-300        | 125       | 10.06%  |
| 351-400        | 122       | 9.82%   |
| 501-600        | 112       | 9.02%   |
| 401-500        | 58        | 4.67%   |
| 601-700        | 21        | 1.69%   |
| 701-800        | 13        | 1.05%   |
| 1001-1500      | 11        | 0.89%   |
| 1501-2000      | 10        | 0.81%   |
| Unknown        | 8         | 0.64%   |
| 801-900        | 7         | 0.56%   |
| 101-200        | 2         | 0.16%   |
| More than 2000 | 1         | 0.08%   |
| 1-100          | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 907       | 83.29%  |
| 16/10   | 125       | 11.48%  |
| 3/2     | 13        | 1.19%   |
| 21/9    | 13        | 1.19%   |
| 4/3     | 11        | 1.01%   |
| 5/4     | 8         | 0.73%   |
| 2.65    | 4         | 0.37%   |
| Unknown | 3         | 0.28%   |
| 32/9    | 2         | 0.18%   |
| 6/5     | 1         | 0.09%   |
| 3.40    | 1         | 0.09%   |
| 1.00    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 507       | 40.56%  |
| 81-90          | 267       | 21.36%  |
| 121-130        | 93        | 7.44%   |
| 201-250        | 86        | 6.88%   |
| 71-80          | 52        | 4.16%   |
| 301-350        | 51        | 4.08%   |
| 61-70          | 36        | 2.88%   |
| 351-500        | 24        | 1.92%   |
| 151-200        | 24        | 1.92%   |
| More than 1000 | 20        | 1.6%    |
| 251-300        | 18        | 1.44%   |
| 111-120        | 15        | 1.2%    |
| 51-60          | 12        | 0.96%   |
| 131-140        | 10        | 0.8%    |
| 141-150        | 9         | 0.72%   |
| 501-1000       | 8         | 0.64%   |
| Unknown        | 8         | 0.64%   |
| 41-50          | 4         | 0.32%   |
| 91-100         | 4         | 0.32%   |
| 1-40           | 2         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 558       | 45.63%  |
| 101-120       | 309       | 25.27%  |
| 51-100        | 191       | 15.62%  |
| 161-240       | 98        | 8.01%   |
| More than 240 | 48        | 3.92%   |
| 1-50          | 11        | 0.9%    |
| Unknown       | 8         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 818       | 76.38%  |
| 2     | 206       | 19.23%  |
| 3     | 28        | 2.61%   |
| 0     | 16        | 1.49%   |
| 4     | 3         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 614       | 37.17%  |
| Realtek Semiconductor                  | 540       | 32.69%  |
| Qualcomm Atheros                       | 197       | 11.92%  |
| Broadcom                               | 93        | 5.63%   |
| MediaTek                               | 39        | 2.36%   |
| Broadcom Limited                       | 22        | 1.33%   |
| Marvell Technology Group               | 13        | 0.79%   |
| Ralink Technology                      | 11        | 0.67%   |
| ASIX Electronics                       | 10        | 0.61%   |
| Sierra Wireless                        | 9         | 0.54%   |
| Ralink                                 | 9         | 0.54%   |
| Nvidia                                 | 9         | 0.54%   |
| TP-Link                                | 8         | 0.48%   |
| Lenovo                                 | 8         | 0.48%   |
| Dell                                   | 7         | 0.42%   |
| Hewlett-Packard                        | 6         | 0.36%   |
| Ericsson Business Mobile Networks      | 6         | 0.36%   |
| DisplayLink                            | 6         | 0.36%   |
| Huawei Technologies                    | 4         | 0.24%   |
| Cypress Semiconductor                  | 4         | 0.24%   |
| Xiaomi                                 | 3         | 0.18%   |
| Samsung Electronics                    | 3         | 0.18%   |
| Qualcomm                               | 3         | 0.18%   |
| ICS Advent                             | 3         | 0.18%   |
| Edimax Technology                      | 3         | 0.18%   |
| HMD Global                             | 2         | 0.12%   |
| D-Link                                 | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.06%   |
| VIA Technologies                       | 1         | 0.06%   |
| VEX                                    | 1         | 0.06%   |
| U-Blox                                 | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.06%   |
| Realtek                                | 1         | 0.06%   |
| Qualcomm Atheros Communications        | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| MosChip Semiconductor                  | 1         | 0.06%   |
| Meizu                                  | 1         | 0.06%   |
| Manta                                  | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 359       | 17.83%  |
| Intel Wi-Fi 6 AX200                                               | 84        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 3.33%   |
| Intel Wireless 8265 / 8275                                        | 62        | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 55        | 2.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 2.38%   |
| Intel Wi-Fi 6 AX201                                               | 43        | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 2.14%   |
| Intel Wireless 8260                                               | 39        | 1.94%   |
| Intel Wireless 7260                                               | 37        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.64%   |
| Intel Wireless 7265                                               | 32        | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 30        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 27        | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 24        | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 22        | 1.09%   |
| Intel Wireless-AC 9260                                            | 22        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 20        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 18        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16        | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.79%   |
| Intel Centrino Ultimate-N 6300                                    | 15        | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 14        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 14        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 13        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.65%   |
| Intel Centrino Advanced-N 6235                                    | 13        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 13        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.6%    |
| Intel Wireless 3160                                               | 11        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 595       | 55.14%  |
| Qualcomm Atheros                | 164       | 15.2%   |
| Realtek Semiconductor           | 144       | 13.35%  |
| Broadcom                        | 78        | 7.23%   |
| MediaTek                        | 35        | 3.24%   |
| Ralink Technology               | 11        | 1.02%   |
| Broadcom Limited                | 11        | 1.02%   |
| Sierra Wireless                 | 9         | 0.83%   |
| Ralink                          | 9         | 0.83%   |
| Dell                            | 6         | 0.56%   |
| Qualcomm                        | 3         | 0.28%   |
| Edimax Technology               | 3         | 0.28%   |
| TP-Link                         | 2         | 0.19%   |
| D-Link                          | 2         | 0.19%   |
| Xiaomi                          | 1         | 0.09%   |
| Realtek                         | 1         | 0.09%   |
| Qualcomm Atheros Communications | 1         | 0.09%   |
| Linksys                         | 1         | 0.09%   |
| Hewlett-Packard                 | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |
| ASUSTek Computer                | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 84        | 7.71%   |
| Intel Wireless 8265 / 8275                                     | 62        | 5.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 55        | 5.05%   |
| Intel Wi-Fi 6 AX201                                            | 43        | 3.95%   |
| Intel Wireless 8260                                            | 39        | 3.58%   |
| Intel Wireless 7260                                            | 37        | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 33        | 3.03%   |
| Intel Wireless 7265                                            | 32        | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 30        | 2.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 2.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 27        | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24        | 2.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 22        | 2.02%   |
| Intel Wireless-AC 9260                                         | 22        | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 20        | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 1.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 18        | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 1.47%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 14        | 1.29%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13        | 1.19%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                  | 13        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1.1%    |
| Intel Wireless 3160                                            | 11        | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 0.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 0.92%   |
| Intel Wireless 3165                                            | 9         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 7         | 0.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 7         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 6         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 485       | 54.19%  |
| Intel                            | 239       | 26.7%   |
| Qualcomm Atheros                 | 52        | 5.81%   |
| Broadcom                         | 30        | 3.35%   |
| Marvell Technology Group         | 13        | 1.45%   |
| Broadcom Limited                 | 11        | 1.23%   |
| ASIX Electronics                 | 10        | 1.12%   |
| Nvidia                           | 9         | 1.01%   |
| Lenovo                           | 8         | 0.89%   |
| TP-Link                          | 6         | 0.67%   |
| DisplayLink                      | 6         | 0.67%   |
| MediaTek                         | 4         | 0.45%   |
| Cypress Semiconductor            | 4         | 0.45%   |
| ICS Advent                       | 3         | 0.34%   |
| Huawei Technologies              | 3         | 0.34%   |
| Xiaomi                           | 2         | 0.22%   |
| Samsung Electronics              | 2         | 0.22%   |
| HMD Global                       | 2         | 0.22%   |
| VIA Technologies                 | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| Motorola PCS                     | 1         | 0.11%   |
| MosChip Semiconductor            | 1         | 0.11%   |
| JMicron Technology               | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 359       | 39.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 7.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 5.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 2.88%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.55%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 1.44%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 1.11%   |
| Intel Ethernet Connection I219-V                                  | 10        | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 9         | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.89%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.66%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 5         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.55%   |
| Intel Ethernet Connection (16) I219-LM                            | 5         | 0.55%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.55%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.55%   |
| Intel Ethernet Connection (10) I219-LM                            | 5         | 0.55%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 5         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.44%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.44%   |
| Cypress K38231_03                                                 | 4         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1030      | 54.38%  |
| Ethernet | 842       | 44.46%  |
| Modem    | 19        | 1%      |
| Unknown  | 3         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 858       | 75.46%  |
| Ethernet | 279       | 24.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 769       | 73.59%  |
| 1     | 259       | 24.78%  |
| 3     | 10        | 0.96%   |
| 0     | 7         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 853       | 80.17%  |
| Yes  | 211       | 19.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 467       | 53.68%  |
| Realtek Semiconductor           | 80        | 9.2%    |
| Qualcomm Atheros Communications | 74        | 8.51%   |
| Lite-On Technology              | 47        | 5.4%    |
| Broadcom                        | 40        | 4.6%    |
| IMC Networks                    | 39        | 4.48%   |
| Foxconn / Hon Hai               | 31        | 3.56%   |
| Apple                           | 30        | 3.45%   |
| Hewlett-Packard                 | 11        | 1.26%   |
| Dell                            | 9         | 1.03%   |
| Realtek                         | 8         | 0.92%   |
| Cambridge Silicon Radio         | 7         | 0.8%    |
| Toshiba                         | 6         | 0.69%   |
| MediaTek                        | 3         | 0.34%   |
| USI                             | 2         | 0.23%   |
| Taiyo Yuden                     | 2         | 0.23%   |
| Smart Modular Technologies      | 2         | 0.23%   |
| Ralink                          | 2         | 0.23%   |
| Foxconn International           | 2         | 0.23%   |
| Alps Electric                   | 2         | 0.23%   |
| Unknown                         | 1         | 0.11%   |
| Ralink Technology               | 1         | 0.11%   |
| Qcom                            | 1         | 0.11%   |
| Integrated System Solution      | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| ASUSTek Computer                | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 170       | 19.47%  |
| Intel AX200 Bluetooth                                                               | 80        | 9.16%   |
| Intel AX201 Bluetooth                                                               | 79        | 9.05%   |
| Realtek Bluetooth Radio                                                             | 52        | 5.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 51        | 5.84%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 37        | 4.24%   |
| Intel Bluetooth Device                                                              | 23        | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 21        | 2.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 20        | 2.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 19        | 2.18%   |
| Apple Bluetooth Host Controller                                                     | 19        | 2.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 16        | 1.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 16        | 1.83%   |
| Intel AX210 Bluetooth                                                               | 15        | 1.72%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 1.49%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 13        | 1.49%   |
| IMC Networks Wireless_Device                                                        | 11        | 1.26%   |
| IMC Networks Bluetooth Device                                                       | 10        | 1.15%   |
| Lite-On Wireless_Device                                                             | 9         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 1.03%   |
| Apple Bluetooth USB Host Controller                                                 | 9         | 1.03%   |
| Realtek Bluetooth Radio                                                             | 8         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 0.92%   |
| Lite-On Bluetooth Device                                                            | 7         | 0.8%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 0.8%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.69%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 5         | 0.57%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.46%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 4         | 0.46%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.46%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 0.46%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 4         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.46%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.34%   |
| MediaTek Wireless_Device                                                            | 3         | 0.34%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 3         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 785       | 61.86%  |
| AMD                                             | 259       | 20.41%  |
| Nvidia                                          | 114       | 8.98%   |
| C-Media Electronics                             | 14        | 1.1%    |
| Realtek Semiconductor                           | 11        | 0.87%   |
| Lenovo                                          | 10        | 0.79%   |
| Logitech                                        | 8         | 0.63%   |
| Texas Instruments                               | 7         | 0.55%   |
| JMTek                                           | 4         | 0.32%   |
| GN Netcom                                       | 4         | 0.32%   |
| Razer USA                                       | 3         | 0.24%   |
| Plantronics                                     | 3         | 0.24%   |
| M-Audio                                         | 3         | 0.24%   |
| Hewlett-Packard                                 | 3         | 0.24%   |
| Creative Technology                             | 3         | 0.24%   |
| BEHRINGER International                         | 3         | 0.24%   |
| SAVITECH                                        | 2         | 0.16%   |
| RODE Microphones                                | 2         | 0.16%   |
| No brand                                        | 2         | 0.16%   |
| Kingston Technology                             | 2         | 0.16%   |
| Generalplus Technology                          | 2         | 0.16%   |
| Focusrite-Novation                              | 2         | 0.16%   |
| ESS Technology                                  | 2         | 0.16%   |
| Conexant Systems                                | 2         | 0.16%   |
| ASUSTek Computer                                | 2         | 0.16%   |
| ZOOM                                            | 1         | 0.08%   |
| Yamaha                                          | 1         | 0.08%   |
| VIA Technologies                                | 1         | 0.08%   |
| SteelSeries ApS                                 | 1         | 0.08%   |
| Specialix                                       | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.08%   |
| Philips (or NXP)                                | 1         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.08%   |
| LG Electronics                                  | 1         | 0.08%   |
| iSoft Silicon                                   | 1         | 0.08%   |
| Huawei Technologies                             | 1         | 0.08%   |
| GYROCOM C&C                                     | 1         | 0.08%   |
| FiiO Electronics Technology                     | 1         | 0.08%   |
| Dell                                            | 1         | 0.08%   |
| Corsair                                         | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 179       | 11.19%  |
| Intel Sunrise Point-LP HD Audio                                            | 141       | 8.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 104       | 6.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 79        | 4.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 59        | 3.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 52        | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 50        | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 48        | 3%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 47        | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 39        | 2.44%   |
| Intel 8 Series HD Audio Controller                                         | 39        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 37        | 2.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 36        | 2.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 2.19%   |
| Intel Broadwell-U Audio Controller                                         | 35        | 2.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 35        | 2.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 29        | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 27        | 1.69%   |
| AMD FCH Azalia Controller                                                  | 27        | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 23        | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 23        | 1.44%   |
| Intel CM238 HD Audio Controller                                            | 21        | 1.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 19        | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                   | 18        | 1.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 0.75%   |
| AMD High Definition Audio Controller                                       | 12        | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 11        | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 0.69%   |
| Realtek Semiconductor USB Audio                                            | 10        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10        | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 10        | 0.63%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.56%   |
| Nvidia MCP79 High Definition Audio                                         | 8         | 0.5%    |
| Nvidia GT216 HDMI Audio Controller                                         | 7         | 0.44%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 268       | 31.35%  |
| SK hynix            | 196       | 22.92%  |
| Micron Technology   | 105       | 12.28%  |
| Kingston            | 77        | 9.01%   |
| Unknown             | 38        | 4.44%   |
| Crucial             | 38        | 4.44%   |
| Corsair             | 18        | 2.11%   |
| A-DATA Technology   | 18        | 2.11%   |
| Ramaxel Technology  | 16        | 1.87%   |
| Elpida              | 13        | 1.52%   |
| G.Skill             | 9         | 1.05%   |
| Unknown (ABCD)      | 8         | 0.94%   |
| Smart               | 7         | 0.82%   |
| GOODRAM             | 6         | 0.7%    |
| Team                | 5         | 0.58%   |
| Nanya Technology    | 5         | 0.58%   |
| Unknown             | 5         | 0.58%   |
| Transcend           | 3         | 0.35%   |
| Patriot             | 3         | 0.35%   |
| Teikon              | 2         | 0.23%   |
| Qimonda             | 2         | 0.23%   |
| Lexar               | 2         | 0.23%   |
| ChangXin Memory     | 2         | 0.23%   |
| AMD                 | 2         | 0.23%   |
| Toshiba             | 1         | 0.12%   |
| Smart Modular       | 1         | 0.12%   |
| Smart Brazil        | 1         | 0.12%   |
| pqi                 | 1         | 0.12%   |
| Kingmax             | 1         | 0.12%   |
| HT Micron           | 1         | 0.12%   |
| ASint Technology    | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 16        | 1.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 1.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 1.34%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 1%      |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 9         | 1%      |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 8         | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.78%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.78%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 7         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 6         | 0.67%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 6         | 0.67%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.56%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.56%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 5         | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 5         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.56%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 5         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 378       | 53.31%  |
| DDR3    | 214       | 30.18%  |
| LPDDR4  | 37        | 5.22%   |
| DDR2    | 23        | 3.24%   |
| LPDDR3  | 17        | 2.4%    |
| DDR5    | 15        | 2.12%   |
| SDRAM   | 11        | 1.55%   |
| LPDDR5  | 9         | 1.27%   |
| DDR     | 3         | 0.42%   |
| DRAM    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 640       | 88.89%  |
| Row Of Chips | 66        | 9.17%   |
| Chip         | 9         | 1.25%   |
| DIMM         | 4         | 0.56%   |
| Unknown      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 318       | 40.61%  |
| 4096  | 222       | 28.35%  |
| 16384 | 133       | 16.99%  |
| 2048  | 67        | 8.56%   |
| 32768 | 23        | 2.94%   |
| 1024  | 19        | 2.43%   |
| 128   | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 173       | 22.38%  |
| 1600    | 160       | 20.7%   |
| 3200    | 149       | 19.28%  |
| 2400    | 59        | 7.63%   |
| 2133    | 40        | 5.17%   |
| 1334    | 38        | 4.92%   |
| 1333    | 20        | 2.59%   |
| 3266    | 14        | 1.81%   |
| 4800    | 13        | 1.68%   |
| 667     | 12        | 1.55%   |
| 4267    | 11        | 1.42%   |
| 4266    | 9         | 1.16%   |
| 1067    | 9         | 1.16%   |
| Unknown | 9         | 1.16%   |
| 6400    | 8         | 1.03%   |
| 1867    | 8         | 1.03%   |
| 8400    | 7         | 0.91%   |
| 2048    | 6         | 0.78%   |
| 975     | 5         | 0.65%   |
| 3733    | 4         | 0.52%   |
| 800     | 4         | 0.52%   |
| 4199    | 3         | 0.39%   |
| 1066    | 3         | 0.39%   |
| 5600    | 2         | 0.26%   |
| 533     | 2         | 0.26%   |
| 333     | 2         | 0.26%   |
| 2933    | 1         | 0.13%   |
| 1777    | 1         | 0.13%   |
| 100     | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 69.23%  |
| Seiko Epson         | 2         | 15.38%  |
| Samsung Electronics | 1         | 7.69%   |
| Prolific Technology | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Officejet 4500 G510g-m     | 2         | 15.38%  |
| Seiko Epson WF-2510 Series    | 1         | 7.69%   |
| Seiko Epson ET-2710 Series    | 1         | 7.69%   |
| Samsung M267x 287x Series     | 1         | 7.69%   |
| Prolific PL2305 Parallel Port | 1         | 7.69%   |
| HP Officejet Pro 6230         | 1         | 7.69%   |
| HP Officejet 7110 series      | 1         | 7.69%   |
| HP OfficeJet 3830 series      | 1         | 7.69%   |
| HP LaserJet CM1415fn          | 1         | 7.69%   |
| HP LaserJet 1020              | 1         | 7.69%   |
| HP Deskjet Ink Advant K209a-z | 1         | 7.69%   |
| HP DeskJet 2700 series        | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20               | 1         | 33.33%  |
| Canon CanoScan LiDE 210                          | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 251       | 26.39%  |
| IMC Networks                           | 114       | 11.99%  |
| Microdia                               | 81        | 8.52%   |
| Realtek Semiconductor                  | 78        | 8.2%    |
| Sunplus Innovation Technology          | 60        | 6.31%   |
| Bison Electronics                      | 59        | 6.2%    |
| Quanta                                 | 54        | 5.68%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 3.68%   |
| Acer                                   | 33        | 3.47%   |
| Apple                                  | 27        | 2.84%   |
| Syntek                                 | 26        | 2.73%   |
| Luxvisions Innotech Limited            | 25        | 2.63%   |
| Lite-On Technology                     | 24        | 2.52%   |
| Suyin                                  | 17        | 1.79%   |
| Logitech                               | 9         | 0.95%   |
| Silicon Motion                         | 8         | 0.84%   |
| Lenovo                                 | 7         | 0.74%   |
| Alcor Micro                            | 7         | 0.74%   |
| Ricoh                                  | 4         | 0.42%   |
| Primax Electronics                     | 4         | 0.42%   |
| Sonix Technology                       | 3         | 0.32%   |
| Y Media                                | 2         | 0.21%   |
| LG Electronics                         | 2         | 0.21%   |
| Importek                               | 2         | 0.21%   |
| ALi                                    | 2         | 0.21%   |
| Z-Star Microelectronics                | 1         | 0.11%   |
| vivo                                   | 1         | 0.11%   |
| USB Camera CS                          | 1         | 0.11%   |
| Unknown (3730304231385631394831)       | 1         | 0.11%   |
| Tobii Technology AB                    | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| ShineTech                              | 1         | 0.11%   |
| Samsung Electronics                    | 1         | 0.11%   |
| OmniVision Technologies                | 1         | 0.11%   |
| Mitsumi                                | 1         | 0.11%   |
| kingcome                               | 1         | 0.11%   |
| Intel                                  | 1         | 0.11%   |
| Generalplus Technology                 | 1         | 0.11%   |
| Foxconn / Hon Hai                      | 1         | 0.11%   |
| Cypress Semiconductor                  | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 56        | 5.88%   |
| Microdia Integrated_Webcam_HD                        | 43        | 4.51%   |
| IMC Networks Integrated Camera                       | 40        | 4.2%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 34        | 3.57%   |
| Realtek Integrated_Webcam_HD                         | 28        | 2.94%   |
| Chicony HD Webcam                                    | 27        | 2.83%   |
| Sunplus Integrated_Webcam_HD                         | 19        | 1.99%   |
| Chicony HP HD Camera                                 | 16        | 1.68%   |
| Syntek Integrated Camera                             | 15        | 1.57%   |
| Bison Integrated Camera                              | 15        | 1.57%   |
| Acer Integrated Camera                               | 12        | 1.26%   |
| Quanta HP HD Camera                                  | 11        | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 11        | 1.15%   |
| Chicony Integrated Camera (1280x720@30)              | 11        | 1.15%   |
| Lite-On Integrated Camera                            | 10        | 1.05%   |
| Chicony USB2.0 Camera                                | 10        | 1.05%   |
| Chicony HP HD Webcam                                 | 10        | 1.05%   |
| Apple Built-in iSight                                | 10        | 1.05%   |
| Realtek Integrated Webcam HD                         | 9         | 0.94%   |
| Quanta HD User Facing                                | 9         | 0.94%   |
| Apple FaceTime HD Camera                             | 9         | 0.94%   |
| Acer HD Webcam                                       | 9         | 0.94%   |
| Sunplus HD WebCam                                    | 8         | 0.84%   |
| Quanta VGA WebCam                                    | 8         | 0.84%   |
| Chicony HD User Facing                               | 8         | 0.84%   |
| Realtek USB Camera                                   | 7         | 0.73%   |
| Microdia Integrated Webcam                           | 7         | 0.73%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 7         | 0.73%   |
| Chicony USB 2.0 Camera                               | 7         | 0.73%   |
| Chicony FJ Camera                                    | 7         | 0.73%   |
| Quanta HP TrueVision HD Camera                       | 6         | 0.63%   |
| Luxvisions Innotech Limited Integrated Camera        | 6         | 0.63%   |
| Chicony TOSHIBA Web Camera - HD                      | 6         | 0.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 6         | 0.63%   |
| Chicony Lenovo EasyCamera                            | 6         | 0.63%   |
| Chicony Integrated IR Camera                         | 6         | 0.63%   |
| Chicony HP Truevision HD                             | 6         | 0.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 6         | 0.63%   |
| Syntek Lenovo EasyCamera                             | 5         | 0.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 90        | 43.06%  |
| Synaptics                  | 65        | 31.1%   |
| Shenzhen Goodix Technology | 27        | 12.92%  |
| Upek                       | 11        | 5.26%   |
| AuthenTec                  | 10        | 4.78%   |
| Elan Microelectronics      | 4         | 1.91%   |
| LighTuning Technology      | 2         | 0.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 11%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 10.05%  |
| Shenzhen Goodix  FingerPrint Device                                        | 21        | 10.05%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 6.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 5.26%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 4.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 4.31%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 4.31%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 3.35%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 2.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.39%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.39%   |
| Validity Sensors VFS491                                                    | 4         | 1.91%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.91%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.91%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.91%   |
| Synaptics WBDI Device                                                      | 3         | 1.44%   |
| Synaptics WBDI                                                             | 3         | 1.44%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.44%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.44%   |
| Unknown                                                                    | 3         | 1.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.96%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.96%   |
| Synaptics UWP WBDI                                                         | 2         | 0.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.96%   |
| AuthenTec AES2810                                                          | 2         | 0.96%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.96%   |
| AuthenTec AES1600                                                          | 2         | 0.96%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.48%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.48%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.48%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.48%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.48%   |
| Synaptics  WBDI                                                            | 1         | 0.48%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.48%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 37        | 44.58%  |
| Broadcom              | 34        | 40.96%  |
| Upek                  | 4         | 4.82%   |
| O2 Micro              | 3         | 3.61%   |
| Lenovo                | 2         | 2.41%   |
| Gemalto (was Gemplus) | 2         | 2.41%   |
| Hewlett-Packard       | 1         | 1.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 42.17%  |
| Broadcom 5880                                                                | 13        | 15.66%  |
| Broadcom 58200                                                               | 10        | 12.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 8.43%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.82%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.82%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.61%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.41%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.2%    |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 1.2%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.2%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.2%    |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 639       | 59.33%  |
| 1     | 352       | 32.68%  |
| 2     | 76        | 7.06%   |
| 3     | 7         | 0.65%   |
| 4     | 3         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 207       | 39.66%  |
| Graphics card            | 113       | 21.65%  |
| Chipcard                 | 77        | 14.75%  |
| Multimedia controller    | 37        | 7.09%   |
| Net/wireless             | 29        | 5.56%   |
| Camera                   | 18        | 3.45%   |
| Sound                    | 10        | 1.92%   |
| Storage                  | 7         | 1.34%   |
| Card reader              | 6         | 1.15%   |
| Bluetooth                | 6         | 1.15%   |
| Network                  | 3         | 0.57%   |
| Net/ethernet             | 3         | 0.57%   |
| Communication controller | 3         | 0.57%   |
| Modem                    | 2         | 0.38%   |
| Flash memory             | 1         | 0.19%   |

