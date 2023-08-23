Linux in Taiwan - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Taiwan.

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

Total: 333

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 00010C A00                  | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| Altos         | BrainSphere P10 F7          | [8608df7a38](https://linux-hardware.org/?probe=8608df7a38) | Jul 20, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [bc805d82a7](https://linux-hardware.org/?probe=bc805d82a7) | Jul 13, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [36b6c49552](https://linux-hardware.org/?probe=36b6c49552) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [ffa5984711](https://linux-hardware.org/?probe=ffa5984711) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Intel         | X99                         | [81dbd5c4f0](https://linux-hardware.org/?probe=81dbd5c4f0) | Jul 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | X370 Killer SLI             | [10939cb152](https://linux-hardware.org/?probe=10939cb152) | Jun 20, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| MSI           | B250M MORTAR ARCTIC         | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| MSI           | H97 GAMING 3                | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [936b06e11f](https://linux-hardware.org/?probe=936b06e11f) | May 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [2adc02040e](https://linux-hardware.org/?probe=2adc02040e) | May 21, 2023 |
| Win elemen... | M600                        | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Win elemen... | M600                        | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [867e98f955](https://linux-hardware.org/?probe=867e98f955) | May 05, 2023 |
| MSI           | H55M-P31                    | [386b720202](https://linux-hardware.org/?probe=386b720202) | May 04, 2023 |
| Acer          | Veriton M2630G V:1.0        | [7ffa9c83d7](https://linux-hardware.org/?probe=7ffa9c83d7) | May 03, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| HP            | 83E2                        | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASRock        | X300M-STX                   | [4a8d662bee](https://linux-hardware.org/?probe=4a8d662bee) | Apr 25, 2023 |
| Gigabyte      | H81N                        | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| Acer          | Predator G3610              | [3d1841fa41](https://linux-hardware.org/?probe=3d1841fa41) | Apr 17, 2023 |
| Acer          | EG43LMK                     | [78b389b848](https://linux-hardware.org/?probe=78b389b848) | Apr 15, 2023 |
| Acer          | Predator G3610              | [d49e4d680c](https://linux-hardware.org/?probe=d49e4d680c) | Apr 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Win elemen... | M600                        | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | F2A78M-DS2                  | [0528b2df2b](https://linux-hardware.org/?probe=0528b2df2b) | Apr 01, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| ASRock        | N68-GS4/USB3 FX             | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| ASUSTek       | H110M-K D3                  | [24a568ad05](https://linux-hardware.org/?probe=24a568ad05) | Mar 25, 2023 |
| MSI           | H55M-P31                    | [07a5228600](https://linux-hardware.org/?probe=07a5228600) | Mar 25, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [b03324de35](https://linux-hardware.org/?probe=b03324de35) | Mar 24, 2023 |
| Gigabyte      | B75N                        | [8a16ffed3b](https://linux-hardware.org/?probe=8a16ffed3b) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| OEM           | B85 JHS359                  | [1d5d7e95fc](https://linux-hardware.org/?probe=1d5d7e95fc) | Mar 16, 2023 |
| Gigabyte      | G31M-ES2L                   | [f5535f53dc](https://linux-hardware.org/?probe=f5535f53dc) | Mar 08, 2023 |
| ASUSTek       | H81M-E                      | [fc1a09013d](https://linux-hardware.org/?probe=fc1a09013d) | Mar 05, 2023 |
| MSI           | MEG X670E ACE               | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| ASRock        | X300M-STX                   | [061edbf583](https://linux-hardware.org/?probe=061edbf583) | Mar 01, 2023 |
| ASRock        | X300M-STX                   | [97a1558878](https://linux-hardware.org/?probe=97a1558878) | Feb 25, 2023 |
| Maxtang       | EHL30 V1.0                  | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7f895dc97f](https://linux-hardware.org/?probe=7f895dc97f) | Feb 04, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [9e9deedf0d](https://linux-hardware.org/?probe=9e9deedf0d) | Jan 31, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | H81N                        | [e7cf6a4216](https://linux-hardware.org/?probe=e7cf6a4216) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Acer          | Aspire XC-105               | [8192fe90a8](https://linux-hardware.org/?probe=8192fe90a8) | Jan 19, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| Unknown       | Unknown                     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| ASUSTek       | PRIME H510M-K               | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| ASUSTek       | CM1530                      | [3990cff263](https://linux-hardware.org/?probe=3990cff263) | Dec 06, 2022 |
| Dell          | 0NNFGG A00                  | [b955357ccc](https://linux-hardware.org/?probe=b955357ccc) | Dec 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [580b716020](https://linux-hardware.org/?probe=580b716020) | Dec 03, 2022 |
| ASUSTek       | Z97-K                       | [52aaeb537b](https://linux-hardware.org/?probe=52aaeb537b) | Dec 03, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Dell          | 0XJ5V0 A03                  | [b954e4c174](https://linux-hardware.org/?probe=b954e4c174) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [aea7b4c016](https://linux-hardware.org/?probe=aea7b4c016) | Nov 23, 2022 |
| Gigabyte      | Z490 AORUS PRO AX           | [abe3da973c](https://linux-hardware.org/?probe=abe3da973c) | Nov 19, 2022 |
| Intel         | Burnside                    | [5db283bd1f](https://linux-hardware.org/?probe=5db283bd1f) | Nov 17, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| MSI           | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| MSI           | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| HP            | 1589                        | [a6be3ee931](https://linux-hardware.org/?probe=a6be3ee931) | Oct 17, 2022 |
| HP            | 1589                        | [c36aa260eb](https://linux-hardware.org/?probe=c36aa260eb) | Oct 17, 2022 |
| ASUSTek       | X99-A/USB                   | [11fc608e0a](https://linux-hardware.org/?probe=11fc608e0a) | Oct 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5c45d7b1bf](https://linux-hardware.org/?probe=5c45d7b1bf) | Oct 09, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0d7188c951](https://linux-hardware.org/?probe=0d7188c951) | Oct 03, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [dbe024bea9](https://linux-hardware.org/?probe=dbe024bea9) | Sep 16, 2022 |
| DNI           | SNDTP-1513N 5508015890      | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [96a87ada26](https://linux-hardware.org/?probe=96a87ada26) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [aaf726faa0](https://linux-hardware.org/?probe=aaf726faa0) | Aug 20, 2022 |
| ASRock        | B550M-ITX/ac                | [8898e9247d](https://linux-hardware.org/?probe=8898e9247d) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [2d41c9a29f](https://linux-hardware.org/?probe=2d41c9a29f) | Aug 08, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [21d06392bc](https://linux-hardware.org/?probe=21d06392bc) | Aug 06, 2022 |
| Gigabyte      | B550M DS3H                  | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [6f083e1754](https://linux-hardware.org/?probe=6f083e1754) | Jul 27, 2022 |
| Gigabyte      | H310MSTX-HD3-CF             | [13e7ed20e1](https://linux-hardware.org/?probe=13e7ed20e1) | Jul 27, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d88edfec1f](https://linux-hardware.org/?probe=d88edfec1f) | Jul 20, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f32b12f921](https://linux-hardware.org/?probe=f32b12f921) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [11fc460e29](https://linux-hardware.org/?probe=11fc460e29) | Jul 13, 2022 |
| MSI           | H81M-P33                    | [e523b324e6](https://linux-hardware.org/?probe=e523b324e6) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [32e2995911](https://linux-hardware.org/?probe=32e2995911) | Jun 30, 2022 |
| MSI           | H81M-P33                    | [1a0e20ab20](https://linux-hardware.org/?probe=1a0e20ab20) | Jun 29, 2022 |
| MSI           | H81M-P33                    | [e25d17a838](https://linux-hardware.org/?probe=e25d17a838) | Jun 25, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [39cc29c976](https://linux-hardware.org/?probe=39cc29c976) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d610c245f8](https://linux-hardware.org/?probe=d610c245f8) | Jun 22, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [73c4749082](https://linux-hardware.org/?probe=73c4749082) | Jun 10, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | [2966cd34b8](https://linux-hardware.org/?probe=2966cd34b8) | May 31, 2022 |
| MSI           | B150M BAZOOKA               | [b8ec3bee43](https://linux-hardware.org/?probe=b8ec3bee43) | May 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c8abb0fed](https://linux-hardware.org/?probe=2c8abb0fed) | May 12, 2022 |
| Ruckus Wir... | SCG-100                     | [781560aa15](https://linux-hardware.org/?probe=781560aa15) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [288bb26592](https://linux-hardware.org/?probe=288bb26592) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| Dell          | Precision 3260              | [70a8481a89](https://linux-hardware.org/?probe=70a8481a89) | Apr 19, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [9d2aeecf05](https://linux-hardware.org/?probe=9d2aeecf05) | Apr 15, 2022 |
| Gigabyte      | B75M-D3H                    | [79aee125b7](https://linux-hardware.org/?probe=79aee125b7) | Apr 05, 2022 |
| ASUSTek       | M3A78-EMH HDMI              | [4462ffed73](https://linux-hardware.org/?probe=4462ffed73) | Apr 01, 2022 |
| Gigabyte      | EP31-DS3L                   | [7a4dfc156e](https://linux-hardware.org/?probe=7a4dfc156e) | Mar 28, 2022 |
| Gigabyte      | X570S AERO G                | [97cfd592c5](https://linux-hardware.org/?probe=97cfd592c5) | Mar 22, 2022 |
| ASUSTek       | P8H77-M PRO                 | [f7ee97d348](https://linux-hardware.org/?probe=f7ee97d348) | Mar 16, 2022 |
| ASRock        | X300M-STX                   | [5b18945822](https://linux-hardware.org/?probe=5b18945822) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [8d52e31d86](https://linux-hardware.org/?probe=8d52e31d86) | Mar 09, 2022 |
| ASRock        | A300M-STX                   | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASUSTek       | B75M-PLUS                   | [c408f72a53](https://linux-hardware.org/?probe=c408f72a53) | Feb 23, 2022 |
| ASRock        | H81M-ITX                    | [bf52168e79](https://linux-hardware.org/?probe=bf52168e79) | Feb 14, 2022 |
| ASUSTek       | CM6630_CM6730_CM6830        | [bb588fd423](https://linux-hardware.org/?probe=bb588fd423) | Feb 07, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [589137e95b](https://linux-hardware.org/?probe=589137e95b) | Feb 02, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| ASUSTek       | P5P41T/USB3                 | [8db65bef56](https://linux-hardware.org/?probe=8db65bef56) | Jan 20, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [8eec04fc92](https://linux-hardware.org/?probe=8eec04fc92) | Dec 29, 2021 |
| DFI           | HD330-Q87CR                 | [000e53fce1](https://linux-hardware.org/?probe=000e53fce1) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f8a6ac527d](https://linux-hardware.org/?probe=f8a6ac527d) | Dec 27, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [85bcddc2e5](https://linux-hardware.org/?probe=85bcddc2e5) | Dec 27, 2021 |
| Huanan        | B85                         | [d2b55c013c](https://linux-hardware.org/?probe=d2b55c013c) | Dec 07, 2021 |
| Acer          | EG43LMK                     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8fb57be688](https://linux-hardware.org/?probe=8fb57be688) | Nov 22, 2021 |
| MSI           | PRO Z690-A DDR4             | [ae15f235e1](https://linux-hardware.org/?probe=ae15f235e1) | Nov 20, 2021 |
| ASRock        | G41C-VS                     | [e4a0a0c2c1](https://linux-hardware.org/?probe=e4a0a0c2c1) | Nov 19, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | [edc27953c6](https://linux-hardware.org/?probe=edc27953c6) | Oct 28, 2021 |
| eMachines     | EMCP73VT-PM                 | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| ASUSTek       | PRIME B350M-A               | [f20f2bfc32](https://linux-hardware.org/?probe=f20f2bfc32) | Oct 26, 2021 |
| eMachines     | EMCP73VT-PM                 | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| PANSHI        | B85-S1 V1.0                 | [963f2f28d4](https://linux-hardware.org/?probe=963f2f28d4) | Oct 24, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| HP            | 84FD 10                     | [fb32fc7215](https://linux-hardware.org/?probe=fb32fc7215) | Oct 14, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [caeaeaddf2](https://linux-hardware.org/?probe=caeaeaddf2) | Oct 12, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [eef22ec3df](https://linux-hardware.org/?probe=eef22ec3df) | Oct 10, 2021 |
| HP            | 21D0                        | [4fccb60381](https://linux-hardware.org/?probe=4fccb60381) | Oct 08, 2021 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [4b370353e4](https://linux-hardware.org/?probe=4b370353e4) | Sep 29, 2021 |
| Gigabyte      | H81M-H                      | [b961548815](https://linux-hardware.org/?probe=b961548815) | Sep 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [7114ee3f72](https://linux-hardware.org/?probe=7114ee3f72) | Sep 13, 2021 |
| Lenovo        | ThinkCentre M58 7627AA9     | [e5bedff47d](https://linux-hardware.org/?probe=e5bedff47d) | Aug 29, 2021 |
| HP            | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | H61-PLUS                    | [806118d8b3](https://linux-hardware.org/?probe=806118d8b3) | Aug 22, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [51947c0182](https://linux-hardware.org/?probe=51947c0182) | Aug 07, 2021 |
| Gigabyte      | H110M-H-CF                  | [37ac6809ad](https://linux-hardware.org/?probe=37ac6809ad) | Jul 31, 2021 |
| MSI           | B250M MORTAR                | [6c6e37fbfe](https://linux-hardware.org/?probe=6c6e37fbfe) | Jul 31, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a8c5113f4c](https://linux-hardware.org/?probe=a8c5113f4c) | Jul 06, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | [e014f9e41f](https://linux-hardware.org/?probe=e014f9e41f) | Jul 05, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [42090bac96](https://linux-hardware.org/?probe=42090bac96) | Jun 27, 2021 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [cf9f5ab2b6](https://linux-hardware.org/?probe=cf9f5ab2b6) | Jun 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [98be9faa06](https://linux-hardware.org/?probe=98be9faa06) | Jun 21, 2021 |
| Supermicro    | C9Z490-PGW                  | [9b89e87202](https://linux-hardware.org/?probe=9b89e87202) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [18b2fc7e21](https://linux-hardware.org/?probe=18b2fc7e21) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [db99ef3085](https://linux-hardware.org/?probe=db99ef3085) | Jun 14, 2021 |
| Intel         | SHARKBAY                    | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| Dell          | 05GD68 A00                  | [b87ca56da6](https://linux-hardware.org/?probe=b87ca56da6) | Jun 11, 2021 |
| ASUSTek       | P5P41T/USB3                 | [be02c1622c](https://linux-hardware.org/?probe=be02c1622c) | Jun 06, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [ba117fef7e](https://linux-hardware.org/?probe=ba117fef7e) | May 31, 2021 |
| ASUSTek       | P5P41T/USB3                 | [e7eca73b93](https://linux-hardware.org/?probe=e7eca73b93) | May 30, 2021 |
| Dell          | 0RY206                      | [f02982ff12](https://linux-hardware.org/?probe=f02982ff12) | May 29, 2021 |
| ASRock        | H310M-ITX/ac                | [839b20476a](https://linux-hardware.org/?probe=839b20476a) | May 29, 2021 |
| ASRock        | X300M-STX                   | [6b0f0cd327](https://linux-hardware.org/?probe=6b0f0cd327) | May 27, 2021 |
| Gigabyte      | Z390 UD                     | [bbc8131c67](https://linux-hardware.org/?probe=bbc8131c67) | May 05, 2021 |
| Lenovo        | MAHOBAY                     | [6928edc4c3](https://linux-hardware.org/?probe=6928edc4c3) | Apr 30, 2021 |
| ASRock        | H55M/USB3                   | [8041f40ea2](https://linux-hardware.org/?probe=8041f40ea2) | Apr 22, 2021 |
| ASUSTek       | P8Z68-V LX                  | [060122f540](https://linux-hardware.org/?probe=060122f540) | Apr 19, 2021 |
| HP            | 0AECh D                     | [4e2517cb92](https://linux-hardware.org/?probe=4e2517cb92) | Apr 17, 2021 |
| ASUSTek       | P8Z68-V LX                  | [f67c224c2d](https://linux-hardware.org/?probe=f67c224c2d) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3dcec36efc](https://linux-hardware.org/?probe=3dcec36efc) | Mar 24, 2021 |
| Acer          | M1930                       | [ecd09c75f9](https://linux-hardware.org/?probe=ecd09c75f9) | Mar 23, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6fed85f2b6](https://linux-hardware.org/?probe=6fed85f2b6) | Mar 21, 2021 |
| Acer          | Veriton L4630G V:1.0        | [d5413884e0](https://linux-hardware.org/?probe=d5413884e0) | Feb 15, 2021 |
| Gigabyte      | B75M-D3H                    | [626560cf30](https://linux-hardware.org/?probe=626560cf30) | Feb 04, 2021 |
| ASRock        | HM87-MXM                    | [95efd1e9a2](https://linux-hardware.org/?probe=95efd1e9a2) | Feb 04, 2021 |
| Acer          | IPIMB-AR                    | [eb7a1feeff](https://linux-hardware.org/?probe=eb7a1feeff) | Jan 25, 2021 |
| MSI           | 760GM-P23                   | [8fdb02babb](https://linux-hardware.org/?probe=8fdb02babb) | Jan 24, 2021 |
| MSI           | 760GM-P23                   | [9ebcac45bd](https://linux-hardware.org/?probe=9ebcac45bd) | Jan 24, 2021 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [ac56dd5c89](https://linux-hardware.org/?probe=ac56dd5c89) | Jan 23, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [1deb2b04c5](https://linux-hardware.org/?probe=1deb2b04c5) | Jan 21, 2021 |
| ASRock        | X300M-STX                   | [b690109a78](https://linux-hardware.org/?probe=b690109a78) | Jan 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [7ade5574be](https://linux-hardware.org/?probe=7ade5574be) | Jan 14, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [e5dc6589db](https://linux-hardware.org/?probe=e5dc6589db) | Jan 05, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| ASUSTek       | P5P41T/USB3                 | [f8f8546b66](https://linux-hardware.org/?probe=f8f8546b66) | Dec 28, 2020 |
| Gigabyte      | H310M H                     | [dfa5c13a96](https://linux-hardware.org/?probe=dfa5c13a96) | Dec 22, 2020 |
| MSI           | AM1M                        | [e7e7d1e0cc](https://linux-hardware.org/?probe=e7e7d1e0cc) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [fb4b7a114e](https://linux-hardware.org/?probe=fb4b7a114e) | Dec 14, 2020 |
| Gigabyte      | H87-HD3                     | [55f095e43d](https://linux-hardware.org/?probe=55f095e43d) | Dec 13, 2020 |
| Gigabyte      | EP43-S3L                    | [7c9b5cd232](https://linux-hardware.org/?probe=7c9b5cd232) | Nov 28, 2020 |
| Gigabyte      | EP43-S3L                    | [218d68cc94](https://linux-hardware.org/?probe=218d68cc94) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [799008f314](https://linux-hardware.org/?probe=799008f314) | Nov 26, 2020 |
| Gigabyte      | EP43-S3L                    | [c91fdcd723](https://linux-hardware.org/?probe=c91fdcd723) | Nov 26, 2020 |
| ASUSTek       | GR8 II-K                    | [dce0e65158](https://linux-hardware.org/?probe=dce0e65158) | Nov 24, 2020 |
| ASUSTek       | H97-PRO                     | [df130b5488](https://linux-hardware.org/?probe=df130b5488) | Nov 23, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [8b7818376f](https://linux-hardware.org/?probe=8b7818376f) | Nov 18, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3d64c2bcc8](https://linux-hardware.org/?probe=3d64c2bcc8) | Nov 17, 2020 |
| ASUSTek       | PRIME B250M-K               | [35bc246b54](https://linux-hardware.org/?probe=35bc246b54) | Nov 13, 2020 |
| ASRock        | HM87-MXM                    | [d47723e369](https://linux-hardware.org/?probe=d47723e369) | Nov 03, 2020 |
| Unknown       | Unknown                     | [3ed3ea4f60](https://linux-hardware.org/?probe=3ed3ea4f60) | Oct 29, 2020 |
| Unknown       | Unknown                     | [c80fe9e03a](https://linux-hardware.org/?probe=c80fe9e03a) | Oct 29, 2020 |
| Gigabyte      | B85M-D2V                    | [1f2b50c872](https://linux-hardware.org/?probe=1f2b50c872) | Oct 24, 2020 |
| Gigabyte      | B75M-D3H                    | [352ce3d09c](https://linux-hardware.org/?probe=352ce3d09c) | Oct 16, 2020 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | [8de90e5004](https://linux-hardware.org/?probe=8de90e5004) | Oct 12, 2020 |
| MSI           | B450M-A PRO MAX             | [3712afebf5](https://linux-hardware.org/?probe=3712afebf5) | Oct 09, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [605fe21a48](https://linux-hardware.org/?probe=605fe21a48) | Oct 03, 2020 |
| ASUSTek       | M4A785D-M PRO               | [c8033471fb](https://linux-hardware.org/?probe=c8033471fb) | Oct 01, 2020 |
| HP            | 339A                        | [84f1e1735f](https://linux-hardware.org/?probe=84f1e1735f) | Sep 19, 2020 |
| Dell          | 0RY206                      | [40e7b0cafb](https://linux-hardware.org/?probe=40e7b0cafb) | Sep 05, 2020 |
| ASUSTek       | B85M-K                      | [8fe74ac1ad](https://linux-hardware.org/?probe=8fe74ac1ad) | Sep 04, 2020 |
| Unknown       | Unknown                     | [e5e9a43e32](https://linux-hardware.org/?probe=e5e9a43e32) | Sep 04, 2020 |
| NEXCOM        | SKLD4-P1                    | [23c5f53c73](https://linux-hardware.org/?probe=23c5f53c73) | Sep 03, 2020 |
| NEXCOM        | SKLD4-P1                    | [e27e3df3f3](https://linux-hardware.org/?probe=e27e3df3f3) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [26c3ba8ef4](https://linux-hardware.org/?probe=26c3ba8ef4) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [066c04a858](https://linux-hardware.org/?probe=066c04a858) | Sep 02, 2020 |
| MSI           | B450M-A PRO MAX             | [e46d6617a9](https://linux-hardware.org/?probe=e46d6617a9) | Aug 28, 2020 |
| Lenovo        | 7Z74                        | [84586c4db2](https://linux-hardware.org/?probe=84586c4db2) | Aug 27, 2020 |
| ASUSTek       | B85M-K                      | [9fd11c530f](https://linux-hardware.org/?probe=9fd11c530f) | Aug 21, 2020 |
| Gigabyte      | H170-Gaming 3               | [b4bad24684](https://linux-hardware.org/?probe=b4bad24684) | Aug 21, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [67cf1d26af](https://linux-hardware.org/?probe=67cf1d26af) | Aug 12, 2020 |
| Lenovo        | 0B98401 WIN                 | [20cb7c14f8](https://linux-hardware.org/?probe=20cb7c14f8) | Jul 10, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e012c28e4a](https://linux-hardware.org/?probe=e012c28e4a) | Jul 06, 2020 |
| Gigabyte      | B75M-D3H                    | [925fdfd7c7](https://linux-hardware.org/?probe=925fdfd7c7) | Jun 16, 2020 |
| Dell          | 0RY206                      | [648bdee6ec](https://linux-hardware.org/?probe=648bdee6ec) | May 29, 2020 |
| Gigabyte      | G31M-ES2L                   | [9c2d3cb657](https://linux-hardware.org/?probe=9c2d3cb657) | May 24, 2020 |
| ASRock        | N68-GS4/USB3 FX             | [baefccea96](https://linux-hardware.org/?probe=baefccea96) | May 22, 2020 |
| Gigabyte      | B85M-D2V                    | [ec5da680aa](https://linux-hardware.org/?probe=ec5da680aa) | May 16, 2020 |
| Gigabyte      | B75M-D3H                    | [1069d9adc6](https://linux-hardware.org/?probe=1069d9adc6) | May 10, 2020 |
| Accton        | SAU5041                     | [b1efc2e064](https://linux-hardware.org/?probe=b1efc2e064) | May 07, 2020 |
| ASUSTek       | P8H77-V LE                  | [5ef719f7d8](https://linux-hardware.org/?probe=5ef719f7d8) | May 06, 2020 |
| Gigabyte      | B75M-D3H                    | [235c047618](https://linux-hardware.org/?probe=235c047618) | May 04, 2020 |
| ASUSTek       | P5Q                         | [c6681e044f](https://linux-hardware.org/?probe=c6681e044f) | May 02, 2020 |
| ASUSTek       | P5Q                         | [e620caac82](https://linux-hardware.org/?probe=e620caac82) | May 02, 2020 |
| Lenovo        | 0B98401 WIN                 | [e818900359](https://linux-hardware.org/?probe=e818900359) | May 01, 2020 |
| Lenovo        | 0B98401 WIN                 | [ef970e6611](https://linux-hardware.org/?probe=ef970e6611) | Apr 30, 2020 |
| Gigabyte      | H77M-D3H                    | [b34b605dda](https://linux-hardware.org/?probe=b34b605dda) | Apr 30, 2020 |
| Gigabyte      | B75M-D3H                    | [530e0b1725](https://linux-hardware.org/?probe=530e0b1725) | Apr 24, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [a90f89123d](https://linux-hardware.org/?probe=a90f89123d) | Apr 20, 2020 |
| Accton        | SAU5041                     | [c23eb2c1bb](https://linux-hardware.org/?probe=c23eb2c1bb) | Apr 13, 2020 |
| Unknown       | Unknown                     | [c3983e6074](https://linux-hardware.org/?probe=c3983e6074) | Mar 31, 2020 |
| Unknown       | Unknown                     | [df51a87843](https://linux-hardware.org/?probe=df51a87843) | Mar 31, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [5568d1765b](https://linux-hardware.org/?probe=5568d1765b) | Mar 30, 2020 |
| MSI           | MEG X299 CREATION           | [8112942b50](https://linux-hardware.org/?probe=8112942b50) | Mar 26, 2020 |
| Gigabyte      | Z77-D3H                     | [0a6d8786dc](https://linux-hardware.org/?probe=0a6d8786dc) | Mar 22, 2020 |
| Gigabyte      | Z77-D3H                     | [0b49d54fce](https://linux-hardware.org/?probe=0b49d54fce) | Mar 20, 2020 |
| ASUSTek       | D340MC-C                    | [e1396240d9](https://linux-hardware.org/?probe=e1396240d9) | Mar 19, 2020 |
| ASUSTek       | D840MB                      | [c2599225a3](https://linux-hardware.org/?probe=c2599225a3) | Mar 11, 2020 |
| Lenovo        | Board                       | [81650f1328](https://linux-hardware.org/?probe=81650f1328) | Mar 03, 2020 |
| MSI           | MEG X299 CREATION           | [dc2b1917fc](https://linux-hardware.org/?probe=dc2b1917fc) | Mar 02, 2020 |
| ASRock        | A300M-STX                   | [fed0334ebb](https://linux-hardware.org/?probe=fed0334ebb) | Feb 25, 2020 |
| Gigabyte      | B360 M AORUS PRO-CF         | [8b8bf9eb3c](https://linux-hardware.org/?probe=8b8bf9eb3c) | Feb 05, 2020 |
| Gigabyte      | Z68A-D3H-B3                 | [ec012fce91](https://linux-hardware.org/?probe=ec012fce91) | Jan 30, 2020 |
| ASUSTek       | M5A78L-M LE/USB3            | [871b431e0b](https://linux-hardware.org/?probe=871b431e0b) | Jan 23, 2020 |
| Gigabyte      | P55A-UD4                    | [0765c0e746](https://linux-hardware.org/?probe=0765c0e746) | Jan 23, 2020 |
| ASUSTek       | P8H61-M LX PLUS             | [e1061f8758](https://linux-hardware.org/?probe=e1061f8758) | Jan 17, 2020 |
| Dell          | 0TP412                      | [92059b060a](https://linux-hardware.org/?probe=92059b060a) | Jan 15, 2020 |
| ASUSTek       | Z87-PRO                     | [4c444b85d5](https://linux-hardware.org/?probe=4c444b85d5) | Jan 11, 2020 |
| Foxconn       | 2ADA                        | [161e031506](https://linux-hardware.org/?probe=161e031506) | Jan 11, 2020 |
| MSI           | K9N6PGM2-V2                 | [93e77f9dc3](https://linux-hardware.org/?probe=93e77f9dc3) | Dec 26, 2019 |
| MSI           | K9N6PGM2-V2                 | [7cac7cc3cc](https://linux-hardware.org/?probe=7cac7cc3cc) | Dec 26, 2019 |
| Foxconn       | 2ADA                        | [61f3387aaa](https://linux-hardware.org/?probe=61f3387aaa) | Dec 19, 2019 |
| Acer          | M1930                       | [6f798ab348](https://linux-hardware.org/?probe=6f798ab348) | Dec 16, 2019 |
| ASRock        | 960GC-GS FX                 | [3e7a8d31ef](https://linux-hardware.org/?probe=3e7a8d31ef) | Dec 03, 2019 |
| ASUSTek       | P8Z77-V LX                  | [9f10e816c5](https://linux-hardware.org/?probe=9f10e816c5) | Nov 21, 2019 |
| ASUSTek       | P8Z77-V LX                  | [ad60feb203](https://linux-hardware.org/?probe=ad60feb203) | Nov 21, 2019 |
| MSI           | P45 Platinum                | [178de664ca](https://linux-hardware.org/?probe=178de664ca) | Oct 28, 2019 |
| Lenovo        | ThinkCentre M58 7627AA9     | [4ca1d19d3a](https://linux-hardware.org/?probe=4ca1d19d3a) | Oct 18, 2019 |
| MSI           | K9N6PGM2-V2                 | [8dd08d1a97](https://linux-hardware.org/?probe=8dd08d1a97) | Oct 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [0a39f948fd](https://linux-hardware.org/?probe=0a39f948fd) | Sep 29, 2019 |
| ASRock        | H81M-ITX                    | [ce10f2cbfe](https://linux-hardware.org/?probe=ce10f2cbfe) | Sep 26, 2019 |
| ASRock        | H81M-ITX                    | [aed359375a](https://linux-hardware.org/?probe=aed359375a) | Sep 26, 2019 |
| MSI           | X399 SLI PLUS               | [b281f9ca55](https://linux-hardware.org/?probe=b281f9ca55) | Sep 15, 2019 |
| MSI           | X399 SLI PLUS               | [130f51b891](https://linux-hardware.org/?probe=130f51b891) | Sep 11, 2019 |
| MSI           | X399 SLI PLUS               | [8da6642033](https://linux-hardware.org/?probe=8da6642033) | Sep 11, 2019 |
| ASRock        | H81M-VG4 R2.0               | [a6a357de21](https://linux-hardware.org/?probe=a6a357de21) | Aug 08, 2019 |
| Gigabyte      | EX58-UD3R                   | [f5c15b4975](https://linux-hardware.org/?probe=f5c15b4975) | Aug 01, 2019 |
| ASUSTek       | P7H55-M/USB3                | [517d2f4be4](https://linux-hardware.org/?probe=517d2f4be4) | Jul 31, 2019 |
| Gigabyte      | MZGLKCH-SI                  | [0f78f0b23e](https://linux-hardware.org/?probe=0f78f0b23e) | Jul 24, 2019 |
| Unknown       | Unknown                     | [55981af24a](https://linux-hardware.org/?probe=55981af24a) | Jul 17, 2019 |
| Unknown       | Unknown                     | [efe95ef406](https://linux-hardware.org/?probe=efe95ef406) | Jul 17, 2019 |
| Unknown       | Unknown                     | [e8900d6721](https://linux-hardware.org/?probe=e8900d6721) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [087f924e20](https://linux-hardware.org/?probe=087f924e20) | Jul 15, 2019 |
| Unknown       | Unknown                     | [e58e143a7f](https://linux-hardware.org/?probe=e58e143a7f) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [683b87be0f](https://linux-hardware.org/?probe=683b87be0f) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [43db5dc346](https://linux-hardware.org/?probe=43db5dc346) | Jul 15, 2019 |
| Unknown       | Unknown                     | [4124a2b6aa](https://linux-hardware.org/?probe=4124a2b6aa) | Jul 12, 2019 |
| ASUSTek       | Z170-DELUXE                 | [093c4071fd](https://linux-hardware.org/?probe=093c4071fd) | Jul 10, 2019 |
| Unknown       | Unknown                     | [25b6099cd2](https://linux-hardware.org/?probe=25b6099cd2) | Jul 09, 2019 |
| Unknown       | Unknown                     | [c9ae4d965c](https://linux-hardware.org/?probe=c9ae4d965c) | Jul 09, 2019 |
| Unknown       | Unknown                     | [1e3ba128f6](https://linux-hardware.org/?probe=1e3ba128f6) | Jul 08, 2019 |
| ASUSTek       | M5A78L-M LE/USB3            | [44650751a9](https://linux-hardware.org/?probe=44650751a9) | Jul 04, 2019 |
| Gigabyte      | B450M GAMING                | [154fbbffd3](https://linux-hardware.org/?probe=154fbbffd3) | Jul 04, 2019 |
| Gigabyte      | G1.Sniper Z97               | [7552a8cb4c](https://linux-hardware.org/?probe=7552a8cb4c) | Jun 20, 2019 |
| Gigabyte      | GA-M56S-S3                  | [21fb8f59a4](https://linux-hardware.org/?probe=21fb8f59a4) | Jun 07, 2019 |
| Gigabyte      | Z370P D3-CF                 | [a210ba04d3](https://linux-hardware.org/?probe=a210ba04d3) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d2e0085e5f](https://linux-hardware.org/?probe=d2e0085e5f) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [f96a5f5393](https://linux-hardware.org/?probe=f96a5f5393) | Jun 04, 2019 |
| ASUSTek       | WS X299 PRO                 | [510ae49df2](https://linux-hardware.org/?probe=510ae49df2) | May 22, 2019 |
| Acer          | Veriton M6620G v1.0         | [4f1a9afa27](https://linux-hardware.org/?probe=4f1a9afa27) | May 21, 2019 |
| Gigabyte      | Z170M-HERO-CF               | [0d7f7b5382](https://linux-hardware.org/?probe=0d7f7b5382) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [d5403368f6](https://linux-hardware.org/?probe=d5403368f6) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [1c42aae9b4](https://linux-hardware.org/?probe=1c42aae9b4) | Apr 27, 2019 |
| Gigabyte      | G41M-Combo                  | [f70f72098a](https://linux-hardware.org/?probe=f70f72098a) | Apr 21, 2019 |
| ASRock        | 960GC-GS FX                 | [2ab4402059](https://linux-hardware.org/?probe=2ab4402059) | Apr 13, 2019 |
| MSI           | Z68MA-G45                   | [c3e718dfec](https://linux-hardware.org/?probe=c3e718dfec) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | [d9b1ec3c37](https://linux-hardware.org/?probe=d9b1ec3c37) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | [d61584bf4e](https://linux-hardware.org/?probe=d61584bf4e) | Apr 09, 2019 |
| ASRock        | 960GC-GS FX                 | [925ee04320](https://linux-hardware.org/?probe=925ee04320) | Apr 07, 2019 |
| ASUSTek       | BM1AF_BP1AF_BM6AF           | [dcf80c3fe6](https://linux-hardware.org/?probe=dcf80c3fe6) | Apr 03, 2019 |
| Gigabyte      | F2A88X-D3H                  | [d9a29354a7](https://linux-hardware.org/?probe=d9a29354a7) | Feb 19, 2019 |
| Gigabyte      | F2A88X-D3H                  | [a3a29982fd](https://linux-hardware.org/?probe=a3a29982fd) | Feb 19, 2019 |
| ASRock        | H310M-ITX/ac                | [0ae0ba17de](https://linux-hardware.org/?probe=0ae0ba17de) | Feb 02, 2019 |
| Gigabyte      | H87M-D3H                    | [dd3cc86ec3](https://linux-hardware.org/?probe=dd3cc86ec3) | Jan 29, 2019 |
| ASRock        | H310M-ITX/ac                | [899220711e](https://linux-hardware.org/?probe=899220711e) | Jan 25, 2019 |
| Gigabyte      | H87M-D3H                    | [90a29cddfa](https://linux-hardware.org/?probe=90a29cddfa) | Dec 21, 2018 |
| ASRock        | H310M-STX/COM               | [d350550408](https://linux-hardware.org/?probe=d350550408) | Dec 07, 2018 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [3eaee61f5f](https://linux-hardware.org/?probe=3eaee61f5f) | Nov 29, 2018 |
| Gigabyte      | H310 D3                     | [eb95ee1f27](https://linux-hardware.org/?probe=eb95ee1f27) | Nov 20, 2018 |
| MSI           | FM2-A75MA-E35               | [d4730289c0](https://linux-hardware.org/?probe=d4730289c0) | Nov 12, 2018 |
| ASUSTek       | P8H67                       | [821e6f68ce](https://linux-hardware.org/?probe=821e6f68ce) | Sep 17, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 18.04       | 50       | 19.92%  |
| Ubuntu 20.04       | 36       | 14.34%  |
| Ubuntu 22.04       | 11       | 4.38%   |
| Debian 11          | 10       | 3.98%   |
| OpenMandriva 4.2   | 9        | 3.59%   |
| OpenMandriva 23.01 | 6        | 2.39%   |
| Linux Mint 20.3    | 6        | 2.39%   |
| Arch Rolling       | 6        | 2.39%   |
| Xubuntu 18.04      | 5        | 1.99%   |
| Xubuntu 20.04      | 4        | 1.59%   |
| Pop!_OS 20.04      | 4        | 1.59%   |
| OpenMandriva 4.3   | 4        | 1.59%   |
| OpenMandriva 23.03 | 4        | 1.59%   |
| Ubuntu 21.10       | 3        | 1.2%    |
| Ubuntu 19.04       | 3        | 1.2%    |
| Kubuntu 20.04      | 3        | 1.2%    |
| Fedora 38          | 3        | 1.2%    |
| Zorin 16           | 2        | 0.8%    |
| Ubuntu 23.04       | 2        | 0.8%    |
| Ubuntu 22.10       | 2        | 0.8%    |
| Ubuntu 20.10       | 2        | 0.8%    |
| Ubuntu 19.10       | 2        | 0.8%    |
| Ubuntu 18.10       | 2        | 0.8%    |
| Ubuntu 16.04       | 2        | 0.8%    |
| ROSA R11           | 2        | 0.8%    |
| openSUSE Leap-15.0 | 2        | 0.8%    |
| OpenMandriva 4.90  | 2        | 0.8%    |
| Linux Mint 20.2    | 2        | 0.8%    |
| KDE neon 20.04     | 2        | 0.8%    |
| Kali 2020.2        | 2        | 0.8%    |
| Fedora 37          | 2        | 0.8%    |
| Fedora 33          | 2        | 0.8%    |
| Endless 3.5.4      | 2        | 0.8%    |
| Debian 10          | 2        | 0.8%    |
| Zorin 15           | 1        | 0.4%    |
| Xubuntu 22.04      | 1        | 0.4%    |
| Xubuntu 19.04      | 1        | 0.4%    |
| Xubuntu 16.04      | 1        | 0.4%    |
| Ubuntu Unity 16.04 | 1        | 0.4%    |
| Ubuntu MATE 22.04  | 1        | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 113      | 45.93%  |
| OpenMandriva  | 24       | 9.76%   |
| Linux Mint    | 13       | 5.28%   |
| Debian        | 13       | 5.28%   |
| Xubuntu       | 12       | 4.88%   |
| Fedora        | 12       | 4.88%   |
| Manjaro       | 7        | 2.85%   |
| Arch          | 7        | 2.85%   |
| Pop!_OS       | 5        | 2.03%   |
| Kubuntu       | 5        | 2.03%   |
| Endless       | 4        | 1.63%   |
| Zorin         | 3        | 1.22%   |
| Ubuntu MATE   | 3        | 1.22%   |
| openSUSE      | 3        | 1.22%   |
| Kali          | 3        | 1.22%   |
| ROSA          | 2        | 0.81%   |
| KDE neon      | 2        | 0.81%   |
| Gentoo        | 2        | 0.81%   |
| Clear Linux   | 2        | 0.81%   |
| CentOS        | 2        | 0.81%   |
| Ubuntu Unity  | 1        | 0.41%   |
| Ubuntu Budgie | 1        | 0.41%   |
| NixOS         | 1        | 0.41%   |
| Mageia        | 1        | 0.41%   |
| Lubuntu       | 1        | 0.41%   |
| Lilidog       | 1        | 0.41%   |
| Garuda Linux  | 1        | 0.41%   |
| BlackPanther  | 1        | 0.41%   |
| ArcoLinux     | 1        | 0.41%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 2.56%   |
| 6.1.1-desktop-1omv2290   | 6        | 2.2%    |
| 5.4.0-42-generic         | 5        | 1.83%   |
| 5.8.0-50-generic         | 4        | 1.47%   |
| 5.4.0-45-generic         | 4        | 1.47%   |
| 5.4.0-28-generic         | 4        | 1.47%   |
| 5.16.7-desktop-1omv4003  | 4        | 1.47%   |
| 6.2.6-desktop-1omv2390   | 3        | 1.1%    |
| 5.4.0-58-generic         | 3        | 1.1%    |
| 5.11.0-27-generic        | 3        | 1.1%    |
| 5.0.0-37-generic         | 3        | 1.1%    |
| 5.0.0-23-generic         | 3        | 1.1%    |
| 4.15.0-66-generic        | 3        | 1.1%    |
| 4.15.0-29-generic        | 3        | 1.1%    |
| 5.8.0-55-generic         | 2        | 0.73%   |
| 5.8.0-43-generic         | 2        | 0.73%   |
| 5.8.0-38-generic         | 2        | 0.73%   |
| 5.5.0-kali2-amd64        | 2        | 0.73%   |
| 5.4.0-91-generic         | 2        | 0.73%   |
| 5.4.0-81-generic         | 2        | 0.73%   |
| 5.4.0-80-generic         | 2        | 0.73%   |
| 5.4.0-77-generic         | 2        | 0.73%   |
| 5.4.0-66-generic         | 2        | 0.73%   |
| 5.4.0-54-generic         | 2        | 0.73%   |
| 5.4.0-53-generic         | 2        | 0.73%   |
| 5.4.0-48-generic         | 2        | 0.73%   |
| 5.4.0-122-generic        | 2        | 0.73%   |
| 5.3.0-40-generic         | 2        | 0.73%   |
| 5.3.0-28-generic         | 2        | 0.73%   |
| 5.19.0-46-generic        | 2        | 0.73%   |
| 5.19.0-38-generic        | 2        | 0.73%   |
| 5.18.12-desktop-3omv4090 | 2        | 0.73%   |
| 5.15.83-1-pve            | 2        | 0.73%   |
| 5.15.0-53-generic        | 2        | 0.73%   |
| 5.15.0-52-generic        | 2        | 0.73%   |
| 5.15.0-48-generic        | 2        | 0.73%   |
| 5.13.0-35-generic        | 2        | 0.73%   |
| 5.13.0-30-generic        | 2        | 0.73%   |
| 5.11.12-desktop-1omv4002 | 2        | 0.73%   |
| 5.11.0-43-generic        | 2        | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 53       | 20.7%   |
| 4.15.0  | 27       | 10.55%  |
| 5.8.0   | 13       | 5.08%   |
| 5.15.0  | 12       | 4.69%   |
| 5.11.0  | 11       | 4.3%    |
| 5.0.0   | 11       | 4.3%    |
| 4.18.0  | 10       | 3.91%   |
| 5.3.0   | 9        | 3.52%   |
| 5.19.0  | 8        | 3.13%   |
| 5.13.0  | 8        | 3.13%   |
| 5.10.14 | 7        | 2.73%   |
| 6.1.1   | 6        | 2.34%   |
| 5.16.7  | 4        | 1.56%   |
| 5.10.0  | 4        | 1.56%   |
| 6.2.6   | 3        | 1.17%   |
| 6.2.0   | 3        | 1.17%   |
| 6.2.2   | 2        | 0.78%   |
| 6.2.12  | 2        | 0.78%   |
| 5.5.0   | 2        | 0.78%   |
| 5.18.12 | 2        | 0.78%   |
| 5.15.83 | 2        | 0.78%   |
| 5.15.23 | 2        | 0.78%   |
| 5.11.12 | 2        | 0.78%   |
| 4.19.57 | 2        | 0.78%   |
| 4.19.0  | 2        | 0.78%   |
| 4.12.14 | 2        | 0.78%   |
| 6.4.0   | 1        | 0.39%   |
| 6.3.9   | 1        | 0.39%   |
| 6.3.5   | 1        | 0.39%   |
| 6.3.2   | 1        | 0.39%   |
| 6.3.12  | 1        | 0.39%   |
| 6.2.15  | 1        | 0.39%   |
| 6.2.11  | 1        | 0.39%   |
| 6.2.10  | 1        | 0.39%   |
| 6.2.1   | 1        | 0.39%   |
| 6.1.31  | 1        | 0.39%   |
| 6.1.0   | 1        | 0.39%   |
| 6.0.15  | 1        | 0.39%   |
| 6.0.12  | 1        | 0.39%   |
| 6.0.11  | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 53       | 20.78%  |
| 4.15    | 27       | 10.59%  |
| 5.15    | 22       | 8.63%   |
| 5.8     | 15       | 5.88%   |
| 5.10    | 15       | 5.88%   |
| 6.2     | 14       | 5.49%   |
| 5.11    | 14       | 5.49%   |
| 5.0     | 12       | 4.71%   |
| 4.18    | 11       | 4.31%   |
| 5.3     | 9        | 3.53%   |
| 5.19    | 9        | 3.53%   |
| 6.1     | 8        | 3.14%   |
| 5.13    | 8        | 3.14%   |
| 5.16    | 6        | 2.35%   |
| 6.0     | 5        | 1.96%   |
| 6.3     | 4        | 1.57%   |
| 4.19    | 4        | 1.57%   |
| 5.5     | 3        | 1.18%   |
| 5.18    | 3        | 1.18%   |
| 4.12    | 2        | 0.78%   |
| 6.4     | 1        | 0.39%   |
| 5.9     | 1        | 0.39%   |
| 5.7     | 1        | 0.39%   |
| 5.17    | 1        | 0.39%   |
| 5.14    | 1        | 0.39%   |
| 5.12    | 1        | 0.39%   |
| 5.1     | 1        | 0.39%   |
| 4.9     | 1        | 0.39%   |
| 4.4     | 1        | 0.39%   |
| 4.14    | 1        | 0.39%   |
| 3.10    | 1        | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 237      | 97.13%  |
| i686    | 6        | 2.46%   |
| riscv64 | 1        | 0.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 112      | 45.16%  |
| Unknown          | 50       | 20.16%  |
| KDE5             | 40       | 16.13%  |
| XFCE             | 17       | 6.85%   |
| Cinnamon         | 6        | 2.42%   |
| X-Cinnamon       | 5        | 2.02%   |
| MATE             | 5        | 2.02%   |
| KDE              | 3        | 1.21%   |
| LXDE             | 2        | 0.81%   |
| Unity            | 1        | 0.4%    |
| LXQt             | 1        | 0.4%    |
| lightdm-xsession | 1        | 0.4%    |
| KDE4             | 1        | 0.4%    |
| i3               | 1        | 0.4%    |
| Hyprland         | 1        | 0.4%    |
| GNOME Classic    | 1        | 0.4%    |
| Budgie           | 1        | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 182      | 72.8%   |
| Wayland | 31       | 12.4%   |
| Unknown | 27       | 10.8%   |
| Tty     | 10       | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 123      | 49.6%   |
| GDM     | 38       | 15.32%  |
| SDDM    | 37       | 14.92%  |
| GDM3    | 25       | 10.08%  |
| LightDM | 15       | 6.05%   |
| TDM     | 8        | 3.23%   |
| KDM     | 2        | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 95       | 38.46%  |
| zh_TW   | 87       | 35.22%  |
| Unknown | 47       | 19.03%  |
| C       | 6        | 2.43%   |
| zh_HK   | 2        | 0.81%   |
| en_HK   | 2        | 0.81%   |
| en_GB   | 2        | 0.81%   |
| zh_CN   | 1        | 0.4%    |
| it_IT   | 1        | 0.4%    |
| es_ES   | 1        | 0.4%    |
| en_SG   | 1        | 0.4%    |
| en_PH   | 1        | 0.4%    |
| en_AU   | 1        | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 129      | 52.02%  |
| BIOS | 119      | 47.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 182      | 74.29%  |
| Btrfs   | 22       | 8.98%   |
| Overlay | 19       | 7.76%   |
| Unknown | 7        | 2.86%   |
| Xfs     | 5        | 2.04%   |
| Tmpfs   | 5        | 2.04%   |
| Ext2    | 3        | 1.22%   |
| Rootfs  | 1        | 0.41%   |
| Ext3    | 1        | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 117      | 46.99%  |
| GPT     | 109      | 43.78%  |
| MBR     | 23       | 9.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 188      | 76.11%  |
| Yes       | 59       | 23.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 56.68%  |
| Yes       | 107      | 43.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 76       | 31.15%  |
| Gigabyte Technology | 61       | 25%     |
| MSI                 | 22       | 9.02%   |
| ASRock              | 20       | 8.2%    |
| Acer                | 14       | 5.74%   |
| Dell                | 9        | 3.69%   |
| Hewlett-Packard     | 8        | 3.28%   |
| Unknown             | 8        | 3.28%   |
| Lenovo              | 6        | 2.46%   |
| Intel               | 3        | 1.23%   |
| Win element         | 1        | 0.41%   |
| Supermicro          | 1        | 0.41%   |
| Ruckus Wireless     | 1        | 0.41%   |
| PANSHI              | 1        | 0.41%   |
| OEM                 | 1        | 0.41%   |
| NEXCOM              | 1        | 0.41%   |
| Maxtang             | 1        | 0.41%   |
| Huanan              | 1        | 0.41%   |
| Foxconn             | 1        | 0.41%   |
| eMachines           | 1        | 0.41%   |
| DNI                 | 1        | 0.41%   |
| DFI                 | 1        | 0.41%   |
| BESSTAR Tech        | 1        | 0.41%   |
| ASRockRack          | 1        | 0.41%   |
| Altos               | 1        | 0.41%   |
| Accton              | 1        | 0.41%   |
| AAEON               | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 8        | 3.28%   |
| ASUS All Series                | 6        | 2.46%   |
| Gigabyte B75M-D3H              | 4        | 1.64%   |
| Gigabyte B550I AORUS PRO AX    | 4        | 1.64%   |
| Lenovo ThinkCentre M58 7627AA9 | 3        | 1.23%   |
| Dell Inspiron 531s             | 3        | 1.23%   |
| ASUS M5A78L-M/USB3             | 3        | 1.23%   |
| ASRock X300M-STX               | 3        | 1.23%   |
| MSI MS-7C52                    | 2        | 0.82%   |
| MSI MS-7A69                    | 2        | 0.82%   |
| Gigabyte Z97MX-Gaming 5        | 2        | 0.82%   |
| Gigabyte H81N                  | 2        | 0.82%   |
| Gigabyte G31M-ES2L             | 2        | 0.82%   |
| Gigabyte B85M-D2V              | 2        | 0.82%   |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.82%   |
| ASUS ROG STRIX B350-F GAMING   | 2        | 0.82%   |
| ASUS Pro WS X570-ACE           | 2        | 0.82%   |
| ASUS PRIME B660M-A WIFI D4     | 2        | 0.82%   |
| ASUS P8Z77-V LX                | 2        | 0.82%   |
| ASUS CM6630_CM6730_CM6830      | 2        | 0.82%   |
| ASRock N68-GS4/USB3 FX         | 2        | 0.82%   |
| ASRock H310M-ITX/ac            | 2        | 0.82%   |
| ASRock A300M-STX               | 2        | 0.82%   |
| ASRock 960GC-GS FX             | 2        | 0.82%   |
| Acer Veriton L480              | 2        | 0.82%   |
| Win element M600               | 1        | 0.41%   |
| Supermicro C9Z490-PGW          | 1        | 0.41%   |
| Ruckus Wireless SCG-100        | 1        | 0.41%   |
| PANSHI B85-S1 V1.0             | 1        | 0.41%   |
| OEM B85 JHS359                 | 1        | 0.41%   |
| NEXCOM SKLD4-P1                | 1        | 0.41%   |
| MSI MS-7D69                    | 1        | 0.41%   |
| MSI MS-7D25                    | 1        | 0.41%   |
| MSI MS-7D19                    | 1        | 0.41%   |
| MSI MS-7D08                    | 1        | 0.41%   |
| MSI MS-7C06                    | 1        | 0.41%   |
| MSI MS-7B89                    | 1        | 0.41%   |
| MSI MS-7B09                    | 1        | 0.41%   |
| MSI MS-7A32                    | 1        | 0.41%   |
| MSI MS-7982                    | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 11       | 4.51%   |
| ASUS TUF                | 10       | 4.1%    |
| ASUS PRIME              | 9        | 3.69%   |
| Unknown                 | 8        | 3.28%   |
| Acer Aspire             | 7        | 2.87%   |
| ASUS All                | 6        | 2.46%   |
| Dell Inspiron           | 5        | 2.05%   |
| ASUS M5A78L-M           | 5        | 2.05%   |
| Acer Veriton            | 5        | 2.05%   |
| Gigabyte B75M-D3H       | 4        | 1.64%   |
| Gigabyte B550I          | 4        | 1.64%   |
| Lenovo ThinkCentre      | 3        | 1.23%   |
| ASUS Pro                | 3        | 1.23%   |
| ASUS P8Z77-V            | 3        | 1.23%   |
| ASRock X300M-STX        | 3        | 1.23%   |
| MSI MS-7C52             | 2        | 0.82%   |
| MSI MS-7A69             | 2        | 0.82%   |
| Gigabyte Z97MX-Gaming   | 2        | 0.82%   |
| Gigabyte X570S          | 2        | 0.82%   |
| Gigabyte H81N           | 2        | 0.82%   |
| Gigabyte G31M-ES2L      | 2        | 0.82%   |
| Gigabyte B85M-D2V       | 2        | 0.82%   |
| Gigabyte B550M          | 2        | 0.82%   |
| Gigabyte B360           | 2        | 0.82%   |
| Dell Precision          | 2        | 0.82%   |
| Dell OptiPlex           | 2        | 0.82%   |
| ASUS P8H61-M            | 2        | 0.82%   |
| ASUS CM6630             | 2        | 0.82%   |
| ASUS ASUSPRO            | 2        | 0.82%   |
| ASRock N68-GS4          | 2        | 0.82%   |
| ASRock H310M-ITX        | 2        | 0.82%   |
| ASRock A300M-STX        | 2        | 0.82%   |
| ASRock 960GC-GS         | 2        | 0.82%   |
| Win element M600        | 1        | 0.41%   |
| Supermicro C9Z490-PGW   | 1        | 0.41%   |
| Ruckus Wireless SCG-100 | 1        | 0.41%   |
| PANSHI B85-S1           | 1        | 0.41%   |
| OEM B85                 | 1        | 0.41%   |
| NEXCOM SKLD4-P1         | 1        | 0.41%   |
| MSI MS-7D69             | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 30       | 12.3%   |
| 2018    | 28       | 11.48%  |
| 2013    | 21       | 8.61%   |
| 2021    | 20       | 8.2%    |
| 2014    | 20       | 8.2%    |
| 2012    | 20       | 8.2%    |
| 2011    | 16       | 6.56%   |
| 2022    | 13       | 5.33%   |
| 2016    | 12       | 4.92%   |
| 2009    | 12       | 4.92%   |
| 2017    | 11       | 4.51%   |
| 2019    | 10       | 4.1%    |
| 2008    | 9        | 3.69%   |
| 2015    | 8        | 3.28%   |
| 2010    | 8        | 3.28%   |
| 2007    | 4        | 1.64%   |
| 2023    | 1        | 0.41%   |
| Unknown | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 244      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 238      | 97.14%  |
| Enabled  | 7        | 2.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 244      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 59       | 23.89%  |
| 32.01-64.0      | 48       | 19.43%  |
| 3.01-4.0        | 37       | 14.98%  |
| 8.01-16.0       | 37       | 14.98%  |
| 4.01-8.0        | 35       | 14.17%  |
| 64.01-256.0     | 17       | 6.88%   |
| 24.01-32.0      | 7        | 2.83%   |
| 1.01-2.0        | 6        | 2.43%   |
| More than 256.0 | 1        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 98       | 37.26%  |
| 2.01-3.0   | 63       | 23.95%  |
| 4.01-8.0   | 42       | 15.97%  |
| 3.01-4.0   | 32       | 12.17%  |
| 8.01-16.0  | 11       | 4.18%   |
| 0.51-1.0   | 7        | 2.66%   |
| 0.01-0.5   | 4        | 1.52%   |
| 24.01-32.0 | 3        | 1.14%   |
| 16.01-24.0 | 2        | 0.76%   |
| 32.01-64.0 | 1        | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 37.8%   |
| 2      | 74       | 30.08%  |
| 3      | 43       | 17.48%  |
| 4      | 16       | 6.5%    |
| 5      | 8        | 3.25%   |
| 0      | 6        | 2.44%   |
| 6      | 4        | 1.63%   |
| 14     | 1        | 0.41%   |
| 7      | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 67.76%  |
| Yes       | 79       | 32.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 242      | 99.18%  |
| No        | 2        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 55.1%   |
| Yes       | 110      | 44.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 64.26%  |
| Yes       | 89       | 35.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Taiwan  | 244      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Taipei            | 67       | 26.69%  |
| New Taipei        | 48       | 19.12%  |
| Taichung          | 22       | 8.76%   |
| Taoyuan District  | 20       | 7.97%   |
| Hsinchu           | 20       | 7.97%   |
| Kaohsiung City    | 17       | 6.77%   |
| Tainan City       | 15       | 5.98%   |
| Hsinchu County    | 5        | 1.99%   |
| Chang-hua         | 4        | 1.59%   |
| Miaoli            | 3        | 1.2%    |
| Keelung           | 3        | 1.2%    |
| Zhudong           | 2        | 0.8%    |
| Yilan             | 2        | 0.8%    |
| Nantou City       | 2        | 0.8%    |
| Kanzijiao         | 2        | 0.8%    |
| Chiayi City       | 2        | 0.8%    |
| Baitang           | 2        | 0.8%    |
| Yangmei District  | 1        | 0.4%    |
| Xinzhuang         | 1        | 0.4%    |
| Xindian           | 1        | 0.4%    |
| Xiatayou          | 1        | 0.4%    |
| Taoyuan City      | 1        | 0.4%    |
| Taishan           | 1        | 0.4%    |
| Taichung City     | 1        | 0.4%    |
| Sanchong District | 1        | 0.4%    |
| Magong            | 1        | 0.4%    |
| Hualien City      | 1        | 0.4%    |
| Fongshan District | 1        | 0.4%    |
| Chongde           | 1        | 0.4%    |
| Chiayi            | 1        | 0.4%    |
| Banqiao           | 1        | 0.4%    |
| Aquan             | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 72       | 110    | 16.29%  |
| Seagate                     | 70       | 122    | 15.84%  |
| Toshiba                     | 41       | 55     | 9.28%   |
| Crucial                     | 31       | 40     | 7.01%   |
| Intel                       | 22       | 32     | 4.98%   |
| Hitachi                     | 21       | 25     | 4.75%   |
| A-DATA Technology           | 19       | 21     | 4.3%    |
| Samsung Electronics         | 16       | 19     | 3.62%   |
| Kingston                    | 15       | 20     | 3.39%   |
| Unknown                     | 11       | 14     | 2.49%   |
| SanDisk                     | 11       | 18     | 2.49%   |
| Transcend                   | 10       | 11     | 2.26%   |
| Apacer                      | 8        | 10     | 1.81%   |
| Plextor                     | 7        | 8      | 1.58%   |
| Micron/Crucial Technology   | 6        | 9      | 1.36%   |
| ANACOMDA                    | 5        | 5      | 1.13%   |
| Patriot                     | 4        | 4      | 0.9%    |
| Micron Technology           | 4        | 4      | 0.9%    |
| Team                        | 3        | 4      | 0.68%   |
| Silicon Motion              | 3        | 3      | 0.68%   |
| PNY                         | 3        | 3      | 0.68%   |
| Maxtor                      | 3        | 3      | 0.68%   |
| Lite-On                     | 3        | 3      | 0.68%   |
| KIOXIA                      | 3        | 3      | 0.68%   |
| ADATA Technology            | 3        | 3      | 0.68%   |
| XPG                         | 2        | 2      | 0.45%   |
| SPCC                        | 2        | 2      | 0.45%   |
| Phison Electronics          | 2        | 3      | 0.45%   |
| Phison                      | 2        | 3      | 0.45%   |
| OCZ                         | 2        | 2      | 0.45%   |
| Leven                       | 2        | 2      | 0.45%   |
| KLEVV                       | 2        | 2      | 0.45%   |
| HGST                        | 2        | 3      | 0.45%   |
| Gigastone                   | 2        | 2      | 0.45%   |
| Fujitsu                     | 2        | 3      | 0.45%   |
| China                       | 2        | 2      | 0.45%   |
| ASMT                        | 2        | 2      | 0.45%   |
| Unknown                     | 2        | 2      | 0.45%   |
| ZHITAI                      | 1        | 1      | 0.23%   |
| Yangtze Memory Technologies | 1        | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                             | 14       | 2.87%   |
| Crucial CT500MX500SSD1 500GB                                       | 11       | 2.26%   |
| Toshiba DT01ACA200 2TB                                             | 10       | 2.05%   |
| Seagate ST2000DM008-2FR102 2TB                                     | 8        | 1.64%   |
| Crucial CT1000MX500SSD1 1TB                                        | 8        | 1.64%   |
| Toshiba MQ01ABD032 320GB                                           | 5        | 1.03%   |
| Seagate ST500DM002-1BD142 500GB                                    | 5        | 1.03%   |
| Seagate ST3500418AS 500GB                                          | 5        | 1.03%   |
| WDC WDS250G1B0B-00AS40 250GB SSD                                   | 4        | 0.82%   |
| WDC WD10EZEX-75WN4A1 1TB                                           | 4        | 0.82%   |
| Seagate ST2000DM001-1CH164 2TB                                     | 4        | 0.82%   |
| Seagate ST1000DM003-1ER162 1TB                                     | 4        | 0.82%   |
| SanDisk NVMe SSD Drive 500GB                                       | 4        | 0.82%   |
| Patriot Burst 120GB SSD                                            | 4        | 0.82%   |
| Kingston SA400S37480G 480GB SSD                                    | 4        | 0.82%   |
| A-DATA SU800 512GB SSD                                             | 4        | 0.82%   |
| A-DATA SU800 256GB SSD                                             | 4        | 0.82%   |
| WDC WD6402AAEX-00Z3A0 640GB                                        | 3        | 0.62%   |
| WDC WD3200AAKS-00L9A0 320GB                                        | 3        | 0.62%   |
| WDC WD1600AAJS-08L7A0 160GB                                        | 3        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 3        | 0.62%   |
| Unknown 004G60  4GB                                                | 3        | 0.62%   |
| Silicon Motion NVMe SSD Drive 512GB                                | 3        | 0.62%   |
| Seagate ST750LX003-1AC154 752GB                                    | 3        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 3        | 0.62%   |
| PNY CS3030 2TB SSD                                                 | 3        | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                                | 3        | 0.62%   |
| Micron/Crucial NVMe SSD Drive 1TB                                  | 3        | 0.62%   |
| Apacer 256GB SATA Flash Drive SSD                                  | 3        | 0.62%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 3        | 0.62%   |
| WDC WDS500G2B0C-00PXH0 500GB                                       | 2        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                   | 2        | 0.41%   |
| WDC WDS100T2B0C-00PXH0 1TB                                         | 2        | 0.41%   |
| WDC WD5000AAKX-001CA0 500GB                                        | 2        | 0.41%   |
| WDC WD20EZBX-00AYRA0 2TB                                           | 2        | 0.41%   |
| WDC WD20EARX-00PASB0 2TB                                           | 2        | 0.41%   |
| WDC WD10EZEX-21M2NA0 1TB                                           | 2        | 0.41%   |
| WDC WD1001FALS-00J7B1 1TB                                          | 2        | 0.41%   |
| Unknown SD/MMC/MS PRO 128GB                                        | 2        | 0.41%   |
| Transcend TS128GSSD340 128GB                                       | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 69       | 119    | 35.57%  |
| WDC                 | 54       | 82     | 27.84%  |
| Toshiba             | 39       | 53     | 20.1%   |
| Hitachi             | 21       | 25     | 10.82%  |
| Unknown             | 3        | 4      | 1.55%   |
| Maxtor              | 3        | 3      | 1.55%   |
| HGST                | 2        | 3      | 1.03%   |
| Samsung Electronics | 1        | 2      | 0.52%   |
| Fujitsu             | 1        | 2      | 0.52%   |
| ASMT                | 1        | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 30       | 38     | 19.74%  |
| A-DATA Technology   | 16       | 18     | 10.53%  |
| Intel               | 13       | 18     | 8.55%   |
| WDC                 | 12       | 17     | 7.89%   |
| Transcend           | 10       | 11     | 6.58%   |
| Kingston            | 9        | 11     | 5.92%   |
| Plextor             | 6        | 7      | 3.95%   |
| Apacer              | 6        | 8      | 3.95%   |
| ANACOMDA            | 5        | 5      | 3.29%   |
| Samsung Electronics | 4        | 4      | 2.63%   |
| Patriot             | 4        | 4      | 2.63%   |
| SanDisk             | 3        | 4      | 1.97%   |
| Micron Technology   | 3        | 3      | 1.97%   |
| Toshiba             | 2        | 2      | 1.32%   |
| Team                | 2        | 3      | 1.32%   |
| SPCC                | 2        | 2      | 1.32%   |
| OCZ                 | 2        | 2      | 1.32%   |
| Leven               | 2        | 2      | 1.32%   |
| KLEVV               | 2        | 2      | 1.32%   |
| Gigastone           | 2        | 2      | 1.32%   |
| China               | 2        | 2      | 1.32%   |
| ZHITAI              | 1        | 1      | 0.66%   |
| Wintec              | 1        | 1      | 0.66%   |
| Unknown             | 1        | 1      | 0.66%   |
| Sony                | 1        | 1      | 0.66%   |
| OCZ-VECT            | 1        | 1      | 0.66%   |
| OCZ-REVODRIVE       | 1        | 4      | 0.66%   |
| MemoCom             | 1        | 2      | 0.66%   |
| LITEONIT            | 1        | 1      | 0.66%   |
| Hewlett-Packard     | 1        | 1      | 0.66%   |
| Fujitsu             | 1        | 1      | 0.66%   |
| EZLINK              | 1        | 1      | 0.66%   |
| AXIOMTEK            | 1        | 1      | 0.66%   |
| ATP                 | 1        | 1      | 0.66%   |
| ASMT                | 1        | 1      | 0.66%   |
| AGI                 | 1        | 2      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 153      | 294    | 42.27%  |
| SSD     | 124      | 185    | 34.25%  |
| NVMe    | 77       | 119    | 21.27%  |
| MMC     | 4        | 4      | 1.1%    |
| Unknown | 4        | 6      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 211      | 458    | 69.18%  |
| NVMe | 76       | 118    | 24.92%  |
| SAS  | 14       | 28     | 4.59%   |
| MMC  | 4        | 4      | 1.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 145      | 245    | 47.54%  |
| 0.51-1.0   | 89       | 123    | 29.18%  |
| 1.01-2.0   | 39       | 60     | 12.79%  |
| 3.01-4.0   | 11       | 15     | 3.61%   |
| 2.01-3.0   | 9        | 11     | 2.95%   |
| 4.01-10.0  | 9        | 22     | 2.95%   |
| 10.01-20.0 | 3        | 3      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 60       | 23.44%  |
| 251-500        | 38       | 14.84%  |
| 1001-2000      | 31       | 12.11%  |
| 501-1000       | 31       | 12.11%  |
| 2001-3000      | 22       | 8.59%   |
| More than 3000 | 19       | 7.42%   |
| 51-100         | 18       | 7.03%   |
| 1-20           | 15       | 5.86%   |
| 21-50          | 12       | 4.69%   |
| Unknown        | 10       | 3.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 94       | 35.88%  |
| 51-100         | 34       | 12.98%  |
| 21-50          | 32       | 12.21%  |
| 101-250        | 32       | 12.21%  |
| 251-500        | 17       | 6.49%   |
| 1001-2000      | 16       | 6.11%   |
| 501-1000       | 16       | 6.11%   |
| Unknown        | 10       | 3.82%   |
| 2001-3000      | 6        | 2.29%   |
| More than 3000 | 5        | 1.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Intel SSDPEKKW256G7 256GB           | 2        | 3      | 7.41%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 3.7%    |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 1      | 3.7%    |
| WDC WD5000AADS-00L4B1 500GB         | 1        | 1      | 3.7%    |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 3.7%    |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 3.7%    |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 3.7%    |
| WDC WD10EFRX-68JCSN0 1TB            | 1        | 1      | 3.7%    |
| WDC WD10EALS-00Z8A0 1TB             | 1        | 1      | 3.7%    |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 3.7%    |
| Transcend TS64GSSD340 64GB          | 1        | 1      | 3.7%    |
| Seagate ST500LM000-1EJ162 500GB     | 1        | 1      | 3.7%    |
| Seagate ST4000DX001-1CE168 4TB      | 1        | 2      | 3.7%    |
| Seagate ST3500410SV 500GB           | 1        | 1      | 3.7%    |
| Seagate ST3160811AS 160GB           | 1        | 1      | 3.7%    |
| Seagate ST2000VN000-1H3164 2TB      | 1        | 2      | 3.7%    |
| Samsung Electronics HM321HI 320GB   | 1        | 2      | 3.7%    |
| Plextor PX-128M6Pro 128GB SSD       | 1        | 1      | 3.7%    |
| LITEONIT E200-080 80GB SSD          | 1        | 1      | 3.7%    |
| KLEVV SSD NEO N500 240GB            | 1        | 1      | 3.7%    |
| Kingston SV300S37A60G 64GB SSD      | 1        | 1      | 3.7%    |
| Intel SSDSC2BB016T7 2TB             | 1        | 1      | 3.7%    |
| Hitachi HDT721010SLA360 1TB         | 1        | 1      | 3.7%    |
| Hitachi HDS723020BLA642 2TB         | 1        | 2      | 3.7%    |
| Crucial CT275MX300SSD4 275GB        | 1        | 1      | 3.7%    |
| A-DATA Technology IMSS332-960GB SSD | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 33.33%  |
| Seagate             | 5        | 7      | 18.52%  |
| Intel               | 3        | 4      | 11.11%  |
| Hitachi             | 2        | 3      | 7.41%   |
| Transcend           | 1        | 1      | 3.7%    |
| Samsung Electronics | 1        | 2      | 3.7%    |
| Plextor             | 1        | 1      | 3.7%    |
| LITEONIT            | 1        | 1      | 3.7%    |
| KLEVV               | 1        | 1      | 3.7%    |
| Kingston            | 1        | 1      | 3.7%    |
| Crucial             | 1        | 1      | 3.7%    |
| A-DATA Technology   | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 52.94%  |
| Seagate             | 5        | 7      | 29.41%  |
| Hitachi             | 2        | 3      | 11.76%  |
| Samsung Electronics | 1        | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 21     | 60%     |
| SSD  | 8        | 8      | 32%     |
| NVMe | 2        | 3      | 8%      |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 143      | 368    | 53.56%  |
| Works    | 99       | 208    | 37.08%  |
| Malfunc  | 25       | 32     | 9.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 167      | 47.99%  |
| AMD                            | 66       | 18.97%  |
| SanDisk                        | 16       | 4.6%    |
| ASMedia Technology             | 14       | 4.02%   |
| Samsung Electronics            | 11       | 3.16%   |
| Phison Electronics             | 11       | 3.16%   |
| Nvidia                         | 9        | 2.59%   |
| Micron/Crucial Technology      | 8        | 2.3%    |
| Kingston Technology Company    | 6        | 1.72%   |
| ADATA Technology               | 6        | 1.72%   |
| Marvell Technology Group       | 5        | 1.44%   |
| Silicon Motion                 | 4        | 1.15%   |
| Lite-On Technology             | 3        | 0.86%   |
| KIOXIA                         | 3        | 0.86%   |
| JMicron Technology             | 3        | 0.86%   |
| Solid State Storage Technology | 2        | 0.57%   |
| Realtek Semiconductor          | 2        | 0.57%   |
| LSI Logic / Symbios Logic      | 2        | 0.57%   |
| Yangtze Memory Technologies    | 1        | 0.29%   |
| Solidigm                       | 1        | 0.29%   |
| Silicon Image                  | 1        | 0.29%   |
| Seagate Technology             | 1        | 0.29%   |
| Micron Technology              | 1        | 0.29%   |
| MAXIO Technology (Hangzhou)    | 1        | 0.29%   |
| Integrated Technology Express  | 1        | 0.29%   |
| INNOGRIT                       | 1        | 0.29%   |
| Innodisk                       | 1        | 0.29%   |
| Broadcom / LSI                 | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 8.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 5.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 2.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 13       | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 2.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 2.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 2.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 1.84%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 7        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 7        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 7        | 1.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 1.38%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 1.38%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.38%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.38%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.38%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5        | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.15%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.15%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 0.92%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.92%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.92%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.92%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                        | 4        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 0.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.92%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 196      | 56.48%  |
| NVMe | 76       | 21.9%   |
| IDE  | 56       | 16.14%  |
| RAID | 15       | 4.32%   |
| SAS  | 3        | 0.86%   |
| SCSI | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 168      | 68.85%  |
| AMD           | 75       | 30.74%  |
| sifive,u74-mc | 1        | 0.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 2.03%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 2.03%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.03%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 3        | 1.22%   |
| Intel Pentium CPU G840 @ 2.80GHz            | 3        | 1.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.22%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.22%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.22%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 1.22%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 3        | 1.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.22%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1.22%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 0.81%   |
| Intel Pentium Gold G5500 CPU @ 3.80GHz      | 2        | 0.81%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.81%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.81%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 0.81%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.81%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.81%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.81%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.81%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.81%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 0.81%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 2        | 0.81%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.81%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.81%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 0.81%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.81%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.81%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 0.81%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.81%   |
| Intel 13th Gen Core i9-13900K               | 2        | 0.81%   |
| Intel 12th Gen Core i7-12700                | 2        | 0.81%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 0.81%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 0.81%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.81%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 40       | 16.26%  |
| Intel Core i7           | 30       | 12.2%   |
| Intel Core i3           | 26       | 10.57%  |
| AMD Ryzen 5             | 22       | 8.94%   |
| Intel Xeon              | 16       | 6.5%    |
| Other                   | 14       | 5.69%   |
| AMD Ryzen 7             | 13       | 5.28%   |
| Intel Celeron           | 10       | 4.07%   |
| Intel Core 2 Quad       | 9        | 3.66%   |
| AMD Ryzen 9             | 9        | 3.66%   |
| Intel Pentium           | 7        | 2.85%   |
| AMD FX                  | 7        | 2.85%   |
| Intel Core 2 Duo        | 5        | 2.03%   |
| Intel Pentium Gold      | 4        | 1.63%   |
| AMD Athlon 64 X2        | 4        | 1.63%   |
| Intel Genuine           | 3        | 1.22%   |
| Intel Core i9           | 3        | 1.22%   |
| AMD Ryzen 5 PRO         | 3        | 1.22%   |
| Intel Pentium Dual-Core | 2        | 0.81%   |
| AMD Phenom II X4        | 2        | 0.81%   |
| AMD Athlon II X4        | 2        | 0.81%   |
| AMD Athlon II X2        | 2        | 0.81%   |
| AMD A8                  | 2        | 0.81%   |
| Intel Pentium Silver    | 1        | 0.41%   |
| Intel Atom              | 1        | 0.41%   |
| AMD Sempron             | 1        | 0.41%   |
| AMD Ryzen Threadripper  | 1        | 0.41%   |
| AMD Ryzen 7 PRO         | 1        | 0.41%   |
| AMD Ryzen 3             | 1        | 0.41%   |
| AMD Phenom II X6        | 1        | 0.41%   |
| AMD Phenom II X2        | 1        | 0.41%   |
| AMD Athlon              | 1        | 0.41%   |
| AMD A4                  | 1        | 0.41%   |
| AMD A10                 | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 98       | 40%     |
| 2       | 58       | 23.67%  |
| 6       | 35       | 14.29%  |
| 8       | 27       | 11.02%  |
| 12      | 10       | 4.08%   |
| 16      | 7        | 2.86%   |
| 28      | 2        | 0.82%   |
| 24      | 2        | 0.82%   |
| 3       | 2        | 0.82%   |
| 48      | 1        | 0.41%   |
| 44      | 1        | 0.41%   |
| 18      | 1        | 0.41%   |
| Unknown | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 237      | 97.13%  |
| 2       | 6        | 2.46%   |
| Unknown | 1        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 141      | 57.32%  |
| 1       | 104      | 42.28%  |
| Unknown | 1        | 0.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 238      | 97.14%  |
| Unknown        | 7        | 2.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 22.62%  |
| 0x306c3    | 26       | 10.32%  |
| 0x306a9    | 15       | 5.95%   |
| 0x206a7    | 13       | 5.16%   |
| 0x08701021 | 9        | 3.57%   |
| 0x506e3    | 8        | 3.17%   |
| 0x1067a    | 8        | 3.17%   |
| 0x906ea    | 7        | 2.78%   |
| 0x906eb    | 6        | 2.38%   |
| 0x90672    | 4        | 1.59%   |
| 0x706a1    | 4        | 1.59%   |
| 0x10676    | 4        | 1.59%   |
| 0x06000852 | 4        | 1.59%   |
| 0xa0655    | 3        | 1.19%   |
| 0xa0653    | 3        | 1.19%   |
| 0x0a50000d | 3        | 1.19%   |
| 0x0810100b | 3        | 1.19%   |
| 0x08001138 | 3        | 1.19%   |
| 0x010000c8 | 3        | 1.19%   |
| 0xa0671    | 2        | 0.79%   |
| 0x906ed    | 2        | 0.79%   |
| 0x6fb      | 2        | 0.79%   |
| 0x50654    | 2        | 0.79%   |
| 0x206c2    | 2        | 0.79%   |
| 0x106e5    | 2        | 0.79%   |
| 0x10677    | 2        | 0.79%   |
| 0x0a601203 | 2        | 0.79%   |
| 0x0a50000c | 2        | 0.79%   |
| 0x0a20120a | 2        | 0.79%   |
| 0x0a201016 | 2        | 0.79%   |
| 0x0a201009 | 2        | 0.79%   |
| 0x08600106 | 2        | 0.79%   |
| 0x08101016 | 2        | 0.79%   |
| 0x0800820d | 2        | 0.79%   |
| 0x0800820b | 2        | 0.79%   |
| 0x06001119 | 2        | 0.79%   |
| 0xb0671    | 1        | 0.4%    |
| 0xa0650    | 1        | 0.4%    |
| 0x906c0    | 1        | 0.4%    |
| 0x90671    | 1        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 36       | 14.69%  |
| KabyLake         | 22       | 8.98%   |
| IvyBridge        | 18       | 7.35%   |
| Zen 2            | 17       | 6.94%   |
| SandyBridge      | 17       | 6.94%   |
| Penryn           | 16       | 6.53%   |
| Skylake          | 15       | 6.12%   |
| Zen 3            | 14       | 5.71%   |
| Unknown          | 11       | 4.49%   |
| Zen              | 10       | 4.08%   |
| K10              | 9        | 3.67%   |
| CometLake        | 9        | 3.67%   |
| Piledriver       | 8        | 3.27%   |
| Zen+             | 6        | 2.45%   |
| Alderlake Hybrid | 5        | 2.04%   |
| Westmere         | 4        | 1.63%   |
| K8 Hammer        | 4        | 1.63%   |
| Goldmont plus    | 4        | 1.63%   |
| Nehalem          | 3        | 1.22%   |
| Icelake          | 3        | 1.22%   |
| Broadwell        | 3        | 1.22%   |
| Tremont          | 2        | 0.82%   |
| Jaguar           | 2        | 0.82%   |
| Core             | 2        | 0.82%   |
| Steamroller      | 1        | 0.41%   |
| Silvermont       | 1        | 0.41%   |
| Goldmont         | 1        | 0.41%   |
| Bulldozer        | 1        | 0.41%   |
| Bonnell          | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 103      | 40.71%  |
| Intel                      | 91       | 35.97%  |
| AMD                        | 54       | 21.34%  |
| ASPEED Technology          | 3        | 1.19%   |
| Matrox Electronics Systems | 2        | 0.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 5.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 4.31%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 3.53%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 3.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 3.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.75%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 2.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.35%   |
| Intel HD Graphics 530                                                       | 5        | 1.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.96%   |
| Intel AlderLake-S GT1                                                       | 5        | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.57%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 4        | 1.57%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.57%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.57%   |
| AMD Renoir                                                                  | 4        | 1.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.18%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.18%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 1.18%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3        | 1.18%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.18%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.78%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.78%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.78%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.78%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.78%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.78%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 0.78%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 93       | 37.8%   |
| 1 x Intel      | 85       | 34.55%  |
| 1 x AMD        | 51       | 20.73%  |
| Intel + Nvidia | 7        | 2.85%   |
| Other          | 3        | 1.22%   |
| 1 x Matrox     | 2        | 0.81%   |
| 1 x ASPEED     | 2        | 0.81%   |
| AMD + Nvidia   | 2        | 0.81%   |
| AMD + ASPEED   | 1        | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 177      | 70.8%   |
| Proprietary | 54       | 21.6%   |
| Unknown     | 19       | 7.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 119      | 47.04%  |
| 1.01-2.0   | 32       | 12.65%  |
| 0.01-0.5   | 26       | 10.28%  |
| 0.51-1.0   | 22       | 8.7%    |
| 3.01-4.0   | 19       | 7.51%   |
| 5.01-6.0   | 17       | 6.72%   |
| 7.01-8.0   | 8        | 3.16%   |
| 8.01-16.0  | 7        | 2.77%   |
| 2.01-3.0   | 3        | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Ancor Communications    | 34       | 13.93%  |
| BenQ                    | 30       | 12.3%   |
| Acer                    | 27       | 11.07%  |
| ViewSonic               | 22       | 9.02%   |
| Dell                    | 15       | 6.15%   |
| Goldstar                | 12       | 4.92%   |
| AOC                     | 11       | 4.51%   |
| Samsung Electronics     | 10       | 4.1%    |
| Philips                 | 10       | 4.1%    |
| ASUSTek Computer        | 9        | 3.69%   |
| Hewlett-Packard         | 7        | 2.87%   |
| NEX                     | 6        | 2.46%   |
| Eizo                    | 6        | 2.46%   |
| Unknown                 | 5        | 2.05%   |
| Envision Peripherals    | 5        | 2.05%   |
| LG Electronics          | 4        | 1.64%   |
| Vizio                   | 3        | 1.23%   |
| Wacom                   | 2        | 0.82%   |
| Unknown (XXX)           | 2        | 0.82%   |
| Sony                    | 2        | 0.82%   |
| Gigabyte Technology     | 2        | 0.82%   |
| AUS                     | 2        | 0.82%   |
| Unknown                 | 2        | 0.82%   |
| ___                     | 1        | 0.41%   |
| VIZ                     | 1        | 0.41%   |
| Toshiba                 | 1        | 0.41%   |
| Tatung                  | 1        | 0.41%   |
| NEC Computers           | 1        | 0.41%   |
| MSI                     | 1        | 0.41%   |
| KTC                     | 1        | 0.41%   |
| KEB                     | 1        | 0.41%   |
| ITE                     | 1        | 0.41%   |
| INS                     | 1        | 0.41%   |
| HWL                     | 1        | 0.41%   |
| GLE                     | 1        | 0.41%   |
| Chi Mei Optoelectronics | 1        | 0.41%   |
| Arnos Instruments       | 1        | 0.41%   |
| AOpen                   | 1        | 0.41%   |
| AMT International       | 1        | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 7        | 2.82%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 4        | 1.61%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 4        | 1.61%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 1.21%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 3        | 1.21%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 3        | 1.21%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3        | 1.21%   |
| Ancor Communications ASUS VS207 ACI20F2 1600x900 432x240mm 19.5-inch  | 3        | 1.21%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.81%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 2        | 0.81%   |
| ViewSonic VA916 Series VSC7C20 1280x1024 376x301mm 19.0-inch          | 2        | 0.81%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 480x270mm 21.7-inch         | 2        | 0.81%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.81%   |
| Unknown LCD Monitor Kingston Technology 43 TV 1920x1080               | 2        | 0.81%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 2        | 0.81%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 2        | 0.81%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 2        | 0.81%   |
| Envision Peripherals LED H963wLs ENV1963 1366x768 410x230mm 18.5-inch | 2        | 0.81%   |
| Envision Peripherals LCD2271W ENV2271 1920x1080 476x268mm 21.5-inch   | 2        | 0.81%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 2        | 0.81%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 2        | 0.81%   |
| BenQ GL2450H BNQ78A6 1920x1080 531x298mm 24.0-inch                    | 2        | 0.81%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                   | 2        | 0.81%   |
| BenQ EW2730V BNQ7931 1920x1080 597x336mm 27.0-inch                    | 2        | 0.81%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 2        | 0.81%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 2        | 0.81%   |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch | 2        | 0.81%   |
| Ancor Communications ASUS VW247 ACI2496 1920x1080 531x299mm 24.0-inch | 2        | 0.81%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch | 2        | 0.81%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 2        | 0.81%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch  | 2        | 0.81%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 477x268mm 21.5-inch | 2        | 0.81%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 2        | 0.81%   |
| Acer XV272U ACR06C1 2560x1440 597x336mm 27.0-inch                     | 2        | 0.81%   |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                     | 2        | 0.81%   |
| Unknown                                                               | 2        | 0.81%   |
| ___ LCD Monitor ___0217 1920x1080 930x530mm 42.1-inch                 | 1        | 0.4%    |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.4%    |
| Vizio V320M-TW VIZ0058 1920x1080 700x390mm 31.5-inch                  | 1        | 0.4%    |
| Vizio M3D470KD VIZ0078 1920x1080 1039x584mm 46.9-inch                 | 1        | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 130      | 55.56%  |
| 2560x1440 (QHD)    | 23       | 9.83%   |
| 3840x2160 (4K)     | 14       | 5.98%   |
| 1366x768 (WXGA)    | 13       | 5.56%   |
| 1680x1050 (WSXGA+) | 9        | 3.85%   |
| 1280x1024 (SXGA)   | 9        | 3.85%   |
| 2560x1080          | 7        | 2.99%   |
| 1600x900 (HD+)     | 7        | 2.99%   |
| 1920x1200 (WUXGA)  | 6        | 2.56%   |
| 1440x900 (WXGA+)   | 6        | 2.56%   |
| 3840x1080          | 2        | 0.85%   |
| 3440x1440          | 2        | 0.85%   |
| 1024x768 (XGA)     | 2        | 0.85%   |
| Unknown            | 2        | 0.85%   |
| 1920x540           | 1        | 0.43%   |
| 1360x768           | 1        | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 41       | 16.87%  |
| 21      | 41       | 16.87%  |
| 24      | 37       | 15.23%  |
| Unknown | 33       | 13.58%  |
| 23      | 22       | 9.05%   |
| 19      | 19       | 7.82%   |
| 31      | 8        | 3.29%   |
| 18      | 8        | 3.29%   |
| 34      | 6        | 2.47%   |
| 22      | 6        | 2.47%   |
| 15      | 4        | 1.65%   |
| 54      | 2        | 0.82%   |
| 43      | 2        | 0.82%   |
| 20      | 2        | 0.82%   |
| 17      | 2        | 0.82%   |
| 13      | 2        | 0.82%   |
| 69      | 1        | 0.41%   |
| 65      | 1        | 0.41%   |
| 48      | 1        | 0.41%   |
| 46      | 1        | 0.41%   |
| 42      | 1        | 0.41%   |
| 41      | 1        | 0.41%   |
| 26      | 1        | 0.41%   |
| 25      | 1        | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 90       | 37.97%  |
| 401-500     | 69       | 29.11%  |
| Unknown     | 33       | 13.92%  |
| 601-700     | 15       | 6.33%   |
| 701-800     | 6        | 2.53%   |
| 351-400     | 6        | 2.53%   |
| 301-350     | 5        | 2.11%   |
| 1001-1500   | 5        | 2.11%   |
| 901-1000    | 4        | 1.69%   |
| 201-300     | 3        | 1.27%   |
| 1501-2000   | 1        | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 154      | 66.67%  |
| Unknown | 32       | 13.85%  |
| 16/10   | 25       | 10.82%  |
| 5/4     | 8        | 3.46%   |
| 21/9    | 6        | 2.6%    |
| 4/3     | 2        | 0.87%   |
| 32/9    | 2        | 0.87%   |
| 6/5     | 1        | 0.43%   |
| 3/2     | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 84       | 34.85%  |
| 301-350        | 42       | 17.43%  |
| 151-200        | 33       | 13.69%  |
| Unknown        | 33       | 13.69%  |
| 351-500        | 14       | 5.81%   |
| 141-150        | 10       | 4.15%   |
| 251-300        | 9        | 3.73%   |
| 501-1000       | 6        | 2.49%   |
| More than 1000 | 4        | 1.66%   |
| 71-80          | 2        | 0.83%   |
| 101-110        | 2        | 0.83%   |
| 121-130        | 1        | 0.41%   |
| 111-120        | 1        | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 137      | 57.56%  |
| 101-120 | 53       | 22.27%  |
| Unknown | 33       | 13.87%  |
| 121-160 | 8        | 3.36%   |
| 161-240 | 4        | 1.68%   |
| 1-50    | 3        | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 205      | 83%     |
| 0     | 21       | 8.5%    |
| 2     | 20       | 8.1%    |
| 3     | 1        | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 141      | 39.72%  |
| Intel                                  | 109      | 30.7%   |
| Qualcomm Atheros                       | 16       | 4.51%   |
| MediaTek                               | 11       | 3.1%    |
| Ralink Technology                      | 9        | 2.54%   |
| Aquantia                               | 9        | 2.54%   |
| Edimax Technology                      | 7        | 1.97%   |
| Broadcom                               | 7        | 1.97%   |
| Nvidia                                 | 5        | 1.41%   |
| TP-Link                                | 4        | 1.13%   |
| HTC (High Tech Computer)               | 4        | 1.13%   |
| ASUSTek Computer                       | 4        | 1.13%   |
| Marvell Technology Group               | 3        | 0.85%   |
| Samsung Electronics                    | 2        | 0.56%   |
| Ralink                                 | 2        | 0.56%   |
| ZyXEL Communications                   | 1        | 0.28%   |
| SparkFun                               | 1        | 0.28%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.28%   |
| Senao                                  | 1        | 0.28%   |
| Qualcomm Atheros Communications        | 1        | 0.28%   |
| Prolific Technology                    | 1        | 0.28%   |
| OPPO Electronics                       | 1        | 0.28%   |
| Microsoft                              | 1        | 0.28%   |
| Mercucys                               | 1        | 0.28%   |
| Mellanox Technologies                  | 1        | 0.28%   |
| IBM                                    | 1        | 0.28%   |
| Huawei Technologies                    | 1        | 0.28%   |
| Google                                 | 1        | 0.28%   |
| D-Link System                          | 1        | 0.28%   |
| D-Link                                 | 1        | 0.28%   |
| BUFFALO                                | 1        | 0.28%   |
| ASIX Electronics                       | 1        | 0.28%   |
| Arduino SA                             | 1        | 0.28%   |
| Apple                                  | 1        | 0.28%   |
| American Megatrends                    | 1        | 0.28%   |
| Accton Technology                      | 1        | 0.28%   |
| 3Com                                   | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 114      | 28.22%  |
| Intel I211 Gigabit Network Connection                               | 19       | 4.7%    |
| Realtek RTL8125 2.5GbE Controller                                   | 15       | 3.71%   |
| Intel Ethernet Controller I225-V                                    | 15       | 3.71%   |
| Intel Wi-Fi 6 AX200                                                 | 14       | 3.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 9        | 2.23%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 1.98%   |
| Ralink MT7601U Wireless Adapter                                     | 7        | 1.73%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 1.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 6        | 1.49%   |
| Intel Wireless-AC 9260                                              | 6        | 1.49%   |
| Intel I210 Gigabit Network Connection                               | 6        | 1.49%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 6        | 1.49%   |
| Intel Ethernet Connection I217-V                                    | 5        | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 5        | 1.24%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                          | 4        | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4        | 0.99%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 0.99%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 4        | 0.99%   |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4        | 0.99%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]      | 4        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 0.74%   |
| Nvidia MCP61 Ethernet                                               | 3        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 3        | 0.74%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                          | 2        | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 2        | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                               | 2        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.5%    |
| MediaTek Titan pocket                                               | 2        | 0.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 2        | 0.5%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller             | 2        | 0.5%    |
| Intel Wireless 8265 / 8275                                          | 2        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 50       | 43.86%  |
| Realtek Semiconductor           | 16       | 14.04%  |
| Ralink Technology               | 9        | 7.89%   |
| MediaTek                        | 9        | 7.89%   |
| Edimax Technology               | 7        | 6.14%   |
| ASUSTek Computer                | 4        | 3.51%   |
| Qualcomm Atheros                | 3        | 2.63%   |
| Broadcom                        | 3        | 2.63%   |
| TP-Link                         | 2        | 1.75%   |
| Ralink                          | 2        | 1.75%   |
| ZyXEL Communications            | 1        | 0.88%   |
| Senao                           | 1        | 0.88%   |
| Qualcomm Atheros Communications | 1        | 0.88%   |
| Microsoft                       | 1        | 0.88%   |
| Mercucys                        | 1        | 0.88%   |
| D-Link System                   | 1        | 0.88%   |
| D-Link                          | 1        | 0.88%   |
| BUFFALO                         | 1        | 0.88%   |
| Accton Technology               | 1        | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14       | 12.17%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9        | 7.83%   |
| Ralink MT7601U Wireless Adapter                                | 7        | 6.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 5.22%   |
| Intel Wireless-AC 9260                                         | 6        | 5.22%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 4        | 3.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4        | 3.48%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 4        | 3.48%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 4        | 3.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3        | 2.61%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 2.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2        | 1.74%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 1.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 1.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 1.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2        | 1.74%   |
| Intel Wireless 8265 / 8275                                     | 2        | 1.74%   |
| Intel Wireless 3165                                            | 2        | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 1.74%   |
| ASUS 802.11ac NIC                                              | 2        | 1.74%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1        | 0.87%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 0.87%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.87%   |
| Senao 802.11 n WLAN                                            | 1        | 0.87%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1        | 0.87%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 0.87%   |
| Realtek 802.11ac NIC                                           | 1        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.87%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1        | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1        | 0.87%   |
| Mercucys 802.11n NIC                                           | 1        | 0.87%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 1        | 0.87%   |
| Intel Wireless 8260                                            | 1        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 0.87%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 1        | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 133      | 48.72%  |
| Intel                    | 87       | 31.87%  |
| Qualcomm Atheros         | 13       | 4.76%   |
| Aquantia                 | 9        | 3.3%    |
| Nvidia                   | 5        | 1.83%   |
| HTC (High Tech Computer) | 4        | 1.47%   |
| Broadcom                 | 4        | 1.47%   |
| Marvell Technology Group | 3        | 1.1%    |
| TP-Link                  | 2        | 0.73%   |
| Samsung Electronics      | 2        | 0.73%   |
| MediaTek                 | 2        | 0.73%   |
| OPPO Electronics         | 1        | 0.37%   |
| Mellanox Technologies    | 1        | 0.37%   |
| IBM                      | 1        | 0.37%   |
| Huawei Technologies      | 1        | 0.37%   |
| Google                   | 1        | 0.37%   |
| ASIX Electronics         | 1        | 0.37%   |
| Apple                    | 1        | 0.37%   |
| American Megatrends      | 1        | 0.37%   |
| 3Com                     | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 114      | 40%     |
| Intel I211 Gigabit Network Connection                               | 19       | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                   | 15       | 5.26%   |
| Intel Ethernet Controller I225-V                                    | 15       | 5.26%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 2.81%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 2.46%   |
| Intel I210 Gigabit Network Connection                               | 6        | 2.11%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 6        | 2.11%   |
| Intel Ethernet Connection I217-V                                    | 5        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 5        | 1.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 1.4%    |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.4%    |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4        | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 1.05%   |
| Nvidia MCP61 Ethernet                                               | 3        | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 1.05%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.7%    |
| MediaTek Titan pocket                                               | 2        | 0.7%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller             | 2        | 0.7%    |
| Intel I350 Gigabit Network Connection                               | 2        | 0.7%    |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.7%    |
| Intel Ethernet Connection (17) I219-V                               | 2        | 0.7%    |
| Intel Ethernet Connection (17) I219-LM                              | 2        | 0.7%    |
| Intel Ethernet Connection (14) I219-V                               | 2        | 0.7%    |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.7%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 0.7%    |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.7%    |
| Intel 82574L Gigabit Network Connection                             | 2        | 0.7%    |
| TP-Link USB 10/100 LAN                                              | 1        | 0.35%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 1        | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 240      | 67.8%   |
| WiFi     | 110      | 31.07%  |
| Modem    | 3        | 0.85%   |
| Unknown  | 1        | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 191      | 76.4%   |
| WiFi     | 58       | 23.2%   |
| Unknown  | 1        | 0.4%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 129      | 52.65%  |
| 2     | 90       | 36.73%  |
| 3     | 12       | 4.9%    |
| 0     | 9        | 3.67%   |
| 6     | 2        | 0.82%   |
| 4     | 2        | 0.82%   |
| 10    | 1        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 212      | 85.48%  |
| Yes  | 36       | 14.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 49       | 55.06%  |
| Cambridge Silicon Radio         | 16       | 17.98%  |
| MediaTek                        | 8        | 8.99%   |
| Realtek Semiconductor           | 3        | 3.37%   |
| IMC Networks                    | 3        | 3.37%   |
| Broadcom                        | 3        | 3.37%   |
| ASUSTek Computer                | 3        | 3.37%   |
| TP-Link                         | 1        | 1.12%   |
| Ralink                          | 1        | 1.12%   |
| Qualcomm Atheros Communications | 1        | 1.12%   |
| Apple                           | 1        | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 16       | 17.98%  |
| Intel AX200 Bluetooth                                 | 14       | 15.73%  |
| Intel Wireless-AC 3168 Bluetooth                      | 9        | 10.11%  |
| Intel AX201 Bluetooth                                 | 9        | 10.11%  |
| MediaTek Wireless_Device                              | 8        | 8.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6        | 6.74%   |
| Intel Bluetooth wireless interface                    | 5        | 5.62%   |
| Intel AX210 Bluetooth                                 | 4        | 4.49%   |
| Realtek Bluetooth Radio                               | 2        | 2.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 2.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 2.25%   |
| ASUS Bluetooth Radio                                  | 2        | 2.25%   |
| TP-Link UB500 Adapter                                 | 1        | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.12%   |
| Ralink RT3290 Bluetooth                               | 1        | 1.12%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.12%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.12%   |
| IMC Networks Bluetooth Device                         | 1        | 1.12%   |
| IMC Networks BCM20702A0                               | 1        | 1.12%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 1.12%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.12%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 160      | 41.34%  |
| Nvidia                               | 99       | 25.58%  |
| AMD                                  | 82       | 21.19%  |
| C-Media Electronics                  | 5        | 1.29%   |
| Logitech                             | 4        | 1.03%   |
| ASUSTek Computer                     | 4        | 1.03%   |
| Generalplus Technology               | 3        | 0.78%   |
| XMOS                                 | 2        | 0.52%   |
| Texas Instruments                    | 2        | 0.52%   |
| SAVITECH                             | 2        | 0.52%   |
| Micro Star International             | 2        | 0.52%   |
| KORG                                 | 2        | 0.52%   |
| Focusrite-Novation                   | 2        | 0.52%   |
| Audio-Technica                       | 2        | 0.52%   |
| ZOOM                                 | 1        | 0.26%   |
| Yamaha                               | 1        | 0.26%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.26%   |
| Sony                                 | 1        | 0.26%   |
| Realtek Semiconductor                | 1        | 0.26%   |
| OPPO Electronics                     | 1        | 0.26%   |
| Novra/IDC/Wegener                    | 1        | 0.26%   |
| JMTek                                | 1        | 0.26%   |
| Harman                               | 1        | 0.26%   |
| GN Netcom                            | 1        | 0.26%   |
| Giga-Byte Technology                 | 1        | 0.26%   |
| Elite Silicon                        | 1        | 0.26%   |
| Dell                                 | 1        | 0.26%   |
| Creative Technology                  | 1        | 0.26%   |
| Creative Labs                        | 1        | 0.26%   |
| 2.4G Composite Device                | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 6.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 20       | 4.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19       | 4.28%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19       | 4.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17       | 3.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 15       | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 3.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 12       | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 2.7%    |
| Intel 200 Series PCH HD Audio                                              | 11       | 2.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10       | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 2.25%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9        | 2.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.03%   |
| Nvidia GP108 High Definition Audio Controller                              | 8        | 1.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7        | 1.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 1.58%   |
| Nvidia MCP61 High Definition Audio                                         | 6        | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.35%   |
| Nvidia GF116 High Definition Audio Controller                              | 6        | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.13%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 0.9%    |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.9%    |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.68%   |
| Logitech H390 headset with microphone                                      | 3        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 28       | 18.92%  |
| Kingston            | 26       | 17.57%  |
| Unknown             | 17       | 11.49%  |
| Transcend           | 17       | 11.49%  |
| A-DATA Technology   | 13       | 8.78%   |
| Micron Technology   | 10       | 6.76%   |
| SK hynix            | 7        | 4.73%   |
| Samsung Electronics | 6        | 4.05%   |
| Unifosa             | 3        | 2.03%   |
| Team                | 3        | 2.03%   |
| G.Skill             | 3        | 2.03%   |
| Silicon Power       | 2        | 1.35%   |
| Patriot             | 2        | 1.35%   |
| Apacer              | 2        | 1.35%   |
| Unknown             | 2        | 1.35%   |
| V-Color             | 1        | 0.68%   |
| UMAX                | 1        | 0.68%   |
| Ramaxel Technology  | 1        | 0.68%   |
| KLEVV               | 1        | 0.68%   |
| GLOWAY              | 1        | 0.68%   |
| CUSO                | 1        | 0.68%   |
| ASint Technology    | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 4        | 2.52%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s         | 3        | 1.89%   |
| Transcend RAM Module 4GB DIMM DDR3 1600MT/s              | 3        | 1.89%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s            | 3        | 1.89%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s         | 3        | 1.89%   |
| Transcend RAM JM1333KLN-4G 4096MB DIMM SDRAM 1600MT/s    | 2        | 1.26%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s      | 2        | 1.26%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 1.26%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 2        | 1.26%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s   | 2        | 1.26%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s     | 2        | 1.26%   |
| Unknown                                                  | 2        | 1.26%   |
| V-Color RAM TD4G8C11-H11 4GB DIMM DDR3 1600MT/s          | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM 667MT/s                      | 1        | 0.63%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 0.63%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.63%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                     | 1        | 0.63%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 0.63%   |
| Unknown RAM Module 1GB DIMM 533MT/s                      | 1        | 0.63%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s             | 1        | 0.63%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s          | 1        | 0.63%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s            | 1        | 0.63%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.63%   |
| Unifosa RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.63%   |
| Unifosa RAM GU332G0ALEPR8H2C6F 2GB SODIMM DDR2 800MT/s   | 1        | 0.63%   |
| UMAX RAM D4-3200-16G-2048X8-L 16384MB DIMM DDR4 3200MT/s | 1        | 0.63%   |
| Transcend RAM TX2400KLN-8GK 4096MB DIMM DDR3 1600MT/s    | 1        | 0.63%   |
| Transcend RAM TX2133KLN-8GK 4096MB DIMM DDR3 2000MT/s    | 1        | 0.63%   |
| Transcend RAM TS512MLK72V6N 4GB DIMM DDR3 1600MT/s       | 1        | 0.63%   |
| Transcend RAM TS2GLH64V1B 16GB DIMM DDR4 2133MT/s        | 1        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 73       | 54.89%  |
| DDR3    | 38       | 28.57%  |
| Unknown | 9        | 6.77%   |
| DDR5    | 5        | 3.76%   |
| DDR2    | 4        | 3.01%   |
| SDRAM   | 3        | 2.26%   |
| DDR     | 1        | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 116      | 87.22%  |
| SODIMM | 17       | 12.78%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 50       | 35.97%  |
| 16384 | 39       | 28.06%  |
| 4096  | 26       | 18.71%  |
| 32768 | 11       | 7.91%   |
| 2048  | 11       | 7.91%   |
| 1024  | 2        | 1.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 34       | 23.13%  |
| 3200  | 23       | 15.65%  |
| 2667  | 13       | 8.84%   |
| 2400  | 11       | 7.48%   |
| 1333  | 10       | 6.8%    |
| 2133  | 9        | 6.12%   |
| 3600  | 7        | 4.76%   |
| 3000  | 5        | 3.4%    |
| 4800  | 4        | 2.72%   |
| 3733  | 4        | 2.72%   |
| 800   | 4        | 2.72%   |
| 667   | 3        | 2.04%   |
| 3466  | 2        | 1.36%   |
| 3400  | 2        | 1.36%   |
| 2933  | 2        | 1.36%   |
| 6000  | 1        | 0.68%   |
| 5200  | 1        | 0.68%   |
| 4333  | 1        | 0.68%   |
| 4000  | 1        | 0.68%   |
| 3866  | 1        | 0.68%   |
| 3800  | 1        | 0.68%   |
| 3334  | 1        | 0.68%   |
| 3134  | 1        | 0.68%   |
| 2866  | 1        | 0.68%   |
| 2666  | 1        | 0.68%   |
| 2000  | 1        | 0.68%   |
| 1066  | 1        | 0.68%   |
| 533   | 1        | 0.68%   |
| 400   | 1        | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 75%     |
| Seiko Epson     | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson XP-240 Series        | 1        | 25%     |
| HP LaserJet Professional P1102w  | 1        | 25%     |
| HP LaserJet Professional P 1102w | 1        | 25%     |
| HP LaserJet 1020                 | 1        | 25%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 14       | 63.64%  |
| Sunplus Innovation Technology | 2        | 9.09%   |
| Microdia                      | 1        | 4.55%   |
| KYE Systems (Mouse Systems)   | 1        | 4.55%   |
| Generalplus Technology        | 1        | 4.55%   |
| eMeet                         | 1        | 4.55%   |
| Apple                         | 1        | 4.55%   |
| A4Tech                        | 1        | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 5        | 22.73%  |
| Logitech Webcam C120                            | 3        | 13.64%  |
| Logitech Webcam C930e                           | 2        | 9.09%   |
| Sunplus HanChen Wise Camera                     | 1        | 4.55%   |
| Sunplus ezcap U3 capture-04                     | 1        | 4.55%   |
| Microdia USB 2.0 Camera                         | 1        | 4.55%   |
| Logitech Webcam C170                            | 1        | 4.55%   |
| Logitech QuickCam Home                          | 1        | 4.55%   |
| Logitech QuickCam E 3500                        | 1        | 4.55%   |
| Logitech HD Pro Webcam C920                     | 1        | 4.55%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 4.55%   |
| Generalplus GENERAL WEBCAM                      | 1        | 4.55%   |
| eMeet HD Webcam C960                            | 1        | 4.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                 | 1        | 4.55%   |
| A4Tech FHD 1080P PC Camera                      | 1        | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 202      | 81.45%  |
| 1     | 36       | 14.52%  |
| 2     | 5        | 2.02%   |
| 3     | 3        | 1.21%   |
| 5     | 1        | 0.4%    |
| 4     | 1        | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 36.36%  |
| Unassigned class         | 8        | 14.55%  |
| Net/wireless             | 7        | 12.73%  |
| Communication controller | 7        | 12.73%  |
| Card reader              | 3        | 5.45%   |
| Storage/raid             | 2        | 3.64%   |
| Sound                    | 2        | 3.64%   |
| Net/ethernet             | 2        | 3.64%   |
| Bluetooth                | 2        | 3.64%   |
| Network                  | 1        | 1.82%   |
| Camera                   | 1        | 1.82%   |

