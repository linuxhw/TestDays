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

Total: 274

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 46        | 23.35%  |
| Ubuntu 18.04        | 19        | 9.64%   |
| OpenMandriva 4.2    | 14        | 7.11%   |
| Linux Mint 20.1     | 7         | 3.55%   |
| OpenMandriva 4.3    | 6         | 3.05%   |
| KDE neon 20.04      | 6         | 3.05%   |
| Pop!_OS 20.04       | 5         | 2.54%   |
| Arch                | 5         | 2.54%   |
| Ubuntu 21.04        | 4         | 2.03%   |
| Ubuntu 19.10        | 4         | 2.03%   |
| ArcoLinux Rolling   | 4         | 2.03%   |
| Xubuntu 20.04       | 3         | 1.52%   |
| Ubuntu 20.10        | 3         | 1.52%   |
| ROSA R10            | 3         | 1.52%   |
| Manjaro             | 3         | 1.52%   |
| Linux Mint 20.2     | 3         | 1.52%   |
| Fedora 35           | 3         | 1.52%   |
| BlackPanther 18.1   | 3         | 1.52%   |
| Zorin 16            | 2         | 1.02%   |
| Ubuntu 22.04        | 2         | 1.02%   |
| Ubuntu 19.04        | 2         | 1.02%   |
| Ubuntu 16.04        | 2         | 1.02%   |
| ROSA R8.1           | 2         | 1.02%   |
| ROSA R11            | 2         | 1.02%   |
| Manjaro 20.1        | 2         | 1.02%   |
| Kubuntu 20.04       | 2         | 1.02%   |
| Kali 2021.2         | 2         | 1.02%   |
| Kali 2021.1         | 2         | 1.02%   |
| Fedora 33           | 2         | 1.02%   |
| Debian 11           | 2         | 1.02%   |
| Debian 10           | 2         | 1.02%   |
| Xubuntu 18.04       | 1         | 0.51%   |
| UbuntuDDE 20.04     | 1         | 0.51%   |
| Ubuntu Budgie 22.04 | 1         | 0.51%   |
| Ubuntu 21.10        | 1         | 0.51%   |
| Skygate 1.6-16219   | 1         | 0.51%   |
| Pop!_OS 21.10       | 1         | 0.51%   |
| Pop!_OS 21.04       | 1         | 0.51%   |
| Pop!_OS 20.10       | 1         | 0.51%   |
| Peppermint 9        | 1         | 0.51%   |
| Peppermint 10       | 1         | 0.51%   |
| Pear OS 20.04       | 1         | 0.51%   |
| Parrot 5.0          | 1         | 0.51%   |
| Parrot 4.11         | 1         | 0.51%   |
| OpenMandriva 4.90   | 1         | 0.51%   |
| OpenMandriva 4.50   | 1         | 0.51%   |
| MX 19               | 1         | 0.51%   |
| Manjaro 21.2.4      | 1         | 0.51%   |
| Manjaro 18.0.4      | 1         | 0.51%   |
| Linux Mint 20       | 1         | 0.51%   |
| Linux Mint 19.2     | 1         | 0.51%   |
| Linux Mint 19       | 1         | 0.51%   |
| Kubuntu 2.0         | 1         | 0.51%   |
| Kali 2021.4         | 1         | 0.51%   |
| Fedora 31           | 1         | 0.51%   |
| Fedora 29           | 1         | 0.51%   |
| Debian Unstable     | 1         | 0.51%   |
| Clear Linux 34640   | 1         | 0.51%   |
| CentOS 7            | 1         | 0.51%   |
| Artix Rolling       | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 79        | 41.15%  |
| OpenMandriva  | 22        | 11.46%  |
| Linux Mint    | 13        | 6.77%   |
| Pop!_OS       | 8         | 4.17%   |
| Manjaro       | 7         | 3.65%   |
| Fedora        | 7         | 3.65%   |
| ROSA          | 6         | 3.13%   |
| KDE neon      | 6         | 3.13%   |
| Kali          | 5         | 2.6%    |
| Debian        | 5         | 2.6%    |
| Arch          | 5         | 2.6%    |
| Xubuntu       | 4         | 2.08%   |
| ArcoLinux     | 4         | 2.08%   |
| Kubuntu       | 3         | 1.56%   |
| BlackPanther  | 3         | 1.56%   |
| Zorin         | 2         | 1.04%   |
| Peppermint    | 2         | 1.04%   |
| Parrot        | 2         | 1.04%   |
| UbuntuDDE     | 1         | 0.52%   |
| Ubuntu Budgie | 1         | 0.52%   |
| Skygate       | 1         | 0.52%   |
| Pear OS       | 1         | 0.52%   |
| MX            | 1         | 0.52%   |
| Clear Linux   | 1         | 0.52%   |
| CentOS        | 1         | 0.52%   |
| Artix         | 1         | 0.52%   |
| ArchLabs      | 1         | 0.52%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 14        | 6.8%    |
| 5.16.7-desktop-1omv4003         | 6         | 2.91%   |
| 5.4.0-42-generic                | 5         | 2.43%   |
| 5.8.0-50-generic                | 4         | 1.94%   |
| 5.4.0-72-generic                | 4         | 1.94%   |
| 5.4.0-54-generic                | 4         | 1.94%   |
| 5.4.0-29-generic                | 4         | 1.94%   |
| 5.0.0-37-generic                | 4         | 1.94%   |
| 5.4.0-65-generic                | 3         | 1.46%   |
| 5.4.0-56-generic                | 3         | 1.46%   |
| 5.4.0-52-generic                | 3         | 1.46%   |
| 5.3.0-46-generic                | 3         | 1.46%   |
| 5.13.0-30-generic               | 3         | 1.46%   |
| 5.11.0-38-generic               | 3         | 1.46%   |
| 5.11.0-27-generic               | 3         | 1.46%   |
| 5.8.0-44-generic                | 2         | 0.97%   |
| 5.4.0-88-generic                | 2         | 0.97%   |
| 5.4.0-81-generic                | 2         | 0.97%   |
| 5.4.0-80-generic                | 2         | 0.97%   |
| 5.4.0-7625-generic              | 2         | 0.97%   |
| 5.4.0-48-generic                | 2         | 0.97%   |
| 5.4.0-33-generic                | 2         | 0.97%   |
| 5.3.0-40-generic                | 2         | 0.97%   |
| 5.11.0-40-generic               | 2         | 0.97%   |
| 5.11.0-36-generic               | 2         | 0.97%   |
| 5.11.0-34-generic               | 2         | 0.97%   |
| 5.11.0-25-generic               | 2         | 0.97%   |
| 5.0.0-29-generic                | 2         | 0.97%   |
| 5.0.0-23-generic                | 2         | 0.97%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.97%   |
| 4.18.16-desktop-1bP             | 2         | 0.97%   |
| 4.15.0-42-generic               | 2         | 0.97%   |
| 5.9.11-3-MANJARO                | 1         | 0.49%   |
| 5.8.18-300.fc33.x86_64          | 1         | 0.49%   |
| 5.8.0-7630-generic              | 1         | 0.49%   |
| 5.8.0-63-generic                | 1         | 0.49%   |
| 5.8.0-59-generic                | 1         | 0.49%   |
| 5.8.0-48-generic                | 1         | 0.49%   |
| 5.8.0-45-generic                | 1         | 0.49%   |
| 5.8.0-43-generic                | 1         | 0.49%   |
| 5.8.0-36-generic                | 1         | 0.49%   |
| 5.8.0-29-generic                | 1         | 0.49%   |
| 5.7.17-2-MANJARO                | 1         | 0.49%   |
| 5.7.0-kali1-amd64               | 1         | 0.49%   |
| 5.6.14-desktop-2bP              | 1         | 0.49%   |
| 5.6.0-2-amd64                   | 1         | 0.49%   |
| 5.4.72-1-lts                    | 1         | 0.49%   |
| 5.4.60-2-MANJARO                | 1         | 0.49%   |
| 5.4.15-200.fc31.x86_64          | 1         | 0.49%   |
| 5.4.0-77-generic                | 1         | 0.49%   |
| 5.4.0-7642-generic              | 1         | 0.49%   |
| 5.4.0-7626-generic              | 1         | 0.49%   |
| 5.4.0-74-generic                | 1         | 0.49%   |
| 5.4.0-71-generic                | 1         | 0.49%   |
| 5.4.0-70-generic                | 1         | 0.49%   |
| 5.4.0-58-generic                | 1         | 0.49%   |
| 5.4.0-51-generic                | 1         | 0.49%   |
| 5.4.0-47-generic                | 1         | 0.49%   |
| 5.4.0-40-generic                | 1         | 0.49%   |
| 5.4.0-39-generic                | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 23.2%   |
| 5.11.0  | 16        | 8.25%   |
| 5.8.0   | 14        | 7.22%   |
| 5.10.14 | 14        | 7.22%   |
| 4.15.0  | 12        | 6.19%   |
| 5.3.0   | 10        | 5.15%   |
| 5.0.0   | 10        | 5.15%   |
| 5.16.7  | 6         | 3.09%   |
| 5.13.0  | 6         | 3.09%   |
| 5.10.0  | 6         | 3.09%   |
| 5.15.0  | 4         | 2.06%   |
| 4.18.16 | 3         | 1.55%   |
| 5.15.7  | 2         | 1.03%   |
| 5.14.0  | 2         | 1.03%   |
| 4.9.60  | 2         | 1.03%   |
| 4.4.0   | 2         | 1.03%   |
| 4.19.0  | 2         | 1.03%   |
| 5.9.11  | 1         | 0.52%   |
| 5.8.18  | 1         | 0.52%   |
| 5.7.17  | 1         | 0.52%   |
| 5.7.0   | 1         | 0.52%   |
| 5.6.14  | 1         | 0.52%   |
| 5.6.0   | 1         | 0.52%   |
| 5.4.72  | 1         | 0.52%   |
| 5.4.60  | 1         | 0.52%   |
| 5.4.15  | 1         | 0.52%   |
| 5.18.12 | 1         | 0.52%   |
| 5.17.4  | 1         | 0.52%   |
| 5.17.0  | 1         | 0.52%   |
| 5.16.11 | 1         | 0.52%   |
| 5.15.8  | 1         | 0.52%   |
| 5.15.5  | 1         | 0.52%   |
| 5.15.25 | 1         | 0.52%   |
| 5.15.15 | 1         | 0.52%   |
| 5.15.11 | 1         | 0.52%   |
| 5.15.10 | 1         | 0.52%   |
| 5.14.18 | 1         | 0.52%   |
| 5.14.16 | 1         | 0.52%   |
| 5.13.2  | 1         | 0.52%   |
| 5.12.5  | 1         | 0.52%   |
| 5.12.4  | 1         | 0.52%   |
| 5.12.15 | 1         | 0.52%   |
| 5.11.2  | 1         | 0.52%   |
| 5.11.15 | 1         | 0.52%   |
| 5.10.82 | 1         | 0.52%   |
| 5.10.75 | 1         | 0.52%   |
| 5.10.4  | 1         | 0.52%   |
| 5.10.3  | 1         | 0.52%   |
| 4.9.9   | 1         | 0.52%   |
| 4.9.76  | 1         | 0.52%   |
| 4.19.79 | 1         | 0.52%   |
| 4.19.30 | 1         | 0.52%   |
| 4.18.0  | 1         | 0.52%   |
| 4.1.38  | 1         | 0.52%   |
| 3.10.0  | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 48        | 24.74%  |
| 5.10    | 24        | 12.37%  |
| 5.11    | 18        | 9.28%   |
| 5.8     | 15        | 7.73%   |
| 5.15    | 12        | 6.19%   |
| 4.15    | 12        | 6.19%   |
| 5.3     | 10        | 5.15%   |
| 5.0     | 10        | 5.15%   |
| 5.16    | 7         | 3.61%   |
| 5.13    | 7         | 3.61%   |
| 5.14    | 4         | 2.06%   |
| 4.9     | 4         | 2.06%   |
| 4.19    | 4         | 2.06%   |
| 4.18    | 4         | 2.06%   |
| 5.12    | 3         | 1.55%   |
| 5.7     | 2         | 1.03%   |
| 5.6     | 2         | 1.03%   |
| 5.17    | 2         | 1.03%   |
| 4.4     | 2         | 1.03%   |
| 5.9     | 1         | 0.52%   |
| 5.18    | 1         | 0.52%   |
| 4.1     | 1         | 0.52%   |
| 3.10    | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 171       | 97.71%  |
| i686   | 4         | 2.29%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 80        | 43.01%  |
| KDE5            | 37        | 19.89%  |
| Unknown         | 24        | 12.9%   |
| XFCE            | 11        | 5.91%   |
| X-Cinnamon      | 7         | 3.76%   |
| KDE             | 5         | 2.69%   |
| MATE            | 4         | 2.15%   |
| KDE4            | 4         | 2.15%   |
| Cinnamon        | 3         | 1.61%   |
| LXQt            | 2         | 1.08%   |
| i3              | 2         | 1.08%   |
| Unity           | 1         | 0.54%   |
| Peppermint      | 1         | 0.54%   |
| LXDE            | 1         | 0.54%   |
| GNOME Flashback | 1         | 0.54%   |
| fvwm            | 1         | 0.54%   |
| Deepin          | 1         | 0.54%   |
| Budgie          | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 156       | 87.64%  |
| Unknown | 11        | 6.18%   |
| Wayland | 10        | 5.62%   |
| Tty     | 1         | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 103       | 55.98%  |
| SDDM    | 32        | 17.39%  |
| GDM     | 17        | 9.24%   |
| LightDM | 14        | 7.61%   |
| TDM     | 7         | 3.8%    |
| GDM3    | 6         | 3.26%   |
| KDM     | 4         | 2.17%   |
| SLiM    | 1         | 0.54%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 72        | 39.78%  |
| fr_FR       | 61        | 33.7%   |
| Unknown     | 25        | 13.81%  |
| en_GB       | 8         | 4.42%   |
| C           | 5         | 2.76%   |
| ar_DZ       | 4         | 2.21%   |
| fr_DZ       | 2         | 1.1%    |
| ar_EG       | 2         | 1.1%    |
| fr_BE       | 1         | 0.55%   |
| en-US-UTF-8 | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 127       | 70.95%  |
| EFI  | 52        | 29.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 135       | 74.59%  |
| Overlay | 23        | 12.71%  |
| Btrfs   | 9         | 4.97%   |
| Unknown | 9         | 4.97%   |
| Ext2    | 3         | 1.66%   |
| Xfs     | 1         | 0.55%   |
| Ext3    | 1         | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 113       | 63.48%  |
| MBR     | 37        | 20.79%  |
| GPT     | 28        | 15.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 145       | 80.11%  |
| Yes       | 36        | 19.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 51.4%   |
| Yes       | 87        | 48.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 31        | 17.71%  |
| Hewlett-Packard     | 24        | 13.71%  |
| Lenovo              | 20        | 11.43%  |
| ASUSTek Computer    | 13        | 7.43%   |
| Gigabyte Technology | 12        | 6.86%   |
| MSI                 | 11        | 6.29%   |
| Acer                | 11        | 6.29%   |
| Toshiba             | 8         | 4.57%   |
| Sony                | 6         | 3.43%   |
| ECS                 | 6         | 3.43%   |
| Unknown             | 6         | 3.43%   |
| Foxconn             | 5         | 2.86%   |
| Packard Bell        | 3         | 1.71%   |
| Intel               | 3         | 1.71%   |
| Biostar             | 3         | 1.71%   |
| Samsung Electronics | 2         | 1.14%   |
| Fujitsu             | 2         | 1.14%   |
| ASRock              | 2         | 1.14%   |
| Apple               | 2         | 1.14%   |
| WeiBu               | 1         | 0.57%   |
| Pegatron            | 1         | 0.57%   |
| Microsoft           | 1         | 0.57%   |
| LDLC                | 1         | 0.57%   |
| eMachines           | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 6         | 3.43%   |
| Intel H55                           | 3         | 1.71%   |
| Toshiba Satellite C55-B             | 2         | 1.14%   |
| MSI MS-7758                         | 2         | 1.14%   |
| MSI MS-7636                         | 2         | 1.14%   |
| Lenovo IdeaPad 300-15ISK 80Q7       | 2         | 1.14%   |
| Lenovo G560 20042                   | 2         | 1.14%   |
| Lenovo G50-30 80G0                  | 2         | 1.14%   |
| Lenovo B50-70 20384                 | 2         | 1.14%   |
| HP ProBook 4540s                    | 2         | 1.14%   |
| HP Pavilion 15                      | 2         | 1.14%   |
| HP 15                               | 2         | 1.14%   |
| Gigabyte B85M-DS3H-A                | 2         | 1.14%   |
| ECS H61H2-MV                        | 2         | 1.14%   |
| Dell Latitude E7440                 | 2         | 1.14%   |
| Dell Latitude E5430 vPro            | 2         | 1.14%   |
| Dell Inspiron N5110                 | 2         | 1.14%   |
| Dell Inspiron 3542                  | 2         | 1.14%   |
| Dell Inspiron 15-3567               | 2         | 1.14%   |
| Biostar P4M89-M7B                   | 2         | 1.14%   |
| Acer Aspire 5738                    | 2         | 1.14%   |
| WeiBu SIMM INT G-41D3 G1.0L         | 1         | 0.57%   |
| Toshiba Satellite C850-A979         | 1         | 0.57%   |
| Toshiba Satellite C50-A560          | 1         | 0.57%   |
| Toshiba Satellite C50-A545          | 1         | 0.57%   |
| Toshiba Satellite C50-A539          | 1         | 0.57%   |
| Toshiba PORTEGE R30-A               | 1         | 0.57%   |
| Toshiba PORTEGE M780                | 1         | 0.57%   |
| Sony VPCEJ2S1E                      | 1         | 0.57%   |
| Sony VPCEH2H1E                      | 1         | 0.57%   |
| Sony VGN-AW21M_H                    | 1         | 0.57%   |
| Sony SVF1531GSFB                    | 1         | 0.57%   |
| Sony SVE1713A6EW                    | 1         | 0.57%   |
| Sony SVE1513K1EW                    | 1         | 0.57%   |
| Samsung N102SP/N100SP/N101SP        | 1         | 0.57%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B | 1         | 0.57%   |
| Pegatron 2A94h                      | 1         | 0.57%   |
| Packard Bell EasyNote TJ75          | 1         | 0.57%   |
| Packard Bell EasyNote LJ71          | 1         | 0.57%   |
| Packard Bell DOT S                  | 1         | 0.57%   |
| MSI MS-7C52                         | 1         | 0.57%   |
| MSI MS-7788                         | 1         | 0.57%   |
| MSI MS-7752                         | 1         | 0.57%   |
| MSI MS-7693                         | 1         | 0.57%   |
| MSI MS-7637                         | 1         | 0.57%   |
| MSI MS-7592                         | 1         | 0.57%   |
| MSI CR610M                          | 1         | 0.57%   |
| Microsoft Surface Pro 3             | 1         | 0.57%   |
| Lenovo Yoga 910-13IKB 80VF          | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S1G104     | 1         | 0.57%   |
| Lenovo ThinkPad X201 3680AQ1        | 1         | 0.57%   |
| Lenovo ThinkPad T450 20BUS2RN1H     | 1         | 0.57%   |
| Lenovo ThinkPad T440 20B6S00200     | 1         | 0.57%   |
| Lenovo S510 10KW005NFM              | 1         | 0.57%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 1         | 0.57%   |
| Lenovo IdeaPad 310-15IKB 80TV       | 1         | 0.57%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 0.57%   |
| Lenovo G580 2189                    | 1         | 0.57%   |
| Lenovo G500 20236                   | 1         | 0.57%   |
| Lenovo 0B98417 PRO                  | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 12        | 6.86%   |
| Dell Latitude         | 10        | 5.71%   |
| Acer Aspire           | 9         | 5.14%   |
| HP ProBook            | 8         | 4.57%   |
| Toshiba Satellite     | 6         | 3.43%   |
| Unknown               | 6         | 3.43%   |
| Lenovo IdeaPad        | 5         | 2.86%   |
| Lenovo ThinkPad       | 4         | 2.29%   |
| Intel H55             | 3         | 1.71%   |
| HP Pavilion           | 3         | 1.71%   |
| HP EliteBook          | 3         | 1.71%   |
| Toshiba PORTEGE       | 2         | 1.14%   |
| Packard Bell EasyNote | 2         | 1.14%   |
| MSI MS-7758           | 2         | 1.14%   |
| MSI MS-7636           | 2         | 1.14%   |
| Lenovo G560           | 2         | 1.14%   |
| Lenovo G50-30         | 2         | 1.14%   |
| Lenovo B50-70         | 2         | 1.14%   |
| HP 15                 | 2         | 1.14%   |
| Gigabyte B85M-DS3H-A  | 2         | 1.14%   |
| Fujitsu LIFEBOOK      | 2         | 1.14%   |
| ECS H61H2-MV          | 2         | 1.14%   |
| Dell Vostro           | 2         | 1.14%   |
| Dell Precision        | 2         | 1.14%   |
| Dell OptiPlex         | 2         | 1.14%   |
| Biostar P4M89-M7B     | 2         | 1.14%   |
| Acer Extensa          | 2         | 1.14%   |
| WeiBu SIMM            | 1         | 0.57%   |
| Sony VPCEJ2S1E        | 1         | 0.57%   |
| Sony VPCEH2H1E        | 1         | 0.57%   |
| Sony VGN-AW21M        | 1         | 0.57%   |
| Sony SVF1531GSFB      | 1         | 0.57%   |
| Sony SVE1713A6EW      | 1         | 0.57%   |
| Sony SVE1513K1EW      | 1         | 0.57%   |
| Samsung N102SP        | 1         | 0.57%   |
| Samsung 700Z3A        | 1         | 0.57%   |
| Pegatron 2A94h        | 1         | 0.57%   |
| Packard Bell DOT      | 1         | 0.57%   |
| MSI MS-7C52           | 1         | 0.57%   |
| MSI MS-7788           | 1         | 0.57%   |
| MSI MS-7752           | 1         | 0.57%   |
| MSI MS-7693           | 1         | 0.57%   |
| MSI MS-7637           | 1         | 0.57%   |
| MSI MS-7592           | 1         | 0.57%   |
| MSI CR610M            | 1         | 0.57%   |
| Microsoft Surface     | 1         | 0.57%   |
| Lenovo Yoga           | 1         | 0.57%   |
| Lenovo S510           | 1         | 0.57%   |
| Lenovo G580           | 1         | 0.57%   |
| Lenovo G500           | 1         | 0.57%   |
| Lenovo 0B98417        | 1         | 0.57%   |
| LDLC Mercure          | 1         | 0.57%   |
| HP ZBook              | 1         | 0.57%   |
| HP Notebook           | 1         | 0.57%   |
| HP Laptop             | 1         | 0.57%   |
| HP ElitePad           | 1         | 0.57%   |
| HP Compaq             | 1         | 0.57%   |
| HP 630                | 1         | 0.57%   |
| HP 280                | 1         | 0.57%   |
| HP 250                | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 33        | 18.86%  |
| 2014 | 22        | 12.57%  |
| 2013 | 22        | 12.57%  |
| 2011 | 16        | 9.14%   |
| 2010 | 14        | 8%      |
| 2016 | 13        | 7.43%   |
| 2015 | 13        | 7.43%   |
| 2017 | 10        | 5.71%   |
| 2018 | 9         | 5.14%   |
| 2009 | 8         | 4.57%   |
| 2008 | 4         | 2.29%   |
| 2007 | 4         | 2.29%   |
| 2019 | 3         | 1.71%   |
| 2021 | 2         | 1.14%   |
| 2020 | 1         | 0.57%   |
| 2006 | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 110       | 62.86%  |
| Desktop     | 61        | 34.86%  |
| Tablet      | 2         | 1.14%   |
| Convertible | 1         | 0.57%   |
| All in one  | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 172       | 98.29%  |
| Enabled  | 3         | 1.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 67        | 37.85%  |
| 4.01-8.0    | 41        | 23.16%  |
| 8.01-16.0   | 33        | 18.64%  |
| 1.01-2.0    | 16        | 9.04%   |
| 16.01-24.0  | 8         | 4.52%   |
| 2.01-3.0    | 6         | 3.39%   |
| 32.01-64.0  | 3         | 1.69%   |
| 0.51-1.0    | 2         | 1.13%   |
| 64.01-256.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 94        | 48.96%  |
| 2.01-3.0  | 51        | 26.56%  |
| 3.01-4.0  | 17        | 8.85%   |
| 0.51-1.0  | 16        | 8.33%   |
| 4.01-8.0  | 11        | 5.73%   |
| 8.01-16.0 | 2         | 1.04%   |
| 0.01-0.5  | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 119       | 66.85%  |
| 2      | 46        | 25.84%  |
| 3      | 8         | 4.49%   |
| 4      | 3         | 1.69%   |
| 0      | 2         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 63.07%  |
| No        | 65        | 36.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 93.71%  |
| No        | 11        | 6.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 77.97%  |
| No        | 39        | 22.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 50.56%  |
| Yes       | 89        | 49.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 175       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Algiers         | 30        | 15.31%  |
| Tlemcen         | 9         | 4.59%   |
| Oran            | 9         | 4.59%   |
| Belcourt        | 9         | 4.59%   |
| Annaba          | 9         | 4.59%   |
| Sétif          | 6         | 3.06%   |
| Skikda          | 5         | 2.55%   |
| Blida           | 5         | 2.55%   |
| Biskra          | 5         | 2.55%   |
| Relizane        | 4         | 2.04%   |
| Cheraga         | 4         | 2.04%   |
| Birkhadem       | 4         | 2.04%   |
| Batna City      | 4         | 2.04%   |
| Tipasa          | 3         | 1.53%   |
| Mostaganem      | 3         | 1.53%   |
| Laghouat        | 3         | 1.53%   |
| Jijelli         | 3         | 1.53%   |
| Béjaïa        | 3         | 1.53%   |
| ash-Shalif      | 3         | 1.53%   |
| Tizi Ouzou      | 2         | 1.02%   |
| Sidi Akkacha    | 2         | 1.02%   |
| Saida           | 2         | 1.02%   |
| Ouenza          | 2         | 1.02%   |
| Kouba           | 2         | 1.02%   |
| Khenchela       | 2         | 1.02%   |
| Draria          | 2         | 1.02%   |
| Djelfa          | 2         | 1.02%   |
| Constantine     | 2         | 1.02%   |
| Bir el Djir     | 2         | 1.02%   |
| Ben ’Aknoûn  | 2         | 1.02%   |
| Bab Ezzouar     | 2         | 1.02%   |
| Ain Fakroun     | 2         | 1.02%   |
| Tolga           | 1         | 0.51%   |
| Tichi           | 1         | 0.51%   |
| Tazoult-Lambese | 1         | 0.51%   |
| Tadjenanet      | 1         | 0.51%   |
| Souma           | 1         | 0.51%   |
| Sig             | 1         | 0.51%   |
| Sidi Kada       | 1         | 0.51%   |
| Sidi Bel Abbes  | 1         | 0.51%   |
| Saoula          | 1         | 0.51%   |
| Reguiba         | 1         | 0.51%   |
| Oum el Bouaghi  | 1         | 0.51%   |
| Oued Smar       | 1         | 0.51%   |
| Ouargla         | 1         | 0.51%   |
| Mascara         | 1         | 0.51%   |
| M'Sila          | 1         | 0.51%   |
| Larbaâ         | 1         | 0.51%   |
| Khraicia        | 1         | 0.51%   |
| Hassi Bahbah    | 1         | 0.51%   |
| El Oued         | 1         | 0.51%   |
| El Khroub       | 1         | 0.51%   |
| El Eulma        | 1         | 0.51%   |
| El Aouinet      | 1         | 0.51%   |
| Dunqulah        | 1         | 0.51%   |
| Debila          | 1         | 0.51%   |
| Brezina         | 1         | 0.51%   |
| BouГЇra       | 1         | 0.51%   |
| Boumerdes       | 1         | 0.51%   |
| Bouïra         | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 49        | 72     | 22.07%  |
| Seagate                   | 36        | 46     | 16.22%  |
| Toshiba                   | 29        | 30     | 13.06%  |
| Samsung Electronics       | 22        | 24     | 9.91%   |
| Hitachi                   | 19        | 28     | 8.56%   |
| HGST                      | 13        | 17     | 5.86%   |
| A-DATA Technology         | 10        | 10     | 4.5%    |
| SanDisk                   | 5         | 5      | 2.25%   |
| Lexar                     | 5         | 5      | 2.25%   |
| Unknown                   | 4         | 5      | 1.8%    |
| Maxtor                    | 4         | 5      | 1.8%    |
| LITEON                    | 4         | 7      | 1.8%    |
| Realtek Semiconductor     | 3         | 3      | 1.35%   |
| XPG                       | 2         | 2      | 0.9%    |
| SK hynix                  | 2         | 2      | 0.9%    |
| Kingston                  | 2         | 2      | 0.9%    |
| Intel                     | 2         | 2      | 0.9%    |
| ZTE                       | 1         | 1      | 0.45%   |
| WD MediaMax               | 1         | 1      | 0.45%   |
| Team                      | 1         | 1      | 0.45%   |
| T-FORCE                   | 1         | 1      | 0.45%   |
| Silicon Motion            | 1         | 1      | 0.45%   |
| PNY                       | 1         | 1      | 0.45%   |
| Micron/Crucial Technology | 1         | 1      | 0.45%   |
| Micron Technology         | 1         | 2      | 0.45%   |
| HUAWEI                    | 1         | 1      | 0.45%   |
| Fujitsu                   | 1         | 2      | 0.45%   |
| Crucial                   | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB           | 8         | 3.4%    |
| WDC WD5000LPCX-24C6HT0 500GB       | 4         | 1.7%    |
| Toshiba MQ01ABD100 1TB             | 4         | 1.7%    |
| Seagate ST500LT012-1DG142 500GB    | 4         | 1.7%    |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 1.28%   |
| WDC WD10EZEX-00WN4A0 1TB           | 3         | 1.28%   |
| Toshiba DT01ACA100 1TB             | 3         | 1.28%   |
| Toshiba DT01ACA050 500GB           | 3         | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 1.28%   |
| Seagate Expansion 1TB              | 3         | 1.28%   |
| HGST HTS545050A7E680 500GB         | 3         | 1.28%   |
| HGST HTS545050A7E380 500GB         | 3         | 1.28%   |
| XPG SX950U 960GB                   | 2         | 0.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.85%   |
| WDC WD5000AVVS-63M8B0 500GB        | 2         | 0.85%   |
| Unknown MMC Card  64GB             | 2         | 0.85%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 0.85%   |
| Seagate ST3500312CS 500GB          | 2         | 0.85%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.85%   |
| Samsung NVMe SSD Drive 256GB       | 2         | 0.85%   |
| Lexar 512GB SSD                    | 2         | 0.85%   |
| Lexar 128GB SSD                    | 2         | 0.85%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 0.85%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 0.85%   |
| Hitachi HDS721616PLA380 160GB      | 2         | 0.85%   |
| HGST HTS725050A7E630 500GB         | 2         | 0.85%   |
| HGST HTS541010A9E680 1TB           | 2         | 0.85%   |
| A-DATA SU630 240GB SSD             | 2         | 0.85%   |
| ZTE MMC Storage 942MB              | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.43%   |
| WDC WDS100T2B0B-00YS70 1TB SSD     | 1         | 0.43%   |
| WDC WD800JD-55MUA1 80GB            | 1         | 0.43%   |
| WDC WD7500AYYS-01RCA0 752GB        | 1         | 0.43%   |
| WDC WD5000LUCT-62RC2Y0 500GB       | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.43%   |
| WDC WD5000LPVT-16G33T0 500GB       | 1         | 0.43%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.43%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.43%   |
| WDC WD5000LPCX-21VHAT0 500GB       | 1         | 0.43%   |
| WDC WD5000BPVT-75HXZT3 500GB       | 1         | 0.43%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 0.43%   |
| WDC WD5000AZLX-08K2TA0 500GB       | 1         | 0.43%   |
| WDC WD5000AVCS-632DY1 500GB        | 1         | 0.43%   |
| WDC WD5000AAKX-603CA0 500GB        | 1         | 0.43%   |
| WDC WD5000AAKX-083CA1 500GB        | 1         | 0.43%   |
| WDC WD5000AAKX-00U6AA0 500GB       | 1         | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 0.43%   |
| WDC WD5000AAKX-001CA0 500GB        | 1         | 0.43%   |
| WDC WD5000AAKS-00A7B0 500GB        | 1         | 0.43%   |
| WDC WD5000AADS-00S9B0 500GB        | 1         | 0.43%   |
| WDC WD400EB-00CPF0 40GB            | 1         | 0.43%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.43%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 0.43%   |
| WDC WD3200BEKT-75KA9T0 320GB       | 1         | 0.43%   |
| WDC WD3200AVJS-63B6A0 320GB        | 1         | 0.43%   |
| WDC WD3200AAKS-75L9A0 320GB        | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 66     | 29.38%  |
| Seagate             | 36        | 46     | 22.5%   |
| Toshiba             | 29        | 30     | 18.13%  |
| Hitachi             | 19        | 28     | 11.88%  |
| HGST                | 13        | 17     | 8.13%   |
| Samsung Electronics | 10        | 11     | 6.25%   |
| Maxtor              | 4         | 5      | 2.5%    |
| WD MediaMax         | 1         | 1      | 0.63%   |
| Fujitsu             | 1         | 2      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 7         | 7      | 18.42%  |
| Samsung Electronics | 5         | 5      | 13.16%  |
| WDC                 | 4         | 6      | 10.53%  |
| SanDisk             | 4         | 4      | 10.53%  |
| LITEON              | 4         | 7      | 10.53%  |
| Lexar               | 4         | 4      | 10.53%  |
| XPG                 | 2         | 2      | 5.26%   |
| Intel               | 2         | 2      | 5.26%   |
| Team                | 1         | 1      | 2.63%   |
| T-FORCE             | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| Kingston            | 1         | 1      | 2.63%   |
| Crucial             | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 144       | 206    | 71.64%  |
| SSD     | 35        | 43     | 17.41%  |
| NVMe    | 14        | 19     | 6.97%   |
| MMC     | 5         | 7      | 2.49%   |
| Unknown | 3         | 3      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 246    | 86.56%  |
| NVMe | 14        | 19     | 7.53%   |
| SAS  | 6         | 6      | 3.23%   |
| MMC  | 5         | 7      | 2.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 128       | 186    | 69.95%  |
| 0.51-1.0   | 50        | 58     | 27.32%  |
| 1.01-2.0   | 5         | 5      | 2.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 52        | 27.96%  |
| 101-250    | 30        | 16.13%  |
| 51-100     | 30        | 16.13%  |
| 1-20       | 22        | 11.83%  |
| 501-1000   | 22        | 11.83%  |
| 21-50      | 16        | 8.6%    |
| 1001-2000  | 10        | 5.38%   |
| Unknown    | 3         | 1.61%   |
| 2001-3000  | 1         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 95        | 49.48%  |
| 21-50     | 35        | 18.23%  |
| 101-250   | 23        | 11.98%  |
| 51-100    | 16        | 8.33%   |
| 251-500   | 12        | 6.25%   |
| 501-1000  | 6         | 3.13%   |
| Unknown   | 3         | 1.56%   |
| 1001-2000 | 2         | 1.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 3.33%   |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 3.33%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 3.33%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 3.33%   |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 3.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 3.33%   |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 3.33%   |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 3.33%   |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 3.33%   |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 3.33%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 3.33%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 3.33%   |
| Seagate ST500LT012-9WS142 500GB             | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 3.33%   |
| Seagate ST500LM021-1KJ152 500GB             | 1         | 1      | 3.33%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 3.33%   |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 3.33%   |
| Samsung Electronics HD502HI 500GB           | 1         | 1      | 3.33%   |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 3.33%   |
| Samsung Electronics HD160JJ/ 160GB          | 1         | 1      | 3.33%   |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 3.33%   |
| Maxtor 6L300S0 304GB                        | 1         | 1      | 3.33%   |
| Maxtor 32049H2 20GB                         | 1         | 1      | 3.33%   |
| Hitachi HTS723225L9A360 250GB               | 1         | 1      | 3.33%   |
| Hitachi HTS547564A9E384 640GB               | 1         | 1      | 3.33%   |
| Hitachi HTS542516K9SA00 160GB               | 1         | 1      | 3.33%   |
| Hitachi HDS721032CLA362 320GB               | 1         | 1      | 3.33%   |
| HGST HTS725050A7E630 500GB                  | 1         | 3      | 3.33%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 27.59%  |
| Samsung Electronics | 6         | 6      | 20.69%  |
| Seagate             | 4         | 4      | 13.79%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Toshiba             | 2         | 2      | 6.9%    |
| Maxtor              | 2         | 2      | 6.9%    |
| HGST                | 2         | 4      | 6.9%    |
| WD MediaMax         | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 28.57%  |
| Samsung Electronics | 5         | 5      | 17.86%  |
| Seagate             | 4         | 4      | 14.29%  |
| Hitachi             | 4         | 4      | 14.29%  |
| Toshiba             | 2         | 2      | 7.14%   |
| Maxtor              | 2         | 2      | 7.14%   |
| HGST                | 2         | 4      | 7.14%   |
| WD MediaMax         | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 31     | 96.43%  |
| SSD  | 1         | 1      | 3.57%   |

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
| Detected | 117       | 189    | 62.57%  |
| Works    | 42        | 57     | 22.46%  |
| Malfunc  | 28        | 32     | 14.97%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 151       | 79.47%  |
| AMD                         | 11        | 5.79%   |
| Samsung Electronics         | 6         | 3.16%   |
| Realtek Semiconductor       | 5         | 2.63%   |
| Nvidia                      | 4         | 2.11%   |
| VIA Technologies            | 3         | 1.58%   |
| Silicon Motion              | 2         | 1.05%   |
| JMicron Technology          | 2         | 1.05%   |
| ASMedia Technology          | 2         | 1.05%   |
| Micron/Crucial Technology   | 1         | 0.53%   |
| Micron Technology           | 1         | 0.53%   |
| Marvell Technology Group    | 1         | 0.53%   |
| Kingston Technology Company | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 21        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 6.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14        | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14        | 6.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 4.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 3.9%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 3.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 3.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.6%    |
| Realtek Realtek Non-Volatile memory controller                                          | 5         | 2.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.73%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.73%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 1.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.3%    |
| VIA Serial ATA Controller                                                               | 2         | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.87%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.87%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.87%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.87%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 2         | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.87%   |
| VIA VT8237/8251 Serial ATA Controller                                                   | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.43%   |
| Nvidia MCP89 SATA Controller                                                            | 1         | 0.43%   |
| Nvidia MCP79 SATA Controller                                                            | 1         | 0.43%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1         | 0.43%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1         | 0.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.43%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.43%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1         | 0.43%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.43%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.43%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.43%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 0.43%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 0.43%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.43%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 0.43%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.43%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.43%   |
| ASMedia ASM1061 SATA IDE Controller                                                     | 1         | 0.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 0.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 0.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 116       | 61.7%   |
| IDE  | 44        | 23.4%   |
| RAID | 14        | 7.45%   |
| NVMe | 14        | 7.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 162       | 92.57%  |
| AMD    | 13        | 7.43%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 3.43%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 5         | 2.86%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 4         | 2.29%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 2.29%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3         | 1.71%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 1.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.71%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 3         | 1.71%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 1.71%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.14%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.14%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2         | 1.14%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.14%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 1.14%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 2         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.14%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.14%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.14%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.14%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1.14%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 1.14%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.14%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 1.14%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 1.14%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.14%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.14%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 1.14%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.14%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.14%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.14%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2         | 1.14%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.14%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2         | 1.14%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.57%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1         | 0.57%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.57%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.57%   |
| Intel Pentium CPU G850 @ 2.90GHz            | 1         | 0.57%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1         | 0.57%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.57%   |
| Intel Pentium CPU G2010 @ 2.80GHz           | 1         | 0.57%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.57%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.57%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1         | 0.57%   |
| Intel Pentium 3805U @ 1.90GHz               | 1         | 0.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i3           | 50        | 28.57%  |
| Intel Core i5           | 37        | 21.14%  |
| Intel Core i7           | 23        | 13.14%  |
| Intel Pentium           | 14        | 8%      |
| Intel Pentium Dual-Core | 11        | 6.29%   |
| Intel Core 2 Duo        | 9         | 5.14%   |
| Intel Celeron           | 5         | 2.86%   |
| Intel Atom              | 5         | 2.86%   |
| Intel Pentium Dual      | 3         | 1.71%   |
| AMD Ryzen 7             | 3         | 1.71%   |
| Other                   | 1         | 0.57%   |
| Intel Xeon              | 1         | 0.57%   |
| Intel Pentium D         | 1         | 0.57%   |
| Intel Pentium 4         | 1         | 0.57%   |
| Intel Core 2 Quad       | 1         | 0.57%   |
| AMD Ryzen 9             | 1         | 0.57%   |
| AMD Ryzen 5 PRO         | 1         | 0.57%   |
| AMD Ryzen 5             | 1         | 0.57%   |
| AMD Ryzen 3             | 1         | 0.57%   |
| AMD FX                  | 1         | 0.57%   |
| AMD E2                  | 1         | 0.57%   |
| AMD E1                  | 1         | 0.57%   |
| AMD Athlon II Dual-Core | 1         | 0.57%   |
| AMD Athlon 64           | 1         | 0.57%   |
| AMD A4                  | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 135       | 77.14%  |
| 4      | 28        | 16%     |
| 1      | 4         | 2.29%   |
| 8      | 3         | 1.71%   |
| 6      | 3         | 1.71%   |
| 16     | 1         | 0.57%   |
| 3      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 175       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 118       | 67.43%  |
| 1      | 57        | 32.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 173       | 98.3%   |
| Unknown        | 3         | 1.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 29        | 15.93%  |
| Unknown    | 29        | 15.93%  |
| 0x206a7    | 17        | 9.34%   |
| 0x20655    | 15        | 8.24%   |
| 0x1067a    | 15        | 8.24%   |
| 0x40651    | 10        | 5.49%   |
| 0x406e3    | 8         | 4.4%    |
| 0x30678    | 7         | 3.85%   |
| 0x306d4    | 6         | 3.3%    |
| 0x806e9    | 5         | 2.75%   |
| 0x306c3    | 5         | 2.75%   |
| 0x806ea    | 4         | 2.2%    |
| 0x6fd      | 3         | 1.65%   |
| 0x20652    | 3         | 1.65%   |
| 0x906e9    | 2         | 1.1%    |
| 0x30661    | 2         | 1.1%    |
| 0x0800820d | 2         | 1.1%    |
| 0xf65      | 1         | 0.55%   |
| 0x906eb    | 1         | 0.55%   |
| 0x806ec    | 1         | 0.55%   |
| 0x806c1    | 1         | 0.55%   |
| 0x6fb      | 1         | 0.55%   |
| 0x506e3    | 1         | 0.55%   |
| 0x506c9    | 1         | 0.55%   |
| 0x406c4    | 1         | 0.55%   |
| 0x406c3    | 1         | 0.55%   |
| 0x306e4    | 1         | 0.55%   |
| 0x10676    | 1         | 0.55%   |
| 0x0a201016 | 1         | 0.55%   |
| 0x08701021 | 1         | 0.55%   |
| 0x08608103 | 1         | 0.55%   |
| 0x08600106 | 1         | 0.55%   |
| 0x0810100b | 1         | 0.55%   |
| 0x0700010f | 1         | 0.55%   |
| 0x06006705 | 1         | 0.55%   |
| 0x0600063d | 1         | 0.55%   |
| 0x05000119 | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 33        | 18.86%  |
| SandyBridge | 21        | 12%     |
| Penryn      | 19        | 10.86%  |
| Haswell     | 19        | 10.86%  |
| Westmere    | 18        | 10.29%  |
| KabyLake    | 14        | 8%      |
| Skylake     | 11        | 6.29%   |
| Silvermont  | 10        | 5.71%   |
| Broadwell   | 6         | 3.43%   |
| Core        | 5         | 2.86%   |
| Zen+        | 2         | 1.14%   |
| Zen 2       | 2         | 1.14%   |
| NetBurst    | 2         | 1.14%   |
| Bonnell     | 2         | 1.14%   |
| Zen 3       | 1         | 0.57%   |
| Zen         | 1         | 0.57%   |
| TigerLake   | 1         | 0.57%   |
| K8 Hammer   | 1         | 0.57%   |
| K10         | 1         | 0.57%   |
| Jaguar      | 1         | 0.57%   |
| Goldmont    | 1         | 0.57%   |
| Excavator   | 1         | 0.57%   |
| Bulldozer   | 1         | 0.57%   |
| Bobcat      | 1         | 0.57%   |
| Unknown     | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 127       | 60.19%  |
| Nvidia           | 41        | 19.43%  |
| AMD              | 41        | 19.43%  |
| VIA Technologies | 2         | 0.95%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 9%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 5.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 5.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 4.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 3.79%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8         | 3.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 3.32%   |
| Intel HD Graphics 620                                                                    | 6         | 2.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 2.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.37%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.37%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.42%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.42%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.95%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.95%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.95%   |
| Intel HD Graphics 630                                                                    | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.95%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.95%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.95%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.95%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.95%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.95%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.95%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.47%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.47%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.47%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.47%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.47%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.47%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.47%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.47%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.47%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.47%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.47%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.47%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.47%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.47%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.47%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.47%   |
| Nvidia GK104GLM [Quadro K4000M]                                                          | 1         | 0.47%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.47%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.47%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.47%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.47%   |
| Nvidia GF108M [GeForce GT 620M]                                                          | 1         | 0.47%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1         | 0.47%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1         | 0.47%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.47%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1         | 0.47%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.47%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 0.47%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 0.47%   |
| Nvidia C77 [GeForce 8200]                                                                | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 94        | 53.11%  |
| 1 x Nvidia     | 24        | 13.56%  |
| 1 x AMD        | 24        | 13.56%  |
| Intel + Nvidia | 16        | 9.04%   |
| Intel + AMD    | 16        | 9.04%   |
| 1 x VIA        | 2         | 1.13%   |
| AMD + Nvidia   | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 152       | 84.92%  |
| Proprietary | 20        | 11.17%  |
| Unknown     | 7         | 3.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 58.1%   |
| 1.01-2.0   | 40        | 22.35%  |
| 0.51-1.0   | 14        | 7.82%   |
| 0.01-0.5   | 13        | 7.26%   |
| 3.01-4.0   | 6         | 3.35%   |
| 7.01-8.0   | 2         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 37        | 22.02%  |
| LG Display              | 23        | 13.69%  |
| AU Optronics            | 21        | 12.5%   |
| Chimei Innolux          | 13        | 7.74%   |
| BOE                     | 13        | 7.74%   |
| Hewlett-Packard         | 9         | 5.36%   |
| AOC                     | 8         | 4.76%   |
| Chi Mei Optoelectronics | 7         | 4.17%   |
| KTC                     | 4         | 2.38%   |
| Acer                    | 4         | 2.38%   |
| BenQ                    | 3         | 1.79%   |
| Ancor Communications    | 3         | 1.79%   |
| Lenovo                  | 2         | 1.19%   |
| Goldstar                | 2         | 1.19%   |
| Dell                    | 2         | 1.19%   |
| Apple                   | 2         | 1.19%   |
| Unknown                 | 2         | 1.19%   |
| ___                     | 1         | 0.6%    |
| Unknown (XXX)           | 1         | 0.6%    |
| Unknown                 | 1         | 0.6%    |
| TSN                     | 1         | 0.6%    |
| SKY                     | 1         | 0.6%    |
| Sharp                   | 1         | 0.6%    |
| PTW                     | 1         | 0.6%    |
| PiLot                   | 1         | 0.6%    |
| PANDA                   | 1         | 0.6%    |
| MStar                   | 1         | 0.6%    |
| LGD                     | 1         | 0.6%    |
| InnoLux Display         | 1         | 0.6%    |
| EMP                     | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 1.76%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 1.76%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.76%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.76%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 3         | 1.76%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 1.18%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 1.18%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 2         | 1.18%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 1.18%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 2         | 1.18%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 1.18%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 1.18%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 1.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.18%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 1.18%   |
| Unknown                                                                  | 2         | 1.18%   |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.59%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.59%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 1         | 0.59%   |
| TSN 24 Monitor TSN2400 1360x768 510x287mm 23.0-inch                      | 1         | 0.59%   |
| SKY TV-PHILCO SKY0104 1920x1080 885x498mm 40.0-inch                      | 1         | 0.59%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM04D5 1920x540                          | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch     | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM00A6 1280x1024 380x310mm 19.3-inch     | 1         | 0.59%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch        | 1         | 0.59%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch       | 1         | 0.59%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch       | 1         | 0.59%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch        | 1         | 0.59%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch        | 1         | 0.59%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch        | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC494A 1366x768 344x193mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch    | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3442 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 370x230mm 17.2-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3241 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch    | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SA300/SA350 1600x900                     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor S22E390 1920x1080                        | 1         | 0.59%   |
| Samsung Electronics C24B550 SAM0956 1920x1080 531x299mm 24.0-inch        | 1         | 0.59%   |
| PTW 22GM55L PTW0866 1920x1080 477x268mm 21.5-inch                        | 1         | 0.59%   |
| PiLot monitor PLT1850 1366x768 368x207mm 16.6-inch                       | 1         | 0.59%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 0.59%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 0.59%   |
| LGD LCD Monitor 1600x900                                                 | 1         | 0.59%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch             | 1         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 82        | 50.31%  |
| 1920x1080 (FHD)    | 44        | 26.99%  |
| 1600x900 (HD+)     | 8         | 4.91%   |
| 1440x900 (WXGA+)   | 6         | 3.68%   |
| 1280x1024 (SXGA)   | 4         | 2.45%   |
| 2560x1440 (QHD)    | 3         | 1.84%   |
| 1360x768           | 3         | 1.84%   |
| 1280x800 (WXGA)    | 3         | 1.84%   |
| 3840x2160 (4K)     | 2         | 1.23%   |
| 1680x1050 (WSXGA+) | 2         | 1.23%   |
| 2160x1440          | 1         | 0.61%   |
| 1920x540           | 1         | 0.61%   |
| 1920x1200 (WUXGA)  | 1         | 0.61%   |
| 1680x945           | 1         | 0.61%   |
| 1600x1200          | 1         | 0.61%   |
| 1024x600           | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 74        | 43.79%  |
| 21      | 12        | 7.1%    |
| 18      | 12        | 7.1%    |
| 13      | 10        | 5.92%   |
| 17      | 8         | 4.73%   |
| 14      | 7         | 4.14%   |
| 23      | 6         | 3.55%   |
| 19      | 6         | 3.55%   |
| Unknown | 6         | 3.55%   |
| 12      | 5         | 2.96%   |
| 27      | 4         | 2.37%   |
| 24      | 4         | 2.37%   |
| 52      | 2         | 1.18%   |
| 22      | 2         | 1.18%   |
| 20      | 2         | 1.18%   |
| 10      | 2         | 1.18%   |
| 46      | 1         | 0.59%   |
| 40      | 1         | 0.59%   |
| 37      | 1         | 0.59%   |
| 32      | 1         | 0.59%   |
| 31      | 1         | 0.59%   |
| 16      | 1         | 0.59%   |
| 11      | 1         | 0.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 89        | 53.29%  |
| 401-500     | 29        | 17.37%  |
| 501-600     | 14        | 8.38%   |
| 351-400     | 12        | 7.19%   |
| 201-300     | 10        | 5.99%   |
| Unknown     | 6         | 3.59%   |
| 1001-1500   | 3         | 1.8%    |
| 801-900     | 2         | 1.2%    |
| 701-800     | 1         | 0.6%    |
| 601-700     | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 137       | 85.09%  |
| 16/10   | 11        | 6.83%   |
| Unknown | 5         | 3.11%   |
| 5/4     | 4         | 2.48%   |
| 6/5     | 1         | 0.62%   |
| 4/3     | 1         | 0.62%   |
| 32/9    | 1         | 0.62%   |
| 3/2     | 1         | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 73        | 43.45%  |
| 201-250        | 17        | 10.12%  |
| 81-90          | 15        | 8.93%   |
| 151-200        | 15        | 8.93%   |
| 141-150        | 13        | 7.74%   |
| Unknown        | 6         | 3.57%   |
| 61-70          | 5         | 2.98%   |
| 301-350        | 4         | 2.38%   |
| 121-130        | 4         | 2.38%   |
| 501-1000       | 3         | 1.79%   |
| More than 1000 | 2         | 1.19%   |
| 71-80          | 2         | 1.19%   |
| 351-500        | 2         | 1.19%   |
| 41-50          | 2         | 1.19%   |
| 131-140        | 2         | 1.19%   |
| 111-120        | 2         | 1.19%   |
| 51-60          | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 83        | 49.7%   |
| 51-100  | 47        | 28.14%  |
| 121-160 | 23        | 13.77%  |
| Unknown | 6         | 3.59%   |
| 1-50    | 4         | 2.4%    |
| 161-240 | 4         | 2.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 159       | 89.33%  |
| 2     | 11        | 6.18%   |
| 0     | 8         | 4.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 109       | 37.72%  |
| Qualcomm Atheros                | 50        | 17.3%   |
| Intel                           | 43        | 14.88%  |
| Broadcom                        | 29        | 10.03%  |
| Ralink Technology               | 16        | 5.54%   |
| Ralink                          | 10        | 3.46%   |
| VIA Technologies                | 3         | 1.04%   |
| Samsung Electronics             | 3         | 1.04%   |
| Qualcomm Atheros Communications | 3         | 1.04%   |
| Nvidia                          | 3         | 1.04%   |
| MediaTek                        | 3         | 1.04%   |
| D-Link System                   | 3         | 1.04%   |
| Xiaomi                          | 2         | 0.69%   |
| Marvell Technology Group        | 2         | 0.69%   |
| Huawei Technologies             | 2         | 0.69%   |
| Broadcom Limited                | 2         | 0.69%   |
| TP-Link                         | 1         | 0.35%   |
| Sierra Wireless                 | 1         | 0.35%   |
| LG Electronics                  | 1         | 0.35%   |
| Hewlett-Packard                 | 1         | 0.35%   |
| D-Link                          | 1         | 0.35%   |
| AMD                             | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 64        | 19.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 42        | 12.77%  |
| Broadcom BCM43142 802.11b/g/n                                        | 12        | 3.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 11        | 3.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 3.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 2.13%   |
| Ralink MT7601U Wireless Adapter                                      | 6         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 6         | 1.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1.22%   |
| Ralink RT5370 Wireless Adapter                                       | 4         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 1.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 4         | 1.22%   |
| Intel Wireless 8265 / 8275                                           | 4         | 1.22%   |
| Intel Wireless 8260                                                  | 4         | 1.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 4         | 1.22%   |
| VIA VT6102/VT6103 [Rhine-II]                                         | 3         | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                      | 3         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 3         | 0.91%   |
| Intel Wireless 7260                                                  | 3         | 0.91%   |
| Intel Wireless 3160                                                  | 3         | 0.91%   |
| Intel Ethernet Connection I219-LM                                    | 3         | 0.91%   |
| Intel Ethernet Connection I218-LM                                    | 3         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                                | 3         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 2         | 0.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2         | 0.61%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 0.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 2         | 0.61%   |
| MediaTek moto e(6) plus                                              | 2         | 0.61%   |
| Intel Wireless 7265                                                  | 2         | 0.61%   |
| Intel WiFi Link 5100                                                 | 2         | 0.61%   |
| Intel I211 Gigabit Network Connection                                | 2         | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 0.61%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 0.61%   |
| Intel Centrino Wireless-N 135                                        | 2         | 0.61%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 0.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 0.61%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                             | 2         | 0.61%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2         | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 2         | 0.61%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 2         | 0.61%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 0.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.3%    |
| Sierra Wireless EM7305                                               | 1         | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.3%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.3%    |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.3%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.3%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.3%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)            | 1         | 0.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.3%    |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 41        | 26.8%   |
| Intel                           | 37        | 24.18%  |
| Broadcom                        | 21        | 13.73%  |
| Ralink Technology               | 16        | 10.46%  |
| Realtek Semiconductor           | 15        | 9.8%    |
| Ralink                          | 10        | 6.54%   |
| Qualcomm Atheros Communications | 3         | 1.96%   |
| D-Link System                   | 3         | 1.96%   |
| TP-Link                         | 1         | 0.65%   |
| Sierra Wireless                 | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| Marvell Technology Group        | 1         | 0.65%   |
| Hewlett-Packard                 | 1         | 0.65%   |
| D-Link                          | 1         | 0.65%   |
| Broadcom Limited                | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                        | 12        | 7.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 11        | 7.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 6.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 4.58%   |
| Ralink MT7601U Wireless Adapter                                      | 6         | 3.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 3.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 3.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 2.61%   |
| Ralink RT5370 Wireless Adapter                                       | 4         | 2.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 2.61%   |
| Intel Wireless 8265 / 8275                                           | 4         | 2.61%   |
| Intel Wireless 8260                                                  | 4         | 2.61%   |
| Qualcomm Atheros AR9271 802.11n                                      | 3         | 1.96%   |
| Intel Wireless 7260                                                  | 3         | 1.96%   |
| Intel Wireless 3160                                                  | 3         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 3         | 1.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2         | 1.31%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2         | 1.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.31%   |
| Intel Wireless 7265                                                  | 2         | 1.31%   |
| Intel WiFi Link 5100                                                 | 2         | 1.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 1.31%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.31%   |
| Intel Centrino Wireless-N 135                                        | 2         | 1.31%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.31%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.31%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2         | 1.31%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 1.31%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.65%   |
| Sierra Wireless EM7305                                               | 1         | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.65%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.65%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.65%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)            | 1         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.65%   |
| Ralink RT2070 Wireless Adapter                                       | 1         | 0.65%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.65%   |
| Ralink RT2600 802.11 MIMO                                            | 1         | 0.65%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 0.65%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter           | 1         | 0.65%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]  | 1         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1         | 0.65%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 1         | 0.65%   |
| Intel Wireless 3165                                                  | 1         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 0.65%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 0.65%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                 | 1         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 0.65%   |
| HP lt4112 Gobi 4G Module Network Device                              | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 60.92%  |
| Intel                    | 27        | 15.52%  |
| Qualcomm Atheros         | 12        | 6.9%    |
| Broadcom                 | 11        | 6.32%   |
| VIA Technologies         | 3         | 1.72%   |
| Samsung Electronics      | 3         | 1.72%   |
| Nvidia                   | 3         | 1.72%   |
| Xiaomi                   | 2         | 1.15%   |
| MediaTek                 | 2         | 1.15%   |
| Marvell Technology Group | 1         | 0.57%   |
| LG Electronics           | 1         | 0.57%   |
| Huawei Technologies      | 1         | 0.57%   |
| Broadcom Limited         | 1         | 0.57%   |
| AMD                      | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 36.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 24%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 2.29%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 2.29%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.71%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.71%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.14%   |
| MediaTek moto e(6) plus                                           | 2         | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.14%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.14%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.57%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.57%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.57%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.57%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.57%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.57%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.57%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.57%   |
| Huawei E353/E3131                                                 | 1         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.57%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1         | 0.57%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.57%   |
| AMD 79c970 [PCnet32 LANCE]                                        | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 164       | 54.13%  |
| WiFi     | 138       | 45.54%  |
| Modem    | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 65.32%  |
| Ethernet | 60        | 34.68%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 64.25%  |
| 1     | 61        | 34.08%  |
| 0     | 3         | 1.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 25.84%  |
| Qualcomm Atheros Communications | 12        | 13.48%  |
| Broadcom                        | 10        | 11.24%  |
| Realtek Semiconductor           | 7         | 7.87%   |
| Lite-On Technology              | 5         | 5.62%   |
| Foxconn / Hon Hai               | 5         | 5.62%   |
| Ralink                          | 4         | 4.49%   |
| IMC Networks                    | 4         | 4.49%   |
| Dell                            | 4         | 4.49%   |
| Cambridge Silicon Radio         | 4         | 4.49%   |
| Foxconn International           | 3         | 3.37%   |
| Apple                           | 2         | 2.25%   |
| Toshiba                         | 1         | 1.12%   |
| Ralink Technology               | 1         | 1.12%   |
| Marvell Semiconductor           | 1         | 1.12%   |
| Integrated System Solution      | 1         | 1.12%   |
| Chicony Electronics             | 1         | 1.12%   |
| Alps Electric                   | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 16        | 17.98%  |
| Qualcomm Atheros  Bluetooth Device                    | 6         | 6.74%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 5.62%   |
| Ralink RT3290 Bluetooth                               | 4         | 4.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 4.49%   |
| Realtek Bluetooth Radio                               | 3         | 3.37%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3         | 3.37%   |
| IMC Networks Bluetooth Device                         | 3         | 3.37%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 3.37%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 3         | 3.37%   |
| Realtek RTL8723B Bluetooth                            | 2         | 2.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 2         | 2.25%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 2.25%   |
| Dell Wireless 365 Bluetooth                           | 2         | 2.25%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 2.25%   |
| Apple Bluetooth Host Controller                       | 2         | 2.25%   |
| Toshiba Bluetooth Device                              | 1         | 1.12%   |
| Realtek RTL8821A Bluetooth                            | 1         | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.12%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 1.12%   |
| Qualcomm Atheros Bluetooth                            | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 1.12%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 1.12%   |
| Lite-On Wireless_Device                               | 1         | 1.12%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 1.12%   |
| Lite-On BCM43142A0                                    | 1         | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 1.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1         | 1.12%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.12%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 1.12%   |
| Foxconn / Hon Hai BCM43142A0                          | 1         | 1.12%   |
| Foxconn / Hon Hai Acer Module                         | 1         | 1.12%   |
| Dell DW375 Bluetooth Module                           | 1         | 1.12%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 1.12%   |
| Chicony Bluetooth (RTL8723BE)                         | 1         | 1.12%   |
| Broadcom HP Portable Bumble Bee                       | 1         | 1.12%   |
| Broadcom Bluetooth Device                             | 1         | 1.12%   |
| Broadcom BCM92045B3 ROM                               | 1         | 1.12%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 1         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 1.12%   |
| Alps Electric BCM2046 Bluetooth Device                | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 153       | 69.55%  |
| AMD                   | 33        | 15%     |
| Nvidia                | 25        | 11.36%  |
| VIA Technologies      | 3         | 1.36%   |
| JMTek                 | 2         | 0.91%   |
| Texas Instruments     | 1         | 0.45%   |
| Logitech              | 1         | 0.45%   |
| Logic3 / SpectraVideo | 1         | 0.45%   |
| Guillemot             | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 11.51%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 9.92%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 7.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 7.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 5.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.76%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 4.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 10        | 3.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.98%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.59%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.19%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.79%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.79%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.79%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.79%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 2         | 0.79%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.4%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.4%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.4%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.4%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.4%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.4%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.4%    |
| Logic3 / SpectraVideo USB Audio Device                                                            | 1         | 0.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.4%    |
| Guillemot Hercules Blog Webcam                                                                    | 1         | 0.4%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.4%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.4%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 26        | 24.07%  |
| Samsung Electronics | 22        | 20.37%  |
| SK hynix            | 20        | 18.52%  |
| Micron Technology   | 13        | 12.04%  |
| A-DATA Technology   | 8         | 7.41%   |
| Kingston            | 6         | 5.56%   |
| TwinMOS             | 2         | 1.85%   |
| Nanya Technology    | 2         | 1.85%   |
| Thermaltake         | 1         | 0.93%   |
| Team                | 1         | 0.93%   |
| Ramaxel Technology  | 1         | 0.93%   |
| Patriot             | 1         | 0.93%   |
| GeIL                | 1         | 0.93%   |
| Elpida              | 1         | 0.93%   |
| Dynet               | 1         | 0.93%   |
| Crucial             | 1         | 0.93%   |
| ASint Technology    | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 3.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 3         | 2.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 2.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 2.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s              | 2         | 1.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 2         | 1.67%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 2         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s    | 2         | 1.67%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.83%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR2                          | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                   | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR2                       | 1         | 0.83%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1333MT/s               | 1         | 0.83%   |
| Unknown RAM Module 4096MB DIMM SDRAM                        | 1         | 0.83%   |
| Unknown RAM Module 4096MB DIMM DDR3 800MT/s                 | 1         | 0.83%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM 667MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s               | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM DDR2                         | 1         | 0.83%   |
| Unknown RAM Module 1GB DIMM 800MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 1GB DIMM 533MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s                 | 1         | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR2 200MT/s                 | 1         | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR2                         | 1         | 0.83%   |
| TwinMOS RAM 9DPCBNZB-TATP 4GB DIMM DDR3 1333MT/s            | 1         | 0.83%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s            | 1         | 0.83%   |
| Thermaltake RAM R019D408GX2-3200C16A 8GB DIMM DDR4 2666MT/s | 1         | 0.83%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 0.83%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s            | 1         | 0.83%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 1         | 0.83%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s   | 1         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s   | 1         | 0.83%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 0.83%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 0.83%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 1         | 0.83%   |
| SK hynix RAM HMA425S6BJR6N-UH 2GB SODIMM DDR4 2667MT/s      | 1         | 0.83%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s              | 1         | 0.83%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.83%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 52        | 59.09%  |
| DDR4    | 19        | 21.59%  |
| SDRAM   | 6         | 6.82%   |
| DDR2    | 5         | 5.68%   |
| Unknown | 4         | 4.55%   |
| LPDDR4  | 1         | 1.14%   |
| DDR     | 1         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 53        | 61.63%  |
| DIMM   | 33        | 38.37%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 47        | 46.53%  |
| 2048  | 25        | 24.75%  |
| 8192  | 17        | 16.83%  |
| 1024  | 5         | 4.95%   |
| 16384 | 4         | 3.96%   |
| 32768 | 2         | 1.98%   |
| 512   | 1         | 0.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 31.96%  |
| 1333    | 16        | 16.49%  |
| 2667    | 9         | 9.28%   |
| Unknown | 6         | 6.19%   |
| 1334    | 5         | 5.15%   |
| 800     | 5         | 5.15%   |
| 3200    | 3         | 3.09%   |
| 2400    | 3         | 3.09%   |
| 3266    | 2         | 2.06%   |
| 2666    | 2         | 2.06%   |
| 2133    | 2         | 2.06%   |
| 1067    | 2         | 2.06%   |
| 667     | 2         | 2.06%   |
| 4199    | 1         | 1.03%   |
| 3800    | 1         | 1.03%   |
| 3400    | 1         | 1.03%   |
| 3066    | 1         | 1.03%   |
| 2200    | 1         | 1.03%   |
| 1639    | 1         | 1.03%   |
| 533     | 1         | 1.03%   |
| 266     | 1         | 1.03%   |
| 200     | 1         | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 6         | 54.55%  |
| Seiko Epson        | 3         | 27.27%  |
| Hewlett-Packard    | 1         | 9.09%   |
| Brother Industries | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6000                     | 2         | 18.18%  |
| Seiko Epson XP-243 245 247 Series | 1         | 9.09%   |
| Seiko Epson XP-202 203 206 Series | 1         | 9.09%   |
| Seiko Epson Printer               | 1         | 9.09%   |
| HP DeskJet 5810 series            | 1         | 9.09%   |
| Canon MG5700 series               | 1         | 9.09%   |
| Canon LBP6030/6030B/6018L         | 1         | 9.09%   |
| Canon LBP6020                     | 1         | 9.09%   |
| Canon LBP2900                     | 1         | 9.09%   |
| Brother MFC-J480DW                | 1         | 9.09%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 24.04%  |
| Microdia                               | 15        | 14.42%  |
| Realtek Semiconductor                  | 9         | 8.65%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 8.65%   |
| Acer                                   | 8         | 7.69%   |
| Sunplus Innovation Technology          | 7         | 6.73%   |
| Suyin                                  | 5         | 4.81%   |
| Syntek                                 | 4         | 3.85%   |
| IMC Networks                           | 3         | 2.88%   |
| Apple                                  | 3         | 2.88%   |
| Silicon Motion                         | 2         | 1.92%   |
| Samsung Electronics                    | 2         | 1.92%   |
| Quanta                                 | 2         | 1.92%   |
| Lite-On Technology                     | 2         | 1.92%   |
| Primax Electronics                     | 1         | 0.96%   |
| Pixart Imaging                         | 1         | 0.96%   |
| Microsoft                              | 1         | 0.96%   |
| GEMBIRD                                | 1         | 0.96%   |
| Aveo Technology                        | 1         | 0.96%   |
| Arkmicro Technologies                  | 1         | 0.96%   |
| ALi                                    | 1         | 0.96%   |
| Alcor Micro                            | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Acer Lenovo EasyCamera                                                | 6         | 5.71%   |
| Chicony TOSHIBA Web Camera - HD                                       | 4         | 3.81%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                | 3         | 2.86%   |
| Microdia Integrated_Webcam_HD                                         | 3         | 2.86%   |
| Microdia Integrated Webcam                                            | 3         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                   | 3         | 2.86%   |
| Syntek Lenovo EasyCamera                                              | 2         | 1.9%    |
| Suyin HP Truevision HD                                                | 2         | 1.9%    |
| Sunplus Laptop_Integrated_Webcam_FHD                                  | 2         | 1.9%    |
| Sunplus Integrated_Webcam_HD                                          | 2         | 1.9%    |
| Samsung Galaxy A5 (MTP)                                               | 2         | 1.9%    |
| Chicony USB2.0 VGA UVC WebCam                                         | 2         | 1.9%    |
| Chicony Integrated Camera                                             | 2         | 1.9%    |
| Chicony HD WebCam                                                     | 2         | 1.9%    |
| Chicony Acer CrystalEye Webcam                                        | 2         | 1.9%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                         | 2         | 1.9%    |
| Apple iPhone 5/5C/5S/6/SE                                             | 2         | 1.9%    |
| Syntek USB2.0 Camera                                                  | 1         | 0.95%   |
| Syntek EasyCamera                                                     | 1         | 0.95%   |
| Suyin WebCam                                                          | 1         | 0.95%   |
| Suyin Integrated_Webcam_HD                                            | 1         | 0.95%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                              | 1         | 0.95%   |
| Sunplus Laptop Integrated Webcam HD                                   | 1         | 0.95%   |
| Sunplus HP HD Webcam [Fixed]                                          | 1         | 0.95%   |
| Sunplus Dell HD Webcam                                                | 1         | 0.95%   |
| Silicon Motion WebCam SC-13HDL11431N                                  | 1         | 0.95%   |
| Silicon Motion WebCam SC-0311139N                                     | 1         | 0.95%   |
| Realtek USB2.0 VGA UVC WebCam                                         | 1         | 0.95%   |
| Realtek USB Camera                                                    | 1         | 0.95%   |
| Realtek Lenovo EasyCamera                                             | 1         | 0.95%   |
| Realtek Integrated Webcam_HD                                          | 1         | 0.95%   |
| Realtek Integrated Webcam                                             | 1         | 0.95%   |
| Realtek HP Webcam                                                     | 1         | 0.95%   |
| Realtek HP Truevision HD                                              | 1         | 0.95%   |
| Realtek HD Webcam - Realtek                                           | 1         | 0.95%   |
| Realtek Acer 640 x 480 laptop camera                                  | 1         | 0.95%   |
| Quanta HD Webcam                                                      | 1         | 0.95%   |
| Quanta HD User Facing                                                 | 1         | 0.95%   |
| Primax webcam                                                         | 1         | 0.95%   |
| Pixart Imaging VGA Webcam                                             | 1         | 0.95%   |
| Microsoft LifeCam Rear                                                | 1         | 0.95%   |
| Microsoft LifeCam Front                                               | 1         | 0.95%   |
| Microdia Sony Visual Communication Camera                             | 1         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_HD                                  | 1         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_2M                                  | 1         | 0.95%   |
| Microdia Integrated Webcam HD                                         | 1         | 0.95%   |
| Microdia 1.3 MPixel Integrated Webcam                                 | 1         | 0.95%   |
| Lite-On TOSHIBA Web Camera - HD                                       | 1         | 0.95%   |
| Lite-On Integrated Camera                                             | 1         | 0.95%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 0.95%   |
| IMC Networks Lenovo EasyCamera                                        | 1         | 0.95%   |
| IMC Networks Integrated Webcam                                        | 1         | 0.95%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                     | 1         | 0.95%   |
| Chicony WebCam                                                        | 1         | 0.95%   |
| Chicony UVC 1.00 device HD UVC WebCam                                 | 1         | 0.95%   |
| Chicony USB2.0 HD UVC WebCam                                          | 1         | 0.95%   |
| Chicony Sony Visual Communication Camera                              | 1         | 0.95%   |
| Chicony Lenovo EasyCamera                                             | 1         | 0.95%   |
| Chicony HP Webcam                                                     | 1         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 10        | 71.43%  |
| AuthenTec             | 2         | 14.29%  |
| Synaptics             | 1         | 7.14%   |
| Elan Microelectronics | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 28.57%  |
| Validity Sensors VFS491                                    | 2         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                            | 1         | 7.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                      | 1         | 7.14%   |
| AuthenTec AES2810                                          | 1         | 7.14%   |
| AuthenTec AES1600                                          | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 7         | 87.5%   |
| OmniKey  | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 126       | 70.79%  |
| 1     | 45        | 25.28%  |
| 2     | 6         | 3.37%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 22.95%  |
| Fingerprint reader       | 14        | 22.95%  |
| Net/wireless             | 11        | 18.03%  |
| Chipcard                 | 8         | 13.11%  |
| Bluetooth                | 4         | 6.56%   |
| Storage                  | 2         | 3.28%   |
| Net/ethernet             | 2         | 3.28%   |
| Multimedia controller    | 2         | 3.28%   |
| Communication controller | 2         | 3.28%   |
| Card reader              | 1         | 1.64%   |
| Camera                   | 1         | 1.64%   |

