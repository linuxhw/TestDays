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

Total: 175

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 32        | 26.23%  |
| Ubuntu 18.04        | 13        | 10.66%  |
| OpenMandriva 4.2    | 9         | 7.38%   |
| Linux Mint 20.1     | 6         | 4.92%   |
| KDE neon 20.04      | 5         | 4.1%    |
| Pop!_OS 20.04       | 4         | 3.28%   |
| Xubuntu 20.04       | 3         | 2.46%   |
| Fedora 35           | 3         | 2.46%   |
| ArcoLinux Rolling   | 3         | 2.46%   |
| Arch                | 3         | 2.46%   |
| Ubuntu 20.10        | 2         | 1.64%   |
| Ubuntu 19.10        | 2         | 1.64%   |
| Ubuntu 16.04        | 2         | 1.64%   |
| ROSA R11            | 2         | 1.64%   |
| Manjaro             | 2         | 1.64%   |
| Kubuntu 20.04       | 2         | 1.64%   |
| Kali 2021.1         | 2         | 1.64%   |
| BlackPanther 18.1   | 2         | 1.64%   |
| Zorin 16            | 1         | 0.82%   |
| UbuntuDDE 20.04     | 1         | 0.82%   |
| Ubuntu Budgie 22.04 | 1         | 0.82%   |
| Ubuntu 22.04        | 1         | 0.82%   |
| Ubuntu 21.10        | 1         | 0.82%   |
| Ubuntu 21.04        | 1         | 0.82%   |
| ROSA R8.1           | 1         | 0.82%   |
| ROSA R10            | 1         | 0.82%   |
| Pop!_OS 21.04       | 1         | 0.82%   |
| Pear OS 20.04       | 1         | 0.82%   |
| Parrot 5.0          | 1         | 0.82%   |
| OpenMandriva 4.50   | 1         | 0.82%   |
| MX 19               | 1         | 0.82%   |
| Manjaro 20.1        | 1         | 0.82%   |
| Linux Mint 20.2     | 1         | 0.82%   |
| Linux Mint 20       | 1         | 0.82%   |
| Kali 2021.2         | 1         | 0.82%   |
| Fedora 31           | 1         | 0.82%   |
| Fedora 29           | 1         | 0.82%   |
| Debian 11           | 1         | 0.82%   |
| Debian 10           | 1         | 0.82%   |
| Clear Linux 34640   | 1         | 0.82%   |
| CentOS 7            | 1         | 0.82%   |
| Artix Rolling       | 1         | 0.82%   |
| ArchLabs 2020.11.04 | 1         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 53        | 44.17%  |
| OpenMandriva  | 10        | 8.33%   |
| Linux Mint    | 8         | 6.67%   |
| Pop!_OS       | 5         | 4.17%   |
| KDE neon      | 5         | 4.17%   |
| Fedora        | 5         | 4.17%   |
| Xubuntu       | 3         | 2.5%    |
| ROSA          | 3         | 2.5%    |
| Manjaro       | 3         | 2.5%    |
| Kali          | 3         | 2.5%    |
| ArcoLinux     | 3         | 2.5%    |
| Arch          | 3         | 2.5%    |
| Kubuntu       | 2         | 1.67%   |
| Debian        | 2         | 1.67%   |
| BlackPanther  | 2         | 1.67%   |
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
| 5.10.14-desktop-1omv4002 | 9         | 7.03%   |
| 5.4.0-72-generic         | 4         | 3.13%   |
| 5.4.0-42-generic         | 4         | 3.13%   |
| 5.4.0-29-generic         | 4         | 3.13%   |
| 5.4.0-54-generic         | 3         | 2.34%   |
| 5.13.0-30-generic        | 3         | 2.34%   |
| 5.8.0-50-generic         | 2         | 1.56%   |
| 5.8.0-44-generic         | 2         | 1.56%   |
| 5.4.0-80-generic         | 2         | 1.56%   |
| 5.4.0-7625-generic       | 2         | 1.56%   |
| 5.4.0-65-generic         | 2         | 1.56%   |
| 5.4.0-56-generic         | 2         | 1.56%   |
| 5.4.0-52-generic         | 2         | 1.56%   |
| 5.4.0-48-generic         | 2         | 1.56%   |
| 5.4.0-33-generic         | 2         | 1.56%   |
| 5.3.0-40-generic         | 2         | 1.56%   |
| 5.11.0-27-generic        | 2         | 1.56%   |
| 5.11.0-25-generic        | 2         | 1.56%   |
| 4.18.16-desktop-1bP      | 2         | 1.56%   |
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
| 5.13.2-051302-generic    | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 28.33%  |
| 5.8.0   | 9         | 7.5%    |
| 5.10.14 | 9         | 7.5%    |
| 5.3.0   | 7         | 5.83%   |
| 5.11.0  | 7         | 5.83%   |
| 5.13.0  | 6         | 5%      |
| 4.15.0  | 5         | 4.17%   |
| 5.0.0   | 4         | 3.33%   |
| 5.15.0  | 3         | 2.5%    |
| 5.10.0  | 3         | 2.5%    |
| 4.18.16 | 3         | 2.5%    |
| 5.15.7  | 2         | 1.67%   |
| 4.4.0   | 2         | 1.67%   |
| 5.9.11  | 1         | 0.83%   |
| 5.7.17  | 1         | 0.83%   |
| 5.7.0   | 1         | 0.83%   |
| 5.6.0   | 1         | 0.83%   |
| 5.4.72  | 1         | 0.83%   |
| 5.4.15  | 1         | 0.83%   |
| 5.17.4  | 1         | 0.83%   |
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
| 5.4     | 36        | 30%     |
| 5.10    | 14        | 11.67%  |
| 5.8     | 9         | 7.5%    |
| 5.15    | 9         | 7.5%    |
| 5.11    | 8         | 6.67%   |
| 5.3     | 7         | 5.83%   |
| 5.13    | 7         | 5.83%   |
| 4.15    | 5         | 4.17%   |
| 5.0     | 4         | 3.33%   |
| 4.18    | 4         | 3.33%   |
| 5.12    | 3         | 2.5%    |
| 5.7     | 2         | 1.67%   |
| 4.9     | 2         | 1.67%   |
| 4.4     | 2         | 1.67%   |
| 4.19    | 2         | 1.67%   |
| 5.9     | 1         | 0.83%   |
| 5.6     | 1         | 0.83%   |
| 5.17    | 1         | 0.83%   |
| 5.16    | 1         | 0.83%   |
| 5.14    | 1         | 0.83%   |
| 3.10    | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 98.17%  |
| i686   | 2         | 1.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 57        | 49.14%  |
| KDE5       | 18        | 15.52%  |
| Unknown    | 13        | 11.21%  |
| XFCE       | 9         | 7.76%   |
| X-Cinnamon | 4         | 3.45%   |
| KDE        | 4         | 3.45%   |
| MATE       | 3         | 2.59%   |
| KDE4       | 2         | 1.72%   |
| Unity      | 1         | 0.86%   |
| LXQt       | 1         | 0.86%   |
| i3         | 1         | 0.86%   |
| Deepin     | 1         | 0.86%   |
| Cinnamon   | 1         | 0.86%   |
| Budgie     | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 97        | 87.39%  |
| Wayland | 7         | 6.31%   |
| Unknown | 6         | 5.41%   |
| Tty     | 1         | 0.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 68        | 59.13%  |
| SDDM    | 15        | 13.04%  |
| GDM     | 15        | 13.04%  |
| LightDM | 9         | 7.83%   |
| TDM     | 4         | 3.48%   |
| KDM     | 2         | 1.74%   |
| SLiM    | 1         | 0.87%   |
| GDM3    | 1         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 52        | 46.85%  |
| fr_FR   | 33        | 29.73%  |
| Unknown | 13        | 11.71%  |
| en_GB   | 4         | 3.6%    |
| C       | 4         | 3.6%    |
| ar_DZ   | 2         | 1.8%    |
| fr_DZ   | 1         | 0.9%    |
| fr_BE   | 1         | 0.9%    |
| ar_EG   | 1         | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 76        | 67.26%  |
| EFI  | 37        | 32.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 76.32%  |
| Overlay | 12        | 10.53%  |
| Btrfs   | 6         | 5.26%   |
| Unknown | 4         | 3.51%   |
| Ext2    | 3         | 2.63%   |
| Xfs     | 1         | 0.88%   |
| Ext3    | 1         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 67.86%  |
| MBR     | 19        | 16.96%  |
| GPT     | 17        | 15.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 84.07%  |
| Yes       | 18        | 15.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 51.35%  |
| No        | 54        | 48.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 26        | 23.85%  |
| Hewlett-Packard     | 22        | 20.18%  |
| Lenovo              | 17        | 15.6%   |
| Acer                | 10        | 9.17%   |
| Toshiba             | 8         | 7.34%   |
| ASUSTek Computer    | 8         | 7.34%   |
| Sony                | 6         | 5.5%    |
| Packard Bell        | 3         | 2.75%   |
| Samsung Electronics | 2         | 1.83%   |
| Fujitsu             | 2         | 1.83%   |
| Apple               | 2         | 1.83%   |
| MSI                 | 1         | 0.92%   |
| LDLC                | 1         | 0.92%   |
| eMachines           | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba Satellite C55-B             | 2         | 1.83%   |
| Lenovo IdeaPad 300-15ISK 80Q7       | 2         | 1.83%   |
| Lenovo G560 20042                   | 2         | 1.83%   |
| Lenovo G50-30 80G0                  | 2         | 1.83%   |
| Lenovo B50-70 20384                 | 2         | 1.83%   |
| HP ProBook 4540s                    | 2         | 1.83%   |
| HP Pavilion 15                      | 2         | 1.83%   |
| HP 15                               | 2         | 1.83%   |
| Dell Latitude E7440                 | 2         | 1.83%   |
| Dell Latitude E5430 vPro            | 2         | 1.83%   |
| Dell Inspiron N5110                 | 2         | 1.83%   |
| Dell Inspiron 3542                  | 2         | 1.83%   |
| Dell Inspiron 15-3567               | 2         | 1.83%   |
| Acer Aspire 5738                    | 2         | 1.83%   |
| Toshiba Satellite C850-A979         | 1         | 0.92%   |
| Toshiba Satellite C50-A560          | 1         | 0.92%   |
| Toshiba Satellite C50-A545          | 1         | 0.92%   |
| Toshiba Satellite C50-A539          | 1         | 0.92%   |
| Toshiba PORTEGE R30-A               | 1         | 0.92%   |
| Toshiba PORTEGE M780                | 1         | 0.92%   |
| Sony VPCEJ2S1E                      | 1         | 0.92%   |
| Sony VPCEH2H1E                      | 1         | 0.92%   |
| Sony VGN-AW21M_H                    | 1         | 0.92%   |
| Sony SVF1531GSFB                    | 1         | 0.92%   |
| Sony SVE1713A6EW                    | 1         | 0.92%   |
| Sony SVE1513K1EW                    | 1         | 0.92%   |
| Samsung N102SP/N100SP/N101SP        | 1         | 0.92%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B | 1         | 0.92%   |
| Packard Bell EasyNote TJ75          | 1         | 0.92%   |
| Packard Bell EasyNote LJ71          | 1         | 0.92%   |
| Packard Bell DOT S                  | 1         | 0.92%   |
| MSI CR610M                          | 1         | 0.92%   |
| Lenovo ThinkPad X260 20F5S1G104     | 1         | 0.92%   |
| Lenovo ThinkPad X201 3680AQ1        | 1         | 0.92%   |
| Lenovo ThinkPad T450 20BUS2RN1H     | 1         | 0.92%   |
| Lenovo ThinkPad T440 20B6S00200     | 1         | 0.92%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 0.92%   |
| Lenovo IdeaPad 310-15IKB 80TV       | 1         | 0.92%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 0.92%   |
| Lenovo G580 2189                    | 1         | 0.92%   |
| Lenovo G500 20236                   | 1         | 0.92%   |
| LDLC Mercure MH                     | 1         | 0.92%   |
| HP ZBook 15 G4                      | 1         | 0.92%   |
| HP ProBook 650 G1                   | 1         | 0.92%   |
| HP ProBook 4720s                    | 1         | 0.92%   |
| HP ProBook 450 G6                   | 1         | 0.92%   |
| HP ProBook 450 G3                   | 1         | 0.92%   |
| HP ProBook 450 G2                   | 1         | 0.92%   |
| HP ProBook 450 G0                   | 1         | 0.92%   |
| HP Pavilion Notebook                | 1         | 0.92%   |
| HP Notebook                         | 1         | 0.92%   |
| HP Laptop 15-bw0xx                  | 1         | 0.92%   |
| HP ElitePad 1000 G2                 | 1         | 0.92%   |
| HP EliteBook Folio 9470m            | 1         | 0.92%   |
| HP EliteBook 840 G3                 | 1         | 0.92%   |
| HP EliteBook 820 G3                 | 1         | 0.92%   |
| HP 630                              | 1         | 0.92%   |
| HP 250 G4                           | 1         | 0.92%   |
| Fujitsu LIFEBOOK AH532/G21          | 1         | 0.92%   |
| Fujitsu LIFEBOOK A532               | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 12        | 11.01%  |
| Dell Latitude         | 10        | 9.17%   |
| HP ProBook            | 8         | 7.34%   |
| Acer Aspire           | 8         | 7.34%   |
| Toshiba Satellite     | 6         | 5.5%    |
| Lenovo IdeaPad        | 5         | 4.59%   |
| Lenovo ThinkPad       | 4         | 3.67%   |
| HP Pavilion           | 3         | 2.75%   |
| HP EliteBook          | 3         | 2.75%   |
| Toshiba PORTEGE       | 2         | 1.83%   |
| Packard Bell EasyNote | 2         | 1.83%   |
| Lenovo G560           | 2         | 1.83%   |
| Lenovo G50-30         | 2         | 1.83%   |
| Lenovo B50-70         | 2         | 1.83%   |
| HP 15                 | 2         | 1.83%   |
| Fujitsu LIFEBOOK      | 2         | 1.83%   |
| Dell Precision        | 2         | 1.83%   |
| Acer Extensa          | 2         | 1.83%   |
| Sony VPCEJ2S1E        | 1         | 0.92%   |
| Sony VPCEH2H1E        | 1         | 0.92%   |
| Sony VGN-AW21M        | 1         | 0.92%   |
| Sony SVF1531GSFB      | 1         | 0.92%   |
| Sony SVE1713A6EW      | 1         | 0.92%   |
| Sony SVE1513K1EW      | 1         | 0.92%   |
| Samsung N102SP        | 1         | 0.92%   |
| Samsung 700Z3A        | 1         | 0.92%   |
| Packard Bell DOT      | 1         | 0.92%   |
| MSI CR610M            | 1         | 0.92%   |
| Lenovo G580           | 1         | 0.92%   |
| Lenovo G500           | 1         | 0.92%   |
| LDLC Mercure          | 1         | 0.92%   |
| HP ZBook              | 1         | 0.92%   |
| HP Notebook           | 1         | 0.92%   |
| HP Laptop             | 1         | 0.92%   |
| HP ElitePad           | 1         | 0.92%   |
| HP 630                | 1         | 0.92%   |
| HP 250                | 1         | 0.92%   |
| eMachines eME732      | 1         | 0.92%   |
| Dell XPS              | 1         | 0.92%   |
| Dell Vostro           | 1         | 0.92%   |
| ASUS X55U             | 1         | 0.92%   |
| ASUS X555LAB          | 1         | 0.92%   |
| ASUS X551CA           | 1         | 0.92%   |
| ASUS X541UV           | 1         | 0.92%   |
| ASUS X540SA           | 1         | 0.92%   |
| ASUS X205TAW          | 1         | 0.92%   |
| ASUS K50IE            | 1         | 0.92%   |
| ASUS GL753VD          | 1         | 0.92%   |
| Apple MacBookPro8     | 1         | 0.92%   |
| Apple MacBook7        | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 19        | 17.43%  |
| 2012 | 19        | 17.43%  |
| 2013 | 14        | 12.84%  |
| 2016 | 10        | 9.17%   |
| 2017 | 9         | 8.26%   |
| 2015 | 9         | 8.26%   |
| 2010 | 8         | 7.34%   |
| 2011 | 7         | 6.42%   |
| 2009 | 7         | 6.42%   |
| 2018 | 5         | 4.59%   |
| 2021 | 1         | 0.92%   |
| 2008 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 109       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 108       | 99.08%  |
| Enabled  | 1         | 0.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 47        | 43.12%  |
| 4.01-8.0   | 30        | 27.52%  |
| 8.01-16.0  | 19        | 17.43%  |
| 1.01-2.0   | 6         | 5.5%    |
| 16.01-24.0 | 3         | 2.75%   |
| 32.01-64.0 | 2         | 1.83%   |
| 2.01-3.0   | 2         | 1.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 63        | 51.22%  |
| 2.01-3.0  | 35        | 28.46%  |
| 3.01-4.0  | 13        | 10.57%  |
| 0.51-1.0  | 7         | 5.69%   |
| 4.01-8.0  | 4         | 3.25%   |
| 8.01-16.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 74.55%  |
| 2      | 26        | 23.64%  |
| 4      | 1         | 0.91%   |
| 0      | 1         | 0.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 70.64%  |
| No        | 32        | 29.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 93.58%  |
| No        | 7         | 6.42%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 98.18%  |
| No        | 2         | 1.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 71.17%  |
| No        | 32        | 28.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Algeria | 109       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Algiers              | 19        | 15.2%   |
| Tlemcen              | 7         | 5.6%    |
| Belcourt             | 6         | 4.8%    |
| Oran                 | 5         | 4%      |
| Skikda               | 4         | 3.2%    |
| Relizane             | 4         | 3.2%    |
| Cheraga              | 4         | 3.2%    |
| Birkhadem            | 4         | 3.2%    |
| Sétif               | 3         | 2.4%    |
| Laghouat             | 3         | 2.4%    |
| Blida                | 3         | 2.4%    |
| Béjaïa             | 3         | 2.4%    |
| ash-Shalif           | 3         | 2.4%    |
| Tizi Ouzou           | 2         | 1.6%    |
| Tipasa               | 2         | 1.6%    |
| Saida                | 2         | 1.6%    |
| Kouba                | 2         | 1.6%    |
| Djelfa               | 2         | 1.6%    |
| Constantine          | 2         | 1.6%    |
| Biskra               | 2         | 1.6%    |
| Bir el Djir          | 2         | 1.6%    |
| Annaba               | 2         | 1.6%    |
| Ain Fakroun          | 2         | 1.6%    |
| Tolga                | 1         | 0.8%    |
| Tichi                | 1         | 0.8%    |
| Tazoult-Lambese      | 1         | 0.8%    |
| Souma                | 1         | 0.8%    |
| Sidi Kada            | 1         | 0.8%    |
| Sidi Bel Abbes       | 1         | 0.8%    |
| Saoula               | 1         | 0.8%    |
| Reguiba              | 1         | 0.8%    |
| Ouenza               | 1         | 0.8%    |
| M'Sila               | 1         | 0.8%    |
| Larbaâ              | 1         | 0.8%    |
| Jijelli              | 1         | 0.8%    |
| El Oued              | 1         | 0.8%    |
| El Khroub            | 1         | 0.8%    |
| El Eulma             | 1         | 0.8%    |
| El Aouinet           | 1         | 0.8%    |
| Dunqulah             | 1         | 0.8%    |
| Draria               | 1         | 0.8%    |
| Debila               | 1         | 0.8%    |
| Brezina              | 1         | 0.8%    |
| BouГЇra            | 1         | 0.8%    |
| Boumerdes            | 1         | 0.8%    |
| Boudouaou            | 1         | 0.8%    |
| Bordj el Kiffan      | 1         | 0.8%    |
| Berhoum              | 1         | 0.8%    |
| Ben ’Aknoûn       | 1         | 0.8%    |
| Ben вЂ™AknoГ»n | 1         | 0.8%    |
| Batna City           | 1         | 0.8%    |
| Baba Hassen          | 1         | 0.8%    |
| Bab Ezzouar          | 1         | 0.8%    |
| Aomar                | 1         | 0.8%    |
| Ain Taya             | 1         | 0.8%    |
| Ain Oussera          | 1         | 0.8%    |
| Ain el Bya           | 1         | 0.8%    |
| Ain Bessem           | 1         | 0.8%    |
| Ain Beida            | 1         | 0.8%    |
| Aflou                | 1         | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 24        | 32     | 18.75%  |
| Toshiba               | 21        | 22     | 16.41%  |
| WDC                   | 20        | 24     | 15.63%  |
| HGST                  | 13        | 17     | 10.16%  |
| Hitachi               | 12        | 14     | 9.38%   |
| Samsung Electronics   | 7         | 7      | 5.47%   |
| A-DATA Technology     | 5         | 5      | 3.91%   |
| Unknown               | 4         | 5      | 3.13%   |
| Lexar                 | 4         | 4      | 3.13%   |
| SanDisk               | 3         | 3      | 2.34%   |
| LITEON                | 3         | 6      | 2.34%   |
| SK hynix              | 2         | 2      | 1.56%   |
| Intel                 | 2         | 2      | 1.56%   |
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
| Toshiba MQ01ABF050 500GB              | 8         | 6.11%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 3.05%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 3         | 2.29%   |
| Toshiba MQ01ABD100 1TB                | 3         | 2.29%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 2.29%   |
| Seagate Expansion 1TB                 | 3         | 2.29%   |
| HGST HTS545050A7E680 500GB            | 3         | 2.29%   |
| HGST HTS545050A7E380 500GB            | 3         | 2.29%   |
| Unknown MMC Card  64GB                | 2         | 1.53%   |
| Seagate ST500VT000-1DK142 500GB       | 2         | 1.53%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 1.53%   |
| Seagate ST320LT020-9YG142 320GB       | 2         | 1.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 1.53%   |
| Lexar 512GB SSD                       | 2         | 1.53%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 1.53%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 1.53%   |
| HGST HTS725050A7E630 500GB            | 2         | 1.53%   |
| HGST HTS541010A9E680 1TB              | 2         | 1.53%   |
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
| SanDisk SSD U110 16GB                 | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 32     | 26.67%  |
| Toshiba             | 21        | 22     | 23.33%  |
| WDC                 | 18        | 21     | 20%     |
| HGST                | 13        | 17     | 14.44%  |
| Hitachi             | 12        | 14     | 13.33%  |
| Samsung Electronics | 1         | 1      | 1.11%   |
| Fujitsu             | 1         | 2      | 1.11%   |

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
| HDD     | 86        | 109    | 71.07%  |
| SSD     | 24        | 29     | 19.83%  |
| NVMe    | 6         | 8      | 4.96%   |
| MMC     | 4         | 6      | 3.31%   |
| Unknown | 1         | 1      | 0.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 134    | 86.96%  |
| NVMe | 6         | 8      | 5.22%   |
| SAS  | 5         | 5      | 4.35%   |
| MMC  | 4         | 6      | 3.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 106    | 72.07%  |
| 0.51-1.0   | 30        | 31     | 27.03%  |
| 1.01-2.0   | 1         | 1      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 34        | 29.31%  |
| 51-100     | 22        | 18.97%  |
| 101-250    | 17        | 14.66%  |
| 501-1000   | 15        | 12.93%  |
| 21-50      | 11        | 9.48%   |
| 1-20       | 10        | 8.62%   |
| 1001-2000  | 5         | 4.31%   |
| Unknown    | 2         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 59        | 48.36%  |
| 21-50    | 21        | 17.21%  |
| 101-250  | 18        | 14.75%  |
| 51-100   | 11        | 9.02%   |
| 251-500  | 7         | 5.74%   |
| 501-1000 | 4         | 3.28%   |
| Unknown  | 2         | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 8.33%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 8.33%   |
| Samsung Electronics HM320HJ 320GB | 1         | 1      | 8.33%   |
| Hitachi HTS723225L9A360 250GB     | 1         | 1      | 8.33%   |
| Hitachi HTS547564A9E384 640GB     | 1         | 1      | 8.33%   |
| Hitachi HTS542516K9SA00 160GB     | 1         | 1      | 8.33%   |
| HGST HTS725050A7E630 500GB        | 1         | 3      | 8.33%   |
| HGST HTS545050A7E680 500GB        | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 25%     |
| Hitachi             | 3         | 3      | 25%     |
| Toshiba             | 2         | 2      | 16.67%  |
| HGST                | 2         | 4      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 25%     |
| Hitachi             | 3         | 3      | 25%     |
| Toshiba             | 2         | 2      | 16.67%  |
| HGST                | 2         | 4      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 14     | 100%    |

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
| Detected | 76        | 107    | 67.26%  |
| Works    | 25        | 32     | 22.12%  |
| Malfunc  | 12        | 14     | 10.62%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 99        | 87.61%  |
| AMD                   | 5         | 4.42%   |
| Samsung Electronics   | 4         | 3.54%   |
| Nvidia                | 2         | 1.77%   |
| Silicon Motion        | 1         | 0.88%   |
| Realtek Semiconductor | 1         | 0.88%   |
| Micron Technology     | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 18.1%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 13.79%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 9.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 6.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 5.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 5.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 3.45%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.72%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                            | 2         | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.86%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.86%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.86%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.86%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.86%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.86%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.86%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 91        | 79.82%  |
| RAID | 12        | 10.53%  |
| NVMe | 6         | 5.26%   |
| IDE  | 5         | 4.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 104       | 95.41%  |
| AMD    | 5         | 4.59%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-3217U CPU @ 1.80GHz           | 5         | 4.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 3.67%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 4         | 3.67%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 2.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 2.75%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 2.75%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.83%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.83%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.83%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.83%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.83%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.83%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.83%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.83%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.83%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.83%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.83%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.92%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.92%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.92%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.92%   |
| Intel Pentium 3805U @ 1.90GHz               | 1         | 0.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.92%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.92%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.92%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.92%   |
| Intel Core i7-2675QM CPU @ 2.20GHz          | 1         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.92%   |
| Intel Core i5-6198DU CPU @ 2.30GHz          | 1         | 0.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.92%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.92%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 0.92%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.92%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 0.92%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 0.92%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 1         | 0.92%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 0.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 0.92%   |
| Intel Core i3-2348M CPU @ 2.30GHz           | 1         | 0.92%   |
| Intel Core i3-2328M CPU @ 2.20GHz           | 1         | 0.92%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 0.92%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 0.92%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 0.92%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 0.92%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 30.28%  |
| Intel Core i3           | 32        | 29.36%  |
| Intel Core i7           | 17        | 15.6%   |
| Intel Pentium           | 6         | 5.5%    |
| Intel Celeron           | 5         | 4.59%   |
| Intel Atom              | 4         | 3.67%   |
| Intel Pentium Dual-Core | 3         | 2.75%   |
| Intel Core 2 Duo        | 3         | 2.75%   |
| Other                   | 1         | 0.92%   |
| AMD Ryzen 3             | 1         | 0.92%   |
| AMD E2                  | 1         | 0.92%   |
| AMD E1                  | 1         | 0.92%   |
| AMD Athlon II Dual-Core | 1         | 0.92%   |
| AMD A4                  | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 89        | 81.65%  |
| 4      | 18        | 16.51%  |
| 1      | 2         | 1.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 85        | 77.98%  |
| 1      | 24        | 22.02%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 98.17%  |
| Unknown        | 2         | 1.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 18.42%  |
| 0x306a9    | 17        | 14.91%  |
| 0x206a7    | 10        | 8.77%   |
| 0x40651    | 9         | 7.89%   |
| 0x20655    | 9         | 7.89%   |
| 0x406e3    | 8         | 7.02%   |
| 0x30678    | 7         | 6.14%   |
| 0x306d4    | 6         | 5.26%   |
| 0x806ea    | 4         | 3.51%   |
| 0x806e9    | 4         | 3.51%   |
| 0x1067a    | 4         | 3.51%   |
| 0x906e9    | 2         | 1.75%   |
| 0x30661    | 2         | 1.75%   |
| 0x20652    | 2         | 1.75%   |
| 0x806ec    | 1         | 0.88%   |
| 0x806c1    | 1         | 0.88%   |
| 0x506c9    | 1         | 0.88%   |
| 0x406c3    | 1         | 0.88%   |
| 0x306c3    | 1         | 0.88%   |
| 0x0810100b | 1         | 0.88%   |
| 0x0700010f | 1         | 0.88%   |
| 0x06006705 | 1         | 0.88%   |
| 0x05000119 | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 20        | 18.35%  |
| Haswell     | 14        | 12.84%  |
| SandyBridge | 12        | 11.01%  |
| KabyLake    | 12        | 11.01%  |
| Westmere    | 11        | 10.09%  |
| Skylake     | 10        | 9.17%   |
| Silvermont  | 9         | 8.26%   |
| Penryn      | 6         | 5.5%    |
| Broadwell   | 6         | 5.5%    |
| Bonnell     | 2         | 1.83%   |
| Zen         | 1         | 0.92%   |
| TigerLake   | 1         | 0.92%   |
| K10         | 1         | 0.92%   |
| Jaguar      | 1         | 0.92%   |
| Goldmont    | 1         | 0.92%   |
| Excavator   | 1         | 0.92%   |
| Bobcat      | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 95        | 68.35%  |
| AMD    | 24        | 17.27%  |
| Nvidia | 20        | 14.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 13.67%  |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 7.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 7.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 6.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 6.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 5.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 4.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 3.6%    |
| Intel HD Graphics 620                                                                    | 5         | 3.6%    |
| Intel HD Graphics 5500                                                                   | 5         | 3.6%    |
| Intel UHD Graphics 620                                                                   | 4         | 2.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.16%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.44%   |
| Intel HD Graphics 630                                                                    | 2         | 1.44%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.44%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.44%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.44%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 1.44%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.72%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.72%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.72%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.72%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.72%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.72%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.72%   |
| Nvidia GK104GLM [Quadro K4000M]                                                          | 1         | 0.72%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 620M]                                                          | 1         | 0.72%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.72%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.72%   |
| Intel HD Graphics 510                                                                    | 1         | 0.72%   |
| Intel HD Graphics 500                                                                    | 1         | 0.72%   |
| Intel HD Graphics                                                                        | 1         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.72%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.72%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.72%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.72%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.72%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.72%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 0.72%   |
| AMD Mars [Radeon HD 8730M]                                                               | 1         | 0.72%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.72%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 0.72%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 59.63%  |
| Intel + Nvidia | 16        | 14.68%  |
| Intel + AMD    | 14        | 12.84%  |
| 1 x AMD        | 10        | 9.17%   |
| 1 x Nvidia     | 4         | 3.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 98        | 89.09%  |
| Proprietary | 10        | 9.09%   |
| Unknown     | 2         | 1.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 64.86%  |
| 1.01-2.0   | 19        | 17.12%  |
| 0.51-1.0   | 8         | 7.21%   |
| 0.01-0.5   | 8         | 7.21%   |
| 3.01-4.0   | 4         | 3.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 23        | 20.54%  |
| Samsung Electronics     | 22        | 19.64%  |
| AU Optronics            | 20        | 17.86%  |
| BOE                     | 13        | 11.61%  |
| Chimei Innolux          | 12        | 10.71%  |
| Chi Mei Optoelectronics | 7         | 6.25%   |
| Hewlett-Packard         | 3         | 2.68%   |
| Apple                   | 2         | 1.79%   |
| Sharp                   | 1         | 0.89%   |
| PANDA                   | 1         | 0.89%   |
| MStar                   | 1         | 0.89%   |
| LGD                     | 1         | 0.89%   |
| Lenovo                  | 1         | 0.89%   |
| InnoLux Display         | 1         | 0.89%   |
| Goldstar                | 1         | 0.89%   |
| BenQ                    | 1         | 0.89%   |
| AOC                     | 1         | 0.89%   |
| Acer                    | 1         | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch      | 3         | 2.68%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 3         | 2.68%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 2.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch      | 2         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 2         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch      | 2         | 1.79%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch             | 2         | 1.79%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch               | 2         | 1.79%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 1.79%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 2         | 1.79%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 2         | 1.79%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 2         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch          | 2         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 1.79%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                      | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 2         | 1.79%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.89%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch         | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC494A 1366x768 344x193mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3442 1366x768 344x194mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 370x230mm 17.2-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3241 1366x768 344x194mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch      | 1         | 0.89%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                   | 1         | 0.89%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                          | 1         | 0.89%   |
| LGD LCD Monitor 1600x900                                                  | 1         | 0.89%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch              | 1         | 0.89%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch               | 1         | 0.89%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 1         | 0.89%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch              | 1         | 0.89%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 1         | 0.89%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch               | 1         | 0.89%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 1         | 0.89%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch              | 1         | 0.89%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch               | 1         | 0.89%   |
| LG Display LCD Monitor LGD01F5 1280x800 304x190mm 14.1-inch               | 1         | 0.89%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 1         | 0.89%   |
| InnoLux Display LCD Monitor INL0006 1366x768 344x194mm 15.5-inch          | 1         | 0.89%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch                 | 1         | 0.89%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch               | 1         | 0.89%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch                | 1         | 0.89%   |
| Goldstar L1720B GSM4372 1280x1024 338x270mm 17.0-inch                     | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch           | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch          | 1         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch           | 1         | 0.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 73        | 66.97%  |
| 1920x1080 (FHD)   | 20        | 18.35%  |
| 1600x900 (HD+)    | 5         | 4.59%   |
| 1280x800 (WXGA)   | 3         | 2.75%   |
| 3840x2160 (4K)    | 2         | 1.83%   |
| 1440x900 (WXGA+)  | 2         | 1.83%   |
| 1920x1200 (WUXGA) | 1         | 0.92%   |
| 1680x945          | 1         | 0.92%   |
| 1280x1024 (SXGA)  | 1         | 0.92%   |
| 1024x600          | 1         | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 64.29%  |
| 13      | 10        | 8.93%   |
| 17      | 6         | 5.36%   |
| 14      | 6         | 5.36%   |
| 12      | 5         | 4.46%   |
| 18      | 4         | 3.57%   |
| 10      | 2         | 1.79%   |
| 52      | 1         | 0.89%   |
| 27      | 1         | 0.89%   |
| 24      | 1         | 0.89%   |
| 21      | 1         | 0.89%   |
| 19      | 1         | 0.89%   |
| 11      | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 85        | 76.58%  |
| 201-300     | 10        | 9.01%   |
| 351-400     | 7         | 6.31%   |
| 401-500     | 5         | 4.5%    |
| 501-600     | 2         | 1.8%    |
| 1001-1500   | 1         | 0.9%    |
| Unknown     | 1         | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 96        | 91.43%  |
| 16/10   | 6         | 5.71%   |
| 5/4     | 1         | 0.95%   |
| 3/2     | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 64.29%  |
| 81-90          | 14        | 12.5%   |
| 61-70          | 5         | 4.46%   |
| 141-150        | 5         | 4.46%   |
| 121-130        | 3         | 2.68%   |
| 71-80          | 2         | 1.79%   |
| 41-50          | 2         | 1.79%   |
| 151-200        | 2         | 1.79%   |
| 131-140        | 2         | 1.79%   |
| More than 1000 | 1         | 0.89%   |
| 51-60          | 1         | 0.89%   |
| 301-350        | 1         | 0.89%   |
| 201-250        | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 69        | 62.16%  |
| 121-160 | 21        | 18.92%  |
| 51-100  | 15        | 13.51%  |
| 161-240 | 4         | 3.6%    |
| 1-50    | 1         | 0.9%    |
| Unknown | 1         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 100       | 90.91%  |
| 2     | 8         | 7.27%   |
| 0     | 2         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 65        | 33.68%  |
| Intel                           | 38        | 19.69%  |
| Qualcomm Atheros                | 36        | 18.65%  |
| Broadcom                        | 25        | 12.95%  |
| Ralink Technology               | 7         | 3.63%   |
| Ralink                          | 6         | 3.11%   |
| Samsung Electronics             | 2         | 1.04%   |
| MediaTek                        | 2         | 1.04%   |
| Huawei Technologies             | 2         | 1.04%   |
| Broadcom Limited                | 2         | 1.04%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 16.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 10.87%  |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 5.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 3.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.74%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.74%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.74%   |
| Intel Wireless 8260                                               | 4         | 1.74%   |
| Intel Wireless 7260                                               | 3         | 1.3%    |
| Intel Wireless 3160                                               | 3         | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.3%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.3%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.3%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.87%   |
| Intel Wireless 7265                                               | 2         | 0.87%   |
| Intel WiFi Link 5100                                              | 2         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.87%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.87%   |
| Intel Centrino Wireless-N 135                                     | 2         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.87%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.87%   |
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
| MediaTek TECNO SPARK 3                                            | 1         | 0.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.43%   |
| Intel Wireless 3165                                               | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 30%     |
| Qualcomm Atheros                | 32        | 26.67%  |
| Broadcom                        | 20        | 16.67%  |
| Realtek Semiconductor           | 13        | 10.83%  |
| Ralink Technology               | 7         | 5.83%   |
| Ralink                          | 6         | 5%      |
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
| Broadcom BCM43142 802.11b/g/n                                        | 12        | 10%     |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 8.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 8         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 4.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 3.33%   |
| Ralink MT7601U Wireless Adapter                                      | 4         | 3.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 3.33%   |
| Intel Wireless 8265 / 8275                                           | 4         | 3.33%   |
| Intel Wireless 8260                                                  | 4         | 3.33%   |
| Intel Wireless 7260                                                  | 3         | 2.5%    |
| Intel Wireless 3160                                                  | 3         | 2.5%    |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 2.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 1.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.67%   |
| Intel Wireless 7265                                                  | 2         | 1.67%   |
| Intel WiFi Link 5100                                                 | 2         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 1.67%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.67%   |
| Intel Centrino Wireless-N 135                                        | 2         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.67%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.67%   |
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
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 58.33%  |
| Intel                    | 22        | 20.37%  |
| Qualcomm Atheros         | 7         | 6.48%   |
| Broadcom                 | 7         | 6.48%   |
| Samsung Electronics      | 2         | 1.85%   |
| Xiaomi                   | 1         | 0.93%   |
| Nvidia                   | 1         | 0.93%   |
| MediaTek                 | 1         | 0.93%   |
| Marvell Technology Group | 1         | 0.93%   |
| LG Electronics           | 1         | 0.93%   |
| Huawei Technologies      | 1         | 0.93%   |
| Broadcom Limited         | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 34.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 22.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 3.67%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.75%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.75%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.83%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.92%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.92%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.92%   |
| MediaTek TECNO SPARK 3                                            | 1         | 0.92%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.92%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.92%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.92%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.92%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.92%   |
| Huawei E353/E3131                                                 | 1         | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.92%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.92%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 51.18%  |
| Ethernet | 102       | 48.34%  |
| Modem    | 1         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 85.98%  |
| Ethernet | 15        | 14.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 102       | 91.89%  |
| 1     | 6         | 5.41%   |
| 0     | 3         | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

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
| Intel             | 100       | 84.75%  |
| AMD               | 12        | 10.17%  |
| Nvidia            | 5         | 4.24%   |
| Texas Instruments | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 16.67%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 13.19%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 7.64%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 7.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 7.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.17%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.39%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.39%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.39%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.39%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.39%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.69%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.69%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.69%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.69%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.69%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.69%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 30.51%  |
| SK hynix            | 17        | 28.81%  |
| Micron Technology   | 9         | 15.25%  |
| Unknown             | 6         | 10.17%  |
| Kingston            | 2         | 3.39%   |
| Team                | 1         | 1.69%   |
| Ramaxel Technology  | 1         | 1.69%   |
| Nanya Technology    | 1         | 1.69%   |
| Elpida              | 1         | 1.69%   |
| Crucial             | 1         | 1.69%   |
| ASint Technology    | 1         | 1.69%   |
| A-DATA Technology   | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 6.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 3         | 4.62%   |
| Unknown RAM Module 4096MB SODIMM DDR3                      | 2         | 3.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 3.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 2         | 3.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 1.54%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s             | 1         | 1.54%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                | 1         | 1.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 1.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s             | 1         | 1.54%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s      | 1         | 1.54%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s           | 1         | 1.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 1.54%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.54%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s  | 1         | 1.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 1.54%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s  | 1         | 1.54%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.54%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.54%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s  | 1         | 1.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 1.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 1         | 1.54%   |
| SK hynix RAM HMA425S6BJR6N-UH 2GB SODIMM DDR4 2667MT/s     | 1         | 1.54%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.54%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 1.54%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s      | 1         | 1.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 1.54%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s      | 1         | 1.54%   |
| Ramaxel RAM RMT1970ED48E8F1333 2GB SODIMM DDR3 1333MT/s    | 1         | 1.54%   |
| Nanya RAM M2S4G64CC88B4N-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 1.54%   |
| Micron RAM MT8KTF51264HZ-1G6 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.54%   |
| Micron RAM MT41K512M8RH-125:E 4GB SODIMM DDR3 1600MT/s     | 1         | 1.54%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 1.54%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.54%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s      | 1         | 1.54%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Micron RAM 16JTF1G64HZ-1G6D1 8GB SODIMM DDR3 1600MT/s      | 1         | 1.54%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s     | 1         | 1.54%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s    | 1         | 1.54%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s      | 1         | 1.54%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s | 1         | 1.54%   |
| ASint RAM C1RE5SR4HN1 2GB SODIMM SDRAM 4199MT/s            | 1         | 1.54%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2400MT/s             | 1         | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 36        | 73.47%  |
| DDR4   | 11        | 22.45%  |
| SDRAM  | 1         | 2.04%   |
| LPDDR4 | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 48        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 28        | 49.12%  |
| 8192  | 14        | 24.56%  |
| 2048  | 13        | 22.81%  |
| 32768 | 1         | 1.75%   |
| 16384 | 1         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 51.92%  |
| 2667    | 8         | 15.38%  |
| 1334    | 4         | 7.69%   |
| 1333    | 3         | 5.77%   |
| 3266    | 2         | 3.85%   |
| 2400    | 2         | 3.85%   |
| Unknown | 2         | 3.85%   |
| 4199    | 1         | 1.92%   |
| 3200    | 1         | 1.92%   |
| 2133    | 1         | 1.92%   |
| 1067    | 1         | 1.92%   |

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
| Chicony Electronics                    | 24        | 24.49%  |
| Microdia                               | 15        | 15.31%  |
| Realtek Semiconductor                  | 9         | 9.18%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 9.18%   |
| Acer                                   | 8         | 8.16%   |
| Sunplus Innovation Technology          | 7         | 7.14%   |
| Suyin                                  | 5         | 5.1%    |
| Syntek                                 | 4         | 4.08%   |
| IMC Networks                           | 3         | 3.06%   |
| Apple                                  | 3         | 3.06%   |
| Silicon Motion                         | 2         | 2.04%   |
| Quanta                                 | 2         | 2.04%   |
| Lite-On Technology                     | 2         | 2.04%   |
| Samsung Electronics                    | 1         | 1.02%   |
| Primax Electronics                     | 1         | 1.02%   |
| Pixart Imaging                         | 1         | 1.02%   |
| Aveo Technology                        | 1         | 1.02%   |
| Alcor Micro                            | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Acer Lenovo EasyCamera                              | 6         | 6.12%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 4.08%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 3         | 3.06%   |
| Microdia Integrated_Webcam_HD                       | 3         | 3.06%   |
| Microdia Integrated Webcam                          | 3         | 3.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 3.06%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.04%   |
| Suyin HP Truevision HD                              | 2         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 2         | 2.04%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.04%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 2.04%   |
| Chicony Integrated Camera                           | 2         | 2.04%   |
| Chicony HD WebCam                                   | 2         | 2.04%   |
| Chicony Acer CrystalEye Webcam                      | 2         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 2.04%   |
| Syntek USB2.0 Camera                                | 1         | 1.02%   |
| Syntek EasyCamera                                   | 1         | 1.02%   |
| Suyin WebCam                                        | 1         | 1.02%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.02%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.02%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.02%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 1.02%   |
| Sunplus Dell HD Webcam                              | 1         | 1.02%   |
| Silicon Motion WebCam SC-13HDL11431N                | 1         | 1.02%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.02%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 1.02%   |
| Realtek USB Camera                                  | 1         | 1.02%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.02%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.02%   |
| Realtek Integrated Webcam                           | 1         | 1.02%   |
| Realtek HP Webcam                                   | 1         | 1.02%   |
| Realtek HP Truevision HD                            | 1         | 1.02%   |
| Realtek HD Webcam - Realtek                         | 1         | 1.02%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 1.02%   |
| Quanta HD Webcam                                    | 1         | 1.02%   |
| Quanta HD User Facing                               | 1         | 1.02%   |
| Primax webcam                                       | 1         | 1.02%   |
| Pixart Imaging VGA Webcam                           | 1         | 1.02%   |
| Microdia Sony Visual Communication Camera           | 1         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.02%   |
| Microdia Integrated Webcam HD                       | 1         | 1.02%   |
| Microdia 1.3 MPixel Integrated Webcam               | 1         | 1.02%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.02%   |
| Lite-On Integrated Camera                           | 1         | 1.02%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.02%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.02%   |
| IMC Networks Integrated Webcam                      | 1         | 1.02%   |
| Chicony WebCam                                      | 1         | 1.02%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.02%   |
| Chicony Sony Visual Communication Camera            | 1         | 1.02%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.02%   |
| Chicony HP Webcam                                   | 1         | 1.02%   |
| Chicony HP Truevision HD                            | 1         | 1.02%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 1.02%   |
| Chicony HP HD Camera                                | 1         | 1.02%   |

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
| 0     | 71        | 64.55%  |
| 1     | 34        | 30.91%  |
| 2     | 4         | 3.64%   |
| 3     | 1         | 0.91%   |

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

