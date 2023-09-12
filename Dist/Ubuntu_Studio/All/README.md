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

Total: 213

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [69bf752a4a](https://linux-hardware.org/?probe=69bf752a4a) | Sep 06, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [6ffb2379fa](https://linux-hardware.org/?probe=6ffb2379fa) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ab3c1508f9](https://linux-hardware.org/?probe=ab3c1508f9) | Aug 30, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [17136ed242](https://linux-hardware.org/?probe=17136ed242) | Aug 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [fcfb9cd970](https://linux-hardware.org/?probe=fcfb9cd970) | Aug 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c3490914f6](https://linux-hardware.org/?probe=c3490914f6) | Aug 26, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [499c14b0f7](https://linux-hardware.org/?probe=499c14b0f7) | Aug 26, 2023 |
| Toshiba       | Satellite A505              | Notebook    | [a7b1465809](https://linux-hardware.org/?probe=a7b1465809) | Aug 25, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 83        | 45.36%  |
| Ubuntu Studio 22.04 | 50        | 27.32%  |
| Ubuntu Studio 20.10 | 13        | 7.1%    |
| Ubuntu Studio 23.04 | 10        | 5.46%   |
| Ubuntu Studio 22.10 | 9         | 4.92%   |
| Ubuntu Studio 21.10 | 7         | 3.83%   |
| Ubuntu Studio 21.04 | 5         | 2.73%   |
| Ubuntu Studio 18.04 | 3         | 1.64%   |
| Ubuntu Studio 19.10 | 2         | 1.09%   |
| Ubuntu Studio 16.04 | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 181       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-56-lowlatency   | 5         | 2.67%   |
| 5.15.0-46-lowlatency   | 5         | 2.67%   |
| 5.13.0-28-lowlatency   | 5         | 2.67%   |
| 6.2.0-1009-lowlatency  | 4         | 2.14%   |
| 6.2.0-1003-lowlatency  | 4         | 2.14%   |
| 5.4.0-52-lowlatency    | 4         | 2.14%   |
| 5.4.0-42-lowlatency    | 4         | 2.14%   |
| 5.8.0-55-lowlatency    | 3         | 1.6%    |
| 5.8.0-50-lowlatency    | 3         | 1.6%    |
| 5.8.0-44-lowlatency    | 3         | 1.6%    |
| 5.8.0-25-lowlatency    | 3         | 1.6%    |
| 5.4.0-65-lowlatency    | 3         | 1.6%    |
| 5.4.0-26-lowlatency    | 3         | 1.6%    |
| 5.15.0-67-lowlatency   | 3         | 1.6%    |
| 5.15.0-58-lowlatency   | 3         | 1.6%    |
| 5.15.0-52-lowlatency   | 3         | 1.6%    |
| 5.15.0-50-lowlatency   | 3         | 1.6%    |
| 5.15.0-48-lowlatency   | 3         | 1.6%    |
| 5.15.0-47-lowlatency   | 3         | 1.6%    |
| 5.11.0-44-lowlatency   | 3         | 1.6%    |
| 5.11.0-34-lowlatency   | 3         | 1.6%    |
| 5.8.0-48-lowlatency    | 2         | 1.07%   |
| 5.8.0-29-lowlatency    | 2         | 1.07%   |
| 5.4.0-94-lowlatency    | 2         | 1.07%   |
| 5.4.0-58-lowlatency    | 2         | 1.07%   |
| 5.4.0-56-lowlatency    | 2         | 1.07%   |
| 5.4.0-45-lowlatency    | 2         | 1.07%   |
| 5.19.0-1021-lowlatency | 2         | 1.07%   |
| 5.19.0-1017-lowlatency | 2         | 1.07%   |
| 5.19.0-1015-lowlatency | 2         | 1.07%   |
| 5.19.0-1007-lowlatency | 2         | 1.07%   |
| 5.15.0-79-lowlatency   | 2         | 1.07%   |
| 5.15.0-76-lowlatency   | 2         | 1.07%   |
| 5.15.0-71-lowlatency   | 2         | 1.07%   |
| 5.15.0-69-lowlatency   | 2         | 1.07%   |
| 5.15.0-53-lowlatency   | 2         | 1.07%   |
| 5.15.0-40-lowlatency   | 2         | 1.07%   |
| 5.15.0-30-lowlatency   | 2         | 1.07%   |
| 5.13.0-30-lowlatency   | 2         | 1.07%   |
| 5.11.0-27-lowlatency   | 2         | 1.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 53        | 28.96%  |
| 5.15.0  | 47        | 25.68%  |
| 5.8.0   | 23        | 12.57%  |
| 5.11.0  | 15        | 8.2%    |
| 5.19.0  | 13        | 7.1%    |
| 6.2.0   | 12        | 6.56%   |
| 5.13.0  | 10        | 5.46%   |
| 4.15.0  | 3         | 1.64%   |
| 5.3.0   | 2         | 1.09%   |
| 6.2.8   | 1         | 0.55%   |
| 5.7.6   | 1         | 0.55%   |
| 5.17.1  | 1         | 0.55%   |
| 5.15.6  | 1         | 0.55%   |
| 4.4.0   | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 28.96%  |
| 5.15    | 48        | 26.23%  |
| 5.8     | 23        | 12.57%  |
| 5.11    | 15        | 8.2%    |
| 6.2     | 13        | 7.1%    |
| 5.19    | 13        | 7.1%    |
| 5.13    | 10        | 5.46%   |
| 4.15    | 3         | 1.64%   |
| 5.3     | 2         | 1.09%   |
| 5.7     | 1         | 0.55%   |
| 5.17    | 1         | 0.55%   |
| 4.4     | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 179       | 98.9%   |
| i686    | 1         | 0.55%   |
| aarch64 | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 84        | 46.15%  |
| XFCE            | 80        | 43.96%  |
| GNOME           | 10        | 5.49%   |
| LXQt            | 3         | 1.65%   |
| MATE            | 2         | 1.1%    |
| KDE             | 1         | 0.55%   |
| GNOME Flashback | 1         | 0.55%   |
| Cinnamon        | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 172       | 94.51%  |
| Wayland | 6         | 3.3%    |
| Tty     | 4         | 2.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 77        | 42.54%  |
| TDM     | 49        | 27.07%  |
| LightDM | 42        | 23.2%   |
| GDM     | 11        | 6.08%   |
| LXDM    | 1         | 0.55%   |
| GDM3    | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 74        | 40.66%  |
| fr_FR      | 23        | 12.64%  |
| de_DE      | 13        | 7.14%   |
| en_GB      | 8         | 4.4%    |
| C          | 8         | 4.4%    |
| it_IT      | 7         | 3.85%   |
| pt_BR      | 6         | 3.3%    |
| ru_RU      | 5         | 2.75%   |
| en_CA      | 4         | 2.2%    |
| es_ES      | 3         | 1.65%   |
| en_AU      | 3         | 1.65%   |
| nl_NL      | 2         | 1.1%    |
| es_AR      | 2         | 1.1%    |
| en_AG      | 2         | 1.1%    |
| Unknown    | 2         | 1.1%    |
| sv_SE      | 1         | 0.55%   |
| sk_SK      | 1         | 0.55%   |
| nl_BE      | 1         | 0.55%   |
| nb_NO      | 1         | 0.55%   |
| hu_HU      | 1         | 0.55%   |
| fr_FR.UTF8 | 1         | 0.55%   |
| fr_CH      | 1         | 0.55%   |
| fr_BE      | 1         | 0.55%   |
| es_NI      | 1         | 0.55%   |
| es_MX      | 1         | 0.55%   |
| es_GT      | 1         | 0.55%   |
| es_CR      | 1         | 0.55%   |
| en_NG      | 1         | 0.55%   |
| en_IL      | 1         | 0.55%   |
| en_IE      | 1         | 0.55%   |
| en_DE      | 1         | 0.55%   |
| de_CH      | 1         | 0.55%   |
| de_AT      | 1         | 0.55%   |
| ca_ES      | 1         | 0.55%   |
| ca_AD      | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 106       | 58.56%  |
| BIOS | 75        | 41.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 173       | 95.58%  |
| Overlay | 6         | 3.31%   |
| Xfs     | 1         | 0.55%   |
| Ext2    | 1         | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 117       | 64.64%  |
| MBR  | 64        | 35.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 80.33%  |
| Yes       | 36        | 19.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 54.95%  |
| Yes       | 82        | 45.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 34        | 18.78%  |
| Dell                                 | 26        | 14.36%  |
| Lenovo                               | 25        | 13.81%  |
| Hewlett-Packard                      | 23        | 12.71%  |
| Gigabyte Technology                  | 14        | 7.73%   |
| Apple                                | 7         | 3.87%   |
| Acer                                 | 7         | 3.87%   |
| Toshiba                              | 4         | 2.21%   |
| MSI                                  | 4         | 2.21%   |
| Fujitsu                              | 4         | 2.21%   |
| Intel                                | 3         | 1.66%   |
| ASRock                               | 3         | 1.66%   |
| HUAWEI                               | 2         | 1.1%    |
| AZW                                  | 2         | 1.1%    |
| win element                          | 1         | 0.55%   |
| System76                             | 1         | 0.55%   |
| Sony                                 | 1         | 0.55%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.55%   |
| Samsung Electronics                  | 1         | 0.55%   |
| Razer                                | 1         | 0.55%   |
| Raspberry Pi Foundation              | 1         | 0.55%   |
| Pegatron                             | 1         | 0.55%   |
| Packard Bell                         | 1         | 0.55%   |
| Medion                               | 1         | 0.55%   |
| Intel Client Systems                 | 1         | 0.55%   |
| IBM                                  | 1         | 0.55%   |
| GPU Company                          | 1         | 0.55%   |
| Google                               | 1         | 0.55%   |
| Getac                                | 1         | 0.55%   |
| Foxconn                              | 1         | 0.55%   |
| ECS                                  | 1         | 0.55%   |
| DEPO Computers                       | 1         | 0.55%   |
| COM1                                 | 1         | 0.55%   |
| Clevo                                | 1         | 0.55%   |
| Avell High Performance               | 1         | 0.55%   |
| ATOPNUC                              | 1         | 0.55%   |
| Acidanthera                          | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 2.21%   |
| Lenovo G50-45 80E3                         | 2         | 1.1%    |
| HP Pavilion dv6                            | 2         | 1.1%    |
| Dell OptiPlex 790                          | 2         | 1.1%    |
| ASUS TUF Gaming X570-PLUS                  | 2         | 1.1%    |
| ASUS PRIME X570-PRO                        | 2         | 1.1%    |
| ASUS M4A785-M                              | 2         | 1.1%    |
| Apple iMac18,3                             | 2         | 1.1%    |
| win element MoreFine S500+                 | 1         | 0.55%   |
| Toshiba Satellite L755D                    | 1         | 0.55%   |
| Toshiba Satellite L505                     | 1         | 0.55%   |
| Toshiba Satellite C855                     | 1         | 0.55%   |
| Toshiba Satellite A505                     | 1         | 0.55%   |
| System76 Thelio                            | 1         | 0.55%   |
| Sony VGN-NS31M_W                           | 1         | 0.55%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.55%   |
| Samsung 305V4A/305V5A                      | 1         | 0.55%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.55%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.55%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.55%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.55%   |
| MSI MS-7E02                                | 1         | 0.55%   |
| MSI MS-7C95                                | 1         | 0.55%   |
| MSI MS-7A57                                | 1         | 0.55%   |
| MSI MS-7752                                | 1         | 0.55%   |
| Medion MD34207/C746                        | 1         | 0.55%   |
| Lenovo ThinkPad X250 20CL001LMB            | 1         | 0.55%   |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.55%   |
| Lenovo ThinkPad X230 23245S1               | 1         | 0.55%   |
| Lenovo ThinkPad X1 Yoga Gen 7 21CDCTO1WW   | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW   | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US   | 1         | 0.55%   |
| Lenovo ThinkPad W530 2447IG0               | 1         | 0.55%   |
| Lenovo ThinkPad T530 24296HG               | 1         | 0.55%   |
| Lenovo ThinkPad T520 4243K86               | 1         | 0.55%   |
| Lenovo ThinkPad P50 20EQS0VV03             | 1         | 0.55%   |
| Lenovo ThinkPad L460 20FVS3JK00            | 1         | 0.55%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE       | 1         | 0.55%   |
| Lenovo ThinkCentre M93p 10A8S45S00         | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 13        | 7.18%   |
| Dell OptiPlex                              | 9         | 4.97%   |
| HP Compaq                                  | 8         | 4.42%   |
| Dell Inspiron                              | 8         | 4.42%   |
| Lenovo IdeaPad                             | 5         | 2.76%   |
| Dell Latitude                              | 5         | 2.76%   |
| ASUS ROG                                   | 5         | 2.76%   |
| Acer Aspire                                | 5         | 2.76%   |
| Toshiba Satellite                          | 4         | 2.21%   |
| ASUS All                                   | 4         | 2.21%   |
| HP Pavilion                                | 3         | 1.66%   |
| HP EliteBook                               | 3         | 1.66%   |
| Fujitsu ESPRIMO                            | 3         | 1.66%   |
| Dell Precision                             | 3         | 1.66%   |
| ASUS TUF                                   | 3         | 1.66%   |
| Lenovo G50-45                              | 2         | 1.1%    |
| ASUS VivoBook                              | 2         | 1.1%    |
| ASUS PRIME                                 | 2         | 1.1%    |
| ASUS P8P67                                 | 2         | 1.1%    |
| ASUS M4A785-M                              | 2         | 1.1%    |
| Apple iMac18                               | 2         | 1.1%    |
| win element MoreFine                       | 1         | 0.55%   |
| System76 Thelio                            | 1         | 0.55%   |
| Sony VGN-NS31M                             | 1         | 0.55%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.55%   |
| Samsung 305V4A                             | 1         | 0.55%   |
| Razer Blade                                | 1         | 0.55%   |
| RPi Raspberry                              | 1         | 0.55%   |
| Pegatron FL368AA-UUZ                       | 1         | 0.55%   |
| Packard Bell IMEDIA                        | 1         | 0.55%   |
| MSI MS-7E02                                | 1         | 0.55%   |
| MSI MS-7C95                                | 1         | 0.55%   |
| MSI MS-7A57                                | 1         | 0.55%   |
| MSI MS-7752                                | 1         | 0.55%   |
| Medion MD34207                             | 1         | 0.55%   |
| Lenovo ThinkCentre                         | 1         | 0.55%   |
| Lenovo Legion                              | 1         | 0.55%   |
| Lenovo IdeaPadFlex                         | 1         | 0.55%   |
| Lenovo IdeaCentre                          | 1         | 0.55%   |
| Lenovo G70-80                              | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 21        | 11.6%   |
| 2019 | 16        | 8.84%   |
| 2012 | 16        | 8.84%   |
| 2018 | 13        | 7.18%   |
| 2011 | 13        | 7.18%   |
| 2014 | 12        | 6.63%   |
| 2013 | 12        | 6.63%   |
| 2021 | 11        | 6.08%   |
| 2017 | 10        | 5.52%   |
| 2016 | 10        | 5.52%   |
| 2015 | 10        | 5.52%   |
| 2009 | 9         | 4.97%   |
| 2010 | 8         | 4.42%   |
| 2008 | 7         | 3.87%   |
| 2022 | 6         | 3.31%   |
| 2007 | 4         | 2.21%   |
| 2005 | 3         | 1.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 84        | 46.41%  |
| Notebook       | 81        | 44.75%  |
| All in one     | 7         | 3.87%   |
| Mini pc        | 5         | 2.76%   |
| Convertible    | 3         | 1.66%   |
| System on chip | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 171       | 94.48%  |
| Enabled  | 10        | 5.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 98.9%   |
| Yes  | 2         | 1.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 28.57%  |
| 16.01-24.0  | 37        | 20.33%  |
| 8.01-16.0   | 36        | 19.78%  |
| 32.01-64.0  | 22        | 12.09%  |
| 3.01-4.0    | 16        | 8.79%   |
| 64.01-256.0 | 9         | 4.95%   |
| 1.01-2.0    | 4         | 2.2%    |
| 24.01-32.0  | 3         | 1.65%   |
| 2.01-3.0    | 3         | 1.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 58        | 31.35%  |
| 2.01-3.0   | 45        | 24.32%  |
| 4.01-8.0   | 35        | 18.92%  |
| 3.01-4.0   | 30        | 16.22%  |
| 8.01-16.0  | 12        | 6.49%   |
| 0.51-1.0   | 4         | 2.16%   |
| 24.01-32.0 | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 94        | 51.65%  |
| 2      | 62        | 34.07%  |
| 3      | 10        | 5.49%   |
| 4      | 5         | 2.75%   |
| 7      | 3         | 1.65%   |
| 5      | 3         | 1.65%   |
| 0      | 2         | 1.1%    |
| 16     | 1         | 0.55%   |
| 11     | 1         | 0.55%   |
| 10     | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 55.49%  |
| Yes       | 81        | 44.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 90.06%  |
| No        | 18        | 9.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 73.48%  |
| No        | 48        | 26.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 55.25%  |
| No        | 81        | 44.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 45        | 24.86%  |
| France                 | 23        | 12.71%  |
| Germany                | 20        | 11.05%  |
| Italy                  | 11        | 6.08%   |
| Russia                 | 7         | 3.87%   |
| Brazil                 | 7         | 3.87%   |
| Spain                  | 6         | 3.31%   |
| UK                     | 5         | 2.76%   |
| Canada                 | 5         | 2.76%   |
| Austria                | 5         | 2.76%   |
| Belgium                | 4         | 2.21%   |
| Australia              | 4         | 2.21%   |
| Sweden                 | 3         | 1.66%   |
| Netherlands            | 3         | 1.66%   |
| Taiwan                 | 2         | 1.1%    |
| Switzerland            | 2         | 1.1%    |
| Romania                | 2         | 1.1%    |
| Norway                 | 2         | 1.1%    |
| Mexico                 | 2         | 1.1%    |
| Ivory Coast            | 2         | 1.1%    |
| Costa Rica             | 2         | 1.1%    |
| Argentina              | 2         | 1.1%    |
| Yemen                  | 1         | 0.55%   |
| Turkey                 | 1         | 0.55%   |
| South Africa           | 1         | 0.55%   |
| Slovakia               | 1         | 0.55%   |
| Poland                 | 1         | 0.55%   |
| Peru                   | 1         | 0.55%   |
| Nigeria                | 1         | 0.55%   |
| Nicaragua              | 1         | 0.55%   |
| Luxembourg             | 1         | 0.55%   |
| Kenya                  | 1         | 0.55%   |
| Israel                 | 1         | 0.55%   |
| Indonesia              | 1         | 0.55%   |
| Hungary                | 1         | 0.55%   |
| Guatemala              | 1         | 0.55%   |
| Finland                | 1         | 0.55%   |
| Bulgaria               | 1         | 0.55%   |
| Bosnia and Herzegovina | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Vienna        | 3         | 1.64%   |
| Stockholm     | 3         | 1.64%   |
| Paris         | 3         | 1.64%   |
| Madrid        | 3         | 1.64%   |
| Houston       | 3         | 1.64%   |
| Turin         | 2         | 1.09%   |
| Stuttgart     | 2         | 1.09%   |
| San Francisco | 2         | 1.09%   |
| Moscow        | 2         | 1.09%   |
| Montreal      | 2         | 1.09%   |
| Mississauga   | 2         | 1.09%   |
| Hamburg       | 2         | 1.09%   |
| Groningen     | 2         | 1.09%   |
| Denver        | 2         | 1.09%   |
| Bucharest     | 2         | 1.09%   |
| Béziers      | 2         | 1.09%   |
| Abidjan       | 2         | 1.09%   |
| Zanesville    | 1         | 0.55%   |
| Yonkers       | 1         | 0.55%   |
| Yekaterinburg | 1         | 0.55%   |
| Wroclaw       | 1         | 0.55%   |
| Woonsocket    | 1         | 0.55%   |
| Woodland Park | 1         | 0.55%   |
| Wildenfels    | 1         | 0.55%   |
| West Mifflin  | 1         | 0.55%   |
| Warner Robins | 1         | 0.55%   |
| Villefontaine | 1         | 0.55%   |
| Verviers      | 1         | 0.55%   |
| Velleron      | 1         | 0.55%   |
| Toulouse      | 1         | 0.55%   |
| Tilburg       | 1         | 0.55%   |
| Taylor        | 1         | 0.55%   |
| Tarragona     | 1         | 0.55%   |
| Taipei        | 1         | 0.55%   |
| Taichung      | 1         | 0.55%   |
| Sunderland    | 1         | 0.55%   |
| Stabekk       | 1         | 0.55%   |
| St Petersburg | 1         | 0.55%   |
| Sofia         | 1         | 0.55%   |
| Sleman        | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 47        | 57     | 16.55%  |
| Samsung Electronics   | 46        | 59     | 16.2%   |
| Seagate               | 33        | 57     | 11.62%  |
| Toshiba               | 18        | 19     | 6.34%   |
| SanDisk               | 18        | 19     | 6.34%   |
| Hitachi               | 10        | 11     | 3.52%   |
| Kingston              | 9         | 10     | 3.17%   |
| Intel                 | 9         | 12     | 3.17%   |
| Crucial               | 8         | 8      | 2.82%   |
| Unknown               | 7         | 7      | 2.46%   |
| SK hynix              | 5         | 6      | 1.76%   |
| Phison                | 5         | 5      | 1.76%   |
| HGST                  | 5         | 6      | 1.76%   |
| PNY                   | 4         | 4      | 1.41%   |
| Micron Technology     | 4         | 4      | 1.41%   |
| Team                  | 3         | 3      | 1.06%   |
| SPCC                  | 3         | 3      | 1.06%   |
| JMicron Technology    | 3         | 3      | 1.06%   |
| Intenso               | 3         | 3      | 1.06%   |
| China                 | 3         | 3      | 1.06%   |
| ASMT                  | 3         | 3      | 1.06%   |
| Apple                 | 3         | 5      | 1.06%   |
| A-DATA Technology     | 3         | 4      | 1.06%   |
| KIOXIA                | 2         | 2      | 0.7%    |
| Fujitsu               | 2         | 2      | 0.7%    |
| Corsair               | 2         | 3      | 0.7%    |
| BHT                   | 2         | 2      | 0.7%    |
| XPG                   | 1         | 1      | 0.35%   |
| Wibtek                | 1         | 1      | 0.35%   |
| USB 3.0               | 1         | 2      | 0.35%   |
| Union Memory          | 1         | 1      | 0.35%   |
| UMIS                  | 1         | 1      | 0.35%   |
| TO Exter              | 1         | 1      | 0.35%   |
| SCY                   | 1         | 1      | 0.35%   |
| Reeinno               | 1         | 1      | 0.35%   |
| Realtek Semiconductor | 1         | 1      | 0.35%   |
| Realtek               | 1         | 1      | 0.35%   |
| Phison Electronics    | 1         | 1      | 0.35%   |
| Patriot               | 1         | 1      | 0.35%   |
| OCZ                   | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 1.26%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 1.26%   |
| Seagate ST2000DM001-1ER164 2TB            | 4         | 1.26%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 1.26%   |
| Seagate ST2000DM008-2FR102 2TB            | 3         | 0.95%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 0.95%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 0.95%   |
| Crucial CT500MX500SSD1 500GB              | 3         | 0.95%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 2         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.63%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.63%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.63%   |
| Toshiba HDWD130 3TB                       | 2         | 0.63%   |
| Toshiba DT01ACA050 500GB                  | 2         | 0.63%   |
| Team T253X6001T 1024GB SSD                | 2         | 0.63%   |
| SPCC Solid State Disk 256GB               | 2         | 0.63%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.63%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.63%   |
| Seagate Expansion Desk 2TB                | 2         | 0.63%   |
| Seagate Expansion 2TB                     | 2         | 0.63%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.63%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 0.63%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.63%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.63%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.63%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.63%   |
| Samsung HD753LJ 752GB                     | 2         | 0.63%   |
| Phison Sabrent 256GB                      | 2         | 0.63%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 0.63%   |
| JMicron Generic 1TB                       | 2         | 0.63%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 0.63%   |
| China SSD 1TB                             | 2         | 0.63%   |
| Apple SSD SM0032L 32GB                    | 2         | 0.63%   |
| Apple HDD ST1000DM003 1TB                 | 2         | 0.63%   |
| XPG GAMMIX S7 1TB                         | 1         | 0.32%   |
| Wibtek W800S 512GB SSD                    | 1         | 0.32%   |
| WDC WDS512G1X0C-00ENX0 512GB              | 1         | 0.32%   |
| WDC WDS100T2G0A-00JH30 1TB SSD            | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 36        | 46     | 31.58%  |
| Seagate             | 32        | 55     | 28.07%  |
| Toshiba             | 17        | 18     | 14.91%  |
| Hitachi             | 10        | 11     | 8.77%   |
| Samsung Electronics | 5         | 5      | 4.39%   |
| HGST                | 5         | 6      | 4.39%   |
| Fujitsu             | 2         | 2      | 1.75%   |
| Apple               | 2         | 2      | 1.75%   |
| USB 3.0             | 1         | 2      | 0.88%   |
| Unknown             | 1         | 1      | 0.88%   |
| Maxtor              | 1         | 1      | 0.88%   |
| Inateck             | 1         | 1      | 0.88%   |
| ASMT                | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 31     | 25.24%  |
| SanDisk             | 15        | 16     | 14.56%  |
| Kingston            | 8         | 9      | 7.77%   |
| Crucial             | 8         | 8      | 7.77%   |
| WDC                 | 4         | 4      | 3.88%   |
| PNY                 | 4         | 4      | 3.88%   |
| SPCC                | 3         | 3      | 2.91%   |
| Micron Technology   | 3         | 3      | 2.91%   |
| Intenso             | 3         | 3      | 2.91%   |
| China               | 3         | 3      | 2.91%   |
| Team                | 2         | 2      | 1.94%   |
| JMicron Technology  | 2         | 2      | 1.94%   |
| BHT                 | 2         | 2      | 1.94%   |
| ASMT                | 2         | 2      | 1.94%   |
| A-DATA Technology   | 2         | 2      | 1.94%   |
| Wibtek              | 1         | 1      | 0.97%   |
| Toshiba             | 1         | 1      | 0.97%   |
| TO Exter            | 1         | 1      | 0.97%   |
| SK hynix            | 1         | 1      | 0.97%   |
| SCY                 | 1         | 1      | 0.97%   |
| Reeinno             | 1         | 1      | 0.97%   |
| Patriot             | 1         | 1      | 0.97%   |
| OCZ                 | 1         | 1      | 0.97%   |
| NGFF                | 1         | 1      | 0.97%   |
| Leven               | 1         | 1      | 0.97%   |
| KingSpec            | 1         | 1      | 0.97%   |
| Intel               | 1         | 1      | 0.97%   |
| Integral            | 1         | 1      | 0.97%   |
| EDGE eMe            | 1         | 1      | 0.97%   |
| Dogfish             | 1         | 1      | 0.97%   |
| Corsair             | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 151    | 37.92%  |
| SSD     | 84        | 110    | 35%     |
| NVMe    | 54        | 72     | 22.5%   |
| MMC     | 8         | 9      | 3.33%   |
| Unknown | 3         | 3      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 139       | 241    | 63.47%  |
| NVMe | 54        | 71     | 24.66%  |
| SAS  | 18        | 24     | 8.22%   |
| MMC  | 8         | 9      | 3.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 101       | 131    | 51.79%  |
| 0.51-1.0   | 56        | 68     | 28.72%  |
| 1.01-2.0   | 21        | 25     | 10.77%  |
| 3.01-4.0   | 8         | 10     | 4.1%    |
| 4.01-10.0  | 6         | 23     | 3.08%   |
| 2.01-3.0   | 3         | 4      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 27.17%  |
| 501-1000       | 33        | 17.93%  |
| 251-500        | 32        | 17.39%  |
| 1001-2000      | 26        | 14.13%  |
| More than 3000 | 15        | 8.15%   |
| 51-100         | 11        | 5.98%   |
| 21-50          | 9         | 4.89%   |
| 1-20           | 6         | 3.26%   |
| 2001-3000      | 2         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 57        | 30.81%  |
| 21-50          | 32        | 17.3%   |
| 101-250        | 29        | 15.68%  |
| 251-500        | 18        | 9.73%   |
| 51-100         | 15        | 8.11%   |
| 501-1000       | 13        | 7.03%   |
| More than 3000 | 9         | 4.86%   |
| 1001-2000      | 8         | 4.32%   |
| 2001-3000      | 4         | 2.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 7.32%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 3      | 4.88%   |
| Samsung Electronics HD753LJ 752GB                   | 2         | 2      | 4.88%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2.44%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1      | 2.44%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 2.44%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.44%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 2.44%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 2.44%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 2.44%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 2.44%   |
| WDC WD10EAVS-32D7B1 1TB                             | 1         | 1      | 2.44%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2.44%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 2.44%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 2.44%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.44%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 2.44%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.44%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 2.44%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 2.44%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 2.44%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 2.44%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 2.44%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 2.44%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.44%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 2.44%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 2.44%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.44%   |
| Hitachi HDS721010CLA332 1TB                         | 1         | 1      | 2.44%   |
| Hitachi HDS5C1010CLA382 1TB                         | 1         | 1      | 2.44%   |
| HGST HTS721010A9 1TB                                | 1         | 1      | 2.44%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 1      | 2.44%   |
| A-DATA Technology SP550 240GB SSD                   | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 27.5%   |
| WDC                 | 9         | 10     | 22.5%   |
| Samsung Electronics | 7         | 8      | 17.5%   |
| Hitachi             | 4         | 4      | 10%     |
| Toshiba             | 3         | 3      | 7.5%    |
| A-DATA Technology   | 2         | 2      | 5%      |
| Micron Technology   | 1         | 1      | 2.5%    |
| KingSpec            | 1         | 1      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 34.38%  |
| WDC                 | 9         | 10     | 28.13%  |
| Samsung Electronics | 4         | 4      | 12.5%   |
| Hitachi             | 4         | 4      | 12.5%   |
| Toshiba             | 3         | 3      | 9.38%   |
| HGST                | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 38     | 78.95%  |
| SSD  | 7         | 8      | 18.42%  |
| NVMe | 1         | 1      | 2.63%   |

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
| Works    | 153       | 264    | 70.51%  |
| Malfunc  | 38        | 47     | 17.51%  |
| Detected | 24        | 32     | 11.06%  |
| Failed   | 2         | 2      | 0.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 124       | 52.1%   |
| AMD                          | 42        | 17.65%  |
| Samsung Electronics          | 20        | 8.4%    |
| SanDisk                      | 9         | 3.78%   |
| Phison Electronics           | 8         | 3.36%   |
| Marvell Technology Group     | 5         | 2.1%    |
| ASMedia Technology           | 5         | 2.1%    |
| SK hynix                     | 4         | 1.68%   |
| Nvidia                       | 3         | 1.26%   |
| Union Memory (Shenzhen)      | 2         | 0.84%   |
| Realtek Semiconductor        | 2         | 0.84%   |
| JMicron Technology           | 2         | 0.84%   |
| VIA Technologies             | 1         | 0.42%   |
| Toshiba America Info Systems | 1         | 0.42%   |
| Silicon Image                | 1         | 0.42%   |
| Seagate Technology           | 1         | 0.42%   |
| Micron Technology            | 1         | 0.42%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.42%   |
| LSI Logic / Symbios Logic    | 1         | 0.42%   |
| KIOXIA                       | 1         | 0.42%   |
| Kingston Technology Company  | 1         | 0.42%   |
| Apple                        | 1         | 0.42%   |
| ADATA Technology             | 1         | 0.42%   |
| Adaptec                      | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28        | 10.07%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 4.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 4.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 3.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 2.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 1.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.8%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.44%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 1.08%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.72%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.72%   |
| Samsung NVMe SSD SM0032L                                                       | 2         | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.72%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.72%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.72%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2         | 0.72%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2         | 0.72%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.72%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.72%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 140       | 58.33%  |
| NVMe | 55        | 22.92%  |
| IDE  | 26        | 10.83%  |
| RAID | 15        | 6.25%   |
| SAS  | 3         | 1.25%   |
| SCSI | 1         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 131       | 72.38%  |
| AMD    | 49        | 27.07%  |
| ARM    | 1         | 0.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 1.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 1.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.66%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.66%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 1.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 1.1%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 1.1%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 1.1%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 1.1%    |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 1.1%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 1.1%    |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 1.1%    |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 1.1%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.1%    |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 1.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.1%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.1%    |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 1.1%    |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 1.1%    |
| AMD Ryzen 7 5825U with Radeon Graphics  | 2         | 1.1%    |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 1.1%    |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 1.1%    |
| AMD Phenom II X4 945 Processor          | 2         | 1.1%    |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.55%   |
| Intel Xeon CPU E5420 @ 2.50GHz          | 1         | 0.55%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1         | 0.55%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.55%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.55%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.55%   |
| Intel Pentium D CPU 3.40GHz             | 1         | 0.55%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.55%   |
| Intel Pentium 4 CPU 3.20GHz             | 1         | 0.55%   |
| Intel Pentium 4 CPU 2.80GHz             | 1         | 0.55%   |
| Intel Genuine CPU U2300 @ 1.20GHz       | 1         | 0.55%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1         | 0.55%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 0.55%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.55%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 1         | 0.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 44        | 24.31%  |
| Intel Core i7          | 42        | 23.2%   |
| Intel Core i3          | 12        | 6.63%   |
| Other                  | 10        | 5.52%   |
| AMD Ryzen 5            | 10        | 5.52%   |
| AMD Ryzen 7            | 8         | 4.42%   |
| Intel Core 2 Duo       | 6         | 3.31%   |
| Intel Celeron          | 5         | 2.76%   |
| AMD Ryzen 9            | 5         | 2.76%   |
| Intel Xeon             | 4         | 2.21%   |
| Intel Core i9          | 4         | 2.21%   |
| AMD Phenom II X4       | 4         | 2.21%   |
| AMD E                  | 3         | 1.66%   |
| Intel Pentium 4        | 2         | 1.1%    |
| AMD Ryzen 3            | 2         | 1.1%    |
| AMD FX                 | 2         | 1.1%    |
| AMD Athlon II X2       | 2         | 1.1%    |
| AMD A4                 | 2         | 1.1%    |
| Intel Pentium Dual     | 1         | 0.55%   |
| Intel Pentium D        | 1         | 0.55%   |
| Intel Pentium          | 1         | 0.55%   |
| Intel Genuine          | 1         | 0.55%   |
| Intel Core 2           | 1         | 0.55%   |
| AMD Ryzen Threadripper | 1         | 0.55%   |
| AMD Ryzen 3 PRO        | 1         | 0.55%   |
| AMD E2                 | 1         | 0.55%   |
| AMD E1                 | 1         | 0.55%   |
| AMD Athlon X4          | 1         | 0.55%   |
| AMD Athlon Dual Core   | 1         | 0.55%   |
| AMD Athlon 64 X2       | 1         | 0.55%   |
| AMD A6                 | 1         | 0.55%   |
| AMD A10                | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 75        | 41.44%  |
| 2      | 61        | 33.7%   |
| 6      | 21        | 11.6%   |
| 8      | 12        | 6.63%   |
| 12     | 3         | 1.66%   |
| 10     | 3         | 1.66%   |
| 1      | 3         | 1.66%   |
| 16     | 2         | 1.1%    |
| 32     | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 180       | 99.45%  |
| 2      | 1         | 0.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 116       | 64.09%  |
| 1      | 65        | 35.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 180       | 99.45%  |
| 32-bit         | 1         | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 13.19%  |
| 0x306c3    | 14        | 7.69%   |
| 0x206a7    | 14        | 7.69%   |
| 0x306a9    | 13        | 7.14%   |
| 0x906ea    | 8         | 4.4%    |
| 0x506e3    | 5         | 2.75%   |
| 0x306d4    | 5         | 2.75%   |
| 0x806ea    | 4         | 2.2%    |
| 0x806c1    | 4         | 2.2%    |
| 0x08701021 | 4         | 2.2%    |
| 0x08600104 | 4         | 2.2%    |
| 0xa0652    | 3         | 1.65%   |
| 0x906e9    | 3         | 1.65%   |
| 0x706e5    | 3         | 1.65%   |
| 0x406e3    | 3         | 1.65%   |
| 0x106e5    | 3         | 1.65%   |
| 0x10676    | 3         | 1.65%   |
| 0x0a50000d | 3         | 1.65%   |
| 0x08108109 | 3         | 1.65%   |
| 0x010000c8 | 3         | 1.65%   |
| 0xf41      | 2         | 1.1%    |
| 0xa0655    | 2         | 1.1%    |
| 0x906ed    | 2         | 1.1%    |
| 0x6fd      | 2         | 1.1%    |
| 0x40651    | 2         | 1.1%    |
| 0x206d7    | 2         | 1.1%    |
| 0x0a50000c | 2         | 1.1%    |
| 0x08600106 | 2         | 1.1%    |
| 0x07030105 | 2         | 1.1%    |
| 0x010000b6 | 2         | 1.1%    |
| 0xf65      | 1         | 0.55%   |
| 0x906ec    | 1         | 0.55%   |
| 0x906a3    | 1         | 0.55%   |
| 0x90675    | 1         | 0.55%   |
| 0x806e9    | 1         | 0.55%   |
| 0x706a1    | 1         | 0.55%   |
| 0x6fb      | 1         | 0.55%   |
| 0x6f6      | 1         | 0.55%   |
| 0x506ca    | 1         | 0.55%   |
| 0x506c9    | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 12.15%  |
| Haswell          | 18        | 9.94%   |
| SandyBridge      | 16        | 8.84%   |
| Zen 2            | 15        | 8.29%   |
| Skylake          | 14        | 7.73%   |
| IvyBridge        | 14        | 7.73%   |
| Zen 3            | 7         | 3.87%   |
| Penryn           | 6         | 3.31%   |
| K10              | 6         | 3.31%   |
| Broadwell        | 6         | 3.31%   |
| Nehalem          | 5         | 2.76%   |
| CometLake        | 5         | 2.76%   |
| Westmere         | 4         | 2.21%   |
| TigerLake        | 4         | 2.21%   |
| IceLake          | 4         | 2.21%   |
| Core             | 4         | 2.21%   |
| Zen+             | 3         | 1.66%   |
| Puma             | 3         | 1.66%   |
| Piledriver       | 3         | 1.66%   |
| NetBurst         | 3         | 1.66%   |
| Excavator        | 3         | 1.66%   |
| Unknown          | 3         | 1.66%   |
| K8 Hammer        | 2         | 1.1%    |
| Goldmont         | 2         | 1.1%    |
| Bobcat           | 2         | 1.1%    |
| Alderlake Hybrid | 2         | 1.1%    |
| Zen              | 1         | 0.55%   |
| Steamroller      | 1         | 0.55%   |
| Silvermont       | 1         | 0.55%   |
| K10 Llano        | 1         | 0.55%   |
| Goldmont plus    | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 43.6%   |
| Nvidia | 68        | 32.23%  |
| AMD    | 51        | 24.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8         | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 3.24%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 3.24%   |
| AMD Renoir                                                                  | 7         | 3.24%   |
| Intel HD Graphics 530                                                       | 6         | 2.78%   |
| Intel HD Graphics 5500                                                      | 5         | 2.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 2.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 1.85%   |
| Nvidia TU117M                                                               | 3         | 1.39%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.39%   |
| Intel UHD Graphics 620                                                      | 3         | 1.39%   |
| Intel Iris Plus Graphics G7                                                 | 3         | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.39%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.93%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 0.93%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 0.93%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.93%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 0.93%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.93%   |
| Intel HD Graphics 630                                                       | 2         | 0.93%   |
| Intel HD Graphics 500                                                       | 2         | 0.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.93%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 0.93%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 0.93%   |
| AMD Wrestler [Radeon HD 6310]                                               | 2         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 64        | 35.36%  |
| 1 x Nvidia     | 43        | 23.76%  |
| 1 x AMD        | 42        | 23.2%   |
| Intel + Nvidia | 20        | 11.05%  |
| AMD + Nvidia   | 4         | 2.21%   |
| Intel + AMD    | 3         | 1.66%   |
| 2 x AMD        | 2         | 1.1%    |
| Other          | 1         | 0.55%   |
| 2 x Nvidia     | 1         | 0.55%   |
| 2 x Intel      | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 146       | 80.22%  |
| Proprietary | 34        | 18.68%  |
| Unknown     | 2         | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 42.86%  |
| 1.01-2.0   | 26        | 14.29%  |
| 0.01-0.5   | 26        | 14.29%  |
| 0.51-1.0   | 20        | 10.99%  |
| 3.01-4.0   | 14        | 7.69%   |
| 7.01-8.0   | 7         | 3.85%   |
| 5.01-6.0   | 5         | 2.75%   |
| 8.01-16.0  | 4         | 2.2%    |
| 2.01-3.0   | 1         | 0.55%   |
| 16.01-24.0 | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 28        | 13.73%  |
| LG Display              | 21        | 10.29%  |
| AU Optronics            | 16        | 7.84%   |
| Goldstar                | 14        | 6.86%   |
| Hewlett-Packard         | 12        | 5.88%   |
| Dell                    | 12        | 5.88%   |
| BOE                     | 12        | 5.88%   |
| Chimei Innolux          | 11        | 5.39%   |
| Acer                    | 11        | 5.39%   |
| Philips                 | 10        | 4.9%    |
| Ancor Communications    | 7         | 3.43%   |
| Apple                   | 5         | 2.45%   |
| Lenovo                  | 4         | 1.96%   |
| BenQ                    | 3         | 1.47%   |
| AOC                     | 3         | 1.47%   |
| Sharp                   | 2         | 0.98%   |
| ONN                     | 2         | 0.98%   |
| Iiyama                  | 2         | 0.98%   |
| Hannspree               | 2         | 0.98%   |
| Fujitsu Siemens         | 2         | 0.98%   |
| Eizo                    | 2         | 0.98%   |
| Chi Mei Optoelectronics | 2         | 0.98%   |
| ASUSTek Computer        | 2         | 0.98%   |
| ViewSonic               | 1         | 0.49%   |
| VIE                     | 1         | 0.49%   |
| Unknown                 | 1         | 0.49%   |
| UGD                     | 1         | 0.49%   |
| TVT                     | 1         | 0.49%   |
| Targa Visionary         | 1         | 0.49%   |
| Sony                    | 1         | 0.49%   |
| Seiki                   | 1         | 0.49%   |
| Onkyo                   | 1         | 0.49%   |
| NEC Computers           | 1         | 0.49%   |
| MSI                     | 1         | 0.49%   |
| Medion                  | 1         | 0.49%   |
| LG Philips              | 1         | 0.49%   |
| KTC                     | 1         | 0.49%   |
| HannStar                | 1         | 0.49%   |
| DENON                   | 1         | 0.49%   |
| CPT                     | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 2         | 0.93%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.93%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.93%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 2         | 0.93%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.93%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.93%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.93%   |
| Apple iMac APPAE11 3840x2160 597x336mm 27.0-inch                      | 2         | 0.93%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2         | 0.93%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1         | 0.47%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1         | 0.47%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1         | 0.47%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch               | 1         | 0.47%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1         | 0.47%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1         | 0.47%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.47%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1         | 0.47%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.47%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch   | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.47%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch  | 1         | 0.47%   |
| Samsung Electronics SMB2330HD SAM0710 1920x1080 510x290mm 23.1-inch   | 1         | 0.47%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch   | 1         | 0.47%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.47%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.47%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1         | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 92        | 47.92%  |
| 1366x768 (WXGA)    | 27        | 14.06%  |
| 3840x2160 (4K)     | 18        | 9.38%   |
| 1280x1024 (SXGA)   | 10        | 5.21%   |
| 1680x1050 (WSXGA+) | 9         | 4.69%   |
| 1600x900 (HD+)     | 7         | 3.65%   |
| 1920x1200 (WUXGA)  | 6         | 3.13%   |
| 2560x1440 (QHD)    | 5         | 2.6%    |
| 1440x900 (WXGA+)   | 4         | 2.08%   |
| 3440x1440          | 2         | 1.04%   |
| 1360x768           | 2         | 1.04%   |
| 1280x800 (WXGA)    | 2         | 1.04%   |
| Unknown            | 2         | 1.04%   |
| 5760x2160          | 1         | 0.52%   |
| 3280x1080          | 1         | 0.52%   |
| 2880x1800          | 1         | 0.52%   |
| 2160x1440          | 1         | 0.52%   |
| 1600x1200          | 1         | 0.52%   |
| 1400x1050          | 1         | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 49        | 24.02%  |
| 27      | 19        | 9.31%   |
| 23      | 19        | 9.31%   |
| 21      | 18        | 8.82%   |
| 24      | 17        | 8.33%   |
| 13      | 11        | 5.39%   |
| 14      | 10        | 4.9%    |
| 19      | 9         | 4.41%   |
| 17      | 9         | 4.41%   |
| 22      | 7         | 3.43%   |
| 31      | 6         | 2.94%   |
| 18      | 6         | 2.94%   |
| 12      | 5         | 2.45%   |
| 20      | 4         | 1.96%   |
| Unknown | 3         | 1.47%   |
| 84      | 2         | 0.98%   |
| 65      | 1         | 0.49%   |
| 54      | 1         | 0.49%   |
| 52      | 1         | 0.49%   |
| 50      | 1         | 0.49%   |
| 43      | 1         | 0.49%   |
| 34      | 1         | 0.49%   |
| 32      | 1         | 0.49%   |
| 26      | 1         | 0.49%   |
| 16      | 1         | 0.49%   |
| 11      | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 69        | 34.67%  |
| 501-600     | 51        | 25.63%  |
| 401-500     | 38        | 19.1%   |
| 201-300     | 12        | 6.03%   |
| 351-400     | 9         | 4.52%   |
| 601-700     | 8         | 4.02%   |
| 1001-1500   | 4         | 2.01%   |
| Unknown     | 3         | 1.51%   |
| 701-800     | 2         | 1.01%   |
| 1501-2000   | 2         | 1.01%   |
| 901-1000    | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 76.09%  |
| 16/10   | 27        | 14.67%  |
| 5/4     | 9         | 4.89%   |
| Unknown | 3         | 1.63%   |
| 4/3     | 2         | 1.09%   |
| 3/2     | 2         | 1.09%   |
| 21/9    | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 24.62%  |
| 201-250        | 47        | 23.62%  |
| 301-350        | 20        | 10.05%  |
| 81-90          | 16        | 8.04%   |
| 151-200        | 15        | 7.54%   |
| 141-150        | 12        | 6.03%   |
| 351-500        | 8         | 4.02%   |
| 251-300        | 7         | 3.52%   |
| More than 1000 | 6         | 3.02%   |
| 71-80          | 5         | 2.51%   |
| 61-70          | 5         | 2.51%   |
| Unknown        | 3         | 1.51%   |
| 121-130        | 2         | 1.01%   |
| 51-60          | 1         | 0.5%    |
| 131-140        | 1         | 0.5%    |
| 111-120        | 1         | 0.5%    |
| 501-1000       | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 79        | 40.93%  |
| 121-160       | 46        | 23.83%  |
| 101-120       | 46        | 23.83%  |
| 161-240       | 15        | 7.77%   |
| Unknown       | 3         | 1.55%   |
| More than 240 | 2         | 1.04%   |
| 1-50          | 2         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 140       | 76.5%   |
| 2     | 40        | 21.86%  |
| 3     | 2         | 1.09%   |
| 0     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 99        | 35.87%  |
| Realtek Semiconductor             | 98        | 35.51%  |
| Qualcomm Atheros                  | 28        | 10.14%  |
| Broadcom                          | 15        | 5.43%   |
| MediaTek                          | 5         | 1.81%   |
| ASIX Electronics                  | 4         | 1.45%   |
| TP-Link                           | 3         | 1.09%   |
| Nvidia                            | 3         | 1.09%   |
| Broadcom Limited                  | 3         | 1.09%   |
| Ralink                            | 2         | 0.72%   |
| Ericsson Business Mobile Networks | 2         | 0.72%   |
| Aquantia                          | 2         | 0.72%   |
| ZyDAS                             | 1         | 0.36%   |
| Wacom                             | 1         | 0.36%   |
| Ralink Technology                 | 1         | 0.36%   |
| Qualcomm Atheros Communications   | 1         | 0.36%   |
| NetGear                           | 1         | 0.36%   |
| Motorola PCS                      | 1         | 0.36%   |
| Microsoft                         | 1         | 0.36%   |
| Marvell Technology Group          | 1         | 0.36%   |
| InterBiometrics                   | 1         | 0.36%   |
| Input Club                        | 1         | 0.36%   |
| Huawei Technologies               | 1         | 0.36%   |
| DisplayLink                       | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68        | 21.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17        | 5.26%   |
| Intel Wireless 7265                                                           | 10        | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 7         | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 1.86%   |
| Intel I211 Gigabit Network Connection                                         | 6         | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6         | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 1.55%   |
| Intel Wireless-AC 9260                                                        | 5         | 1.55%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.55%   |
| Realtek 802.11ac NIC                                                          | 4         | 1.24%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 1.24%   |
| Intel Wireless 8260                                                           | 4         | 1.24%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 0.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 3         | 0.93%   |
| Intel Wireless 7260                                                           | 3         | 0.93%   |
| Intel WiFi Link 5100                                                          | 3         | 0.93%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 0.93%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 0.93%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 3         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.62%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 0.62%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.62%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.62%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 47.79%  |
| Realtek Semiconductor           | 24        | 17.65%  |
| Qualcomm Atheros                | 22        | 16.18%  |
| Broadcom                        | 9         | 6.62%   |
| MediaTek                        | 4         | 2.94%   |
| TP-Link                         | 3         | 2.21%   |
| Ralink                          | 2         | 1.47%   |
| ZyDAS                           | 1         | 0.74%   |
| Wacom                           | 1         | 0.74%   |
| Ralink Technology               | 1         | 0.74%   |
| Qualcomm Atheros Communications | 1         | 0.74%   |
| NetGear                         | 1         | 0.74%   |
| Microsoft                       | 1         | 0.74%   |
| Broadcom Limited                | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 10        | 7.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 4.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6         | 4.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 3.65%   |
| Intel Wireless-AC 9260                                                        | 5         | 3.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 3.65%   |
| Realtek 802.11ac NIC                                                          | 4         | 2.92%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 2.92%   |
| Intel Wireless 8260                                                           | 4         | 2.92%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 2.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 2.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 2.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 3         | 2.19%   |
| Intel Wireless 7260                                                           | 3         | 2.19%   |
| Intel WiFi Link 5100                                                          | 3         | 2.19%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 2.19%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 2.19%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 3         | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 1.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.46%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.46%   |
| ZyDAS ZD1211B 802.11g                                                         | 1         | 0.73%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1         | 0.73%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.73%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.73%   |
| TP-Link 802.11ac NIC                                                          | 1         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.73%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.73%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.73%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                       | 1         | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 83        | 47.16%  |
| Intel                    | 62        | 35.23%  |
| Broadcom                 | 9         | 5.11%   |
| Qualcomm Atheros         | 8         | 4.55%   |
| ASIX Electronics         | 4         | 2.27%   |
| Nvidia                   | 3         | 1.7%    |
| Broadcom Limited         | 2         | 1.14%   |
| Aquantia                 | 2         | 1.14%   |
| MediaTek                 | 1         | 0.57%   |
| Marvell Technology Group | 1         | 0.57%   |
| DisplayLink              | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 37.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 9.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.89%   |
| Intel I211 Gigabit Network Connection                             | 6         | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.78%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.67%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.11%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.11%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.11%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.11%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.11%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.11%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.56%   |
| MediaTek moto g22                                                 | 1         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 163       | 53.97%  |
| WiFi     | 133       | 44.04%  |
| Modem    | 5         | 1.66%   |
| Unknown  | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 50.26%  |
| Ethernet | 97        | 49.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 100       | 55.25%  |
| 1     | 75        | 41.44%  |
| 3     | 4         | 2.21%   |
| 0     | 2         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 142       | 78.02%  |
| Yes  | 40        | 21.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 48.51%  |
| Realtek Semiconductor           | 8         | 7.92%   |
| Qualcomm Atheros Communications | 8         | 7.92%   |
| Cambridge Silicon Radio         | 6         | 5.94%   |
| Apple                           | 6         | 5.94%   |
| Broadcom                        | 5         | 4.95%   |
| ASUSTek Computer                | 4         | 3.96%   |
| MediaTek                        | 3         | 2.97%   |
| Realtek                         | 2         | 1.98%   |
| Ralink Technology               | 2         | 1.98%   |
| Lite-On Technology              | 2         | 1.98%   |
| IMC Networks                    | 2         | 1.98%   |
| Hewlett-Packard                 | 2         | 1.98%   |
| Foxconn International           | 1         | 0.99%   |
| Dell                            | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 21.78%  |
| Intel AX201 Bluetooth                               | 8         | 7.92%   |
| Realtek Bluetooth Radio                             | 7         | 6.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 6.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 5.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 4.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 3.96%   |
| MediaTek Wireless_Device                            | 3         | 2.97%   |
| Intel AX200 Bluetooth                               | 3         | 2.97%   |
| Apple Bluetooth USB Host Controller                 | 3         | 2.97%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.98%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.98%   |
| Intel Bluetooth Device                              | 2         | 1.98%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.98%   |
| Apple Bluetooth Host Controller                     | 2         | 1.98%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.99%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.99%   |
| Ralink CSR BS8510                                   | 1         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.99%   |
| Intel AX210 Bluetooth                               | 1         | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.99%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.99%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.99%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.99%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.99%   |
| ASUS BCM20702A0                                     | 1         | 0.99%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 126       | 41.72%  |
| AMD                                  | 58        | 19.21%  |
| Nvidia                               | 56        | 18.54%  |
| C-Media Electronics                  | 6         | 1.99%   |
| Texas Instruments                    | 5         | 1.66%   |
| Yamaha                               | 4         | 1.32%   |
| M-Audio                              | 3         | 0.99%   |
| Logitech                             | 3         | 0.99%   |
| JMTek                                | 3         | 0.99%   |
| QinHeng Electronics                  | 2         | 0.66%   |
| PreSonus Audio Electronics           | 2         | 0.66%   |
| Mackie Designs                       | 2         | 0.66%   |
| Generalplus Technology               | 2         | 0.66%   |
| Focusrite-Novation                   | 2         | 0.66%   |
| ASUSTek Computer                     | 2         | 0.66%   |
| ZOOM                                 | 1         | 0.33%   |
| Yealink Network Technology           | 1         | 0.33%   |
| Xilinx                               | 1         | 0.33%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.33%   |
| Textech International                | 1         | 0.33%   |
| Tenx Technology                      | 1         | 0.33%   |
| TEAC                                 | 1         | 0.33%   |
| Studiologic                          | 1         | 0.33%   |
| SteelSeries ApS                      | 1         | 0.33%   |
| Samson Technologies                  | 1         | 0.33%   |
| Plantronics                          | 1         | 0.33%   |
| MIDITECH                             | 1         | 0.33%   |
| Medeli Electronics                   | 1         | 0.33%   |
| Mark of the Unicorn                  | 1         | 0.33%   |
| KTMicro                              | 1         | 0.33%   |
| Jieli Technology                     | 1         | 0.33%   |
| Harman                               | 1         | 0.33%   |
| Ensoniq                              | 1         | 0.33%   |
| Dell                                 | 1         | 0.33%   |
| Creative Technology                  | 1         | 0.33%   |
| Behringer.......                     | 1         | 0.33%   |
| BEHRINGER International              | 1         | 0.33%   |
| Audient                              | 1         | 0.33%   |
| Apple                                | 1         | 0.33%   |
| Alesis                               | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 17        | 4.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15        | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 13        | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 13        | 3.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12        | 3.39%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10        | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9         | 2.54%   |
| AMD Starship/Matisse HD Audio Controller                                          | 9         | 2.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8         | 2.26%   |
| Intel Sunrise Point-LP HD Audio                                                   | 8         | 2.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8         | 2.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8         | 2.26%   |
| AMD FCH Azalia Controller                                                         | 7         | 1.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.69%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 1.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 1.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 4         | 1.13%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 1.13%   |
| Intel 200 Series PCH HD Audio                                                     | 4         | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                          | 4         | 1.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4         | 1.13%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 1.13%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.85%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3         | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 0.85%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3         | 0.85%   |
| QinHeng Electronics CH345 MIDI adapter                                            | 2         | 0.56%   |
| PreSonus Audio Electronics Studio 24c                                             | 2         | 0.56%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2         | 0.56%   |
| Nvidia High Definition Audio Controller                                           | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 20.64%  |
| SK hynix            | 44        | 20.18%  |
| Kingston            | 25        | 11.47%  |
| Micron Technology   | 21        | 9.63%   |
| Unknown             | 16        | 7.34%   |
| Crucial             | 14        | 6.42%   |
| Corsair             | 12        | 5.5%    |
| G.Skill             | 10        | 4.59%   |
| Patriot             | 6         | 2.75%   |
| Ramaxel Technology  | 4         | 1.83%   |
| Nanya Technology    | 3         | 1.38%   |
| Timetec             | 2         | 0.92%   |
| A-DATA Technology   | 2         | 0.92%   |
| Wodposit            | 1         | 0.46%   |
| Unifosa             | 1         | 0.46%   |
| Transcend           | 1         | 0.46%   |
| Smart               | 1         | 0.46%   |
| S                   | 1         | 0.46%   |
| PNY                 | 1         | 0.46%   |
| OCZ                 | 1         | 0.46%   |
| M                   | 1         | 0.46%   |
| HBS                 | 1         | 0.46%   |
| Goldkey             | 1         | 0.46%   |
| Elpida              | 1         | 0.46%   |
| Aeneon              | 1         | 0.46%   |
| 0194808980CE        | 1         | 0.46%   |
| Unknown             | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.24%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.24%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.24%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 3         | 1.24%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s       | 3         | 1.24%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s      | 3         | 1.24%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s   | 3         | 1.24%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2         | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 2         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 2         | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.83%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 2         | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.83%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s               | 2         | 0.83%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 0.83%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.83%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.83%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 2         | 0.83%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2         | 0.83%   |
| Patriot RAM 2400 C15 Series 16GB SODIMM DDR4 2667MT/s     | 2         | 0.83%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 2         | 0.83%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 2         | 0.83%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 2         | 0.83%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2400MT/s    | 1         | 0.41%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                 | 1         | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR                         | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                  | 1         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s          | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1         | 0.41%   |
| Unknown RAM Module 256MB DIMM DDR                         | 1         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                   | 1         | 0.41%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                  | 1         | 0.41%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s              | 1         | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                | 1         | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR                        | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 82        | 44.32%  |
| DDR4    | 72        | 38.92%  |
| DDR2    | 12        | 6.49%   |
| SDRAM   | 5         | 2.7%    |
| Unknown | 5         | 2.7%    |
| LPDDR4  | 3         | 1.62%   |
| DDR     | 3         | 1.62%   |
| LPDDR3  | 2         | 1.08%   |
| LPDDR5  | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 91        | 49.73%  |
| DIMM         | 77        | 42.08%  |
| Row Of Chips | 11        | 6.01%   |
| RIMM         | 1         | 0.55%   |
| FB-DIMM      | 1         | 0.55%   |
| Chip         | 1         | 0.55%   |
| Unknown      | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 67        | 31.9%   |
| 4096  | 66        | 31.43%  |
| 2048  | 26        | 12.38%  |
| 16384 | 25        | 11.9%   |
| 32768 | 12        | 5.71%   |
| 1024  | 11        | 5.24%   |
| 512   | 2         | 0.95%   |
| 256   | 1         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 57        | 28.36%  |
| 3200    | 21        | 10.45%  |
| 2667    | 17        | 8.46%   |
| 1333    | 15        | 7.46%   |
| 2400    | 12        | 5.97%   |
| 2133    | 9         | 4.48%   |
| 1334    | 8         | 3.98%   |
| 667     | 8         | 3.98%   |
| 3600    | 7         | 3.48%   |
| 1866    | 5         | 2.49%   |
| 3266    | 4         | 1.99%   |
| 1800    | 4         | 1.99%   |
| 1066    | 4         | 1.99%   |
| 800     | 4         | 1.99%   |
| 4267    | 3         | 1.49%   |
| Unknown | 3         | 1.49%   |
| 4199    | 2         | 1%      |
| 2933    | 2         | 1%      |
| 1867    | 2         | 1%      |
| 1067    | 2         | 1%      |
| 533     | 2         | 1%      |
| 6400    | 1         | 0.5%    |
| 3500    | 1         | 0.5%    |
| 3466    | 1         | 0.5%    |
| 3000    | 1         | 0.5%    |
| 2934    | 1         | 0.5%    |
| 2800    | 1         | 0.5%    |
| 2666    | 1         | 0.5%    |
| 2472    | 1         | 0.5%    |
| 1639    | 1         | 0.5%    |
| 1632    | 1         | 0.5%    |

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
| Chicony Electronics                    | 21        | 19.63%  |
| Logitech                               | 8         | 7.48%   |
| IMC Networks                           | 8         | 7.48%   |
| Microdia                               | 7         | 6.54%   |
| Suyin                                  | 6         | 5.61%   |
| Sunplus Innovation Technology          | 6         | 5.61%   |
| Realtek Semiconductor                  | 6         | 5.61%   |
| Syntek                                 | 5         | 4.67%   |
| Apple                                  | 4         | 3.74%   |
| Quanta                                 | 3         | 2.8%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.8%    |
| Samsung Electronics                    | 2         | 1.87%   |
| Philips (or NXP)                       | 2         | 1.87%   |
| Microsoft                              | 2         | 1.87%   |
| Lite-On Technology                     | 2         | 1.87%   |
| Bison Electronics                      | 2         | 1.87%   |
| Acer                                   | 2         | 1.87%   |
| Xiongmai                               | 1         | 0.93%   |
| ViewSonic                              | 1         | 0.93%   |
| ViewQuest Technologies                 | 1         | 0.93%   |
| Trust                                  | 1         | 0.93%   |
| Sweex                                  | 1         | 0.93%   |
| Sunplus IT                             | 1         | 0.93%   |
| Sonix Technology                       | 1         | 0.93%   |
| Silicon Motion                         | 1         | 0.93%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.93%   |
| Ricoh                                  | 1         | 0.93%   |
| Razer USA                              | 1         | 0.93%   |
| MacroSilicon                           | 1         | 0.93%   |
| Jieli Technology                       | 1         | 0.93%   |
| Intel                                  | 1         | 0.93%   |
| Importek                               | 1         | 0.93%   |
| HRY                                    | 1         | 0.93%   |
| Dynex                                  | 1         | 0.93%   |
| Dell                                   | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                          | 5         | 4.63%   |
| Chicony Integrated Camera                         | 5         | 4.63%   |
| IMC Networks Integrated Camera                    | 4         | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]              | 3         | 2.78%   |
| Suyin USB 2.0 Camera                              | 2         | 1.85%   |
| Suyin Asus Integrated Webcam                      | 2         | 1.85%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 1.85%   |
| Sunplus HD WebCam                                 | 2         | 1.85%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2         | 1.85%   |
| Realtek Lenovo EasyCamera                         | 2         | 1.85%   |
| Microdia Integrated_Webcam_HD                     | 2         | 1.85%   |
| Logitech Webcam C270                              | 2         | 1.85%   |
| Chicony HP HD Camera                              | 2         | 1.85%   |
| Chicony HD Webcam                                 | 2         | 1.85%   |
| Chicony HD User Facing                            | 2         | 1.85%   |
| Apple FaceTime HD Camera (Built-in)               | 2         | 1.85%   |
| Xiongmai web camera                               | 1         | 0.93%   |
| ViewSonic PC Camera                               | 1         | 0.93%   |
| ViewQuest Ability GABB Webcam                     | 1         | 0.93%   |
| Trust AUKEY PC-LM1A Webcam                        | 1         | 0.93%   |
| Sweex WC060 Series HD Webcam                      | 1         | 0.93%   |
| Suyin HP Webcam                                   | 1         | 0.93%   |
| Suyin HP TrueVision HD Integrated Webcam          | 1         | 0.93%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1         | 0.93%   |
| Sunplus HD 720P webcam                            | 1         | 0.93%   |
| Sunplus Dell HD Webcam                            | 1         | 0.93%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 0.93%   |
| Silicon Motion WebCam SCB-1100N                   | 1         | 0.93%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1         | 0.93%   |
| Ricoh Sony Vaio Integrated Webcam                 | 1         | 0.93%   |
| Realtek VGA WebCam                                | 1         | 0.93%   |
| Realtek MTD camera                                | 1         | 0.93%   |
| Realtek Integrated_Webcam_HD                      | 1         | 0.93%   |
| Realtek HP Wide Vision HD Camera                  | 1         | 0.93%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1         | 0.93%   |
| Quanta ov9734_techfront_camera                    | 1         | 0.93%   |
| Quanta HP Webcam                                  | 1         | 0.93%   |
| Quanta HP TrueVision HD Camera                    | 1         | 0.93%   |
| Philips (or NXP) Webcam SPC530NC                  | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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
| 0     | 129       | 71.27%  |
| 1     | 46        | 25.41%  |
| 2     | 5         | 2.76%   |
| 3     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 30.91%  |
| Graphics card            | 12        | 21.82%  |
| Chipcard                 | 9         | 16.36%  |
| Net/wireless             | 7         | 12.73%  |
| Camera                   | 3         | 5.45%   |
| Sound                    | 2         | 3.64%   |
| Multimedia controller    | 2         | 3.64%   |
| Unassigned class         | 1         | 1.82%   |
| Modem                    | 1         | 1.82%   |
| Communication controller | 1         | 1.82%   |

