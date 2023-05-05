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

Total: 459

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [701fb0df1b](https://linux-hardware.org/?probe=701fb0df1b) | Apr 26, 2023 |
| HP            | 18E7                        | Desktop     | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [fa6f088b8d](https://linux-hardware.org/?probe=fa6f088b8d) | Apr 24, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7ba77e1842](https://linux-hardware.org/?probe=7ba77e1842) | Apr 23, 2023 |
| Dell          | Latitude E6430              | Notebook    | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [54af26ce93](https://linux-hardware.org/?probe=54af26ce93) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [98121ef614](https://linux-hardware.org/?probe=98121ef614) | Apr 14, 2023 |
| HP            | 1998                        | Desktop     | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| Lenovo        | 3000 V200 07642XU           | Notebook    | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| Biostar       | H61MHV                      | Desktop     | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [fdb331baab](https://linux-hardware.org/?probe=fdb331baab) | Apr 10, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| VIT           | P2402                       | Notebook    | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| Biostar       | G41D3                       | Desktop     | [969695eafd](https://linux-hardware.org/?probe=969695eafd) | Apr 06, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [df6a8a3453](https://linux-hardware.org/?probe=df6a8a3453) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| ASRock        | A55M-HVS                    | Desktop     | [426d150c30](https://linux-hardware.org/?probe=426d150c30) | Apr 03, 2023 |
| Notebook      | W54BL                       | Notebook    | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Debian 11          | 31        | 9.23%   |
| Ubuntu 20.04       | 24        | 7.14%   |
| OpenMandriva 4.3   | 18        | 5.36%   |
| Ubuntu 18.04       | 16        | 4.76%   |
| Ubuntu 22.04       | 15        | 4.46%   |
| OpenMandriva 23.03 | 11        | 3.27%   |
| Zorin 16           | 10        | 2.98%   |
| OpenMandriva 4.2   | 10        | 2.98%   |
| Debian 10          | 10        | 2.98%   |
| KDE neon 20.04     | 9         | 2.68%   |
| Linux Mint 20.3    | 8         | 2.38%   |
| Xubuntu 18.04      | 7         | 2.08%   |
| OpenMandriva 23.01 | 7         | 2.08%   |
| Linux Mint 21.1    | 6         | 1.79%   |
| Kubuntu 20.04      | 6         | 1.79%   |
| ROSA R9            | 5         | 1.49%   |
| ROSA R11           | 5         | 1.49%   |
| Linux Mint 20      | 5         | 1.49%   |
| Linux Mint 19.3    | 5         | 1.49%   |
| Zorin 15           | 4         | 1.19%   |
| Ubuntu MATE 19.10  | 4         | 1.19%   |
| Ubuntu 19.10       | 4         | 1.19%   |
| Fedora 35          | 4         | 1.19%   |
| Xubuntu 22.04      | 3         | 0.89%   |
| Ubuntu 21.10       | 3         | 0.89%   |
| OpenMandriva 4.50  | 3         | 0.89%   |
| Manjaro            | 3         | 0.89%   |
| KDE neon 22.04     | 3         | 0.89%   |
| KDE neon 18.04     | 3         | 0.89%   |
| Fedora 36          | 3         | 0.89%   |
| ArcoLinux Rolling  | 3         | 0.89%   |
| Arch Rolling       | 3         | 0.89%   |
| Xubuntu 20.04      | 2         | 0.6%    |
| Xubuntu 16.04      | 2         | 0.6%    |
| Ubuntu Unity 16.04 | 2         | 0.6%    |
| Ubuntu 20.10       | 2         | 0.6%    |
| Pop!_OS 22.04      | 2         | 0.6%    |
| Pop!_OS 21.04      | 2         | 0.6%    |
| MX 21              | 2         | 0.6%    |
| LMDE 5             | 2         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 64        | 19.88%  |
| OpenMandriva | 47        | 14.6%   |
| Debian       | 44        | 13.66%  |
| Linux Mint   | 29        | 9.01%   |
| ROSA         | 15        | 4.66%   |
| Zorin        | 14        | 4.35%   |
| Xubuntu      | 14        | 4.35%   |
| KDE neon     | 14        | 4.35%   |
| Fedora       | 12        | 3.73%   |
| Kubuntu      | 9         | 2.8%    |
| Manjaro      | 8         | 2.48%   |
| Ubuntu MATE  | 5         | 1.55%   |
| Pop!_OS      | 5         | 1.55%   |
| Arch         | 5         | 1.55%   |
| Elementary   | 4         | 1.24%   |
| Ubuntu Unity | 3         | 0.93%   |
| MX           | 3         | 0.93%   |
| LMDE         | 3         | 0.93%   |
| ArcoLinux    | 3         | 0.93%   |
| Solus        | 2         | 0.62%   |
| Nobara       | 2         | 0.62%   |
| Kali         | 2         | 0.62%   |
| Garuda Linux | 2         | 0.62%   |
| Feren OS     | 2         | 0.62%   |
| Sparky       | 1         | 0.31%   |
| Q4OS         | 1         | 0.31%   |
| PCLinuxOS    | 1         | 0.31%   |
| openSUSE     | 1         | 0.31%   |
| Lubuntu      | 1         | 0.31%   |
| Linux Lite   | 1         | 0.31%   |
| Endless      | 1         | 0.31%   |
| Deepin       | 1         | 0.31%   |
| BunsenLabs   | 1         | 0.31%   |
| Alpine       | 1         | 0.31%   |
| AlmaLinux    | 1         | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 18        | 4.95%   |
| 6.2.6-desktop-1omv2390          | 11        | 3.02%   |
| 5.10.14-desktop-1omv4002        | 10        | 2.75%   |
| 5.4.0-42-generic                | 8         | 2.2%    |
| 6.1.1-desktop-1omv2290          | 7         | 1.92%   |
| 5.3.0-40-generic                | 6         | 1.65%   |
| 5.15.0-56-generic               | 6         | 1.65%   |
| 5.15.0-46-generic               | 6         | 1.65%   |
| 5.4.0-77-generic                | 4         | 1.1%    |
| 5.15.0-67-generic               | 4         | 1.1%    |
| 5.13.0-39-generic               | 4         | 1.1%    |
| 5.10.0-16-amd64                 | 4         | 1.1%    |
| 5.10.0-13-amd64                 | 4         | 1.1%    |
| 5.10.0-11-amd64                 | 4         | 1.1%    |
| 5.0.0-37-generic                | 4         | 1.1%    |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 1.1%    |
| 4.19.0-17-amd64                 | 4         | 1.1%    |
| 5.4.0-74-generic                | 3         | 0.82%   |
| 5.4.0-73-generic                | 3         | 0.82%   |
| 5.4.0-52-generic                | 3         | 0.82%   |
| 5.3.0-29-generic                | 3         | 0.82%   |
| 5.15.0-58-generic               | 3         | 0.82%   |
| 5.15.0-52-generic               | 3         | 0.82%   |
| 5.11.0-37-generic               | 3         | 0.82%   |
| 5.10.0-21-amd64                 | 3         | 0.82%   |
| 4.15.0-48-generic               | 3         | 0.82%   |
| 5.8.0-63-generic                | 2         | 0.55%   |
| 5.8.0-55-generic                | 2         | 0.55%   |
| 5.8.0-44-generic                | 2         | 0.55%   |
| 5.4.0-89-generic                | 2         | 0.55%   |
| 5.4.0-66-generic                | 2         | 0.55%   |
| 5.4.0-54-generic                | 2         | 0.55%   |
| 5.4.0-48-generic                | 2         | 0.55%   |
| 5.4.0-31-generic                | 2         | 0.55%   |
| 5.4.0-26-generic                | 2         | 0.55%   |
| 5.4.0-107-generic               | 2         | 0.55%   |
| 5.3.0-42-generic                | 2         | 0.55%   |
| 5.19.0-40-generic               | 2         | 0.55%   |
| 5.19.0-35-generic               | 2         | 0.55%   |
| 5.19.0-2-amd64                  | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 48        | 14.16%  |
| 5.15.0  | 38        | 11.21%  |
| 5.10.0  | 32        | 9.44%   |
| 4.15.0  | 24        | 7.08%   |
| 5.13.0  | 19        | 5.6%    |
| 5.16.7  | 18        | 5.31%   |
| 5.3.0   | 12        | 3.54%   |
| 4.19.0  | 12        | 3.54%   |
| 6.2.6   | 11        | 3.24%   |
| 5.8.0   | 10        | 2.95%   |
| 5.10.14 | 10        | 2.95%   |
| 5.11.0  | 9         | 2.65%   |
| 5.19.0  | 8         | 2.36%   |
| 6.1.1   | 7         | 2.06%   |
| 5.0.0   | 7         | 2.06%   |
| 4.9.20  | 5         | 1.47%   |
| 5.14.10 | 3         | 0.88%   |
| 6.2.12  | 2         | 0.59%   |
| 5.15.6  | 2         | 0.59%   |
| 5.15.2  | 2         | 0.59%   |
| 5.12.4  | 2         | 0.59%   |
| 4.9.0   | 2         | 0.59%   |
| 4.18.0  | 2         | 0.59%   |
| 6.2.0   | 1         | 0.29%   |
| 6.1.8   | 1         | 0.29%   |
| 6.1.20  | 1         | 0.29%   |
| 6.1.14  | 1         | 0.29%   |
| 6.1.10  | 1         | 0.29%   |
| 6.1.0   | 1         | 0.29%   |
| 6.0.8   | 1         | 0.29%   |
| 6.0.5   | 1         | 0.29%   |
| 6.0.2   | 1         | 0.29%   |
| 6.0.0   | 1         | 0.29%   |
| 5.9.16  | 1         | 0.29%   |
| 5.9.0   | 1         | 0.29%   |
| 5.8.6   | 1         | 0.29%   |
| 5.8.11  | 1         | 0.29%   |
| 5.8.10  | 1         | 0.29%   |
| 5.7.0   | 1         | 0.29%   |
| 5.6.6   | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 50        | 14.93%  |
| 5.15    | 48        | 14.33%  |
| 5.10    | 48        | 14.33%  |
| 4.15    | 24        | 7.16%   |
| 5.13    | 22        | 6.57%   |
| 5.16    | 20        | 5.97%   |
| 6.2     | 14        | 4.18%   |
| 5.8     | 13        | 3.88%   |
| 5.3     | 12        | 3.58%   |
| 4.19    | 12        | 3.58%   |
| 6.1     | 11        | 3.28%   |
| 5.19    | 10        | 2.99%   |
| 5.11    | 9         | 2.69%   |
| 5.0     | 7         | 2.09%   |
| 4.9     | 7         | 2.09%   |
| 6.0     | 4         | 1.19%   |
| 5.17    | 4         | 1.19%   |
| 5.6     | 3         | 0.9%    |
| 5.14    | 3         | 0.9%    |
| 5.12    | 3         | 0.9%    |
| 5.9     | 2         | 0.6%    |
| 5.18    | 2         | 0.6%    |
| 4.18    | 2         | 0.6%    |
| 5.7     | 1         | 0.3%    |
| 5.5     | 1         | 0.3%    |
| 4.4     | 1         | 0.3%    |
| 4.13    | 1         | 0.3%    |
| 4.1     | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 282       | 91.26%  |
| i686   | 27        | 8.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 100       | 30.4%   |
| KDE5            | 81        | 24.62%  |
| XFCE            | 41        | 12.46%  |
| Unknown         | 26        | 7.9%    |
| X-Cinnamon      | 21        | 6.38%   |
| MATE            | 13        | 3.95%   |
| KDE             | 12        | 3.65%   |
| KDE4            | 7         | 2.13%   |
| LXQt            | 5         | 1.52%   |
| Cinnamon        | 5         | 1.52%   |
| LXDE            | 4         | 1.22%   |
| Unity           | 3         | 0.91%   |
| Pantheon        | 3         | 0.91%   |
| GNOME Classic   | 2         | 0.61%   |
| Budgie          | 2         | 0.61%   |
| xmonad          | 1         | 0.3%    |
| GNOME Flashback | 1         | 0.3%    |
| Deepin          | 1         | 0.3%    |
| awesome         | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 267       | 85.03%  |
| Wayland | 40        | 12.74%  |
| Unknown | 5         | 1.59%   |
| Tty     | 2         | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 38.44%  |
| SDDM    | 73        | 22.81%  |
| LightDM | 42        | 13.13%  |
| GDM     | 40        | 12.5%   |
| GDM3    | 23        | 7.19%   |
| TDM     | 10        | 3.13%   |
| KDM     | 7         | 2.19%   |
| SLiM    | 2         | 0.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 185       | 58.54%  |
| en_US   | 76        | 24.05%  |
| Unknown | 25        | 7.91%   |
| es_ES   | 18        | 5.7%    |
| es_US   | 4         | 1.27%   |
| es_MX   | 3         | 0.95%   |
| C       | 2         | 0.63%   |
| es_CO   | 1         | 0.32%   |
| en_CA   | 1         | 0.32%   |
| de_DE   | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 228       | 73.08%  |
| EFI  | 84        | 26.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 239       | 75.87%  |
| Overlay | 42        | 13.33%  |
| Btrfs   | 19        | 6.03%   |
| Unknown | 8         | 2.54%   |
| Xfs     | 5         | 1.59%   |
| Ext2    | 2         | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 140       | 44.73%  |
| MBR     | 91        | 29.07%  |
| GPT     | 82        | 26.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 80.89%  |
| Yes       | 60        | 19.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 190       | 61.09%  |
| Yes       | 121       | 38.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 37        | 12.05%  |
| Dell                           | 33        | 10.75%  |
| Hewlett-Packard                | 32        | 10.42%  |
| ASRock                         | 27        | 8.79%   |
| Intel                          | 25        | 8.14%   |
| VIT                            | 23        | 7.49%   |
| ASUSTek Computer               | 19        | 6.19%   |
| ECS                            | 15        | 4.89%   |
| Pegatron                       | 14        | 4.56%   |
| Gigabyte Technology            | 12        | 3.91%   |
| Biostar                        | 10        | 3.26%   |
| Acer                           | 9         | 2.93%   |
| MSI                            | 6         | 1.95%   |
| Unknown                        | 6         | 1.95%   |
| Foxconn                        | 5         | 1.63%   |
| langchao                       | 4         | 1.3%    |
| Apple                          | 4         | 1.3%    |
| Shanghai Zhaoxin Semiconductor | 3         | 0.98%   |
| Google                         | 3         | 0.98%   |
| Toshiba                        | 2         | 0.65%   |
| Samsung Electronics            | 2         | 0.65%   |
| Notebook                       | 2         | 0.65%   |
| UNIQCELL                       | 1         | 0.33%   |
| Standard                       | 1         | 0.33%   |
| Sony                           | 1         | 0.33%   |
| Soncview                       | 1         | 0.33%   |
| SIRAGON                        | 1         | 0.33%   |
| IP3 Tech                       | 1         | 0.33%   |
| Inspur                         | 1         | 0.33%   |
| IBM                            | 1         | 0.33%   |
| GPU Company                    | 1         | 0.33%   |
| Gateway                        | 1         | 0.33%   |
| Exo                            | 1         | 0.33%   |
| Clevo                          | 1         | 0.33%   |
| AVITA                          | 1         | 0.33%   |
| Alienware                      | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Intel powered classmate PC                | 11        | 3.58%   |
| ECS H61H2-CM                              | 8         | 2.61%   |
| ASRock G41M-VS3                           | 6         | 1.95%   |
| Unknown                                   | 6         | 1.95%   |
| VIT P2400                                 | 5         | 1.63%   |
| VIT P2402                                 | 4         | 1.3%    |
| langchao 12345                            | 4         | 1.3%    |
| VIT P3400                                 | 3         | 0.98%   |
| VIT M2420                                 | 3         | 0.98%   |
| Shanghai Zhaoxin ZXE CRB                  | 3         | 0.98%   |
| Pegatron Compaq dx2400 Microtower         | 3         | 0.98%   |
| HP Compaq 8200 Elite SFF PC               | 3         | 0.98%   |
| ASRock N68C-S UCC                         | 3         | 0.98%   |
| ASRock N68-VS3 UCC                        | 3         | 0.98%   |
| VIT P1400                                 | 2         | 0.65%   |
| VIT M2421                                 | 2         | 0.65%   |
| VIT Aptio CRB                             | 2         | 0.65%   |
| Lenovo IdeaPad S100c 20194                | 2         | 0.65%   |
| Lenovo 3000 N200 0769ARS                  | 2         | 0.65%   |
| Intel H61                                 | 2         | 0.65%   |
| HP Compaq Presario C700                   | 2         | 0.65%   |
| Google Candy                              | 2         | 0.65%   |
| ECS G31T-M7                               | 2         | 0.65%   |
| Dell OptiPlex 9020                        | 2         | 0.65%   |
| Dell Inspiron 1545                        | 2         | 0.65%   |
| Biostar G41D3                             | 2         | 0.65%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM | 2         | 0.65%   |
| Apple iMac11,2                            | 2         | 0.65%   |
| Acer Aspire 4739Z                         | 2         | 0.65%   |
| VIT NP3020M3                              | 1         | 0.33%   |
| VIT M2400-01                              | 1         | 0.33%   |
| UNIQCELL Q15.6                            | 1         | 0.33%   |
| Toshiba Satellite E55t-A                  | 1         | 0.33%   |
| Toshiba ENCORE 2 WT8-B                    | 1         | 0.33%   |
| Standard AIO                              | 1         | 0.33%   |
| Sony VGN-FW510F                           | 1         | 0.33%   |
| Soncview G41D3C                           | 1         | 0.33%   |
| SIRAGON AIO-5150                          | 1         | 0.33%   |
| Samsung 905S3G/906S3G/915S3G              | 1         | 0.33%   |
| Samsung 355V4C/356V4C/3445VC/3545VC       | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 12        | 3.91%   |
| Intel powered        | 11        | 3.58%   |
| HP Compaq            | 11        | 3.58%   |
| Lenovo IdeaPad       | 10        | 3.26%   |
| ECS H61H2-CM         | 8         | 2.61%   |
| Acer Aspire          | 8         | 2.61%   |
| Lenovo ThinkCentre   | 7         | 2.28%   |
| HP Pavilion          | 7         | 2.28%   |
| Lenovo ThinkPad      | 6         | 1.95%   |
| Dell Vostro          | 6         | 1.95%   |
| Dell OptiPlex        | 6         | 1.95%   |
| Dell Latitude        | 6         | 1.95%   |
| ASRock G41M-VS3      | 6         | 1.95%   |
| Unknown              | 6         | 1.95%   |
| VIT P2400            | 5         | 1.63%   |
| VIT P2402            | 4         | 1.3%    |
| Pegatron Compaq      | 4         | 1.3%    |
| Lenovo 3000          | 4         | 1.3%    |
| langchao 12345       | 4         | 1.3%    |
| VIT P3400            | 3         | 0.98%   |
| VIT M2420            | 3         | 0.98%   |
| Shanghai Zhaoxin ZXE | 3         | 0.98%   |
| ASUS ASUS            | 3         | 0.98%   |
| ASRock N68C-S        | 3         | 0.98%   |
| ASRock N68-VS3       | 3         | 0.98%   |
| VIT P1400            | 2         | 0.65%   |
| VIT M2421            | 2         | 0.65%   |
| VIT Aptio            | 2         | 0.65%   |
| Lenovo Legion        | 2         | 0.65%   |
| Intel H61            | 2         | 0.65%   |
| HP Presario          | 2         | 0.65%   |
| HP Laptop            | 2         | 0.65%   |
| HP ENVY              | 2         | 0.65%   |
| HP EliteDesk         | 2         | 0.65%   |
| HP EliteBook         | 2         | 0.65%   |
| Google Candy         | 2         | 0.65%   |
| ECS G31T-M7          | 2         | 0.65%   |
| Dell Precision       | 2         | 0.65%   |
| Biostar G41D3        | 2         | 0.65%   |
| ASUS VivoBook        | 2         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 55        | 17.92%  |
| 2010    | 43        | 14.01%  |
| 2012    | 32        | 10.42%  |
| 2013    | 25        | 8.14%   |
| 2008    | 23        | 7.49%   |
| 2007    | 22        | 7.17%   |
| 2014    | 16        | 5.21%   |
| 2020    | 13        | 4.23%   |
| 2022    | 10        | 3.26%   |
| 2021    | 10        | 3.26%   |
| 2019    | 9         | 2.93%   |
| 2009    | 9         | 2.93%   |
| 2018    | 8         | 2.61%   |
| 2017    | 8         | 2.61%   |
| 2015    | 8         | 2.61%   |
| 2006    | 8         | 2.61%   |
| 2016    | 4         | 1.3%    |
| Unknown | 2         | 0.65%   |
| 2023    | 1         | 0.33%   |
| 2005    | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 149       | 48.53%  |
| Notebook    | 140       | 45.6%   |
| All in one  | 6         | 1.95%   |
| Tablet      | 4         | 1.3%    |
| Mini pc     | 3         | 0.98%   |
| Server      | 3         | 0.98%   |
| Convertible | 2         | 0.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 303       | 98.7%   |
| Enabled  | 4         | 1.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 304       | 99.02%  |
| Yes  | 3         | 0.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 89        | 28.43%  |
| 4.01-8.0    | 69        | 22.04%  |
| 1.01-2.0    | 53        | 16.93%  |
| 8.01-16.0   | 45        | 14.38%  |
| 16.01-24.0  | 29        | 9.27%   |
| 2.01-3.0    | 11        | 3.51%   |
| 32.01-64.0  | 8         | 2.56%   |
| 24.01-32.0  | 4         | 1.28%   |
| 0.51-1.0    | 3         | 0.96%   |
| 64.01-256.0 | 2         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 135       | 39.71%  |
| 2.01-3.0   | 83        | 24.41%  |
| 0.51-1.0   | 47        | 13.82%  |
| 4.01-8.0   | 38        | 11.18%  |
| 3.01-4.0   | 27        | 7.94%   |
| 8.01-16.0  | 5         | 1.47%   |
| 0.01-0.5   | 4         | 1.18%   |
| 16.01-24.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 194       | 61.59%  |
| 2      | 98        | 31.11%  |
| 3      | 18        | 5.71%   |
| 4      | 3         | 0.95%   |
| 6      | 1         | 0.32%   |
| 0      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 169       | 54.34%  |
| Yes       | 142       | 45.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 282       | 91.26%  |
| No        | 27        | 8.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 229       | 73.63%  |
| No        | 82        | 26.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 198       | 63.87%  |
| Yes       | 112       | 36.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 307       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 144       | 43.37%  |
| Maracaibo                  | 23        | 6.93%   |
| Barquisimeto               | 18        | 5.42%   |
| Maracay                    | 16        | 4.82%   |
| Valencia                   | 14        | 4.22%   |
| Mérida                    | 11        | 3.31%   |
| San Cristóbal             | 9         | 2.71%   |
| Maturín                   | 9         | 2.71%   |
| Barcelona                  | 7         | 2.11%   |
| San Carlos del Zulia       | 6         | 1.81%   |
| Ciudad Guayana             | 4         | 1.2%    |
| Barinas                    | 4         | 1.2%    |
| San Antonio de Los Altos   | 3         | 0.9%    |
| Porlamar                   | 3         | 0.9%    |
| Parroquia El Recreo        | 3         | 0.9%    |
| Los Teques                 | 3         | 0.9%    |
| Lecherias                  | 3         | 0.9%    |
| Ciudad Bolívar            | 3         | 0.9%    |
| Carrizal                   | 3         | 0.9%    |
| Acarigua                   | 3         | 0.9%    |
| San Juan Bautista          | 2         | 0.6%    |
| Los Palos Grandes          | 2         | 0.6%    |
| Las Vegas                  | 2         | 0.6%    |
| Guatire                    | 2         | 0.6%    |
| Guarenas                   | 2         | 0.6%    |
| Cua                        | 2         | 0.6%    |
| Cabudare                   | 2         | 0.6%    |
| Anaco                      | 2         | 0.6%    |
| Valle de La Pascua         | 1         | 0.3%    |
| Tucupita                   | 1         | 0.3%    |
| Tucape                     | 1         | 0.3%    |
| Santa Rita                 | 1         | 0.3%    |
| San Francisco              | 1         | 0.3%    |
| San Felipe                 | 1         | 0.3%    |
| San Diego                  | 1         | 0.3%    |
| Punto Fijo                 | 1         | 0.3%    |
| Puerto Ordaz and San Felix | 1         | 0.3%    |
| Puerto Cumarebo            | 1         | 0.3%    |
| Puerto Cruz                | 1         | 0.3%    |
| Naguanagua                 | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 96        | 133    | 24%     |
| Seagate             | 91        | 135    | 22.75%  |
| Hitachi             | 38        | 52     | 9.5%    |
| Samsung Electronics | 31        | 35     | 7.75%   |
| Toshiba             | 30        | 32     | 7.5%    |
| Kingston            | 15        | 19     | 3.75%   |
| Unknown             | 12        | 16     | 3%      |
| SanDisk             | 8         | 12     | 2%      |
| SK hynix            | 7         | 8      | 1.75%   |
| Intel               | 7         | 10     | 1.75%   |
| PNY                 | 6         | 7      | 1.5%    |
| Maxtor              | 6         | 6      | 1.5%    |
| HGST                | 6         | 6      | 1.5%    |
| Crucial             | 6         | 8      | 1.5%    |
| SPCC                | 4         | 6      | 1%      |
| LITEONIT            | 4         | 8      | 1%      |
| Fujitsu             | 4         | 4      | 1%      |
| Team                | 3         | 3      | 0.75%   |
| addlink             | 3         | 3      | 0.75%   |
| Silicon Motion      | 2         | 2      | 0.5%    |
| Patriot             | 2         | 2      | 0.5%    |
| Micron Technology   | 2         | 5      | 0.5%    |
| HUAWEI              | 2         | 2      | 0.5%    |
| BIWIN               | 2         | 3      | 0.5%    |
| Vaseky              | 1         | 1      | 0.25%   |
| PUSKILL             | 1         | 1      | 0.25%   |
| Phison Electronics  | 1         | 1      | 0.25%   |
| Phison              | 1         | 1      | 0.25%   |
| Netac               | 1         | 1      | 0.25%   |
| Lexar               | 1         | 1      | 0.25%   |
| KingFast            | 1         | 3      | 0.25%   |
| JMicron Technology  | 1         | 1      | 0.25%   |
| Intenso             | 1         | 1      | 0.25%   |
| ExcelStor           | 1         | 1      | 0.25%   |
| Dogfish             | 1         | 1      | 0.25%   |
| Dell                | 1         | 2      | 0.25%   |
| Apacer              | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 16        | 3.67%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 8         | 1.83%   |
| Toshiba DT01ACA050 500GB            | 8         | 1.83%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 1.38%   |
| Seagate ST320LM000 HM321HI 320GB    | 5         | 1.15%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 4         | 0.92%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 0.92%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 0.92%   |
| Seagate ST500DM002-1BD142 500GB     | 4         | 0.92%   |
| Seagate ST3320418AS 320GB           | 4         | 0.92%   |
| Seagate ST320LT012-9WS14C 320GB     | 4         | 0.92%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 0.92%   |
| Samsung HD502HJ 500GB               | 4         | 0.92%   |
| WDC WD5000AAKX-221CA1 500GB         | 3         | 0.69%   |
| WDC WD5000AAKX-001CA0 500GB         | 3         | 0.69%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 0.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 0.69%   |
| WDC WD3200AAJS-08L7A0 320GB         | 3         | 0.69%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.69%   |
| Unknown NVMe SSD Drive 512GB        | 3         | 0.69%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.69%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 0.69%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 0.69%   |
| Samsung HD161HJ 160GB               | 3         | 0.69%   |
| Samsung HD161GJ 160GB               | 3         | 0.69%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 0.69%   |
| Hitachi HTS542580K9SA00 80GB        | 3         | 0.69%   |
| Hitachi HDS728080PLA380 82GB        | 3         | 0.69%   |
| WDC WD800BD-22MRA1 80GB             | 2         | 0.46%   |
| WDC WD800BB-22JHC0 80GB             | 2         | 0.46%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.46%   |
| WDC WD5000AAKX-753CA1 500GB         | 2         | 0.46%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 2         | 0.46%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2         | 0.46%   |
| WDC WD1200BEVS-60UST0 120GB         | 2         | 0.46%   |
| Unknown MMC Card  16GB              | 2         | 0.46%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.46%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.46%   |
| Toshiba MQ01ABF032 320GB            | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 93        | 127    | 32.29%  |
| Seagate             | 88        | 132    | 30.56%  |
| Hitachi             | 38        | 52     | 13.19%  |
| Toshiba             | 29        | 31     | 10.07%  |
| Samsung Electronics | 20        | 23     | 6.94%   |
| Maxtor              | 6         | 6      | 2.08%   |
| HGST                | 6         | 6      | 2.08%   |
| Fujitsu             | 4         | 4      | 1.39%   |
| Unknown             | 2         | 2      | 0.69%   |
| JMicron Technology  | 1         | 1      | 0.35%   |
| ExcelStor           | 1         | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 13        | 17     | 20.97%  |
| Samsung Electronics | 7         | 8      | 11.29%  |
| PNY                 | 6         | 7      | 9.68%   |
| Crucial             | 6         | 8      | 9.68%   |
| LITEONIT            | 4         | 8      | 6.45%   |
| SPCC                | 3         | 4      | 4.84%   |
| SanDisk             | 3         | 4      | 4.84%   |
| Team                | 2         | 2      | 3.23%   |
| SK hynix            | 2         | 2      | 3.23%   |
| Patriot             | 2         | 2      | 3.23%   |
| addlink             | 2         | 2      | 3.23%   |
| Vaseky              | 1         | 1      | 1.61%   |
| Toshiba             | 1         | 1      | 1.61%   |
| PUSKILL             | 1         | 1      | 1.61%   |
| Netac               | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 3      | 1.61%   |
| Lexar               | 1         | 1      | 1.61%   |
| KingFast            | 1         | 3      | 1.61%   |
| Intenso             | 1         | 1      | 1.61%   |
| Intel               | 1         | 1      | 1.61%   |
| Dogfish             | 1         | 1      | 1.61%   |
| Dell                | 1         | 2      | 1.61%   |
| BIWIN               | 1         | 2      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 236       | 385    | 68.6%   |
| SSD     | 60        | 82     | 17.44%  |
| NVMe    | 36        | 51     | 10.47%  |
| MMC     | 7         | 10     | 2.03%   |
| Unknown | 5         | 5      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 273       | 463    | 84%     |
| NVMe | 36        | 51     | 11.08%  |
| SAS  | 9         | 9      | 2.77%   |
| MMC  | 7         | 10     | 2.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 245       | 374    | 79.03%  |
| 0.51-1.0   | 49        | 68     | 15.81%  |
| 1.01-2.0   | 12        | 20     | 3.87%   |
| 3.01-4.0   | 2         | 2      | 0.65%   |
| 2.01-3.0   | 2         | 3      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 104       | 31.61%  |
| 101-250        | 74        | 22.49%  |
| 501-1000       | 45        | 13.68%  |
| 1-20           | 38        | 11.55%  |
| 51-100         | 28        | 8.51%   |
| 21-50          | 15        | 4.56%   |
| 1001-2000      | 11        | 3.34%   |
| 2001-3000      | 5         | 1.52%   |
| Unknown        | 5         | 1.52%   |
| More than 3000 | 4         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 135       | 39.94%  |
| 21-50          | 61        | 18.05%  |
| 101-250        | 50        | 14.79%  |
| 51-100         | 35        | 10.36%  |
| 251-500        | 30        | 8.88%   |
| 501-1000       | 12        | 3.55%   |
| Unknown        | 5         | 1.48%   |
| 2001-3000      | 4         | 1.18%   |
| 1001-2000      | 4         | 1.18%   |
| More than 3000 | 2         | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 6         | 7      | 6.25%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 4         | 5      | 4.17%   |
| Toshiba DT01ACA050 500GB          | 3         | 4      | 3.13%   |
| WDC WD5000AAKX-221CA1 500GB       | 2         | 2      | 2.08%   |
| WDC WD5000AAKS-00A7B0 500GB       | 2         | 2      | 2.08%   |
| WDC WD1200BEVS-60UST0 120GB       | 2         | 2      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 2.08%   |
| Samsung Electronics HM321HI 320GB | 2         | 2      | 2.08%   |
| Samsung Electronics HD161GJ 160GB | 2         | 2      | 2.08%   |
| Maxtor STM3160215AS 160GB         | 2         | 2      | 2.08%   |
| Hitachi HTS725050A9A364 500GB     | 2         | 2      | 2.08%   |
| Hitachi HDS728080PLA380 82GB      | 2         | 2      | 2.08%   |
| Hitachi HDS721616PLA380 160GB     | 2         | 2      | 2.08%   |
| HGST HTS545050A7E380 500GB        | 2         | 2      | 2.08%   |
| WDC WD800BD-08MRA1 80GB           | 1         | 1      | 1.04%   |
| WDC WD800BB-22JHC0 80GB           | 1         | 1      | 1.04%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 1.04%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1         | 1      | 1.04%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 1      | 1.04%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 2      | 1.04%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1         | 1      | 1.04%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1         | 1      | 1.04%   |
| WDC WD50 00BPVT-24HXZT1 500GB     | 1         | 1      | 1.04%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 1.04%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1         | 1      | 1.04%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 1      | 1.04%   |
| WDC WD3200AAJS-08L7A0 320GB       | 1         | 2      | 1.04%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1         | 1      | 1.04%   |
| WDC WD10JPVX-22JC3T0 1TB          | 1         | 2      | 1.04%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1         | 1      | 1.04%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1         | 1      | 1.04%   |
| Toshiba MQ01ACF050 500GB          | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 1.04%   |
| Toshiba MK3275GSX 320GB           | 1         | 1      | 1.04%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 1.04%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 1.04%   |
| Seagate ST9160314AS 160GB         | 1         | 1      | 1.04%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 1.04%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 1.04%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1         | 1      | 1.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 30     | 30.34%  |
| WDC                 | 21        | 31     | 23.6%   |
| Hitachi             | 17        | 17     | 19.1%   |
| Samsung Electronics | 8         | 9      | 8.99%   |
| Toshiba             | 6         | 7      | 6.74%   |
| Maxtor              | 3         | 3      | 3.37%   |
| HGST                | 3         | 3      | 3.37%   |
| Intel               | 2         | 2      | 2.25%   |
| JMicron Technology  | 1         | 1      | 1.12%   |
| ExcelStor           | 1         | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 30     | 31.03%  |
| WDC                 | 21        | 31     | 24.14%  |
| Hitachi             | 17        | 17     | 19.54%  |
| Samsung Electronics | 8         | 9      | 9.2%    |
| Toshiba             | 6         | 7      | 6.9%    |
| Maxtor              | 3         | 3      | 3.45%   |
| HGST                | 3         | 3      | 3.45%   |
| JMicron Technology  | 1         | 1      | 1.15%   |
| ExcelStor           | 1         | 1      | 1.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 73        | 102    | 97.33%  |
| NVMe | 2         | 2      | 2.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB  | 2         | 2      | 66.67%  |
| Seagate ST9320423AS 320GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 162       | 287    | 48.07%  |
| Works    | 97        | 139    | 28.78%  |
| Malfunc  | 75        | 104    | 22.26%  |
| Failed   | 3         | 3      | 0.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 242       | 71.18%  |
| AMD                         | 35        | 10.29%  |
| Nvidia                      | 15        | 4.41%   |
| SanDisk                     | 8         | 2.35%   |
| Marvell Technology Group    | 6         | 1.76%   |
| JMicron Technology          | 6         | 1.76%   |
| SK hynix                    | 5         | 1.47%   |
| Samsung Electronics         | 4         | 1.18%   |
| Phison Electronics          | 4         | 1.18%   |
| Jiangsu Huacun Elec.        | 4         | 1.18%   |
| VIA Technologies            | 3         | 0.88%   |
| Silicon Motion              | 3         | 0.88%   |
| Kingston Technology Company | 2         | 0.59%   |
| Micron Technology           | 1         | 0.29%   |
| ASMedia Technology          | 1         | 0.29%   |
| Adaptec                     | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 38        | 8.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 30        | 6.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 4.9%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 22        | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20        | 4.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17        | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 17        | 3.79%   |
| Nvidia MCP61 SATA Controller                                                            | 14        | 3.12%   |
| Nvidia MCP61 IDE                                                                        | 12        | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 9         | 2%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 1.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 1.34%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 1.34%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6         | 1.34%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 1.34%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 1.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.11%   |
| Jiangsu Huacun Elec. Non-Volatile memory controller                                     | 4         | 0.89%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 4         | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.89%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.67%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 3         | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.67%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.67%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 0.67%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3         | 0.67%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 0.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 180       | 50.85%  |
| IDE  | 117       | 33.05%  |
| NVMe | 36        | 10.17%  |
| RAID | 19        | 5.37%   |
| SAS  | 1         | 0.28%   |
| SCSI | 1         | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 250       | 81.43%  |
| AMD          | 54        | 17.59%  |
| CentaurHauls | 3         | 0.98%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 6         | 1.95%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 6         | 1.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 6         | 1.95%   |
| Intel Celeron CPU N2805 @ 1.46GHz              | 6         | 1.95%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 6         | 1.95%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz    | 4         | 1.3%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 4         | 1.3%    |
| Intel Pentium CPU G620 @ 2.60GHz               | 4         | 1.3%    |
| Intel Core i3-2120 CPU @ 3.30GHz               | 4         | 1.3%    |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 4         | 1.3%    |
| Intel Atom CPU N455 @ 1.66GHz                  | 4         | 1.3%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 3         | 0.98%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 0.98%   |
| Intel Pentium CPU G2030 @ 3.00GHz              | 3         | 0.98%   |
| Intel Pentium 4 CPU 3.00GHz                    | 3         | 0.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 3         | 0.98%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 3         | 0.98%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 3         | 0.98%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 3         | 0.98%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3         | 0.98%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 3         | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 3         | 0.98%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 0.98%   |
| AMD Sempron 145 Processor                      | 3         | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 3         | 0.98%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 0.65%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz    | 2         | 0.65%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 2         | 0.65%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz         | 2         | 0.65%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 2         | 0.65%   |
| Intel Pentium CPU N3710 @ 1.60GHz              | 2         | 0.65%   |
| Intel Pentium CPU G640 @ 2.80GHz               | 2         | 0.65%   |
| Intel Pentium CPU 2030M @ 2.50GHz              | 2         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 2         | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2         | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 2         | 0.65%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 2         | 0.65%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 0.65%   |
| Intel Core i5-3330 CPU @ 3.00GHz               | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 45        | 14.66%  |
| Intel Core i3                  | 33        | 10.75%  |
| Intel Pentium Dual-Core        | 26        | 8.47%   |
| Intel Core i7                  | 23        | 7.49%   |
| Intel Core 2 Duo               | 23        | 7.49%   |
| Intel Pentium                  | 22        | 7.17%   |
| Intel Celeron                  | 21        | 6.84%   |
| Other                          | 15        | 4.89%   |
| Intel Pentium Dual             | 11        | 3.58%   |
| Intel Atom                     | 10        | 3.26%   |
| AMD Ryzen 5                    | 9         | 2.93%   |
| Intel Xeon                     | 7         | 2.28%   |
| AMD Sempron                    | 7         | 2.28%   |
| Intel Core 2 Quad              | 5         | 1.63%   |
| AMD Ryzen 7                    | 5         | 1.63%   |
| Intel Pentium 4                | 4         | 1.3%    |
| Intel Core 2                   | 4         | 1.3%    |
| AMD FX                         | 3         | 0.98%   |
| AMD Athlon II X2               | 3         | 0.98%   |
| Intel Pentium D                | 2         | 0.65%   |
| Intel Genuine                  | 2         | 0.65%   |
| AMD Ryzen 3                    | 2         | 0.65%   |
| AMD Phenom II X4               | 2         | 0.65%   |
| AMD Phenom                     | 2         | 0.65%   |
| AMD E1                         | 2         | 0.65%   |
| AMD Athlon II X4               | 2         | 0.65%   |
| AMD Athlon                     | 2         | 0.65%   |
| AMD A6                         | 2         | 0.65%   |
| AMD A10                        | 2         | 0.65%   |
| Intel Pentium Silver           | 1         | 0.33%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.33%   |
| AMD Quad-Core                  | 1         | 0.33%   |
| AMD Phenom II X2               | 1         | 0.33%   |
| AMD Mobile Sempron             | 1         | 0.33%   |
| AMD E                          | 1         | 0.33%   |
| AMD C-70                       | 1         | 0.33%   |
| AMD Athlon II                  | 1         | 0.33%   |
| AMD Athlon 64 X2               | 1         | 0.33%   |
| AMD A8                         | 1         | 0.33%   |
| AMD A4                         | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 182       | 59.28%  |
| 4       | 79        | 25.73%  |
| 1       | 20        | 6.51%   |
| 6       | 10        | 3.26%   |
| 8       | 7         | 2.28%   |
| 3       | 4         | 1.3%    |
| Unknown | 4         | 1.3%    |
| 14      | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 307       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 180       | 58.63%  |
| 2       | 123       | 40.07%  |
| Unknown | 4         | 1.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 297       | 96.74%  |
| 64-bit         | 5         | 1.63%   |
| 32-bit         | 4         | 1.3%    |
| Unknown        | 1         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 21.7%   |
| 0x1067a    | 40        | 12.58%  |
| 0x206a7    | 37        | 11.64%  |
| 0x306a9    | 25        | 7.86%   |
| 0x6fd      | 13        | 4.09%   |
| 0x306c3    | 9         | 2.83%   |
| 0x30673    | 6         | 1.89%   |
| 0x106ca    | 6         | 1.89%   |
| 0x806e9    | 5         | 1.57%   |
| 0x806c1    | 5         | 1.57%   |
| 0x20655    | 5         | 1.57%   |
| 0x010000c8 | 5         | 1.57%   |
| 0xf65      | 4         | 1.26%   |
| 0x6fb      | 4         | 1.26%   |
| 0x30678    | 4         | 1.26%   |
| 0x6f2      | 3         | 0.94%   |
| 0x40651    | 3         | 0.94%   |
| 0x106a5    | 3         | 0.94%   |
| 0x10676    | 3         | 0.94%   |
| 0x05000119 | 3         | 0.94%   |
| 0x010000c7 | 3         | 0.94%   |
| 0xa0671    | 2         | 0.63%   |
| 0x906e9    | 2         | 0.63%   |
| 0x806ec    | 2         | 0.63%   |
| 0x806d1    | 2         | 0.63%   |
| 0x406e3    | 2         | 0.63%   |
| 0x406c4    | 2         | 0.63%   |
| 0x306d4    | 2         | 0.63%   |
| 0x08608103 | 2         | 0.63%   |
| 0x08600104 | 2         | 0.63%   |
| 0x08108102 | 2         | 0.63%   |
| 0x0810100b | 2         | 0.63%   |
| 0x0600063e | 2         | 0.63%   |
| 0x03000027 | 2         | 0.63%   |
| 0x010000b6 | 2         | 0.63%   |
| 0xf47      | 1         | 0.31%   |
| 0xf41      | 1         | 0.31%   |
| 0x906eb    | 1         | 0.31%   |
| 0x906ea    | 1         | 0.31%   |
| 0x806ea    | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 48        | 15.64%  |
| Penryn           | 45        | 14.66%  |
| IvyBridge        | 33        | 10.75%  |
| Core             | 29        | 9.45%   |
| K10              | 16        | 5.21%   |
| Haswell          | 16        | 5.21%   |
| KabyLake         | 14        | 4.56%   |
| Silvermont       | 13        | 4.23%   |
| Westmere         | 11        | 3.58%   |
| Bonnell          | 9         | 2.93%   |
| Unknown          | 9         | 2.93%   |
| NetBurst         | 6         | 1.95%   |
| Zen+             | 5         | 1.63%   |
| TigerLake        | 5         | 1.63%   |
| Zen 2            | 4         | 1.3%    |
| K8 Hammer        | 4         | 1.3%    |
| Icelake          | 4         | 1.3%    |
| Bobcat           | 4         | 1.3%    |
| Zen              | 3         | 0.98%   |
| Skylake          | 3         | 0.98%   |
| Nehalem          | 3         | 0.98%   |
| Excavator        | 3         | 0.98%   |
| Broadwell        | 3         | 0.98%   |
| Piledriver       | 2         | 0.65%   |
| K10 Llano        | 2         | 0.65%   |
| Jaguar           | 2         | 0.65%   |
| Goldmont plus    | 2         | 0.65%   |
| Bulldozer        | 2         | 0.65%   |
| Zen 3            | 1         | 0.33%   |
| Steamroller      | 1         | 0.33%   |
| P6               | 1         | 0.33%   |
| K8 & K10 hybrid  | 1         | 0.33%   |
| Goldmont         | 1         | 0.33%   |
| CometLake        | 1         | 0.33%   |
| Alderlake Hybrid | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 211       | 64.13%  |
| AMD                        | 60        | 18.24%  |
| Nvidia                     | 50        | 15.2%   |
| Zhaoxin                    | 3         | 0.91%   |
| VIA Technologies           | 3         | 0.91%   |
| Matrox Electronics Systems | 1         | 0.3%    |
| ASPEED Technology          | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 42        | 12.24%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 5.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 4.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 2.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 2.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 8         | 2.33%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.75%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.46%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 4         | 1.17%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4         | 1.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.17%   |
| Intel HD Graphics 620                                                                    | 4         | 1.17%   |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 4         | 1.17%   |
| AMD Lucienne                                                                             | 4         | 1.17%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 3         | 0.87%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.87%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3         | 0.87%   |
| Intel HD Graphics 630                                                                    | 3         | 0.87%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3         | 0.87%   |
| AMD Renoir                                                                               | 3         | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.87%   |
| Nvidia TU117M                                                                            | 2         | 0.58%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.58%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.58%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.58%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2         | 0.58%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2         | 0.58%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.58%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 192       | 62.34%  |
| 1 x AMD         | 53        | 17.21%  |
| 1 x Nvidia      | 39        | 12.66%  |
| Intel + Nvidia  | 7         | 2.27%   |
| 1 x Zhaoxin     | 3         | 0.97%   |
| 1 x VIA         | 3         | 0.97%   |
| AMD + Nvidia    | 3         | 0.97%   |
| 2 x Intel       | 2         | 0.65%   |
| 2 x AMD         | 2         | 0.65%   |
| Intel + AMD     | 2         | 0.65%   |
| Nvidia + ASPEED | 1         | 0.32%   |
| 1 x Matrox      | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 267       | 86.41%  |
| Proprietary | 23        | 7.44%   |
| Unknown     | 19        | 6.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 209       | 66.14%  |
| 0.01-0.5   | 42        | 13.29%  |
| 0.51-1.0   | 32        | 10.13%  |
| 1.01-2.0   | 23        | 7.28%   |
| 3.01-4.0   | 8         | 2.53%   |
| 5.01-6.0   | 2         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 59        | 19.47%  |
| BOE                                   | 25        | 8.25%   |
| AU Optronics                          | 23        | 7.59%   |
| LG Display                            | 20        | 6.6%    |
| Hewlett-Packard                       | 19        | 6.27%   |
| Goldstar                              | 18        | 5.94%   |
| Chimei Innolux                        | 15        | 4.95%   |
| Lenovo                                | 14        | 4.62%   |
| Dell                                  | 13        | 4.29%   |
| Toshiba                               | 10        | 3.3%    |
| InfoVision                            | 9         | 2.97%   |
| AOC                                   | 9         | 2.97%   |
| Acer                                  | 9         | 2.97%   |
| Chi Mei Optoelectronics               | 7         | 2.31%   |
| Vita                                  | 5         | 1.65%   |
| LG Philips                            | 5         | 1.65%   |
| HannStar                              | 4         | 1.32%   |
| Apple                                 | 4         | 1.32%   |
| BenQ                                  | 3         | 0.99%   |
| ViewSonic                             | 2         | 0.66%   |
| Unknown (XXX)                         | 2         | 0.66%   |
| Sony                                  | 2         | 0.66%   |
| PANDA                                 | 2         | 0.66%   |
| MStar                                 | 2         | 0.66%   |
| ITL                                   | 2         | 0.66%   |
| Envision                              | 2         | 0.66%   |
| Vizio                                 | 1         | 0.33%   |
| Toshiba Matsushita Display Technology | 1         | 0.33%   |
| TCL                                   | 1         | 0.33%   |
| Sharp                                 | 1         | 0.33%   |
| Sceptre Tech                          | 1         | 0.33%   |
| Plain Tree Systems                    | 1         | 0.33%   |
| PEGA                                  | 1         | 0.33%   |
| Parker                                | 1         | 0.33%   |
| LSC                                   | 1         | 0.33%   |
| LG Electronics                        | 1         | 0.33%   |
| LED                                   | 1         | 0.33%   |
| KTC                                   | 1         | 0.33%   |
| InnoLux Display                       | 1         | 0.33%   |
| IBM                                   | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 7         | 2.27%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 6         | 1.95%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 5         | 1.62%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 5         | 1.62%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 5         | 1.62%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4         | 1.3%    |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 4         | 1.3%    |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 3         | 0.97%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 3         | 0.97%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 0.97%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 3         | 0.97%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 3         | 0.97%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 2         | 0.65%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2         | 0.65%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.65%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.65%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                      | 2         | 0.65%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 2         | 0.65%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.65%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch          | 2         | 0.65%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                     | 2         | 0.65%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.65%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                   | 2         | 0.65%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch       | 2         | 0.65%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.65%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                      | 2         | 0.65%   |
| Vizio E3D320VX VIZ0079 1920x1080 698x393mm 31.5-inch                 | 1         | 0.32%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1         | 0.32%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch        | 1         | 0.32%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch               | 1         | 0.32%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch           | 1         | 0.32%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch            | 1         | 0.32%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR        | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 108       | 36.86%  |
| 1920x1080 (FHD)    | 64        | 21.84%  |
| 1280x1024 (SXGA)   | 31        | 10.58%  |
| 1440x900 (WXGA+)   | 19        | 6.48%   |
| 1600x900 (HD+)     | 17        | 5.8%    |
| 1280x800 (WXGA)    | 14        | 4.78%   |
| 1360x768           | 9         | 3.07%   |
| 1680x1050 (WSXGA+) | 7         | 2.39%   |
| 3840x2160 (4K)     | 5         | 1.71%   |
| 1920x1200 (WUXGA)  | 4         | 1.37%   |
| 1024x768 (XGA)     | 4         | 1.37%   |
| 1280x720 (HD)      | 3         | 1.02%   |
| 1024x600           | 3         | 1.02%   |
| 2560x1440 (QHD)    | 2         | 0.68%   |
| Unknown            | 2         | 0.68%   |
| 3840x1080          | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 20.93%  |
| 18      | 39        | 12.96%  |
| 14      | 31        | 10.3%   |
| 17      | 30        | 9.97%   |
| 21      | 26        | 8.64%   |
| 13      | 25        | 8.31%   |
| 19      | 19        | 6.31%   |
| Unknown | 11        | 3.65%   |
| 10      | 10        | 3.32%   |
| 23      | 8         | 2.66%   |
| 20      | 8         | 2.66%   |
| 11      | 5         | 1.66%   |
| 22      | 4         | 1.33%   |
| 74      | 3         | 1%      |
| 27      | 3         | 1%      |
| 16      | 3         | 1%      |
| 72      | 2         | 0.66%   |
| 52      | 2         | 0.66%   |
| 32      | 2         | 0.66%   |
| 24      | 2         | 0.66%   |
| 12      | 2         | 0.66%   |
| 54      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 31      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 137       | 46.13%  |
| 401-500     | 87        | 29.29%  |
| 201-300     | 20        | 6.73%   |
| 351-400     | 17        | 5.72%   |
| 501-600     | 13        | 4.38%   |
| Unknown     | 11        | 3.7%    |
| 1501-2000   | 5         | 1.68%   |
| 1001-1500   | 3         | 1.01%   |
| 701-800     | 2         | 0.67%   |
| 801-900     | 1         | 0.34%   |
| 601-700     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 189       | 67.5%   |
| 16/10   | 47        | 16.79%  |
| 5/4     | 29        | 10.36%  |
| Unknown | 8         | 2.86%   |
| 4/3     | 5         | 1.79%   |
| 3/2     | 2         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 21%     |
| 81-90          | 53        | 17.67%  |
| 141-150        | 52        | 17.33%  |
| 151-200        | 45        | 15%     |
| 201-250        | 28        | 9.33%   |
| Unknown        | 11        | 3.67%   |
| 41-50          | 10        | 3.33%   |
| 121-130        | 10        | 3.33%   |
| More than 1000 | 8         | 2.67%   |
| 51-60          | 5         | 1.67%   |
| 351-500        | 3         | 1%      |
| 301-350        | 3         | 1%      |
| 71-80          | 2         | 0.67%   |
| 61-70          | 2         | 0.67%   |
| 251-300        | 2         | 0.67%   |
| 131-140        | 1         | 0.33%   |
| 501-1000       | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 130       | 43.77%  |
| 101-120       | 95        | 31.99%  |
| 121-160       | 48        | 16.16%  |
| Unknown       | 11        | 3.7%    |
| 1-50          | 10        | 3.37%   |
| 161-240       | 2         | 0.67%   |
| More than 240 | 1         | 0.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 257       | 82.9%   |
| 2     | 31        | 10%     |
| 0     | 19        | 6.13%   |
| 3     | 3         | 0.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 190       | 38.46%  |
| Intel                             | 92        | 18.62%  |
| Qualcomm Atheros                  | 84        | 17%     |
| Broadcom                          | 28        | 5.67%   |
| Ralink                            | 15        | 3.04%   |
| Nvidia                            | 15        | 3.04%   |
| Ralink Technology                 | 10        | 2.02%   |
| Xiaomi                            | 7         | 1.42%   |
| Qualcomm Atheros Communications   | 6         | 1.21%   |
| Broadcom Limited                  | 6         | 1.21%   |
| TP-Link                           | 5         | 1.01%   |
| Marvell Technology Group          | 5         | 1.01%   |
| JMicron Technology                | 4         | 0.81%   |
| VIA Technologies                  | 3         | 0.61%   |
| Samsung Electronics               | 3         | 0.61%   |
| MediaTek                          | 3         | 0.61%   |
| Trendchip Technologies            | 2         | 0.4%    |
| Sundance Technology Inc / IC Plus | 2         | 0.4%    |
| Mercucys                          | 2         | 0.4%    |
| D-Link System                     | 2         | 0.4%    |
| ZyXEL Communications              | 1         | 0.2%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.2%    |
| National Semiconductor            | 1         | 0.2%    |
| Motorola PCS                      | 1         | 0.2%    |
| Motorola BCS                      | 1         | 0.2%    |
| ICS Advent                        | 1         | 0.2%    |
| Huawei Technologies               | 1         | 0.2%    |
| Digium                            | 1         | 0.2%    |
| ASIX Electronics                  | 1         | 0.2%    |
| AMD                               | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 112       | 20.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 37        | 6.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 16        | 2.89%   |
| Nvidia MCP61 Ethernet                                                   | 14        | 2.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 9         | 1.63%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 1.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 8         | 1.45%   |
| Intel Wireless 7265                                                     | 8         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 1.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.08%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 1.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 5         | 0.9%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.9%    |
| Intel Wireless 7260                                                     | 5         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 4         | 0.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 4         | 0.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 4         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.72%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.72%   |
| Intel Centrino Wireless-N 105                                           | 4         | 0.72%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                   | 4         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.72%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.72%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 3         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 3         | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 63        | 26.14%  |
| Qualcomm Atheros                | 61        | 25.31%  |
| Intel                           | 56        | 23.24%  |
| Broadcom                        | 16        | 6.64%   |
| Ralink                          | 15        | 6.22%   |
| Ralink Technology               | 10        | 4.15%   |
| Qualcomm Atheros Communications | 6         | 2.49%   |
| TP-Link                         | 4         | 1.66%   |
| MediaTek                        | 3         | 1.24%   |
| Mercucys                        | 2         | 0.83%   |
| D-Link System                   | 2         | 0.83%   |
| Broadcom Limited                | 2         | 0.83%   |
| Xiaomi                          | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 16        | 6.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 11        | 4.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 3.73%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 8         | 3.32%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 8         | 3.32%   |
| Intel Wireless 7265                                                            | 8         | 3.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 7         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 6         | 2.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5         | 2.07%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 2.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 2.07%   |
| Intel Wireless 7260                                                            | 5         | 2.07%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 4         | 1.66%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4         | 1.66%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 1.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.66%   |
| Ralink MT7601U Wireless Adapter                                                | 4         | 1.66%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4         | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 1.66%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4         | 1.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 4         | 1.66%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 1.66%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 1.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 1.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 1.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 3         | 1.24%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.24%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.24%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 1.24%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 1.24%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.24%   |
| Intel WiFi Link 5100                                                           | 3         | 1.24%   |
| Intel Wi-Fi 6 AX201                                                            | 3         | 1.24%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 3         | 1.24%   |
| Intel Centrino Ultimate-N 6300                                                 | 3         | 1.24%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 3         | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2         | 0.83%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 2         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 159       | 52.82%  |
| Intel                             | 50        | 16.61%  |
| Qualcomm Atheros                  | 31        | 10.3%   |
| Nvidia                            | 15        | 4.98%   |
| Broadcom                          | 13        | 4.32%   |
| Xiaomi                            | 6         | 1.99%   |
| Marvell Technology Group          | 5         | 1.66%   |
| JMicron Technology                | 4         | 1.33%   |
| Broadcom Limited                  | 4         | 1.33%   |
| VIA Technologies                  | 3         | 1%      |
| Trendchip Technologies            | 2         | 0.66%   |
| Sundance Technology Inc / IC Plus | 2         | 0.66%   |
| ZyXEL Communications              | 1         | 0.33%   |
| TP-Link                           | 1         | 0.33%   |
| National Semiconductor            | 1         | 0.33%   |
| Motorola PCS                      | 1         | 0.33%   |
| Motorola BCS                      | 1         | 0.33%   |
| ICS Advent                        | 1         | 0.33%   |
| ASIX Electronics                  | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 112       | 36.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 37        | 12.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 16        | 5.25%   |
| Nvidia MCP61 Ethernet                                                      | 14        | 4.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 9         | 2.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7         | 2.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 7         | 2.3%    |
| Intel Ethernet Connection I217-LM                                          | 6         | 1.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 5         | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4         | 1.31%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4         | 1.31%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3         | 0.98%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 3         | 0.98%   |
| Intel PRO/100 VE Network Connection                                        | 3         | 0.98%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 3         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2         | 0.66%   |
| Trendchip Ethernet controller                                              | 2         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2         | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                           | 2         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                      | 2         | 0.66%   |
| Intel 82574L Gigabit Network Connection                                    | 2         | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.66%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                        | 2         | 0.66%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                | 2         | 0.66%   |
| ZyXEL ADSL Modem Prestige 600 series                                       | 1         | 0.33%   |
| TP-Link M7200                                                              | 1         | 0.33%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.33%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.33%   |
| Realtek PCIe GbE Family Controller                                         | 1         | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1         | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                      | 1         | 0.33%   |
| Nvidia MCP77 Ethernet                                                      | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 281       | 54.35%  |
| WiFi     | 229       | 44.29%  |
| Modem    | 6         | 1.16%   |
| Unknown  | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 52.8%   |
| Ethernet | 152       | 47.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 177       | 56.91%  |
| 1     | 126       | 40.51%  |
| 3     | 4         | 1.29%   |
| 0     | 3         | 0.96%   |
| 4     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 306       | 99.35%  |
| Yes  | 2         | 0.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 33.04%  |
| Realtek Semiconductor           | 16        | 14.29%  |
| Qualcomm Atheros Communications | 13        | 11.61%  |
| IMC Networks                    | 13        | 11.61%  |
| Cambridge Silicon Radio         | 10        | 8.93%   |
| Broadcom                        | 9         | 8.04%   |
| Lite-On Technology              | 4         | 3.57%   |
| Apple                           | 4         | 3.57%   |
| ASUSTek Computer                | 3         | 2.68%   |
| Hewlett-Packard                 | 2         | 1.79%   |
| Dell                            | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 16.96%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 10        | 8.93%   |
| Realtek RTL8723B Bluetooth                                  | 7         | 6.25%   |
| Intel AX201 Bluetooth                                       | 7         | 6.25%   |
| Realtek Bluetooth Radio                                     | 6         | 5.36%   |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 4.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 3.57%   |
| Intel AX200 Bluetooth                                       | 4         | 3.57%   |
| IMC Networks Bluetooth                                      | 4         | 3.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.68%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 2.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 2.68%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 2.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 2.68%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.79%   |
| IMC Networks Wireless_Device                                | 2         | 1.79%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.79%   |
| IMC Networks Bluetooth Module                               | 2         | 1.79%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.89%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 1         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.89%   |
| Lite-On Wireless_Device                                     | 1         | 0.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.89%   |
| Lite-On Bluetooth Device                                    | 1         | 0.89%   |
| Lite-On BCM20702A0                                          | 1         | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.89%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.89%   |
| Broadcom HP Portable Valentine                              | 1         | 0.89%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle         | 1         | 0.89%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.89%   |
| Broadcom BCM2070 Bluetooth Device                           | 1         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.89%   |
| Broadcom BCM2035B3 Bluetooth Adapter                        | 1         | 0.89%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.89%   |
| ASUS Bluetooth Adapter                                      | 1         | 0.89%   |
| Apple Bluetooth HCI                                         | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 241       | 62.92%  |
| AMD                       | 61        | 15.93%  |
| Nvidia                    | 44        | 11.49%  |
| C-Media Electronics       | 8         | 2.09%   |
| VIA Technologies          | 4         | 1.04%   |
| Creative Labs             | 4         | 1.04%   |
| Zhaoxin                   | 3         | 0.78%   |
| Logitech                  | 3         | 0.78%   |
| JMTek                     | 3         | 0.78%   |
| Sennheiser Communications | 2         | 0.52%   |
| Microsoft                 | 2         | 0.52%   |
| Generalplus Technology    | 2         | 0.52%   |
| Unknown                   | 1         | 0.26%   |
| Realtek Semiconductor     | 1         | 0.26%   |
| Megawin Technology        | 1         | 0.26%   |
| Giga-Byte Technology      | 1         | 0.26%   |
| Cirrus Logic              | 1         | 0.26%   |
| Aureal Semiconductor      | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 48        | 10.96%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 47        | 10.73%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 7.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 3.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 3.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 2.97%   |
| Nvidia MCP61 High Definition Audio                                                                | 12        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.51%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 2.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 1.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.83%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 1.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.37%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.14%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.91%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 3         | 0.68%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 3         | 0.68%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.68%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.68%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.68%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.68%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 3         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.68%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 59        | 22.78%  |
| Samsung Electronics        | 38        | 14.67%  |
| SK hynix                   | 36        | 13.9%   |
| Ramaxel Technology         | 24        | 9.27%   |
| Kingston                   | 24        | 9.27%   |
| Micron Technology          | 17        | 6.56%   |
| Crucial                    | 12        | 4.63%   |
| Corsair                    | 8         | 3.09%   |
| Elpida                     | 6         | 2.32%   |
| Team                       | 4         | 1.54%   |
| Qimonda                    | 3         | 1.16%   |
| Nanya Technology           | 3         | 1.16%   |
| A-DATA Technology          | 3         | 1.16%   |
| Unknown                    | 3         | 1.16%   |
| Unknown (ABCD)             | 2         | 0.77%   |
| Unknown (0x07D5)           | 2         | 0.77%   |
| Shenzhen WODPOSIT          | 2         | 0.77%   |
| Avant                      | 2         | 0.77%   |
| Unknown (7F7F7F7F7F7F7F83) | 1         | 0.39%   |
| Unknown (0x0CBA)           | 1         | 0.39%   |
| Unknown (081A)             | 1         | 0.39%   |
| Unknown (07F7)             | 1         | 0.39%   |
| PNY                        | 1         | 0.39%   |
| OCZ                        | 1         | 0.39%   |
| Memox                      | 1         | 0.39%   |
| Kreton                     | 1         | 0.39%   |
| Gold Key                   | 1         | 0.39%   |
| Apacer                     | 1         | 0.39%   |
| <Invalid>                  | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 4         | 1.39%   |
| Unknown RAM Module 4GB DIMM SDRAM                       | 3         | 1.05%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 3         | 1.05%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 3         | 1.05%   |
| Unknown RAM Module 2048MB DIMM DDR2                     | 3         | 1.05%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 3         | 1.05%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 1.05%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s  | 3         | 1.05%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 3         | 1.05%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s | 3         | 1.05%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s | 3         | 1.05%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s | 3         | 1.05%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s | 3         | 1.05%   |
| Unknown                                                 | 3         | 1.05%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2         | 0.7%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 2         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s             | 2         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s               | 2         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2                        | 2         | 0.7%    |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 2         | 0.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 2         | 0.7%    |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 2         | 0.7%    |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s             | 2         | 0.7%    |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s    | 2         | 0.7%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s    | 2         | 0.7%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s  | 2         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 2         | 0.7%    |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s | 2         | 0.7%    |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s   | 2         | 0.7%    |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s             | 2         | 0.7%    |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s               | 2         | 0.7%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s   | 2         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 2         | 0.7%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2         | 0.7%    |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s     | 2         | 0.7%    |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s   | 2         | 0.7%    |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s   | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 80        | 39.6%   |
| DDR4    | 43        | 21.29%  |
| DDR2    | 37        | 18.32%  |
| SDRAM   | 20        | 9.9%    |
| Unknown | 14        | 6.93%   |
| DDR     | 5         | 2.48%   |
| LPDDR4  | 3         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 98        | 50.26%  |
| SODIMM       | 94        | 48.21%  |
| Row Of Chips | 3         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 78        | 33.62%  |
| 4096  | 72        | 31.03%  |
| 8192  | 46        | 19.83%  |
| 1024  | 22        | 9.48%   |
| 16384 | 9         | 3.88%   |
| 32768 | 3         | 1.29%   |
| 512   | 2         | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 22.12%  |
| 1333    | 32        | 14.16%  |
| Unknown | 20        | 8.85%   |
| 3200    | 17        | 7.52%   |
| 2667    | 15        | 6.64%   |
| 667     | 15        | 6.64%   |
| 800     | 11        | 4.87%   |
| 2400    | 8         | 3.54%   |
| 1066    | 7         | 3.1%    |
| 533     | 7         | 3.1%    |
| 400     | 5         | 2.21%   |
| 2048    | 4         | 1.77%   |
| 1334    | 4         | 1.77%   |
| 2666    | 3         | 1.33%   |
| 2133    | 3         | 1.33%   |
| 1867    | 3         | 1.33%   |
| 1639    | 3         | 1.33%   |
| 1067    | 3         | 1.33%   |
| 133     | 3         | 1.33%   |
| 4199    | 2         | 0.88%   |
| 3266    | 2         | 0.88%   |
| 975     | 2         | 0.88%   |
| 3800    | 1         | 0.44%   |
| 3733    | 1         | 0.44%   |
| 3600    | 1         | 0.44%   |
| 3000    | 1         | 0.44%   |
| 2000    | 1         | 0.44%   |
| 1800    | 1         | 0.44%   |
| 1024    | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 58.33%  |
| Seiko Epson         | 3         | 25%     |
| Samsung Electronics | 2         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 8.33%   |
| Seiko Epson L6160 Series                     | 1         | 8.33%   |
| Seiko Epson L210 Series                      | 1         | 8.33%   |
| Samsung ML-216x Series Laser Printer         | 1         | 8.33%   |
| Samsung ML-1865                              | 1         | 8.33%   |
| HP LaserJet Professional P1102w              | 1         | 8.33%   |
| HP LaserJet P1006                            | 1         | 8.33%   |
| HP LaserJet P1005                            | 1         | 8.33%   |
| HP LaserJet 1018                             | 1         | 8.33%   |
| HP DeskJet F4100 Printer series              | 1         | 8.33%   |
| HP DeskJet 2300 series                       | 1         | 8.33%   |
| HP Color LaserJet CP1215                     | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| KYE Systems (Mouse Systems) | 1         | 33.33%  |
| Hewlett-Packard             | 1         | 33.33%  |
| Canon                       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE | 1         | 33.33%  |
| HP Scanjet 200                                      | 1         | 33.33%  |
| Canon CanoScan LiDE 110                             | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 32        | 22.07%  |
| Microdia                               | 15        | 10.34%  |
| IMC Networks                           | 11        | 7.59%   |
| Realtek Semiconductor                  | 10        | 6.9%    |
| Bison Electronics                      | 9         | 6.21%   |
| Suyin                                  | 8         | 5.52%   |
| Logitech                               | 5         | 3.45%   |
| Apple                                  | 5         | 3.45%   |
| Acer                                   | 5         | 3.45%   |
| Syntek                                 | 4         | 2.76%   |
| Sunplus Innovation Technology          | 4         | 2.76%   |
| Quanta                                 | 4         | 2.76%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.76%   |
| Samsung Electronics                    | 3         | 2.07%   |
| Ricoh                                  | 3         | 2.07%   |
| Microsoft                              | 3         | 2.07%   |
| Lite-On Technology                     | 3         | 2.07%   |
| ALi                                    | 3         | 2.07%   |
| Sonix Technology                       | 2         | 1.38%   |
| KYE Systems (Mouse Systems)            | 2         | 1.38%   |
| Tobii Technology AB                    | 1         | 0.69%   |
| Silicon Motion                         | 1         | 0.69%   |
| SiGma Micro                            | 1         | 0.69%   |
| Luxvisions Innotech Limited            | 1         | 0.69%   |
| LG Electronics                         | 1         | 0.69%   |
| Lenovo                                 | 1         | 0.69%   |
| Importek                               | 1         | 0.69%   |
| icSpring                               | 1         | 0.69%   |
| Cubeternet                             | 1         | 0.69%   |
| Aveo Technology                        | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 11        | 7.59%   |
| Microdia USB 2.0 Camera                                       | 5         | 3.45%   |
| Bison HD Webcam                                               | 5         | 3.45%   |
| Realtek Integrated_Webcam_HD                                  | 4         | 2.76%   |
| Chicony Lenovo EasyCamera                                     | 4         | 2.76%   |
| Chicony Integrated Camera                                     | 4         | 2.76%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 3         | 2.07%   |
| Logitech Webcam C270                                          | 3         | 2.07%   |
| IMC Networks XHC Camera                                       | 3         | 2.07%   |
| Chicony HD Webcam                                             | 3         | 2.07%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 3         | 2.07%   |
| Apple Built-in iSight                                         | 3         | 2.07%   |
| Suyin Integrated_Webcam_HD                                    | 2         | 1.38%   |
| Suyin HP Webcam 101                                           | 2         | 1.38%   |
| Sunplus Integrated_Webcam_HD                                  | 2         | 1.38%   |
| Sonix USB2.0 HD UVC WebCam                                    | 2         | 1.38%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.38%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.38%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.38%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.38%   |
| Chicony HP Wide Vision HD Camera                              | 2         | 1.38%   |
| ALi WebCam                                                    | 2         | 1.38%   |
| Acer USB Camera                                               | 2         | 1.38%   |
| Tobii AB EyeChip                                              | 1         | 0.69%   |
| Syntek USB Camera Device                                      | 1         | 0.69%   |
| Syntek Integrated Webcam                                      | 1         | 0.69%   |
| Syntek Integrated Camera                                      | 1         | 0.69%   |
| Syntek EasyCamera                                             | 1         | 0.69%   |
| Suyin USB2.0 UVC 1.3M WebCam                                  | 1         | 0.69%   |
| Suyin HP Webcam                                               | 1         | 0.69%   |
| Suyin HD Video WebCam                                         | 1         | 0.69%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.69%   |
| Sunplus MTD Camera                                            | 1         | 0.69%   |
| Sunplus Lenovo EasyCamera                                     | 1         | 0.69%   |
| Silicon Motion WebCam SC-10HDD13335N                          | 1         | 0.69%   |
| SiGma Micro WebCam SiGma Micro                                | 1         | 0.69%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 0.69%   |
| Realtek USB2.0 camera                                         | 1         | 0.69%   |
| Realtek USB Camera                                            | 1         | 0.69%   |
| Realtek Integrated Webcam HD                                  | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 43.75%  |
| AuthenTec                  | 3         | 18.75%  |
| Synaptics                  | 2         | 12.5%   |
| Upek                       | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| Futronic Technology        | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 18.75%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 12.5%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 12.5%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics UWP WBDI                                     | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 6.25%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                       | 1         | 6.25%   |
| AuthenTec AES1600                                      | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 80%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 237       | 76.45%  |
| 1     | 61        | 19.68%  |
| 2     | 11        | 3.55%   |
| 4     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 34        | 39.08%  |
| Fingerprint reader       | 16        | 18.39%  |
| Communication controller | 11        | 12.64%  |
| Net/wireless             | 8         | 9.2%    |
| Sound                    | 6         | 6.9%    |
| Chipcard                 | 5         | 5.75%   |
| Camera                   | 4         | 4.6%    |
| Storage                  | 1         | 1.15%   |
| Network                  | 1         | 1.15%   |
| Multimedia controller    | 1         | 1.15%   |

