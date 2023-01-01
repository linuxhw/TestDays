Linux in Germany - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

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

Total: 12594

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | NBLK-WAX9X                  | [2391058f73](https://linux-hardware.org/?probe=2391058f73) | Jan 01, 2023 |
| Lenovo        | ThinkPad T410 2537DH6       | [23c0cbbe94](https://linux-hardware.org/?probe=23c0cbbe94) | Dec 31, 2022 |
| Lenovo        | G500 20236                  | [75f2e6fae1](https://linux-hardware.org/?probe=75f2e6fae1) | Dec 31, 2022 |
| Lenovo        | G500 20236                  | [0d3ed20685](https://linux-hardware.org/?probe=0d3ed20685) | Dec 31, 2022 |
| ASUSTek       | UX31E                       | [58391b15a5](https://linux-hardware.org/?probe=58391b15a5) | Dec 31, 2022 |
| HP            | Laptop 15-db0xxx            | [375dccca30](https://linux-hardware.org/?probe=375dccca30) | Dec 31, 2022 |
| Fujitsu       | LIFEBOOK U772               | [3ecdad230a](https://linux-hardware.org/?probe=3ecdad230a) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [ce5baca257](https://linux-hardware.org/?probe=ce5baca257) | Dec 31, 2022 |
| ASUSTek       | X550VXK                     | [b8cd38522a](https://linux-hardware.org/?probe=b8cd38522a) | Dec 31, 2022 |
| Valve         | Jupiter                     | [1922673e86](https://linux-hardware.org/?probe=1922673e86) | Dec 31, 2022 |
| Valve         | Jupiter                     | [b5b95e62a1](https://linux-hardware.org/?probe=b5b95e62a1) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [62b14864e1](https://linux-hardware.org/?probe=62b14864e1) | Dec 30, 2022 |
| Acer          | Aspire 8943G                | [dd6e590470](https://linux-hardware.org/?probe=dd6e590470) | Dec 30, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| HP            | ProBook 455R G6             | [71c9651ee2](https://linux-hardware.org/?probe=71c9651ee2) | Dec 30, 2022 |
| HP            | EliteBook 830 G5            | [bdd6f3912d](https://linux-hardware.org/?probe=bdd6f3912d) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Lenovo        | G575 4383                   | [7c203c43cc](https://linux-hardware.org/?probe=7c203c43cc) | Dec 30, 2022 |
| Lenovo        | G575 4383                   | [c9656285fc](https://linux-hardware.org/?probe=c9656285fc) | Dec 30, 2022 |
| HP            | Laptop 17-by0xxx            | [0da7f8e1d5](https://linux-hardware.org/?probe=0da7f8e1d5) | Dec 30, 2022 |
| Acer          | Aspire A517-51              | [7ec5b8bb3f](https://linux-hardware.org/?probe=7ec5b8bb3f) | Dec 29, 2022 |
| Medion        | Akoya E6416                 | [ddd9ba1ffc](https://linux-hardware.org/?probe=ddd9ba1ffc) | Dec 29, 2022 |
| Dell          | Latitude E6430              | [8ecaae98d3](https://linux-hardware.org/?probe=8ecaae98d3) | Dec 29, 2022 |
| Samsung       | 935XDB                      | [650bd43eae](https://linux-hardware.org/?probe=650bd43eae) | Dec 29, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Acer          | Aspire A517-51              | [d6e1d87869](https://linux-hardware.org/?probe=d6e1d87869) | Dec 29, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [a14e00ab97](https://linux-hardware.org/?probe=a14e00ab97) | Dec 29, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [00e25b3232](https://linux-hardware.org/?probe=00e25b3232) | Dec 29, 2022 |
| Lenovo        | ThinkPad T500 2089W3A       | [401f529e18](https://linux-hardware.org/?probe=401f529e18) | Dec 29, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [5e094b34a5](https://linux-hardware.org/?probe=5e094b34a5) | Dec 29, 2022 |
| Lenovo        | G50-45 80E3                 | [05070bdc72](https://linux-hardware.org/?probe=05070bdc72) | Dec 29, 2022 |
| TrekStor      | Primebook P14               | [c22676280e](https://linux-hardware.org/?probe=c22676280e) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [1c46a3fdd3](https://linux-hardware.org/?probe=1c46a3fdd3) | Dec 29, 2022 |
| HP            | ZBook 17 G4                 | [86eec5f93c](https://linux-hardware.org/?probe=86eec5f93c) | Dec 29, 2022 |
| Apple         | MacBookAir6,2               | [af9ab4ba4d](https://linux-hardware.org/?probe=af9ab4ba4d) | Dec 29, 2022 |
| HP            | EliteBook 2560p             | [e0c82de440](https://linux-hardware.org/?probe=e0c82de440) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [bbd6e1daf5](https://linux-hardware.org/?probe=bbd6e1daf5) | Dec 29, 2022 |
| Lenovo        | V14-IIL 82C4                | [9b77a1e3f3](https://linux-hardware.org/?probe=9b77a1e3f3) | Dec 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [23fe358945](https://linux-hardware.org/?probe=23fe358945) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [2412713729](https://linux-hardware.org/?probe=2412713729) | Dec 29, 2022 |
| Notebook      | W65_67SZ                    | [cbebefb520](https://linux-hardware.org/?probe=cbebefb520) | Dec 29, 2022 |
| Acer          | Aspire A315-41              | [09c901fe98](https://linux-hardware.org/?probe=09c901fe98) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK P702               | [4734f4370b](https://linux-hardware.org/?probe=4734f4370b) | Dec 28, 2022 |
| Toshiba       | Satellite C870-1C2          | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | EliteBook 820 G2            | [bd56ec4f01](https://linux-hardware.org/?probe=bd56ec4f01) | Dec 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [58825656f9](https://linux-hardware.org/?probe=58825656f9) | Dec 28, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Valve         | Jupiter                     | [a89e87f342](https://linux-hardware.org/?probe=a89e87f342) | Dec 28, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [f5c5147826](https://linux-hardware.org/?probe=f5c5147826) | Dec 28, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [8dfcf5860f](https://linux-hardware.org/?probe=8dfcf5860f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| HP            | EliteBook 850 G6            | [b30d6f1b58](https://linux-hardware.org/?probe=b30d6f1b58) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| HUAWEI        | BOM-WXX9                    | [826a683b58](https://linux-hardware.org/?probe=826a683b58) | Dec 28, 2022 |
| HP            | EliteBook 820 G3            | [3c494dd1eb](https://linux-hardware.org/?probe=3c494dd1eb) | Dec 28, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | [a86fddc0b9](https://linux-hardware.org/?probe=a86fddc0b9) | Dec 28, 2022 |
| Valve         | Jupiter                     | [42288a62eb](https://linux-hardware.org/?probe=42288a62eb) | Dec 27, 2022 |
| Lenovo        | G555 0873                   | [f705d0146a](https://linux-hardware.org/?probe=f705d0146a) | Dec 27, 2022 |
| Valve         | Jupiter                     | [bcdce3240d](https://linux-hardware.org/?probe=bcdce3240d) | Dec 27, 2022 |
| HP            | ZBook 17 G5                 | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| HP            | EliteBook 8440p             | [6674099744](https://linux-hardware.org/?probe=6674099744) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [2c2b5135eb](https://linux-hardware.org/?probe=2c2b5135eb) | Dec 27, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [9409e9bfce](https://linux-hardware.org/?probe=9409e9bfce) | Dec 27, 2022 |
| HP            | 255 15.6 inch G9 Noteboo... | [dc9d334f95](https://linux-hardware.org/?probe=dc9d334f95) | Dec 27, 2022 |
| Dell          | Venue 11 Pro 5130           | [c68cba64e9](https://linux-hardware.org/?probe=c68cba64e9) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a7b2bad562](https://linux-hardware.org/?probe=a7b2bad562) | Dec 27, 2022 |
| Valve         | Jupiter                     | [d244a4aa10](https://linux-hardware.org/?probe=d244a4aa10) | Dec 27, 2022 |
| Samsung       | SP55S                       | [ce8b6d3fdb](https://linux-hardware.org/?probe=ce8b6d3fdb) | Dec 27, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | [7b4305ce5a](https://linux-hardware.org/?probe=7b4305ce5a) | Dec 27, 2022 |
| Samsung       | SP55S                       | [f0d13bbd0d](https://linux-hardware.org/?probe=f0d13bbd0d) | Dec 27, 2022 |
| Medion        | P6640                       | [0787385a0f](https://linux-hardware.org/?probe=0787385a0f) | Dec 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [29a54c4976](https://linux-hardware.org/?probe=29a54c4976) | Dec 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [442fcdba27](https://linux-hardware.org/?probe=442fcdba27) | Dec 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [4ad973e635](https://linux-hardware.org/?probe=4ad973e635) | Dec 26, 2022 |
| ASUSTek       | X751MA                      | [f63581c721](https://linux-hardware.org/?probe=f63581c721) | Dec 26, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [e5463f6249](https://linux-hardware.org/?probe=e5463f6249) | Dec 26, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [4cf226b65c](https://linux-hardware.org/?probe=4cf226b65c) | Dec 26, 2022 |
| Acer          | Aspire A515-51              | [e763dd5dfe](https://linux-hardware.org/?probe=e763dd5dfe) | Dec 26, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8da465a60c](https://linux-hardware.org/?probe=8da465a60c) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [06027a53fb](https://linux-hardware.org/?probe=06027a53fb) | Dec 26, 2022 |
| Toshiba       | Satellite L500              | [08b4f83030](https://linux-hardware.org/?probe=08b4f83030) | Dec 26, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [6e3d39b4ae](https://linux-hardware.org/?probe=6e3d39b4ae) | Dec 25, 2022 |
| Acer          | Swift SF314-51              | [bfdd69d192](https://linux-hardware.org/?probe=bfdd69d192) | Dec 25, 2022 |
| Dell          | XPS 13 7390                 | [9131496b00](https://linux-hardware.org/?probe=9131496b00) | Dec 25, 2022 |
| Toshiba       | Satellite C850-1C8          | [eab4ef74de](https://linux-hardware.org/?probe=eab4ef74de) | Dec 25, 2022 |
| Toshiba       | Satellite C850-1C8          | [1e47b54431](https://linux-hardware.org/?probe=1e47b54431) | Dec 25, 2022 |
| Acer          | Aspire A515-57G             | [2e82fb3f66](https://linux-hardware.org/?probe=2e82fb3f66) | Dec 25, 2022 |
| Valve         | Jupiter                     | [8194c72bb9](https://linux-hardware.org/?probe=8194c72bb9) | Dec 25, 2022 |
| Acer          | Aspire 5739G                | [0d3bd3f3ec](https://linux-hardware.org/?probe=0d3bd3f3ec) | Dec 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [8d2d8be057](https://linux-hardware.org/?probe=8d2d8be057) | Dec 25, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| Valve         | Jupiter                     | [f8ff1f6342](https://linux-hardware.org/?probe=f8ff1f6342) | Dec 25, 2022 |
| Acer          | Aspire ES1-523              | [41211efaae](https://linux-hardware.org/?probe=41211efaae) | Dec 25, 2022 |
| Acer          | Swift SF314-43              | [b1c3a71567](https://linux-hardware.org/?probe=b1c3a71567) | Dec 24, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | [afc91c5da0](https://linux-hardware.org/?probe=afc91c5da0) | Dec 24, 2022 |
| Medion        | E122X                       | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [5e589fb2d1](https://linux-hardware.org/?probe=5e589fb2d1) | Dec 24, 2022 |
| Dell          | Inspiron 3593               | [a640541ee0](https://linux-hardware.org/?probe=a640541ee0) | Dec 24, 2022 |
| Lenovo        | ThinkPad X61s 7667WHE       | [d689ae23a7](https://linux-hardware.org/?probe=d689ae23a7) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Acer          | Aspire A315-53              | [eb42b5e055](https://linux-hardware.org/?probe=eb42b5e055) | Dec 24, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [9e5c4705fa](https://linux-hardware.org/?probe=9e5c4705fa) | Dec 23, 2022 |
| HP            | Pavilion Notebook           | [6f02a1834d](https://linux-hardware.org/?probe=6f02a1834d) | Dec 23, 2022 |
| ASUSTek       | G73Sw                       | [3f4336472e](https://linux-hardware.org/?probe=3f4336472e) | Dec 23, 2022 |
| Acer          | Aspire ES1-523              | [476f9315a1](https://linux-hardware.org/?probe=476f9315a1) | Dec 23, 2022 |
| Timi          | TM1703                      | [5e25655f36](https://linux-hardware.org/?probe=5e25655f36) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [79b015dcea](https://linux-hardware.org/?probe=79b015dcea) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [aeb7addbc3](https://linux-hardware.org/?probe=aeb7addbc3) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [2a0cacc27e](https://linux-hardware.org/?probe=2a0cacc27e) | Dec 23, 2022 |
| Lenovo        | G50-80 80E5                 | [194eee0657](https://linux-hardware.org/?probe=194eee0657) | Dec 22, 2022 |
| Acer          | Aspire ES1-311              | [e5d7bd61f1](https://linux-hardware.org/?probe=e5d7bd61f1) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [341becfd8a](https://linux-hardware.org/?probe=341becfd8a) | Dec 22, 2022 |
| Dell          | Latitude 5280               | [59002e923b](https://linux-hardware.org/?probe=59002e923b) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [9100b276c2](https://linux-hardware.org/?probe=9100b276c2) | Dec 22, 2022 |
| HP            | Pavilion 17                 | [c58baa8506](https://linux-hardware.org/?probe=c58baa8506) | Dec 22, 2022 |
| Acer          | Aspire ES1-523              | [d034bb7c92](https://linux-hardware.org/?probe=d034bb7c92) | Dec 22, 2022 |
| Dell          | Latitude E6430              | [7fe3f11f56](https://linux-hardware.org/?probe=7fe3f11f56) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [e60df2d8ba](https://linux-hardware.org/?probe=e60df2d8ba) | Dec 22, 2022 |
| Acer          | Aspire ES1-523              | [806aa49648](https://linux-hardware.org/?probe=806aa49648) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [54fb90def3](https://linux-hardware.org/?probe=54fb90def3) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [214d584e36](https://linux-hardware.org/?probe=214d584e36) | Dec 21, 2022 |
| Valve         | Jupiter                     | [0bea978cf7](https://linux-hardware.org/?probe=0bea978cf7) | Dec 21, 2022 |
| Samsung       | R540/R580/R780/SA41/E452... | [044928d818](https://linux-hardware.org/?probe=044928d818) | Dec 21, 2022 |
| Acer          | Aspire ES1-523              | [3528a9d40f](https://linux-hardware.org/?probe=3528a9d40f) | Dec 21, 2022 |
| HP            | Stream Notebook PC 13       | [9c88ffc394](https://linux-hardware.org/?probe=9c88ffc394) | Dec 21, 2022 |
| HP            | 255 15.6 inch G9 Noteboo... | [54b5dfbdbb](https://linux-hardware.org/?probe=54b5dfbdbb) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Dell          | G15 5515                    | [e222bc4dfc](https://linux-hardware.org/?probe=e222bc4dfc) | Dec 21, 2022 |
| Lenovo        | ThinkPad X250 20CM001PGE    | [8d98e783c2](https://linux-hardware.org/?probe=8d98e783c2) | Dec 21, 2022 |
| Valve         | Jupiter                     | [9a358caee7](https://linux-hardware.org/?probe=9a358caee7) | Dec 21, 2022 |
| HP            | Falco                       | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| Acer          | TravelMate 3270             | [dd1f31466b](https://linux-hardware.org/?probe=dd1f31466b) | Dec 21, 2022 |
| Dell          | Latitude E6420              | [3244fe3048](https://linux-hardware.org/?probe=3244fe3048) | Dec 20, 2022 |
| Lenovo        | ThinkPad X230 2325AEG       | [5000a7274b](https://linux-hardware.org/?probe=5000a7274b) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [a285792280](https://linux-hardware.org/?probe=a285792280) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [90d1d153a4](https://linux-hardware.org/?probe=90d1d153a4) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | [cd16c6fb41](https://linux-hardware.org/?probe=cd16c6fb41) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [90d4affad3](https://linux-hardware.org/?probe=90d4affad3) | Dec 19, 2022 |
| Fujitsu Si... | LIFEBOOK T5010              | [9f5485a1ed](https://linux-hardware.org/?probe=9f5485a1ed) | Dec 19, 2022 |
| Fujitsu Si... | LIFEBOOK T5010              | [e7fe928198](https://linux-hardware.org/?probe=e7fe928198) | Dec 19, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [81e26c759e](https://linux-hardware.org/?probe=81e26c759e) | Dec 19, 2022 |
| MSI           | MS-1035                     | [6a8a6b7de4](https://linux-hardware.org/?probe=6a8a6b7de4) | Dec 19, 2022 |
| HP            | Pavilion g6                 | [4ffa593ffe](https://linux-hardware.org/?probe=4ffa593ffe) | Dec 19, 2022 |
| HP            | Pavilion g6                 | [ede790ce3c](https://linux-hardware.org/?probe=ede790ce3c) | Dec 19, 2022 |
| ASUSTek       | X555QA                      | [3a7e8867bd](https://linux-hardware.org/?probe=3a7e8867bd) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| HUAWEI        | BOD-WXX9                    | [da35f3ec23](https://linux-hardware.org/?probe=da35f3ec23) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3e4b608419](https://linux-hardware.org/?probe=3e4b608419) | Dec 19, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2347CM9       | [cc1c68fe85](https://linux-hardware.org/?probe=cc1c68fe85) | Dec 19, 2022 |
| Alienware     | x14                         | [d965b3510e](https://linux-hardware.org/?probe=d965b3510e) | Dec 19, 2022 |
| Sony          | VPCF23S1E                   | [4ab362e83b](https://linux-hardware.org/?probe=4ab362e83b) | Dec 19, 2022 |
| Sony          | VPCF23S1E                   | [b62decbb3f](https://linux-hardware.org/?probe=b62decbb3f) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [1489f7e01d](https://linux-hardware.org/?probe=1489f7e01d) | Dec 18, 2022 |
| HP            | 255 15.6 inch G9 Noteboo... | [145cf4199f](https://linux-hardware.org/?probe=145cf4199f) | Dec 18, 2022 |
| HP            | 255 15.6 inch G9 Noteboo... | [ecdb6b63ee](https://linux-hardware.org/?probe=ecdb6b63ee) | Dec 18, 2022 |
| Acer          | Aspire V3-772G              | [706c85a543](https://linux-hardware.org/?probe=706c85a543) | Dec 18, 2022 |
| Lenovo        | Z41-70 80K5                 | [2bf0954d5d](https://linux-hardware.org/?probe=2bf0954d5d) | Dec 18, 2022 |
| Lenovo        | Z41-70 80K5                 | [c37887c710](https://linux-hardware.org/?probe=c37887c710) | Dec 18, 2022 |
| Acer          | Aspire V3-772G              | [038b09e27b](https://linux-hardware.org/?probe=038b09e27b) | Dec 18, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Apple         | MacBookAir5,1               | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| Acer          | Aspire A517-52G             | [225e2eaae8](https://linux-hardware.org/?probe=225e2eaae8) | Dec 18, 2022 |
| Dell          | Latitude E6530              | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| HP            | Notebook                    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | [973cbefa6b](https://linux-hardware.org/?probe=973cbefa6b) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [2d6dff8209](https://linux-hardware.org/?probe=2d6dff8209) | Dec 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PG... | [938c10075a](https://linux-hardware.org/?probe=938c10075a) | Dec 18, 2022 |
| Acer          | Aspire 5739G                | [0cf9fc6ba8](https://linux-hardware.org/?probe=0cf9fc6ba8) | Dec 17, 2022 |
| Acer          | Aspire E1-531               | [633910e332](https://linux-hardware.org/?probe=633910e332) | Dec 17, 2022 |
| Dell          | Latitude 5590               | [83e177278e](https://linux-hardware.org/?probe=83e177278e) | Dec 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [49969f1b81](https://linux-hardware.org/?probe=49969f1b81) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [39de5a5168](https://linux-hardware.org/?probe=39de5a5168) | Dec 17, 2022 |
| Jumper        | EZbook                      | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [f777de4f53](https://linux-hardware.org/?probe=f777de4f53) | Dec 17, 2022 |
| Acer          | Aspire E1-572G              | [adc5196d64](https://linux-hardware.org/?probe=adc5196d64) | Dec 17, 2022 |
| Jumper        | EZbook                      | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| Acer          | Aspire V3-771               | [f8468e696e](https://linux-hardware.org/?probe=f8468e696e) | Dec 17, 2022 |
| Acer          | Aspire V3-771               | [4b9551aa0e](https://linux-hardware.org/?probe=4b9551aa0e) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Acer          | Extensa 7630EZ              | [e17ca259c0](https://linux-hardware.org/?probe=e17ca259c0) | Dec 16, 2022 |
| Dell          | Latitude E7450              | [e5008fde53](https://linux-hardware.org/?probe=e5008fde53) | Dec 16, 2022 |
| Dell          | Precision 5570              | [9468beba51](https://linux-hardware.org/?probe=9468beba51) | Dec 16, 2022 |
| Acer          | Extensa 7630EZ              | [fac3dd4a6c](https://linux-hardware.org/?probe=fac3dd4a6c) | Dec 16, 2022 |
| Lenovo        | ThinkPad T420s 4174NEG      | [85724ffd5a](https://linux-hardware.org/?probe=85724ffd5a) | Dec 16, 2022 |
| HP            | EliteBook 8460p             | [f11100a29e](https://linux-hardware.org/?probe=f11100a29e) | Dec 16, 2022 |
| Toshiba       | Satellite P500              | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Valve         | Jupiter                     | [2014e95862](https://linux-hardware.org/?probe=2014e95862) | Dec 16, 2022 |
| Lenovo        | Yoga 2-11 20332             | [92a038a164](https://linux-hardware.org/?probe=92a038a164) | Dec 16, 2022 |
| Apple         | MacBookPro13,3              | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| Apple         | MacBookPro6,2               | [23aac83ffc](https://linux-hardware.org/?probe=23aac83ffc) | Dec 15, 2022 |
| Apple         | MacBookPro6,2               | [227363d9bd](https://linux-hardware.org/?probe=227363d9bd) | Dec 15, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [4f1aa7401d](https://linux-hardware.org/?probe=4f1aa7401d) | Dec 15, 2022 |
| Dell          | Vostro 3559                 | [7b151443b9](https://linux-hardware.org/?probe=7b151443b9) | Dec 15, 2022 |
| ASUSTek       | X751MA                      | [3655864f08](https://linux-hardware.org/?probe=3655864f08) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7bcd1aa991](https://linux-hardware.org/?probe=7bcd1aa991) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [711364b4dd](https://linux-hardware.org/?probe=711364b4dd) | Dec 15, 2022 |
| ASUSTek       | N71Vn                       | [579adf052e](https://linux-hardware.org/?probe=579adf052e) | Dec 15, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [5d47df0d10](https://linux-hardware.org/?probe=5d47df0d10) | Dec 15, 2022 |
| HUAWEI        | KPL-W0X                     | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Dell          | Precision 7760              | [cbe51e9db3](https://linux-hardware.org/?probe=cbe51e9db3) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [85c38f0af3](https://linux-hardware.org/?probe=85c38f0af3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a8c1f371e5](https://linux-hardware.org/?probe=a8c1f371e5) | Dec 15, 2022 |
| Google        | Cyan                        | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f18b9184ca](https://linux-hardware.org/?probe=f18b9184ca) | Dec 15, 2022 |
| ASUSTek       | K53U                        | [cbbffb5194](https://linux-hardware.org/?probe=cbbffb5194) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [b7d1538f13](https://linux-hardware.org/?probe=b7d1538f13) | Dec 14, 2022 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [37c6f8c548](https://linux-hardware.org/?probe=37c6f8c548) | Dec 14, 2022 |
| ASUSTek       | X751MA                      | [ddd84e9ac8](https://linux-hardware.org/?probe=ddd84e9ac8) | Dec 14, 2022 |
| Valve         | Jupiter                     | [2f2528fad3](https://linux-hardware.org/?probe=2f2528fad3) | Dec 14, 2022 |
| Lenovo        | ThinkPad T530 239237G       | [de24340935](https://linux-hardware.org/?probe=de24340935) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Lenovo        | ThinkPad W541 20EGS06T00    | [2cdb5f249e](https://linux-hardware.org/?probe=2cdb5f249e) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [034b34f6d6](https://linux-hardware.org/?probe=034b34f6d6) | Dec 13, 2022 |
| Unknown       | Unknown                     | [7c8c0bd933](https://linux-hardware.org/?probe=7c8c0bd933) | Dec 13, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [6e2b72eefe](https://linux-hardware.org/?probe=6e2b72eefe) | Dec 13, 2022 |
| Lenovo        | B71-80 80RJ                 | [8369524e4e](https://linux-hardware.org/?probe=8369524e4e) | Dec 13, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5dd8c45fee](https://linux-hardware.org/?probe=5dd8c45fee) | Dec 13, 2022 |
| Dell          | Latitude 5420               | [741ffe2e7d](https://linux-hardware.org/?probe=741ffe2e7d) | Dec 13, 2022 |
| Dynabook      | Satellite Pro C50-H-11D     | [f2f233cc99](https://linux-hardware.org/?probe=f2f233cc99) | Dec 13, 2022 |
| Lenovo        | ThinkPad SL510 2847A72      | [77518bc6c6](https://linux-hardware.org/?probe=77518bc6c6) | Dec 13, 2022 |
| Dell          | Inspiron 13-5368            | [952dd9d819](https://linux-hardware.org/?probe=952dd9d819) | Dec 13, 2022 |
| Dell          | Inspiron 5721               | [4271312a60](https://linux-hardware.org/?probe=4271312a60) | Dec 13, 2022 |
| Dell          | Studio 1747                 | [f2feefe033](https://linux-hardware.org/?probe=f2feefe033) | Dec 13, 2022 |
| HUAWEI        | MDZ-WXX9X                   | [ec151dcc1e](https://linux-hardware.org/?probe=ec151dcc1e) | Dec 12, 2022 |
| MSI           | GP73 Leopard 8RD            | [548de8bdae](https://linux-hardware.org/?probe=548de8bdae) | Dec 12, 2022 |
| Dell          | Latitude 5501               | [1a06a1c5e3](https://linux-hardware.org/?probe=1a06a1c5e3) | Dec 12, 2022 |
| Dell          | Inspiron 3793               | [0aecc9e3c9](https://linux-hardware.org/?probe=0aecc9e3c9) | Dec 12, 2022 |
| Dell          | Latitude 5501               | [bfb65fea9d](https://linux-hardware.org/?probe=bfb65fea9d) | Dec 12, 2022 |
| HP            | EliteBook 8470p             | [352e496f98](https://linux-hardware.org/?probe=352e496f98) | Dec 12, 2022 |
| HP            | 255 G5 Notebook PC          | [3504b137ee](https://linux-hardware.org/?probe=3504b137ee) | Dec 12, 2022 |
| HP            | ProBook 6560b               | [78dfb8c378](https://linux-hardware.org/?probe=78dfb8c378) | Dec 12, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [dba940474a](https://linux-hardware.org/?probe=dba940474a) | Dec 12, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [9fb659eea3](https://linux-hardware.org/?probe=9fb659eea3) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| MSI           | Modern 14 B11MOU            | [9739ffdf34](https://linux-hardware.org/?probe=9739ffdf34) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Valve         | Jupiter                     | [708d1f0ed9](https://linux-hardware.org/?probe=708d1f0ed9) | Dec 11, 2022 |
| Valve         | Jupiter                     | [ce3ee9584d](https://linux-hardware.org/?probe=ce3ee9584d) | Dec 11, 2022 |
| Valve         | Jupiter                     | [0dcaa4653d](https://linux-hardware.org/?probe=0dcaa4653d) | Dec 11, 2022 |
| Lenovo        | ThinkPad P51 20HH0018GE     | [4d5dd8fdc0](https://linux-hardware.org/?probe=4d5dd8fdc0) | Dec 11, 2022 |
| Samsung       | 930X5J/910S5J/940X5J        | [deb721084b](https://linux-hardware.org/?probe=deb721084b) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [c68d83cbe9](https://linux-hardware.org/?probe=c68d83cbe9) | Dec 11, 2022 |
| HP            | Pavilion g7                 | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Acer          | Aspire A315-56              | [aa4c9c448c](https://linux-hardware.org/?probe=aa4c9c448c) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [eaba83d221](https://linux-hardware.org/?probe=eaba83d221) | Dec 11, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [89e7835b90](https://linux-hardware.org/?probe=89e7835b90) | Dec 11, 2022 |
| Wortmann      | 1220569_1470092             | [89700d418b](https://linux-hardware.org/?probe=89700d418b) | Dec 11, 2022 |
| HUAWEI        | HVY-WXX9                    | [6f8c8644e2](https://linux-hardware.org/?probe=6f8c8644e2) | Dec 10, 2022 |
| Sony          | VGN-NR32M_S                 | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X540SA                      | [ac26a0f572](https://linux-hardware.org/?probe=ac26a0f572) | Dec 10, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [4e67196d41](https://linux-hardware.org/?probe=4e67196d41) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [71d6dc33e1](https://linux-hardware.org/?probe=71d6dc33e1) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [8b8b7600f2](https://linux-hardware.org/?probe=8b8b7600f2) | Dec 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [b262201707](https://linux-hardware.org/?probe=b262201707) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [c06e4cdc68](https://linux-hardware.org/?probe=c06e4cdc68) | Dec 10, 2022 |
| ASUSTek       | X540SA                      | [abda33d50f](https://linux-hardware.org/?probe=abda33d50f) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [bec3d9e1e0](https://linux-hardware.org/?probe=bec3d9e1e0) | Dec 10, 2022 |
| Lenovo        | ThinkPad T510 4349WHC       | [290bcc9d81](https://linux-hardware.org/?probe=290bcc9d81) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [040652df3d](https://linux-hardware.org/?probe=040652df3d) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [f02aa7b2d8](https://linux-hardware.org/?probe=f02aa7b2d8) | Dec 10, 2022 |
| ASUSTek       | K75VM                       | [dcf550e3ae](https://linux-hardware.org/?probe=dcf550e3ae) | Dec 10, 2022 |
| ASUSTek       | K75VM                       | [3dd374de1a](https://linux-hardware.org/?probe=3dd374de1a) | Dec 09, 2022 |
| Fujitsu       | LIFEBOOK E752               | [f325091065](https://linux-hardware.org/?probe=f325091065) | Dec 09, 2022 |
| ASUSTek       | X751MA                      | [ecd4e8aded](https://linux-hardware.org/?probe=ecd4e8aded) | Dec 09, 2022 |
| System76      | Oryx Pro                    | [55c305af4f](https://linux-hardware.org/?probe=55c305af4f) | Dec 09, 2022 |
| HP            | ProBook 650 G1              | [46d77ce0b4](https://linux-hardware.org/?probe=46d77ce0b4) | Dec 09, 2022 |
| Schenker      | VIA 15                      | [25883b06a1](https://linux-hardware.org/?probe=25883b06a1) | Dec 09, 2022 |
| MSI           | EX610                       | [389095b190](https://linux-hardware.org/?probe=389095b190) | Dec 09, 2022 |
| Valve         | Jupiter                     | [8a3cf19a14](https://linux-hardware.org/?probe=8a3cf19a14) | Dec 09, 2022 |
| Acer          | Aspire E1-572G              | [2dabd7cf91](https://linux-hardware.org/?probe=2dabd7cf91) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | [adea8bc8d8](https://linux-hardware.org/?probe=adea8bc8d8) | Dec 08, 2022 |
| Notebook      | P65_P67SA                   | [4f79e1d964](https://linux-hardware.org/?probe=4f79e1d964) | Dec 08, 2022 |
| Acer          | Swift SF515-51T             | [6c3140ce31](https://linux-hardware.org/?probe=6c3140ce31) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| Dell          | Inspiron 3593               | [62212b2baa](https://linux-hardware.org/?probe=62212b2baa) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [b0f77fed1f](https://linux-hardware.org/?probe=b0f77fed1f) | Dec 08, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8924598f09](https://linux-hardware.org/?probe=8924598f09) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [e56fd20ec9](https://linux-hardware.org/?probe=e56fd20ec9) | Dec 08, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| HP            | ZBook Fury 17 G7 Mobile ... | [cb45484bb6](https://linux-hardware.org/?probe=cb45484bb6) | Dec 08, 2022 |
| HUAWEI        | MACH-WX9                    | [5ed19862a7](https://linux-hardware.org/?probe=5ed19862a7) | Dec 08, 2022 |
| Lenovo        | ThinkPad T510 4349WHC       | [fd6203739f](https://linux-hardware.org/?probe=fd6203739f) | Dec 08, 2022 |
| Dell          | Vostro 15-3568              | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Dell          | XPS 13 7390                 | [d01478d161](https://linux-hardware.org/?probe=d01478d161) | Dec 07, 2022 |
| Lenovo        | B71-80 80RJ                 | [b08283f242](https://linux-hardware.org/?probe=b08283f242) | Dec 07, 2022 |
| HP            | ZBook 15                    | [316f6e168b](https://linux-hardware.org/?probe=316f6e168b) | Dec 07, 2022 |
| HP            | Pavilion 17                 | [fa9fae08f8](https://linux-hardware.org/?probe=fa9fae08f8) | Dec 07, 2022 |
| HP            | EliteBook 8530p             | [bffa0ab8f4](https://linux-hardware.org/?probe=bffa0ab8f4) | Dec 07, 2022 |
| Dell          | Latitude 5490               | [5ee7cf0137](https://linux-hardware.org/?probe=5ee7cf0137) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349WHC       | [8ddc2eef9c](https://linux-hardware.org/?probe=8ddc2eef9c) | Dec 07, 2022 |
| Lenovo        | ThinkPad X230 2320CTO       | [b74f2893d0](https://linux-hardware.org/?probe=b74f2893d0) | Dec 07, 2022 |
| HP            | 255 G8 Notebook PC          | [020ef58a08](https://linux-hardware.org/?probe=020ef58a08) | Dec 06, 2022 |
| Lenovo        | IdeaPad Y560                | [64abd8c6fe](https://linux-hardware.org/?probe=64abd8c6fe) | Dec 06, 2022 |
| Dell          | Inspiron 3593               | [6fc850bb3e](https://linux-hardware.org/?probe=6fc850bb3e) | Dec 06, 2022 |
| Acer          | Aspire ES1-731              | [8856d29995](https://linux-hardware.org/?probe=8856d29995) | Dec 06, 2022 |
| Packard Be... | EasyNote LJ65               | [1ca8a161fd](https://linux-hardware.org/?probe=1ca8a161fd) | Dec 06, 2022 |
| HP            | EliteBook 8570p             | [056abaad2b](https://linux-hardware.org/?probe=056abaad2b) | Dec 06, 2022 |
| Dell          | G15 5515                    | [63fed6d448](https://linux-hardware.org/?probe=63fed6d448) | Dec 06, 2022 |
| Valve         | Jupiter                     | [6fcb4cb441](https://linux-hardware.org/?probe=6fcb4cb441) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [db1a2c7a74](https://linux-hardware.org/?probe=db1a2c7a74) | Dec 06, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [a3b78e7093](https://linux-hardware.org/?probe=a3b78e7093) | Dec 06, 2022 |
| Dell          | Latitude 14 Rugged (5404... | [7850a16a1b](https://linux-hardware.org/?probe=7850a16a1b) | Dec 06, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [3e1e88ac7a](https://linux-hardware.org/?probe=3e1e88ac7a) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [6ae5470891](https://linux-hardware.org/?probe=6ae5470891) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [03aba4d315](https://linux-hardware.org/?probe=03aba4d315) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Acer          | Swift SF313-52              | [3dfa942513](https://linux-hardware.org/?probe=3dfa942513) | Dec 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [86cd634760](https://linux-hardware.org/?probe=86cd634760) | Dec 06, 2022 |
| Dell          | Latitude E6540              | [20786b000c](https://linux-hardware.org/?probe=20786b000c) | Dec 05, 2022 |
| Medion        | P6640                       | [69564ba63a](https://linux-hardware.org/?probe=69564ba63a) | Dec 05, 2022 |
| Medion        | P6640                       | [b80a41d8e0](https://linux-hardware.org/?probe=b80a41d8e0) | Dec 05, 2022 |
| Lenovo        | ThinkPad L512 2550A19       | [28a7cac896](https://linux-hardware.org/?probe=28a7cac896) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| Lenovo        | ThinkPad T540p 20BE00B5G... | [38e0f031c1](https://linux-hardware.org/?probe=38e0f031c1) | Dec 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [8b5cb6a81d](https://linux-hardware.org/?probe=8b5cb6a81d) | Dec 04, 2022 |
| HP            | Pavilion Notebook           | [df4873cc34](https://linux-hardware.org/?probe=df4873cc34) | Dec 04, 2022 |
| Acer          | TravelMate 5742             | [f4487c6ad5](https://linux-hardware.org/?probe=f4487c6ad5) | Dec 04, 2022 |
| Sony          | VGN-NW31JF_S                | [ebfbfb034a](https://linux-hardware.org/?probe=ebfbfb034a) | Dec 04, 2022 |
| ASUSTek       | X751SA                      | [4d6d15b681](https://linux-hardware.org/?probe=4d6d15b681) | Dec 04, 2022 |
| Medion        | P6624                       | [6410b045a3](https://linux-hardware.org/?probe=6410b045a3) | Dec 04, 2022 |
| Acer          | TravelMate 3270             | [f984264133](https://linux-hardware.org/?probe=f984264133) | Dec 04, 2022 |
| Lenovo        | ThinkPad T540p 20BE00B5G... | [afa5d891bd](https://linux-hardware.org/?probe=afa5d891bd) | Dec 04, 2022 |
| Fujitsu       | LIFEBOOK E544               | [bd465999ee](https://linux-hardware.org/?probe=bd465999ee) | Dec 04, 2022 |
| Dell          | Inspiron 15-5578            | [61f5950e07](https://linux-hardware.org/?probe=61f5950e07) | Dec 03, 2022 |
| Acer          | Aspire 5820TG               | [f1ba906a03](https://linux-hardware.org/?probe=f1ba906a03) | Dec 03, 2022 |
| ASUSTek       | X555QA                      | [677ef3b3f2](https://linux-hardware.org/?probe=677ef3b3f2) | Dec 03, 2022 |
| Acer          | Aspire 5820TG               | [ff1d00ce49](https://linux-hardware.org/?probe=ff1d00ce49) | Dec 03, 2022 |
| ASUSTek       | X751SA                      | [d56875294a](https://linux-hardware.org/?probe=d56875294a) | Dec 03, 2022 |
| SGIN          | laptop                      | [1c676d77ee](https://linux-hardware.org/?probe=1c676d77ee) | Dec 03, 2022 |
| Acer          | Aspire A315-59              | [abc4c3e5c6](https://linux-hardware.org/?probe=abc4c3e5c6) | Dec 03, 2022 |
| HP            | 250 G8 Notebook PC          | [f6bba1c80e](https://linux-hardware.org/?probe=f6bba1c80e) | Dec 03, 2022 |
| HP            | EliteBook 820 G3            | [6913ec89c8](https://linux-hardware.org/?probe=6913ec89c8) | Dec 03, 2022 |
| Acer          | TravelMate 3270             | [508b0c99e6](https://linux-hardware.org/?probe=508b0c99e6) | Dec 03, 2022 |
| Sony          | SVE1512H1EB                 | [8a18c5ecb7](https://linux-hardware.org/?probe=8a18c5ecb7) | Dec 03, 2022 |
| Sony          | SVE1512H1EB                 | [6b98a2d097](https://linux-hardware.org/?probe=6b98a2d097) | Dec 03, 2022 |
| HP            | ZBook 15                    | [f2868b04a8](https://linux-hardware.org/?probe=f2868b04a8) | Dec 03, 2022 |
| Apple         | MacBook7,1                  | [2ac1c5691b](https://linux-hardware.org/?probe=2ac1c5691b) | Dec 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [cde3a58a79](https://linux-hardware.org/?probe=cde3a58a79) | Dec 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [fe5fd075f2](https://linux-hardware.org/?probe=fe5fd075f2) | Dec 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [778cdee8a8](https://linux-hardware.org/?probe=778cdee8a8) | Dec 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [476f1de597](https://linux-hardware.org/?probe=476f1de597) | Dec 02, 2022 |
| Unknown       | Unknown                     | [6d3639b02c](https://linux-hardware.org/?probe=6d3639b02c) | Dec 02, 2022 |
| Google        | Kled                        | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [9c5bc7ca10](https://linux-hardware.org/?probe=9c5bc7ca10) | Dec 02, 2022 |
| HP            | EliteBook 820 G3            | [2414a84e4f](https://linux-hardware.org/?probe=2414a84e4f) | Dec 02, 2022 |
| TUXEDO        | Book BA1510                 | [0e6c8cb124](https://linux-hardware.org/?probe=0e6c8cb124) | Dec 02, 2022 |
| MSI           | GF75 Thin 10UEK             | [3f994419c5](https://linux-hardware.org/?probe=3f994419c5) | Dec 01, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | [4ebebe7785](https://linux-hardware.org/?probe=4ebebe7785) | Dec 01, 2022 |
| Packard Be... | DOT S                       | [bb05d9a173](https://linux-hardware.org/?probe=bb05d9a173) | Dec 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [fe9e8854c5](https://linux-hardware.org/?probe=fe9e8854c5) | Dec 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| TUXEDO        | N13xWU                      | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Dell          | XPS 13 9343                 | [125fcd77b9](https://linux-hardware.org/?probe=125fcd77b9) | Dec 01, 2022 |
| Acer          | TravelMate P614-51T-G2      | [952e89e25d](https://linux-hardware.org/?probe=952e89e25d) | Dec 01, 2022 |
| Sony          | VPCEB4L9E                   | [cad7ef5059](https://linux-hardware.org/?probe=cad7ef5059) | Nov 30, 2022 |
| Lenovo        | G500 20236                  | [43815283d9](https://linux-hardware.org/?probe=43815283d9) | Nov 30, 2022 |
| Dell          | XPS 15 9500                 | [42971a8394](https://linux-hardware.org/?probe=42971a8394) | Nov 30, 2022 |
| Notebook      | RIM2520                     | [5f66abbb8b](https://linux-hardware.org/?probe=5f66abbb8b) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9505f905e8](https://linux-hardware.org/?probe=9505f905e8) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c33e807c11](https://linux-hardware.org/?probe=c33e807c11) | Nov 30, 2022 |
| Tactus        | GeoBook 140                 | [91342e56df](https://linux-hardware.org/?probe=91342e56df) | Nov 29, 2022 |
| HP            | Compaq CQ58                 | [009ac41742](https://linux-hardware.org/?probe=009ac41742) | Nov 29, 2022 |
| Dell          | Precision 7520              | [2c0cb92f23](https://linux-hardware.org/?probe=2c0cb92f23) | Nov 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50e500a8fb](https://linux-hardware.org/?probe=50e500a8fb) | Nov 29, 2022 |
| Lenovo        | ThinkPad E550 20DF004RGE    | [a06fd97ee3](https://linux-hardware.org/?probe=a06fd97ee3) | Nov 29, 2022 |
| ASUSTek       | X756UXK                     | [a8fde1c59a](https://linux-hardware.org/?probe=a8fde1c59a) | Nov 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [140872c53d](https://linux-hardware.org/?probe=140872c53d) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| TUXEDO        | Unknown                     | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | G500 20236                  | [6ece9d62e6](https://linux-hardware.org/?probe=6ece9d62e6) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460s 20FAS16J0... | [142a1e8a94](https://linux-hardware.org/?probe=142a1e8a94) | Nov 29, 2022 |
| HP            | ZBook 15                    | [452a6f86d5](https://linux-hardware.org/?probe=452a6f86d5) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [fd821a4b54](https://linux-hardware.org/?probe=fd821a4b54) | Nov 29, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [6dcdb4d9ea](https://linux-hardware.org/?probe=6dcdb4d9ea) | Nov 29, 2022 |
| Dell          | G7 7790                     | [a85c1cd70e](https://linux-hardware.org/?probe=a85c1cd70e) | Nov 28, 2022 |
| Acer          | Aspire 5820TG               | [61cab6d996](https://linux-hardware.org/?probe=61cab6d996) | Nov 28, 2022 |
| Acer          | Aspire 5820TG               | [1e64d9426d](https://linux-hardware.org/?probe=1e64d9426d) | Nov 28, 2022 |
| Acer          | Swift SF314-43              | [1a6c47ad0e](https://linux-hardware.org/?probe=1a6c47ad0e) | Nov 28, 2022 |
| Acer          | Aspire A315-59              | [f7a1cff386](https://linux-hardware.org/?probe=f7a1cff386) | Nov 28, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| Chuwi         | HeroBook Pro                | [df7f48022d](https://linux-hardware.org/?probe=df7f48022d) | Nov 28, 2022 |
| Chuwi         | HeroBook Pro                | [c8e48e2c0f](https://linux-hardware.org/?probe=c8e48e2c0f) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| Lenovo        | G700 20251                  | [49167f9f67](https://linux-hardware.org/?probe=49167f9f67) | Nov 28, 2022 |
| HP            | 255 G6 Notebook PC          | [e17172d1c5](https://linux-hardware.org/?probe=e17172d1c5) | Nov 28, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [1f4c5bfc57](https://linux-hardware.org/?probe=1f4c5bfc57) | Nov 28, 2022 |
| HP            | EliteBook 8560w             | [61e60261ef](https://linux-hardware.org/?probe=61e60261ef) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [0c1dece352](https://linux-hardware.org/?probe=0c1dece352) | Nov 28, 2022 |
| Dell          | System XPS L502X            | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Fujitsu       | LIFEBOOK S751               | [20cb13ada3](https://linux-hardware.org/?probe=20cb13ada3) | Nov 27, 2022 |
| Fujitsu       | LIFEBOOK S751               | [9062066523](https://linux-hardware.org/?probe=9062066523) | Nov 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [d8bb1b1d38](https://linux-hardware.org/?probe=d8bb1b1d38) | Nov 27, 2022 |
| Medion        | E11201                      | [0838f9db75](https://linux-hardware.org/?probe=0838f9db75) | Nov 27, 2022 |
| HP            | EliteBook 8560w             | [3145d17bb7](https://linux-hardware.org/?probe=3145d17bb7) | Nov 27, 2022 |
| Tactus        | GeoBook 140                 | [e3f4d734da](https://linux-hardware.org/?probe=e3f4d734da) | Nov 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [7db4db6cc7](https://linux-hardware.org/?probe=7db4db6cc7) | Nov 27, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| HP            | ProBook 440 G7              | [d923cda32c](https://linux-hardware.org/?probe=d923cda32c) | Nov 26, 2022 |
| Dell          | XPS 15 7590                 | [071f2be55e](https://linux-hardware.org/?probe=071f2be55e) | Nov 26, 2022 |
| Dell          | Latitude D610               | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| Valve         | Jupiter                     | [ea37f7d713](https://linux-hardware.org/?probe=ea37f7d713) | Nov 26, 2022 |
| HP            | 255 G7 Notebook PC          | [8c389cf5d6](https://linux-hardware.org/?probe=8c389cf5d6) | Nov 26, 2022 |
| Acer          | Swift SFX14-41G             | [521cb4d847](https://linux-hardware.org/?probe=521cb4d847) | Nov 26, 2022 |
| MSI           | GE70 2OC\2OE                | [842781ccfc](https://linux-hardware.org/?probe=842781ccfc) | Nov 26, 2022 |
| Dell          | Latitude E6540              | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| Getac         | S410                        | [3df44aa3af](https://linux-hardware.org/?probe=3df44aa3af) | Nov 26, 2022 |
| TUXEDO        | Aura 15 Gen1                | [2868e94785](https://linux-hardware.org/?probe=2868e94785) | Nov 26, 2022 |
| Samsung       | RC530/RC730                 | [64515ff8b1](https://linux-hardware.org/?probe=64515ff8b1) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [ab0d49b5cd](https://linux-hardware.org/?probe=ab0d49b5cd) | Nov 25, 2022 |
| MSI           | MS-16G1                     | [8d8233d2a9](https://linux-hardware.org/?probe=8d8233d2a9) | Nov 25, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [18130ae317](https://linux-hardware.org/?probe=18130ae317) | Nov 25, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [48d797ccdc](https://linux-hardware.org/?probe=48d797ccdc) | Nov 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [86735d895f](https://linux-hardware.org/?probe=86735d895f) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [1f2bd09174](https://linux-hardware.org/?probe=1f2bd09174) | Nov 25, 2022 |
| ASUSTek       | X751MA                      | [15ea4b4462](https://linux-hardware.org/?probe=15ea4b4462) | Nov 25, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [024b4da647](https://linux-hardware.org/?probe=024b4da647) | Nov 25, 2022 |
| HP            | Compaq CQ58                 | [e6d1387823](https://linux-hardware.org/?probe=e6d1387823) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| Lenovo        | 40684WG                     | [27e2eeccbf](https://linux-hardware.org/?probe=27e2eeccbf) | Nov 25, 2022 |
| Samsung       | R59P/R60P/R61P              | [62510109f9](https://linux-hardware.org/?probe=62510109f9) | Nov 25, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [f82ee02c50](https://linux-hardware.org/?probe=f82ee02c50) | Nov 25, 2022 |
| HP            | ZBook 15                    | [dc8f215893](https://linux-hardware.org/?probe=dc8f215893) | Nov 25, 2022 |
| Dell          | Inspiron 7559               | [620f0d5cec](https://linux-hardware.org/?probe=620f0d5cec) | Nov 25, 2022 |
| Acer          | Aspire VN7-791G             | [7664866053](https://linux-hardware.org/?probe=7664866053) | Nov 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Apple         | MacBook3,1                  | [404821c7d6](https://linux-hardware.org/?probe=404821c7d6) | Nov 25, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [cd660d3210](https://linux-hardware.org/?probe=cd660d3210) | Nov 24, 2022 |
| HP            | 255 G7 Notebook PC          | [f5a6bcf0fb](https://linux-hardware.org/?probe=f5a6bcf0fb) | Nov 24, 2022 |
| Acer          | Aspire E5-573               | [c0ccedd707](https://linux-hardware.org/?probe=c0ccedd707) | Nov 24, 2022 |
| Acer          | Aspire E5-573               | [f2b9fd554b](https://linux-hardware.org/?probe=f2b9fd554b) | Nov 24, 2022 |
| Acer          | Aspire ES1-711              | [b3260faedb](https://linux-hardware.org/?probe=b3260faedb) | Nov 24, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [aaa0e3394f](https://linux-hardware.org/?probe=aaa0e3394f) | Nov 24, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [b73b2c4c07](https://linux-hardware.org/?probe=b73b2c4c07) | Nov 24, 2022 |
| Lenovo        | V145-15AST 81MT             | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| Samsung       | 600B4B/600B5B               | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Dell          | XPS 13 9300                 | [43fe4ed852](https://linux-hardware.org/?probe=43fe4ed852) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| HP            | EliteBook 820 G3            | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| HP            | EliteBook 8560w             | [7253dd4798](https://linux-hardware.org/?probe=7253dd4798) | Nov 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0f96032f10](https://linux-hardware.org/?probe=0f96032f10) | Nov 24, 2022 |
| Packard Be... | EasyNote TM98               | [468831c306](https://linux-hardware.org/?probe=468831c306) | Nov 24, 2022 |
| Lenovo        | ThinkPad T460 20FMS0VG25    | [06221c9746](https://linux-hardware.org/?probe=06221c9746) | Nov 24, 2022 |
| Dell          | Inspiron 7720               | [a75b9a21f9](https://linux-hardware.org/?probe=a75b9a21f9) | Nov 24, 2022 |
| Dell          | Latitude E6320              | [81f633b550](https://linux-hardware.org/?probe=81f633b550) | Nov 24, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [1c65fff6e7](https://linux-hardware.org/?probe=1c65fff6e7) | Nov 24, 2022 |
| Dell          | XPS 9320                    | [d63a585507](https://linux-hardware.org/?probe=d63a585507) | Nov 23, 2022 |
| Dell          | Inspiron 7720               | [ae4fc56cb3](https://linux-hardware.org/?probe=ae4fc56cb3) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| Lenovo        | ThinkPad T460 20FMS0VG25    | [b00a1e7f6a](https://linux-hardware.org/?probe=b00a1e7f6a) | Nov 23, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| HP            | G62                         | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| MPMAN         | CONVERTER 102               | [cab847edc0](https://linux-hardware.org/?probe=cab847edc0) | Nov 23, 2022 |
| ASUSTek       | GR8                         | [99683fc732](https://linux-hardware.org/?probe=99683fc732) | Nov 22, 2022 |
| Apple         | MacBookPro11,3              | [476415b4e4](https://linux-hardware.org/?probe=476415b4e4) | Nov 22, 2022 |
| Acer          | Aspire 7520                 | [d2f4caca66](https://linux-hardware.org/?probe=d2f4caca66) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RJ0... | [43f6a19d9a](https://linux-hardware.org/?probe=43f6a19d9a) | Nov 22, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | [31ddbc5ee3](https://linux-hardware.org/?probe=31ddbc5ee3) | Nov 22, 2022 |
| Acer          | Aspire A315-51              | [3d8ef86616](https://linux-hardware.org/?probe=3d8ef86616) | Nov 21, 2022 |
| Acer          | Aspire A315-51              | [bcff111ecd](https://linux-hardware.org/?probe=bcff111ecd) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Lenovo        | ThinkPad T450 20BUA0AEIG    | [48956b6f61](https://linux-hardware.org/?probe=48956b6f61) | Nov 21, 2022 |
| HP            | EliteBook 840 G5            | [62ffc22eea](https://linux-hardware.org/?probe=62ffc22eea) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440 20B7000LGE    | [9194594686](https://linux-hardware.org/?probe=9194594686) | Nov 21, 2022 |
| HP            | 250 G7 Notebook PC          | [f56bd99812](https://linux-hardware.org/?probe=f56bd99812) | Nov 21, 2022 |
| HP            | 250 G7 Notebook PC          | [d7e8c67720](https://linux-hardware.org/?probe=d7e8c67720) | Nov 21, 2022 |
| HP            | ZBook 17 G2                 | [1c5168fcfe](https://linux-hardware.org/?probe=1c5168fcfe) | Nov 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [b65ee83a19](https://linux-hardware.org/?probe=b65ee83a19) | Nov 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [c8d395cdcc](https://linux-hardware.org/?probe=c8d395cdcc) | Nov 21, 2022 |
| Dell          | Latitude E6320              | [91ebf30a5c](https://linux-hardware.org/?probe=91ebf30a5c) | Nov 21, 2022 |
| Medion        | Akoya P2214T                | [eb9e0cfbf8](https://linux-hardware.org/?probe=eb9e0cfbf8) | Nov 20, 2022 |
| Samsung       | 270E5J/2570EJ               | [f5b73b34c6](https://linux-hardware.org/?probe=f5b73b34c6) | Nov 20, 2022 |
| MSI           | CX700                       | [69c6ae1f04](https://linux-hardware.org/?probe=69c6ae1f04) | Nov 20, 2022 |
| HUAWEI        | MACH-WX9                    | [32fa69ea64](https://linux-hardware.org/?probe=32fa69ea64) | Nov 20, 2022 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [d9a74ee60a](https://linux-hardware.org/?probe=d9a74ee60a) | Nov 20, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2db5ac853d](https://linux-hardware.org/?probe=2db5ac853d) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | [52810e28da](https://linux-hardware.org/?probe=52810e28da) | Nov 20, 2022 |
| HP            | EliteBook 850 G4            | [30c7f00ee5](https://linux-hardware.org/?probe=30c7f00ee5) | Nov 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| Acer          | Aspire VN7-572G             | [314902c0f1](https://linux-hardware.org/?probe=314902c0f1) | Nov 20, 2022 |
| HP            | ZBook 15 G2                 | [5df677d667](https://linux-hardware.org/?probe=5df677d667) | Nov 20, 2022 |
| MPMAN         | CONVERTER 102               | [845925720b](https://linux-hardware.org/?probe=845925720b) | Nov 20, 2022 |
| Chuwi         | LapBook SE                  | [ecc56a3703](https://linux-hardware.org/?probe=ecc56a3703) | Nov 19, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| ASUSTek       | B451JA                      | [faeb294d65](https://linux-hardware.org/?probe=faeb294d65) | Nov 19, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [bed1f98f04](https://linux-hardware.org/?probe=bed1f98f04) | Nov 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [85e0869ac9](https://linux-hardware.org/?probe=85e0869ac9) | Nov 19, 2022 |
| Tactus        | GeoBook 140                 | [127ec68044](https://linux-hardware.org/?probe=127ec68044) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Dell          | Inspiron 3537               | [b8d74d8e6f](https://linux-hardware.org/?probe=b8d74d8e6f) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [1572414802](https://linux-hardware.org/?probe=1572414802) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |
| Dell          | Latitude 5414               | [a408bec327](https://linux-hardware.org/?probe=a408bec327) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Acer          | Aspire A515-45              | [482709f151](https://linux-hardware.org/?probe=482709f151) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| Dell          | Precision M4400             | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK E756               | [144470ec16](https://linux-hardware.org/?probe=144470ec16) | Nov 18, 2022 |
| HUAWEI        | HLYL-WXX9                   | [560c24bf74](https://linux-hardware.org/?probe=560c24bf74) | Nov 18, 2022 |
| Packard Be... | EasyNote TK81               | [c396423368](https://linux-hardware.org/?probe=c396423368) | Nov 17, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [13bd11ffd4](https://linux-hardware.org/?probe=13bd11ffd4) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [64fb254a64](https://linux-hardware.org/?probe=64fb254a64) | Nov 17, 2022 |
| HP            | EliteBook 745 G5            | [9d7fefd253](https://linux-hardware.org/?probe=9d7fefd253) | Nov 17, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | [aacdefc31b](https://linux-hardware.org/?probe=aacdefc31b) | Nov 17, 2022 |
| Apple         | MacBookAir7,2               | [b0bdd6227a](https://linux-hardware.org/?probe=b0bdd6227a) | Nov 17, 2022 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [ca1def3570](https://linux-hardware.org/?probe=ca1def3570) | Nov 17, 2022 |
| Medion        | P6816                       | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| HP            | Laptop 17-by1xxx            | [a74914048e](https://linux-hardware.org/?probe=a74914048e) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| Dell          | Latitude 3320               | [fbaf8e5ab9](https://linux-hardware.org/?probe=fbaf8e5ab9) | Nov 16, 2022 |
| Dell          | Latitude 3320               | [377fbd3b41](https://linux-hardware.org/?probe=377fbd3b41) | Nov 16, 2022 |
| Apple         | MacBookPro9,2               | [8e1b32a9f0](https://linux-hardware.org/?probe=8e1b32a9f0) | Nov 16, 2022 |
| ASUSTek       | A7K                         | [08edc83fa4](https://linux-hardware.org/?probe=08edc83fa4) | Nov 16, 2022 |
| MSI           | CR620                       | [4d90de18ca](https://linux-hardware.org/?probe=4d90de18ca) | Nov 16, 2022 |
| Apple         | MacBook4,1                  | [06c160b1a8](https://linux-hardware.org/?probe=06c160b1a8) | Nov 16, 2022 |
| Dell          | Latitude E6430              | [60832751d1](https://linux-hardware.org/?probe=60832751d1) | Nov 16, 2022 |
| Acer          | Aspire A315-42              | [121ed6e51d](https://linux-hardware.org/?probe=121ed6e51d) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e7343719c2](https://linux-hardware.org/?probe=e7343719c2) | Nov 16, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [c43362b7ad](https://linux-hardware.org/?probe=c43362b7ad) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| Google        | Boten                       | [105e91dd04](https://linux-hardware.org/?probe=105e91dd04) | Nov 16, 2022 |
| ASUSTek       | T100HAN                     | [f973b6bcd4](https://linux-hardware.org/?probe=f973b6bcd4) | Nov 15, 2022 |
| Dell          | Studio 1737                 | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| Dell          | Inspiron 3505               | [ce754fa34b](https://linux-hardware.org/?probe=ce754fa34b) | Nov 15, 2022 |
| Apple         | MacBook1,1                  | [6945006338](https://linux-hardware.org/?probe=6945006338) | Nov 15, 2022 |
| Lenovo        | ThinkPad T490s 20NYS02B0... | [7d2cffcf6a](https://linux-hardware.org/?probe=7d2cffcf6a) | Nov 15, 2022 |
| ASUSTek       | A7K                         | [ff0ca96a2e](https://linux-hardware.org/?probe=ff0ca96a2e) | Nov 15, 2022 |
| Acer          | Aspire V3-571G              | [ea0093a1f6](https://linux-hardware.org/?probe=ea0093a1f6) | Nov 15, 2022 |
| Chuwi         | GemiBook Pro                | [d9b2356cf0](https://linux-hardware.org/?probe=d9b2356cf0) | Nov 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dcffe478fe](https://linux-hardware.org/?probe=dcffe478fe) | Nov 14, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [de9e18e6ca](https://linux-hardware.org/?probe=de9e18e6ca) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ASUSTek       | K53U                        | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| Apple         | MacBookPro11,4              | [9028326508](https://linux-hardware.org/?probe=9028326508) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Acer          | Aspire A315-42              | [333067d4c6](https://linux-hardware.org/?probe=333067d4c6) | Nov 14, 2022 |
| Dell          | XPS 13 9380                 | [1501d641b4](https://linux-hardware.org/?probe=1501d641b4) | Nov 14, 2022 |
| Dell          | XPS 9315                    | [9f97a6b66c](https://linux-hardware.org/?probe=9f97a6b66c) | Nov 14, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [8267ec6686](https://linux-hardware.org/?probe=8267ec6686) | Nov 14, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [3e1d185e6d](https://linux-hardware.org/?probe=3e1d185e6d) | Nov 14, 2022 |
| Toshiba       | Satellite P50-B-10Q         | [f28064cdad](https://linux-hardware.org/?probe=f28064cdad) | Nov 14, 2022 |
| Fujitsu       | LIFEBOOK U7511              | [66656bedcf](https://linux-hardware.org/?probe=66656bedcf) | Nov 14, 2022 |
| Valve         | Jupiter                     | [0bd1833d8c](https://linux-hardware.org/?probe=0bd1833d8c) | Nov 13, 2022 |
| HP            | 530 Notebook PC(KD092AA#... | [b6c682238c](https://linux-hardware.org/?probe=b6c682238c) | Nov 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [41dbab85c0](https://linux-hardware.org/?probe=41dbab85c0) | Nov 13, 2022 |
| Dell          | Venue 11 Pro 5130           | [bb8c29a397](https://linux-hardware.org/?probe=bb8c29a397) | Nov 13, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| Medion        | E7220                       | [7d3df30772](https://linux-hardware.org/?probe=7d3df30772) | Nov 13, 2022 |
| HP            | ProBook 640 G4              | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| HP            | Pavilion g7                 | [ebf3708ac3](https://linux-hardware.org/?probe=ebf3708ac3) | Nov 13, 2022 |
| Valve         | Jupiter                     | [0046f0e15d](https://linux-hardware.org/?probe=0046f0e15d) | Nov 13, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [ff0881b6e4](https://linux-hardware.org/?probe=ff0881b6e4) | Nov 13, 2022 |
| Acer          | Aspire SW5-171              | [2d44304a43](https://linux-hardware.org/?probe=2d44304a43) | Nov 13, 2022 |
| Packard Be... | EasyNote TM98               | [1b98225677](https://linux-hardware.org/?probe=1b98225677) | Nov 13, 2022 |
| Medion        | E4254 MD63100               | [b38503d9ac](https://linux-hardware.org/?probe=b38503d9ac) | Nov 13, 2022 |
| Medion        | E4254 MD63100               | [bc622b98f9](https://linux-hardware.org/?probe=bc622b98f9) | Nov 13, 2022 |
| Sony          | SVF1532W4E                  | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| Sony          | SVT1511M1ES                 | [2fd916d045](https://linux-hardware.org/?probe=2fd916d045) | Nov 12, 2022 |
| Valve         | Jupiter                     | [62e925fd8a](https://linux-hardware.org/?probe=62e925fd8a) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E782               | [f6b2530682](https://linux-hardware.org/?probe=f6b2530682) | Nov 12, 2022 |
| Packard Be... | EasyNote LJ65               | [1de1737600](https://linux-hardware.org/?probe=1de1737600) | Nov 12, 2022 |
| Dell          | Latitude E6420              | [056daa7806](https://linux-hardware.org/?probe=056daa7806) | Nov 12, 2022 |
| Dell          | Precision 5570              | [b89bc3b56a](https://linux-hardware.org/?probe=b89bc3b56a) | Nov 12, 2022 |
| Lenovo        | ThinkPad A285 20MX000HMX    | [d199e5d35b](https://linux-hardware.org/?probe=d199e5d35b) | Nov 12, 2022 |
| Lenovo        | G710 20252                  | [3ae6407869](https://linux-hardware.org/?probe=3ae6407869) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0d6bd34095](https://linux-hardware.org/?probe=0d6bd34095) | Nov 12, 2022 |
| Google        | Shyvana                     | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Dell          | Vostro 3300                 | [be3a3b081d](https://linux-hardware.org/?probe=be3a3b081d) | Nov 12, 2022 |
| AXDIA Inte... | MYBOOK 14                   | [0638c8c3ec](https://linux-hardware.org/?probe=0638c8c3ec) | Nov 12, 2022 |
| Acer          | Aspire SW5-171              | [6b887efe23](https://linux-hardware.org/?probe=6b887efe23) | Nov 11, 2022 |
| HP            | EliteBook 8460p             | [0bf7762382](https://linux-hardware.org/?probe=0bf7762382) | Nov 11, 2022 |
| Dell          | Precision M4700             | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [22ab694d81](https://linux-hardware.org/?probe=22ab694d81) | Nov 11, 2022 |
| Google        | Volet                       | [ad7d4384bc](https://linux-hardware.org/?probe=ad7d4384bc) | Nov 11, 2022 |
| Acer          | AOD255E                     | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| Dell          | XPS 15 9510                 | [2db7764d25](https://linux-hardware.org/?probe=2db7764d25) | Nov 11, 2022 |
| Gigabyte      | AERO 15-X9                  | [1d490bb7d1](https://linux-hardware.org/?probe=1d490bb7d1) | Nov 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Medion        | X781X                       | [c6dc817a03](https://linux-hardware.org/?probe=c6dc817a03) | Nov 10, 2022 |
| Samsung       | SP55S                       | [92ae1cf763](https://linux-hardware.org/?probe=92ae1cf763) | Nov 10, 2022 |
| HP            | EliteBook 840 14 inch G9... | [950c263b8a](https://linux-hardware.org/?probe=950c263b8a) | Nov 10, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [4e535c916f](https://linux-hardware.org/?probe=4e535c916f) | Nov 10, 2022 |
| CSL-Comput... | R Evolve C14i               | [2a99a4d733](https://linux-hardware.org/?probe=2a99a4d733) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| ASUSTek       | G752VS                      | [d64b6e685f](https://linux-hardware.org/?probe=d64b6e685f) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | [0847b8a5d7](https://linux-hardware.org/?probe=0847b8a5d7) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | [a5446ab998](https://linux-hardware.org/?probe=a5446ab998) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| HP            | Laptop 17-ca2xxx            | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Dell          | Inspiron 3593               | [be071c7456](https://linux-hardware.org/?probe=be071c7456) | Nov 08, 2022 |
| HP            | ProBook 650 G4              | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S24N00    | [0b17fc5246](https://linux-hardware.org/?probe=0b17fc5246) | Nov 08, 2022 |
| Dell          | Precision 5540              | [4dacdf54de](https://linux-hardware.org/?probe=4dacdf54de) | Nov 08, 2022 |
| Acer          | Aspire 7735                 | [6134256155](https://linux-hardware.org/?probe=6134256155) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| Apple         | MacBookPro12,1              | [2b5899e483](https://linux-hardware.org/?probe=2b5899e483) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [2c04c69ac3](https://linux-hardware.org/?probe=2c04c69ac3) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Apple         | MacBookPro9,2               | [0d548754f5](https://linux-hardware.org/?probe=0d548754f5) | Nov 07, 2022 |
| Acer          | Enduro EN314-51W            | [ed2102b338](https://linux-hardware.org/?probe=ed2102b338) | Nov 07, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [9c3a72fffb](https://linux-hardware.org/?probe=9c3a72fffb) | Nov 07, 2022 |
| Lenovo        | V15-IIL 82C5                | [7f372be9dc](https://linux-hardware.org/?probe=7f372be9dc) | Nov 07, 2022 |
| Dell          | Studio 1558                 | [8be31a4335](https://linux-hardware.org/?probe=8be31a4335) | Nov 07, 2022 |
| Dell          | Studio 1737                 | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| Schenker      | XMG NEO (M22)               | [b1abd017f3](https://linux-hardware.org/?probe=b1abd017f3) | Nov 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f3c625be2d](https://linux-hardware.org/?probe=f3c625be2d) | Nov 07, 2022 |
| Dell          | Inspiron 5415               | [48edcdeec1](https://linux-hardware.org/?probe=48edcdeec1) | Nov 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e13f29fc81](https://linux-hardware.org/?probe=e13f29fc81) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| Unknown       | Unknown                     | [6af513692f](https://linux-hardware.org/?probe=6af513692f) | Nov 07, 2022 |
| Unknown       | Unknown                     | [b4859caaba](https://linux-hardware.org/?probe=b4859caaba) | Nov 07, 2022 |
| Lenovo        | ThinkPad T470p 20J60018G... | [b9650901a5](https://linux-hardware.org/?probe=b9650901a5) | Nov 07, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [12b14f3cbc](https://linux-hardware.org/?probe=12b14f3cbc) | Nov 06, 2022 |
| Lenovo        | Y520-15IKB 80YY             | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Fujitsu Si... | LIFEBOOK E8410              | [a2bfb0cd63](https://linux-hardware.org/?probe=a2bfb0cd63) | Nov 06, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| Packard Be... | EasyNote LJ65               | [c75f470cf8](https://linux-hardware.org/?probe=c75f470cf8) | Nov 06, 2022 |
| Acer          | Aspire 5750                 | [83a24172bd](https://linux-hardware.org/?probe=83a24172bd) | Nov 06, 2022 |
| Valve         | Jupiter                     | [695f4b6a83](https://linux-hardware.org/?probe=695f4b6a83) | Nov 06, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a37d4887e1](https://linux-hardware.org/?probe=a37d4887e1) | Nov 06, 2022 |
| HP            | 250 G8 Notebook PC          | [de8ffd02b1](https://linux-hardware.org/?probe=de8ffd02b1) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Lenovo        | ThinkPad L450 20DT0000GE    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [055c066a45](https://linux-hardware.org/?probe=055c066a45) | Nov 06, 2022 |
| Packard Be... | EasyNote LS44HR             | [375b78c3f3](https://linux-hardware.org/?probe=375b78c3f3) | Nov 06, 2022 |
| ASUSTek       | GL752VW                     | [cc373f85e7](https://linux-hardware.org/?probe=cc373f85e7) | Nov 06, 2022 |
| Medion        | E6222                       | [5e8852fe27](https://linux-hardware.org/?probe=5e8852fe27) | Nov 05, 2022 |
| Medion        | E6222                       | [382425c8de](https://linux-hardware.org/?probe=382425c8de) | Nov 05, 2022 |
| Quanta        | TW8/SW8/DW8                 | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| Wortmann      | 1220624_1470150             | [2782ad2c3e](https://linux-hardware.org/?probe=2782ad2c3e) | Nov 05, 2022 |
| TUXEDO        | Stellaris Intel Gen4        | [2b4987c9e8](https://linux-hardware.org/?probe=2b4987c9e8) | Nov 05, 2022 |
| Acer          | Aspire A717-71G             | [a6fa794196](https://linux-hardware.org/?probe=a6fa794196) | Nov 05, 2022 |
| Acer          | Aspire 5737Z                | [272737a826](https://linux-hardware.org/?probe=272737a826) | Nov 05, 2022 |
| Notebook      | N13xWU                      | [1514310861](https://linux-hardware.org/?probe=1514310861) | Nov 05, 2022 |
| Lenovo        | G50-70 20351                | [e29a593971](https://linux-hardware.org/?probe=e29a593971) | Nov 05, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [a2905cad90](https://linux-hardware.org/?probe=a2905cad90) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Lenovo        | B71-80 80RJ                 | [25e9f48d6e](https://linux-hardware.org/?probe=25e9f48d6e) | Nov 04, 2022 |
| Apple         | MacBookPro12,1              | [e63f3a94fa](https://linux-hardware.org/?probe=e63f3a94fa) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [4e666fbb8f](https://linux-hardware.org/?probe=4e666fbb8f) | Nov 04, 2022 |
| Medion        | E6246 MD63200               | [211d565292](https://linux-hardware.org/?probe=211d565292) | Nov 04, 2022 |
| ASUSTek       | X553MA                      | [d70f962654](https://linux-hardware.org/?probe=d70f962654) | Nov 04, 2022 |
| Lenovo        | Unknown                     | [0825807141](https://linux-hardware.org/?probe=0825807141) | Nov 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS2M300    | [28ebd68fbc](https://linux-hardware.org/?probe=28ebd68fbc) | Nov 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS2M300    | [9dd90ba8d3](https://linux-hardware.org/?probe=9dd90ba8d3) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [efb286a3c6](https://linux-hardware.org/?probe=efb286a3c6) | Nov 03, 2022 |
| HP            | EliteBook 850 G6            | [3480a7be5a](https://linux-hardware.org/?probe=3480a7be5a) | Nov 03, 2022 |
| MSI           | GF63 Thin 10SC              | [e5cf54c1c1](https://linux-hardware.org/?probe=e5cf54c1c1) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [813cfb5bdf](https://linux-hardware.org/?probe=813cfb5bdf) | Nov 03, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [c868e47483](https://linux-hardware.org/?probe=c868e47483) | Nov 03, 2022 |
| Notebook      | NJ50_70CU                   | [0427d9b80c](https://linux-hardware.org/?probe=0427d9b80c) | Nov 03, 2022 |
| Lenovo        | ThinkPad R500 2714AAG       | [456f21be22](https://linux-hardware.org/?probe=456f21be22) | Nov 03, 2022 |
| ASUSTek       | K50IJ                       | [5aa399c2c2](https://linux-hardware.org/?probe=5aa399c2c2) | Nov 03, 2022 |
| HUAWEI        | CREM-WXX9                   | [870d04c833](https://linux-hardware.org/?probe=870d04c833) | Nov 03, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Dell          | Latitude E6320              | [b66269072e](https://linux-hardware.org/?probe=b66269072e) | Nov 02, 2022 |
| Acer          | Nitro AN515-43              | [8ca3bfde82](https://linux-hardware.org/?probe=8ca3bfde82) | Nov 02, 2022 |
| Lenovo        | G50-45 80E3                 | [d4f08c71a6](https://linux-hardware.org/?probe=d4f08c71a6) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| HP            | 625                         | [830c5c0d14](https://linux-hardware.org/?probe=830c5c0d14) | Nov 02, 2022 |
| HP            | 625                         | [4c627cab51](https://linux-hardware.org/?probe=4c627cab51) | Nov 02, 2022 |
| HUAWEI        | HVY-WXX9                    | [87ab6daba5](https://linux-hardware.org/?probe=87ab6daba5) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Dell          | Vostro 15 3515              | [59c101934c](https://linux-hardware.org/?probe=59c101934c) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| HP            | ZBook 15 G3                 | [06ea8207dc](https://linux-hardware.org/?probe=06ea8207dc) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [1d24aac4ce](https://linux-hardware.org/?probe=1d24aac4ce) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2eb32b1bb3](https://linux-hardware.org/?probe=2eb32b1bb3) | Nov 01, 2022 |
| Timi          | TM1701                      | [84a5a6ce39](https://linux-hardware.org/?probe=84a5a6ce39) | Nov 01, 2022 |
| Lenovo        | G710 20252                  | [834e3f17aa](https://linux-hardware.org/?probe=834e3f17aa) | Oct 31, 2022 |
| Lenovo        | G710 20252                  | [acc007bae4](https://linux-hardware.org/?probe=acc007bae4) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| Sony          | VPCZ12C5E                   | [b1e6524541](https://linux-hardware.org/?probe=b1e6524541) | Oct 31, 2022 |
| HP            | Laptop 17-ca3xxx            | [2c42913712](https://linux-hardware.org/?probe=2c42913712) | Oct 31, 2022 |
| Dell          | Latitude E6500              | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| Sony          | VPCZ12C5E                   | [85803f499a](https://linux-hardware.org/?probe=85803f499a) | Oct 31, 2022 |
| Lenovo        | G700                        | [9bf9b4e263](https://linux-hardware.org/?probe=9bf9b4e263) | Oct 31, 2022 |
| Sony          | SVT13118FXS                 | [13b4af9ec3](https://linux-hardware.org/?probe=13b4af9ec3) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| ASUSTek       | K73SV                       | [d505f0c0d0](https://linux-hardware.org/?probe=d505f0c0d0) | Oct 30, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [2e39c3ce92](https://linux-hardware.org/?probe=2e39c3ce92) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| HP            | ProBook 450 G6              | [224f9c8141](https://linux-hardware.org/?probe=224f9c8141) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | [01d8b89e0d](https://linux-hardware.org/?probe=01d8b89e0d) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | [183feb626d](https://linux-hardware.org/?probe=183feb626d) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [97425e2f52](https://linux-hardware.org/?probe=97425e2f52) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [42fcb880db](https://linux-hardware.org/?probe=42fcb880db) | Oct 29, 2022 |
| Apple         | MacBookPro11,2              | [c5955c7440](https://linux-hardware.org/?probe=c5955c7440) | Oct 29, 2022 |
| Lenovo        | G710 20252                  | [f700e495ba](https://linux-hardware.org/?probe=f700e495ba) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [242fbb2c79](https://linux-hardware.org/?probe=242fbb2c79) | Oct 29, 2022 |
| Apple         | MacBookPro3,1               | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| HP            | Laptop 17-bs0xx             | [68238274ff](https://linux-hardware.org/?probe=68238274ff) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Dell          | Latitude 5590               | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4PR1... | [d99f500b00](https://linux-hardware.org/?probe=d99f500b00) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [7800fc7b5b](https://linux-hardware.org/?probe=7800fc7b5b) | Oct 29, 2022 |
| HP            | 255 G8 Notebook PC          | [7e9c19c994](https://linux-hardware.org/?probe=7e9c19c994) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [0971db18ed](https://linux-hardware.org/?probe=0971db18ed) | Oct 28, 2022 |
| TUXEDO        | Unknown                     | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Lenovo        | ThinkPad Edge E320 1298R... | [c79d1e6209](https://linux-hardware.org/?probe=c79d1e6209) | Oct 28, 2022 |
| TUXEDO        | Aura 15 Gen1                | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Dell          | Inspiron MM061              | [e1709bf653](https://linux-hardware.org/?probe=e1709bf653) | Oct 28, 2022 |
| Dell          | Inspiron MM061              | [05cffb09e0](https://linux-hardware.org/?probe=05cffb09e0) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Inspiron 15 3511            | [7cc13c49e2](https://linux-hardware.org/?probe=7cc13c49e2) | Oct 28, 2022 |
| HP            | 250 G5 Notebook PC          | [da6915a49b](https://linux-hardware.org/?probe=da6915a49b) | Oct 28, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [768c6c8357](https://linux-hardware.org/?probe=768c6c8357) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| Toshiba       | Satellite L300              | [60618ba137](https://linux-hardware.org/?probe=60618ba137) | Oct 27, 2022 |
| Lenovo        | G710 20252                  | [d15bee47c4](https://linux-hardware.org/?probe=d15bee47c4) | Oct 27, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [84acb8d19b](https://linux-hardware.org/?probe=84acb8d19b) | Oct 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | [7ffc8c3537](https://linux-hardware.org/?probe=7ffc8c3537) | Oct 27, 2022 |
| ASUSTek       | UL50VT                      | [e156a74255](https://linux-hardware.org/?probe=e156a74255) | Oct 27, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3541e2e011](https://linux-hardware.org/?probe=3541e2e011) | Oct 27, 2022 |
| Lenovo        | ThinkPad L590 20Q7001HGE    | [187544b911](https://linux-hardware.org/?probe=187544b911) | Oct 27, 2022 |
| Dell          | Precision 7760              | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Acer          | Aspire 8730                 | [86bffd9523](https://linux-hardware.org/?probe=86bffd9523) | Oct 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4386ec3fb8](https://linux-hardware.org/?probe=4386ec3fb8) | Oct 27, 2022 |
| Acer          | Aspire E3-112               | [fd34f66305](https://linux-hardware.org/?probe=fd34f66305) | Oct 26, 2022 |
| HP            | ProBook 445 G7              | [d9f63cbff8](https://linux-hardware.org/?probe=d9f63cbff8) | Oct 26, 2022 |
| ASUSTek       | X510UQ                      | [8907b3e019](https://linux-hardware.org/?probe=8907b3e019) | Oct 26, 2022 |
| LincPlus      | P1                          | [cc97e9ec36](https://linux-hardware.org/?probe=cc97e9ec36) | Oct 26, 2022 |
| Dell          | Precision 5570              | [3d5a222867](https://linux-hardware.org/?probe=3d5a222867) | Oct 26, 2022 |
| HP            | ProBook 640 G1              | [e30a33bfd8](https://linux-hardware.org/?probe=e30a33bfd8) | Oct 26, 2022 |
| Dell          | Latitude 7480               | [ec106dc62b](https://linux-hardware.org/?probe=ec106dc62b) | Oct 26, 2022 |
| HP            | 250 G5 Notebook PC          | [3f112eb783](https://linux-hardware.org/?probe=3f112eb783) | Oct 26, 2022 |
| HP            | 250 G5 Notebook PC          | [282a978812](https://linux-hardware.org/?probe=282a978812) | Oct 26, 2022 |
| Medion        | Unknown                     | [4645bf772f](https://linux-hardware.org/?probe=4645bf772f) | Oct 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [bd0f4d864e](https://linux-hardware.org/?probe=bd0f4d864e) | Oct 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [ae3d3abdf0](https://linux-hardware.org/?probe=ae3d3abdf0) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Dell          | Precision 5570              | [d74abc314b](https://linux-hardware.org/?probe=d74abc314b) | Oct 25, 2022 |
| Valve         | Jupiter                     | [98a9dbc46f](https://linux-hardware.org/?probe=98a9dbc46f) | Oct 25, 2022 |
| Lenovo        | IdeaPad U530 Touch 20289    | [93932086e7](https://linux-hardware.org/?probe=93932086e7) | Oct 25, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [80177955c3](https://linux-hardware.org/?probe=80177955c3) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [e4d7dc5f38](https://linux-hardware.org/?probe=e4d7dc5f38) | Oct 25, 2022 |
| Medion        | P8612                       | [a5c437d5f8](https://linux-hardware.org/?probe=a5c437d5f8) | Oct 24, 2022 |
| HP            | Laptop 17-cp0xxx            | [4a818d766f](https://linux-hardware.org/?probe=4a818d766f) | Oct 24, 2022 |
| Dell          | XPS 15 9500                 | [ebe6337ddc](https://linux-hardware.org/?probe=ebe6337ddc) | Oct 24, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [3cb2ce5a02](https://linux-hardware.org/?probe=3cb2ce5a02) | Oct 24, 2022 |
| Tactus        | GeoBook_240                 | [5331bf15bd](https://linux-hardware.org/?probe=5331bf15bd) | Oct 23, 2022 |
| Dell          | XPS 15 9500                 | [5fc8ebf31f](https://linux-hardware.org/?probe=5fc8ebf31f) | Oct 23, 2022 |
| Valve         | Jupiter                     | [6e4712d276](https://linux-hardware.org/?probe=6e4712d276) | Oct 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [7f98afbe41](https://linux-hardware.org/?probe=7f98afbe41) | Oct 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [b5315c133f](https://linux-hardware.org/?probe=b5315c133f) | Oct 23, 2022 |
| Valve         | Jupiter                     | [719742423c](https://linux-hardware.org/?probe=719742423c) | Oct 23, 2022 |
| Samsung       | R59P/R60P/R61P              | [0465cb7dee](https://linux-hardware.org/?probe=0465cb7dee) | Oct 23, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6EH0... | [794fa1859f](https://linux-hardware.org/?probe=794fa1859f) | Oct 23, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8138e910ce](https://linux-hardware.org/?probe=8138e910ce) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4884be1a24](https://linux-hardware.org/?probe=4884be1a24) | Oct 22, 2022 |
| Apple         | MacBookPro3,1               | [64087e63a2](https://linux-hardware.org/?probe=64087e63a2) | Oct 22, 2022 |
| Panasonic     | CF-LX3J-50M3                | [949acb4c3a](https://linux-hardware.org/?probe=949acb4c3a) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Lenovo        | ThinkPad X200 7459J74       | [7ca95da1a5](https://linux-hardware.org/?probe=7ca95da1a5) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [079a05485d](https://linux-hardware.org/?probe=079a05485d) | Oct 22, 2022 |
| ASUSTek       | X705UAP                     | [97de42a1ec](https://linux-hardware.org/?probe=97de42a1ec) | Oct 22, 2022 |
| Global Dis... | W11651                      | [9cf1e2df07](https://linux-hardware.org/?probe=9cf1e2df07) | Oct 22, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [c097316857](https://linux-hardware.org/?probe=c097316857) | Oct 22, 2022 |
| PC Special... | N750HU                      | [c90194cfb9](https://linux-hardware.org/?probe=c90194cfb9) | Oct 22, 2022 |
| Lenovo        | Legion 5 82B5               | [3d67f01531](https://linux-hardware.org/?probe=3d67f01531) | Oct 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [8eebebb58f](https://linux-hardware.org/?probe=8eebebb58f) | Oct 21, 2022 |
| MSI           | Katana GF76 11UG            | [ab90111e61](https://linux-hardware.org/?probe=ab90111e61) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [1ab0245c57](https://linux-hardware.org/?probe=1ab0245c57) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [41bade1339](https://linux-hardware.org/?probe=41bade1339) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [1c9e2ec0c2](https://linux-hardware.org/?probe=1c9e2ec0c2) | Oct 21, 2022 |
| Fujitsu       | LIFEBOOK E746               | [4c699ac628](https://linux-hardware.org/?probe=4c699ac628) | Oct 21, 2022 |
| Dell          | Precision M6800             | [9b909039ee](https://linux-hardware.org/?probe=9b909039ee) | Oct 21, 2022 |
| Acer          | Extensa 215-52              | [aaf7209d03](https://linux-hardware.org/?probe=aaf7209d03) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [c7cd7a2ddf](https://linux-hardware.org/?probe=c7cd7a2ddf) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [43eb559763](https://linux-hardware.org/?probe=43eb559763) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| MSI           | GT70 0NC/GT70 0NC           | [592b788d62](https://linux-hardware.org/?probe=592b788d62) | Oct 20, 2022 |
| Dell          | Latitude 5520               | [0455df4135](https://linux-hardware.org/?probe=0455df4135) | Oct 20, 2022 |
| Lenovo        | G780                        | [986b0fdbd0](https://linux-hardware.org/?probe=986b0fdbd0) | Oct 20, 2022 |
| HP            | Laptop 15-db0xxx            | [c9962923a9](https://linux-hardware.org/?probe=c9962923a9) | Oct 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [4c0b27f18e](https://linux-hardware.org/?probe=4c0b27f18e) | Oct 20, 2022 |
| HP            | EliteBook Folio 9470m       | [8e8d9a5c1d](https://linux-hardware.org/?probe=8e8d9a5c1d) | Oct 20, 2022 |
| HP            | EliteBook Folio 9470m       | [5b059add3e](https://linux-hardware.org/?probe=5b059add3e) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| Valve         | Jupiter                     | [53e7ae8cd4](https://linux-hardware.org/?probe=53e7ae8cd4) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| Valve         | Jupiter                     | [bdca0279e2](https://linux-hardware.org/?probe=bdca0279e2) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| HP            | 250 G8 Notebook PC          | [e8dc04cc0e](https://linux-hardware.org/?probe=e8dc04cc0e) | Oct 20, 2022 |
| HUAWEI        | HLYL-WXX9                   | [6a7e7ac7ce](https://linux-hardware.org/?probe=6a7e7ac7ce) | Oct 19, 2022 |
| Dell          | Latitude 7420               | [332d2cd420](https://linux-hardware.org/?probe=332d2cd420) | Oct 19, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [30bf540299](https://linux-hardware.org/?probe=30bf540299) | Oct 19, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1Q10... | [a96060006f](https://linux-hardware.org/?probe=a96060006f) | Oct 19, 2022 |
| Toshiba       | Satellite L300              | [ccd5c1a1d7](https://linux-hardware.org/?probe=ccd5c1a1d7) | Oct 19, 2022 |
| HP            | ZBook 15 G3                 | [a078a2f2ae](https://linux-hardware.org/?probe=a078a2f2ae) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| ASUSTek       | N82JV                       | [7157bb5872](https://linux-hardware.org/?probe=7157bb5872) | Oct 19, 2022 |
| ASUSTek       | BU201LAV                    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Acer          | Aspire V3-772G              | [b901145ed0](https://linux-hardware.org/?probe=b901145ed0) | Oct 19, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| MSI           | Katana GF66 11UE            | [0e2d9432e1](https://linux-hardware.org/?probe=0e2d9432e1) | Oct 18, 2022 |
| Dell          | XPS L701X                   | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| Notebook      | N15_17RD,RD2                | [50713b916b](https://linux-hardware.org/?probe=50713b916b) | Oct 18, 2022 |
| Valve         | Jupiter                     | [a52a79aad6](https://linux-hardware.org/?probe=a52a79aad6) | Oct 18, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [28a1d15220](https://linux-hardware.org/?probe=28a1d15220) | Oct 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [437cb780cb](https://linux-hardware.org/?probe=437cb780cb) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| Dell          | Precision 7760              | [44b60a4fcf](https://linux-hardware.org/?probe=44b60a4fcf) | Oct 18, 2022 |
| HP            | EliteBook 850 G2            | [79a8b3d707](https://linux-hardware.org/?probe=79a8b3d707) | Oct 18, 2022 |
| Toshiba       | Satellite L300              | [5c7a54a7ad](https://linux-hardware.org/?probe=5c7a54a7ad) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | [8a3de9dbf2](https://linux-hardware.org/?probe=8a3de9dbf2) | Oct 18, 2022 |
| HP            | Laptop 17-bs0xx             | [369934a06c](https://linux-hardware.org/?probe=369934a06c) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | [3dd30d87be](https://linux-hardware.org/?probe=3dd30d87be) | Oct 18, 2022 |
| Acer          | Aspire V3-772G              | [8231c6e6ef](https://linux-hardware.org/?probe=8231c6e6ef) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| MSI           | GP72VR 7RF                  | [86a4902866](https://linux-hardware.org/?probe=86a4902866) | Oct 17, 2022 |
| Valve         | Jupiter                     | [1c513b151b](https://linux-hardware.org/?probe=1c513b151b) | Oct 17, 2022 |
| Dell          | Latitude E7250              | [f7089d8635](https://linux-hardware.org/?probe=f7089d8635) | Oct 17, 2022 |
| Dell          | Latitude E5270              | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| ASUSTek       | X553MA                      | [71cfc713af](https://linux-hardware.org/?probe=71cfc713af) | Oct 17, 2022 |
| ASUSTek       | UX21A                       | [1d7d76b463](https://linux-hardware.org/?probe=1d7d76b463) | Oct 16, 2022 |
| Sony          | SVE1712C1EW                 | [d4f9a0d03b](https://linux-hardware.org/?probe=d4f9a0d03b) | Oct 16, 2022 |
| HP            | EliteBook 8460p             | [62291b3c66](https://linux-hardware.org/?probe=62291b3c66) | Oct 16, 2022 |
| Dell          | XPS 13 7390                 | [c78fae026e](https://linux-hardware.org/?probe=c78fae026e) | Oct 16, 2022 |
| Dell          | Latitude 3350               | [4c634a0308](https://linux-hardware.org/?probe=4c634a0308) | Oct 16, 2022 |
| Samsung       | NC10                        | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| MSI           | Katana GF76 11UG            | [460ceb1307](https://linux-hardware.org/?probe=460ceb1307) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [300f16471f](https://linux-hardware.org/?probe=300f16471f) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [e4645890b8](https://linux-hardware.org/?probe=e4645890b8) | Oct 16, 2022 |
| HP            | Laptop 17-bs0xx             | [090cc3b6c5](https://linux-hardware.org/?probe=090cc3b6c5) | Oct 16, 2022 |
| Dell          | Inspiron 3505               | [ea75db9cc9](https://linux-hardware.org/?probe=ea75db9cc9) | Oct 16, 2022 |
| Lenovo        | G70-70 80HW                 | [75e3a82cdf](https://linux-hardware.org/?probe=75e3a82cdf) | Oct 15, 2022 |
| Timi          | TM1701                      | [c2b709ff0c](https://linux-hardware.org/?probe=c2b709ff0c) | Oct 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [cce0f23c1a](https://linux-hardware.org/?probe=cce0f23c1a) | Oct 15, 2022 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | [ba752883e7](https://linux-hardware.org/?probe=ba752883e7) | Oct 15, 2022 |
| Fujitsu       | LIFEBOOK E754               | [4a2e6b2db6](https://linux-hardware.org/?probe=4a2e6b2db6) | Oct 15, 2022 |
| Acer          | Aspire A515-44              | [a19fc69283](https://linux-hardware.org/?probe=a19fc69283) | Oct 15, 2022 |
| Panasonic     | CF-LX3J-50M3                | [95386977de](https://linux-hardware.org/?probe=95386977de) | Oct 14, 2022 |
| Lenovo        | V15 G2 IJL 82QY             | [240811f34a](https://linux-hardware.org/?probe=240811f34a) | Oct 14, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e93bd87f1b](https://linux-hardware.org/?probe=e93bd87f1b) | Oct 14, 2022 |
| Toshiba       | Satellite C70-B             | [610178423d](https://linux-hardware.org/?probe=610178423d) | Oct 14, 2022 |
| Acer          | Aspire A515-45              | [f5f09c5dd6](https://linux-hardware.org/?probe=f5f09c5dd6) | Oct 14, 2022 |
| Acer          | Aspire A515-45              | [8b3d048a4b](https://linux-hardware.org/?probe=8b3d048a4b) | Oct 14, 2022 |
| Acer          | Aspire 5820TG               | [21ed56e447](https://linux-hardware.org/?probe=21ed56e447) | Oct 14, 2022 |
| Dell          | Latitude 5420               | [6621462af3](https://linux-hardware.org/?probe=6621462af3) | Oct 14, 2022 |
| ASUSTek       | N750JK                      | [cfa8b0a147](https://linux-hardware.org/?probe=cfa8b0a147) | Oct 14, 2022 |
| Lenovo        | ThinkPad T520 42434YG       | [cdfaf8e110](https://linux-hardware.org/?probe=cdfaf8e110) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [009302e426](https://linux-hardware.org/?probe=009302e426) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [77adb778b6](https://linux-hardware.org/?probe=77adb778b6) | Oct 13, 2022 |
| Gigabyte      | G5 MD                       | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 13 7390                 | [60b21aed9a](https://linux-hardware.org/?probe=60b21aed9a) | Oct 13, 2022 |
| ASUSTek       | X553MA                      | [256cb98ed8](https://linux-hardware.org/?probe=256cb98ed8) | Oct 13, 2022 |
| Dell          | Precision 7720              | [4cadd86832](https://linux-hardware.org/?probe=4cadd86832) | Oct 13, 2022 |
| Schenker      | SLIM_13_14_SSL13_14L18      | [b7bd0894f2](https://linux-hardware.org/?probe=b7bd0894f2) | Oct 13, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [38739fd54f](https://linux-hardware.org/?probe=38739fd54f) | Oct 13, 2022 |
| Fujitsu       | LIFEBOOK E752               | [b4b93e4c15](https://linux-hardware.org/?probe=b4b93e4c15) | Oct 13, 2022 |
| Dell          | Latitude E6420              | [f39e0305c5](https://linux-hardware.org/?probe=f39e0305c5) | Oct 13, 2022 |
| Lenovo        | ThinkPad T520 42434YG       | [d29671c689](https://linux-hardware.org/?probe=d29671c689) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b604d02690](https://linux-hardware.org/?probe=b604d02690) | Oct 13, 2022 |
| MSI           | Prestige 14 A11SCS          | [e552920463](https://linux-hardware.org/?probe=e552920463) | Oct 13, 2022 |
| Valve         | Jupiter                     | [ec6c38cc2e](https://linux-hardware.org/?probe=ec6c38cc2e) | Oct 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [705931711b](https://linux-hardware.org/?probe=705931711b) | Oct 13, 2022 |
| Valve         | Jupiter                     | [88385d207c](https://linux-hardware.org/?probe=88385d207c) | Oct 12, 2022 |
| HP            | EliteBook 830 G6            | [0dc42d7e5e](https://linux-hardware.org/?probe=0dc42d7e5e) | Oct 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [a2ec61226c](https://linux-hardware.org/?probe=a2ec61226c) | Oct 12, 2022 |
| HP            | x2 210                      | [8b73f83532](https://linux-hardware.org/?probe=8b73f83532) | Oct 12, 2022 |
| HP            | x2 210                      | [981b59c927](https://linux-hardware.org/?probe=981b59c927) | Oct 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ccee0b66d9](https://linux-hardware.org/?probe=ccee0b66d9) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [8b554dcfe0](https://linux-hardware.org/?probe=8b554dcfe0) | Oct 12, 2022 |
| Acer          | Aspire 8943G                | [b2db9705c1](https://linux-hardware.org/?probe=b2db9705c1) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [1bbc611d89](https://linux-hardware.org/?probe=1bbc611d89) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| Acer          | Nitro AN515-51              | [68df5abb66](https://linux-hardware.org/?probe=68df5abb66) | Oct 11, 2022 |
| Lenovo        | ThinkPad T430 2347DS3       | [970542656e](https://linux-hardware.org/?probe=970542656e) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [62dbb6973e](https://linux-hardware.org/?probe=62dbb6973e) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| Lenovo        | G710 20252                  | [d83e7270f9](https://linux-hardware.org/?probe=d83e7270f9) | Oct 11, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [3c02b5a75c](https://linux-hardware.org/?probe=3c02b5a75c) | Oct 10, 2022 |
| Valve         | Jupiter                     | [4c324f424d](https://linux-hardware.org/?probe=4c324f424d) | Oct 10, 2022 |
| HP            | Berknip                     | [016d401f29](https://linux-hardware.org/?probe=016d401f29) | Oct 10, 2022 |
| Sony          | VGN-N21E_W                  | [464905b4f8](https://linux-hardware.org/?probe=464905b4f8) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [98a14153ba](https://linux-hardware.org/?probe=98a14153ba) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [58eb34d574](https://linux-hardware.org/?probe=58eb34d574) | Oct 10, 2022 |
| MSI           | EX610                       | [60ac12983f](https://linux-hardware.org/?probe=60ac12983f) | Oct 10, 2022 |
| Acer          | Aspire A317-52              | [af63fa24cb](https://linux-hardware.org/?probe=af63fa24cb) | Oct 09, 2022 |
| Notebook      | N13xWU                      | [b9d5ec8b96](https://linux-hardware.org/?probe=b9d5ec8b96) | Oct 09, 2022 |
| Dell          | Inspiron 14 5420            | [d9f937a8c4](https://linux-hardware.org/?probe=d9f937a8c4) | Oct 09, 2022 |
| HP            | 255 G8 Notebook PC          | [6a56a66eae](https://linux-hardware.org/?probe=6a56a66eae) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [99d95e9424](https://linux-hardware.org/?probe=99d95e9424) | Oct 09, 2022 |
| Dell          | Studio 1745                 | [0a38385b3c](https://linux-hardware.org/?probe=0a38385b3c) | Oct 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [cd06846004](https://linux-hardware.org/?probe=cd06846004) | Oct 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [2f4281aaaf](https://linux-hardware.org/?probe=2f4281aaaf) | Oct 09, 2022 |
| Lenovo        | ThinkPad T61 765912G        | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| HP            | EliteBook 8460p             | [c49812c597](https://linux-hardware.org/?probe=c49812c597) | Oct 09, 2022 |
| HP            | EliteBook 8460p             | [0a13b34320](https://linux-hardware.org/?probe=0a13b34320) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7785f0ebfb](https://linux-hardware.org/?probe=7785f0ebfb) | Oct 09, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [4b42e61542](https://linux-hardware.org/?probe=4b42e61542) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [49802b54cd](https://linux-hardware.org/?probe=49802b54cd) | Oct 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f2e24545a0](https://linux-hardware.org/?probe=f2e24545a0) | Oct 08, 2022 |
| Sony          | VGN-AR71J                   | [57348f6a71](https://linux-hardware.org/?probe=57348f6a71) | Oct 08, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [ff4f9614fd](https://linux-hardware.org/?probe=ff4f9614fd) | Oct 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [f28b3e73c0](https://linux-hardware.org/?probe=f28b3e73c0) | Oct 08, 2022 |
| Dell          | Studio 1745                 | [35a2b9314f](https://linux-hardware.org/?probe=35a2b9314f) | Oct 08, 2022 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | [3aee91df8c](https://linux-hardware.org/?probe=3aee91df8c) | Oct 08, 2022 |
| Lenovo        | ThinkPad X200 7458EB2       | [70673f67bd](https://linux-hardware.org/?probe=70673f67bd) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Toshiba       | Satellite P200              | [55e4a786bd](https://linux-hardware.org/?probe=55e4a786bd) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3d968cc61a](https://linux-hardware.org/?probe=3d968cc61a) | Oct 08, 2022 |
| Packard Be... | EasyNote LS11HR             | [f606170c85](https://linux-hardware.org/?probe=f606170c85) | Oct 08, 2022 |
| HP            | ProBook 470 G1              | [8572d5cbb6](https://linux-hardware.org/?probe=8572d5cbb6) | Oct 08, 2022 |
| Valve         | Jupiter                     | [2d8b46d523](https://linux-hardware.org/?probe=2d8b46d523) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [dc99eb14fb](https://linux-hardware.org/?probe=dc99eb14fb) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E736               | [3e7cc2c14a](https://linux-hardware.org/?probe=3e7cc2c14a) | Oct 07, 2022 |
| Clevo         | W150HRM                     | [0aa2ea3e92](https://linux-hardware.org/?probe=0aa2ea3e92) | Oct 07, 2022 |
| HP            | ProBook 455 G7              | [26dfdb5aed](https://linux-hardware.org/?probe=26dfdb5aed) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| Acer          | Swift SF314-42              | [b20fc20189](https://linux-hardware.org/?probe=b20fc20189) | Oct 07, 2022 |
| HP            | Compaq 6530b (GW688AV)      | [4f99aa083c](https://linux-hardware.org/?probe=4f99aa083c) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [08e98e28c2](https://linux-hardware.org/?probe=08e98e28c2) | Oct 07, 2022 |
| Lenovo        | ThinkPad W510 4391B76       | [1c7ffe7f28](https://linux-hardware.org/?probe=1c7ffe7f28) | Oct 07, 2022 |
| HP            | Compaq 6530b (GW688AV)      | [805c7c3031](https://linux-hardware.org/?probe=805c7c3031) | Oct 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 1372      | 15.33%  |
| Ubuntu 18.04                 | 641       | 7.16%   |
| Ubuntu 22.04                 | 301       | 3.36%   |
| Linux Mint 20.2              | 300       | 3.35%   |
| Linux Mint 20.3              | 261       | 2.92%   |
| OpenMandriva 4.2             | 253       | 2.83%   |
| OpenMandriva 4.3             | 225       | 2.51%   |
| Linux Mint 20.1              | 200       | 2.23%   |
| Debian 11                    | 197       | 2.2%    |
| Linux Mint 20                | 172       | 1.92%   |
| Ubuntu 21.10                 | 160       | 1.79%   |
| Ubuntu 20.10                 | 160       | 1.79%   |
| Linux Mint 19.3              | 157       | 1.75%   |
| Manjaro                      | 151       | 1.69%   |
| Arch                         | 146       | 1.63%   |
| Xubuntu 20.04                | 132       | 1.48%   |
| Zorin 16                     | 130       | 1.45%   |
| KDE neon 20.04               | 116       | 1.3%    |
| Ubuntu 19.10                 | 111       | 1.24%   |
| Arch Rolling                 | 106       | 1.18%   |
| Ubuntu 19.04                 | 102       | 1.14%   |
| Ubuntu 21.04                 | 99        | 1.11%   |
| Linux Mint 21                | 95        | 1.06%   |
| BlackPanther 18.1            | 84        | 0.94%   |
| Fedora 36                    | 83        | 0.93%   |
| Debian 10                    | 78        | 0.87%   |
| Fedora 33                    | 71        | 0.79%   |
| Pop!_OS 20.10                | 67        | 0.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 67        | 0.75%   |
| Xubuntu 18.04                | 65        | 0.73%   |
| Zorin 15                     | 64        | 0.72%   |
| Kubuntu 20.04                | 64        | 0.72%   |
| Pop!_OS 22.04                | 63        | 0.7%    |
| Fedora 32                    | 63        | 0.7%    |
| Pop!_OS 20.04                | 59        | 0.66%   |
| Ubuntu 18.10                 | 57        | 0.64%   |
| Fedora 34                    | 57        | 0.64%   |
| Debian Testing               | 56        | 0.63%   |
| ArcoLinux Rolling            | 56        | 0.63%   |
| Linux Mint 19.2              | 54        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2897      | 34.29%  |
| Linux Mint    | 1234      | 14.61%  |
| OpenMandriva  | 530       | 6.27%   |
| Debian        | 370       | 4.38%   |
| Fedora        | 359       | 4.25%   |
| Manjaro       | 355       | 4.2%    |
| Pop!_OS       | 267       | 3.16%   |
| Xubuntu       | 261       | 3.09%   |
| Arch          | 248       | 2.94%   |
| Zorin         | 206       | 2.44%   |
| ROSA          | 178       | 2.11%   |
| Kubuntu       | 178       | 2.11%   |
| KDE neon      | 139       | 1.65%   |
| openSUSE      | 131       | 1.55%   |
| Endless       | 101       | 1.2%    |
| BlackPanther  | 93        | 1.1%    |
| Gentoo        | 80        | 0.95%   |
| Elementary    | 80        | 0.95%   |
| Ubuntu MATE   | 71        | 0.84%   |
| ArcoLinux     | 64        | 0.76%   |
| Ubuntu Budgie | 57        | 0.67%   |
| Ubuntu Unity  | 50        | 0.59%   |
| SteamOS       | 50        | 0.59%   |
| LMDE          | 50        | 0.59%   |
| Kali          | 48        | 0.57%   |
| Lubuntu       | 44        | 0.52%   |
| MX            | 30        | 0.36%   |
| EndeavourOS   | 23        | 0.27%   |
| Clear Linux   | 23        | 0.27%   |
| Peppermint    | 17        | 0.2%    |
| Garuda Linux  | 17        | 0.2%    |
| CentOS        | 16        | 0.19%   |
| Parrot        | 14        | 0.17%   |
| LinuxFX       | 11        | 0.13%   |
| Deepin        | 9         | 0.11%   |
| Void Linux    | 7         | 0.08%   |
| TUXEDO OS     | 7         | 0.08%   |
| RHEL          | 7         | 0.08%   |
| Ubuntu Studio | 6         | 0.07%   |
| Siduction     | 6         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 243       | 2.43%   |
| 5.16.7-desktop-1omv4003  | 215       | 2.15%   |
| 5.4.0-42-generic         | 157       | 1.57%   |
| 5.4.0-58-generic         | 119       | 1.19%   |
| 5.15.0-56-generic        | 111       | 1.11%   |
| 5.4.0-91-generic         | 104       | 1.04%   |
| 5.4.0-48-generic         | 93        | 0.93%   |
| 5.4.0-52-generic         | 90        | 0.9%    |
| 5.15.0-52-generic        | 78        | 0.78%   |
| 5.15.0-46-generic        | 77        | 0.77%   |
| 5.8.0-43-generic         | 66        | 0.66%   |
| 5.4.0-26-generic         | 62        | 0.62%   |
| 5.15.0-48-generic        | 62        | 0.62%   |
| 5.13.0-39-generic        | 61        | 0.61%   |
| 5.13.0-28-generic        | 60        | 0.6%    |
| 5.11.0-38-generic        | 60        | 0.6%    |
| 5.4.0-56-generic         | 59        | 0.59%   |
| 5.4.0-65-generic         | 58        | 0.58%   |
| 5.4.0-72-generic         | 57        | 0.57%   |
| 5.11.0-37-generic        | 57        | 0.57%   |
| 5.11.0-27-generic        | 57        | 0.57%   |
| 5.4.0-74-generic         | 56        | 0.56%   |
| 5.4.0-54-generic         | 56        | 0.56%   |
| 5.15.0-53-generic        | 56        | 0.56%   |
| 5.11.0-40-generic        | 56        | 0.56%   |
| 4.18.16-desktop-1bP      | 56        | 0.56%   |
| 5.4.0-33-generic         | 55        | 0.55%   |
| 5.4.0-29-generic         | 55        | 0.55%   |
| 5.4.0-40-generic         | 53        | 0.53%   |
| 5.3.0-40-generic         | 52        | 0.52%   |
| 5.4.0-47-generic         | 51        | 0.51%   |
| 5.3.0-28-generic         | 51        | 0.51%   |
| 5.15.0-47-generic        | 51        | 0.51%   |
| 5.4.0-90-generic         | 50        | 0.5%    |
| 5.4.0-81-generic         | 50        | 0.5%    |
| 5.8.0-59-generic         | 47        | 0.47%   |
| 5.4.0-77-generic         | 47        | 0.47%   |
| 5.4.0-80-generic         | 46        | 0.46%   |
| 5.4.0-73-generic         | 46        | 0.46%   |
| 5.11.0-43-generic        | 46        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 2039      | 22.16%  |
| 5.15.0  | 647       | 7.03%   |
| 4.15.0  | 599       | 6.51%   |
| 5.8.0   | 597       | 6.49%   |
| 5.11.0  | 580       | 6.3%    |
| 5.13.0  | 552       | 6%      |
| 5.3.0   | 387       | 4.21%   |
| 5.10.0  | 269       | 2.92%   |
| 5.0.0   | 250       | 2.72%   |
| 5.10.14 | 245       | 2.66%   |
| 5.16.7  | 218       | 2.37%   |
| 4.18.0  | 207       | 2.25%   |
| 4.19.0  | 94        | 1.02%   |
| 5.19.0  | 63        | 0.68%   |
| 4.18.16 | 60        | 0.65%   |
| 5.14.0  | 42        | 0.46%   |
| 4.9.20  | 36        | 0.39%   |
| 5.3.18  | 33        | 0.36%   |
| 5.18.0  | 33        | 0.36%   |
| 4.9.60  | 31        | 0.34%   |
| 5.17.5  | 29        | 0.32%   |
| 4.4.0   | 28        | 0.3%    |
| 5.9.16  | 27        | 0.29%   |
| 5.6.14  | 27        | 0.29%   |
| 5.6.0   | 27        | 0.29%   |
| 6.0.0   | 26        | 0.28%   |
| 5.16.0  | 25        | 0.27%   |
| 5.8.16  | 24        | 0.26%   |
| 5.17.1  | 20        | 0.22%   |
| 5.18.10 | 19        | 0.21%   |
| 5.17.0  | 19        | 0.21%   |
| 5.9.11  | 18        | 0.2%    |
| 5.7.0   | 18        | 0.2%    |
| 4.13.0  | 18        | 0.2%    |
| 6.0.2   | 17        | 0.18%   |
| 5.9.0   | 17        | 0.18%   |
| 4.9.0   | 17        | 0.18%   |
| 5.9.8   | 16        | 0.17%   |
| 5.19.5  | 16        | 0.17%   |
| 5.12.4  | 16        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 2150      | 23.64%  |
| 5.15    | 843       | 9.27%   |
| 5.8     | 713       | 7.84%   |
| 5.10    | 670       | 7.37%   |
| 5.11    | 664       | 7.3%    |
| 5.13    | 628       | 6.9%    |
| 4.15    | 603       | 6.63%   |
| 5.3     | 457       | 5.02%   |
| 5.16    | 333       | 3.66%   |
| 4.18    | 276       | 3.03%   |
| 5.0     | 258       | 2.84%   |
| 5.19    | 153       | 1.68%   |
| 6.0     | 133       | 1.46%   |
| 5.9     | 133       | 1.46%   |
| 4.9     | 128       | 1.41%   |
| 5.6     | 122       | 1.34%   |
| 4.19    | 118       | 1.3%    |
| 5.17    | 112       | 1.23%   |
| 5.18    | 108       | 1.19%   |
| 5.14    | 106       | 1.17%   |
| 5.12    | 80        | 0.88%   |
| 5.7     | 71        | 0.78%   |
| 5.5     | 51        | 0.56%   |
| 4.4     | 31        | 0.34%   |
| 5.1     | 25        | 0.27%   |
| 4.1     | 22        | 0.24%   |
| 4.13    | 19        | 0.21%   |
| 5.2     | 18        | 0.2%    |
| 4.12    | 16        | 0.18%   |
| 6.1     | 14        | 0.15%   |
| 4.14    | 9         | 0.1%    |
| 4.20    | 7         | 0.08%   |
| 4.8     | 4         | 0.04%   |
| 4.17    | 4         | 0.04%   |
| 3.10    | 4         | 0.04%   |
| 4.11    | 3         | 0.03%   |
| 4.10    | 2         | 0.02%   |
| 5.4.104 | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| 4.6     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 7892      | 96%     |
| i686    | 320       | 3.89%   |
| aarch64 | 4         | 0.05%   |
| ppc     | 3         | 0.04%   |
| armv7l  | 2         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 3450      | 40.34%  |
| KDE5                         | 1307      | 15.28%  |
| Unknown                      | 964       | 11.27%  |
| X-Cinnamon                   | 925       | 10.82%  |
| XFCE                         | 691       | 8.08%   |
| MATE                         | 275       | 3.22%   |
| KDE                          | 221       | 2.58%   |
| Cinnamon                     | 148       | 1.73%   |
| KDE4                         | 106       | 1.24%   |
| Pantheon                     | 75        | 0.88%   |
| Budgie                       | 68        | 0.8%    |
| LXQt                         | 61        | 0.71%   |
| Unity                        | 54        | 0.63%   |
| i3                           | 48        | 0.56%   |
| LXDE                         | 36        | 0.42%   |
| GNOME Flashback              | 21        | 0.25%   |
| Deepin                       | 19        | 0.22%   |
| sway                         | 12        | 0.14%   |
| lightdm-xsession             | 12        | 0.14%   |
| awesome                      | 10        | 0.12%   |
| GNOME Classic                | 8         | 0.09%   |
| herbstluftwm                 | 5         | 0.06%   |
| xmonad                       | 4         | 0.05%   |
| Trinity                      | 4         | 0.05%   |
| openbox                      | 4         | 0.05%   |
| bspwm                        | 4         | 0.05%   |
| Enlightenment                | 3         | 0.04%   |
| DWM                          | 3         | 0.04%   |
| qtile                        | 2         | 0.02%   |
| leftwm                       | 2         | 0.02%   |
| default                      | 2         | 0.02%   |
| xubuntu                      | 1         | 0.01%   |
| x-session-manager            | 1         | 0.01%   |
| nxde                         | 1         | 0.01%   |
| KDE:old                      | 1         | 0.01%   |
| icewm                        | 1         | 0.01%   |
| GNOME-Subgraph-Classic:GNOME | 1         | 0.01%   |
| fluxbox                      | 1         | 0.01%   |
| cwm                          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 6786      | 80.57%  |
| Wayland     | 1038      | 12.32%  |
| Unknown     | 520       | 6.17%   |
| Tty         | 78        | 0.93%   |
| Unspecified | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4318      | 50.59%  |
| SDDM    | 1152      | 13.5%   |
| LightDM | 904       | 10.59%  |
| GDM3    | 825       | 9.66%   |
| GDM     | 822       | 9.63%   |
| TDM     | 366       | 4.29%   |
| KDM     | 107       | 1.25%   |
| SLiM    | 14        | 0.16%   |
| XDM     | 13        | 0.15%   |
| NODM    | 5         | 0.06%   |
| LXDM    | 4         | 0.05%   |
| GREETD  | 3         | 0.04%   |
| MDM     | 2         | 0.02%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| de_DE       | 5289      | 63.08%  |
| en_US       | 1488      | 17.75%  |
| Unknown     | 1082      | 12.9%   |
| en_GB       | 137       | 1.63%   |
| C           | 96        | 1.14%   |
| ru_RU       | 45        | 0.54%   |
| pl_PL       | 30        | 0.36%   |
| en_DE       | 24        | 0.29%   |
| it_IT       | 19        | 0.23%   |
| POSIX       | 15        | 0.18%   |
| fr_FR       | 13        | 0.16%   |
| es_ES       | 13        | 0.16%   |
| de_AT       | 9         | 0.11%   |
| hu_HU       | 8         | 0.1%    |
| C.UTF8      | 8         | 0.1%    |
| ro_RO       | 7         | 0.08%   |
| en_CA       | 7         | 0.08%   |
| de_CH       | 6         | 0.07%   |
| ru_UA       | 5         | 0.06%   |
| pt_BR       | 5         | 0.06%   |
| en_IN       | 5         | 0.06%   |
| en_IE       | 5         | 0.06%   |
| en_AU       | 5         | 0.06%   |
| en_AG       | 5         | 0.06%   |
| nl_NL       | 4         | 0.05%   |
| en_DK       | 4         | 0.05%   |
| bg_BG       | 4         | 0.05%   |
| tr_TR       | 3         | 0.04%   |
| sk_SK       | 3         | 0.04%   |
| nds_DE      | 3         | 0.04%   |
| ja_JP       | 2         | 0.02%   |
| en_SG       | 2         | 0.02%   |
| el_GR       | 2         | 0.02%   |
| de_LI       | 2         | 0.02%   |
| de_IT       | 2         | 0.02%   |
| de_DE.utf-8 | 2         | 0.02%   |
| de_BE       | 2         | 0.02%   |
| Default     | 2         | 0.02%   |
| cs_CZ       | 2         | 0.02%   |
| zh_TW       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 4347      | 51.88%  |
| EFI  | 4032      | 48.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 6667      | 79.91%  |
| Overlay  | 616       | 7.38%   |
| Btrfs    | 543       | 6.51%   |
| Unknown  | 342       | 4.1%    |
| Xfs      | 75        | 0.9%    |
| Zfs      | 40        | 0.48%   |
| Ext2     | 23        | 0.28%   |
| F2fs     | 14        | 0.17%   |
| Ext3     | 11        | 0.13%   |
| Tmpfs    | 5         | 0.06%   |
| Reiserfs | 2         | 0.02%   |
| Aufs     | 2         | 0.02%   |
| XXXXXXX  | 1         | 0.01%   |
| Rootfs   | 1         | 0.01%   |
| OveXlay  | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4828      | 57.69%  |
| GPT     | 2624      | 31.35%  |
| MBR     | 917       | 10.96%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7312      | 87.85%  |
| Yes       | 1011      | 12.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6188      | 74.21%  |
| Yes       | 2151      | 25.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2113      | 25.72%  |
| Hewlett-Packard     | 1220      | 14.85%  |
| Dell                | 978       | 11.91%  |
| Acer                | 895       | 10.9%   |
| ASUSTek Computer    | 698       | 8.5%    |
| Medion              | 266       | 3.24%   |
| Toshiba             | 225       | 2.74%   |
| Fujitsu             | 190       | 2.31%   |
| Samsung Electronics | 185       | 2.25%   |
| Apple               | 172       | 2.09%   |
| TUXEDO              | 147       | 1.79%   |
| Sony                | 144       | 1.75%   |
| MSI                 | 124       | 1.51%   |
| HUAWEI              | 89        | 1.08%   |
| Notebook            | 84        | 1.02%   |
| Fujitsu Siemens     | 81        | 0.99%   |
| Packard Bell        | 70        | 0.85%   |
| Schenker            | 56        | 0.68%   |
| Valve               | 51        | 0.62%   |
| Wortmann AG         | 38        | 0.46%   |
| Unknown             | 37        | 0.45%   |
| TrekStor            | 21        | 0.26%   |
| IBM                 | 16        | 0.19%   |
| Google              | 16        | 0.19%   |
| Alienware           | 15        | 0.18%   |
| Timi                | 14        | 0.17%   |
| eMachines           | 14        | 0.17%   |
| Clevo               | 14        | 0.17%   |
| Razer               | 13        | 0.16%   |
| Panasonic           | 13        | 0.16%   |
| AXDIA International | 13        | 0.16%   |
| LG Electronics      | 12        | 0.15%   |
| Gigabyte Technology | 12        | 0.15%   |
| Framework           | 11        | 0.13%   |
| Chuwi               | 11        | 0.13%   |
| LincPlus            | 8         | 0.1%    |
| Tactus              | 7         | 0.09%   |
| AMI                 | 7         | 0.09%   |
| Jumper              | 5         | 0.06%   |
| CSL-Computer        | 5         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 100       | 1.22%   |
| Valve Jupiter                 | 51        | 0.62%   |
| HP Notebook                   | 43        | 0.52%   |
| ASUS P50IJ                    | 29        | 0.35%   |
| Lenovo IdeaPad 5 15ARE05 81YQ | 25        | 0.3%    |
| HP 255 G7 Notebook PC         | 23        | 0.28%   |
| Dell Latitude E6420           | 23        | 0.28%   |
| Dell Latitude E6410           | 20        | 0.24%   |
| Dell XPS 15 9570              | 19        | 0.23%   |
| Dell Latitude E6430           | 19        | 0.23%   |
| Acer Swift SF114-34           | 18        | 0.22%   |
| HP Laptop 17-ca1xxx           | 17        | 0.21%   |
| HP Laptop 17-ca0xxx           | 17        | 0.21%   |
| HP EliteBook 8470p            | 17        | 0.21%   |
| HP EliteBook 8460p            | 17        | 0.21%   |
| Dell XPS 13 9370              | 17        | 0.21%   |
| HP Pavilion 17                | 16        | 0.19%   |
| HP 250 G7 Notebook PC         | 16        | 0.19%   |
| Dell Latitude E6540           | 16        | 0.19%   |
| HP Pavilion Notebook          | 15        | 0.18%   |
| HP Pavilion g7                | 15        | 0.18%   |
| HP Pavilion dv7               | 15        | 0.18%   |
| HP Laptop 15s-eq2xxx          | 15        | 0.18%   |
| Dell XPS 15 9500              | 15        | 0.18%   |
| Acer Aspire 7750G             | 15        | 0.18%   |
| HP ProBook 650 G1             | 14        | 0.17%   |
| HP Laptop 15-db1xxx           | 14        | 0.17%   |
| Dell XPS 15 7590              | 14        | 0.17%   |
| Dell Latitude E7470           | 14        | 0.17%   |
| Dell Latitude E6520           | 14        | 0.17%   |
| Lenovo G710 20252             | 13        | 0.16%   |
| Lenovo G50-70 20351           | 13        | 0.16%   |
| HUAWEI NBLK-WAX9X             | 13        | 0.16%   |
| HP Pavilion g6                | 13        | 0.16%   |
| HP Pavilion dv6               | 13        | 0.16%   |
| HP EliteBook 8440p            | 13        | 0.16%   |
| HP EliteBook 840 G5           | 13        | 0.16%   |
| Dell XPS 13 9380              | 13        | 0.16%   |
| Dell XPS 13 7390              | 13        | 0.16%   |
| Dell Latitude D630            | 13        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 1398      | 17.02%  |
| Acer Aspire              | 613       | 7.46%   |
| Dell Latitude            | 446       | 5.43%   |
| Lenovo IdeaPad           | 329       | 4.01%   |
| HP EliteBook             | 267       | 3.25%   |
| HP Laptop                | 197       | 2.4%    |
| HP Pavilion              | 182       | 2.22%   |
| Toshiba Satellite        | 181       | 2.2%    |
| Fujitsu LIFEBOOK         | 180       | 2.19%   |
| HP ProBook               | 162       | 1.97%   |
| Dell XPS                 | 157       | 1.91%   |
| Dell Inspiron            | 144       | 1.75%   |
| Dell Precision           | 111       | 1.35%   |
| Unknown                  | 100       | 1.22%   |
| Acer Swift               | 86        | 1.05%   |
| HP Compaq                | 80        | 0.97%   |
| ASUS VivoBook            | 80        | 0.97%   |
| Acer TravelMate          | 70        | 0.85%   |
| Packard Bell EasyNote    | 61        | 0.74%   |
| Medion Akoya             | 54        | 0.66%   |
| Dell Vostro              | 53        | 0.65%   |
| Valve Jupiter            | 51        | 0.62%   |
| HP 255                   | 50        | 0.61%   |
| HP 250                   | 47        | 0.57%   |
| HP ZBook                 | 46        | 0.56%   |
| ASUS ZenBook             | 45        | 0.55%   |
| HP Notebook              | 43        | 0.52%   |
| Lenovo Yoga              | 42        | 0.51%   |
| Acer Extensa             | 36        | 0.44%   |
| Fujitsu Siemens AMILO    | 34        | 0.41%   |
| Lenovo ThinkBook         | 29        | 0.35%   |
| ASUS P50IJ               | 29        | 0.35%   |
| Schenker XMG             | 27        | 0.33%   |
| Fujitsu Siemens LIFEBOOK | 27        | 0.33%   |
| Acer Nitro               | 27        | 0.33%   |
| Lenovo Legion            | 26        | 0.32%   |
| HP ENVY                  | 26        | 0.32%   |
| TUXEDO InfinityBook      | 24        | 0.29%   |
| Dell System              | 22        | 0.27%   |
| ASUS ROG                 | 22        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 724       | 8.81%   |
| 2012    | 710       | 8.64%   |
| 2011    | 693       | 8.44%   |
| 2019    | 690       | 8.4%    |
| 2018    | 667       | 8.12%   |
| 2013    | 550       | 6.7%    |
| 2010    | 523       | 6.37%   |
| 2021    | 486       | 5.92%   |
| 2017    | 474       | 5.77%   |
| 2014    | 467       | 5.69%   |
| 2015    | 443       | 5.39%   |
| 2016    | 438       | 5.33%   |
| 2008    | 429       | 5.22%   |
| 2009    | 374       | 4.55%   |
| 2007    | 219       | 2.67%   |
| 2022    | 147       | 1.79%   |
| 2006    | 102       | 1.24%   |
| 2005    | 40        | 0.49%   |
| Unknown | 21        | 0.26%   |
| 2004    | 10        | 0.12%   |
| 2003    | 3         | 0.04%   |
| 2002    | 2         | 0.02%   |
| 2000    | 1         | 0.01%   |
| 1999    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 8214      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7458      | 90.14%  |
| Enabled  | 816       | 9.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8181      | 99.6%   |
| Yes  | 33        | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2313      | 27.8%   |
| 3.01-4.0    | 2003      | 24.08%  |
| 8.01-16.0   | 1498      | 18.01%  |
| 16.01-24.0  | 1228      | 14.76%  |
| 32.01-64.0  | 466       | 5.6%    |
| 1.01-2.0    | 391       | 4.7%    |
| 2.01-3.0    | 169       | 2.03%   |
| 64.01-256.0 | 86        | 1.03%   |
| 24.01-32.0  | 78        | 0.94%   |
| 0.51-1.0    | 78        | 0.94%   |
| 0.01-0.5    | 7         | 0.08%   |
| Unknown     | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3897      | 42.97%  |
| 2.01-3.0   | 2167      | 23.89%  |
| 3.01-4.0   | 953       | 10.51%  |
| 4.01-8.0   | 914       | 10.08%  |
| 0.51-1.0   | 722       | 7.96%   |
| 8.01-16.0  | 265       | 2.92%   |
| 0.01-0.5   | 110       | 1.21%   |
| 16.01-24.0 | 27        | 0.3%    |
| 24.01-32.0 | 9         | 0.1%    |
| Unknown    | 3         | 0.03%   |
| 32.01-64.0 | 2         | 0.02%   |
| 0          | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6161      | 73.28%  |
| 2      | 1883      | 22.4%   |
| 3      | 232       | 2.76%   |
| 0      | 80        | 0.95%   |
| 4      | 40        | 0.48%   |
| 6      | 5         | 0.06%   |
| 5      | 4         | 0.05%   |
| 9      | 1         | 0.01%   |
| 7      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4518      | 54.66%  |
| Yes       | 3747      | 45.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7022      | 85.2%   |
| No        | 1220      | 14.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8073      | 98.2%   |
| No        | 148       | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5980      | 71.57%  |
| No        | 2375      | 28.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 8214      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Berlin               | 785       | 8.85%   |
| Munich               | 431       | 4.86%   |
| Hamburg              | 330       | 3.72%   |
| Frankfurt am Main    | 259       | 2.92%   |
| Cologne              | 204       | 2.3%    |
| Stuttgart            | 183       | 2.06%   |
| Leipzig              | 142       | 1.6%    |
| Dresden              | 109       | 1.23%   |
| Nuremberg            | 100       | 1.13%   |
| Düsseldorf          | 94        | 1.06%   |
| Essen                | 93        | 1.05%   |
| Mannheim             | 84        | 0.95%   |
| Dortmund             | 76        | 0.86%   |
| Karlsruhe            | 70        | 0.79%   |
| Duisburg             | 69        | 0.78%   |
| Bremen               | 65        | 0.73%   |
| Darmstadt            | 55        | 0.62%   |
| Bielefeld            | 55        | 0.62%   |
| Bonn                 | 52        | 0.59%   |
| Hanover              | 51        | 0.57%   |
| Wuppertal            | 49        | 0.55%   |
| Münster             | 49        | 0.55%   |
| Braunschweig         | 49        | 0.55%   |
| Wiesbaden            | 48        | 0.54%   |
| Augsburg             | 44        | 0.5%    |
| Regensburg           | 42        | 0.47%   |
| Mainz                | 42        | 0.47%   |
| Bochum               | 40        | 0.45%   |
| Halle                | 39        | 0.44%   |
| Freiburg im Breisgau | 38        | 0.43%   |
| Aachen               | 37        | 0.42%   |
| Chemnitz             | 36        | 0.41%   |
| Bamberg              | 35        | 0.39%   |
| Kiel                 | 34        | 0.38%   |
| Garbsen              | 30        | 0.34%   |
| Erfurt               | 29        | 0.33%   |
| Rüsselsheim am Main | 28        | 0.32%   |
| Potsdam              | 27        | 0.3%    |
| Kassel               | 27        | 0.3%    |
| Hemmingen            | 27        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2170      | 2887   | 21.65%  |
| WDC                         | 1038      | 1317   | 10.36%  |
| Seagate                     | 983       | 1260   | 9.81%   |
| SanDisk                     | 831       | 1115   | 8.29%   |
| Toshiba                     | 802       | 1017   | 8%      |
| Unknown                     | 575       | 779    | 5.74%   |
| SK hynix                    | 405       | 507    | 4.04%   |
| Crucial                     | 374       | 490    | 3.73%   |
| Hitachi                     | 341       | 413    | 3.4%    |
| Kingston                    | 307       | 372    | 3.06%   |
| Intel                       | 279       | 363    | 2.78%   |
| Micron Technology           | 242       | 308    | 2.41%   |
| Intenso                     | 242       | 306    | 2.41%   |
| HGST                        | 207       | 262    | 2.07%   |
| Fujitsu                     | 100       | 128    | 1%      |
| Apple                       | 69        | 81     | 0.69%   |
| Transcend                   | 68        | 84     | 0.68%   |
| KIOXIA                      | 67        | 83     | 0.67%   |
| Phison                      | 61        | 83     | 0.61%   |
| LITEON                      | 60        | 62     | 0.6%    |
| A-DATA Technology           | 51        | 59     | 0.51%   |
| LITEONIT                    | 41        | 51     | 0.41%   |
| OCZ                         | 34        | 45     | 0.34%   |
| China                       | 28        | 32     | 0.28%   |
| Unknown                     | 27        | 30     | 0.27%   |
| Patriot                     | 23        | 27     | 0.23%   |
| SPCC                        | 22        | 26     | 0.22%   |
| Micron/Crucial Technology   | 22        | 24     | 0.22%   |
| JMicron Technology          | 22        | 22     | 0.22%   |
| Leven                       | 20        | 29     | 0.2%    |
| Lenovo                      | 19        | 23     | 0.19%   |
| INNOVATION IT               | 19        | 23     | 0.19%   |
| Netac                       | 18        | 22     | 0.18%   |
| Silicon Motion              | 17        | 19     | 0.17%   |
| UMIS                        | 16        | 29     | 0.16%   |
| Kingston Technology Company | 15        | 17     | 0.15%   |
| Hewlett-Packard             | 15        | 21     | 0.15%   |
| ASMT                        | 14        | 16     | 0.14%   |
| SABRENT                     | 13        | 14     | 0.13%   |
| PNY                         | 13        | 17     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 117       | 1.12%   |
| Unknown MMC Card  32GB                              | 107       | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 102       | 0.98%   |
| Samsung SSD 850 EVO 500GB                           | 102       | 0.98%   |
| Samsung NVMe SSD Drive 512GB                        | 99        | 0.95%   |
| SanDisk NVMe SSD Drive 512GB                        | 95        | 0.91%   |
| Samsung SSD 860 EVO 500GB                           | 91        | 0.87%   |
| Seagate ST9500325AS 500GB                           | 86        | 0.82%   |
| Samsung SSD 850 EVO 250GB                           | 85        | 0.81%   |
| Unknown MMC Card  64GB                              | 83        | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB                      | 78        | 0.75%   |
| SK hynix NVMe SSD Drive 512GB                       | 63        | 0.6%    |
| Toshiba MQ01ABF050 500GB                            | 62        | 0.59%   |
| SanDisk SSD PLUS 240GB                              | 62        | 0.59%   |
| Samsung SSD 860 EVO 1TB                             | 57        | 0.55%   |
| Crucial CT500MX500SSD1 500GB                        | 57        | 0.55%   |
| Samsung NVMe SSD Drive 1024GB                       | 56        | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 55        | 0.53%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 54        | 0.52%   |
| Samsung SSD 860 EVO 250GB                           | 52        | 0.5%    |
| Unknown MMC Card  128GB                             | 51        | 0.49%   |
| Seagate ST500LT012-1DG142 500GB                     | 50        | 0.48%   |
| Intel NVMe SSD Drive 512GB                          | 49        | 0.47%   |
| Toshiba MQ04ABF100 1TB                              | 48        | 0.46%   |
| SanDisk SSD PLUS 1000GB                             | 44        | 0.42%   |
| Samsung NVMe SSD Drive 500GB                        | 44        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                         | 44        | 0.42%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.41%   |
| Toshiba NVMe SSD Drive 512GB                        | 42        | 0.4%    |
| HGST HTS721010A9E630 1TB                            | 42        | 0.4%    |
| Samsung SSD 840 EVO 500GB                           | 41        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                        | 41        | 0.39%   |
| HGST HTS725050A7E630 500GB                          | 40        | 0.38%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 37        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                        | 37        | 0.35%   |
| Samsung SSD 840 EVO 250GB                           | 37        | 0.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 37        | 0.35%   |
| HGST HTS541010A9E680 1TB                            | 37        | 0.35%   |
| Intenso SSD SATAIII 128GB                           | 36        | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 35        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 958       | 1226   | 31.61%  |
| WDC                 | 710       | 904    | 23.42%  |
| Toshiba             | 501       | 625    | 16.53%  |
| Hitachi             | 341       | 413    | 11.25%  |
| HGST                | 207       | 262    | 6.83%   |
| Samsung Electronics | 109       | 138    | 3.6%    |
| Fujitsu             | 100       | 128    | 3.3%    |
| Unknown             | 29        | 65     | 0.96%   |
| Intenso             | 21        | 28     | 0.69%   |
| ASMT                | 11        | 12     | 0.36%   |
| IBM/Hitachi         | 8         | 8      | 0.26%   |
| Apple               | 8         | 8      | 0.26%   |
| USB3.0              | 7         | 8      | 0.23%   |
| ASMedia             | 4         | 5      | 0.13%   |
| USB                 | 3         | 3      | 0.1%    |
| SILICONMOTION       | 2         | 3      | 0.07%   |
| LIO-ORG             | 2         | 8      | 0.07%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| WD MediaMax         | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| IB-AC703            | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 2      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1250      | 1633   | 32.88%  |
| SanDisk             | 593       | 831    | 15.6%   |
| Crucial             | 350       | 464    | 9.21%   |
| Kingston            | 204       | 256    | 5.37%   |
| Intenso             | 184       | 224    | 4.84%   |
| WDC                 | 128       | 160    | 3.37%   |
| Micron Technology   | 122       | 147    | 3.21%   |
| Toshiba             | 113       | 136    | 2.97%   |
| SK hynix            | 104       | 125    | 2.74%   |
| Intel               | 90        | 113    | 2.37%   |
| Transcend           | 66        | 82     | 1.74%   |
| LITEON              | 57        | 59     | 1.5%    |
| Apple               | 48        | 54     | 1.26%   |
| A-DATA Technology   | 42        | 48     | 1.1%    |
| LITEONIT            | 41        | 51     | 1.08%   |
| OCZ                 | 34        | 45     | 0.89%   |
| China               | 28        | 32     | 0.74%   |
| Patriot             | 23        | 27     | 0.6%    |
| SPCC                | 20        | 23     | 0.53%   |
| INNOVATION IT       | 19        | 23     | 0.5%    |
| Netac               | 18        | 22     | 0.47%   |
| Leven               | 17        | 23     | 0.45%   |
| JMicron Technology  | 15        | 16     | 0.39%   |
| Hewlett-Packard     | 13        | 14     | 0.34%   |
| Phison              | 12        | 14     | 0.32%   |
| PNY                 | 11        | 15     | 0.29%   |
| Apacer              | 11        | 13     | 0.29%   |
| Unknown             | 10        | 10     | 0.26%   |
| Dogfish             | 10        | 17     | 0.26%   |
| KingSpec            | 8         | 11     | 0.21%   |
| Emtec               | 8         | 9      | 0.21%   |
| Corsair             | 8         | 9      | 0.21%   |
| Unknown             | 8         | 8      | 0.21%   |
| Seagate             | 7         | 9      | 0.18%   |
| KingDian            | 7         | 8      | 0.18%   |
| TrekStor            | 6         | 8      | 0.16%   |
| Lexar               | 6         | 8      | 0.16%   |
| Plextor             | 5         | 6      | 0.13%   |
| BIWIN               | 5         | 5      | 0.13%   |
| Verbatim            | 4         | 9      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 3545      | 4890   | 36.91%  |
| HDD     | 2932      | 3855   | 30.53%  |
| NVMe    | 2422      | 3256   | 25.22%  |
| MMC     | 568       | 739    | 5.91%   |
| Unknown | 137       | 177    | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5857      | 8464   | 63.88%  |
| NVMe | 2414      | 3234   | 26.33%  |
| MMC  | 568       | 739    | 6.19%   |
| SAS  | 330       | 480    | 3.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4626      | 6321   | 71.96%  |
| 0.51-1.0   | 1580      | 2102   | 24.58%  |
| 1.01-2.0   | 167       | 226    | 2.6%    |
| 3.01-4.0   | 37        | 65     | 0.58%   |
| 4.01-10.0  | 18        | 30     | 0.28%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2650      | 30.6%   |
| 251-500        | 2271      | 26.22%  |
| 501-1000       | 1208      | 13.95%  |
| 1-20           | 606       | 7%      |
| 51-100         | 605       | 6.99%   |
| 1001-2000      | 451       | 5.21%   |
| 21-50          | 369       | 4.26%   |
| Unknown        | 252       | 2.91%   |
| More than 3000 | 143       | 1.65%   |
| 2001-3000      | 105       | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3696      | 40.69%  |
| 21-50          | 1710      | 18.83%  |
| 101-250        | 1141      | 12.56%  |
| 51-100         | 1115      | 12.28%  |
| 251-500        | 634       | 6.98%   |
| 501-1000       | 327       | 3.6%    |
| Unknown        | 252       | 2.77%   |
| 1001-2000      | 144       | 1.59%   |
| More than 3000 | 41        | 0.45%   |
| 2001-3000      | 20        | 0.22%   |
| 0              | 3         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 9         | 11     | 2.2%    |
| Seagate ST9500325AS 500GB                           | 9         | 13     | 2.2%    |
| Seagate ST500LT012-9WS142 500GB                     | 7         | 8      | 1.71%   |
| Seagate ST500LM000-SSHD-8GB                         | 7         | 7      | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 10     | 1.71%   |
| Seagate ST9320325AS 320GB                           | 6         | 7      | 1.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 6         | 6      | 1.47%   |
| Seagate ST500LM000-1EJ162 500GB                     | 6         | 8      | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 6      | 1.47%   |
| HGST HTS725050A7E630 500GB                          | 6         | 6      | 1.47%   |
| HGST HTS545050A7E680 500GB                          | 6         | 10     | 1.47%   |
| Crucial M4-CT256M4SSD3 256GB                        | 5         | 5      | 1.22%   |
| Seagate ST9500420AS 500GB                           | 4         | 4      | 0.98%   |
| Seagate ST9250315AS 250GB                           | 4         | 5      | 0.98%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 4         | 4      | 0.98%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 4      | 0.98%   |
| Hitachi HTS545050A7E380 500GB                       | 4         | 4      | 0.98%   |
| Hitachi HTS541616J9SA00 160GB                       | 4         | 5      | 0.98%   |
| HGST HTS545050A7E380 500GB                          | 4         | 7      | 0.98%   |
| Fujitsu MHZ2320BH G2 320GB                          | 4         | 5      | 0.98%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 3         | 3      | 0.73%   |
| Toshiba MQ01ACF050 500GB                            | 3         | 3      | 0.73%   |
| Toshiba MQ01ABD075 752GB                            | 3         | 3      | 0.73%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 3         | 3      | 0.73%   |
| Seagate ST9750423AS 752GB                           | 3         | 4      | 0.73%   |
| Seagate ST2000LM007-1R8174 2TB                      | 3         | 3      | 0.73%   |
| SanDisk SSD PLUS 1000GB                             | 3         | 3      | 0.73%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 0.73%   |
| Hitachi HTS547564A9E384 640GB                       | 3         | 3      | 0.73%   |
| HGST HTS541010A9E680 1TB                            | 3         | 3      | 0.73%   |
| WDC WD7500BPVX-22JC3T0 752GB                        | 2         | 2      | 0.49%   |
| WDC WD5000BPVT-22HXZT1 500GB                        | 2         | 2      | 0.49%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 2         | 2      | 0.49%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 2         | 2      | 0.49%   |
| Toshiba MK5059GSXP 500GB                            | 2         | 2      | 0.49%   |
| Toshiba MK3259GSXP 320GB                            | 2         | 2      | 0.49%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 2      | 0.49%   |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 2         | 2      | 0.49%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 2         | 2      | 0.49%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB             | 2         | 4      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 103       | 122    | 25.31%  |
| Hitachi             | 51        | 57     | 12.53%  |
| WDC                 | 45        | 49     | 11.06%  |
| Toshiba             | 40        | 44     | 9.83%   |
| Samsung Electronics | 32        | 37     | 7.86%   |
| HGST                | 22        | 29     | 5.41%   |
| SanDisk             | 21        | 24     | 5.16%   |
| SK hynix            | 16        | 18     | 3.93%   |
| Crucial             | 16        | 16     | 3.93%   |
| Micron Technology   | 15        | 17     | 3.69%   |
| Fujitsu             | 15        | 17     | 3.69%   |
| Intel               | 8         | 8      | 1.97%   |
| Transcend           | 4         | 4      | 0.98%   |
| Kingston            | 4         | 4      | 0.98%   |
| LITEONIT            | 2         | 4      | 0.49%   |
| Intenso             | 2         | 2      | 0.49%   |
| Apple               | 2         | 2      | 0.49%   |
| A-DATA Technology   | 2         | 3      | 0.49%   |
| PNY                 | 1         | 1      | 0.25%   |
| Phison              | 1         | 1      | 0.25%   |
| LITEON              | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |
| China               | 1         | 1      | 0.25%   |
| ASMedia             | 1         | 1      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 103       | 122    | 36.92%  |
| Hitachi             | 51        | 57     | 18.28%  |
| WDC                 | 39        | 43     | 13.98%  |
| Toshiba             | 34        | 36     | 12.19%  |
| HGST                | 22        | 29     | 7.89%   |
| Fujitsu             | 15        | 17     | 5.38%   |
| Samsung Electronics | 13        | 16     | 4.66%   |
| IBM/Hitachi         | 1         | 1      | 0.36%   |
| ASMedia             | 1         | 1      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 278       | 322    | 68.64%  |
| SSD  | 110       | 121    | 27.16%  |
| NVMe | 17        | 21     | 4.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-00A0RT0 500GB                   | 1         | 1      | 9.09%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB           | 1         | 1      | 9.09%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 9.09%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 9.09%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 9.09%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 9.09%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 9.09%   |
| Intel SSDSCKGF256A5 SATA 256GB                 | 1         | 1      | 9.09%   |
| Intel SSDSA2BW160G3 160GB                      | 1         | 1      | 9.09%   |
| Hitachi HTS541010G9SA00 100GB                  | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 18.18%  |
| Toshiba           | 2         | 2      | 18.18%  |
| Seagate           | 2         | 2      | 18.18%  |
| Intel             | 2         | 2      | 18.18%  |
| Micron Technology | 1         | 1      | 9.09%   |
| Hitachi           | 1         | 1      | 9.09%   |
| HGST              | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5253      | 8448   | 60.89%  |
| Works    | 2960      | 3994   | 34.31%  |
| Malfunc  | 403       | 464    | 4.67%   |
| Failed   | 11        | 11     | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5846      | 62.87%  |
| Samsung Electronics              | 912       | 9.81%   |
| AMD                              | 910       | 9.79%   |
| SanDisk                          | 419       | 4.51%   |
| SK hynix                         | 286       | 3.08%   |
| Toshiba America Info Systems     | 192       | 2.06%   |
| Micron Technology                | 121       | 1.3%    |
| Kingston Technology Company      | 116       | 1.25%   |
| Nvidia                           | 91        | 0.98%   |
| KIOXIA                           | 71        | 0.76%   |
| Phison Electronics               | 65        | 0.7%    |
| Micron/Crucial Technology        | 45        | 0.48%   |
| Union Memory (Shenzhen)          | 31        | 0.33%   |
| Silicon Integrated Systems [SiS] | 22        | 0.24%   |
| Silicon Motion                   | 20        | 0.22%   |
| Lenovo                           | 19        | 0.2%    |
| ADATA Technology                 | 17        | 0.18%   |
| VIA Technologies                 | 14        | 0.15%   |
| Silicon Image                    | 12        | 0.13%   |
| Lite-On Technology               | 12        | 0.13%   |
| Solid State Storage Technology   | 11        | 0.12%   |
| Apple                            | 11        | 0.12%   |
| Marvell Technology Group         | 9         | 0.1%    |
| JMicron Technology               | 9         | 0.1%    |
| Seagate Technology               | 8         | 0.09%   |
| O2 Micro                         | 7         | 0.08%   |
| Shenzhen Longsys Electronics     | 5         | 0.05%   |
| Realtek Semiconductor            | 4         | 0.04%   |
| ASMedia Technology               | 4         | 0.04%   |
| Yangtze Memory Technologies      | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |
| Unknown                          | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 722       | 7.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 709       | 7.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 610       | 6.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 544       | 5.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 519       | 5.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 447       | 4.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 368       | 3.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 302       | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 282       | 2.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 278       | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 231       | 2.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 200       | 2%      |
| Samsung NVMe SSD Controller 980                                                  | 199       | 1.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 169       | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 169       | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 153       | 1.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 144       | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                              | 130       | 1.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 128       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 122       | 1.22%   |
| Micron Non-Volatile memory controller                                            | 121       | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 118       | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 113       | 1.13%   |
| Intel SSD 660P Series                                                            | 95        | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 88        | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                            | 86        | 0.86%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 84        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 84        | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 82        | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 81        | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 77        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 77        | 0.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 76        | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 75        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 70        | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 67        | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 63        | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 62        | 0.62%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 62        | 0.62%   |
| Intel Tiger Lake-LP SATA Controller                                              | 61        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5953      | 61.5%   |
| NVMe | 2437      | 25.18%  |
| IDE  | 770       | 7.95%   |
| RAID | 520       | 5.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6746      | 82.13%  |
| AMD          | 1457      | 17.74%  |
| ARM          | 4         | 0.05%   |
| Unknown      | 2         | 0.02%   |
| QUALCOMM     | 1         | 0.01%   |
| PowerBook5,6 | 1         | 0.01%   |
| PowerBook5,4 | 1         | 0.01%   |
| PowerBook3,4 | 1         | 0.01%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 141       | 1.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 135       | 1.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 130       | 1.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 114       | 1.39%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 112       | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 111       | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 106       | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 96        | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 95        | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 92        | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 90        | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 81        | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 81        | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 80        | 0.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 78        | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 73        | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 69        | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 69        | 0.84%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 69        | 0.84%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 64        | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 63        | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 58        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 57        | 0.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 57        | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 56        | 0.68%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 55        | 0.67%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 55        | 0.67%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 54        | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 53        | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 53        | 0.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 52        | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 51        | 0.62%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 51        | 0.62%   |
| AMD Custom APU 0405                           | 51        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 49        | 0.6%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 47        | 0.57%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 46        | 0.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 46        | 0.56%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 46        | 0.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 45        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2122      | 25.82%  |
| Intel Core i7           | 1777      | 21.62%  |
| Intel Core 2 Duo        | 597       | 7.26%   |
| Intel Core i3           | 558       | 6.79%   |
| Other                   | 428       | 5.21%   |
| AMD Ryzen 5             | 349       | 4.25%   |
| Intel Celeron           | 345       | 4.2%    |
| Intel Pentium           | 300       | 3.65%   |
| AMD Ryzen 7             | 288       | 3.5%    |
| Intel Atom              | 216       | 2.63%   |
| Intel Pentium Dual-Core | 95        | 1.16%   |
| AMD Ryzen 7 PRO         | 95        | 1.16%   |
| AMD A6                  | 77        | 0.94%   |
| AMD E                   | 65        | 0.79%   |
| AMD A4                  | 65        | 0.79%   |
| Intel Pentium Silver    | 61        | 0.74%   |
| Intel Core 2            | 60        | 0.73%   |
| Intel Genuine           | 56        | 0.68%   |
| AMD Ryzen 3             | 55        | 0.67%   |
| AMD A8                  | 55        | 0.67%   |
| Intel Pentium Dual      | 51        | 0.62%   |
| Intel Pentium M         | 41        | 0.5%    |
| AMD Turion 64 X2 Mobile | 40        | 0.49%   |
| AMD E2                  | 40        | 0.49%   |
| AMD Ryzen 9             | 28        | 0.34%   |
| Intel Celeron M         | 24        | 0.29%   |
| AMD E1                  | 24        | 0.29%   |
| AMD A10                 | 24        | 0.29%   |
| AMD Ryzen 5 PRO         | 23        | 0.28%   |
| AMD Athlon              | 21        | 0.26%   |
| Intel Core i9           | 20        | 0.24%   |
| AMD Athlon X2           | 17        | 0.21%   |
| Intel Core M            | 16        | 0.19%   |
| AMD Athlon II           | 15        | 0.18%   |
| Intel Xeon              | 13        | 0.16%   |
| AMD Athlon 64 X2        | 13        | 0.16%   |
| Intel Core m3           | 11        | 0.13%   |
| AMD Turion 64 Mobile    | 11        | 0.13%   |
| Intel Core m5           | 9         | 0.11%   |
| AMD Mobile Sempron      | 9         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4430      | 53.89%  |
| 4       | 2575      | 31.32%  |
| 6       | 467       | 5.68%   |
| 8       | 412       | 5.01%   |
| 1       | 272       | 3.31%   |
| 14      | 20        | 0.24%   |
| 12      | 16        | 0.19%   |
| Unknown | 15        | 0.18%   |
| 10      | 10        | 0.12%   |
| 5       | 2         | 0.02%   |
| 16      | 1         | 0.01%   |
| 3       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 8209      | 99.94%  |
| 2       | 2         | 0.02%   |
| Unknown | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5745      | 69.88%  |
| 1       | 2458      | 29.9%   |
| Unknown | 15        | 0.18%   |
| 8       | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7917      | 96.16%  |
| 32-bit         | 164       | 1.99%   |
| Unknown        | 149       | 1.81%   |
| 64-bit         | 3         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1627      | 19.19%  |
| 0x206a7    | 603       | 7.11%   |
| 0x306a9    | 575       | 6.78%   |
| 0x1067a    | 358       | 4.22%   |
| 0x806ea    | 274       | 3.23%   |
| 0x40651    | 271       | 3.2%    |
| 0x306c3    | 268       | 3.16%   |
| 0x406e3    | 265       | 3.13%   |
| 0x20655    | 253       | 2.98%   |
| 0x806ec    | 250       | 2.95%   |
| 0x306d4    | 215       | 2.54%   |
| 0x806c1    | 209       | 2.47%   |
| 0x806e9    | 204       | 2.41%   |
| 0x906ea    | 172       | 2.03%   |
| 0x6fd      | 152       | 1.79%   |
| 0x10676    | 152       | 1.79%   |
| 0x30678    | 123       | 1.45%   |
| 0x08108102 | 120       | 1.42%   |
| 0x20652    | 112       | 1.32%   |
| 0x08600106 | 105       | 1.24%   |
| 0x806eb    | 97        | 1.14%   |
| 0x0a50000c | 95        | 1.12%   |
| 0x08108109 | 92        | 1.09%   |
| 0x406c4    | 91        | 1.07%   |
| 0xa0652    | 89        | 1.05%   |
| 0x506e3    | 87        | 1.03%   |
| 0x906e9    | 86        | 1.01%   |
| 0x08608103 | 79        | 0.93%   |
| 0x706e5    | 77        | 0.91%   |
| 0x06006705 | 68        | 0.8%    |
| 0x08600103 | 67        | 0.79%   |
| 0x506c9    | 65        | 0.77%   |
| 0x05000119 | 61        | 0.72%   |
| 0x706a1    | 58        | 0.68%   |
| 0x106ca    | 53        | 0.63%   |
| 0x07030105 | 50        | 0.59%   |
| 0x106c2    | 48        | 0.57%   |
| 0x406c3    | 47        | 0.55%   |
| 0x6f6      | 43        | 0.51%   |
| 0x6fb      | 41        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1357      | 16.51%  |
| SandyBridge      | 711       | 8.65%   |
| IvyBridge        | 686       | 8.35%   |
| Haswell          | 645       | 7.85%   |
| Penryn           | 575       | 7%      |
| Skylake          | 437       | 5.32%   |
| Westmere         | 435       | 5.29%   |
| Silvermont       | 310       | 3.77%   |
| Core             | 306       | 3.72%   |
| Zen 2            | 284       | 3.46%   |
| Broadwell        | 260       | 3.16%   |
| TigerLake        | 244       | 2.97%   |
| Zen+             | 243       | 2.96%   |
| Unknown          | 232       | 2.82%   |
| Zen 3            | 129       | 1.57%   |
| Icelake          | 124       | 1.51%   |
| Bonnell          | 116       | 1.41%   |
| CometLake        | 115       | 1.4%    |
| Goldmont plus    | 114       | 1.39%   |
| P6               | 101       | 1.23%   |
| Excavator        | 101       | 1.23%   |
| Bobcat           | 96        | 1.17%   |
| Puma             | 81        | 0.99%   |
| K8 Hammer        | 79        | 0.96%   |
| Goldmont         | 79        | 0.96%   |
| Zen              | 70        | 0.85%   |
| Jaguar           | 41        | 0.5%    |
| K10              | 40        | 0.49%   |
| Piledriver       | 35        | 0.43%   |
| Nehalem          | 35        | 0.43%   |
| K10 Llano        | 34        | 0.41%   |
| Alderlake Hybrid | 34        | 0.41%   |
| K8 & K10 hybrid  | 31        | 0.38%   |
| Tremont          | 21        | 0.26%   |
| Steamroller      | 10        | 0.12%   |
| NetBurst         | 6         | 0.07%   |
| K6               | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5868      | 58.34%  |
| Nvidia                           | 2118      | 21.06%  |
| AMD                              | 2045      | 20.33%  |
| Silicon Integrated Systems [SiS] | 13        | 0.13%   |
| VIA Technologies                 | 9         | 0.09%   |
| S3 Graphics                      | 4         | 0.04%   |
| Neomagic                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 653       | 6.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 612       | 5.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 330       | 3.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 319       | 3.06%   |
| Intel UHD Graphics 620                                                                   | 311       | 2.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 283       | 2.72%   |
| AMD Renoir                                                                               | 281       | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 280       | 2.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 272       | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 247       | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 232       | 2.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 223       | 2.14%   |
| Intel HD Graphics 620                                                                    | 223       | 2.14%   |
| Intel HD Graphics 5500                                                                   | 211       | 2.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 208       | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 166       | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 158       | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 152       | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 121       | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 121       | 1.16%   |
| AMD Lucienne                                                                             | 118       | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 106       | 1.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 105       | 1.01%   |
| Intel HD Graphics 530                                                                    | 103       | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 99        | 0.95%   |
| Intel HD Graphics 630                                                                    | 98        | 0.94%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 84        | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 83        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 79        | 0.76%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 65        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 63        | 0.6%    |
| Nvidia GP108M [GeForce MX150]                                                            | 62        | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 62        | 0.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 62        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 62        | 0.59%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 59        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 56        | 0.54%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 56        | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 54        | 0.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 54        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 4113      | 49.96%  |
| 1 x AMD         | 1524      | 18.51%  |
| Intel + Nvidia  | 1448      | 17.59%  |
| 1 x Nvidia      | 567       | 6.89%   |
| Intel + AMD     | 305       | 3.71%   |
| 2 x AMD         | 123       | 1.49%   |
| AMD + Nvidia    | 96        | 1.17%   |
| 2 x Nvidia      | 13        | 0.16%   |
| 1 x SiS         | 13        | 0.16%   |
| Other           | 11        | 0.13%   |
| 1 x VIA         | 9         | 0.11%   |
| 2 x Intel       | 5         | 0.06%   |
| 1 x S3 Graphics | 4         | 0.05%   |
| 1 x Neomagic    | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 7142      | 85.76%  |
| Proprietary | 911       | 10.94%  |
| Unknown     | 275       | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 5083      | 60.17%  |
| 0.01-0.5       | 1182      | 13.99%  |
| 1.01-2.0       | 1052      | 12.45%  |
| 0.51-1.0       | 579       | 6.85%   |
| 3.01-4.0       | 379       | 4.49%   |
| 5.01-6.0       | 92        | 1.09%   |
| 7.01-8.0       | 58        | 0.69%   |
| 2.01-3.0       | 14        | 0.17%   |
| 8.01-16.0      | 8         | 0.09%   |
| More than 64.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1870      | 20.64%  |
| LG Display              | 1449      | 16%     |
| Chimei Innolux          | 1088      | 12.01%  |
| Samsung Electronics     | 921       | 10.17%  |
| BOE                     | 885       | 9.77%   |
| Lenovo                  | 330       | 3.64%   |
| Chi Mei Optoelectronics | 252       | 2.78%   |
| Sharp                   | 221       | 2.44%   |
| Dell                    | 221       | 2.44%   |
| Apple                   | 176       | 1.94%   |
| Goldstar                | 138       | 1.52%   |
| LG Philips              | 117       | 1.29%   |
| BenQ                    | 116       | 1.28%   |
| PANDA                   | 101       | 1.12%   |
| Hewlett-Packard         | 89        | 0.98%   |
| Acer                    | 78        | 0.86%   |
| Ancor Communications    | 72        | 0.79%   |
| InfoVision              | 69        | 0.76%   |
| Philips                 | 55        | 0.61%   |
| CPT                     | 53        | 0.59%   |
| Eizo                    | 50        | 0.55%   |
| AOC                     | 49        | 0.54%   |
| Iiyama                  | 47        | 0.52%   |
| Sony                    | 43        | 0.47%   |
| CSO                     | 43        | 0.47%   |
| HannStar                | 41        | 0.45%   |
| Fujitsu Siemens         | 35        | 0.39%   |
| Seiko/Epson             | 30        | 0.33%   |
| Panasonic               | 30        | 0.33%   |
| LGD                     | 26        | 0.29%   |
| Analogix                | 22        | 0.24%   |
| ANX                     | 21        | 0.23%   |
| Toshiba                 | 19        | 0.21%   |
| Medion                  | 19        | 0.21%   |
| Vestel Elektronik       | 17        | 0.19%   |
| Unknown                 | 16        | 0.18%   |
| Quanta Display          | 16        | 0.18%   |
| IBM                     | 14        | 0.15%   |
| ASUSTek Computer        | 14        | 0.15%   |
| InnoLux Display         | 13        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 72        | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 61        | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 61        | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 58        | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 55        | 0.6%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 50        | 0.54%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 47        | 0.51%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 46        | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 45        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 43        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 42        | 0.46%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 41        | 0.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 41        | 0.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 40        | 0.43%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 39        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 39        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 36        | 0.39%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 36        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 35        | 0.38%   |
| BOE LCD Monitor BOE0660 1600x900 382x215mm 17.3-inch                      | 35        | 0.38%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 35        | 0.38%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 34        | 0.37%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 34        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 34        | 0.37%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 32        | 0.35%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 32        | 0.35%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 31        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 30        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 29        | 0.32%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 29        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 29        | 0.32%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 29        | 0.32%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 28        | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 27        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 27        | 0.29%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 27        | 0.29%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 27        | 0.29%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 26        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 25        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 25        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3593      | 41.75%  |
| 1366x768 (WXGA)    | 1939      | 22.53%  |
| 1600x900 (HD+)     | 895       | 10.4%   |
| 1280x800 (WXGA)    | 444       | 5.16%   |
| 3840x2160 (4K)     | 298       | 3.46%   |
| 2560x1440 (QHD)    | 252       | 2.93%   |
| 1440x900 (WXGA+)   | 221       | 2.57%   |
| 1920x1200 (WUXGA)  | 175       | 2.03%   |
| 1680x1050 (WSXGA+) | 125       | 1.45%   |
| 1024x600           | 78        | 0.91%   |
| 1280x1024 (SXGA)   | 58        | 0.67%   |
| 800x1280           | 50        | 0.58%   |
| 2560x1600          | 47        | 0.55%   |
| 3440x1440          | 44        | 0.51%   |
| 2880x1800          | 40        | 0.46%   |
| 3840x2400          | 32        | 0.37%   |
| 2160x1440          | 28        | 0.33%   |
| 3200x1800 (QHD+)   | 27        | 0.31%   |
| 1024x768 (XGA)     | 24        | 0.28%   |
| Unknown            | 22        | 0.26%   |
| 2560x1080          | 20        | 0.23%   |
| 2256x1504          | 19        | 0.22%   |
| 1680x945           | 19        | 0.22%   |
| 3840x1080          | 16        | 0.19%   |
| 1920x540           | 16        | 0.19%   |
| 1360x768           | 15        | 0.17%   |
| 3000x2000          | 10        | 0.12%   |
| 1920x1280          | 10        | 0.12%   |
| 1400x1050          | 10        | 0.12%   |
| 1600x1200          | 9         | 0.1%    |
| 2520x1680          | 5         | 0.06%   |
| 2288x1287          | 5         | 0.06%   |
| 1280x768           | 5         | 0.06%   |
| 3072x1920          | 4         | 0.05%   |
| 2304x1440          | 4         | 0.05%   |
| 1280x720 (HD)      | 4         | 0.05%   |
| 3840x1600          | 3         | 0.03%   |
| 3840x1200          | 3         | 0.03%   |
| 1280x854           | 3         | 0.03%   |
| 1024x576           | 3         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3430      | 37.88%  |
| 17      | 1192      | 13.17%  |
| 13      | 1065      | 11.76%  |
| 14      | 1041      | 11.5%   |
| 24      | 352       | 3.89%   |
| 12      | 317       | 3.5%    |
| 27      | 311       | 3.43%   |
| Unknown | 209       | 2.31%   |
| 23      | 186       | 2.05%   |
| 11      | 145       | 1.6%    |
| 21      | 107       | 1.18%   |
| 10      | 98        | 1.08%   |
| 18      | 82        | 0.91%   |
| 16      | 67        | 0.74%   |
| 34      | 56        | 0.62%   |
| 19      | 56        | 0.62%   |
| 22      | 55        | 0.61%   |
| 31      | 49        | 0.54%   |
| 84      | 30        | 0.33%   |
| 25      | 22        | 0.24%   |
| 72      | 21        | 0.23%   |
| 20      | 19        | 0.21%   |
| 54      | 17        | 0.19%   |
| 32      | 16        | 0.18%   |
| 40      | 13        | 0.14%   |
| 28      | 11        | 0.12%   |
| 26      | 11        | 0.12%   |
| 48      | 10        | 0.11%   |
| 7       | 10        | 0.11%   |
| 8       | 8         | 0.09%   |
| 52      | 6         | 0.07%   |
| 142     | 5         | 0.06%   |
| 65      | 5         | 0.06%   |
| 37      | 5         | 0.06%   |
| 33      | 5         | 0.06%   |
| 49      | 4         | 0.04%   |
| 35      | 4         | 0.04%   |
| 55      | 2         | 0.02%   |
| 47      | 2         | 0.02%   |
| 41      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 4888      | 54.4%   |
| 351-400        | 1367      | 15.21%  |
| 201-300        | 1128      | 12.55%  |
| 501-600        | 796       | 8.86%   |
| 401-500        | 275       | 3.06%   |
| Unknown        | 209       | 2.33%   |
| 601-700        | 96        | 1.07%   |
| 701-800        | 78        | 0.87%   |
| 1501-2000      | 49        | 0.55%   |
| 1001-1500      | 48        | 0.53%   |
| 801-900        | 24        | 0.27%   |
| 101-200        | 9         | 0.1%    |
| 1-100          | 9         | 0.1%    |
| More than 2000 | 5         | 0.06%   |
| 901-1000       | 4         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6581      | 80.98%  |
| 16/10   | 1071      | 13.18%  |
| Unknown | 126       | 1.55%   |
| 3/2     | 100       | 1.23%   |
| 21/9    | 66        | 0.81%   |
| 5/4     | 54        | 0.66%   |
| 4/3     | 44        | 0.54%   |
| 0.62    | 44        | 0.54%   |
| 32/9    | 17        | 0.21%   |
| 0.67    | 9         | 0.11%   |
| 6/5     | 5         | 0.06%   |
| 1.00    | 5         | 0.06%   |
| 3.73    | 2         | 0.02%   |
| 0.89    | 1         | 0.01%   |
| 0.65    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3436      | 38%     |
| 81-90          | 1649      | 18.24%  |
| 121-130        | 1007      | 11.14%  |
| 201-250        | 525       | 5.81%   |
| 71-80          | 448       | 4.95%   |
| 301-350        | 317       | 3.51%   |
| 61-70          | 313       | 3.46%   |
| Unknown        | 209       | 2.31%   |
| 131-140        | 172       | 1.9%    |
| 251-300        | 168       | 1.86%   |
| 51-60          | 147       | 1.63%   |
| 351-500        | 139       | 1.54%   |
| 151-200        | 108       | 1.19%   |
| 41-50          | 96        | 1.06%   |
| 141-150        | 91        | 1.01%   |
| More than 1000 | 89        | 0.98%   |
| 111-120        | 43        | 0.48%   |
| 501-1000       | 37        | 0.41%   |
| 91-100         | 31        | 0.34%   |
| 1-40           | 18        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3634      | 40.89%  |
| 101-120       | 2672      | 30.06%  |
| 51-100        | 1504      | 16.92%  |
| 161-240       | 576       | 6.48%   |
| More than 240 | 229       | 2.58%   |
| Unknown       | 209       | 2.35%   |
| 1-50          | 64        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6821      | 80.99%  |
| 2     | 1152      | 13.68%  |
| 0     | 276       | 3.28%   |
| 3     | 162       | 1.92%   |
| 4     | 11        | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4695      | 35.23%  |
| Realtek Semiconductor             | 3896      | 29.24%  |
| Qualcomm Atheros                  | 1880      | 14.11%  |
| Broadcom                          | 915       | 6.87%   |
| Marvell Technology Group          | 208       | 1.56%   |
| Broadcom Limited                  | 197       | 1.48%   |
| Ericsson Business Mobile Networks | 164       | 1.23%   |
| Sierra Wireless                   | 155       | 1.16%   |
| Dell                              | 139       | 1.04%   |
| Ralink                            | 105       | 0.79%   |
| MediaTek                          | 100       | 0.75%   |
| Lenovo                            | 88        | 0.66%   |
| ASIX Electronics                  | 80        | 0.6%    |
| Hewlett-Packard                   | 65        | 0.49%   |
| Nvidia                            | 64        | 0.48%   |
| TP-Link                           | 48        | 0.36%   |
| Huawei Technologies               | 47        | 0.35%   |
| Ralink Technology                 | 46        | 0.35%   |
| DisplayLink                       | 44        | 0.33%   |
| Fibocom                           | 34        | 0.26%   |
| Samsung Electronics               | 32        | 0.24%   |
| JMicron Technology                | 26        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 20        | 0.15%   |
| ASUSTek Computer                  | 20        | 0.15%   |
| Edimax Technology                 | 19        | 0.14%   |
| AVM                               | 16        | 0.12%   |
| Qualcomm                          | 15        | 0.11%   |
| Xiaomi                            | 13        | 0.1%    |
| NetGear                           | 12        | 0.09%   |
| VIA Technologies                  | 11        | 0.08%   |
| Qualcomm Atheros Communications   | 11        | 0.08%   |
| D-Link System                     | 11        | 0.08%   |
| Attansic Technology               | 11        | 0.08%   |
| D-Link                            | 9         | 0.07%   |
| Apple                             | 9         | 0.07%   |
| U-Blox                            | 8         | 0.06%   |
| Microsoft                         | 7         | 0.05%   |
| AMD                               | 7         | 0.05%   |
| Toshiba                           | 6         | 0.05%   |
| Google                            | 6         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2566      | 15.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 533       | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 504       | 3.06%   |
| Intel Wi-Fi 6 AX200                                                     | 429       | 2.61%   |
| Intel Wireless 8265 / 8275                                              | 373       | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 360       | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 355       | 2.16%   |
| Intel Wireless 7260                                                     | 342       | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 320       | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 282       | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 252       | 1.53%   |
| Intel Wireless 8260                                                     | 252       | 1.53%   |
| Intel Wireless 7265                                                     | 231       | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 200       | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 181       | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 177       | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 170       | 1.03%   |
| Intel Wi-Fi 6 AX201                                                     | 165       | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 160       | 0.97%   |
| Intel Centrino Ultimate-N 6300                                          | 152       | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                | 144       | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 136       | 0.83%   |
| Intel WiFi Link 5100                                                    | 134       | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 133       | 0.81%   |
| Intel Wireless 3160                                                     | 132       | 0.8%    |
| Intel Wireless 3165                                                     | 130       | 0.79%   |
| Intel Wireless-AC 9260                                                  | 129       | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 128       | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 127       | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 127       | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 126       | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                | 124       | 0.75%   |
| Intel Ethernet Connection I217-LM                                       | 117       | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 116       | 0.7%    |
| Intel Ethernet Connection I219-LM                                       | 111       | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 110       | 0.67%   |
| Intel Ethernet Connection I218-LM                                       | 108       | 0.66%   |
| Intel Centrino Wireless-N 2230                                          | 104       | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                    | 102       | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 94        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4459      | 51.7%   |
| Qualcomm Atheros                | 1564      | 18.14%  |
| Realtek Semiconductor           | 1164      | 13.5%   |
| Broadcom                        | 633       | 7.34%   |
| Sierra Wireless                 | 155       | 1.8%    |
| Ralink                          | 105       | 1.22%   |
| Broadcom Limited                | 103       | 1.19%   |
| MediaTek                        | 97        | 1.12%   |
| Dell                            | 67        | 0.78%   |
| Ralink Technology               | 46        | 0.53%   |
| TP-Link                         | 40        | 0.46%   |
| Fibocom                         | 33        | 0.38%   |
| ASUSTek Computer                | 20        | 0.23%   |
| Edimax Technology               | 19        | 0.22%   |
| AVM                             | 16        | 0.19%   |
| Hewlett-Packard                 | 14        | 0.16%   |
| NetGear                         | 12        | 0.14%   |
| Qualcomm Atheros Communications | 11        | 0.13%   |
| Qualcomm                        | 11        | 0.13%   |
| D-Link System                   | 11        | 0.13%   |
| D-Link                          | 8         | 0.09%   |
| Microsoft                       | 6         | 0.07%   |
| ZyDAS                           | 4         | 0.05%   |
| Belkin Components               | 4         | 0.05%   |
| Winbond Electronics             | 2         | 0.02%   |
| Texas Instruments               | 2         | 0.02%   |
| Sitecom Europe                  | 2         | 0.02%   |
| Samsung Electronics             | 2         | 0.02%   |
| Quectel Wireless Solutions      | 2         | 0.02%   |
| Micro Star International        | 2         | 0.02%   |
| Linksys                         | 2         | 0.02%   |
| Fujitsu Siemens Computers       | 2         | 0.02%   |
| ZyXEL Communications            | 1         | 0.01%   |
| Wacom                           | 1         | 0.01%   |
| Qcom                            | 1         | 0.01%   |
| Marvell Technology Group        | 1         | 0.01%   |
| BUFFALO                         | 1         | 0.01%   |
| Acer NeWeb                      | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 429       | 4.95%   |
| Intel Wireless 8265 / 8275                                              | 373       | 4.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 360       | 4.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 355       | 4.09%   |
| Intel Wireless 7260                                                     | 342       | 3.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 282       | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 252       | 2.9%    |
| Intel Wireless 8260                                                     | 252       | 2.9%    |
| Intel Wireless 7265                                                     | 231       | 2.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 200       | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 181       | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 177       | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 170       | 1.96%   |
| Intel Wi-Fi 6 AX201                                                     | 165       | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 160       | 1.84%   |
| Intel Centrino Ultimate-N 6300                                          | 152       | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 136       | 1.57%   |
| Intel WiFi Link 5100                                                    | 134       | 1.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 133       | 1.53%   |
| Intel Wireless 3160                                                     | 132       | 1.52%   |
| Intel Wireless 3165                                                     | 130       | 1.5%    |
| Intel Wireless-AC 9260                                                  | 129       | 1.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 127       | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                           | 127       | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 126       | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 116       | 1.34%   |
| Intel Centrino Advanced-N 6200                                          | 110       | 1.27%   |
| Intel Centrino Wireless-N 2230                                          | 104       | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 94        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 92        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 82        | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 82        | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 81        | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 81        | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 78        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 77        | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 75        | 0.86%   |
| Intel Centrino Advanced-N 6235                                          | 73        | 0.84%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 67        | 0.77%   |
| Intel Ultimate N WiFi Link 5300                                         | 66        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3475      | 47.55%  |
| Intel                            | 2054      | 28.11%  |
| Qualcomm Atheros                 | 583       | 7.98%   |
| Broadcom                         | 408       | 5.58%   |
| Marvell Technology Group         | 207       | 2.83%   |
| Broadcom Limited                 | 100       | 1.37%   |
| Lenovo                           | 88        | 1.2%    |
| ASIX Electronics                 | 80        | 1.09%   |
| Nvidia                           | 64        | 0.88%   |
| DisplayLink                      | 44        | 0.6%    |
| Samsung Electronics              | 26        | 0.36%   |
| JMicron Technology               | 26        | 0.36%   |
| Huawei Technologies              | 19        | 0.26%   |
| Silicon Integrated Systems [SiS] | 18        | 0.25%   |
| Hewlett-Packard                  | 15        | 0.21%   |
| Xiaomi                           | 13        | 0.18%   |
| VIA Technologies                 | 11        | 0.15%   |
| Attansic Technology              | 11        | 0.15%   |
| Apple                            | 9         | 0.12%   |
| TP-Link                          | 8         | 0.11%   |
| Google                           | 6         | 0.08%   |
| Microchip Technology             | 5         | 0.07%   |
| Qualcomm                         | 4         | 0.05%   |
| HMD Global                       | 4         | 0.05%   |
| T & A Mobile Phones              | 3         | 0.04%   |
| MosChip Semiconductor            | 3         | 0.04%   |
| ULi Electronics                  | 2         | 0.03%   |
| OPPO Electronics                 | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.03%   |
| MediaTek                         | 2         | 0.03%   |
| ICS Advent                       | 2         | 0.03%   |
| Davicom Semiconductor            | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |
| Research In Motion               | 1         | 0.01%   |
| Promise Technology               | 1         | 0.01%   |
| National Semiconductor           | 1         | 0.01%   |
| Microsoft                        | 1         | 0.01%   |
| LG Electronics                   | 1         | 0.01%   |
| Intersil                         | 1         | 0.01%   |
| Foxconn / Hon Hai                | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2566      | 34.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 533       | 7.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 504       | 6.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 320       | 4.34%   |
| Intel 82577LM Gigabit Network Connection                                       | 144       | 1.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 128       | 1.73%   |
| Intel 82567LM Gigabit Network Connection                                       | 124       | 1.68%   |
| Intel Ethernet Connection I217-LM                                              | 117       | 1.59%   |
| Intel Ethernet Connection I219-LM                                              | 111       | 1.5%    |
| Intel Ethernet Connection I218-LM                                              | 108       | 1.46%   |
| Intel Ethernet Connection (4) I219-V                                           | 102       | 1.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 93        | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                                          | 91        | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                                          | 90        | 1.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 64        | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 62        | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 60        | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 59        | 0.8%    |
| Intel Ethernet Connection I219-V                                               | 58        | 0.79%   |
| Intel 82579V Gigabit Network Connection                                        | 56        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                           | 52        | 0.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 50        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 48        | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 45        | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 44        | 0.6%    |
| Intel 82566MM Gigabit Network Connection                                       | 44        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                          | 43        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 40        | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 40        | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 39        | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 37        | 0.5%    |
| Nvidia MCP79 Ethernet                                                          | 36        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                          | 36        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 35        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                                          | 34        | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 32        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 31        | 0.42%   |
| Intel Ethernet Connection I217-V                                               | 31        | 0.42%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 30        | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 28        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 8072      | 52.13%  |
| Ethernet | 7015      | 45.3%   |
| Modem    | 386       | 2.49%   |
| Unknown  | 12        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6461      | 73.29%  |
| Ethernet | 2355      | 26.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6490      | 78.93%  |
| 1     | 1559      | 18.96%  |
| 0     | 99        | 1.2%    |
| 3     | 72        | 0.88%   |
| 5     | 1         | 0.01%   |
| 4     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5901      | 69.73%  |
| Yes  | 2562      | 30.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2894      | 47.95%  |
| Realtek Semiconductor           | 662       | 10.97%  |
| Broadcom                        | 470       | 7.79%   |
| Qualcomm Atheros Communications | 351       | 5.82%   |
| Lite-On Technology              | 307       | 5.09%   |
| Foxconn / Hon Hai               | 265       | 4.39%   |
| IMC Networks                    | 237       | 3.93%   |
| Dell                            | 161       | 2.67%   |
| Apple                           | 159       | 2.63%   |
| Cambridge Silicon Radio         | 127       | 2.1%    |
| Hewlett-Packard                 | 84        | 1.39%   |
| Toshiba                         | 64        | 1.06%   |
| Realtek                         | 43        | 0.71%   |
| Foxconn International           | 42        | 0.7%    |
| ASUSTek Computer                | 29        | 0.48%   |
| Alps Electric                   | 28        | 0.46%   |
| Askey Computer                  | 24        | 0.4%    |
| Ralink                          | 23        | 0.38%   |
| Taiyo Yuden                     | 15        | 0.25%   |
| Chicony Electronics             | 11        | 0.18%   |
| Ralink Technology               | 9         | 0.15%   |
| Qcom                            | 5         | 0.08%   |
| Belkin Components               | 5         | 0.08%   |
| MediaTek                        | 4         | 0.07%   |
| Edimax Technology               | 4         | 0.07%   |
| Fujitsu                         | 3         | 0.05%   |
| USI                             | 2         | 0.03%   |
| TP-Link                         | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1333      | 22.07%  |
| Realtek Bluetooth Radio                             | 411       | 6.81%   |
| Intel AX200 Bluetooth                               | 406       | 6.72%   |
| Intel AX201 Bluetooth                               | 399       | 6.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 297       | 4.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 193       | 3.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 157       | 2.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 137       | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 127       | 2.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 119       | 1.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 118       | 1.95%   |
| IMC Networks Bluetooth Radio                        | 115       | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 100       | 1.66%   |
| Lite-On Bluetooth Device                            | 98        | 1.62%   |
| Apple Bluetooth Host Controller                     | 91        | 1.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 88        | 1.46%   |
| Foxconn / Hon Hai Bluetooth Device                  | 84        | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 67        | 1.11%   |
| Dell DW375 Bluetooth Module                         | 65        | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 64        | 1.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 63        | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 57        | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 54        | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 54        | 0.89%   |
| IMC Networks Bluetooth Device                       | 50        | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                    | 50        | 0.83%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 48        | 0.79%   |
| Intel AX210 Bluetooth                               | 44        | 0.73%   |
| Realtek Bluetooth Radio                             | 43        | 0.71%   |
| Foxconn International BCM43142A0 Bluetooth module   | 42        | 0.7%    |
| Foxconn / Hon Hai BCM20702A0                        | 42        | 0.7%    |
| Realtek RTL8723B Bluetooth                          | 39        | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                   | 38        | 0.63%   |
| Dell BCM20702A0 Bluetooth Module                    | 38        | 0.63%   |
| Broadcom BCM2045 Bluetooth                          | 38        | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 34        | 0.56%   |
| Broadcom HP Portable SoftSailing                    | 30        | 0.5%    |
| Apple Bluetooth USB Host Controller                 | 30        | 0.5%    |
| Intel Bluetooth Device                              | 29        | 0.48%   |
| Apple Bluetooth HCI                                 | 26        | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6544      | 65.7%   |
| AMD                              | 1713      | 17.2%   |
| Nvidia                           | 1020      | 10.24%  |
| Lenovo                           | 92        | 0.92%   |
| C-Media Electronics              | 84        | 0.84%   |
| GN Netcom                        | 70        | 0.7%    |
| Realtek Semiconductor            | 64        | 0.64%   |
| Logitech                         | 46        | 0.46%   |
| Plantronics                      | 30        | 0.3%    |
| Silicon Integrated Systems [SiS] | 22        | 0.22%   |
| Texas Instruments                | 16        | 0.16%   |
| Hewlett-Packard                  | 15        | 0.15%   |
| Focusrite-Novation               | 15        | 0.15%   |
| Conexant Systems                 | 13        | 0.13%   |
| JMTek                            | 12        | 0.12%   |
| VIA Technologies                 | 11        | 0.11%   |
| Kingston Technology              | 11        | 0.11%   |
| Generalplus Technology           | 11        | 0.11%   |
| Creative Technology              | 11        | 0.11%   |
| RODE Microphones                 | 9         | 0.09%   |
| DSEA A/S                         | 8         | 0.08%   |
| Sennheiser Communications        | 7         | 0.07%   |
| Dell                             | 7         | 0.07%   |
| TerraTec Electronic              | 6         | 0.06%   |
| Razer USA                        | 6         | 0.06%   |
| Apple                            | 6         | 0.06%   |
| SteelSeries ApS                  | 5         | 0.05%   |
| M-Audio                          | 5         | 0.05%   |
| No brand                         | 4         | 0.04%   |
| Native Instruments               | 4         | 0.04%   |
| GYROCOM C&C                      | 4         | 0.04%   |
| Blue Microphones                 | 4         | 0.04%   |
| SAVITECH                         | 3         | 0.03%   |
| Samson Technologies              | 3         | 0.03%   |
| Corsair                          | 3         | 0.03%   |
| Cambridge Silicon Radio          | 3         | 0.03%   |
| BEHRINGER International          | 3         | 0.03%   |
| AKAI Professional M.I.           | 3         | 0.03%   |
| Yamaha                           | 2         | 0.02%   |
| ULi Electronics                  | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 898       | 7.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 832       | 6.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 786       | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 610       | 5.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 516       | 4.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 472       | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 470       | 3.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 323       | 2.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 321       | 2.66%   |
| Intel 8 Series HD Audio Controller                                                                | 321       | 2.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 301       | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 276       | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 260       | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 256       | 2.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 244       | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 244       | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 238       | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 229       | 1.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 215       | 1.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 207       | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 174       | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 174       | 1.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 146       | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                                          | 139       | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 129       | 1.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 119       | 0.99%   |
| Intel CM238 HD Audio Controller                                                                   | 115       | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 114       | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 109       | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 100       | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 90        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 89        | 0.74%   |
| AMD High Definition Audio Controller                                                              | 83        | 0.69%   |
| Nvidia High Definition Audio Controller                                                           | 81        | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 78        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 76        | 0.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 69        | 0.57%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 68        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 65        | 0.54%   |
| Realtek Semiconductor USB Audio                                                                   | 61        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 1519      | 32.16%  |
| SK hynix                                         | 1072      | 22.7%   |
| Micron Technology                                | 539       | 11.41%  |
| Unknown                                          | 401       | 8.49%   |
| Kingston                                         | 348       | 7.37%   |
| Crucial                                          | 208       | 4.4%    |
| Ramaxel Technology                               | 128       | 2.71%   |
| Elpida                                           | 113       | 2.39%   |
| A-DATA Technology                                | 65        | 1.38%   |
| Nanya Technology                                 | 64        | 1.36%   |
| Corsair                                          | 60        | 1.27%   |
| Unknown (ABCD)                                   | 48        | 1.02%   |
| G.Skill                                          | 23        | 0.49%   |
| Unknown                                          | 18        | 0.38%   |
| Transcend                                        | 17        | 0.36%   |
| ASint Technology                                 | 17        | 0.36%   |
| 48spaces                                         | 10        | 0.21%   |
| Avant                                            | 7         | 0.15%   |
| Toshiba                                          | 5         | 0.11%   |
| Team                                             | 5         | 0.11%   |
| Patriot                                          | 5         | 0.11%   |
| Goodram                                          | 5         | 0.11%   |
| SHARETRONIC                                      | 4         | 0.08%   |
| Qimonda                                          | 4         | 0.08%   |
| CSX                                              | 4         | 0.08%   |
| PNY                                              | 3         | 0.06%   |
| Lexar                                            | 3         | 0.06%   |
| Apacer                                           | 3         | 0.06%   |
| GeIL                                             | 2         | 0.04%   |
| Aeneon                                           | 2         | 0.04%   |
| ZIFEI                                            | 1         | 0.02%   |
| Unknown (AB)                                     | 1         | 0.02%   |
| Unknown (8ECE)                                   | 1         | 0.02%   |
| Unknown (7F7F7F7F7F7F7F25)                       | 1         | 0.02%   |
| Unknown (0x5D00000000000000)                     | 1         | 0.02%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.02%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.02%   |
| Unknown (09C7)                                   | 1         | 0.02%   |
| Unifosa                                          | 1         | 0.02%   |
| Smart                                            | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 72        | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 70        | 1.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 62        | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 61        | 1.21%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 58        | 1.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 54        | 1.07%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 54        | 1.07%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 51        | 1.01%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 51        | 1.01%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 49        | 0.97%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 47        | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 46        | 0.91%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 46        | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 43        | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 40        | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 40        | 0.8%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 38        | 0.76%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 37        | 0.74%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 37        | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 34        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 33        | 0.66%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 32        | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.64%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 30        | 0.6%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 30        | 0.6%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 29        | 0.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 28        | 0.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 28        | 0.56%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 27        | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 26        | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 26        | 0.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 26        | 0.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 25        | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 25        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.46%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 23        | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 22        | 0.44%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 22        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1798      | 44.18%  |
| DDR3    | 1530      | 37.59%  |
| DDR2    | 231       | 5.68%   |
| LPDDR4  | 185       | 4.55%   |
| LPDDR3  | 125       | 3.07%   |
| SDRAM   | 96        | 2.36%   |
| DDR     | 30        | 0.74%   |
| Unknown | 24        | 0.59%   |
| LPDDR5  | 20        | 0.49%   |
| DRAM    | 16        | 0.39%   |
| DDR5    | 15        | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3684      | 90.27%  |
| Row Of Chips | 318       | 7.79%   |
| Chip         | 49        | 1.2%    |
| DIMM         | 24        | 0.59%   |
| Unknown      | 6         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1584      | 36.14%  |
| 4096  | 1367      | 31.19%  |
| 2048  | 575       | 13.12%  |
| 16384 | 571       | 13.03%  |
| 1024  | 152       | 3.47%   |
| 32768 | 108       | 2.46%   |
| 512   | 18        | 0.41%   |
| 256   | 4         | 0.09%   |
| 128   | 4         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 984       | 22.42%  |
| 2667    | 874       | 19.92%  |
| 3200    | 671       | 15.29%  |
| 2400    | 304       | 6.93%   |
| 1334    | 271       | 6.18%   |
| 2133    | 192       | 4.38%   |
| 1333    | 190       | 4.33%   |
| Unknown | 127       | 2.89%   |
| 667     | 122       | 2.78%   |
| 1067    | 112       | 2.55%   |
| 4267    | 71        | 1.62%   |
| 1867    | 64        | 1.46%   |
| 3266    | 54        | 1.23%   |
| 4199    | 53        | 1.21%   |
| 800     | 51        | 1.16%   |
| 1066    | 37        | 0.84%   |
| 4266    | 29        | 0.66%   |
| 8400    | 28        | 0.64%   |
| 2048    | 26        | 0.59%   |
| 975     | 24        | 0.55%   |
| 533     | 19        | 0.43%   |
| 6400    | 17        | 0.39%   |
| 4800    | 16        | 0.36%   |
| 1866    | 12        | 0.27%   |
| 3733    | 10        | 0.23%   |
| 333     | 9         | 0.21%   |
| 2933    | 4         | 0.09%   |
| 3000    | 3         | 0.07%   |
| 2267    | 3         | 0.07%   |
| 400     | 3         | 0.07%   |
| 1639    | 2         | 0.05%   |
| 933     | 1         | 0.02%   |
| 666     | 1         | 0.02%   |
| 266     | 1         | 0.02%   |
| 200     | 1         | 0.02%   |
| 166     | 1         | 0.02%   |
| 100     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 50        | 34.25%  |
| Canon                 | 26        | 17.81%  |
| Brother Industries    | 23        | 15.75%  |
| Samsung Electronics   | 17        | 11.64%  |
| Seiko Epson           | 10        | 6.85%   |
| Kyocera               | 7         | 4.79%   |
| Prolific Technology   | 5         | 3.42%   |
| QinHeng Electronics   | 2         | 1.37%   |
| Lexmark International | 2         | 1.37%   |
| STMicroelectronics    | 1         | 0.68%   |
| Oki Data              | 1         | 0.68%   |
| MIIIW                 | 1         | 0.68%   |
| Dymo-CoStar           | 1         | 0.68%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                      | 5         | 3.42%   |
| Prolific PL2305 Parallel Port                             | 5         | 3.42%   |
| Canon PIXMA MX920 Series                                  | 5         | 3.42%   |
| HP Deskjet 2540 series                                    | 4         | 2.74%   |
| Brother DCP-7055W                                         | 4         | 2.74%   |
| Kyocera Mita FS-820                                       | 3         | 2.05%   |
| HP ENVY 4520 series                                       | 3         | 2.05%   |
| HP Deskjet 1050 J410                                      | 3         | 2.05%   |
| Seiko Epson XP-4100 Series                                | 2         | 1.37%   |
| Samsung CLX-3300 Series                                   | 2         | 1.37%   |
| QinHeng CH340S                                            | 2         | 1.37%   |
| Lexmark International E360d                               | 2         | 1.37%   |
| Kyocera FS-1030D printer                                  | 2         | 1.37%   |
| HP Officejet 4620 series                                  | 2         | 1.37%   |
| HP LaserJet 200 colorMFP M275nw                           | 2         | 1.37%   |
| HP DeskJet 3630 series                                    | 2         | 1.37%   |
| HP DeskJet 2700 series                                    | 2         | 1.37%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 1.37%   |
| HP Deskjet 2050 J510                                      | 2         | 1.37%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.37%   |
| Canon TS700 series                                        | 2         | 1.37%   |
| Canon PIXMA MG3600 Series                                 | 2         | 1.37%   |
| Brother MFC-L3750CDW                                      | 2         | 1.37%   |
| Brother MFC-L2710DW series                                | 2         | 1.37%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.68%   |
| Seiko Epson XP-3100 Series                                | 1         | 0.68%   |
| Seiko Epson XP-2100 Series                                | 1         | 0.68%   |
| Seiko Epson WF-2530 Series                                | 1         | 0.68%   |
| Seiko Epson WF-2510 Series                                | 1         | 0.68%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.68%   |
| Seiko Epson Printer                                       | 1         | 0.68%   |
| Seiko Epson L3160 Series                                  | 1         | 0.68%   |
| Seiko Epson L3150 Series                                  | 1         | 0.68%   |
| Samsung SCX-4200 series                                   | 1         | 0.68%   |
| Samsung SCX-3200 Series                                   | 1         | 0.68%   |
| Samsung ML-331x Series Laser Printer                      | 1         | 0.68%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 0.68%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 0.68%   |
| Samsung M267x 287x Series                                 | 1         | 0.68%   |
| Samsung Color Laser Printer                               | 1         | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 25        | 73.53%  |
| Seiko Epson     | 5         | 14.71%  |
| Plustek         | 1         | 2.94%   |
| Mustek Systems  | 1         | 2.94%   |
| Hewlett-Packard | 1         | 2.94%   |
| AGFA-Gevaert NV | 1         | 2.94%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                  | 4         | 11.76%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 3         | 8.82%   |
| Canon CanoScan LIDE 25                                   | 3         | 8.82%   |
| Canon CanoScan LiDE 110                                  | 3         | 8.82%   |
| Canon CanoScan LiDE 500F                                 | 2         | 5.88%   |
| Canon CanoScan LiDE 210                                  | 2         | 5.88%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1         | 2.94%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]  | 1         | 2.94%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 2.94%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 1         | 2.94%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 2.94%   |
| Plustek OpticPro UT12/16/24 Scanner                      | 1         | 2.94%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 2.94%   |
| HP HP4470C                                               | 1         | 2.94%   |
| Canon CanoScan LiDE 90                                   | 1         | 2.94%   |
| Canon CanoScan LiDE 600F                                 | 1         | 2.94%   |
| Canon CanoScan LiDE 60                                   | 1         | 2.94%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 2.94%   |
| Canon CanoScan LiDE 200                                  | 1         | 2.94%   |
| Canon CanoScan LiDE 120                                  | 1         | 2.94%   |
| Canon CanoScan LiDE 100                                  | 1         | 2.94%   |
| Canon CanoScan 3200F                                     | 1         | 2.94%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                       | 1         | 2.94%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2127      | 30.39%  |
| IMC Networks                           | 639       | 9.13%   |
| Acer                                   | 629       | 8.99%   |
| Realtek Semiconductor                  | 491       | 7.01%   |
| Microdia                               | 477       | 6.81%   |
| Quanta                                 | 325       | 4.64%   |
| Sunplus Innovation Technology          | 311       | 4.44%   |
| Suyin                                  | 285       | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 279       | 3.99%   |
| Lite-On Technology                     | 189       | 2.7%    |
| Syntek                                 | 152       | 2.17%   |
| Apple                                  | 133       | 1.9%    |
| Logitech                               | 116       | 1.66%   |
| Silicon Motion                         | 102       | 1.46%   |
| Ricoh                                  | 97        | 1.39%   |
| Alcor Micro                            | 91        | 1.3%    |
| Lenovo                                 | 83        | 1.19%   |
| Luxvisions Innotech Limited            | 61        | 0.87%   |
| Z-Star Microelectronics                | 52        | 0.74%   |
| ALi                                    | 46        | 0.66%   |
| Primax Electronics                     | 32        | 0.46%   |
| Samsung Electronics                    | 28        | 0.4%    |
| DigiTech                               | 25        | 0.36%   |
| Importek                               | 22        | 0.31%   |
| Microsoft                              | 14        | 0.2%    |
| Sunplus Technology                     | 13        | 0.19%   |
| SunplusIT                              | 12        | 0.17%   |
| Generalplus Technology                 | 12        | 0.17%   |
| Genesys Logic                          | 10        | 0.14%   |
| Sonix Technology                       | 9         | 0.13%   |
| Intel                                  | 8         | 0.11%   |
| eMPIA Technology                       | 8         | 0.11%   |
| DJJHFA1BIF5595                         | 8         | 0.11%   |
| USB Camera                             | 7         | 0.1%    |
| OmniVision Technologies                | 7         | 0.1%    |
| Creative Technology                    | 7         | 0.1%    |
| Y Media                                | 5         | 0.07%   |
| KYE Systems (Mouse Systems)            | 5         | 0.07%   |
| ARC International                      | 5         | 0.07%   |
| Unknown                                | 4         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 438       | 6.23%   |
| Chicony HD WebCam                                | 257       | 3.66%   |
| IMC Networks Integrated Camera                   | 222       | 3.16%   |
| Acer Integrated Camera                           | 190       | 2.7%    |
| Microdia Integrated_Webcam_HD                    | 175       | 2.49%   |
| Realtek Integrated_Webcam_HD                     | 137       | 1.95%   |
| IMC Networks USB2.0 HD UVC WebCam                | 115       | 1.64%   |
| Chicony USB2.0 Camera                            | 108       | 1.54%   |
| Chicony FJ Camera                                | 96        | 1.37%   |
| Chicony USB 2.0 Camera                           | 84        | 1.2%    |
| Lite-On Integrated Camera                        | 82        | 1.17%   |
| Syntek Integrated Camera                         | 75        | 1.07%   |
| Acer Lenovo EasyCamera                           | 75        | 1.07%   |
| Chicony USB2.0 HD UVC WebCam                     | 66        | 0.94%   |
| Microdia Integrated Webcam                       | 65        | 0.93%   |
| Chicony HD User Facing                           | 65        | 0.93%   |
| Acer BisonCam, NB Pro                            | 64        | 0.91%   |
| Quanta HD User Facing                            | 62        | 0.88%   |
| Sunplus HD WebCam                                | 61        | 0.87%   |
| Chicony Integrated Camera (1280x720@30)          | 58        | 0.83%   |
| Sunplus Integrated_Webcam_HD                     | 57        | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 56        | 0.8%    |
| Chicony HP HD Camera                             | 55        | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 55        | 0.78%   |
| Acer SunplusIT Integrated Camera                 | 55        | 0.78%   |
| Realtek USB Camera                               | 52        | 0.74%   |
| Quanta HP Webcam                                 | 52        | 0.74%   |
| Chicony HP Webcam                                | 50        | 0.71%   |
| Microdia USB 2.0 Camera                          | 48        | 0.68%   |
| Chicony TOSHIBA Web Camera - HD                  | 48        | 0.68%   |
| Acer Lenovo Integrated Webcam                    | 48        | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 47        | 0.67%   |
| Apple Built-in iSight                            | 45        | 0.64%   |
| Quanta HP HD Camera                              | 44        | 0.63%   |
| Chicony VGA Webcam                               | 44        | 0.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 43        | 0.61%   |
| Realtek Lenovo EasyCamera                        | 41        | 0.58%   |
| Chicony Lenovo EasyCamera                        | 41        | 0.58%   |
| Chicony EasyCamera                               | 40        | 0.57%   |
| Quanta HD Webcam                                 | 38        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 567       | 32.46%  |
| Synaptics                  | 426       | 24.38%  |
| Shenzhen Goodix Technology | 213       | 12.19%  |
| AuthenTec                  | 173       | 9.9%    |
| Upek                       | 139       | 7.96%   |
| LighTuning Technology      | 118       | 6.75%   |
| Elan Microelectronics      | 68        | 3.89%   |
| STMicroelectronics         | 35        | 2%      |
| HOLTEK                     | 5         | 0.29%   |
| Samsung Electronics        | 1         | 0.06%   |
| Next Biometrics            | 1         | 0.06%   |
| Focal-systems.Corp         | 1         | 0.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 187       | 10.7%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 131       | 7.5%    |
| Shenzhen Goodix  Fingerprint Device                                        | 128       | 7.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 106       | 6.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 96        | 5.5%    |
| AuthenTec AES2810                                                          | 65        | 3.72%   |
| Unknown                                                                    | 64        | 3.66%   |
| Validity Sensors Synaptics WBDI                                            | 62        | 3.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 59        | 3.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 59        | 3.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 52        | 2.98%   |
| Shenzhen Goodix Fingerprint Reader                                         | 48        | 2.75%   |
| Elan ELAN:Fingerprint                                                      | 45        | 2.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 43        | 2.46%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 40        | 2.29%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 40        | 2.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 38        | 2.18%   |
| Shenzhen Goodix FingerPrint                                                | 37        | 2.12%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 37        | 2.12%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 35        | 2%      |
| STMicroelectronics Fingerprint Reader                                      | 35        | 2%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 29        | 1.66%   |
| AuthenTec AES1600                                                          | 29        | 1.66%   |
| Validity Sensors VFS491                                                    | 28        | 1.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 28        | 1.6%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 26        | 1.49%   |
| LighTuning Fingerprint Reader                                              | 25        | 1.43%   |
| AuthenTec Fingerprint Sensor                                               | 24        | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 23        | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 21        | 1.2%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 15        | 0.86%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 0.86%   |
| Synaptics WBDI Device                                                      | 12        | 0.69%   |
| Synaptics  WBDI                                                            | 9         | 0.52%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 9         | 0.52%   |
| Upek TCS5B Fingerprint sensor                                              | 8         | 0.46%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 8         | 0.46%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.4%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 5         | 0.29%   |
| HOLTEK FocalTech Fingerprint Device                                        | 5         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 413       | 40.14%  |
| Broadcom                  | 316       | 30.71%  |
| Lenovo                    | 95        | 9.23%   |
| O2 Micro                  | 94        | 9.14%   |
| Upek                      | 64        | 6.22%   |
| Gemalto (was Gemplus)     | 11        | 1.07%   |
| Yubico.com                | 10        | 0.97%   |
| OmniKey                   | 5         | 0.49%   |
| Clay Logic                | 5         | 0.49%   |
| SCM Microsystems          | 4         | 0.39%   |
| Reiner SCT Kartensysteme  | 3         | 0.29%   |
| NXP Semiconductors        | 2         | 0.19%   |
| Realtek Semiconductor     | 1         | 0.1%    |
| Purism, SPC               | 1         | 0.1%    |
| Microchip Technology      | 1         | 0.1%    |
| Kobil Systems             | 1         | 0.1%    |
| In Focus Systems          | 1         | 0.1%    |
| Fujitsu Siemens Computers | 1         | 0.1%    |
| Cherry                    | 1         | 0.1%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 413       | 40.14%  |
| Broadcom BCM5880 Secure Applications Processor                               | 133       | 12.93%  |
| Lenovo Integrated Smart Card Reader                                          | 95        | 9.23%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 83        | 8.07%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 69        | 6.71%   |
| Broadcom 5880                                                                | 65        | 6.32%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 64        | 6.22%   |
| Broadcom 58200                                                               | 43        | 4.18%   |
| O2 Micro Oz776 SmartCard Reader                                              | 11        | 1.07%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 8         | 0.78%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 0.58%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 6         | 0.58%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 0.49%   |
| Clay Logic Nitrokey Pro                                                      | 5         | 0.49%   |
| OmniKey CardMan 4321                                                         | 3         | 0.29%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.19%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.19%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.19%   |
| NXP Semiconductors PR533                                                     | 2         | 0.19%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.1%    |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.1%    |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.1%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.1%    |
| Purism, SPC Librem Key                                                       | 1         | 0.1%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.1%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.1%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.1%    |
| Kobil Systems Smart Token                                                    | 1         | 0.1%    |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.1%    |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.1%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4825      | 57.22%  |
| 1     | 2638      | 31.29%  |
| 2     | 773       | 9.17%   |
| 3     | 142       | 1.68%   |
| 4     | 31        | 0.37%   |
| 5     | 15        | 0.18%   |
| 6     | 4         | 0.05%   |
| 7     | 3         | 0.04%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1725      | 36.87%  |
| Chipcard                 | 922       | 19.71%  |
| Graphics card            | 739       | 15.79%  |
| Net/wireless             | 459       | 9.81%   |
| Multimedia controller    | 206       | 4.4%    |
| Storage                  | 130       | 2.78%   |
| Camera                   | 105       | 2.24%   |
| Communication controller | 96        | 2.05%   |
| Card reader              | 78        | 1.67%   |
| Bluetooth                | 75        | 1.6%    |
| Modem                    | 39        | 0.83%   |
| Sound                    | 38        | 0.81%   |
| Net/ethernet             | 25        | 0.53%   |
| Network                  | 14        | 0.3%    |
| Flash memory             | 9         | 0.19%   |
| Unassigned class         | 5         | 0.11%   |
| Storage/ide              | 5         | 0.11%   |
| Firewire controller      | 4         | 0.09%   |
| Storage/raid             | 2         | 0.04%   |
| Tv card                  | 1         | 0.02%   |
| Storage/ata              | 1         | 0.02%   |
| Dvb card                 | 1         | 0.02%   |

