Ubuntu Studio - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Studio/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Studio/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | TP300UA                     | Notebook    | [22ff7f5827](https://linux-hardware.org/?probe=22ff7f5827) | Feb 20, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| Dell          | Latitude 5511               | Notebook    | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c63c663181](https://linux-hardware.org/?probe=c63c663181) | Jan 30, 2023 |
| HP            | 304Ah                       | Desktop     | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| HP            | 1497                        | Desktop     | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [db3b391bd0](https://linux-hardware.org/?probe=db3b391bd0) | Jan 20, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [3140672f28](https://linux-hardware.org/?probe=3140672f28) | Jan 10, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [f36c085389](https://linux-hardware.org/?probe=f36c085389) | Dec 25, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [9d689be2ab](https://linux-hardware.org/?probe=9d689be2ab) | Dec 11, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| Dell          | Latitude E6500              | Notebook    | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [a888eb38b3](https://linux-hardware.org/?probe=a888eb38b3) | Dec 01, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [78defd6c12](https://linux-hardware.org/?probe=78defd6c12) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [b76898d624](https://linux-hardware.org/?probe=b76898d624) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [5147db88ea](https://linux-hardware.org/?probe=5147db88ea) | Nov 14, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1d490bb7d1](https://linux-hardware.org/?probe=1d490bb7d1) | Nov 11, 2022 |
| HP            | 09F8h                       | Desktop     | [f1107e91f2](https://linux-hardware.org/?probe=f1107e91f2) | Nov 01, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | Desktop     | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [55771f0c33](https://linux-hardware.org/?probe=55771f0c33) | Oct 18, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [7e0028c2fa](https://linux-hardware.org/?probe=7e0028c2fa) | Oct 18, 2022 |
| Gigabyte      | X79S-UP5                    | Desktop     | [62f59af32c](https://linux-hardware.org/?probe=62f59af32c) | Oct 15, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5bfc8f0a7d](https://linux-hardware.org/?probe=5bfc8f0a7d) | Sep 30, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2dc3febd4d](https://linux-hardware.org/?probe=2dc3febd4d) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [5b39dcf114](https://linux-hardware.org/?probe=5b39dcf114) | Sep 19, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [b1d97f239e](https://linux-hardware.org/?probe=b1d97f239e) | Sep 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [de37b9cf96](https://linux-hardware.org/?probe=de37b9cf96) | Sep 13, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [d6d8f577e0](https://linux-hardware.org/?probe=d6d8f577e0) | Sep 12, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [07428c96e1](https://linux-hardware.org/?probe=07428c96e1) | Sep 11, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a23b4a8cd4](https://linux-hardware.org/?probe=a23b4a8cd4) | Aug 27, 2022 |
| HP            | 18E7                        | Desktop     | [698520133f](https://linux-hardware.org/?probe=698520133f) | Aug 22, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [45491460bc](https://linux-hardware.org/?probe=45491460bc) | Aug 12, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| HP            | G62                         | Notebook    | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| AZW           | SER V01                     | Mini pc     | [0bf81855b6](https://linux-hardware.org/?probe=0bf81855b6) | Jul 18, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e45e0b0c90](https://linux-hardware.org/?probe=e45e0b0c90) | Jun 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [4ed102b3fa](https://linux-hardware.org/?probe=4ed102b3fa) | Jun 15, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [6023bfb4cc](https://linux-hardware.org/?probe=6023bfb4cc) | Jun 09, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [a4aa661ab1](https://linux-hardware.org/?probe=a4aa661ab1) | Jun 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bcd22d5d0e](https://linux-hardware.org/?probe=bcd22d5d0e) | May 20, 2022 |
| Getac         | S400G3                      | Notebook    | [56cc8b4c1a](https://linux-hardware.org/?probe=56cc8b4c1a) | May 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [fc3e449b4d](https://linux-hardware.org/?probe=fc3e449b4d) | May 09, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b2bddaf1b1](https://linux-hardware.org/?probe=b2bddaf1b1) | Apr 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [02b0c35fed](https://linux-hardware.org/?probe=02b0c35fed) | Apr 27, 2022 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [cebf5b3135](https://linux-hardware.org/?probe=cebf5b3135) | Apr 17, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [aff1557d72](https://linux-hardware.org/?probe=aff1557d72) | Apr 11, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [a87f9de14e](https://linux-hardware.org/?probe=a87f9de14e) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [01ad19348a](https://linux-hardware.org/?probe=01ad19348a) | Mar 20, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [3f8fe40793](https://linux-hardware.org/?probe=3f8fe40793) | Mar 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [4206238fce](https://linux-hardware.org/?probe=4206238fce) | Mar 01, 2022 |
| HP            | Sona                        | Notebook    | [4fcab0b3b7](https://linux-hardware.org/?probe=4fcab0b3b7) | Feb 24, 2022 |
| HP            | Sona                        | Notebook    | [d0b3189e0f](https://linux-hardware.org/?probe=d0b3189e0f) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [82f706b315](https://linux-hardware.org/?probe=82f706b315) | Feb 11, 2022 |
| Google        | Nami                        | Notebook    | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [fe9fed2a45](https://linux-hardware.org/?probe=fe9fed2a45) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [5ccce1fb71](https://linux-hardware.org/?probe=5ccce1fb71) | Jan 21, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [91adda5a0e](https://linux-hardware.org/?probe=91adda5a0e) | Jan 21, 2022 |
| Clevo         | W35_37ET                    | Notebook    | [f8858fd0c3](https://linux-hardware.org/?probe=f8858fd0c3) | Jan 20, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [b479441fe2](https://linux-hardware.org/?probe=b479441fe2) | Jan 15, 2022 |
| HP            | 3396                        | Desktop     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [7f94c66f93](https://linux-hardware.org/?probe=7f94c66f93) | Jan 09, 2022 |
| AZW           | GK35                        | Desktop     | [ed1be3dbf7](https://linux-hardware.org/?probe=ed1be3dbf7) | Jan 07, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [e071d4f83a](https://linux-hardware.org/?probe=e071d4f83a) | Jan 02, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| Toshiba       | Satellite C855              | Notebook    | [7914ab9929](https://linux-hardware.org/?probe=7914ab9929) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [22033e7185](https://linux-hardware.org/?probe=22033e7185) | Oct 05, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [91b4275b9b](https://linux-hardware.org/?probe=91b4275b9b) | Aug 25, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| HP            | Pavilion dv6                | Notebook    | [089a39fe70](https://linux-hardware.org/?probe=089a39fe70) | Jul 07, 2021 |
| Acer          | Aspire U5-710               | All in one  | [c2ff1a33ee](https://linux-hardware.org/?probe=c2ff1a33ee) | Jun 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| HP            | 1495                        | Desktop     | [56251d62e1](https://linux-hardware.org/?probe=56251d62e1) | Jun 17, 2021 |
| Intel Clie... | LAPBC510                    | Notebook    | [06421d0916](https://linux-hardware.org/?probe=06421d0916) | Jun 15, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [f88f0c3680](https://linux-hardware.org/?probe=f88f0c3680) | Jun 14, 2021 |
| Pegatron      | NARRA3                      | Desktop     | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [80ca4b15a5](https://linux-hardware.org/?probe=80ca4b15a5) | May 16, 2021 |
| HP            | 158A                        | Desktop     | [2fac0fa486](https://linux-hardware.org/?probe=2fac0fa486) | May 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ef264215af](https://linux-hardware.org/?probe=ef264215af) | Apr 24, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [749002b5ad](https://linux-hardware.org/?probe=749002b5ad) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [aec24cb317](https://linux-hardware.org/?probe=aec24cb317) | Apr 20, 2021 |
| Dell          | Precision M4500             | Notebook    | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [5e98e0ae38](https://linux-hardware.org/?probe=5e98e0ae38) | Apr 14, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [43cb3af3a5](https://linux-hardware.org/?probe=43cb3af3a5) | Apr 12, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [9414f40cf2](https://linux-hardware.org/?probe=9414f40cf2) | Apr 03, 2021 |
| Fujitsu       | D3654-C1 S26361-D3654-C1    | Desktop     | [4cd56bcfa1](https://linux-hardware.org/?probe=4cd56bcfa1) | Apr 02, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [5ff7a11404](https://linux-hardware.org/?probe=5ff7a11404) | Mar 28, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [7b7a266de6](https://linux-hardware.org/?probe=7b7a266de6) | Mar 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [d9f29b65da](https://linux-hardware.org/?probe=d9f29b65da) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [369f0a0cdb](https://linux-hardware.org/?probe=369f0a0cdb) | Mar 12, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e4fb438978](https://linux-hardware.org/?probe=e4fb438978) | Feb 24, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [19bc1494c6](https://linux-hardware.org/?probe=19bc1494c6) | Feb 21, 2021 |
| Sony          | VGN-NS31M_W                 | Notebook    | [dcc1660569](https://linux-hardware.org/?probe=dcc1660569) | Feb 17, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [387cfadf45](https://linux-hardware.org/?probe=387cfadf45) | Feb 06, 2021 |
| IBM           | 8188PPV                     | Desktop     | [6d4f098a65](https://linux-hardware.org/?probe=6d4f098a65) | Jan 31, 2021 |
| Dell          | 02YRK5 A01                  | Desktop     | [6a2d5cd538](https://linux-hardware.org/?probe=6a2d5cd538) | Jan 30, 2021 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [c9af16a580](https://linux-hardware.org/?probe=c9af16a580) | Jan 24, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [e74dbb590d](https://linux-hardware.org/?probe=e74dbb590d) | Jan 21, 2021 |
| Intel         | DQ965GF AAD41676-402        | Desktop     | [2e9a342427](https://linux-hardware.org/?probe=2e9a342427) | Jan 13, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [13edd89415](https://linux-hardware.org/?probe=13edd89415) | Jan 11, 2021 |
| ASUSTek       | U56E                        | Notebook    | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [a8ebb648f7](https://linux-hardware.org/?probe=a8ebb648f7) | Jan 03, 2021 |
| Acer          | Aspire X3400                | Desktop     | [da9e0d0bb4](https://linux-hardware.org/?probe=da9e0d0bb4) | Jan 02, 2021 |
| Packard Be... | WMCP78M                     | Desktop     | [6a6c4577d4](https://linux-hardware.org/?probe=6a6c4577d4) | Dec 31, 2020 |
| HP            | 1850                        | Desktop     | [b86e749745](https://linux-hardware.org/?probe=b86e749745) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4332bc902d](https://linux-hardware.org/?probe=4332bc902d) | Dec 21, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [b2e5d9d8b0](https://linux-hardware.org/?probe=b2e5d9d8b0) | Dec 09, 2020 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [2291f0c106](https://linux-hardware.org/?probe=2291f0c106) | Dec 08, 2020 |
| Dell          | 04YP6J A02                  | Desktop     | [6c15ba650c](https://linux-hardware.org/?probe=6c15ba650c) | Dec 06, 2020 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [505443aeb1](https://linux-hardware.org/?probe=505443aeb1) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [73e35c07b8](https://linux-hardware.org/?probe=73e35c07b8) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [3b24badd98](https://linux-hardware.org/?probe=3b24badd98) | Dec 02, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | Latitude E6530              | Notebook    | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| ASUSTek       | CS-B                        | Desktop     | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| Dell          | Latitude E7250              | Notebook    | [d5e2f8b706](https://linux-hardware.org/?probe=d5e2f8b706) | Nov 01, 2020 |
| Acer          | ASPIRE1420P_MSFT            | Notebook    | [5185b46abc](https://linux-hardware.org/?probe=5185b46abc) | Oct 31, 2020 |
| HP            | 3047h                       | Desktop     | [a23efe0e20](https://linux-hardware.org/?probe=a23efe0e20) | Oct 26, 2020 |
| ASRock        | H55M/USB3                   | Desktop     | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| Dell          | 0F8098                      | Desktop     | [a2217fa6a7](https://linux-hardware.org/?probe=a2217fa6a7) | Sep 25, 2020 |
| Dell          | 0F8098                      | Desktop     | [2c747bcc47](https://linux-hardware.org/?probe=2c747bcc47) | Sep 25, 2020 |
| Avell High... | Avell G1555 MUV / A62 MU... | Notebook    | [c2994bb093](https://linux-hardware.org/?probe=c2994bb093) | Sep 18, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [e00620b124](https://linux-hardware.org/?probe=e00620b124) | Sep 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [57d3d832f5](https://linux-hardware.org/?probe=57d3d832f5) | Sep 04, 2020 |
| Dell          | Latitude E4300              | Notebook    | [3e0fb2e03f](https://linux-hardware.org/?probe=3e0fb2e03f) | Sep 03, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [03bcf3b1fd](https://linux-hardware.org/?probe=03bcf3b1fd) | Sep 02, 2020 |
| HP            | Compaq 8510p                | Notebook    | [2ea87d13f0](https://linux-hardware.org/?probe=2ea87d13f0) | Aug 26, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [d4f13322ac](https://linux-hardware.org/?probe=d4f13322ac) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [d2851c54e9](https://linux-hardware.org/?probe=d2851c54e9) | Aug 18, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [92e2a05f2d](https://linux-hardware.org/?probe=92e2a05f2d) | Aug 13, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [0ae5a1aab2](https://linux-hardware.org/?probe=0ae5a1aab2) | Aug 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [96ba8dc0e8](https://linux-hardware.org/?probe=96ba8dc0e8) | Jul 31, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [3162979c2e](https://linux-hardware.org/?probe=3162979c2e) | Jul 24, 2020 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [d21c458a4f](https://linux-hardware.org/?probe=d21c458a4f) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [957ec007de](https://linux-hardware.org/?probe=957ec007de) | Jun 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cb240b6e7e](https://linux-hardware.org/?probe=cb240b6e7e) | Jun 05, 2020 |
| HP            | Notebook                    | Notebook    | [e406d5cf9e](https://linux-hardware.org/?probe=e406d5cf9e) | Jun 02, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [8271aeba33](https://linux-hardware.org/?probe=8271aeba33) | Mar 19, 2020 |
| Lenovo        | ThinkPad W530 2447IG0       | Notebook    | [f7125d9a17](https://linux-hardware.org/?probe=f7125d9a17) | Mar 19, 2020 |
| Lenovo        | ThinkPad X230 23245S1       | Notebook    | [047f29b7c7](https://linux-hardware.org/?probe=047f29b7c7) | Nov 01, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ebbf8cd8d4](https://linux-hardware.org/?probe=ebbf8cd8d4) | May 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 80        | 53.33%  |
| Ubuntu Studio 22.04 | 33        | 22%     |
| Ubuntu Studio 20.10 | 13        | 8.67%   |
| Ubuntu Studio 21.10 | 7         | 4.67%   |
| Ubuntu Studio 22.10 | 6         | 4%      |
| Ubuntu Studio 21.04 | 5         | 3.33%   |
| Ubuntu Studio 18.04 | 3         | 2%      |
| Ubuntu Studio 19.10 | 2         | 1.33%   |
| Ubuntu Studio 16.04 | 1         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 149       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.15.0-56-lowlatency    | 5         | 3.29%   |
| 5.15.0-46-lowlatency    | 5         | 3.29%   |
| 5.13.0-28-lowlatency    | 5         | 3.29%   |
| 5.4.0-52-lowlatency     | 4         | 2.63%   |
| 5.4.0-42-lowlatency     | 4         | 2.63%   |
| 5.8.0-55-lowlatency     | 3         | 1.97%   |
| 5.8.0-50-lowlatency     | 3         | 1.97%   |
| 5.8.0-44-lowlatency     | 3         | 1.97%   |
| 5.8.0-25-lowlatency     | 3         | 1.97%   |
| 5.4.0-65-lowlatency     | 3         | 1.97%   |
| 5.4.0-26-lowlatency     | 3         | 1.97%   |
| 5.15.0-58-lowlatency    | 3         | 1.97%   |
| 5.15.0-52-lowlatency    | 3         | 1.97%   |
| 5.15.0-50-lowlatency    | 3         | 1.97%   |
| 5.15.0-48-lowlatency    | 3         | 1.97%   |
| 5.15.0-47-lowlatency    | 3         | 1.97%   |
| 5.11.0-44-lowlatency    | 3         | 1.97%   |
| 5.11.0-34-lowlatency    | 3         | 1.97%   |
| 5.8.0-48-lowlatency     | 2         | 1.32%   |
| 5.8.0-29-lowlatency     | 2         | 1.32%   |
| 5.4.0-94-lowlatency     | 2         | 1.32%   |
| 5.4.0-58-lowlatency     | 2         | 1.32%   |
| 5.4.0-56-lowlatency     | 2         | 1.32%   |
| 5.4.0-45-lowlatency     | 2         | 1.32%   |
| 5.19.0-1015-lowlatency  | 2         | 1.32%   |
| 5.15.0-53-lowlatency    | 2         | 1.32%   |
| 5.15.0-40-lowlatency    | 2         | 1.32%   |
| 5.15.0-30-lowlatency    | 2         | 1.32%   |
| 5.13.0-30-lowlatency    | 2         | 1.32%   |
| 5.11.0-27-lowlatency    | 2         | 1.32%   |
| 5.8.0-59-lowlatency     | 1         | 0.66%   |
| 5.8.0-45-lowlatency     | 1         | 0.66%   |
| 5.8.0-43-lowlatency     | 1         | 0.66%   |
| 5.8.0-36-lowlatency     | 1         | 0.66%   |
| 5.8.0-34-lowlatency     | 1         | 0.66%   |
| 5.8.0-34-generic        | 1         | 0.66%   |
| 5.8.0-33-lowlatency     | 1         | 0.66%   |
| 5.7.6-050706-lowlatency | 1         | 0.66%   |
| 5.7.6-050706-generic    | 1         | 0.66%   |
| 5.4.0-99-lowlatency     | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 34%     |
| 5.15.0  | 36        | 24%     |
| 5.8.0   | 23        | 15.33%  |
| 5.11.0  | 15        | 10%     |
| 5.13.0  | 10        | 6.67%   |
| 5.19.0  | 6         | 4%      |
| 4.15.0  | 3         | 2%      |
| 5.3.0   | 2         | 1.33%   |
| 5.7.6   | 1         | 0.67%   |
| 5.17.1  | 1         | 0.67%   |
| 5.15.6  | 1         | 0.67%   |
| 4.4.0   | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 51        | 34%     |
| 5.15    | 37        | 24.67%  |
| 5.8     | 23        | 15.33%  |
| 5.11    | 15        | 10%     |
| 5.13    | 10        | 6.67%   |
| 5.19    | 6         | 4%      |
| 4.15    | 3         | 2%      |
| 5.3     | 2         | 1.33%   |
| 5.7     | 1         | 0.67%   |
| 5.17    | 1         | 0.67%   |
| 4.4     | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 147       | 98.66%  |
| i686    | 1         | 0.67%   |
| aarch64 | 1         | 0.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 77        | 51.68%  |
| KDE5            | 55        | 36.91%  |
| GNOME           | 10        | 6.71%   |
| MATE            | 2         | 1.34%   |
| LXQt            | 2         | 1.34%   |
| KDE             | 1         | 0.67%   |
| GNOME Flashback | 1         | 0.67%   |
| Cinnamon        | 1         | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 142       | 95.3%   |
| Wayland | 5         | 3.36%   |
| Tty     | 2         | 1.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 51        | 34.23%  |
| TDM     | 49        | 32.89%  |
| LightDM | 36        | 24.16%  |
| GDM     | 11        | 7.38%   |
| LXDM    | 1         | 0.67%   |
| GDM3    | 1         | 0.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 60        | 40%     |
| fr_FR      | 20        | 13.33%  |
| de_DE      | 10        | 6.67%   |
| pt_BR      | 6         | 4%      |
| it_IT      | 6         | 4%      |
| en_GB      | 6         | 4%      |
| C          | 6         | 4%      |
| en_CA      | 4         | 2.67%   |
| ru_RU      | 3         | 2%      |
| nl_NL      | 2         | 1.33%   |
| es_ES      | 2         | 1.33%   |
| en_AU      | 2         | 1.33%   |
| en_AG      | 2         | 1.33%   |
| Unknown    | 2         | 1.33%   |
| sv_SE      | 1         | 0.67%   |
| sk_SK      | 1         | 0.67%   |
| nl_BE      | 1         | 0.67%   |
| nb_NO      | 1         | 0.67%   |
| hu_HU      | 1         | 0.67%   |
| fr_FR.UTF8 | 1         | 0.67%   |
| fr_CH      | 1         | 0.67%   |
| fr_BE      | 1         | 0.67%   |
| es_NI      | 1         | 0.67%   |
| es_GT      | 1         | 0.67%   |
| es_CR      | 1         | 0.67%   |
| es_AR      | 1         | 0.67%   |
| en_NG      | 1         | 0.67%   |
| en_IE      | 1         | 0.67%   |
| en_DE      | 1         | 0.67%   |
| de_CH      | 1         | 0.67%   |
| de_AT      | 1         | 0.67%   |
| ca_ES      | 1         | 0.67%   |
| ca_AD      | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 83        | 55.7%   |
| BIOS | 66        | 44.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 143       | 95.97%  |
| Overlay | 4         | 2.68%   |
| Xfs     | 1         | 0.67%   |
| Ext2    | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 92        | 61.74%  |
| MBR  | 57        | 38.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 121       | 80.67%  |
| Yes       | 29        | 19.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 55.03%  |
| Yes       | 67        | 44.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 29        | 19.46%  |
| Dell                    | 24        | 16.11%  |
| Hewlett-Packard         | 21        | 14.09%  |
| Lenovo                  | 19        | 12.75%  |
| Gigabyte Technology     | 12        | 8.05%   |
| Acer                    | 6         | 4.03%   |
| Apple                   | 5         | 3.36%   |
| Intel                   | 3         | 2.01%   |
| Fujitsu                 | 3         | 2.01%   |
| ASRock                  | 3         | 2.01%   |
| Toshiba                 | 2         | 1.34%   |
| MSI                     | 2         | 1.34%   |
| HUAWEI                  | 2         | 1.34%   |
| AZW                     | 2         | 1.34%   |
| System76                | 1         | 0.67%   |
| Sony                    | 1         | 0.67%   |
| Samsung Electronics     | 1         | 0.67%   |
| Razer                   | 1         | 0.67%   |
| Raspberry Pi Foundation | 1         | 0.67%   |
| Pegatron                | 1         | 0.67%   |
| Packard Bell            | 1         | 0.67%   |
| Medion                  | 1         | 0.67%   |
| Intel Client Systems    | 1         | 0.67%   |
| IBM                     | 1         | 0.67%   |
| Google                  | 1         | 0.67%   |
| Getac                   | 1         | 0.67%   |
| Foxconn                 | 1         | 0.67%   |
| Clevo                   | 1         | 0.67%   |
| Avell High Performance  | 1         | 0.67%   |
| Acidanthera             | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 2.68%   |
| Lenovo G50-45 80E3                         | 2         | 1.34%   |
| HP Pavilion dv6                            | 2         | 1.34%   |
| Dell OptiPlex 790                          | 2         | 1.34%   |
| ASUS PRIME X570-PRO                        | 2         | 1.34%   |
| Toshiba Satellite L755D                    | 1         | 0.67%   |
| Toshiba Satellite C855                     | 1         | 0.67%   |
| System76 Thelio                            | 1         | 0.67%   |
| Sony VGN-NS31M_W                           | 1         | 0.67%   |
| Samsung 305V4A/305V5A                      | 1         | 0.67%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.67%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.67%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.67%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.67%   |
| MSI MS-7A57                                | 1         | 0.67%   |
| MSI MS-7752                                | 1         | 0.67%   |
| Medion MD34207/C746                        | 1         | 0.67%   |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.67%   |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.67%   |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.67%   |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.67%   |
| Lenovo ThinkPad T530 24296HG               | 1         | 0.67%   |
| Lenovo ThinkPad T520 4243K86               | 1         | 0.67%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1         | 0.67%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.67%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4       | 1         | 0.67%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 1         | 0.67%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 1         | 0.67%   |
| Lenovo IdeaPad 3 15ABA7 82RN               | 1         | 0.67%   |
| Lenovo IdeaPad 3 14ARE05 81W3              | 1         | 0.67%   |
| Lenovo IdeaCentre AIO 520-27ICB F0DE00EJRI | 1         | 0.67%   |
| Lenovo G70-80 80FF                         | 1         | 0.67%   |
| Intel NUC8i5BEH                            | 1         | 0.67%   |
| Intel NUC7i5DNKE                           | 1         | 0.67%   |
| Intel DQ965GF HD/FP Audio                  | 1         | 0.67%   |
| Intel Client Systems LAPBC510              | 1         | 0.67%   |
| IBM 8188PPV                                | 1         | 0.67%   |
| HUAWEI KLVL-WXXW                           | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 8         | 5.37%   |
| HP Compaq                     | 8         | 5.37%   |
| Dell OptiPlex                 | 8         | 5.37%   |
| Dell Inspiron                 | 8         | 5.37%   |
| Lenovo IdeaPad                | 5         | 3.36%   |
| Dell Latitude                 | 5         | 3.36%   |
| Acer Aspire                   | 5         | 3.36%   |
| ASUS ROG                      | 4         | 2.68%   |
| ASUS All                      | 4         | 2.68%   |
| Fujitsu ESPRIMO               | 3         | 2.01%   |
| Toshiba Satellite             | 2         | 1.34%   |
| Lenovo G50-45                 | 2         | 1.34%   |
| HP Pavilion                   | 2         | 1.34%   |
| HP EliteBook                  | 2         | 1.34%   |
| Dell Precision                | 2         | 1.34%   |
| ASUS TUF                      | 2         | 1.34%   |
| ASUS PRIME                    | 2         | 1.34%   |
| ASUS P8P67                    | 2         | 1.34%   |
| System76 Thelio               | 1         | 0.67%   |
| Sony VGN-NS31M                | 1         | 0.67%   |
| Samsung 305V4A                | 1         | 0.67%   |
| Razer Blade                   | 1         | 0.67%   |
| RPi Raspberry                 | 1         | 0.67%   |
| Pegatron FL368AA-UUZ          | 1         | 0.67%   |
| Packard Bell IMEDIA           | 1         | 0.67%   |
| MSI MS-7A57                   | 1         | 0.67%   |
| MSI MS-7752                   | 1         | 0.67%   |
| Medion MD34207                | 1         | 0.67%   |
| Lenovo ThinkCentre            | 1         | 0.67%   |
| Lenovo Legion                 | 1         | 0.67%   |
| Lenovo IdeaCentre             | 1         | 0.67%   |
| Lenovo G70-80                 | 1         | 0.67%   |
| Intel NUC8i5BEH               | 1         | 0.67%   |
| Intel NUC7i5DNKE              | 1         | 0.67%   |
| Intel DQ965GF                 | 1         | 0.67%   |
| Intel Client Systems LAPBC510 | 1         | 0.67%   |
| IBM 8188PPV                   | 1         | 0.67%   |
| HUAWEI KLVL-WXXW              | 1         | 0.67%   |
| HUAWEI HLYL-WXX9              | 1         | 0.67%   |
| HP ZBook                      | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 17        | 11.41%  |
| 2012 | 15        | 10.07%  |
| 2019 | 14        | 9.4%    |
| 2014 | 13        | 8.72%   |
| 2018 | 12        | 8.05%   |
| 2011 | 12        | 8.05%   |
| 2013 | 9         | 6.04%   |
| 2021 | 8         | 5.37%   |
| 2017 | 8         | 5.37%   |
| 2016 | 7         | 4.7%    |
| 2015 | 7         | 4.7%    |
| 2010 | 7         | 4.7%    |
| 2008 | 7         | 4.7%    |
| 2009 | 5         | 3.36%   |
| 2007 | 4         | 2.68%   |
| 2005 | 3         | 2.01%   |
| 2022 | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 71        | 47.65%  |
| Notebook       | 67        | 44.97%  |
| All in one     | 5         | 3.36%   |
| Mini pc        | 4         | 2.68%   |
| System on chip | 1         | 0.67%   |
| Convertible    | 1         | 0.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 140       | 93.96%  |
| Enabled  | 9         | 6.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 147       | 98.66%  |
| Yes  | 2         | 1.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 41        | 27.33%  |
| 16.01-24.0  | 34        | 22.67%  |
| 8.01-16.0   | 29        | 19.33%  |
| 3.01-4.0    | 15        | 10%     |
| 32.01-64.0  | 14        | 9.33%   |
| 64.01-256.0 | 7         | 4.67%   |
| 1.01-2.0    | 4         | 2.67%   |
| 24.01-32.0  | 3         | 2%      |
| 2.01-3.0    | 3         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 51        | 33.55%  |
| 2.01-3.0   | 36        | 23.68%  |
| 4.01-8.0   | 27        | 17.76%  |
| 3.01-4.0   | 22        | 14.47%  |
| 8.01-16.0  | 11        | 7.24%   |
| 0.51-1.0   | 4         | 2.63%   |
| 24.01-32.0 | 1         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 54.67%  |
| 2      | 48        | 32%     |
| 3      | 7         | 4.67%   |
| 4      | 4         | 2.67%   |
| 7      | 2         | 1.33%   |
| 5      | 2         | 1.33%   |
| 0      | 2         | 1.33%   |
| 16     | 1         | 0.67%   |
| 11     | 1         | 0.67%   |
| 10     | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 51.33%  |
| Yes       | 73        | 48.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 89.93%  |
| No        | 15        | 10.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 71.81%  |
| No        | 42        | 28.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 54.36%  |
| No        | 68        | 45.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 32        | 21.48%  |
| France                 | 22        | 14.77%  |
| Germany                | 16        | 10.74%  |
| Italy                  | 10        | 6.71%   |
| Brazil                 | 7         | 4.7%    |
| UK                     | 5         | 3.36%   |
| Spain                  | 5         | 3.36%   |
| Russia                 | 5         | 3.36%   |
| Canada                 | 5         | 3.36%   |
| Austria                | 4         | 2.68%   |
| Netherlands            | 3         | 2.01%   |
| Belgium                | 3         | 2.01%   |
| Australia              | 3         | 2.01%   |
| Taiwan                 | 2         | 1.34%   |
| Switzerland            | 2         | 1.34%   |
| Sweden                 | 2         | 1.34%   |
| Romania                | 2         | 1.34%   |
| Norway                 | 2         | 1.34%   |
| Mexico                 | 2         | 1.34%   |
| Costa Rica             | 2         | 1.34%   |
| Yemen                  | 1         | 0.67%   |
| Turkey                 | 1         | 0.67%   |
| Slovakia               | 1         | 0.67%   |
| Poland                 | 1         | 0.67%   |
| Nigeria                | 1         | 0.67%   |
| Nicaragua              | 1         | 0.67%   |
| Kenya                  | 1         | 0.67%   |
| Ivory Coast            | 1         | 0.67%   |
| Indonesia              | 1         | 0.67%   |
| Hungary                | 1         | 0.67%   |
| Guatemala              | 1         | 0.67%   |
| Finland                | 1         | 0.67%   |
| Bulgaria               | 1         | 0.67%   |
| Bosnia and Herzegovina | 1         | 0.67%   |
| Argentina              | 1         | 0.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Paris                   | 3         | 2%      |
| Vienna                  | 2         | 1.33%   |
| Turin                   | 2         | 1.33%   |
| Stuttgart               | 2         | 1.33%   |
| Montreal                | 2         | 1.33%   |
| Mississauga             | 2         | 1.33%   |
| Madrid                  | 2         | 1.33%   |
| Houston                 | 2         | 1.33%   |
| Groningen               | 2         | 1.33%   |
| Denver                  | 2         | 1.33%   |
| Bucharest               | 2         | 1.33%   |
| Béziers                | 2         | 1.33%   |
| Zanesville              | 1         | 0.67%   |
| Yekaterinburg           | 1         | 0.67%   |
| Wroclaw                 | 1         | 0.67%   |
| Woonsocket              | 1         | 0.67%   |
| Woodland Park           | 1         | 0.67%   |
| Villefontaine           | 1         | 0.67%   |
| Velleron                | 1         | 0.67%   |
| Tilburg                 | 1         | 0.67%   |
| Taylor                  | 1         | 0.67%   |
| Tarragona               | 1         | 0.67%   |
| Taipei                  | 1         | 0.67%   |
| Taichung                | 1         | 0.67%   |
| Sunderland              | 1         | 0.67%   |
| Stockholm               | 1         | 0.67%   |
| Stabekk                 | 1         | 0.67%   |
| St Petersburg           | 1         | 0.67%   |
| Sofia                   | 1         | 0.67%   |
| Sleman                  | 1         | 0.67%   |
| Sherman Oaks            | 1         | 0.67%   |
| Seropedica              | 1         | 0.67%   |
| Sarajevo                | 1         | 0.67%   |
| Sao Paulo               | 1         | 0.67%   |
| Santa Barbara d'Oeste   | 1         | 0.67%   |
| Sanaa                   | 1         | 0.67%   |
| San Secondo di Pinerolo | 1         | 0.67%   |
| San Juan                | 1         | 0.67%   |
| San Francisco           | 1         | 0.67%   |
| Samara                  | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 41        | 50     | 17.75%  |
| WDC                         | 35        | 42     | 15.15%  |
| Seagate                     | 27        | 47     | 11.69%  |
| Toshiba                     | 15        | 16     | 6.49%   |
| SanDisk                     | 15        | 16     | 6.49%   |
| Kingston                    | 8         | 8      | 3.46%   |
| Intel                       | 8         | 11     | 3.46%   |
| Hitachi                     | 8         | 8      | 3.46%   |
| Crucial                     | 8         | 8      | 3.46%   |
| Unknown                     | 7         | 7      | 3.03%   |
| HGST                        | 5         | 6      | 2.16%   |
| SK hynix                    | 4         | 5      | 1.73%   |
| Phison                      | 3         | 3      | 1.3%    |
| Micron Technology           | 3         | 3      | 1.3%    |
| Intenso                     | 3         | 3      | 1.3%    |
| ASMT                        | 3         | 3      | 1.3%    |
| Team                        | 2         | 2      | 0.87%   |
| SPCC                        | 2         | 2      | 0.87%   |
| JMicron Technology          | 2         | 2      | 0.87%   |
| Fujitsu                     | 2         | 2      | 0.87%   |
| Corsair                     | 2         | 3      | 0.87%   |
| China                       | 2         | 2      | 0.87%   |
| BHT                         | 2         | 2      | 0.87%   |
| A-DATA Technology           | 2         | 2      | 0.87%   |
| USB 3.0                     | 1         | 2      | 0.43%   |
| Union Memory                | 1         | 1      | 0.43%   |
| UMIS                        | 1         | 1      | 0.43%   |
| TO Exter                    | 1         | 1      | 0.43%   |
| Reeinno                     | 1         | 1      | 0.43%   |
| Realtek Semiconductor       | 1         | 1      | 0.43%   |
| Realtek                     | 1         | 1      | 0.43%   |
| PNY                         | 1         | 1      | 0.43%   |
| Phison Electronics          | 1         | 1      | 0.43%   |
| Patriot                     | 1         | 1      | 0.43%   |
| OCZ                         | 1         | 1      | 0.43%   |
| NGFF                        | 1         | 1      | 0.43%   |
| Maxtor                      | 1         | 1      | 0.43%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.43%   |
| Leven                       | 1         | 1      | 0.43%   |
| KIOXIA                      | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 1.56%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.56%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 1.56%   |
| Seagate ST2000DM001-1ER164 2TB            | 3         | 1.17%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 1.17%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 1.17%   |
| Crucial CT500MX500SSD1 500GB              | 3         | 1.17%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.78%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.78%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.78%   |
| Toshiba HDWD130 3TB                       | 2         | 0.78%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.78%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB            | 2         | 0.78%   |
| Seagate Expansion 1TB                     | 2         | 0.78%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.78%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.78%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.78%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.78%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.78%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.78%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.78%   |
| Samsung HD753LJ 752GB                     | 2         | 0.78%   |
| JMicron Generic 200GB                     | 2         | 0.78%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 0.78%   |
| WDC WDS512G1X0C-00ENX0 512GB              | 1         | 0.39%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 1         | 0.39%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.39%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1         | 0.39%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.39%   |
| WDC WD5000BPKT-60PK4T0 500GB              | 1         | 0.39%   |
| WDC WD5000AAKS-75V0A0 500GB               | 1         | 0.39%   |
| WDC WD40EZRZ-00GXCB0 4TB                  | 1         | 0.39%   |
| WDC WD40EFRX-68N32N0 4TB                  | 1         | 0.39%   |
| WDC WD40EFAX-68JH4N1 4TB                  | 1         | 0.39%   |
| WDC WD40EFAX-68JH4N0 4TB                  | 1         | 0.39%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 0.39%   |
| WDC WD3200BPVT-75JJ5T0 320GB              | 1         | 0.39%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 35     | 29.79%  |
| Seagate             | 26        | 45     | 27.66%  |
| Toshiba             | 14        | 15     | 14.89%  |
| Hitachi             | 8         | 8      | 8.51%   |
| Samsung Electronics | 5         | 5      | 5.32%   |
| HGST                | 5         | 6      | 5.32%   |
| JMicron Technology  | 2         | 2      | 2.13%   |
| Fujitsu             | 2         | 2      | 2.13%   |
| USB 3.0             | 1         | 2      | 1.06%   |
| Unknown             | 1         | 1      | 1.06%   |
| Maxtor              | 1         | 1      | 1.06%   |
| ASMT                | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 28     | 29.76%  |
| SanDisk             | 13        | 14     | 15.48%  |
| Crucial             | 8         | 8      | 9.52%   |
| Kingston            | 7         | 7      | 8.33%   |
| Intenso             | 3         | 3      | 3.57%   |
| WDC                 | 2         | 2      | 2.38%   |
| SPCC                | 2         | 2      | 2.38%   |
| Micron Technology   | 2         | 2      | 2.38%   |
| China               | 2         | 2      | 2.38%   |
| BHT                 | 2         | 2      | 2.38%   |
| ASMT                | 2         | 2      | 2.38%   |
| A-DATA Technology   | 2         | 2      | 2.38%   |
| Toshiba             | 1         | 1      | 1.19%   |
| TO Exter            | 1         | 1      | 1.19%   |
| Team                | 1         | 1      | 1.19%   |
| Reeinno             | 1         | 1      | 1.19%   |
| PNY                 | 1         | 1      | 1.19%   |
| Patriot             | 1         | 1      | 1.19%   |
| OCZ                 | 1         | 1      | 1.19%   |
| NGFF                | 1         | 1      | 1.19%   |
| Leven               | 1         | 1      | 1.19%   |
| KingSpec            | 1         | 1      | 1.19%   |
| Intel               | 1         | 1      | 1.19%   |
| Integral            | 1         | 1      | 1.19%   |
| Inateck             | 1         | 1      | 1.19%   |
| Corsair             | 1         | 1      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 74        | 123    | 38.34%  |
| SSD     | 69        | 88     | 35.75%  |
| NVMe    | 40        | 54     | 20.73%  |
| MMC     | 8         | 9      | 4.15%   |
| Unknown | 2         | 2      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 194    | 64.77%  |
| NVMe | 40        | 53     | 22.73%  |
| SAS  | 14        | 20     | 7.95%   |
| MMC  | 8         | 9      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 107    | 52.83%  |
| 0.51-1.0   | 48        | 55     | 30.19%  |
| 1.01-2.0   | 11        | 13     | 6.92%   |
| 4.01-10.0  | 7         | 24     | 4.4%    |
| 3.01-4.0   | 5         | 7      | 3.14%   |
| 2.01-3.0   | 4         | 5      | 2.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 29.14%  |
| 251-500        | 26        | 17.22%  |
| 501-1000       | 25        | 16.56%  |
| 1001-2000      | 18        | 11.92%  |
| More than 3000 | 12        | 7.95%   |
| 51-100         | 11        | 7.28%   |
| 21-50          | 9         | 5.96%   |
| 1-20           | 5         | 3.31%   |
| 2001-3000      | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 48        | 31.79%  |
| 21-50          | 28        | 18.54%  |
| 101-250        | 22        | 14.57%  |
| 251-500        | 15        | 9.93%   |
| 51-100         | 13        | 8.61%   |
| 501-1000       | 9         | 5.96%   |
| More than 3000 | 6         | 3.97%   |
| 1001-2000      | 6         | 3.97%   |
| 2001-3000      | 4         | 2.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 9.09%   |
| Samsung Electronics HD753LJ 752GB                   | 2         | 2      | 6.06%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 3.03%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 3.03%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 3.03%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 3.03%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 3.03%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 3.03%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 3.03%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 3.03%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 3.03%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 3.03%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 3.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.03%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 3.03%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 3.03%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 3.03%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 3.03%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 3.03%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 3.03%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 3.03%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 3.03%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 3.03%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 3.03%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 3.03%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 3.03%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 3.03%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 30.3%   |
| WDC                 | 7         | 7      | 21.21%  |
| Samsung Electronics | 6         | 6      | 18.18%  |
| Toshiba             | 2         | 2      | 6.06%   |
| Hitachi             | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 2      | 6.06%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 38.46%  |
| WDC                 | 7         | 7      | 26.92%  |
| Samsung Electronics | 4         | 4      | 15.38%  |
| Toshiba             | 2         | 2      | 7.69%   |
| Hitachi             | 2         | 2      | 7.69%   |
| HGST                | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 31     | 78.13%  |
| SSD  | 6         | 6      | 18.75%  |
| NVMe | 1         | 1      | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB               | 1         | 1      | 50%     |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 122       | 208    | 69.32%  |
| Malfunc  | 32        | 38     | 18.18%  |
| Detected | 20        | 28     | 11.36%  |
| Failed   | 2         | 2      | 1.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 104       | 53.33%  |
| AMD                         | 33        | 16.92%  |
| Samsung Electronics         | 14        | 7.18%   |
| SanDisk                     | 6         | 3.08%   |
| Phison Electronics          | 6         | 3.08%   |
| Marvell Technology Group    | 5         | 2.56%   |
| ASMedia Technology          | 5         | 2.56%   |
| SK hynix                    | 4         | 2.05%   |
| Nvidia                      | 3         | 1.54%   |
| Union Memory (Shenzhen)     | 2         | 1.03%   |
| JMicron Technology          | 2         | 1.03%   |
| VIA Technologies            | 1         | 0.51%   |
| Silicon Image               | 1         | 0.51%   |
| Seagate Technology          | 1         | 0.51%   |
| Realtek Semiconductor       | 1         | 0.51%   |
| Micron Technology           | 1         | 0.51%   |
| MAXIO Technology (Hangzhou) | 1         | 0.51%   |
| LSI Logic / Symbios Logic   | 1         | 0.51%   |
| KIOXIA                      | 1         | 0.51%   |
| Kingston Technology Company | 1         | 0.51%   |
| Apple                       | 1         | 0.51%   |
| Adaptec                     | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 22        | 9.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 5.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 4.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 3.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 2.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2.16%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 1.72%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.72%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.29%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.29%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.86%   |
| SK hynix BC511                                                                 | 2         | 0.86%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.86%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2         | 0.86%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2         | 0.86%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.86%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.86%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2         | 0.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 0.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 114       | 58.16%  |
| NVMe | 41        | 20.92%  |
| IDE  | 24        | 12.24%  |
| RAID | 13        | 6.63%   |
| SAS  | 3         | 1.53%   |
| SCSI | 1         | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 109       | 73.15%  |
| AMD    | 39        | 26.17%  |
| ARM    | 1         | 0.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 2.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 2.01%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 2.01%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 2.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.34%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 1.34%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 1.34%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 1.34%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.34%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 1.34%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 1.34%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 1.34%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.67%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.67%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.67%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.67%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.67%   |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.67%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.67%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.67%   |
| Intel Pentium 4 CPU 2.80GHz             | 1         | 0.67%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.67%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1         | 0.67%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.67%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.67%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1         | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.67%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.67%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 0.67%   |
| Intel Core i7-6700T CPU @ 2.80GHz       | 1         | 0.67%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 0.67%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 0.67%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz      | 1         | 0.67%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1         | 0.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 1         | 0.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 37        | 24.83%  |
| Intel Core i7          | 33        | 22.15%  |
| Intel Core i3          | 11        | 7.38%   |
| AMD Ryzen 5            | 7         | 4.7%    |
| Other                  | 6         | 4.03%   |
| AMD Ryzen 7            | 6         | 4.03%   |
| Intel Core 2 Duo       | 5         | 3.36%   |
| Intel Celeron          | 5         | 3.36%   |
| AMD Ryzen 9            | 4         | 2.68%   |
| Intel Xeon             | 3         | 2.01%   |
| Intel Core i9          | 3         | 2.01%   |
| AMD Phenom II X4       | 3         | 2.01%   |
| AMD E                  | 3         | 2.01%   |
| Intel Pentium 4        | 2         | 1.34%   |
| AMD Ryzen 3            | 2         | 1.34%   |
| AMD Athlon II X2       | 2         | 1.34%   |
| AMD A4                 | 2         | 1.34%   |
| Intel Pentium Dual     | 1         | 0.67%   |
| Intel Pentium D        | 1         | 0.67%   |
| Intel Pentium          | 1         | 0.67%   |
| Intel Genuine          | 1         | 0.67%   |
| Intel Core 2           | 1         | 0.67%   |
| AMD Ryzen Threadripper | 1         | 0.67%   |
| AMD Ryzen 3 PRO        | 1         | 0.67%   |
| AMD FX                 | 1         | 0.67%   |
| AMD E2                 | 1         | 0.67%   |
| AMD E1                 | 1         | 0.67%   |
| AMD Athlon X4          | 1         | 0.67%   |
| AMD Athlon Dual Core   | 1         | 0.67%   |
| AMD Athlon 64 X2       | 1         | 0.67%   |
| AMD A6                 | 1         | 0.67%   |
| AMD A10                | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 59        | 39.6%   |
| 2      | 55        | 36.91%  |
| 6      | 16        | 10.74%  |
| 8      | 9         | 6.04%   |
| 1      | 3         | 2.01%   |
| 16     | 2         | 1.34%   |
| 12     | 2         | 1.34%   |
| 10     | 2         | 1.34%   |
| 32     | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 148       | 99.33%  |
| 2      | 1         | 0.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 94        | 63.09%  |
| 1      | 55        | 36.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 148       | 99.33%  |
| 32-bit         | 1         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 10.67%  |
| 0x306c3    | 13        | 8.67%   |
| 0x206a7    | 13        | 8.67%   |
| 0x306a9    | 12        | 8%      |
| 0x906ea    | 7         | 4.67%   |
| 0x506e3    | 5         | 3.33%   |
| 0x806ea    | 4         | 2.67%   |
| 0x806c1    | 4         | 2.67%   |
| 0x306d4    | 4         | 2.67%   |
| 0x08701021 | 4         | 2.67%   |
| 0x08600104 | 4         | 2.67%   |
| 0x406e3    | 3         | 2%      |
| 0x10676    | 3         | 2%      |
| 0x010000c8 | 3         | 2%      |
| 0xf41      | 2         | 1.33%   |
| 0xa0652    | 2         | 1.33%   |
| 0x906ed    | 2         | 1.33%   |
| 0x906e9    | 2         | 1.33%   |
| 0x706e5    | 2         | 1.33%   |
| 0x6fd      | 2         | 1.33%   |
| 0x40651    | 2         | 1.33%   |
| 0x206d7    | 2         | 1.33%   |
| 0x106e5    | 2         | 1.33%   |
| 0x0a50000d | 2         | 1.33%   |
| 0x08600106 | 2         | 1.33%   |
| 0x08108109 | 2         | 1.33%   |
| 0x07030105 | 2         | 1.33%   |
| 0xf65      | 1         | 0.67%   |
| 0xa0655    | 1         | 0.67%   |
| 0x806e9    | 1         | 0.67%   |
| 0x706a1    | 1         | 0.67%   |
| 0x6fb      | 1         | 0.67%   |
| 0x6f6      | 1         | 0.67%   |
| 0x506ca    | 1         | 0.67%   |
| 0x506c9    | 1         | 0.67%   |
| 0x50654    | 1         | 0.67%   |
| 0x406c4    | 1         | 0.67%   |
| 0x40661    | 1         | 0.67%   |
| 0x20655    | 1         | 0.67%   |
| 0x106a5    | 1         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 18        | 12.08%  |
| Haswell       | 16        | 10.74%  |
| SandyBridge   | 15        | 10.07%  |
| Zen 2         | 14        | 9.4%    |
| Skylake       | 12        | 8.05%   |
| IvyBridge     | 12        | 8.05%   |
| Penryn        | 5         | 3.36%   |
| K10           | 5         | 3.36%   |
| Broadwell     | 5         | 3.36%   |
| Zen 3         | 4         | 2.68%   |
| TigerLake     | 4         | 2.68%   |
| Core          | 4         | 2.68%   |
| Westmere      | 3         | 2.01%   |
| Puma          | 3         | 2.01%   |
| NetBurst      | 3         | 2.01%   |
| Nehalem       | 3         | 2.01%   |
| CometLake     | 3         | 2.01%   |
| Zen+          | 2         | 1.34%   |
| Piledriver    | 2         | 1.34%   |
| K8 Hammer     | 2         | 1.34%   |
| IceLake       | 2         | 1.34%   |
| Goldmont      | 2         | 1.34%   |
| Bobcat        | 2         | 1.34%   |
| Unknown       | 2         | 1.34%   |
| Zen           | 1         | 0.67%   |
| Steamroller   | 1         | 0.67%   |
| Silvermont    | 1         | 0.67%   |
| K10 Llano     | 1         | 0.67%   |
| Goldmont plus | 1         | 0.67%   |
| Excavator     | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 79        | 45.14%  |
| Nvidia | 56        | 32%     |
| AMD    | 40        | 22.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8         | 4.47%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 3.91%   |
| AMD Renoir                                                                  | 7         | 3.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 3.35%   |
| Intel HD Graphics 530                                                       | 6         | 3.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.23%   |
| Intel HD Graphics 5500                                                      | 4         | 2.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 2.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.23%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.68%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.68%   |
| Intel UHD Graphics 620                                                      | 3         | 1.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 1.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.68%   |
| Nvidia TU117M                                                               | 2         | 1.12%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.12%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.12%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 1.12%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 1.12%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 1.12%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 1.12%   |
| Intel HD Graphics 630                                                       | 2         | 1.12%   |
| Intel HD Graphics 500                                                       | 2         | 1.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.12%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2         | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.12%   |
| AMD Wrestler [Radeon HD 6310]                                               | 2         | 1.12%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.56%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1         | 0.56%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 36.91%  |
| 1 x Nvidia     | 34        | 22.82%  |
| 1 x AMD        | 32        | 21.48%  |
| Intel + Nvidia | 17        | 11.41%  |
| AMD + Nvidia   | 4         | 2.68%   |
| Intel + AMD    | 3         | 2.01%   |
| Other          | 1         | 0.67%   |
| 2 x Nvidia     | 1         | 0.67%   |
| 2 x Intel      | 1         | 0.67%   |
| 2 x AMD        | 1         | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 119       | 79.87%  |
| Proprietary | 28        | 18.79%  |
| Unknown     | 2         | 1.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 44.97%  |
| 1.01-2.0   | 21        | 14.09%  |
| 0.01-0.5   | 20        | 13.42%  |
| 0.51-1.0   | 17        | 11.41%  |
| 3.01-4.0   | 10        | 6.71%   |
| 7.01-8.0   | 4         | 2.68%   |
| 5.01-6.0   | 4         | 2.68%   |
| 8.01-16.0  | 4         | 2.68%   |
| 2.01-3.0   | 1         | 0.67%   |
| 16.01-24.0 | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 13.69%  |
| AU Optronics            | 16        | 9.52%   |
| LG Display              | 14        | 8.33%   |
| Goldstar                | 12        | 7.14%   |
| Hewlett-Packard         | 10        | 5.95%   |
| Philips                 | 9         | 5.36%   |
| Dell                    | 9         | 5.36%   |
| Chimei Innolux          | 9         | 5.36%   |
| BOE                     | 9         | 5.36%   |
| Acer                    | 9         | 5.36%   |
| Ancor Communications    | 7         | 4.17%   |
| Lenovo                  | 4         | 2.38%   |
| Apple                   | 3         | 1.79%   |
| AOC                     | 3         | 1.79%   |
| Sharp                   | 2         | 1.19%   |
| Iiyama                  | 2         | 1.19%   |
| Hannspree               | 2         | 1.19%   |
| Eizo                    | 2         | 1.19%   |
| Chi Mei Optoelectronics | 2         | 1.19%   |
| BenQ                    | 2         | 1.19%   |
| ASUSTek Computer        | 2         | 1.19%   |
| VIE                     | 1         | 0.6%    |
| Unknown                 | 1         | 0.6%    |
| UGD                     | 1         | 0.6%    |
| TVT                     | 1         | 0.6%    |
| Targa Visionary         | 1         | 0.6%    |
| Sony                    | 1         | 0.6%    |
| Seiki                   | 1         | 0.6%    |
| ONN                     | 1         | 0.6%    |
| Onkyo                   | 1         | 0.6%    |
| NEC Computers           | 1         | 0.6%    |
| Medion                  | 1         | 0.6%    |
| LG Philips              | 1         | 0.6%    |
| KTC                     | 1         | 0.6%    |
| Fujitsu Siemens         | 1         | 0.6%    |
| DENON                   | 1         | 0.6%    |
| CPT                     | 1         | 0.6%    |
| Arnos Instruments       | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 1.13%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.13%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 1.13%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                    | 2         | 1.13%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 2         | 1.13%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.13%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                   | 1         | 0.56%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                   | 1         | 0.56%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch                 | 1         | 0.56%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                          | 1         | 0.56%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch     | 1         | 0.56%   |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                      | 1         | 0.56%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                 | 1         | 0.56%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 0.56%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                     | 1         | 0.56%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1         | 0.56%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch    | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch     | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch    | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch    | 1         | 0.56%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1         | 0.56%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch     | 1         | 0.56%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch     | 1         | 0.56%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1         | 0.56%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.56%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 73        | 46.2%   |
| 1366x768 (WXGA)    | 24        | 15.19%  |
| 3840x2160 (4K)     | 15        | 9.49%   |
| 1280x1024 (SXGA)   | 10        | 6.33%   |
| 1680x1050 (WSXGA+) | 7         | 4.43%   |
| 1600x900 (HD+)     | 7         | 4.43%   |
| 2560x1440 (QHD)    | 4         | 2.53%   |
| 1920x1200 (WUXGA)  | 4         | 2.53%   |
| 1440x900 (WXGA+)   | 4         | 2.53%   |
| 1360x768           | 2         | 1.27%   |
| 1280x800 (WXGA)    | 2         | 1.27%   |
| 5760x2160          | 1         | 0.63%   |
| 2880x1800          | 1         | 0.63%   |
| 2160x1440          | 1         | 0.63%   |
| 1600x1200          | 1         | 0.63%   |
| 1400x1050          | 1         | 0.63%   |
| Unknown            | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 42        | 25%     |
| 21      | 17        | 10.12%  |
| 27      | 14        | 8.33%   |
| 24      | 14        | 8.33%   |
| 23      | 14        | 8.33%   |
| 13      | 10        | 5.95%   |
| 19      | 8         | 4.76%   |
| 17      | 8         | 4.76%   |
| 14      | 6         | 3.57%   |
| 31      | 5         | 2.98%   |
| 22      | 5         | 2.98%   |
| 18      | 5         | 2.98%   |
| 20      | 4         | 2.38%   |
| 12      | 4         | 2.38%   |
| 84      | 2         | 1.19%   |
| 65      | 1         | 0.6%    |
| 54      | 1         | 0.6%    |
| 52      | 1         | 0.6%    |
| 50      | 1         | 0.6%    |
| 43      | 1         | 0.6%    |
| 32      | 1         | 0.6%    |
| 26      | 1         | 0.6%    |
| 16      | 1         | 0.6%    |
| 11      | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 35.37%  |
| 501-600     | 39        | 23.78%  |
| 401-500     | 33        | 20.12%  |
| 201-300     | 11        | 6.71%   |
| 601-700     | 7         | 4.27%   |
| 351-400     | 7         | 4.27%   |
| 1001-1500   | 4         | 2.44%   |
| 1501-2000   | 2         | 1.22%   |
| 701-800     | 1         | 0.61%   |
| 901-1000    | 1         | 0.61%   |
| Unknown     | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 115       | 76.16%  |
| 16/10   | 22        | 14.57%  |
| 5/4     | 9         | 5.96%   |
| 4/3     | 2         | 1.32%   |
| 3/2     | 2         | 1.32%   |
| Unknown | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 25.3%   |
| 201-250        | 39        | 23.49%  |
| 301-350        | 15        | 9.04%   |
| 151-200        | 15        | 9.04%   |
| 81-90          | 11        | 6.63%   |
| 141-150        | 11        | 6.63%   |
| More than 1000 | 6         | 3.61%   |
| 351-500        | 6         | 3.61%   |
| 251-300        | 6         | 3.61%   |
| 71-80          | 5         | 3.01%   |
| 61-70          | 4         | 2.41%   |
| 51-60          | 1         | 0.6%    |
| 131-140        | 1         | 0.6%    |
| 121-130        | 1         | 0.6%    |
| 111-120        | 1         | 0.6%    |
| 501-1000       | 1         | 0.6%    |
| Unknown        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 68        | 42.77%  |
| 101-120       | 40        | 25.16%  |
| 121-160       | 35        | 22.01%  |
| 161-240       | 11        | 6.92%   |
| More than 240 | 2         | 1.26%   |
| 1-50          | 2         | 1.26%   |
| Unknown       | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 114       | 75.5%   |
| 2     | 35        | 23.18%  |
| 3     | 1         | 0.66%   |
| 0     | 1         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 80        | 35.24%  |
| Realtek Semiconductor             | 79        | 34.8%   |
| Qualcomm Atheros                  | 26        | 11.45%  |
| Broadcom                          | 12        | 5.29%   |
| TP-Link                           | 3         | 1.32%   |
| Nvidia                            | 3         | 1.32%   |
| Broadcom Limited                  | 3         | 1.32%   |
| ASIX Electronics                  | 3         | 1.32%   |
| Ralink                            | 2         | 0.88%   |
| MediaTek                          | 2         | 0.88%   |
| Ericsson Business Mobile Networks | 2         | 0.88%   |
| Aquantia                          | 2         | 0.88%   |
| ZyDAS                             | 1         | 0.44%   |
| Wacom                             | 1         | 0.44%   |
| Ralink Technology                 | 1         | 0.44%   |
| Qualcomm Atheros Communications   | 1         | 0.44%   |
| NetGear                           | 1         | 0.44%   |
| Microsoft                         | 1         | 0.44%   |
| Marvell Technology Group          | 1         | 0.44%   |
| InterBiometrics                   | 1         | 0.44%   |
| Huawei Technologies               | 1         | 0.44%   |
| DisplayLink                       | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 56        | 21.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 15        | 5.77%   |
| Intel Wireless 7265                                                | 8         | 3.08%   |
| Intel I211 Gigabit Network Connection                              | 6         | 2.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 5         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 5         | 1.92%   |
| Intel Wireless-AC 9260                                             | 5         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 5         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 4         | 1.54%   |
| Intel Wireless 8265 / 8275                                         | 4         | 1.54%   |
| Intel Wi-Fi 6 AX201                                                | 4         | 1.54%   |
| Intel Ethernet Connection I217-LM                                  | 4         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 3         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 3         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 3         | 1.15%   |
| Intel Wireless 7260                                                | 3         | 1.15%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 1.15%   |
| Intel Ethernet Connection (2) I219-V                               | 3         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                     | 3         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 2         | 0.77%   |
| Realtek 802.11ac NIC                                               | 2         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller          | 2         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 2         | 0.77%   |
| Nvidia MCP77 Ethernet                                              | 2         | 0.77%   |
| Intel Wireless 8260                                                | 2         | 0.77%   |
| Intel WiFi Link 5100                                               | 2         | 0.77%   |
| Intel Ethernet Connection I219-LM                                  | 2         | 0.77%   |
| Intel Ethernet Connection I217-V                                   | 2         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                           | 2         | 0.77%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                     | 2         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                      | 2         | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                      | 2         | 0.77%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]  | 2         | 0.77%   |
| ZyDAS ZD1211B 802.11g                                              | 1         | 0.38%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                           | 1         | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 1         | 0.38%   |
| TP-Link 802.11ac WLAN Adapter                                      | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 48.62%  |
| Qualcomm Atheros                | 20        | 18.35%  |
| Realtek Semiconductor           | 16        | 14.68%  |
| Broadcom                        | 7         | 6.42%   |
| TP-Link                         | 3         | 2.75%   |
| Ralink                          | 2         | 1.83%   |
| ZyDAS                           | 1         | 0.92%   |
| Wacom                           | 1         | 0.92%   |
| Ralink Technology               | 1         | 0.92%   |
| Qualcomm Atheros Communications | 1         | 0.92%   |
| NetGear                         | 1         | 0.92%   |
| Microsoft                       | 1         | 0.92%   |
| MediaTek                        | 1         | 0.92%   |
| Broadcom Limited                | 1         | 0.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 8         | 7.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 5         | 4.55%   |
| Intel Wireless-AC 9260                                           | 5         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 5         | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 5         | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 3.64%   |
| Intel Wireless 8265 / 8275                                       | 4         | 3.64%   |
| Intel Wi-Fi 6 AX201                                              | 4         | 3.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 3         | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 3         | 2.73%   |
| Intel Wireless 7260                                              | 3         | 2.73%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 2.73%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 2.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 1.82%   |
| Realtek 802.11ac NIC                                             | 2         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 2         | 1.82%   |
| Intel Wireless 8260                                              | 2         | 1.82%   |
| Intel WiFi Link 5100                                             | 2         | 1.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                   | 2         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 1.82%   |
| ZyDAS ZD1211B 802.11g                                            | 1         | 0.91%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                         | 1         | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]       | 1         | 0.91%   |
| TP-Link 802.11ac WLAN Adapter                                    | 1         | 0.91%   |
| TP-Link 802.11ac NIC                                             | 1         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 0.91%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter          | 1         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 0.91%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1         | 0.91%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller        | 1         | 0.91%   |
| Realtek Realtek Network controller                               | 1         | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 0.91%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                  | 1         | 0.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                 | 1         | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)   | 1         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 66        | 45.52%  |
| Intel                    | 52        | 35.86%  |
| Qualcomm Atheros         | 7         | 4.83%   |
| Broadcom                 | 7         | 4.83%   |
| Nvidia                   | 3         | 2.07%   |
| ASIX Electronics         | 3         | 2.07%   |
| Broadcom Limited         | 2         | 1.38%   |
| Aquantia                 | 2         | 1.38%   |
| MediaTek                 | 1         | 0.69%   |
| Marvell Technology Group | 1         | 0.69%   |
| DisplayLink              | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 38.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 10.27%  |
| Intel I211 Gigabit Network Connection                             | 6         | 4.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.42%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.37%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.37%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.37%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.37%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.37%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.37%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.68%   |
| MediaTek moto e(6) plus                                           | 1         | 0.68%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.68%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.68%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.68%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 134       | 54.69%  |
| WiFi     | 107       | 43.67%  |
| Modem    | 4         | 1.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 81        | 50.31%  |
| WiFi     | 80        | 49.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 83        | 55.7%   |
| 1     | 63        | 42.28%  |
| 3     | 2         | 1.34%   |
| 0     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 118       | 79.19%  |
| Yes  | 31        | 20.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 48.78%  |
| Qualcomm Atheros Communications | 8         | 9.76%   |
| Realtek Semiconductor           | 6         | 7.32%   |
| Cambridge Silicon Radio         | 6         | 7.32%   |
| Broadcom                        | 5         | 6.1%    |
| Apple                           | 4         | 4.88%   |
| ASUSTek Computer                | 3         | 3.66%   |
| Realtek                         | 2         | 2.44%   |
| Ralink Technology               | 2         | 2.44%   |
| Lite-On Technology              | 2         | 2.44%   |
| MediaTek                        | 1         | 1.22%   |
| Hewlett-Packard                 | 1         | 1.22%   |
| Foxconn International           | 1         | 1.22%   |
| Dell                            | 1         | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 21.95%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 7.32%   |
| Intel AX201 Bluetooth                               | 6         | 7.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 7.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 6.1%    |
| Realtek Bluetooth Radio                             | 4         | 4.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 4.88%   |
| Intel AX200 Bluetooth                               | 3         | 3.66%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 2.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.44%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 2.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 2.44%   |
| Apple Bluetooth Host Controller                     | 2         | 2.44%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.22%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.22%   |
| Ralink CSR BS8510                                   | 1         | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.22%   |
| MediaTek Wireless_Device                            | 1         | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.22%   |
| Intel AX210 Bluetooth                               | 1         | 1.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.22%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.22%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 1.22%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.22%   |
| ASUS BCM20702A0                                     | 1         | 1.22%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.22%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 105       | 42.17%  |
| Nvidia                               | 46        | 18.47%  |
| AMD                                  | 44        | 17.67%  |
| Texas Instruments                    | 5         | 2.01%   |
| C-Media Electronics                  | 5         | 2.01%   |
| Yamaha                               | 4         | 1.61%   |
| Logitech                             | 3         | 1.2%    |
| JMTek                                | 3         | 1.2%    |
| QinHeng Electronics                  | 2         | 0.8%    |
| PreSonus Audio Electronics           | 2         | 0.8%    |
| Mackie Designs                       | 2         | 0.8%    |
| M-Audio                              | 2         | 0.8%    |
| Focusrite-Novation                   | 2         | 0.8%    |
| ZOOM                                 | 1         | 0.4%    |
| Yealink Network Technology           | 1         | 0.4%    |
| Xilinx                               | 1         | 0.4%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.4%    |
| Textech International                | 1         | 0.4%    |
| Studiologic                          | 1         | 0.4%    |
| SteelSeries ApS                      | 1         | 0.4%    |
| Samson Technologies                  | 1         | 0.4%    |
| Plantronics                          | 1         | 0.4%    |
| MIDITECH                             | 1         | 0.4%    |
| Medeli Electronics                   | 1         | 0.4%    |
| Mark of the Unicorn                  | 1         | 0.4%    |
| KTMicro                              | 1         | 0.4%    |
| Jieli Technology                     | 1         | 0.4%    |
| Harman                               | 1         | 0.4%    |
| Generalplus Technology               | 1         | 0.4%    |
| Ensoniq                              | 1         | 0.4%    |
| Creative Technology                  | 1         | 0.4%    |
| Behringer.......                     | 1         | 0.4%    |
| BEHRINGER International              | 1         | 0.4%    |
| ASUSTek Computer                     | 1         | 0.4%    |
| Apple                                | 1         | 0.4%    |
| Alesis                               | 1         | 0.4%    |
| AKAI Professional M.I.               | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 14        | 4.81%   |
| AMD Family 17h/19h HD Audio Controller                                            | 13        | 4.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 12        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 12        | 4.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9         | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                        | 9         | 3.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 9         | 3.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7         | 2.41%   |
| Intel Sunrise Point-LP HD Audio                                                   | 7         | 2.41%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7         | 2.41%   |
| AMD FCH Azalia Controller                                                         | 7         | 2.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6         | 2.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6         | 2.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 1.72%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 5         | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 1.37%   |
| Intel 200 Series PCH HD Audio                                                     | 4         | 1.37%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3         | 1.03%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3         | 1.03%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3         | 1.03%   |
| Intel Comet Lake PCH cAVS                                                         | 3         | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3         | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                          | 3         | 1.03%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 1.03%   |
| QinHeng Electronics CH345 MIDI adapter                                            | 2         | 0.69%   |
| PreSonus Audio Electronics Studio 24c                                             | 2         | 0.69%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2         | 0.69%   |
| Nvidia High Definition Audio Controller                                           | 2         | 0.69%   |
| Nvidia GT216 HDMI Audio Controller                                                | 2         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 0.69%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2         | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 21.86%  |
| SK hynix            | 39        | 21.31%  |
| Kingston            | 21        | 11.48%  |
| Micron Technology   | 15        | 8.2%    |
| Unknown             | 13        | 7.1%    |
| Crucial             | 12        | 6.56%   |
| Corsair             | 11        | 6.01%   |
| G.Skill             | 8         | 4.37%   |
| Patriot             | 4         | 2.19%   |
| Ramaxel Technology  | 3         | 1.64%   |
| Nanya Technology    | 3         | 1.64%   |
| Timetec             | 2         | 1.09%   |
| Unifosa             | 1         | 0.55%   |
| Transcend           | 1         | 0.55%   |
| Smart               | 1         | 0.55%   |
| S                   | 1         | 0.55%   |
| PNY                 | 1         | 0.55%   |
| OCZ                 | 1         | 0.55%   |
| M                   | 1         | 0.55%   |
| HBS                 | 1         | 0.55%   |
| Elpida              | 1         | 0.55%   |
| Aeneon              | 1         | 0.55%   |
| 0194808980CE        | 1         | 0.55%   |
| Unknown             | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.47%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s      | 3         | 1.47%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 2         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.98%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s               | 2         | 0.98%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 0.98%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.98%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 2         | 0.98%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 2         | 0.98%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s    | 2         | 0.98%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s        | 2         | 0.98%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 2         | 0.98%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s  | 2         | 0.98%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 2         | 0.98%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 2         | 0.98%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR                         | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s          | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 256MB DIMM DDR                         | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR                        | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 1         | 0.49%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s               | 1         | 0.49%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s         | 1         | 0.49%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s        | 1         | 0.49%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.49%   |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.49%   |
| Smart RAM SH564568FH8N0QHSC 2GB DIMM DDR3 1333MT/s        | 1         | 0.49%   |
| SK hynix RAM TMT41GU6BFR8C-PBSC 8192MB DIMM DDR3 1600MT/s | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 72        | 46.75%  |
| DDR4    | 54        | 35.06%  |
| DDR2    | 11        | 7.14%   |
| SDRAM   | 5         | 3.25%   |
| Unknown | 4         | 2.6%    |
| LPDDR4  | 3         | 1.95%   |
| DDR     | 3         | 1.95%   |
| LPDDR3  | 2         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 48.03%  |
| DIMM         | 67        | 44.08%  |
| Row Of Chips | 9         | 5.92%   |
| FB-DIMM      | 1         | 0.66%   |
| Chip         | 1         | 0.66%   |
| Unknown      | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 60        | 34.48%  |
| 8192  | 51        | 29.31%  |
| 2048  | 23        | 13.22%  |
| 16384 | 19        | 10.92%  |
| 1024  | 10        | 5.75%   |
| 32768 | 8         | 4.6%    |
| 512   | 2         | 1.15%   |
| 256   | 1         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 54        | 32.53%  |
| 3200    | 15        | 9.04%   |
| 2667    | 13        | 7.83%   |
| 1333    | 13        | 7.83%   |
| 2133    | 8         | 4.82%   |
| 1334    | 7         | 4.22%   |
| 667     | 7         | 4.22%   |
| 2400    | 6         | 3.61%   |
| 3600    | 5         | 3.01%   |
| 1066    | 4         | 2.41%   |
| 800     | 4         | 2.41%   |
| 4267    | 3         | 1.81%   |
| 3266    | 3         | 1.81%   |
| 1866    | 3         | 1.81%   |
| Unknown | 3         | 1.81%   |
| 4199    | 2         | 1.2%    |
| 1867    | 2         | 1.2%    |
| 1800    | 2         | 1.2%    |
| 533     | 2         | 1.2%    |
| 3500    | 1         | 0.6%    |
| 3466    | 1         | 0.6%    |
| 3000    | 1         | 0.6%    |
| 2934    | 1         | 0.6%    |
| 2933    | 1         | 0.6%    |
| 2800    | 1         | 0.6%    |
| 2666    | 1         | 0.6%    |
| 2472    | 1         | 0.6%    |
| 1639    | 1         | 0.6%    |
| 1067    | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Ricoh           | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Ricoh Aficio SP 100SU | 1         | 20%     |
| HP OfficeJet Pro 6960 | 1         | 20%     |
| HP OfficeJet 6950     | 1         | 20%     |
| HP LaserJet 1022      | 1         | 20%     |
| Canon LiDE 400        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LiDE 60 | 1         | 33.33%  |
| Canon CanoScan FB630U  | 1         | 33.33%  |
| Canon CanoScan 4200F   | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 20.99%  |
| Microdia                               | 7         | 8.64%   |
| IMC Networks                           | 7         | 8.64%   |
| Sunplus Innovation Technology          | 6         | 7.41%   |
| Realtek Semiconductor                  | 6         | 7.41%   |
| Logitech                               | 6         | 7.41%   |
| Syntek                                 | 4         | 4.94%   |
| Suyin                                  | 4         | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.7%    |
| Samsung Electronics                    | 2         | 2.47%   |
| Quanta                                 | 2         | 2.47%   |
| Philips (or NXP)                       | 2         | 2.47%   |
| Microsoft                              | 2         | 2.47%   |
| Apple                                  | 2         | 2.47%   |
| Acer                                   | 2         | 2.47%   |
| Xiongmai                               | 1         | 1.23%   |
| ViewSonic                              | 1         | 1.23%   |
| ViewQuest Technologies                 | 1         | 1.23%   |
| Sweex                                  | 1         | 1.23%   |
| Sunplus IT                             | 1         | 1.23%   |
| Silicon Motion                         | 1         | 1.23%   |
| Ricoh                                  | 1         | 1.23%   |
| Intel                                  | 1         | 1.23%   |
| Importek                               | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Syntek Integrated Camera                   | 4         | 4.88%   |
| Chicony Integrated Camera                  | 4         | 4.88%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 3.66%   |
| IMC Networks Integrated Camera             | 3         | 3.66%   |
| Chicony Integrated Camera [ThinkPad]       | 3         | 3.66%   |
| Suyin Asus Integrated Webcam               | 2         | 2.44%   |
| Sunplus Integrated_Webcam_HD               | 2         | 2.44%   |
| Sunplus HD WebCam                          | 2         | 2.44%   |
| Samsung Galaxy A5 (MTP)                    | 2         | 2.44%   |
| Realtek Lenovo EasyCamera                  | 2         | 2.44%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.44%   |
| Logitech Webcam C270                       | 2         | 2.44%   |
| Chicony HP HD Camera                       | 2         | 2.44%   |
| Xiongmai web camera                        | 1         | 1.22%   |
| ViewSonic PC Camera                        | 1         | 1.22%   |
| ViewQuest Ability GABB Webcam              | 1         | 1.22%   |
| Sweex WC060 Series HD Webcam               | 1         | 1.22%   |
| Suyin HP Webcam                            | 1         | 1.22%   |
| Suyin HP TrueVision HD Integrated Webcam   | 1         | 1.22%   |
| Sunplus IT AUKEY PC-LM1 USB Camera         | 1         | 1.22%   |
| Sunplus HD 720P webcam                     | 1         | 1.22%   |
| Sunplus Dell HD Webcam                     | 1         | 1.22%   |
| Silicon Motion WebCam SCB-1100N            | 1         | 1.22%   |
| Ricoh Sony Vaio Integrated Webcam          | 1         | 1.22%   |
| Realtek VGA WebCam                         | 1         | 1.22%   |
| Realtek MTD camera                         | 1         | 1.22%   |
| Realtek Integrated_Webcam_HD               | 1         | 1.22%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.22%   |
| Quanta ov9734_techfront_camera             | 1         | 1.22%   |
| Quanta HP TrueVision HD Camera             | 1         | 1.22%   |
| Philips (or NXP) Webcam SPC530NC           | 1         | 1.22%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc] | 1         | 1.22%   |
| Microsoft LifeCam VX-5000                  | 1         | 1.22%   |
| Microsoft LifeCam Cinema                   | 1         | 1.22%   |
| Microdia USB 2.0 Camera                    | 1         | 1.22%   |
| Microdia Sonix Integrated Webcam           | 1         | 1.22%   |
| Microdia MSI Starcam Racer                 | 1         | 1.22%   |
| Microdia Integrated_Webcam_FHD             | 1         | 1.22%   |
| Microdia Integrated Webcam HD              | 1         | 1.22%   |
| Logitech QuickCam Communicate MP/S5500     | 1         | 1.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Shenzhen Goodix Technology | 3         | 30%     |
| Synaptics                  | 2         | 20%     |
| LighTuning Technology      | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 10%     |
| Validity Sensors Fingerprint scanner                       | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 10%     |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 10%     |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 44.44%  |
| Upek        | 3         | 33.33%  |
| Lenovo      | 1         | 11.11%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 22.22%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 110       | 73.83%  |
| 1     | 35        | 23.49%  |
| 2     | 3         | 2.01%   |
| 3     | 1         | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 25%     |
| Fingerprint reader       | 10        | 25%     |
| Chipcard                 | 8         | 20%     |
| Net/wireless             | 5         | 12.5%   |
| Sound                    | 2         | 5%      |
| Multimedia controller    | 2         | 5%      |
| Modem                    | 1         | 2.5%    |
| Communication controller | 1         | 2.5%    |
| Camera                   | 1         | 2.5%    |

