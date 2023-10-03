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

Total: 343

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 00010C A00                  | [40d7defca4](https://linux-hardware.org/?probe=40d7defca4) | Sep 23, 2023 |
| Centerm       | C92                         | [022344ea10](https://linux-hardware.org/?probe=022344ea10) | Sep 22, 2023 |
| Acer          | Revo RN86                   | [315559ee42](https://linux-hardware.org/?probe=315559ee42) | Sep 21, 2023 |
| ASUSTek       | Z170-P D3                   | [fad69be075](https://linux-hardware.org/?probe=fad69be075) | Sep 12, 2023 |
| MSI           | MS-B0A81                    | [2c4cc9e78f](https://linux-hardware.org/?probe=2c4cc9e78f) | Sep 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | [6bd78c519f](https://linux-hardware.org/?probe=6bd78c519f) | Aug 25, 2023 |
| ASUSTek       | M11AD                       | [a107c7eb20](https://linux-hardware.org/?probe=a107c7eb20) | Aug 25, 2023 |
| Acer          | Predator G3610              | [008082be63](https://linux-hardware.org/?probe=008082be63) | Aug 19, 2023 |
| Acer          | Predator G3610              | [d362c81682](https://linux-hardware.org/?probe=d362c81682) | Aug 19, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
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
| Ubuntu 18.04       | 50       | 19.38%  |
| Ubuntu 20.04       | 36       | 13.95%  |
| Ubuntu 22.04       | 13       | 5.04%   |
| Debian 11          | 10       | 3.88%   |
| OpenMandriva 4.2   | 9        | 3.49%   |
| OpenMandriva 23.01 | 6        | 2.33%   |
| Linux Mint 20.3    | 6        | 2.33%   |
| Arch Rolling       | 6        | 2.33%   |
| Xubuntu 18.04      | 5        | 1.94%   |
| Xubuntu 20.04      | 4        | 1.55%   |
| Pop!_OS 20.04      | 4        | 1.55%   |
| OpenMandriva 4.3   | 4        | 1.55%   |
| OpenMandriva 23.03 | 4        | 1.55%   |
| Ubuntu 21.10       | 3        | 1.16%   |
| Ubuntu 19.04       | 3        | 1.16%   |
| Kubuntu 20.04      | 3        | 1.16%   |
| Fedora 38          | 3        | 1.16%   |
| Zorin 16           | 2        | 0.78%   |
| Ubuntu 23.04       | 2        | 0.78%   |
| Ubuntu 22.10       | 2        | 0.78%   |
| Ubuntu 20.10       | 2        | 0.78%   |
| Ubuntu 19.10       | 2        | 0.78%   |
| Ubuntu 18.10       | 2        | 0.78%   |
| Ubuntu 16.04       | 2        | 0.78%   |
| ROSA R11           | 2        | 0.78%   |
| openSUSE Leap-15.0 | 2        | 0.78%   |
| OpenMandriva 4.90  | 2        | 0.78%   |
| Manjaro 23.0.0     | 2        | 0.78%   |
| Linux Mint 20.2    | 2        | 0.78%   |
| KDE neon 20.04     | 2        | 0.78%   |
| Kali 2020.2        | 2        | 0.78%   |
| Fedora 37          | 2        | 0.78%   |
| Fedora 33          | 2        | 0.78%   |
| Endless 3.5.4      | 2        | 0.78%   |
| Debian 10          | 2        | 0.78%   |
| Zorin 15           | 1        | 0.39%   |
| Xubuntu 22.04      | 1        | 0.39%   |
| Xubuntu 19.04      | 1        | 0.39%   |
| Xubuntu 16.04      | 1        | 0.39%   |
| Ubuntu Unity 16.04 | 1        | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 115      | 45.45%  |
| OpenMandriva  | 25       | 9.88%   |
| Linux Mint    | 14       | 5.53%   |
| Debian        | 13       | 5.14%   |
| Xubuntu       | 12       | 4.74%   |
| Fedora        | 12       | 4.74%   |
| Manjaro       | 8        | 3.16%   |
| Arch          | 7        | 2.77%   |
| Pop!_OS       | 5        | 1.98%   |
| Kubuntu       | 5        | 1.98%   |
| Kali          | 4        | 1.58%   |
| Endless       | 4        | 1.58%   |
| Zorin         | 3        | 1.19%   |
| Ubuntu MATE   | 3        | 1.19%   |
| openSUSE      | 3        | 1.19%   |
| ROSA          | 2        | 0.79%   |
| Lubuntu       | 2        | 0.79%   |
| KDE neon      | 2        | 0.79%   |
| Gentoo        | 2        | 0.79%   |
| Clear Linux   | 2        | 0.79%   |
| CentOS        | 2        | 0.79%   |
| Ubuntu Unity  | 1        | 0.4%    |
| Ubuntu Budgie | 1        | 0.4%    |
| NixOS         | 1        | 0.4%    |
| Mageia        | 1        | 0.4%    |
| Lilidog       | 1        | 0.4%    |
| Garuda Linux  | 1        | 0.4%    |
| BlackPanther  | 1        | 0.4%    |
| ArcoLinux     | 1        | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 2.48%   |
| 6.1.1-desktop-1omv2290   | 6        | 2.13%   |
| 5.4.0-42-generic         | 5        | 1.77%   |
| 5.8.0-50-generic         | 4        | 1.42%   |
| 5.4.0-45-generic         | 4        | 1.42%   |
| 5.4.0-28-generic         | 4        | 1.42%   |
| 5.16.7-desktop-1omv4003  | 4        | 1.42%   |
| 6.2.6-desktop-1omv2390   | 3        | 1.06%   |
| 5.4.0-58-generic         | 3        | 1.06%   |
| 5.19.0-46-generic        | 3        | 1.06%   |
| 5.11.0-27-generic        | 3        | 1.06%   |
| 5.0.0-37-generic         | 3        | 1.06%   |
| 5.0.0-23-generic         | 3        | 1.06%   |
| 4.15.0-66-generic        | 3        | 1.06%   |
| 4.15.0-29-generic        | 3        | 1.06%   |
| 5.8.0-55-generic         | 2        | 0.71%   |
| 5.8.0-43-generic         | 2        | 0.71%   |
| 5.8.0-38-generic         | 2        | 0.71%   |
| 5.5.0-kali2-amd64        | 2        | 0.71%   |
| 5.4.0-91-generic         | 2        | 0.71%   |
| 5.4.0-81-generic         | 2        | 0.71%   |
| 5.4.0-80-generic         | 2        | 0.71%   |
| 5.4.0-77-generic         | 2        | 0.71%   |
| 5.4.0-66-generic         | 2        | 0.71%   |
| 5.4.0-54-generic         | 2        | 0.71%   |
| 5.4.0-53-generic         | 2        | 0.71%   |
| 5.4.0-48-generic         | 2        | 0.71%   |
| 5.4.0-122-generic        | 2        | 0.71%   |
| 5.3.0-40-generic         | 2        | 0.71%   |
| 5.3.0-28-generic         | 2        | 0.71%   |
| 5.19.0-38-generic        | 2        | 0.71%   |
| 5.18.12-desktop-3omv4090 | 2        | 0.71%   |
| 5.15.83-1-pve            | 2        | 0.71%   |
| 5.15.0-53-generic        | 2        | 0.71%   |
| 5.15.0-52-generic        | 2        | 0.71%   |
| 5.15.0-48-generic        | 2        | 0.71%   |
| 5.13.0-35-generic        | 2        | 0.71%   |
| 5.13.0-30-generic        | 2        | 0.71%   |
| 5.11.12-desktop-1omv4002 | 2        | 0.71%   |
| 5.11.0-43-generic        | 2        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 53       | 20.08%  |
| 4.15.0  | 27       | 10.23%  |
| 5.8.0   | 13       | 4.92%   |
| 5.15.0  | 13       | 4.92%   |
| 5.11.0  | 11       | 4.17%   |
| 5.0.0   | 11       | 4.17%   |
| 4.18.0  | 10       | 3.79%   |
| 5.3.0   | 9        | 3.41%   |
| 5.19.0  | 9        | 3.41%   |
| 5.13.0  | 8        | 3.03%   |
| 5.10.14 | 7        | 2.65%   |
| 6.1.1   | 6        | 2.27%   |
| 6.2.0   | 5        | 1.89%   |
| 5.16.7  | 4        | 1.52%   |
| 5.10.0  | 4        | 1.52%   |
| 6.2.6   | 3        | 1.14%   |
| 6.4.0   | 2        | 0.76%   |
| 6.2.2   | 2        | 0.76%   |
| 6.2.12  | 2        | 0.76%   |
| 5.5.0   | 2        | 0.76%   |
| 5.18.12 | 2        | 0.76%   |
| 5.15.83 | 2        | 0.76%   |
| 5.15.23 | 2        | 0.76%   |
| 5.11.12 | 2        | 0.76%   |
| 4.19.57 | 2        | 0.76%   |
| 4.19.0  | 2        | 0.76%   |
| 4.12.14 | 2        | 0.76%   |
| 6.5.3   | 1        | 0.38%   |
| 6.5.0   | 1        | 0.38%   |
| 6.4.15  | 1        | 0.38%   |
| 6.3.9   | 1        | 0.38%   |
| 6.3.5   | 1        | 0.38%   |
| 6.3.2   | 1        | 0.38%   |
| 6.3.12  | 1        | 0.38%   |
| 6.2.15  | 1        | 0.38%   |
| 6.2.11  | 1        | 0.38%   |
| 6.2.10  | 1        | 0.38%   |
| 6.2.1   | 1        | 0.38%   |
| 6.1.31  | 1        | 0.38%   |
| 6.1.0   | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 53       | 20.15%  |
| 4.15    | 27       | 10.27%  |
| 5.15    | 23       | 8.75%   |
| 6.2     | 16       | 6.08%   |
| 5.8     | 15       | 5.7%    |
| 5.10    | 15       | 5.7%    |
| 5.11    | 14       | 5.32%   |
| 5.0     | 12       | 4.56%   |
| 4.18    | 11       | 4.18%   |
| 5.19    | 10       | 3.8%    |
| 5.3     | 9        | 3.42%   |
| 6.1     | 8        | 3.04%   |
| 5.13    | 8        | 3.04%   |
| 5.16    | 6        | 2.28%   |
| 6.0     | 5        | 1.9%    |
| 6.3     | 4        | 1.52%   |
| 4.19    | 4        | 1.52%   |
| 6.4     | 3        | 1.14%   |
| 5.5     | 3        | 1.14%   |
| 5.18    | 3        | 1.14%   |
| 6.5     | 2        | 0.76%   |
| 4.12    | 2        | 0.76%   |
| 5.9     | 1        | 0.38%   |
| 5.7     | 1        | 0.38%   |
| 5.17    | 1        | 0.38%   |
| 5.14    | 1        | 0.38%   |
| 5.12    | 1        | 0.38%   |
| 5.1     | 1        | 0.38%   |
| 4.9     | 1        | 0.38%   |
| 4.4     | 1        | 0.38%   |
| 4.14    | 1        | 0.38%   |
| 3.10    | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 244      | 97.21%  |
| i686    | 6        | 2.39%   |
| riscv64 | 1        | 0.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 115      | 45.1%   |
| Unknown          | 50       | 19.61%  |
| KDE5             | 41       | 16.08%  |
| XFCE             | 17       | 6.67%   |
| X-Cinnamon       | 6        | 2.35%   |
| Cinnamon         | 6        | 2.35%   |
| MATE             | 5        | 1.96%   |
| LXQt             | 3        | 1.18%   |
| KDE              | 3        | 1.18%   |
| LXDE             | 2        | 0.78%   |
| Unity            | 1        | 0.39%   |
| lightdm-xsession | 1        | 0.39%   |
| KDE4             | 1        | 0.39%   |
| i3               | 1        | 0.39%   |
| Hyprland         | 1        | 0.39%   |
| GNOME Classic    | 1        | 0.39%   |
| Budgie           | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 185      | 71.98%  |
| Wayland | 35       | 13.62%  |
| Unknown | 27       | 10.51%  |
| Tty     | 10       | 3.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 125      | 49.02%  |
| SDDM    | 40       | 15.69%  |
| GDM     | 38       | 14.9%   |
| GDM3    | 27       | 10.59%  |
| LightDM | 15       | 5.88%   |
| TDM     | 8        | 3.14%   |
| KDM     | 2        | 0.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 97       | 38.19%  |
| zh_TW   | 92       | 36.22%  |
| Unknown | 47       | 18.5%   |
| C       | 6        | 2.36%   |
| zh_HK   | 2        | 0.79%   |
| en_HK   | 2        | 0.79%   |
| en_GB   | 2        | 0.79%   |
| zh_CN   | 1        | 0.39%   |
| it_IT   | 1        | 0.39%   |
| es_ES   | 1        | 0.39%   |
| en_SG   | 1        | 0.39%   |
| en_PH   | 1        | 0.39%   |
| en_AU   | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 132      | 51.56%  |
| BIOS | 124      | 48.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 187      | 73.91%  |
| Btrfs   | 22       | 8.7%    |
| Overlay | 19       | 7.51%   |
| Tmpfs   | 8        | 3.16%   |
| Unknown | 7        | 2.77%   |
| Xfs     | 5        | 1.98%   |
| Ext2    | 3        | 1.19%   |
| Rootfs  | 1        | 0.4%    |
| Ext3    | 1        | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 119      | 46.48%  |
| GPT     | 113      | 44.14%  |
| MBR     | 24       | 9.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 76.47%  |
| Yes       | 60       | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 56.86%  |
| Yes       | 110      | 43.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 79       | 31.47%  |
| Gigabyte Technology | 62       | 24.7%   |
| MSI                 | 23       | 9.16%   |
| ASRock              | 20       | 7.97%   |
| Acer                | 15       | 5.98%   |
| Dell                | 9        | 3.59%   |
| Hewlett-Packard     | 8        | 3.19%   |
| Unknown             | 8        | 3.19%   |
| Lenovo              | 6        | 2.39%   |
| Intel               | 3        | 1.2%    |
| Win element         | 1        | 0.4%    |
| Supermicro          | 1        | 0.4%    |
| Ruckus Wireless     | 1        | 0.4%    |
| PANSHI              | 1        | 0.4%    |
| OEM                 | 1        | 0.4%    |
| NEXCOM              | 1        | 0.4%    |
| Maxtang             | 1        | 0.4%    |
| Huanan              | 1        | 0.4%    |
| Foxconn             | 1        | 0.4%    |
| eMachines           | 1        | 0.4%    |
| DNI                 | 1        | 0.4%    |
| DFI                 | 1        | 0.4%    |
| Centerm             | 1        | 0.4%    |
| BESSTAR Tech        | 1        | 0.4%    |
| ASRockRack          | 1        | 0.4%    |
| Altos               | 1        | 0.4%    |
| Accton              | 1        | 0.4%    |
| AAEON               | 1        | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 8        | 3.19%   |
| ASUS All Series                | 6        | 2.39%   |
| Gigabyte B75M-D3H              | 4        | 1.59%   |
| Gigabyte B550I AORUS PRO AX    | 4        | 1.59%   |
| Lenovo ThinkCentre M58 7627AA9 | 3        | 1.2%    |
| Dell Inspiron 531s             | 3        | 1.2%    |
| ASUS M5A78L-M/USB3             | 3        | 1.2%    |
| ASRock X300M-STX               | 3        | 1.2%    |
| MSI MS-7C52                    | 2        | 0.8%    |
| MSI MS-7A69                    | 2        | 0.8%    |
| Gigabyte Z97MX-Gaming 5        | 2        | 0.8%    |
| Gigabyte H81N                  | 2        | 0.8%    |
| Gigabyte G31M-ES2L             | 2        | 0.8%    |
| Gigabyte B85M-D2V              | 2        | 0.8%    |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.8%    |
| ASUS ROG STRIX B350-F GAMING   | 2        | 0.8%    |
| ASUS Pro WS X570-ACE           | 2        | 0.8%    |
| ASUS PRIME B660M-A WIFI D4     | 2        | 0.8%    |
| ASUS P8Z77-V LX                | 2        | 0.8%    |
| ASUS CM6630_CM6730_CM6830      | 2        | 0.8%    |
| ASRock N68-GS4/USB3 FX         | 2        | 0.8%    |
| ASRock H310M-ITX/ac            | 2        | 0.8%    |
| ASRock A300M-STX               | 2        | 0.8%    |
| ASRock 960GC-GS FX             | 2        | 0.8%    |
| Acer Veriton L480              | 2        | 0.8%    |
| Win element M600               | 1        | 0.4%    |
| Supermicro C9Z490-PGW          | 1        | 0.4%    |
| Ruckus Wireless SCG-100        | 1        | 0.4%    |
| PANSHI B85-S1 V1.0             | 1        | 0.4%    |
| OEM B85 JHS359                 | 1        | 0.4%    |
| NEXCOM SKLD4-P1                | 1        | 0.4%    |
| MSI PRO ADL-U Cubi 5 (MS-B0A8) | 1        | 0.4%    |
| MSI MS-7D69                    | 1        | 0.4%    |
| MSI MS-7D25                    | 1        | 0.4%    |
| MSI MS-7D19                    | 1        | 0.4%    |
| MSI MS-7D08                    | 1        | 0.4%    |
| MSI MS-7C06                    | 1        | 0.4%    |
| MSI MS-7B89                    | 1        | 0.4%    |
| MSI MS-7B09                    | 1        | 0.4%    |
| MSI MS-7A32                    | 1        | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 11       | 4.38%   |
| ASUS TUF                | 10       | 3.98%   |
| ASUS PRIME              | 9        | 3.59%   |
| Unknown                 | 8        | 3.19%   |
| Acer Aspire             | 7        | 2.79%   |
| ASUS All                | 6        | 2.39%   |
| Dell Inspiron           | 5        | 1.99%   |
| ASUS M5A78L-M           | 5        | 1.99%   |
| Acer Veriton            | 5        | 1.99%   |
| Gigabyte B75M-D3H       | 4        | 1.59%   |
| Gigabyte B550I          | 4        | 1.59%   |
| Lenovo ThinkCentre      | 3        | 1.2%    |
| ASUS Pro                | 3        | 1.2%    |
| ASUS P8Z77-V            | 3        | 1.2%    |
| ASRock X300M-STX        | 3        | 1.2%    |
| MSI MS-7C52             | 2        | 0.8%    |
| MSI MS-7A69             | 2        | 0.8%    |
| Gigabyte Z97MX-Gaming   | 2        | 0.8%    |
| Gigabyte X570S          | 2        | 0.8%    |
| Gigabyte H81N           | 2        | 0.8%    |
| Gigabyte G31M-ES2L      | 2        | 0.8%    |
| Gigabyte B85M-D2V       | 2        | 0.8%    |
| Gigabyte B550M          | 2        | 0.8%    |
| Gigabyte B360           | 2        | 0.8%    |
| Dell Precision          | 2        | 0.8%    |
| Dell OptiPlex           | 2        | 0.8%    |
| ASUS P8H61-M            | 2        | 0.8%    |
| ASUS CM6630             | 2        | 0.8%    |
| ASUS ASUSPRO            | 2        | 0.8%    |
| ASRock N68-GS4          | 2        | 0.8%    |
| ASRock H310M-ITX        | 2        | 0.8%    |
| ASRock A300M-STX        | 2        | 0.8%    |
| ASRock 960GC-GS         | 2        | 0.8%    |
| Win element M600        | 1        | 0.4%    |
| Supermicro C9Z490-PGW   | 1        | 0.4%    |
| Ruckus Wireless SCG-100 | 1        | 0.4%    |
| PANSHI B85-S1           | 1        | 0.4%    |
| OEM B85                 | 1        | 0.4%    |
| NEXCOM SKLD4-P1         | 1        | 0.4%    |
| MSI PRO                 | 1        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 31       | 12.35%  |
| 2018    | 28       | 11.16%  |
| 2013    | 22       | 8.76%   |
| 2012    | 22       | 8.76%   |
| 2021    | 21       | 8.37%   |
| 2014    | 21       | 8.37%   |
| 2011    | 16       | 6.37%   |
| 2022    | 13       | 5.18%   |
| 2009    | 13       | 5.18%   |
| 2016    | 12       | 4.78%   |
| 2017    | 11       | 4.38%   |
| 2019    | 10       | 3.98%   |
| 2008    | 9        | 3.59%   |
| 2015    | 8        | 3.19%   |
| 2010    | 8        | 3.19%   |
| 2007    | 4        | 1.59%   |
| 2023    | 1        | 0.4%    |
| Unknown | 1        | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 251      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 245      | 97.22%  |
| Enabled  | 7        | 2.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 251      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 61       | 24.02%  |
| 32.01-64.0      | 49       | 19.29%  |
| 3.01-4.0        | 39       | 15.35%  |
| 8.01-16.0       | 38       | 14.96%  |
| 4.01-8.0        | 36       | 14.17%  |
| 64.01-256.0     | 17       | 6.69%   |
| 24.01-32.0      | 7        | 2.76%   |
| 1.01-2.0        | 6        | 2.36%   |
| More than 256.0 | 1        | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 100      | 36.76%  |
| 2.01-3.0   | 68       | 25%     |
| 4.01-8.0   | 44       | 16.18%  |
| 3.01-4.0   | 32       | 11.76%  |
| 8.01-16.0  | 11       | 4.04%   |
| 0.51-1.0   | 7        | 2.57%   |
| 0.01-0.5   | 4        | 1.47%   |
| 24.01-32.0 | 3        | 1.1%    |
| 16.01-24.0 | 2        | 0.74%   |
| 32.01-64.0 | 1        | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 37.94%  |
| 2      | 75       | 29.64%  |
| 3      | 44       | 17.39%  |
| 4      | 16       | 6.32%   |
| 5      | 8        | 3.16%   |
| 0      | 7        | 2.77%   |
| 6      | 4        | 1.58%   |
| 7      | 2        | 0.79%   |
| 14     | 1        | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 170      | 67.46%  |
| Yes       | 82       | 32.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 249      | 99.2%   |
| No        | 2        | 0.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 55.16%  |
| Yes       | 113      | 44.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 64.06%  |
| Yes       | 92       | 35.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Taiwan  | 251      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Taipei            | 71       | 27.41%  |
| New Taipei        | 48       | 18.53%  |
| Taichung          | 22       | 8.49%   |
| Taoyuan District  | 20       | 7.72%   |
| Hsinchu           | 20       | 7.72%   |
| Kaohsiung City    | 18       | 6.95%   |
| Tainan City       | 15       | 5.79%   |
| Hsinchu County    | 5        | 1.93%   |
| Keelung           | 4        | 1.54%   |
| Chang-hua         | 4        | 1.54%   |
| Miaoli            | 3        | 1.16%   |
| Zhudong           | 2        | 0.77%   |
| Yilan             | 2        | 0.77%   |
| Nantou City       | 2        | 0.77%   |
| Kanzijiao         | 2        | 0.77%   |
| Chiayi City       | 2        | 0.77%   |
| Baitang           | 2        | 0.77%   |
| Yangmei District  | 1        | 0.39%   |
| Xinzhuang         | 1        | 0.39%   |
| Xindian           | 1        | 0.39%   |
| Xiatayou          | 1        | 0.39%   |
| Taoyuan City      | 1        | 0.39%   |
| Taitung           | 1        | 0.39%   |
| Taishan           | 1        | 0.39%   |
| Taichung City     | 1        | 0.39%   |
| Sanchong District | 1        | 0.39%   |
| Magong            | 1        | 0.39%   |
| Hualien City      | 1        | 0.39%   |
| Fongshan District | 1        | 0.39%   |
| Chongde           | 1        | 0.39%   |
| Chiayi            | 1        | 0.39%   |
| Banqiao           | 1        | 0.39%   |
| Baiyu             | 1        | 0.39%   |
| Aquan             | 1        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 75       | 114    | 16.52%  |
| Seagate                     | 72       | 126    | 15.86%  |
| Toshiba                     | 43       | 59     | 9.47%   |
| Crucial                     | 32       | 41     | 7.05%   |
| Intel                       | 22       | 32     | 4.85%   |
| Hitachi                     | 21       | 25     | 4.63%   |
| A-DATA Technology           | 19       | 22     | 4.19%   |
| Samsung Electronics         | 16       | 19     | 3.52%   |
| Kingston                    | 15       | 20     | 3.3%    |
| SanDisk                     | 12       | 19     | 2.64%   |
| Unknown                     | 11       | 14     | 2.42%   |
| Transcend                   | 10       | 11     | 2.2%    |
| Apacer                      | 8        | 10     | 1.76%   |
| Plextor                     | 7        | 8      | 1.54%   |
| Micron/Crucial Technology   | 6        | 9      | 1.32%   |
| ANACOMDA                    | 5        | 5      | 1.1%    |
| Silicon Motion              | 4        | 4      | 0.88%   |
| Patriot                     | 4        | 4      | 0.88%   |
| Micron Technology           | 4        | 4      | 0.88%   |
| Team                        | 3        | 4      | 0.66%   |
| PNY                         | 3        | 3      | 0.66%   |
| Maxtor                      | 3        | 3      | 0.66%   |
| Lite-On                     | 3        | 3      | 0.66%   |
| KIOXIA                      | 3        | 3      | 0.66%   |
| ADATA Technology            | 3        | 3      | 0.66%   |
| XPG                         | 2        | 2      | 0.44%   |
| SPCC                        | 2        | 2      | 0.44%   |
| Phison Electronics          | 2        | 3      | 0.44%   |
| Phison                      | 2        | 3      | 0.44%   |
| OCZ                         | 2        | 2      | 0.44%   |
| Leven                       | 2        | 2      | 0.44%   |
| KLEVV                       | 2        | 2      | 0.44%   |
| Kingston Technology Company | 2        | 3      | 0.44%   |
| HGST                        | 2        | 3      | 0.44%   |
| Gigastone                   | 2        | 2      | 0.44%   |
| Fujitsu                     | 2        | 3      | 0.44%   |
| China                       | 2        | 2      | 0.44%   |
| ASMT                        | 2        | 2      | 0.44%   |
| Unknown                     | 2        | 2      | 0.44%   |
| ZHITAI                      | 1        | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                            | 14       | 2.79%   |
| Toshiba DT01ACA200 2TB                                            | 12       | 2.4%    |
| Crucial CT500MX500SSD1 500GB                                      | 11       | 2.2%    |
| Seagate ST2000DM008-2FR102 2TB                                    | 8        | 1.6%    |
| Crucial CT1000MX500SSD1 1TB                                       | 8        | 1.6%    |
| Toshiba MQ01ABD032 320GB                                          | 5        | 1%      |
| Seagate ST500DM002-1BD142 500GB                                   | 5        | 1%      |
| Seagate ST3500418AS 500GB                                         | 5        | 1%      |
| WDC WDS250G1B0B-00AS40 250GB SSD                                  | 4        | 0.8%    |
| WDC WD10EZEX-75WN4A1 1TB                                          | 4        | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB                                    | 4        | 0.8%    |
| Seagate ST1000DM003-1ER162 1TB                                    | 4        | 0.8%    |
| SanDisk NVMe SSD Drive 500GB                                      | 4        | 0.8%    |
| Patriot Burst 120GB SSD                                           | 4        | 0.8%    |
| Kingston SA400S37480G 480GB SSD                                   | 4        | 0.8%    |
| A-DATA SU800 512GB SSD                                            | 4        | 0.8%    |
| A-DATA SU800 256GB SSD                                            | 4        | 0.8%    |
| WDC WD6402AAEX-00Z3A0 640GB                                       | 3        | 0.6%    |
| WDC WD3200AAKS-00L9A0 320GB                                       | 3        | 0.6%    |
| WDC WD1600AAJS-08L7A0 160GB                                       | 3        | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB                                          | 3        | 0.6%    |
| Unknown 004G60  4GB                                               | 3        | 0.6%    |
| Silicon Motion NVMe SSD Drive 512GB                               | 3        | 0.6%    |
| Seagate ST750LX003-1AC154 752GB                                   | 3        | 0.6%    |
| Seagate ST3320613AS 320GB                                         | 3        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                                    | 3        | 0.6%    |
| PNY CS3030 2TB SSD                                                | 3        | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                               | 3        | 0.6%    |
| Micron/Crucial NVMe SSD Drive 1TB                                 | 3        | 0.6%    |
| Apacer 256GB SATA Flash Drive SSD                                 | 3        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 3        | 0.6%    |
| WDC WDS500G2B0C-00PXH0 500GB                                      | 2        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                                  | 2        | 0.4%    |
| WDC WDS100T2B0C-00PXH0 1TB                                        | 2        | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB                                      | 2        | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB                                       | 2        | 0.4%    |
| WDC WD20EZBX-00AYRA0 2TB                                          | 2        | 0.4%    |
| WDC WD20EARX-00PASB0 2TB                                          | 2        | 0.4%    |
| WDC WD10EZEX-21M2NA0 1TB                                          | 2        | 0.4%    |
| WDC WD1001FALS-00J7B1 1TB                                         | 2        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 71       | 123    | 35.5%   |
| WDC                 | 57       | 86     | 28.5%   |
| Toshiba             | 41       | 57     | 20.5%   |
| Hitachi             | 21       | 25     | 10.5%   |
| Unknown             | 3        | 4      | 1.5%    |
| Maxtor              | 3        | 3      | 1.5%    |
| HGST                | 2        | 3      | 1%      |
| Samsung Electronics | 1        | 2      | 0.5%    |
| Fujitsu             | 1        | 2      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 31       | 39     | 19.87%  |
| A-DATA Technology   | 16       | 19     | 10.26%  |
| Intel               | 13       | 18     | 8.33%   |
| WDC                 | 12       | 17     | 7.69%   |
| Transcend           | 10       | 11     | 6.41%   |
| Kingston            | 9        | 11     | 5.77%   |
| Plextor             | 6        | 7      | 3.85%   |
| Apacer              | 6        | 8      | 3.85%   |
| ANACOMDA            | 5        | 5      | 3.21%   |
| SanDisk             | 4        | 5      | 2.56%   |
| Samsung Electronics | 4        | 4      | 2.56%   |
| Patriot             | 4        | 4      | 2.56%   |
| Micron Technology   | 3        | 3      | 1.92%   |
| Toshiba             | 2        | 2      | 1.28%   |
| Team                | 2        | 3      | 1.28%   |
| SPCC                | 2        | 2      | 1.28%   |
| OCZ                 | 2        | 2      | 1.28%   |
| Leven               | 2        | 2      | 1.28%   |
| KLEVV               | 2        | 2      | 1.28%   |
| Gigastone           | 2        | 2      | 1.28%   |
| China               | 2        | 2      | 1.28%   |
| ASMT                | 2        | 2      | 1.28%   |
| ZHITAI              | 1        | 1      | 0.64%   |
| Wintec              | 1        | 1      | 0.64%   |
| Unknown             | 1        | 1      | 0.64%   |
| Sony                | 1        | 1      | 0.64%   |
| OCZ-VECT            | 1        | 1      | 0.64%   |
| OCZ-REVODRIVE       | 1        | 4      | 0.64%   |
| MemoCom             | 1        | 2      | 0.64%   |
| LITEONIT            | 1        | 1      | 0.64%   |
| Hewlett-Packard     | 1        | 1      | 0.64%   |
| Fujitsu             | 1        | 1      | 0.64%   |
| FORESEE             | 1        | 1      | 0.64%   |
| EZLINK              | 1        | 1      | 0.64%   |
| AXIOMTEK            | 1        | 1      | 0.64%   |
| ATP                 | 1        | 1      | 0.64%   |
| AGI                 | 1        | 2      | 0.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 157      | 305    | 42.32%  |
| SSD     | 127      | 190    | 34.23%  |
| NVMe    | 79       | 121    | 21.29%  |
| MMC     | 4        | 4      | 1.08%   |
| Unknown | 4        | 6      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 216      | 472    | 69.01%  |
| NVMe | 78       | 120    | 24.92%  |
| SAS  | 15       | 30     | 4.79%   |
| MMC  | 4        | 4      | 1.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 150      | 252    | 47.77%  |
| 0.51-1.0   | 90       | 127    | 28.66%  |
| 1.01-2.0   | 40       | 63     | 12.74%  |
| 3.01-4.0   | 12       | 16     | 3.82%   |
| 2.01-3.0   | 10       | 12     | 3.18%   |
| 4.01-10.0  | 9        | 22     | 2.87%   |
| 10.01-20.0 | 3        | 3      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 61       | 23.11%  |
| 251-500        | 40       | 15.15%  |
| 501-1000       | 33       | 12.5%   |
| 1001-2000      | 32       | 12.12%  |
| 2001-3000      | 22       | 8.33%   |
| More than 3000 | 20       | 7.58%   |
| 51-100         | 18       | 6.82%   |
| 1-20           | 15       | 5.68%   |
| 21-50          | 13       | 4.92%   |
| Unknown        | 10       | 3.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 97       | 35.93%  |
| 51-100         | 36       | 13.33%  |
| 101-250        | 33       | 12.22%  |
| 21-50          | 32       | 11.85%  |
| 251-500        | 18       | 6.67%   |
| 1001-2000      | 16       | 5.93%   |
| 501-1000       | 16       | 5.93%   |
| Unknown        | 10       | 3.7%    |
| More than 3000 | 6        | 2.22%   |
| 2001-3000      | 6        | 2.22%   |

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
| Detected | 147      | 383    | 53.85%  |
| Works    | 101      | 211    | 37%     |
| Malfunc  | 25       | 32     | 9.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 173      | 48.19%  |
| AMD                            | 67       | 18.66%  |
| SanDisk                        | 16       | 4.46%   |
| ASMedia Technology             | 14       | 3.9%    |
| Samsung Electronics            | 11       | 3.06%   |
| Phison Electronics             | 11       | 3.06%   |
| Nvidia                         | 9        | 2.51%   |
| Micron/Crucial Technology      | 8        | 2.23%   |
| Kingston Technology Company    | 7        | 1.95%   |
| Marvell Technology Group       | 6        | 1.67%   |
| ADATA Technology               | 6        | 1.67%   |
| Silicon Motion                 | 5        | 1.39%   |
| JMicron Technology             | 4        | 1.11%   |
| Lite-On Technology             | 3        | 0.84%   |
| KIOXIA                         | 3        | 0.84%   |
| Solid State Storage Technology | 2        | 0.56%   |
| Realtek Semiconductor          | 2        | 0.56%   |
| LSI Logic / Symbios Logic      | 2        | 0.56%   |
| Yangtze Memory Technologies    | 1        | 0.28%   |
| Solidigm                       | 1        | 0.28%   |
| Silicon Image                  | 1        | 0.28%   |
| Seagate Technology             | 1        | 0.28%   |
| Micron Technology              | 1        | 0.28%   |
| MAXIO Technology (Hangzhou)    | 1        | 0.28%   |
| Integrated Technology Express  | 1        | 0.28%   |
| INNOGRIT                       | 1        | 0.28%   |
| Innodisk                       | 1        | 0.28%   |
| Broadcom / LSI                 | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 8.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 5.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 2.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 13       | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 2.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 2.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 2.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.01%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 8        | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 8        | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 1.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 7        | 1.56%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 1.34%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 1.34%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.34%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.34%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5        | 1.12%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.12%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.12%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 0.89%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.89%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.89%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.89%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                        | 4        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 0.89%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.89%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 201      | 56.3%   |
| NVMe | 78       | 21.85%  |
| IDE  | 58       | 16.25%  |
| RAID | 16       | 4.48%   |
| SAS  | 3        | 0.84%   |
| SCSI | 1        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 174      | 69.32%  |
| AMD           | 76       | 30.28%  |
| sifive,u74-mc | 1        | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.98%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 1.98%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 1.98%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 3        | 1.19%   |
| Intel Pentium CPU G840 @ 2.80GHz            | 3        | 1.19%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.19%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.19%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 1.19%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.19%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.19%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 1.19%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 3        | 1.19%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.19%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1.19%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 0.79%   |
| Intel Pentium Gold G5500 CPU @ 3.80GHz      | 2        | 0.79%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.79%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.79%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 0.79%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.79%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.79%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.79%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 0.79%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 2        | 0.79%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.79%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.79%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 0.79%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.79%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.79%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 0.79%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.79%   |
| Intel 13th Gen Core i9-13900K               | 2        | 0.79%   |
| Intel 12th Gen Core i7-12700                | 2        | 0.79%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 0.79%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 0.79%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 41       | 16.21%  |
| Intel Core i7           | 33       | 13.04%  |
| Intel Core i3           | 26       | 10.28%  |
| AMD Ryzen 5             | 22       | 8.7%    |
| Intel Xeon              | 16       | 6.32%   |
| Other                   | 15       | 5.93%   |
| AMD Ryzen 7             | 13       | 5.14%   |
| Intel Celeron           | 11       | 4.35%   |
| Intel Core 2 Quad       | 9        | 3.56%   |
| AMD Ryzen 9             | 9        | 3.56%   |
| Intel Pentium           | 7        | 2.77%   |
| AMD FX                  | 7        | 2.77%   |
| Intel Core 2 Duo        | 5        | 1.98%   |
| Intel Pentium Gold      | 4        | 1.58%   |
| AMD Athlon 64 X2        | 4        | 1.58%   |
| Intel Genuine           | 3        | 1.19%   |
| Intel Core i9           | 3        | 1.19%   |
| AMD Ryzen 5 PRO         | 3        | 1.19%   |
| AMD Phenom II X4        | 3        | 1.19%   |
| Intel Pentium Dual-Core | 2        | 0.79%   |
| AMD Athlon II X4        | 2        | 0.79%   |
| AMD Athlon II X2        | 2        | 0.79%   |
| AMD A8                  | 2        | 0.79%   |
| Intel Pentium Silver    | 1        | 0.4%    |
| Intel Atom              | 1        | 0.4%    |
| AMD Sempron             | 1        | 0.4%    |
| AMD Ryzen Threadripper  | 1        | 0.4%    |
| AMD Ryzen 7 PRO         | 1        | 0.4%    |
| AMD Ryzen 3             | 1        | 0.4%    |
| AMD Phenom II X6        | 1        | 0.4%    |
| AMD Phenom II X2        | 1        | 0.4%    |
| AMD Athlon              | 1        | 0.4%    |
| AMD A4                  | 1        | 0.4%    |
| AMD A10                 | 1        | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 103      | 40.87%  |
| 2       | 58       | 23.02%  |
| 6       | 36       | 14.29%  |
| 8       | 27       | 10.71%  |
| 12      | 10       | 3.97%   |
| 16      | 7        | 2.78%   |
| 28      | 2        | 0.79%   |
| 24      | 2        | 0.79%   |
| 3       | 2        | 0.79%   |
| 48      | 1        | 0.4%    |
| 44      | 1        | 0.4%    |
| 18      | 1        | 0.4%    |
| 10      | 1        | 0.4%    |
| Unknown | 1        | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 244      | 97.21%  |
| 2       | 6        | 2.39%   |
| Unknown | 1        | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 145      | 57.31%  |
| 1       | 107      | 42.29%  |
| Unknown | 1        | 0.4%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 245      | 97.22%  |
| Unknown        | 7        | 2.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 24.23%  |
| 0x306c3    | 26       | 10%     |
| 0x306a9    | 16       | 6.15%   |
| 0x206a7    | 14       | 5.38%   |
| 0x08701021 | 9        | 3.46%   |
| 0x506e3    | 8        | 3.08%   |
| 0x1067a    | 8        | 3.08%   |
| 0x906ea    | 7        | 2.69%   |
| 0x906eb    | 6        | 2.31%   |
| 0x90672    | 4        | 1.54%   |
| 0x706a1    | 4        | 1.54%   |
| 0x10676    | 4        | 1.54%   |
| 0x06000852 | 4        | 1.54%   |
| 0xa0655    | 3        | 1.15%   |
| 0xa0653    | 3        | 1.15%   |
| 0x0a50000d | 3        | 1.15%   |
| 0x0810100b | 3        | 1.15%   |
| 0x08001138 | 3        | 1.15%   |
| 0x010000c8 | 3        | 1.15%   |
| 0xa0671    | 2        | 0.77%   |
| 0x906ed    | 2        | 0.77%   |
| 0x6fb      | 2        | 0.77%   |
| 0x50654    | 2        | 0.77%   |
| 0x206c2    | 2        | 0.77%   |
| 0x106e5    | 2        | 0.77%   |
| 0x10677    | 2        | 0.77%   |
| 0x0a601203 | 2        | 0.77%   |
| 0x0a50000c | 2        | 0.77%   |
| 0x0a20120a | 2        | 0.77%   |
| 0x0a201016 | 2        | 0.77%   |
| 0x0a201009 | 2        | 0.77%   |
| 0x08600106 | 2        | 0.77%   |
| 0x08101016 | 2        | 0.77%   |
| 0x0800820d | 2        | 0.77%   |
| 0x0800820b | 2        | 0.77%   |
| 0x06001119 | 2        | 0.77%   |
| 0xb0671    | 1        | 0.38%   |
| 0xa0650    | 1        | 0.38%   |
| 0x906c0    | 1        | 0.38%   |
| 0x90671    | 1        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 37       | 14.68%  |
| KabyLake         | 24       | 9.52%   |
| IvyBridge        | 19       | 7.54%   |
| Zen 2            | 17       | 6.75%   |
| SandyBridge      | 17       | 6.75%   |
| Penryn           | 16       | 6.35%   |
| Skylake          | 15       | 5.95%   |
| Zen 3            | 14       | 5.56%   |
| Unknown          | 11       | 4.37%   |
| Zen              | 10       | 3.97%   |
| K10              | 10       | 3.97%   |
| CometLake        | 9        | 3.57%   |
| Piledriver       | 8        | 3.17%   |
| Zen+             | 6        | 2.38%   |
| Alderlake Hybrid | 6        | 2.38%   |
| Westmere         | 4        | 1.59%   |
| K8 Hammer        | 4        | 1.59%   |
| Goldmont plus    | 4        | 1.59%   |
| Nehalem          | 3        | 1.19%   |
| Icelake          | 3        | 1.19%   |
| Broadwell        | 3        | 1.19%   |
| Tremont          | 2        | 0.79%   |
| Silvermont       | 2        | 0.79%   |
| Jaguar           | 2        | 0.79%   |
| Core             | 2        | 0.79%   |
| Steamroller      | 1        | 0.4%    |
| Goldmont         | 1        | 0.4%    |
| Bulldozer        | 1        | 0.4%    |
| Bonnell          | 1        | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 106      | 40.77%  |
| Intel                      | 94       | 36.15%  |
| AMD                        | 55       | 21.15%  |
| ASPEED Technology          | 3        | 1.15%   |
| Matrox Electronics Systems | 2        | 0.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 5.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 12       | 4.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 3.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 3.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 3.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 2.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.29%   |
| Intel HD Graphics 530                                                       | 5        | 1.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.91%   |
| Intel AlderLake-S GT1                                                       | 5        | 1.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 1.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 1.91%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.53%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.53%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 4        | 1.53%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.53%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.53%   |
| AMD Renoir                                                                  | 4        | 1.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.53%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.15%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.15%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 1.15%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3        | 1.15%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.15%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 0.76%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.76%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.76%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.76%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.76%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.76%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 96       | 37.94%  |
| 1 x Intel      | 88       | 34.78%  |
| 1 x AMD        | 52       | 20.55%  |
| Intel + Nvidia | 7        | 2.77%   |
| Other          | 3        | 1.19%   |
| 1 x Matrox     | 2        | 0.79%   |
| 1 x ASPEED     | 2        | 0.79%   |
| AMD + Nvidia   | 2        | 0.79%   |
| AMD + ASPEED   | 1        | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 182      | 70.82%  |
| Proprietary | 55       | 21.4%   |
| Unknown     | 20       | 7.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 124      | 47.69%  |
| 1.01-2.0   | 32       | 12.31%  |
| 0.01-0.5   | 26       | 10%     |
| 0.51-1.0   | 23       | 8.85%   |
| 3.01-4.0   | 19       | 7.31%   |
| 5.01-6.0   | 17       | 6.54%   |
| 7.01-8.0   | 9        | 3.46%   |
| 8.01-16.0  | 7        | 2.69%   |
| 2.01-3.0   | 3        | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Ancor Communications    | 34       | 13.71%  |
| BenQ                    | 30       | 12.1%   |
| Acer                    | 27       | 10.89%  |
| ViewSonic               | 22       | 8.87%   |
| Dell                    | 15       | 6.05%   |
| Goldstar                | 13       | 5.24%   |
| Samsung Electronics     | 11       | 4.44%   |
| AOC                     | 11       | 4.44%   |
| Philips                 | 10       | 4.03%   |
| ASUSTek Computer        | 9        | 3.63%   |
| Hewlett-Packard         | 7        | 2.82%   |
| NEX                     | 6        | 2.42%   |
| Eizo                    | 6        | 2.42%   |
| Unknown                 | 5        | 2.02%   |
| Envision Peripherals    | 5        | 2.02%   |
| LG Electronics          | 4        | 1.61%   |
| Vizio                   | 3        | 1.21%   |
| Unknown                 | 3        | 1.21%   |
| Wacom                   | 2        | 0.81%   |
| Unknown (XXX)           | 2        | 0.81%   |
| Sony                    | 2        | 0.81%   |
| Gigabyte Technology     | 2        | 0.81%   |
| AUS                     | 2        | 0.81%   |
| ___                     | 1        | 0.4%    |
| VIZ                     | 1        | 0.4%    |
| Toshiba                 | 1        | 0.4%    |
| Tatung                  | 1        | 0.4%    |
| SMP                     | 1        | 0.4%    |
| NEC Computers           | 1        | 0.4%    |
| MSI                     | 1        | 0.4%    |
| KTC                     | 1        | 0.4%    |
| KEB                     | 1        | 0.4%    |
| ITE                     | 1        | 0.4%    |
| INS                     | 1        | 0.4%    |
| HWL                     | 1        | 0.4%    |
| GLE                     | 1        | 0.4%    |
| Chi Mei Optoelectronics | 1        | 0.4%    |
| Arnos Instruments       | 1        | 0.4%    |
| AOpen                   | 1        | 0.4%    |
| AMT International       | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 7        | 2.78%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 4        | 1.59%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4        | 1.59%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 4        | 1.59%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 1.19%   |
| BenQ GC2870 BNQ78DD 1920x1080 620x340mm 27.8-inch                     | 3        | 1.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3        | 1.19%   |
| Ancor Communications ASUS VS207 ACI20F2 1600x900 432x240mm 19.5-inch  | 3        | 1.19%   |
| Unknown                                                               | 3        | 1.19%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.79%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 2        | 0.79%   |
| ViewSonic VA916 Series VSC7C20 1280x1024 376x301mm 19.0-inch          | 2        | 0.79%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 2        | 0.79%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.79%   |
| Unknown LCD Monitor Kingston Technology 43 TV 1920x1080               | 2        | 0.79%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.79%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 2        | 0.79%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.79%   |
| Envision Peripherals LED H963wLs ENV1963 1366x768 410x230mm 18.5-inch | 2        | 0.79%   |
| Envision Peripherals LCD2271W ENV2271 1920x1080 476x268mm 21.5-inch   | 2        | 0.79%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 2        | 0.79%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 2        | 0.79%   |
| BenQ GL2450H BNQ78A6 1920x1080 531x298mm 24.0-inch                    | 2        | 0.79%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                   | 2        | 0.79%   |
| BenQ EW2730V BNQ7931 1920x1080 597x336mm 27.0-inch                    | 2        | 0.79%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 2        | 0.79%   |
| AOC 2260 AOC2260 1680x1050 474x296mm 22.0-inch                        | 2        | 0.79%   |
| Ancor Communications VX239 ACI23E1 1920x1080 510x290mm 23.1-inch      | 2        | 0.79%   |
| Ancor Communications ASUS VW247 ACI2496 1920x1080 531x299mm 24.0-inch | 2        | 0.79%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch | 2        | 0.79%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 2        | 0.79%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch  | 2        | 0.79%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 477x268mm 21.5-inch | 2        | 0.79%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 2        | 0.79%   |
| Acer XV272U ACR06C1 2560x1440 597x336mm 27.0-inch                     | 2        | 0.79%   |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                     | 2        | 0.79%   |
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
| 1920x1080 (FHD)    | 132      | 55.46%  |
| 2560x1440 (QHD)    | 23       | 9.66%   |
| 3840x2160 (4K)     | 16       | 6.72%   |
| 1366x768 (WXGA)    | 13       | 5.46%   |
| 1680x1050 (WSXGA+) | 9        | 3.78%   |
| 1280x1024 (SXGA)   | 9        | 3.78%   |
| 2560x1080          | 7        | 2.94%   |
| 1600x900 (HD+)     | 7        | 2.94%   |
| 1920x1200 (WUXGA)  | 6        | 2.52%   |
| 1440x900 (WXGA+)   | 6        | 2.52%   |
| 3840x1080          | 2        | 0.84%   |
| 3440x1440          | 2        | 0.84%   |
| 1024x768 (XGA)     | 2        | 0.84%   |
| Unknown            | 2        | 0.84%   |
| 1920x540           | 1        | 0.42%   |
| 1360x768           | 1        | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 42       | 17%     |
| 27      | 41       | 16.6%   |
| 24      | 37       | 14.98%  |
| Unknown | 34       | 13.77%  |
| 23      | 22       | 8.91%   |
| 19      | 19       | 7.69%   |
| 31      | 9        | 3.64%   |
| 18      | 8        | 3.24%   |
| 34      | 6        | 2.43%   |
| 22      | 6        | 2.43%   |
| 15      | 4        | 1.62%   |
| 54      | 2        | 0.81%   |
| 43      | 2        | 0.81%   |
| 20      | 2        | 0.81%   |
| 17      | 2        | 0.81%   |
| 13      | 2        | 0.81%   |
| 84      | 1        | 0.4%    |
| 69      | 1        | 0.4%    |
| 65      | 1        | 0.4%    |
| 48      | 1        | 0.4%    |
| 46      | 1        | 0.4%    |
| 42      | 1        | 0.4%    |
| 41      | 1        | 0.4%    |
| 26      | 1        | 0.4%    |
| 25      | 1        | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 90       | 37.34%  |
| 401-500     | 70       | 29.05%  |
| Unknown     | 34       | 14.11%  |
| 601-700     | 16       | 6.64%   |
| 701-800     | 6        | 2.49%   |
| 351-400     | 6        | 2.49%   |
| 301-350     | 5        | 2.07%   |
| 1001-1500   | 5        | 2.07%   |
| 901-1000    | 4        | 1.66%   |
| 201-300     | 3        | 1.24%   |
| 1501-2000   | 2        | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 157      | 66.81%  |
| Unknown | 33       | 14.04%  |
| 16/10   | 25       | 10.64%  |
| 5/4     | 8        | 3.4%    |
| 21/9    | 6        | 2.55%   |
| 4/3     | 2        | 0.85%   |
| 32/9    | 2        | 0.85%   |
| 6/5     | 1        | 0.43%   |
| 3/2     | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 85       | 34.69%  |
| 301-350        | 42       | 17.14%  |
| Unknown        | 34       | 13.88%  |
| 151-200        | 33       | 13.47%  |
| 351-500        | 15       | 6.12%   |
| 141-150        | 10       | 4.08%   |
| 251-300        | 9        | 3.67%   |
| 501-1000       | 6        | 2.45%   |
| More than 1000 | 5        | 2.04%   |
| 71-80          | 2        | 0.82%   |
| 101-110        | 2        | 0.82%   |
| 121-130        | 1        | 0.41%   |
| 111-120        | 1        | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 139      | 57.44%  |
| 101-120 | 54       | 22.31%  |
| Unknown | 34       | 14.05%  |
| 121-160 | 8        | 3.31%   |
| 161-240 | 4        | 1.65%   |
| 1-50    | 3        | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 210      | 82.68%  |
| 0     | 23       | 9.06%   |
| 2     | 20       | 7.87%   |
| 3     | 1        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 146      | 39.89%  |
| Intel                                  | 114      | 31.15%  |
| Qualcomm Atheros                       | 16       | 4.37%   |
| MediaTek                               | 11       | 3.01%   |
| Ralink Technology                      | 9        | 2.46%   |
| Aquantia                               | 9        | 2.46%   |
| Edimax Technology                      | 7        | 1.91%   |
| Broadcom                               | 7        | 1.91%   |
| Nvidia                                 | 5        | 1.37%   |
| ASUSTek Computer                       | 5        | 1.37%   |
| TP-Link                                | 4        | 1.09%   |
| HTC (High Tech Computer)               | 4        | 1.09%   |
| Marvell Technology Group               | 3        | 0.82%   |
| Samsung Electronics                    | 2        | 0.55%   |
| Ralink                                 | 2        | 0.55%   |
| ZyXEL Communications                   | 1        | 0.27%   |
| SparkFun                               | 1        | 0.27%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.27%   |
| Senao                                  | 1        | 0.27%   |
| Qualcomm Atheros Communications        | 1        | 0.27%   |
| Prolific Technology                    | 1        | 0.27%   |
| OPPO Electronics                       | 1        | 0.27%   |
| Microsoft                              | 1        | 0.27%   |
| Mercucys                               | 1        | 0.27%   |
| Mellanox Technologies                  | 1        | 0.27%   |
| IBM                                    | 1        | 0.27%   |
| Huawei Technologies                    | 1        | 0.27%   |
| Google                                 | 1        | 0.27%   |
| D-Link System                          | 1        | 0.27%   |
| D-Link                                 | 1        | 0.27%   |
| BUFFALO                                | 1        | 0.27%   |
| ASIX Electronics                       | 1        | 0.27%   |
| Arduino SA                             | 1        | 0.27%   |
| Apple                                  | 1        | 0.27%   |
| American Megatrends                    | 1        | 0.27%   |
| Accton Technology                      | 1        | 0.27%   |
| 3Com                                   | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 119      | 28.47%  |
| Intel I211 Gigabit Network Connection                               | 20       | 4.78%   |
| Realtek RTL8125 2.5GbE Controller                                   | 16       | 3.83%   |
| Intel Ethernet Controller I225-V                                    | 15       | 3.59%   |
| Intel Wi-Fi 6 AX200                                                 | 14       | 3.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 9        | 2.15%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 1.91%   |
| Ralink MT7601U Wireless Adapter                                     | 7        | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 1.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 6        | 1.44%   |
| Intel Wireless-AC 9260                                              | 6        | 1.44%   |
| Intel I210 Gigabit Network Connection                               | 6        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 6        | 1.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 6        | 1.44%   |
| Intel Ethernet Connection I217-V                                    | 5        | 1.2%    |
| Realtek 802.11n WLAN Adapter                                        | 4        | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4        | 0.96%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 0.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 4        | 0.96%   |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4        | 0.96%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]      | 4        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 0.72%   |
| Nvidia MCP61 Ethernet                                               | 3        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 3        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 0.72%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 0.72%   |
| ASUS 802.11ac NIC                                                   | 3        | 0.72%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2        | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2        | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 2        | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 2        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 2        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 44.44%  |
| Realtek Semiconductor           | 16       | 13.68%  |
| Ralink Technology               | 9        | 7.69%   |
| MediaTek                        | 9        | 7.69%   |
| Edimax Technology               | 7        | 5.98%   |
| ASUSTek Computer                | 5        | 4.27%   |
| Qualcomm Atheros                | 3        | 2.56%   |
| Broadcom                        | 3        | 2.56%   |
| TP-Link                         | 2        | 1.71%   |
| Ralink                          | 2        | 1.71%   |
| ZyXEL Communications            | 1        | 0.85%   |
| Senao                           | 1        | 0.85%   |
| Qualcomm Atheros Communications | 1        | 0.85%   |
| Microsoft                       | 1        | 0.85%   |
| Mercucys                        | 1        | 0.85%   |
| D-Link System                   | 1        | 0.85%   |
| D-Link                          | 1        | 0.85%   |
| BUFFALO                         | 1        | 0.85%   |
| Accton Technology               | 1        | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14       | 11.67%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9        | 7.5%    |
| Ralink MT7601U Wireless Adapter                                | 7        | 5.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 5%      |
| Intel Wireless-AC 9260                                         | 6        | 5%      |
| Realtek 802.11n WLAN Adapter                                   | 4        | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4        | 3.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 4        | 3.33%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 4        | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3        | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 2.5%    |
| ASUS 802.11ac NIC                                              | 3        | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2        | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 1.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 1.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2        | 1.67%   |
| Intel Wireless 8265 / 8275                                     | 2        | 1.67%   |
| Intel Wireless 3165                                            | 2        | 1.67%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1        | 0.83%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.83%   |
| Senao 802.11 n WLAN                                            | 1        | 0.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1        | 0.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 0.83%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 0.83%   |
| Realtek 802.11ac NIC                                           | 1        | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1        | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 0.83%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1        | 0.83%   |
| Mercucys 802.11n NIC                                           | 1        | 0.83%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 1        | 0.83%   |
| Intel Wireless 8260                                            | 1        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 138      | 49.11%  |
| Intel                    | 90       | 32.03%  |
| Qualcomm Atheros         | 13       | 4.63%   |
| Aquantia                 | 9        | 3.2%    |
| Nvidia                   | 5        | 1.78%   |
| HTC (High Tech Computer) | 4        | 1.42%   |
| Broadcom                 | 4        | 1.42%   |
| Marvell Technology Group | 3        | 1.07%   |
| TP-Link                  | 2        | 0.71%   |
| Samsung Electronics      | 2        | 0.71%   |
| MediaTek                 | 2        | 0.71%   |
| OPPO Electronics         | 1        | 0.36%   |
| Mellanox Technologies    | 1        | 0.36%   |
| IBM                      | 1        | 0.36%   |
| Huawei Technologies      | 1        | 0.36%   |
| Google                   | 1        | 0.36%   |
| ASIX Electronics         | 1        | 0.36%   |
| Apple                    | 1        | 0.36%   |
| American Megatrends      | 1        | 0.36%   |
| 3Com                     | 1        | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 119      | 40.48%  |
| Intel I211 Gigabit Network Connection                               | 20       | 6.8%    |
| Realtek RTL8125 2.5GbE Controller                                   | 16       | 5.44%   |
| Intel Ethernet Controller I225-V                                    | 15       | 5.1%    |
| Intel Ethernet Connection (7) I219-V                                | 8        | 2.72%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 2.38%   |
| Intel I210 Gigabit Network Connection                               | 6        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 6        | 2.04%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 6        | 2.04%   |
| Intel Ethernet Connection I217-V                                    | 5        | 1.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 1.36%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.36%   |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4        | 1.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 1.02%   |
| Nvidia MCP61 Ethernet                                               | 3        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 1.02%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 1.02%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.68%   |
| MediaTek Infinix SMART 6 HD                                         | 2        | 0.68%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller             | 2        | 0.68%   |
| Intel I350 Gigabit Network Connection                               | 2        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.68%   |
| Intel Ethernet Connection (17) I219-V                               | 2        | 0.68%   |
| Intel Ethernet Connection (17) I219-LM                              | 2        | 0.68%   |
| Intel Ethernet Connection (14) I219-V                               | 2        | 0.68%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 0.68%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.68%   |
| TP-Link USB 10/100 LAN                                              | 1        | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 1        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 247      | 67.86%  |
| WiFi     | 113      | 31.04%  |
| Modem    | 3        | 0.82%   |
| Unknown  | 1        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 198      | 76.74%  |
| WiFi     | 59       | 22.87%  |
| Unknown  | 1        | 0.39%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 133      | 52.78%  |
| 2     | 92       | 36.51%  |
| 3     | 13       | 5.16%   |
| 0     | 9        | 3.57%   |
| 6     | 2        | 0.79%   |
| 4     | 2        | 0.79%   |
| 10    | 1        | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 217      | 85.1%   |
| Yes  | 38       | 14.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 51       | 55.43%  |
| Cambridge Silicon Radio         | 17       | 18.48%  |
| MediaTek                        | 8        | 8.7%    |
| Realtek Semiconductor           | 3        | 3.26%   |
| IMC Networks                    | 3        | 3.26%   |
| Broadcom                        | 3        | 3.26%   |
| ASUSTek Computer                | 3        | 3.26%   |
| TP-Link                         | 1        | 1.09%   |
| Ralink                          | 1        | 1.09%   |
| Qualcomm Atheros Communications | 1        | 1.09%   |
| Apple                           | 1        | 1.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 17       | 18.48%  |
| Intel AX200 Bluetooth                                 | 14       | 15.22%  |
| Intel Wireless-AC 3168 Bluetooth                      | 9        | 9.78%   |
| Intel AX201 Bluetooth                                 | 9        | 9.78%   |
| MediaTek Wireless_Device                              | 8        | 8.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6        | 6.52%   |
| Intel Bluetooth wireless interface                    | 5        | 5.43%   |
| Intel AX210 Bluetooth                                 | 4        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 3.26%   |
| Realtek Bluetooth Radio                               | 2        | 2.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 2.17%   |
| ASUS Bluetooth Radio                                  | 2        | 2.17%   |
| TP-Link UB5A Adapter                                  | 1        | 1.09%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.09%   |
| Ralink RT3290 Bluetooth                               | 1        | 1.09%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.09%   |
| Intel Bluetooth Device                                | 1        | 1.09%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.09%   |
| IMC Networks Bluetooth Device                         | 1        | 1.09%   |
| IMC Networks BCM20702A0                               | 1        | 1.09%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 1.09%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.09%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 166      | 41.71%  |
| Nvidia                               | 102      | 25.63%  |
| AMD                                  | 84       | 21.11%  |
| C-Media Electronics                  | 5        | 1.26%   |
| Logitech                             | 4        | 1.01%   |
| ASUSTek Computer                     | 4        | 1.01%   |
| Generalplus Technology               | 3        | 0.75%   |
| XMOS                                 | 2        | 0.5%    |
| Texas Instruments                    | 2        | 0.5%    |
| SAVITECH                             | 2        | 0.5%    |
| Micro Star International             | 2        | 0.5%    |
| KORG                                 | 2        | 0.5%    |
| Focusrite-Novation                   | 2        | 0.5%    |
| Audio-Technica                       | 2        | 0.5%    |
| ZOOM                                 | 1        | 0.25%   |
| Yamaha                               | 1        | 0.25%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.25%   |
| Sony                                 | 1        | 0.25%   |
| Realtek Semiconductor                | 1        | 0.25%   |
| OPPO Electronics                     | 1        | 0.25%   |
| Novra/IDC/Wegener                    | 1        | 0.25%   |
| JMTek                                | 1        | 0.25%   |
| Harman                               | 1        | 0.25%   |
| GN Netcom                            | 1        | 0.25%   |
| Giga-Byte Technology                 | 1        | 0.25%   |
| Elite Silicon                        | 1        | 0.25%   |
| Dell                                 | 1        | 0.25%   |
| Creative Technology                  | 1        | 0.25%   |
| Creative Labs                        | 1        | 0.25%   |
| 2.4G Composite Device                | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 28       | 6.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 20       | 4.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19       | 4.18%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19       | 4.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18       | 3.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 16       | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 3.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 2.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 12       | 2.64%   |
| Intel 200 Series PCH HD Audio                                              | 11       | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 10       | 2.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 2.2%    |
| Intel Alder Lake-S HD Audio Controller                                     | 9        | 1.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 1.98%   |
| Nvidia GP108 High Definition Audio Controller                              | 8        | 1.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7        | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.54%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 1.54%   |
| Nvidia MCP61 High Definition Audio                                         | 6        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.32%   |
| Nvidia GF116 High Definition Audio Controller                              | 6        | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.1%    |
| AMD FCH Azalia Controller                                                  | 5        | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.88%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4        | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.66%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.66%   |
| Logitech H390 headset with microphone                                      | 3        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 28       | 18.3%   |
| Crucial             | 28       | 18.3%   |
| Unknown             | 17       | 11.11%  |
| Transcend           | 17       | 11.11%  |
| A-DATA Technology   | 14       | 9.15%   |
| Micron Technology   | 10       | 6.54%   |
| SK hynix            | 8        | 5.23%   |
| Samsung Electronics | 7        | 4.58%   |
| Unifosa             | 3        | 1.96%   |
| Team                | 3        | 1.96%   |
| G.Skill             | 3        | 1.96%   |
| Silicon Power       | 2        | 1.31%   |
| Patriot             | 2        | 1.31%   |
| Apacer              | 2        | 1.31%   |
| Unknown             | 2        | 1.31%   |
| V-Color             | 1        | 0.65%   |
| UMAX                | 1        | 0.65%   |
| Ramaxel Technology  | 1        | 0.65%   |
| KLEVV               | 1        | 0.65%   |
| GLOWAY              | 1        | 0.65%   |
| CUSO                | 1        | 0.65%   |
| ASint Technology    | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 4        | 2.44%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s         | 3        | 1.83%   |
| Transcend RAM Module 4GB DIMM DDR3 1600MT/s              | 3        | 1.83%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s            | 3        | 1.83%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s         | 3        | 1.83%   |
| Transcend RAM JM1333KLN-4G 4096MB DIMM SDRAM 1600MT/s    | 2        | 1.22%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 2        | 1.22%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 1.22%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 2        | 1.22%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s   | 2        | 1.22%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s     | 2        | 1.22%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                 | 2        | 1.22%   |
| Unknown                                                  | 2        | 1.22%   |
| V-Color RAM TD4G8C11-H11 4GB DIMM DDR3 1600MT/s          | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM 667MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 0.61%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                     | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM 533MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s             | 1        | 0.61%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s          | 1        | 0.61%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s            | 1        | 0.61%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.61%   |
| Unifosa RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.61%   |
| Unifosa RAM GU332G0ALEPR8H2C6F 2GB SODIMM DDR2 800MT/s   | 1        | 0.61%   |
| UMAX RAM D4-3200-16G-2048X8-L 16384MB DIMM DDR4 3200MT/s | 1        | 0.61%   |
| Transcend RAM TX2400KLN-8GK 4096MB DIMM DDR3 1600MT/s    | 1        | 0.61%   |
| Transcend RAM TX2133KLN-8GK 4096MB DIMM DDR3 2000MT/s    | 1        | 0.61%   |
| Transcend RAM TS512MLK72V6N 4GB DIMM DDR3 1600MT/s       | 1        | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 75       | 54.74%  |
| DDR3    | 39       | 28.47%  |
| Unknown | 9        | 6.57%   |
| DDR5    | 5        | 3.65%   |
| SDRAM   | 4        | 2.92%   |
| DDR2    | 4        | 2.92%   |
| DDR     | 1        | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 118      | 86.13%  |
| SODIMM | 19       | 13.87%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 51       | 35.66%  |
| 16384 | 40       | 27.97%  |
| 4096  | 27       | 18.88%  |
| 2048  | 12       | 8.39%   |
| 32768 | 11       | 7.69%   |
| 1024  | 2        | 1.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 33       | 21.85%  |
| 3200  | 24       | 15.89%  |
| 2667  | 14       | 9.27%   |
| 1333  | 12       | 7.95%   |
| 2400  | 11       | 7.28%   |
| 2133  | 9        | 5.96%   |
| 3600  | 7        | 4.64%   |
| 3000  | 5        | 3.31%   |
| 4800  | 4        | 2.65%   |
| 3733  | 4        | 2.65%   |
| 800   | 4        | 2.65%   |
| 667   | 3        | 1.99%   |
| 3466  | 2        | 1.32%   |
| 3400  | 2        | 1.32%   |
| 2933  | 2        | 1.32%   |
| 6000  | 1        | 0.66%   |
| 5200  | 1        | 0.66%   |
| 4333  | 1        | 0.66%   |
| 4000  | 1        | 0.66%   |
| 3866  | 1        | 0.66%   |
| 3800  | 1        | 0.66%   |
| 3334  | 1        | 0.66%   |
| 3134  | 1        | 0.66%   |
| 2866  | 1        | 0.66%   |
| 2666  | 1        | 0.66%   |
| 2000  | 1        | 0.66%   |
| 1632  | 1        | 0.66%   |
| 1066  | 1        | 0.66%   |
| 533   | 1        | 0.66%   |
| 400   | 1        | 0.66%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 14       | 60.87%  |
| Sunplus Innovation Technology | 2        | 8.7%    |
| Samsung Electronics           | 1        | 4.35%   |
| Microdia                      | 1        | 4.35%   |
| KYE Systems (Mouse Systems)   | 1        | 4.35%   |
| Generalplus Technology        | 1        | 4.35%   |
| eMeet                         | 1        | 4.35%   |
| Apple                         | 1        | 4.35%   |
| A4Tech                        | 1        | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 5        | 21.74%  |
| Logitech Webcam C120                            | 3        | 13.04%  |
| Logitech Webcam C930e                           | 2        | 8.7%    |
| Sunplus HanChen Wise Camera                     | 1        | 4.35%   |
| Sunplus ezcap U3 capture-04                     | 1        | 4.35%   |
| Samsung Galaxy series, misc. (MTP mode)         | 1        | 4.35%   |
| Microdia Rapoo camera                           | 1        | 4.35%   |
| Logitech Webcam C170                            | 1        | 4.35%   |
| Logitech QuickCam Home                          | 1        | 4.35%   |
| Logitech QuickCam E 3500                        | 1        | 4.35%   |
| Logitech HD Pro Webcam C920                     | 1        | 4.35%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 4.35%   |
| Generalplus CAMERA - UVC                        | 1        | 4.35%   |
| eMeet HD Webcam C960                            | 1        | 4.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR              | 1        | 4.35%   |
| A4Tech FHD 1080P PC Camera                      | 1        | 4.35%   |

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
| 0     | 205      | 80.08%  |
| 1     | 41       | 16.02%  |
| 2     | 5        | 1.95%   |
| 3     | 3        | 1.17%   |
| 5     | 1        | 0.39%   |
| 4     | 1        | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 24       | 40%     |
| Unassigned class         | 8        | 13.33%  |
| Net/wireless             | 8        | 13.33%  |
| Communication controller | 7        | 11.67%  |
| Card reader              | 3        | 5%      |
| Storage/raid             | 2        | 3.33%   |
| Sound                    | 2        | 3.33%   |
| Net/ethernet             | 2        | 3.33%   |
| Bluetooth                | 2        | 3.33%   |
| Network                  | 1        | 1.67%   |
| Camera                   | 1        | 1.67%   |

