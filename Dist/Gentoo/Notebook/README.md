Gentoo - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Gentoo.

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

Total: 1430

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6b0368fd61](https://linux-hardware.org/?probe=6b0368fd61) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [87b9f04878](https://linux-hardware.org/?probe=87b9f04878) | Dec 23, 2023 |
| Dell          | Precision 5480              | [7cc190b5c0](https://linux-hardware.org/?probe=7cc190b5c0) | Dec 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b14bdf4602](https://linux-hardware.org/?probe=b14bdf4602) | Dec 20, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [8e419e7090](https://linux-hardware.org/?probe=8e419e7090) | Dec 16, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [042bbde845](https://linux-hardware.org/?probe=042bbde845) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [4c6cd4453d](https://linux-hardware.org/?probe=4c6cd4453d) | Dec 10, 2023 |
| Dell          | XPS 9320                    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| BANGHO        | MAX L4                      | [d1306fe54f](https://linux-hardware.org/?probe=d1306fe54f) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | [a0f107fc92](https://linux-hardware.org/?probe=a0f107fc92) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [d95358436c](https://linux-hardware.org/?probe=d95358436c) | Nov 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [d4c90a615f](https://linux-hardware.org/?probe=d4c90a615f) | Nov 29, 2023 |
| Unknown       | Unknown                     | [b6ebeab524](https://linux-hardware.org/?probe=b6ebeab524) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [2b2bb98701](https://linux-hardware.org/?probe=2b2bb98701) | Nov 29, 2023 |
| Dell          | Latitude E6540              | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Unknown       | Unknown                     | [d7d0f11ab2](https://linux-hardware.org/?probe=d7d0f11ab2) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [9d3e14a9ba](https://linux-hardware.org/?probe=9d3e14a9ba) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| Dell          | Latitude D630               | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| HP            | EliteBook 840 G5            | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [360ad65af8](https://linux-hardware.org/?probe=360ad65af8) | Nov 21, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3a8da808e0](https://linux-hardware.org/?probe=3a8da808e0) | Nov 20, 2023 |
| HP            | Victus by Gaming Laptop ... | [d46bf1bcb4](https://linux-hardware.org/?probe=d46bf1bcb4) | Nov 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| HP            | Pavilion Notebook           | [85f5d912da](https://linux-hardware.org/?probe=85f5d912da) | Nov 18, 2023 |
| Dell          | Latitude D630               | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| Dell          | Precision 5480              | [ee10103325](https://linux-hardware.org/?probe=ee10103325) | Nov 18, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Dell          | G5 5505                     | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [f1e3e6eb2c](https://linux-hardware.org/?probe=f1e3e6eb2c) | Nov 13, 2023 |
| Dell          | G5 5505                     | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| Lenovo        | G50-30 80G0                 | [51cd292a70](https://linux-hardware.org/?probe=51cd292a70) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | [16d356b88c](https://linux-hardware.org/?probe=16d356b88c) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | [bce581924a](https://linux-hardware.org/?probe=bce581924a) | Nov 12, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [6996973cde](https://linux-hardware.org/?probe=6996973cde) | Nov 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4aae90aee9](https://linux-hardware.org/?probe=4aae90aee9) | Nov 11, 2023 |
| Dell          | Latitude D630               | [8af88f25f0](https://linux-hardware.org/?probe=8af88f25f0) | Nov 10, 2023 |
| Notebook      | NS5x_NS7xPU                 | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [379584ba47](https://linux-hardware.org/?probe=379584ba47) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [503b6e943c](https://linux-hardware.org/?probe=503b6e943c) | Nov 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| Dell          | XPS 15 7590                 | [63e30986f6](https://linux-hardware.org/?probe=63e30986f6) | Nov 05, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Dell          | XPS 15 9530                 | [148857cc51](https://linux-hardware.org/?probe=148857cc51) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| Dell          | Latitude 7320               | [efc40122bf](https://linux-hardware.org/?probe=efc40122bf) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [de3f77c938](https://linux-hardware.org/?probe=de3f77c938) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| Acer          | Swift SFX14-41G             | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [47e99a1356](https://linux-hardware.org/?probe=47e99a1356) | Oct 26, 2023 |
| HP            | EliteBook 845 14 inch G1... | [ba2a49fbef](https://linux-hardware.org/?probe=ba2a49fbef) | Oct 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f4a0aca53d](https://linux-hardware.org/?probe=f4a0aca53d) | Oct 24, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| Lenovo        | G50-30 80G0                 | [2a00efe761](https://linux-hardware.org/?probe=2a00efe761) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [3368da4a2b](https://linux-hardware.org/?probe=3368da4a2b) | Oct 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8be373f42f](https://linux-hardware.org/?probe=8be373f42f) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [98ebe6766d](https://linux-hardware.org/?probe=98ebe6766d) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [4f5f1c9eea](https://linux-hardware.org/?probe=4f5f1c9eea) | Oct 11, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [af06968ae1](https://linux-hardware.org/?probe=af06968ae1) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| HP            | EliteBook 830 G6            | [e684c274a6](https://linux-hardware.org/?probe=e684c274a6) | Oct 03, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| HP            | EliteBook 830 G6            | [154150aa88](https://linux-hardware.org/?probe=154150aa88) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8a581a8a85](https://linux-hardware.org/?probe=8a581a8a85) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [7732f1eb9b](https://linux-hardware.org/?probe=7732f1eb9b) | Sep 22, 2023 |
| HP            | ProBook 450 G5              | [e1b56bb588](https://linux-hardware.org/?probe=e1b56bb588) | Sep 19, 2023 |
| HP            | EliteBook 830 G6            | [8dcd49002d](https://linux-hardware.org/?probe=8dcd49002d) | Sep 18, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [4b1c4ae225](https://linux-hardware.org/?probe=4b1c4ae225) | Sep 18, 2023 |
| Timi          | RedmiBook Pro 15S           | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| Acer          | Aspire A515-45              | [7cd5acacf7](https://linux-hardware.org/?probe=7cd5acacf7) | Sep 16, 2023 |
| HP            | EliteBook 8540w             | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| HP            | ProBook 450 G5              | [077f5b81b8](https://linux-hardware.org/?probe=077f5b81b8) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [de7acf45a6](https://linux-hardware.org/?probe=de7acf45a6) | Sep 12, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [5ac44fe5ec](https://linux-hardware.org/?probe=5ac44fe5ec) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| Dell          | Precision M4800             | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [a6bbf0ac50](https://linux-hardware.org/?probe=a6bbf0ac50) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| System76      | Pangolin                    | [43dbf49440](https://linux-hardware.org/?probe=43dbf49440) | Sep 06, 2023 |
| System76      | Pangolin                    | [461b8d48ba](https://linux-hardware.org/?probe=461b8d48ba) | Sep 05, 2023 |
| Gigabyte      | AORUS 17 XE4                | [7987abcc44](https://linux-hardware.org/?probe=7987abcc44) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | [f3cbaf1a86](https://linux-hardware.org/?probe=f3cbaf1a86) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | [b0e01251ca](https://linux-hardware.org/?probe=b0e01251ca) | Sep 04, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| HP            | ProBook 430 G5              | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| Dell          | Inspiron 15 3511            | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Dell          | Latitude E6510              | [ccc08ed4ed](https://linux-hardware.org/?probe=ccc08ed4ed) | Aug 30, 2023 |
| Dell          | Latitude E6510              | [dcf1be6cbe](https://linux-hardware.org/?probe=dcf1be6cbe) | Aug 30, 2023 |
| Dell          | G5 5505                     | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| HP            | EliteBook 8540w             | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| MSI           | Modern 14 C12M              | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| Timi          | RedmiBook Pro 15S           | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| HP            | Laptop 14-df0xxx            | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Apple         | MacBookPro11,1              | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| HP            | EliteBook 8540w             | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| Dell          | Latitude E7450              | [057d88b470](https://linux-hardware.org/?probe=057d88b470) | Aug 13, 2023 |
| HP            | EliteBook 8540w             | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [46ae462027](https://linux-hardware.org/?probe=46ae462027) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Apple         | MacBookPro10,1              | [ed97e2ea3e](https://linux-hardware.org/?probe=ed97e2ea3e) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| Lenovo        | Yoga 2 13 20344             | [767b492aa4](https://linux-hardware.org/?probe=767b492aa4) | Aug 03, 2023 |
| Lenovo        | Yoga 2 13 20344             | [47ca08e0d1](https://linux-hardware.org/?probe=47ca08e0d1) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| Alienware     | x17 R1                      | [bcdf52a63e](https://linux-hardware.org/?probe=bcdf52a63e) | Aug 01, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| Apple         | MacBookPro12,1              | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| HP            | EliteBook 8540w             | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [3cb74490f6](https://linux-hardware.org/?probe=3cb74490f6) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| Dell          | XPS 15 9520                 | [54377b2911](https://linux-hardware.org/?probe=54377b2911) | Jul 25, 2023 |
| A-DATA Tec... | XENIA 15                    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| HP            | ProBook 450 G5              | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| HP            | ProBook 440 G7              | [48cf81576d](https://linux-hardware.org/?probe=48cf81576d) | Jul 17, 2023 |
| HP            | EliteBook 8540w             | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a5cdc8bb58](https://linux-hardware.org/?probe=a5cdc8bb58) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [2a37881afa](https://linux-hardware.org/?probe=2a37881afa) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| Dell          | XPS 15 7590                 | [ca41a9886a](https://linux-hardware.org/?probe=ca41a9886a) | Jul 09, 2023 |
| HP            | EliteBook 8540w             | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| Fujitsu       | LIFEBOOK U758               | [eaa8bbf9da](https://linux-hardware.org/?probe=eaa8bbf9da) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Jumper        | EZbook                      | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| HP            | EliteBook 8540w             | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| Dell          | Inspiron 16 5625            | [bf36f89d32](https://linux-hardware.org/?probe=bf36f89d32) | Jul 01, 2023 |
| Dell          | Inspiron 16 5625            | [cbbe256fa2](https://linux-hardware.org/?probe=cbbe256fa2) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [2d16f5be74](https://linux-hardware.org/?probe=2d16f5be74) | Jun 29, 2023 |
| HP            | EliteBook 8540w             | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [178ed56625](https://linux-hardware.org/?probe=178ed56625) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| HP            | EliteBook 8540w             | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [12153cd235](https://linux-hardware.org/?probe=12153cd235) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| HP            | ENVY m6                     | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| Dell          | Precision 5530              | [29ec4c7e1d](https://linux-hardware.org/?probe=29ec4c7e1d) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| Dell          | Precision 5530              | [cff5125fb6](https://linux-hardware.org/?probe=cff5125fb6) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| HP            | EliteBook 8540w             | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| Google        | Nightfury                   | [02badb166b](https://linux-hardware.org/?probe=02badb166b) | Jun 14, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| Lenovo        | Yoga 2 13 20344             | [eab5787d6a](https://linux-hardware.org/?probe=eab5787d6a) | Jun 11, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Acer          | Swift SF314-511             | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| Dell          | Precision 5530              | [8b4e10b85a](https://linux-hardware.org/?probe=8b4e10b85a) | Jun 05, 2023 |
| Apple         | MacBookPro11,1              | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| Dell          | Precision 5530              | [151584f5aa](https://linux-hardware.org/?probe=151584f5aa) | Jun 02, 2023 |
| MSI           | GE76 Raider 11UH            | [64a17da7a3](https://linux-hardware.org/?probe=64a17da7a3) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [f4889c41be](https://linux-hardware.org/?probe=f4889c41be) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| HP            | Pavilion Notebook           | [08eec5e6ca](https://linux-hardware.org/?probe=08eec5e6ca) | May 26, 2023 |
| Acer          | Aspire A515-45G             | [99bcbfbb2a](https://linux-hardware.org/?probe=99bcbfbb2a) | May 25, 2023 |
| HP            | EliteBook 8570w             | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Fujitsu       | CELSIUS H760                | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [4b3b94a776](https://linux-hardware.org/?probe=4b3b94a776) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [870c85a9ac](https://linux-hardware.org/?probe=870c85a9ac) | May 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [847d86e573](https://linux-hardware.org/?probe=847d86e573) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Unknown       | Unknown                     | [82281ca3d5](https://linux-hardware.org/?probe=82281ca3d5) | May 06, 2023 |
| HUAWEI        | CREM-WXX9                   | [8ebf347e24](https://linux-hardware.org/?probe=8ebf347e24) | May 03, 2023 |
| Acer          | Swift SF314-41              | [520066013b](https://linux-hardware.org/?probe=520066013b) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| HP            | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| Dell          | Inspiron N5010              | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a16e963c10](https://linux-hardware.org/?probe=a16e963c10) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8bc0a29b23](https://linux-hardware.org/?probe=8bc0a29b23) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| Dell          | Precision 7770              | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| Dell          | Latitude 7420               | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [21c928caeb](https://linux-hardware.org/?probe=21c928caeb) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [1c99075a1d](https://linux-hardware.org/?probe=1c99075a1d) | Apr 16, 2023 |
| Toshiba       | Satellite L850              | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| HP            | OMEN by Laptop              | [8a1ef40351](https://linux-hardware.org/?probe=8a1ef40351) | Apr 15, 2023 |
| Dell          | Inspiron 5415               | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| MAXDATA       | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Acer          | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Dell          | Precision 7770              | [5091c10fa2](https://linux-hardware.org/?probe=5091c10fa2) | Apr 11, 2023 |
| HUAWEI        | KPL-W0X                     | [2cf04d07fb](https://linux-hardware.org/?probe=2cf04d07fb) | Apr 09, 2023 |
| HP            | Laptop 17-cp0xxx            | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Dell          | XPS 13 9305                 | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| HP            | EliteBook 745 G6            | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| Dell          | Latitude 7480               | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP            | EliteBook 745 G6            | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| HP            | EliteBook 8570p             | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| HP            | ZBook 17 G3                 | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Unknown       | Unknown                     | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs     | StarBook                    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell          | Precision 7770              | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell          | Precision 7770              | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell          | Precision 7770              | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| Dell          | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| Dell          | Precision 7770              | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| Dell          | Precision 7770              | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Acer          | Aspire 7750G                | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| IBM           | ThinkPad T41 23737JU        | [5495bd2109](https://linux-hardware.org/?probe=5495bd2109) | Mar 03, 2023 |
| Apple         | MacBookPro9,1               | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| MSI           | GS66 Stealth 10UE           | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| HP            | Laptop 17-ca1xxx            | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| Acer          | Aspire A515-45G             | [5f8c1e2d90](https://linux-hardware.org/?probe=5f8c1e2d90) | Feb 28, 2023 |
| MSI           | GS66 Stealth 10UE           | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| realme        | RMNBXXXX                    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Valve         | Jupiter                     | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| MSI           | GS66 Stealth 10UE           | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP            | Victus by Gaming Laptop ... | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Alienware     | 17                          | [848d5cd7e9](https://linux-hardware.org/?probe=848d5cd7e9) | Feb 20, 2023 |
| Dell          | Precision 7770              | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Valve         | Jupiter                     | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| Unknown       | Unknown                     | [7d36f8eee5](https://linux-hardware.org/?probe=7d36f8eee5) | Feb 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| MSI           | GS66 Stealth 10UE           | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Timi          | RedmiBook Pro 15S           | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Unknown       | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP            | Pavilion Notebook           | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | [aedfc67444](https://linux-hardware.org/?probe=aedfc67444) | Feb 12, 2023 |
| Unknown       | Unknown                     | [e0fd4c1db9](https://linux-hardware.org/?probe=e0fd4c1db9) | Feb 11, 2023 |
| Apple         | MacBookPro10,2              | [85b07c179c](https://linux-hardware.org/?probe=85b07c179c) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | [238c7a2c08](https://linux-hardware.org/?probe=238c7a2c08) | Feb 09, 2023 |
| Dell          | Precision 7770              | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell          | Precision 7770              | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell          | Precision 7770              | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Valve         | Jupiter                     | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| Valve         | Jupiter                     | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [37d0cc301b](https://linux-hardware.org/?probe=37d0cc301b) | Feb 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [a08ee9b387](https://linux-hardware.org/?probe=a08ee9b387) | Feb 03, 2023 |
| Dell          | Precision 7770              | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| MSI           | GP60 2PE                    | [a1bb8934a0](https://linux-hardware.org/?probe=a1bb8934a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [396877a008](https://linux-hardware.org/?probe=396877a008) | Jan 31, 2023 |
| Sony          | PCG-GRT230(UC)              | [0a7c76da78](https://linux-hardware.org/?probe=0a7c76da78) | Jan 30, 2023 |
| Google        | Helios                      | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [f71299a9c6](https://linux-hardware.org/?probe=f71299a9c6) | Jan 27, 2023 |
| Dell          | XPS 9320                    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Dell          | Latitude 5530               | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 7770              | [47044d362f](https://linux-hardware.org/?probe=47044d362f) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| HP            | Victus by Gaming Laptop ... | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Dell          | XPS 9320                    | [ebe686793d](https://linux-hardware.org/?probe=ebe686793d) | Jan 21, 2023 |
| Dell          | XPS 9320                    | [706152a268](https://linux-hardware.org/?probe=706152a268) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | [d37b338c87](https://linux-hardware.org/?probe=d37b338c87) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | [413cd3b7cf](https://linux-hardware.org/?probe=413cd3b7cf) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [753a61e1de](https://linux-hardware.org/?probe=753a61e1de) | Jan 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [b14d57e1a3](https://linux-hardware.org/?probe=b14d57e1a3) | Jan 19, 2023 |
| Dell          | Precision 7720              | [9a00916b91](https://linux-hardware.org/?probe=9a00916b91) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Schenker      | XMG PRO (E22)               | [475e812e56](https://linux-hardware.org/?probe=475e812e56) | Jan 19, 2023 |
| Dell          | Latitude 5410               | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| Dell          | Precision 7720              | [f8e1c53257](https://linux-hardware.org/?probe=f8e1c53257) | Jan 16, 2023 |
| MSI           | Bravo 15 B5DD               | [8e35281ea5](https://linux-hardware.org/?probe=8e35281ea5) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [4fe502c977](https://linux-hardware.org/?probe=4fe502c977) | Jan 10, 2023 |
| Google        | Sasuke                      | [aa3a09aaef](https://linux-hardware.org/?probe=aa3a09aaef) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | [0dbae6cda4](https://linux-hardware.org/?probe=0dbae6cda4) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | [bca9343f96](https://linux-hardware.org/?probe=bca9343f96) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [40a6c7370b](https://linux-hardware.org/?probe=40a6c7370b) | Jan 05, 2023 |
| Acer          | TravelMate B115-M           | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| Dell          | Precision 7720              | [59813a7461](https://linux-hardware.org/?probe=59813a7461) | Jan 03, 2023 |
| Lenovo        | ThinkPad W540 20BG0033RT    | [5cfa12cec1](https://linux-hardware.org/?probe=5cfa12cec1) | Dec 31, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [4b130212a2](https://linux-hardware.org/?probe=4b130212a2) | Dec 30, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [0c7ced8708](https://linux-hardware.org/?probe=0c7ced8708) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| Dell          | Precision 7720              | [56db0ab146](https://linux-hardware.org/?probe=56db0ab146) | Dec 28, 2022 |
| Dell          | Precision 7720              | [e94a7bb989](https://linux-hardware.org/?probe=e94a7bb989) | Dec 28, 2022 |
| Dell          | G3 3500                     | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| System76      | Darter Pro                  | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| Dell          | G5 5505                     | [87f62bee87](https://linux-hardware.org/?probe=87f62bee87) | Dec 26, 2022 |
| Star Labs     | StarLite                    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Dell          | Vostro 5490                 | [f694fa24c8](https://linux-hardware.org/?probe=f694fa24c8) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [25cbb2c39a](https://linux-hardware.org/?probe=25cbb2c39a) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| HP            | 250 G7 Notebook PC          | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b9aed745da](https://linux-hardware.org/?probe=b9aed745da) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c7cea6dd19](https://linux-hardware.org/?probe=c7cea6dd19) | Dec 20, 2022 |
| Dell          | Inspiron 15 3511            | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | [3dc497faf1](https://linux-hardware.org/?probe=3dc497faf1) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| Acer          | Predator PH315-51           | [34676168fa](https://linux-hardware.org/?probe=34676168fa) | Dec 14, 2022 |
| Acer          | Predator PH315-51           | [0f9b4ae170](https://linux-hardware.org/?probe=0f9b4ae170) | Dec 14, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7541ce9ac6](https://linux-hardware.org/?probe=7541ce9ac6) | Dec 11, 2022 |
| Star Labs     | StarLite                    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| HP            | ProBook 6570b               | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |
| Star Labs     | StarLite                    | [4446ba1d6a](https://linux-hardware.org/?probe=4446ba1d6a) | Dec 10, 2022 |
| Google        | Eve                         | [d78558c833](https://linux-hardware.org/?probe=d78558c833) | Dec 08, 2022 |
| Google        | Eve                         | [92d1d03fed](https://linux-hardware.org/?probe=92d1d03fed) | Dec 08, 2022 |
| Toshiba       | Satellite L50-B             | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9fec7bdfdc](https://linux-hardware.org/?probe=9fec7bdfdc) | Dec 04, 2022 |
| HP            | G62                         | [494d9e65e4](https://linux-hardware.org/?probe=494d9e65e4) | Dec 03, 2022 |
| Dell          | Inspiron 3501               | [f9379c4ffb](https://linux-hardware.org/?probe=f9379c4ffb) | Dec 01, 2022 |
| Unknown       | Unknown                     | [dceef2a9d5](https://linux-hardware.org/?probe=dceef2a9d5) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [d77cb5ebb0](https://linux-hardware.org/?probe=d77cb5ebb0) | Nov 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| Acer          | Swift SF314-57              | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| Dell          | Inspiron N5010              | [8a94d169c5](https://linux-hardware.org/?probe=8a94d169c5) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | [fbe52d681e](https://linux-hardware.org/?probe=fbe52d681e) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Unknown       | Unknown                     | [f3222cf843](https://linux-hardware.org/?probe=f3222cf843) | Nov 16, 2022 |
| Unknown       | Unknown                     | [9217d900c4](https://linux-hardware.org/?probe=9217d900c4) | Nov 16, 2022 |
| Lenovo        | G50-30 80G0                 | [b870eb1d72](https://linux-hardware.org/?probe=b870eb1d72) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [346303c711](https://linux-hardware.org/?probe=346303c711) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [cbd0b88f5f](https://linux-hardware.org/?probe=cbd0b88f5f) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [0e9a1a51a5](https://linux-hardware.org/?probe=0e9a1a51a5) | Nov 14, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [2e29461f3b](https://linux-hardware.org/?probe=2e29461f3b) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9db585ddc5](https://linux-hardware.org/?probe=9db585ddc5) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| Dell          | Precision 5540              | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Acer          | Nitro AN515-58              | [9f4cb2a547](https://linux-hardware.org/?probe=9f4cb2a547) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [8939445388](https://linux-hardware.org/?probe=8939445388) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [420aaf8ede](https://linux-hardware.org/?probe=420aaf8ede) | Nov 09, 2022 |
| Dell          | G3 3500                     | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d238949b9f](https://linux-hardware.org/?probe=d238949b9f) | Nov 06, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [dda5d2dd10](https://linux-hardware.org/?probe=dda5d2dd10) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [c0f68304d1](https://linux-hardware.org/?probe=c0f68304d1) | Nov 03, 2022 |
| Acer          | Nitro AN515-43              | [8ca3bfde82](https://linux-hardware.org/?probe=8ca3bfde82) | Nov 02, 2022 |
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | G3 3500                     | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [2e39c3ce92](https://linux-hardware.org/?probe=2e39c3ce92) | Oct 30, 2022 |
| Dell          | Vostro 5490                 | [057163f0e4](https://linux-hardware.org/?probe=057163f0e4) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [42fcb880db](https://linux-hardware.org/?probe=42fcb880db) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [242fbb2c79](https://linux-hardware.org/?probe=242fbb2c79) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [7800fc7b5b](https://linux-hardware.org/?probe=7800fc7b5b) | Oct 29, 2022 |
| Acer          | AOD257                      | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Dell          | Vostro 5490                 | [ac6587adbb](https://linux-hardware.org/?probe=ac6587adbb) | Oct 27, 2022 |
| Acer          | AOD257                      | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [a44f774778](https://linux-hardware.org/?probe=a44f774778) | Oct 27, 2022 |
| Dell          | Precision 5570              | [d74abc314b](https://linux-hardware.org/?probe=d74abc314b) | Oct 25, 2022 |
| HP            | Pavilion Notebook           | [35cf015c33](https://linux-hardware.org/?probe=35cf015c33) | Oct 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9115752bd4](https://linux-hardware.org/?probe=9115752bd4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| Gigabyte      | G5 KD                       | [c0f91f7282](https://linux-hardware.org/?probe=c0f91f7282) | Oct 20, 2022 |
| Gigabyte      | G5 KD                       | [35db9f3cd8](https://linux-hardware.org/?probe=35db9f3cd8) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4644a299f3](https://linux-hardware.org/?probe=4644a299f3) | Oct 18, 2022 |
| Dell          | Precision 7760              | [44b60a4fcf](https://linux-hardware.org/?probe=44b60a4fcf) | Oct 18, 2022 |
| Sony          | PCG-GRT230(UC)              | [b33a31225b](https://linux-hardware.org/?probe=b33a31225b) | Oct 18, 2022 |
| HP            | Laptop 14-dk1xxx            | [caf126d0af](https://linux-hardware.org/?probe=caf126d0af) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [41d3e4e97d](https://linux-hardware.org/?probe=41d3e4e97d) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | G3 3500                     | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | [f60fd55235](https://linux-hardware.org/?probe=f60fd55235) | Oct 16, 2022 |
| Dell          | G3 3500                     | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| HP            | EliteBook 830 G6            | [0dc42d7e5e](https://linux-hardware.org/?probe=0dc42d7e5e) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| IBM           | ThinkPad T42 2373K1U        | [934a3226e9](https://linux-hardware.org/?probe=934a3226e9) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Intel Clie... | LAPBC710                    | [42b7bc6ee4](https://linux-hardware.org/?probe=42b7bc6ee4) | Oct 10, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [99d95e9424](https://linux-hardware.org/?probe=99d95e9424) | Oct 09, 2022 |
| Valve         | Jupiter                     | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| Intel Clie... | LAPBC710                    | [bacb30816f](https://linux-hardware.org/?probe=bacb30816f) | Oct 07, 2022 |
| ASUSTek       | ProArt Studiobook H7600Z... | [5db7aac5d3](https://linux-hardware.org/?probe=5db7aac5d3) | Oct 07, 2022 |
| HP            | Laptop 15-ra0xx             | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| Alienware     | x14                         | [ad37874de1](https://linux-hardware.org/?probe=ad37874de1) | Oct 05, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [ae4533cfd6](https://linux-hardware.org/?probe=ae4533cfd6) | Oct 03, 2022 |
| MSI           | GE66 Raider 11UE            | [0eb2e22fc1](https://linux-hardware.org/?probe=0eb2e22fc1) | Oct 03, 2022 |
| Sony          | PCG-GRT230(UC)              | [cab24d4c04](https://linux-hardware.org/?probe=cab24d4c04) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6d9c960574](https://linux-hardware.org/?probe=6d9c960574) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [4479784a2e](https://linux-hardware.org/?probe=4479784a2e) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [d0808e8abe](https://linux-hardware.org/?probe=d0808e8abe) | Sep 27, 2022 |
| Sony          | PCG-GRT230(UC)              | [af843c265c](https://linux-hardware.org/?probe=af843c265c) | Sep 26, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [6ea4c40a80](https://linux-hardware.org/?probe=6ea4c40a80) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [cdbc7c7949](https://linux-hardware.org/?probe=cdbc7c7949) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [907383d255](https://linux-hardware.org/?probe=907383d255) | Sep 25, 2022 |
| Matsushita... | CF-29LTQGZBM                | [29f52f862c](https://linux-hardware.org/?probe=29f52f862c) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | ThinkPad L580 20LWCTO1WW    | [a80367f777](https://linux-hardware.org/?probe=a80367f777) | Sep 21, 2022 |
| System76      | Gazelle Professional        | [95f19a0c4c](https://linux-hardware.org/?probe=95f19a0c4c) | Sep 18, 2022 |
| Dell          | G7 7588                     | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Timi          | TM1604                      | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Dell          | Latitude D410               | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Toshiba       | Satellite C850D-118         | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| win elemen... | MoreFine S500+              | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Eluktronic... | MAX-17                      | [627ecbeb36](https://linux-hardware.org/?probe=627ecbeb36) | Aug 29, 2022 |
| Dell          | Precision 3570              | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| Timi          | A35                         | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Timi          | A35                         | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| IBM           | 2722BDG                     | [e0fe2162a3](https://linux-hardware.org/?probe=e0fe2162a3) | Aug 18, 2022 |
| Dell          | G3 3500                     | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Purism        | Librem 15 v4                | [4448709e50](https://linux-hardware.org/?probe=4448709e50) | Aug 13, 2022 |
| Purism        | Librem 15 v4                | [9e76f9e7ff](https://linux-hardware.org/?probe=9e76f9e7ff) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| Timi          | A35                         | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Notebook      | N141CU                      | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Acer          | Swift SF314-512             | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9b228ae787](https://linux-hardware.org/?probe=9b228ae787) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9f2e51f185](https://linux-hardware.org/?probe=9f2e51f185) | Aug 10, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [78f846e0e5](https://linux-hardware.org/?probe=78f846e0e5) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Toshiba       | NB100                       | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [019849a487](https://linux-hardware.org/?probe=019849a487) | Aug 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| Samsung       | 700G7C                      | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | [fa1566785a](https://linux-hardware.org/?probe=fa1566785a) | Aug 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Razer         | Blade 15 Studio Edition ... | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI           | GS63VR 6RF                  | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell          | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI           | GS63VR 6RF                  | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo        | G510 20238                  | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| HP            | EliteBook 2560p             | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Toshiba       | Satellite A200              | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| Timi          | RedmiBook 13                | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Dell          | Precision 7550              | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| AVITA         | NS14A6                      | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| Dell          | G3 3500                     | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [6fa09c2dd0](https://linux-hardware.org/?probe=6fa09c2dd0) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [d3f9fd8f0c](https://linux-hardware.org/?probe=d3f9fd8f0c) | Jun 16, 2022 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [283958f1a4](https://linux-hardware.org/?probe=283958f1a4) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | G3 3500                     | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| Dell          | XPS 17 9710                 | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell          | XPS 17 9710                 | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Dell          | Inspiron 15 5510            | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | 1005HA                      | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | 1005HA                      | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| HP            | Laptop 14-dk1xxx            | [6f78dba14b](https://linux-hardware.org/?probe=6f78dba14b) | May 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Acer          | Aspire E5-571G              | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| HP            | ProBook 430 G7              | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| HP            | ZBook 15 G3                 | [020e862674](https://linux-hardware.org/?probe=020e862674) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| HP            | Pavilion Notebook           | [0f04e6b439](https://linux-hardware.org/?probe=0f04e6b439) | May 09, 2022 |
| HP            | 255 G8 Notebook PC          | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Dell          | Inspiron 1525               | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| Lenovo        | Yoga 2 13 20344             | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Acer          | Aspire E5-571G              | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| Dell          | Precision 3520              | [caae9a5055](https://linux-hardware.org/?probe=caae9a5055) | May 02, 2022 |
| Lenovo        | Yoga 2 13 20344             | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| HP            | ZBook 15 G3                 | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| Dell          | G3 3500                     | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Acer          | Aspire VX5-591G             | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | [5620bf468d](https://linux-hardware.org/?probe=5620bf468d) | Apr 13, 2022 |
| Dell          | G5 5505                     | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| MSI           | GE66 Raider 11UE            | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| HP            | Pavilion Notebook           | [51c96e48de](https://linux-hardware.org/?probe=51c96e48de) | Apr 10, 2022 |
| Dell          | Precision 7560              | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| Apple         | MacBookAir3,1               | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| Apple         | MacBookPro11,3              | [18fb9eceac](https://linux-hardware.org/?probe=18fb9eceac) | Apr 09, 2022 |
| System76      | Gazelle                     | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [b7b2d796d9](https://linux-hardware.org/?probe=b7b2d796d9) | Apr 08, 2022 |
| System76      | Gazelle                     | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| MSI           | GE66 Raider 11UE            | [30cd3d5d00](https://linux-hardware.org/?probe=30cd3d5d00) | Apr 06, 2022 |
| Timi          | A35                         | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | [11ca55cd73](https://linux-hardware.org/?probe=11ca55cd73) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | [27768b901a](https://linux-hardware.org/?probe=27768b901a) | Mar 28, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| MSI           | GE66 Raider 11UE            | [69919648c7](https://linux-hardware.org/?probe=69919648c7) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [4b3bd32143](https://linux-hardware.org/?probe=4b3bd32143) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| Apple         | MacBookPro11,3              | [e39c413976](https://linux-hardware.org/?probe=e39c413976) | Mar 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [906f450dd5](https://linux-hardware.org/?probe=906f450dd5) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| Dell          | XPS 12-9Q33                 | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| MSI           | MS-7A34                     | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [3f58a0f2a4](https://linux-hardware.org/?probe=3f58a0f2a4) | Mar 11, 2022 |
| Framework     | Laptop                      | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Framework     | Laptop                      | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Toshiba       | Satellite L50-C             | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ee935ed8be](https://linux-hardware.org/?probe=ee935ed8be) | Feb 28, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Dell          | XPS 17 9710                 | [302433b9e3](https://linux-hardware.org/?probe=302433b9e3) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Timi          | RedmiBook Pro 15S           | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| Dell          | XPS 17 9710                 | [018fa00447](https://linux-hardware.org/?probe=018fa00447) | Feb 17, 2022 |
| HP            | ProBook 450 G6              | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | XPS 13 9310                 | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| Dell          | Inspiron 5515               | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| ASUSTek       | 900                         | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Samsung       | RC530/RC730                 | [c4651bdbc6](https://linux-hardware.org/?probe=c4651bdbc6) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [e35fffc0dd](https://linux-hardware.org/?probe=e35fffc0dd) | Jan 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [2f36ebcc7e](https://linux-hardware.org/?probe=2f36ebcc7e) | Jan 30, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Dell          | Precision 7520              | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| Dell          | XPS 15 9570                 | [cd1ab231e7](https://linux-hardware.org/?probe=cd1ab231e7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [999e47c570](https://linux-hardware.org/?probe=999e47c570) | Jan 28, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Dell          | XPS 15 9570                 | [1ccb1fd970](https://linux-hardware.org/?probe=1ccb1fd970) | Jan 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [7e7edbe447](https://linux-hardware.org/?probe=7e7edbe447) | Jan 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [3c430f09c4](https://linux-hardware.org/?probe=3c430f09c4) | Jan 23, 2022 |
| MSI           | GE73 Raider RGB 8RF         | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Dell          | XPS 17 9710                 | [597fae9cb6](https://linux-hardware.org/?probe=597fae9cb6) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Apple         | MacBookPro6,2               | [93dfa22733](https://linux-hardware.org/?probe=93dfa22733) | Jan 17, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Apple         | MacBookPro6,2               | [e69fb99ebf](https://linux-hardware.org/?probe=e69fb99ebf) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | [cdb65d6460](https://linux-hardware.org/?probe=cdb65d6460) | Jan 13, 2022 |
| Acer          | Swift SF314-59              | [175b161d3f](https://linux-hardware.org/?probe=175b161d3f) | Jan 11, 2022 |
| Samsung       | 700T1C                      | [349d306d37](https://linux-hardware.org/?probe=349d306d37) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| HUAWEI        | HVY-WXX9                    | [f6376ab7d5](https://linux-hardware.org/?probe=f6376ab7d5) | Jan 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [639c7cbb68](https://linux-hardware.org/?probe=639c7cbb68) | Jan 06, 2022 |
| Acer          | Aspire E5-571G              | [75edf90312](https://linux-hardware.org/?probe=75edf90312) | Jan 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| Dell          | Precision 7560              | [158ff657e7](https://linux-hardware.org/?probe=158ff657e7) | Jan 02, 2022 |
| Timi          | RedmiBook 13                | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Timi          | A35                         | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| Dell          | XPS 17 9710                 | [ac139db0b3](https://linux-hardware.org/?probe=ac139db0b3) | Dec 27, 2021 |
| MSI           | Delta 15 A5EFK              | [e874b85848](https://linux-hardware.org/?probe=e874b85848) | Dec 26, 2021 |
| Lenovo        | ThinkPad T480s 20L7001MR... | [199482a1fe](https://linux-hardware.org/?probe=199482a1fe) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [913bb7bf0b](https://linux-hardware.org/?probe=913bb7bf0b) | Dec 25, 2021 |
| Timi          | A35                         | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Apple         | MacBook10,1                 | [4b98d2c8ba](https://linux-hardware.org/?probe=4b98d2c8ba) | Dec 24, 2021 |
| Dell          | Inspiron 15 5510            | [060d274be1](https://linux-hardware.org/?probe=060d274be1) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2144a3a32c](https://linux-hardware.org/?probe=2144a3a32c) | Dec 23, 2021 |
| Dell          | Inspiron 15 5510            | [e4d91f5636](https://linux-hardware.org/?probe=e4d91f5636) | Dec 21, 2021 |
| Framework     | Laptop                      | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| Dell          | Inspiron 15 5510            | [2018752b06](https://linux-hardware.org/?probe=2018752b06) | Dec 21, 2021 |
| Acer          | Aspire E5-571G              | [201e93fd24](https://linux-hardware.org/?probe=201e93fd24) | Dec 20, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b03f7a8ab8](https://linux-hardware.org/?probe=b03f7a8ab8) | Dec 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| Dell          | Latitude 5420               | [f8313f07c4](https://linux-hardware.org/?probe=f8313f07c4) | Dec 18, 2021 |
| Samsung       | 700T1C                      | [f63266db56](https://linux-hardware.org/?probe=f63266db56) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ce3508ebb4](https://linux-hardware.org/?probe=ce3508ebb4) | Dec 17, 2021 |
| HP            | EliteBook 830 G5            | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [d94711b81b](https://linux-hardware.org/?probe=d94711b81b) | Dec 13, 2021 |
| Dell          | XPS 17 9710                 | [ade9c0e3ec](https://linux-hardware.org/?probe=ade9c0e3ec) | Dec 13, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Dell          | XPS 17 9710                 | [fd6cff7345](https://linux-hardware.org/?probe=fd6cff7345) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Acer          | Aspire E5-571G              | [53fb790458](https://linux-hardware.org/?probe=53fb790458) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [208868fbae](https://linux-hardware.org/?probe=208868fbae) | Dec 07, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | RC530/RC730                 | [6105853b97](https://linux-hardware.org/?probe=6105853b97) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Dell          | Vostro 3500                 | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Timi          | A35                         | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Timi          | A35                         | [ce66e74002](https://linux-hardware.org/?probe=ce66e74002) | Nov 25, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [1bb2b21d60](https://linux-hardware.org/?probe=1bb2b21d60) | Nov 24, 2021 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [58684dd498](https://linux-hardware.org/?probe=58684dd498) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| SIEMENS       | SIMATIC Field PG M6         | [a0e1ef3935](https://linux-hardware.org/?probe=a0e1ef3935) | Nov 22, 2021 |
| HP            | Compaq 6730b (KE717AV)      | [71527b8152](https://linux-hardware.org/?probe=71527b8152) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [674bb00d63](https://linux-hardware.org/?probe=674bb00d63) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [47908fe107](https://linux-hardware.org/?probe=47908fe107) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| HP            | ProBook 430 G5              | [634b7c7102](https://linux-hardware.org/?probe=634b7c7102) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [05879919b0](https://linux-hardware.org/?probe=05879919b0) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5f0f191f13](https://linux-hardware.org/?probe=5f0f191f13) | Nov 16, 2021 |
| MOTILE        | M142                        | [d56931cbc6](https://linux-hardware.org/?probe=d56931cbc6) | Nov 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5c55a759db](https://linux-hardware.org/?probe=5c55a759db) | Nov 13, 2021 |
| HP            | EliteBook 745 G6            | [a4bc523c79](https://linux-hardware.org/?probe=a4bc523c79) | Nov 12, 2021 |
| HP            | EliteBook 745 G6            | [faa7680568](https://linux-hardware.org/?probe=faa7680568) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [49148de6c4](https://linux-hardware.org/?probe=49148de6c4) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| ASUSTek       | 900                         | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [efd3dadc76](https://linux-hardware.org/?probe=efd3dadc76) | Nov 08, 2021 |
| Dell          | Latitude E7440              | [96a92b3d98](https://linux-hardware.org/?probe=96a92b3d98) | Nov 04, 2021 |
| Samsung       | RC530/RC730                 | [a4d9d06231](https://linux-hardware.org/?probe=a4d9d06231) | Nov 02, 2021 |
| Dell          | Latitude 7490               | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Dell          | Latitude 5520               | [49a6b5ef90](https://linux-hardware.org/?probe=49a6b5ef90) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | ProBook 455 G7              | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| ASUSTek       | X556URK                     | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| Dell          | Latitude E6530              | [fd1375d5f1](https://linux-hardware.org/?probe=fd1375d5f1) | Oct 28, 2021 |
| Dell          | Latitude E6530              | [f37394899f](https://linux-hardware.org/?probe=f37394899f) | Oct 28, 2021 |
| HP            | Pavilion Notebook           | [4b691f2884](https://linux-hardware.org/?probe=4b691f2884) | Oct 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Timi          | RedmiBook 13 R              | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| Acer          | Aspire A515-55              | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [10d09b7d77](https://linux-hardware.org/?probe=10d09b7d77) | Oct 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d7a870e424](https://linux-hardware.org/?probe=d7a870e424) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [03350be971](https://linux-hardware.org/?probe=03350be971) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [6e6d3fe55c](https://linux-hardware.org/?probe=6e6d3fe55c) | Oct 10, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [67510cc1aa](https://linux-hardware.org/?probe=67510cc1aa) | Oct 10, 2021 |
| Timi          | RedmiBook 13 R              | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [a8ea4ccbef](https://linux-hardware.org/?probe=a8ea4ccbef) | Oct 06, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [666f9cb875](https://linux-hardware.org/?probe=666f9cb875) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Samsung       | RC530/RC730                 | [931664ed89](https://linux-hardware.org/?probe=931664ed89) | Oct 04, 2021 |
| Timi          | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| ASUSTek       | Unknown                     | [9b357ee9bb](https://linux-hardware.org/?probe=9b357ee9bb) | Oct 01, 2021 |
| Dell          | Inspiron 5415               | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [27707fb954](https://linux-hardware.org/?probe=27707fb954) | Oct 01, 2021 |
| HP            | 255 G6 Notebook PC          | [9823c616ed](https://linux-hardware.org/?probe=9823c616ed) | Sep 30, 2021 |
| HP            | ProBook 430 G5              | [6ee2943500](https://linux-hardware.org/?probe=6ee2943500) | Sep 30, 2021 |
| Dell          | Inspiron 5577               | [f5ec85dd12](https://linux-hardware.org/?probe=f5ec85dd12) | Sep 29, 2021 |
| Dell          | Inspiron 5577               | [80e36f9785](https://linux-hardware.org/?probe=80e36f9785) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS1LN00    | [71d301cc84](https://linux-hardware.org/?probe=71d301cc84) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [116e97036b](https://linux-hardware.org/?probe=116e97036b) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8b939aae88](https://linux-hardware.org/?probe=8b939aae88) | Sep 25, 2021 |
| ASUSTek       | GX501VIK                    | [b36bf17cc2](https://linux-hardware.org/?probe=b36bf17cc2) | Sep 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [f40c18c3b8](https://linux-hardware.org/?probe=f40c18c3b8) | Sep 23, 2021 |
| Samsung       | RC530/RC730                 | [4aa6a34c0c](https://linux-hardware.org/?probe=4aa6a34c0c) | Sep 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [4c18c08616](https://linux-hardware.org/?probe=4c18c08616) | Sep 15, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [d406b31a3a](https://linux-hardware.org/?probe=d406b31a3a) | Sep 15, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Notebook      | P65xHP                      | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| Dell          | Latitude 5410               | [97ed647d4c](https://linux-hardware.org/?probe=97ed647d4c) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [9dcddb807d](https://linux-hardware.org/?probe=9dcddb807d) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [572c0c5198](https://linux-hardware.org/?probe=572c0c5198) | Sep 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [36bf3dd55d](https://linux-hardware.org/?probe=36bf3dd55d) | Sep 09, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| HP            | Pavilion g6                 | [1161032a20](https://linux-hardware.org/?probe=1161032a20) | Sep 08, 2021 |
| Dell          | Precision 7560              | [03d7773132](https://linux-hardware.org/?probe=03d7773132) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| ASUSTek       | X550ZA                      | [0d41969b6b](https://linux-hardware.org/?probe=0d41969b6b) | Sep 02, 2021 |
| Dell          | Latitude E6510              | [2ab208b5cd](https://linux-hardware.org/?probe=2ab208b5cd) | Sep 02, 2021 |
| HP            | 255 G6 Notebook PC          | [4f71a8ad02](https://linux-hardware.org/?probe=4f71a8ad02) | Sep 01, 2021 |
| HP            | ZBook 15 G3                 | [d6872bd9e9](https://linux-hardware.org/?probe=d6872bd9e9) | Sep 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| IBM           | ThinkPad T42 2373V4F        | [2362291c05](https://linux-hardware.org/?probe=2362291c05) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [5a606b504c](https://linux-hardware.org/?probe=5a606b504c) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [2af8736235](https://linux-hardware.org/?probe=2af8736235) | Aug 28, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [aabbe0dbcc](https://linux-hardware.org/?probe=aabbe0dbcc) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| HP            | 255 G6 Notebook PC          | [b776f7f3b7](https://linux-hardware.org/?probe=b776f7f3b7) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [62ba09ac38](https://linux-hardware.org/?probe=62ba09ac38) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 23259H1       | [fb125d2779](https://linux-hardware.org/?probe=fb125d2779) | Aug 25, 2021 |
| Dell          | Inspiron 5415               | [909e2cdc93](https://linux-hardware.org/?probe=909e2cdc93) | Aug 15, 2021 |
| Dell          | Inspiron 5415               | [63594290cf](https://linux-hardware.org/?probe=63594290cf) | Aug 11, 2021 |
| TUXEDO        | Book XC1711                 | [806e284c8a](https://linux-hardware.org/?probe=806e284c8a) | Aug 11, 2021 |
| Jumper        | EZpad                       | [da2436c208](https://linux-hardware.org/?probe=da2436c208) | Aug 11, 2021 |
| Jumper        | EZpad                       | [6215ba7396](https://linux-hardware.org/?probe=6215ba7396) | Aug 10, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ddf6a2277a](https://linux-hardware.org/?probe=ddf6a2277a) | Aug 07, 2021 |
| MSI           | GF63 Thin 9SCSR             | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| ASUSTek       | X510UR                      | [8e08727583](https://linux-hardware.org/?probe=8e08727583) | Aug 03, 2021 |
| TUXEDO        | Book_XA1510                 | [f4f777ed12](https://linux-hardware.org/?probe=f4f777ed12) | Aug 03, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [380758e335](https://linux-hardware.org/?probe=380758e335) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [a5a11a0de1](https://linux-hardware.org/?probe=a5a11a0de1) | Jul 28, 2021 |
| Dell          | XPS 15 7590                 | [f22f34ea9a](https://linux-hardware.org/?probe=f22f34ea9a) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3de3129139](https://linux-hardware.org/?probe=3de3129139) | Jul 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c6a7c7d9d8](https://linux-hardware.org/?probe=c6a7c7d9d8) | Jul 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [483690e890](https://linux-hardware.org/?probe=483690e890) | Jul 14, 2021 |
| Dell          | Latitude E6430              | [3dc281ca01](https://linux-hardware.org/?probe=3dc281ca01) | Jul 13, 2021 |
| Dell          | XPS 13 9310                 | [6835266a32](https://linux-hardware.org/?probe=6835266a32) | Jul 10, 2021 |
| Dell          | Latitude E6430              | [f5a73f4d90](https://linux-hardware.org/?probe=f5a73f4d90) | Jul 09, 2021 |
| Dell          | Latitude E6430              | [8d685287ce](https://linux-hardware.org/?probe=8d685287ce) | Jul 09, 2021 |
| HP            | Pavilion Notebook           | [68c41ed42b](https://linux-hardware.org/?probe=68c41ed42b) | Jul 08, 2021 |
| HP            | Pavilion Notebook           | [5a6fca486a](https://linux-hardware.org/?probe=5a6fca486a) | Jul 08, 2021 |
| Acer          | Aspire A315-32              | [3a9edbefac](https://linux-hardware.org/?probe=3a9edbefac) | Jul 06, 2021 |
| Acer          | Aspire A315-32              | [09f71bed72](https://linux-hardware.org/?probe=09f71bed72) | Jul 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| HP            | Pro Tablet 608 G1           | [c1a115b721](https://linux-hardware.org/?probe=c1a115b721) | Jun 28, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [5d9bde452b](https://linux-hardware.org/?probe=5d9bde452b) | Jun 27, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | [69f9da2ac3](https://linux-hardware.org/?probe=69f9da2ac3) | Jun 26, 2021 |
| HUAWEI        | HN-WX9X                     | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Apple         | MacBookPro8,3               | [1453a09197](https://linux-hardware.org/?probe=1453a09197) | Jun 25, 2021 |
| Apple         | MacBookPro8,3               | [94f589e95c](https://linux-hardware.org/?probe=94f589e95c) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [8ac09d11a4](https://linux-hardware.org/?probe=8ac09d11a4) | Jun 20, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [70c10f988f](https://linux-hardware.org/?probe=70c10f988f) | Jun 20, 2021 |
| Dell          | Latitude E7440              | [9302b47a78](https://linux-hardware.org/?probe=9302b47a78) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| MSI           | GS66 Stealth 10SFS          | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| HP            | Pavilion Notebook           | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [8d5844241c](https://linux-hardware.org/?probe=8d5844241c) | Jun 13, 2021 |
| HP            | Laptop 14-dk0xxx            | [9b07d82840](https://linux-hardware.org/?probe=9b07d82840) | Jun 12, 2021 |
| Acer          | Aspire A315-42              | [efab65cf1d](https://linux-hardware.org/?probe=efab65cf1d) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | [f1d0d2bda6](https://linux-hardware.org/?probe=f1d0d2bda6) | Jun 09, 2021 |
| Lenovo        | G50-30 80G0                 | [ab9da369c0](https://linux-hardware.org/?probe=ab9da369c0) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [407abb051f](https://linux-hardware.org/?probe=407abb051f) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e6aba1341](https://linux-hardware.org/?probe=5e6aba1341) | Jun 09, 2021 |
| Dell          | Inspiron 7375               | [7704e5289b](https://linux-hardware.org/?probe=7704e5289b) | Jun 07, 2021 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [f8e58be450](https://linux-hardware.org/?probe=f8e58be450) | Jun 03, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | [b571e885e2](https://linux-hardware.org/?probe=b571e885e2) | Jun 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [f3f3c323ab](https://linux-hardware.org/?probe=f3f3c323ab) | Jun 03, 2021 |
| Dell          | XPS 13 9300                 | [e85b21841c](https://linux-hardware.org/?probe=e85b21841c) | Jun 01, 2021 |
| Dell          | XPS 13 9300                 | [024ffa0922](https://linux-hardware.org/?probe=024ffa0922) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [052b95ba1d](https://linux-hardware.org/?probe=052b95ba1d) | May 27, 2021 |
| Dell          | Inspiron 5415               | [bbf1e95976](https://linux-hardware.org/?probe=bbf1e95976) | May 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| Dell          | Inspiron 5415               | [abc4464787](https://linux-hardware.org/?probe=abc4464787) | May 26, 2021 |
| Dell          | Inspiron 5415               | [27c5c40e12](https://linux-hardware.org/?probe=27c5c40e12) | May 26, 2021 |
| Lenovo        | ThinkPad X230 2325BF1       | [0d334af224](https://linux-hardware.org/?probe=0d334af224) | May 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e1cf7f4599](https://linux-hardware.org/?probe=e1cf7f4599) | May 24, 2021 |
| Toshiba       | Satellite A200              | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| ASUSTek       | X550ZA                      | [aef8ea73d8](https://linux-hardware.org/?probe=aef8ea73d8) | May 20, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [089c319771](https://linux-hardware.org/?probe=089c319771) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | [8a05529e0c](https://linux-hardware.org/?probe=8a05529e0c) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | [6daf66a738](https://linux-hardware.org/?probe=6daf66a738) | May 18, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [50b75a0212](https://linux-hardware.org/?probe=50b75a0212) | May 17, 2021 |
| Lenovo        | Yoga 2 13 20344             | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| Samsung       | RC530/RC730                 | [1da22350d7](https://linux-hardware.org/?probe=1da22350d7) | May 15, 2021 |
| HP            | Unknown                     | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| Dell          | Inspiron 3135               | [2773a72a9b](https://linux-hardware.org/?probe=2773a72a9b) | May 10, 2021 |
| HP            | ProBook 445 G7              | [6c504fbdf0](https://linux-hardware.org/?probe=6c504fbdf0) | May 10, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [5b8198d382](https://linux-hardware.org/?probe=5b8198d382) | May 08, 2021 |
| Dell          | Inspiron 3135               | [9bcfced245](https://linux-hardware.org/?probe=9bcfced245) | May 07, 2021 |
| Dell          | XPS 13 9310                 | [c3e8ad6826](https://linux-hardware.org/?probe=c3e8ad6826) | May 07, 2021 |
| HP            | Laptop 15-dw2xxx            | [0b4a5c33ef](https://linux-hardware.org/?probe=0b4a5c33ef) | May 06, 2021 |
| Dell          | G3 3500                     | [f6624959c4](https://linux-hardware.org/?probe=f6624959c4) | May 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1d95f1feca](https://linux-hardware.org/?probe=1d95f1feca) | May 02, 2021 |
| Toshiba       | NB100                       | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| Dell          | Inspiron 3542               | [aa72a49a15](https://linux-hardware.org/?probe=aa72a49a15) | Apr 30, 2021 |
| Lenovo        | ThinkPad P50 20EN0006UK     | [6f9d0f45bb](https://linux-hardware.org/?probe=6f9d0f45bb) | Apr 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0bbb4df743](https://linux-hardware.org/?probe=0bbb4df743) | Apr 27, 2021 |
| Dell          | XPS 17 9700                 | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| Dell          | G3 3500                     | [d1a4723065](https://linux-hardware.org/?probe=d1a4723065) | Apr 20, 2021 |
| Dell          | G3 3500                     | [3295e38ea9](https://linux-hardware.org/?probe=3295e38ea9) | Apr 20, 2021 |
| Dell          | XPS 17 9700                 | [84387a75f7](https://linux-hardware.org/?probe=84387a75f7) | Apr 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b10d744c6c](https://linux-hardware.org/?probe=b10d744c6c) | Apr 18, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [6d94f31cd6](https://linux-hardware.org/?probe=6d94f31cd6) | Apr 14, 2021 |
| Fujitsu       | LIFEBOOK T901               | [cb4c0ac9a9](https://linux-hardware.org/?probe=cb4c0ac9a9) | Apr 13, 2021 |
| TUXEDO        | N24_25BU                    | [32cc7aa6c2](https://linux-hardware.org/?probe=32cc7aa6c2) | Apr 12, 2021 |
| HP            | Pavilion Notebook           | [5159073240](https://linux-hardware.org/?probe=5159073240) | Apr 11, 2021 |
| HP            | Pavilion Notebook           | [99daea7567](https://linux-hardware.org/?probe=99daea7567) | Apr 11, 2021 |
| Dell          | G3 3500                     | [3510f864f1](https://linux-hardware.org/?probe=3510f864f1) | Apr 10, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 244       | 27.38%  |
| Gentoo 2.6     | 200       | 22.45%  |
| Gentoo 2.8     | 156       | 17.51%  |
| Gentoo 2.13    | 101       | 11.34%  |
| Gentoo 2.14    | 85        | 9.54%   |
| Gentoo 2.9     | 76        | 8.53%   |
| Gentoo         | 7         | 0.79%   |
| Gentoo 2.4.1   | 5         | 0.56%   |
| Gentoo 2.3     | 4         | 0.45%   |
| Gentoo 2.2     | 4         | 0.45%   |
| Gentoo 23      | 3         | 0.34%   |
| Gentoo Pelikan | 1         | 0.11%   |
| Gentoo 22      | 1         | 0.11%   |
| Gentoo 2022    | 1         | 0.11%   |
| Gentoo 20.04   | 1         | 0.11%   |
| Gentoo 2.1     | 1         | 0.11%   |
| Gentoo 1       | 1         | 0.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Gentoo | 769       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.27-gentoo           | 16        | 1.58%   |
| 5.10.61-gentoo           | 13        | 1.29%   |
| 5.4.38-gentoo            | 11        | 1.09%   |
| 5.15.80-gentoo-x86_64    | 10        | 0.99%   |
| 5.4.80-gentoo-r1         | 9         | 0.89%   |
| 5.4.48-gentoo            | 9         | 0.89%   |
| 5.15.32-gentoo-r1        | 9         | 0.89%   |
| 5.10.76-gentoo-r1        | 9         | 0.89%   |
| 6.1.57-gentoo-x86_64     | 7         | 0.69%   |
| 6.1.19-gentoo-x86_64     | 7         | 0.69%   |
| 5.15.80-gentoo           | 7         | 0.69%   |
| 5.10.76-gentoo-r1-x86_64 | 7         | 0.69%   |
| 5.15.75-gentoo-x86_64    | 6         | 0.59%   |
| 5.15.59-gentoo-x86_64    | 6         | 0.59%   |
| 5.10.52-gentoo           | 6         | 0.59%   |
| 5.10.27-gentoo-x86_64    | 6         | 0.59%   |
| 6.1.46-gentoo            | 5         | 0.49%   |
| 6.1.41-gentoo-dist       | 5         | 0.49%   |
| 6.1.31-gentoo-dist       | 5         | 0.49%   |
| 6.1.12-gentoo-dist       | 5         | 0.49%   |
| 5.4.97-gentoo            | 5         | 0.49%   |
| 5.4.60-gentoo            | 5         | 0.49%   |
| 5.4.28-gentoo            | 5         | 0.49%   |
| 5.15.75-gentoo           | 5         | 0.49%   |
| 5.15.72-gentoo-x86_64    | 5         | 0.49%   |
| 5.15.72-gentoo           | 5         | 0.49%   |
| 5.15.52-gentoo           | 5         | 0.49%   |
| 5.15.32-gentoo-r1-x86_64 | 5         | 0.49%   |
| 5.10.61-gentoo-x86_64    | 5         | 0.49%   |
| 6.1.57-gentoo-dist       | 4         | 0.4%    |
| 6.1.57-gentoo            | 4         | 0.4%    |
| 6.1.19-gentoo            | 4         | 0.4%    |
| 6.1.12-gentoo            | 4         | 0.4%    |
| 5.8.0-gentoo-r1          | 4         | 0.4%    |
| 5.4.97-gentoo-x86_64     | 4         | 0.4%    |
| 5.4.48-gentoo-x86_64     | 4         | 0.4%    |
| 5.19.0-gentoo-x86_64     | 4         | 0.4%    |
| 5.15.88-gentoo-x86_64    | 4         | 0.4%    |
| 5.15.88-gentoo           | 4         | 0.4%    |
| 5.15.69-gentoo           | 4         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.27 | 25        | 2.48%   |
| 5.10.76 | 21        | 2.08%   |
| 5.4.48  | 20        | 1.98%   |
| 5.10.61 | 19        | 1.88%   |
| 6.1.57  | 18        | 1.78%   |
| 5.15.80 | 17        | 1.68%   |
| 5.15.32 | 17        | 1.68%   |
| 5.4.38  | 16        | 1.59%   |
| 6.1.19  | 15        | 1.49%   |
| 6.1.12  | 13        | 1.29%   |
| 5.15.75 | 13        | 1.29%   |
| 5.15.59 | 13        | 1.29%   |
| 6.1.31  | 12        | 1.19%   |
| 5.15.72 | 12        | 1.19%   |
| 6.1.46  | 11        | 1.09%   |
| 5.4.97  | 11        | 1.09%   |
| 5.4.80  | 11        | 1.09%   |
| 5.4.28  | 11        | 1.09%   |
| 5.15.52 | 11        | 1.09%   |
| 5.10.52 | 11        | 1.09%   |
| 6.1.41  | 9         | 0.89%   |
| 6.1.38  | 9         | 0.89%   |
| 5.15.11 | 9         | 0.89%   |
| 6.0.0   | 8         | 0.79%   |
| 5.15.88 | 8         | 0.79%   |
| 5.15.69 | 8         | 0.79%   |
| 5.15.41 | 8         | 0.79%   |
| 4.19.97 | 8         | 0.79%   |
| 5.4.72  | 7         | 0.69%   |
| 5.4.60  | 7         | 0.69%   |
| 5.19.0  | 7         | 0.69%   |
| 5.17.1  | 7         | 0.69%   |
| 5.16.0  | 7         | 0.69%   |
| 6.1.7   | 6         | 0.59%   |
| 6.1.53  | 6         | 0.59%   |
| 5.4.66  | 6         | 0.59%   |
| 5.15.26 | 6         | 0.59%   |
| 5.15.23 | 6         | 0.59%   |
| 5.15.10 | 6         | 0.59%   |
| 6.6.0   | 5         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 167       | 17.88%  |
| 6.1     | 125       | 13.38%  |
| 5.10    | 110       | 11.78%  |
| 5.4     | 102       | 10.92%  |
| 4.19    | 33        | 3.53%   |
| 6.2     | 25        | 2.68%   |
| 6.0     | 25        | 2.68%   |
| 5.17    | 25        | 2.68%   |
| 5.16    | 24        | 2.57%   |
| 5.9     | 23        | 2.46%   |
| 5.6     | 22        | 2.36%   |
| 5.14    | 22        | 2.36%   |
| 6.5     | 21        | 2.25%   |
| 5.18    | 20        | 2.14%   |
| 5.8     | 19        | 2.03%   |
| 5.11    | 19        | 2.03%   |
| 5.12    | 17        | 1.82%   |
| 5.7     | 16        | 1.71%   |
| 5.19    | 16        | 1.71%   |
| 6.4     | 15        | 1.61%   |
| 6.6     | 14        | 1.5%    |
| 5.13    | 13        | 1.39%   |
| 6.3     | 11        | 1.18%   |
| 4.14    | 8         | 0.86%   |
| 5.5     | 7         | 0.75%   |
| 5.3     | 5         | 0.54%   |
| 5.1     | 5         | 0.54%   |
| 4.4     | 5         | 0.54%   |
| 5.2     | 3         | 0.32%   |
| 4.9     | 3         | 0.32%   |
| 4.18    | 3         | 0.32%   |
| 5.0     | 2         | 0.21%   |
| 4.6     | 2         | 0.21%   |
| 4.12    | 2         | 0.21%   |
| 6.7     | 1         | 0.11%   |
| 4.5     | 1         | 0.11%   |
| 4.20    | 1         | 0.11%   |
| 4.10    | 1         | 0.11%   |
| 4.1     | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 744       | 96.75%  |
| i686   | 22        | 2.86%   |
| ppc    | 3         | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 324       | 39.13%  |
| KDE5           | 184       | 22.22%  |
| GNOME          | 105       | 12.68%  |
| XFCE           | 69        | 8.33%   |
| MATE           | 25        | 3.02%   |
| KDE            | 25        | 3.02%   |
| DWM            | 20        | 2.42%   |
| LXQt           | 13        | 1.57%   |
| Hyprland       | 9         | 1.09%   |
| sway           | 8         | 0.97%   |
| Xsession       | 5         | 0.6%    |
| LXDE           | 5         | 0.6%    |
| i3             | 5         | 0.6%    |
| awesome        | 5         | 0.6%    |
| bspwm          | 4         | 0.48%   |
| X-Cinnamon     | 3         | 0.36%   |
| Trinity        | 3         | 0.36%   |
| openbox        | 3         | 0.36%   |
| Enlightenment  | 2         | 0.24%   |
| Cinnamon       | 2         | 0.24%   |
| xmonad         | 1         | 0.12%   |
| ratpoison      | 1         | 0.12%   |
| qt5ct          | 1         | 0.12%   |
| LeftWM         | 1         | 0.12%   |
| ICEWM          | 1         | 0.12%   |
| i3-with-shmlog | 1         | 0.12%   |
| GNOME Classic  | 1         | 0.12%   |
| fvwm           | 1         | 0.12%   |
| fluxbox        | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 455       | 54.82%  |
| Wayland | 134       | 16.14%  |
| Unknown | 124       | 14.94%  |
| Tty     | 117       | 14.1%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 360       | 44.55%  |
| SDDM    | 229       | 28.34%  |
| LightDM | 91        | 11.26%  |
| GDM     | 75        | 9.28%   |
| SLiM    | 16        | 1.98%   |
| XDM     | 15        | 1.86%   |
| LXDM    | 7         | 0.87%   |
| GREETD  | 7         | 0.87%   |
| TDM     | 5         | 0.62%   |
| Ly      | 1         | 0.12%   |
| KDM     | 1         | 0.12%   |
| GDM3    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 310       | 38.04%  |
| Unknown    | 126       | 15.46%  |
| C.UTF8     | 73        | 8.96%   |
| en_GB      | 45        | 5.52%   |
| de_DE      | 40        | 4.91%   |
| ru_RU      | 36        | 4.42%   |
| fr_FR      | 22        | 2.7%    |
| C          | 21        | 2.58%   |
| it_IT      | 14        | 1.72%   |
| cs_CZ      | 14        | 1.72%   |
| en_AU      | 12        | 1.47%   |
| zh_CN      | 9         | 1.1%    |
| en_CA      | 8         | 0.98%   |
| pl_PL      | 7         | 0.86%   |
| es_ES      | 7         | 0.86%   |
| pt_BR      | 5         | 0.61%   |
| POSIX      | 5         | 0.61%   |
| el_GR      | 5         | 0.61%   |
| es_AR      | 4         | 0.49%   |
| uk_UA      | 3         | 0.37%   |
| nl_NL      | 3         | 0.37%   |
| nl_BE      | 3         | 0.37%   |
| ja_JP      | 3         | 0.37%   |
| fr_CA      | 3         | 0.37%   |
| es_CL      | 3         | 0.37%   |
| en_IE      | 3         | 0.37%   |
| de_CH      | 3         | 0.37%   |
| mi_NZ      | 2         | 0.25%   |
| en_ZA      | 2         | 0.25%   |
| en_US.UTF8 | 2         | 0.25%   |
| en_MX      | 2         | 0.25%   |
| ca_ES      | 2         | 0.25%   |
| zh_TW      | 1         | 0.12%   |
| tr_TR.UTF8 | 1         | 0.12%   |
| tr_TR      | 1         | 0.12%   |
| sv_SE      | 1         | 0.12%   |
| ru_UA      | 1         | 0.12%   |
| ro_RO      | 1         | 0.12%   |
| lt_LT      | 1         | 0.12%   |
| ko_KR      | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 612       | 78.16%  |
| BIOS | 171       | 21.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 456       | 58.31%  |
| Btrfs    | 203       | 25.96%  |
| Xfs      | 35        | 4.48%   |
| Unknown  | 23        | 2.94%   |
| F2fs     | 21        | 2.69%   |
| Zfs      | 20        | 2.56%   |
| XXXXXXX  | 13        | 1.66%   |
| Reiserfs | 3         | 0.38%   |
| Jfs      | 2         | 0.26%   |
| Ext3     | 2         | 0.26%   |
| Bcachefs | 2         | 0.26%   |
| Overlay  | 1         | 0.13%   |
| Ext2     | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 660       | 84.83%  |
| MBR     | 78        | 10.03%  |
| Unknown | 40        | 5.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 605       | 75.81%  |
| Yes       | 193       | 24.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 547       | 69.33%  |
| Yes       | 242       | 30.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 211       | 27.44%  |
| Dell                | 131       | 17.04%  |
| Hewlett-Packard     | 113       | 14.69%  |
| ASUSTek Computer    | 88        | 11.44%  |
| Acer                | 45        | 5.85%   |
| MSI                 | 24        | 3.12%   |
| Apple               | 22        | 2.86%   |
| Timi                | 12        | 1.56%   |
| HUAWEI              | 12        | 1.56%   |
| Toshiba             | 9         | 1.17%   |
| Samsung Electronics | 8         | 1.04%   |
| Unknown             | 8         | 1.04%   |
| TUXEDO              | 7         | 0.91%   |
| Framework           | 7         | 0.91%   |
| Razer               | 5         | 0.65%   |
| IBM                 | 5         | 0.65%   |
| Google              | 5         | 0.65%   |
| System76            | 4         | 0.52%   |
| Notebook            | 4         | 0.52%   |
| Fujitsu             | 4         | 0.52%   |
| Sony                | 3         | 0.39%   |
| Alienware           | 3         | 0.39%   |
| win element         | 2         | 0.26%   |
| Valve               | 2         | 0.26%   |
| Star Labs           | 2         | 0.26%   |
| Schenker            | 2         | 0.26%   |
| Purism              | 2         | 0.26%   |
| Positivo            | 2         | 0.26%   |
| Medion              | 2         | 0.26%   |
| Jumper              | 2         | 0.26%   |
| Gigabyte Technology | 2         | 0.26%   |
| Chuwi               | 2         | 0.26%   |
| BANGHO              | 2         | 0.26%   |
| XMG                 | 1         | 0.13%   |
| Wortmann AG         | 1         | 0.13%   |
| TULPAR              | 1         | 0.13%   |
| SIEMENS             | 1         | 0.13%   |
| Seco                | 1         | 0.13%   |
| realme              | 1         | 0.13%   |
| PC Specialist       | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 15        | 1.95%   |
| Dell XPS 15 9570                       | 6         | 0.78%   |
| ASUS ROG Strix G513QY_G513QY           | 6         | 0.78%   |
| HP Pavilion Notebook                   | 5         | 0.65%   |
| HP OMEN by Laptop                      | 5         | 0.65%   |
| HP Pavilion Gaming Laptop 15-ec1xxx    | 4         | 0.52%   |
| HP Laptop 14-dk1xxx                    | 4         | 0.52%   |
| Framework Laptop (13th Gen Intel Core) | 4         | 0.52%   |
| Dell XPS 17 9710                       | 4         | 0.52%   |
| Dell XPS 15 7590                       | 4         | 0.52%   |
| Dell XPS 13 9310                       | 4         | 0.52%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II  | 4         | 0.52%   |
| Timi RedmiBook Pro 15S                 | 3         | 0.39%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE   | 3         | 0.39%   |
| Lenovo Legion Y530-15ICH 81FV          | 3         | 0.39%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ       | 3         | 0.39%   |
| Dell XPS 9320                          | 3         | 0.39%   |
| Dell XPS 13 9370                       | 3         | 0.39%   |
| Dell XPS 13 9360                       | 3         | 0.39%   |
| Dell Latitude E7440                    | 3         | 0.39%   |
| Dell Latitude 7390                     | 3         | 0.39%   |
| Dell G5 5505                           | 3         | 0.39%   |
| win element MoreFine S500+             | 2         | 0.26%   |
| Valve Jupiter                          | 2         | 0.26%   |
| Toshiba Satellite C850D-118            | 2         | 0.26%   |
| Toshiba NB100                          | 2         | 0.26%   |
| Timi RedmiBook 13 R                    | 2         | 0.26%   |
| Sony PCG-GRT230(UC)                    | 2         | 0.26%   |
| MSI GS65 Stealth Thin 8RF              | 2         | 0.26%   |
| MSI GS63VR 6RF                         | 2         | 0.26%   |
| Lenovo Yoga 2 13 20344                 | 2         | 0.26%   |
| Lenovo ThinkPad T480 20L5CTO1WW        | 2         | 0.26%   |
| Lenovo ThinkPad T470p 20J7S25C00       | 2         | 0.26%   |
| Lenovo ThinkPad P51 20HHCTO1WW         | 2         | 0.26%   |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB   | 2         | 0.26%   |
| Lenovo ThinkPad E14 Gen 4 21EBCTO1WW   | 2         | 0.26%   |
| Lenovo Legion Y540-15IRH 81SX          | 2         | 0.26%   |
| Lenovo Legion R7000 2020 82B6          | 2         | 0.26%   |
| Lenovo IdeaPad 5 15ITL05 82FG          | 2         | 0.26%   |
| Lenovo IdeaPad 5 15ABA7 82SG           | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 131       | 17.04%  |
| Dell Latitude        | 45        | 5.85%   |
| Dell XPS             | 38        | 4.94%   |
| HP EliteBook         | 27        | 3.51%   |
| Lenovo IdeaPad       | 26        | 3.38%   |
| Lenovo Legion        | 25        | 3.25%   |
| Acer Aspire          | 24        | 3.12%   |
| HP Pavilion          | 23        | 2.99%   |
| ASUS ROG             | 21        | 2.73%   |
| Dell Inspiron        | 19        | 2.47%   |
| HP Laptop            | 17        | 2.21%   |
| Dell Precision       | 17        | 2.21%   |
| ASUS VivoBook        | 15        | 1.95%   |
| Unknown              | 15        | 1.95%   |
| HP OMEN              | 12        | 1.56%   |
| HP ProBook           | 11        | 1.43%   |
| ASUS ZenBook         | 10        | 1.3%    |
| Lenovo Yoga          | 9         | 1.17%   |
| Acer Swift           | 9         | 1.17%   |
| Toshiba Satellite    | 7         | 0.91%   |
| Timi RedmiBook       | 7         | 0.91%   |
| HP ZBook             | 7         | 0.91%   |
| Framework Laptop     | 7         | 0.91%   |
| Acer Nitro           | 7         | 0.91%   |
| ASUS ASUS            | 6         | 0.78%   |
| Razer Blade          | 5         | 0.65%   |
| Lenovo ThinkBook     | 5         | 0.65%   |
| Apple MacBookPro8    | 5         | 0.65%   |
| Apple MacBookPro11   | 5         | 0.65%   |
| IBM ThinkPad         | 4         | 0.52%   |
| HP Victus            | 4         | 0.52%   |
| Dell G5              | 4         | 0.52%   |
| Timi Mi              | 3         | 0.39%   |
| HP 255               | 3         | 0.39%   |
| Fujitsu LIFEBOOK     | 3         | 0.39%   |
| Dell Vostro          | 3         | 0.39%   |
| Dell G3              | 3         | 0.39%   |
| ASUS TUF             | 3         | 0.39%   |
| win element MoreFine | 2         | 0.26%   |
| Valve Jupiter        | 2         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 119       | 15.47%  |
| 2019    | 113       | 14.69%  |
| 2021    | 104       | 13.52%  |
| 2018    | 79        | 10.27%  |
| 2022    | 52        | 6.76%   |
| 2017    | 41        | 5.33%   |
| 2014    | 41        | 5.33%   |
| 2012    | 36        | 4.68%   |
| 2015    | 29        | 3.77%   |
| 2016    | 27        | 3.51%   |
| 2011    | 26        | 3.38%   |
| 2013    | 21        | 2.73%   |
| 2023    | 20        | 2.6%    |
| 2010    | 18        | 2.34%   |
| 2008    | 14        | 1.82%   |
| 2006    | 7         | 0.91%   |
| 2009    | 5         | 0.65%   |
| Unknown | 5         | 0.65%   |
| 2007    | 4         | 0.52%   |
| 2005    | 3         | 0.39%   |
| 2004    | 3         | 0.39%   |
| 2003    | 2         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 769       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 758       | 98.06%  |
| Enabled  | 15        | 1.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 757       | 98.44%  |
| Yes  | 12        | 1.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 184       | 23.32%  |
| 8.01-16.0   | 178       | 22.56%  |
| 4.01-8.0    | 144       | 18.25%  |
| 32.01-64.0  | 134       | 16.98%  |
| 3.01-4.0    | 49        | 6.21%   |
| 64.01-256.0 | 32        | 4.06%   |
| 24.01-32.0  | 27        | 3.42%   |
| 1.01-2.0    | 16        | 2.03%   |
| 2.01-3.0    | 14        | 1.77%   |
| 0.51-1.0    | 8         | 1.01%   |
| 0.01-0.5    | 3         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 230       | 25.25%  |
| 2.01-3.0   | 153       | 16.79%  |
| 4.01-8.0   | 146       | 16.03%  |
| 3.01-4.0   | 109       | 11.96%  |
| 0.01-0.5   | 95        | 10.43%  |
| 0.51-1.0   | 94        | 10.32%  |
| 8.01-16.0  | 74        | 8.12%   |
| 16.01-24.0 | 7         | 0.77%   |
| 32.01-64.0 | 2         | 0.22%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 553       | 69.56%  |
| 2       | 208       | 26.16%  |
| 3       | 25        | 3.14%   |
| 0       | 5         | 0.63%   |
| 4       | 3         | 0.38%   |
| Unknown | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 655       | 84.08%  |
| Yes       | 124       | 15.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 599       | 76.89%  |
| No        | 180       | 23.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 759       | 98.7%   |
| No        | 10        | 1.3%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 673       | 86.62%  |
| No        | 104       | 13.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 150       | 19.13%  |
| Germany      | 94        | 11.99%  |
| Russia       | 70        | 8.93%   |
| France       | 41        | 5.23%   |
| China        | 34        | 4.34%   |
| Canada       | 33        | 4.21%   |
| UK           | 31        | 3.95%   |
| Czechia      | 25        | 3.19%   |
| Poland       | 24        | 3.06%   |
| Italy        | 24        | 3.06%   |
| Spain        | 21        | 2.68%   |
| Netherlands  | 21        | 2.68%   |
| Australia    | 17        | 2.17%   |
| Ukraine      | 13        | 1.66%   |
| Sweden       | 12        | 1.53%   |
| Turkey       | 11        | 1.4%    |
| Greece       | 10        | 1.28%   |
| Switzerland  | 9         | 1.15%   |
| Brazil       | 9         | 1.15%   |
| Belgium      | 9         | 1.15%   |
| Finland      | 8         | 1.02%   |
| Mexico       | 7         | 0.89%   |
| Japan        | 7         | 0.89%   |
| India        | 7         | 0.89%   |
| Romania      | 6         | 0.77%   |
| Norway       | 6         | 0.77%   |
| Hong Kong    | 6         | 0.77%   |
| Slovakia     | 5         | 0.64%   |
| Portugal     | 5         | 0.64%   |
| Indonesia    | 5         | 0.64%   |
| Belarus      | 5         | 0.64%   |
| Austria      | 5         | 0.64%   |
| New Zealand  | 4         | 0.51%   |
| Lithuania    | 4         | 0.51%   |
| Hungary      | 4         | 0.51%   |
| Argentina    | 4         | 0.51%   |
| Taiwan       | 3         | 0.38%   |
| South Africa | 3         | 0.38%   |
| Iran         | 3         | 0.38%   |
| Chile        | 3         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 27        | 3.13%   |
| Moscow            | 24        | 2.78%   |
| Sydney            | 10        | 1.16%   |
| St Petersburg     | 10        | 1.16%   |
| Athens            | 10        | 1.16%   |
| Milan             | 9         | 1.04%   |
| Amsterdam         | 9         | 1.04%   |
| Warsaw            | 7         | 0.81%   |
| Vancouver         | 7         | 0.81%   |
| Prague            | 7         | 0.81%   |
| Munich            | 7         | 0.81%   |
| Kyiv              | 7         | 0.81%   |
| Guangzhou         | 7         | 0.81%   |
| Paris             | 6         | 0.7%    |
| Madrid            | 6         | 0.7%    |
| Los Angeles       | 6         | 0.7%    |
| Weatherford       | 5         | 0.58%   |
| New York          | 5         | 0.58%   |
| Minsk             | 5         | 0.58%   |
| Istanbul          | 5         | 0.58%   |
| Cieszyn           | 5         | 0.58%   |
| Beijing           | 5         | 0.58%   |
| Šlapanice        | 4         | 0.46%   |
| Melbourne         | 4         | 0.46%   |
| London            | 4         | 0.46%   |
| Helsinki          | 4         | 0.46%   |
| Frankfurt am Main | 4         | 0.46%   |
| Bratislava        | 4         | 0.46%   |
| Wuelfrath         | 3         | 0.35%   |
| Vilnius           | 3         | 0.35%   |
| Vienna            | 3         | 0.35%   |
| Toulouse          | 3         | 0.35%   |
| Taganrog          | 3         | 0.35%   |
| Sun Prairie       | 3         | 0.35%   |
| Stockholm         | 3         | 0.35%   |
| Shenzhen          | 3         | 0.35%   |
| Seattle           | 3         | 0.35%   |
| San Jose          | 3         | 0.35%   |
| Rome              | 3         | 0.35%   |
| Pittsburgh        | 3         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 234       | 390    | 23.59%  |
| WDC                         | 109       | 151    | 10.99%  |
| Sandisk                     | 73        | 100    | 7.36%   |
| SK hynix                    | 67        | 85     | 6.75%   |
| Intel                       | 62        | 103    | 6.25%   |
| Seagate                     | 61        | 88     | 6.15%   |
| Toshiba                     | 50        | 58     | 5.04%   |
| Micron Technology           | 37        | 46     | 3.73%   |
| Kingston                    | 37        | 51     | 3.73%   |
| Unknown                     | 36        | 47     | 3.63%   |
| HGST                        | 31        | 35     | 3.13%   |
| KIOXIA                      | 21        | 29     | 2.12%   |
| Crucial                     | 19        | 23     | 1.92%   |
| Hitachi                     | 13        | 13     | 1.31%   |
| Phison Electronics          | 12        | 13     | 1.21%   |
| Apple                       | 11        | 13     | 1.11%   |
| Kingston Technology Company | 9         | 10     | 0.91%   |
| A-DATA Technology           | 9         | 15     | 0.91%   |
| China                       | 7         | 16     | 0.71%   |
| Fujitsu                     | 6         | 8      | 0.6%    |
| OCZ                         | 5         | 9      | 0.5%    |
| Phison                      | 4         | 4      | 0.4%    |
| LITEON                      | 4         | 8      | 0.4%    |
| Transcend                   | 3         | 6      | 0.3%    |
| Micron/Crucial Technology   | 3         | 5      | 0.3%    |
| Lenovo                      | 3         | 5      | 0.3%    |
| IBM/Hitachi                 | 3         | 4      | 0.3%    |
| Yangtze Memory Technologies | 2         | 2      | 0.2%    |
| XPG                         | 2         | 3      | 0.2%    |
| Solid State Storage         | 2         | 2      | 0.2%    |
| Plextor                     | 2         | 2      | 0.2%    |
| Netac                       | 2         | 2      | 0.2%    |
| MyDigitalSSD                | 2         | 2      | 0.2%    |
| LITEONIT                    | 2         | 3      | 0.2%    |
| Lexar                       | 2         | 2      | 0.2%    |
| KIOXIA-EXCERIA              | 2         | 5      | 0.2%    |
| Intenso                     | 2         | 2      | 0.2%    |
| GOODRAM                     | 2         | 2      | 0.2%    |
| Dogfish                     | 2         | 2      | 0.2%    |
| ADATA Technology            | 2         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 32        | 3.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 22        | 2.07%   |
| HGST HTS721010A9E630 1TB                            | 20        | 1.88%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 10        | 0.94%   |
| Intel SSDPEKNW010T8 1TB                             | 10        | 0.94%   |
| Intel SSDPEKNU512GZ 512GB                           | 10        | 0.94%   |
| Seagate ST1000LM035-1RK172 1TB                      | 9         | 0.85%   |
| Samsung SSD 980 1TB                                 | 9         | 0.85%   |
| Samsung SSD 860 EVO 500GB                           | 8         | 0.75%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.75%   |
| Samsung MZVLB512HBJQ-000L2 512GB                    | 8         | 0.75%   |
| Intel SSD 660P Series 512GB                         | 8         | 0.75%   |
| Seagate ST1000LM049-2GH172 1TB                      | 7         | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 7         | 0.66%   |
| Unknown MMC Card  128GB                             | 6         | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.56%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 6         | 0.56%   |
| KIOXIA KBG40ZNV512G 512GB                           | 6         | 0.56%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 5         | 0.47%   |
| Unknown MMC Card  32GB                              | 5         | 0.47%   |
| Unknown MMC Card  16GB                              | 5         | 0.47%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 0.47%   |
| SK hynix PC711 NVMe 1TB                             | 5         | 0.47%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 5         | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.47%   |
| Sandisk WD Black SN850 1024GB                       | 5         | 0.47%   |
| Samsung SSD 980 PRO 2TB                             | 5         | 0.47%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 0.47%   |
| Samsung NVMe SSD Drive 512GB                        | 5         | 0.47%   |
| Kingston SA400S37480G 480GB SSD                     | 5         | 0.47%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 0.47%   |
| HGST HTS541010A9E680 1TB                            | 5         | 0.47%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 4         | 0.38%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 4         | 0.38%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                  | 4         | 0.38%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 0.38%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.38%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 4         | 0.38%   |
| Seagate ST2000LX001-1RG174 2TB                      | 4         | 0.38%   |
| Seagate ST2000LM015-2E8174 2TB                      | 4         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 85     | 31.87%  |
| WDC                 | 41        | 48     | 22.53%  |
| HGST                | 31        | 35     | 17.03%  |
| Toshiba             | 24        | 28     | 13.19%  |
| Hitachi             | 13        | 13     | 7.14%   |
| Fujitsu             | 6         | 8      | 3.3%    |
| IBM/Hitachi         | 3         | 4      | 1.65%   |
| Teleplan            | 1         | 4      | 0.55%   |
| StoreJet            | 1         | 1      | 0.55%   |
| Samsung Electronics | 1         | 2      | 0.55%   |
| HGST HTS            | 1         | 1      | 0.55%   |
| ASMT                | 1         | 2      | 0.55%   |
| Apple               | 1         | 1      | 0.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 83        | 122    | 29.12%  |
| SanDisk             | 30        | 42     | 10.53%  |
| Kingston            | 22        | 31     | 7.72%   |
| WDC                 | 17        | 31     | 5.96%   |
| Crucial             | 16        | 20     | 5.61%   |
| Intel               | 14        | 14     | 4.91%   |
| SK hynix            | 13        | 14     | 4.56%   |
| Micron Technology   | 9         | 14     | 3.16%   |
| A-DATA Technology   | 9         | 15     | 3.16%   |
| Apple               | 8         | 9      | 2.81%   |
| Toshiba             | 7         | 8      | 2.46%   |
| China               | 7         | 16     | 2.46%   |
| OCZ                 | 5         | 9      | 1.75%   |
| Transcend           | 2         | 5      | 0.7%    |
| Seagate             | 2         | 2      | 0.7%    |
| Plextor             | 2         | 2      | 0.7%    |
| Netac               | 2         | 2      | 0.7%    |
| MyDigitalSSD        | 2         | 2      | 0.7%    |
| LITEONIT            | 2         | 3      | 0.7%    |
| Lexar               | 2         | 2      | 0.7%    |
| Intenso             | 2         | 2      | 0.7%    |
| GOODRAM             | 2         | 2      | 0.7%    |
| Dogfish             | 2         | 2      | 0.7%    |
| Zheino              | 1         | 1      | 0.35%   |
| XrayDisk            | 1         | 1      | 0.35%   |
| Verbatim            | 1         | 1      | 0.35%   |
| Star                | 1         | 1      | 0.35%   |
| SPCC                | 1         | 1      | 0.35%   |
| Smartbuy            | 1         | 1      | 0.35%   |
| ShanDianZhe         | 1         | 2      | 0.35%   |
| RevuAhn             | 1         | 1      | 0.35%   |
| PNY                 | 1         | 2      | 0.35%   |
| Phison              | 1         | 1      | 0.35%   |
| Mushkin             | 1         | 1      | 0.35%   |
| LITEON              | 1         | 3      | 0.35%   |
| Lite-On             | 1         | 1      | 0.35%   |
| Linux               | 1         | 1      | 0.35%   |
| Lenovo              | 1         | 2      | 0.35%   |
| Kingmax             | 1         | 1      | 0.35%   |
| KingDian            | 1         | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 457       | 732    | 49.3%   |
| SSD     | 257       | 401    | 27.72%  |
| HDD     | 175       | 232    | 18.88%  |
| MMC     | 35        | 44     | 3.78%   |
| Unknown | 3         | 5      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 457       | 729    | 51.46%  |
| SATA | 376       | 614    | 42.34%  |
| MMC  | 35        | 44     | 3.94%   |
| SAS  | 20        | 27     | 2.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 259       | 390    | 59.68%  |
| 0.51-1.0   | 154       | 207    | 35.48%  |
| 1.01-2.0   | 18        | 32     | 4.15%   |
| 3.01-4.0   | 2         | 3      | 0.46%   |
| 4.01-10.0  | 1         | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 215       | 25.9%   |
| 101-250        | 182       | 21.93%  |
| 501-1000       | 158       | 19.04%  |
| 1001-2000      | 82        | 9.88%   |
| 51-100         | 46        | 5.54%   |
| Unknown        | 45        | 5.42%   |
| 1-20           | 44        | 5.3%    |
| More than 3000 | 22        | 2.65%   |
| 21-50          | 19        | 2.29%   |
| 2001-3000      | 17        | 2.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 211       | 23.81%  |
| 21-50          | 159       | 17.95%  |
| 101-250        | 139       | 15.69%  |
| 251-500        | 121       | 13.66%  |
| 51-100         | 105       | 11.85%  |
| 501-1000       | 72        | 8.13%   |
| Unknown        | 45        | 5.08%   |
| 1001-2000      | 24        | 2.71%   |
| 2001-3000      | 6         | 0.68%   |
| More than 3000 | 4         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Notebooks | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                                  | 6         | 7      | 7.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                        | 3         | 8      | 3.75%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD                   | 3         | 3      | 3.75%   |
| WDC WD10JPVX-75JC3T0 1TB                                  | 2         | 2      | 2.5%    |
| SK hynix HFS256G39TND-N210A 256GB SSD                     | 2         | 2      | 2.5%    |
| Seagate ST2000LX001-1RG174 2TB                            | 2         | 2      | 2.5%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD                       | 2         | 2      | 2.5%    |
| Samsung Electronics SSD 850 EVO 1TB                       | 2         | 2      | 2.5%    |
| HGST HTS725050A7E630 500GB                                | 2         | 3      | 2.5%    |
| WDC WDS120G2G0B-00EPW0 120GB SSD                          | 1         | 1      | 1.25%   |
| WDC WD1600BEVS-22RST0 160GB                               | 1         | 1      | 1.25%   |
| WDC WD10SPZX-24Z10T0 1TB                                  | 1         | 1      | 1.25%   |
| WDC WD10EZEX-08M2NA0 1TB                                  | 1         | 2      | 1.25%   |
| WDC WD Green 2.5 240GB SSD                                | 1         | 1      | 1.25%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD                  | 1         | 1      | 1.25%   |
| Toshiba MQ02ABD100H 1TB                                   | 1         | 1      | 1.25%   |
| Toshiba MQ01ABF050 500GB                                  | 1         | 1      | 1.25%   |
| Toshiba MK6008GAH 64GB                                    | 1         | 2      | 1.25%   |
| Toshiba MK5056GSY 500GB                                   | 1         | 1      | 1.25%   |
| Toshiba MK4026GAX 40GB                                    | 1         | 1      | 1.25%   |
| Toshiba MK1629GSG 160GB                                   | 1         | 1      | 1.25%   |
| SK hynix SH920 mSATA 256GB SSD                            | 1         | 1      | 1.25%   |
| SK hynix SC210 mSATA 128GB SSD                            | 1         | 1      | 1.25%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                      | 1         | 2      | 1.25%   |
| SK hynix BC501 NVMe Solid State Drive 512GB               | 1         | 3      | 1.25%   |
| Seagate ST9750420AS 752GB                                 | 1         | 1      | 1.25%   |
| Seagate ST9100824AS 100GB                                 | 1         | 1      | 1.25%   |
| Seagate ST320LT007-9ZV142 320GB                           | 1         | 1      | 1.25%   |
| Seagate ST1000LM049-2GH172 1TB                            | 1         | 1      | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB                            | 1         | 2      | 1.25%   |
| Seagate ST1000LM014-1EJ164 1TB                            | 1         | 1      | 1.25%   |
| SanDisk SSD PLUS 480GB                                    | 1         | 1      | 1.25%   |
| SanDisk SD9SN8W 128GB SSD                                 | 1         | 1      | 1.25%   |
| SanDisk SD7SB2Q512G1001 512GB SSD                         | 1         | 1      | 1.25%   |
| Samsung Electronics SSD SM841 mSATA 512GB                 | 1         | 1      | 1.25%   |
| Samsung Electronics SSD 870 EVO 2TB                       | 1         | 1      | 1.25%   |
| Samsung Electronics PM9A1 NVMe 2048GB                     | 1         | 1      | 1.25%   |
| Samsung Electronics HM160HC 160GB                         | 1         | 1      | 1.25%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 1         | 2      | 1.25%   |
| OCZ VERTEX4 256GB SSD                                     | 1         | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 11        | 17     | 13.92%  |
| HGST                        | 11        | 13     | 13.92%  |
| WDC                         | 7         | 8      | 8.86%   |
| Toshiba                     | 7         | 8      | 8.86%   |
| SK hynix                    | 6         | 9      | 7.59%   |
| Samsung Electronics         | 6         | 6      | 7.59%   |
| Intel                       | 6         | 6      | 7.59%   |
| Hitachi                     | 5         | 5      | 6.33%   |
| SanDisk                     | 4         | 5      | 5.06%   |
| Kingston                    | 3         | 3      | 3.8%    |
| Fujitsu                     | 3         | 3      | 3.8%    |
| IBM/Hitachi                 | 2         | 2      | 2.53%   |
| A-DATA Technology           | 2         | 2      | 2.53%   |
| Realtek Semiconductor       | 1         | 2      | 1.27%   |
| OCZ                         | 1         | 1      | 1.27%   |
| LITEON                      | 1         | 3      | 1.27%   |
| Kingston Technology Company | 1         | 1      | 1.27%   |
| HGST HTS                    | 1         | 1      | 1.27%   |
| Crucial                     | 1         | 1      | 1.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 17     | 24.44%  |
| HGST                | 11        | 13     | 24.44%  |
| Toshiba             | 6         | 7      | 13.33%  |
| WDC                 | 5         | 6      | 11.11%  |
| Hitachi             | 5         | 5      | 11.11%  |
| Fujitsu             | 3         | 3      | 6.67%   |
| IBM/Hitachi         | 2         | 2      | 4.44%   |
| Samsung Electronics | 1         | 1      | 2.22%   |
| HGST HTS            | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 55     | 56.96%  |
| SSD  | 27        | 30     | 34.18%  |
| NVMe | 7         | 11     | 8.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB  | 1         | 1      | 33.33%  |
| Hitachi HTS721010G9SA00 100GB    | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 658       | 1168   | 78.33%  |
| Detected | 102       | 147    | 12.14%  |
| Malfunc  | 77        | 96     | 9.17%   |
| Failed   | 3         | 3      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 438       | 43.84%  |
| Samsung Electronics              | 172       | 17.22%  |
| AMD                              | 99        | 9.91%   |
| SanDisk                          | 89        | 8.91%   |
| SK hynix                         | 54        | 5.41%   |
| Micron Technology                | 28        | 2.8%    |
| Kingston Technology Company      | 25        | 2.5%    |
| Toshiba America Info Systems     | 22        | 2.2%    |
| KIOXIA                           | 21        | 2.1%    |
| Phison Electronics               | 15        | 1.5%    |
| Micron/Crucial Technology        | 5         | 0.5%    |
| Solid State Storage Technology   | 3         | 0.3%    |
| Lite-On Technology               | 3         | 0.3%    |
| ADATA Technology                 | 3         | 0.3%    |
| Yangtze Memory Technologies      | 2         | 0.2%    |
| Union Memory (Shenzhen)          | 2         | 0.2%    |
| Silicon Motion                   | 2         | 0.2%    |
| Silicon Integrated Systems [SiS] | 2         | 0.2%    |
| Nvidia                           | 2         | 0.2%    |
| Lenovo                           | 2         | 0.2%    |
| JMicron Technology               | 2         | 0.2%    |
| INNOGRIT                         | 2         | 0.2%    |
| Apple                            | 2         | 0.2%    |
| Transcend                        | 1         | 0.1%    |
| Seagate Technology               | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 94        | 8.96%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 91        | 8.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 51        | 4.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 42        | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 38        | 3.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 36        | 3.43%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 30        | 2.86%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 29        | 2.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 2.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 27        | 2.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 27        | 2.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 27        | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 24        | 2.29%   |
| Intel SSD 660P Series                                                          | 23        | 2.19%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 20        | 1.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15        | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 1.43%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 14        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 1.14%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 12        | 1.14%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 11        | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.05%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 10        | 0.95%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 10        | 0.95%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 9         | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 8         | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 8         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.67%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 6         | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 6         | 0.57%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 6         | 0.57%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 6         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 463       | 46.63%  |
| SATA | 423       | 42.6%   |
| RAID | 70        | 7.05%   |
| IDE  | 37        | 3.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 569       | 73.99%  |
| AMD          | 197       | 25.62%  |
| PowerBook5,6 | 1         | 0.13%   |
| PowerBook5,4 | 1         | 0.13%   |
| PowerBook3,4 | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 24        | 3.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 21        | 2.73%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 2.73%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.69%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 1.69%   |
| Intel 12th Gen Core i7-12700H                 | 12        | 1.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 1.43%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 1.43%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 10        | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 1.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 9         | 1.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.17%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 8         | 1.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 1.04%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 7         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.91%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 0.78%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.78%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 6         | 0.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 0.78%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.78%   |
| Intel 12th Gen Core i7-1260P                  | 6         | 0.78%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 6         | 0.78%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.78%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.78%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 5         | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.65%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 229       | 29.78%  |
| Intel Core i5           | 140       | 18.21%  |
| Other                   | 102       | 13.26%  |
| AMD Ryzen 7             | 84        | 10.92%  |
| AMD Ryzen 5             | 38        | 4.94%   |
| AMD Ryzen 7 PRO         | 25        | 3.25%   |
| Intel Core i3           | 15        | 1.95%   |
| Intel Celeron           | 15        | 1.95%   |
| Intel Core 2 Duo        | 14        | 1.82%   |
| AMD Ryzen 9             | 14        | 1.82%   |
| Intel Atom              | 12        | 1.56%   |
| Intel Core i9           | 10        | 1.3%    |
| Intel Pentium M         | 9         | 1.17%   |
| Intel Pentium           | 9         | 1.17%   |
| AMD Ryzen 3             | 8         | 1.04%   |
| AMD Ryzen 5 PRO         | 6         | 0.78%   |
| AMD A6                  | 6         | 0.78%   |
| Intel Xeon              | 5         | 0.65%   |
| Intel Pentium Silver    | 3         | 0.39%   |
| Intel Core m3           | 3         | 0.39%   |
| AMD A8                  | 3         | 0.39%   |
| Intel Pentium 4         | 2         | 0.26%   |
| Intel Genuine           | 2         | 0.26%   |
| Intel Core Duo          | 2         | 0.26%   |
| AMD E1                  | 2         | 0.26%   |
| AMD Athlon II           | 2         | 0.26%   |
| Intel Core 2            | 1         | 0.13%   |
| Intel Celeron M         | 1         | 0.13%   |
| AMD Turion II Dual-Core | 1         | 0.13%   |
| AMD E                   | 1         | 0.13%   |
| AMD Athlon Neo X2       | 1         | 0.13%   |
| AMD Athlon 64           | 1         | 0.13%   |
| AMD Athlon              | 1         | 0.13%   |
| AMD A12                 | 1         | 0.13%   |
| AMD A10                 | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 284       | 36.88%  |
| 2       | 184       | 23.9%   |
| 8       | 137       | 17.79%  |
| 6       | 98        | 12.73%  |
| 1       | 25        | 3.25%   |
| 14      | 24        | 3.12%   |
| 12      | 10        | 1.3%    |
| 16      | 3         | 0.39%   |
| 10      | 2         | 0.26%   |
| Unknown | 2         | 0.26%   |
| 24      | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 767       | 99.74%  |
| Unknown | 2         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 660       | 85.38%  |
| 1       | 110       | 14.23%  |
| Unknown | 2         | 0.26%   |
| 4       | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 742       | 96.49%  |
| 32-bit         | 24        | 3.12%   |
| Unknown        | 3         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 16.56%  |
| 0x906ea    | 51        | 6.35%   |
| 0x0a50000c | 41        | 5.11%   |
| 0x806ec    | 39        | 4.86%   |
| 0x806ea    | 35        | 4.36%   |
| 0x806c1    | 32        | 3.99%   |
| 0x206a7    | 27        | 3.36%   |
| 0x08600106 | 27        | 3.36%   |
| 0x306a9    | 24        | 2.99%   |
| 0x506e3    | 22        | 2.74%   |
| 0x806e9    | 21        | 2.62%   |
| 0xa0652    | 20        | 2.49%   |
| 0x806d1    | 19        | 2.37%   |
| 0x906e9    | 18        | 2.24%   |
| 0x40651    | 18        | 2.24%   |
| 0x08108109 | 18        | 2.24%   |
| 0x906a3    | 17        | 2.12%   |
| 0x406e3    | 16        | 1.99%   |
| 0x08600103 | 14        | 1.74%   |
| 0x306d4    | 13        | 1.62%   |
| 0x306c3    | 13        | 1.62%   |
| 0x906ed    | 11        | 1.37%   |
| 0x08608103 | 10        | 1.25%   |
| 0x08600104 | 10        | 1.25%   |
| 0x08108102 | 10        | 1.25%   |
| 0xb06a2    | 9         | 1.12%   |
| 0x30678    | 9         | 1.12%   |
| 0x0a50000d | 9         | 1.12%   |
| 0x0a404102 | 9         | 1.12%   |
| 0x806eb    | 7         | 0.87%   |
| 0x706e5    | 6         | 0.75%   |
| 0x6d8      | 5         | 0.62%   |
| 0x20655    | 4         | 0.5%    |
| 0x1067a    | 4         | 0.5%    |
| 0x706a1    | 3         | 0.37%   |
| 0x6fb      | 3         | 0.37%   |
| 0x406c4    | 3         | 0.37%   |
| 0x20652    | 3         | 0.37%   |
| 0x106c2    | 3         | 0.37%   |
| 0x10676    | 3         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 210       | 27.2%   |
| Zen 2            | 59        | 7.64%   |
| Zen 3            | 53        | 6.87%   |
| Unknown          | 44        | 5.7%    |
| Skylake          | 41        | 5.31%   |
| Haswell          | 40        | 5.18%   |
| TigerLake        | 38        | 4.92%   |
| Alderlake Hybrid | 37        | 4.79%   |
| SandyBridge      | 32        | 4.15%   |
| Zen+             | 29        | 3.76%   |
| IvyBridge        | 28        | 3.63%   |
| IceLake          | 28        | 3.63%   |
| CometLake        | 23        | 2.98%   |
| Broadwell        | 16        | 2.07%   |
| Silvermont       | 14        | 1.81%   |
| P6               | 14        | 1.81%   |
| Westmere         | 10        | 1.3%    |
| Penryn           | 8         | 1.04%   |
| Bonnell          | 8         | 1.04%   |
| Core             | 7         | 0.91%   |
| Goldmont plus    | 6         | 0.78%   |
| Zen              | 5         | 0.65%   |
| Steamroller      | 3         | 0.39%   |
| Excavator        | 3         | 0.39%   |
| Bobcat           | 3         | 0.39%   |
| Puma             | 2         | 0.26%   |
| NetBurst         | 2         | 0.26%   |
| K8 Hammer        | 2         | 0.26%   |
| K10 Llano        | 2         | 0.26%   |
| K10              | 2         | 0.26%   |
| Tremont          | 1         | 0.13%   |
| Jaguar           | 1         | 0.13%   |
| Goldmont         | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 513       | 49.9%   |
| Nvidia | 294       | 28.6%   |
| AMD    | 221       | 21.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 60        | 5.64%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 55        | 5.17%   |
| Intel UHD Graphics 620                                                        | 44        | 4.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 41        | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 36        | 3.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 32        | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 29        | 2.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 26        | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 26        | 2.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 23        | 2.16%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 23        | 2.16%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 22        | 2.07%   |
| Intel HD Graphics 530                                                         | 21        | 1.97%   |
| Intel HD Graphics 620                                                         | 19        | 1.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 19        | 1.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 18        | 1.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 17        | 1.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 17        | 1.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 16        | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 16        | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 15        | 1.41%   |
| Intel HD Graphics 630                                                         | 13        | 1.22%   |
| Intel HD Graphics 5500                                                        | 13        | 1.22%   |
| AMD Rembrandt [Radeon 680M]                                                   | 13        | 1.22%   |
| AMD Lucienne                                                                  | 13        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 12        | 1.13%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 10        | 0.94%   |
| Nvidia GP108M [GeForce MX150]                                                 | 10        | 0.94%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 10        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 10        | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 8         | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 8         | 0.75%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 8         | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 8         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 7         | 0.66%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 7         | 0.66%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 7         | 0.66%   |
| AMD Barcelo                                                                   | 7         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 6         | 0.56%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 6         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 274       | 35.08%  |
| Intel + Nvidia | 210       | 26.89%  |
| 1 x AMD        | 153       | 19.59%  |
| 1 x Nvidia     | 61        | 7.81%   |
| AMD + Nvidia   | 29        | 3.71%   |
| 2 x AMD        | 22        | 2.82%   |
| Intel + AMD    | 19        | 2.43%   |
| 2 x Intel      | 12        | 1.54%   |
| 2 x Nvidia     | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 605       | 76.1%   |
| Proprietary | 160       | 20.13%  |
| Unknown     | 30        | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 457       | 57.41%  |
| 0.01-0.5   | 110       | 13.82%  |
| 1.01-2.0   | 78        | 9.8%    |
| 3.01-4.0   | 58        | 7.29%   |
| 0.51-1.0   | 35        | 4.4%    |
| 5.01-6.0   | 22        | 2.76%   |
| 7.01-8.0   | 20        | 2.51%   |
| 8.01-16.0  | 12        | 1.51%   |
| 2.01-3.0   | 4         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 168       | 18.44%  |
| BOE                     | 131       | 14.38%  |
| LG Display              | 114       | 12.51%  |
| Chimei Innolux          | 103       | 11.31%  |
| Samsung Electronics     | 72        | 7.9%    |
| Sharp                   | 54        | 5.93%   |
| Dell                    | 43        | 4.72%   |
| Apple                   | 25        | 2.74%   |
| Lenovo                  | 17        | 1.87%   |
| Goldstar                | 16        | 1.76%   |
| Chi Mei Optoelectronics | 15        | 1.65%   |
| PANDA                   | 14        | 1.54%   |
| CSO                     | 13        | 1.43%   |
| Hewlett-Packard         | 12        | 1.32%   |
| Philips                 | 8         | 0.88%   |
| BenQ                    | 8         | 0.88%   |
| AOC                     | 8         | 0.88%   |
| Acer                    | 7         | 0.77%   |
| InfoVision              | 6         | 0.66%   |
| Iiyama                  | 6         | 0.66%   |
| ASUSTek Computer        | 6         | 0.66%   |
| Ancor Communications    | 5         | 0.55%   |
| ViewSonic               | 4         | 0.44%   |
| TMX                     | 4         | 0.44%   |
| Eizo                    | 4         | 0.44%   |
| Sony                    | 3         | 0.33%   |
| MSI                     | 3         | 0.33%   |
| Mi                      | 3         | 0.33%   |
| HannStar                | 3         | 0.33%   |
| Toshiba                 | 2         | 0.22%   |
| LGD                     | 2         | 0.22%   |
| LG Philips              | 2         | 0.22%   |
| Gigabyte Technology     | 2         | 0.22%   |
| Fujitsu Siemens         | 2         | 0.22%   |
| CMN                     | 2         | 0.22%   |
| BOE Technology Group    | 2         | 0.22%   |
| Unknown                 | 2         | 0.22%   |
| Xiaomi                  | 1         | 0.11%   |
| WST                     | 1         | 0.11%   |
| Viotek                  | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.97%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 7         | 0.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 6         | 0.65%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 6         | 0.65%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 5         | 0.54%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.54%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 5         | 0.54%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                    | 4         | 0.43%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 4         | 0.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.43%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                    | 4         | 0.43%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 4         | 0.43%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 3         | 0.32%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 3         | 0.32%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 3         | 0.32%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 3         | 0.32%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.32%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                  | 3         | 0.32%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 3         | 0.32%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 3         | 0.32%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.32%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.32%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.32%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.32%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                        | 3         | 0.32%   |
| Dell U2414H DELA0A3 1920x1080 530x300mm 24.0-inch                        | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.32%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE082B 1920x1080 309x174mm 14.0-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 449       | 53.33%  |
| 1366x768 (WXGA)    | 82        | 9.74%   |
| 3840x2160 (4K)     | 54        | 6.41%   |
| 2560x1440 (QHD)    | 43        | 5.11%   |
| 1920x1200 (WUXGA)  | 26        | 3.09%   |
| 2560x1600          | 24        | 2.85%   |
| 1600x900 (HD+)     | 23        | 2.73%   |
| 3840x2400          | 17        | 2.02%   |
| 1280x800 (WXGA)    | 13        | 1.54%   |
| 3440x1440          | 11        | 1.31%   |
| 1680x1050 (WSXGA+) | 11        | 1.31%   |
| 1440x900 (WXGA+)   | 11        | 1.31%   |
| 2880x1800          | 9         | 1.07%   |
| 1024x600           | 8         | 0.95%   |
| 2256x1504          | 7         | 0.83%   |
| 1280x1024 (SXGA)   | 6         | 0.71%   |
| 3200x2000          | 5         | 0.59%   |
| 2160x1440          | 5         | 0.59%   |
| 3456x2160          | 3         | 0.36%   |
| 3200x1800 (QHD+)   | 3         | 0.36%   |
| 1280x854           | 3         | 0.36%   |
| 800x1280           | 2         | 0.24%   |
| 3840x1080          | 2         | 0.24%   |
| 2560x1080          | 2         | 0.24%   |
| 2240x1400          | 2         | 0.24%   |
| 2048x1152          | 2         | 0.24%   |
| 1600x1200          | 2         | 0.24%   |
| Unknown            | 2         | 0.24%   |
| 5040x1080          | 1         | 0.12%   |
| 3840x1200          | 1         | 0.12%   |
| 3840x1100          | 1         | 0.12%   |
| 3072x1920          | 1         | 0.12%   |
| 2880x1620          | 1         | 0.12%   |
| 2520x1680          | 1         | 0.12%   |
| 2400x1600          | 1         | 0.12%   |
| 2304x1440          | 1         | 0.12%   |
| 2288x1287          | 1         | 0.12%   |
| 1920x540           | 1         | 0.12%   |
| 1920x1280          | 1         | 0.12%   |
| 1400x1050          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 320       | 35.28%  |
| 13      | 131       | 14.44%  |
| 14      | 116       | 12.79%  |
| 17      | 66        | 7.28%   |
| 27      | 44        | 4.85%   |
| 24      | 33        | 3.64%   |
| 12      | 29        | 3.2%    |
| 23      | 28        | 3.09%   |
| 16      | 27        | 2.98%   |
| 21      | 23        | 2.54%   |
| 34      | 13        | 1.43%   |
| 11      | 11        | 1.21%   |
| Unknown | 11        | 1.21%   |
| 22      | 6         | 0.66%   |
| 19      | 6         | 0.66%   |
| 10      | 6         | 0.66%   |
| 31      | 5         | 0.55%   |
| 25      | 4         | 0.44%   |
| 18      | 4         | 0.44%   |
| 8       | 3         | 0.33%   |
| 58      | 2         | 0.22%   |
| 40      | 2         | 0.22%   |
| 142     | 1         | 0.11%   |
| 75      | 1         | 0.11%   |
| 74      | 1         | 0.11%   |
| 72      | 1         | 0.11%   |
| 65      | 1         | 0.11%   |
| 54      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 36      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 20      | 1         | 0.11%   |
| 7       | 1         | 0.11%   |
| 3       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 509       | 56.74%  |
| 201-300        | 122       | 13.6%   |
| 501-600        | 99        | 11.04%  |
| 351-400        | 74        | 8.25%   |
| 401-500        | 38        | 4.24%   |
| 701-800        | 14        | 1.56%   |
| 601-700        | 11        | 1.23%   |
| Unknown        | 11        | 1.23%   |
| 1001-1500      | 7         | 0.78%   |
| 801-900        | 3         | 0.33%   |
| 1501-2000      | 3         | 0.33%   |
| 101-200        | 3         | 0.33%   |
| 1-100          | 2         | 0.22%   |
| More than 2000 | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 608       | 76.67%  |
| 16/10   | 122       | 15.38%  |
| 3/2     | 22        | 2.77%   |
| 21/9    | 14        | 1.77%   |
| Unknown | 9         | 1.13%   |
| 5/4     | 5         | 0.63%   |
| 4/3     | 5         | 0.63%   |
| 32/9    | 2         | 0.25%   |
| 6/5     | 1         | 0.13%   |
| 3.40    | 1         | 0.13%   |
| 3.20    | 1         | 0.13%   |
| 1.00    | 1         | 0.13%   |
| 0.67    | 1         | 0.13%   |
| 0.62    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 319       | 35.17%  |
| 81-90          | 185       | 20.4%   |
| 201-250        | 67        | 7.39%   |
| 71-80          | 62        | 6.84%   |
| 121-130        | 58        | 6.39%   |
| 301-350        | 45        | 4.96%   |
| 61-70          | 27        | 2.98%   |
| 111-120        | 26        | 2.87%   |
| 351-500        | 19        | 2.09%   |
| 251-300        | 18        | 1.98%   |
| 151-200        | 14        | 1.54%   |
| 51-60          | 12        | 1.32%   |
| Unknown        | 11        | 1.21%   |
| More than 1000 | 9         | 0.99%   |
| 131-140        | 7         | 0.77%   |
| 41-50          | 6         | 0.66%   |
| 141-150        | 6         | 0.66%   |
| 501-1000       | 6         | 0.66%   |
| 1-40           | 5         | 0.55%   |
| 91-100         | 5         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 421       | 47.3%   |
| 101-120       | 139       | 15.62%  |
| 161-240       | 122       | 13.71%  |
| 51-100        | 122       | 13.71%  |
| More than 240 | 67        | 7.53%   |
| Unknown       | 11        | 1.24%   |
| 1-50          | 8         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 615       | 76.21%  |
| 2     | 137       | 16.98%  |
| 0     | 29        | 3.59%   |
| 3     | 26        | 3.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 506       | 42.1%   |
| Realtek Semiconductor                 | 376       | 31.28%  |
| Qualcomm Atheros                      | 99        | 8.24%   |
| Broadcom                              | 45        | 3.74%   |
| MediaTek                              | 34        | 2.83%   |
| ASIX Electronics                      | 15        | 1.25%   |
| Lenovo                                | 13        | 1.08%   |
| Qualcomm                              | 12        | 1%      |
| Marvell Technology Group              | 9         | 0.75%   |
| Dell                                  | 9         | 0.75%   |
| Xiaomi                                | 8         | 0.67%   |
| Broadcom Limited                      | 8         | 0.67%   |
| Sierra Wireless                       | 7         | 0.58%   |
| Samsung Electronics                   | 6         | 0.5%    |
| TP-Link                               | 5         | 0.42%   |
| Fibocom                               | 5         | 0.42%   |
| Ericsson Business Mobile Networks     | 5         | 0.42%   |
| Apple                                 | 5         | 0.42%   |
| Ralink Technology                     | 3         | 0.25%   |
| Qualcomm Atheros Communications       | 3         | 0.25%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.17%   |
| Silicon Integrated Systems [SiS]      | 2         | 0.17%   |
| Ralink                                | 2         | 0.17%   |
| ICS Advent                            | 2         | 0.17%   |
| D-Link System                         | 2         | 0.17%   |
| Texas Instruments                     | 1         | 0.08%   |
| Shenzhen Goodix Technology            | 1         | 0.08%   |
| Prusa                                 | 1         | 0.08%   |
| Nvidia                                | 1         | 0.08%   |
| NetGear                               | 1         | 0.08%   |
| Microsoft                             | 1         | 0.08%   |
| JMicron Technology                    | 1         | 0.08%   |
| Huawei Technologies                   | 1         | 0.08%   |
| Google                                | 1         | 0.08%   |
| Gemtek                                | 1         | 0.08%   |
| Edimax Technology                     | 1         | 0.08%   |
| D-Link                                | 1         | 0.08%   |
| Cisco Aironet Wireless Communications | 1         | 0.08%   |
| BUFFALO                               | 1         | 0.08%   |
| AVM                                   | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 257       | 17.41%  |
| Intel Wi-Fi 6 AX200                                               | 84        | 5.69%   |
| Intel Wireless 8265 / 8275                                        | 56        | 3.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 3.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 36        | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 28        | 1.9%    |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 26        | 1.76%   |
| Intel Wireless 7265                                               | 25        | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 23        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 22        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 1.42%   |
| Intel Wireless 7260                                               | 21        | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 1.42%   |
| Intel Wireless 8260                                               | 20        | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 0.95%   |
| Intel Wireless 3165                                               | 13        | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 12        | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 0.54%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 8         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 0.54%   |
| Intel Centrino Advanced-N 6235                                    | 8         | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 494       | 61.6%   |
| Realtek Semiconductor                 | 103       | 12.84%  |
| Qualcomm Atheros                      | 76        | 9.48%   |
| Broadcom                              | 37        | 4.61%   |
| MediaTek                              | 33        | 4.11%   |
| Qualcomm                              | 12        | 1.5%    |
| Sierra Wireless                       | 7         | 0.87%   |
| Dell                                  | 7         | 0.87%   |
| Fibocom                               | 5         | 0.62%   |
| Broadcom Limited                      | 5         | 0.62%   |
| TP-Link                               | 3         | 0.37%   |
| Ralink Technology                     | 3         | 0.37%   |
| Qualcomm Atheros Communications       | 3         | 0.37%   |
| Ralink                                | 2         | 0.25%   |
| Ericsson Business Mobile Networks     | 2         | 0.25%   |
| D-Link System                         | 2         | 0.25%   |
| NetGear                               | 1         | 0.12%   |
| Microsoft                             | 1         | 0.12%   |
| Edimax Technology                     | 1         | 0.12%   |
| D-Link                                | 1         | 0.12%   |
| Cisco Aironet Wireless Communications | 1         | 0.12%   |
| BUFFALO                               | 1         | 0.12%   |
| AVM                                   | 1         | 0.12%   |
| ASUSTek Computer                      | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 84        | 10.43%  |
| Intel Wireless 8265 / 8275                                              | 56        | 6.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 4.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 28        | 3.48%   |
| Intel Wi-Fi 6 AX201                                                     | 28        | 3.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 26        | 3.23%   |
| Intel Wireless 7265                                                     | 25        | 3.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 2.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 23        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 22        | 2.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 2.61%   |
| Intel Wireless 7260                                                     | 21        | 2.61%   |
| Intel Wireless 8260                                                     | 20        | 2.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 2.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 19        | 2.36%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 18        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.74%   |
| Intel Wireless 3165                                                     | 13        | 1.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 12        | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 12        | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.99%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 8         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.99%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.87%   |
| Intel Wireless-AC 9260                                                  | 7         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 7         | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 0.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 6         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.62%   |
| Intel Wireless 3160                                                     | 5         | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.62%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.62%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 4         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 339       | 53.39%  |
| Intel                            | 173       | 27.24%  |
| Qualcomm Atheros                 | 34        | 5.35%   |
| Broadcom                         | 18        | 2.83%   |
| ASIX Electronics                 | 15        | 2.36%   |
| Lenovo                           | 13        | 2.05%   |
| Marvell Technology Group         | 9         | 1.42%   |
| Xiaomi                           | 8         | 1.26%   |
| Apple                            | 5         | 0.79%   |
| Samsung Electronics              | 4         | 0.63%   |
| Broadcom Limited                 | 3         | 0.47%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.31%   |
| TP-Link                          | 2         | 0.31%   |
| Silicon Integrated Systems [SiS] | 2         | 0.31%   |
| ICS Advent                       | 2         | 0.31%   |
| Nvidia                           | 1         | 0.16%   |
| JMicron Technology               | 1         | 0.16%   |
| Huawei Technologies              | 1         | 0.16%   |
| Google                           | 1         | 0.16%   |
| Gemtek                           | 1         | 0.16%   |
| Aquantia                         | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 257       | 39.72%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 7.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 3.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 3.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 3.09%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 1.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 1.55%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 1.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.93%   |
| Intel Ethernet Connection (5) I219-LM                             | 6         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.77%   |
| Lenovo USB-C Dock Ethernet                                        | 5         | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.62%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.62%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.62%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.62%   |
| Intel Ethernet Connection (14) I219-LM                            | 4         | 0.62%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 3         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.46%   |
| Intel Ethernet Connection (16) I219-LM                            | 3         | 0.46%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.46%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.46%   |
| Intel Ethernet Connection (10) I219-LM                            | 3         | 0.46%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 3         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 759       | 54.92%  |
| Ethernet | 599       | 43.34%  |
| Modem    | 23        | 1.66%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 601       | 70.96%  |
| Ethernet | 246       | 29.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 511       | 66.28%  |
| 1     | 238       | 30.87%  |
| 3     | 18        | 2.33%   |
| 0     | 4         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 649       | 81.94%  |
| Yes  | 143       | 18.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 422       | 62.43%  |
| Realtek Semiconductor           | 62        | 9.17%   |
| IMC Networks                    | 30        | 4.44%   |
| Lite-On Technology              | 24        | 3.55%   |
| Foxconn / Hon Hai               | 24        | 3.55%   |
| Qualcomm Atheros Communications | 22        | 3.25%   |
| Apple                           | 22        | 3.25%   |
| Broadcom                        | 18        | 2.66%   |
| Dell                            | 9         | 1.33%   |
| Realtek                         | 8         | 1.18%   |
| Cambridge Silicon Radio         | 7         | 1.04%   |
| USI                             | 6         | 0.89%   |
| Toshiba                         | 4         | 0.59%   |
| Hewlett-Packard                 | 4         | 0.59%   |
| Foxconn International           | 3         | 0.44%   |
| ASUSTek Computer                | 3         | 0.44%   |
| MediaTek                        | 2         | 0.3%    |
| Ralink Technology               | 1         | 0.15%   |
| Opticis                         | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |
| Askey Computer                  | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |
| Actiontec Electronics           | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 135       | 19.94%  |
| Intel AX200 Bluetooth                               | 80        | 11.82%  |
| Intel AX201 Bluetooth                               | 73        | 10.78%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 67        | 9.9%    |
| Realtek Bluetooth Radio                             | 29        | 4.28%   |
| Intel Bluetooth Device                              | 25        | 3.69%   |
| Intel AX210 Bluetooth                               | 22        | 3.25%   |
| Apple Bluetooth Host Controller                     | 17        | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 2.07%   |
| IMC Networks Wireless_Device                        | 13        | 1.92%   |
| IMC Networks Bluetooth Radio                        | 12        | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1.48%   |
| Realtek 802.11ac WLAN Adapter                       | 9         | 1.33%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 1.33%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.03%   |
| Lite-On Bluetooth Device                            | 7         | 1.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 1.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 1.03%   |
| USI Bluetooth Device                                | 6         | 0.89%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.74%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.59%   |
| Lite-On Wireless_Device                             | 4         | 0.59%   |
| IMC Networks Bluetooth Device                       | 4         | 0.59%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.59%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.44%   |
| Apple Bluetooth HCI                                 | 3         | 0.44%   |
| Toshiba RT Bluetooth Radio                          | 2         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 560       | 53.38%  |
| AMD                                  | 202       | 19.26%  |
| Nvidia                               | 186       | 17.73%  |
| Lenovo                               | 15        | 1.43%   |
| Realtek Semiconductor                | 9         | 0.86%   |
| C-Media Electronics                  | 9         | 0.86%   |
| Logitech                             | 5         | 0.48%   |
| Plantronics                          | 4         | 0.38%   |
| Kingston Technology                  | 4         | 0.38%   |
| SteelSeries ApS                      | 3         | 0.29%   |
| Razer USA                            | 3         | 0.29%   |
| No brand                             | 3         | 0.29%   |
| Hewlett-Packard                      | 3         | 0.29%   |
| Dell                                 | 3         | 0.29%   |
| Creative Technology                  | 3         | 0.29%   |
| Blue Microphones                     | 3         | 0.29%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.19%   |
| GYROCOM C&C                          | 2         | 0.19%   |
| GN Netcom                            | 2         | 0.19%   |
| Generalplus Technology               | 2         | 0.19%   |
| AudioQuest                           | 2         | 0.19%   |
| ASUSTek Computer                     | 2         | 0.19%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.1%    |
| Texas Instruments                    | 1         | 0.1%    |
| Tdlasunnic                           | 1         | 0.1%    |
| Synaptics                            | 1         | 0.1%    |
| Sennheiser Communications            | 1         | 0.1%    |
| Samson Technologies                  | 1         | 0.1%    |
| RODE Microphones                     | 1         | 0.1%    |
| LG Electronics                       | 1         | 0.1%    |
| JMTek                                | 1         | 0.1%    |
| JBL                                  | 1         | 0.1%    |
| iCreate Technologies                 | 1         | 0.1%    |
| FiiO Electronics Technology          | 1         | 0.1%    |
| EGO SYStems                          | 1         | 0.1%    |
| DSEA A/S                             | 1         | 0.1%    |
| Corsair                              | 1         | 0.1%    |
| Behringer.......                     | 1         | 0.1%    |
| AVer Information                     | 1         | 0.1%    |
| Audio-Technica                       | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 171       | 13.33%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 104       | 8.11%   |
| Intel Sunrise Point-LP HD Audio                                            | 86        | 6.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 70        | 5.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 38        | 2.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 33        | 2.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 31        | 2.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 29        | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 27        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 27        | 2.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 24        | 1.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 24        | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 23        | 1.79%   |
| Intel Comet Lake PCH cAVS                                                  | 22        | 1.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 1.71%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 21        | 1.64%   |
| Intel CM238 HD Audio Controller                                            | 21        | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 1.48%   |
| Intel 8 Series HD Audio Controller                                         | 19        | 1.48%   |
| Nvidia GA106 High Definition Audio Controller                              | 17        | 1.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 17        | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 16        | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16        | 1.25%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.25%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 16        | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.17%   |
| Nvidia Audio device                                                        | 14        | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                              | 12        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 11        | 0.86%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 11        | 0.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 10        | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 0.78%   |
| AMD FCH Azalia Controller                                                  | 10        | 0.78%   |
| Realtek Semiconductor USB Audio                                            | 9         | 0.7%    |
| Nvidia TU104 HD Audio Controller                                           | 9         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 281       | 32.15%  |
| SK hynix                     | 189       | 21.62%  |
| Micron Technology            | 123       | 14.07%  |
| Kingston                     | 69        | 7.89%   |
| Crucial                      | 52        | 5.95%   |
| Unknown                      | 45        | 5.15%   |
| Ramaxel Technology           | 14        | 1.6%    |
| Corsair                      | 13        | 1.49%   |
| A-DATA Technology            | 13        | 1.49%   |
| Elpida                       | 12        | 1.37%   |
| G.Skill                      | 8         | 0.92%   |
| Team                         | 7         | 0.8%    |
| Unknown                      | 7         | 0.8%    |
| Transcend                    | 6         | 0.69%   |
| Nanya Technology             | 6         | 0.69%   |
| Patriot                      | 5         | 0.57%   |
| GOODRAM                      | 4         | 0.46%   |
| Unknown (ABCD)               | 3         | 0.34%   |
| Timetec                      | 3         | 0.34%   |
| Apacer                       | 2         | 0.23%   |
| AMD                          | 2         | 0.23%   |
| Unknown (0x5D00000000000000) | 1         | 0.11%   |
| Teikon                       | 1         | 0.11%   |
| Saikano                      | 1         | 0.11%   |
| Magnum Tech                  | 1         | 0.11%   |
| KLEVV                        | 1         | 0.11%   |
| GSkill                       | 1         | 0.11%   |
| Goldkey                      | 1         | 0.11%   |
| CSX                          | 1         | 0.11%   |
| Avant                        | 1         | 0.11%   |
| 48spaces                     | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 14        | 1.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 12        | 1.31%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 12        | 1.31%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 11        | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 11        | 1.2%    |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s    | 11        | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 10        | 1.09%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 9         | 0.98%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 9         | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.98%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 8         | 0.87%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 8         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 8         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.87%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 8         | 0.87%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.87%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 8         | 0.87%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.77%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 7         | 0.77%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 7         | 0.77%   |
| Unknown                                                     | 7         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.66%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 6         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 5         | 0.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 5         | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 5         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 5         | 0.55%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 5         | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.55%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.55%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s       | 5         | 0.55%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 5         | 0.55%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.55%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s          | 5         | 0.55%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 5         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 5         | 0.55%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s      | 5         | 0.55%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s     | 5         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 446       | 60.19%  |
| DDR3    | 158       | 21.32%  |
| LPDDR4  | 36        | 4.86%   |
| DDR5    | 23        | 3.1%    |
| LPDDR3  | 22        | 2.97%   |
| LPDDR5  | 18        | 2.43%   |
| DDR2    | 18        | 2.43%   |
| DDR     | 12        | 1.62%   |
| SDRAM   | 5         | 0.67%   |
| Unknown | 2         | 0.27%   |
| DRAM    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 657       | 88.31%  |
| Row Of Chips | 77        | 10.35%  |
| Chip         | 5         | 0.67%   |
| DIMM         | 3         | 0.4%    |
| Unknown      | 2         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 350       | 43.32%  |
| 16384 | 180       | 22.28%  |
| 4096  | 148       | 18.32%  |
| 2048  | 51        | 6.31%   |
| 32768 | 50        | 6.19%   |
| 1024  | 21        | 2.6%    |
| 512   | 4         | 0.5%    |
| 256   | 4         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 204       | 25.66%  |
| 2667    | 190       | 23.9%   |
| 1600    | 110       | 13.84%  |
| 2400    | 50        | 6.29%   |
| 2133    | 40        | 5.03%   |
| 1333    | 24        | 3.02%   |
| 4800    | 22        | 2.77%   |
| 6400    | 18        | 2.26%   |
| 4267    | 18        | 2.26%   |
| 1334    | 17        | 2.14%   |
| Unknown | 16        | 2.01%   |
| 667     | 14        | 1.76%   |
| 3266    | 10        | 1.26%   |
| 1867    | 10        | 1.26%   |
| 8400    | 9         | 1.13%   |
| 1067    | 7         | 0.88%   |
| 4266    | 5         | 0.63%   |
| 800     | 5         | 0.63%   |
| 5600    | 4         | 0.5%    |
| 3733    | 4         | 0.5%    |
| 2933    | 4         | 0.5%    |
| 533     | 4         | 0.5%    |
| 3000    | 2         | 0.25%   |
| 400     | 2         | 0.25%   |
| 133     | 2         | 0.25%   |
| 4199    | 1         | 0.13%   |
| 3600    | 1         | 0.13%   |
| 3467    | 1         | 0.13%   |
| 1639    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 40%     |
| Seiko Epson         | 2         | 20%     |
| Xiaomi              | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| Konica Minolta      | 1         | 10%     |
| Canon               | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xiaomi MiMouse 2                     | 1         | 10%     |
| Seiko Epson WF-2510 Series           | 1         | 10%     |
| Seiko Epson AL-M310DN                | 1         | 10%     |
| Samsung CLP-325 Color Laser Printer  | 1         | 10%     |
| Konica Minolta magicolor 1680MF scan | 1         | 10%     |
| HP LaserJet P2055 series             | 1         | 10%     |
| HP Deskjet D1500 series              | 1         | 10%     |
| HP DeskJet 5440                      | 1         | 10%     |
| HP DeskJet 3630 series               | 1         | 10%     |
| Canon CanoScan LiDE 300              | 1         | 10%     |

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
| Chicony Electronics                    | 171       | 25.68%  |
| IMC Networks                           | 89        | 13.36%  |
| Microdia                               | 64        | 9.61%   |
| Realtek Semiconductor                  | 50        | 7.51%   |
| Bison Electronics                      | 47        | 7.06%   |
| Sunplus Innovation Technology          | 36        | 5.41%   |
| Quanta                                 | 35        | 5.26%   |
| Lite-On Technology                     | 25        | 3.75%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 3.3%    |
| Luxvisions Innotech Limited            | 20        | 3%      |
| Syntek                                 | 16        | 2.4%    |
| Apple                                  | 15        | 2.25%   |
| Logitech                               | 14        | 2.1%    |
| Acer                                   | 7         | 1.05%   |
| Sonix Technology                       | 5         | 0.75%   |
| Samsung Electronics                    | 5         | 0.75%   |
| Suyin                                  | 4         | 0.6%    |
| DigiTech                               | 4         | 0.6%    |
| Z-Star Microelectronics                | 3         | 0.45%   |
| Silicon Motion                         | 3         | 0.45%   |
| Microsoft                              | 3         | 0.45%   |
| Ricoh                                  | 2         | 0.3%    |
| LG Electronics                         | 2         | 0.3%    |
| Lenovo                                 | 2         | 0.3%    |
| kingcome                               | 2         | 0.3%    |
| Genesys Logic                          | 2         | 0.3%    |
| Alcor Micro                            | 2         | 0.3%    |
| USB3.0 HD Audio Capture                | 1         | 0.15%   |
| SunplusIT                              | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| ShineTech                              | 1         | 0.15%   |
| Razer USA                              | 1         | 0.15%   |
| Omnivision                             | 1         | 0.15%   |
| Intel                                  | 1         | 0.15%   |
| icSpring                               | 1         | 0.15%   |
| Holitech                               | 1         | 0.15%   |
| Hewlett-Packard                        | 1         | 0.15%   |
| Google                                 | 1         | 0.15%   |
| Goodong                                | 1         | 0.15%   |
| Elgato Systems                         | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 58        | 8.62%   |
| Microdia Integrated_Webcam_HD                        | 40        | 5.94%   |
| IMC Networks Integrated Camera                       | 33        | 4.9%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 26        | 3.86%   |
| Bison Integrated Camera                              | 23        | 3.42%   |
| Realtek Integrated_Webcam_HD                         | 22        | 3.27%   |
| Chicony HD Webcam                                    | 17        | 2.53%   |
| Sunplus Integrated_Webcam_HD                         | 12        | 1.78%   |
| Chicony HP HD Camera                                 | 12        | 1.78%   |
| Syntek Integrated Camera                             | 11        | 1.63%   |
| Quanta HD User Facing                                | 9         | 1.34%   |
| Lite-On Integrated Camera                            | 9         | 1.34%   |
| Lite-On HP HD Camera                                 | 7         | 1.04%   |
| Sunplus HD WebCam                                    | 6         | 0.89%   |
| Logitech HD Pro Webcam C920                          | 6         | 0.89%   |
| Chicony Lenovo EasyCamera                            | 6         | 0.89%   |
| Chicony HD User Facing                               | 6         | 0.89%   |
| Bison SunplusIT Integrated Camera                    | 6         | 0.89%   |
| Apple FaceTime HD Camera                             | 6         | 0.89%   |
| Samsung Galaxy series, misc. (MTP mode)              | 5         | 0.74%   |
| Quanta HP TrueVision HD Camera                       | 5         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 5         | 0.74%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.74%   |
| Luxvisions Innotech Limited HP HD Camera             | 5         | 0.74%   |
| IMC Networks ov9734_azurewave_camera                 | 5         | 0.74%   |
| Chicony USB2.0 Camera                                | 5         | 0.74%   |
| Chicony ThinkPad T490 Webcam                         | 5         | 0.74%   |
| Chicony Integrated Camera (1280x720@30)              | 5         | 0.74%   |
| Bison HD Webcam                                      | 5         | 0.74%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.59%   |
| Realtek Laptop Camera                                | 4         | 0.59%   |
| Quanta HP Wide Vision HD Camera                      | 4         | 0.59%   |
| Quanta HD Webcam                                     | 4         | 0.59%   |
| Microdia Integrated_Webcam_FHD                       | 4         | 0.59%   |
| Microdia Integrated Webcam                           | 4         | 0.59%   |
| Luxvisions Innotech Limited Integrated Camera        | 4         | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 0.59%   |
| Lite-On TOSHIBA Web Camera - HD                      | 4         | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 4         | 0.59%   |
| IMC Networks USB2.0 HD IR UVC WebCam                 | 4         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 68        | 45.95%  |
| Validity Sensors           | 36        | 24.32%  |
| Shenzhen Goodix Technology | 22        | 14.86%  |
| Elan Microelectronics      | 9         | 6.08%   |
| STMicroelectronics         | 4         | 2.7%    |
| LighTuning Technology      | 4         | 2.7%    |
| AuthenTec                  | 4         | 2.7%    |
| Upek                       | 1         | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 28        | 18.92%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 10.14%  |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 8.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 6.08%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 6.08%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.05%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 4.05%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 3.38%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.7%    |
| Synaptics UWP WBDI Device                                                  | 4         | 2.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 2.7%    |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.7%    |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.03%   |
| Synaptics WBDI                                                             | 3         | 2.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.03%   |
| Validity Sensors VFS491                                                    | 2         | 1.35%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.35%   |
| Unknown                                                                    | 2         | 1.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.68%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 0.68%   |
| Synaptics WBDI Device                                                      | 1         | 0.68%   |
| Synaptics TouchPad                                                         | 1         | 0.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.68%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 42        | 41.58%  |
| Alcor Micro               | 41        | 40.59%  |
| Upek                      | 5         | 4.95%   |
| O2 Micro                  | 5         | 4.95%   |
| Yubico.com                | 1         | 0.99%   |
| Purism, SPC               | 1         | 0.99%   |
| OmniKey                   | 1         | 0.99%   |
| Microchip Technology      | 1         | 0.99%   |
| Lenovo                    | 1         | 0.99%   |
| Gemalto (was Gemplus)     | 1         | 0.99%   |
| Clay Logic                | 1         | 0.99%   |
| Aladdin Knowledge Systems | 1         | 0.99%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 40.59%  |
| Broadcom 58200                                                               | 16        | 15.84%  |
| Broadcom 5880                                                                | 12        | 11.88%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.93%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 5.94%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.95%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 3.96%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.99%   |
| Purism, SPC Librem Key                                                       | 1         | 0.99%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.99%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.99%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.99%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 0.99%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.99%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.99%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.99%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.99%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 302       | 34.55%  |
| 1     | 232       | 26.54%  |
| 2     | 136       | 15.56%  |
| 3     | 92        | 10.53%  |
| 4     | 58        | 6.64%   |
| 5     | 34        | 3.89%   |
| 6     | 17        | 1.95%   |
| 7     | 2         | 0.23%   |
| 8     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 181       | 15.26%  |
| Camera                   | 164       | 13.83%  |
| Bluetooth                | 158       | 13.32%  |
| Fingerprint reader       | 147       | 12.39%  |
| Graphics card            | 140       | 11.8%   |
| Chipcard                 | 86        | 7.25%   |
| Multimedia controller    | 72        | 6.07%   |
| Card reader              | 70        | 5.9%    |
| Net/wireless             | 69        | 5.82%   |
| Sound                    | 22        | 1.85%   |
| Modem                    | 16        | 1.35%   |
| Net/ethernet             | 15        | 1.26%   |
| Network                  | 14        | 1.18%   |
| Storage/ata              | 8         | 0.67%   |
| Firewire controller      | 6         | 0.51%   |
| Storage                  | 5         | 0.42%   |
| Storage/ide              | 4         | 0.34%   |
| Tv card                  | 2         | 0.17%   |
| Storage/raid             | 2         | 0.17%   |
| Storage/nvme             | 2         | 0.17%   |
| Dvb card                 | 2         | 0.17%   |
| Wireless                 | 1         | 0.08%   |

