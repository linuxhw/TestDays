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

Total: 195

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 745 G3            | Notebook    | [5a1b8d9fd3](https://linux-hardware.org/?probe=5a1b8d9fd3) | Jun 04, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| Lenovo        | ThinkPad L460 20FVS3JK00    | Notebook    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [bffa46ef83](https://linux-hardware.org/?probe=bffa46ef83) | May 07, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [cbf9d11153](https://linux-hardware.org/?probe=cbf9d11153) | May 07, 2023 |
| ECS           | H410-SF110                  | Desktop     | [5e5011bdd3](https://linux-hardware.org/?probe=5e5011bdd3) | May 07, 2023 |
| HP            | 1495                        | Desktop     | [d6e629523f](https://linux-hardware.org/?probe=d6e629523f) | May 01, 2023 |
| DEPO Compu... | MS-7846                     | Desktop     | [bf72733735](https://linux-hardware.org/?probe=bf72733735) | Apr 13, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [2743830739](https://linux-hardware.org/?probe=2743830739) | Apr 11, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6347cdcf9c](https://linux-hardware.org/?probe=6347cdcf9c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3ce456f3c8](https://linux-hardware.org/?probe=3ce456f3c8) | Mar 25, 2023 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | Desktop     | [a2c287936d](https://linux-hardware.org/?probe=a2c287936d) | Mar 24, 2023 |
| Lenovo        | ThinkPad X250 20CL001LMB    | Notebook    | [d78880e600](https://linux-hardware.org/?probe=d78880e600) | Mar 17, 2023 |
| HP            | Pavilion dv8                | Notebook    | [105a616a39](https://linux-hardware.org/?probe=105a616a39) | Mar 14, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [8553f4abea](https://linux-hardware.org/?probe=8553f4abea) | Mar 13, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [7d9e6e46db](https://linux-hardware.org/?probe=7d9e6e46db) | Mar 13, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [257b3941af](https://linux-hardware.org/?probe=257b3941af) | Mar 10, 2023 |
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
| Ubuntu Studio 20.04 | 80        | 47.9%   |
| Ubuntu Studio 22.04 | 44        | 26.35%  |
| Ubuntu Studio 20.10 | 13        | 7.78%   |
| Ubuntu Studio 22.10 | 9         | 5.39%   |
| Ubuntu Studio 21.10 | 7         | 4.19%   |
| Ubuntu Studio 21.04 | 5         | 2.99%   |
| Ubuntu Studio 23.04 | 3         | 1.8%    |
| Ubuntu Studio 18.04 | 3         | 1.8%    |
| Ubuntu Studio 19.10 | 2         | 1.2%    |
| Ubuntu Studio 16.04 | 1         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 165       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-56-lowlatency   | 5         | 2.94%   |
| 5.15.0-46-lowlatency   | 5         | 2.94%   |
| 5.13.0-28-lowlatency   | 5         | 2.94%   |
| 5.4.0-52-lowlatency    | 4         | 2.35%   |
| 5.4.0-42-lowlatency    | 4         | 2.35%   |
| 6.2.0-1003-lowlatency  | 3         | 1.76%   |
| 5.8.0-55-lowlatency    | 3         | 1.76%   |
| 5.8.0-50-lowlatency    | 3         | 1.76%   |
| 5.8.0-44-lowlatency    | 3         | 1.76%   |
| 5.8.0-25-lowlatency    | 3         | 1.76%   |
| 5.4.0-65-lowlatency    | 3         | 1.76%   |
| 5.4.0-26-lowlatency    | 3         | 1.76%   |
| 5.15.0-67-lowlatency   | 3         | 1.76%   |
| 5.15.0-58-lowlatency   | 3         | 1.76%   |
| 5.15.0-52-lowlatency   | 3         | 1.76%   |
| 5.15.0-50-lowlatency   | 3         | 1.76%   |
| 5.15.0-48-lowlatency   | 3         | 1.76%   |
| 5.15.0-47-lowlatency   | 3         | 1.76%   |
| 5.11.0-44-lowlatency   | 3         | 1.76%   |
| 5.11.0-34-lowlatency   | 3         | 1.76%   |
| 5.8.0-48-lowlatency    | 2         | 1.18%   |
| 5.8.0-29-lowlatency    | 2         | 1.18%   |
| 5.4.0-94-lowlatency    | 2         | 1.18%   |
| 5.4.0-58-lowlatency    | 2         | 1.18%   |
| 5.4.0-56-lowlatency    | 2         | 1.18%   |
| 5.4.0-45-lowlatency    | 2         | 1.18%   |
| 5.19.0-1021-lowlatency | 2         | 1.18%   |
| 5.19.0-1017-lowlatency | 2         | 1.18%   |
| 5.19.0-1015-lowlatency | 2         | 1.18%   |
| 5.19.0-1007-lowlatency | 2         | 1.18%   |
| 5.15.0-71-lowlatency   | 2         | 1.18%   |
| 5.15.0-69-lowlatency   | 2         | 1.18%   |
| 5.15.0-53-lowlatency   | 2         | 1.18%   |
| 5.15.0-40-lowlatency   | 2         | 1.18%   |
| 5.15.0-30-lowlatency   | 2         | 1.18%   |
| 5.13.0-30-lowlatency   | 2         | 1.18%   |
| 5.11.0-27-lowlatency   | 2         | 1.18%   |
| 6.2.8-x64v3-xanmod1    | 1         | 0.59%   |
| 5.8.0-59-lowlatency    | 1         | 0.59%   |
| 5.8.0-45-lowlatency    | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 30.54%  |
| 5.15.0  | 43        | 25.75%  |
| 5.8.0   | 23        | 13.77%  |
| 5.11.0  | 15        | 8.98%   |
| 5.19.0  | 12        | 7.19%   |
| 5.13.0  | 10        | 5.99%   |
| 6.2.0   | 3         | 1.8%    |
| 4.15.0  | 3         | 1.8%    |
| 5.3.0   | 2         | 1.2%    |
| 6.2.8   | 1         | 0.6%    |
| 5.7.6   | 1         | 0.6%    |
| 5.17.1  | 1         | 0.6%    |
| 5.15.6  | 1         | 0.6%    |
| 4.4.0   | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 51        | 30.54%  |
| 5.15    | 44        | 26.35%  |
| 5.8     | 23        | 13.77%  |
| 5.11    | 15        | 8.98%   |
| 5.19    | 12        | 7.19%   |
| 5.13    | 10        | 5.99%   |
| 6.2     | 4         | 2.4%    |
| 4.15    | 3         | 1.8%    |
| 5.3     | 2         | 1.2%    |
| 5.7     | 1         | 0.6%    |
| 5.17    | 1         | 0.6%    |
| 4.4     | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 163       | 98.79%  |
| i686    | 1         | 0.61%   |
| aarch64 | 1         | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 77        | 46.39%  |
| KDE5            | 71        | 42.77%  |
| GNOME           | 10        | 6.02%   |
| LXQt            | 3         | 1.81%   |
| MATE            | 2         | 1.2%    |
| KDE             | 1         | 0.6%    |
| GNOME Flashback | 1         | 0.6%    |
| Cinnamon        | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 157       | 94.58%  |
| Wayland | 5         | 3.01%   |
| Tty     | 4         | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 65        | 39.39%  |
| TDM     | 49        | 29.7%   |
| LightDM | 38        | 23.03%  |
| GDM     | 11        | 6.67%   |
| LXDM    | 1         | 0.61%   |
| GDM3    | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 68        | 40.96%  |
| fr_FR      | 21        | 12.65%  |
| de_DE      | 12        | 7.23%   |
| C          | 8         | 4.82%   |
| pt_BR      | 6         | 3.61%   |
| it_IT      | 6         | 3.61%   |
| en_GB      | 6         | 3.61%   |
| ru_RU      | 4         | 2.41%   |
| en_CA      | 4         | 2.41%   |
| en_AU      | 3         | 1.81%   |
| nl_NL      | 2         | 1.2%    |
| es_ES      | 2         | 1.2%    |
| en_AG      | 2         | 1.2%    |
| Unknown    | 2         | 1.2%    |
| sv_SE      | 1         | 0.6%    |
| sk_SK      | 1         | 0.6%    |
| nl_BE      | 1         | 0.6%    |
| nb_NO      | 1         | 0.6%    |
| hu_HU      | 1         | 0.6%    |
| fr_FR.UTF8 | 1         | 0.6%    |
| fr_CH      | 1         | 0.6%    |
| fr_BE      | 1         | 0.6%    |
| es_NI      | 1         | 0.6%    |
| es_MX      | 1         | 0.6%    |
| es_GT      | 1         | 0.6%    |
| es_CR      | 1         | 0.6%    |
| es_AR      | 1         | 0.6%    |
| en_NG      | 1         | 0.6%    |
| en_IE      | 1         | 0.6%    |
| en_DE      | 1         | 0.6%    |
| de_CH      | 1         | 0.6%    |
| de_AT      | 1         | 0.6%    |
| ca_ES      | 1         | 0.6%    |
| ca_AD      | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 95        | 57.58%  |
| BIOS | 70        | 42.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 157       | 95.15%  |
| Overlay | 6         | 3.64%   |
| Xfs     | 1         | 0.61%   |
| Ext2    | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 104       | 63.03%  |
| MBR  | 61        | 36.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 79.64%  |
| Yes       | 34        | 20.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 55.42%  |
| Yes       | 74        | 44.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 30        | 18.18%  |
| Dell                    | 26        | 15.76%  |
| Lenovo                  | 23        | 13.94%  |
| Hewlett-Packard         | 23        | 13.94%  |
| Gigabyte Technology     | 12        | 7.27%   |
| Apple                   | 6         | 3.64%   |
| Acer                    | 6         | 3.64%   |
| Fujitsu                 | 4         | 2.42%   |
| Intel                   | 3         | 1.82%   |
| ASRock                  | 3         | 1.82%   |
| Toshiba                 | 2         | 1.21%   |
| MSI                     | 2         | 1.21%   |
| HUAWEI                  | 2         | 1.21%   |
| AZW                     | 2         | 1.21%   |
| System76                | 1         | 0.61%   |
| Sony                    | 1         | 0.61%   |
| Samsung Electronics     | 1         | 0.61%   |
| Razer                   | 1         | 0.61%   |
| Raspberry Pi Foundation | 1         | 0.61%   |
| Pegatron                | 1         | 0.61%   |
| Packard Bell            | 1         | 0.61%   |
| Medion                  | 1         | 0.61%   |
| Intel Client Systems    | 1         | 0.61%   |
| IBM                     | 1         | 0.61%   |
| GPU Company             | 1         | 0.61%   |
| Google                  | 1         | 0.61%   |
| Getac                   | 1         | 0.61%   |
| Foxconn                 | 1         | 0.61%   |
| ECS                     | 1         | 0.61%   |
| DEPO Computers          | 1         | 0.61%   |
| COM1                    | 1         | 0.61%   |
| Clevo                   | 1         | 0.61%   |
| Avell High Performance  | 1         | 0.61%   |
| ATOPNUC                 | 1         | 0.61%   |
| Acidanthera             | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 2.42%   |
| Lenovo G50-45 80E3                         | 2         | 1.21%   |
| HP Pavilion dv6                            | 2         | 1.21%   |
| Dell OptiPlex 790                          | 2         | 1.21%   |
| ASUS PRIME X570-PRO                        | 2         | 1.21%   |
| ASUS M4A785-M                              | 2         | 1.21%   |
| Toshiba Satellite L755D                    | 1         | 0.61%   |
| Toshiba Satellite C855                     | 1         | 0.61%   |
| System76 Thelio                            | 1         | 0.61%   |
| Sony VGN-NS31M_W                           | 1         | 0.61%   |
| Samsung 305V4A/305V5A                      | 1         | 0.61%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.61%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.61%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.61%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.61%   |
| MSI MS-7A57                                | 1         | 0.61%   |
| MSI MS-7752                                | 1         | 0.61%   |
| Medion MD34207/C746                        | 1         | 0.61%   |
| Lenovo ThinkPad X250 20CL001LMB            | 1         | 0.61%   |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.61%   |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.61%   |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.61%   |
| Lenovo ThinkPad X1 Yoga Gen 7 21CDCTO1WW   | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.61%   |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.61%   |
| Lenovo ThinkPad T530 24296HG               | 1         | 0.61%   |
| Lenovo ThinkPad T520 4243K86               | 1         | 0.61%   |
| Lenovo ThinkPad L460 20FVS3JK00            | 1         | 0.61%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE       | 1         | 0.61%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1         | 0.61%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.61%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4       | 1         | 0.61%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 1         | 0.61%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 1         | 0.61%   |
| Lenovo IdeaPad 3 15ABA7 82RN               | 1         | 0.61%   |
| Lenovo IdeaPad 3 14ARE05 81W3              | 1         | 0.61%   |
| Lenovo IdeaCentre AIO 520-27ICB F0DE00EJRI | 1         | 0.61%   |
| Lenovo G70-80 80FF                         | 1         | 0.61%   |
| Intel NUC8i5BEH                            | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 12        | 7.27%   |
| Dell OptiPlex                 | 9         | 5.45%   |
| HP Compaq                     | 8         | 4.85%   |
| Dell Inspiron                 | 8         | 4.85%   |
| Lenovo IdeaPad                | 5         | 3.03%   |
| Dell Latitude                 | 5         | 3.03%   |
| Acer Aspire                   | 5         | 3.03%   |
| ASUS ROG                      | 4         | 2.42%   |
| ASUS All                      | 4         | 2.42%   |
| HP Pavilion                   | 3         | 1.82%   |
| HP EliteBook                  | 3         | 1.82%   |
| Fujitsu ESPRIMO               | 3         | 1.82%   |
| Dell Precision                | 3         | 1.82%   |
| Toshiba Satellite             | 2         | 1.21%   |
| Lenovo G50-45                 | 2         | 1.21%   |
| ASUS TUF                      | 2         | 1.21%   |
| ASUS PRIME                    | 2         | 1.21%   |
| ASUS P8P67                    | 2         | 1.21%   |
| ASUS M4A785-M                 | 2         | 1.21%   |
| System76 Thelio               | 1         | 0.61%   |
| Sony VGN-NS31M                | 1         | 0.61%   |
| Samsung 305V4A                | 1         | 0.61%   |
| Razer Blade                   | 1         | 0.61%   |
| RPi Raspberry                 | 1         | 0.61%   |
| Pegatron FL368AA-UUZ          | 1         | 0.61%   |
| Packard Bell IMEDIA           | 1         | 0.61%   |
| MSI MS-7A57                   | 1         | 0.61%   |
| MSI MS-7752                   | 1         | 0.61%   |
| Medion MD34207                | 1         | 0.61%   |
| Lenovo ThinkCentre            | 1         | 0.61%   |
| Lenovo Legion                 | 1         | 0.61%   |
| Lenovo IdeaCentre             | 1         | 0.61%   |
| Lenovo G70-80                 | 1         | 0.61%   |
| Intel NUC8i5BEH               | 1         | 0.61%   |
| Intel NUC7i5DNKE              | 1         | 0.61%   |
| Intel DQ965GF                 | 1         | 0.61%   |
| Intel Client Systems LAPBC510 | 1         | 0.61%   |
| IBM 8188PPV                   | 1         | 0.61%   |
| HUAWEI KLVL-WXXW              | 1         | 0.61%   |
| HUAWEI HLYL-WXX9              | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 18        | 10.91%  |
| 2012 | 16        | 9.7%    |
| 2019 | 15        | 9.09%   |
| 2014 | 13        | 7.88%   |
| 2018 | 12        | 7.27%   |
| 2011 | 12        | 7.27%   |
| 2021 | 10        | 6.06%   |
| 2016 | 10        | 6.06%   |
| 2013 | 10        | 6.06%   |
| 2017 | 9         | 5.45%   |
| 2015 | 9         | 5.45%   |
| 2010 | 7         | 4.24%   |
| 2009 | 7         | 4.24%   |
| 2008 | 7         | 4.24%   |
| 2007 | 4         | 2.42%   |
| 2022 | 3         | 1.82%   |
| 2005 | 3         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 77        | 46.67%  |
| Notebook       | 74        | 44.85%  |
| All in one     | 6         | 3.64%   |
| Mini pc        | 5         | 3.03%   |
| Convertible    | 2         | 1.21%   |
| System on chip | 1         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 156       | 94.55%  |
| Enabled  | 9         | 5.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 163       | 98.79%  |
| Yes  | 2         | 1.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 29.52%  |
| 16.01-24.0  | 34        | 20.48%  |
| 8.01-16.0   | 32        | 19.28%  |
| 32.01-64.0  | 18        | 10.84%  |
| 3.01-4.0    | 15        | 9.04%   |
| 64.01-256.0 | 8         | 4.82%   |
| 1.01-2.0    | 4         | 2.41%   |
| 24.01-32.0  | 3         | 1.81%   |
| 2.01-3.0    | 3         | 1.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 57        | 33.73%  |
| 2.01-3.0   | 40        | 23.67%  |
| 4.01-8.0   | 31        | 18.34%  |
| 3.01-4.0   | 24        | 14.2%   |
| 8.01-16.0  | 12        | 7.1%    |
| 0.51-1.0   | 4         | 2.37%   |
| 24.01-32.0 | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 90        | 54.22%  |
| 2      | 55        | 33.13%  |
| 3      | 7         | 4.22%   |
| 4      | 5         | 3.01%   |
| 7      | 2         | 1.2%    |
| 5      | 2         | 1.2%    |
| 0      | 2         | 1.2%    |
| 16     | 1         | 0.6%    |
| 11     | 1         | 0.6%    |
| 10     | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 53.61%  |
| Yes       | 77        | 46.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 89.7%   |
| No        | 17        | 10.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 72.73%  |
| No        | 45        | 27.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 54.55%  |
| No        | 75        | 45.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 40        | 24.24%  |
| France                 | 22        | 13.33%  |
| Germany                | 19        | 11.52%  |
| Italy                  | 10        | 6.06%   |
| Brazil                 | 7         | 4.24%   |
| Russia                 | 6         | 3.64%   |
| UK                     | 5         | 3.03%   |
| Spain                  | 5         | 3.03%   |
| Canada                 | 5         | 3.03%   |
| Austria                | 4         | 2.42%   |
| Australia              | 4         | 2.42%   |
| Sweden                 | 3         | 1.82%   |
| Netherlands            | 3         | 1.82%   |
| Belgium                | 3         | 1.82%   |
| Taiwan                 | 2         | 1.21%   |
| Switzerland            | 2         | 1.21%   |
| Romania                | 2         | 1.21%   |
| Norway                 | 2         | 1.21%   |
| Mexico                 | 2         | 1.21%   |
| Ivory Coast            | 2         | 1.21%   |
| Costa Rica             | 2         | 1.21%   |
| Yemen                  | 1         | 0.61%   |
| Turkey                 | 1         | 0.61%   |
| Slovakia               | 1         | 0.61%   |
| Poland                 | 1         | 0.61%   |
| Peru                   | 1         | 0.61%   |
| Nigeria                | 1         | 0.61%   |
| Nicaragua              | 1         | 0.61%   |
| Kenya                  | 1         | 0.61%   |
| Indonesia              | 1         | 0.61%   |
| Hungary                | 1         | 0.61%   |
| Guatemala              | 1         | 0.61%   |
| Finland                | 1         | 0.61%   |
| Bulgaria               | 1         | 0.61%   |
| Bosnia and Herzegovina | 1         | 0.61%   |
| Argentina              | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Stockholm     | 3         | 1.8%    |
| Paris         | 3         | 1.8%    |
| Houston       | 3         | 1.8%    |
| Vienna        | 2         | 1.2%    |
| Turin         | 2         | 1.2%    |
| Stuttgart     | 2         | 1.2%    |
| Moscow        | 2         | 1.2%    |
| Montreal      | 2         | 1.2%    |
| Mississauga   | 2         | 1.2%    |
| Madrid        | 2         | 1.2%    |
| Hamburg       | 2         | 1.2%    |
| Groningen     | 2         | 1.2%    |
| Denver        | 2         | 1.2%    |
| Bucharest     | 2         | 1.2%    |
| Béziers      | 2         | 1.2%    |
| Abidjan       | 2         | 1.2%    |
| Zanesville    | 1         | 0.6%    |
| Yonkers       | 1         | 0.6%    |
| Yekaterinburg | 1         | 0.6%    |
| Wroclaw       | 1         | 0.6%    |
| Woonsocket    | 1         | 0.6%    |
| Woodland Park | 1         | 0.6%    |
| Wildenfels    | 1         | 0.6%    |
| West Mifflin  | 1         | 0.6%    |
| Warner Robins | 1         | 0.6%    |
| Villefontaine | 1         | 0.6%    |
| Velleron      | 1         | 0.6%    |
| Tilburg       | 1         | 0.6%    |
| Taylor        | 1         | 0.6%    |
| Tarragona     | 1         | 0.6%    |
| Taipei        | 1         | 0.6%    |
| Taichung      | 1         | 0.6%    |
| Sunderland    | 1         | 0.6%    |
| Stabekk       | 1         | 0.6%    |
| St Petersburg | 1         | 0.6%    |
| Sofia         | 1         | 0.6%    |
| Sleman        | 1         | 0.6%    |
| Sherman Oaks  | 1         | 0.6%    |
| Seropedica    | 1         | 0.6%    |
| Sarajevo      | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 43        | 54     | 17.06%  |
| WDC                   | 40        | 48     | 15.87%  |
| Seagate               | 29        | 51     | 11.51%  |
| Toshiba               | 17        | 18     | 6.75%   |
| SanDisk               | 16        | 17     | 6.35%   |
| Kingston              | 8         | 8      | 3.17%   |
| Intel                 | 8         | 11     | 3.17%   |
| Hitachi               | 8         | 9      | 3.17%   |
| Crucial               | 8         | 8      | 3.17%   |
| Unknown               | 7         | 7      | 2.78%   |
| HGST                  | 5         | 6      | 1.98%   |
| SK hynix              | 4         | 5      | 1.59%   |
| Micron Technology     | 4         | 4      | 1.59%   |
| Team                  | 3         | 3      | 1.19%   |
| SPCC                  | 3         | 3      | 1.19%   |
| Phison                | 3         | 3      | 1.19%   |
| Intenso               | 3         | 3      | 1.19%   |
| China                 | 3         | 3      | 1.19%   |
| ASMT                  | 3         | 3      | 1.19%   |
| A-DATA Technology     | 3         | 4      | 1.19%   |
| JMicron Technology    | 2         | 2      | 0.79%   |
| Fujitsu               | 2         | 2      | 0.79%   |
| Corsair               | 2         | 3      | 0.79%   |
| BHT                   | 2         | 2      | 0.79%   |
| Apple                 | 2         | 3      | 0.79%   |
| Wibtek                | 1         | 1      | 0.4%    |
| USB 3.0               | 1         | 2      | 0.4%    |
| Union Memory          | 1         | 1      | 0.4%    |
| UMIS                  | 1         | 1      | 0.4%    |
| TO Exter              | 1         | 1      | 0.4%    |
| SCY                   | 1         | 1      | 0.4%    |
| Reeinno               | 1         | 1      | 0.4%    |
| Realtek Semiconductor | 1         | 1      | 0.4%    |
| Realtek               | 1         | 1      | 0.4%    |
| PNY                   | 1         | 1      | 0.4%    |
| Phison Electronics    | 1         | 1      | 0.4%    |
| Patriot               | 1         | 1      | 0.4%    |
| OCZ                   | 1         | 1      | 0.4%    |
| NGFF                  | 1         | 1      | 0.4%    |
| Maxtor                | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 1.42%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.42%   |
| Seagate ST2000DM001-1ER164 2TB            | 4         | 1.42%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 1.42%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 1.07%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 1.07%   |
| Crucial CT500MX500SSD1 500GB              | 3         | 1.07%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 2         | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.71%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.71%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.71%   |
| Toshiba HDWD130 3TB                       | 2         | 0.71%   |
| Toshiba DT01ACA050 500GB                  | 2         | 0.71%   |
| Team T253X6001T 1TB SSD                   | 2         | 0.71%   |
| SPCC Solid State Disk 256GB               | 2         | 0.71%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.71%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB            | 2         | 0.71%   |
| Seagate Expansion Desk 4TB                | 2         | 0.71%   |
| Seagate Expansion 1TB                     | 2         | 0.71%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.71%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.71%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.71%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.71%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.71%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.71%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.71%   |
| Samsung HD753LJ 752GB                     | 2         | 0.71%   |
| JMicron Generic 320GB                     | 2         | 0.71%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 0.71%   |
| China SSD 1TB                             | 2         | 0.71%   |
| Wibtek W800S 512GB SSD                    | 1         | 0.36%   |
| WDC WDS512G1X0C-00ENX0 512GB              | 1         | 0.36%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.36%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1         | 0.36%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.36%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.36%   |
| WDC WD5000BPKT-60PK4T0 500GB              | 1         | 0.36%   |
| WDC WD5000BEKT-60KA9T0 500GB              | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 39     | 30.69%  |
| Seagate             | 28        | 49     | 27.72%  |
| Toshiba             | 16        | 17     | 15.84%  |
| Hitachi             | 8         | 9      | 7.92%   |
| Samsung Electronics | 5         | 5      | 4.95%   |
| HGST                | 5         | 6      | 4.95%   |
| Fujitsu             | 2         | 2      | 1.98%   |
| USB 3.0             | 1         | 2      | 0.99%   |
| Unknown             | 1         | 1      | 0.99%   |
| Maxtor              | 1         | 1      | 0.99%   |
| Inateck             | 1         | 1      | 0.99%   |
| ASMT                | 1         | 1      | 0.99%   |
| Apple               | 1         | 1      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 30     | 26.6%   |
| SanDisk             | 14        | 15     | 14.89%  |
| Crucial             | 8         | 8      | 8.51%   |
| Kingston            | 7         | 7      | 7.45%   |
| WDC                 | 3         | 3      | 3.19%   |
| SPCC                | 3         | 3      | 3.19%   |
| Micron Technology   | 3         | 3      | 3.19%   |
| Intenso             | 3         | 3      | 3.19%   |
| China               | 3         | 3      | 3.19%   |
| Team                | 2         | 2      | 2.13%   |
| JMicron Technology  | 2         | 2      | 2.13%   |
| BHT                 | 2         | 2      | 2.13%   |
| ASMT                | 2         | 2      | 2.13%   |
| A-DATA Technology   | 2         | 2      | 2.13%   |
| Wibtek              | 1         | 1      | 1.06%   |
| Toshiba             | 1         | 1      | 1.06%   |
| TO Exter            | 1         | 1      | 1.06%   |
| SCY                 | 1         | 1      | 1.06%   |
| Reeinno             | 1         | 1      | 1.06%   |
| PNY                 | 1         | 1      | 1.06%   |
| Patriot             | 1         | 1      | 1.06%   |
| OCZ                 | 1         | 1      | 1.06%   |
| NGFF                | 1         | 1      | 1.06%   |
| Leven               | 1         | 1      | 1.06%   |
| KingSpec            | 1         | 1      | 1.06%   |
| Intel               | 1         | 1      | 1.06%   |
| Integral            | 1         | 1      | 1.06%   |
| Dogfish             | 1         | 1      | 1.06%   |
| Corsair             | 1         | 1      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 81        | 134    | 38.03%  |
| SSD     | 77        | 100    | 36.15%  |
| NVMe    | 45        | 60     | 21.13%  |
| MMC     | 8         | 9      | 3.76%   |
| Unknown | 2         | 2      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 216    | 65.13%  |
| NVMe | 45        | 59     | 23.08%  |
| SAS  | 15        | 21     | 7.69%   |
| MMC  | 8         | 9      | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 95        | 119    | 53.67%  |
| 0.51-1.0   | 51        | 61     | 28.81%  |
| 1.01-2.0   | 15        | 18     | 8.47%   |
| 3.01-4.0   | 7         | 9      | 3.95%   |
| 4.01-10.0  | 6         | 23     | 3.39%   |
| 2.01-3.0   | 3         | 4      | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 27.98%  |
| 251-500        | 30        | 17.86%  |
| 501-1000       | 29        | 17.26%  |
| 1001-2000      | 21        | 12.5%   |
| More than 3000 | 13        | 7.74%   |
| 51-100         | 11        | 6.55%   |
| 21-50          | 9         | 5.36%   |
| 1-20           | 6         | 3.57%   |
| 2001-3000      | 2         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 55        | 32.54%  |
| 21-50          | 31        | 18.34%  |
| 101-250        | 23        | 13.61%  |
| 251-500        | 17        | 10.06%  |
| 51-100         | 13        | 7.69%   |
| 501-1000       | 12        | 7.1%    |
| More than 3000 | 7         | 4.14%   |
| 1001-2000      | 7         | 4.14%   |
| 2001-3000      | 4         | 2.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 8.33%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 3      | 5.56%   |
| Samsung Electronics HD753LJ 752GB                   | 2         | 2      | 5.56%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2.78%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1      | 2.78%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 2.78%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.78%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 2.78%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 2.78%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 2.78%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 2.78%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2.78%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 2.78%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 2.78%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 2.78%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 2.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.78%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 2.78%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 2.78%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 2.78%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 2.78%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 2.78%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.78%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 2.78%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 2.78%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.78%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 2.78%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 2.78%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 2.78%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 27.78%  |
| WDC                 | 8         | 8      | 22.22%  |
| Samsung Electronics | 7         | 8      | 19.44%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Hitachi             | 2         | 2      | 5.56%   |
| A-DATA Technology   | 2         | 2      | 5.56%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| KingSpec            | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 35.71%  |
| WDC                 | 8         | 8      | 28.57%  |
| Samsung Electronics | 4         | 4      | 14.29%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Hitachi             | 2         | 2      | 7.14%   |
| HGST                | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 33     | 77.14%  |
| SSD  | 7         | 8      | 20%     |
| NVMe | 1         | 1      | 2.86%   |

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
| Works    | 138       | 232    | 70.41%  |
| Malfunc  | 35        | 42     | 17.86%  |
| Detected | 21        | 29     | 10.71%  |
| Failed   | 2         | 2      | 1.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 114       | 53.27%  |
| AMD                         | 37        | 17.29%  |
| Samsung Electronics         | 17        | 7.94%   |
| SanDisk                     | 7         | 3.27%   |
| Phison Electronics          | 6         | 2.8%    |
| Marvell Technology Group    | 5         | 2.34%   |
| ASMedia Technology          | 5         | 2.34%   |
| SK hynix                    | 4         | 1.87%   |
| Nvidia                      | 3         | 1.4%    |
| Union Memory (Shenzhen)     | 2         | 0.93%   |
| JMicron Technology          | 2         | 0.93%   |
| VIA Technologies            | 1         | 0.47%   |
| Silicon Image               | 1         | 0.47%   |
| Seagate Technology          | 1         | 0.47%   |
| Realtek Semiconductor       | 1         | 0.47%   |
| Micron Technology           | 1         | 0.47%   |
| MAXIO Technology (Hangzhou) | 1         | 0.47%   |
| LSI Logic / Symbios Logic   | 1         | 0.47%   |
| KIOXIA                      | 1         | 0.47%   |
| Kingston Technology Company | 1         | 0.47%   |
| Apple                       | 1         | 0.47%   |
| ADATA Technology            | 1         | 0.47%   |
| Adaptec                     | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 9.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 5.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 3.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 1.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.98%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.59%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.59%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.19%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.19%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.19%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.79%   |
| SK hynix BC511                                                                 | 2         | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.79%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2         | 0.79%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2         | 0.79%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.79%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.79%   |
| Intel NVMe Controller                                                          | 2         | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2         | 0.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 128       | 59.26%  |
| NVMe | 46        | 21.3%   |
| IDE  | 25        | 11.57%  |
| RAID | 13        | 6.02%   |
| SAS  | 3         | 1.39%   |
| SCSI | 1         | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 120       | 72.73%  |
| AMD    | 44        | 26.67%  |
| ARM    | 1         | 0.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.82%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 1.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 1.21%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 1.21%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 1.21%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 1.21%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 1.21%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 1.21%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.21%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.21%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 1.21%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 1.21%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 1.21%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 1.21%   |
| AMD Phenom II X4 945 Processor          | 2         | 1.21%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.61%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.61%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1         | 0.61%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.61%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.61%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.61%   |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.61%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.61%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.61%   |
| Intel Pentium 4 CPU 2.80GHz             | 1         | 0.61%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1         | 0.61%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.61%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.61%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 1         | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.61%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1         | 0.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.61%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.61%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 0.61%   |
| Intel Core i7-6700T CPU @ 2.80GHz       | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 41        | 24.85%  |
| Intel Core i7          | 37        | 22.42%  |
| Intel Core i3          | 11        | 6.67%   |
| Other                  | 9         | 5.45%   |
| AMD Ryzen 5            | 8         | 4.85%   |
| AMD Ryzen 7            | 7         | 4.24%   |
| Intel Core 2 Duo       | 5         | 3.03%   |
| Intel Celeron          | 5         | 3.03%   |
| Intel Xeon             | 4         | 2.42%   |
| Intel Core i9          | 4         | 2.42%   |
| AMD Ryzen 9            | 4         | 2.42%   |
| AMD Phenom II X4       | 4         | 2.42%   |
| AMD E                  | 3         | 1.82%   |
| Intel Pentium 4        | 2         | 1.21%   |
| AMD Ryzen 3            | 2         | 1.21%   |
| AMD Athlon II X2       | 2         | 1.21%   |
| AMD A4                 | 2         | 1.21%   |
| Intel Pentium Dual     | 1         | 0.61%   |
| Intel Pentium D        | 1         | 0.61%   |
| Intel Pentium          | 1         | 0.61%   |
| Intel Genuine          | 1         | 0.61%   |
| Intel Core 2           | 1         | 0.61%   |
| AMD Ryzen Threadripper | 1         | 0.61%   |
| AMD Ryzen 3 PRO        | 1         | 0.61%   |
| AMD FX                 | 1         | 0.61%   |
| AMD E2                 | 1         | 0.61%   |
| AMD E1                 | 1         | 0.61%   |
| AMD Athlon X4          | 1         | 0.61%   |
| AMD Athlon Dual Core   | 1         | 0.61%   |
| AMD Athlon 64 X2       | 1         | 0.61%   |
| AMD A6                 | 1         | 0.61%   |
| AMD A10                | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 66        | 40%     |
| 2      | 59        | 35.76%  |
| 6      | 19        | 11.52%  |
| 8      | 9         | 5.45%   |
| 12     | 3         | 1.82%   |
| 10     | 3         | 1.82%   |
| 1      | 3         | 1.82%   |
| 16     | 2         | 1.21%   |
| 32     | 1         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 164       | 99.39%  |
| 2      | 1         | 0.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 63.03%  |
| 1      | 61        | 36.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 164       | 99.39%  |
| 32-bit         | 1         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 10.84%  |
| 0x306c3    | 14        | 8.43%   |
| 0x306a9    | 13        | 7.83%   |
| 0x206a7    | 13        | 7.83%   |
| 0x906ea    | 8         | 4.82%   |
| 0x506e3    | 5         | 3.01%   |
| 0x306d4    | 5         | 3.01%   |
| 0x806ea    | 4         | 2.41%   |
| 0x806c1    | 4         | 2.41%   |
| 0x08701021 | 4         | 2.41%   |
| 0x08600104 | 4         | 2.41%   |
| 0x906e9    | 3         | 1.81%   |
| 0x406e3    | 3         | 1.81%   |
| 0x106e5    | 3         | 1.81%   |
| 0x10676    | 3         | 1.81%   |
| 0x08108109 | 3         | 1.81%   |
| 0x010000c8 | 3         | 1.81%   |
| 0xf41      | 2         | 1.2%    |
| 0xa0655    | 2         | 1.2%    |
| 0xa0652    | 2         | 1.2%    |
| 0x906ed    | 2         | 1.2%    |
| 0x706e5    | 2         | 1.2%    |
| 0x6fd      | 2         | 1.2%    |
| 0x40651    | 2         | 1.2%    |
| 0x206d7    | 2         | 1.2%    |
| 0x0a50000d | 2         | 1.2%    |
| 0x08600106 | 2         | 1.2%    |
| 0x07030105 | 2         | 1.2%    |
| 0x010000b6 | 2         | 1.2%    |
| 0xf65      | 1         | 0.6%    |
| 0x906a3    | 1         | 0.6%    |
| 0x806e9    | 1         | 0.6%    |
| 0x706a1    | 1         | 0.6%    |
| 0x6fb      | 1         | 0.6%    |
| 0x6f6      | 1         | 0.6%    |
| 0x506ca    | 1         | 0.6%    |
| 0x506c9    | 1         | 0.6%    |
| 0x50654    | 1         | 0.6%    |
| 0x406c4    | 1         | 0.6%    |
| 0x40661    | 1         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 12.12%  |
| Haswell          | 18        | 10.91%  |
| SandyBridge      | 15        | 9.09%   |
| Zen 2            | 14        | 8.48%   |
| IvyBridge        | 14        | 8.48%   |
| Skylake          | 13        | 7.88%   |
| K10              | 6         | 3.64%   |
| Broadwell        | 6         | 3.64%   |
| Penryn           | 5         | 3.03%   |
| Zen 3            | 4         | 2.42%   |
| TigerLake        | 4         | 2.42%   |
| Nehalem          | 4         | 2.42%   |
| Core             | 4         | 2.42%   |
| CometLake        | 4         | 2.42%   |
| Zen+             | 3         | 1.82%   |
| Westmere         | 3         | 1.82%   |
| Puma             | 3         | 1.82%   |
| NetBurst         | 3         | 1.82%   |
| Excavator        | 3         | 1.82%   |
| Unknown          | 3         | 1.82%   |
| Piledriver       | 2         | 1.21%   |
| K8 Hammer        | 2         | 1.21%   |
| IceLake          | 2         | 1.21%   |
| Goldmont         | 2         | 1.21%   |
| Bobcat           | 2         | 1.21%   |
| Zen              | 1         | 0.61%   |
| Steamroller      | 1         | 0.61%   |
| Silvermont       | 1         | 0.61%   |
| K10 Llano        | 1         | 0.61%   |
| Goldmont plus    | 1         | 0.61%   |
| Alderlake Hybrid | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 86        | 44.79%  |
| Nvidia | 59        | 30.73%  |
| AMD    | 47        | 24.48%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8         | 4.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 3.57%   |
| AMD Renoir                                                                  | 7         | 3.57%   |
| Intel HD Graphics 530                                                       | 6         | 3.06%   |
| Intel HD Graphics 5500                                                      | 5         | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 2.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 2.04%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.53%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.53%   |
| Intel UHD Graphics 620                                                      | 3         | 1.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 1.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.02%   |
| Nvidia TU117M                                                               | 2         | 1.02%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.02%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 1.02%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 1.02%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 1.02%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.02%   |
| Intel HD Graphics 630                                                       | 2         | 1.02%   |
| Intel HD Graphics 500                                                       | 2         | 1.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.02%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.02%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2         | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.02%   |
| AMD Wrestler [Radeon HD 6310]                                               | 2         | 1.02%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 2         | 1.02%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2         | 1.02%   |
| AMD Lucienne                                                                | 2         | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 36.97%  |
| 1 x AMD        | 39        | 23.64%  |
| 1 x Nvidia     | 36        | 21.82%  |
| Intel + Nvidia | 18        | 10.91%  |
| AMD + Nvidia   | 4         | 2.42%   |
| Intel + AMD    | 3         | 1.82%   |
| Other          | 1         | 0.61%   |
| 2 x Nvidia     | 1         | 0.61%   |
| 2 x Intel      | 1         | 0.61%   |
| 2 x AMD        | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 135       | 81.33%  |
| Proprietary | 29        | 17.47%  |
| Unknown     | 2         | 1.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 44.58%  |
| 0.01-0.5   | 25        | 15.06%  |
| 1.01-2.0   | 21        | 12.65%  |
| 0.51-1.0   | 20        | 12.05%  |
| 3.01-4.0   | 12        | 7.23%   |
| 7.01-8.0   | 4         | 2.41%   |
| 5.01-6.0   | 4         | 2.41%   |
| 8.01-16.0  | 4         | 2.41%   |
| 2.01-3.0   | 1         | 0.6%    |
| 16.01-24.0 | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24        | 12.97%  |
| LG Display              | 18        | 9.73%   |
| AU Optronics            | 16        | 8.65%   |
| Goldstar                | 13        | 7.03%   |
| Dell                    | 11        | 5.95%   |
| BOE                     | 11        | 5.95%   |
| Philips                 | 10        | 5.41%   |
| Hewlett-Packard         | 10        | 5.41%   |
| Chimei Innolux          | 10        | 5.41%   |
| Acer                    | 10        | 5.41%   |
| Ancor Communications    | 6         | 3.24%   |
| Lenovo                  | 4         | 2.16%   |
| Apple                   | 4         | 2.16%   |
| AOC                     | 3         | 1.62%   |
| Sharp                   | 2         | 1.08%   |
| ONN                     | 2         | 1.08%   |
| Iiyama                  | 2         | 1.08%   |
| Hannspree               | 2         | 1.08%   |
| Fujitsu Siemens         | 2         | 1.08%   |
| Eizo                    | 2         | 1.08%   |
| Chi Mei Optoelectronics | 2         | 1.08%   |
| BenQ                    | 2         | 1.08%   |
| ASUSTek Computer        | 2         | 1.08%   |
| ViewSonic               | 1         | 0.54%   |
| VIE                     | 1         | 0.54%   |
| Unknown                 | 1         | 0.54%   |
| UGD                     | 1         | 0.54%   |
| TVT                     | 1         | 0.54%   |
| Targa Visionary         | 1         | 0.54%   |
| Sony                    | 1         | 0.54%   |
| Seiki                   | 1         | 0.54%   |
| Onkyo                   | 1         | 0.54%   |
| NEC Computers           | 1         | 0.54%   |
| Medion                  | 1         | 0.54%   |
| LG Philips              | 1         | 0.54%   |
| KTC                     | 1         | 0.54%   |
| DENON                   | 1         | 0.54%   |
| CPT                     | 1         | 0.54%   |
| Arnos Instruments       | 1         | 0.54%   |
| Unknown                 | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 2         | 1.03%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.03%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 2         | 1.03%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.03%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 1.03%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.03%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1         | 0.52%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1         | 0.52%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1         | 0.52%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch               | 1         | 0.52%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1         | 0.52%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1         | 0.52%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                    | 1         | 0.52%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.52%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1         | 0.52%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.52%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 1         | 0.52%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1         | 0.52%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1         | 0.52%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch   | 1         | 0.52%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.52%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.52%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 48%     |
| 1366x768 (WXGA)    | 25        | 14.29%  |
| 3840x2160 (4K)     | 16        | 9.14%   |
| 1280x1024 (SXGA)   | 10        | 5.71%   |
| 1680x1050 (WSXGA+) | 7         | 4%      |
| 1600x900 (HD+)     | 7         | 4%      |
| 1920x1200 (WUXGA)  | 6         | 3.43%   |
| 2560x1440 (QHD)    | 4         | 2.29%   |
| 1440x900 (WXGA+)   | 4         | 2.29%   |
| 1360x768           | 2         | 1.14%   |
| 1280x800 (WXGA)    | 2         | 1.14%   |
| Unknown            | 2         | 1.14%   |
| 5760x2160          | 1         | 0.57%   |
| 3280x1080          | 1         | 0.57%   |
| 2880x1800          | 1         | 0.57%   |
| 2160x1440          | 1         | 0.57%   |
| 1600x1200          | 1         | 0.57%   |
| 1400x1050          | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 44        | 23.78%  |
| 21      | 18        | 9.73%   |
| 27      | 16        | 8.65%   |
| 24      | 16        | 8.65%   |
| 23      | 15        | 8.11%   |
| 13      | 11        | 5.95%   |
| 19      | 9         | 4.86%   |
| 14      | 9         | 4.86%   |
| 17      | 8         | 4.32%   |
| 31      | 6         | 3.24%   |
| 18      | 6         | 3.24%   |
| 22      | 5         | 2.7%    |
| 12      | 5         | 2.7%    |
| 20      | 4         | 2.16%   |
| 84      | 2         | 1.08%   |
| Unknown | 2         | 1.08%   |
| 65      | 1         | 0.54%   |
| 54      | 1         | 0.54%   |
| 52      | 1         | 0.54%   |
| 50      | 1         | 0.54%   |
| 43      | 1         | 0.54%   |
| 32      | 1         | 0.54%   |
| 26      | 1         | 0.54%   |
| 16      | 1         | 0.54%   |
| 11      | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 35.36%  |
| 501-600     | 44        | 24.31%  |
| 401-500     | 36        | 19.89%  |
| 201-300     | 12        | 6.63%   |
| 601-700     | 8         | 4.42%   |
| 351-400     | 7         | 3.87%   |
| 1001-1500   | 4         | 2.21%   |
| 1501-2000   | 2         | 1.1%    |
| Unknown     | 2         | 1.1%    |
| 701-800     | 1         | 0.55%   |
| 901-1000    | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 128       | 76.19%  |
| 16/10   | 25        | 14.88%  |
| 5/4     | 9         | 5.36%   |
| 4/3     | 2         | 1.19%   |
| 3/2     | 2         | 1.19%   |
| Unknown | 2         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 24.18%  |
| 201-250        | 42        | 23.08%  |
| 301-350        | 17        | 9.34%   |
| 81-90          | 15        | 8.24%   |
| 151-200        | 15        | 8.24%   |
| 141-150        | 12        | 6.59%   |
| 351-500        | 7         | 3.85%   |
| 251-300        | 7         | 3.85%   |
| More than 1000 | 6         | 3.3%    |
| 71-80          | 5         | 2.75%   |
| 61-70          | 5         | 2.75%   |
| Unknown        | 2         | 1.1%    |
| 51-60          | 1         | 0.55%   |
| 131-140        | 1         | 0.55%   |
| 121-130        | 1         | 0.55%   |
| 111-120        | 1         | 0.55%   |
| 501-1000       | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 73        | 41.48%  |
| 101-120       | 43        | 24.43%  |
| 121-160       | 41        | 23.3%   |
| 161-240       | 13        | 7.39%   |
| More than 240 | 2         | 1.14%   |
| 1-50          | 2         | 1.14%   |
| Unknown       | 2         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 129       | 77.25%  |
| 2     | 36        | 21.56%  |
| 3     | 1         | 0.6%    |
| 0     | 1         | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 92        | 36.22%  |
| Realtek Semiconductor             | 87        | 34.25%  |
| Qualcomm Atheros                  | 27        | 10.63%  |
| Broadcom                          | 14        | 5.51%   |
| ASIX Electronics                  | 4         | 1.57%   |
| TP-Link                           | 3         | 1.18%   |
| Nvidia                            | 3         | 1.18%   |
| MediaTek                          | 3         | 1.18%   |
| Broadcom Limited                  | 3         | 1.18%   |
| Ralink                            | 2         | 0.79%   |
| Ericsson Business Mobile Networks | 2         | 0.79%   |
| Aquantia                          | 2         | 0.79%   |
| ZyDAS                             | 1         | 0.39%   |
| Wacom                             | 1         | 0.39%   |
| Ralink Technology                 | 1         | 0.39%   |
| Qualcomm Atheros Communications   | 1         | 0.39%   |
| NetGear                           | 1         | 0.39%   |
| Motorola PCS                      | 1         | 0.39%   |
| Microsoft                         | 1         | 0.39%   |
| Marvell Technology Group          | 1         | 0.39%   |
| InterBiometrics                   | 1         | 0.39%   |
| Input Club                        | 1         | 0.39%   |
| Huawei Technologies               | 1         | 0.39%   |
| DisplayLink                       | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 62        | 21.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17        | 5.82%   |
| Intel Wireless 7265                                                           | 10        | 3.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 2.05%   |
| Intel I211 Gigabit Network Connection                                         | 6         | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6         | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 1.71%   |
| Intel Wireless-AC 9260                                                        | 5         | 1.71%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.71%   |
| Realtek 802.11ac NIC                                                          | 4         | 1.37%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 1.03%   |
| Intel Wireless 8260                                                           | 3         | 1.03%   |
| Intel Wireless 7260                                                           | 3         | 1.03%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.03%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.68%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 0.68%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 0.68%   |
| Intel WiFi Link 5100                                                          | 2         | 0.68%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.68%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.68%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.68%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                      | 2         | 0.68%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module            | 2         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 0.68%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 48.78%  |
| Qualcomm Atheros                | 21        | 17.07%  |
| Realtek Semiconductor           | 20        | 16.26%  |
| Broadcom                        | 8         | 6.5%    |
| TP-Link                         | 3         | 2.44%   |
| Ralink                          | 2         | 1.63%   |
| MediaTek                        | 2         | 1.63%   |
| ZyDAS                           | 1         | 0.81%   |
| Wacom                           | 1         | 0.81%   |
| Ralink Technology               | 1         | 0.81%   |
| Qualcomm Atheros Communications | 1         | 0.81%   |
| NetGear                         | 1         | 0.81%   |
| Microsoft                       | 1         | 0.81%   |
| Broadcom Limited                | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 10        | 8.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 4.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6         | 4.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 4.03%   |
| Intel Wireless-AC 9260                                                        | 5         | 4.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 4.03%   |
| Realtek 802.11ac NIC                                                          | 4         | 3.23%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 3.23%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 2.42%   |
| Intel Wireless 8260                                                           | 3         | 2.42%   |
| Intel Wireless 7260                                                           | 3         | 2.42%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 2.42%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 2.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.61%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.61%   |
| Intel WiFi Link 5100                                                          | 2         | 1.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 1.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.61%   |
| ZyDAS ZD1211B 802.11g                                                         | 1         | 0.81%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1         | 0.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.81%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.81%   |
| TP-Link 802.11ac NIC                                                          | 1         | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.81%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.81%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1         | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.81%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]              | 1         | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 44.72%  |
| Intel                    | 59        | 36.65%  |
| Broadcom                 | 9         | 5.59%   |
| Qualcomm Atheros         | 7         | 4.35%   |
| ASIX Electronics         | 4         | 2.48%   |
| Nvidia                   | 3         | 1.86%   |
| Broadcom Limited         | 2         | 1.24%   |
| Aquantia                 | 2         | 1.24%   |
| MediaTek                 | 1         | 0.62%   |
| Marvell Technology Group | 1         | 0.62%   |
| DisplayLink              | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 38.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 10.49%  |
| Intel I211 Gigabit Network Connection                             | 6         | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.09%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.23%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.23%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.23%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.23%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.23%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.62%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.62%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.62%   |
| MediaTek TECNO SPARK 9T                                           | 1         | 0.62%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.62%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.62%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 54.01%  |
| WiFi     | 120       | 43.8%   |
| Modem    | 5         | 1.82%   |
| Unknown  | 1         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 90        | 50.85%  |
| Ethernet | 87        | 49.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 92        | 55.76%  |
| 1     | 68        | 41.21%  |
| 3     | 3         | 1.82%   |
| 0     | 2         | 1.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 130       | 78.31%  |
| Yes  | 36        | 21.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 49.45%  |
| Qualcomm Atheros Communications | 8         | 8.79%   |
| Realtek Semiconductor           | 7         | 7.69%   |
| Cambridge Silicon Radio         | 6         | 6.59%   |
| Broadcom                        | 5         | 5.49%   |
| Apple                           | 5         | 5.49%   |
| ASUSTek Computer                | 3         | 3.3%    |
| Realtek                         | 2         | 2.2%    |
| Ralink Technology               | 2         | 2.2%    |
| Lite-On Technology              | 2         | 2.2%    |
| Hewlett-Packard                 | 2         | 2.2%    |
| MediaTek                        | 1         | 1.1%    |
| IMC Networks                    | 1         | 1.1%    |
| Foxconn International           | 1         | 1.1%    |
| Dell                            | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 23.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 7.69%   |
| Intel AX201 Bluetooth                               | 6         | 6.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 6.59%   |
| Realtek Bluetooth Radio                             | 5         | 5.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 5.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 4.4%    |
| Intel AX200 Bluetooth                               | 3         | 3.3%    |
| Realtek Bluetooth Radio                             | 2         | 2.2%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.2%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 2.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.2%    |
| Intel Bluetooth Device                              | 2         | 2.2%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 2.2%    |
| Apple Bluetooth USB Host Controller                 | 2         | 2.2%    |
| Apple Bluetooth Host Controller                     | 2         | 2.2%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.1%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.1%    |
| Ralink CSR BS8510                                   | 1         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.1%    |
| MediaTek Wireless_Device                            | 1         | 1.1%    |
| Intel AX210 Bluetooth                               | 1         | 1.1%    |
| IMC Networks Bluetooth Radio                        | 1         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.1%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.1%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.1%    |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 1.1%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.1%    |
| ASUS BCM20702A0                                     | 1         | 1.1%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 115       | 42.44%  |
| AMD                                  | 51        | 18.82%  |
| Nvidia                               | 48        | 17.71%  |
| Texas Instruments                    | 5         | 1.85%   |
| C-Media Electronics                  | 5         | 1.85%   |
| Yamaha                               | 4         | 1.48%   |
| Logitech                             | 3         | 1.11%   |
| JMTek                                | 3         | 1.11%   |
| QinHeng Electronics                  | 2         | 0.74%   |
| PreSonus Audio Electronics           | 2         | 0.74%   |
| Mackie Designs                       | 2         | 0.74%   |
| M-Audio                              | 2         | 0.74%   |
| Generalplus Technology               | 2         | 0.74%   |
| Focusrite-Novation                   | 2         | 0.74%   |
| ZOOM                                 | 1         | 0.37%   |
| Yealink Network Technology           | 1         | 0.37%   |
| Xilinx                               | 1         | 0.37%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.37%   |
| Textech International                | 1         | 0.37%   |
| Tenx Technology                      | 1         | 0.37%   |
| TEAC                                 | 1         | 0.37%   |
| Studiologic                          | 1         | 0.37%   |
| SteelSeries ApS                      | 1         | 0.37%   |
| Samson Technologies                  | 1         | 0.37%   |
| Plantronics                          | 1         | 0.37%   |
| MIDITECH                             | 1         | 0.37%   |
| Medeli Electronics                   | 1         | 0.37%   |
| Mark of the Unicorn                  | 1         | 0.37%   |
| KTMicro                              | 1         | 0.37%   |
| Harman                               | 1         | 0.37%   |
| Ensoniq                              | 1         | 0.37%   |
| Creative Technology                  | 1         | 0.37%   |
| BR23                                 | 1         | 0.37%   |
| Behringer.......                     | 1         | 0.37%   |
| BEHRINGER International              | 1         | 0.37%   |
| ASUSTek Computer                     | 1         | 0.37%   |
| Apple                                | 1         | 0.37%   |
| Alesis                               | 1         | 0.37%   |
| AKAI Professional M.I.               | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15        | 4.69%   |
| AMD Family 17h/19h HD Audio Controller                                            | 15        | 4.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 13        | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 12        | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                        | 10        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 10        | 3.13%   |
| Intel Sunrise Point-LP HD Audio                                                   | 8         | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7         | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 2.19%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7         | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7         | 2.19%   |
| AMD FCH Azalia Controller                                                         | 7         | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.88%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6         | 1.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 1.25%   |
| Intel 200 Series PCH HD Audio                                                     | 4         | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                          | 4         | 1.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 1.25%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.94%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3         | 0.94%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3         | 0.94%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                         | 3         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3         | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 0.94%   |
| QinHeng Electronics CH345 MIDI adapter                                            | 2         | 0.63%   |
| PreSonus Audio Electronics Studio 24c                                             | 2         | 0.63%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2         | 0.63%   |
| Nvidia High Definition Audio Controller                                           | 2         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2         | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 21.78%  |
| SK hynix            | 43        | 21.29%  |
| Kingston            | 24        | 11.88%  |
| Micron Technology   | 18        | 8.91%   |
| Unknown             | 14        | 6.93%   |
| Crucial             | 12        | 5.94%   |
| Corsair             | 11        | 5.45%   |
| G.Skill             | 8         | 3.96%   |
| Ramaxel Technology  | 4         | 1.98%   |
| Patriot             | 4         | 1.98%   |
| Nanya Technology    | 3         | 1.49%   |
| Timetec             | 2         | 0.99%   |
| Wodposit            | 1         | 0.5%    |
| Unifosa             | 1         | 0.5%    |
| Transcend           | 1         | 0.5%    |
| Smart               | 1         | 0.5%    |
| S                   | 1         | 0.5%    |
| PNY                 | 1         | 0.5%    |
| OCZ                 | 1         | 0.5%    |
| M                   | 1         | 0.5%    |
| HBS                 | 1         | 0.5%    |
| Goldkey             | 1         | 0.5%    |
| Elpida              | 1         | 0.5%    |
| Aeneon              | 1         | 0.5%    |
| A-DATA Technology   | 1         | 0.5%    |
| 0194808980CE        | 1         | 0.5%    |
| Unknown             | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s  | 3         | 1.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 1.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3         | 1.33%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s    | 3         | 1.33%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 2         | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2         | 0.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 2         | 0.89%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s  | 2         | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 2         | 0.89%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s             | 2         | 0.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s   | 2         | 0.89%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 0.89%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s  | 2         | 0.89%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2         | 0.89%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s     | 2         | 0.89%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 2         | 0.89%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s   | 2         | 0.89%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s | 2         | 0.89%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 2         | 0.89%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2400MT/s  | 1         | 0.44%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s          | 1         | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s               | 1         | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR                       | 1         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                | 1         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s        | 1         | 0.44%   |
| Unknown RAM Module 256MB DIMM DDR                       | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s           | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2                   | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                 | 1         | 0.44%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s              | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1         | 0.44%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s             | 1         | 0.44%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s       | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 79        | 46.47%  |
| DDR4    | 61        | 35.88%  |
| DDR2    | 12        | 7.06%   |
| SDRAM   | 5         | 2.94%   |
| Unknown | 4         | 2.35%   |
| LPDDR4  | 3         | 1.76%   |
| DDR     | 3         | 1.76%   |
| LPDDR3  | 2         | 1.18%   |
| LPDDR5  | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 49.4%   |
| DIMM         | 71        | 42.26%  |
| Row Of Chips | 10        | 5.95%   |
| RIMM         | 1         | 0.6%    |
| FB-DIMM      | 1         | 0.6%    |
| Chip         | 1         | 0.6%    |
| Unknown      | 1         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 67        | 34.9%   |
| 8192  | 57        | 29.69%  |
| 2048  | 24        | 12.5%   |
| 16384 | 21        | 10.94%  |
| 1024  | 11        | 5.73%   |
| 32768 | 9         | 4.69%   |
| 512   | 2         | 1.04%   |
| 256   | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 58        | 31.35%  |
| 3200    | 16        | 8.65%   |
| 2667    | 15        | 8.11%   |
| 1333    | 13        | 7.03%   |
| 2400    | 10        | 5.41%   |
| 2133    | 9         | 4.86%   |
| 1334    | 8         | 4.32%   |
| 667     | 8         | 4.32%   |
| 3600    | 5         | 2.7%    |
| 1866    | 4         | 2.16%   |
| 1800    | 4         | 2.16%   |
| 1066    | 4         | 2.16%   |
| 800     | 4         | 2.16%   |
| 4267    | 3         | 1.62%   |
| 3266    | 3         | 1.62%   |
| Unknown | 3         | 1.62%   |
| 4199    | 2         | 1.08%   |
| 2933    | 2         | 1.08%   |
| 1867    | 2         | 1.08%   |
| 533     | 2         | 1.08%   |
| 6400    | 1         | 0.54%   |
| 3500    | 1         | 0.54%   |
| 3466    | 1         | 0.54%   |
| 3000    | 1         | 0.54%   |
| 2934    | 1         | 0.54%   |
| 2800    | 1         | 0.54%   |
| 2666    | 1         | 0.54%   |
| 2472    | 1         | 0.54%   |
| 1639    | 1         | 0.54%   |
| 1067    | 1         | 0.54%   |

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
| Chicony Electronics                    | 18        | 19.35%  |
| IMC Networks                           | 8         | 8.6%    |
| Microdia                               | 7         | 7.53%   |
| Logitech                               | 7         | 7.53%   |
| Sunplus Innovation Technology          | 6         | 6.45%   |
| Realtek Semiconductor                  | 6         | 6.45%   |
| Syntek                                 | 5         | 5.38%   |
| Suyin                                  | 4         | 4.3%    |
| Quanta                                 | 3         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.23%   |
| Apple                                  | 3         | 3.23%   |
| Samsung Electronics                    | 2         | 2.15%   |
| Philips (or NXP)                       | 2         | 2.15%   |
| Microsoft                              | 2         | 2.15%   |
| Lite-On Technology                     | 2         | 2.15%   |
| Bison Electronics                      | 2         | 2.15%   |
| Xiongmai                               | 1         | 1.08%   |
| ViewSonic                              | 1         | 1.08%   |
| ViewQuest Technologies                 | 1         | 1.08%   |
| Sweex                                  | 1         | 1.08%   |
| Sunplus IT                             | 1         | 1.08%   |
| Silicon Motion                         | 1         | 1.08%   |
| Ricoh                                  | 1         | 1.08%   |
| MacroSilicon                           | 1         | 1.08%   |
| Intel                                  | 1         | 1.08%   |
| Importek                               | 1         | 1.08%   |
| HRY                                    | 1         | 1.08%   |
| Dynex                                  | 1         | 1.08%   |
| Acer                                   | 1         | 1.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Syntek Integrated Camera                   | 5         | 5.32%   |
| IMC Networks Integrated Camera             | 4         | 4.26%   |
| Chicony Integrated Camera                  | 4         | 4.26%   |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 3.19%   |
| Chicony Integrated Camera [ThinkPad]       | 3         | 3.19%   |
| Suyin Asus Integrated Webcam               | 2         | 2.13%   |
| Sunplus Integrated_Webcam_HD               | 2         | 2.13%   |
| Sunplus HD WebCam                          | 2         | 2.13%   |
| Samsung Galaxy series, misc. (MTP mode)    | 2         | 2.13%   |
| Realtek Lenovo EasyCamera                  | 2         | 2.13%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.13%   |
| Logitech Webcam C270                       | 2         | 2.13%   |
| Chicony HP HD Camera                       | 2         | 2.13%   |
| Chicony HD Webcam                          | 2         | 2.13%   |
| Xiongmai web camera                        | 1         | 1.06%   |
| ViewSonic PC Camera                        | 1         | 1.06%   |
| ViewQuest Ability GABB Webcam              | 1         | 1.06%   |
| Sweex WC060 Series HD Webcam               | 1         | 1.06%   |
| Suyin HP Webcam                            | 1         | 1.06%   |
| Suyin HP TrueVision HD Integrated Webcam   | 1         | 1.06%   |
| Sunplus IT AUKEY PC-LM1 USB Camera         | 1         | 1.06%   |
| Sunplus HD 720P webcam                     | 1         | 1.06%   |
| Sunplus Dell HD Webcam                     | 1         | 1.06%   |
| Silicon Motion WebCam SCB-1100N            | 1         | 1.06%   |
| Ricoh Sony Vaio Integrated Webcam          | 1         | 1.06%   |
| Realtek VGA WebCam                         | 1         | 1.06%   |
| Realtek USB Camera                         | 1         | 1.06%   |
| Realtek Integrated_Webcam_HD               | 1         | 1.06%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.06%   |
| Quanta ov9734_techfront_camera             | 1         | 1.06%   |
| Quanta HP Webcam                           | 1         | 1.06%   |
| Quanta HP TrueVision HD Camera             | 1         | 1.06%   |
| Philips (or NXP) Webcam SPC530NC           | 1         | 1.06%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc] | 1         | 1.06%   |
| Microsoft LifeCam VX-5000                  | 1         | 1.06%   |
| Microsoft LifeCam Cinema                   | 1         | 1.06%   |
| Microdia Sonix Integrated Webcam           | 1         | 1.06%   |
| Microdia MSI Starcam Racer                 | 1         | 1.06%   |
| Microdia Integrated_Webcam_FHD             | 1         | 1.06%   |
| Microdia Integrated Webcam HD              | 1         | 1.06%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 46.67%  |
| Shenzhen Goodix Technology | 3         | 20%     |
| Synaptics                  | 2         | 13.33%  |
| LighTuning Technology      | 1         | 6.67%   |
| Focal-systems.Corp         | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 13.33%  |
| Shenzhen Goodix  Fingerprint Device                        | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 6.67%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                       | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 6.67%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Upek        | 3         | 30%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 116       | 70.3%   |
| 1     | 43        | 26.06%  |
| 2     | 5         | 3.03%   |
| 3     | 1         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 28.85%  |
| Graphics card            | 12        | 23.08%  |
| Chipcard                 | 9         | 17.31%  |
| Net/wireless             | 6         | 11.54%  |
| Camera                   | 3         | 5.77%   |
| Sound                    | 2         | 3.85%   |
| Multimedia controller    | 2         | 3.85%   |
| Unassigned class         | 1         | 1.92%   |
| Modem                    | 1         | 1.92%   |
| Communication controller | 1         | 1.92%   |

