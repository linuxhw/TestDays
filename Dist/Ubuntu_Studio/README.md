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

Total: 205

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-55              | Notebook    | [191aa2a04f](https://linux-hardware.org/?probe=191aa2a04f) | Aug 04, 2023 |
| Toshiba       | Satellite L505              | Notebook    | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [50ee937fb2](https://linux-hardware.org/?probe=50ee937fb2) | Aug 02, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [c04f6d6467](https://linux-hardware.org/?probe=c04f6d6467) | Aug 01, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [6a0b0513cd](https://linux-hardware.org/?probe=6a0b0513cd) | Jul 22, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [d3718d1a8d](https://linux-hardware.org/?probe=d3718d1a8d) | Jul 16, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [60e43d39b2](https://linux-hardware.org/?probe=60e43d39b2) | Jul 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97ebfed554](https://linux-hardware.org/?probe=97ebfed554) | Jul 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [57d511fdb3](https://linux-hardware.org/?probe=57d511fdb3) | Jun 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV03     | Notebook    | [c2a4d4d2c0](https://linux-hardware.org/?probe=c2a4d4d2c0) | Jun 17, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 81        | 45.76%  |
| Ubuntu Studio 22.04 | 47        | 26.55%  |
| Ubuntu Studio 20.10 | 13        | 7.34%   |
| Ubuntu Studio 23.04 | 9         | 5.08%   |
| Ubuntu Studio 22.10 | 9         | 5.08%   |
| Ubuntu Studio 21.10 | 7         | 3.95%   |
| Ubuntu Studio 21.04 | 5         | 2.82%   |
| Ubuntu Studio 18.04 | 3         | 1.69%   |
| Ubuntu Studio 19.10 | 2         | 1.13%   |
| Ubuntu Studio 16.04 | 1         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 175       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-56-lowlatency   | 5         | 2.78%   |
| 5.15.0-46-lowlatency   | 5         | 2.78%   |
| 5.13.0-28-lowlatency   | 5         | 2.78%   |
| 6.2.0-1003-lowlatency  | 4         | 2.22%   |
| 5.4.0-52-lowlatency    | 4         | 2.22%   |
| 5.4.0-42-lowlatency    | 4         | 2.22%   |
| 5.8.0-55-lowlatency    | 3         | 1.67%   |
| 5.8.0-50-lowlatency    | 3         | 1.67%   |
| 5.8.0-44-lowlatency    | 3         | 1.67%   |
| 5.8.0-25-lowlatency    | 3         | 1.67%   |
| 5.4.0-65-lowlatency    | 3         | 1.67%   |
| 5.4.0-26-lowlatency    | 3         | 1.67%   |
| 5.15.0-67-lowlatency   | 3         | 1.67%   |
| 5.15.0-58-lowlatency   | 3         | 1.67%   |
| 5.15.0-52-lowlatency   | 3         | 1.67%   |
| 5.15.0-50-lowlatency   | 3         | 1.67%   |
| 5.15.0-48-lowlatency   | 3         | 1.67%   |
| 5.15.0-47-lowlatency   | 3         | 1.67%   |
| 5.11.0-44-lowlatency   | 3         | 1.67%   |
| 5.11.0-34-lowlatency   | 3         | 1.67%   |
| 6.2.0-1009-lowlatency  | 2         | 1.11%   |
| 5.8.0-48-lowlatency    | 2         | 1.11%   |
| 5.8.0-29-lowlatency    | 2         | 1.11%   |
| 5.4.0-94-lowlatency    | 2         | 1.11%   |
| 5.4.0-58-lowlatency    | 2         | 1.11%   |
| 5.4.0-56-lowlatency    | 2         | 1.11%   |
| 5.4.0-45-lowlatency    | 2         | 1.11%   |
| 5.19.0-1021-lowlatency | 2         | 1.11%   |
| 5.19.0-1017-lowlatency | 2         | 1.11%   |
| 5.19.0-1015-lowlatency | 2         | 1.11%   |
| 5.19.0-1007-lowlatency | 2         | 1.11%   |
| 5.15.0-76-lowlatency   | 2         | 1.11%   |
| 5.15.0-71-lowlatency   | 2         | 1.11%   |
| 5.15.0-69-lowlatency   | 2         | 1.11%   |
| 5.15.0-53-lowlatency   | 2         | 1.11%   |
| 5.15.0-40-lowlatency   | 2         | 1.11%   |
| 5.15.0-30-lowlatency   | 2         | 1.11%   |
| 5.13.0-30-lowlatency   | 2         | 1.11%   |
| 5.11.0-27-lowlatency   | 2         | 1.11%   |
| 6.2.8-x64v3-xanmod1    | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 52        | 29.38%  |
| 5.15.0  | 45        | 25.42%  |
| 5.8.0   | 23        | 12.99%  |
| 5.11.0  | 15        | 8.47%   |
| 5.19.0  | 13        | 7.34%   |
| 5.13.0  | 10        | 5.65%   |
| 6.2.0   | 9         | 5.08%   |
| 4.15.0  | 3         | 1.69%   |
| 5.3.0   | 2         | 1.13%   |
| 6.2.8   | 1         | 0.56%   |
| 5.7.6   | 1         | 0.56%   |
| 5.17.1  | 1         | 0.56%   |
| 5.15.6  | 1         | 0.56%   |
| 4.4.0   | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 52        | 29.38%  |
| 5.15    | 46        | 25.99%  |
| 5.8     | 23        | 12.99%  |
| 5.11    | 15        | 8.47%   |
| 5.19    | 13        | 7.34%   |
| 6.2     | 10        | 5.65%   |
| 5.13    | 10        | 5.65%   |
| 4.15    | 3         | 1.69%   |
| 5.3     | 2         | 1.13%   |
| 5.7     | 1         | 0.56%   |
| 5.17    | 1         | 0.56%   |
| 4.4     | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 173       | 98.86%  |
| i686    | 1         | 0.57%   |
| aarch64 | 1         | 0.57%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 80        | 45.45%  |
| XFCE            | 78        | 44.32%  |
| GNOME           | 10        | 5.68%   |
| LXQt            | 3         | 1.7%    |
| MATE            | 2         | 1.14%   |
| KDE             | 1         | 0.57%   |
| GNOME Flashback | 1         | 0.57%   |
| Cinnamon        | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 166       | 94.32%  |
| Wayland | 6         | 3.41%   |
| Tty     | 4         | 2.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 73        | 41.71%  |
| TDM     | 49        | 28%     |
| LightDM | 40        | 22.86%  |
| GDM     | 11        | 6.29%   |
| LXDM    | 1         | 0.57%   |
| GDM3    | 1         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 72        | 40.91%  |
| fr_FR      | 22        | 12.5%   |
| de_DE      | 12        | 6.82%   |
| en_GB      | 8         | 4.55%   |
| C          | 8         | 4.55%   |
| pt_BR      | 6         | 3.41%   |
| it_IT      | 6         | 3.41%   |
| ru_RU      | 5         | 2.84%   |
| en_CA      | 4         | 2.27%   |
| es_ES      | 3         | 1.7%    |
| en_AU      | 3         | 1.7%    |
| nl_NL      | 2         | 1.14%   |
| es_AR      | 2         | 1.14%   |
| en_AG      | 2         | 1.14%   |
| Unknown    | 2         | 1.14%   |
| sv_SE      | 1         | 0.57%   |
| sk_SK      | 1         | 0.57%   |
| nl_BE      | 1         | 0.57%   |
| nb_NO      | 1         | 0.57%   |
| hu_HU      | 1         | 0.57%   |
| fr_FR.UTF8 | 1         | 0.57%   |
| fr_CH      | 1         | 0.57%   |
| fr_BE      | 1         | 0.57%   |
| es_NI      | 1         | 0.57%   |
| es_MX      | 1         | 0.57%   |
| es_GT      | 1         | 0.57%   |
| es_CR      | 1         | 0.57%   |
| en_NG      | 1         | 0.57%   |
| en_IE      | 1         | 0.57%   |
| en_DE      | 1         | 0.57%   |
| de_CH      | 1         | 0.57%   |
| de_AT      | 1         | 0.57%   |
| ca_ES      | 1         | 0.57%   |
| ca_AD      | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 101       | 57.71%  |
| BIOS | 74        | 42.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 95.43%  |
| Overlay | 6         | 3.43%   |
| Xfs     | 1         | 0.57%   |
| Ext2    | 1         | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 112       | 64%     |
| MBR  | 63        | 36%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 80.23%  |
| Yes       | 35        | 19.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 55.11%  |
| Yes       | 79        | 44.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 32        | 18.29%  |
| Dell                                 | 26        | 14.86%  |
| Lenovo                               | 25        | 14.29%  |
| Hewlett-Packard                      | 23        | 13.14%  |
| Gigabyte Technology                  | 13        | 7.43%   |
| Acer                                 | 7         | 4%      |
| Apple                                | 6         | 3.43%   |
| Fujitsu                              | 4         | 2.29%   |
| Toshiba                              | 3         | 1.71%   |
| MSI                                  | 3         | 1.71%   |
| Intel                                | 3         | 1.71%   |
| ASRock                               | 3         | 1.71%   |
| HUAWEI                               | 2         | 1.14%   |
| AZW                                  | 2         | 1.14%   |
| win element                          | 1         | 0.57%   |
| System76                             | 1         | 0.57%   |
| Sony                                 | 1         | 0.57%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.57%   |
| Samsung Electronics                  | 1         | 0.57%   |
| Razer                                | 1         | 0.57%   |
| Raspberry Pi Foundation              | 1         | 0.57%   |
| Pegatron                             | 1         | 0.57%   |
| Packard Bell                         | 1         | 0.57%   |
| Medion                               | 1         | 0.57%   |
| Intel Client Systems                 | 1         | 0.57%   |
| IBM                                  | 1         | 0.57%   |
| GPU Company                          | 1         | 0.57%   |
| Google                               | 1         | 0.57%   |
| Getac                                | 1         | 0.57%   |
| Foxconn                              | 1         | 0.57%   |
| ECS                                  | 1         | 0.57%   |
| DEPO Computers                       | 1         | 0.57%   |
| COM1                                 | 1         | 0.57%   |
| Clevo                                | 1         | 0.57%   |
| Avell High Performance               | 1         | 0.57%   |
| ATOPNUC                              | 1         | 0.57%   |
| Acidanthera                          | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 2.29%   |
| Lenovo G50-45 80E3                         | 2         | 1.14%   |
| HP Pavilion dv6                            | 2         | 1.14%   |
| Dell OptiPlex 790                          | 2         | 1.14%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 1.14%   |
| ASUS PRIME X570-PRO                        | 2         | 1.14%   |
| ASUS M4A785-M                              | 2         | 1.14%   |
| win element MoreFine S500+                 | 1         | 0.57%   |
| Toshiba Satellite L755D                    | 1         | 0.57%   |
| Toshiba Satellite L505                     | 1         | 0.57%   |
| Toshiba Satellite C855                     | 1         | 0.57%   |
| System76 Thelio                            | 1         | 0.57%   |
| Sony VGN-NS31M_W                           | 1         | 0.57%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.57%   |
| Samsung 305V4A/305V5A                      | 1         | 0.57%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.57%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.57%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.57%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.57%   |
| MSI MS-7E02                                | 1         | 0.57%   |
| MSI MS-7A57                                | 1         | 0.57%   |
| MSI MS-7752                                | 1         | 0.57%   |
| Medion MD34207/C746                        | 1         | 0.57%   |
| Lenovo ThinkPad X250 20CL001LMB            | 1         | 0.57%   |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.57%   |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.57%   |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.57%   |
| Lenovo ThinkPad X1 Yoga Gen 7 21CDCTO1WW   | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.57%   |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.57%   |
| Lenovo ThinkPad T530 24296HG               | 1         | 0.57%   |
| Lenovo ThinkPad T520 4243K86               | 1         | 0.57%   |
| Lenovo ThinkPad P50 20EQS0VV03             | 1         | 0.57%   |
| Lenovo ThinkPad L460 20FVS3JK00            | 1         | 0.57%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE       | 1         | 0.57%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1         | 0.57%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.57%   |
| Lenovo IdeaPadFlex 5 14IIL05 81X1          | 1         | 0.57%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4       | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 13        | 7.43%   |
| Dell OptiPlex                              | 9         | 5.14%   |
| HP Compaq                                  | 8         | 4.57%   |
| Dell Inspiron                              | 8         | 4.57%   |
| Lenovo IdeaPad                             | 5         | 2.86%   |
| Dell Latitude                              | 5         | 2.86%   |
| Acer Aspire                                | 5         | 2.86%   |
| ASUS ROG                                   | 4         | 2.29%   |
| ASUS All                                   | 4         | 2.29%   |
| Toshiba Satellite                          | 3         | 1.71%   |
| HP Pavilion                                | 3         | 1.71%   |
| HP EliteBook                               | 3         | 1.71%   |
| Fujitsu ESPRIMO                            | 3         | 1.71%   |
| Dell Precision                             | 3         | 1.71%   |
| ASUS TUF                                   | 3         | 1.71%   |
| Lenovo G50-45                              | 2         | 1.14%   |
| ASUS PRIME                                 | 2         | 1.14%   |
| ASUS P8P67                                 | 2         | 1.14%   |
| ASUS M4A785-M                              | 2         | 1.14%   |
| win element MoreFine                       | 1         | 0.57%   |
| System76 Thelio                            | 1         | 0.57%   |
| Sony VGN-NS31M                             | 1         | 0.57%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.57%   |
| Samsung 305V4A                             | 1         | 0.57%   |
| Razer Blade                                | 1         | 0.57%   |
| RPi Raspberry                              | 1         | 0.57%   |
| Pegatron FL368AA-UUZ                       | 1         | 0.57%   |
| Packard Bell IMEDIA                        | 1         | 0.57%   |
| MSI MS-7E02                                | 1         | 0.57%   |
| MSI MS-7A57                                | 1         | 0.57%   |
| MSI MS-7752                                | 1         | 0.57%   |
| Medion MD34207                             | 1         | 0.57%   |
| Lenovo ThinkCentre                         | 1         | 0.57%   |
| Lenovo Legion                              | 1         | 0.57%   |
| Lenovo IdeaPadFlex                         | 1         | 0.57%   |
| Lenovo IdeaCentre                          | 1         | 0.57%   |
| Lenovo G70-80                              | 1         | 0.57%   |
| Intel NUC8i5BEH                            | 1         | 0.57%   |
| Intel NUC7i5DNKE                           | 1         | 0.57%   |
| Intel DQ965GF                              | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 20        | 11.43%  |
| 2019 | 16        | 9.14%   |
| 2012 | 16        | 9.14%   |
| 2018 | 12        | 6.86%   |
| 2014 | 12        | 6.86%   |
| 2013 | 12        | 6.86%   |
| 2011 | 12        | 6.86%   |
| 2021 | 11        | 6.29%   |
| 2016 | 10        | 5.71%   |
| 2015 | 10        | 5.71%   |
| 2017 | 9         | 5.14%   |
| 2010 | 8         | 4.57%   |
| 2009 | 8         | 4.57%   |
| 2008 | 7         | 4%      |
| 2022 | 5         | 2.86%   |
| 2007 | 4         | 2.29%   |
| 2005 | 3         | 1.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 81        | 46.29%  |
| Notebook       | 79        | 45.14%  |
| All in one     | 6         | 3.43%   |
| Mini pc        | 5         | 2.86%   |
| Convertible    | 3         | 1.71%   |
| System on chip | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 165       | 94.29%  |
| Enabled  | 10        | 5.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 98.86%  |
| Yes  | 2         | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 50        | 28.41%  |
| 16.01-24.0  | 37        | 21.02%  |
| 8.01-16.0   | 35        | 19.89%  |
| 32.01-64.0  | 20        | 11.36%  |
| 3.01-4.0    | 16        | 9.09%   |
| 64.01-256.0 | 8         | 4.55%   |
| 1.01-2.0    | 4         | 2.27%   |
| 24.01-32.0  | 3         | 1.7%    |
| 2.01-3.0    | 3         | 1.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 57        | 31.84%  |
| 2.01-3.0   | 43        | 24.02%  |
| 4.01-8.0   | 34        | 18.99%  |
| 3.01-4.0   | 28        | 15.64%  |
| 8.01-16.0  | 12        | 6.7%    |
| 0.51-1.0   | 4         | 2.23%   |
| 24.01-32.0 | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 52.27%  |
| 2      | 61        | 34.66%  |
| 3      | 8         | 4.55%   |
| 4      | 5         | 2.84%   |
| 7      | 3         | 1.7%    |
| 5      | 2         | 1.14%   |
| 0      | 2         | 1.14%   |
| 16     | 1         | 0.57%   |
| 11     | 1         | 0.57%   |
| 10     | 1         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 55.68%  |
| Yes       | 78        | 44.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 89.71%  |
| No        | 18        | 10.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 73.71%  |
| No        | 46        | 26.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 54.86%  |
| No        | 79        | 45.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 43        | 24.57%  |
| France                 | 22        | 12.57%  |
| Germany                | 19        | 10.86%  |
| Italy                  | 10        | 5.71%   |
| Russia                 | 7         | 4%      |
| Brazil                 | 7         | 4%      |
| Spain                  | 6         | 3.43%   |
| UK                     | 5         | 2.86%   |
| Canada                 | 5         | 2.86%   |
| Austria                | 5         | 2.86%   |
| Belgium                | 4         | 2.29%   |
| Australia              | 4         | 2.29%   |
| Sweden                 | 3         | 1.71%   |
| Netherlands            | 3         | 1.71%   |
| Taiwan                 | 2         | 1.14%   |
| Switzerland            | 2         | 1.14%   |
| Romania                | 2         | 1.14%   |
| Norway                 | 2         | 1.14%   |
| Mexico                 | 2         | 1.14%   |
| Ivory Coast            | 2         | 1.14%   |
| Costa Rica             | 2         | 1.14%   |
| Argentina              | 2         | 1.14%   |
| Yemen                  | 1         | 0.57%   |
| Turkey                 | 1         | 0.57%   |
| South Africa           | 1         | 0.57%   |
| Slovakia               | 1         | 0.57%   |
| Poland                 | 1         | 0.57%   |
| Peru                   | 1         | 0.57%   |
| Nigeria                | 1         | 0.57%   |
| Nicaragua              | 1         | 0.57%   |
| Luxembourg             | 1         | 0.57%   |
| Kenya                  | 1         | 0.57%   |
| Indonesia              | 1         | 0.57%   |
| Hungary                | 1         | 0.57%   |
| Guatemala              | 1         | 0.57%   |
| Finland                | 1         | 0.57%   |
| Bulgaria               | 1         | 0.57%   |
| Bosnia and Herzegovina | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Vienna        | 3         | 1.69%   |
| Stockholm     | 3         | 1.69%   |
| Paris         | 3         | 1.69%   |
| Madrid        | 3         | 1.69%   |
| Houston       | 3         | 1.69%   |
| Turin         | 2         | 1.13%   |
| Stuttgart     | 2         | 1.13%   |
| San Francisco | 2         | 1.13%   |
| Moscow        | 2         | 1.13%   |
| Montreal      | 2         | 1.13%   |
| Mississauga   | 2         | 1.13%   |
| Hamburg       | 2         | 1.13%   |
| Groningen     | 2         | 1.13%   |
| Denver        | 2         | 1.13%   |
| Bucharest     | 2         | 1.13%   |
| Béziers      | 2         | 1.13%   |
| Abidjan       | 2         | 1.13%   |
| Zanesville    | 1         | 0.56%   |
| Yonkers       | 1         | 0.56%   |
| Yekaterinburg | 1         | 0.56%   |
| Wroclaw       | 1         | 0.56%   |
| Woonsocket    | 1         | 0.56%   |
| Woodland Park | 1         | 0.56%   |
| Wildenfels    | 1         | 0.56%   |
| West Mifflin  | 1         | 0.56%   |
| Warner Robins | 1         | 0.56%   |
| Villefontaine | 1         | 0.56%   |
| Verviers      | 1         | 0.56%   |
| Velleron      | 1         | 0.56%   |
| Tilburg       | 1         | 0.56%   |
| Taylor        | 1         | 0.56%   |
| Tarragona     | 1         | 0.56%   |
| Taipei        | 1         | 0.56%   |
| Taichung      | 1         | 0.56%   |
| Sunderland    | 1         | 0.56%   |
| Stabekk       | 1         | 0.56%   |
| St Petersburg | 1         | 0.56%   |
| Sofia         | 1         | 0.56%   |
| Sleman        | 1         | 0.56%   |
| Sherman Oaks  | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 45        | 53     | 16.48%  |
| Samsung Electronics   | 44        | 55     | 16.12%  |
| Seagate               | 32        | 55     | 11.72%  |
| SanDisk               | 18        | 19     | 6.59%   |
| Toshiba               | 17        | 18     | 6.23%   |
| Kingston              | 9         | 10     | 3.3%    |
| Hitachi               | 9         | 10     | 3.3%    |
| Intel                 | 8         | 11     | 2.93%   |
| Crucial               | 8         | 8      | 2.93%   |
| Unknown               | 7         | 7      | 2.56%   |
| SK hynix              | 5         | 6      | 1.83%   |
| Phison                | 5         | 5      | 1.83%   |
| HGST                  | 5         | 6      | 1.83%   |
| Micron Technology     | 4         | 4      | 1.47%   |
| Team                  | 3         | 3      | 1.1%    |
| SPCC                  | 3         | 3      | 1.1%    |
| PNY                   | 3         | 3      | 1.1%    |
| JMicron Technology    | 3         | 3      | 1.1%    |
| Intenso               | 3         | 3      | 1.1%    |
| China                 | 3         | 3      | 1.1%    |
| ASMT                  | 3         | 3      | 1.1%    |
| A-DATA Technology     | 3         | 4      | 1.1%    |
| KIOXIA                | 2         | 2      | 0.73%   |
| Fujitsu               | 2         | 2      | 0.73%   |
| Corsair               | 2         | 3      | 0.73%   |
| BHT                   | 2         | 2      | 0.73%   |
| Apple                 | 2         | 3      | 0.73%   |
| XPG                   | 1         | 1      | 0.37%   |
| Wibtek                | 1         | 1      | 0.37%   |
| USB 3.0               | 1         | 2      | 0.37%   |
| Union Memory          | 1         | 1      | 0.37%   |
| UMIS                  | 1         | 1      | 0.37%   |
| TO Exter              | 1         | 1      | 0.37%   |
| SCY                   | 1         | 1      | 0.37%   |
| Reeinno               | 1         | 1      | 0.37%   |
| Realtek Semiconductor | 1         | 1      | 0.37%   |
| Realtek               | 1         | 1      | 0.37%   |
| Phison Electronics    | 1         | 1      | 0.37%   |
| Patriot               | 1         | 1      | 0.37%   |
| OCZ                   | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 1.32%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.32%   |
| Seagate ST2000DM001-1ER164 2TB            | 4         | 1.32%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 1.32%   |
| Seagate ST2000DM008-2FR102 2TB            | 3         | 0.99%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 0.99%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 0.99%   |
| Crucial CT500MX500SSD1 500GB              | 3         | 0.99%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 2         | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.66%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.66%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.66%   |
| Toshiba HDWD130 3TB                       | 2         | 0.66%   |
| Toshiba DT01ACA050 500GB                  | 2         | 0.66%   |
| Team T253X6001T 1024GB SSD                | 2         | 0.66%   |
| SPCC Solid State Disk 256GB               | 2         | 0.66%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.66%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.66%   |
| Seagate Expansion Desk 8TB                | 2         | 0.66%   |
| Seagate Expansion 1TB                     | 2         | 0.66%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.66%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.66%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.66%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.66%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.66%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.66%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.66%   |
| Samsung HD753LJ 752GB                     | 2         | 0.66%   |
| Phison Sabrent 1TB                        | 2         | 0.66%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 0.66%   |
| JMicron Generic 512GB                     | 2         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 0.66%   |
| China SSD 1TB                             | 2         | 0.66%   |
| XPG GAMMIX S7 1TB                         | 1         | 0.33%   |
| Wibtek W800S 512GB                        | 1         | 0.33%   |
| WDC WDS512G1X0C-00ENX0 512GB              | 1         | 0.33%   |
| WDC WDS100T2G0A-00JH30 1TB SSD            | 1         | 0.33%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.33%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.33%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 42     | 30.63%  |
| Seagate             | 31        | 53     | 27.93%  |
| Toshiba             | 16        | 17     | 14.41%  |
| Hitachi             | 9         | 10     | 8.11%   |
| Samsung Electronics | 5         | 5      | 4.5%    |
| HGST                | 5         | 6      | 4.5%    |
| JMicron Technology  | 2         | 2      | 1.8%    |
| Fujitsu             | 2         | 2      | 1.8%    |
| ASMT                | 2         | 2      | 1.8%    |
| USB 3.0             | 1         | 2      | 0.9%    |
| Unknown             | 1         | 1      | 0.9%    |
| Maxtor              | 1         | 1      | 0.9%    |
| Inateck             | 1         | 1      | 0.9%    |
| Apple               | 1         | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 31     | 26.53%  |
| SanDisk             | 15        | 16     | 15.31%  |
| Kingston            | 8         | 9      | 8.16%   |
| Crucial             | 8         | 8      | 8.16%   |
| WDC                 | 4         | 4      | 4.08%   |
| SPCC                | 3         | 3      | 3.06%   |
| PNY                 | 3         | 3      | 3.06%   |
| Micron Technology   | 3         | 3      | 3.06%   |
| Intenso             | 3         | 3      | 3.06%   |
| China               | 3         | 3      | 3.06%   |
| Team                | 2         | 2      | 2.04%   |
| BHT                 | 2         | 2      | 2.04%   |
| A-DATA Technology   | 2         | 2      | 2.04%   |
| Wibtek              | 1         | 1      | 1.02%   |
| Toshiba             | 1         | 1      | 1.02%   |
| TO Exter            | 1         | 1      | 1.02%   |
| SK hynix            | 1         | 1      | 1.02%   |
| SCY                 | 1         | 1      | 1.02%   |
| Reeinno             | 1         | 1      | 1.02%   |
| Patriot             | 1         | 1      | 1.02%   |
| OCZ                 | 1         | 1      | 1.02%   |
| NGFF                | 1         | 1      | 1.02%   |
| Leven               | 1         | 1      | 1.02%   |
| KingSpec            | 1         | 1      | 1.02%   |
| Intel               | 1         | 1      | 1.02%   |
| Integral            | 1         | 1      | 1.02%   |
| Dogfish             | 1         | 1      | 1.02%   |
| Corsair             | 1         | 1      | 1.02%   |
| ASMT                | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 88        | 145    | 38.26%  |
| SSD     | 81        | 105    | 35.22%  |
| NVMe    | 50        | 66     | 21.74%  |
| MMC     | 8         | 9      | 3.48%   |
| Unknown | 3         | 3      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135       | 232    | 64.59%  |
| NVMe | 50        | 65     | 23.92%  |
| SAS  | 16        | 22     | 7.66%   |
| MMC  | 8         | 9      | 3.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 127    | 52.94%  |
| 0.51-1.0   | 54        | 66     | 28.88%  |
| 1.01-2.0   | 16        | 19     | 8.56%   |
| 4.01-10.0  | 8         | 25     | 4.28%   |
| 3.01-4.0   | 7         | 9      | 3.74%   |
| 2.01-3.0   | 3         | 4      | 1.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 28.09%  |
| 501-1000       | 32        | 17.98%  |
| 251-500        | 31        | 17.42%  |
| 1001-2000      | 23        | 12.92%  |
| More than 3000 | 14        | 7.87%   |
| 51-100         | 11        | 6.18%   |
| 21-50          | 9         | 5.06%   |
| 1-20           | 6         | 3.37%   |
| 2001-3000      | 2         | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 56        | 31.28%  |
| 21-50          | 31        | 17.32%  |
| 101-250        | 29        | 16.2%   |
| 251-500        | 17        | 9.5%    |
| 51-100         | 15        | 8.38%   |
| 501-1000       | 12        | 6.7%    |
| More than 3000 | 8         | 4.47%   |
| 1001-2000      | 7         | 3.91%   |
| 2001-3000      | 4         | 2.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 7.89%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 3      | 5.26%   |
| Samsung Electronics HD753LJ 752GB                   | 2         | 2      | 5.26%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2.63%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1      | 2.63%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 2.63%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.63%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 2.63%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 2.63%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 2.63%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 2.63%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2.63%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 2.63%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 2.63%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.63%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 2.63%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 2.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.63%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 2.63%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 2.63%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 2.63%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 2.63%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 2.63%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 2.63%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.63%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 2.63%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 2.63%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.63%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.63%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 2.63%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 2.63%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 2.63%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 28.95%  |
| WDC                 | 8         | 8      | 21.05%  |
| Samsung Electronics | 7         | 8      | 18.42%  |
| Toshiba             | 3         | 3      | 7.89%   |
| Hitachi             | 3         | 3      | 7.89%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 36.67%  |
| WDC                 | 8         | 8      | 26.67%  |
| Samsung Electronics | 4         | 4      | 13.33%  |
| Toshiba             | 3         | 3      | 10%     |
| Hitachi             | 3         | 3      | 10%     |
| HGST                | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 35     | 78.38%  |
| SSD  | 7         | 8      | 18.92%  |
| NVMe | 1         | 1      | 2.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB               | 1         | 1      | 50%     |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 147       | 252    | 70.67%  |
| Malfunc  | 37        | 44     | 17.79%  |
| Detected | 22        | 30     | 10.58%  |
| Failed   | 2         | 2      | 0.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 119       | 51.97%  |
| AMD                          | 41        | 17.9%   |
| Samsung Electronics          | 17        | 7.42%   |
| SanDisk                      | 9         | 3.93%   |
| Phison Electronics           | 8         | 3.49%   |
| Marvell Technology Group     | 5         | 2.18%   |
| ASMedia Technology           | 5         | 2.18%   |
| SK hynix                     | 4         | 1.75%   |
| Nvidia                       | 3         | 1.31%   |
| Union Memory (Shenzhen)      | 2         | 0.87%   |
| Realtek Semiconductor        | 2         | 0.87%   |
| JMicron Technology           | 2         | 0.87%   |
| VIA Technologies             | 1         | 0.44%   |
| Toshiba America Info Systems | 1         | 0.44%   |
| Silicon Image                | 1         | 0.44%   |
| Seagate Technology           | 1         | 0.44%   |
| Micron Technology            | 1         | 0.44%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.44%   |
| LSI Logic / Symbios Logic    | 1         | 0.44%   |
| KIOXIA                       | 1         | 0.44%   |
| Kingston Technology Company  | 1         | 0.44%   |
| Apple                        | 1         | 0.44%   |
| ADATA Technology             | 1         | 0.44%   |
| Adaptec                      | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28        | 10.49%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 4.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 3.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 3%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 2.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 1.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.87%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.5%    |
| Phison E12 NVMe Controller                                                     | 4         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.5%    |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.12%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.12%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.75%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.75%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2         | 0.75%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2         | 0.75%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.75%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.75%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 59.13%  |
| NVMe | 51        | 22.17%  |
| IDE  | 25        | 10.87%  |
| RAID | 14        | 6.09%   |
| SAS  | 3         | 1.3%    |
| SCSI | 1         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 126       | 72%     |
| AMD    | 48        | 27.43%  |
| ARM    | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 1.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.71%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 1.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 1.14%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 1.14%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 1.14%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 1.14%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 1.14%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 1.14%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 1.14%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 1.14%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.14%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.14%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 1.14%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 1.14%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 2         | 1.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 1.14%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 1.14%   |
| AMD Phenom II X4 945 Processor          | 2         | 1.14%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.57%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.57%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1         | 0.57%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.57%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.57%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.57%   |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.57%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.57%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.57%   |
| Intel Pentium 4 CPU 2.80GHz             | 1         | 0.57%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.57%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1         | 0.57%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.57%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.57%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 1         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 42        | 24%     |
| Intel Core i7          | 40        | 22.86%  |
| Intel Core i3          | 12        | 6.86%   |
| Other                  | 10        | 5.71%   |
| AMD Ryzen 5            | 9         | 5.14%   |
| AMD Ryzen 7            | 8         | 4.57%   |
| Intel Core 2 Duo       | 5         | 2.86%   |
| Intel Celeron          | 5         | 2.86%   |
| AMD Ryzen 9            | 5         | 2.86%   |
| Intel Xeon             | 4         | 2.29%   |
| Intel Core i9          | 4         | 2.29%   |
| AMD Phenom II X4       | 4         | 2.29%   |
| AMD E                  | 3         | 1.71%   |
| Intel Pentium 4        | 2         | 1.14%   |
| AMD Ryzen 3            | 2         | 1.14%   |
| AMD FX                 | 2         | 1.14%   |
| AMD Athlon II X2       | 2         | 1.14%   |
| AMD A4                 | 2         | 1.14%   |
| Intel Pentium Dual     | 1         | 0.57%   |
| Intel Pentium D        | 1         | 0.57%   |
| Intel Pentium          | 1         | 0.57%   |
| Intel Genuine          | 1         | 0.57%   |
| Intel Core 2           | 1         | 0.57%   |
| AMD Ryzen Threadripper | 1         | 0.57%   |
| AMD Ryzen 3 PRO        | 1         | 0.57%   |
| AMD E2                 | 1         | 0.57%   |
| AMD E1                 | 1         | 0.57%   |
| AMD Athlon X4          | 1         | 0.57%   |
| AMD Athlon Dual Core   | 1         | 0.57%   |
| AMD Athlon 64 X2       | 1         | 0.57%   |
| AMD A6                 | 1         | 0.57%   |
| AMD A10                | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 72        | 41.14%  |
| 2      | 60        | 34.29%  |
| 6      | 20        | 11.43%  |
| 8      | 11        | 6.29%   |
| 12     | 3         | 1.71%   |
| 10     | 3         | 1.71%   |
| 1      | 3         | 1.71%   |
| 16     | 2         | 1.14%   |
| 32     | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 174       | 99.43%  |
| 2      | 1         | 0.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 114       | 65.14%  |
| 1      | 61        | 34.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 174       | 99.43%  |
| 32-bit         | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 12.5%   |
| 0x306c3    | 14        | 7.95%   |
| 0x306a9    | 13        | 7.39%   |
| 0x206a7    | 13        | 7.39%   |
| 0x906ea    | 8         | 4.55%   |
| 0x506e3    | 5         | 2.84%   |
| 0x306d4    | 5         | 2.84%   |
| 0x806ea    | 4         | 2.27%   |
| 0x806c1    | 4         | 2.27%   |
| 0x08701021 | 4         | 2.27%   |
| 0x08600104 | 4         | 2.27%   |
| 0xa0652    | 3         | 1.7%    |
| 0x906e9    | 3         | 1.7%    |
| 0x406e3    | 3         | 1.7%    |
| 0x106e5    | 3         | 1.7%    |
| 0x10676    | 3         | 1.7%    |
| 0x0a50000d | 3         | 1.7%    |
| 0x08108109 | 3         | 1.7%    |
| 0x010000c8 | 3         | 1.7%    |
| 0xf41      | 2         | 1.14%   |
| 0xa0655    | 2         | 1.14%   |
| 0x906ed    | 2         | 1.14%   |
| 0x706e5    | 2         | 1.14%   |
| 0x6fd      | 2         | 1.14%   |
| 0x40651    | 2         | 1.14%   |
| 0x206d7    | 2         | 1.14%   |
| 0x0a50000c | 2         | 1.14%   |
| 0x08600106 | 2         | 1.14%   |
| 0x07030105 | 2         | 1.14%   |
| 0x010000b6 | 2         | 1.14%   |
| 0xf65      | 1         | 0.57%   |
| 0x906a3    | 1         | 0.57%   |
| 0x90675    | 1         | 0.57%   |
| 0x806e9    | 1         | 0.57%   |
| 0x706a1    | 1         | 0.57%   |
| 0x6fb      | 1         | 0.57%   |
| 0x6f6      | 1         | 0.57%   |
| 0x506ca    | 1         | 0.57%   |
| 0x506c9    | 1         | 0.57%   |
| 0x50654    | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 11.43%  |
| Haswell          | 18        | 10.29%  |
| Zen 2            | 15        | 8.57%   |
| SandyBridge      | 15        | 8.57%   |
| Skylake          | 14        | 8%      |
| IvyBridge        | 14        | 8%      |
| Zen 3            | 6         | 3.43%   |
| K10              | 6         | 3.43%   |
| Broadwell        | 6         | 3.43%   |
| Penryn           | 5         | 2.86%   |
| Nehalem          | 5         | 2.86%   |
| CometLake        | 5         | 2.86%   |
| Westmere         | 4         | 2.29%   |
| TigerLake        | 4         | 2.29%   |
| Core             | 4         | 2.29%   |
| Zen+             | 3         | 1.71%   |
| Puma             | 3         | 1.71%   |
| Piledriver       | 3         | 1.71%   |
| NetBurst         | 3         | 1.71%   |
| IceLake          | 3         | 1.71%   |
| Excavator        | 3         | 1.71%   |
| Unknown          | 3         | 1.71%   |
| K8 Hammer        | 2         | 1.14%   |
| Goldmont         | 2         | 1.14%   |
| Bobcat           | 2         | 1.14%   |
| Alderlake Hybrid | 2         | 1.14%   |
| Zen              | 1         | 0.57%   |
| Steamroller      | 1         | 0.57%   |
| Silvermont       | 1         | 0.57%   |
| K10 Llano        | 1         | 0.57%   |
| Goldmont plus    | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 89        | 43.63%  |
| Nvidia | 65        | 31.86%  |
| AMD    | 50        | 24.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8         | 3.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 3.35%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 3.35%   |
| AMD Renoir                                                                  | 7         | 3.35%   |
| Intel HD Graphics 530                                                       | 6         | 2.87%   |
| Intel HD Graphics 5500                                                      | 5         | 2.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 2.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 1.91%   |
| Nvidia TU117M                                                               | 3         | 1.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.44%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.44%   |
| Intel UHD Graphics 620                                                      | 3         | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.96%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.96%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.96%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 0.96%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 0.96%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.96%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 0.96%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.96%   |
| Intel Iris Plus Graphics G7                                                 | 2         | 0.96%   |
| Intel HD Graphics 630                                                       | 2         | 0.96%   |
| Intel HD Graphics 500                                                       | 2         | 0.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 0.96%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 0.96%   |
| AMD Wrestler [Radeon HD 6310]                                               | 2         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 35.43%  |
| 1 x AMD        | 41        | 23.43%  |
| 1 x Nvidia     | 40        | 22.86%  |
| Intel + Nvidia | 20        | 11.43%  |
| AMD + Nvidia   | 4         | 2.29%   |
| Intel + AMD    | 3         | 1.71%   |
| 2 x AMD        | 2         | 1.14%   |
| Other          | 1         | 0.57%   |
| 2 x Nvidia     | 1         | 0.57%   |
| 2 x Intel      | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 143       | 81.25%  |
| Proprietary | 31        | 17.61%  |
| Unknown     | 2         | 1.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 43.18%  |
| 0.01-0.5   | 26        | 14.77%  |
| 1.01-2.0   | 25        | 14.2%   |
| 0.51-1.0   | 20        | 11.36%  |
| 3.01-4.0   | 13        | 7.39%   |
| 7.01-8.0   | 5         | 2.84%   |
| 5.01-6.0   | 5         | 2.84%   |
| 8.01-16.0  | 4         | 2.27%   |
| 2.01-3.0   | 1         | 0.57%   |
| 16.01-24.0 | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 25        | 12.76%  |
| LG Display              | 21        | 10.71%  |
| AU Optronics            | 16        | 8.16%   |
| Goldstar                | 13        | 6.63%   |
| Hewlett-Packard         | 12        | 6.12%   |
| Dell                    | 12        | 6.12%   |
| BOE                     | 12        | 6.12%   |
| Philips                 | 10        | 5.1%    |
| Chimei Innolux          | 10        | 5.1%    |
| Acer                    | 10        | 5.1%    |
| Ancor Communications    | 7         | 3.57%   |
| Lenovo                  | 4         | 2.04%   |
| Apple                   | 4         | 2.04%   |
| AOC                     | 3         | 1.53%   |
| Sharp                   | 2         | 1.02%   |
| ONN                     | 2         | 1.02%   |
| Iiyama                  | 2         | 1.02%   |
| Hannspree               | 2         | 1.02%   |
| Fujitsu Siemens         | 2         | 1.02%   |
| Eizo                    | 2         | 1.02%   |
| Chi Mei Optoelectronics | 2         | 1.02%   |
| BenQ                    | 2         | 1.02%   |
| ASUSTek Computer        | 2         | 1.02%   |
| ViewSonic               | 1         | 0.51%   |
| VIE                     | 1         | 0.51%   |
| Unknown                 | 1         | 0.51%   |
| UGD                     | 1         | 0.51%   |
| TVT                     | 1         | 0.51%   |
| Targa Visionary         | 1         | 0.51%   |
| Sony                    | 1         | 0.51%   |
| Seiki                   | 1         | 0.51%   |
| Onkyo                   | 1         | 0.51%   |
| NEC Computers           | 1         | 0.51%   |
| MSI                     | 1         | 0.51%   |
| Medion                  | 1         | 0.51%   |
| LG Philips              | 1         | 0.51%   |
| KTC                     | 1         | 0.51%   |
| HannStar                | 1         | 0.51%   |
| DENON                   | 1         | 0.51%   |
| CPT                     | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 2         | 0.97%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.97%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.97%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 2         | 0.97%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.97%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.97%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.97%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2         | 0.97%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1         | 0.48%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1         | 0.48%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1         | 0.48%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch               | 1         | 0.48%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1         | 0.48%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1         | 0.48%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.48%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.48%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1         | 0.48%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.48%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.48%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1         | 0.48%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1         | 0.48%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch   | 1         | 0.48%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.48%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.48%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 90        | 48.91%  |
| 1366x768 (WXGA)    | 26        | 14.13%  |
| 3840x2160 (4K)     | 16        | 8.7%    |
| 1280x1024 (SXGA)   | 10        | 5.43%   |
| 1680x1050 (WSXGA+) | 7         | 3.8%    |
| 1600x900 (HD+)     | 7         | 3.8%    |
| 1920x1200 (WUXGA)  | 6         | 3.26%   |
| 2560x1440 (QHD)    | 4         | 2.17%   |
| 1440x900 (WXGA+)   | 4         | 2.17%   |
| 3440x1440          | 2         | 1.09%   |
| 1360x768           | 2         | 1.09%   |
| 1280x800 (WXGA)    | 2         | 1.09%   |
| Unknown            | 2         | 1.09%   |
| 5760x2160          | 1         | 0.54%   |
| 3280x1080          | 1         | 0.54%   |
| 2880x1800          | 1         | 0.54%   |
| 2160x1440          | 1         | 0.54%   |
| 1600x1200          | 1         | 0.54%   |
| 1400x1050          | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 47        | 23.98%  |
| 23      | 18        | 9.18%   |
| 21      | 18        | 9.18%   |
| 24      | 17        | 8.67%   |
| 27      | 16        | 8.16%   |
| 13      | 11        | 5.61%   |
| 14      | 10        | 5.1%    |
| 19      | 9         | 4.59%   |
| 17      | 9         | 4.59%   |
| 31      | 6         | 3.06%   |
| 18      | 6         | 3.06%   |
| 22      | 5         | 2.55%   |
| 12      | 5         | 2.55%   |
| 20      | 4         | 2.04%   |
| Unknown | 3         | 1.53%   |
| 84      | 2         | 1.02%   |
| 65      | 1         | 0.51%   |
| 54      | 1         | 0.51%   |
| 52      | 1         | 0.51%   |
| 50      | 1         | 0.51%   |
| 43      | 1         | 0.51%   |
| 34      | 1         | 0.51%   |
| 32      | 1         | 0.51%   |
| 26      | 1         | 0.51%   |
| 16      | 1         | 0.51%   |
| 11      | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 35.6%   |
| 501-600     | 47        | 24.61%  |
| 401-500     | 36        | 18.85%  |
| 201-300     | 12        | 6.28%   |
| 601-700     | 8         | 4.19%   |
| 351-400     | 8         | 4.19%   |
| 1001-1500   | 4         | 2.09%   |
| Unknown     | 3         | 1.57%   |
| 701-800     | 2         | 1.05%   |
| 1501-2000   | 2         | 1.05%   |
| 901-1000    | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 135       | 76.27%  |
| 16/10   | 25        | 14.12%  |
| 5/4     | 9         | 5.08%   |
| Unknown | 3         | 1.69%   |
| 4/3     | 2         | 1.13%   |
| 3/2     | 2         | 1.13%   |
| 21/9    | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 24.48%  |
| 201-250        | 45        | 23.44%  |
| 301-350        | 17        | 8.85%   |
| 81-90          | 16        | 8.33%   |
| 151-200        | 15        | 7.81%   |
| 141-150        | 12        | 6.25%   |
| 351-500        | 8         | 4.17%   |
| 251-300        | 7         | 3.65%   |
| More than 1000 | 6         | 3.13%   |
| 71-80          | 5         | 2.6%    |
| 61-70          | 5         | 2.6%    |
| Unknown        | 3         | 1.56%   |
| 121-130        | 2         | 1.04%   |
| 51-60          | 1         | 0.52%   |
| 131-140        | 1         | 0.52%   |
| 111-120        | 1         | 0.52%   |
| 501-1000       | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 76        | 40.86%  |
| 121-160       | 45        | 24.19%  |
| 101-120       | 45        | 24.19%  |
| 161-240       | 13        | 6.99%   |
| Unknown       | 3         | 1.61%   |
| More than 240 | 2         | 1.08%   |
| 1-50          | 2         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 136       | 76.84%  |
| 2     | 38        | 21.47%  |
| 3     | 2         | 1.13%   |
| 0     | 1         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 96        | 35.96%  |
| Realtek Semiconductor             | 93        | 34.83%  |
| Qualcomm Atheros                  | 28        | 10.49%  |
| Broadcom                          | 14        | 5.24%   |
| MediaTek                          | 5         | 1.87%   |
| ASIX Electronics                  | 4         | 1.5%    |
| TP-Link                           | 3         | 1.12%   |
| Nvidia                            | 3         | 1.12%   |
| Broadcom Limited                  | 3         | 1.12%   |
| Ralink                            | 2         | 0.75%   |
| Ericsson Business Mobile Networks | 2         | 0.75%   |
| Aquantia                          | 2         | 0.75%   |
| ZyDAS                             | 1         | 0.37%   |
| Wacom                             | 1         | 0.37%   |
| Ralink Technology                 | 1         | 0.37%   |
| Qualcomm Atheros Communications   | 1         | 0.37%   |
| NetGear                           | 1         | 0.37%   |
| Motorola PCS                      | 1         | 0.37%   |
| Microsoft                         | 1         | 0.37%   |
| Marvell Technology Group          | 1         | 0.37%   |
| InterBiometrics                   | 1         | 0.37%   |
| Input Club                        | 1         | 0.37%   |
| Huawei Technologies               | 1         | 0.37%   |
| DisplayLink                       | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 66        | 21.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17        | 5.43%   |
| Intel Wireless 7265                                                           | 10        | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 1.92%   |
| Intel I211 Gigabit Network Connection                                         | 6         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 5         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 1.6%    |
| Intel Wireless-AC 9260                                                        | 5         | 1.6%    |
| Intel Ethernet Connection I217-LM                                             | 5         | 1.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.6%    |
| Realtek 802.11ac NIC                                                          | 4         | 1.28%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 1.28%   |
| Intel Wireless 8260                                                           | 4         | 1.28%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 0.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 3         | 0.96%   |
| Intel Wireless 7260                                                           | 3         | 0.96%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 0.96%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.64%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 0.64%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 0.64%   |
| Intel WiFi Link 5100                                                          | 2         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.64%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.64%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.64%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 47.73%  |
| Realtek Semiconductor           | 23        | 17.42%  |
| Qualcomm Atheros                | 22        | 16.67%  |
| Broadcom                        | 8         | 6.06%   |
| MediaTek                        | 4         | 3.03%   |
| TP-Link                         | 3         | 2.27%   |
| Ralink                          | 2         | 1.52%   |
| ZyDAS                           | 1         | 0.76%   |
| Wacom                           | 1         | 0.76%   |
| Ralink Technology               | 1         | 0.76%   |
| Qualcomm Atheros Communications | 1         | 0.76%   |
| NetGear                         | 1         | 0.76%   |
| Microsoft                       | 1         | 0.76%   |
| Broadcom Limited                | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 10        | 7.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 4.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6         | 4.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 3.76%   |
| Intel Wireless-AC 9260                                                        | 5         | 3.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 3.76%   |
| Realtek 802.11ac NIC                                                          | 4         | 3.01%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 3.01%   |
| Intel Wireless 8260                                                           | 4         | 3.01%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 2.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 3         | 2.26%   |
| Intel Wireless 7260                                                           | 3         | 2.26%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 2.26%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 2.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 1.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.5%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.5%    |
| Intel WiFi Link 5100                                                          | 2         | 1.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.5%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 1.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.5%    |
| ZyDAS ZD1211B 802.11g                                                         | 1         | 0.75%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1         | 0.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.75%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.75%   |
| TP-Link 802.11ac NIC                                                          | 1         | 0.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.75%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 78        | 45.88%  |
| Intel                    | 61        | 35.88%  |
| Broadcom                 | 9         | 5.29%   |
| Qualcomm Atheros         | 8         | 4.71%   |
| ASIX Electronics         | 4         | 2.35%   |
| Nvidia                   | 3         | 1.76%   |
| Broadcom Limited         | 2         | 1.18%   |
| Aquantia                 | 2         | 1.18%   |
| MediaTek                 | 1         | 0.59%   |
| Marvell Technology Group | 1         | 0.59%   |
| DisplayLink              | 1         | 0.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 37.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 9.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 6         | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.87%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.87%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.72%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.15%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.15%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.15%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.15%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.15%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.15%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.15%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.57%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.57%   |
| MediaTek Titan pocket                                             | 1         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.57%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 157       | 53.77%  |
| WiFi     | 129       | 44.18%  |
| Modem    | 5         | 1.71%   |
| Unknown  | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 50.53%  |
| Ethernet | 93        | 49.47%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 98        | 56%     |
| 1     | 71        | 40.57%  |
| 3     | 4         | 2.29%   |
| 0     | 2         | 1.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 137       | 77.84%  |
| Yes  | 39        | 22.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 49.48%  |
| Qualcomm Atheros Communications | 8         | 8.25%   |
| Realtek Semiconductor           | 7         | 7.22%   |
| Cambridge Silicon Radio         | 6         | 6.19%   |
| Broadcom                        | 5         | 5.15%   |
| Apple                           | 5         | 5.15%   |
| ASUSTek Computer                | 4         | 4.12%   |
| MediaTek                        | 3         | 3.09%   |
| Realtek                         | 2         | 2.06%   |
| Ralink Technology               | 2         | 2.06%   |
| Lite-On Technology              | 2         | 2.06%   |
| Hewlett-Packard                 | 2         | 2.06%   |
| IMC Networks                    | 1         | 1.03%   |
| Foxconn International           | 1         | 1.03%   |
| Dell                            | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 22.68%  |
| Intel AX201 Bluetooth                               | 8         | 8.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 7.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 6.19%   |
| Realtek Bluetooth Radio                             | 5         | 5.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 5.15%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 4.12%   |
| MediaTek Wireless_Device                            | 3         | 3.09%   |
| Intel AX200 Bluetooth                               | 3         | 3.09%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 2.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.06%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 2.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 2.06%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.06%   |
| Apple Bluetooth Host Controller                     | 2         | 2.06%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.03%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.03%   |
| Ralink CSR BS8510                                   | 1         | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.03%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.03%   |
| Intel Bluetooth Device                              | 1         | 1.03%   |
| Intel AX210 Bluetooth                               | 1         | 1.03%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.03%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.03%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 1.03%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.03%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.03%   |
| ASUS BCM20702A0                                     | 1         | 1.03%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 121       | 41.72%  |
| AMD                                  | 56        | 19.31%  |
| Nvidia                               | 53        | 18.28%  |
| C-Media Electronics                  | 6         | 2.07%   |
| Texas Instruments                    | 5         | 1.72%   |
| Yamaha                               | 4         | 1.38%   |
| Logitech                             | 3         | 1.03%   |
| JMTek                                | 3         | 1.03%   |
| QinHeng Electronics                  | 2         | 0.69%   |
| PreSonus Audio Electronics           | 2         | 0.69%   |
| Mackie Designs                       | 2         | 0.69%   |
| M-Audio                              | 2         | 0.69%   |
| Generalplus Technology               | 2         | 0.69%   |
| Focusrite-Novation                   | 2         | 0.69%   |
| ZOOM                                 | 1         | 0.34%   |
| Yealink Network Technology           | 1         | 0.34%   |
| Xilinx                               | 1         | 0.34%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.34%   |
| Textech International                | 1         | 0.34%   |
| Tenx Technology                      | 1         | 0.34%   |
| TEAC                                 | 1         | 0.34%   |
| Studiologic                          | 1         | 0.34%   |
| SteelSeries ApS                      | 1         | 0.34%   |
| Samson Technologies                  | 1         | 0.34%   |
| Plantronics                          | 1         | 0.34%   |
| MIDITECH                             | 1         | 0.34%   |
| Medeli Electronics                   | 1         | 0.34%   |
| Mark of the Unicorn                  | 1         | 0.34%   |
| KTMicro                              | 1         | 0.34%   |
| Jieli Technology                     | 1         | 0.34%   |
| Harman                               | 1         | 0.34%   |
| Ensoniq                              | 1         | 0.34%   |
| Dell                                 | 1         | 0.34%   |
| Creative Technology                  | 1         | 0.34%   |
| Behringer.......                     | 1         | 0.34%   |
| BEHRINGER International              | 1         | 0.34%   |
| Audient                              | 1         | 0.34%   |
| ASUSTek Computer                     | 1         | 0.34%   |
| Apple                                | 1         | 0.34%   |
| Alesis                               | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 17        | 4.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15        | 4.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 13        | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 12        | 3.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12        | 3.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10        | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                        | 10        | 2.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8         | 2.34%   |
| Intel Sunrise Point-LP HD Audio                                                   | 8         | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8         | 2.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8         | 2.34%   |
| AMD Starship/Matisse HD Audio Controller                                          | 8         | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8         | 2.34%   |
| AMD FCH Azalia Controller                                                         | 7         | 2.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.75%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 1.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 1.17%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 1.17%   |
| Intel 200 Series PCH HD Audio                                                     | 4         | 1.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4         | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                          | 4         | 1.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 1.17%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3         | 0.88%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3         | 0.88%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 3         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3         | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 0.88%   |
| QinHeng Electronics CH345 MIDI adapter                                            | 2         | 0.58%   |
| PreSonus Audio Electronics Studio 24c                                             | 2         | 0.58%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2         | 0.58%   |
| Nvidia High Definition Audio Controller                                           | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 44        | 20.66%  |
| Samsung Electronics | 44        | 20.66%  |
| Kingston            | 25        | 11.74%  |
| Micron Technology   | 21        | 9.86%   |
| Unknown             | 14        | 6.57%   |
| Crucial             | 14        | 6.57%   |
| Corsair             | 11        | 5.16%   |
| G.Skill             | 9         | 4.23%   |
| Patriot             | 6         | 2.82%   |
| Ramaxel Technology  | 4         | 1.88%   |
| Nanya Technology    | 3         | 1.41%   |
| Timetec             | 2         | 0.94%   |
| A-DATA Technology   | 2         | 0.94%   |
| Wodposit            | 1         | 0.47%   |
| Unifosa             | 1         | 0.47%   |
| Transcend           | 1         | 0.47%   |
| Smart               | 1         | 0.47%   |
| S                   | 1         | 0.47%   |
| PNY                 | 1         | 0.47%   |
| OCZ                 | 1         | 0.47%   |
| M                   | 1         | 0.47%   |
| HBS                 | 1         | 0.47%   |
| Goldkey             | 1         | 0.47%   |
| Elpida              | 1         | 0.47%   |
| Aeneon              | 1         | 0.47%   |
| 0194808980CE        | 1         | 0.47%   |
| Unknown             | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s      | 3         | 1.27%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 3         | 1.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 3         | 1.27%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 3         | 1.27%   |
| Patriot RAM 3200 C16 Series 8192MB DIMM DDR4 3266MT/s  | 3         | 1.27%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s   | 3         | 1.27%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 2         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 2         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 2         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 2         | 0.85%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s | 2         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s | 2         | 0.85%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s       | 2         | 0.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s  | 2         | 0.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 0.85%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s | 2         | 0.85%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 2         | 0.85%   |
| Patriot RAM 2400 C15 Series 16GB SODIMM DDR4 2667MT/s  | 2         | 0.85%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 2         | 0.85%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 2         | 0.85%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 2         | 0.85%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s | 2         | 0.85%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2400MT/s | 1         | 0.42%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.42%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s              | 1         | 0.42%   |
| Unknown RAM Module 512MB DIMM DDR                      | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s               | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s       | 1         | 0.42%   |
| Unknown RAM Module 256MB DIMM DDR                      | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s          | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                  | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                | 1         | 0.42%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1         | 0.42%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s             | 1         | 0.42%   |
| Unknown RAM Module 1024MB DIMM DDR                     | 1         | 0.42%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 1         | 0.42%   |
| Unknown RAM M0650120 512MB DIMM DDR 533MT/s            | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 82        | 45.56%  |
| DDR4    | 68        | 37.78%  |
| DDR2    | 12        | 6.67%   |
| SDRAM   | 5         | 2.78%   |
| Unknown | 4         | 2.22%   |
| LPDDR4  | 3         | 1.67%   |
| DDR     | 3         | 1.67%   |
| LPDDR3  | 2         | 1.11%   |
| LPDDR5  | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 50%     |
| DIMM         | 74        | 41.57%  |
| Row Of Chips | 11        | 6.18%   |
| RIMM         | 1         | 0.56%   |
| FB-DIMM      | 1         | 0.56%   |
| Chip         | 1         | 0.56%   |
| Unknown      | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 66        | 32.2%   |
| 4096  | 65        | 31.71%  |
| 2048  | 26        | 12.68%  |
| 16384 | 23        | 11.22%  |
| 32768 | 11        | 5.37%   |
| 1024  | 11        | 5.37%   |
| 512   | 2         | 0.98%   |
| 256   | 1         | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 58        | 29.59%  |
| 3200    | 20        | 10.2%   |
| 2667    | 17        | 8.67%   |
| 1333    | 14        | 7.14%   |
| 2400    | 11        | 5.61%   |
| 2133    | 9         | 4.59%   |
| 1334    | 8         | 4.08%   |
| 667     | 8         | 4.08%   |
| 3600    | 5         | 2.55%   |
| 1866    | 5         | 2.55%   |
| 3266    | 4         | 2.04%   |
| 1800    | 4         | 2.04%   |
| 1066    | 4         | 2.04%   |
| 800     | 4         | 2.04%   |
| 4267    | 3         | 1.53%   |
| Unknown | 3         | 1.53%   |
| 4199    | 2         | 1.02%   |
| 2933    | 2         | 1.02%   |
| 1867    | 2         | 1.02%   |
| 1067    | 2         | 1.02%   |
| 533     | 2         | 1.02%   |
| 6400    | 1         | 0.51%   |
| 3500    | 1         | 0.51%   |
| 3466    | 1         | 0.51%   |
| 3000    | 1         | 0.51%   |
| 2934    | 1         | 0.51%   |
| 2800    | 1         | 0.51%   |
| 2666    | 1         | 0.51%   |
| 2472    | 1         | 0.51%   |
| 1639    | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Ricoh           | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 20.79%  |
| IMC Networks                           | 8         | 7.92%   |
| Microdia                               | 7         | 6.93%   |
| Logitech                               | 7         | 6.93%   |
| Sunplus Innovation Technology          | 6         | 5.94%   |
| Realtek Semiconductor                  | 6         | 5.94%   |
| Syntek                                 | 5         | 4.95%   |
| Suyin                                  | 5         | 4.95%   |
| Quanta                                 | 3         | 2.97%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.97%   |
| Bison Electronics                      | 3         | 2.97%   |
| Apple                                  | 3         | 2.97%   |
| Samsung Electronics                    | 2         | 1.98%   |
| Philips (or NXP)                       | 2         | 1.98%   |
| Microsoft                              | 2         | 1.98%   |
| Lite-On Technology                     | 2         | 1.98%   |
| Xiongmai                               | 1         | 0.99%   |
| ViewSonic                              | 1         | 0.99%   |
| ViewQuest Technologies                 | 1         | 0.99%   |
| Sweex                                  | 1         | 0.99%   |
| Sunplus IT                             | 1         | 0.99%   |
| Silicon Motion                         | 1         | 0.99%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.99%   |
| Ricoh                                  | 1         | 0.99%   |
| Razer USA                              | 1         | 0.99%   |
| MacroSilicon                           | 1         | 0.99%   |
| Intel                                  | 1         | 0.99%   |
| Importek                               | 1         | 0.99%   |
| HRY                                    | 1         | 0.99%   |
| Dynex                                  | 1         | 0.99%   |
| Dell                                   | 1         | 0.99%   |
| Acer                                   | 1         | 0.99%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                          | 5         | 4.9%    |
| Chicony Integrated Camera                         | 5         | 4.9%    |
| IMC Networks Integrated Camera                    | 4         | 3.92%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.94%   |
| Chicony Integrated Camera [ThinkPad]              | 3         | 2.94%   |
| Suyin Asus Integrated Webcam                      | 2         | 1.96%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 1.96%   |
| Sunplus HD WebCam                                 | 2         | 1.96%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2         | 1.96%   |
| Realtek Lenovo EasyCamera                         | 2         | 1.96%   |
| Microdia Integrated_Webcam_HD                     | 2         | 1.96%   |
| Logitech Webcam C270                              | 2         | 1.96%   |
| Chicony HP HD Camera                              | 2         | 1.96%   |
| Chicony HD Webcam                                 | 2         | 1.96%   |
| Chicony HD User Facing                            | 2         | 1.96%   |
| Xiongmai web camera                               | 1         | 0.98%   |
| ViewSonic PC Camera                               | 1         | 0.98%   |
| ViewQuest Ability GABB Webcam                     | 1         | 0.98%   |
| Sweex WC060 Series HD Webcam                      | 1         | 0.98%   |
| Suyin USB 2.0 Camera                              | 1         | 0.98%   |
| Suyin HP Webcam                                   | 1         | 0.98%   |
| Suyin HP TrueVision HD Integrated Webcam          | 1         | 0.98%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1         | 0.98%   |
| Sunplus HD 720P webcam                            | 1         | 0.98%   |
| Sunplus Dell HD Webcam                            | 1         | 0.98%   |
| Silicon Motion WebCam SCB-1100N                   | 1         | 0.98%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1         | 0.98%   |
| Ricoh Sony Vaio Integrated Webcam                 | 1         | 0.98%   |
| Realtek VGA WebCam                                | 1         | 0.98%   |
| Realtek USB Camera                                | 1         | 0.98%   |
| Realtek Integrated_Webcam_HD                      | 1         | 0.98%   |
| Realtek HP Wide Vision HD Camera                  | 1         | 0.98%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1         | 0.98%   |
| Quanta ov9734_techfront_camera                    | 1         | 0.98%   |
| Quanta HP Webcam                                  | 1         | 0.98%   |
| Quanta HP TrueVision HD Camera                    | 1         | 0.98%   |
| Philips (or NXP) Webcam SPC530NC                  | 1         | 0.98%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]        | 1         | 0.98%   |
| Microsoft LifeCam VX-5000                         | 1         | 0.98%   |
| Microsoft LifeCam Cinema                          | 1         | 0.98%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Shenzhen Goodix Technology | 4         | 23.53%  |
| Synaptics                  | 2         | 11.76%  |
| LighTuning Technology      | 1         | 5.88%   |
| Focal-systems.Corp         | 1         | 5.88%   |
| AuthenTec                  | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 11.76%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 11.76%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 11.76%  |
| Shenzhen Goodix Fingerprint Reader                | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5.88%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5.88%   |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5.88%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5.88%   |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 5.88%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Upek        | 3         | 30%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 123       | 70.29%  |
| 1     | 45        | 25.71%  |
| 2     | 6         | 3.43%   |
| 3     | 1         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 30.36%  |
| Graphics card            | 13        | 23.21%  |
| Chipcard                 | 9         | 16.07%  |
| Net/wireless             | 7         | 12.5%   |
| Camera                   | 3         | 5.36%   |
| Sound                    | 2         | 3.57%   |
| Multimedia controller    | 2         | 3.57%   |
| Unassigned class         | 1         | 1.79%   |
| Modem                    | 1         | 1.79%   |
| Communication controller | 1         | 1.79%   |

