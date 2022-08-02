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

Total: 201

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| KOHJINSHA     | SC series                   | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Fujitsu       | LIFEBOOK V1020              | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| IBM           | 260921H                     | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | [f3e0ebd16e](https://linux-hardware.org/?probe=f3e0ebd16e) | Jul 15, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | [ab1472b3cd](https://linux-hardware.org/?probe=ab1472b3cd) | Jul 15, 2022 |
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
| Ubuntu 20.04                 | 26        | 18.84%  |
| Ubuntu 18.04                 | 9         | 6.52%   |
| Arch                         | 7         | 5.07%   |
| antiX 21                     | 7         | 5.07%   |
| Fedora 32                    | 5         | 3.62%   |
| Ubuntu 19.10                 | 4         | 2.9%    |
| Gentoo 2.7                   | 4         | 2.9%    |
| OpenMandriva 4.2             | 3         | 2.17%   |
| Linux Mint 20                | 3         | 2.17%   |
| Fedora 33                    | 3         | 2.17%   |
| Chrome OS                    | 3         | 2.17%   |
| ArcoLinux Rolling            | 3         | 2.17%   |
| Arch Rolling                 | 3         | 2.17%   |
| Ubuntu 22.04                 | 2         | 1.45%   |
| Ubuntu 21.04                 | 2         | 1.45%   |
| Ubuntu 19.04                 | 2         | 1.45%   |
| Ubuntu 16.04                 | 2         | 1.45%   |
| Pop!_OS 22.04                | 2         | 1.45%   |
| Pop!_OS 20.10                | 2         | 1.45%   |
| Pop!_OS 20.04                | 2         | 1.45%   |
| Manjaro 20.1                 | 2         | 1.45%   |
| Linux Mint 20.3              | 2         | 1.45%   |
| KDE neon 20.04               | 2         | 1.45%   |
| Fedora 36                    | 2         | 1.45%   |
| Fedora 34                    | 2         | 1.45%   |
| EndeavourOS Rolling          | 2         | 1.45%   |
| Zorin 15                     | 1         | 0.72%   |
| UbuntuDDE 21.10              | 1         | 0.72%   |
| Ubuntu Budgie 20.04          | 1         | 0.72%   |
| Ubuntu 21.10                 | 1         | 0.72%   |
| Ubuntu 20.10                 | 1         | 0.72%   |
| ROSA R11                     | 1         | 0.72%   |
| ROSA R10                     | 1         | 0.72%   |
| Pop!_OS 21.10                | 1         | 0.72%   |
| Pop!_OS 21.04                | 1         | 0.72%   |
| PCLinuxOS 2020               | 1         | 0.72%   |
| Oracle Linux 8.6             | 1         | 0.72%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.72%   |
| OpenMandriva 4.90            | 1         | 0.72%   |
| OpenMandriva 4.50            | 1         | 0.72%   |
| OpenMandriva 4.3             | 1         | 0.72%   |
| Manjaro 21.1.0               | 1         | 0.72%   |
| Manjaro 21.0                 | 1         | 0.72%   |
| Manjaro 20.2.1               | 1         | 0.72%   |
| Linux Mint 20.1              | 1         | 0.72%   |
| Linux Mint 19.1              | 1         | 0.72%   |
| Kubuntu 21.10                | 1         | 0.72%   |
| Kali 2021.4                  | 1         | 0.72%   |
| Gentoo 2.8                   | 1         | 0.72%   |
| Fedora 35                    | 1         | 0.72%   |
| Fedora 30                    | 1         | 0.72%   |
| Elementary 5.1.7             | 1         | 0.72%   |
| Elementary 5.1.5             | 1         | 0.72%   |
| Debian 11                    | 1         | 0.72%   |
| Clear Linux 34930            | 1         | 0.72%   |
| Clear Linux 34290            | 1         | 0.72%   |
| Clear Linux 34180            | 1         | 0.72%   |
| BlackPanther 16.2            | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 48        | 35.82%  |
| Fedora        | 14        | 10.45%  |
| Arch          | 10        | 7.46%   |
| Pop!_OS       | 8         | 5.97%   |
| antiX         | 7         | 5.22%   |
| OpenMandriva  | 6         | 4.48%   |
| Linux Mint    | 6         | 4.48%   |
| Manjaro       | 5         | 3.73%   |
| Gentoo        | 4         | 2.99%   |
| Clear Linux   | 3         | 2.24%   |
| Chrome OS     | 3         | 2.24%   |
| ArcoLinux     | 3         | 2.24%   |
| ROSA          | 2         | 1.49%   |
| KDE neon      | 2         | 1.49%   |
| EndeavourOS   | 2         | 1.49%   |
| Zorin         | 1         | 0.75%   |
| UbuntuDDE     | 1         | 0.75%   |
| Ubuntu Budgie | 1         | 0.75%   |
| PCLinuxOS     | 1         | 0.75%   |
| Oracle Linux  | 1         | 0.75%   |
| openSUSE      | 1         | 0.75%   |
| Kubuntu       | 1         | 0.75%   |
| Kali          | 1         | 0.75%   |
| Elementary    | 1         | 0.75%   |
| Debian        | 1         | 0.75%   |
| BlackPanther  | 1         | 0.75%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp       | 7         | 4.7%    |
| 5.4.0-42-generic                | 6         | 4.03%   |
| 5.8.0-43-generic                | 3         | 2.01%   |
| 5.4.0-48-generic                | 3         | 2.01%   |
| 5.13.0-39-generic               | 3         | 2.01%   |
| 5.10.14-desktop-1omv4002        | 3         | 2.01%   |
| 4.19.49+                        | 3         | 2.01%   |
| 5.9.2-arch1-1                   | 2         | 1.34%   |
| 5.8.0-7630-generic              | 2         | 1.34%   |
| 5.4.0-58-generic                | 2         | 1.34%   |
| 5.4.0-28-generic                | 2         | 1.34%   |
| 5.4.0-26-generic                | 2         | 1.34%   |
| 5.3.0-18-generic                | 2         | 1.34%   |
| 5.17.11-300.fc36.x86_64         | 2         | 1.34%   |
| 5.13.0-35-generic               | 2         | 1.34%   |
| 5.11.0-37-generic               | 2         | 1.34%   |
| 5.0.0-31-generic                | 2         | 1.34%   |
| 4.18.0-15-generic               | 2         | 1.34%   |
| 5.9.8-200.fc33.x86_64           | 1         | 0.67%   |
| 5.9.3-arch1-1                   | 1         | 0.67%   |
| 5.9.14-100.fc32.x86_64          | 1         | 0.67%   |
| 5.9.10-artix1-1                 | 1         | 0.67%   |
| 5.8.6-1-MANJARO                 | 1         | 0.67%   |
| 5.8.3-2-MANJARO                 | 1         | 0.67%   |
| 5.8.15-gentoo                   | 1         | 0.67%   |
| 5.8.0-64-generic                | 1         | 0.67%   |
| 5.8.0-63-generic                | 1         | 0.67%   |
| 5.8.0-55-generic                | 1         | 0.67%   |
| 5.8.0-54-generic                | 1         | 0.67%   |
| 5.8.0-33-generic                | 1         | 0.67%   |
| 5.8.0-25-generic                | 1         | 0.67%   |
| 5.7.9-200.fc32.x86_64           | 1         | 0.67%   |
| 5.7.4-gentoo                    | 1         | 0.67%   |
| 5.7.11-200.fc32.x86_64          | 1         | 0.67%   |
| 5.7.10-201.fc32.x86_64          | 1         | 0.67%   |
| 5.6.3-zen1-1-zen                | 1         | 0.67%   |
| 5.4.17-2136.300.7.el8uek.x86_64 | 1         | 0.67%   |
| 5.4.0-7634-generic              | 1         | 0.67%   |
| 5.4.0-67-generic                | 1         | 0.67%   |
| 5.4.0-65-generic                | 1         | 0.67%   |
| 5.4.0-53-generic                | 1         | 0.67%   |
| 5.4.0-52-generic                | 1         | 0.67%   |
| 5.4.0-45-generic                | 1         | 0.67%   |
| 5.4.0-37-generic                | 1         | 0.67%   |
| 5.4.0-33-generic                | 1         | 0.67%   |
| 5.4.0-122-generic               | 1         | 0.67%   |
| 5.4.0-117-generic               | 1         | 0.67%   |
| 5.4.0-1007-fips                 | 1         | 0.67%   |
| 5.3.5-200.fc30.x86_64           | 1         | 0.67%   |
| 5.3.14-lqx1-1-lqx               | 1         | 0.67%   |
| 5.3.11-zen1-1-zen               | 1         | 0.67%   |
| 5.3.0-59-generic                | 1         | 0.67%   |
| 5.3.0-46-generic                | 1         | 0.67%   |
| 5.3.0-24-generic                | 1         | 0.67%   |
| 5.18.7-zen1-1-zen               | 1         | 0.67%   |
| 5.18.5-arch1-1                  | 1         | 0.67%   |
| 5.18.12-desktop-3omv4090        | 1         | 0.67%   |
| 5.17.9-arch1-1                  | 1         | 0.67%   |
| 5.17.5-76051705-generic         | 1         | 0.67%   |
| 5.17.4-100.fc34.x86_64          | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 14.29%  |
| 5.13.0  | 10        | 7.14%   |
| 5.8.0   | 9         | 6.43%   |
| 4.9.0   | 7         | 5%      |
| 4.15.0  | 7         | 5%      |
| 5.11.0  | 6         | 4.29%   |
| 5.3.0   | 5         | 3.57%   |
| 5.0.0   | 5         | 3.57%   |
| 5.10.14 | 3         | 2.14%   |
| 4.19.49 | 3         | 2.14%   |
| 5.9.2   | 2         | 1.43%   |
| 5.17.4  | 2         | 1.43%   |
| 5.17.11 | 2         | 1.43%   |
| 5.15.0  | 2         | 1.43%   |
| 4.18.0  | 2         | 1.43%   |
| 5.9.8   | 1         | 0.71%   |
| 5.9.3   | 1         | 0.71%   |
| 5.9.14  | 1         | 0.71%   |
| 5.9.10  | 1         | 0.71%   |
| 5.8.6   | 1         | 0.71%   |
| 5.8.3   | 1         | 0.71%   |
| 5.8.15  | 1         | 0.71%   |
| 5.7.9   | 1         | 0.71%   |
| 5.7.4   | 1         | 0.71%   |
| 5.7.11  | 1         | 0.71%   |
| 5.7.10  | 1         | 0.71%   |
| 5.6.3   | 1         | 0.71%   |
| 5.4.17  | 1         | 0.71%   |
| 5.3.5   | 1         | 0.71%   |
| 5.3.14  | 1         | 0.71%   |
| 5.3.11  | 1         | 0.71%   |
| 5.18.7  | 1         | 0.71%   |
| 5.18.5  | 1         | 0.71%   |
| 5.18.12 | 1         | 0.71%   |
| 5.17.9  | 1         | 0.71%   |
| 5.17.5  | 1         | 0.71%   |
| 5.17.3  | 1         | 0.71%   |
| 5.17.1  | 1         | 0.71%   |
| 5.16.7  | 1         | 0.71%   |
| 5.16.19 | 1         | 0.71%   |
| 5.16.12 | 1         | 0.71%   |
| 5.16.11 | 1         | 0.71%   |
| 5.15.48 | 1         | 0.71%   |
| 5.15.15 | 1         | 0.71%   |
| 5.15.13 | 1         | 0.71%   |
| 5.14.8  | 1         | 0.71%   |
| 5.14.7  | 1         | 0.71%   |
| 5.14.15 | 1         | 0.71%   |
| 5.14.0  | 1         | 0.71%   |
| 5.13.8  | 1         | 0.71%   |
| 5.13.13 | 1         | 0.71%   |
| 5.12.9  | 1         | 0.71%   |
| 5.11.6  | 1         | 0.71%   |
| 5.11.2  | 1         | 0.71%   |
| 5.11.19 | 1         | 0.71%   |
| 5.11.18 | 1         | 0.71%   |
| 5.11.17 | 1         | 0.71%   |
| 5.11.12 | 1         | 0.71%   |
| 5.11.10 | 1         | 0.71%   |
| 5.10.8  | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 14.49%  |
| 5.8     | 12        | 8.7%    |
| 5.13    | 12        | 8.7%    |
| 5.11    | 12        | 8.7%    |
| 5.10    | 11        | 7.97%   |
| 4.9     | 9         | 6.52%   |
| 5.3     | 8         | 5.8%    |
| 5.17    | 8         | 5.8%    |
| 4.15    | 7         | 5.07%   |
| 5.9     | 6         | 4.35%   |
| 5.15    | 5         | 3.62%   |
| 5.0     | 5         | 3.62%   |
| 5.7     | 4         | 2.9%    |
| 5.16    | 4         | 2.9%    |
| 5.14    | 4         | 2.9%    |
| 5.18    | 3         | 2.17%   |
| 4.19    | 3         | 2.17%   |
| 4.18    | 3         | 2.17%   |
| 5.6     | 1         | 0.72%   |
| 5.12    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 121       | 91.67%  |
| i686   | 10        | 7.58%   |
| i586   | 1         | 0.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 65        | 48.15%  |
| Unknown    | 27        | 20%     |
| KDE5       | 22        | 16.3%   |
| XFCE       | 4         | 2.96%   |
| X-Cinnamon | 4         | 2.96%   |
| KDE        | 3         | 2.22%   |
| i3         | 3         | 2.22%   |
| Unity      | 1         | 0.74%   |
| LXQt       | 1         | 0.74%   |
| fvwm       | 1         | 0.74%   |
| dwm        | 1         | 0.74%   |
| Deepin     | 1         | 0.74%   |
| Cinnamon   | 1         | 0.74%   |
| Budgie     | 1         | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 109       | 81.95%  |
| Wayland | 15        | 11.28%  |
| Unknown | 8         | 6.02%   |
| Tty     | 1         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 51.49%  |
| SDDM    | 24        | 17.91%  |
| GDM     | 22        | 16.42%  |
| LightDM | 8         | 5.97%   |
| GDM3    | 7         | 5.22%   |
| TDM     | 4         | 2.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 57        | 41.91%  |
| en_HK   | 23        | 16.91%  |
| Unknown | 19        | 13.97%  |
| zh_CN   | 15        | 11.03%  |
| zh_HK   | 7         | 5.15%   |
| zh_TW   | 5         | 3.68%   |
| C       | 4         | 2.94%   |
| en_GB   | 3         | 2.21%   |
| it_IT   | 1         | 0.74%   |
| en_ZA   | 1         | 0.74%   |
| en_AU   | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 88        | 66.17%  |
| BIOS | 45        | 33.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 97        | 72.39%  |
| Btrfs   | 14        | 10.45%  |
| Overlay | 9         | 6.72%   |
| Unknown | 7         | 5.22%   |
| Xfs     | 3         | 2.24%   |
| Zfs     | 2         | 1.49%   |
| Ext3    | 1         | 0.75%   |
| Ext2    | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 48.15%  |
| GPT     | 57        | 42.22%  |
| MBR     | 13        | 9.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 90.23%  |
| Yes       | 13        | 9.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 57.89%  |
| Yes       | 56        | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 41        | 31.06%  |
| Dell                 | 17        | 12.88%  |
| Hewlett-Packard      | 13        | 9.85%   |
| ASUSTek Computer     | 12        | 9.09%   |
| Fujitsu              | 11        | 8.33%   |
| Unknown              | 8         | 6.06%   |
| Acer                 | 5         | 3.79%   |
| HUAWEI               | 3         | 2.27%   |
| Apple                | 3         | 2.27%   |
| Toshiba              | 2         | 1.52%   |
| Samsung Electronics  | 2         | 1.52%   |
| KOHJINSHA            | 2         | 1.52%   |
| IBM                  | 2         | 1.52%   |
| GPD                  | 2         | 1.52%   |
| Timi                 | 1         | 0.76%   |
| Sony                 | 1         | 0.76%   |
| Schenker             | 1         | 0.76%   |
| Panasonic            | 1         | 0.76%   |
| MSI                  | 1         | 0.76%   |
| Jumper               | 1         | 0.76%   |
| Intel Client Systems | 1         | 0.76%   |
| Google               | 1         | 0.76%   |
| Compaq               | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 9         | 6.82%   |
| Lenovo Legion R7000 2020 82B6            | 2         | 1.52%   |
| IBM 260921H                              | 2         | 1.52%   |
| HUAWEI KPRC-WX0                          | 2         | 1.52%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC         | 2         | 1.52%   |
| HP EliteBook 2540p                       | 2         | 1.52%   |
| Fujitsu UH-X                             | 2         | 1.52%   |
| Fujitsu LIFEBOOK AH544                   | 2         | 1.52%   |
| Dell XPS 13 9310                         | 2         | 1.52%   |
| Dell Inspiron 5580                       | 2         | 1.52%   |
| ASUS TUF Gaming FA506IU_FA506IU          | 2         | 1.52%   |
| Toshiba PORTEGE R830                     | 1         | 0.76%   |
| Toshiba dynabook R731/E                  | 1         | 0.76%   |
| Timi TM1607                              | 1         | 0.76%   |
| Sony VPCCB17FG                           | 1         | 0.76%   |
| Schenker XMG_APEX15_XAP15E20             | 1         | 0.76%   |
| Samsung SQ1S                             | 1         | 0.76%   |
| Samsung 930XBE                           | 1         | 0.76%   |
| Panasonic CFSZ5-2L                       | 1         | 0.76%   |
| MSI GS73VR 7RG                           | 1         | 0.76%   |
| Lenovo ZHAOYANG K47                      | 1         | 0.76%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.76%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN        | 1         | 0.76%   |
| Lenovo XiaoXin-14API QC 2019 81UW        | 1         | 0.76%   |
| Lenovo XiaoXin Chao7000-14IKBR 81GA      | 1         | 0.76%   |
| Lenovo ThinkPad X270 20HNA00RAD          | 1         | 0.76%   |
| Lenovo ThinkPad X250 20CLA1VECD          | 1         | 0.76%   |
| Lenovo ThinkPad X220 4290NL5             | 1         | 0.76%   |
| Lenovo ThinkPad X1 Extreme 20MFS0PE00    | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1001BHH | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR003HHH | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBA05VCD | 1         | 0.76%   |
| Lenovo ThinkPad W530 24384KU             | 1         | 0.76%   |
| Lenovo ThinkPad T61 6465CTO              | 1         | 0.76%   |
| Lenovo ThinkPad T520 4242BC5             | 1         | 0.76%   |
| Lenovo ThinkPad T480s 20L7CTO1WW         | 1         | 0.76%   |
| Lenovo ThinkPad T480s 20L7005FUS         | 1         | 0.76%   |
| Lenovo ThinkPad T430s 2355C33            | 1         | 0.76%   |
| Lenovo ThinkPad T430 2342AG4             | 1         | 0.76%   |
| Lenovo ThinkPad T400 64751W1             | 1         | 0.76%   |
| Lenovo ThinkPad S3 Yoga 14 20DM000VUS    | 1         | 0.76%   |
| Lenovo ThinkPad P15v Gen 1 20TQS08G00    | 1         | 0.76%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 0.76%   |
| Lenovo ThinkPad L14 Gen 1 20U6A008CD     | 1         | 0.76%   |
| Lenovo ThinkPad E14 20RAA002CD           | 1         | 0.76%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0         | 1         | 0.76%   |
| Lenovo Legion Y9000P2021H 82JD           | 1         | 0.76%   |
| Lenovo Legion Y7000P2020H 82AX           | 1         | 0.76%   |
| Lenovo Legion 5 15ACH6 82JW              | 1         | 0.76%   |
| Lenovo IdeaPad Yoga 13 20175             | 1         | 0.76%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 1         | 0.76%   |
| Lenovo IdeaPad 5 14IIL05 81YH            | 1         | 0.76%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 0.76%   |
| Lenovo IdeaPad 320-15IKB 80XL            | 1         | 0.76%   |
| Lenovo G770 20089                        | 1         | 0.76%   |
| Lenovo G710 20252                        | 1         | 0.76%   |
| Lenovo E10-30 20424                      | 1         | 0.76%   |
| Lenovo 3000 G410                         | 1         | 0.76%   |
| KOHJINSHA SX series                      | 1         | 0.76%   |
| KOHJINSHA SC series                      | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 20        | 15.15%  |
| Unknown                       | 9         | 6.82%   |
| Fujitsu LIFEBOOK              | 8         | 6.06%   |
| Dell XPS                      | 6         | 4.55%   |
| Lenovo Legion                 | 5         | 3.79%   |
| Lenovo IdeaPad                | 5         | 3.79%   |
| Dell Inspiron                 | 5         | 3.79%   |
| HP EliteBook                  | 3         | 2.27%   |
| Dell Precision                | 3         | 2.27%   |
| ASUS TUF                      | 3         | 2.27%   |
| Acer Aspire                   | 3         | 2.27%   |
| IBM 260921H                   | 2         | 1.52%   |
| HUAWEI KPRC-WX0               | 2         | 1.52%   |
| HP ZHAN                       | 2         | 1.52%   |
| Fujitsu UH-X                  | 2         | 1.52%   |
| Dell Latitude                 | 2         | 1.52%   |
| ASUS ROG                      | 2         | 1.52%   |
| Acer Swift                    | 2         | 1.52%   |
| Toshiba PORTEGE               | 1         | 0.76%   |
| Toshiba dynabook              | 1         | 0.76%   |
| Timi TM1607                   | 1         | 0.76%   |
| Sony VPCCB17FG                | 1         | 0.76%   |
| Schenker XMG                  | 1         | 0.76%   |
| Samsung SQ1S                  | 1         | 0.76%   |
| Samsung 930XBE                | 1         | 0.76%   |
| Panasonic CFSZ5-2L            | 1         | 0.76%   |
| MSI GS73VR                    | 1         | 0.76%   |
| Lenovo ZHAOYANG               | 1         | 0.76%   |
| Lenovo Yoga                   | 1         | 0.76%   |
| Lenovo XiaoXinAir-14ARE       | 1         | 0.76%   |
| Lenovo XiaoXin-14API          | 1         | 0.76%   |
| Lenovo XiaoXin                | 1         | 0.76%   |
| Lenovo ThinkBook              | 1         | 0.76%   |
| Lenovo G770                   | 1         | 0.76%   |
| Lenovo G710                   | 1         | 0.76%   |
| Lenovo E10-30                 | 1         | 0.76%   |
| Lenovo 3000                   | 1         | 0.76%   |
| KOHJINSHA SX                  | 1         | 0.76%   |
| KOHJINSHA SC                  | 1         | 0.76%   |
| Jumper EZbook                 | 1         | 0.76%   |
| Intel Client Systems LAPKC71F | 1         | 0.76%   |
| HUAWEI WRT-WX9                | 1         | 0.76%   |
| HP Victus                     | 1         | 0.76%   |
| HP ProBook                    | 1         | 0.76%   |
| HP OMEN                       | 1         | 0.76%   |
| HP Notebook                   | 1         | 0.76%   |
| HP Laptop                     | 1         | 0.76%   |
| HP G72                        | 1         | 0.76%   |
| HP 2140                       | 1         | 0.76%   |
| HP 2000                       | 1         | 0.76%   |
| GPD P2                        | 1         | 0.76%   |
| GPD G1618-03                  | 1         | 0.76%   |
| Google Eve                    | 1         | 0.76%   |
| Fujitsu S6420                 | 1         | 0.76%   |
| Dell G7                       | 1         | 0.76%   |
| Compaq Tablet                 | 1         | 0.76%   |
| ASUS Zephyrus                 | 1         | 0.76%   |
| ASUS Zenbook                  | 1         | 0.76%   |
| ASUS X556URK                  | 1         | 0.76%   |
| ASUS UX302LA                  | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 22        | 16.67%  |
| 2018 | 18        | 13.64%  |
| 2021 | 15        | 11.36%  |
| 2019 | 13        | 9.85%   |
| 2011 | 9         | 6.82%   |
| 2017 | 8         | 6.06%   |
| 2012 | 7         | 5.3%    |
| 2014 | 6         | 4.55%   |
| 2010 | 6         | 4.55%   |
| 2015 | 5         | 3.79%   |
| 2008 | 5         | 3.79%   |
| 2022 | 4         | 3.03%   |
| 2016 | 3         | 2.27%   |
| 2013 | 3         | 2.27%   |
| 2009 | 3         | 2.27%   |
| 2007 | 2         | 1.52%   |
| 1999 | 2         | 1.52%   |
| 2003 | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 132       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 114       | 86.36%  |
| Enabled  | 18        | 13.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 99.24%  |
| Yes  | 1         | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 22.73%  |
| 8.01-16.0   | 29        | 21.97%  |
| 16.01-24.0  | 25        | 18.94%  |
| 32.01-64.0  | 14        | 10.61%  |
| 3.01-4.0    | 14        | 10.61%  |
| 2.01-3.0    | 5         | 3.79%   |
| 64.01-256.0 | 4         | 3.03%   |
| 1.01-2.0    | 4         | 3.03%   |
| 0.51-1.0    | 3         | 2.27%   |
| 24.01-32.0  | 2         | 1.52%   |
| 0.01-0.5    | 2         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 37        | 26.81%  |
| 2.01-3.0   | 31        | 22.46%  |
| 4.01-8.0   | 24        | 17.39%  |
| 3.01-4.0   | 19        | 13.77%  |
| 0.01-0.5   | 11        | 7.97%   |
| 8.01-16.0  | 9         | 6.52%   |
| 0.51-1.0   | 4         | 2.9%    |
| 16.01-24.0 | 3         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 59.85%  |
| 2      | 47        | 34.31%  |
| 3      | 5         | 3.65%   |
| 0      | 2         | 1.46%   |
| 5      | 1         | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 77.61%  |
| Yes       | 30        | 22.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 70.45%  |
| No        | 39        | 29.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 99.24%  |
| No        | 1         | 0.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 75.94%  |
| No        | 32        | 24.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Hong Kong | 132       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Central       | 73        | 52.9%   |
| Shatin        | 9         | 6.52%   |
| Tung Chung    | 5         | 3.62%   |
| Kowloon       | 5         | 3.62%   |
| Wanchai       | 4         | 2.9%    |
| Hung Hom      | 4         | 2.9%    |
| Hong Kong     | 4         | 2.9%    |
| Tseung Kwan O | 3         | 2.17%   |
| Tai Po        | 3         | 2.17%   |
| Yuen Long     | 2         | 1.45%   |
| Tuen Mun      | 2         | 1.45%   |
| Ngau Wu Tok   | 2         | 1.45%   |
| Man Kok       | 2         | 1.45%   |
| Discovery Bay | 2         | 1.45%   |
| Yau Tsim Mong | 1         | 0.72%   |
| Wong Tai Sin  | 1         | 0.72%   |
| Tsuen Wan     | 1         | 0.72%   |
| To Kwa Wan    | 1         | 0.72%   |
| Tin Shui Wai  | 1         | 0.72%   |
| Tai Wan To    | 1         | 0.72%   |
| Tai Wan       | 1         | 0.72%   |
| Sheung Shui   | 1         | 0.72%   |
| Shau Kei Wan  | 1         | 0.72%   |
| Sai Kung      | 1         | 0.72%   |
| Quarry Bay    | 1         | 0.72%   |
| North Point   | 1         | 0.72%   |
| North         | 1         | 0.72%   |
| Mong Kok      | 1         | 0.72%   |
| Lam Tin       | 1         | 0.72%   |
| Kwun Hang     | 1         | 0.72%   |
| Fanling       | 1         | 0.72%   |
| Causeway Bay  | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 43     | 20.22%  |
| WDC                 | 20        | 21     | 11.24%  |
| Unknown             | 12        | 16     | 6.74%   |
| Seagate             | 10        | 11     | 5.62%   |
| SanDisk             | 10        | 11     | 5.62%   |
| Intel               | 10        | 12     | 5.62%   |
| Hitachi             | 8         | 8      | 4.49%   |
| SK hynix            | 7         | 7      | 3.93%   |
| Kingston            | 6         | 7      | 3.37%   |
| HGST                | 5         | 6      | 2.81%   |
| Toshiba             | 4         | 4      | 2.25%   |
| Micron Technology   | 4         | 5      | 2.25%   |
| Fujitsu             | 4         | 5      | 2.25%   |
| Crucial             | 4         | 7      | 2.25%   |
| Phison              | 3         | 3      | 1.69%   |
| KIOXIA              | 3         | 3      | 1.69%   |
| JMicron Technology  | 3         | 4      | 1.69%   |
| China               | 3         | 4      | 1.69%   |
| Plextor             | 2         | 3      | 1.12%   |
| KingSpec            | 2         | 3      | 1.12%   |
| Hikvision           | 2         | 2      | 1.12%   |
| Apple               | 2         | 3      | 1.12%   |
| Verbatim            | 1         | 2      | 0.56%   |
| Unknown (CF)        | 1         | 1      | 0.56%   |
| Transcend           | 1         | 1      | 0.56%   |
| TO Exter            | 1         | 1      | 0.56%   |
| Team                | 1         | 1      | 0.56%   |
| ShineDisk           | 1         | 1      | 0.56%   |
| RECADATA            | 1         | 1      | 0.56%   |
| Ramsta              | 1         | 1      | 0.56%   |
| PH4-CE12            | 1         | 1      | 0.56%   |
| Lexar               | 1         | 1      | 0.56%   |
| HS-SSD-C100         | 1         | 2      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| GALAX TA            | 1         | 1      | 0.56%   |
| Faspeed             | 1         | 1      | 0.56%   |
| BIWIN               | 1         | 1      | 0.56%   |
| Apacer              | 1         | 4      | 0.56%   |
| A-DATA Technology   | 1         | 1      | 0.56%   |
| Unknown             | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                  | 3         | 1.62%   |
| SanDisk NVMe SSD Drive 512GB            | 3         | 1.62%   |
| WDC WD10SPZX-22Z10T1 1TB                | 2         | 1.08%   |
| Unknown MMC Card  128GB                 | 2         | 1.08%   |
| Toshiba MQ01ABF050 500GB                | 2         | 1.08%   |
| SK hynix BC501 NVMe 128GB               | 2         | 1.08%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 1.08%   |
| SanDisk NVMe SSD Drive 256GB            | 2         | 1.08%   |
| Samsung SSD 970 EVO Plus 2TB            | 2         | 1.08%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 1.08%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.08%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 1.08%   |
| Samsung MZVL2512HCJQ-00BL2 512GB        | 2         | 1.08%   |
| Plextor PX-128M7VC 128GB SSD            | 2         | 1.08%   |
| KIOXIA NVMe SSD Drive 512GB             | 2         | 1.08%   |
| JMicron Generic 2TB                     | 2         | 1.08%   |
| Intel NVMe SSD Drive 512GB              | 2         | 1.08%   |
| Fujitsu F300 480GB                      | 2         | 1.08%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 1.08%   |
| WDC WDS500G2B0A 500GB SSD               | 1         | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.54%   |
| WDC WDS200T3X0C-00SJG0 2TB              | 1         | 0.54%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.54%   |
| WDC WDS100T2G0A-00JH30 1TB SSD          | 1         | 0.54%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.54%   |
| WDC WD7500BPVT-24HXZT1 752GB            | 1         | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.54%   |
| WDC WD5000BEVT-16A0RT0 500GB            | 1         | 0.54%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.54%   |
| WDC WD10SPCX-16HWST0 1TB                | 1         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.54%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 0.54%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 1         | 0.54%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB    | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB    | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 1         | 0.54%   |
| Verbatim Vi550 S3 SSD 128GB             | 1         | 0.54%   |
| Unknown SMI  121MB                      | 1         | 0.54%   |
| Unknown SD32G  32GB                     | 1         | 0.54%   |
| Unknown NVMe SSD Drive 1024GB           | 1         | 0.54%   |
| Unknown MMC Card  7GB                   | 1         | 0.54%   |
| Unknown MMC Card  32GB                  | 1         | 0.54%   |
| Unknown MMC Card  16GB                  | 1         | 0.54%   |
| Unknown DURM4R  128GB                   | 1         | 0.54%   |
| Unknown 064GE2  64GB                    | 1         | 0.54%   |
| Unknown 00000  129GB                    | 1         | 0.54%   |
| Unknown (CF) Card 16GB SSD              | 1         | 0.54%   |
| Transcend SSD 2GB                       | 1         | 0.54%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.54%   |
| Toshiba KBG20ZMS512G NVMe 512GB         | 1         | 0.54%   |
| TO Exter nal USB 3.0 1TB                | 1         | 0.54%   |
| Team TEAML5Lite3D120G 120GB SSD         | 1         | 0.54%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 0.54%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 1         | 0.54%   |
| SK hynix NVMe SSD Drive 2TB             | 1         | 0.54%   |
| SK hynix NVMe SSD Drive 1TB             | 1         | 0.54%   |
| SK hynix BC501 NVMe 256GB               | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 26.32%  |
| Seagate             | 10        | 11     | 26.32%  |
| Hitachi             | 8         | 8      | 21.05%  |
| HGST                | 5         | 6      | 13.16%  |
| Toshiba             | 2         | 2      | 5.26%   |
| Samsung Electronics | 1         | 1      | 2.63%   |
| JMicron Technology  | 1         | 2      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 27.08%  |
| WDC                 | 4         | 4      | 8.33%   |
| Intel               | 4         | 6      | 8.33%   |
| Crucial             | 4         | 7      | 8.33%   |
| China               | 3         | 4      | 6.25%   |
| Plextor             | 2         | 3      | 4.17%   |
| Kingston            | 2         | 2      | 4.17%   |
| Fujitsu             | 2         | 3      | 4.17%   |
| Verbatim            | 1         | 2      | 2.08%   |
| Unknown (CF)        | 1         | 1      | 2.08%   |
| Transcend           | 1         | 1      | 2.08%   |
| TO Exter            | 1         | 1      | 2.08%   |
| Team                | 1         | 1      | 2.08%   |
| SanDisk             | 1         | 1      | 2.08%   |
| RECADATA            | 1         | 1      | 2.08%   |
| Ramsta              | 1         | 1      | 2.08%   |
| Micron Technology   | 1         | 2      | 2.08%   |
| Lexar               | 1         | 1      | 2.08%   |
| Hikvision           | 1         | 1      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |
| Apacer              | 1         | 4      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 65        | 79     | 38.92%  |
| SSD     | 43        | 64     | 25.75%  |
| HDD     | 38        | 41     | 22.75%  |
| MMC     | 13        | 17     | 7.78%   |
| Unknown | 8         | 10     | 4.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 106    | 46.54%  |
| NVMe | 63        | 77     | 39.62%  |
| MMC  | 13        | 17     | 8.18%   |
| SAS  | 9         | 11     | 5.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 74     | 63.41%  |
| 0.51-1.0   | 22        | 22     | 26.83%  |
| 1.01-2.0   | 7         | 8      | 8.54%   |
| 10.01-20.0 | 1         | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 26.28%  |
| 251-500        | 28        | 20.44%  |
| 501-1000       | 18        | 13.14%  |
| 1-20           | 17        | 12.41%  |
| 1001-2000      | 16        | 11.68%  |
| 51-100         | 11        | 8.03%   |
| 21-50          | 4         | 2.92%   |
| 2001-3000      | 4         | 2.92%   |
| More than 3000 | 2         | 1.46%   |
| Unknown        | 1         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 64        | 45.07%  |
| 21-50     | 20        | 14.08%  |
| 51-100    | 19        | 13.38%  |
| 251-500   | 14        | 9.86%   |
| 101-250   | 13        | 9.15%   |
| 501-1000  | 6         | 4.23%   |
| 1001-2000 | 5         | 3.52%   |
| Unknown   | 1         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 1         | 1      | 11.11%  |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 860 EVO 1TB | 1         | 1      | 11.11%  |
| Hitachi HTS725050A7E630 500GB       | 1         | 1      | 11.11%  |
| Hitachi HTS723216L9A360 160GB       | 1         | 1      | 11.11%  |
| Hitachi HTC426040G8CE00 40GB        | 1         | 1      | 11.11%  |
| Hitachi DK23AA-60 6GB               | 1         | 1      | 11.11%  |
| HGST TOURO Mobile 1TB               | 1         | 1      | 11.11%  |
| Crucial CT240M500SSD1 240GB         | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 44.44%  |
| Seagate             | 1         | 1      | 11.11%  |
| SanDisk             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

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
| HDD  | 6         | 6      | 66.67%  |
| SSD  | 3         | 3      | 33.33%  |

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
| Detected | 74        | 118    | 52.48%  |
| Works    | 58        | 84     | 41.13%  |
| Malfunc  | 9         | 9      | 6.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 93        | 54.07%  |
| Samsung Electronics          | 25        | 14.53%  |
| SanDisk                      | 15        | 8.72%   |
| AMD                          | 10        | 5.81%   |
| SK hynix                     | 7         | 4.07%   |
| Phison Electronics           | 4         | 2.33%   |
| Kingston Technology Company  | 4         | 2.33%   |
| Toshiba America Info Systems | 3         | 1.74%   |
| Micron Technology            | 3         | 1.74%   |
| Silicon Motion               | 2         | 1.16%   |
| KIOXIA                       | 2         | 1.16%   |
| VIA Technologies             | 1         | 0.58%   |
| Nvidia                       | 1         | 0.58%   |
| Biwin Storage Technology     | 1         | 0.58%   |
| Apple                        | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 14        | 7.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 10        | 5.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 10        | 5.46%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 5.46%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 8         | 4.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 4.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 5         | 2.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 2.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 2.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 4         | 2.19%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 2.19%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 1.64%   |
| Micron Non-Volatile memory controller                                                  | 3         | 1.64%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 3         | 1.64%   |
| Intel SSD 660P Series                                                                  | 3         | 1.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 1.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.09%   |
| SK hynix Non-Volatile memory controller                                                | 2         | 1.09%   |
| SK hynix Gold P31 SSD                                                                  | 2         | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 1.09%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 1.09%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.09%   |
| Phison PS5013 E13 NVMe Controller                                                      | 2         | 1.09%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 1.09%   |
| Kingston Company Company Non-Volatile memory controller                                | 2         | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 1.09%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 2         | 1.09%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 1.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 1.09%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                          | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.09%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.55%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.55%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.55%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.55%   |
| Phison NVMe Storage Controller                                                         | 1         | 0.55%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.55%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.55%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.55%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.55%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 0.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.55%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 0.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 79        | 46.75%  |
| NVMe | 65        | 38.46%  |
| IDE  | 15        | 8.88%   |
| RAID | 10        | 5.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 112       | 84.85%  |
| AMD          | 19        | 14.39%  |
| GenuineTMx86 | 1         | 0.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 3.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 3.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 3.03%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 3.03%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.27%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.52%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.52%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.52%   |
| Intel Celeron (Mendocino)                     | 2         | 1.52%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 2         | 1.52%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 1.52%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.52%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.52%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.52%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.76%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.76%   |
| Intel Pentium M processor 1.00GHz             | 1         | 0.76%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.76%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.76%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.76%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.76%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.76%   |
| Intel Core m3-7Y32 CPU @ 1.10GHz              | 1         | 0.76%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.76%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 1         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.76%   |
| Intel Core i7-6560U CPU @ 2.20GHz             | 1         | 0.76%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.76%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 0.76%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.76%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.76%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.76%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.76%   |
| Intel Core i7 CPU L 640 @ 2.13GHz             | 1         | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.76%   |
| Intel Core i5-7Y57 CPU @ 1.20GHz              | 1         | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.76%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.76%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.76%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 0.76%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 0.76%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 25%     |
| Intel Core i7           | 29        | 21.97%  |
| Other                   | 14        | 10.61%  |
| Intel Celeron           | 12        | 9.09%   |
| AMD Ryzen 7             | 9         | 6.82%   |
| Intel Core i3           | 7         | 5.3%    |
| AMD Ryzen 5             | 5         | 3.79%   |
| Intel Core 2 Duo        | 4         | 3.03%   |
| Intel Atom              | 4         | 3.03%   |
| AMD Ryzen 9             | 4         | 3.03%   |
| Intel Core m3           | 3         | 2.27%   |
| Intel Xeon              | 2         | 1.52%   |
| Intel Pentium Dual-Core | 2         | 1.52%   |
| Intel Pentium M         | 1         | 0.76%   |
| Intel Pentium Gold      | 1         | 0.76%   |
| Intel Pentium Dual      | 1         | 0.76%   |
| AMD Ryzen 7 PRO         | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 55        | 41.67%  |
| 4      | 40        | 30.3%   |
| 8      | 15        | 11.36%  |
| 6      | 10        | 7.58%   |
| 1      | 8         | 6.06%   |
| 14     | 3         | 2.27%   |
| 12     | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 79.7%   |
| 1      | 27        | 20.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 90.15%  |
| 32-bit         | 8         | 6.06%   |
| Unknown        | 5         | 3.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 19.4%   |
| 0x806e9    | 9         | 6.72%   |
| 0x206a7    | 9         | 6.72%   |
| 0x806ea    | 6         | 4.48%   |
| 0x806c1    | 6         | 4.48%   |
| 0x506c9    | 5         | 3.73%   |
| 0x906ea    | 4         | 2.99%   |
| 0x406e3    | 4         | 2.99%   |
| 0x40651    | 4         | 2.99%   |
| 0x306a9    | 4         | 2.99%   |
| 0x106c2    | 4         | 2.99%   |
| 0xa0652    | 3         | 2.24%   |
| 0x806ec    | 3         | 2.24%   |
| 0x806eb    | 3         | 2.24%   |
| 0x706e5    | 3         | 2.24%   |
| 0x20655    | 3         | 2.24%   |
| 0x1067a    | 3         | 2.24%   |
| 0x08600104 | 3         | 2.24%   |
| 0x08108102 | 3         | 2.24%   |
| 0x906e9    | 2         | 1.49%   |
| 0x906a3    | 2         | 1.49%   |
| 0x806d1    | 2         | 1.49%   |
| 0x6fd      | 2         | 1.49%   |
| 0x66a      | 2         | 1.49%   |
| 0x306c3    | 2         | 1.49%   |
| 0x0a50000c | 2         | 1.49%   |
| 0x0a50000b | 2         | 1.49%   |
| 0x08600106 | 2         | 1.49%   |
| 0x08600103 | 2         | 1.49%   |
| 0x706a8    | 1         | 0.75%   |
| 0x706a1    | 1         | 0.75%   |
| 0x6fb      | 1         | 0.75%   |
| 0x6d6      | 1         | 0.75%   |
| 0x506e3    | 1         | 0.75%   |
| 0x306d4    | 1         | 0.75%   |
| 0x30678    | 1         | 0.75%   |
| 0x20652    | 1         | 0.75%   |
| 0x08701013 | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 21.97%  |
| SandyBridge      | 12        | 9.09%   |
| Zen 2            | 10        | 7.58%   |
| TigerLake        | 9         | 6.82%   |
| Haswell          | 8         | 6.06%   |
| IvyBridge        | 7         | 5.3%    |
| Skylake          | 6         | 4.55%   |
| IceLake          | 6         | 4.55%   |
| Unknown          | 6         | 4.55%   |
| Zen 3            | 5         | 3.79%   |
| Goldmont         | 5         | 3.79%   |
| Westmere         | 4         | 3.03%   |
| Penryn           | 4         | 3.03%   |
| CometLake        | 4         | 3.03%   |
| Bonnell          | 4         | 3.03%   |
| Zen+             | 3         | 2.27%   |
| Core             | 3         | 2.27%   |
| Goldmont plus    | 2         | 1.52%   |
| Broadwell        | 2         | 1.52%   |
| Silvermont       | 1         | 0.76%   |
| P6               | 1         | 0.76%   |
| Alderlake Hybrid | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 104       | 60.82%  |
| Nvidia      | 41        | 23.98%  |
| AMD         | 23        | 13.45%  |
| Neomagic    | 2         | 1.17%   |
| S3 Graphics | 1         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 12        | 6.82%   |
| AMD Renoir                                                                    | 8         | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 3.98%   |
| Intel UHD Graphics 620                                                        | 6         | 3.41%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 3.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 2.84%   |
| Intel HD Graphics 500                                                         | 5         | 2.84%   |
| AMD Cezanne                                                                   | 5         | 2.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 2.27%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 4         | 2.27%   |
| Intel HD Graphics 620                                                         | 4         | 2.27%   |
| Intel HD Graphics 615                                                         | 4         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 2.27%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 3         | 1.7%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 3         | 1.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 1.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 1.7%    |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 1.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.7%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 3         | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 1.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 1.14%   |
| Nvidia GP108M [GeForce MX150]                                                 | 2         | 1.14%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 2         | 1.14%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 1.14%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 1.14%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 1.14%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 1.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.14%   |
| Intel HD Graphics 5500                                                        | 2         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.14%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 1.14%   |
| S3 Graphics Chrome 430 ULP / 435 ULP / 440 GTX                                | 1         | 0.57%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 0.57%   |
| Nvidia TU117M                                                                 | 1         | 0.57%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.57%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 1         | 0.57%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 0.57%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.57%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 0.57%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.57%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.57%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.57%   |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.57%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 1         | 0.57%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 0.57%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 0.57%   |
| Nvidia GM108M [GeForce 930MX]                                                 | 1         | 0.57%   |
| Nvidia GM108M [GeForce 920MX]                                                 | 1         | 0.57%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.57%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 0.57%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 0.57%   |
| Nvidia GK107GLM [Quadro K1000M]                                               | 1         | 0.57%   |
| Nvidia GF119M [GeForce 410M]                                                  | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 74        | 56.06%  |
| Intel + Nvidia  | 25        | 18.94%  |
| 1 x AMD         | 10        | 7.58%   |
| AMD + Nvidia    | 8         | 6.06%   |
| 1 x Nvidia      | 7         | 5.3%    |
| Intel + AMD     | 5         | 3.79%   |
| 1 x Neomagic    | 2         | 1.52%   |
| 1 x S3 Graphics | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 106       | 80.3%   |
| Proprietary | 20        | 15.15%  |
| Unknown     | 6         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 66.17%  |
| 1.01-2.0   | 14        | 10.53%  |
| 0.01-0.5   | 11        | 8.27%   |
| 3.01-4.0   | 6         | 4.51%   |
| 5.01-6.0   | 5         | 3.76%   |
| 0.51-1.0   | 5         | 3.76%   |
| 7.01-8.0   | 4         | 3.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 27        | 19.15%  |
| AU Optronics            | 21        | 14.89%  |
| LG Display              | 20        | 14.18%  |
| Chimei Innolux          | 15        | 10.64%  |
| Samsung Electronics     | 9         | 6.38%   |
| Sharp                   | 8         | 5.67%   |
| Dell                    | 6         | 4.26%   |
| AOC                     | 4         | 2.84%   |
| Apple                   | 3         | 2.13%   |
| Philips                 | 2         | 1.42%   |
| LG Philips              | 2         | 1.42%   |
| Lenovo                  | 2         | 1.42%   |
| CPT                     | 2         | 1.42%   |
| Chi Mei Optoelectronics | 2         | 1.42%   |
| Unknown (DAE)           | 1         | 0.71%   |
| TMX                     | 1         | 0.71%   |
| Sony                    | 1         | 0.71%   |
| RGT                     | 1         | 0.71%   |
| PANDA                   | 1         | 0.71%   |
| MStar                   | 1         | 0.71%   |
| Mi                      | 1         | 0.71%   |
| Lenovo Group Limited    | 1         | 0.71%   |
| JXC                     | 1         | 0.71%   |
| ITE                     | 1         | 0.71%   |
| IPS                     | 1         | 0.71%   |
| InnoLux Display         | 1         | 0.71%   |
| InfoVision              | 1         | 0.71%   |
| Hewlett-Packard         | 1         | 0.71%   |
| Goldstar                | 1         | 0.71%   |
| CSO                     | 1         | 0.71%   |
| Ancor Communications    | 1         | 0.71%   |
| Acer                    | 1         | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 2.11%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.11%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 1.41%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 1.41%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 1.41%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.41%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 1.41%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 2         | 1.41%   |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.7%    |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.7%    |
| Sony BW8 MS_9001 1200x1920                                            | 1         | 0.7%    |
| Sharp LQ133M1JW48 SHP14F5 1920x1080 294x165mm 13.3-inch               | 1         | 0.7%    |
| Sharp LQ133M1JW35 SHP14B0 1920x1080 294x165mm 13.3-inch               | 1         | 0.7%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.7%    |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.7%    |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                 | 1         | 0.7%    |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 1         | 0.7%    |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 1         | 0.7%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 1         | 0.7%    |
| Mi Monitor XMI23C2 1920x1080 530x290mm 23.8-inch                      | 1         | 0.7%    |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.7%    |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD06A5 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD04B8 1366x768 344x194mm 15.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 1         | 0.7%    |
| Lenovo LEN LS2023wC LEN0EC2 1600x900 440x250mm 19.9-inch              | 1         | 0.7%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch               | 1         | 0.7%    |
| Lenovo Group Limited LCD Monitor                                      | 1         | 0.7%    |
| JXC JXC3221 JXC3200 3840x2160 697x392mm 31.5-inch                     | 1         | 0.7%    |
| ITE RP-WIFI ITE9320 2560x1440 1600x900mm 72.3-inch                    | 1         | 0.7%    |
| IPS SONGREN 240E IPS2380 2560x1440 452x254mm 20.4-inch                | 1         | 0.7%    |
| InnoLux Display LCD Monitor CMI0023 1366x768 309x174mm 14.0-inch      | 1         | 0.7%    |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 1         | 0.7%    |
| Hewlett-Packard 22w HPN3430 1920x1080 476x268mm 21.5-inch             | 1         | 0.7%    |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch              | 1         | 0.7%    |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 63        | 48.09%  |
| 1366x768 (WXGA)   | 20        | 15.27%  |
| 3840x2160 (4K)    | 8         | 6.11%   |
| 1600x900 (HD+)    | 6         | 4.58%   |
| 1280x800 (WXGA)   | 5         | 3.82%   |
| 2560x1440 (QHD)   | 4         | 3.05%   |
| 2880x1800         | 3         | 2.29%   |
| 3840x2400         | 2         | 1.53%   |
| 3440x1440         | 2         | 1.53%   |
| 2560x1600         | 2         | 1.53%   |
| 1440x900 (WXGA+)  | 2         | 1.53%   |
| 3840x1600         | 1         | 0.76%   |
| 3520x1080         | 1         | 0.76%   |
| 3456x2160         | 1         | 0.76%   |
| 3200x2000         | 1         | 0.76%   |
| 3200x1800 (QHD+)  | 1         | 0.76%   |
| 2880x1920         | 1         | 0.76%   |
| 2400x1600         | 1         | 0.76%   |
| 2304x1440         | 1         | 0.76%   |
| 2256x1504         | 1         | 0.76%   |
| 2160x1440         | 1         | 0.76%   |
| 1920x1200 (WUXGA) | 1         | 0.76%   |
| 1024x600          | 1         | 0.76%   |
| 1024x576          | 1         | 0.76%   |
| Unknown           | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 46        | 32.86%  |
| 13      | 26        | 18.57%  |
| 14      | 21        | 15%     |
| 12      | 9         | 6.43%   |
| 21      | 6         | 4.29%   |
| 23      | 4         | 2.86%   |
| 17      | 4         | 2.86%   |
| 31      | 3         | 2.14%   |
| 24      | 3         | 2.14%   |
| 10      | 3         | 2.14%   |
| Unknown | 3         | 2.14%   |
| 34      | 2         | 1.43%   |
| 27      | 2         | 1.43%   |
| 19      | 2         | 1.43%   |
| 72      | 1         | 0.71%   |
| 52      | 1         | 0.71%   |
| 37      | 1         | 0.71%   |
| 16      | 1         | 0.71%   |
| 11      | 1         | 0.71%   |
| 8       | 1         | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 55.4%   |
| 201-300     | 29        | 20.86%  |
| 501-600     | 9         | 6.47%   |
| 401-500     | 7         | 5.04%   |
| 351-400     | 5         | 3.6%    |
| 601-700     | 3         | 2.16%   |
| Unknown     | 3         | 2.16%   |
| 701-800     | 2         | 1.44%   |
| 801-900     | 1         | 0.72%   |
| 1501-2000   | 1         | 0.72%   |
| 101-200     | 1         | 0.72%   |
| 1001-1500   | 1         | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 99        | 79.2%   |
| 16/10   | 17        | 13.6%   |
| 3/2     | 4         | 3.2%    |
| 21/9    | 3         | 2.4%    |
| 0.62    | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 32.62%  |
| 81-90          | 33        | 23.4%   |
| 71-80          | 15        | 10.64%  |
| 201-250        | 11        | 7.8%    |
| 61-70          | 8         | 5.67%   |
| 351-500        | 6         | 4.26%   |
| 121-130        | 4         | 2.84%   |
| 41-50          | 3         | 2.13%   |
| 151-200        | 3         | 2.13%   |
| Unknown        | 3         | 2.13%   |
| More than 1000 | 2         | 1.42%   |
| 301-350        | 2         | 1.42%   |
| 51-60          | 1         | 0.71%   |
| 1-40           | 1         | 0.71%   |
| 251-300        | 1         | 0.71%   |
| 111-120        | 1         | 0.71%   |
| 91-100         | 1         | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 58        | 42.03%  |
| 101-120       | 28        | 20.29%  |
| 161-240       | 18        | 13.04%  |
| More than 240 | 14        | 10.14%  |
| 51-100        | 14        | 10.14%  |
| 1-50          | 3         | 2.17%   |
| Unknown       | 3         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 105       | 78.95%  |
| 2     | 21        | 15.79%  |
| 0     | 6         | 4.51%   |
| 3     | 1         | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 79        | 40.31%  |
| Realtek Semiconductor    | 57        | 29.08%  |
| Qualcomm Atheros         | 22        | 11.22%  |
| Broadcom                 | 10        | 5.1%    |
| MediaTek                 | 6         | 3.06%   |
| Ralink Technology        | 4         | 2.04%   |
| Marvell Technology Group | 3         | 1.53%   |
| ASIX Electronics         | 3         | 1.53%   |
| Qualcomm                 | 2         | 1.02%   |
| Broadcom Limited         | 2         | 1.02%   |
| Xiaomi                   | 1         | 0.51%   |
| Texas Instruments        | 1         | 0.51%   |
| SEGGER                   | 1         | 0.51%   |
| Ralink                   | 1         | 0.51%   |
| OPPO Electronics         | 1         | 0.51%   |
| Lenovo                   | 1         | 0.51%   |
| Fitbit                   | 1         | 0.51%   |
| DisplayLink              | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 32        | 13.39%  |
| Intel Wi-Fi 6 AX200                                                                           | 13        | 5.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 8         | 3.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 7         | 2.93%   |
| Intel Wireless 8265 / 8275                                                                    | 7         | 2.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6         | 2.51%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 5         | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 5         | 2.09%   |
| Intel Wireless 7265                                                                           | 5         | 2.09%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 2.09%   |
| Intel Ethernet Connection (4) I219-V                                                          | 5         | 2.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 5         | 2.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 4         | 1.67%   |
| Intel Wireless 8260                                                                           | 4         | 1.67%   |
| Intel Wireless 7260                                                                           | 4         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.26%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 3         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 3         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 1.26%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 1.26%   |
| Intel 82579V Gigabit Network Connection                                                       | 3         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                                                      | 3         | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.84%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 2         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 0.84%   |
| Qualcomm QCA6390 Wireless Network Adapter                                                     | 2         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 0.84%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 0.84%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 2         | 0.84%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1         | 0.42%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                                           | 1         | 0.42%   |
| SEGGER J-Link Pro OB                                                                          | 1         | 0.42%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.42%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                        | 1         | 0.42%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                                     | 1         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.42%   |
| Realtek Realtek Network controller                                                            | 1         | 0.42%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                        | 1         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1         | 0.42%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 54.74%  |
| Qualcomm Atheros      | 20        | 14.6%   |
| Realtek Semiconductor | 18        | 13.14%  |
| Broadcom              | 9         | 6.57%   |
| MediaTek              | 6         | 4.38%   |
| Ralink Technology     | 4         | 2.92%   |
| Qualcomm              | 2         | 1.46%   |
| Texas Instruments     | 1         | 0.73%   |
| Ralink                | 1         | 0.73%   |
| Broadcom Limited      | 1         | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 13        | 9.42%   |
| Intel Wireless 8265 / 8275                                                                    | 7         | 5.07%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 5         | 3.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 5         | 3.62%   |
| Intel Wireless 7265                                                                           | 5         | 3.62%   |
| Intel Wi-Fi 6 AX201                                                                           | 5         | 3.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 5         | 3.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 4         | 2.9%    |
| Intel Wireless 8260                                                                           | 4         | 2.9%    |
| Intel Wireless 7260                                                                           | 4         | 2.9%    |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4         | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 2.17%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 2.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 3         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 3         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 2.17%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 2.17%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.45%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 2         | 1.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.45%   |
| Qualcomm QCA6390 Wireless Network Adapter                                                     | 2         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2         | 1.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 1.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.45%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 2         | 1.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 1.45%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                                           | 1         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.72%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                        | 1         | 0.72%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                                     | 1         | 0.72%   |
| Realtek Realtek Network controller                                                            | 1         | 0.72%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.72%   |
| MediaTek WLAN controller                                                                      | 1         | 0.72%   |
| MediaTek 802.11 n WLAN                                                                        | 1         | 0.72%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.72%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 0.72%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                                     | 1         | 0.72%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 1         | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 0.72%   |
| Intel Centrino Wireless-N 2200                                                                | 1         | 0.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 0.72%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                                 | 1         | 0.72%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                                               | 1         | 0.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 48.98%  |
| Intel                    | 32        | 32.65%  |
| Qualcomm Atheros         | 5         | 5.1%    |
| Marvell Technology Group | 3         | 3.06%   |
| ASIX Electronics         | 3         | 3.06%   |
| Broadcom                 | 2         | 2.04%   |
| Xiaomi                   | 1         | 1.02%   |
| OPPO Electronics         | 1         | 1.02%   |
| Lenovo                   | 1         | 1.02%   |
| DisplayLink              | 1         | 1.02%   |
| Broadcom Limited         | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 32.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 8.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 7.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6.06%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 5.05%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 3.03%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 3.03%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.01%   |
| Realtek USB 10/100 LAN                                            | 1         | 1.01%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.01%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 1         | 1.01%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.01%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.01%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.01%   |
| Lenovo Thinkpad LAN                                               | 1         | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.01%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.01%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.01%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.01%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.01%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.01%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.01%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.01%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 1.01%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.01%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.01%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.01%   |
| ASIX AX88772B                                                     | 1         | 1.01%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 57.96%  |
| Ethernet | 93        | 41.15%  |
| Modem    | 2         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 81.82%  |
| Ethernet | 26        | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 80        | 60.61%  |
| 1     | 46        | 34.85%  |
| 0     | 6         | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 132       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 57.43%  |
| Foxconn / Hon Hai               | 6         | 5.94%   |
| Broadcom                        | 6         | 5.94%   |
| Qualcomm Atheros Communications | 5         | 4.95%   |
| Realtek Semiconductor           | 4         | 3.96%   |
| Lite-On Technology              | 4         | 3.96%   |
| IMC Networks                    | 3         | 2.97%   |
| Hewlett-Packard                 | 3         | 2.97%   |
| Realtek                         | 2         | 1.98%   |
| Foxconn International           | 2         | 1.98%   |
| Dell                            | 2         | 1.98%   |
| Apple                           | 2         | 1.98%   |
| Taiyo Yuden                     | 1         | 0.99%   |
| Fujitsu                         | 1         | 0.99%   |
| Cambridge Silicon Radio         | 1         | 0.99%   |
| Askey Computer                  | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 17.82%  |
| Intel AX201 Bluetooth                               | 14        | 13.86%  |
| Intel AX200 Bluetooth                               | 13        | 12.87%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 9.9%    |
| Realtek Bluetooth Radio                             | 4         | 3.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.96%   |
| Intel Bluetooth Device                              | 3         | 2.97%   |
| IMC Networks Wireless_Device                        | 3         | 2.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 2.97%   |
| Realtek Bluetooth Radio                             | 2         | 1.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.98%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.98%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.98%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.98%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.98%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.99%   |
| Lite-On Bluetooth Radio                             | 1         | 0.99%   |
| Lite-On Bluetooth Device                            | 1         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.99%   |
| Fujitsu Bluetooth Device                            | 1         | 0.99%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.99%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.99%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.99%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.99%   |
| Broadcom BCM2045A0                                  | 1         | 0.99%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.99%   |
| Askey Bluetooth Device                              | 1         | 0.99%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.99%   |
| Apple Bluetooth Host Controller                     | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 108       | 68.35%  |
| Nvidia                      | 21        | 13.29%  |
| AMD                         | 20        | 12.66%  |
| Generalplus Technology      | 2         | 1.27%   |
| ESS Technology              | 2         | 1.27%   |
| VIA Technologies            | 1         | 0.63%   |
| Logitech                    | 1         | 0.63%   |
| iCreate Technologies        | 1         | 0.63%   |
| FiiO Electronics Technology | 1         | 0.63%   |
| BY EDIFIER                  | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 10.99%  |
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 9.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 6.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 5.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 4.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 2.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 2.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 2.2%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.2%    |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.2%    |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.1%    |
| Nvidia Audio device                                                        | 2         | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.1%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.1%    |
| Intel CM238 HD Audio Controller                                            | 2         | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.1%    |
| Generalplus Technology USB Audio Device                                    | 2         | 1.1%    |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 1.1%    |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 0.55%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.55%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.55%   |
| Logitech USB Headset H540                                                  | 1         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.55%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 0.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.55%   |
| iCreate Technologies Xonar U7 Echelon Ed.                                  | 1         | 0.55%   |
| FiiO Electronics Technology Exynos                                         | 1         | 0.55%   |
| BY EDIFIER EDIFIER G2 II GAMING HEADSET                                    | 1         | 0.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.55%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 0.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 30        | 32.61%  |
| Samsung Electronics | 21        | 22.83%  |
| Unknown             | 12        | 13.04%  |
| Micron Technology   | 10        | 10.87%  |
| Kingston            | 5         | 5.43%   |
| Unknown             | 5         | 5.43%   |
| Crucial             | 3         | 3.26%   |
| Unknown (ABCD)      | 2         | 2.17%   |
| Team                | 1         | 1.09%   |
| Lenovo              | 1         | 1.09%   |
| Kingmax             | 1         | 1.09%   |
| A-DATA Technology   | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 5         | 5.26%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 4.21%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 3.16%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 2         | 2.11%   |
| Unknown RAM Module 256MB SODIMM DRAM                                | 2         | 2.11%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s      | 2         | 2.11%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                        | 2         | 2.11%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 2.11%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 2.11%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 2.11%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 2.11%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 2         | 2.11%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.11%   |
| Unknown RAM Module 512MB SODIMM DRAM                                | 1         | 1.05%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                          | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR                                   | 1         | 1.05%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.05%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 1.05%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                       | 1         | 1.05%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 1.05%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMAA4GS7AJR8N-WM 32GB SODIMM DDR4 2933MT/s             | 1         | 1.05%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 1.05%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.05%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16384MB SODIMM DDR4 2400MT/s          | 1         | 1.05%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 1         | 1.05%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 1.05%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.05%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.05%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB SODIMM LPDDR4 4266MT/s          | 1         | 1.05%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.05%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.05%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s    | 1         | 1.05%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4096MB 1867MT/s                     | 1         | 1.05%   |
| SK hynix RAM D471A1K43CB1-CTD 8GB SODIMM DDR4 2400MT/s              | 1         | 1.05%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s              | 1         | 1.05%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s              | 1         | 1.05%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.05%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1867MT/s                 | 1         | 1.05%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 1.05%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.05%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.05%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.05%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM 4800MT/s                  | 1         | 1.05%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s        | 1         | 1.05%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips 6400MT/s           | 1         | 1.05%   |
| Micron RAM Module 4GB SODIMM LPDDR3 1867MT/s                        | 1         | 1.05%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 1         | 1.05%   |
| Micron RAM 8KTF51264HDZ-1G9E1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| Micron RAM 8JTF25664JHZ-1G6M2 2048MB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 42.67%  |
| DDR3    | 13        | 17.33%  |
| LPDDR3  | 8         | 10.67%  |
| LPDDR4  | 7         | 9.33%   |
| DDR2    | 5         | 6.67%   |
| Unknown | 4         | 5.33%   |
| DRAM    | 3         | 4%      |
| SDRAM   | 2         | 2.67%   |
| DDR     | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 72.97%  |
| Row Of Chips | 15        | 20.27%  |
| DIMM         | 4         | 5.41%   |
| Unknown      | 1         | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 30        | 35.29%  |
| 4096  | 20        | 23.53%  |
| 2048  | 11        | 12.94%  |
| 32768 | 8         | 9.41%   |
| 16384 | 7         | 8.24%   |
| 1024  | 3         | 3.53%   |
| 256   | 2         | 2.35%   |
| 64    | 2         | 2.35%   |
| 512   | 1         | 1.18%   |
| 232   | 1         | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 14        | 17.72%  |
| 2667    | 14        | 17.72%  |
| 1600    | 13        | 16.46%  |
| 2400    | 6         | 7.59%   |
| Unknown | 6         | 7.59%   |
| 2133    | 5         | 6.33%   |
| 1867    | 5         | 6.33%   |
| 4267    | 3         | 3.8%    |
| 667     | 2         | 2.53%   |
| 533     | 2         | 2.53%   |
| 6400    | 1         | 1.27%   |
| 4800    | 1         | 1.27%   |
| 4266    | 1         | 1.27%   |
| 3733    | 1         | 1.27%   |
| 3266    | 1         | 1.27%   |
| 2933    | 1         | 1.27%   |
| 1334    | 1         | 1.27%   |
| 975     | 1         | 1.27%   |
| 333     | 1         | 1.27%   |

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
| Chicony Electronics                    | 25        | 23.15%  |
| IMC Networks                           | 11        | 10.19%  |
| Acer                                   | 11        | 10.19%  |
| Microdia                               | 9         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 6.48%   |
| Realtek Semiconductor                  | 6         | 5.56%   |
| Sunplus Innovation Technology          | 4         | 3.7%    |
| Syntek                                 | 3         | 2.78%   |
| Silicon Motion                         | 3         | 2.78%   |
| Quanta                                 | 3         | 2.78%   |
| Luxvisions Innotech Limited            | 3         | 2.78%   |
| Apple                                  | 3         | 2.78%   |
| Alcor Micro                            | 3         | 2.78%   |
| Suyin                                  | 2         | 1.85%   |
| Lite-On Technology                     | 2         | 1.85%   |
| Importek                               | 2         | 1.85%   |
| DJJHNA29IE70D3                         | 2         | 1.85%   |
| WaveRider Communications               | 1         | 0.93%   |
| Sonix Technology                       | 1         | 0.93%   |
| Ricoh                                  | 1         | 0.93%   |
| Primax Electronics                     | 1         | 0.93%   |
| Nebraska Furniture Mart                | 1         | 0.93%   |
| Microsoft                              | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| lihappe8                               | 1         | 0.93%   |
| Genesys Logic                          | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                         | 7         | 6.42%   |
| Chicony Integrated Camera                                             | 6         | 5.5%    |
| IMC Networks USB2.0 HD UVC WebCam                                     | 5         | 4.59%   |
| Chicony FJ Camera                                                     | 5         | 4.59%   |
| IMC Networks Integrated Camera                                        | 4         | 3.67%   |
| Chicony HD Webcam                                                     | 4         | 3.67%   |
| Syntek Integrated Camera                                              | 3         | 2.75%   |
| Alcor Micro USB 2.0 PC cam                                            | 3         | 2.75%   |
| Acer Integrated Camera                                                | 3         | 2.75%   |
| Realtek Integrated_Webcam_HD                                          | 2         | 1.83%   |
| Lite-On Integrated Camera                                             | 2         | 1.83%   |
| Importek FJ Camera                                                    | 2         | 1.83%   |
| DJJHNA29IE70D3 HP HD Camera                                           | 2         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera       | 2         | 1.83%   |
| Acer SunplusIT Integrated Camera                                      | 2         | 1.83%   |
| Acer Lenovo EasyCamera                                                | 2         | 1.83%   |
| WaveRider USB 2.0 Camera                                              | 1         | 0.92%   |
| Suyin HP TrueVision HD Integrated Webcam                              | 1         | 0.92%   |
| Suyin HP Truevision HD                                                | 1         | 0.92%   |
| Sunplus USB Camera                                                    | 1         | 0.92%   |
| Sunplus Integrated_Webcam_HD                                          | 1         | 0.92%   |
| Sunplus HP Universal Camera                                           | 1         | 0.92%   |
| Sunplus HD WebCam                                                     | 1         | 0.92%   |
| Sonix USB2.0 HD UVC WebCam                                            | 1         | 0.92%   |
| Silicon Motion Lenovo EasyCamera                                      | 1         | 0.92%   |
| Silicon Motion 720p HD Camera                                         | 1         | 0.92%   |
| Silicon Motion 300k Pixel Camera                                      | 1         | 0.92%   |
| Ricoh USB2.0 Camera                                                   | 1         | 0.92%   |
| Realtek WebCamera                                                     | 1         | 0.92%   |
| Realtek USB2.0 HD UVC WebCam                                          | 1         | 0.92%   |
| Realtek Lenovo easy camera                                            | 1         | 0.92%   |
| Realtek Integrated Webcam_HD                                          | 1         | 0.92%   |
| Quanta USB Webcam                                                     | 1         | 0.92%   |
| Quanta hm1091_techfront                                               | 1         | 0.92%   |
| Quanta HD User Facing                                                 | 1         | 0.92%   |
| Primax Dell Laptop Integrated Webcam 2Mpix                            | 1         | 0.92%   |
| Nebraska Furniture Mart USB 2.0 PC cam                                | 1         | 0.92%   |
| Microsoft LifeCam Cinema                                              | 1         | 0.92%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 0.92%   |
| Microdia Dell Integrated HD Webcam                                    | 1         | 0.92%   |
| Luxvisions Innotech Limited Integrated RGB Camera                     | 1         | 0.92%   |
| Luxvisions Innotech Limited Integrated Camera                         | 1         | 0.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                   | 1         | 0.92%   |
| Logitech Fujitsu Webcam                                               | 1         | 0.92%   |
| lihappe8 USB 2.0 Camera                                               | 1         | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 1         | 0.92%   |
| IMC Networks Lenovo EasyCamera                                        | 1         | 0.92%   |
| Genesys Logic Camera                                                  | 1         | 0.92%   |
| Chicony VGA WebCam                                                    | 1         | 0.92%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 1         | 0.92%   |
| Chicony USB 2.0 Webcam Device                                         | 1         | 0.92%   |
| Chicony Lenovo Integrated Camera (0.3MP)                              | 1         | 0.92%   |
| Chicony Lenovo EasyCamera                                             | 1         | 0.92%   |
| Chicony Integrated Camera [ThinkPad]                                  | 1         | 0.92%   |
| Chicony Integrated Camera (1280x720@30)                               | 1         | 0.92%   |
| Chicony HP Webcam [2 MP Macro]                                        | 1         | 0.92%   |
| Chicony Fujitsu Integrated Camera                                     | 1         | 0.92%   |
| Chicony CNF8031                                                       | 1         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi Webcam                  | 1         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                   | 1         | 0.92%   |

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
| 0     | 79        | 58.52%  |
| 1     | 43        | 31.85%  |
| 2     | 9         | 6.67%   |
| 3     | 2         | 1.48%   |
| 5     | 1         | 0.74%   |
| 4     | 1         | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 30.67%  |
| Graphics card            | 19        | 25.33%  |
| Chipcard                 | 10        | 13.33%  |
| Multimedia controller    | 7         | 9.33%   |
| Net/wireless             | 6         | 8%      |
| Communication controller | 3         | 4%      |
| Bluetooth                | 2         | 2.67%   |
| Storage                  | 1         | 1.33%   |
| Sound                    | 1         | 1.33%   |
| Net/ethernet             | 1         | 1.33%   |
| Card reader              | 1         | 1.33%   |
| Camera                   | 1         | 1.33%   |

