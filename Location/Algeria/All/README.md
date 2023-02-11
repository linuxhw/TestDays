Linux in Algeria - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Algeria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Algeria/Desktop/README.md) and [notebooks](/Location/Algeria/Notebook/README.md).

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

Total: 327

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook Revolve 810 G3    | Notebook    | [1f55ca148f](https://linux-hardware.org/?probe=1f55ca148f) | Jan 30, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4042b92ee1](https://linux-hardware.org/?probe=4042b92ee1) | Jan 29, 2023 |
| HP            | 18E7                        | Desktop     | [01cbafc241](https://linux-hardware.org/?probe=01cbafc241) | Jan 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f1f0543123](https://linux-hardware.org/?probe=f1f0543123) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5169fb5013](https://linux-hardware.org/?probe=5169fb5013) | Jan 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [f0ed3b4989](https://linux-hardware.org/?probe=f0ed3b4989) | Jan 14, 2023 |
| MSI           | H270-A PRO                  | Desktop     | [f150327257](https://linux-hardware.org/?probe=f150327257) | Jan 14, 2023 |
| Acer          | Calpella                    | Notebook    | [108843a25a](https://linux-hardware.org/?probe=108843a25a) | Jan 14, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9cc37ff271](https://linux-hardware.org/?probe=9cc37ff271) | Jan 09, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | Notebook    | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Sony          | VGN-NS10J_S                 | Notebook    | [3789038010](https://linux-hardware.org/?probe=3789038010) | Jan 04, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [c2d592a9e5](https://linux-hardware.org/?probe=c2d592a9e5) | Dec 30, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [de5dc0c3ea](https://linux-hardware.org/?probe=de5dc0c3ea) | Dec 17, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [3b340e6b29](https://linux-hardware.org/?probe=3b340e6b29) | Dec 16, 2022 |
| Dell          | Latitude 5480               | Notebook    | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [ca043cff45](https://linux-hardware.org/?probe=ca043cff45) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [08d7f00868](https://linux-hardware.org/?probe=08d7f00868) | Nov 24, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [da02cb82bf](https://linux-hardware.org/?probe=da02cb82bf) | Nov 23, 2022 |
| ASUSTek       | S300CA                      | Notebook    | [3efc297b44](https://linux-hardware.org/?probe=3efc297b44) | Nov 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [cae1dbbb12](https://linux-hardware.org/?probe=cae1dbbb12) | Nov 12, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [64c65685da](https://linux-hardware.org/?probe=64c65685da) | Nov 03, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5dbeb8f7dd](https://linux-hardware.org/?probe=5dbeb8f7dd) | Nov 03, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6c979bdf58](https://linux-hardware.org/?probe=6c979bdf58) | Oct 27, 2022 |
| Unknown       | X79                         | Desktop     | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4727244665](https://linux-hardware.org/?probe=4727244665) | Oct 18, 2022 |
| ECS           | G41T-M7                     | Desktop     | [3abe70653e](https://linux-hardware.org/?probe=3abe70653e) | Oct 16, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6a0a056c36](https://linux-hardware.org/?probe=6a0a056c36) | Oct 15, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [fefb833511](https://linux-hardware.org/?probe=fefb833511) | Oct 14, 2022 |
| Dell          | Precision M4800             | Notebook    | [be05dcbe15](https://linux-hardware.org/?probe=be05dcbe15) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [7d65aefb93](https://linux-hardware.org/?probe=7d65aefb93) | Oct 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [719ac47bc6](https://linux-hardware.org/?probe=719ac47bc6) | Oct 06, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cd06f54882](https://linux-hardware.org/?probe=cd06f54882) | Sep 30, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [21d9eb0a71](https://linux-hardware.org/?probe=21d9eb0a71) | Sep 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Lenovo        | ThinkPad X230 2325CZ1       | Notebook    | [b484febc13](https://linux-hardware.org/?probe=b484febc13) | Sep 17, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e61fe6932b](https://linux-hardware.org/?probe=e61fe6932b) | Sep 13, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [3b1c07d561](https://linux-hardware.org/?probe=3b1c07d561) | Sep 01, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [26c9be116e](https://linux-hardware.org/?probe=26c9be116e) | Aug 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [1f4f742288](https://linux-hardware.org/?probe=1f4f742288) | Aug 23, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| HP            | Pavilion dm3                | Notebook    | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [708f9572ad](https://linux-hardware.org/?probe=708f9572ad) | Jul 26, 2022 |
| ECS           | G41T-M16                    | Desktop     | [5a3363d66f](https://linux-hardware.org/?probe=5a3363d66f) | Jun 28, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [4eadb7ee17](https://linux-hardware.org/?probe=4eadb7ee17) | Jun 19, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [fd9f1b2ef6](https://linux-hardware.org/?probe=fd9f1b2ef6) | Jun 17, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [149eb0bab7](https://linux-hardware.org/?probe=149eb0bab7) | Jun 14, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9ff02a8c0c](https://linux-hardware.org/?probe=9ff02a8c0c) | Jun 12, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9273aa4844](https://linux-hardware.org/?probe=9273aa4844) | Jun 12, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [15532b1663](https://linux-hardware.org/?probe=15532b1663) | Jun 07, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [0dd5791ff8](https://linux-hardware.org/?probe=0dd5791ff8) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1b7a237b9b](https://linux-hardware.org/?probe=1b7a237b9b) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| HP            | ProBook 4720s               | Notebook    | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| HP            | ProBook 4720s               | Notebook    | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [57d9d59b56](https://linux-hardware.org/?probe=57d9d59b56) | May 13, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [577c71e530](https://linux-hardware.org/?probe=577c71e530) | May 06, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [95d53f5fc0](https://linux-hardware.org/?probe=95d53f5fc0) | Mar 31, 2022 |
| Dell          | 07N90W A02                  | Desktop     | [4fd59735d6](https://linux-hardware.org/?probe=4fd59735d6) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [698654a73f](https://linux-hardware.org/?probe=698654a73f) | Mar 26, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [00e72ee0ce](https://linux-hardware.org/?probe=00e72ee0ce) | Mar 04, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [eb4abb6e15](https://linux-hardware.org/?probe=eb4abb6e15) | Mar 02, 2022 |
| Packard Be... | DOT S                       | Notebook    | [4110664747](https://linux-hardware.org/?probe=4110664747) | Mar 02, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [9d0a21adb1](https://linux-hardware.org/?probe=9d0a21adb1) | Mar 02, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [7bdf3a8998](https://linux-hardware.org/?probe=7bdf3a8998) | Feb 27, 2022 |
| HP            | 630                         | Notebook    | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [214381cf00](https://linux-hardware.org/?probe=214381cf00) | Feb 16, 2022 |
| Lenovo        | 0B98417 PRO                 | Desktop     | [6e5fa50531](https://linux-hardware.org/?probe=6e5fa50531) | Feb 13, 2022 |
| Intel         | H55                         | Desktop     | [1b1b5c3ed8](https://linux-hardware.org/?probe=1b1b5c3ed8) | Feb 12, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f5b85f478](https://linux-hardware.org/?probe=3f5b85f478) | Feb 07, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03d4a4af15](https://linux-hardware.org/?probe=03d4a4af15) | Feb 05, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| MSI           | H61M-S20                    | Desktop     | [7d0384b2d2](https://linux-hardware.org/?probe=7d0384b2d2) | Jan 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [0d6dacc5dc](https://linux-hardware.org/?probe=0d6dacc5dc) | Jan 20, 2022 |
| ECS           | H61H2-M4                    | Desktop     | [2995a79728](https://linux-hardware.org/?probe=2995a79728) | Jan 07, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Unknown       | X79                         | Desktop     | [ec1620ee82](https://linux-hardware.org/?probe=ec1620ee82) | Jan 01, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [33df9edd07](https://linux-hardware.org/?probe=33df9edd07) | Dec 25, 2021 |
| LDLC          | Mercure MH                  | Notebook    | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Sony          | VGN-AW21M_H                 | Notebook    | [b4cf74ec7d](https://linux-hardware.org/?probe=b4cf74ec7d) | Dec 23, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [69ecf03c84](https://linux-hardware.org/?probe=69ecf03c84) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| ASUSTek       | X555LAB                     | Notebook    | [c07bccb6c7](https://linux-hardware.org/?probe=c07bccb6c7) | Dec 07, 2021 |
| Sony          | SVF1531GSFB                 | Notebook    | [fb251b93e9](https://linux-hardware.org/?probe=fb251b93e9) | Dec 04, 2021 |
| MSI           | H61M-S20                    | Desktop     | [5e73200702](https://linux-hardware.org/?probe=5e73200702) | Dec 02, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Foxconn       | 17A0                        | Desktop     | [0fc17817a1](https://linux-hardware.org/?probe=0fc17817a1) | Nov 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e26d674874](https://linux-hardware.org/?probe=e26d674874) | Nov 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [233d576651](https://linux-hardware.org/?probe=233d576651) | Nov 12, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [0862dc626b](https://linux-hardware.org/?probe=0862dc626b) | Oct 29, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [545b983e7c](https://linux-hardware.org/?probe=545b983e7c) | Oct 22, 2021 |
| Unknown       | G41 Series V10              | Desktop     | [ce791f779f](https://linux-hardware.org/?probe=ce791f779f) | Oct 21, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [ebd6264587](https://linux-hardware.org/?probe=ebd6264587) | Oct 19, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [a629aeaa1b](https://linux-hardware.org/?probe=a629aeaa1b) | Oct 15, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [9855c138d4](https://linux-hardware.org/?probe=9855c138d4) | Oct 11, 2021 |
| MSI           | H61M-S20                    | Desktop     | [9669908158](https://linux-hardware.org/?probe=9669908158) | Sep 29, 2021 |
| MSI           | H61M-S20                    | Desktop     | [481ecaa854](https://linux-hardware.org/?probe=481ecaa854) | Sep 28, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8641901755](https://linux-hardware.org/?probe=8641901755) | Sep 27, 2021 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [d986a2e532](https://linux-hardware.org/?probe=d986a2e532) | Sep 26, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3b43d9b42f](https://linux-hardware.org/?probe=3b43d9b42f) | Sep 22, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [a31437072c](https://linux-hardware.org/?probe=a31437072c) | Sep 20, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [1c77028990](https://linux-hardware.org/?probe=1c77028990) | Sep 18, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [b740654686](https://linux-hardware.org/?probe=b740654686) | Sep 17, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [e817658118](https://linux-hardware.org/?probe=e817658118) | Sep 10, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [b8661880d2](https://linux-hardware.org/?probe=b8661880d2) | Sep 07, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [95d654f778](https://linux-hardware.org/?probe=95d654f778) | Sep 04, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [78886ef280](https://linux-hardware.org/?probe=78886ef280) | Aug 31, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [82aceb2458](https://linux-hardware.org/?probe=82aceb2458) | Aug 30, 2021 |
| HP            | 15                          | Notebook    | [5520042e14](https://linux-hardware.org/?probe=5520042e14) | Aug 28, 2021 |
| HP            | 15                          | Notebook    | [cc4e936b38](https://linux-hardware.org/?probe=cc4e936b38) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8a71545b54](https://linux-hardware.org/?probe=8a71545b54) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [297e2e187c](https://linux-hardware.org/?probe=297e2e187c) | Aug 25, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [b1490652d3](https://linux-hardware.org/?probe=b1490652d3) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [47ed88595b](https://linux-hardware.org/?probe=47ed88595b) | Aug 20, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [cf362e966f](https://linux-hardware.org/?probe=cf362e966f) | Aug 19, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [795edc5779](https://linux-hardware.org/?probe=795edc5779) | Aug 15, 2021 |
| Dell          | Latitude E6400              | Notebook    | [eb029acad6](https://linux-hardware.org/?probe=eb029acad6) | Aug 12, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [84199b59aa](https://linux-hardware.org/?probe=84199b59aa) | Aug 10, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [a4be1b3322](https://linux-hardware.org/?probe=a4be1b3322) | Aug 10, 2021 |
| MSI           | CR610M                      | Notebook    | [68759b0315](https://linux-hardware.org/?probe=68759b0315) | Aug 08, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [007cd499bf](https://linux-hardware.org/?probe=007cd499bf) | Aug 06, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [405dddebf5](https://linux-hardware.org/?probe=405dddebf5) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| Dell          | Latitude 7380               | Notebook    | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| Dell          | 0WG864                      | Desktop     | [2e28996126](https://linux-hardware.org/?probe=2e28996126) | Jul 28, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [185f27f184](https://linux-hardware.org/?probe=185f27f184) | Jul 22, 2021 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [cf7ebc455f](https://linux-hardware.org/?probe=cf7ebc455f) | Jul 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [d8fd7fe06d](https://linux-hardware.org/?probe=d8fd7fe06d) | Jul 20, 2021 |
| Intel         | H55                         | Desktop     | [47c7c454ac](https://linux-hardware.org/?probe=47c7c454ac) | Jul 09, 2021 |
| Intel         | H55                         | Desktop     | [9e4504d3a3](https://linux-hardware.org/?probe=9e4504d3a3) | Jul 09, 2021 |
| Dell          | Latitude 7480               | Notebook    | [28d1d17f13](https://linux-hardware.org/?probe=28d1d17f13) | Jun 22, 2021 |
| HP            | 2B34                        | Desktop     | [d2c91c450b](https://linux-hardware.org/?probe=d2c91c450b) | May 31, 2021 |
| MSI           | ZH77A-G41                   | Desktop     | [8755040ea2](https://linux-hardware.org/?probe=8755040ea2) | May 25, 2021 |
| Toshiba       | Satellite C50-A539          | Notebook    | [c6c8ae87d9](https://linux-hardware.org/?probe=c6c8ae87d9) | May 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f54143a81d](https://linux-hardware.org/?probe=f54143a81d) | May 24, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [8a9dc6ab53](https://linux-hardware.org/?probe=8a9dc6ab53) | May 24, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [36b88b7391](https://linux-hardware.org/?probe=36b88b7391) | May 23, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [34c12e6041](https://linux-hardware.org/?probe=34c12e6041) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d91a5890c9](https://linux-hardware.org/?probe=d91a5890c9) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d12a52a705](https://linux-hardware.org/?probe=d12a52a705) | May 14, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [be3e7aa080](https://linux-hardware.org/?probe=be3e7aa080) | May 09, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0252beb838](https://linux-hardware.org/?probe=0252beb838) | May 04, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [bd06d6bb56](https://linux-hardware.org/?probe=bd06d6bb56) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [861a11fe04](https://linux-hardware.org/?probe=861a11fe04) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [66faef6161](https://linux-hardware.org/?probe=66faef6161) | May 02, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [62fc21894d](https://linux-hardware.org/?probe=62fc21894d) | Apr 28, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [7a97f404a4](https://linux-hardware.org/?probe=7a97f404a4) | Apr 24, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [ba300d050b](https://linux-hardware.org/?probe=ba300d050b) | Apr 24, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [7a72fc45b4](https://linux-hardware.org/?probe=7a72fc45b4) | Apr 22, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [b46bb85400](https://linux-hardware.org/?probe=b46bb85400) | Apr 21, 2021 |
| Dell          | Latitude E7440              | Notebook    | [4acb0ea358](https://linux-hardware.org/?probe=4acb0ea358) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [a48b0c422f](https://linux-hardware.org/?probe=a48b0c422f) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [6fd83225c1](https://linux-hardware.org/?probe=6fd83225c1) | Apr 18, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [2953bef8d1](https://linux-hardware.org/?probe=2953bef8d1) | Apr 18, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [f3b2236c7a](https://linux-hardware.org/?probe=f3b2236c7a) | Apr 15, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [8e5a3a6e19](https://linux-hardware.org/?probe=8e5a3a6e19) | Apr 05, 2021 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [843dae0f43](https://linux-hardware.org/?probe=843dae0f43) | Apr 04, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [2df99824aa](https://linux-hardware.org/?probe=2df99824aa) | Apr 03, 2021 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [765ae993b9](https://linux-hardware.org/?probe=765ae993b9) | Mar 16, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [6408cdb8b2](https://linux-hardware.org/?probe=6408cdb8b2) | Mar 14, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [210d440087](https://linux-hardware.org/?probe=210d440087) | Mar 13, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [a9068d7ec4](https://linux-hardware.org/?probe=a9068d7ec4) | Mar 12, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [387b714e2f](https://linux-hardware.org/?probe=387b714e2f) | Mar 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [5f41497264](https://linux-hardware.org/?probe=5f41497264) | Mar 02, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5cf7ce91a7](https://linux-hardware.org/?probe=5cf7ce91a7) | Mar 01, 2021 |
| Acer          | Extensa 2508                | Notebook    | [7fb16dc91b](https://linux-hardware.org/?probe=7fb16dc91b) | Feb 28, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [0eb94c0487](https://linux-hardware.org/?probe=0eb94c0487) | Feb 26, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [5582abd577](https://linux-hardware.org/?probe=5582abd577) | Feb 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [97f3e486f0](https://linux-hardware.org/?probe=97f3e486f0) | Feb 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [d4273cb949](https://linux-hardware.org/?probe=d4273cb949) | Feb 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [7ec7f64225](https://linux-hardware.org/?probe=7ec7f64225) | Feb 20, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [35ca18e322](https://linux-hardware.org/?probe=35ca18e322) | Feb 18, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [67702a7546](https://linux-hardware.org/?probe=67702a7546) | Feb 17, 2021 |
| HP            | ProBook 4540s               | Notebook    | [f6618c225b](https://linux-hardware.org/?probe=f6618c225b) | Feb 16, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [c107fc9c40](https://linux-hardware.org/?probe=c107fc9c40) | Feb 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [74fb8b5b1d](https://linux-hardware.org/?probe=74fb8b5b1d) | Feb 14, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [da10465006](https://linux-hardware.org/?probe=da10465006) | Feb 08, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b050103b48](https://linux-hardware.org/?probe=b050103b48) | Feb 04, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [8c36c3c601](https://linux-hardware.org/?probe=8c36c3c601) | Feb 03, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [807a0ea003](https://linux-hardware.org/?probe=807a0ea003) | Jan 31, 2021 |
| Dell          | Precision M6600             | Notebook    | [3731eb952c](https://linux-hardware.org/?probe=3731eb952c) | Jan 29, 2021 |
| Acer          | Aspire V5-571               | Notebook    | [74f0d86e1e](https://linux-hardware.org/?probe=74f0d86e1e) | Jan 28, 2021 |
| Dell          | Precision M6600             | Notebook    | [105a9a66c3](https://linux-hardware.org/?probe=105a9a66c3) | Jan 23, 2021 |
| Dell          | Precision M6600             | Notebook    | [84d3a754fb](https://linux-hardware.org/?probe=84d3a754fb) | Jan 23, 2021 |
| Sony          | VPCEH2H1E                   | Notebook    | [891e9364e0](https://linux-hardware.org/?probe=891e9364e0) | Jan 14, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [9286a611a0](https://linux-hardware.org/?probe=9286a611a0) | Jan 04, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [aae61a1ca3](https://linux-hardware.org/?probe=aae61a1ca3) | Dec 22, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ce37e65007](https://linux-hardware.org/?probe=ce37e65007) | Dec 21, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [cf12b04ead](https://linux-hardware.org/?probe=cf12b04ead) | Dec 21, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9e347f10ee](https://linux-hardware.org/?probe=9e347f10ee) | Dec 12, 2020 |
| Unknown       | Unknown                     | Desktop     | [83507a1ac0](https://linux-hardware.org/?probe=83507a1ac0) | Dec 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [688a7e3a73](https://linux-hardware.org/?probe=688a7e3a73) | Dec 11, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [3bab146c4c](https://linux-hardware.org/?probe=3bab146c4c) | Dec 10, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [997a066f37](https://linux-hardware.org/?probe=997a066f37) | Dec 08, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [356e5f32f8](https://linux-hardware.org/?probe=356e5f32f8) | Dec 08, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8dec91d656](https://linux-hardware.org/?probe=8dec91d656) | Dec 01, 2020 |
| Dell          | Vostro 3500                 | Notebook    | [a76707659b](https://linux-hardware.org/?probe=a76707659b) | Nov 29, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Gigabyte      | P61A-D3                     | Desktop     | [c547f76923](https://linux-hardware.org/?probe=c547f76923) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [cfbfec849d](https://linux-hardware.org/?probe=cfbfec849d) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [97d5763d6b](https://linux-hardware.org/?probe=97d5763d6b) | Nov 21, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [4ead657ec9](https://linux-hardware.org/?probe=4ead657ec9) | Nov 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a9f4ce29b9](https://linux-hardware.org/?probe=a9f4ce29b9) | Nov 15, 2020 |
| MSI           | G41M-P33 Combo              | Desktop     | [36ffd6debb](https://linux-hardware.org/?probe=36ffd6debb) | Nov 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [51b974180e](https://linux-hardware.org/?probe=51b974180e) | Nov 11, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [39251e283c](https://linux-hardware.org/?probe=39251e283c) | Oct 29, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [85e77f85c7](https://linux-hardware.org/?probe=85e77f85c7) | Oct 26, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [230a4dff71](https://linux-hardware.org/?probe=230a4dff71) | Oct 26, 2020 |
| HP            | ProBook 4540s               | Notebook    | [e2bb03b7da](https://linux-hardware.org/?probe=e2bb03b7da) | Oct 23, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1425d1ebde](https://linux-hardware.org/?probe=1425d1ebde) | Oct 20, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [f1040f264c](https://linux-hardware.org/?probe=f1040f264c) | Oct 19, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [6a54c56b7a](https://linux-hardware.org/?probe=6a54c56b7a) | Oct 19, 2020 |
| HP            | ProBook 4540s               | Notebook    | [b369817417](https://linux-hardware.org/?probe=b369817417) | Oct 15, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [07077a7194](https://linux-hardware.org/?probe=07077a7194) | Oct 02, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [c35dfa149d](https://linux-hardware.org/?probe=c35dfa149d) | Sep 24, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1efd90cecb](https://linux-hardware.org/?probe=1efd90cecb) | Sep 20, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ebaa6b30e4](https://linux-hardware.org/?probe=ebaa6b30e4) | Sep 20, 2020 |
| HP            | 3397                        | Desktop     | [5232568c4a](https://linux-hardware.org/?probe=5232568c4a) | Sep 06, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [ec99eca757](https://linux-hardware.org/?probe=ec99eca757) | Sep 03, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [9ab161c8d7](https://linux-hardware.org/?probe=9ab161c8d7) | Sep 03, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [c4e5d02631](https://linux-hardware.org/?probe=c4e5d02631) | Sep 02, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Packard Be... | EasyNote LJ71               | Notebook    | [8848f3250d](https://linux-hardware.org/?probe=8848f3250d) | Aug 26, 2020 |
| HP            | 250 G4                      | Notebook    | [84bd70a658](https://linux-hardware.org/?probe=84bd70a658) | Jul 24, 2020 |
| HP            | 250 G4                      | Notebook    | [bb773c0ade](https://linux-hardware.org/?probe=bb773c0ade) | Jul 24, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [33e5e60503](https://linux-hardware.org/?probe=33e5e60503) | Jul 05, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [2273ab39c8](https://linux-hardware.org/?probe=2273ab39c8) | Jun 27, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [734c3a7d86](https://linux-hardware.org/?probe=734c3a7d86) | Jun 22, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [9451ca4468](https://linux-hardware.org/?probe=9451ca4468) | Jun 22, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [cb406c43ec](https://linux-hardware.org/?probe=cb406c43ec) | Jun 21, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [46894e19cd](https://linux-hardware.org/?probe=46894e19cd) | Jun 21, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [81cf9fa7cf](https://linux-hardware.org/?probe=81cf9fa7cf) | Jun 11, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [b4ef87de2d](https://linux-hardware.org/?probe=b4ef87de2d) | Jun 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [c349a84934](https://linux-hardware.org/?probe=c349a84934) | Jun 02, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [0bc2465c23](https://linux-hardware.org/?probe=0bc2465c23) | May 25, 2020 |
| ASUSTek       | X541UV                      | Notebook    | [25108243d2](https://linux-hardware.org/?probe=25108243d2) | May 23, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [148b457da1](https://linux-hardware.org/?probe=148b457da1) | May 21, 2020 |
| Acer          | Extensa 2510                | Notebook    | [3c56d54986](https://linux-hardware.org/?probe=3c56d54986) | May 16, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [800fe450a7](https://linux-hardware.org/?probe=800fe450a7) | May 16, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [ad602ee170](https://linux-hardware.org/?probe=ad602ee170) | May 15, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [e1f352ee7e](https://linux-hardware.org/?probe=e1f352ee7e) | May 15, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [165c5e3446](https://linux-hardware.org/?probe=165c5e3446) | May 11, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9deb8b9d38](https://linux-hardware.org/?probe=9deb8b9d38) | May 01, 2020 |
| HP            | 15                          | Notebook    | [bc0640c653](https://linux-hardware.org/?probe=bc0640c653) | May 01, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [30806c27ea](https://linux-hardware.org/?probe=30806c27ea) | May 01, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [bc3989f5fd](https://linux-hardware.org/?probe=bc3989f5fd) | Apr 30, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [eb26a0a6dd](https://linux-hardware.org/?probe=eb26a0a6dd) | Apr 26, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [27139478ff](https://linux-hardware.org/?probe=27139478ff) | Apr 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1e23113365](https://linux-hardware.org/?probe=1e23113365) | Apr 19, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [a06745a31b](https://linux-hardware.org/?probe=a06745a31b) | Apr 19, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [300ccfbb68](https://linux-hardware.org/?probe=300ccfbb68) | Apr 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [32919aba44](https://linux-hardware.org/?probe=32919aba44) | Apr 08, 2020 |
| Sony          | SVE1713A6EW                 | Notebook    | [998290195d](https://linux-hardware.org/?probe=998290195d) | Mar 26, 2020 |
| Dell          | Precision M4600             | Notebook    | [995809b82f](https://linux-hardware.org/?probe=995809b82f) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [394723d5ec](https://linux-hardware.org/?probe=394723d5ec) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [9a4b04d5c6](https://linux-hardware.org/?probe=9a4b04d5c6) | Mar 10, 2020 |
| Dell          | Latitude 7490               | Notebook    | [3b7100f499](https://linux-hardware.org/?probe=3b7100f499) | Mar 10, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [b0b0e640c9](https://linux-hardware.org/?probe=b0b0e640c9) | Mar 01, 2020 |
| ECS           | G41T-M7                     | Desktop     | [39f9889169](https://linux-hardware.org/?probe=39f9889169) | Feb 26, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [46a39dcec8](https://linux-hardware.org/?probe=46a39dcec8) | Feb 10, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [52020faf85](https://linux-hardware.org/?probe=52020faf85) | Feb 05, 2020 |
| Dell          | 0F0TGN A00                  | Desktop     | [1f4a60f810](https://linux-hardware.org/?probe=1f4a60f810) | Feb 03, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [ed6be60ed5](https://linux-hardware.org/?probe=ed6be60ed5) | Jan 07, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [b8f52696c7](https://linux-hardware.org/?probe=b8f52696c7) | Jan 07, 2020 |
| MSI           | H55M-E21                    | Desktop     | [a586112d3f](https://linux-hardware.org/?probe=a586112d3f) | Jan 01, 2020 |
| MSI           | H55M-E21                    | Desktop     | [71183fc4d2](https://linux-hardware.org/?probe=71183fc4d2) | Jan 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [170967f63e](https://linux-hardware.org/?probe=170967f63e) | Dec 31, 2019 |
| HP            | Pavilion 15                 | Notebook    | [e190391a64](https://linux-hardware.org/?probe=e190391a64) | Dec 10, 2019 |
| Lenovo        | ThinkPad T440 20B6S00200    | Notebook    | [8491772fe8](https://linux-hardware.org/?probe=8491772fe8) | Nov 19, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [3aed06c634](https://linux-hardware.org/?probe=3aed06c634) | Nov 05, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [80803b7502](https://linux-hardware.org/?probe=80803b7502) | Nov 05, 2019 |
| Sony          | VPCEJ2S1E                   | Notebook    | [909ce7c754](https://linux-hardware.org/?probe=909ce7c754) | Oct 25, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [742402d677](https://linux-hardware.org/?probe=742402d677) | Oct 01, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [bf938959f0](https://linux-hardware.org/?probe=bf938959f0) | Sep 30, 2019 |
| MSI           | Z77A-G45                    | Desktop     | [169e8e49d9](https://linux-hardware.org/?probe=169e8e49d9) | Sep 27, 2019 |
| HP            | 3397                        | Desktop     | [4367666d7a](https://linux-hardware.org/?probe=4367666d7a) | Sep 18, 2019 |
| HP            | 3397                        | Desktop     | [148b5948f9](https://linux-hardware.org/?probe=148b5948f9) | Sep 18, 2019 |
| HP            | Pavilion 15                 | Notebook    | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Intel         | H55                         | Desktop     | [4529486397](https://linux-hardware.org/?probe=4529486397) | Jul 17, 2019 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [a9f20406b7](https://linux-hardware.org/?probe=a9f20406b7) | Jul 17, 2019 |
| Packard Be... | EasyNote TJ75               | Notebook    | [84742985cb](https://linux-hardware.org/?probe=84742985cb) | Apr 30, 2019 |
| Dell          | Latitude E5430 vPro         | Notebook    | [d88e664ef7](https://linux-hardware.org/?probe=d88e664ef7) | Apr 29, 2019 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [ec6b1b90c3](https://linux-hardware.org/?probe=ec6b1b90c3) | Apr 22, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5aeb26c21c](https://linux-hardware.org/?probe=5aeb26c21c) | Apr 10, 2019 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [92ce529502](https://linux-hardware.org/?probe=92ce529502) | Apr 10, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [53ac040baf](https://linux-hardware.org/?probe=53ac040baf) | Mar 28, 2019 |
| HP            | Notebook                    | Notebook    | [a94921a2ad](https://linux-hardware.org/?probe=a94921a2ad) | Dec 29, 2018 |
| WeiBu         | SIMM INT G-41D3 G1.0L       | Desktop     | [d8be685baa](https://linux-hardware.org/?probe=d8be685baa) | Dec 01, 2018 |
| Dell          | 0TP406                      | Desktop     | [620c3d413f](https://linux-hardware.org/?probe=620c3d413f) | Nov 28, 2018 |
| Dell          | 0TP406                      | Desktop     | [e33d9fb70d](https://linux-hardware.org/?probe=e33d9fb70d) | Nov 28, 2018 |
| Unknown       | Unknown                     | Desktop     | [1ee83f48b0](https://linux-hardware.org/?probe=1ee83f48b0) | Oct 14, 2018 |
| MSI           | H55-GD65                    | Desktop     | [6cbd59f0a9](https://linux-hardware.org/?probe=6cbd59f0a9) | Feb 27, 2018 |
| HP            | Pavilion Notebook           | Notebook    | [283bc29327](https://linux-hardware.org/?probe=283bc29327) | Dec 24, 2017 |
| HP            | Pavilion Notebook           | Notebook    | [af28f98e0a](https://linux-hardware.org/?probe=af28f98e0a) | Dec 07, 2017 |
| MSI           | 970A-G46                    | Desktop     | [693800273f](https://linux-hardware.org/?probe=693800273f) | Apr 01, 2017 |
| ASUSTek       | X540SA                      | Notebook    | [f76ee802c9](https://linux-hardware.org/?probe=f76ee802c9) | Mar 09, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 47        | 19.83%  |
| Ubuntu 18.04        | 20        | 8.44%   |
| OpenMandriva 4.3    | 14        | 5.91%   |
| OpenMandriva 4.2    | 14        | 5.91%   |
| Ubuntu 22.04        | 13        | 5.49%   |
| Linux Mint 20.1     | 7         | 2.95%   |
| KDE neon 20.04      | 6         | 2.53%   |
| Pop!_OS 20.04       | 5         | 2.11%   |
| Arch                | 5         | 2.11%   |
| Ubuntu 21.04        | 4         | 1.69%   |
| Ubuntu 19.10        | 4         | 1.69%   |
| ArcoLinux Rolling   | 4         | 1.69%   |
| Zorin 16            | 3         | 1.27%   |
| Xubuntu 20.04       | 3         | 1.27%   |
| Ubuntu 20.10        | 3         | 1.27%   |
| ROSA R11            | 3         | 1.27%   |
| ROSA R10            | 3         | 1.27%   |
| Manjaro             | 3         | 1.27%   |
| Linux Mint 20.2     | 3         | 1.27%   |
| Fedora 35           | 3         | 1.27%   |
| Debian 11           | 3         | 1.27%   |
| BlackPanther 18.1   | 3         | 1.27%   |
| Ubuntu 21.10        | 2         | 0.84%   |
| Ubuntu 19.04        | 2         | 0.84%   |
| ROSA R8.1           | 2         | 0.84%   |
| Parrot 5.0          | 2         | 0.84%   |
| OpenMandriva 23.01  | 2         | 0.84%   |
| Manjaro 20.1        | 2         | 0.84%   |
| Kubuntu 20.04       | 2         | 0.84%   |
| Kali 2021.2         | 2         | 0.84%   |
| Kali 2021.1         | 2         | 0.84%   |
| Fedora 36           | 2         | 0.84%   |
| Fedora 33           | 2         | 0.84%   |
| Debian 10           | 2         | 0.84%   |
| Zorin 15            | 1         | 0.42%   |
| Xubuntu 22.04       | 1         | 0.42%   |
| Xubuntu 18.04       | 1         | 0.42%   |
| UbuntuDDE 20.04     | 1         | 0.42%   |
| Ubuntu Unity 16.04  | 1         | 0.42%   |
| Ubuntu Budgie 22.04 | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 93        | 40.09%  |
| OpenMandriva  | 32        | 13.79%  |
| Linux Mint    | 16        | 6.9%    |
| Fedora        | 9         | 3.88%   |
| ROSA          | 8         | 3.45%   |
| Pop!_OS       | 8         | 3.45%   |
| Manjaro       | 7         | 3.02%   |
| KDE neon      | 7         | 3.02%   |
| Debian        | 6         | 2.59%   |
| Arch          | 6         | 2.59%   |
| Xubuntu       | 5         | 2.16%   |
| Kali          | 5         | 2.16%   |
| Zorin         | 4         | 1.72%   |
| ArcoLinux     | 4         | 1.72%   |
| Parrot        | 3         | 1.29%   |
| Kubuntu       | 3         | 1.29%   |
| BlackPanther  | 3         | 1.29%   |
| Peppermint    | 2         | 0.86%   |
| UbuntuDDE     | 1         | 0.43%   |
| Ubuntu Unity  | 1         | 0.43%   |
| Ubuntu Budgie | 1         | 0.43%   |
| Skygate       | 1         | 0.43%   |
| Pear OS       | 1         | 0.43%   |
| MX            | 1         | 0.43%   |
| EndeavourOS   | 1         | 0.43%   |
| Clear Linux   | 1         | 0.43%   |
| CentOS        | 1         | 0.43%   |
| Artix         | 1         | 0.43%   |
| ArchLabs      | 1         | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 14        | 5.62%   |
| 5.10.14-desktop-1omv4002        | 14        | 5.62%   |
| 5.4.0-42-generic                | 5         | 2.01%   |
| 5.8.0-50-generic                | 4         | 1.61%   |
| 5.4.0-72-generic                | 4         | 1.61%   |
| 5.4.0-54-generic                | 4         | 1.61%   |
| 5.4.0-29-generic                | 4         | 1.61%   |
| 5.15.0-47-generic               | 4         | 1.61%   |
| 5.0.0-37-generic                | 4         | 1.61%   |
| 5.4.0-65-generic                | 3         | 1.2%    |
| 5.4.0-56-generic                | 3         | 1.2%    |
| 5.4.0-52-generic                | 3         | 1.2%    |
| 5.3.0-46-generic                | 3         | 1.2%    |
| 5.15.0-56-generic               | 3         | 1.2%    |
| 5.13.0-30-generic               | 3         | 1.2%    |
| 5.11.0-38-generic               | 3         | 1.2%    |
| 5.11.0-27-generic               | 3         | 1.2%    |
| 6.1.1-desktop-1omv2290          | 2         | 0.8%    |
| 5.8.0-44-generic                | 2         | 0.8%    |
| 5.4.0-88-generic                | 2         | 0.8%    |
| 5.4.0-81-generic                | 2         | 0.8%    |
| 5.4.0-80-generic                | 2         | 0.8%    |
| 5.4.0-7625-generic              | 2         | 0.8%    |
| 5.4.0-48-generic                | 2         | 0.8%    |
| 5.4.0-33-generic                | 2         | 0.8%    |
| 5.3.0-40-generic                | 2         | 0.8%    |
| 5.15.0-48-generic               | 2         | 0.8%    |
| 5.11.0-40-generic               | 2         | 0.8%    |
| 5.11.0-36-generic               | 2         | 0.8%    |
| 5.11.0-34-generic               | 2         | 0.8%    |
| 5.11.0-25-generic               | 2         | 0.8%    |
| 5.0.0-29-generic                | 2         | 0.8%    |
| 5.0.0-23-generic                | 2         | 0.8%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.8%    |
| 4.18.16-desktop-1bP             | 2         | 0.8%    |
| 4.15.0-desktop-45.1rosa-x86_64  | 2         | 0.8%    |
| 4.15.0-42-generic               | 2         | 0.8%    |
| 6.0.9-060009-generic            | 1         | 0.4%    |
| 5.9.11-3-MANJARO                | 1         | 0.4%    |
| 5.8.18-300.fc33.x86_64          | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 49        | 20.85%  |
| 5.15.0  | 17        | 7.23%   |
| 5.11.0  | 16        | 6.81%   |
| 5.8.0   | 14        | 5.96%   |
| 5.16.7  | 14        | 5.96%   |
| 5.10.14 | 14        | 5.96%   |
| 4.15.0  | 13        | 5.53%   |
| 5.3.0   | 10        | 4.26%   |
| 5.0.0   | 10        | 4.26%   |
| 5.13.0  | 7         | 2.98%   |
| 5.10.0  | 7         | 2.98%   |
| 4.18.16 | 3         | 1.28%   |
| 6.1.1   | 2         | 0.85%   |
| 5.18.12 | 2         | 0.85%   |
| 5.15.7  | 2         | 0.85%   |
| 5.14.0  | 2         | 0.85%   |
| 4.9.60  | 2         | 0.85%   |
| 4.4.0   | 2         | 0.85%   |
| 4.19.0  | 2         | 0.85%   |
| 6.0.9   | 1         | 0.43%   |
| 5.9.11  | 1         | 0.43%   |
| 5.8.18  | 1         | 0.43%   |
| 5.7.17  | 1         | 0.43%   |
| 5.7.0   | 1         | 0.43%   |
| 5.6.14  | 1         | 0.43%   |
| 5.6.0   | 1         | 0.43%   |
| 5.4.72  | 1         | 0.43%   |
| 5.4.60  | 1         | 0.43%   |
| 5.4.15  | 1         | 0.43%   |
| 5.19.3  | 1         | 0.43%   |
| 5.19.14 | 1         | 0.43%   |
| 5.19.12 | 1         | 0.43%   |
| 5.19.11 | 1         | 0.43%   |
| 5.19.10 | 1         | 0.43%   |
| 5.19.0  | 1         | 0.43%   |
| 5.17.4  | 1         | 0.43%   |
| 5.17.0  | 1         | 0.43%   |
| 5.16.11 | 1         | 0.43%   |
| 5.16.0  | 1         | 0.43%   |
| 5.15.8  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 52        | 22.13%  |
| 5.15    | 26        | 11.06%  |
| 5.10    | 26        | 11.06%  |
| 5.11    | 18        | 7.66%   |
| 5.16    | 16        | 6.81%   |
| 5.8     | 15        | 6.38%   |
| 4.15    | 13        | 5.53%   |
| 5.3     | 10        | 4.26%   |
| 5.0     | 10        | 4.26%   |
| 5.13    | 8         | 3.4%    |
| 5.19    | 6         | 2.55%   |
| 5.14    | 4         | 1.7%    |
| 4.9     | 4         | 1.7%    |
| 4.19    | 4         | 1.7%    |
| 4.18    | 4         | 1.7%    |
| 5.12    | 3         | 1.28%   |
| 6.1     | 2         | 0.85%   |
| 5.7     | 2         | 0.85%   |
| 5.6     | 2         | 0.85%   |
| 5.18    | 2         | 0.85%   |
| 5.17    | 2         | 0.85%   |
| 4.4     | 2         | 0.85%   |
| 6.0     | 1         | 0.43%   |
| 5.9     | 1         | 0.43%   |
| 4.1     | 1         | 0.43%   |
| 3.10    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 205       | 96.7%   |
| i686   | 6         | 2.83%   |
| armv7l | 1         | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 99        | 44%     |
| KDE5            | 49        | 21.78%  |
| Unknown         | 24        | 10.67%  |
| XFCE            | 15        | 6.67%   |
| X-Cinnamon      | 9         | 4%      |
| MATE            | 5         | 2.22%   |
| KDE4            | 5         | 2.22%   |
| KDE             | 5         | 2.22%   |
| Cinnamon        | 3         | 1.33%   |
| LXQt            | 2         | 0.89%   |
| i3              | 2         | 0.89%   |
| Unity           | 1         | 0.44%   |
| Peppermint      | 1         | 0.44%   |
| LXDE            | 1         | 0.44%   |
| GNOME Flashback | 1         | 0.44%   |
| fvwm            | 1         | 0.44%   |
| Deepin          | 1         | 0.44%   |
| Budgie          | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 179       | 82.49%  |
| Wayland | 26        | 11.98%  |
| Unknown | 11        | 5.07%   |
| Tty     | 1         | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 112       | 50.22%  |
| SDDM    | 43        | 19.28%  |
| LightDM | 20        | 8.97%   |
| GDM3    | 18        | 8.07%   |
| GDM     | 17        | 7.62%   |
| TDM     | 7         | 3.14%   |
| KDM     | 5         | 2.24%   |
| SLiM    | 1         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 91        | 41.55%  |
| fr_FR       | 77        | 35.16%  |
| Unknown     | 26        | 11.87%  |
| en_GB       | 8         | 3.65%   |
| C           | 6         | 2.74%   |
| ar_DZ       | 4         | 1.83%   |
| fr_DZ       | 2         | 0.91%   |
| fr_BE       | 2         | 0.91%   |
| ar_EG       | 2         | 0.91%   |
| en-US-UTF-8 | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 154       | 70.97%  |
| EFI  | 63        | 29.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 160       | 73.06%  |
| Overlay | 33        | 15.07%  |
| Btrfs   | 12        | 5.48%   |
| Unknown | 9         | 4.11%   |
| Ext2    | 3         | 1.37%   |
| Xfs     | 1         | 0.46%   |
| Ext3    | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 127       | 58.8%   |
| GPT     | 46        | 21.3%   |
| MBR     | 43        | 19.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 80.73%  |
| Yes       | 42        | 19.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 53%     |
| Yes       | 102       | 47%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 37        | 17.45%  |
| Hewlett-Packard     | 30        | 14.15%  |
| Lenovo              | 24        | 11.32%  |
| MSI                 | 15        | 7.08%   |
| ASUSTek Computer    | 15        | 7.08%   |
| Gigabyte Technology | 14        | 6.6%    |
| Acer                | 13        | 6.13%   |
| Toshiba             | 9         | 4.25%   |
| ECS                 | 8         | 3.77%   |
| Sony                | 7         | 3.3%    |
| Unknown             | 7         | 3.3%    |
| Foxconn             | 5         | 2.36%   |
| Apple               | 5         | 2.36%   |
| Samsung Electronics | 3         | 1.42%   |
| Packard Bell        | 3         | 1.42%   |
| Intel               | 3         | 1.42%   |
| Biostar             | 3         | 1.42%   |
| Fujitsu             | 2         | 0.94%   |
| ASRock              | 2         | 0.94%   |
| Wistron             | 1         | 0.47%   |
| WeiBu               | 1         | 0.47%   |
| sunxi               | 1         | 0.47%   |
| Pegatron            | 1         | 0.47%   |
| Microsoft           | 1         | 0.47%   |
| LDLC                | 1         | 0.47%   |
| eMachines           | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 7         | 3.3%    |
| Toshiba Satellite C55-B       | 3         | 1.42%   |
| Intel H55                     | 3         | 1.42%   |
| ECS G41T-M7                   | 3         | 1.42%   |
| Dell Inspiron 3542            | 3         | 1.42%   |
| MSI MS-7758                   | 2         | 0.94%   |
| MSI MS-7636                   | 2         | 0.94%   |
| Lenovo IdeaPad 300-15ISK 80Q7 | 2         | 0.94%   |
| Lenovo G560 20042             | 2         | 0.94%   |
| Lenovo G50-30 80G0            | 2         | 0.94%   |
| Lenovo B50-70 20384           | 2         | 0.94%   |
| HP ProBook 4540s              | 2         | 0.94%   |
| HP Pavilion 15                | 2         | 0.94%   |
| HP 280 G1 MT                  | 2         | 0.94%   |
| HP 15                         | 2         | 0.94%   |
| Gigabyte B85M-DS3H-A          | 2         | 0.94%   |
| ECS H61H2-MV                  | 2         | 0.94%   |
| Dell Latitude E7440           | 2         | 0.94%   |
| Dell Latitude E5430 vPro      | 2         | 0.94%   |
| Dell Latitude 7480            | 2         | 0.94%   |
| Dell Inspiron N5110           | 2         | 0.94%   |
| Dell Inspiron 15-3567         | 2         | 0.94%   |
| Biostar P4M89-M7B             | 2         | 0.94%   |
| Acer Aspire 5738              | 2         | 0.94%   |
| Wistron ProLiant ML110 G5     | 1         | 0.47%   |
| WeiBu SIMM INT G-41D3 G1.0L   | 1         | 0.47%   |
| Toshiba Satellite C850-A979   | 1         | 0.47%   |
| Toshiba Satellite C50-A560    | 1         | 0.47%   |
| Toshiba Satellite C50-A545    | 1         | 0.47%   |
| Toshiba Satellite C50-A539    | 1         | 0.47%   |
| Toshiba PORTEGE R30-A         | 1         | 0.47%   |
| Toshiba PORTEGE M780          | 1         | 0.47%   |
| sunxi LeMaker Banana Pi       | 1         | 0.47%   |
| Sony VPCEJ2S1E                | 1         | 0.47%   |
| Sony VPCEH2H1E                | 1         | 0.47%   |
| Sony VGN-NS10J_S              | 1         | 0.47%   |
| Sony VGN-AW21M_H              | 1         | 0.47%   |
| Sony SVF1531GSFB              | 1         | 0.47%   |
| Sony SVE1713A6EW              | 1         | 0.47%   |
| Sony SVE1513K1EW              | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 13        | 6.13%   |
| Dell Latitude         | 12        | 5.66%   |
| Acer Aspire           | 10        | 4.72%   |
| HP ProBook            | 9         | 4.25%   |
| Toshiba Satellite     | 7         | 3.3%    |
| Unknown               | 7         | 3.3%    |
| Lenovo ThinkPad       | 6         | 2.83%   |
| Lenovo IdeaPad        | 5         | 2.36%   |
| HP Pavilion           | 5         | 2.36%   |
| HP EliteBook          | 4         | 1.89%   |
| Intel H55             | 3         | 1.42%   |
| ECS G41T-M7           | 3         | 1.42%   |
| Dell Vostro           | 3         | 1.42%   |
| Dell Precision        | 3         | 1.42%   |
| Dell OptiPlex         | 3         | 1.42%   |
| Toshiba PORTEGE       | 2         | 0.94%   |
| Packard Bell EasyNote | 2         | 0.94%   |
| MSI MS-7758           | 2         | 0.94%   |
| MSI MS-7636           | 2         | 0.94%   |
| Lenovo G580           | 2         | 0.94%   |
| Lenovo G560           | 2         | 0.94%   |
| Lenovo G50-30         | 2         | 0.94%   |
| Lenovo B50-70         | 2         | 0.94%   |
| HP 280                | 2         | 0.94%   |
| HP 15                 | 2         | 0.94%   |
| Gigabyte B85M-DS3H-A  | 2         | 0.94%   |
| Fujitsu LIFEBOOK      | 2         | 0.94%   |
| ECS H61H2-MV          | 2         | 0.94%   |
| Biostar P4M89-M7B     | 2         | 0.94%   |
| Acer Extensa          | 2         | 0.94%   |
| Wistron ProLiant      | 1         | 0.47%   |
| WeiBu SIMM            | 1         | 0.47%   |
| sunxi LeMaker         | 1         | 0.47%   |
| Sony VPCEJ2S1E        | 1         | 0.47%   |
| Sony VPCEH2H1E        | 1         | 0.47%   |
| Sony VGN-NS10J        | 1         | 0.47%   |
| Sony VGN-AW21M        | 1         | 0.47%   |
| Sony SVF1531GSFB      | 1         | 0.47%   |
| Sony SVE1713A6EW      | 1         | 0.47%   |
| Sony SVE1513K1EW      | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 39        | 18.4%   |
| 2013    | 28        | 13.21%  |
| 2014    | 25        | 11.79%  |
| 2015    | 19        | 8.96%   |
| 2011    | 18        | 8.49%   |
| 2010    | 15        | 7.08%   |
| 2017    | 13        | 6.13%   |
| 2016    | 13        | 6.13%   |
| 2018    | 11        | 5.19%   |
| 2009    | 11        | 5.19%   |
| 2008    | 5         | 2.36%   |
| 2007    | 5         | 2.36%   |
| 2019    | 4         | 1.89%   |
| 2021    | 2         | 0.94%   |
| 2020    | 2         | 0.94%   |
| 2006    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 130       | 61.32%  |
| Desktop        | 75        | 35.38%  |
| All in one     | 3         | 1.42%   |
| Tablet         | 2         | 0.94%   |
| System on chip | 1         | 0.47%   |
| Convertible    | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 209       | 98.58%  |
| Enabled  | 3         | 1.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 212       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 79        | 36.74%  |
| 4.01-8.0    | 53        | 24.65%  |
| 8.01-16.0   | 37        | 17.21%  |
| 1.01-2.0    | 18        | 8.37%   |
| 16.01-24.0  | 11        | 5.12%   |
| 2.01-3.0    | 7         | 3.26%   |
| 32.01-64.0  | 5         | 2.33%   |
| 0.51-1.0    | 4         | 1.86%   |
| 64.01-256.0 | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 113       | 48.71%  |
| 2.01-3.0  | 61        | 26.29%  |
| 3.01-4.0  | 23        | 9.91%   |
| 0.51-1.0  | 17        | 7.33%   |
| 4.01-8.0  | 11        | 4.74%   |
| 8.01-16.0 | 4         | 1.72%   |
| 0.01-0.5  | 3         | 1.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 144       | 66.67%  |
| 2      | 54        | 25%     |
| 3      | 12        | 5.56%   |
| 4      | 4         | 1.85%   |
| 0      | 2         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 61.68%  |
| No        | 82        | 38.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 93.4%   |
| No        | 14        | 6.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 78.04%  |
| No        | 47        | 21.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 114       | 52.53%  |
| Yes       | 103       | 47.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 212       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Algiers            | 34        | 14.41%  |
| Oran               | 11        | 4.66%   |
| Belcourt           | 11        | 4.66%   |
| Annaba             | 10        | 4.24%   |
| Tlemcen            | 9         | 3.81%   |
| Skikda             | 6         | 2.54%   |
| Sétif             | 6         | 2.54%   |
| Constantine        | 6         | 2.54%   |
| Tipasa             | 5         | 2.12%   |
| Blida              | 5         | 2.12%   |
| Biskra             | 5         | 2.12%   |
| Relizane           | 4         | 1.69%   |
| Mostaganem         | 4         | 1.69%   |
| Cheraga            | 4         | 1.69%   |
| Birkhadem          | 4         | 1.69%   |
| Béjaïa           | 4         | 1.69%   |
| Batna City         | 4         | 1.69%   |
| Tizi Ouzou         | 3         | 1.27%   |
| Sidi Akkacha       | 3         | 1.27%   |
| Ouargla            | 3         | 1.27%   |
| Laghouat           | 3         | 1.27%   |
| Jijelli            | 3         | 1.27%   |
| Ben ’Aknoûn     | 3         | 1.27%   |
| Bab Ezzouar        | 3         | 1.27%   |
| ash-Shalif         | 3         | 1.27%   |
| Tolga              | 2         | 0.85%   |
| Saoula             | 2         | 0.85%   |
| Saida              | 2         | 0.85%   |
| Ouenza             | 2         | 0.85%   |
| Kouba              | 2         | 0.85%   |
| Khenchela          | 2         | 0.85%   |
| El Aouinet         | 2         | 0.85%   |
| Draria             | 2         | 0.85%   |
| Djelfa             | 2         | 0.85%   |
| Bordj el Kiffan    | 2         | 0.85%   |
| Bordj Bou Arreridj | 2         | 0.85%   |
| Bir el Djir        | 2         | 0.85%   |
| Ain Fakroun        | 2         | 0.85%   |
| Ain Defla          | 2         | 0.85%   |
| Ain Beida          | 2         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 53        | 77     | 19.2%   |
| Seagate                   | 47        | 59     | 17.03%  |
| Toshiba                   | 31        | 33     | 11.23%  |
| Hitachi                   | 25        | 34     | 9.06%   |
| Samsung Electronics       | 22        | 24     | 7.97%   |
| HGST                      | 14        | 18     | 5.07%   |
| A-DATA Technology         | 14        | 15     | 5.07%   |
| SanDisk                   | 7         | 7      | 2.54%   |
| Lexar                     | 6         | 8      | 2.17%   |
| Unknown                   | 5         | 6      | 1.81%   |
| SK hynix                  | 4         | 6      | 1.45%   |
| Maxtor                    | 4         | 5      | 1.45%   |
| LITEON                    | 4         | 7      | 1.45%   |
| Realtek Semiconductor     | 3         | 3      | 1.09%   |
| Kingston                  | 3         | 3      | 1.09%   |
| Fujitsu                   | 3         | 4      | 1.09%   |
| XPG                       | 2         | 2      | 0.72%   |
| Team                      | 2         | 3      | 0.72%   |
| Silicon Motion            | 2         | 2      | 0.72%   |
| KESU                      | 2         | 2      | 0.72%   |
| Intel                     | 2         | 2      | 0.72%   |
| China                     | 2         | 2      | 0.72%   |
| Apple                     | 2         | 2      | 0.72%   |
| ZTE                       | 1         | 1      | 0.36%   |
| WD MediaMax               | 1         | 1      | 0.36%   |
| TwinMOS                   | 1         | 1      | 0.36%   |
| T-FORCE                   | 1         | 1      | 0.36%   |
| Smart                     | 1         | 1      | 0.36%   |
| PNY                       | 1         | 1      | 0.36%   |
| Micron/Crucial Technology | 1         | 1      | 0.36%   |
| Micron Technology         | 1         | 2      | 0.36%   |
| MDT                       | 1         | 1      | 0.36%   |
| Magnetic Data             | 1         | 1      | 0.36%   |
| Londisk                   | 1         | 1      | 0.36%   |
| KingSpec                  | 1         | 1      | 0.36%   |
| HUAWEI                    | 1         | 1      | 0.36%   |
| HS-SSD-E100               | 1         | 1      | 0.36%   |
| HS-SSD-C100               | 1         | 1      | 0.36%   |
| Hewlett-Packard           | 1         | 1      | 0.36%   |
| Crucial                   | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 9         | 3.09%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 4         | 1.37%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 1.37%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 1.37%   |
| HGST HTS545050A7E680 500GB             | 4         | 1.37%   |
| WDC WD10EZEX-08WN4A0 1TB               | 3         | 1.03%   |
| WDC WD10EZEX-00WN4A0 1TB               | 3         | 1.03%   |
| Toshiba DT01ACA100 1TB                 | 3         | 1.03%   |
| Toshiba DT01ACA050 500GB               | 3         | 1.03%   |
| Seagate ST9500325AS 500GB              | 3         | 1.03%   |
| Seagate ST500LT012-9WS142 500GB        | 3         | 1.03%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 1.03%   |
| Seagate Expansion 240GB                | 3         | 1.03%   |
| Lexar 512GB SSD                        | 3         | 1.03%   |
| Hitachi HTS545050B9A300 500GB          | 3         | 1.03%   |
| Hitachi HTS545050A7E380 500GB          | 3         | 1.03%   |
| HGST HTS545050A7E380 500GB             | 3         | 1.03%   |
| A-DATA SU630 240GB SSD                 | 3         | 1.03%   |
| XPG SX950U 240GB                       | 2         | 0.69%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.69%   |
| WDC WD5000AVVS-63M8B0 500GB            | 2         | 0.69%   |
| Unknown MMC Card  64GB                 | 2         | 0.69%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.69%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.69%   |
| Seagate ST3500312CS 500GB              | 2         | 0.69%   |
| Seagate ST320LT020-9YG142 320GB        | 2         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.69%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.69%   |
| Lexar 128GB SSD                        | 2         | 0.69%   |
| Hitachi HDS721616PLA380 160GB          | 2         | 0.69%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.69%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.69%   |
| A-DATA SU650 120GB SSD                 | 2         | 0.69%   |
| ZTE MMC Storage 942MB                  | 1         | 0.34%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.34%   |
| WDC WDS100T2B0B-00YS70 1TB SSD         | 1         | 0.34%   |
| WDC WD800JD-55MUA1 80GB                | 1         | 0.34%   |
| WDC WD7500BPKX-75HPJT0 752GB           | 1         | 0.34%   |
| WDC WD7500AYYS-01RCA0 752GB            | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 51        | 71     | 26.84%  |
| Seagate             | 47        | 59     | 24.74%  |
| Toshiba             | 31        | 33     | 16.32%  |
| Hitachi             | 25        | 34     | 13.16%  |
| HGST                | 14        | 18     | 7.37%   |
| Samsung Electronics | 10        | 11     | 5.26%   |
| Maxtor              | 4         | 5      | 2.11%   |
| Fujitsu             | 3         | 4      | 1.58%   |
| WD MediaMax         | 1         | 1      | 0.53%   |
| Magnetic Data       | 1         | 1      | 0.53%   |
| KESU                | 1         | 1      | 0.53%   |
| Hewlett-Packard     | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 11        | 12     | 20.37%  |
| SanDisk             | 5         | 5      | 9.26%   |
| Samsung Electronics | 5         | 5      | 9.26%   |
| Lexar               | 5         | 7      | 9.26%   |
| WDC                 | 4         | 6      | 7.41%   |
| LITEON              | 4         | 7      | 7.41%   |
| SK hynix            | 3         | 5      | 5.56%   |
| XPG                 | 2         | 2      | 3.7%    |
| Kingston            | 2         | 2      | 3.7%    |
| Intel               | 2         | 2      | 3.7%    |
| China               | 2         | 2      | 3.7%    |
| TwinMOS             | 1         | 1      | 1.85%   |
| Team                | 1         | 2      | 1.85%   |
| T-FORCE             | 1         | 1      | 1.85%   |
| PNY                 | 1         | 1      | 1.85%   |
| Londisk             | 1         | 1      | 1.85%   |
| KingSpec            | 1         | 1      | 1.85%   |
| HS-SSD-C100         | 1         | 1      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 169       | 240    | 68.15%  |
| SSD     | 49        | 65     | 19.76%  |
| NVMe    | 17        | 22     | 6.85%   |
| Unknown | 7         | 7      | 2.82%   |
| MMC     | 6         | 8      | 2.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 195       | 302    | 85.9%   |
| NVMe | 17        | 22     | 7.49%   |
| SAS  | 9         | 10     | 3.96%   |
| MMC  | 6         | 8      | 2.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 159       | 235    | 72.94%  |
| 0.51-1.0   | 53        | 64     | 24.31%  |
| 1.01-2.0   | 6         | 6      | 2.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 58        | 25.78%  |
| 101-250    | 40        | 17.78%  |
| 51-100     | 38        | 16.89%  |
| 1-20       | 28        | 12.44%  |
| 501-1000   | 26        | 11.56%  |
| 21-50      | 17        | 7.56%   |
| 1001-2000  | 13        | 5.78%   |
| Unknown    | 3         | 1.33%   |
| 2001-3000  | 2         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 115       | 49.36%  |
| 21-50     | 39        | 16.74%  |
| 101-250   | 29        | 12.45%  |
| 51-100    | 21        | 9.01%   |
| 251-500   | 15        | 6.44%   |
| 501-1000  | 8         | 3.43%   |
| 1001-2000 | 3         | 1.29%   |
| Unknown   | 3         | 1.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB             | 2         | 2      | 5.13%   |
| WDC WD5000LUCT-62C26Y0 500GB                | 1         | 1      | 2.56%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 2.56%   |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 2.56%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 2.56%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 2.56%   |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 2.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 2.56%   |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 2.56%   |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 2.56%   |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 2.56%   |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 2.56%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 2.56%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.56%   |
| Seagate ST9500325AS 500GB                   | 1         | 1      | 2.56%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 2.56%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 2.56%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 2.56%   |
| Seagate ST500LM021-1KJ152 500GB             | 1         | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 2.56%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 2.56%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 2.56%   |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 2.56%   |
| Samsung Electronics HD502HI 500GB           | 1         | 1      | 2.56%   |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 2.56%   |
| Samsung Electronics HD160JJ 160GB           | 1         | 1      | 2.56%   |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 2.56%   |
| Maxtor 6L300S0 304GB                        | 1         | 1      | 2.56%   |
| Maxtor 32049H2 20GB                         | 1         | 1      | 2.56%   |
| Magnetic Data MD07500-ALDW-RO 752GB         | 1         | 1      | 2.56%   |
| Hitachi HTS723225L9A360 250GB               | 1         | 1      | 2.56%   |
| Hitachi HTS722010K9SA00 100GB               | 1         | 1      | 2.56%   |
| Hitachi HTS547564A9E384 640GB               | 1         | 1      | 2.56%   |
| Hitachi HTS545050B9A300 500GB               | 1         | 1      | 2.56%   |
| Hitachi HTS542516K9SA00 160GB               | 1         | 1      | 2.56%   |
| Hitachi HDS721032CLA362 320GB               | 1         | 1      | 2.56%   |
| HGST HTS725050A7E630 500GB                  | 1         | 3      | 2.56%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 23.68%  |
| Seagate             | 9         | 9      | 23.68%  |
| Samsung Electronics | 6         | 6      | 15.79%  |
| Hitachi             | 6         | 6      | 15.79%  |
| Toshiba             | 2         | 2      | 5.26%   |
| Maxtor              | 2         | 2      | 5.26%   |
| HGST                | 2         | 4      | 5.26%   |
| WD MediaMax         | 1         | 1      | 2.63%   |
| Magnetic Data       | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 24.32%  |
| Seagate             | 9         | 9      | 24.32%  |
| Hitachi             | 6         | 6      | 16.22%  |
| Samsung Electronics | 5         | 5      | 13.51%  |
| Toshiba             | 2         | 2      | 5.41%   |
| Maxtor              | 2         | 2      | 5.41%   |
| HGST                | 2         | 4      | 5.41%   |
| WD MediaMax         | 1         | 1      | 2.7%    |
| Magnetic Data       | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 40     | 97.22%  |
| SSD  | 1         | 1      | 2.78%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 138       | 229    | 60.79%  |
| Works    | 53        | 72     | 23.35%  |
| Malfunc  | 36        | 41     | 15.86%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 184       | 80.7%   |
| AMD                         | 12        | 5.26%   |
| Samsung Electronics         | 7         | 3.07%   |
| Realtek Semiconductor       | 5         | 2.19%   |
| Nvidia                      | 4         | 1.75%   |
| VIA Technologies            | 3         | 1.32%   |
| Silicon Motion              | 3         | 1.32%   |
| JMicron Technology          | 2         | 0.88%   |
| ASMedia Technology          | 2         | 0.88%   |
| SanDisk                     | 1         | 0.44%   |
| Micron/Crucial Technology   | 1         | 0.44%   |
| Micron Technology           | 1         | 0.44%   |
| MAXIO Technology (Hangzhou) | 1         | 0.44%   |
| Marvell Technology Group    | 1         | 0.44%   |
| Kingston Technology Company | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 26        | 9.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 18        | 6.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 5.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 4.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11        | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 4%      |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 3.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 2.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 2.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 2.55%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 2.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 2.18%   |
| Realtek Realtek Non-Volatile memory controller                                          | 5         | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.45%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 1.09%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.09%   |
| VIA Serial ATA Controller                                                               | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.73%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.73%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 2         | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 0.73%   |
| VIA VT8237/8251 Serial ATA Controller                                                   | 1         | 0.36%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.36%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.36%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 145       | 63.6%   |
| IDE  | 51        | 22.37%  |
| NVMe | 17        | 7.46%   |
| RAID | 15        | 6.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 196       | 92.45%  |
| AMD    | 15        | 7.08%   |
| ARM    | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-3217U CPU @ 1.80GHz           | 6         | 2.83%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 2.83%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5         | 2.36%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 4         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.89%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 1.89%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 1.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.42%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 1.42%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3         | 1.42%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 1.42%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 1.42%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.42%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 1.42%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 1.42%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 2         | 0.94%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.94%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 0.94%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2         | 0.94%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.94%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.94%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 2         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.94%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 0.94%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 2         | 0.94%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 0.94%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 0.94%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 0.94%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 0.94%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i3           | 58        | 27.36%  |
| Intel Core i5           | 49        | 23.11%  |
| Intel Core i7           | 26        | 12.26%  |
| Intel Pentium           | 15        | 7.08%   |
| Intel Pentium Dual-Core | 13        | 6.13%   |
| Intel Core 2 Duo        | 12        | 5.66%   |
| Intel Celeron           | 7         | 3.3%    |
| Intel Atom              | 5         | 2.36%   |
| Intel Xeon              | 3         | 1.42%   |
| Intel Pentium Dual      | 3         | 1.42%   |
| AMD Ryzen 7             | 3         | 1.42%   |
| AMD Ryzen 5             | 2         | 0.94%   |
| Other                   | 1         | 0.47%   |
| Intel Pentium D         | 1         | 0.47%   |
| Intel Pentium 4         | 1         | 0.47%   |
| Intel Genuine           | 1         | 0.47%   |
| Intel Core 2 Quad       | 1         | 0.47%   |
| ARM Allwinner           | 1         | 0.47%   |
| AMD Ryzen 9             | 1         | 0.47%   |
| AMD Ryzen 5 PRO         | 1         | 0.47%   |
| AMD Ryzen 3             | 1         | 0.47%   |
| AMD FX                  | 1         | 0.47%   |
| AMD E2                  | 1         | 0.47%   |
| AMD E1                  | 1         | 0.47%   |
| AMD Athlon Neo X2       | 1         | 0.47%   |
| AMD Athlon II Dual-Core | 1         | 0.47%   |
| AMD Athlon 64           | 1         | 0.47%   |
| AMD A4                  | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 161       | 75.94%  |
| 4      | 35        | 16.51%  |
| 6      | 6         | 2.83%   |
| 1      | 5         | 2.36%   |
| 8      | 3         | 1.42%   |
| 16     | 1         | 0.47%   |
| 3      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 212       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 136       | 64.15%  |
| 1      | 75        | 35.38%  |
| 4      | 1         | 0.47%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 208       | 97.65%  |
| Unknown        | 4         | 1.88%   |
| 32-bit         | 1         | 0.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 20.91%  |
| 0x306a9    | 31        | 14.09%  |
| 0x206a7    | 18        | 8.18%   |
| 0x1067a    | 18        | 8.18%   |
| 0x20655    | 16        | 7.27%   |
| 0x40651    | 11        | 5%      |
| 0x406e3    | 9         | 4.09%   |
| 0x306d4    | 8         | 3.64%   |
| 0x306c3    | 7         | 3.18%   |
| 0x30678    | 7         | 3.18%   |
| 0x806e9    | 6         | 2.73%   |
| 0x906e9    | 4         | 1.82%   |
| 0x806ea    | 4         | 1.82%   |
| 0x6fd      | 4         | 1.82%   |
| 0x20652    | 3         | 1.36%   |
| 0x6fb      | 2         | 0.91%   |
| 0x506e3    | 2         | 0.91%   |
| 0x306e4    | 2         | 0.91%   |
| 0x30661    | 2         | 0.91%   |
| 0x0800820d | 2         | 0.91%   |
| 0xf65      | 1         | 0.45%   |
| 0x906eb    | 1         | 0.45%   |
| 0x806ec    | 1         | 0.45%   |
| 0x806c1    | 1         | 0.45%   |
| 0x6ec      | 1         | 0.45%   |
| 0x506c9    | 1         | 0.45%   |
| 0x406c4    | 1         | 0.45%   |
| 0x406c3    | 1         | 0.45%   |
| 0x10676    | 1         | 0.45%   |
| 0x0a201016 | 1         | 0.45%   |
| 0x08701021 | 1         | 0.45%   |
| 0x08608103 | 1         | 0.45%   |
| 0x08600106 | 1         | 0.45%   |
| 0x0810100b | 1         | 0.45%   |
| 0x0700010f | 1         | 0.45%   |
| 0x06006705 | 1         | 0.45%   |
| 0x0600063d | 1         | 0.45%   |
| 0x05000119 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 41        | 19.34%  |
| Haswell       | 26        | 12.26%  |
| SandyBridge   | 23        | 10.85%  |
| Penryn        | 22        | 10.38%  |
| Westmere      | 19        | 8.96%   |
| KabyLake      | 18        | 8.49%   |
| Skylake       | 13        | 6.13%   |
| Silvermont    | 10        | 4.72%   |
| Core          | 8         | 3.77%   |
| Broadwell     | 8         | 3.77%   |
| Zen 2         | 3         | 1.42%   |
| Zen+          | 2         | 0.94%   |
| NetBurst      | 2         | 0.94%   |
| K8 Hammer     | 2         | 0.94%   |
| Bonnell       | 2         | 0.94%   |
| Unknown       | 2         | 0.94%   |
| Zen 3         | 1         | 0.47%   |
| Zen           | 1         | 0.47%   |
| TigerLake     | 1         | 0.47%   |
| P6            | 1         | 0.47%   |
| K10           | 1         | 0.47%   |
| Jaguar        | 1         | 0.47%   |
| Goldmont plus | 1         | 0.47%   |
| Goldmont      | 1         | 0.47%   |
| Excavator     | 1         | 0.47%   |
| Bulldozer     | 1         | 0.47%   |
| Bobcat        | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 154       | 61.85%  |
| Nvidia                     | 47        | 18.88%  |
| AMD                        | 45        | 18.07%  |
| VIA Technologies           | 2         | 0.8%    |
| Matrox Electronics Systems | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 9.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 5.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 4.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 4%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 3.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.2%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8         | 3.2%    |
| Intel HD Graphics 620                                                                    | 7         | 2.8%    |
| Intel HD Graphics 5500                                                                   | 6         | 2.4%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 2.4%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.6%    |
| Intel UHD Graphics 620                                                                   | 4         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.6%    |
| Intel HD Graphics 630                                                                    | 4         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.6%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 3         | 1.2%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.8%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.8%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.8%    |
| Nvidia G98M [GeForce 9300M GS]                                                           | 2         | 0.8%    |
| Intel HD Graphics 530                                                                    | 2         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.8%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.8%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.8%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.8%    |
| AMD Renoir                                                                               | 2         | 0.8%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.8%    |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.4%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.4%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.4%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.4%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.4%    |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.4%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 119       | 55.61%  |
| 1 x Nvidia     | 28        | 13.08%  |
| 1 x AMD        | 28        | 13.08%  |
| Intel + Nvidia | 18        | 8.41%   |
| Intel + AMD    | 16        | 7.48%   |
| 1 x VIA        | 2         | 0.93%   |
| Other          | 1         | 0.47%   |
| 1 x Matrox     | 1         | 0.47%   |
| AMD + Nvidia   | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 187       | 86.18%  |
| Proprietary | 21        | 9.68%   |
| Unknown     | 9         | 4.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 62.21%  |
| 1.01-2.0   | 44        | 20.28%  |
| 0.01-0.5   | 15        | 6.91%   |
| 0.51-1.0   | 14        | 6.45%   |
| 3.01-4.0   | 7         | 3.23%   |
| 7.01-8.0   | 2         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 20.2%   |
| LG Display              | 31        | 15.27%  |
| AU Optronics            | 25        | 12.32%  |
| Chimei Innolux          | 14        | 6.9%    |
| BOE                     | 14        | 6.9%    |
| Hewlett-Packard         | 13        | 6.4%    |
| AOC                     | 11        | 5.42%   |
| Chi Mei Optoelectronics | 8         | 3.94%   |
| KTC                     | 5         | 2.46%   |
| Apple                   | 5         | 2.46%   |
| Acer                    | 4         | 1.97%   |
| Dell                    | 3         | 1.48%   |
| BenQ                    | 3         | 1.48%   |
| Ancor Communications    | 3         | 1.48%   |
| Unknown                 | 3         | 1.48%   |
| Unknown (XXX)           | 2         | 0.99%   |
| Lenovo                  | 2         | 0.99%   |
| Goldstar                | 2         | 0.99%   |
| ___                     | 1         | 0.49%   |
| Unknown                 | 1         | 0.49%   |
| TSN                     | 1         | 0.49%   |
| SKY                     | 1         | 0.49%   |
| Sharp                   | 1         | 0.49%   |
| PTW                     | 1         | 0.49%   |
| PiLot                   | 1         | 0.49%   |
| PANDA                   | 1         | 0.49%   |
| MStar                   | 1         | 0.49%   |
| LGD                     | 1         | 0.49%   |
| ITE                     | 1         | 0.49%   |
| InnoLux Display         | 1         | 0.49%   |
| EMP                     | 1         | 0.49%   |
| AGO                     | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 1.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 1.46%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 1.46%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 3         | 1.46%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.46%   |
| AOC V22 AOC2200 1680x1050 526x296mm 23.8-inch                            | 3         | 1.46%   |
| Unknown                                                                  | 3         | 1.46%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 2         | 0.97%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 2         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.97%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 0.97%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 0.97%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.97%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.97%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.97%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.97%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 0.97%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.97%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 0.97%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.97%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 0.97%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.49%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.49%   |
| TSN 24 Monitor TSN2400 1360x768 510x287mm 23.0-inch                      | 1         | 0.49%   |
| SKY TV-monitor SKY0104 1920x1080 885x498mm 40.0-inch                     | 1         | 0.49%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch     | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM04D5 1920x1080                         | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch     | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM00A6 1280x1024 380x310mm 19.3-inch     | 1         | 0.49%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch        | 1         | 0.49%   |
| Samsung Electronics SMBX2031N SAM0769 1600x900 443x249mm 20.0-inch       | 1         | 0.49%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch       | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 97        | 49.49%  |
| 1920x1080 (FHD)    | 53        | 27.04%  |
| 1600x900 (HD+)     | 10        | 5.1%    |
| 1440x900 (WXGA+)   | 8         | 4.08%   |
| 2560x1440 (QHD)    | 4         | 2.04%   |
| 1680x1050 (WSXGA+) | 4         | 2.04%   |
| 1280x800 (WXGA)    | 4         | 2.04%   |
| 1360x768           | 3         | 1.53%   |
| 1280x1024 (SXGA)   | 3         | 1.53%   |
| 3840x2160 (4K)     | 2         | 1.02%   |
| 1920x1200 (WUXGA)  | 2         | 1.02%   |
| 2160x1440          | 1         | 0.51%   |
| 1920x540           | 1         | 0.51%   |
| 1680x945           | 1         | 0.51%   |
| 1600x1200          | 1         | 0.51%   |
| 1280x720 (HD)      | 1         | 0.51%   |
| 1024x600           | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 84        | 41.18%  |
| 18      | 16        | 7.84%   |
| 13      | 14        | 6.86%   |
| 21      | 13        | 6.37%   |
| 14      | 9         | 4.41%   |
| 23      | 8         | 3.92%   |
| 17      | 8         | 3.92%   |
| 19      | 7         | 3.43%   |
| 12      | 7         | 3.43%   |
| Unknown | 7         | 3.43%   |
| 27      | 6         | 2.94%   |
| 24      | 5         | 2.45%   |
| 20      | 5         | 2.45%   |
| 52      | 3         | 1.47%   |
| 22      | 2         | 0.98%   |
| 11      | 2         | 0.98%   |
| 10      | 2         | 0.98%   |
| 46      | 1         | 0.49%   |
| 40      | 1         | 0.49%   |
| 37      | 1         | 0.49%   |
| 32      | 1         | 0.49%   |
| 31      | 1         | 0.49%   |
| 16      | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 50%     |
| 401-500     | 39        | 19.31%  |
| 501-600     | 19        | 9.41%   |
| 201-300     | 16        | 7.92%   |
| 351-400     | 12        | 5.94%   |
| Unknown     | 7         | 3.47%   |
| 1001-1500   | 4         | 1.98%   |
| 801-900     | 2         | 0.99%   |
| 701-800     | 1         | 0.5%    |
| 601-700     | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 162       | 83.94%  |
| 16/10   | 17        | 8.81%   |
| Unknown | 6         | 3.11%   |
| 5/4     | 3         | 1.55%   |
| 4/3     | 2         | 1.04%   |
| 6/5     | 1         | 0.52%   |
| 32/9    | 1         | 0.52%   |
| 3/2     | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 83        | 40.89%  |
| 201-250        | 21        | 10.34%  |
| 81-90          | 19        | 9.36%   |
| 151-200        | 18        | 8.87%   |
| 141-150        | 17        | 8.37%   |
| Unknown        | 7         | 3.45%   |
| 61-70          | 6         | 2.96%   |
| 301-350        | 6         | 2.96%   |
| 71-80          | 5         | 2.46%   |
| 121-130        | 4         | 1.97%   |
| More than 1000 | 3         | 1.48%   |
| 501-1000       | 3         | 1.48%   |
| 51-60          | 2         | 0.99%   |
| 351-500        | 2         | 0.99%   |
| 41-50          | 2         | 0.99%   |
| 131-140        | 2         | 0.99%   |
| 111-120        | 2         | 0.99%   |
| 251-300        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 91        | 45.5%   |
| 51-100  | 62        | 31%     |
| 121-160 | 30        | 15%     |
| Unknown | 7         | 3.5%    |
| 1-50    | 5         | 2.5%    |
| 161-240 | 5         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 191       | 88.84%  |
| 2     | 14        | 6.51%   |
| 0     | 9         | 4.19%   |
| 3     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 127       | 36.92%  |
| Qualcomm Atheros                | 56        | 16.28%  |
| Intel                           | 55        | 15.99%  |
| Broadcom                        | 35        | 10.17%  |
| Ralink Technology               | 20        | 5.81%   |
| Ralink                          | 10        | 2.91%   |
| Broadcom Limited                | 5         | 1.45%   |
| Qualcomm Atheros Communications | 4         | 1.16%   |
| MediaTek                        | 4         | 1.16%   |
| Marvell Technology Group        | 4         | 1.16%   |
| VIA Technologies                | 3         | 0.87%   |
| Samsung Electronics             | 3         | 0.87%   |
| Nvidia                          | 3         | 0.87%   |
| D-Link System                   | 3         | 0.87%   |
| Xiaomi                          | 2         | 0.58%   |
| TP-Link                         | 2         | 0.58%   |
| Huawei Technologies             | 2         | 0.58%   |
| D-Link                          | 2         | 0.58%   |
| Sierra Wireless                 | 1         | 0.29%   |
| LG Electronics                  | 1         | 0.29%   |
| Hewlett-Packard                 | 1         | 0.29%   |
| AMD                             | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 19.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 11.93%  |
| Broadcom BCM43142 802.11b/g/n                                     | 13        | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 2.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 2.79%   |
| Ralink MT7601U Wireless Adapter                                   | 8         | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.27%   |
| Ralink RT5370 Wireless Adapter                                    | 5         | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5         | 1.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 1.02%   |
| Intel Wireless 8260                                               | 4         | 1.02%   |
| Intel Wireless 7265                                               | 4         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.76%   |
| MediaTek File-CD Gadget                                           | 3         | 0.76%   |
| Intel Wireless 7260                                               | 3         | 0.76%   |
| Intel Wireless 3160                                               | 3         | 0.76%   |
| Intel WiFi Link 5100                                              | 3         | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.51%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 46        | 25%     |
| Intel                           | 46        | 25%     |
| Broadcom                        | 26        | 14.13%  |
| Ralink Technology               | 20        | 10.87%  |
| Realtek Semiconductor           | 19        | 10.33%  |
| Ralink                          | 10        | 5.43%   |
| Qualcomm Atheros Communications | 4         | 2.17%   |
| D-Link System                   | 3         | 1.63%   |
| TP-Link                         | 2         | 1.09%   |
| D-Link                          | 2         | 1.09%   |
| Broadcom Limited                | 2         | 1.09%   |
| Sierra Wireless                 | 1         | 0.54%   |
| MediaTek                        | 1         | 0.54%   |
| Marvell Technology Group        | 1         | 0.54%   |
| Hewlett-Packard                 | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 13        | 7.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 11        | 5.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 11        | 5.98%   |
| Ralink MT7601U Wireless Adapter                                      | 8         | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 8         | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 3.8%    |
| Intel Wireless 8265 / 8275                                           | 6         | 3.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 2.72%   |
| Ralink RT5370 Wireless Adapter                                       | 5         | 2.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 2.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 2.17%   |
| Intel Wireless 8260                                                  | 4         | 2.17%   |
| Intel Wireless 7265                                                  | 4         | 2.17%   |
| Intel Wireless 7260                                                  | 3         | 1.63%   |
| Intel Wireless 3160                                                  | 3         | 1.63%   |
| Intel WiFi Link 5100                                                 | 3         | 1.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 1.63%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 1.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 1.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2         | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 1.09%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.09%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.09%   |
| Intel Centrino Wireless-N 135                                        | 2         | 1.09%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.09%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2         | 1.09%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 1.09%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.54%   |
| Sierra Wireless EM7305                                               | 1         | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.54%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.54%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 122       | 58.65%  |
| Intel                    | 35        | 16.83%  |
| Qualcomm Atheros         | 15        | 7.21%   |
| Broadcom                 | 13        | 6.25%   |
| VIA Technologies         | 3         | 1.44%   |
| Samsung Electronics      | 3         | 1.44%   |
| Nvidia                   | 3         | 1.44%   |
| MediaTek                 | 3         | 1.44%   |
| Marvell Technology Group | 3         | 1.44%   |
| Broadcom Limited         | 3         | 1.44%   |
| Xiaomi                   | 2         | 0.96%   |
| LG Electronics           | 1         | 0.48%   |
| Huawei Technologies      | 1         | 0.48%   |
| AMD                      | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 35.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 22.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 2.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.91%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 1.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.44%   |
| MediaTek File-CD Gadget                                           | 3         | 1.44%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.96%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.96%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.96%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.96%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.96%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.48%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.48%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.48%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.48%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.48%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.48%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.48%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.48%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 197       | 53.97%  |
| WiFi     | 167       | 45.75%  |
| Modem    | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 65.71%  |
| Ethernet | 72        | 34.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 134       | 62.04%  |
| 1     | 77        | 35.65%  |
| 0     | 4         | 1.85%   |
| 3     | 1         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 212       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 27.18%  |
| Qualcomm Atheros Communications | 13        | 12.62%  |
| Broadcom                        | 11        | 10.68%  |
| Realtek Semiconductor           | 7         | 6.8%    |
| Foxconn / Hon Hai               | 6         | 5.83%   |
| Lite-On Technology              | 5         | 4.85%   |
| Cambridge Silicon Radio         | 5         | 4.85%   |
| Apple                           | 5         | 4.85%   |
| Ralink                          | 4         | 3.88%   |
| IMC Networks                    | 4         | 3.88%   |
| Dell                            | 4         | 3.88%   |
| Foxconn International           | 3         | 2.91%   |
| Toshiba                         | 2         | 1.94%   |
| Ralink Technology               | 1         | 0.97%   |
| Marvell Semiconductor           | 1         | 0.97%   |
| Integrated System Solution      | 1         | 0.97%   |
| Hewlett-Packard                 | 1         | 0.97%   |
| Chicony Electronics             | 1         | 0.97%   |
| Alps Electric                   | 1         | 0.97%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 20        | 19.42%  |
| Qualcomm Atheros  Bluetooth Device                    | 5         | 4.85%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 4.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5         | 4.85%   |
| Ralink RT3290 Bluetooth                               | 4         | 3.88%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 3.88%   |
| Realtek Bluetooth Radio                               | 3         | 2.91%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3         | 2.91%   |
| IMC Networks Bluetooth Device                         | 3         | 2.91%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 2.91%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3         | 2.91%   |
| Toshiba Bluetooth Device                              | 2         | 1.94%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 2         | 1.94%   |
| Lite-On Bluetooth Device                              | 2         | 1.94%   |
| Dell Wireless 365 Bluetooth                           | 2         | 1.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 1.94%   |
| Apple Bluetooth USB Host Controller                   | 2         | 1.94%   |
| Apple Bluetooth Host Controller                       | 2         | 1.94%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.97%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.97%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.97%   |
| Qualcomm Atheros Bluetooth                            | 1         | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.97%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.97%   |
| Lite-On Wireless_Device                               | 1         | 0.97%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 0.97%   |
| Lite-On BCM43142A0                                    | 1         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 0.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1         | 0.97%   |
| Intel AX200 Bluetooth                                 | 1         | 0.97%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.97%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 0.97%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.97%   |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 0.97%   |
| Foxconn / Hon Hai Acer Module                         | 1         | 0.97%   |
| Dell DW375 Bluetooth Module                           | 1         | 0.97%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.97%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 186       | 71.26%  |
| AMD                   | 36        | 13.79%  |
| Nvidia                | 29        | 11.11%  |
| VIA Technologies      | 3         | 1.15%   |
| JMTek                 | 2         | 0.77%   |
| Texas Instruments     | 1         | 0.38%   |
| Medeli Electronics    | 1         | 0.38%   |
| Logitech              | 1         | 0.38%   |
| Logic3 / SpectraVideo | 1         | 0.38%   |
| Guillemot             | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 35        | 11.59%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29        | 9.6%    |
| Intel Sunrise Point-LP HD Audio                                                   | 22        | 7.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 19        | 6.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 16        | 5.3%    |
| Intel Haswell-ULT HD Audio Controller                                             | 14        | 4.64%   |
| Intel 8 Series HD Audio Controller                                                | 14        | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12        | 3.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 10        | 3.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 9         | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8         | 2.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 8         | 2.65%   |
| Intel Broadwell-U Audio Controller                                                | 8         | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 6         | 1.99%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5         | 1.66%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 1.32%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4         | 1.32%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 3         | 0.99%   |
| Nvidia High Definition Audio Controller                                           | 3         | 0.99%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 0.99%   |
| Nvidia MCP79 High Definition Audio                                                | 2         | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2         | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.66%   |
| JMTek USB PnP Audio Device(EEPROM)                                                | 2         | 0.66%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 0.66%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 0.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 0.66%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 0.66%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 0.66%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2         | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.66%   |
| AMD FCH Azalia Controller                                                         | 2         | 0.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.66%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.66%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 2         | 0.66%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.33%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 30        | 22.73%  |
| Samsung Electronics | 28        | 21.21%  |
| SK hynix            | 24        | 18.18%  |
| Micron Technology   | 17        | 12.88%  |
| Kingston            | 9         | 6.82%   |
| A-DATA Technology   | 9         | 6.82%   |
| TwinMOS             | 3         | 2.27%   |
| Nanya Technology    | 3         | 2.27%   |
| Thermaltake         | 1         | 0.76%   |
| Team                | 1         | 0.76%   |
| Ramaxel Technology  | 1         | 0.76%   |
| Patriot             | 1         | 0.76%   |
| GeIL                | 1         | 0.76%   |
| Elpida              | 1         | 0.76%   |
| Dynet               | 1         | 0.76%   |
| Crucial             | 1         | 0.76%   |
| ASint Technology    | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 4         | 2.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 2.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 3         | 2.07%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 2         | 1.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 2         | 1.38%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 2         | 1.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2         | 1.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 2         | 1.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 1.38%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 2         | 1.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.38%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 1.38%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 1.38%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR2                        | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM SDRAM                         | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                 | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR2                     | 1         | 0.69%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1333MT/s             | 1         | 0.69%   |
| Unknown RAM Module 4096MB DIMM SDRAM                      | 1         | 0.69%   |
| Unknown RAM Module 4096MB DIMM DDR3 800MT/s               | 1         | 0.69%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s               | 1         | 0.69%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1         | 0.69%   |
| Unknown RAM Module 2GB DIMM 667MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s              | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s             | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 1         | 0.69%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                  | 1         | 0.69%   |
| Unknown RAM Module 1GB DIMM 800MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 1GB DIMM 533MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s               | 1         | 0.69%   |
| Unknown RAM Module 1024MB DIMM DDR2 200MT/s               | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 62        | 57.41%  |
| DDR4    | 23        | 21.3%   |
| SDRAM   | 8         | 7.41%   |
| DDR2    | 8         | 7.41%   |
| Unknown | 5         | 4.63%   |
| LPDDR4  | 1         | 0.93%   |
| DDR     | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 65        | 62.5%   |
| DIMM   | 39        | 37.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 55        | 45.83%  |
| 2048  | 30        | 25%     |
| 8192  | 22        | 18.33%  |
| 1024  | 6         | 5%      |
| 16384 | 4         | 3.33%   |
| 32768 | 2         | 1.67%   |
| 512   | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 32.2%   |
| 1333    | 17        | 14.41%  |
| 2667    | 10        | 8.47%   |
| 800     | 7         | 5.93%   |
| Unknown | 6         | 5.08%   |
| 2400    | 5         | 4.24%   |
| 1334    | 5         | 4.24%   |
| 667     | 4         | 3.39%   |
| 4199    | 3         | 2.54%   |
| 3200    | 3         | 2.54%   |
| 2133    | 3         | 2.54%   |
| 1067    | 3         | 2.54%   |
| 3266    | 2         | 1.69%   |
| 3800    | 1         | 0.85%   |
| 3400    | 1         | 0.85%   |
| 3066    | 1         | 0.85%   |
| 3000    | 1         | 0.85%   |
| 2666    | 1         | 0.85%   |
| 2200    | 1         | 0.85%   |
| 1648    | 1         | 0.85%   |
| 1639    | 1         | 0.85%   |
| 533     | 1         | 0.85%   |
| 333     | 1         | 0.85%   |
| 266     | 1         | 0.85%   |
| 200     | 1         | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 9         | 64.29%  |
| Seiko Epson        | 3         | 21.43%  |
| Hewlett-Packard    | 1         | 7.14%   |
| Brother Industries | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6020                     | 2         | 14.29%  |
| Canon LBP6000                     | 2         | 14.29%  |
| Seiko Epson XP-243 245 247 Series | 1         | 7.14%   |
| Seiko Epson XP-200 Series         | 1         | 7.14%   |
| Seiko Epson Printer               | 1         | 7.14%   |
| HP DeskJet 5810 series            | 1         | 7.14%   |
| Canon MG5700 series               | 1         | 7.14%   |
| Canon MF3010                      | 1         | 7.14%   |
| Canon LBP6030w/6018w              | 1         | 7.14%   |
| Canon LBP3000                     | 1         | 7.14%   |
| Canon LBP2900                     | 1         | 7.14%   |
| Brother MFC-J480DW                | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 23.02%  |
| Microdia                               | 21        | 16.67%  |
| Cheng Uei Precision Industry (Foxlink) | 11        | 8.73%   |
| Realtek Semiconductor                  | 10        | 7.94%   |
| Acer                                   | 10        | 7.94%   |
| Sunplus Innovation Technology          | 7         | 5.56%   |
| Suyin                                  | 5         | 3.97%   |
| Apple                                  | 5         | 3.97%   |
| Syntek                                 | 4         | 3.17%   |
| IMC Networks                           | 4         | 3.17%   |
| Silicon Motion                         | 3         | 2.38%   |
| Samsung Electronics                    | 2         | 1.59%   |
| Quanta                                 | 2         | 1.59%   |
| Lite-On Technology                     | 2         | 1.59%   |
| Alcor Micro                            | 2         | 1.59%   |
| Ricoh                                  | 1         | 0.79%   |
| Primax Electronics                     | 1         | 0.79%   |
| Pixart Imaging                         | 1         | 0.79%   |
| Microsoft                              | 1         | 0.79%   |
| GEMBIRD                                | 1         | 0.79%   |
| Cubeternet                             | 1         | 0.79%   |
| Aveo Technology                        | 1         | 0.79%   |
| Arkmicro Technologies                  | 1         | 0.79%   |
| ALi                                    | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 6         | 4.72%   |
| Acer Lenovo EasyCamera                                                   | 6         | 4.72%   |
| Chicony Integrated Camera                                                | 4         | 3.15%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 3.15%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 2.36%   |
| Microdia Integrated Webcam                                               | 3         | 2.36%   |
| Chicony Web Camera - HD                                                  | 3         | 2.36%   |
| Chicony HD WebCam                                                        | 3         | 2.36%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 1.57%   |
| Suyin HP Truevision HD                                                   | 2         | 1.57%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 1.57%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 1.57%   |
| Samsung Galaxy A5 (MTP)                                                  | 2         | 1.57%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 2         | 1.57%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.57%   |
| Chicony TOSHIBA Web Camera - HD                                          | 2         | 1.57%   |
| Chicony Acer CrystalEye Webcam                                           | 2         | 1.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 1.57%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.57%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 2         | 1.57%   |
| Apple Built-in iSight                                                    | 2         | 1.57%   |
| Syntek USB2.0 Camera                                                     | 1         | 0.79%   |
| Syntek EasyCamera                                                        | 1         | 0.79%   |
| Suyin WebCam                                                             | 1         | 0.79%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.79%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 0.79%   |
| Sunplus Laptop Integrated Webcam HD                                      | 1         | 0.79%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.79%   |
| Sunplus Dell HD Webcam                                                   | 1         | 0.79%   |
| Silicon Motion WebCam SC-13HDL11431N                                     | 1         | 0.79%   |
| Silicon Motion WebCam SC-10HDD12636N                                     | 1         | 0.79%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 0.79%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 0.79%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 1         | 0.79%   |
| Realtek USB Camera                                                       | 1         | 0.79%   |
| Realtek Lenovo EasyCamera                                                | 1         | 0.79%   |
| Realtek Integrated Webcam_HD                                             | 1         | 0.79%   |
| Realtek Integrated Webcam HD                                             | 1         | 0.79%   |
| Realtek Integrated Webcam                                                | 1         | 0.79%   |
| Realtek HP Webcam                                                        | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 11        | 73.33%  |
| AuthenTec             | 2         | 13.33%  |
| Synaptics             | 1         | 6.67%   |
| Elan Microelectronics | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 33.33%  |
| Validity Sensors VFS491                                    | 2         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 13.33%  |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                            | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Elan ELAN:Fingerprint                                      | 1         | 6.67%   |
| AuthenTec AES2810                                          | 1         | 6.67%   |
| AuthenTec AES1600                                          | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 9         | 90%     |
| OmniKey  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 155       | 71.76%  |
| 1     | 53        | 24.54%  |
| 2     | 7         | 3.24%   |
| 3     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 17        | 23.94%  |
| Fingerprint reader       | 15        | 21.13%  |
| Net/wireless             | 11        | 15.49%  |
| Chipcard                 | 10        | 14.08%  |
| Multimedia controller    | 5         | 7.04%   |
| Bluetooth                | 4         | 5.63%   |
| Storage                  | 3         | 4.23%   |
| Net/ethernet             | 2         | 2.82%   |
| Communication controller | 2         | 2.82%   |
| Card reader              | 1         | 1.41%   |
| Camera                   | 1         | 1.41%   |

