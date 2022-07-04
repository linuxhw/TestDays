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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Dell          | XPS 15 9520                 | [eee1a317b6](https://linux-hardware.org/?probe=eee1a317b6) | May 30, 2022 |
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
| Ubuntu 20.04                 | 26        | 20%     |
| Ubuntu 18.04                 | 9         | 6.92%   |
| Arch                         | 6         | 4.62%   |
| Fedora 32                    | 5         | 3.85%   |
| Ubuntu 19.10                 | 4         | 3.08%   |
| Gentoo 2.7                   | 4         | 3.08%   |
| OpenMandriva 4.2             | 3         | 2.31%   |
| Linux Mint 20                | 3         | 2.31%   |
| Fedora 33                    | 3         | 2.31%   |
| Chrome OS                    | 3         | 2.31%   |
| Arch Rolling                 | 3         | 2.31%   |
| antiX 21                     | 3         | 2.31%   |
| Ubuntu 22.04                 | 2         | 1.54%   |
| Ubuntu 21.04                 | 2         | 1.54%   |
| Ubuntu 19.04                 | 2         | 1.54%   |
| Ubuntu 16.04                 | 2         | 1.54%   |
| Pop!_OS 22.04                | 2         | 1.54%   |
| Pop!_OS 20.10                | 2         | 1.54%   |
| Pop!_OS 20.04                | 2         | 1.54%   |
| Manjaro 20.1                 | 2         | 1.54%   |
| Linux Mint 20.3              | 2         | 1.54%   |
| KDE neon 20.04               | 2         | 1.54%   |
| Fedora 36                    | 2         | 1.54%   |
| Fedora 34                    | 2         | 1.54%   |
| EndeavourOS Rolling          | 2         | 1.54%   |
| ArcoLinux Rolling            | 2         | 1.54%   |
| Zorin 15                     | 1         | 0.77%   |
| UbuntuDDE 21.10              | 1         | 0.77%   |
| Ubuntu Budgie 20.04          | 1         | 0.77%   |
| Ubuntu 21.10                 | 1         | 0.77%   |
| Ubuntu 20.10                 | 1         | 0.77%   |
| ROSA R11                     | 1         | 0.77%   |
| ROSA R10                     | 1         | 0.77%   |
| Pop!_OS 21.10                | 1         | 0.77%   |
| Pop!_OS 21.04                | 1         | 0.77%   |
| PCLinuxOS 2020               | 1         | 0.77%   |
| Oracle Linux 8.6             | 1         | 0.77%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.77%   |
| OpenMandriva 4.50            | 1         | 0.77%   |
| Manjaro 21.1.0               | 1         | 0.77%   |
| Manjaro 21.0                 | 1         | 0.77%   |
| Manjaro 20.2.1               | 1         | 0.77%   |
| Linux Mint 20.1              | 1         | 0.77%   |
| Linux Mint 19.1              | 1         | 0.77%   |
| Kubuntu 21.10                | 1         | 0.77%   |
| Kali 2021.4                  | 1         | 0.77%   |
| Gentoo 2.8                   | 1         | 0.77%   |
| Fedora 35                    | 1         | 0.77%   |
| Fedora 30                    | 1         | 0.77%   |
| Elementary 5.1.7             | 1         | 0.77%   |
| Elementary 5.1.5             | 1         | 0.77%   |
| Debian 11                    | 1         | 0.77%   |
| Clear Linux 34930            | 1         | 0.77%   |
| Clear Linux 34290            | 1         | 0.77%   |
| Clear Linux 34180            | 1         | 0.77%   |
| BlackPanther 16.2            | 1         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 48        | 38.1%   |
| Fedora        | 14        | 11.11%  |
| Arch          | 9         | 7.14%   |
| Pop!_OS       | 8         | 6.35%   |
| Linux Mint    | 6         | 4.76%   |
| Manjaro       | 5         | 3.97%   |
| OpenMandriva  | 4         | 3.17%   |
| Gentoo        | 4         | 3.17%   |
| Clear Linux   | 3         | 2.38%   |
| Chrome OS     | 3         | 2.38%   |
| antiX         | 3         | 2.38%   |
| ROSA          | 2         | 1.59%   |
| KDE neon      | 2         | 1.59%   |
| EndeavourOS   | 2         | 1.59%   |
| ArcoLinux     | 2         | 1.59%   |
| Zorin         | 1         | 0.79%   |
| UbuntuDDE     | 1         | 0.79%   |
| Ubuntu Budgie | 1         | 0.79%   |
| PCLinuxOS     | 1         | 0.79%   |
| Oracle Linux  | 1         | 0.79%   |
| openSUSE      | 1         | 0.79%   |
| Kubuntu       | 1         | 0.79%   |
| Kali          | 1         | 0.79%   |
| Elementary    | 1         | 0.79%   |
| Debian        | 1         | 0.79%   |
| BlackPanther  | 1         | 0.79%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 6         | 4.29%   |
| 5.8.0-43-generic                | 3         | 2.14%   |
| 5.4.0-48-generic                | 3         | 2.14%   |
| 5.13.0-39-generic               | 3         | 2.14%   |
| 5.10.14-desktop-1omv4002        | 3         | 2.14%   |
| 4.9.0-279-antix.1-486-smp       | 3         | 2.14%   |
| 4.19.49+                        | 3         | 2.14%   |
| 5.9.2-arch1-1                   | 2         | 1.43%   |
| 5.8.0-7630-generic              | 2         | 1.43%   |
| 5.4.0-58-generic                | 2         | 1.43%   |
| 5.4.0-28-generic                | 2         | 1.43%   |
| 5.4.0-26-generic                | 2         | 1.43%   |
| 5.3.0-18-generic                | 2         | 1.43%   |
| 5.17.11-300.fc36.x86_64         | 2         | 1.43%   |
| 5.13.0-35-generic               | 2         | 1.43%   |
| 5.11.0-37-generic               | 2         | 1.43%   |
| 5.0.0-31-generic                | 2         | 1.43%   |
| 4.18.0-15-generic               | 2         | 1.43%   |
| 5.9.8-200.fc33.x86_64           | 1         | 0.71%   |
| 5.9.3-arch1-1                   | 1         | 0.71%   |
| 5.9.14-100.fc32.x86_64          | 1         | 0.71%   |
| 5.9.10-artix1-1                 | 1         | 0.71%   |
| 5.8.6-1-MANJARO                 | 1         | 0.71%   |
| 5.8.3-2-MANJARO                 | 1         | 0.71%   |
| 5.8.15-gentoo                   | 1         | 0.71%   |
| 5.8.0-64-generic                | 1         | 0.71%   |
| 5.8.0-63-generic                | 1         | 0.71%   |
| 5.8.0-55-generic                | 1         | 0.71%   |
| 5.8.0-54-generic                | 1         | 0.71%   |
| 5.8.0-33-generic                | 1         | 0.71%   |
| 5.8.0-25-generic                | 1         | 0.71%   |
| 5.7.9-200.fc32.x86_64           | 1         | 0.71%   |
| 5.7.4-gentoo                    | 1         | 0.71%   |
| 5.7.11-200.fc32.x86_64          | 1         | 0.71%   |
| 5.7.10-201.fc32.x86_64          | 1         | 0.71%   |
| 5.6.3-zen1-1-zen                | 1         | 0.71%   |
| 5.4.17-2136.300.7.el8uek.x86_64 | 1         | 0.71%   |
| 5.4.0-7634-generic              | 1         | 0.71%   |
| 5.4.0-67-generic                | 1         | 0.71%   |
| 5.4.0-65-generic                | 1         | 0.71%   |
| 5.4.0-53-generic                | 1         | 0.71%   |
| 5.4.0-52-generic                | 1         | 0.71%   |
| 5.4.0-45-generic                | 1         | 0.71%   |
| 5.4.0-37-generic                | 1         | 0.71%   |
| 5.4.0-33-generic                | 1         | 0.71%   |
| 5.4.0-117-generic               | 1         | 0.71%   |
| 5.4.0-1007-fips                 | 1         | 0.71%   |
| 5.3.5-200.fc30.x86_64           | 1         | 0.71%   |
| 5.3.14-lqx1-1-lqx               | 1         | 0.71%   |
| 5.3.11-zen1-1-zen               | 1         | 0.71%   |
| 5.3.0-59-generic                | 1         | 0.71%   |
| 5.3.0-46-generic                | 1         | 0.71%   |
| 5.3.0-24-generic                | 1         | 0.71%   |
| 5.17.9-arch1-1                  | 1         | 0.71%   |
| 5.17.5-76051705-generic         | 1         | 0.71%   |
| 5.17.4-100.fc34.x86_64          | 1         | 0.71%   |
| 5.17.4-1-default                | 1         | 0.71%   |
| 5.17.3-arch1-1                  | 1         | 0.71%   |
| 5.17.1-arch1-1.1                | 1         | 0.71%   |
| 5.16.19-76051619-generic        | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 15.15%  |
| 5.13.0  | 10        | 7.58%   |
| 5.8.0   | 9         | 6.82%   |
| 4.15.0  | 7         | 5.3%    |
| 5.11.0  | 6         | 4.55%   |
| 5.3.0   | 5         | 3.79%   |
| 5.0.0   | 5         | 3.79%   |
| 5.10.14 | 3         | 2.27%   |
| 4.9.0   | 3         | 2.27%   |
| 4.19.49 | 3         | 2.27%   |
| 5.9.2   | 2         | 1.52%   |
| 5.17.4  | 2         | 1.52%   |
| 5.17.11 | 2         | 1.52%   |
| 5.15.0  | 2         | 1.52%   |
| 4.18.0  | 2         | 1.52%   |
| 5.9.8   | 1         | 0.76%   |
| 5.9.3   | 1         | 0.76%   |
| 5.9.14  | 1         | 0.76%   |
| 5.9.10  | 1         | 0.76%   |
| 5.8.6   | 1         | 0.76%   |
| 5.8.3   | 1         | 0.76%   |
| 5.8.15  | 1         | 0.76%   |
| 5.7.9   | 1         | 0.76%   |
| 5.7.4   | 1         | 0.76%   |
| 5.7.11  | 1         | 0.76%   |
| 5.7.10  | 1         | 0.76%   |
| 5.6.3   | 1         | 0.76%   |
| 5.4.17  | 1         | 0.76%   |
| 5.3.5   | 1         | 0.76%   |
| 5.3.14  | 1         | 0.76%   |
| 5.3.11  | 1         | 0.76%   |
| 5.17.9  | 1         | 0.76%   |
| 5.17.5  | 1         | 0.76%   |
| 5.17.3  | 1         | 0.76%   |
| 5.17.1  | 1         | 0.76%   |
| 5.16.19 | 1         | 0.76%   |
| 5.16.12 | 1         | 0.76%   |
| 5.16.11 | 1         | 0.76%   |
| 5.15.48 | 1         | 0.76%   |
| 5.15.15 | 1         | 0.76%   |
| 5.15.13 | 1         | 0.76%   |
| 5.14.8  | 1         | 0.76%   |
| 5.14.7  | 1         | 0.76%   |
| 5.14.15 | 1         | 0.76%   |
| 5.14.0  | 1         | 0.76%   |
| 5.13.8  | 1         | 0.76%   |
| 5.13.13 | 1         | 0.76%   |
| 5.12.9  | 1         | 0.76%   |
| 5.11.6  | 1         | 0.76%   |
| 5.11.2  | 1         | 0.76%   |
| 5.11.19 | 1         | 0.76%   |
| 5.11.18 | 1         | 0.76%   |
| 5.11.17 | 1         | 0.76%   |
| 5.11.12 | 1         | 0.76%   |
| 5.11.10 | 1         | 0.76%   |
| 5.10.8  | 1         | 0.76%   |
| 5.10.76 | 1         | 0.76%   |
| 5.10.52 | 1         | 0.76%   |
| 5.10.21 | 1         | 0.76%   |
| 5.10.2  | 1         | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 15.38%  |
| 5.8     | 12        | 9.23%   |
| 5.13    | 12        | 9.23%   |
| 5.11    | 12        | 9.23%   |
| 5.10    | 11        | 8.46%   |
| 5.3     | 8         | 6.15%   |
| 5.17    | 8         | 6.15%   |
| 4.15    | 7         | 5.38%   |
| 5.9     | 6         | 4.62%   |
| 5.15    | 5         | 3.85%   |
| 5.0     | 5         | 3.85%   |
| 4.9     | 5         | 3.85%   |
| 5.7     | 4         | 3.08%   |
| 5.14    | 4         | 3.08%   |
| 5.16    | 3         | 2.31%   |
| 4.19    | 3         | 2.31%   |
| 4.18    | 3         | 2.31%   |
| 5.6     | 1         | 0.77%   |
| 5.12    | 1         | 0.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 117       | 94.35%  |
| i686   | 6         | 4.84%   |
| i586   | 1         | 0.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 65        | 51.18%  |
| Unknown    | 23        | 18.11%  |
| KDE5       | 19        | 14.96%  |
| XFCE       | 4         | 3.15%   |
| X-Cinnamon | 4         | 3.15%   |
| KDE        | 3         | 2.36%   |
| i3         | 3         | 2.36%   |
| Unity      | 1         | 0.79%   |
| LXQt       | 1         | 0.79%   |
| fvwm       | 1         | 0.79%   |
| Deepin     | 1         | 0.79%   |
| Cinnamon   | 1         | 0.79%   |
| Budgie     | 1         | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 101       | 80.8%   |
| Wayland | 15        | 12%     |
| Unknown | 8         | 6.4%    |
| Tty     | 1         | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 51.59%  |
| GDM     | 22        | 17.46%  |
| SDDM    | 20        | 15.87%  |
| LightDM | 8         | 6.35%   |
| GDM3    | 7         | 5.56%   |
| TDM     | 4         | 3.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 50        | 39.06%  |
| en_HK   | 23        | 17.97%  |
| Unknown | 19        | 14.84%  |
| zh_CN   | 14        | 10.94%  |
| zh_HK   | 7         | 5.47%   |
| zh_TW   | 5         | 3.91%   |
| C       | 4         | 3.13%   |
| en_GB   | 3         | 2.34%   |
| it_IT   | 1         | 0.78%   |
| en_ZA   | 1         | 0.78%   |
| en_AU   | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 85        | 68%     |
| BIOS | 40        | 32%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 93        | 73.81%  |
| Btrfs   | 13        | 10.32%  |
| Unknown | 7         | 5.56%   |
| Overlay | 6         | 4.76%   |
| Xfs     | 3         | 2.38%   |
| Zfs     | 2         | 1.59%   |
| Ext3    | 1         | 0.79%   |
| Ext2    | 1         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 51.18%  |
| GPT     | 54        | 42.52%  |
| MBR     | 8         | 6.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 92%     |
| Yes       | 10        | 8%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 59.2%   |
| Yes       | 51        | 40.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 39        | 31.45%  |
| Dell                 | 17        | 13.71%  |
| Hewlett-Packard      | 12        | 9.68%   |
| ASUSTek Computer     | 12        | 9.68%   |
| Fujitsu              | 10        | 8.06%   |
| Unknown              | 8         | 6.45%   |
| Acer                 | 4         | 3.23%   |
| HUAWEI               | 3         | 2.42%   |
| Apple                | 3         | 2.42%   |
| Toshiba              | 2         | 1.61%   |
| Samsung Electronics  | 2         | 1.61%   |
| GPD                  | 2         | 1.61%   |
| Timi                 | 1         | 0.81%   |
| Sony                 | 1         | 0.81%   |
| Schenker             | 1         | 0.81%   |
| Panasonic            | 1         | 0.81%   |
| MSI                  | 1         | 0.81%   |
| KOHJINSHA            | 1         | 0.81%   |
| Jumper               | 1         | 0.81%   |
| Intel Client Systems | 1         | 0.81%   |
| Google               | 1         | 0.81%   |
| Compaq               | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 6.45%   |
| Lenovo Legion R7000 2020 82B6            | 2         | 1.61%   |
| HUAWEI KPRC-WX0                          | 2         | 1.61%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC         | 2         | 1.61%   |
| HP EliteBook 2540p                       | 2         | 1.61%   |
| Fujitsu UH-X                             | 2         | 1.61%   |
| Fujitsu LIFEBOOK AH544                   | 2         | 1.61%   |
| Dell XPS 13 9310                         | 2         | 1.61%   |
| Dell Inspiron 5580                       | 2         | 1.61%   |
| ASUS TUF Gaming FA506IU_FA506IU          | 2         | 1.61%   |
| Toshiba PORTEGE R830                     | 1         | 0.81%   |
| Toshiba dynabook R731/E                  | 1         | 0.81%   |
| Timi TM1607                              | 1         | 0.81%   |
| Sony VPCCB17FG                           | 1         | 0.81%   |
| Schenker XMG_APEX15_XAP15E20             | 1         | 0.81%   |
| Samsung SQ1S                             | 1         | 0.81%   |
| Samsung 930XBE                           | 1         | 0.81%   |
| Panasonic CFSZ5-2L                       | 1         | 0.81%   |
| MSI GS73VR 7RG                           | 1         | 0.81%   |
| Lenovo ZHAOYANG K47                      | 1         | 0.81%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.81%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN        | 1         | 0.81%   |
| Lenovo XiaoXin-14API QC 2019 81UW        | 1         | 0.81%   |
| Lenovo XiaoXin Chao7000-14IKBR 81GA      | 1         | 0.81%   |
| Lenovo ThinkPad X270 20HNA00RAD          | 1         | 0.81%   |
| Lenovo ThinkPad X250 20CLA1VECD          | 1         | 0.81%   |
| Lenovo ThinkPad X220 4290NL5             | 1         | 0.81%   |
| Lenovo ThinkPad X1 Extreme 20MFS0PE00    | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1001BHH | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR003HHH | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBA05VCD | 1         | 0.81%   |
| Lenovo ThinkPad W530 24384KU             | 1         | 0.81%   |
| Lenovo ThinkPad T61 6465CTO              | 1         | 0.81%   |
| Lenovo ThinkPad T520 4242BC5             | 1         | 0.81%   |
| Lenovo ThinkPad T480s 20L7CTO1WW         | 1         | 0.81%   |
| Lenovo ThinkPad T480s 20L7005FUS         | 1         | 0.81%   |
| Lenovo ThinkPad T430s 2355C33            | 1         | 0.81%   |
| Lenovo ThinkPad T430 2342AG4             | 1         | 0.81%   |
| Lenovo ThinkPad T400 64751W1             | 1         | 0.81%   |
| Lenovo ThinkPad S3 Yoga 14 20DM000VUS    | 1         | 0.81%   |
| Lenovo ThinkPad P15v Gen 1 20TQS08G00    | 1         | 0.81%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 0.81%   |
| Lenovo ThinkPad E14 20RAA002CD           | 1         | 0.81%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0         | 1         | 0.81%   |
| Lenovo Legion Y9000P2021H 82JD           | 1         | 0.81%   |
| Lenovo Legion Y7000P2020H 82AX           | 1         | 0.81%   |
| Lenovo Legion 5 15ACH6 82JW              | 1         | 0.81%   |
| Lenovo IdeaPad Yoga 13 20175             | 1         | 0.81%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 1         | 0.81%   |
| Lenovo IdeaPad 5 14IIL05 81YH            | 1         | 0.81%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 0.81%   |
| Lenovo IdeaPad 320-15IKB 80XL            | 1         | 0.81%   |
| Lenovo G770 20089                        | 1         | 0.81%   |
| Lenovo G710 20252                        | 1         | 0.81%   |
| Lenovo E10-30 20424                      | 1         | 0.81%   |
| Lenovo 3000 G410                         | 1         | 0.81%   |
| KOHJINSHA SX series                      | 1         | 0.81%   |
| Jumper EZbook                            | 1         | 0.81%   |
| Intel Client Systems LAPKC71F            | 1         | 0.81%   |
| HUAWEI WRT-WX9                           | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 19        | 15.32%  |
| Unknown                       | 8         | 6.45%   |
| Fujitsu LIFEBOOK              | 7         | 5.65%   |
| Dell XPS                      | 6         | 4.84%   |
| Lenovo Legion                 | 5         | 4.03%   |
| Lenovo IdeaPad                | 5         | 4.03%   |
| Dell Inspiron                 | 5         | 4.03%   |
| HP EliteBook                  | 3         | 2.42%   |
| Dell Precision                | 3         | 2.42%   |
| ASUS TUF                      | 3         | 2.42%   |
| Acer Aspire                   | 3         | 2.42%   |
| HUAWEI KPRC-WX0               | 2         | 1.61%   |
| HP ZHAN                       | 2         | 1.61%   |
| Fujitsu UH-X                  | 2         | 1.61%   |
| Dell Latitude                 | 2         | 1.61%   |
| ASUS ROG                      | 2         | 1.61%   |
| Toshiba PORTEGE               | 1         | 0.81%   |
| Toshiba dynabook              | 1         | 0.81%   |
| Timi TM1607                   | 1         | 0.81%   |
| Sony VPCCB17FG                | 1         | 0.81%   |
| Schenker XMG                  | 1         | 0.81%   |
| Samsung SQ1S                  | 1         | 0.81%   |
| Samsung 930XBE                | 1         | 0.81%   |
| Panasonic CFSZ5-2L            | 1         | 0.81%   |
| MSI GS73VR                    | 1         | 0.81%   |
| Lenovo ZHAOYANG               | 1         | 0.81%   |
| Lenovo Yoga                   | 1         | 0.81%   |
| Lenovo XiaoXinAir-14ARE       | 1         | 0.81%   |
| Lenovo XiaoXin-14API          | 1         | 0.81%   |
| Lenovo XiaoXin                | 1         | 0.81%   |
| Lenovo ThinkBook              | 1         | 0.81%   |
| Lenovo G770                   | 1         | 0.81%   |
| Lenovo G710                   | 1         | 0.81%   |
| Lenovo E10-30                 | 1         | 0.81%   |
| Lenovo 3000                   | 1         | 0.81%   |
| KOHJINSHA SX                  | 1         | 0.81%   |
| Jumper EZbook                 | 1         | 0.81%   |
| Intel Client Systems LAPKC71F | 1         | 0.81%   |
| HUAWEI WRT-WX9                | 1         | 0.81%   |
| HP Victus                     | 1         | 0.81%   |
| HP ProBook                    | 1         | 0.81%   |
| HP Notebook                   | 1         | 0.81%   |
| HP Laptop                     | 1         | 0.81%   |
| HP G72                        | 1         | 0.81%   |
| HP 2140                       | 1         | 0.81%   |
| HP 2000                       | 1         | 0.81%   |
| GPD P2                        | 1         | 0.81%   |
| GPD G1618-03                  | 1         | 0.81%   |
| Google Eve                    | 1         | 0.81%   |
| Fujitsu S6420                 | 1         | 0.81%   |
| Dell G7                       | 1         | 0.81%   |
| Compaq Tablet                 | 1         | 0.81%   |
| ASUS Zephyrus                 | 1         | 0.81%   |
| ASUS Zenbook                  | 1         | 0.81%   |
| ASUS X556URK                  | 1         | 0.81%   |
| ASUS UX302LA                  | 1         | 0.81%   |
| ASUS N501VW                   | 1         | 0.81%   |
| ASUS K501UX                   | 1         | 0.81%   |
| ASUS ASUS                     | 1         | 0.81%   |
| Apple MacBookPro7             | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 20        | 16.13%  |
| 2018 | 18        | 14.52%  |
| 2021 | 15        | 12.1%   |
| 2019 | 13        | 10.48%  |
| 2011 | 9         | 7.26%   |
| 2017 | 8         | 6.45%   |
| 2012 | 7         | 5.65%   |
| 2014 | 6         | 4.84%   |
| 2010 | 6         | 4.84%   |
| 2015 | 5         | 4.03%   |
| 2008 | 4         | 3.23%   |
| 2022 | 3         | 2.42%   |
| 2016 | 3         | 2.42%   |
| 2013 | 3         | 2.42%   |
| 2007 | 2         | 1.61%   |
| 2009 | 1         | 0.81%   |
| 2003 | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 124       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 106       | 85.48%  |
| Enabled  | 18        | 14.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 123       | 99.19%  |
| Yes  | 1         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 24.19%  |
| 8.01-16.0   | 27        | 21.77%  |
| 16.01-24.0  | 25        | 20.16%  |
| 3.01-4.0    | 14        | 11.29%  |
| 32.01-64.0  | 13        | 10.48%  |
| 2.01-3.0    | 4         | 3.23%   |
| 64.01-256.0 | 4         | 3.23%   |
| 1.01-2.0    | 3         | 2.42%   |
| 24.01-32.0  | 2         | 1.61%   |
| 0.51-1.0    | 2         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 36        | 27.91%  |
| 2.01-3.0   | 29        | 22.48%  |
| 4.01-8.0   | 24        | 18.6%   |
| 3.01-4.0   | 19        | 14.73%  |
| 8.01-16.0  | 8         | 6.2%    |
| 0.01-0.5   | 7         | 5.43%   |
| 16.01-24.0 | 3         | 2.33%   |
| 0.51-1.0   | 3         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 60.47%  |
| 2      | 43        | 33.33%  |
| 3      | 5         | 3.88%   |
| 0      | 2         | 1.55%   |
| 5      | 1         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 76.38%  |
| Yes       | 30        | 23.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 70.97%  |
| No        | 36        | 29.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 99.19%  |
| No        | 1         | 0.81%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 78.4%   |
| No        | 27        | 21.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Hong Kong | 124       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Central       | 70        | 53.85%  |
| Shatin        | 6         | 4.62%   |
| Tung Chung    | 5         | 3.85%   |
| Kowloon       | 5         | 3.85%   |
| Hung Hom      | 4         | 3.08%   |
| Hong Kong     | 4         | 3.08%   |
| Wanchai       | 3         | 2.31%   |
| Tseung Kwan O | 3         | 2.31%   |
| Tai Po        | 3         | 2.31%   |
| Yuen Long     | 2         | 1.54%   |
| Tuen Mun      | 2         | 1.54%   |
| Ngau Wu Tok   | 2         | 1.54%   |
| Man Kok       | 2         | 1.54%   |
| Discovery Bay | 2         | 1.54%   |
| Yau Tsim Mong | 1         | 0.77%   |
| Wong Tai Sin  | 1         | 0.77%   |
| Tsuen Wan     | 1         | 0.77%   |
| To Kwa Wan    | 1         | 0.77%   |
| Tin Shui Wai  | 1         | 0.77%   |
| Tai Wan To    | 1         | 0.77%   |
| Tai Wan       | 1         | 0.77%   |
| Shau Kei Wan  | 1         | 0.77%   |
| Sai Kung      | 1         | 0.77%   |
| Quarry Bay    | 1         | 0.77%   |
| North Point   | 1         | 0.77%   |
| North         | 1         | 0.77%   |
| Mong Kok      | 1         | 0.77%   |
| Lam Tin       | 1         | 0.77%   |
| Kwun Hang     | 1         | 0.77%   |
| Fanling       | 1         | 0.77%   |
| Causeway Bay  | 1         | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 40     | 19.64%  |
| WDC                 | 19        | 20     | 11.31%  |
| Unknown             | 12        | 16     | 7.14%   |
| SanDisk             | 10        | 11     | 5.95%   |
| Intel               | 10        | 12     | 5.95%   |
| Seagate             | 9         | 10     | 5.36%   |
| SK hynix            | 7         | 7      | 4.17%   |
| Hitachi             | 7         | 7      | 4.17%   |
| Kingston            | 6         | 7      | 3.57%   |
| HGST                | 5         | 6      | 2.98%   |
| Toshiba             | 4         | 4      | 2.38%   |
| Micron Technology   | 4         | 5      | 2.38%   |
| Crucial             | 4         | 7      | 2.38%   |
| Phison              | 3         | 3      | 1.79%   |
| KIOXIA              | 3         | 3      | 1.79%   |
| JMicron Technology  | 3         | 4      | 1.79%   |
| Fujitsu             | 3         | 4      | 1.79%   |
| China               | 3         | 4      | 1.79%   |
| Plextor             | 2         | 2      | 1.19%   |
| KingSpec            | 2         | 3      | 1.19%   |
| Apple               | 2         | 3      | 1.19%   |
| Verbatim            | 1         | 2      | 0.6%    |
| TO Exter            | 1         | 1      | 0.6%    |
| Team                | 1         | 1      | 0.6%    |
| ShineDisk           | 1         | 1      | 0.6%    |
| RECADATA            | 1         | 1      | 0.6%    |
| Ramsta              | 1         | 1      | 0.6%    |
| PH4-CE12            | 1         | 1      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| HS-SSD-C100         | 1         | 2      | 0.6%    |
| Hikvision           | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| GALAX TA            | 1         | 1      | 0.6%    |
| Faspeed             | 1         | 1      | 0.6%    |
| BIWIN               | 1         | 1      | 0.6%    |
| Apacer              | 1         | 4      | 0.6%    |
| A-DATA Technology   | 1         | 1      | 0.6%    |
| Unknown             | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                  | 3         | 1.71%   |
| SanDisk NVMe SSD Drive 512GB            | 3         | 1.71%   |
| WDC WD10SPZX-22Z10T1 1TB                | 2         | 1.14%   |
| Unknown MMC Card  128GB                 | 2         | 1.14%   |
| Toshiba MQ01ABF050 500GB                | 2         | 1.14%   |
| SK hynix BC501 NVMe 128GB               | 2         | 1.14%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 1.14%   |
| SanDisk NVMe SSD Drive 256GB            | 2         | 1.14%   |
| Samsung SSD 970 EVO Plus 2TB            | 2         | 1.14%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 1.14%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.14%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 1.14%   |
| Samsung MZVL2512HCJQ-00BL2 512GB        | 2         | 1.14%   |
| Plextor PX-128M7VC 128GB SSD            | 2         | 1.14%   |
| KIOXIA NVMe SSD Drive 512GB             | 2         | 1.14%   |
| JMicron Generic 2TB                     | 2         | 1.14%   |
| Intel NVMe SSD Drive 512GB              | 2         | 1.14%   |
| Fujitsu F300 480GB                      | 2         | 1.14%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 1.14%   |
| WDC WDS500G2B0A 500GB SSD               | 1         | 0.57%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.57%   |
| WDC WDS200T3X0C-00SJG0 2TB              | 1         | 0.57%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.57%   |
| WDC WDS100T2G0A-00JH30 1TB SSD          | 1         | 0.57%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.57%   |
| WDC WD7500BPVT-24HXZT1 752GB            | 1         | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.57%   |
| WDC WD5000BEVT-16A0RT0 500GB            | 1         | 0.57%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.57%   |
| WDC WD10SPCX-16HWST0 1TB                | 1         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.57%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 0.57%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 1         | 0.57%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB    | 1         | 0.57%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 1         | 0.57%   |
| Verbatim Vi550 S3 SSD 128GB             | 1         | 0.57%   |
| Unknown SMI  121MB                      | 1         | 0.57%   |
| Unknown SD32G  32GB                     | 1         | 0.57%   |
| Unknown NVMe SSD Drive 1024GB           | 1         | 0.57%   |
| Unknown MMC Card  7GB                   | 1         | 0.57%   |
| Unknown MMC Card  32GB                  | 1         | 0.57%   |
| Unknown MMC Card  16GB                  | 1         | 0.57%   |
| Unknown DURM4R  128GB                   | 1         | 0.57%   |
| Unknown 064GE2  64GB                    | 1         | 0.57%   |
| Unknown 00000  129GB                    | 1         | 0.57%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.57%   |
| Toshiba KBG20ZMS512G NVMe 512GB         | 1         | 0.57%   |
| TO Exter nal USB 3.0 256GB              | 1         | 0.57%   |
| Team TEAML5Lite3D120G 120GB SSD         | 1         | 0.57%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 0.57%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 1         | 0.57%   |
| SK hynix NVMe SSD Drive 2TB             | 1         | 0.57%   |
| SK hynix NVMe SSD Drive 1TB             | 1         | 0.57%   |
| SK hynix BC501 NVMe 256GB               | 1         | 0.57%   |
| ShineDisk M667 240G                     | 1         | 0.57%   |
| Seagate ST9250315ASG 250GB              | 1         | 0.57%   |
| Seagate ST9160412AS 160GB               | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 10        | 10     | 27.78%  |
| Seagate            | 9         | 10     | 25%     |
| Hitachi            | 7         | 7      | 19.44%  |
| HGST               | 5         | 6      | 13.89%  |
| JMicron Technology | 3         | 4      | 8.33%   |
| Toshiba            | 2         | 2      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 28.26%  |
| WDC                 | 4         | 4      | 8.7%    |
| Intel               | 4         | 6      | 8.7%    |
| Crucial             | 4         | 7      | 8.7%    |
| China               | 3         | 4      | 6.52%   |
| Plextor             | 2         | 2      | 4.35%   |
| Kingston            | 2         | 2      | 4.35%   |
| Fujitsu             | 2         | 3      | 4.35%   |
| Verbatim            | 1         | 2      | 2.17%   |
| TO Exter            | 1         | 1      | 2.17%   |
| Team                | 1         | 1      | 2.17%   |
| SanDisk             | 1         | 1      | 2.17%   |
| RECADATA            | 1         | 1      | 2.17%   |
| Ramsta              | 1         | 1      | 2.17%   |
| Micron Technology   | 1         | 2      | 2.17%   |
| Lexar               | 1         | 1      | 2.17%   |
| Hikvision           | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |
| Apacer              | 1         | 4      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 60        | 73     | 37.97%  |
| SSD     | 42        | 61     | 26.58%  |
| HDD     | 35        | 39     | 22.15%  |
| MMC     | 13        | 17     | 8.23%   |
| Unknown | 8         | 10     | 5.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 99     | 45.7%   |
| NVMe | 60        | 73     | 39.74%  |
| MMC  | 13        | 17     | 8.61%   |
| SAS  | 9         | 11     | 5.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 68     | 60.26%  |
| 0.51-1.0   | 21        | 21     | 26.92%  |
| 1.01-2.0   | 9         | 10     | 11.54%  |
| 10.01-20.0 | 1         | 1      | 1.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 27.13%  |
| 251-500        | 27        | 20.93%  |
| 501-1000       | 18        | 13.95%  |
| 1001-2000      | 16        | 12.4%   |
| 1-20           | 11        | 8.53%   |
| 51-100         | 11        | 8.53%   |
| 21-50          | 4         | 3.1%    |
| 2001-3000      | 4         | 3.1%    |
| More than 3000 | 2         | 1.55%   |
| Unknown        | 1         | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 58        | 43.28%  |
| 21-50     | 20        | 14.93%  |
| 51-100    | 19        | 14.18%  |
| 251-500   | 14        | 10.45%  |
| 101-250   | 11        | 8.21%   |
| 501-1000  | 6         | 4.48%   |
| 1001-2000 | 5         | 3.73%   |
| Unknown   | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 860 EVO 1TB | 1         | 1      | 14.29%  |
| Hitachi HTS725050A7E630 500GB       | 1         | 1      | 14.29%  |
| Hitachi HTS723216L9A360 160GB       | 1         | 1      | 14.29%  |
| Hitachi HTC426040G8CE00 40GB        | 1         | 1      | 14.29%  |
| HGST TOURO Mobile 1TB               | 1         | 1      | 14.29%  |
| Crucial CT240M500SSD1 240GB         | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 3         | 3      | 42.86%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 75%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 57.14%  |
| SSD  | 3         | 3      | 42.86%  |

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
| Detected | 73        | 116    | 55.3%   |
| Works    | 52        | 77     | 39.39%  |
| Malfunc  | 7         | 7      | 5.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 88        | 54.66%  |
| Samsung Electronics          | 23        | 14.29%  |
| SanDisk                      | 14        | 8.7%    |
| AMD                          | 8         | 4.97%   |
| SK hynix                     | 7         | 4.35%   |
| Kingston Technology Company  | 4         | 2.48%   |
| Toshiba America Info Systems | 3         | 1.86%   |
| Phison Electronics           | 3         | 1.86%   |
| Micron Technology            | 3         | 1.86%   |
| Silicon Motion               | 2         | 1.24%   |
| KIOXIA                       | 2         | 1.24%   |
| VIA Technologies             | 1         | 0.62%   |
| Nvidia                       | 1         | 0.62%   |
| Biwin Storage Technology     | 1         | 0.62%   |
| Apple                        | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 12        | 7.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 10        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 10        | 5.88%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 8         | 4.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 4.71%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 8         | 4.71%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 5         | 2.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 2.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 2.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 2.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 2.35%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 1.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 1.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 1.76%   |
| Micron Non-Volatile memory controller                                                  | 3         | 1.76%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 3         | 1.76%   |
| Intel SSD 660P Series                                                                  | 3         | 1.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 1.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.18%   |
| SK hynix Non-Volatile memory controller                                                | 2         | 1.18%   |
| SK hynix Gold P31 SSD                                                                  | 2         | 1.18%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 1.18%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.18%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                                | 2         | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 1.18%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 1.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.18%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.59%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.59%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 0.59%   |
| Phison NVMe Storage Controller                                                         | 1         | 0.59%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.59%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.59%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.59%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.59%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 0.59%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.59%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.59%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 0.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 1         | 0.59%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                             | 1         | 0.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 76        | 48.1%   |
| NVMe | 62        | 39.24%  |
| RAID | 10        | 6.33%   |
| IDE  | 10        | 6.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 107       | 86.29%  |
| AMD          | 16        | 12.9%   |
| GenuineTMx86 | 1         | 0.81%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 3.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 3.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 3.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 3.23%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 3.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 3.23%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 2.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.42%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 2.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.61%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.61%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.61%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.81%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.81%   |
| Intel Pentium M processor 1.00GHz             | 1         | 0.81%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.81%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.81%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.81%   |
| Intel Core m3-7Y32 CPU @ 1.10GHz              | 1         | 0.81%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.81%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 1         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.81%   |
| Intel Core i7-6560U CPU @ 2.20GHz             | 1         | 0.81%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.81%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 0.81%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.81%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.81%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.81%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.81%   |
| Intel Core i7 CPU L 640 @ 2.13GHz             | 1         | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.81%   |
| Intel Core i5-7Y57 CPU @ 1.20GHz              | 1         | 0.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.81%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 0.81%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.81%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.81%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 0.81%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.81%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 0.81%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 0.81%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 0.81%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 0.81%   |
| Intel Core i3-5020U CPU @ 2.20GHz             | 1         | 0.81%   |
| Intel Core i3-4100M CPU @ 2.50GHz             | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 26.61%  |
| Intel Core i7           | 29        | 23.39%  |
| Other                   | 14        | 11.29%  |
| Intel Celeron           | 10        | 8.06%   |
| AMD Ryzen 7             | 8         | 6.45%   |
| Intel Core i3           | 7         | 5.65%   |
| AMD Ryzen 9             | 4         | 3.23%   |
| AMD Ryzen 5             | 4         | 3.23%   |
| Intel Core m3           | 3         | 2.42%   |
| Intel Core 2 Duo        | 3         | 2.42%   |
| Intel Xeon              | 2         | 1.61%   |
| Intel Pentium Dual-Core | 2         | 1.61%   |
| Intel Atom              | 2         | 1.61%   |
| Intel Pentium M         | 1         | 0.81%   |
| Intel Pentium Gold      | 1         | 0.81%   |
| Intel Pentium Dual      | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 54        | 43.55%  |
| 4      | 40        | 32.26%  |
| 8      | 13        | 10.48%  |
| 6      | 9         | 7.26%   |
| 1      | 4         | 3.23%   |
| 14     | 3         | 2.42%   |
| 12     | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 124       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 102       | 81.6%   |
| 1      | 23        | 18.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 115       | 92.74%  |
| Unknown        | 5         | 4.03%   |
| 32-bit         | 4         | 3.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 20.63%  |
| 0x806e9    | 9         | 7.14%   |
| 0x206a7    | 9         | 7.14%   |
| 0x806ea    | 6         | 4.76%   |
| 0x806c1    | 6         | 4.76%   |
| 0x506c9    | 5         | 3.97%   |
| 0x906ea    | 4         | 3.17%   |
| 0x406e3    | 4         | 3.17%   |
| 0x40651    | 4         | 3.17%   |
| 0x306a9    | 4         | 3.17%   |
| 0xa0652    | 3         | 2.38%   |
| 0x806ec    | 3         | 2.38%   |
| 0x806eb    | 3         | 2.38%   |
| 0x706e5    | 3         | 2.38%   |
| 0x20655    | 3         | 2.38%   |
| 0x1067a    | 3         | 2.38%   |
| 0x08108102 | 3         | 2.38%   |
| 0x906e9    | 2         | 1.59%   |
| 0x906a3    | 2         | 1.59%   |
| 0x806d1    | 2         | 1.59%   |
| 0x306c3    | 2         | 1.59%   |
| 0x106c2    | 2         | 1.59%   |
| 0x0a50000c | 2         | 1.59%   |
| 0x0a50000b | 2         | 1.59%   |
| 0x08600104 | 2         | 1.59%   |
| 0x08600103 | 2         | 1.59%   |
| 0x706a8    | 1         | 0.79%   |
| 0x706a1    | 1         | 0.79%   |
| 0x6fd      | 1         | 0.79%   |
| 0x6fb      | 1         | 0.79%   |
| 0x6d6      | 1         | 0.79%   |
| 0x506e3    | 1         | 0.79%   |
| 0x306d4    | 1         | 0.79%   |
| 0x30678    | 1         | 0.79%   |
| 0x20652    | 1         | 0.79%   |
| 0x08701013 | 1         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 23.39%  |
| SandyBridge      | 12        | 9.68%   |
| TigerLake        | 9         | 7.26%   |
| Haswell          | 8         | 6.45%   |
| Zen 2            | 7         | 5.65%   |
| IvyBridge        | 7         | 5.65%   |
| Skylake          | 6         | 4.84%   |
| Icelake          | 6         | 4.84%   |
| Zen 3            | 5         | 4.03%   |
| Goldmont         | 5         | 4.03%   |
| Westmere         | 4         | 3.23%   |
| Penryn           | 4         | 3.23%   |
| CometLake        | 4         | 3.23%   |
| Unknown          | 4         | 3.23%   |
| Zen+             | 3         | 2.42%   |
| Goldmont plus    | 2         | 1.61%   |
| Core             | 2         | 1.61%   |
| Broadwell        | 2         | 1.61%   |
| Bonnell          | 2         | 1.61%   |
| Silvermont       | 1         | 0.81%   |
| P6               | 1         | 0.81%   |
| Alderlake Hybrid | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 101       | 62.35%  |
| Nvidia      | 40        | 24.69%  |
| AMD         | 20        | 12.35%  |
| S3 Graphics | 1         | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 12        | 7.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 4.24%   |
| Intel UHD Graphics 620                                                    | 6         | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 3.03%   |
| Intel HD Graphics 500                                                     | 5         | 3.03%   |
| AMD Renoir                                                                | 5         | 3.03%   |
| AMD Cezanne                                                               | 5         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 2.42%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 2.42%   |
| Intel HD Graphics 620                                                     | 4         | 2.42%   |
| Intel HD Graphics 615                                                     | 4         | 2.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 2.42%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 3         | 1.82%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 3         | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 1.82%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 3         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 1.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.21%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.21%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 1.21%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.21%   |
| Intel HD Graphics 5500                                                    | 2         | 1.21%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.21%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.21%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 2         | 1.21%   |
| S3 Graphics Chrome 430 ULP / 435 ULP / 440 GTX                            | 1         | 0.61%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.61%   |
| Nvidia TU117M                                                             | 1         | 0.61%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.61%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.61%   |
| Nvidia NV11M [GeForce2 Go]                                                | 1         | 0.61%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 0.61%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.61%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.61%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.61%   |
| Nvidia GP107GLM [Quadro P620]                                             | 1         | 0.61%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                   | 1         | 0.61%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                     | 1         | 0.61%   |
| Nvidia GM108M [GeForce 930MX]                                             | 1         | 0.61%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.61%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.61%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.61%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.61%   |
| Nvidia GF119M [GeForce 410M]                                              | 1         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.61%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 0.61%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.61%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                               | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 71        | 57.26%  |
| Intel + Nvidia  | 25        | 20.16%  |
| 1 x AMD         | 8         | 6.45%   |
| 1 x Nvidia      | 7         | 5.65%   |
| AMD + Nvidia    | 7         | 5.65%   |
| Intel + AMD     | 5         | 4.03%   |
| 1 x S3 Graphics | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 100       | 80.65%  |
| Proprietary | 20        | 16.13%  |
| Unknown     | 4         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 84        | 67.2%   |
| 1.01-2.0   | 14        | 11.2%   |
| 0.01-0.5   | 8         | 6.4%    |
| 5.01-6.0   | 5         | 4%      |
| 3.01-4.0   | 5         | 4%      |
| 0.51-1.0   | 5         | 4%      |
| 7.01-8.0   | 4         | 3.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 25        | 18.52%  |
| AU Optronics            | 21        | 15.56%  |
| LG Display              | 20        | 14.81%  |
| Chimei Innolux          | 14        | 10.37%  |
| Samsung Electronics     | 9         | 6.67%   |
| Sharp                   | 8         | 5.93%   |
| Dell                    | 6         | 4.44%   |
| Apple                   | 3         | 2.22%   |
| AOC                     | 3         | 2.22%   |
| Philips                 | 2         | 1.48%   |
| LG Philips              | 2         | 1.48%   |
| Lenovo                  | 2         | 1.48%   |
| Chi Mei Optoelectronics | 2         | 1.48%   |
| Unknown (DAE)           | 1         | 0.74%   |
| TMX                     | 1         | 0.74%   |
| Sony                    | 1         | 0.74%   |
| PANDA                   | 1         | 0.74%   |
| MStar                   | 1         | 0.74%   |
| Mi                      | 1         | 0.74%   |
| Lenovo Group Limited    | 1         | 0.74%   |
| JXC                     | 1         | 0.74%   |
| ITE                     | 1         | 0.74%   |
| IPS                     | 1         | 0.74%   |
| InnoLux Display         | 1         | 0.74%   |
| InfoVision              | 1         | 0.74%   |
| Hewlett-Packard         | 1         | 0.74%   |
| Goldstar                | 1         | 0.74%   |
| CSO                     | 1         | 0.74%   |
| CPT                     | 1         | 0.74%   |
| Ancor Communications    | 1         | 0.74%   |
| Acer                    | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 2.21%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.21%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 1.47%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 1.47%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 1.47%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 1.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.47%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 2         | 1.47%   |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.74%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.74%   |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 0.74%   |
| Sharp LQ133M1JW48 SHP14F5 1920x1080 294x165mm 13.3-inch               | 1         | 0.74%   |
| Sharp LQ133M1JW35 SHP14B0 1920x1080 294x165mm 13.3-inch               | 1         | 0.74%   |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.74%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 1         | 0.74%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 1         | 0.74%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.74%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.74%   |
| Mi Monitor XMI23C2 1920x1080 530x290mm 23.8-inch                      | 1         | 0.74%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.74%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD06A5 1920x1080 344x194mm 15.5-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD0625 1920x1080 340x190mm 15.3-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD04B8 1366x768 344x194mm 15.5-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 1         | 0.74%   |
| Lenovo LEN LS2023wC LEN0EC2 1600x900 440x250mm 19.9-inch              | 1         | 0.74%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 1         | 0.74%   |
| Lenovo Group Limited LCD Monitor                                      | 1         | 0.74%   |
| JXC JXC3221 JXC3200 3840x2160 697x392mm 31.5-inch                     | 1         | 0.74%   |
| ITE RP-WIFI ITE9320 2560x1440 1600x900mm 72.3-inch                    | 1         | 0.74%   |
| IPS SONGREN 240E IPS2380 2560x1440 452x254mm 20.4-inch                | 1         | 0.74%   |
| InnoLux Display LCD Monitor CMI0023 1366x768 309x174mm 14.0-inch      | 1         | 0.74%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 1         | 0.74%   |
| Hewlett-Packard 22w HPN3430 1920x1080 476x268mm 21.5-inch             | 1         | 0.74%   |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch              | 1         | 0.74%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 0.74%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 60        | 47.24%  |
| 1366x768 (WXGA)   | 20        | 15.75%  |
| 3840x2160 (4K)    | 8         | 6.3%    |
| 1600x900 (HD+)    | 6         | 4.72%   |
| 1280x800 (WXGA)   | 5         | 3.94%   |
| 2560x1440 (QHD)   | 4         | 3.15%   |
| 2880x1800         | 3         | 2.36%   |
| 3840x2400         | 2         | 1.57%   |
| 3440x1440         | 2         | 1.57%   |
| 2560x1600         | 2         | 1.57%   |
| 1440x900 (WXGA+)  | 2         | 1.57%   |
| 3840x1600         | 1         | 0.79%   |
| 3520x1080         | 1         | 0.79%   |
| 3456x2160         | 1         | 0.79%   |
| 3200x2000         | 1         | 0.79%   |
| 3200x1800 (QHD+)  | 1         | 0.79%   |
| 2880x1920         | 1         | 0.79%   |
| 2400x1600         | 1         | 0.79%   |
| 2304x1440         | 1         | 0.79%   |
| 2256x1504         | 1         | 0.79%   |
| 2160x1440         | 1         | 0.79%   |
| 1920x1200 (WUXGA) | 1         | 0.79%   |
| 1024x576          | 1         | 0.79%   |
| Unknown           | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 45        | 33.58%  |
| 13      | 25        | 18.66%  |
| 14      | 20        | 14.93%  |
| 12      | 9         | 6.72%   |
| 23      | 4         | 2.99%   |
| 21      | 4         | 2.99%   |
| 17      | 4         | 2.99%   |
| 31      | 3         | 2.24%   |
| 24      | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 34      | 2         | 1.49%   |
| 27      | 2         | 1.49%   |
| 19      | 2         | 1.49%   |
| 10      | 2         | 1.49%   |
| 72      | 1         | 0.75%   |
| 52      | 1         | 0.75%   |
| 37      | 1         | 0.75%   |
| 16      | 1         | 0.75%   |
| 11      | 1         | 0.75%   |
| 8       | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 55.64%  |
| 201-300     | 28        | 21.05%  |
| 501-600     | 9         | 6.77%   |
| 401-500     | 5         | 3.76%   |
| 351-400     | 5         | 3.76%   |
| 601-700     | 3         | 2.26%   |
| Unknown     | 3         | 2.26%   |
| 701-800     | 2         | 1.5%    |
| 801-900     | 1         | 0.75%   |
| 1501-2000   | 1         | 0.75%   |
| 101-200     | 1         | 0.75%   |
| 1001-1500   | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 95        | 78.51%  |
| 16/10   | 17        | 14.05%  |
| 3/2     | 4         | 3.31%   |
| 21/9    | 3         | 2.48%   |
| 0.62    | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 33.33%  |
| 81-90          | 31        | 22.96%  |
| 71-80          | 15        | 11.11%  |
| 201-250        | 10        | 7.41%   |
| 61-70          | 8         | 5.93%   |
| 351-500        | 6         | 4.44%   |
| 121-130        | 4         | 2.96%   |
| Unknown        | 3         | 2.22%   |
| More than 1000 | 2         | 1.48%   |
| 41-50          | 2         | 1.48%   |
| 301-350        | 2         | 1.48%   |
| 151-200        | 2         | 1.48%   |
| 51-60          | 1         | 0.74%   |
| 1-40           | 1         | 0.74%   |
| 251-300        | 1         | 0.74%   |
| 111-120        | 1         | 0.74%   |
| 91-100         | 1         | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 55        | 41.67%  |
| 101-120       | 25        | 18.94%  |
| 161-240       | 18        | 13.64%  |
| More than 240 | 14        | 10.61%  |
| 51-100        | 14        | 10.61%  |
| 1-50          | 3         | 2.27%   |
| Unknown       | 3         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 101       | 80.8%   |
| 2     | 19        | 15.2%   |
| 0     | 4         | 3.2%    |
| 3     | 1         | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 75        | 40.98%  |
| Realtek Semiconductor    | 55        | 30.05%  |
| Qualcomm Atheros         | 20        | 10.93%  |
| Broadcom                 | 9         | 4.92%   |
| MediaTek                 | 5         | 2.73%   |
| Ralink Technology        | 4         | 2.19%   |
| Qualcomm                 | 2         | 1.09%   |
| Marvell Technology Group | 2         | 1.09%   |
| Broadcom Limited         | 2         | 1.09%   |
| ASIX Electronics         | 2         | 1.09%   |
| Xiaomi                   | 1         | 0.55%   |
| SEGGER                   | 1         | 0.55%   |
| Ralink                   | 1         | 0.55%   |
| OPPO Electronics         | 1         | 0.55%   |
| Lenovo                   | 1         | 0.55%   |
| Fitbit                   | 1         | 0.55%   |
| DisplayLink              | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 30        | 13.33%  |
| Intel Wi-Fi 6 AX200                                                                           | 10        | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 8         | 3.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 7         | 3.11%   |
| Intel Wireless 8265 / 8275                                                                    | 7         | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6         | 2.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 5         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 5         | 2.22%   |
| Intel Wireless 7265                                                                           | 5         | 2.22%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 2.22%   |
| Intel Ethernet Connection (4) I219-V                                                          | 5         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 5         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 4         | 1.78%   |
| Intel Wireless 8260                                                                           | 4         | 1.78%   |
| Intel Wireless 7260                                                                           | 4         | 1.78%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4         | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.33%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 3         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 1.33%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 1.33%   |
| Intel 82579V Gigabit Network Connection                                                       | 3         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                                      | 3         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.89%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 2         | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 0.89%   |
| Qualcomm QCA6390 Wireless Network Adapter                                                     | 2         | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 0.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 0.89%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 0.89%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 2         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1         | 0.44%   |
| SEGGER J-Link Pro OB                                                                          | 1         | 0.44%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.44%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                        | 1         | 0.44%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                                     | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.44%   |
| Realtek Realtek Network controller                                                            | 1         | 0.44%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                        | 1         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.44%   |
| OPPO Find X2 Lite                                                                             | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 71        | 55.47%  |
| Realtek Semiconductor | 18        | 14.06%  |
| Qualcomm Atheros      | 18        | 14.06%  |
| Broadcom              | 8         | 6.25%   |
| MediaTek              | 5         | 3.91%   |
| Ralink Technology     | 4         | 3.13%   |
| Qualcomm              | 2         | 1.56%   |
| Ralink                | 1         | 0.78%   |
| Broadcom Limited      | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 10        | 7.75%   |
| Intel Wireless 8265 / 8275                                                                    | 7         | 5.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 5         | 3.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 5         | 3.88%   |
| Intel Wireless 7265                                                                           | 5         | 3.88%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 3.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 5         | 3.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 4         | 3.1%    |
| Intel Wireless 8260                                                                           | 4         | 3.1%    |
| Intel Wireless 7260                                                                           | 4         | 3.1%    |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4         | 3.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 3.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 2.33%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 3         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 2.33%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.55%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 2         | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.55%   |
| Qualcomm QCA6390 Wireless Network Adapter                                                     | 2         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 1.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2         | 1.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 1.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.55%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 2         | 1.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.78%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                        | 1         | 0.78%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                                     | 1         | 0.78%   |
| Realtek Realtek Network controller                                                            | 1         | 0.78%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.78%   |
| MediaTek WLAN controller                                                                      | 1         | 0.78%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.78%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 0.78%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                                     | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 0.78%   |
| Intel Centrino Wireless-N 2200                                                                | 1         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                                 | 1         | 0.78%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                                               | 1         | 0.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 1         | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 46        | 49.46%  |
| Intel                    | 32        | 34.41%  |
| Qualcomm Atheros         | 5         | 5.38%   |
| Marvell Technology Group | 2         | 2.15%   |
| ASIX Electronics         | 2         | 2.15%   |
| Xiaomi                   | 1         | 1.08%   |
| OPPO Electronics         | 1         | 1.08%   |
| Lenovo                   | 1         | 1.08%   |
| DisplayLink              | 1         | 1.08%   |
| Broadcom Limited         | 1         | 1.08%   |
| Broadcom                 | 1         | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 31.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 8.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 7.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6.38%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 5.32%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 3.19%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 3.19%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.06%   |
| Realtek USB 10/100 LAN                                            | 1         | 1.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.06%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.06%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.06%   |
| OPPO Find X2 Lite                                                 | 1         | 1.06%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.06%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.06%   |
| Lenovo Thinkpad LAN                                               | 1         | 1.06%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.06%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.06%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.06%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.06%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.06%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.06%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.06%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 1.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.06%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.06%   |
| ASIX AX88772B                                                     | 1         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 57.75%  |
| Ethernet | 88        | 41.31%  |
| Modem    | 2         | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 82.09%  |
| Ethernet | 24        | 17.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 76        | 61.29%  |
| 1     | 42        | 33.87%  |
| 0     | 6         | 4.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 56.12%  |
| Foxconn / Hon Hai               | 6         | 6.12%   |
| Broadcom                        | 6         | 6.12%   |
| Qualcomm Atheros Communications | 5         | 5.1%    |
| Realtek Semiconductor           | 4         | 4.08%   |
| Lite-On Technology              | 4         | 4.08%   |
| IMC Networks                    | 3         | 3.06%   |
| Hewlett-Packard                 | 3         | 3.06%   |
| Realtek                         | 2         | 2.04%   |
| Foxconn International           | 2         | 2.04%   |
| Dell                            | 2         | 2.04%   |
| Apple                           | 2         | 2.04%   |
| Taiyo Yuden                     | 1         | 1.02%   |
| Fujitsu                         | 1         | 1.02%   |
| Cambridge Silicon Radio         | 1         | 1.02%   |
| Askey Computer                  | 1         | 1.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 18.37%  |
| Intel Bluetooth Device                              | 16        | 16.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 10.2%   |
| Intel AX200 Bluetooth                               | 10        | 10.2%   |
| Realtek Bluetooth Radio                             | 4         | 4.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.06%   |
| IMC Networks Wireless_Device                        | 3         | 3.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 3.06%   |
| Realtek Bluetooth Radio                             | 2         | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.04%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.04%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 2.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 2.04%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.02%   |
| Lite-On Bluetooth Radio                             | 1         | 1.02%   |
| Lite-On Bluetooth Device                            | 1         | 1.02%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.02%   |
| Fujitsu Bluetooth Device                            | 1         | 1.02%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.02%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.02%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.02%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 1.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.02%   |
| Broadcom BCM2045A0                                  | 1         | 1.02%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.02%   |
| Askey Bluetooth Device                              | 1         | 1.02%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.02%   |
| Apple Bluetooth Host Controller                     | 1         | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 105       | 70.47%  |
| Nvidia                      | 20        | 13.42%  |
| AMD                         | 17        | 11.41%  |
| Generalplus Technology      | 2         | 1.34%   |
| VIA Technologies            | 1         | 0.67%   |
| Logitech                    | 1         | 0.67%   |
| iCreate Technologies        | 1         | 0.67%   |
| FiiO Electronics Technology | 1         | 0.67%   |
| BY EDIFIER                  | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 11.7%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 8.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 6.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 4.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 2.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.34%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 2.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 2.34%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.34%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.34%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.75%   |
| Nvidia Audio device                                                        | 3         | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.17%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.17%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.17%   |
| Generalplus Technology IMYB 7.1 Channel                                    | 2         | 1.17%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 0.58%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.58%   |
| Logitech USB Headset H540                                                  | 1         | 0.58%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.58%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 0.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.58%   |
| iCreate Technologies Xonar U7 Echelon Ed.                                  | 1         | 0.58%   |
| FiiO Electronics Technology Exynos                                         | 1         | 0.58%   |
| BY EDIFIER EDIFIER G2 II GAMING HEADSET                                    | 1         | 0.58%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.58%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 0.58%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 28        | 34.57%  |
| Samsung Electronics | 20        | 24.69%  |
| Micron Technology   | 10        | 12.35%  |
| Unknown             | 7         | 8.64%   |
| Kingston            | 5         | 6.17%   |
| Crucial             | 3         | 3.7%    |
| Unknown (ABCD)      | 2         | 2.47%   |
| Unknown             | 2         | 2.47%   |
| Team                | 1         | 1.23%   |
| Lenovo              | 1         | 1.23%   |
| Kingmax             | 1         | 1.23%   |
| A-DATA Technology   | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 4.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 2.38%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 2         | 2.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 2.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 2.38%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 2.38%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 2.38%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 2.38%   |
| Unknown                                                          | 2         | 2.38%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.19%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.19%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.19%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.19%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 1.19%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 1         | 1.19%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.19%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.19%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.19%   |
| SK hynix RAM HMAA4GS7AJR8N-WM 32GB SODIMM DDR4 2933MT/s          | 1         | 1.19%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.19%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.19%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16384MB SODIMM DDR4 2400MT/s       | 1         | 1.19%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.19%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.19%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.19%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.19%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.19%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.19%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.19%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.19%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.19%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4096MB 1867MT/s                  | 1         | 1.19%   |
| SK hynix RAM D471A1K43CB1-CTD 8GB SODIMM DDR4 2400MT/s           | 1         | 1.19%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s           | 1         | 1.19%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s           | 1         | 1.19%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.19%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.19%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.19%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.19%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.19%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.19%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.19%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.19%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.19%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.19%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 1         | 1.19%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8192MB SODIMM 4800MT/s            | 1         | 1.19%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.19%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips 6400MT/s        | 1         | 1.19%   |
| Micron RAM Module 4GB SODIMM LPDDR3 1867MT/s                     | 1         | 1.19%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.19%   |
| Micron RAM 8KTF51264HDZ-1G9E1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.19%   |
| Micron RAM 8JTF25664JHZ-1G6M2 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.19%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.19%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.19%   |
| Micron RAM 4ATF51264HZ-2G6E! 4096MB SODIMM DDR4 2400MT/s         | 1         | 1.19%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 30        | 44.78%  |
| DDR3    | 13        | 19.4%   |
| LPDDR3  | 8         | 11.94%  |
| LPDDR4  | 6         | 8.96%   |
| Unknown | 4         | 5.97%   |
| DDR2    | 3         | 4.48%   |
| SDRAM   | 1         | 1.49%   |
| DRAM    | 1         | 1.49%   |
| DDR     | 1         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 71.21%  |
| Row Of Chips | 15        | 22.73%  |
| DIMM         | 3         | 4.55%   |
| Unknown      | 1         | 1.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 27        | 36.49%  |
| 4096  | 20        | 27.03%  |
| 2048  | 9         | 12.16%  |
| 32768 | 7         | 9.46%   |
| 16384 | 7         | 9.46%   |
| 1024  | 2         | 2.7%    |
| 512   | 1         | 1.35%   |
| 232   | 1         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 14        | 19.72%  |
| 1600    | 13        | 18.31%  |
| 3200    | 12        | 16.9%   |
| 2400    | 6         | 8.45%   |
| 2133    | 5         | 7.04%   |
| 1867    | 5         | 7.04%   |
| 4267    | 3         | 4.23%   |
| Unknown | 3         | 4.23%   |
| 667     | 2         | 2.82%   |
| 6400    | 1         | 1.41%   |
| 4800    | 1         | 1.41%   |
| 3733    | 1         | 1.41%   |
| 3266    | 1         | 1.41%   |
| 2933    | 1         | 1.41%   |
| 1334    | 1         | 1.41%   |
| 975     | 1         | 1.41%   |
| 533     | 1         | 1.41%   |

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
| Chicony Electronics                    | 25        | 24.27%  |
| IMC Networks                           | 11        | 10.68%  |
| Acer                                   | 10        | 9.71%   |
| Microdia                               | 9         | 8.74%   |
| Realtek Semiconductor                  | 6         | 5.83%   |
| Luxvisions Innotech Limited            | 5         | 4.85%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.85%   |
| Sunplus Innovation Technology          | 4         | 3.88%   |
| Syntek                                 | 3         | 2.91%   |
| Apple                                  | 3         | 2.91%   |
| Alcor Micro                            | 3         | 2.91%   |
| Suyin                                  | 2         | 1.94%   |
| Silicon Motion                         | 2         | 1.94%   |
| Quanta                                 | 2         | 1.94%   |
| Lite-On Technology                     | 2         | 1.94%   |
| Importek                               | 2         | 1.94%   |
| WaveRider Communications               | 1         | 0.97%   |
| Sonix Technology                       | 1         | 0.97%   |
| Ricoh                                  | 1         | 0.97%   |
| Primax Electronics                     | 1         | 0.97%   |
| Nebraska Furniture Mart                | 1         | 0.97%   |
| Microsoft                              | 1         | 0.97%   |
| Logitech                               | 1         | 0.97%   |
| lihappe8                               | 1         | 0.97%   |
| Genesys Logic                          | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 7         | 6.73%   |
| Chicony Integrated Camera                                       | 6         | 5.77%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 4.81%   |
| Chicony FJ Camera                                               | 5         | 4.81%   |
| IMC Networks Integrated Camera                                  | 4         | 3.85%   |
| Chicony HD Webcam                                               | 4         | 3.85%   |
| Syntek Integrated Camera                                        | 3         | 2.88%   |
| Alcor Micro USB 2.0 Camera                                      | 3         | 2.88%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 1.92%   |
| Luxvisions Innotech Limited HP HD Camera                        | 2         | 1.92%   |
| Lite-On Integrated Camera                                       | 2         | 1.92%   |
| Importek FJ Camera                                              | 2         | 1.92%   |
| Acer SunplusIT Integrated Camera                                | 2         | 1.92%   |
| Acer Lenovo EasyCamera                                          | 2         | 1.92%   |
| Acer Integrated Camera                                          | 2         | 1.92%   |
| WaveRider USB 2.0 Camera                                        | 1         | 0.96%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 1         | 0.96%   |
| Suyin HP Truevision HD                                          | 1         | 0.96%   |
| Sunplus MTD Camera                                              | 1         | 0.96%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 0.96%   |
| Sunplus HP Universal Camera                                     | 1         | 0.96%   |
| Sunplus HD WebCam                                               | 1         | 0.96%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 0.96%   |
| Silicon Motion 720p HD Camera                                   | 1         | 0.96%   |
| Silicon Motion 300k Pixel Camera                                | 1         | 0.96%   |
| Ricoh USB2.0 Camera                                             | 1         | 0.96%   |
| Realtek WebCamera                                               | 1         | 0.96%   |
| Realtek USB2.0 HD UVC WebCam                                    | 1         | 0.96%   |
| Realtek Lenovo easy camera                                      | 1         | 0.96%   |
| Realtek Integrated Webcam_HD                                    | 1         | 0.96%   |
| Quanta USB Webcam                                               | 1         | 0.96%   |
| Quanta hm1091_techfront                                         | 1         | 0.96%   |
| Primax Dell Laptop Integrated Webcam 2Mpix                      | 1         | 0.96%   |
| Nebraska Furniture Mart USB 2.0 PC cam                          | 1         | 0.96%   |
| Microsoft LifeCam Cinema                                        | 1         | 0.96%   |
| Microdia Laptop_Integrated_Webcam_0.3M                          | 1         | 0.96%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 0.96%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 1         | 0.96%   |
| Luxvisions Innotech Limited Integrated Camera                   | 1         | 0.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 0.96%   |
| Logitech Fujitsu Webcam                                         | 1         | 0.96%   |
| lihappe8 USB 2.0 Camera                                         | 1         | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 0.96%   |
| IMC Networks Lenovo EasyCamera                                  | 1         | 0.96%   |
| Genesys Logic Camera                                            | 1         | 0.96%   |
| Chicony VGA WebCam                                              | 1         | 0.96%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 0.96%   |
| Chicony USB 2.0 Webcam Device                                   | 1         | 0.96%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 0.96%   |
| Chicony Lenovo EasyCamera                                       | 1         | 0.96%   |
| Chicony Integrated Camera [ThinkPad]                            | 1         | 0.96%   |
| Chicony Integrated Camera (1280x720@30)                         | 1         | 0.96%   |
| Chicony HP Webcam [2 MP Macro]                                  | 1         | 0.96%   |
| Chicony Fujitsu Integrated Camera                               | 1         | 0.96%   |
| Chicony CNF8031                                                 | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi Webcam            | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 1         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM         | 1         | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 29.17%  |
| Validity Sensors           | 6         | 25%     |
| Shenzhen Goodix Technology | 5         | 20.83%  |
| Upek                       | 2         | 8.33%   |
| AuthenTec                  | 2         | 8.33%   |
| Samsung Electronics        | 1         | 4.17%   |
| LighTuning Technology      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 12.5%   |
| Validity Sensors Synaptics WBDI                        | 2         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 8.33%   |
| Shenzhen Goodix FingerPrint                            | 2         | 8.33%   |
| AuthenTec Fingerprint Sensor                           | 2         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.17%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.17%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 4.17%   |
| Samsung Fingerprint Device                             | 1         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.17%   |
| Unknown                                                | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Upek        | 2         | 20%     |
| Lenovo      | 2         | 20%     |
| O2 Micro    | 1         | 10%     |
| Alcor Micro | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 20%     |
| Lenovo Integrated Smart Card Reader                                          | 2         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 73        | 57.48%  |
| 1     | 40        | 31.5%   |
| 2     | 10        | 7.87%   |
| 3     | 2         | 1.57%   |
| 5     | 1         | 0.79%   |
| 4     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 31.51%  |
| Graphics card            | 17        | 23.29%  |
| Chipcard                 | 10        | 13.7%   |
| Multimedia controller    | 7         | 9.59%   |
| Net/wireless             | 6         | 8.22%   |
| Communication controller | 3         | 4.11%   |
| Bluetooth                | 2         | 2.74%   |
| Storage                  | 1         | 1.37%   |
| Sound                    | 1         | 1.37%   |
| Net/ethernet             | 1         | 1.37%   |
| Card reader              | 1         | 1.37%   |
| Camera                   | 1         | 1.37%   |

