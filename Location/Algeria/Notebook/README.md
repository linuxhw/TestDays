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

Total: 264

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | UL80VT                      | [1d3c36ccf4](https://linux-hardware.org/?probe=1d3c36ccf4) | Sep 25, 2023 |
| Dell          | Inspiron N5110              | [e98b118b85](https://linux-hardware.org/?probe=e98b118b85) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Dell          | Inspiron N5110              | [6903c7fc50](https://linux-hardware.org/?probe=6903c7fc50) | Sep 18, 2023 |
| Dell          | Inspiron 15-3552            | [eaf6dbaf3e](https://linux-hardware.org/?probe=eaf6dbaf3e) | Sep 09, 2023 |
| Dell          | Latitude E5470              | [a404e86063](https://linux-hardware.org/?probe=a404e86063) | Sep 08, 2023 |
| ASUSTek       | UL80VT                      | [daa7101bf4](https://linux-hardware.org/?probe=daa7101bf4) | Sep 07, 2023 |
| Unknown       | TBYF-1014WIN32              | [11ef48e0c0](https://linux-hardware.org/?probe=11ef48e0c0) | Sep 06, 2023 |
| ASUSTek       | UL80VT                      | [aec41416ac](https://linux-hardware.org/?probe=aec41416ac) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| ASUSTek       | UL80VT                      | [858a6c3ea1](https://linux-hardware.org/?probe=858a6c3ea1) | Aug 26, 2023 |
| Dell          | Latitude 7430               | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| MSI           | CR610M                      | [e2432b72a5](https://linux-hardware.org/?probe=e2432b72a5) | Aug 22, 2023 |
| Dell          | Latitude 7430               | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| Lenovo        | G50-70 20351                | [439b66555d](https://linux-hardware.org/?probe=439b66555d) | Aug 17, 2023 |
| Lenovo        | G50-70 20351                | [e11ae0d2b7](https://linux-hardware.org/?probe=e11ae0d2b7) | Aug 17, 2023 |
| Dell          | Inspiron N5110              | [8218626de4](https://linux-hardware.org/?probe=8218626de4) | Aug 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [e6c5dadeef](https://linux-hardware.org/?probe=e6c5dadeef) | Jul 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b72c043646](https://linux-hardware.org/?probe=b72c043646) | Jul 13, 2023 |
| Dell          | Inspiron N5110              | [355ccda3d5](https://linux-hardware.org/?probe=355ccda3d5) | Jul 05, 2023 |
| Dell          | Inspiron N5110              | [354dd05c7f](https://linux-hardware.org/?probe=354dd05c7f) | Jul 01, 2023 |
| Dell          | Inspiron N5110              | [b465607eea](https://linux-hardware.org/?probe=b465607eea) | Jun 30, 2023 |
| Dell          | Inspiron N5110              | [0668932749](https://linux-hardware.org/?probe=0668932749) | Jun 30, 2023 |
| Lenovo        | ThinkPad W520 428425G       | [48d9a1b9fc](https://linux-hardware.org/?probe=48d9a1b9fc) | Jun 26, 2023 |
| Lenovo        | ThinkPad W520 428425G       | [813d5adfd5](https://linux-hardware.org/?probe=813d5adfd5) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| ASUSTek       | N75SF                       | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| Dell          | Inspiron N5110              | [2d5e375a3d](https://linux-hardware.org/?probe=2d5e375a3d) | May 09, 2023 |
| Dell          | Inspiron 15-3567            | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| HP            | Notebook                    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| HP            | Laptop 15-bs1xx             | [e68f2bc46e](https://linux-hardware.org/?probe=e68f2bc46e) | Apr 27, 2023 |
| Toshiba       | Satellite Pro A100          | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Dell          | Inspiron N5110              | [48b2d021fa](https://linux-hardware.org/?probe=48b2d021fa) | Apr 17, 2023 |
| Dell          | Inspiron N5110              | [065b7d4c01](https://linux-hardware.org/?probe=065b7d4c01) | Apr 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| Dell          | Inspiron N5110              | [a3ecc0f893](https://linux-hardware.org/?probe=a3ecc0f893) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [e27fc333c6](https://linux-hardware.org/?probe=e27fc333c6) | Apr 05, 2023 |
| Toshiba       | Satellite C55-B             | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| Dell          | Inspiron N5110              | [aa74b25c97](https://linux-hardware.org/?probe=aa74b25c97) | Apr 02, 2023 |
| Dell          | Latitude E7470              | [ee66bc49a5](https://linux-hardware.org/?probe=ee66bc49a5) | Apr 01, 2023 |
| Dell          | Inspiron N5110              | [7ff133a50e](https://linux-hardware.org/?probe=7ff133a50e) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | [6b3c579924](https://linux-hardware.org/?probe=6b3c579924) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| HP            | EliteBook 8570p             | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| Dell          | Inspiron 15-3567            | [f6b6b24623](https://linux-hardware.org/?probe=f6b6b24623) | Feb 24, 2023 |
| Dell          | Latitude E7470              | [6b5f9db086](https://linux-hardware.org/?probe=6b5f9db086) | Feb 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [28a0794b08](https://linux-hardware.org/?probe=28a0794b08) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e87f489185](https://linux-hardware.org/?probe=e87f489185) | Feb 20, 2023 |
| HP            | Notebook                    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Dell          | Latitude E7470              | [5c8d26c4ff](https://linux-hardware.org/?probe=5c8d26c4ff) | Feb 05, 2023 |
| Dell          | Latitude E7470              | [d68227808b](https://linux-hardware.org/?probe=d68227808b) | Feb 05, 2023 |
| HP            | EliteBook Revolve 810 G3    | [1f55ca148f](https://linux-hardware.org/?probe=1f55ca148f) | Jan 30, 2023 |
| Dell          | Vostro 1520                 | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [5169fb5013](https://linux-hardware.org/?probe=5169fb5013) | Jan 17, 2023 |
| Acer          | Aspire M3-581T              | [f0ed3b4989](https://linux-hardware.org/?probe=f0ed3b4989) | Jan 14, 2023 |
| Acer          | Calpella                    | [108843a25a](https://linux-hardware.org/?probe=108843a25a) | Jan 14, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Sony          | VGN-NS10J_S                 | [3789038010](https://linux-hardware.org/?probe=3789038010) | Jan 04, 2023 |
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
| Ubuntu 20.04        | 36        | 20.45%  |
| Ubuntu 18.04        | 13        | 7.39%   |
| OpenMandriva 4.2    | 9         | 5.11%   |
| Linux Mint 20.1     | 6         | 3.41%   |
| Ubuntu 22.04        | 5         | 2.84%   |
| OpenMandriva 4.3    | 5         | 2.84%   |
| KDE neon 20.04      | 5         | 2.84%   |
| Pop!_OS 20.04       | 4         | 2.27%   |
| Fedora 35           | 4         | 2.27%   |
| Zorin 16            | 3         | 1.7%    |
| Xubuntu 20.04       | 3         | 1.7%    |
| OpenMandriva 23.09  | 3         | 1.7%    |
| OpenMandriva 23.01  | 3         | 1.7%    |
| Manjaro             | 3         | 1.7%    |
| Debian 11           | 3         | 1.7%    |
| ArcoLinux Rolling   | 3         | 1.7%    |
| Arch                | 3         | 1.7%    |
| Ubuntu 21.10        | 2         | 1.14%   |
| Ubuntu 20.10        | 2         | 1.14%   |
| Ubuntu 19.10        | 2         | 1.14%   |
| ROSA R11            | 2         | 1.14%   |
| Pop!_OS 22.04       | 2         | 1.14%   |
| OpenMandriva 23.08  | 2         | 1.14%   |
| Kubuntu 20.04       | 2         | 1.14%   |
| KDE neon 22.04      | 2         | 1.14%   |
| Kali 2021.1         | 2         | 1.14%   |
| Fedora 38           | 2         | 1.14%   |
| Fedora 37           | 2         | 1.14%   |
| BlackPanther 18.1   | 2         | 1.14%   |
| Zorin 15            | 1         | 0.57%   |
| Xubuntu 22.04       | 1         | 0.57%   |
| UbuntuDDE 20.04     | 1         | 0.57%   |
| Ubuntu Unity 16.04  | 1         | 0.57%   |
| Ubuntu Budgie 22.04 | 1         | 0.57%   |
| Ubuntu 23.04        | 1         | 0.57%   |
| Ubuntu 22.10        | 1         | 0.57%   |
| Ubuntu 21.04        | 1         | 0.57%   |
| Ubuntu 16.04        | 1         | 0.57%   |
| ROSA R8.1           | 1         | 0.57%   |
| ROSA R10            | 1         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 63        | 36.84%  |
| OpenMandriva  | 22        | 12.87%  |
| Linux Mint    | 12        | 7.02%   |
| Fedora        | 11        | 6.43%   |
| Pop!_OS       | 7         | 4.09%   |
| KDE neon      | 7         | 4.09%   |
| Kali          | 5         | 2.92%   |
| Zorin         | 4         | 2.34%   |
| Xubuntu       | 4         | 2.34%   |
| ROSA          | 4         | 2.34%   |
| Manjaro       | 4         | 2.34%   |
| Debian        | 4         | 2.34%   |
| ArcoLinux     | 3         | 1.75%   |
| Arch          | 3         | 1.75%   |
| Parrot        | 2         | 1.17%   |
| Kubuntu       | 2         | 1.17%   |
| BlackPanther  | 2         | 1.17%   |
| UbuntuDDE     | 1         | 0.58%   |
| Ubuntu Unity  | 1         | 0.58%   |
| Ubuntu Budgie | 1         | 0.58%   |
| Pear OS       | 1         | 0.58%   |
| MX            | 1         | 0.58%   |
| Gentoo        | 1         | 0.58%   |
| Garuda Linux  | 1         | 0.58%   |
| EndeavourOS   | 1         | 0.58%   |
| Clear Linux   | 1         | 0.58%   |
| CentOS        | 1         | 0.58%   |
| Artix         | 1         | 0.58%   |
| ArchLabs      | 1         | 0.58%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 9         | 4.81%   |
| 5.16.7-desktop-1omv4003  | 5         | 2.67%   |
| 5.4.0-72-generic         | 4         | 2.14%   |
| 5.4.0-42-generic         | 4         | 2.14%   |
| 5.4.0-29-generic         | 4         | 2.14%   |
| 5.4.0-54-generic         | 3         | 1.6%    |
| 5.15.0-56-generic        | 3         | 1.6%    |
| 5.13.0-30-generic        | 3         | 1.6%    |
| 6.5.0-desktop-1omv2390   | 2         | 1.07%   |
| 6.1.1-desktop-1omv2290   | 2         | 1.07%   |
| 5.8.0-50-generic         | 2         | 1.07%   |
| 5.8.0-44-generic         | 2         | 1.07%   |
| 5.4.0-80-generic         | 2         | 1.07%   |
| 5.4.0-7625-generic       | 2         | 1.07%   |
| 5.4.0-65-generic         | 2         | 1.07%   |
| 5.4.0-56-generic         | 2         | 1.07%   |
| 5.4.0-52-generic         | 2         | 1.07%   |
| 5.4.0-48-generic         | 2         | 1.07%   |
| 5.4.0-33-generic         | 2         | 1.07%   |
| 5.3.0-40-generic         | 2         | 1.07%   |
| 5.15.0-83-generic        | 2         | 1.07%   |
| 5.15.0-58-generic        | 2         | 1.07%   |
| 5.15.0-47-generic        | 2         | 1.07%   |
| 5.13.0-44-generic        | 2         | 1.07%   |
| 5.11.0-27-generic        | 2         | 1.07%   |
| 5.11.0-25-generic        | 2         | 1.07%   |
| 4.18.16-desktop-1bP      | 2         | 1.07%   |
| 6.5.3-desktop-1omv2390   | 1         | 0.53%   |
| 6.4.8-desktop-2omv2390   | 1         | 0.53%   |
| 6.4.6-76060406-generic   | 1         | 0.53%   |
| 6.4.14-200.fc38.x86_64   | 1         | 0.53%   |
| 6.4.11-desktop-1omv2390  | 1         | 0.53%   |
| 6.3.4-arch1-1            | 1         | 0.53%   |
| 6.3.0-kali1-amd64        | 1         | 0.53%   |
| 6.2.8-200.fc37.x86_64    | 1         | 0.53%   |
| 6.2.8-060208-generic     | 1         | 0.53%   |
| 6.2.6-desktop-1omv2390   | 1         | 0.53%   |
| 6.2.6-76060206-generic   | 1         | 0.53%   |
| 6.2.14-300.fc38.x86_64   | 1         | 0.53%   |
| 6.2.0-20-generic         | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 37        | 20.9%   |
| 5.15.0  | 16        | 9.04%   |
| 5.8.0   | 9         | 5.08%   |
| 5.10.14 | 9         | 5.08%   |
| 5.13.0  | 8         | 4.52%   |
| 5.3.0   | 7         | 3.95%   |
| 5.11.0  | 7         | 3.95%   |
| 5.16.7  | 5         | 2.82%   |
| 5.10.0  | 5         | 2.82%   |
| 4.15.0  | 5         | 2.82%   |
| 5.0.0   | 4         | 2.26%   |
| 4.18.16 | 3         | 1.69%   |
| 6.5.0   | 2         | 1.13%   |
| 6.2.8   | 2         | 1.13%   |
| 6.2.6   | 2         | 1.13%   |
| 6.1.1   | 2         | 1.13%   |
| 6.1.0   | 2         | 1.13%   |
| 5.19.0  | 2         | 1.13%   |
| 5.15.7  | 2         | 1.13%   |
| 4.4.0   | 2         | 1.13%   |
| 6.5.3   | 1         | 0.56%   |
| 6.4.8   | 1         | 0.56%   |
| 6.4.6   | 1         | 0.56%   |
| 6.4.14  | 1         | 0.56%   |
| 6.4.11  | 1         | 0.56%   |
| 6.3.4   | 1         | 0.56%   |
| 6.3.0   | 1         | 0.56%   |
| 6.2.14  | 1         | 0.56%   |
| 6.2.0   | 1         | 0.56%   |
| 6.1.9   | 1         | 0.56%   |
| 6.1.50  | 1         | 0.56%   |
| 6.1.4   | 1         | 0.56%   |
| 6.1.12  | 1         | 0.56%   |
| 6.0.7   | 1         | 0.56%   |
| 6.0.12  | 1         | 0.56%   |
| 5.9.11  | 1         | 0.56%   |
| 5.7.17  | 1         | 0.56%   |
| 5.7.0   | 1         | 0.56%   |
| 5.6.0   | 1         | 0.56%   |
| 5.4.72  | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 39        | 22.16%  |
| 5.15    | 23        | 13.07%  |
| 5.10    | 17        | 9.66%   |
| 5.8     | 9         | 5.11%   |
| 5.13    | 9         | 5.11%   |
| 5.11    | 8         | 4.55%   |
| 6.1     | 7         | 3.98%   |
| 5.3     | 7         | 3.98%   |
| 6.2     | 6         | 3.41%   |
| 5.16    | 6         | 3.41%   |
| 4.15    | 5         | 2.84%   |
| 6.4     | 4         | 2.27%   |
| 5.19    | 4         | 2.27%   |
| 5.0     | 4         | 2.27%   |
| 4.18    | 4         | 2.27%   |
| 6.5     | 3         | 1.7%    |
| 5.12    | 3         | 1.7%    |
| 6.3     | 2         | 1.14%   |
| 6.0     | 2         | 1.14%   |
| 5.7     | 2         | 1.14%   |
| 5.17    | 2         | 1.14%   |
| 4.9     | 2         | 1.14%   |
| 4.4     | 2         | 1.14%   |
| 4.19    | 2         | 1.14%   |
| 5.9     | 1         | 0.57%   |
| 5.6     | 1         | 0.57%   |
| 5.14    | 1         | 0.57%   |
| 3.10    | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 151       | 96.79%  |
| i686   | 5         | 3.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 78        | 46.99%  |
| KDE5             | 35        | 21.08%  |
| XFCE             | 15        | 9.04%   |
| Unknown          | 13        | 7.83%   |
| X-Cinnamon       | 7         | 4.22%   |
| MATE             | 5         | 3.01%   |
| KDE              | 4         | 2.41%   |
| KDE4             | 2         | 1.2%    |
| Unity            | 1         | 0.6%    |
| LXQt             | 1         | 0.6%    |
| lightdm-xsession | 1         | 0.6%    |
| i3               | 1         | 0.6%    |
| Deepin           | 1         | 0.6%    |
| Cinnamon         | 1         | 0.6%    |
| Budgie           | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 127       | 79.38%  |
| Wayland | 26        | 16.25%  |
| Unknown | 6         | 3.75%   |
| Tty     | 1         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 82        | 49.4%   |
| SDDM    | 29        | 17.47%  |
| GDM     | 20        | 12.05%  |
| LightDM | 17        | 10.24%  |
| GDM3    | 11        | 6.63%   |
| TDM     | 4         | 2.41%   |
| KDM     | 2         | 1.2%    |
| SLiM    | 1         | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 72        | 45%     |
| fr_FR   | 58        | 36.25%  |
| Unknown | 13        | 8.13%   |
| en_GB   | 6         | 3.75%   |
| C       | 4         | 2.5%    |
| ar_DZ   | 3         | 1.88%   |
| fr_BE   | 2         | 1.25%   |
| fr_DZ   | 1         | 0.63%   |
| ar_EG   | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 106       | 65.84%  |
| EFI  | 55        | 34.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 120       | 73.17%  |
| Overlay | 21        | 12.8%   |
| Btrfs   | 13        | 7.93%   |
| Unknown | 4         | 2.44%   |
| Ext2    | 3         | 1.83%   |
| Xfs     | 1         | 0.61%   |
| Tmpfs   | 1         | 0.61%   |
| Ext3    | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 92        | 57.14%  |
| GPT     | 41        | 25.47%  |
| MBR     | 28        | 17.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 134       | 81.71%  |
| Yes       | 30        | 18.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 50.63%  |
| Yes       | 79        | 49.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 38        | 24.36%  |
| Hewlett-Packard     | 30        | 19.23%  |
| Lenovo              | 25        | 16.03%  |
| ASUSTek Computer    | 16        | 10.26%  |
| Acer                | 13        | 8.33%   |
| Toshiba             | 11        | 7.05%   |
| Sony                | 7         | 4.49%   |
| Samsung Electronics | 3         | 1.92%   |
| Packard Bell        | 3         | 1.92%   |
| Apple               | 3         | 1.92%   |
| Fujitsu             | 2         | 1.28%   |
| MSI                 | 1         | 0.64%   |
| LDLC                | 1         | 0.64%   |
| HUAWEI              | 1         | 0.64%   |
| eMachines           | 1         | 0.64%   |
| Unknown             | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Toshiba Satellite C55-B                               | 4         | 2.56%   |
| Dell Inspiron 15-3567                                 | 4         | 2.56%   |
| ASUS UL80VT                                           | 4         | 2.56%   |
| HP Notebook                                           | 3         | 1.92%   |
| Dell Inspiron N5110                                   | 3         | 1.92%   |
| Dell Inspiron 3542                                    | 3         | 1.92%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 1.28%   |
| Lenovo G560 20042                                     | 2         | 1.28%   |
| Lenovo G50-30 80G0                                    | 2         | 1.28%   |
| Lenovo B50-70 20384                                   | 2         | 1.28%   |
| HP ProBook 4540s                                      | 2         | 1.28%   |
| HP Pavilion 15                                        | 2         | 1.28%   |
| HP 15                                                 | 2         | 1.28%   |
| Dell Latitude E7440                                   | 2         | 1.28%   |
| Dell Latitude E5430 vPro                              | 2         | 1.28%   |
| Dell Latitude 7480                                    | 2         | 1.28%   |
| Acer Aspire 5738                                      | 2         | 1.28%   |
| Toshiba Satellite Pro A100                            | 1         | 0.64%   |
| Toshiba Satellite C850-A979                           | 1         | 0.64%   |
| Toshiba Satellite C50-A560                            | 1         | 0.64%   |
| Toshiba Satellite C50-A545                            | 1         | 0.64%   |
| Toshiba Satellite C50-A539                            | 1         | 0.64%   |
| Toshiba PORTEGE R30-A                                 | 1         | 0.64%   |
| Toshiba PORTEGE M780                                  | 1         | 0.64%   |
| Sony VPCEJ2S1E                                        | 1         | 0.64%   |
| Sony VPCEH2H1E                                        | 1         | 0.64%   |
| Sony VGN-NS10J_S                                      | 1         | 0.64%   |
| Sony VGN-AW21M_H                                      | 1         | 0.64%   |
| Sony SVF1531GSFB                                      | 1         | 0.64%   |
| Sony SVE1713A6EW                                      | 1         | 0.64%   |
| Sony SVE1513K1EW                                      | 1         | 0.64%   |
| Samsung N102SP/N100SP/N101SP                          | 1         | 0.64%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B                   | 1         | 0.64%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.64%   |
| Packard Bell EasyNote TJ75                            | 1         | 0.64%   |
| Packard Bell EasyNote LJ71                            | 1         | 0.64%   |
| Packard Bell DOT S                                    | 1         | 0.64%   |
| MSI CR610M                                            | 1         | 0.64%   |
| Lenovo V130-15IGM 81HL                                | 1         | 0.64%   |
| Lenovo ThinkPad X260 20F5S1G104                       | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 17        | 10.9%   |
| Dell Latitude         | 15        | 9.62%   |
| Acer Aspire           | 10        | 6.41%   |
| Toshiba Satellite     | 9         | 5.77%   |
| Lenovo ThinkPad       | 9         | 5.77%   |
| HP ProBook            | 9         | 5.77%   |
| Lenovo IdeaPad        | 5         | 3.21%   |
| HP Pavilion           | 5         | 3.21%   |
| HP EliteBook          | 5         | 3.21%   |
| ASUS UL80VT           | 4         | 2.56%   |
| HP Notebook           | 3         | 1.92%   |
| Dell Precision        | 3         | 1.92%   |
| Toshiba PORTEGE       | 2         | 1.28%   |
| Packard Bell EasyNote | 2         | 1.28%   |
| Lenovo G580           | 2         | 1.28%   |
| Lenovo G560           | 2         | 1.28%   |
| Lenovo G50-30         | 2         | 1.28%   |
| Lenovo B50-70         | 2         | 1.28%   |
| HP Laptop             | 2         | 1.28%   |
| HP 15                 | 2         | 1.28%   |
| Fujitsu LIFEBOOK      | 2         | 1.28%   |
| Dell Vostro           | 2         | 1.28%   |
| Acer Extensa          | 2         | 1.28%   |
| Sony VPCEJ2S1E        | 1         | 0.64%   |
| Sony VPCEH2H1E        | 1         | 0.64%   |
| Sony VGN-NS10J        | 1         | 0.64%   |
| Sony VGN-AW21M        | 1         | 0.64%   |
| Sony SVF1531GSFB      | 1         | 0.64%   |
| Sony SVE1713A6EW      | 1         | 0.64%   |
| Sony SVE1513K1EW      | 1         | 0.64%   |
| Samsung N102SP        | 1         | 0.64%   |
| Samsung 700Z3A        | 1         | 0.64%   |
| Samsung 300E5EV       | 1         | 0.64%   |
| Packard Bell DOT      | 1         | 0.64%   |
| MSI CR610M            | 1         | 0.64%   |
| Lenovo V130-15IGM     | 1         | 0.64%   |
| Lenovo G500           | 1         | 0.64%   |
| Lenovo G50-70         | 1         | 0.64%   |
| LDLC Mercure          | 1         | 0.64%   |
| HUAWEI BOHB-WAX9      | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 25        | 16.03%  |
| 2014 | 23        | 14.74%  |
| 2013 | 18        | 11.54%  |
| 2015 | 15        | 9.62%   |
| 2016 | 13        | 8.33%   |
| 2009 | 13        | 8.33%   |
| 2017 | 12        | 7.69%   |
| 2011 | 10        | 6.41%   |
| 2010 | 10        | 6.41%   |
| 2018 | 6         | 3.85%   |
| 2021 | 3         | 1.92%   |
| 2020 | 2         | 1.28%   |
| 2019 | 2         | 1.28%   |
| 2008 | 2         | 1.28%   |
| 2022 | 1         | 0.64%   |
| 2006 | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 156       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 153       | 97.45%  |
| Enabled  | 4         | 2.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 60        | 38.22%  |
| 4.01-8.0   | 46        | 29.3%   |
| 8.01-16.0  | 28        | 17.83%  |
| 16.01-24.0 | 9         | 5.73%   |
| 1.01-2.0   | 9         | 5.73%   |
| 2.01-3.0   | 3         | 1.91%   |
| 32.01-64.0 | 2         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 83        | 46.89%  |
| 2.01-3.0  | 50        | 28.25%  |
| 3.01-4.0  | 26        | 14.69%  |
| 0.51-1.0  | 8         | 4.52%   |
| 4.01-8.0  | 7         | 3.95%   |
| 8.01-16.0 | 3         | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 121       | 76.58%  |
| 2      | 34        | 21.52%  |
| 4      | 1         | 0.63%   |
| 3      | 1         | 0.63%   |
| 0      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 64.33%  |
| No        | 56        | 35.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 91.03%  |
| No        | 14        | 8.97%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 97.45%  |
| No        | 4         | 2.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 67.09%  |
| No        | 52        | 32.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Algeria | 156       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Algiers         | 28        | 15.38%  |
| Belcourt        | 10        | 5.49%   |
| Tlemcen         | 8         | 4.4%    |
| Oran            | 7         | 3.85%   |
| Relizane        | 6         | 3.3%    |
| Béjaïa        | 6         | 3.3%    |
| Constantine     | 5         | 2.75%   |
| Cheraga         | 5         | 2.75%   |
| Tizi Ouzou      | 4         | 2.2%    |
| Tipasa          | 4         | 2.2%    |
| Skikda          | 4         | 2.2%    |
| Sétif          | 4         | 2.2%    |
| Birkhadem       | 4         | 2.2%    |
| Annaba          | 4         | 2.2%    |
| Laghouat        | 3         | 1.65%   |
| Kouba           | 3         | 1.65%   |
| Jijelli         | 3         | 1.65%   |
| Blida           | 3         | 1.65%   |
| ash-Shalif      | 3         | 1.65%   |
| Sidi Bel Abbes  | 2         | 1.1%    |
| Saoula          | 2         | 1.1%    |
| Saida           | 2         | 1.1%    |
| Ouargla         | 2         | 1.1%    |
| Djelfa          | 2         | 1.1%    |
| Boudouaou       | 2         | 1.1%    |
| Biskra          | 2         | 1.1%    |
| Bir el Djir     | 2         | 1.1%    |
| Ben ’Aknoûn  | 2         | 1.1%    |
| Bab Ezzouar     | 2         | 1.1%    |
| Ain Fakroun     | 2         | 1.1%    |
| Tolga           | 1         | 0.55%   |
| Tichi           | 1         | 0.55%   |
| Tazoult-Lambese | 1         | 0.55%   |
| Souma           | 1         | 0.55%   |
| Souk Ahras      | 1         | 0.55%   |
| Sidi Kada       | 1         | 0.55%   |
| Sidi Akkacha    | 1         | 0.55%   |
| Reguiba         | 1         | 0.55%   |
| Ouenza          | 1         | 0.55%   |
| Oued Sly        | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 36        | 47     | 19.46%  |
| Toshiba               | 25        | 34     | 13.51%  |
| WDC                   | 23        | 27     | 12.43%  |
| HGST                  | 16        | 20     | 8.65%   |
| Hitachi               | 15        | 18     | 8.11%   |
| Samsung Electronics   | 9         | 9      | 4.86%   |
| A-DATA Technology     | 6         | 9      | 3.24%   |
| Unknown               | 5         | 6      | 2.7%    |
| Team                  | 5         | 6      | 2.7%    |
| SanDisk               | 5         | 5      | 2.7%    |
| Lexar                 | 5         | 7      | 2.7%    |
| SK hynix              | 4         | 6      | 2.16%   |
| LITEON                | 4         | 7      | 2.16%   |
| Intel                 | 3         | 4      | 1.62%   |
| Fujitsu               | 3         | 4      | 1.62%   |
| Micron Technology     | 2         | 3      | 1.08%   |
| KingSpec              | 2         | 2      | 1.08%   |
| China                 | 2         | 2      | 1.08%   |
| XrayDisk              | 1         | 1      | 0.54%   |
| XPG                   | 1         | 1      | 0.54%   |
| Realtek Semiconductor | 1         | 1      | 0.54%   |
| PNY                   | 1         | 1      | 0.54%   |
| Londisk               | 1         | 1      | 0.54%   |
| Lenovo                | 1         | 1      | 0.54%   |
| KIOXIA                | 1         | 1      | 0.54%   |
| Kingston              | 1         | 1      | 0.54%   |
| KESU                  | 1         | 1      | 0.54%   |
| JMicron Technology    | 1         | 1      | 0.54%   |
| Initio                | 1         | 1      | 0.54%   |
| HUAWEI                | 1         | 1      | 0.54%   |
| HS-SSD-C100           | 1         | 1      | 0.54%   |
| Apple                 | 1         | 1      | 0.54%   |
| Unknown               | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB           | 9         | 4.74%   |
| Seagate ST9500325AS 500GB          | 6         | 3.16%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 3.16%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 2.11%   |
| Seagate Expansion 1TB              | 4         | 2.11%   |
| HGST HTS545050A7E380 500GB         | 4         | 2.11%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 3         | 1.58%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.58%   |
| Hitachi HTS545050B9A300 500GB      | 3         | 1.58%   |
| HGST HTS725050A7E630 500GB         | 3         | 1.58%   |
| HGST HTS545050A7E680 500GB         | 3         | 1.58%   |
| Unknown MMC Card  64GB             | 2         | 1.05%   |
| Team T253512GB SSD                 | 2         | 1.05%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 1.05%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 1.05%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 1.05%   |
| Lexar 512GB SSD                    | 2         | 1.05%   |
| Lexar 128GB SSD                    | 2         | 1.05%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 1.05%   |
| HGST HTS541010A9E680 1TB           | 2         | 1.05%   |
| XrayDisk 512GB SSD                 | 1         | 0.53%   |
| XPG SX950U 240GB                   | 1         | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.53%   |
| WDC WDS100T2B0B-00YS70 1TB SSD     | 1         | 0.53%   |
| WDC WD7500BPKX-75HPJT0 752GB       | 1         | 0.53%   |
| WDC WD5000LUCT-62RC2Y0 500GB       | 1         | 0.53%   |
| WDC WD5000LUCT-62C26Y0 500GB       | 1         | 0.53%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.53%   |
| WDC WD5000LPVT-16G33T0 500GB       | 1         | 0.53%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.53%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.53%   |
| WDC WD5000LPCX-21VHAT0 500GB       | 1         | 0.53%   |
| WDC WD5000BPVT-75HXZT3 500GB       | 1         | 0.53%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 0.53%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 0.53%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.53%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 47     | 30.77%  |
| Toshiba             | 24        | 31     | 20.51%  |
| WDC                 | 21        | 24     | 17.95%  |
| HGST                | 16        | 20     | 13.68%  |
| Hitachi             | 15        | 18     | 12.82%  |
| Fujitsu             | 3         | 4      | 2.56%   |
| Samsung Electronics | 1         | 1      | 0.85%   |
| Initio              | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 6         | 9      | 12.77%  |
| Team                | 4         | 5      | 8.51%   |
| SanDisk             | 4         | 4      | 8.51%   |
| LITEON              | 4         | 7      | 8.51%   |
| Lexar               | 4         | 6      | 8.51%   |
| WDC                 | 3         | 3      | 6.38%   |
| SK hynix            | 3         | 5      | 6.38%   |
| Intel               | 3         | 4      | 6.38%   |
| Samsung Electronics | 2         | 2      | 4.26%   |
| KingSpec            | 2         | 2      | 4.26%   |
| China               | 2         | 2      | 4.26%   |
| XrayDisk            | 1         | 1      | 2.13%   |
| XPG                 | 1         | 1      | 2.13%   |
| PNY                 | 1         | 1      | 2.13%   |
| Londisk             | 1         | 1      | 2.13%   |
| Lenovo              | 1         | 1      | 2.13%   |
| Kingston            | 1         | 1      | 2.13%   |
| JMicron Technology  | 1         | 1      | 2.13%   |
| HS-SSD-C100         | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |
| Unknown             | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 112       | 146    | 64.37%  |
| SSD     | 42        | 59     | 24.14%  |
| NVMe    | 13        | 17     | 7.47%   |
| MMC     | 5         | 7      | 2.87%   |
| Unknown | 2         | 2      | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 139       | 197    | 83.23%  |
| NVMe | 13        | 17     | 7.78%   |
| SAS  | 10        | 10     | 5.99%   |
| MMC  | 5         | 7      | 2.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 114       | 157    | 74.03%  |
| 0.51-1.0   | 38        | 46     | 24.68%  |
| 1.01-2.0   | 2         | 2      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 44        | 26.19%  |
| 51-100     | 32        | 19.05%  |
| 101-250    | 30        | 17.86%  |
| 501-1000   | 20        | 11.9%   |
| 1-20       | 17        | 10.12%  |
| 21-50      | 16        | 9.52%   |
| 1001-2000  | 7         | 4.17%   |
| Unknown    | 2         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 84        | 48%     |
| 21-50    | 32        | 18.29%  |
| 101-250  | 27        | 15.43%  |
| 51-100   | 18        | 10.29%  |
| 251-500  | 8         | 4.57%   |
| 501-1000 | 4         | 2.29%   |
| Unknown  | 2         | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB         | 5         | 5      | 20%     |
| HGST HTS725050A7E630 500GB        | 2         | 4      | 8%      |
| WDC WD5000LUCT-62C26Y0 500GB      | 1         | 1      | 4%      |
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 1      | 4%      |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 4%      |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 4%      |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 4%      |
| Seagate ST9320325AS 320GB         | 1         | 1      | 4%      |
| Seagate ST9250410AS 250GB         | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 4%      |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 4%      |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 4%      |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 4%      |
| Samsung Electronics HM320HJ 320GB | 1         | 1      | 4%      |
| KingSpec P3-128 128GB             | 1         | 1      | 4%      |
| Hitachi HTS723225L9A360 250GB     | 1         | 2      | 4%      |
| Hitachi HTS547564A9E384 640GB     | 1         | 1      | 4%      |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 4%      |
| Hitachi HTS542516K9SA00 160GB     | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB        | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 44%     |
| Hitachi             | 4         | 5      | 16%     |
| WDC                 | 3         | 3      | 12%     |
| HGST                | 3         | 5      | 12%     |
| Toshiba             | 2         | 2      | 8%      |
| Samsung Electronics | 1         | 1      | 4%      |
| KingSpec            | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 45.83%  |
| Hitachi             | 4         | 5      | 16.67%  |
| WDC                 | 3         | 3      | 12.5%   |
| HGST                | 3         | 5      | 12.5%   |
| Toshiba             | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 27     | 95.83%  |
| SSD  | 1         | 1      | 4.17%   |

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
| Detected | 98        | 143    | 59.39%  |
| Works    | 43        | 60     | 26.06%  |
| Malfunc  | 24        | 28     | 14.55%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 139       | 85.8%   |
| Samsung Electronics          | 7         | 4.32%   |
| AMD                          | 6         | 3.7%    |
| Nvidia                       | 2         | 1.23%   |
| Micron Technology            | 2         | 1.23%   |
| Toshiba America Info Systems | 1         | 0.62%   |
| Silicon Motion               | 1         | 0.62%   |
| SanDisk                      | 1         | 0.62%   |
| Realtek Semiconductor        | 1         | 0.62%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.62%   |
| KIOXIA                       | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 27        | 16.27%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 13.25%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 7.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 6.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 5.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 4.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 4.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.41%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 2.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.81%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.2%    |
| Intel Atom Processor E3800 Series SATA IDE Controller                            | 2         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.2%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.6%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.6%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 0.6%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.6%    |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                | 1         | 0.6%    |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.6%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.6%    |
| Micron 2210 NVMe SSD [Cobain]                                                    | 1         | 0.6%    |
| Micron 2200S NVMe SSD [Cassandra]                                                | 1         | 0.6%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 1         | 0.6%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 1         | 0.6%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.6%    |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.6%    |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.6%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.6%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 129       | 78.66%  |
| RAID | 15        | 9.15%   |
| NVMe | 13        | 7.93%   |
| IDE  | 7         | 4.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 148       | 94.87%  |
| AMD    | 8         | 5.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-3217U CPU @ 1.80GHz           | 6         | 3.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 5         | 3.21%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 4         | 2.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 4         | 2.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 2.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 2.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 2.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 4         | 2.56%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 3         | 1.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.92%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.92%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.92%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 1.92%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 1.92%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.28%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.28%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.28%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.28%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.28%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 2         | 1.28%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.28%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.28%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.28%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.28%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.28%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.28%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.64%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.64%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.64%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.64%   |
| Intel Pentium 3805U @ 1.90GHz               | 1         | 0.64%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.64%   |
| Intel Genuine CPU T2080 @ 1.73GHz           | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 30.77%  |
| Intel Core i3           | 39        | 25%     |
| Intel Core i7           | 24        | 15.38%  |
| Intel Celeron           | 9         | 5.77%   |
| Intel Pentium           | 7         | 4.49%   |
| Intel Genuine           | 6         | 3.85%   |
| Intel Core 2 Duo        | 5         | 3.21%   |
| Intel Atom              | 5         | 3.21%   |
| Intel Pentium Dual-Core | 3         | 1.92%   |
| Other                   | 2         | 1.28%   |
| AMD Ryzen 5             | 2         | 1.28%   |
| AMD Ryzen 3             | 1         | 0.64%   |
| AMD E2                  | 1         | 0.64%   |
| AMD E1                  | 1         | 0.64%   |
| AMD Athlon Neo X2       | 1         | 0.64%   |
| AMD Athlon II Dual-Core | 1         | 0.64%   |
| AMD A4                  | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 122       | 78.21%  |
| 4      | 29        | 18.59%  |
| 1      | 3         | 1.92%   |
| 12     | 1         | 0.64%   |
| 6      | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 156       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 73.72%  |
| 1      | 40        | 25.64%  |
| 4      | 1         | 0.64%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 152       | 97.44%  |
| 32-bit         | 2         | 1.28%   |
| Unknown        | 2         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 26.06%  |
| 0x306a9    | 20        | 12.12%  |
| 0x206a7    | 13        | 7.88%   |
| 0x406e3    | 11        | 6.67%   |
| 0x40651    | 11        | 6.67%   |
| 0x20655    | 11        | 6.67%   |
| 0x306d4    | 8         | 4.85%   |
| 0x30678    | 8         | 4.85%   |
| 0x806e9    | 7         | 4.24%   |
| 0x1067a    | 5         | 3.03%   |
| 0x806ea    | 4         | 2.42%   |
| 0x906e9    | 3         | 1.82%   |
| 0x806ec    | 2         | 1.21%   |
| 0x306c3    | 2         | 1.21%   |
| 0x30661    | 2         | 1.21%   |
| 0x20652    | 2         | 1.21%   |
| 0xa0652    | 1         | 0.61%   |
| 0x806c1    | 1         | 0.61%   |
| 0x706a8    | 1         | 0.61%   |
| 0x6fd      | 1         | 0.61%   |
| 0x6ec      | 1         | 0.61%   |
| 0x6e8      | 1         | 0.61%   |
| 0x506c9    | 1         | 0.61%   |
| 0x406c3    | 1         | 0.61%   |
| 0x08108102 | 1         | 0.61%   |
| 0x0810100b | 1         | 0.61%   |
| 0x0700010f | 1         | 0.61%   |
| 0x06006705 | 1         | 0.61%   |
| 0x05000119 | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 25        | 16.03%  |
| KabyLake      | 19        | 12.18%  |
| Haswell       | 18        | 11.54%  |
| SandyBridge   | 16        | 10.26%  |
| Skylake       | 14        | 8.97%   |
| Westmere      | 13        | 8.33%   |
| Silvermont    | 12        | 7.69%   |
| Penryn        | 11        | 7.05%   |
| Broadwell     | 9         | 5.77%   |
| P6            | 2         | 1.28%   |
| Goldmont plus | 2         | 1.28%   |
| Bonnell       | 2         | 1.28%   |
| Zen+          | 1         | 0.64%   |
| Zen 2         | 1         | 0.64%   |
| Zen           | 1         | 0.64%   |
| TigerLake     | 1         | 0.64%   |
| K8 Hammer     | 1         | 0.64%   |
| K10           | 1         | 0.64%   |
| Jaguar        | 1         | 0.64%   |
| Goldmont      | 1         | 0.64%   |
| Excavator     | 1         | 0.64%   |
| Core          | 1         | 0.64%   |
| CometLake     | 1         | 0.64%   |
| Bobcat        | 1         | 0.64%   |
| Unknown       | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 68%     |
| AMD    | 33        | 16.5%   |
| Nvidia | 31        | 15.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 11.39%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 7.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 6.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 6.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 4.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 4.95%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 9         | 4.46%   |
| Intel HD Graphics 620                                                                    | 8         | 3.96%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.48%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.48%   |
| Nvidia GT218M [GeForce G210M]                                                            | 4         | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.98%   |
| Intel HD Graphics 630                                                                    | 3         | 1.49%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.49%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 1.49%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.99%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 2         | 0.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.99%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.99%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.99%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 2         | 0.99%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.99%   |
| Nvidia TU117M                                                                            | 1         | 0.5%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.5%    |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.5%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.5%    |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.5%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.5%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.5%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.5%    |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.5%    |
| Nvidia GK104GLM [Quadro K4000M]                                                          | 1         | 0.5%    |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 92        | 58.97%  |
| Intel + Nvidia | 26        | 16.67%  |
| Intel + AMD    | 18        | 11.54%  |
| 1 x AMD        | 15        | 9.62%   |
| 1 x Nvidia     | 5         | 3.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 145       | 92.36%  |
| Proprietary | 10        | 6.37%   |
| Unknown     | 2         | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 64.56%  |
| 1.01-2.0   | 26        | 16.46%  |
| 0.01-0.5   | 15        | 9.49%   |
| 0.51-1.0   | 10        | 6.33%   |
| 3.01-4.0   | 5         | 3.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 37        | 22.16%  |
| AU Optronics            | 29        | 17.37%  |
| Samsung Electronics     | 26        | 15.57%  |
| BOE                     | 21        | 12.57%  |
| Chimei Innolux          | 16        | 9.58%   |
| Chi Mei Optoelectronics | 10        | 5.99%   |
| Acer                    | 5         | 2.99%   |
| Hewlett-Packard         | 4         | 2.4%    |
| Apple                   | 3         | 1.8%    |
| Sharp                   | 2         | 1.2%    |
| Lenovo                  | 2         | 1.2%    |
| AOC                     | 2         | 1.2%    |
| Unknown                 | 2         | 1.2%    |
| ___                     | 1         | 0.6%    |
| PANDA                   | 1         | 0.6%    |
| MStar                   | 1         | 0.6%    |
| LGD                     | 1         | 0.6%    |
| InnoLux Display         | 1         | 0.6%    |
| Goldstar                | 1         | 0.6%    |
| BenQ                    | 1         | 0.6%    |
| AGO                     | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 4         | 2.38%   |
| AU Optronics LCD Monitor AUO213C 1366x768 309x174mm 14.0-inch            | 4         | 2.38%   |
| Acer V193HQ ACR00F9 1366x768 410x230mm 18.5-inch                         | 4         | 2.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.79%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.79%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 3         | 1.79%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 1.19%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 1.19%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 2         | 1.19%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 1.19%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 1.19%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 1.19%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 1.19%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 1.19%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 2         | 1.19%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 1.19%   |
| Unknown                                                                  | 2         | 1.19%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.6%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.6%    |
| Sharp HDMI SHP10DB 1920x1080 1330x750mm 60.1-inch                        | 1         | 0.6%    |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch        | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC494A 1366x768 344x193mm 15.5-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3442 1366x768 344x194mm 15.5-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3254 1366x768 293x165mm 13.2-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3241 1366x768 344x194mm 15.5-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch     | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 100       | 64.52%  |
| 1920x1080 (FHD)   | 34        | 21.94%  |
| 1600x900 (HD+)    | 6         | 3.87%   |
| 1280x800 (WXGA)   | 4         | 2.58%   |
| 1440x900 (WXGA+)  | 3         | 1.94%   |
| 3840x2160 (4K)    | 2         | 1.29%   |
| 2560x1440 (QHD)   | 1         | 0.65%   |
| 1920x540          | 1         | 0.65%   |
| 1920x1200 (WUXGA) | 1         | 0.65%   |
| 1680x945          | 1         | 0.65%   |
| 1280x1024 (SXGA)  | 1         | 0.65%   |
| 1024x600          | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 97        | 58.43%  |
| 14      | 16        | 9.64%   |
| 13      | 15        | 9.04%   |
| 18      | 9         | 5.42%   |
| 17      | 7         | 4.22%   |
| 12      | 7         | 4.22%   |
| 11      | 2         | 1.2%    |
| 10      | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |
| 60      | 1         | 0.6%    |
| 52      | 1         | 0.6%    |
| 37      | 1         | 0.6%    |
| 27      | 1         | 0.6%    |
| 24      | 1         | 0.6%    |
| 23      | 1         | 0.6%    |
| 21      | 1         | 0.6%    |
| 20      | 1         | 0.6%    |
| 19      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 120       | 72.73%  |
| 201-300     | 16        | 9.7%    |
| 401-500     | 11        | 6.67%   |
| 351-400     | 10        | 6.06%   |
| 501-600     | 3         | 1.82%   |
| 1001-1500   | 2         | 1.21%   |
| Unknown     | 2         | 1.21%   |
| 801-900     | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 138       | 91.39%  |
| 16/10   | 8         | 5.3%    |
| 5/4     | 1         | 0.66%   |
| 4/3     | 1         | 0.66%   |
| 32/9    | 1         | 0.66%   |
| 3/2     | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 97        | 58.43%  |
| 81-90          | 27        | 16.27%  |
| 141-150        | 10        | 6.02%   |
| 61-70          | 6         | 3.61%   |
| 71-80          | 5         | 3.01%   |
| 121-130        | 4         | 2.41%   |
| 151-200        | 3         | 1.81%   |
| More than 1000 | 2         | 1.2%    |
| 51-60          | 2         | 1.2%    |
| 41-50          | 2         | 1.2%    |
| 201-250        | 2         | 1.2%    |
| 131-140        | 2         | 1.2%    |
| Unknown        | 2         | 1.2%    |
| 301-350        | 1         | 0.6%    |
| 501-1000       | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 90        | 54.88%  |
| 121-160 | 36        | 21.95%  |
| 51-100  | 28        | 17.07%  |
| 161-240 | 6         | 3.66%   |
| 1-50    | 2         | 1.22%   |
| Unknown | 2         | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 134       | 84.81%  |
| 2     | 19        | 12.03%  |
| 0     | 3         | 1.9%    |
| 3     | 2         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 86        | 32.7%   |
| Intel                           | 57        | 21.67%  |
| Qualcomm Atheros                | 50        | 19.01%  |
| Broadcom                        | 32        | 12.17%  |
| Ralink Technology               | 10        | 3.8%    |
| Ralink                          | 6         | 2.28%   |
| Broadcom Limited                | 4         | 1.52%   |
| Samsung Electronics             | 3         | 1.14%   |
| MediaTek                        | 3         | 1.14%   |
| Xiaomi                          | 2         | 0.76%   |
| Marvell Technology Group        | 2         | 0.76%   |
| Huawei Technologies             | 2         | 0.76%   |
| Sierra Wireless                 | 1         | 0.38%   |
| Qualcomm Atheros Communications | 1         | 0.38%   |
| Nvidia                          | 1         | 0.38%   |
| LG Electronics                  | 1         | 0.38%   |
| Hewlett-Packard                 | 1         | 0.38%   |
| D-Link System                   | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 14.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 10.09%  |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 4.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 4.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.52%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.21%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.58%   |
| Intel Wireless 8260                                               | 5         | 1.58%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 1.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.26%   |
| Intel Wireless 7265                                               | 4         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 1.26%   |
| Intel Wireless 7260                                               | 3         | 0.95%   |
| Intel Wireless 3160                                               | 3         | 0.95%   |
| Intel WiFi Link 5100                                              | 3         | 0.95%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.95%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.95%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.63%   |
| Intel PRO/100 VE Network Connection                               | 2         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 32.34%  |
| Qualcomm Atheros                | 42        | 25.15%  |
| Broadcom                        | 26        | 15.57%  |
| Realtek Semiconductor           | 21        | 12.57%  |
| Ralink Technology               | 10        | 5.99%   |
| Ralink                          | 6         | 3.59%   |
| MediaTek                        | 2         | 1.2%    |
| Broadcom Limited                | 2         | 1.2%    |
| Sierra Wireless                 | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Hewlett-Packard                 | 1         | 0.6%    |
| D-Link System                   | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 8.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 7.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 5.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 4.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 4.79%   |
| Intel Wireless 8265 / 8275                                     | 7         | 4.19%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 3.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.99%   |
| Intel Wireless 8260                                            | 5         | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 2.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 2.4%    |
| Intel Wireless 7265                                            | 4         | 2.4%    |
| Intel Wireless 7260                                            | 3         | 1.8%    |
| Intel Wireless 3160                                            | 3         | 1.8%    |
| Intel WiFi Link 5100                                           | 3         | 1.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.8%    |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.2%    |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.2%    |
| Intel Centrino Wireless-N 135                                  | 2         | 1.2%    |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.2%    |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.2%    |
| Sierra Wireless EM7305                                         | 1         | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.6%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 78        | 52.7%   |
| Intel                    | 34        | 22.97%  |
| Qualcomm Atheros         | 14        | 9.46%   |
| Broadcom                 | 9         | 6.08%   |
| Samsung Electronics      | 3         | 2.03%   |
| Xiaomi                   | 2         | 1.35%   |
| Marvell Technology Group | 2         | 1.35%   |
| Broadcom Limited         | 2         | 1.35%   |
| Nvidia                   | 1         | 0.68%   |
| MediaTek                 | 1         | 0.68%   |
| LG Electronics           | 1         | 0.68%   |
| Huawei Technologies      | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 30.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 21.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.37%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 3.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 2.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 2.68%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.34%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.34%   |
| Intel PRO/100 VE Network Connection                               | 2         | 1.34%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.34%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.34%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.34%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 1.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.67%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.67%   |
| MediaTek Infinix SMART 6 HD                                       | 1         | 0.67%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.67%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.67%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.67%   |
| Huawei E353/E3131                                                 | 1         | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.67%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 153       | 51.86%  |
| Ethernet | 141       | 47.8%   |
| Modem    | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 127       | 82.47%  |
| Ethernet | 27        | 17.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 138       | 87.34%  |
| 1     | 15        | 9.49%   |
| 0     | 5         | 3.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 29.25%  |
| Qualcomm Atheros Communications | 15        | 14.15%  |
| Broadcom                        | 13        | 12.26%  |
| Realtek Semiconductor           | 9         | 8.49%   |
| Foxconn / Hon Hai               | 6         | 5.66%   |
| Lite-On Technology              | 5         | 4.72%   |
| IMC Networks                    | 5         | 4.72%   |
| Ralink                          | 4         | 3.77%   |
| Dell                            | 4         | 3.77%   |
| Toshiba                         | 3         | 2.83%   |
| Foxconn International           | 3         | 2.83%   |
| Apple                           | 3         | 2.83%   |
| Ralink Technology               | 1         | 0.94%   |
| Integrated System Solution      | 1         | 0.94%   |
| Hewlett-Packard                 | 1         | 0.94%   |
| Chicony Electronics             | 1         | 0.94%   |
| Alps Electric                   | 1         | 0.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 21        | 19.81%  |
| Qualcomm Atheros  Bluetooth Device                    | 7         | 6.6%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 4.72%   |
| Realtek Bluetooth Radio                               | 4         | 3.77%   |
| Ralink RT3290 Bluetooth                               | 4         | 3.77%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 3.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3         | 2.83%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3         | 2.83%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 2.83%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3         | 2.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 3         | 2.83%   |
| Toshiba Bluetooth Device                              | 2         | 1.89%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 1.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 1.89%   |
| IMC Networks Bluetooth Device                         | 2         | 1.89%   |
| Dell Wireless 365 Bluetooth                           | 2         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.89%   |
| Apple Bluetooth Host Controller                       | 2         | 1.89%   |
| Toshiba BCM43142A0                                    | 1         | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.94%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.94%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.94%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 0.94%   |
| Qualcomm Atheros Bluetooth                            | 1         | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.94%   |
| Lite-On Wireless_Device                               | 1         | 0.94%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 0.94%   |
| Lite-On BCM43142A0                                    | 1         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 0.94%   |
| Intel Bluetooth Device                                | 1         | 0.94%   |
| Intel AX200 Bluetooth                                 | 1         | 0.94%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.94%   |
| IMC Networks Wireless_Device                          | 1         | 0.94%   |
| IMC Networks Bluetooth Radio                          | 1         | 0.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 0.94%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.94%   |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 0.94%   |
| Foxconn / Hon Hai Acer Module                         | 1         | 0.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel              | 143       | 80.34%  |
| AMD                | 17        | 9.55%   |
| Nvidia             | 14        | 7.87%   |
| Texas Instruments  | 1         | 0.56%   |
| Medeli Electronics | 1         | 0.56%   |
| JMTek              | 1         | 0.56%   |
| Goldvish           | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 14.02%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 12.62%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 6.54%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 6.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 6.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 5.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 4.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 4.21%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 4.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 3.27%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.87%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.4%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 1.4%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.93%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.93%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.47%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Medeli Electronics USB Audio Device                                                               | 1         | 0.47%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.47%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 26        | 26%     |
| Samsung Electronics | 26        | 26%     |
| Micron Technology   | 15        | 15%     |
| Unknown             | 14        | 14%     |
| Kingston            | 7         | 7%      |
| Nanya Technology    | 3         | 3%      |
| Ramaxel Technology  | 2         | 2%      |
| Crucial             | 2         | 2%      |
| TwinMOS             | 1         | 1%      |
| Team                | 1         | 1%      |
| Elpida              | 1         | 1%      |
| ASint Technology    | 1         | 1%      |
| A-DATA Technology   | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 5         | 4.63%   |
| Unknown RAM Module 4GB SODIMM 1066MT/s                    | 4         | 3.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 3.7%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s     | 3         | 2.78%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 1.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 2         | 1.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 1.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.85%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 2         | 1.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 1.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.85%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 1.85%   |
| Nanya RAM Module 8GB SODIMM DDR4 2667MT/s                 | 2         | 1.85%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 2         | 1.85%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s     | 2         | 1.85%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1334MT/s  | 2         | 1.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s               | 1         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s            | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                | 1         | 0.93%   |
| TwinMOS RAM 9DHTBNIB-TATP 4GB SODIMM DDR3 1067MT/s        | 1         | 0.93%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s      | 1         | 0.93%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.93%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 2133MT/s      | 1         | 0.93%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s          | 1         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1         | 0.93%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s | 1         | 0.93%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s | 1         | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 50        | 62.5%   |
| DDR4    | 19        | 23.75%  |
| Unknown | 4         | 5%      |
| SDRAM   | 3         | 3.75%   |
| DDR2    | 2         | 2.5%    |
| LPDDR4  | 1         | 1.25%   |
| LPDDR3  | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 98.7%   |
| Row Of Chips | 1         | 1.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 45        | 50.56%  |
| 8192  | 21        | 23.6%   |
| 2048  | 19        | 21.35%  |
| 32768 | 1         | 1.12%   |
| 16384 | 1         | 1.12%   |
| 1024  | 1         | 1.12%   |
| 512   | 1         | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 36        | 41.38%  |
| 2667    | 12        | 13.79%  |
| 1333    | 7         | 8.05%   |
| 2133    | 6         | 6.9%    |
| 1334    | 6         | 6.9%    |
| 1066    | 4         | 4.6%    |
| 4199    | 3         | 3.45%   |
| 3200    | 3         | 3.45%   |
| 3266    | 2         | 2.3%    |
| 1067    | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |
| 2400    | 1         | 1.15%   |
| 667     | 1         | 1.15%   |
| 533     | 1         | 1.15%   |
| 333     | 1         | 1.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson XP-200 Series                                             | 1         | 20%     |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 20%     |
| Canon LBP6020                                                         | 1         | 20%     |
| Canon LBP3010/LBP3018/LBP3050                                         | 1         | 20%     |
| Canon LBP2900                                                         | 1         | 20%     |

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
| Chicony Electronics                    | 38        | 27.14%  |
| Microdia                               | 23        | 16.43%  |
| Realtek Semiconductor                  | 13        | 9.29%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 7.86%   |
| Sunplus Innovation Technology          | 9         | 6.43%   |
| Bison Electronics                      | 8         | 5.71%   |
| IMC Networks                           | 7         | 5%      |
| Suyin                                  | 5         | 3.57%   |
| Syntek                                 | 4         | 2.86%   |
| Silicon Motion                         | 3         | 2.14%   |
| Quanta                                 | 3         | 2.14%   |
| Apple                                  | 3         | 2.14%   |
| Lite-On Technology                     | 2         | 1.43%   |
| Alcor Micro                            | 2         | 1.43%   |
| Acer                                   | 2         | 1.43%   |
| Sonix Technology                       | 1         | 0.71%   |
| Samsung Electronics                    | 1         | 0.71%   |
| Ricoh                                  | 1         | 0.71%   |
| Primax Electronics                     | 1         | 0.71%   |
| Pixart Imaging                         | 1         | 0.71%   |
| Aveo Technology                        | 1         | 0.71%   |
| ALi                                    | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 6         | 4.29%   |
| Bison Lenovo EasyCamera                                                  | 6         | 4.29%   |
| Chicony Integrated Camera                                                | 5         | 3.57%   |
| Chicony Web Camera - HD                                                  | 4         | 2.86%   |
| Chicony Asus Integrated 0.3M UVC Webcam                                  | 4         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 2.86%   |
| Sunplus Integrated_Webcam_HD                                             | 3         | 2.14%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 2.14%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 2.14%   |
| Microdia Integrated Webcam                                               | 3         | 2.14%   |
| Chicony HD WebCam                                                        | 3         | 2.14%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 1.43%   |
| Suyin HP Truevision HD                                                   | 2         | 1.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 1.43%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 1.43%   |
| Realtek HP Truevision HD                                                 | 2         | 1.43%   |
| IMC Networks Lenovo EasyCamera                                           | 2         | 1.43%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.43%   |
| Chicony TOSHIBA Web Camera - HD                                          | 2         | 1.43%   |
| Chicony HP TrueVision HD                                                 | 2         | 1.43%   |
| Chicony HP HD Webcam [Fixed]                                             | 2         | 1.43%   |
| Chicony Acer CrystalEye Webcam                                           | 2         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.43%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                       | 2         | 1.43%   |
| Syntek USB2.0 Camera                                                     | 1         | 0.71%   |
| Syntek EasyCamera                                                        | 1         | 0.71%   |
| Suyin WebCam                                                             | 1         | 0.71%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 0.71%   |
| Sunplus Laptop Integrated Webcam HD                                      | 1         | 0.71%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.71%   |
| Sunplus Dell HD Webcam                                                   | 1         | 0.71%   |
| Sunplus Asus Webcam                                                      | 1         | 0.71%   |
| Sonix USB2.0 HD UVC WebCam                                               | 1         | 0.71%   |
| Silicon Motion WebCam SC-13HDL11431N                                     | 1         | 0.71%   |
| Silicon Motion WebCam SC-10HDD12636N                                     | 1         | 0.71%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 1         | 0.71%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 11        | 73.33%  |
| Synaptics        | 2         | 13.33%  |
| AuthenTec        | 2         | 13.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 5         | 33.33%  |
| Validity Sensors VFS491                           | 3         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 13.33%  |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 6.67%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 6.67%   |
| AuthenTec AES2810                                 | 1         | 6.67%   |
| AuthenTec AES1600                                 | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 11        | 91.67%  |
| OmniKey  | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 41.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 33.33%  |
| OmniKey CardMan 4321                                                         | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 102       | 64.56%  |
| 1     | 48        | 30.38%  |
| 2     | 7         | 4.43%   |
| 3     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 22.73%  |
| Net/wireless             | 12        | 18.18%  |
| Graphics card            | 12        | 18.18%  |
| Chipcard                 | 12        | 18.18%  |
| Bluetooth                | 5         | 7.58%   |
| Storage                  | 3         | 4.55%   |
| Net/ethernet             | 2         | 3.03%   |
| Multimedia controller    | 2         | 3.03%   |
| Communication controller | 1         | 1.52%   |
| Card reader              | 1         | 1.52%   |
| Camera                   | 1         | 1.52%   |

