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

Total: 231

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 28        | 16.97%  |
| Ubuntu 18.04        | 9         | 5.45%   |
| Ubuntu 22.04        | 8         | 4.85%   |
| Arch                | 8         | 4.85%   |
| antiX 21            | 8         | 4.85%   |
| Fedora 32           | 5         | 3.03%   |
| Ubuntu 19.10        | 4         | 2.42%   |
| Gentoo 2.7          | 4         | 2.42%   |
| EndeavourOS Rolling | 4         | 2.42%   |
| Arch Rolling        | 4         | 2.42%   |
| OpenMandriva 4.2    | 3         | 1.82%   |
| Linux Mint 20       | 3         | 1.82%   |
| Fedora 36           | 3         | 1.82%   |
| Fedora 33           | 3         | 1.82%   |
| Chrome OS           | 3         | 1.82%   |
| ArcoLinux Rolling   | 3         | 1.82%   |
| Ubuntu 22.10        | 2         | 1.21%   |
| Ubuntu 21.04        | 2         | 1.21%   |
| Ubuntu 19.04        | 2         | 1.21%   |
| Ubuntu 16.04        | 2         | 1.21%   |
| Pop!_OS 22.04       | 2         | 1.21%   |
| Pop!_OS 20.10       | 2         | 1.21%   |
| Pop!_OS 20.04       | 2         | 1.21%   |
| OpenMandriva 4.50   | 2         | 1.21%   |
| Manjaro 20.1        | 2         | 1.21%   |
| Linux Mint 20.3     | 2         | 1.21%   |
| KDE neon 20.04      | 2         | 1.21%   |
| Gentoo 2.8          | 2         | 1.21%   |
| Fedora 34           | 2         | 1.21%   |
| Debian Testing      | 2         | 1.21%   |
| Debian 11           | 2         | 1.21%   |
| Zorin 15            | 1         | 0.61%   |
| UbuntuDDE 21.10     | 1         | 0.61%   |
| Ubuntu Unity 22.04  | 1         | 0.61%   |
| Ubuntu Unity 20.04  | 1         | 0.61%   |
| Ubuntu Unity 18.04  | 1         | 0.61%   |
| Ubuntu Budgie 20.04 | 1         | 0.61%   |
| Ubuntu 21.10        | 1         | 0.61%   |
| Ubuntu 20.10        | 1         | 0.61%   |
| SteamOS 3.4         | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 58        | 36.02%  |
| Fedora        | 15        | 9.32%   |
| Arch          | 12        | 7.45%   |
| Pop!_OS       | 8         | 4.97%   |
| antiX         | 8         | 4.97%   |
| OpenMandriva  | 7         | 4.35%   |
| Linux Mint    | 7         | 4.35%   |
| Manjaro       | 5         | 3.11%   |
| Gentoo        | 5         | 3.11%   |
| EndeavourOS   | 4         | 2.48%   |
| Debian        | 4         | 2.48%   |
| Clear Linux   | 4         | 2.48%   |
| Ubuntu Unity  | 3         | 1.86%   |
| Chrome OS     | 3         | 1.86%   |
| ArcoLinux     | 3         | 1.86%   |
| ROSA          | 2         | 1.24%   |
| KDE neon      | 2         | 1.24%   |
| Zorin         | 1         | 0.62%   |
| UbuntuDDE     | 1         | 0.62%   |
| Ubuntu Budgie | 1         | 0.62%   |
| SteamOS       | 1         | 0.62%   |
| PCLinuxOS     | 1         | 0.62%   |
| Oracle Linux  | 1         | 0.62%   |
| openSUSE      | 1         | 0.62%   |
| Kubuntu       | 1         | 0.62%   |
| Kali          | 1         | 0.62%   |
| Elementary    | 1         | 0.62%   |
| BlackPanther  | 1         | 0.62%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp           | 8         | 4.52%   |
| 5.4.0-42-generic                    | 6         | 3.39%   |
| 5.8.0-43-generic                    | 3         | 1.69%   |
| 5.4.0-48-generic                    | 3         | 1.69%   |
| 5.15.0-46-generic                   | 3         | 1.69%   |
| 5.13.0-39-generic                   | 3         | 1.69%   |
| 5.10.14-desktop-1omv4002            | 3         | 1.69%   |
| 4.19.49+                            | 3         | 1.69%   |
| 5.9.2-arch1-1                       | 2         | 1.13%   |
| 5.8.0-7630-generic                  | 2         | 1.13%   |
| 5.4.0-58-generic                    | 2         | 1.13%   |
| 5.4.0-28-generic                    | 2         | 1.13%   |
| 5.4.0-26-generic                    | 2         | 1.13%   |
| 5.3.0-18-generic                    | 2         | 1.13%   |
| 5.17.11-300.fc36.x86_64             | 2         | 1.13%   |
| 5.15.0-47-generic                   | 2         | 1.13%   |
| 5.13.0-35-generic                   | 2         | 1.13%   |
| 5.11.0-37-generic                   | 2         | 1.13%   |
| 5.0.0-31-generic                    | 2         | 1.13%   |
| 4.18.0-15-generic                   | 2         | 1.13%   |
| 6.0.0-rc1-asahi-00175-g01a8389621b6 | 1         | 0.56%   |
| 6.0.0-060000-generic                | 1         | 0.56%   |
| 5.9.8-200.fc33.x86_64               | 1         | 0.56%   |
| 5.9.3-arch1-1                       | 1         | 0.56%   |
| 5.9.14-100.fc32.x86_64              | 1         | 0.56%   |
| 5.9.10-artix1-1                     | 1         | 0.56%   |
| 5.8.6-1-MANJARO                     | 1         | 0.56%   |
| 5.8.3-2-MANJARO                     | 1         | 0.56%   |
| 5.8.15-gentoo                       | 1         | 0.56%   |
| 5.8.0-64-generic                    | 1         | 0.56%   |
| 5.8.0-63-generic                    | 1         | 0.56%   |
| 5.8.0-55-generic                    | 1         | 0.56%   |
| 5.8.0-54-generic                    | 1         | 0.56%   |
| 5.8.0-33-generic                    | 1         | 0.56%   |
| 5.8.0-25-generic                    | 1         | 0.56%   |
| 5.7.9-200.fc32.x86_64               | 1         | 0.56%   |
| 5.7.4-gentoo                        | 1         | 0.56%   |
| 5.7.11-200.fc32.x86_64              | 1         | 0.56%   |
| 5.7.10-201.fc32.x86_64              | 1         | 0.56%   |
| 5.6.3-zen1-1-zen                    | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 12.5%   |
| 5.13.0  | 11        | 6.55%   |
| 5.15.0  | 10        | 5.95%   |
| 5.8.0   | 9         | 5.36%   |
| 4.9.0   | 8         | 4.76%   |
| 4.15.0  | 7         | 4.17%   |
| 5.11.0  | 6         | 3.57%   |
| 5.3.0   | 5         | 2.98%   |
| 5.0.0   | 5         | 2.98%   |
| 5.19.0  | 4         | 2.38%   |
| 5.10.14 | 3         | 1.79%   |
| 4.19.49 | 3         | 1.79%   |
| 6.0.0   | 2         | 1.19%   |
| 5.9.2   | 2         | 1.19%   |
| 5.17.4  | 2         | 1.19%   |
| 5.17.11 | 2         | 1.19%   |
| 5.10.0  | 2         | 1.19%   |
| 4.18.0  | 2         | 1.19%   |
| 5.9.8   | 1         | 0.6%    |
| 5.9.3   | 1         | 0.6%    |
| 5.9.14  | 1         | 0.6%    |
| 5.9.10  | 1         | 0.6%    |
| 5.8.6   | 1         | 0.6%    |
| 5.8.3   | 1         | 0.6%    |
| 5.8.15  | 1         | 0.6%    |
| 5.7.9   | 1         | 0.6%    |
| 5.7.4   | 1         | 0.6%    |
| 5.7.11  | 1         | 0.6%    |
| 5.7.10  | 1         | 0.6%    |
| 5.6.3   | 1         | 0.6%    |
| 5.4.17  | 1         | 0.6%    |
| 5.3.5   | 1         | 0.6%    |
| 5.3.14  | 1         | 0.6%    |
| 5.3.11  | 1         | 0.6%    |
| 5.19.8  | 1         | 0.6%    |
| 5.19.6  | 1         | 0.6%    |
| 5.19.5  | 1         | 0.6%    |
| 5.19.15 | 1         | 0.6%    |
| 5.19.13 | 1         | 0.6%    |
| 5.19.11 | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 12.73%  |
| 5.15    | 14        | 8.48%   |
| 5.13    | 13        | 7.88%   |
| 5.8     | 12        | 7.27%   |
| 5.11    | 12        | 7.27%   |
| 5.10    | 12        | 7.27%   |
| 5.19    | 11        | 6.67%   |
| 4.9     | 10        | 6.06%   |
| 5.3     | 8         | 4.85%   |
| 5.17    | 8         | 4.85%   |
| 4.15    | 7         | 4.24%   |
| 5.9     | 6         | 3.64%   |
| 5.0     | 5         | 3.03%   |
| 5.7     | 4         | 2.42%   |
| 5.16    | 4         | 2.42%   |
| 5.14    | 4         | 2.42%   |
| 4.19    | 4         | 2.42%   |
| 5.18    | 3         | 1.82%   |
| 4.18    | 3         | 1.82%   |
| 6.0     | 2         | 1.21%   |
| 5.6     | 1         | 0.61%   |
| 5.12    | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 145       | 91.77%  |
| i686    | 11        | 6.96%   |
| i586    | 1         | 0.63%   |
| aarch64 | 1         | 0.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 78        | 48.15%  |
| KDE5       | 30        | 18.52%  |
| Unknown    | 29        | 17.9%   |
| XFCE       | 5         | 3.09%   |
| X-Cinnamon | 5         | 3.09%   |
| KDE        | 3         | 1.85%   |
| i3         | 3         | 1.85%   |
| Unity      | 2         | 1.23%   |
| dwm        | 2         | 1.23%   |
| LXQt       | 1         | 0.62%   |
| fvwm       | 1         | 0.62%   |
| Deepin     | 1         | 0.62%   |
| Cinnamon   | 1         | 0.62%   |
| Budgie     | 1         | 0.62%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 126       | 78.75%  |
| Wayland | 24        | 15%     |
| Unknown | 9         | 5.63%   |
| Tty     | 1         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 46.25%  |
| SDDM    | 27        | 16.88%  |
| GDM     | 26        | 16.25%  |
| GDM3    | 15        | 9.38%   |
| LightDM | 13        | 8.13%   |
| TDM     | 4         | 2.5%    |
| LXDM    | 1         | 0.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 66        | 40.49%  |
| en_HK   | 32        | 19.63%  |
| zh_CN   | 20        | 12.27%  |
| Unknown | 19        | 11.66%  |
| zh_HK   | 7         | 4.29%   |
| zh_TW   | 6         | 3.68%   |
| C       | 6         | 3.68%   |
| en_GB   | 3         | 1.84%   |
| it_IT   | 1         | 0.61%   |
| en_ZA   | 1         | 0.61%   |
| en_AU   | 1         | 0.61%   |
| de_DE   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 108       | 67.92%  |
| BIOS | 51        | 32.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 117       | 72.67%  |
| Btrfs   | 17        | 10.56%  |
| Overlay | 11        | 6.83%   |
| Unknown | 7         | 4.35%   |
| Zfs     | 3         | 1.86%   |
| Xfs     | 3         | 1.86%   |
| Ext2    | 2         | 1.24%   |
| Ext3    | 1         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 76        | 47.2%   |
| Unknown | 69        | 42.86%  |
| MBR     | 16        | 9.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 142       | 89.31%  |
| Yes       | 17        | 10.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 61.01%  |
| Yes       | 62        | 38.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 50        | 31.65%  |
| Dell                 | 22        | 13.92%  |
| Hewlett-Packard      | 16        | 10.13%  |
| Fujitsu              | 12        | 7.59%   |
| ASUSTek Computer     | 12        | 7.59%   |
| Unknown              | 9         | 5.7%    |
| Acer                 | 6         | 3.8%    |
| HUAWEI               | 4         | 2.53%   |
| Apple                | 4         | 2.53%   |
| GPD                  | 3         | 1.9%    |
| Toshiba              | 2         | 1.27%   |
| Samsung Electronics  | 2         | 1.27%   |
| MSI                  | 2         | 1.27%   |
| KOHJINSHA            | 2         | 1.27%   |
| IBM                  | 2         | 1.27%   |
| Timi                 | 1         | 0.63%   |
| Sony                 | 1         | 0.63%   |
| Schenker             | 1         | 0.63%   |
| Panasonic            | 1         | 0.63%   |
| Jumper               | 1         | 0.63%   |
| Intel Client Systems | 1         | 0.63%   |
| Google               | 1         | 0.63%   |
| Compaq               | 1         | 0.63%   |
| Chuwi                | 1         | 0.63%   |
| AMI                  | 1         | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 10        | 6.33%   |
| Lenovo Legion R7000 2020 82B6            | 3         | 1.9%    |
| IBM 260921H                              | 2         | 1.27%   |
| HUAWEI KPRC-WX0                          | 2         | 1.27%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC         | 2         | 1.27%   |
| HP EliteBook 2540p                       | 2         | 1.27%   |
| Fujitsu UH-X                             | 2         | 1.27%   |
| Fujitsu LIFEBOOK AH544                   | 2         | 1.27%   |
| Dell XPS 13 9310                         | 2         | 1.27%   |
| Dell Inspiron 5580                       | 2         | 1.27%   |
| ASUS TUF Gaming FA506IU_FA506IU          | 2         | 1.27%   |
| Toshiba PORTEGE R830                     | 1         | 0.63%   |
| Toshiba dynabook R731/E                  | 1         | 0.63%   |
| Timi TM1607                              | 1         | 0.63%   |
| Sony VPCCB17FG                           | 1         | 0.63%   |
| Schenker XMG_APEX15_XAP15E20             | 1         | 0.63%   |
| Samsung SQ1S                             | 1         | 0.63%   |
| Samsung 930XBE                           | 1         | 0.63%   |
| Panasonic CFSZ5-2L                       | 1         | 0.63%   |
| MSI GS73VR 7RG                           | 1         | 0.63%   |
| MSI GS65 Stealth Thin 8RE                | 1         | 0.63%   |
| Lenovo ZHAOYANG K47                      | 1         | 0.63%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.63%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN        | 1         | 0.63%   |
| Lenovo XiaoXin-14API QC 2019 81UW        | 1         | 0.63%   |
| Lenovo XiaoXin Chao7000-14IKBR 81GA      | 1         | 0.63%   |
| Lenovo ThinkPad X270 20HNA00RAD          | 1         | 0.63%   |
| Lenovo ThinkPad X250 20CLA1VECD          | 1         | 0.63%   |
| Lenovo ThinkPad X220 4290NL5             | 1         | 0.63%   |
| Lenovo ThinkPad X13 Gen 1 20UFS01C00     | 1         | 0.63%   |
| Lenovo ThinkPad X1 Extreme 20MFS0PE00    | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1001BHH | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS9SA1N | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6J30S | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR003HHH | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBA05VCD | 1         | 0.63%   |
| Lenovo ThinkPad W530 24384KU             | 1         | 0.63%   |
| Lenovo ThinkPad T61 6465CTO              | 1         | 0.63%   |
| Lenovo ThinkPad T520 4242BC5             | 1         | 0.63%   |
| Lenovo ThinkPad T490s 20NYS79X00         | 1         | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 26        | 16.46%  |
| Unknown                 | 10        | 6.33%   |
| Fujitsu LIFEBOOK        | 8         | 5.06%   |
| Lenovo Legion           | 7         | 4.43%   |
| Dell XPS                | 7         | 4.43%   |
| Dell Inspiron           | 7         | 4.43%   |
| Lenovo IdeaPad          | 5         | 3.16%   |
| Dell Latitude           | 4         | 2.53%   |
| HP ZHAN                 | 3         | 1.9%    |
| HP EliteBook            | 3         | 1.9%    |
| Dell Precision          | 3         | 1.9%    |
| ASUS TUF                | 3         | 1.9%    |
| Acer Swift              | 3         | 1.9%    |
| Acer Aspire             | 3         | 1.9%    |
| Lenovo ThinkBook        | 2         | 1.27%   |
| IBM 260921H             | 2         | 1.27%   |
| HUAWEI KPRC-WX0         | 2         | 1.27%   |
| Fujitsu UH-X            | 2         | 1.27%   |
| ASUS ROG                | 2         | 1.27%   |
| Toshiba PORTEGE         | 1         | 0.63%   |
| Toshiba dynabook        | 1         | 0.63%   |
| Timi TM1607             | 1         | 0.63%   |
| Sony VPCCB17FG          | 1         | 0.63%   |
| Schenker XMG            | 1         | 0.63%   |
| Samsung SQ1S            | 1         | 0.63%   |
| Samsung 930XBE          | 1         | 0.63%   |
| Panasonic CFSZ5-2L      | 1         | 0.63%   |
| MSI GS73VR              | 1         | 0.63%   |
| MSI GS65                | 1         | 0.63%   |
| Lenovo ZHAOYANG         | 1         | 0.63%   |
| Lenovo Yoga             | 1         | 0.63%   |
| Lenovo XiaoXinAir-14ARE | 1         | 0.63%   |
| Lenovo XiaoXin-14API    | 1         | 0.63%   |
| Lenovo XiaoXin          | 1         | 0.63%   |
| Lenovo G770             | 1         | 0.63%   |
| Lenovo G710             | 1         | 0.63%   |
| Lenovo E10-30           | 1         | 0.63%   |
| Lenovo 3000             | 1         | 0.63%   |
| KOHJINSHA SX            | 1         | 0.63%   |
| KOHJINSHA SC            | 1         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 26        | 16.46%  |
| 2018    | 26        | 16.46%  |
| 2021    | 17        | 10.76%  |
| 2019    | 15        | 9.49%   |
| 2011    | 10        | 6.33%   |
| 2017    | 9         | 5.7%    |
| 2014    | 7         | 4.43%   |
| 2012    | 7         | 4.43%   |
| 2022    | 6         | 3.8%    |
| 2015    | 6         | 3.8%    |
| 2010    | 6         | 3.8%    |
| 2008    | 5         | 3.16%   |
| 2016    | 4         | 2.53%   |
| 2013    | 3         | 1.9%    |
| 2009    | 3         | 1.9%    |
| 2007    | 3         | 1.9%    |
| 1999    | 2         | 1.27%   |
| 2005    | 1         | 0.63%   |
| 2003    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 158       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 137       | 86.71%  |
| Enabled  | 21        | 13.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 157       | 99.37%  |
| Yes  | 1         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 22.15%  |
| 8.01-16.0   | 34        | 21.52%  |
| 16.01-24.0  | 33        | 20.89%  |
| 32.01-64.0  | 16        | 10.13%  |
| 3.01-4.0    | 16        | 10.13%  |
| 2.01-3.0    | 5         | 3.16%   |
| 1.01-2.0    | 5         | 3.16%   |
| 24.01-32.0  | 4         | 2.53%   |
| 64.01-256.0 | 4         | 2.53%   |
| 0.51-1.0    | 4         | 2.53%   |
| 0.01-0.5    | 2         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 43        | 26.22%  |
| 2.01-3.0   | 35        | 21.34%  |
| 4.01-8.0   | 28        | 17.07%  |
| 3.01-4.0   | 24        | 14.63%  |
| 0.01-0.5   | 14        | 8.54%   |
| 8.01-16.0  | 12        | 7.32%   |
| 0.51-1.0   | 4         | 2.44%   |
| 16.01-24.0 | 3         | 1.83%   |
| 24.01-32.0 | 1         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 60.37%  |
| 2      | 53        | 32.32%  |
| 3      | 8         | 4.88%   |
| 0      | 3         | 1.83%   |
| 5      | 1         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 128       | 80%     |
| Yes       | 32        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 71.52%  |
| No        | 45        | 28.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 98.73%  |
| No        | 2         | 1.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 75.47%  |
| No        | 39        | 24.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Hong Kong | 158       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Central       | 87        | 52.41%  |
| Shatin        | 10        | 6.02%   |
| Kowloon       | 7         | 4.22%   |
| Tseung Kwan O | 6         | 3.61%   |
| Wanchai       | 5         | 3.01%   |
| Tung Chung    | 5         | 3.01%   |
| Hong Kong     | 5         | 3.01%   |
| Hung Hom      | 4         | 2.41%   |
| Tuen Mun      | 3         | 1.81%   |
| Tai Po        | 3         | 1.81%   |
| Yuen Long     | 2         | 1.2%    |
| Sai Kung      | 2         | 1.2%    |
| Ngau Wu Tok   | 2         | 1.2%    |
| Man Kok       | 2         | 1.2%    |
| Kwun Hang     | 2         | 1.2%    |
| Discovery Bay | 2         | 1.2%    |
| Yau Tsim Mong | 1         | 0.6%    |
| Wong Tai Sin  | 1         | 0.6%    |
| Tsuen Wan     | 1         | 0.6%    |
| Tsimshatsui   | 1         | 0.6%    |
| To Kwa Wan    | 1         | 0.6%    |
| Tin Shui Wai  | 1         | 0.6%    |
| Tai Wan To    | 1         | 0.6%    |
| Tai Wan       | 1         | 0.6%    |
| So Kon Po     | 1         | 0.6%    |
| Sheung Shui   | 1         | 0.6%    |
| Shau Kei Wan  | 1         | 0.6%    |
| Quarry Bay    | 1         | 0.6%    |
| North Point   | 1         | 0.6%    |
| North         | 1         | 0.6%    |
| Mong Kok      | 1         | 0.6%    |
| Lam Tin       | 1         | 0.6%    |
| Fanling       | 1         | 0.6%    |
| Causeway Bay  | 1         | 0.6%    |
| Unknown       | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 48     | 19.52%  |
| WDC                 | 24        | 25     | 11.43%  |
| Unknown             | 14        | 18     | 6.67%   |
| Seagate             | 14        | 15     | 6.67%   |
| SanDisk             | 13        | 15     | 6.19%   |
| Intel               | 11        | 13     | 5.24%   |
| SK hynix            | 10        | 11     | 4.76%   |
| Hitachi             | 8         | 8      | 3.81%   |
| Kingston            | 7         | 8      | 3.33%   |
| Toshiba             | 5         | 5      | 2.38%   |
| Micron Technology   | 5         | 6      | 2.38%   |
| HGST                | 5         | 6      | 2.38%   |
| Crucial             | 5         | 9      | 2.38%   |
| Fujitsu             | 4         | 6      | 1.9%    |
| Apple               | 4         | 7      | 1.9%    |
| Phison              | 3         | 3      | 1.43%   |
| KIOXIA              | 3         | 3      | 1.43%   |
| JMicron Technology  | 3         | 4      | 1.43%   |
| China               | 3         | 4      | 1.43%   |
| Plextor             | 2         | 3      | 0.95%   |
| KingSpec            | 2         | 3      | 0.95%   |
| Hikvision           | 2         | 2      | 0.95%   |
| BIWIN               | 2         | 2      | 0.95%   |
| Verbatim            | 1         | 2      | 0.48%   |
| Unknown (CF)        | 1         | 1      | 0.48%   |
| Transcend           | 1         | 1      | 0.48%   |
| TO Exter            | 1         | 1      | 0.48%   |
| Team                | 1         | 1      | 0.48%   |
| ShineDisk           | 1         | 1      | 0.48%   |
| RECADATA            | 1         | 1      | 0.48%   |
| Ramsta              | 1         | 1      | 0.48%   |
| PH4-CE12            | 1         | 1      | 0.48%   |
| Lexar               | 1         | 1      | 0.48%   |
| Lenovo              | 1         | 1      | 0.48%   |
| INTEL SS            | 1         | 1      | 0.48%   |
| HS-SSD-C100         | 1         | 2      | 0.48%   |
| Hewlett-Packard     | 1         | 1      | 0.48%   |
| GALAX TA            | 1         | 1      | 0.48%   |
| Faspeed             | 1         | 1      | 0.48%   |
| DGM                 | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 4         | 1.83%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.83%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 1.38%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.38%   |
| Samsung NVMe SSD Drive 512GB         | 3         | 1.38%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 2         | 0.92%   |
| WDC WD10SPZX-22Z10T1 1TB             | 2         | 0.92%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 2         | 0.92%   |
| Unknown MMC Card  128GB              | 2         | 0.92%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.92%   |
| SK hynix BC501 NVMe 128GB            | 2         | 0.92%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 0.92%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 0.92%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 0.92%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.92%   |
| Samsung MZVLB512HBJQ-000L2 512GB     | 2         | 0.92%   |
| Samsung MZVL2512HCJQ-00BL2 512GB     | 2         | 0.92%   |
| Plextor PX-128M7VC 128GB SSD         | 2         | 0.92%   |
| KIOXIA NVMe SSD Drive 512GB          | 2         | 0.92%   |
| JMicron Generic 1TB                  | 2         | 0.92%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.92%   |
| Fujitsu F300 480GB                   | 2         | 0.92%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.92%   |
| BIWIN SSD 512GB                      | 2         | 0.92%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.46%   |
| WDC WDS200T3X0C-00SJG0 2TB           | 1         | 0.46%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.46%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.46%   |
| WDC WD7500BPVT-24HXZT1 752GB         | 1         | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.46%   |
| WDC WD5000BPVT-75HXZT1 500GB         | 1         | 0.46%   |
| WDC WD5000BEVT-16A0RT0 500GB         | 1         | 0.46%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.46%   |
| WDC WD10SPCX-16HWST0 1TB             | 1         | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.46%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.46%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 32.56%  |
| WDC                 | 11        | 11     | 25.58%  |
| Hitachi             | 8         | 8      | 18.6%   |
| HGST                | 5         | 6      | 11.63%  |
| Toshiba             | 2         | 2      | 4.65%   |
| Samsung Electronics | 1         | 1      | 2.33%   |
| JMicron Technology  | 1         | 2      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 23.21%  |
| Intel               | 5         | 7      | 8.93%   |
| Crucial             | 5         | 9      | 8.93%   |
| WDC                 | 4         | 4      | 7.14%   |
| Kingston            | 3         | 3      | 5.36%   |
| China               | 3         | 4      | 5.36%   |
| SanDisk             | 2         | 2      | 3.57%   |
| Plextor             | 2         | 3      | 3.57%   |
| JMicron Technology  | 2         | 2      | 3.57%   |
| Fujitsu             | 2         | 4      | 3.57%   |
| Verbatim            | 1         | 2      | 1.79%   |
| Unknown (CF)        | 1         | 1      | 1.79%   |
| Transcend           | 1         | 1      | 1.79%   |
| TO Exter            | 1         | 1      | 1.79%   |
| Team                | 1         | 1      | 1.79%   |
| SK hynix            | 1         | 1      | 1.79%   |
| RECADATA            | 1         | 1      | 1.79%   |
| Ramsta              | 1         | 1      | 1.79%   |
| Micron Technology   | 1         | 2      | 1.79%   |
| Lexar               | 1         | 1      | 1.79%   |
| Hikvision           | 1         | 1      | 1.79%   |
| DGM                 | 1         | 1      | 1.79%   |
| Apple               | 1         | 1      | 1.79%   |
| Apacer              | 1         | 4      | 1.79%   |
| A-DATA Technology   | 1         | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 81        | 100    | 41.54%  |
| SSD     | 48        | 74     | 24.62%  |
| HDD     | 43        | 46     | 22.05%  |
| MMC     | 15        | 19     | 7.69%   |
| Unknown | 8         | 10     | 4.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 83        | 118    | 43.68%  |
| NVMe | 81        | 99     | 42.63%  |
| MMC  | 15        | 19     | 7.89%   |
| SAS  | 11        | 13     | 5.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 80     | 60.22%  |
| 0.51-1.0   | 28        | 30     | 30.11%  |
| 1.01-2.0   | 7         | 8      | 7.53%   |
| 10.01-20.0 | 1         | 1      | 1.08%   |
| 4.01-10.0  | 1         | 1      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 43        | 26.38%  |
| 251-500        | 35        | 21.47%  |
| 1-20           | 20        | 12.27%  |
| 501-1000       | 20        | 12.27%  |
| 1001-2000      | 17        | 10.43%  |
| 51-100         | 15        | 9.2%    |
| 21-50          | 5         | 3.07%   |
| 2001-3000      | 5         | 3.07%   |
| More than 3000 | 2         | 1.23%   |
| Unknown        | 1         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 75        | 44.64%  |
| 51-100    | 24        | 14.29%  |
| 21-50     | 21        | 12.5%   |
| 251-500   | 19        | 11.31%  |
| 101-250   | 17        | 10.12%  |
| 501-1000  | 6         | 3.57%   |
| 1001-2000 | 5         | 2.98%   |
| Unknown   | 1         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 1         | 1      | 10%     |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 10%     |
| Samsung Electronics SSD 860 EVO 1TB | 1         | 1      | 10%     |
| Hitachi HTS725050A7E630 500GB       | 1         | 1      | 10%     |
| Hitachi HTS723216L9A360 160GB       | 1         | 1      | 10%     |
| Hitachi HTC426040G8CE00 40GB        | 1         | 1      | 10%     |
| Hitachi DK23AA-60 6GB               | 1         | 1      | 10%     |
| HGST TOURO Mobile 1TB               | 1         | 1      | 10%     |
| DGM SSD 120GB S3-120A               | 1         | 1      | 10%     |
| Crucial CT240M500SSD1 240GB         | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 40%     |
| Seagate             | 1         | 1      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |
| DGM                 | 1         | 1      | 10%     |
| Crucial             | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 4         | 4      | 66.67%  |
| Seagate | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 60%     |
| SSD  | 4         | 4      | 40%     |

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
| Detected | 81        | 130    | 48.5%   |
| Works    | 76        | 109    | 45.51%  |
| Malfunc  | 10        | 10     | 5.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 105       | 51.98%  |
| Samsung Electronics          | 30        | 14.85%  |
| SanDisk                      | 20        | 9.9%    |
| AMD                          | 11        | 5.45%   |
| SK hynix                     | 9         | 4.46%   |
| Toshiba America Info Systems | 4         | 1.98%   |
| Phison Electronics           | 4         | 1.98%   |
| Micron Technology            | 4         | 1.98%   |
| Kingston Technology Company  | 4         | 1.98%   |
| Silicon Motion               | 3         | 1.49%   |
| KIOXIA                       | 2         | 0.99%   |
| Apple                        | 2         | 0.99%   |
| VIA Technologies             | 1         | 0.5%    |
| Nvidia                       | 1         | 0.5%    |
| Lenovo                       | 1         | 0.5%    |
| Biwin Storage Technology     | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 7.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 5.16%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 5.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 4.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 2.82%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 5         | 2.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 2.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.35%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.88%   |
| Micron Non-Volatile memory controller                                          | 4         | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.88%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 1.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.41%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.41%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.41%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.41%   |
| Intel SSD 660P Series                                                          | 3         | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.94%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.94%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.94%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.94%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.94%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.94%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 0.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.94%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 87        | 43.72%  |
| NVMe | 82        | 41.21%  |
| IDE  | 17        | 8.54%   |
| RAID | 13        | 6.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 131       | 82.91%  |
| AMD          | 25        | 15.82%  |
| GenuineTMx86 | 1         | 0.63%   |
| Unknown      | 1         | 0.63%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 4.43%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 3.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.53%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 2.53%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 1.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.9%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 1.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.9%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.27%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.27%   |
| Intel Celeron (Mendocino)                     | 2         | 1.27%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 2         | 1.27%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 1.27%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.27%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.27%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.27%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.63%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.63%   |
| Intel Pentium M processor 1.00GHz             | 1         | 0.63%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.63%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.63%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.63%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.63%   |
| Intel Genuine processor 800MHz                | 1         | 0.63%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.63%   |
| Intel Core m3-7Y32 CPU @ 1.10GHz              | 1         | 0.63%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 38        | 24.05%  |
| Intel Core i5           | 36        | 22.78%  |
| Other                   | 16        | 10.13%  |
| Intel Celeron           | 13        | 8.23%   |
| AMD Ryzen 7             | 12        | 7.59%   |
| Intel Core i3           | 9         | 5.7%    |
| AMD Ryzen 5             | 7         | 4.43%   |
| Intel Atom              | 5         | 3.16%   |
| Intel Core 2 Duo        | 4         | 2.53%   |
| AMD Ryzen 9             | 4         | 2.53%   |
| Intel Core m3           | 3         | 1.9%    |
| Intel Xeon              | 2         | 1.27%   |
| Intel Pentium Dual-Core | 2         | 1.27%   |
| AMD Ryzen 7 PRO         | 2         | 1.27%   |
| Intel Pentium M         | 1         | 0.63%   |
| Intel Pentium Gold      | 1         | 0.63%   |
| Intel Pentium Dual      | 1         | 0.63%   |
| Intel Genuine           | 1         | 0.63%   |
| Intel Core 2            | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 60        | 37.97%  |
| 4      | 50        | 31.65%  |
| 8      | 20        | 12.66%  |
| 6      | 14        | 8.86%   |
| 1      | 9         | 5.7%    |
| 14     | 3         | 1.9%    |
| 12     | 2         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 158       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 127       | 79.87%  |
| 1      | 32        | 20.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 143       | 90.51%  |
| 32-bit         | 9         | 5.7%    |
| Unknown        | 5         | 3.16%   |
| 64-bit         | 1         | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 19.38%  |
| 0x806ea    | 10        | 6.25%   |
| 0x806e9    | 10        | 6.25%   |
| 0x206a7    | 10        | 6.25%   |
| 0x906ea    | 8         | 5%      |
| 0x806c1    | 6         | 3.75%   |
| 0x506c9    | 5         | 3.13%   |
| 0x806ec    | 4         | 2.5%    |
| 0x406e3    | 4         | 2.5%    |
| 0x40651    | 4         | 2.5%    |
| 0x306a9    | 4         | 2.5%    |
| 0x106c2    | 4         | 2.5%    |
| 0x08600106 | 4         | 2.5%    |
| 0xa0652    | 3         | 1.88%   |
| 0x906a3    | 3         | 1.88%   |
| 0x806eb    | 3         | 1.88%   |
| 0x706e5    | 3         | 1.88%   |
| 0x20655    | 3         | 1.88%   |
| 0x1067a    | 3         | 1.88%   |
| 0x0a50000c | 3         | 1.88%   |
| 0x08600104 | 3         | 1.88%   |
| 0x08108102 | 3         | 1.88%   |
| 0x906e9    | 2         | 1.25%   |
| 0x806d1    | 2         | 1.25%   |
| 0x706a8    | 2         | 1.25%   |
| 0x6fd      | 2         | 1.25%   |
| 0x66a      | 2         | 1.25%   |
| 0x506e3    | 2         | 1.25%   |
| 0x306d4    | 2         | 1.25%   |
| 0x306c3    | 2         | 1.25%   |
| 0x0a50000b | 2         | 1.25%   |
| 0x08600103 | 2         | 1.25%   |
| 0x706a1    | 1         | 0.63%   |
| 0x6fb      | 1         | 0.63%   |
| 0x6f6      | 1         | 0.63%   |
| 0x6d8      | 1         | 0.63%   |
| 0x6d6      | 1         | 0.63%   |
| 0x406c3    | 1         | 0.63%   |
| 0x30678    | 1         | 0.63%   |
| 0x20652    | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 25.32%  |
| SandyBridge      | 13        | 8.23%   |
| Zen 2            | 12        | 7.59%   |
| TigerLake        | 9         | 5.7%    |
| Haswell          | 8         | 5.06%   |
| Unknown          | 8         | 5.06%   |
| Zen 3            | 7         | 4.43%   |
| Skylake          | 7         | 4.43%   |
| IvyBridge        | 7         | 4.43%   |
| IceLake          | 6         | 3.8%    |
| Goldmont         | 5         | 3.16%   |
| Zen+             | 4         | 2.53%   |
| Westmere         | 4         | 2.53%   |
| Penryn           | 4         | 2.53%   |
| Core             | 4         | 2.53%   |
| CometLake        | 4         | 2.53%   |
| Bonnell          | 4         | 2.53%   |
| Goldmont plus    | 3         | 1.9%    |
| Broadwell        | 3         | 1.9%    |
| Silvermont       | 2         | 1.27%   |
| P6               | 2         | 1.27%   |
| Alderlake Hybrid | 2         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 122       | 59.8%   |
| Nvidia      | 48        | 23.53%  |
| AMD         | 31        | 15.2%   |
| Neomagic    | 2         | 0.98%   |
| S3 Graphics | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 6.19%   |
| Intel UHD Graphics 620                                                        | 10        | 4.76%   |
| AMD Renoir                                                                    | 10        | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 8         | 3.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 3.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 6         | 2.86%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 2.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 2.86%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 2.38%   |
| Intel HD Graphics 620                                                         | 5         | 2.38%   |
| Intel HD Graphics 500                                                         | 5         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 4         | 1.9%    |
| Intel HD Graphics 615                                                         | 4         | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 1.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 4         | 1.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.9%    |
| Nvidia GP108M [GeForce MX150]                                                 | 3         | 1.43%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 3         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 1.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 1.43%   |
| Intel HD Graphics 5500                                                        | 3         | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.43%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 2         | 0.95%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 2         | 0.95%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 0.95%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 0.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 0.95%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.95%   |
| Intel HD Graphics 530                                                         | 2         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 0.95%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 0.95%   |
| AMD Rembrandt [Radeon 680M]                                                   | 2         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 84        | 53.16%  |
| Intel + Nvidia  | 32        | 20.25%  |
| 1 x AMD         | 17        | 10.76%  |
| AMD + Nvidia    | 8         | 5.06%   |
| 1 x Nvidia      | 7         | 4.43%   |
| Intel + AMD     | 6         | 3.8%    |
| 1 x Neomagic    | 2         | 1.27%   |
| Other           | 1         | 0.63%   |
| 1 x S3 Graphics | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 126       | 79.75%  |
| Proprietary | 25        | 15.82%  |
| Unknown     | 7         | 4.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 67.92%  |
| 0.01-0.5   | 15        | 9.43%   |
| 1.01-2.0   | 14        | 8.81%   |
| 3.01-4.0   | 7         | 4.4%    |
| 0.51-1.0   | 6         | 3.77%   |
| 5.01-6.0   | 5         | 3.14%   |
| 7.01-8.0   | 4         | 2.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 33        | 20%     |
| AU Optronics            | 29        | 17.58%  |
| LG Display              | 22        | 13.33%  |
| Chimei Innolux          | 17        | 10.3%   |
| Sharp                   | 9         | 5.45%   |
| Samsung Electronics     | 9         | 5.45%   |
| Dell                    | 7         | 4.24%   |
| Apple                   | 4         | 2.42%   |
| AOC                     | 4         | 2.42%   |
| Philips                 | 3         | 1.82%   |
| LG Philips              | 2         | 1.21%   |
| Lenovo                  | 2         | 1.21%   |
| InfoVision              | 2         | 1.21%   |
| CPT                     | 2         | 1.21%   |
| Chi Mei Optoelectronics | 2         | 1.21%   |
| Unknown (DAE)           | 1         | 0.61%   |
| TMX                     | 1         | 0.61%   |
| Sony                    | 1         | 0.61%   |
| RGT                     | 1         | 0.61%   |
| PANDA                   | 1         | 0.61%   |
| MStar                   | 1         | 0.61%   |
| Mi                      | 1         | 0.61%   |
| Lenovo Group Limited    | 1         | 0.61%   |
| JXC                     | 1         | 0.61%   |
| JDI                     | 1         | 0.61%   |
| ITE                     | 1         | 0.61%   |
| IPS                     | 1         | 0.61%   |
| InnoLux Display         | 1         | 0.61%   |
| Hewlett-Packard         | 1         | 0.61%   |
| Goldstar                | 1         | 0.61%   |
| CSO                     | 1         | 0.61%   |
| Ancor Communications    | 1         | 0.61%   |
| Acer                    | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 1.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.81%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 1.81%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 1.2%    |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 1.2%    |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 1.2%    |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.2%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 1.2%    |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch        | 2         | 1.2%    |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.6%    |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 0.6%    |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 0.6%    |
| Sharp LQ133M1JW48 SHP14F5 1920x1080 294x165mm 13.3-inch               | 1         | 0.6%    |
| Sharp LQ133M1JW35 SHP14B0 1920x1080 294x165mm 13.3-inch               | 1         | 0.6%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.6%    |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.6%    |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                 | 1         | 0.6%    |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 1         | 0.6%    |
| Philips PHL 272P7VU PHL093A 3840x2160 597x336mm 27.0-inch             | 1         | 0.6%    |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1         | 0.6%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| MStar Demo MST0030 1920x1080 1150x650mm 52.0-inch                     | 1         | 0.6%    |
| Mi Monitor XMI23C2 1920x1080 530x290mm 23.8-inch                      | 1         | 0.6%    |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.6%    |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD06A5 1920x1080 344x194mm 15.5-inch          | 1         | 0.6%    |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 79        | 50.97%  |
| 1366x768 (WXGA)   | 22        | 14.19%  |
| 3840x2160 (4K)    | 9         | 5.81%   |
| 2560x1440 (QHD)   | 6         | 3.87%   |
| 1600x900 (HD+)    | 6         | 3.87%   |
| 1280x800 (WXGA)   | 5         | 3.23%   |
| 2560x1600         | 4         | 2.58%   |
| 2880x1800         | 3         | 1.94%   |
| 3840x2400         | 2         | 1.29%   |
| 3440x1440         | 2         | 1.29%   |
| 1440x900 (WXGA+)  | 2         | 1.29%   |
| 3840x1600         | 1         | 0.65%   |
| 3520x1080         | 1         | 0.65%   |
| 3456x2160         | 1         | 0.65%   |
| 3200x2000         | 1         | 0.65%   |
| 3200x1800 (QHD+)  | 1         | 0.65%   |
| 2880x1920         | 1         | 0.65%   |
| 2400x1600         | 1         | 0.65%   |
| 2304x1440         | 1         | 0.65%   |
| 2256x1504         | 1         | 0.65%   |
| 2240x1400         | 1         | 0.65%   |
| 2160x1440         | 1         | 0.65%   |
| 1920x1200 (WUXGA) | 1         | 0.65%   |
| 1024x600          | 1         | 0.65%   |
| 1024x576          | 1         | 0.65%   |
| Unknown           | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 51        | 31.1%   |
| 13      | 33        | 20.12%  |
| 14      | 28        | 17.07%  |
| 12      | 10        | 6.1%    |
| 21      | 6         | 3.66%   |
| 17      | 5         | 3.05%   |
| 24      | 4         | 2.44%   |
| 23      | 4         | 2.44%   |
| 31      | 3         | 1.83%   |
| 27      | 3         | 1.83%   |
| 10      | 3         | 1.83%   |
| Unknown | 3         | 1.83%   |
| 34      | 2         | 1.22%   |
| 19      | 2         | 1.22%   |
| 72      | 1         | 0.61%   |
| 52      | 1         | 0.61%   |
| 40      | 1         | 0.61%   |
| 37      | 1         | 0.61%   |
| 16      | 1         | 0.61%   |
| 11      | 1         | 0.61%   |
| 8       | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 56.44%  |
| 201-300     | 34        | 20.86%  |
| 501-600     | 11        | 6.75%   |
| 401-500     | 7         | 4.29%   |
| 351-400     | 6         | 3.68%   |
| 601-700     | 3         | 1.84%   |
| Unknown     | 3         | 1.84%   |
| 801-900     | 2         | 1.23%   |
| 701-800     | 2         | 1.23%   |
| 1501-2000   | 1         | 0.61%   |
| 101-200     | 1         | 0.61%   |
| 1001-1500   | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 120       | 81.08%  |
| 16/10   | 19        | 12.84%  |
| 3/2     | 4         | 2.7%    |
| 21/9    | 3         | 2.03%   |
| 0.62    | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 30.91%  |
| 81-90          | 45        | 27.27%  |
| 71-80          | 17        | 10.3%   |
| 201-250        | 12        | 7.27%   |
| 61-70          | 9         | 5.45%   |
| 351-500        | 6         | 3.64%   |
| 121-130        | 5         | 3.03%   |
| 41-50          | 3         | 1.82%   |
| 301-350        | 3         | 1.82%   |
| 151-200        | 3         | 1.82%   |
| Unknown        | 3         | 1.82%   |
| More than 1000 | 2         | 1.21%   |
| 51-60          | 1         | 0.61%   |
| 1-40           | 1         | 0.61%   |
| 251-300        | 1         | 0.61%   |
| 111-120        | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |
| 91-100         | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 45.63%  |
| 101-120       | 29        | 18.13%  |
| 161-240       | 23        | 14.38%  |
| 51-100        | 15        | 9.38%   |
| More than 240 | 14        | 8.75%   |
| 1-50          | 3         | 1.88%   |
| Unknown       | 3         | 1.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 128       | 80.5%   |
| 2     | 24        | 15.09%  |
| 0     | 6         | 3.77%   |
| 3     | 1         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 95        | 40.25%  |
| Realtek Semiconductor    | 67        | 28.39%  |
| Qualcomm Atheros         | 28        | 11.86%  |
| Broadcom                 | 12        | 5.08%   |
| MediaTek                 | 7         | 2.97%   |
| Ralink Technology        | 4         | 1.69%   |
| Qualcomm                 | 3         | 1.27%   |
| Marvell Technology Group | 3         | 1.27%   |
| Broadcom Limited         | 3         | 1.27%   |
| ASIX Electronics         | 3         | 1.27%   |
| Xiaomi                   | 1         | 0.42%   |
| Texas Instruments        | 1         | 0.42%   |
| SEGGER                   | 1         | 0.42%   |
| Ralink                   | 1         | 0.42%   |
| OPPO Electronics         | 1         | 0.42%   |
| NetGear                  | 1         | 0.42%   |
| Lenovo                   | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| Fitbit                   | 1         | 0.42%   |
| DisplayLink              | 1         | 0.42%   |
| Apple                    | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 37        | 12.89%  |
| Intel Wi-Fi 6 AX200                                                     | 15        | 5.23%   |
| Intel Wireless 8265 / 8275                                              | 10        | 3.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 3.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 3.14%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 2.09%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.74%   |
| Intel Wireless 8260                                                     | 5         | 1.74%   |
| Intel Wireless 7265                                                     | 5         | 1.74%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.39%   |
| Intel Wireless 7260                                                     | 4         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.39%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.05%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.05%   |
| Intel 82579V Gigabit Network Connection                                 | 3         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.7%    |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 90        | 55.21%  |
| Qualcomm Atheros      | 25        | 15.34%  |
| Realtek Semiconductor | 19        | 11.66%  |
| Broadcom              | 11        | 6.75%   |
| MediaTek              | 7         | 4.29%   |
| Ralink Technology     | 4         | 2.45%   |
| Qualcomm              | 3         | 1.84%   |
| Texas Instruments     | 1         | 0.61%   |
| Ralink                | 1         | 0.61%   |
| NetGear               | 1         | 0.61%   |
| Broadcom Limited      | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 15        | 9.15%   |
| Intel Wireless 8265 / 8275                                                                    | 10        | 6.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 7         | 4.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6         | 3.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 6         | 3.66%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 5         | 3.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 5         | 3.05%   |
| Intel Wireless 8260                                                                           | 5         | 3.05%   |
| Intel Wireless 7265                                                                           | 5         | 3.05%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 3.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 2.44%   |
| Intel Wireless 7260                                                                           | 4         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4         | 2.44%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 1.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 3         | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 3         | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 1.83%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 1.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 3         | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.22%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 2         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.22%   |
| Qualcomm QCA6390 Wireless Network Adapter                                                     | 2         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2         | 1.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 1.22%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 2         | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 1.22%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                                           | 1         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.61%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                        | 1         | 0.61%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                                     | 1         | 0.61%   |
| Realtek Realtek Network controller                                                            | 1         | 0.61%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 57        | 47.9%   |
| Intel                    | 40        | 33.61%  |
| Qualcomm Atheros         | 6         | 5.04%   |
| Marvell Technology Group | 3         | 2.52%   |
| ASIX Electronics         | 3         | 2.52%   |
| Broadcom Limited         | 2         | 1.68%   |
| Broadcom                 | 2         | 1.68%   |
| Xiaomi                   | 1         | 0.84%   |
| OPPO Electronics         | 1         | 0.84%   |
| Lenovo                   | 1         | 0.84%   |
| Huawei Technologies      | 1         | 0.84%   |
| DisplayLink              | 1         | 0.84%   |
| Apple                    | 1         | 0.84%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 30.83%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 7.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 7.5%    |
| Intel Ethernet Connection (4) I219-V                              | 7         | 5.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5%      |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.5%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.83%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.83%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 0.83%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.83%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.83%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.83%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.83%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.83%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.83%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.83%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 0.83%   |
| Huawei SNE-LX1                                                    | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 156       | 57.56%  |
| Ethernet | 112       | 41.33%  |
| Modem    | 2         | 0.74%   |
| Unknown  | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 82.04%  |
| Ethernet | 30        | 17.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 98        | 62.03%  |
| 1     | 53        | 33.54%  |
| 0     | 7         | 4.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 158       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 59.17%  |
| Foxconn / Hon Hai               | 8         | 6.67%   |
| Qualcomm Atheros Communications | 7         | 5.83%   |
| Broadcom                        | 6         | 5%      |
| Realtek Semiconductor           | 4         | 3.33%   |
| Lite-On Technology              | 4         | 3.33%   |
| IMC Networks                    | 4         | 3.33%   |
| Realtek                         | 3         | 2.5%    |
| Hewlett-Packard                 | 3         | 2.5%    |
| Foxconn International           | 2         | 1.67%   |
| Dell                            | 2         | 1.67%   |
| Apple                           | 2         | 1.67%   |
| Taiyo Yuden                     | 1         | 0.83%   |
| Fujitsu                         | 1         | 0.83%   |
| Cambridge Silicon Radio         | 1         | 0.83%   |
| Askey Computer                  | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 18.33%  |
| Intel AX200 Bluetooth                               | 15        | 12.5%   |
| Intel AX201 Bluetooth                               | 14        | 11.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 10.83%  |
| Realtek Bluetooth Radio                             | 4         | 3.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.33%   |
| Realtek Bluetooth Radio                             | 3         | 2.5%    |
| Intel Bluetooth Device                              | 3         | 2.5%    |
| IMC Networks Wireless_Device                        | 3         | 2.5%    |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 2.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.67%   |
| Intel AX210 Bluetooth                               | 2         | 1.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.67%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.83%   |
| Lite-On Bluetooth Radio                             | 1         | 0.83%   |
| Lite-On Bluetooth Device                            | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.83%   |
| IMC Networks Bluetooth Device                       | 1         | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.83%   |
| Fujitsu Bluetooth Device                            | 1         | 0.83%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.83%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.83%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.83%   |
| Broadcom BCM2045A0                                  | 1         | 0.83%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.83%   |
| Askey Bluetooth Device                              | 1         | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.83%   |
| Apple Bluetooth Host Controller                     | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 126       | 67.38%  |
| AMD                         | 26        | 13.9%   |
| Nvidia                      | 25        | 13.37%  |
| Generalplus Technology      | 2         | 1.07%   |
| ESS Technology              | 2         | 1.07%   |
| VIA Technologies            | 1         | 0.53%   |
| Logitech                    | 1         | 0.53%   |
| iCreate Technologies        | 1         | 0.53%   |
| FiiO Electronics Technology | 1         | 0.53%   |
| BY EDIFIER                  | 1         | 0.53%   |
| Apple                       | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 25        | 11.52%  |
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 11.06%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 5.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 5.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 4.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.84%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.84%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.38%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.38%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.92%   |
| Nvidia Audio device                                                        | 2         | 0.92%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.92%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.92%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 0.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 0.92%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 36        | 31.58%  |
| Samsung Electronics | 32        | 28.07%  |
| Unknown             | 12        | 10.53%  |
| Micron Technology   | 12        | 10.53%  |
| Unknown             | 6         | 5.26%   |
| Kingston            | 5         | 4.39%   |
| Crucial             | 3         | 2.63%   |
| Unknown (ABCD)      | 2         | 1.75%   |
| Team                | 1         | 0.88%   |
| Nanya Technology    | 1         | 0.88%   |
| Lenovo              | 1         | 0.88%   |
| Kingmax             | 1         | 0.88%   |
| Elpida              | 1         | 0.88%   |
| A-DATA Technology   | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 6         | 5.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 3.39%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 4         | 3.39%   |
| Unknown RAM Module 2GB DIMM SDRAM                             | 2         | 1.69%   |
| Unknown RAM Module 256MB SODIMM DRAM                          | 2         | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s  | 2         | 1.69%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                  | 2         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 1.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 1.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 2         | 1.69%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 2         | 1.69%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 2         | 1.69%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s        | 2         | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s      | 2         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 1.69%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 2         | 1.69%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 2         | 1.69%   |
| Unknown RAM Module 512MB SODIMM DRAM                          | 1         | 0.85%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR                             | 1         | 0.85%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                 | 1         | 0.85%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s          | 1         | 0.85%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.85%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 0.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.85%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s | 1         | 0.85%   |
| SK hynix RAM HMAA4GS7AJR8N-WM 32GB SODIMM DDR4 2933MT/s       | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s  | 1         | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 1         | 0.85%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16384MB SODIMM DDR4 2400MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 0.85%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 43        | 45.26%  |
| DDR3    | 16        | 16.84%  |
| LPDDR3  | 11        | 11.58%  |
| LPDDR4  | 8         | 8.42%   |
| DDR2    | 7         | 7.37%   |
| DRAM    | 3         | 3.16%   |
| SDRAM   | 2         | 2.11%   |
| Unknown | 2         | 2.11%   |
| LPDDR5  | 1         | 1.05%   |
| DDR5    | 1         | 1.05%   |
| DDR     | 1         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 72.34%  |
| Row Of Chips | 20        | 21.28%  |
| DIMM         | 5         | 5.32%   |
| Unknown      | 1         | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 40        | 37.74%  |
| 4096  | 24        | 22.64%  |
| 2048  | 12        | 11.32%  |
| 16384 | 11        | 10.38%  |
| 32768 | 8         | 7.55%   |
| 1024  | 5         | 4.72%   |
| 256   | 2         | 1.89%   |
| 64    | 2         | 1.89%   |
| 512   | 1         | 0.94%   |
| 232   | 1         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 21        | 20.79%  |
| 3200    | 17        | 16.83%  |
| 1600    | 14        | 13.86%  |
| 2133    | 9         | 8.91%   |
| 2400    | 6         | 5.94%   |
| Unknown | 6         | 5.94%   |
| 1867    | 5         | 4.95%   |
| 4267    | 4         | 3.96%   |
| 667     | 3         | 2.97%   |
| 3266    | 2         | 1.98%   |
| 1334    | 2         | 1.98%   |
| 533     | 2         | 1.98%   |
| 6400    | 1         | 0.99%   |
| 4800    | 1         | 0.99%   |
| 4266    | 1         | 0.99%   |
| 3733    | 1         | 0.99%   |
| 2933    | 1         | 0.99%   |
| 1067    | 1         | 0.99%   |
| 1066    | 1         | 0.99%   |
| 975     | 1         | 0.99%   |
| 333     | 1         | 0.99%   |
| 200     | 1         | 0.99%   |

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
| Chicony Electronics                    | 30        | 23.08%  |
| IMC Networks                           | 15        | 11.54%  |
| Acer                                   | 11        | 8.46%   |
| Microdia                               | 10        | 7.69%   |
| Realtek Semiconductor                  | 7         | 5.38%   |
| Luxvisions Innotech Limited            | 7         | 5.38%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.38%   |
| Sunplus Innovation Technology          | 5         | 3.85%   |
| Apple                                  | 5         | 3.85%   |
| Syntek                                 | 4         | 3.08%   |
| Suyin                                  | 3         | 2.31%   |
| Silicon Motion                         | 3         | 2.31%   |
| Quanta                                 | 3         | 2.31%   |
| Alcor Micro                            | 3         | 2.31%   |
| Lite-On Technology                     | 2         | 1.54%   |
| Importek                               | 2         | 1.54%   |
| Xiaomi                                 | 1         | 0.77%   |
| WaveRider Communications               | 1         | 0.77%   |
| USB Camera                             | 1         | 0.77%   |
| Tripath Technology                     | 1         | 0.77%   |
| Sonix Technology                       | 1         | 0.77%   |
| Ricoh                                  | 1         | 0.77%   |
| Primax Electronics                     | 1         | 0.77%   |
| Nebraska Furniture Mart                | 1         | 0.77%   |
| Microsoft                              | 1         | 0.77%   |
| Logitech                               | 1         | 0.77%   |
| lihappe8                               | 1         | 0.77%   |
| Genesys Logic                          | 1         | 0.77%   |
| eMPIA Technology                       | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 9         | 6.82%   |
| Microdia Integrated_Webcam_HD                                   | 8         | 6.06%   |
| IMC Networks Integrated Camera                                  | 7         | 5.3%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 3.79%   |
| Chicony FJ Camera                                               | 5         | 3.79%   |
| Syntek Integrated Camera                                        | 4         | 3.03%   |
| Chicony HD Webcam                                               | 4         | 3.03%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 2.27%   |
| Luxvisions Innotech Limited HP HD Camera                        | 3         | 2.27%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 2.27%   |
| Acer Integrated Camera                                          | 3         | 2.27%   |
| Sunplus HD WebCam                                               | 2         | 1.52%   |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 1.52%   |
| Lite-On Integrated Camera                                       | 2         | 1.52%   |
| Importek FJ Camera                                              | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.52%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 2         | 1.52%   |
| Apple FaceTime HD Camera (Built-in)                             | 2         | 1.52%   |
| Acer SunplusIT Integrated Camera                                | 2         | 1.52%   |
| Acer Lenovo EasyCamera                                          | 2         | 1.52%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                              | 1         | 0.76%   |
| WaveRider USB 2.0 Camera                                        | 1         | 0.76%   |
| USB Camera USB Camera                                           | 1         | 0.76%   |
| Tripath USB Camera                                              | 1         | 0.76%   |
| Suyin Integrated Webcam                                         | 1         | 0.76%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 1         | 0.76%   |
| Suyin HP Truevision HD                                          | 1         | 0.76%   |
| Sunplus ZCF-171115                                              | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 0.76%   |
| Sunplus HP Universal Camera                                     | 1         | 0.76%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 0.76%   |
| Silicon Motion Lenovo EasyCamera                                | 1         | 0.76%   |
| Silicon Motion 720p HD Camera                                   | 1         | 0.76%   |
| Silicon Motion 300k Pixel Camera                                | 1         | 0.76%   |
| Ricoh USB2.0 Camera                                             | 1         | 0.76%   |
| Realtek WebCamera                                               | 1         | 0.76%   |
| Realtek USB2.0 HD UVC WebCam                                    | 1         | 0.76%   |
| Realtek Lenovo easy camera                                      | 1         | 0.76%   |
| Realtek Integrated Webcam_HD                                    | 1         | 0.76%   |
| Quanta USB Webcam                                               | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 36.36%  |
| Validity Sensors           | 8         | 24.24%  |
| Shenzhen Goodix Technology | 6         | 18.18%  |
| AuthenTec                  | 3         | 9.09%   |
| Upek                       | 2         | 6.06%   |
| Samsung Electronics        | 1         | 3.03%   |
| LighTuning Technology      | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader       | 6         | 18.18%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 15.15%  |
| Validity Sensors Synaptics WBDI                        | 3         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 6.06%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 6.06%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 6.06%   |
| Shenzhen Goodix FingerPrint                            | 2         | 6.06%   |
| AuthenTec Fingerprint Sensor                           | 2         | 6.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.03%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.03%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.03%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 3.03%   |
| Samsung Fingerprint Device                             | 1         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.03%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 3.03%   |
| Unknown                                                | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 38.46%  |
| Upek        | 3         | 23.08%  |
| Lenovo      | 2         | 15.38%  |
| Alcor Micro | 2         | 15.38%  |
| O2 Micro    | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 23.08%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 15.38%  |
| Broadcom 5880                                                                | 2         | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 92        | 56.79%  |
| 1     | 53        | 32.72%  |
| 2     | 11        | 6.79%   |
| 3     | 4         | 2.47%   |
| 5     | 1         | 0.62%   |
| 4     | 1         | 0.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 32.63%  |
| Graphics card            | 23        | 24.21%  |
| Chipcard                 | 13        | 13.68%  |
| Multimedia controller    | 9         | 9.47%   |
| Net/wireless             | 8         | 8.42%   |
| Communication controller | 3         | 3.16%   |
| Bluetooth                | 3         | 3.16%   |
| Storage                  | 1         | 1.05%   |
| Sound                    | 1         | 1.05%   |
| Net/ethernet             | 1         | 1.05%   |
| Card reader              | 1         | 1.05%   |
| Camera                   | 1         | 1.05%   |

