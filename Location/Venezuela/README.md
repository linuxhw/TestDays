Linux in Venezuela - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Venezuela/Desktop/README.md) and [notebooks](/Location/Venezuela/Notebook/README.md).

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

Total: 433

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0J3C2F A02                  | Desktop     | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| Soncview      | G41D3C                      | Desktop     | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [615409e462](https://linux-hardware.org/?probe=615409e462) | Mar 12, 2023 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [cc778f466a](https://linux-hardware.org/?probe=cc778f466a) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [d94d167f13](https://linux-hardware.org/?probe=d94d167f13) | Mar 11, 2023 |
| Pegatron      | H36Y                        | Notebook    | [1757156f40](https://linux-hardware.org/?probe=1757156f40) | Mar 11, 2023 |
| Acer          | Aspire A715-76              | Notebook    | [c0c0d5447d](https://linux-hardware.org/?probe=c0c0d5447d) | Mar 09, 2023 |
| Pegatron      | H36Y                        | Notebook    | [8d9c3ebbc8](https://linux-hardware.org/?probe=8d9c3ebbc8) | Mar 09, 2023 |
| MSI           | GL73 9SD                    | Notebook    | [0913746f16](https://linux-hardware.org/?probe=0913746f16) | Mar 07, 2023 |
| VIT           | P1400                       | Notebook    | [3d31270e0d](https://linux-hardware.org/?probe=3d31270e0d) | Mar 07, 2023 |
| VIT           | P1400                       | Notebook    | [bed6aed6fa](https://linux-hardware.org/?probe=bed6aed6fa) | Mar 07, 2023 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [9a9f442174](https://linux-hardware.org/?probe=9a9f442174) | Mar 03, 2023 |
| Acer          | Aspire A715-76              | Notebook    | [b9f52dc0f3](https://linux-hardware.org/?probe=b9f52dc0f3) | Feb 27, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [b9fbaca53d](https://linux-hardware.org/?probe=b9fbaca53d) | Feb 23, 2023 |
| Dell          | Latitude E6430              | Notebook    | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Google        | Candy                       | Notebook    | [b2f2862759](https://linux-hardware.org/?probe=b2f2862759) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Aspire 4739Z                | Notebook    | [cc795627da](https://linux-hardware.org/?probe=cc795627da) | Feb 10, 2023 |
| HP            | 1495                        | Desktop     | [627c584065](https://linux-hardware.org/?probe=627c584065) | Feb 09, 2023 |
| Dell          | 0YF8P5 A00                  | Desktop     | [4bb4dd8a98](https://linux-hardware.org/?probe=4bb4dd8a98) | Feb 06, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d6cea67f50](https://linux-hardware.org/?probe=d6cea67f50) | Feb 05, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [c20b6ee7d2](https://linux-hardware.org/?probe=c20b6ee7d2) | Feb 04, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| ECS           | G31T-M7                     | Desktop     | [76be6a1404](https://linux-hardware.org/?probe=76be6a1404) | Feb 01, 2023 |
| ECS           | G31T-M7                     | Desktop     | [9b0f53b46c](https://linux-hardware.org/?probe=9b0f53b46c) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [daa9bd48c8](https://linux-hardware.org/?probe=daa9bd48c8) | Jan 31, 2023 |
| Gigabyte      | EP35-DS3L                   | Desktop     | [5be0362f3e](https://linux-hardware.org/?probe=5be0362f3e) | Jan 23, 2023 |
| Lenovo        | ThinkPad SL 2743A65         | Notebook    | [89f744ff83](https://linux-hardware.org/?probe=89f744ff83) | Jan 22, 2023 |
| Dell          | Vostro 1220                 | Notebook    | [6cd42b6be3](https://linux-hardware.org/?probe=6cd42b6be3) | Jan 19, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [c48a8fe525](https://linux-hardware.org/?probe=c48a8fe525) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| HP            | 1495                        | Desktop     | [28c3cf967d](https://linux-hardware.org/?probe=28c3cf967d) | Jan 16, 2023 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| Pegatron      | B74                         | Notebook    | [3e721dbe13](https://linux-hardware.org/?probe=3e721dbe13) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6cb922bbdf](https://linux-hardware.org/?probe=6cb922bbdf) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4ed227f8af](https://linux-hardware.org/?probe=4ed227f8af) | Jan 09, 2023 |
| Intel         | powered classmate PC        | Tablet      | [c35a8d75ce](https://linux-hardware.org/?probe=c35a8d75ce) | Jan 05, 2023 |
| Intel         | powered classmate PC        | Tablet      | [dbca24d9e5](https://linux-hardware.org/?probe=dbca24d9e5) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8e885883c6](https://linux-hardware.org/?probe=8e885883c6) | Jan 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [61b7eaac72](https://linux-hardware.org/?probe=61b7eaac72) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [de0a127527](https://linux-hardware.org/?probe=de0a127527) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [515785c9c4](https://linux-hardware.org/?probe=515785c9c4) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [68f683d29e](https://linux-hardware.org/?probe=68f683d29e) | Dec 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a656b96d5f](https://linux-hardware.org/?probe=a656b96d5f) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6275a6ee8f](https://linux-hardware.org/?probe=6275a6ee8f) | Dec 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e1a4335a71](https://linux-hardware.org/?probe=e1a4335a71) | Dec 01, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| Intel         | powered classmate PC        | Tablet      | [44cc912fe3](https://linux-hardware.org/?probe=44cc912fe3) | Nov 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [906ad9a3c1](https://linux-hardware.org/?probe=906ad9a3c1) | Nov 25, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [b252a902f4](https://linux-hardware.org/?probe=b252a902f4) | Nov 24, 2022 |
| VIT           | M2400-01                    | Mini pc     | [4b590aa76a](https://linux-hardware.org/?probe=4b590aa76a) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3469b1e624](https://linux-hardware.org/?probe=3469b1e624) | Nov 07, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [d3ef4a43db](https://linux-hardware.org/?probe=d3ef4a43db) | Nov 06, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Intel         | H61                         | Desktop     | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| Intel         | powered classmate PC        | Tablet      | [d047cd6e73](https://linux-hardware.org/?probe=d047cd6e73) | Oct 22, 2022 |
| Google        | Candy                       | Notebook    | [af2c0be6ca](https://linux-hardware.org/?probe=af2c0be6ca) | Oct 17, 2022 |
| Google        | Candy                       | Notebook    | [ec740507fd](https://linux-hardware.org/?probe=ec740507fd) | Oct 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| ECS           | A890GXM-A2                  | Desktop     | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| VIT           | P2402                       | Notebook    | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | Notebook    | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [21cfcdcbdd](https://linux-hardware.org/?probe=21cfcdcbdd) | Sep 23, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Gateway       | NV57H                       | Notebook    | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| Clevo         | W54xEU                      | Notebook    | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [ac687f4dcd](https://linux-hardware.org/?probe=ac687f4dcd) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b3b173a476](https://linux-hardware.org/?probe=b3b173a476) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Intel         | S1200BTL E98681-352         | Server      | [1db51bcff9](https://linux-hardware.org/?probe=1db51bcff9) | Aug 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | 339A                        | Desktop     | [c19f3d1361](https://linux-hardware.org/?probe=c19f3d1361) | Jul 29, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| Intel         | powered classmate PC        | Tablet      | [1abacce964](https://linux-hardware.org/?probe=1abacce964) | Jul 06, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [737e14fea7](https://linux-hardware.org/?probe=737e14fea7) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| Pegatron      | IPPSB-DB                    | Desktop     | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| Google        | Cyan                        | Notebook    | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| langchao      | IPM41-D3                    | Desktop     | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [5d8aa17afc](https://linux-hardware.org/?probe=5d8aa17afc) | Jun 10, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [a502ed154f](https://linux-hardware.org/?probe=a502ed154f) | Jun 10, 2022 |
| VIT           | M2420                       | Notebook    | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| VIT           | M2420                       | Notebook    | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | Notebook    | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Lenovo        | 11051CS ThinkServer TS13... | Desktop     | [48e6a5501d](https://linux-hardware.org/?probe=48e6a5501d) | May 26, 2022 |
| Acer          | TravelMate 5742Z            | Notebook    | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| IP3 Tech      | TB20                        | Desktop     | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Intel         | H61                         | Desktop     | [28277b5d5a](https://linux-hardware.org/?probe=28277b5d5a) | May 10, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | Notebook    | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| ASRock        | G31M-S                      | Desktop     | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| Gateway       | NV57H                       | Notebook    | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [552956f271](https://linux-hardware.org/?probe=552956f271) | Mar 24, 2022 |
| VIT           | P2402                       | Notebook    | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Inspur        | Computer All in one PC V... | Desktop     | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| MSI           | 3664h                       | Desktop     | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | NP3020M3                    | Server      | [9fbb87a829](https://linux-hardware.org/?probe=9fbb87a829) | Mar 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [0e8fbc26f1](https://linux-hardware.org/?probe=0e8fbc26f1) | Mar 01, 2022 |
| Pegatron      | 2ACC                        | Desktop     | [c1127626c5](https://linux-hardware.org/?probe=c1127626c5) | Mar 01, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Intel         | powered classmate PC        | Tablet      | [a2b7a04dfa](https://linux-hardware.org/?probe=a2b7a04dfa) | Feb 18, 2022 |
| VIT           | P3400                       | Notebook    | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | Notebook    | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| ECS           | KAM1-I                      | Desktop     | [be38f855ff](https://linux-hardware.org/?probe=be38f855ff) | Feb 10, 2022 |
| Gateway       | NV57H                       | Notebook    | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| ASRock        | A55M-HVS                    | Desktop     | [c4c68e7dd1](https://linux-hardware.org/?probe=c4c68e7dd1) | Feb 08, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| ASUSTek       | P6X58-E PRO                 | Desktop     | [9ee8e1ecdf](https://linux-hardware.org/?probe=9ee8e1ecdf) | Jan 30, 2022 |
| Intel         | DG41TY AAE47335-203         | Desktop     | [01ec1ff569](https://linux-hardware.org/?probe=01ec1ff569) | Jan 26, 2022 |
| MSI           | MS-1454                     | Notebook    | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8700fd1193](https://linux-hardware.org/?probe=8700fd1193) | Jan 11, 2022 |
| VIT           | M2421                       | Notebook    | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| UNIQCELL      | Q15.6                       | Notebook    | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [8d19cd079a](https://linux-hardware.org/?probe=8d19cd079a) | Dec 09, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ecd0add9b3](https://linux-hardware.org/?probe=ecd0add9b3) | Dec 09, 2021 |
| HP            | 3398                        | Desktop     | [5ae73e1468](https://linux-hardware.org/?probe=5ae73e1468) | Dec 07, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Lenovo        | B40-70 20392                | Notebook    | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| Intel         | powered classmate PC        | Tablet      | [aea7e0243a](https://linux-hardware.org/?probe=aea7e0243a) | Nov 21, 2021 |
| Intel         | powered classmate PC        | Tablet      | [444812feb3](https://linux-hardware.org/?probe=444812feb3) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | Notebook    | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| HP            | 1495                        | Desktop     | [64cbb112e2](https://linux-hardware.org/?probe=64cbb112e2) | Oct 01, 2021 |
| Clevo         | W54xEU                      | Notebook    | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | Notebook    | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | Notebook    | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Foxconn       | M61PMV FAB                  | Desktop     | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| Pegatron      | T14AF                       | Notebook    | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | Notebook    | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ec9367ff70](https://linux-hardware.org/?probe=ec9367ff70) | Aug 16, 2021 |
| VIT           | P2400                       | Notebook    | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Foxconn       | ELA01                       | Desktop     | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Lenovo        | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [60c62c33f8](https://linux-hardware.org/?probe=60c62c33f8) | Jul 14, 2021 |
| Biostar       | G41D3                       | Desktop     | [673d4faa98](https://linux-hardware.org/?probe=673d4faa98) | Jul 12, 2021 |
| HP            | 3397                        | Desktop     | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP            | 3397                        | Desktop     | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [a57f28921c](https://linux-hardware.org/?probe=a57f28921c) | Jul 05, 2021 |
| ECS           | Livermore                   | Desktop     | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| VIT           | P2400                       | Notebook    | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [512537c402](https://linux-hardware.org/?probe=512537c402) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [9773736b0f](https://linux-hardware.org/?probe=9773736b0f) | Jun 17, 2021 |
| ECS           | G31T-M7                     | Desktop     | [01ed8410e9](https://linux-hardware.org/?probe=01ed8410e9) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M55E 9645BN2    | Desktop     | [ef91279611](https://linux-hardware.org/?probe=ef91279611) | Jun 15, 2021 |
| VIT           | P1400                       | Notebook    | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| Biostar       | G41D3C                      | Desktop     | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | Notebook    | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | Notebook    | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [42960896cb](https://linux-hardware.org/?probe=42960896cb) | May 20, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4856303cbe](https://linux-hardware.org/?probe=4856303cbe) | May 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | Notebook    | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [8d84f6dc9e](https://linux-hardware.org/?probe=8d84f6dc9e) | Apr 25, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [db04624ac3](https://linux-hardware.org/?probe=db04624ac3) | Apr 20, 2021 |
| Acer          | Aspire 4935                 | Notebook    | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| Toshiba       | Satellite E55t-A            | Notebook    | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | Notebook    | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [7f2618efb7](https://linux-hardware.org/?probe=7f2618efb7) | Mar 12, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 1495                        | Desktop     | [248af9611e](https://linux-hardware.org/?probe=248af9611e) | Mar 11, 2021 |
| Dell          | 0GX297                      | Desktop     | [6ac3da669a](https://linux-hardware.org/?probe=6ac3da669a) | Mar 09, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [543e8d3501](https://linux-hardware.org/?probe=543e8d3501) | Mar 07, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [892f3e6658](https://linux-hardware.org/?probe=892f3e6658) | Mar 07, 2021 |
| HP            | 2000                        | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Intel         | S5500BC E25124-407          | Server      | [fe3d758c20](https://linux-hardware.org/?probe=fe3d758c20) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9e6a12d9e1](https://linux-hardware.org/?probe=9e6a12d9e1) | Feb 15, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e4d1cc65bc](https://linux-hardware.org/?probe=e4d1cc65bc) | Jan 27, 2021 |
| HP            | 1493                        | Desktop     | [febb5aee31](https://linux-hardware.org/?probe=febb5aee31) | Jan 15, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| Pegatron      | IPM41-D3                    | Desktop     | [4e0489bdb0](https://linux-hardware.org/?probe=4e0489bdb0) | Dec 05, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [e195f622e4](https://linux-hardware.org/?probe=e195f622e4) | Nov 22, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [a0456b9ad3](https://linux-hardware.org/?probe=a0456b9ad3) | Nov 22, 2020 |
| HP            | 1495                        | Desktop     | [72bdee2784](https://linux-hardware.org/?probe=72bdee2784) | Nov 19, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | Notebook    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Foxconn       | M61PMV FAB A1               | Desktop     | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db328c3c01](https://linux-hardware.org/?probe=db328c3c01) | Sep 29, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [8ae7ffac0b](https://linux-hardware.org/?probe=8ae7ffac0b) | Sep 28, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | Notebook    | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Intel         | powered classmate PC        | Tablet      | [4f4efbc5c6](https://linux-hardware.org/?probe=4f4efbc5c6) | Sep 06, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [5f5f0bd2cf](https://linux-hardware.org/?probe=5f5f0bd2cf) | Aug 29, 2020 |
| Biostar       | N68S3B                      | Desktop     | [1e4d89cafe](https://linux-hardware.org/?probe=1e4d89cafe) | Aug 27, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [7f40a96159](https://linux-hardware.org/?probe=7f40a96159) | Aug 20, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8445b18759](https://linux-hardware.org/?probe=8445b18759) | Aug 20, 2020 |
| HP            | Presario V2000 (EW997LA#... | Notebook    | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | Notebook    | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [43d0144f0a](https://linux-hardware.org/?probe=43d0144f0a) | Aug 06, 2020 |
| MSI           | K9N2 Diamond                | Desktop     | [07a001660f](https://linux-hardware.org/?probe=07a001660f) | Aug 04, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [f2fdb4f618](https://linux-hardware.org/?probe=f2fdb4f618) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [a2e742ec36](https://linux-hardware.org/?probe=a2e742ec36) | Jul 27, 2020 |
| VIT           | M2421                       | Notebook    | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [6786c103d7](https://linux-hardware.org/?probe=6786c103d7) | Jul 27, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| Intel         | powered classmate PC        | Notebook    | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | Notebook    | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [39510acc74](https://linux-hardware.org/?probe=39510acc74) | Jul 06, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [eff9ad2c7d](https://linux-hardware.org/?probe=eff9ad2c7d) | Jul 05, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [a1e610807e](https://linux-hardware.org/?probe=a1e610807e) | Jun 30, 2020 |
| HP            | Presario C700               | Notebook    | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [e8c521f7e8](https://linux-hardware.org/?probe=e8c521f7e8) | Jun 25, 2020 |
| Standard      | AHV                         | All in one  | [989175dbdc](https://linux-hardware.org/?probe=989175dbdc) | Jun 08, 2020 |
| Standard      | AHV                         | All in one  | [f0bd9ac2e1](https://linux-hardware.org/?probe=f0bd9ac2e1) | Jun 07, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [cd52689b0a](https://linux-hardware.org/?probe=cd52689b0a) | May 25, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [d48d360c14](https://linux-hardware.org/?probe=d48d360c14) | May 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [18c81b7e8b](https://linux-hardware.org/?probe=18c81b7e8b) | May 19, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [cce631f67b](https://linux-hardware.org/?probe=cce631f67b) | May 19, 2020 |
| VIT           | P3400                       | Notebook    | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [084641dbc1](https://linux-hardware.org/?probe=084641dbc1) | May 17, 2020 |
| VIT           | P3400                       | Notebook    | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | Notebook    | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b55d1daea5](https://linux-hardware.org/?probe=b55d1daea5) | May 11, 2020 |
| VIT           | P2402                       | Notebook    | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97e5a8c8da](https://linux-hardware.org/?probe=97e5a8c8da) | Apr 26, 2020 |
| VIT           | P3400                       | Notebook    | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | Notebook    | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | Notebook    | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [b3436f0ec6](https://linux-hardware.org/?probe=b3436f0ec6) | Apr 11, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [841ded939f](https://linux-hardware.org/?probe=841ded939f) | Mar 31, 2020 |
| Lenovo        | ThinkCentre A58 7515A33     | Desktop     | [75be0ab7ac](https://linux-hardware.org/?probe=75be0ab7ac) | Mar 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | Notebook    | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [1d140aa76c](https://linux-hardware.org/?probe=1d140aa76c) | Mar 07, 2020 |
| Acer          | Aspire Z3730                | All in one  | [24d42a520e](https://linux-hardware.org/?probe=24d42a520e) | Mar 03, 2020 |
| VIT           | P2402                       | Notebook    | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [2859756e56](https://linux-hardware.org/?probe=2859756e56) | Feb 29, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | ThinkCentre XXXX 8705A84    | Desktop     | [b824441963](https://linux-hardware.org/?probe=b824441963) | Feb 23, 2020 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [e79318e87d](https://linux-hardware.org/?probe=e79318e87d) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [3e6bc93a39](https://linux-hardware.org/?probe=3e6bc93a39) | Jan 31, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b6ba4394f7](https://linux-hardware.org/?probe=b6ba4394f7) | Jan 29, 2020 |
| ASUSTek       | Leonite2                    | Desktop     | [d0d56d5609](https://linux-hardware.org/?probe=d0d56d5609) | Jan 23, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| VIT           | Aptio CRB                   | Mini pc     | [d999c674f1](https://linux-hardware.org/?probe=d999c674f1) | Dec 23, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [41131b1d8e](https://linux-hardware.org/?probe=41131b1d8e) | Dec 23, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | Desktop     | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [2d4b473d59](https://linux-hardware.org/?probe=2d4b473d59) | Dec 01, 2019 |
| Pegatron      | 2A73h                       | Desktop     | [2371d130d0](https://linux-hardware.org/?probe=2371d130d0) | Nov 30, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [aba5fa885d](https://linux-hardware.org/?probe=aba5fa885d) | Nov 25, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3d775f418d](https://linux-hardware.org/?probe=3d775f418d) | Oct 08, 2019 |
| Foxconn       | 8657MF-series               | Desktop     | [8ce7f69a15](https://linux-hardware.org/?probe=8ce7f69a15) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3fc14db446](https://linux-hardware.org/?probe=3fc14db446) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [af840eb366](https://linux-hardware.org/?probe=af840eb366) | Oct 04, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Intel         | powered classmate PC        | Tablet      | [05f47d610a](https://linux-hardware.org/?probe=05f47d610a) | Aug 22, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [f80cb4a7f2](https://linux-hardware.org/?probe=f80cb4a7f2) | Aug 17, 2019 |
| Dell          | 0RK936                      | Desktop     | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [e107cafe33](https://linux-hardware.org/?probe=e107cafe33) | Jun 07, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [65dd091a6f](https://linux-hardware.org/?probe=65dd091a6f) | May 13, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| Pegatron      | 2AF0                        | Desktop     | [bebc187dbd](https://linux-hardware.org/?probe=bebc187dbd) | May 05, 2019 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [c73b25ed21](https://linux-hardware.org/?probe=c73b25ed21) | Apr 24, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [d1941d4619](https://linux-hardware.org/?probe=d1941d4619) | Apr 24, 2019 |
| Lenovo        | H220 10028                  | Desktop     | [9b6593e8c6](https://linux-hardware.org/?probe=9b6593e8c6) | Apr 21, 2019 |
| ASRock        | N68C-S UCC                  | Desktop     | [ac39e69311](https://linux-hardware.org/?probe=ac39e69311) | Apr 21, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [282ee52768](https://linux-hardware.org/?probe=282ee52768) | Apr 19, 2019 |
| HP            | Pavilion dv4                | Notebook    | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [e054fab57c](https://linux-hardware.org/?probe=e054fab57c) | Nov 24, 2018 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d3d5ff2e54](https://linux-hardware.org/?probe=d3d5ff2e54) | Nov 24, 2018 |
| Intel         | powered classmate PC        | Notebook    | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | Notebook    | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [8d884b92fa](https://linux-hardware.org/?probe=8d884b92fa) | Sep 16, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [17af4fce47](https://linux-hardware.org/?probe=17af4fce47) | Sep 03, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [c501aaa553](https://linux-hardware.org/?probe=c501aaa553) | Sep 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |
| ASRock        | 945GCM-S                    | Desktop     | [009791bef2](https://linux-hardware.org/?probe=009791bef2) | Jun 25, 2017 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [270499b92c](https://linux-hardware.org/?probe=270499b92c) | Dec 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Debian 11          | 31        | 9.87%   |
| Ubuntu 20.04       | 23        | 7.32%   |
| OpenMandriva 4.3   | 18        | 5.73%   |
| Ubuntu 18.04       | 16        | 5.1%    |
| Ubuntu 22.04       | 14        | 4.46%   |
| OpenMandriva 4.2   | 10        | 3.18%   |
| Debian 10          | 10        | 3.18%   |
| KDE neon 20.04     | 9         | 2.87%   |
| Zorin 16           | 8         | 2.55%   |
| Linux Mint 20.3    | 8         | 2.55%   |
| Xubuntu 18.04      | 7         | 2.23%   |
| OpenMandriva 23.01 | 7         | 2.23%   |
| Kubuntu 20.04      | 6         | 1.91%   |
| ROSA R9            | 5         | 1.59%   |
| ROSA R11           | 5         | 1.59%   |
| Linux Mint 21.1    | 5         | 1.59%   |
| Linux Mint 20      | 5         | 1.59%   |
| Linux Mint 19.3    | 5         | 1.59%   |
| Zorin 15           | 4         | 1.27%   |
| Ubuntu MATE 19.10  | 4         | 1.27%   |
| Ubuntu 19.10       | 4         | 1.27%   |
| Fedora 35          | 4         | 1.27%   |
| Xubuntu 22.04      | 3         | 0.96%   |
| Ubuntu 21.10       | 3         | 0.96%   |
| OpenMandriva 4.50  | 3         | 0.96%   |
| Manjaro            | 3         | 0.96%   |
| KDE neon 18.04     | 3         | 0.96%   |
| Fedora 36          | 3         | 0.96%   |
| Arch Rolling       | 3         | 0.96%   |
| Xubuntu 20.04      | 2         | 0.64%   |
| Xubuntu 16.04      | 2         | 0.64%   |
| Ubuntu Unity 16.04 | 2         | 0.64%   |
| Ubuntu 20.10       | 2         | 0.64%   |
| Pop!_OS 22.04      | 2         | 0.64%   |
| Pop!_OS 21.04      | 2         | 0.64%   |
| MX 21              | 2         | 0.64%   |
| LMDE 5             | 2         | 0.64%   |
| Linux Mint 21      | 2         | 0.64%   |
| Linux Mint 20.1    | 2         | 0.64%   |
| Fedora 37          | 2         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 62        | 20.46%  |
| Debian       | 44        | 14.52%  |
| OpenMandriva | 38        | 12.54%  |
| Linux Mint   | 28        | 9.24%   |
| Xubuntu      | 14        | 4.62%   |
| ROSA         | 14        | 4.62%   |
| Zorin        | 12        | 3.96%   |
| KDE neon     | 12        | 3.96%   |
| Fedora       | 12        | 3.96%   |
| Manjaro      | 8         | 2.64%   |
| Kubuntu      | 8         | 2.64%   |
| Ubuntu MATE  | 5         | 1.65%   |
| Pop!_OS      | 5         | 1.65%   |
| Arch         | 5         | 1.65%   |
| Elementary   | 4         | 1.32%   |
| Ubuntu Unity | 3         | 0.99%   |
| MX           | 3         | 0.99%   |
| LMDE         | 3         | 0.99%   |
| Solus        | 2         | 0.66%   |
| Nobara       | 2         | 0.66%   |
| Kali         | 2         | 0.66%   |
| Garuda Linux | 2         | 0.66%   |
| Feren OS     | 2         | 0.66%   |
| ArcoLinux    | 2         | 0.66%   |
| Sparky       | 1         | 0.33%   |
| Q4OS         | 1         | 0.33%   |
| PCLinuxOS    | 1         | 0.33%   |
| openSUSE     | 1         | 0.33%   |
| Lubuntu      | 1         | 0.33%   |
| Linux Lite   | 1         | 0.33%   |
| Endless      | 1         | 0.33%   |
| Deepin       | 1         | 0.33%   |
| BunsenLabs   | 1         | 0.33%   |
| Alpine       | 1         | 0.33%   |
| AlmaLinux    | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 18        | 5.28%   |
| 5.10.14-desktop-1omv4002        | 10        | 2.93%   |
| 5.4.0-42-generic                | 8         | 2.35%   |
| 6.1.1-desktop-1omv2290          | 7         | 2.05%   |
| 5.3.0-40-generic                | 6         | 1.76%   |
| 5.15.0-56-generic               | 6         | 1.76%   |
| 5.15.0-46-generic               | 6         | 1.76%   |
| 5.4.0-77-generic                | 4         | 1.17%   |
| 5.15.0-67-generic               | 4         | 1.17%   |
| 5.13.0-39-generic               | 4         | 1.17%   |
| 5.10.0-16-amd64                 | 4         | 1.17%   |
| 5.10.0-13-amd64                 | 4         | 1.17%   |
| 5.10.0-11-amd64                 | 4         | 1.17%   |
| 5.0.0-37-generic                | 4         | 1.17%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 1.17%   |
| 4.19.0-17-amd64                 | 4         | 1.17%   |
| 5.4.0-74-generic                | 3         | 0.88%   |
| 5.4.0-73-generic                | 3         | 0.88%   |
| 5.4.0-52-generic                | 3         | 0.88%   |
| 5.3.0-29-generic                | 3         | 0.88%   |
| 5.15.0-52-generic               | 3         | 0.88%   |
| 5.11.0-37-generic               | 3         | 0.88%   |
| 4.15.0-48-generic               | 3         | 0.88%   |
| 5.8.0-63-generic                | 2         | 0.59%   |
| 5.8.0-55-generic                | 2         | 0.59%   |
| 5.8.0-44-generic                | 2         | 0.59%   |
| 5.4.0-89-generic                | 2         | 0.59%   |
| 5.4.0-66-generic                | 2         | 0.59%   |
| 5.4.0-54-generic                | 2         | 0.59%   |
| 5.4.0-48-generic                | 2         | 0.59%   |
| 5.4.0-31-generic                | 2         | 0.59%   |
| 5.4.0-26-generic                | 2         | 0.59%   |
| 5.4.0-107-generic               | 2         | 0.59%   |
| 5.3.0-42-generic                | 2         | 0.59%   |
| 5.19.0-35-generic               | 2         | 0.59%   |
| 5.19.0-2-amd64                  | 2         | 0.59%   |
| 5.15.0-60-generic               | 2         | 0.59%   |
| 5.15.0-58-generic               | 2         | 0.59%   |
| 5.15.0-53-generic               | 2         | 0.59%   |
| 5.15.0-48-generic               | 2         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 48        | 15.14%  |
| 5.15.0  | 34        | 10.73%  |
| 5.10.0  | 32        | 10.09%  |
| 4.15.0  | 24        | 7.57%   |
| 5.13.0  | 19        | 5.99%   |
| 5.16.7  | 18        | 5.68%   |
| 5.3.0   | 12        | 3.79%   |
| 4.19.0  | 12        | 3.79%   |
| 5.8.0   | 10        | 3.15%   |
| 5.10.14 | 10        | 3.15%   |
| 5.11.0  | 9         | 2.84%   |
| 6.1.1   | 7         | 2.21%   |
| 5.0.0   | 7         | 2.21%   |
| 5.19.0  | 5         | 1.58%   |
| 4.9.20  | 5         | 1.58%   |
| 5.14.10 | 3         | 0.95%   |
| 5.15.6  | 2         | 0.63%   |
| 5.12.4  | 2         | 0.63%   |
| 4.9.0   | 2         | 0.63%   |
| 4.18.0  | 2         | 0.63%   |
| 6.2.0   | 1         | 0.32%   |
| 6.1.8   | 1         | 0.32%   |
| 6.1.14  | 1         | 0.32%   |
| 6.1.10  | 1         | 0.32%   |
| 6.1.0   | 1         | 0.32%   |
| 6.0.8   | 1         | 0.32%   |
| 6.0.5   | 1         | 0.32%   |
| 6.0.2   | 1         | 0.32%   |
| 6.0.0   | 1         | 0.32%   |
| 5.9.16  | 1         | 0.32%   |
| 5.9.0   | 1         | 0.32%   |
| 5.8.6   | 1         | 0.32%   |
| 5.8.11  | 1         | 0.32%   |
| 5.8.10  | 1         | 0.32%   |
| 5.7.0   | 1         | 0.32%   |
| 5.6.6   | 1         | 0.32%   |
| 5.6.18  | 1         | 0.32%   |
| 5.6.0   | 1         | 0.32%   |
| 5.5.4   | 1         | 0.32%   |
| 5.4.83  | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 50        | 15.92%  |
| 5.10    | 48        | 15.29%  |
| 5.15    | 43        | 13.69%  |
| 4.15    | 24        | 7.64%   |
| 5.13    | 22        | 7.01%   |
| 5.16    | 20        | 6.37%   |
| 5.8     | 13        | 4.14%   |
| 5.3     | 12        | 3.82%   |
| 4.19    | 12        | 3.82%   |
| 6.1     | 11        | 3.5%    |
| 5.11    | 9         | 2.87%   |
| 5.19    | 7         | 2.23%   |
| 5.0     | 7         | 2.23%   |
| 4.9     | 7         | 2.23%   |
| 6.0     | 4         | 1.27%   |
| 5.17    | 4         | 1.27%   |
| 5.6     | 3         | 0.96%   |
| 5.14    | 3         | 0.96%   |
| 5.12    | 3         | 0.96%   |
| 5.9     | 2         | 0.64%   |
| 5.18    | 2         | 0.64%   |
| 4.18    | 2         | 0.64%   |
| 6.2     | 1         | 0.32%   |
| 5.7     | 1         | 0.32%   |
| 5.5     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.13    | 1         | 0.32%   |
| 4.1     | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 265       | 90.75%  |
| i686   | 27        | 9.25%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 96        | 31.07%  |
| KDE5            | 71        | 22.98%  |
| XFCE            | 40        | 12.94%  |
| Unknown         | 26        | 8.41%   |
| X-Cinnamon      | 20        | 6.47%   |
| MATE            | 13        | 4.21%   |
| KDE             | 12        | 3.88%   |
| KDE4            | 7         | 2.27%   |
| Cinnamon        | 5         | 1.62%   |
| LXDE            | 4         | 1.29%   |
| Unity           | 3         | 0.97%   |
| Pantheon        | 3         | 0.97%   |
| LXQt            | 2         | 0.65%   |
| GNOME Classic   | 2         | 0.65%   |
| Budgie          | 2         | 0.65%   |
| xmonad          | 1         | 0.32%   |
| GNOME Flashback | 1         | 0.32%   |
| Deepin          | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 251       | 85.08%  |
| Wayland | 37        | 12.54%  |
| Unknown | 5         | 1.69%   |
| Tty     | 2         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 118       | 39.2%   |
| SDDM    | 62        | 20.6%   |
| LightDM | 42        | 13.95%  |
| GDM     | 38        | 12.62%  |
| GDM3    | 22        | 7.31%   |
| TDM     | 10        | 3.32%   |
| KDM     | 7         | 2.33%   |
| SLiM    | 2         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 176       | 59.06%  |
| en_US   | 71        | 23.83%  |
| Unknown | 25        | 8.39%   |
| es_ES   | 16        | 5.37%   |
| es_US   | 4         | 1.34%   |
| C       | 2         | 0.67%   |
| es_MX   | 1         | 0.34%   |
| es_CO   | 1         | 0.34%   |
| en_CA   | 1         | 0.34%   |
| de_DE   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 216       | 73.47%  |
| EFI  | 78        | 26.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 225       | 76.53%  |
| Overlay | 38        | 12.93%  |
| Btrfs   | 17        | 5.78%   |
| Unknown | 8         | 2.72%   |
| Xfs     | 4         | 1.36%   |
| Ext2    | 2         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 135       | 45.61%  |
| MBR     | 85        | 28.72%  |
| GPT     | 76        | 25.68%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 242       | 81.76%  |
| Yes       | 54        | 18.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 61.64%  |
| Yes       | 112       | 38.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 34        | 11.72%  |
| Dell                           | 32        | 11.03%  |
| Hewlett-Packard                | 29        | 10%     |
| ASRock                         | 26        | 8.97%   |
| Intel                          | 25        | 8.62%   |
| VIT                            | 23        | 7.93%   |
| ASUSTek Computer               | 17        | 5.86%   |
| ECS                            | 15        | 5.17%   |
| Pegatron                       | 13        | 4.48%   |
| Gigabyte Technology            | 12        | 4.14%   |
| Acer                           | 9         | 3.1%    |
| Biostar                        | 8         | 2.76%   |
| MSI                            | 6         | 2.07%   |
| Unknown                        | 6         | 2.07%   |
| langchao                       | 4         | 1.38%   |
| Foxconn                        | 4         | 1.38%   |
| Apple                          | 4         | 1.38%   |
| Shanghai Zhaoxin Semiconductor | 3         | 1.03%   |
| Google                         | 3         | 1.03%   |
| Toshiba                        | 2         | 0.69%   |
| UNIQCELL                       | 1         | 0.34%   |
| Standard                       | 1         | 0.34%   |
| Sony                           | 1         | 0.34%   |
| Soncview                       | 1         | 0.34%   |
| SIRAGON                        | 1         | 0.34%   |
| Samsung Electronics            | 1         | 0.34%   |
| IP3 Tech                       | 1         | 0.34%   |
| Inspur                         | 1         | 0.34%   |
| IBM                            | 1         | 0.34%   |
| GPU Company                    | 1         | 0.34%   |
| Gateway                        | 1         | 0.34%   |
| Exo                            | 1         | 0.34%   |
| Clevo                          | 1         | 0.34%   |
| AVITA                          | 1         | 0.34%   |
| Alienware                      | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Intel powered classmate PC          | 11        | 3.79%   |
| ECS H61H2-CM                        | 8         | 2.76%   |
| ASRock G41M-VS3                     | 6         | 2.07%   |
| Unknown                             | 6         | 2.07%   |
| VIT P2400                           | 5         | 1.72%   |
| VIT P2402                           | 4         | 1.38%   |
| langchao 12345                      | 4         | 1.38%   |
| VIT P3400                           | 3         | 1.03%   |
| VIT M2420                           | 3         | 1.03%   |
| Shanghai Zhaoxin ZXE CRB            | 3         | 1.03%   |
| HP Compaq 8200 Elite SFF PC         | 3         | 1.03%   |
| ASRock N68C-S UCC                   | 3         | 1.03%   |
| ASRock N68-VS3 UCC                  | 3         | 1.03%   |
| VIT P1400                           | 2         | 0.69%   |
| VIT M2421                           | 2         | 0.69%   |
| VIT Aptio CRB                       | 2         | 0.69%   |
| Pegatron Compaq dx2400 Microtower   | 2         | 0.69%   |
| Lenovo IdeaPad S100c 20194          | 2         | 0.69%   |
| Lenovo 3000 N200 0769ARS            | 2         | 0.69%   |
| Intel H61                           | 2         | 0.69%   |
| HP Compaq Presario C700             | 2         | 0.69%   |
| Google Candy                        | 2         | 0.69%   |
| ECS G31T-M7                         | 2         | 0.69%   |
| Dell OptiPlex 9020                  | 2         | 0.69%   |
| Dell Inspiron 1545                  | 2         | 0.69%   |
| Apple iMac11,2                      | 2         | 0.69%   |
| Acer Aspire 4739Z                   | 2         | 0.69%   |
| VIT NP3020M3                        | 1         | 0.34%   |
| VIT M2400-01                        | 1         | 0.34%   |
| UNIQCELL Q15.6                      | 1         | 0.34%   |
| Toshiba Satellite E55t-A            | 1         | 0.34%   |
| Toshiba ENCORE 2 WT8-B              | 1         | 0.34%   |
| Standard AIO                        | 1         | 0.34%   |
| Sony VGN-FW510F                     | 1         | 0.34%   |
| Soncview G41D3C                     | 1         | 0.34%   |
| SIRAGON AIO-5150                    | 1         | 0.34%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.34%   |
| Pegatron T14AF                      | 1         | 0.34%   |
| Pegatron PEGATRON                   | 1         | 0.34%   |
| Pegatron IPPEL-DB                   | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 12        | 4.14%   |
| Intel powered        | 11        | 3.79%   |
| HP Compaq            | 11        | 3.79%   |
| Lenovo IdeaPad       | 8         | 2.76%   |
| ECS H61H2-CM         | 8         | 2.76%   |
| Acer Aspire          | 8         | 2.76%   |
| Lenovo ThinkCentre   | 7         | 2.41%   |
| HP Pavilion          | 7         | 2.41%   |
| Lenovo ThinkPad      | 6         | 2.07%   |
| Dell Vostro          | 6         | 2.07%   |
| Dell Latitude        | 6         | 2.07%   |
| ASRock G41M-VS3      | 6         | 2.07%   |
| Unknown              | 6         | 2.07%   |
| VIT P2400            | 5         | 1.72%   |
| Dell OptiPlex        | 5         | 1.72%   |
| VIT P2402            | 4         | 1.38%   |
| langchao 12345       | 4         | 1.38%   |
| VIT P3400            | 3         | 1.03%   |
| VIT M2420            | 3         | 1.03%   |
| Shanghai Zhaoxin ZXE | 3         | 1.03%   |
| Pegatron Compaq      | 3         | 1.03%   |
| Lenovo 3000          | 3         | 1.03%   |
| ASRock N68C-S        | 3         | 1.03%   |
| ASRock N68-VS3       | 3         | 1.03%   |
| VIT P1400            | 2         | 0.69%   |
| VIT M2421            | 2         | 0.69%   |
| VIT Aptio            | 2         | 0.69%   |
| Lenovo Legion        | 2         | 0.69%   |
| Intel H61            | 2         | 0.69%   |
| HP Presario          | 2         | 0.69%   |
| HP ENVY              | 2         | 0.69%   |
| HP EliteBook         | 2         | 0.69%   |
| Google Candy         | 2         | 0.69%   |
| ECS G31T-M7          | 2         | 0.69%   |
| Dell Precision       | 2         | 0.69%   |
| ASUS VivoBook        | 2         | 0.69%   |
| ASUS P5G41T-M        | 2         | 0.69%   |
| ASUS ASUS            | 2         | 0.69%   |
| Apple iMac11         | 2         | 0.69%   |
| VIT NP3020M3         | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 53        | 18.28%  |
| 2010    | 42        | 14.48%  |
| 2012    | 31        | 10.69%  |
| 2008    | 22        | 7.59%   |
| 2007    | 21        | 7.24%   |
| 2013    | 20        | 6.9%    |
| 2014    | 16        | 5.52%   |
| 2020    | 13        | 4.48%   |
| 2021    | 9         | 3.1%    |
| 2022    | 8         | 2.76%   |
| 2019    | 8         | 2.76%   |
| 2017    | 8         | 2.76%   |
| 2015    | 8         | 2.76%   |
| 2009    | 8         | 2.76%   |
| 2006    | 8         | 2.76%   |
| 2018    | 7         | 2.41%   |
| 2016    | 4         | 1.38%   |
| Unknown | 2         | 0.69%   |
| 2023    | 1         | 0.34%   |
| 2005    | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 140       | 48.28%  |
| Notebook    | 132       | 45.52%  |
| All in one  | 6         | 2.07%   |
| Tablet      | 4         | 1.38%   |
| Mini pc     | 3         | 1.03%   |
| Server      | 3         | 1.03%   |
| Convertible | 2         | 0.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 286       | 98.62%  |
| Enabled  | 4         | 1.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 287       | 98.97%  |
| Yes  | 3         | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 83        | 28.23%  |
| 4.01-8.0    | 63        | 21.43%  |
| 1.01-2.0    | 52        | 17.69%  |
| 8.01-16.0   | 42        | 14.29%  |
| 16.01-24.0  | 27        | 9.18%   |
| 2.01-3.0    | 11        | 3.74%   |
| 32.01-64.0  | 7         | 2.38%   |
| 24.01-32.0  | 4         | 1.36%   |
| 0.51-1.0    | 3         | 1.02%   |
| 64.01-256.0 | 2         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 126       | 39.38%  |
| 2.01-3.0   | 81        | 25.31%  |
| 0.51-1.0   | 44        | 13.75%  |
| 4.01-8.0   | 36        | 11.25%  |
| 3.01-4.0   | 23        | 7.19%   |
| 8.01-16.0  | 5         | 1.56%   |
| 0.01-0.5   | 4         | 1.25%   |
| 16.01-24.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 182       | 61.28%  |
| 2      | 93        | 31.31%  |
| 3      | 17        | 5.72%   |
| 4      | 3         | 1.01%   |
| 6      | 1         | 0.34%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 161       | 54.76%  |
| Yes       | 133       | 45.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 91.78%  |
| No        | 24        | 8.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 73.97%  |
| No        | 76        | 26.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 191       | 65.19%  |
| Yes       | 102       | 34.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 290       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 138       | 43.95%  |
| Maracaibo                  | 21        | 6.69%   |
| Barquisimeto               | 17        | 5.41%   |
| Maracay                    | 16        | 5.1%    |
| Valencia                   | 13        | 4.14%   |
| San Cristóbal             | 9         | 2.87%   |
| Mérida                    | 9         | 2.87%   |
| Maturín                   | 8         | 2.55%   |
| Barcelona                  | 7         | 2.23%   |
| San Carlos del Zulia       | 6         | 1.91%   |
| Ciudad Guayana             | 4         | 1.27%   |
| Barinas                    | 4         | 1.27%   |
| San Antonio de Los Altos   | 3         | 0.96%   |
| Parroquia El Recreo        | 3         | 0.96%   |
| Lecherias                  | 3         | 0.96%   |
| Ciudad Bolívar            | 3         | 0.96%   |
| Carrizal                   | 3         | 0.96%   |
| Acarigua                   | 3         | 0.96%   |
| San Juan Bautista          | 2         | 0.64%   |
| Porlamar                   | 2         | 0.64%   |
| Los Teques                 | 2         | 0.64%   |
| Los Palos Grandes          | 2         | 0.64%   |
| Las Vegas                  | 2         | 0.64%   |
| Guatire                    | 2         | 0.64%   |
| Guarenas                   | 2         | 0.64%   |
| Cua                        | 2         | 0.64%   |
| Cabudare                   | 2         | 0.64%   |
| Anaco                      | 2         | 0.64%   |
| Valle de La Pascua         | 1         | 0.32%   |
| Tucupita                   | 1         | 0.32%   |
| Tucape                     | 1         | 0.32%   |
| Santa Rita                 | 1         | 0.32%   |
| San Francisco              | 1         | 0.32%   |
| San Felipe                 | 1         | 0.32%   |
| San Diego                  | 1         | 0.32%   |
| Punto Fijo                 | 1         | 0.32%   |
| Puerto Ordaz and San Felix | 1         | 0.32%   |
| Puerto Cumarebo            | 1         | 0.32%   |
| Puerto Cruz                | 1         | 0.32%   |
| Naguanagua                 | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 91        | 128    | 24.46%  |
| Seagate             | 87        | 131    | 23.39%  |
| Hitachi             | 35        | 49     | 9.41%   |
| Toshiba             | 29        | 30     | 7.8%    |
| Samsung Electronics | 28        | 32     | 7.53%   |
| Kingston            | 14        | 17     | 3.76%   |
| Unknown             | 12        | 16     | 3.23%   |
| SanDisk             | 7         | 11     | 1.88%   |
| SK hynix            | 6         | 7      | 1.61%   |
| PNY                 | 6         | 7      | 1.61%   |
| Intel               | 6         | 9      | 1.61%   |
| Crucial             | 6         | 8      | 1.61%   |
| Maxtor              | 5         | 5      | 1.34%   |
| HGST                | 5         | 5      | 1.34%   |
| SPCC                | 4         | 6      | 1.08%   |
| LITEONIT            | 4         | 7      | 1.08%   |
| Team                | 3         | 3      | 0.81%   |
| Fujitsu             | 3         | 3      | 0.81%   |
| Patriot             | 2         | 2      | 0.54%   |
| Micron Technology   | 2         | 5      | 0.54%   |
| HUAWEI              | 2         | 2      | 0.54%   |
| addlink             | 2         | 2      | 0.54%   |
| Vaseky              | 1         | 1      | 0.27%   |
| Silicon Motion      | 1         | 1      | 0.27%   |
| PUSKILL             | 1         | 1      | 0.27%   |
| Phison Electronics  | 1         | 1      | 0.27%   |
| Phison              | 1         | 1      | 0.27%   |
| Lexar               | 1         | 1      | 0.27%   |
| KingFast            | 1         | 2      | 0.27%   |
| Intenso             | 1         | 1      | 0.27%   |
| ExcelStor           | 1         | 1      | 0.27%   |
| Dogfish             | 1         | 1      | 0.27%   |
| Dell                | 1         | 2      | 0.27%   |
| BIWIN               | 1         | 2      | 0.27%   |
| Apacer              | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 16        | 3.92%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 8         | 1.96%   |
| Toshiba DT01ACA050 500GB            | 8         | 1.96%   |
| Seagate ST320LM000 HM321HI 320GB    | 5         | 1.23%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 1.23%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 0.98%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 0.98%   |
| Seagate ST500DM002-1BD142 500GB     | 4         | 0.98%   |
| Seagate ST3320418AS 320GB           | 4         | 0.98%   |
| Seagate ST320LT012-9WS14C 320GB     | 4         | 0.98%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 0.98%   |
| Samsung HD502HJ 500GB               | 4         | 0.98%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.74%   |
| WDC WD5000AAKX-221CA1 500GB         | 3         | 0.74%   |
| WDC WD5000AAKX-001CA0 500GB         | 3         | 0.74%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 0.74%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 0.74%   |
| WDC WD3200AAJS-08L7A0 320GB         | 3         | 0.74%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.74%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 0.74%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.74%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 0.74%   |
| Samsung HD161HJ 160GB               | 3         | 0.74%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 0.74%   |
| Hitachi HTS542580K9SA00 80GB        | 3         | 0.74%   |
| Hitachi HDS728080PLA380 82GB        | 3         | 0.74%   |
| WDC WD800BD-22MRA1 80GB             | 2         | 0.49%   |
| WDC WD800BB-22JHC0 80GB             | 2         | 0.49%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.49%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 2         | 0.49%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2         | 0.49%   |
| WDC WD1200BEVS-60UST0 120GB         | 2         | 0.49%   |
| Unknown MMC Card  16GB              | 2         | 0.49%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.49%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.49%   |
| Toshiba MQ01ABF032 320GB            | 2         | 0.49%   |
| Toshiba MK3275GSX 320GB             | 2         | 0.49%   |
| SPCC Solid State Disk 128GB         | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 88        | 122    | 32.47%  |
| Seagate             | 85        | 129    | 31.37%  |
| Hitachi             | 35        | 49     | 12.92%  |
| Toshiba             | 28        | 29     | 10.33%  |
| Samsung Electronics | 19        | 22     | 7.01%   |
| Maxtor              | 5         | 5      | 1.85%   |
| HGST                | 5         | 5      | 1.85%   |
| Fujitsu             | 3         | 3      | 1.11%   |
| Unknown             | 2         | 2      | 0.74%   |
| ExcelStor           | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 15     | 21.05%  |
| PNY                 | 6         | 7      | 10.53%  |
| Crucial             | 6         | 8      | 10.53%  |
| Samsung Electronics | 5         | 6      | 8.77%   |
| LITEONIT            | 4         | 7      | 7.02%   |
| SPCC                | 3         | 4      | 5.26%   |
| SanDisk             | 3         | 4      | 5.26%   |
| Team                | 2         | 2      | 3.51%   |
| SK hynix            | 2         | 2      | 3.51%   |
| Patriot             | 2         | 2      | 3.51%   |
| Vaseky              | 1         | 1      | 1.75%   |
| Toshiba             | 1         | 1      | 1.75%   |
| PUSKILL             | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 3      | 1.75%   |
| Lexar               | 1         | 1      | 1.75%   |
| KingFast            | 1         | 2      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| Dogfish             | 1         | 1      | 1.75%   |
| Dell                | 1         | 2      | 1.75%   |
| BIWIN               | 1         | 2      | 1.75%   |
| addlink             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 224       | 367    | 69.57%  |
| SSD     | 55        | 74     | 17.08%  |
| NVMe    | 32        | 46     | 9.94%   |
| MMC     | 7         | 10     | 2.17%   |
| Unknown | 4         | 4      | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 260       | 438    | 84.97%  |
| NVMe | 32        | 46     | 10.46%  |
| SAS  | 7         | 7      | 2.29%   |
| MMC  | 7         | 10     | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 233       | 353    | 79.52%  |
| 0.51-1.0   | 44        | 63     | 15.02%  |
| 1.01-2.0   | 12        | 20     | 4.1%    |
| 3.01-4.0   | 2         | 2      | 0.68%   |
| 2.01-3.0   | 2         | 3      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 99        | 32.04%  |
| 101-250        | 67        | 21.68%  |
| 501-1000       | 45        | 14.56%  |
| 1-20           | 36        | 11.65%  |
| 51-100         | 25        | 8.09%   |
| 21-50          | 14        | 4.53%   |
| 1001-2000      | 11        | 3.56%   |
| 2001-3000      | 5         | 1.62%   |
| Unknown        | 5         | 1.62%   |
| More than 3000 | 2         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 128       | 40.13%  |
| 21-50          | 57        | 17.87%  |
| 101-250        | 47        | 14.73%  |
| 51-100         | 32        | 10.03%  |
| 251-500        | 30        | 9.4%    |
| 501-1000       | 12        | 3.76%   |
| Unknown        | 5         | 1.57%   |
| 2001-3000      | 3         | 0.94%   |
| 1001-2000      | 3         | 0.94%   |
| More than 3000 | 2         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 6         | 7      | 6.98%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 4         | 5      | 4.65%   |
| Toshiba DT01ACA050 500GB          | 3         | 4      | 3.49%   |
| WDC WD5000AAKX-221CA1 500GB       | 2         | 2      | 2.33%   |
| WDC WD5000AAKS-00A7B0 500GB       | 2         | 2      | 2.33%   |
| WDC WD1200BEVS-60UST0 120GB       | 2         | 2      | 2.33%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 2.33%   |
| Samsung Electronics HM321HI 320GB | 2         | 2      | 2.33%   |
| Hitachi HDS728080PLA380 82GB      | 2         | 2      | 2.33%   |
| Hitachi HDS721616PLA380 160GB     | 2         | 2      | 2.33%   |
| WDC WD800BD-08MRA1 80GB           | 1         | 1      | 1.16%   |
| WDC WD800BB-22JHC0 80GB           | 1         | 1      | 1.16%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 1.16%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1         | 1      | 1.16%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 1      | 1.16%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 2      | 1.16%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1         | 1      | 1.16%   |
| WDC WD50 00BPVT-24HXZT1 500GB     | 1         | 1      | 1.16%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 1.16%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1         | 1      | 1.16%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 1      | 1.16%   |
| WDC WD3200AAJS-08L7A0 320GB       | 1         | 2      | 1.16%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1         | 1      | 1.16%   |
| WDC WD10JPVX-22JC3T0 1TB          | 1         | 2      | 1.16%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1         | 1      | 1.16%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1         | 1      | 1.16%   |
| Toshiba MQ01ACF050 500GB          | 1         | 1      | 1.16%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 1.16%   |
| Toshiba MK3275GSX 320GB           | 1         | 1      | 1.16%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 1.16%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 1.16%   |
| Seagate ST9160314AS 160GB         | 1         | 1      | 1.16%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 1.16%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 1.16%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1         | 1      | 1.16%   |
| Seagate ST3500630AS 500GB         | 1         | 1      | 1.16%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 1.16%   |
| Seagate ST3500413AS 500GB         | 1         | 1      | 1.16%   |
| Seagate ST3500312CS 500GB         | 1         | 1      | 1.16%   |
| Seagate ST340014AS 40GB           | 1         | 1      | 1.16%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 31.65%  |
| WDC                 | 20        | 30     | 25.32%  |
| Hitachi             | 14        | 14     | 17.72%  |
| Samsung Electronics | 7         | 8      | 8.86%   |
| Toshiba             | 6         | 7      | 7.59%   |
| Maxtor              | 2         | 2      | 2.53%   |
| Intel               | 2         | 2      | 2.53%   |
| HGST                | 2         | 2      | 2.53%   |
| ExcelStor           | 1         | 1      | 1.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 32.47%  |
| WDC                 | 20        | 30     | 25.97%  |
| Hitachi             | 14        | 14     | 18.18%  |
| Samsung Electronics | 7         | 8      | 9.09%   |
| Toshiba             | 6         | 7      | 7.79%   |
| Maxtor              | 2         | 2      | 2.6%    |
| HGST                | 2         | 2      | 2.6%    |
| ExcelStor           | 1         | 1      | 1.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 65        | 92     | 97.01%  |
| NVMe | 2         | 2      | 2.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB | 2         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 157       | 280    | 49.84%  |
| Works    | 89        | 125    | 28.25%  |
| Malfunc  | 67        | 94     | 21.27%  |
| Failed   | 2         | 2      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 229       | 71.56%  |
| AMD                         | 31        | 9.69%   |
| Nvidia                      | 15        | 4.69%   |
| SanDisk                     | 7         | 2.19%   |
| Marvell Technology Group    | 6         | 1.88%   |
| JMicron Technology          | 6         | 1.88%   |
| SK hynix                    | 4         | 1.25%   |
| Samsung Electronics         | 4         | 1.25%   |
| Phison Electronics          | 4         | 1.25%   |
| Jiangsu Huacun Elec.        | 4         | 1.25%   |
| VIA Technologies            | 3         | 0.94%   |
| Silicon Motion              | 2         | 0.63%   |
| Kingston Technology Company | 2         | 0.63%   |
| Micron Technology           | 1         | 0.31%   |
| ASMedia Technology          | 1         | 0.31%   |
| Adaptec                     | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 36        | 8.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 28        | 6.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 5.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19        | 4.5%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 19        | 4.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 3.55%   |
| Nvidia MCP61 SATA Controller                                                            | 14        | 3.32%   |
| Nvidia MCP61 IDE                                                                        | 12        | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 2.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 1.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.9%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.66%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 1.42%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 1.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.18%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1.18%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.18%   |
| Jiangsu Huacun Elec. Non-Volatile memory controller                                     | 4         | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 4         | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.95%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.71%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 0.71%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.71%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3         | 0.71%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 0.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.71%   |
| VIA Serial ATA Controller                                                               | 2         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 171       | 51.51%  |
| IDE  | 110       | 33.13%  |
| NVMe | 32        | 9.64%   |
| RAID | 17        | 5.12%   |
| SAS  | 1         | 0.3%    |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 238       | 82.07%  |
| AMD          | 49        | 16.9%   |
| CentaurHauls | 3         | 1.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 6         | 2.07%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 6         | 2.07%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 6         | 2.07%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 6         | 2.07%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 6         | 2.07%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz    | 4         | 1.38%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 4         | 1.38%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 4         | 1.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 4         | 1.38%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 1.38%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 4         | 1.38%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 3         | 1.03%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 1.03%   |
| Intel Pentium 4 CPU 3.00GHz                    | 3         | 1.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 3         | 1.03%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 3         | 1.03%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 3         | 1.03%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3         | 1.03%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3         | 1.03%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 1.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 3         | 1.03%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 1.03%   |
| AMD Sempron 145 Processor                      | 3         | 1.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 3         | 1.03%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 0.69%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz    | 2         | 0.69%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 2         | 0.69%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz         | 2         | 0.69%   |
| Intel Pentium CPU N3710 @ 1.60GHz              | 2         | 0.69%   |
| Intel Pentium CPU G640 @ 2.80GHz               | 2         | 0.69%   |
| Intel Pentium CPU 2030M @ 2.50GHz              | 2         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 0.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2         | 0.69%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 0.69%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 0.69%   |
| Intel Core i5-3330 CPU @ 3.00GHz               | 2         | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 0.69%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 2         | 0.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 2         | 0.69%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 44        | 15.17%  |
| Intel Core i3                  | 33        | 11.38%  |
| Intel Pentium Dual-Core        | 25        | 8.62%   |
| Intel Core 2 Duo               | 22        | 7.59%   |
| Intel Core i7                  | 21        | 7.24%   |
| Intel Celeron                  | 21        | 7.24%   |
| Intel Pentium                  | 18        | 6.21%   |
| Other                          | 13        | 4.48%   |
| Intel Atom                     | 10        | 3.45%   |
| Intel Pentium Dual             | 9         | 3.1%    |
| AMD Ryzen 5                    | 8         | 2.76%   |
| Intel Xeon                     | 7         | 2.41%   |
| AMD Sempron                    | 7         | 2.41%   |
| Intel Core 2 Quad              | 5         | 1.72%   |
| Intel Pentium 4                | 4         | 1.38%   |
| Intel Core 2                   | 4         | 1.38%   |
| AMD Ryzen 7                    | 4         | 1.38%   |
| AMD FX                         | 3         | 1.03%   |
| AMD Athlon II X2               | 3         | 1.03%   |
| Intel Pentium D                | 2         | 0.69%   |
| Intel Genuine                  | 2         | 0.69%   |
| AMD Ryzen 3                    | 2         | 0.69%   |
| AMD Phenom II X4               | 2         | 0.69%   |
| AMD Phenom                     | 2         | 0.69%   |
| AMD E1                         | 2         | 0.69%   |
| AMD Athlon II X4               | 2         | 0.69%   |
| AMD Athlon                     | 2         | 0.69%   |
| AMD A6                         | 2         | 0.69%   |
| AMD A10                        | 2         | 0.69%   |
| Intel Pentium Silver           | 1         | 0.34%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.34%   |
| AMD Phenom II X2               | 1         | 0.34%   |
| AMD Mobile Sempron             | 1         | 0.34%   |
| AMD E                          | 1         | 0.34%   |
| AMD Athlon II                  | 1         | 0.34%   |
| AMD Athlon 64 X2               | 1         | 0.34%   |
| AMD A8                         | 1         | 0.34%   |
| AMD A4                         | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 172       | 59.31%  |
| 4       | 75        | 25.86%  |
| 1       | 20        | 6.9%    |
| 6       | 9         | 3.1%    |
| 8       | 5         | 1.72%   |
| 3       | 4         | 1.38%   |
| Unknown | 4         | 1.38%   |
| 14      | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 290       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 169       | 58.28%  |
| 2       | 117       | 40.34%  |
| Unknown | 4         | 1.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 96.55%  |
| 64-bit         | 5         | 1.72%   |
| 32-bit         | 4         | 1.38%   |
| Unknown        | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 18.18%  |
| 0x1067a    | 40        | 13.47%  |
| 0x206a7    | 37        | 12.46%  |
| 0x306a9    | 25        | 8.42%   |
| 0x6fd      | 12        | 4.04%   |
| 0x306c3    | 9         | 3.03%   |
| 0x30673    | 6         | 2.02%   |
| 0x106ca    | 6         | 2.02%   |
| 0x806e9    | 5         | 1.68%   |
| 0x806c1    | 5         | 1.68%   |
| 0x20655    | 5         | 1.68%   |
| 0x010000c8 | 5         | 1.68%   |
| 0xf65      | 4         | 1.35%   |
| 0x6fb      | 4         | 1.35%   |
| 0x30678    | 4         | 1.35%   |
| 0x6f2      | 3         | 1.01%   |
| 0x40651    | 3         | 1.01%   |
| 0x106a5    | 3         | 1.01%   |
| 0x10676    | 3         | 1.01%   |
| 0x05000119 | 3         | 1.01%   |
| 0x010000c7 | 3         | 1.01%   |
| 0xa0671    | 2         | 0.67%   |
| 0x906e9    | 2         | 0.67%   |
| 0x406e3    | 2         | 0.67%   |
| 0x406c4    | 2         | 0.67%   |
| 0x306d4    | 2         | 0.67%   |
| 0x08608103 | 2         | 0.67%   |
| 0x08600104 | 2         | 0.67%   |
| 0x08108102 | 2         | 0.67%   |
| 0x0810100b | 2         | 0.67%   |
| 0x0600063e | 2         | 0.67%   |
| 0x010000b6 | 2         | 0.67%   |
| 0xf47      | 1         | 0.34%   |
| 0xf41      | 1         | 0.34%   |
| 0x906eb    | 1         | 0.34%   |
| 0x906ea    | 1         | 0.34%   |
| 0x806ec    | 1         | 0.34%   |
| 0x806ea    | 1         | 0.34%   |
| 0x806d1    | 1         | 0.34%   |
| 0x706e5    | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 46        | 15.86%  |
| Penryn           | 44        | 15.17%  |
| IvyBridge        | 31        | 10.69%  |
| Core             | 26        | 8.97%   |
| K10              | 16        | 5.52%   |
| Haswell          | 14        | 4.83%   |
| Silvermont       | 13        | 4.48%   |
| KabyLake         | 13        | 4.48%   |
| Westmere         | 11        | 3.79%   |
| Bonnell          | 9         | 3.1%    |
| Unknown          | 7         | 2.41%   |
| NetBurst         | 6         | 2.07%   |
| Zen+             | 5         | 1.72%   |
| TigerLake        | 5         | 1.72%   |
| Zen 2            | 4         | 1.38%   |
| K8 Hammer        | 4         | 1.38%   |
| Zen              | 3         | 1.03%   |
| Skylake          | 3         | 1.03%   |
| Nehalem          | 3         | 1.03%   |
| IceLake          | 3         | 1.03%   |
| Broadwell        | 3         | 1.03%   |
| Bobcat           | 3         | 1.03%   |
| Piledriver       | 2         | 0.69%   |
| K10 Llano        | 2         | 0.69%   |
| Goldmont plus    | 2         | 0.69%   |
| Excavator        | 2         | 0.69%   |
| Bulldozer        | 2         | 0.69%   |
| Zen 3            | 1         | 0.34%   |
| Steamroller      | 1         | 0.34%   |
| P6               | 1         | 0.34%   |
| K8 & K10 hybrid  | 1         | 0.34%   |
| Jaguar           | 1         | 0.34%   |
| Goldmont         | 1         | 0.34%   |
| CometLake        | 1         | 0.34%   |
| Alderlake Hybrid | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 201       | 64.63%  |
| AMD                        | 53        | 17.04%  |
| Nvidia                     | 49        | 15.76%  |
| Zhaoxin                    | 3         | 0.96%   |
| VIA Technologies           | 3         | 0.96%   |
| Matrox Electronics Systems | 1         | 0.32%   |
| ASPEED Technology          | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 41        | 12.65%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 5.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 3.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 3.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.47%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 8         | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 2.16%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 2.16%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6         | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.54%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 4         | 1.23%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4         | 1.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.23%   |
| Intel HD Graphics 620                                                                    | 4         | 1.23%   |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 4         | 1.23%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 3         | 0.93%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.93%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.93%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3         | 0.93%   |
| Intel HD Graphics 630                                                                    | 3         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.93%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3         | 0.93%   |
| AMD Renoir                                                                               | 3         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.93%   |
| Nvidia TU117M                                                                            | 2         | 0.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.62%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.62%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2         | 0.62%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2         | 0.62%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 184       | 63.23%  |
| 1 x AMD         | 46        | 15.81%  |
| 1 x Nvidia      | 39        | 13.4%   |
| Intel + Nvidia  | 6         | 2.06%   |
| 1 x Zhaoxin     | 3         | 1.03%   |
| 1 x VIA         | 3         | 1.03%   |
| AMD + Nvidia    | 3         | 1.03%   |
| 2 x AMD         | 2         | 0.69%   |
| Intel + AMD     | 2         | 0.69%   |
| 2 x Intel       | 1         | 0.34%   |
| Nvidia + ASPEED | 1         | 0.34%   |
| 1 x Matrox      | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 251       | 86.25%  |
| Proprietary | 23        | 7.9%    |
| Unknown     | 17        | 5.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 196       | 65.77%  |
| 0.01-0.5   | 41        | 13.76%  |
| 0.51-1.0   | 29        | 9.73%   |
| 1.01-2.0   | 23        | 7.72%   |
| 3.01-4.0   | 8         | 2.68%   |
| 5.01-6.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 57        | 19.86%  |
| BOE                                   | 23        | 8.01%   |
| AU Optronics                          | 20        | 6.97%   |
| LG Display                            | 19        | 6.62%   |
| Hewlett-Packard                       | 17        | 5.92%   |
| Goldstar                              | 17        | 5.92%   |
| Lenovo                                | 14        | 4.88%   |
| Chimei Innolux                        | 14        | 4.88%   |
| Dell                                  | 13        | 4.53%   |
| Toshiba                               | 10        | 3.48%   |
| InfoVision                            | 9         | 3.14%   |
| Acer                                  | 9         | 3.14%   |
| AOC                                   | 8         | 2.79%   |
| Chi Mei Optoelectronics               | 7         | 2.44%   |
| Vita                                  | 5         | 1.74%   |
| LG Philips                            | 5         | 1.74%   |
| HannStar                              | 4         | 1.39%   |
| Apple                                 | 4         | 1.39%   |
| BenQ                                  | 3         | 1.05%   |
| ViewSonic                             | 2         | 0.7%    |
| Sony                                  | 2         | 0.7%    |
| PANDA                                 | 2         | 0.7%    |
| MStar                                 | 2         | 0.7%    |
| ITL                                   | 2         | 0.7%    |
| Envision                              | 2         | 0.7%    |
| Vizio                                 | 1         | 0.35%   |
| Unknown (XXX)                         | 1         | 0.35%   |
| Toshiba Matsushita Display Technology | 1         | 0.35%   |
| TCL                                   | 1         | 0.35%   |
| Sharp                                 | 1         | 0.35%   |
| Sceptre Tech                          | 1         | 0.35%   |
| Plain Tree Systems                    | 1         | 0.35%   |
| PEGA                                  | 1         | 0.35%   |
| Parker                                | 1         | 0.35%   |
| LSC                                   | 1         | 0.35%   |
| LG Electronics                        | 1         | 0.35%   |
| LED                                   | 1         | 0.35%   |
| KTC                                   | 1         | 0.35%   |
| InnoLux Display                       | 1         | 0.35%   |
| IBM                                   | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 7         | 2.41%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 6         | 2.06%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 5         | 1.72%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 5         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 5         | 1.72%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4         | 1.37%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 4         | 1.37%   |
| Toshiba TV TSB0206 1920x1080                                         | 3         | 1.03%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 1.03%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 3         | 1.03%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 2         | 0.69%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2         | 0.69%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.69%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.69%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.69%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.69%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                      | 2         | 0.69%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.69%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                     | 2         | 0.69%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.69%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 2         | 0.69%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.69%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                   | 2         | 0.69%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 2         | 0.69%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 2         | 0.69%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.69%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                      | 2         | 0.69%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                 | 1         | 0.34%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1         | 0.34%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch        | 1         | 0.34%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch           | 1         | 0.34%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch            | 1         | 0.34%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR        | 1         | 0.34%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                    | 1         | 0.34%   |
| Sony TV SNYEB01 1360x768                                             | 1         | 0.34%   |
| Sony TV SNYEA01 1920x1080                                            | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 103       | 37.32%  |
| 1920x1080 (FHD)    | 59        | 21.38%  |
| 1280x1024 (SXGA)   | 29        | 10.51%  |
| 1440x900 (WXGA+)   | 19        | 6.88%   |
| 1600x900 (HD+)     | 17        | 6.16%   |
| 1280x800 (WXGA)    | 13        | 4.71%   |
| 1360x768           | 8         | 2.9%    |
| 1680x1050 (WSXGA+) | 6         | 2.17%   |
| 3840x2160 (4K)     | 5         | 1.81%   |
| 1920x1200 (WUXGA)  | 3         | 1.09%   |
| 1280x720 (HD)      | 3         | 1.09%   |
| 1024x768 (XGA)     | 3         | 1.09%   |
| 1024x600           | 3         | 1.09%   |
| 2560x1440 (QHD)    | 2         | 0.72%   |
| Unknown            | 2         | 0.72%   |
| 3840x1080          | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 60        | 21.05%  |
| 18      | 37        | 12.98%  |
| 14      | 30        | 10.53%  |
| 17      | 27        | 9.47%   |
| 21      | 25        | 8.77%   |
| 13      | 23        | 8.07%   |
| 19      | 18        | 6.32%   |
| 10      | 10        | 3.51%   |
| Unknown | 10        | 3.51%   |
| 23      | 8         | 2.81%   |
| 20      | 8         | 2.81%   |
| 11      | 5         | 1.75%   |
| 74      | 3         | 1.05%   |
| 27      | 3         | 1.05%   |
| 22      | 3         | 1.05%   |
| 16      | 3         | 1.05%   |
| 72      | 2         | 0.7%    |
| 52      | 2         | 0.7%    |
| 32      | 2         | 0.7%    |
| 24      | 2         | 0.7%    |
| 54      | 1         | 0.35%   |
| 39      | 1         | 0.35%   |
| 31      | 1         | 0.35%   |
| 12      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 46.79%  |
| 401-500     | 82        | 29.29%  |
| 201-300     | 18        | 6.43%   |
| 351-400     | 14        | 5%      |
| 501-600     | 13        | 4.64%   |
| Unknown     | 10        | 3.57%   |
| 1501-2000   | 5         | 1.79%   |
| 1001-1500   | 3         | 1.07%   |
| 701-800     | 2         | 0.71%   |
| 801-900     | 1         | 0.36%   |
| 601-700     | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 178       | 67.68%  |
| 16/10   | 44        | 16.73%  |
| 5/4     | 27        | 10.27%  |
| Unknown | 8         | 3.04%   |
| 4/3     | 4         | 1.52%   |
| 3/2     | 2         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 60        | 21.13%  |
| 81-90          | 51        | 17.96%  |
| 141-150        | 49        | 17.25%  |
| 151-200        | 43        | 15.14%  |
| 201-250        | 27        | 9.51%   |
| 41-50          | 10        | 3.52%   |
| Unknown        | 10        | 3.52%   |
| More than 1000 | 8         | 2.82%   |
| 121-130        | 8         | 2.82%   |
| 51-60          | 5         | 1.76%   |
| 351-500        | 3         | 1.06%   |
| 301-350        | 3         | 1.06%   |
| 251-300        | 2         | 0.7%    |
| 71-80          | 1         | 0.35%   |
| 61-70          | 1         | 0.35%   |
| 131-140        | 1         | 0.35%   |
| 501-1000       | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 124       | 44.13%  |
| 101-120       | 91        | 32.38%  |
| 121-160       | 43        | 15.3%   |
| 1-50          | 10        | 3.56%   |
| Unknown       | 10        | 3.56%   |
| 161-240       | 2         | 0.71%   |
| More than 240 | 1         | 0.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 243       | 83.22%  |
| 2     | 29        | 9.93%   |
| 0     | 17        | 5.82%   |
| 3     | 3         | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 176       | 37.69%  |
| Intel                             | 87        | 18.63%  |
| Qualcomm Atheros                  | 82        | 17.56%  |
| Broadcom                          | 27        | 5.78%   |
| Ralink                            | 15        | 3.21%   |
| Nvidia                            | 15        | 3.21%   |
| Xiaomi                            | 7         | 1.5%    |
| Ralink Technology                 | 7         | 1.5%    |
| Qualcomm Atheros Communications   | 6         | 1.28%   |
| Broadcom Limited                  | 6         | 1.28%   |
| Marvell Technology Group          | 5         | 1.07%   |
| TP-Link                           | 4         | 0.86%   |
| JMicron Technology                | 4         | 0.86%   |
| VIA Technologies                  | 3         | 0.64%   |
| Samsung Electronics               | 3         | 0.64%   |
| Trendchip Technologies            | 2         | 0.43%   |
| Sundance Technology Inc / IC Plus | 2         | 0.43%   |
| Mercucys                          | 2         | 0.43%   |
| MediaTek                          | 2         | 0.43%   |
| D-Link System                     | 2         | 0.43%   |
| ZyXEL Communications              | 1         | 0.21%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.21%   |
| National Semiconductor            | 1         | 0.21%   |
| Motorola PCS                      | 1         | 0.21%   |
| Motorola BCS                      | 1         | 0.21%   |
| ICS Advent                        | 1         | 0.21%   |
| Huawei Technologies               | 1         | 0.21%   |
| Digium                            | 1         | 0.21%   |
| ASIX Electronics                  | 1         | 0.21%   |
| AMD                               | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 104       | 19.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 34        | 6.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 2.86%   |
| Nvidia MCP61 Ethernet                                                   | 14        | 2.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 9         | 1.72%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 8         | 1.53%   |
| Intel Wireless 7265                                                     | 8         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.34%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 7         | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 1.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 1.34%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.95%   |
| Intel Wireless 7260                                                     | 5         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 4         | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.76%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 4         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.76%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.76%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.76%   |
| Intel Centrino Wireless-N 105                                           | 4         | 0.76%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                   | 4         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.76%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.76%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 3         | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 3         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.57%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 59        | 25.99%  |
| Realtek Semiconductor           | 58        | 25.55%  |
| Intel                           | 54        | 23.79%  |
| Broadcom                        | 16        | 7.05%   |
| Ralink                          | 15        | 6.61%   |
| Ralink Technology               | 7         | 3.08%   |
| Qualcomm Atheros Communications | 6         | 2.64%   |
| TP-Link                         | 3         | 1.32%   |
| Mercucys                        | 2         | 0.88%   |
| MediaTek                        | 2         | 0.88%   |
| D-Link System                   | 2         | 0.88%   |
| Broadcom Limited                | 2         | 0.88%   |
| Xiaomi                          | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 15        | 6.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 11        | 4.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 3.96%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 8         | 3.52%   |
| Intel Wireless 7265                                                            | 8         | 3.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 7         | 3.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 7         | 3.08%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 2.2%    |
| Intel Wireless 7260                                                            | 5         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 1.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4         | 1.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 1.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.76%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4         | 1.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 1.76%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4         | 1.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 4         | 1.76%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 1.76%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 1.76%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 1.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 3         | 1.32%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3         | 1.32%   |
| Ralink MT7601U Wireless Adapter                                                | 3         | 1.32%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.32%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 1.32%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 1.32%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.32%   |
| Intel WiFi Link 5100                                                           | 3         | 1.32%   |
| Intel Wi-Fi 6 AX201                                                            | 3         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                                 | 3         | 1.32%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 3         | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2         | 0.88%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 2         | 0.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 148       | 51.21%  |
| Intel                             | 47        | 16.26%  |
| Qualcomm Atheros                  | 31        | 10.73%  |
| Nvidia                            | 15        | 5.19%   |
| Broadcom                          | 12        | 4.15%   |
| Xiaomi                            | 6         | 2.08%   |
| Marvell Technology Group          | 5         | 1.73%   |
| JMicron Technology                | 4         | 1.38%   |
| Broadcom Limited                  | 4         | 1.38%   |
| VIA Technologies                  | 3         | 1.04%   |
| Samsung Electronics               | 3         | 1.04%   |
| Trendchip Technologies            | 2         | 0.69%   |
| Sundance Technology Inc / IC Plus | 2         | 0.69%   |
| ZyXEL Communications              | 1         | 0.35%   |
| TP-Link                           | 1         | 0.35%   |
| National Semiconductor            | 1         | 0.35%   |
| Motorola PCS                      | 1         | 0.35%   |
| Motorola BCS                      | 1         | 0.35%   |
| ICS Advent                        | 1         | 0.35%   |
| ASIX Electronics                  | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 104       | 35.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 34        | 11.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 15        | 5.12%   |
| Nvidia MCP61 Ethernet                                                      | 14        | 4.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 9         | 3.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7         | 2.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 7         | 2.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 5         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4         | 1.37%   |
| Intel Ethernet Connection I217-LM                                          | 4         | 1.37%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4         | 1.37%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3         | 1.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3         | 1.02%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 3         | 1.02%   |
| Intel PRO/100 VE Network Connection                                        | 3         | 1.02%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 3         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2         | 0.68%   |
| Trendchip Ethernet controller                                              | 2         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2         | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.68%   |
| Intel Ethernet Connection I217-V                                           | 2         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                      | 2         | 0.68%   |
| Intel 82574L Gigabit Network Connection                                    | 2         | 0.68%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.68%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                | 2         | 0.68%   |
| ZyXEL ADSL Modem Prestige 600 series                                       | 1         | 0.34%   |
| TP-Link M7200                                                              | 1         | 0.34%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.34%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.34%   |
| Realtek PCIe GbE Family Controller                                         | 1         | 0.34%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1         | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1         | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                      | 1         | 0.34%   |
| Nvidia MCP77 Ethernet                                                      | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 267       | 54.83%  |
| WiFi     | 216       | 44.35%  |
| Modem    | 3         | 0.62%   |
| Unknown  | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 157       | 51.64%  |
| Ethernet | 147       | 48.36%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 169       | 57.68%  |
| 1     | 116       | 39.59%  |
| 3     | 4         | 1.37%   |
| 0     | 3         | 1.02%   |
| 4     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 289       | 99.31%  |
| Yes  | 2         | 0.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 35.29%  |
| Realtek Semiconductor           | 12        | 11.76%  |
| Qualcomm Atheros Communications | 12        | 11.76%  |
| IMC Networks                    | 12        | 11.76%  |
| Cambridge Silicon Radio         | 9         | 8.82%   |
| Broadcom                        | 7         | 6.86%   |
| Lite-On Technology              | 4         | 3.92%   |
| Apple                           | 4         | 3.92%   |
| ASUSTek Computer                | 3         | 2.94%   |
| Hewlett-Packard                 | 2         | 1.96%   |
| Dell                            | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 18.63%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 8.82%   |
| Realtek RTL8723B Bluetooth                                  | 7         | 6.86%   |
| Intel AX201 Bluetooth                                       | 7         | 6.86%   |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 4.9%    |
| Intel AX200 Bluetooth                                       | 4         | 3.92%   |
| IMC Networks Bluetooth                                      | 4         | 3.92%   |
| Realtek Bluetooth Radio                                     | 3         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 2.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 2.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 2.94%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.96%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.96%   |
| IMC Networks Bluetooth Module                               | 2         | 1.96%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 1.96%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 1         | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.98%   |
| Lite-On Wireless_Device                                     | 1         | 0.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.98%   |
| Lite-On Bluetooth Device                                    | 1         | 0.98%   |
| Lite-On BCM20702A0                                          | 1         | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.98%   |
| IMC Networks Wireless_Device                                | 1         | 0.98%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.98%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.98%   |
| Broadcom HP Portable Valentine                              | 1         | 0.98%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.98%   |
| Broadcom BCM2070 Bluetooth Device                           | 1         | 0.98%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.98%   |
| Broadcom BCM2035B3 Bluetooth Adapter                        | 1         | 0.98%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.98%   |
| ASUS Bluetooth Adapter                                      | 1         | 0.98%   |
| Apple Bluetooth HCI                                         | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 230       | 63.54%  |
| AMD                       | 54        | 14.92%  |
| Nvidia                    | 43        | 11.88%  |
| C-Media Electronics       | 8         | 2.21%   |
| VIA Technologies          | 4         | 1.1%    |
| Zhaoxin                   | 3         | 0.83%   |
| Logitech                  | 3         | 0.83%   |
| Creative Labs             | 3         | 0.83%   |
| Sennheiser Communications | 2         | 0.55%   |
| Microsoft                 | 2         | 0.55%   |
| JMTek                     | 2         | 0.55%   |
| Generalplus Technology    | 2         | 0.55%   |
| Unknown                   | 1         | 0.28%   |
| Realtek Semiconductor     | 1         | 0.28%   |
| Megawin Technology        | 1         | 0.28%   |
| Giga-Byte Technology      | 1         | 0.28%   |
| Cirrus Logic              | 1         | 0.28%   |
| Aureal Semiconductor      | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 45        | 10.98%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 44        | 10.73%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 7.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 3.9%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 3.66%   |
| Nvidia MCP61 High Definition Audio                                                                | 12        | 2.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 2.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.2%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 1.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.95%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.95%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 1.71%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.46%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 1.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.22%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.98%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 0.73%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 3         | 0.73%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.73%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.73%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.73%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.73%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 3         | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.73%   |
| Sennheiser Communications SC230                                                                   | 2         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 57        | 23.85%  |
| Samsung Electronics | 35        | 14.64%  |
| SK hynix            | 32        | 13.39%  |
| Ramaxel Technology  | 22        | 9.21%   |
| Kingston            | 22        | 9.21%   |
| Micron Technology   | 14        | 5.86%   |
| Crucial             | 10        | 4.18%   |
| Corsair             | 8         | 3.35%   |
| Elpida              | 6         | 2.51%   |
| Team                | 4         | 1.67%   |
| Qimonda             | 3         | 1.26%   |
| Nanya Technology    | 3         | 1.26%   |
| A-DATA Technology   | 3         | 1.26%   |
| Unknown             | 3         | 1.26%   |
| Unknown (ABCD)      | 2         | 0.84%   |
| Unknown (0x07D5)    | 2         | 0.84%   |
| Shenzhen WODPOSIT   | 2         | 0.84%   |
| Avant               | 2         | 0.84%   |
| Unknown (0x0CBA)    | 1         | 0.42%   |
| Unknown (081A)      | 1         | 0.42%   |
| PNY                 | 1         | 0.42%   |
| OCZ                 | 1         | 0.42%   |
| Memox               | 1         | 0.42%   |
| Kreton              | 1         | 0.42%   |
| Gold Key            | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |
| <Invalid>           | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM 400MT/s                     | 3         | 1.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 3         | 1.13%   |
| Unknown RAM Module 2048MB DIMM DDR2                     | 3         | 1.13%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 3         | 1.13%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s  | 3         | 1.13%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 3         | 1.13%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s | 3         | 1.13%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s | 3         | 1.13%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s | 3         | 1.13%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s | 3         | 1.13%   |
| Unknown                                                 | 3         | 1.13%   |
| Unknown RAM Module 4GB DIMM SDRAM                       | 2         | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2         | 0.75%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 2         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s             | 2         | 0.75%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 2         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s               | 2         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2                        | 2         | 0.75%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 2         | 0.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2         | 0.75%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 2         | 0.75%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 2         | 0.75%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s             | 2         | 0.75%   |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s    | 2         | 0.75%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s    | 2         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.75%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s  | 2         | 0.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 2         | 0.75%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s | 2         | 0.75%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s   | 2         | 0.75%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s             | 2         | 0.75%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s               | 2         | 0.75%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s   | 2         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 2         | 0.75%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s     | 2         | 0.75%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s   | 2         | 0.75%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s   | 2         | 0.75%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s   | 2         | 0.75%   |
| Ramaxel RAM Module 4GB SODIMM DDR3 1333MT/s             | 2         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 74        | 39.36%  |
| DDR4    | 39        | 20.74%  |
| DDR2    | 35        | 18.62%  |
| SDRAM   | 18        | 9.57%   |
| Unknown | 14        | 7.45%   |
| DDR     | 5         | 2.66%   |
| LPDDR4  | 3         | 1.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 91        | 50.28%  |
| SODIMM       | 88        | 48.62%  |
| Row Of Chips | 2         | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 75        | 34.72%  |
| 4096  | 64        | 29.63%  |
| 8192  | 41        | 18.98%  |
| 1024  | 22        | 10.19%  |
| 16384 | 9         | 4.17%   |
| 32768 | 3         | 1.39%   |
| 512   | 2         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 49        | 23.44%  |
| 1333    | 29        | 13.88%  |
| Unknown | 19        | 9.09%   |
| 3200    | 15        | 7.18%   |
| 2667    | 13        | 6.22%   |
| 667     | 13        | 6.22%   |
| 800     | 9         | 4.31%   |
| 2400    | 8         | 3.83%   |
| 1066    | 7         | 3.35%   |
| 533     | 7         | 3.35%   |
| 400     | 5         | 2.39%   |
| 2048    | 4         | 1.91%   |
| 1334    | 4         | 1.91%   |
| 2666    | 3         | 1.44%   |
| 1639    | 3         | 1.44%   |
| 1067    | 3         | 1.44%   |
| 133     | 3         | 1.44%   |
| 4199    | 2         | 0.96%   |
| 3266    | 2         | 0.96%   |
| 2133    | 2         | 0.96%   |
| 1867    | 2         | 0.96%   |
| 975     | 2         | 0.96%   |
| 3800    | 1         | 0.48%   |
| 3733    | 1         | 0.48%   |
| 3600    | 1         | 0.48%   |
| 3000    | 1         | 0.48%   |
| 1024    | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 60%     |
| Seiko Epson         | 2         | 20%     |
| Samsung Electronics | 2         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 10%     |
| Seiko Epson L210 Series                      | 1         | 10%     |
| Samsung ML-216x Series Laser Printer         | 1         | 10%     |
| Samsung ML-1865                              | 1         | 10%     |
| HP LaserJet Professional P1102w              | 1         | 10%     |
| HP LaserJet P1006                            | 1         | 10%     |
| HP LaserJet P1005                            | 1         | 10%     |
| HP LaserJet 1018                             | 1         | 10%     |
| HP DeskJet 2300 series                       | 1         | 10%     |
| HP Color LaserJet CP1215                     | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP Scanjet 200          | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 22.63%  |
| Microdia                               | 15        | 10.95%  |
| IMC Networks                           | 11        | 8.03%   |
| Realtek Semiconductor                  | 10        | 7.3%    |
| Acer                                   | 10        | 7.3%    |
| Suyin                                  | 8         | 5.84%   |
| Logitech                               | 5         | 3.65%   |
| Apple                                  | 5         | 3.65%   |
| Sunplus Innovation Technology          | 4         | 2.92%   |
| Quanta                                 | 4         | 2.92%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.92%   |
| Ricoh                                  | 3         | 2.19%   |
| Microsoft                              | 3         | 2.19%   |
| Lite-On Technology                     | 3         | 2.19%   |
| ALi                                    | 3         | 2.19%   |
| Syntek                                 | 2         | 1.46%   |
| Samsung Electronics                    | 2         | 1.46%   |
| KYE Systems (Mouse Systems)            | 2         | 1.46%   |
| Bison Electronics                      | 2         | 1.46%   |
| USB Camera                             | 1         | 0.73%   |
| Tobii Technology AB                    | 1         | 0.73%   |
| Sonix Technology                       | 1         | 0.73%   |
| SiGma Micro                            | 1         | 0.73%   |
| Luxvisions Innotech Limited            | 1         | 0.73%   |
| LG Electronics                         | 1         | 0.73%   |
| Lenovo                                 | 1         | 0.73%   |
| Importek                               | 1         | 0.73%   |
| Cubeternet                             | 1         | 0.73%   |
| Aveo Technology                        | 1         | 0.73%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 11        | 8.03%   |
| Microdia USB 2.0 Camera                                       | 5         | 3.65%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 2.92%   |
| Chicony Lenovo EasyCamera                                     | 4         | 2.92%   |
| Chicony Integrated Camera                                     | 4         | 2.92%   |
| Logitech Webcam C270                                          | 3         | 2.19%   |
| IMC Networks XHC Camera                                       | 3         | 2.19%   |
| Chicony HD Webcam                                             | 3         | 2.19%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 2.19%   |
| Apple Built-in iSight                                         | 3         | 2.19%   |
| Acer HD Webcam                                                | 3         | 2.19%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.46%   |
| Suyin HP Webcam 101                                           | 2         | 1.46%   |
| Sunplus Integrated_Webcam_HD                                  | 2         | 1.46%   |
| Samsung Galaxy A5 (MTP)                                       | 2         | 1.46%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.46%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.46%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.46%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.46%   |
| Chicony HP Wide Vision HD Camera                              | 2         | 1.46%   |
| Bison HD Webcam                                               | 2         | 1.46%   |
| ALi WebCam                                                    | 2         | 1.46%   |
| Acer USB Camera                                               | 2         | 1.46%   |
| Acer Lenovo EasyCamera                                        | 2         | 1.46%   |
| USB Camera USB Camera                                         | 1         | 0.73%   |
| Tobii AB EyeChip                                              | 1         | 0.73%   |
| Syntek USB Camera Device                                      | 1         | 0.73%   |
| Syntek Integrated Webcam                                      | 1         | 0.73%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 0.73%   |
| Suyin HP Webcam                                               | 1         | 0.73%   |
| Suyin Acer HD Crystal Eye webcam                              | 1         | 0.73%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.73%   |
| Sunplus USB Camera                                            | 1         | 0.73%   |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.73%   |
| Sonix USB2.0 HD UVC WebCam                                    | 1         | 0.73%   |
| SiGma Micro WebCam SiGma Micro                                | 1         | 0.73%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 0.73%   |
| Realtek USB2.0 camera                                         | 1         | 0.73%   |
| Realtek USB Camera                                            | 1         | 0.73%   |
| Realtek Integrated Webcam HD                                  | 1         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 50%     |
| Synaptics                  | 2         | 14.29%  |
| AuthenTec                  | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| Futronic Technology        | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 21.43%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 14.29%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics UWP WBDI                                     | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.14%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 80%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 40%     |
| Broadcom 5880                                  | 2         | 40%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 224       | 76.45%  |
| 1     | 59        | 20.14%  |
| 2     | 9         | 3.07%   |
| 4     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 31        | 38.27%  |
| Fingerprint reader       | 14        | 17.28%  |
| Communication controller | 11        | 13.58%  |
| Net/wireless             | 8         | 9.88%   |
| Sound                    | 6         | 7.41%   |
| Chipcard                 | 5         | 6.17%   |
| Camera                   | 3         | 3.7%    |
| Storage                  | 1         | 1.23%   |
| Network                  | 1         | 1.23%   |
| Multimedia controller    | 1         | 1.23%   |

