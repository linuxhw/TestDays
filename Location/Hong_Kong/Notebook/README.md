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

Total: 239

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 29        | 17.06%  |
| Ubuntu 18.04        | 9         | 5.29%   |
| Ubuntu 22.04        | 8         | 4.71%   |
| Arch                | 8         | 4.71%   |
| antiX 21            | 8         | 4.71%   |
| Fedora 32           | 5         | 2.94%   |
| Ubuntu 19.10        | 4         | 2.35%   |
| Gentoo 2.7          | 4         | 2.35%   |
| EndeavourOS Rolling | 4         | 2.35%   |
| Arch Rolling        | 4         | 2.35%   |
| OpenMandriva 4.2    | 3         | 1.76%   |
| Linux Mint 20       | 3         | 1.76%   |
| Fedora 36           | 3         | 1.76%   |
| Fedora 33           | 3         | 1.76%   |
| Debian 11           | 3         | 1.76%   |
| Chrome OS           | 3         | 1.76%   |
| ArcoLinux Rolling   | 3         | 1.76%   |
| Ubuntu 22.10        | 2         | 1.18%   |
| Ubuntu 21.04        | 2         | 1.18%   |
| Ubuntu 19.04        | 2         | 1.18%   |
| Ubuntu 16.04        | 2         | 1.18%   |
| Pop!_OS 22.04       | 2         | 1.18%   |
| Pop!_OS 20.10       | 2         | 1.18%   |
| Pop!_OS 20.04       | 2         | 1.18%   |
| OpenMandriva 4.50   | 2         | 1.18%   |
| Manjaro 20.1        | 2         | 1.18%   |
| Linux Mint 20.3     | 2         | 1.18%   |
| KDE neon 20.04      | 2         | 1.18%   |
| Gentoo 2.8          | 2         | 1.18%   |
| Fedora 37           | 2         | 1.18%   |
| Fedora 34           | 2         | 1.18%   |
| Debian Testing      | 2         | 1.18%   |
| Zorin 15            | 1         | 0.59%   |
| UbuntuDDE 21.10     | 1         | 0.59%   |
| Ubuntu Unity 22.04  | 1         | 0.59%   |
| Ubuntu Unity 20.04  | 1         | 0.59%   |
| Ubuntu Unity 18.04  | 1         | 0.59%   |
| Ubuntu Budgie 20.04 | 1         | 0.59%   |
| Ubuntu 21.10        | 1         | 0.59%   |
| Ubuntu 20.10        | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 59        | 35.76%  |
| Fedora        | 17        | 10.3%   |
| Arch          | 12        | 7.27%   |
| Pop!_OS       | 8         | 4.85%   |
| antiX         | 8         | 4.85%   |
| OpenMandriva  | 7         | 4.24%   |
| Linux Mint    | 7         | 4.24%   |
| Manjaro       | 5         | 3.03%   |
| Gentoo        | 5         | 3.03%   |
| Debian        | 5         | 3.03%   |
| EndeavourOS   | 4         | 2.42%   |
| Clear Linux   | 4         | 2.42%   |
| Ubuntu Unity  | 3         | 1.82%   |
| Chrome OS     | 3         | 1.82%   |
| ArcoLinux     | 3         | 1.82%   |
| ROSA          | 2         | 1.21%   |
| KDE neon      | 2         | 1.21%   |
| Zorin         | 1         | 0.61%   |
| UbuntuDDE     | 1         | 0.61%   |
| Ubuntu Budgie | 1         | 0.61%   |
| SteamOS       | 1         | 0.61%   |
| PCLinuxOS     | 1         | 0.61%   |
| Oracle Linux  | 1         | 0.61%   |
| openSUSE      | 1         | 0.61%   |
| Kubuntu       | 1         | 0.61%   |
| Kali          | 1         | 0.61%   |
| Elementary    | 1         | 0.61%   |
| BlackPanther  | 1         | 0.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp           | 8         | 4.4%    |
| 5.4.0-42-generic                    | 6         | 3.3%    |
| 5.8.0-43-generic                    | 3         | 1.65%   |
| 5.4.0-48-generic                    | 3         | 1.65%   |
| 5.15.0-46-generic                   | 3         | 1.65%   |
| 5.13.0-39-generic                   | 3         | 1.65%   |
| 5.10.14-desktop-1omv4002            | 3         | 1.65%   |
| 4.19.49+                            | 3         | 1.65%   |
| 6.0.12-300.fc37.x86_64              | 2         | 1.1%    |
| 5.9.2-arch1-1                       | 2         | 1.1%    |
| 5.8.0-7630-generic                  | 2         | 1.1%    |
| 5.4.0-58-generic                    | 2         | 1.1%    |
| 5.4.0-28-generic                    | 2         | 1.1%    |
| 5.4.0-26-generic                    | 2         | 1.1%    |
| 5.3.0-18-generic                    | 2         | 1.1%    |
| 5.17.11-300.fc36.x86_64             | 2         | 1.1%    |
| 5.15.0-47-generic                   | 2         | 1.1%    |
| 5.13.0-35-generic                   | 2         | 1.1%    |
| 5.11.0-37-generic                   | 2         | 1.1%    |
| 5.0.0-31-generic                    | 2         | 1.1%    |
| 4.18.0-15-generic                   | 2         | 1.1%    |
| 6.1.0-asahi                         | 1         | 0.55%   |
| 6.0.10-1215.native                  | 1         | 0.55%   |
| 6.0.0-rc1-asahi-00175-g01a8389621b6 | 1         | 0.55%   |
| 6.0.0-060000-generic                | 1         | 0.55%   |
| 5.9.8-200.fc33.x86_64               | 1         | 0.55%   |
| 5.9.3-arch1-1                       | 1         | 0.55%   |
| 5.9.14-100.fc32.x86_64              | 1         | 0.55%   |
| 5.9.10-artix1-1                     | 1         | 0.55%   |
| 5.8.6-1-MANJARO                     | 1         | 0.55%   |
| 5.8.3-2-MANJARO                     | 1         | 0.55%   |
| 5.8.15-gentoo                       | 1         | 0.55%   |
| 5.8.0-64-generic                    | 1         | 0.55%   |
| 5.8.0-63-generic                    | 1         | 0.55%   |
| 5.8.0-55-generic                    | 1         | 0.55%   |
| 5.8.0-54-generic                    | 1         | 0.55%   |
| 5.8.0-33-generic                    | 1         | 0.55%   |
| 5.8.0-25-generic                    | 1         | 0.55%   |
| 5.7.9-200.fc32.x86_64               | 1         | 0.55%   |
| 5.7.4-gentoo                        | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 12.14%  |
| 5.15.0  | 11        | 6.36%   |
| 5.13.0  | 11        | 6.36%   |
| 5.8.0   | 9         | 5.2%    |
| 4.9.0   | 8         | 4.62%   |
| 4.15.0  | 7         | 4.05%   |
| 5.11.0  | 6         | 3.47%   |
| 5.3.0   | 5         | 2.89%   |
| 5.19.0  | 5         | 2.89%   |
| 5.0.0   | 5         | 2.89%   |
| 5.10.14 | 3         | 1.73%   |
| 4.19.49 | 3         | 1.73%   |
| 6.0.12  | 2         | 1.16%   |
| 6.0.0   | 2         | 1.16%   |
| 5.9.2   | 2         | 1.16%   |
| 5.17.4  | 2         | 1.16%   |
| 5.17.11 | 2         | 1.16%   |
| 5.10.0  | 2         | 1.16%   |
| 4.18.0  | 2         | 1.16%   |
| 6.1.0   | 1         | 0.58%   |
| 6.0.10  | 1         | 0.58%   |
| 5.9.8   | 1         | 0.58%   |
| 5.9.3   | 1         | 0.58%   |
| 5.9.14  | 1         | 0.58%   |
| 5.9.10  | 1         | 0.58%   |
| 5.8.6   | 1         | 0.58%   |
| 5.8.3   | 1         | 0.58%   |
| 5.8.15  | 1         | 0.58%   |
| 5.7.9   | 1         | 0.58%   |
| 5.7.4   | 1         | 0.58%   |
| 5.7.11  | 1         | 0.58%   |
| 5.7.10  | 1         | 0.58%   |
| 5.6.3   | 1         | 0.58%   |
| 5.4.17  | 1         | 0.58%   |
| 5.3.5   | 1         | 0.58%   |
| 5.3.14  | 1         | 0.58%   |
| 5.3.11  | 1         | 0.58%   |
| 5.19.8  | 1         | 0.58%   |
| 5.19.6  | 1         | 0.58%   |
| 5.19.5  | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 12.35%  |
| 5.15    | 15        | 8.82%   |
| 5.13    | 13        | 7.65%   |
| 5.8     | 12        | 7.06%   |
| 5.19    | 12        | 7.06%   |
| 5.11    | 12        | 7.06%   |
| 5.10    | 12        | 7.06%   |
| 4.9     | 10        | 5.88%   |
| 5.3     | 8         | 4.71%   |
| 5.17    | 8         | 4.71%   |
| 4.15    | 7         | 4.12%   |
| 5.9     | 6         | 3.53%   |
| 6.0     | 5         | 2.94%   |
| 5.0     | 5         | 2.94%   |
| 5.7     | 4         | 2.35%   |
| 5.16    | 4         | 2.35%   |
| 5.14    | 4         | 2.35%   |
| 5.18    | 3         | 1.76%   |
| 4.19    | 3         | 1.76%   |
| 4.18    | 3         | 1.76%   |
| 6.1     | 1         | 0.59%   |
| 5.6     | 1         | 0.59%   |
| 5.12    | 1         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 148       | 91.93%  |
| i686    | 11        | 6.83%   |
| i586    | 1         | 0.62%   |
| aarch64 | 1         | 0.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 80        | 48.78%  |
| KDE5       | 30        | 18.29%  |
| Unknown    | 29        | 17.68%  |
| XFCE       | 5         | 3.05%   |
| X-Cinnamon | 5         | 3.05%   |
| KDE        | 3         | 1.83%   |
| i3         | 3         | 1.83%   |
| Unity      | 2         | 1.22%   |
| dwm        | 2         | 1.22%   |
| LXQt       | 1         | 0.61%   |
| fvwm       | 1         | 0.61%   |
| Deepin     | 1         | 0.61%   |
| Cinnamon   | 1         | 0.61%   |
| Budgie     | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 127       | 77.91%  |
| Wayland | 26        | 15.95%  |
| Unknown | 9         | 5.52%   |
| Tty     | 1         | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 45.4%   |
| SDDM    | 28        | 17.18%  |
| GDM     | 28        | 17.18%  |
| GDM3    | 15        | 9.2%    |
| LightDM | 13        | 7.98%   |
| TDM     | 4         | 2.45%   |
| LXDM    | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 68        | 40.72%  |
| en_HK   | 33        | 19.76%  |
| zh_CN   | 21        | 12.57%  |
| Unknown | 19        | 11.38%  |
| zh_HK   | 7         | 4.19%   |
| zh_TW   | 6         | 3.59%   |
| C       | 6         | 3.59%   |
| en_GB   | 3         | 1.8%    |
| it_IT   | 1         | 0.6%    |
| en_ZA   | 1         | 0.6%    |
| en_AU   | 1         | 0.6%    |
| de_DE   | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 111       | 68.52%  |
| BIOS | 51        | 31.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 119       | 72.12%  |
| Btrfs   | 19        | 11.52%  |
| Overlay | 11        | 6.67%   |
| Unknown | 7         | 4.24%   |
| Zfs     | 3         | 1.82%   |
| Xfs     | 3         | 1.82%   |
| Ext2    | 2         | 1.21%   |
| Ext3    | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 79        | 48.17%  |
| Unknown | 69        | 42.07%  |
| MBR     | 16        | 9.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 88.89%  |
| Yes       | 18        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 61.35%  |
| Yes       | 63        | 38.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 50        | 31.06%  |
| Dell                 | 23        | 14.29%  |
| Hewlett-Packard      | 17        | 10.56%  |
| Fujitsu              | 12        | 7.45%   |
| ASUSTek Computer     | 12        | 7.45%   |
| Unknown              | 9         | 5.59%   |
| Acer                 | 6         | 3.73%   |
| Apple                | 5         | 3.11%   |
| HUAWEI               | 4         | 2.48%   |
| GPD                  | 3         | 1.86%   |
| Toshiba              | 2         | 1.24%   |
| Samsung Electronics  | 2         | 1.24%   |
| MSI                  | 2         | 1.24%   |
| KOHJINSHA            | 2         | 1.24%   |
| IBM                  | 2         | 1.24%   |
| Timi                 | 1         | 0.62%   |
| Sony                 | 1         | 0.62%   |
| Schenker             | 1         | 0.62%   |
| Panasonic            | 1         | 0.62%   |
| Jumper               | 1         | 0.62%   |
| Intel Client Systems | 1         | 0.62%   |
| Google               | 1         | 0.62%   |
| Compaq               | 1         | 0.62%   |
| Chuwi                | 1         | 0.62%   |
| AMI                  | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 10        | 6.21%   |
| Lenovo Legion R7000 2020 82B6            | 3         | 1.86%   |
| IBM 260921H                              | 2         | 1.24%   |
| HUAWEI KPRC-WX0                          | 2         | 1.24%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC         | 2         | 1.24%   |
| HP EliteBook 2540p                       | 2         | 1.24%   |
| Fujitsu UH-X                             | 2         | 1.24%   |
| Fujitsu LIFEBOOK AH544                   | 2         | 1.24%   |
| Dell XPS 13 9310                         | 2         | 1.24%   |
| Dell Inspiron 5580                       | 2         | 1.24%   |
| ASUS TUF Gaming FA506IU_FA506IU          | 2         | 1.24%   |
| Toshiba PORTEGE R830                     | 1         | 0.62%   |
| Toshiba dynabook R731/E                  | 1         | 0.62%   |
| Timi TM1607                              | 1         | 0.62%   |
| Sony VPCCB17FG                           | 1         | 0.62%   |
| Schenker XMG_APEX15_XAP15E20             | 1         | 0.62%   |
| Samsung SQ1S                             | 1         | 0.62%   |
| Samsung 930XBE                           | 1         | 0.62%   |
| Panasonic CFSZ5-2L                       | 1         | 0.62%   |
| MSI GS73VR 7RG                           | 1         | 0.62%   |
| MSI GS65 Stealth Thin 8RE                | 1         | 0.62%   |
| Lenovo ZHAOYANG K47                      | 1         | 0.62%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.62%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN        | 1         | 0.62%   |
| Lenovo XiaoXin-14API QC 2019 81UW        | 1         | 0.62%   |
| Lenovo XiaoXin Chao7000-14IKBR 81GA      | 1         | 0.62%   |
| Lenovo ThinkPad X270 20HNA00RAD          | 1         | 0.62%   |
| Lenovo ThinkPad X250 20CLA1VECD          | 1         | 0.62%   |
| Lenovo ThinkPad X220 4290NL5             | 1         | 0.62%   |
| Lenovo ThinkPad X13 Gen 1 20UFS01C00     | 1         | 0.62%   |
| Lenovo ThinkPad X1 Extreme 20MFS0PE00    | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1001BHH | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS9SA1N | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6J30S | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR003HHH | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBA05VCD | 1         | 0.62%   |
| Lenovo ThinkPad W530 24384KU             | 1         | 0.62%   |
| Lenovo ThinkPad T61 6465CTO              | 1         | 0.62%   |
| Lenovo ThinkPad T520 4242BC5             | 1         | 0.62%   |
| Lenovo ThinkPad T490s 20NYS79X00         | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 26        | 16.15%  |
| Unknown                 | 10        | 6.21%   |
| Fujitsu LIFEBOOK        | 8         | 4.97%   |
| Dell Inspiron           | 8         | 4.97%   |
| Lenovo Legion           | 7         | 4.35%   |
| Dell XPS                | 7         | 4.35%   |
| Lenovo IdeaPad          | 5         | 3.11%   |
| Dell Latitude           | 4         | 2.48%   |
| HP ZHAN                 | 3         | 1.86%   |
| HP EliteBook            | 3         | 1.86%   |
| Dell Precision          | 3         | 1.86%   |
| ASUS TUF                | 3         | 1.86%   |
| Acer Swift              | 3         | 1.86%   |
| Acer Aspire             | 3         | 1.86%   |
| Lenovo ThinkBook        | 2         | 1.24%   |
| IBM 260921H             | 2         | 1.24%   |
| HUAWEI KPRC-WX0         | 2         | 1.24%   |
| HP Pavilion             | 2         | 1.24%   |
| Fujitsu UH-X            | 2         | 1.24%   |
| ASUS ROG                | 2         | 1.24%   |
| Apple MacBookAir5       | 2         | 1.24%   |
| Toshiba PORTEGE         | 1         | 0.62%   |
| Toshiba dynabook        | 1         | 0.62%   |
| Timi TM1607             | 1         | 0.62%   |
| Sony VPCCB17FG          | 1         | 0.62%   |
| Schenker XMG            | 1         | 0.62%   |
| Samsung SQ1S            | 1         | 0.62%   |
| Samsung 930XBE          | 1         | 0.62%   |
| Panasonic CFSZ5-2L      | 1         | 0.62%   |
| MSI GS73VR              | 1         | 0.62%   |
| MSI GS65                | 1         | 0.62%   |
| Lenovo ZHAOYANG         | 1         | 0.62%   |
| Lenovo Yoga             | 1         | 0.62%   |
| Lenovo XiaoXinAir-14ARE | 1         | 0.62%   |
| Lenovo XiaoXin-14API    | 1         | 0.62%   |
| Lenovo XiaoXin          | 1         | 0.62%   |
| Lenovo G770             | 1         | 0.62%   |
| Lenovo G710             | 1         | 0.62%   |
| Lenovo E10-30           | 1         | 0.62%   |
| Lenovo 3000             | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 27        | 16.77%  |
| 2020    | 26        | 16.15%  |
| 2021    | 17        | 10.56%  |
| 2019    | 16        | 9.94%   |
| 2011    | 10        | 6.21%   |
| 2017    | 9         | 5.59%   |
| 2015    | 7         | 4.35%   |
| 2014    | 7         | 4.35%   |
| 2012    | 7         | 4.35%   |
| 2022    | 6         | 3.73%   |
| 2010    | 6         | 3.73%   |
| 2008    | 5         | 3.11%   |
| 2016    | 4         | 2.48%   |
| 2013    | 3         | 1.86%   |
| 2009    | 3         | 1.86%   |
| 2007    | 3         | 1.86%   |
| 1999    | 2         | 1.24%   |
| 2005    | 1         | 0.62%   |
| 2003    | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 161       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 139       | 86.34%  |
| Enabled  | 22        | 13.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 160       | 99.38%  |
| Yes  | 1         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 21.74%  |
| 16.01-24.0  | 34        | 21.12%  |
| 8.01-16.0   | 34        | 21.12%  |
| 32.01-64.0  | 17        | 10.56%  |
| 3.01-4.0    | 17        | 10.56%  |
| 2.01-3.0    | 5         | 3.11%   |
| 1.01-2.0    | 5         | 3.11%   |
| 24.01-32.0  | 4         | 2.48%   |
| 64.01-256.0 | 4         | 2.48%   |
| 0.51-1.0    | 4         | 2.48%   |
| 0.01-0.5    | 2         | 1.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 45        | 26.63%  |
| 2.01-3.0   | 36        | 21.3%   |
| 4.01-8.0   | 29        | 17.16%  |
| 3.01-4.0   | 25        | 14.79%  |
| 0.01-0.5   | 14        | 8.28%   |
| 8.01-16.0  | 12        | 7.1%    |
| 0.51-1.0   | 4         | 2.37%   |
| 16.01-24.0 | 3         | 1.78%   |
| 24.01-32.0 | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 60.48%  |
| 2      | 54        | 32.34%  |
| 3      | 8         | 4.79%   |
| 0      | 3         | 1.8%    |
| 5      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 80.37%  |
| Yes       | 32        | 19.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 71.6%   |
| No        | 46        | 28.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 98.76%  |
| No        | 2         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 75.93%  |
| No        | 39        | 24.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Hong Kong | 161       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Central       | 90        | 52.94%  |
| Shatin        | 10        | 5.88%   |
| Kowloon       | 8         | 4.71%   |
| Tseung Kwan O | 6         | 3.53%   |
| Wanchai       | 5         | 2.94%   |
| Tung Chung    | 5         | 2.94%   |
| Hong Kong     | 5         | 2.94%   |
| Hung Hom      | 4         | 2.35%   |
| Tuen Mun      | 3         | 1.76%   |
| Tai Po        | 3         | 1.76%   |
| Yuen Long     | 2         | 1.18%   |
| Sai Kung      | 2         | 1.18%   |
| Ngau Wu Tok   | 2         | 1.18%   |
| Man Kok       | 2         | 1.18%   |
| Discovery Bay | 2         | 1.18%   |
| Yau Tsim Mong | 1         | 0.59%   |
| Wong Tai Sin  | 1         | 0.59%   |
| Tsuen Wan     | 1         | 0.59%   |
| Tsimshatsui   | 1         | 0.59%   |
| To Kwa Wan    | 1         | 0.59%   |
| Tin Shui Wai  | 1         | 0.59%   |
| Tai Wan To    | 1         | 0.59%   |
| Tai Wan       | 1         | 0.59%   |
| So Kon Po     | 1         | 0.59%   |
| Sheung Shui   | 1         | 0.59%   |
| Shau Kei Wan  | 1         | 0.59%   |
| Quarry Bay    | 1         | 0.59%   |
| North Point   | 1         | 0.59%   |
| North         | 1         | 0.59%   |
| Mong Kok      | 1         | 0.59%   |
| Lam Tin       | 1         | 0.59%   |
| Kwun Hang     | 1         | 0.59%   |
| Ho Man Tin    | 1         | 0.59%   |
| Fanling       | 1         | 0.59%   |
| Causeway Bay  | 1         | 0.59%   |
| Unknown       | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 48     | 19.07%  |
| WDC                 | 25        | 26     | 11.63%  |
| Unknown             | 14        | 18     | 6.51%   |
| Seagate             | 14        | 15     | 6.51%   |
| SanDisk             | 14        | 16     | 6.51%   |
| SK hynix            | 11        | 12     | 5.12%   |
| Intel               | 11        | 13     | 5.12%   |
| Hitachi             | 8         | 8      | 3.72%   |
| Kingston            | 7         | 8      | 3.26%   |
| Toshiba             | 5         | 5      | 2.33%   |
| Micron Technology   | 5         | 6      | 2.33%   |
| HGST                | 5         | 6      | 2.33%   |
| Crucial             | 5         | 9      | 2.33%   |
| Apple               | 5         | 11     | 2.33%   |
| Fujitsu             | 4         | 6      | 1.86%   |
| Phison              | 3         | 3      | 1.4%    |
| KIOXIA              | 3         | 3      | 1.4%    |
| JMicron Technology  | 3         | 4      | 1.4%    |
| China               | 3         | 4      | 1.4%    |
| Plextor             | 2         | 3      | 0.93%   |
| KingSpec            | 2         | 3      | 0.93%   |
| HS-SSD-C100         | 2         | 3      | 0.93%   |
| Hikvision           | 2         | 2      | 0.93%   |
| BIWIN               | 2         | 2      | 0.93%   |
| Verbatim            | 1         | 2      | 0.47%   |
| Unknown (CF)        | 1         | 1      | 0.47%   |
| Transcend           | 1         | 1      | 0.47%   |
| TO Exter            | 1         | 1      | 0.47%   |
| Team                | 1         | 1      | 0.47%   |
| ShineDisk           | 1         | 1      | 0.47%   |
| RECADATA            | 1         | 1      | 0.47%   |
| Ramsta              | 1         | 1      | 0.47%   |
| PH4-CE12            | 1         | 1      | 0.47%   |
| Lexar               | 1         | 1      | 0.47%   |
| Lenovo              | 1         | 1      | 0.47%   |
| INTEL SS            | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 1      | 0.47%   |
| GALAX TA            | 1         | 1      | 0.47%   |
| Faspeed             | 1         | 1      | 0.47%   |
| DGM                 | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 4         | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.79%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 3         | 1.35%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 1.35%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.35%   |
| Samsung NVMe SSD Drive 512GB         | 3         | 1.35%   |
| WDC WD10SPZX-22Z10T1 1TB             | 2         | 0.9%    |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 2         | 0.9%    |
| Unknown MMC Card  128GB              | 2         | 0.9%    |
| Toshiba MQ01ABF050 500GB             | 2         | 0.9%    |
| SK hynix BC501 NVMe 128GB            | 2         | 0.9%    |
| SanDisk NVMe SSD Drive 256GB         | 2         | 0.9%    |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 0.9%    |
| Samsung NVMe SSD Drive 1TB           | 2         | 0.9%    |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.9%    |
| Samsung MZVLB512HBJQ-000L2 512GB     | 2         | 0.9%    |
| Samsung MZVL2512HCJQ-00BL2 512GB     | 2         | 0.9%    |
| Plextor PX-128M7VC 128GB SSD         | 2         | 0.9%    |
| KIOXIA NVMe SSD Drive 512GB          | 2         | 0.9%    |
| JMicron Generic 240GB SSD            | 2         | 0.9%    |
| Intel NVMe SSD Drive 512GB           | 2         | 0.9%    |
| Fujitsu F300 480GB                   | 2         | 0.9%    |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.9%    |
| BIWIN SSD 512GB                      | 2         | 0.9%    |
| Apple SSD TS128E 121GB               | 2         | 0.9%    |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.45%   |
| WDC WDS200T3X0C-00SJG0 2TB           | 1         | 0.45%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.45%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.45%   |
| WDC WD7500BPVT-24HXZT1 752GB         | 1         | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.45%   |
| WDC WD5000BPVT-75HXZT1 500GB         | 1         | 0.45%   |
| WDC WD5000BEVT-16A0RT0 500GB         | 1         | 0.45%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.45%   |
| WDC WD10SPCX-16HWST0 1TB             | 1         | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.45%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.45%   |

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
| Samsung Electronics | 13        | 16     | 22.41%  |
| Intel               | 5         | 7      | 8.62%   |
| Crucial             | 5         | 9      | 8.62%   |
| WDC                 | 4         | 4      | 6.9%    |
| Kingston            | 3         | 3      | 5.17%   |
| China               | 3         | 4      | 5.17%   |
| SanDisk             | 2         | 2      | 3.45%   |
| Plextor             | 2         | 3      | 3.45%   |
| JMicron Technology  | 2         | 2      | 3.45%   |
| Fujitsu             | 2         | 4      | 3.45%   |
| Apple               | 2         | 2      | 3.45%   |
| Verbatim            | 1         | 2      | 1.72%   |
| Unknown (CF)        | 1         | 1      | 1.72%   |
| Transcend           | 1         | 1      | 1.72%   |
| TO Exter            | 1         | 1      | 1.72%   |
| Team                | 1         | 1      | 1.72%   |
| SK hynix            | 1         | 1      | 1.72%   |
| RECADATA            | 1         | 1      | 1.72%   |
| Ramsta              | 1         | 1      | 1.72%   |
| Micron Technology   | 1         | 2      | 1.72%   |
| Lexar               | 1         | 1      | 1.72%   |
| HS-SSD-C100         | 1         | 1      | 1.72%   |
| Hikvision           | 1         | 1      | 1.72%   |
| DGM                 | 1         | 1      | 1.72%   |
| Apacer              | 1         | 4      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 83        | 106    | 41.71%  |
| SSD     | 50        | 76     | 25.13%  |
| HDD     | 43        | 46     | 21.61%  |
| MMC     | 15        | 19     | 7.54%   |
| Unknown | 8         | 10     | 4.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 120    | 43.81%  |
| NVMe | 83        | 105    | 42.78%  |
| MMC  | 15        | 19     | 7.73%   |
| SAS  | 11        | 13     | 5.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 84     | 62.11%  |
| 0.51-1.0   | 28        | 29     | 29.47%  |
| 1.01-2.0   | 8         | 9      | 8.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 26.63%  |
| 251-500        | 36        | 21.3%   |
| 1-20           | 22        | 13.02%  |
| 501-1000       | 21        | 12.43%  |
| 1001-2000      | 17        | 10.06%  |
| 51-100         | 15        | 8.88%   |
| 21-50          | 5         | 2.96%   |
| 2001-3000      | 5         | 2.96%   |
| More than 3000 | 2         | 1.18%   |
| Unknown        | 1         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 79        | 45.4%   |
| 51-100    | 24        | 13.79%  |
| 21-50     | 21        | 12.07%  |
| 251-500   | 19        | 10.92%  |
| 101-250   | 19        | 10.92%  |
| 501-1000  | 6         | 3.45%   |
| 1001-2000 | 5         | 2.87%   |
| Unknown   | 1         | 0.57%   |

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
| HGST TOURO Mobile 500GB             | 1         | 1      | 10%     |
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
| Detected | 82        | 131    | 47.95%  |
| Works    | 79        | 116    | 46.2%   |
| Malfunc  | 10        | 10     | 5.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 108       | 51.92%  |
| Samsung Electronics          | 30        | 14.42%  |
| SanDisk                      | 22        | 10.58%  |
| AMD                          | 11        | 5.29%   |
| SK hynix                     | 10        | 4.81%   |
| Toshiba America Info Systems | 4         | 1.92%   |
| Phison Electronics           | 4         | 1.92%   |
| Micron Technology            | 4         | 1.92%   |
| Kingston Technology Company  | 4         | 1.92%   |
| Silicon Motion               | 3         | 1.44%   |
| KIOXIA                       | 2         | 0.96%   |
| Apple                        | 2         | 0.96%   |
| VIA Technologies             | 1         | 0.48%   |
| Nvidia                       | 1         | 0.48%   |
| Lenovo                       | 1         | 0.48%   |
| Biwin Storage Technology     | 1         | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 7.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 5.02%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 5.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 4.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 4.11%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 2.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 2.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 2.28%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 5         | 2.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 2.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.28%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.83%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.83%   |
| Micron Non-Volatile memory controller                                          | 4         | 1.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.83%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.37%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 1.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.37%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.37%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.37%   |
| Intel SSD 660P Series                                                          | 3         | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.37%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.91%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.91%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.91%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.91%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.91%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.91%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 0.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.91%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.91%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 89        | 43.63%  |
| NVMe | 84        | 41.18%  |
| IDE  | 17        | 8.33%   |
| RAID | 14        | 6.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 134       | 83.23%  |
| AMD          | 25        | 15.53%  |
| GenuineTMx86 | 1         | 0.62%   |
| Unknown      | 1         | 0.62%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 4.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 3.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.48%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 2.48%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 1.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.86%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 1.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.86%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.24%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.24%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.24%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.24%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.24%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.24%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.24%   |
| Intel Celeron (Mendocino)                     | 2         | 1.24%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 2         | 1.24%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 1.24%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.24%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.24%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.24%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.24%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.24%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.62%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.62%   |
| Intel Pentium M processor 1.00GHz             | 1         | 0.62%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.62%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.62%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.62%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.62%   |
| Intel Genuine processor 800MHz                | 1         | 0.62%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.62%   |
| Intel Core m3-7Y32 CPU @ 1.10GHz              | 1         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 24.22%  |
| Intel Core i7           | 38        | 23.6%   |
| Other                   | 16        | 9.94%   |
| Intel Celeron           | 13        | 8.07%   |
| AMD Ryzen 7             | 12        | 7.45%   |
| Intel Core i3           | 9         | 5.59%   |
| AMD Ryzen 5             | 7         | 4.35%   |
| Intel Atom              | 5         | 3.11%   |
| Intel Core 2 Duo        | 4         | 2.48%   |
| AMD Ryzen 9             | 4         | 2.48%   |
| Intel Core m3           | 3         | 1.86%   |
| Intel Xeon              | 2         | 1.24%   |
| Intel Pentium Dual-Core | 2         | 1.24%   |
| AMD Ryzen 7 PRO         | 2         | 1.24%   |
| Intel Pentium M         | 1         | 0.62%   |
| Intel Pentium Gold      | 1         | 0.62%   |
| Intel Pentium Dual      | 1         | 0.62%   |
| Intel Genuine           | 1         | 0.62%   |
| Intel Core 2            | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 37.89%  |
| 4      | 52        | 32.3%   |
| 8      | 20        | 12.42%  |
| 6      | 14        | 8.7%    |
| 1      | 9         | 5.59%   |
| 14     | 3         | 1.86%   |
| 12     | 2         | 1.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 161       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 130       | 80.25%  |
| 1      | 32        | 19.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 146       | 90.68%  |
| 32-bit         | 9         | 5.59%   |
| Unknown        | 5         | 3.11%   |
| 64-bit         | 1         | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 19.02%  |
| 0x806ea    | 10        | 6.13%   |
| 0x806e9    | 10        | 6.13%   |
| 0x206a7    | 10        | 6.13%   |
| 0x906ea    | 9         | 5.52%   |
| 0x806c1    | 6         | 3.68%   |
| 0x506c9    | 5         | 3.07%   |
| 0x306a9    | 5         | 3.07%   |
| 0x806ec    | 4         | 2.45%   |
| 0x806eb    | 4         | 2.45%   |
| 0x406e3    | 4         | 2.45%   |
| 0x40651    | 4         | 2.45%   |
| 0x106c2    | 4         | 2.45%   |
| 0x08600106 | 4         | 2.45%   |
| 0xa0652    | 3         | 1.84%   |
| 0x906a3    | 3         | 1.84%   |
| 0x706e5    | 3         | 1.84%   |
| 0x20655    | 3         | 1.84%   |
| 0x1067a    | 3         | 1.84%   |
| 0x0a50000c | 3         | 1.84%   |
| 0x08600104 | 3         | 1.84%   |
| 0x08108102 | 3         | 1.84%   |
| 0x906e9    | 2         | 1.23%   |
| 0x806d1    | 2         | 1.23%   |
| 0x706a8    | 2         | 1.23%   |
| 0x6fd      | 2         | 1.23%   |
| 0x66a      | 2         | 1.23%   |
| 0x506e3    | 2         | 1.23%   |
| 0x306d4    | 2         | 1.23%   |
| 0x306c3    | 2         | 1.23%   |
| 0x0a50000b | 2         | 1.23%   |
| 0x08600103 | 2         | 1.23%   |
| 0x706a1    | 1         | 0.61%   |
| 0x6fb      | 1         | 0.61%   |
| 0x6f6      | 1         | 0.61%   |
| 0x6d8      | 1         | 0.61%   |
| 0x6d6      | 1         | 0.61%   |
| 0x406c3    | 1         | 0.61%   |
| 0x30678    | 1         | 0.61%   |
| 0x20652    | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 26.09%  |
| SandyBridge      | 13        | 8.07%   |
| Zen 2            | 12        | 7.45%   |
| TigerLake        | 9         | 5.59%   |
| IvyBridge        | 8         | 4.97%   |
| Haswell          | 8         | 4.97%   |
| Unknown          | 8         | 4.97%   |
| Zen 3            | 7         | 4.35%   |
| Skylake          | 7         | 4.35%   |
| IceLake          | 6         | 3.73%   |
| Goldmont         | 5         | 3.11%   |
| Zen+             | 4         | 2.48%   |
| Westmere         | 4         | 2.48%   |
| Penryn           | 4         | 2.48%   |
| Core             | 4         | 2.48%   |
| CometLake        | 4         | 2.48%   |
| Bonnell          | 4         | 2.48%   |
| Goldmont plus    | 3         | 1.86%   |
| Broadwell        | 3         | 1.86%   |
| Silvermont       | 2         | 1.24%   |
| P6               | 2         | 1.24%   |
| Alderlake Hybrid | 2         | 1.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 125       | 59.81%  |
| Nvidia      | 50        | 23.92%  |
| AMD         | 31        | 14.83%  |
| Neomagic    | 2         | 0.96%   |
| S3 Graphics | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 6.05%   |
| Intel UHD Graphics 620                                                        | 10        | 4.65%   |
| AMD Renoir                                                                    | 10        | 4.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 4.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 7         | 3.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 3.26%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 3.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 2.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 2.33%   |
| Intel HD Graphics 620                                                         | 5         | 2.33%   |
| Intel HD Graphics 500                                                         | 5         | 2.33%   |
| Nvidia GP108M [GeForce MX150]                                                 | 4         | 1.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 4         | 1.86%   |
| Intel HD Graphics 615                                                         | 4         | 1.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 1.86%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 4         | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.86%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 3         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 1.4%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 1.4%    |
| Intel HD Graphics 5500                                                        | 3         | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.4%    |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 2         | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 2         | 0.93%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 0.93%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 0.93%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.93%   |
| Intel HD Graphics 530                                                         | 2         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 0.93%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 0.93%   |
| AMD Rembrandt [Radeon 680M]                                                   | 2         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 85        | 52.8%   |
| Intel + Nvidia  | 34        | 21.12%  |
| 1 x AMD         | 17        | 10.56%  |
| AMD + Nvidia    | 8         | 4.97%   |
| 1 x Nvidia      | 7         | 4.35%   |
| Intel + AMD     | 6         | 3.73%   |
| 1 x Neomagic    | 2         | 1.24%   |
| Other           | 1         | 0.62%   |
| 1 x S3 Graphics | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 128       | 79.5%   |
| Proprietary | 26        | 16.15%  |
| Unknown     | 7         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 67.9%   |
| 1.01-2.0   | 15        | 9.26%   |
| 0.01-0.5   | 15        | 9.26%   |
| 3.01-4.0   | 7         | 4.32%   |
| 0.51-1.0   | 6         | 3.7%    |
| 5.01-6.0   | 5         | 3.09%   |
| 7.01-8.0   | 4         | 2.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 33        | 19.53%  |
| AU Optronics            | 30        | 17.75%  |
| LG Display              | 23        | 13.61%  |
| Chimei Innolux          | 17        | 10.06%  |
| Sharp                   | 9         | 5.33%   |
| Samsung Electronics     | 9         | 5.33%   |
| Dell                    | 7         | 4.14%   |
| Apple                   | 5         | 2.96%   |
| AOC                     | 4         | 2.37%   |
| Philips                 | 3         | 1.78%   |
| LG Philips              | 2         | 1.18%   |
| Lenovo                  | 2         | 1.18%   |
| InfoVision              | 2         | 1.18%   |
| CPT                     | 2         | 1.18%   |
| Chi Mei Optoelectronics | 2         | 1.18%   |
| Unknown (DAE)           | 1         | 0.59%   |
| TUO                     | 1         | 0.59%   |
| TMX                     | 1         | 0.59%   |
| Sony                    | 1         | 0.59%   |
| RGT                     | 1         | 0.59%   |
| PANDA                   | 1         | 0.59%   |
| MStar                   | 1         | 0.59%   |
| Mi                      | 1         | 0.59%   |
| Lenovo Group Limited    | 1         | 0.59%   |
| JXC                     | 1         | 0.59%   |
| JDI                     | 1         | 0.59%   |
| ITE                     | 1         | 0.59%   |
| IPS                     | 1         | 0.59%   |
| InnoLux Display         | 1         | 0.59%   |
| Hewlett-Packard         | 1         | 0.59%   |
| Goldstar                | 1         | 0.59%   |
| CSO                     | 1         | 0.59%   |
| Ancor Communications    | 1         | 0.59%   |
| Acer                    | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 1.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.76%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 1.76%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 1.18%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 1.18%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 1.18%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.18%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 1.18%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch        | 2         | 1.18%   |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.59%   |
| TUO 240RS TUO2400 1920x1080 408x255mm 18.9-inch                       | 1         | 0.59%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.59%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                         | 1         | 0.59%   |
| Sharp LQ133M1JW48 SHP14F5 1920x1080 294x165mm 13.3-inch               | 1         | 0.59%   |
| Sharp LQ133M1JW35 SHP14B0 1920x1080 294x165mm 13.3-inch               | 1         | 0.59%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.59%   |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch               | 1         | 0.59%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch               | 1         | 0.59%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.59%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                 | 1         | 0.59%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 1         | 0.59%   |
| Philips PHL 272P7VU PHL093A 3840x2160 597x336mm 27.0-inch             | 1         | 0.59%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 1         | 0.59%   |
| Mi Monitor XMI23C2 1920x1080 530x290mm 23.8-inch                      | 1         | 0.59%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.59%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD06A5 1920x1080 344x194mm 15.5-inch          | 1         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 81        | 51.27%  |
| 1366x768 (WXGA)   | 22        | 13.92%  |
| 3840x2160 (4K)    | 9         | 5.7%    |
| 2560x1440 (QHD)   | 6         | 3.8%    |
| 1600x900 (HD+)    | 6         | 3.8%    |
| 1280x800 (WXGA)   | 5         | 3.16%   |
| 2560x1600         | 4         | 2.53%   |
| 2880x1800         | 3         | 1.9%    |
| 1440x900 (WXGA+)  | 3         | 1.9%    |
| 3840x2400         | 2         | 1.27%   |
| 3440x1440         | 2         | 1.27%   |
| 3840x1600         | 1         | 0.63%   |
| 3520x1080         | 1         | 0.63%   |
| 3456x2160         | 1         | 0.63%   |
| 3200x2000         | 1         | 0.63%   |
| 3200x1800 (QHD+)  | 1         | 0.63%   |
| 2880x1920         | 1         | 0.63%   |
| 2400x1600         | 1         | 0.63%   |
| 2304x1440         | 1         | 0.63%   |
| 2256x1504         | 1         | 0.63%   |
| 2240x1400         | 1         | 0.63%   |
| 2160x1440         | 1         | 0.63%   |
| 1920x1200 (WUXGA) | 1         | 0.63%   |
| 1024x600          | 1         | 0.63%   |
| 1024x576          | 1         | 0.63%   |
| Unknown           | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 52        | 30.95%  |
| 13      | 34        | 20.24%  |
| 14      | 29        | 17.26%  |
| 12      | 10        | 5.95%   |
| 21      | 6         | 3.57%   |
| 17      | 5         | 2.98%   |
| 24      | 4         | 2.38%   |
| 23      | 4         | 2.38%   |
| 31      | 3         | 1.79%   |
| 27      | 3         | 1.79%   |
| 10      | 3         | 1.79%   |
| Unknown | 3         | 1.79%   |
| 34      | 2         | 1.19%   |
| 19      | 2         | 1.19%   |
| 72      | 1         | 0.6%    |
| 52      | 1         | 0.6%    |
| 40      | 1         | 0.6%    |
| 37      | 1         | 0.6%    |
| 18      | 1         | 0.6%    |
| 16      | 1         | 0.6%    |
| 11      | 1         | 0.6%    |
| 8       | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 94        | 56.29%  |
| 201-300     | 35        | 20.96%  |
| 501-600     | 11        | 6.59%   |
| 401-500     | 8         | 4.79%   |
| 351-400     | 6         | 3.59%   |
| 601-700     | 3         | 1.8%    |
| Unknown     | 3         | 1.8%    |
| 801-900     | 2         | 1.2%    |
| 701-800     | 2         | 1.2%    |
| 1501-2000   | 1         | 0.6%    |
| 101-200     | 1         | 0.6%    |
| 1001-1500   | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 122       | 80.26%  |
| 16/10   | 21        | 13.82%  |
| 3/2     | 4         | 2.63%   |
| 21/9    | 3         | 1.97%   |
| 0.62    | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 30.77%  |
| 81-90          | 47        | 27.81%  |
| 71-80          | 17        | 10.06%  |
| 201-250        | 12        | 7.1%    |
| 61-70          | 9         | 5.33%   |
| 351-500        | 6         | 3.55%   |
| 121-130        | 5         | 2.96%   |
| 151-200        | 4         | 2.37%   |
| 41-50          | 3         | 1.78%   |
| 301-350        | 3         | 1.78%   |
| Unknown        | 3         | 1.78%   |
| More than 1000 | 2         | 1.18%   |
| 51-60          | 1         | 0.59%   |
| 1-40           | 1         | 0.59%   |
| 251-300        | 1         | 0.59%   |
| 111-120        | 1         | 0.59%   |
| 501-1000       | 1         | 0.59%   |
| 91-100         | 1         | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 76        | 46.34%  |
| 101-120       | 30        | 18.29%  |
| 161-240       | 23        | 14.02%  |
| 51-100        | 15        | 9.15%   |
| More than 240 | 14        | 8.54%   |
| 1-50          | 3         | 1.83%   |
| Unknown       | 3         | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 130       | 79.27%  |
| 2     | 25        | 15.24%  |
| 0     | 8         | 4.88%   |
| 3     | 1         | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 97        | 40.08%  |
| Realtek Semiconductor    | 69        | 28.51%  |
| Qualcomm Atheros         | 28        | 11.57%  |
| Broadcom                 | 13        | 5.37%   |
| MediaTek                 | 7         | 2.89%   |
| Ralink Technology        | 4         | 1.65%   |
| ASIX Electronics         | 4         | 1.65%   |
| Qualcomm                 | 3         | 1.24%   |
| Marvell Technology Group | 3         | 1.24%   |
| Broadcom Limited         | 3         | 1.24%   |
| Xiaomi                   | 1         | 0.41%   |
| Texas Instruments        | 1         | 0.41%   |
| SEGGER                   | 1         | 0.41%   |
| Ralink                   | 1         | 0.41%   |
| OPPO Electronics         | 1         | 0.41%   |
| NetGear                  | 1         | 0.41%   |
| Lenovo                   | 1         | 0.41%   |
| Huawei Technologies      | 1         | 0.41%   |
| Fitbit                   | 1         | 0.41%   |
| DisplayLink              | 1         | 0.41%   |
| Apple                    | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 38        | 12.97%  |
| Intel Wi-Fi 6 AX200                                                     | 15        | 5.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 3.41%   |
| Intel Wireless 8265 / 8275                                              | 10        | 3.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 3.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.73%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 2.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 2.05%   |
| Realtek 802.11n WLAN Adapter                                            | 5         | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.71%   |
| Intel Wireless 8260                                                     | 5         | 1.71%   |
| Intel Wireless 7265                                                     | 5         | 1.71%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.37%   |
| Intel Wireless 7260                                                     | 4         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.37%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.02%   |
| Intel 82579V Gigabit Network Connection                                 | 3         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.68%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 92        | 55.42%  |
| Qualcomm Atheros      | 25        | 15.06%  |
| Realtek Semiconductor | 19        | 11.45%  |
| Broadcom              | 12        | 7.23%   |
| MediaTek              | 7         | 4.22%   |
| Ralink Technology     | 4         | 2.41%   |
| Qualcomm              | 3         | 1.81%   |
| Texas Instruments     | 1         | 0.6%    |
| Ralink                | 1         | 0.6%    |
| NetGear               | 1         | 0.6%    |
| Broadcom Limited      | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 15        | 8.98%   |
| Intel Wireless 8265 / 8275                                              | 10        | 5.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 4.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.59%   |
| Realtek 802.11n WLAN Adapter                                            | 5         | 2.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.99%   |
| Intel Wireless 8260                                                     | 5         | 2.99%   |
| Intel Wireless 7265                                                     | 5         | 2.99%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.4%    |
| Intel Wireless 7260                                                     | 4         | 2.4%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 2.4%    |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.8%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.2%    |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.2%    |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.2%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 2         | 1.2%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.2%    |
| Texas Instruments ACX 100 22Mbps Wireless Interface                     | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 0.6%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)               | 1         | 0.6%    |
| Realtek Realtek Network controller                                      | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 59        | 48.36%  |
| Intel                    | 40        | 32.79%  |
| Qualcomm Atheros         | 6         | 4.92%   |
| ASIX Electronics         | 4         | 3.28%   |
| Marvell Technology Group | 3         | 2.46%   |
| Broadcom Limited         | 2         | 1.64%   |
| Broadcom                 | 2         | 1.64%   |
| Xiaomi                   | 1         | 0.82%   |
| OPPO Electronics         | 1         | 0.82%   |
| Lenovo                   | 1         | 0.82%   |
| Huawei Technologies      | 1         | 0.82%   |
| DisplayLink              | 1         | 0.82%   |
| Apple                    | 1         | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 30.89%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 8.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 7.32%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 5.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.44%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.63%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.81%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.81%   |
| OPPO RMX3263                                                      | 1         | 0.81%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.81%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.81%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.81%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.81%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.81%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.81%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 57.4%   |
| Ethernet | 115       | 41.52%  |
| Modem    | 2         | 0.72%   |
| Unknown  | 1         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 139       | 81.29%  |
| Ethernet | 32        | 18.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 99        | 61.49%  |
| 1     | 55        | 34.16%  |
| 0     | 7         | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 161       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 59.35%  |
| Foxconn / Hon Hai               | 8         | 6.5%    |
| Qualcomm Atheros Communications | 7         | 5.69%   |
| Broadcom                        | 6         | 4.88%   |
| Realtek Semiconductor           | 4         | 3.25%   |
| Lite-On Technology              | 4         | 3.25%   |
| IMC Networks                    | 4         | 3.25%   |
| Realtek                         | 3         | 2.44%   |
| Hewlett-Packard                 | 3         | 2.44%   |
| Apple                           | 3         | 2.44%   |
| Foxconn International           | 2         | 1.63%   |
| Dell                            | 2         | 1.63%   |
| Taiyo Yuden                     | 1         | 0.81%   |
| Fujitsu                         | 1         | 0.81%   |
| Cambridge Silicon Radio         | 1         | 0.81%   |
| Askey Computer                  | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 17.89%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 12.2%   |
| Intel AX200 Bluetooth                               | 15        | 12.2%   |
| Intel AX201 Bluetooth                               | 14        | 11.38%  |
| Realtek Bluetooth Radio                             | 4         | 3.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.25%   |
| Realtek Bluetooth Radio                             | 3         | 2.44%   |
| Intel Bluetooth Device                              | 3         | 2.44%   |
| IMC Networks Wireless_Device                        | 3         | 2.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2.44%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 2.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 2.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.63%   |
| Intel AX210 Bluetooth                               | 2         | 1.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.63%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.81%   |
| Lite-On Bluetooth Radio                             | 1         | 0.81%   |
| Lite-On Bluetooth Device                            | 1         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.81%   |
| IMC Networks Bluetooth Device                       | 1         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.81%   |
| Fujitsu Bluetooth Device                            | 1         | 0.81%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.81%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.81%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.81%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.81%   |
| Broadcom BCM2045A0                                  | 1         | 0.81%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.81%   |
| Askey Bluetooth Device                              | 1         | 0.81%   |
| Apple Bluetooth Host Controller                     | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 129       | 67.89%  |
| AMD                         | 26        | 13.68%  |
| Nvidia                      | 25        | 13.16%  |
| Generalplus Technology      | 2         | 1.05%   |
| ESS Technology              | 2         | 1.05%   |
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
| Intel Sunrise Point-LP HD Audio                                            | 25        | 11.36%  |
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 10.91%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 5.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 5.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 4.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 4.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 3.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.82%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.82%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.36%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.91%   |
| Nvidia Audio device                                                        | 2         | 0.91%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.91%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.91%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 0.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 0.91%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 36        | 30.77%  |
| Samsung Electronics | 34        | 29.06%  |
| Unknown             | 12        | 10.26%  |
| Micron Technology   | 12        | 10.26%  |
| Kingston            | 6         | 5.13%   |
| Unknown             | 6         | 5.13%   |
| Crucial             | 3         | 2.56%   |
| Unknown (ABCD)      | 2         | 1.71%   |
| Team                | 1         | 0.85%   |
| Nanya Technology    | 1         | 0.85%   |
| Lenovo              | 1         | 0.85%   |
| Kingmax             | 1         | 0.85%   |
| Elpida              | 1         | 0.85%   |
| A-DATA Technology   | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 6         | 4.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 3.28%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 4         | 3.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                             | 2         | 1.64%   |
| Unknown RAM Module 256MB SODIMM DRAM                          | 2         | 1.64%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s  | 2         | 1.64%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                  | 2         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 1.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 1.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 2         | 1.64%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 2         | 1.64%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 2         | 1.64%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s        | 2         | 1.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 1.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 1.64%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 2         | 1.64%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 2         | 1.64%   |
| Unknown RAM Module 512MB SODIMM DRAM                          | 1         | 0.82%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                    | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR                             | 1         | 0.82%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.82%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                    | 1         | 0.82%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                 | 1         | 0.82%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s          | 1         | 0.82%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.82%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                    | 1         | 0.82%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 0.82%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.82%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s | 1         | 0.82%   |
| SK hynix RAM HMAA4GS7AJR8N-WM 32GB SODIMM DDR4 2933MT/s       | 1         | 0.82%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s  | 1         | 0.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 1         | 0.82%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16384MB SODIMM DDR4 2400MT/s    | 1         | 0.82%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 0.82%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 1         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 45        | 45.92%  |
| DDR3    | 17        | 17.35%  |
| LPDDR3  | 11        | 11.22%  |
| LPDDR4  | 8         | 8.16%   |
| DDR2    | 7         | 7.14%   |
| DRAM    | 3         | 3.06%   |
| SDRAM   | 2         | 2.04%   |
| Unknown | 2         | 2.04%   |
| LPDDR5  | 1         | 1.02%   |
| DDR5    | 1         | 1.02%   |
| DDR     | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 73.2%   |
| Row Of Chips | 20        | 20.62%  |
| DIMM         | 5         | 5.15%   |
| Unknown      | 1         | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 40        | 36.7%   |
| 4096  | 24        | 22.02%  |
| 16384 | 13        | 11.93%  |
| 2048  | 13        | 11.93%  |
| 32768 | 8         | 7.34%   |
| 1024  | 5         | 4.59%   |
| 256   | 2         | 1.83%   |
| 64    | 2         | 1.83%   |
| 512   | 1         | 0.92%   |
| 232   | 1         | 0.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 22        | 21.15%  |
| 3200    | 17        | 16.35%  |
| 1600    | 15        | 14.42%  |
| 2133    | 9         | 8.65%   |
| 2400    | 6         | 5.77%   |
| Unknown | 6         | 5.77%   |
| 1867    | 5         | 4.81%   |
| 4267    | 4         | 3.85%   |
| 667     | 3         | 2.88%   |
| 3266    | 2         | 1.92%   |
| 1334    | 2         | 1.92%   |
| 533     | 2         | 1.92%   |
| 8400    | 1         | 0.96%   |
| 6400    | 1         | 0.96%   |
| 4800    | 1         | 0.96%   |
| 4266    | 1         | 0.96%   |
| 3733    | 1         | 0.96%   |
| 2933    | 1         | 0.96%   |
| 1067    | 1         | 0.96%   |
| 1066    | 1         | 0.96%   |
| 975     | 1         | 0.96%   |
| 333     | 1         | 0.96%   |
| 200     | 1         | 0.96%   |

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
| Chicony Electronics                    | 30        | 22.56%  |
| IMC Networks                           | 15        | 11.28%  |
| Microdia                               | 11        | 8.27%   |
| Acer                                   | 11        | 8.27%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 6.02%   |
| Realtek Semiconductor                  | 7         | 5.26%   |
| Luxvisions Innotech Limited            | 6         | 4.51%   |
| Apple                                  | 6         | 4.51%   |
| Sunplus Innovation Technology          | 5         | 3.76%   |
| Syntek                                 | 4         | 3.01%   |
| Suyin                                  | 3         | 2.26%   |
| Silicon Motion                         | 3         | 2.26%   |
| Quanta                                 | 3         | 2.26%   |
| Alcor Micro                            | 3         | 2.26%   |
| Lite-On Technology                     | 2         | 1.5%    |
| Importek                               | 2         | 1.5%    |
| Xiaomi                                 | 1         | 0.75%   |
| WaveRider Communications               | 1         | 0.75%   |
| USB Camera                             | 1         | 0.75%   |
| Tripath Technology                     | 1         | 0.75%   |
| Sonix Technology                       | 1         | 0.75%   |
| Ricoh                                  | 1         | 0.75%   |
| Primax Electronics                     | 1         | 0.75%   |
| Nebraska Furniture Mart                | 1         | 0.75%   |
| Microsoft                              | 1         | 0.75%   |
| Logitech                               | 1         | 0.75%   |
| lihappe8                               | 1         | 0.75%   |
| Genesys Logic                          | 1         | 0.75%   |
| eMPIA Technology                       | 1         | 0.75%   |
| DLTCT0A9IH1FFL                         | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 9         | 6.67%   |
| Chicony Integrated Camera                                       | 9         | 6.67%   |
| IMC Networks Integrated Camera                                  | 7         | 5.19%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 3.7%    |
| Chicony FJ Camera                                               | 5         | 3.7%    |
| Syntek Integrated Camera                                        | 4         | 2.96%   |
| Chicony HD Webcam                                               | 4         | 2.96%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 2.22%   |
| Apple FaceTime HD Camera (Built-in)                             | 3         | 2.22%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 2.22%   |
| Acer Integrated Camera                                          | 3         | 2.22%   |
| Sunplus HD WebCam                                               | 2         | 1.48%   |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 1.48%   |
| Luxvisions Innotech Limited HP HD Camera                        | 2         | 1.48%   |
| Lite-On Integrated Camera                                       | 2         | 1.48%   |
| Importek FJ Camera                                              | 2         | 1.48%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.48%   |
| Apple iPhone5/5C/5S/6                                           | 2         | 1.48%   |
| Acer SunplusIT Integrated Camera                                | 2         | 1.48%   |
| Acer Lenovo EasyCamera                                          | 2         | 1.48%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                              | 1         | 0.74%   |
| WaveRider USB 2.0 Camera                                        | 1         | 0.74%   |
| USB Camera USB Camera                                           | 1         | 0.74%   |
| Tripath PC Camera                                               | 1         | 0.74%   |
| Suyin Integrated Webcam                                         | 1         | 0.74%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 1         | 0.74%   |
| Suyin HP Truevision HD                                          | 1         | 0.74%   |
| Sunplus ZCF-171115                                              | 1         | 0.74%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 0.74%   |
| Sunplus HP Universal Camera                                     | 1         | 0.74%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 0.74%   |
| Silicon Motion Lenovo EasyCamera                                | 1         | 0.74%   |
| Silicon Motion 720p HD Camera                                   | 1         | 0.74%   |
| Silicon Motion 300k Pixel Camera                                | 1         | 0.74%   |
| Ricoh USB2.0 Camera                                             | 1         | 0.74%   |
| Realtek WebCamera                                               | 1         | 0.74%   |
| Realtek USB2.0 HD UVC WebCam                                    | 1         | 0.74%   |
| Realtek Integrated Webcam_HD                                    | 1         | 0.74%   |
| Realtek EasyCamera                                              | 1         | 0.74%   |
| Quanta USB Webcam                                               | 1         | 0.74%   |

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
| 0     | 94        | 56.97%  |
| 1     | 52        | 31.52%  |
| 2     | 13        | 7.88%   |
| 3     | 4         | 2.42%   |
| 5     | 1         | 0.61%   |
| 4     | 1         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 31.96%  |
| Graphics card            | 25        | 25.77%  |
| Chipcard                 | 13        | 13.4%   |
| Multimedia controller    | 9         | 9.28%   |
| Net/wireless             | 8         | 8.25%   |
| Communication controller | 3         | 3.09%   |
| Bluetooth                | 3         | 3.09%   |
| Storage                  | 1         | 1.03%   |
| Sound                    | 1         | 1.03%   |
| Net/ethernet             | 1         | 1.03%   |
| Card reader              | 1         | 1.03%   |
| Camera                   | 1         | 1.03%   |

