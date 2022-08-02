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

Total: 176

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 32        | 26.02%  |
| Ubuntu 18.04        | 13        | 10.57%  |
| OpenMandriva 4.2    | 9         | 7.32%   |
| Linux Mint 20.1     | 6         | 4.88%   |
| KDE neon 20.04      | 5         | 4.07%   |
| Pop!_OS 20.04       | 4         | 3.25%   |
| Xubuntu 20.04       | 3         | 2.44%   |
| Fedora 35           | 3         | 2.44%   |
| ArcoLinux Rolling   | 3         | 2.44%   |
| Arch                | 3         | 2.44%   |
| Ubuntu 20.10        | 2         | 1.63%   |
| Ubuntu 19.10        | 2         | 1.63%   |
| Ubuntu 16.04        | 2         | 1.63%   |
| ROSA R11            | 2         | 1.63%   |
| Manjaro             | 2         | 1.63%   |
| Kubuntu 20.04       | 2         | 1.63%   |
| Kali 2021.1         | 2         | 1.63%   |
| BlackPanther 18.1   | 2         | 1.63%   |
| Zorin 16            | 1         | 0.81%   |
| UbuntuDDE 20.04     | 1         | 0.81%   |
| Ubuntu Budgie 22.04 | 1         | 0.81%   |
| Ubuntu 22.04        | 1         | 0.81%   |
| Ubuntu 21.10        | 1         | 0.81%   |
| Ubuntu 21.04        | 1         | 0.81%   |
| ROSA R8.1           | 1         | 0.81%   |
| ROSA R10            | 1         | 0.81%   |
| Pop!_OS 21.04       | 1         | 0.81%   |
| Pear OS 20.04       | 1         | 0.81%   |
| Parrot 5.0          | 1         | 0.81%   |
| OpenMandriva 4.50   | 1         | 0.81%   |
| OpenMandriva 4.3    | 1         | 0.81%   |
| MX 19               | 1         | 0.81%   |
| Manjaro 20.1        | 1         | 0.81%   |
| Linux Mint 20.2     | 1         | 0.81%   |
| Linux Mint 20       | 1         | 0.81%   |
| Kali 2021.2         | 1         | 0.81%   |
| Fedora 31           | 1         | 0.81%   |
| Fedora 29           | 1         | 0.81%   |
| Debian 11           | 1         | 0.81%   |
| Debian 10           | 1         | 0.81%   |
| Clear Linux 34640   | 1         | 0.81%   |
| CentOS 7            | 1         | 0.81%   |
| Artix Rolling       | 1         | 0.81%   |
| ArchLabs 2020.11.04 | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 53        | 43.8%   |
| OpenMandriva  | 11        | 9.09%   |
| Linux Mint    | 8         | 6.61%   |
| Pop!_OS       | 5         | 4.13%   |
| KDE neon      | 5         | 4.13%   |
| Fedora        | 5         | 4.13%   |
| Xubuntu       | 3         | 2.48%   |
| ROSA          | 3         | 2.48%   |
| Manjaro       | 3         | 2.48%   |
| Kali          | 3         | 2.48%   |
| ArcoLinux     | 3         | 2.48%   |
| Arch          | 3         | 2.48%   |
| Kubuntu       | 2         | 1.65%   |
| Debian        | 2         | 1.65%   |
| BlackPanther  | 2         | 1.65%   |
| Zorin         | 1         | 0.83%   |
| UbuntuDDE     | 1         | 0.83%   |
| Ubuntu Budgie | 1         | 0.83%   |
| Pear OS       | 1         | 0.83%   |
| Parrot        | 1         | 0.83%   |
| MX            | 1         | 0.83%   |
| Clear Linux   | 1         | 0.83%   |
| CentOS        | 1         | 0.83%   |
| Artix         | 1         | 0.83%   |
| ArchLabs      | 1         | 0.83%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 9         | 6.98%   |
| 5.4.0-72-generic         | 4         | 3.1%    |
| 5.4.0-42-generic         | 4         | 3.1%    |
| 5.4.0-29-generic         | 4         | 3.1%    |
| 5.4.0-54-generic         | 3         | 2.33%   |
| 5.13.0-30-generic        | 3         | 2.33%   |
| 5.8.0-50-generic         | 2         | 1.55%   |
| 5.8.0-44-generic         | 2         | 1.55%   |
| 5.4.0-80-generic         | 2         | 1.55%   |
| 5.4.0-7625-generic       | 2         | 1.55%   |
| 5.4.0-65-generic         | 2         | 1.55%   |
| 5.4.0-56-generic         | 2         | 1.55%   |
| 5.4.0-52-generic         | 2         | 1.55%   |
| 5.4.0-48-generic         | 2         | 1.55%   |
| 5.4.0-33-generic         | 2         | 1.55%   |
| 5.3.0-40-generic         | 2         | 1.55%   |
| 5.11.0-27-generic        | 2         | 1.55%   |
| 5.11.0-25-generic        | 2         | 1.55%   |
| 4.18.16-desktop-1bP      | 2         | 1.55%   |
| 5.9.11-3-MANJARO         | 1         | 0.78%   |
| 5.8.0-63-generic         | 1         | 0.78%   |
| 5.8.0-48-generic         | 1         | 0.78%   |
| 5.8.0-45-generic         | 1         | 0.78%   |
| 5.8.0-43-generic         | 1         | 0.78%   |
| 5.8.0-36-generic         | 1         | 0.78%   |
| 5.7.17-2-MANJARO         | 1         | 0.78%   |
| 5.7.0-kali1-amd64        | 1         | 0.78%   |
| 5.6.0-2-amd64            | 1         | 0.78%   |
| 5.4.72-1-lts             | 1         | 0.78%   |
| 5.4.15-200.fc31.x86_64   | 1         | 0.78%   |
| 5.4.0-81-generic         | 1         | 0.78%   |
| 5.4.0-7626-generic       | 1         | 0.78%   |
| 5.4.0-74-generic         | 1         | 0.78%   |
| 5.4.0-70-generic         | 1         | 0.78%   |
| 5.4.0-58-generic         | 1         | 0.78%   |
| 5.4.0-51-generic         | 1         | 0.78%   |
| 5.4.0-47-generic         | 1         | 0.78%   |
| 5.4.0-40-generic         | 1         | 0.78%   |
| 5.4.0-39-generic         | 1         | 0.78%   |
| 5.4.0-37-generic         | 1         | 0.78%   |
| 5.4.0-31-generic         | 1         | 0.78%   |
| 5.4.0-26-generic         | 1         | 0.78%   |
| 5.3.0-51-generic         | 1         | 0.78%   |
| 5.3.0-46-generic         | 1         | 0.78%   |
| 5.3.0-42-generic         | 1         | 0.78%   |
| 5.3.0-28-generic         | 1         | 0.78%   |
| 5.3.0-18-generic         | 1         | 0.78%   |
| 5.17.4-200.fc35.x86_64   | 1         | 0.78%   |
| 5.16.7-desktop-1omv4003  | 1         | 0.78%   |
| 5.16.11-arch1-1          | 1         | 0.78%   |
| 5.15.8-76051508-generic  | 1         | 0.78%   |
| 5.15.7-zen1-1-zen        | 1         | 0.78%   |
| 5.15.7-arch1-1           | 1         | 0.78%   |
| 5.15.5-76051505-generic  | 1         | 0.78%   |
| 5.15.15-200.fc35.x86_64  | 1         | 0.78%   |
| 5.15.10-200.fc35.x86_64  | 1         | 0.78%   |
| 5.15.0-40-generic        | 1         | 0.78%   |
| 5.15.0-39-generic        | 1         | 0.78%   |
| 5.15.0-051500rc5-generic | 1         | 0.78%   |
| 5.14.0-9parrot1-amd64    | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 28.1%   |
| 5.8.0   | 9         | 7.44%   |
| 5.10.14 | 9         | 7.44%   |
| 5.3.0   | 7         | 5.79%   |
| 5.11.0  | 7         | 5.79%   |
| 5.13.0  | 6         | 4.96%   |
| 4.15.0  | 5         | 4.13%   |
| 5.0.0   | 4         | 3.31%   |
| 5.15.0  | 3         | 2.48%   |
| 5.10.0  | 3         | 2.48%   |
| 4.18.16 | 3         | 2.48%   |
| 5.15.7  | 2         | 1.65%   |
| 4.4.0   | 2         | 1.65%   |
| 5.9.11  | 1         | 0.83%   |
| 5.7.17  | 1         | 0.83%   |
| 5.7.0   | 1         | 0.83%   |
| 5.6.0   | 1         | 0.83%   |
| 5.4.72  | 1         | 0.83%   |
| 5.4.15  | 1         | 0.83%   |
| 5.17.4  | 1         | 0.83%   |
| 5.16.7  | 1         | 0.83%   |
| 5.16.11 | 1         | 0.83%   |
| 5.15.8  | 1         | 0.83%   |
| 5.15.5  | 1         | 0.83%   |
| 5.15.15 | 1         | 0.83%   |
| 5.15.10 | 1         | 0.83%   |
| 5.14.0  | 1         | 0.83%   |
| 5.13.2  | 1         | 0.83%   |
| 5.12.5  | 1         | 0.83%   |
| 5.12.4  | 1         | 0.83%   |
| 5.12.15 | 1         | 0.83%   |
| 5.11.15 | 1         | 0.83%   |
| 5.10.82 | 1         | 0.83%   |
| 5.10.3  | 1         | 0.83%   |
| 4.9.9   | 1         | 0.83%   |
| 4.9.60  | 1         | 0.83%   |
| 4.19.79 | 1         | 0.83%   |
| 4.19.0  | 1         | 0.83%   |
| 4.18.0  | 1         | 0.83%   |
| 3.10.0  | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 29.75%  |
| 5.10    | 14        | 11.57%  |
| 5.8     | 9         | 7.44%   |
| 5.15    | 9         | 7.44%   |
| 5.11    | 8         | 6.61%   |
| 5.3     | 7         | 5.79%   |
| 5.13    | 7         | 5.79%   |
| 4.15    | 5         | 4.13%   |
| 5.0     | 4         | 3.31%   |
| 4.18    | 4         | 3.31%   |
| 5.12    | 3         | 2.48%   |
| 5.7     | 2         | 1.65%   |
| 5.16    | 2         | 1.65%   |
| 4.9     | 2         | 1.65%   |
| 4.4     | 2         | 1.65%   |
| 4.19    | 2         | 1.65%   |
| 5.9     | 1         | 0.83%   |
| 5.6     | 1         | 0.83%   |
| 5.17    | 1         | 0.83%   |
| 5.14    | 1         | 0.83%   |
| 3.10    | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 108       | 98.18%  |
| i686   | 2         | 1.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 57        | 48.72%  |
| KDE5       | 19        | 16.24%  |
| Unknown    | 13        | 11.11%  |
| XFCE       | 9         | 7.69%   |
| X-Cinnamon | 4         | 3.42%   |
| KDE        | 4         | 3.42%   |
| MATE       | 3         | 2.56%   |
| KDE4       | 2         | 1.71%   |
| Unity      | 1         | 0.85%   |
| LXQt       | 1         | 0.85%   |
| i3         | 1         | 0.85%   |
| Deepin     | 1         | 0.85%   |
| Cinnamon   | 1         | 0.85%   |
| Budgie     | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 98        | 87.5%   |
| Wayland | 7         | 6.25%   |
| Unknown | 6         | 5.36%   |
| Tty     | 1         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 68        | 58.62%  |
| SDDM    | 16        | 13.79%  |
| GDM     | 15        | 12.93%  |
| LightDM | 9         | 7.76%   |
| TDM     | 4         | 3.45%   |
| KDM     | 2         | 1.72%   |
| SLiM    | 1         | 0.86%   |
| GDM3    | 1         | 0.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 53        | 47.32%  |
| fr_FR   | 33        | 29.46%  |
| Unknown | 13        | 11.61%  |
| en_GB   | 4         | 3.57%   |
| C       | 4         | 3.57%   |
| ar_DZ   | 2         | 1.79%   |
| fr_DZ   | 1         | 0.89%   |
| fr_BE   | 1         | 0.89%   |
| ar_EG   | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 77        | 67.54%  |
| EFI  | 37        | 32.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 75.65%  |
| Overlay | 13        | 11.3%   |
| Btrfs   | 6         | 5.22%   |
| Unknown | 4         | 3.48%   |
| Ext2    | 3         | 2.61%   |
| Xfs     | 1         | 0.87%   |
| Ext3    | 1         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 67.26%  |
| MBR     | 20        | 17.7%   |
| GPT     | 17        | 15.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 83.33%  |
| Yes       | 19        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 51.79%  |
| No        | 54        | 48.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 26        | 23.64%  |
| Hewlett-Packard     | 22        | 20%     |
| Lenovo              | 17        | 15.45%  |
| Acer                | 11        | 10%     |
| Toshiba             | 8         | 7.27%   |
| ASUSTek Computer    | 8         | 7.27%   |
| Sony                | 6         | 5.45%   |
| Packard Bell        | 3         | 2.73%   |
| Samsung Electronics | 2         | 1.82%   |
| Fujitsu             | 2         | 1.82%   |
| Apple               | 2         | 1.82%   |
| MSI                 | 1         | 0.91%   |
| LDLC                | 1         | 0.91%   |
| eMachines           | 1         | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba Satellite C55-B             | 2         | 1.82%   |
| Lenovo IdeaPad 300-15ISK 80Q7       | 2         | 1.82%   |
| Lenovo G560 20042                   | 2         | 1.82%   |
| Lenovo G50-30 80G0                  | 2         | 1.82%   |
| Lenovo B50-70 20384                 | 2         | 1.82%   |
| HP ProBook 4540s                    | 2         | 1.82%   |
| HP Pavilion 15                      | 2         | 1.82%   |
| HP 15                               | 2         | 1.82%   |
| Dell Latitude E7440                 | 2         | 1.82%   |
| Dell Latitude E5430 vPro            | 2         | 1.82%   |
| Dell Inspiron N5110                 | 2         | 1.82%   |
| Dell Inspiron 3542                  | 2         | 1.82%   |
| Dell Inspiron 15-3567               | 2         | 1.82%   |
| Acer Aspire 5738                    | 2         | 1.82%   |
| Toshiba Satellite C850-A979         | 1         | 0.91%   |
| Toshiba Satellite C50-A560          | 1         | 0.91%   |
| Toshiba Satellite C50-A545          | 1         | 0.91%   |
| Toshiba Satellite C50-A539          | 1         | 0.91%   |
| Toshiba PORTEGE R30-A               | 1         | 0.91%   |
| Toshiba PORTEGE M780                | 1         | 0.91%   |
| Sony VPCEJ2S1E                      | 1         | 0.91%   |
| Sony VPCEH2H1E                      | 1         | 0.91%   |
| Sony VGN-AW21M_H                    | 1         | 0.91%   |
| Sony SVF1531GSFB                    | 1         | 0.91%   |
| Sony SVE1713A6EW                    | 1         | 0.91%   |
| Sony SVE1513K1EW                    | 1         | 0.91%   |
| Samsung N102SP/N100SP/N101SP        | 1         | 0.91%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B | 1         | 0.91%   |
| Packard Bell EasyNote TJ75          | 1         | 0.91%   |
| Packard Bell EasyNote LJ71          | 1         | 0.91%   |
| Packard Bell DOT S                  | 1         | 0.91%   |
| MSI CR610M                          | 1         | 0.91%   |
| Lenovo ThinkPad X260 20F5S1G104     | 1         | 0.91%   |
| Lenovo ThinkPad X201 3680AQ1        | 1         | 0.91%   |
| Lenovo ThinkPad T450 20BUS2RN1H     | 1         | 0.91%   |
| Lenovo ThinkPad T440 20B6S00200     | 1         | 0.91%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 0.91%   |
| Lenovo IdeaPad 310-15IKB 80TV       | 1         | 0.91%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 0.91%   |
| Lenovo G580 2189                    | 1         | 0.91%   |
| Lenovo G500 20236                   | 1         | 0.91%   |
| LDLC Mercure MH                     | 1         | 0.91%   |
| HP ZBook 15 G4                      | 1         | 0.91%   |
| HP ProBook 650 G1                   | 1         | 0.91%   |
| HP ProBook 4720s                    | 1         | 0.91%   |
| HP ProBook 450 G6                   | 1         | 0.91%   |
| HP ProBook 450 G3                   | 1         | 0.91%   |
| HP ProBook 450 G2                   | 1         | 0.91%   |
| HP ProBook 450 G0                   | 1         | 0.91%   |
| HP Pavilion Notebook                | 1         | 0.91%   |
| HP Notebook                         | 1         | 0.91%   |
| HP Laptop 15-bw0xx                  | 1         | 0.91%   |
| HP ElitePad 1000 G2                 | 1         | 0.91%   |
| HP EliteBook Folio 9470m            | 1         | 0.91%   |
| HP EliteBook 840 G3                 | 1         | 0.91%   |
| HP EliteBook 820 G3                 | 1         | 0.91%   |
| HP 630                              | 1         | 0.91%   |
| HP 250 G4                           | 1         | 0.91%   |
| Fujitsu LIFEBOOK AH532/G21          | 1         | 0.91%   |
| Fujitsu LIFEBOOK A532               | 1         | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 12        | 10.91%  |
| Dell Latitude         | 10        | 9.09%   |
| Acer Aspire           | 9         | 8.18%   |
| HP ProBook            | 8         | 7.27%   |
| Toshiba Satellite     | 6         | 5.45%   |
| Lenovo IdeaPad        | 5         | 4.55%   |
| Lenovo ThinkPad       | 4         | 3.64%   |
| HP Pavilion           | 3         | 2.73%   |
| HP EliteBook          | 3         | 2.73%   |
| Toshiba PORTEGE       | 2         | 1.82%   |
| Packard Bell EasyNote | 2         | 1.82%   |
| Lenovo G560           | 2         | 1.82%   |
| Lenovo G50-30         | 2         | 1.82%   |
| Lenovo B50-70         | 2         | 1.82%   |
| HP 15                 | 2         | 1.82%   |
| Fujitsu LIFEBOOK      | 2         | 1.82%   |
| Dell Precision        | 2         | 1.82%   |
| Acer Extensa          | 2         | 1.82%   |
| Sony VPCEJ2S1E        | 1         | 0.91%   |
| Sony VPCEH2H1E        | 1         | 0.91%   |
| Sony VGN-AW21M        | 1         | 0.91%   |
| Sony SVF1531GSFB      | 1         | 0.91%   |
| Sony SVE1713A6EW      | 1         | 0.91%   |
| Sony SVE1513K1EW      | 1         | 0.91%   |
| Samsung N102SP        | 1         | 0.91%   |
| Samsung 700Z3A        | 1         | 0.91%   |
| Packard Bell DOT      | 1         | 0.91%   |
| MSI CR610M            | 1         | 0.91%   |
| Lenovo G580           | 1         | 0.91%   |
| Lenovo G500           | 1         | 0.91%   |
| LDLC Mercure          | 1         | 0.91%   |
| HP ZBook              | 1         | 0.91%   |
| HP Notebook           | 1         | 0.91%   |
| HP Laptop             | 1         | 0.91%   |
| HP ElitePad           | 1         | 0.91%   |
| HP 630                | 1         | 0.91%   |
| HP 250                | 1         | 0.91%   |
| eMachines eME732      | 1         | 0.91%   |
| Dell XPS              | 1         | 0.91%   |
| Dell Vostro           | 1         | 0.91%   |
| ASUS X55U             | 1         | 0.91%   |
| ASUS X555LAB          | 1         | 0.91%   |
| ASUS X551CA           | 1         | 0.91%   |
| ASUS X541UV           | 1         | 0.91%   |
| ASUS X540SA           | 1         | 0.91%   |
| ASUS X205TAW          | 1         | 0.91%   |
| ASUS K50IE            | 1         | 0.91%   |
| ASUS GL753VD          | 1         | 0.91%   |
| Apple MacBookPro8     | 1         | 0.91%   |
| Apple MacBook7        | 1         | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 19        | 17.27%  |
| 2014 | 17        | 15.45%  |
| 2013 | 16        | 14.55%  |
| 2016 | 10        | 9.09%   |
| 2017 | 9         | 8.18%   |
| 2015 | 9         | 8.18%   |
| 2010 | 9         | 8.18%   |
| 2011 | 7         | 6.36%   |
| 2009 | 7         | 6.36%   |
| 2018 | 5         | 4.55%   |
| 2021 | 1         | 0.91%   |
| 2008 | 1         | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 110       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 109       | 99.09%  |
| Enabled  | 1         | 0.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 48        | 43.64%  |
| 4.01-8.0   | 30        | 27.27%  |
| 8.01-16.0  | 19        | 17.27%  |
| 1.01-2.0   | 6         | 5.45%   |
| 16.01-24.0 | 3         | 2.73%   |
| 32.01-64.0 | 2         | 1.82%   |
| 2.01-3.0   | 2         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 64        | 51.61%  |
| 2.01-3.0  | 35        | 28.23%  |
| 3.01-4.0  | 13        | 10.48%  |
| 0.51-1.0  | 7         | 5.65%   |
| 4.01-8.0  | 4         | 3.23%   |
| 8.01-16.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 74.77%  |
| 2      | 26        | 23.42%  |
| 4      | 1         | 0.9%    |
| 0      | 1         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 70.91%  |
| No        | 32        | 29.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 93.64%  |
| No        | 7         | 6.36%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 98.2%   |
| No        | 2         | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 70.54%  |
| No        | 33        | 29.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Algeria | 110       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Algiers              | 19        | 15.08%  |
| Tlemcen              | 7         | 5.56%   |
| Belcourt             | 6         | 4.76%   |
| Oran                 | 5         | 3.97%   |
| Skikda               | 4         | 3.17%   |
| Relizane             | 4         | 3.17%   |
| Cheraga              | 4         | 3.17%   |
| Birkhadem            | 4         | 3.17%   |
| Sétif               | 3         | 2.38%   |
| Laghouat             | 3         | 2.38%   |
| Blida                | 3         | 2.38%   |
| Béjaïa             | 3         | 2.38%   |
| ash-Shalif           | 3         | 2.38%   |
| Annaba               | 3         | 2.38%   |
| Tizi Ouzou           | 2         | 1.59%   |
| Tipasa               | 2         | 1.59%   |
| Saida                | 2         | 1.59%   |
| Kouba                | 2         | 1.59%   |
| Djelfa               | 2         | 1.59%   |
| Constantine          | 2         | 1.59%   |
| Biskra               | 2         | 1.59%   |
| Bir el Djir          | 2         | 1.59%   |
| Ain Fakroun          | 2         | 1.59%   |
| Tolga                | 1         | 0.79%   |
| Tichi                | 1         | 0.79%   |
| Tazoult-Lambese      | 1         | 0.79%   |
| Souma                | 1         | 0.79%   |
| Sidi Kada            | 1         | 0.79%   |
| Sidi Bel Abbes       | 1         | 0.79%   |
| Saoula               | 1         | 0.79%   |
| Reguiba              | 1         | 0.79%   |
| Ouenza               | 1         | 0.79%   |
| M'Sila               | 1         | 0.79%   |
| Larbaâ              | 1         | 0.79%   |
| Jijelli              | 1         | 0.79%   |
| El Oued              | 1         | 0.79%   |
| El Khroub            | 1         | 0.79%   |
| El Eulma             | 1         | 0.79%   |
| El Aouinet           | 1         | 0.79%   |
| Dunqulah             | 1         | 0.79%   |
| Draria               | 1         | 0.79%   |
| Debila               | 1         | 0.79%   |
| Brezina              | 1         | 0.79%   |
| BouГЇra            | 1         | 0.79%   |
| Boumerdes            | 1         | 0.79%   |
| Boudouaou            | 1         | 0.79%   |
| Bordj el Kiffan      | 1         | 0.79%   |
| Berhoum              | 1         | 0.79%   |
| Ben ’Aknoûn       | 1         | 0.79%   |
| Ben вЂ™AknoГ»n | 1         | 0.79%   |
| Batna City           | 1         | 0.79%   |
| Baba Hassen          | 1         | 0.79%   |
| Bab Ezzouar          | 1         | 0.79%   |
| Aomar                | 1         | 0.79%   |
| Ain Taya             | 1         | 0.79%   |
| Ain Oussera          | 1         | 0.79%   |
| Ain el Bya           | 1         | 0.79%   |
| Ain Bessem           | 1         | 0.79%   |
| Ain Beida            | 1         | 0.79%   |
| Aflou                | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 24        | 32     | 18.6%   |
| WDC                   | 21        | 25     | 16.28%  |
| Toshiba               | 21        | 22     | 16.28%  |
| HGST                  | 13        | 17     | 10.08%  |
| Hitachi               | 12        | 14     | 9.3%    |
| Samsung Electronics   | 7         | 7      | 5.43%   |
| A-DATA Technology     | 5         | 5      | 3.88%   |
| Unknown               | 4         | 5      | 3.1%    |
| Lexar                 | 4         | 4      | 3.1%    |
| SanDisk               | 3         | 3      | 2.33%   |
| LITEON                | 3         | 6      | 2.33%   |
| SK hynix              | 2         | 2      | 1.55%   |
| Intel                 | 2         | 2      | 1.55%   |
| XPG                   | 1         | 1      | 0.78%   |
| Team                  | 1         | 1      | 0.78%   |
| Realtek Semiconductor | 1         | 1      | 0.78%   |
| PNY                   | 1         | 1      | 0.78%   |
| Micron Technology     | 1         | 2      | 0.78%   |
| Kingston              | 1         | 1      | 0.78%   |
| HUAWEI                | 1         | 1      | 0.78%   |
| Fujitsu               | 1         | 2      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB              | 8         | 6.06%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 3.03%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 3         | 2.27%   |
| Toshiba MQ01ABD100 1TB                | 3         | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 2.27%   |
| Seagate Expansion 1TB                 | 3         | 2.27%   |
| HGST HTS545050A7E680 500GB            | 3         | 2.27%   |
| HGST HTS545050A7E380 500GB            | 3         | 2.27%   |
| Unknown MMC Card  64GB                | 2         | 1.52%   |
| Seagate ST500VT000-1DK142 500GB       | 2         | 1.52%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 1.52%   |
| Seagate ST320LT020-9YG142 320GB       | 2         | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 1.52%   |
| Lexar 512GB SSD                       | 2         | 1.52%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 1.52%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 1.52%   |
| HGST HTS725050A7E630 500GB            | 2         | 1.52%   |
| HGST HTS541010A9E680 1TB              | 2         | 1.52%   |
| XPG SX950U 960GB                      | 1         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.76%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.76%   |
| WDC WDS100T2B0B-00YS70 1TB SSD        | 1         | 0.76%   |
| WDC WD5000LUCT-62RC2Y0 500GB          | 1         | 0.76%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.76%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.76%   |
| WDC WD5000LPVT-16G33T0 500GB          | 1         | 0.76%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 0.76%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 1         | 0.76%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 1         | 0.76%   |
| WDC WD5000BPVT-75HXZT3 500GB          | 1         | 0.76%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 0.76%   |
| WDC WD3200BVVT-63A26Y0 320GB          | 1         | 0.76%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 0.76%   |
| WDC WD3200BEKT-75PVMT1 320GB          | 1         | 0.76%   |
| WDC WD3200BEKT-75KA9T0 320GB          | 1         | 0.76%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 0.76%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.76%   |
| WDC WD10JPVX-08JC3T5 1TB              | 1         | 0.76%   |
| Unknown SA16G  16GB                   | 1         | 0.76%   |
| Unknown MMC Card  32GB                | 1         | 0.76%   |
| Unknown MMC Card  128GB               | 1         | 0.76%   |
| Toshiba MQ01ABF032 320GB              | 1         | 0.76%   |
| Toshiba MQ01ABD075 752GB              | 1         | 0.76%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 0.76%   |
| Toshiba MK7559GSXF 752GB              | 1         | 0.76%   |
| Toshiba MK6459GSXP 640GB              | 1         | 0.76%   |
| Toshiba MK5059GSXP 500GB              | 1         | 0.76%   |
| Toshiba MK4058GSX 400GB               | 1         | 0.76%   |
| Toshiba MK3259GSXP 320GB              | 1         | 0.76%   |
| Toshiba MK3259GSX 320GB               | 1         | 0.76%   |
| Toshiba MK2555GSXF 250GB              | 1         | 0.76%   |
| Team T253X2512G 512GB SSD             | 1         | 0.76%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 0.76%   |
| SK hynix HCG8e  64GB                  | 1         | 0.76%   |
| Seagate ST9500325AS 500GB             | 1         | 0.76%   |
| Seagate ST9320325AS 320GB             | 1         | 0.76%   |
| Seagate ST9250311CS 250GB             | 1         | 0.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 0.76%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB    | 1         | 0.76%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 32     | 26.37%  |
| Toshiba             | 21        | 22     | 23.08%  |
| WDC                 | 19        | 22     | 20.88%  |
| HGST                | 13        | 17     | 14.29%  |
| Hitachi             | 12        | 14     | 13.19%  |
| Samsung Electronics | 1         | 1      | 1.1%    |
| Fujitsu             | 1         | 2      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 5         | 5      | 19.23%  |
| WDC                 | 3         | 3      | 11.54%  |
| SanDisk             | 3         | 3      | 11.54%  |
| LITEON              | 3         | 6      | 11.54%  |
| Lexar               | 3         | 3      | 11.54%  |
| Samsung Electronics | 2         | 2      | 7.69%   |
| Intel               | 2         | 2      | 7.69%   |
| XPG                 | 1         | 1      | 3.85%   |
| Team                | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 110    | 71.31%  |
| SSD     | 24        | 29     | 19.67%  |
| NVMe    | 6         | 8      | 4.92%   |
| MMC     | 4         | 6      | 3.28%   |
| Unknown | 1         | 1      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 135    | 87.07%  |
| NVMe | 6         | 8      | 5.17%   |
| SAS  | 5         | 5      | 4.31%   |
| MMC  | 4         | 6      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 107    | 72.32%  |
| 0.51-1.0   | 30        | 31     | 26.79%  |
| 1.01-2.0   | 1         | 1      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 34        | 29.06%  |
| 51-100     | 22        | 18.8%   |
| 101-250    | 17        | 14.53%  |
| 501-1000   | 15        | 12.82%  |
| 21-50      | 11        | 9.4%    |
| 1-20       | 11        | 9.4%    |
| 1001-2000  | 5         | 4.27%   |
| Unknown    | 2         | 1.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 60        | 48.78%  |
| 21-50    | 21        | 17.07%  |
| 101-250  | 18        | 14.63%  |
| 51-100   | 11        | 8.94%   |
| 251-500  | 7         | 5.69%   |
| 501-1000 | 4         | 3.25%   |
| Unknown  | 2         | 1.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 1      | 7.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 7.69%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 7.69%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 7.69%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 7.69%   |
| Samsung Electronics HM320HJ 320GB | 1         | 1      | 7.69%   |
| Hitachi HTS723225L9A360 250GB     | 1         | 1      | 7.69%   |
| Hitachi HTS547564A9E384 640GB     | 1         | 1      | 7.69%   |
| Hitachi HTS542516K9SA00 160GB     | 1         | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB        | 1         | 3      | 7.69%   |
| HGST HTS545050A7E680 500GB        | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 23.08%  |
| Hitachi             | 3         | 3      | 23.08%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| HGST                | 2         | 4      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 23.08%  |
| Hitachi             | 3         | 3      | 23.08%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| HGST                | 2         | 4      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 100%    |

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
| Detected | 76        | 107    | 66.67%  |
| Works    | 25        | 32     | 21.93%  |
| Malfunc  | 13        | 15     | 11.4%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 87.72%  |
| AMD                   | 5         | 4.39%   |
| Samsung Electronics   | 4         | 3.51%   |
| Nvidia                | 2         | 1.75%   |
| Silicon Motion        | 1         | 0.88%   |
| Realtek Semiconductor | 1         | 0.88%   |
| Micron Technology     | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 17.95%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 13.68%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 9.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 6.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 5.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 5.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 3.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 3.42%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.71%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                            | 2         | 1.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.85%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.85%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.85%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.85%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.85%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 92        | 80%     |
| RAID | 12        | 10.43%  |
| NVMe | 6         | 5.22%   |
| IDE  | 5         | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 95.45%  |
| AMD    | 5         | 4.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-3217U CPU @ 1.80GHz           | 5         | 4.55%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 3.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 4         | 3.64%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 2.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 2.73%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 2.73%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.82%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.82%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.82%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.82%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.82%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.82%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.82%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.91%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.91%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.91%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.91%   |
| Intel Pentium 3805U @ 1.90GHz               | 1         | 0.91%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.91%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.91%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.91%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.91%   |
| Intel Core i7-2675QM CPU @ 2.20GHz          | 1         | 0.91%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.91%   |
| Intel Core i5-6198DU CPU @ 2.30GHz          | 1         | 0.91%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.91%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.91%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 0.91%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.91%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 0.91%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.91%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 0.91%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 1         | 0.91%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 0.91%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 0.91%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 0.91%   |
| Intel Core i3-2348M CPU @ 2.30GHz           | 1         | 0.91%   |
| Intel Core i3-2328M CPU @ 2.20GHz           | 1         | 0.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 0.91%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 0.91%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 0.91%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 30.91%  |
| Intel Core i3           | 32        | 29.09%  |
| Intel Core i7           | 17        | 15.45%  |
| Intel Pentium           | 6         | 5.45%   |
| Intel Celeron           | 5         | 4.55%   |
| Intel Atom              | 4         | 3.64%   |
| Intel Pentium Dual-Core | 3         | 2.73%   |
| Intel Core 2 Duo        | 3         | 2.73%   |
| Other                   | 1         | 0.91%   |
| AMD Ryzen 3             | 1         | 0.91%   |
| AMD E2                  | 1         | 0.91%   |
| AMD E1                  | 1         | 0.91%   |
| AMD Athlon II Dual-Core | 1         | 0.91%   |
| AMD A4                  | 1         | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 90        | 81.82%  |
| 4      | 18        | 16.36%  |
| 1      | 2         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 110       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 86        | 78.18%  |
| 1      | 24        | 21.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 108       | 98.18%  |
| Unknown        | 2         | 1.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 18.26%  |
| 0x306a9    | 17        | 14.78%  |
| 0x206a7    | 10        | 8.7%    |
| 0x20655    | 10        | 8.7%    |
| 0x40651    | 9         | 7.83%   |
| 0x406e3    | 8         | 6.96%   |
| 0x30678    | 7         | 6.09%   |
| 0x306d4    | 6         | 5.22%   |
| 0x806ea    | 4         | 3.48%   |
| 0x806e9    | 4         | 3.48%   |
| 0x1067a    | 4         | 3.48%   |
| 0x906e9    | 2         | 1.74%   |
| 0x30661    | 2         | 1.74%   |
| 0x20652    | 2         | 1.74%   |
| 0x806ec    | 1         | 0.87%   |
| 0x806c1    | 1         | 0.87%   |
| 0x506c9    | 1         | 0.87%   |
| 0x406c3    | 1         | 0.87%   |
| 0x306c3    | 1         | 0.87%   |
| 0x0810100b | 1         | 0.87%   |
| 0x0700010f | 1         | 0.87%   |
| 0x06006705 | 1         | 0.87%   |
| 0x05000119 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 20        | 18.18%  |
| Haswell     | 14        | 12.73%  |
| Westmere    | 12        | 10.91%  |
| SandyBridge | 12        | 10.91%  |
| KabyLake    | 12        | 10.91%  |
| Skylake     | 10        | 9.09%   |
| Silvermont  | 9         | 8.18%   |
| Penryn      | 6         | 5.45%   |
| Broadwell   | 6         | 5.45%   |
| Bonnell     | 2         | 1.82%   |
| Zen         | 1         | 0.91%   |
| TigerLake   | 1         | 0.91%   |
| K10         | 1         | 0.91%   |
| Jaguar      | 1         | 0.91%   |
| Goldmont    | 1         | 0.91%   |
| Excavator   | 1         | 0.91%   |
| Bobcat      | 1         | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 95        | 67.86%  |
| AMD    | 25        | 17.86%  |
| Nvidia | 20        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 13.57%  |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 7.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 7.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 6.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 6.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 5.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 4.29%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 3.57%   |
| Intel HD Graphics 620                                                                    | 5         | 3.57%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.57%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.14%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.43%   |
| Intel HD Graphics 630                                                                    | 2         | 1.43%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.43%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.43%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.43%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 1.43%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 1.43%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.71%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.71%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.71%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.71%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.71%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.71%   |
| Nvidia GK104GLM [Quadro K4000M]                                                          | 1         | 0.71%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.71%   |
| Nvidia GF108M [GeForce GT 620M]                                                          | 1         | 0.71%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.71%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.71%   |
| Intel HD Graphics 510                                                                    | 1         | 0.71%   |
| Intel HD Graphics 500                                                                    | 1         | 0.71%   |
| Intel HD Graphics                                                                        | 1         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.71%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.71%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.71%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.71%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.71%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.71%   |
| AMD Mars [Radeon HD 8730M]                                                               | 1         | 0.71%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.71%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 0.71%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 59.09%  |
| Intel + Nvidia | 16        | 14.55%  |
| Intel + AMD    | 14        | 12.73%  |
| 1 x AMD        | 11        | 10%     |
| 1 x Nvidia     | 4         | 3.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 99        | 89.19%  |
| Proprietary | 10        | 9.01%   |
| Unknown     | 2         | 1.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 64.29%  |
| 1.01-2.0   | 19        | 16.96%  |
| 0.01-0.5   | 9         | 8.04%   |
| 0.51-1.0   | 8         | 7.14%   |
| 3.01-4.0   | 4         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 23        | 20.18%  |
| Samsung Electronics     | 22        | 19.3%   |
| AU Optronics            | 20        | 17.54%  |
| BOE                     | 13        | 11.4%   |
| Chimei Innolux          | 12        | 10.53%  |
| Chi Mei Optoelectronics | 7         | 6.14%   |
| Hewlett-Packard         | 3         | 2.63%   |
| Apple                   | 2         | 1.75%   |
| ___                     | 1         | 0.88%   |
| Sharp                   | 1         | 0.88%   |
| PANDA                   | 1         | 0.88%   |
| MStar                   | 1         | 0.88%   |
| LGD                     | 1         | 0.88%   |
| Lenovo                  | 1         | 0.88%   |
| InnoLux Display         | 1         | 0.88%   |
| Goldstar                | 1         | 0.88%   |
| BenQ                    | 1         | 0.88%   |
| AOC                     | 1         | 0.88%   |
| Acer                    | 1         | 0.88%   |
| Unknown                 | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 2.63%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 2.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 2.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 1.75%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 1.75%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 1.75%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 1.75%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 2         | 1.75%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 1.75%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.75%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 1.75%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.88%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.88%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch        | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC494A 1366x768 344x193mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3442 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 370x230mm 17.2-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3241 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 0.88%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 0.88%   |
| LGD LCD Monitor 1600x900                                                 | 1         | 0.88%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch             | 1         | 0.88%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch             | 1         | 0.88%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch             | 1         | 0.88%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch             | 1         | 0.88%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD01F5 1280x800 304x190mm 14.1-inch              | 1         | 0.88%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 0.88%   |
| InnoLux Display LCD Monitor INL0006 1366x768 344x194mm 15.5-inch         | 1         | 0.88%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch                | 1         | 0.88%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch              | 1         | 0.88%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch               | 1         | 0.88%   |
| Goldstar L1720B GSM4372 1280x1024 338x270mm 17.0-inch                    | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch         | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch          | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 73        | 66.36%  |
| 1920x1080 (FHD)   | 21        | 19.09%  |
| 1600x900 (HD+)    | 5         | 4.55%   |
| 1280x800 (WXGA)   | 3         | 2.73%   |
| 3840x2160 (4K)    | 2         | 1.82%   |
| 1440x900 (WXGA+)  | 2         | 1.82%   |
| 1920x1200 (WUXGA) | 1         | 0.91%   |
| 1680x945          | 1         | 0.91%   |
| 1280x1024 (SXGA)  | 1         | 0.91%   |
| 1024x600          | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 63.72%  |
| 13      | 10        | 8.85%   |
| 17      | 6         | 5.31%   |
| 14      | 6         | 5.31%   |
| 12      | 5         | 4.42%   |
| 18      | 4         | 3.54%   |
| 10      | 2         | 1.77%   |
| 52      | 1         | 0.88%   |
| 37      | 1         | 0.88%   |
| 27      | 1         | 0.88%   |
| 24      | 1         | 0.88%   |
| 21      | 1         | 0.88%   |
| 19      | 1         | 0.88%   |
| 11      | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 85        | 75.89%  |
| 201-300     | 10        | 8.93%   |
| 351-400     | 7         | 6.25%   |
| 401-500     | 5         | 4.46%   |
| 501-600     | 2         | 1.79%   |
| 801-900     | 1         | 0.89%   |
| 1001-1500   | 1         | 0.89%   |
| Unknown     | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 97        | 91.51%  |
| 16/10   | 6         | 5.66%   |
| 5/4     | 1         | 0.94%   |
| 3/2     | 1         | 0.94%   |
| Unknown | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 63.72%  |
| 81-90          | 14        | 12.39%  |
| 61-70          | 5         | 4.42%   |
| 141-150        | 5         | 4.42%   |
| 121-130        | 3         | 2.65%   |
| 71-80          | 2         | 1.77%   |
| 41-50          | 2         | 1.77%   |
| 151-200        | 2         | 1.77%   |
| 131-140        | 2         | 1.77%   |
| More than 1000 | 1         | 0.88%   |
| 51-60          | 1         | 0.88%   |
| 301-350        | 1         | 0.88%   |
| 201-250        | 1         | 0.88%   |
| 501-1000       | 1         | 0.88%   |
| Unknown        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 69        | 61.61%  |
| 121-160 | 21        | 18.75%  |
| 51-100  | 16        | 14.29%  |
| 161-240 | 4         | 3.57%   |
| 1-50    | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 100       | 90.09%  |
| 2     | 9         | 8.11%   |
| 0     | 2         | 1.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 65        | 33.51%  |
| Intel                           | 38        | 19.59%  |
| Qualcomm Atheros                | 36        | 18.56%  |
| Broadcom                        | 26        | 13.4%   |
| Ralink Technology               | 7         | 3.61%   |
| Ralink                          | 6         | 3.09%   |
| Samsung Electronics             | 2         | 1.03%   |
| MediaTek                        | 2         | 1.03%   |
| Huawei Technologies             | 2         | 1.03%   |
| Broadcom Limited                | 2         | 1.03%   |
| Xiaomi                          | 1         | 0.52%   |
| Sierra Wireless                 | 1         | 0.52%   |
| Qualcomm Atheros Communications | 1         | 0.52%   |
| Nvidia                          | 1         | 0.52%   |
| Marvell Technology Group        | 1         | 0.52%   |
| LG Electronics                  | 1         | 0.52%   |
| Hewlett-Packard                 | 1         | 0.52%   |
| D-Link System                   | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 16.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 10.78%  |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 5.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 4.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.72%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.72%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.72%   |
| Intel Wireless 8260                                               | 4         | 1.72%   |
| Intel Wireless 7260                                               | 3         | 1.29%   |
| Intel Wireless 3160                                               | 3         | 1.29%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.29%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.29%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.29%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.86%   |
| Intel Wireless 7265                                               | 2         | 0.86%   |
| Intel WiFi Link 5100                                              | 2         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.86%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.86%   |
| Intel Centrino Wireless-N 135                                     | 2         | 0.86%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.86%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.86%   |
| Broadcom BCM43225 802.11b/g/n                                     | 2         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.43%   |
| Sierra Wireless EM7305                                            | 1         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.43%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.43%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.43%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.43%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.43%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.43%   |
| MediaTek moto e(6) plus                                           | 1         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 29.75%  |
| Qualcomm Atheros                | 32        | 26.45%  |
| Broadcom                        | 21        | 17.36%  |
| Realtek Semiconductor           | 13        | 10.74%  |
| Ralink Technology               | 7         | 5.79%   |
| Ralink                          | 6         | 4.96%   |
| Sierra Wireless                 | 1         | 0.83%   |
| Qualcomm Atheros Communications | 1         | 0.83%   |
| MediaTek                        | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |
| D-Link System                   | 1         | 0.83%   |
| Broadcom Limited                | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 12        | 9.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 8.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 8         | 6.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 4.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 4.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 3.31%   |
| Ralink MT7601U Wireless Adapter                                      | 4         | 3.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 3.31%   |
| Intel Wireless 8265 / 8275                                           | 4         | 3.31%   |
| Intel Wireless 8260                                                  | 4         | 3.31%   |
| Intel Wireless 7260                                                  | 3         | 2.48%   |
| Intel Wireless 3160                                                  | 3         | 2.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 2.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 1.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.65%   |
| Intel Wireless 7265                                                  | 2         | 1.65%   |
| Intel WiFi Link 5100                                                 | 2         | 1.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 1.65%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.65%   |
| Intel Centrino Wireless-N 135                                        | 2         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.65%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.65%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 1.65%   |
| Sierra Wireless EM7305                                               | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.83%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.83%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.83%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1         | 0.83%   |
| Intel Wireless 3165                                                  | 1         | 0.83%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.83%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 0.83%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 0.83%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                 | 1         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 0.83%   |
| HP lt4112 Gobi 4G Module Network Device                              | 1         | 0.83%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 0.83%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 1         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 0.83%   |
| Broadcom BCM43227 802.11b/g/n                                        | 1         | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 57.8%   |
| Intel                    | 22        | 20.18%  |
| Broadcom                 | 8         | 7.34%   |
| Qualcomm Atheros         | 7         | 6.42%   |
| Samsung Electronics      | 2         | 1.83%   |
| Xiaomi                   | 1         | 0.92%   |
| Nvidia                   | 1         | 0.92%   |
| MediaTek                 | 1         | 0.92%   |
| Marvell Technology Group | 1         | 0.92%   |
| LG Electronics           | 1         | 0.92%   |
| Huawei Technologies      | 1         | 0.92%   |
| Broadcom Limited         | 1         | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 34.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 22.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 3.64%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.73%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 2.73%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.91%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.91%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.91%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.91%   |
| MediaTek moto e(6) plus                                           | 1         | 0.91%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.91%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.91%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.91%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.91%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.91%   |
| Huawei E353/E3131                                                 | 1         | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.91%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.91%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.91%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 51.17%  |
| Ethernet | 103       | 48.36%  |
| Modem    | 1         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 85.19%  |
| Ethernet | 16        | 14.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 103       | 91.96%  |
| 1     | 6         | 5.36%   |
| 0     | 3         | 2.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 27.85%  |
| Qualcomm Atheros Communications | 11        | 13.92%  |
| Broadcom                        | 9         | 11.39%  |
| Realtek Semiconductor           | 7         | 8.86%   |
| Lite-On Technology              | 5         | 6.33%   |
| Foxconn / Hon Hai               | 5         | 6.33%   |
| Ralink                          | 4         | 5.06%   |
| Dell                            | 4         | 5.06%   |
| IMC Networks                    | 3         | 3.8%    |
| Foxconn International           | 3         | 3.8%    |
| Apple                           | 2         | 2.53%   |
| Toshiba                         | 1         | 1.27%   |
| Ralink Technology               | 1         | 1.27%   |
| Chicony Electronics             | 1         | 1.27%   |
| Alps Electric                   | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 16        | 20.25%  |
| Qualcomm Atheros  Bluetooth Device                | 5         | 6.33%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 5         | 6.33%   |
| Ralink RT3290 Bluetooth                           | 4         | 5.06%   |
| Realtek Bluetooth Radio                           | 3         | 3.8%    |
| Qualcomm Atheros AR3011 Bluetooth                 | 3         | 3.8%    |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 3.8%    |
| Broadcom BCM43142 Bluetooth 4.0                   | 3         | 3.8%    |
| Realtek RTL8723B Bluetooth                        | 2         | 2.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 2.53%   |
| IMC Networks Bluetooth Device                     | 2         | 2.53%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 2.53%   |
| Dell Wireless 365 Bluetooth                       | 2         | 2.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 2         | 2.53%   |
| Apple Bluetooth Host Controller                   | 2         | 2.53%   |
| Toshiba Bluetooth Device                          | 1         | 1.27%   |
| Realtek RTL8821A Bluetooth                        | 1         | 1.27%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.27%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.27%   |
| Qualcomm Atheros Bluetooth                        | 1         | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.27%   |
| Lite-On Wireless_Device                           | 1         | 1.27%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]       | 1         | 1.27%   |
| Lite-On BCM43142A0                                | 1         | 1.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 1         | 1.27%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 1.27%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 1.27%   |
| Foxconn / Hon Hai BCM43142A0                      | 1         | 1.27%   |
| Foxconn / Hon Hai Acer Module                     | 1         | 1.27%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.27%   |
| Dell BCM20702A0 Bluetooth Module                  | 1         | 1.27%   |
| Chicony Bluetooth (RTL8723BE)                     | 1         | 1.27%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 1.27%   |
| Broadcom Bluetooth Device                         | 1         | 1.27%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 1         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 1.27%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 101       | 84.17%  |
| AMD               | 13        | 10.83%  |
| Nvidia            | 5         | 4.17%   |
| Texas Instruments | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 16.44%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 13.01%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 8.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 7.53%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 7.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.11%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 4.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.37%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.37%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.37%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.37%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.37%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.37%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.68%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.68%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.68%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.68%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.68%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 30%     |
| SK hynix            | 17        | 28.33%  |
| Micron Technology   | 9         | 15%     |
| Unknown             | 6         | 10%     |
| Kingston            | 3         | 5%      |
| Team                | 1         | 1.67%   |
| Ramaxel Technology  | 1         | 1.67%   |
| Nanya Technology    | 1         | 1.67%   |
| Elpida              | 1         | 1.67%   |
| Crucial             | 1         | 1.67%   |
| ASint Technology    | 1         | 1.67%   |
| A-DATA Technology   | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 6.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 4.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 4.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 2         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s    | 2         | 3.03%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.52%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 1.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 1.52%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.52%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 1.52%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s            | 1         | 1.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.52%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s   | 1         | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s   | 1         | 1.52%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 1.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 1.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 1         | 1.52%   |
| SK hynix RAM HMA425S6BJR6N-UH 2GB SODIMM DDR4 2667MT/s      | 1         | 1.52%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s              | 1         | 1.52%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.52%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s    | 1         | 1.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s       | 1         | 1.52%   |
| Ramaxel RAM RMT1970ED48E8F1333 2GB SODIMM DDR3 1333MT/s     | 1         | 1.52%   |
| Nanya RAM M2S4G64CC88B4N-DI 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Micron RAM MT41K512M8RH-125:E 4GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s       | 1         | 1.52%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Micron RAM 16JTF1G64HZ-1G6D1 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s      | 1         | 1.52%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Kingston RAM ACR256X64D3S1333C9 2048MB SODIMM DDR3 1334MT/s | 1         | 1.52%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s     | 1         | 1.52%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s       | 1         | 1.52%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s     | 1         | 1.52%   |
| ASint RAM C1RE5SR4HN1 2GB SODIMM SDRAM 4199MT/s             | 1         | 1.52%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2400MT/s              | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 37        | 74%     |
| DDR4   | 11        | 22%     |
| SDRAM  | 1         | 2%      |
| LPDDR4 | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 49        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 28        | 48.28%  |
| 8192  | 14        | 24.14%  |
| 2048  | 14        | 24.14%  |
| 32768 | 1         | 1.72%   |
| 16384 | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 50.94%  |
| 2667    | 8         | 15.09%  |
| 1334    | 5         | 9.43%   |
| 1333    | 3         | 5.66%   |
| 3266    | 2         | 3.77%   |
| 2400    | 2         | 3.77%   |
| Unknown | 2         | 3.77%   |
| 4199    | 1         | 1.89%   |
| 3200    | 1         | 1.89%   |
| 2133    | 1         | 1.89%   |
| 1067    | 1         | 1.89%   |

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


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-202 203 206 Series | 1         | 33.33%  |
| Canon LBP6020                     | 1         | 33.33%  |
| Canon LBP2900                     | 1         | 33.33%  |

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
| Chicony Electronics                    | 24        | 24.24%  |
| Microdia                               | 15        | 15.15%  |
| Realtek Semiconductor                  | 9         | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 9.09%   |
| Acer                                   | 8         | 8.08%   |
| Sunplus Innovation Technology          | 7         | 7.07%   |
| Suyin                                  | 5         | 5.05%   |
| Syntek                                 | 4         | 4.04%   |
| IMC Networks                           | 3         | 3.03%   |
| Apple                                  | 3         | 3.03%   |
| Silicon Motion                         | 2         | 2.02%   |
| Quanta                                 | 2         | 2.02%   |
| Lite-On Technology                     | 2         | 2.02%   |
| Samsung Electronics                    | 1         | 1.01%   |
| Primax Electronics                     | 1         | 1.01%   |
| Pixart Imaging                         | 1         | 1.01%   |
| Aveo Technology                        | 1         | 1.01%   |
| ALi                                    | 1         | 1.01%   |
| Alcor Micro                            | 1         | 1.01%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Acer Lenovo EasyCamera                                                | 6         | 6.06%   |
| Chicony TOSHIBA Web Camera - HD                                       | 4         | 4.04%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                | 3         | 3.03%   |
| Microdia Integrated_Webcam_HD                                         | 3         | 3.03%   |
| Microdia Integrated Webcam                                            | 3         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                   | 3         | 3.03%   |
| Syntek Lenovo EasyCamera                                              | 2         | 2.02%   |
| Suyin HP Truevision HD                                                | 2         | 2.02%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                  | 2         | 2.02%   |
| Sunplus Integrated_Webcam_HD                                          | 2         | 2.02%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 2         | 2.02%   |
| Chicony Integrated Camera                                             | 2         | 2.02%   |
| Chicony HD WebCam                                                     | 2         | 2.02%   |
| Chicony Acer CrystalEye Webcam                                        | 2         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                         | 2         | 2.02%   |
| Apple iPhone 5/5C/5S/6/SE                                             | 2         | 2.02%   |
| Syntek USB2.0 Camera                                                  | 1         | 1.01%   |
| Syntek EasyCamera                                                     | 1         | 1.01%   |
| Suyin WebCam                                                          | 1         | 1.01%   |
| Suyin Integrated_Webcam_HD                                            | 1         | 1.01%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                              | 1         | 1.01%   |
| Sunplus Laptop Integrated Webcam HD                                   | 1         | 1.01%   |
| Sunplus HP HD Webcam [Fixed]                                          | 1         | 1.01%   |
| Sunplus Dell HD Webcam                                                | 1         | 1.01%   |
| Silicon Motion WebCam SC-13HDL11431N                                  | 1         | 1.01%   |
| Silicon Motion WebCam SC-0311139N                                     | 1         | 1.01%   |
| Samsung Galaxy A5 (MTP)                                               | 1         | 1.01%   |
| Realtek USB2.0 VGA UVC WebCam                                         | 1         | 1.01%   |
| Realtek USB Camera                                                    | 1         | 1.01%   |
| Realtek Lenovo EasyCamera                                             | 1         | 1.01%   |
| Realtek Integrated Webcam_HD                                          | 1         | 1.01%   |
| Realtek Integrated Webcam                                             | 1         | 1.01%   |
| Realtek HP Webcam                                                     | 1         | 1.01%   |
| Realtek HP Truevision HD                                              | 1         | 1.01%   |
| Realtek HD Webcam - Realtek                                           | 1         | 1.01%   |
| Realtek Acer 640 x 480 laptop camera                                  | 1         | 1.01%   |
| Quanta HD Webcam                                                      | 1         | 1.01%   |
| Quanta HD User Facing                                                 | 1         | 1.01%   |
| Primax webcam                                                         | 1         | 1.01%   |
| Pixart Imaging VGA Webcam                                             | 1         | 1.01%   |
| Microdia Sony Visual Communication Camera                             | 1         | 1.01%   |
| Microdia Laptop_Integrated_Webcam_HD                                  | 1         | 1.01%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.01%   |
| Microdia Laptop_Integrated_Webcam_2M                                  | 1         | 1.01%   |
| Microdia Integrated Webcam HD                                         | 1         | 1.01%   |
| Microdia 1.3 MPixel Integrated Webcam                                 | 1         | 1.01%   |
| Lite-On TOSHIBA Web Camera - HD                                       | 1         | 1.01%   |
| Lite-On Integrated Camera                                             | 1         | 1.01%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 1.01%   |
| IMC Networks Lenovo EasyCamera                                        | 1         | 1.01%   |
| IMC Networks Integrated Webcam                                        | 1         | 1.01%   |
| Chicony WebCam                                                        | 1         | 1.01%   |
| Chicony UVC 1.00 device HD UVC WebCam                                 | 1         | 1.01%   |
| Chicony USB2.0 HD UVC WebCam                                          | 1         | 1.01%   |
| Chicony Sony Visual Communication Camera                              | 1         | 1.01%   |
| Chicony Lenovo EasyCamera                                             | 1         | 1.01%   |
| Chicony HP Webcam                                                     | 1         | 1.01%   |
| Chicony HP Truevision HD                                              | 1         | 1.01%   |
| Chicony HP HD Webcam [Fixed]                                          | 1         | 1.01%   |
| Chicony HP HD Camera                                                  | 1         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 9         | 75%     |
| AuthenTec        | 2         | 16.67%  |
| Synaptics        | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 33.33%  |
| Validity Sensors VFS491                                    | 2         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 8.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| AuthenTec AES2810                                          | 1         | 8.33%   |
| AuthenTec AES1600                                          | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 7         | 87.5%   |
| OmniKey  | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 37.5%   |
| Broadcom 5880                                                                | 3         | 37.5%   |
| OmniKey CardMan 4321                                                         | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 72        | 64.86%  |
| 1     | 34        | 30.63%  |
| 2     | 4         | 3.6%    |
| 3     | 1         | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 12        | 26.09%  |
| Net/wireless       | 10        | 21.74%  |
| Chipcard           | 8         | 17.39%  |
| Graphics card      | 7         | 15.22%  |
| Bluetooth          | 4         | 8.7%    |
| Storage            | 2         | 4.35%   |
| Net/ethernet       | 2         | 4.35%   |
| Card reader        | 1         | 2.17%   |

