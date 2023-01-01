Linux in Algeria - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Algeria.

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
| Toshiba       | Satellite C55-B             | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Dell          | Inspiron N7010              | [de5dc0c3ea](https://linux-hardware.org/?probe=de5dc0c3ea) | Dec 17, 2022 |
| HP            | EliteBook Revolve 810 G3    | [3b340e6b29](https://linux-hardware.org/?probe=3b340e6b29) | Dec 16, 2022 |
| Dell          | Latitude 5480               | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| HP            | EliteBook Revolve 810 G3    | [ca043cff45](https://linux-hardware.org/?probe=ca043cff45) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | EliteBook Revolve 810 G3    | [08d7f00868](https://linux-hardware.org/?probe=08d7f00868) | Nov 24, 2022 |
| HP            | EliteBook Revolve 810 G3    | [da02cb82bf](https://linux-hardware.org/?probe=da02cb82bf) | Nov 23, 2022 |
| ASUSTek       | S300CA                      | [3efc297b44](https://linux-hardware.org/?probe=3efc297b44) | Nov 23, 2022 |
| Lenovo        | G580 20150                  | [cae1dbbb12](https://linux-hardware.org/?probe=cae1dbbb12) | Nov 12, 2022 |
| Lenovo        | G580 20150                  | [64c65685da](https://linux-hardware.org/?probe=64c65685da) | Nov 03, 2022 |
| Lenovo        | V130-15IGM 81HL             | [5dbeb8f7dd](https://linux-hardware.org/?probe=5dbeb8f7dd) | Nov 03, 2022 |
| Dell          | Inspiron 3542               | [6c979bdf58](https://linux-hardware.org/?probe=6c979bdf58) | Oct 27, 2022 |
| Dell          | Inspiron 15-3567            | [4727244665](https://linux-hardware.org/?probe=4727244665) | Oct 18, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [6a0a056c36](https://linux-hardware.org/?probe=6a0a056c36) | Oct 15, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [fefb833511](https://linux-hardware.org/?probe=fefb833511) | Oct 14, 2022 |
| Dell          | Precision M4800             | [be05dcbe15](https://linux-hardware.org/?probe=be05dcbe15) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | [7d65aefb93](https://linux-hardware.org/?probe=7d65aefb93) | Oct 06, 2022 |
| Apple         | MacBookAir7,2               | [719ac47bc6](https://linux-hardware.org/?probe=719ac47bc6) | Oct 06, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| HP            | ProBook 450 G4              | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| Dell          | Latitude 7480               | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | ThinkPad X230 2325CZ1       | [b484febc13](https://linux-hardware.org/?probe=b484febc13) | Sep 17, 2022 |
| HP            | Pavilion dm3                | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Acer          | Aspire 7741                 | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | EliteBook 820 G3            | [4eadb7ee17](https://linux-hardware.org/?probe=4eadb7ee17) | Jun 19, 2022 |
| Dell          | Inspiron N7010              | [149eb0bab7](https://linux-hardware.org/?probe=149eb0bab7) | Jun 14, 2022 |
| HP            | ElitePad 1000 G2            | [9ff02a8c0c](https://linux-hardware.org/?probe=9ff02a8c0c) | Jun 12, 2022 |
| HP            | ElitePad 1000 G2            | [9273aa4844](https://linux-hardware.org/?probe=9273aa4844) | Jun 12, 2022 |
| ASUSTek       | X551CA                      | [15532b1663](https://linux-hardware.org/?probe=15532b1663) | Jun 07, 2022 |
| HP            | ProBook 4720s               | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| HP            | ProBook 4720s               | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| ASUSTek       | X205TAW                     | [57d9d59b56](https://linux-hardware.org/?probe=57d9d59b56) | May 13, 2022 |
| ASUSTek       | X205TAW                     | [577c71e530](https://linux-hardware.org/?probe=577c71e530) | May 06, 2022 |
| HP            | EliteBook 840 G3            | [95d53f5fc0](https://linux-hardware.org/?probe=95d53f5fc0) | Mar 31, 2022 |
| HP            | EliteBook 840 G3            | [698654a73f](https://linux-hardware.org/?probe=698654a73f) | Mar 26, 2022 |
| Acer          | Aspire E5-511               | [00e72ee0ce](https://linux-hardware.org/?probe=00e72ee0ce) | Mar 04, 2022 |
| Lenovo        | B50-70 20384                | [eb4abb6e15](https://linux-hardware.org/?probe=eb4abb6e15) | Mar 02, 2022 |
| Packard Be... | DOT S                       | [4110664747](https://linux-hardware.org/?probe=4110664747) | Mar 02, 2022 |
| Lenovo        | B50-70 20384                | [9d0a21adb1](https://linux-hardware.org/?probe=9d0a21adb1) | Mar 02, 2022 |
| HP            | 630                         | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3f5b85f478](https://linux-hardware.org/?probe=3f5b85f478) | Feb 07, 2022 |
| Apple         | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Dell          | Latitude E7440              | [03d4a4af15](https://linux-hardware.org/?probe=03d4a4af15) | Feb 05, 2022 |
| Apple         | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell          | Inspiron N5110              | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| HP            | ProBook 450 G3              | [0d6dacc5dc](https://linux-hardware.org/?probe=0d6dacc5dc) | Jan 20, 2022 |
| Dell          | Inspiron 5570               | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Dell          | Inspiron 3520               | [33df9edd07](https://linux-hardware.org/?probe=33df9edd07) | Dec 25, 2021 |
| LDLC          | Mercure MH                  | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Sony          | VGN-AW21M_H                 | [b4cf74ec7d](https://linux-hardware.org/?probe=b4cf74ec7d) | Dec 23, 2021 |
| ASUSTek       | X55U                        | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| ASUSTek       | X555LAB                     | [c07bccb6c7](https://linux-hardware.org/?probe=c07bccb6c7) | Dec 07, 2021 |
| Sony          | SVF1531GSFB                 | [fb251b93e9](https://linux-hardware.org/?probe=fb251b93e9) | Dec 04, 2021 |
| ASUSTek       | K50IE                       | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Dell          | Latitude E7240              | [e26d674874](https://linux-hardware.org/?probe=e26d674874) | Nov 14, 2021 |
| Dell          | Inspiron 3542               | [0862dc626b](https://linux-hardware.org/?probe=0862dc626b) | Oct 29, 2021 |
| Dell          | Inspiron 15-3567            | [a629aeaa1b](https://linux-hardware.org/?probe=a629aeaa1b) | Oct 15, 2021 |
| Lenovo        | B50-70 20384                | [8641901755](https://linux-hardware.org/?probe=8641901755) | Sep 27, 2021 |
| Lenovo        | G560 20042                  | [a31437072c](https://linux-hardware.org/?probe=a31437072c) | Sep 20, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [1c77028990](https://linux-hardware.org/?probe=1c77028990) | Sep 18, 2021 |
| Lenovo        | G500 20236                  | [b740654686](https://linux-hardware.org/?probe=b740654686) | Sep 17, 2021 |
| Sony          | SVE1713A6EW                 | [b8661880d2](https://linux-hardware.org/?probe=b8661880d2) | Sep 07, 2021 |
| HP            | 15                          | [5520042e14](https://linux-hardware.org/?probe=5520042e14) | Aug 28, 2021 |
| HP            | 15                          | [cc4e936b38](https://linux-hardware.org/?probe=cc4e936b38) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | [8a71545b54](https://linux-hardware.org/?probe=8a71545b54) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | [297e2e187c](https://linux-hardware.org/?probe=297e2e187c) | Aug 25, 2021 |
| HP            | ProBook 450 G6              | [47ed88595b](https://linux-hardware.org/?probe=47ed88595b) | Aug 20, 2021 |
| Sony          | SVE1713A6EW                 | [cf362e966f](https://linux-hardware.org/?probe=cf362e966f) | Aug 19, 2021 |
| Acer          | Aspire A515-56G             | [795edc5779](https://linux-hardware.org/?probe=795edc5779) | Aug 15, 2021 |
| Dell          | Latitude E6400              | [eb029acad6](https://linux-hardware.org/?probe=eb029acad6) | Aug 12, 2021 |
| Dell          | Latitude E5430 vPro         | [84199b59aa](https://linux-hardware.org/?probe=84199b59aa) | Aug 10, 2021 |
| Dell          | Latitude E5430 vPro         | [a4be1b3322](https://linux-hardware.org/?probe=a4be1b3322) | Aug 10, 2021 |
| MSI           | CR610M                      | [68759b0315](https://linux-hardware.org/?probe=68759b0315) | Aug 08, 2021 |
| HP            | EliteBook Folio 9470m       | [007cd499bf](https://linux-hardware.org/?probe=007cd499bf) | Aug 06, 2021 |
| Lenovo        | G560 20042                  | [405dddebf5](https://linux-hardware.org/?probe=405dddebf5) | Aug 05, 2021 |
| Dell          | Latitude 7380               | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| Acer          | Aspire A515-56G             | [185f27f184](https://linux-hardware.org/?probe=185f27f184) | Jul 22, 2021 |
| Dell          | Latitude E7440              | [d8fd7fe06d](https://linux-hardware.org/?probe=d8fd7fe06d) | Jul 20, 2021 |
| Dell          | Latitude 7480               | [28d1d17f13](https://linux-hardware.org/?probe=28d1d17f13) | Jun 22, 2021 |
| Toshiba       | Satellite C50-A539          | [c6c8ae87d9](https://linux-hardware.org/?probe=c6c8ae87d9) | May 25, 2021 |
| Toshiba       | Satellite C50-A545          | [8a9dc6ab53](https://linux-hardware.org/?probe=8a9dc6ab53) | May 24, 2021 |
| HP            | ProBook 450 G2              | [36b88b7391](https://linux-hardware.org/?probe=36b88b7391) | May 23, 2021 |
| Toshiba       | Satellite C50-A545          | [34c12e6041](https://linux-hardware.org/?probe=34c12e6041) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | [d91a5890c9](https://linux-hardware.org/?probe=d91a5890c9) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | [d12a52a705](https://linux-hardware.org/?probe=d12a52a705) | May 14, 2021 |
| Dell          | Inspiron 3576               | [be3e7aa080](https://linux-hardware.org/?probe=be3e7aa080) | May 09, 2021 |
| HP            | Laptop 15-bw0xx             | [0252beb838](https://linux-hardware.org/?probe=0252beb838) | May 04, 2021 |
| HP            | Laptop 15-bw0xx             | [bd06d6bb56](https://linux-hardware.org/?probe=bd06d6bb56) | May 04, 2021 |
| Lenovo        | G560 20042                  | [62fc21894d](https://linux-hardware.org/?probe=62fc21894d) | Apr 28, 2021 |
| Lenovo        | G560 20042                  | [7a72fc45b4](https://linux-hardware.org/?probe=7a72fc45b4) | Apr 22, 2021 |
| Apple         | MacBookPro8,2               | [b46bb85400](https://linux-hardware.org/?probe=b46bb85400) | Apr 21, 2021 |
| Dell          | Latitude E7440              | [4acb0ea358](https://linux-hardware.org/?probe=4acb0ea358) | Apr 19, 2021 |
| eMachines     | eME732                      | [a48b0c422f](https://linux-hardware.org/?probe=a48b0c422f) | Apr 19, 2021 |
| eMachines     | eME732                      | [6fd83225c1](https://linux-hardware.org/?probe=6fd83225c1) | Apr 18, 2021 |
| Dell          | XPS 13 9350                 | [2953bef8d1](https://linux-hardware.org/?probe=2953bef8d1) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | [8e5a3a6e19](https://linux-hardware.org/?probe=8e5a3a6e19) | Apr 05, 2021 |
| Fujitsu       | LIFEBOOK A532               | [843dae0f43](https://linux-hardware.org/?probe=843dae0f43) | Apr 04, 2021 |
| Toshiba       | PORTEGE R30-A               | [765ae993b9](https://linux-hardware.org/?probe=765ae993b9) | Mar 16, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | [210d440087](https://linux-hardware.org/?probe=210d440087) | Mar 13, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | [a9068d7ec4](https://linux-hardware.org/?probe=a9068d7ec4) | Mar 12, 2021 |
| Lenovo        | G580 2189                   | [387b714e2f](https://linux-hardware.org/?probe=387b714e2f) | Mar 12, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [5cf7ce91a7](https://linux-hardware.org/?probe=5cf7ce91a7) | Mar 01, 2021 |
| Acer          | Extensa 2508                | [7fb16dc91b](https://linux-hardware.org/?probe=7fb16dc91b) | Feb 28, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | [0eb94c0487](https://linux-hardware.org/?probe=0eb94c0487) | Feb 26, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | [5582abd577](https://linux-hardware.org/?probe=5582abd577) | Feb 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | [97f3e486f0](https://linux-hardware.org/?probe=97f3e486f0) | Feb 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | [d4273cb949](https://linux-hardware.org/?probe=d4273cb949) | Feb 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | [7ec7f64225](https://linux-hardware.org/?probe=7ec7f64225) | Feb 20, 2021 |
| Sony          | SVE1513K1EW                 | [35ca18e322](https://linux-hardware.org/?probe=35ca18e322) | Feb 18, 2021 |
| Sony          | SVE1513K1EW                 | [67702a7546](https://linux-hardware.org/?probe=67702a7546) | Feb 17, 2021 |
| HP            | ProBook 4540s               | [f6618c225b](https://linux-hardware.org/?probe=f6618c225b) | Feb 16, 2021 |
| Acer          | Aspire 5738                 | [c107fc9c40](https://linux-hardware.org/?probe=c107fc9c40) | Feb 15, 2021 |
| HP            | Pavilion Notebook           | [74fb8b5b1d](https://linux-hardware.org/?probe=74fb8b5b1d) | Feb 14, 2021 |
| Dell          | Precision M6600             | [3731eb952c](https://linux-hardware.org/?probe=3731eb952c) | Jan 29, 2021 |
| Acer          | Aspire V5-571               | [74f0d86e1e](https://linux-hardware.org/?probe=74f0d86e1e) | Jan 28, 2021 |
| Dell          | Precision M6600             | [105a9a66c3](https://linux-hardware.org/?probe=105a9a66c3) | Jan 23, 2021 |
| Dell          | Precision M6600             | [84d3a754fb](https://linux-hardware.org/?probe=84d3a754fb) | Jan 23, 2021 |
| Sony          | VPCEH2H1E                   | [891e9364e0](https://linux-hardware.org/?probe=891e9364e0) | Jan 14, 2021 |
| Dell          | Inspiron 3543               | [aae61a1ca3](https://linux-hardware.org/?probe=aae61a1ca3) | Dec 22, 2020 |
| Dell          | Inspiron 3543               | [ce37e65007](https://linux-hardware.org/?probe=ce37e65007) | Dec 21, 2020 |
| Lenovo        | G50-30 80G0                 | [9e347f10ee](https://linux-hardware.org/?probe=9e347f10ee) | Dec 12, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [3bab146c4c](https://linux-hardware.org/?probe=3bab146c4c) | Dec 10, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [997a066f37](https://linux-hardware.org/?probe=997a066f37) | Dec 08, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [356e5f32f8](https://linux-hardware.org/?probe=356e5f32f8) | Dec 08, 2020 |
| Dell          | Vostro 3500                 | [a76707659b](https://linux-hardware.org/?probe=a76707659b) | Nov 29, 2020 |
| Dell          | Inspiron 3543               | [cfbfec849d](https://linux-hardware.org/?probe=cfbfec849d) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | [97d5763d6b](https://linux-hardware.org/?probe=97d5763d6b) | Nov 21, 2020 |
| Acer          | Aspire 5738                 | [4ead657ec9](https://linux-hardware.org/?probe=4ead657ec9) | Nov 21, 2020 |
| Acer          | Aspire F5-572               | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| HP            | EliteBook Folio 9470m       | [39251e283c](https://linux-hardware.org/?probe=39251e283c) | Oct 29, 2020 |
| HP            | ProBook 450 G0              | [85e77f85c7](https://linux-hardware.org/?probe=85e77f85c7) | Oct 26, 2020 |
| Dell          | Latitude E5430 non-vPro     | [230a4dff71](https://linux-hardware.org/?probe=230a4dff71) | Oct 26, 2020 |
| HP            | ProBook 4540s               | [e2bb03b7da](https://linux-hardware.org/?probe=e2bb03b7da) | Oct 23, 2020 |
| HP            | ProBook 4540s               | [b369817417](https://linux-hardware.org/?probe=b369817417) | Oct 15, 2020 |
| Lenovo        | G50-30 80G0                 | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| Sony          | VPCEH2H1E                   | [07077a7194](https://linux-hardware.org/?probe=07077a7194) | Oct 02, 2020 |
| Sony          | VPCEH2H1E                   | [c35dfa149d](https://linux-hardware.org/?probe=c35dfa149d) | Sep 24, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [1efd90cecb](https://linux-hardware.org/?probe=1efd90cecb) | Sep 20, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ebaa6b30e4](https://linux-hardware.org/?probe=ebaa6b30e4) | Sep 20, 2020 |
| Acer          | Aspire F5-572               | [9ab161c8d7](https://linux-hardware.org/?probe=9ab161c8d7) | Sep 03, 2020 |
| HP            | ZBook 15 G4                 | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Packard Be... | EasyNote LJ71               | [8848f3250d](https://linux-hardware.org/?probe=8848f3250d) | Aug 26, 2020 |
| HP            | 250 G4                      | [84bd70a658](https://linux-hardware.org/?probe=84bd70a658) | Jul 24, 2020 |
| HP            | 250 G4                      | [bb773c0ade](https://linux-hardware.org/?probe=bb773c0ade) | Jul 24, 2020 |
| HP            | ProBook 650 G1              | [33e5e60503](https://linux-hardware.org/?probe=33e5e60503) | Jul 05, 2020 |
| HP            | EliteBook Folio 9470m       | [2273ab39c8](https://linux-hardware.org/?probe=2273ab39c8) | Jun 27, 2020 |
| HP            | Pavilion Notebook           | [734c3a7d86](https://linux-hardware.org/?probe=734c3a7d86) | Jun 22, 2020 |
| HP            | Pavilion Notebook           | [9451ca4468](https://linux-hardware.org/?probe=9451ca4468) | Jun 22, 2020 |
| Toshiba       | Satellite C50-A560          | [cb406c43ec](https://linux-hardware.org/?probe=cb406c43ec) | Jun 21, 2020 |
| Toshiba       | Satellite C50-A560          | [46894e19cd](https://linux-hardware.org/?probe=46894e19cd) | Jun 21, 2020 |
| HP            | ProBook 450 G2              | [81cf9fa7cf](https://linux-hardware.org/?probe=81cf9fa7cf) | Jun 11, 2020 |
| Dell          | Inspiron N5110              | [c349a84934](https://linux-hardware.org/?probe=c349a84934) | Jun 02, 2020 |
| Toshiba       | Satellite C55-B             | [0bc2465c23](https://linux-hardware.org/?probe=0bc2465c23) | May 25, 2020 |
| ASUSTek       | X541UV                      | [25108243d2](https://linux-hardware.org/?probe=25108243d2) | May 23, 2020 |
| HP            | ProBook 450 G2              | [148b457da1](https://linux-hardware.org/?probe=148b457da1) | May 21, 2020 |
| Acer          | Extensa 2510                | [3c56d54986](https://linux-hardware.org/?probe=3c56d54986) | May 16, 2020 |
| Toshiba       | Satellite C55-B             | [800fe450a7](https://linux-hardware.org/?probe=800fe450a7) | May 16, 2020 |
| Dell          | Inspiron 3558               | [e1f352ee7e](https://linux-hardware.org/?probe=e1f352ee7e) | May 15, 2020 |
| Acer          | Aspire 5733                 | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| HP            | ProBook 450 G2              | [165c5e3446](https://linux-hardware.org/?probe=165c5e3446) | May 11, 2020 |
| HP            | 15                          | [bc0640c653](https://linux-hardware.org/?probe=bc0640c653) | May 01, 2020 |
| Dell          | Inspiron 3558               | [bc3989f5fd](https://linux-hardware.org/?probe=bc3989f5fd) | Apr 30, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | [eb26a0a6dd](https://linux-hardware.org/?probe=eb26a0a6dd) | Apr 26, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | [27139478ff](https://linux-hardware.org/?probe=27139478ff) | Apr 24, 2020 |
| Sony          | SVE1713A6EW                 | [998290195d](https://linux-hardware.org/?probe=998290195d) | Mar 26, 2020 |
| Dell          | Precision M4600             | [995809b82f](https://linux-hardware.org/?probe=995809b82f) | Mar 12, 2020 |
| Dell          | Latitude 7490               | [394723d5ec](https://linux-hardware.org/?probe=394723d5ec) | Mar 12, 2020 |
| Dell          | Latitude 7490               | [9a4b04d5c6](https://linux-hardware.org/?probe=9a4b04d5c6) | Mar 10, 2020 |
| Dell          | Latitude 7490               | [3b7100f499](https://linux-hardware.org/?probe=3b7100f499) | Mar 10, 2020 |
| HP            | Pavilion Notebook           | [b0b0e640c9](https://linux-hardware.org/?probe=b0b0e640c9) | Mar 01, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [46a39dcec8](https://linux-hardware.org/?probe=46a39dcec8) | Feb 10, 2020 |
| Dell          | Inspiron 15-3567            | [52020faf85](https://linux-hardware.org/?probe=52020faf85) | Feb 05, 2020 |
| Toshiba       | PORTEGE M780                | [ed6be60ed5](https://linux-hardware.org/?probe=ed6be60ed5) | Jan 07, 2020 |
| Toshiba       | PORTEGE M780                | [b8f52696c7](https://linux-hardware.org/?probe=b8f52696c7) | Jan 07, 2020 |
| Dell          | Inspiron 3542               | [170967f63e](https://linux-hardware.org/?probe=170967f63e) | Dec 31, 2019 |
| HP            | Pavilion 15                 | [e190391a64](https://linux-hardware.org/?probe=e190391a64) | Dec 10, 2019 |
| Lenovo        | ThinkPad T440 20B6S00200    | [8491772fe8](https://linux-hardware.org/?probe=8491772fe8) | Nov 19, 2019 |
| ASUSTek       | GL753VD                     | [3aed06c634](https://linux-hardware.org/?probe=3aed06c634) | Nov 05, 2019 |
| ASUSTek       | GL753VD                     | [80803b7502](https://linux-hardware.org/?probe=80803b7502) | Nov 05, 2019 |
| Sony          | VPCEJ2S1E                   | [909ce7c754](https://linux-hardware.org/?probe=909ce7c754) | Oct 25, 2019 |
| Toshiba       | Satellite C850-A979         | [742402d677](https://linux-hardware.org/?probe=742402d677) | Oct 01, 2019 |
| Toshiba       | Satellite C850-A979         | [bf938959f0](https://linux-hardware.org/?probe=bf938959f0) | Sep 30, 2019 |
| HP            | Pavilion 15                 | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Fujitsu       | LIFEBOOK AH532/G21          | [a9f20406b7](https://linux-hardware.org/?probe=a9f20406b7) | Jul 17, 2019 |
| Packard Be... | EasyNote TJ75               | [84742985cb](https://linux-hardware.org/?probe=84742985cb) | Apr 30, 2019 |
| Dell          | Latitude E5430 vPro         | [d88e664ef7](https://linux-hardware.org/?probe=d88e664ef7) | Apr 29, 2019 |
| Lenovo        | G50-30 80G0                 | [5aeb26c21c](https://linux-hardware.org/?probe=5aeb26c21c) | Apr 10, 2019 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [92ce529502](https://linux-hardware.org/?probe=92ce529502) | Apr 10, 2019 |
| HP            | Notebook                    | [a94921a2ad](https://linux-hardware.org/?probe=a94921a2ad) | Dec 29, 2018 |
| HP            | Pavilion Notebook           | [283bc29327](https://linux-hardware.org/?probe=283bc29327) | Dec 24, 2017 |
| HP            | Pavilion Notebook           | [af28f98e0a](https://linux-hardware.org/?probe=af28f98e0a) | Dec 07, 2017 |
| ASUSTek       | X540SA                      | [f76ee802c9](https://linux-hardware.org/?probe=f76ee802c9) | Mar 09, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 32        | 22.86%  |
| Ubuntu 18.04        | 13        | 9.29%   |
| OpenMandriva 4.2    | 9         | 6.43%   |
| Linux Mint 20.1     | 6         | 4.29%   |
| OpenMandriva 4.3    | 5         | 3.57%   |
| KDE neon 20.04      | 5         | 3.57%   |
| Ubuntu 22.04        | 4         | 2.86%   |
| Pop!_OS 20.04       | 4         | 2.86%   |
| Xubuntu 20.04       | 3         | 2.14%   |
| Fedora 35           | 3         | 2.14%   |
| ArcoLinux Rolling   | 3         | 2.14%   |
| Arch                | 3         | 2.14%   |
| Ubuntu 21.10        | 2         | 1.43%   |
| Ubuntu 20.10        | 2         | 1.43%   |
| Ubuntu 19.10        | 2         | 1.43%   |
| ROSA R11            | 2         | 1.43%   |
| Manjaro             | 2         | 1.43%   |
| Kubuntu 20.04       | 2         | 1.43%   |
| Kali 2021.1         | 2         | 1.43%   |
| Debian 11           | 2         | 1.43%   |
| BlackPanther 18.1   | 2         | 1.43%   |
| Zorin 16            | 1         | 0.71%   |
| UbuntuDDE 20.04     | 1         | 0.71%   |
| Ubuntu Unity 16.04  | 1         | 0.71%   |
| Ubuntu Budgie 22.04 | 1         | 0.71%   |
| Ubuntu 22.10        | 1         | 0.71%   |
| Ubuntu 21.04        | 1         | 0.71%   |
| Ubuntu 16.04        | 1         | 0.71%   |
| ROSA R8.1           | 1         | 0.71%   |
| ROSA R10            | 1         | 0.71%   |
| ROSA 12.2           | 1         | 0.71%   |
| Pop!_OS 21.04       | 1         | 0.71%   |
| Pear OS 20.04       | 1         | 0.71%   |
| Parrot 5.0          | 1         | 0.71%   |
| OpenMandriva 4.50   | 1         | 0.71%   |
| MX 19               | 1         | 0.71%   |
| Manjaro 20.1        | 1         | 0.71%   |
| Linux Mint 21       | 1         | 0.71%   |
| Linux Mint 20.3     | 1         | 0.71%   |
| Linux Mint 20.2     | 1         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 57        | 41.3%   |
| OpenMandriva  | 15        | 10.87%  |
| Linux Mint    | 11        | 7.97%   |
| KDE neon      | 6         | 4.35%   |
| Fedora        | 6         | 4.35%   |
| Pop!_OS       | 5         | 3.62%   |
| ROSA          | 4         | 2.9%    |
| Xubuntu       | 3         | 2.17%   |
| Manjaro       | 3         | 2.17%   |
| Kali          | 3         | 2.17%   |
| Debian        | 3         | 2.17%   |
| ArcoLinux     | 3         | 2.17%   |
| Arch          | 3         | 2.17%   |
| Kubuntu       | 2         | 1.45%   |
| BlackPanther  | 2         | 1.45%   |
| Zorin         | 1         | 0.72%   |
| UbuntuDDE     | 1         | 0.72%   |
| Ubuntu Unity  | 1         | 0.72%   |
| Ubuntu Budgie | 1         | 0.72%   |
| Pear OS       | 1         | 0.72%   |
| Parrot        | 1         | 0.72%   |
| MX            | 1         | 0.72%   |
| EndeavourOS   | 1         | 0.72%   |
| Clear Linux   | 1         | 0.72%   |
| CentOS        | 1         | 0.72%   |
| Artix         | 1         | 0.72%   |
| ArchLabs      | 1         | 0.72%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 9         | 6.12%   |
| 5.16.7-desktop-1omv4003  | 5         | 3.4%    |
| 5.4.0-72-generic         | 4         | 2.72%   |
| 5.4.0-42-generic         | 4         | 2.72%   |
| 5.4.0-29-generic         | 4         | 2.72%   |
| 5.4.0-54-generic         | 3         | 2.04%   |
| 5.13.0-30-generic        | 3         | 2.04%   |
| 5.8.0-50-generic         | 2         | 1.36%   |
| 5.8.0-44-generic         | 2         | 1.36%   |
| 5.4.0-80-generic         | 2         | 1.36%   |
| 5.4.0-7625-generic       | 2         | 1.36%   |
| 5.4.0-65-generic         | 2         | 1.36%   |
| 5.4.0-56-generic         | 2         | 1.36%   |
| 5.4.0-52-generic         | 2         | 1.36%   |
| 5.4.0-48-generic         | 2         | 1.36%   |
| 5.4.0-33-generic         | 2         | 1.36%   |
| 5.3.0-40-generic         | 2         | 1.36%   |
| 5.15.0-47-generic        | 2         | 1.36%   |
| 5.11.0-27-generic        | 2         | 1.36%   |
| 5.11.0-25-generic        | 2         | 1.36%   |
| 4.18.16-desktop-1bP      | 2         | 1.36%   |
| 5.9.11-3-MANJARO         | 1         | 0.68%   |
| 5.8.0-63-generic         | 1         | 0.68%   |
| 5.8.0-48-generic         | 1         | 0.68%   |
| 5.8.0-45-generic         | 1         | 0.68%   |
| 5.8.0-43-generic         | 1         | 0.68%   |
| 5.8.0-36-generic         | 1         | 0.68%   |
| 5.7.17-2-MANJARO         | 1         | 0.68%   |
| 5.7.0-kali1-amd64        | 1         | 0.68%   |
| 5.6.0-2-amd64            | 1         | 0.68%   |
| 5.4.72-1-lts             | 1         | 0.68%   |
| 5.4.15-200.fc31.x86_64   | 1         | 0.68%   |
| 5.4.0-81-generic         | 1         | 0.68%   |
| 5.4.0-7626-generic       | 1         | 0.68%   |
| 5.4.0-74-generic         | 1         | 0.68%   |
| 5.4.0-70-generic         | 1         | 0.68%   |
| 5.4.0-58-generic         | 1         | 0.68%   |
| 5.4.0-51-generic         | 1         | 0.68%   |
| 5.4.0-47-generic         | 1         | 0.68%   |
| 5.4.0-40-generic         | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 26.09%  |
| 5.8.0   | 9         | 6.52%   |
| 5.10.14 | 9         | 6.52%   |
| 5.15.0  | 8         | 5.8%    |
| 5.3.0   | 7         | 5.07%   |
| 5.13.0  | 7         | 5.07%   |
| 5.11.0  | 7         | 5.07%   |
| 5.16.7  | 5         | 3.62%   |
| 4.15.0  | 5         | 3.62%   |
| 5.10.0  | 4         | 2.9%    |
| 5.0.0   | 4         | 2.9%    |
| 4.18.16 | 3         | 2.17%   |
| 5.15.7  | 2         | 1.45%   |
| 4.4.0   | 2         | 1.45%   |
| 5.9.11  | 1         | 0.72%   |
| 5.7.17  | 1         | 0.72%   |
| 5.7.0   | 1         | 0.72%   |
| 5.6.0   | 1         | 0.72%   |
| 5.4.72  | 1         | 0.72%   |
| 5.4.15  | 1         | 0.72%   |
| 5.19.12 | 1         | 0.72%   |
| 5.19.11 | 1         | 0.72%   |
| 5.19.0  | 1         | 0.72%   |
| 5.17.4  | 1         | 0.72%   |
| 5.16.11 | 1         | 0.72%   |
| 5.15.8  | 1         | 0.72%   |
| 5.15.5  | 1         | 0.72%   |
| 5.15.15 | 1         | 0.72%   |
| 5.15.10 | 1         | 0.72%   |
| 5.14.0  | 1         | 0.72%   |
| 5.13.2  | 1         | 0.72%   |
| 5.12.5  | 1         | 0.72%   |
| 5.12.4  | 1         | 0.72%   |
| 5.12.15 | 1         | 0.72%   |
| 5.11.15 | 1         | 0.72%   |
| 5.10.82 | 1         | 0.72%   |
| 5.10.74 | 1         | 0.72%   |
| 5.10.3  | 1         | 0.72%   |
| 4.9.9   | 1         | 0.72%   |
| 4.9.60  | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 38        | 27.54%  |
| 5.10    | 16        | 11.59%  |
| 5.15    | 14        | 10.14%  |
| 5.8     | 9         | 6.52%   |
| 5.13    | 8         | 5.8%    |
| 5.11    | 8         | 5.8%    |
| 5.3     | 7         | 5.07%   |
| 5.16    | 6         | 4.35%   |
| 4.15    | 5         | 3.62%   |
| 5.0     | 4         | 2.9%    |
| 4.18    | 4         | 2.9%    |
| 5.19    | 3         | 2.17%   |
| 5.12    | 3         | 2.17%   |
| 5.7     | 2         | 1.45%   |
| 4.9     | 2         | 1.45%   |
| 4.4     | 2         | 1.45%   |
| 4.19    | 2         | 1.45%   |
| 5.9     | 1         | 0.72%   |
| 5.6     | 1         | 0.72%   |
| 5.17    | 1         | 0.72%   |
| 5.14    | 1         | 0.72%   |
| 3.10    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 121       | 97.58%  |
| i686   | 3         | 2.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 63        | 47.73%  |
| KDE5       | 24        | 18.18%  |
| Unknown    | 13        | 9.85%   |
| XFCE       | 10        | 7.58%   |
| X-Cinnamon | 6         | 4.55%   |
| MATE       | 4         | 3.03%   |
| KDE        | 4         | 3.03%   |
| KDE4       | 2         | 1.52%   |
| Unity      | 1         | 0.76%   |
| LXQt       | 1         | 0.76%   |
| i3         | 1         | 0.76%   |
| Deepin     | 1         | 0.76%   |
| Cinnamon   | 1         | 0.76%   |
| Budgie     | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 106       | 83.46%  |
| Wayland | 14        | 11.02%  |
| Unknown | 6         | 4.72%   |
| Tty     | 1         | 0.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 54.2%   |
| SDDM    | 20        | 15.27%  |
| GDM     | 15        | 11.45%  |
| LightDM | 13        | 9.92%   |
| GDM3    | 5         | 3.82%   |
| TDM     | 4         | 3.05%   |
| KDM     | 2         | 1.53%   |
| SLiM    | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 62        | 49.21%  |
| fr_FR   | 37        | 29.37%  |
| Unknown | 13        | 10.32%  |
| en_GB   | 4         | 3.17%   |
| C       | 4         | 3.17%   |
| fr_BE   | 2         | 1.59%   |
| ar_DZ   | 2         | 1.59%   |
| fr_DZ   | 1         | 0.79%   |
| ar_EG   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 86        | 67.19%  |
| EFI  | 42        | 32.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 98        | 75.38%  |
| Overlay | 17        | 13.08%  |
| Btrfs   | 6         | 4.62%   |
| Unknown | 4         | 3.08%   |
| Ext2    | 3         | 2.31%   |
| Xfs     | 1         | 0.77%   |
| Ext3    | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 62.99%  |
| GPT     | 27        | 21.26%  |
| MBR     | 20        | 15.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 83.59%  |
| Yes       | 21        | 16.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 50.79%  |
| Yes       | 62        | 49.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 30        | 24.19%  |
| Hewlett-Packard     | 25        | 20.16%  |
| Lenovo              | 20        | 16.13%  |
| Acer                | 11        | 8.87%   |
| Toshiba             | 9         | 7.26%   |
| ASUSTek Computer    | 9         | 7.26%   |
| Sony                | 6         | 4.84%   |
| Samsung Electronics | 3         | 2.42%   |
| Packard Bell        | 3         | 2.42%   |
| Apple               | 3         | 2.42%   |
| Fujitsu             | 2         | 1.61%   |
| MSI                 | 1         | 0.81%   |
| LDLC                | 1         | 0.81%   |
| eMachines           | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Toshiba Satellite C55-B                               | 3         | 2.42%   |
| Dell Inspiron 3542                                    | 3         | 2.42%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 1.61%   |
| Lenovo G560 20042                                     | 2         | 1.61%   |
| Lenovo G50-30 80G0                                    | 2         | 1.61%   |
| Lenovo B50-70 20384                                   | 2         | 1.61%   |
| HP ProBook 4540s                                      | 2         | 1.61%   |
| HP Pavilion 15                                        | 2         | 1.61%   |
| HP 15                                                 | 2         | 1.61%   |
| Dell Latitude E7440                                   | 2         | 1.61%   |
| Dell Latitude E5430 vPro                              | 2         | 1.61%   |
| Dell Latitude 7480                                    | 2         | 1.61%   |
| Dell Inspiron N5110                                   | 2         | 1.61%   |
| Dell Inspiron 15-3567                                 | 2         | 1.61%   |
| Acer Aspire 5738                                      | 2         | 1.61%   |
| Toshiba Satellite C850-A979                           | 1         | 0.81%   |
| Toshiba Satellite C50-A560                            | 1         | 0.81%   |
| Toshiba Satellite C50-A545                            | 1         | 0.81%   |
| Toshiba Satellite C50-A539                            | 1         | 0.81%   |
| Toshiba PORTEGE R30-A                                 | 1         | 0.81%   |
| Toshiba PORTEGE M780                                  | 1         | 0.81%   |
| Sony VPCEJ2S1E                                        | 1         | 0.81%   |
| Sony VPCEH2H1E                                        | 1         | 0.81%   |
| Sony VGN-AW21M_H                                      | 1         | 0.81%   |
| Sony SVF1531GSFB                                      | 1         | 0.81%   |
| Sony SVE1713A6EW                                      | 1         | 0.81%   |
| Sony SVE1513K1EW                                      | 1         | 0.81%   |
| Samsung N102SP/N100SP/N101SP                          | 1         | 0.81%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B                   | 1         | 0.81%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.81%   |
| Packard Bell EasyNote TJ75                            | 1         | 0.81%   |
| Packard Bell EasyNote LJ71                            | 1         | 0.81%   |
| Packard Bell DOT S                                    | 1         | 0.81%   |
| MSI CR610M                                            | 1         | 0.81%   |
| Lenovo V130-15IGM 81HL                                | 1         | 0.81%   |
| Lenovo ThinkPad X260 20F5S1G104                       | 1         | 0.81%   |
| Lenovo ThinkPad X230 2325CZ1                          | 1         | 0.81%   |
| Lenovo ThinkPad X201 3680AQ1                          | 1         | 0.81%   |
| Lenovo ThinkPad T450 20BUS2RN1H                       | 1         | 0.81%   |
| Lenovo ThinkPad T440 20B6S00200                       | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 13        | 10.48%  |
| Dell Latitude         | 12        | 9.68%   |
| HP ProBook            | 9         | 7.26%   |
| Acer Aspire           | 9         | 7.26%   |
| Toshiba Satellite     | 7         | 5.65%   |
| Lenovo ThinkPad       | 5         | 4.03%   |
| Lenovo IdeaPad        | 5         | 4.03%   |
| HP Pavilion           | 4         | 3.23%   |
| HP EliteBook          | 4         | 3.23%   |
| Dell Precision        | 3         | 2.42%   |
| Toshiba PORTEGE       | 2         | 1.61%   |
| Packard Bell EasyNote | 2         | 1.61%   |
| Lenovo G580           | 2         | 1.61%   |
| Lenovo G560           | 2         | 1.61%   |
| Lenovo G50-30         | 2         | 1.61%   |
| Lenovo B50-70         | 2         | 1.61%   |
| HP 15                 | 2         | 1.61%   |
| Fujitsu LIFEBOOK      | 2         | 1.61%   |
| Acer Extensa          | 2         | 1.61%   |
| Sony VPCEJ2S1E        | 1         | 0.81%   |
| Sony VPCEH2H1E        | 1         | 0.81%   |
| Sony VGN-AW21M        | 1         | 0.81%   |
| Sony SVF1531GSFB      | 1         | 0.81%   |
| Sony SVE1713A6EW      | 1         | 0.81%   |
| Sony SVE1513K1EW      | 1         | 0.81%   |
| Samsung N102SP        | 1         | 0.81%   |
| Samsung 700Z3A        | 1         | 0.81%   |
| Samsung 300E5EV       | 1         | 0.81%   |
| Packard Bell DOT      | 1         | 0.81%   |
| MSI CR610M            | 1         | 0.81%   |
| Lenovo V130-15IGM     | 1         | 0.81%   |
| Lenovo G500           | 1         | 0.81%   |
| LDLC Mercure          | 1         | 0.81%   |
| HP ZBook              | 1         | 0.81%   |
| HP Notebook           | 1         | 0.81%   |
| HP Laptop             | 1         | 0.81%   |
| HP ElitePad           | 1         | 0.81%   |
| HP 630                | 1         | 0.81%   |
| HP 250                | 1         | 0.81%   |
| eMachines eME732      | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 22        | 17.74%  |
| 2014 | 20        | 16.13%  |
| 2013 | 17        | 13.71%  |
| 2015 | 13        | 10.48%  |
| 2017 | 11        | 8.87%   |
| 2016 | 9         | 7.26%   |
| 2010 | 9         | 7.26%   |
| 2009 | 8         | 6.45%   |
| 2011 | 7         | 5.65%   |
| 2018 | 6         | 4.84%   |
| 2021 | 1         | 0.81%   |
| 2008 | 1         | 0.81%   |

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
| Disabled | 123       | 99.19%  |
| Enabled  | 1         | 0.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 54        | 43.2%   |
| 4.01-8.0   | 35        | 28%     |
| 8.01-16.0  | 21        | 16.8%   |
| 1.01-2.0   | 6         | 4.8%    |
| 16.01-24.0 | 5         | 4%      |
| 32.01-64.0 | 2         | 1.6%    |
| 2.01-3.0   | 2         | 1.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 71        | 50.71%  |
| 2.01-3.0  | 40        | 28.57%  |
| 3.01-4.0  | 16        | 11.43%  |
| 0.51-1.0  | 7         | 5%      |
| 4.01-8.0  | 4         | 2.86%   |
| 8.01-16.0 | 2         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 75.2%   |
| 2      | 28        | 22.4%   |
| 4      | 1         | 0.8%    |
| 3      | 1         | 0.8%    |
| 0      | 1         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 66.13%  |
| No        | 42        | 33.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 93.55%  |
| No        | 8         | 6.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 98.4%   |
| No        | 2         | 1.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 69.84%  |
| No        | 38        | 30.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Algeria | 124       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Algiers         | 21        | 14.69%  |
| Tlemcen         | 7         | 4.9%    |
| Oran            | 7         | 4.9%    |
| Belcourt        | 7         | 4.9%    |
| Tipasa          | 4         | 2.8%    |
| Skikda          | 4         | 2.8%    |
| Relizane        | 4         | 2.8%    |
| Cheraga         | 4         | 2.8%    |
| Birkhadem       | 4         | 2.8%    |
| Tizi Ouzou      | 3         | 2.1%    |
| Sétif          | 3         | 2.1%    |
| Laghouat        | 3         | 2.1%    |
| Constantine     | 3         | 2.1%    |
| Blida           | 3         | 2.1%    |
| Béjaïa        | 3         | 2.1%    |
| ash-Shalif      | 3         | 2.1%    |
| Annaba          | 3         | 2.1%    |
| Saoula          | 2         | 1.4%    |
| Saida           | 2         | 1.4%    |
| Kouba           | 2         | 1.4%    |
| Djelfa          | 2         | 1.4%    |
| Biskra          | 2         | 1.4%    |
| Bir el Djir     | 2         | 1.4%    |
| Ben ’Aknoûn  | 2         | 1.4%    |
| Bab Ezzouar     | 2         | 1.4%    |
| Ain Fakroun     | 2         | 1.4%    |
| Tolga           | 1         | 0.7%    |
| Tichi           | 1         | 0.7%    |
| Tazoult-Lambese | 1         | 0.7%    |
| Souma           | 1         | 0.7%    |
| Souk Ahras      | 1         | 0.7%    |
| Sidi Kada       | 1         | 0.7%    |
| Sidi Bel Abbes  | 1         | 0.7%    |
| Sidi Akkacha    | 1         | 0.7%    |
| Reguiba         | 1         | 0.7%    |
| Ouenza          | 1         | 0.7%    |
| Naama           | 1         | 0.7%    |
| Mostaganem      | 1         | 0.7%    |
| Mila            | 1         | 0.7%    |
| M'Sila          | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 27        | 35     | 18.37%  |
| WDC                   | 22        | 26     | 14.97%  |
| Toshiba               | 22        | 23     | 14.97%  |
| Hitachi               | 14        | 16     | 9.52%   |
| HGST                  | 13        | 17     | 8.84%   |
| Samsung Electronics   | 7         | 7      | 4.76%   |
| A-DATA Technology     | 6         | 7      | 4.08%   |
| Unknown               | 4         | 5      | 2.72%   |
| SK hynix              | 4         | 5      | 2.72%   |
| SanDisk               | 4         | 4      | 2.72%   |
| Lexar                 | 4         | 6      | 2.72%   |
| LITEON                | 3         | 6      | 2.04%   |
| Team                  | 2         | 3      | 1.36%   |
| Intel                 | 2         | 2      | 1.36%   |
| XPG                   | 1         | 1      | 0.68%   |
| Realtek Semiconductor | 1         | 1      | 0.68%   |
| PNY                   | 1         | 1      | 0.68%   |
| Micron Technology     | 1         | 2      | 0.68%   |
| Londisk               | 1         | 1      | 0.68%   |
| Kingston              | 1         | 1      | 0.68%   |
| KingSpec              | 1         | 1      | 0.68%   |
| KESU                  | 1         | 1      | 0.68%   |
| HUAWEI                | 1         | 1      | 0.68%   |
| HS-SSD-C100           | 1         | 1      | 0.68%   |
| Fujitsu               | 1         | 2      | 0.68%   |
| China                 | 1         | 1      | 0.68%   |
| Apple                 | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB           | 9         | 6%      |
| Seagate ST500LT012-1DG142 500GB    | 4         | 2.67%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 3         | 2%      |
| Toshiba MQ01ABD100 1TB             | 3         | 2%      |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 2%      |
| Seagate Expansion 4TB              | 3         | 2%      |
| HGST HTS545050A7E680 500GB         | 3         | 2%      |
| HGST HTS545050A7E380 500GB         | 3         | 2%      |
| Unknown MMC Card  64GB             | 2         | 1.33%   |
| Seagate ST9500325AS 500GB          | 2         | 1.33%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 1.33%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 1.33%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 1.33%   |
| Lexar 512GB SSD                    | 2         | 1.33%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 1.33%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 1.33%   |
| HGST HTS725050A7E630 500GB         | 2         | 1.33%   |
| HGST HTS541010A9E680 1TB           | 2         | 1.33%   |
| XPG SX950U 240GB                   | 1         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.67%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.67%   |
| WDC WDS100T2B0B-00YS70 1TB SSD     | 1         | 0.67%   |
| WDC WD7500BPKX-75HPJT0 752GB       | 1         | 0.67%   |
| WDC WD5000LUCT-62RC2Y0 500GB       | 1         | 0.67%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.67%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.67%   |
| WDC WD5000LPVT-16G33T0 500GB       | 1         | 0.67%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.67%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.67%   |
| WDC WD5000LPCX-21VHAT0 500GB       | 1         | 0.67%   |
| WDC WD5000BPVT-75HXZT3 500GB       | 1         | 0.67%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 0.67%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 0.67%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.67%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 0.67%   |
| WDC WD3200BEKT-75KA9T0 320GB       | 1         | 0.67%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 0.67%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 0.67%   |
| WDC WD10JPVX-08JC3T5 1TB           | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 35     | 27.55%  |
| Toshiba             | 22        | 23     | 22.45%  |
| WDC                 | 20        | 23     | 20.41%  |
| Hitachi             | 14        | 16     | 14.29%  |
| HGST                | 13        | 17     | 13.27%  |
| Samsung Electronics | 1         | 1      | 1.02%   |
| Fujitsu             | 1         | 2      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 6         | 7      | 17.14%  |
| SanDisk             | 4         | 4      | 11.43%  |
| WDC                 | 3         | 3      | 8.57%   |
| SK hynix            | 3         | 4      | 8.57%   |
| LITEON              | 3         | 6      | 8.57%   |
| Lexar               | 3         | 5      | 8.57%   |
| Samsung Electronics | 2         | 2      | 5.71%   |
| Intel               | 2         | 2      | 5.71%   |
| XPG                 | 1         | 1      | 2.86%   |
| Team                | 1         | 2      | 2.86%   |
| PNY                 | 1         | 1      | 2.86%   |
| Londisk             | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |
| KingSpec            | 1         | 1      | 2.86%   |
| HS-SSD-C100         | 1         | 1      | 2.86%   |
| China               | 1         | 1      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 94        | 117    | 68.12%  |
| SSD     | 31        | 43     | 22.46%  |
| NVMe    | 7         | 9      | 5.07%   |
| MMC     | 4         | 6      | 2.9%    |
| Unknown | 2         | 2      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 155    | 86.36%  |
| SAS  | 7         | 7      | 5.3%    |
| NVMe | 7         | 9      | 5.3%    |
| MMC  | 4         | 6      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 125    | 74.6%   |
| 0.51-1.0   | 28        | 31     | 22.22%  |
| 3.01-4.0   | 3         | 3      | 2.38%   |
| 1.01-2.0   | 1         | 1      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 37        | 28.03%  |
| 51-100     | 25        | 18.94%  |
| 101-250    | 23        | 17.42%  |
| 501-1000   | 16        | 12.12%  |
| 1-20       | 13        | 9.85%   |
| 21-50      | 11        | 8.33%   |
| 1001-2000  | 5         | 3.79%   |
| Unknown    | 2         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 68        | 48.92%  |
| 21-50    | 23        | 16.55%  |
| 101-250  | 22        | 15.83%  |
| 51-100   | 13        | 9.35%   |
| 251-500  | 7         | 5.04%   |
| 501-1000 | 4         | 2.88%   |
| Unknown  | 2         | 1.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 1      | 6.25%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 6.25%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 6.25%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 6.25%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 6.25%   |
| Samsung Electronics HM320HJ 320GB | 1         | 1      | 6.25%   |
| Hitachi HTS723225L9A360 250GB     | 1         | 1      | 6.25%   |
| Hitachi HTS547564A9E384 640GB     | 1         | 1      | 6.25%   |
| Hitachi HTS542516K9SA00 160GB     | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB        | 1         | 3      | 6.25%   |
| HGST HTS545050A7E680 500GB        | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| HGST                | 2         | 4      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| HGST                | 2         | 4      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 18     | 100%    |

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
| Detected | 82        | 117    | 63.08%  |
| Works    | 32        | 42     | 24.62%  |
| Malfunc  | 16        | 18     | 12.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 112       | 86.82%  |
| AMD                         | 6         | 4.65%   |
| Samsung Electronics         | 5         | 3.88%   |
| Nvidia                      | 2         | 1.55%   |
| Silicon Motion              | 1         | 0.78%   |
| Realtek Semiconductor       | 1         | 0.78%   |
| Micron Technology           | 1         | 0.78%   |
| MAXIO Technology (Hangzhou) | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 25        | 18.94%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 13.64%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 8.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 7.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 5.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 4.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 3.03%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.52%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                            | 2         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.76%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.76%   |
| Samsung Electronics SATA controller                                              | 1         | 0.76%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.76%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.76%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 1         | 0.76%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.76%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.76%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 105       | 80.77%  |
| RAID | 13        | 10%     |
| NVMe | 7         | 5.38%   |
| IDE  | 5         | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 118       | 95.16%  |
| AMD    | 6         | 4.84%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-3217U CPU @ 1.80GHz           | 6         | 4.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 3.23%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 3.23%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 4         | 3.23%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 2.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 2.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 2.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 2.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 2.42%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 2.42%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 2.42%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 2.42%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.61%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.61%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.61%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.61%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.61%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.61%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.61%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.81%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.81%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.81%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.81%   |
| Intel Pentium 3805U @ 1.90GHz               | 1         | 0.81%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.81%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 0.81%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.81%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 31.45%  |
| Intel Core i3           | 36        | 29.03%  |
| Intel Core i7           | 19        | 15.32%  |
| Intel Celeron           | 7         | 5.65%   |
| Intel Pentium           | 6         | 4.84%   |
| Intel Atom              | 4         | 3.23%   |
| Intel Pentium Dual-Core | 3         | 2.42%   |
| Intel Core 2 Duo        | 3         | 2.42%   |
| Other                   | 1         | 0.81%   |
| AMD Ryzen 3             | 1         | 0.81%   |
| AMD E2                  | 1         | 0.81%   |
| AMD E1                  | 1         | 0.81%   |
| AMD Athlon Neo X2       | 1         | 0.81%   |
| AMD Athlon II Dual-Core | 1         | 0.81%   |
| AMD A4                  | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 101       | 81.45%  |
| 4      | 20        | 16.13%  |
| 1      | 3         | 2.42%   |

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
| 2      | 96        | 77.42%  |
| 1      | 27        | 21.77%  |
| 4      | 1         | 0.81%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 122       | 98.39%  |
| Unknown        | 2         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 20.77%  |
| 0x306a9    | 18        | 13.85%  |
| 0x206a7    | 11        | 8.46%   |
| 0x40651    | 10        | 7.69%   |
| 0x20655    | 10        | 7.69%   |
| 0x406e3    | 9         | 6.92%   |
| 0x306d4    | 8         | 6.15%   |
| 0x30678    | 7         | 5.38%   |
| 0x806e9    | 5         | 3.85%   |
| 0x806ea    | 4         | 3.08%   |
| 0x1067a    | 4         | 3.08%   |
| 0x906e9    | 3         | 2.31%   |
| 0x306c3    | 2         | 1.54%   |
| 0x30661    | 2         | 1.54%   |
| 0x20652    | 2         | 1.54%   |
| 0x806ec    | 1         | 0.77%   |
| 0x806c1    | 1         | 0.77%   |
| 0x506c9    | 1         | 0.77%   |
| 0x406c3    | 1         | 0.77%   |
| 0x0810100b | 1         | 0.77%   |
| 0x0700010f | 1         | 0.77%   |
| 0x06006705 | 1         | 0.77%   |
| 0x05000119 | 1         | 0.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 23        | 18.55%  |
| Haswell       | 17        | 13.71%  |
| KabyLake      | 14        | 11.29%  |
| SandyBridge   | 13        | 10.48%  |
| Westmere      | 12        | 9.68%   |
| Skylake       | 11        | 8.87%   |
| Silvermont    | 9         | 7.26%   |
| Broadwell     | 8         | 6.45%   |
| Penryn        | 6         | 4.84%   |
| Bonnell       | 2         | 1.61%   |
| Zen           | 1         | 0.81%   |
| TigerLake     | 1         | 0.81%   |
| K8 Hammer     | 1         | 0.81%   |
| K10           | 1         | 0.81%   |
| Jaguar        | 1         | 0.81%   |
| Goldmont plus | 1         | 0.81%   |
| Goldmont      | 1         | 0.81%   |
| Excavator     | 1         | 0.81%   |
| Bobcat        | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 108       | 69.23%  |
| AMD    | 26        | 16.67%  |
| Nvidia | 22        | 14.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 22        | 14.1%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 13        | 8.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 12        | 7.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 10        | 6.41%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 5.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 8         | 5.13%   |
| Intel HD Graphics 620                                                                 | 6         | 3.85%   |
| Intel HD Graphics 5500                                                                | 6         | 3.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 6         | 3.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 5         | 3.21%   |
| Intel UHD Graphics 620                                                                | 4         | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 2.56%   |
| Intel HD Graphics 630                                                                 | 3         | 1.92%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 2         | 1.28%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                       | 2         | 1.28%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.28%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 2         | 1.28%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                     | 2         | 1.28%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 2         | 1.28%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 1         | 0.64%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 0.64%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 0.64%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 0.64%   |
| Nvidia GM108M [GeForce 940M]                                                          | 1         | 0.64%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.64%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 0.64%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 0.64%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 1         | 0.64%   |
| Nvidia GK104GLM [Quadro K4000M]                                                       | 1         | 0.64%   |
| Nvidia GF119M [GeForce 410M]                                                          | 1         | 0.64%   |
| Nvidia GF108M [GeForce GT 620M]                                                       | 1         | 0.64%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 0.64%   |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 0.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 0.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 0.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 0.64%   |
| Intel HD Graphics 6000                                                                | 1         | 0.64%   |
| Intel HD Graphics 510                                                                 | 1         | 0.64%   |
| Intel HD Graphics 500                                                                 | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 76        | 61.29%  |
| Intel + Nvidia | 18        | 14.52%  |
| Intel + AMD    | 14        | 11.29%  |
| 1 x AMD        | 12        | 9.68%   |
| 1 x Nvidia     | 4         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 90.4%   |
| Proprietary | 10        | 8%      |
| Unknown     | 2         | 1.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 65.87%  |
| 1.01-2.0   | 21        | 16.67%  |
| 0.01-0.5   | 10        | 7.94%   |
| 0.51-1.0   | 8         | 6.35%   |
| 3.01-4.0   | 4         | 3.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 30        | 22.9%   |
| AU Optronics            | 23        | 17.56%  |
| Samsung Electronics     | 22        | 16.79%  |
| BOE                     | 14        | 10.69%  |
| Chimei Innolux          | 13        | 9.92%   |
| Chi Mei Optoelectronics | 8         | 6.11%   |
| Hewlett-Packard         | 4         | 3.05%   |
| Apple                   | 3         | 2.29%   |
| AOC                     | 2         | 1.53%   |
| ___                     | 1         | 0.76%   |
| Sharp                   | 1         | 0.76%   |
| PANDA                   | 1         | 0.76%   |
| MStar                   | 1         | 0.76%   |
| LGD                     | 1         | 0.76%   |
| Lenovo                  | 1         | 0.76%   |
| InnoLux Display         | 1         | 0.76%   |
| Goldstar                | 1         | 0.76%   |
| BenQ                    | 1         | 0.76%   |
| AGO                     | 1         | 0.76%   |
| Acer                    | 1         | 0.76%   |
| Unknown                 | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 2.27%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 3         | 2.27%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 2.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 2.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.52%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 2         | 1.52%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 1.52%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 1.52%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 1.52%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 1.52%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 1.52%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 1.52%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 1.52%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 1.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.52%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 1.52%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.76%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.76%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch        | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC494A 1366x768 344x193mm 15.5-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3442 1366x768 344x194mm 15.5-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3241 1366x768 344x194mm 15.5-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 1         | 0.76%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 0.76%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 0.76%   |
| LGD LCD Monitor 1600x900                                                 | 1         | 0.76%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD0558 1920x1080 309x174mm 14.0-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 83        | 66.4%   |
| 1920x1080 (FHD)   | 25        | 20%     |
| 1600x900 (HD+)    | 5         | 4%      |
| 1440x900 (WXGA+)  | 3         | 2.4%    |
| 1280x800 (WXGA)   | 3         | 2.4%    |
| 3840x2160 (4K)    | 2         | 1.6%    |
| 1920x1200 (WUXGA) | 1         | 0.8%    |
| 1680x945          | 1         | 0.8%    |
| 1280x1024 (SXGA)  | 1         | 0.8%    |
| 1024x600          | 1         | 0.8%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 60.77%  |
| 13      | 14        | 10.77%  |
| 14      | 7         | 5.38%   |
| 12      | 7         | 5.38%   |
| 17      | 6         | 4.62%   |
| 18      | 5         | 3.85%   |
| 11      | 2         | 1.54%   |
| 10      | 2         | 1.54%   |
| 52      | 1         | 0.77%   |
| 37      | 1         | 0.77%   |
| 27      | 1         | 0.77%   |
| 24      | 1         | 0.77%   |
| 21      | 1         | 0.77%   |
| 20      | 1         | 0.77%   |
| 19      | 1         | 0.77%   |
| Unknown | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 94        | 72.87%  |
| 201-300     | 16        | 12.4%   |
| 401-500     | 7         | 5.43%   |
| 351-400     | 7         | 5.43%   |
| 501-600     | 2         | 1.55%   |
| 801-900     | 1         | 0.78%   |
| 1001-1500   | 1         | 0.78%   |
| Unknown     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 110       | 90.91%  |
| 16/10   | 7         | 5.79%   |
| 5/4     | 1         | 0.83%   |
| 4/3     | 1         | 0.83%   |
| 3/2     | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 79        | 60.77%  |
| 81-90          | 17        | 13.08%  |
| 61-70          | 6         | 4.62%   |
| 141-150        | 6         | 4.62%   |
| 71-80          | 5         | 3.85%   |
| 151-200        | 3         | 2.31%   |
| 121-130        | 3         | 2.31%   |
| 51-60          | 2         | 1.54%   |
| 41-50          | 2         | 1.54%   |
| 131-140        | 2         | 1.54%   |
| More than 1000 | 1         | 0.77%   |
| 301-350        | 1         | 0.77%   |
| 201-250        | 1         | 0.77%   |
| 501-1000       | 1         | 0.77%   |
| Unknown        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 75        | 58.59%  |
| 121-160 | 27        | 21.09%  |
| 51-100  | 19        | 14.84%  |
| 161-240 | 5         | 3.91%   |
| 1-50    | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 111       | 88.8%   |
| 2     | 11        | 8.8%    |
| 0     | 2         | 1.6%    |
| 3     | 1         | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 70        | 32.86%  |
| Intel                           | 45        | 21.13%  |
| Qualcomm Atheros                | 40        | 18.78%  |
| Broadcom                        | 27        | 12.68%  |
| Ralink Technology               | 8         | 3.76%   |
| Ralink                          | 6         | 2.82%   |
| Broadcom Limited                | 3         | 1.41%   |
| Samsung Electronics             | 2         | 0.94%   |
| MediaTek                        | 2         | 0.94%   |
| Huawei Technologies             | 2         | 0.94%   |
| Xiaomi                          | 1         | 0.47%   |
| Sierra Wireless                 | 1         | 0.47%   |
| Qualcomm Atheros Communications | 1         | 0.47%   |
| Nvidia                          | 1         | 0.47%   |
| Marvell Technology Group        | 1         | 0.47%   |
| LG Electronics                  | 1         | 0.47%   |
| Hewlett-Packard                 | 1         | 0.47%   |
| D-Link System                   | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 15.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 10.85%  |
| Broadcom BCM43142 802.11b/g/n                                     | 13        | 5.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 3.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.33%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.33%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.55%   |
| Intel Wireless 8260                                               | 4         | 1.55%   |
| Intel Wireless 7265                                               | 4         | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.55%   |
| Intel Wireless 7260                                               | 3         | 1.16%   |
| Intel Wireless 3160                                               | 3         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.16%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.16%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.16%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.78%   |
| Intel WiFi Link 5100                                              | 2         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.78%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.78%   |
| Intel Centrino Wireless-N 135                                     | 2         | 0.78%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.78%   |
| Broadcom BCM43225 802.11b/g/n                                     | 2         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.39%   |
| Sierra Wireless EM7305                                            | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 31.85%  |
| Qualcomm Atheros                | 36        | 26.67%  |
| Broadcom                        | 22        | 16.3%   |
| Realtek Semiconductor           | 13        | 9.63%   |
| Ralink Technology               | 8         | 5.93%   |
| Ralink                          | 6         | 4.44%   |
| Broadcom Limited                | 2         | 1.48%   |
| Sierra Wireless                 | 1         | 0.74%   |
| Qualcomm Atheros Communications | 1         | 0.74%   |
| MediaTek                        | 1         | 0.74%   |
| Hewlett-Packard                 | 1         | 0.74%   |
| D-Link System                   | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                  | 13        | 9.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 8.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 5.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 5.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 4.44%   |
| Intel Wireless 8265 / 8275                                     | 6         | 4.44%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 2.96%   |
| Intel Wireless 8260                                            | 4         | 2.96%   |
| Intel Wireless 7265                                            | 4         | 2.96%   |
| Intel Wireless 7260                                            | 3         | 2.22%   |
| Intel Wireless 3160                                            | 3         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 2.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 1.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.48%   |
| Intel WiFi Link 5100                                           | 2         | 1.48%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.48%   |
| Intel Centrino Wireless-N 135                                  | 2         | 1.48%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.48%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.48%   |
| Sierra Wireless EM7305                                         | 1         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.74%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.74%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.74%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 68        | 56.2%   |
| Intel                    | 27        | 22.31%  |
| Qualcomm Atheros         | 9         | 7.44%   |
| Broadcom                 | 8         | 6.61%   |
| Samsung Electronics      | 2         | 1.65%   |
| Xiaomi                   | 1         | 0.83%   |
| Nvidia                   | 1         | 0.83%   |
| MediaTek                 | 1         | 0.83%   |
| Marvell Technology Group | 1         | 0.83%   |
| LG Electronics           | 1         | 0.83%   |
| Huawei Technologies      | 1         | 0.83%   |
| Broadcom Limited         | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 32.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 22.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 3.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.28%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.46%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 2.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.82%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.82%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.82%   |
| MediaTek Infinix NOTE 11                                          | 1         | 0.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.82%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.82%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.82%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.82%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.82%   |
| Huawei E353/E3131                                                 | 1         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.82%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.82%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.82%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 51.46%  |
| Ethernet | 115       | 48.12%  |
| Modem    | 1         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 86.07%  |
| Ethernet | 17        | 13.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 114       | 90.48%  |
| 1     | 9         | 7.14%   |
| 0     | 3         | 2.38%   |

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
| Intel                           | 26        | 29.55%  |
| Qualcomm Atheros Communications | 12        | 13.64%  |
| Broadcom                        | 10        | 11.36%  |
| Realtek Semiconductor           | 7         | 7.95%   |
| Lite-On Technology              | 5         | 5.68%   |
| Foxconn / Hon Hai               | 5         | 5.68%   |
| Ralink                          | 4         | 4.55%   |
| Dell                            | 4         | 4.55%   |
| IMC Networks                    | 3         | 3.41%   |
| Foxconn International           | 3         | 3.41%   |
| Apple                           | 3         | 3.41%   |
| Toshiba                         | 2         | 2.27%   |
| Ralink Technology               | 1         | 1.14%   |
| Hewlett-Packard                 | 1         | 1.14%   |
| Chicony Electronics             | 1         | 1.14%   |
| Alps Electric                   | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 20        | 22.73%  |
| Qualcomm Atheros  Bluetooth Device                | 5         | 5.68%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 5         | 5.68%   |
| Ralink RT3290 Bluetooth                           | 4         | 4.55%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 4         | 4.55%   |
| Realtek Bluetooth Radio                           | 3         | 3.41%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 3         | 3.41%   |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 3.41%   |
| Toshiba Bluetooth Device                          | 2         | 2.27%   |
| Realtek RTL8723B Bluetooth                        | 2         | 2.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 2.27%   |
| IMC Networks Bluetooth Device                     | 2         | 2.27%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 2.27%   |
| Dell Wireless 365 Bluetooth                       | 2         | 2.27%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 2         | 2.27%   |
| Apple Bluetooth Host Controller                   | 2         | 2.27%   |
| Realtek RTL8821A Bluetooth                        | 1         | 1.14%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.14%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.14%   |
| Qualcomm Atheros Bluetooth                        | 1         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 1.14%   |
| Lite-On Wireless_Device                           | 1         | 1.14%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]       | 1         | 1.14%   |
| Lite-On BCM43142A0                                | 1         | 1.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 1         | 1.14%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 1.14%   |
| Foxconn / Hon Hai BCM43142A0                      | 1         | 1.14%   |
| Foxconn / Hon Hai Acer Module                     | 1         | 1.14%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.14%   |
| Dell BCM20702A0 Bluetooth Module                  | 1         | 1.14%   |
| Chicony Bluetooth (RTL8723BE)                     | 1         | 1.14%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 1.14%   |
| Broadcom Bluetooth Device                         | 1         | 1.14%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 1         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 1.14%   |
| Apple Bluetooth USB Host Controller               | 1         | 1.14%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel              | 114       | 83.82%  |
| AMD                | 14        | 10.29%  |
| Nvidia             | 6         | 4.41%   |
| Texas Instruments  | 1         | 0.74%   |
| Medeli Electronics | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 16.67%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 12.5%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 7.74%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 7.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 7.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 4.76%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.38%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.19%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.19%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.19%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.6%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Medeli Electronics USB Audio Device                                                               | 1         | 0.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.6%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.6%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.6%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 0.6%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.6%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 31.08%  |
| SK hynix            | 21        | 28.38%  |
| Micron Technology   | 12        | 16.22%  |
| Unknown             | 6         | 8.11%   |
| Kingston            | 4         | 5.41%   |
| Nanya Technology    | 2         | 2.7%    |
| Team                | 1         | 1.35%   |
| Ramaxel Technology  | 1         | 1.35%   |
| Elpida              | 1         | 1.35%   |
| Crucial             | 1         | 1.35%   |
| ASint Technology    | 1         | 1.35%   |
| A-DATA Technology   | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 4         | 4.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 4         | 4.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 4         | 4.94%   |
| Unknown RAM Module 4096MB SODIMM DDR3                    | 2         | 2.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 2.47%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s   | 2         | 2.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 2.47%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s    | 2         | 2.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 2.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 2         | 2.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s              | 1         | 1.23%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1         | 1.23%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1         | 1.23%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s     | 1         | 1.23%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s             | 1         | 1.23%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s         | 1         | 1.23%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 1.23%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 1.23%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s   | 1         | 1.23%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s   | 1         | 1.23%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s   | 1         | 1.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 1         | 1.23%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s | 1         | 1.23%   |
| SK hynix RAM HMA425S6BJR6N-UH 2GB SODIMM DDR4 2667MT/s   | 1         | 1.23%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s    | 1         | 1.23%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s | 1         | 1.23%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1         | 1.23%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s | 1         | 1.23%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 44        | 72.13%  |
| DDR4   | 13        | 21.31%  |
| SDRAM  | 2         | 3.28%   |
| LPDDR4 | 1         | 1.64%   |
| DDR2   | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 59        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 34        | 50%     |
| 8192  | 17        | 25%     |
| 2048  | 15        | 22.06%  |
| 32768 | 1         | 1.47%   |
| 16384 | 1         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 34        | 52.31%  |
| 2667    | 9         | 13.85%  |
| 1334    | 5         | 7.69%   |
| 1333    | 3         | 4.62%   |
| 4199    | 2         | 3.08%   |
| 3266    | 2         | 3.08%   |
| 2400    | 2         | 3.08%   |
| 2133    | 2         | 3.08%   |
| Unknown | 2         | 3.08%   |
| 3200    | 1         | 1.54%   |
| 1067    | 1         | 1.54%   |
| 667     | 1         | 1.54%   |
| 333     | 1         | 1.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson XP-200 Series | 1         | 33.33%  |
| Canon LBP6020             | 1         | 33.33%  |
| Canon LBP2900             | 1         | 33.33%  |

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
| Chicony Electronics                    | 26        | 23.01%  |
| Microdia                               | 19        | 16.81%  |
| Cheng Uei Precision Industry (Foxlink) | 11        | 9.73%   |
| Realtek Semiconductor                  | 10        | 8.85%   |
| Acer                                   | 10        | 8.85%   |
| Sunplus Innovation Technology          | 7         | 6.19%   |
| Suyin                                  | 5         | 4.42%   |
| Syntek                                 | 4         | 3.54%   |
| IMC Networks                           | 4         | 3.54%   |
| Silicon Motion                         | 3         | 2.65%   |
| Apple                                  | 3         | 2.65%   |
| Quanta                                 | 2         | 1.77%   |
| Lite-On Technology                     | 2         | 1.77%   |
| Alcor Micro                            | 2         | 1.77%   |
| Samsung Electronics                    | 1         | 0.88%   |
| Primax Electronics                     | 1         | 0.88%   |
| Pixart Imaging                         | 1         | 0.88%   |
| Aveo Technology                        | 1         | 0.88%   |
| ALi                                    | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 7         | 6.19%   |
| Acer Lenovo EasyCamera                                                   | 6         | 5.31%   |
| Chicony TOSHIBA Web Camera - HD                                          | 5         | 4.42%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 3.54%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 2.65%   |
| Microdia Integrated Webcam                                               | 3         | 2.65%   |
| Chicony Integrated Camera                                                | 3         | 2.65%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 1.77%   |
| Suyin HP Truevision HD                                                   | 2         | 1.77%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 1.77%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 1.77%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 2         | 1.77%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.77%   |
| Chicony HD WebCam                                                        | 2         | 1.77%   |
| Chicony Acer CrystalEye Webcam                                           | 2         | 1.77%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 1.77%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.77%   |
| Apple iPhone5/5C/5S/6                                                    | 2         | 1.77%   |
| Syntek USB2.0 Camera                                                     | 1         | 0.88%   |
| Syntek EasyCamera                                                        | 1         | 0.88%   |
| Suyin WebCam                                                             | 1         | 0.88%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.88%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 0.88%   |
| Sunplus Laptop Integrated Webcam HD                                      | 1         | 0.88%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.88%   |
| Sunplus Dell HD Webcam                                                   | 1         | 0.88%   |
| Silicon Motion WebCam SC-13HDL11431N                                     | 1         | 0.88%   |
| Silicon Motion WebCam SC-10HDD12636N                                     | 1         | 0.88%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 0.88%   |
| Samsung Galaxy A5 (MTP)                                                  | 1         | 0.88%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 1         | 0.88%   |
| Realtek USB Camera                                                       | 1         | 0.88%   |
| Realtek Lenovo EasyCamera                                                | 1         | 0.88%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 0.88%   |
| Realtek Integrated Webcam_HD                                             | 1         | 0.88%   |
| Realtek Integrated Webcam                                                | 1         | 0.88%   |
| Realtek HP Webcam                                                        | 1         | 0.88%   |
| Realtek HP Truevision HD                                                 | 1         | 0.88%   |
| Realtek HD Webcam - Realtek                                              | 1         | 0.88%   |
| Realtek Acer 640 x 480 laptop camera                                     | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 10        | 76.92%  |
| AuthenTec        | 2         | 15.38%  |
| Synaptics        | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 38.46%  |
| Validity Sensors VFS491                                    | 2         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 15.38%  |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| AuthenTec AES2810                                          | 1         | 7.69%   |
| AuthenTec AES1600                                          | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 9         | 90%     |
| OmniKey  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 40%     |
| Broadcom 5880                                                                | 4         | 40%     |
| OmniKey CardMan 4321                                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 81        | 63.78%  |
| 1     | 41        | 32.28%  |
| 2     | 4         | 3.15%   |
| 3     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 24.53%  |
| Net/wireless          | 10        | 18.87%  |
| Graphics card         | 10        | 18.87%  |
| Chipcard              | 10        | 18.87%  |
| Bluetooth             | 4         | 7.55%   |
| Storage               | 2         | 3.77%   |
| Net/ethernet          | 2         | 3.77%   |
| Multimedia controller | 1         | 1.89%   |
| Card reader           | 1         | 1.89%   |

