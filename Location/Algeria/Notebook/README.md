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
| Sony          | SVE1713A6EW                 | [d1c46739be](https://linux-hardware.org/?probe=d1c46739be) | Sep 07, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [30aa6bbae6](https://linux-hardware.org/?probe=30aa6bbae6) | Aug 30, 2021 |
| HP            | 15                          | [5520042e14](https://linux-hardware.org/?probe=5520042e14) | Aug 28, 2021 |
| HP            | 15                          | [cc4e936b38](https://linux-hardware.org/?probe=cc4e936b38) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | [8a71545b54](https://linux-hardware.org/?probe=8a71545b54) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | [fcbd3a84a5](https://linux-hardware.org/?probe=fcbd3a84a5) | Aug 25, 2021 |
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
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [f0ee9bb300](https://linux-hardware.org/?probe=f0ee9bb300) | Mar 02, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [5cf7ce91a7](https://linux-hardware.org/?probe=5cf7ce91a7) | Mar 01, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [a88af46d6e](https://linux-hardware.org/?probe=a88af46d6e) | Mar 01, 2021 |
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
| Sony          | VPCEH2H1E                   | [1b82d6faa0](https://linux-hardware.org/?probe=1b82d6faa0) | Nov 14, 2020 |
| Acer          | Aspire F5-572               | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| HP            | EliteBook Folio 9470m       | [39251e283c](https://linux-hardware.org/?probe=39251e283c) | Oct 29, 2020 |
| HP            | ProBook 450 G2              | [35c0a9b54d](https://linux-hardware.org/?probe=35c0a9b54d) | Oct 28, 2020 |
| HP            | ProBook 450 G2              | [d4e9bfb078](https://linux-hardware.org/?probe=d4e9bfb078) | Oct 28, 2020 |
| HP            | ProBook 450 G0              | [85e77f85c7](https://linux-hardware.org/?probe=85e77f85c7) | Oct 26, 2020 |
| Dell          | Latitude E5430 non-vPro     | [230a4dff71](https://linux-hardware.org/?probe=230a4dff71) | Oct 26, 2020 |
| HP            | ProBook 4540s               | [e2bb03b7da](https://linux-hardware.org/?probe=e2bb03b7da) | Oct 23, 2020 |
| HP            | ProBook 4540s               | [b369817417](https://linux-hardware.org/?probe=b369817417) | Oct 15, 2020 |
| Lenovo        | G50-30 80G0                 | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| Sony          | VPCEH2H1E                   | [07077a7194](https://linux-hardware.org/?probe=07077a7194) | Oct 02, 2020 |
| Sony          | VPCEH2H1E                   | [086925774f](https://linux-hardware.org/?probe=086925774f) | Sep 24, 2020 |
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
| HP            | Pavilion 15                 | [b2625d7672](https://linux-hardware.org/?probe=b2625d7672) | Sep 15, 2019 |
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
| Ubuntu 20.04        | 32        | 27.35%  |
| Ubuntu 18.04        | 13        | 11.11%  |
| OpenMandriva 4.2    | 9         | 7.69%   |
| Linux Mint 20.1     | 6         | 5.13%   |
| KDE neon 20.04      | 5         | 4.27%   |
| Xubuntu 20.04       | 4         | 3.42%   |
| Pop!_OS 20.04       | 4         | 3.42%   |
| Fedora 35           | 3         | 2.56%   |
| ArcoLinux Rolling   | 3         | 2.56%   |
| Arch                | 3         | 2.56%   |
| Ubuntu 20.10        | 2         | 1.71%   |
| Ubuntu 19.10        | 2         | 1.71%   |
| Ubuntu 16.04        | 2         | 1.71%   |
| ROSA R11            | 2         | 1.71%   |
| Manjaro             | 2         | 1.71%   |
| Kubuntu 20.04       | 2         | 1.71%   |
| Kali 2021.1         | 2         | 1.71%   |
| BlackPanther 18.1   | 2         | 1.71%   |
| Zorin 16            | 1         | 0.85%   |
| Ubuntu 21.10        | 1         | 0.85%   |
| Ubuntu 21.04        | 1         | 0.85%   |
| ROSA R8.1           | 1         | 0.85%   |
| ROSA R10            | 1         | 0.85%   |
| Pop!_OS 21.04       | 1         | 0.85%   |
| Pear OS 20.04       | 1         | 0.85%   |
| Parrot 5.0          | 1         | 0.85%   |
| OpenMandriva 4.50   | 1         | 0.85%   |
| MX 19               | 1         | 0.85%   |
| Manjaro 20.1        | 1         | 0.85%   |
| Linux Mint 20       | 1         | 0.85%   |
| Fedora 31           | 1         | 0.85%   |
| Fedora 29           | 1         | 0.85%   |
| Debian 10           | 1         | 0.85%   |
| Clear Linux 34640   | 1         | 0.85%   |
| CentOS 7            | 1         | 0.85%   |
| Artix Rolling       | 1         | 0.85%   |
| ArchLabs 2020.11.04 | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 52        | 45.22%  |
| OpenMandriva | 10        | 8.7%    |
| Linux Mint   | 7         | 6.09%   |
| Pop!_OS      | 5         | 4.35%   |
| KDE neon     | 5         | 4.35%   |
| Fedora       | 5         | 4.35%   |
| Xubuntu      | 4         | 3.48%   |
| ROSA         | 3         | 2.61%   |
| Manjaro      | 3         | 2.61%   |
| ArcoLinux    | 3         | 2.61%   |
| Arch         | 3         | 2.61%   |
| Kubuntu      | 2         | 1.74%   |
| Kali         | 2         | 1.74%   |
| BlackPanther | 2         | 1.74%   |
| Zorin        | 1         | 0.87%   |
| Pear OS      | 1         | 0.87%   |
| Parrot       | 1         | 0.87%   |
| MX           | 1         | 0.87%   |
| Debian       | 1         | 0.87%   |
| Clear Linux  | 1         | 0.87%   |
| CentOS       | 1         | 0.87%   |
| Artix        | 1         | 0.87%   |
| ArchLabs     | 1         | 0.87%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 9         | 7.14%   |
| 5.4.0-72-generic         | 4         | 3.17%   |
| 5.4.0-54-generic         | 4         | 3.17%   |
| 5.4.0-42-generic         | 4         | 3.17%   |
| 5.4.0-29-generic         | 4         | 3.17%   |
| 5.4.0-48-generic         | 3         | 2.38%   |
| 5.13.0-30-generic        | 3         | 2.38%   |
| 5.11.0-27-generic        | 3         | 2.38%   |
| 5.8.0-50-generic         | 2         | 1.59%   |
| 5.8.0-44-generic         | 2         | 1.59%   |
| 5.4.0-80-generic         | 2         | 1.59%   |
| 5.4.0-7625-generic       | 2         | 1.59%   |
| 5.4.0-65-generic         | 2         | 1.59%   |
| 5.4.0-56-generic         | 2         | 1.59%   |
| 5.4.0-52-generic         | 2         | 1.59%   |
| 5.4.0-33-generic         | 2         | 1.59%   |
| 5.3.0-40-generic         | 2         | 1.59%   |
| 5.11.0-25-generic        | 2         | 1.59%   |
| 4.18.16-desktop-1bP      | 2         | 1.59%   |
| 5.9.11-3-MANJARO         | 1         | 0.79%   |
| 5.8.0-63-generic         | 1         | 0.79%   |
| 5.8.0-48-generic         | 1         | 0.79%   |
| 5.8.0-45-generic         | 1         | 0.79%   |
| 5.8.0-43-generic         | 1         | 0.79%   |
| 5.8.0-36-generic         | 1         | 0.79%   |
| 5.7.17-2-MANJARO         | 1         | 0.79%   |
| 5.7.0-kali1-amd64        | 1         | 0.79%   |
| 5.6.0-2-amd64            | 1         | 0.79%   |
| 5.4.72-1-lts             | 1         | 0.79%   |
| 5.4.15-200.fc31.x86_64   | 1         | 0.79%   |
| 5.4.0-81-generic         | 1         | 0.79%   |
| 5.4.0-7626-generic       | 1         | 0.79%   |
| 5.4.0-70-generic         | 1         | 0.79%   |
| 5.4.0-58-generic         | 1         | 0.79%   |
| 5.4.0-51-generic         | 1         | 0.79%   |
| 5.4.0-47-generic         | 1         | 0.79%   |
| 5.4.0-40-generic         | 1         | 0.79%   |
| 5.4.0-39-generic         | 1         | 0.79%   |
| 5.4.0-37-generic         | 1         | 0.79%   |
| 5.4.0-31-generic         | 1         | 0.79%   |
| 5.4.0-26-generic         | 1         | 0.79%   |
| 5.3.0-51-generic         | 1         | 0.79%   |
| 5.3.0-46-generic         | 1         | 0.79%   |
| 5.3.0-42-generic         | 1         | 0.79%   |
| 5.3.0-28-generic         | 1         | 0.79%   |
| 5.3.0-18-generic         | 1         | 0.79%   |
| 5.17.4-200.fc35.x86_64   | 1         | 0.79%   |
| 5.16.11-arch1-1          | 1         | 0.79%   |
| 5.15.8-76051508-generic  | 1         | 0.79%   |
| 5.15.7-zen1-1-zen        | 1         | 0.79%   |
| 5.15.7-arch1-1           | 1         | 0.79%   |
| 5.15.5-76051505-generic  | 1         | 0.79%   |
| 5.15.15-200.fc35.x86_64  | 1         | 0.79%   |
| 5.15.10-200.fc35.x86_64  | 1         | 0.79%   |
| 5.15.0-051500rc5-generic | 1         | 0.79%   |
| 5.14.0-9parrot1-amd64    | 1         | 0.79%   |
| 5.13.2-051302-generic    | 1         | 0.79%   |
| 5.13.0-37-generic        | 1         | 0.79%   |
| 5.13.0-25-generic        | 1         | 0.79%   |
| 5.12.5-1041.native       | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 33        | 28.7%   |
| 5.8.0   | 9         | 7.83%   |
| 5.10.14 | 9         | 7.83%   |
| 5.3.0   | 7         | 6.09%   |
| 5.11.0  | 7         | 6.09%   |
| 5.13.0  | 5         | 4.35%   |
| 4.15.0  | 5         | 4.35%   |
| 5.0.0   | 4         | 3.48%   |
| 4.18.16 | 3         | 2.61%   |
| 5.15.7  | 2         | 1.74%   |
| 5.10.0  | 2         | 1.74%   |
| 4.4.0   | 2         | 1.74%   |
| 5.9.11  | 1         | 0.87%   |
| 5.7.17  | 1         | 0.87%   |
| 5.7.0   | 1         | 0.87%   |
| 5.6.0   | 1         | 0.87%   |
| 5.4.72  | 1         | 0.87%   |
| 5.4.15  | 1         | 0.87%   |
| 5.17.4  | 1         | 0.87%   |
| 5.16.11 | 1         | 0.87%   |
| 5.15.8  | 1         | 0.87%   |
| 5.15.5  | 1         | 0.87%   |
| 5.15.15 | 1         | 0.87%   |
| 5.15.10 | 1         | 0.87%   |
| 5.15.0  | 1         | 0.87%   |
| 5.14.0  | 1         | 0.87%   |
| 5.13.2  | 1         | 0.87%   |
| 5.12.5  | 1         | 0.87%   |
| 5.12.4  | 1         | 0.87%   |
| 5.12.15 | 1         | 0.87%   |
| 5.11.15 | 1         | 0.87%   |
| 5.10.82 | 1         | 0.87%   |
| 5.10.3  | 1         | 0.87%   |
| 4.9.9   | 1         | 0.87%   |
| 4.9.60  | 1         | 0.87%   |
| 4.19.79 | 1         | 0.87%   |
| 4.19.0  | 1         | 0.87%   |
| 4.18.0  | 1         | 0.87%   |
| 3.10.0  | 1         | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 35        | 30.43%  |
| 5.10    | 13        | 11.3%   |
| 5.8     | 9         | 7.83%   |
| 5.11    | 8         | 6.96%   |
| 5.3     | 7         | 6.09%   |
| 5.15    | 7         | 6.09%   |
| 5.13    | 6         | 5.22%   |
| 4.15    | 5         | 4.35%   |
| 5.0     | 4         | 3.48%   |
| 4.18    | 4         | 3.48%   |
| 5.12    | 3         | 2.61%   |
| 5.7     | 2         | 1.74%   |
| 4.9     | 2         | 1.74%   |
| 4.4     | 2         | 1.74%   |
| 4.19    | 2         | 1.74%   |
| 5.9     | 1         | 0.87%   |
| 5.6     | 1         | 0.87%   |
| 5.17    | 1         | 0.87%   |
| 5.16    | 1         | 0.87%   |
| 5.14    | 1         | 0.87%   |
| 3.10    | 1         | 0.87%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 103       | 99.04%  |
| i686   | 1         | 0.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 54        | 48.65%  |
| KDE5       | 18        | 16.22%  |
| Unknown    | 13        | 11.71%  |
| XFCE       | 8         | 7.21%   |
| X-Cinnamon | 4         | 3.6%    |
| KDE        | 4         | 3.6%    |
| MATE       | 3         | 2.7%    |
| KDE4       | 2         | 1.8%    |
| Unity      | 1         | 0.9%    |
| LXQt       | 1         | 0.9%    |
| i3         | 1         | 0.9%    |
| Deepin     | 1         | 0.9%    |
| Cinnamon   | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 93        | 87.74%  |
| Wayland | 6         | 5.66%   |
| Unknown | 6         | 5.66%   |
| Tty     | 1         | 0.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 60%     |
| SDDM    | 15        | 13.64%  |
| GDM     | 13        | 11.82%  |
| LightDM | 8         | 7.27%   |
| TDM     | 4         | 3.64%   |
| KDM     | 2         | 1.82%   |
| SLiM    | 1         | 0.91%   |
| GDM3    | 1         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 51        | 48.11%  |
| fr_FR   | 29        | 27.36%  |
| Unknown | 13        | 12.26%  |
| en_GB   | 4         | 3.77%   |
| C       | 4         | 3.77%   |
| ar_DZ   | 2         | 1.89%   |
| fr_DZ   | 1         | 0.94%   |
| fr_BE   | 1         | 0.94%   |
| ar_EG   | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 71        | 65.74%  |
| EFI  | 37        | 34.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 83        | 76.15%  |
| Overlay | 12        | 11.01%  |
| Btrfs   | 6         | 5.5%    |
| Ext2    | 3         | 2.75%   |
| Unknown | 3         | 2.75%   |
| Xfs     | 1         | 0.92%   |
| Ext3    | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 73        | 68.22%  |
| MBR     | 17        | 15.89%  |
| GPT     | 17        | 15.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 84.4%   |
| Yes       | 17        | 15.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 53.77%  |
| No        | 49        | 46.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 25        | 24.04%  |
| Hewlett-Packard     | 19        | 18.27%  |
| Lenovo              | 17        | 16.35%  |
| Acer                | 10        | 9.62%   |
| Toshiba             | 8         | 7.69%   |
| ASUSTek Computer    | 7         | 6.73%   |
| Sony                | 6         | 5.77%   |
| Packard Bell        | 3         | 2.88%   |
| Samsung Electronics | 2         | 1.92%   |
| Fujitsu             | 2         | 1.92%   |
| Apple               | 2         | 1.92%   |
| MSI                 | 1         | 0.96%   |
| LDLC                | 1         | 0.96%   |
| eMachines           | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba Satellite C55-B             | 2         | 1.92%   |
| Lenovo IdeaPad 300-15ISK 80Q7       | 2         | 1.92%   |
| Lenovo G560 20042                   | 2         | 1.92%   |
| Lenovo G50-30 80G0                  | 2         | 1.92%   |
| Lenovo B50-70 20384                 | 2         | 1.92%   |
| HP ProBook 4540s                    | 2         | 1.92%   |
| HP Pavilion 15                      | 2         | 1.92%   |
| HP 15                               | 2         | 1.92%   |
| Dell Latitude E7440                 | 2         | 1.92%   |
| Dell Latitude E5430 vPro            | 2         | 1.92%   |
| Dell Inspiron N5110                 | 2         | 1.92%   |
| Dell Inspiron 3542                  | 2         | 1.92%   |
| Dell Inspiron 15-3567               | 2         | 1.92%   |
| Acer Aspire 5738                    | 2         | 1.92%   |
| Toshiba Satellite C850-A979         | 1         | 0.96%   |
| Toshiba Satellite C50-A560          | 1         | 0.96%   |
| Toshiba Satellite C50-A545          | 1         | 0.96%   |
| Toshiba Satellite C50-A539          | 1         | 0.96%   |
| Toshiba PORTEGE R30-A               | 1         | 0.96%   |
| Toshiba PORTEGE M780                | 1         | 0.96%   |
| Sony VPCEJ2S1E                      | 1         | 0.96%   |
| Sony VPCEH2H1E                      | 1         | 0.96%   |
| Sony VGN-AW21M_H                    | 1         | 0.96%   |
| Sony SVF1531GSFB                    | 1         | 0.96%   |
| Sony SVE1713A6EW                    | 1         | 0.96%   |
| Sony SVE1513K1EW                    | 1         | 0.96%   |
| Samsung N102SP/N100SP/N101SP        | 1         | 0.96%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B | 1         | 0.96%   |
| Packard Bell EasyNote TJ75          | 1         | 0.96%   |
| Packard Bell EasyNote LJ71          | 1         | 0.96%   |
| Packard Bell DOT S                  | 1         | 0.96%   |
| MSI CR610M                          | 1         | 0.96%   |
| Lenovo ThinkPad X260 20F5S1G104     | 1         | 0.96%   |
| Lenovo ThinkPad X201 3680AQ1        | 1         | 0.96%   |
| Lenovo ThinkPad T450 20BUS2RN1H     | 1         | 0.96%   |
| Lenovo ThinkPad T440 20B6S00200     | 1         | 0.96%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 0.96%   |
| Lenovo IdeaPad 310-15IKB 80TV       | 1         | 0.96%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 0.96%   |
| Lenovo G580 2189                    | 1         | 0.96%   |
| Lenovo G500 20236                   | 1         | 0.96%   |
| LDLC Mercure MH                     | 1         | 0.96%   |
| HP ZBook 15 G4                      | 1         | 0.96%   |
| HP ProBook 650 G1                   | 1         | 0.96%   |
| HP ProBook 450 G6                   | 1         | 0.96%   |
| HP ProBook 450 G3                   | 1         | 0.96%   |
| HP ProBook 450 G2                   | 1         | 0.96%   |
| HP ProBook 450 G0                   | 1         | 0.96%   |
| HP Pavilion Notebook                | 1         | 0.96%   |
| HP Notebook                         | 1         | 0.96%   |
| HP Laptop 15-bw0xx                  | 1         | 0.96%   |
| HP EliteBook Folio 9470m            | 1         | 0.96%   |
| HP EliteBook 840 G3                 | 1         | 0.96%   |
| HP 630                              | 1         | 0.96%   |
| HP 250 G4                           | 1         | 0.96%   |
| Fujitsu LIFEBOOK AH532/G21          | 1         | 0.96%   |
| Fujitsu LIFEBOOK A532               | 1         | 0.96%   |
| eMachines eME732                    | 1         | 0.96%   |
| Dell XPS 13 9350                    | 1         | 0.96%   |
| Dell Vostro 3500                    | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 11        | 10.58%  |
| Dell Latitude         | 10        | 9.62%   |
| Acer Aspire           | 8         | 7.69%   |
| HP ProBook            | 7         | 6.73%   |
| Toshiba Satellite     | 6         | 5.77%   |
| Lenovo IdeaPad        | 5         | 4.81%   |
| Lenovo ThinkPad       | 4         | 3.85%   |
| HP Pavilion           | 3         | 2.88%   |
| Toshiba PORTEGE       | 2         | 1.92%   |
| Packard Bell EasyNote | 2         | 1.92%   |
| Lenovo G560           | 2         | 1.92%   |
| Lenovo G50-30         | 2         | 1.92%   |
| Lenovo B50-70         | 2         | 1.92%   |
| HP EliteBook          | 2         | 1.92%   |
| HP 15                 | 2         | 1.92%   |
| Fujitsu LIFEBOOK      | 2         | 1.92%   |
| Dell Precision        | 2         | 1.92%   |
| Acer Extensa          | 2         | 1.92%   |
| Sony VPCEJ2S1E        | 1         | 0.96%   |
| Sony VPCEH2H1E        | 1         | 0.96%   |
| Sony VGN-AW21M        | 1         | 0.96%   |
| Sony SVF1531GSFB      | 1         | 0.96%   |
| Sony SVE1713A6EW      | 1         | 0.96%   |
| Sony SVE1513K1EW      | 1         | 0.96%   |
| Samsung N102SP        | 1         | 0.96%   |
| Samsung 700Z3A        | 1         | 0.96%   |
| Packard Bell DOT      | 1         | 0.96%   |
| MSI CR610M            | 1         | 0.96%   |
| Lenovo G580           | 1         | 0.96%   |
| Lenovo G500           | 1         | 0.96%   |
| LDLC Mercure          | 1         | 0.96%   |
| HP ZBook              | 1         | 0.96%   |
| HP Notebook           | 1         | 0.96%   |
| HP Laptop             | 1         | 0.96%   |
| HP 630                | 1         | 0.96%   |
| HP 250                | 1         | 0.96%   |
| eMachines eME732      | 1         | 0.96%   |
| Dell XPS              | 1         | 0.96%   |
| Dell Vostro           | 1         | 0.96%   |
| ASUS X55U             | 1         | 0.96%   |
| ASUS X555LAB          | 1         | 0.96%   |
| ASUS X541UV           | 1         | 0.96%   |
| ASUS X540SA           | 1         | 0.96%   |
| ASUS X205TAW          | 1         | 0.96%   |
| ASUS K50IE            | 1         | 0.96%   |
| ASUS GL753VD          | 1         | 0.96%   |
| Apple MacBookPro8     | 1         | 0.96%   |
| Apple MacBook7        | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 19        | 18.27%  |
| 2014 | 18        | 17.31%  |
| 2013 | 13        | 12.5%   |
| 2017 | 9         | 8.65%   |
| 2016 | 9         | 8.65%   |
| 2015 | 9         | 8.65%   |
| 2011 | 7         | 6.73%   |
| 2009 | 7         | 6.73%   |
| 2010 | 6         | 5.77%   |
| 2018 | 5         | 4.81%   |
| 2021 | 1         | 0.96%   |
| 2008 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 103       | 99.04%  |
| Enabled  | 1         | 0.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 45        | 43.27%  |
| 4.01-8.0   | 28        | 26.92%  |
| 8.01-16.0  | 19        | 18.27%  |
| 1.01-2.0   | 6         | 5.77%   |
| 16.01-24.0 | 3         | 2.88%   |
| 32.01-64.0 | 2         | 1.92%   |
| 2.01-3.0   | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 61        | 51.69%  |
| 2.01-3.0  | 34        | 28.81%  |
| 3.01-4.0  | 12        | 10.17%  |
| 0.51-1.0  | 6         | 5.08%   |
| 4.01-8.0  | 4         | 3.39%   |
| 8.01-16.0 | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 76.19%  |
| 2      | 23        | 21.9%   |
| 4      | 1         | 0.95%   |
| 0      | 1         | 0.95%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 71.15%  |
| No        | 30        | 28.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 94.23%  |
| No        | 6         | 5.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 98.1%   |
| No        | 2         | 1.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 70.75%  |
| No        | 31        | 29.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Algeria | 104       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Algiers                 | 24        | 20.17%  |
| Oran                    | 7         | 5.88%   |
| Belcourt                | 6         | 5.04%   |
| Blida                   | 5         | 4.2%    |
| Tlemcen                 | 4         | 3.36%   |
| Relizane                | 3         | 2.52%   |
| Laghouat                | 3         | 2.52%   |
| Constantine             | 3         | 2.52%   |
| Cheraga                 | 3         | 2.52%   |
| ash-Shalif              | 3         | 2.52%   |
| Annaba                  | 3         | 2.52%   |
| Tizi Ouzou              | 2         | 1.68%   |
| SГ©tif                | 2         | 1.68%   |
| Souk Ahras              | 2         | 1.68%   |
| Sidi Bel Abbes          | 2         | 1.68%   |
| El Eulma                | 2         | 1.68%   |
| Djelfa                  | 2         | 1.68%   |
| BouГЇra               | 2         | 1.68%   |
| Biskra                  | 2         | 1.68%   |
| Bir el Djir             | 2         | 1.68%   |
| Ain Fakroun             | 2         | 1.68%   |
| вЂ™AГЇn el Hammam | 1         | 0.84%   |
| Tolga                   | 1         | 0.84%   |
| Tipasa                  | 1         | 0.84%   |
| Tikobain                | 1         | 0.84%   |
| Teniet en Nasr          | 1         | 0.84%   |
| Tazoult-Lambese         | 1         | 0.84%   |
| Tadmait                 | 1         | 0.84%   |
| Sidi Kada               | 1         | 0.84%   |
| Saoula                  | 1         | 0.84%   |
| Salah Bey               | 1         | 0.84%   |
| Saida                   | 1         | 0.84%   |
| Reguiba                 | 1         | 0.84%   |
| Ras el Oued             | 1         | 0.84%   |
| Ouargla                 | 1         | 0.84%   |
| Noumerat                | 1         | 0.84%   |
| Medea                   | 1         | 0.84%   |
| Larbaâ                 | 1         | 0.84%   |
| Jijelli                 | 1         | 0.84%   |
| El Khroub               | 1         | 0.84%   |
| El Aouinet              | 1         | 0.84%   |
| Drea                    | 1         | 0.84%   |
| Djidiouia               | 1         | 0.84%   |
| Debila                  | 1         | 0.84%   |
| Chir                    | 1         | 0.84%   |
| Brezina                 | 1         | 0.84%   |
| Bougaa                  | 1         | 0.84%   |
| Boufarik                | 1         | 0.84%   |
| BouÃ¯ra               | 1         | 0.84%   |
| Boghni                  | 1         | 0.84%   |
| Birkhadem               | 1         | 0.84%   |
| Batna City              | 1         | 0.84%   |
| Ain el Bya              | 1         | 0.84%   |
| Ain Defla               | 1         | 0.84%   |
| Ain Beida               | 1         | 0.84%   |
| Aflou                   | 1         | 0.84%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 24        | 34     | 19.83%  |
| Toshiba               | 21        | 22     | 17.36%  |
| WDC                   | 20        | 24     | 16.53%  |
| Hitachi               | 12        | 14     | 9.92%   |
| HGST                  | 12        | 17     | 9.92%   |
| Samsung Electronics   | 6         | 6      | 4.96%   |
| A-DATA Technology     | 5         | 5      | 4.13%   |
| SanDisk               | 3         | 3      | 2.48%   |
| LITEON                | 3         | 6      | 2.48%   |
| Lexar                 | 3         | 3      | 2.48%   |
| Unknown               | 2         | 3      | 1.65%   |
| Intel                 | 2         | 2      | 1.65%   |
| XPG                   | 1         | 1      | 0.83%   |
| SK Hynix              | 1         | 1      | 0.83%   |
| Realtek Semiconductor | 1         | 1      | 0.83%   |
| PNY                   | 1         | 1      | 0.83%   |
| Micron Technology     | 1         | 2      | 0.83%   |
| Kingston              | 1         | 1      | 0.83%   |
| HUAWEI                | 1         | 1      | 0.83%   |
| Fujitsu               | 1         | 2      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB              | 8         | 6.45%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 3.23%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 3         | 2.42%   |
| Toshiba MQ01ABD100 1TB                | 3         | 2.42%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 2.42%   |
| Seagate Expansion+ 2TB                | 3         | 2.42%   |
| HGST HTS545050A7E380 500GB            | 3         | 2.42%   |
| Unknown MMC Card  64GB                | 2         | 1.61%   |
| Seagate ST500VT000-1DK142 500GB       | 2         | 1.61%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 1.61%   |
| Seagate ST320LT020-9YG142 320GB       | 2         | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 1.61%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 1.61%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 1.61%   |
| HGST HTS725050A7E630 500GB            | 2         | 1.61%   |
| HGST HTS545050A7E680 500GB            | 2         | 1.61%   |
| HGST HTS541010A9E680 1TB              | 2         | 1.61%   |
| XPG SX950U 960GB                      | 1         | 0.81%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.81%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.81%   |
| WDC WDS100T2B0B-00YS70 1TB SSD        | 1         | 0.81%   |
| WDC WD5000LUCT-62RC2Y0 500GB          | 1         | 0.81%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.81%   |
| WDC WD5000LPVT-16G33T0 500GB          | 1         | 0.81%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 0.81%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 1         | 0.81%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 1         | 0.81%   |
| WDC WD5000BPVT-75HXZT3 500GB          | 1         | 0.81%   |
| WDC WD3200BVVT-63A26Y0 320GB          | 1         | 0.81%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 0.81%   |
| WDC WD3200BEKT-75PVMT1 320GB          | 1         | 0.81%   |
| WDC WD3200BEKT-75KA9T0 320GB          | 1         | 0.81%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 0.81%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.81%   |
| WDC WD10JPVX-08JC3T5 1TB              | 1         | 0.81%   |
| Unknown MMC Card  32GB                | 1         | 0.81%   |
| Toshiba MQ01ABF032 320GB              | 1         | 0.81%   |
| Toshiba MQ01ABD075 752GB              | 1         | 0.81%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 0.81%   |
| Toshiba MK7559GSXF 752GB              | 1         | 0.81%   |
| Toshiba MK6459GSXP 640GB              | 1         | 0.81%   |
| Toshiba MK5059GSXP 500GB              | 1         | 0.81%   |
| Toshiba MK4058GSX 400GB               | 1         | 0.81%   |
| Toshiba MK3259GSXP 320GB              | 1         | 0.81%   |
| Toshiba MK3259GSX 320GB               | 1         | 0.81%   |
| Toshiba MK2555GSXF 250GB              | 1         | 0.81%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 0.81%   |
| Seagate ST9500325AS 500GB             | 1         | 0.81%   |
| Seagate ST9320325AS 320GB             | 1         | 0.81%   |
| Seagate ST9250311CS 250GB             | 1         | 0.81%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 0.81%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB    | 1         | 0.81%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 0.81%   |
| SanDisk SSD U110 16GB                 | 1         | 0.81%   |
| SanDisk SDSSDHP256G 256GB             | 1         | 0.81%   |
| SanDisk iSSD P4 8GB                   | 1         | 0.81%   |
| Samsung SSD PM871 2.5 7mm 256GB       | 1         | 0.81%   |
| Samsung SSD PM851 mSATA 256GB         | 1         | 0.81%   |
| Samsung NVMe SSD Drive 500GB          | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 24        | 34     | 27.27%  |
| Toshiba | 21        | 22     | 23.86%  |
| WDC     | 18        | 21     | 20.45%  |
| Hitachi | 12        | 14     | 13.64%  |
| HGST    | 12        | 17     | 13.64%  |
| Fujitsu | 1         | 2      | 1.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 5         | 5      | 20.83%  |
| WDC                 | 3         | 3      | 12.5%   |
| SanDisk             | 3         | 3      | 12.5%   |
| LITEON              | 3         | 6      | 12.5%   |
| Samsung Electronics | 2         | 2      | 8.33%   |
| Lexar               | 2         | 2      | 8.33%   |
| Intel               | 2         | 2      | 8.33%   |
| XPG                 | 1         | 1      | 4.17%   |
| SK Hynix            | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 84        | 110    | 73.04%  |
| SSD     | 22        | 27     | 19.13%  |
| NVMe    | 6         | 8      | 5.22%   |
| MMC     | 2         | 3      | 1.74%   |
| Unknown | 1         | 1      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 133    | 88.07%  |
| NVMe | 6         | 8      | 5.5%    |
| SAS  | 5         | 5      | 4.59%   |
| MMC  | 2         | 3      | 1.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 78        | 107    | 72.9%   |
| 0.51-1.0   | 25        | 26     | 23.36%  |
| 1.01-2.0   | 4         | 4      | 3.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 33        | 29.2%   |
| 51-100     | 22        | 19.47%  |
| 101-250    | 17        | 15.04%  |
| 501-1000   | 14        | 12.39%  |
| 21-50      | 10        | 8.85%   |
| 1-20       | 10        | 8.85%   |
| 1001-2000  | 5         | 4.42%   |
| Unknown    | 2         | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 56        | 47.86%  |
| 21-50    | 21        | 17.95%  |
| 101-250  | 17        | 14.53%  |
| 51-100   | 10        | 8.55%   |
| 251-500  | 7         | 5.98%   |
| 501-1000 | 4         | 3.42%   |
| Unknown  | 2         | 1.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB    | 1         | 1      | 10%     |
| Toshiba MQ01ABF050 500GB        | 1         | 1      | 10%     |
| Toshiba MQ01ABD100 1TB          | 1         | 1      | 10%     |
| Seagate ST9320325AS 320GB       | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 10%     |
| Seagate ST500LM021-1KJ152 500GB | 1         | 1      | 10%     |
| Hitachi HTS723225L9A360 250GB   | 1         | 1      | 10%     |
| Hitachi HTS547564A9E384 640GB   | 1         | 1      | 10%     |
| Hitachi HTS542516K9SA00 160GB   | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB      | 1         | 3      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| Hitachi | 3         | 3      | 30%     |
| Toshiba | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| HGST    | 1         | 3      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| Hitachi | 3         | 3      | 30%     |
| Toshiba | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| HGST    | 1         | 3      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 100%    |

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
| Detected | 73        | 105    | 67.59%  |
| Works    | 25        | 32     | 23.15%  |
| Malfunc  | 10        | 12     | 9.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 95        | 87.16%  |
| AMD                   | 5         | 4.59%   |
| Samsung Electronics   | 4         | 3.67%   |
| Nvidia                | 2         | 1.83%   |
| Silicon Motion        | 1         | 0.92%   |
| Realtek Semiconductor | 1         | 0.92%   |
| Micron Technology     | 1         | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 18.02%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 13.51%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 9.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 7.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 5.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 5.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 3.6%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.8%    |
| Intel Atom Processor E3800 Series SATA IDE Controller                            | 2         | 1.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.9%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.9%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.9%    |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.9%    |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.9%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.9%    |
| Micron Non-Volatile memory controller                                            | 1         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.9%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.9%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 88        | 80%     |
| RAID | 12        | 10.91%  |
| NVMe | 6         | 5.45%   |
| IDE  | 4         | 3.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 99        | 95.19%  |
| AMD    | 5         | 4.81%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 3.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 3.85%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 2.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.88%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 2.88%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 2.88%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 3         | 2.88%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.92%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.92%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.92%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.92%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.92%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.92%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.92%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.92%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.96%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.96%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.96%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.96%   |
| Intel Pentium 3805U @ 1.90GHz               | 1         | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.96%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.96%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.96%   |
| Intel Core i7-2675QM CPU @ 2.20GHz          | 1         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i5-6198DU CPU @ 2.30GHz          | 1         | 0.96%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.96%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.96%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 0.96%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 0.96%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.96%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 0.96%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.96%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 0.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 0.96%   |
| Intel Core i3-2348M CPU @ 2.30GHz           | 1         | 0.96%   |
| Intel Core i3-2328M CPU @ 2.20GHz           | 1         | 0.96%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 0.96%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 0.96%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 0.96%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 0.96%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 0.96%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 29.81%  |
| Intel Core i3           | 30        | 28.85%  |
| Intel Core i7           | 17        | 16.35%  |
| Intel Pentium           | 6         | 5.77%   |
| Intel Celeron           | 5         | 4.81%   |
| Intel Pentium Dual-Core | 3         | 2.88%   |
| Intel Core 2 Duo        | 3         | 2.88%   |
| Intel Atom              | 3         | 2.88%   |
| Other                   | 1         | 0.96%   |
| AMD Ryzen 3             | 1         | 0.96%   |
| AMD E2                  | 1         | 0.96%   |
| AMD E1                  | 1         | 0.96%   |
| AMD Athlon II Dual-Core | 1         | 0.96%   |
| AMD A4                  | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 85        | 81.73%  |
| 4      | 17        | 16.35%  |
| 1      | 2         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 77.88%  |
| 1      | 23        | 22.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 102       | 98.08%  |
| Unknown        | 2         | 1.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 17.43%  |
| 0x306a9    | 16        | 14.68%  |
| 0x206a7    | 10        | 9.17%   |
| 0x40651    | 9         | 8.26%   |
| 0x406e3    | 8         | 7.34%   |
| 0x30678    | 7         | 6.42%   |
| 0x20655    | 7         | 6.42%   |
| 0x306d4    | 6         | 5.5%    |
| 0x806ea    | 4         | 3.67%   |
| 0x806e9    | 4         | 3.67%   |
| 0x1067a    | 4         | 3.67%   |
| 0x906e9    | 2         | 1.83%   |
| 0x30661    | 2         | 1.83%   |
| 0x20652    | 2         | 1.83%   |
| 0x806ec    | 1         | 0.92%   |
| 0x806c1    | 1         | 0.92%   |
| 0x506c9    | 1         | 0.92%   |
| 0x406c3    | 1         | 0.92%   |
| 0x306c3    | 1         | 0.92%   |
| 0x0810100b | 1         | 0.92%   |
| 0x0700010f | 1         | 0.92%   |
| 0x06006705 | 1         | 0.92%   |
| 0x05000119 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 19        | 18.27%  |
| Haswell     | 14        | 13.46%  |
| SandyBridge | 12        | 11.54%  |
| KabyLake    | 12        | 11.54%  |
| Westmere    | 9         | 8.65%   |
| Skylake     | 9         | 8.65%   |
| Silvermont  | 8         | 7.69%   |
| Penryn      | 6         | 5.77%   |
| Broadwell   | 6         | 5.77%   |
| Bonnell     | 2         | 1.92%   |
| Zen         | 1         | 0.96%   |
| TigerLake   | 1         | 0.96%   |
| K10         | 1         | 0.96%   |
| Jaguar      | 1         | 0.96%   |
| Goldmont    | 1         | 0.96%   |
| Excavator   | 1         | 0.96%   |
| Bobcat      | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 67.91%  |
| AMD    | 23        | 17.16%  |
| Nvidia | 20        | 14.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 13.43%  |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 8.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 8.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 5.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 5.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 5.22%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 4.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 3.73%   |
| Intel HD Graphics 620                                                                    | 5         | 3.73%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.73%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.24%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 1.49%   |
| Intel HD Graphics 630                                                                    | 2         | 1.49%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.49%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.49%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.49%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 1.49%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.75%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.75%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.75%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.75%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.75%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.75%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.75%   |
| Nvidia GK104GLM [Quadro K4000M]                                                          | 1         | 0.75%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.75%   |
| Nvidia GF108M [GeForce GT 620M]                                                          | 1         | 0.75%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.75%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.75%   |
| Intel HD Graphics 510                                                                    | 1         | 0.75%   |
| Intel HD Graphics 500                                                                    | 1         | 0.75%   |
| Intel HD Graphics                                                                        | 1         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.75%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.75%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.75%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.75%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.75%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.75%   |
| AMD Mars [Radeon HD 8730M]                                                               | 1         | 0.75%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.75%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 0.75%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 58.65%  |
| Intel + Nvidia | 16        | 15.38%  |
| Intel + AMD    | 14        | 13.46%  |
| 1 x AMD        | 9         | 8.65%   |
| 1 x Nvidia     | 4         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 93        | 88.57%  |
| Proprietary | 10        | 9.52%   |
| Unknown     | 2         | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 63.21%  |
| 1.01-2.0   | 19        | 17.92%  |
| 0.51-1.0   | 8         | 7.55%   |
| 0.01-0.5   | 8         | 7.55%   |
| 3.01-4.0   | 4         | 3.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 22        | 20.56%  |
| Samsung Electronics     | 21        | 19.63%  |
| AU Optronics            | 18        | 16.82%  |
| BOE                     | 13        | 12.15%  |
| Chimei Innolux          | 12        | 11.21%  |
| Chi Mei Optoelectronics | 6         | 5.61%   |
| Hewlett-Packard         | 3         | 2.8%    |
| Apple                   | 2         | 1.87%   |
| Sharp                   | 1         | 0.93%   |
| PANDA                   | 1         | 0.93%   |
| MStar                   | 1         | 0.93%   |
| LGD                     | 1         | 0.93%   |
| Lenovo                  | 1         | 0.93%   |
| InnoLux Display         | 1         | 0.93%   |
| Goldstar                | 1         | 0.93%   |
| BenQ                    | 1         | 0.93%   |
| AOC                     | 1         | 0.93%   |
| Acer                    | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch      | 3         | 2.8%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 3         | 2.8%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 2.8%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 2         | 1.87%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch      | 2         | 1.87%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 2         | 1.87%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch      | 2         | 1.87%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch             | 2         | 1.87%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch               | 2         | 1.87%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 1.87%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 2         | 1.87%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 2         | 1.87%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 2         | 1.87%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 1.87%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch          | 2         | 1.87%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                      | 2         | 1.87%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 2         | 1.87%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 2         | 1.87%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.93%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch         | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC494A 1366x768 344x193mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3442 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3241 1024x768 246x184mm 12.1-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                   | 1         | 0.93%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                          | 1         | 0.93%   |
| LGD LCD Monitor 1600x900                                                  | 1         | 0.93%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD01F5 1280x800 304x190mm 14.1-inch               | 1         | 0.93%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 1         | 0.93%   |
| InnoLux Display LCD Monitor INL0006 1366x768 344x194mm 15.5-inch          | 1         | 0.93%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch                 | 1         | 0.93%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch               | 1         | 0.93%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch                | 1         | 0.93%   |
| Goldstar L1720B GSM4372 1280x1024 338x270mm 17.0-inch                     | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch          | 1         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch           | 1         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 1         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch  | 1         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 72        | 69.23%  |
| 1920x1080 (FHD)  | 19        | 18.27%  |
| 1600x900 (HD+)   | 3         | 2.88%   |
| 1280x800 (WXGA)  | 3         | 2.88%   |
| 3840x2160 (4K)   | 2         | 1.92%   |
| 1440x900 (WXGA+) | 2         | 1.92%   |
| 1680x945         | 1         | 0.96%   |
| 1280x1024 (SXGA) | 1         | 0.96%   |
| 1024x600         | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 71        | 66.36%  |
| 13      | 10        | 9.35%   |
| 14      | 6         | 5.61%   |
| 18      | 4         | 3.74%   |
| 17      | 4         | 3.74%   |
| 12      | 4         | 3.74%   |
| 52      | 1         | 0.93%   |
| 27      | 1         | 0.93%   |
| 24      | 1         | 0.93%   |
| 21      | 1         | 0.93%   |
| 19      | 1         | 0.93%   |
| 11      | 1         | 0.93%   |
| 10      | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 79.25%  |
| 201-300     | 8         | 7.55%   |
| 401-500     | 5         | 4.72%   |
| 351-400     | 5         | 4.72%   |
| 501-600     | 2         | 1.89%   |
| 1001-1500   | 1         | 0.94%   |
| Unknown     | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 93        | 93%     |
| 16/10   | 4         | 4%      |
| 5/4     | 1         | 1%      |
| 3/2     | 1         | 1%      |
| Unknown | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 66.36%  |
| 81-90          | 14        | 13.08%  |
| 141-150        | 5         | 4.67%   |
| 61-70          | 4         | 3.74%   |
| 71-80          | 2         | 1.87%   |
| 151-200        | 2         | 1.87%   |
| 121-130        | 2         | 1.87%   |
| More than 1000 | 1         | 0.93%   |
| 51-60          | 1         | 0.93%   |
| 41-50          | 1         | 0.93%   |
| 301-350        | 1         | 0.93%   |
| 201-250        | 1         | 0.93%   |
| 131-140        | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 67        | 63.21%  |
| 121-160 | 21        | 19.81%  |
| 51-100  | 14        | 13.21%  |
| 161-240 | 2         | 1.89%   |
| 1-50    | 1         | 0.94%   |
| Unknown | 1         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 95        | 90.48%  |
| 2     | 8         | 7.62%   |
| 0     | 2         | 1.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 34.24%  |
| Intel                    | 36        | 19.57%  |
| Qualcomm Atheros         | 34        | 18.48%  |
| Broadcom                 | 25        | 13.59%  |
| Ralink Technology        | 7         | 3.8%    |
| Ralink                   | 5         | 2.72%   |
| Samsung Electronics      | 2         | 1.09%   |
| MEDIATEK                 | 2         | 1.09%   |
| Huawei Technologies      | 2         | 1.09%   |
| Broadcom Limited         | 2         | 1.09%   |
| Xiaomi                   | 1         | 0.54%   |
| Sierra Wireless          | 1         | 0.54%   |
| Nvidia                   | 1         | 0.54%   |
| Marvell Technology Group | 1         | 0.54%   |
| LG Electronics           | 1         | 0.54%   |
| D-Link System            | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 16.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 10.91%  |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 5.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.82%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.82%   |
| Intel Wireless 8260                                               | 3         | 1.36%   |
| Intel Wireless 7260                                               | 3         | 1.36%   |
| Intel Wireless 3160                                               | 3         | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.36%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.36%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.91%   |
| Intel Wireless 7265                                               | 2         | 0.91%   |
| Intel WiFi Link 5100                                              | 2         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.91%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.91%   |
| Intel Centrino Wireless-N 135                                     | 2         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.91%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.91%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.45%   |
| Sierra Wireless EM7305                                            | 1         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.45%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.45%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.45%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.45%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.45%   |
| MediaTek NOA N2                                                   | 1         | 0.45%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.45%   |
| Intel Wireless 3165                                               | 1         | 0.45%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.45%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 29.82%  |
| Qualcomm Atheros      | 31        | 27.19%  |
| Broadcom              | 20        | 17.54%  |
| Realtek Semiconductor | 13        | 11.4%   |
| Ralink Technology     | 7         | 6.14%   |
| Ralink                | 5         | 4.39%   |
| Sierra Wireless       | 1         | 0.88%   |
| MEDIATEK              | 1         | 0.88%   |
| D-Link System         | 1         | 0.88%   |
| Broadcom Limited      | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 12        | 10.53%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 8.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 8         | 7.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 5.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 3.51%   |
| Ralink MT7601U Wireless Adapter                                      | 4         | 3.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 3.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 3.51%   |
| Intel Wireless 8265 / 8275                                           | 4         | 3.51%   |
| Intel Wireless 8260                                                  | 3         | 2.63%   |
| Intel Wireless 7260                                                  | 3         | 2.63%   |
| Intel Wireless 3160                                                  | 3         | 2.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 2.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.75%   |
| Intel Wireless 7265                                                  | 2         | 1.75%   |
| Intel WiFi Link 5100                                                 | 2         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 1.75%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.75%   |
| Intel Centrino Wireless-N 135                                        | 2         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.75%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.75%   |
| Sierra Wireless EM7305                                               | 1         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.88%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.88%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 0.88%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 0.88%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter        | 1         | 0.88%   |
| Intel Wireless 3165                                                  | 1         | 0.88%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.88%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 0.88%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                 | 1         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 0.88%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 0.88%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 1         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 0.88%   |
| Broadcom BCM43227 802.11b/g/n                                        | 1         | 0.88%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 0.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 58.65%  |
| Intel                    | 21        | 20.19%  |
| Broadcom                 | 7         | 6.73%   |
| Qualcomm Atheros         | 6         | 5.77%   |
| Samsung Electronics      | 2         | 1.92%   |
| Xiaomi                   | 1         | 0.96%   |
| Nvidia                   | 1         | 0.96%   |
| MediaTek                 | 1         | 0.96%   |
| Marvell Technology Group | 1         | 0.96%   |
| LG Electronics           | 1         | 0.96%   |
| Huawei Technologies      | 1         | 0.96%   |
| Broadcom Limited         | 1         | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 35.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 22.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 3.81%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.86%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.9%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.95%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.95%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.95%   |
| MediaTek NOA N2                                                   | 1         | 0.95%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.95%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.95%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.95%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.95%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.95%   |
| Huawei E353/E3131                                                 | 1         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.95%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.95%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.95%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 103       | 50.99%  |
| Ethernet | 98        | 48.51%  |
| Modem    | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 72.44%  |
| Ethernet | 35        | 27.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 98        | 92.45%  |
| 1     | 6         | 5.66%   |
| 0     | 2         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 28%     |
| Qualcomm Atheros Communications | 11        | 14.67%  |
| Broadcom                        | 9         | 12%     |
| Realtek Semiconductor           | 7         | 9.33%   |
| Lite-On Technology              | 5         | 6.67%   |
| Foxconn / Hon Hai               | 5         | 6.67%   |
| Ralink                          | 4         | 5.33%   |
| Foxconn International           | 3         | 4%      |
| Dell                            | 3         | 4%      |
| IMC Networks                    | 2         | 2.67%   |
| Apple                           | 2         | 2.67%   |
| Toshiba                         | 1         | 1.33%   |
| Chicony Electronics             | 1         | 1.33%   |
| Alps Electric                   | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 15        | 20%     |
| Qualcomm Atheros  Bluetooth Device                | 5         | 6.67%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 5         | 6.67%   |
| Ralink RT3290 Bluetooth                           | 4         | 5.33%   |
| Realtek Bluetooth Radio                           | 3         | 4%      |
| Qualcomm Atheros AR3011 Bluetooth                 | 3         | 4%      |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 4%      |
| Broadcom BCM43142 Bluetooth 4.0                   | 3         | 4%      |
| Realtek RTL8723B Bluetooth                        | 2         | 2.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 2.67%   |
| IMC Networks Bluetooth Device                     | 2         | 2.67%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 2.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 2         | 2.67%   |
| Apple Bluetooth Host Controller                   | 2         | 2.67%   |
| Toshiba Bluetooth Device                          | 1         | 1.33%   |
| Realtek RTL8821A Bluetooth                        | 1         | 1.33%   |
| Realtek 802.11n WLAN Adapter                      | 1         | 1.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.33%   |
| Lite-On Wireless_Device                           | 1         | 1.33%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]       | 1         | 1.33%   |
| Lite-On BCM43142A0                                | 1         | 1.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 1         | 1.33%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 1.33%   |
| Foxconn / Hon Hai BCM43142A0                      | 1         | 1.33%   |
| Foxconn / Hon Hai Acer Module                     | 1         | 1.33%   |
| Dell Wireless 365 Bluetooth                       | 1         | 1.33%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.33%   |
| Dell BCM20702A0 Bluetooth Module                  | 1         | 1.33%   |
| Chicony Bluetooth (RTL8723BE)                     | 1         | 1.33%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 1.33%   |
| Broadcom Bluetooth Device                         | 1         | 1.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 1         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 1.33%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 96        | 84.96%  |
| AMD               | 11        | 9.73%   |
| Nvidia            | 5         | 4.42%   |
| Texas Instruments | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 16.55%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 12.95%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 7.91%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 7.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 6.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.32%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 4.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.44%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.44%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.44%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.44%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.44%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.72%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.72%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.72%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.72%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.72%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.72%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.72%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 17        | 30.36%  |
| Samsung Electronics | 17        | 30.36%  |
| Micron Technology   | 8         | 14.29%  |
| Unknown             | 6         | 10.71%  |
| Kingston            | 2         | 3.57%   |
| Team                | 1         | 1.79%   |
| Nanya Technology    | 1         | 1.79%   |
| Elpida              | 1         | 1.79%   |
| Crucial             | 1         | 1.79%   |
| ASint Technology    | 1         | 1.79%   |
| A-DATA Technology   | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 6.45%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 4.84%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 3         | 4.84%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 2         | 3.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 3.23%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 1.61%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 1         | 1.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 1.61%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s     | 1         | 1.61%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2400MT/s          | 1         | 1.61%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s | 1         | 1.61%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 1.61%   |
| SK Hynix RAM HMA425S6BJR6N-UH 2GB SODIMM DDR4 2667MT/s    | 1         | 1.61%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s  | 1         | 1.61%   |
| Samsung RAM M471B5273EB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| Samsung RAM M471B5273DH0-YK0 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Samsung RAM M471B1G73BH0-CK0 8192MB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 1.61%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s     | 1         | 1.61%   |
| Nanya RAM M2S4G64CC88B4N-DI 4GB SODIMM DDR3 1600MT/s      | 1         | 1.61%   |
| Micron RAM MT41K512M8RH-125:E 4GB SODIMM DDR3 1600MT/s    | 1         | 1.61%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s             | 1         | 1.61%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s  | 1         | 1.61%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Micron RAM 16JTF1G64HZ-1G6D1 8GB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3             | 1         | 1.61%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.61%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s   | 1         | 1.61%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s     | 1         | 1.61%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s   | 1         | 1.61%   |
| ASint RAM C1RE5SR4HN1 2GB SODIMM SDRAM 4199MT/s           | 1         | 1.61%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2400MT/s            | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 34        | 72.34%  |
| DDR4   | 11        | 23.4%   |
| SDRAM  | 1         | 2.13%   |
| LPDDR4 | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 46        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 26        | 48.15%  |
| 8192  | 14        | 25.93%  |
| 2048  | 12        | 22.22%  |
| 32768 | 1         | 1.85%   |
| 16384 | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 53.06%  |
| 2667    | 8         | 16.33%  |
| 1334    | 3         | 6.12%   |
| 3266    | 2         | 4.08%   |
| 2400    | 2         | 4.08%   |
| 1333    | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| 4199    | 1         | 2.04%   |
| 3200    | 1         | 2.04%   |
| 2133    | 1         | 2.04%   |
| 1067    | 1         | 2.04%   |

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
| Chicony Electronics                    | 23        | 24.47%  |
| Microdia                               | 14        | 14.89%  |
| Realtek Semiconductor                  | 9         | 9.57%   |
| Acer                                   | 8         | 8.51%   |
| Sunplus Innovation Technology          | 7         | 7.45%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 7.45%   |
| Suyin                                  | 5         | 5.32%   |
| Syntek                                 | 4         | 4.26%   |
| IMC Networks                           | 3         | 3.19%   |
| Apple                                  | 3         | 3.19%   |
| Silicon Motion                         | 2         | 2.13%   |
| Quanta                                 | 2         | 2.13%   |
| Lite-On Technology                     | 2         | 2.13%   |
| Samsung Electronics                    | 1         | 1.06%   |
| Primax Electronics                     | 1         | 1.06%   |
| Pixart Imaging                         | 1         | 1.06%   |
| Aveo Technology                        | 1         | 1.06%   |
| Alcor Micro                            | 1         | 1.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Acer Lenovo EasyCamera                              | 6         | 6.38%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 4.26%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 3         | 3.19%   |
| Microdia Integrated_Webcam_HD                       | 3         | 3.19%   |
| Microdia Integrated Webcam                          | 3         | 3.19%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 3.19%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.13%   |
| Suyin HP Truevision HD                              | 2         | 2.13%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 2         | 2.13%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.13%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 2.13%   |
| Chicony Integrated Camera                           | 2         | 2.13%   |
| Chicony HD WebCam                                   | 2         | 2.13%   |
| Chicony Acer CrystalEye Webcam                      | 2         | 2.13%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 2.13%   |
| Syntek USB2.0 Camera                                | 1         | 1.06%   |
| Syntek EasyCamera                                   | 1         | 1.06%   |
| Suyin WebCam                                        | 1         | 1.06%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.06%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.06%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.06%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 1.06%   |
| Sunplus Dell HD Webcam                              | 1         | 1.06%   |
| Silicon Motion WebCam SC-13HDL11431N                | 1         | 1.06%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.06%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 1.06%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 1.06%   |
| Realtek USB Camera                                  | 1         | 1.06%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.06%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.06%   |
| Realtek Integrated Webcam                           | 1         | 1.06%   |
| Realtek HP Webcam                                   | 1         | 1.06%   |
| Realtek HP Truevision HD                            | 1         | 1.06%   |
| Realtek HD Webcam - Realtek                         | 1         | 1.06%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 1.06%   |
| Quanta HD Webcam                                    | 1         | 1.06%   |
| Quanta HD User Facing                               | 1         | 1.06%   |
| Primax webcam                                       | 1         | 1.06%   |
| Pixart Imaging VGA Webcam                           | 1         | 1.06%   |
| Microdia Sony Visual Communication Camera           | 1         | 1.06%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 1.06%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.06%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.06%   |
| Microdia Integrated Webcam HD                       | 1         | 1.06%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.06%   |
| Lite-On Integrated Camera                           | 1         | 1.06%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.06%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.06%   |
| IMC Networks Integrated Webcam                      | 1         | 1.06%   |
| Chicony WebCam                                      | 1         | 1.06%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.06%   |
| Chicony Sony Visual Communication Camera            | 1         | 1.06%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.06%   |
| Chicony HP Webcam                                   | 1         | 1.06%   |
| Chicony HP Truevision HD                            | 1         | 1.06%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 1.06%   |
| Chicony HP HD Camera                                | 1         | 1.06%   |
| Chicony Front Camera                                | 1         | 1.06%   |
| Chicony FJ Camera                                   | 1         | 1.06%   |
| Chicony CNA7157                                     | 1         | 1.06%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 8         | 72.73%  |
| AuthenTec        | 2         | 18.18%  |
| Synaptics        | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 36.36%  |
| Validity Sensors VFS491                                    | 2         | 18.18%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 18.18%  |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| AuthenTec AES2810                                          | 1         | 9.09%   |
| AuthenTec AES1600                                          | 1         | 9.09%   |

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
| 0     | 69        | 65.09%  |
| 1     | 33        | 31.13%  |
| 2     | 4         | 3.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 11        | 26.19%  |
| Net/wireless       | 8         | 19.05%  |
| Chipcard           | 8         | 19.05%  |
| Graphics card      | 6         | 14.29%  |
| Bluetooth          | 4         | 9.52%   |
| Storage            | 2         | 4.76%   |
| Net/ethernet       | 2         | 4.76%   |
| Card reader        | 1         | 2.38%   |

