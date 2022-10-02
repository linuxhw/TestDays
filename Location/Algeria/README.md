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

Total: 289

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 46        | 22.01%  |
| Ubuntu 18.04        | 19        | 9.09%   |
| OpenMandriva 4.2    | 14        | 6.7%    |
| OpenMandriva 4.3    | 10        | 4.78%   |
| Linux Mint 20.1     | 7         | 3.35%   |
| Ubuntu 22.04        | 6         | 2.87%   |
| KDE neon 20.04      | 6         | 2.87%   |
| Pop!_OS 20.04       | 5         | 2.39%   |
| Arch                | 5         | 2.39%   |
| Ubuntu 21.04        | 4         | 1.91%   |
| Ubuntu 19.10        | 4         | 1.91%   |
| ArcoLinux Rolling   | 4         | 1.91%   |
| Xubuntu 20.04       | 3         | 1.44%   |
| Ubuntu 20.10        | 3         | 1.44%   |
| ROSA R10            | 3         | 1.44%   |
| Manjaro             | 3         | 1.44%   |
| Linux Mint 20.2     | 3         | 1.44%   |
| Fedora 35           | 3         | 1.44%   |
| BlackPanther 18.1   | 3         | 1.44%   |
| Zorin 16            | 2         | 0.96%   |
| Ubuntu 19.04        | 2         | 0.96%   |
| ROSA R8.1           | 2         | 0.96%   |
| ROSA R11            | 2         | 0.96%   |
| Parrot 5.0          | 2         | 0.96%   |
| Manjaro 20.1        | 2         | 0.96%   |
| Kubuntu 20.04       | 2         | 0.96%   |
| Kali 2021.2         | 2         | 0.96%   |
| Kali 2021.1         | 2         | 0.96%   |
| Fedora 33           | 2         | 0.96%   |
| Debian 11           | 2         | 0.96%   |
| Debian 10           | 2         | 0.96%   |
| Xubuntu 18.04       | 1         | 0.48%   |
| UbuntuDDE 20.04     | 1         | 0.48%   |
| Ubuntu Unity 16.04  | 1         | 0.48%   |
| Ubuntu Budgie 22.04 | 1         | 0.48%   |
| Ubuntu 21.10        | 1         | 0.48%   |
| Ubuntu 16.04        | 1         | 0.48%   |
| Skygate 1.6-16219   | 1         | 0.48%   |
| Pop!_OS 21.10       | 1         | 0.48%   |
| Pop!_OS 21.04       | 1         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 82        | 40.2%   |
| OpenMandriva  | 26        | 12.75%  |
| Linux Mint    | 14        | 6.86%   |
| Pop!_OS       | 8         | 3.92%   |
| Fedora        | 8         | 3.92%   |
| Manjaro       | 7         | 3.43%   |
| ROSA          | 6         | 2.94%   |
| KDE neon      | 6         | 2.94%   |
| Kali          | 5         | 2.45%   |
| Debian        | 5         | 2.45%   |
| Arch          | 5         | 2.45%   |
| Xubuntu       | 4         | 1.96%   |
| ArcoLinux     | 4         | 1.96%   |
| Parrot        | 3         | 1.47%   |
| Kubuntu       | 3         | 1.47%   |
| BlackPanther  | 3         | 1.47%   |
| Zorin         | 2         | 0.98%   |
| Peppermint    | 2         | 0.98%   |
| UbuntuDDE     | 1         | 0.49%   |
| Ubuntu Unity  | 1         | 0.49%   |
| Ubuntu Budgie | 1         | 0.49%   |
| Skygate       | 1         | 0.49%   |
| Pear OS       | 1         | 0.49%   |
| MX            | 1         | 0.49%   |
| EndeavourOS   | 1         | 0.49%   |
| Clear Linux   | 1         | 0.49%   |
| CentOS        | 1         | 0.49%   |
| Artix         | 1         | 0.49%   |
| ArchLabs      | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 14        | 6.39%   |
| 5.16.7-desktop-1omv4003         | 10        | 4.57%   |
| 5.4.0-42-generic                | 5         | 2.28%   |
| 5.8.0-50-generic                | 4         | 1.83%   |
| 5.4.0-72-generic                | 4         | 1.83%   |
| 5.4.0-54-generic                | 4         | 1.83%   |
| 5.4.0-29-generic                | 4         | 1.83%   |
| 5.0.0-37-generic                | 4         | 1.83%   |
| 5.4.0-65-generic                | 3         | 1.37%   |
| 5.4.0-56-generic                | 3         | 1.37%   |
| 5.4.0-52-generic                | 3         | 1.37%   |
| 5.3.0-46-generic                | 3         | 1.37%   |
| 5.15.0-47-generic               | 3         | 1.37%   |
| 5.13.0-30-generic               | 3         | 1.37%   |
| 5.11.0-38-generic               | 3         | 1.37%   |
| 5.11.0-27-generic               | 3         | 1.37%   |
| 5.8.0-44-generic                | 2         | 0.91%   |
| 5.4.0-88-generic                | 2         | 0.91%   |
| 5.4.0-81-generic                | 2         | 0.91%   |
| 5.4.0-80-generic                | 2         | 0.91%   |
| 5.4.0-7625-generic              | 2         | 0.91%   |
| 5.4.0-48-generic                | 2         | 0.91%   |
| 5.4.0-33-generic                | 2         | 0.91%   |
| 5.3.0-40-generic                | 2         | 0.91%   |
| 5.11.0-40-generic               | 2         | 0.91%   |
| 5.11.0-36-generic               | 2         | 0.91%   |
| 5.11.0-34-generic               | 2         | 0.91%   |
| 5.11.0-25-generic               | 2         | 0.91%   |
| 5.0.0-29-generic                | 2         | 0.91%   |
| 5.0.0-23-generic                | 2         | 0.91%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.91%   |
| 4.18.16-desktop-1bP             | 2         | 0.91%   |
| 4.15.0-42-generic               | 2         | 0.91%   |
| 5.9.11-3-MANJARO                | 1         | 0.46%   |
| 5.8.18-300.fc33.x86_64          | 1         | 0.46%   |
| 5.8.0-7630-generic              | 1         | 0.46%   |
| 5.8.0-63-generic                | 1         | 0.46%   |
| 5.8.0-59-generic                | 1         | 0.46%   |
| 5.8.0-48-generic                | 1         | 0.46%   |
| 5.8.0-45-generic                | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 21.74%  |
| 5.11.0  | 16        | 7.73%   |
| 5.8.0   | 14        | 6.76%   |
| 5.10.14 | 14        | 6.76%   |
| 4.15.0  | 12        | 5.8%    |
| 5.3.0   | 10        | 4.83%   |
| 5.16.7  | 10        | 4.83%   |
| 5.0.0   | 10        | 4.83%   |
| 5.15.0  | 8         | 3.86%   |
| 5.13.0  | 6         | 2.9%    |
| 5.10.0  | 6         | 2.9%    |
| 4.18.16 | 3         | 1.45%   |
| 5.15.7  | 2         | 0.97%   |
| 5.14.0  | 2         | 0.97%   |
| 4.9.60  | 2         | 0.97%   |
| 4.4.0   | 2         | 0.97%   |
| 4.19.0  | 2         | 0.97%   |
| 5.9.11  | 1         | 0.48%   |
| 5.8.18  | 1         | 0.48%   |
| 5.7.17  | 1         | 0.48%   |
| 5.7.0   | 1         | 0.48%   |
| 5.6.14  | 1         | 0.48%   |
| 5.6.0   | 1         | 0.48%   |
| 5.4.72  | 1         | 0.48%   |
| 5.4.60  | 1         | 0.48%   |
| 5.4.15  | 1         | 0.48%   |
| 5.19.3  | 1         | 0.48%   |
| 5.19.12 | 1         | 0.48%   |
| 5.19.11 | 1         | 0.48%   |
| 5.19.10 | 1         | 0.48%   |
| 5.18.12 | 1         | 0.48%   |
| 5.17.4  | 1         | 0.48%   |
| 5.17.0  | 1         | 0.48%   |
| 5.16.11 | 1         | 0.48%   |
| 5.16.0  | 1         | 0.48%   |
| 5.15.8  | 1         | 0.48%   |
| 5.15.5  | 1         | 0.48%   |
| 5.15.25 | 1         | 0.48%   |
| 5.15.15 | 1         | 0.48%   |
| 5.15.11 | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 48        | 23.19%  |
| 5.10    | 24        | 11.59%  |
| 5.11    | 18        | 8.7%    |
| 5.15    | 16        | 7.73%   |
| 5.8     | 15        | 7.25%   |
| 5.16    | 12        | 5.8%    |
| 4.15    | 12        | 5.8%    |
| 5.3     | 10        | 4.83%   |
| 5.0     | 10        | 4.83%   |
| 5.13    | 7         | 3.38%   |
| 5.19    | 4         | 1.93%   |
| 5.14    | 4         | 1.93%   |
| 4.9     | 4         | 1.93%   |
| 4.19    | 4         | 1.93%   |
| 4.18    | 4         | 1.93%   |
| 5.12    | 3         | 1.45%   |
| 5.7     | 2         | 0.97%   |
| 5.6     | 2         | 0.97%   |
| 5.17    | 2         | 0.97%   |
| 4.4     | 2         | 0.97%   |
| 5.9     | 1         | 0.48%   |
| 5.18    | 1         | 0.48%   |
| 4.1     | 1         | 0.48%   |
| 3.10    | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 182       | 97.85%  |
| i686   | 4         | 2.15%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 86        | 43.43%  |
| KDE5            | 42        | 21.21%  |
| Unknown         | 24        | 12.12%  |
| XFCE            | 12        | 6.06%   |
| X-Cinnamon      | 7         | 3.54%   |
| KDE             | 5         | 2.53%   |
| MATE            | 4         | 2.02%   |
| KDE4            | 4         | 2.02%   |
| Cinnamon        | 3         | 1.52%   |
| LXQt            | 2         | 1.01%   |
| i3              | 2         | 1.01%   |
| Unity           | 1         | 0.51%   |
| Peppermint      | 1         | 0.51%   |
| LXDE            | 1         | 0.51%   |
| GNOME Flashback | 1         | 0.51%   |
| fvwm            | 1         | 0.51%   |
| Deepin          | 1         | 0.51%   |
| Budgie          | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 163       | 85.79%  |
| Wayland | 15        | 7.89%   |
| Unknown | 11        | 5.79%   |
| Tty     | 1         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 53.85%  |
| SDDM    | 36        | 18.46%  |
| GDM     | 17        | 8.72%   |
| LightDM | 15        | 7.69%   |
| GDM3    | 10        | 5.13%   |
| TDM     | 7         | 3.59%   |
| KDM     | 4         | 2.05%   |
| SLiM    | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 77        | 39.9%   |
| fr_FR       | 67        | 34.72%  |
| Unknown     | 25        | 12.95%  |
| en_GB       | 8         | 4.15%   |
| C           | 6         | 3.11%   |
| ar_DZ       | 4         | 2.07%   |
| fr_DZ       | 2         | 1.04%   |
| ar_EG       | 2         | 1.04%   |
| fr_BE       | 1         | 0.52%   |
| en-US-UTF-8 | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 134       | 70.53%  |
| EFI  | 56        | 29.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 141       | 73.44%  |
| Overlay | 27        | 14.06%  |
| Btrfs   | 10        | 5.21%   |
| Unknown | 9         | 4.69%   |
| Ext2    | 3         | 1.56%   |
| Xfs     | 1         | 0.52%   |
| Ext3    | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 118       | 62.43%  |
| MBR     | 37        | 19.58%  |
| GPT     | 34        | 17.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 153       | 79.69%  |
| Yes       | 39        | 20.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 52.63%  |
| Yes       | 90        | 47.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 33        | 17.74%  |
| Hewlett-Packard     | 27        | 14.52%  |
| Lenovo              | 21        | 11.29%  |
| Gigabyte Technology | 14        | 7.53%   |
| ASUSTek Computer    | 14        | 7.53%   |
| MSI                 | 13        | 6.99%   |
| Acer                | 11        | 5.91%   |
| Toshiba             | 8         | 4.3%    |
| Sony                | 6         | 3.23%   |
| ECS                 | 6         | 3.23%   |
| Unknown             | 6         | 3.23%   |
| Foxconn             | 5         | 2.69%   |
| Packard Bell        | 3         | 1.61%   |
| Intel               | 3         | 1.61%   |
| Biostar             | 3         | 1.61%   |
| Samsung Electronics | 2         | 1.08%   |
| Fujitsu             | 2         | 1.08%   |
| ASRock              | 2         | 1.08%   |
| Apple               | 2         | 1.08%   |
| WeiBu               | 1         | 0.54%   |
| Pegatron            | 1         | 0.54%   |
| Microsoft           | 1         | 0.54%   |
| LDLC                | 1         | 0.54%   |
| eMachines           | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 6         | 3.23%   |
| Intel H55                           | 3         | 1.61%   |
| Toshiba Satellite C55-B             | 2         | 1.08%   |
| MSI MS-7758                         | 2         | 1.08%   |
| MSI MS-7636                         | 2         | 1.08%   |
| Lenovo IdeaPad 300-15ISK 80Q7       | 2         | 1.08%   |
| Lenovo G560 20042                   | 2         | 1.08%   |
| Lenovo G50-30 80G0                  | 2         | 1.08%   |
| Lenovo B50-70 20384                 | 2         | 1.08%   |
| HP ProBook 4540s                    | 2         | 1.08%   |
| HP Pavilion 15                      | 2         | 1.08%   |
| HP 280 G1 MT                        | 2         | 1.08%   |
| HP 15                               | 2         | 1.08%   |
| Gigabyte B85M-DS3H-A                | 2         | 1.08%   |
| ECS H61H2-MV                        | 2         | 1.08%   |
| Dell Latitude E7440                 | 2         | 1.08%   |
| Dell Latitude E5430 vPro            | 2         | 1.08%   |
| Dell Latitude 7480                  | 2         | 1.08%   |
| Dell Inspiron N5110                 | 2         | 1.08%   |
| Dell Inspiron 3542                  | 2         | 1.08%   |
| Dell Inspiron 15-3567               | 2         | 1.08%   |
| Biostar P4M89-M7B                   | 2         | 1.08%   |
| Acer Aspire 5738                    | 2         | 1.08%   |
| WeiBu SIMM INT G-41D3 G1.0L         | 1         | 0.54%   |
| Toshiba Satellite C850-A979         | 1         | 0.54%   |
| Toshiba Satellite C50-A560          | 1         | 0.54%   |
| Toshiba Satellite C50-A545          | 1         | 0.54%   |
| Toshiba Satellite C50-A539          | 1         | 0.54%   |
| Toshiba PORTEGE R30-A               | 1         | 0.54%   |
| Toshiba PORTEGE M780                | 1         | 0.54%   |
| Sony VPCEJ2S1E                      | 1         | 0.54%   |
| Sony VPCEH2H1E                      | 1         | 0.54%   |
| Sony VGN-AW21M_H                    | 1         | 0.54%   |
| Sony SVF1531GSFB                    | 1         | 0.54%   |
| Sony SVE1713A6EW                    | 1         | 0.54%   |
| Sony SVE1513K1EW                    | 1         | 0.54%   |
| Samsung N102SP/N100SP/N101SP        | 1         | 0.54%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B | 1         | 0.54%   |
| Pegatron 2A94h                      | 1         | 0.54%   |
| Packard Bell EasyNote TJ75          | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 12        | 6.45%   |
| Dell Latitude         | 11        | 5.91%   |
| HP ProBook            | 9         | 4.84%   |
| Acer Aspire           | 9         | 4.84%   |
| Toshiba Satellite     | 6         | 3.23%   |
| Unknown               | 6         | 3.23%   |
| Lenovo ThinkPad       | 5         | 2.69%   |
| Lenovo IdeaPad        | 5         | 2.69%   |
| HP Pavilion           | 4         | 2.15%   |
| Intel H55             | 3         | 1.61%   |
| HP EliteBook          | 3         | 1.61%   |
| Dell OptiPlex         | 3         | 1.61%   |
| Toshiba PORTEGE       | 2         | 1.08%   |
| Packard Bell EasyNote | 2         | 1.08%   |
| MSI MS-7758           | 2         | 1.08%   |
| MSI MS-7636           | 2         | 1.08%   |
| Lenovo G560           | 2         | 1.08%   |
| Lenovo G50-30         | 2         | 1.08%   |
| Lenovo B50-70         | 2         | 1.08%   |
| HP 280                | 2         | 1.08%   |
| HP 15                 | 2         | 1.08%   |
| Gigabyte B85M-DS3H-A  | 2         | 1.08%   |
| Fujitsu LIFEBOOK      | 2         | 1.08%   |
| ECS H61H2-MV          | 2         | 1.08%   |
| Dell Vostro           | 2         | 1.08%   |
| Dell Precision        | 2         | 1.08%   |
| Biostar P4M89-M7B     | 2         | 1.08%   |
| Acer Extensa          | 2         | 1.08%   |
| WeiBu SIMM            | 1         | 0.54%   |
| Sony VPCEJ2S1E        | 1         | 0.54%   |
| Sony VPCEH2H1E        | 1         | 0.54%   |
| Sony VGN-AW21M        | 1         | 0.54%   |
| Sony SVF1531GSFB      | 1         | 0.54%   |
| Sony SVE1713A6EW      | 1         | 0.54%   |
| Sony SVE1513K1EW      | 1         | 0.54%   |
| Samsung N102SP        | 1         | 0.54%   |
| Samsung 700Z3A        | 1         | 0.54%   |
| Pegatron 2A94h        | 1         | 0.54%   |
| Packard Bell DOT      | 1         | 0.54%   |
| MSI MS-7C52           | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 35        | 18.82%  |
| 2013 | 25        | 13.44%  |
| 2014 | 22        | 11.83%  |
| 2011 | 16        | 8.6%    |
| 2015 | 15        | 8.06%   |
| 2016 | 14        | 7.53%   |
| 2010 | 14        | 7.53%   |
| 2017 | 11        | 5.91%   |
| 2018 | 10        | 5.38%   |
| 2009 | 9         | 4.84%   |
| 2008 | 4         | 2.15%   |
| 2007 | 4         | 2.15%   |
| 2019 | 3         | 1.61%   |
| 2021 | 2         | 1.08%   |
| 2020 | 1         | 0.54%   |
| 2006 | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 114       | 61.29%  |
| Desktop     | 68        | 36.56%  |
| Tablet      | 2         | 1.08%   |
| Convertible | 1         | 0.54%   |
| All in one  | 1         | 0.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 183       | 98.39%  |
| Enabled  | 3         | 1.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 186       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 71        | 37.77%  |
| 4.01-8.0    | 44        | 23.4%   |
| 8.01-16.0   | 35        | 18.62%  |
| 1.01-2.0    | 16        | 8.51%   |
| 16.01-24.0  | 9         | 4.79%   |
| 2.01-3.0    | 6         | 3.19%   |
| 32.01-64.0  | 4         | 2.13%   |
| 0.51-1.0    | 2         | 1.06%   |
| 64.01-256.0 | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 101       | 49.75%  |
| 2.01-3.0  | 54        | 26.6%   |
| 3.01-4.0  | 17        | 8.37%   |
| 0.51-1.0  | 16        | 7.88%   |
| 4.01-8.0  | 11        | 5.42%   |
| 8.01-16.0 | 3         | 1.48%   |
| 0.01-0.5  | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 65.79%  |
| 2      | 49        | 25.79%  |
| 3      | 11        | 5.79%   |
| 4      | 3         | 1.58%   |
| 0      | 2         | 1.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 63.3%   |
| No        | 69        | 36.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 94.09%  |
| No        | 11        | 5.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 78.19%  |
| No        | 41        | 21.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 51.83%  |
| Yes       | 92        | 48.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 186       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Algiers         | 30        | 14.49%  |
| Oran            | 10        | 4.83%   |
| Belcourt        | 10        | 4.83%   |
| Tlemcen         | 9         | 4.35%   |
| Annaba          | 9         | 4.35%   |
| Sétif          | 6         | 2.9%    |
| Skikda          | 5         | 2.42%   |
| Blida           | 5         | 2.42%   |
| Biskra          | 5         | 2.42%   |
| Relizane        | 4         | 1.93%   |
| Mostaganem      | 4         | 1.93%   |
| Cheraga         | 4         | 1.93%   |
| Birkhadem       | 4         | 1.93%   |
| Batna City      | 4         | 1.93%   |
| Tipasa          | 3         | 1.45%   |
| Sidi Akkacha    | 3         | 1.45%   |
| Laghouat        | 3         | 1.45%   |
| Jijelli         | 3         | 1.45%   |
| Béjaïa        | 3         | 1.45%   |
| ash-Shalif      | 3         | 1.45%   |
| Tizi Ouzou      | 2         | 0.97%   |
| Saida           | 2         | 0.97%   |
| Ouenza          | 2         | 0.97%   |
| Kouba           | 2         | 0.97%   |
| Khenchela       | 2         | 0.97%   |
| El Aouinet      | 2         | 0.97%   |
| Draria          | 2         | 0.97%   |
| Djelfa          | 2         | 0.97%   |
| Constantine     | 2         | 0.97%   |
| Bordj el Kiffan | 2         | 0.97%   |
| Bir el Djir     | 2         | 0.97%   |
| Ben ’Aknoûn  | 2         | 0.97%   |
| Bab Ezzouar     | 2         | 0.97%   |
| Ain Fakroun     | 2         | 0.97%   |
| Ain Defla       | 2         | 0.97%   |
| Tolga           | 1         | 0.48%   |
| Tichi           | 1         | 0.48%   |
| Tazoult-Lambese | 1         | 0.48%   |
| Tamanghasset    | 1         | 0.48%   |
| Tadjenanet      | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 50        | 74     | 20.92%  |
| Seagate                   | 42        | 54     | 17.57%  |
| Toshiba                   | 29        | 31     | 12.13%  |
| Samsung Electronics       | 22        | 24     | 9.21%   |
| Hitachi                   | 20        | 29     | 8.37%   |
| HGST                      | 14        | 18     | 5.86%   |
| A-DATA Technology         | 10        | 11     | 4.18%   |
| SanDisk                   | 6         | 6      | 2.51%   |
| Lexar                     | 6         | 6      | 2.51%   |
| Unknown                   | 4         | 5      | 1.67%   |
| Maxtor                    | 4         | 5      | 1.67%   |
| LITEON                    | 4         | 7      | 1.67%   |
| SK hynix                  | 3         | 3      | 1.26%   |
| Realtek Semiconductor     | 3         | 3      | 1.26%   |
| XPG                       | 2         | 2      | 0.84%   |
| Kingston                  | 2         | 2      | 0.84%   |
| Intel                     | 2         | 2      | 0.84%   |
| ZTE                       | 1         | 1      | 0.42%   |
| WD MediaMax               | 1         | 1      | 0.42%   |
| TwinMOS                   | 1         | 1      | 0.42%   |
| Team                      | 1         | 1      | 0.42%   |
| T-FORCE                   | 1         | 1      | 0.42%   |
| Silicon Motion            | 1         | 1      | 0.42%   |
| PNY                       | 1         | 1      | 0.42%   |
| Micron/Crucial Technology | 1         | 1      | 0.42%   |
| Micron Technology         | 1         | 2      | 0.42%   |
| MDT                       | 1         | 1      | 0.42%   |
| KingSpec                  | 1         | 1      | 0.42%   |
| KESU                      | 1         | 1      | 0.42%   |
| HUAWEI                    | 1         | 1      | 0.42%   |
| Fujitsu                   | 1         | 2      | 0.42%   |
| Crucial                   | 1         | 1      | 0.42%   |
| China                     | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB           | 8         | 3.15%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 4         | 1.57%   |
| Toshiba MQ01ABD100 1TB             | 4         | 1.57%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 1.57%   |
| HGST HTS545050A7E680 500GB         | 4         | 1.57%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 1.18%   |
| WDC WD10EZEX-00WN4A0 1TB           | 3         | 1.18%   |
| Toshiba DT01ACA100 1TB             | 3         | 1.18%   |
| Toshiba DT01ACA050 500GB           | 3         | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 1.18%   |
| Seagate Expansion 1TB              | 3         | 1.18%   |
| Lexar 512GB SSD                    | 3         | 1.18%   |
| HGST HTS545050A7E380 500GB         | 3         | 1.18%   |
| XPG SX950U 960GB SSD               | 2         | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.79%   |
| WDC WD5000AVVS-63M8B0 500GB        | 2         | 0.79%   |
| Unknown MMC Card  64GB             | 2         | 0.79%   |
| Seagate ST9500325AS 500GB          | 2         | 0.79%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 0.79%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.79%   |
| Seagate ST3500312CS 500GB          | 2         | 0.79%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.79%   |
| Samsung NVMe SSD Drive 256GB       | 2         | 0.79%   |
| Lexar 128GB SSD                    | 2         | 0.79%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 0.79%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 0.79%   |
| Hitachi HDS721616PLA380 160GB      | 2         | 0.79%   |
| HGST HTS725050A7E630 500GB         | 2         | 0.79%   |
| HGST HTS541010A9E680 1TB           | 2         | 0.79%   |
| A-DATA SU630 240GB SSD             | 2         | 0.79%   |
| ZTE MMC Storage 942MB              | 1         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.39%   |
| WDC WDS100T2B0B-00YS70 1TB SSD     | 1         | 0.39%   |
| WDC WD800JD-55MUA1 80GB            | 1         | 0.39%   |
| WDC WD7500AYYS-01RCA0 752GB        | 1         | 0.39%   |
| WDC WD5000LUCT-62RC2Y0 500GB       | 1         | 0.39%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 48        | 68     | 28.4%   |
| Seagate             | 42        | 54     | 24.85%  |
| Toshiba             | 29        | 31     | 17.16%  |
| Hitachi             | 20        | 29     | 11.83%  |
| HGST                | 14        | 18     | 8.28%   |
| Samsung Electronics | 10        | 11     | 5.92%   |
| Maxtor              | 4         | 5      | 2.37%   |
| WD MediaMax         | 1         | 1      | 0.59%   |
| Fujitsu             | 1         | 2      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 7         | 8      | 15.91%  |
| SanDisk             | 5         | 5      | 11.36%  |
| Samsung Electronics | 5         | 5      | 11.36%  |
| Lexar               | 5         | 5      | 11.36%  |
| WDC                 | 4         | 6      | 9.09%   |
| LITEON              | 4         | 7      | 9.09%   |
| XPG                 | 2         | 2      | 4.55%   |
| SK hynix            | 2         | 2      | 4.55%   |
| Intel               | 2         | 2      | 4.55%   |
| TwinMOS             | 1         | 1      | 2.27%   |
| Team                | 1         | 1      | 2.27%   |
| T-FORCE             | 1         | 1      | 2.27%   |
| PNY                 | 1         | 1      | 2.27%   |
| Kingston            | 1         | 1      | 2.27%   |
| KingSpec            | 1         | 1      | 2.27%   |
| Crucial             | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 152       | 219    | 70.37%  |
| SSD     | 40        | 50     | 18.52%  |
| NVMe    | 14        | 19     | 6.48%   |
| MMC     | 5         | 7      | 2.31%   |
| Unknown | 5         | 5      | 2.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 172       | 267    | 86.87%  |
| NVMe | 14        | 19     | 7.07%   |
| SAS  | 7         | 7      | 3.54%   |
| MMC  | 5         | 7      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 139       | 200    | 70.2%   |
| 0.51-1.0   | 53        | 63     | 26.77%  |
| 1.01-2.0   | 6         | 6      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 53        | 26.77%  |
| 101-250    | 34        | 17.17%  |
| 51-100     | 31        | 15.66%  |
| 1-20       | 24        | 12.12%  |
| 501-1000   | 24        | 12.12%  |
| 21-50      | 16        | 8.08%   |
| 1001-2000  | 12        | 6.06%   |
| Unknown    | 3         | 1.52%   |
| 2001-3000  | 1         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 102       | 49.76%  |
| 21-50     | 35        | 17.07%  |
| 101-250   | 25        | 12.2%   |
| 51-100    | 17        | 8.29%   |
| 251-500   | 13        | 6.34%   |
| 501-1000  | 7         | 3.41%   |
| 1001-2000 | 3         | 1.46%   |
| Unknown   | 3         | 1.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 2.94%   |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 2.94%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 2.94%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 2.94%   |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 2.94%   |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 2.94%   |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 2.94%   |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 2.94%   |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 2.94%   |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 2.94%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.94%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 2.94%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 2.94%   |
| Seagate ST500LT012-9WS142 500GB             | 1         | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 2.94%   |
| Seagate ST500LM021-1KJ152 500GB             | 1         | 1      | 2.94%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 2.94%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 2.94%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 2.94%   |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 2.94%   |
| Samsung Electronics HD502HI 500GB           | 1         | 1      | 2.94%   |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 2.94%   |
| Samsung Electronics HD160JJ 160GB           | 1         | 1      | 2.94%   |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 2.94%   |
| Maxtor 6L300S0 304GB                        | 1         | 1      | 2.94%   |
| Maxtor 32049H2 20GB                         | 1         | 1      | 2.94%   |
| Hitachi HTS723225L9A360 250GB               | 1         | 1      | 2.94%   |
| Hitachi HTS722010K9SA00 100GB               | 1         | 1      | 2.94%   |
| Hitachi HTS547564A9E384 640GB               | 1         | 1      | 2.94%   |
| Hitachi HTS542516K9SA00 160GB               | 1         | 1      | 2.94%   |
| Hitachi HDS721032CLA362 320GB               | 1         | 1      | 2.94%   |
| HGST HTS725050A7E630 500GB                  | 1         | 3      | 2.94%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 24.24%  |
| Seagate             | 7         | 7      | 21.21%  |
| Samsung Electronics | 6         | 6      | 18.18%  |
| Hitachi             | 5         | 5      | 15.15%  |
| Toshiba             | 2         | 2      | 6.06%   |
| Maxtor              | 2         | 2      | 6.06%   |
| HGST                | 2         | 4      | 6.06%   |
| WD MediaMax         | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 25%     |
| Seagate             | 7         | 7      | 21.88%  |
| Samsung Electronics | 5         | 5      | 15.63%  |
| Hitachi             | 5         | 5      | 15.63%  |
| Toshiba             | 2         | 2      | 6.25%   |
| Maxtor              | 2         | 2      | 6.25%   |
| HGST                | 2         | 4      | 6.25%   |
| WD MediaMax         | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 35     | 96.88%  |
| SSD  | 1         | 1      | 3.13%   |

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
| Detected | 122       | 203    | 61.31%  |
| Works    | 45        | 61     | 22.61%  |
| Malfunc  | 32        | 36     | 16.08%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 161       | 80.1%   |
| AMD                         | 12        | 5.97%   |
| Samsung Electronics         | 6         | 2.99%   |
| Realtek Semiconductor       | 5         | 2.49%   |
| Nvidia                      | 4         | 1.99%   |
| VIA Technologies            | 3         | 1.49%   |
| Silicon Motion              | 2         | 1%      |
| JMicron Technology          | 2         | 1%      |
| ASMedia Technology          | 2         | 1%      |
| Micron/Crucial Technology   | 1         | 0.5%    |
| Micron Technology           | 1         | 0.5%    |
| Marvell Technology Group    | 1         | 0.5%    |
| Kingston Technology Company | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 9.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 18        | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 6.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 4.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 4.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 3.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 3.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 2.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 2.47%   |
| Realtek Realtek Non-Volatile memory controller                                          | 5         | 2.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.65%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.23%   |
| VIA Serial ATA Controller                                                               | 2         | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.82%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.82%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.82%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 2         | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 0.82%   |
| VIA VT8237/8251 Serial ATA Controller                                                   | 1         | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.41%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.41%   |
| Nvidia MCP89 SATA Controller                                                            | 1         | 0.41%   |
| Nvidia MCP79 SATA Controller                                                            | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 126       | 63.32%  |
| IDE  | 45        | 22.61%  |
| RAID | 14        | 7.04%   |
| NVMe | 14        | 7.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 172       | 92.47%  |
| AMD    | 14        | 7.53%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 3.23%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 5         | 2.69%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 4         | 2.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 2.15%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 2.15%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3         | 1.61%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 1.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.61%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3         | 1.61%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 1.61%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.61%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 1.61%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 1.61%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.08%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.08%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2         | 1.08%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.08%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.08%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 2         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.08%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.08%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.08%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 1.08%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.08%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.08%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.08%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.08%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.08%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i3           | 54        | 29.03%  |
| Intel Core i5           | 42        | 22.58%  |
| Intel Core i7           | 23        | 12.37%  |
| Intel Pentium           | 15        | 8.06%   |
| Intel Pentium Dual-Core | 11        | 5.91%   |
| Intel Core 2 Duo        | 9         | 4.84%   |
| Intel Celeron           | 5         | 2.69%   |
| Intel Atom              | 5         | 2.69%   |
| Intel Pentium Dual      | 3         | 1.61%   |
| AMD Ryzen 7             | 3         | 1.61%   |
| Other                   | 1         | 0.54%   |
| Intel Xeon              | 1         | 0.54%   |
| Intel Pentium D         | 1         | 0.54%   |
| Intel Pentium 4         | 1         | 0.54%   |
| Intel Core 2 Quad       | 1         | 0.54%   |
| AMD Ryzen 9             | 1         | 0.54%   |
| AMD Ryzen 5 PRO         | 1         | 0.54%   |
| AMD Ryzen 5             | 1         | 0.54%   |
| AMD Ryzen 3             | 1         | 0.54%   |
| AMD FX                  | 1         | 0.54%   |
| AMD E2                  | 1         | 0.54%   |
| AMD E1                  | 1         | 0.54%   |
| AMD Athlon Neo X2       | 1         | 0.54%   |
| AMD Athlon II Dual-Core | 1         | 0.54%   |
| AMD Athlon 64           | 1         | 0.54%   |
| AMD A4                  | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 144       | 77.42%  |
| 4      | 29        | 15.59%  |
| 6      | 4         | 2.15%   |
| 1      | 4         | 2.15%   |
| 8      | 3         | 1.61%   |
| 16     | 1         | 0.54%   |
| 3      | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 186       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 125       | 67.2%   |
| 1      | 61        | 32.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 184       | 98.4%   |
| Unknown        | 3         | 1.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 18.13%  |
| 0x306a9    | 30        | 15.54%  |
| 0x206a7    | 17        | 8.81%   |
| 0x20655    | 15        | 7.77%   |
| 0x1067a    | 15        | 7.77%   |
| 0x40651    | 10        | 5.18%   |
| 0x406e3    | 9         | 4.66%   |
| 0x30678    | 7         | 3.63%   |
| 0x806e9    | 6         | 3.11%   |
| 0x306d4    | 6         | 3.11%   |
| 0x306c3    | 6         | 3.11%   |
| 0x806ea    | 4         | 2.07%   |
| 0x906e9    | 3         | 1.55%   |
| 0x6fd      | 3         | 1.55%   |
| 0x20652    | 3         | 1.55%   |
| 0x30661    | 2         | 1.04%   |
| 0x0800820d | 2         | 1.04%   |
| 0xf65      | 1         | 0.52%   |
| 0x906eb    | 1         | 0.52%   |
| 0x806ec    | 1         | 0.52%   |
| 0x806c1    | 1         | 0.52%   |
| 0x6fb      | 1         | 0.52%   |
| 0x506e3    | 1         | 0.52%   |
| 0x506c9    | 1         | 0.52%   |
| 0x406c4    | 1         | 0.52%   |
| 0x406c3    | 1         | 0.52%   |
| 0x306e4    | 1         | 0.52%   |
| 0x10676    | 1         | 0.52%   |
| 0x0a201016 | 1         | 0.52%   |
| 0x08701021 | 1         | 0.52%   |
| 0x08608103 | 1         | 0.52%   |
| 0x08600106 | 1         | 0.52%   |
| 0x0810100b | 1         | 0.52%   |
| 0x0700010f | 1         | 0.52%   |
| 0x06006705 | 1         | 0.52%   |
| 0x0600063d | 1         | 0.52%   |
| 0x05000119 | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 37        | 19.89%  |
| SandyBridge | 22        | 11.83%  |
| Haswell     | 20        | 10.75%  |
| Penryn      | 19        | 10.22%  |
| Westmere    | 18        | 9.68%   |
| KabyLake    | 17        | 9.14%   |
| Skylake     | 12        | 6.45%   |
| Silvermont  | 10        | 5.38%   |
| Broadwell   | 6         | 3.23%   |
| Core        | 5         | 2.69%   |
| Zen+        | 2         | 1.08%   |
| Zen 2       | 2         | 1.08%   |
| NetBurst    | 2         | 1.08%   |
| K8 Hammer   | 2         | 1.08%   |
| Bonnell     | 2         | 1.08%   |
| Zen 3       | 1         | 0.54%   |
| Zen         | 1         | 0.54%   |
| TigerLake   | 1         | 0.54%   |
| K10         | 1         | 0.54%   |
| Jaguar      | 1         | 0.54%   |
| Goldmont    | 1         | 0.54%   |
| Excavator   | 1         | 0.54%   |
| Bulldozer   | 1         | 0.54%   |
| Bobcat      | 1         | 0.54%   |
| Unknown     | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 135       | 60.54%  |
| Nvidia           | 43        | 19.28%  |
| AMD              | 43        | 19.28%  |
| VIA Technologies | 2         | 0.9%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 8.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 6.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 5.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 4.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 4.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 4.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 3.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8         | 3.59%   |
| Intel HD Graphics 620                                                                    | 7         | 3.14%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 2.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.24%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.24%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.35%   |
| Intel HD Graphics 630                                                                    | 3         | 1.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.35%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.9%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.9%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.9%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.9%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.9%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.9%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.9%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.9%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.9%    |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.45%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.45%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.45%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.45%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.45%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 53.72%  |
| 1 x AMD        | 26        | 13.83%  |
| 1 x Nvidia     | 25        | 13.3%   |
| Intel + Nvidia | 17        | 9.04%   |
| Intel + AMD    | 16        | 8.51%   |
| 1 x VIA        | 2         | 1.06%   |
| AMD + Nvidia   | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 163       | 85.34%  |
| Proprietary | 21        | 10.99%  |
| Unknown     | 7         | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 59.16%  |
| 1.01-2.0   | 41        | 21.47%  |
| 0.51-1.0   | 14        | 7.33%   |
| 0.01-0.5   | 14        | 7.33%   |
| 3.01-4.0   | 7         | 3.66%   |
| 7.01-8.0   | 2         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 38        | 21.35%  |
| LG Display              | 25        | 14.04%  |
| AU Optronics            | 22        | 12.36%  |
| BOE                     | 14        | 7.87%   |
| Chimei Innolux          | 13        | 7.3%    |
| Hewlett-Packard         | 12        | 6.74%   |
| AOC                     | 8         | 4.49%   |
| Chi Mei Optoelectronics | 7         | 3.93%   |
| KTC                     | 4         | 2.25%   |
| Acer                    | 4         | 2.25%   |
| Dell                    | 3         | 1.69%   |
| BenQ                    | 3         | 1.69%   |
| Ancor Communications    | 3         | 1.69%   |
| Unknown                 | 3         | 1.69%   |
| Lenovo                  | 2         | 1.12%   |
| Goldstar                | 2         | 1.12%   |
| Apple                   | 2         | 1.12%   |
| ___                     | 1         | 0.56%   |
| Unknown (XXX)           | 1         | 0.56%   |
| Unknown                 | 1         | 0.56%   |
| TSN                     | 1         | 0.56%   |
| SKY                     | 1         | 0.56%   |
| Sharp                   | 1         | 0.56%   |
| PTW                     | 1         | 0.56%   |
| PiLot                   | 1         | 0.56%   |
| PANDA                   | 1         | 0.56%   |
| MStar                   | 1         | 0.56%   |
| LGD                     | 1         | 0.56%   |
| InnoLux Display         | 1         | 0.56%   |
| EMP                     | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 1.66%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 1.66%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.66%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 3         | 1.66%   |
| Unknown                                                                  | 3         | 1.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 2         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 2         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 1.1%    |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 1.1%    |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 1.1%    |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 1.1%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 2         | 1.1%    |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 1.1%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 1.1%    |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 1.1%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.1%    |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 1.1%    |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.55%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.55%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 1         | 0.55%   |
| TSN 24 Monitor TSN2400 1360x768 510x287mm 23.0-inch                      | 1         | 0.55%   |
| SKY TV-monitor SKY0104 1920x1080 885x498mm 40.0-inch                     | 1         | 0.55%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch     | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM04D5 1920x1080                         | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch     | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM00A6 1280x1024 380x310mm 19.3-inch     | 1         | 0.55%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch        | 1         | 0.55%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch       | 1         | 0.55%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch       | 1         | 0.55%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch        | 1         | 0.55%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch        | 1         | 0.55%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch        | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC494A 1366x768 344x193mm 15.5-inch     | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 86        | 49.71%  |
| 1920x1080 (FHD)    | 47        | 27.17%  |
| 1600x900 (HD+)     | 9         | 5.2%    |
| 1440x900 (WXGA+)   | 6         | 3.47%   |
| 1280x1024 (SXGA)   | 4         | 2.31%   |
| 2560x1440 (QHD)    | 3         | 1.73%   |
| 1680x1050 (WSXGA+) | 3         | 1.73%   |
| 1360x768           | 3         | 1.73%   |
| 1280x800 (WXGA)    | 3         | 1.73%   |
| 3840x2160 (4K)     | 2         | 1.16%   |
| 2160x1440          | 1         | 0.58%   |
| 1920x540           | 1         | 0.58%   |
| 1920x1200 (WUXGA)  | 1         | 0.58%   |
| 1680x945           | 1         | 0.58%   |
| 1600x1200          | 1         | 0.58%   |
| 1280x720 (HD)      | 1         | 0.58%   |
| 1024x600           | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 75        | 41.9%   |
| 21      | 13        | 7.26%   |
| 18      | 13        | 7.26%   |
| 13      | 12        | 6.7%    |
| 17      | 8         | 4.47%   |
| 23      | 7         | 3.91%   |
| 19      | 7         | 3.91%   |
| 14      | 7         | 3.91%   |
| Unknown | 7         | 3.91%   |
| 12      | 6         | 3.35%   |
| 27      | 4         | 2.23%   |
| 24      | 4         | 2.23%   |
| 20      | 3         | 1.68%   |
| 52      | 2         | 1.12%   |
| 22      | 2         | 1.12%   |
| 10      | 2         | 1.12%   |
| 46      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 37      | 1         | 0.56%   |
| 32      | 1         | 0.56%   |
| 31      | 1         | 0.56%   |
| 16      | 1         | 0.56%   |
| 11      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 51.41%  |
| 401-500     | 33        | 18.64%  |
| 501-600     | 15        | 8.47%   |
| 351-400     | 12        | 6.78%   |
| 201-300     | 12        | 6.78%   |
| Unknown     | 7         | 3.95%   |
| 1001-1500   | 3         | 1.69%   |
| 801-900     | 2         | 1.13%   |
| 701-800     | 1         | 0.56%   |
| 601-700     | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 144       | 84.71%  |
| 16/10   | 12        | 7.06%   |
| Unknown | 6         | 3.53%   |
| 5/4     | 4         | 2.35%   |
| 6/5     | 1         | 0.59%   |
| 4/3     | 1         | 0.59%   |
| 32/9    | 1         | 0.59%   |
| 3/2     | 1         | 0.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 74        | 41.57%  |
| 201-250        | 19        | 10.67%  |
| 151-200        | 17        | 9.55%   |
| 81-90          | 16        | 8.99%   |
| 141-150        | 14        | 7.87%   |
| Unknown        | 7         | 3.93%   |
| 61-70          | 6         | 3.37%   |
| 301-350        | 4         | 2.25%   |
| 121-130        | 4         | 2.25%   |
| 71-80          | 3         | 1.69%   |
| 501-1000       | 3         | 1.69%   |
| More than 1000 | 2         | 1.12%   |
| 351-500        | 2         | 1.12%   |
| 41-50          | 2         | 1.12%   |
| 131-140        | 2         | 1.12%   |
| 111-120        | 2         | 1.12%   |
| 51-60          | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 85        | 48.3%   |
| 51-100  | 51        | 28.98%  |
| 121-160 | 25        | 14.2%   |
| Unknown | 7         | 3.98%   |
| 1-50    | 4         | 2.27%   |
| 161-240 | 4         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 169       | 89.42%  |
| 2     | 11        | 5.82%   |
| 0     | 8         | 4.23%   |
| 3     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 117       | 38.36%  |
| Qualcomm Atheros                | 50        | 16.39%  |
| Intel                           | 47        | 15.41%  |
| Broadcom                        | 29        | 9.51%   |
| Ralink Technology               | 18        | 5.9%    |
| Ralink                          | 10        | 3.28%   |
| Qualcomm Atheros Communications | 4         | 1.31%   |
| VIA Technologies                | 3         | 0.98%   |
| Samsung Electronics             | 3         | 0.98%   |
| Nvidia                          | 3         | 0.98%   |
| MediaTek                        | 3         | 0.98%   |
| D-Link System                   | 3         | 0.98%   |
| Xiaomi                          | 2         | 0.66%   |
| Marvell Technology Group        | 2         | 0.66%   |
| Huawei Technologies             | 2         | 0.66%   |
| D-Link                          | 2         | 0.66%   |
| Broadcom Limited                | 2         | 0.66%   |
| TP-Link                         | 1         | 0.33%   |
| Sierra Wireless                 | 1         | 0.33%   |
| LG Electronics                  | 1         | 0.33%   |
| Hewlett-Packard                 | 1         | 0.33%   |
| AMD                             | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 20.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 12.32%  |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 3.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 3.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.87%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5         | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.43%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                    | 4         | 1.15%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.15%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 1.15%   |
| Intel Wireless 8260                                               | 4         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 1.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.86%   |
| Intel Wireless 7265                                               | 3         | 0.86%   |
| Intel Wireless 7260                                               | 3         | 0.86%   |
| Intel Wireless 3160                                               | 3         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.86%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.86%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.57%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2         | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.57%   |
| MediaTek Nokia 5.1 Plus                                           | 2         | 0.57%   |
| Intel WiFi Link 5100                                              | 2         | 0.57%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 41        | 25.31%  |
| Intel                           | 40        | 24.69%  |
| Broadcom                        | 21        | 12.96%  |
| Ralink Technology               | 18        | 11.11%  |
| Realtek Semiconductor           | 17        | 10.49%  |
| Ralink                          | 10        | 6.17%   |
| Qualcomm Atheros Communications | 4         | 2.47%   |
| D-Link System                   | 3         | 1.85%   |
| D-Link                          | 2         | 1.23%   |
| TP-Link                         | 1         | 0.62%   |
| Sierra Wireless                 | 1         | 0.62%   |
| MediaTek                        | 1         | 0.62%   |
| Marvell Technology Group        | 1         | 0.62%   |
| Hewlett-Packard                 | 1         | 0.62%   |
| Broadcom Limited                | 1         | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 12        | 7.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 11        | 6.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 6.17%   |
| Ralink MT7601U Wireless Adapter                                      | 7         | 4.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 4.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 3.09%   |
| Intel Wireless 8265 / 8275                                           | 5         | 3.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 2.47%   |
| Ralink RT5370 Wireless Adapter                                       | 4         | 2.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 2.47%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 2.47%   |
| Intel Wireless 8260                                                  | 4         | 2.47%   |
| Intel Wireless 7265                                                  | 3         | 1.85%   |
| Intel Wireless 7260                                                  | 3         | 1.85%   |
| Intel Wireless 3160                                                  | 3         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 1.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 1.23%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.23%   |
| Intel WiFi Link 5100                                                 | 2         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 1.23%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.23%   |
| Intel Centrino Wireless-N 135                                        | 2         | 1.23%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.23%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.23%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2         | 1.23%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 1.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.62%   |
| Sierra Wireless EM7305                                               | 1         | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.62%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.62%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.62%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.62%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 114       | 61.62%  |
| Intel                    | 30        | 16.22%  |
| Qualcomm Atheros         | 12        | 6.49%   |
| Broadcom                 | 11        | 5.95%   |
| VIA Technologies         | 3         | 1.62%   |
| Samsung Electronics      | 3         | 1.62%   |
| Nvidia                   | 3         | 1.62%   |
| Xiaomi                   | 2         | 1.08%   |
| MediaTek                 | 2         | 1.08%   |
| Marvell Technology Group | 1         | 0.54%   |
| LG Electronics           | 1         | 0.54%   |
| Huawei Technologies      | 1         | 0.54%   |
| Broadcom Limited         | 1         | 0.54%   |
| AMD                      | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 38.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 23.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 2.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 2.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.61%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.08%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.08%   |
| MediaTek Nokia 5.1 Plus                                           | 2         | 1.08%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.08%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.54%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.54%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.54%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.54%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.54%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.54%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.54%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.54%   |
| Huawei E353/E3131                                                 | 1         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 175       | 54.18%  |
| WiFi     | 147       | 45.51%  |
| Modem    | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 65.76%  |
| Ethernet | 63        | 34.24%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 119       | 62.63%  |
| 1     | 68        | 35.79%  |
| 0     | 3         | 1.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 186       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 27.17%  |
| Qualcomm Atheros Communications | 12        | 13.04%  |
| Broadcom                        | 10        | 10.87%  |
| Realtek Semiconductor           | 7         | 7.61%   |
| Lite-On Technology              | 5         | 5.43%   |
| Foxconn / Hon Hai               | 5         | 5.43%   |
| Ralink                          | 4         | 4.35%   |
| IMC Networks                    | 4         | 4.35%   |
| Dell                            | 4         | 4.35%   |
| Cambridge Silicon Radio         | 4         | 4.35%   |
| Foxconn International           | 3         | 3.26%   |
| Apple                           | 2         | 2.17%   |
| Toshiba                         | 1         | 1.09%   |
| Ralink Technology               | 1         | 1.09%   |
| Marvell Semiconductor           | 1         | 1.09%   |
| Integrated System Solution      | 1         | 1.09%   |
| Hewlett-Packard                 | 1         | 1.09%   |
| Chicony Electronics             | 1         | 1.09%   |
| Alps Electric                   | 1         | 1.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 18        | 19.57%  |
| Qualcomm Atheros  Bluetooth Device                    | 5         | 5.43%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 5.43%   |
| Realtek Bluetooth Radio                               | 4         | 4.35%   |
| Ralink RT3290 Bluetooth                               | 4         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 4.35%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3         | 3.26%   |
| IMC Networks Bluetooth Device                         | 3         | 3.26%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 3.26%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 3         | 3.26%   |
| Realtek RTL8723B Bluetooth                            | 2         | 2.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 2.17%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 2.17%   |
| Dell Wireless 365 Bluetooth                           | 2         | 2.17%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 2.17%   |
| Apple Bluetooth Host Controller                       | 2         | 2.17%   |
| Toshiba Bluetooth Device                              | 1         | 1.09%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.09%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 1.09%   |
| Qualcomm Atheros Bluetooth                            | 1         | 1.09%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 1.09%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 1.09%   |
| Lite-On Wireless_Device                               | 1         | 1.09%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 1.09%   |
| Lite-On BCM43142A0                                    | 1         | 1.09%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 1.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1         | 1.09%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.09%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 1.09%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.09%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 1.09%   |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 1.09%   |
| Foxconn / Hon Hai Acer Module                         | 1         | 1.09%   |
| Dell DW375 Bluetooth Module                           | 1         | 1.09%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 1.09%   |
| Chicony Bluetooth (RTL8723BE)                         | 1         | 1.09%   |
| Broadcom HP Portable Bumble Bee                       | 1         | 1.09%   |
| Broadcom Bluetooth Device                             | 1         | 1.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 163       | 69.66%  |
| AMD                   | 35        | 14.96%  |
| Nvidia                | 26        | 11.11%  |
| VIA Technologies      | 3         | 1.28%   |
| JMTek                 | 2         | 0.85%   |
| Texas Instruments     | 1         | 0.43%   |
| Medeli Electronics    | 1         | 0.43%   |
| Logitech              | 1         | 0.43%   |
| Logic3 / SpectraVideo | 1         | 0.43%   |
| Guillemot             | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 30        | 11.24%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29        | 10.86%  |
| Intel Sunrise Point-LP HD Audio                                                   | 22        | 8.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 18        | 6.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 13        | 4.87%   |
| Intel Haswell-ULT HD Audio Controller                                             | 12        | 4.49%   |
| Intel 8 Series HD Audio Controller                                                | 12        | 4.49%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 10        | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 8         | 3%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7         | 2.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 2.25%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 2.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 6         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5         | 1.87%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4         | 1.5%    |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 1.5%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 3         | 1.12%   |
| Nvidia High Definition Audio Controller                                           | 3         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 1.12%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 1.12%   |
| Nvidia MCP79 High Definition Audio                                                | 2         | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.75%   |
| JMTek USB PnP Audio Device(EEPROM)                                                | 2         | 0.75%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 0.75%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 0.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2         | 0.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.75%   |
| AMD FCH Azalia Controller                                                         | 2         | 0.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.75%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 2         | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.37%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.37%   |
| Nvidia MCP89 High Definition Audio                                                | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 26        | 22.41%  |
| Samsung Electronics | 23        | 19.83%  |
| SK hynix            | 22        | 18.97%  |
| Micron Technology   | 15        | 12.93%  |
| A-DATA Technology   | 9         | 7.76%   |
| Kingston            | 8         | 6.9%    |
| TwinMOS             | 2         | 1.72%   |
| Nanya Technology    | 2         | 1.72%   |
| Thermaltake         | 1         | 0.86%   |
| Team                | 1         | 0.86%   |
| Ramaxel Technology  | 1         | 0.86%   |
| Patriot             | 1         | 0.86%   |
| GeIL                | 1         | 0.86%   |
| Elpida              | 1         | 0.86%   |
| Dynet               | 1         | 0.86%   |
| Crucial             | 1         | 0.86%   |
| ASint Technology    | 1         | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 4         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 3.13%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 3         | 2.34%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s              | 2         | 1.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 2         | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 2         | 1.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 2         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 2         | 1.56%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.78%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR2                          | 1         | 0.78%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 1         | 0.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                   | 1         | 0.78%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 0.78%   |
| Unknown RAM Module 4096MB SODIMM DDR2                       | 1         | 0.78%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1333MT/s               | 1         | 0.78%   |
| Unknown RAM Module 4096MB DIMM SDRAM                        | 1         | 0.78%   |
| Unknown RAM Module 4096MB DIMM DDR3 800MT/s                 | 1         | 0.78%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 0.78%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1         | 0.78%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1         | 0.78%   |
| Unknown RAM Module 2GB DIMM 667MT/s                         | 1         | 0.78%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                | 1         | 0.78%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s               | 1         | 0.78%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1         | 0.78%   |
| Unknown RAM Module 2048MB DIMM DDR2                         | 1         | 0.78%   |
| Unknown RAM Module 1GB DIMM 800MT/s                         | 1         | 0.78%   |
| Unknown RAM Module 1GB DIMM 533MT/s                         | 1         | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s                 | 1         | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR2 200MT/s                 | 1         | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR2                         | 1         | 0.78%   |
| TwinMOS RAM 9DPCBNZB-TATP 4GB DIMM DDR3 1333MT/s            | 1         | 0.78%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s            | 1         | 0.78%   |
| Thermaltake RAM R019D408GX2-3200C16A 8GB DIMM DDR4 2666MT/s | 1         | 0.78%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 0.78%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 0.78%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s            | 1         | 0.78%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 54        | 57.45%  |
| DDR4    | 22        | 23.4%   |
| SDRAM   | 6         | 6.38%   |
| DDR2    | 6         | 6.38%   |
| Unknown | 4         | 4.26%   |
| LPDDR4  | 1         | 1.06%   |
| DDR     | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 56        | 60.87%  |
| DIMM   | 36        | 39.13%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 48        | 44.86%  |
| 2048  | 26        | 24.3%   |
| 8192  | 21        | 19.63%  |
| 1024  | 5         | 4.67%   |
| 16384 | 4         | 3.74%   |
| 32768 | 2         | 1.87%   |
| 512   | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 33        | 31.73%  |
| 1333    | 16        | 15.38%  |
| 2667    | 10        | 9.62%   |
| Unknown | 6         | 5.77%   |
| 2400    | 5         | 4.81%   |
| 1334    | 5         | 4.81%   |
| 800     | 5         | 4.81%   |
| 3200    | 3         | 2.88%   |
| 667     | 3         | 2.88%   |
| 3266    | 2         | 1.92%   |
| 2133    | 2         | 1.92%   |
| 1067    | 2         | 1.92%   |
| 4199    | 1         | 0.96%   |
| 3800    | 1         | 0.96%   |
| 3400    | 1         | 0.96%   |
| 3066    | 1         | 0.96%   |
| 3000    | 1         | 0.96%   |
| 2666    | 1         | 0.96%   |
| 2200    | 1         | 0.96%   |
| 1639    | 1         | 0.96%   |
| 533     | 1         | 0.96%   |
| 333     | 1         | 0.96%   |
| 266     | 1         | 0.96%   |
| 200     | 1         | 0.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 7         | 58.33%  |
| Seiko Epson        | 3         | 25%     |
| Hewlett-Packard    | 1         | 8.33%   |
| Brother Industries | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6020                     | 2         | 16.67%  |
| Canon LBP6000                     | 2         | 16.67%  |
| Seiko Epson XP-243 245 247 Series | 1         | 8.33%   |
| Seiko Epson XP-202 203 206 Series | 1         | 8.33%   |
| Seiko Epson Printer               | 1         | 8.33%   |
| HP DeskJet 5810 series            | 1         | 8.33%   |
| Canon MG5700 series               | 1         | 8.33%   |
| Canon LBP6030w/6018w              | 1         | 8.33%   |
| Canon LBP2900                     | 1         | 8.33%   |
| Brother MFC-J480DW                | 1         | 8.33%   |

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
| Chicony Electronics                    | 26        | 24.07%  |
| Microdia                               | 16        | 14.81%  |
| Cheng Uei Precision Industry (Foxlink) | 10        | 9.26%   |
| Realtek Semiconductor                  | 9         | 8.33%   |
| Acer                                   | 8         | 7.41%   |
| Sunplus Innovation Technology          | 7         | 6.48%   |
| Suyin                                  | 5         | 4.63%   |
| Syntek                                 | 4         | 3.7%    |
| IMC Networks                           | 3         | 2.78%   |
| Apple                                  | 3         | 2.78%   |
| Silicon Motion                         | 2         | 1.85%   |
| Samsung Electronics                    | 2         | 1.85%   |
| Quanta                                 | 2         | 1.85%   |
| Lite-On Technology                     | 2         | 1.85%   |
| Alcor Micro                            | 2         | 1.85%   |
| Primax Electronics                     | 1         | 0.93%   |
| Pixart Imaging                         | 1         | 0.93%   |
| Microsoft                              | 1         | 0.93%   |
| GEMBIRD                                | 1         | 0.93%   |
| Aveo Technology                        | 1         | 0.93%   |
| Arkmicro Technologies                  | 1         | 0.93%   |
| ALi                                    | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Acer Lenovo EasyCamera                              | 6         | 5.5%    |
| Microdia Integrated_Webcam_HD                       | 4         | 3.67%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 3.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 3.67%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 3         | 2.75%   |
| Microdia Integrated Webcam                          | 3         | 2.75%   |
| Chicony Integrated Camera                           | 3         | 2.75%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.83%   |
| Suyin HP Truevision HD                              | 2         | 1.83%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 2         | 1.83%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.83%   |
| Samsung Galaxy A5 (MTP)                             | 2         | 1.83%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.83%   |
| Chicony HD WebCam                                   | 2         | 1.83%   |
| Chicony Acer CrystalEye Webcam                      | 2         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.83%   |
| Apple iPhone5/5C/5S/6                               | 2         | 1.83%   |
| Syntek USB2.0 Camera                                | 1         | 0.92%   |
| Syntek EasyCamera                                   | 1         | 0.92%   |
| Suyin WebCam                                        | 1         | 0.92%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.92%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 0.92%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 0.92%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.92%   |
| Sunplus Dell HD Webcam                              | 1         | 0.92%   |
| Silicon Motion WebCam SC-13HDL11431N                | 1         | 0.92%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.92%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.92%   |
| Realtek USB Camera                                  | 1         | 0.92%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.92%   |
| Realtek Integrated Webcam_HD                        | 1         | 0.92%   |
| Realtek Integrated Webcam                           | 1         | 0.92%   |
| Realtek HP Webcam                                   | 1         | 0.92%   |
| Realtek HP Truevision HD                            | 1         | 0.92%   |
| Realtek HD Webcam - Realtek                         | 1         | 0.92%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 0.92%   |
| Quanta HD Webcam                                    | 1         | 0.92%   |
| Quanta HD User Facing                               | 1         | 0.92%   |
| Primax webcam                                       | 1         | 0.92%   |
| Pixart Imaging VGA Webcam                           | 1         | 0.92%   |

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
| Broadcom | 8         | 88.89%  |
| OmniKey  | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 4         | 44.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 33.33%  |
| OmniKey CardMan 4321                                                         | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 135       | 71.43%  |
| 1     | 47        | 24.87%  |
| 2     | 6         | 3.17%   |
| 3     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 23.81%  |
| Graphics card            | 13        | 20.63%  |
| Net/wireless             | 11        | 17.46%  |
| Chipcard                 | 9         | 14.29%  |
| Bluetooth                | 4         | 6.35%   |
| Multimedia controller    | 3         | 4.76%   |
| Storage                  | 2         | 3.17%   |
| Net/ethernet             | 2         | 3.17%   |
| Communication controller | 2         | 3.17%   |
| Card reader              | 1         | 1.59%   |
| Camera                   | 1         | 1.59%   |

