Ubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 6497

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X550CC                      | [cc784397f9](https://linux-hardware.org/?probe=cc784397f9) | May 01, 2023 |
| Dell          | Latitude 3420               | [327be624ce](https://linux-hardware.org/?probe=327be624ce) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [842333a8da](https://linux-hardware.org/?probe=842333a8da) | May 01, 2023 |
| Dell          | Latitude 3420               | [1ce0c58a17](https://linux-hardware.org/?probe=1ce0c58a17) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6A0LJCL    | [f67154866c](https://linux-hardware.org/?probe=f67154866c) | May 01, 2023 |
| Acer          | Nitro AN517-54              | [593a6b247f](https://linux-hardware.org/?probe=593a6b247f) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [4f72daaab8](https://linux-hardware.org/?probe=4f72daaab8) | May 01, 2023 |
| HP            | EliteBook 8470p             | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| Unknown       | Unknown                     | [8978b9aa5f](https://linux-hardware.org/?probe=8978b9aa5f) | May 01, 2023 |
| HP            | Unknown                     | [475eb33956](https://linux-hardware.org/?probe=475eb33956) | May 01, 2023 |
| Unknown       | Unknown                     | [070854df6b](https://linux-hardware.org/?probe=070854df6b) | Apr 30, 2023 |
| Lenovo        | Z50-75 80EC                 | [af5d37f4f7](https://linux-hardware.org/?probe=af5d37f4f7) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Dell          | Vostro 3558                 | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| Dell          | XPS 13 9350                 | [95b5e79487](https://linux-hardware.org/?probe=95b5e79487) | Apr 30, 2023 |
| Acer          | Aspire E5-551G              | [bba2f8d1ad](https://linux-hardware.org/?probe=bba2f8d1ad) | Apr 30, 2023 |
| Dell          | Vostro 5468                 | [93eb16d30d](https://linux-hardware.org/?probe=93eb16d30d) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [28b11100ac](https://linux-hardware.org/?probe=28b11100ac) | Apr 30, 2023 |
| Gateway       | P-7805u                     | [0958f250f2](https://linux-hardware.org/?probe=0958f250f2) | Apr 30, 2023 |
| Maibenben     | MaiBook X series            | [5f97e34b20](https://linux-hardware.org/?probe=5f97e34b20) | Apr 30, 2023 |
| Dell          | G15 5511                    | [7d5f166e7a](https://linux-hardware.org/?probe=7d5f166e7a) | Apr 30, 2023 |
| Dell          | XPS 13 7390                 | [c5000ec967](https://linux-hardware.org/?probe=c5000ec967) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [272103e5a7](https://linux-hardware.org/?probe=272103e5a7) | Apr 29, 2023 |
| ASUSTek       | G56JR                       | [b7eb868ec4](https://linux-hardware.org/?probe=b7eb868ec4) | Apr 29, 2023 |
| Acer          | TravelMate 5730             | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Dell          | Inspiron 7773               | [19741ac2ea](https://linux-hardware.org/?probe=19741ac2ea) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [21d008c7d8](https://linux-hardware.org/?probe=21d008c7d8) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [49557b8214](https://linux-hardware.org/?probe=49557b8214) | Apr 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [7598c18042](https://linux-hardware.org/?probe=7598c18042) | Apr 29, 2023 |
| Dell          | Latitude E5470              | [c6c943679f](https://linux-hardware.org/?probe=c6c943679f) | Apr 29, 2023 |
| ASUSTek       | X756UVK                     | [72ba8fbf57](https://linux-hardware.org/?probe=72ba8fbf57) | Apr 29, 2023 |
| Dell          | Latitude 3301               | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| Dell          | Precision M6600             | [39d9af4736](https://linux-hardware.org/?probe=39d9af4736) | Apr 28, 2023 |
| Dell          | Inspiron 3180               | [bc3400a372](https://linux-hardware.org/?probe=bc3400a372) | Apr 28, 2023 |
| Dell          | Inspiron 15-3567            | [5dcd15cacf](https://linux-hardware.org/?probe=5dcd15cacf) | Apr 28, 2023 |
| Dell          | Latitude E5450              | [85fb3ec2fd](https://linux-hardware.org/?probe=85fb3ec2fd) | Apr 28, 2023 |
| Acer          | Aspire ES1-731              | [140e5eb8fc](https://linux-hardware.org/?probe=140e5eb8fc) | Apr 28, 2023 |
| Acer          | Swift SF314-57G             | [6fd79b811f](https://linux-hardware.org/?probe=6fd79b811f) | Apr 28, 2023 |
| HP            | Laptop 15-ef2xxx            | [f922f80a69](https://linux-hardware.org/?probe=f922f80a69) | Apr 28, 2023 |
| Pegatron      | A15                         | [e9de945dce](https://linux-hardware.org/?probe=e9de945dce) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [65f390b956](https://linux-hardware.org/?probe=65f390b956) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [31bdde77c9](https://linux-hardware.org/?probe=31bdde77c9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [eb550390c1](https://linux-hardware.org/?probe=eb550390c1) | Apr 28, 2023 |
| Dell          | Latitude 3301               | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [7c34e35183](https://linux-hardware.org/?probe=7c34e35183) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [266477f792](https://linux-hardware.org/?probe=266477f792) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [ceaa38e624](https://linux-hardware.org/?probe=ceaa38e624) | Apr 28, 2023 |
| Gigabyte      | G5 GD                       | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| HP            | Compaq 6910p                | [049253c0c8](https://linux-hardware.org/?probe=049253c0c8) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | XPS 13 7390                 | [318ea8ad1e](https://linux-hardware.org/?probe=318ea8ad1e) | Apr 27, 2023 |
| Dell          | XPS 15 9520                 | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [f428173506](https://linux-hardware.org/?probe=f428173506) | Apr 27, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [6a56164bfd](https://linux-hardware.org/?probe=6a56164bfd) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [9344f38032](https://linux-hardware.org/?probe=9344f38032) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [393c7b06d5](https://linux-hardware.org/?probe=393c7b06d5) | Apr 26, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Toshiba       | Satellite Pro S500          | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Sony          | SVD1322X2EW                 | [2574ef07fb](https://linux-hardware.org/?probe=2574ef07fb) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | [d910b01835](https://linux-hardware.org/?probe=d910b01835) | Apr 26, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3c104a89ef](https://linux-hardware.org/?probe=3c104a89ef) | Apr 26, 2023 |
| Dell          | Vostro 15 3510              | [81cae0ba77](https://linux-hardware.org/?probe=81cae0ba77) | Apr 26, 2023 |
| Dell          | XPS 15 9500                 | [e37d368767](https://linux-hardware.org/?probe=e37d368767) | Apr 26, 2023 |
| HP            | EliteBook Folio 9470m       | [e0d69966e9](https://linux-hardware.org/?probe=e0d69966e9) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [940cbb6ef0](https://linux-hardware.org/?probe=940cbb6ef0) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [5daf26faca](https://linux-hardware.org/?probe=5daf26faca) | Apr 26, 2023 |
| System76      | Gazelle                     | [dbf4d8b33d](https://linux-hardware.org/?probe=dbf4d8b33d) | Apr 26, 2023 |
| Dell          | Precision M6600             | [4f5cd6d28e](https://linux-hardware.org/?probe=4f5cd6d28e) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349UKM       | [6adb010c7a](https://linux-hardware.org/?probe=6adb010c7a) | Apr 25, 2023 |
| Acer          | Aspire E1-571               | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Timi          | Mi NoteBook Ultra           | [b6b7cdfe22](https://linux-hardware.org/?probe=b6b7cdfe22) | Apr 25, 2023 |
| Acer          | Nitro AN517-42              | [5e54d08f91](https://linux-hardware.org/?probe=5e54d08f91) | Apr 25, 2023 |
| Avell High... | A70 HYB BS                  | [c7b5f9ef04](https://linux-hardware.org/?probe=c7b5f9ef04) | Apr 25, 2023 |
| Dell          | XPS 13 9310                 | [b9bc4703a8](https://linux-hardware.org/?probe=b9bc4703a8) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| Dell          | Latitude 5490               | [32ddaf898c](https://linux-hardware.org/?probe=32ddaf898c) | Apr 25, 2023 |
| HP            | 255 G5 Notebook PC          | [c542c2df7e](https://linux-hardware.org/?probe=c542c2df7e) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [3a7c24a13f](https://linux-hardware.org/?probe=3a7c24a13f) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d5bd7e8fa](https://linux-hardware.org/?probe=7d5bd7e8fa) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [24bf298df5](https://linux-hardware.org/?probe=24bf298df5) | Apr 25, 2023 |
| Lenovo        | ThinkPad Edge E545 20B20... | [fd66f3852a](https://linux-hardware.org/?probe=fd66f3852a) | Apr 25, 2023 |
| Notebook      | W650EH                      | [8e848e589e](https://linux-hardware.org/?probe=8e848e589e) | Apr 25, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [5fd25f9235](https://linux-hardware.org/?probe=5fd25f9235) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | [37f98c9450](https://linux-hardware.org/?probe=37f98c9450) | Apr 25, 2023 |
| Dell          | Inspiron 3543               | [2a3020f392](https://linux-hardware.org/?probe=2a3020f392) | Apr 24, 2023 |
| ASUSTek       | X510UQR                     | [4a2e357ace](https://linux-hardware.org/?probe=4a2e357ace) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9e926f5c65](https://linux-hardware.org/?probe=9e926f5c65) | Apr 24, 2023 |
| Dell          | Vostro 15 3515              | [13c75fa32e](https://linux-hardware.org/?probe=13c75fa32e) | Apr 24, 2023 |
| INSYS         | PT1-140C                    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| Lenovo        | G700                        | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Dell          | System XPS L502X            | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [253f35c2c3](https://linux-hardware.org/?probe=253f35c2c3) | Apr 24, 2023 |
| Dell          | Inspiron 15 5510            | [c8f22361f6](https://linux-hardware.org/?probe=c8f22361f6) | Apr 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [2787d97e6e](https://linux-hardware.org/?probe=2787d97e6e) | Apr 24, 2023 |
| Fujitsu       | LIFEBOOK S751               | [e01b26f35f](https://linux-hardware.org/?probe=e01b26f35f) | Apr 24, 2023 |
| HP            | Laptop 15-db0xxx            | [2ab42d58bf](https://linux-hardware.org/?probe=2ab42d58bf) | Apr 24, 2023 |
| HP            | Laptop 15-db0xxx            | [8c5aea6211](https://linux-hardware.org/?probe=8c5aea6211) | Apr 24, 2023 |
| Dell          | Inspiron 3542               | [9f4ce3c5a4](https://linux-hardware.org/?probe=9f4ce3c5a4) | Apr 24, 2023 |
| LG Electro... | 16Z90Q-G.AD78F              | [99bbc09adb](https://linux-hardware.org/?probe=99bbc09adb) | Apr 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS16G0... | [b019f5af89](https://linux-hardware.org/?probe=b019f5af89) | Apr 24, 2023 |
| HP            | ProBook 450 G7              | [57f0ae7486](https://linux-hardware.org/?probe=57f0ae7486) | Apr 24, 2023 |
| ASUSTek       | PRIME X670-P                | [ebe7f36c99](https://linux-hardware.org/?probe=ebe7f36c99) | Apr 23, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e562ba35c6](https://linux-hardware.org/?probe=e562ba35c6) | Apr 23, 2023 |
| HP            | 350 G2                      | [ffa4ab3dc0](https://linux-hardware.org/?probe=ffa4ab3dc0) | Apr 23, 2023 |
| Samsung       | R510/P510                   | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| HP            | G42                         | [1d5b2eefc3](https://linux-hardware.org/?probe=1d5b2eefc3) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | [f6fe80f275](https://linux-hardware.org/?probe=f6fe80f275) | Apr 23, 2023 |
| MSI           | Bravo 15 B5DD               | [180f1dd402](https://linux-hardware.org/?probe=180f1dd402) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [b4dfa57eea](https://linux-hardware.org/?probe=b4dfa57eea) | Apr 23, 2023 |
| Sony          | SVD1322X2EW                 | [1652ce4c8f](https://linux-hardware.org/?probe=1652ce4c8f) | Apr 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [18fc5f09ed](https://linux-hardware.org/?probe=18fc5f09ed) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [1a45f96f80](https://linux-hardware.org/?probe=1a45f96f80) | Apr 23, 2023 |
| Acer          | Aspire A515-57              | [23f076b6d3](https://linux-hardware.org/?probe=23f076b6d3) | Apr 23, 2023 |
| HP            | Pavilion dv7                | [0ca422761e](https://linux-hardware.org/?probe=0ca422761e) | Apr 23, 2023 |
| Dell          | Latitude E7240              | [1b5828d441](https://linux-hardware.org/?probe=1b5828d441) | Apr 23, 2023 |
| ASUSTek       | UX310UA                     | [a7b628ab1c](https://linux-hardware.org/?probe=a7b628ab1c) | Apr 23, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [aa23589794](https://linux-hardware.org/?probe=aa23589794) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| Toshiba       | Satellite Pro S500          | [fcf8a7bdb4](https://linux-hardware.org/?probe=fcf8a7bdb4) | Apr 23, 2023 |
| Sony          | VPCF13M1E                   | [023cbeeac3](https://linux-hardware.org/?probe=023cbeeac3) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [77a309dcf1](https://linux-hardware.org/?probe=77a309dcf1) | Apr 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [25e942e55c](https://linux-hardware.org/?probe=25e942e55c) | Apr 22, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [4c60675864](https://linux-hardware.org/?probe=4c60675864) | Apr 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | [13b6b127e6](https://linux-hardware.org/?probe=13b6b127e6) | Apr 22, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| Apple         | MacBookPro11,5              | [7a873a7baa](https://linux-hardware.org/?probe=7a873a7baa) | Apr 22, 2023 |
| Dell          | Latitude E6500              | [5de8825606](https://linux-hardware.org/?probe=5de8825606) | Apr 22, 2023 |
| HP            | Pavilion g7                 | [785e97ad3d](https://linux-hardware.org/?probe=785e97ad3d) | Apr 22, 2023 |
| HP            | Pavilion g7                 | [0e6f1d6bf7](https://linux-hardware.org/?probe=0e6f1d6bf7) | Apr 22, 2023 |
| Medion        | Akoya E7416T                | [da5ea2c44b](https://linux-hardware.org/?probe=da5ea2c44b) | Apr 22, 2023 |
| Unknown       | M-140BI5                    | [32ba023e2a](https://linux-hardware.org/?probe=32ba023e2a) | Apr 22, 2023 |
| Acer          | Aspire E5-772               | [edfa9fcbef](https://linux-hardware.org/?probe=edfa9fcbef) | Apr 22, 2023 |
| Lenovo        | Z50-70 20354                | [76f54ae42f](https://linux-hardware.org/?probe=76f54ae42f) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | [a26039eb50](https://linux-hardware.org/?probe=a26039eb50) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | [7e7a982c3c](https://linux-hardware.org/?probe=7e7a982c3c) | Apr 22, 2023 |
| Lenovo        | N22 80S6                    | [e915245bfd](https://linux-hardware.org/?probe=e915245bfd) | Apr 22, 2023 |
| HP            | ProBook 4540s               | [12ee30d786](https://linux-hardware.org/?probe=12ee30d786) | Apr 22, 2023 |
| AMI           | Cherry Trail CR             | [325dfde573](https://linux-hardware.org/?probe=325dfde573) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [3056a65306](https://linux-hardware.org/?probe=3056a65306) | Apr 22, 2023 |
| HP            | Pavilion 15                 | [ac3f0ac1d5](https://linux-hardware.org/?probe=ac3f0ac1d5) | Apr 21, 2023 |
| HP            | Pavilion 15                 | [877b05303e](https://linux-hardware.org/?probe=877b05303e) | Apr 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2a507e00bf](https://linux-hardware.org/?probe=2a507e00bf) | Apr 21, 2023 |
| Gigabyte      | AERO 16 KE5                 | [9e4fe316b8](https://linux-hardware.org/?probe=9e4fe316b8) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [9a23d08368](https://linux-hardware.org/?probe=9a23d08368) | Apr 21, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [52cfdbde2d](https://linux-hardware.org/?probe=52cfdbde2d) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [6b255d5f07](https://linux-hardware.org/?probe=6b255d5f07) | Apr 21, 2023 |
| Dell          | Precision M6600             | [6f80333ca9](https://linux-hardware.org/?probe=6f80333ca9) | Apr 21, 2023 |
| HP            | EliteBook 2540p             | [b2a6b1a66d](https://linux-hardware.org/?probe=b2a6b1a66d) | Apr 21, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [af72838c03](https://linux-hardware.org/?probe=af72838c03) | Apr 21, 2023 |
| ASUSTek       | ZenBook UX333FN_RX333FN     | [8027ff2b04](https://linux-hardware.org/?probe=8027ff2b04) | Apr 21, 2023 |
| Dell          | Latitude 7280               | [1359a75ba3](https://linux-hardware.org/?probe=1359a75ba3) | Apr 21, 2023 |
| Medion        | S15449                      | [c63e98624a](https://linux-hardware.org/?probe=c63e98624a) | Apr 21, 2023 |
| HP            | Pavilion Sleekbook 15       | [644ea805a9](https://linux-hardware.org/?probe=644ea805a9) | Apr 21, 2023 |
| Medion        | S15449                      | [914511ca07](https://linux-hardware.org/?probe=914511ca07) | Apr 21, 2023 |
| Dell          | Latitude E6500              | [363b443628](https://linux-hardware.org/?probe=363b443628) | Apr 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6dcb6d41ef](https://linux-hardware.org/?probe=6dcb6d41ef) | Apr 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6e2da1e766](https://linux-hardware.org/?probe=6e2da1e766) | Apr 21, 2023 |
| Google        | Swanky                      | [92156daf53](https://linux-hardware.org/?probe=92156daf53) | Apr 21, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [acbe851404](https://linux-hardware.org/?probe=acbe851404) | Apr 21, 2023 |
| Lenovo        | ThinkPad W530 2436CTO       | [74d9f6c0d6](https://linux-hardware.org/?probe=74d9f6c0d6) | Apr 21, 2023 |
| HP            | EliteBook 2540p             | [be19bcd7de](https://linux-hardware.org/?probe=be19bcd7de) | Apr 21, 2023 |
| PC Special... | TN1-156M                    | [ef6b57e807](https://linux-hardware.org/?probe=ef6b57e807) | Apr 21, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [167000be9b](https://linux-hardware.org/?probe=167000be9b) | Apr 21, 2023 |
| Dell          | Vostro 3550                 | [21111146cd](https://linux-hardware.org/?probe=21111146cd) | Apr 21, 2023 |
| Dell          | G15 5510                    | [43d4ce3c37](https://linux-hardware.org/?probe=43d4ce3c37) | Apr 21, 2023 |
| HP            | Notebook                    | [150b1d6ae7](https://linux-hardware.org/?probe=150b1d6ae7) | Apr 21, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [525241657b](https://linux-hardware.org/?probe=525241657b) | Apr 20, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [07e2728dfe](https://linux-hardware.org/?probe=07e2728dfe) | Apr 20, 2023 |
| Infinix       | INBOOK X2 GEN11             | [cac51ecb89](https://linux-hardware.org/?probe=cac51ecb89) | Apr 20, 2023 |
| Infinix       | INBOOK X2 GEN11             | [7fea1a73bc](https://linux-hardware.org/?probe=7fea1a73bc) | Apr 20, 2023 |
| MSI           | GF63 Thin 9SC               | [fbed7350fc](https://linux-hardware.org/?probe=fbed7350fc) | Apr 20, 2023 |
| Timi          | A34R                        | [310e4d7b63](https://linux-hardware.org/?probe=310e4d7b63) | Apr 20, 2023 |
| Dell          | Latitude E6410              | [52ada88fb1](https://linux-hardware.org/?probe=52ada88fb1) | Apr 20, 2023 |
| MSI           | Creator Z17 A12UHST         | [1396746fba](https://linux-hardware.org/?probe=1396746fba) | Apr 20, 2023 |
| HP            | Notebook                    | [36788985ec](https://linux-hardware.org/?probe=36788985ec) | Apr 20, 2023 |
| ASUSTek       | K501LX                      | [00676747c4](https://linux-hardware.org/?probe=00676747c4) | Apr 19, 2023 |
| Dell          | Latitude E7440              | [c701c43108](https://linux-hardware.org/?probe=c701c43108) | Apr 19, 2023 |
| TUXEDO        | Book XUX7 Gen11             | [c92f90cd3b](https://linux-hardware.org/?probe=c92f90cd3b) | Apr 19, 2023 |
| Toshiba       | Satellite C55-C             | [594ceb6023](https://linux-hardware.org/?probe=594ceb6023) | Apr 19, 2023 |
| HP            | Notebook                    | [072fc2bf12](https://linux-hardware.org/?probe=072fc2bf12) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9df9b0d25d](https://linux-hardware.org/?probe=9df9b0d25d) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | [a0cf4fd00d](https://linux-hardware.org/?probe=a0cf4fd00d) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | [7ce26d7fd9](https://linux-hardware.org/?probe=7ce26d7fd9) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [b4c6c1198f](https://linux-hardware.org/?probe=b4c6c1198f) | Apr 19, 2023 |
| HP            | Pavilion dv7                | [f5c84d7a1b](https://linux-hardware.org/?probe=f5c84d7a1b) | Apr 19, 2023 |
| ASUSTek       | UX430UNR                    | [d8ed935b86](https://linux-hardware.org/?probe=d8ed935b86) | Apr 19, 2023 |
| TECNO         | MEGABOOK T1                 | [733d7d5584](https://linux-hardware.org/?probe=733d7d5584) | Apr 18, 2023 |
| HP            | Compaq Presario CQ70        | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| MSI           | GP65 Leopard 10SEK          | [3b852bad57](https://linux-hardware.org/?probe=3b852bad57) | Apr 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [e69d8250d4](https://linux-hardware.org/?probe=e69d8250d4) | Apr 18, 2023 |
| HP            | Laptop 17-cn2xxx            | [5b77cc21f4](https://linux-hardware.org/?probe=5b77cc21f4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | [0896195ea4](https://linux-hardware.org/?probe=0896195ea4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | [7105145a87](https://linux-hardware.org/?probe=7105145a87) | Apr 18, 2023 |
| Dell          | XPS 15 9500                 | [7e8eea0944](https://linux-hardware.org/?probe=7e8eea0944) | Apr 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [ec0532e3e3](https://linux-hardware.org/?probe=ec0532e3e3) | Apr 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [0dde7d44fb](https://linux-hardware.org/?probe=0dde7d44fb) | Apr 18, 2023 |
| Dell          | XPS 15 9500                 | [470d6fd3a4](https://linux-hardware.org/?probe=470d6fd3a4) | Apr 18, 2023 |
| HP            | ProBook 440 G5              | [329811ff90](https://linux-hardware.org/?probe=329811ff90) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| Sony          | VPCCW1S1E                   | [49dc80d94c](https://linux-hardware.org/?probe=49dc80d94c) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| ASUSTek       | K55A                        | [99fe712761](https://linux-hardware.org/?probe=99fe712761) | Apr 17, 2023 |
| HP            | 240 G4 Notebook PC          | [6410232c86](https://linux-hardware.org/?probe=6410232c86) | Apr 17, 2023 |
| HP            | ProBook 4730s               | [1e951f37df](https://linux-hardware.org/?probe=1e951f37df) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [877464f534](https://linux-hardware.org/?probe=877464f534) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [650deb855e](https://linux-hardware.org/?probe=650deb855e) | Apr 17, 2023 |
| Dell          | Inspiron 5559               | [945c1a2fe3](https://linux-hardware.org/?probe=945c1a2fe3) | Apr 17, 2023 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | [a83fb2552a](https://linux-hardware.org/?probe=a83fb2552a) | Apr 17, 2023 |
| Dell          | Inspiron 5559               | [a25bcc21e8](https://linux-hardware.org/?probe=a25bcc21e8) | Apr 17, 2023 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | [a2060000b4](https://linux-hardware.org/?probe=a2060000b4) | Apr 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f3a91915df](https://linux-hardware.org/?probe=f3a91915df) | Apr 17, 2023 |
| Dell          | Latitude 7420               | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| Dell          | Latitude E7440              | [6264046b14](https://linux-hardware.org/?probe=6264046b14) | Apr 17, 2023 |
| HP            | ENVY Laptop 17-cg1xxx       | [e4fda598c3](https://linux-hardware.org/?probe=e4fda598c3) | Apr 16, 2023 |
| HP            | Laptop 14-dq2xxx            | [ebfde7de62](https://linux-hardware.org/?probe=ebfde7de62) | Apr 16, 2023 |
| Acer          | Aspire V3-772               | [a44b73c5e5](https://linux-hardware.org/?probe=a44b73c5e5) | Apr 16, 2023 |
| Acer          | Aspire V3-772               | [5dec93d2ba](https://linux-hardware.org/?probe=5dec93d2ba) | Apr 16, 2023 |
| iQual         | NQ4X                        | [425ccf4057](https://linux-hardware.org/?probe=425ccf4057) | Apr 16, 2023 |
| ASUSTek       | K53BE                       | [f21e7219ce](https://linux-hardware.org/?probe=f21e7219ce) | Apr 16, 2023 |
| HP            | ProBook 450 G1              | [000e6c6702](https://linux-hardware.org/?probe=000e6c6702) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5f4a346d92](https://linux-hardware.org/?probe=5f4a346d92) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [411186569d](https://linux-hardware.org/?probe=411186569d) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d86218a8d1](https://linux-hardware.org/?probe=d86218a8d1) | Apr 16, 2023 |
| HP            | ProBook 4730s               | [be8f644cc3](https://linux-hardware.org/?probe=be8f644cc3) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f7cf140a28](https://linux-hardware.org/?probe=f7cf140a28) | Apr 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b1b447dbbf](https://linux-hardware.org/?probe=b1b447dbbf) | Apr 16, 2023 |
| Dell          | Latitude E6520              | [4cce894e16](https://linux-hardware.org/?probe=4cce894e16) | Apr 16, 2023 |
| HP            | ProBook 440 G5              | [ff2ad3337b](https://linux-hardware.org/?probe=ff2ad3337b) | Apr 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [861920db51](https://linux-hardware.org/?probe=861920db51) | Apr 15, 2023 |
| Acer          | Aspire ES1-731              | [774333b753](https://linux-hardware.org/?probe=774333b753) | Apr 15, 2023 |
| MSI           | Modern 14 B11MOU            | [fb2586255c](https://linux-hardware.org/?probe=fb2586255c) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 33233QM       | [f84da542f6](https://linux-hardware.org/?probe=f84da542f6) | Apr 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0e89a3c19b](https://linux-hardware.org/?probe=0e89a3c19b) | Apr 15, 2023 |
| MSI           | Modern 14 B11MOU            | [5be6d6af31](https://linux-hardware.org/?probe=5be6d6af31) | Apr 15, 2023 |
| ASUSTek       | UX303LN                     | [48f04b1b6e](https://linux-hardware.org/?probe=48f04b1b6e) | Apr 15, 2023 |
| Acer          | Aspire A515-55              | [18414177a2](https://linux-hardware.org/?probe=18414177a2) | Apr 15, 2023 |
| Toshiba       | Satellite L655              | [c3c64a7016](https://linux-hardware.org/?probe=c3c64a7016) | Apr 14, 2023 |
| Apple         | MacBookAir7,2               | [ed87c59a92](https://linux-hardware.org/?probe=ed87c59a92) | Apr 14, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | [a5cce02e71](https://linux-hardware.org/?probe=a5cce02e71) | Apr 14, 2023 |
| Dell          | XPS 15 7590                 | [f3248c9bca](https://linux-hardware.org/?probe=f3248c9bca) | Apr 14, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | [b87471108a](https://linux-hardware.org/?probe=b87471108a) | Apr 14, 2023 |
| Samsung       | 750XDA                      | [e447451a7a](https://linux-hardware.org/?probe=e447451a7a) | Apr 14, 2023 |
| Acer          | Aspire A515-57              | [ea0055d848](https://linux-hardware.org/?probe=ea0055d848) | Apr 14, 2023 |
| Notebook      | W65_67SH                    | [d84563301e](https://linux-hardware.org/?probe=d84563301e) | Apr 14, 2023 |
| Dell          | Inspiron 15 3511            | [6cfca82c2f](https://linux-hardware.org/?probe=6cfca82c2f) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | [6522f4e2dc](https://linux-hardware.org/?probe=6522f4e2dc) | Apr 14, 2023 |
| Clevo         | W760T/M740T/M760T           | [0dfaa8f0e8](https://linux-hardware.org/?probe=0dfaa8f0e8) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | [5a17f65715](https://linux-hardware.org/?probe=5a17f65715) | Apr 14, 2023 |
| HUAWEI        | MRG-WXX                     | [56c255e5f0](https://linux-hardware.org/?probe=56c255e5f0) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [d4de10f812](https://linux-hardware.org/?probe=d4de10f812) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7c862e338c](https://linux-hardware.org/?probe=7c862e338c) | Apr 14, 2023 |
| Lenovo        | ThinkPad X270 20HMS0T000    | [9e33b0dcc4](https://linux-hardware.org/?probe=9e33b0dcc4) | Apr 14, 2023 |
| GPU Compan... | GWTC116-2                   | [05c4b7477b](https://linux-hardware.org/?probe=05c4b7477b) | Apr 14, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [98121ef614](https://linux-hardware.org/?probe=98121ef614) | Apr 14, 2023 |
| Dell          | Latitude E6400              | [7497f0d27e](https://linux-hardware.org/?probe=7497f0d27e) | Apr 14, 2023 |
| Acer          | Nitro AN515-54              | [07a2ba2393](https://linux-hardware.org/?probe=07a2ba2393) | Apr 13, 2023 |
| Lenovo        | ThinkPad T430 2349UKM       | [c67f1476bc](https://linux-hardware.org/?probe=c67f1476bc) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b223f5fbf1](https://linux-hardware.org/?probe=b223f5fbf1) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 4291AY8       | [b2bc70473d](https://linux-hardware.org/?probe=b2bc70473d) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | [c200475e1f](https://linux-hardware.org/?probe=c200475e1f) | Apr 13, 2023 |
| Acer          | Aspire A515-54G             | [eedb55e1ba](https://linux-hardware.org/?probe=eedb55e1ba) | Apr 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [fa8b03b686](https://linux-hardware.org/?probe=fa8b03b686) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | [ae928fe177](https://linux-hardware.org/?probe=ae928fe177) | Apr 13, 2023 |
| HP            | Notebook                    | [5fc60b1d5f](https://linux-hardware.org/?probe=5fc60b1d5f) | Apr 13, 2023 |
| Acer          | Aspire A515-57G             | [42e4889a44](https://linux-hardware.org/?probe=42e4889a44) | Apr 13, 2023 |
| Acer          | Nitro AN517-55              | [82931a3c45](https://linux-hardware.org/?probe=82931a3c45) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [a8184cfc25](https://linux-hardware.org/?probe=a8184cfc25) | Apr 13, 2023 |
| Dell          | XPS L322X                   | [cbf247e5a6](https://linux-hardware.org/?probe=cbf247e5a6) | Apr 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0a09da06be](https://linux-hardware.org/?probe=0a09da06be) | Apr 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [da97aa7885](https://linux-hardware.org/?probe=da97aa7885) | Apr 13, 2023 |
| Dell          | Vostro 3550                 | [eaade18ae0](https://linux-hardware.org/?probe=eaade18ae0) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [da0c8e23ed](https://linux-hardware.org/?probe=da0c8e23ed) | Apr 13, 2023 |
| HP            | Laptop 15-db0xxx            | [296ce6a791](https://linux-hardware.org/?probe=296ce6a791) | Apr 13, 2023 |
| Toshiba       | Satellite Pro S500          | [44dca3cd92](https://linux-hardware.org/?probe=44dca3cd92) | Apr 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS29J05    | [60c50f0a10](https://linux-hardware.org/?probe=60c50f0a10) | Apr 13, 2023 |
| Acer          | Aspire A515-57G             | [73893f31b6](https://linux-hardware.org/?probe=73893f31b6) | Apr 12, 2023 |
| HP            | Pavilion TS 15              | [43b322dcf3](https://linux-hardware.org/?probe=43b322dcf3) | Apr 12, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [d809f15d99](https://linux-hardware.org/?probe=d809f15d99) | Apr 12, 2023 |
| Acer          | Aspire ES1-731              | [3ea34efd72](https://linux-hardware.org/?probe=3ea34efd72) | Apr 12, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [e75be02a84](https://linux-hardware.org/?probe=e75be02a84) | Apr 12, 2023 |
| MSI           | Prestige 14Evo B13M         | [8ded60277f](https://linux-hardware.org/?probe=8ded60277f) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [d914c2a179](https://linux-hardware.org/?probe=d914c2a179) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [5b861c968e](https://linux-hardware.org/?probe=5b861c968e) | Apr 12, 2023 |
| Apple         | MacBookPro14,1              | [11757b2c03](https://linux-hardware.org/?probe=11757b2c03) | Apr 12, 2023 |
| Acer          | TravelMate P253             | [e07f3af414](https://linux-hardware.org/?probe=e07f3af414) | Apr 12, 2023 |
| Gateway       | NE56R                       | [39a33d998b](https://linux-hardware.org/?probe=39a33d998b) | Apr 12, 2023 |
| Lenovo        | ThinkPad W541 20EF000JUS    | [4fd97924f2](https://linux-hardware.org/?probe=4fd97924f2) | Apr 12, 2023 |
| Google        | Gnawty                      | [ddb0fea339](https://linux-hardware.org/?probe=ddb0fea339) | Apr 12, 2023 |
| Dell          | Latitude 3510               | [582f6705cb](https://linux-hardware.org/?probe=582f6705cb) | Apr 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [9a592d3392](https://linux-hardware.org/?probe=9a592d3392) | Apr 11, 2023 |
| HP            | Compaq CQ58                 | [77ae8df47c](https://linux-hardware.org/?probe=77ae8df47c) | Apr 11, 2023 |
| MSI           | GP72MVR 7RFX                | [17f60a29f5](https://linux-hardware.org/?probe=17f60a29f5) | Apr 11, 2023 |
| HP            | Laptop 17-by4xxx            | [0f08555585](https://linux-hardware.org/?probe=0f08555585) | Apr 11, 2023 |
| HP            | Compaq CQ58                 | [31975ede32](https://linux-hardware.org/?probe=31975ede32) | Apr 11, 2023 |
| HP            | Laptop 17-by4xxx            | [abb34e803c](https://linux-hardware.org/?probe=abb34e803c) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | [f1999ee14e](https://linux-hardware.org/?probe=f1999ee14e) | Apr 11, 2023 |
| Dell          | XPS 15 9520                 | [5b01d0eda1](https://linux-hardware.org/?probe=5b01d0eda1) | Apr 11, 2023 |
| HP            | Pavilion (EH737UA#ABA)      | [cc8ff92529](https://linux-hardware.org/?probe=cc8ff92529) | Apr 11, 2023 |
| MSI           | GF63 Thin 9SCXR             | [3225aa17d2](https://linux-hardware.org/?probe=3225aa17d2) | Apr 11, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [5234925c5c](https://linux-hardware.org/?probe=5234925c5c) | Apr 11, 2023 |
| HP            | 250 G8 Notebook PC          | [a60609df80](https://linux-hardware.org/?probe=a60609df80) | Apr 11, 2023 |
| Lenovo        | ThinkPad W541 20EGS03800    | [4be9d98954](https://linux-hardware.org/?probe=4be9d98954) | Apr 11, 2023 |
| Acer          | Aspire A515-57              | [f577606375](https://linux-hardware.org/?probe=f577606375) | Apr 11, 2023 |
| Dell          | G5 5590                     | [9c1f2f432b](https://linux-hardware.org/?probe=9c1f2f432b) | Apr 11, 2023 |
| BESSTAR Te... | X400                        | [6b1587e21d](https://linux-hardware.org/?probe=6b1587e21d) | Apr 11, 2023 |
| Dell          | Inspiron 5567               | [f12e2a4eb4](https://linux-hardware.org/?probe=f12e2a4eb4) | Apr 11, 2023 |
| MSI           | Prestige 14Evo B13M         | [a3967e84ad](https://linux-hardware.org/?probe=a3967e84ad) | Apr 11, 2023 |
| Acer          | Aspire E5-471               | [dbcbf972e5](https://linux-hardware.org/?probe=dbcbf972e5) | Apr 11, 2023 |
| MSI           | Creator 15 A11UE            | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [7852e88a19](https://linux-hardware.org/?probe=7852e88a19) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [40c7ac46e2](https://linux-hardware.org/?probe=40c7ac46e2) | Apr 10, 2023 |
| ASUSTek       | K55VD                       | [110fdee9b2](https://linux-hardware.org/?probe=110fdee9b2) | Apr 10, 2023 |
| TUXEDO        | Book XP1511                 | [5f5ee54a58](https://linux-hardware.org/?probe=5f5ee54a58) | Apr 10, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [704f5bcf78](https://linux-hardware.org/?probe=704f5bcf78) | Apr 10, 2023 |
| HP            | Pavilion dv7                | [09416f091f](https://linux-hardware.org/?probe=09416f091f) | Apr 10, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [93f3fa59af](https://linux-hardware.org/?probe=93f3fa59af) | Apr 09, 2023 |
| HP            | Pavilion dv7                | [1e1b8b9ee8](https://linux-hardware.org/?probe=1e1b8b9ee8) | Apr 09, 2023 |
| HP            | Pavilion dv7                | [de8b7df38c](https://linux-hardware.org/?probe=de8b7df38c) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe939f268b](https://linux-hardware.org/?probe=fe939f268b) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [955a648772](https://linux-hardware.org/?probe=955a648772) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [02bbb66fe9](https://linux-hardware.org/?probe=02bbb66fe9) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c82c56c81e](https://linux-hardware.org/?probe=c82c56c81e) | Apr 09, 2023 |
| Dell          | Latitude 7275               | [d1a55f8f55](https://linux-hardware.org/?probe=d1a55f8f55) | Apr 09, 2023 |
| Acer          | Aspire A515-57              | [e04fc7e8e8](https://linux-hardware.org/?probe=e04fc7e8e8) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [b1c4404d58](https://linux-hardware.org/?probe=b1c4404d58) | Apr 09, 2023 |
| HONOR         | NMH-WCX9                    | [51c8f59aeb](https://linux-hardware.org/?probe=51c8f59aeb) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | [37849126d4](https://linux-hardware.org/?probe=37849126d4) | Apr 08, 2023 |
| ICL           | RAYbook Si1512              | [1dd919f7ff](https://linux-hardware.org/?probe=1dd919f7ff) | Apr 08, 2023 |
| HP            | EliteBook 8560p             | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [0477a89130](https://linux-hardware.org/?probe=0477a89130) | Apr 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [52a7fed8d7](https://linux-hardware.org/?probe=52a7fed8d7) | Apr 07, 2023 |
| Notebook      | N141CU                      | [8648ddb323](https://linux-hardware.org/?probe=8648ddb323) | Apr 07, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [b0f67ad60e](https://linux-hardware.org/?probe=b0f67ad60e) | Apr 07, 2023 |
| Dell          | G3 3500                     | [cae0e09f03](https://linux-hardware.org/?probe=cae0e09f03) | Apr 07, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [868d29e288](https://linux-hardware.org/?probe=868d29e288) | Apr 07, 2023 |
| Dell          | G3 3500                     | [9f77f9158a](https://linux-hardware.org/?probe=9f77f9158a) | Apr 07, 2023 |
| Notebook      | NL5xNU                      | [3d65b6c046](https://linux-hardware.org/?probe=3d65b6c046) | Apr 07, 2023 |
| Dell          | Latitude E5550              | [b0e2c2e0d5](https://linux-hardware.org/?probe=b0e2c2e0d5) | Apr 07, 2023 |
| Dell          | Vostro 5391                 | [aaa8e31af8](https://linux-hardware.org/?probe=aaa8e31af8) | Apr 07, 2023 |
| HP            | ProBook 6360b               | [bfa6c44b14](https://linux-hardware.org/?probe=bfa6c44b14) | Apr 07, 2023 |
| HP            | Laptop 14-dk0xxx            | [fb1a3cbdb9](https://linux-hardware.org/?probe=fb1a3cbdb9) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9e7e969310](https://linux-hardware.org/?probe=9e7e969310) | Apr 06, 2023 |
| HUAWEI        | RLEF-XX                     | [874157891b](https://linux-hardware.org/?probe=874157891b) | Apr 06, 2023 |
| HP            | Laptop 15-da1xxx            | [84c8a107d4](https://linux-hardware.org/?probe=84c8a107d4) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b220308aa1](https://linux-hardware.org/?probe=b220308aa1) | Apr 06, 2023 |
| HP            | 250 G6 Notebook PC          | [2537675a96](https://linux-hardware.org/?probe=2537675a96) | Apr 06, 2023 |
| Lenovo        | ThinkPad T480s 20L70029U... | [dac43b8971](https://linux-hardware.org/?probe=dac43b8971) | Apr 06, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ff65115a04](https://linux-hardware.org/?probe=ff65115a04) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [3d59062866](https://linux-hardware.org/?probe=3d59062866) | Apr 06, 2023 |
| Dell          | XPS 15 9570                 | [3c1e15ab5c](https://linux-hardware.org/?probe=3c1e15ab5c) | Apr 06, 2023 |
| Notebook      | P15SM                       | [0e5e8189a3](https://linux-hardware.org/?probe=0e5e8189a3) | Apr 06, 2023 |
| Acer          | Swift SF314-59              | [d12cbc4044](https://linux-hardware.org/?probe=d12cbc4044) | Apr 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [e4f64facb0](https://linux-hardware.org/?probe=e4f64facb0) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | [d9d2e73619](https://linux-hardware.org/?probe=d9d2e73619) | Apr 05, 2023 |
| HP            | EliteBook 840 G5            | [0d68e199a9](https://linux-hardware.org/?probe=0d68e199a9) | Apr 05, 2023 |
| Fujitsu       | LIFEBOOK E751               | [0bdc444de8](https://linux-hardware.org/?probe=0bdc444de8) | Apr 05, 2023 |
| MSI           | Katana GF66 12UE            | [5114a5bd7a](https://linux-hardware.org/?probe=5114a5bd7a) | Apr 05, 2023 |
| Acer          | E1-510                      | [44b40ae5ac](https://linux-hardware.org/?probe=44b40ae5ac) | Apr 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBC... | [f4dd5b1a73](https://linux-hardware.org/?probe=f4dd5b1a73) | Apr 05, 2023 |
| Dell          | Inspiron 5567               | [59e664cdc6](https://linux-hardware.org/?probe=59e664cdc6) | Apr 05, 2023 |
| HP            | 250 G6 Notebook PC          | [f3d81b9880](https://linux-hardware.org/?probe=f3d81b9880) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [405f73f1fd](https://linux-hardware.org/?probe=405f73f1fd) | Apr 05, 2023 |
| Dell          | Inspiron 5567               | [2e9904d939](https://linux-hardware.org/?probe=2e9904d939) | Apr 05, 2023 |
| Dell          | Latitude 5591               | [aa2f4e4208](https://linux-hardware.org/?probe=aa2f4e4208) | Apr 05, 2023 |
| Dell          | Precision 7670              | [b5e95f0d21](https://linux-hardware.org/?probe=b5e95f0d21) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [a7cb3cf668](https://linux-hardware.org/?probe=a7cb3cf668) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [16f81f8254](https://linux-hardware.org/?probe=16f81f8254) | Apr 05, 2023 |
| MSI           | Creator Z16 A12UET          | [240fb67b93](https://linux-hardware.org/?probe=240fb67b93) | Apr 05, 2023 |
| Dynabook      | TECRA A50-J                 | [a73b280bf3](https://linux-hardware.org/?probe=a73b280bf3) | Apr 04, 2023 |
| HP            | Notebook                    | [2566e7b2a0](https://linux-hardware.org/?probe=2566e7b2a0) | Apr 04, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [fa9fe4337a](https://linux-hardware.org/?probe=fa9fe4337a) | Apr 04, 2023 |
| MSI           | GF63 Thin 10SCXR            | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [9f33f20fc4](https://linux-hardware.org/?probe=9f33f20fc4) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [ec6a09a6ba](https://linux-hardware.org/?probe=ec6a09a6ba) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [81400b8912](https://linux-hardware.org/?probe=81400b8912) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | G500 20236                  | [4bbe18183a](https://linux-hardware.org/?probe=4bbe18183a) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [9da88b2a33](https://linux-hardware.org/?probe=9da88b2a33) | Apr 04, 2023 |
| ASUSTek       | GL553VD                     | [1978d77ba2](https://linux-hardware.org/?probe=1978d77ba2) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [a55f69e324](https://linux-hardware.org/?probe=a55f69e324) | Apr 03, 2023 |
| Dell          | Latitude 5530               | [802248e232](https://linux-hardware.org/?probe=802248e232) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [93fa18f474](https://linux-hardware.org/?probe=93fa18f474) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [915c34d052](https://linux-hardware.org/?probe=915c34d052) | Apr 03, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [953b450863](https://linux-hardware.org/?probe=953b450863) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [71a388a292](https://linux-hardware.org/?probe=71a388a292) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [28652ebe9b](https://linux-hardware.org/?probe=28652ebe9b) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK E752               | [4c5c75cfcb](https://linux-hardware.org/?probe=4c5c75cfcb) | Apr 03, 2023 |
| Apple         | MacBookPro11,5              | [80b6ae92c9](https://linux-hardware.org/?probe=80b6ae92c9) | Apr 03, 2023 |
| Dell          | Latitude 5521               | [35be2ed98c](https://linux-hardware.org/?probe=35be2ed98c) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | [ef04e5d464](https://linux-hardware.org/?probe=ef04e5d464) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | [f9eb684250](https://linux-hardware.org/?probe=f9eb684250) | Apr 03, 2023 |
| Apple         | MacBookPro5,5               | [c674243118](https://linux-hardware.org/?probe=c674243118) | Apr 03, 2023 |
| Apple         | MacBookPro5,5               | [dca6973952](https://linux-hardware.org/?probe=dca6973952) | Apr 03, 2023 |
| HP            | Stream Notebook             | [27610e0a39](https://linux-hardware.org/?probe=27610e0a39) | Apr 03, 2023 |
| Gateway       | NE56R                       | [ffa6b1d3f3](https://linux-hardware.org/?probe=ffa6b1d3f3) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [1c15668c5d](https://linux-hardware.org/?probe=1c15668c5d) | Apr 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Acer          | Aspire A515-47              | [d6b7e9a498](https://linux-hardware.org/?probe=d6b7e9a498) | Apr 03, 2023 |
| Acer          | Aspire A515-47              | [e9d49346e1](https://linux-hardware.org/?probe=e9d49346e1) | Apr 03, 2023 |
| Lenovo        | ThinkPad Edge 0578A21       | [52a6bcc2f4](https://linux-hardware.org/?probe=52a6bcc2f4) | Apr 03, 2023 |
| Lenovo        | ThinkPad Edge 0578A21       | [26803a939c](https://linux-hardware.org/?probe=26803a939c) | Apr 03, 2023 |
| Toshiba       | Satellite L850              | [2635da1e14](https://linux-hardware.org/?probe=2635da1e14) | Apr 03, 2023 |
| ASUSTek       | TP300LJ                     | [7da5aab332](https://linux-hardware.org/?probe=7da5aab332) | Apr 02, 2023 |
| HUAWEI        | HVY-WXX9                    | [63d38ddebf](https://linux-hardware.org/?probe=63d38ddebf) | Apr 02, 2023 |
| Sony          | SVE1713Q1EB                 | [0ffe86aecd](https://linux-hardware.org/?probe=0ffe86aecd) | Apr 02, 2023 |
| Dell          | Inspiron 3593               | [498aad682e](https://linux-hardware.org/?probe=498aad682e) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [892ffd1727](https://linux-hardware.org/?probe=892ffd1727) | Apr 02, 2023 |
| Lenovo        | ThinkPad Edge E545 20B20... | [fddacb7078](https://linux-hardware.org/?probe=fddacb7078) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e3078a63c3](https://linux-hardware.org/?probe=e3078a63c3) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1c8c26f5c0](https://linux-hardware.org/?probe=1c8c26f5c0) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ac5393930b](https://linux-hardware.org/?probe=ac5393930b) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | [f7f0d77f00](https://linux-hardware.org/?probe=f7f0d77f00) | Apr 02, 2023 |
| Lenovo        | IdeaPad N580                | [d41c216646](https://linux-hardware.org/?probe=d41c216646) | Apr 02, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [3c3a2da37a](https://linux-hardware.org/?probe=3c3a2da37a) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Lenovo        | B50-30 80ES                 | [a971008720](https://linux-hardware.org/?probe=a971008720) | Apr 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [676156b5df](https://linux-hardware.org/?probe=676156b5df) | Apr 02, 2023 |
| HP            | 250 G3                      | [2030ba57b9](https://linux-hardware.org/?probe=2030ba57b9) | Apr 02, 2023 |
| Acer          | Aspire 5517                 | [a61aee0407](https://linux-hardware.org/?probe=a61aee0407) | Apr 02, 2023 |
| Timi          | TM1604                      | [48e0f0529d](https://linux-hardware.org/?probe=48e0f0529d) | Apr 02, 2023 |
| Timi          | TM1604                      | [d621eb4471](https://linux-hardware.org/?probe=d621eb4471) | Apr 02, 2023 |
| Apple         | MacBook4,1                  | [dda3791c20](https://linux-hardware.org/?probe=dda3791c20) | Apr 01, 2023 |
| Lenovo        | V15-ADA 82C7                | [eeffd94725](https://linux-hardware.org/?probe=eeffd94725) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0941828bd0](https://linux-hardware.org/?probe=0941828bd0) | Apr 01, 2023 |
| Dell          | Latitude 7410               | [c0ff135386](https://linux-hardware.org/?probe=c0ff135386) | Apr 01, 2023 |
| HUAWEI        | HKD-WXX                     | [c0827316e3](https://linux-hardware.org/?probe=c0827316e3) | Apr 01, 2023 |
| Lenovo        | ThinkPad L560 20F2S1AJ00    | [8987605dde](https://linux-hardware.org/?probe=8987605dde) | Apr 01, 2023 |
| Haier         | A1410EM                     | [f772f1b9eb](https://linux-hardware.org/?probe=f772f1b9eb) | Apr 01, 2023 |
| Haier         | A1410EM                     | [709a07dd3c](https://linux-hardware.org/?probe=709a07dd3c) | Apr 01, 2023 |
| HUAWEI        | MACHC-WAX9                  | [3494157f4b](https://linux-hardware.org/?probe=3494157f4b) | Apr 01, 2023 |
| Dell          | Latitude 5530               | [e4688e2ef8](https://linux-hardware.org/?probe=e4688e2ef8) | Apr 01, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| Lenovo        | V310-14ISK 80SX             | [cd6dee4651](https://linux-hardware.org/?probe=cd6dee4651) | Apr 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [4191279e7e](https://linux-hardware.org/?probe=4191279e7e) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [db058df07b](https://linux-hardware.org/?probe=db058df07b) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [3691be13e8](https://linux-hardware.org/?probe=3691be13e8) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 20RA004YUS     | [36b592e607](https://linux-hardware.org/?probe=36b592e607) | Apr 01, 2023 |
| Samsung       | R530/R730/R540              | [714ed0f007](https://linux-hardware.org/?probe=714ed0f007) | Apr 01, 2023 |
| Itautec       | Infoway w7535               | [48a539f108](https://linux-hardware.org/?probe=48a539f108) | Apr 01, 2023 |
| Samsung       | 950XED                      | [c3b37a213a](https://linux-hardware.org/?probe=c3b37a213a) | Mar 31, 2023 |
| Acer          | Extensa 215-31              | [b1601e6747](https://linux-hardware.org/?probe=b1601e6747) | Mar 31, 2023 |
| Dell          | Vostro V131                 | [53538c2ae9](https://linux-hardware.org/?probe=53538c2ae9) | Mar 31, 2023 |
| ASUSTek       | K53SD                       | [81d03c3707](https://linux-hardware.org/?probe=81d03c3707) | Mar 31, 2023 |
| Lenovo        | ThinkPad E14 20RA0016IX     | [685f18f5b3](https://linux-hardware.org/?probe=685f18f5b3) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| Lenovo        | ThinkPad Edge E545 20B20... | [c2061eeeb8](https://linux-hardware.org/?probe=c2061eeeb8) | Mar 31, 2023 |
| Lenovo        | ThinkPad Edge E545 20B20... | [9a866f03fd](https://linux-hardware.org/?probe=9a866f03fd) | Mar 31, 2023 |
| Lenovo        | ThinkPad X270 20HMS0T000    | [702223a4b1](https://linux-hardware.org/?probe=702223a4b1) | Mar 31, 2023 |
| EVOO          | EVC156-1                    | [8e665ae8b2](https://linux-hardware.org/?probe=8e665ae8b2) | Mar 31, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [fe51f2c62f](https://linux-hardware.org/?probe=fe51f2c62f) | Mar 31, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [d7f3354ce9](https://linux-hardware.org/?probe=d7f3354ce9) | Mar 31, 2023 |
| Toshiba       | Satellite Pro S500          | [b2e60d9170](https://linux-hardware.org/?probe=b2e60d9170) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [c6bbbbb7d8](https://linux-hardware.org/?probe=c6bbbbb7d8) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| Medion        | E15407                      | [b863362865](https://linux-hardware.org/?probe=b863362865) | Mar 30, 2023 |
| Medion        | E15407                      | [641091a85d](https://linux-hardware.org/?probe=641091a85d) | Mar 30, 2023 |
| Apple         | MacBookAir7,2               | [d9cbbe0a35](https://linux-hardware.org/?probe=d9cbbe0a35) | Mar 30, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [1dc323a9e9](https://linux-hardware.org/?probe=1dc323a9e9) | Mar 30, 2023 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [95a77f6dcc](https://linux-hardware.org/?probe=95a77f6dcc) | Mar 30, 2023 |
| Apple         | MacBookPro10,2              | [2f56ac98c1](https://linux-hardware.org/?probe=2f56ac98c1) | Mar 30, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [31d333ecc9](https://linux-hardware.org/?probe=31d333ecc9) | Mar 30, 2023 |
| Dell          | Vostro 5402                 | [27b9c84cbe](https://linux-hardware.org/?probe=27b9c84cbe) | Mar 30, 2023 |
| Lenovo        | Yoga 510-14ISK 80UK         | [722c1e9d68](https://linux-hardware.org/?probe=722c1e9d68) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [252d340923](https://linux-hardware.org/?probe=252d340923) | Mar 30, 2023 |
| Dell          | Latitude 3490               | [16d4f0954b](https://linux-hardware.org/?probe=16d4f0954b) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [da1e07f122](https://linux-hardware.org/?probe=da1e07f122) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [492d575f31](https://linux-hardware.org/?probe=492d575f31) | Mar 30, 2023 |
| HP            | ProBook 450 G5              | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Lenovo        | N22 80S6                    | [c6cbeeb984](https://linux-hardware.org/?probe=c6cbeeb984) | Mar 30, 2023 |
| Acer          | Aspire A514-54              | [94da64753b](https://linux-hardware.org/?probe=94da64753b) | Mar 30, 2023 |
| Acer          | Aspire 8943G                | [e1d172011e](https://linux-hardware.org/?probe=e1d172011e) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Apple         | MacBookAir9,1               | [1fe20bdfcb](https://linux-hardware.org/?probe=1fe20bdfcb) | Mar 30, 2023 |
| Notebook      | N650DU                      | [e8ec3c6462](https://linux-hardware.org/?probe=e8ec3c6462) | Mar 30, 2023 |
| Dell          | Inspiron 5566               | [7b53b4da78](https://linux-hardware.org/?probe=7b53b4da78) | Mar 29, 2023 |
| Dell          | Latitude E6530              | [eb7392d1ae](https://linux-hardware.org/?probe=eb7392d1ae) | Mar 29, 2023 |
| Medion        | P8614                       | [a66fe7042e](https://linux-hardware.org/?probe=a66fe7042e) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [803a180064](https://linux-hardware.org/?probe=803a180064) | Mar 29, 2023 |
| Dell          | Inspiron 5767               | [1c80487906](https://linux-hardware.org/?probe=1c80487906) | Mar 29, 2023 |
| Acer          | Extensa 215-23              | [bf5730d468](https://linux-hardware.org/?probe=bf5730d468) | Mar 29, 2023 |
| ASUSTek       | X751LJ                      | [cf5d71e2b3](https://linux-hardware.org/?probe=cf5d71e2b3) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [f33059ab6b](https://linux-hardware.org/?probe=f33059ab6b) | Mar 29, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [40b3e68058](https://linux-hardware.org/?probe=40b3e68058) | Mar 29, 2023 |
| Timi          | TM1701                      | [16ca4bcb7f](https://linux-hardware.org/?probe=16ca4bcb7f) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [bfa850ddad](https://linux-hardware.org/?probe=bfa850ddad) | Mar 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [31d94ffb5f](https://linux-hardware.org/?probe=31d94ffb5f) | Mar 29, 2023 |
| Dell          | Vostro 15 3515              | [7b4a51d5e3](https://linux-hardware.org/?probe=7b4a51d5e3) | Mar 29, 2023 |
| Dell          | Inspiron 7520               | [8258074853](https://linux-hardware.org/?probe=8258074853) | Mar 28, 2023 |
| Google        | Caroline                    | [80f01f2a87](https://linux-hardware.org/?probe=80f01f2a87) | Mar 28, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [25cc7bfca2](https://linux-hardware.org/?probe=25cc7bfca2) | Mar 28, 2023 |
| HP            | Pavilion g6                 | [c5b99ffdb0](https://linux-hardware.org/?probe=c5b99ffdb0) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| Acer          | TravelMate P215-52          | [b6184e813b](https://linux-hardware.org/?probe=b6184e813b) | Mar 28, 2023 |
| Dell          | G15 5511                    | [7f15a1e2c7](https://linux-hardware.org/?probe=7f15a1e2c7) | Mar 28, 2023 |
| Dell          | Precision 5540              | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | ThinkPad E14 20RA004YUS     | [18226d4ded](https://linux-hardware.org/?probe=18226d4ded) | Mar 28, 2023 |
| HP            | ProBook 450 G7              | [8b27d78a17](https://linux-hardware.org/?probe=8b27d78a17) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [856b789461](https://linux-hardware.org/?probe=856b789461) | Mar 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [577947c9d3](https://linux-hardware.org/?probe=577947c9d3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE004EU... | [988731ac8d](https://linux-hardware.org/?probe=988731ac8d) | Mar 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE004EU... | [8406000835](https://linux-hardware.org/?probe=8406000835) | Mar 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4c2dd89a20](https://linux-hardware.org/?probe=4c2dd89a20) | Mar 28, 2023 |
| HP            | Compaq 610                  | [dc9383200e](https://linux-hardware.org/?probe=dc9383200e) | Mar 28, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [8921171c40](https://linux-hardware.org/?probe=8921171c40) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| ASUSTek       | N53SV                       | [77aa77b2a3](https://linux-hardware.org/?probe=77aa77b2a3) | Mar 28, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [7a9cf507e6](https://linux-hardware.org/?probe=7a9cf507e6) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HP            | Laptop 14s-fq2xxx           | [8b64ddb550](https://linux-hardware.org/?probe=8b64ddb550) | Mar 27, 2023 |
| Acer          | Extensa 2530                | [e39fe56d67](https://linux-hardware.org/?probe=e39fe56d67) | Mar 27, 2023 |
| Dell          | Inspiron 13-5378            | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| HUAWEI        | NBD-WXX9                    | [e7788fd2a4](https://linux-hardware.org/?probe=e7788fd2a4) | Mar 27, 2023 |
| HUAWEI        | NBD-WXX9                    | [d723ff0fa9](https://linux-hardware.org/?probe=d723ff0fa9) | Mar 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1U20... | [99ea485cee](https://linux-hardware.org/?probe=99ea485cee) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [2f96abf16a](https://linux-hardware.org/?probe=2f96abf16a) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [07caea9176](https://linux-hardware.org/?probe=07caea9176) | Mar 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Dell          | Precision 7530              | [d5687ef764](https://linux-hardware.org/?probe=d5687ef764) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [d484c5e138](https://linux-hardware.org/?probe=d484c5e138) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Acer          | Aspire 4820TG               | [e634227889](https://linux-hardware.org/?probe=e634227889) | Mar 27, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [629579e7f2](https://linux-hardware.org/?probe=629579e7f2) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Dell          | Precision 7670              | [eece926391](https://linux-hardware.org/?probe=eece926391) | Mar 27, 2023 |
| HP            | EliteBook 2570p             | [d5ba09feb1](https://linux-hardware.org/?probe=d5ba09feb1) | Mar 27, 2023 |
| Dell          | Precision 7670              | [5b8f0590ec](https://linux-hardware.org/?probe=5b8f0590ec) | Mar 27, 2023 |
| Dell          | Latitude E5570              | [350e781679](https://linux-hardware.org/?probe=350e781679) | Mar 27, 2023 |
| Fujitsu       | LIFEBOOK E736               | [03df3679d3](https://linux-hardware.org/?probe=03df3679d3) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | [bef27b5a10](https://linux-hardware.org/?probe=bef27b5a10) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | [daac2899b2](https://linux-hardware.org/?probe=daac2899b2) | Mar 26, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | [9022b333bd](https://linux-hardware.org/?probe=9022b333bd) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | [f7d3c52f58](https://linux-hardware.org/?probe=f7d3c52f58) | Mar 26, 2023 |
| HUAWEI        | RLEF-XX                     | [b860e76ead](https://linux-hardware.org/?probe=b860e76ead) | Mar 26, 2023 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [6f3481adc0](https://linux-hardware.org/?probe=6f3481adc0) | Mar 26, 2023 |
| Dell          | XPS 15 7590                 | [aeec5e2588](https://linux-hardware.org/?probe=aeec5e2588) | Mar 26, 2023 |
| Apple         | MacBookPro16,2              | [cf7ab8adb4](https://linux-hardware.org/?probe=cf7ab8adb4) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Positivo      | Smash2                      | [b61791c478](https://linux-hardware.org/?probe=b61791c478) | Mar 26, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [946f550eb7](https://linux-hardware.org/?probe=946f550eb7) | Mar 26, 2023 |
| Acer          | V5-131                      | [f35bd55401](https://linux-hardware.org/?probe=f35bd55401) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| MSI           | Creator Z16 A11UET          | [0133ab37af](https://linux-hardware.org/?probe=0133ab37af) | Mar 26, 2023 |
| Dell          | XPS 13 9305                 | [5b29fbd6ac](https://linux-hardware.org/?probe=5b29fbd6ac) | Mar 26, 2023 |
| Lenovo        | ThinkPad T430 4237ZC7       | [845a2ed117](https://linux-hardware.org/?probe=845a2ed117) | Mar 26, 2023 |
| Dell          | Latitude E6430              | [912e5e8577](https://linux-hardware.org/?probe=912e5e8577) | Mar 26, 2023 |
| Dell          | Latitude E6430              | [237dabb566](https://linux-hardware.org/?probe=237dabb566) | Mar 26, 2023 |
| Sony          | SVF14215CXB                 | [624af23eb4](https://linux-hardware.org/?probe=624af23eb4) | Mar 26, 2023 |
| Lenovo        | G510 20238                  | [f406bad420](https://linux-hardware.org/?probe=f406bad420) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| HP            | G42                         | [f1b5695907](https://linux-hardware.org/?probe=f1b5695907) | Mar 25, 2023 |
| Lenovo        | ThinkPad W520 4282PQ7       | [ff42aa158f](https://linux-hardware.org/?probe=ff42aa158f) | Mar 25, 2023 |
| Timi          | TM1701                      | [f5dfd4628e](https://linux-hardware.org/?probe=f5dfd4628e) | Mar 25, 2023 |
| HP            | ProBook 650 G1              | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| Acer          | Aspire ES1-731              | [927cc86995](https://linux-hardware.org/?probe=927cc86995) | Mar 25, 2023 |
| Acer          | Aspire E1-731               | [667456015e](https://linux-hardware.org/?probe=667456015e) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| Lenovo        | ThinkPad X201 3680W81       | [02821ba817](https://linux-hardware.org/?probe=02821ba817) | Mar 25, 2023 |
| Timi          | TM1701                      | [17e055a118](https://linux-hardware.org/?probe=17e055a118) | Mar 25, 2023 |
| Dell          | XPS 13 9380                 | [72bf3db096](https://linux-hardware.org/?probe=72bf3db096) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [22aa7f3036](https://linux-hardware.org/?probe=22aa7f3036) | Mar 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [0bfaf1252f](https://linux-hardware.org/?probe=0bfaf1252f) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e09dc41124](https://linux-hardware.org/?probe=e09dc41124) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Getac         | B300-H                      | [28a9b0b0c7](https://linux-hardware.org/?probe=28a9b0b0c7) | Mar 25, 2023 |
| Dell          | Latitude E7450              | [7154586794](https://linux-hardware.org/?probe=7154586794) | Mar 25, 2023 |
| Dell          | Inspiron N5110              | [f8fc6c74da](https://linux-hardware.org/?probe=f8fc6c74da) | Mar 25, 2023 |
| Acer          | Aspire 4740                 | [c4e47e53dc](https://linux-hardware.org/?probe=c4e47e53dc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9e45f992a1](https://linux-hardware.org/?probe=9e45f992a1) | Mar 25, 2023 |
| Dell          | Vostro 5581                 | [d2ebb46bea](https://linux-hardware.org/?probe=d2ebb46bea) | Mar 25, 2023 |
| Apple         | MacBook4,1                  | [7ade2b1d1a](https://linux-hardware.org/?probe=7ade2b1d1a) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| Dell          | XPS 13 9350                 | [d1ba8cb8e9](https://linux-hardware.org/?probe=d1ba8cb8e9) | Mar 24, 2023 |
| Dell          | Precision 3510              | [2ea0671f5d](https://linux-hardware.org/?probe=2ea0671f5d) | Mar 24, 2023 |
| HP            | Pavilion 11 x360 PC         | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [bc6baa37ef](https://linux-hardware.org/?probe=bc6baa37ef) | Mar 24, 2023 |
| MSI           | Creator Z17 A12UHST         | [47814b01b6](https://linux-hardware.org/?probe=47814b01b6) | Mar 24, 2023 |
| HP            | ProBook 5330m               | [6844efa448](https://linux-hardware.org/?probe=6844efa448) | Mar 24, 2023 |
| HP            | Laptop 15-dw0xxx            | [299c20969c](https://linux-hardware.org/?probe=299c20969c) | Mar 24, 2023 |
| Dell          | XPS 13 9305                 | [c7e354ffe3](https://linux-hardware.org/?probe=c7e354ffe3) | Mar 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [7dfb215d39](https://linux-hardware.org/?probe=7dfb215d39) | Mar 24, 2023 |
| HP            | Laptop 15s-du2xxx           | [882f1dbee1](https://linux-hardware.org/?probe=882f1dbee1) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e14a63a1e4](https://linux-hardware.org/?probe=e14a63a1e4) | Mar 24, 2023 |
| Dell          | Vostro 3500                 | [a375452089](https://linux-hardware.org/?probe=a375452089) | Mar 23, 2023 |
| Dell          | Latitude 5420               | [9e55d83acd](https://linux-hardware.org/?probe=9e55d83acd) | Mar 23, 2023 |
| Dell          | Latitude D630               | [95a44067f1](https://linux-hardware.org/?probe=95a44067f1) | Mar 23, 2023 |
| ASUSTek       | X75A1                       | [a4b87d85da](https://linux-hardware.org/?probe=a4b87d85da) | Mar 23, 2023 |
| ASUSTek       | X75A1                       | [654683dd2b](https://linux-hardware.org/?probe=654683dd2b) | Mar 23, 2023 |
| Dell          | Latitude D630               | [45e100abf8](https://linux-hardware.org/?probe=45e100abf8) | Mar 23, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [d40284254e](https://linux-hardware.org/?probe=d40284254e) | Mar 23, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [26521abccd](https://linux-hardware.org/?probe=26521abccd) | Mar 23, 2023 |
| Dell          | XPS 15 9520                 | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Toshiba       | Satellite U845W             | [27e67eea9d](https://linux-hardware.org/?probe=27e67eea9d) | Mar 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c17f20a679](https://linux-hardware.org/?probe=c17f20a679) | Mar 23, 2023 |
| Notebook      | W510LU                      | [076125acc3](https://linux-hardware.org/?probe=076125acc3) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d956770153](https://linux-hardware.org/?probe=d956770153) | Mar 23, 2023 |
| HP            | ProBook 650 G5              | [028c91d344](https://linux-hardware.org/?probe=028c91d344) | Mar 23, 2023 |
| HUAWEI        | BOD-WXX9                    | [088494906d](https://linux-hardware.org/?probe=088494906d) | Mar 23, 2023 |
| Dell          | XPS 15 9510                 | [e6db3c2c26](https://linux-hardware.org/?probe=e6db3c2c26) | Mar 23, 2023 |
| HONOR         | NMH-WCX9                    | [21f61b5987](https://linux-hardware.org/?probe=21f61b5987) | Mar 23, 2023 |
| Lenovo        | ThinkPad P70 20ESS2VP00     | [bb6fdb6236](https://linux-hardware.org/?probe=bb6fdb6236) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Dell          | Latitude 5400               | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Timi          | TM1613                      | [3016a40df3](https://linux-hardware.org/?probe=3016a40df3) | Mar 23, 2023 |
| Timi          | TM1613                      | [ddbc83a8d3](https://linux-hardware.org/?probe=ddbc83a8d3) | Mar 23, 2023 |
| Dell          | Latitude 5400               | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Lenovo        | ThinkPad L450 20DSA25V01    | [68b1ae2c5d](https://linux-hardware.org/?probe=68b1ae2c5d) | Mar 23, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [c91fa425a5](https://linux-hardware.org/?probe=c91fa425a5) | Mar 23, 2023 |
| Teclast       | F15Plus 2                   | [70a7bfb366](https://linux-hardware.org/?probe=70a7bfb366) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [34fd631d2b](https://linux-hardware.org/?probe=34fd631d2b) | Mar 22, 2023 |
| IGEL Techn... | M340C                       | [0a16ce19bb](https://linux-hardware.org/?probe=0a16ce19bb) | Mar 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4cbcbc3025](https://linux-hardware.org/?probe=4cbcbc3025) | Mar 22, 2023 |
| Toshiba       | Satellite U845W             | [65958975b3](https://linux-hardware.org/?probe=65958975b3) | Mar 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [ba101f37d0](https://linux-hardware.org/?probe=ba101f37d0) | Mar 22, 2023 |
| Sony          | VGN-AR51M                   | [ae55922eae](https://linux-hardware.org/?probe=ae55922eae) | Mar 22, 2023 |
| HP            | Laptop 17-by2xxx            | [e8c5422a4f](https://linux-hardware.org/?probe=e8c5422a4f) | Mar 22, 2023 |
| Toshiba       | Satellite Pro S500          | [2bb2519c2c](https://linux-hardware.org/?probe=2bb2519c2c) | Mar 21, 2023 |
| Toshiba       | Satellite Pro S500          | [a45c7086e5](https://linux-hardware.org/?probe=a45c7086e5) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [8606a64427](https://linux-hardware.org/?probe=8606a64427) | Mar 21, 2023 |
| ASUSTek       | VivoBook E14 E402WAS        | [95154b40cc](https://linux-hardware.org/?probe=95154b40cc) | Mar 21, 2023 |
| HUAWEI        | CREM-WXX9                   | [64a63f42bf](https://linux-hardware.org/?probe=64a63f42bf) | Mar 21, 2023 |
| Dell          | G15 5510                    | [3ddfc82bcd](https://linux-hardware.org/?probe=3ddfc82bcd) | Mar 21, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3a8692d4cf](https://linux-hardware.org/?probe=3a8692d4cf) | Mar 21, 2023 |
| MSI           | GF63 Thin 10SCSR            | [45610ce6bf](https://linux-hardware.org/?probe=45610ce6bf) | Mar 21, 2023 |
| Avell High... | A62 LIV                     | [14dab05208](https://linux-hardware.org/?probe=14dab05208) | Mar 21, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [42629ad13b](https://linux-hardware.org/?probe=42629ad13b) | Mar 21, 2023 |
| ASUSTek       | GL553VD                     | [ea7e302020](https://linux-hardware.org/?probe=ea7e302020) | Mar 21, 2023 |
| ASUSTek       | GL553VD                     | [8ed4a1e3ba](https://linux-hardware.org/?probe=8ed4a1e3ba) | Mar 21, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [c5b2997e80](https://linux-hardware.org/?probe=c5b2997e80) | Mar 21, 2023 |
| Dell          | Latitude E6520              | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| HP            | EliteBook 840 G5            | [a204a0f2c0](https://linux-hardware.org/?probe=a204a0f2c0) | Mar 21, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a8b511cdb0](https://linux-hardware.org/?probe=a8b511cdb0) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [d068d67f2d](https://linux-hardware.org/?probe=d068d67f2d) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| Framework     | Laptop                      | [a7dc7b28c9](https://linux-hardware.org/?probe=a7dc7b28c9) | Mar 21, 2023 |
| Dell          | Inspiron 7520               | [330f307e06](https://linux-hardware.org/?probe=330f307e06) | Mar 21, 2023 |
| Tactus        | GeoBook 140                 | [5efd6f0674](https://linux-hardware.org/?probe=5efd6f0674) | Mar 20, 2023 |
| HP            | EliteBook 8440p             | [580c62b3b8](https://linux-hardware.org/?probe=580c62b3b8) | Mar 20, 2023 |
| IGEL Techn... | M340C                       | [2785bf290e](https://linux-hardware.org/?probe=2785bf290e) | Mar 20, 2023 |
| Dell          | Inspiron 3442               | [33137a049e](https://linux-hardware.org/?probe=33137a049e) | Mar 20, 2023 |
| HP            | 250 G4                      | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| Dell          | Latitude 7420               | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c9c86f1e79](https://linux-hardware.org/?probe=c9c86f1e79) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| HP            | Pavilion dm4                | [7983ee084c](https://linux-hardware.org/?probe=7983ee084c) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Sony          | VPCEH3N6E                   | [9de8a9a50a](https://linux-hardware.org/?probe=9de8a9a50a) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Dell          | Latitude 5520               | [4153e72c6b](https://linux-hardware.org/?probe=4153e72c6b) | Mar 19, 2023 |
| Acer          | Swift SF514-53T             | [9d37ace881](https://linux-hardware.org/?probe=9d37ace881) | Mar 19, 2023 |
| Acer          | Swift SF514-53T             | [93ce0e9d73](https://linux-hardware.org/?probe=93ce0e9d73) | Mar 19, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [95ae633abb](https://linux-hardware.org/?probe=95ae633abb) | Mar 19, 2023 |
| Acer          | Aspire V3-772               | [64b17e8d2c](https://linux-hardware.org/?probe=64b17e8d2c) | Mar 19, 2023 |
| Teclast       | F15Plus 2                   | [17558890e2](https://linux-hardware.org/?probe=17558890e2) | Mar 19, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [54025a10f5](https://linux-hardware.org/?probe=54025a10f5) | Mar 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [92ae74e13d](https://linux-hardware.org/?probe=92ae74e13d) | Mar 19, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [dfc02dad7e](https://linux-hardware.org/?probe=dfc02dad7e) | Mar 19, 2023 |
| ASUSTek       | X550VX                      | [dcc37300fd](https://linux-hardware.org/?probe=dcc37300fd) | Mar 19, 2023 |
| Dell          | Latitude E7470              | [d9108aaeab](https://linux-hardware.org/?probe=d9108aaeab) | Mar 19, 2023 |
| Dell          | Inspiron 7520               | [f587cfd0f1](https://linux-hardware.org/?probe=f587cfd0f1) | Mar 19, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [f60325ef42](https://linux-hardware.org/?probe=f60325ef42) | Mar 19, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [dc8d19f73a](https://linux-hardware.org/?probe=dc8d19f73a) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [f5c5712df1](https://linux-hardware.org/?probe=f5c5712df1) | Mar 18, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [5a11bc39d5](https://linux-hardware.org/?probe=5a11bc39d5) | Mar 18, 2023 |
| Lenovo        | ThinkPad Edge E330 33541... | [4f0ddac461](https://linux-hardware.org/?probe=4f0ddac461) | Mar 18, 2023 |
| Schenker      | VISION 14                   | [85200e20d8](https://linux-hardware.org/?probe=85200e20d8) | Mar 18, 2023 |
| HP            | Laptop 15-db0xxx            | [bb43e46d71](https://linux-hardware.org/?probe=bb43e46d71) | Mar 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [8c8a87616c](https://linux-hardware.org/?probe=8c8a87616c) | Mar 18, 2023 |
| Apple         | MacBookPro9,2               | [e996669ec1](https://linux-hardware.org/?probe=e996669ec1) | Mar 18, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [2a6ded1018](https://linux-hardware.org/?probe=2a6ded1018) | Mar 18, 2023 |
| Acer          | Aspire 8730                 | [bc63e0d2c1](https://linux-hardware.org/?probe=bc63e0d2c1) | Mar 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [837ed83646](https://linux-hardware.org/?probe=837ed83646) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | [9c677b7a7b](https://linux-hardware.org/?probe=9c677b7a7b) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | [703cc66d3e](https://linux-hardware.org/?probe=703cc66d3e) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [928a8fe84e](https://linux-hardware.org/?probe=928a8fe84e) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [00dc1c3b6e](https://linux-hardware.org/?probe=00dc1c3b6e) | Mar 18, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [5ede1a1bf2](https://linux-hardware.org/?probe=5ede1a1bf2) | Mar 18, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [d7acdc8bf3](https://linux-hardware.org/?probe=d7acdc8bf3) | Mar 18, 2023 |
| Lenovo        | ThinkPad Edge E335 33556... | [463dac90ba](https://linux-hardware.org/?probe=463dac90ba) | Mar 18, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [c145898fae](https://linux-hardware.org/?probe=c145898fae) | Mar 17, 2023 |
| Lenovo        | V580c 20160                 | [b7f2837ccd](https://linux-hardware.org/?probe=b7f2837ccd) | Mar 17, 2023 |
| Notebook      | N150CU                      | [284a367641](https://linux-hardware.org/?probe=284a367641) | Mar 17, 2023 |
| HONOR         | HYM-WXX                     | [279e932275](https://linux-hardware.org/?probe=279e932275) | Mar 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0006GE     | [6364c78054](https://linux-hardware.org/?probe=6364c78054) | Mar 17, 2023 |
| Acer          | Aspire V7-482PG             | [9ba6bdc643](https://linux-hardware.org/?probe=9ba6bdc643) | Mar 17, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [293fe8b4ab](https://linux-hardware.org/?probe=293fe8b4ab) | Mar 17, 2023 |
| Medion        | GUARDIAN X10                | [f30ef18641](https://linux-hardware.org/?probe=f30ef18641) | Mar 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [51ec4d252f](https://linux-hardware.org/?probe=51ec4d252f) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [353d82cd61](https://linux-hardware.org/?probe=353d82cd61) | Mar 17, 2023 |
| Dell          | Latitude 7310               | [6b5de5fe3c](https://linux-hardware.org/?probe=6b5de5fe3c) | Mar 17, 2023 |
| Medion        | GUARDIAN X10                | [76798fdb55](https://linux-hardware.org/?probe=76798fdb55) | Mar 17, 2023 |
| MSI           | GP62 6QE                    | [3db109542c](https://linux-hardware.org/?probe=3db109542c) | Mar 17, 2023 |
| Dell          | Inspiron 3593               | [d983398383](https://linux-hardware.org/?probe=d983398383) | Mar 17, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [70812fb9c8](https://linux-hardware.org/?probe=70812fb9c8) | Mar 17, 2023 |
| Dell          | Inspiron 7520               | [1cedff3f90](https://linux-hardware.org/?probe=1cedff3f90) | Mar 17, 2023 |
| HP            | ZBook Studio G3             | [db6c4ae697](https://linux-hardware.org/?probe=db6c4ae697) | Mar 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S88M0... | [2ad89b7995](https://linux-hardware.org/?probe=2ad89b7995) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [6a1e908693](https://linux-hardware.org/?probe=6a1e908693) | Mar 16, 2023 |
| Dell          | Inspiron 14 5425            | [1128b14745](https://linux-hardware.org/?probe=1128b14745) | Mar 16, 2023 |
| HP            | EliteBook 1050 G1           | [6dcfa134ac](https://linux-hardware.org/?probe=6dcfa134ac) | Mar 16, 2023 |
| Unknown       | Unknown                     | [7a44108d05](https://linux-hardware.org/?probe=7a44108d05) | Mar 16, 2023 |
| Dell          | Latitude 5511               | [7444a8c723](https://linux-hardware.org/?probe=7444a8c723) | Mar 16, 2023 |
| HUAWEI        | NDZ-WXX9                    | [82687f32c9](https://linux-hardware.org/?probe=82687f32c9) | Mar 16, 2023 |
| Lenovo        | Flex 2-15                   | [6bea7b508e](https://linux-hardware.org/?probe=6bea7b508e) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [ef98a330e6](https://linux-hardware.org/?probe=ef98a330e6) | Mar 16, 2023 |
| Acer          | TravelMate P215-53          | [3fc3403dfd](https://linux-hardware.org/?probe=3fc3403dfd) | Mar 16, 2023 |
| Dell          | Inspiron 5579               | [2854150d6e](https://linux-hardware.org/?probe=2854150d6e) | Mar 16, 2023 |
| Dell          | Latitude 7280               | [d793cea3ba](https://linux-hardware.org/?probe=d793cea3ba) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [c54f2ca880](https://linux-hardware.org/?probe=c54f2ca880) | Mar 16, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [a01912ff82](https://linux-hardware.org/?probe=a01912ff82) | Mar 15, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [7af2ed2e31](https://linux-hardware.org/?probe=7af2ed2e31) | Mar 15, 2023 |
| HP            | Laptop 15-bs0xx             | [be76f3a0a3](https://linux-hardware.org/?probe=be76f3a0a3) | Mar 15, 2023 |
| Sony          | SVE17137CXB                 | [acf08014f7](https://linux-hardware.org/?probe=acf08014f7) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [c6c5f88e4b](https://linux-hardware.org/?probe=c6c5f88e4b) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [3c632e35c3](https://linux-hardware.org/?probe=3c632e35c3) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30-B               | [06db6fa9b3](https://linux-hardware.org/?probe=06db6fa9b3) | Mar 15, 2023 |
| Apple         | MacBookPro15,2              | [26ab8620d9](https://linux-hardware.org/?probe=26ab8620d9) | Mar 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c454542aaa](https://linux-hardware.org/?probe=c454542aaa) | Mar 15, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3028035868](https://linux-hardware.org/?probe=3028035868) | Mar 15, 2023 |
| Apple         | MacBookPro9,2               | [6640fe0d6f](https://linux-hardware.org/?probe=6640fe0d6f) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [f5a6ecdae0](https://linux-hardware.org/?probe=f5a6ecdae0) | Mar 15, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [890aa0e0d3](https://linux-hardware.org/?probe=890aa0e0d3) | Mar 15, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [d28c932c13](https://linux-hardware.org/?probe=d28c932c13) | Mar 15, 2023 |
| HP            | ZBook 15                    | [c34b49ba46](https://linux-hardware.org/?probe=c34b49ba46) | Mar 15, 2023 |
| Dell          | Vostro 3500                 | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Toshiba       | Satellite Pro S500          | [0065669867](https://linux-hardware.org/?probe=0065669867) | Mar 15, 2023 |
| Acer          | Swift SF314-42              | [67500cfa07](https://linux-hardware.org/?probe=67500cfa07) | Mar 15, 2023 |
| HP            | EliteBook 2570p             | [1c6475f7da](https://linux-hardware.org/?probe=1c6475f7da) | Mar 15, 2023 |
| Apple         | MacBookPro9,2               | [9b01d90367](https://linux-hardware.org/?probe=9b01d90367) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fcb50f0e4f](https://linux-hardware.org/?probe=fcb50f0e4f) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fc7320db54](https://linux-hardware.org/?probe=fc7320db54) | Mar 14, 2023 |
| HP            | Laptop 17-ca0xxx            | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| Lenovo        | ThinkPad P53 20QN002LUS     | [77022cf63c](https://linux-hardware.org/?probe=77022cf63c) | Mar 14, 2023 |
| Acer          | Aspire 5100                 | [5142811e2b](https://linux-hardware.org/?probe=5142811e2b) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [b3d9dfdb16](https://linux-hardware.org/?probe=b3d9dfdb16) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0f6370d7f7](https://linux-hardware.org/?probe=0f6370d7f7) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [31ac227c9f](https://linux-hardware.org/?probe=31ac227c9f) | Mar 14, 2023 |
| Lenovo        | ThinkPad T520 4242BC5       | [328620a2d3](https://linux-hardware.org/?probe=328620a2d3) | Mar 14, 2023 |
| Dell          | Inspiron 3583               | [9eaa09faf0](https://linux-hardware.org/?probe=9eaa09faf0) | Mar 14, 2023 |
| Samsung       | 750XDA                      | [c6b76619bf](https://linux-hardware.org/?probe=c6b76619bf) | Mar 14, 2023 |
| Dell          | Precision 5570              | [f0d98798a2](https://linux-hardware.org/?probe=f0d98798a2) | Mar 14, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [f3dd1409f6](https://linux-hardware.org/?probe=f3dd1409f6) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | [b428d6d41a](https://linux-hardware.org/?probe=b428d6d41a) | Mar 14, 2023 |
| Dell          | G3 3579                     | [e548fa074e](https://linux-hardware.org/?probe=e548fa074e) | Mar 14, 2023 |
| HP            | EliteBook 8470p             | [ff14bacd9a](https://linux-hardware.org/?probe=ff14bacd9a) | Mar 14, 2023 |
| Gateway       | M-1634U                     | [2c8551dd63](https://linux-hardware.org/?probe=2c8551dd63) | Mar 14, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [04fcb41bb8](https://linux-hardware.org/?probe=04fcb41bb8) | Mar 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [9332803ca3](https://linux-hardware.org/?probe=9332803ca3) | Mar 13, 2023 |
| HP            | ZBook 15 G2                 | [e262c9e978](https://linux-hardware.org/?probe=e262c9e978) | Mar 13, 2023 |
| Dell          | G15 5510                    | [fa6a50c541](https://linux-hardware.org/?probe=fa6a50c541) | Mar 13, 2023 |
| Dell          | Precision 7560              | [0b0c4e4b1c](https://linux-hardware.org/?probe=0b0c4e4b1c) | Mar 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [4c6424525e](https://linux-hardware.org/?probe=4c6424525e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bc375a2ddd](https://linux-hardware.org/?probe=bc375a2ddd) | Mar 13, 2023 |
| HP            | ZBook Studio G4             | [2e04fad893](https://linux-hardware.org/?probe=2e04fad893) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| HP            | Pavilion Notebook           | [34e902c00b](https://linux-hardware.org/?probe=34e902c00b) | Mar 13, 2023 |
| Jumper        | EZbook                      | [a6114c514f](https://linux-hardware.org/?probe=a6114c514f) | Mar 13, 2023 |
| Dell          | Latitude E5440              | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| HP            | Pavilion dm1                | [9ed7d80abb](https://linux-hardware.org/?probe=9ed7d80abb) | Mar 13, 2023 |
| Acer          | Nitro AN517-52              | [43c96b4e3e](https://linux-hardware.org/?probe=43c96b4e3e) | Mar 13, 2023 |
| Dell          | Latitude E7470              | [09bef8e5cd](https://linux-hardware.org/?probe=09bef8e5cd) | Mar 13, 2023 |
| ASUSTek       | X202EV                      | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| Lenovo        | 3000 N500 423353U           | [240375d7f3](https://linux-hardware.org/?probe=240375d7f3) | Mar 12, 2023 |
| OEGStone      | W240EU/W250EUQ/W270EUQ      | [45ea3c4094](https://linux-hardware.org/?probe=45ea3c4094) | Mar 12, 2023 |
| Intel         | STCK1A8LFC H67494-302       | [bbce56dcee](https://linux-hardware.org/?probe=bbce56dcee) | Mar 12, 2023 |
| HP            | Pavilion dv7                | [66f70aa8f4](https://linux-hardware.org/?probe=66f70aa8f4) | Mar 12, 2023 |
| Toshiba       | Satellite Pro L500          | [303f47547b](https://linux-hardware.org/?probe=303f47547b) | Mar 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [f1749d153b](https://linux-hardware.org/?probe=f1749d153b) | Mar 12, 2023 |
| Dell          | Inspiron 3593               | [ee9887a6a5](https://linux-hardware.org/?probe=ee9887a6a5) | Mar 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [eb987f6db2](https://linux-hardware.org/?probe=eb987f6db2) | Mar 12, 2023 |
| HP            | Laptop 15s-du0xxx           | [8c91461d71](https://linux-hardware.org/?probe=8c91461d71) | Mar 12, 2023 |
| ASUSTek       | X751MA                      | [f697401630](https://linux-hardware.org/?probe=f697401630) | Mar 12, 2023 |
| Acer          | Aspire 8930                 | [7434247d21](https://linux-hardware.org/?probe=7434247d21) | Mar 12, 2023 |
| Gigabyte      | AORUS 17G XC                | [fb998b9957](https://linux-hardware.org/?probe=fb998b9957) | Mar 12, 2023 |
| Google        | Droid                       | [b2a41c71ac](https://linux-hardware.org/?probe=b2a41c71ac) | Mar 12, 2023 |
| ASUSTek       | K501UW                      | [322b5bf476](https://linux-hardware.org/?probe=322b5bf476) | Mar 12, 2023 |
| Samsung       | 550XDA                      | [c42ead0ecf](https://linux-hardware.org/?probe=c42ead0ecf) | Mar 12, 2023 |
| Toshiba       | Satellite L735              | [0c5b1ebe0a](https://linux-hardware.org/?probe=0c5b1ebe0a) | Mar 11, 2023 |
| Toshiba       | Satellite L735              | [5371ec61c1](https://linux-hardware.org/?probe=5371ec61c1) | Mar 11, 2023 |
| Positivo      | Q464B                       | [513b08857c](https://linux-hardware.org/?probe=513b08857c) | Mar 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f91bf005b0](https://linux-hardware.org/?probe=f91bf005b0) | Mar 11, 2023 |
| ASUSTek       | K56CB                       | [b9690b513d](https://linux-hardware.org/?probe=b9690b513d) | Mar 11, 2023 |
| HP            | EliteBook 840 G2            | [40bda215a2](https://linux-hardware.org/?probe=40bda215a2) | Mar 11, 2023 |
| HP            | EliteBook 840 G4            | [c4792e57b9](https://linux-hardware.org/?probe=c4792e57b9) | Mar 11, 2023 |
| Infinix       | INBOOK X2 PLUS              | [62b4169c3e](https://linux-hardware.org/?probe=62b4169c3e) | Mar 11, 2023 |
| Apple         | MacBookPro15,2              | [b6dc707f97](https://linux-hardware.org/?probe=b6dc707f97) | Mar 11, 2023 |
| VALE          | Notebook Classic C140       | [4e25d5eb76](https://linux-hardware.org/?probe=4e25d5eb76) | Mar 11, 2023 |
| Dell          | G15 Special Edition 5521    | [f6b2a6bfe0](https://linux-hardware.org/?probe=f6b2a6bfe0) | Mar 11, 2023 |
| Dell          | G15 Special Edition 5521    | [9fab787ede](https://linux-hardware.org/?probe=9fab787ede) | Mar 11, 2023 |
| HP            | Laptop 17-ca0xxx            | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| HP            | 250 G6 Notebook PC          | [d173735b81](https://linux-hardware.org/?probe=d173735b81) | Mar 11, 2023 |
| HP            | Laptop 15s-du0xxx           | [36133f02b8](https://linux-hardware.org/?probe=36133f02b8) | Mar 11, 2023 |
| ASUSTek       | UX430UAR                    | [a2b1839fd1](https://linux-hardware.org/?probe=a2b1839fd1) | Mar 11, 2023 |
| Acer          | Aspire A515-51G             | [607171cb69](https://linux-hardware.org/?probe=607171cb69) | Mar 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [87779bfdea](https://linux-hardware.org/?probe=87779bfdea) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [3823c10f89](https://linux-hardware.org/?probe=3823c10f89) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS55Q1... | [302abad9dc](https://linux-hardware.org/?probe=302abad9dc) | Mar 11, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [c45a0f2220](https://linux-hardware.org/?probe=c45a0f2220) | Mar 11, 2023 |
| Star Labs     | StarBook                    | [04d0c2826a](https://linux-hardware.org/?probe=04d0c2826a) | Mar 11, 2023 |
| IGEL Techn... | M340C                       | [878b5f0965](https://linux-hardware.org/?probe=878b5f0965) | Mar 11, 2023 |
| Acer          | Aspire A515-55              | [037961f7a1](https://linux-hardware.org/?probe=037961f7a1) | Mar 11, 2023 |
| Apple         | MacBookPro9,2               | [2d0a8398ee](https://linux-hardware.org/?probe=2d0a8398ee) | Mar 11, 2023 |
| Google        | Ampton                      | [641b7d64fc](https://linux-hardware.org/?probe=641b7d64fc) | Mar 10, 2023 |
| ASUSTek       | K52Je                       | [f964ad4a66](https://linux-hardware.org/?probe=f964ad4a66) | Mar 10, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e770c2f24c](https://linux-hardware.org/?probe=e770c2f24c) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [96e374345a](https://linux-hardware.org/?probe=96e374345a) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5f8598cfd](https://linux-hardware.org/?probe=b5f8598cfd) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ffcc55bb14](https://linux-hardware.org/?probe=ffcc55bb14) | Mar 10, 2023 |
| HP            | EliteBook 8470p             | [1c2bbbfbae](https://linux-hardware.org/?probe=1c2bbbfbae) | Mar 10, 2023 |
| Notebook      | N150CU                      | [3b891fe927](https://linux-hardware.org/?probe=3b891fe927) | Mar 10, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [99e2790846](https://linux-hardware.org/?probe=99e2790846) | Mar 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [53649dddb6](https://linux-hardware.org/?probe=53649dddb6) | Mar 10, 2023 |
| Notebook      | N150CU                      | [b7fbec9613](https://linux-hardware.org/?probe=b7fbec9613) | Mar 10, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [a62abba552](https://linux-hardware.org/?probe=a62abba552) | Mar 10, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | [18fba066d8](https://linux-hardware.org/?probe=18fba066d8) | Mar 10, 2023 |
| HP            | EliteBook 840 G3            | [41bf4fb877](https://linux-hardware.org/?probe=41bf4fb877) | Mar 10, 2023 |
| HP            | Laptop 17-by3xxx            | [4528da8a2c](https://linux-hardware.org/?probe=4528da8a2c) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | [4f689d1291](https://linux-hardware.org/?probe=4f689d1291) | Mar 10, 2023 |
| HP            | ProBook 4330s               | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [2d99e047c9](https://linux-hardware.org/?probe=2d99e047c9) | Mar 10, 2023 |
| HP            | ProBook 430 G4              | [9c3d2e652a](https://linux-hardware.org/?probe=9c3d2e652a) | Mar 09, 2023 |
| Toshiba       | TECRA Z40-A                 | [43c7df46f9](https://linux-hardware.org/?probe=43c7df46f9) | Mar 09, 2023 |
| Acer          | Aspire ES1-531              | [bf2d3857fd](https://linux-hardware.org/?probe=bf2d3857fd) | Mar 09, 2023 |
| HP            | ProBook 430 G2              | [21595cd5ed](https://linux-hardware.org/?probe=21595cd5ed) | Mar 09, 2023 |
| Lenovo        | ThinkPad X201 36806V4       | [1921dc6d6b](https://linux-hardware.org/?probe=1921dc6d6b) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [026c39773a](https://linux-hardware.org/?probe=026c39773a) | Mar 09, 2023 |
| HP            | Presario CQ57               | [87bbd773ac](https://linux-hardware.org/?probe=87bbd773ac) | Mar 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7236313c80](https://linux-hardware.org/?probe=7236313c80) | Mar 09, 2023 |
| HP            | EliteBook 8470p             | [4b88826804](https://linux-hardware.org/?probe=4b88826804) | Mar 09, 2023 |
| ASUSTek       | X580VD                      | [8cb2ac6f38](https://linux-hardware.org/?probe=8cb2ac6f38) | Mar 09, 2023 |
| Lenovo        | ThinkPad Edge E330 3354D... | [b741a79767](https://linux-hardware.org/?probe=b741a79767) | Mar 09, 2023 |
| HP            | 250 G7 Notebook PC          | [149a0b40c6](https://linux-hardware.org/?probe=149a0b40c6) | Mar 09, 2023 |
| HP            | Laptop 15s-du3xxx           | [bdfaf09cd0](https://linux-hardware.org/?probe=bdfaf09cd0) | Mar 09, 2023 |
| Toshiba       | Satellite L855              | [3832889508](https://linux-hardware.org/?probe=3832889508) | Mar 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [36987c495a](https://linux-hardware.org/?probe=36987c495a) | Mar 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMA... | [f15426402c](https://linux-hardware.org/?probe=f15426402c) | Mar 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [fdc32a6871](https://linux-hardware.org/?probe=fdc32a6871) | Mar 09, 2023 |
| Unknown       | M-140BI5                    | [bb3776e45d](https://linux-hardware.org/?probe=bb3776e45d) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | [39805e4790](https://linux-hardware.org/?probe=39805e4790) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | [d12e99f5d2](https://linux-hardware.org/?probe=d12e99f5d2) | Mar 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [da38390eca](https://linux-hardware.org/?probe=da38390eca) | Mar 09, 2023 |
| ASUSTek       | UX410UAR                    | [4fa93928b1](https://linux-hardware.org/?probe=4fa93928b1) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| Fujitsu       | LIFEBOOK E734               | [a4e6e8e566](https://linux-hardware.org/?probe=a4e6e8e566) | Mar 08, 2023 |
| HP            | Laptop 15s-eq1xxx           | [fc2ee93757](https://linux-hardware.org/?probe=fc2ee93757) | Mar 08, 2023 |
| HP            | Laptop 15s-eq1xxx           | [e1ce357347](https://linux-hardware.org/?probe=e1ce357347) | Mar 08, 2023 |
| Apple         | MacBookPro15,1              | [af6a474ce9](https://linux-hardware.org/?probe=af6a474ce9) | Mar 08, 2023 |
| HP            | Presario CQ57               | [ffa117dde1](https://linux-hardware.org/?probe=ffa117dde1) | Mar 08, 2023 |
| HP            | Pavilion g7                 | [c5c1815bc8](https://linux-hardware.org/?probe=c5c1815bc8) | Mar 08, 2023 |
| ASUSTek       | X705UAR                     | [21ea5828e3](https://linux-hardware.org/?probe=21ea5828e3) | Mar 08, 2023 |
| Samsung       | 550XDA                      | [65093a6cf5](https://linux-hardware.org/?probe=65093a6cf5) | Mar 08, 2023 |
| Entroware     | Apollo                      | [d1576010b3](https://linux-hardware.org/?probe=d1576010b3) | Mar 08, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [2756d8312f](https://linux-hardware.org/?probe=2756d8312f) | Mar 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [3c5ca39c55](https://linux-hardware.org/?probe=3c5ca39c55) | Mar 08, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3087a03cb5](https://linux-hardware.org/?probe=3087a03cb5) | Mar 08, 2023 |
| Lenovo        | ThinkPad P73 20QSS1M700     | [f97fd31dd0](https://linux-hardware.org/?probe=f97fd31dd0) | Mar 08, 2023 |
| Intel         | Raptor Lake Client Platf... | [f52d925104](https://linux-hardware.org/?probe=f52d925104) | Mar 08, 2023 |
| ADVAN         | 1405                        | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Toshiba       | Satellite P755              | [091eec0edf](https://linux-hardware.org/?probe=091eec0edf) | Mar 08, 2023 |
| Dell          | XPS 13 9380                 | [1edca5142c](https://linux-hardware.org/?probe=1edca5142c) | Mar 07, 2023 |
| Acer          | Swift SFX14-51G             | [54d0c16597](https://linux-hardware.org/?probe=54d0c16597) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | [faaa24cfbf](https://linux-hardware.org/?probe=faaa24cfbf) | Mar 07, 2023 |
| MSI           | GL73 9SD                    | [0913746f16](https://linux-hardware.org/?probe=0913746f16) | Mar 07, 2023 |
| Apple         | MacBookPro9,2               | [9d9396bbfe](https://linux-hardware.org/?probe=9d9396bbfe) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| Dell          | Latitude E5530 non-vPro     | [a490496acc](https://linux-hardware.org/?probe=a490496acc) | Mar 07, 2023 |
| Fujitsu       | CELSIUS H780                | [7080d07525](https://linux-hardware.org/?probe=7080d07525) | Mar 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [85701c7290](https://linux-hardware.org/?probe=85701c7290) | Mar 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [48dc89b146](https://linux-hardware.org/?probe=48dc89b146) | Mar 07, 2023 |
| Dell          | Latitude E5570              | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| MSI           | Katana GF66 11UD            | [f464d5be92](https://linux-hardware.org/?probe=f464d5be92) | Mar 07, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [070c644d4f](https://linux-hardware.org/?probe=070c644d4f) | Mar 07, 2023 |
| Acer          | Nitro AN517-52              | [fd6cb5c68a](https://linux-hardware.org/?probe=fd6cb5c68a) | Mar 07, 2023 |
| Dell          | Inspiron N5010              | [16d683966c](https://linux-hardware.org/?probe=16d683966c) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | [fe3f99601c](https://linux-hardware.org/?probe=fe3f99601c) | Mar 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [5c33d1feca](https://linux-hardware.org/?probe=5c33d1feca) | Mar 07, 2023 |
| LG Electro... | A530-U.BE54P1               | [c0260c82db](https://linux-hardware.org/?probe=c0260c82db) | Mar 07, 2023 |
| Acer          | Aspire 8943G                | [914975f33e](https://linux-hardware.org/?probe=914975f33e) | Mar 06, 2023 |
| Dell          | XPS 13 9310                 | [5abae1d66c](https://linux-hardware.org/?probe=5abae1d66c) | Mar 06, 2023 |
| HP            | ProBook 450 G6              | [b27b730e8f](https://linux-hardware.org/?probe=b27b730e8f) | Mar 06, 2023 |
| HP            | Presario CQ57               | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| Dell          | Latitude 5400               | [9e2592768b](https://linux-hardware.org/?probe=9e2592768b) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7fb36218d9](https://linux-hardware.org/?probe=7fb36218d9) | Mar 06, 2023 |
| Dell          | Latitude 7420               | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| HP            | G72                         | [64009d0874](https://linux-hardware.org/?probe=64009d0874) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e682158c7f](https://linux-hardware.org/?probe=e682158c7f) | Mar 06, 2023 |
| HONOR         | HYM-WXX                     | [f9f277d226](https://linux-hardware.org/?probe=f9f277d226) | Mar 06, 2023 |
| HP            | ProBook 430 G5              | [aaebada0ca](https://linux-hardware.org/?probe=aaebada0ca) | Mar 06, 2023 |
| Dell          | Latitude 7420               | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [8961f32cc5](https://linux-hardware.org/?probe=8961f32cc5) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [ddeeba335b](https://linux-hardware.org/?probe=ddeeba335b) | Mar 06, 2023 |
| ASUSTek       | K501UW                      | [9a61fd62b3](https://linux-hardware.org/?probe=9a61fd62b3) | Mar 05, 2023 |
| Sony          | SVE1513I4E                  | [76d0570787](https://linux-hardware.org/?probe=76d0570787) | Mar 05, 2023 |
| Lenovo        | ThinkPad X240 20AMA1KEIX    | [addfa0676d](https://linux-hardware.org/?probe=addfa0676d) | Mar 05, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [d1a37d82cb](https://linux-hardware.org/?probe=d1a37d82cb) | Mar 05, 2023 |
| HUAWEI        | MACHC-WAX9                  | [53b112adac](https://linux-hardware.org/?probe=53b112adac) | Mar 05, 2023 |
| Acer          | Aspire 5750G                | [1c918f0aa3](https://linux-hardware.org/?probe=1c918f0aa3) | Mar 05, 2023 |
| Avell High... | A70 MOB                     | [79d3147035](https://linux-hardware.org/?probe=79d3147035) | Mar 05, 2023 |
| Lenovo        | G50-80 80R0                 | [6d4a93e1d8](https://linux-hardware.org/?probe=6d4a93e1d8) | Mar 05, 2023 |
| Avell High... | A70 MOB                     | [38bf7fda89](https://linux-hardware.org/?probe=38bf7fda89) | Mar 05, 2023 |
| Lenovo        | G505s 20255                 | [b338e704d9](https://linux-hardware.org/?probe=b338e704d9) | Mar 05, 2023 |
| Lenovo        | G50-80 80R0                 | [5e640d57d8](https://linux-hardware.org/?probe=5e640d57d8) | Mar 05, 2023 |
| Apple         | MacBookPro9,2               | [64d9894f5e](https://linux-hardware.org/?probe=64d9894f5e) | Mar 05, 2023 |
| Lenovo        | G50-80 80L0                 | [6e4cec1477](https://linux-hardware.org/?probe=6e4cec1477) | Mar 05, 2023 |
| Acer          | Aspire A315-51              | [4f87025cfe](https://linux-hardware.org/?probe=4f87025cfe) | Mar 05, 2023 |
| Acer          | Predator PH315-52           | [d95904900e](https://linux-hardware.org/?probe=d95904900e) | Mar 05, 2023 |
| Acer          | Swift SFX16-52G             | [fb45390054](https://linux-hardware.org/?probe=fb45390054) | Mar 05, 2023 |
| Acer          | Swift SFX16-52G             | [b86acec192](https://linux-hardware.org/?probe=b86acec192) | Mar 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [8b36c984f8](https://linux-hardware.org/?probe=8b36c984f8) | Mar 05, 2023 |
| LG Electro... | R580-K.APC4BE1              | [9cac5bdcfc](https://linux-hardware.org/?probe=9cac5bdcfc) | Mar 05, 2023 |
| HP            | Laptop 14-dq2xxx            | [1a46276700](https://linux-hardware.org/?probe=1a46276700) | Mar 05, 2023 |
| MSI           | PS42 8RB                    | [effde33b49](https://linux-hardware.org/?probe=effde33b49) | Mar 05, 2023 |
| Apple         | MacBookPro16,2              | [9897b46cbd](https://linux-hardware.org/?probe=9897b46cbd) | Mar 05, 2023 |
| Acer          | Predator PH315-52           | [ec79844b81](https://linux-hardware.org/?probe=ec79844b81) | Mar 05, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [51aacc46ce](https://linux-hardware.org/?probe=51aacc46ce) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [0f0f44b0ee](https://linux-hardware.org/?probe=0f0f44b0ee) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [c112aacdb6](https://linux-hardware.org/?probe=c112aacdb6) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [ccd91fb0c7](https://linux-hardware.org/?probe=ccd91fb0c7) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [3c5d0610bb](https://linux-hardware.org/?probe=3c5d0610bb) | Mar 05, 2023 |
| Acer          | TravelMate 7730             | [86db818e06](https://linux-hardware.org/?probe=86db818e06) | Mar 05, 2023 |
| MSI           | GS70 2QE                    | [3c8e62e276](https://linux-hardware.org/?probe=3c8e62e276) | Mar 04, 2023 |
| Sony          | SVE1713Q1EB                 | [27268e9025](https://linux-hardware.org/?probe=27268e9025) | Mar 04, 2023 |
| Notebook      | N150CU                      | [99f9fb1cb3](https://linux-hardware.org/?probe=99f9fb1cb3) | Mar 04, 2023 |
| Acer          | Aspire A515-47              | [3b1c7f5e26](https://linux-hardware.org/?probe=3b1c7f5e26) | Mar 04, 2023 |
| HP            | 15                          | [0efd9be7ae](https://linux-hardware.org/?probe=0efd9be7ae) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | [5c059744df](https://linux-hardware.org/?probe=5c059744df) | Mar 04, 2023 |
| HP            | 15                          | [b8a33a3d73](https://linux-hardware.org/?probe=b8a33a3d73) | Mar 04, 2023 |
| HP            | 250 G4                      | [3912b0e13e](https://linux-hardware.org/?probe=3912b0e13e) | Mar 04, 2023 |
| Acer          | Aspire A515-57T             | [0407d35133](https://linux-hardware.org/?probe=0407d35133) | Mar 04, 2023 |
| Apple         | MacBookPro10,1              | [7b7aa513b8](https://linux-hardware.org/?probe=7b7aa513b8) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2a93373173](https://linux-hardware.org/?probe=2a93373173) | Mar 04, 2023 |
| HP            | ProBook 430 G4              | [4ee8ecac35](https://linux-hardware.org/?probe=4ee8ecac35) | Mar 04, 2023 |
| HP            | EliteBook 840 G5            | [948a77b264](https://linux-hardware.org/?probe=948a77b264) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5871fdcf26](https://linux-hardware.org/?probe=5871fdcf26) | Mar 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [afe8ef7318](https://linux-hardware.org/?probe=afe8ef7318) | Mar 04, 2023 |
| HP            | ProBook 430 G4              | [91ad7a5414](https://linux-hardware.org/?probe=91ad7a5414) | Mar 04, 2023 |
| HP            | G72                         | [a094ef43f1](https://linux-hardware.org/?probe=a094ef43f1) | Mar 04, 2023 |
| HP            | EliteBook 840 G5            | [f245db2b9a](https://linux-hardware.org/?probe=f245db2b9a) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [a987f40464](https://linux-hardware.org/?probe=a987f40464) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cd1e0a746](https://linux-hardware.org/?probe=6cd1e0a746) | Mar 04, 2023 |
| Dell          | Inspiron 16 7610            | [1121d93a65](https://linux-hardware.org/?probe=1121d93a65) | Mar 04, 2023 |
| Dell          | Latitude 5300               | [a77b29e10d](https://linux-hardware.org/?probe=a77b29e10d) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Presario CQ56               | [683be42a73](https://linux-hardware.org/?probe=683be42a73) | Mar 04, 2023 |
| HP            | ProBook 440 G7              | [ada5bd893b](https://linux-hardware.org/?probe=ada5bd893b) | Mar 04, 2023 |
| Acer          | Aspire VN7-791              | [8655b798d8](https://linux-hardware.org/?probe=8655b798d8) | Mar 04, 2023 |
| HP            | ProBook 440 G7              | [ce3d086582](https://linux-hardware.org/?probe=ce3d086582) | Mar 04, 2023 |
| Acer          | Aspire VN7-791              | [7502c125de](https://linux-hardware.org/?probe=7502c125de) | Mar 04, 2023 |
| Apple         | MacBookPro8,2               | [0b0c5a6895](https://linux-hardware.org/?probe=0b0c5a6895) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| HP            | Presario CQ61               | [912b79009b](https://linux-hardware.org/?probe=912b79009b) | Mar 04, 2023 |
| HP            | EliteBook 840 G2            | [be9b47dc08](https://linux-hardware.org/?probe=be9b47dc08) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [0228fd4ab1](https://linux-hardware.org/?probe=0228fd4ab1) | Mar 04, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | [4291caa1e6](https://linux-hardware.org/?probe=4291caa1e6) | Mar 03, 2023 |
| Apple         | MacBookPro5,4               | [fa4ef70ef1](https://linux-hardware.org/?probe=fa4ef70ef1) | Mar 03, 2023 |
| Apple         | MacBookPro5,4               | [69a6118dde](https://linux-hardware.org/?probe=69a6118dde) | Mar 03, 2023 |
| Fujitsu       | LIFEBOOK S760               | [ad73d4c8d8](https://linux-hardware.org/?probe=ad73d4c8d8) | Mar 03, 2023 |
| Apple         | MacBookPro16,1              | [5dac5286b0](https://linux-hardware.org/?probe=5dac5286b0) | Mar 03, 2023 |
| Dell          | Precision 3551              | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| HP            | Compaq 6720s                | [b422954b5a](https://linux-hardware.org/?probe=b422954b5a) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| HP            | Compaq 615                  | [a700e4efc5](https://linux-hardware.org/?probe=a700e4efc5) | Mar 03, 2023 |
| HP            | Pavilion 17                 | [de3dcf402a](https://linux-hardware.org/?probe=de3dcf402a) | Mar 03, 2023 |
| Packard Be... | EasyNote TJ65               | [18f0877a2e](https://linux-hardware.org/?probe=18f0877a2e) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [38623506fd](https://linux-hardware.org/?probe=38623506fd) | Mar 03, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-56-generic     | 420       | 8.2%    |
| 5.15.0-52-generic     | 371       | 7.24%   |
| 5.15.0-58-generic     | 345       | 6.73%   |
| 5.15.0-48-generic     | 292       | 5.7%    |
| 5.15.0-43-generic     | 285       | 5.56%   |
| 5.19.0-35-generic     | 273       | 5.33%   |
| 5.15.0-47-generic     | 253       | 4.94%   |
| 5.19.0-32-generic     | 237       | 4.63%   |
| 5.15.0-46-generic     | 233       | 4.55%   |
| 5.15.0-53-generic     | 211       | 4.12%   |
| 5.19.0-38-generic     | 193       | 3.77%   |
| 5.15.0-25-generic     | 185       | 3.61%   |
| 5.15.0-27-generic     | 175       | 3.42%   |
| 5.15.0-41-generic     | 166       | 3.24%   |
| 5.15.0-40-generic     | 156       | 3.04%   |
| 5.15.0-50-generic     | 145       | 2.83%   |
| 5.15.0-60-generic     | 126       | 2.46%   |
| 5.15.0-33-generic     | 108       | 2.11%   |
| 5.15.0-57-generic     | 103       | 2.01%   |
| 5.15.0-30-generic     | 87        | 1.7%    |
| 5.19.0-40-generic     | 78        | 1.52%   |
| 5.15.0-39-generic     | 73        | 1.42%   |
| 5.15.0-37-generic     | 57        | 1.11%   |
| 5.15.0-35-generic     | 46        | 0.9%    |
| 5.19.0-41-generic     | 27        | 0.53%   |
| 5.15.0-67-generic     | 23        | 0.45%   |
| 5.15.0-23-generic     | 21        | 0.41%   |
| 5.15.0-69-generic     | 20        | 0.39%   |
| 5.15.0-18-generic     | 13        | 0.25%   |
| 5.15.0-59-generic     | 11        | 0.21%   |
| 5.15.0-71-generic     | 10        | 0.2%    |
| 5.15.0-54-generic     | 8         | 0.16%   |
| 5.19.0-37-generic     | 7         | 0.14%   |
| 5.17.0-1019-oem       | 7         | 0.14%   |
| 5.15.0-28-generic     | 7         | 0.14%   |
| 5.15.0-17-generic     | 7         | 0.14%   |
| 6.2.11-060211-generic | 6         | 0.12%   |
| 6.0.9-060009-generic  | 6         | 0.12%   |
| 5.19.5-051905-generic | 6         | 0.12%   |
| 5.19.0-051900-generic | 6         | 0.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 3762      | 77.58%  |
| 5.19.0  | 803       | 16.56%  |
| 5.17.0  | 53        | 1.09%   |
| 5.14.0  | 27        | 0.56%   |
| 6.0.0   | 16        | 0.33%   |
| 5.13.0  | 13        | 0.27%   |
| 6.1.0   | 9         | 0.19%   |
| 5.18.0  | 9         | 0.19%   |
| 5.19.5  | 7         | 0.14%   |
| 5.17.1  | 7         | 0.14%   |
| 6.2.2   | 6         | 0.12%   |
| 6.2.11  | 6         | 0.12%   |
| 6.0.9   | 6         | 0.12%   |
| 6.2.8   | 5         | 0.1%    |
| 5.17.5  | 5         | 0.1%    |
| 6.2.0   | 4         | 0.08%   |
| 6.0.6   | 4         | 0.08%   |
| 5.13.19 | 4         | 0.08%   |
| 6.2.9   | 3         | 0.06%   |
| 6.2.10  | 3         | 0.06%   |
| 6.1.12  | 3         | 0.06%   |
| 5.4.0   | 3         | 0.06%   |
| 5.18.8  | 3         | 0.06%   |
| 5.17.9  | 3         | 0.06%   |
| 5.17.8  | 3         | 0.06%   |
| 5.17.2  | 3         | 0.06%   |
| 5.16.0  | 3         | 0.06%   |
| 6.2.7   | 2         | 0.04%   |
| 6.2.5   | 2         | 0.04%   |
| 6.2.1   | 2         | 0.04%   |
| 6.1.9   | 2         | 0.04%   |
| 6.0.7   | 2         | 0.04%   |
| 6.0.2   | 2         | 0.04%   |
| 5.19.3  | 2         | 0.04%   |
| 5.19.11 | 2         | 0.04%   |
| 5.18.6  | 2         | 0.04%   |
| 5.18.19 | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.17.6  | 2         | 0.04%   |
| 5.17.4  | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 3774      | 77.93%  |
| 5.19    | 818       | 16.89%  |
| 5.17    | 81        | 1.67%   |
| 6.0     | 34        | 0.7%    |
| 6.2     | 33        | 0.68%   |
| 5.14    | 27        | 0.56%   |
| 5.18    | 25        | 0.52%   |
| 6.1     | 20        | 0.41%   |
| 5.13    | 17        | 0.35%   |
| 5.16    | 5         | 0.1%    |
| 5.4     | 3         | 0.06%   |
| 5.11    | 2         | 0.04%   |
| 6.3     | 1         | 0.02%   |
| 6       | 1         | 0.02%   |
| 5.8     | 1         | 0.02%   |
| 5.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4744      | 99.98%  |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 4574      | 96.17%  |
| Unknown           | 94        | 1.98%   |
| X-Cinnamon        | 30        | 0.63%   |
| GNOME Flashback   | 25        | 0.53%   |
| i3                | 10        | 0.21%   |
| GNOME Classic     | 5         | 0.11%   |
| Cinnamon          | 4         | 0.08%   |
| sway              | 3         | 0.06%   |
| awesome           | 3         | 0.06%   |
| dwm               | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xsession          | 1         | 0.02%   |
| ratflow           | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| fluxbox           | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 3303      | 68.64%  |
| X11     | 1389      | 28.87%  |
| Unknown | 81        | 1.68%   |
| Tty     | 39        | 0.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 4404      | 92.44%  |
| Unknown | 260       | 5.46%   |
| LightDM | 59        | 1.24%   |
| GDM     | 19        | 0.4%    |
| SDDM    | 18        | 0.38%   |
| SLiM    | 3         | 0.06%   |
| XDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2241      | 47.09%  |
| de_DE   | 375       | 7.88%   |
| fr_FR   | 262       | 5.51%   |
| en_GB   | 231       | 4.85%   |
| pt_BR   | 193       | 4.06%   |
| en_IN   | 160       | 3.36%   |
| it_IT   | 158       | 3.32%   |
| ru_RU   | 131       | 2.75%   |
| es_ES   | 117       | 2.46%   |
| en_CA   | 98        | 2.06%   |
| pl_PL   | 72        | 1.51%   |
| en_AU   | 52        | 1.09%   |
| nl_NL   | 42        | 0.88%   |
| zh_CN   | 38        | 0.8%    |
| hu_HU   | 34        | 0.71%   |
| es_MX   | 30        | 0.63%   |
| en_ZA   | 30        | 0.63%   |
| Unknown | 30        | 0.63%   |
| C       | 29        | 0.61%   |
| cs_CZ   | 28        | 0.59%   |
| es_AR   | 26        | 0.55%   |
| tr_TR   | 22        | 0.46%   |
| pt_PT   | 22        | 0.46%   |
| es_CO   | 20        | 0.42%   |
| de_AT   | 20        | 0.42%   |
| sv_SE   | 18        | 0.38%   |
| en_PH   | 16        | 0.34%   |
| de_CH   | 16        | 0.34%   |
| en_NZ   | 14        | 0.29%   |
| da_DK   | 13        | 0.27%   |
| fr_BE   | 12        | 0.25%   |
| es_CL   | 12        | 0.25%   |
| ro_RO   | 11        | 0.23%   |
| nb_NO   | 11        | 0.23%   |
| fi_FI   | 11        | 0.23%   |
| ja_JP   | 10        | 0.21%   |
| en_IL   | 10        | 0.21%   |
| en_IE   | 10        | 0.21%   |
| ko_KR   | 8         | 0.17%   |
| en_SG   | 8         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2628      | 54.85%  |
| EFI  | 2163      | 45.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4392      | 92.19%  |
| Overlay | 127       | 2.67%   |
| Zfs     | 121       | 2.54%   |
| Tmpfs   | 58        | 1.22%   |
| Btrfs   | 41        | 0.86%   |
| Xfs     | 9         | 0.19%   |
| Ext3    | 8         | 0.17%   |
| Ext2    | 7         | 0.15%   |
| XXX4    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3268      | 67.86%  |
| Unknown | 1201      | 24.94%  |
| MBR     | 347       | 7.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4388      | 91.86%  |
| Yes       | 389       | 8.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3029      | 63.49%  |
| Yes       | 1742      | 36.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 970       | 20.44%  |
| Hewlett-Packard        | 887       | 18.69%  |
| Dell                   | 822       | 17.32%  |
| ASUSTek Computer       | 493       | 10.39%  |
| Acer                   | 372       | 7.84%   |
| Apple                  | 136       | 2.87%   |
| MSI                    | 129       | 2.72%   |
| HUAWEI                 | 112       | 2.36%   |
| Toshiba                | 99        | 2.09%   |
| Samsung Electronics    | 72        | 1.52%   |
| Sony                   | 46        | 0.97%   |
| Notebook               | 40        | 0.84%   |
| Timi                   | 35        | 0.74%   |
| Unknown                | 35        | 0.74%   |
| Alienware              | 32        | 0.67%   |
| Fujitsu                | 31        | 0.65%   |
| Google                 | 30        | 0.63%   |
| Medion                 | 21        | 0.44%   |
| Positivo               | 19        | 0.4%    |
| LG Electronics         | 19        | 0.4%    |
| Packard Bell           | 16        | 0.34%   |
| Chuwi                  | 16        | 0.34%   |
| TUXEDO                 | 14        | 0.3%    |
| Gigabyte Technology    | 14        | 0.3%    |
| System76               | 13        | 0.27%   |
| Avell High Performance | 13        | 0.27%   |
| Razer                  | 11        | 0.23%   |
| Gateway                | 11        | 0.23%   |
| HONOR                  | 10        | 0.21%   |
| Teclast                | 9         | 0.19%   |
| Framework              | 9         | 0.19%   |
| Schenker               | 8         | 0.17%   |
| GPU Company            | 7         | 0.15%   |
| AZW                    | 7         | 0.15%   |
| PC Specialist          | 6         | 0.13%   |
| Panasonic              | 6         | 0.13%   |
| Monster                | 6         | 0.13%   |
| Intel                  | 6         | 0.13%   |
| AMI                    | 6         | 0.13%   |
| Jumper                 | 5         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 50        | 1.05%   |
| HP Notebook                     | 23        | 0.48%   |
| Dell XPS 15 9520                | 16        | 0.34%   |
| Dell Latitude 5420              | 15        | 0.32%   |
| HP Pavilion dv7                 | 14        | 0.3%    |
| HP EliteBook 840 G8 Notebook PC | 14        | 0.3%    |
| HUAWEI HVY-WXX9                 | 13        | 0.27%   |
| HP Pavilion Notebook            | 13        | 0.27%   |
| HP EliteBook 840 G5             | 13        | 0.27%   |
| HP 15                           | 13        | 0.27%   |
| HP Pavilion g6                  | 12        | 0.25%   |
| HUAWEI NBLK-WAX9X               | 11        | 0.23%   |
| HUAWEI BOD-WXX9                 | 11        | 0.23%   |
| HP Pavilion g7                  | 11        | 0.23%   |
| HP Pavilion dv6                 | 11        | 0.23%   |
| HP EliteBook 8470p              | 11        | 0.23%   |
| HP EliteBook 840 G3             | 11        | 0.23%   |
| Dell XPS 15 9500                | 11        | 0.23%   |
| Dell XPS 13 9380                | 11        | 0.23%   |
| Timi TM1701                     | 10        | 0.21%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 10        | 0.21%   |
| HUAWEI BOM-WXX9                 | 10        | 0.21%   |
| Dell XPS 15 7590                | 10        | 0.21%   |
| Dell XPS 13 9370                | 10        | 0.21%   |
| Dell XPS 13 7390                | 10        | 0.21%   |
| Dell Vostro 3500                | 10        | 0.21%   |
| Dell Latitude 7420              | 10        | 0.21%   |
| Apple MacBookPro9,2             | 10        | 0.21%   |
| HP Pavilion 15                  | 9         | 0.19%   |
| Dell XPS 15 9570                | 9         | 0.19%   |
| Dell Latitude E7470             | 9         | 0.19%   |
| Dell Latitude E6510             | 9         | 0.19%   |
| Dell Latitude E6420             | 9         | 0.19%   |
| Dell G15 5510                   | 9         | 0.19%   |
| Acer Aspire E5-571              | 9         | 0.19%   |
| Lenovo IdeaPad 3 15ALC6 82MF    | 8         | 0.17%   |
| HUAWEI NBLB-WAX9N               | 8         | 0.17%   |
| HUAWEI BOHB-WAX9                | 8         | 0.17%   |
| HP Laptop 15s-eq2xxx            | 8         | 0.17%   |
| HP Laptop 15-db0xxx             | 8         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 478       | 10.07%  |
| Dell Latitude         | 290       | 6.11%   |
| Acer Aspire           | 249       | 5.25%   |
| Lenovo IdeaPad        | 232       | 4.89%   |
| Dell Inspiron         | 205       | 4.32%   |
| HP EliteBook          | 174       | 3.67%   |
| HP Pavilion           | 171       | 3.6%    |
| Dell XPS              | 135       | 2.85%   |
| HP ProBook            | 134       | 2.82%   |
| HP Laptop             | 127       | 2.68%   |
| ASUS VivoBook         | 126       | 2.66%   |
| Toshiba Satellite     | 78        | 1.64%   |
| Dell Vostro           | 71        | 1.5%    |
| Dell Precision        | 70        | 1.48%   |
| Lenovo ThinkBook      | 57        | 1.2%    |
| ASUS ROG              | 51        | 1.07%   |
| Unknown               | 50        | 1.05%   |
| ASUS ZenBook          | 47        | 0.99%   |
| Lenovo Legion         | 45        | 0.95%   |
| Acer Swift            | 43        | 0.91%   |
| HP ZBook              | 42        | 0.89%   |
| ASUS ASUS             | 39        | 0.82%   |
| HP ENVY               | 36        | 0.76%   |
| Acer Nitro            | 31        | 0.65%   |
| Fujitsu LIFEBOOK      | 27        | 0.57%   |
| HP OMEN               | 26        | 0.55%   |
| HP Notebook           | 24        | 0.51%   |
| Dell G15              | 24        | 0.51%   |
| HP 250                | 22        | 0.46%   |
| HP 255                | 19        | 0.4%    |
| HP 15                 | 19        | 0.4%    |
| Lenovo Yoga           | 18        | 0.38%   |
| HP Compaq             | 16        | 0.34%   |
| Packard Bell EasyNote | 15        | 0.32%   |
| MSI Stealth           | 15        | 0.32%   |
| Apple MacBookPro8     | 15        | 0.32%   |
| Apple MacBookPro11    | 15        | 0.32%   |
| Acer TravelMate       | 15        | 0.32%   |
| MSI Prestige          | 14        | 0.3%    |
| MSI GF63              | 14        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 769       | 16.21%  |
| 2020    | 591       | 12.46%  |
| 2019    | 437       | 9.21%   |
| 2022    | 381       | 8.03%   |
| 2018    | 351       | 7.4%    |
| 2013    | 296       | 6.24%   |
| 2012    | 278       | 5.86%   |
| 2017    | 277       | 5.84%   |
| 2011    | 265       | 5.58%   |
| 2014    | 229       | 4.83%   |
| 2016    | 222       | 4.68%   |
| 2015    | 222       | 4.68%   |
| 2010    | 186       | 3.92%   |
| 2008    | 98        | 2.07%   |
| 2009    | 85        | 1.79%   |
| 2007    | 33        | 0.7%    |
| 2023    | 10        | 0.21%   |
| 2006    | 10        | 0.21%   |
| Unknown | 5         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4745      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4107      | 86.08%  |
| Enabled  | 664       | 13.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4707      | 99.2%   |
| Yes  | 38        | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1447      | 30.43%  |
| 16.01-24.0  | 1054      | 22.17%  |
| 3.01-4.0    | 787       | 16.55%  |
| 8.01-16.0   | 756       | 15.9%   |
| 32.01-64.0  | 408       | 8.58%   |
| 1.01-2.0    | 94        | 1.98%   |
| 64.01-256.0 | 86        | 1.81%   |
| 24.01-32.0  | 79        | 1.66%   |
| 2.01-3.0    | 41        | 0.86%   |
| 0.51-1.0    | 3         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1583      | 31.9%   |
| 1.01-2.0   | 1358      | 27.36%  |
| 4.01-8.0   | 901       | 18.15%  |
| 3.01-4.0   | 791       | 15.94%  |
| 8.01-16.0  | 250       | 5.04%   |
| 0.51-1.0   | 36        | 0.73%   |
| 16.01-24.0 | 28        | 0.56%   |
| 24.01-32.0 | 9         | 0.18%   |
| 0.01-0.5   | 4         | 0.08%   |
| 32.01-64.0 | 3         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3658      | 76.51%  |
| 2      | 990       | 20.71%  |
| 3      | 88        | 1.84%   |
| 0      | 32        | 0.67%   |
| 4      | 10        | 0.21%   |
| 5      | 2         | 0.04%   |
| 7      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3432      | 72.15%  |
| Yes       | 1325      | 27.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3591      | 75.52%  |
| No        | 1164      | 24.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4671      | 98.42%  |
| No        | 75        | 1.58%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3932      | 82.28%  |
| No        | 847       | 17.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 720       | 15.12%  |
| Germany      | 497       | 10.44%  |
| France       | 328       | 6.89%   |
| Brazil       | 269       | 5.65%   |
| Italy        | 241       | 5.06%   |
| Russia       | 190       | 3.99%   |
| UK           | 184       | 3.86%   |
| India        | 182       | 3.82%   |
| Poland       | 144       | 3.02%   |
| Spain        | 141       | 2.96%   |
| Canada       | 109       | 2.29%   |
| Netherlands  | 108       | 2.27%   |
| Turkey       | 70        | 1.47%   |
| Mexico       | 65        | 1.37%   |
| Sweden       | 63        | 1.32%   |
| Hungary      | 61        | 1.28%   |
| Argentina    | 51        | 1.07%   |
| Czechia      | 47        | 0.99%   |
| Australia    | 47        | 0.99%   |
| Belgium      | 46        | 0.97%   |
| Austria      | 46        | 0.97%   |
| Switzerland  | 45        | 0.95%   |
| Romania      | 45        | 0.95%   |
| Portugal     | 45        | 0.95%   |
| Indonesia    | 41        | 0.86%   |
| China        | 41        | 0.86%   |
| Greece       | 38        | 0.8%    |
| Colombia     | 38        | 0.8%    |
| South Africa | 31        | 0.65%   |
| Denmark      | 31        | 0.65%   |
| Finland      | 29        | 0.61%   |
| Chile        | 27        | 0.57%   |
| Egypt        | 26        | 0.55%   |
| Bulgaria     | 26        | 0.55%   |
| Ukraine      | 25        | 0.53%   |
| Iran         | 25        | 0.53%   |
| Ireland      | 23        | 0.48%   |
| Japan        | 22        | 0.46%   |
| Taiwan       | 21        | 0.44%   |
| Serbia       | 21        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 54        | 1.1%    |
| Moscow            | 50        | 1.02%   |
| Paris             | 49        | 1%      |
| Milan             | 42        | 0.86%   |
| Warsaw            | 39        | 0.8%    |
| St Petersburg     | 38        | 0.78%   |
| Madrid            | 33        | 0.67%   |
| Budapest          | 32        | 0.65%   |
| Sao Paulo         | 27        | 0.55%   |
| Vienna            | 26        | 0.53%   |
| Rome              | 25        | 0.51%   |
| Istanbul          | 25        | 0.51%   |
| Munich            | 21        | 0.43%   |
| London            | 21        | 0.43%   |
| Bengaluru         | 21        | 0.43%   |
| Rio de Janeiro    | 20        | 0.41%   |
| Barcelona         | 20        | 0.41%   |
| Nairobi           | 19        | 0.39%   |
| Frankfurt am Main | 19        | 0.39%   |
| Sydney            | 17        | 0.35%   |
| Helsinki          | 17        | 0.35%   |
| Hamburg           | 17        | 0.35%   |
| Denver            | 17        | 0.35%   |
| Bogotá           | 17        | 0.35%   |
| Prague            | 16        | 0.33%   |
| Cape Town         | 16        | 0.33%   |
| Athens            | 16        | 0.33%   |
| Wroclaw           | 15        | 0.31%   |
| Tehran            | 15        | 0.31%   |
| Stockholm         | 15        | 0.31%   |
| Santiago          | 15        | 0.31%   |
| Los Angeles       | 15        | 0.31%   |
| Dublin            | 15        | 0.31%   |
| Singapore         | 14        | 0.29%   |
| Mexico City       | 14        | 0.29%   |
| Jakarta           | 14        | 0.29%   |
| Bucharest         | 14        | 0.29%   |
| Belgrade          | 14        | 0.29%   |
| Ankara            | 14        | 0.29%   |
| Amsterdam         | 14        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1020      | 1201   | 17.95%  |
| WDC                         | 571       | 652    | 10.05%  |
| Seagate                     | 479       | 557    | 8.43%   |
| Toshiba                     | 368       | 406    | 6.48%   |
| SanDisk                     | 356       | 419    | 6.27%   |
| SK hynix                    | 299       | 319    | 5.26%   |
| Kingston                    | 290       | 322    | 5.1%    |
| Unknown                     | 273       | 326    | 4.81%   |
| Micron Technology           | 225       | 239    | 3.96%   |
| Intel                       | 206       | 249    | 3.63%   |
| Crucial                     | 172       | 189    | 3.03%   |
| KIOXIA                      | 136       | 147    | 2.39%   |
| Hitachi                     | 128       | 148    | 2.25%   |
| HGST                        | 125       | 135    | 2.2%    |
| A-DATA Technology           | 79        | 90     | 1.39%   |
| Apple                       | 77        | 87     | 1.36%   |
| Phison                      | 60        | 66     | 1.06%   |
| Unknown                     | 51        | 52     | 0.9%    |
| China                       | 39        | 47     | 0.69%   |
| LITEON                      | 37        | 39     | 0.65%   |
| Silicon Motion              | 31        | 35     | 0.55%   |
| Intenso                     | 30        | 38     | 0.53%   |
| SPCC                        | 28        | 32     | 0.49%   |
| Netac                       | 23        | 25     | 0.4%    |
| Kingston Technology Company | 22        | 25     | 0.39%   |
| SSSTC                       | 20        | 22     | 0.35%   |
| Phison Electronics          | 20        | 21     | 0.35%   |
| Micron/Crucial Technology   | 20        | 21     | 0.35%   |
| PNY                         | 19        | 23     | 0.33%   |
| Fujitsu                     | 17        | 18     | 0.3%    |
| ADATA Technology            | 16        | 20     | 0.28%   |
| Transcend                   | 15        | 17     | 0.26%   |
| GOODRAM                     | 15        | 16     | 0.26%   |
| LITEONIT                    | 14        | 19     | 0.25%   |
| UMIS                        | 12        | 12     | 0.21%   |
| Patriot                     | 12        | 14     | 0.21%   |
| Hewlett-Packard             | 12        | 16     | 0.21%   |
| Gigabyte Technology         | 12        | 13     | 0.21%   |
| YMTC                        | 10        | 10     | 0.18%   |
| Team                        | 10        | 11     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                   | 70        | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 67        | 1.14%   |
| Toshiba MQ04ABF100 1TB                             | 52        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 52        | 0.89%   |
| Toshiba MQ01ABD100 1TB                             | 51        | 0.87%   |
| Unknown                                            | 51        | 0.87%   |
| Kingston SA400S37240G 240GB SSD                    | 48        | 0.82%   |
| Unknown MMC Card  32GB                             | 46        | 0.78%   |
| Unknown MMC Card  64GB                             | 45        | 0.77%   |
| Samsung NVMe SSD Drive 512GB                       | 38        | 0.65%   |
| Toshiba MQ01ABF050 500GB                           | 35        | 0.6%    |
| Seagate ST9500325AS 500GB                          | 34        | 0.58%   |
| Seagate ST500LT012-1DG142 500GB                    | 34        | 0.58%   |
| HGST HTS721010A9E630 1TB                           | 33        | 0.56%   |
| Samsung SSD 860 EVO 500GB                          | 31        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 31        | 0.53%   |
| Phison 311CD0512GB                                 | 29        | 0.49%   |
| Intel SSDPEKNU512GZ 512GB                          | 29        | 0.49%   |
| Crucial CT500MX500SSD1 500GB                       | 29        | 0.49%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                     | 28        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                    | 28        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB                       | 27        | 0.46%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 27        | 0.46%   |
| Crucial CT240BX500SSD1 240GB                       | 25        | 0.43%   |
| Samsung SSD 850 EVO 500GB                          | 24        | 0.41%   |
| Samsung NVMe SSD Drive 256GB                       | 22        | 0.38%   |
| HGST HTS545050A7E680 500GB                         | 22        | 0.38%   |
| HGST HTS541010A9E680 1TB                           | 22        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                        | 22        | 0.38%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 21        | 0.36%   |
| Unknown SD/MMC/MS PRO 249GB                        | 20        | 0.34%   |
| SanDisk NVMe SSD Drive 256GB                       | 20        | 0.34%   |
| Samsung SSD 850 EVO 250GB                          | 20        | 0.34%   |
| Samsung NVMe SSD Drive 1024GB                      | 20        | 0.34%   |
| KIOXIA KBG40ZNV512G 512GB                          | 20        | 0.34%   |
| Kingston SA400S37120G 120GB SSD                    | 20        | 0.34%   |
| Intel SSD 660P Series 512GB                        | 20        | 0.34%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 19        | 0.32%   |
| Samsung MZVL21T0HCLR-00B00 1TB                     | 19        | 0.32%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 18        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 460       | 532    | 33.48%  |
| WDC                 | 324       | 364    | 23.58%  |
| Toshiba             | 245       | 261    | 17.83%  |
| Hitachi             | 127       | 147    | 9.24%   |
| HGST                | 125       | 135    | 9.1%    |
| Samsung Electronics | 29        | 34     | 2.11%   |
| Unknown             | 21        | 23     | 1.53%   |
| Fujitsu             | 17        | 18     | 1.24%   |
| JMicron Technology  | 5         | 5      | 0.36%   |
| Apple               | 4         | 4      | 0.29%   |
| USB3.0              | 3         | 3      | 0.22%   |
| Intenso             | 3         | 3      | 0.22%   |
| ASMT                | 3         | 3      | 0.22%   |
| ASMedia             | 2         | 2      | 0.15%   |
| USB                 | 1         | 1      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| SAGE                | 1         | 1      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| MARSHAL             | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 2      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 332       | 373    | 20.65%  |
| Kingston            | 192       | 218    | 11.94%  |
| SanDisk             | 168       | 202    | 10.45%  |
| Crucial             | 151       | 165    | 9.39%   |
| WDC                 | 101       | 115    | 6.28%   |
| Micron Technology   | 53        | 55     | 3.3%    |
| SK hynix            | 46        | 55     | 2.86%   |
| Intel               | 37        | 39     | 2.3%    |
| China               | 37        | 43     | 2.3%    |
| Apple               | 36        | 37     | 2.24%   |
| A-DATA Technology   | 36        | 38     | 2.24%   |
| LITEON              | 34        | 36     | 2.11%   |
| Toshiba             | 26        | 29     | 1.62%   |
| SPCC                | 26        | 30     | 1.62%   |
| Netac               | 23        | 24     | 1.43%   |
| PNY                 | 17        | 20     | 1.06%   |
| Intenso             | 17        | 20     | 1.06%   |
| Unknown             | 17        | 17     | 1.06%   |
| LITEONIT            | 14        | 19     | 0.87%   |
| GOODRAM             | 14        | 15     | 0.87%   |
| Transcend           | 13        | 15     | 0.81%   |
| Patriot             | 12        | 14     | 0.75%   |
| Team                | 9         | 9      | 0.56%   |
| Gigabyte Technology | 9         | 9      | 0.56%   |
| Teclast             | 8         | 9      | 0.5%    |
| OCZ                 | 8         | 8      | 0.5%    |
| KingSpec            | 8         | 8      | 0.5%    |
| Hewlett-Packard     | 8         | 12     | 0.5%    |
| BIWIN               | 7         | 7      | 0.44%   |
| Lexar               | 6         | 6      | 0.37%   |
| Corsair             | 6         | 6      | 0.37%   |
| Apacer              | 6         | 6      | 0.37%   |
| Seagate             | 5         | 7      | 0.31%   |
| Emtec               | 5         | 5      | 0.31%   |
| BHT                 | 5         | 7      | 0.31%   |
| SSSTC               | 4         | 5      | 0.25%   |
| Plextor             | 4         | 4      | 0.25%   |
| Maxtor              | 4         | 4      | 0.25%   |
| Verbatim            | 3         | 3      | 0.19%   |
| Vaseky              | 3         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2252      | 2675   | 41.13%  |
| SSD     | 1522      | 1809   | 27.8%   |
| HDD     | 1334      | 1541   | 24.37%  |
| MMC     | 278       | 333    | 5.08%   |
| Unknown | 89        | 103    | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2579      | 3239   | 48.75%  |
| NVMe | 2245      | 2661   | 42.44%  |
| MMC  | 278       | 333    | 5.26%   |
| SAS  | 188       | 228    | 3.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1826      | 2197   | 64.77%  |
| 0.51-1.0   | 895       | 1037   | 31.75%  |
| 1.01-2.0   | 67        | 78     | 2.38%   |
| 3.01-4.0   | 14        | 14     | 0.5%    |
| 10.01-20.0 | 7         | 8      | 0.25%   |
| 4.01-10.0  | 7         | 9      | 0.25%   |
| 2.01-3.0   | 3         | 7      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1526      | 31.62%  |
| 251-500        | 1425      | 29.53%  |
| 501-1000       | 795       | 16.47%  |
| 51-100         | 286       | 5.93%   |
| 1-20           | 236       | 4.89%   |
| 1001-2000      | 218       | 4.52%   |
| 21-50          | 192       | 3.98%   |
| More than 3000 | 58        | 1.2%    |
| 2001-3000      | 48        | 0.99%   |
| Unknown        | 42        | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1795      | 36.26%  |
| 21-50          | 1102      | 22.26%  |
| 51-100         | 734       | 14.83%  |
| 101-250        | 678       | 13.7%   |
| 251-500        | 337       | 6.81%   |
| 501-1000       | 171       | 3.45%   |
| 1001-2000      | 59        | 1.19%   |
| Unknown        | 42        | 0.85%   |
| More than 3000 | 21        | 0.42%   |
| 2001-3000      | 11        | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 970GB      | 7         | 7      | 3.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 7      | 2.87%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 2.39%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 5         | 5      | 2.39%   |
| Seagate ST9500325AS 500GB             | 5         | 5      | 2.39%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 1.91%   |
| Seagate ST1000LM014-1EJ164 1TB        | 4         | 5      | 1.91%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 1.91%   |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 1.44%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 1.44%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 1.44%   |
| Seagate ST1000LX015-1U7172 1TB        | 3         | 3      | 1.44%   |
| Seagate ST1000LM014-SSHD-8GB          | 3         | 3      | 1.44%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 3      | 1.44%   |
| Hitachi HTS543232A7A384 320GB         | 3         | 3      | 1.44%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.44%   |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 1.44%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 1.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.96%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 2      | 0.96%   |
| WDC WD10JPVX-60JC3T0 1TB              | 2         | 2      | 0.96%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 2      | 0.96%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.96%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 3      | 0.96%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.96%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.96%   |
| Intel SSDSC2BF180A5L 180GB            | 2         | 2      | 0.96%   |
| HGST HTS541075A9E680 752GB            | 2         | 2      | 0.96%   |
| Crucial CT275MX300SSD4 275GB          | 2         | 2      | 0.96%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.48%   |
| WDC WD7500BPVT-24HXZT3 752GB          | 1         | 1      | 0.48%   |
| WDC WD7500BPKT-22PK4T0 752GB          | 1         | 1      | 0.48%   |
| WDC WD6000HLHX-01JJPV0 600GB          | 1         | 1      | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.48%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 0.48%   |
| WDC WD5000BEVT-60ZAT1 500GB           | 1         | 1      | 0.48%   |
| WDC WD5000BEVT-00A0RT0 500GB          | 1         | 1      | 0.48%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 56     | 24.52%  |
| WDC                 | 30        | 32     | 14.42%  |
| Toshiba             | 21        | 22     | 10.1%   |
| HGST                | 18        | 18     | 8.65%   |
| SK hynix            | 16        | 16     | 7.69%   |
| Hitachi             | 15        | 16     | 7.21%   |
| Samsung Electronics | 12        | 12     | 5.77%   |
| Intel               | 7         | 7      | 3.37%   |
| SanDisk             | 6         | 7      | 2.88%   |
| Micron Technology   | 6         | 6      | 2.88%   |
| A-DATA Technology   | 4         | 4      | 1.92%   |
| LITEON              | 3         | 3      | 1.44%   |
| Crucial             | 3         | 3      | 1.44%   |
| Kingston            | 2         | 3      | 0.96%   |
| China               | 2         | 2      | 0.96%   |
| WALRAM              | 1         | 1      | 0.48%   |
| VISIPRO             | 1         | 1      | 0.48%   |
| tecmiyo             | 1         | 1      | 0.48%   |
| SSSTC               | 1         | 1      | 0.48%   |
| ShiJi               | 1         | 1      | 0.48%   |
| RX7                 | 1         | 1      | 0.48%   |
| KingSpec            | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| HS-SSD-E100         | 1         | 1      | 0.48%   |
| Fujitsu             | 1         | 1      | 0.48%   |
| Corsair             | 1         | 1      | 0.48%   |
| Apple               | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 56     | 37.78%  |
| WDC                 | 25        | 27     | 18.52%  |
| Toshiba             | 20        | 21     | 14.81%  |
| HGST                | 18        | 18     | 13.33%  |
| Hitachi             | 15        | 16     | 11.11%  |
| Samsung Electronics | 4         | 4      | 2.96%   |
| Fujitsu             | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 135       | 144    | 64.9%   |
| SSD  | 52        | 54     | 25%     |
| NVMe | 21        | 21     | 10.1%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                                    | 1         | 1      | 20%     |
| WDC WD5000BEVT-22A0RT0 500GB                                    | 1         | 1      | 20%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 500GB | 1         | 1      | 20%     |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 20%     |
| Crucial M4-CT256M4SSD3 256GB                                    | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |
| Crucial             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2807      | 3890   | 56.84%  |
| Works    | 1921      | 2347   | 38.9%   |
| Malfunc  | 205       | 219    | 4.15%   |
| Failed   | 5         | 5      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3113      | 53.11%  |
| Samsung Electronics                  | 707       | 12.06%  |
| AMD                                  | 510       | 8.7%    |
| SanDisk                              | 328       | 5.6%    |
| SK hynix                             | 243       | 4.15%   |
| Micron Technology                    | 172       | 2.93%   |
| KIOXIA                               | 127       | 2.17%   |
| Kingston Technology Company          | 119       | 2.03%   |
| Toshiba America Info Systems         | 108       | 1.84%   |
| Phison Electronics                   | 83        | 1.42%   |
| ADATA Technology                     | 56        | 0.96%   |
| Silicon Motion                       | 47        | 0.8%    |
| Micron/Crucial Technology            | 42        | 0.72%   |
| Solid State Storage Technology       | 41        | 0.7%    |
| Apple                                | 34        | 0.58%   |
| Nvidia                               | 27        | 0.46%   |
| Union Memory (Shenzhen)              | 22        | 0.38%   |
| Yangtze Memory Technologies          | 13        | 0.22%   |
| Marvell Technology Group             | 12        | 0.2%    |
| Realtek Semiconductor                | 9         | 0.15%   |
| Shenzhen Longsys Electronics         | 8         | 0.14%   |
| Lite-On Technology                   | 7         | 0.12%   |
| Seagate Technology                   | 6         | 0.1%    |
| Lenovo                               | 5         | 0.09%   |
| MAXIO Technology (Hangzhou)          | 4         | 0.07%   |
| Biwin Storage Technology             | 3         | 0.05%   |
| ASMedia Technology                   | 3         | 0.05%   |
| Unknown                              | 3         | 0.05%   |
| Transcend                            | 2         | 0.03%   |
| INNOGRIT                             | 2         | 0.03%   |
| Zhaoxin                              | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.02%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.02%   |
| Netac Technology                     | 1         | 0.02%   |
| JMicron Technology                   | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 452       | 7.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 367       | 5.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 347       | 5.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 294       | 4.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 282       | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 247       | 3.99%   |
| Samsung NVMe SSD Controller 980                                                | 218       | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 195       | 3.15%   |
| Micron NVMe Storage Controller                                                 | 171       | 2.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 148       | 2.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 143       | 2.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 129       | 2.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 126       | 2.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 125       | 2.02%   |
| Intel Tiger Lake-LP SATA Controller                                            | 120       | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 117       | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 108       | 1.74%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 103       | 1.66%   |
| Intel Comet Lake SATA AHCI Controller                                          | 92        | 1.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 87        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 80        | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 73        | 1.18%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 70        | 1.13%   |
| Intel Non-Volatile memory controller                                           | 66        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 65        | 1.05%   |
| Intel SSD 660P Series                                                          | 61        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 61        | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 57        | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 57        | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 55        | 0.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 54        | 0.87%   |
| Phison PS5013 E13 NVMe Controller                                              | 52        | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 47        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 47        | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 47        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 45        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 44        | 0.71%   |
| SanDisk Non-Volatile memory controller                                         | 43        | 0.69%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 42        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 42        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3009      | 49.99%  |
| NVMe | 2236      | 37.15%  |
| RAID | 636       | 10.57%  |
| IDE  | 138       | 2.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3884      | 81.85%  |
| AMD          | 859       | 18.1%   |
| Phytium      | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 142       | 2.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 135       | 2.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 80        | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 71        | 1.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 64        | 1.35%   |
| Intel 12th Gen Core i7-12700H                 | 64        | 1.35%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 64        | 1.35%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 60        | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 57        | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 55        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 55        | 1.16%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 55        | 1.16%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 53        | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 52        | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 51        | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 50        | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 49        | 1.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 49        | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 48        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 47        | 0.99%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 47        | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 44        | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 43        | 0.91%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 42        | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 41        | 0.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 33        | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 32        | 0.67%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 32        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 31        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 29        | 0.61%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 28        | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 27        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 26        | 0.55%   |
| Intel 12th Gen Core i7-1260P                  | 26        | 0.55%   |
| Intel 12th Gen Core i7-1255U                  | 26        | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 25        | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 25        | 0.53%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 25        | 0.53%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 24        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1117      | 23.54%  |
| Intel Core i7           | 991       | 20.89%  |
| Other                   | 804       | 16.94%  |
| Intel Core i3           | 332       | 7%      |
| Intel Celeron           | 282       | 5.94%   |
| AMD Ryzen 5             | 238       | 5.02%   |
| AMD Ryzen 7             | 226       | 4.76%   |
| Intel Core 2 Duo        | 122       | 2.57%   |
| Intel Pentium           | 105       | 2.21%   |
| AMD Ryzen 9             | 45        | 0.95%   |
| AMD Ryzen 3             | 44        | 0.93%   |
| Intel Atom              | 43        | 0.91%   |
| AMD A6                  | 40        | 0.84%   |
| AMD A8                  | 34        | 0.72%   |
| AMD Ryzen 7 PRO         | 33        | 0.7%    |
| AMD A4                  | 26        | 0.55%   |
| AMD A10                 | 25        | 0.53%   |
| Intel Pentium Dual-Core | 22        | 0.46%   |
| AMD E2                  | 22        | 0.46%   |
| Intel Core i9           | 19        | 0.4%    |
| Intel Pentium Dual      | 15        | 0.32%   |
| AMD E1                  | 12        | 0.25%   |
| AMD E                   | 12        | 0.25%   |
| AMD Athlon              | 12        | 0.25%   |
| AMD Ryzen 5 PRO         | 11        | 0.23%   |
| Intel Xeon              | 10        | 0.21%   |
| Intel Pentium Silver    | 10        | 0.21%   |
| Intel Core 2            | 7         | 0.15%   |
| Intel Genuine           | 6         | 0.13%   |
| Intel Core M            | 6         | 0.13%   |
| AMD Turion 64 X2 Mobile | 6         | 0.13%   |
| Intel Core m3           | 5         | 0.11%   |
| Intel Celeron Dual-Core | 5         | 0.11%   |
| AMD Phenom II           | 5         | 0.11%   |
| AMD Athlon II           | 5         | 0.11%   |
| AMD A12                 | 5         | 0.11%   |
| AMD FX                  | 4         | 0.08%   |
| AMD Athlon II Dual-Core | 4         | 0.08%   |
| AMD Turion 64 Mobile    | 3         | 0.06%   |
| AMD Sempron             | 3         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2018      | 42.52%  |
| 4      | 1666      | 35.1%   |
| 8      | 410       | 8.64%   |
| 6      | 377       | 7.94%   |
| 14     | 118       | 2.49%   |
| 12     | 66        | 1.39%   |
| 10     | 51        | 1.07%   |
| 1      | 30        | 0.63%   |
| 16     | 5         | 0.11%   |
| 3      | 3         | 0.06%   |
| 5      | 2         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4745      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3798      | 79.99%  |
| 1      | 950       | 20.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4744      | 99.98%  |
| Unknown        | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2479      | 51.28%  |
| 0x806c1    | 274       | 5.67%   |
| 0x806ec    | 171       | 3.54%   |
| 0x806ea    | 127       | 2.63%   |
| 0x906a3    | 126       | 2.61%   |
| 0x306a9    | 113       | 2.34%   |
| 0x0a50000c | 103       | 2.13%   |
| 0x906ea    | 80        | 1.65%   |
| 0x206a7    | 79        | 1.63%   |
| 0xa0652    | 73        | 1.51%   |
| 0x306d4    | 71        | 1.47%   |
| 0x40651    | 69        | 1.43%   |
| 0x08608103 | 67        | 1.39%   |
| 0x806d1    | 66        | 1.37%   |
| 0x406e3    | 65        | 1.34%   |
| 0x806e9    | 62        | 1.28%   |
| 0x706e5    | 57        | 1.18%   |
| 0x706a8    | 53        | 1.1%    |
| 0x306c3    | 52        | 1.08%   |
| 0x08600106 | 44        | 0.91%   |
| 0x08108109 | 44        | 0.91%   |
| 0x906a4    | 35        | 0.72%   |
| 0x20655    | 35        | 0.72%   |
| 0x906e9    | 28        | 0.58%   |
| 0x806eb    | 25        | 0.52%   |
| 0x506e3    | 23        | 0.48%   |
| 0x30678    | 21        | 0.43%   |
| 0x1067a    | 21        | 0.43%   |
| 0x08600104 | 20        | 0.41%   |
| 0x906ed    | 19        | 0.39%   |
| 0x506c9    | 19        | 0.39%   |
| 0x08108102 | 19        | 0.39%   |
| 0x706a1    | 18        | 0.37%   |
| 0x06006705 | 16        | 0.33%   |
| 0x806c2    | 15        | 0.31%   |
| 0x0a404102 | 14        | 0.29%   |
| 0x20652    | 13        | 0.27%   |
| 0x06001119 | 12        | 0.25%   |
| 0x6fd      | 11        | 0.23%   |
| 0x406c4    | 10        | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 914       | 19.23%  |
| TigerLake        | 428       | 9.01%   |
| Haswell          | 324       | 6.82%   |
| Unknown          | 302       | 6.36%   |
| IvyBridge        | 301       | 6.33%   |
| SandyBridge      | 272       | 5.72%   |
| Skylake          | 232       | 4.88%   |
| Icelake          | 179       | 3.77%   |
| Zen 3            | 176       | 3.7%    |
| Alderlake Hybrid | 166       | 3.49%   |
| Broadwell        | 155       | 3.26%   |
| Westmere         | 152       | 3.2%    |
| Silvermont       | 142       | 2.99%   |
| Zen+             | 128       | 2.69%   |
| Penryn           | 124       | 2.61%   |
| Zen 2            | 119       | 2.5%    |
| Goldmont plus    | 119       | 2.5%    |
| CometLake        | 118       | 2.48%   |
| Excavator        | 72        | 1.52%   |
| Core             | 60        | 1.26%   |
| Goldmont         | 49        | 1.03%   |
| Puma             | 35        | 0.74%   |
| Zen              | 28        | 0.59%   |
| Piledriver       | 28        | 0.59%   |
| Bobcat           | 28        | 0.59%   |
| K10              | 22        | 0.46%   |
| Steamroller      | 13        | 0.27%   |
| K8 Hammer        | 13        | 0.27%   |
| K10 Llano        | 13        | 0.27%   |
| Jaguar           | 13        | 0.27%   |
| Nehalem          | 11        | 0.23%   |
| K8 & K10 hybrid  | 8         | 0.17%   |
| Tremont          | 6         | 0.13%   |
| Bonnell          | 2         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3634      | 59.25%  |
| Nvidia                           | 1387      | 22.62%  |
| AMD                              | 1110      | 18.1%   |
| Zhaoxin                          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 397       | 6.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 277       | 4.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 252       | 4.04%   |
| Intel UHD Graphics 620                                                                   | 211       | 3.39%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 179       | 2.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 167       | 2.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 160       | 2.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 158       | 2.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 147       | 2.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 141       | 2.26%   |
| Intel HD Graphics 620                                                                    | 141       | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 139       | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 134       | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 133       | 2.13%   |
| Intel HD Graphics 5500                                                                   | 128       | 2.05%   |
| AMD Lucienne                                                                             | 123       | 1.97%   |
| AMD Renoir                                                                               | 113       | 1.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 109       | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 106       | 1.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 104       | 1.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 101       | 1.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 95        | 1.52%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 81        | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 77        | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 65        | 1.04%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 64        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 64        | 1.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 57        | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 55        | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 55        | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 46        | 0.74%   |
| Intel HD Graphics 500                                                                    | 45        | 0.72%   |
| Intel HD Graphics 630                                                                    | 44        | 0.71%   |
| Intel HD Graphics 530                                                                    | 41        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 40        | 0.64%   |
| AMD Rembrandt [Radeon 680M]                                                              | 38        | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 37        | 0.59%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 36        | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 35        | 0.56%   |
| Nvidia TU117M                                                                            | 34        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 2372      | 49.97%  |
| Intel + Nvidia | 1072      | 22.58%  |
| 1 x AMD        | 744       | 15.67%  |
| 1 x Nvidia     | 180       | 3.79%   |
| Intel + AMD    | 176       | 3.71%   |
| AMD + Nvidia   | 133       | 2.8%    |
| 2 x AMD        | 56        | 1.18%   |
| Other          | 9         | 0.19%   |
| 2 x Nvidia     | 2         | 0.04%   |
| 2 x Intel      | 1         | 0.02%   |
| 1 x Zhaoxin    | 1         | 0.02%   |
| 1 x SiS        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3929      | 82.39%  |
| Proprietary | 753       | 15.79%  |
| Unknown     | 87        | 1.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3917      | 81.96%  |
| 1.01-2.0   | 272       | 5.69%   |
| 0.01-0.5   | 266       | 5.57%   |
| 0.51-1.0   | 136       | 2.85%   |
| 3.01-4.0   | 119       | 2.49%   |
| 5.01-6.0   | 36        | 0.75%   |
| 7.01-8.0   | 22        | 0.46%   |
| 2.01-3.0   | 6         | 0.13%   |
| 8.01-16.0  | 5         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1008      | 18.1%   |
| BOE                     | 943       | 16.93%  |
| Chimei Innolux          | 734       | 13.18%  |
| LG Display              | 708       | 12.71%  |
| Samsung Electronics     | 529       | 9.5%    |
| Dell                    | 176       | 3.16%   |
| Sharp                   | 173       | 3.11%   |
| Apple                   | 132       | 2.37%   |
| Goldstar                | 130       | 2.33%   |
| PANDA                   | 102       | 1.83%   |
| Chi Mei Optoelectronics | 93        | 1.67%   |
| Lenovo                  | 90        | 1.62%   |
| Hewlett-Packard         | 79        | 1.42%   |
| Acer                    | 55        | 0.99%   |
| InfoVision              | 49        | 0.88%   |
| CSO                     | 49        | 0.88%   |
| Philips                 | 45        | 0.81%   |
| AOC                     | 44        | 0.79%   |
| Ancor Communications    | 35        | 0.63%   |
| BenQ                    | 34        | 0.61%   |
| Iiyama                  | 33        | 0.59%   |
| ViewSonic               | 23        | 0.41%   |
| Sony                    | 22        | 0.4%    |
| ASUSTek Computer        | 22        | 0.4%    |
| LG Philips              | 20        | 0.36%   |
| TMX                     | 18        | 0.32%   |
| CPT                     | 14        | 0.25%   |
| Mi                      | 11        | 0.2%    |
| MSI                     | 10        | 0.18%   |
| Toshiba                 | 9         | 0.16%   |
| Panasonic               | 9         | 0.16%   |
| Vizio                   | 7         | 0.13%   |
| Fujitsu Siemens         | 7         | 0.13%   |
| Eizo                    | 7         | 0.13%   |
| SLD                     | 6         | 0.11%   |
| HannStar                | 6         | 0.11%   |
| Vestel Elektronik       | 5         | 0.09%   |
| STA                     | 5         | 0.09%   |
| SGT                     | 5         | 0.09%   |
| NEC Computers           | 5         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 43        | 0.76%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 35        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 35        | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 34        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 33        | 0.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 30        | 0.53%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 28        | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 25        | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 24        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 23        | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 23        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 22        | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 20        | 0.35%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 19        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 18        | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.3%    |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 16        | 0.28%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 16        | 0.28%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 16        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 15        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 15        | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 0.27%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                    | 15        | 0.27%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 15        | 0.27%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 15        | 0.27%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 15        | 0.27%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 14        | 0.25%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 14        | 0.25%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x165mm 13.2-inch            | 14        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.25%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 13        | 0.23%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 13        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 13        | 0.23%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                    | 13        | 0.23%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 13        | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.21%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.21%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 12        | 0.21%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 12        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2415      | 46.46%  |
| 1366x768 (WXGA)    | 1299      | 24.99%  |
| 1600x900 (HD+)     | 262       | 5.04%   |
| 3840x2160 (4K)     | 219       | 4.21%   |
| 2560x1440 (QHD)    | 184       | 3.54%   |
| 1920x1200 (WUXGA)  | 134       | 2.58%   |
| 1280x800 (WXGA)    | 122       | 2.35%   |
| 2560x1600          | 101       | 1.94%   |
| 2880x1800          | 63        | 1.21%   |
| 1440x900 (WXGA+)   | 56        | 1.08%   |
| 3840x2400          | 44        | 0.85%   |
| 1680x1050 (WSXGA+) | 41        | 0.79%   |
| 2560x1080          | 39        | 0.75%   |
| 3440x1440          | 36        | 0.69%   |
| 2160x1440          | 27        | 0.52%   |
| 1280x1024 (SXGA)   | 19        | 0.37%   |
| 1360x768           | 14        | 0.27%   |
| 3200x1800 (QHD+)   | 10        | 0.19%   |
| 2256x1504          | 10        | 0.19%   |
| 3840x1080          | 9         | 0.17%   |
| 2520x1680          | 8         | 0.15%   |
| 3456x2160          | 7         | 0.13%   |
| 3200x2000          | 7         | 0.13%   |
| 3072x1920          | 7         | 0.13%   |
| 3000x2000          | 6         | 0.12%   |
| 1920x540           | 6         | 0.12%   |
| Unknown            | 6         | 0.12%   |
| 2240x1400          | 4         | 0.08%   |
| 1680x945           | 4         | 0.08%   |
| 1024x768 (XGA)     | 4         | 0.08%   |
| 2880x1620          | 3         | 0.06%   |
| 3840x1600          | 2         | 0.04%   |
| 2304x1440          | 2         | 0.04%   |
| 2160x1350          | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 1600x1200          | 2         | 0.04%   |
| 1400x1050          | 2         | 0.04%   |
| 1280x720 (HD)      | 2         | 0.04%   |
| 1024x600           | 2         | 0.04%   |
| 6400x2160          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2236      | 40.13%  |
| 13      | 803       | 14.41%  |
| 14      | 713       | 12.8%   |
| 17      | 407       | 7.3%    |
| 27      | 215       | 3.86%   |
| 24      | 196       | 3.52%   |
| 23      | 155       | 2.78%   |
| 16      | 126       | 2.26%   |
| 21      | 120       | 2.15%   |
| 12      | 97        | 1.74%   |
| 11      | 88        | 1.58%   |
| 34      | 69        | 1.24%   |
| 31      | 52        | 0.93%   |
| 18      | 38        | 0.68%   |
| Unknown | 34        | 0.61%   |
| 22      | 26        | 0.47%   |
| 19      | 23        | 0.41%   |
| 20      | 18        | 0.32%   |
| 40      | 17        | 0.31%   |
| 84      | 16        | 0.29%   |
| 54      | 16        | 0.29%   |
| 72      | 14        | 0.25%   |
| 10      | 12        | 0.22%   |
| 26      | 11        | 0.2%    |
| 28      | 9         | 0.16%   |
| 25      | 8         | 0.14%   |
| 32      | 6         | 0.11%   |
| 65      | 5         | 0.09%   |
| 48      | 5         | 0.09%   |
| 43      | 5         | 0.09%   |
| 49      | 4         | 0.07%   |
| 52      | 3         | 0.05%   |
| 46      | 3         | 0.05%   |
| 38      | 3         | 0.05%   |
| 37      | 3         | 0.05%   |
| 29      | 3         | 0.05%   |
| 74      | 2         | 0.04%   |
| 47      | 2         | 0.04%   |
| 35      | 2         | 0.04%   |
| 33      | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 3395      | 61.36%  |
| 201-300     | 598       | 10.81%  |
| 501-600     | 528       | 9.54%   |
| 351-400     | 492       | 8.89%   |
| 401-500     | 216       | 3.9%    |
| 601-700     | 88        | 1.59%   |
| 701-800     | 76        | 1.37%   |
| 1001-1500   | 40        | 0.72%   |
| Unknown     | 34        | 0.61%   |
| 1501-2000   | 33        | 0.6%    |
| 801-900     | 26        | 0.47%   |
| 901-1000    | 5         | 0.09%   |
| 101-200     | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4050      | 83.37%  |
| 16/10   | 602       | 12.39%  |
| 21/9    | 80        | 1.65%   |
| 3/2     | 65        | 1.34%   |
| Unknown | 18        | 0.37%   |
| 4/3     | 14        | 0.29%   |
| 5/4     | 13        | 0.27%   |
| 32/9    | 7         | 0.14%   |
| 6/5     | 3         | 0.06%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 2.12    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2248      | 40.42%  |
| 81-90          | 1207      | 21.7%   |
| 201-250        | 398       | 7.16%   |
| 121-130        | 364       | 6.54%   |
| 71-80          | 306       | 5.5%    |
| 301-350        | 224       | 4.03%   |
| 351-500        | 135       | 2.43%   |
| 111-120        | 102       | 1.83%   |
| 61-70          | 90        | 1.62%   |
| 51-60          | 88        | 1.58%   |
| 251-300        | 77        | 1.38%   |
| 151-200        | 73        | 1.31%   |
| More than 1000 | 59        | 1.06%   |
| 501-1000       | 41        | 0.74%   |
| 141-150        | 40        | 0.72%   |
| 131-140        | 40        | 0.72%   |
| Unknown        | 34        | 0.61%   |
| 91-100         | 22        | 0.4%    |
| 41-50          | 13        | 0.23%   |
| 1-40           | 1         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2334      | 42.87%  |
| 101-120       | 1504      | 27.62%  |
| 51-100        | 814       | 14.95%  |
| 161-240       | 503       | 9.24%   |
| More than 240 | 207       | 3.8%    |
| 1-50          | 49        | 0.9%    |
| Unknown       | 34        | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3700      | 77.04%  |
| 2     | 861       | 17.93%  |
| 0     | 119       | 2.48%   |
| 3     | 114       | 2.37%   |
| 4     | 8         | 0.17%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 2652      | 35.9%   |
| Realtek Semiconductor                  | 2564      | 34.7%   |
| Qualcomm Atheros                       | 862       | 11.67%  |
| Broadcom                               | 404       | 5.47%   |
| MediaTek                               | 174       | 2.36%   |
| Broadcom Limited                       | 99        | 1.34%   |
| ASIX Electronics                       | 60        | 0.81%   |
| Ralink                                 | 56        | 0.76%   |
| TP-Link                                | 46        | 0.62%   |
| Marvell Technology Group               | 40        | 0.54%   |
| DisplayLink                            | 35        | 0.47%   |
| Dell                                   | 33        | 0.45%   |
| Samsung Electronics                    | 32        | 0.43%   |
| Lenovo                                 | 27        | 0.37%   |
| Qualcomm                               | 25        | 0.34%   |
| Ralink Technology                      | 22        | 0.3%    |
| Nvidia                                 | 20        | 0.27%   |
| NetGear                                | 20        | 0.27%   |
| Sierra Wireless                        | 19        | 0.26%   |
| Xiaomi                                 | 17        | 0.23%   |
| Hewlett-Packard                        | 16        | 0.22%   |
| Ericsson Business Mobile Networks      | 15        | 0.2%    |
| JMicron Technology                     | 13        | 0.18%   |
| Qualcomm Atheros Communications        | 12        | 0.16%   |
| ICS Advent                             | 11        | 0.15%   |
| Apple                                  | 11        | 0.15%   |
| Huawei Technologies                    | 10        | 0.14%   |
| OPPO Electronics                       | 9         | 0.12%   |
| Google                                 | 9         | 0.12%   |
| Motorola PCS                           | 7         | 0.09%   |
| D-Link                                 | 7         | 0.09%   |
| Fibocom                                | 6         | 0.08%   |
| U-Blox                                 | 5         | 0.07%   |
| Edimax Technology                      | 5         | 0.07%   |
| Arduino SA                             | 5         | 0.07%   |
| Toshiba                                | 4         | 0.05%   |
| D-Link System                          | 3         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1446      | 16.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 363       | 4.12%   |
| Intel Wi-Fi 6 AX201                                               | 332       | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 253       | 2.87%   |
| Intel Wi-Fi 6 AX200                                               | 226       | 2.57%   |
| Intel Wireless 8265 / 8275                                        | 210       | 2.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 202       | 2.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 174       | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 171       | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 164       | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 162       | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 141       | 1.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 129       | 1.46%   |
| Intel Wireless 7265                                               | 127       | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 126       | 1.43%   |
| Intel Wireless 7260                                               | 125       | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 120       | 1.36%   |
| Intel Wireless 8260                                               | 115       | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 112       | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 94        | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 90        | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 88        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 85        | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 84        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 79        | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 69        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 68        | 0.77%   |
| Intel Wireless 3165                                               | 67        | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 63        | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 61        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 58        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 58        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                     | 56        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 56        | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 52        | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 48        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 47        | 0.53%   |
| Intel Centrino Wireless-N 2230                                    | 46        | 0.52%   |
| Intel Ethernet Connection I218-LM                                 | 45        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2538      | 52.09%  |
| Realtek Semiconductor           | 796       | 16.34%  |
| Qualcomm Atheros                | 740       | 15.19%  |
| Broadcom                        | 330       | 6.77%   |
| MediaTek                        | 166       | 3.41%   |
| Broadcom Limited                | 64        | 1.31%   |
| Ralink                          | 56        | 1.15%   |
| TP-Link                         | 36        | 0.74%   |
| Ralink Technology               | 22        | 0.45%   |
| Dell                            | 22        | 0.45%   |
| Qualcomm                        | 20        | 0.41%   |
| NetGear                         | 19        | 0.39%   |
| Sierra Wireless                 | 17        | 0.35%   |
| Qualcomm Atheros Communications | 12        | 0.25%   |
| Hewlett-Packard                 | 6         | 0.12%   |
| Fibocom                         | 6         | 0.12%   |
| D-Link                          | 6         | 0.12%   |
| Edimax Technology               | 5         | 0.1%    |
| D-Link System                   | 3         | 0.06%   |
| U.S. Robotics                   | 1         | 0.02%   |
| TRENDnet                        | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Linksys                         | 1         | 0.02%   |
| IMC Networks                    | 1         | 0.02%   |
| I-O Data Device                 | 1         | 0.02%   |
| AboCom Systems                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 332       | 6.77%   |
| Intel Wi-Fi 6 AX200                                            | 226       | 4.61%   |
| Intel Wireless 8265 / 8275                                     | 210       | 4.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 202       | 4.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 174       | 3.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 171       | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 164       | 3.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 162       | 3.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 129       | 2.63%   |
| Intel Wireless 7265                                            | 127       | 2.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 126       | 2.57%   |
| Intel Wireless 7260                                            | 125       | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 120       | 2.45%   |
| Intel Wireless 8260                                            | 115       | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 112       | 2.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 94        | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 88        | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 85        | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 84        | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 79        | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 69        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 68        | 1.39%   |
| Intel Wireless 3165                                            | 67        | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 61        | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 58        | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 58        | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                  | 56        | 1.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 48        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 47        | 0.96%   |
| Intel Centrino Wireless-N 2230                                 | 46        | 0.94%   |
| Intel Wireless 3160                                            | 44        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 42        | 0.86%   |
| Intel Wireless-AC 9260                                         | 40        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                 | 37        | 0.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 36        | 0.73%   |
| Intel Centrino Advanced-N 6200                                 | 36        | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 35        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 34        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 34        | 0.69%   |
| Realtek 802.11n WLAN Adapter                                   | 32        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2191      | 58.12%  |
| Intel                                  | 867       | 23%     |
| Qualcomm Atheros                       | 206       | 5.46%   |
| Broadcom                               | 141       | 3.74%   |
| ASIX Electronics                       | 60        | 1.59%   |
| Marvell Technology Group               | 40        | 1.06%   |
| Broadcom Limited                       | 37        | 0.98%   |
| DisplayLink                            | 35        | 0.93%   |
| Lenovo                                 | 27        | 0.72%   |
| Samsung Electronics                    | 23        | 0.61%   |
| Nvidia                                 | 20        | 0.53%   |
| Xiaomi                                 | 17        | 0.45%   |
| JMicron Technology                     | 13        | 0.34%   |
| ICS Advent                             | 11        | 0.29%   |
| Apple                                  | 11        | 0.29%   |
| TP-Link                                | 10        | 0.27%   |
| OPPO Electronics                       | 9         | 0.24%   |
| Google                                 | 9         | 0.24%   |
| MediaTek                               | 8         | 0.21%   |
| Qualcomm                               | 5         | 0.13%   |
| Motorola PCS                           | 5         | 0.13%   |
| Huawei Technologies                    | 5         | 0.13%   |
| Hewlett-Packard                        | 4         | 0.11%   |
| Sierra Wireless                        | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| HMD Global                             | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.03%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.03%   |
| Research In Motion                     | 1         | 0.03%   |
| NetGear                                | 1         | 0.03%   |
| Netchip Technology                     | 1         | 0.03%   |
| LG Electronics                         | 1         | 0.03%   |
| Davicom Semiconductor                  | 1         | 0.03%   |
| D-Link                                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1446      | 37.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 363       | 9.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 253       | 6.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 141       | 3.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 90        | 2.35%   |
| Intel Ethernet Connection I219-LM                                 | 63        | 1.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 56        | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 1.36%   |
| Intel 82577LM Gigabit Network Connection                          | 52        | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 45        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 38        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 37        | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 37        | 0.97%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 35        | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 35        | 0.91%   |
| Realtek Killer E3000 2.5GbE Controller                            | 33        | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                             | 31        | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 30        | 0.78%   |
| Intel Ethernet Connection (13) I219-LM                            | 26        | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 22        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.58%   |
| Intel Ethernet Connection (13) I219-V                             | 20        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 19        | 0.5%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 19        | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 18        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18        | 0.47%   |
| Intel Ethernet Connection (16) I219-LM                            | 18        | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 18        | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 17        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 17        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 16        | 0.42%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 16        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 16        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4674      | 56.12%  |
| Ethernet | 3580      | 42.98%  |
| Modem    | 67        | 0.8%    |
| Unknown  | 8         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3952      | 78.68%  |
| Ethernet | 1071      | 21.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3166      | 66.72%  |
| 1     | 1466      | 30.9%   |
| 0     | 83        | 1.75%   |
| 3     | 30        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3370      | 70.4%   |
| Yes  | 1417      | 29.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2146      | 54.22%  |
| Realtek Semiconductor           | 446       | 11.27%  |
| Qualcomm Atheros Communications | 300       | 7.58%   |
| IMC Networks                    | 209       | 5.28%   |
| Lite-On Technology              | 159       | 4.02%   |
| Foxconn / Hon Hai               | 158       | 3.99%   |
| Broadcom                        | 144       | 3.64%   |
| Apple                           | 98        | 2.48%   |
| Dell                            | 57        | 1.44%   |
| Realtek                         | 48        | 1.21%   |
| Hewlett-Packard                 | 37        | 0.93%   |
| Cambridge Silicon Radio         | 36        | 0.91%   |
| Ralink                          | 31        | 0.78%   |
| Toshiba                         | 24        | 0.61%   |
| ASUSTek Computer                | 11        | 0.28%   |
| Foxconn International           | 10        | 0.25%   |
| Alps Electric                   | 9         | 0.23%   |
| Ralink Technology               | 8         | 0.2%    |
| USI                             | 6         | 0.15%   |
| MediaTek                        | 6         | 0.15%   |
| Askey Computer                  | 4         | 0.1%    |
| Opticis                         | 3         | 0.08%   |
| TP-Link                         | 1         | 0.03%   |
| Roper                           | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Mobile Action Technology        | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Fujitsu Siemens Computers       | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 680       | 17.17%  |
| Intel AX201 Bluetooth                               | 585       | 14.77%  |
| Realtek Bluetooth Radio                             | 317       | 8.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 287       | 7.25%   |
| Intel AX200 Bluetooth                               | 223       | 5.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 191       | 4.82%   |
| Intel Bluetooth Device                              | 166       | 4.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 93        | 2.35%   |
| IMC Networks Wireless_Device                        | 82        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 71        | 1.79%   |
| Apple Bluetooth Host Controller                     | 62        | 1.57%   |
| IMC Networks Bluetooth Radio                        | 59        | 1.49%   |
| Intel AX210 Bluetooth                               | 57        | 1.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 54        | 1.36%   |
| Foxconn / Hon Hai Bluetooth Device                  | 54        | 1.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 50        | 1.26%   |
| Foxconn / Hon Hai Wireless_Device                   | 48        | 1.21%   |
| Realtek 802.11ac WLAN Adapter                       | 43        | 1.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 36        | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 35        | 0.88%   |
| IMC Networks Bluetooth Device                       | 34        | 0.86%   |
| Ralink RT3290 Bluetooth                             | 31        | 0.78%   |
| Lite-On Bluetooth Device                            | 31        | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 31        | 0.78%   |
| Apple Bluetooth USB Host Controller                 | 28        | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 27        | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 25        | 0.63%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 23        | 0.58%   |
| Lite-On Wireless_Device                             | 21        | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 19        | 0.48%   |
| Broadcom HP Portable SoftSailing                    | 19        | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 16        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 14        | 0.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 12        | 0.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3813      | 64.17%  |
| AMD                                          | 963       | 16.21%  |
| Nvidia                                       | 744       | 12.52%  |
| Realtek Semiconductor                        | 36        | 0.61%   |
| Logitech                                     | 34        | 0.57%   |
| C-Media Electronics                          | 34        | 0.57%   |
| Lenovo                                       | 31        | 0.52%   |
| Hewlett-Packard                              | 30        | 0.5%    |
| GN Netcom                                    | 29        | 0.49%   |
| Plantronics                                  | 28        | 0.47%   |
| Apple                                        | 26        | 0.44%   |
| JMTek                                        | 14        | 0.24%   |
| Corsair                                      | 12        | 0.2%    |
| Kingston Technology                          | 11        | 0.19%   |
| Texas Instruments                            | 10        | 0.17%   |
| Razer USA                                    | 9         | 0.15%   |
| Generalplus Technology                       | 8         | 0.13%   |
| Creative Technology                          | 8         | 0.13%   |
| Sennheiser Communications                    | 6         | 0.1%    |
| ASUSTek Computer                             | 6         | 0.1%    |
| SteelSeries ApS                              | 5         | 0.08%   |
| DCMT Technology                              | 5         | 0.08%   |
| BR25                                         | 5         | 0.08%   |
| Sony                                         | 4         | 0.07%   |
| RODE Microphones                             | 4         | 0.07%   |
| BEHRINGER International                      | 4         | 0.07%   |
| JBL                                          | 3         | 0.05%   |
| DSEA A/S                                     | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| Syntek                                       | 2         | 0.03%   |
| Samsung Electronics                          | 2         | 0.03%   |
| OPPO Electronics                             | 2         | 0.03%   |
| Microsoft                                    | 2         | 0.03%   |
| Huawei Technologies                          | 2         | 0.03%   |
| Google                                       | 2         | 0.03%   |
| Focusrite-Novation                           | 2         | 0.03%   |
| fifine Microphones                           | 2         | 0.03%   |
| Dell                                         | 2         | 0.03%   |
| Conexant Systems                             | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 576       | 8.07%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 553       | 7.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 428       | 6%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 365       | 5.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 349       | 4.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 235       | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 223       | 3.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 171       | 2.4%    |
| Intel 8 Series HD Audio Controller                                                                | 171       | 2.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 167       | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 162       | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 161       | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 159       | 2.23%   |
| Intel Broadwell-U Audio Controller                                                                | 155       | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 155       | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 150       | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 143       | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 125       | 1.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 119       | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 115       | 1.61%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 112       | 1.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 111       | 1.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 105       | 1.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 103       | 1.44%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 93        | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 86        | 1.2%    |
| Nvidia Audio device                                                                               | 83        | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 72        | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 70        | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 63        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 57        | 0.8%    |
| AMD High Definition Audio Controller                                                              | 57        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 56        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 53        | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 52        | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 51        | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 50        | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 50        | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 49        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 49        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 980       | 31.42%  |
| SK hynix                                | 743       | 23.82%  |
| Micron Technology                       | 426       | 13.66%  |
| Kingston                                | 223       | 7.15%   |
| Crucial                                 | 147       | 4.71%   |
| Unknown                                 | 102       | 3.27%   |
| A-DATA Technology                       | 72        | 2.31%   |
| Unknown (ABCD)                          | 65        | 2.08%   |
| Ramaxel Technology                      | 64        | 2.05%   |
| Nanya Technology                        | 39        | 1.25%   |
| Elpida                                  | 28        | 0.9%    |
| Corsair                                 | 28        | 0.9%    |
| Smart                                   | 24        | 0.77%   |
| Unknown                                 | 23        | 0.74%   |
| G.Skill                                 | 18        | 0.58%   |
| Team                                    | 13        | 0.42%   |
| Patriot                                 | 10        | 0.32%   |
| Smart Brazil                            | 8         | 0.26%   |
| Transcend                               | 6         | 0.19%   |
| GOODRAM                                 | 6         | 0.19%   |
| Goldkey                                 | 6         | 0.19%   |
| ChangXin Memory                         | 6         | 0.19%   |
| Wilk                                    | 4         | 0.13%   |
| Toshiba                                 | 3         | 0.1%    |
| PNY                                     | 3         | 0.1%    |
| Neo Forza                               | 3         | 0.1%    |
| fef5                                    | 3         | 0.1%    |
| Avant                                   | 3         | 0.1%    |
| ASint Technology                        | 3         | 0.1%    |
| Apacer                                  | 3         | 0.1%    |
| AMD                                     | 3         | 0.1%    |
| Unknown (768A)                          | 2         | 0.06%   |
| Teikon                                  | 2         | 0.06%   |
| Smart Modular                           | 2         | 0.06%   |
| Silicon Power Computer & Communications | 2         | 0.06%   |
| Silicon Power                           | 2         | 0.06%   |
| SHARETRONIC                             | 2         | 0.06%   |
| Qimonda                                 | 2         | 0.06%   |
| OM Nanotech                             | 2         | 0.06%   |
| Netac                                   | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 72        | 2.2%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 62        | 1.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 45        | 1.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 36        | 1.1%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 34        | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 33        | 1.01%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 1.01%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 31        | 0.95%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 30        | 0.92%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 27        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 26        | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 23        | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.7%    |
| Unknown                                                          | 23        | 0.7%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 21        | 0.64%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 20        | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.58%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 19        | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 17        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 16        | 0.49%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 16        | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.49%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 16        | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.46%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 15        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1493      | 56.19%  |
| DDR3    | 612       | 23.03%  |
| LPDDR4  | 235       | 8.84%   |
| LPDDR3  | 105       | 3.95%   |
| DDR5    | 99        | 3.73%   |
| LPDDR5  | 43        | 1.62%   |
| DDR2    | 39        | 1.47%   |
| SDRAM   | 19        | 0.72%   |
| Unknown | 9         | 0.34%   |
| DDR     | 2         | 0.08%   |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 2232      | 82.94%  |
| Row Of Chips    | 416       | 15.46%  |
| Unknown         | 17        | 0.63%   |
| Chip            | 13        | 0.48%   |
| DIMM            | 11        | 0.41%   |
| Proprietary Car | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Notebooks | Percent |
|--------|-----------|---------|
| 8192   | 1255      | 43.8%   |
| 4096   | 771       | 26.91%  |
| 16384  | 507       | 17.7%   |
| 2048   | 189       | 6.6%    |
| 32768  | 100       | 3.49%   |
| 1024   | 38        | 1.33%   |
| 6144   | 2         | 0.07%   |
| 131072 | 1         | 0.03%   |
| 65536  | 1         | 0.03%   |
| 1536   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 812       | 28.65%  |
| 2667    | 571       | 20.15%  |
| 1600    | 462       | 16.3%   |
| 2400    | 225       | 7.94%   |
| 2133    | 144       | 5.08%   |
| 4800    | 102       | 3.6%    |
| 4267    | 94        | 3.32%   |
| 1334    | 88        | 3.11%   |
| 1333    | 57        | 2.01%   |
| 6400    | 46        | 1.62%   |
| 3266    | 36        | 1.27%   |
| 1867    | 28        | 0.99%   |
| 4266    | 24        | 0.85%   |
| 667     | 23        | 0.81%   |
| Unknown | 21        | 0.74%   |
| 1067    | 19        | 0.67%   |
| 4199    | 15        | 0.53%   |
| 3733    | 12        | 0.42%   |
| 1066    | 12        | 0.42%   |
| 8400    | 10        | 0.35%   |
| 800     | 8         | 0.28%   |
| 2933    | 5         | 0.18%   |
| 2048    | 4         | 0.14%   |
| 1866    | 3         | 0.11%   |
| 533     | 3         | 0.11%   |
| 975     | 2         | 0.07%   |
| 333     | 2         | 0.07%   |
| 3000    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 1777    | 1         | 0.04%   |
| 1200    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 38.3%   |
| Canon               | 8         | 17.02%  |
| Brother Industries  | 7         | 14.89%  |
| Seiko Epson         | 5         | 10.64%  |
| Samsung Electronics | 4         | 8.51%   |
| Xiaomi              | 1         | 2.13%   |
| Xerox               | 1         | 2.13%   |
| STMicroelectronics  | 1         | 2.13%   |
| Kyocera             | 1         | 2.13%   |
| Unknown             | 1         | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP DeskJet 2300 series                 | 4         | 8.33%   |
| HP DeskJet 2700 series                 | 2         | 4.17%   |
| Brother DCP-1510                       | 2         | 4.17%   |
| Xiaomi MiMouse 2                       | 1         | 2.08%   |
| Xerox Phaser 3260                      | 1         | 2.08%   |
| STMicroelectronics USB Printer P       | 1         | 2.08%   |
| Seiko Epson XP-4100 Series             | 1         | 2.08%   |
| Seiko Epson Stylus NX230/SX235W Series | 1         | 2.08%   |
| Seiko Epson L3110 Series               | 1         | 2.08%   |
| Seiko Epson FX-2190IIN                 | 1         | 2.08%   |
| Seiko Epson Epson Stylus Photo 1500    | 1         | 2.08%   |
| Samsung ML-216x Series Laser Printer   | 1         | 2.08%   |
| Samsung ML-1610 Mono Laser Printer     | 1         | 2.08%   |
| Samsung M2020 Series                   | 1         | 2.08%   |
| Samsung C43x Series                    | 1         | 2.08%   |
| Kyocera FS-1116MFP                     | 1         | 2.08%   |
| HP Officejet 4630 series               | 1         | 2.08%   |
| HP Officejet 4500 G510n-z              | 1         | 2.08%   |
| HP LaserJet M14-M17                    | 1         | 2.08%   |
| HP LaserJet 4250                       | 1         | 2.08%   |
| HP LaserJet 400 M401a                  | 1         | 2.08%   |
| HP LaserJet 1300                       | 1         | 2.08%   |
| HP LaserJet 1150                       | 1         | 2.08%   |
| HP LaserJet 1020                       | 1         | 2.08%   |
| HP LaserJet 1018                       | 1         | 2.08%   |
| HP Laser 107w                          | 1         | 2.08%   |
| HP DeskJet 2620 All-in-One Printer     | 1         | 2.08%   |
| HP Color LaserJet CP1215               | 1         | 2.08%   |
| HP color LaserJet 5550                 | 1         | 2.08%   |
| Canon SELPHY CP400                     | 1         | 2.08%   |
| Canon PIXMA MX330                      | 1         | 2.08%   |
| Canon PIXMA MG2900 Series              | 1         | 2.08%   |
| Canon MF633C/635C                      | 1         | 2.08%   |
| Canon MF4100 series                    | 1         | 2.08%   |
| Canon MF3110                           | 1         | 2.08%   |
| Canon LBP6030w/6018w                   | 1         | 2.08%   |
| Canon LBP2900                          | 1         | 2.08%   |
| Brother MFC-L2710DN series             | 1         | 2.08%   |
| Brother MFC-L2700DW                    | 1         | 2.08%   |
| Brother HL-L2360D series               | 1         | 2.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 57.14%  |
| Seiko Epson     | 2         | 28.57%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 14.29%  |
| Seiko Epson ES-D200 [GT-S50]                      | 1         | 14.29%  |
| HP OfficeJet 6110                                 | 1         | 14.29%  |
| Canon CanoScan LIDE 25                            | 1         | 14.29%  |
| Canon CanoScan LiDE 110                           | 1         | 14.29%  |
| Canon CanoScan LiDE 100                           | 1         | 14.29%  |
| Canon CanoScan 4200F                              | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 922       | 21.17%  |
| IMC Networks                           | 496       | 11.39%  |
| Microdia                               | 450       | 10.33%  |
| Realtek Semiconductor                  | 349       | 8.01%   |
| Quanta                                 | 296       | 6.8%    |
| Sunplus Innovation Technology          | 286       | 6.57%   |
| Cheng Uei Precision Industry (Foxlink) | 186       | 4.27%   |
| Bison Electronics                      | 167       | 3.83%   |
| Acer                                   | 159       | 3.65%   |
| Luxvisions Innotech Limited            | 128       | 2.94%   |
| Syntek                                 | 117       | 2.69%   |
| Suyin                                  | 117       | 2.69%   |
| Lite-On Technology                     | 98        | 2.25%   |
| Apple                                  | 97        | 2.23%   |
| Logitech                               | 60        | 1.38%   |
| Alcor Micro                            | 49        | 1.13%   |
| Silicon Motion                         | 47        | 1.08%   |
| Samsung Electronics                    | 37        | 0.85%   |
| Sonix Technology                       | 34        | 0.78%   |
| Ricoh                                  | 32        | 0.73%   |
| SunplusIT                              | 22        | 0.51%   |
| Lenovo                                 | 21        | 0.48%   |
| icSpring                               | 21        | 0.48%   |
| Primax Electronics                     | 19        | 0.44%   |
| Importek                               | 15        | 0.34%   |
| ALi                                    | 14        | 0.32%   |
| Z-Star Microelectronics                | 11        | 0.25%   |
| Y Media                                | 11        | 0.25%   |
| Microsoft                              | 7         | 0.16%   |
| Sunplus Technology                     | 5         | 0.11%   |
| OmniVision Technologies                | 5         | 0.11%   |
| Intel                                  | 5         | 0.11%   |
| DigiTech                               | 4         | 0.09%   |
| Unknown                                | 4         | 0.09%   |
| WaveRider Communications               | 3         | 0.07%   |
| Unknown                                | 3         | 0.07%   |
| Sunplus IT                             | 3         | 0.07%   |
| LG Electronics                         | 3         | 0.07%   |
| Jieli Technology                       | 3         | 0.07%   |
| Goodong                                | 3         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 253       | 5.78%   |
| Chicony Integrated Camera                           | 206       | 4.71%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 135       | 3.08%   |
| IMC Networks Integrated Camera                      | 129       | 2.95%   |
| Realtek Integrated_Webcam_HD                        | 125       | 2.86%   |
| Chicony HD WebCam                                   | 103       | 2.35%   |
| Sunplus Integrated_Webcam_HD                        | 86        | 1.96%   |
| Syntek Integrated Camera                            | 76        | 1.74%   |
| Acer Integrated Camera                              | 69        | 1.58%   |
| Chicony HP HD Camera                                | 56        | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 52        | 1.19%   |
| Quanta HP HD Camera                                 | 46        | 1.05%   |
| Sunplus HD Webcam                                   | 45        | 1.03%   |
| Quanta HD User Facing                               | 44        | 1.01%   |
| IMC Networks HD Camera                              | 39        | 0.89%   |
| Samsung Galaxy series, misc. (MTP mode)             | 37        | 0.85%   |
| Quanta HP TrueVision HD Camera                      | 37        | 0.85%   |
| Chicony HD User Facing                              | 33        | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 32        | 0.73%   |
| Chicony TOSHIBA Web Camera - HD                     | 32        | 0.73%   |
| Chicony USB2.0 Camera                               | 31        | 0.71%   |
| Quanta HP Wide Vision HD Camera                     | 29        | 0.66%   |
| Luxvisions Innotech Limited Integrated Camera       | 29        | 0.66%   |
| Chicony HP TrueVision HD Camera                     | 29        | 0.66%   |
| Luxvisions Innotech Limited HP HD Camera            | 28        | 0.64%   |
| Lite-On Integrated Camera                           | 28        | 0.64%   |
| Bison Integrated Camera                             | 28        | 0.64%   |
| Sonix USB2.0 HD UVC WebCam                          | 27        | 0.62%   |
| Chicony HP Truevision HD                            | 27        | 0.62%   |
| Bison SunplusIT Integrated Camera                   | 27        | 0.62%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 27        | 0.62%   |
| Chicony HP Wide Vision HD Camera                    | 26        | 0.59%   |
| Bison HD Webcam                                     | 26        | 0.59%   |
| Realtek USB Camera                                  | 25        | 0.57%   |
| Realtek Integrated Webcam                           | 25        | 0.57%   |
| Microdia Integrated Webcam                          | 25        | 0.57%   |
| Lite-On HP HD Camera                                | 24        | 0.55%   |
| IMC Networks ov9734_azurewave_camera                | 24        | 0.55%   |
| Chicony Integrated Camera (1280x720@30)             | 24        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 24        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 299       | 30.57%  |
| Synaptics                          | 265       | 27.1%   |
| Shenzhen Goodix Technology         | 218       | 22.29%  |
| Elan Microelectronics              | 80        | 8.18%   |
| Upek                               | 34        | 3.48%   |
| AuthenTec                          | 31        | 3.17%   |
| LighTuning Technology              | 26        | 2.66%   |
| Realtek USB2.0 Finger Print Bridge | 10        | 1.02%   |
| STMicroelectronics                 | 5         | 0.51%   |
| Samsung Electronics                | 3         | 0.31%   |
| HOLTEK                             | 3         | 0.31%   |
| Focal-systems.Corp                 | 3         | 0.31%   |
| DigitalPersona                     | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 161       | 16.46%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 81        | 8.28%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 70        | 7.16%   |
| Elan ELAN:ARM-M4                                                           | 47        | 4.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 42        | 4.29%   |
| Elan ELAN:Fingerprint                                                      | 33        | 3.37%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 32        | 3.27%   |
| Shenzhen Goodix FingerPrint                                                | 30        | 3.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 27        | 2.76%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 27        | 2.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 2.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 26        | 2.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 26        | 2.66%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 23        | 2.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 22        | 2.25%   |
| Validity Sensors VFS491                                                    | 21        | 2.15%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 2.15%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 1.94%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 1.74%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 16        | 1.64%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 14        | 1.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.33%   |
| Synaptics UWP WBDI Device                                                  | 13        | 1.33%   |
| AuthenTec Fingerprint Sensor                                               | 13        | 1.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.23%   |
| Synaptics WBDI                                                             | 10        | 1.02%   |
| Synaptics UWP WBDI                                                         | 10        | 1.02%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 10        | 1.02%   |
| Unknown                                                                    | 9         | 0.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 0.72%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.72%   |
| AuthenTec AES2810                                                          | 7         | 0.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.61%   |
| Synaptics  WBDI                                                            | 6         | 0.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.61%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 0.51%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.41%   |
| AuthenTec AES1600                                                          | 4         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 215       | 55.99%  |
| Alcor Micro               | 105       | 27.34%  |
| O2 Micro                  | 19        | 4.95%   |
| Upek                      | 14        | 3.65%   |
| Gemalto (was Gemplus)     | 8         | 2.08%   |
| Lenovo                    | 6         | 1.56%   |
| Watchdata                 | 2         | 0.52%   |
| SCM Microsystems          | 2         | 0.52%   |
| OmniKey                   | 2         | 0.52%   |
| Chicony Electronics       | 2         | 0.52%   |
| Aladdin Knowledge Systems | 2         | 0.52%   |
| Reiner SCT Kartensysteme  | 1         | 0.26%   |
| NXP Semiconductors        | 1         | 0.26%   |
| Giesecke & Devrient       | 1         | 0.26%   |
| Fujitsu Siemens Computers | 1         | 0.26%   |
| Cherry                    | 1         | 0.26%   |
| C3PO                      | 1         | 0.26%   |
| Aktiv                     | 1         | 0.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 105       | 27.34%  |
| Broadcom 58200                                                               | 77        | 20.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 16.67%  |
| Broadcom 5880                                                                | 47        | 12.24%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 7.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 4.95%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 3.65%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 1.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.56%   |
| Watchdata USB Key                                                            | 2         | 0.52%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.52%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.52%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.52%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.26%   |
| OmniKey CardMan 4321                                                         | 1         | 0.26%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.26%   |
| NXP Semiconductors PR533                                                     | 1         | 0.26%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.26%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.26%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.26%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.26%   |
| C3PO LTC31v2                                                                 | 1         | 0.26%   |
| Aktiv Rutoken lite                                                           | 1         | 0.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2716      | 56.65%  |
| 1     | 1638      | 34.17%  |
| 2     | 388       | 8.09%   |
| 3     | 44        | 0.92%   |
| 5     | 3         | 0.06%   |
| 4     | 2         | 0.04%   |
| 9     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 955       | 37.58%  |
| Graphics card            | 600       | 23.61%  |
| Chipcard                 | 359       | 14.13%  |
| Net/wireless             | 204       | 8.03%   |
| Camera                   | 149       | 5.86%   |
| Multimedia controller    | 80        | 3.15%   |
| Bluetooth                | 61        | 2.4%    |
| Storage                  | 33        | 1.3%    |
| Sound                    | 33        | 1.3%    |
| Card reader              | 23        | 0.91%   |
| Net/ethernet             | 16        | 0.63%   |
| Communication controller | 14        | 0.55%   |
| Network                  | 10        | 0.39%   |
| Modem                    | 2         | 0.08%   |
| Flash memory             | 2         | 0.08%   |

