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

Total: 309

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 46        | 20.54%  |
| Ubuntu 18.04        | 19        | 8.48%   |
| OpenMandriva 4.2    | 14        | 6.25%   |
| OpenMandriva 4.3    | 13        | 5.8%    |
| Ubuntu 22.04        | 9         | 4.02%   |
| Linux Mint 20.1     | 7         | 3.13%   |
| KDE neon 20.04      | 6         | 2.68%   |
| Pop!_OS 20.04       | 5         | 2.23%   |
| Arch                | 5         | 2.23%   |
| Ubuntu 21.04        | 4         | 1.79%   |
| Ubuntu 19.10        | 4         | 1.79%   |
| ArcoLinux Rolling   | 4         | 1.79%   |
| Xubuntu 20.04       | 3         | 1.34%   |
| Ubuntu 20.10        | 3         | 1.34%   |
| ROSA R11            | 3         | 1.34%   |
| ROSA R10            | 3         | 1.34%   |
| Manjaro             | 3         | 1.34%   |
| Linux Mint 20.2     | 3         | 1.34%   |
| Fedora 35           | 3         | 1.34%   |
| BlackPanther 18.1   | 3         | 1.34%   |
| Zorin 16            | 2         | 0.89%   |
| Ubuntu 21.10        | 2         | 0.89%   |
| Ubuntu 19.04        | 2         | 0.89%   |
| ROSA R8.1           | 2         | 0.89%   |
| Parrot 5.0          | 2         | 0.89%   |
| Manjaro 20.1        | 2         | 0.89%   |
| Kubuntu 20.04       | 2         | 0.89%   |
| Kali 2021.2         | 2         | 0.89%   |
| Kali 2021.1         | 2         | 0.89%   |
| Fedora 36           | 2         | 0.89%   |
| Fedora 33           | 2         | 0.89%   |
| Debian 11           | 2         | 0.89%   |
| Debian 10           | 2         | 0.89%   |
| Xubuntu 22.04       | 1         | 0.45%   |
| Xubuntu 18.04       | 1         | 0.45%   |
| UbuntuDDE 20.04     | 1         | 0.45%   |
| Ubuntu Unity 16.04  | 1         | 0.45%   |
| Ubuntu Budgie 22.04 | 1         | 0.45%   |
| Ubuntu 22.10        | 1         | 0.45%   |
| Ubuntu 16.04        | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 87        | 39.73%  |
| OpenMandriva  | 29        | 13.24%  |
| Linux Mint    | 16        | 7.31%   |
| Fedora        | 9         | 4.11%   |
| ROSA          | 8         | 3.65%   |
| Pop!_OS       | 8         | 3.65%   |
| Manjaro       | 7         | 3.2%    |
| KDE neon      | 7         | 3.2%    |
| Xubuntu       | 5         | 2.28%   |
| Kali          | 5         | 2.28%   |
| Debian        | 5         | 2.28%   |
| Arch          | 5         | 2.28%   |
| ArcoLinux     | 4         | 1.83%   |
| Parrot        | 3         | 1.37%   |
| Kubuntu       | 3         | 1.37%   |
| BlackPanther  | 3         | 1.37%   |
| Zorin         | 2         | 0.91%   |
| Peppermint    | 2         | 0.91%   |
| UbuntuDDE     | 1         | 0.46%   |
| Ubuntu Unity  | 1         | 0.46%   |
| Ubuntu Budgie | 1         | 0.46%   |
| Skygate       | 1         | 0.46%   |
| Pear OS       | 1         | 0.46%   |
| MX            | 1         | 0.46%   |
| EndeavourOS   | 1         | 0.46%   |
| Clear Linux   | 1         | 0.46%   |
| CentOS        | 1         | 0.46%   |
| Artix         | 1         | 0.46%   |
| ArchLabs      | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 14        | 5.98%   |
| 5.16.7-desktop-1omv4003         | 13        | 5.56%   |
| 5.4.0-42-generic                | 5         | 2.14%   |
| 5.8.0-50-generic                | 4         | 1.71%   |
| 5.4.0-72-generic                | 4         | 1.71%   |
| 5.4.0-54-generic                | 4         | 1.71%   |
| 5.4.0-29-generic                | 4         | 1.71%   |
| 5.15.0-47-generic               | 4         | 1.71%   |
| 5.0.0-37-generic                | 4         | 1.71%   |
| 5.4.0-65-generic                | 3         | 1.28%   |
| 5.4.0-56-generic                | 3         | 1.28%   |
| 5.4.0-52-generic                | 3         | 1.28%   |
| 5.3.0-46-generic                | 3         | 1.28%   |
| 5.13.0-30-generic               | 3         | 1.28%   |
| 5.11.0-38-generic               | 3         | 1.28%   |
| 5.11.0-27-generic               | 3         | 1.28%   |
| 5.8.0-44-generic                | 2         | 0.85%   |
| 5.4.0-88-generic                | 2         | 0.85%   |
| 5.4.0-81-generic                | 2         | 0.85%   |
| 5.4.0-80-generic                | 2         | 0.85%   |
| 5.4.0-7625-generic              | 2         | 0.85%   |
| 5.4.0-48-generic                | 2         | 0.85%   |
| 5.4.0-33-generic                | 2         | 0.85%   |
| 5.3.0-40-generic                | 2         | 0.85%   |
| 5.15.0-48-generic               | 2         | 0.85%   |
| 5.11.0-40-generic               | 2         | 0.85%   |
| 5.11.0-36-generic               | 2         | 0.85%   |
| 5.11.0-34-generic               | 2         | 0.85%   |
| 5.11.0-25-generic               | 2         | 0.85%   |
| 5.0.0-29-generic                | 2         | 0.85%   |
| 5.0.0-23-generic                | 2         | 0.85%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.85%   |
| 4.18.16-desktop-1bP             | 2         | 0.85%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 2         | 0.85%   |
| 4.15.0-42-generic               | 2         | 0.85%   |
| 5.9.11-3-MANJARO                | 1         | 0.43%   |
| 5.8.18-300.fc33.x86_64          | 1         | 0.43%   |
| 5.8.0-7630-generic              | 1         | 0.43%   |
| 5.8.0-63-generic                | 1         | 0.43%   |
| 5.8.0-59-generic                | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 47        | 21.17%  |
| 5.11.0  | 16        | 7.21%   |
| 5.8.0   | 14        | 6.31%   |
| 5.10.14 | 14        | 6.31%   |
| 5.16.7  | 13        | 5.86%   |
| 4.15.0  | 13        | 5.86%   |
| 5.15.0  | 12        | 5.41%   |
| 5.3.0   | 10        | 4.5%    |
| 5.0.0   | 10        | 4.5%    |
| 5.13.0  | 7         | 3.15%   |
| 5.10.0  | 6         | 2.7%    |
| 4.18.16 | 3         | 1.35%   |
| 5.15.7  | 2         | 0.9%    |
| 5.14.0  | 2         | 0.9%    |
| 4.9.60  | 2         | 0.9%    |
| 4.4.0   | 2         | 0.9%    |
| 4.19.0  | 2         | 0.9%    |
| 5.9.11  | 1         | 0.45%   |
| 5.8.18  | 1         | 0.45%   |
| 5.7.17  | 1         | 0.45%   |
| 5.7.0   | 1         | 0.45%   |
| 5.6.14  | 1         | 0.45%   |
| 5.6.0   | 1         | 0.45%   |
| 5.4.72  | 1         | 0.45%   |
| 5.4.60  | 1         | 0.45%   |
| 5.4.15  | 1         | 0.45%   |
| 5.19.3  | 1         | 0.45%   |
| 5.19.14 | 1         | 0.45%   |
| 5.19.12 | 1         | 0.45%   |
| 5.19.11 | 1         | 0.45%   |
| 5.19.10 | 1         | 0.45%   |
| 5.19.0  | 1         | 0.45%   |
| 5.18.12 | 1         | 0.45%   |
| 5.17.4  | 1         | 0.45%   |
| 5.17.0  | 1         | 0.45%   |
| 5.16.11 | 1         | 0.45%   |
| 5.16.0  | 1         | 0.45%   |
| 5.15.8  | 1         | 0.45%   |
| 5.15.74 | 1         | 0.45%   |
| 5.15.5  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 50        | 22.52%  |
| 5.10    | 25        | 11.26%  |
| 5.15    | 21        | 9.46%   |
| 5.11    | 18        | 8.11%   |
| 5.8     | 15        | 6.76%   |
| 5.16    | 15        | 6.76%   |
| 4.15    | 13        | 5.86%   |
| 5.3     | 10        | 4.5%    |
| 5.0     | 10        | 4.5%    |
| 5.13    | 8         | 3.6%    |
| 5.19    | 6         | 2.7%    |
| 5.14    | 4         | 1.8%    |
| 4.9     | 4         | 1.8%    |
| 4.19    | 4         | 1.8%    |
| 4.18    | 4         | 1.8%    |
| 5.12    | 3         | 1.35%   |
| 5.7     | 2         | 0.9%    |
| 5.6     | 2         | 0.9%    |
| 5.17    | 2         | 0.9%    |
| 4.4     | 2         | 0.9%    |
| 5.9     | 1         | 0.45%   |
| 5.18    | 1         | 0.45%   |
| 4.1     | 1         | 0.45%   |
| 3.10    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 193       | 96.98%  |
| i686   | 5         | 2.51%   |
| armv7l | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 92        | 43.4%   |
| KDE5            | 46        | 21.7%   |
| Unknown         | 24        | 11.32%  |
| XFCE            | 13        | 6.13%   |
| X-Cinnamon      | 8         | 3.77%   |
| MATE            | 5         | 2.36%   |
| KDE4            | 5         | 2.36%   |
| KDE             | 5         | 2.36%   |
| Cinnamon        | 3         | 1.42%   |
| LXQt            | 2         | 0.94%   |
| i3              | 2         | 0.94%   |
| Unity           | 1         | 0.47%   |
| Peppermint      | 1         | 0.47%   |
| LXDE            | 1         | 0.47%   |
| GNOME Flashback | 1         | 0.47%   |
| fvwm            | 1         | 0.47%   |
| Deepin          | 1         | 0.47%   |
| Budgie          | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 170       | 83.74%  |
| Wayland | 21        | 10.34%  |
| Unknown | 11        | 5.42%   |
| Tty     | 1         | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 51.67%  |
| SDDM    | 39        | 18.66%  |
| LightDM | 18        | 8.61%   |
| GDM     | 17        | 8.13%   |
| GDM3    | 14        | 6.7%    |
| TDM     | 7         | 3.35%   |
| KDM     | 5         | 2.39%   |
| SLiM    | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 85        | 41.26%  |
| fr_FR       | 70        | 33.98%  |
| Unknown     | 26        | 12.62%  |
| en_GB       | 8         | 3.88%   |
| C           | 6         | 2.91%   |
| ar_DZ       | 4         | 1.94%   |
| fr_DZ       | 2         | 0.97%   |
| fr_BE       | 2         | 0.97%   |
| ar_EG       | 2         | 0.97%   |
| en-US-UTF-8 | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 143       | 70.44%  |
| EFI  | 60        | 29.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 151       | 73.3%   |
| Overlay | 30        | 14.56%  |
| Btrfs   | 11        | 5.34%   |
| Unknown | 9         | 4.37%   |
| Ext2    | 3         | 1.46%   |
| Xfs     | 1         | 0.49%   |
| Ext3    | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 122       | 60.4%   |
| MBR     | 41        | 20.3%   |
| GPT     | 39        | 19.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 80.49%  |
| Yes       | 40        | 19.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 53.69%  |
| Yes       | 94        | 46.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 35        | 17.59%  |
| Hewlett-Packard     | 28        | 14.07%  |
| Lenovo              | 23        | 11.56%  |
| ASUSTek Computer    | 15        | 7.54%   |
| Gigabyte Technology | 14        | 7.04%   |
| MSI                 | 13        | 6.53%   |
| Acer                | 11        | 5.53%   |
| Toshiba             | 8         | 4.02%   |
| ECS                 | 8         | 4.02%   |
| Unknown             | 7         | 3.52%   |
| Sony                | 6         | 3.02%   |
| Foxconn             | 5         | 2.51%   |
| Samsung Electronics | 3         | 1.51%   |
| Packard Bell        | 3         | 1.51%   |
| Intel               | 3         | 1.51%   |
| Biostar             | 3         | 1.51%   |
| Apple               | 3         | 1.51%   |
| Fujitsu             | 2         | 1.01%   |
| ASRock              | 2         | 1.01%   |
| Wistron             | 1         | 0.5%    |
| WeiBu               | 1         | 0.5%    |
| sunxi               | 1         | 0.5%    |
| Pegatron            | 1         | 0.5%    |
| Microsoft           | 1         | 0.5%    |
| LDLC                | 1         | 0.5%    |
| eMachines           | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 7         | 3.52%   |
| Intel H55                     | 3         | 1.51%   |
| ECS G41T-M7                   | 3         | 1.51%   |
| Dell Inspiron 3542            | 3         | 1.51%   |
| Toshiba Satellite C55-B       | 2         | 1.01%   |
| MSI MS-7758                   | 2         | 1.01%   |
| MSI MS-7636                   | 2         | 1.01%   |
| Lenovo IdeaPad 300-15ISK 80Q7 | 2         | 1.01%   |
| Lenovo G560 20042             | 2         | 1.01%   |
| Lenovo G50-30 80G0            | 2         | 1.01%   |
| Lenovo B50-70 20384           | 2         | 1.01%   |
| HP ProBook 4540s              | 2         | 1.01%   |
| HP Pavilion 15                | 2         | 1.01%   |
| HP 280 G1 MT                  | 2         | 1.01%   |
| HP 15                         | 2         | 1.01%   |
| Gigabyte B85M-DS3H-A          | 2         | 1.01%   |
| ECS H61H2-MV                  | 2         | 1.01%   |
| Dell Latitude E7440           | 2         | 1.01%   |
| Dell Latitude E5430 vPro      | 2         | 1.01%   |
| Dell Latitude 7480            | 2         | 1.01%   |
| Dell Inspiron N5110           | 2         | 1.01%   |
| Dell Inspiron 15-3567         | 2         | 1.01%   |
| Biostar P4M89-M7B             | 2         | 1.01%   |
| Acer Aspire 5738              | 2         | 1.01%   |
| Wistron ProLiant ML110 G5     | 1         | 0.5%    |
| WeiBu SIMM INT G-41D3 G1.0L   | 1         | 0.5%    |
| Toshiba Satellite C850-A979   | 1         | 0.5%    |
| Toshiba Satellite C50-A560    | 1         | 0.5%    |
| Toshiba Satellite C50-A545    | 1         | 0.5%    |
| Toshiba Satellite C50-A539    | 1         | 0.5%    |
| Toshiba PORTEGE R30-A         | 1         | 0.5%    |
| Toshiba PORTEGE M780          | 1         | 0.5%    |
| sunxi LeMaker Banana Pi       | 1         | 0.5%    |
| Sony VPCEJ2S1E                | 1         | 0.5%    |
| Sony VPCEH2H1E                | 1         | 0.5%    |
| Sony VGN-AW21M_H              | 1         | 0.5%    |
| Sony SVF1531GSFB              | 1         | 0.5%    |
| Sony SVE1713A6EW              | 1         | 0.5%    |
| Sony SVE1513K1EW              | 1         | 0.5%    |
| Samsung N102SP/N100SP/N101SP  | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 13        | 6.53%   |
| Dell Latitude         | 11        | 5.53%   |
| HP ProBook            | 9         | 4.52%   |
| Acer Aspire           | 9         | 4.52%   |
| Unknown               | 7         | 3.52%   |
| Toshiba Satellite     | 6         | 3.02%   |
| Lenovo ThinkPad       | 5         | 2.51%   |
| Lenovo IdeaPad        | 5         | 2.51%   |
| HP Pavilion           | 4         | 2.01%   |
| HP EliteBook          | 4         | 2.01%   |
| Intel H55             | 3         | 1.51%   |
| ECS G41T-M7           | 3         | 1.51%   |
| Dell Precision        | 3         | 1.51%   |
| Dell OptiPlex         | 3         | 1.51%   |
| Toshiba PORTEGE       | 2         | 1.01%   |
| Packard Bell EasyNote | 2         | 1.01%   |
| MSI MS-7758           | 2         | 1.01%   |
| MSI MS-7636           | 2         | 1.01%   |
| Lenovo G580           | 2         | 1.01%   |
| Lenovo G560           | 2         | 1.01%   |
| Lenovo G50-30         | 2         | 1.01%   |
| Lenovo B50-70         | 2         | 1.01%   |
| HP 280                | 2         | 1.01%   |
| HP 15                 | 2         | 1.01%   |
| Gigabyte B85M-DS3H-A  | 2         | 1.01%   |
| Fujitsu LIFEBOOK      | 2         | 1.01%   |
| ECS H61H2-MV          | 2         | 1.01%   |
| Dell Vostro           | 2         | 1.01%   |
| Biostar P4M89-M7B     | 2         | 1.01%   |
| Acer Extensa          | 2         | 1.01%   |
| Wistron ProLiant      | 1         | 0.5%    |
| WeiBu SIMM            | 1         | 0.5%    |
| sunxi LeMaker         | 1         | 0.5%    |
| Sony VPCEJ2S1E        | 1         | 0.5%    |
| Sony VPCEH2H1E        | 1         | 0.5%    |
| Sony VGN-AW21M        | 1         | 0.5%    |
| Sony SVF1531GSFB      | 1         | 0.5%    |
| Sony SVE1713A6EW      | 1         | 0.5%    |
| Sony SVE1513K1EW      | 1         | 0.5%    |
| Samsung N102SP        | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 37        | 18.59%  |
| 2013    | 26        | 13.07%  |
| 2014    | 24        | 12.06%  |
| 2011    | 18        | 9.05%   |
| 2015    | 17        | 8.54%   |
| 2016    | 14        | 7.04%   |
| 2010    | 14        | 7.04%   |
| 2018    | 11        | 5.53%   |
| 2017    | 11        | 5.53%   |
| 2009    | 10        | 5.03%   |
| 2019    | 4         | 2.01%   |
| 2008    | 4         | 2.01%   |
| 2007    | 4         | 2.01%   |
| 2021    | 2         | 1.01%   |
| 2020    | 1         | 0.5%    |
| 2006    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 122       | 61.31%  |
| Desktop        | 72        | 36.18%  |
| Tablet         | 2         | 1.01%   |
| System on chip | 1         | 0.5%    |
| Convertible    | 1         | 0.5%    |
| All in one     | 1         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 196       | 98.49%  |
| Enabled  | 3         | 1.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 199       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 75        | 37.13%  |
| 4.01-8.0    | 49        | 24.26%  |
| 8.01-16.0   | 35        | 17.33%  |
| 1.01-2.0    | 17        | 8.42%   |
| 16.01-24.0  | 10        | 4.95%   |
| 2.01-3.0    | 6         | 2.97%   |
| 32.01-64.0  | 5         | 2.48%   |
| 0.51-1.0    | 4         | 1.98%   |
| 64.01-256.0 | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 106       | 48.85%  |
| 2.01-3.0  | 57        | 26.27%  |
| 3.01-4.0  | 20        | 9.22%   |
| 0.51-1.0  | 16        | 7.37%   |
| 4.01-8.0  | 11        | 5.07%   |
| 8.01-16.0 | 4         | 1.84%   |
| 0.01-0.5  | 3         | 1.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 135       | 66.5%   |
| 2      | 51        | 25.12%  |
| 3      | 12        | 5.91%   |
| 4      | 3         | 1.48%   |
| 0      | 2         | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 62.19%  |
| No        | 76        | 37.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 92.96%  |
| No        | 14        | 7.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 78.11%  |
| No        | 44        | 21.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 52.45%  |
| Yes       | 97        | 47.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 199       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Algiers            | 32        | 14.48%  |
| Oran               | 10        | 4.52%   |
| Belcourt           | 10        | 4.52%   |
| Tlemcen            | 9         | 4.07%   |
| Annaba             | 9         | 4.07%   |
| Sétif             | 6         | 2.71%   |
| Skikda             | 5         | 2.26%   |
| Blida              | 5         | 2.26%   |
| Biskra             | 5         | 2.26%   |
| Tipasa             | 4         | 1.81%   |
| Relizane           | 4         | 1.81%   |
| Mostaganem         | 4         | 1.81%   |
| Constantine        | 4         | 1.81%   |
| Cheraga            | 4         | 1.81%   |
| Birkhadem          | 4         | 1.81%   |
| Batna City         | 4         | 1.81%   |
| Tizi Ouzou         | 3         | 1.36%   |
| Sidi Akkacha       | 3         | 1.36%   |
| Laghouat           | 3         | 1.36%   |
| Jijelli            | 3         | 1.36%   |
| Ben ’Aknoûn     | 3         | 1.36%   |
| Béjaïa           | 3         | 1.36%   |
| Bab Ezzouar        | 3         | 1.36%   |
| ash-Shalif         | 3         | 1.36%   |
| Saida              | 2         | 0.9%    |
| Ouenza             | 2         | 0.9%    |
| Ouargla            | 2         | 0.9%    |
| Kouba              | 2         | 0.9%    |
| Khenchela          | 2         | 0.9%    |
| El Aouinet         | 2         | 0.9%    |
| Draria             | 2         | 0.9%    |
| Djelfa             | 2         | 0.9%    |
| Bordj el Kiffan    | 2         | 0.9%    |
| Bordj Bou Arreridj | 2         | 0.9%    |
| Bir el Djir        | 2         | 0.9%    |
| Ain Fakroun        | 2         | 0.9%    |
| Ain Defla          | 2         | 0.9%    |
| Tolga              | 1         | 0.45%   |
| Tichi              | 1         | 0.45%   |
| Tazoult-Lambese    | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 51        | 75     | 19.92%  |
| Seagate                   | 44        | 56     | 17.19%  |
| Toshiba                   | 30        | 32     | 11.72%  |
| Hitachi                   | 23        | 32     | 8.98%   |
| Samsung Electronics       | 22        | 24     | 8.59%   |
| HGST                      | 14        | 18     | 5.47%   |
| A-DATA Technology         | 12        | 13     | 4.69%   |
| SanDisk                   | 6         | 6      | 2.34%   |
| Lexar                     | 6         | 8      | 2.34%   |
| Unknown                   | 5         | 6      | 1.95%   |
| SK hynix                  | 4         | 4      | 1.56%   |
| Maxtor                    | 4         | 5      | 1.56%   |
| LITEON                    | 4         | 7      | 1.56%   |
| Realtek Semiconductor     | 3         | 3      | 1.17%   |
| XPG                       | 2         | 2      | 0.78%   |
| Silicon Motion            | 2         | 2      | 0.78%   |
| Kingston                  | 2         | 2      | 0.78%   |
| Intel                     | 2         | 2      | 0.78%   |
| ZTE                       | 1         | 1      | 0.39%   |
| WD MediaMax               | 1         | 1      | 0.39%   |
| TwinMOS                   | 1         | 1      | 0.39%   |
| Team                      | 1         | 1      | 0.39%   |
| T-FORCE                   | 1         | 1      | 0.39%   |
| PNY                       | 1         | 1      | 0.39%   |
| Micron/Crucial Technology | 1         | 1      | 0.39%   |
| Micron Technology         | 1         | 2      | 0.39%   |
| MDT                       | 1         | 1      | 0.39%   |
| Magnetic Data             | 1         | 1      | 0.39%   |
| Londisk                   | 1         | 1      | 0.39%   |
| KingSpec                  | 1         | 1      | 0.39%   |
| KESU                      | 1         | 1      | 0.39%   |
| HUAWEI                    | 1         | 1      | 0.39%   |
| HS-SSD-C100               | 1         | 1      | 0.39%   |
| Hewlett-Packard           | 1         | 1      | 0.39%   |
| Fujitsu                   | 1         | 2      | 0.39%   |
| Crucial                   | 1         | 1      | 0.39%   |
| China                     | 1         | 1      | 0.39%   |
| Apple                     | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 9         | 3.32%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 4         | 1.48%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 1.48%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 1.48%   |
| HGST HTS545050A7E680 500GB             | 4         | 1.48%   |
| WDC WD10EZEX-08WN4A0 1TB               | 3         | 1.11%   |
| WDC WD10EZEX-00WN4A0 1TB               | 3         | 1.11%   |
| Toshiba DT01ACA100 1TB                 | 3         | 1.11%   |
| Toshiba DT01ACA050 500GB               | 3         | 1.11%   |
| Seagate ST9500325AS 500GB              | 3         | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 1.11%   |
| Seagate Expansion 1TB                  | 3         | 1.11%   |
| Lexar 512GB SSD                        | 3         | 1.11%   |
| Hitachi HTS545050A7E380 500GB          | 3         | 1.11%   |
| HGST HTS545050A7E380 500GB             | 3         | 1.11%   |
| A-DATA SU630 240GB SSD                 | 3         | 1.11%   |
| XPG SX950U 240GB                       | 2         | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.74%   |
| WDC WD5000AVVS-63M8B0 500GB            | 2         | 0.74%   |
| Unknown MMC Card  64GB                 | 2         | 0.74%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.74%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.74%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.74%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.74%   |
| Seagate ST3500312CS 500GB              | 2         | 0.74%   |
| Seagate ST320LT020-9YG142 320GB        | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.74%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.74%   |
| Lexar 128GB SSD                        | 2         | 0.74%   |
| Hitachi HTS545050B9A300 500GB          | 2         | 0.74%   |
| Hitachi HDS721616PLA380 164GB          | 2         | 0.74%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.74%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.74%   |
| ZTE MMC Storage 942MB                  | 1         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.37%   |
| WDC WDS100T2B0B-00YS70 1TB SSD         | 1         | 0.37%   |
| WDC WD800JD-55MUA1 80GB                | 1         | 0.37%   |
| WDC WD7500BPKX-75HPJT0 752GB           | 1         | 0.37%   |
| WDC WD7500AYYS-01RCA0 752GB            | 1         | 0.37%   |
| WDC WD5000LUCT-62RC2Y0 500GB           | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 49        | 69     | 27.53%  |
| Seagate             | 44        | 56     | 24.72%  |
| Toshiba             | 30        | 32     | 16.85%  |
| Hitachi             | 23        | 32     | 12.92%  |
| HGST                | 14        | 18     | 7.87%   |
| Samsung Electronics | 10        | 11     | 5.62%   |
| Maxtor              | 4         | 5      | 2.25%   |
| WD MediaMax         | 1         | 1      | 0.56%   |
| Magnetic Data       | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 2      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 9         | 10     | 18%     |
| SanDisk             | 5         | 5      | 10%     |
| Samsung Electronics | 5         | 5      | 10%     |
| Lexar               | 5         | 7      | 10%     |
| WDC                 | 4         | 6      | 8%      |
| LITEON              | 4         | 7      | 8%      |
| SK hynix            | 3         | 3      | 6%      |
| XPG                 | 2         | 2      | 4%      |
| Intel               | 2         | 2      | 4%      |
| TwinMOS             | 1         | 1      | 2%      |
| Team                | 1         | 1      | 2%      |
| T-FORCE             | 1         | 1      | 2%      |
| PNY                 | 1         | 1      | 2%      |
| Londisk             | 1         | 1      | 2%      |
| Kingston            | 1         | 1      | 2%      |
| KingSpec            | 1         | 1      | 2%      |
| HS-SSD-C100         | 1         | 1      | 2%      |
| Crucial             | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 161       | 228    | 69.4%   |
| SSD     | 45        | 58     | 19.4%   |
| NVMe    | 15        | 20     | 6.47%   |
| MMC     | 6         | 8      | 2.59%   |
| Unknown | 5         | 5      | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 184       | 283    | 86.38%  |
| NVMe | 15        | 20     | 7.04%   |
| SAS  | 8         | 8      | 3.76%   |
| MMC  | 6         | 8      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 151       | 217    | 71.56%  |
| 0.51-1.0   | 54        | 63     | 25.59%  |
| 1.01-2.0   | 6         | 6      | 2.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 56        | 26.54%  |
| 101-250    | 37        | 17.54%  |
| 51-100     | 34        | 16.11%  |
| 1-20       | 26        | 12.32%  |
| 501-1000   | 25        | 11.85%  |
| 21-50      | 16        | 7.58%   |
| 1001-2000  | 13        | 6.16%   |
| Unknown    | 3         | 1.42%   |
| 2001-3000  | 1         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 108       | 49.54%  |
| 21-50     | 37        | 16.97%  |
| 101-250   | 27        | 12.39%  |
| 51-100    | 18        | 8.26%   |
| 251-500   | 14        | 6.42%   |
| 501-1000  | 8         | 3.67%   |
| 1001-2000 | 3         | 1.38%   |
| Unknown   | 3         | 1.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB             | 2         | 2      | 5.41%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 2.7%    |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 2.7%    |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 2.7%    |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 2.7%    |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 2.7%    |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 2.7%    |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 2.7%    |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 2.7%    |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 2.7%    |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 2.7%    |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.7%    |
| Seagate ST9500325AS 500GB                   | 1         | 1      | 2.7%    |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 2.7%    |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB             | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 2.7%    |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 2.7%    |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 2.7%    |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 2.7%    |
| Samsung Electronics HD502HI 500GB           | 1         | 1      | 2.7%    |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 2.7%    |
| Samsung Electronics HD160JJ 160GB           | 1         | 1      | 2.7%    |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 2.7%    |
| Maxtor 6L300S0 304GB                        | 1         | 1      | 2.7%    |
| Maxtor 32049H2 20GB                         | 1         | 1      | 2.7%    |
| Magnetic Data MD07500-ALDW-RO 752GB         | 1         | 1      | 2.7%    |
| Hitachi HTS723225L9A360 250GB               | 1         | 1      | 2.7%    |
| Hitachi HTS722010K9SA00 100GB               | 1         | 1      | 2.7%    |
| Hitachi HTS547564A9E384 640GB               | 1         | 1      | 2.7%    |
| Hitachi HTS542516K9SA00 160GB               | 1         | 1      | 2.7%    |
| Hitachi HDS721032CLA362 320GB               | 1         | 1      | 2.7%    |
| HGST HTS725050A7E630 500GB                  | 1         | 3      | 2.7%    |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 25%     |
| WDC                 | 8         | 9      | 22.22%  |
| Samsung Electronics | 6         | 6      | 16.67%  |
| Hitachi             | 5         | 5      | 13.89%  |
| Toshiba             | 2         | 2      | 5.56%   |
| Maxtor              | 2         | 2      | 5.56%   |
| HGST                | 2         | 4      | 5.56%   |
| WD MediaMax         | 1         | 1      | 2.78%   |
| Magnetic Data       | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 25.71%  |
| WDC                 | 8         | 9      | 22.86%  |
| Samsung Electronics | 5         | 5      | 14.29%  |
| Hitachi             | 5         | 5      | 14.29%  |
| Toshiba             | 2         | 2      | 5.71%   |
| Maxtor              | 2         | 2      | 5.71%   |
| HGST                | 2         | 4      | 5.71%   |
| WD MediaMax         | 1         | 1      | 2.86%   |
| Magnetic Data       | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 38     | 97.14%  |
| SSD  | 1         | 1      | 2.86%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 129       | 212    | 60.28%  |
| Works    | 50        | 68     | 23.36%  |
| Malfunc  | 35        | 39     | 16.36%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 172       | 80.37%  |
| AMD                         | 12        | 5.61%   |
| Samsung Electronics         | 7         | 3.27%   |
| Realtek Semiconductor       | 5         | 2.34%   |
| Nvidia                      | 4         | 1.87%   |
| VIA Technologies            | 3         | 1.4%    |
| Silicon Motion              | 3         | 1.4%    |
| JMicron Technology          | 2         | 0.93%   |
| ASMedia Technology          | 2         | 0.93%   |
| Micron/Crucial Technology   | 1         | 0.47%   |
| Micron Technology           | 1         | 0.47%   |
| Marvell Technology Group    | 1         | 0.47%   |
| Kingston Technology Company | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 25        | 9.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 18        | 6.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 5.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 5.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 5.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 4.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10        | 3.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 3.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 3.47%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 3.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 2.32%   |
| Realtek Realtek Non-Volatile memory controller                                          | 5         | 1.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.54%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 1.16%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.16%   |
| VIA Serial ATA Controller                                                               | 2         | 0.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.77%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.77%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.77%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.77%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 2         | 0.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 0.77%   |
| VIA VT8237/8251 Serial ATA Controller                                                   | 1         | 0.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.39%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.39%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.39%   |
| Nvidia MCP89 SATA Controller                                                            | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 135       | 63.68%  |
| IDE  | 48        | 22.64%  |
| NVMe | 15        | 7.08%   |
| RAID | 14        | 6.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 184       | 92.46%  |
| AMD    | 14        | 7.04%   |
| ARM    | 1         | 0.5%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-3217U CPU @ 1.80GHz           | 6         | 3.02%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 3.02%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5         | 2.51%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 4         | 2.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 2.01%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 2.01%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 1.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.51%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3         | 1.51%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 1.51%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 1.51%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.51%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 1.51%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 1.51%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 2         | 1.01%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.01%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.01%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2         | 1.01%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.01%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.01%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 2         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.01%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.01%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.01%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.01%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 1.01%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.01%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.01%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.01%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.01%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i3           | 57        | 28.64%  |
| Intel Core i5           | 44        | 22.11%  |
| Intel Core i7           | 24        | 12.06%  |
| Intel Pentium           | 15        | 7.54%   |
| Intel Pentium Dual-Core | 13        | 6.53%   |
| Intel Core 2 Duo        | 9         | 4.52%   |
| Intel Celeron           | 7         | 3.52%   |
| Intel Atom              | 5         | 2.51%   |
| Intel Xeon              | 3         | 1.51%   |
| Intel Pentium Dual      | 3         | 1.51%   |
| AMD Ryzen 7             | 3         | 1.51%   |
| Other                   | 1         | 0.5%    |
| Intel Pentium D         | 1         | 0.5%    |
| Intel Pentium 4         | 1         | 0.5%    |
| Intel Core 2 Quad       | 1         | 0.5%    |
| ARM Allwinner           | 1         | 0.5%    |
| AMD Ryzen 9             | 1         | 0.5%    |
| AMD Ryzen 5 PRO         | 1         | 0.5%    |
| AMD Ryzen 5             | 1         | 0.5%    |
| AMD Ryzen 3             | 1         | 0.5%    |
| AMD FX                  | 1         | 0.5%    |
| AMD E2                  | 1         | 0.5%    |
| AMD E1                  | 1         | 0.5%    |
| AMD Athlon Neo X2       | 1         | 0.5%    |
| AMD Athlon II Dual-Core | 1         | 0.5%    |
| AMD Athlon 64           | 1         | 0.5%    |
| AMD A4                  | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 154       | 77.39%  |
| 4      | 30        | 15.08%  |
| 6      | 5         | 2.51%   |
| 1      | 5         | 2.51%   |
| 8      | 3         | 1.51%   |
| 16     | 1         | 0.5%    |
| 3      | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 199       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 131       | 65.83%  |
| 1      | 67        | 33.67%  |
| 4      | 1         | 0.5%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 98%     |
| Unknown        | 4         | 2%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 19.42%  |
| 0x306a9    | 30        | 14.56%  |
| 0x206a7    | 18        | 8.74%   |
| 0x1067a    | 17        | 8.25%   |
| 0x20655    | 15        | 7.28%   |
| 0x40651    | 10        | 4.85%   |
| 0x406e3    | 9         | 4.37%   |
| 0x306d4    | 8         | 3.88%   |
| 0x306c3    | 7         | 3.4%    |
| 0x30678    | 7         | 3.4%    |
| 0x806e9    | 6         | 2.91%   |
| 0x806ea    | 4         | 1.94%   |
| 0x906e9    | 3         | 1.46%   |
| 0x6fd      | 3         | 1.46%   |
| 0x20652    | 3         | 1.46%   |
| 0x6fb      | 2         | 0.97%   |
| 0x306e4    | 2         | 0.97%   |
| 0x30661    | 2         | 0.97%   |
| 0x0800820d | 2         | 0.97%   |
| 0xf65      | 1         | 0.49%   |
| 0x906eb    | 1         | 0.49%   |
| 0x806ec    | 1         | 0.49%   |
| 0x806c1    | 1         | 0.49%   |
| 0x506e3    | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x406c4    | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x10676    | 1         | 0.49%   |
| 0x0a201016 | 1         | 0.49%   |
| 0x08701021 | 1         | 0.49%   |
| 0x08608103 | 1         | 0.49%   |
| 0x08600106 | 1         | 0.49%   |
| 0x0810100b | 1         | 0.49%   |
| 0x0700010f | 1         | 0.49%   |
| 0x06006705 | 1         | 0.49%   |
| 0x0600063d | 1         | 0.49%   |
| 0x05000119 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 40        | 20.1%   |
| SandyBridge   | 23        | 11.56%  |
| Haswell       | 22        | 11.06%  |
| Penryn        | 21        | 10.55%  |
| Westmere      | 18        | 9.05%   |
| KabyLake      | 17        | 8.54%   |
| Skylake       | 12        | 6.03%   |
| Silvermont    | 10        | 5.03%   |
| Broadwell     | 8         | 4.02%   |
| Core          | 6         | 3.02%   |
| Zen+          | 2         | 1.01%   |
| Zen 2         | 2         | 1.01%   |
| NetBurst      | 2         | 1.01%   |
| K8 Hammer     | 2         | 1.01%   |
| Bonnell       | 2         | 1.01%   |
| Unknown       | 2         | 1.01%   |
| Zen 3         | 1         | 0.5%    |
| Zen           | 1         | 0.5%    |
| TigerLake     | 1         | 0.5%    |
| K10           | 1         | 0.5%    |
| Jaguar        | 1         | 0.5%    |
| Goldmont plus | 1         | 0.5%    |
| Goldmont      | 1         | 0.5%    |
| Excavator     | 1         | 0.5%    |
| Bulldozer     | 1         | 0.5%    |
| Bobcat        | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 145       | 61.44%  |
| Nvidia                     | 45        | 19.07%  |
| AMD                        | 43        | 18.22%  |
| VIA Technologies           | 2         | 0.85%   |
| Matrox Electronics Systems | 1         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 9.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 5.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 4.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 4.24%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 4.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 3.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.39%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8         | 3.39%   |
| Intel HD Graphics 620                                                                    | 7         | 2.97%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.54%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 2.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.12%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.69%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.27%   |
| Intel HD Graphics 630                                                                    | 3         | 1.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.27%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.85%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.85%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.85%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.85%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.85%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.85%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.42%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.42%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.42%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.42%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.42%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.42%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 110       | 54.73%  |
| 1 x Nvidia     | 26        | 12.94%  |
| 1 x AMD        | 26        | 12.94%  |
| Intel + Nvidia | 18        | 8.96%   |
| Intel + AMD    | 16        | 7.96%   |
| 1 x VIA        | 2         | 1%      |
| Other          | 1         | 0.5%    |
| 1 x Matrox     | 1         | 0.5%    |
| AMD + Nvidia   | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 174       | 85.29%  |
| Proprietary | 21        | 10.29%  |
| Unknown     | 9         | 4.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 60.29%  |
| 1.01-2.0   | 44        | 21.57%  |
| 0.51-1.0   | 14        | 6.86%   |
| 0.01-0.5   | 14        | 6.86%   |
| 3.01-4.0   | 7         | 3.43%   |
| 7.01-8.0   | 2         | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 38        | 19.9%   |
| LG Display              | 28        | 14.66%  |
| AU Optronics            | 24        | 12.57%  |
| Chimei Innolux          | 14        | 7.33%   |
| BOE                     | 14        | 7.33%   |
| Hewlett-Packard         | 12        | 6.28%   |
| AOC                     | 10        | 5.24%   |
| Chi Mei Optoelectronics | 8         | 4.19%   |
| KTC                     | 5         | 2.62%   |
| Acer                    | 4         | 2.09%   |
| Dell                    | 3         | 1.57%   |
| BenQ                    | 3         | 1.57%   |
| Apple                   | 3         | 1.57%   |
| Ancor Communications    | 3         | 1.57%   |
| Unknown                 | 3         | 1.57%   |
| Unknown (XXX)           | 2         | 1.05%   |
| Lenovo                  | 2         | 1.05%   |
| Goldstar                | 2         | 1.05%   |
| ___                     | 1         | 0.52%   |
| Unknown                 | 1         | 0.52%   |
| TSN                     | 1         | 0.52%   |
| SKY                     | 1         | 0.52%   |
| Sharp                   | 1         | 0.52%   |
| PTW                     | 1         | 0.52%   |
| PiLot                   | 1         | 0.52%   |
| PANDA                   | 1         | 0.52%   |
| MStar                   | 1         | 0.52%   |
| LGD                     | 1         | 0.52%   |
| InnoLux Display         | 1         | 0.52%   |
| EMP                     | 1         | 0.52%   |
| AGO                     | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 1.55%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 1.55%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.55%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 3         | 1.55%   |
| Unknown                                                                  | 3         | 1.55%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 1.03%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 1.03%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD045C 1366x768 344x194mm 15.5-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 1.03%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 1.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.03%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 1.03%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 1.03%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 1.03%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.52%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.52%   |
| TSN 24 Monitor TSN2400 1360x768 510x287mm 23.0-inch                      | 1         | 0.52%   |
| SKY TV-monitor SKY0104 1920x1080 885x498mm 40.0-inch                     | 1         | 0.52%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM04D5 1920x540                          | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM00A6 1280x1024 380x310mm 19.3-inch     | 1         | 0.52%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch        | 1         | 0.52%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch       | 1         | 0.52%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch       | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 93        | 50.54%  |
| 1920x1080 (FHD)    | 49        | 26.63%  |
| 1600x900 (HD+)     | 9         | 4.89%   |
| 1440x900 (WXGA+)   | 8         | 4.35%   |
| 2560x1440 (QHD)    | 3         | 1.63%   |
| 1680x1050 (WSXGA+) | 3         | 1.63%   |
| 1360x768           | 3         | 1.63%   |
| 1280x800 (WXGA)    | 3         | 1.63%   |
| 1280x1024 (SXGA)   | 3         | 1.63%   |
| 3840x2160 (4K)     | 2         | 1.09%   |
| 1920x1200 (WUXGA)  | 2         | 1.09%   |
| 2160x1440          | 1         | 0.54%   |
| 1920x540           | 1         | 0.54%   |
| 1680x945           | 1         | 0.54%   |
| 1600x1200          | 1         | 0.54%   |
| 1280x720 (HD)      | 1         | 0.54%   |
| 1024x600           | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 80        | 41.67%  |
| 18      | 15        | 7.81%   |
| 13      | 14        | 7.29%   |
| 21      | 13        | 6.77%   |
| 17      | 8         | 4.17%   |
| 23      | 7         | 3.65%   |
| 19      | 7         | 3.65%   |
| 14      | 7         | 3.65%   |
| 12      | 7         | 3.65%   |
| Unknown | 7         | 3.65%   |
| 24      | 5         | 2.6%    |
| 27      | 4         | 2.08%   |
| 52      | 3         | 1.56%   |
| 20      | 3         | 1.56%   |
| 22      | 2         | 1.04%   |
| 11      | 2         | 1.04%   |
| 10      | 2         | 1.04%   |
| 46      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 37      | 1         | 0.52%   |
| 32      | 1         | 0.52%   |
| 31      | 1         | 0.52%   |
| 16      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 50.53%  |
| 401-500     | 36        | 18.95%  |
| 501-600     | 16        | 8.42%   |
| 201-300     | 16        | 8.42%   |
| 351-400     | 11        | 5.79%   |
| Unknown     | 7         | 3.68%   |
| 1001-1500   | 4         | 2.11%   |
| 801-900     | 2         | 1.05%   |
| 701-800     | 1         | 0.53%   |
| 601-700     | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 153       | 84.07%  |
| 16/10   | 15        | 8.24%   |
| Unknown | 6         | 3.3%    |
| 5/4     | 3         | 1.65%   |
| 4/3     | 2         | 1.1%    |
| 6/5     | 1         | 0.55%   |
| 32/9    | 1         | 0.55%   |
| 3/2     | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 79        | 41.36%  |
| 201-250        | 19        | 9.95%   |
| 81-90          | 17        | 8.9%    |
| 151-200        | 17        | 8.9%    |
| 141-150        | 16        | 8.38%   |
| Unknown        | 7         | 3.66%   |
| 61-70          | 6         | 3.14%   |
| 71-80          | 5         | 2.62%   |
| 301-350        | 4         | 2.09%   |
| 121-130        | 4         | 2.09%   |
| More than 1000 | 3         | 1.57%   |
| 501-1000       | 3         | 1.57%   |
| 51-60          | 2         | 1.05%   |
| 351-500        | 2         | 1.05%   |
| 41-50          | 2         | 1.05%   |
| 131-140        | 2         | 1.05%   |
| 111-120        | 2         | 1.05%   |
| 251-300        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 89        | 47.09%  |
| 51-100  | 55        | 29.1%   |
| 121-160 | 28        | 14.81%  |
| Unknown | 7         | 3.7%    |
| 1-50    | 5         | 2.65%   |
| 161-240 | 5         | 2.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 179       | 88.61%  |
| 2     | 13        | 6.44%   |
| 0     | 9         | 4.46%   |
| 3     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 123       | 38.32%  |
| Qualcomm Atheros                | 53        | 16.51%  |
| Intel                           | 50        | 15.58%  |
| Broadcom                        | 30        | 9.35%   |
| Ralink Technology               | 19        | 5.92%   |
| Ralink                          | 10        | 3.12%   |
| Qualcomm Atheros Communications | 4         | 1.25%   |
| Broadcom Limited                | 4         | 1.25%   |
| VIA Technologies                | 3         | 0.93%   |
| Samsung Electronics             | 3         | 0.93%   |
| Nvidia                          | 3         | 0.93%   |
| MediaTek                        | 3         | 0.93%   |
| D-Link System                   | 3         | 0.93%   |
| Xiaomi                          | 2         | 0.62%   |
| Marvell Technology Group        | 2         | 0.62%   |
| Huawei Technologies             | 2         | 0.62%   |
| D-Link                          | 2         | 0.62%   |
| TP-Link                         | 1         | 0.31%   |
| Sierra Wireless                 | 1         | 0.31%   |
| LG Electronics                  | 1         | 0.31%   |
| Hewlett-Packard                 | 1         | 0.31%   |
| AMD                             | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 19.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 12.74%  |
| Broadcom BCM43142 802.11b/g/n                                     | 13        | 3.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.17%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.36%   |
| Ralink RT5370 Wireless Adapter                                    | 5         | 1.36%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5         | 1.36%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 1.08%   |
| Intel Wireless 8260                                               | 4         | 1.08%   |
| Intel Wireless 7265                                               | 4         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 1.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.81%   |
| Intel Wireless 7260                                               | 3         | 0.81%   |
| Intel Wireless 3160                                               | 3         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.54%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2         | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.54%   |
| MediaTek N152DL                                                   | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 44        | 25.58%  |
| Intel                           | 43        | 25%     |
| Broadcom                        | 22        | 12.79%  |
| Ralink Technology               | 19        | 11.05%  |
| Realtek Semiconductor           | 18        | 10.47%  |
| Ralink                          | 10        | 5.81%   |
| Qualcomm Atheros Communications | 4         | 2.33%   |
| D-Link System                   | 3         | 1.74%   |
| D-Link                          | 2         | 1.16%   |
| Broadcom Limited                | 2         | 1.16%   |
| TP-Link                         | 1         | 0.58%   |
| Sierra Wireless                 | 1         | 0.58%   |
| MediaTek                        | 1         | 0.58%   |
| Marvell Technology Group        | 1         | 0.58%   |
| Hewlett-Packard                 | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 13        | 7.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 11        | 6.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 5.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 8         | 4.65%   |
| Ralink MT7601U Wireless Adapter                                      | 7         | 4.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 4.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 2.91%   |
| Ralink RT5370 Wireless Adapter                                       | 5         | 2.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 2.91%   |
| Intel Wireless 8265 / 8275                                           | 5         | 2.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 2.33%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 2.33%   |
| Intel Wireless 8260                                                  | 4         | 2.33%   |
| Intel Wireless 7265                                                  | 4         | 2.33%   |
| Intel Wireless 7260                                                  | 3         | 1.74%   |
| Intel Wireless 3160                                                  | 3         | 1.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 1.74%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 1.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 1.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 1.16%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.16%   |
| Intel WiFi Link 5100                                                 | 2         | 1.16%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.16%   |
| Intel Centrino Wireless-N 135                                        | 2         | 1.16%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.16%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2         | 1.16%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 1.16%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.58%   |
| Sierra Wireless EM7305                                               | 1         | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.58%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.58%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.58%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 119       | 61.03%  |
| Intel                    | 32        | 16.41%  |
| Qualcomm Atheros         | 14        | 7.18%   |
| Broadcom                 | 11        | 5.64%   |
| VIA Technologies         | 3         | 1.54%   |
| Samsung Electronics      | 3         | 1.54%   |
| Nvidia                   | 3         | 1.54%   |
| Xiaomi                   | 2         | 1.03%   |
| MediaTek                 | 2         | 1.03%   |
| Broadcom Limited         | 2         | 1.03%   |
| Marvell Technology Group | 1         | 0.51%   |
| LG Electronics           | 1         | 0.51%   |
| Huawei Technologies      | 1         | 0.51%   |
| AMD                      | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 36.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 23.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 2.04%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 1.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.53%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.53%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.02%   |
| MediaTek N152DL                                                   | 2         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.02%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.51%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.51%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.51%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.51%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.51%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.51%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.51%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.51%   |
| Huawei E353/E3131                                                 | 1         | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 185       | 53.94%  |
| WiFi     | 157       | 45.77%  |
| Modem    | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 66.5%   |
| Ethernet | 66        | 33.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 126       | 62.07%  |
| 1     | 73        | 35.96%  |
| 0     | 4         | 1.97%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 199       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 27.84%  |
| Qualcomm Atheros Communications | 13        | 13.4%   |
| Broadcom                        | 11        | 11.34%  |
| Realtek Semiconductor           | 7         | 7.22%   |
| Lite-On Technology              | 5         | 5.15%   |
| Foxconn / Hon Hai               | 5         | 5.15%   |
| Ralink                          | 4         | 4.12%   |
| IMC Networks                    | 4         | 4.12%   |
| Dell                            | 4         | 4.12%   |
| Cambridge Silicon Radio         | 4         | 4.12%   |
| Foxconn International           | 3         | 3.09%   |
| Apple                           | 3         | 3.09%   |
| Toshiba                         | 1         | 1.03%   |
| Ralink Technology               | 1         | 1.03%   |
| Marvell Semiconductor           | 1         | 1.03%   |
| Integrated System Solution      | 1         | 1.03%   |
| Hewlett-Packard                 | 1         | 1.03%   |
| Chicony Electronics             | 1         | 1.03%   |
| Alps Electric                   | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 20        | 20.62%  |
| Qualcomm Atheros  Bluetooth Device                    | 5         | 5.15%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 5.15%   |
| Ralink RT3290 Bluetooth                               | 4         | 4.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 4.12%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 4.12%   |
| Realtek Bluetooth Radio                               | 3         | 3.09%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3         | 3.09%   |
| IMC Networks Bluetooth Device                         | 3         | 3.09%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 3.09%   |
| Realtek RTL8723B Bluetooth                            | 2         | 2.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 2         | 2.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 2.06%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 2.06%   |
| Dell Wireless 365 Bluetooth                           | 2         | 2.06%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 2.06%   |
| Apple Bluetooth Host Controller                       | 2         | 2.06%   |
| Toshiba Bluetooth Device                              | 1         | 1.03%   |
| Realtek RTL8821A Bluetooth                            | 1         | 1.03%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.03%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 1.03%   |
| Qualcomm Atheros Bluetooth                            | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 1.03%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 1.03%   |
| Lite-On Wireless_Device                               | 1         | 1.03%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 1.03%   |
| Lite-On BCM43142A0                                    | 1         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 1.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1         | 1.03%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.03%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.03%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 1.03%   |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 1.03%   |
| Foxconn / Hon Hai Acer Module                         | 1         | 1.03%   |
| Dell DW375 Bluetooth Module                           | 1         | 1.03%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 1.03%   |
| Chicony Bluetooth (RTL8723BE)                         | 1         | 1.03%   |
| Broadcom HP Portable Bumble Bee                       | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 174       | 70.45%  |
| AMD                   | 35        | 14.17%  |
| Nvidia                | 28        | 11.34%  |
| VIA Technologies      | 3         | 1.21%   |
| JMTek                 | 2         | 0.81%   |
| Texas Instruments     | 1         | 0.4%    |
| Medeli Electronics    | 1         | 0.4%    |
| Logitech              | 1         | 0.4%    |
| Logic3 / SpectraVideo | 1         | 0.4%    |
| Guillemot             | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 34        | 11.97%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29        | 10.21%  |
| Intel Sunrise Point-LP HD Audio                                                   | 22        | 7.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 18        | 6.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 15        | 5.28%   |
| Intel Haswell-ULT HD Audio Controller                                             | 13        | 4.58%   |
| Intel 8 Series HD Audio Controller                                                | 13        | 4.58%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 10        | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9         | 3.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 8         | 2.82%   |
| Intel Broadwell-U Audio Controller                                                | 8         | 2.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6         | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 6         | 2.11%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5         | 1.76%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 1.41%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 3         | 1.06%   |
| Nvidia High Definition Audio Controller                                           | 3         | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 1.06%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 1.06%   |
| Nvidia MCP79 High Definition Audio                                                | 2         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.7%    |
| JMTek USB PnP Audio Device                                                        | 2         | 0.7%    |
| Intel CM238 HD Audio Controller                                                   | 2         | 0.7%    |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 0.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 0.7%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 0.7%    |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 0.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2         | 0.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.7%    |
| AMD FCH Azalia Controller                                                         | 2         | 0.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.7%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.7%    |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 2         | 0.7%    |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.35%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.35%   |
| Nvidia MCP89 High Definition Audio                                                | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 29        | 23.02%  |
| Samsung Electronics | 27        | 21.43%  |
| SK hynix            | 23        | 18.25%  |
| Micron Technology   | 16        | 12.7%   |
| A-DATA Technology   | 9         | 7.14%   |
| Kingston            | 8         | 6.35%   |
| Nanya Technology    | 3         | 2.38%   |
| TwinMOS             | 2         | 1.59%   |
| Thermaltake         | 1         | 0.79%   |
| Team                | 1         | 0.79%   |
| Ramaxel Technology  | 1         | 0.79%   |
| Patriot             | 1         | 0.79%   |
| GeIL                | 1         | 0.79%   |
| Elpida              | 1         | 0.79%   |
| Dynet               | 1         | 0.79%   |
| Crucial             | 1         | 0.79%   |
| ASint Technology    | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 4         | 2.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 4         | 2.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 4         | 2.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 3         | 2.16%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 2         | 1.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3                    | 2         | 1.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 2         | 1.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2         | 1.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s             | 2         | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s | 2         | 1.44%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s    | 2         | 1.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 1.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 2         | 1.44%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s              | 1         | 0.72%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR2                       | 1         | 0.72%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1         | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR2                    | 1         | 0.72%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1333MT/s            | 1         | 0.72%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 1         | 0.72%   |
| Unknown RAM Module 4096MB DIMM DDR3 800MT/s              | 1         | 0.72%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1         | 0.72%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1         | 0.72%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s             | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s            | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 1         | 0.72%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1         | 0.72%   |
| Unknown RAM Module 1GB DIMM 800MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 1GB DIMM 533MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s              | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 200MT/s              | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 1         | 0.72%   |
| TwinMOS RAM 9DPCBNZB-TATP 4GB DIMM DDR3 1333MT/s         | 1         | 0.72%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s         | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 59        | 57.28%  |
| DDR4    | 22        | 21.36%  |
| DDR2    | 8         | 7.77%   |
| SDRAM   | 7         | 6.8%    |
| Unknown | 5         | 4.85%   |
| LPDDR4  | 1         | 0.97%   |
| DDR     | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 61        | 61%     |
| DIMM   | 39        | 39%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 53        | 46.09%  |
| 2048  | 28        | 24.35%  |
| 8192  | 21        | 18.26%  |
| 1024  | 6         | 5.22%   |
| 16384 | 4         | 3.48%   |
| 32768 | 2         | 1.74%   |
| 512   | 1         | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 37        | 32.74%  |
| 1333    | 16        | 14.16%  |
| 2667    | 10        | 8.85%   |
| 800     | 7         | 6.19%   |
| Unknown | 6         | 5.31%   |
| 2400    | 5         | 4.42%   |
| 1334    | 5         | 4.42%   |
| 667     | 4         | 3.54%   |
| 3200    | 3         | 2.65%   |
| 4199    | 2         | 1.77%   |
| 3266    | 2         | 1.77%   |
| 2133    | 2         | 1.77%   |
| 1067    | 2         | 1.77%   |
| 3800    | 1         | 0.88%   |
| 3400    | 1         | 0.88%   |
| 3066    | 1         | 0.88%   |
| 3000    | 1         | 0.88%   |
| 2666    | 1         | 0.88%   |
| 2200    | 1         | 0.88%   |
| 1648    | 1         | 0.88%   |
| 1639    | 1         | 0.88%   |
| 533     | 1         | 0.88%   |
| 333     | 1         | 0.88%   |
| 266     | 1         | 0.88%   |
| 200     | 1         | 0.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 9         | 64.29%  |
| Seiko Epson        | 3         | 21.43%  |
| Hewlett-Packard    | 1         | 7.14%   |
| Brother Industries | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26        | 22.41%  |
| Microdia                               | 19        | 16.38%  |
| Cheng Uei Precision Industry (Foxlink) | 11        | 9.48%   |
| Acer                                   | 10        | 8.62%   |
| Realtek Semiconductor                  | 9         | 7.76%   |
| Sunplus Innovation Technology          | 7         | 6.03%   |
| Suyin                                  | 5         | 4.31%   |
| Syntek                                 | 4         | 3.45%   |
| IMC Networks                           | 4         | 3.45%   |
| Silicon Motion                         | 3         | 2.59%   |
| Apple                                  | 3         | 2.59%   |
| Samsung Electronics                    | 2         | 1.72%   |
| Quanta                                 | 2         | 1.72%   |
| Lite-On Technology                     | 2         | 1.72%   |
| Alcor Micro                            | 2         | 1.72%   |
| Primax Electronics                     | 1         | 0.86%   |
| Pixart Imaging                         | 1         | 0.86%   |
| Microsoft                              | 1         | 0.86%   |
| GEMBIRD                                | 1         | 0.86%   |
| Aveo Technology                        | 1         | 0.86%   |
| Arkmicro Technologies                  | 1         | 0.86%   |
| ALi                                    | 1         | 0.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 6         | 5.13%   |
| Acer Lenovo EasyCamera                                                   | 6         | 5.13%   |
| Chicony TOSHIBA Web Camera - HD                                          | 4         | 3.42%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 3.42%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 2.56%   |
| Microdia Integrated Webcam                                               | 3         | 2.56%   |
| Chicony Integrated Camera                                                | 3         | 2.56%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 1.71%   |
| Suyin HP Truevision HD                                                   | 2         | 1.71%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 1.71%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 1.71%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 2         | 1.71%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 2         | 1.71%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.71%   |
| Chicony HD WebCam                                                        | 2         | 1.71%   |
| Chicony Acer CrystalEye Webcam                                           | 2         | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.71%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 2         | 1.71%   |
| Syntek USB2.0 Camera                                                     | 1         | 0.85%   |
| Syntek EasyCamera                                                        | 1         | 0.85%   |
| Suyin WebCam                                                             | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 0.85%   |
| Sunplus Laptop Integrated Webcam HD                                      | 1         | 0.85%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.85%   |
| Sunplus Dell HD Webcam                                                   | 1         | 0.85%   |
| Silicon Motion WebCam SC-13HDL11431N                                     | 1         | 0.85%   |
| Silicon Motion WebCam SC-10HDD12636N                                     | 1         | 0.85%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 0.85%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 1         | 0.85%   |
| Realtek USB Camera                                                       | 1         | 0.85%   |
| Realtek Lenovo EasyCamera                                                | 1         | 0.85%   |
| Realtek Integrated Webcam_HD                                             | 1         | 0.85%   |
| Realtek Integrated Webcam                                                | 1         | 0.85%   |
| Realtek HP Webcam                                                        | 1         | 0.85%   |
| Realtek HP Truevision HD                                                 | 1         | 0.85%   |
| Realtek HD Webcam - Realtek                                              | 1         | 0.85%   |
| Realtek Acer 640 x 480 laptop camera                                     | 1         | 0.85%   |
| Quanta HD Webcam                                                         | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 11        | 73.33%  |
| AuthenTec             | 2         | 13.33%  |
| Synaptics             | 1         | 6.67%   |
| Elan Microelectronics | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 9         | 90%     |
| OmniKey  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 144       | 70.59%  |
| 1     | 53        | 25.98%  |
| 2     | 6         | 2.94%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 17        | 24.64%  |
| Fingerprint reader       | 15        | 21.74%  |
| Net/wireless             | 11        | 15.94%  |
| Chipcard                 | 10        | 14.49%  |
| Multimedia controller    | 4         | 5.8%    |
| Bluetooth                | 4         | 5.8%    |
| Storage                  | 2         | 2.9%    |
| Net/ethernet             | 2         | 2.9%    |
| Communication controller | 2         | 2.9%    |
| Card reader              | 1         | 1.45%   |
| Camera                   | 1         | 1.45%   |

