Linux in Ireland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ireland/Desktop/README.md) and [notebooks](/Location/Ireland/Notebook/README.md).

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

Total: 1078

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Medion        | Akoya E6239                 | Notebook    | [757858a876](https://linux-hardware.org/?probe=757858a876) | Dec 31, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [a06265dd1e](https://linux-hardware.org/?probe=a06265dd1e) | Dec 30, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| Dell          | Inspiron 3482               | Notebook    | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| AVITA         | NS14A6                      | Notebook    | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| Toshiba       | Satellite A660              | Notebook    | [d0415e05d3](https://linux-hardware.org/?probe=d0415e05d3) | Dec 23, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1dd35fdb02](https://linux-hardware.org/?probe=1dd35fdb02) | Dec 19, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [18f1d4c5d0](https://linux-hardware.org/?probe=18f1d4c5d0) | Dec 18, 2023 |
| Dell          | Latitude 5400               | Notebook    | [9ae128faf4](https://linux-hardware.org/?probe=9ae128faf4) | Dec 16, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | Notebook    | [91fd392ea3](https://linux-hardware.org/?probe=91fd392ea3) | Dec 14, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | Notebook    | [2dc1349392](https://linux-hardware.org/?probe=2dc1349392) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [647f96ad2c](https://linux-hardware.org/?probe=647f96ad2c) | Dec 08, 2023 |
| Samsung       | 750XED                      | Notebook    | [5263f7ebc0](https://linux-hardware.org/?probe=5263f7ebc0) | Dec 07, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [a84f25d406](https://linux-hardware.org/?probe=a84f25d406) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [6a95e96b1b](https://linux-hardware.org/?probe=6a95e96b1b) | Dec 02, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [8425b9dc62](https://linux-hardware.org/?probe=8425b9dc62) | Nov 30, 2023 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [438812dbd7](https://linux-hardware.org/?probe=438812dbd7) | Nov 27, 2023 |
| Samsung       | 965QFG                      | Convertible | [8769cfd663](https://linux-hardware.org/?probe=8769cfd663) | Nov 27, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| AZW           | Green G3                    | Desktop     | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [2c7d8106d0](https://linux-hardware.org/?probe=2c7d8106d0) | Nov 24, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [9fe4290fb6](https://linux-hardware.org/?probe=9fe4290fb6) | Nov 21, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [93d573033d](https://linux-hardware.org/?probe=93d573033d) | Nov 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0af175a9d7](https://linux-hardware.org/?probe=0af175a9d7) | Nov 19, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [d0f4cc3a98](https://linux-hardware.org/?probe=d0f4cc3a98) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [a76432f7df](https://linux-hardware.org/?probe=a76432f7df) | Nov 16, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [1d3516385d](https://linux-hardware.org/?probe=1d3516385d) | Nov 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e45684a89b](https://linux-hardware.org/?probe=e45684a89b) | Nov 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Alienware     | m18 R1                      | Notebook    | [f4c5c9d2ec](https://linux-hardware.org/?probe=f4c5c9d2ec) | Nov 13, 2023 |
| HP            | Pavilion m6                 | Notebook    | [60a4921f94](https://linux-hardware.org/?probe=60a4921f94) | Nov 13, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [5ad5316ab5](https://linux-hardware.org/?probe=5ad5316ab5) | Nov 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [94186792b2](https://linux-hardware.org/?probe=94186792b2) | Nov 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [d743b33cc7](https://linux-hardware.org/?probe=d743b33cc7) | Nov 05, 2023 |
| System76      | Lemur Pro                   | Notebook    | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [3ba4126936](https://linux-hardware.org/?probe=3ba4126936) | Nov 04, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [440d52f445](https://linux-hardware.org/?probe=440d52f445) | Nov 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Dell          | Latitude 5421               | Notebook    | [670d635ddc](https://linux-hardware.org/?probe=670d635ddc) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1a7844f56d](https://linux-hardware.org/?probe=1a7844f56d) | Oct 30, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [1a28398320](https://linux-hardware.org/?probe=1a28398320) | Oct 26, 2023 |
| HP            | 3399                        | Desktop     | [3dca1c2950](https://linux-hardware.org/?probe=3dca1c2950) | Oct 22, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [c9ab502087](https://linux-hardware.org/?probe=c9ab502087) | Oct 17, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [88057db3aa](https://linux-hardware.org/?probe=88057db3aa) | Oct 11, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45d51130b0](https://linux-hardware.org/?probe=45d51130b0) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [446c6847c3](https://linux-hardware.org/?probe=446c6847c3) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cf79594d59](https://linux-hardware.org/?probe=cf79594d59) | Oct 02, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cb7ac852c](https://linux-hardware.org/?probe=9cb7ac852c) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| Dell          | Latitude 5410               | Notebook    | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [86d39b72d6](https://linux-hardware.org/?probe=86d39b72d6) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Dell          | Latitude 5410               | Notebook    | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Dell          | Latitude 7320               | Notebook    | [2549020a4e](https://linux-hardware.org/?probe=2549020a4e) | Sep 26, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| MSI           | Katana GF76 12UG            | Notebook    | [ee50afcf85](https://linux-hardware.org/?probe=ee50afcf85) | Sep 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [8bf4c79f98](https://linux-hardware.org/?probe=8bf4c79f98) | Sep 17, 2023 |
| HP            | 0B54h D                     | Desktop     | [f5259ad0b1](https://linux-hardware.org/?probe=f5259ad0b1) | Sep 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| Dell          | Latitude E6400              | Notebook    | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| ASUSTek       | TALAS                       | Desktop     | [094153c6f4](https://linux-hardware.org/?probe=094153c6f4) | Sep 04, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [0f98d77b72](https://linux-hardware.org/?probe=0f98d77b72) | Sep 01, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | Notebook    | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [db091802b1](https://linux-hardware.org/?probe=db091802b1) | Aug 26, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [8f51778271](https://linux-hardware.org/?probe=8f51778271) | Aug 25, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7e397373d8](https://linux-hardware.org/?probe=7e397373d8) | Aug 25, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82be53cac0](https://linux-hardware.org/?probe=82be53cac0) | Aug 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2970428ad3](https://linux-hardware.org/?probe=2970428ad3) | Aug 23, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [0182dad759](https://linux-hardware.org/?probe=0182dad759) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8b0d028b37](https://linux-hardware.org/?probe=8b0d028b37) | Aug 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [179beade50](https://linux-hardware.org/?probe=179beade50) | Aug 08, 2023 |
| Dell          | Precision M2800             | Notebook    | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea4d9240fb](https://linux-hardware.org/?probe=ea4d9240fb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [6c13f7a1f0](https://linux-hardware.org/?probe=6c13f7a1f0) | Aug 04, 2023 |
| HP            | 21D0                        | Desktop     | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [928fd8c7cb](https://linux-hardware.org/?probe=928fd8c7cb) | Jul 29, 2023 |
| HP            | 829A                        | Mini pc     | [5bd4fdc8d1](https://linux-hardware.org/?probe=5bd4fdc8d1) | Jul 28, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [8e05eceeef](https://linux-hardware.org/?probe=8e05eceeef) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [5457b19b2b](https://linux-hardware.org/?probe=5457b19b2b) | Jul 26, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [08fd0fea6a](https://linux-hardware.org/?probe=08fd0fea6a) | Jul 26, 2023 |
| HP            | 21D0                        | Desktop     | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [8b128357b4](https://linux-hardware.org/?probe=8b128357b4) | Jul 19, 2023 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [7733080cef](https://linux-hardware.org/?probe=7733080cef) | Jul 19, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| HP            | Pavilion m6                 | Notebook    | [8566e9607f](https://linux-hardware.org/?probe=8566e9607f) | Jul 14, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [0e9916f3e3](https://linux-hardware.org/?probe=0e9916f3e3) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [a72d009fab](https://linux-hardware.org/?probe=a72d009fab) | Jul 13, 2023 |
| HP            | 21D0                        | Desktop     | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Samsung       | 750XED                      | Notebook    | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [aa8cfd7d60](https://linux-hardware.org/?probe=aa8cfd7d60) | Jul 07, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | Desktop     | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | Desktop     | [b24c1d471d](https://linux-hardware.org/?probe=b24c1d471d) | Jul 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Shenzhen W... | AERO 5 Lite Mini PC         | Mini pc     | [7375ced625](https://linux-hardware.org/?probe=7375ced625) | Jun 30, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3e2928fe9d](https://linux-hardware.org/?probe=3e2928fe9d) | Jun 23, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [ae5f4be943](https://linux-hardware.org/?probe=ae5f4be943) | Jun 20, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [913d8d26b9](https://linux-hardware.org/?probe=913d8d26b9) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | Notebook    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [8678eeac9b](https://linux-hardware.org/?probe=8678eeac9b) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Notebook    | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| HP            | 0AECh D                     | Desktop     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| HP            | ZBook 15                    | Notebook    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [a3798147d9](https://linux-hardware.org/?probe=a3798147d9) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [f2655b5798](https://linux-hardware.org/?probe=f2655b5798) | May 24, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [2bed616680](https://linux-hardware.org/?probe=2bed616680) | May 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [785f4bad86](https://linux-hardware.org/?probe=785f4bad86) | May 23, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63c991635f](https://linux-hardware.org/?probe=63c991635f) | May 17, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [46b31c9243](https://linux-hardware.org/?probe=46b31c9243) | May 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e21cdf9e37](https://linux-hardware.org/?probe=e21cdf9e37) | May 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed810bd154](https://linux-hardware.org/?probe=ed810bd154) | May 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [d6598957ff](https://linux-hardware.org/?probe=d6598957ff) | May 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [51eba04846](https://linux-hardware.org/?probe=51eba04846) | May 08, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [c223c83063](https://linux-hardware.org/?probe=c223c83063) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [983ec204ab](https://linux-hardware.org/?probe=983ec204ab) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3ba3358e4d](https://linux-hardware.org/?probe=3ba3358e4d) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Dell          | Latitude E5520              | Notebook    | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f543ce6c65](https://linux-hardware.org/?probe=f543ce6c65) | Apr 29, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [261c116001](https://linux-hardware.org/?probe=261c116001) | Apr 28, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [f2b702b631](https://linux-hardware.org/?probe=f2b702b631) | Apr 28, 2023 |
| Dell          | Latitude 7420               | Notebook    | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [84ae892fb4](https://linux-hardware.org/?probe=84ae892fb4) | Apr 19, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88b9080a8c](https://linux-hardware.org/?probe=88b9080a8c) | Apr 17, 2023 |
| Dell          | Latitude 7420               | Notebook    | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [690ed7960a](https://linux-hardware.org/?probe=690ed7960a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63574c5adf](https://linux-hardware.org/?probe=63574c5adf) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [beeb850c3b](https://linux-hardware.org/?probe=beeb850c3b) | Apr 09, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | G752VM                      | Notebook    | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ab9916feea](https://linux-hardware.org/?probe=ab9916feea) | Apr 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7e97eb6308](https://linux-hardware.org/?probe=7e97eb6308) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Dell          | 0TP412                      | Desktop     | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [4f8515b9ed](https://linux-hardware.org/?probe=4f8515b9ed) | Mar 27, 2023 |
| HP            | 0B54h D                     | Desktop     | [3edc678017](https://linux-hardware.org/?probe=3edc678017) | Mar 26, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| Timi          | A35S                        | Notebook    | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5cbf68e6d](https://linux-hardware.org/?probe=f5cbf68e6d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 8715                        | Mini pc     | [9ce704a4b9](https://linux-hardware.org/?probe=9ce704a4b9) | Mar 23, 2023 |
| MSI           | GP72 7RE                    | Notebook    | [729f2297cb](https://linux-hardware.org/?probe=729f2297cb) | Mar 23, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [dab7a6edbc](https://linux-hardware.org/?probe=dab7a6edbc) | Mar 22, 2023 |
| Dell          | Latitude 7420               | Notebook    | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| HP            | 83E9                        | Desktop     | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c462ccc41a](https://linux-hardware.org/?probe=c462ccc41a) | Mar 19, 2023 |
| Samsung       | 940XFG                      | Notebook    | [566a4046f6](https://linux-hardware.org/?probe=566a4046f6) | Mar 18, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [9d0ac027df](https://linux-hardware.org/?probe=9d0ac027df) | Mar 14, 2023 |
| Google        | Reks                        | Notebook    | [56296236c5](https://linux-hardware.org/?probe=56296236c5) | Mar 12, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [f6da200721](https://linux-hardware.org/?probe=f6da200721) | Mar 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [56e5783575](https://linux-hardware.org/?probe=56e5783575) | Mar 11, 2023 |
| HP            | ProBook 4330s               | Notebook    | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Google        | Reks                        | Notebook    | [f877db79d3](https://linux-hardware.org/?probe=f877db79d3) | Mar 09, 2023 |
| Intel         | ArcherCity                  | Server      | [3ddb00da94](https://linux-hardware.org/?probe=3ddb00da94) | Mar 08, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [a541fe5881](https://linux-hardware.org/?probe=a541fe5881) | Mar 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| Dell          | Latitude 7420               | Notebook    | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| Dell          | 0JC474                      | Desktop     | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [8078d7ca28](https://linux-hardware.org/?probe=8078d7ca28) | Mar 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d70aeca173](https://linux-hardware.org/?probe=d70aeca173) | Mar 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a23a00a71e](https://linux-hardware.org/?probe=a23a00a71e) | Mar 02, 2023 |
| Dell          | Latitude 7420               | Notebook    | [49bdd8711f](https://linux-hardware.org/?probe=49bdd8711f) | Mar 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [2b007293f7](https://linux-hardware.org/?probe=2b007293f7) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd415a086a](https://linux-hardware.org/?probe=bd415a086a) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [dcaa80ec62](https://linux-hardware.org/?probe=dcaa80ec62) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [91405b88cc](https://linux-hardware.org/?probe=91405b88cc) | Feb 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [d3af27a0ac](https://linux-hardware.org/?probe=d3af27a0ac) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d032f0a547](https://linux-hardware.org/?probe=d032f0a547) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b6f7c77e33](https://linux-hardware.org/?probe=b6f7c77e33) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1d62ae4e43](https://linux-hardware.org/?probe=1d62ae4e43) | Feb 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [813066eda5](https://linux-hardware.org/?probe=813066eda5) | Feb 19, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [0496d0bbcf](https://linux-hardware.org/?probe=0496d0bbcf) | Feb 18, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [ba5a46ec10](https://linux-hardware.org/?probe=ba5a46ec10) | Feb 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [fdab522500](https://linux-hardware.org/?probe=fdab522500) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [dd863b4bdf](https://linux-hardware.org/?probe=dd863b4bdf) | Feb 17, 2023 |
| Foxconn       | H67M-S/H67M-V/H67M          | Desktop     | [78dc1c5856](https://linux-hardware.org/?probe=78dc1c5856) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [8de835c5da](https://linux-hardware.org/?probe=8de835c5da) | Feb 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fb6daef60c](https://linux-hardware.org/?probe=fb6daef60c) | Feb 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3206e7be82](https://linux-hardware.org/?probe=3206e7be82) | Feb 16, 2023 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [4891d8306b](https://linux-hardware.org/?probe=4891d8306b) | Feb 15, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [73f7fb3f85](https://linux-hardware.org/?probe=73f7fb3f85) | Feb 15, 2023 |
| Dell          | G15 5520                    | Notebook    | [a5966eaac0](https://linux-hardware.org/?probe=a5966eaac0) | Feb 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [cc77f75f3d](https://linux-hardware.org/?probe=cc77f75f3d) | Feb 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [011e8929fa](https://linux-hardware.org/?probe=011e8929fa) | Feb 15, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [e689bce0ca](https://linux-hardware.org/?probe=e689bce0ca) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [bc1c7ec97f](https://linux-hardware.org/?probe=bc1c7ec97f) | Feb 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7e81f35584](https://linux-hardware.org/?probe=7e81f35584) | Feb 13, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [b1b8672218](https://linux-hardware.org/?probe=b1b8672218) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c17ac89917](https://linux-hardware.org/?probe=c17ac89917) | Feb 11, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [181833b556](https://linux-hardware.org/?probe=181833b556) | Feb 09, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [6a589cafec](https://linux-hardware.org/?probe=6a589cafec) | Feb 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [43b52ad56f](https://linux-hardware.org/?probe=43b52ad56f) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [275ce1a7fc](https://linux-hardware.org/?probe=275ce1a7fc) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef988ae85](https://linux-hardware.org/?probe=aef988ae85) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0f24e9c32c](https://linux-hardware.org/?probe=0f24e9c32c) | Feb 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a838bfb720](https://linux-hardware.org/?probe=a838bfb720) | Feb 04, 2023 |
| Shenzhen W... | AERO 5 Lite Mini PC         | Mini pc     | [cd8f74acd2](https://linux-hardware.org/?probe=cd8f74acd2) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [50727dbbde](https://linux-hardware.org/?probe=50727dbbde) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0b0eaa5c48](https://linux-hardware.org/?probe=0b0eaa5c48) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe2d2d279](https://linux-hardware.org/?probe=2fe2d2d279) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [995da6b474](https://linux-hardware.org/?probe=995da6b474) | Jan 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0323a2bd47](https://linux-hardware.org/?probe=0323a2bd47) | Jan 27, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe7cc7865](https://linux-hardware.org/?probe=2fe7cc7865) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [8ae5c7adec](https://linux-hardware.org/?probe=8ae5c7adec) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b87a9b3447](https://linux-hardware.org/?probe=b87a9b3447) | Jan 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c7c957ccb3](https://linux-hardware.org/?probe=c7c957ccb3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [09735072af](https://linux-hardware.org/?probe=09735072af) | Jan 23, 2023 |
| Dell          | Latitude 7420               | Notebook    | [dc99eb6c92](https://linux-hardware.org/?probe=dc99eb6c92) | Jan 23, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4f65820da4](https://linux-hardware.org/?probe=4f65820da4) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [01e83b7640](https://linux-hardware.org/?probe=01e83b7640) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [70b4ca8de7](https://linux-hardware.org/?probe=70b4ca8de7) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [7fb655b498](https://linux-hardware.org/?probe=7fb655b498) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [397b4da9ab](https://linux-hardware.org/?probe=397b4da9ab) | Jan 21, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [93932bdc92](https://linux-hardware.org/?probe=93932bdc92) | Jan 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2ad3ad8258](https://linux-hardware.org/?probe=2ad3ad8258) | Jan 20, 2023 |
| Dell          | G5 5590                     | Notebook    | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude 5510               | Notebook    | [c9738f8691](https://linux-hardware.org/?probe=c9738f8691) | Jan 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [b5b4cde08e](https://linux-hardware.org/?probe=b5b4cde08e) | Jan 18, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [fa1a881ee9](https://linux-hardware.org/?probe=fa1a881ee9) | Jan 17, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6941e3520e](https://linux-hardware.org/?probe=6941e3520e) | Jan 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [24d62d6974](https://linux-hardware.org/?probe=24d62d6974) | Jan 17, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [5905971b70](https://linux-hardware.org/?probe=5905971b70) | Jan 16, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [389b01b49a](https://linux-hardware.org/?probe=389b01b49a) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4c3d300ccc](https://linux-hardware.org/?probe=4c3d300ccc) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1ad37ae4cc](https://linux-hardware.org/?probe=1ad37ae4cc) | Jan 13, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [d390e11930](https://linux-hardware.org/?probe=d390e11930) | Jan 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [a181d83115](https://linux-hardware.org/?probe=a181d83115) | Jan 11, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4ce659b05d](https://linux-hardware.org/?probe=4ce659b05d) | Jan 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| Star Labs     | Lite                        | Notebook    | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef797585c](https://linux-hardware.org/?probe=aef797585c) | Jan 09, 2023 |
| Dell          | Latitude 7420               | Notebook    | [cd159088a3](https://linux-hardware.org/?probe=cd159088a3) | Jan 09, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [ec306ce0f9](https://linux-hardware.org/?probe=ec306ce0f9) | Jan 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [81269f2363](https://linux-hardware.org/?probe=81269f2363) | Jan 04, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [21b5ec2d81](https://linux-hardware.org/?probe=21b5ec2d81) | Jan 03, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [1b8d741ea3](https://linux-hardware.org/?probe=1b8d741ea3) | Jan 03, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a51048ad0a](https://linux-hardware.org/?probe=a51048ad0a) | Jan 01, 2023 |
| Samsung       | 940XFG                      | Notebook    | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e7ac43e8c3](https://linux-hardware.org/?probe=e7ac43e8c3) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4d613961a4](https://linux-hardware.org/?probe=4d613961a4) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1780cf9c13](https://linux-hardware.org/?probe=1780cf9c13) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c93684da4d](https://linux-hardware.org/?probe=c93684da4d) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c9cadd190](https://linux-hardware.org/?probe=5c9cadd190) | Dec 28, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5ea84f62cb](https://linux-hardware.org/?probe=5ea84f62cb) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3fc3ad1b46](https://linux-hardware.org/?probe=3fc3ad1b46) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [afb738446f](https://linux-hardware.org/?probe=afb738446f) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [91a9d07c9f](https://linux-hardware.org/?probe=91a9d07c9f) | Dec 22, 2022 |
| Intel         | DQ77CP AAG67261-300         | Desktop     | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0b63acf3b2](https://linux-hardware.org/?probe=0b63acf3b2) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [660c9e5023](https://linux-hardware.org/?probe=660c9e5023) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [54fbda3732](https://linux-hardware.org/?probe=54fbda3732) | Dec 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [da494e2be3](https://linux-hardware.org/?probe=da494e2be3) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1bd00059e2](https://linux-hardware.org/?probe=1bd00059e2) | Dec 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7236ad8a5d](https://linux-hardware.org/?probe=7236ad8a5d) | Dec 17, 2022 |
| Dell          | Latitude 7420               | Notebook    | [60f07d5a45](https://linux-hardware.org/?probe=60f07d5a45) | Dec 16, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2991f8736b](https://linux-hardware.org/?probe=2991f8736b) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [69776fdb13](https://linux-hardware.org/?probe=69776fdb13) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [09c89a9bef](https://linux-hardware.org/?probe=09c89a9bef) | Dec 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed707b6698](https://linux-hardware.org/?probe=ed707b6698) | Dec 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c91212b8ed](https://linux-hardware.org/?probe=c91212b8ed) | Dec 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88196a712d](https://linux-hardware.org/?probe=88196a712d) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [57e8e4ab79](https://linux-hardware.org/?probe=57e8e4ab79) | Dec 06, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| Dell          | Latitude 7290               | Notebook    | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | Notebook    | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [7bdc87a5cc](https://linux-hardware.org/?probe=7bdc87a5cc) | Dec 02, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [d17ff52554](https://linux-hardware.org/?probe=d17ff52554) | Dec 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [080e04d17d](https://linux-hardware.org/?probe=080e04d17d) | Dec 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c4ae439087](https://linux-hardware.org/?probe=c4ae439087) | Nov 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c395ef8a4](https://linux-hardware.org/?probe=5c395ef8a4) | Nov 26, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [0c97f1e481](https://linux-hardware.org/?probe=0c97f1e481) | Nov 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [587e23a674](https://linux-hardware.org/?probe=587e23a674) | Nov 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | Notebook    | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4ac6dbf9b](https://linux-hardware.org/?probe=a4ac6dbf9b) | Nov 17, 2022 |
| Chuwi         | X312B                       | Notebook    | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [11dbbdfcc1](https://linux-hardware.org/?probe=11dbbdfcc1) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [02aab6ab70](https://linux-hardware.org/?probe=02aab6ab70) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | Notebook    | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [74a1e6875a](https://linux-hardware.org/?probe=74a1e6875a) | Nov 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c03daa3621](https://linux-hardware.org/?probe=c03daa3621) | Nov 08, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a5700bebdf](https://linux-hardware.org/?probe=a5700bebdf) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d89464b05](https://linux-hardware.org/?probe=5d89464b05) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [8b457c11e8](https://linux-hardware.org/?probe=8b457c11e8) | Oct 23, 2022 |
| Dell          | Latitude E6440              | Notebook    | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| Dell          | Latitude 7400               | Notebook    | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | Notebook    | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | Notebook    | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | 21D0                        | Desktop     | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [26df10ca7d](https://linux-hardware.org/?probe=26df10ca7d) | Oct 02, 2022 |
| Timi          | TM1709                      | Notebook    | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [da0b586e04](https://linux-hardware.org/?probe=da0b586e04) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b389a760a8](https://linux-hardware.org/?probe=b389a760a8) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Pavilion m6                 | Notebook    | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | Notebook    | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [296fc14c83](https://linux-hardware.org/?probe=296fc14c83) | Aug 26, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | Notebook    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | Notebook    | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [531e4340a6](https://linux-hardware.org/?probe=531e4340a6) | Aug 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd2dbeaa0e](https://linux-hardware.org/?probe=bd2dbeaa0e) | Aug 02, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d83f785b08](https://linux-hardware.org/?probe=d83f785b08) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Samsung       | 935XDB                      | Notebook    | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [033c284273](https://linux-hardware.org/?probe=033c284273) | Jul 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8d0399bc8d](https://linux-hardware.org/?probe=8d0399bc8d) | Jul 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ef61582503](https://linux-hardware.org/?probe=ef61582503) | Jul 16, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Jumper        | EZbook                      | Notebook    | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | Notebook    | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1bde29740](https://linux-hardware.org/?probe=c1bde29740) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | Notebook    | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | Desktop     | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Rockchip      | Unknown                     | Soc         | [fcef507e8e](https://linux-hardware.org/?probe=fcef507e8e) | Mar 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5723ec8b7](https://linux-hardware.org/?probe=f5723ec8b7) | Mar 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [27548876c6](https://linux-hardware.org/?probe=27548876c6) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0eaf02ff7d](https://linux-hardware.org/?probe=0eaf02ff7d) | Mar 07, 2022 |
| Dell          | Latitude 9420               | Notebook    | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [34b97f062b](https://linux-hardware.org/?probe=34b97f062b) | Mar 01, 2022 |
| HP            | 21D0                        | Desktop     | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6dd3795cad](https://linux-hardware.org/?probe=6dd3795cad) | Feb 24, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | Notebook    | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45922e4586](https://linux-hardware.org/?probe=45922e4586) | Feb 04, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | Notebook    | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Notebook      | P15SM                       | Notebook    | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4fad903d2a](https://linux-hardware.org/?probe=4fad903d2a) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | Notebook    | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aea80bda1f](https://linux-hardware.org/?probe=aea80bda1f) | Jan 01, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | Notebook    | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7230ad27b7](https://linux-hardware.org/?probe=7230ad27b7) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b6327d329](https://linux-hardware.org/?probe=7b6327d329) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | Notebook    | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Acer          | AOD255                      | Notebook    | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | Notebook    | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | Notebook    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [00ac329183](https://linux-hardware.org/?probe=00ac329183) | Oct 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | Desktop     | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| MSI           | MS-7270                     | Desktop     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | Desktop     | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | Notebook    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [feec038877](https://linux-hardware.org/?probe=feec038877) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | Notebook    | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | Notebook    | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| Dell          | Studio XPS 1640             | Notebook    | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| ASRock        | J4105M                      | Desktop     | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Dell          | Latitude 7370               | Notebook    | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Entroware     | Apollo                      | Notebook    | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | Notebook    | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | Notebook    | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | Notebook    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | 07F37C A01                  | Desktop     | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | Notebook    | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| MSI           | MS-7270                     | Desktop     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 3397                        | Desktop     | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| HP            | 15                          | Notebook    | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | Notebook    | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | Desktop     | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Entroware     | Proteus                     | Notebook    | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | Notebook    | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| HP            | HDX 18                      | Notebook    | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| HP            | EliteBook Folio G1          | Notebook    | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0ceacbca21](https://linux-hardware.org/?probe=0ceacbca21) | Apr 17, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [93033ed87e](https://linux-hardware.org/?probe=93033ed87e) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [6b926d1195](https://linux-hardware.org/?probe=6b926d1195) | Apr 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | Notebook    | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | Desktop     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| HP            | Pavilion m6                 | Notebook    | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | Notebook    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | Notebook    | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | Desktop     | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6ef4606f95](https://linux-hardware.org/?probe=6ef4606f95) | Feb 09, 2021 |
| HP            | 1495                        | Desktop     | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4502d7365](https://linux-hardware.org/?probe=d4502d7365) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [1dbf9cced7](https://linux-hardware.org/?probe=1dbf9cced7) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | Notebook    | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | Notebook    | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [59440917d2](https://linux-hardware.org/?probe=59440917d2) | Jan 01, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Dell          | System XPS L502X            | Notebook    | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| Acer          | Aspire 5551                 | Notebook    | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | Notebook    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| MSI           | MS-7270                     | Desktop     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | Notebook    | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | Notebook    | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | Notebook    | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d8379e8abb](https://linux-hardware.org/?probe=d8379e8abb) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | Notebook    | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | Notebook    | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| MSI           | MS-7270                     | Desktop     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| HP            | 1495                        | Desktop     | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| MSI           | MS-7270                     | Desktop     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eac2b32ee0](https://linux-hardware.org/?probe=eac2b32ee0) | Nov 04, 2020 |
| System76      | Galago Pro                  | Notebook    | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | Notebook    | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Dell          | Dimension 5100              | Desktop     | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3be1cd15b1](https://linux-hardware.org/?probe=3be1cd15b1) | Oct 30, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [e9e4822309](https://linux-hardware.org/?probe=e9e4822309) | Oct 28, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | Notebook    | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| HP            | 1497                        | Desktop     | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | Desktop     | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | Desktop     | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| HP            | 1497                        | Desktop     | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Nvidia        | Tegra                       | Soc         | [9b157b83a5](https://linux-hardware.org/?probe=9b157b83a5) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Dell          | Dimension 5100              | Desktop     | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| HP            | G70                         | Notebook    | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | Notebook    | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | Notebook    | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| Unknown       | RS780-SB700 Unknox          | Desktop     | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASUSTek       | ZN241IC                     | All in one  | [46c001d058](https://linux-hardware.org/?probe=46c001d058) | Aug 10, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| HP            | 8648                        | Desktop     | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Dell          | 0P4T42 A00                  | All in one  | [4924eefd27](https://linux-hardware.org/?probe=4924eefd27) | Aug 03, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | Notebook    | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | Notebook    | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [0e300aa2a8](https://linux-hardware.org/?probe=0e300aa2a8) | Jul 30, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | Notebook    | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| Dell          | Latitude 5480               | Notebook    | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [4615574555](https://linux-hardware.org/?probe=4615574555) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 8425                        | Desktop     | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| HP            | 255 G2                      | Notebook    | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | Notebook    | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [f504426c40](https://linux-hardware.org/?probe=f504426c40) | Jul 04, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [124cdbcc52](https://linux-hardware.org/?probe=124cdbcc52) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | Notebook    | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| SLIMBOOK      | PROX15                      | Notebook    | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | Notebook    | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Lenovo        | ThinkCentre M58 7373BVU     | Desktop     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| Dell          | Latitude E5420              | Notebook    | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | Notebook    | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | Notebook    | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | Notebook    | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [932b22c52a](https://linux-hardware.org/?probe=932b22c52a) | May 16, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [02b85cc578](https://linux-hardware.org/?probe=02b85cc578) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | Notebook    | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | Notebook    | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | Desktop     | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | Notebook    | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Sony UK       | Raspberry Pi 3 Model B      | Soc         | [52f0b7d3fa](https://linux-hardware.org/?probe=52f0b7d3fa) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | Notebook    | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | 0FH884                      | Desktop     | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | XPS M1530                   | Notebook    | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | Notebook    | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | Notebook    | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| ABIT          | KN9                         | Desktop     | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | Notebook    | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | Notebook    | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| ABIT          | KN9                         | Desktop     | [be7c3f4dc9](https://linux-hardware.org/?probe=be7c3f4dc9) | Apr 14, 2020 |
| Dell          | Latitude E5450              | Notebook    | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | Notebook    | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d882ce78cd](https://linux-hardware.org/?probe=d882ce78cd) | Apr 09, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | Notebook    | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | Notebook    | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [79ceb06042](https://linux-hardware.org/?probe=79ceb06042) | Apr 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| ASUSTek       | Z87-K                       | Desktop     | [2ccf545fb8](https://linux-hardware.org/?probe=2ccf545fb8) | Apr 03, 2020 |
| Dell          | 0P301D A00                  | Desktop     | [5996aa0d7b](https://linux-hardware.org/?probe=5996aa0d7b) | Apr 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [cf7a7cb442](https://linux-hardware.org/?probe=cf7a7cb442) | Mar 21, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Lenovo        | ThinkCentre A70 7844Q2G     | Desktop     | [7a3df56f82](https://linux-hardware.org/?probe=7a3df56f82) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b5c9d31ae9](https://linux-hardware.org/?probe=b5c9d31ae9) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [3a37c7a548](https://linux-hardware.org/?probe=3a37c7a548) | Mar 11, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [6672072cc5](https://linux-hardware.org/?probe=6672072cc5) | Mar 03, 2020 |
| ABIT          | KN9                         | Desktop     | [dafc30ae16](https://linux-hardware.org/?probe=dafc30ae16) | Mar 02, 2020 |
| ABIT          | KN9                         | Desktop     | [e26e7f08ca](https://linux-hardware.org/?probe=e26e7f08ca) | Feb 23, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [11d467ac47](https://linux-hardware.org/?probe=11d467ac47) | Feb 22, 2020 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [e53a35010c](https://linux-hardware.org/?probe=e53a35010c) | Feb 22, 2020 |
| Dell          | Precision M6300             | Notebook    | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | Notebook    | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | Notebook    | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ec722fbbfe](https://linux-hardware.org/?probe=ec722fbbfe) | Feb 01, 2020 |
| HP            | 1998                        | Desktop     | [edb9bba986](https://linux-hardware.org/?probe=edb9bba986) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | Notebook    | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | Notebook    | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [0c3d1fcefe](https://linux-hardware.org/?probe=0c3d1fcefe) | Dec 05, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [ab7afebfb6](https://linux-hardware.org/?probe=ab7afebfb6) | Nov 26, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [77c87b6b71](https://linux-hardware.org/?probe=77c87b6b71) | Nov 26, 2019 |
| System76      | Galago Pro                  | Notebook    | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | Notebook    | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ireland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 85        | 11.58%  |
| Ubuntu 18.04       | 44        | 5.99%   |
| Ubuntu 22.04       | 38        | 5.18%   |
| Debian 11          | 27        | 3.68%   |
| Pop!_OS 22.04      | 18        | 2.45%   |
| Zorin 16           | 14        | 1.91%   |
| OpenMandriva 4.2   | 12        | 1.63%   |
| Manjaro            | 12        | 1.63%   |
| Fedora 38          | 12        | 1.63%   |
| ArcoLinux Rolling  | 12        | 1.63%   |
| Arch Rolling       | 12        | 1.63%   |
| Linux Mint 20.2    | 11        | 1.5%    |
| Arch               | 11        | 1.5%    |
| Ubuntu 22.10       | 10        | 1.36%   |
| Linux Mint 21.1    | 10        | 1.36%   |
| Linux Mint 20      | 10        | 1.36%   |
| Fedora 37          | 10        | 1.36%   |
| Fedora 36          | 10        | 1.36%   |
| Debian 10          | 10        | 1.36%   |
| Ubuntu 19.04       | 9         | 1.23%   |
| Pop!_OS 21.10      | 9         | 1.23%   |
| OpenMandriva 23.01 | 9         | 1.23%   |
| Linux Mint 20.3    | 9         | 1.23%   |
| Ubuntu 23.04       | 8         | 1.09%   |
| Pop!_OS 20.10      | 8         | 1.09%   |
| Pop!_OS 20.04      | 7         | 0.95%   |
| OpenMandriva 4.3   | 7         | 0.95%   |
| Linux Mint 21      | 7         | 0.95%   |
| KDE neon 20.04     | 7         | 0.95%   |
| BlackPanther 18.1  | 7         | 0.95%   |
| Ubuntu 19.10       | 6         | 0.82%   |
| Linux Mint 21.2    | 6         | 0.82%   |
| Debian 12          | 6         | 0.82%   |
| Ubuntu 21.10       | 5         | 0.68%   |
| ROSA R11           | 5         | 0.68%   |
| ROSA R10           | 5         | 0.68%   |
| OpenMandriva 23.03 | 5         | 0.68%   |
| Lubuntu 20.04      | 5         | 0.68%   |
| Linux Mint 20.1    | 5         | 0.68%   |
| Linux Mint 19.3    | 5         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 209       | 30.38%  |
| Linux Mint    | 68        | 9.88%   |
| Fedora        | 50        | 7.27%   |
| Debian        | 49        | 7.12%   |
| Pop!_OS       | 42        | 6.1%    |
| OpenMandriva  | 38        | 5.52%   |
| Manjaro       | 26        | 3.78%   |
| Arch          | 23        | 3.34%   |
| Zorin         | 18        | 2.62%   |
| Kubuntu       | 15        | 2.18%   |
| ROSA          | 13        | 1.89%   |
| KDE neon      | 13        | 1.89%   |
| ArcoLinux     | 12        | 1.74%   |
| Elementary    | 10        | 1.45%   |
| Lubuntu       | 8         | 1.16%   |
| Xubuntu       | 7         | 1.02%   |
| SteamOS       | 7         | 1.02%   |
| openSUSE      | 7         | 1.02%   |
| Gentoo        | 7         | 1.02%   |
| BlackPanther  | 7         | 1.02%   |
| Ubuntu Unity  | 5         | 0.73%   |
| Ubuntu MATE   | 5         | 0.73%   |
| Endless       | 5         | 0.73%   |
| Ubuntu Budgie | 4         | 0.58%   |
| Parrot        | 3         | 0.44%   |
| MX            | 3         | 0.44%   |
| Kali          | 3         | 0.44%   |
| Clear Linux   | 3         | 0.44%   |
| Rocky Linux   | 2         | 0.29%   |
| Peppermint    | 2         | 0.29%   |
| Nobara        | 2         | 0.29%   |
| LMDE          | 2         | 0.29%   |
| Linux Lite    | 2         | 0.29%   |
| Garuda Linux  | 2         | 0.29%   |
| CentOS        | 2         | 0.29%   |
| CachyOS       | 2         | 0.29%   |
| Xero          | 1         | 0.15%   |
| Ubuntu Studio | 1         | 0.15%   |
| Trisquel      | 1         | 0.15%   |
| Solus         | 1         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 1.84%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.47%   |
| 5.3.0-46-generic         | 10        | 1.23%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.98%   |
| 5.15.0-56-generic        | 8         | 0.98%   |
| 5.15.0-46-generic        | 8         | 0.98%   |
| 5.19.0-35-generic        | 7         | 0.86%   |
| 5.16.7-desktop-1omv4003  | 7         | 0.86%   |
| 5.10.0-23-amd64          | 7         | 0.86%   |
| 6.2.0-26-generic         | 6         | 0.74%   |
| 5.4.0-52-generic         | 6         | 0.74%   |
| 5.15.0-52-generic        | 6         | 0.74%   |
| 4.18.16-desktop-1bP      | 6         | 0.74%   |
| 6.4.11-desktop-1omv2390  | 5         | 0.61%   |
| 6.2.6-desktop-1omv2390   | 5         | 0.61%   |
| 6.2.0-20-generic         | 5         | 0.61%   |
| 5.4.0-91-generic         | 5         | 0.61%   |
| 5.4.0-48-generic         | 5         | 0.61%   |
| 5.19.0-29-generic        | 5         | 0.61%   |
| 5.15.0-67-generic        | 5         | 0.61%   |
| 5.11.0-27-generic        | 5         | 0.61%   |
| 6.2.6-76060206-generic   | 4         | 0.49%   |
| 6.2.0-36-generic         | 4         | 0.49%   |
| 5.8.0-7630-generic       | 4         | 0.49%   |
| 5.8.0-43-generic         | 4         | 0.49%   |
| 5.4.0-72-generic         | 4         | 0.49%   |
| 5.4.0-47-generic         | 4         | 0.49%   |
| 5.4.0-31-generic         | 4         | 0.49%   |
| 5.4.0-29-generic         | 4         | 0.49%   |
| 5.4.0-26-generic         | 4         | 0.49%   |
| 5.3.0-28-generic         | 4         | 0.49%   |
| 5.19.0-38-generic        | 4         | 0.49%   |
| 5.15.0-60-generic        | 4         | 0.49%   |
| 5.15.0-48-generic        | 4         | 0.49%   |
| 5.10.0-8-amd64           | 4         | 0.49%   |
| 4.18.0-15-generic        | 4         | 0.49%   |
| 6.3.8-200.fc38.x86_64    | 3         | 0.37%   |
| 6.2.0-32-generic         | 3         | 0.37%   |
| 6.1.0-1parrot1-amd64     | 3         | 0.37%   |
| 6.0.6-76060006-generic   | 3         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 116       | 15.22%  |
| 5.15.0  | 62        | 8.14%   |
| 5.19.0  | 37        | 4.86%   |
| 4.15.0  | 36        | 4.72%   |
| 5.8.0   | 28        | 3.67%   |
| 5.11.0  | 27        | 3.54%   |
| 5.10.0  | 27        | 3.54%   |
| 6.2.0   | 26        | 3.41%   |
| 5.3.0   | 26        | 3.41%   |
| 5.13.0  | 22        | 2.89%   |
| 5.0.0   | 15        | 1.97%   |
| 5.10.14 | 12        | 1.57%   |
| 4.19.0  | 11        | 1.44%   |
| 4.18.0  | 11        | 1.44%   |
| 6.1.0   | 10        | 1.31%   |
| 6.2.6   | 9         | 1.18%   |
| 6.1.1   | 8         | 1.05%   |
| 5.17.5  | 8         | 1.05%   |
| 5.16.7  | 7         | 0.92%   |
| 4.18.16 | 6         | 0.79%   |
| 6.4.11  | 5         | 0.66%   |
| 6.3.8   | 5         | 0.66%   |
| 6.5.6   | 4         | 0.52%   |
| 6.5.0   | 4         | 0.52%   |
| 6.0.6   | 4         | 0.52%   |
| 5.18.0  | 4         | 0.52%   |
| 5.16.11 | 4         | 0.52%   |
| 4.9.60  | 4         | 0.52%   |
| 6.6.4   | 3         | 0.39%   |
| 6.2.9   | 3         | 0.39%   |
| 6.2.8   | 3         | 0.39%   |
| 6.1.9   | 3         | 0.39%   |
| 6.0.9   | 3         | 0.39%   |
| 6.0.12  | 3         | 0.39%   |
| 6.0.0   | 3         | 0.39%   |
| 5.8.14  | 3         | 0.39%   |
| 5.6.0   | 3         | 0.39%   |
| 5.16.15 | 3         | 0.39%   |
| 5.15.12 | 3         | 0.39%   |
| 5.15.11 | 3         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 122       | 16.29%  |
| 5.15    | 80        | 10.68%  |
| 5.10    | 52        | 6.94%   |
| 5.19    | 44        | 5.87%   |
| 6.2     | 43        | 5.74%   |
| 4.15    | 36        | 4.81%   |
| 5.8     | 35        | 4.67%   |
| 5.11    | 33        | 4.41%   |
| 6.1     | 32        | 4.27%   |
| 5.13    | 28        | 3.74%   |
| 5.3     | 27        | 3.6%    |
| 6.0     | 20        | 2.67%   |
| 5.16    | 17        | 2.27%   |
| 4.18    | 17        | 2.27%   |
| 5.17    | 15        | 2%      |
| 5.0     | 15        | 2%      |
| 6.5     | 13        | 1.74%   |
| 6.4     | 12        | 1.6%    |
| 4.19    | 12        | 1.6%    |
| 5.18    | 11        | 1.47%   |
| 4.9     | 11        | 1.47%   |
| 6.3     | 10        | 1.34%   |
| 5.6     | 10        | 1.34%   |
| 5.14    | 9         | 1.2%    |
| 5.12    | 9         | 1.2%    |
| 5.7     | 7         | 0.93%   |
| 6.6     | 6         | 0.8%    |
| 5.9     | 5         | 0.67%   |
| 4.4     | 3         | 0.4%    |
| 4.10    | 3         | 0.4%    |
| 4.13    | 2         | 0.27%   |
| 4.12    | 2         | 0.27%   |
| 3.10    | 2         | 0.27%   |
| 5.5     | 1         | 0.13%   |
| 5.2     | 1         | 0.13%   |
| 5       | 1         | 0.13%   |
| 4.20    | 1         | 0.13%   |
| 4.14    | 1         | 0.13%   |
| 4.1     | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 632       | 96.34%  |
| i686    | 16        | 2.44%   |
| aarch64 | 8         | 1.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 304       | 43.74%  |
| KDE5            | 121       | 17.41%  |
| Unknown         | 76        | 10.94%  |
| XFCE            | 51        | 7.34%   |
| X-Cinnamon      | 50        | 7.19%   |
| KDE             | 18        | 2.59%   |
| MATE            | 17        | 2.45%   |
| Pantheon        | 9         | 1.29%   |
| LXQt            | 9         | 1.29%   |
| Cinnamon        | 9         | 1.29%   |
| KDE4            | 6         | 0.86%   |
| Unity           | 5         | 0.72%   |
| i3              | 4         | 0.58%   |
| Budgie          | 4         | 0.58%   |
| GNOME Flashback | 3         | 0.43%   |
| LXDE            | 2         | 0.29%   |
| GNOME Classic   | 2         | 0.29%   |
| X-Generic       | 1         | 0.14%   |
| LeftWM          | 1         | 0.14%   |
| Enlightenment   | 1         | 0.14%   |
| DWM             | 1         | 0.14%   |
| BunsenLabs      | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 510       | 76.01%  |
| Wayland | 107       | 15.95%  |
| Unknown | 41        | 6.11%   |
| Tty     | 13        | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 341       | 49.49%  |
| SDDM    | 101       | 14.66%  |
| GDM     | 80        | 11.61%  |
| GDM3    | 70        | 10.16%  |
| LightDM | 68        | 9.87%   |
| TDM     | 19        | 2.76%   |
| KDM     | 6         | 0.87%   |
| LXDM    | 2         | 0.29%   |
| SLiM    | 1         | 0.15%   |
| MDM     | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 325       | 47.38%  |
| en_GB   | 129       | 18.8%   |
| en_US   | 116       | 16.91%  |
| Unknown | 68        | 9.91%   |
| pl_PL   | 14        | 2.04%   |
| C       | 7         | 1.02%   |
| es_ES   | 3         | 0.44%   |
| ru_RU   | 2         | 0.29%   |
| en_IN   | 2         | 0.29%   |
| en_CA   | 2         | 0.29%   |
| bg_BG   | 2         | 0.29%   |
| zh_CN   | 1         | 0.15%   |
| pt_PT   | 1         | 0.15%   |
| pt_BR   | 1         | 0.15%   |
| lt_LT   | 1         | 0.15%   |
| it_IT   | 1         | 0.15%   |
| hu_HU   | 1         | 0.15%   |
| ga_IE   | 1         | 0.15%   |
| fr_FR   | 1         | 0.15%   |
| fr_BE   | 1         | 0.15%   |
| es_SV   | 1         | 0.15%   |
| en_ZA   | 1         | 0.15%   |
| en_DE   | 1         | 0.15%   |
| en_BW   | 1         | 0.15%   |
| en_AU   | 1         | 0.15%   |
| de_DE   | 1         | 0.15%   |
| C.UTF8  | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 341       | 50.82%  |
| EFI  | 330       | 49.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 492       | 72.89%  |
| Btrfs               | 75        | 11.11%  |
| Overlay             | 45        | 6.67%   |
| Unknown             | 23        | 3.41%   |
| Tmpfs               | 17        | 2.52%   |
| Xfs                 | 14        | 2.07%   |
| Zfs                 | 5         | 0.74%   |
| Fuse.fuse-overlayfs | 1         | 0.15%   |
| Fake                | 1         | 0.15%   |
| F2fs                | 1         | 0.15%   |
| Ext3                | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 343       | 50.37%  |
| GPT     | 268       | 39.35%  |
| MBR     | 70        | 10.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 564       | 84.43%  |
| Yes       | 104       | 15.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 505       | 75.37%  |
| Yes       | 165       | 24.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Dell                        | 140       | 21.41%  |
| Lenovo                      | 115       | 17.58%  |
| ASUSTek Computer            | 78        | 11.93%  |
| Hewlett-Packard             | 75        | 11.47%  |
| Gigabyte Technology         | 32        | 4.89%   |
| Acer                        | 29        | 4.43%   |
| MSI                         | 23        | 3.52%   |
| Apple                       | 21        | 3.21%   |
| ASRock                      | 14        | 2.14%   |
| Toshiba                     | 13        | 1.99%   |
| Intel                       | 11        | 1.68%   |
| Samsung Electronics         | 10        | 1.53%   |
| Medion                      | 6         | 0.92%   |
| Foxconn                     | 5         | 0.76%   |
| Chuwi                       | 5         | 0.76%   |
| Valve                       | 4         | 0.61%   |
| TUXEDO                      | 4         | 0.61%   |
| Timi                        | 4         | 0.61%   |
| PC Specialist               | 4         | 0.61%   |
| Packard Bell                | 4         | 0.61%   |
| System76                    | 3         | 0.46%   |
| Raspberry Pi Foundation     | 3         | 0.46%   |
| Notebook                    | 3         | 0.46%   |
| HUAWEI                      | 3         | 0.46%   |
| Fujitsu                     | 3         | 0.46%   |
| Shuttle                     | 2         | 0.31%   |
| Seco                        | 2         | 0.31%   |
| Nvidia                      | 2         | 0.31%   |
| Fujitsu Siemens             | 2         | 0.31%   |
| Entroware                   | 2         | 0.31%   |
| eMachines                   | 2         | 0.31%   |
| AZW                         | 2         | 0.31%   |
| AVITA                       | 2         | 0.31%   |
| Alienware                   | 2         | 0.31%   |
| Unknown                     | 2         | 0.31%   |
| Star Labs                   | 1         | 0.15%   |
| Sony UK                     | 1         | 0.15%   |
| Sony                        | 1         | 0.15%   |
| SLIMBOOK                    | 1         | 0.15%   |
| Shenzhen Wangang Technology | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Dell OptiPlex 7010                | 8         | 1.22%   |
| Dell Latitude 7420                | 8         | 1.22%   |
| ASUS All Series                   | 7         | 1.07%   |
| Lenovo Yoga 6 13ALC7 82UD         | 5         | 0.76%   |
| Gigabyte B450M DS3H               | 5         | 0.76%   |
| Valve Jupiter                     | 4         | 0.61%   |
| Dell OptiPlex 790                 | 4         | 0.61%   |
| Dell OptiPlex 780                 | 4         | 0.61%   |
| Lenovo V145-15AST 81MT            | 3         | 0.46%   |
| HP Compaq 8200 Elite SFF PC       | 3         | 0.46%   |
| Dell OptiPlex 7020                | 3         | 0.46%   |
| Dell Latitude E7240               | 3         | 0.46%   |
| Dell Inspiron 13-5378             | 3         | 0.46%   |
| ASUS ROG STRIX B450-F GAMING      | 3         | 0.46%   |
| ASUS P8P67 PRO                    | 3         | 0.46%   |
| Unknown                           | 3         | 0.46%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.31%   |
| Seco C40                          | 2         | 0.31%   |
| Samsung 750XED                    | 2         | 0.31%   |
| RPi Raspberry Pi                  | 2         | 0.31%   |
| Nvidia Tegra                      | 2         | 0.31%   |
| MSI MS-7C37                       | 2         | 0.31%   |
| MSI MS-7B86                       | 2         | 0.31%   |
| MSI MS-7B79                       | 2         | 0.31%   |
| Medion Akoya E6239                | 2         | 0.31%   |
| Lenovo ThinkStation D20 415892G   | 2         | 0.31%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.31%   |
| Lenovo ThinkCentre E73 10DS000TUK | 2         | 0.31%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.31%   |
| HUAWEI NBLK-WAX9X                 | 2         | 0.31%   |
| HP Pavilion Laptop 15-eh0xxx      | 2         | 0.31%   |
| HP Pavilion g6                    | 2         | 0.31%   |
| HP OMEN by Laptop 15-dc0xxx       | 2         | 0.31%   |
| HP Notebook                       | 2         | 0.31%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.31%   |
| Gigabyte X570 AORUS ULTRA         | 2         | 0.31%   |
| Gigabyte A320M-S2H                | 2         | 0.31%   |
| Foxconn Pro 3500 Series           | 2         | 0.31%   |
| Dell XPS 9320                     | 2         | 0.31%   |
| Dell XPS 13 9310                  | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 51        | 7.8%    |
| Dell Latitude         | 47        | 7.19%   |
| Dell OptiPlex         | 28        | 4.28%   |
| Dell Inspiron         | 24        | 3.67%   |
| Lenovo IdeaPad        | 20        | 3.06%   |
| Acer Aspire           | 20        | 3.06%   |
| HP Pavilion           | 15        | 2.29%   |
| Dell XPS              | 15        | 2.29%   |
| HP EliteBook          | 14        | 2.14%   |
| Dell Precision        | 12        | 1.83%   |
| Toshiba Satellite     | 10        | 1.53%   |
| Lenovo Yoga           | 10        | 1.53%   |
| Lenovo ThinkCentre    | 10        | 1.53%   |
| HP Compaq             | 10        | 1.53%   |
| ASUS TUF              | 9         | 1.38%   |
| ASUS PRIME            | 8         | 1.22%   |
| ASUS ROG              | 7         | 1.07%   |
| ASUS All              | 7         | 1.07%   |
| HP EliteDesk          | 5         | 0.76%   |
| Gigabyte B450M        | 5         | 0.76%   |
| Valve Jupiter         | 4         | 0.61%   |
| Dell Vostro           | 4         | 0.61%   |
| ASUS ZenBook          | 4         | 0.61%   |
| RPi Raspberry         | 3         | 0.46%   |
| Packard Bell EasyNote | 3         | 0.46%   |
| Lenovo V145-15AST     | 3         | 0.46%   |
| Lenovo ThinkBook      | 3         | 0.46%   |
| HP ProBook            | 3         | 0.46%   |
| HP Presario           | 3         | 0.46%   |
| HP OMEN               | 3         | 0.46%   |
| HP Laptop             | 3         | 0.46%   |
| Fujitsu LIFEBOOK      | 3         | 0.46%   |
| Foxconn Pro           | 3         | 0.46%   |
| ASUS VivoBook         | 3         | 0.46%   |
| ASUS P8P67            | 3         | 0.46%   |
| Apple MacBookPro5     | 3         | 0.46%   |
| Acer Nitro            | 3         | 0.46%   |
| Unknown               | 3         | 0.46%   |
| TUXEDO Pulse          | 2         | 0.31%   |
| TUXEDO InfinityBook   | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 66        | 10.09%  |
| 2019    | 61        | 9.33%   |
| 2018    | 57        | 8.72%   |
| 2012    | 52        | 7.95%   |
| 2013    | 51        | 7.8%    |
| 2017    | 46        | 7.03%   |
| 2011    | 45        | 6.88%   |
| 2021    | 36        | 5.5%    |
| 2022    | 35        | 5.35%   |
| 2010    | 32        | 4.89%   |
| 2008    | 31        | 4.74%   |
| 2015    | 30        | 4.59%   |
| 2014    | 26        | 3.98%   |
| 2016    | 24        | 3.67%   |
| 2009    | 20        | 3.06%   |
| 2023    | 12        | 1.83%   |
| 2007    | 10        | 1.53%   |
| 2006    | 8         | 1.22%   |
| Unknown | 8         | 1.22%   |
| 2005    | 3         | 0.46%   |
| 2003    | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 393       | 60.09%  |
| Desktop        | 205       | 31.35%  |
| Mini pc        | 16        | 2.45%   |
| Convertible    | 15        | 2.29%   |
| All in one     | 12        | 1.83%   |
| System on chip | 7         | 1.07%   |
| Tablet         | 4         | 0.61%   |
| Phone          | 1         | 0.15%   |
| Server         | 1         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 599       | 90.76%  |
| Enabled  | 61        | 9.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 651       | 99.54%  |
| Yes  | 3         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 155       | 23.2%   |
| 16.01-24.0      | 144       | 21.56%  |
| 8.01-16.0       | 122       | 18.26%  |
| 3.01-4.0        | 113       | 16.92%  |
| 32.01-64.0      | 70        | 10.48%  |
| 1.01-2.0        | 20        | 2.99%   |
| 64.01-256.0     | 18        | 2.69%   |
| 24.01-32.0      | 13        | 1.95%   |
| 2.01-3.0        | 6         | 0.9%    |
| 0.51-1.0        | 5         | 0.75%   |
| More than 256.0 | 1         | 0.15%   |
| 0.01-0.5        | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 228       | 30.77%  |
| 2.01-3.0   | 188       | 25.37%  |
| 4.01-8.0   | 123       | 16.6%   |
| 3.01-4.0   | 113       | 15.25%  |
| 0.51-1.0   | 42        | 5.67%   |
| 8.01-16.0  | 33        | 4.45%   |
| 0.01-0.5   | 7         | 0.94%   |
| 16.01-24.0 | 5         | 0.67%   |
| 32.01-64.0 | 1         | 0.13%   |
| Unknown    | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 416       | 60.12%  |
| 2      | 162       | 23.41%  |
| 3      | 47        | 6.79%   |
| 4      | 29        | 4.19%   |
| 5      | 14        | 2.02%   |
| 0      | 7         | 1.01%   |
| 7      | 6         | 0.87%   |
| 6      | 5         | 0.72%   |
| 10     | 3         | 0.43%   |
| 11     | 1         | 0.14%   |
| 9      | 1         | 0.14%   |
| 8      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 416       | 62.56%  |
| Yes       | 249       | 37.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 558       | 84.8%   |
| No        | 100       | 15.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 560       | 84.34%  |
| No        | 104       | 15.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 438       | 65.86%  |
| No        | 227       | 34.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 654       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Dublin         | 391       | 56.67%  |
| Cork           | 40        | 5.8%    |
| Limerick       | 23        | 3.33%   |
| Galway         | 21        | 3.04%   |
| Naas           | 13        | 1.88%   |
| Ennis          | 9         | 1.3%    |
| Drogheda       | 8         | 1.16%   |
| Sligo          | 6         | 0.87%   |
| Portlaoise     | 6         | 0.87%   |
| Gorey          | 6         | 0.87%   |
| Enniscorthy    | 6         | 0.87%   |
| Athlone        | 6         | 0.87%   |
| Nenagh         | 5         | 0.72%   |
| Navan          | 5         | 0.72%   |
| Kenmare        | 5         | 0.72%   |
| Wexford        | 4         | 0.58%   |
| Tuam           | 4         | 0.58%   |
| Lucan          | 4         | 0.58%   |
| Loughrea       | 4         | 0.58%   |
| Kilkenny       | 4         | 0.58%   |
| Dún Laoghaire | 4         | 0.58%   |
| Waterford      | 3         | 0.43%   |
| Tullamore      | 3         | 0.43%   |
| Maynooth       | 3         | 0.43%   |
| Letterkenny    | 3         | 0.43%   |
| Cobh           | 3         | 0.43%   |
| Cavan          | 3         | 0.43%   |
| Bray           | 3         | 0.43%   |
| Blackrock      | 3         | 0.43%   |
| Ballina        | 3         | 0.43%   |
| Westport       | 2         | 0.29%   |
| Tobercurry     | 2         | 0.29%   |
| Swords         | 2         | 0.29%   |
| Oranmore       | 2         | 0.29%   |
| Mallow         | 2         | 0.29%   |
| Killorglin     | 2         | 0.29%   |
| Kildare        | 2         | 0.29%   |
| Edenderry      | 2         | 0.29%   |
| Donegal        | 2         | 0.29%   |
| Clonakilty     | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 161       | 242    | 16.72%  |
| WDC                         | 145       | 249    | 15.06%  |
| Seagate                     | 121       | 200    | 12.56%  |
| SanDisk                     | 53        | 72     | 5.5%    |
| Toshiba                     | 52        | 73     | 5.4%    |
| Unknown                     | 50        | 68     | 5.19%   |
| Crucial                     | 47        | 61     | 4.88%   |
| Hitachi                     | 40        | 56     | 4.15%   |
| Kingston                    | 29        | 45     | 3.01%   |
| SK hynix                    | 22        | 24     | 2.28%   |
| Intel                       | 21        | 25     | 2.18%   |
| Micron Technology           | 20        | 22     | 2.08%   |
| KIOXIA                      | 17        | 20     | 1.77%   |
| HGST                        | 16        | 19     | 1.66%   |
| A-DATA Technology           | 11        | 17     | 1.14%   |
| China                       | 9         | 15     | 0.93%   |
| Apple                       | 8         | 10     | 0.83%   |
| Phison                      | 7         | 12     | 0.73%   |
| LITEON                      | 7         | 8      | 0.73%   |
| Fujitsu                     | 7         | 10     | 0.73%   |
| OCZ                         | 6         | 6      | 0.62%   |
| Micron/Crucial Technology   | 6         | 10     | 0.62%   |
| Verbatim                    | 5         | 5      | 0.52%   |
| Kingston Technology Company | 5         | 5      | 0.52%   |
| Transcend                   | 4         | 4      | 0.42%   |
| Silicon Motion              | 4         | 11     | 0.42%   |
| PNY                         | 4         | 4      | 0.42%   |
| KingSpec                    | 4         | 4      | 0.42%   |
| Patriot                     | 3         | 4      | 0.31%   |
| Netac                       | 3         | 3      | 0.31%   |
| LITEONIT                    | 3         | 3      | 0.31%   |
| KingDian                    | 3         | 14     | 0.31%   |
| FORESEE                     | 3         | 4      | 0.31%   |
| ASMT                        | 3         | 5      | 0.31%   |
| Unknown                     | 3         | 3      | 0.31%   |
| Union Memory                | 2         | 2      | 0.21%   |
| Team                        | 2         | 2      | 0.21%   |
| SSSTC                       | 2         | 2      | 0.21%   |
| SABRENT                     | 2         | 3      | 0.21%   |
| QNAP                        | 2         | 18     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 12        | 1.12%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.84%   |
| Unknown MMC Card  64GB                              | 8         | 0.75%   |
| Unknown MMC Card  32GB                              | 8         | 0.75%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 8         | 0.75%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                      | 7         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB                        | 7         | 0.65%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 7         | 0.65%   |
| Kingston SA400S37240G 240GB SSD                     | 7         | 0.65%   |
| Crucial CT500MX500SSD1 500GB                        | 7         | 0.65%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 0.56%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB              | 6         | 0.56%   |
| Seagate ST8000DM004-2CX188 8TB                      | 6         | 0.56%   |
| Seagate ST2000DL003-9VT166 2TB                      | 6         | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.56%   |
| Samsung SSD 850 EVO 250GB                           | 6         | 0.56%   |
| Samsung SSD 840 EVO 250GB                           | 6         | 0.56%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 6         | 0.56%   |
| Samsung NVMe SSD Drive 500GB                        | 6         | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 5         | 0.47%   |
| WDC WD10EURX-83UY4Y0 1TB                            | 5         | 0.47%   |
| Verbatim Vi550 S3 SSD 512GB                         | 5         | 0.47%   |
| Samsung SSD 850 EVO 500GB                           | 5         | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 5         | 0.47%   |
| Kingston SA400S37480G 480GB SSD                     | 5         | 0.47%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.47%   |
| HGST HTS545050A7E680 500GB                          | 5         | 0.47%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 4         | 0.37%   |
| Seagate ST3500312CS 500GB                           | 4         | 0.37%   |
| Seagate Expansion Desk 8TB                          | 4         | 0.37%   |
| SanDisk SSD PLUS 240GB                              | 4         | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                    | 4         | 0.37%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 0.37%   |
| Crucial M4-CT128M4SSD2 128GB                        | 4         | 0.37%   |
| Crucial CT480BX500SSD1 480GB                        | 4         | 0.37%   |
| A-DATA SU650 240GB SSD                              | 4         | 0.37%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 3         | 0.28%   |
| WDC WD3200AAJS-60Z0A0 320GB                         | 3         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 119       | 197    | 32.51%  |
| WDC                 | 115       | 207    | 31.42%  |
| Hitachi             | 40        | 56     | 10.93%  |
| Toshiba             | 35        | 49     | 9.56%   |
| HGST                | 16        | 19     | 4.37%   |
| Samsung Electronics | 11        | 14     | 3.01%   |
| Fujitsu             | 7         | 10     | 1.91%   |
| Apple               | 4         | 4      | 1.09%   |
| Unknown             | 3         | 3      | 0.82%   |
| SABRENT             | 2         | 3      | 0.55%   |
| QNAP                | 2         | 18     | 0.55%   |
| Maxtor              | 2         | 2      | 0.55%   |
| USB3.0              | 1         | 1      | 0.27%   |
| USB                 | 1         | 1      | 0.27%   |
| StoreJet            | 1         | 2      | 0.27%   |
| LaCie               | 1         | 1      | 0.27%   |
| KESU                | 1         | 1      | 0.27%   |
| Inateck             | 1         | 1      | 0.27%   |
| FNK TECH            | 1         | 1      | 0.27%   |
| ExcelStor           | 1         | 2      | 0.27%   |
| DAS                 | 1         | 4      | 0.27%   |
| ASMT                | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 78        | 113    | 25.74%  |
| Crucial             | 43        | 57     | 14.19%  |
| SanDisk             | 29        | 34     | 9.57%   |
| Kingston            | 26        | 41     | 8.58%   |
| WDC                 | 13        | 19     | 4.29%   |
| China               | 9         | 15     | 2.97%   |
| Intel               | 8         | 8      | 2.64%   |
| A-DATA Technology   | 8         | 13     | 2.64%   |
| OCZ                 | 6         | 6      | 1.98%   |
| Micron Technology   | 6         | 6      | 1.98%   |
| LITEON              | 6         | 7      | 1.98%   |
| Verbatim            | 5         | 5      | 1.65%   |
| Toshiba             | 4         | 6      | 1.32%   |
| SK hynix            | 4         | 4      | 1.32%   |
| PNY                 | 4         | 4      | 1.32%   |
| KingSpec            | 4         | 4      | 1.32%   |
| Transcend           | 3         | 3      | 0.99%   |
| Patriot             | 3         | 4      | 0.99%   |
| Netac               | 3         | 3      | 0.99%   |
| LITEONIT            | 3         | 3      | 0.99%   |
| KingDian            | 3         | 14     | 0.99%   |
| FORESEE             | 3         | 4      | 0.99%   |
| Apple               | 3         | 3      | 0.99%   |
| Team                | 2         | 2      | 0.66%   |
| Integral            | 2         | 2      | 0.66%   |
| Fanxiang            | 2         | 2      | 0.66%   |
| ASMT                | 2         | 4      | 0.66%   |
| Unknown             | 2         | 2      | 0.66%   |
| Zheino              | 1         | 1      | 0.33%   |
| Wibtek              | 1         | 2      | 0.33%   |
| W800S               | 1         | 2      | 0.33%   |
| Union Memory        | 1         | 1      | 0.33%   |
| TCSUNBOW            | 1         | 1      | 0.33%   |
| Star                | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| Plextor             | 1         | 1      | 0.33%   |
| Palit               | 1         | 1      | 0.33%   |
| JMicron Technology  | 1         | 1      | 0.33%   |
| Hikvision           | 1         | 1      | 0.33%   |
| Hewlett-Packard     | 1         | 2      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 294       | 597    | 34.39%  |
| SSD     | 269       | 412    | 31.46%  |
| NVMe    | 232       | 334    | 27.13%  |
| MMC     | 47        | 68     | 5.5%    |
| Unknown | 13        | 13     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 460       | 974    | 59.43%  |
| NVMe | 232       | 334    | 29.97%  |
| MMC  | 47        | 68     | 6.07%   |
| SAS  | 35        | 48     | 4.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 339       | 562    | 56.31%  |
| 0.51-1.0   | 174       | 283    | 28.9%   |
| 1.01-2.0   | 46        | 70     | 7.64%   |
| 3.01-4.0   | 16        | 33     | 2.66%   |
| 4.01-10.0  | 15        | 43     | 2.49%   |
| 2.01-3.0   | 9         | 14     | 1.5%    |
| 10.01-20.0 | 3         | 4      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 177       | 25.21%  |
| 101-250        | 176       | 25.07%  |
| 501-1000       | 90        | 12.82%  |
| 51-100         | 54        | 7.69%   |
| 1-20           | 53        | 7.55%   |
| 1001-2000      | 47        | 6.7%    |
| More than 3000 | 40        | 5.7%    |
| 21-50          | 24        | 3.42%   |
| Unknown        | 23        | 3.28%   |
| 2001-3000      | 18        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 275       | 37.36%  |
| 21-50          | 110       | 14.95%  |
| 101-250        | 97        | 13.18%  |
| 51-100         | 94        | 12.77%  |
| 251-500        | 48        | 6.52%   |
| 501-1000       | 46        | 6.25%   |
| Unknown        | 23        | 3.13%   |
| More than 3000 | 19        | 2.58%   |
| 1001-2000      | 15        | 2.04%   |
| 2001-3000      | 9         | 1.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST2000DL003-9VT166 2TB           | 4         | 6      | 5.56%   |
| WDC WD10EALX-009BA0 1TB                  | 3         | 8      | 4.17%   |
| WDC WD3200AVJS-63B6A0 320GB              | 2         | 2      | 2.78%   |
| WDC WD2500AAKX-753CA1 250GB              | 2         | 4      | 2.78%   |
| Hitachi HTS723232A7A364 320GB            | 2         | 2      | 2.78%   |
| Western Digital SN730 500GB              | 1         | 2      | 1.39%   |
| WDC WD7500BPKX-00HPJT0 752GB             | 1         | 1      | 1.39%   |
| WDC WD5000LPCX-24VHAT0 500GB             | 1         | 1      | 1.39%   |
| WDC WD5000HHTZ-04N21V0 500GB             | 1         | 3      | 1.39%   |
| WDC WD5000BEVT-35A0RT0 500GB             | 1         | 1      | 1.39%   |
| WDC WD5000AAKX-001CA0 500GB              | 1         | 2      | 1.39%   |
| WDC WD400JB-00FMA0 40GB                  | 1         | 2      | 1.39%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 1.39%   |
| WDC WD2500BEKT-75A25T0 250GB             | 1         | 1      | 1.39%   |
| WDC WD2500AAKX-603CA0 250GB              | 1         | 1      | 1.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1         | 2      | 1.39%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1         | 1      | 1.39%   |
| WDC WD1001FALS-00E8B0 1TB                | 1         | 2      | 1.39%   |
| Toshiba MQ01ABF050H 500GB                | 1         | 1      | 1.39%   |
| Toshiba MQ01ABD050 500GB                 | 1         | 1      | 1.39%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 1.39%   |
| Toshiba MK1652GSX 160GB                  | 1         | 1      | 1.39%   |
| Toshiba MK1059GSM 1TB                    | 1         | 1      | 1.39%   |
| Toshiba DT01ACA050 500GB                 | 1         | 3      | 1.39%   |
| SK hynix SC308 SATA 256GB SSD            | 1         | 1      | 1.39%   |
| Seagate ST910021AS 100GB                 | 1         | 1      | 1.39%   |
| Seagate ST500LM030-2E717D 500GB          | 1         | 1      | 1.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 1.39%   |
| Seagate ST4000DX001-1CE168 4TB           | 1         | 1      | 1.39%   |
| Seagate ST3500418AS 500GB                | 1         | 3      | 1.39%   |
| Seagate ST320LT009-9WC142 320GB          | 1         | 1      | 1.39%   |
| Seagate ST31500541AS 1TB                 | 1         | 1      | 1.39%   |
| Seagate ST3120026A 120GB                 | 1         | 1      | 1.39%   |
| Seagate ST31000333AS 1TB                 | 1         | 2      | 1.39%   |
| Seagate ST3000DM001-1ER166 3TB           | 1         | 1      | 1.39%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1      | 1.39%   |
| SanDisk SSD PLUS 240GB                   | 1         | 1      | 1.39%   |
| Samsung Electronics SSD 970 EVO Plus 2TB | 1         | 1      | 1.39%   |
| Samsung Electronics HM120JC 120GB        | 1         | 1      | 1.39%   |
| Samsung Electronics HD103SI 1TB          | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 32     | 23.19%  |
| Seagate             | 14        | 19     | 20.29%  |
| Hitachi             | 11        | 15     | 15.94%  |
| Toshiba             | 6         | 8      | 8.7%    |
| Samsung Electronics | 3         | 3      | 4.35%   |
| Micron Technology   | 3         | 3      | 4.35%   |
| SanDisk             | 2         | 2      | 2.9%    |
| HGST                | 2         | 2      | 2.9%    |
| Western Digital     | 1         | 2      | 1.45%   |
| SK hynix            | 1         | 1      | 1.45%   |
| Netac               | 1         | 1      | 1.45%   |
| Maxtor              | 1         | 1      | 1.45%   |
| JMicron Technology  | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |
| Inateck             | 1         | 1      | 1.45%   |
| Fujitsu             | 1         | 1      | 1.45%   |
| DRVEO               | 1         | 1      | 1.45%   |
| China               | 1         | 1      | 1.45%   |
| Apple               | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 32     | 29.09%  |
| Seagate             | 14        | 19     | 25.45%  |
| Hitachi             | 11        | 15     | 20%     |
| Toshiba             | 6         | 8      | 10.91%  |
| Samsung Electronics | 2         | 2      | 3.64%   |
| HGST                | 2         | 2      | 3.64%   |
| Maxtor              | 1         | 1      | 1.82%   |
| Inateck             | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 82     | 75.86%  |
| SSD  | 11        | 11     | 18.97%  |
| NVMe | 3         | 4      | 5.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 50%     |
| KingDian S400 120GB         | 1         | 4      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 50%     |
| KingDian | 1         | 4      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 397       | 793    | 54.99%  |
| Works    | 267       | 529    | 36.98%  |
| Malfunc  | 56        | 97     | 7.76%   |
| Failed   | 2         | 5      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 416       | 50.79%  |
| AMD                            | 116       | 14.16%  |
| Samsung Electronics            | 83        | 10.13%  |
| SanDisk                        | 42        | 5.13%   |
| SK hynix                       | 18        | 2.2%    |
| KIOXIA                         | 16        | 1.95%   |
| Toshiba America Info Systems   | 15        | 1.83%   |
| Nvidia                         | 15        | 1.83%   |
| Micron Technology              | 14        | 1.71%   |
| Marvell Technology Group       | 11        | 1.34%   |
| ASMedia Technology             | 11        | 1.34%   |
| Micron/Crucial Technology      | 10        | 1.22%   |
| Phison Electronics             | 8         | 0.98%   |
| Kingston Technology Company    | 8         | 0.98%   |
| JMicron Technology             | 6         | 0.73%   |
| Union Memory (Shenzhen)        | 4         | 0.49%   |
| Silicon Motion                 | 4         | 0.49%   |
| LSI Logic / Symbios Logic      | 4         | 0.49%   |
| ADATA Technology               | 3         | 0.37%   |
| Solid State Storage Technology | 2         | 0.24%   |
| Realtek Semiconductor          | 2         | 0.24%   |
| O2 Micro                       | 2         | 0.24%   |
| ULi Electronics                | 1         | 0.12%   |
| Transcend                      | 1         | 0.12%   |
| Silicon Image                  | 1         | 0.12%   |
| Seagate Technology             | 1         | 0.12%   |
| Lite-On Technology             | 1         | 0.12%   |
| Lenovo                         | 1         | 0.12%   |
| Broadcom / LSI                 | 1         | 0.12%   |
| Apple                          | 1         | 0.12%   |
| Adaptec                        | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 92        | 9.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 47        | 5.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 39        | 4.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 26        | 2.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25        | 2.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 25        | 2.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19        | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19        | 2.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 18        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 18        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17        | 1.81%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 15        | 1.6%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 1.6%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 14        | 1.49%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 14        | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 14        | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 12        | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11        | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 1.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.07%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 9         | 0.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 0.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 8         | 0.85%   |
| Intel SATA Controller [RAID mode]                                                       | 8         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 0.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 0.75%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7         | 0.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 0.75%   |
| Nvidia MCP79 AHCI Controller                                                            | 6         | 0.64%   |
| Micron 2300 NVMe SSD [Santana]                                                          | 6         | 0.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.64%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 6         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 454       | 54.7%   |
| NVMe | 233       | 28.07%  |
| IDE  | 80        | 9.64%   |
| RAID | 59        | 7.11%   |
| SCSI | 4         | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 489       | 74.66%  |
| AMD    | 157       | 23.97%  |
| ARM    | 8         | 1.22%   |
| iSH    | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 14        | 2.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.21%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.21%   |
| ARM Processor                                 | 8         | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.06%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 1.06%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 7         | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 0.91%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.91%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 5         | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.76%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.61%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.61%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 4         | 0.61%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 4         | 0.61%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 4         | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 0.61%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 0.61%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.61%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.61%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.61%   |
| AMD Custom APU 0405                           | 4         | 0.61%   |
| Intel Pentium 4 CPU 3.00GHz                   | 3         | 0.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.46%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.46%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 133       | 20.18%  |
| Intel Core i7           | 124       | 18.82%  |
| Other                   | 72        | 10.93%  |
| Intel Core i3           | 48        | 7.28%   |
| AMD Ryzen 5             | 38        | 5.77%   |
| Intel Celeron           | 32        | 4.86%   |
| Intel Core 2 Duo        | 29        | 4.4%    |
| AMD Ryzen 7             | 29        | 4.4%    |
| AMD Ryzen 9             | 13        | 1.97%   |
| Intel Pentium           | 11        | 1.67%   |
| Intel Atom              | 11        | 1.67%   |
| Intel Xeon              | 10        | 1.52%   |
| Intel Core 2 Quad       | 8         | 1.21%   |
| AMD Ryzen 3             | 6         | 0.91%   |
| AMD FX                  | 6         | 0.91%   |
| AMD Athlon 64 X2        | 6         | 0.91%   |
| Intel Pentium Dual-Core | 5         | 0.76%   |
| AMD A6                  | 5         | 0.76%   |
| Intel Pentium 4         | 4         | 0.61%   |
| AMD E1                  | 4         | 0.61%   |
| AMD A8                  | 4         | 0.61%   |
| Intel Pentium Silver    | 3         | 0.46%   |
| Intel Core i9           | 3         | 0.46%   |
| Intel Core 2            | 3         | 0.46%   |
| AMD Ryzen Threadripper  | 3         | 0.46%   |
| AMD Ryzen 7 PRO         | 3         | 0.46%   |
| AMD Ryzen 5 PRO         | 3         | 0.46%   |
| AMD Athlon II X4        | 3         | 0.46%   |
| Intel Core m3           | 2         | 0.3%    |
| Intel Celeron Dual-Core | 2         | 0.3%    |
| AMD Sempron             | 2         | 0.3%    |
| AMD Ryzen Embedded      | 2         | 0.3%    |
| AMD Ryzen 3 PRO         | 2         | 0.3%    |
| AMD PRO A10             | 2         | 0.3%    |
| AMD Phenom II X6        | 2         | 0.3%    |
| AMD Phenom II X4        | 2         | 0.3%    |
| AMD E2                  | 2         | 0.3%    |
| AMD A4                  | 2         | 0.3%    |
| AMD A10                 | 2         | 0.3%    |
| Intel Xeon Platinum     | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 267       | 40.64%  |
| 2       | 233       | 35.46%  |
| 6       | 52        | 7.91%   |
| 8       | 41        | 6.24%   |
| 12      | 21        | 3.2%    |
| 1       | 20        | 3.04%   |
| 14      | 7         | 1.07%   |
| 10      | 6         | 0.91%   |
| 3       | 3         | 0.46%   |
| 24      | 2         | 0.3%    |
| Unknown | 2         | 0.3%    |
| 96      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 16      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 647       | 98.93%  |
| 2       | 6         | 0.92%   |
| Unknown | 1         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 439       | 66.62%  |
| 1       | 218       | 33.08%  |
| Unknown | 2         | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 636       | 96.8%   |
| Unknown        | 18        | 2.74%   |
| 32-bit         | 3         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 227       | 33.14%  |
| 0x306a9    | 39        | 5.69%   |
| 0x206a7    | 30        | 4.38%   |
| 0x1067a    | 24        | 3.5%    |
| 0x306c3    | 23        | 3.36%   |
| 0x806ec    | 22        | 3.21%   |
| 0x806e9    | 18        | 2.63%   |
| 0x806c1    | 17        | 2.48%   |
| 0x806ea    | 14        | 2.04%   |
| 0x406e3    | 13        | 1.9%    |
| 0x906ea    | 10        | 1.46%   |
| 0x906e9    | 10        | 1.46%   |
| 0x40651    | 10        | 1.46%   |
| 0x08108109 | 10        | 1.46%   |
| 0x406c4    | 8         | 1.17%   |
| 0x10676    | 8         | 1.17%   |
| 0xa0652    | 7         | 1.02%   |
| 0x30678    | 7         | 1.02%   |
| 0x0a50000c | 7         | 1.02%   |
| 0x08701021 | 7         | 1.02%   |
| 0x506e3    | 6         | 0.88%   |
| 0x306d4    | 6         | 0.88%   |
| 0x0810100b | 6         | 0.88%   |
| 0x20655    | 5         | 0.73%   |
| 0x08108102 | 5         | 0.73%   |
| 0x0800820d | 5         | 0.73%   |
| 0x06006705 | 5         | 0.73%   |
| 0xa0653    | 4         | 0.58%   |
| 0x906a3    | 4         | 0.58%   |
| 0x706a8    | 4         | 0.58%   |
| 0x6fd      | 4         | 0.58%   |
| 0x6fb      | 4         | 0.58%   |
| 0x206c2    | 4         | 0.58%   |
| 0x0600611a | 4         | 0.58%   |
| 0xf43      | 3         | 0.44%   |
| 0x906ed    | 3         | 0.44%   |
| 0x806d1    | 3         | 0.44%   |
| 0x706e5    | 3         | 0.44%   |
| 0x706a1    | 3         | 0.44%   |
| 0x106ca    | 3         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 100       | 15.24%  |
| IvyBridge        | 56        | 8.54%   |
| SandyBridge      | 47        | 7.16%   |
| Haswell          | 47        | 7.16%   |
| Unknown          | 40        | 6.1%    |
| Penryn           | 36        | 5.49%   |
| TigerLake        | 30        | 4.57%   |
| Skylake          | 30        | 4.57%   |
| Zen 2            | 29        | 4.42%   |
| Zen+             | 27        | 4.12%   |
| Silvermont       | 21        | 3.2%    |
| Westmere         | 19        | 2.9%    |
| Core             | 15        | 2.29%   |
| Zen 3            | 14        | 2.13%   |
| CometLake        | 14        | 2.13%   |
| Zen              | 13        | 1.98%   |
| Goldmont plus    | 12        | 1.83%   |
| Alderlake Hybrid | 12        | 1.83%   |
| Excavator        | 11        | 1.68%   |
| K10              | 10        | 1.52%   |
| Piledriver       | 9         | 1.37%   |
| K8 Hammer        | 9         | 1.37%   |
| IceLake          | 8         | 1.22%   |
| Broadwell        | 8         | 1.22%   |
| Nehalem          | 6         | 0.91%   |
| NetBurst         | 5         | 0.76%   |
| Bonnell          | 5         | 0.76%   |
| Puma             | 4         | 0.61%   |
| P6               | 4         | 0.61%   |
| Jaguar           | 4         | 0.61%   |
| Bobcat           | 4         | 0.61%   |
| Goldmont         | 3         | 0.46%   |
| Tremont          | 1         | 0.15%   |
| Steamroller      | 1         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.15%   |
| Bulldozer        | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 379       | 50.13%  |
| Nvidia            | 190       | 25.13%  |
| AMD               | 186       | 24.6%   |
| ASPEED Technology | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 3.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 3.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 3.45%   |
| Intel HD Graphics 620                                                                    | 19        | 2.43%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 18        | 2.3%    |
| Intel UHD Graphics 620                                                                   | 17        | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 1.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 1.4%    |
| Intel HD Graphics 630                                                                    | 11        | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.02%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 1.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.02%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 8         | 1.02%   |
| AMD Lucienne                                                                             | 8         | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.77%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 6         | 0.77%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 0.77%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.77%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.64%   |
| AMD Rembrandt [Radeon 680M]                                                              | 5         | 0.64%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 5         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 285       | 42.92%  |
| 1 x AMD        | 151       | 22.74%  |
| 1 x Nvidia     | 104       | 15.66%  |
| Intel + Nvidia | 74        | 11.14%  |
| 2 x AMD        | 15        | 2.26%   |
| AMD + Nvidia   | 11        | 1.66%   |
| Other          | 9         | 1.36%   |
| Intel + AMD    | 9         | 1.36%   |
| 2 x Intel      | 3         | 0.45%   |
| 2 x Nvidia     | 2         | 0.3%    |
| 1 x ASPEED     | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 535       | 80.45%  |
| Proprietary | 97        | 14.59%  |
| Unknown     | 33        | 4.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 397       | 58.3%   |
| 0.01-0.5   | 69        | 10.13%  |
| 1.01-2.0   | 62        | 9.1%    |
| 3.01-4.0   | 48        | 7.05%   |
| 0.51-1.0   | 46        | 6.75%   |
| 7.01-8.0   | 29        | 4.26%   |
| 5.01-6.0   | 18        | 2.64%   |
| 2.01-3.0   | 5         | 0.73%   |
| 8.01-16.0  | 5         | 0.73%   |
| 16.01-24.0 | 2         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 81        | 11.14%  |
| AU Optronics            | 80        | 11%     |
| Dell                    | 78        | 10.73%  |
| LG Display              | 68        | 9.35%   |
| Samsung Electronics     | 60        | 8.25%   |
| Chimei Innolux          | 50        | 6.88%   |
| Acer                    | 24        | 3.3%    |
| Hewlett-Packard         | 23        | 3.16%   |
| BenQ                    | 22        | 3.03%   |
| Sharp                   | 21        | 2.89%   |
| Apple                   | 19        | 2.61%   |
| Philips                 | 18        | 2.48%   |
| Lenovo                  | 17        | 2.34%   |
| Goldstar                | 17        | 2.34%   |
| AOC                     | 16        | 2.2%    |
| ViewSonic               | 13        | 1.79%   |
| Iiyama                  | 13        | 1.79%   |
| PANDA                   | 9         | 1.24%   |
| Chi Mei Optoelectronics | 8         | 1.1%    |
| Sony                    | 5         | 0.69%   |
| LG Philips              | 5         | 0.69%   |
| Vestel Elektronik       | 4         | 0.55%   |
| MSI                     | 4         | 0.55%   |
| InfoVision              | 4         | 0.55%   |
| ASUSTek Computer        | 4         | 0.55%   |
| Ancor Communications    | 4         | 0.55%   |
| ___                     | 3         | 0.41%   |
| Valve                   | 3         | 0.41%   |
| Unknown                 | 3         | 0.41%   |
| Toshiba                 | 3         | 0.41%   |
| HKC                     | 3         | 0.41%   |
| HannStar                | 3         | 0.41%   |
| CSO                     | 3         | 0.41%   |
| OEM                     | 2         | 0.28%   |
| NEC Computers           | 2         | 0.28%   |
| MiTAC                   | 2         | 0.28%   |
| KDB                     | 2         | 0.28%   |
| HannStar Display        | 2         | 0.28%   |
| CPT                     | 2         | 0.28%   |
| BOE Technology Group    | 2         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                  | 9         | 1.18%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch              | 8         | 1.05%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                      | 8         | 1.05%   |
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                   | 5         | 0.66%   |
| BOE LCD Monitor BOE0964 1920x1200 286x179mm 13.3-inch                  | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 5         | 0.66%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 4         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 4         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 4         | 0.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 4         | 0.52%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 4         | 0.52%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch                | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 4         | 0.52%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 4         | 0.52%   |
| ___ LCDTV16 ___9000 1360x768                                           | 3         | 0.39%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 3         | 0.39%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 3         | 0.39%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 3         | 0.39%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 3         | 0.39%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 3         | 0.39%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3         | 0.39%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 3         | 0.39%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 3         | 0.39%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch            | 3         | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 3         | 0.39%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                | 3         | 0.39%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                       | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch       | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch         | 3         | 0.39%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch                | 2         | 0.26%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 2         | 0.26%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                | 2         | 0.26%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                | 2         | 0.26%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 2         | 0.26%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch   | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 319       | 46.1%   |
| 1366x768 (WXGA)    | 114       | 16.47%  |
| 3840x2160 (4K)     | 42        | 6.07%   |
| 2560x1440 (QHD)    | 42        | 6.07%   |
| 1920x1200 (WUXGA)  | 23        | 3.32%   |
| 1600x900 (HD+)     | 21        | 3.03%   |
| 1280x1024 (SXGA)   | 20        | 2.89%   |
| 1440x900 (WXGA+)   | 19        | 2.75%   |
| 1280x800 (WXGA)    | 14        | 2.02%   |
| 3440x1440          | 10        | 1.45%   |
| 1360x768           | 8         | 1.16%   |
| Unknown            | 8         | 1.16%   |
| 2560x1600          | 6         | 0.87%   |
| 1680x1050 (WSXGA+) | 6         | 0.87%   |
| 2880x1800          | 5         | 0.72%   |
| 800x1280           | 4         | 0.58%   |
| 3840x1080          | 4         | 0.58%   |
| 3840x2400          | 3         | 0.43%   |
| 1600x1200          | 3         | 0.43%   |
| 1024x600           | 3         | 0.43%   |
| 3456x2160          | 2         | 0.29%   |
| 3200x1800 (QHD+)   | 2         | 0.29%   |
| 2560x1080          | 2         | 0.29%   |
| 2160x1440          | 2         | 0.29%   |
| 1920x540           | 2         | 0.29%   |
| 1024x768 (XGA)     | 2         | 0.29%   |
| 6400x2160          | 1         | 0.14%   |
| 5280x2560          | 1         | 0.14%   |
| 4480x1440          | 1         | 0.14%   |
| 3600x1080          | 1         | 0.14%   |
| 2256x1504          | 1         | 0.14%   |
| 1280x960           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 187       | 25.65%  |
| 14      | 75        | 10.29%  |
| 27      | 70        | 9.6%    |
| 13      | 66        | 9.05%   |
| 24      | 53        | 7.27%   |
| 21      | 47        | 6.45%   |
| 23      | 42        | 5.76%   |
| 17      | 33        | 4.53%   |
| Unknown | 29        | 3.98%   |
| 12      | 18        | 2.47%   |
| 19      | 16        | 2.19%   |
| 34      | 12        | 1.65%   |
| 31      | 12        | 1.65%   |
| 84      | 7         | 0.96%   |
| 18      | 7         | 0.96%   |
| 16      | 6         | 0.82%   |
| 11      | 6         | 0.82%   |
| 72      | 5         | 0.69%   |
| 32      | 5         | 0.69%   |
| 20      | 5         | 0.69%   |
| 33      | 4         | 0.55%   |
| 40      | 3         | 0.41%   |
| 25      | 3         | 0.41%   |
| 22      | 3         | 0.41%   |
| 10      | 3         | 0.41%   |
| 7       | 3         | 0.41%   |
| 49      | 2         | 0.27%   |
| 29      | 2         | 0.27%   |
| 65      | 1         | 0.14%   |
| 46      | 1         | 0.14%   |
| 35      | 1         | 0.14%   |
| 26      | 1         | 0.14%   |
| 3       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 290       | 40.5%   |
| 501-600     | 150       | 20.95%  |
| 401-500     | 71        | 9.92%   |
| 201-300     | 71        | 9.92%   |
| 351-400     | 38        | 5.31%   |
| Unknown     | 29        | 4.05%   |
| 601-700     | 22        | 3.07%   |
| 701-800     | 21        | 2.93%   |
| 1501-2000   | 12        | 1.68%   |
| 801-900     | 4         | 0.56%   |
| 1001-1500   | 4         | 0.56%   |
| 1-100       | 4         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 487       | 76.57%  |
| 16/10   | 76        | 11.95%  |
| Unknown | 23        | 3.62%   |
| 5/4     | 19        | 2.99%   |
| 21/9    | 13        | 2.04%   |
| 4/3     | 8         | 1.26%   |
| 3/2     | 5         | 0.79%   |
| 0.67    | 3         | 0.47%   |
| 6/5     | 1         | 0.16%   |
| 32/9    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 184       | 25.27%  |
| 201-250        | 118       | 16.21%  |
| 81-90          | 105       | 14.42%  |
| 301-350        | 72        | 9.89%   |
| 71-80          | 38        | 5.22%   |
| 351-500        | 34        | 4.67%   |
| 151-200        | 31        | 4.26%   |
| Unknown        | 29        | 3.98%   |
| 251-300        | 22        | 3.02%   |
| 141-150        | 17        | 2.34%   |
| 121-130        | 17        | 2.34%   |
| 61-70          | 16        | 2.2%    |
| More than 1000 | 13        | 1.79%   |
| 111-120        | 8         | 1.1%    |
| 51-60          | 6         | 0.82%   |
| 501-1000       | 6         | 0.82%   |
| 1-40           | 4         | 0.55%   |
| 131-140        | 4         | 0.55%   |
| 41-50          | 3         | 0.41%   |
| 91-100         | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 215       | 30.63%  |
| 51-100        | 200       | 28.49%  |
| 101-120       | 171       | 24.36%  |
| 161-240       | 55        | 7.83%   |
| Unknown       | 29        | 4.13%   |
| More than 240 | 18        | 2.56%   |
| 1-50          | 14        | 1.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 520       | 76.7%   |
| 2     | 108       | 15.93%  |
| 0     | 29        | 4.28%   |
| 3     | 20        | 2.95%   |
| 4     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 357       | 34.53%  |
| Realtek Semiconductor             | 327       | 31.62%  |
| Qualcomm Atheros                  | 92        | 8.9%    |
| Broadcom                          | 66        | 6.38%   |
| Ralink Technology                 | 21        | 2.03%   |
| MediaTek                          | 19        | 1.84%   |
| TP-Link                           | 18        | 1.74%   |
| Nvidia                            | 14        | 1.35%   |
| Broadcom Limited                  | 13        | 1.26%   |
| Marvell Technology Group          | 12        | 1.16%   |
| Ralink                            | 11        | 1.06%   |
| Microsoft                         | 9         | 0.87%   |
| Samsung Electronics               | 6         | 0.58%   |
| Lenovo                            | 6         | 0.58%   |
| ASIX Electronics                  | 6         | 0.58%   |
| OPPO Electronics                  | 5         | 0.48%   |
| Ericsson Business Mobile Networks | 5         | 0.48%   |
| DisplayLink                       | 5         | 0.48%   |
| Xiaomi                            | 3         | 0.29%   |
| NetGear                           | 3         | 0.29%   |
| Qualcomm Atheros Communications   | 2         | 0.19%   |
| Qualcomm                          | 2         | 0.19%   |
| Microchip Technology              | 2         | 0.19%   |
| ICS Advent                        | 2         | 0.19%   |
| Huawei Technologies               | 2         | 0.19%   |
| Dell                              | 2         | 0.19%   |
| Belkin Components                 | 2         | 0.19%   |
| Xilinx                            | 1         | 0.1%    |
| Van Ooijen Technische Informatica | 1         | 0.1%    |
| ULi Electronics                   | 1         | 0.1%    |
| Toshiba                           | 1         | 0.1%    |
| T & A Mobile Phones               | 1         | 0.1%    |
| Standard Microsystems             | 1         | 0.1%    |
| Sierra Wireless                   | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.1%    |
| NetXen Incorporated               | 1         | 0.1%    |
| LSI                               | 1         | 0.1%    |
| LG Electronics                    | 1         | 0.1%    |
| JMicron Technology                | 1         | 0.1%    |
| IMC Networks                      | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 200       | 16.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 44        | 3.61%   |
| Intel Wi-Fi 6 AX200                                               | 41        | 3.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 3.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 22        | 1.8%    |
| Intel Wireless 8265 / 8275                                        | 20        | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 20        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.23%   |
| Intel Wireless 7260                                               | 15        | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.15%   |
| Intel Wireless 8260                                               | 13        | 1.07%   |
| Realtek 802.11ac NIC                                              | 12        | 0.98%   |
| Intel Wireless 7265                                               | 12        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.9%    |
| Ralink MT7601U Wireless Adapter                                   | 11        | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 11        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 10        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 0.74%   |
| Intel Wireless-AC 9260                                            | 9         | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 0.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 8         | 0.66%   |
| Intel Wireless 3165                                               | 8         | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                    | 7         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7         | 0.57%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 7         | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 280       | 46.74%  |
| Realtek Semiconductor             | 92        | 15.36%  |
| Qualcomm Atheros                  | 83        | 13.86%  |
| Broadcom                          | 46        | 7.68%   |
| Ralink Technology                 | 21        | 3.51%   |
| TP-Link                           | 18        | 3.01%   |
| MediaTek                          | 16        | 2.67%   |
| Ralink                            | 11        | 1.84%   |
| Microsoft                         | 8         | 1.34%   |
| Broadcom Limited                  | 5         | 0.83%   |
| NetGear                           | 3         | 0.5%    |
| Qualcomm Atheros Communications   | 2         | 0.33%   |
| Qualcomm                          | 2         | 0.33%   |
| Ericsson Business Mobile Networks | 2         | 0.33%   |
| Dell                              | 2         | 0.33%   |
| Belkin Components                 | 2         | 0.33%   |
| Sierra Wireless                   | 1         | 0.17%   |
| Marvell Technology Group          | 1         | 0.17%   |
| LG Electronics                    | 1         | 0.17%   |
| IMC Networks                      | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |
| Apple                             | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 41        | 6.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 3.81%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 3.64%   |
| Intel Wireless 8265 / 8275                                              | 20        | 3.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 2.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.48%   |
| Intel Wireless 7260                                                     | 15        | 2.48%   |
| Intel Wireless 8260                                                     | 13        | 2.15%   |
| Realtek 802.11ac NIC                                                    | 12        | 1.99%   |
| Intel Wireless 7265                                                     | 12        | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.82%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.49%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 1.49%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 8         | 1.32%   |
| Intel Wireless 3165                                                     | 8         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.32%   |
| Ralink RT5370 Wireless Adapter                                          | 7         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 7         | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.16%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 6         | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 6         | 0.99%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 5         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.83%   |
| Intel Wireless 3160                                                     | 5         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.83%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 5         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 281       | 47.63%  |
| Intel                         | 180       | 30.51%  |
| Broadcom                      | 30        | 5.08%   |
| Qualcomm Atheros              | 18        | 3.05%   |
| Nvidia                        | 14        | 2.37%   |
| Marvell Technology Group      | 11        | 1.86%   |
| Broadcom Limited              | 9         | 1.53%   |
| Lenovo                        | 6         | 1.02%   |
| ASIX Electronics              | 6         | 1.02%   |
| OPPO Electronics              | 5         | 0.85%   |
| DisplayLink                   | 5         | 0.85%   |
| Samsung Electronics           | 4         | 0.68%   |
| Xiaomi                        | 3         | 0.51%   |
| MediaTek                      | 2         | 0.34%   |
| ICS Advent                    | 2         | 0.34%   |
| Xilinx                        | 1         | 0.17%   |
| ULi Electronics               | 1         | 0.17%   |
| T & A Mobile Phones           | 1         | 0.17%   |
| Standard Microsystems         | 1         | 0.17%   |
| OnePlus Technology (Shenzhen) | 1         | 0.17%   |
| NetXen Incorporated           | 1         | 0.17%   |
| Microsoft                     | 1         | 0.17%   |
| Microchip Technology          | 1         | 0.17%   |
| JMicron Technology            | 1         | 0.17%   |
| Huawei Technologies           | 1         | 0.17%   |
| HMD Global                    | 1         | 0.17%   |
| Aquantia                      | 1         | 0.17%   |
| ADMtek                        | 1         | 0.17%   |
| 3Com                          | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 200       | 33.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 44        | 7.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 6.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 5.01%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 2.34%   |
| Intel I211 Gigabit Network Connection                             | 11        | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.5%    |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.34%   |
| Nvidia MCP79 Ethernet                                             | 7         | 1.17%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7         | 1.17%   |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 5         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.83%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.67%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 3         | 0.5%    |
| Intel Ethernet Controller I225-LM                                 | 3         | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 3         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 557       | 49.29%  |
| Ethernet | 557       | 49.29%  |
| Modem    | 16        | 1.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 415       | 60.23%  |
| Ethernet | 274       | 39.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 372       | 56.45%  |
| 1     | 257       | 39%     |
| 0     | 15        | 2.28%   |
| 3     | 13        | 1.97%   |
| 6     | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 566       | 84.98%  |
| Yes  | 100       | 15.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 225       | 50.45%  |
| Realtek Semiconductor           | 42        | 9.42%   |
| Broadcom                        | 26        | 5.83%   |
| Qualcomm Atheros Communications | 25        | 5.61%   |
| IMC Networks                    | 25        | 5.61%   |
| Cambridge Silicon Radio         | 24        | 5.38%   |
| Lite-On Technology              | 17        | 3.81%   |
| Apple                           | 17        | 3.81%   |
| Foxconn / Hon Hai               | 8         | 1.79%   |
| Dell                            | 8         | 1.79%   |
| ASUSTek Computer                | 6         | 1.35%   |
| Hewlett-Packard                 | 5         | 1.12%   |
| Toshiba                         | 4         | 0.9%    |
| Realtek                         | 4         | 0.9%    |
| TP-Link                         | 2         | 0.45%   |
| Foxconn International           | 2         | 0.45%   |
| Belkin Components               | 2         | 0.45%   |
| Ralink                          | 1         | 0.22%   |
| MediaTek                        | 1         | 0.22%   |
| Edimax Technology               | 1         | 0.22%   |
| Conwise Technology              | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 78        | 17.45%  |
| Intel Bluetooth Device                              | 60        | 13.42%  |
| Intel AX200 Bluetooth                               | 38        | 8.5%    |
| Realtek Bluetooth Radio                             | 29        | 6.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24        | 5.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 4.92%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 1.79%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.57%   |
| Intel AX210 Bluetooth                               | 6         | 1.34%   |
| IMC Networks Wireless_Device                        | 6         | 1.34%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.34%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.12%   |
| IMC Networks Bluetooth Device                       | 5         | 1.12%   |
| Apple Bluetooth Host Controller                     | 5         | 1.12%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.89%   |
| Realtek Bluetooth Radio                             | 4         | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.89%   |
| IMC Networks 802.11ac WLAN Adapter                  | 4         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.89%   |
| Apple Bluetooth HCI                                 | 4         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.67%   |
| Lite-On Wireless_Device                             | 3         | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.67%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.67%   |
| TP-Link UB500 Adapter                               | 2         | 0.45%   |
| Toshiba Bluetooth Device                            | 2         | 0.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.45%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.45%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 469       | 50.65%  |
| AMD                                             | 198       | 21.38%  |
| Nvidia                                          | 148       | 15.98%  |
| Realtek Semiconductor                           | 12        | 1.3%    |
| Plantronics                                     | 11        | 1.19%   |
| C-Media Electronics                             | 8         | 0.86%   |
| Creative Labs                                   | 7         | 0.76%   |
| Logitech                                        | 6         | 0.65%   |
| Kingston Technology                             | 6         | 0.65%   |
| GN Netcom                                       | 6         | 0.65%   |
| Creative Technology                             | 5         | 0.54%   |
| Lenovo                                          | 4         | 0.43%   |
| Texas Instruments                               | 3         | 0.32%   |
| RODE Microphones                                | 3         | 0.32%   |
| Sony                                            | 2         | 0.22%   |
| Micronas                                        | 2         | 0.22%   |
| JMTek                                           | 2         | 0.22%   |
| Giga-Byte Technology                            | 2         | 0.22%   |
| Generalplus Technology                          | 2         | 0.22%   |
| Ensoniq                                         | 2         | 0.22%   |
| Dell                                            | 2         | 0.22%   |
| Blue Microphones                                | 2         | 0.22%   |
| VIA Technologies                                | 1         | 0.11%   |
| ULi Electronics                                 | 1         | 0.11%   |
| Turtle Beach                                    | 1         | 0.11%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.11%   |
| SAVITECH                                        | 1         | 0.11%   |
| Razer USA                                       | 1         | 0.11%   |
| No brand                                        | 1         | 0.11%   |
| Native Instruments                              | 1         | 0.11%   |
| M-Audio                                         | 1         | 0.11%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.11%   |
| KTMicro                                         | 1         | 0.11%   |
| Huawei Technologies                             | 1         | 0.11%   |
| Focusrite-Novation                              | 1         | 0.11%   |
| FiiO Electronics Technology                     | 1         | 0.11%   |
| ESS Technology                                  | 1         | 0.11%   |
| DSEA A/S                                        | 1         | 0.11%   |
| Corsair                                         | 1         | 0.11%   |
| Conexant Systems                                | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 66        | 6.04%   |
| Intel Sunrise Point-LP HD Audio                                                   | 59        | 5.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 53        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 48        | 4.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 30        | 2.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 29        | 2.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 27        | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 22        | 2.01%   |
| AMD Starship/Matisse HD Audio Controller                                          | 21        | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 20        | 1.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 19        | 1.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 18        | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 18        | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 17        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 17        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 17        | 1.56%   |
| AMD FCH Azalia Controller                                                         | 17        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                        | 16        | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                                     | 14        | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                          | 14        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 13        | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 13        | 1.19%   |
| Realtek Semiconductor USB Audio                                                   | 12        | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                             | 12        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                         | 12        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 12        | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 12        | 1.1%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 12        | 1.1%    |
| Intel 8 Series HD Audio Controller                                                | 12        | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12        | 1.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 12        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                                     | 11        | 1.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 11        | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 11        | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                                     | 10        | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 9         | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9         | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 9         | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                                     | 8         | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 8         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 83        | 20.39%  |
| SK hynix            | 81        | 19.9%   |
| Micron Technology   | 42        | 10.32%  |
| Unknown             | 37        | 9.09%   |
| Crucial             | 37        | 9.09%   |
| Corsair             | 36        | 8.85%   |
| Kingston            | 35        | 8.6%    |
| Ramaxel Technology  | 10        | 2.46%   |
| G.Skill             | 9         | 2.21%   |
| Elpida              | 6         | 1.47%   |
| Nanya Technology    | 5         | 1.23%   |
| Unknown (ABCD)      | 4         | 0.98%   |
| Team                | 3         | 0.74%   |
| Patriot             | 3         | 0.74%   |
| Apacer              | 2         | 0.49%   |
| A-DATA Technology   | 2         | 0.49%   |
| A Force             | 2         | 0.49%   |
| Transcend           | 1         | 0.25%   |
| Toshiba             | 1         | 0.25%   |
| Silicon Power       | 1         | 0.25%   |
| SHARETRONIC         | 1         | 0.25%   |
| OSV                 | 1         | 0.25%   |
| Infineon            | 1         | 0.25%   |
| CSX                 | 1         | 0.25%   |
| BiNFUL              | 1         | 0.25%   |
| 4ea5                | 1         | 0.25%   |
| Unknown             | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.37%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.92%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.92%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.69%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.69%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 3         | 0.69%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.69%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 3         | 0.69%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 3         | 0.69%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.46%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.46%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 2         | 0.46%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.46%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 2         | 0.46%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.46%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.46%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.46%   |
| SK hynix RAM H54G56CYRBX247N 2GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.46%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.46%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 162       | 46.02%  |
| DDR3    | 105       | 29.83%  |
| LPDDR4  | 20        | 5.68%   |
| DDR2    | 16        | 4.55%   |
| Unknown | 14        | 3.98%   |
| SDRAM   | 11        | 3.13%   |
| LPDDR3  | 8         | 2.27%   |
| DDR5    | 7         | 1.99%   |
| LPDDR5  | 3         | 0.85%   |
| DRAM    | 3         | 0.85%   |
| DDR     | 3         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 208       | 58.92%  |
| DIMM         | 109       | 30.88%  |
| Row Of Chips | 29        | 8.22%   |
| Chip         | 4         | 1.13%   |
| Unknown      | 3         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 148       | 38.44%  |
| 4096  | 102       | 26.49%  |
| 16384 | 57        | 14.81%  |
| 2048  | 43        | 11.17%  |
| 32768 | 17        | 4.42%   |
| 1024  | 14        | 3.64%   |
| 128   | 2         | 0.52%   |
| 512   | 1         | 0.26%   |
| 256   | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 70        | 18.18%  |
| 3200    | 56        | 14.55%  |
| 2667    | 50        | 12.99%  |
| 2400    | 27        | 7.01%   |
| 2133    | 24        | 6.23%   |
| 1333    | 21        | 5.45%   |
| 800     | 15        | 3.9%    |
| 667     | 12        | 3.12%   |
| 4267    | 11        | 2.86%   |
| 1334    | 10        | 2.6%    |
| 3600    | 9         | 2.34%   |
| 3266    | 9         | 2.34%   |
| 1867    | 7         | 1.82%   |
| 4800    | 6         | 1.56%   |
| 1067    | 6         | 1.56%   |
| Unknown | 5         | 1.3%    |
| 8400    | 3         | 0.78%   |
| 6400    | 3         | 0.78%   |
| 4266    | 3         | 0.78%   |
| 3533    | 3         | 0.78%   |
| 3400    | 3         | 0.78%   |
| 1866    | 3         | 0.78%   |
| 1800    | 3         | 0.78%   |
| 533     | 3         | 0.78%   |
| 4199    | 2         | 0.52%   |
| 3800    | 2         | 0.52%   |
| 2666    | 2         | 0.52%   |
| 2048    | 2         | 0.52%   |
| 1648    | 2         | 0.52%   |
| 1066    | 2         | 0.52%   |
| 975     | 2         | 0.52%   |
| 5600    | 1         | 0.26%   |
| 5200    | 1         | 0.26%   |
| 3733    | 1         | 0.26%   |
| 3000    | 1         | 0.26%   |
| 2933    | 1         | 0.26%   |
| 2733    | 1         | 0.26%   |
| 2267    | 1         | 0.26%   |
| 1639    | 1         | 0.26%   |
| 400     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 33.33%  |
| STMicroelectronics  | 2         | 22.22%  |
| Brother Industries  | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| Hewlett-Packard     | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 22.22%  |
| Samsung M2070 Series                                      | 1         | 11.11%  |
| HP Officejet 4500 G510g-m                                 | 1         | 11.11%  |
| Canon TS5300 series                                       | 1         | 11.11%  |
| Canon PIXMA MG3600 Series                                 | 1         | 11.11%  |
| Canon PIXMA MG2500 Series                                 | 1         | 11.11%  |
| Brother MFC-L2700DW                                       | 1         | 11.11%  |
| Brother HL-L2340D series                                  | 1         | 11.11%  |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 102       | 23.78%  |
| Realtek Semiconductor                  | 43        | 10.02%  |
| Microdia                               | 41        | 9.56%   |
| IMC Networks                           | 37        | 8.62%   |
| Logitech                               | 29        | 6.76%   |
| Sunplus Innovation Technology          | 26        | 6.06%   |
| Bison Electronics                      | 25        | 5.83%   |
| Quanta                                 | 20        | 4.66%   |
| Apple                                  | 18        | 4.2%    |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.56%   |
| Samsung Electronics                    | 7         | 1.63%   |
| Acer                                   | 7         | 1.63%   |
| Suyin                                  | 6         | 1.4%    |
| Microsoft                              | 6         | 1.4%    |
| Ricoh                                  | 5         | 1.17%   |
| Lite-On Technology                     | 5         | 1.17%   |
| ALi                                    | 5         | 1.17%   |
| Syntek                                 | 4         | 0.93%   |
| Silicon Motion                         | 4         | 0.93%   |
| SunplusIT                              | 3         | 0.7%    |
| Sonix Technology                       | 2         | 0.47%   |
| Lenovo                                 | 2         | 0.47%   |
| Generalplus Technology                 | 2         | 0.47%   |
| Creative Technology                    | 2         | 0.47%   |
| Alcor Micro                            | 2         | 0.47%   |
| Z-Star Microelectronics                | 1         | 0.23%   |
| Y Media                                | 1         | 0.23%   |
| WaveRider Communications               | 1         | 0.23%   |
| USB3.0 HD Audio Capture                | 1         | 0.23%   |
| Trust                                  | 1         | 0.23%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.23%   |
| Razer USA                              | 1         | 0.23%   |
| Nokia Mobile Phones                    | 1         | 0.23%   |
| Nikon                                  | 1         | 0.23%   |
| MacroSilicon                           | 1         | 0.23%   |
| Luxvisions Innotech Limited            | 1         | 0.23%   |
| GenesysLogic Technology                | 1         | 0.23%   |
| GEMBIRD                                | 1         | 0.23%   |
| DigiTech                               | 1         | 0.23%   |
| ARC International                      | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 25        | 5.77%   |
| Microdia Integrated_Webcam_HD           | 18        | 4.16%   |
| Realtek Integrated_Webcam_HD            | 17        | 3.93%   |
| IMC Networks Integrated Camera          | 13        | 3%      |
| Logitech HD Pro Webcam C920             | 12        | 2.77%   |
| Bison Integrated Camera                 | 10        | 2.31%   |
| Apple Built-in iSight                   | 10        | 2.31%   |
| Sunplus Integrated_Webcam_HD            | 8         | 1.85%   |
| Sunplus Integrated_Webcam_FHD           | 8         | 1.85%   |
| Chicony USB2.0 Camera                   | 8         | 1.85%   |
| Chicony HD WebCam                       | 8         | 1.85%   |
| Samsung Galaxy series, misc. (MTP mode) | 7         | 1.62%   |
| IMC Networks USB2.0 HD UVC WebCam       | 7         | 1.62%   |
| Microdia Integrated Webcam              | 6         | 1.39%   |
| Microsoft LifeCam HD-3000               | 5         | 1.15%   |
| Chicony HP Wide Vision HD Camera        | 5         | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE               | 5         | 1.15%   |
| Realtek Integrated Webcam HD            | 4         | 0.92%   |
| Microdia Webcam Vitade AF               | 4         | 0.92%   |
| Logitech Webcam C270                    | 4         | 0.92%   |
| Lite-On HP HD Camera                    | 4         | 0.92%   |
| Chicony USB2.0 HD UVC WebCam            | 4         | 0.92%   |
| Bison EasyCamera                        | 4         | 0.92%   |
| Apple FaceTime HD Camera (Built-in)     | 4         | 0.92%   |
| Realtek USB2.0 HD UVC WebCam            | 3         | 0.69%   |
| Realtek USB camera                      | 3         | 0.69%   |
| Realtek EasyCamera                      | 3         | 0.69%   |
| Quanta HD User Facing                   | 3         | 0.69%   |
| Quanta ACER HD User Facing              | 3         | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 3         | 0.69%   |
| Chicony thinkpad t430s camera           | 3         | 0.69%   |
| Chicony Lenovo EasyCamera               | 3         | 0.69%   |
| Chicony Integrated Camera (1280x720@30) | 3         | 0.69%   |
| Chicony HP HD Camera                    | 3         | 0.69%   |
| Chicony EasyCamera                      | 3         | 0.69%   |
| ALi WebCam                              | 3         | 0.69%   |
| Syntek Integrated Camera                | 2         | 0.46%   |
| Syntek EasyCamera                       | 2         | 0.46%   |
| Suyin HP Truevision HD                  | 2         | 0.46%   |
| SunplusIT 720p HD Camera                | 2         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 28        | 33.33%  |
| Validity Sensors           | 22        | 26.19%  |
| Shenzhen Goodix Technology | 18        | 21.43%  |
| Upek                       | 4         | 4.76%   |
| Elan Microelectronics      | 4         | 4.76%   |
| AuthenTec                  | 4         | 4.76%   |
| LighTuning Technology      | 2         | 2.38%   |
| STMicroelectronics         | 1         | 1.19%   |
| Focal-systems.Corp         | 1         | 1.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                       | 8         | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader               | 6         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 6         | 7.14%   |
| Shenzhen Goodix FingerPrint                              | 6         | 7.14%   |
| Unknown                                                  | 5         | 5.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 4         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 4         | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                      | 4         | 4.76%   |
| Synaptics  WBDI                                          | 3         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                     | 3         | 3.57%   |
| AuthenTec Fingerprint Sensor                             | 3         | 3.57%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 2.38%   |
| Validity Sensors VFS471 Fingerprint Reader               | 2         | 2.38%   |
| Validity Sensors VFS451 Fingerprint Reader               | 2         | 2.38%   |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 2.38%   |
| Validity Sensors Synaptics WBDI                          | 2         | 2.38%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 2         | 2.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 2.38%   |
| Elan ELAN:Fingerprint                                    | 2         | 2.38%   |
| Elan ELAN:ARM-M4                                         | 2         | 2.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 1.19%   |
| Validity Sensors VFS300 Fingerprint Reader               | 1         | 1.19%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.19%   |
| Validity Sensors Fingerprint scanner                     | 1         | 1.19%   |
| Synaptics WBDI                                           | 1         | 1.19%   |
| Synaptics UWP WBDI Device                                | 1         | 1.19%   |
| Synaptics UWP WBDI                                       | 1         | 1.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.19%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 1.19%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 1.19%   |
| AuthenTec AES2810                                        | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 33        | 61.11%  |
| Alcor Micro                       | 8         | 14.81%  |
| Upek                              | 5         | 9.26%   |
| O2 Micro                          | 5         | 9.26%   |
| Lenovo                            | 2         | 3.7%    |
| Free Software Initiative of Japan | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 15        | 27.78%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 14.81%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 14.81%  |
| Broadcom 5880                                                                | 6         | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 9.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 7.41%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.85%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 428       | 63.41%  |
| 1     | 190       | 28.15%  |
| 2     | 48        | 7.11%   |
| 3     | 7         | 1.04%   |
| 5     | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 83        | 27.95%  |
| Net/wireless             | 62        | 20.88%  |
| Graphics card            | 57        | 19.19%  |
| Chipcard                 | 47        | 15.82%  |
| Multimedia controller    | 13        | 4.38%   |
| Camera                   | 9         | 3.03%   |
| Communication controller | 8         | 2.69%   |
| Storage                  | 5         | 1.68%   |
| Card reader              | 3         | 1.01%   |
| Bluetooth                | 3         | 1.01%   |
| Net/ethernet             | 2         | 0.67%   |
| Unassigned class         | 1         | 0.34%   |
| Storage/ata              | 1         | 0.34%   |
| Sound                    | 1         | 0.34%   |
| Modem                    | 1         | 0.34%   |
| Firewire controller      | 1         | 0.34%   |

