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

Total: 476

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 10%     |
| Ubuntu 22.04                 | 31        | 9.69%   |
| Arch Rolling                 | 28        | 8.75%   |
| Ubuntu 18.04                 | 9         | 2.81%   |
| ArcoLinux Rolling            | 9         | 2.81%   |
| antiX 21                     | 9         | 2.81%   |
| Fedora 37                    | 8         | 2.5%    |
| Arch                         | 8         | 2.5%    |
| Debian 12                    | 7         | 2.19%   |
| Pop!_OS 22.04                | 6         | 1.88%   |
| Ubuntu 24.04                 | 5         | 1.56%   |
| Kylin V10                    | 5         | 1.56%   |
| Fedora 32                    | 5         | 1.56%   |
| Ubuntu 19.10                 | 4         | 1.25%   |
| OpenMandriva 23.03           | 4         | 1.25%   |
| Gentoo 2.7                   | 4         | 1.25%   |
| Fedora 39                    | 4         | 1.25%   |
| EndeavourOS Rolling          | 4         | 1.25%   |
| Debian 11                    | 4         | 1.25%   |
| Ubuntu 22.10                 | 3         | 0.94%   |
| OpenMandriva 4.2             | 3         | 0.94%   |
| OpenMandriva 23.01           | 3         | 0.94%   |
| Linux Mint 20                | 3         | 0.94%   |
| Fedora 41                    | 3         | 0.94%   |
| Fedora 40                    | 3         | 0.94%   |
| Fedora 36                    | 3         | 0.94%   |
| Fedora 33                    | 3         | 0.94%   |
| Chrome OS                    | 3         | 0.94%   |
| UOS 20                       | 2         | 0.63%   |
| Ubuntu MATE 22.04            | 2         | 0.63%   |
| Ubuntu 23.10                 | 2         | 0.63%   |
| Ubuntu 23.04                 | 2         | 0.63%   |
| Ubuntu 21.04                 | 2         | 0.63%   |
| Ubuntu 19.04                 | 2         | 0.63%   |
| Ubuntu 16.04                 | 2         | 0.63%   |
| SteamOS Rolling              | 2         | 0.63%   |
| Pop!_OS 20.10                | 2         | 0.63%   |
| Pop!_OS 20.04                | 2         | 0.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.63%   |
| OpenMandriva 5.0             | 2         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 94        | 30.92%  |
| Arch          | 36        | 11.84%  |
| Fedora        | 31        | 10.2%   |
| OpenMandriva  | 18        | 5.92%   |
| Pop!_OS       | 12        | 3.95%   |
| Debian        | 12        | 3.95%   |
| Linux Mint    | 10        | 3.29%   |
| Gentoo        | 9         | 2.96%   |
| ArcoLinux     | 9         | 2.96%   |
| antiX         | 9         | 2.96%   |
| Manjaro       | 6         | 1.97%   |
| Kylin         | 5         | 1.64%   |
| SteamOS       | 4         | 1.32%   |
| Kali          | 4         | 1.32%   |
| EndeavourOS   | 4         | 1.32%   |
| Clear Linux   | 4         | 1.32%   |
| Ubuntu Unity  | 3         | 0.99%   |
| ROSA          | 3         | 0.99%   |
| openSUSE      | 3         | 0.99%   |
| NixOS         | 3         | 0.99%   |
| KDE neon      | 3         | 0.99%   |
| Chrome OS     | 3         | 0.99%   |
| Ubuntu MATE   | 2         | 0.66%   |
| Nobara        | 2         | 0.66%   |
| Deepin        | 2         | 0.66%   |
| Zorin         | 1         | 0.33%   |
| Xubuntu       | 1         | 0.33%   |
| Ultramarine   | 1         | 0.33%   |
| UbuntuDDE     | 1         | 0.33%   |
| Ubuntu Budgie | 1         | 0.33%   |
| PCLinuxOS     | 1         | 0.33%   |
| Oracle Linux  | 1         | 0.33%   |
| Kubuntu       | 1         | 0.33%   |
| Guix          | 1         | 0.33%   |
| Elementary    | 1         | 0.33%   |
| CachyOS       | 1         | 0.33%   |
| BlackPanther  | 1         | 0.33%   |
| Atz           | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp  | 9         | 2.48%   |
| 5.4.0-42-generic           | 6         | 1.65%   |
| 6.2.0-26-generic           | 5         | 1.38%   |
| 6.6.2-desktop-1omv2390     | 4         | 1.1%    |
| 6.2.6-desktop-1omv2390     | 4         | 1.1%    |
| 6.3.6-arch1-1              | 3         | 0.83%   |
| 6.1.1-desktop-1omv2290     | 3         | 0.83%   |
| 5.8.0-43-generic           | 3         | 0.83%   |
| 5.4.0-48-generic           | 3         | 0.83%   |
| 5.19.0-32-generic          | 3         | 0.83%   |
| 5.15.0-46-generic          | 3         | 0.83%   |
| 5.13.0-39-generic          | 3         | 0.83%   |
| 5.10.14-desktop-1omv4002   | 3         | 0.83%   |
| 4.19.49+                   | 3         | 0.83%   |
| 6.8.7-1-cachyos            | 2         | 0.55%   |
| 6.8.2-arch2-1              | 2         | 0.55%   |
| 6.8.0-47-generic           | 2         | 0.55%   |
| 6.8.0-40-generic           | 2         | 0.55%   |
| 6.8.0-35-generic           | 2         | 0.55%   |
| 6.7.5-arch1-1              | 2         | 0.55%   |
| 6.7.4-arch1-1              | 2         | 0.55%   |
| 6.6.7-arch1-1              | 2         | 0.55%   |
| 6.5.5-arch1-1              | 2         | 0.55%   |
| 6.5.0-26-generic           | 2         | 0.55%   |
| 6.5.0-14-generic           | 2         | 0.55%   |
| 6.4.11-desktop-1omv2390    | 2         | 0.55%   |
| 6.2.0-34-generic           | 2         | 0.55%   |
| 6.1.21-valve1-3-neptune-61 | 2         | 0.55%   |
| 6.1.0-23-amd64             | 2         | 0.55%   |
| 6.1.0-11-amd64             | 2         | 0.55%   |
| 6.0.12-300.fc37.x86_64     | 2         | 0.55%   |
| 5.9.2-arch1-1              | 2         | 0.55%   |
| 5.8.0-7630-generic         | 2         | 0.55%   |
| 5.4.0-58-generic           | 2         | 0.55%   |
| 5.4.0-28-generic           | 2         | 0.55%   |
| 5.4.0-26-generic           | 2         | 0.55%   |
| 5.3.0-18-generic           | 2         | 0.55%   |
| 5.17.11-300.fc36.x86_64    | 2         | 0.55%   |
| 5.15.0-60-generic          | 2         | 0.55%   |
| 5.15.0-58-generic          | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 6%      |
| 5.15.0  | 18        | 5.14%   |
| 6.2.0   | 14        | 4%      |
| 5.19.0  | 13        | 3.71%   |
| 5.13.0  | 12        | 3.43%   |
| 6.8.0   | 10        | 2.86%   |
| 6.5.0   | 10        | 2.86%   |
| 5.8.0   | 9         | 2.57%   |
| 4.9.0   | 9         | 2.57%   |
| 6.1.0   | 7         | 2%      |
| 4.15.0  | 7         | 2%      |
| 5.11.0  | 6         | 1.71%   |
| 5.3.0   | 5         | 1.43%   |
| 5.0.0   | 5         | 1.43%   |
| 6.8.7   | 4         | 1.14%   |
| 6.6.2   | 4         | 1.14%   |
| 6.2.6   | 4         | 1.14%   |
| 5.10.0  | 4         | 1.14%   |
| 6.7.5   | 3         | 0.86%   |
| 6.6.6   | 3         | 0.86%   |
| 6.4.2   | 3         | 0.86%   |
| 6.4.11  | 3         | 0.86%   |
| 6.3.6   | 3         | 0.86%   |
| 6.1.1   | 3         | 0.86%   |
| 6.0.0   | 3         | 0.86%   |
| 5.10.14 | 3         | 0.86%   |
| 4.19.49 | 3         | 0.86%   |
| 6.9.9   | 2         | 0.57%   |
| 6.9.1   | 2         | 0.57%   |
| 6.8.9   | 2         | 0.57%   |
| 6.8.2   | 2         | 0.57%   |
| 6.8.1   | 2         | 0.57%   |
| 6.7.4   | 2         | 0.57%   |
| 6.6.7   | 2         | 0.57%   |
| 6.6.3   | 2         | 0.57%   |
| 6.5.5   | 2         | 0.57%   |
| 6.5.12  | 2         | 0.57%   |
| 6.4.7   | 2         | 0.57%   |
| 6.4.0   | 2         | 0.57%   |
| 6.12.1  | 2         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 23        | 6.82%   |
| 5.15    | 23        | 6.82%   |
| 5.4     | 21        | 6.23%   |
| 5.19    | 20        | 5.93%   |
| 6.8     | 19        | 5.64%   |
| 6.2     | 19        | 5.64%   |
| 6.6     | 16        | 4.75%   |
| 6.5     | 16        | 4.75%   |
| 5.13    | 14        | 4.15%   |
| 5.10    | 14        | 4.15%   |
| 5.11    | 13        | 3.86%   |
| 5.8     | 12        | 3.56%   |
| 6.4     | 11        | 3.26%   |
| 6.11    | 11        | 3.26%   |
| 4.9     | 11        | 3.26%   |
| 6.10    | 8         | 2.37%   |
| 5.3     | 8         | 2.37%   |
| 5.17    | 8         | 2.37%   |
| 6.9     | 7         | 2.08%   |
| 6.0     | 7         | 2.08%   |
| 4.15    | 7         | 2.08%   |
| 6.7     | 6         | 1.78%   |
| 5.9     | 6         | 1.78%   |
| 6.3     | 5         | 1.48%   |
| 5.14    | 5         | 1.48%   |
| 5.0     | 5         | 1.48%   |
| 5.7     | 4         | 1.19%   |
| 5.16    | 4         | 1.19%   |
| 6.12    | 3         | 0.89%   |
| 5.18    | 3         | 0.89%   |
| 4.19    | 3         | 0.89%   |
| 4.18    | 3         | 0.89%   |
| 5.6     | 1         | 0.3%    |
| 5.12    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 282       | 94.95%  |
| i686    | 12        | 4.04%   |
| aarch64 | 2         | 0.67%   |
| i586    | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 145       | 46.03%  |
| KDE5       | 66        | 20.95%  |
| Unknown    | 37        | 11.75%  |
| XFCE       | 14        | 4.44%   |
| KDE6       | 9         | 2.86%   |
| X-Cinnamon | 8         | 2.54%   |
| i3         | 6         | 1.9%    |
| Deepin     | 6         | 1.9%    |
| KDE        | 5         | 1.59%   |
| LXQt       | 3         | 0.95%   |
| Hyprland   | 3         | 0.95%   |
| dwm        | 3         | 0.95%   |
| Unity      | 2         | 0.63%   |
| MATE       | 2         | 0.63%   |
| Sway       | 1         | 0.32%   |
| icewm      | 1         | 0.32%   |
| fvwm       | 1         | 0.32%   |
| dwl        | 1         | 0.32%   |
| Cinnamon   | 1         | 0.32%   |
| Budgie     | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 191       | 61.81%  |
| Wayland | 98        | 31.72%  |
| Unknown | 14        | 4.53%   |
| Tty     | 6         | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 98        | 32.24%  |
| SDDM    | 72        | 23.68%  |
| GDM3    | 53        | 17.43%  |
| GDM     | 44        | 14.47%  |
| LightDM | 32        | 10.53%  |
| TDM     | 4         | 1.32%   |
| LXDM    | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 126       | 40.38%  |
| zh_CN   | 60        | 19.23%  |
| en_HK   | 56        | 17.95%  |
| Unknown | 19        | 6.09%   |
| zh_HK   | 13        | 4.17%   |
| zh_TW   | 11        | 3.53%   |
| C       | 11        | 3.53%   |
| en_GB   | 8         | 2.56%   |
| en_AU   | 2         | 0.64%   |
| zh_SG   | 1         | 0.32%   |
| ja_JP   | 1         | 0.32%   |
| it_IT   | 1         | 0.32%   |
| en_ZA   | 1         | 0.32%   |
| de_DE   | 1         | 0.32%   |
| C.UTF8  | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 222       | 73.75%  |
| BIOS | 79        | 26.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 196       | 64.47%  |
| Btrfs   | 56        | 18.42%  |
| Overlay | 20        | 6.58%   |
| Tmpfs   | 11        | 3.62%   |
| Unknown | 7         | 2.3%    |
| Xfs     | 6         | 1.97%   |
| Zfs     | 5         | 1.64%   |
| Ext2    | 2         | 0.66%   |
| Ext3    | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 196       | 64.9%   |
| Unknown | 87        | 28.81%  |
| MBR     | 19        | 6.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 262       | 87.04%  |
| Yes       | 39        | 12.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 173       | 57.28%  |
| Yes       | 129       | 42.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 100       | 33.67%  |
| ASUSTek Computer     | 34        | 11.45%  |
| Dell                 | 28        | 9.43%   |
| Hewlett-Packard      | 22        | 7.41%   |
| Fujitsu              | 14        | 4.71%   |
| Acer                 | 14        | 4.71%   |
| Unknown              | 11        | 3.7%    |
| Apple                | 10        | 3.37%   |
| HUAWEI               | 7         | 2.36%   |
| MECHREVO             | 6         | 2.02%   |
| GPD                  | 5         | 1.68%   |
| Chuwi                | 5         | 1.68%   |
| Samsung Electronics  | 4         | 1.35%   |
| Timi                 | 3         | 1.01%   |
| MSI                  | 3         | 1.01%   |
| Valve                | 2         | 0.67%   |
| Toshiba              | 2         | 0.67%   |
| Sony                 | 2         | 0.67%   |
| Notebook             | 2         | 0.67%   |
| KOHJINSHA            | 2         | 0.67%   |
| IBM                  | 2         | 0.67%   |
| Google               | 2         | 0.67%   |
| AMI                  | 2         | 0.67%   |
| System76             | 1         | 0.34%   |
| Schenker             | 1         | 0.34%   |
| Panasonic            | 1         | 0.34%   |
| ONE-NETBOOK          | 1         | 0.34%   |
| Nexstgo              | 1         | 0.34%   |
| METAPHYUNI           | 1         | 0.34%   |
| MACHENIKE            | 1         | 0.34%   |
| LG Electronics       | 1         | 0.34%   |
| KUU                  | 1         | 0.34%   |
| Jumper               | 1         | 0.34%   |
| Intel Client Systems | 1         | 0.34%   |
| HONOR                | 1         | 0.34%   |
| HASEE Computer       | 1         | 0.34%   |
| Compaq               | 1         | 0.34%   |
| Alienware            | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 12        | 4.04%   |
| Lenovo LOQ 15IRH8 82XV              | 4         | 1.35%   |
| MECHREVO WUJIE14 PRO                | 3         | 1.01%   |
| Lenovo Legion R7000 2020 82B6       | 3         | 1.01%   |
| GPD G1619-04                        | 3         | 1.01%   |
| Chuwi HeroBook Pro                  | 3         | 1.01%   |
| Valve Jupiter                       | 2         | 0.67%   |
| Lenovo XiaoXinPro 14ITL 2021 82GH   | 2         | 0.67%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0    | 2         | 0.67%   |
| Lenovo Legion R9000P ARX8 82WM      | 2         | 0.67%   |
| Lenovo G770 20089                   | 2         | 0.67%   |
| IBM 260921H                         | 2         | 0.67%   |
| HUAWEI KPRC-WX0                     | 2         | 0.67%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC    | 2         | 0.67%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.67%   |
| HP OMEN by Gaming Laptop 16-wf0xxx  | 2         | 0.67%   |
| HP EliteBook 2540p                  | 2         | 0.67%   |
| Fujitsu UH-X                        | 2         | 0.67%   |
| Fujitsu LIFEBOOK AH544              | 2         | 0.67%   |
| Fujitsu FMVNU6G1C                   | 2         | 0.67%   |
| Dell XPS 13 9310                    | 2         | 0.67%   |
| Dell Inspiron 5580                  | 2         | 0.67%   |
| ASUS TUF Gaming FA506IU_FA506IU     | 2         | 0.67%   |
| Apple MacBookAir6,2                 | 2         | 0.67%   |
| Apple MacBookAir5,2                 | 2         | 0.67%   |
| Apple MacBook10,1                   | 2         | 0.67%   |
| Acer Swift SF314-512                | 2         | 0.67%   |
| Toshiba PORTEGE R830                | 1         | 0.34%   |
| Toshiba dynabook R731/E             | 1         | 0.34%   |
| Timi TM1613                         | 1         | 0.34%   |
| Timi TM1607                         | 1         | 0.34%   |
| Timi A35                            | 1         | 0.34%   |
| System76 Bonobo WS                  | 1         | 0.34%   |
| Sony VPCCB17FG                      | 1         | 0.34%   |
| Sony VGN-TZ27GN_B                   | 1         | 0.34%   |
| Schenker XMG_APEX15_XAP15E20        | 1         | 0.34%   |
| Samsung SQ1S                        | 1         | 0.34%   |
| Samsung 950XCJ/951XCJ/950XCR        | 1         | 0.34%   |
| Samsung 930XBE                      | 1         | 0.34%   |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 45        | 15.15%  |
| Lenovo Legion     | 15        | 5.05%   |
| Unknown           | 12        | 4.04%   |
| Lenovo IdeaPad    | 10        | 3.37%   |
| Dell XPS          | 10        | 3.37%   |
| Lenovo ThinkBook  | 9         | 3.03%   |
| Fujitsu LIFEBOOK  | 9         | 3.03%   |
| ASUS ROG          | 9         | 3.03%   |
| Dell Inspiron     | 8         | 2.69%   |
| Acer Swift        | 7         | 2.36%   |
| ASUS VivoBook     | 6         | 2.02%   |
| Dell Latitude     | 5         | 1.68%   |
| Lenovo LOQ        | 4         | 1.35%   |
| HP Pavilion       | 4         | 1.35%   |
| Dell Precision    | 4         | 1.35%   |
| ASUS ASUS         | 4         | 1.35%   |
| Acer Aspire       | 4         | 1.35%   |
| MECHREVO WUJIE14  | 3         | 1.01%   |
| Lenovo XiaoXinPro | 3         | 1.01%   |
| HP ZHAN           | 3         | 1.01%   |
| HP OMEN           | 3         | 1.01%   |
| HP EliteBook      | 3         | 1.01%   |
| GPD G1619-04      | 3         | 1.01%   |
| Chuwi HeroBook    | 3         | 1.01%   |
| ASUS TUF          | 3         | 1.01%   |
| Apple MacBookAir5 | 3         | 1.01%   |
| Acer Nitro        | 3         | 1.01%   |
| Valve Jupiter     | 2         | 0.67%   |
| Lenovo ZHAOYANG   | 2         | 0.67%   |
| Lenovo G770       | 2         | 0.67%   |
| IBM 260921H       | 2         | 0.67%   |
| HUAWEI KPRC-WX0   | 2         | 0.67%   |
| Fujitsu UH-X      | 2         | 0.67%   |
| Fujitsu FMVNU6G1C | 2         | 0.67%   |
| Apple MacBookAir6 | 2         | 0.67%   |
| Apple MacBook10   | 2         | 0.67%   |
| Toshiba PORTEGE   | 1         | 0.34%   |
| Toshiba dynabook  | 1         | 0.34%   |
| Timi TM1613       | 1         | 0.34%   |
| Timi TM1607       | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 39        | 13.13%  |
| 2018    | 37        | 12.46%  |
| 2023    | 34        | 11.45%  |
| 2021    | 32        | 10.77%  |
| 2022    | 25        | 8.42%   |
| 2019    | 22        | 7.41%   |
| 2017    | 14        | 4.71%   |
| 2012    | 13        | 4.38%   |
| 2011    | 13        | 4.38%   |
| 2013    | 10        | 3.37%   |
| 2014    | 9         | 3.03%   |
| 2024    | 8         | 2.69%   |
| 2015    | 7         | 2.36%   |
| 2010    | 7         | 2.36%   |
| 2008    | 7         | 2.36%   |
| 2016    | 6         | 2.02%   |
| 2007    | 6         | 2.02%   |
| 2009    | 2         | 0.67%   |
| 1999    | 2         | 0.67%   |
| Unknown | 2         | 0.67%   |
| 2005    | 1         | 0.34%   |
| 2003    | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 297       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 256       | 85.62%  |
| Enabled  | 43        | 14.38%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 294       | 98.99%  |
| Yes  | 3         | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 67        | 22.41%  |
| 8.01-16.0   | 59        | 19.73%  |
| 4.01-8.0    | 55        | 18.39%  |
| 32.01-64.0  | 48        | 16.05%  |
| 3.01-4.0    | 26        | 8.7%    |
| 24.01-32.0  | 14        | 4.68%   |
| 64.01-256.0 | 12        | 4.01%   |
| 1.01-2.0    | 6         | 2.01%   |
| 2.01-3.0    | 5         | 1.67%   |
| 0.51-1.0    | 5         | 1.67%   |
| 0.01-0.5    | 2         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 76        | 23.24%  |
| 2.01-3.0   | 76        | 23.24%  |
| 1.01-2.0   | 64        | 19.57%  |
| 3.01-4.0   | 52        | 15.9%   |
| 8.01-16.0  | 29        | 8.87%   |
| 0.01-0.5   | 16        | 4.89%   |
| 0.51-1.0   | 7         | 2.14%   |
| 16.01-24.0 | 6         | 1.83%   |
| 24.01-32.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 182       | 59.28%  |
| 2      | 101       | 32.9%   |
| 3      | 19        | 6.19%   |
| 0      | 4         | 1.3%    |
| 5      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 258       | 86%     |
| Yes       | 42        | 14%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 68%     |
| No        | 96        | 32%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 289       | 97.31%  |
| No        | 8         | 2.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 250       | 83.33%  |
| No        | 50        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Hong Kong | 297       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Central           | 167       | 53.35%  |
| Wanchai           | 17        | 5.43%   |
| Kowloon           | 17        | 5.43%   |
| Hong Kong         | 14        | 4.47%   |
| Shatin            | 11        | 3.51%   |
| Tsuen Wan         | 8         | 2.56%   |
| Tseung Kwan O     | 6         | 1.92%   |
| Tai Po            | 6         | 1.92%   |
| Tung Chung        | 5         | 1.6%    |
| Mong Kok          | 5         | 1.6%    |
| Hung Hom          | 5         | 1.6%    |
| Tuen Mun          | 4         | 1.28%   |
| Sai Kung          | 4         | 1.28%   |
| Tsimshatsui       | 3         | 0.96%   |
| Man Kok           | 3         | 0.96%   |
| Yuen Long San Hui | 2         | 0.64%   |
| Wan Chai          | 2         | 0.64%   |
| Shau Kei Wan      | 2         | 0.64%   |
| Quarry Bay        | 2         | 0.64%   |
| Ngau Wu Tok       | 2         | 0.64%   |
| Fanling           | 2         | 0.64%   |
| Discovery Bay     | 2         | 0.64%   |
| Yuen Long         | 1         | 0.32%   |
| Yau Tsim Mong     | 1         | 0.32%   |
| Wong Tai Sin      | 1         | 0.32%   |
| Tuen Mun San Hui  | 1         | 0.32%   |
| Tsing Yi Town     | 1         | 0.32%   |
| To Kwa Wan        | 1         | 0.32%   |
| Tin Shui Wai      | 1         | 0.32%   |
| The Peak          | 1         | 0.32%   |
| Tai Wan To        | 1         | 0.32%   |
| Tai Wan           | 1         | 0.32%   |
| So Kon Po         | 1         | 0.32%   |
| Sheung Shui       | 1         | 0.32%   |
| North Point       | 1         | 0.32%   |
| North             | 1         | 0.32%   |
| Ma On Shan        | 1         | 0.32%   |
| Lam Tin           | 1         | 0.32%   |
| Kwun Hang         | 1         | 0.32%   |
| Kwai Chung        | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 88        | 110    | 21.52%  |
| WDC                         | 36        | 47     | 8.8%    |
| Sandisk                     | 32        | 36     | 7.82%   |
| Unknown                     | 24        | 29     | 5.87%   |
| Seagate                     | 20        | 24     | 4.89%   |
| Micron Technology           | 18        | 20     | 4.4%    |
| Intel                       | 17        | 22     | 4.16%   |
| SK hynix                    | 16        | 19     | 3.91%   |
| Apple                       | 11        | 31     | 2.69%   |
| Toshiba                     | 10        | 10     | 2.44%   |
| Hitachi                     | 10        | 10     | 2.44%   |
| KIOXIA                      | 9         | 9      | 2.2%    |
| Kingston                    | 9         | 10     | 2.2%    |
| Crucial                     | 8         | 16     | 1.96%   |
| HGST                        | 7         | 8      | 1.71%   |
| Yangtze Memory Technologies | 6         | 7      | 1.47%   |
| MAXIO Technology (Hangzhou) | 5         | 5      | 1.22%   |
| Fujitsu                     | 4         | 6      | 0.98%   |
| China                       | 4         | 6      | 0.98%   |
| Phison                      | 3         | 3      | 0.73%   |
| JMicron Technology          | 3         | 4      | 0.73%   |
| BIWIN                       | 3         | 3      | 0.73%   |
| ZHITAI                      | 2         | 2      | 0.49%   |
| Yangtze Memory              | 2         | 2      | 0.49%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.49%   |
| Transcend                   | 2         | 2      | 0.49%   |
| TO Exter                    | 2         | 2      | 0.49%   |
| Plextor                     | 2         | 3      | 0.49%   |
| LITEON                      | 2         | 2      | 0.49%   |
| Lenovo                      | 2         | 2      | 0.49%   |
| Kingston Technology Company | 2         | 2      | 0.49%   |
| KingSpec                    | 2         | 3      | 0.49%   |
| HS-SSD-C100                 | 2         | 3      | 0.49%   |
| Hikvision                   | 2         | 2      | 0.49%   |
| External                    | 2         | 2      | 0.49%   |
| Biwin Storage Technology    | 2         | 3      | 0.49%   |
| A-DATA Technology           | 2         | 2      | 0.49%   |
| Unknown                     | 2         | 3      | 0.49%   |
| ZX1 1TB                     | 1         | 1      | 0.24%   |
| YMTC                        | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 10        | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 8         | 1.88%   |
| Unknown MMC Card  64GB                               | 6         | 1.41%   |
| Samsung SSD 980 1TB                                  | 6         | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB                       | 5         | 1.17%   |
| SanDisk NVMe SSD Drive 2TB                           | 5         | 1.17%   |
| Unknown MMC Card  128GB                              | 4         | 0.94%   |
| Samsung MZAL41T0HBLB-00BL2 1TB                       | 4         | 0.94%   |
| WDC WDS100T2B0C-00PXH0 1TB                           | 3         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB                       | 3         | 0.7%    |
| SanDisk NVMe SSD Drive 512GB                         | 3         | 0.7%    |
| SanDisk NVMe SSD Drive 1TB                           | 3         | 0.7%    |
| SanDisk DF4064  64GB                                 | 3         | 0.7%    |
| Samsung SSD 990 PRO 1TB                              | 3         | 0.7%    |
| Samsung NVMe SSD Drive 512GB                         | 3         | 0.7%    |
| Samsung MZVL2512HCJQ-00BL2 512GB                     | 3         | 0.7%    |
| Micron 3400_MTFDKBA512TFH 512GB                      | 3         | 0.7%    |
| Yangtze Memory ZHITAI PC005 Active 1TB               | 2         | 0.47%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                 | 2         | 0.47%   |
| Yangtze Memory YMTC PC300-1TB-B                      | 2         | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 2         | 0.47%   |
| WDC WD10SPZX-24Z10T0 1TB                             | 2         | 0.47%   |
| WDC WD10SPZX-22Z10T1 1TB                             | 2         | 0.47%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                 | 2         | 0.47%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB                 | 2         | 0.47%   |
| Unknown NVMe SSD Drive 1TB                           | 2         | 0.47%   |
| Unknown NVMe SSD Drive 1024GB                        | 2         | 0.47%   |
| Toshiba MQ04ABF100 1TB                               | 2         | 0.47%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 0.47%   |
| TO Exter nal USB 3.0 1024GB                          | 2         | 0.47%   |
| SK hynix BC501 NVMe 128GB                            | 2         | 0.47%   |
| Seagate ST500LT012-9WS142 500GB                      | 2         | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 2         | 0.47%   |
| Sandisk WD PC SN740 SDDPTQE-2T00 2TB                 | 2         | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 2         | 0.47%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 2         | 0.47%   |
| SanDisk NVMe SSD Drive 256GB                         | 2         | 0.47%   |
| Samsung SSD 990 PRO 2TB                              | 2         | 0.47%   |
| Samsung SSD 970 EVO Plus 2TB                         | 2         | 0.47%   |
| Samsung NVMe SSD Drive 1TB                           | 2         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 24     | 28.99%  |
| WDC                 | 17        | 24     | 24.64%  |
| Hitachi             | 10        | 10     | 14.49%  |
| HGST                | 7         | 8      | 10.14%  |
| Toshiba             | 5         | 5      | 7.25%   |
| JMicron Technology  | 3         | 4      | 4.35%   |
| TO Exter            | 2         | 2      | 2.9%    |
| External            | 2         | 2      | 2.9%    |
| Unknown (CF)        | 1         | 1      | 1.45%   |
| Samsung Electronics | 1         | 1      | 1.45%   |
| Fujitsu             | 1         | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 24     | 19.51%  |
| Crucial             | 7         | 15     | 8.54%   |
| WDC                 | 6         | 6      | 7.32%   |
| Intel               | 6         | 9      | 7.32%   |
| Apple               | 6         | 11     | 7.32%   |
| Kingston            | 5         | 5      | 6.1%    |
| China               | 4         | 6      | 4.88%   |
| SanDisk             | 3         | 3      | 3.66%   |
| Micron Technology   | 3         | 4      | 3.66%   |
| Transcend           | 2         | 2      | 2.44%   |
| SK hynix            | 2         | 2      | 2.44%   |
| Plextor             | 2         | 3      | 2.44%   |
| LITEON              | 2         | 2      | 2.44%   |
| Fujitsu             | 2         | 4      | 2.44%   |
| Verbatim            | 1         | 2      | 1.22%   |
| USB3.0              | 1         | 1      | 1.22%   |
| Team                | 1         | 1      | 1.22%   |
| ShiJi               | 1         | 17     | 1.22%   |
| RECADATA            | 1         | 1      | 1.22%   |
| Ramsta              | 1         | 1      | 1.22%   |
| Netac               | 1         | 1      | 1.22%   |
| Lexar               | 1         | 1      | 1.22%   |
| Lenovo              | 1         | 1      | 1.22%   |
| KLEVV               | 1         | 1      | 1.22%   |
| HS-SSD-C100         | 1         | 1      | 1.22%   |
| Hikvision           | 1         | 1      | 1.22%   |
| DGM                 | 1         | 1      | 1.22%   |
| BIWIN               | 1         | 1      | 1.22%   |
| Apacer              | 1         | 4      | 1.22%   |
| A-DATA Technology   | 1         | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 184       | 265    | 50.69%  |
| SSD     | 73        | 132    | 20.11%  |
| HDD     | 67        | 82     | 18.46%  |
| MMC     | 23        | 29     | 6.34%   |
| Unknown | 16        | 19     | 4.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 184       | 261    | 51.83%  |
| SATA | 124       | 208    | 34.93%  |
| SAS  | 24        | 29     | 6.76%   |
| MMC  | 23        | 29     | 6.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 121    | 60%     |
| 0.51-1.0   | 45        | 79     | 32.14%  |
| 1.01-2.0   | 11        | 14     | 7.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 22.26%  |
| 251-500        | 63        | 19.75%  |
| 501-1000       | 56        | 17.55%  |
| 1001-2000      | 32        | 10.03%  |
| 1-20           | 31        | 9.72%   |
| 51-100         | 23        | 7.21%   |
| 21-50          | 15        | 4.7%    |
| More than 3000 | 13        | 4.08%   |
| 2001-3000      | 9         | 2.82%   |
| Unknown        | 6         | 1.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 124       | 38.04%  |
| 21-50          | 45        | 13.8%   |
| 101-250        | 44        | 13.5%   |
| 251-500        | 37        | 11.35%  |
| 51-100         | 35        | 10.74%  |
| 501-1000       | 19        | 5.83%   |
| 1001-2000      | 13        | 3.99%   |
| Unknown        | 6         | 1.84%   |
| More than 3000 | 2         | 0.61%   |
| 2001-3000      | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| LITEON CV8-8E128-HP 128GB SSD                       | 2         | 2      | 11.11%  |
| WDC WD20SPZX-75UA7T0 2TB                            | 1         | 2      | 5.56%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 5.56%   |
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
| Seagate             | 3         | 3      | 16.67%  |
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
| Seagate | 3         | 3      | 37.5%   |
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
| HDD  | 8         | 9      | 44.44%  |

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
| Works    | 174       | 289    | 53.87%  |
| Detected | 131       | 219    | 40.56%  |
| Malfunc  | 18        | 19     | 5.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 163       | 42.01%  |
| Samsung Electronics                     | 75        | 19.33%  |
| SanDisk                                 | 40        | 10.31%  |
| Micron Technology                       | 16        | 4.12%   |
| AMD                                     | 16        | 4.12%   |
| SK hynix                                | 14        | 3.61%   |
| Yangtze Memory Technologies             | 10        | 2.58%   |
| Toshiba America Info Systems            | 7         | 1.8%    |
| MAXIO Technology (Hangzhou)             | 7         | 1.8%    |
| KIOXIA                                  | 7         | 1.8%    |
| Kingston Technology Company             | 6         | 1.55%   |
| Silicon Motion                          | 4         | 1.03%   |
| Phison Electronics                      | 4         | 1.03%   |
| INNOGRIT                                | 3         | 0.77%   |
| Biwin Storage Technology                | 3         | 0.77%   |
| Apple                                   | 3         | 0.77%   |
| Shenzhen Unionmemory Information System | 2         | 0.52%   |
| VIA Technologies                        | 1         | 0.26%   |
| Solidigm                                | 1         | 0.26%   |
| Solid State Storage Technology          | 1         | 0.26%   |
| Realtek Semiconductor                   | 1         | 0.26%   |
| Nvidia                                  | 1         | 0.26%   |
| Micron/Crucial Technology               | 1         | 0.26%   |
| Marvell Technology Group                | 1         | 0.26%   |
| Lenovo                                  | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25        | 6.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 4.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 4.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 3.89%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 3.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 3.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 10        | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 2.43%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 8         | 1.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.95%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 7         | 1.7%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 7         | 1.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.7%    |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 6         | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 6         | 1.46%   |
| Intel SSD 660P Series                                                          | 6         | 1.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 1.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.46%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 5         | 1.22%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 1.22%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 5         | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 1.22%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 4         | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 0.97%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.97%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.97%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 4         | 0.97%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 4         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.97%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.73%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 0.73%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.73%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.73%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 3         | 0.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 184       | 50.14%  |
| SATA | 131       | 35.69%  |
| RAID | 32        | 8.72%   |
| IDE  | 20        | 5.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 229       | 77.1%   |
| AMD          | 65        | 21.89%  |
| Unknown      | 2         | 0.67%   |
| GenuineTMx86 | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 2.36%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 2.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 2.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.68%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 5         | 1.68%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 1.68%   |
| Intel Core Ultra 7 155H                       | 4         | 1.35%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.35%   |
| Intel 13th Gen Core i9-13900HX                | 4         | 1.35%   |
| Intel 13th Gen Core i5-13420H                 | 4         | 1.35%   |
| AMD Ryzen 9 7945HX with Radeon Graphics       | 4         | 1.35%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 1.35%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 4         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.01%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 1.01%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.01%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.01%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.01%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.01%   |
| Intel 13th Gen Core i9-13900H                 | 3         | 1.01%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.01%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.01%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 3         | 1.01%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 3         | 1.01%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.01%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.01%   |
| Intel Genuine processor 800MHz                | 2         | 0.67%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 59        | 19.87%  |
| Intel Core i5           | 58        | 19.53%  |
| Other                   | 53        | 17.85%  |
| AMD Ryzen 7             | 33        | 11.11%  |
| Intel Celeron           | 20        | 6.73%   |
| Intel Core i3           | 13        | 4.38%   |
| AMD Ryzen 9             | 12        | 4.04%   |
| AMD Ryzen 5             | 9         | 3.03%   |
| Intel Core              | 7         | 2.36%   |
| AMD Ryzen 7 PRO         | 7         | 2.36%   |
| Intel Atom              | 5         | 1.68%   |
| Intel Core m3           | 4         | 1.35%   |
| Intel Core 2 Duo        | 4         | 1.35%   |
| Intel Xeon              | 2         | 0.67%   |
| Intel Pentium Dual-Core | 2         | 0.67%   |
| Intel Genuine           | 2         | 0.67%   |
| Intel Core 2            | 2         | 0.67%   |
| Intel Pentium M         | 1         | 0.34%   |
| Intel Pentium Gold      | 1         | 0.34%   |
| Intel Pentium Dual      | 1         | 0.34%   |
| Intel Core i9           | 1         | 0.34%   |
| AMD Quad-Core           | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 88        | 29.63%  |
| 4      | 87        | 29.29%  |
| 8      | 56        | 18.86%  |
| 6      | 19        | 6.4%    |
| 14     | 10        | 3.37%   |
| 12     | 10        | 3.37%   |
| 1      | 10        | 3.37%   |
| 16     | 9         | 3.03%   |
| 24     | 5         | 1.68%   |
| 10     | 3         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 297       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 248       | 83.22%  |
| 1      | 50        | 16.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 94.28%  |
| 32-bit         | 10        | 3.37%   |
| Unknown        | 5         | 1.68%   |
| 64-bit         | 2         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 42.35%  |
| 0x806e9    | 11        | 3.58%   |
| 0x806ea    | 10        | 3.26%   |
| 0x206a7    | 10        | 3.26%   |
| 0x906ea    | 9         | 2.93%   |
| 0x806c1    | 7         | 2.28%   |
| 0x306a9    | 7         | 2.28%   |
| 0x08600106 | 7         | 2.28%   |
| 0x806ec    | 6         | 1.95%   |
| 0x706e5    | 6         | 1.95%   |
| 0x506c9    | 6         | 1.95%   |
| 0x406e3    | 6         | 1.95%   |
| 0x0a50000c | 6         | 1.95%   |
| 0x0a404102 | 6         | 1.95%   |
| 0xa0652    | 5         | 1.63%   |
| 0x806eb    | 5         | 1.63%   |
| 0x40651    | 5         | 1.63%   |
| 0x106c2    | 4         | 1.3%    |
| 0xb0671    | 3         | 0.98%   |
| 0x906a3    | 3         | 0.98%   |
| 0x806d1    | 3         | 0.98%   |
| 0x706a8    | 3         | 0.98%   |
| 0x306c3    | 3         | 0.98%   |
| 0x20655    | 3         | 0.98%   |
| 0x1067a    | 3         | 0.98%   |
| 0x08600104 | 3         | 0.98%   |
| 0x08108102 | 3         | 0.98%   |
| 0x906e9    | 2         | 0.65%   |
| 0x6fd      | 2         | 0.65%   |
| 0x6d8      | 2         | 0.65%   |
| 0x66a      | 2         | 0.65%   |
| 0x506e3    | 2         | 0.65%   |
| 0x306d4    | 2         | 0.65%   |
| 0x0a601203 | 2         | 0.65%   |
| 0x0a50000b | 2         | 0.65%   |
| 0x08600103 | 2         | 0.65%   |
| 0x906c0    | 1         | 0.33%   |
| 0x706a1    | 1         | 0.33%   |
| 0x6fb      | 1         | 0.33%   |
| 0x6f6      | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 60        | 20.13%  |
| Unknown           | 46        | 15.44%  |
| Alderlake Hybrid  | 19        | 6.38%   |
| Zen 2             | 16        | 5.37%   |
| TigerLake         | 16        | 5.37%   |
| SandyBridge       | 15        | 5.03%   |
| Zen 3             | 14        | 4.7%    |
| Skylake           | 14        | 4.7%    |
| IvyBridge         | 14        | 4.7%    |
| Haswell           | 14        | 4.7%    |
| IceLake           | 11        | 3.69%   |
| Goldmont plus     | 7         | 2.35%   |
| Goldmont          | 6         | 2.01%   |
| CometLake         | 6         | 2.01%   |
| Westmere          | 5         | 1.68%   |
| Meteorlake Hybrid | 5         | 1.68%   |
| Core              | 5         | 1.68%   |
| Zen+              | 4         | 1.34%   |
| Penryn            | 4         | 1.34%   |
| Broadwell         | 4         | 1.34%   |
| Bonnell           | 4         | 1.34%   |
| P6                | 3         | 1.01%   |
| Silvermont        | 2         | 0.67%   |
| Tremont           | 1         | 0.34%   |
| Lunarlake Hybrid  | 1         | 0.34%   |
| Jaguar            | 1         | 0.34%   |
| Gracemont         | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 217       | 55.08%  |
| Nvidia      | 104       | 26.4%   |
| AMD         | 70        | 17.77%  |
| Neomagic    | 2         | 0.51%   |
| S3 Graphics | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                        | 17        | 4.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 15        | 3.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 14        | 3.47%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 14        | 3.47%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 13        | 3.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 11        | 2.72%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 11        | 2.72%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 11        | 2.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 10        | 2.48%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 10        | 2.48%   |
| AMD Rembrandt [Radeon 680M]                                                   | 10        | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 9         | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 8         | 1.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 1.73%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 7         | 1.73%   |
| AMD Phoenix3                                                                  | 7         | 1.73%   |
| Nvidia GP108M [GeForce MX150]                                                 | 6         | 1.49%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                               | 6         | 1.49%   |
| Intel HD Graphics 620                                                         | 6         | 1.49%   |
| Intel HD Graphics 500                                                         | 6         | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 6         | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 1.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 1.24%   |
| Intel Raptor Lake-P [UHD Graphics]                                            | 5         | 1.24%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 5         | 1.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 5         | 1.24%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                      | 5         | 1.24%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 5         | 1.24%   |
| Intel HD Graphics 615                                                         | 5         | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 0.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 0.99%   |
| Intel HD Graphics 5500                                                        | 4         | 0.99%   |
| Intel HD Graphics 530                                                         | 4         | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 0.99%   |
| AMD Raphael                                                                   | 4         | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 0.99%   |
| AMD Phoenix1                                                                  | 4         | 0.99%   |
| Nvidia TU117M [GeForce MX450]                                                 | 3         | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 3         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 138       | 46.15%  |
| Intel + Nvidia  | 71        | 23.75%  |
| 1 x AMD         | 40        | 13.38%  |
| AMD + Nvidia    | 21        | 7.02%   |
| 1 x Nvidia      | 13        | 4.35%   |
| Intel + AMD     | 8         | 2.68%   |
| Other           | 2         | 0.67%   |
| 2 x AMD         | 2         | 0.67%   |
| 1 x Neomagic    | 2         | 0.67%   |
| 2 x Intel       | 1         | 0.33%   |
| 1 x S3 Graphics | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 221       | 73.67%  |
| Proprietary | 62        | 20.67%  |
| Unknown     | 17        | 5.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 201       | 67%     |
| 0.01-0.5   | 30        | 10%     |
| 1.01-2.0   | 25        | 8.33%   |
| 3.01-4.0   | 13        | 4.33%   |
| 7.01-8.0   | 10        | 3.33%   |
| 0.51-1.0   | 10        | 3.33%   |
| 5.01-6.0   | 9         | 3%      |
| 2.01-3.0   | 2         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 65        | 20.12%  |
| AU Optronics            | 50        | 15.48%  |
| LG Display              | 38        | 11.76%  |
| Chimei Innolux          | 30        | 9.29%   |
| Samsung Electronics     | 24        | 7.43%   |
| Sharp                   | 14        | 4.33%   |
| Dell                    | 11        | 3.41%   |
| Apple                   | 10        | 3.1%    |
| AOC                     | 10        | 3.1%    |
| CSO                     | 7         | 2.17%   |
| Lenovo                  | 6         | 1.86%   |
| TMA                     | 5         | 1.55%   |
| JDI                     | 5         | 1.55%   |
| Philips                 | 4         | 1.24%   |
| PANDA                   | 3         | 0.93%   |
| Mi                      | 3         | 0.93%   |
| InfoVision              | 3         | 0.93%   |
| Goldstar                | 3         | 0.93%   |
| Valve                   | 2         | 0.62%   |
| TMX                     | 2         | 0.62%   |
| LG Philips              | 2         | 0.62%   |
| IPS                     | 2         | 0.62%   |
| HKC                     | 2         | 0.62%   |
| CPT                     | 2         | 0.62%   |
| Chi Mei Optoelectronics | 2         | 0.62%   |
| Unknown (DAE)           | 1         | 0.31%   |
| TUO                     | 1         | 0.31%   |
| SOY                     | 1         | 0.31%   |
| Sony                    | 1         | 0.31%   |
| SAC                     | 1         | 0.31%   |
| RGT                     | 1         | 0.31%   |
| MStar                   | 1         | 0.31%   |
| Lenovo Group Limited    | 1         | 0.31%   |
| JXC                     | 1         | 0.31%   |
| ITE                     | 1         | 0.31%   |
| Intehill                | 1         | 0.31%   |
| InnoLux Display         | 1         | 0.31%   |
| Hewlett-Packard         | 1         | 0.31%   |
| GBE                     | 1         | 0.31%   |
| BenQ                    | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| TMA TL140ADXP24-0 TMA2004 2880x1800 300x190mm 14.0-inch               | 5         | 1.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 1.22%   |
| BOE LCD Monitor BOE0AE3 1920x1080 344x194mm 15.5-inch                 | 4         | 1.22%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 4         | 1.22%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 3         | 0.92%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 3         | 0.92%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 0.92%   |
| AU Optronics LCD Monitor AUOC391 2880x1800 301x188mm 14.0-inch        | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 0.92%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 0.92%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.61%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SDC419F 2880x1800 302x189mm 14.0-inch | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 2         | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.61%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.61%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.61%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.61%   |
| IPS R240 IPS2380 1920x1080 526x296mm 23.8-inch                        | 2         | 0.61%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 381x214mm 17.2-inch                 | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 0.61%   |
| BOE LCD Monitor BOE0B7D 2560x1440 355x200mm 16.0-inch                 | 2         | 0.61%   |
| BOE LCD Monitor BOE0B11 2560x1600 345x215mm 16.0-inch                 | 2         | 0.61%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.61%   |
| AU Optronics LCD Monitor AUOA195 2240x1400 300x188mm 13.9-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch        | 2         | 0.61%   |
| Apple Color LCD APPA027 2304x1440 259x162mm 12.0-inch                 | 2         | 0.61%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 2         | 0.61%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 2         | 0.61%   |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 129       | 41.88%  |
| 1366x768 (WXGA)   | 36        | 11.69%  |
| 3840x2160 (4K)    | 21        | 6.82%   |
| 2560x1600         | 19        | 6.17%   |
| 2560x1440 (QHD)   | 19        | 6.17%   |
| 2880x1800         | 15        | 4.87%   |
| 1600x900 (HD+)    | 8         | 2.6%    |
| 1440x900 (WXGA+)  | 6         | 1.95%   |
| 1280x800 (WXGA)   | 6         | 1.95%   |
| 1920x1200 (WUXGA) | 5         | 1.62%   |
| 3840x2400         | 4         | 1.3%    |
| 2240x1400         | 4         | 1.3%    |
| 3200x2000         | 3         | 0.97%   |
| 3000x2000         | 3         | 0.97%   |
| Unknown           | 3         | 0.97%   |
| 800x1280          | 2         | 0.65%   |
| 3456x2160         | 2         | 0.65%   |
| 3440x1440         | 2         | 0.65%   |
| 3200x1800 (QHD+)  | 2         | 0.65%   |
| 2880x1920         | 2         | 0.65%   |
| 2880x1620         | 2         | 0.65%   |
| 2400x1600         | 2         | 0.65%   |
| 2304x1440         | 2         | 0.65%   |
| 2160x1440         | 2         | 0.65%   |
| 3840x1600         | 1         | 0.32%   |
| 3840x1100         | 1         | 0.32%   |
| 3520x1080         | 1         | 0.32%   |
| 3072x1920         | 1         | 0.32%   |
| 2560x1080         | 1         | 0.32%   |
| 2256x1504         | 1         | 0.32%   |
| 1600x2560         | 1         | 0.32%   |
| 1024x600          | 1         | 0.32%   |
| 1024x576          | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 87        | 26.93%  |
| 14      | 60        | 18.58%  |
| 13      | 57        | 17.65%  |
| 16      | 18        | 5.57%   |
| 12      | 17        | 5.26%   |
| 27      | 13        | 4.02%   |
| 17      | 13        | 4.02%   |
| 24      | 10        | 3.1%    |
| 21      | 8         | 2.48%   |
| 23      | 6         | 1.86%   |
| Unknown | 5         | 1.55%   |
| 40      | 4         | 1.24%   |
| 31      | 4         | 1.24%   |
| 34      | 3         | 0.93%   |
| 10      | 3         | 0.93%   |
| 20      | 2         | 0.62%   |
| 11      | 2         | 0.62%   |
| 8       | 2         | 0.62%   |
| 7       | 2         | 0.62%   |
| 72      | 1         | 0.31%   |
| 52      | 1         | 0.31%   |
| 43      | 1         | 0.31%   |
| 37      | 1         | 0.31%   |
| 26      | 1         | 0.31%   |
| 19      | 1         | 0.31%   |
| 18      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 173       | 53.89%  |
| 201-300     | 65        | 20.25%  |
| 501-600     | 29        | 9.03%   |
| 351-400     | 18        | 5.61%   |
| 401-500     | 11        | 3.43%   |
| 801-900     | 5         | 1.56%   |
| 601-700     | 5         | 1.56%   |
| Unknown     | 5         | 1.56%   |
| 701-800     | 3         | 0.93%   |
| 101-200     | 2         | 0.62%   |
| 1-100       | 2         | 0.62%   |
| 1501-2000   | 1         | 0.31%   |
| 1001-1500   | 1         | 0.31%   |
| 901-1000    | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 209       | 71.09%  |
| 16/10   | 62        | 21.09%  |
| 3/2     | 11        | 3.74%   |
| 21/9    | 4         | 1.36%   |
| Unknown | 3         | 1.02%   |
| 0.67    | 2         | 0.68%   |
| 0.62    | 2         | 0.68%   |
| 3.40    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 89        | 27.47%  |
| 101-110        | 88        | 27.16%  |
| 71-80          | 27        | 8.33%   |
| 201-250        | 20        | 6.17%   |
| 61-70          | 16        | 4.94%   |
| 111-120        | 16        | 4.94%   |
| 301-350        | 14        | 4.32%   |
| 121-130        | 13        | 4.01%   |
| 351-500        | 8         | 2.47%   |
| 151-200        | 6         | 1.85%   |
| 501-1000       | 5         | 1.54%   |
| Unknown        | 5         | 1.54%   |
| 1-40           | 4         | 1.23%   |
| 51-60          | 3         | 0.93%   |
| 41-50          | 3         | 0.93%   |
| 91-100         | 3         | 0.93%   |
| More than 1000 | 2         | 0.62%   |
| 251-300        | 2         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 125       | 39.94%  |
| 161-240       | 67        | 21.41%  |
| 101-120       | 45        | 14.38%  |
| More than 240 | 38        | 12.14%  |
| 51-100        | 29        | 9.27%   |
| Unknown       | 5         | 1.6%    |
| 1-50          | 4         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 239       | 78.1%   |
| 2     | 52        | 16.99%  |
| 0     | 12        | 3.92%   |
| 3     | 3         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 182       | 40.72%  |
| Realtek Semiconductor                  | 135       | 30.2%   |
| Qualcomm Atheros                       | 38        | 8.5%    |
| MediaTek                               | 25        | 5.59%   |
| Broadcom                               | 19        | 4.25%   |
| ASIX Electronics                       | 9         | 2.01%   |
| Qualcomm                               | 5         | 1.12%   |
| Broadcom Limited                       | 5         | 1.12%   |
| Ralink Technology                      | 4         | 0.89%   |
| Marvell Technology Group               | 4         | 0.89%   |
| TP-Link                                | 2         | 0.45%   |
| SEGGER                                 | 2         | 0.45%   |
| Quectel Wireless Solutions             | 2         | 0.45%   |
| Lenovo                                 | 2         | 0.45%   |
| DisplayLink                            | 2         | 0.45%   |
| Xiaomi                                 | 1         | 0.22%   |
| Texas Instruments                      | 1         | 0.22%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.22%   |
| Ralink                                 | 1         | 0.22%   |
| Qualcomm Technologies                  | 1         | 0.22%   |
| OPPO Electronics                       | 1         | 0.22%   |
| NetGear                                | 1         | 0.22%   |
| Microsoft                              | 1         | 0.22%   |
| Huawei Technologies                    | 1         | 0.22%   |
| Fitbit                                 | 1         | 0.22%   |
| Apple                                  | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 80        | 15.21%  |
| Intel Wi-Fi 6 AX200                                                     | 21        | 3.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 18        | 3.42%   |
| Intel Wireless 8265 / 8275                                              | 15        | 2.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 13        | 2.47%   |
| Intel Wireless 7265                                                     | 10        | 1.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 1.9%    |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 1.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 1.71%   |
| Intel Wireless 8260                                                     | 9         | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 8         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 7         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.14%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 6         | 1.14%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 6         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                           | 6         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 0.95%   |
| Intel Wireless 7260                                                     | 5         | 0.95%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 5         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                       | 4         | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 172       | 57.33%  |
| Realtek Semiconductor      | 36        | 12%     |
| Qualcomm Atheros           | 34        | 11.33%  |
| MediaTek                   | 21        | 7%      |
| Broadcom                   | 16        | 5.33%   |
| Qualcomm                   | 5         | 1.67%   |
| Ralink Technology          | 4         | 1.33%   |
| Broadcom Limited           | 3         | 1%      |
| TP-Link                    | 2         | 0.67%   |
| Quectel Wireless Solutions | 2         | 0.67%   |
| Texas Instruments          | 1         | 0.33%   |
| Ralink                     | 1         | 0.33%   |
| Qualcomm Technologies      | 1         | 0.33%   |
| NetGear                    | 1         | 0.33%   |
| Microsoft                  | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 21        | 6.98%   |
| Intel Wireless 8265 / 8275                                              | 15        | 4.98%   |
| Intel Wireless 7265                                                     | 10        | 3.32%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 3.32%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 3.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 9         | 2.99%   |
| Intel Wireless 8260                                                     | 9         | 2.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 2.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 2.99%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 8         | 2.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 2.66%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 7         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 6         | 1.99%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 6         | 1.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.66%   |
| Intel Wireless 7260                                                     | 5         | 1.66%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 5         | 1.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1%      |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1%      |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1%      |
| Intel Centrino Advanced-N 6200                                          | 3         | 1%      |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 3         | 1%      |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1%      |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.66%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 119       | 54.84%  |
| Intel                                  | 57        | 26.27%  |
| Qualcomm Atheros                       | 9         | 4.15%   |
| ASIX Electronics                       | 9         | 4.15%   |
| MediaTek                               | 4         | 1.84%   |
| Marvell Technology Group               | 4         | 1.84%   |
| Broadcom                               | 4         | 1.84%   |
| Lenovo                                 | 2         | 0.92%   |
| DisplayLink                            | 2         | 0.92%   |
| Broadcom Limited                       | 2         | 0.92%   |
| Xiaomi                                 | 1         | 0.46%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.46%   |
| OPPO Electronics                       | 1         | 0.46%   |
| Huawei Technologies                    | 1         | 0.46%   |
| Apple                                  | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 80        | 36.36%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 18        | 8.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 4.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 4.09%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 3.18%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 1.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.82%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 1.36%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.36%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 2         | 0.91%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.91%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.91%   |
| Lenovo ThinkPad Lan                                                    | 2         | 0.91%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.91%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.91%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.91%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.91%   |
| DisplayLink LAPDOCK                                                    | 2         | 0.91%   |
| ASIX AX88772B                                                          | 2         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.45%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Realtek USB 10/100 LAN                                                 | 1         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.45%   |
| OPPO OnePlus Nord 4                                                    | 1         | 0.45%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.45%   |
| Lenovo USB-C Hub                                                       | 1         | 0.45%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller (3)                | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 287       | 58.1%   |
| Ethernet | 202       | 40.89%  |
| Modem    | 3         | 0.61%   |
| Unknown  | 2         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 250       | 78.86%  |
| Ethernet | 67        | 21.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 172       | 57.91%  |
| 1     | 116       | 39.06%  |
| 0     | 9         | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 286       | 96.3%   |
| Yes  | 11        | 3.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 150       | 60.24%  |
| Foxconn / Hon Hai               | 22        | 8.84%   |
| Realtek Semiconductor           | 14        | 5.62%   |
| IMC Networks                    | 12        | 4.82%   |
| Qualcomm Atheros Communications | 10        | 4.02%   |
| Broadcom                        | 8         | 3.21%   |
| Apple                           | 7         | 2.81%   |
| Lite-On Technology              | 5         | 2.01%   |
| Realtek                         | 3         | 1.2%    |
| MediaTek                        | 3         | 1.2%    |
| Hewlett-Packard                 | 3         | 1.2%    |
| Foxconn International           | 3         | 1.2%    |
| Taiyo Yuden                     | 2         | 0.8%    |
| Dell                            | 2         | 0.8%    |
| USI                             | 1         | 0.4%    |
| Fujitsu                         | 1         | 0.4%    |
| Cambridge Silicon Radio         | 1         | 0.4%    |
| Askey Computer                  | 1         | 0.4%    |
| Alps Electric                   | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 38        | 15.26%  |
| Intel AX201 Bluetooth                             | 31        | 12.45%  |
| Intel AX211 Bluetooth                             | 24        | 9.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 23        | 9.24%   |
| Intel AX200 Bluetooth                             | 21        | 8.43%   |
| Realtek Bluetooth Radio                           | 14        | 5.62%   |
| Intel AX210 Bluetooth                             | 10        | 4.02%   |
| Foxconn / Hon Hai Wireless_Device                 | 9         | 3.61%   |
| IMC Networks Wireless_Device                      | 6         | 2.41%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 2.01%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 5         | 2.01%   |
| Foxconn / Hon Hai Bluetooth Device                | 5         | 2.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 1.61%   |
| Realtek Bluetooth Radio                           | 3         | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 3         | 1.2%    |
| MediaTek Wireless_Device                          | 3         | 1.2%    |
| IMC Networks Bluetooth Radio                      | 3         | 1.2%    |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 1.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 3         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 0.8%    |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 0.8%    |
| IMC Networks Bluetooth Device                     | 2         | 0.8%    |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 0.8%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device   | 2         | 0.8%    |
| Apple Bluetooth USB Host Controller               | 2         | 0.8%    |
| Apple Bluetooth Host Controller                   | 2         | 0.8%    |
| USI Bluetooth Device                              | 1         | 0.4%    |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)           | 1         | 0.4%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)           | 1         | 0.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.4%    |
| Lite-On Bluetooth Radio                           | 1         | 0.4%    |
| Lite-On Bluetooth Device                          | 1         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.4%    |
| IMC Networks Bluetooth USB Host Controller        | 1         | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 0.4%    |
| Fujitsu Bluetooth Device                          | 1         | 0.4%    |
| Foxconn / Hon Hai BCM20702A0                      | 1         | 0.4%    |
| Dell DW375 Bluetooth Module                       | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 223       | 60.76%  |
| AMD                         | 65        | 17.71%  |
| Nvidia                      | 63        | 17.17%  |
| Generalplus Technology      | 2         | 0.54%   |
| ESS Technology              | 2         | 0.54%   |
| Walmart                     | 1         | 0.27%   |
| VIA Technologies            | 1         | 0.27%   |
| Logitech                    | 1         | 0.27%   |
| Lenovo                      | 1         | 0.27%   |
| JMTek                       | 1         | 0.27%   |
| iCreate Technologies        | 1         | 0.27%   |
| Huawei Technologies         | 1         | 0.27%   |
| FiiO Electronics Technology | 1         | 0.27%   |
| DSEA A/S                    | 1         | 0.27%   |
| BY EDIFIER                  | 1         | 0.27%   |
| AudioQuest                  | 1         | 0.27%   |
| Apple                       | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 60        | 13.82%  |
| Intel Sunrise Point-LP HD Audio                                            | 40        | 9.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 26        | 5.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 4.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 16        | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 3.46%   |
| Nvidia AD107 High Definition Audio Controller                              | 13        | 3%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 3%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 3%      |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.53%   |
| Nvidia GA106 High Definition Audio Controller                              | 10        | 2.3%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 2.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.61%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.38%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 6         | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.38%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 1.38%   |
| Nvidia GA107 High Definition Audio Controller                              | 5         | 1.15%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5         | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.92%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 0.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 0.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.69%   |
| Nvidia AD106M High Definition Audio Controller                             | 3         | 0.69%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 77        | 32.49%  |
| SK hynix                   | 56        | 23.63%  |
| Micron Technology          | 34        | 14.35%  |
| Unknown                    | 16        | 6.75%   |
| Crucial                    | 14        | 5.91%   |
| Kingston                   | 11        | 4.64%   |
| Unknown                    | 10        | 4.22%   |
| Unknown (ABCD)             | 4         | 1.69%   |
| Elpida                     | 3         | 1.27%   |
| A-DATA Technology          | 2         | 0.84%   |
| Unknown (08C8)             | 1         | 0.42%   |
| Team                       | 1         | 0.42%   |
| Shenzhen Jinge Information | 1         | 0.42%   |
| Ramaxel Technology         | 1         | 0.42%   |
| Patriot                    | 1         | 0.42%   |
| Nanya Technology           | 1         | 0.42%   |
| Lenovo                     | 1         | 0.42%   |
| Kingmax                    | 1         | 0.42%   |
| Corsair                    | 1         | 0.42%   |
| ChangXin Memory            | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 10        | 4.07%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s          | 5         | 2.03%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.63%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 4         | 1.63%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.22%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 3         | 1.22%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 1.22%   |
| Samsung RAM K3KL9L90CM-MGCT 4GB Row Of Chips LPDDR5 7500MT/s     | 3         | 1.22%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 2         | 0.81%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.81%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 2         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 2         | 0.81%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 2         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.81%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| SK hynix RAM H58G66BK7BX067 8GB Row Of Chips LPDDR5 7500MT/s     | 2         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.81%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.81%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 2         | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.81%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 0.81%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s          | 2         | 0.81%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.81%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 0.81%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 2         | 0.81%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s       | 2         | 0.81%   |
| Micron RAM MT62F2G32D4DS-026 4GB Row Of Chips LPDDR5 7467MT/s    | 2         | 0.81%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.81%   |
| Crucial RAM CT16G4SFS832A.C8FB 16GB SODIMM DDR4 3200MT/s         | 2         | 0.81%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 78        | 38.05%  |
| DDR3    | 28        | 13.66%  |
| DDR5    | 25        | 12.2%   |
| LPDDR4  | 22        | 10.73%  |
| LPDDR5  | 20        | 9.76%   |
| LPDDR3  | 15        | 7.32%   |
| DDR2    | 8         | 3.9%    |
| DRAM    | 3         | 1.46%   |
| SDRAM   | 2         | 0.98%   |
| DDR     | 2         | 0.98%   |
| Unknown | 2         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 143       | 69.42%  |
| Row Of Chips | 53        | 25.73%  |
| DIMM         | 6         | 2.91%   |
| Unknown      | 3         | 1.46%   |
| Chip         | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 82        | 36.61%  |
| 16384 | 48        | 21.43%  |
| 4096  | 42        | 18.75%  |
| 2048  | 21        | 9.38%   |
| 32768 | 16        | 7.14%   |
| 1024  | 6         | 2.68%   |
| 3072  | 2         | 0.89%   |
| 256   | 2         | 0.89%   |
| 64    | 2         | 0.89%   |
| 49152 | 1         | 0.45%   |
| 512   | 1         | 0.45%   |
| 232   | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 34        | 15.89%  |
| 2667    | 32        | 14.95%  |
| 1600    | 24        | 11.21%  |
| 2133    | 16        | 7.48%   |
| 5600    | 15        | 7.01%   |
| 2400    | 14        | 6.54%   |
| 4800    | 11        | 5.14%   |
| 4267    | 10        | 4.67%   |
| 6400    | 9         | 4.21%   |
| 1867    | 8         | 3.74%   |
| 7500    | 7         | 3.27%   |
| Unknown | 7         | 3.27%   |
| 3266    | 4         | 1.87%   |
| 1334    | 3         | 1.4%    |
| 667     | 3         | 1.4%    |
| 8533    | 2         | 0.93%   |
| 7467    | 2         | 0.93%   |
| 3733    | 2         | 0.93%   |
| 533     | 2         | 0.93%   |
| 200     | 2         | 0.93%   |
| 8400    | 1         | 0.47%   |
| 4266    | 1         | 0.47%   |
| 2933    | 1         | 0.47%   |
| 1067    | 1         | 0.47%   |
| 1066    | 1         | 0.47%   |
| 975     | 1         | 0.47%   |
| 333     | 1         | 0.47%   |

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
| Chicony Electronics                    | 62        | 24.6%   |
| IMC Networks                           | 29        | 11.51%  |
| Bison Electronics                      | 19        | 7.54%   |
| Luxvisions Innotech Limited            | 17        | 6.75%   |
| Microdia                               | 14        | 5.56%   |
| Realtek Semiconductor                  | 13        | 5.16%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.97%   |
| Sunplus Innovation Technology          | 9         | 3.57%   |
| Quanta                                 | 8         | 3.17%   |
| Apple                                  | 7         | 2.78%   |
| Syntek                                 | 6         | 2.38%   |
| Acer                                   | 6         | 2.38%   |
| Sonix Technology                       | 5         | 1.98%   |
| Silicon Motion                         | 5         | 1.98%   |
| Suyin                                  | 4         | 1.59%   |
| Shinetech                              | 4         | 1.59%   |
| Alcor Micro                            | 4         | 1.59%   |
| Tripath Technology                     | 3         | 1.19%   |
| Microsoft                              | 3         | 1.19%   |
| Ricoh                                  | 2         | 0.79%   |
| Lite-On Technology                     | 2         | 0.79%   |
| kingcome                               | 2         | 0.79%   |
| Importek                               | 2         | 0.79%   |
| Xiaomi                                 | 1         | 0.4%    |
| WaveRider Communications               | 1         | 0.4%    |
| SN0002                                 | 1         | 0.4%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.4%    |
| Primax Electronics                     | 1         | 0.4%    |
| Nebraska Furniture Mart                | 1         | 0.4%    |
| Logitech                               | 1         | 0.4%    |
| lihappe8                               | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| Intel                                  | 1         | 0.4%    |
| icSpring                               | 1         | 0.4%    |
| HYGD-220831-A                          | 1         | 0.4%    |
| Genesys Logic                          | 1         | 0.4%    |
| eMPIA Technology                       | 1         | 0.4%    |
| BillionPixels                          | 1         | 0.4%    |
| Unknown                                | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 28        | 10.89%  |
| IMC Networks Integrated Camera                                  | 12        | 4.67%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 3.5%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 9         | 3.5%    |
| Bison Integrated Camera                                         | 9         | 3.5%    |
| Luxvisions Innotech Limited Integrated Camera                   | 7         | 2.72%   |
| Chicony HD Webcam                                               | 7         | 2.72%   |
| Chicony FJ Camera                                               | 6         | 2.33%   |
| Realtek Integrated_Webcam_HD                                    | 5         | 1.95%   |
| Syntek Integrated Camera                                        | 4         | 1.56%   |
| Shinetech USB2.0 FHD UVC WebCam                                 | 4         | 1.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 4         | 1.56%   |
| Apple FaceTime HD Camera (Built-in)                             | 4         | 1.56%   |
| Tripath USB Camera                                              | 3         | 1.17%   |
| Sonix USB2.0 FHD UVC WebCam                                     | 3         | 1.17%   |
| Quanta HD User Facing                                           | 3         | 1.17%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 3         | 1.17%   |
| Luxvisions Innotech Limited HP HD Camera                        | 3         | 1.17%   |
| Chicony Integrated IR Camera                                    | 3         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 3         | 1.17%   |
| Bison Lenovo EasyCamera                                         | 3         | 1.17%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 1.17%   |
| Acer Integrated RGB Camera                                      | 3         | 1.17%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 0.78%   |
| Silicon Motion 720p HD Camera                                   | 2         | 0.78%   |
| Realtek USB Camera                                              | 2         | 0.78%   |
| Realtek Front Camera                                            | 2         | 0.78%   |
| Quanta ACER HD User Facing                                      | 2         | 0.78%   |
| Microsoft LifeCam Cinema                                        | 2         | 0.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 0.78%   |
| Lite-On Integrated Camera                                       | 2         | 0.78%   |
| Importek FJ Camera                                              | 2         | 0.78%   |
| Chicony USB2.0 HD UVC WebCam                                    | 2         | 0.78%   |
| Chicony USB2.0 Camera                                           | 2         | 0.78%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 0.78%   |
| Bison SunplusIT Integrated Camera                               | 2         | 0.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 2         | 0.78%   |
| Acer BisonCam,NB Pro                                            | 2         | 0.78%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                              | 1         | 0.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 22        | 37.29%  |
| Validity Sensors                   | 12        | 20.34%  |
| Shenzhen Goodix Technology         | 10        | 16.95%  |
| Upek                               | 4         | 6.78%   |
| LighTuning Technology              | 4         | 6.78%   |
| AuthenTec                          | 4         | 6.78%   |
| Samsung Electronics                | 2         | 3.39%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 8         | 13.56%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 7         | 11.86%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 8.47%   |
| Validity Sensors Synaptics WBDI                                 | 4         | 6.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 6.78%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 5.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 3         | 5.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 3.39%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 3.39%   |
| Synaptics UWP WBDI Device                                       | 2         | 3.39%   |
| Synaptics Prometheus Fingerprint Reader                         | 2         | 3.39%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.39%   |
| AuthenTec Fingerprint Sensor                                    | 2         | 3.39%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 3.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.69%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.69%   |
| Synaptics WBDI                                                  | 1         | 1.69%   |
| Synaptics UWP WBDI                                              | 1         | 1.69%   |
| Samsung Fingerprint Sensor Device - 730B                        | 1         | 1.69%   |
| Samsung Fingerprint Device                                      | 1         | 1.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.69%   |
| Unknown                                                         | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 35.29%  |
| Upek                  | 4         | 23.53%  |
| Alcor Micro           | 3         | 17.65%  |
| Lenovo                | 2         | 11.76%  |
| O2 Micro              | 1         | 5.88%   |
| Advanced Card Systems | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 23.53%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 17.65%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 11.76%  |
| Broadcom 5880                                                                | 2         | 11.76%  |
| Broadcom 58200                                                               | 2         | 11.76%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.88%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 173       | 57.28%  |
| 1     | 98        | 32.45%  |
| 2     | 24        | 7.95%   |
| 3     | 5         | 1.66%   |
| 5     | 1         | 0.33%   |
| 4     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 55        | 33.95%  |
| Graphics card            | 43        | 26.54%  |
| Multimedia controller    | 17        | 10.49%  |
| Chipcard                 | 16        | 9.88%   |
| Net/wireless             | 8         | 4.94%   |
| Camera                   | 7         | 4.32%   |
| Communication controller | 6         | 3.7%    |
| Bluetooth                | 3         | 1.85%   |
| Modem                    | 2         | 1.23%   |
| Card reader              | 2         | 1.23%   |
| Storage                  | 1         | 0.62%   |
| Sound                    | 1         | 0.62%   |
| Net/ethernet             | 1         | 0.62%   |

