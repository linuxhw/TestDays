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

Total: 318

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 18.04       | 49       | 20.5%   |
| Ubuntu 20.04       | 36       | 15.06%  |
| Ubuntu 22.04       | 9        | 3.77%   |
| OpenMandriva 4.2   | 9        | 3.77%   |
| Debian 11          | 8        | 3.35%   |
| OpenMandriva 23.01 | 6        | 2.51%   |
| Linux Mint 20.3    | 6        | 2.51%   |
| Arch Rolling       | 6        | 2.51%   |
| Xubuntu 18.04      | 5        | 2.09%   |
| Xubuntu 20.04      | 4        | 1.67%   |
| Pop!_OS 20.04      | 4        | 1.67%   |
| OpenMandriva 4.3   | 4        | 1.67%   |
| OpenMandriva 23.03 | 4        | 1.67%   |
| Ubuntu 21.10       | 3        | 1.26%   |
| Ubuntu 19.04       | 3        | 1.26%   |
| Kubuntu 20.04      | 3        | 1.26%   |
| Zorin 16           | 2        | 0.84%   |
| Ubuntu 22.10       | 2        | 0.84%   |
| Ubuntu 20.10       | 2        | 0.84%   |
| Ubuntu 19.10       | 2        | 0.84%   |
| Ubuntu 18.10       | 2        | 0.84%   |
| Ubuntu 16.04       | 2        | 0.84%   |
| ROSA R11           | 2        | 0.84%   |
| openSUSE Leap-15.0 | 2        | 0.84%   |
| OpenMandriva 4.90  | 2        | 0.84%   |
| Linux Mint 20.2    | 2        | 0.84%   |
| KDE neon 20.04     | 2        | 0.84%   |
| Kali 2020.2        | 2        | 0.84%   |
| Fedora 38          | 2        | 0.84%   |
| Fedora 33          | 2        | 0.84%   |
| Endless 3.5.4      | 2        | 0.84%   |
| Debian 10          | 2        | 0.84%   |
| Zorin 15           | 1        | 0.42%   |
| Xubuntu 22.04      | 1        | 0.42%   |
| Xubuntu 19.04      | 1        | 0.42%   |
| Xubuntu 16.04      | 1        | 0.42%   |
| Ubuntu Unity 16.04 | 1        | 0.42%   |
| Ubuntu MATE 22.04  | 1        | 0.42%   |
| Ubuntu MATE 20.04  | 1        | 0.42%   |
| Ubuntu MATE 18.04  | 1        | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 108      | 46.15%  |
| OpenMandriva  | 24       | 10.26%  |
| Linux Mint    | 13       | 5.56%   |
| Xubuntu       | 12       | 5.13%   |
| Debian        | 11       | 4.7%    |
| Fedora        | 10       | 4.27%   |
| Arch          | 7        | 2.99%   |
| Manjaro       | 6        | 2.56%   |
| Pop!_OS       | 5        | 2.14%   |
| Kubuntu       | 5        | 2.14%   |
| Endless       | 4        | 1.71%   |
| Zorin         | 3        | 1.28%   |
| Ubuntu MATE   | 3        | 1.28%   |
| Kali          | 3        | 1.28%   |
| ROSA          | 2        | 0.85%   |
| openSUSE      | 2        | 0.85%   |
| KDE neon      | 2        | 0.85%   |
| Gentoo        | 2        | 0.85%   |
| Clear Linux   | 2        | 0.85%   |
| CentOS        | 2        | 0.85%   |
| Ubuntu Unity  | 1        | 0.43%   |
| Ubuntu Budgie | 1        | 0.43%   |
| Mageia        | 1        | 0.43%   |
| Lubuntu       | 1        | 0.43%   |
| Lilidog       | 1        | 0.43%   |
| Garuda Linux  | 1        | 0.43%   |
| BlackPanther  | 1        | 0.43%   |
| ArcoLinux     | 1        | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 2.7%    |
| 6.1.1-desktop-1omv2290   | 6        | 2.32%   |
| 5.4.0-42-generic         | 5        | 1.93%   |
| 5.8.0-50-generic         | 4        | 1.54%   |
| 5.4.0-45-generic         | 4        | 1.54%   |
| 5.4.0-28-generic         | 4        | 1.54%   |
| 5.16.7-desktop-1omv4003  | 4        | 1.54%   |
| 6.2.6-desktop-1omv2390   | 3        | 1.16%   |
| 5.4.0-58-generic         | 3        | 1.16%   |
| 5.11.0-27-generic        | 3        | 1.16%   |
| 5.0.0-37-generic         | 3        | 1.16%   |
| 5.0.0-23-generic         | 3        | 1.16%   |
| 4.15.0-66-generic        | 3        | 1.16%   |
| 4.15.0-29-generic        | 3        | 1.16%   |
| 5.8.0-55-generic         | 2        | 0.77%   |
| 5.8.0-43-generic         | 2        | 0.77%   |
| 5.8.0-38-generic         | 2        | 0.77%   |
| 5.5.0-kali2-amd64        | 2        | 0.77%   |
| 5.4.0-91-generic         | 2        | 0.77%   |
| 5.4.0-81-generic         | 2        | 0.77%   |
| 5.4.0-80-generic         | 2        | 0.77%   |
| 5.4.0-77-generic         | 2        | 0.77%   |
| 5.4.0-66-generic         | 2        | 0.77%   |
| 5.4.0-54-generic         | 2        | 0.77%   |
| 5.4.0-53-generic         | 2        | 0.77%   |
| 5.4.0-48-generic         | 2        | 0.77%   |
| 5.4.0-122-generic        | 2        | 0.77%   |
| 5.3.0-40-generic         | 2        | 0.77%   |
| 5.3.0-28-generic         | 2        | 0.77%   |
| 5.19.0-38-generic        | 2        | 0.77%   |
| 5.18.12-desktop-3omv4090 | 2        | 0.77%   |
| 5.15.83-1-pve            | 2        | 0.77%   |
| 5.15.0-53-generic        | 2        | 0.77%   |
| 5.15.0-52-generic        | 2        | 0.77%   |
| 5.15.0-48-generic        | 2        | 0.77%   |
| 5.13.0-35-generic        | 2        | 0.77%   |
| 5.13.0-30-generic        | 2        | 0.77%   |
| 5.11.12-desktop-1omv4002 | 2        | 0.77%   |
| 5.11.0-43-generic        | 2        | 0.77%   |
| 5.11.0-40-generic        | 2        | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 52       | 21.4%   |
| 4.15.0  | 27       | 11.11%  |
| 5.8.0   | 13       | 5.35%   |
| 5.15.0  | 12       | 4.94%   |
| 5.11.0  | 11       | 4.53%   |
| 5.0.0   | 11       | 4.53%   |
| 4.18.0  | 10       | 4.12%   |
| 5.3.0   | 9        | 3.7%    |
| 5.13.0  | 8        | 3.29%   |
| 5.10.14 | 7        | 2.88%   |
| 6.1.1   | 6        | 2.47%   |
| 5.19.0  | 6        | 2.47%   |
| 5.16.7  | 4        | 1.65%   |
| 6.2.6   | 3        | 1.23%   |
| 5.10.0  | 3        | 1.23%   |
| 6.2.2   | 2        | 0.82%   |
| 5.5.0   | 2        | 0.82%   |
| 5.18.12 | 2        | 0.82%   |
| 5.15.83 | 2        | 0.82%   |
| 5.15.23 | 2        | 0.82%   |
| 5.11.12 | 2        | 0.82%   |
| 4.19.57 | 2        | 0.82%   |
| 4.19.0  | 2        | 0.82%   |
| 4.12.14 | 2        | 0.82%   |
| 6.3.5   | 1        | 0.41%   |
| 6.3.2   | 1        | 0.41%   |
| 6.2.15  | 1        | 0.41%   |
| 6.2.12  | 1        | 0.41%   |
| 6.2.11  | 1        | 0.41%   |
| 6.2.10  | 1        | 0.41%   |
| 6.2.1   | 1        | 0.41%   |
| 6.1.0   | 1        | 0.41%   |
| 6.0.15  | 1        | 0.41%   |
| 6.0.12  | 1        | 0.41%   |
| 6.0.11  | 1        | 0.41%   |
| 6.0.10  | 1        | 0.41%   |
| 6.0.0   | 1        | 0.41%   |
| 5.9.8   | 1        | 0.41%   |
| 5.8.5   | 1        | 0.41%   |
| 5.8.18  | 1        | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 52       | 21.49%  |
| 4.15    | 27       | 11.16%  |
| 5.15    | 21       | 8.68%   |
| 5.8     | 15       | 6.2%    |
| 5.11    | 14       | 5.79%   |
| 5.10    | 14       | 5.79%   |
| 5.0     | 12       | 4.96%   |
| 4.18    | 11       | 4.55%   |
| 6.2     | 10       | 4.13%   |
| 5.3     | 9        | 3.72%   |
| 5.13    | 8        | 3.31%   |
| 6.1     | 7        | 2.89%   |
| 5.19    | 7        | 2.89%   |
| 5.16    | 6        | 2.48%   |
| 6.0     | 5        | 2.07%   |
| 4.19    | 4        | 1.65%   |
| 5.5     | 3        | 1.24%   |
| 5.18    | 3        | 1.24%   |
| 6.3     | 2        | 0.83%   |
| 4.12    | 2        | 0.83%   |
| 5.9     | 1        | 0.41%   |
| 5.7     | 1        | 0.41%   |
| 5.17    | 1        | 0.41%   |
| 5.14    | 1        | 0.41%   |
| 5.12    | 1        | 0.41%   |
| 5.1     | 1        | 0.41%   |
| 4.9     | 1        | 0.41%   |
| 4.4     | 1        | 0.41%   |
| 4.14    | 1        | 0.41%   |
| 3.10    | 1        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 225      | 96.98%  |
| i686    | 6        | 2.59%   |
| riscv64 | 1        | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 104      | 44.07%  |
| Unknown          | 48       | 20.34%  |
| KDE5             | 39       | 16.53%  |
| XFCE             | 16       | 6.78%   |
| Cinnamon         | 6        | 2.54%   |
| X-Cinnamon       | 5        | 2.12%   |
| MATE             | 5        | 2.12%   |
| KDE              | 3        | 1.27%   |
| LXDE             | 2        | 0.85%   |
| Unity            | 1        | 0.42%   |
| LXQt             | 1        | 0.42%   |
| lightdm-xsession | 1        | 0.42%   |
| KDE4             | 1        | 0.42%   |
| i3               | 1        | 0.42%   |
| Hyprland         | 1        | 0.42%   |
| GNOME Classic    | 1        | 0.42%   |
| Budgie           | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 176      | 73.95%  |
| Wayland | 27       | 11.34%  |
| Unknown | 26       | 10.92%  |
| Tty     | 9        | 3.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 118      | 50.21%  |
| SDDM    | 37       | 15.74%  |
| GDM     | 34       | 14.47%  |
| GDM3    | 23       | 9.79%   |
| LightDM | 13       | 5.53%   |
| TDM     | 8        | 3.4%    |
| KDM     | 2        | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 89       | 37.87%  |
| zh_TW   | 82       | 34.89%  |
| Unknown | 46       | 19.57%  |
| C       | 6        | 2.55%   |
| zh_HK   | 2        | 0.85%   |
| en_HK   | 2        | 0.85%   |
| en_GB   | 2        | 0.85%   |
| zh_CN   | 1        | 0.43%   |
| it_IT   | 1        | 0.43%   |
| es_ES   | 1        | 0.43%   |
| en_SG   | 1        | 0.43%   |
| en_PH   | 1        | 0.43%   |
| en_AU   | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 121      | 51.27%  |
| BIOS | 115      | 48.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 176      | 75.54%  |
| Overlay | 19       | 8.15%   |
| Btrfs   | 18       | 7.73%   |
| Unknown | 7        | 3%      |
| Xfs     | 5        | 2.15%   |
| Tmpfs   | 3        | 1.29%   |
| Ext2    | 3        | 1.29%   |
| Rootfs  | 1        | 0.43%   |
| Ext3    | 1        | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 113      | 48.09%  |
| GPT     | 100      | 42.55%  |
| MBR     | 22       | 9.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 178      | 75.74%  |
| Yes       | 57       | 24.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 55.32%  |
| Yes       | 105      | 44.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 72       | 31.03%  |
| Gigabyte Technology | 59       | 25.43%  |
| MSI                 | 21       | 9.05%   |
| ASRock              | 19       | 8.19%   |
| Acer                | 14       | 6.03%   |
| Hewlett-Packard     | 8        | 3.45%   |
| Dell                | 8        | 3.45%   |
| Unknown             | 8        | 3.45%   |
| Lenovo              | 6        | 2.59%   |
| Intel               | 2        | 0.86%   |
| Win element         | 1        | 0.43%   |
| Supermicro          | 1        | 0.43%   |
| Ruckus Wireless     | 1        | 0.43%   |
| PANSHI              | 1        | 0.43%   |
| OEM                 | 1        | 0.43%   |
| NEXCOM              | 1        | 0.43%   |
| Maxtang             | 1        | 0.43%   |
| Huanan              | 1        | 0.43%   |
| Foxconn             | 1        | 0.43%   |
| eMachines           | 1        | 0.43%   |
| DNI                 | 1        | 0.43%   |
| DFI                 | 1        | 0.43%   |
| BESSTAR Tech        | 1        | 0.43%   |
| ASRockRack          | 1        | 0.43%   |
| Accton              | 1        | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 8        | 3.45%   |
| ASUS All Series                | 6        | 2.59%   |
| Gigabyte B75M-D3H              | 4        | 1.72%   |
| Gigabyte B550I AORUS PRO AX    | 4        | 1.72%   |
| Lenovo ThinkCentre M58 7627AA9 | 3        | 1.29%   |
| Dell Inspiron 531s             | 3        | 1.29%   |
| ASUS M5A78L-M/USB3             | 3        | 1.29%   |
| ASRock X300M-STX               | 3        | 1.29%   |
| MSI MS-7C52                    | 2        | 0.86%   |
| Gigabyte Z97MX-Gaming 5        | 2        | 0.86%   |
| Gigabyte H81N                  | 2        | 0.86%   |
| Gigabyte G31M-ES2L             | 2        | 0.86%   |
| Gigabyte B85M-D2V              | 2        | 0.86%   |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.86%   |
| ASUS ROG STRIX B350-F GAMING   | 2        | 0.86%   |
| ASUS Pro WS X570-ACE           | 2        | 0.86%   |
| ASUS P8Z77-V LX                | 2        | 0.86%   |
| ASUS CM6630_CM6730_CM6830      | 2        | 0.86%   |
| ASRock N68-GS4/USB3 FX         | 2        | 0.86%   |
| ASRock H310M-ITX/ac            | 2        | 0.86%   |
| ASRock A300M-STX               | 2        | 0.86%   |
| ASRock 960GC-GS FX             | 2        | 0.86%   |
| Acer Veriton L480              | 2        | 0.86%   |
| Win element M600               | 1        | 0.43%   |
| Supermicro C9Z490-PGW          | 1        | 0.43%   |
| Ruckus Wireless SCG-100        | 1        | 0.43%   |
| PANSHI B85-S1 V1.0             | 1        | 0.43%   |
| OEM B85 JHS359                 | 1        | 0.43%   |
| NEXCOM SKLD4-P1                | 1        | 0.43%   |
| MSI MS-7D69                    | 1        | 0.43%   |
| MSI MS-7D25                    | 1        | 0.43%   |
| MSI MS-7D19                    | 1        | 0.43%   |
| MSI MS-7D08                    | 1        | 0.43%   |
| MSI MS-7C06                    | 1        | 0.43%   |
| MSI MS-7B89                    | 1        | 0.43%   |
| MSI MS-7B09                    | 1        | 0.43%   |
| MSI MS-7A69                    | 1        | 0.43%   |
| MSI MS-7A32                    | 1        | 0.43%   |
| MSI MS-7982                    | 1        | 0.43%   |
| MSI MS-7918                    | 1        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 11       | 4.74%   |
| ASUS TUF                | 9        | 3.88%   |
| Unknown                 | 8        | 3.45%   |
| Acer Aspire             | 7        | 3.02%   |
| ASUS PRIME              | 6        | 2.59%   |
| ASUS All                | 6        | 2.59%   |
| ASUS M5A78L-M           | 5        | 2.16%   |
| Acer Veriton            | 5        | 2.16%   |
| Gigabyte B75M-D3H       | 4        | 1.72%   |
| Gigabyte B550I          | 4        | 1.72%   |
| Dell Inspiron           | 4        | 1.72%   |
| Lenovo ThinkCentre      | 3        | 1.29%   |
| ASUS Pro                | 3        | 1.29%   |
| ASUS P8Z77-V            | 3        | 1.29%   |
| ASRock X300M-STX        | 3        | 1.29%   |
| MSI MS-7C52             | 2        | 0.86%   |
| Gigabyte Z97MX-Gaming   | 2        | 0.86%   |
| Gigabyte X570S          | 2        | 0.86%   |
| Gigabyte H81N           | 2        | 0.86%   |
| Gigabyte G31M-ES2L      | 2        | 0.86%   |
| Gigabyte B85M-D2V       | 2        | 0.86%   |
| Gigabyte B360           | 2        | 0.86%   |
| Dell Precision          | 2        | 0.86%   |
| Dell OptiPlex           | 2        | 0.86%   |
| ASUS P8H61-M            | 2        | 0.86%   |
| ASUS CM6630             | 2        | 0.86%   |
| ASUS ASUSPRO            | 2        | 0.86%   |
| ASRock N68-GS4          | 2        | 0.86%   |
| ASRock H310M-ITX        | 2        | 0.86%   |
| ASRock A300M-STX        | 2        | 0.86%   |
| ASRock 960GC-GS         | 2        | 0.86%   |
| Win element M600        | 1        | 0.43%   |
| Supermicro C9Z490-PGW   | 1        | 0.43%   |
| Ruckus Wireless SCG-100 | 1        | 0.43%   |
| PANSHI B85-S1           | 1        | 0.43%   |
| OEM B85                 | 1        | 0.43%   |
| NEXCOM SKLD4-P1         | 1        | 0.43%   |
| MSI MS-7D69             | 1        | 0.43%   |
| MSI MS-7D25             | 1        | 0.43%   |
| MSI MS-7D19             | 1        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 29       | 12.5%   |
| 2018    | 28       | 12.07%  |
| 2013    | 21       | 9.05%   |
| 2012    | 20       | 8.62%   |
| 2014    | 19       | 8.19%   |
| 2011    | 16       | 6.9%    |
| 2021    | 15       | 6.47%   |
| 2016    | 12       | 5.17%   |
| 2009    | 12       | 5.17%   |
| 2022    | 10       | 4.31%   |
| 2017    | 10       | 4.31%   |
| 2019    | 9        | 3.88%   |
| 2015    | 9        | 3.88%   |
| 2008    | 9        | 3.88%   |
| 2010    | 8        | 3.45%   |
| 2007    | 4        | 1.72%   |
| Unknown | 1        | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 232      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 228      | 97.85%  |
| Enabled  | 5        | 2.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 232      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 55       | 23.4%   |
| 32.01-64.0      | 46       | 19.57%  |
| 3.01-4.0        | 37       | 15.74%  |
| 8.01-16.0       | 37       | 15.74%  |
| 4.01-8.0        | 33       | 14.04%  |
| 64.01-256.0     | 14       | 5.96%   |
| 24.01-32.0      | 6        | 2.55%   |
| 1.01-2.0        | 6        | 2.55%   |
| More than 256.0 | 1        | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 97       | 38.8%   |
| 2.01-3.0   | 61       | 24.4%   |
| 4.01-8.0   | 38       | 15.2%   |
| 3.01-4.0   | 29       | 11.6%   |
| 8.01-16.0  | 9        | 3.6%    |
| 0.51-1.0   | 7        | 2.8%    |
| 0.01-0.5   | 4        | 1.6%    |
| 24.01-32.0 | 2        | 0.8%    |
| 16.01-24.0 | 2        | 0.8%    |
| 32.01-64.0 | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 89       | 38.2%   |
| 2      | 68       | 29.18%  |
| 3      | 42       | 18.03%  |
| 4      | 14       | 6.01%   |
| 5      | 8        | 3.43%   |
| 0      | 6        | 2.58%   |
| 6      | 4        | 1.72%   |
| 14     | 1        | 0.43%   |
| 7      | 1        | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 157      | 67.38%  |
| Yes       | 76       | 32.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 230      | 99.14%  |
| No        | 2        | 0.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 55.36%  |
| Yes       | 104      | 44.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 64.98%  |
| Yes       | 83       | 35.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Taiwan  | 232      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Taipei            | 65       | 27.2%   |
| New Taipei        | 47       | 19.67%  |
| Taoyuan District  | 20       | 8.37%   |
| Taichung          | 20       | 8.37%   |
| Hsinchu           | 19       | 7.95%   |
| Kaohsiung City    | 15       | 6.28%   |
| Tainan City       | 14       | 5.86%   |
| Chang-hua         | 4        | 1.67%   |
| Miaoli            | 3        | 1.26%   |
| Keelung           | 3        | 1.26%   |
| Hsinchu County    | 3        | 1.26%   |
| Zhudong           | 2        | 0.84%   |
| Yilan             | 2        | 0.84%   |
| Kanzijiao         | 2        | 0.84%   |
| Chiayi City       | 2        | 0.84%   |
| Baitang           | 2        | 0.84%   |
| Yangmei District  | 1        | 0.42%   |
| Xinzhuang         | 1        | 0.42%   |
| Xindian           | 1        | 0.42%   |
| Xiatayou          | 1        | 0.42%   |
| Taoyuan City      | 1        | 0.42%   |
| Taishan           | 1        | 0.42%   |
| Taichung City     | 1        | 0.42%   |
| Sanchong District | 1        | 0.42%   |
| Nantou City       | 1        | 0.42%   |
| Magong            | 1        | 0.42%   |
| Hualien City      | 1        | 0.42%   |
| Fongshan District | 1        | 0.42%   |
| Chongde           | 1        | 0.42%   |
| Chiayi            | 1        | 0.42%   |
| Banqiao           | 1        | 0.42%   |
| Aquan             | 1        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 68       | 106    | 16.27%  |
| Seagate                   | 68       | 118    | 16.27%  |
| Toshiba                   | 40       | 53     | 9.57%   |
| Crucial                   | 29       | 38     | 6.94%   |
| Intel                     | 22       | 32     | 5.26%   |
| Hitachi                   | 21       | 25     | 5.02%   |
| A-DATA Technology         | 19       | 21     | 4.55%   |
| Samsung Electronics       | 14       | 17     | 3.35%   |
| Kingston                  | 14       | 19     | 3.35%   |
| Sandisk                   | 11       | 18     | 2.63%   |
| Unknown                   | 10       | 11     | 2.39%   |
| Transcend                 | 10       | 11     | 2.39%   |
| Apacer                    | 8        | 10     | 1.91%   |
| Plextor                   | 7        | 8      | 1.67%   |
| Micron/Crucial Technology | 5        | 8      | 1.2%    |
| ANACOMDA                  | 5        | 5      | 1.2%    |
| Patriot                   | 4        | 4      | 0.96%   |
| Micron Technology         | 4        | 4      | 0.96%   |
| Silicon Motion            | 3        | 3      | 0.72%   |
| PNY                       | 3        | 3      | 0.72%   |
| Maxtor                    | 3        | 3      | 0.72%   |
| Lite-On                   | 3        | 3      | 0.72%   |
| ADATA Technology          | 3        | 3      | 0.72%   |
| XPG                       | 2        | 2      | 0.48%   |
| Team                      | 2        | 3      | 0.48%   |
| SPCC                      | 2        | 2      | 0.48%   |
| Phison                    | 2        | 3      | 0.48%   |
| OCZ                       | 2        | 2      | 0.48%   |
| Leven                     | 2        | 2      | 0.48%   |
| KLEVV                     | 2        | 2      | 0.48%   |
| Fujitsu                   | 2        | 3      | 0.48%   |
| China                     | 2        | 2      | 0.48%   |
| ASMT                      | 2        | 2      | 0.48%   |
| Wintec                    | 1        | 1      | 0.24%   |
| Unknown (583)             | 1        | 1      | 0.24%   |
| TOPMORE                   | 1        | 1      | 0.24%   |
| SSSTC                     | 1        | 1      | 0.24%   |
| Sony                      | 1        | 1      | 0.24%   |
| Realtek Semiconductor     | 1        | 1      | 0.24%   |
| Pioneer                   | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                          | 13       | 2.82%   |
| Toshiba DT01ACA200 2TB                                          | 10       | 2.17%   |
| Crucial CT500MX500SSD1 500GB                                    | 9        | 1.95%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 8        | 1.74%   |
| Crucial CT1000MX500SSD1 1TB                                     | 8        | 1.74%   |
| Toshiba MQ01ABD032 320GB                                        | 5        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB                                 | 5        | 1.08%   |
| Seagate ST3500418AS 500GB                                       | 5        | 1.08%   |
| WDC WDS250G1B0B-00AS40 250GB SSD                                | 4        | 0.87%   |
| WDC WD10EZEX-75WN4A1 1TB                                        | 4        | 0.87%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 4        | 0.87%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 4        | 0.87%   |
| SanDisk NVMe SSD Drive 500GB                                    | 4        | 0.87%   |
| Patriot Burst 120GB SSD                                         | 4        | 0.87%   |
| A-DATA SU800 512GB SSD                                          | 4        | 0.87%   |
| A-DATA SU800 256GB SSD                                          | 4        | 0.87%   |
| WDC WD6402AAEX-00Z3A0 640GB                                     | 3        | 0.65%   |
| WDC WD3200AAKS-00L9A0 320GB                                     | 3        | 0.65%   |
| WDC WD1600AAJS-08L7A0 160GB                                     | 3        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 3        | 0.65%   |
| Unknown 004G60  4GB                                             | 3        | 0.65%   |
| Silicon Motion NVMe SSD Drive 512GB                             | 3        | 0.65%   |
| Seagate ST750LX003-1AC154 752GB                                 | 3        | 0.65%   |
| PNY CS3030 2TB SSD                                              | 3        | 0.65%   |
| Micron/Crucial NVMe SSD Drive 1TB                               | 3        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                                 | 3        | 0.65%   |
| Apacer 256GB SATA Flash Drive SSD                               | 3        | 0.65%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3        | 0.65%   |
| WDC WDS500G2B0C-00PXH0 500GB                                    | 2        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 2        | 0.43%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 2        | 0.43%   |
| WDC WD20EARX-00PASB0 2TB                                        | 2        | 0.43%   |
| WDC WD1001FALS-00J7B1 1TB                                       | 2        | 0.43%   |
| Unknown SD/MMC/MS PRO 64GB                                      | 2        | 0.43%   |
| Transcend TS128GSSD340 128GB                                    | 2        | 0.43%   |
| Toshiba MQ02ABF050H 500GB                                       | 2        | 0.43%   |
| Toshiba MD06ACA10T 10TB                                         | 2        | 0.43%   |
| Toshiba DT02ABA400 4TB                                          | 2        | 0.43%   |
| SPCC Solid State Disk 120GB                                     | 2        | 0.43%   |
| Seagate ST6000DM003-2CY186 6TB                                  | 2        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 67       | 115    | 36.02%  |
| WDC                 | 51       | 79     | 27.42%  |
| Toshiba             | 38       | 51     | 20.43%  |
| Hitachi             | 21       | 25     | 11.29%  |
| Unknown             | 3        | 3      | 1.61%   |
| Maxtor              | 3        | 3      | 1.61%   |
| Samsung Electronics | 1        | 2      | 0.54%   |
| HGST                | 1        | 2      | 0.54%   |
| Fujitsu             | 1        | 2      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 28       | 36     | 19.05%  |
| A-DATA Technology   | 16       | 18     | 10.88%  |
| Intel               | 13       | 18     | 8.84%   |
| WDC                 | 12       | 17     | 8.16%   |
| Transcend           | 10       | 11     | 6.8%    |
| Kingston            | 8        | 10     | 5.44%   |
| Plextor             | 6        | 7      | 4.08%   |
| Apacer              | 6        | 8      | 4.08%   |
| ANACOMDA            | 5        | 5      | 3.4%    |
| Samsung Electronics | 4        | 4      | 2.72%   |
| Patriot             | 4        | 4      | 2.72%   |
| SanDisk             | 3        | 4      | 2.04%   |
| Micron Technology   | 3        | 3      | 2.04%   |
| Toshiba             | 2        | 2      | 1.36%   |
| Team                | 2        | 3      | 1.36%   |
| SPCC                | 2        | 2      | 1.36%   |
| OCZ                 | 2        | 2      | 1.36%   |
| Leven               | 2        | 2      | 1.36%   |
| KLEVV               | 2        | 2      | 1.36%   |
| China               | 2        | 2      | 1.36%   |
| ASMT                | 2        | 2      | 1.36%   |
| Wintec              | 1        | 1      | 0.68%   |
| Unknown             | 1        | 1      | 0.68%   |
| Sony                | 1        | 1      | 0.68%   |
| OCZ-VECT            | 1        | 1      | 0.68%   |
| OCZ-REVODRIVE       | 1        | 4      | 0.68%   |
| MemoCom             | 1        | 2      | 0.68%   |
| LITEONIT            | 1        | 1      | 0.68%   |
| Hewlett-Packard     | 1        | 1      | 0.68%   |
| Fujitsu             | 1        | 1      | 0.68%   |
| EZLINK              | 1        | 1      | 0.68%   |
| AXIOMTEK            | 1        | 1      | 0.68%   |
| ATP                 | 1        | 1      | 0.68%   |
| AGI                 | 1        | 2      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 148      | 282    | 43.15%  |
| SSD     | 118      | 180    | 34.4%   |
| NVMe    | 69       | 106    | 20.12%  |
| MMC     | 4        | 4      | 1.17%   |
| Unknown | 4        | 6      | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 204      | 443    | 70.59%  |
| NVMe | 68       | 105    | 23.53%  |
| SAS  | 13       | 26     | 4.5%    |
| MMC  | 4        | 4      | 1.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 142      | 241    | 48.3%   |
| 0.51-1.0   | 83       | 113    | 28.23%  |
| 1.01-2.0   | 37       | 58     | 12.59%  |
| 3.01-4.0   | 12       | 21     | 4.08%   |
| 2.01-3.0   | 9        | 11     | 3.06%   |
| 4.01-10.0  | 8        | 15     | 2.72%   |
| 10.01-20.0 | 3        | 3      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 57       | 23.55%  |
| 251-500        | 38       | 15.7%   |
| 501-1000       | 28       | 11.57%  |
| 1001-2000      | 27       | 11.16%  |
| 2001-3000      | 21       | 8.68%   |
| 51-100         | 18       | 7.44%   |
| More than 3000 | 17       | 7.02%   |
| 1-20           | 15       | 6.2%    |
| 21-50          | 12       | 4.96%   |
| Unknown        | 9        | 3.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 92       | 36.95%  |
| 101-250        | 32       | 12.85%  |
| 21-50          | 31       | 12.45%  |
| 51-100         | 31       | 12.45%  |
| 1001-2000      | 16       | 6.43%   |
| 251-500        | 15       | 6.02%   |
| 501-1000       | 13       | 5.22%   |
| Unknown        | 9        | 3.61%   |
| 2001-3000      | 6        | 2.41%   |
| More than 3000 | 4        | 1.61%   |

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
| Detected | 135      | 348    | 52.94%  |
| Works    | 95       | 198    | 37.25%  |
| Malfunc  | 25       | 32     | 9.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 160      | 49.23%  |
| AMD                            | 62       | 19.08%  |
| SanDisk                        | 15       | 4.62%   |
| ASMedia Technology             | 14       | 4.31%   |
| Phison Electronics             | 10       | 3.08%   |
| Samsung Electronics            | 9        | 2.77%   |
| Nvidia                         | 9        | 2.77%   |
| Micron/Crucial Technology      | 7        | 2.15%   |
| Kingston Technology Company    | 6        | 1.85%   |
| ADATA Technology               | 6        | 1.85%   |
| Marvell Technology Group       | 5        | 1.54%   |
| Silicon Motion                 | 4        | 1.23%   |
| Lite-On Technology             | 3        | 0.92%   |
| JMicron Technology             | 3        | 0.92%   |
| Solid State Storage Technology | 2        | 0.62%   |
| Realtek Semiconductor          | 2        | 0.62%   |
| LSI Logic / Symbios Logic      | 2        | 0.62%   |
| Silicon Image                  | 1        | 0.31%   |
| Seagate Technology             | 1        | 0.31%   |
| Micron Technology              | 1        | 0.31%   |
| KIOXIA                         | 1        | 0.31%   |
| Integrated Technology Express  | 1        | 0.31%   |
| Broadcom / LSI                 | 1        | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 37       | 9.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 6.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 2.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 2.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 2.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 7        | 1.72%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 7        | 1.72%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 1.47%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.47%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6        | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 1.47%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5        | 1.23%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.23%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.23%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.98%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.98%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 4        | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 0.98%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.98%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.98%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.98%   |
| ASMedia 106x SATA/RAID Controller                                                       | 4        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 186      | 57.23%  |
| NVMe | 68       | 20.92%  |
| IDE  | 56       | 17.23%  |
| RAID | 11       | 3.38%   |
| SAS  | 3        | 0.92%   |
| SCSI | 1        | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 160      | 68.97%  |
| AMD           | 71       | 30.6%   |
| sifive,u74-mc | 1        | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 2.14%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 2.14%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.14%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 3        | 1.28%   |
| Intel Pentium CPU G840 @ 2.80GHz            | 3        | 1.28%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.28%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.28%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 1.28%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.28%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.28%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 1.28%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 3        | 1.28%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1.28%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 0.85%   |
| Intel Pentium Gold G5500 CPU @ 3.80GHz      | 2        | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.85%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.85%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 0.85%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.85%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.85%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 0.85%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 2        | 0.85%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.85%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 0.85%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.85%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.85%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 0.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.85%   |
| Intel 12th Gen Core i7-12700                | 2        | 0.85%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 0.85%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.85%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 0.85%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 0.85%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 37       | 15.81%  |
| Intel Core i7           | 30       | 12.82%  |
| Intel Core i3           | 26       | 11.11%  |
| AMD Ryzen 5             | 19       | 8.12%   |
| Intel Xeon              | 15       | 6.41%   |
| AMD Ryzen 7             | 12       | 5.13%   |
| Other                   | 10       | 4.27%   |
| Intel Celeron           | 10       | 4.27%   |
| Intel Core 2 Quad       | 9        | 3.85%   |
| AMD Ryzen 9             | 9        | 3.85%   |
| Intel Pentium           | 7        | 2.99%   |
| AMD FX                  | 7        | 2.99%   |
| Intel Core 2 Duo        | 5        | 2.14%   |
| Intel Pentium Gold      | 4        | 1.71%   |
| AMD Athlon 64 X2        | 4        | 1.71%   |
| Intel Genuine           | 3        | 1.28%   |
| Intel Core i9           | 3        | 1.28%   |
| AMD Ryzen 5 PRO         | 3        | 1.28%   |
| Intel Pentium Dual-Core | 2        | 0.85%   |
| AMD Phenom II X4        | 2        | 0.85%   |
| AMD Athlon II X4        | 2        | 0.85%   |
| AMD Athlon II X2        | 2        | 0.85%   |
| AMD A8                  | 2        | 0.85%   |
| Intel Pentium Silver    | 1        | 0.43%   |
| Intel Atom              | 1        | 0.43%   |
| AMD Sempron             | 1        | 0.43%   |
| AMD Ryzen Threadripper  | 1        | 0.43%   |
| AMD Ryzen 7 PRO         | 1        | 0.43%   |
| AMD Ryzen 3             | 1        | 0.43%   |
| AMD Phenom II X6        | 1        | 0.43%   |
| AMD Phenom II X2        | 1        | 0.43%   |
| AMD Athlon              | 1        | 0.43%   |
| AMD A4                  | 1        | 0.43%   |
| AMD A10                 | 1        | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 96       | 41.2%   |
| 2       | 58       | 24.89%  |
| 6       | 28       | 12.02%  |
| 8       | 26       | 11.16%  |
| 12      | 10       | 4.29%   |
| 16      | 7        | 3%      |
| 3       | 2        | 0.86%   |
| 48      | 1        | 0.43%   |
| 44      | 1        | 0.43%   |
| 28      | 1        | 0.43%   |
| 24      | 1        | 0.43%   |
| 18      | 1        | 0.43%   |
| Unknown | 1        | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 226      | 97.41%  |
| 2       | 5        | 2.16%   |
| Unknown | 1        | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 132      | 56.41%  |
| 1       | 101      | 43.16%  |
| Unknown | 1        | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 226      | 97%     |
| Unknown        | 7        | 3%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 20.08%  |
| 0x306c3    | 26       | 10.88%  |
| 0x306a9    | 15       | 6.28%   |
| 0x206a7    | 13       | 5.44%   |
| 0x506e3    | 8        | 3.35%   |
| 0x1067a    | 8        | 3.35%   |
| 0x08701021 | 8        | 3.35%   |
| 0x906ea    | 7        | 2.93%   |
| 0x906eb    | 6        | 2.51%   |
| 0x90672    | 4        | 1.67%   |
| 0x706a1    | 4        | 1.67%   |
| 0x10676    | 4        | 1.67%   |
| 0x06000852 | 4        | 1.67%   |
| 0xa0655    | 3        | 1.26%   |
| 0xa0653    | 3        | 1.26%   |
| 0x0810100b | 3        | 1.26%   |
| 0x08001138 | 3        | 1.26%   |
| 0x010000c8 | 3        | 1.26%   |
| 0xa0671    | 2        | 0.84%   |
| 0x906ed    | 2        | 0.84%   |
| 0x6fb      | 2        | 0.84%   |
| 0x50654    | 2        | 0.84%   |
| 0x206c2    | 2        | 0.84%   |
| 0x106e5    | 2        | 0.84%   |
| 0x10677    | 2        | 0.84%   |
| 0x0a50000d | 2        | 0.84%   |
| 0x0a50000c | 2        | 0.84%   |
| 0x0a20120a | 2        | 0.84%   |
| 0x0a201016 | 2        | 0.84%   |
| 0x0a201009 | 2        | 0.84%   |
| 0x08600106 | 2        | 0.84%   |
| 0x08101016 | 2        | 0.84%   |
| 0x0800820d | 2        | 0.84%   |
| 0x0800820b | 2        | 0.84%   |
| 0x06001119 | 2        | 0.84%   |
| 0xb0671    | 1        | 0.42%   |
| 0x906c0    | 1        | 0.42%   |
| 0x90671    | 1        | 0.42%   |
| 0x90661    | 1        | 0.42%   |
| 0x606a4    | 1        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 36       | 15.45%  |
| KabyLake         | 20       | 8.58%   |
| IvyBridge        | 18       | 7.73%   |
| SandyBridge      | 17       | 7.3%    |
| Zen 2            | 16       | 6.87%   |
| Penryn           | 16       | 6.87%   |
| Skylake          | 15       | 6.44%   |
| Zen 3            | 13       | 5.58%   |
| Zen              | 10       | 4.29%   |
| K10              | 9        | 3.86%   |
| Piledriver       | 8        | 3.43%   |
| CometLake        | 8        | 3.43%   |
| Unknown          | 8        | 3.43%   |
| Zen+             | 6        | 2.58%   |
| Westmere         | 4        | 1.72%   |
| K8 Hammer        | 4        | 1.72%   |
| Goldmont plus    | 4        | 1.72%   |
| Nehalem          | 3        | 1.29%   |
| Icelake          | 3        | 1.29%   |
| Tremont          | 2        | 0.86%   |
| Jaguar           | 2        | 0.86%   |
| Core             | 2        | 0.86%   |
| Broadwell        | 2        | 0.86%   |
| Alderlake Hybrid | 2        | 0.86%   |
| Steamroller      | 1        | 0.43%   |
| Silvermont       | 1        | 0.43%   |
| Goldmont         | 1        | 0.43%   |
| Bulldozer        | 1        | 0.43%   |
| Bonnell          | 1        | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 98       | 41.18%  |
| Intel                      | 85       | 35.71%  |
| AMD                        | 50       | 21.01%  |
| ASPEED Technology          | 3        | 1.26%   |
| Matrox Electronics Systems | 2        | 0.84%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 5.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 4.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 3.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 3.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 2.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.92%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 2.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.5%    |
| Intel HD Graphics 530                                                       | 5        | 2.08%   |
| Intel AlderLake-S GT1                                                       | 5        | 2.08%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.67%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 4        | 1.67%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.67%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.67%   |
| AMD Renoir                                                                  | 4        | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.67%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.25%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.25%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.25%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 1.25%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3        | 1.25%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.25%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.83%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.83%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.83%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.83%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.83%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.83%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 0.83%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 0.83%   |
| AMD Cape Verde LE [Radeon HD 7730/8730]                                     | 2        | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 91       | 38.89%  |
| 1 x Intel      | 81       | 34.62%  |
| 1 x AMD        | 48       | 20.51%  |
| Intel + Nvidia | 5        | 2.14%   |
| Other          | 3        | 1.28%   |
| 1 x Matrox     | 2        | 0.85%   |
| 1 x ASPEED     | 2        | 0.85%   |
| AMD + Nvidia   | 1        | 0.43%   |
| AMD + ASPEED   | 1        | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 170      | 71.43%  |
| Proprietary | 51       | 21.43%  |
| Unknown     | 17       | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 114      | 47.3%   |
| 1.01-2.0   | 31       | 12.86%  |
| 0.01-0.5   | 25       | 10.37%  |
| 0.51-1.0   | 22       | 9.13%   |
| 5.01-6.0   | 16       | 6.64%   |
| 3.01-4.0   | 16       | 6.64%   |
| 7.01-8.0   | 8        | 3.32%   |
| 8.01-16.0  | 6        | 2.49%   |
| 2.01-3.0   | 3        | 1.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Ancor Communications    | 32       | 13.85%  |
| BenQ                    | 29       | 12.55%  |
| Acer                    | 23       | 9.96%   |
| ViewSonic               | 22       | 9.52%   |
| Dell                    | 14       | 6.06%   |
| Goldstar                | 11       | 4.76%   |
| AOC                     | 11       | 4.76%   |
| Samsung Electronics     | 10       | 4.33%   |
| Philips                 | 10       | 4.33%   |
| ASUSTek Computer        | 8        | 3.46%   |
| Hewlett-Packard         | 7        | 3.03%   |
| NEX                     | 6        | 2.6%    |
| Eizo                    | 6        | 2.6%    |
| Unknown                 | 5        | 2.16%   |
| Envision Peripherals    | 5        | 2.16%   |
| LG Electronics          | 4        | 1.73%   |
| Vizio                   | 3        | 1.3%    |
| Unknown (XXX)           | 2        | 0.87%   |
| Sony                    | 2        | 0.87%   |
| Gigabyte Technology     | 2        | 0.87%   |
| AUS                     | 2        | 0.87%   |
| Unknown                 | 2        | 0.87%   |
| ___                     | 1        | 0.43%   |
| VIZ                     | 1        | 0.43%   |
| Toshiba                 | 1        | 0.43%   |
| Tatung                  | 1        | 0.43%   |
| NEC Computers           | 1        | 0.43%   |
| MSI                     | 1        | 0.43%   |
| KTC                     | 1        | 0.43%   |
| KEB                     | 1        | 0.43%   |
| INS                     | 1        | 0.43%   |
| HWL                     | 1        | 0.43%   |
| GLE                     | 1        | 0.43%   |
| Chi Mei Optoelectronics | 1        | 0.43%   |
| Arnos Instruments       | 1        | 0.43%   |
| AOpen                   | 1        | 0.43%   |
| AMT International       | 1        | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 7        | 2.98%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 4        | 1.7%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 1.28%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 3        | 1.28%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3        | 1.28%   |
| Ancor Communications ASUS VS207 ACI20F2 1600x900 432x240mm 19.5-inch  | 3        | 1.28%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 530x300mm 24.0-inch         | 2        | 0.85%   |
| ViewSonic VA916 Series VSC7C20 1280x1024 376x301mm 19.0-inch          | 2        | 0.85%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 2        | 0.85%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.85%   |
| Unknown LCD Monitor Kingston Technology 43 TV 1920x1080               | 2        | 0.85%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.85%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 2        | 0.85%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.85%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.85%   |
| Envision Peripherals LED H963wLs ENV1963 1366x768 410x230mm 18.5-inch | 2        | 0.85%   |
| Envision Peripherals LED 2271wh ENV2271 1920x1080 476x268mm 21.5-inch | 2        | 0.85%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 2        | 0.85%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 2        | 0.85%   |
| BenQ GL2450H BNQ78A6 1920x1080 531x298mm 24.0-inch                    | 2        | 0.85%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                   | 2        | 0.85%   |
| BenQ EW2730V BNQ7931 1920x1080 597x336mm 27.0-inch                    | 2        | 0.85%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 2        | 0.85%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 2        | 0.85%   |
| Ancor Communications VX239 ACI23E1 1920x1080 510x290mm 23.1-inch      | 2        | 0.85%   |
| Ancor Communications ASUS VW247 ACI2496 1920x1080 531x299mm 24.0-inch | 2        | 0.85%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch | 2        | 0.85%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch  | 2        | 0.85%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 477x268mm 21.5-inch | 2        | 0.85%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 510x290mm 23.1-inch | 2        | 0.85%   |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                     | 2        | 0.85%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 2        | 0.85%   |
| Unknown                                                               | 2        | 0.85%   |
| ___ LCD Monitor ___0217 1920x1080 930x530mm 42.1-inch                 | 1        | 0.43%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.43%   |
| Vizio V320M-TW VIZ0058 1920x1080 700x390mm 31.5-inch                  | 1        | 0.43%   |
| Vizio M3D470KD VIZ0078 1920x1080 1039x584mm 46.9-inch                 | 1        | 0.43%   |
| VIZ LCD Monitor SV472XVT-T 1920x1080                                  | 1        | 0.43%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch         | 1        | 0.43%   |
| ViewSonic VX2263 Series VSC692F 1920x1080 476x268mm 21.5-inch         | 1        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 123      | 55.16%  |
| 2560x1440 (QHD)    | 22       | 9.87%   |
| 3840x2160 (4K)     | 13       | 5.83%   |
| 1366x768 (WXGA)    | 11       | 4.93%   |
| 1680x1050 (WSXGA+) | 9        | 4.04%   |
| 1280x1024 (SXGA)   | 9        | 4.04%   |
| 2560x1080          | 7        | 3.14%   |
| 1600x900 (HD+)     | 7        | 3.14%   |
| 1920x1200 (WUXGA)  | 6        | 2.69%   |
| 1440x900 (WXGA+)   | 6        | 2.69%   |
| 3840x1080          | 2        | 0.9%    |
| 3440x1440          | 2        | 0.9%    |
| 1024x768 (XGA)     | 2        | 0.9%    |
| Unknown            | 2        | 0.9%    |
| 1920x540           | 1        | 0.45%   |
| 1360x768           | 1        | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 38       | 16.52%  |
| 21      | 37       | 16.09%  |
| 24      | 36       | 15.65%  |
| Unknown | 32       | 13.91%  |
| 23      | 21       | 9.13%   |
| 19      | 19       | 8.26%   |
| 31      | 8        | 3.48%   |
| 18      | 7        | 3.04%   |
| 34      | 6        | 2.61%   |
| 22      | 6        | 2.61%   |
| 15      | 4        | 1.74%   |
| 54      | 2        | 0.87%   |
| 43      | 2        | 0.87%   |
| 20      | 2        | 0.87%   |
| 17      | 2        | 0.87%   |
| 69      | 1        | 0.43%   |
| 65      | 1        | 0.43%   |
| 48      | 1        | 0.43%   |
| 46      | 1        | 0.43%   |
| 42      | 1        | 0.43%   |
| 41      | 1        | 0.43%   |
| 26      | 1        | 0.43%   |
| 25      | 1        | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 85       | 37.95%  |
| 401-500     | 64       | 28.57%  |
| Unknown     | 32       | 14.29%  |
| 601-700     | 15       | 6.7%    |
| 701-800     | 6        | 2.68%   |
| 351-400     | 6        | 2.68%   |
| 301-350     | 5        | 2.23%   |
| 1001-1500   | 5        | 2.23%   |
| 901-1000    | 4        | 1.79%   |
| 201-300     | 1        | 0.45%   |
| 1501-2000   | 1        | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 144      | 65.45%  |
| Unknown | 31       | 14.09%  |
| 16/10   | 25       | 11.36%  |
| 5/4     | 8        | 3.64%   |
| 21/9    | 6        | 2.73%   |
| 4/3     | 2        | 0.91%   |
| 32/9    | 2        | 0.91%   |
| 6/5     | 1        | 0.45%   |
| 3/2     | 1        | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 76       | 33.33%  |
| 301-350        | 39       | 17.11%  |
| 151-200        | 35       | 15.35%  |
| Unknown        | 32       | 14.04%  |
| 351-500        | 14       | 6.14%   |
| 251-300        | 9        | 3.95%   |
| 141-150        | 9        | 3.95%   |
| 501-1000       | 6        | 2.63%   |
| More than 1000 | 4        | 1.75%   |
| 101-110        | 2        | 0.88%   |
| 121-130        | 1        | 0.44%   |
| 111-120        | 1        | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 133      | 59.11%  |
| 101-120 | 48       | 21.33%  |
| Unknown | 32       | 14.22%  |
| 121-160 | 8        | 3.56%   |
| 1-50    | 3        | 1.33%   |
| 161-240 | 1        | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 196      | 83.4%   |
| 0     | 20       | 8.51%   |
| 2     | 18       | 7.66%   |
| 3     | 1        | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 135      | 39.94%  |
| Intel                                  | 102      | 30.18%  |
| Qualcomm Atheros                       | 15       | 4.44%   |
| MediaTek                               | 10       | 2.96%   |
| Ralink Technology                      | 9        | 2.66%   |
| Aquantia                               | 9        | 2.66%   |
| Edimax Technology                      | 7        | 2.07%   |
| Broadcom                               | 7        | 2.07%   |
| Nvidia                                 | 5        | 1.48%   |
| HTC (High Tech Computer)               | 4        | 1.18%   |
| ASUSTek Computer                       | 4        | 1.18%   |
| TP-Link                                | 3        | 0.89%   |
| Marvell Technology Group               | 3        | 0.89%   |
| Samsung Electronics                    | 2        | 0.59%   |
| Ralink                                 | 2        | 0.59%   |
| ZyXEL Communications                   | 1        | 0.3%    |
| SparkFun                               | 1        | 0.3%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.3%    |
| Senao                                  | 1        | 0.3%    |
| Qualcomm Atheros Communications        | 1        | 0.3%    |
| Prolific Technology                    | 1        | 0.3%    |
| OPPO Electronics                       | 1        | 0.3%    |
| Microsoft                              | 1        | 0.3%    |
| Mercucys                               | 1        | 0.3%    |
| Mellanox Technologies                  | 1        | 0.3%    |
| IBM                                    | 1        | 0.3%    |
| Huawei Technologies                    | 1        | 0.3%    |
| Google                                 | 1        | 0.3%    |
| D-Link System                          | 1        | 0.3%    |
| D-Link                                 | 1        | 0.3%    |
| BUFFALO                                | 1        | 0.3%    |
| Arduino SA                             | 1        | 0.3%    |
| Apple                                  | 1        | 0.3%    |
| American Megatrends                    | 1        | 0.3%    |
| Accton Technology                      | 1        | 0.3%    |
| 3Com                                   | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 110      | 28.8%   |
| Intel I211 Gigabit Network Connection                               | 17       | 4.45%   |
| Realtek RTL8125 2.5GbE Controller                                   | 14       | 3.66%   |
| Intel Wi-Fi 6 AX200                                                 | 13       | 3.4%    |
| Intel Ethernet Controller I225-V                                    | 13       | 3.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 9        | 2.36%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 2.09%   |
| Ralink MT7601U Wireless Adapter                                     | 7        | 1.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 6        | 1.57%   |
| Intel Wireless-AC 9260                                              | 6        | 1.57%   |
| Intel I210 Gigabit Network Connection                               | 6        | 1.57%   |
| Intel Ethernet Connection (2) I219-V                                | 6        | 1.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 6        | 1.57%   |
| Intel Ethernet Connection I217-V                                    | 5        | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 5        | 1.31%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                          | 4        | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4        | 1.05%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.05%   |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4        | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]      | 4        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3        | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 0.79%   |
| Nvidia MCP61 Ethernet                                               | 3        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 3        | 0.79%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2        | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 2        | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 2        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.52%   |
| MediaTek TECNO SPARK 9T                                             | 2        | 0.52%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller             | 2        | 0.52%   |
| Intel Wireless 8265 / 8275                                          | 2        | 0.52%   |
| Intel Wireless 3165                                                 | 2        | 0.52%   |
| Intel I350 Gigabit Network Connection                               | 2        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 47       | 43.52%  |
| Realtek Semiconductor           | 15       | 13.89%  |
| Ralink Technology               | 9        | 8.33%   |
| MediaTek                        | 8        | 7.41%   |
| Edimax Technology               | 7        | 6.48%   |
| ASUSTek Computer                | 4        | 3.7%    |
| Broadcom                        | 3        | 2.78%   |
| TP-Link                         | 2        | 1.85%   |
| Ralink                          | 2        | 1.85%   |
| Qualcomm Atheros                | 2        | 1.85%   |
| ZyXEL Communications            | 1        | 0.93%   |
| Senao                           | 1        | 0.93%   |
| Qualcomm Atheros Communications | 1        | 0.93%   |
| Microsoft                       | 1        | 0.93%   |
| Mercucys                        | 1        | 0.93%   |
| D-Link System                   | 1        | 0.93%   |
| D-Link                          | 1        | 0.93%   |
| BUFFALO                         | 1        | 0.93%   |
| Accton Technology               | 1        | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 13       | 11.93%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 9        | 8.26%   |
| Ralink MT7601U Wireless Adapter                                 | 7        | 6.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 6        | 5.5%    |
| Intel Wireless-AC 9260                                          | 6        | 5.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                      | 4        | 3.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 4        | 3.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 4        | 3.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 3        | 2.75%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 3        | 2.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 2        | 1.83%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 2        | 1.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 2        | 1.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 2        | 1.83%   |
| Intel Wireless 8265 / 8275                                      | 2        | 1.83%   |
| Intel Wireless 3165                                             | 2        | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 2        | 1.83%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 2        | 1.83%   |
| ASUS 802.11ac NIC                                               | 2        | 1.83%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]    | 1        | 0.92%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1        | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1        | 0.92%   |
| Senao 802.11 n WLAN                                             | 1        | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 1        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 1        | 0.92%   |
| Realtek 802.11ac NIC                                            | 1        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                       | 1        | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                       | 1        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1        | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                 | 1        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1        | 0.92%   |
| Microsoft Xbox 360 Wireless Adapter                             | 1        | 0.92%   |
| Mercucys 802.11n NIC                                            | 1        | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 1        | 0.92%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter              | 1        | 0.92%   |
| Intel Wireless 8260                                             | 1        | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 1        | 0.92%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection        | 1        | 0.92%   |
| Intel 700 Series Chipset Family Wi-Fi                           | 1        | 0.92%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 127      | 49.22%  |
| Intel                    | 80       | 31.01%  |
| Qualcomm Atheros         | 13       | 5.04%   |
| Aquantia                 | 9        | 3.49%   |
| Nvidia                   | 5        | 1.94%   |
| HTC (High Tech Computer) | 4        | 1.55%   |
| Broadcom                 | 4        | 1.55%   |
| Marvell Technology Group | 3        | 1.16%   |
| Samsung Electronics      | 2        | 0.78%   |
| MediaTek                 | 2        | 0.78%   |
| TP-Link                  | 1        | 0.39%   |
| OPPO Electronics         | 1        | 0.39%   |
| Mellanox Technologies    | 1        | 0.39%   |
| IBM                      | 1        | 0.39%   |
| Huawei Technologies      | 1        | 0.39%   |
| Google                   | 1        | 0.39%   |
| Apple                    | 1        | 0.39%   |
| American Megatrends      | 1        | 0.39%   |
| 3Com                     | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 110      | 40.89%  |
| Intel I211 Gigabit Network Connection                               | 17       | 6.32%   |
| Realtek RTL8125 2.5GbE Controller                                   | 14       | 5.2%    |
| Intel Ethernet Controller I225-V                                    | 13       | 4.83%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 2.97%   |
| Intel I210 Gigabit Network Connection                               | 6        | 2.23%   |
| Intel Ethernet Connection (2) I219-V                                | 6        | 2.23%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 6        | 2.23%   |
| Intel Ethernet Connection I217-V                                    | 5        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 5        | 1.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 1.49%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.49%   |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4        | 1.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 1.12%   |
| Nvidia MCP61 Ethernet                                               | 3        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 1.12%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.74%   |
| MediaTek TECNO SPARK 9T                                             | 2        | 0.74%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller             | 2        | 0.74%   |
| Intel I350 Gigabit Network Connection                               | 2        | 0.74%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.74%   |
| Intel Ethernet Connection (17) I219-LM                              | 2        | 0.74%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 0.74%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.74%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 0.74%   |
| TP-Link USB 10/100 LAN                                              | 1        | 0.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 1        | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.37%   |
| OPPO SM8350-MTP _SN:1518BD09                                        | 1        | 0.37%   |
| Nvidia MCP79 Ethernet                                               | 1        | 0.37%   |
| Nvidia MCP65 Ethernet                                               | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 228      | 67.86%  |
| WiFi     | 104      | 30.95%  |
| Modem    | 3        | 0.89%   |
| Unknown  | 1        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 181      | 76.05%  |
| WiFi     | 56       | 23.53%  |
| Unknown  | 1        | 0.42%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 125      | 53.65%  |
| 2     | 82       | 35.19%  |
| 3     | 12       | 5.15%   |
| 0     | 9        | 3.86%   |
| 6     | 2        | 0.86%   |
| 4     | 2        | 0.86%   |
| 10    | 1        | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 199      | 84.68%  |
| Yes  | 36       | 15.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 46       | 55.42%  |
| Cambridge Silicon Radio | 16       | 19.28%  |
| MediaTek                | 7        | 8.43%   |
| Realtek Semiconductor   | 3        | 3.61%   |
| Broadcom                | 3        | 3.61%   |
| ASUSTek Computer        | 3        | 3.61%   |
| IMC Networks            | 2        | 2.41%   |
| TP-Link                 | 1        | 1.2%    |
| Ralink                  | 1        | 1.2%    |
| Apple                   | 1        | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 16       | 19.28%  |
| Intel AX200 Bluetooth                                 | 13       | 15.66%  |
| Intel Wireless-AC 3168 Bluetooth                      | 9        | 10.84%  |
| MediaTek Wireless_Device                              | 7        | 8.43%   |
| Intel AX201 Bluetooth                                 | 7        | 8.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6        | 7.23%   |
| Intel Bluetooth wireless interface                    | 5        | 6.02%   |
| Intel AX210 Bluetooth                                 | 4        | 4.82%   |
| Realtek Bluetooth Radio                               | 2        | 2.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 2.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 2.41%   |
| ASUS Bluetooth Radio                                  | 2        | 2.41%   |
| TP-Link UB500 Adapter                                 | 1        | 1.2%    |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.2%    |
| Ralink RT3290 Bluetooth                               | 1        | 1.2%    |
| IMC Networks Bluetooth Device                         | 1        | 1.2%    |
| IMC Networks BCM20702A0                               | 1        | 1.2%    |
| Broadcom BCM2045 Bluetooth                            | 1        | 1.2%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.2%    |
| Apple Bluetooth USB Host Controller                   | 1        | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 152      | 41.87%  |
| Nvidia                               | 94       | 25.9%   |
| AMD                                  | 78       | 21.49%  |
| C-Media Electronics                  | 5        | 1.38%   |
| ASUSTek Computer                     | 4        | 1.1%    |
| Generalplus Technology               | 3        | 0.83%   |
| XMOS                                 | 2        | 0.55%   |
| Texas Instruments                    | 2        | 0.55%   |
| SAVITECH                             | 2        | 0.55%   |
| Micro Star International             | 2        | 0.55%   |
| Logitech                             | 2        | 0.55%   |
| Focusrite-Novation                   | 2        | 0.55%   |
| Audio-Technica                       | 2        | 0.55%   |
| ZOOM                                 | 1        | 0.28%   |
| Yamaha                               | 1        | 0.28%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.28%   |
| Sony                                 | 1        | 0.28%   |
| Realtek Semiconductor                | 1        | 0.28%   |
| OPPO Electronics                     | 1        | 0.28%   |
| Novra/IDC/Wegener                    | 1        | 0.28%   |
| GN Netcom                            | 1        | 0.28%   |
| Elite Silicon                        | 1        | 0.28%   |
| Dell                                 | 1        | 0.28%   |
| Creative Technology                  | 1        | 0.28%   |
| Creative Labs                        | 1        | 0.28%   |
| 2.4G Composite Device                | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 6.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19       | 4.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17       | 4.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16       | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 15       | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 2.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 11       | 2.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 2.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 2.16%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.16%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 2.16%   |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 1.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7        | 1.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 1.68%   |
| Nvidia MCP61 High Definition Audio                                         | 6        | 1.44%   |
| Nvidia GF116 High Definition Audio Controller                              | 6        | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 1.44%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.2%    |
| AMD FCH Azalia Controller                                                  | 5        | 1.2%    |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.96%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4        | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.72%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 18.44%  |
| Crucial             | 26       | 18.44%  |
| Unknown             | 17       | 12.06%  |
| Transcend           | 16       | 11.35%  |
| A-DATA Technology   | 12       | 8.51%   |
| Micron Technology   | 10       | 7.09%   |
| SK hynix            | 6        | 4.26%   |
| Samsung Electronics | 6        | 4.26%   |
| Unifosa             | 3        | 2.13%   |
| Team                | 3        | 2.13%   |
| G.Skill             | 3        | 2.13%   |
| Silicon Power       | 2        | 1.42%   |
| Patriot             | 2        | 1.42%   |
| Unknown             | 2        | 1.42%   |
| V-Color             | 1        | 0.71%   |
| UMAX                | 1        | 0.71%   |
| Ramaxel Technology  | 1        | 0.71%   |
| KLEVV               | 1        | 0.71%   |
| CUSO                | 1        | 0.71%   |
| ASint Technology    | 1        | 0.71%   |
| Apacer              | 1        | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 4        | 2.67%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s         | 3        | 2%      |
| Transcend RAM Module 4GB DIMM DDR3 1600MT/s              | 3        | 2%      |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s            | 3        | 2%      |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s         | 3        | 2%      |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s        | 2        | 1.33%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s      | 2        | 1.33%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 1.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 2        | 1.33%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s   | 2        | 1.33%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s     | 2        | 1.33%   |
| Unknown                                                  | 2        | 1.33%   |
| V-Color RAM TD4G8C11-H11 4GB DIMM DDR3 1600MT/s          | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM 667MT/s                      | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 0.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.67%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                     | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 0.67%   |
| Unknown RAM Module 1GB DIMM 533MT/s                      | 1        | 0.67%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s             | 1        | 0.67%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s          | 1        | 0.67%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s            | 1        | 0.67%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.67%   |
| Unifosa RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.67%   |
| Unifosa RAM GU332G0ALEPR8H2C6F 2GB SODIMM DDR2 800MT/s   | 1        | 0.67%   |
| UMAX RAM D4-3200-16G-2048X8-L 16384MB DIMM DDR4 3200MT/s | 1        | 0.67%   |
| Transcend RAM TX2400KLN-8GK 4096MB DIMM DDR3 1600MT/s    | 1        | 0.67%   |
| Transcend RAM TX2133KLN-8GK 4096MB DIMM DDR3 2000MT/s    | 1        | 0.67%   |
| Transcend RAM TS512MLK72V6N 4GB DIMM DDR3 1600MT/s       | 1        | 0.67%   |
| Transcend RAM TS2GLH64V1B 16GB DIMM DDR4 2133MT/s        | 1        | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 67       | 53.17%  |
| DDR3    | 40       | 31.75%  |
| Unknown | 9        | 7.14%   |
| DDR5    | 4        | 3.17%   |
| DDR2    | 4        | 3.17%   |
| SDRAM   | 1        | 0.79%   |
| DDR     | 1        | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 110      | 87.3%   |
| SODIMM | 16       | 12.7%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 47       | 35.61%  |
| 16384 | 37       | 28.03%  |
| 4096  | 26       | 19.7%   |
| 2048  | 11       | 8.33%   |
| 32768 | 9        | 6.82%   |
| 1024  | 2        | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 34       | 24.46%  |
| 3200  | 20       | 14.39%  |
| 2667  | 11       | 7.91%   |
| 2400  | 11       | 7.91%   |
| 1333  | 10       | 7.19%   |
| 2133  | 9        | 6.47%   |
| 3600  | 6        | 4.32%   |
| 3000  | 5        | 3.6%    |
| 4800  | 4        | 2.88%   |
| 3733  | 4        | 2.88%   |
| 800   | 4        | 2.88%   |
| 667   | 3        | 2.16%   |
| 3466  | 2        | 1.44%   |
| 2933  | 2        | 1.44%   |
| 5200  | 1        | 0.72%   |
| 4333  | 1        | 0.72%   |
| 4000  | 1        | 0.72%   |
| 3866  | 1        | 0.72%   |
| 3800  | 1        | 0.72%   |
| 3400  | 1        | 0.72%   |
| 3334  | 1        | 0.72%   |
| 3134  | 1        | 0.72%   |
| 2866  | 1        | 0.72%   |
| 2666  | 1        | 0.72%   |
| 2000  | 1        | 0.72%   |
| 1066  | 1        | 0.72%   |
| 533   | 1        | 0.72%   |
| 400   | 1        | 0.72%   |

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


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-243 245 247 Series | 1        | 25%     |
| HP LaserJet Professional P1102w   | 1        | 25%     |
| HP LaserJet Professional P 1102w  | 1        | 25%     |
| HP LaserJet 1020                  | 1        | 25%     |

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
| Logitech                      | 12       | 60%     |
| Sunplus Innovation Technology | 2        | 10%     |
| Microdia                      | 1        | 5%      |
| KYE Systems (Mouse Systems)   | 1        | 5%      |
| Generalplus Technology        | 1        | 5%      |
| eMeet                         | 1        | 5%      |
| Apple                         | 1        | 5%      |
| A4Tech                        | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 3        | 15%     |
| Logitech Webcam C120                            | 3        | 15%     |
| Logitech Webcam C930e                           | 2        | 10%     |
| Sunplus HanChen Wise Camera                     | 1        | 5%      |
| Sunplus ezcap U3 capture-04                     | 1        | 5%      |
| Microdia USB 2.0 Camera                         | 1        | 5%      |
| Logitech Webcam C170                            | 1        | 5%      |
| Logitech QuickCam Home                          | 1        | 5%      |
| Logitech QuickCam E 3500                        | 1        | 5%      |
| Logitech HD Pro Webcam C920                     | 1        | 5%      |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 5%      |
| Generalplus GENERAL WEBCAM                      | 1        | 5%      |
| eMeet HD Webcam C960                            | 1        | 5%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                 | 1        | 5%      |
| A4Tech FHD 1080P PC Camera                      | 1        | 5%      |

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
| 0     | 191      | 80.93%  |
| 1     | 36       | 15.25%  |
| 2     | 5        | 2.12%   |
| 3     | 2        | 0.85%   |
| 5     | 1        | 0.42%   |
| 4     | 1        | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 38.46%  |
| Unassigned class         | 7        | 13.46%  |
| Net/wireless             | 7        | 13.46%  |
| Communication controller | 6        | 11.54%  |
| Card reader              | 3        | 5.77%   |
| Storage/raid             | 2        | 3.85%   |
| Sound                    | 2        | 3.85%   |
| Bluetooth                | 2        | 3.85%   |
| Network                  | 1        | 1.92%   |
| Net/ethernet             | 1        | 1.92%   |
| Camera                   | 1        | 1.92%   |

